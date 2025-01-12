---
name: York Space
website: https://www.yorkspacesystems.com/
---

>[!summary]
>York Space Systems is a U.S.-based satellite manufacturer specializing in the design and production of small and medium-sized satellites for commercial and government applications. Known for its standardized spacecraft platforms, such as the S-CLASS, York aims to reduce costs and streamline production timelines. The company provides end-to-end satellite solutions, including mission planning, satellite integration, and operations support, catering to industries like Earth observation, communications, and defense.


## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[York Space Systems]])
sort launch_date desc
```

## 📰 News

```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[York Space Systems]])
sort published desc
```
