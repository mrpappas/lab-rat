---

name: Myriota
website: https://myriota.com/
---

**Name:** Myriota
**Website:** https://myriota.com/

>[!summary]
Myriota is an Australian company specializing in low-power, direct-to-satellite IoT (Internet of Things) connectivity. Headquartered in Adelaide, Myriota provides affordable and efficient solutions for transmitting small amounts of data from remote sensors and devices via its satellite constellation.
>
Myriota’s technology enables industries such as agriculture, utilities, environmental monitoring, and asset tracking to connect devices globally without relying on traditional terrestrial infrastructure. Their system allows ultra-low-power communication, extending the life of IoT devices in remote locations for years on minimal energy.


## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[Myriota]])
sort launch_date desc
```
%%

| File                                                                      | Date             | Location                                              | Vehicle                          | Orbit & Mass                        | Outcome   |
| ------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ----------------------------------- | --------- |
| [[Launch/Launches/019 'They Go Up So Fast'.md\|019 'They Go Up So Fast']] | 2021-03-22 22:30 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 450 km and 550 km \| 45° \| Unknown | ✅ Success |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[Myriota]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                                           | Published         |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------- |
| [[News/Rocket Lab Successfully Launches 19th Electron, Deploys 100th Satellite.md\|Rocket Lab Successfully Launches 19th Electron, Deploys 100th Satellite]]                                                                                                                   | March 23, 2021    |
| [[News/Rocket Lab’s Next Mission to Launch 100th Satellite and Deploy Next-Generation Photon Spacecraft in Preparation for Moon Mission.md\|Rocket Lab’s Next Mission to Launch 100th Satellite and Deploy Next-Generation Photon Spacecraft in Preparation for Moon Mission]] | February 09, 2021 |

%%DATAVIEW_PUBLISHER: end %%