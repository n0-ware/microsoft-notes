---
tags:
topic: "auth_and_auth"
subTopic: "aadds"
source: "guru"
family: "Azure"
imageNameKey: "Azure_aadds"
cert: "AZ-900"
---
# AAD Domain Services
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`


- With the new cloud services is going to be most difficult portions of degrading or migrating to Azure AD.
- AAD DS is not a replacement. Uses entirely different methods for authenticating

## Limitations of Azure AD vs AD DS

- Legacy apps
- Might struggle with modern auth such as OAuth 2.0
- Likely require traditional ADDS (not AAD DS) like group policy, LDAP, NTLM, or Kerberos

 ## Solutions?

- Keep using old on-prem AD servers
	- Can just sync to Azure AD
- Configure another AD server on the Azure VM
	- Self managed AD DS
	- You maintain it al

## Azure Active Directory Domain Services (Azure AD DS)

- **Managed** AD DS on the cloud
- Provides classic AD features in a managed service

# How it works

- Managed service
- Two domain controllers for high availability
- **You cannot use the same domain name as you have on prem**
	- It is not an extension
	- It is standalone
	- A "one-way sync" can get all your Azure AD info to Azure AD DS, including groups, creds, users, etc. 
- Also possible to keep the two-way sync between AD and Azure AD, ending up in a two-way and 1-way sync

![[1_Azure_aadds.png]]