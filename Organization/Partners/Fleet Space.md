---

name: Fleet Space
website: https://www.fleetspace.com/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> Fleet Space

**Website:** https://www.fleetspace.com/

>[!summary]
Fleet Space Technologies is an Australian company specializing in satellite-based connectivity solutions, focusing on Internet of Things (IoT) applications. Fleet operates a constellation of small low Earth orbit ([[🌍 Orbits#LEO|LEO]]) satellites that provide global, low-power, and cost-effective communications for industries such as mining, energy, agriculture, and defense. Their [ExoSphere](https://www.fleetspace.com/mineral-exploration) service combines satellite technology with geophysical sensors to support exploration and resource management. Fleet Space emphasizes innovation in nanosatellite design and rapid deployment to enable scalable IoT solutions.
## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[Fleet Space]])
sort launch_date desc
```
%%

| File                                                                      | Date             | Location                                              | Vehicle                          | Orbit & Mass                        | Outcome |
| ------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ----------------------------------- | ------- |
| [[Launch/Launches/019 - They Go Up So Fast.md\|019 - They Go Up So Fast]] | 2021-03-22 22:30 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 450 km and 550 km \| 45° \| Unknown | ✅       |
| [[Launch/Launches/003 - It's Business Time.md\|003 - It's Business Time]] | 2018-11-11 03:50 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 500 km \| 85° \| 45 kg              | ✅       |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[Fleet Space]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                                           | Published         |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------- |
| [[News/Rocket Lab Successfully Launches 19th Electron, Deploys 100th Satellite.md\|Rocket Lab Successfully Launches 19th Electron, Deploys 100th Satellite]]                                                                                                                   | March 23, 2021    |
| [[News/Rocket Lab’s Next Mission to Launch 100th Satellite and Deploy Next-Generation Photon Spacecraft in Preparation for Moon Mission.md\|Rocket Lab’s Next Mission to Launch 100th Satellite and Deploy Next-Generation Photon Spacecraft in Preparation for Moon Mission]] | February 09, 2021 |
| [[News/Rocket Lab reaches orbit again, deploys more satellites.md\|Rocket Lab reaches orbit again, deploys more satellites]]                                                                                                                                                   | November 11, 2018 |
| [[News/Rocket Lab enters high frequency launch operations.md\|Rocket Lab enters high frequency launch operations]]                                                                                                                                                             | October 30, 2018  |
| [[News/Fleet Space Technologies joins Rocket Lab manifest for  It’s Business Time mission.md\|Fleet Space Technologies joins Rocket Lab manifest for  It’s Business Time mission]]                                                                                             | October 29, 2018  |
| [[News/Rocket Lab to launch It’s Business Time and ELaNa XIX missions weeks apart.md\|Rocket Lab to launch It’s Business Time and ELaNa XIX missions weeks apart]]                                                                                                             | August 06, 2018   |
| [[News/Rocket Lab confirms new ‘It’s Business Time’ launch window and bolsters manifest.md\|Rocket Lab confirms new ‘It’s Business Time’ launch window and bolsters manifest]]                                                                                                 | May 25, 2018      |
| [[News/Rocket Lab moves ‘It’s Business Time’ launch window.md\|Rocket Lab moves ‘It’s Business Time’ launch window]]                                                                                                                                                           | April 17, 2018    |
| [[News/Rocket Lab 'Its Business Time' launch window to open 20 April 2018 NZT.md\|Rocket Lab 'Its Business Time' launch window to open 20 April 2018 NZT]]                                                                                                                     | April 03, 2018    |
| [[News/It's Business Time at Rocket Lab.md\|It's Business Time at Rocket Lab]]                                                                                                                                                                                                 | March 13, 2018    |

%%DATAVIEW_PUBLISHER: end %%