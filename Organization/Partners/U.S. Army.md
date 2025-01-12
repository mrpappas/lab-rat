---
name: U.S. Army
website: https://www.smdc.army.mil/
---
## Space and Missile Defense Command
>[!summary]
>The U.S. Army Space and Missile Defense Command (SMDC) is a critical component of the United States Army, specializing in space and missile defense operations to support national security. Headquartered in Redstone Arsenal, Alabama, SMDC provides expertise in developing and deploying technologies for missile defense, space operations, and global situational awareness. The command oversees satellite communications, space-based missile warning systems, and the Army's contributions to the Department of Defense's ballistic missile defense programs. SMDC also leads research and development efforts, advancing capabilities like directed energy weapons and hypersonic systems. With a focus on integrating space and missile defense into military operations, SMDC plays a pivotal role in protecting U.S. interests and maintaining strategic dominance in the increasingly contested space domain.

### 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[U.S. Army]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[U.S. Army]])
sort published desc
```
