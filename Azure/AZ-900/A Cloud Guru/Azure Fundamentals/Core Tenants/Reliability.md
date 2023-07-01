---
tags:
topic: "fundamentals"
subTopic: "reliability"
source: "guru"
family: "Azure"
cert: "AZ-900"
---
# Reliability
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

> Describes the resilience of cloud computing

```ad-tip
Reliability refers to uptime, failure-tolerance, etc. High-availability is the responsiveness to customer load and accessibility to your customers. 
```

- Generally meaning a systems ability to recover from failures and continue to function
- No single point of failure
	- Through mutli zone/region deployment

## Fault Tolerance

> Proactive and Reactive methods to **continue operating properly** when one or more components fails.

*Proactive*
- Regular backups of apps, data, and resources
- Deploying to multiple Availability Zones or regions
- Load balancing across multiple regions or zones
- Monitoring the health of your data, apps, and resources continuously to detect failures. And some of these options.

*Reactive*
- Backup plans to restore your data, apps, and resources in different Availability Zones or with different resources
- The ability to deploy immediately into different Availability Zones or regions as needed
- Availability of load balancing and scaling.

## Disaster Recovery

> A system's ability to **back up and restore data**, apps, and resources when needed.

- Azure can restore
	- on premises to on premises
	- On premises to azure
	- Other clouds to azure
	- Azure to Azure.
