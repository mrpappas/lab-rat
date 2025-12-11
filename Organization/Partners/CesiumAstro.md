---
name: CesiumAstro
website: https://www.cesiumastro.com/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> CesiumAstro

**Website**: https://www.cesiumastro.com/

CesiumAstro is an aerospace and defense company specializing in active phased array and software-defined radio technology. Founded in 2017 and headquartered in Austin, Texas, the company develops high-performance communication, sensing, and networking systems for satellites, unmanned aerial vehicles, and other mission-critical platforms. CesiumAstro’s modular hardware and software solutions support a range of applications, including secure data transmission, radar, and telemetry. With in-house design, manufacturing, and testing capabilities, the company focuses on delivering scalable, reliable systems for commercial, government, and defense customers.

![[Cesium_product_logo_plate-3.webp|300]]

## Missions

### SDA Tranche 2
CesiumAstro was selected as a subcontractor for Rocket Lab's [[SDA Tranche 2 - Transport Layer]] contract.

🔗 [[Rocket Lab Selects Subcontractors to Support SDA Satellite Constellation Development]]

### NASA Starling
Part of of [NASA's Starling](https://www.nasa.gov/smallspacecraft/what-is-starling/) mission, CesiumAstro was selected to provide crosslink radios and antennas for the MANET (Mobile Ad-hoc Network) experiment. The CommPacks were installed on each of the four cubesats launched on [[039 - Baby Come Back]] 


## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[]])
sort launch_date desc
```
%%

| File                                                              | Date             | Location                                              | Vehicle                          | Orbit & Mass               | Outcome |
| ----------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | -------------------------- | ------- |
| [[Launch/Launches/039 - Baby Come Back.md\|039 - Baby Come Back]] | 2023-07-18 01:27 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 1000 km \| 99.45° \| 86 kg | ✅       |

%%DATAVIEW_PUBLISHER: end %%

## 🛰️ Space Systems

### Vireo Multi-Beam Communications Payload

https://www.cesiumastro.com/systems/vireo

A complete solution for uplink and downlink opperations from LEO, the Vireo payload supports to 8-beam opperation with independently steerable, shapable beams. Jam resistant and reconfigurable on-orbit to meet evolving threats.

| Specification   | Value                                                    |
| --------------- | -------------------------------------------------------- |
| Frequency Range | Tx 17.5 GHz to 21.2 GHz<br>Rx 27.5 GHz to 31 GHz         |
| Polarization    | RHCP or LHCP<br>selectable at manufacturing              |
| Size            | Tx 27 cm x 23 cm x 16 cm<br>Rx 18 cm x 15.5 cm x 15.5 cm |
| Mass            | Tx 14.5 kg<br>Rx 7 kg                                    |
| Lifetime        | 7 to 12 years in LEO<br>at 1000 km                       |
| Baseplate Temp. | -24 °C to 61 °C<br>Operational                           |
| EIRP            | 45 dBW to 49 dBW<br>aggregate at boresight               |
| G/T             | 5 dB/K<br>300 K scene temperature                        |



![[Pasted image 20250302180643.png]]


![[Pasted image 20250302181043.png]]

### CommPack Cross-Link Communications Payload

https://www.cesiumastro.com/applications/isl

Part of NASA's Starling mission, CesiumAstro’s CommPack payload includes two S-band antennas, the [[CesiumAstro#🛰️ Space Systems#SDR-1001 Software Defined Radio|SDR-1001 software-defined radio]], and their carrier-sense multiple access/time-division duplexed (CSMA/TDD) waveform enabling mobile ad hoc networking (MANET) in space. The satellites use CommPack to establish and maintain the dynamic communications network between the spacecraft in the swarm.

[📰 News Release](https://www.cesiumastro.com/press-release/cesiumastro-celebrates-successful-tests-of-its-commpack-cross-link-communications-payloads-on-nasas-starling-mission-achieves-trl-9-status)

![[Pasted image 20250303002028.png]]

### SDR-1001 Software Defined Radio

https://www.cesiumastro.com/products/sdr-1001#specifications

A high-performance, compact, software-defined radio designed to operate in LEO and airborne environments, SDR-1001 is suitable for demanding RF, digital signal processing, and communications applications supporting custom waveform development or DVB-S2/DVB-S2X and CCSDS modems.

- 4x 200 MHz Tx channels
- 4x 100 MHz Rx channels
- TDD and FDD operation
- Tunable from 300 MHz to 6 GHz
- Tx up to 500 Mb/s on single channel
- 1000BASE-X, UART, and SpaceWire interfaces
- FPGA Development Kit™ for user-customizable waveform development
- Redundant boot flash with automatic failover and watchdog timers
- Onboard telemetry sensing
- Compact design with thermal pillars

| Specification            | Value           |
| ------------------------ | --------------- |
| DC Input Voltage         | 9 V to 13 V     |
| Baseplate Operating Temp | -24 °C to 61 °C |
| Mass                     | 110 g           |


![[Pasted image 20250303003049.png]]


![[Pasted image 20250303003029.png]]


## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(partner, [[]])
sort published desc
```
%%

| File                                                                                                                                                                                   | Published    |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ |
| [[News/Rocket Lab Selects Subcontractors to Support SDA Satellite Constellation Development.md\|Rocket Lab Selects Subcontractors to Support SDA Satellite Constellation Development]] | May 06, 2024 |

%%DATAVIEW_PUBLISHER: end %%