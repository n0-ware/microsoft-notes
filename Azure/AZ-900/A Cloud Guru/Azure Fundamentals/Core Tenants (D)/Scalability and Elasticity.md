---
tags:
topic: "fundamentals"
subTopic: "scalability and elasticity"
source: "guru"
family: "Azure"
cert: "AZ-900"
---
# Scalability and Elasticity
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

## Scalability

> The ability to increase the count or size of existing resources.
> Key tenant of controlling **cost**

> Scalability is the ability of a system to handle increased load. Elasticity is the ability to dynamically scale to meet demand.

> From Microsoft...*Scalability is the ability of a system to handle increased load. Services covered by [Azure Autoscale](https://azure.microsoft.com/features/autoscale) can scale automatically to match demand to accommodate workload. These services scale out to ensure capacity during workload peaks and return to normal automatically when the peak drops.*

- Scale out/in = increase count of servers (horizontal)
	- The majority scaling in the cloud is horizontal
	- **Non-Disruptive Change**
- Scale up/down = increase SIZE of instance (Vertical)
	- **Disruptive Change**
- Generally requires being behind some sort of load balancer

## Elasticity

> The ability to increase the count or size of existing workflows in response to varying needs in your traffic or load, or in the type of resources you are processing.

> From Microsoft...  *Elastic computing is the ability to quickly expand or decrease computer processing, memory, and storage resources to meet changing demands without worrying about capacity planning and engineering for peak usage. Typically controlled by system monitoring tools, elastic computing matches the amount of resources allocated to the amount of resources actually needed without disrupting operations. With cloud elasticity, a company avoids paying for unused capacity or idle resources and doesn’t have to worry about investing in the purchase or maintenance of additional resources and equipment.*

- This includes the ability to scale in both directions, in and out, up and down
- It can be manual or automated
- The key concept being changes in your workload
- Core tenant of paying only for what you use. Scale back down. we may start with one 