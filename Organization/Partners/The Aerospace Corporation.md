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

| File                                                                        | Date             | Location                                               | Vehicle                          | Orbit & Mass       | Outcome |
| --------------------------------------------------------------------------- | ---------------- | ------------------------------------------------------ | -------------------------------- | ------------------ | ------- |
| [[Launch/Launches/079 - AVALANCHE (STP-S30).md\|079 - AVALANCHE (STP-S30)]] | 2025-12-18 10:00 | [[Locations/Launch Complex 2.md#Launch Pad 0C\|LC2-0]] | [[Launch/Electron.md\|Electron]] | Unknown \| Unknown | ⌛       |

%%DATAVIEW_PUBLISHER: end %%

## Space Systems
### DiskSat

#### Summary

**DiskSat** is The Aerospace Corporation’s flat, disk-shaped smallsat architecture, designed as a performance-focused evolution of the CubeSat model.

- **Adaptable Design**: Dimensions can be customized for different launch vehicles and payloads.  
- **Ease of Integration**: Flat form factor simplifies assembly, integration, and testing.  
- **Mission Applications**: High-power payloads (comms, SAR, PNT), vLEO Earth observation, and deep-space operations with high-ΔV capability.  

🔗 https://aerospace.org/disksat

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

## News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(partner, [[]])
sort published desc
```
%%

| File                                                                                                                                                                                 | Published      |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------- |
| [[News/U.S. Space Force Awards Rocket Lab Launch Contract for Space Test Program (STP)-S30.md\|U.S. Space Force Awards Rocket Lab Launch Contract for Space Test Program (STP)-S30]] | April 08, 2024 |

%%DATAVIEW_PUBLISHER: end %%
## Media

### DiskSats

![](https://www.youtube.com/watch?v=wz4urbxb8fQ)