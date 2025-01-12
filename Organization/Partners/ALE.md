---
name: ALE
website: https://star-ale.com/en/technology/

---

>[!summary]
ALE Co., Ltd. is a Japanese company specializing in space entertainment and atmospheric research through artificial meteor showers. ALE uses small satellites equipped with technology to release specially designed particles that create visible "shooting stars" when they re-enter Earth's atmosphere and burn up. This technology enables unique light displays for events and scientific observation while contributing to atmospheric data collection. ALE's mission combines innovation in space with commercial applications and scientific research, aiming to advance our understanding of Earth's atmosphere while creating novel space-based experiences.

### 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[ALE]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[ALE]])
sort published desc
```
