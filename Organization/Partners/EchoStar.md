---

name: EchoStar
website: https://www.echostar.com/
---
**Name**: EchoStar
**Website**: https://www.echostar.com/
**Ticker**: [SATS](https://finance.yahoo.com/quote/SATS/)

>[!summary]
>EchoStar Corporation is an American telecommunications company, specializing in satellite communication, wireless telecommunications, and internet services. Echostar also provides multichannel video programming and mobile services through its subsidiaries: [Boost Mobile](https://www.echostar.com/brands/boost-mobile), [Hughesnet](https://www.echostar.com/brands/hughesnet), [Hughes](https://www.echostar.com/brands/hughes), [DISH](https://www.echostar.com/brands/dish), and [Sling](https://www.echostar.com/brands/sling).
>
Originally establishing the Dish Network brand name in 1996, EchoStar later acquired Dish as a wholly-owned subsidiary in 2023.

## **Launches**

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[EchoStar]])
sort launch_date desc
```
%%

| File                                                                            | Date             | Location                                              | Vehicle                          | Orbit & Mass        | Outcome   |
| ------------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | -------------------------------- | ------------------- | --------- |
| [[Launch/Launches/067 - Symphony In The Stars.md\|067 - Symphony In The Stars]] | 2025-06-20 07:15 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC-1B]] | [[Launch/Electron.md\|Electron]] | 650 \| 96° \| 74 kg | ⌛ Pending |

%%DATAVIEW_PUBLISHER: end %%

## Space Systems

### Lyra Block-1

Lyra is an in-development S-Band constellation of [[🌍 Orbits#LEO|LEO]] satellites based on [[Astro Digital#Corvus-XL|Astro Digital's Corvus-XL]] bus, designed to deliver global Internet-of-Things(IoT), machine to machine (M2M), and other data services. Enabled with Lora protocol and support for 5G non-terrestrial network (NTN) services. “The EchoStar Lyra constellation will provide both a commercial platform for IoT services and a platform for ongoing development of our global S-band portfolio”([Source](https://www.linkedin.com/posts/hughesconnects_network-connectivity-satellite-activity-7041093850957783041-0EcL/?trk=public_profile_like_view)).

Gunter's Space: https://space.skyrocket.de/doc_sdat/lyra-block1.htm

![[Pasted image 20250621153815.jpg]]

| Specification      | Value                                                                              |
| ------------------ | ---------------------------------------------------------------------------------- |
| Mass               | 74 kg                                                                              |
| Operational Orbit  | 650 km \| 96°                                                                      |
| Manufacturer       | [Astro Digital](https://astrodigital.com/)                                         |
| Satellite Bus      | [[Astro Digital#Corvus-XL\| Corvus-XL]]                                            |
| Propulsion         | [Spaceware Micro](https://www.exotrail.com/product/spaceware) Hall effect thruster |
| Constellation Size | 28 (4 Block-1, 24 Block-2)                                                         |

## Owned & Leased Satellites

https://echostarsatelliteservices.com/satellites

### Ka-Band Satellites (Broadband, Internet)

| Satellite                                                                    | Position | Use Case                       | Owner/Leased        | Notes                       |
| ---------------------------------------------------------------------------- | -------- | ------------------------------ | ------------------- | --------------------------- |
| [EchoStar 9 / Galaxy 23](https://space.skyrocket.de/doc_sdat/echostar-9.htm) | 121° W   | DISH TV, video & data services | Owned               | Also carries Ka- and C-band |
| [EchoStar 105 / SES-11](https://space.skyrocket.de/doc_sdat/echostar-9.htm)  | 105° W   | DISH TV                        | **Leased from SES** | Joint payload with SES      |

### S-Band Satellites (IoT, MSS, NTN)

| Satellite                                                                        | Position | Use Case                               | Owner/Leased             | Notes                            |
| -------------------------------------------------------------------------------- | -------- | -------------------------------------- | ------------------------ | -------------------------------- |
| [Al Yah 3](https://space.skyrocket.de/doc_sdat/al-yah-3.htm)                     | 20° W    | Broadband in South America & Africa    | **Leased from Yahsat**   | Uses Ka-band beams               |
| [Telstar 19V VANTAGE](https://space.skyrocket.de/doc_sdat/telstar-19v.htm)       | 63° W    | HughesNet broadband in South America   | **Leased from Telesat**  | Shared high-throughput satellite |
| [EUTELSAT 65 West A](https://space.skyrocket.de/doc_sdat/eutelsat-65-west-a.htm) | 65° W    | Latin American services                | **Leased from Eutelsat** | Used for HTS Ka-band in Brazil   |
| [Jupiter 1 / EchoStar 17](https://space.skyrocket.de/doc_sdat/jupiter-1.htm)     | 107.1° W | HughesNet broadband (North America)    | Owned                    | GEO HTS                          |
| [Jupiter 2 / EchoStar 19](https://space.skyrocket.de/doc_sdat/jupiter-2.htm)     | 97.1° W  | HughesNet broadband (North America)    | Owned                    | GEO HTS                          |
| [Jupiter 3 / EchoStar 24](https://space.skyrocket.de/doc_sdat/jupiter-3.htm)     | 95° W    | HughesNet, enterprise, mobile backhaul | Owned                    | Launched 2023 (Falcon Heavy)     |

### S-Band Satellites (IoT, MSS, NTN)

| Satellite                                                            | Position | Use Case                               | Owner/Leased | Notes                                              |
| -------------------------------------------------------------------- | -------- | -------------------------------------- | ------------ | -------------------------------------------------- |
| [EchoStar XXI](https://space.skyrocket.de/doc_sdat/terrestar-1.htm)  | 10.25° E | S-band MSS for Europe (IoT, messaging) | Owned        | Also called **TerreStar-2**                        |
| [EUTELSAT 10A](https://space.skyrocket.de/doc_sdat/eutelsat-w2a.htm) | 10.25° E | Backup MSS S-band payload              | **Leased**   | Eutelsat W2A carries S-band payload for MSS trials |
| [Lyra Block-1](https://space.skyrocket.de/doc_sdat/lyra-block1.htm)  | 96° W    | S-band IoT, NTN                        | Owned        |                                                    |


## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[EchoStar]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                   | Published     |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| [[News/Rocket Lab Adds Two New Missions to 2025 Electron Launch Manifest, Schedules First Launch in Four Days’ Time.md\|Rocket Lab Adds Two New Missions to 2025 Electron Launch Manifest, Schedules First Launch in Four Days’ Time]] | June 16, 2025 |

%%DATAVIEW_PUBLISHER: end %%