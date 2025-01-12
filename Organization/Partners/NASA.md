---
name: NASA
website: https://www.nasa.gov/
---

>[!summary]
NASA (National Aeronautics and Space Administration) is the United States government agency responsible for space exploration, scientific discovery, and aeronautics research. Established in 1958, NASA has been at the forefront of space exploration, including historic achievements like the Apollo Moon landings, the Mars rovers, and the Hubble Space Telescope. The agency conducts cutting-edge research to advance human understanding of the universe, Earth's climate, and aeronautics technologies. Key initiatives include the Artemis program, aiming to return humans to the Moon and prepare for Mars exploration, and the James Webb Space Telescope, revolutionizing astrophysics. NASA collaborates with international partners and private industry to expand the boundaries of space exploration and technology.
## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[NASA]])
sort launch_date desc
```
## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[NASA]])
sort published desc
```
