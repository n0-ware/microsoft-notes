---
tags:
topic: "storage"
subTopic: "premium"
source: "guru"
family: "Azure"
imageNameKey: "Azure_premium"
cert: "AZ-900"
---
# Premium Storage

> _Created On:_ `=this.file.cday` 
> _Last Modified:_ `=this.file.mday`

Premium Storage uses SSD and comes with distinct considerations:

- Certain storage types may not be available.
- Redundancy options are limited.
- All premium options only support single-region redundancy options.

### Standard Storage

The default option is Standard General Purpose v2, which supports all types of storage and offers all redundancy options.

### Premium Storage Variants

- **Premium Blob:** Ideal for low latency blob workloads, such as AI or IoT analytics. Supports LRS/ZRS only.
- **Premium Page:** Unmanaged virtual disk for VMs. Supports LRS only.
- **Premium File Share:** Uses Azure Files for high-performance enterprise apps. Supports SMB or NFS types and LRS/ZRS only.