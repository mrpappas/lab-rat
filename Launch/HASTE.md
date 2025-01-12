>[!summary]
Hypersonic Accelerator Suborbital Test Electron (HASTE) is a suborbital testbed launch vehicle derived from the Electron orbital rocket. HASTE provides flight test opportunities for hypersonic and suborbital system technology development. It successfully launched its first mission "Scout's Arrow" on 18 June 2023, for Leidos.
>
HASTE has a payload capacity of 700 kg (1,500 lb), double that of Electron. It can deploy payloads from 80 km (50 mi) altitude and higher. In 2024, two HASTE launches were planned. As of November 2023 Rocket Lab had contracted for at least six HASTE missions.
>
> 🚀 https://www.rocketlabusa.com/launch/haste/
>🔗 https://en.wikipedia.org/wiki/Rocket_Lab#HASTE_suborbital_rocket

## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(vehicle, [[HASTE]])
sort launch_date desc
```

## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(tags, "HASTE")
sort published desc
```

