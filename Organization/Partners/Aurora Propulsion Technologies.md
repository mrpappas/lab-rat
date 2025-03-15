---

name: Aurora Propulsion Technologies
website: https://aurorapt.space/
---

**Name:** Aurora Propulsion Technologies
**Website:** https://aurorapt.space/

>[!summary]
Aurora Propulsion Technologies is a Finnish company specializing in spacecraft propulsion and satellite deorbiting solutions. Focused on sustainable space operations, the company develops small-scale electric propulsion systems and tools to enable satellite maneuvering and controlled deorbiting at the end of mission lifecycles. Aurora’s products, such as water-based resistojet thrusters and plasma brake technologies, are designed to support small satellite missions and reduce space debris.

## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[Aurora Propulsion Technologies]])
sort launch_date desc
```
%%

| File                                                                          | Date             | Location                                              | Vehicle                          | Orbit & Mass             | Outcome   |
| ----------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ------------------------ | --------- |
| [[Launch/Launches/026 'There And Back Again'.md\|026 'There And Back Again']] | 2022-05-02 22:49 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 520 km \| 94° \| Unknown | ✅ Success |

%%DATAVIEW_PUBLISHER: end %%


## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[Aurora Propulsion Technologies]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                     | Published       |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------- |
| [[News/Rocket Lab Successfully Deploys 34 Satellites and Catches Rocket Booster Returning from Space with Helicopter.md\|Rocket Lab Successfully Deploys 34 Satellites and Catches Rocket Booster Returning from Space with Helicopter]] | May 02, 2022    |
| [[News/Rocket Lab to Attempt First Mid-Air Helicopter Capture of the Electron Rocket During Next Mission.md\|Rocket Lab to Attempt First Mid-Air Helicopter Capture of the Electron Rocket During Next Mission]]                         | April 06, 2022  |
| [[News/Rocket Lab to Launch Finnish Satellite Developing Next-Generation Space Junk Removal Technologies.md\|Rocket Lab to Launch Finnish Satellite Developing Next-Generation Space Junk Removal Technologies]]                         | August 16, 2021 |

%%DATAVIEW_PUBLISHER: end %%