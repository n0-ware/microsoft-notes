---
tags:
topic: "storage"
subTopic: "blob"
source: "guru"
family: "Azure"
imageNameKey: "Azure_blob"
cert: "AZ-900"
---
# Azure Blob Storage

> _Creation Date:_ `=this.file.cday` _Last Modified:_ `=this.file.mday`

Blob (Binary Large Object) Storage in Azure is organized in a three-tier hierarchy:

1. A Storage Account that contains...
2. Containers, which in turn hold...
3. Blob data.

Each blob object has a unique web address associated with the account address. Blob storage can accommodate all types of files, such as images, streaming data, logs, etc.

Azure offers **three types of blobs**:

1. Block blobs for storing text and binary data up to 4.7 terabytes. These are individually managed blocks of data.
2. Append blobs optimized for append operations, which are useful for storing log data.
3. Page blobs can store up to 8 terabytes of data and function like a virtual hard drive.

## Blob Storage Pricing Tiers

- **Hot tier**: Ideal for frequently accessed files. This tier offers lower access times at a higher cost.
- **Cool tier**: Suitable for infrequently accessed data that remains in storage for at least 30 days. This tier has a lower cost but higher access times.
- **Archive tier**: Offers the lowest cost for the highest access times. Ideal for long-term storage of infrequently accessed data.