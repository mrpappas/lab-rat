---

name: Advanced Space
website: https://advancedspace.com/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> Advanced Space

**Website:** https://advancedspace.com/

>[!summary]
Advanced Space is a Colorado-based company specializing in mission design, navigation, and operations for space exploration, with a focus on cislunar and deep space missions. Known for their expertise in orbital dynamics and spacecraft navigation, Advanced Space supports commercial and government clients, including NASA. They are notably the operator of the CAPSTONE mission (Cislunar Autonomous Positioning System Technology Operations and Navigation Experiment), a pathfinding CubeSat mission to the Moon that demonstrates navigation technology for the Gateway program in NASA's Artemis initiative. The company aims to advance the use of innovative technologies for sustainable space exploration.

## 🛰️ Space Systems

### CAPSTONE
#### Summary
CAPSTONE (Cislunar Autonomous Positioning System Technology Operations and Navigation Experiment) is a lunar orbiter that is testing and verifying the calculated orbital stability planned for the Lunar Gateway space station. The spacecraft is a 12-unit CubeSat that is also testing a navigation system that is measuring its position relative to [NASA's Lunar Reconnaissance Orbiter (LRO)](https://science.nasa.gov/mission/lro/) without relying on ground stations. It was [[027 - CAPSTONE|launched on 28 June 2022]], arrived in lunar orbit on 14 November 2022, and was scheduled to orbit for six months. On 18 May 2023, it completed its primary mission to orbit in the near-rectilinear halo orbit for six months, but will stay on this orbit, continuing to perform experiments during an enhanced mission phase.

[[CAPSTONE|🛰️ CAPSTONE Mission]]

![[capstone_05-19jan22_0_0.webp]]

#### Specifications

🔗 [CAPSTONE Mission Update to Interplanetary Small Satellite Conference](http://www.intersmallsatconference.com/past/2024/A.2%20-%20Gardner/Gardner%20CAPSTONE_ISSC%202024%2004_30_24.pdf)

| Specification             | Value                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Size**                  | 12U (34 x 34 x 61 cm)                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Mass**                  | 25 kg                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Propulsion**            | Monopropellant [Hydrazine](https://en.wikipedia.org/wiki/Hydrazine) propulsion system developed by [Stellar Exploration](https://www.stellar-exploration.com/) providing over 200 m/s of total ΔV with eight 0.25-Newton thrusters and 3.25 kg fuel.<br>🔗 [Data Sheet](https://static1.squarespace.com/static/5c54e307fd67934e24b27846/t/62e74d493ba1a46b5841fcb5/1659325786410/Datasheet+propulsion+2022+04+04.pdf) |
| **Manufacturer**          | [[Terran Orbital]]                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Battery Modules**       | QTY 3×, 182 W-hr storage                                                                                                                                                                                                                                                                                                                                                                                              |
| Solar Panels              | Deployable fixed-angle arrays, peak power 114 W (BOL), 120 XTJ Prime cells                                                                                                                                                                                                                                                                                                                                            |
| **Space/Ground Radio**    | Iris Radio, 3.8 W, 1-way CSAC-enabled firmware                                                                                                                                                                                                                                                                                                                                                                        |
| **Space/Ground Antennas** | X-band high gain & low gain patch antennas, on spacecraft Y– and Y+ faces                                                                                                                                                                                                                                                                                                                                             |
| **LRO Crosslink Radio**   | TUI SLX, 2 W                                                                                                                                                                                                                                                                                                                                                                                                          |
| **LRO Crosslink Antenna** | S-band patch antenna on Z+ face                                                                                                                                                                                                                                                                                                                                                                                       |
| **ADCS Control**          | Coarse sensor module, redundant star trackers, redundant IMUs, four pyramidal reaction wheels                                                                                                                                                                                                                                                                                                                         |
| **Thermal Control**       | Active battery heaters, 16 thermistor channels, 8 independent heaters, passive coatings and MLI                                                                                                                                                                                                                                                                                                                       |

#### CAPS (Cislunar Autonomous Positioning System)

📡 The **Cislunar Autonomous Positioning System (CAPS)** is a peer-to-peer navigation technology, incorporating relative tracking data between two or more vehicles. This improves existing navigation products, reduces the need for ground-based tracking expenses, and even permits autonomous, absolute navigation of all vehicles involved. 

💻 The CAPS navigation software is hosted on a separate flight computer from the spacecraft’s primary redundant flight computer boards and operate distinctly from one another. Being hosted on a separate board allows for the CAPS software to experience updates and modifications throughout the demonstration as observations are returned, without disrupting the operations of the primary flight computer(s).

 🛰️ CAPS is a unique innovation that operationalizes, and leverages investments made in algorithms, flight computers, and radios over the past decade. At its foundation, CAPS starts with the algorithms and logic of automated navigation layered on top of an innovative approach to absolute orbit determination that requires only relative radiometric ranging and Doppler measurements. In its most streamlined implementation, CAPS will be a software innovation that can be incorporated on any future spacecraft.

#### Partners

**[[NASA]]**
CAPSTONE’s development is supported by the Space Technology Mission Directorate via the Small Spacecraft Technology and Small Business Innovation Research programs at NASA’s Ames Research Center in California’s Silicon Valley. The Artemis Campaign Development Division within NASA’s Exploration Systems Development Mission Directorate supported the launch and mission operations. NASA’s Launch Services Program at Kennedy Space Center in Florida was responsible for launch management. NASA’s Jet Propulsion Laboratory supported the communication, tracking, and telemetry downlink via NASA’s Deep Space Network, Iris radio design, and groundbreaking 1-way navigation algorithms.

**[[Terran Orbital]]**
Spacecraft design, development and implementation, hardware manufacturing, assembly, testing, and mission operations support.

[**Stellar Exploration Corporation**](https://www.stellar-exploration.com/)
Propulsion subsystem provider.

**Rocket Lab**
Launch services provider.

[**Space Dynamics Lab (SDL)**](https://www.sdl.usu.edu/)
Iris radio and navigation firmware provider.

[**Orion Space Solutions**](https://orion.arcfield.com/)
Chip Scale Atomic Clock (CSAC) hardware provider necessary for the 1-way ranging experiment.

[**Tethers Unlimited, Inc.**](https://arka.org/)
Cross Link radio provider.

**Morehead State University (MSU)**
Operates the newest “affiliated node” on the NASA Deep Space Network (DSN). Provides telemetry, tracking, and control services for NASA and commercial space missions and engages university students in deep space mission operations.

## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[Advanced Space]])
sort launch_date desc
```
%%

| File                                                  | Date             | Location                                              | Vehicle                          | Orbit & Mass                                       | Outcome |
| ----------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | -------------------------------------------------- | ------- |
| [[Launch/Launches/027 - CAPSTONE.md\|027 - CAPSTONE]] | 2022-06-28 09:55 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | Translunar Injection (TLI) \| 320kg LEO / 80kg TLI | ✅       |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News

%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[Advanced Space]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                             | Published         |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/Rocket Lab-launched CAPSTONE Spacecraft Enters Lunar Orbit.md\|Rocket Lab-launched CAPSTONE Spacecraft Enters Lunar Orbit]]                                                                                                                               | November 15, 2022 |
| [[News/Rocket Lab Moon Mission for NASA a Success  Rocket Lab.md\|Rocket Lab Moon Mission for NASA a Success  Rocket Lab]]                                                                                                                                       | July 04, 2022     |
| [[News/Rocket Lab’s Lunar Photon Completes Sixth Orbit Raise for NASA’s CAPSTONE Mission to The Moon.md\|Rocket Lab’s Lunar Photon Completes Sixth Orbit Raise for NASA’s CAPSTONE Mission to The Moon]]                                                         | July 01, 2022     |
| [[News/Rocket Lab Completes Fifth Orbit Raise For NASA’s CAPSTONE Mission to The Moon.md\|Rocket Lab Completes Fifth Orbit Raise For NASA’s CAPSTONE Mission to The Moon]]                                                                                       | June 30, 2022     |
| [[News/Rocket Lab Successfully Raises Orbit a Fourth Time For NASA’s CAPSTONE Moon Mission.md\|Rocket Lab Successfully Raises Orbit a Fourth Time For NASA’s CAPSTONE Moon Mission]]                                                                             | June 30, 2022     |
| [[News/Rocket Lab’s Lunar Photon Spacecraft Successfully Completes Third Orbit Raising Maneuver for NASA’s CAPSTONE Moon Mission.md\|Rocket Lab’s Lunar Photon Spacecraft Successfully Completes Third Orbit Raising Maneuver for NASA’s CAPSTONE Moon Mission]] | June 29, 2022     |
| [[News/Rocket Lab Successfully Launches CAPSTONE Spacecraft, Completes First Leg of Moon Mission for NASA.md\|Rocket Lab Successfully Launches CAPSTONE Spacecraft, Completes First Leg of Moon Mission for NASA]]                                               | June 28, 2022     |
| [[News/Rocket Lab Prepares to Launch CAPSTONE Mission to the Moon for NASA.md\|Rocket Lab Prepares to Launch CAPSTONE Mission to the Moon for NASA]]                                                                                                             | June 23, 2022     |
| [[News/Rocket Lab Begins Payload Integration for CAPSTONE Mission to the Moon.md\|Rocket Lab Begins Payload Integration for CAPSTONE Mission to the Moon]]                                                                                                       | May 16, 2022      |
| [[News/Rocket Lab to Launch NASA Funded Commercial Moon Mission from New Zealand.md\|Rocket Lab to Launch NASA Funded Commercial Moon Mission from New Zealand]]                                                                                                 | August 06, 2021   |
| [[News/Rocket Lab Readies Photon Spacecraft for NASA Moon Mission.md\|Rocket Lab Readies Photon Spacecraft for NASA Moon Mission]]                                                                                                                               | December 11, 2020 |
| [[News/Rocket Lab Selected by NASA to Launch Pathfinder Mission to the Moon.md\|Rocket Lab Selected by NASA to Launch Pathfinder Mission to the Moon]]                                                                                                           | February 14, 2020 |

%%DATAVIEW_PUBLISHER: end %%