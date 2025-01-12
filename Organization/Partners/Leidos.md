---
name: Leidos
website: https://www.leidos.com/markets/space
---


>[!summary]
Leidos is a U.S.-based technology and defense company specializing in advanced solutions for aerospace, defense, intelligence, and civil markets. In the space sector, Leidos supports missions through systems integration, satellite communications, space domain awareness, and mission-critical technologies. The company provides services ranging from developing ground control systems to designing and managing space-related hardware, software, and data solutions for both government and commercial customers. Leidos plays a critical role in supporting national security, [[NASA]] programs, and the broader space ecosystem through innovation in autonomous systems, space infrastructure, and defense applications.

## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Leidos]])
sort launch_date desc
```

## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Leidos]])
sort published desc
```
