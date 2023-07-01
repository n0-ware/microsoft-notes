---
tags:
topic: "security"
subTopic: "network_security"
source: "guru"
family: "Azure"
imageNameKey: "Azure_network_security"
cert: "AZ-900"
---
# Network Security

> _Creation Date:_ `=this.file.cday` 
> _Last Modified:_ `=this.file.mday`

Azure provides various tools and services for network security.

## Azure Firewall

- Implements rule-based access policies.
- Manages traffic according to defined rules.
- Offers several variations for flexible configuration.
- Serves as a critical component for protecting your Azure resources.

## Distributed Denial of Service Attacks

1. "Distributed" refers to a large number of Internet-connected devices sending connections simultaneously.
2. Azure's DDoS Protection Service provides robust defense mechanisms.
3. Azure's global infrastructure ensures no downtime during DDoS attacks.

## Network Security Groups

See [[Network Security Groups]]

- Acts as a resource firewall.
- Allows setting rules for who can connect, what they can connect to, and from where they can connect.
- Adds an extra layer of security ("NSG") to VMs.
- Generally, VNets are secured behind the firewall.

## Application Security Groups

1. Focused on protecting application infrastructure, with emphasis on the application's security rather than a specific IP endpoint.
2. Extends Network Security Groups by grouping VMs and virtual networks into logical application groups, enabling application security implementation at scale.
