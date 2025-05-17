>[!summary]
Hypersonic Accelerator Suborbital Test Electron (HASTE) is a suborbital testbed launch vehicle derived from the Electron orbital rocket. HASTE provides flight test opportunities for hypersonic and suborbital system technology development. It successfully launched its first mission "Scout's Arrow" on 18 June 2023, for Leidos.
>
HASTE has a payload capacity of 700 kg (1,500 lb), double that of Electron. It can deploy payloads from 80 km (50 mi) altitude and higher. In 2024, two HASTE launches were planned. As of November 2023 Rocket Lab had contracted for at least six HASTE missions.
>
> 🚀 https://www.rocketlabusa.com/launch/haste/
>🔗 https://en.wikipedia.org/wiki/Rocket_Lab#HASTE_suborbital_rocket

**Payload Mass**: ~700kg / 1540 lbs
**Payload Separation Velocity**: 3 km/sec to 7.5 km/sec
**Payload Separation Altitude**: 80 km+
## 📡 Payload Configurations

### Air-Breathing Applications
This configuration supports payloads such as scramjet or ramjet engines that operate by ingesting atmospheric air during flight. HASTE can deploy these payloads at specific altitudes and velocities to facilitate testing of air-breathing propulsion systems under realistic flight conditions.

### Ballistic Re-Entry Applications
In this setup, HASTE delivers payloads on a suborbital trajectory that re-enters the Earth's atmosphere following a ballistic path. This is ideal for testing re-entry vehicles, heat shields, and other technologies that must withstand the high temperatures and pressures encountered during atmospheric re-entry.

### Boost Glide Applications
This configuration involves deploying payloads that glide unpowered after an initial boost phase, covering long distances at hypersonic speeds within the atmosphere. It's particularly useful for testing hypersonic glide vehicles and related technologies that require sustained high-speed atmospheric flight.

### Space-Based Applications
HASTE can also accommodate payloads intended for space-based experiments or technology demonstrations. While primarily a suborbital vehicle, its flexible design allows it to support missions that require brief exposure to space environments, enabling testing of space technologies without the need for full orbital insertion.

![[Pasted image 20250119002432.png]]

## 🚀 Launches
%%DATAVIEW_PUBLISHER: start
```
table launch_date, outcome
from "Launch/Launches"
where contains(vehicle, [[HASTE]])
sort launch_date desc
```
%%

| File                                                                  | launch_date      | outcome   |
| --------------------------------------------------------------------- | ---------------- | --------- |
| [[Launch/Launches/057 - Stonehenge.md\|057 - Stonehenge]]             | 2024-12-13 00:00 | ✅ Success |
| [[Launch/Launches/055 - HASTE A La Vista.md\|055 - HASTE A La Vista]] | 2024-11-24 06:00 | ✅ Success |
| [[Launch/Launches/038 - Scout's Arrow.md\|038 - Scout's Arrow]]       | 2023-06-18 01:24 | ✅ Success |

%%DATAVIEW_PUBLISHER: end%%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table title as "Title", published as "Published"
from "News"
where contains(tags, "HASTE")
sort published desc
```
%%

| File                                                                                                                                                                                                                                                                               | Title                                                                                                                              | Published          |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ------------------ |
| [[News/Rocket Lab Awarded New HASTE Launch Contract for the DOD by Kratos.md\|Rocket Lab Awarded New HASTE Launch Contract for the DOD by Kratos]]                                                                                                                                 | Rocket Lab Awarded New HASTE Launch Contract for the DOD by Kratos                                                                 | April 23, 2025     |
| [[News/Rocket Lab Onramped To Multi-Billion Dollar U.S. and U.K. Defense Contracts To Expand Hypersonic Technology Development with HASTE.md\|Rocket Lab Onramped To Multi-Billion Dollar U.S. and U.K. Defense Contracts To Expand Hypersonic Technology Development with HASTE]] | Rocket Lab Onramped To Multi-Billion Dollar U.S. and U.K. Defense Contracts To Expand Hypersonic Technology Development with HASTE | April 14, 2025     |
| [[News/Rocket Lab Selected by Kratos to Deliver Hypersonic Test Launches for DoD with HASTE Rocket.md\|Rocket Lab Selected by Kratos to Deliver Hypersonic Test Launches for DoD with HASTE Rocket]]                                                                               | Rocket Lab Selected by Kratos to Deliver Hypersonic Test Launches for DoD with HASTE Rocket  \| Rocket Lab                         | January 07, 2025   |
| [[News/Mission Success for Rocket Lab’s Latest Suborbital Hypersonic Launch.md\|Mission Success for Rocket Lab’s Latest Suborbital Hypersonic Launch]]                                                                                                                             | Mission Success for Rocket Lab’s Latest Suborbital Hypersonic Launch                                                               | December 09, 2024  |
| [[News/Rocket Lab Successfully Launches Two Missions in Less Than 24 Hours.md\|Rocket Lab Successfully Launches Two Missions in Less Than 24 Hours]]                                                                                                                               | Rocket Lab Successfully Launches Two Missions in Less Than 24 Hours                                                                | November 25, 2024  |
| [[News/Rocket Lab Adds New HASTE Launch from Virginia for the Department of Defense’s Defense Innovation Unit.md\|Rocket Lab Adds New HASTE Launch from Virginia for the Department of Defense’s Defense Innovation Unit]]                                                         | Rocket Lab Adds New HASTE Launch from Virginia for the Department of Defense’s Defense Innovation Unit                             | November 08, 2023  |
| [[News/Rocket Lab Signs Deal with Leidos to Launch Four HASTE Missions.md\|Rocket Lab Signs Deal with Leidos to Launch Four HASTE Missions]]                                                                                                                                       | Rocket Lab Signs Deal with Leidos to Launch Four HASTE Missions                                                                    | September 12, 2023 |
| [[News/Rocket Lab Inks New Deal to Launch HASTE Mission from Virginia.md\|Rocket Lab Inks New Deal to Launch HASTE Mission from Virginia]]                                                                                                                                         | Rocket Lab Inks New Deal to Launch HASTE Mission from Virginia                                                                     | August 08, 2023    |
| [[News/Rocket Lab Debuts HASTE Rocket with First Successful Suborbital Launch from Virginia.md\|Rocket Lab Debuts HASTE Rocket with First Successful Suborbital Launch from Virginia]]                                                                                             | Rocket Lab Debuts HASTE Rocket with First Successful Suborbital Launch from Virginia                                               | June 17, 2023      |
| [[News/Rocket Lab Introduces Suborbital Testbed Rocket, Selected for Hypersonic Test Flights.md\|Rocket Lab Introduces Suborbital Testbed Rocket, Selected for Hypersonic Test Flights]]                                                                                           | Rocket Lab Introduces Suborbital Testbed Rocket, Selected for Hypersonic Test Flights                                              | April 17, 2023     |

%%DATAVIEW_PUBLISHER: end%%
