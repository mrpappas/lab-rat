---
customer: "[[iQPS]]"
---
[[Home|🏠]] > [[Contracts & Vehicles]] > iQPS Four Launch Contract 2024

>[!success] Contract Complete

Four Launch [[Electron]] contract for [[iQPS]] to deploy four (one per launch) of the 36 [[iQPS#QPS-SAR|QPS-SAR]] Synthetic Aperture Radar satellites for its earth observation constellation.
- **Customer**: [[iQPS]]
- **Contract Value**: Unknown
- **Launches**: 4
- **Date**: July 2024
- **Vehicle**: [[Electron]]

## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(contract, [[]])
sort launch_date desc
```
%%

| File                                                                                        | Date             | Location                                              | Vehicle                                            | Orbit & Mass            | Outcome |
| ------------------------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------------------------- | ----------------------- | ------- |
| [[Launch/Launches/069 - The Harvest Goddess Thrives.md\|069 - The Harvest Goddess Thrives]] | 2025-08-05 04:10 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Hardware/Launch Vehicles/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg | ✅       |
| [[Launch/Launches/066 - The Mountain God Guards.md\|066 - The Mountain God Guards]]         | 2025-06-11 15:15 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Hardware/Launch Vehicles/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg | ✅       |
| [[Launch/Launches/064 - The Sea God Sees.md\|064 - The Sea God Sees]]                       | 2025-05-17 08:17 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Hardware/Launch Vehicles/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg | ✅       |
| [[Launch/Launches/061 - The Lightning God Reigns.md\|061 - The Lightning God Reigns]]       | 2025-03-15 00:00 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Hardware/Launch Vehicles/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg | ✅       |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%% DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(contract, [[]])
sort published desc

```
%%

| File                                                                                                                                                                 | Published         |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/Rocket Lab Signs Multi-Launch Contract with iQPS for Four Electron Missions.md\|Rocket Lab Signs Multi-Launch Contract with iQPS for Four Electron Missions]] | February 03, 2025 |

%% DATAVIEW_PUBLISHER: end %%