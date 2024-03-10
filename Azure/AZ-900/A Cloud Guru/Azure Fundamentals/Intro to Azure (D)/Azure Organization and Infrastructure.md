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

> _Creation Date:_ `=this.file.cday` _Last Modified:_ `=this.file.mday`

Azure offers an extensive set of tools and infrastructure components to facilitate various computing needs. This section provides an overview of Azure's organizational structure and infrastructure elements.

## What is Azure?

Azure is Microsoft's **public cloud computing platform**, offering:

- Over 200 individual products/services.
- Capabilities to build, manage, and run applications on a **global infrastructure**, covering:
    - **IaaS (Infrastructure as a Service)**
    - **PaaS (Platform as a Service)**: Managed Services
    - **SaaS (Software as a Service)**: Managed Services
- A supplement or potential replacement for on-premises computing services.

> **Note**: Azure operates on a "pay-as-you-go" pricing model, promoting OpEx (Operational Expense) instead of CapEx (Capital Expense).

## Global Infrastructure
> See [[Azure/AZ-900/A Cloud Guru/Azure Fundamentals/Intro to Azure (D)/Regions and Availability Zones| | Regions and Availability Zones]]

Azure's expansive global datacenter infrastructure differentiates between regions and availability zones:

- **Region**: A group of data centers in a specific geographic location, like Central US or South India.
    - Benefits: High availability, fault tolerance, proximity to users, and protection against regional outages.
- **Availability Zone (AZ)**: Unique locations within a region, often comprising multiple data centers.
    - Benefits: Offers fault tolerance. Deploying resources across zones helps negate the risk of a single point of failure (SPOF).

> **Key Takeaway**: AZs and Regions form the foundation of Azure's _high availability_, _fault tolerance_, and overall **resiliency**.

## Azure Services

Azure services span three main levels:

1. **Platform Services** (Highest Level)
2. **Infrastructure Services**
3. **Datacenter Infrastructure**

Azure provides a multitude of solutions across diverse categories, from Traditional IT to IaaS, PaaS, and SaaS.

![[Azure/AZ-900/A Cloud Guru/Azure Fundamentals/Intro to Azure (D)/Photos/1_Azure_Intro.png| 800 ]]

Azure offers various interfaces for interaction, including:

- Azure Portal
- Azure PowerShell
- Azure CLI
- REST Clients
- SDKs

All interactions with services occur via the **Azure Resource Manager (ARM)**, acting as a unified management and authentication hub.

![[Azure/AZ-900/A Cloud Guru/Azure Fundamentals/Intro to Azure (D)/Photos/2_Azure_Intro.png| 800 ]]

## Resource Hierarchy

Understanding Azure's resource hierarchy helps in organization, billing tracking, and access control. It's structured as:

- **Management Group**: Can contain multiple subscriptions.
    - **Subscription**: A billing and access isolation boundary.
        - **Resource Group**: Aggregates resources for shared purposes or lifecycle phases.
            - **Resources**: Any Azure entity, irrespective of its type.

![[Azure/AZ-900/A Cloud Guru/Azure Fundamentals/Intro to Azure (D)/Photos/3_Azure_Intro.png| 800 ]]

Notable points about the hierarchy:

- It follows a parent-child relationship, essential for inheritance.
- Access and policies are inherited, ensuring a central management approach.
- Parents can have multiple children, but a child can only have one parent.
- This structure is analogous to an OS file structure.

|Name|Description|Notes|
|---|---|---|
|**Tenant**|A unique organizational instance of Azure AD|Manages users in a unified "bucket".|
|**Management Groups**|Optional grouping component|Enables central management across multiple subscriptions.|
|**Subscriptions**|Defines primary billing and access isolation boundaries|Each subscription possesses its own billing agreement.|
|**Resource Groups**|Bundles resources for similar goals or lifecycles|All Azure resources must belong to a resource group.|
|**Resources**|Refers to any Azure creation, regardless of its type||

![[Azure/AZ-900/A Cloud Guru/Azure Fundamentals/Intro to Azure (D)/Photos/4_Azure_Intro.png| 800 ]]