---
name: KSAT (Kongsberg Satellite Services)
website: https://www.ksat.no/
---

>[!summary]
>Kongsberg Satellite Services AS (KSAT) is a Norwegian-based company. KSAT has the most extensive ground station network globally, and the world's largest ground station for support of polar orbiting satellites located at [78° North - Svalbard, Norway](https://maps.app.goo.gl/na4tJeEj5AARqEyH8). They are a provider of ground network services and maritime monitoring services.

## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[KSAT]]) or contains(partner, [[KSAT]])
sort published desc
```
