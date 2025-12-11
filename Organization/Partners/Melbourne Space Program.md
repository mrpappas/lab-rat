---
name: Melbourne Space Program
website: https://www.melbournespace.com.au/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> Melbourne Space Program
## Partner Details

**Website:** https://www.melbournespace.com.au/

The Melbourne Space Program is a non-profit organization based in Melbourne, Australia, focused on student-led satellite development and hands-on space systems education. Their key achievements include the ACRUX-1 CubeSat, launched in June 2019 aboard a Rocket Lab Electron, as a demonstration of satellite design and deployment capabilities. Future missions, such as ACRUX-2, aim to build on this success. The program emphasizes practical training in space engineering and systems development for students and early-career professionals.

![[Pasted image 20251211021537.jpg|300]]

## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[]])
sort launch_date desc
```
%%

| File                                                          | Date             | Location                                              | Vehicle                          | Orbit & Mass           | Outcome |
| ------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ---------------------- | ------- |
| [[Launch/Launches/007 - Make it Rain.md\|007 - Make it Rain]] | 2019-06-29 04:30 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 450 km \| 45° \| 80 kg | ✅       |

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

| File                                                                                                                                                                                                   | Published     |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------- |
| [[News/Rocket Lab successfully launches seventh Electron mission, deploys seven satellites to orbit.md\|Rocket Lab successfully launches seventh Electron mission, deploys seven satellites to orbit]] | June 29, 2019 |
| [[News/Rocket Lab to launch rideshare mission for Spaceflight.md\|Rocket Lab to launch rideshare mission for Spaceflight]]                                                                             | May 10, 2019  |

%%DATAVIEW_PUBLISHER: end %%
## ✏️ Notes

- Future ACRUX-2 project: https://www.melbournespace.com.au/projects