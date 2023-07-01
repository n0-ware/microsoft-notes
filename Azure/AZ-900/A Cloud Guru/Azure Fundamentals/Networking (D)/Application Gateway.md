---
tags:
topic: "networking"
subTopic: "app_gateway"
source: "guru"
family: "Azure"
imageNameKey: "Azure_app_gateway"
cert: "AZ-900"
---
# Application Gateway

_Creation Date:_ `=this.file.cday` 
_Last Modified:_ `=this.file.mday`

Application Gateway is an Azure service that adds a layer of application-level routing on top of the traditional network load balancing.

- It routes incoming requests based on the type, including data format, URI, and host header from any HTTP request.
- It ***does not*** consider IP/port, focusing instead on data.

## Benefits

- **Scalability**: An Application Gateway can be scaled to accommodate changes in traffic.
- **Encryption**: It can be enabled to adhere to security policies and disabled on the back end for increased performance.
- **Zone Redundancy**: It can span multiple availability zones for fault tolerance.
- **Multi-Site Hosting**: Allows usage of the same Application Gateway for over 100 websites.