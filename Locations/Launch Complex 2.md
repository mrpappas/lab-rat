
>[!summary]
Launch Complex 2 (LC-2), located at [[NASA]]'s [Wallops Flight Facility in Virginia](https://en.wikipedia.org/wiki/Wallops_Flight_Facility), is the company’s U.S.-based launch site for mid- and high-inclination orbital missions. Designed to support up to 12 [[Electron]] launches annually, LC-2 features a state-of-the-art Vehicle Integration Facility (VIF) and a NASA-certified Autonomous Flight Termination System (AFTS) for safe and efficient operations.
>
[📸 Image Gallery of LC-2](https://www.flickr.com/photos/rocketlab/albums/72157716859992311/)


![[Pasted image 20250117182853.jpg]]

Rocket Lab’s Launch Complex 2 represents a new responsive launch capability for the United States on home soil. Tailored specifically for U.S. government small satellite missions, Launch Complex 2 can support up to 12 missions per year.


## 📍Location

41 N Seawall Rd, Wallops Island, Virginia USA

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1590.6805452235728!2d-75.4889498919699!3d37.83337178539618!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89b9631cc00bf42d%3A0x8ed8e2ddb08e5d4e!2sLC2!5e1!3m2!1sen!2sus!4v1734236211331!5m2!1sen!2sus" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>


## 🏭 Facilities

###  Launch Pad 0C

**Location**: [37°49'59.8"N 75°29'17.6"W](https://www.google.com/maps/place/37%C2%B049'59.8%22N+75%C2%B029'17.6%22W/@37.8332723,-75.4886878,263m/data=!3m1!1e3!4m4!3m3!8m2!3d37.8332778!4d-75.4882222!5m1!1e2?hl=en&entry=ttu&g_ep=EgoyMDI0MTIxMS4wIKXMDSoASAFQAw%3D%3D)
**66 Metric Ton Launch Platform and 7.6 Ton strongback**
### 🛠️ Electron Integration and Control Facility (ICF)

State-of-the-art launch control center, payload integration factory and vehicle integration area capable of supporting multiple Electrons.

## 🚀 Launches from LC-2
%%DATAVIEW_PUBLISHER: start
```
table customer as "Customer", launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where location = [[Launch Complex 2#Launch Pad 0C]] or location = [[Launch Complex 2]]
sort launch_date desc
```
%%

| File                                                                                            | Customer                                                                                                | Date             | Location                                               | Vehicle                          | Orbit & Mass             | Outcome |
| ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | ---------------- | ------------------------------------------------------ | -------------------------------- | ------------------------ | ------- |
| [[Launch/Launches/072 - JUSTIN.md\|072 - JUSTIN]]                                               | Confidential Customer                                                                                   | 2025-09-30 20:28 | [[Locations/Launch Complex 2.md#Launch Pad 0C\|LC2-0]] | [[Launch/HASTE.md\|HASTE]]       | Suborbital \| unknown    | ✅       |
| [[Launch/Launches/071 - JENNA.md\|071 - JENNA]]                                                 | Confidential Customer                                                                                   | 2025-09-22 07:45 | [[Locations/Launch Complex 2.md#Launch Pad 0C\|LC2-0]] | [[Launch/HASTE.md\|HASTE]]       | Suborbital \| unknown    | ✅       |
| [[Launch/Launches/057 - Stonehenge.md\|057 - Stonehenge]]                                       | Unknown*                                                                                                | 2024-12-13 00:00 | [[Locations/Launch Complex 2.md#Launch Pad 0C\|LC2-0]] | [[Launch/HASTE.md\|HASTE]]       | Suborbital \| unknown    | ✅       |
| [[Launch/Launches/055 - HASTE A La Vista.md\|055 - HASTE A La Vista]]                           | [[Organization/Partners/U.S. Department of Defense.md\|U.S. Department of Defense]]                     | 2024-11-24 06:00 | [[Locations/Launch Complex 2.md#Launch Pad 0C\|LC2-0]] | [[Launch/HASTE.md\|HASTE]]       | Suborbital \| unknown    | ✅       |
| [[Launch/Launches/046 - Live And Let Fly.md\|046 - Live And Let Fly]]                           | [[Organization/Partners/National Reconnaissance Office (NRO).md\|National Reconnaissance Office (NRO)]] | 2024-03-21 06:40 | [[Locations/Launch Complex 2.md#Launch Pad 0C\|LC2-0]] | [[Launch/Electron.md\|Electron]] | Classified \| Classified | ✅       |
| [[Launch/Launches/038 - Scout's Arrow.md\|038 - Scout's Arrow]]                                 | [[Organization/Partners/Leidos.md\|Leidos]]                                                             | 2023-06-18 01:24 | [[Locations/Launch Complex 2.md#Launch Pad 0C\|LC2-0]] | [[Launch/HASTE.md\|HASTE]]       | Suborbital \| unknown    | ✅       |
| [[Launch/Launches/034 - Stronger Together.md\|034 - Stronger Together]]                         | [[Organization/Partners/Capella Space.md\|Capella Space]]                                               | 2023-03-16 22:38 | [[Locations/Launch Complex 2.md#Launch Pad 0C\|LC2-0]] | [[Launch/Electron.md\|Electron]] | 600 km \| 44° \| 224 kg  | ✅       |
| [[Launch/Launches/033 - Virginia is for Launch Lovers.md\|033 - Virginia is for Launch Lovers]] | [[Organization/Partners/HawkEye 360.md\|HawkEye 360]]                                                   | 2023-01-24 23:00 | [[Locations/Launch Complex 2.md#Launch Pad 0C\|LC2-0]] | [[Launch/Electron.md\|Electron]] | 550 km \| 40.5° \| 40 kg | ✅       |

%%DATAVIEW_PUBLISHER: end %%

## News

Here's a list of all launches from LC-2, for more info on all launches see  [[Launches]]

%%DATAVIEW_PUBLISHER: start
```
table title as "Title", published as "Published"
from "News"
where contains(location, [[Launch Complex 2]])
sort published desc

```
%%

| File                                                                                                                                                                                                                                     | Title                                                                                                          | Published          |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | ------------------ |
| [[News/Rocket Lab Completes Final Dress Rehearsal at Launch Complex 2 Ahead of First Electron Mission from U.S. Soil.md\|Rocket Lab Completes Final Dress Rehearsal at Launch Complex 2 Ahead of First Electron Mission from U.S. Soil]] | Rocket Lab Completes Final Dress Rehearsal at Launch Complex 2 Ahead of First Electron Mission from U.S. Soil  | September 17, 2020 |
| [[News/Rocket Lab Granted FAA Launch Operator License for Missions from Launch Complex 2.md\|Rocket Lab Granted FAA Launch Operator License for Missions from Launch Complex 2]]                                                         | Rocket Lab Granted FAA Launch Operator License for Missions from Launch Complex 2                              | September 01, 2020 |
| [[News/Electron Roll-Out Complete at Launch Complex 2 Ahead of Upcoming U.S. Space Force Mission.md\|Electron Roll-Out Complete at Launch Complex 2 Ahead of Upcoming U.S. Space Force Mission]]                                         | Electron Roll-Out Complete at Launch Complex 2 Ahead of Upcoming U.S. Space Force Mission                      | April 29, 2020     |
| [[News/Rocket Lab Opens Launch Complex 2, Confirms U.S. Air Force Payload as First Electron Mission from U.S. Soil.md\|Rocket Lab Opens Launch Complex 2, Confirms U.S. Air Force Payload as First Electron Mission from U.S. Soil]]     | Rocket Lab Opens Launch Complex 2, Confirms U.S. Air Force Payload as First Electron Mission from U.S. Soil    | December 12, 2019  |
| [[News/Rocket Lab Readies Launch Complex 2 for Electron Launches From U.S. Soil.md\|Rocket Lab Readies Launch Complex 2 for Electron Launches From U.S. Soil]]                                                                           | Rocket Lab Readies Launch Complex 2 for Electron Launches From U.S. Soil                                       | September 18, 2019 |
| [[News/Rocket Lab selects Wallops Flight Facility for US launch site.md\|Rocket Lab selects Wallops Flight Facility for US launch site]]                                                                                                 | Rocket Lab selects Wallops Flight Facility for US launch site                                                  | October 17, 2018   |
| [[News/Rocket Lab to expand launch capability with US launch site.md\|Rocket Lab to expand launch capability with US launch site]]                                                                                                       | Rocket Lab to expand launch capability with US launch site                                                     | July 10, 2018      |

%%DATAVIEW_PUBLISHER: end%%


## 📽️ Media


<div class="responsive-video">
<iframe width="750" height="427" src="https://www.youtube.com/embed/vu-ZisFbjFo" title="Rocket Lab Launch Complex 2 Opening" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
