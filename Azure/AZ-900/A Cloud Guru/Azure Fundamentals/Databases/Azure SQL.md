---
tags:
topic: "databases"
subTopic: "azure_sql"
source: "guru"
family: "Azure"
imageNameKey: "Azure_azure_sql"
cert: "AZ-900"
---
# Azure SQL
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

## Key Features

Database as a service

- Easy on-prem to Azure SQL migration
- Built-in machine Learning
	- Suggests optimizations
	- Warnings are easy
- Scales well
- High availability
- Scales up to 100TBs in size
- Security is easy because it is managed

## Database vs Managed Instance

**Azure SQL Database**
- More like a traditional SQL Server

**Azure SQL Managed Instance**
- Aimed at migrating from on-premesis

**Differences**
> There are no variances in language features, database features, security features, or data models

| SQL Database                                 | SQL Managed Instance                                |
| -------------------------------------------- | --------------------------------------------------- |
| Recovery from automated backusp only         | Reovery from automated backups and full SQL backups |
| Geo-replication                              | No geo-replication                                  |
| Autoscale supported when in serverless model | No autoscaling                                      |
| Automatic tuning                             | SQL Server Profiler                                 |
| No SQL Server Agent                          | SQL Server Agent                                                    |
