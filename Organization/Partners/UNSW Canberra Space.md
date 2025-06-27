---

name: UNSW Canberra Space
website: https://www.unsw.edu.au/canberra/our-research/research-centres-institutes/unsw-canberra-space
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> UNSW Canberra Space

**Website:** https://www.unsw.edu.au/canberra/our-research/research-centres-institutes/unsw-canberra-space

>[!summary]
UNSW Canberra Space is a leading Australian space research and development center, based at the [University of New South Wales in Canberra](https://www.unsw.edu.au/canberra). Specializing in the design, development, and operation of small satellites, UNSW Canberra Space focuses on advancing space technology for Earth observation, defense, and scientific research. The center collaborates with government agencies, including the Australian Defence Force, and industry partners to deliver innovative and resilient space systems. With a strong emphasis on space situational awareness, satellite communications, and autonomous systems, UNSW Canberra Space plays a pivotal role in supporting Australia's growing presence in the global space industry.

## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[UNSW Canberra Space]])
sort launch_date desc
```
%%

| File                                                                      | Date             | Location                                              | Vehicle                          | Orbit & Mass                         | Outcome   |
| ------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ------------------------------------ | --------- |
| [[Launch/Launches/019 - They Go Up So Fast.md\|019 - They Go Up So Fast]] | 2021-03-22 22:30 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 450 km and 550 km \| 45° \| Unknown  | ✅ Success |
| [[Launch/Launches/012 - Don't Stop Me Now.md\|012 - Don't Stop Me Now]]   | 2020-06-13 05:12 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 570 x 590 km \| 97.75° \| Classified | ✅ Success |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[UNSW Canberra Space]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                                           | Published         |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------- |
| [[News/Rocket Lab Successfully Launches 19th Electron, Deploys 100th Satellite.md\|Rocket Lab Successfully Launches 19th Electron, Deploys 100th Satellite]]                                                                                                                   | March 23, 2021    |
| [[News/Rocket Lab’s Next Mission to Launch 100th Satellite and Deploy Next-Generation Photon Spacecraft in Preparation for Moon Mission.md\|Rocket Lab’s Next Mission to Launch 100th Satellite and Deploy Next-Generation Photon Spacecraft in Preparation for Moon Mission]] | February 09, 2021 |
| [[News/Rocket Lab’s Next Mission to Launch Satellites for NASA, NRO and the University of New South Wales.md\|Rocket Lab’s Next Mission to Launch Satellites for NASA, NRO and the University of New South Wales]]                                                             | March 09, 2020    |

%%DATAVIEW_PUBLISHER: end %%