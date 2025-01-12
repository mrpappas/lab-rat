---
name: U.S. Space Force
website: https://www.spaceforce.mil/
---

>[!summary]
>The U.S. Space Force (USSF), established on December 20, 2019, is the sixth branch of the United States Armed Forces and is dedicated to organizing, training, and equipping military personnel for operations in space. As the first new military branch since 1947, the Space Force focuses on ensuring U.S. superiority in the increasingly contested and congested space domain. Its primary responsibilities include maintaining and protecting critical space-based assets, such as GPS, missile warning, and secure communication satellites, as well as developing capabilities to deter and counter threats from adversaries' space activities. The USSF oversees space situational awareness, orbital debris management, and the advancement of space technologies, working closely with the Department of Defense, NASA, and private industry. With its headquarters at the Pentagon and major operations through Space Operations Command, the Space Force plays a crucial role in supporting national security and enabling global military operations.

### 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[U.S. Space Force]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[U.S. Space Force]])
sort published desc
```
