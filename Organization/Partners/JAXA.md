---
name: Japan Aerospace Exporation Agency (JAXA)
website: https://global.jaxa.jp/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> JAXA

**Website**: https://global.jaxa.jp/

JAXA is the Japan Aerospace Exploration Agency, Japan's national space agency responsible for research in space exploration and aviation. It conducts activities ranging from launching satellites and rockets to exploring planets and conducting scientific experiments on the International Space Station (ISS). JAXA was formed in 2003 through the merger of three previous organizations: the Institute of Space and Astronautical Science (ISAS), the National Space Development Agency of Japan (NASDA), and the National Aerospace Laboratory of Japan (NAL). 

![[Pasted image 20251210234728.png]]
## Launches

JAXA Launches w/ Rocket Lab

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[]])
sort launch_date desc
```
%%

| File                                                                | Date             | Location                                              | Vehicle                          | Orbit & Mass               | Outcome |
| ------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | -------------------------- | ------- |
| [[Launch/Launches/077 - RAISE and Shine.md\|077 - RAISE and Shine]] | 2025-12-14 03:09 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 540 km \| 97.5° \| ~110 kg | ✅       |

%%DATAVIEW_PUBLISHER: end %%

## Space Systems

### RAISE-4

#### Summary
RAISE-4 (Rapid Innovative payload demonstration Satellite-4) is a dedicated technology demonstration satellite developed by the Japan Aerospace Exploration Agency (JAXA). It is the primary payload for the Rocket Lab Electron mission, [[077 - RAISE and Shine]], scheduled to launch from [[Launch Complex 1]] in Mahia, New Zealand.

This mission is a critical part of JAXA's [Innovative Satellite Technology Demonstration Program](https://www.kenkai.jaxa.jp/eng/research/innovative/innovative.html), which provides on-orbit demonstration opportunities for private companies, universities, and research institutions to test new space components and subsystems. RAISE-4 carries eight distinct technology themes, six of which are re-flights of payloads originally onboard [RAISE-3](https://space.skyrocket.de/doc_sdat/raise-3.htm) (which was lost in an Epsilon launch failure in 2022). The mission marks the first of two dedicated [[Electron]] launches contracted directly by JAXA, with the second scheduled for Q1 2026.

📰 Press Release: https://www.kenkai.jaxa.jp/kakushin/kakushin04.html
#### Specifications

| Specification          | Value                                                         |
| ---------------------- | ------------------------------------------------------------- |
| Mass                   | ~110 kg                                                       |
| Dimensions             | 790mm x 1000mm x 1010mm                                       |
| Power Generation (BOL) | > 215W                                                        |
| Power Generation (EOL) | > 180W                                                        |
| Transmission Power     | >105Wh, EOL: >62Wh                                            |
| Battery                | Lithium Ion                                                   |
| Stabiliation           | 3-Axis Stabilized                                             |
| Bus Manufacturer       | Mitsubishi Heavy Industries                                   |
| Mission Period         | 2 months of initial operation, 13 months of regular operation |


![[Pasted image 20251124181149.png]]
#### Components and Subsystems

##### LEOMI
**Produced By:** [NTT Corporation](https://group.ntt/en/)
**Description**: In-orbit demonstration of a 920MHz band satellite IoT platform utilizing satellite MIMO technology  
![[Pasted image 20251125013212.png]]
##### GEMINI
**Produced By:** [Mitsubishi Electric Corporation](https://www.mitsubishielectric.com/en/products-solutions/)
**Description**: In-orbit evaluation and model-based development of commercial GPUs  
![[Pasted image 20251125013227.png]]
##### KIR-X
**Produced By:** [Pale Blue Co.](https://pale-blue.co.jp/)
**Description**: In-orbit demonstration of a micro-integrated propulsion system using water as a propellant  
![[Pasted image 20251125013244.png]]
##### TDS-PPT
**Produced By:** [Takahashi Electric Works Co](http://www.t-kc.co.jp/en/company)
**Description**: In-orbit demonstration and performance evaluation of pulsed plasma thruster (PPT) for small satellites  
![[Pasted image 20251125013301.png]]
##### D-SAIL
**Produced By:** [Axelspace Corporation](https://www.axelspace.com/)
**Description**: In-orbit demonstration of membrane-deployable deorbit mechanism for microsatellites
![[Pasted image 20251125013320.png]]
##### HELIOS-R
**Produced By:** [Sakase Adtec Co Ltd](https://www.sakase.co.jp/company_en/)
**Description**: Demonstration of a lightweight membrane deployable structure with power generation and antenna functions toward Society 5.0  
![[Pasted image 20251125013331.png]] 
##### CF-CAM
**Produced By:** [Mach Corporation](https://www.machcorporation.com/eng/index.html)
**Description**: In-orbit demonstration of next-generation high-performance CMOS image sensor
![[Pasted image 20251125013349.png]]
##### SOISOC-4
**Produced By:** [Mitsubishi Heavy Industries](https://www.mhi.com/)
**Description**: On-orbit demonstration of onboard AI object detection and improved detection accuracy using next-generation space MPU
![[Pasted image 20251125013402.png]]
## News

%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[]])
sort published desc
```
%%

| File                                                                                                                                                                                                                         | Published         |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/Mission Success Rocket Lab Deploys First Dedicated Launch for Japan Aerospace Exploration Agency (JAXA).md\|Mission Success Rocket Lab Deploys First Dedicated Launch for Japan Aerospace Exploration Agency (JAXA)]] | December 14, 2025 |
| [[News/Rocket Lab Schedules First Dedicated Launch for Japan Aerospace Exploration Agency (JAXA).md\|Rocket Lab Schedules First Dedicated Launch for Japan Aerospace Exploration Agency (JAXA)]]                             | November 24, 2025 |
| [[News/Rocket Lab Secures Multiple Launches with Japan Aerospace Exploration Agency (JAXA).md\|Rocket Lab Secures Multiple Launches with Japan Aerospace Exploration Agency (JAXA)]]                                         | October 10, 2025  |

%%DATAVIEW_PUBLISHER: end %%