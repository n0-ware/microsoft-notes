---
tags:
- moc
topic: "azure"
subTopic: "moc"
source: "local"
family: "Azure"
cert: "AZ-900"
---
# + Azure MOC
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

```dataview
TABLE
	topic as "Main Topic",
	subTopic as "Sub Topic",
	subTopic2 as "Secondary Topic",
	file.mday as "Last Modified", 
	file.cday as "Created"
FROM "Azure/AZ-900/A Cloud Guru" AND -#moc
WHERE file.name != this.file.name
```

