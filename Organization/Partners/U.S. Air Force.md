---

name: U.S. Air Force
website: https://www.airforce.com/
---

**Name:** U.S. Air Force
**Website:** https://www.airforce.com/

>[!summary]
>The U.S. Air Force (USAF) plays a vital role in national security through its operations in air, space, and cyber domains, with a significant focus on space capabilities. Before the establishment of the [[U.S. Space Force]] in 2019, the USAF managed the majority of the Department of Defense's space operations. Its contributions include developing and maintaining critical satellite systems for global positioning (GPS), missile warning, communications, and weather monitoring. The USAF also pioneered space surveillance, orbital debris tracking, and space situational awareness to ensure safe and secure operations in Earth's orbit. Today, the Air Force continues to support space missions through collaboration with the Space Force, focusing on advanced technologies, launch systems, and integrating space capabilities into joint military operations to maintain U.S. superiority in space.

## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[U.S. Air Force]])
sort launch_date desc
```
%%

| File                                                                    | Date             | Location                                              | Vehicle                          | Orbit & Mass             | Outcome   |
| ----------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ------------------------ | --------- |
| [[Launch/Launches/008 'Look Ma, No Hands'.md\|008 'Look Ma, No Hands']] | 2019-08-19 12:12 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 510 km \| 94.8° \| 80 kg | ✅ Success |
| [[Launch/Launches/006 'STP-27RD'.md\|006 'STP-27RD']]                   | 2019-05-05 06:00 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 500 km \| 40° \| 180 kg  | ✅ Success |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[U.S. Air Force]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                 | Published         |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/Rocket Lab Granted Air Force Research Lab Award to Showcase Digital Engineering with New Archimedes Rocket Engine.md\|Rocket Lab Granted Air Force Research Lab Award to Showcase Digital Engineering with New Archimedes Rocket Engine]]     | November 12, 2024 |
| [[News/Rocket Lab Opens Launch Complex 2, Confirms U.S. Air Force Payload as First Electron Mission from U.S. Soil.md\|Rocket Lab Opens Launch Complex 2, Confirms U.S. Air Force Payload as First Electron Mission from U.S. Soil]]                 | December 12, 2019 |
| [[News/Rocket Lab successfully launches eighth Electron mission,  takes next step in recovery and reuse for future flights.md\|Rocket Lab successfully launches eighth Electron mission,  takes next step in recovery and reuse for future flights]] | August 20, 2019   |
| [[News/Rocket Lab’s Next Mission Focused On Building Constellations And Enabling R&D.md\|Rocket Lab’s Next Mission Focused On Building Constellations And Enabling R&D]]                                                                             | July 22, 2019     |
| [[News/Rocket Lab successfully launches three R&D satellites to orbit for the U.S. Air Force.md\|Rocket Lab successfully launches three R&D satellites to orbit for the U.S. Air Force]]                                                             | May 05, 2019      |
| [[News/Rocket Lab to launch three R&D satellites for the U.S. Air Force.md\|Rocket Lab to launch three R&D satellites for the U.S. Air Force]]                                                                                                       | April 04, 2019    |

%%DATAVIEW_PUBLISHER: end %%