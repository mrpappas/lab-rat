---
name: Astroscale-Japan
website: https://astroscale.com/
---

>[!summary]
Astroscale-Japan is a subsidiary of Astroscale Holdings, a company dedicated to addressing space sustainability by providing on-orbit servicing solutions. Focused on debris removal, satellite life extension, and end-of-life services, Astroscale develops technologies to clean up existing space debris and ensure responsible satellite deorbiting. The company’s missions, such as *ELSA-d* (End-of-Life Services by Astroscale-demonstration) and *ADRAS-J* (Active Debris Removal by Astroscale-Japan), demonstrate capabilities in docking with, capturing, and deorbiting defunct satellites and debris to maintain a sustainable space environment.

## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Astroscale-Japan]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Astroscale-Japan]])
sort published desc
```

---
## ✏️ Notes

-  https://arstechnica.com/space/2024/08/there-are-2000-plus-dead-rockets-in-orbit-heres-a-rare-view-of-one-of-them/