---
name: Planet Labs
website: https://www.planet.com/
---


>[!summary]
Planet Labs is a leading Earth observation company that designs, builds, and operates the world’s largest fleet of imaging satellites. Planet's constellation of Dove, SuperDove, and SkySat satellites captures daily, high-resolution imagery of the entire Earth. This continuous, real-time data stream enables governments, businesses, and researchers to monitor changes, track trends, and make data-driven decisions in areas such as agriculture, forestry, climate monitoring, urban development, and disaster response. 


### 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Planet Labs]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Planet Labs]])
sort published desc
```
