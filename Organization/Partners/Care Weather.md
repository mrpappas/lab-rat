---
name: Care Weather
website: https://careweather.com/
---

>[!summary]
Care Weather is a technology company focused on deploying **small satellite-based weather observation systems**. The company specializes in **CubeSat platforms** equipped with **[microwave radiometers](https://en.wikipedia.org/wiki/Microwave_radiometer#:~:text=Microwave%20radiometers%20are%20very%20sensitive,atmospheres%2C%20surfaces%20or%20extraterrestrial%20objects.)** to provide real-time and global weather data, particularly for **storm tracking** and **climate monitoring**. Care Weather’s approach leverages low-cost, scalable satellite technology to enhance **weather forecasting capabilities** and provide critical data for industries affected by severe weather conditions.

## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Care Weather]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Care Weather]])
sort published desc
```
