---

name: York Space
website: https://www.yorkspacesystems.com/
---

**Name:** York Space
**Website:** https://www.yorkspacesystems.com/

>[!summary]
>York Space Systems is a U.S.-based satellite manufacturer specializing in the design and production of small and medium-sized satellites for commercial and government applications. Known for its standardized spacecraft platforms, such as the S-CLASS, York aims to reduce costs and streamline production timelines. The company provides end-to-end satellite solutions, including mission planning, satellite integration, and operations support, catering to industries like Earth observation, communications, and defense.


## 🚀 Launches

### <span style="color:limegreen">Successful Launches</span>

%%DATAVIEW_PUBLISHER: start
```
table launch_date
from "Launch/Launches"
where contains(customer, [[York Space Systems]]) and outcome = "Success"
sort launch_date desc
```
%%

| File                                                                        | launch_date      |
| --------------------------------------------------------------------------- | ---------------- |
| [[Launch/Launches/006 'STP-27RD' - Electron.md\|006 'STP-27RD' - Electron]] | 2019-05-05 06:00 |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table title as "Title", published as "Published"
from "News"
where contains(customer, [[York Space Systems]])
sort published desc
```
%%

| File                                                                                                                                                                                     | Title                                                                                  | Published      |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------- |
| [[News/Rocket Lab successfully launches three R&D satellites to orbit for the U.S. Air Force.md\|Rocket Lab successfully launches three R&D satellites to orbit for the U.S. Air Force]] | Rocket Lab successfully launches three R&D satellites to orbit for the U.S. Air Force  | May 05, 2019   |
| [[News/Rocket Lab to launch three R&D satellites for the U.S. Air Force.md\|Rocket Lab to launch three R&D satellites for the U.S. Air Force]]                                           | Rocket Lab to launch three R&D satellites for the U.S. Air Force                       | April 04, 2019 |

%%DATAVIEW_PUBLISHER: end %%