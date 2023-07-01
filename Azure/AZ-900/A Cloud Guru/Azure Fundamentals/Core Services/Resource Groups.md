---
tags:
topic: "core_services"
subTopic: "resource_groups"
source: "guru"
family: "Azure"
imageNameKey: "Azure_core_services"
cert: "AZ-900"
---
# Resource Groups
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

- ALL resources are within a resource group
- BUT resource groups themselves are not resources

## Core

- A resource exists in only one resource group
- Add or remove
- Move a resource
- Can be across multiple regions
- Access control friendly
- Resources can interact across resource groups
- MUST have a location for meta data
- **Unlike AWS the resource groups allow for ALL of the resources within that group to be deleted, much like CloudFormation**
	- Provided there are no "locked" resources in use by another service