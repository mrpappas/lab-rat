[[Home|🏠]]  <span style="color: LightSlateGray">></span> [[Launches]] <span style="color: LightSlateGray">></span> Launches Trailing
## 12 Months

All Launches in the Last 12 Months

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch",
  customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)",
  vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass",
  outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date
  AND regexreplace(launch_date, " .*", "") >= dateformat(date(today) - dur(12 months), "yyyy-MM-dd")
  AND regexreplace(launch_date, " .*", "") <= dateformat(date(today), "yyyy-MM-dd")
SORT launch_date DESC


```
%%

| Launch                                                                                            | Customer                                                          | Date (UTC) | Vehicle                          | Orbit & Mass                | Outcome |
| ------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- | ---------- | -------------------------------- | --------------------------- | ------- |
| [[Launch/Launches/076 - Follow My Speed.md\|076 - Follow My Speed]]                               | [[Organization/Partners/BlackSky.md\|BlackSky]]                   | 2025-11-20 | [[Launch/Electron.md\|Electron]] | 470 km \| 42° \| 138 kg     | ✅       |
| [[Launch/Launches/075 - Prometheus Run.md\|075 - Prometheus Run]]                                 | [[Organization/Partners/MDA.md\|MDA]]                             | 2025-11-18 | [[Launch/HASTE.md\|HASTE]]       | Suborbital \| unknown       | ✅       |
| [[Launch/Launches/074 - The Nation God Navigates.md\|074 - The Nation God Navigates]]             | [[Organization/Partners/iQPS.md\|iQPS]]                           | 2025-11-05 | [[Launch/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg     | ✅       |
| [[Launch/Launches/073 - Owl New World.md\|073 - Owl New World]]                                   | [[Organization/Partners/Synspective.md\|Synspective]]             | 2025-10-14 | [[Launch/Electron.md\|Electron]] | 583 km \| 42° \| 100 kg     | ✅       |
| [[Launch/Launches/072 - JUSTIN.md\|072 - JUSTIN]]                                                 | Confidential Customer                                             | 2025-09-30 | [[Launch/HASTE.md\|HASTE]]       | Suborbital \| unknown       | ✅       |
| [[Launch/Launches/071 - JENNA.md\|071 - JENNA]]                                                   | Confidential Customer                                             | 2025-09-22 | [[Launch/HASTE.md\|HASTE]]       | Suborbital \| unknown       | ✅       |
| [[Launch/Launches/070 - Live, Laugh, Launch.md\|070 - Live, Laugh, Launch]]                       | [[Organization/Partners/EchoStar.md\|EchoStar (Confidential)]]    | 2025-08-23 | [[Launch/Electron.md\|Electron]] | 650 km \| 96° \| Unknown    | ✅       |
| [[Launch/Launches/069 - The Harvest Goddess Thrives.md\|069 - The Harvest Goddess Thrives]]       | [[Organization/Partners/iQPS.md\|iQPS]]                           | 2025-08-05 | [[Launch/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg     | ✅       |
| [[Launch/Launches/068 - Symphony In The Stars.md\|068 - Symphony In The Stars]]                   | [[Organization/Partners/EchoStar.md\|EchoStar (Confidential)]]    | 2025-06-28 | [[Launch/Electron.md\|Electron]] | 650 km \| 96° \| 74 kg      | ✅       |
| [[Launch/Launches/067 - Get The Hawk Outta Here.md\|067 - Get The Hawk Outta Here]]               | [[Organization/Partners/HawkEye 360.md\|HawkEye 360]]             | 2025-06-26 | [[Launch/Electron.md\|Electron]] | 520 km \| 97.45° \| Unknown | ✅       |
| [[Launch/Launches/066 - The Mountain God Guards.md\|066 - The Mountain God Guards]]               | [[Organization/Partners/iQPS.md\|iQPS]]                           | 2025-06-11 | [[Launch/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg     | ✅       |
| [[Launch/Launches/065 - Full Stream Ahead.md\|065 - Full Stream Ahead]]                           | [[Organization/Partners/BlackSky.md\|BlackSky]]                   | 2025-06-03 | [[Launch/Electron.md\|Electron]] | 470 km \| 59° \| 138 kg     | ✅       |
| [[Launch/Launches/064 - The Sea God Sees.md\|064 - The Sea God Sees]]                             | [[Organization/Partners/iQPS.md\|iQPS]]                           | 2025-05-17 | [[Launch/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg     | ✅       |
| [[Launch/Launches/063 - Finding Hot Wildfires Near You.md\|063 - Finding Hot Wildfires Near You]] | [[Organization/Partners/Orora Technlogies.md\|Orora Technlogies]] | 2025-03-26 | [[Launch/Electron.md\|Electron]] | 550 km \| 97° \| Unknown    | ✅       |
| [[Launch/Launches/062 - High Five.md\|062 - High Five]]                                           | [[Organization/Partners/Kinéis.md\|Kinéis]]                       | 2025-03-18 | [[Launch/Electron.md\|Electron]] | 643 km \| 97° \| 150 kg     | ✅       |
| [[Launch/Launches/061 - The Lightning God Reigns.md\|061 - The Lightning God Reigns]]             | [[Organization/Partners/iQPS.md\|iQPS]]                           | 2025-03-15 | [[Launch/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg     | ✅       |
| [[Launch/Launches/060 - Fasten Your Space Belts.md\|060 - Fasten Your Space Belts]]               | [[Organization/Partners/BlackSky.md\|BlackSky]]                   | 2025-02-19 | [[Launch/Electron.md\|Electron]] | 470 km \| 59° \| 138 kg     | ✅       |
| [[Launch/Launches/059 - IOT 4 You and Me.md\|059 - IOT 4 You and Me]]                             | [[Organization/Partners/Kinéis.md\|Kinéis]]                       | 2025-02-04 | [[Launch/Electron.md\|Electron]] | 643 km \| 97° \| 150 kg     | ✅       |
| [[Launch/Launches/058 - Owl The Way Up.md\|058 - Owl The Way Up]]                                 | [[Organization/Partners/Synspective.md\|Synspective]]             | 2024-12-21 | [[Launch/Electron.md\|Electron]] | 574 km \| 97° \| 100 kg     | ✅       |
| [[Launch/Launches/057 - Stonehenge.md\|057 - Stonehenge]]                                         | Unknown*                                                          | 2024-12-13 | [[Launch/HASTE.md\|HASTE]]       | Suborbital \| unknown       | ✅       |
| [[Launch/Launches/056 - Ice AIS Baby.md\|056 - Ice AIS Baby]]                                     | [[Organization/Partners/Kinéis.md\|Kinéis]]                       | 2024-11-25 | [[Launch/Electron.md\|Electron]] | 643 km \| 97° \| 150 kg     | ✅       |

%% DATAVIEW_PUBLISHER: end %%


## 90 Days

All Launches in the Last 90 Days

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch",
  customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)",
  vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass",
  outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date
  AND regexreplace(launch_date, " .*", "") >= dateformat(date(today) - dur(90 days), "yyyy-MM-dd")
  AND regexreplace(launch_date, " .*", "") <= dateformat(date(today), "yyyy-MM-dd")
SORT launch_date DESC

```
%%

