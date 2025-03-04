---

name: Leidos
website: https://www.leidos.com/markets/space
---

**Name:** Leidos
**Website:** https://www.leidos.com/markets/space

>[!summary]
Leidos is a U.S.-based technology and defense company specializing in advanced solutions for aerospace, defense, intelligence, and civil markets. In the space sector, Leidos supports missions through systems integration, satellite communications, space domain awareness, and mission-critical technologies. The company provides services ranging from developing ground control systems to designing and managing space-related hardware, software, and data solutions for both government and commercial customers. Leidos plays a critical role in supporting national security, [[NASA]] programs, and the broader space ecosystem through innovation in autonomous systems, space infrastructure, and defense applications.

## 🚀 Launches

### <span style="color:limegreen">Successful Launches</span>

%%DATAVIEW_PUBLISHER: start
```
table launch_date
from "Launch/Launches"
where contains(customer, [[Leidos]]) and outcome = "Success"
sort launch_date desc
```
%%

| File                                                                            | launch_date      |
| ------------------------------------------------------------------------------- | ---------------- |
| [[Launch/Launches/038 'Scout's Arrow' - HASTE.md\|038 'Scout's Arrow' - HASTE]] | 2023-06-18 01:24 |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Leidos]])
sort published desc
```
%%

| File                                                                                                                                                                                   | Title                                                                                  | Published          |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | ------------------ |
| [[News/Rocket Lab Signs Deal with Leidos to Launch Four HASTE Missions.md\|Rocket Lab Signs Deal with Leidos to Launch Four HASTE Missions]]                                           | Rocket Lab Signs Deal with Leidos to Launch Four HASTE Missions                        | September 12, 2023 |
| [[News/Rocket Lab Debuts HASTE Rocket with First Successful Suborbital Launch from Virginia.md\|Rocket Lab Debuts HASTE Rocket with First Successful Suborbital Launch from Virginia]] | Rocket Lab Debuts HASTE Rocket with First Successful Suborbital Launch from Virginia   | June 17, 2023      |

%%DATAVIEW_PUBLISHER: end %%