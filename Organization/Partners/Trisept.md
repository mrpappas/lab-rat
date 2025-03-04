---

name: Trisept
website: https://trisept.com/
---

**Name:** Trisept
**Website:** https://trisept.com/

>[!summary]
TriSept provides launch integration, mission management, and engineering services for satellite missions of all sizes. With expertise spanning rideshare coordination, dedicated launches, and complex multi-payload deployments, TriSept ensures reliable and efficient access to space for commercial, government, and defense customers. Their proven track record, combined with mission assurance and innovative solutions, enables seamless integration from concept to orbit.


## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date
from "Launch/Launches"
where contains(customer, [[Trisept]]) and outcome = "Success"
sort launch_date desc
```
%%

| File                                                                                            | launch_date      |
| ----------------------------------------------------------------------------------------------- | ---------------- |
| [[Launch/Launches/019 'They Go Up So Fast' - Electron.md\|019 'They Go Up So Fast' - Electron]] | 2021-03-22 22:30 |
| [[Launch/Launches/016 'Return to Sender' - Electron.md\|016 'Return to Sender' - Electron]]     | 2020-11-20 02:20 |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[Trisept]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                                           | Published         |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------- |
| [[News/Rocket Lab Successfully Launches 19th Electron, Deploys 100th Satellite.md\|Rocket Lab Successfully Launches 19th Electron, Deploys 100th Satellite]]                                                                                                                   | March 23, 2021    |
| [[News/Rocket Lab’s Next Mission to Launch 100th Satellite and Deploy Next-Generation Photon Spacecraft in Preparation for Moon Mission.md\|Rocket Lab’s Next Mission to Launch 100th Satellite and Deploy Next-Generation Photon Spacecraft in Preparation for Moon Mission]] | February 09, 2021 |
| [[News/How to bring a rocket back from space.md\|How to bring a rocket back from space]]                                                                                                                                                                                       | November 30, 2020 |
| [[News/Rocket Lab Launches 16th Mission, Completes Booster Recovery.md\|Rocket Lab Launches 16th Mission, Completes Booster Recovery]]                                                                                                                                         | November 22, 2020 |
| [[News/Rocket Lab to Attempt First Stage Recovery on Next Mission.md\|Rocket Lab to Attempt First Stage Recovery on Next Mission]]                                                                                                                                             | November 05, 2020 |
| [[News/Rocket Lab to Launch Most Diverse Mission Yet.md\|Rocket Lab to Launch Most Diverse Mission Yet]]                                                                                                                                                                       | November 02, 2020 |

%%DATAVIEW_PUBLISHER: end %%