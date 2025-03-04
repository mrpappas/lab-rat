---

name: In-Space Missions
website: https://in-space.co.uk/
---

**Name:** In-Space Missions
**Website:** https://in-space.co.uk/

>[!summary]
In-Space Missions is a UK-based company that designs, builds, and operates satellites, specializing in rideshare missions like the Faraday series, which host multiple payloads on a single platform. They offer rapid access to space for technology demonstration, Earth observation, and communication missions. Acquired by [BAE Systems](https://www.baesystems.com/en/home) in 2021, they support commercial, governmental, and research customers.

## 🚀 Launches

### <span style="color:orangered">Failed Launches</span>

%%DATAVIEW_PUBLISHER: start
```
table launch_date
from "Launch/Launches"
where contains(customer, [[In-Space Missions]]) and outcome = "Failure"
sort launch_date desc
```
%%

| File                                                                                                        | launch_date      |
| ----------------------------------------------------------------------------------------------------------- | ---------------- |
| [[Launch/Launches/013 'Pics Or It Didn't Happen' - Electron.md\|013 'Pics Or It Didn't Happen' - Electron]] | 2020-07-04 21:19 |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table title as "Title", published as "Published"
from "News"
where contains(customer, [[In-Space Missions]])
sort published desc
```
%%

| File                                                                                                                                 | Title                                                         | Published     |
| ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------- | ------------- |
| [[News/Rocket Lab to Resume Electron Launches in August.md\|Rocket Lab to Resume Electron Launches in August]]                       | Rocket Lab to Resume Electron Launches in August              | July 31, 2020 |
| [[News/Rocket Lab Mission Fails to Reach Orbit.md\|Rocket Lab Mission Fails to Reach Orbit]]                                         | Rocket Lab Mission Fails to Reach Orbit                       | July 04, 2020 |
| [[News/Rocket Lab to Demonstrate Fastest Launch Turnaround to Date.md\|Rocket Lab to Demonstrate Fastest Launch Turnaround to Date]] | Rocket Lab to Demonstrate Fastest Launch Turnaround to Date   | June 15, 2020 |

%%DATAVIEW_PUBLISHER: end %%