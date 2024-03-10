---
tags:
topic: "exam"
subTopic: "questions"
source: "guru"
family: "Azure"
imageNameKey: "Azure_questions"
cert: "AZ-900"
---
# Questions to Review
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

**Question**: Which cloud attribute is defined by knowing your application will perform as expected regardless of customer demand?
- *My Answer*: Reliability - Reliability refers more to the resiliency of an application even in the case of partial or wide-scale failures or outages.
- *Correct Answer*: **Predictability** - Predictability is knowing that your application will perform at a consistent level. This is achieved through a combination of autoscaling, high availability, and load balancing. Though not noted in the question, it also describes transparency in costs.

**Question**: You have an on-premises application that processes incoming queue messages and records the data to a log file. You migrate this application to an Azure function app. Which cloud service model would your application then be considered after this migration?
- *My Answer*: INCORRECT (PaaS) - Platform as a Service (PaaS) is a complete development and deployment environment in the cloud, with resources that enable you to deliver everything from simple cloud-based apps to sophisticated, cloud-enabled enterprise applications. An Azure function app would not be considered a PaaS service.
- *Correct Answer*: **CORRECT (Serverless)** - Serverless computing is the abstraction of servers, infrastructure, and operating systems. When you build serverless apps, you don't need to provision and manage any servers, so you don't have to worry about infrastructure. Serverless computing is driven by the reaction to events and triggers happening in near-real time in the cloud.

**Question**: What is the purpose of Application Insights?
- *My Answer*: Gain insights from stored logs and metrics collected by Azure Monitor via queries
	- This describes Log Analytics.
- *Correct Answer*: **Provides insights such as customer behavior, performance bottlenecks, and web application errors**
	- Application Insights provides website performance monitoring.

**Question**: Select the cloud concept that is defined by: - Knowing that your application will perform as expected, even under heavy load.
- *My Answer*: High availability
	- While there is some overlap between many of the core cloud concepts, high availability is specifically defined by making sure resources are always _available_, which is carried out by using clusters of identical servers, automatically replacing failed servers, etc.
- *Correct Answer*: **Predictability**
	- Predictability is knowing that your application will always perform as expected regardless of load. While there is some overlap with the concepts of scalability and high availability to achieve this outcome, the concept of being confident of _consistent_ performance is Predictability. 

**Question**: Your company is migrating several types of existing on-premises resources to Azure. You need to migrate the functionality of your existing on-premises file server to Azure, which will act as a mapped drive location for multiple office desktops. This solution needs to use the Server Message Block (SMB) shares for file storage and management. What solution should you use?
- *My Answer*: ****
	- Managed disks act as hosted VM disks used by Azure VMs. It is not used as a cloud-based SMB share for non-Azure resources. Azure Files is the better selection.
- *Correct Answer*: **Azure Files**
	- Azure Files uses SMB shares within a storage account to act as a cloud-based network file server.

**Question**: You need to create a virtual machine with the following disk requirements: - Hold up to 64TB in a single disk - Highest possible performance with sub-millisecond latency Which disk type should you select for your virtual machine?
- *My Answer*: Premium SSD
	- While Premium SSD disk types offer higher performance than most of the other disk type options, Ultra disk types offer even higher performance and go up to 64TB in size.
- *Correct Answer*: **Ultra**
	- Ultra disks are the most expensive, yet highest-performing disk types available for Azure virtual machines. They support up to 64TB on a single disk.

**Question**: What describes the cloud attribute of management?
- *My Answer*: Having full control, or even choosing how much control you want, over your cloud resources' security configuration
	- This definition describes the security attribute.
- *Correct Answer*: **How you interact with and implement different cloud-based resources**
	- Manageability has two aspects: 1. How you create and manage resources, which includes autoscaling, template-based deployments, and monitoring/alerts. 2. How you interact with your cloud environments, including via the web portal, command line, and programmatic APIs.

**Question**: Define the concept of "scalability."
- *My Answer*: A cloud service that responds quickly when demand increases and needs to be manually scaled down when demand decreases.
	- Scalability is the ability of a system to handle increased load. Elasticity is the ability to dynamically scale to meet demand.
- *Correct Answer*: **The ability of a system to handle increased load**
	- Microsoft's official definition of scalability is: *"Scalability is the ability of a system to handle increased load."*\* Elasticity is the ability to dynamically scale to meet demand. Scaling can be dynamic or manual (such as, often, the case for vertical scaling). Reference: [Design for Scaling](https://learn.microsoft.com/en-us/azure/architecture/framework/scalability/design-scale "null")

**Question**: What is the purpose of Azure Blueprints?
- *My Answer*: Automated and repeatable resource deployment in Azure.
	- This is a tricky one. This describes ARM templates, which only automate resource deployment. Azure Blueprints, by comparison, is able to deploy multiple ARM templates (resources), plus policies, role assignments, and more.
- *Correct Answer*: **Automated and repeatable environment setup in Azure.**
	- Azure Blueprints provides automated and repeatable environment setup in Azure. It is able to implement: - Role assignments - Policy assignments - Azure Resource Manager templates (ARM templates) - Resource groups

**Question**: You are the Azure Administrator for Radio Gaga, LTD. You have a resource group named RG-RG and need to ensure no other administrators can create virtual networks in this resource group. What can you implement to accomplish this?
- *My Answer*: Locks
	- A resource group lock would prevent anyone from deleting the RG-RG resource group, but it would not prevent them from creating virtual networks in the resource group. As an administrator, you may need to lock a subscription, resource group, or resource to prevent other users in your organization from accidentally deleting or modifying critical resources. You can set the lock level to CanNotDelete or ReadOnly. In the portal, the locks are called Delete and Read-only, respectively. Unlike role-based access control, you use management locks to apply a restriction across all users and roles. [Lock resources to prevent unexpected changes](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-lock-resources "null")
- *Correct Answer*: **Azure Policy**
	- Azure Policy is used to enforce different rules and effects over your resources, such as limiting what actions different administrators can perform within your RG-RG resource group. The other answers are incorrect: Access Control can be used to prevent the creation of Azure resources, but improper use could prevent required system access from other administrators, so this is not the best selection. Locks can be used on a resource to prevent accidental deletion or modification of a resource group, for example. Properties are typically read-only values for an Azure resource, such as its resource ID, subscription, resource group, and other information. Reference: [Overview of Azure Policy - Azure Policy | Microsoft Docs](https://docs.microsoft.com/en-us/azure/governance/policy/overview "null")

**Question**: What are Azure Resource Manager (ARM) templates?
- *My Answer*: A declarative method to orchestrate the deployment of resource templates and other artifacts such as role assignments, policy assignments, resource templates, and resource groups
	- This describes Azure Blueprints
- *Correct Answer*: **Azure's native Infrastructure-as-Code (IaC) solution**
	- ARM templates are Azure's native Infrastructure-as-Code (IaC) solution that can consistently and automatically deploy the same environments that are defined in code format.

**Question**:
- *My Answer*:
- *Correct Answer*:

**Question**:
- *My Answer*:
- *Correct Answer*:

**Question**:
- *My Answer*:
- *Correct Answer*:

**Question**:
- *My Answer*:
- *Correct Answer*:

**Question**:
- *My Answer*:
- *Correct Answer*:

**Question**:
- *My Answer*:
- *Correct Answer*:

