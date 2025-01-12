---
name: Synspective
website: https://synspective.com/
---


>[!summary]
Synspective is a Japanese startup that develops and operates [[📦 Payload Types#Synthetic Aperture Radar (SAR)|Synthetic Aperture Radar (SAR)]] satellites to provide high-frequency, high-resolution Earth observation data. The company’s mission is to enable smarter decision-making through precise geospatial insights, focusing on areas such as urban development, disaster response, infrastructure monitoring, and resource management. By leveraging its constellation of SAR satellites, Synspective delivers consistent, cloud-penetrating imagery, ensuring reliable data regardless of weather or lighting conditions. Its solutions support governments and businesses in addressing global challenges through advanced analytics and actionable intelligence.


### 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Synspective]])
sort launch_date desc
```


## 🛰️ Space Systems

### StriX

Synspective's StriX satellites are a series of small, innovative, and cost-effective [[📦 Payload Types#Synthetic Aperture Radar (SAR)|Synthetic Aperture Radar (SAR)]] satellites designed for high-resolution Earth observation. Developed in collaboration with the University of Tokyo, the Tokyo Institute of Technology, and the Japan Aerospace Exploration Agency (JAXA), the StriX series originated from Japan's ImPACT Program, aiming to enhance information-gathering capabilities for emergency response and other applications.

[Synspective Strix](https://synspective.com/satellite/satellite-strix/)

| Mass                 | 100 kg                                                                                                |
| -------------------- | ----------------------------------------------------------------------------------------------------- |
| **Size**             | 0.8m × 1.0m × 0.8m<br>(Before antenna deployment)<br>5.0m × 1.0m × 0.8m<br>(After antenna deployment) |
| **Antenna Size**     | 5m × 0.8m                                                                                             |
| **Propulsion**       | Yes                                                                                                   |
| **Mission Life**     | Approximately 5 years                                                                                 |
| **Center Frequency** | 9.65 GHz (X-band)                                                                                     |
| **Look Direction**   | Right and Left                                                                                        |
| **PRF**              | Up to 7 kHz                                                                                           |
| **Chirp Bandwith**   | Up to 300 MHz                                                                                         |
| **RF Peak Power**    | 1kW                                                                                                   |
| **Polarization**     | VV                                                                                                    |
| **Off-Nadir Angle**  | 15 – 45 degrees                                                                                       |

Example use cases include:

- detecting anomalies in road, rail, energy and other infrastructure, resulting in lower maintenance costs and accident risk,
- monitoring crop growth conditions and analyzing soil and vegetation health to help reduce costs and increase efficiency for farmers,
- detecting illegal logging and fishing in the most remote parts of the world,
- providing rapid damage assessment after flooding, landslides and volcanic eruptions, as well as risk assessment for land subsidence,
- enabling the persistent monitoring of maritime traffic, border activities and other potential security threats, and advances maritime domain awareness,
- analyzing tree cover to calculate CO2 absorption and carbon credits.


![[Pasted image 20241224215520.png]]

---
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Synspective]])
sort published desc
```
