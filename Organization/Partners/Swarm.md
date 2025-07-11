---

name: Swarm
website: https://en.wikipedia.org/wiki/Swarm_Technologies
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> Swarm

**Website:** https://en.wikipedia.org/wiki/Swarm_Technologies

Subsidiary of [[SpaceX]]

>[!summary]
Swarm Technologies, a subsidiary of SpaceX, provides affordable and reliable global satellite connectivity for IoT (Internet of Things) devices. Using its constellation of miniature satellites, known as SpaceBEEs, Swarm delivers low-cost, low-bandwidth communication for industries like agriculture, maritime, logistics, and environmental monitoring. The company’s focus is on enabling global coverage for IoT applications, even in remote and underserved areas, through its compact hardware and efficient data services. As part of SpaceX, Swarm leverages synergies in innovation and infrastructure to expand its reach and make satellite IoT connectivity accessible worldwide.


## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[Swarm]])
sort launch_date desc
```
%%

| File                                                                  | Date             | Location                                              | Vehicle                          | Orbit & Mass              | Outcome |
| --------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ------------------------- | ------- |
| [[Launch/Launches/016 - Return to Sender.md\|016 - Return to Sender]] | 2020-11-20 02:20 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 500 km \| 97.3° \| 200 kg | ✅       |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[Swarm]])
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

### ✏️ Notes

- Acquired by [[SpaceX]] August 6 2021. [Source](https://www.satellitetoday.com/finance/2021/08/09/spacex-buys-out-satellite-iot-startup-swarm-technologies/)