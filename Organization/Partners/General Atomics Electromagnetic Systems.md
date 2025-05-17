---

name: General Atomics Electromagnetic Systems
website: https://www.ga.com/about/ems
---

**Name:** General Atomics Electromagnetic Systems
**Website:** https://www.ga.com/about/ems

>[!summary]
General Atomics Electromagnetic Systems (GA-EMS) designs and manufactures advanced technology solutions, including electromagnetic launch and power systems, space systems, and missile defense technologies. GA-EMS supports defense, aerospace, and commercial markets with innovations such as railguns, directed energy systems, satellite platforms, and components like spacecraft structures, payloads, and propulsion systems. The company plays a key role in space-based surveillance, satellite manufacturing, and national security programs.


## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[General Atomics Electromagnetic Systems]])
sort launch_date desc
```
%%

| File                                                                            | Date             | Location                                              | Vehicle                          | Orbit & Mass            | Outcome   |
| ------------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ----------------------- | --------- |
| [[Launch/Launches/031 - It Argos Up From Here.md\|031 - It Argos Up From Here]] | 2022-10-07 17:09 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 750 km \| 98° \| 118 kg | ✅ Success |

%%DATAVIEW_PUBLISHER: end %%


## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[General Atomics Electromagnetic Systems]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                             | Published          |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ |
| [[News/Rocket Lab Successfully Launches 31st Electron Rocket, Breaks Annual Launch Record.md\|Rocket Lab Successfully Launches 31st Electron Rocket, Breaks Annual Launch Record]]                                                                               | October 07, 2022   |
| [[News/Rocket Lab to Launch 31st Mission, Deploying Environmental Monitoring Satellite for General Atomics.md\|Rocket Lab to Launch 31st Mission, Deploying Environmental Monitoring Satellite for General Atomics]]                                             | October 04, 2022   |
| [[News/Rocket Lab to Launch NOAA-Supported Argos-4 Spacecraft for General Atomics to Support Environmental Monitoring from Space.md\|Rocket Lab to Launch NOAA-Supported Argos-4 Spacecraft for General Atomics to Support Environmental Monitoring from Space]] | September 19, 2022 |

%%DATAVIEW_PUBLISHER: end %%
## 🛰️ Space Systems

### GAzelle

**Payload**: [[CNES#🛰️ Space Systems#Argos-4|Argos-4]] built by [[CNES]] for [[NOAA]]

GAzelle, formerly known as Orbital Test Bed 3, is a commercial satellite built and owned by General Atomics, which manufactured the spacecraft in Centennial, Colorado. The craft’s primary payload is a government-sponsored instrument called [[CNES#🛰️ Space Systems#Argos-4|Argos-4]] for [[NOAA]] and [[CNES]], the French space agency.

![[ARGOS-4 (1).jpg.webp]]