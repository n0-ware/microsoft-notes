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

> A reliable workload is both _resilient_ and _available_. [Resiliency](https://learn.microsoft.com/en-us/azure/well-architected/resiliency/) is the ability of the system to recover from failures and continue to function. The goal of resiliency is to return the application to a fully functioning state after a failure occurs. Availability is whether your users can access your workload when they need to.

```ad-tip
Reliability refers to uptime, failure-tolerance, etc. High-availability is the responsiveness to customer load and accessibility to your customers. 
```

Reliability in the cloud implies:

- The system's resilience and its ability to recover from setbacks.
- Eliminating single points of failure through multi-zone or region deployments.

## Fault Tolerance

Ensures seamless operations despite component failures. Strategies include:

- **Proactive**:
    
    - Backing up apps, data, and resources.
    - Multi-zone or region deployments.
    - Load balancing across regions or zones.
    - Continuous health monitoring.
- **Reactive**:
    
    - Backup and restoration strategies for different zones or resources.
    - Quick deployments to alternative zones or regions.
    - Utilizing load balancing and scaling.

## Disaster Recovery

Focuses on backing up and restoring data, apps, and resources:

- Azure's versatility allows for various restoration scenarios, including on-premises to Azure, between clouds, or within Azure itself.