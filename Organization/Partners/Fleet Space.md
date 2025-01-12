---
name: Fleet Space
website: https://www.fleetspace.com/
---


>[!summary]
Fleet Space Technologies is an Australian company specializing in satellite-based connectivity solutions, focusing on Internet of Things (IoT) applications. Fleet operates a constellation of small low Earth orbit ([[🌍 Orbits#LEO|LEO]]) satellites that provide global, low-power, and cost-effective communications for industries such as mining, energy, agriculture, and defense. Their [ExoSphere](https://www.fleetspace.com/mineral-exploration) service combines satellite technology with geophysical sensors to support exploration and resource management. Fleet Space emphasizes innovation in nanosatellite design and rapid deployment to enable scalable IoT solutions.
### 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Fleet Space]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Fleet Space]])
sort published desc
```
