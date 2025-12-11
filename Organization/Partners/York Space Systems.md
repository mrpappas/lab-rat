---

name: York Space
website: https://www.yorkspacesystems.com/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> York Space Systems
## Partner Details

**Website:** https://www.yorkspacesystems.com/

York Space Systems is a U.S.-based satellite manufacturer specializing in the design and production of small and medium-sized satellites for commercial and government applications. Known for its standardized spacecraft platforms, such as the S-CLASS, York aims to reduce costs and streamline production timelines. The company provides end-to-end satellite solutions, including mission planning, satellite integration, and operations support, catering to industries like Earth observation, communications, and defense.

![[York.webp|300]]
## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[]])
sort launch_date desc
```
%%

| File                                                  | Date             | Location                                              | Vehicle                          | Orbit & Mass            | Outcome |
| ----------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ----------------------- | ------- |
| [[Launch/Launches/006 - STP-27RD.md\|006 - STP-27RD]] | 2019-05-05 06:00 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 500 km \| 40° \| 180 kg | ✅       |

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

| File                                                                                                                                                                                     | Published      |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- |
| [[News/Rocket Lab successfully launches three R&D satellites to orbit for the U.S. Air Force.md\|Rocket Lab successfully launches three R&D satellites to orbit for the U.S. Air Force]] | May 05, 2019   |
| [[News/Rocket Lab to launch three R&D satellites for the U.S. Air Force.md\|Rocket Lab to launch three R&D satellites for the U.S. Air Force]]                                           | April 04, 2019 |

%%DATAVIEW_PUBLISHER: end %%