---

name: NorthStar Earth & Space
website: https://northstar-data.com/
---

**Name:** NorthStar Earth & Space
**Website:** https://northstar-data.com/

>[!summary]
NorthStar Earth & Space is a Canadian company focused on Earth observation and space situational awareness (SSA). Headquartered in Montreal, NorthStar operates and develops satellite constellations designed to provide data for monitoring Earth's environment and tracking objects in orbit.
>
NorthStar's SSA services involve tracking satellites and space debris to mitigate collision risks in increasingly congested orbital environments. Their Earth observation solutions focus on applications such as climate monitoring, natural resource management, and environmental analysis.
>
The company aims to deliver critical data to governments, commercial operators, and industries for decision-making in both terrestrial and space-based operations.


## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[NorthStar Earth & Space]])
sort launch_date desc
```
%%

| File                                                              | Location                                              | Vehicle                          | Orbit & Mass            | Outcome   |
| ----------------------------------------------------------------- | ----------------------------------------------------- | -------------------------------- | ----------------------- | --------- |
| [[Launch/Launches/043 'Four Of A Kind'.md\|043 'Four Of A Kind']] | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 530 km \| 97° \| 112 kg | ✅ Success |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[NorthStar Earth & Space]])
sort published desc
```
%%

| File                                                                                                                                                                                   | Published        |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- |
| [[News/Rocket Lab Successfully Launches First Electron Mission of Busy 2024 Launch Schedule.md\|Rocket Lab Successfully Launches First Electron Mission of Busy 2024 Launch Schedule]] | January 31, 2024 |
| [[News/Rocket Lab to Launch Space Situational Awareness Mission for Spire and NorthStar.md\|Rocket Lab to Launch Space Situational Awareness Mission for Spire and NorthStar]]         | January 08, 2024 |
| [[News/Rocket Lab to Launch Space Object Monitoring Mission For Spire Global & NorthStar.md\|Rocket Lab to Launch Space Object Monitoring Mission For Spire Global & NorthStar]]       | June 22, 2023    |

%%DATAVIEW_PUBLISHER: end %%