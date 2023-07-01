---
tags:
topic: "storage"
subTopic: "redundancy"
source: "guru"
family: "Azure"
imageNameKey: "Azure_redundancy"
cert: "AZ-900"
---
# Storage Redundancy

> _Created On:_ `=this.file.cday` 
> _Last Modified:_ `=this.file.mday`

Azure automatically creates multiple copies of your data for redundancy. You can control the redundancy options, but the cost increases with greater redundancy.

## Redundancy Options

- **Single Region:** Three copies are maintained in the primary region 
	- Locally Redundant Storage or **LRS**
	- Zone Redundant Storage or **ZRS**.
- **Multi Region:** Three copies are maintained in a secondary region.
	- Geo-Redundant Storage or **GRS**
	- Geo-zone-Redundant Storage or **GZRS**.

### LRS

- Three copies of the data are stored within the same data center or AZ. LRS is the most cost-effective option and protects against single disk failures but not against zone failure.

### ZRS

- More expensive than LRS, ZRS increases availability by storing data across three zones rather than three racks.

### GRS

- GRS maintains three copies of data in two different regions (an LRS version). It provides protection against regional failures and also offers read-replica access from the secondary region for high availability.

### GZRS

- GZRS provides the highest level of redundancy by applying ZRS in the primary region and LRS in the secondary region. It tolerates regional failure and also mitigates the need for failover to the secondary region.

## Summary

- Data is automatically replicated in Azure Storage for redundancy.
- At least three copies are maintained in a single region.
- A minimum of six copies is maintained across two regions when using regional failover options.
- There is an inverse relationship between availability and cost.
- Redundancy options range from a single zone to multiple zones within a single region, and across regions.