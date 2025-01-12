---
name: Swarm
website: https://en.wikipedia.org/wiki/Swarm_Technologies
---

Subsidiary of [[SpaceX]]

>[!summary]
Swarm Technologies, a subsidiary of SpaceX, provides affordable and reliable global satellite connectivity for IoT (Internet of Things) devices. Using its constellation of miniature satellites, known as SpaceBEEs, Swarm delivers low-cost, low-bandwidth communication for industries like agriculture, maritime, logistics, and environmental monitoring. The company’s focus is on enabling global coverage for IoT applications, even in remote and underserved areas, through its compact hardware and efficient data services. As part of SpaceX, Swarm leverages synergies in innovation and infrastructure to expand its reach and make satellite IoT connectivity accessible worldwide.


### 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Swarm]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Swarm]])
sort published desc
```

---
### ✏️ Notes

- Acquired by [[SpaceX]] August 6 2021. [Source](https://www.satellitetoday.com/finance/2021/08/09/spacex-buys-out-satellite-iot-startup-swarm-technologies/)