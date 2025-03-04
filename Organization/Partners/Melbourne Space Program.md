---

name: Melbourne Space Program
website: https://www.melbournespace.com.au/
---

**Name:** Melbourne Space Program
**Website:** https://www.melbournespace.com.au/

>[!summary]
The Melbourne Space Program is a non-profit organization based in Melbourne, Australia, focused on student-led satellite development and hands-on space systems education. Their key achievements include the ACRUX-1 CubeSat, launched in June 2019 aboard a Rocket Lab Electron, as a demonstration of satellite design and deployment capabilities. Future missions, such as ACRUX-2, aim to build on this success. The program emphasizes practical training in space engineering and systems development for students and early-career professionals.

## 🚀 Launches

### <span style="color:limegreen">Successful Launches</span>

%%DATAVIEW_PUBLISHER: start
```
table launch_date
from "Launch/Launches"
where contains(customer, [[Melbourne Space Program]]) and outcome = "Success"
sort launch_date desc
```
%%

| File                                                                                | launch_date      |
| ----------------------------------------------------------------------------------- | ---------------- |
| [[Launch/Launches/007 'Make it Rain' - Electron.md\|007 'Make it Rain' - Electron]] | 2019-06-29 04:30 |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[Melbourne Space Program]])
sort published desc
```
%%

| File                                                                                                                                                                                                   | Published     |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------- |
| [[News/Rocket Lab successfully launches seventh Electron mission, deploys seven satellites to orbit.md\|Rocket Lab successfully launches seventh Electron mission, deploys seven satellites to orbit]] | June 29, 2019 |
| [[News/Rocket Lab to launch rideshare mission for Spaceflight.md\|Rocket Lab to launch rideshare mission for Spaceflight]]                                                                             | May 10, 2019  |

%%DATAVIEW_PUBLISHER: end %%
## ✏️ Notes

- Future ACRUX-2 project: https://www.melbournespace.com.au/projects