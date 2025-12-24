---
name: Leidos
website: https://www.leidos.com/markets/space
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> Leidos

**Website:** https://www.leidos.com/markets/space

Leidos is a U.S.-based technology and defense company specializing in advanced solutions for aerospace, defense, intelligence, and civil markets. In the space sector, Leidos supports missions through systems integration, satellite communications, space domain awareness, and mission-critical technologies. The company provides services ranging from developing ground control systems to designing and managing space-related hardware, software, and data solutions for both government and commercial customers. Leidos plays a critical role in supporting national security, [[NASA]] programs, and the broader space ecosystem through innovation in autonomous systems, space infrastructure, and defense applications.

![[Pasted image 20251211022437.png]]
## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[Leidos]])
sort launch_date desc
```
%%

| File                                                            | Date             | Location                                               | Vehicle                                           | Orbit & Mass          | Outcome |
| --------------------------------------------------------------- | ---------------- | ------------------------------------------------------ | ------------------------------------------------- | --------------------- | ------- |
| [[Launch/Launches/038 - Scout's Arrow.md\|038 - Scout's Arrow]] | 2023-06-18 01:24 | [[Locations/Launch Complex 2.md#Launch Pad 0C\|LC2-0]] | [[Space Systems/Launch Vehicles/HASTE.md\|HASTE]] | Suborbital \| unknown | ✅       |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[]])
sort published desc
```
%%

| File                                                                                                                                                                                     | Published          |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ |
| [[News/Rocket Lab Signs Deal with Leidos to Launch Four HASTE Missions.md\|Rocket Lab Signs Deal with Leidos to Launch Four HASTE Missions]]                                             | September 12, 2023 |
| [[News/Rocket Lab Debuts HASTE Rocket with First Successful Suborbital Launch from Virginia.md\|Rocket Lab Debuts HASTE Rocket with First Successful Suborbital Launch from Virginia]]   | June 17, 2023      |
| [[News/Rocket Lab Introduces Suborbital Testbed Rocket, Selected for Hypersonic Test Flights.md\|Rocket Lab Introduces Suborbital Testbed Rocket, Selected for Hypersonic Test Flights]] | April 17, 2023     |

%%DATAVIEW_PUBLISHER: end %%