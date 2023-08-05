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

> _Creation Date:_ `=this.file.cday` 
> _Last Modified:_ `=this.file.mday`

## Key Points

- Zero Trust is a security concept well-suited to the modern, decentralized work environment, which involves remote working and cloud services.
- The core principle of Zero Trust is "never trust, always verify," regardless of whether the access request comes from within or outside the network.
- Zero Trust moves away from the traditional security model of trusting everything within a network perimeter and distrusting everything outside it.
- Zero Trust is not a product or service but a strategic approach to security.

### Classic Trusted vs Untrusted Model

- In the classic model, the network perimeter (or edge) is trusted, and everything outside is considered potentially dangerous.
- Remote working poses a challenge to the classic model as access usually comes from outside the trusted network.
- VPNs only extend the trusted perimeter and still operate under the same principle of trusting everything within a certain boundary.
- The classic model can be vulnerable to attacks from within the trusted perimeter.

### Zero Trust Model

- Zero Trust operates on the principle of "never trust, always verify," whether the request comes from inside or outside the network.
- Identity, not location, forms the basis of trust in Zero Trust.
- Zero Trust adopts a Least Privilege Access approach, providing users and devices with only the minimum necessary access.
- Zero Trust assumes that a breach can happen and works to limit its impact.
- Zero Trust should be used in combination with the classic model for a defense-in-depth approach.

### Implementing Zero Trust

- Conditional Access policies are key to implementing Zero Trust, controlling access based on conditions such as user identity, device health, and network location.
- Managed devices, which are devices that conform to an organization's security policies, play a significant role in Zero Trust.
- Zero Trust extends to all resources, not just to the network but also applications, data, infrastructure, and services.
- Zero Trust requires continuous validation and verification, as trust can never be fully established.
- Microsegmentation is often used in Zero Trust to isolate workloads from one another and secure them individually.
- Zero Trust leverages advanced technologies like artificial intelligence and machine learning to detect abnormal behavior and automate responses.
- Implementing Zero Trust requires a holistic approach that includes people, processes, and technology.