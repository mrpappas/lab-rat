---

name: Astrix Astronautics
website: https://astrix.space/
---

**Name:** Astrix Astronautics
**Website:** https://astrix.space/

>[!summary]
Astrix Astronautics is a New Zealand-based company specializing in innovative power systems for small satellites. The company focuses on developing high-performance solar arrays and deployable power solutions to maximize energy efficiency for small satellite platforms. Astrix's technology is designed to meet the growing power demands of modern satellite missions, supporting applications such as Earth observation, communications, and deep space exploration. Their systems enable increased satellite capabilities while maintaining a compact and lightweight form factor, catering to both commercial and government customers in the space industry.

## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[Astrix Astronautics]])
sort launch_date desc
```
%%

| File                                                                          | Date             | Location                                              | Vehicle                          | Orbit & Mass             | Outcome   |
| ----------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ------------------------ | --------- |
| [[Launch/Launches/026 - There And Back Again.md\|026 - There And Back Again]] | 2022-05-02 22:49 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 520 km \| 94° \| Unknown | ✅ Success |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[Astrix Astronautics]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                     | Published      |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- |
| [[News/Rocket Lab Successfully Deploys 34 Satellites and Catches Rocket Booster Returning from Space with Helicopter.md\|Rocket Lab Successfully Deploys 34 Satellites and Catches Rocket Booster Returning from Space with Helicopter]] | May 02, 2022   |
| [[News/Rocket Lab to Attempt First Mid-Air Helicopter Capture of the Electron Rocket During Next Mission.md\|Rocket Lab to Attempt First Mid-Air Helicopter Capture of the Electron Rocket During Next Mission]]                         | April 06, 2022 |

%%DATAVIEW_PUBLISHER: end %%