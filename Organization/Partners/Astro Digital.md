---
name: Astro Digital
website: https://astrodigital.com/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> Astro Digital

**Website:** https://astrodigital.com/

Astro Digital is a satellite manufacturer and operator specializing in delivering turnkey solutions for Earth observation, communications, and data analytics. The company focuses on designing, building, and operating small satellite systems to provide rapid access to data for commercial and government customers. Astro Digital offers customizable platforms for satellite missions, including payload integration, mission operations, and ground support. Known for its flexible approach, the company serves clients requiring Earth imagery, environmental monitoring, and IoT data transmission.

![[Pasted image 20251211031134.jpg|300]]

## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[]])
sort launch_date desc
```
%%

| File                                                                    | Date             | Location                                              | Vehicle                                                 | Orbit & Mass              | Outcome |
| ----------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | ------------------------------------------------------- | ------------------------- | ------- |
| [[Launch/Launches/009 - As The Crow Flies.md\|009 - As The Crow Flies]] | 2019-10-17 01:22 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 1200 km \| 87.9° \| 20 kg | ✅       |

%%DATAVIEW_PUBLISHER: end %%

## Astro Digital Bus Platform

The Astro Digital Bus Platform is a modular and scalable collection of satellite subsystems. With bus variants ranging from 6U CubeSats to ESPA Class missions, the buses provide a flexible and cost-effective solutions across a wide range of applications and mission profiles from LEO to GEO.

Datasheet: https://app.box.com/s/zoxrybljpeog38qttqphx262zeufduov

### Corvus-6U

Corvus-6U is the longest running production platform at Astro Digital, a multi-purpose CubeSat capable of a wide variety of missions. 
Datasheet: https://www.spacemanic.com/files/datasheet/6U.pdf

![[Pasted image 20250621181301.png]]

| Specification                     | Value                                                                                                   |
| --------------------------------- | ------------------------------------------------------------------------------------------------------- |
| Mass                              | Up to 12 kg                                                                                             |
| Dimensions                        | 10cm x 20cm x 30xm                                                                                      |
| Payload Mass                      | Up to 4 kg                                                                                              |
| Payload Volume                    | Up to 4U                                                                                                |
| Spacecraft Sun-pointing Power Gen | 40 W*                                                                                                   |
| Orbit Avg Power                   | 15 W*                                                                                                   |
| Peak Payload Power                | 100 W*                                                                                                  |
| Battery Capacity                  | 70 Whrs*                                                                                                |
| Bus Voltage                       | 4 V unregulated, with configurable rails up to 17 V available                                           |
| On-board Data Interfaces          | Ethernet, UART, USB, I<sup>2</sup>C, SPI                                                                |
| Data Connector                    | Configurable - Typically [Harwin Datamate](https://www.harwin.com/hri-range/datamate) M80 or M83 series |
| Deployment Interface              | Any industry standard 6U CubeSat deployer                                                               |
\* Specs listed based on most common configuration. Bus can be configured with additional battery / solar options

### Corvus-16U

First launched in 2019, Corvus-16U is the first 16U CubeSat ever launched.

![[Pasted image 20250621181407.png]]

| Specification                     | Value                                                                                                   |
| --------------------------------- | ------------------------------------------------------------------------------------------------------- |
| Mass                              | Up to 24 kg                                                                                             |
| Dimensions                        | 20cm x 20cm x 40cm                                                                                      |
| Payload Mass                      | Up to 18 kg                                                                                             |
| Payload Volume                    | Up  to 12U                                                                                              |
| Spacecraft Sun-pointing Power Gen | 120 W*                                                                                                  |
| Orbit Avg Power                   | 42 W*                                                                                                   |
| Peak Payload Power                | 200 W*                                                                                                  |
| Battery Capacity                  | 240 Whrs*                                                                                               |
| Bus Voltage                       | 4 V unregulated, with configurable rails up to 17 V available                                           |
| On-board Data Interfaces          | Ethernet, UART, USB, I<sup>2</sup>C, SPI                                                                |
| Data Connector                    | Configurable - Typically [Harwin Datamate](https://www.harwin.com/hri-range/datamate) M80 or M83 series |
| Deployment Interface              | Any industry standard 16U CubeSat deployer                                                              |
\* Specs listed based on most common configuration. Bus can be configured with additional battery / solar options

### Corvus-Micro

On orbit heritage since 2021, the Corvus-Micro form factor provides additional design flexibility and increased capability with over 50% of the platform volume available for the payload. 

![[Pasted image 20250621181604.png]]

| Specification                     | Value                                                                                                   |
| --------------------------------- | ------------------------------------------------------------------------------------------------------- |
| Mass                              | Up to 60 kg                                                                                             |
| Dimensions                        | 40cm x 40cm x 60cm                                                                                      |
| Payload Mass                      | Up to 30 kg                                                                                             |
| Payload Volume                    | Up  to 35cm x 35cm x 40cm                                                                               |
| Spacecraft Sun-pointing Power Gen | 130 W*                                                                                                  |
| Orbit Avg Power                   | 70 W*                                                                                                   |
| Peak Payload Power                | 1 kW*                                                                                                   |
| Battery Capacity                  | 450 Whrs*                                                                                               |
| Bus Voltage                       | 28-36 V unregulated, with configurable rails available                                                  |
| On-board Data Interfaces          | Ethernet, UART, USB, I<sup>2</sup>C, SPI, CAN                                                           |
| Data Connector                    | Configurable - Typically [Harwin Datamate](https://www.harwin.com/hri-range/datamate) M80 or M83 series |
| Deployment Interface              | Any 8", 11.7", or 15" ring deployment mechanism                                                         |
\* Specs listed based on most common configuration. Bus can be configured with additional battery / solar options

### Corvus-XL

On orbit heritage since 2021, Corvus-XL is the largest flight-heritage platform available at Astro Digital.

![[Pasted image 20250621181747.png]]

| Specification                     | Value                                                                                                   |
| --------------------------------- | ------------------------------------------------------------------------------------------------------- |
| Mass                              | Up to 200 kg                                                                                            |
| Dimensions                        | 50cm x 50cm x 100cm                                                                                     |
| Payload Mass                      | Up to 100 kg                                                                                            |
| Payload Volume                    | Up  to 50cm x 50cm x 70cm                                                                               |
| Spacecraft Sun-pointing Power Gen | 500 W*                                                                                                  |
| Orbit Avg Power                   | 300 W*                                                                                                  |
| Peak Payload Power                | 4 kW*                                                                                                   |
| Battery Capacity                  | 960 Whrs*                                                                                               |
| Bus Voltage                       | 28-36 V unregulated, with configurable rails available                                                  |
| On-board Data Interfaces          | Ethernet, UART, USB, I<sup>2</sup>C, SPI, CAN                                                           |
| Data Connector                    | Configurable - Typically [Harwin Datamate](https://www.harwin.com/hri-range/datamate) M80 or M83 series |
| Deployment Interface              | Any 15" ring deployment mechanism                                                                       |
\* Specs listed based on most common configuration. Bus can be configured with additional battery / solar options

### Raven

The Raven bus has been developed in response to customer demand to provide more capability in terms of paylaod mass and power generation. The platform has an optional radiation-tolerant architecture designed to operate in GEO and Deep Space environments. The first Raven buses are under contract for GEO launches starting Q4 2025.

![[Pasted image 20250621182238.png]]


| Specification                     | Value                                                                                                   |
| --------------------------------- | ------------------------------------------------------------------------------------------------------- |
| Mass                              | Up to 400 kg                                                                                            |
| Dimensions                        | 100cm x 100cm x 135cm                                                                                   |
| Payload Mass                      | Up to 250 kg                                                                                            |
| Payload Volume                    | Up  to 80cm x 80cm x 90cm                                                                               |
| Spacecraft Sun-pointing Power Gen | 1.5 kW*                                                                                                 |
| Orbit Avg Power                   | 1 kW*                                                                                                   |
| Peak Payload Power                | 4 kW*                                                                                                   |
| Battery Capacity                  | 960 Whrs*                                                                                               |
| Bus Voltage                       | 36 V unregulated, with configurable rails available                                                     |
| On-board Data Interfaces          | Ethernet, UART, USB, I<sup>2</sup>C, SPI, CAN                                                           |
| Data Connector                    | Configurable - Typically [Harwin Datamate](https://www.harwin.com/hri-range/datamate) M80 or M83 series |
| Deployment Interface              | Compatible with 4-point release or 15" ring deployment mechanism                                        |
\* Specs listed based on most common configuration. Bus can be configured with additional battery / solar options

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[]])
sort published desc
```
%%

| File                                                                                                                                                                                                     | Published          |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ |
| [[News/Rocket Lab successfully launches ninth Electron mission, deploys payload to highest orbit yet.md\|Rocket Lab successfully launches ninth Electron mission, deploys payload to highest orbit yet]] | October 17, 2019   |
| [[News/Rocket Lab to launch dedicated mission for Astro Digital.md\|Rocket Lab to launch dedicated mission for Astro Digital]]                                                                           | September 30, 2019 |

%%DATAVIEW_PUBLISHER: end %%