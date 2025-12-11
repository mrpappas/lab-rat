---

name: UTIAS Space Flight Laboratory
website: https://www.utias-sfl.net/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> UTIAS Space Flight Laboratory
## Partner Details

**Website:** https://www.utias-sfl.net/

UTIAS Flight Lab, part of the University of Toronto Institute for Aerospace Studies, is a leading developer of small satellite missions and advanced space systems. Specializing in microsatellites, nanosatellites, and CubeSats, SFL provides end-to-end mission solutions, including satellite design, manufacturing, integration, and operations. Known for its innovation in low-cost, high-performance satellites, SFL supports a wide range of applications, such as Earth observation, remote sensing, communications, and scientific research. With a proven track record of launching successful missions globally, SFL is a key player in enabling access to space for commercial, academic, and government clients.

![[Space-Flight-Laboratory.webp|300]]
## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[]])
sort launch_date desc
```
%%

| File                                                              | Date             | Location                                              | Vehicle                          | Orbit & Mass               | Outcome |
| ----------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | -------------------------- | ------- |
| [[Launch/Launches/039 - Baby Come Back.md\|039 - Baby Come Back]] | 2023-07-18 01:27 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 1000 km \| 99.45° \| 86 kg | ✅       |

%%DATAVIEW_PUBLISHER: end %%


## Space Systems

 UTIAS-SFL offers a flexible, flight-proven progression of bus platforms—from low-mass CubeSats (THUNDER, SPARTAN, JAEGER) to mid-range nanosats/microsats (NEMO, DEFIANT, NAUTILUS) up to powerful smallsat busses (DAUNTLESS) capable of supporting hundreds of kilograms of payloads. All are supported by standardized deployers (XPOD) and full mission services—ideal for science, communications, tech demos, & constellation builds.
 
 🔗 https://www.utias-sfl.net/satellite-platforms/overview/

### THUNDER 3U
Standardized 3U CubeSat platform.

![[Pasted image 20250626015608.png]]

| Specification    | Value                                                                                                                                                                     |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Mass             | 3-6 kg                                                                                                                                                                    |
| Volume           | 10x10x34 cm                                                                                                                                                               |
| Payload Mass     | Up to 3 kg                                                                                                                                                                |
| Payload Volume   | Up to 2 dm3<br>2U                                                                                                                                                         |
| Payload Power    | Up to 31 Wh/orbit(5)<br>62 W peak                                                                                                                                         |
| ACS Stability    | 2° 10 arcsec                                                                                                                                                              |
| ACS Modes        | 3-axis inertial, nadir, target tracking                                                                                                                                   |
| Downlink         | Up to 2 Mbps                                                                                                                                                              |
| Propulsion       | Optional                                                                                                                                                                  |
| Navigation       | GPS, 5-10m                                                                                                                                                                |
| Launch Interface | COTS Deployers                                                                                                                                                            |
| Quality Approach | Newspace or Microspace                                                                                                                                                    |
| Mission Heritage | [CanX-2](https://space.skyrocket.de/doc_sdat/canx-2.htm), [NTS](https://space.skyrocket.de/doc_sdat/canx-6.htm), [CanX-7](https://space.skyrocket.de/doc_sdat/canx-7.htm) |

### SPARTAN 6U

Standardized 6U CubeSat platform.

![[Pasted image 20250626020109.png]]

| Specification    | Value                                                                                                                                                                                                                                                                                                                                                                |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Mass             | 6-12 kg                                                                                                                                                                                                                                                                                                                                                              |
| Volume           | 10x20x36 cm                                                                                                                                                                                                                                                                                                                                                          |
| Payload Mass     | Up to 6 kg                                                                                                                                                                                                                                                                                                                                                           |
| Payload Volume   | Up to 4 dm3<br>4U                                                                                                                                                                                                                                                                                                                                                    |
| Payload Power    | Up to 46 Wh/orbit<br>160 W peak                                                                                                                                                                                                                                                                                                                                      |
| ACS Stability    | 2° 10 arcsec                                                                                                                                                                                                                                                                                                                                                         |
| ACS Modes        | 3-axis inertial, nadir, target tracking                                                                                                                                                                                                                                                                                                                              |
| Downlink         | Up to 50 Mbps                                                                                                                                                                                                                                                                                                                                                        |
| Propulsion       | Optional                                                                                                                                                                                                                                                                                                                                                             |
| Navigation       | GPS, 5-10m                                                                                                                                                                                                                                                                                                                                                           |
| Launch Interface | COTS Deployers                                                                                                                                                                                                                                                                                                                                                       |
| Quality Approach | Newspace or Microspace                                                                                                                                                                                                                                                                                                                                               |
| Mission Heritage | [Kepler](https://space.skyrocket.de/doc_sdat/kepler-4.htm), [AISSat Constellation](https://www.utias-sfl.net/aissat-1-2-and-3/), [BRITE Constellation](https://www.utias-sfl.net/canx-3-brite-constellation/), [EV9](https://www.utias-sfl.net/ev9/), [CanX-4](https://www.utias-sfl.net/canx-4-and-canx-5/), [CanX-5](https://www.utias-sfl.net/canx-4-and-canx-5/) |

### JAEGER 12U/6U

### NEMO

### DEFIANT

### NAUTILUS

### DAUNTLESS

## News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                       | Published     |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| [[News/Rocket Lab Deploys Satellites for NASA and Commercial Constellation Operators,  Successfully Recovers Booster.md\|Rocket Lab Deploys Satellites for NASA and Commercial Constellation Operators,  Successfully Recovers Booster]]                   | July 17, 2023 |
| [[News/Rocket Lab Prepares to Launch Mix of NASA and Commercial Satellites, and Takes Next Step in Rocket Reusability Program.md\|Rocket Lab Prepares to Launch Mix of NASA and Commercial Satellites, and Takes Next Step in Rocket Reusability Program]] | July 17, 2023 |
| [[News/Rocket Lab to Launch Multiple Satellites as Part of Upcoming Recovery Mission.md\|Rocket Lab to Launch Multiple Satellites as Part of Upcoming Recovery Mission]]                                                                                   | June 22, 2023 |
| [[News/Space Flight Laboratory Selects Rocket Lab to Launch Telesat Broadband Satellite.md\|Space Flight Laboratory Selects Rocket Lab to Launch Telesat Broadband Satellite]]                                                                             | May 31, 2023  |

%%DATAVIEW_PUBLISHER: end %%