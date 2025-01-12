---
name: NorthStar Earth & Space
website: https://northstar-data.com/
---

>[!summary]
NorthStar Earth & Space is a Canadian company focused on Earth observation and space situational awareness (SSA). Headquartered in Montreal, NorthStar operates and develops satellite constellations designed to provide data for monitoring Earth's environment and tracking objects in orbit.
>
NorthStar's SSA services involve tracking satellites and space debris to mitigate collision risks in increasingly congested orbital environments. Their Earth observation solutions focus on applications such as climate monitoring, natural resource management, and environmental analysis.
>
The company aims to deliver critical data to governments, commercial operators, and industries for decision-making in both terrestrial and space-based operations.


## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[NorthStar Earth & Space]])
sort launch_date desc
```

## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[NorthStar Earth & Space]])
sort published desc
```
