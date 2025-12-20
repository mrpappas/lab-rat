---
name: The Aerospace Corporation
website: https://aerospace.org/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> The Aerospace Corporation

**Website**: https://aerospace.org/

The Aerospace Corporation is an American nonprofit organization that operates as a Federally Funded Research and Development Center (FFRDC). Founded in 1960 and headquartered in Chantilly, Virginia, the company serves as the trusted technical advisor to national security, civil, and commercial space programs

Aerospace's core purpose is to deliver objective technical analysis, systems engineering, and program management support across all phases of space system development—from early concept through operations. As the FFRDC for national-security space, it works closely with agencies such as the U.S. Space Force and National Reconnaissance Office (NRO)

![[Pasted image 20251211015539.png|300]]

## Missions

- [[STP-S30]]

## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[]])
sort launch_date desc
```
%%

| File                                                                              | Date             | Location                                               | Vehicle                          | Orbit & Mass             | Outcome |
| --------------------------------------------------------------------------------- | ---------------- | ------------------------------------------------------ | -------------------------------- | ------------------------ | ------- |
| [[Launch/Launches/078 - Don't Be Such A Square.md\|078 - Don't Be Such A Square]] | 2025-12-18 05:00 | [[Locations/Launch Complex 2.md#Launch Pad 0C\|LC2-0]] | [[Launch/Electron.md\|Electron]] | 550 km \| 45° \| Unknown | ✅       |

%%DATAVIEW_PUBLISHER: end %%

## Space Systems
### DiskSat

#### Summary

 **DiskSat** is The Aerospace Corporation’s **disk-shaped small satellite bus / form factor** designed as an alternative to CubeSat “containerization,” keeping standardized interfaces and rideshare compatibility while **breaking the volume constraints** of a box. Its **2D planar geometry** (about **1 m diameter** and **~2.5 cm thick**) provides unusually large **surface area for solar collection** and **large apertures** (antennas/sensors), enabling **high available power (up to ~200 W class)** without large deployables and simplifying access for integration and test. 
 
 For launch, multiple DiskSats can be **stacked “pancake-style” inside a dedicated dispenser** and **deployed sequentially** to reduce recontact risk, supporting fast constellation deployment from a compact packaged volume. 
 
 DiskSat is also aimed at **high-maneuverability missions**, including **very low Earth orbit (vLEO)** operations where atmospheric drag is high; optional **electric propulsion** and the low-drag geometry support orbit changes / drag compensation use cases. A **NASA-supported demonstration mission** is planned to fly **four DiskSats** to validate the platform (including dispenser operations plus power/thermal/propulsion performance). 


![[disksat-deploying-101-3585x2016-1.webp]]

#### Specifications

| Specification           | Value / Notes                                                                |
| ----------------------- | ---------------------------------------------------------------------------- |
| **Form Factor**         | ~1 m diameter × ~2.5 cm thick (flat, disk-shaped design)                     |
| **Equivalent Volume**   | ~20 L (~ 20 U CubeSat)                                                       |
| **Structural Mass**     | <2.5 kg                                                                      |
| **Peak Power**          | >200 W available without deployables                                         |
| **Electric Propulsion** | Supports ~5000 Ns ΔV for high-maneuverability missions                       |
| **Low-Drag Altitude**   | Operable to ~200 km with drag compensation                                   |
| **Launch Config.**      | Stackable dispenser; multiple units deployed sequentially in orbit           |
| **Demo Mission**        | NASA-backed demo of four DiskSats (planned NET 2025/26) to validate platform |
[🔗 Fact Sheet](https://aerospace.org/sites/default/files/2025-04/FY25_13981_CC_Space-Symposium_2025_DiskSat_Fact-Sheet_RD3.pdf)

Resources: 
🔗 https://aerospace.org/disksat
🔗 https://www.nasa.gov/mission/disksat/
🔗 https://spacenews.com/disksat-demo-mission/
🔗 [DiskSat is ready to launch and show off the future of flat satellites](https://aerospace.org/kickstage/disksat-ready-launch-and-show-future-flat-satellites) (Dec 09, 2025 - aerospace.org)
🔗 [Stacked Like Pancakes: The Aerospace Corporation’s DiskSats Ready for Launch](https://aerospace.org/press-release/stacked-pancakes-aerospace-corporations-disksats-ready-launch) (Dec 16, 2025 - aerospace.org)

White Papers: 
- https://digitalcommons.usu.edu/smallsat/2021/all2021/227/
- https://digitalcommons.usu.edu/smallsat/2022/all2022/102/
- https://ieeexplore.ieee.org/document/11068691

![](https://www.youtube.com/watch?v=wz4urbxb8fQ)
🔗 Backup Link: https://www.youtube.com/watch?v=wz4urbxb8fQ

## News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                 | Published         |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------- |
| [[News/Rocket Lab Executes Successful Launch of STP-S30 Mission for the Department of War.md\|Rocket Lab Executes Successful Launch of STP-S30 Mission for the Department of War]]                                                   | December 18, 2025 |
| [[News/Rocket Lab Schedules Launch for U.S. Space Force’s STP-S30 Mission, Brings Launch Forward By Several Months.md\|Rocket Lab Schedules Launch for U.S. Space Force’s STP-S30 Mission, Brings Launch Forward By Several Months]] | December 16, 2025 |
| [[News/U.S. Space Force Awards Rocket Lab Launch Contract for Space Test Program (STP)-S30.md\|U.S. Space Force Awards Rocket Lab Launch Contract for Space Test Program (STP)-S30]]                                                 | April 08, 2024    |

%%DATAVIEW_PUBLISHER: end %%
