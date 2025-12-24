---
name: Kinéis
website: https://www.kineis.com/en/spatial-iot-connectivity/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> Kinéis

**Website:** https://www.kineis.com/en/spatial-iot-connectivity/

**Kinéis** is a French company specializing in **[[📦 Payload Types#Internet of Things (IoT)|Internet of Things (IoT)]]** connectivity through satellite technology. The company operates a constellation of nanosatellites designed to provide global IoT connectivity, enabling devices in remote or inaccessible locations to transmit data. 

Born out of the **[Argos system](https://en.wikipedia.org/wiki/Argos_(satellite_system))**, a pioneering satellite-based environmental monitoring service developed in partnership with [[CNES]] (the French Space Agency), Kinéis aims to expand and modernize this system. The company is building a **25-satellite constellation**, which will improve coverage, increase data transmission capabilities, and offer real-time connectivity for industries such as maritime, agriculture, logistics, and environmental monitoring.

![[Pasted image 20251211022813.jpg]]
## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[]])
sort launch_date desc
```
%%

| File                                                                                            | Date             | Location                                              | Vehicle                                                 | Orbit & Mass            | Outcome |
| ----------------------------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | ------------------------------------------------------- | ----------------------- | ------- |
| [[Launch/Launches/062 - High Five.md\|062 - High Five]]                                         | 2025-03-18 01:31 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 643 km \| 97° \| 150 kg | ✅       |
| [[Launch/Launches/059 - IOT 4 You and Me.md\|059 - IOT 4 You and Me]]                           | 2025-02-04 20:43 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 643 km \| 97° \| 150 kg | ✅       |
| [[Launch/Launches/056 - Ice AIS Baby.md\|056 - Ice AIS Baby]]                                   | 2024-11-25 04:55 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 643 km \| 97° \| 150 kg | ✅       |
| [[Launch/Launches/053 - Kinéis Killed the RadIOT Star.md\|053 - Kinéis Killed the RadIOT Star]] | 2024-09-20 23:01 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 643 km \| 98° \| 150 kg | ✅       |
| [[Launch/Launches/050 - No Time Toulouse.md\|050 - No Time Toulouse]]                           | 2024-06-18 18:13 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 635 km \| 98° \| 150 kg | ✅       |

%%DATAVIEW_PUBLISHER: end %%

## Space Systems

### Kinéis IoT

The Kinéis IoT satellites are a constellation of advanced nanosatellites designed to provide seamless global connectivity for [[📦 Payload Types#Internet of Things (IoT)|Internet of Things (IoT)]] devices. Each satellite, weighing approximately 30 kg, operates in low Earth orbit (LEO) at an altitude of around 650 km, enabling low-latency and cost-efficient communication. Leveraging UHF (401-406 MHz) and AIS frequencies, these satellites support two-way communication for IoT applications and real-time maritime tracking. With an expected operational life of 7 years, the Kinéis constellation integrates deployable antennas, high-capacity batteries, and robust onboard systems to ensure reliable data collection and transmission in diverse environments. Applications span environmental monitoring, precision agriculture, logistics, smart cities, and maritime safety, making Kinéis a cornerstone for scalable and efficient satellite-based IoT solutions.

| Specification | Value         |
| ------------- | ------------- |
| Mass          | 30 kg         |
| Size          | 1.40m x 1.60m |
| Propulsion    | No            |
| Mission Life  | 7 Years       |
| Frequency     | UHF, AIS      |

![[Pasted image 20241224231429.jpg]]

## News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                         | Published          |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------ |
| [[News/Successful Rocket Lab Launch Completes Deployment of Full Kinéis Constellation in Less Than a Year.md\|Successful Rocket Lab Launch Completes Deployment of Full Kinéis Constellation in Less Than a Year]]                                           | March 18, 2025     |
| [[News/Rocket Lab Schedules Two Launches Three Days Apart, Upcoming Mission to Deploy Final Satellites in Kinéis Constellation.md\|Rocket Lab Schedules Two Launches Three Days Apart, Upcoming Mission to Deploy Final Satellites in Kinéis Constellation]] | March 10, 2025     |
| [[News/Rocket Lab Launches Next Batch of Satellites for Kinéis Constellation.md\|Rocket Lab Launches Next Batch of Satellites for Kinéis Constellation]]                                                                                                     | February 08, 2025  |
| [[News/Rocket Lab Schedules Next Electron Launch for Constellation Operator Kinéis.md\|Rocket Lab Schedules Next Electron Launch for Constellation Operator Kinéis]]                                                                                         | January 21, 2025   |
| [[News/Rocket Lab Successfully Launches Two Missions in Less Than 24 Hours.md\|Rocket Lab Successfully Launches Two Missions in Less Than 24 Hours]]                                                                                                         | November 25, 2024  |
| [[News/Rocket Lab Schedules Next Launch for Constellation Operator Kinéis.md\|Rocket Lab Schedules Next Launch for Constellation Operator Kinéis]]                                                                                                           | November 12, 2024  |
| [[News/Rocket Lab Successfully Launches 53rd Electron Mission, Deploys Another Five Satellites for Kinéis.md\|Rocket Lab Successfully Launches 53rd Electron Mission, Deploys Another Five Satellites for Kinéis]]                                           | September 21, 2024 |
| [[News/Rocket Lab Sets Launch Date for Second Dedicated Kinéis Mission to Deploy IoT Constellation.md\|Rocket Lab Sets Launch Date for Second Dedicated Kinéis Mission to Deploy IoT Constellation]]                                                         | September 03, 2024 |
| [[News/Rocket Lab Successfully Launches 50th Electron Mission, Deploys Satellites for Kinéis.md\|Rocket Lab Successfully Launches 50th Electron Mission, Deploys Satellites for Kinéis]]                                                                     | June 21, 2024      |
| [[News/Rocket Lab Sets Launch Date for 50th Electron Mission, Prepares to Deploy Five Satellites for Kinéis.md\|Rocket Lab Sets Launch Date for 50th Electron Mission, Prepares to Deploy Five Satellites for Kinéis]]                                       | June 07, 2024      |
| [[News/Rocket Lab Lands Multi-Launch Deal to Deploy Entire IoT Satellite Constellation for Kinéis.md\|Rocket Lab Lands Multi-Launch Deal to Deploy Entire IoT Satellite Constellation for Kinéis]]                                                           | September 08, 2021 |

%%DATAVIEW_PUBLISHER: end %%
## Notes

Kinéis currently operates the [Argos System](https://en.wikipedia.org/wiki/Argos_(satellite_system)), an international scientific collaboration between [[CNES]], the National Oceanic and Atmospheric Administration (NOAA), the European Organization for the Exploitation of Meteorological Satellites (EUMETSAT) and the Indian Space Research Organization (ISRO), to monitor wildlife, fisheries, and to collect data about Earth’s climate and environment through CLS. Kinéis’ new constellation will complete the current system with more powerful 30kg-class nanosats that integrate IoT technology and a ship-tracking Automatic Identification System (AIS). Once deployed, this technology will allow Kinéis to expand across multiple industries and scale from 20,000 devices connected to millions.