---

name: ALE
website: https://star-ale.com/en/technology/

---

**Name:** ALE
**Website:** https://star-ale.com/en/technology/

>[!summary]
ALE Co., Ltd. is a Japanese company specializing in space entertainment and atmospheric research through artificial meteor showers. ALE uses small satellites equipped with technology to release specially designed particles that create visible "shooting stars" when they re-enter Earth's atmosphere and burn up. This technology enables unique light displays for events and scientific observation while contributing to atmospheric data collection. ALE's mission combines innovation in space with commercial applications and scientific research, aiming to advance our understanding of Earth's atmosphere while creating novel space-based experiences.

## 🚀 Launches
%%DATAVIEW_PUBLISHER: start
```
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[ALE]])
sort launch_date desc
```
%%

| File                                                                                                    | launch_date      | outcome |
| ------------------------------------------------------------------------------------------------------- | ---------------- | ------- |
| [[Launch/Launches/010 'Running Out Of Fingers' - Electron.md\|010 'Running Out Of Fingers' - Electron]] | 2019-12-06 08:18 | Success |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News

%%DATAVIEW_PUBLISHER: start
```
table title as "Title", published as "Published"
from "News"
where contains(customer, [[ALE]])
sort published desc
```
%%

| File                                                                                                                                                                                                           | Title                                                                                              | Published         |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/Rocket Lab Debuts Fully Autonomous Flight Termination System.md\|Rocket Lab Debuts Fully Autonomous Flight Termination System]]                                                                         | Rocket Lab Debuts Fully Autonomous Flight Termination System                                       | December 09, 2019 |
| [[News/Rocket Lab launches milestone tenth mission, completes major success for reusable rocket program.md\|Rocket Lab launches milestone tenth mission, completes major success for reusable rocket program]] | Rocket Lab launches milestone tenth mission, completes major success for reusable rocket program   | December 06, 2019 |
| [[News/Next Generation Electron Booster on the Pad  for Rocket Lab’s 10th Mission.md\|Next Generation Electron Booster on the Pad  for Rocket Lab’s 10th Mission]]                                             | Next Generation Electron Booster on the Pad  for Rocket Lab’s 10th Mission                         | November 05, 2019 |

%%DATAVIEW_PUBLISHER: end %%