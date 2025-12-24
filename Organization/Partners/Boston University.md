---

name: Boston University
website: https://www.bu.edu/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> Boston University

**Website:** https://www.bu.edu/

Boston University (BU) is a significant player in space technology through its Center for Space Physics (CSP), fostering interdisciplinary research in space science, engineering, and instrumentation, with projects ranging from building sensors for NASA missions (like the LEXI Moon Telescope) to studying heliophysics and planetary atmospheres, involving collaborations across Astronomy, Engineering (Mech & Elec/Comp), and developing both large-scale and small satellite tech. 

![[Pasted image 20251211030744.png|300]]

## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[]])
sort launch_date desc
```
%%

| File                                                                    | Date             | Location                                              | Vehicle                                            | Orbit & Mass                         | Outcome |
| ----------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------------------------- | ------------------------------------ | ------- |
| [[Launch/Launches/012 - Don't Stop Me Now.md\|012 - Don't Stop Me Now]] | 2020-06-13 05:12 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Hardware/Launch Vehicles/Electron.md\|Electron]] | 570 x 590 km \| 97.75° \| Classified | ✅       |

%%DATAVIEW_PUBLISHER: end %%


## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[]])
sort published desc
```
%%

| File                                                                                                                                                                                                               | Published      |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------- |
| [[News/Rocket Lab’s Next Mission to Launch Satellites for NASA, NRO and the University of New South Wales.md\|Rocket Lab’s Next Mission to Launch Satellites for NASA, NRO and the University of New South Wales]] | March 09, 2020 |

%%DATAVIEW_PUBLISHER: end %%