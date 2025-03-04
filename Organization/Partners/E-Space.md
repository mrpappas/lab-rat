---

name: E-Space
website: https://e-space.com/
---

**Name:** E-Space
**Website:** https://e-space.com/

>[!summary]
E-Space is a low Earth orbit ([[🌍 Orbits#LEO|LEO]]) satellite communications company focused on building a sustainable satellite network. The company aims to deploy low-cost, small satellites that offer global connectivity while minimizing space debris through collision avoidance and deorbiting technologies. E-Space emphasizes modular satellite design, efficient manufacturing, and a focus on sustainability to enable scalable and responsible space-based communications solutions for commercial, government, and IoT applications.

## 🚀 Launches

### <span style="color:limegreen">Successful Launches</span>

%%DATAVIEW_PUBLISHER: start
```
table launch_date
from "Launch/Launches"
where contains(customer, [[E-Space]]) and outcome = "Success"
sort launch_date desc
```
%%

| File                                                                                                                                            | launch_date      |
| ----------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- |
| [[Launch/Launches/054 'Changes In Latitudes, Changes In Attitudes' - Electron.md\|054 'Changes In Latitudes, Changes In Attitudes' - Electron]] | 2024-11-05 10:54 |
| [[Launch/Launches/026 'There And Back Again' - Electron.md\|026 'There And Back Again' - Electron]]                                             | 2022-05-02 22:49 |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table title as "Title", published as "Published"
from "News"
where contains(customer, [[E-Space]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                     | Title                                                                                                          | Published         |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/From Contract to Space in Less Than Ten Weeks Rocket Lab Launches its 54th Electron Mission.md\|From Contract to Space in Less Than Ten Weeks Rocket Lab Launches its 54th Electron Mission]]                                     | From Contract to Space in Less Than Ten Weeks: Rocket Lab Launches its 54th Electron Mission                   | November 05, 2024 |
| [[News/Rocket Lab Adds New Mission to 2024 Launch Manifest, Schedules Launch in Coming Days.md\|Rocket Lab Adds New Mission to 2024 Launch Manifest, Schedules Launch in Coming Days]]                                                   | Rocket Lab Adds New Mission to 2024 Launch Manifest, Schedules Launch in Coming Days                           | October 16, 2024  |
| [[News/Rocket Lab Successfully Deploys 34 Satellites and Catches Rocket Booster Returning from Space with Helicopter.md\|Rocket Lab Successfully Deploys 34 Satellites and Catches Rocket Booster Returning from Space with Helicopter]] | Rocket Lab Successfully Deploys 34 Satellites and Catches Rocket Booster Returning from Space with Helicopter  | May 02, 2022      |
| [[News/Rocket Lab to Attempt First Mid-Air Helicopter Capture of the Electron Rocket During Next Mission.md\|Rocket Lab to Attempt First Mid-Air Helicopter Capture of the Electron Rocket During Next Mission]]                         | Rocket Lab to Attempt First Mid-Air Helicopter Capture of the Electron Rocket During Next Mission              | April 06, 2022    |
| [[News/Rocket Lab to Launch Three Demonstration Satellites for E-Space.md\|Rocket Lab to Launch Three Demonstration Satellites for E-Space]]                                                                                             | Rocket Lab to Launch Three Demonstration Satellites for E-Space                                                | March 21, 2022    |

%%DATAVIEW_PUBLISHER: end %%

## ✏️ Notes

- [[054 'Changes In Latitudes, Changes In Attitudes' - Electron]] Rocket Lab did not publicly disclose the customer but New Zealand government filings indicated E-Space was likely the customer. [Source](https://x.com/SpaceEquities/status/1846992995419333052)