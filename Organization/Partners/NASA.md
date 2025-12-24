---
name: NASA
website: https://www.nasa.gov/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> NASA

**Website:** https://www.nasa.gov/

NASA (National Aeronautics and Space Administration) is the United States government agency responsible for space exploration, scientific discovery, and aeronautics research. Established in 1958, NASA has been at the forefront of space exploration, including historic achievements like the Apollo Moon landings, the Mars rovers, and the Hubble Space Telescope. The agency conducts cutting-edge research to advance human understanding of the universe, Earth's climate, and aeronautics technologies. Key initiatives include the Artemis program, aiming to return humans to the Moon and prepare for Mars exploration, and the James Webb Space Telescope, revolutionizing astrophysics. NASA collaborates with international partners and private industry to expand the boundaries of space exploration and technology.

![[Pasted image 20251211021256.jpg]]

## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[]])
sort launch_date desc
```
%%

| File                                                                                      | Date             | Location                                              | Vehicle                                                 | Orbit & Mass                                       | Outcome |
| ----------------------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------- | ------------------------------------------------------- | -------------------------------------------------- | ------- |
| [[Launch/Launches/049 - PREFIRE and ICE.md\|049 - PREFIRE and ICE]]                       | 2024-06-05 03:15 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 525 km \| 97.5° \| 15 kg                           | ✅       |
| [[Launch/Launches/048 - Ready, Aim, Prefire.md\|048 - Ready, Aim, Prefire]]               | 2024-05-25 07:15 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 525 km \| 97.5° \| 15 kg                           | ✅       |
| [[Launch/Launches/047 - Beginning Of The Swarm.md\|047 - Beginning Of The Swarm]]         | 2024-04-23 22:00 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 520 km (Neonsat-1), 1,000 km (ACS3), 97° \| 115 kg | ✅       |
| [[Launch/Launches/039 - Baby Come Back.md\|039 - Baby Come Back]]                         | 2023-07-18 01:27 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 1000 km \| 99.45° \| 86 kg                         | ✅       |
| [[Launch/Launches/037 - Coming To A Storm Near You.md\|037 - Coming To A Storm Near You]] | 2023-05-26 03:46 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 550 km \| 32° \| 10 kg                             | ✅       |
| [[Launch/Launches/036 - Rocket Like A Hurricane.md\|036 - Rocket Like A Hurricane]]       | 2023-05-08 01:00 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 550 km \| 32° \| 10 kg                             | ✅       |
| [[Launch/Launches/027 - CAPSTONE.md\|027 - CAPSTONE]]                                     | 2022-06-28 09:55 | [[Locations/Launch Complex 1.md#Launch Pad B\|LC1-B]] | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | Translunar Injection (TLI) \| 320kg LEO / 80kg TLI | ✅       |
| [[Launch/Launches/012 - Don't Stop Me Now.md\|012 - Don't Stop Me Now]]                   | 2020-06-13 05:12 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 570 x 590 km \| 97.75° \| Classified               | ✅       |
| [[Launch/Launches/004 - NASA ELaNa-19.md\|004 - NASA ELaNa-19]]                           | 2018-12-16 06:33 | [[Locations/Launch Complex 1.md#Launch Pad A\|LC1-A]] | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 500 km \| 85° \| 78 kg                             | ✅       |

%%DATAVIEW_PUBLISHER: end %%

## Missions

 - [[ESCAPADE]]
 - [[GLIDE]]
 - [[NOAA SWFO-L1]]

## News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[]])
sort published desc
```
%%

