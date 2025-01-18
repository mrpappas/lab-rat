---
name: Astrix Astronautics
website: https://astrix.space/
---

>[!summary]
Astrix Astronautics is a New Zealand-based company specializing in innovative power systems for small satellites. The company focuses on developing high-performance solar arrays and deployable power solutions to maximize energy efficiency for small satellite platforms. Astrix's technology is designed to meet the growing power demands of modern satellite missions, supporting applications such as Earth observation, communications, and deep space exploration. Their systems enable increased satellite capabilities while maintaining a compact and lightweight form factor, catering to both commercial and government customers in the space industry.

## 🚀 Launches
%%DATAVIEW_PUBLISHER: start
```
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Astrix Astronautics]])
sort launch_date desc
```
%%

| File                                                                                                | launch_date      | outcome |
| --------------------------------------------------------------------------------------------------- | ---------------- | ------- |
| [[Launch/Launches/026 'There And Back Again' - Electron.md\|026 'There And Back Again' - Electron]] | 2022-05-02 22:49 | Success |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Astrix Astronautics]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                     | Title                                                                                                          | Published      |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | -------------- |
| [[News/Rocket Lab Successfully Deploys 34 Satellites and Catches Rocket Booster Returning from Space with Helicopter.md\|Rocket Lab Successfully Deploys 34 Satellites and Catches Rocket Booster Returning from Space with Helicopter]] | Rocket Lab Successfully Deploys 34 Satellites and Catches Rocket Booster Returning from Space with Helicopter  | May 02, 2022   |
| [[News/Rocket Lab to Attempt First Mid-Air Helicopter Capture of the Electron Rocket During Next Mission.md\|Rocket Lab to Attempt First Mid-Air Helicopter Capture of the Electron Rocket During Next Mission]]                         | Rocket Lab to Attempt First Mid-Air Helicopter Capture of the Electron Rocket During Next Mission              | April 06, 2022 |

%%DATAVIEW_PUBLISHER: end %%