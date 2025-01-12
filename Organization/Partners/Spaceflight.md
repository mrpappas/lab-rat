---
name: Spaceflight
website: https://en.wikipedia.org/wiki/Spaceflight,_Inc.
---

>[!summary]
Spaceflight Inc. was known as a leader in arranging launches of small satellites on small launch vehicles or as secondary payloads on larger launch vehicles, deploying more than 460 payloads. Spaceflight had also developed its own series of orbital transfer vehicles called Sherpa, using a mix of chemical and electric propulsion systems.


### 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Spaceflight]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Spaceflight]])
sort published desc
```

---
## ✏️ Notes

- Acquired by [[Firefly Aerospace]] June 8 2023. [Source](https://www.satellitetoday.com/finance/2023/06/12/firefly-aerospace-to-acquire-rideshare-provider-spaceflight/)