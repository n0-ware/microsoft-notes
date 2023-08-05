---
tags:
topic: "auth_and_auth"
subTopic: "aad"
source: "guru"
family: "Azure"
imageNameKey: "Azure_aad"
cert: "AZ-900"
---
# Azure Active Directory (AAD)

> _Creation Date:_ `=this.file.cday` 
> _Last Modified:_ `=this.file.mday`

Azure Active Directory (AAD) is not to be confused with traditional Active Directory (AD). The two systems have different designs, features, and usage. Knowledge of one does not seamlessly transfer to the other.

|Active Directory (AD)|Azure Active Directory (AAD)|
|---|---|
|Used traditionally for office computers and printers|An AAD service is mandatory for an Azure account|
|Not designed for web-based operations||
|Some AD user services are not available on Azure|A "tenant" is a dedicated instance of AAD representing an organization|
|Self-hosted product||

## Tenant in AAD

1. An AAD tenant represents the organization at the highest level.
2. "Dedicated AAD" means a single instance of AAD is dedicated to one tenant (one organization), granted upon signing up.
3. Tenants in AAD are distinctly and completely separated from each other.
4. A user is bound to a single tenant; they cannot be a member of a second tenant without being a guest. All users are members of their respective tenants.

## Subscription in AAD

1. A subscription is essentially a billing entity, grouping resources that should be associated with a single cost center.
2. Cost separation is possible by having multiple subscriptions within a tenant, allowing separate billing for each.
3. Payment is required to maintain services; non-payment results in service interruption.

## Hybrid Design

Azure Active Directory is designed to bridge the gap between your on-premises infrastructure and Azure in the cloud.

## Entra: A Broader Product Family

Microsoft introduced Entra as a broader product family encompassing:

- All of Microsoft's identity and access capabilities
- Azure AD, while also offering permissions management and verified ID

From an exam perspective, it's crucial to understand that Azure AD is part of the larger Microsoft Entra product family.
