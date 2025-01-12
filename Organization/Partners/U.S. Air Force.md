---
name: U.S. Air Force
website: https://www.airforce.com/
---

>[!summary]
>The U.S. Air Force (USAF) plays a vital role in national security through its operations in air, space, and cyber domains, with a significant focus on space capabilities. Before the establishment of the [[U.S. Space Force]] in 2019, the USAF managed the majority of the Department of Defense's space operations. Its contributions include developing and maintaining critical satellite systems for global positioning (GPS), missile warning, communications, and weather monitoring. The USAF also pioneered space surveillance, orbital debris tracking, and space situational awareness to ensure safe and secure operations in Earth's orbit. Today, the Air Force continues to support space missions through collaboration with the Space Force, focusing on advanced technologies, launch systems, and integrating space capabilities into joint military operations to maintain U.S. superiority in space.
## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[U.S. Air Force]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[U.S. Air Force]])
sort published desc
```
