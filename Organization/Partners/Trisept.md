---
name: Trisept
website: https://trisept.com/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> Trisept

**Website:** https://trisept.com/

TriSept provides launch integration, mission management, and engineering services for satellite missions of all sizes. With expertise spanning rideshare coordination, dedicated launches, and complex multi-payload deployments, TriSept ensures reliable and efficient access to space for commercial, government, and defense customers. Their proven track record, combined with mission assurance and innovative solutions, enables seamless integration from concept to orbit.

![[Pasted image 20251211015429.png]]
## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[]])
sort launch_date desc
```
%%

| File                                                                      | Date             | Location                                              | Vehicle                          | Orbit & Mass                        | Outcome |
| ------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ----------------------------------- | ------- |
| [[Launch/Launches/019 - They Go Up So Fast.md\|019 - They Go Up So Fast]] | 2021-03-22 22:30 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 450 km and 550 km \| 45° \| Unknown | ✅       |
| [[Launch/Launches/016 - Return to Sender.md\|016 - Return to Sender]]     | 2020-11-20 02:20 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 500 km \| 97.3° \| 200 kg           | ✅       |

%%DATAVIEW_PUBLISHER: end %%

## News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[]])
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