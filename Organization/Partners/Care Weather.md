---

name: Care Weather
website: https://careweather.com/
---

**Name:** Care Weather
**Website:** https://careweather.com/

>[!summary]
Care Weather is a technology company focused on deploying **small satellite-based weather observation systems**. The company specializes in **CubeSat platforms** equipped with **[microwave radiometers](https://en.wikipedia.org/wiki/Microwave_radiometer#:~:text=Microwave%20radiometers%20are%20very%20sensitive,atmospheres%2C%20surfaces%20or%20extraterrestrial%20objects.)** to provide real-time and global weather data, particularly for **storm tracking** and **climate monitoring**. Care Weather’s approach leverages low-cost, scalable satellite technology to enhance **weather forecasting capabilities** and provide critical data for industries affected by severe weather conditions.

## 🚀 Launches

### <span style="color:limegreen">Successful Launches</span>

%%DATAVIEW_PUBLISHER: start
```
table launch_date
from "Launch/Launches"
where contains(customer, [[Care Weather]]) and outcome = "Success"
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
where contains(customer, [[Care Weather]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                                           | Published         |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------- |
| [[News/Rocket Lab Successfully Launches 19th Electron, Deploys 100th Satellite.md\|Rocket Lab Successfully Launches 19th Electron, Deploys 100th Satellite]]                                                                                                                   | March 23, 2021    |
| [[News/Rocket Lab’s Next Mission to Launch 100th Satellite and Deploy Next-Generation Photon Spacecraft in Preparation for Moon Mission.md\|Rocket Lab’s Next Mission to Launch 100th Satellite and Deploy Next-Generation Photon Spacecraft in Preparation for Moon Mission]] | February 09, 2021 |

%%DATAVIEW_PUBLISHER: end %%