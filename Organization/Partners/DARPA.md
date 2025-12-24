---

name: DARPA (Defense Advanced Research Projects Agency)
website: https://www.darpa.mil/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> DARPA

**Website:** https://www.darpa.mil/

The Defense Advanced Research Projects Agency (DARPA) is a research and development agency of the United States Department of Defense that focuses on developing new technologies for the military. DARPA's mission is to make significant investments in breakthrough technologies that will transform national security.

![[Pasted image 20251211030058.jpg|300]]

## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[]])
sort launch_date desc
```
%%

| File                                                      | Date             | Location                                              | Vehicle                                                 | Orbit & Mass              | Outcome |
| --------------------------------------------------------- | ---------------- | ----------------------------------------------------- | ------------------------------------------------------- | ------------------------- | ------- |
| [[Launch/Launches/005 - DARPA R3D2.md\|005 - DARPA R3D2]] | 2019-03-28 23:27 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 425 km \| 39.5° \| 150 kg | ✅       |

%%DATAVIEW_PUBLISHER: end %%


## News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[]])
sort published desc
```
%%

| File                                                                                                                                                                                                                               | Published        |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- |
| [[News/Rocket Lab Supports Significant Milestone for DARPA and Space Development Agency on the Mandrake-2 Mission.md\|Rocket Lab Supports Significant Milestone for DARPA and Space Development Agency on the Mandrake-2 Mission]] | July 13, 2022    |
| [[News/Rocket Lab successfully launches R3D2 satellite for DARPA.md\|Rocket Lab successfully launches R3D2 satellite for DARPA]]                                                                                                   | March 28, 2019   |
| [[News/Rocket Lab to launch dedicated Electron mission for DARPA.md\|Rocket Lab to launch dedicated Electron mission for DARPA]]                                                                                                   | January 22, 2019 |

%%DATAVIEW_PUBLISHER: end %%
## Space Systems

### Mandrake-2

DARPA's Mandrake 2 is a technology demonstration program designed to test and validate advanced optical inter-satellite communication links. Part of DARPA’s [Blackjack program](https://www.darpa.mil/research/programs/blackjack), it aims to develop and deploy small satellite constellations with robust, low-latency, and high-bandwidth data transfer capabilities.

Mandrake 2 consists of two small satellites equipped with optical communication terminals, enabling high-speed data transfers in low Earth orbit (LEO). The program tests autonomous acquisition and tracking between satellites, a critical step for enabling resilient, laser-based communication networks in space.

![[Pasted image 20241230024110.png]]


### R3D2

https://www.darpa.mil/news/2019/reflectarray-antenna-prototype
DARPA’s R3D2 (Radio Frequency Risk Reduction Deployment Demonstration) spacecraft intends to space-qualify a prototype reflect array antenna to improve radio communications in small spacecraft. The 150kg spacecraft carried an antenna, made of a tissue-thin Kapton membrane, designed to pack tightly inside the small satellite for stowage during launch, before deploying to its full size of 2.25 meters in diameter in low Earth orbit. The design is intended to provide significant capability, typical of large spacecraft, in a much smaller package. The mission could lay the groundwork for a space-based internet by helping to validate emerging concepts for a resilient sensor and data transport layer in low Earth orbit – a capability that does not exist today.

![[Pasted image 20250104035214.png]]