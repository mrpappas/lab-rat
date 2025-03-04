---

name: U.S. Space Force
website: https://www.spaceforce.mil/
---

**Name:** U.S. Space Force
**Website:** https://www.spaceforce.mil/

>[!summary]
>The U.S. Space Force (USSF), established on December 20, 2019, is the sixth branch of the United States Armed Forces and is dedicated to organizing, training, and equipping military personnel for operations in space. As the first new military branch since 1947, the Space Force focuses on ensuring U.S. superiority in the increasingly contested and congested space domain. Its primary responsibilities include maintaining and protecting critical space-based assets, such as GPS, missile warning, and secure communication satellites, as well as developing capabilities to deter and counter threats from adversaries' space activities. The USSF oversees space situational awareness, orbital debris management, and the advancement of space technologies, working closely with the Department of Defense, NASA, and private industry. With its headquarters at the Pentagon and major operations through Space Operations Command, the Space Force plays a crucial role in supporting national security and enabling global military operations.

## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date
from "Launch/Launches"
where contains(customer, [[U.S. Space Force]]) and outcome = "Success"
sort launch_date desc
```
%%

| File                                                                                                              | launch_date      |
| ----------------------------------------------------------------------------------------------------------------- | ---------------- |
| [[Launch/Launches/021 'It's A Little Chile Up Here' - Electron.md\|021 'It's A Little Chile Up Here' - Electron]] | 2021-07-29 06:00 |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[U.S. Space Force]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                                 | Published          |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ |
| [[News/Rocket Lab Clears Critical Design Review for Space Force VICTUS HAZE Mission.md\|Rocket Lab Clears Critical Design Review for Space Force VICTUS HAZE Mission]]                                                                                               | February 24, 2025  |
| [[News/Rocket Lab Selected by Space Systems Command to Build and Launch Spacecraft for Tactically Responsive Space (TacRS) Mission.md\|Rocket Lab Selected by Space Systems Command to Build and Launch Spacecraft for Tactically Responsive Space (TacRS) Mission]] | April 11, 2024     |
| [[News/U.S. Space Force Awards Rocket Lab Launch Contract for Space Test Program (STP)-S30.md\|U.S. Space Force Awards Rocket Lab Launch Contract for Space Test Program (STP)-S30]]                                                                                 | April 08, 2024     |
| [[News/Rocket Lab to Supply Solar Power for United States Space Force’s New Missile Warning Satellites  Rocket Lab.md\|Rocket Lab to Supply Solar Power for United States Space Force’s New Missile Warning Satellites  Rocket Lab]]                                 | July 27, 2022      |
| [[News/Rocket Lab Wins $24m U.S. Space Force Contract to Develop Neutron Upper Stage.md\|Rocket Lab Wins $24m U.S. Space Force Contract to Develop Neutron Upper Stage]]                                                                                             | September 27, 2021 |
| [[News/Rocket Lab Successfully Launches U.S. Space Force Mission.md\|Rocket Lab Successfully Launches U.S. Space Force Mission]]                                                                                                                                     | July 29, 2021      |
| [[News/Rocket Lab to Launch U.S. Space Force Mission from Launch Complex 1 in New Zealand.md\|Rocket Lab to Launch U.S. Space Force Mission from Launch Complex 1 in New Zealand]]                                                                                   | July 27, 2021      |

%%DATAVIEW_PUBLISHER: end %%