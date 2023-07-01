---
tags:
topic: "security"
subTopic: "summary"
source: "guru"
family: "Azure"
imageNameKey: "Azure_summary"
cert: "AZ-900"
---
# Security Summary

> _Creation Date:_ `=this.file.cday` _Last Modified:_ `=this.file.mday`

## Defense in Depth

A multi-layered defense strategy in Azure, with the following layers of protection:

- Physical.
- Identity and Access.
- Perimeter.
- Network.
- Compute.
- Application.
- Data.

## Network Connectivity Security

- Azure Firewall manages network traffic based on predefined security rules.
- Azure's built-in DDoS protection automatically secures resources from large-scale attacks without downtime.
- Network Security Groups (NSGs) provide a resource-level firewall, defining rules for traffic direction and authorization.

## Public and Private Endpoints

- Most Platform-as-a-Service (PaaS) services in Azure are publicly accessible by default.
- Private endpoints offer secure and private access to these services, with the ability to disable public internet access completely.
- The limitations of service endpoints make private endpoints a superior choice. For instance, service endpoints cannot provide on-premises access or limit access to specific instances of managed services.
- Private endpoints can be accessed over VPNs or peered networks for secure, private connectivity.

## Microsoft Defender for Cloud

- Offers policy-driven resource protection, hygiene monitoring, and threat alerts.
- Provides hybrid capabilities via an agent.
- Can monitor resources across different cloud providers with Azure Arc.

## Azure Key Vault

- Offers secure storage for secrets, keys, and certificates.
- Ensures credentials are securely used without being revealed to other parties or applications.

## Azure Information Protection

- Facilitates secure data sharing both within and outside the network.
- Employs data classification and tagging to control access and track activities.

## Azure Sentinel

- Functions as a centralized Security Information and Event Management (SIEM) solution for Azure.
- Handles data collection, aggregation, normalization, and threat analysis, leaving users to respond to the insights it provides.
- Supports behavioral analytics and integrates with AWS for multi-cloud scenarios.

## Azure Dedicated Hosts

- Provides users with full control over the hardware and OS, without sharing resources with others.
- Allows users to manage their own maintenance schedules.

## Microsoft Defender for Identity

- Monitors and manages user identities both on-premises and in the cloud.
- Establishes user behavior baselines and provides anomaly detection.
- Makes security recommendations based on the user's routine.
- Focuses on the Cyber-Attack Kill Chain stages: reconnaissance, brute force attacks, and privilege escalation.