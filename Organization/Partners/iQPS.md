---

name: iQPS (Institute for Q-shu Pioneers of Space, Inc.)
website: https://i-qps.net/en/
---

**Name:** iQPS (Institute for Q-shu Pioneers of Space, Inc.)
**Website:** https://i-qps.net/en/

>[!summary]
iQPS (Institute for Q-shu Pioneers of Space) is a Japanese company focused on developing and deploying [[📦 Payload Types#Synthetic Aperture Radar (SAR)|Synthetic Aperture Radar (SAR)]] satellites.
They are working toward establishing a constellation of 36 small SAR satellites, aiming to provide near-real-time imaging with high-frequency revisits. Their compact satellites deliver sub-meter resolution data, enabling industries such as disaster management, infrastructure monitoring, agriculture, and defense to benefit from precise and timely Earth observation insights.
iQPS has launched several satellites to demonstrate its SAR capabilities and is actively scaling its constellation to offer comprehensive global coverage.

## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[iQPS]])
sort launch_date desc
```
%%

| File                                                                                  | Date                | Location                                              | Vehicle                          | Orbit & Mass            | Outcome   |
| ------------------------------------------------------------------------------------- | ------------------- | ----------------------------------------------------- | -------------------------------- | ----------------------- | --------- |
| [[Launch/Launches/064 'The Sea God Sees'.md\|064 'The Sea God Sees']]                 | 2025-05-17 00:00:00 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 575km \| 42° \| 100 kg  | ⌛ Pending |
| [[Launch/Launches/061 'The Lightning God Reigns'.md\|061 'The Lightning God Reigns']] | 2025-03-15 00:00    | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 575km \| 42° \| 100 kg  | ✅ Success |
| [[Launch/Launches/042 'The Moon God Awakens'.md\|042 'The Moon God Awakens']]         | 2023-12-15 04:05    | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg | ✅ Success |

%%DATAVIEW_PUBLISHER: end %%

## 🛰️ Space Systems

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


## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[iQPS]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                         | Published         |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------- |
| [[News/Rocket Lab Schedules Next Mission for  Multi-Launch Customer iQPS.md\|Rocket Lab Schedules Next Mission for  Multi-Launch Customer iQPS]]                                                                                                             | May 05, 2025      |
| [[News/Rocket Lab Successfully Launches 61st Electron Mission, Second Launch for iQPS.md\|Rocket Lab Successfully Launches 61st Electron Mission, Second Launch for iQPS]]                                                                                   | March 15, 2025    |
| [[News/Rocket Lab Schedules Two Launches Three Days Apart, Upcoming Mission to Deploy Final Satellites in Kinéis Constellation.md\|Rocket Lab Schedules Two Launches Three Days Apart, Upcoming Mission to Deploy Final Satellites in Kinéis Constellation]] | March 10, 2025    |
| [[News/Rocket Lab Signs Second Multi-Launch Deal, Secures Eight Electron Missions with iQPS.md\|Rocket Lab Signs Second Multi-Launch Deal, Secures Eight Electron Missions with iQPS]]                                                                       | February 27, 2025 |
| [[News/Rocket Lab Signs Multi-Launch Contract with iQPS for Four Electron Missions.md\|Rocket Lab Signs Multi-Launch Contract with iQPS for Four Electron Missions]]                                                                                         | February 03, 2025 |
| [[News/Rocket Lab Reaches New Annual Launch Record with 10th Electron Mission This Year.md\|Rocket Lab Reaches New Annual Launch Record with 10th Electron Mission This Year]]                                                                               | December 15, 2023 |
| [[News/Rocket Lab Prepares to Launch iQPS Mission.md\|Rocket Lab Prepares to Launch iQPS Mission]]                                                                                                                                                           | December 14, 2023 |
| [[News/Rocket Lab Sets Next Electron Launch Window, Provides Update on Anomaly Review.md\|Rocket Lab Sets Next Electron Launch Window, Provides Update on Anomaly Review]]                                                                                   | November 08, 2023 |
| [[News/Rocket Lab Inks Dedicated Launch Deal with Japanese Earth Imaging Company iQPS.md\|Rocket Lab Inks Dedicated Launch Deal with Japanese Earth Imaging Company iQPS]]                                                                                   | August 17, 2023   |

%%DATAVIEW_PUBLISHER: end %%