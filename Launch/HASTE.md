>[!summary]
Hypersonic Accelerator Suborbital Test Electron (HASTE) is a **suborbital testbed** launch vehicle derived from the Electron orbital rocket. HASTE provides flight test opportunities for hypersonic and suborbital system technology development. It successfully launched its first mission [[038 'Scout's Arrow' - HASTE]] on 18 June 2023, for [[Leidos]].
>
A **suborbital testbed** is a launch vehicle that reaches outer space but does not complete a full orbit around the Earth. Suborbital testbeds are used to develop hypersonic and suborbital system technologies.
>
HASTE has a payload capacity of 700 kg (1,540 lbs), double that of orbital [[Electron]]. It can deploy payloads from 80 km (50 mi) altitude and higher.
>
> 🚀 https://www.rocketlabusa.com/launch/haste/
>🔗 https://en.wikipedia.org/wiki/Rocket_Lab#HASTE_suborbital_rocket

![[Pasted image 20250112181533.jpg|450]]


| Payload Mass                    | ~700 kg / 1,540 lbs    |
| ------------------------------- | ---------------------- |
| **Payload Separation Velocity** | 3 km/sec to 7.5 km/sec |
| **Payload Separation Altitude** | 80 km +                |

## 🛠️ Configurations

### Air-Breathing
This configuration supports payloads such as [scramjet](https://en.wikipedia.org/wiki/Scramjet) or [ramjet](https://en.wikipedia.org/wiki/Ramjet) engines that operate by ingesting atmospheric air during flight. HASTE can deploy these payloads at specific altitudes and velocities to facilitate testing of air-breathing propulsion systems under realistic flight conditions. 
### Ballistic Re-entry
In this setup, HASTE delivers payloads on a suborbital trajectory that re-enters the Earth's atmosphere following a ballistic path. This is ideal for testing re-entry vehicles, heat shields, and other technologies that must withstand the high temperatures and pressures encountered during atmospheric re-entry. 
### Boost Glide
This configuration involves deploying payloads that glide unpowered after an initial boost phase, covering long distances at hypersonic speeds within the atmosphere. It's particularly useful for testing hypersonic glide vehicles and related technologies that require sustained high-speed atmospheric flight.

### Space-Based Applications
HASTE can also accommodate payloads intended for space-based experiments or technology demonstrations. While primarily a suborbital vehicle, its flexible design allows it to support missions that require brief exposure to space environments, enabling testing of space technologies without the need for full orbital insertion.

![[Pasted image 20250112183604.png]]
## ✏️ Notes

- HASTE currently only launches from [[Launch Complex 2]] with a maximum cadence of 12 per year. 
- CEO [[Peter Beck]] indicated Rocket Lab has plans to launch HASTE from launch sites other than [[Launch Complex 2]] but did not give a time frame. [Source](https://youtu.be/WAoYVU3pnXY?t=739)

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

