---

name: In-Space Missions
website: https://in-space.co.uk/
---

**Name:** In-Space Missions
**Website:** https://in-space.co.uk/

>[!summary]
In-Space Missions is a UK-based company that designs, builds, and operates satellites, specializing in rideshare missions like the Faraday series, which host multiple payloads on a single platform. They offer rapid access to space for technology demonstration, Earth observation, and communication missions. Acquired by [BAE Systems](https://www.baesystems.com/en/home) in 2021, they support commercial, governmental, and research customers.

## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[In-Space Missions]])
sort launch_date desc
```
%%

| File                                                                                  | Date             | Location                                              | Vehicle                          | Orbit & Mass             | Outcome   |
| ------------------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ------------------------ | --------- |
| [[Launch/Launches/013 'Pics Or It Didn't Happen'.md\|013 'Pics Or It Didn't Happen']] | 2020-07-04 21:19 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 500 km \| 97.5° \| 75 kg | ❌ Failure |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[In-Space Missions]])
sort published desc
```
%%

| File                                                                                                                                 | Published     |
| ------------------------------------------------------------------------------------------------------------------------------------ | ------------- |
| [[News/Rocket Lab to Resume Electron Launches in August.md\|Rocket Lab to Resume Electron Launches in August]]                       | July 31, 2020 |
| [[News/Rocket Lab Mission Fails to Reach Orbit.md\|Rocket Lab Mission Fails to Reach Orbit]]                                         | July 04, 2020 |
| [[News/Rocket Lab to Demonstrate Fastest Launch Turnaround to Date.md\|Rocket Lab to Demonstrate Fastest Launch Turnaround to Date]] | June 15, 2020 |

%%DATAVIEW_PUBLISHER: end %%