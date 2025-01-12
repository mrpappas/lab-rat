---
name: iQPS (Institute for Q-shu Pioneers of Space, Inc.)
website: https://i-qps.net/en/
---


>[!summary]
iQPS (Institute for Q-shu Pioneers of Space) is a Japanese company focused on developing and deploying synthetic aperture radar (SAR) satellites.
They are working toward establishing a constellation of 36 small SAR satellites, aiming to provide near-real-time imaging with high-frequency revisits. Their compact satellites deliver sub-meter resolution data, enabling industries such as disaster management, infrastructure monitoring, agriculture, and defense to benefit from precise and timely Earth observation insights.
iQPS has launched several satellites to demonstrate its SAR capabilities and is actively scaling its constellation to offer comprehensive global coverage.

## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[iQPS]])
sort launch_date desc
```

## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[iQPS]])
sort published desc
```
