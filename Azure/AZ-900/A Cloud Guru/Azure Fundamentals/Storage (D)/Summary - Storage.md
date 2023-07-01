---
tags:
topic: "storage"
subTopic: "summary"
source: "guru"
family: "Azure"
imageNameKey: "Azure_summary"
cert: "AZ-900"
---
# Summary - Storage
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

## Key Concepts

- Azure provides five main types of storage options:
    - Blob (object)
    - Files
    - Disks
    - Queues
    - Tables

## Storage Accounts

- Unique namespace in Azure for data storage.
- Massively scalable (up to petabytes) and high availability.
- Automatically replicates data (3 replicas for fault tolerance).
- Data is replicated across the three Availability Zones in a region.

## Storage Services Overview

- **Blob**: For unstructured data like images, videos, scripts.
- **Files**: Offers network file share capabilities in the cloud.
- **Disks**: Used with VMs, managed by Azure.
- **Queues**: Provides asynchronous messaging between apps and services.
- **Tables**: NoSQL database storage (transitioning to Cosmos DB).

## Redundancy Options

- Azure provides several data redundancy options: LRS, ZRS, GRS, GZRS.
- More redundancy comes at a higher cost.
- Azure always creates multiple copies of data (3 at minimum).

## Archive and Blob Storage

- Archive: Very low-cost long-term storage. Suitable for requirements necessitating long-term data retention.
- Blob Storage: Any type of file can be stored in Blob storage, and each Blob object has a unique web address.

## Disk (Managed) and File Storage

- Managed Disks: Attached to VMs, have guaranteed size and performance.
- File Storage: Acts as a file share in the cloud, resolving on-premises storage issues.

## Data Transfer

- Azure offers various tools for data transfer:
    - **AzCopy**: CLI utility for moving Blob or file data.
    - **Azure Storage Explorer**: GUI-based tool that works with all file types.
    - **Azure File Sync**: Syncs data between on-premises and the cloud.
    - **Azure DataBox**: Used for large-scale data transfers where bandwidth is a concern.
    - **Azure Migrate**: Facilitates migration of servers, databases, and applications from on-premises to Azure.