---
name: Astro Digital
website: https://astrodigital.com/
---

>[!summary]
Astro Digital is a satellite manufacturer and operator specializing in delivering turnkey solutions for Earth observation, communications, and data analytics. The company focuses on designing, building, and operating small satellite systems to provide rapid access to data for commercial and government customers. Astro Digital offers customizable platforms for satellite missions, including payload integration, mission operations, and ground support. Known for its flexible approach, the company serves clients requiring Earth imagery, environmental monitoring, and IoT data transmission.

## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Astro Digital]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Astro Digital]])
sort published desc
```
