---
name: Myriota
website: https://myriota.com/
---

>[!summary]
Myriota is an Australian company specializing in low-power, direct-to-satellite IoT (Internet of Things) connectivity. Headquartered in Adelaide, Myriota provides affordable and efficient solutions for transmitting small amounts of data from remote sensors and devices via its satellite constellation.
>
Myriota’s technology enables industries such as agriculture, utilities, environmental monitoring, and asset tracking to connect devices globally without relying on traditional terrestrial infrastructure. Their system allows ultra-low-power communication, extending the life of IoT devices in remote locations for years on minimal energy.


## 🚀 Launches
%%DATAVIEW_PUBLISHER: start
```
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Myriota]])
sort launch_date desc
```
%%

| File                                                                                            | launch_date      | outcome |
| ----------------------------------------------------------------------------------------------- | ---------------- | ------- |
| [[Launch/Launches/019 'They Go Up So Fast' - Electron.md\|019 'They Go Up So Fast' - Electron]] | 2021-03-22 22:30 | Success |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Myriota]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                                           | Title                                                                                                                             | Published         |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/Rocket Lab Successfully Launches 19th Electron, Deploys 100th Satellite.md\|Rocket Lab Successfully Launches 19th Electron, Deploys 100th Satellite]]                                                                                                                   | Rocket Lab Successfully Launches 19th Electron, Deploys 100th Satellite                                                           | March 23, 2021    |
| [[News/Rocket Lab’s Next Mission to Launch 100th Satellite and Deploy Next-Generation Photon Spacecraft in Preparation for Moon Mission.md\|Rocket Lab’s Next Mission to Launch 100th Satellite and Deploy Next-Generation Photon Spacecraft in Preparation for Moon Mission]] | Rocket Lab’s Next Mission to Launch 100th Satellite and Deploy Next-Generation Photon Spacecraft in Preparation for Moon Mission  | February 09, 2021 |

%%DATAVIEW_PUBLISHER: end %%