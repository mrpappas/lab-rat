---
name: Kinéis
website: https://www.kineis.com/en/spatial-iot-connectivity/
---

>[!summary]
**Kinéis** is a French company specializing in **[[📦 Payload Types#Internet of Things (IoT)|Internet of Things (IoT)]]** connectivity through satellite technology. The company operates a constellation of nanosatellites designed to provide global IoT connectivity, enabling devices in remote or inaccessible locations to transmit data. 
>
Born out of the **[Argos system](https://en.wikipedia.org/wiki/Argos_(satellite_system))**, a pioneering satellite-based environmental monitoring service developed in partnership with [[CNES]] (the French Space Agency), Kinéis aims to expand and modernize this system. The company is building a **25-satellite constellation**, which will improve coverage, increase data transmission capabilities, and offer real-time connectivity for industries such as maritime, agriculture, logistics, and environmental monitoring.
>
Kinéis positions itself as a key player in the growing IoT space market, offering cost-effective and energy-efficient solutions for global data collection and transmission.

### 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Kinéis]])
sort launch_date desc
```

## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Kinéis]])
sort published desc
```

## 🛰️ Space Systems

### Kinéis IoT

The Kinéis IoT satellites are a constellation of advanced nanosatellites designed to provide seamless global connectivity for [[📦 Payload Types#Internet of Things (IoT)|Internet of Things (IoT)]] devices. Each satellite, weighing approximately 30 kg, operates in low Earth orbit (LEO) at an altitude of around 650 km, enabling low-latency and cost-efficient communication. Leveraging UHF (401-406 MHz) and AIS frequencies, these satellites support two-way communication for IoT applications and real-time maritime tracking. With an expected operational life of 7 years, the Kinéis constellation integrates deployable antennas, high-capacity batteries, and robust onboard systems to ensure reliable data collection and transmission in diverse environments. Applications span environmental monitoring, precision agriculture, logistics, smart cities, and maritime safety, making Kinéis a cornerstone for scalable and efficient satellite-based IoT solutions.

| Mass         | 30 kg         |
| ------------ | ------------- |
| Size         | 1.40m x 1.60m |
| Propulsion   | No            |
| Mission Life | 7 Years       |
| Frequency    | UHF, AIS      |

![[Pasted image 20241224231429.jpg]]

## ✏️ Notes

Kinéis currently operates the [Argos System](https://en.wikipedia.org/wiki/Argos_(satellite_system)), an international scientific collaboration between [[CNES]], the National Oceanic and Atmospheric Administration (NOAA), the European Organization for the Exploitation of Meteorological Satellites (EUMETSAT) and the Indian Space Research Organization (ISRO), to monitor wildlife, fisheries, and to collect data about Earth’s climate and environment through CLS. Kinéis’ new constellation will complete the current system with more powerful 30kg-class nanosats that integrate IoT technology and a ship-tracking Automatic Identification System (AIS). Once deployed, this technology will allow Kinéis to expand across multiple industries and scale from 20,000 devices connected to millions.

