---
customer: "[[U.S. Space Force]]"
contract: Tractically Responsive Space (TacRS)
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Missions]] <span style="color: LightSlateGray">></span> VITCUS HAZE
## Mission Details

**Customer**: [[U.S. Space Force]], Space Systems Command
**Program**: [Tactically Responsive Space (TacRS)](https://www.csis.org/analysis/tactically-responsive-space-emerging-new-deterrence-tool), under SSC’s Space Safari in partnership with the Defense Innovation Unit (DIU) and [SpaceWERX](https://spacewerx.us/)

**VICTUS HAZE** is part of the U.S. Space Force’s Tactically Responsive Space (TacRS) program, designed to test end-to-end rapid response capability. Rocket Lab is providing a customized [[Photon]] bus with rendezvous and proximity operations (RPO) hardware and autonomy stack, launched on [[Electron]]. The mission will simulate a real-world contingency: the spacecraft and ground teams will be placed in hot standby, then given a 24-hour notice to launch, with the expectation of achieving orbit and executing RPO/SDA tasks shortly after. 

Rocket Lab’s vehicle is intended to approach and inspect a target spacecraft (operated by [[True Anomaly]], launched by Firefly Alpha), demonstrating cooperative and potentially non-cooperative RPO. The campaign will exercise tasking, launch ops, command uplink, and autonomous decision-making under compressed timelines, feeding into SSC’s efforts to field repeatable TacRS architectures.


![[Pasted image 20250816122117.png]]

## Spacecraft

1. [[#VICTUS HAZE 1 (True Anomaly Jackal)]]
2. [[#VICTUS HAZE 2 (Rocket Lab Photon)]]

## VICTUS HAZE 1 (True Anomaly Jackal)

#### Summary

This satellite, built by [[True Anomaly]], provides the target platform in a cooperative RPO scenario, maneuvering in orbit while Rocket Lab’s satellite performs inspection and characterization. It is built on their [[True Anomaly#Jackal|Jackal]] Bus: 

![[True Anomaly#Jackal]]

#### Launch

**Vehicle**: Firefly Alpha
**Location**: Vandenberg SFB
**Timeline**: Likely Fall 2025

#### Payload

>[!warning] Payload Unknown

While not officially detailed, [[True Anomaly#Jackal|Jackal]] is a multi-mission, payload-agnostic platform with configurable hardpoints. It supports payloads ranging from ~50 kg (LEO baseline) to ~200 kg (GEO/cislunar). Its advertised suite includes multi-spectral RPO sensors (EO/IR, optical, RF), though exact hardware for HAZE isn’t published. Demo Jackal craft have featured a 4 MP camera plus IR sensors, which may reflect the baseline configuration here.

## VICTUS HAZE 2 (Rocket Lab Photon)

#### Summary

Built on the [[Photon]] bus, for VICTUS HAZE it will serve as the inspector spacecraft, carrying an LLNL optical SDA payload built around a monolithic fused-silica telescope. The design enables immediate activation after launch, giving the vehicle the ability to rapidly approach and characterize VH1 in orbit. The platform integrates propulsion, precision GNC, low-latency comms, and autonomy features to support rendezvous, proximity ops, and fast decision cycles.


![[Pasted image 20250816115225.png]]

[Source](https://forum.nasaspaceflight.com/index.php?action=dlattach;topic=46744.0;attach=2312802;image)
#### Specifications

| Specification     | Value                                                                                                  |
| ----------------- | ------------------------------------------------------------------------------------------------------ |
| **Bus**           | [[Photon]]                                                                                             |
| Orbit             | LEO up to 600km altitude and SSO inclination w/ propulsion to enable dynamic space operations          |
| Lifetime          | 3 Years +                                                                                              |
| Mission Assurance | [[⚖️ NASA Mission and Instrument Risk Classification#Class D\|Class D]] (equivalent)                   |
| Satellite Mass    | ~200 kg                                                                                                |
| Power             | ~500 W, fixed arrays                                                                                   |
| Propulsion        | [[Curie]] Bi-Propellant Chemical Engine, > 650 m/sec, 6 DOF Cold Gas RCS                               |
| Comms             | S-Band TT&C, X-band Mission Data Link                                                                  |
| Payload           | LLNL monolithic fused-silica optical telescope (SDA)                                                   |
| Role in HAZE      | Inspector spacecraft; approaches and characterizes Jackal under TacRS hot-standby / 24-hr launch rules |

#### Launch

**Vehicle**: Rocket Lab [[Electron]]
**Location**: [[Launch Complex 1]] or [[Launch Complex 2]]
**Timeline**: Likely Fall 2025

#### Payload

The VICTUS HAZE spacecraft carries an optical space domain awareness instrument developed by [Lawrence Livermore National Laboratory](https://www.llnl.gov/) (LLNL). The payload is based on a monolithic fused-silica telescope, a single-piece design that requires no alignment or calibration after manufacture. This allows the instrument to begin operations almost immediately after launch, reducing commissioning time and aligning with the mission’s goal of rapid threat characterization.

The system builds on LLNL’s earlier work for the Tactically Responsive Launch-2 (TacRL-2) mission in 2021, which flew a similar telescope and sensor package on accelerated development timelines. For VICTUS HAZE, the payload will be integrated with Rocket Lab’s spacecraft bus to support a full demonstration of rapid launch, deployment, and space domain awareness operations.

🔗 [LLNL Article 1](https://www.llnl.gov/article/51201/lab-provide-optical-payload-upcoming-us-space-force-mission)
🔗 [LLNL Article 2](https://www.llnl.gov/article/52211/llnl-starris-optimax-space-systems-announce-partnership-monolithic-telescope-technology)

![[Pasted image 20250816122426.jpg]]

## Objectives

✅ Demonstrate responsive space capabilities: launch readiness within 24 hours of notice.
✅ Execute rendezvous and proximity operations (RPO) to approach and characterize target objects in orbit.
✅ Advance space domain awareness (SDA) via autonomous on-orbit threat identification.
✅ Validate TacRS processes and tactics, including hot standby, rapid activation, and launch in a realistic threat-response scenario.

## Mission Phases

 ☑️ 1. Contract Award & Design - Rocket Lab secured $32 million contract from SSC via DIU for VICTUS HAZE; True Anomaly received parallel contract for a second performer. [Source](https://www.space.com/space-exploration/satellites/us-space-force-picks-rocket-lab-for-2025-victus-haze-space-domain-awareness-mission)
 ☑️ 2. Critical Design Review (CDR) - Successfully completed in early 2025, clearing the path to production. [Source](https://www.businesswire.com/news/home/20250806787028/en/Rocket-Lab-Clears-Integration-Milestone-for-VICTUS-HAZE-Delivering-End-to-End-Capabilities-for-Responsive-Space-Operations)
 ☑️ 3. Systems Integration Review (SIR) & Integration - In May 2025, all spacecraft components, systems, and software were validated and integration proceeded.
 ⌛ 4. Final Testing - Now entering final testing phase ahead of launch, completed within ~15 months from contract award.
 🟪 5. Hot Standby, Notice to Launch, Rapid Deployment - Team awaits a go‑order; must achieve launch within 24-hour notice, proceeding through command operating phases and on-orbit RPO/SDA operations alongside True Anomaly’s Jackal vehicle.


## VICTUS NOX

🔗 [Firefly Mission Link](https://fireflyspace.com/missions/victus-nox/)

VICTUS NOX was the first full TacRS demonstration, focused on proving the rapid call-up and launch sequence. VICTUS HAZE builds directly on this, keeping the 24-hour launch requirement but extending the scope to include rendezvous and proximity operations and space domain awareness once on orbit.

![[Pasted image 20250816133700.jpg|350]]

**Launch Date**: September 14 2023
**Awardees**: Firefly (Alpha launch), Millennium Space Systems (satellite).
**Objective**: Demonstrate hot standby, notice-to-launch, 24-hr launch, rapid commissioning.
**Result**: Firefly Alpha launched from VSFB within 27 hours of the USSF call-up, deploying the Millennium-built satellite. Spacecraft was checked out and operational within ~37 hours.
**Focus**: Primarily validated rapid call-up and launch timelines (first end-to-end TacRS demonstration).

### NOX vs HAZE

| Feature                     | **VICTUS NOX** (2023)                                  | **VICTUS HAZE** (2025)                                                           |
| --------------------------- | ------------------------------------------------------ | -------------------------------------------------------------------------------- |
| **Awardees**                | Firefly (launch) + Millennium Space Systems (bus)      | Rocket Lab (Photon bus + Electron) + True Anomaly (Jackal + Firefly Alpha)       |
| **Mission emphasis**        | Rapid call-up, launch within 24 hr, fast commissioning | Rapid call-up **plus** on-orbit ops (RPO & SDA)                                  |
| **Timeline from call-up**   | Launch within 27 hr; ops within \~37 hr                | Launch within 24 hr; immediate RPO tasking post-commissioning                    |
| **Spacecraft**              | Millennium-built smallsat (details limited)            | Rocket Lab Photon RPO spacecraft + LLNL SDA payload; True Anomaly Jackal vehicle |
| **Launch site**             | Vandenberg SFB, Firefly Alpha                          | LC-1 or LC-2 on Electron; VSFB on Firefly Alpha                                  |
| **Demonstrated capability** | End-to-end TacRS logistics, launch readiness           | Extension into maneuvering, inspection, and threat-response scenario             |
| **Program role**            | First proof-of-concept for TacRS end-to-end            | Expansion into repeatable operational architecture (TacRS “phase two”)           |

## News

%% DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(mission, [[]])
sort published desc

```
%%

| File                                                                                                                                                                                                                                                                 | Published         |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/Rocket Lab Clears Integration Milestone for VICTUS HAZE, Delivering End-to-End Capabilities for Responsive Space Operations.md\|Rocket Lab Clears Integration Milestone for VICTUS HAZE, Delivering End-to-End Capabilities for Responsive Space Operations]] | August 06, 2025   |
| [[News/Rocket Lab Clears Critical Design Review for Space Force VICTUS HAZE Mission.md\|Rocket Lab Clears Critical Design Review for Space Force VICTUS HAZE Mission]]                                                                                               | February 24, 2025 |
| [[News/Rocket Lab Selected by Space Systems Command to Build and Launch Spacecraft for Tactically Responsive Space (TacRS) Mission.md\|Rocket Lab Selected by Space Systems Command to Build and Launch Spacecraft for Tactically Responsive Space (TacRS) Mission]] | April 11, 2024    |

%% DATAVIEW_PUBLISHER: end %%

## Links

- [Rocket Lab Press Release](https://rocketlabcorp.com/updates/rocket-lab-selected-by-space-systems-command-to-build-and-launch-spacecraft-for-tactically-responsive-space-tacrs-mission/?utm_source=chatgpt.com)
- [SSC Press Release](https://www.ssc.spaceforce.mil/Portals/3/Documents/PRESS%20RELEASES/Space%20Systems%20Command%20awards%20Tactically%20Responsive%20Space%20%28TacRS%29%20contracts%20in%20support%20of%20VICTUS%20HAZE%20mission.pdf?ver=aiTDx8FZuvXQ8sIlDUvLww%3D%3D)
- [Space.com article](https://www.space.com/space-exploration/satellites/us-space-force-picks-rocket-lab-for-2025-victus-haze-space-domain-awareness-mission)