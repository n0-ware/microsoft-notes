---
tags:
topic: "auth_and_auth"
subTopic: "guest_access"
source: "guru"
family: "Azure"
imageNameKey: "Azure_guest_access"
cert: "AZ-900"
---
# External Guest Access
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

- Guests often need access such as contractors or testers
- They are not part of your AAD so need to be given a method of access
- Two accounts is an option, but better to use an invite as a guest

## B2B Collaboration
- AAD is pre-configured to invite from a number of identity providers (Microsoft, Google, Facebook, etc.)
	- The IDP brings them right in
- Can configure additional third party IDPs
- Assign privileges for AD and Azure AD
- Can assign to an application as well and inherit permissions there
- Apply cross-tenant conditional access policies


1. Configure an IDP
2. Invite the party
3. Assign permissions
4. Optionally assign apps
5. Optionally assign conditional access
