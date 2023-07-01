---
tags:
topic: "core services"
subTopic: "storage"
source: "guru"
family: "Azure"
cert: "AZ-900"
---
# Azure Storage

> _Created On:_ `=this.file.cday` 
> _Last Modified:_ `=this.file.mday`

Azure Storage is a comprehensive service that offers five key types of storage:

1. Blob (Object)
2. Files
3. Disks
4. Queues
5. Tables

Each of these storage types serves a unique purpose and is leveraged differently based on use case requirements.

## Storage Accounts

An Azure **Storage Account** is a unique namespace for data storage. It's a massively scalable, managed infrastructure that houses Azure's various storage solutions. Each Storage Account can handle up to petabytes of data.

- Every instance of data stored in a Storage Account is automatically replicated three times for fault tolerance.
- Storage Accounts are highly available as they use an intelligent routing device.

```ad-tip
**Note:** Storage data is automatically replicated across three availability zones (AZs) within a region because storage is region-specific.
```

### Understanding Storage Accounts

- Each Storage Account has a globally unique web address.
- Storage Accounts are contained within resource groups, implying that a resource group is a prerequisite.
- A Storage Account isn't the same as an Azure account used to differentiate organizations, geolocations, etc.
- Different types of storage can be created within a Storage Account, and you can have multiple types of the same storage.

## Overview of Azure Storage Services

### Blob

- Blob, or Binary Large Object, is a type of storage that can accommodate any file type. This is typically referred to as object storage and can contain unstructured data, such as images, videos, scripts, etc.

### Files

- Azure Files is essentially a network file share in the cloud.

### Disks

- Disks are the storage mechanisms used by all Virtual Machines (VMs). Every VM uses a storage account (invisible to the end user) for its disks.

### Queues

- Queues facilitate asynchronous messaging between apps and services, acting like a message buffer for incoming data.

### Tables

- Tables offer NoSQL database storage. This service is gradually being shifted to Azure's Cosmos DB solution.