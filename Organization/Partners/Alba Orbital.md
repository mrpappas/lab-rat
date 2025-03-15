---

name: Alba Orbital
website: https://www.albaorbital.com/

---

**Name:** Alba Orbital
**Website:** https://www.albaorbital.com/

>[!summary]
Alba Orbital is a Scottish aerospace company specializing in the development and launch of PocketQube satellites, which are ultra-small satellites designed for cost-effective space access. The company provides end-to-end solutions, including satellite design, manufacturing, and integration, as well as launch services through partnerships with various rocket providers, including Rocket Lab. Alba Orbital has enabled a variety of missions, such as Earth observation, IoT connectivity, and technology demonstrations, leveraging its expertise in miniaturized satellite technology to democratize access to space for startups, universities, and research organizations.

## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[Alba Orbital]])
sort launch_date desc
```
%%

| File                                                                              | Location                                              | Vehicle                          | Orbit & Mass                 | Outcome   |
| --------------------------------------------------------------------------------- | ----------------------------------------------------- | -------------------------------- | ---------------------------- | --------- |
| [[Launch/Launches/026 'There And Back Again'.md\|026 'There And Back Again']]     | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 520 km \| 94° \| Unknown     | ✅ Success |
| [[Launch/Launches/010 'Running Out Of Fingers'.md\|010 'Running Out Of Fingers']] | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 385 x 400 km \| 97° \| 77 kg | ✅ Success |

%%DATAVIEW_PUBLISHER: end %%
## 📰 News

%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[Alba Orbital]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                     | Published         |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/Rocket Lab Successfully Deploys 34 Satellites and Catches Rocket Booster Returning from Space with Helicopter.md\|Rocket Lab Successfully Deploys 34 Satellites and Catches Rocket Booster Returning from Space with Helicopter]] | May 02, 2022      |
| [[News/Rocket Lab to Attempt First Mid-Air Helicopter Capture of the Electron Rocket During Next Mission.md\|Rocket Lab to Attempt First Mid-Air Helicopter Capture of the Electron Rocket During Next Mission]]                         | April 06, 2022    |
| [[News/Rocket Lab to Launch Four PocketQube Satellites for Alba Orbital.md\|Rocket Lab to Launch Four PocketQube Satellites for Alba Orbital]]                                                                                           | August 18, 2021   |
| [[News/Rocket Lab Debuts Fully Autonomous Flight Termination System.md\|Rocket Lab Debuts Fully Autonomous Flight Termination System]]                                                                                                   | December 09, 2019 |
| [[News/Rocket Lab launches milestone tenth mission, completes major success for reusable rocket program.md\|Rocket Lab launches milestone tenth mission, completes major success for reusable rocket program]]                           | December 06, 2019 |
| [[News/Next Generation Electron Booster on the Pad  for Rocket Lab’s 10th Mission.md\|Next Generation Electron Booster on the Pad  for Rocket Lab’s 10th Mission]]                                                                       | November 05, 2019 |

%%DATAVIEW_PUBLISHER: end %%