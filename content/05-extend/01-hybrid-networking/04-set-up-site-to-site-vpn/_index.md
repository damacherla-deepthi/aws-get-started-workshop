---
title: 'Establish Site-to-Site VPN Connection with AWS Transit Gateway'
menuTitle: '4. Establish VPN Integration'
disableToc: true
weight: 40
---

{{% comment %}}
Copyright Amazon.com, Inc. or its affiliates. All Rights Reserved.
SPDX-License-Identifier: CC-BY-SA-4.0
{{% /comment %}}

This section provides detailed step-by-step instructions for using AWS Site-to-Site VPN and AWS Transit Gateway as a means to quickly and securely establish network connectivity between your on-premises and AWS environments. 

By following these instructions, you will enable network connectivity between your on-premises environment and the centrally managed development VPC you established earlier in this guide.

Later in this guide, when you set up your test and production VPCs, the steps required to enable those VPCs to reuse your site-to-site VPN connection will be addressed.  The process in your AWS environment will be largely a repeat of the steps in this section that are used to connect your development VPC to your on-premises network.

{{% notice info %}}
**Automated solution:** As you expand the number of VPCs in your AWS environment, you may benefit from implementing the [Serverless Transit Network Orchestrator](https://aws.amazon.com/solutions/implementations/serverless-transit-network-orchestrator/) AWS solution.  This solution automates much of the work required to integrate newly created VPCs with your transit gateway.
{{% /notice %}}

{{% children showhidden="false" %}}