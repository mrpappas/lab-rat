---

name: HawkEye 360
website: https://www.he360.com/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> HawkEye 360

**Website:** https://www.he360.com/

>[!summary]
HawkEye 360 is a geospatial analytics company that operates a constellation of satellites to detect, characterize, and geolocate radio frequency (RF) signals. Their services provide insights for applications such as maritime domain awareness, spectrum monitoring, and national security. By analyzing RF data, HawkEye 360 helps identify illegal activities like maritime piracy, smuggling, and unlicensed spectrum usage.

## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[HawkEye 360]])
sort launch_date desc
```
%%

| File                                                                                            | Date             | Location                                               | Vehicle                          | Orbit & Mass                | Outcome |
| ----------------------------------------------------------------------------------------------- | ---------------- | ------------------------------------------------------ | -------------------------------- | --------------------------- | ------- |
| [[Launch/Launches/067 - Get The Hawk Outta Here.md\|067 - Get The Hawk Outta Here]]             | 2025-06-26 17:00 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC-1A]]  | [[Launch/Electron.md\|Electron]] | 520 km \| 97.45° \| Unknown | ✅       |
| [[Launch/Launches/033 - Virginia is for Launch Lovers.md\|033 - Virginia is for Launch Lovers]] | 2023-01-24 23:00 | [[Locations/Launch Complex 2.md#Launch Pad 0C\|LC2-0]] | [[Launch/Electron.md\|Electron]] | 550 km \| 40.5° \| 40 kg    | ✅       |

%%DATAVIEW_PUBLISHER: end %%
## 🛰️ Space Systems

### Hawk Satellite

Each HawkEye microsatellite carries two instruments, a software defined radio (SDR) and an RF front-end module. SDR consists of two components, an embedded processor, and three baseband signal processors. The onboard instruments process radio signals from various sources, enabling HawkEye 360 to detect and analyze RF signals across different frequencies. These instruments capture, filter, and convert the signals into usable data. The system allows for monitoring multiple frequencies at once, covering a wide range of applications.

Customers are primarily paying for the ability to track and analyze RF signals, which can be used for applications such as monitoring maritime activity, managing spectrum usage, and detecting illegal transmissions. This data provides valuable insights for government agencies, telecommunications, and defense sectors.

Source: https://www.eoportal.org/satellite-missions/hawkeye-360#eop-quick-facts-section

| Specification | Value         |
| ------------- | ------------- |
| Mass          | 30kg          |
| Mission Life  | 3 Years       |
| Waveband      | 70 MHz - 6GHz |


![[Pasted image 20250403032519.png]]



## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[HawkEye 360]])
sort published desc
```
%%

| File                                                                                                                                                                                                                               | Published         |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/Rocket Lab Successfully Launches 67th Electron Mission, Schedules Next Launch in Less Than 48 Hours.md\|Rocket Lab Successfully Launches 67th Electron Mission, Schedules Next Launch in Less Than 48 Hours]]               | June 26, 2025     |
| [[News/Rocket Lab Executes Responsive Reschedule of Electron Manifest to Launch Next Mission in Two Days’ Time.md\|Rocket Lab Executes Responsive Reschedule of Electron Manifest to Launch Next Mission in Two Days’ Time]]       | June 24, 2025     |
| [[News/Rocket Lab Successfully Launches First Electron Mission from U.S. Soil.md\|Rocket Lab Successfully Launches First Electron Mission from U.S. Soil]]                                                                         | January 24, 2023  |
| [[News/Rocket Lab Sets New Date for First Electron Launch From U.S. Soil.md\|Rocket Lab Sets New Date for First Electron Launch From U.S. Soil]]                                                                                   | January 11, 2023  |
| [[News/Rocket Lab Reschedules First U.S. Launch for January 2023, Provides Updates on Effect to Prior Q4 Guidance.md\|Rocket Lab Reschedules First U.S. Launch for January 2023, Provides Updates on Effect to Prior Q4 Guidance]] | December 19, 2022 |
| [[News/Rocket Lab Prepares to Launch First Mission from Wallops Island.md\|Rocket Lab Prepares to Launch First Mission from Wallops Island]]                                                                                       | December 17, 2022 |
| [[News/Rocket Lab Completes Final Launch Rehearsal Ahead of First Electron Mission from U.S. Soil.md\|Rocket Lab Completes Final Launch Rehearsal Ahead of First Electron Mission from U.S. Soil]]                                 | November 21, 2022 |
| [[News/Rocket Lab Announces Launch Window for Inaugural Electron Mission from Launch Complex 2 in Virginia.md\|Rocket Lab Announces Launch Window for Inaugural Electron Mission from Launch Complex 2 in Virginia]]               | November 09, 2022 |
| [[News/Electron Rocket Arrives at Launch Complex 2 for Rocket Lab’s Inaugural Mission from Virginia.md\|Electron Rocket Arrives at Launch Complex 2 for Rocket Lab’s Inaugural Mission from Virginia]]                             | October 12, 2022  |
| [[News/Rocket Lab Secures Multi-Launch Contract with HawkEye 360, Confirms First Launch Planned from Virginia.md\|Rocket Lab Secures Multi-Launch Contract with HawkEye 360, Confirms First Launch Planned from Virginia]]         | April 19, 2022    |

%%DATAVIEW_PUBLISHER: end %%