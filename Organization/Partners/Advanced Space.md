---
name: Advanced Space
website: https://advancedspace.com/
---

>[!summary]
Advanced Space is a Colorado-based company specializing in mission design, navigation, and operations for space exploration, with a focus on cislunar and deep space missions. Known for their expertise in orbital dynamics and spacecraft navigation, Advanced Space supports commercial and government clients, including NASA. They are notably the operator of the CAPSTONE mission (Cislunar Autonomous Positioning System Technology Operations and Navigation Experiment), a pathfinding CubeSat mission to the Moon that demonstrates navigation technology for the Gateway program in NASA's Artemis initiative. The company aims to advance the use of innovative technologies for sustainable space exploration.

## 🛰️ Space Systems

### CAPSTONE

CAPSTONE will be the first satellite to operate in a Near Rectilinear Halo Orbit around the Moon. CAPSTONE aims to reduce risk and validate operational concepts for future missions using the same lunar orbit.

In this orbit, CAPSTONE will orbit together with the Moon as it orbits Earth and will pass as close as 1600km and as far as 70000km from the lunar surface. About the size of a microwave oven, this 25kg satellite has an onboard communications system capable of determining how far CAPSTONE is from NASA’s Lunar Reconnaissance Orbiter and how fast the distance between the two spacecraft is changing. This inter-spacecraft information will be used to demonstrate the software for autonomous navigation, CAPS, that, when fully demonstrated, will enable future missions to determine their location without having to rely exclusively on tracking from Earth.

![[capstone_05-19jan22_0_0.webp]]

## 🚀 Launches

```dataview
table launch_date, outcome
from "Launch/Launches"
where contains(customer, [[Advanced Space]])
sort launch_date desc
```

## 📰 News
```dataview
table title as "Title", published as "Published"
from "News"
where contains(customer, [[Advanced Space]])
sort published desc
```

