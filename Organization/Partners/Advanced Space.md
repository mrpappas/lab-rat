---

name: Advanced Space
website: https://advancedspace.com/
---

**Name:** Advanced Space
**Website:** https://advancedspace.com/

>[!summary]
Advanced Space is a Colorado-based company specializing in mission design, navigation, and operations for space exploration, with a focus on cislunar and deep space missions. Known for their expertise in orbital dynamics and spacecraft navigation, Advanced Space supports commercial and government clients, including NASA. They are notably the operator of the CAPSTONE mission (Cislunar Autonomous Positioning System Technology Operations and Navigation Experiment), a pathfinding CubeSat mission to the Moon that demonstrates navigation technology for the Gateway program in NASA's Artemis initiative. The company aims to advance the use of innovative technologies for sustainable space exploration.

## 🛰️ Space Systems

### CAPSTONE

CAPSTONE will be the first satellite to operate in a Near Rectilinear Halo Orbit around the Moon. CAPSTONE aims to reduce risk and validate operational concepts for future missions using the same lunar orbit.

In this orbit, CAPSTONE will orbit together with the Moon as it orbits Earth and will pass as close as 1600km and as far as 70000km from the lunar surface. About the size of a microwave oven, this 25kg satellite has an onboard communications system capable of determining how far CAPSTONE is from NASA’s Lunar Reconnaissance Orbiter and how fast the distance between the two spacecraft is changing. This inter-spacecraft information will be used to demonstrate the software for autonomous navigation, CAPS, that, when fully demonstrated, will enable future missions to determine their location without having to rely exclusively on tracking from Earth.

![[capstone_05-19jan22_0_0.webp]]

## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[Advanced Space]])
sort launch_date desc
```
%%

| File                                                  | Date             | Location                                              | Vehicle                          | Orbit & Mass                                       | Outcome   |
| ----------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | -------------------------------------------------- | --------- |
| [[Launch/Launches/027 - CAPSTONE.md\|027 - CAPSTONE]] | 2022-06-28 09:55 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | Translunar Injection (TLI) \| 320kg LEO / 80kg TLI | ✅ Success |

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