---

name: Valve
website: https://www.valvesoftware.com/en/
---

**Name:** Valve
**Website:** https://www.valvesoftware.com/en/

>[!summary]
Valve Corporation is a leading video game developer and digital distribution platform operator known for revolutionizing the gaming industry. As the creators of iconic titles like Half-Life, Portal, and Dota 2, Valve delivers immersive, high-quality gaming experiences. Beyond game development, Valve operates Steam, the world’s largest PC gaming platform, offering a vast library of games, community features, and digital storefront capabilities. Valve is also a pioneer in hardware and VR technology, developing products like the Steam Deck and the cutting-edge Valve Index VR system.


## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[Valve]])
sort launch_date desc
```
%%

| File                                                                  | Date             | Location                                              | Vehicle                          | Orbit & Mass              | Outcome   |
| --------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ------------------------- | --------- |
| [[Launch/Launches/016 'Return to Sender'.md\|016 'Return to Sender']] | 2020-11-20 02:20 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 500 km \| 97.3° \| 200 kg | ✅ Success |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[Valve]])
sort published desc
```
%%

| File                                                                                                                                   | Published         |
| -------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/How to bring a rocket back from space.md\|How to bring a rocket back from space]]                                               | November 30, 2020 |
| [[News/Rocket Lab Launches 16th Mission, Completes Booster Recovery.md\|Rocket Lab Launches 16th Mission, Completes Booster Recovery]] | November 22, 2020 |
| [[News/Rocket Lab to Attempt First Stage Recovery on Next Mission.md\|Rocket Lab to Attempt First Stage Recovery on Next Mission]]     | November 05, 2020 |
| [[News/Rocket Lab to Launch Most Diverse Mission Yet.md\|Rocket Lab to Launch Most Diverse Mission Yet]]                               | November 02, 2020 |

%%DATAVIEW_PUBLISHER: end %%