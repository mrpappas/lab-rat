---

name: BlackSky
website: https://www.blacksky.com/
---

**Name:** BlackSky
**Website:** https://www.blacksky.com/

>[!summary]
BlackSky is a **U.S.-based geospatial intelligence company** that specializes in providing **real-time Earth observation data** and **analytics**. The company operates a constellation of **low Earth orbit (LEO) satellites** designed to capture high-resolution imagery multiple times per day. BlackSky integrates satellite imagery with **artificial intelligence (AI)** and other data sources to deliver **actionable insights** for applications such as **defense, disaster response, supply chain monitoring, and infrastructure management**. BlackSky's subscription-based platform offers near real-time access to **global monitoring** capabilities, enabling rapid decision-making for commercial and government clients.

## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[BlackSky]])
sort launch_date desc
```
%%

| File                                                                                | Date             | Location                                              | Vehicle                          | Orbit & Mass                        | Outcome   |
| ----------------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ----------------------------------- | --------- |
| [[Launch/Launches/065 - Full Stream Ahead.md\|065 - Full Stream Ahead]]             | 2025-05-28 01:30 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 470km \| 59° \| 138 kg              | ⌛ Pending |
| [[Launch/Launches/060 - Fasten Your Space Belts.md\|060 - Fasten Your Space Belts]] | 2025-02-19 12:17 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 470km \| 59° \| 138 kg              | ✅ Success |
| [[Launch/Launches/035 - The Beat Goes On.md\|035 - The Beat Goes On]]               | 2023-03-24 09:14 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 450 km \| 42° \| 120 kg             | ✅ Success |
| [[Launch/Launches/025 - Without Mission A Beat.md\|025 - Without Mission A Beat]]   | 2022-04-02 12:41 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 430 km \| 53° \| 120 kg             | ✅ Success |
| [[Launch/Launches/023 - A Data With Destiny.md\|023 - A Data With Destiny]]         | 2021-12-09 00:02 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 430 km \| 42° \| 120 kg             | ✅ Success |
| [[Launch/Launches/022 - Love At First Insight.md\|022 - Love At First Insight]]     | 2021-11-18 01:38 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 430 km \| 42° \| 120 kg             | ✅ Success |
| [[Launch/Launches/020 - Running Out Of Toes.md\|020 - Running Out Of Toes]]         | 2021-05-15 11:11 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 430 km \| 50° \| 120 kg             | ❌ Failure |
| [[Launch/Launches/019 - They Go Up So Fast.md\|019 - They Go Up So Fast]]           | 2021-03-22 22:30 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 450 km and 550 km \| 45° \| Unknown | ✅ Success |
| [[Launch/Launches/008 - Look Ma, No Hands.md\|008 - Look Ma, No Hands]]             | 2019-08-19 12:12 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 510 km \| 94.8° \| 80 kg            | ✅ Success |
| [[Launch/Launches/007 - Make it Rain.md\|007 - Make it Rain]]                       | 2019-06-29 04:30 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 450 km \| 45° \| 80 kg              | ✅ Success |

%%DATAVIEW_PUBLISHER: end %%

## 🛰️ Space Systems

### BlackSky Gen-2

https://space.skyrocket.de/doc_sdat/blacksky-global.htm

The satellites feature the SpaceView-24 imaging system built by Harris Corp.'s Exelis with an aperture of 24 cm It has a ground resolution of 0.9 - 1.1 m from an orbital height of 500 km. They have a onboard propulsion for a 3 year orbital life. The satellites are built by Spaceflight Services based on their SCOUT bus.

![[Pasted image 20250303200134.jpg]]

### BlackSky Gen-3

🔗 https://www.blacksky.com/gen-3/
[🔧 Data Sheet](https://www.blacksky.com/wp-content/uploads/2025/02/BlackSky-Gen-3-Data-Sheet.pdf)

BlackSky's latest generation Earth Observation satellite featuring 35 cm resolution, multispectral capabilities, AI-enabled analytics, low-latency communications, and a highly agile attitude control system. 

![[Pasted image 20250303195116.png]]


| Specification                     | Value                                                                                                                                                                                     |
| --------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tasking to collection             | < 10 hours                                                                                                                                                                                |
| Collection to delivery            | < 90 minutes                                                                                                                                                                              |
| Automated object detection        | Vehicles: Truck, semi-truck, pickup, jeep, van, private car,<br>bus, construction vehicle<br>Vessels: Small vessel, tug, container, warship, patrol,<br>submarine, merchant vessel, other |
| NIIRS image quality class         | Visible: NIIRS 5+<br>Shortwave infrared: NIIRS 3+                                                                                                                                         |
| Best ground sample distance (GSD) | Visible: 35 cm<br>Shortwave infrared: 1.2 m                                                                                                                                               |
| Minimum scene size                | Visible: 18 km² (3.7 km x 4.9 km)<br>Shortwave infrared: 1.8 km² (1.2 km x 1.5 km)                                                                                                        |
| Spectral bands                    | RGB, panchromatic, shortwave infrared                                                                                                                                                     |
| Geolocation accuracy              | < 20 m CE90<br>< 10 m CE90 in Australia, United States                                                                                                                                    |
| Orbital altitude                  | 450 km low-earth orbit (LEO)                                                                                                                                                              |
| Orbital inclination               | Mid-inclined orbit (MIO)<br>Capable of sun-synchronous orbit (SSO)                                                                                                                        |
| Communications                    | X-band primary downlink<br>S-band primary uplink<br>UHF backup uplink and downlink                                                                                                        |
| Design life                       | 5+ years                                                                                                                                                                                  |


## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[BlackSky]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                                                                   | Published         |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------- |
| [[News/Rocket Lab Schedules Next Launch in Series of Multiple Missions for BlackSky.md\|Rocket Lab Schedules Next Launch in Series of Multiple Missions for BlackSky]]                                                                                                                                 | May 22, 2025      |
| [[News/Rocket Lab Successfully Launches 60th Electron, First of Multiple New Missions for BlackSky.md\|Rocket Lab Successfully Launches 60th Electron, First of Multiple New Missions for BlackSky]]                                                                                                   | February 18, 2025 |
| [[News/Rocket Lab Schedules Launch for First of Multiple Missions for BlackSky.md\|Rocket Lab Schedules Launch for First of Multiple Missions for BlackSky]]                                                                                                                                           | February 10, 2025 |
| [[News/BlackSky Signs New Block Buy for Five Rocket Lab Launches.md\|BlackSky Signs New Block Buy for Five Rocket Lab Launches]]                                                                                                                                                                       | August 08, 2023   |
| [[News/Rocket Lab Successfully Launches 35th Electron Seven Days After Previous Launch, Sets New Company Record for Fastest Launch Turnaround.md\|Rocket Lab Successfully Launches 35th Electron Seven Days After Previous Launch, Sets New Company Record for Fastest Launch Turnaround]]             | March 24, 2023    |
| [[News/Rocket Lab to Launch Pair of Satellites for BlackSky from New Zealand Just Days After Successful Launch from Virginia.md\|Rocket Lab to Launch Pair of Satellites for BlackSky from New Zealand Just Days After Successful Launch from Virginia]]                                               | March 17, 2023    |
| [[News/Rocket Lab Plans Two Launches Days Apart From Two Continents.md\|Rocket Lab Plans Two Launches Days Apart From Two Continents]]                                                                                                                                                                 | February 28, 2023 |
| [[News/Rocket Lab Successfully Launches 112th Satellite to Orbit.md\|Rocket Lab Successfully Launches 112th Satellite to Orbit]]                                                                                                                                                                       | April 03, 2022    |
| [[News/Rocket Lab Confirms Next Electron Launch Window Opens for BlackSky April 1, 2022 UTC; Provides Update on Effect to Prior Q1 Revenue Guidance.md\|Rocket Lab Confirms Next Electron Launch Window Opens for BlackSky April 1, 2022 UTC; Provides Update on Effect to Prior Q1 Revenue Guidance]] | March 24, 2022    |
| [[News/Rocket Lab Readies First 2022 Electron Launch, BlackSky Adds Another Mission to Manifest.md\|Rocket Lab Readies First 2022 Electron Launch, BlackSky Adds Another Mission to Manifest]]                                                                                                         | January 18, 2022  |
| [[News/Rocket Lab Launches 109th Satellite to Orbit.md\|Rocket Lab Launches 109th Satellite to Orbit]]                                                                                                                                                                                                 | December 09, 2021 |
| [[News/Rocket Lab Confirms Helicopter Capture Attempt  For Next Recovery Mission.md\|Rocket Lab Confirms Helicopter Capture Attempt  For Next Recovery Mission]]                                                                                                                                       | November 23, 2021 |
| [[News/Rocket Lab Launches 107th Satellite To Orbit, Successfully Tests Helicopter Recovery Operations.md\|Rocket Lab Launches 107th Satellite To Orbit, Successfully Tests Helicopter Recovery Operations]]                                                                                           | November 18, 2021 |
| [[News/Rocket Lab to Recover Electron Rocket, Introduce Helicopter Operations During Next Launch.md\|Rocket Lab to Recover Electron Rocket, Introduce Helicopter Operations During Next Launch]]                                                                                                       | October 19, 2021  |
| [[News/Rocket Lab Launch Operations Underway For Two BlackSky Missions in November.md\|Rocket Lab Launch Operations Underway For Two BlackSky Missions in November]]                                                                                                                                   | October 11, 2021  |
| [[News/Rocket Lab to Launch Three Back-To-Back Missions for BlackSky from late August.md\|Rocket Lab to Launch Three Back-To-Back Missions for BlackSky from late August]]                                                                                                                             | August 10, 2021   |
| [[News/Rocket Lab Completes Anomaly Review, Next Mission on the Pad in July.md\|Rocket Lab Completes Anomaly Review, Next Mission on the Pad in July]]                                                                                                                                                 | July 19, 2021     |
| [[News/The Federal Aviation Administration Approves Rocket Lab To Resume Launches.md\|The Federal Aviation Administration Approves Rocket Lab To Resume Launches]]                                                                                                                                     | June 02, 2021     |
| [[News/Rocket Lab Experiences Anomaly During Launch.md\|Rocket Lab Experiences Anomaly During Launch]]                                                                                                                                                                                                 | May 17, 2021      |
| [[News/Rocket Lab Progresses Flight Review, Recovers First Stage Following Successful Ocean Splashdown.md\|Rocket Lab Progresses Flight Review, Recovers First Stage Following Successful Ocean Splashdown]]                                                                                           | May 17, 2021      |
| [[News/Rocket Lab to Recover Electron Booster on Next Mission.md\|Rocket Lab to Recover Electron Booster on Next Mission]]                                                                                                                                                                             | April 08, 2021    |
| [[News/Rocket Lab Inks Deal to Launch Five Missions for BlackSky Constellation.md\|Rocket Lab Inks Deal to Launch Five Missions for BlackSky Constellation]]                                                                                                                                           | March 25, 2021    |
| [[News/Rocket Lab Successfully Launches 19th Electron, Deploys 100th Satellite.md\|Rocket Lab Successfully Launches 19th Electron, Deploys 100th Satellite]]                                                                                                                                           | March 23, 2021    |
| [[News/Rocket Lab’s Next Mission to Launch 100th Satellite and Deploy Next-Generation Photon Spacecraft in Preparation for Moon Mission.md\|Rocket Lab’s Next Mission to Launch 100th Satellite and Deploy Next-Generation Photon Spacecraft in Preparation for Moon Mission]]                         | February 09, 2021 |
| [[News/Rocket Lab successfully launches eighth Electron mission,  takes next step in recovery and reuse for future flights.md\|Rocket Lab successfully launches eighth Electron mission,  takes next step in recovery and reuse for future flights]]                                                   | August 20, 2019   |
| [[News/Rocket Lab’s Next Mission Focused On Building Constellations And Enabling R&D.md\|Rocket Lab’s Next Mission Focused On Building Constellations And Enabling R&D]]                                                                                                                               | July 22, 2019     |
| [[News/Rocket Lab successfully launches seventh Electron mission, deploys seven satellites to orbit.md\|Rocket Lab successfully launches seventh Electron mission, deploys seven satellites to orbit]]                                                                                                 | June 29, 2019     |
| [[News/Rocket Lab to launch rideshare mission for Spaceflight.md\|Rocket Lab to launch rideshare mission for Spaceflight]]                                                                                                                                                                             | May 10, 2019      |
| [[News/Rocket Lab confirms three launches with Spaceflight, including missions for Canon Electronics and BlackSky.md\|Rocket Lab confirms three launches with Spaceflight, including missions for Canon Electronics and BlackSky]]                                                                     | June 11, 2018     |

%%DATAVIEW_PUBLISHER: end %%