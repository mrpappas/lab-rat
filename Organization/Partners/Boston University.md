---

name: Boston University
website: https://www.bu.edu/
---

**Name:** Boston University
**Website:** https://www.bu.edu/

## 🚀 Launches

### <span style="color:limegreen">Successful Launches</span>

%%DATAVIEW_PUBLISHER: start
```
table launch_date
from "Launch/Launches"
where contains(customer, [[Boston University]]) and outcome = "Success"
sort launch_date desc
```
%%

| File                                                                                          | launch_date      |
| --------------------------------------------------------------------------------------------- | ---------------- |
| [[Launch/Launches/012 'Don't Stop Me Now' - Electron.md\|012 'Don't Stop Me Now' - Electron]] | 2020-06-13 05:12 |

%%DATAVIEW_PUBLISHER: end %%


## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[Boston University]])
sort published desc
```
%%

| File                                                                                                                                                                                                               | Published      |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------- |
| [[News/Rocket Lab’s Next Mission to Launch Satellites for NASA, NRO and the University of New South Wales.md\|Rocket Lab’s Next Mission to Launch Satellites for NASA, NRO and the University of New South Wales]] | March 09, 2020 |

%%DATAVIEW_PUBLISHER: end %%