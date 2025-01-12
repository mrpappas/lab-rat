---
name: Melbourne Space Program
website: https://www.melbournespace.com.au/
---

>[!summary]
The Melbourne Space Program is a non-profit organization based in Melbourne, Australia, focused on student-led satellite development and hands-on space systems education. Their key achievements include the ACRUX-1 CubeSat, launched in June 2019 aboard a Rocket Lab Electron, as a demonstration of satellite design and deployment capabilities. Future missions, such as ACRUX-2, aim to build on this success. The program emphasizes practical training in space engineering and systems development for students and early-career professionals.

### 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Melbourne Space Program]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Melbourne Space Program]])
sort published desc
```

## ✏️ Notes

- Future ACRUX-2 project: https://www.melbournespace.com.au/projects