---
name: True Anomaly
website: https://www.trueanomaly.space/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> True Anomaly
## Partner Details

**Website**: https://www.trueanomaly.space/

True Anomaly is a U.S. defense-focused space startup founded in 2022 by former U.S. military officers. The company develops spacecraft, autonomy software, and training environments to support space domain awareness (SDA), rendezvous and proximity operations (RPO), and related national security missions. Their flagship spacecraft, the Jackal autonomous orbital vehicle, is a modular bus designed for maneuverability, rapid tasking, and payload flexibility across LEO, GEO, and cislunar regimes. True Anomaly also develops the Mosaic autonomy stack and a digital training/simulation ecosystem, positioning itself as both a hardware and software provider for responsive space operations.

![[TrueAnomaly.webp|300]]
## Missions

[[VICTUS HAZE]]
## Space Systems

### Jackal

#### Summary 

Jackal is a modular, maneuverable autonomous orbital vehicle (AOV) designed for multi-mission flexibility. Jackal’s multi-modal sensor suite and propulsion allow it to execute responsive maneuvers and act as a stand-in for both friendly and potentially non-cooperative spacecraft. With ~275 kg wet mass and a payload-agnostic design, it demonstrates how a rapid-response SDA/RPO platform can be 
deployed and tasked on short notice.
🔗 [True Anomaly Jackal](https://www.trueanomaly.space/jackal)

![[Pasted image 20250816111327.jpg]]
[Payload Space](https://payloadspace.com/space-force-backs-multi-vehicle-commercial-rpo-demos/)

#### Specifications

| Specification         | Value                                                                                                                                               |
| --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Type**              | Autonomous Orbital Vehicle (AOV)                                                                                                                    |
| **Mass**              | \~275 kg wet ([TechCrunch](https://techcrunch.com/2023/08/17/true-anomaly-gets-regulatory-greenlight-for-first-spacecraft-reconnaissance-mission/)) |
| **Payload Capacity**  | Baseline config supports ~50 kg / 200 W; GEO/cislunar variants up to ~200 kg / 1,000 W                                                              |
| **ΔV Capability**     | \~500 m/s in FCC filings; True Anomaly markets **up to 800–1000 m/s** (payload-dependent)                                                           |
| **Guidance/Control**  | [MosaicOS](https://www.trueanomaly.space/mosaic) autonomy stack; onboard compute for RPO decision-making                                            |
| **Sensors**           | Multi-modal suite (EO/IR, optical, RF; configurable per mission)                                                                                    |
| **Power**             | Solar arrays sized for smallsat-class operations (200–1000 W depending on config)                                                                   |
| **Comm**              | Secure, low-latency C2; emphasis on autonomy to reduce comms dependency                                                                             |
| **Operational Range** | LEO, MEO, GEO, cislunar-capable                                                                                                                     |
| **Role in HAZE**      | Target / cooperative spacecraft for RPO; demonstrates maneuvering under TacRS                                                                       |

#### Propulsion

Jackal’s maneuverability is enabled by an advanced propulsion suite developed with [[Agile Space Industries]].  Likely [[Agile Space Industries#LE144 Bipropellant Thruster|LE144]] dual-mode thrusters as the Jackal’s main engines, with [[Agile Space Industries#M4 Monopropellant Thruster|M4]] thrusters handling ACS, [[Agile Space Industries#Zero-Slosh Piston Tanks|Zero-Slosh Piston Tanks]], and possible either their MOAB or YOSEMITE propulsion systems. 

## News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(partner, [[]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                                 | Published      |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- |
| [[News/Rocket Lab Selected by Space Systems Command to Build and Launch Spacecraft for Tactically Responsive Space (TacRS) Mission.md\|Rocket Lab Selected by Space Systems Command to Build and Launch Spacecraft for Tactically Responsive Space (TacRS) Mission]] | April 11, 2024 |

%%DATAVIEW_PUBLISHER: end %%
