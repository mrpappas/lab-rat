---

name: The University of Auckland
website: https://apss.space.auckland.ac.nz/
---

**Name:** The University of Auckland
**Website:** https://apss.space.auckland.ac.nz/

>[!summary]
The University of Auckland's space systems program focuses on research, development, and education in aerospace engineering, satellite technology, and space-related systems. The program combines cutting-edge research with hands-on experience, offering opportunities for students and researchers to design, build, and launch small satellites, such as CubeSats. Leveraging New Zealand's growing role in the global space industry, including partnerships with Rocket Lab, the program aims to develop local talent and advance innovative technologies that support scientific exploration, commercial space applications, and sustainable space operations.

## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date
from "Launch/Launches"
where contains(customer, [[The University of Auckland]]) and outcome = "Success"
sort launch_date desc
```
%%

| File                                                                                        | launch_date      |
| ------------------------------------------------------------------------------------------- | ---------------- |
| [[Launch/Launches/016 'Return to Sender' - Electron.md\|016 'Return to Sender' - Electron]] | 2020-11-20 02:20 |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[The University of Auckland]])
sort published desc
```
%%

| File                                                                                                                                   | Published         |
| -------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/How to bring a rocket back from space.md\|How to bring a rocket back from space]]                                               | November 30, 2020 |
| [[News/Rocket Lab Launches 16th Mission, Completes Booster Recovery.md\|Rocket Lab Launches 16th Mission, Completes Booster Recovery]] | November 22, 2020 |
| [[News/Rocket Lab to Attempt First Stage Recovery on Next Mission.md\|Rocket Lab to Attempt First Stage Recovery on Next Mission]]     | November 05, 2020 |
| [[News/Rocket Lab to Launch Most Diverse Mission Yet.md\|Rocket Lab to Launch Most Diverse Mission Yet]]                               | November 02, 2020 |

%%DATAVIEW_PUBLISHER: end %%