---
name: Alba Orbital
website: https://www.albaorbital.com/

---

>[!summary]
Alba Orbital is a Scottish aerospace company specializing in the development and launch of PocketQube satellites, which are ultra-small satellites designed for cost-effective space access. The company provides end-to-end solutions, including satellite design, manufacturing, and integration, as well as launch services through partnerships with various rocket providers, including Rocket Lab. Alba Orbital has enabled a variety of missions, such as Earth observation, IoT connectivity, and technology demonstrations, leveraging its expertise in miniaturized satellite technology to democratize access to space for startups, universities, and research organizations.

### 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Alba Orbital]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Alba Orbital]])
sort published desc
```
