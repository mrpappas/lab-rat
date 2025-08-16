---
customer: "[[Space Development Agency (SDA)]]"
satellites: 18
aliases: ["T2TL Beta — Rocket Lab"]
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Missions]] <span style="color: LightSlateGray">></span> SDA Tranche 2 - Transport Layer

> **Customer:** [[Space Development Agency (SDA)]]  
> **Contract:** $515 million · 18 **Beta-variant** satellites
> **Satellite Bus**: Rocket Lab [[Lightning]]

## Summary

Rocket Lab is prime-contractor for **18 Beta satellites** in **Tranche 2 Transport Layer (T2TL)** of the [[SDA Proliferated Warfighter Space Architecture (PWSA)]].  
The Beta variant adds **UHF / TACSATCOM** and advanced networking payloads on top of the baseline optical cross-link design.

🔗 [[Rocket Lab Makes its Defense Prime Debut with $0.5 Billion Contract to Design and Build Satellite Constellation for Space Development Agency|Award announcement]]  
🔗 [Solicitation SAM.gov](https://sam.gov/opp/5a29bd91e0d9448c920b605eb399ca37/view)

## Program Status

| Milestone                       | Date            | Note                                                                                                                                                                                                                                                                   |
| ------------------------------- | --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Contract award                  | **18 Oct 2023** | [SDA press release](https://rocketlabcorp.com/updates/rocket-lab-makes-its-defense-prime-debut-with-0-5-billion-contract-to-design-and-build-satellite-constellation-for-space-development-agency/), FFP OTA                                                           |
| Preliminary Design Review (PDR) | **Jan 2025**    | [Completed on schedule](https://rocketlabcorp.com/updates/rocket-lab-on-track-to-advance-u-s-defense-capabilities-passing-major-milestone-in-development-of-spacecraft-constellation-for-space-development-agency-2/)                                                  |
| Critical Design Review (CDR)    | **July 2025**   | [Completed on schedule](https://rocketlabcorp.com/updates/rocket-lab-successfully-completes-critical-design-review-for-space-development-agencys-t2tl-beta-constellation/#:~:text=The%20milestone%20follows%20Rocket%20Lab's,move%20into%20full%2Dscale%20production.) |
| First launch (target)           | **NET 2026**    | Falcon 9 block-buy                                                                                                                                                                                                                                                     |

*(Launch services procured separately by SDA.)*

## Spacecraft Requirements (Beta)

| Subsystem | Key Specs |
|-----------|-----------|
| **OISL** | 3 optical terminals (100 Gbps class) |
| **Comms** | Ka-band mission payload + UHF/TACSATCOM |
| **Networking** | On-board IP router, Link 16 gateway |
| **Nav & TT&C** | GNSS + S-band backup |
| **Cyber** | SDA NEBULA-compatible zero-trust stack |

![[Pasted image 20250705130557.png]]

[Source](https://www.sda.mil/sda-issues-solicitation-for-tranche-2-transport-layer-t2tl-beta-space-vehicles/)

## Spacecraft

### x18 [[Space Development Agency (SDA)#T2TL Transport Layer Beta|T2TL Transport Layer Beta]]

![[Space Development Agency (SDA)#T2TL Transport Layer Beta|T2TL Transport Layer Beta]]

## Sub-contractors

| Company | Contribution |
|---------|--------------|
| [[CesiumAstro]] | **Vireo** Ka-band AESA payload |
| [[Mynaric]] | **CONDOR Mk3** optical terminals |
| [[Redwire Space]] | Antennas & RF hardware |
| [SEAKR Engineering](https://www.seakr.com/) | TACSATCOM SDR & NES |
| [Collins Aerospace](https://www.collinsaerospace.com/) | TACSATCOM waveform, SW/FW |
| [Parsons](https://www.parsons.com/) | **NOVA** ground segment (NEBULA Ops) |
### See also

- [[SDA Proliferated Warfighter Space Architecture (PWSA)]] — full tranche & layer overview  
- [[Space Development Agency (SDA)]] — agency background and acquisition approach

## News
%% DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(mission, [[SDA Proliferated Warfighter Space Architecture (PWSA)]])
or contains(mission, [[]])
sort published desc

```
%%

| File                                                                                                                                                                                                                                                                                                                             | Published        |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- |
| [[News/Rocket Lab Successfully Completes Critical Design Review for Space Development Agency’s T2TL-Beta Constellation.md\|Rocket Lab Successfully Completes Critical Design Review for Space Development Agency’s T2TL-Beta Constellation]]                                                                                     | July 01, 2025    |
| [[News/Rocket Lab on Track to Advance U.S. Defense Capabilities, Passing Major Milestone in Development of Spacecraft Constellation for Space Development Agency.md\|Rocket Lab on Track to Advance U.S. Defense Capabilities, Passing Major Milestone in Development of Spacecraft Constellation for Space Development Agency]] | January 09, 2025 |
| [[News/Rocket Lab Selects Subcontractors to Support SDA Satellite Constellation Development.md\|Rocket Lab Selects Subcontractors to Support SDA Satellite Constellation Development]]                                                                                                                                           | May 06, 2024     |
| [[News/Rocket Lab Makes its Defense Prime Debut with $0.5 Billion Contract to Design and Build Satellite Constellation for Space Development Agency.md\|Rocket Lab Makes its Defense Prime Debut with $0.5 Billion Contract to Design and Build Satellite Constellation for Space Development Agency]]                           | January 08, 2024 |

%% DATAVIEW_PUBLISHER: end %%