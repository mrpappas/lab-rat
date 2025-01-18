---

name: Astroscale-Japan
website: https://astroscale.com/
---

**Name:** Astroscale-Japan
**Website:** https://astroscale.com/

>[!summary]
Astroscale-Japan is a subsidiary of Astroscale Holdings, a company dedicated to addressing space sustainability by providing on-orbit servicing solutions. Focused on debris removal, satellite life extension, and end-of-life services, Astroscale develops technologies to clean up existing space debris and ensure responsible satellite deorbiting. The company’s missions, such as *ELSA-d* (End-of-Life Services by Astroscale-demonstration) and *ADRAS-J* (Active Debris Removal by Astroscale-Japan), demonstrate capabilities in docking with, capturing, and deorbiting defunct satellites and debris to maintain a sustainable space environment.

## 🚀 Launches
%%DATAVIEW_PUBLISHER: start
```
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Astroscale-Japan]])
sort launch_date desc
```
%%

| File                                                                                                | launch_date      | outcome |
| --------------------------------------------------------------------------------------------------- | ---------------- | ------- |
| [[Launch/Launches/044 'On Closer Inspection' - Electron.md\|044 'On Closer Inspection' - Electron]] | 2024-02-19 14:52 | Success |

%%DATAVIEW_PUBLISHER: end %%


## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Astroscale-Japan]])
sort published desc
```
%%

| File                                                                                                                                                                                                         | Title                                                                                            | Published          |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------ |
| [[News/Rocket Lab Successfully Launches Mission Designed to Investigate Removing Space Junk from Orbit.md\|Rocket Lab Successfully Launches Mission Designed to Investigate Removing Space Junk from Orbit]] | Rocket Lab Successfully Launches Mission Designed to Investigate Removing Space Junk from Orbit  | February 19, 2024  |
| [[News/Rocket Lab Sets Launch Window for Astroscale Orbital Debris Inspection Demonstration Mission.md\|Rocket Lab Sets Launch Window for Astroscale Orbital Debris Inspection Demonstration Mission]]       | Rocket Lab Sets Launch Window for Astroscale Orbital Debris Inspection Demonstration Mission     | February 07, 2024  |
| [[News/Rocket Lab Wins Contract to Launch Orbital Debris Removal Demonstration Mission for Astroscale.md\|Rocket Lab Wins Contract to Launch Orbital Debris Removal Demonstration Mission for Astroscale]]   | Rocket Lab Wins Contract to Launch Orbital Debris Removal Demonstration Mission for Astroscale   | September 21, 2021 |

%%DATAVIEW_PUBLISHER: end %%

## ✏️ Notes

-  https://arstechnica.com/space/2024/08/there-are-2000-plus-dead-rockets-in-orbit-heres-a-rare-view-of-one-of-them/