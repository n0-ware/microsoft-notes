---
tags:
topic: "compute"
subTopic: "virtual machines"
source: "guru"
family: "Azure"
cert: "AZ-900"
---
# Virtual Machines
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

> IaaS


-  Virtual machines have all the exact same components as a physical machine, except they are virtualized based on the actual hardware components they're based on.
- Virtual machines fall into the Infrastructure as a Service section, meaning we are responsible for everything above the operating system through applications.


Why not use a managed service?

1. Flexibility is key
	1. Despite the benefits of running on a managed service, there are limits to your flexibility, However, with the VM you can do whatever you want
	2. This makes the tradeoff flexibility versus less management.

## Concepts

- All Azure VM's are servers of some kind, whether Linux or Windows
- Nothing new from AWS in that regard, or in how they define network cards, discs, processors, RAM, virtual RAM and operating systems
- Primary workhorse and Azure
- Virtual Machines are the highest cost driver of most Azure deployments.

## Key Advantages

**Availability, set**
- VM replication, also known as copies
- Replicating VMS means better fault tolerance
- When VMS go down, a new copy can take its place in line.

**Scale Sets**
- Similar to Auto Scaling Groups
- Scaling copies the application's
- When paired with a load balancer, you get scaling and elasticity and increased availability and redundancy.

## Creating

- Resource Group within chosen subscription
- Note the sets
	- Availability and Scaling
- Various hard drive types
- Both user data AND custom data