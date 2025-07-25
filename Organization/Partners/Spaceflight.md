---

name: Spaceflight
website: https://en.wikipedia.org/wiki/Spaceflight,_Inc.
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> Spaceflight

**Website:** https://en.wikipedia.org/wiki/Spaceflight,_Inc.

>[!summary]
Spaceflight Inc. was known as a leader in arranging launches of small satellites on small launch vehicles or as secondary payloads on larger launch vehicles, deploying more than 460 payloads. Spaceflight had also developed its own series of orbital transfer vehicles called Sherpa, using a mix of chemical and electric propulsion systems.


## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[Spaceflight]])
sort launch_date desc
```
%%

| File                                                                                  | Date             | Location                                              | Vehicle                          | Orbit & Mass                 | Outcome |
| ------------------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ---------------------------- | ------- |
| [[Launch/Launches/026 - There And Back Again.md\|026 - There And Back Again]]         | 2022-05-02 22:49 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 520 km \| 94° \| Unknown     | ✅       |
| [[Launch/Launches/022 - Love At First Insight.md\|022 - Love At First Insight]]       | 2021-11-18 01:38 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 430 km \| 42° \| 120 kg      | ✅       |
| [[Launch/Launches/015 - In Focus.md\|015 - In Focus]]                                 | 2020-10-28 21:21 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 500 km \| 97.5° \| 72 kg     | ✅       |
| [[Launch/Launches/013 - Pics Or It Didn't Happen.md\|013 - Pics Or It Didn't Happen]] | 2020-07-04 21:19 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 500 km \| 97.5° \| 75 kg     | ❌       |
| [[Launch/Launches/010 - Running Out Of Fingers.md\|010 - Running Out Of Fingers]]     | 2019-12-06 08:18 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 385 x 400 km \| 97° \| 77 kg | ✅       |
| [[Launch/Launches/007 - Make it Rain.md\|007 - Make it Rain]]                         | 2019-06-29 04:30 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 450 km \| 45° \| 80 kg       | ✅       |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[Spaceflight]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                     | Published          |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ |
| [[News/Rocket Lab Successfully Deploys 34 Satellites and Catches Rocket Booster Returning from Space with Helicopter.md\|Rocket Lab Successfully Deploys 34 Satellites and Catches Rocket Booster Returning from Space with Helicopter]] | May 02, 2022       |
| [[News/Rocket Lab to Attempt First Mid-Air Helicopter Capture of the Electron Rocket During Next Mission.md\|Rocket Lab to Attempt First Mid-Air Helicopter Capture of the Electron Rocket During Next Mission]]                         | April 06, 2022     |
| [[News/Rocket Lab Launches 107th Satellite To Orbit, Successfully Tests Helicopter Recovery Operations.md\|Rocket Lab Launches 107th Satellite To Orbit, Successfully Tests Helicopter Recovery Operations]]                             | November 18, 2021  |
| [[News/Rocket Lab demonstrates flexible in-space transportation with new Kick Stage maneuver.md\|Rocket Lab demonstrates flexible in-space transportation with new Kick Stage maneuver]]                                                 | October 30, 2020   |
| [[News/Rocket Lab Successfully Launches 15th Mission, Deploys Satellites for Planet, Canon Electronics Inc..md\|Rocket Lab Successfully Launches 15th Mission, Deploys Satellites for Planet, Canon Electronics Inc.]]                   | October 29, 2020   |
| [[News/Rocket Lab To Launch Commercial Earth-Imaging Rideshare Mission For Planet, Canon Electronics.md\|Rocket Lab To Launch Commercial Earth-Imaging Rideshare Mission For Planet, Canon Electronics]]                                 | September 21, 2020 |
| [[News/Rocket Lab to Resume Electron Launches in August.md\|Rocket Lab to Resume Electron Launches in August]]                                                                                                                           | July 31, 2020      |
| [[News/Rocket Lab Mission Fails to Reach Orbit.md\|Rocket Lab Mission Fails to Reach Orbit]]                                                                                                                                             | July 04, 2020      |
| [[News/Rocket Lab to Demonstrate Fastest Launch Turnaround to Date.md\|Rocket Lab to Demonstrate Fastest Launch Turnaround to Date]]                                                                                                     | June 15, 2020      |
| [[News/Rocket Lab Debuts Fully Autonomous Flight Termination System.md\|Rocket Lab Debuts Fully Autonomous Flight Termination System]]                                                                                                   | December 09, 2019  |
| [[News/Rocket Lab launches milestone tenth mission, completes major success for reusable rocket program.md\|Rocket Lab launches milestone tenth mission, completes major success for reusable rocket program]]                           | December 06, 2019  |
| [[News/Next Generation Electron Booster on the Pad  for Rocket Lab’s 10th Mission.md\|Next Generation Electron Booster on the Pad  for Rocket Lab’s 10th Mission]]                                                                       | November 05, 2019  |
| [[News/Rocket Lab successfully launches seventh Electron mission, deploys seven satellites to orbit.md\|Rocket Lab successfully launches seventh Electron mission, deploys seven satellites to orbit]]                                   | June 29, 2019      |
| [[News/Rocket Lab to launch rideshare mission for Spaceflight.md\|Rocket Lab to launch rideshare mission for Spaceflight]]                                                                                                               | May 10, 2019       |
| [[News/Rocket Lab confirms three launches with Spaceflight, including missions for Canon Electronics and BlackSky.md\|Rocket Lab confirms three launches with Spaceflight, including missions for Canon Electronics and BlackSky]]       | June 11, 2018      |
| [[News/Rocket Lab Signs Launch Contract with Spaceflight   Rocket Lab.md\|Rocket Lab Signs Launch Contract with Spaceflight   Rocket Lab]]                                                                                               | May 18, 2017       |

%%DATAVIEW_PUBLISHER: end %%

## ✏️ Notes

- Acquired by [[Firefly Aerospace]] June 8 2023. [Source](https://www.satellitetoday.com/finance/2023/06/12/firefly-aerospace-to-acquire-rideshare-provider-spaceflight/)