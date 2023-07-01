---
tags:
topic: "networking"
subTopic: "vpn_gateway"
source: "guru"
family: "Azure"
imageNameKey: "Azure_vpn_gateway"
cert: "AZ-900"
---
# VPN Gateway

_Creation Date:_ `=this.file.cday` _Last Modified:_ `=this.file.mday`

The VPN Gateway facilitates secure communication between multiple networks, either on-premises or in Azure.

## Virtual Network Gateway

- A Virtual Network Gateway is a combination of two or more instances deployed into a specific subnet. These instances manage the infrastructure for the VPN or Express Gateway.
- Combining a Vnet with specific attributes creates unique gateway types.

## VPN Gateway

A VPN Gateway is a type of Virtual Network Gateway that includes two or more dedicated virtual machines.

- Combining a Vnet Gateway with a VPN creates a VPN Gateway.
- VPN Gateways facilitate secure and encrypted traffic flow between on-premises networks and the cloud.
- Understanding the vital component of secure communication with your hybrid gateway is crucial.

### Components

- **Site-to-Site (Multi-Site Available)**: The setup includes a Vnet with an attached VPN Gateway (which gets its own public IP), a secure connection (tunnel) to the on-premises location, and a local VPN Gateway on-premises.