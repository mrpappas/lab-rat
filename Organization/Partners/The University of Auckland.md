---
name: The University of Auckland
website: https://apss.space.auckland.ac.nz/
---

>[!summary]
The University of Auckland's space systems program focuses on research, development, and education in aerospace engineering, satellite technology, and space-related systems. The program combines cutting-edge research with hands-on experience, offering opportunities for students and researchers to design, build, and launch small satellites, such as CubeSats. Leveraging New Zealand's growing role in the global space industry, including partnerships with Rocket Lab, the program aims to develop local talent and advance innovative technologies that support scientific exploration, commercial space applications, and sustainable space operations.

### 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[The University of Auckland]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[The University of Auckland]])
sort published desc
```
