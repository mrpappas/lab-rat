---
name: Aurora Propulsion Technologies
website: https://aurorapt.space/
---

>[!summary]
Aurora Propulsion Technologies is a Finnish company specializing in spacecraft propulsion and satellite deorbiting solutions. Focused on sustainable space operations, the company develops small-scale electric propulsion systems and tools to enable satellite maneuvering and controlled deorbiting at the end of mission lifecycles. Aurora’s products, such as water-based resistojet thrusters and plasma brake technologies, are designed to support small satellite missions and reduce space debris.

## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Aurora Propulsion Technologies]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Aurora Propulsion Technologies]])
sort published desc
```
