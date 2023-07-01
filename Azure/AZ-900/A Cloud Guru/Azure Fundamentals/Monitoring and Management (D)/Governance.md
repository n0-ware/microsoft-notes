---
tags:
topic: "monitor_and_manage"
subTopic: "governance"
source: "guru"
family: "Azure"
imageNameKey: "Azure_governance"
cert: "AZ-900"
---
# Governance
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

> Keeping control over your resources, their configurations, etc. 
- Governance refers to the ability from a management level to govern the overall infrastructure, security, compliance, and other related factors of your cloud
	- standardized environments
	- Regulatory requirements
	- Compliance audits.
- Don't let people do whatever they want to or think they should at the time
- Must set guardrails around resources, creation, use etc. 


## Azure Policy

> Governance validates that your organization can achieve it's goals through effective use of IT

- Is a set of rules
- Rules are then aligned around these policies
- This is the enforcer

## RBAC (Role Based Access Control)

1. Define user access level
2. **Least privilege**
3. Target specific use cases

- Works via assigned roles

*Breaking down RBAC*
- **Security Principal**
	-  An object that represents an entity, such as a user or group, that can access a implied or explicit resource.
- **Role Definition**
	- a collection of permissions such as read write and delete.
- **Scope**
	- the resources the access level applies to. Often used to specify resource group access.

> Role assignment is the process of implementing these three components into your environment

## Locks

1. Assign to a *subscription, resource group, or resource*
2. Two types. Delete and read only. Delete allows changes, read only does not. 
3. Locks must be removed before the actions they block can be performed again


## Blueprints

> Templates for creating resources

- Contain everything you need to build something in azure
	- resource templates
	- RBAC matrices
	- Policies
	- Samples for common regulations.

 ## Cloud Adoption Framework
1. A collection of documents and guides that will help walk you through the adoption to the Cloud
2. Works as guidance to help define strategies for adoption, planning, the move to the cloud, general readiness, reasons for adoption, governance practices, and managing the cloud architecture at scale. And as it grows
3. Governance remains key. And the Cloud Adoption Framework helps keep governance in the forefront.

## Azure Advisor for Security Assistance

- Part of the Azure Security center


# Summary
- Azure policy ensures that the right policies are applied to the right resources and they remain compliant.
- A policy is a set of rules that ensure resources are compliant.
- RBAC ensures user compliance by assigning roles, which are a combination of security, principal, role definition and scope
- Locks make sure that subscriptions, resource groups, or resources are either not modified or deleted
- Blueprints are templates for creating standardized environments
- The Azure Advisor for Security Assistance is part of the Security Center.