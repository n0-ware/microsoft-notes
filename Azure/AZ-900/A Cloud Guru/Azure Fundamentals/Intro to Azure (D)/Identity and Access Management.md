---
tags:
topic: "introduction"
subTopic: "iam"
source: "guru"
family: "Azure"
cert: "AZ-900"
---
# Identity and Access Management

> _Creation Date:_ `=this.file.cday` _Last Modified:_ `=this.file.mday`

Identity and Access Management revolves around three pivotal questions:

1. Who are the users?
2. What actions can they perform?
3. On which specific resources?

- **Azure AD (Azure Active Directory)** determines the "who", serving as the identity foundation.
- **Azure RBAC (Role-Based Access Control)** defines the permissions or "what actions" can be taken.
- **Scope** clarifies the resources or the "where" aspect.

### Azure AD

Every tenant gets a single Azure AD, responsible for identifying users and applications.

> **Identity = Security Principal.** Both users and applications possess identities. Typically, users are identified via email addresses.

### Azure RBAC

This component establishes what actions can be performed by whom.

- Roles are allotted to security principals (identities).
- Roles collate various granular permissions.
- Both generic and specific roles exist, e.g., "Owners" have comprehensive access within a scope, whereas a "Virtual Machine Contributor" role is more specialized.

### Scope

Determines the resources accessible to a user or identity.

- Roles can be designated at different resource hierarchy layers, thus setting the scope.
- Role inheritance ensures that roles assigned at the subscription level apply to all underlying resource groups and their resources.