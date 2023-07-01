---
tags:
topic: "networking"
subTopic: "virtual_network"
source: "guru"
family: "Azure"
cert: "AZ-900"
---
# Virtual Network

_Creation Date:_ `=this.file.cday` _Last Modified:_ `=this.file.mday`

The Virtual Network is a fundamental building block in Azure.

## Azure Virtual Network (VNET)

- Allows both public and private network communications within Azure resources.
- Incorporates familiar networking concepts like subnets, firewalls, and routes, in a virtual format known as Software-Defined Networking (SDN).
- Enables public access and can extend private networking to other networks.

## Deployment

- Resembles an actual on-premises network.
- Every subscription and every region can have multiple virtual networks.
- Networks can be combined and structured to achieve complex network designs.

## Key Terms

- **Subnets**: Segments resources for precise organization and security control.
- **Peering & VPN Express Routes**: Connects to other Azure Vnets, across regions, on-premises networks, or in other clouds.
- **Network Security Groups**: Firewalls control access to the Vnet by defining allowed network protocols, ports, or secure locations.

## Scalability

- Vnets (and therefore address space) can scale as needed.

## High Availability

- Peering with load balancers or VPN gateways increases availability.
- Peering connects two or more Vnets securely, without crossing the internet.

## Isolation

- Resource isolation enables granular and flexible security.