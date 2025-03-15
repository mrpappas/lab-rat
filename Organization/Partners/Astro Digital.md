---

name: Astro Digital
website: https://astrodigital.com/
---

**Name:** Astro Digital
**Website:** https://astrodigital.com/

>[!summary]
Astro Digital is a satellite manufacturer and operator specializing in delivering turnkey solutions for Earth observation, communications, and data analytics. The company focuses on designing, building, and operating small satellite systems to provide rapid access to data for commercial and government customers. Astro Digital offers customizable platforms for satellite missions, including payload integration, mission operations, and ground support. Known for its flexible approach, the company serves clients requiring Earth imagery, environmental monitoring, and IoT data transmission.

## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[Astro Digital]])
sort launch_date desc
```
%%

| File                                                                    | Date             | Location                                              | Vehicle                          | Orbit & Mass              | Outcome   |
| ----------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ------------------------- | --------- |
| [[Launch/Launches/009 'As The Crow Flies'.md\|009 'As The Crow Flies']] | 2019-10-17 01:22 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 1200 km \| 87.9° \| 20 kg | ✅ Success |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[Astro Digital]])
sort published desc
```
%%

| File                                                                                                                                                                                                     | Published          |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ |
| [[News/Rocket Lab successfully launches ninth Electron mission, deploys payload to highest orbit yet.md\|Rocket Lab successfully launches ninth Electron mission, deploys payload to highest orbit yet]] | October 17, 2019   |
| [[News/Rocket Lab to launch dedicated mission for Astro Digital.md\|Rocket Lab to launch dedicated mission for Astro Digital]]                                                                           | September 30, 2019 |

%%DATAVIEW_PUBLISHER: end %%