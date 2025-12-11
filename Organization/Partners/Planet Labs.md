---

name: Planet Labs
website: https://www.planet.com/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> Planet Labs

**Website:** https://www.planet.com/

Planet Labs is a leading Earth observation company that designs, builds, and operates the world’s largest fleet of imaging satellites. Planet's constellation of Dove, SuperDove, and SkySat satellites captures daily, high-resolution imagery of the entire Earth. This continuous, real-time data stream enables governments, businesses, and researchers to monitor changes, track trends, and make data-driven decisions in areas such as agriculture, forestry, climate monitoring, urban development, and disaster response. 

![[Pasted image 20251211020914.png]]

## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[]])
sort launch_date desc
```
%%

| File                                                                                  | Date             | Location                                              | Vehicle                          | Orbit & Mass             | Outcome |
| ------------------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ------------------------ | ------- |
| [[Launch/Launches/015 - In Focus.md\|015 - In Focus]]                                 | 2020-10-28 21:21 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 500 km \| 97.5° \| 72 kg | ✅       |
| [[Launch/Launches/013 - Pics Or It Didn't Happen.md\|013 - Pics Or It Didn't Happen]] | 2020-07-04 21:19 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 500 km \| 97.5° \| 75 kg | ❌       |
| [[Launch/Launches/002 - Still Testing.md\|002 - Still Testing]]                       | 2018-01-21 02:43 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 400 km \| 82.9° \| 13 kg | ✅       |

%%DATAVIEW_PUBLISHER: end %%

## News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[]])
sort published desc
```
%%

| File                                                                                                                                                                                                                   | Published          |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ |
| [[News/Rocket Lab demonstrates flexible in-space transportation with new Kick Stage maneuver.md\|Rocket Lab demonstrates flexible in-space transportation with new Kick Stage maneuver]]                               | October 30, 2020   |
| [[News/Rocket Lab Successfully Launches 15th Mission, Deploys Satellites for Planet, Canon Electronics Inc..md\|Rocket Lab Successfully Launches 15th Mission, Deploys Satellites for Planet, Canon Electronics Inc.]] | October 29, 2020   |
| [[News/Rocket Lab To Launch Commercial Earth-Imaging Rideshare Mission For Planet, Canon Electronics.md\|Rocket Lab To Launch Commercial Earth-Imaging Rideshare Mission For Planet, Canon Electronics]]               | September 21, 2020 |
| [[News/Rocket Lab to Resume Electron Launches in August.md\|Rocket Lab to Resume Electron Launches in August]]                                                                                                         | July 31, 2020      |
| [[News/Rocket Lab Mission Fails to Reach Orbit.md\|Rocket Lab Mission Fails to Reach Orbit]]                                                                                                                           | July 04, 2020      |
| [[News/Rocket Lab to Demonstrate Fastest Launch Turnaround to Date.md\|Rocket Lab to Demonstrate Fastest Launch Turnaround to Date]]                                                                                   | June 15, 2020      |
| [[News/Rocket Lab successfully circularizes orbit with new Electron kick stage.md\|Rocket Lab successfully circularizes orbit with new Electron kick stage]]                                                           | January 23, 2018   |
| [[News/Rocket Lab successfully reaches orbit and deploys payloads.md\|Rocket Lab successfully reaches orbit and deploys payloads]]                                                                                     | January 21, 2018   |
| [[News/Rocket Lab to open ‘Still Testing’ launch window on January 20.md\|Rocket Lab to open ‘Still Testing’ launch window on January 20]]                                                                             | January 12, 2018   |
| [[News/Rocket Lab delays ‘Still Testing’ launch attempt.md\|Rocket Lab delays ‘Still Testing’ launch attempt]]                                                                                                         | December 16, 2017  |
| [[News/Rocket Lab completes analysis of Still Testing launch abort.md\|Rocket Lab completes analysis of Still Testing launch abort]]                                                                                   | December 13, 2017  |
| [[News/Still Testing launch window begins.md\|Still Testing launch window begins]]                                                                                                                                     | December 11, 2017  |
| [[News/'Still Testing' Press Kit.md\|'Still Testing' Press Kit]]                                                                                                                                                       | November 30, 2017  |
| [[News/Rocket Lab Still Testing launch window announced.md\|Rocket Lab Still Testing launch window announced]]                                                                                                         | November 30, 2017  |
| [[News/Rocket Lab to fly Planet and Spire satellites on second test flight.md\|Rocket Lab to fly Planet and Spire satellites on second test flight]]                                                                   | November 22, 2017  |
| [[News/Rocket Lab and Planet Sign Launch Services Agreement.md\|Rocket Lab and Planet Sign Launch Services Agreement]]                                                                                                 | August 18, 2016    |

%%DATAVIEW_PUBLISHER: end %%