---
name: Unseenlabs
website: https://unseenlabs.space/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> Unseenlabs

**Website:** https://unseenlabs.space/

**Unseenlabs** is a French company specializing in **space-based radio frequency (RF) detection and geolocation**. Leveraging its constellation of **nanosatellites** in low Earth orbit (LEO), Unseenlabs provides **maritime surveillance** services by detecting and geolocating RF signals emitted by ships, even those operating with their **Automatic Identification System (AIS) turned off**. 

The company's technology is particularly valuable for **tracking illegal activities**, such as smuggling, piracy, and unregulated fishing, offering critical insights for governments, defense organizations, and maritime operators. Unseenlabs' services support **global maritime security** with high-precision, real-time data, reinforcing transparency and safety across the world’s oceans.

![[Pasted image 20251211014239.jpg]]
##  Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[]])
sort launch_date desc
```
%%

| File                                                                          | Date             | Location                                              | Vehicle                                            | Orbit & Mass              | Outcome |
| ----------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------------------------- | ------------------------- | ------- |
| [[Launch/Launches/026 - There And Back Again.md\|026 - There And Back Again]] | 2022-05-02 22:49 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Hardware/Launch Vehicles/Electron.md\|Electron]] | 520 km \| 94° \| Unknown  | ✅       |
| [[Launch/Launches/016 - Return to Sender.md\|016 - Return to Sender]]         | 2020-11-20 02:20 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Hardware/Launch Vehicles/Electron.md\|Electron]] | 500 km \| 97.3° \| 200 kg | ✅       |
| [[Launch/Launches/008 - Look Ma, No Hands.md\|008 - Look Ma, No Hands]]       | 2019-08-19 12:12 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Hardware/Launch Vehicles/Electron.md\|Electron]] | 510 km \| 94.8° \| 80 kg  | ✅       |

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

| File                                                                                                                                                                                                                                                 | Published         |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/Rocket Lab Successfully Deploys 34 Satellites and Catches Rocket Booster Returning from Space with Helicopter.md\|Rocket Lab Successfully Deploys 34 Satellites and Catches Rocket Booster Returning from Space with Helicopter]]             | May 02, 2022      |
| [[News/Rocket Lab to Attempt First Mid-Air Helicopter Capture of the Electron Rocket During Next Mission.md\|Rocket Lab to Attempt First Mid-Air Helicopter Capture of the Electron Rocket During Next Mission]]                                     | April 06, 2022    |
| [[News/How to bring a rocket back from space.md\|How to bring a rocket back from space]]                                                                                                                                                             | November 30, 2020 |
| [[News/Rocket Lab Launches 16th Mission, Completes Booster Recovery.md\|Rocket Lab Launches 16th Mission, Completes Booster Recovery]]                                                                                                               | November 22, 2020 |
| [[News/Rocket Lab to Attempt First Stage Recovery on Next Mission.md\|Rocket Lab to Attempt First Stage Recovery on Next Mission]]                                                                                                                   | November 05, 2020 |
| [[News/Rocket Lab to Launch Most Diverse Mission Yet.md\|Rocket Lab to Launch Most Diverse Mission Yet]]                                                                                                                                             | November 02, 2020 |
| [[News/Rocket Lab successfully launches eighth Electron mission,  takes next step in recovery and reuse for future flights.md\|Rocket Lab successfully launches eighth Electron mission,  takes next step in recovery and reuse for future flights]] | August 20, 2019   |
| [[News/Rocket Lab’s Next Mission Focused On Building Constellations And Enabling R&D.md\|Rocket Lab’s Next Mission Focused On Building Constellations And Enabling R&D]]                                                                             | July 22, 2019     |

%%DATAVIEW_PUBLISHER: end %%

## Notes

 - On April 29 2024 **Unseen Labs** announced their next-gen satellite constellation, planned to be launched in 2026. This new constellation would expand "its surveillance capabilities to include terrestrial and space environments in addition to maritime". This announcement was made shortly after they secured and €85 Million capital raise. 
   The new fleet would be compromised of 150-kg satellites, which is within [[Electron]]'s payload limitations. 
   **[Source: New Constellation](https://unseenlabs.space/2024/04/29/unseenlabs-announces-next-generation-satellite-constellation-for-2026-to-monitor-sea-land-and-space-environments-from-space/)**
   [**Source: Funding**](https://unseenlabs.space/2024/02/26/unseenlabs-announces-a-record-breaking-fundraising-of-e85-million/)

![[Pasted image 20241216213713.png]]