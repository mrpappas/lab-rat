---

name: Spire Global
website: https://spire.com/
---

**Name:** Spire Global
**Website:** https://spire.com/

>[!summary]
**Spire Global** is a leading provider of **space-based data, analytics, and services**. The company operates a constellation of **CubeSats** that collect data for global maritime, aviation, and weather tracking. By leveraging its extensive satellite network, Spire delivers real-time insights and predictive analytics to industries like logistics, climate monitoring, defense, and telecommunications. Its **multi-purpose satellites** enable businesses and governments to make informed decisions through data on **ship movements, flight paths, atmospheric conditions, and asset tracking**. 


## 🚀 Launches

%%DATAVIEW_PUBLISHER: start
```
table location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[Spire Global]])
sort launch_date desc
```
%%

| File                                                                      | Location                                              | Vehicle                          | Orbit & Mass               | Outcome   |
| ------------------------------------------------------------------------- | ----------------------------------------------------- | -------------------------------- | -------------------------- | --------- |
| [[Launch/Launches/043 'Four Of A Kind'.md\|043 'Four Of A Kind']]         | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 530 km \| 97° \| 112 kg    | ✅ Success |
| [[Launch/Launches/039 'Baby Come Back'.md\|039 'Baby Come Back']]         | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Launch/Electron.md\|Electron]] | 1000 km \| 99.45° \| 86 kg | ✅ Success |
| [[Launch/Launches/003 'It's Business Time'.md\|003 'It's Business Time']] | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 500 km \| 85° \| 45 kg     | ✅ Success |
| [[Launch/Launches/002 'Still Testing'.md\|002 'Still Testing']]           | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Launch/Electron.md\|Electron]] | 400 km \| 82.9° \| 13 kg   | ✅ Success |

%%DATAVIEW_PUBLISHER: end %%

## Space Systems

### Lemur-2

(add Lemur-2 data here)

## 📰 News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[Spire Global]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                       | Published         |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| [[News/Rocket Lab Successfully Launches First Electron Mission of Busy 2024 Launch Schedule.md\|Rocket Lab Successfully Launches First Electron Mission of Busy 2024 Launch Schedule]]                                                                     | January 31, 2024  |
| [[News/Rocket Lab to Launch Space Situational Awareness Mission for Spire and NorthStar.md\|Rocket Lab to Launch Space Situational Awareness Mission for Spire and NorthStar]]                                                                             | January 08, 2024  |
| [[News/Rocket Lab Deploys Satellites for NASA and Commercial Constellation Operators,  Successfully Recovers Booster.md\|Rocket Lab Deploys Satellites for NASA and Commercial Constellation Operators,  Successfully Recovers Booster]]                   | July 17, 2023     |
| [[News/Rocket Lab Prepares to Launch Mix of NASA and Commercial Satellites, and Takes Next Step in Rocket Reusability Program.md\|Rocket Lab Prepares to Launch Mix of NASA and Commercial Satellites, and Takes Next Step in Rocket Reusability Program]] | July 17, 2023     |
| [[News/Rocket Lab to Launch Multiple Satellites as Part of Upcoming Recovery Mission.md\|Rocket Lab to Launch Multiple Satellites as Part of Upcoming Recovery Mission]]                                                                                   | June 22, 2023     |
| [[News/Rocket Lab to Launch Space Object Monitoring Mission For Spire Global & NorthStar.md\|Rocket Lab to Launch Space Object Monitoring Mission For Spire Global & NorthStar]]                                                                           | June 22, 2023     |
| [[News/Rocket Lab reaches orbit again, deploys more satellites.md\|Rocket Lab reaches orbit again, deploys more satellites]]                                                                                                                               | November 11, 2018 |
| [[News/Rocket Lab enters high frequency launch operations.md\|Rocket Lab enters high frequency launch operations]]                                                                                                                                         | October 30, 2018  |
| [[News/Rocket Lab to launch It’s Business Time and ELaNa XIX missions weeks apart.md\|Rocket Lab to launch It’s Business Time and ELaNa XIX missions weeks apart]]                                                                                         | August 06, 2018   |
| [[News/Rocket Lab confirms new ‘It’s Business Time’ launch window and bolsters manifest.md\|Rocket Lab confirms new ‘It’s Business Time’ launch window and bolsters manifest]]                                                                             | May 25, 2018      |
| [[News/Rocket Lab moves ‘It’s Business Time’ launch window.md\|Rocket Lab moves ‘It’s Business Time’ launch window]]                                                                                                                                       | April 17, 2018    |
| [[News/Rocket Lab 'Its Business Time' launch window to open 20 April 2018 NZT.md\|Rocket Lab 'Its Business Time' launch window to open 20 April 2018 NZT]]                                                                                                 | April 03, 2018    |
| [[News/It's Business Time at Rocket Lab.md\|It's Business Time at Rocket Lab]]                                                                                                                                                                             | March 13, 2018    |
| [[News/Rocket Lab successfully circularizes orbit with new Electron kick stage.md\|Rocket Lab successfully circularizes orbit with new Electron kick stage]]                                                                                               | January 23, 2018  |
| [[News/Rocket Lab successfully reaches orbit and deploys payloads.md\|Rocket Lab successfully reaches orbit and deploys payloads]]                                                                                                                         | January 21, 2018  |
| [[News/Rocket Lab to open ‘Still Testing’ launch window on January 20.md\|Rocket Lab to open ‘Still Testing’ launch window on January 20]]                                                                                                                 | January 12, 2018  |
| [[News/Rocket Lab delays ‘Still Testing’ launch attempt.md\|Rocket Lab delays ‘Still Testing’ launch attempt]]                                                                                                                                             | December 16, 2017 |
| [[News/Rocket Lab completes analysis of Still Testing launch abort.md\|Rocket Lab completes analysis of Still Testing launch abort]]                                                                                                                       | December 13, 2017 |
| [[News/Still Testing launch window begins.md\|Still Testing launch window begins]]                                                                                                                                                                         | December 11, 2017 |
| [[News/'Still Testing' Press Kit.md\|'Still Testing' Press Kit]]                                                                                                                                                                                           | November 30, 2017 |
| [[News/Rocket Lab Still Testing launch window announced.md\|Rocket Lab Still Testing launch window announced]]                                                                                                                                             | November 30, 2017 |
| [[News/Rocket Lab to fly Planet and Spire satellites on second test flight.md\|Rocket Lab to fly Planet and Spire satellites on second test flight]]                                                                                                       | November 22, 2017 |

%%DATAVIEW_PUBLISHER: end %%