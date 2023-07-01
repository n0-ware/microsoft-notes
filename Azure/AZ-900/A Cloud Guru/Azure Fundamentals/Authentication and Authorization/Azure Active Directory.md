---
tags:
topic: "auth_and_auth"
subTopic: "aad"
source: "guru"
family: "Azure"
imageNameKey: "Azure_aad"
cert: "AZ-900"
---
# Azure Active Directory
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

- **NOT THE SAME AS REGULAR ACTIVE DIRECTORY**
	- Knowledge does not transfer over seamlessly


| AD                                                 | AAD                                                 |
| -------------------------------------------------- | --------------------------------------------------- |
| Traditional office use with computers and printers | Cannot have an Azure account without an AAD service | 
| Not designed for the web                           |                                                     |
| AD users services not available on azure           |  Tenant is a dedicated instance of AAD                                                   |
| Self-hosted product                                |  Online "tenant" represents the org                                                   |

## Tenant

1. Organization is the top line and a tenant represents the organization
2. Dedicated AAD means that a single tenant is dedicated to a single instance of AAD and an organization gets one upon signing up
3. Separation of tenants distinctly and completely separates other AAD tenants.
4. One user, one tenant means that a user cannot be a member of a second tenant, they must be a guest. And all users are a member of the tenant

## Subscription

1. A billing entity is what subscriptions represent to group the resources that should be assigned a single cost, center
2. Cost separation allows multiple subscriptions within a tenant to receive separate billing
3. Payment is required or services are shut off.

## Hybrid Design

> Azure Active Directory is designed to form a link between your on premises infrastructure and users and Azure in the cloud.

### Entra

Microsoft introduced Entra as a Product Family

- Entra includes all of Microsoft's identity and access capabilities
- It also includes Azure AD while offering permissions management and verified ID
- **Exam perspective requires that you know Azure AD is part of the broader Microsoft entry product family**

