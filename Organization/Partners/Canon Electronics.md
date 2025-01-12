---
name: Canon Electronics
website: https://en.canon-elec.co.jp/
---


>[!summary]
Canon Electronics is a **Japan-based technology company** that specializes in **precision instruments and imaging solutions**. As a subsidiary of [Canon Inc](https://en.wikipedia.org/wiki/Canon_Inc.)., it is known for developing **small satellite technology** and **Earth observation systems**. Canon Electronics leverages its expertise in optics and miniaturization to produce **compact, cost-effective satellites** equipped with high-resolution imaging capabilities. The company aims to contribute to the growing demand for **commercial satellite imaging** and **remote sensing applications**, offering solutions for industries such as agriculture, infrastructure monitoring, and environmental assessment. Canon’s initiatives align with the expansion of low-cost, high-quality space technologies.

## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Canon Electronics]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Canon Electronics]])
sort published desc
```
