---
name: Myriota
website: https://myriota.com/
---

>[!summary]
Myriota is an Australian company specializing in low-power, direct-to-satellite IoT (Internet of Things) connectivity. Headquartered in Adelaide, Myriota provides affordable and efficient solutions for transmitting small amounts of data from remote sensors and devices via its satellite constellation.
>
Myriota’s technology enables industries such as agriculture, utilities, environmental monitoring, and asset tracking to connect devices globally without relying on traditional terrestrial infrastructure. Their system allows ultra-low-power communication, extending the life of IoT devices in remote locations for years on minimal energy.


## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Myriota]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Myriota]])
sort published desc
```
