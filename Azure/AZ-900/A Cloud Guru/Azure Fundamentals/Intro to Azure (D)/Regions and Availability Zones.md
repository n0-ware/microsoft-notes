---
tags:
topic: "fundamentals"
subTopic: "regions_and_azs"
source: "guru"
family: "Azure"
imageNameKey: "Azure_fundamentals"
cert: "AZ-900"
---
# Regions and Availability Zones

> _Creation Date:_ `=this.file.cday` _Last Modified:_ `=this.file.mday`

## Regions

Azure's infrastructure is organized into regions and availability zones:

- **Regions** are broader than AZs, with a latency-defined perimeter ensuring proximity.
- ***Each region houses one or more availability zones.***
- Pricing varies by region.
- Every region has a twin within the same geographic zone *(with an exception for Brazil South, paired with South Central US)*. This pairing ensures redundancy.
- Planned updates impact only one region at a time.
- Data can be replicated across paired regions for added resilience.

## Availability Zones

Availability Zones are distinct physical locations within a region:

- Each contains independent data centers.
- ***Typically, a region has a minimum of three zones.***
- Notably, storage in Azure is automatically replicated across the three AZs within a region due to its regional nature.