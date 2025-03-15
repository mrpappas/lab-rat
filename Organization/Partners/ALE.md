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
table location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[ALE]])
sort launch_date desc
```
%%

| File                                                                              | Location                                              | Vehicle                          | Orbit & Mass                 | Outcome   |
| --------------------------------------------------------------------------------- | ----------------------------------------------------- | -------------------------------- | ---------------------------- | --------- |
| [[Launch/Launches/010 'Running Out Of Fingers'.md\|010 'Running Out Of Fingers']] | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 385 x 400 km \| 97° \| 77 kg | ✅ Success |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News

%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[ALE]])
sort published desc
```
%%

| File                                                                                                                                                                                                           | Published         |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/Rocket Lab Debuts Fully Autonomous Flight Termination System.md\|Rocket Lab Debuts Fully Autonomous Flight Termination System]]                                                                         | December 09, 2019 |
| [[News/Rocket Lab launches milestone tenth mission, completes major success for reusable rocket program.md\|Rocket Lab launches milestone tenth mission, completes major success for reusable rocket program]] | December 06, 2019 |
| [[News/Next Generation Electron Booster on the Pad  for Rocket Lab’s 10th Mission.md\|Next Generation Electron Booster on the Pad  for Rocket Lab’s 10th Mission]]                                             | November 05, 2019 |

%%DATAVIEW_PUBLISHER: end %%