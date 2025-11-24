[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Hardware]] <span style="color: LightSlateGray">></span> HASTE
## Summary 

Hypersonic Accelerator Suborbital Test Electron (HASTE) is a modified suborbital variant of orbital [[Electron]], specifically designed to provide high-cadence, affordable test opportunities for the field of hypersonic technology (flight at speeds of Mach 5, or five times the speed of sound, or greater). The primary purpose of these suborbital flights is to test advanced hardware, such as air-breathing engines, thermal protection systems, and guidance components for the development of U.S. military hypersonic weapons, including cruise missiles and glide vehicles.

Because HASTE is liquid-fueled, it offers a major advantage over older solid-fueled test rockets, which only provide brief moments of relevant test time. HASTE can have its engine power precisely throttled and the engine nozzle actively steered. This flexibility allows engineers to custom-design complex flight paths such as a direct injection trajectory (continuous burn), a controlled glide, or a steep re-entry, all tailored to simulate a real weapon’s flight profile. HASTE can deliver payloads weighing up to 1,543 lbs (700 kg) into these custom high-speed paths, preparing them for the intense heat of atmospheric re-entry. 

🚀 https://www.rocketlabusa.com/launch/haste/

![[Pasted image 20250119002432.png]]

| Specification                   | Value                  |
| ------------------------------- | ---------------------- |
| **Payload Mass**                | ~700kg / 1540 lbs      |
| **Payload Separation Velocity** | 3 km/sec to 7.5 km/sec |
| **Payload Separation Altitude** | 80 km+                 |
## Payload Configurations

### Air-Breathing Applications
This configuration supports payloads such as scramjet or ramjet engines that operate by ingesting atmospheric air during flight. HASTE can deploy these payloads at specific altitudes and velocities to facilitate testing of air-breathing propulsion systems under realistic flight conditions.

### Ballistic Re-Entry Applications
In this setup, HASTE delivers payloads on a suborbital trajectory that re-enters the Earth's atmosphere following a ballistic path. This is ideal for testing re-entry vehicles, heat shields, and other technologies that must withstand the high temperatures and pressures encountered during atmospheric re-entry.

### Boost Glide Applications
This configuration involves deploying payloads that glide unpowered after an initial boost phase, covering long distances at hypersonic speeds within the atmosphere. It's particularly useful for testing hypersonic glide vehicles and related technologies that require sustained high-speed atmospheric flight.

### Space-Based Applications
HASTE can also accommodate payloads intended for space-based experiments or technology demonstrations. While primarily a suborbital vehicle, its flexible design allows it to support missions that require brief exposure to space environments, enabling testing of space technologies without the need for full orbital insertion.

## 🚀 Launches
%%DATAVIEW_PUBLISHER: start
```
table launch_date, outcome
from "Launch/Launches"
where contains(vehicle, [[HASTE]])
sort launch_date desc
```
%%

| File                                                                  | launch_date          | outcome |
| --------------------------------------------------------------------- | -------------------- | ------- |
| [[Launch/Launches/075 - Prometheus Run.md\|075 - Prometheus Run]]     | 2025-11-18 13:00 UTC | ✅       |
| [[Launch/Launches/072 - JUSTIN.md\|072 - JUSTIN]]                     | 2025-09-30 20:28     | ✅       |
| [[Launch/Launches/071 - JENNA.md\|071 - JENNA]]                       | 2025-09-22 07:45     | ✅       |
| [[Launch/Launches/057 - Stonehenge.md\|057 - Stonehenge]]             | 2024-12-13 00:00     | ✅       |
| [[Launch/Launches/055 - HASTE A La Vista.md\|055 - HASTE A La Vista]] | 2024-11-24 06:00     | ✅       |
| [[Launch/Launches/038 - Scout's Arrow.md\|038 - Scout's Arrow]]       | 2023-06-18 01:24     | ✅       |

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
| [[News/Rocket Lab Successfully Launches HASTE Mission for Defense Innovation Unit, Missile Defense Agency.md\|Rocket Lab Successfully Launches HASTE Mission for Defense Innovation Unit, Missile Defense Agency]]                                                                 | Rocket Lab Successfully Launches HASTE Mission for Defense Innovation Unit, Missile Defense Agency                                 | November 18, 2025  |
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
