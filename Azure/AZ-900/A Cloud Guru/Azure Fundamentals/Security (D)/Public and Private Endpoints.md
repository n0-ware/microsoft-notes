---
tags:
topic: "security"
subTopic: "pub_private_endpoints"
source: "guru"
family: "Azure"
imageNameKey: "Azure_pub_private_endpoints"
cert: "AZ-900"
---
# Public and Private Endpoints

> _Creation Date:_ `=this.file.cday` 
> _Last Modified:_ `=this.file.mday`

By default, most managed PaaS services are accessible over the public Internet.

- Note: Even when accessing managed services from your VNet, the communication still occurs over the public internet.
- Public endpoints are exposed over the Internet, but this does not mean that the resources are openly available.
- Proper authorization and authentication are typically required due to the sensitivity of the data.

## Solutions

- Good: Service Endpoints
- Better: Private Endpoints

## Service Endpoints

- Connects your VNet subnet to an Azure PaaS privately.
- The traffic is routed over the Azure backbone network.
- The managed services can be configured to accept traffic only from designated VNets and IPs.

### Limitations

- Provides access only to VNets, thus not allowing private on-premises access.
- Requires public IP for on-premises access, which needs a public endpoint on the PaaS.
- Grants access to the entire managed services, not just to a single storage account, for instance.

## Private Endpoints

- Managed network interface within a VNet subnet, providing a private connection to a specific instance of a service.
- Accessible over VPN/ExpressRoute-connected on-premises networks, as well as for peered VNets.
- Offers the option to completely disable public access.