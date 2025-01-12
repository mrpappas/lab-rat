---
name: Trisept
website: https://trisept.com/
---

>[!summary]
TriSept provides launch integration, mission management, and engineering services for satellite missions of all sizes. With expertise spanning rideshare coordination, dedicated launches, and complex multi-payload deployments, TriSept ensures reliable and efficient access to space for commercial, government, and defense customers. Their proven track record, combined with mission assurance and innovative solutions, enables seamless integration from concept to orbit.


## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Trisept]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Trisept]])
sort published desc
```
