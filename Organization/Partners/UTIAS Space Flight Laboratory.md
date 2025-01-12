---
name: UTIAS Space Flight Laboratory
website: https://www.utias-sfl.net/
---

>[!summary]
UTIAS Flight Lab, part of the University of Toronto Institute for Aerospace Studies, is a leading developer of small satellite missions and advanced space systems. Specializing in microsatellites, nanosatellites, and CubeSats, SFL provides end-to-end mission solutions, including satellite design, manufacturing, integration, and operations. Known for its innovation in low-cost, high-performance satellites, SFL supports a wide range of applications, such as Earth observation, remote sensing, communications, and scientific research. With a proven track record of launching successful missions globally, SFL is a key player in enabling access to space for commercial, academic, and government clients.


### 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[UTIAS Space Flight Laboratory]])
sort launch_date desc
```

## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[UTIAS Space Flight Laboratory]])
sort published desc
```
