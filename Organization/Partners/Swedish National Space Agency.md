---

name: Swedish National Space Agency
website: https://www.rymdstyrelsen.se/en/
---

**Name:** Swedish National Space Agency
**Website:** https://www.rymdstyrelsen.se/en/

>[!summary]
The Swedish National Space Agency (SNSA) is a government agency responsible for national and international space activities in Sweden. It oversees the development and implementation of Sweden's space policies, funds space research and technology development, and coordinates Sweden’s participation in international programs, such as those led by the European Space Agency (ESA). SNSA focuses on advancing scientific research, fostering innovation, and supporting satellite missions that address societal needs, such as climate monitoring, telecommunications, and Earth observation. By collaborating with academia, industry, and international partners, SNSA plays a key role in strengthening Sweden's position as a leader in space science and technology.


## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date
from "Launch/Launches"
where contains(customer, [[Swedish National Space Agency]]) and outcome = "Success"
sort launch_date desc
```
%%

| File                                                                                              | launch_date      |
| ------------------------------------------------------------------------------------------------- | ---------------- |
| [[Launch/Launches/032 'Catch Me If You Can' - Electron.md\|032 'Catch Me If You Can' - Electron]] | 2022-11-04 17:27 |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[Swedish National Space Agency]])
sort published desc
```
%%

| File                                                                                                                                                                       | Published         |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/Rocket Lab Successfully Deploys 152nd Satellite.md\|Rocket Lab Successfully Deploys 152nd Satellite]]                                                               | November 04, 2022 |
| [[News/Rocket Lab to Attempt Next Mid-Air Helicopter Rocket Catch During Next Mission.md\|Rocket Lab to Attempt Next Mid-Air Helicopter Rocket Catch During Next Mission]] | November 01, 2022 |

%%DATAVIEW_PUBLISHER: end %%