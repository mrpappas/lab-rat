---
name: HawkEye 360
website: https://www.he360.com/
---

>[!summary]
HawkEye 360 is a geospatial analytics company that operates a constellation of satellites to detect, characterize, and geolocate radio frequency (RF) signals. Their services provide insights for applications such as maritime domain awareness, spectrum monitoring, and national security. By analyzing RF data, HawkEye 360 helps identify illegal activities like maritime piracy, smuggling, and unlicensed spectrum usage.

## 🚀 Launches
%%DATAVIEW_PUBLISHER: start
```
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[HawkEye 360]])
sort launch_date desc
```
%%

| File                                                                                                                  | launch_date      | outcome |
| --------------------------------------------------------------------------------------------------------------------- | ---------------- | ------- |
| [[Launch/Launches/033 'Virginia is for Launch Lovers' - Electron.md\|033 'Virginia is for Launch Lovers' - Electron]] | 2023-01-24 23:00 | Success |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table title as "Title", published as "Published"
from "News"
where contains(customer, [[HawkEye 360]])
sort published desc
```
%%

| File                                                                                                                                                                                                                               | Title                                                                                                       | Published         |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/Rocket Lab Successfully Launches First Electron Mission from U.S. Soil.md\|Rocket Lab Successfully Launches First Electron Mission from U.S. Soil]]                                                                         | Rocket Lab Successfully Launches First Electron Mission from U.S. Soil                                      | January 24, 2023  |
| [[News/Rocket Lab Sets New Date for First Electron Launch From U.S. Soil.md\|Rocket Lab Sets New Date for First Electron Launch From U.S. Soil]]                                                                                   | Rocket Lab Sets New Date for First Electron Launch From U.S. Soil                                           | January 11, 2023  |
| [[News/Rocket Lab Reschedules First U.S. Launch for January 2023, Provides Updates on Effect to Prior Q4 Guidance.md\|Rocket Lab Reschedules First U.S. Launch for January 2023, Provides Updates on Effect to Prior Q4 Guidance]] | Rocket Lab Reschedules First U.S. Launch for January 2023, Provides Updates on Effect to Prior Q4 Guidance  | December 19, 2022 |
| [[News/Rocket Lab Prepares to Launch First Mission from Wallops Island.md\|Rocket Lab Prepares to Launch First Mission from Wallops Island]]                                                                                       | Rocket Lab Prepares to Launch First Mission from Wallops Island                                             | December 17, 2022 |
| [[News/Rocket Lab Completes Final Launch Rehearsal Ahead of First Electron Mission from U.S. Soil.md\|Rocket Lab Completes Final Launch Rehearsal Ahead of First Electron Mission from U.S. Soil]]                                 | Rocket Lab Completes Final Launch Rehearsal Ahead of First Electron Mission from U.S. Soil                  | November 21, 2022 |
| [[News/Rocket Lab Announces Launch Window for Inaugural Electron Mission from Launch Complex 2 in Virginia.md\|Rocket Lab Announces Launch Window for Inaugural Electron Mission from Launch Complex 2 in Virginia]]               | Rocket Lab Announces Launch Window for Inaugural Electron Mission from Launch Complex 2 in Virginia         | November 09, 2022 |
| [[News/Electron Rocket Arrives at Launch Complex 2 for Rocket Lab’s Inaugural Mission from Virginia.md\|Electron Rocket Arrives at Launch Complex 2 for Rocket Lab’s Inaugural Mission from Virginia]]                             | Electron Rocket Arrives at Launch Complex 2 for Rocket Lab’s Inaugural Mission from Virginia                | October 12, 2022  |

%%DATAVIEW_PUBLISHER: end %%