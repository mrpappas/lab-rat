---
name: UNSW Canberra Space
website: https://www.unsw.edu.au/canberra/our-research/research-centres-institutes/unsw-canberra-space
---

>[!summary]
UNSW Canberra Space is a leading Australian space research and development center, based at the [University of New South Wales in Canberra](https://www.unsw.edu.au/canberra). Specializing in the design, development, and operation of small satellites, UNSW Canberra Space focuses on advancing space technology for Earth observation, defense, and scientific research. The center collaborates with government agencies, including the Australian Defence Force, and industry partners to deliver innovative and resilient space systems. With a strong emphasis on space situational awareness, satellite communications, and autonomous systems, UNSW Canberra Space plays a pivotal role in supporting Australia's growing presence in the global space industry.

## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[UNSW Canberra Space]])
sort launch_date desc
```

## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[UNSW Canberra Space]])
sort published desc
```
