---
name: KAIST (Korea Advanced Institute of Science and Technology)
website: https://www.kaist.ac.kr/en/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> KAIST

**Website:** https://www.kaist.ac.kr/en/

The **Korea Advanced Institute of Science and Technology (KAIST)** is South Korea's leading research-oriented university, recognized for its advancements in science, engineering, and technology. In the space sector, KAIST is notable for its contributions to satellite development and space technology research. The university's **[Satellite Technology Research Center (SaTReC)](https://satrec.kaist.ac.kr/e_01_01.php)** has developed and launched several small satellites, including the **[KITSAT](https://en.wikipedia.org/wiki/KITSAT-1) series** and more advanced Earth observation satellites. These satellites support scientific research, technology demonstration, and space education.

KAIST collaborates with international partners and government agencies, playing a significant role in South Korea's space program by fostering innovation, talent development, and the deployment of cutting-edge space technologies.

![[Pasted image 20251210234548.png]]

## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[]])
sort launch_date desc
```
%%

| File                                                                              | Date                | Location                                              | Vehicle                                            | Orbit & Mass                                       | Outcome   |
| --------------------------------------------------------------------------------- | ------------------- | ----------------------------------------------------- | -------------------------------------------------- | -------------------------------------------------- | --------- |
| [[Launch/Launches/047 - Beginning Of The Swarm.md\|047 - Beginning Of The Swarm]] | 2024-04-23 22:00    | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Hardware/Launch Vehicles/Electron.md\|Electron]] | 520 km (Neonsat-1), 1,000 km (ACS3), 97° \| 115 kg | ✅         |
| [[Launch/Launches/080 - Bridging The Swarm.md\|080 - Bridging The Swarm]]         | 0000-00-00 00:00:00 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Hardware/Launch Vehicles/Electron.md\|Electron]] | 540 km \| 97.4° \| < 100 kg                        | ⌛ (scrub) |

%%DATAVIEW_PUBLISHER: end %%

## Space Systems

### NEONSAT

NEONSAT (New-space Earth Observation Satellite) is KAIST’s small, high-resolution Earth observation constellation designed to monitor the Korean Peninsula and surrounding regions. Each ~100 kg-class microsatellite operates in Sun-synchronous low Earth orbit and carries a high-resolution optical camera capable of ~1 m panchromatic and ~4 m multispectral imaging, supporting missions like disaster monitoring, environmental change tracking, and urban planning. 

The NEONSAT constellation is the first satellite system developed by the government using a mass-production approach for precise monitoring of the Korean Peninsula, lead by the [Satellite Technology Research Center (SaTReC)](https://satrec.kaist.ac.kr/e_01_01.php) at the Korea Advanced Institute of Science and Technology (KAIST), Korea’s leading university dedicated to science and technology. Designed to capture near-real time natural disaster monitoring for the Korean peninsula, KAIST’s NEONSAT constellation is a collaboration across multiple Korean academic, industry, and research institutions, including SaTReC, which is leading the program’s system design and engineering.

The NEONSAT program is funded by the [Korean government’s Ministry of Science and ICT (MSIT)](https://www.msit.go.kr/eng/index.do).

🔗 Gunter's: https://space.skyrocket.de/doc_sdat/neonsat-1.htm

| Specification               | Value (approx.)                                                                     |
| --------------------------- | ----------------------------------------------------------------------------------- |
| **Mass**                    | “About 100 kg” / “less than 100 kg” (microsatellite / nanosatellite class) [1]      |
| **Orbit**                   | ~520 km circular Sun-synchronous orbit, ~97° inclination                            |
| **Ground resolution**       | **1 m** panchromatic (black-and-white) and **4 m** multispectral (color)            |
| **Imaging type**            | High-resolution optical camera                                                      |
| **Constellation plan**      | 12 satellites total: NEONSAT-1, NEONSAT-1A + 10 follow-ons (launches through ~2027) |
| **Power system**            | Deployable solar arrays + batteries                                                 |
| **Downlink freq (example)** | ~2242.75 MHz (one listed downlink)                                                  |
| **Mission role**            | Earth Observation                                                                   |

![[Pasted image 20251210002840.jpg]]

## News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[]])
sort published desc
```
%%

| File                                                                                                                                                                                                                               | Published         |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/Rocket Lab Brings Forward Earth Observation Launch for KAIST, Liftoff Scheduled for Tomorrow.md\|Rocket Lab Brings Forward Earth Observation Launch for KAIST, Liftoff Scheduled for Tomorrow]]                             | December 09, 2025 |
| [[News/Rocket Lab Brings Forward Earth Observation Launch for KAIST, Liftoff Scheduled for Tomorrow 1.md\|Rocket Lab Brings Forward Earth Observation Launch for KAIST, Liftoff Scheduled for Tomorrow 1]]                         | December 09, 2025 |
| [[News/Rocket Lab Successfully Deploys Satellites ~500km Apart to Separate Orbits  For KAIST and NASA  Rocket Lab.md\|Rocket Lab Successfully Deploys Satellites ~500km Apart to Separate Orbits  For KAIST and NASA  Rocket Lab]] | April 24, 2024    |
| [[News/Rocket Lab Prepares to Launch Mission for KAIST and NASA to Deploy Satellites to Two Separate Orbits.md\|Rocket Lab Prepares to Launch Mission for KAIST and NASA to Deploy Satellites to Two Separate Orbits]]             | April 01, 2024    |
| [[News/Rocket Lab Signs Deal to Launch South Korean Satellite.md\|Rocket Lab Signs Deal to Launch South Korean Satellite]]                                                                                                         | December 07, 2023 |

%%DATAVIEW_PUBLISHER: end %%

