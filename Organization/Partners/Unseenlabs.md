---
name: Unseenlabs
website: https://unseenlabs.space/
---

>[!summary]
**Unseenlabs** is a French company specializing in **space-based radio frequency (RF) detection and geolocation**. Leveraging its constellation of **nanosatellites** in low Earth orbit (LEO), Unseenlabs provides **maritime surveillance** services by detecting and geolocating RF signals emitted by ships, even those operating with their **Automatic Identification System (AIS) turned off**. 
>
>The company's technology is particularly valuable for **tracking illegal activities**, such as smuggling, piracy, and unregulated fishing, offering critical insights for governments, defense organizations, and maritime operators. Unseenlabs' services support **global maritime security** with high-precision, real-time data, reinforcing transparency and safety across the world’s oceans.


## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Unseenlabs]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Unseenlabs]])
sort published desc
```

---
## ✏️ Notes

 - On April 29 2024 **Unseen Labs** announced their next-gen satellite constellation, planned to be launched in 2026. This new constellation would expand "its surveillance capabilities to include terrestrial and space environments in addition to maritime". This announcement was made shortly after they secured and €85 Million capital raise. 
   The new fleet would be compromised of 150-kg satellites, which is within [[Electron]]'s payload limitations. 
   **[Source: New Constellation](https://unseenlabs.space/2024/04/29/unseenlabs-announces-next-generation-satellite-constellation-for-2026-to-monitor-sea-land-and-space-environments-from-space/)**
   [**Source: Funding**](https://unseenlabs.space/2024/02/26/unseenlabs-announces-a-record-breaking-fundraising-of-e85-million/)

![[Pasted image 20241216213713.png]]