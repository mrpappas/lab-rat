---
name: E-Space
website: https://e-space.com/
---
>[!summary]
E-Space is a low Earth orbit ([[🌍 Orbits#LEO|LEO]]) satellite communications company focused on building a sustainable satellite network. The company aims to deploy low-cost, small satellites that offer global connectivity while minimizing space debris through collision avoidance and deorbiting technologies. E-Space emphasizes modular satellite design, efficient manufacturing, and a focus on sustainability to enable scalable and responsible space-based communications solutions for commercial, government, and IoT applications.

## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[E-Space]])
sort launch_date desc
```

## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[E-Space]])
sort published desc
```


## ✏️ Notes

- [[054 'Changes In Latitudes, Changes In Attitudes' - Electron]] Rocket Lab did not publicly disclose the customer but New Zealand government filings indicated E-Space was likely the customer. [Source](https://x.com/SpaceEquities/status/1846992995419333052)

