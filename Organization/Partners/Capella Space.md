---

name: Capella Space
website: https://www.capellaspace.com/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> Capella Space

**Website:** https://www.capellaspace.com/

>[!summary]
Capella Space is an American space tech company with data and satellite solutions for government and commercial use. A pioneer in the Earth observation industry, Capella is the first U.S. company with a constellation of [[📦 Payload Types#Synthetic Aperture Radar (SAR)|Synthetic Aperture Rader (SAR)]] satellites, delivering the best quality, highest resolution SAR imagery commercially available. Capella provides easy access to frequent and timely information affecting dozens of industries worldwide, including defense and intelligence, supply chain, insurance, maritime and others. Its market-leading SAR satellites are matched with unparalleled data infrastructure to quickly deliver reliable global insights that sharpen our understanding of the changing world – improving decisions about commerce, conservation, and security on Earth. Headquartered in San Francisco, California with additional locations in Denver, Colorado and Washington, D.C., Capella's satellites are operated, designed, and manufactured in the USA.

## 🛰️ Space Systems

### Acadia

The Acadia satellites are part of [[Capella Space]]'s [[📦 Payload Types#Synthetic Aperture Radar (SAR)|Synthetic Aperture Radar (SAR)]] satellite constellation, designed for high-resolution Earth observation. These satellites provide detailed imaging capabilities regardless of weather or lighting conditions, supporting applications in defense, agriculture, infrastructure monitoring, and environmental analysis.

Features: 
- 3.5-meter mesh-based reflector antenna and 1000 W amplifier ensure high-contrast, low-noise imagery.
- 1.2 Gbps Data Downlink
- Up to 10 minutes of imaging time per orbit

[Capella Space SAR](https://www.capellaspace.com/technology)

[eoPortal Link](https://www.eoportal.org/satellite-missions/capella-x-sar)

| Mass             | 165 kg             |
| ---------------- | ------------------ |
| Antenna Size     | 3.5m Diameter      |
| Propulsion       | Yes                |
| Mission Life     | 3 Years            |
| Center Frequency | 9.65 GHz (X-band)  |
| Chirp Bandwidth  | 500 MHz to 700 MHz |
| RF Peak Power    | Unknown            |
| Polarization     | VV or HH (single)  |

![[Pasted image 20241225001756.jpg]]

## 🚀 Launches


%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[Capella Space]])
sort launch_date desc
```
%%

| File                                                                                                  | Date             | Location                                               | Vehicle                          | Orbit & Mass            | Outcome |
| ----------------------------------------------------------------------------------------------------- | ---------------- | ------------------------------------------------------ | -------------------------------- | ----------------------- | ------- |
| [[Launch/Launches/052 - A Sky Full Of SARs.md\|052 - A Sky Full Of SARs]]                             | 2024-08-11 13:18 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]]  | [[Launch/Electron.md\|Electron]] | 615 km \| 53° \| 165 kg | ✅       |
| [[Launch/Launches/041 - We Will Never Desert You.md\|041 - We Will Never Desert You]]                 | 2023-09-19 06:55 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]]  | [[Launch/Electron.md\|Electron]] | 640 km \| 53° \| 165 kg | ❌       |
| [[Launch/Launches/040 - We Love The Nightlife.md\|040 - We Love The Nightlife]]                       | 2023-08-24 23:45 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]]  | [[Launch/Electron.md\|Electron]] | 640 km \| 53° \| 165 kg | ✅       |
| [[Launch/Launches/034 - Stronger Together.md\|034 - Stronger Together]]                               | 2023-03-16 22:38 | [[Locations/Launch Complex 2.md#Launch Pad 0C\|LC2-0]] | [[Launch/Electron.md\|Electron]] | 600 km \| 44° \| 224 kg | ✅       |
| [[Launch/Launches/014 - I Can't Believe It's Not Optical.md\|014 - I Can't Believe It's Not Optical]] | 2020-08-31 03:05 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]]  | [[Launch/Electron.md\|Electron]] | 500 km \| 45° \| 100 kg | ✅       |

%%DATAVIEW_PUBLISHER: end %%


## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[Capella Space]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                   | Published          |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------ |
| [[News/Rocket Lab Schedules Next Electron Launch Just Eight Days After Previous Mission.md\|Rocket Lab Schedules Next Electron Launch Just Eight Days After Previous Mission]]                                                                         | August 07, 2024    |
| [[News/Rocket Lab Launch Update.md\|Rocket Lab Launch Update]]                                                                                                                                                                                         | July 18, 2024      |
| [[News/Rocket Lab Sets Launch Window For Next Capella Space Mission From Launch Complex 1.md\|Rocket Lab Sets Launch Window For Next Capella Space Mission From Launch Complex 1]]                                                                     | July 09, 2024      |
| [[News/Rocket Lab Sets Next Electron Launch Window, Provides Update on Anomaly Review.md\|Rocket Lab Sets Next Electron Launch Window, Provides Update on Anomaly Review]]                                                                             | November 08, 2023  |
| [[News/Rocket Lab Receives Federal Aviation Administration Authorization to Resume Launches.md\|Rocket Lab Receives Federal Aviation Administration Authorization to Resume Launches]]                                                                 | October 25, 2023   |
| [[News/Rocket Lab Launch Update (2).md\|Rocket Lab Launch Update (2)]]                                                                                                                                                                                 | September 19, 2023 |
| [[News/Rocket Lab Announces Launch Window for Next Capella Space Mission.md\|Rocket Lab Announces Launch Window for Next Capella Space Mission]]                                                                                                       | September 07, 2023 |
| [[News/Rocket Lab Launches 40th Electron Mission, Successfully Flies Reused Engine.md\|Rocket Lab Launches 40th Electron Mission, Successfully Flies Reused Engine]]                                                                                   | August 24, 2023    |
| [[News/Rocket Lab Brings Forward Milestone Recovery Mission.md\|Rocket Lab Brings Forward Milestone Recovery Mission]]                                                                                                                                 | August 23, 2023    |
| [[News/Rocket Lab Announces Launch Window for Next Mission in Multi-Launch Contract for Capella Space.md\|Rocket Lab Announces Launch Window for Next Mission in Multi-Launch Contract for Capella Space]]                                             | July 20, 2023      |
| [[News/Rocket Lab Successfully Launches 34th Electron Rocket, Second Mission from Virginia.md\|Rocket Lab Successfully Launches 34th Electron Rocket, Second Mission from Virginia]]                                                                   | March 16, 2023     |
| [[News/Rocket Lab Announces Launch Window for Second Electron Mission from Virginia.md\|Rocket Lab Announces Launch Window for Second Electron Mission from Virginia]]                                                                                 | March 07, 2023     |
| [[News/Rocket Lab Plans Two Launches Days Apart From Two Continents.md\|Rocket Lab Plans Two Launches Days Apart From Two Continents]]                                                                                                                 | February 28, 2023  |
| [[News/Rocket Lab Signs Multi-Launch Deal to Deploy Satellite Constellation for Capella Space.md\|Rocket Lab Signs Multi-Launch Deal to Deploy Satellite Constellation for Capella Space]]                                                             | February 28, 2023  |
| [[News/Rocket Lab Launches First In-house Designed & Built Photon Satellite.md\|Rocket Lab Launches First In-house Designed & Built Photon Satellite]]                                                                                                 | September 03, 2020 |
| [[News/Rocket Lab Successfully Deploys Satellite for Capella Space on 14th Mission.md\|Rocket Lab Successfully Deploys Satellite for Capella Space on 14th Mission]]                                                                                   | August 31, 2020    |
| [[News/Capella Space and Rocket Lab to Launch Mid-Inclination Satellite to Enable Improved Monitoring of Key Global Regions.md\|Capella Space and Rocket Lab to Launch Mid-Inclination Satellite to Enable Improved Monitoring of Key Global Regions]] | March 05, 2020     |

%%DATAVIEW_PUBLISHER: end %%