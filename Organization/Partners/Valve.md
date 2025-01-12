---
name: Valve
website: https://www.valvesoftware.com/en/
---


>[!summary]
Valve Corporation is a leading video game developer and digital distribution platform operator known for revolutionizing the gaming industry. As the creators of iconic titles like Half-Life, Portal, and Dota 2, Valve delivers immersive, high-quality gaming experiences. Beyond game development, Valve operates Steam, the world’s largest PC gaming platform, offering a vast library of games, community features, and digital storefront capabilities. Valve is also a pioneer in hardware and VR technology, developing products like the Steam Deck and the cutting-edge Valve Index VR system.


## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Valve]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Valve]])
sort published desc
```
