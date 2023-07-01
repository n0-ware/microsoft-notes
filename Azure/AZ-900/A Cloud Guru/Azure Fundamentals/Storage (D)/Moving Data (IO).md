---
tags:
topic: "storage"
subTopic: "moving_data"
source: "guru"
family: "Azure"
imageNameKey: "Azure_moving_data"
cert: "AZ-900"
---
# Moving Data (IO)
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

Azure offers a variety of solutions to manage data transfer depending on the data source (on-premises or in the cloud). These solutions accommodate varying data transfer requirements such as frequency, size, and bandwidth needs.

## Small and Occasional Data Transfers

### AzCopy

- A CLI utility.
- Works with both blob and file types.
- Useful for scripting automated data transfers.
- A typical AzCopy command might look like:

```powershell
az copy "filename.mpf" "https://urlto.my.storage"
```

### Azure Storage Explorer

- A standalone application available for download.
- Provides a GUI for easy drag-and-drop operations.
- Compatible with all file types.

### Azure File Sync

- Syncs data between on-premises and the cloud.
- Offers the benefits of local performance with cloud availability.
- Ideal for backups, servicing remote users, and performing data migrations to Azure.
- Can sync data from several on-premises locations.

## Large-Scale Data Transfers

### Azure DataBox

- Suitable for large volumes of data, especially where bandwidth is a concern.
- Provides offline data transfer solutions.
- A physical device is shipped to the user, who loads the data onto the device and sends it back to Azure.
- Works in reverse as well, enabling secure data export from Azure to on-premises locations.
- Use cases include bulk data migration, disaster recovery events, and scenarios with high-security requirements.

### Azure Migrate

- A service designed to facilitate the migration of servers, databases, and applications.
- Use cases include:
	- Migration of on-premises datacenters: Discovers dependent resources such as VMs and helps migrate databases to Azure-managed databases.
	- Migration of on-premises applications and their dependencies.
	- Collaboration with Azure DataBox for large-scale data migration.