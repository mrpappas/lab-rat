## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table title as "Title", published as "Published"
from "News"
where contains(location, [[Launch Complex 3]])
sort published desc
```
%%

| File                                                                                                                                                                                     | Title                                                                                  | Published         |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | ----------------- |
| [[News/Rocket Lab Selects Virginia for Neutron Launch Site & Extensive Manufacturing Complex.md\|Rocket Lab Selects Virginia for Neutron Launch Site & Extensive Manufacturing Complex]] | Rocket Lab Selects Virginia for Neutron Launch Site & Extensive Manufacturing Complex  | February 28, 2022 |
| [[News/Rocket Lab selects Wallops Flight Facility for US launch site.md\|Rocket Lab selects Wallops Flight Facility for US launch site]]                                                 | Rocket Lab selects Wallops Flight Facility for US launch site                          | October 17, 2018  |

%%DATAVIEW_PUBLISHER: end %%

## 🚀 Launches from LC-3

For more info on all launches see  [[🚀 Launches]]

%%DATAVIEW_PUBLISHER: start
```
table launch_date
from "Launch/Launches"
where location = [[Launch Complex 3]]
sort launch_date desc

```
%%

| File | launch_date |
| ---- | ----------- |

%%DATAVIEW_PUBLISHER: end%%
