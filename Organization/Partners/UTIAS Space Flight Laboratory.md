---

name: UTIAS Space Flight Laboratory
website: https://www.utias-sfl.net/
---

**Name:** UTIAS Space Flight Laboratory
**Website:** https://www.utias-sfl.net/

>[!summary]
UTIAS Flight Lab, part of the University of Toronto Institute for Aerospace Studies, is a leading developer of small satellite missions and advanced space systems. Specializing in microsatellites, nanosatellites, and CubeSats, SFL provides end-to-end mission solutions, including satellite design, manufacturing, integration, and operations. Known for its innovation in low-cost, high-performance satellites, SFL supports a wide range of applications, such as Earth observation, remote sensing, communications, and scientific research. With a proven track record of launching successful missions globally, SFL is a key player in enabling access to space for commercial, academic, and government clients.


## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[UTIAS Space Flight Laboratory]])
sort launch_date desc
```
%%

| File                                                              | Location                                              | Vehicle                          | Orbit & Mass               | Outcome   |
| ----------------------------------------------------------------- | ----------------------------------------------------- | -------------------------------- | -------------------------- | --------- |
| [[Launch/Launches/039 'Baby Come Back'.md\|039 'Baby Come Back']] | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 1000 km \| 99.45° \| 86 kg | ✅ Success |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[UTIAS Space Flight Laboratory]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                       | Published     |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| [[News/Rocket Lab Deploys Satellites for NASA and Commercial Constellation Operators,  Successfully Recovers Booster.md\|Rocket Lab Deploys Satellites for NASA and Commercial Constellation Operators,  Successfully Recovers Booster]]                   | July 17, 2023 |
| [[News/Rocket Lab Prepares to Launch Mix of NASA and Commercial Satellites, and Takes Next Step in Rocket Reusability Program.md\|Rocket Lab Prepares to Launch Mix of NASA and Commercial Satellites, and Takes Next Step in Rocket Reusability Program]] | July 17, 2023 |
| [[News/Rocket Lab to Launch Multiple Satellites as Part of Upcoming Recovery Mission.md\|Rocket Lab to Launch Multiple Satellites as Part of Upcoming Recovery Mission]]                                                                                   | June 22, 2023 |
| [[News/Space Flight Laboratory Selects Rocket Lab to Launch Telesat Broadband Satellite.md\|Space Flight Laboratory Selects Rocket Lab to Launch Telesat Broadband Satellite]]                                                                             | May 31, 2023  |

%%DATAVIEW_PUBLISHER: end %%