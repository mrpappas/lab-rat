---
name: HawkEye 360
website: https://www.he360.com/
---

>[!summary]
HawkEye 360 is a geospatial analytics company that operates a constellation of satellites to detect, characterize, and geolocate radio frequency (RF) signals. Their services provide insights for applications such as maritime domain awareness, spectrum monitoring, and national security. By analyzing RF data, HawkEye 360 helps identify illegal activities like maritime piracy, smuggling, and unlicensed spectrum usage.

## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[HawkEye 360]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[HawkEye 360]])
sort published desc
```
