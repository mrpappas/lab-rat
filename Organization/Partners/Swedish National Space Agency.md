---
name: Swedish National Space Agency
website: https://www.rymdstyrelsen.se/en/
---

>[!summary]
The Swedish National Space Agency (SNSA) is a government agency responsible for national and international space activities in Sweden. It oversees the development and implementation of Sweden's space policies, funds space research and technology development, and coordinates Sweden’s participation in international programs, such as those led by the European Space Agency (ESA). SNSA focuses on advancing scientific research, fostering innovation, and supporting satellite missions that address societal needs, such as climate monitoring, telecommunications, and Earth observation. By collaborating with academia, industry, and international partners, SNSA plays a key role in strengthening Sweden's position as a leader in space science and technology.


## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Swedish National Space Agency]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Swedish National Space Agency]])
sort published desc
```
