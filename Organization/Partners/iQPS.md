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
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[iQPS]])
sort launch_date desc
```
%%

| File                                                                                                | launch_date      | outcome |
| --------------------------------------------------------------------------------------------------- | ---------------- | ------- |
| [[Launch/Launches/042 'The Moon God Awakens' - Electron.md\|042 'The Moon God Awakens' - Electron]] | 2023-12-15 04:05 | Success |

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
table title as "Title", published as "Published"
from "News"
where contains(customer, [[iQPS]])
sort published desc
```
%%

| File                                                                                                                                                                           | Title                                                                             | Published         |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------- | ----------------- |
| [[News/Rocket Lab Signs Multi-Launch Contract with iQPS for Four Electron Missions.md\|Rocket Lab Signs Multi-Launch Contract with iQPS for Four Electron Missions]]           | Rocket Lab Signs Multi-Launch Contract with iQPS for Four Electron Missions       | February 03, 2025 |
| [[News/Rocket Lab Reaches New Annual Launch Record with 10th Electron Mission This Year.md\|Rocket Lab Reaches New Annual Launch Record with 10th Electron Mission This Year]] | Rocket Lab Reaches New Annual Launch Record with 10th Electron Mission This Year  | December 15, 2023 |
| [[News/Rocket Lab Prepares to Launch iQPS Mission.md\|Rocket Lab Prepares to Launch iQPS Mission]]                                                                             | Rocket Lab Prepares to Launch iQPS Mission                                        | December 14, 2023 |
| [[News/Rocket Lab Sets Next Electron Launch Window, Provides Update on Anomaly Review.md\|Rocket Lab Sets Next Electron Launch Window, Provides Update on Anomaly Review]]     | Rocket Lab Sets Next Electron Launch Window, Provides Update on Anomaly Review    | November 08, 2023 |
| [[News/Rocket Lab Inks Dedicated Launch Deal with Japanese Earth Imaging Company iQPS.md\|Rocket Lab Inks Dedicated Launch Deal with Japanese Earth Imaging Company iQPS]]     | Rocket Lab Inks Dedicated Launch Deal with Japanese Earth Imaging Company iQPS    | August 17, 2023   |

%%DATAVIEW_PUBLISHER: end %%