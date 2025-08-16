---
customer: "[[Space Development Agency (SDA)]]"
tags: [PWSA, Transport Layer, Tracking Layer, Custody Layer, Tranches]
---
[[Home|🏠]] > [[Contracts & Vehicles]] > SDA Proliferated Warfighter Space Architecture (PWSA)

> [!summary] SDA Proliferated Warfighter Space Architecture (PWSA)
> **Scope**: hundreds of optical-cross-linked satellites that deliver secure data transport and missile warning/tracking, with future layers for persistent ISR (“Custody”), navigation and battle-management.  
> 
> **Goal**: resilient, low-latency connectivity and global missile-threat custody for joint-force shooters.  Tranches progress as follows: T0 (demo), T1 (initial ops), T2 (scaled warfighting by 2028), and T3 (global persistence) whose Tracking RFP was released April 2025 while the Transport RFP is on budget-driven hold.  
> 
> 🔗 [[SDA Tranche 2 - Transport Layer]] (Rocket Lab 18 SV Beta contract)

## Overview

| Tranche                   | Launch window | Transport Layer awards                                                                                                                                                                               | Tracking Layer awards                                                                                                                                                                                                                    | Notes                                                        |
| ------------------------- | ------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| T0 “Warfighter Immersion” | '23-'24       | 20 SV - York 10, Lockheed 10                                                                                                                                                                         | 8 SV - L3Harris 4, SpaceX 4                                                                                                                                                                                                              | Initial ops checkout                                         |
| T1 “Initial Warfighting”  | '25-'26       | 126 SV - York 42, Northrop 42, Lockheed 42                                                                                                                                                           | 28 SV - L3Harris 14, Northrop 14                                                                                                                                                                                                         | First 24/7 global mesh                                       |
| T2 “Scaled Warfighting”   | '26-'28       | Alpha 62 SV - York ($615 M), Beta 90 SV - Lockheed 36 ($816 M), Northrop 36 ($733 M), [[SDA Tranche 2 - Transport Layer\|Rocket Lab 18 ($515 M)]], Gamma 20 SV - York 10 ($170 M), Tyvak 10 ($254 M) | 54 SV - L3Harris 18 ($919 M), Lockheed 18 ($890 M), Sierra 18 ($740 M)                                                                                                                                                                   | Adds UHF/TACSATCOM, advanced waveforms, fire-control IR      |
| T3 “Global Persistence”   | '28-'30       | Transport Layer RFP paused until SDA receives FY 26 budget guidance; draft “T3TL-Upsilon” issued Jan 2025, final solicitation delayed Apr 2025                                                       | [Tracking Layer RFP](https://sam.gov/opp/d37947f84fdf447cb64228dcc26d4952/view) “T3TRK” released 7 Apr 2025, seeks three awards of 18 SV (54 total); proposals due 22 May 2025; awards projected 1Q FY 26; first launch planned 4Q FY 29 | Will add Custody pathfinders and next-gen Transport payloads |

SV = space vehicle. Contract values are firm-fixed-price OTA ceilings; launch services are contracted separately.

### Transport Layer

* Orbit 750 – 1200 km LEO  
* Three or more optical inter-satellite links per SV (100 Gbps class)  
* Constellation provides at least two SV in view 95 % of Earth, at least one SV 99 %  
* Variants: Alpha (baseline), Beta (+ UHF/TACSATCOM), Gamma (advanced waveforms)  
* T3 Transport solicitation delayed pending budget guidance; draft “Upsilon” variant called for roughly 140 SV across multiple configurations

### Tracking Layer

* Wide-field MW sensors plus narrow-field MT (fire-control) sensors  
* Continuous custody of ballistic and hypersonic threats  
* Data forwarded across the Transport mesh to shooters  
* T3 Tracking seeks at least 54 SV in six planes, with option for additional buys

### Custody Layer (planned)

SDA intends a Custody Layer for persistent ISR / moving-target indication. No production contracts as of mid-2025; requirements expected with the T3 program.

## Contract Totals to Date

| Award set | SV | Obligated value |
|-----------|----|-----------------|
| T1 Transport | 126 | ~ $1.8 B |
| T1 Tracking | 28 | ~ $1.3 B |
| T2 Transport Alpha | 62 | $615 M |
| T2 Transport Beta | 90 | $2.06 B |
| T2 Transport Gamma | 20 | $424 M |
| T2 Tracking | 54 | $2.55 B |
## Official references

* [SDA Transport overview](https://www.sda.mil/transport/)
* [SDA Tracking overview](https://www.sda.mil/tracking/)
* [T3 Tracking Layer RFP](https://www.sda.mil/sda-seeks-proposals-for-tranche-3-tracking-layer-t3trk-of-the-proliferated-warfighter-space-architecture-pwsa/)
* [Draft T3 Transport Layer “Upsilon”](https://www.sda.mil/sda-requests-industry-feedback-on-tranche-3-transport-layer-upsilon-variant-draft-solicitation/)

## Related pages

* [[SDA Tranche 2 - Transport Layer]] – Rocket Lab’s 18 Beta satellites  
* [[Space Development Agency (SDA)]]

## News

%% DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(contract, [[]])
sort published desc

```
%%

| File                                                                                                                                                                                                                                                                                                                                       | Published        |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------- |
| [[News/Rocket Lab Successfully Completes Critical Design Review for Space Development Agency’s T2TL-Beta Constellation.md\|Rocket Lab Successfully Completes Critical Design Review for Space Development Agency’s T2TL-Beta Constellation]]                                                                                               | July 01, 2025    |
| [[News/Rocket Lab Announces Intention to Acquire Mynaric, Leading Laser Communications Provider, in Latest Strategic Step Toward Becoming an End-to-End Space Company.md\|Rocket Lab Announces Intention to Acquire Mynaric, Leading Laser Communications Provider, in Latest Strategic Step Toward Becoming an End-to-End Space Company]] | March 11, 2025   |
| [[News/Rocket Lab on Track to Advance U.S. Defense Capabilities, Passing Major Milestone in Development of Spacecraft Constellation for Space Development Agency.md\|Rocket Lab on Track to Advance U.S. Defense Capabilities, Passing Major Milestone in Development of Spacecraft Constellation for Space Development Agency]]           | January 09, 2025 |
| [[News/Rocket Lab Selects Subcontractors to Support SDA Satellite Constellation Development.md\|Rocket Lab Selects Subcontractors to Support SDA Satellite Constellation Development]]                                                                                                                                                     | May 06, 2024     |
| [[News/Rocket Lab Makes its Defense Prime Debut with $0.5 Billion Contract to Design and Build Satellite Constellation for Space Development Agency.md\|Rocket Lab Makes its Defense Prime Debut with $0.5 Billion Contract to Design and Build Satellite Constellation for Space Development Agency]]                                     | January 08, 2024 |

%% DATAVIEW_PUBLISHER: end %%
