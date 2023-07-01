---
tags:
topic: "networking"
subTopic: "content_delivery_net"
source: "guru"
family: "Azure"
imageNameKey: "Azure_null"
cert: "AZ-900"
---
# Content Delivery Network (CDN)

_Creation Date:_ `=this.file.cday` 
_Last Modified:_ `=this.file.mday`

A CDN increases the speed of websites and resource loading by caching copies of data at local edge nodes, thereby reducing latency.

## Benefits

- **Performance Increase**: Lowers latency, especially when multiple round trips are required.
- **Scalability**: Capable of handling traffic spikes and protecting the backend from high loads.
- **Distribution**: Ensures that requests stay near the user, reducing traffic sent to the hosting application.

## Key Terms

- **Cache**: A collection of temporary copies stored at the edge location that mirrors the original file, optimizing application speed and reducing backend load.
- **Origin Server**: The original location storing master copies that update the cache.