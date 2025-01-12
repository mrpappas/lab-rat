---
name: U.S. Department of Defense
website: https://www.defense.gov/
---

>[!summary]
>The U.S. Department of Defense (DoD) is the federal agency responsible for coordinating and supervising all agencies and functions related to national security and the United States Armed Forces. Headquartered at the Pentagon, the DoD oversees the Army, Navy, Air Force, Marine Corps, and Space Force. In recent years, the DoD has intensified its focus on space as a critical domain for national security. The establishment of the U.S. Space Force in December 2019 as a separate branch under the DoD underscores this emphasis. The DoD develops and operates space-based assets for communication, navigation (including GPS), missile warning, reconnaissance, and weather monitoring. Through agencies like the Space Development Agency (SDA) and collaborations with entities such as NASA and commercial partners, the DoD advances technologies in space situational awareness, satellite defense, and maintains the United States' strategic advantages in space.

### 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[U.S. Department of Defense]])
sort launch_date desc
```

## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[U.S. Department of Defense]])
sort published desc
```
