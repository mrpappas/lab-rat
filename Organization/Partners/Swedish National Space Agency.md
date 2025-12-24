---

name: Swedish National Space Agency
website: https://www.rymdstyrelsen.se/en/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> Swedish National Space Agency

**Website:** https://www.rymdstyrelsen.se/en/

The Swedish National Space Agency (SNSA) is a government agency responsible for national and international space activities in Sweden. It oversees the development and implementation of Sweden's space policies, funds space research and technology development, and coordinates Sweden’s participation in international programs, such as those led by the European Space Agency (ESA). SNSA focuses on advancing scientific research, fostering innovation, and supporting satellite missions that address societal needs, such as climate monitoring, telecommunications, and Earth observation. By collaborating with academia, industry, and international partners, SNSA plays a key role in strengthening Sweden's position as a leader in space science and technology.

![[Swedish-National-Space-Agency.webp|300]]

## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[]])
sort launch_date desc
```
%%

| File                                                                        | Date             | Location                                              | Vehicle                                                 | Orbit & Mass              | Outcome |
| --------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | ------------------------------------------------------- | ------------------------- | ------- |
| [[Launch/Launches/032 - Catch Me If You Can.md\|032 - Catch Me If You Can]] | 2022-11-04 17:27 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 585 km \| 97.66° \| 50 kg | ✅       |

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

| File                                                                                                                                                                       | Published         |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/Rocket Lab Successfully Deploys 152nd Satellite.md\|Rocket Lab Successfully Deploys 152nd Satellite]]                                                               | November 04, 2022 |
| [[News/Rocket Lab to Attempt Next Mid-Air Helicopter Rocket Catch During Next Mission.md\|Rocket Lab to Attempt Next Mid-Air Helicopter Rocket Catch During Next Mission]] | November 01, 2022 |

%%DATAVIEW_PUBLISHER: end %%