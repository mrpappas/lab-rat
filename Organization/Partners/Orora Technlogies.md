---
name: Orora Technologies
website: https://ororatech.com/
---
Name: Orora Technologies
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
table location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[Orora Technlogies]])
sort launch_date desc
```
%%

| File | Location | Vehicle | Orbit & Mass | Outcome |
| ---- | -------- | ------- | ------------ | ------- |

%%DATAVIEW_PUBLISHER: end %%

## 🛰️ Space Systems

### SAFIRE Gen 2

SAFIRE Gen 2 satellites are based on an enlarged 6U CubeSat version of [[Spire Global]]'s [[Spire Global#Space Systems#Lemur-2|Lemur-2]] cubesat and feature customized experiments additionally to the standard Lemur payload.
They carries OroraTech’s unique and proprietary thermal-infrared camera (developed in partnership with [Kampf Telescope Optics](https://www.ktoptics.de/))and data processing unit designed to detect fires and transmit the data using [[Spire Global]]’s satellite and ground network. The technology will help identify and monitor the areas at risk of wildfires and enable early detection of wildfire hotspots.

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

| File                                                                                                                                                                                 | Published        |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------- |
| [[News/Rocket Lab to Launch Global Wildfire Detection and Monitoring Mission for OroraTech.md\|Rocket Lab to Launch Global Wildfire Detection and Monitoring Mission for OroraTech]] | January 22, 2025 |

%%DATAVIEW_PUBLISHER: end %%