| File                                                                                                                                                                                                                                                             | Published          |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ |
| [[News/So you’re in space and on the way to Mars, what next.md\|So you’re in space and on the way to Mars, what next]]                                                                                                                                           | December 01, 2025  |
| [[News/Rocket Lab-Built Twin Spacecraft Begin Mars Journey for NASA and UC Berkeley’s ESCAPADE Mission.md\|Rocket Lab-Built Twin Spacecraft Begin Mars Journey for NASA and UC Berkeley’s ESCAPADE Mission]]                                                     | November 13, 2025  |
| [[News/Rocket Lab’s Two Mars-Bound Spacecraft Arrive in Florida Ahead of Launch.md\|Rocket Lab’s Two Mars-Bound Spacecraft Arrive in Florida Ahead of Launch]]                                                                                                   | September 22, 2025 |
| [[News/Rocket Lab to Launch NASA Astrophysics Science Mission on Electron to Study Galaxy Evolution.md\|Rocket Lab to Launch NASA Astrophysics Science Mission on Electron to Study Galaxy Evolution]]                                                           | May 14, 2025       |
| [[News/Rocket Lab Selected by NASA to Provide Neutron Launch Services Under VADR Launch Contract.md\|Rocket Lab Selected by NASA to Provide Neutron Launch Services Under VADR Launch Contract]]                                                                 | January 09, 2025   |
| [[News/Rocket Lab Awarded NASA Study Contract to Explore Bringing Rock Samples from Mars to Earth for the First Time.md\|Rocket Lab Awarded NASA Study Contract to Explore Bringing Rock Samples from Mars to Earth for the First Time]]                         | October 07, 2024   |
| [[News/Rocket Lab Ships Twin Satellites to Launch Site for NASA Mars Mission  Rocket Lab.md\|Rocket Lab Ships Twin Satellites to Launch Site for NASA Mars Mission  Rocket Lab]]                                                                                 | August 16, 2024    |
| [[News/Rocket Lab Completes Integration and Testing of Twin Spacecraft for NASA Mars Mission.md\|Rocket Lab Completes Integration and Testing of Twin Spacecraft for NASA Mars Mission]]                                                                         | July 29, 2024      |
| [[News/Rocket Lab Successfully Completes Second Launch for NASA Climate Science Mission.md\|Rocket Lab Successfully Completes Second Launch for NASA Climate Science Mission]]                                                                                   | June 05, 2024      |
| [[News/Rocket Lab Prepares Back-To-Back Launches For Climate Change Research Mission For NASA.md\|Rocket Lab Prepares Back-To-Back Launches For Climate Change Research Mission For NASA]]                                                                       | April 29, 2024     |
| [[News/Rocket Lab Successfully Deploys Satellites ~500km Apart to Separate Orbits  For KAIST and NASA  Rocket Lab.md\|Rocket Lab Successfully Deploys Satellites ~500km Apart to Separate Orbits  For KAIST and NASA  Rocket Lab]]                               | April 24, 2024     |
| [[News/Rocket Lab Prepares to Launch Mission for KAIST and NASA to Deploy Satellites to Two Separate Orbits.md\|Rocket Lab Prepares to Launch Mission for KAIST and NASA to Deploy Satellites to Two Separate Orbits]]                                           | April 01, 2024     |
| [[News/Rocket Lab Integrating Twin Spacecraft for Mission to Mars for NASA.md\|Rocket Lab Integrating Twin Spacecraft for Mission to Mars for NASA]]                                                                                                             | October 18, 2023   |
| [[News/Rocket Lab to Launch Climate Change Research Mission Focused on Arctic Ice Caps for NASA.md\|Rocket Lab to Launch Climate Change Research Mission Focused on Arctic Ice Caps for NASA]]                                                                   | August 14, 2023    |
| [[News/Rocket Lab Deploys Satellites for NASA and Commercial Constellation Operators,  Successfully Recovers Booster.md\|Rocket Lab Deploys Satellites for NASA and Commercial Constellation Operators,  Successfully Recovers Booster]]                         | July 17, 2023      |
| [[News/Rocket Lab Prepares to Launch Mix of NASA and Commercial Satellites, and Takes Next Step in Rocket Reusability Program.md\|Rocket Lab Prepares to Launch Mix of NASA and Commercial Satellites, and Takes Next Step in Rocket Reusability Program]]       | July 17, 2023      |
| [[News/Rocket Lab to Launch Multiple Satellites as Part of Upcoming Recovery Mission.md\|Rocket Lab to Launch Multiple Satellites as Part of Upcoming Recovery Mission]]                                                                                         | June 22, 2023      |
| [[News/Rocket Lab Successfully Launches Second Batch of TROPICS Satellites for NASA.md\|Rocket Lab Successfully Launches Second Batch of TROPICS Satellites for NASA]]                                                                                           | May 26, 2023       |
| [[News/Rocket Lab Sets Date for Second NASA TROPICS Launch to Deploy Storm Monitoring Constellation.md\|Rocket Lab Sets Date for Second NASA TROPICS Launch to Deploy Storm Monitoring Constellation]]                                                           | May 15, 2023       |
| [[News/Rocket Lab to Launch Small Satellite Swarm for NASA.md\|Rocket Lab to Launch Small Satellite Swarm for NASA]]                                                                                                                                             | May 09, 2023       |
| [[News/Rocket Lab Successfully Launches First Batch of TROPICS Satellites for NASA.md\|Rocket Lab Successfully Launches First Batch of TROPICS Satellites for NASA]]                                                                                             | May 08, 2023       |
| [[News/Rocket Lab Prepares for First of Two Launches to Deploy Storm Monitoring Constellation for NASA.md\|Rocket Lab Prepares for First of Two Launches to Deploy Storm Monitoring Constellation for NASA]]                                                     | May 07, 2023       |
| [[News/Rocket Lab to Launch NASA’s Cyclone-Tracking Satellite Constellation from New Zealand.md\|Rocket Lab to Launch NASA’s Cyclone-Tracking Satellite Constellation from New Zealand]]                                                                         | April 10, 2023     |
| [[News/NASA Selects Rocket Lab to Launch TROPICS Mission.md\|NASA Selects Rocket Lab to Launch TROPICS Mission]]                                                                                                                                                 | November 23, 2022  |
| [[News/Rocket Lab-launched CAPSTONE Spacecraft Enters Lunar Orbit.md\|Rocket Lab-launched CAPSTONE Spacecraft Enters Lunar Orbit]]                                                                                                                               | November 15, 2022  |
| [[News/NASA’s Communications Services Project Sees Inmarsat Government Select Rocket Lab to Develop L-Band Radio.md\|NASA’s Communications Services Project Sees Inmarsat Government Select Rocket Lab to Develop L-Band Radio]]                                 | November 03, 2022  |
| [[News/Rocket Lab Delivers Final Solar Panels for NASA Gateway’s Power and Propulsion Element.md\|Rocket Lab Delivers Final Solar Panels for NASA Gateway’s Power and Propulsion Element]]                                                                       | November 03, 2022  |
| [[News/Rocket Lab Selected to Build Solar Panels for NASA’s CADRE Mobile Robot Program.md\|Rocket Lab Selected to Build Solar Panels for NASA’s CADRE Mobile Robot Program]]                                                                                     | October 14, 2022   |
| [[News/Rocket Lab Moon Mission for NASA a Success  Rocket Lab.md\|Rocket Lab Moon Mission for NASA a Success  Rocket Lab]]                                                                                                                                       | July 04, 2022      |
| [[News/Rocket Lab’s Lunar Photon Completes Sixth Orbit Raise for NASA’s CAPSTONE Mission to The Moon.md\|Rocket Lab’s Lunar Photon Completes Sixth Orbit Raise for NASA’s CAPSTONE Mission to The Moon]]                                                         | July 01, 2022      |
| [[News/Rocket Lab Completes Fifth Orbit Raise For NASA’s CAPSTONE Mission to The Moon.md\|Rocket Lab Completes Fifth Orbit Raise For NASA’s CAPSTONE Mission to The Moon]]                                                                                       | June 30, 2022      |
| [[News/Rocket Lab Successfully Raises Orbit a Fourth Time For NASA’s CAPSTONE Moon Mission.md\|Rocket Lab Successfully Raises Orbit a Fourth Time For NASA’s CAPSTONE Moon Mission]]                                                                             | June 30, 2022      |
| [[News/Rocket Lab’s Lunar Photon Spacecraft Successfully Completes Third Orbit Raising Maneuver for NASA’s CAPSTONE Moon Mission.md\|Rocket Lab’s Lunar Photon Spacecraft Successfully Completes Third Orbit Raising Maneuver for NASA’s CAPSTONE Moon Mission]] | June 29, 2022      |
| [[News/Rocket Lab Successfully Launches CAPSTONE Spacecraft, Completes First Leg of Moon Mission for NASA.md\|Rocket Lab Successfully Launches CAPSTONE Spacecraft, Completes First Leg of Moon Mission for NASA]]                                               | June 28, 2022      |
| [[News/Rocket Lab Prepares to Launch CAPSTONE Mission to the Moon for NASA.md\|Rocket Lab Prepares to Launch CAPSTONE Mission to the Moon for NASA]]                                                                                                             | June 23, 2022      |
| [[News/Rocket Lab selected by Ball Aerospace to Power NASA’s GLIDE Spacecraft.md\|Rocket Lab selected by Ball Aerospace to Power NASA’s GLIDE Spacecraft]]                                                                                                       | June 09, 2022      |
| [[News/Rocket Lab Begins Payload Integration for CAPSTONE Mission to the Moon.md\|Rocket Lab Begins Payload Integration for CAPSTONE Mission to the Moon]]                                                                                                       | May 16, 2022       |
| [[News/Rocket Lab Selected to Provide Venture Class Launch Services for NASA.md\|Rocket Lab Selected to Provide Venture Class Launch Services for NASA]]                                                                                                         | January 27, 2022   |
| [[News/Rocket Lab Selected to Launch NASA’s Advanced Composite Solar Sail System.md\|Rocket Lab Selected to Launch NASA’s Advanced Composite Solar Sail System]]                                                                                                 | October 06, 2021   |
| [[News/Rocket Lab Spacecraft Confirmed for Mars as NASA Greenlights ESCAPADE Small Satellite Interplanetary Mission.md\|Rocket Lab Spacecraft Confirmed for Mars as NASA Greenlights ESCAPADE Small Satellite Interplanetary Mission]]                           | August 23, 2021    |
| [[News/Rocket Lab to Launch NASA Funded Commercial Moon Mission from New Zealand.md\|Rocket Lab to Launch NASA Funded Commercial Moon Mission from New Zealand]]                                                                                                 | August 06, 2021    |
| [[News/Rocket Lab Awarded Contract to Design Twin Spacecraft for Mars.md\|Rocket Lab Awarded Contract to Design Twin Spacecraft for Mars]]                                                                                                                       | June 15, 2021      |
| [[News/Rocket Lab Readies Photon Spacecraft for NASA Moon Mission.md\|Rocket Lab Readies Photon Spacecraft for NASA Moon Mission]]                                                                                                                               | December 11, 2020  |
| [[News/Rocket Lab’s Electron Launch Vehicle Certified by NASA.md\|Rocket Lab’s Electron Launch Vehicle Certified by NASA]]                                                                                                                                       | March 17, 2020     |
| [[News/Rocket Lab’s Next Mission to Launch Satellites for NASA, NRO and the University of New South Wales.md\|Rocket Lab’s Next Mission to Launch Satellites for NASA, NRO and the University of New South Wales]]                                               | March 09, 2020     |
| [[News/Rocket Lab Selected by NASA to Launch Pathfinder Mission to the Moon.md\|Rocket Lab Selected by NASA to Launch Pathfinder Mission to the Moon]]                                                                                                           | February 14, 2020  |
| [[News/Rocket Lab successfully launches NASA CubeSats to orbit on first ever Venture Class Launch Services mission.md\|Rocket Lab successfully launches NASA CubeSats to orbit on first ever Venture Class Launch Services mission]]                             | December 16, 2018  |
| [[News/Rocket Lab prepares to launch historic CubeSat mission for NASA.md\|Rocket Lab prepares to launch historic CubeSat mission for NASA]]                                                                                                                     | December 04, 2018  |
| [[News/Rocket Lab enters high frequency launch operations.md\|Rocket Lab enters high frequency launch operations]]                                                                                                                                               | October 30, 2018   |
| [[News/Rocket Lab to launch It’s Business Time and ELaNa XIX missions weeks apart.md\|Rocket Lab to launch It’s Business Time and ELaNa XIX missions weeks apart]]                                                                                               | August 06, 2018    |
| [[News/Rocket Lab integrates payloads for first ever NASA Venture Class Launch Services Mission.md\|Rocket Lab integrates payloads for first ever NASA Venture Class Launch Services Mission]]                                                                   | April 25, 2018     |
| [[News/Rocket Lab completes fit check for NASA VCLS ELaNa XIX mission.md\|Rocket Lab completes fit check for NASA VCLS ELaNa XIX mission]]                                                                                                                       | February 09, 2018  |
| [[News/Rocket Lab Wins $6.95M NASA Launch Contract.md\|Rocket Lab Wins $6.95M NASA Launch Contract]]                                                                                                                                                             | October 31, 2015   |
| [[News/Rocket Lab and NASA sign Commercial Space Launch Act Agreement.md\|Rocket Lab and NASA sign Commercial Space Launch Act Agreement]]                                                                                                                       | July 31, 2015      |

%%DATAVIEW_PUBLISHER: end %%