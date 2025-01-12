---
tags:
  - electron
  - launch
  - failure
  - anomaly
mission_name: "We Will Never Desert You"
launch_date: 2023-09-19 06:55
outcome: "Failure"
customer: "[[Capella Space]]"
location: "[[Launch Complex 1]]"
vehicle: "[[Electron]]"
orbit_type: "[[🌍 Orbits#LEO]]"
target_orbit: 640 km | 53°
payload_mass: 165 kg
recovery: No Attempt
mission_link: https://www.rocketlabusa.com/missions/missions-launched/we-will-never-desert-you/
---

>[!Failure] Mission Failure

>[!summary]
Launched on September 19, 2023, from Launch Complex 1 in New Zealand, the ‘We Will Never Desert You’ mission was Rocket Lab's 41st Electron launch. The mission was launched to deploy a synthetic aperture radar (SAR) Earth imaging Acadia satellite for Capella Space, but Electron experienced an anomaly at stage two ignition, resulting in the loss of the mission. 
>
Anomaly occurred 2 minutes 30 seconds into the flight.
>
"The cause of the anomaly is a highly complex set of conditions that are extremely difficult to replicate in testing. However, we believe the findings of the Rocket Lab investigation team overwhelmingly indicate that an electrical arc occurred within the power supply system that provides high voltage to the Rutherford engine’s motor controllers, shorting the battery packs which provide power to the launch vehicle’s upper stage."
[Source](https://www.businesswire.com/news/home/20231108450544/en/Rocket-Lab-Announces-Third-Quarter-2023-Financial-Results-Issues-Guidance-For-Fourth-Quarter-2023-and-Revenue-Guidance-for-First-Quarter-2024)
>
[📸 Mission Photo Album](https://www.flickr.com/photos/rocketlab/albums/72177720311276483/)

### 📦 Payload

x1 [[Capella Space#🛰️ Space Systems#Acadia|Acadia SAR]] Satellite

## 📰 News
```dataview
table published as "Published"
from "News"
where contains(mission, [[041 'We Will Never Desert You' - Electron]])
sort published desc
```

## 📽️ Launch Video

<iframe width="800" height="450" src="https://www.youtube.com/embed/AfYFqsk_NGk" title="Rocket Lab&#39;s Electron - We Will Never Desert You Mission" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>     

## ✏️ Notes


This anomaly delayed all Electron launches for ~3 months.

**Findings for the cause of the anomaly:** 

Exhaustive testing and analysis to recreate this failure mode has led to the investigation team’s determination that the arc was likely only made possible by the rare interaction of multiple conditions. Any one of these factors on their own would likely not have caused the failure of the second stage, but when they occur simultaneously in the low-pressure environment of space, they reach the threshold dictated by Paschen’s Law for an arc to form and travel. Paschen's Law is an equation that breaks down the relationship between voltage, pressure environment, distance between electrodes, and presence of gas necessary for an electrical arc to form and travel.

Three rare conditions had to present simultaneously in the low-pressure space environment to reach the threshold for arcing under [Paschen’s Law](https://en.wikipedia.org/wiki/Paschen%27s_law), including:
- A superimposed alternating current (AC) with the direct current (DC) high-voltage electricity provided to the stage’s power supply system, that is produced as a ripple voltage from the system’s engine motor controllers;
- A small concentration of helium and nitrogen gasses that were present within the interstage between Electron’s first and second stages; and
- An imperceptible fault in the insulation of the high voltage loom within the power supply system.

Source: [[Rocket Lab Sets Next Electron Launch Window, Provides Update on Anomaly Review]]


## 🎙️ Press Kit

![[FINAL-Capella-We-Will-Never-Desert-You-Press-Kit.pdf]]