---
name: In-Space Missions
website: https://in-space.co.uk/
---

>[!summary]
In-Space Missions is a UK-based company that designs, builds, and operates satellites, specializing in rideshare missions like the Faraday series, which host multiple payloads on a single platform. They offer rapid access to space for technology demonstration, Earth observation, and communication missions. Acquired by [BAE Systems](https://www.baesystems.com/en/home) in 2021, they support commercial, governmental, and research customers.

### 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[In-Space Missions]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[In-Space Missions]])
sort published desc
```
