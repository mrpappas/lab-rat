---
name: OHB Group
website: https://www.ohb.de/en/
---

>[!summary]
OHB Group is a leading European space and technology company specializing in the development and execution of innovative space systems and applications. Headquartered in Bremen, Germany, OHB operates across the full spectrum of the space value chain, including satellite manufacturing, space transportation, Earth observation, and exploration missions. The company’s capabilities range from building small and medium-sized satellites for telecommunications, Earth observation, and scientific research to contributing to major space infrastructure projects such as Galileo, Copernicus, and ISS-related systems. With a strong emphasis on innovation, reliability, and partnerships, OHB Group supports government agencies, commercial customers, and international space organizations in achieving their goals in space.


## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[OHB Group]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[OHB Group]])
sort published desc
```
