---
name: BlackSky
website: https://www.blacksky.com/
---


>[!summary]
BlackSky is a **U.S.-based geospatial intelligence company** that specializes in providing **real-time Earth observation data** and **analytics**. The company operates a constellation of **low Earth orbit (LEO) satellites** designed to capture high-resolution imagery multiple times per day. BlackSky integrates satellite imagery with **artificial intelligence (AI)** and other data sources to deliver **actionable insights** for applications such as **defense, disaster response, supply chain monitoring, and infrastructure management**. BlackSky's subscription-based platform offers near real-time access to **global monitoring** capabilities, enabling rapid decision-making for commercial and government clients.

## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[BlackSky]])
sort launch_date desc
```

## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[BlackSky]])
sort published desc
```

