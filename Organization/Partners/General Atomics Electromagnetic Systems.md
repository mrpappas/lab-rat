---
name: General Atomics Electromagnetic Systems
website: https://www.ga.com/about/ems
---


>[!summary]
General Atomics Electromagnetic Systems (GA-EMS) designs and manufactures advanced technology solutions, including electromagnetic launch and power systems, space systems, and missile defense technologies. GA-EMS supports defense, aerospace, and commercial markets with innovations such as railguns, directed energy systems, satellite platforms, and components like spacecraft structures, payloads, and propulsion systems. The company plays a key role in space-based surveillance, satellite manufacturing, and national security programs.


### 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[General Atomics Electromagnetic Systems]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[General Atomics Electromagnetic Systems]])
sort published desc
```

## 🛰️ Space Systems

### GAzelle

**Payload**: [[CNES#🛰️ Space Systems#Argos-4|Argos-4]] built by [[CNES]] for [[NOAA]]

GAzelle, formerly known as Orbital Test Bed 3, is a commercial satellite built and owned by General Atomics, which manufactured the spacecraft in Centennial, Colorado. The craft’s primary payload is a government-sponsored instrument called [[CNES#🛰️ Space Systems#Argos-4|Argos-4]] for [[NOAA]] and [[CNES]], the French space agency.

![[ARGOS-4 (1).jpg.webp]]