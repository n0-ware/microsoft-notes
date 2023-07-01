<%*
let title = await tp.system.prompt("Title")
await tp.file.rename(title)
let topic = await tp.system.prompt("Topic Tag")
let subTopic = await tp.system.prompt("Sub-Topic Tag")
let source = await tp.system.prompt("Souce Tag (e.g., guru)")
tR += "---"
%>
tags:
topic: "<% topic %>"
subTopic: "<% subTopic %>"
source: "<% source %>"
family: "Azure"
imageNameKey: "Azure_<% subTopic %>"
cert: "AZ-900"
---
# <% title %>
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

