---
tags:
topic: "networking"
subTopic: "network_load_balancer"
source: "guru"
family: "Azure"
imageNameKey: "Azure_network_load_balancer"
cert: "AZ-900"
---
# Network Load Balancer

_Creation Date:_ `=this.file.cday` _Last Modified:_ `=this.file.mday`

A Network Load Balancer distributes incoming network flows that arrive on its front-end to the backend instances according to predefined rules and health probes.

- Incoming flows originate from the public internet or local network.
- The front-end is the initial access point for all traffic.
- The backend pool contains the virtual machine instances designated for the traffic.
- Rules and health probes ensure backend instances are healthy and ready to receive data.