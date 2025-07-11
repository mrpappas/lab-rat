---

name: Astroscale-Japan
website: https://astroscale.com/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> Astroscale-Japan

**Website:** https://astroscale.com/

>[!summary]
Astroscale-Japan is a subsidiary of Astroscale Holdings, a company dedicated to addressing space sustainability by providing on-orbit servicing solutions. Focused on debris removal, satellite life extension, and end-of-life services, Astroscale develops technologies to clean up existing space debris and ensure responsible satellite deorbiting. The company’s missions, such as *ELSA-d* (End-of-Life Services by Astroscale-demonstration) and *ADRAS-J* (Active Debris Removal by Astroscale-Japan), demonstrate capabilities in docking with, capturing, and deorbiting defunct satellites and debris to maintain a sustainable space environment.

## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[Astroscale-Japan]])
sort launch_date desc
```
%%

| File                                                                          | Date             | Location                                              | Vehicle                          | Orbit & Mass            | Outcome |
| ----------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ----------------------- | ------- |
| [[Launch/Launches/044 - On Closer Inspection.md\|044 - On Closer Inspection]] | 2024-02-19 14:52 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 600 km \| 98° \| 150 kg | ✅       |

%%DATAVIEW_PUBLISHER: end %%


## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[Astroscale-Japan]])
sort published desc
```
%%

| File                                                                                                                                                                                                         | Published          |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------ |
| [[News/Rocket Lab Successfully Launches Mission Designed to Investigate Removing Space Junk from Orbit.md\|Rocket Lab Successfully Launches Mission Designed to Investigate Removing Space Junk from Orbit]] | February 19, 2024  |
| [[News/Rocket Lab Sets Launch Window for Astroscale Orbital Debris Inspection Demonstration Mission.md\|Rocket Lab Sets Launch Window for Astroscale Orbital Debris Inspection Demonstration Mission]]       | February 07, 2024  |
| [[News/Rocket Lab Wins Contract to Launch Orbital Debris Removal Demonstration Mission for Astroscale.md\|Rocket Lab Wins Contract to Launch Orbital Debris Removal Demonstration Mission for Astroscale]]   | September 21, 2021 |

%%DATAVIEW_PUBLISHER: end %%

## ✏️ Notes

-  https://arstechnica.com/space/2024/08/there-are-2000-plus-dead-rockets-in-orbit-heres-a-rare-view-of-one-of-them/