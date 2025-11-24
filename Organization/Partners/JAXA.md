---
name: Japan Aerospace Exporation Agency (JAXA)
website: https://global.jaxa.jp/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> JAXA
## Partner Details

**Website**: https://global.jaxa.jp/

JAXA is the Japan Aerospace Exploration Agency, Japan's national space agency responsible for research in space exploration and aviation. It conducts activities ranging from launching satellites and rockets to exploring planets and conducting scientific experiments on the International Space Station (ISS). JAXA was formed in 2003 through the merger of three previous organizations: the Institute of Space and Astronautical Science (ISAS), the National Space Development Agency of Japan (NASDA), and the National Aerospace Laboratory of Japan (NAL). 

## Launches

JAXA Launches w/ Rocket Lab

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[]])
sort launch_date desc
```
%%

| File                                                                | Date             | Location                                              | Vehicle                          | Orbit & Mass               | Outcome |
| ------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | -------------------------- | ------- |
| [[Launch/Launches/077 - Raise and Shine.md\|077 - Raise and Shine]] | 2025-12-05 03:00 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 540 km \| 97.5° \| Unknown | ⌛       |

%%DATAVIEW_PUBLISHER: end %%

## Space Systems

### RAISE-4

#### Summary
RAISE-4 (RApid Innovative payload demonstration SatellitE-4) is a dedicated technology demonstration satellite developed by the Japan Aerospace Exploration Agency (JAXA). It is the primary payload for the Rocket Lab Electron mission, [[077 - Raise and Shine]], scheduled to launch from [[Launch Complex 1]] in Mahia, New Zealand.

This mission is a critical part of JAXA's [Innovative Satellite Technology Demonstration Program](https://www.kenkai.jaxa.jp/eng/research/innovative/innovative.html), which provides on-orbit demonstration opportunities for private companies, universities, and research institutions to test new space components and subsystems. RAISE-4 carries eight distinct technology themes, six of which are re-flights of payloads originally onboard [RAISE-3](https://space.skyrocket.de/doc_sdat/raise-3.htm) (which was lost in an Epsilon launch failure in 2022). The mission marks the first of two dedicated [[Electron]] launches contracted directly by JAXA, with the second scheduled for Q1 2026.

#### Specifications

| Specification          | Value                                 |
| ---------------------- | ------------------------------------- |
| Mass                   | ~110 kg                               |
| Dimensions             | 0.75m x 1.0m x 0.8m                   |
| Power Generation (BOL) | 215 Watts (Body mounted Solar panels) |
| Battery                | Lithium Ion                           |
| Stabiliation           | 3-Axis Stabilized                     |
| Bus Manufacturer       | Mitsubishi Heavy Industries           |
| Design Life            | 13 Months                             |
>[!info] Some specs derived from RAISE-3 Press Release

![[Pasted image 20251124181149.png]]
#### Payloads

##### 1. [AIRIS (Artificial Intelligence Retraining In Space)](https://www.mhi.com/news/240306.html) - Mitsubishi Heavy Industries 
![[240306-1.jpg 1.webp|300]]
##### 2.[ D-SAIL (Deployable Deorbit Mechanism)](https://www.axelspace.com/news/dsail_raise4/) - Axelspace Corporation / Sakase Adtech
![[Pasted image 20251124181215.png|300]]
##### 3. [PBI-40 (Water-Based Propulsion)](https://pale-blue.co.jp/product/) - Pale Blue Inc.
![[Pasted image 20251124181413.png|300]]
##### 4. [HELIOS (High-Speed LEO-to-Ground Comms)](https://digitalcommons.usu.edu/cgi/viewcontent.cgi?article=5863&context=smallsat) - JAXA / Research Institutes
![[Pasted image 20251124181635.png|300]]

##### 5. [MEMS FOG (Fiber Optic Gyroscope)](https://mems.tamagawa-seiki.com/en/product/multisensor.html) - Tamagawa Seiki Co., Ltd. / JAXA
![[Pasted image 20251124181759.png|300]]
##### 6. 3D-Printed Waveguide Antenna - Fukui University of Technology

##### 7. HGV & PSDB (Hot Gas Valve & Power Distribution) - Meisei Electric

##### 8. [On-Orbit Thermal Control Demonstration](https://www.kenkai.jaxa.jp/library/pamphlets/pdf/kakushin_presskit_3_e.pdf) - JAXA / Academic Partners


## News

%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[]])
sort published desc
```
%%

| File                                                                                                                                                                                             | Published         |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------- |
| [[News/Rocket Lab Schedules First Dedicated Launch for Japan Aerospace Exploration Agency (JAXA).md\|Rocket Lab Schedules First Dedicated Launch for Japan Aerospace Exploration Agency (JAXA)]] | November 24, 2025 |
| [[News/Rocket Lab Secures Multiple Launches with Japan Aerospace Exploration Agency (JAXA).md\|Rocket Lab Secures Multiple Launches with Japan Aerospace Exploration Agency (JAXA)]]             | October 10, 2025  |

%%DATAVIEW_PUBLISHER: end %%