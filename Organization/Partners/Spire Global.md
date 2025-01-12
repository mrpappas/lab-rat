---
name: Spire Global
website: https://spire.com/
---

>[!summary]
**Spire Global** is a leading provider of **space-based data, analytics, and services**. The company operates a constellation of **CubeSats** that collect data for global maritime, aviation, and weather tracking. By leveraging its extensive satellite network, Spire delivers real-time insights and predictive analytics to industries like logistics, climate monitoring, defense, and telecommunications. Its **multi-purpose satellites** enable businesses and governments to make informed decisions through data on **ship movements, flight paths, atmospheric conditions, and asset tracking**. 


### 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Spire Global]])
sort launch_date desc
```

## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Spire Global]])
sort published desc
```
