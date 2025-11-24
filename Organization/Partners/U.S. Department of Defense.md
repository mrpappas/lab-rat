---

name: U.S. Department of Defense
website: https://www.defense.gov/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> U.S. Department of Defense
## Partner Details

**Website:** https://www.defense.gov/

The U.S. Department of Defense (DoD) is the federal agency responsible for coordinating and supervising all agencies and functions related to national security and the United States Armed Forces. Headquartered at the Pentagon, the DoD oversees the Army, Navy, Air Force, Marine Corps, and Space Force. In recent years, the DoD has intensified its focus on space as a critical domain for national security. The establishment of the U.S. Space Force in December 2019 as a separate branch under the DoD underscores this emphasis. The DoD develops and operates space-based assets for communication, navigation (including GPS), missile warning, reconnaissance, and weather monitoring. Through agencies like the Space Development Agency (SDA) and collaborations with entities such as NASA and commercial partners, the DoD advances technologies in space situational awareness, satellite defense, and maintains the United States' strategic advantages in space.

## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[U.S. Department of Defense]])
sort launch_date desc
```
%%

| File                                                                  | Date             | Location                                               | Vehicle                    | Orbit & Mass          | Outcome |
| --------------------------------------------------------------------- | ---------------- | ------------------------------------------------------ | -------------------------- | --------------------- | ------- |
| [[Launch/Launches/055 - HASTE A La Vista.md\|055 - HASTE A La Vista]] | 2024-11-24 06:00 | [[Locations/Launch Complex 2.md#Launch Pad 0C\|LC2-0]] | [[Launch/HASTE.md\|HASTE]] | Suborbital \| unknown | ✅       |

%%DATAVIEW_PUBLISHER: end %%

## News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[U.S. Department of Defense]])
sort published desc
```
%%

| File                                                                                                                                                                                                                       | Published         |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/Mission Success for Rocket Lab’s Latest Suborbital Hypersonic Launch.md\|Mission Success for Rocket Lab’s Latest Suborbital Hypersonic Launch]]                                                                     | December 09, 2024 |
| [[News/Rocket Lab Successfully Launches Two Missions in Less Than 24 Hours.md\|Rocket Lab Successfully Launches Two Missions in Less Than 24 Hours]]                                                                       | November 25, 2024 |
| [[News/Rocket Lab Adds New HASTE Launch from Virginia for the Department of Defense’s Defense Innovation Unit.md\|Rocket Lab Adds New HASTE Launch from Virginia for the Department of Defense’s Defense Innovation Unit]] | November 08, 2023 |

%%DATAVIEW_PUBLISHER: end %%