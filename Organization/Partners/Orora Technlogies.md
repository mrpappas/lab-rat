---
name: Orora Technologies
website: https://ororatech.com/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> Orora Technlogies

Website: https://ororatech.com/

>[!summary]
>Orora Technologies, more commonly known as OroraTech, is a German company focused on developing a constellation of small satellites equipped with thermal infrared cameras to detect wildfires early and provide real-time monitoring for faster response, essentially creating a global wildfire warning system using space-based technology; their primary product is called the "Wildfire Solution."
>
>[More info on Orora's constellation here](http://gsics.atmos.umd.edu/pub/Development/LunarCalibrationWS2023/4j_Rio%20Fernandes_OroraTech.pdf)
>
>Orora currently uses Spire Global's [[Spire Global#Space Systems#Lemur-2|Lemur-2]] CubeSat platform as the basis for their satellites and in parallel they are working directly with [[ESA]] to develop their own satellite bus and complete solution


## 🚀 Launches
%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[Orora Technlogies]])
sort launch_date desc
```
%%

| File                                                                                              | Date             | Location                                              | Vehicle                          | Orbit & Mass             | Outcome   |
| ------------------------------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ------------------------ | --------- |
| [[Launch/Launches/063 - Finding Hot Wildfires Near You.md\|063 - Finding Hot Wildfires Near You]] | 2025-03-26 15:30 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 550 km \| 97° \| Unknown | ✅ Success |

%%DATAVIEW_PUBLISHER: end %%

## 🛰️ Space Systems

### OTC-P1

**OTC-P1 (OroraTech Constellation Phase 1)** is a wildfire detection constellation. The satellites are based on a modified version of[ Spire Global's Lemur platform](https://spire.com/space-services/lemur-space-platform/) (8U variant). Each one carrying OroraTech’s [SAFIRE GEN 2](https://earth.esa.int/eogateway/documents/20142/4139742/2.07_VH-RODA%202022%20-%20Thermal-IR%20Wildfire%20detection%20-%20DRFernandes.pdf), a unique and proprietary thermal-infrared camera (developed in partnership with [Kampf Telescope Optics](https://www.ktoptics.de/)) and a data processing unit designed to detect fires and transmit the data using [[Spire Global]]’s satellite and ground network. The technology will help identify and monitor the areas at risk of wildfires and enable early detection of wildfire hotspots.

| Spec            | Value             |
| --------------- | ----------------- |
| Application     | Earth Observation |
| GSD             | 200 m             |
| Swath           | 410 km            |
| Detector NEdT   | <50mK             |
| Acuisition Mode | Continuous        |

![[Pasted image 20250122180814.png]]

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[Orora Technlogies]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                                                               | Published        |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- |
| [[News/Rocket Lab Successfully Launches Mission for Global Wildfire Detection Company OroraTech.md\|Rocket Lab Successfully Launches Mission for Global Wildfire Detection Company OroraTech]]                                                                                                     | March 26, 2025   |
| [[News/From Contract to Launch in Four Months Rocket Lab Schedules Electron Launch on a Rapid Turnaround for OroraTech Wildfire Detection Mission.md\|From Contract to Launch in Four Months Rocket Lab Schedules Electron Launch on a Rapid Turnaround for OroraTech Wildfire Detection Mission]] | March 18, 2025   |
| [[News/Rocket Lab to Launch Global Wildfire Detection and Monitoring Mission for OroraTech.md\|Rocket Lab to Launch Global Wildfire Detection and Monitoring Mission for OroraTech]]                                                                                                               | January 22, 2025 |

%%DATAVIEW_PUBLISHER: end %%