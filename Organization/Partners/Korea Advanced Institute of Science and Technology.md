---
name: KAIST (Korea Advanced Institute of Science and Technology)
website: https://www.kaist.ac.kr/en/
---


>[!summary]
The **Korea Advanced Institute of Science and Technology (KAIST)** is South Korea's leading research-oriented university, recognized for its advancements in science, engineering, and technology. In the space sector, KAIST is notable for its contributions to satellite development and space technology research. The university's **[Satellite Technology Research Center (SaTReC)](https://satrec.kaist.ac.kr/e_01_01.php)** has developed and launched several small satellites, including the **[KITSAT](https://en.wikipedia.org/wiki/KITSAT-1) series** and more advanced Earth observation satellites. These satellites support scientific research, technology demonstration, and space education.
>
KAIST collaborates with international partners and government agencies, playing a significant role in South Korea's space program by fostering innovation, talent development, and the deployment of cutting-edge space technologies.

## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Korea Advanced Institute of Science and Technology]])
sort launch_date desc
```

## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Korea Advanced Institute of Science and Technology]])
sort published desc
```
