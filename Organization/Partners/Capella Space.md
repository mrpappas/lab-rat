---
name: Capella Space
website: https://www.capellaspace.com/
---


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

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Capella Space]])
sort launch_date desc
```

## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Capella Space]])
sort published desc
```
