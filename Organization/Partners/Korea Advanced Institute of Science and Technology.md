---

name: KAIST (Korea Advanced Institute of Science and Technology)
website: https://www.kaist.ac.kr/en/
---

**Name:** KAIST (Korea Advanced Institute of Science and Technology)
**Website:** https://www.kaist.ac.kr/en/

>[!summary]
The **Korea Advanced Institute of Science and Technology (KAIST)** is South Korea's leading research-oriented university, recognized for its advancements in science, engineering, and technology. In the space sector, KAIST is notable for its contributions to satellite development and space technology research. The university's **[Satellite Technology Research Center (SaTReC)](https://satrec.kaist.ac.kr/e_01_01.php)** has developed and launched several small satellites, including the **[KITSAT](https://en.wikipedia.org/wiki/KITSAT-1) series** and more advanced Earth observation satellites. These satellites support scientific research, technology demonstration, and space education.
>
KAIST collaborates with international partners and government agencies, playing a significant role in South Korea's space program by fostering innovation, talent development, and the deployment of cutting-edge space technologies.

## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[Korea Advanced Institute of Science and Technology]])
sort launch_date desc
```
%%

| File                                                                              | Date             | Location                                              | Vehicle                          | Orbit & Mass                                       | Outcome   |
| --------------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | -------------------------------------------------- | --------- |
| [[Launch/Launches/047 - Beginning Of The Swarm.md\|047 - Beginning Of The Swarm]] | 2024-04-23 22:00 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 520 km (Neonsat-1), 1,000 km (ACS3), 97° \| 115 kg | ✅ Success |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[Korea Advanced Institute of Science and Technology]])
sort published desc
```
%%

| File                                                                                                                                                                                                                               | Published         |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/Rocket Lab Successfully Deploys Satellites ~500km Apart to Separate Orbits  For KAIST and NASA  Rocket Lab.md\|Rocket Lab Successfully Deploys Satellites ~500km Apart to Separate Orbits  For KAIST and NASA  Rocket Lab]] | April 24, 2024    |
| [[News/Rocket Lab Prepares to Launch Mission for KAIST and NASA to Deploy Satellites to Two Separate Orbits.md\|Rocket Lab Prepares to Launch Mission for KAIST and NASA to Deploy Satellites to Two Separate Orbits]]             | April 01, 2024    |
| [[News/Rocket Lab Signs Deal to Launch South Korean Satellite.md\|Rocket Lab Signs Deal to Launch South Korean Satellite]]                                                                                                         | December 07, 2023 |

%%DATAVIEW_PUBLISHER: end %%