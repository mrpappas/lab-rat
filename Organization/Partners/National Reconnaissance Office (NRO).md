---
name: National Reconnaissance Office (NRO)
website: https://www.nro.gov/
---

>[!summary]
>The National Reconnaissance Office (NRO) is a U.S. government agency responsible for designing, building, and operating reconnaissance satellites to support national security. Established in 1961, the NRO plays a critical role in collecting intelligence for the Department of Defense, intelligence community, and policymakers, focusing on areas like threat assessment, military operations, and disaster response. It develops and manages cutting-edge satellite systems, leveraging advanced technologies to provide geospatial intelligence (GEOINT) and signals intelligence (SIGINT). The NRO works closely with agencies like the CIA, NSA, and U.S. Space Force, as well as commercial and international partners, ensuring the United States maintains a strategic advantage in space-based reconnaissance.
## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[National Reconnaissance Office (NRO)]])
sort launch_date desc
```

## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[National Reconnaissance Office (NRO)]])
sort published desc
```
