---

name: OHB Group
website: https://www.ohb.de/en/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> OHB Group
## Partner Details

**Website:** https://www.ohb.de/en/

OHB Group is a leading European space and technology company specializing in the development and execution of innovative space systems and applications. Headquartered in Bremen, Germany, OHB operates across the full spectrum of the space value chain, including satellite manufacturing, space transportation, Earth observation, and exploration missions. The company’s capabilities range from building small and medium-sized satellites for telecommunications, Earth observation, and scientific research to contributing to major space infrastructure projects such as Galileo, Copernicus, and ISS-related systems. With a strong emphasis on innovation, reliability, and partnerships, OHB Group supports government agencies, commercial customers, and international space organizations in achieving their goals in space.

## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[OHB Group]])
sort launch_date desc
```
%%

| File                                                                                          | Date             | Location                                              | Vehicle                          | Orbit & Mass            | Outcome |
| --------------------------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ----------------------- | ------- |
| [[Launch/Launches/018 - Another One Leaves the Crust.md\|018 - Another One Leaves the Crust]] | 2021-01-20 07:26 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 1200 km \| 90° \| 50 kg | ✅       |

%%DATAVIEW_PUBLISHER: end %%

## News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[OHB Group]])
sort published desc
```
%%

| File                                                                                                                                                                                                                 | Published        |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- |
| [[News/Rocket Lab Demonstrates New Orbital Maneuvering Capability with Most Complex Kick Stage Mission Yet.md\|Rocket Lab Demonstrates New Orbital Maneuvering Capability with Most Complex Kick Stage Mission Yet]] | January 26, 2021 |
| [[News/Rocket Lab’s First Mission of 2021 to Launch Communications Satellite for OHB Group  Rocket Lab.md\|Rocket Lab’s First Mission of 2021 to Launch Communications Satellite for OHB Group  Rocket Lab]]         | January 05, 2021 |
| [[News/Rocket Lab to Launch Dedicated Mission for European Space Technology Company OHB Group.md\|Rocket Lab to Launch Dedicated Mission for European Space Technology Company OHB Group]]                           | August 25, 2020  |

%%DATAVIEW_PUBLISHER: end %%