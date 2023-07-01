---
tags:
topic: "auth_and_auth"
subTopic: "conditional_access"
source: "guru"
family: "Azure"
imageNameKey: "Azure_conditional_access"
cert: "AZ-900"
---
# Conditional Access Policies
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

- Premium feature built into Azure AD
- Use if/then policies
	- if a user meets conditions, also known as signals.
	- Then access is granted or blocked.
	- Paired with central MFA

## Configurations

- Assign **signals**
	- what users and groups are trying to log in
	- Which applications to grant or deny access
	- What's the location
	- Approved or unapproved devices
- Access **decisions**
	- Do you grant access
	- Do you block access
	- Do you require MFA?
![[1_Azure_conditional_access.png]]

**Considerations**
- Do you enforce MFA for all administrators or all users? Or some combination
- Should you block sign INS for legacy authentication protocols
- Should you grant access only from specific locations or IP addresses
- Should you require organization managed devices for application signs?