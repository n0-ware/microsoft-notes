---
tags:
topic: "auth_and_auth"
subTopic: "zero_trust"
source: "guru"
family: "Azure"
imageNameKey: "Azure_zero_trust"
cert: "AZ-900"
---
# Zero Trust Concepts
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

- Zero Trust is a security model that is well adapted to a modern, remote workplace
- Without it, we would not be able to accomplish what we do, enabling employees to work outside of the office.


## Classic Trusted vs Untrusted Model

- The original model relied on a "trusted perimeter" such as a corporate network
- The "edge" was the boundary for secure access
- Access outside of that is restricted
- Challenges are obvious
	- Remote work a challenge because you are immediately outside of the trusted perimeter
	- VPN's are good to an extent, but it just extends the trusted edge, so it is the same model
	- Too much trust inside enables rogue devices or users to take advantage of overly used trust

## Zero Trust

- Unless proven otherwise, no one is trusted
	- Inside or outside of the network
- **Identity** is the trust bases, regardless of location
- **Least Privilege** gives just enough to do ones job. 
- Zero Trust  = Trusted Identities, NOT locations

> Zero trust can be and should be combined with the classic trust model for defense in depth to be in effect.

- Conditional access policies are centrally controlled and can increase your control over identities
- Managed devices help greatly