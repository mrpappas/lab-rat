---

name: National Reconnaissance Office (NRO)
website: https://www.nro.gov/
---

**Name:** National Reconnaissance Office (NRO)
**Website:** https://www.nro.gov/

>[!summary]
>The National Reconnaissance Office (NRO) is a U.S. government agency responsible for designing, building, and operating reconnaissance satellites to support national security. Established in 1961, the NRO plays a critical role in collecting intelligence for the Department of Defense, intelligence community, and policymakers, focusing on areas like threat assessment, military operations, and disaster response. It develops and manages cutting-edge satellite systems, leveraging advanced technologies to provide geospatial intelligence (GEOINT) and signals intelligence (SIGINT). The NRO works closely with agencies like the CIA, NSA, and U.S. Space Force, as well as commercial and international partners, ensuring the United States maintains a strategic advantage in space-based reconnaissance.
## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[National Reconnaissance Office (NRO)]])
sort launch_date desc
```
%%

| File                                                                          | Location                                               | Vehicle                          | Orbit & Mass                         | Outcome   |
| ----------------------------------------------------------------------------- | ------------------------------------------------------ | -------------------------------- | ------------------------------------ | --------- |
| [[Launch/Launches/046 'Live And Let Fly'.md\|046 'Live And Let Fly']]         | [[Locations/Launch Complex 2.md#Launch Pad 0C\|LC2-0]] | [[Launch/Electron.md\|Electron]] | Classified \| Classified             | ✅ Success |
| [[Launch/Launches/029 'Antipodean Adventure'.md\|029 'Antipodean Adventure']] | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]]  | [[Launch/Electron.md\|Electron]] | 620 km \| 70° \| Classified          | ✅ Success |
| [[Launch/Launches/028 'Wise One Looks Ahead'.md\|028 'Wise One Looks Ahead']] | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]]  | [[Launch/Electron.md\|Electron]] | 620 km \| 40° \| Classified          | ✅ Success |
| [[Launch/Launches/012 'Don't Stop Me Now'.md\|012 'Don't Stop Me Now']]       | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]]  | [[Launch/Electron.md\|Electron]] | 570 x 590 km \| 97.75° \| Classified | ✅ Success |
| [[Launch/Launches/011 'Birds of a Feather'.md\|011 'Birds of a Feather']]     | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]]  | [[Launch/Electron.md\|Electron]] | 400 km \| 37° \| Classified          | ✅ Success |

%%DATAVIEW_PUBLISHER: end %%

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[National Reconnaissance Office (NRO)]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                         | Published         |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/Rocket Lab Successfully Launches Fifth National Security Mission for NRO.md\|Rocket Lab Successfully Launches Fifth National Security Mission for NRO]]                                                                               | March 21, 2024    |
| [[News/Rocket Lab to Launch NRO Mission from Wallops, Virginia   Rocket Lab.md\|Rocket Lab to Launch NRO Mission from Wallops, Virginia   Rocket Lab]]                                                                                       | February 21, 2024 |
| [[News/Rocket Lab Successfully Launches Second of Two Back-to-Back National Reconnaissance Office Missions.md\|Rocket Lab Successfully Launches Second of Two Back-to-Back National Reconnaissance Office Missions]]                         | August 04, 2022   |
| [[News/Rocket Lab Readies National Security Launch for National Reconnaissance Office.md\|Rocket Lab Readies National Security Launch for National Reconnaissance Office]]                                                                   | July 28, 2022     |
| [[News/Rocket Lab Successfully Launches First of Two Responsive Space Missions for the  National Reconnaissance Office.md\|Rocket Lab Successfully Launches First of Two Responsive Space Missions for the  National Reconnaissance Office]] | July 13, 2022     |
| [[News/Rocket Lab to Launch Responsive Space Missions for National Reconnaissance Office.md\|Rocket Lab to Launch Responsive Space Missions for National Reconnaissance Office]]                                                             | July 05, 2022     |
| [[News/Rocket Lab’s Next Mission to Launch Satellites for NASA, NRO and the University of New South Wales.md\|Rocket Lab’s Next Mission to Launch Satellites for NASA, NRO and the University of New South Wales]]                           | March 09, 2020    |
| [[News/Rocket Lab Successfully Deploys NRO Satellite On 11th Electron Mission.md\|Rocket Lab Successfully Deploys NRO Satellite On 11th Electron Mission]]                                                                                   | January 31, 2020  |
| [[News/Rocket Lab To Launch National Reconnaissance Office Mission.md\|Rocket Lab To Launch National Reconnaissance Office Mission]]                                                                                                         | January 20, 2020  |

%%DATAVIEW_PUBLISHER: end %%