---
name: Astrix Astronautics
website: https://astrix.space/
---

>[!summary]
Astrix Astronautics is a New Zealand-based company specializing in innovative power systems for small satellites. The company focuses on developing high-performance solar arrays and deployable power solutions to maximize energy efficiency for small satellite platforms. Astrix's technology is designed to meet the growing power demands of modern satellite missions, supporting applications such as Earth observation, communications, and deep space exploration. Their systems enable increased satellite capabilities while maintaining a compact and lightweight form factor, catering to both commercial and government customers in the space industry.

## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Astrix Astronautics]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Astrix Astronautics]])
sort published desc
```
