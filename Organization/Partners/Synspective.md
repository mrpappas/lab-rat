---

name: Synspective
website: https://synspective.com/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> Synspective
## Partner Details

**Website:** https://synspective.com/

Synspective is a Japanese startup that develops and operates [[📦 Payload Types#Synthetic Aperture Radar (SAR)|Synthetic Aperture Radar (SAR)]] satellites to provide high-frequency, high-resolution Earth observation data. The company’s mission is to enable smarter decision-making through precise geospatial insights, focusing on areas such as urban development, disaster response, infrastructure monitoring, and resource management. By leveraging its constellation of SAR satellites, Synspective delivers consistent, cloud-penetrating imagery, ensuring reliable data regardless of weather or lighting conditions. Its solutions support governments and businesses in addressing global challenges through advanced analytics and actionable intelligence.

![[Pasted image 20251211020132.jpg|300]]

## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[]])
sort launch_date desc
```
%%

| File                                                                                    | Date             | Location                                              | Vehicle                          | Orbit & Mass              | Outcome |
| --------------------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ------------------------- | ------- |
| [[Launch/Launches/073 - Owl New World.md\|073 - Owl New World]]                         | 2025-10-14 16:33 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC-1A]] | [[Launch/Electron.md\|Electron]] | 583 km \| 42° \| 100 kg   | ✅       |
| [[Launch/Launches/058 - Owl The Way Up.md\|058 - Owl The Way Up]]                       | 2024-12-21 14:16 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 574 km \| 97° \| 100 kg   | ✅       |
| [[Launch/Launches/051 - Owl For One, One For Owl.md\|051 - Owl For One, One For Owl]]   | 2024-08-02 16:39 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 543 km \| 43° \| 100 kg   | ✅       |
| [[Launch/Launches/045 - Owl Night Long.md\|045 - Owl Night Long]]                       | 2024-03-12 14:00 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 561 km \| 97° \| 100 kg   | ✅       |
| [[Launch/Launches/030 - The Owl Spreads Its Wings.md\|030 - The Owl Spreads Its Wings]] | 2022-09-15 20:30 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 563 km \| 97° \| 100 kg   | ✅       |
| [[Launch/Launches/024 - The Owl's Night Continues.md\|024 - The Owl's Night Continues]] | 2022-02-28 20:37 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 561 km \| 97° \| 150 kg   | ✅       |
| [[Launch/Launches/017 - The Owl's Night Begins.md\|017 - The Owl's Night Begins]]       | 2020-12-15 10:09 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 500 km \| 97.3° \| 150 kg | ✅       |

%%DATAVIEW_PUBLISHER: end %%

## Space Systems

### StriX

Synspective's StriX satellites are a series of small, innovative, and cost-effective [[📦 Payload Types#Synthetic Aperture Radar (SAR)|Synthetic Aperture Radar (SAR)]] satellites designed for high-resolution Earth observation. Developed in collaboration with the University of Tokyo, the Tokyo Institute of Technology, and the Japan Aerospace Exploration Agency (JAXA), the StriX series originated from Japan's ImPACT Program, aiming to enhance information-gathering capabilities for emergency response and other applications.

[Synspective Strix](https://synspective.com/satellite/satellite-strix/)

| Specs                | Value                                                                                                 |
| -------------------- | ----------------------------------------------------------------------------------------------------- |
| Mass                 | 100 kg                                                                                                |
| **Size**             | 0.8m × 1.0m × 0.8m<br>(Before antenna deployment)<br>5.0m × 1.0m × 0.8m<br>(After antenna deployment) |
| **Antenna Size**     | 5m × 0.8m                                                                                             |
| **Propulsion**       | Yes                                                                                                   |
| **Mission Life**     | Approximately 5 years                                                                                 |
| **Center Frequency** | 9.65 GHz (X-band)                                                                                     |
| **Look Direction**   | Right and Left                                                                                        |
| **PRF**              | Up to 7 kHz                                                                                           |
| **Chirp Bandwith**   | Up to 300 MHz                                                                                         |
| **RF Peak Power**    | 1kW                                                                                                   |
| **Polarization**     | VV                                                                                                    |
| **Off-Nadir Angle**  | 15 – 45 degrees                                                                                       |


![[Pasted image 20241224215520.png]]


## News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                                                   | Published          |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ |
| [[News/Mission Success Rocket Lab Launches Latest Satellite for Synspective.md\|Mission Success Rocket Lab Launches Latest Satellite for Synspective]]                                                                                                                                 | October 15, 2025   |
| [[News/Rocket Lab Sets Launch Schedule for 1st of 21 New Missions with Synspective.md\|Rocket Lab Sets Launch Schedule for 1st of 21 New Missions with Synspective]]                                                                                                                   | October 01, 2025   |
| [[News/Rocket Lab and Synspective Strike Another 10-Launch Deal, Boosting Contracted Missions to 21 Electron Launches.md\|Rocket Lab and Synspective Strike Another 10-Launch Deal, Boosting Contracted Missions to 21 Electron Launches]]                                             | September 29, 2025 |
| [[News/Rocket Lab Successfully Deploys Satellite for Synspective, Caps Off Year with 60% Increase in Launches YoY.md\|Rocket Lab Successfully Deploys Satellite for Synspective, Caps Off Year with 60% Increase in Launches YoY]]                                                     | December 22, 2024  |
| [[News/Rocket Lab Sets Launch Window to Deploy Synspective Satellites.md\|Rocket Lab Sets Launch Window to Deploy Synspective Satellites]]                                                                                                                                             | December 05, 2024  |
| [[News/Rocket Lab Successfully Completes Latest Launch for Synspective.md\|Rocket Lab Successfully Completes Latest Launch for Synspective]]                                                                                                                                           | August 03, 2024    |
| [[News/Rocket Lab Sets Launch Date for 51st Electron Mission, Prepares to Deploy Latest Satellites in Multi-Launch Contract for Synspective.md\|Rocket Lab Sets Launch Date for 51st Electron Mission, Prepares to Deploy Latest Satellites in Multi-Launch Contract for Synspective]] | July 24, 2024      |
| [[News/Rocket Lab Signs Record Deal for 10 Electron Launches with Synspective.md\|Rocket Lab Signs Record Deal for 10 Electron Launches with Synspective]]                                                                                                                             | June 18, 2024      |
| [[News/Rocket Lab Successfully Launches 45th Electron Mission, 4th for Longtime Partner Synspective.md\|Rocket Lab Successfully Launches 45th Electron Mission, 4th for Longtime Partner Synspective]]                                                                                 | March 13, 2024     |
| [[News/Rocket Lab Schedules Launch Date for 45th Electron Mission to Deploy Earth-Imaging Satellite for Synspective.md\|Rocket Lab Schedules Launch Date for 45th Electron Mission to Deploy Earth-Imaging Satellite for Synspective]]                                                 | February 20, 2024  |
| [[News/Rocket Lab Signs Multi-Launch Deal to Further Deploy Synspective Constellation.md\|Rocket Lab Signs Multi-Launch Deal to Further Deploy Synspective Constellation]]                                                                                                             | July 13, 2023      |
| [[News/Rocket Lab Successfully Launches 30th Electron Rocket & 150th Satellite to Space.md\|Rocket Lab Successfully Launches 30th Electron Rocket & 150th Satellite to Space]]                                                                                                         | September 15, 2022 |
| [[News/Rocket Lab to Launch 150th Satellite on Upcoming Mission for Synspective.md\|Rocket Lab to Launch 150th Satellite on Upcoming Mission for Synspective]]                                                                                                                         | August 15, 2022    |
| [[News/Rocket Lab Successfully Launches Second Mission for Synspective, Deploys 110th Satellite to Orbit.md\|Rocket Lab Successfully Launches Second Mission for Synspective, Deploys 110th Satellite to Orbit]]                                                                       | March 01, 2022     |
| [[News/Rocket Lab Brings Forward Launch for Earth Imaging Company Synspective.md\|Rocket Lab Brings Forward Launch for Earth Imaging Company Synspective]]                                                                                                                             | February 09, 2022  |
| [[News/Rocket Lab to Launch Three Dedicated Electron Missions for Earth Imaging Company Synspective.md\|Rocket Lab to Launch Three Dedicated Electron Missions for Earth Imaging Company Synspective]]                                                                                 | December 07, 2021  |
| [[News/Rocket Lab Successfully Launches 17th Electron Mission, Deploys SAR Satellite for Synspective.md\|Rocket Lab Successfully Launches 17th Electron Mission, Deploys SAR Satellite for Synspective]]                                                                               | December 15, 2020  |
| [[News/Rocket Lab to Launch Dedicated Mission for  Japanese Earth Imaging Company Synspective.md\|Rocket Lab to Launch Dedicated Mission for  Japanese Earth Imaging Company Synspective]]                                                                                             | November 24, 2020  |
| [[News/Rocket Lab to Launch Dedicated Mission for Japanese Space Industry Start-up Company Synspective.md\|Rocket Lab to Launch Dedicated Mission for Japanese Space Industry Start-up Company Synspective]]                                                                           | April 14, 2020     |

%%DATAVIEW_PUBLISHER: end %%