| Launch                                                                                | Customer                                              | Date (UTC) | Vehicle                          | Orbit & Mass            | Outcome |
| ------------------------------------------------------------------------------------- | ----------------------------------------------------- | ---------- | -------------------------------- | ----------------------- | ------- |
| [[Launch/Launches/076 - Follow My Speed.md\|076 - Follow My Speed]]                   | [[Organization/Partners/BlackSky.md\|BlackSky]]       | 2025-11-20 | [[Launch/Electron.md\|Electron]] | 470 km \| 42° \| 138 kg | ✅       |
| [[Launch/Launches/075 - Prometheus Run.md\|075 - Prometheus Run]]                     | [[Organization/Partners/MDA.md\|MDA]]                 | 2025-11-18 | [[Launch/HASTE.md\|HASTE]]       | Suborbital \| unknown   | ✅       |
| [[Launch/Launches/074 - The Nation God Navigates.md\|074 - The Nation God Navigates]] | [[Organization/Partners/iQPS.md\|iQPS]]               | 2025-11-05 | [[Launch/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg | ✅       |
| [[Launch/Launches/073 - Owl New World.md\|073 - Owl New World]]                       | [[Organization/Partners/Synspective.md\|Synspective]] | 2025-10-14 | [[Launch/Electron.md\|Electron]] | 583 km \| 42° \| 100 kg | ✅       |
| [[Launch/Launches/072 - JUSTIN.md\|072 - JUSTIN]]                                     | Confidential Customer                                 | 2025-09-30 | [[Launch/HASTE.md\|HASTE]]       | Suborbital \| unknown   | ✅       |
| [[Launch/Launches/071 - JENNA.md\|071 - JENNA]]                                       | Confidential Customer                                 | 2025-09-22 | [[Launch/HASTE.md\|HASTE]]       | Suborbital \| unknown   | ✅       |

%% DATAVIEW_PUBLISHER: end %%

## 30 Days

All Launches in the Last 30 Days

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch",
  customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)",
  vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass",
  outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date
  AND regexreplace(launch_date, " .*", "") >= dateformat(date(today) - dur(30 days), "yyyy-MM-dd")
  AND regexreplace(launch_date, " .*", "") <= dateformat(date(today), "yyyy-MM-dd")
SORT launch_date DESC

```
%%

| Launch                                                                                | Customer                                        | Date (UTC) | Vehicle                          | Orbit & Mass            | Outcome |
| ------------------------------------------------------------------------------------- | ----------------------------------------------- | ---------- | -------------------------------- | ----------------------- | ------- |
| [[Launch/Launches/076 - Follow My Speed.md\|076 - Follow My Speed]]                   | [[Organization/Partners/BlackSky.md\|BlackSky]] | 2025-11-20 | [[Launch/Electron.md\|Electron]] | 470 km \| 42° \| 138 kg | ✅       |
| [[Launch/Launches/075 - Prometheus Run.md\|075 - Prometheus Run]]                     | [[Organization/Partners/MDA.md\|MDA]]           | 2025-11-18 | [[Launch/HASTE.md\|HASTE]]       | Suborbital \| unknown   | ✅       |
| [[Launch/Launches/074 - The Nation God Navigates.md\|074 - The Nation God Navigates]] | [[Organization/Partners/iQPS.md\|iQPS]]         | 2025-11-05 | [[Launch/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg | ✅       |

%% DATAVIEW_PUBLISHER: end %%
