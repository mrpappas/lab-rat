---

name: Boston University
website: https://www.bu.edu/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> Boston University

**Website:** https://www.bu.edu/

## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[Boston University]])
sort launch_date desc
```
%%

| File                                                                    | Date             | Location                                              | Vehicle                          | Orbit & Mass                         | Outcome   |
| ----------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ------------------------------------ | --------- |
| [[Launch/Launches/012 - Don't Stop Me Now.md\|012 - Don't Stop Me Now]] | 2020-06-13 05:12 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 570 x 590 km \| 97.75° \| Classified | ✅ Success |

%%DATAVIEW_PUBLISHER: end %%


## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[Boston University]])
sort published desc
```
%%

| File                                                                                                                                                                                                               | Published      |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------- |
| [[News/Rocket Lab’s Next Mission to Launch Satellites for NASA, NRO and the University of New South Wales.md\|Rocket Lab’s Next Mission to Launch Satellites for NASA, NRO and the University of New South Wales]] | March 09, 2020 |

%%DATAVIEW_PUBLISHER: end %%