---
name: iQPS (Institute for Q-shu Pioneers of Space, Inc.)
website: https://i-qps.net/en/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> iQPS

## Partner Details

**🔗 Website:** https://i-qps.net/en/

iQPS (Institute for Q-shu Pioneers of Space) is a Japanese company focused on developing and deploying [[📦 Payload Types#Synthetic Aperture Radar (SAR)|Synthetic Aperture Radar (SAR)]] satellites.
They are working toward establishing a constellation of 36 small SAR satellites, aiming to provide near-real-time imaging with high-frequency revisits. Their compact satellites deliver sub-meter resolution data, enabling industries such as disaster management, infrastructure monitoring, agriculture, and defense to benefit from precise and timely Earth observation insights.
iQPS has launched several satellites to demonstrate its SAR capabilities and is actively scaling its constellation to offer comprehensive global coverage.

## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[iQPS]])
sort launch_date desc
```
%%

| File                                                                                        | Date             | Location                                              | Vehicle                          | Orbit & Mass            | Outcome |
| ------------------------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ----------------------- | ------- |
| [[Launch/Launches/074 - The Nation God Navigates.md\|074 - The Nation God Navigates]]       | 2025-11-05 19:51 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC-1B]] | [[Launch/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg | ✅       |
| [[Launch/Launches/069 - The Harvest Goddess Thrives.md\|069 - The Harvest Goddess Thrives]] | 2025-08-05 04:10 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg | ✅       |
| [[Launch/Launches/066 - The Mountain God Guards.md\|066 - The Mountain God Guards]]         | 2025-06-11 15:15 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg | ✅       |
| [[Launch/Launches/064 - The Sea God Sees.md\|064 - The Sea God Sees]]                       | 2025-05-17 08:17 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg | ✅       |
| [[Launch/Launches/061 - The Lightning God Reigns.md\|061 - The Lightning God Reigns]]       | 2025-03-15 00:00 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg | ✅       |
| [[Launch/Launches/042 - The Moon God Awakens.md\|042 - The Moon God Awakens]]               | 2023-12-15 04:05 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg | ✅       |

%%DATAVIEW_PUBLISHER: end %%

## Space Systems

### QPS-SAR

QPS-SAR of the Institute for Q-shu Pioneers of Space, Inc. (iQPS) is a Japanese commercial [[📦 Payload Types#Synthetic Aperture Radar (SAR)|Synthetic Aperture Radar (SAR)]] satellite constellation that will provide high resolution and near real-time SAR imagery. The company began launching satellites into the constellation in December 2019 with QPS-SAR No.1 of 36, ‘Izanagi’.

[Official Product Info for QPS-SAR](https://i-qps.net/en/product/)
[EO Portal Page on QPS-SAR](https://www.eoportal.org/satellite-missions/qps-sar)

| Specs            | Value                                  |
| ---------------- | -------------------------------------- |
| Mass             | ~100 kg                                |
| Antenna Size     | 3.6 m<sup>2</sup>                      |
| Propulsion       | Available                              |
| Mission Life     | ?                                      |
| Center Frequency | 9.6 GHz (X-Band)                       |
| Look Direction   | Left or Right in Direction of Movement |
| Chirp Bandwidth  | ~600MHz                                |
| RF Peak Power    | 2kW                                    |
| Polarization     | HH or VV                               |
| Off-Nadir Angel  | 15-50 degrees                          |


![[Pasted image 20250206205443.png]]

## Spacecraft

| Spacecraft                          | Launch Date (UTC)        | Launch Vehicle                             | Spaceport                                                                | Orbit                                                        |
| ----------------------------------- | ------------------------ | ------------------------------------------ | ------------------------------------------------------------------------ | ------------------------------------------------------------ |
| QPS-SAR 12                          | August 5, 2025, 04:10    | [[Electron]]                               | [[Launch Complex 1]]                                                     | 575 km \| 42°                                                |
| QPS-SAR 11 (Yamatsumi 1)            | June 11, 2025, 15:31     | [[Electron]]                               | [[Launch Complex 1]]                                                     | 585 km \| 42º                                                |
| QPS-SAR 10 (Wadatsumi 1)            | May 17, 2025, 08:17      | [[Electron]]                               | [[Launch Complex 1]]                                                     | 580 km \| 42º                                                |
| QPS-SAR 9 (Susanoo 1)               | March 15, 2025, 00:00    | [[Electron]]                               | [[Launch Complex 1]]                                                     | 575 km \| 42º                                                |
| QPS-SAR No.8 (Amateru 4)            | August 16, 2024, 18:56   | Falcon 9, Transporter-11 Rideshare mission | Space Launch Complex 4E (SLC-4E), Vandenberg Space Force Base (VSFB)     | Sun-synchronous orbit, 510–600 km, inclination 97.45º–97.75º |
| QPS-SAR No.7 (Tsukuyomi 2)          | April 7, 2024, 23:16     | Falcon 9, Bandwagon-1 Rideshare mission    | Space Launch Complex 40 (SLC-40), Cape Canaveral Space Force Station, FL | Altitude ~590 km, inclination 45.6º                          |
| QPS-SAR No.5 (Tsukuyomi 1)          | December 15, 2023, 04:05 | [[Electron]]                               | [[Launch Complex 1]]                                                     | 575 km \| 42º                                                |
| QPS-SAR No.6 (Amateru 3)            | June 12, 2023, 21:35     | Falcon 9, Transporter-8 Rideshare mission  | Space Launch Complex 4E (SLC-4E), Vandenberg Space Force Base (VSFB)     | Altitude 433–540 km, inclination 97.5º                       |
| QPS-SAR No.3 & No.4 (Amateru 1 & 2) | October 12, 2022, 00:50  | Epsilon Rocket 6                           | Uchinoura Space Centre, Japan                                            | —                                                            |
| QPS-SAR No.2 (Izanami)              | January 25, 2021, 15:00  | Falcon 9, Transporter-1 Rideshare mission  | Space Launch Complex 40 (SLC-40), Cape Canaveral Space Force Station, FL | Altitude ~525 km                                             |
| QPS-SAR No.1 (Izanagi)              | December 11, 2019, 09:55 | PSLV (Polar Satellite Launch Vehicle)      | Satish Dhawan Space Center, India                                        | Altitude ~393 km, inclination 36.9º                          |

## News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[iQPS]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                             | Published         |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/Rocket Lab Successfully Deploys Sixth Earth-Imaging Satellite for iQPS.md\|Rocket Lab Successfully Deploys Sixth Earth-Imaging Satellite for iQPS]]                                                                                                       | November 05, 2025 |
| [[News/Rocket Lab Schedules Next Electron Launch, Sixth Mission for Constellation Operator iQPS.md\|Rocket Lab Schedules Next Electron Launch, Sixth Mission for Constellation Operator iQPS]]                                                                   | October 20, 2025  |
| [[News/Rocket Lab Secures Latest Multi-Launch Contract with iQPS for Three Dedicated Electron Missions.md\|Rocket Lab Secures Latest Multi-Launch Contract with iQPS for Three Dedicated Electron Missions]]                                                     | October 07, 2025  |
| [[News/Mission Success for Rocket Lab’s Latest Constellation Deployment Launch for iQPS.md\|Mission Success for Rocket Lab’s Latest Constellation Deployment Launch for iQPS]]                                                                                   | August 05, 2025   |
| [[News/Rocket Lab Schedules Fifth Electron Mission for Constellation Operator iQPS.md\|Rocket Lab Schedules Fifth Electron Mission for Constellation Operator iQPS]]                                                                                             | July 31, 2025     |
| [[News/Rocket Lab Successfully Launches Second Mission for iQPS in Rapid 25 Day Turnaround.md\|Rocket Lab Successfully Launches Second Mission for iQPS in Rapid 25 Day Turnaround]]                                                                             | June 11, 2025     |
| [[News/Rocket Lab Schedules Third Electron Launch In 24 Days To Deploy Next Mission For iQPS.md\|Rocket Lab Schedules Third Electron Launch In 24 Days To Deploy Next Mission For iQPS]]                                                                         | June 03, 2025     |
| [[News/Rocket Lab Successfully Launches Third Mission for iQPS in Multi-Launch Contract, Sets Schedule For the Next iQPS Mission.md\|Rocket Lab Successfully Launches Third Mission for iQPS in Multi-Launch Contract, Sets Schedule For the Next iQPS Mission]] | May 17, 2025      |
| [[News/Rocket Lab Schedules Next Mission for  Multi-Launch Customer iQPS.md\|Rocket Lab Schedules Next Mission for  Multi-Launch Customer iQPS]]                                                                                                                 | May 05, 2025      |
| [[News/Rocket Lab Successfully Launches 61st Electron Mission, Second Launch for iQPS.md\|Rocket Lab Successfully Launches 61st Electron Mission, Second Launch for iQPS]]                                                                                       | March 15, 2025    |
| [[News/Rocket Lab Schedules Two Launches Three Days Apart, Upcoming Mission to Deploy Final Satellites in Kinéis Constellation.md\|Rocket Lab Schedules Two Launches Three Days Apart, Upcoming Mission to Deploy Final Satellites in Kinéis Constellation]]     | March 10, 2025    |
| [[News/Rocket Lab Signs Second Multi-Launch Deal, Secures Eight Electron Missions with iQPS.md\|Rocket Lab Signs Second Multi-Launch Deal, Secures Eight Electron Missions with iQPS]]                                                                           | February 27, 2025 |
| [[News/Rocket Lab Signs Multi-Launch Contract with iQPS for Four Electron Missions.md\|Rocket Lab Signs Multi-Launch Contract with iQPS for Four Electron Missions]]                                                                                             | February 03, 2025 |
| [[News/Rocket Lab Reaches New Annual Launch Record with 10th Electron Mission This Year.md\|Rocket Lab Reaches New Annual Launch Record with 10th Electron Mission This Year]]                                                                                   | December 15, 2023 |
| [[News/Rocket Lab Prepares to Launch iQPS Mission.md\|Rocket Lab Prepares to Launch iQPS Mission]]                                                                                                                                                               | December 14, 2023 |
| [[News/Rocket Lab Sets Next Electron Launch Window, Provides Update on Anomaly Review.md\|Rocket Lab Sets Next Electron Launch Window, Provides Update on Anomaly Review]]                                                                                       | November 08, 2023 |
| [[News/Rocket Lab Inks Dedicated Launch Deal with Japanese Earth Imaging Company iQPS.md\|Rocket Lab Inks Dedicated Launch Deal with Japanese Earth Imaging Company iQPS]]                                                                                       | August 17, 2023   |

%%DATAVIEW_PUBLISHER: end %%