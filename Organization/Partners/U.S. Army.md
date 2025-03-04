---

name: U.S. Army
website: https://www.smdc.army.mil/
---

**Name:** U.S. Army
**Website:** https://www.smdc.army.mil/

## Space and Missile Defense Command
>[!summary]
>The U.S. Army Space and Missile Defense Command (SMDC) is a critical component of the United States Army, specializing in space and missile defense operations to support national security. Headquartered in Redstone Arsenal, Alabama, SMDC provides expertise in developing and deploying technologies for missile defense, space operations, and global situational awareness. The command oversees satellite communications, space-based missile warning systems, and the Army's contributions to the Department of Defense's ballistic missile defense programs. SMDC also leads research and development efforts, advancing capabilities like directed energy weapons and hypersonic systems. With a focus on integrating space and missile defense into military operations, SMDC plays a pivotal role in protecting U.S. interests and maintaining strategic dominance in the increasingly contested space domain.

## 🚀 Launches

### <span style="color:limegreen">Successful Launches</span>

%%DATAVIEW_PUBLISHER: start
```
table launch_date
from "Launch/Launches"
where contains(customer, [[U.S. Army]]) and outcome = "Success"
sort launch_date desc
```
%%

| File                                                                                            | launch_date      |
| ----------------------------------------------------------------------------------------------- | ---------------- |
| [[Launch/Launches/019 'They Go Up So Fast' - Electron.md\|019 'They Go Up So Fast' - Electron]] | 2021-03-22 22:30 |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[U.S. Army]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                                           | Published         |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------- |
| [[News/Rocket Lab Successfully Launches 19th Electron, Deploys 100th Satellite.md\|Rocket Lab Successfully Launches 19th Electron, Deploys 100th Satellite]]                                                                                                                   | March 23, 2021    |
| [[News/Rocket Lab’s Next Mission to Launch 100th Satellite and Deploy Next-Generation Photon Spacecraft in Preparation for Moon Mission.md\|Rocket Lab’s Next Mission to Launch 100th Satellite and Deploy Next-Generation Photon Spacecraft in Preparation for Moon Mission]] | February 09, 2021 |

%%DATAVIEW_PUBLISHER: end %%