---
tags:
topic: "networking"
subTopic: "summary"
source: "guru"
family: "Azure"
imageNameKey: "Azure_summary"
cert: "AZ-900"
---
# Summary - Networking

> _Creation Date:_ `=this.file.cday` 
> _Last Modified:_ `=this.file.mday`

## Application Gateway

- Layer of application-level routing on top of the traditional load balancing.
- Routes incoming requests based on type, not considering IP/port.
- Scalable, supports encryption, spans multiple availability zones for fault tolerance, and enables multi-site hosting.

## Content Delivery Network (CDN)

- Speeds up websites and resource loading by caching data at local edge nodes.
- Increases performance, supports scalability, and ensures requests stay near the user.

## Express Route

- Provides a high-speed, private connection directly to Azure.
- Ideal for hosting data on an on-premises network with high availability requirements or frequent large-scale data migrations.

## Network Load Balancer

- Distributes incoming network flows to backend instances based on predefined rules and health probes.
- Handles traffic originating from the public internet or local network.

## Virtual Network (VNET)

- Allows both public and private network communications within Azure resources.
- Incorporates subnets, firewalls, and routes in a virtual format, known as Software-Defined Networking (SDN).
- Networks can be combined and structured to achieve complex designs.
- Supports scalability, high availability via peering with load balancers or VPN gateways, and resource isolation for enhanced security.

## VPN Gateway

- Facilitates secure communication between multiple networks, either on-premises or in Azure.
- Combines a Virtual Network Gateway with a VPN to create a VPN Gateway.
- Handles secure and encrypted traffic flow between on-premises networks and the cloud.

