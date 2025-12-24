---

name: Tyvak Nano-Satellite Systems
website: https://tyvak.eu/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> Tyvak Nano-Satellite Systems

**Website:** https://tyvak.eu/
Absorbed by [[Terran Orbital]]

Tyvak Nano-Satellite Systems designs and builds advanced small satellites, offering end-to-end solutions for commercial, government, and defense missions. With expertise in nano-satellite technology and rapid deployment, Tyvak delivers cost-effective, high-performance spacecraft tailored to meet specific mission needs, enabling operations in low Earth orbit and beyond. As part of Terran Orbital, Tyvak drives innovation in the growing small satellite market, supporting critical applications for clients like NASA and the Department of Defense.

![[Pasted image 20251211015135.jpg|300]]

## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[]])
sort launch_date desc
```
%%

| File                                                                      | Date             | Location                                              | Vehicle                                                 | Orbit & Mass                        | Outcome |
| ------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | ------------------------------------------------------- | ----------------------------------- | ------- |
| [[Launch/Launches/019 - They Go Up So Fast.md\|019 - They Go Up So Fast]] | 2021-03-22 22:30 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 450 km and 550 km \| 45° \| Unknown | ✅       |
| [[Launch/Launches/003 - It's Business Time.md\|003 - It's Business Time]] | 2018-11-11 03:50 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 500 km \| 85° \| 45 kg              | ✅       |

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

| File                                                                                                                                                                                                                                                                           | Published         |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------- |
| [[News/Rocket Lab Successfully Launches 19th Electron, Deploys 100th Satellite.md\|Rocket Lab Successfully Launches 19th Electron, Deploys 100th Satellite]]                                                                                                                   | March 23, 2021    |
| [[News/Rocket Lab’s Next Mission to Launch 100th Satellite and Deploy Next-Generation Photon Spacecraft in Preparation for Moon Mission.md\|Rocket Lab’s Next Mission to Launch 100th Satellite and Deploy Next-Generation Photon Spacecraft in Preparation for Moon Mission]] | February 09, 2021 |
| [[News/Rocket Lab reaches orbit again, deploys more satellites.md\|Rocket Lab reaches orbit again, deploys more satellites]]                                                                                                                                                   | November 11, 2018 |
| [[News/Rocket Lab enters high frequency launch operations.md\|Rocket Lab enters high frequency launch operations]]                                                                                                                                                             | October 30, 2018  |
| [[News/Rocket Lab to launch It’s Business Time and ELaNa XIX missions weeks apart.md\|Rocket Lab to launch It’s Business Time and ELaNa XIX missions weeks apart]]                                                                                                             | August 06, 2018   |
| [[News/Rocket Lab confirms new ‘It’s Business Time’ launch window and bolsters manifest.md\|Rocket Lab confirms new ‘It’s Business Time’ launch window and bolsters manifest]]                                                                                                 | May 25, 2018      |
| [[News/Rocket Lab moves ‘It’s Business Time’ launch window.md\|Rocket Lab moves ‘It’s Business Time’ launch window]]                                                                                                                                                           | April 17, 2018    |
| [[News/Rocket Lab 'Its Business Time' launch window to open 20 April 2018 NZT.md\|Rocket Lab 'Its Business Time' launch window to open 20 April 2018 NZT]]                                                                                                                     | April 03, 2018    |
| [[News/It's Business Time at Rocket Lab.md\|It's Business Time at Rocket Lab]]                                                                                                                                                                                                 | March 13, 2018    |

%%DATAVIEW_PUBLISHER: end %%
## Notes

- "Before it became a publicly traded company in March, [[Terran Orbital]], headquartered in Boca Raton, Florida, reorganized and announced it would phase out the name Tyvak as it transitioned from nanosats and cubesats to larger satellites. " [Source](https://spacenews.com/terran-orbital-sees-staff-departures-as-it-turns-focus-to-military-satellites/)