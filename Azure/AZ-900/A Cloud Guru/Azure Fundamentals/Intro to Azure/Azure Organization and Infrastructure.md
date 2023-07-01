---
tags:
topic: "introduction"
subTopic: "org and infra"
source: "guru"
family: "Azure"
cert: "AZ-900"
imageNameKey: "Azure_Intro"
---
# Azure Organization and Infrastructure
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`


- What is it? 
- Global infrastructure
- Azure Services
- Resource Hierarchy and Organization
- Identify and Access Management
- Monitoring Azure

## What is Azure

- Microsoft's **public cloud computing platform**
- 200 individual products/services
- Build, manage, run apps on the **global** infra
	- IaaS
	- PaaS (Managed Services)
	- SaaS (Manage Services)
- Supplement/replace on-prem computing services
- **Remember** "pay as you go" pricing. No up front, pay per second. Operational Expense (opex). Opposite is "capital expense" or "capex"

## Global Infrastructure

> Azure's global datacenter infrastructure

- Regions vs availability zones
	- Azure is global with many regions
- Breakdown of terms
	- **Region** = Group of datacenters in a single geographic location = Central US, South India, etc.
		- **Region** = High-availability and fault tolerance = Be close to users and defend against regional outages 
	- **Availability Zones** = One of several unique locations in a region = One or more individual datacenters per zone, with each zone being self-contained and sustainable. 
		- **AZ** = Fault tolerance **only** = Deply resources across zones to prevent SPOF (single point of failure)
		- AZs and Regions are the cornerstone of *high availability* and *fault-tolerance* (**resiliency**)

## Azure Services

1. Platform Services (Highest Level)
2. Infrastructure Services
3. Datacenter Infrastructure

> Categories section lists all of the services. There is a solution for almost everything that needs to be done. 

> This is where you talk about Traditional IT, IaaS, PaaS, SaaS. 

![[1_Azure_Intro.png]]

- Interaction can be done with the Portal, Azure PowerShell, Azure CLI, REST Clients, SDK's, etc. 
- **All service interaction via Azure Resource Manager (ARM)**
	- This is a central management and authentication portal. 

![[2_Azure_Intro.png]]

## Resource Hierarchy

- How do we organize
- How do we track who is paying for what
- How do we limit who has access to different sets of resources?

It goes like this

1. Management group
	1. Subscription
		1. Resource Group
			1. Resources
	2. Subscription
		1. Resource Group
		2. Resource Group
			1. Resources

![[3_Azure_Intro.png]]

**Be aware of the following**

1. Parent child relationship
	1. Fundamental for many but specifically inheritance
2. Access/policies are inherited
3. Central management
4. Parent's can have multiple children, children can only have one parent
5. Similar to OS file structure.


| Name              | Description                                                   | Notes                                                       |
| ----------------- | ------------------------------------------------------------- | ----------------------------------------------------------- |
| Tenant            | Single organization instance of Azure AD                      | Single "bucket" to manage users                             |
| Management Groups | Grouping component (optional)                                 | Central management of multiple subscriptions                |
| Subscriptions     | Primary billing and Access Isolation boundary.                | Each subscription has its own billing agreement.            |
| Resource groups.  | group resources together for similar purposes or life cycles. | All Azure resources are created inside of a resource group. |
| Resources         | Anything created in Azure regardless of type.                                                              |                                                             |

![[4_Azure_Intro.png]]