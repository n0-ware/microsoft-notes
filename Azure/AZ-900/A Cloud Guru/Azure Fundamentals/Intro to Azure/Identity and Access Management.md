---
tags:
topic: "introduction"
subTopic: "iam"
source: "guru"
family: "Azure"
cert: "AZ-900"
---
# Identity and Access Management
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

Three part question

1. Who
2. Can do what
3. On which resources?


1. Azure AD defines the who
2. Azure RBAC defines who can do what with fine-grained control
3. Scope decides on which resources

## Azure AD - Who

- One per tenant
- Provides identity, or "who are you"

> **Identity = Security Principal.** 
> This is because end users AND applications can have identities

- End users generally come in the format of an e-mail address.
## Azure Role Based Access Control - RBAC

> Can do what?

- Roles are assigned to security principles, also known as identities
- Rules are simply collections of permissions that can be very granular.
- There are general and specific role types.
	- owners have full access in a particular scope for example.
	- The role Virtual Machine contributor can only access and manage VMS.

## Scope

> On which resources?

- Roles are granted at various layers of the resource hierarchy., thus defining the scope
- Roles are inherited, meaning a role applied at the subscription level applies to all resource groups and therefore the resources inside of it.

