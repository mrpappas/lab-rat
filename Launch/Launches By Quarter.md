[[Home|🏠]]  <span style="color: LightSlateGray">></span> [[Launches]] <span style="color: LightSlateGray">></span> Launches By Quarter

## 2025

### Q4 2025

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
WHERE launch_date AND (
  startswith(launch_date, "2025-10") OR
  startswith(launch_date, "2025-11") OR
  startswith(launch_date, "2025-12")
)
SORT launch_date DESC

```
%%

| Launch                                                                                | Customer                                                                                                                                                                      | Date (UTC) | Vehicle                                                 | Orbit & Mass               | Outcome |
| ------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------- | -------------------------- | ------- |
| [[Launch/Launches/079 - The Wisdom God Guides.md\|079 - The Wisdom God Guides]]       | [[Organization/Partners/iQPS.md\|iQPS]]                                                                                                                                       | 2025-12-21 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg    | ✅       |
| [[Launch/Launches/078 - Don't Be Such A Square.md\|078 - Don't Be Such A Square]]     | <ul><li>[[Organization/Partners/U.S. Space Force.md\|U.S. Space Force]]</li><li>[[Organization/Partners/The Aerospace Corporation.md\|The Aerospace Corporation]]</li></ul> | 2025-12-18 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 550 km \| 45° \| Unknown   | ✅       |
| [[Launch/Launches/077 - RAISE and Shine.md\|077 - RAISE and Shine]]                   | [[Organization/Partners/JAXA.md\|JAXA]]                                                                                                                                       | 2025-12-14 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 540 km \| 97.5° \| ~110 kg | ✅       |
| [[Launch/Launches/076 - Follow My Speed.md\|076 - Follow My Speed]]                   | [[Organization/Partners/BlackSky.md\|BlackSky]]                                                                                                                               | 2025-11-20 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 470 km \| 42° \| 138 kg    | ✅       |
| [[Launch/Launches/075 - Prometheus Run.md\|075 - Prometheus Run]]                     | [[Organization/Partners/Missile Defense Agency.md\|Missile Defense Agency]]                                                                                                   | 2025-11-18 | [[Space Systems/Launch Vehicles/HASTE.md\|HASTE]]       | Suborbital \| unknown      | ✅       |
| [[Launch/Launches/074 - The Nation God Navigates.md\|074 - The Nation God Navigates]] | [[Organization/Partners/iQPS.md\|iQPS]]                                                                                                                                       | 2025-11-05 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg    | ✅       |
| [[Launch/Launches/073 - Owl New World.md\|073 - Owl New World]]                       | [[Organization/Partners/Synspective.md\|Synspective]]                                                                                                                         | 2025-10-14 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 583 km \| 42° \| 100 kg    | ✅       |

%% DATAVIEW_PUBLISHER: end %%

### Q3 2025

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
WHERE launch_date AND (
  startswith(launch_date, "2025-07") OR
  startswith(launch_date, "2025-08") OR
  startswith(launch_date, "2025-09")
)
SORT launch_date DESC

```
%%

| Launch                                                                                      | Customer                                                       | Date (UTC) | Vehicle                                                 | Orbit & Mass             | Outcome |
| ------------------------------------------------------------------------------------------- | -------------------------------------------------------------- | ---------- | ------------------------------------------------------- | ------------------------ | ------- |
| [[Launch/Launches/072 - JUSTIN.md\|072 - JUSTIN]]                                           | Confidential Customer                                          | 2025-09-30 | [[Space Systems/Launch Vehicles/HASTE.md\|HASTE]]       | Suborbital \| unknown    | ✅       |
| [[Launch/Launches/071 - JENNA.md\|071 - JENNA]]                                             | Confidential Customer                                          | 2025-09-22 | [[Space Systems/Launch Vehicles/HASTE.md\|HASTE]]       | Suborbital \| unknown    | ✅       |
| [[Launch/Launches/070 - Live, Laugh, Launch.md\|070 - Live, Laugh, Launch]]                 | [[Organization/Partners/EchoStar.md\|EchoStar (Confidential)]] | 2025-08-23 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 650 km \| 96° \| Unknown | ✅       |
| [[Launch/Launches/069 - The Harvest Goddess Thrives.md\|069 - The Harvest Goddess Thrives]] | [[Organization/Partners/iQPS.md\|iQPS]]                        | 2025-08-05 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg  | ✅       |

%% DATAVIEW_PUBLISHER: end %%

### Q2 2025

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
WHERE launch_date AND (
  startswith(launch_date, "2025-04") OR
  startswith(launch_date, "2025-05") OR
  startswith(launch_date, "2025-06")
)
SORT launch_date DESC

```
%%

| Launch                                                                              | Customer                                                       | Date (UTC) | Vehicle                                                 | Orbit & Mass                | Outcome |
| ----------------------------------------------------------------------------------- | -------------------------------------------------------------- | ---------- | ------------------------------------------------------- | --------------------------- | ------- |
| [[Launch/Launches/068 - Symphony In The Stars.md\|068 - Symphony In The Stars]]     | [[Organization/Partners/EchoStar.md\|EchoStar (Confidential)]] | 2025-06-28 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 650 km \| 96° \| 74 kg      | ✅       |
| [[Launch/Launches/067 - Get The Hawk Outta Here.md\|067 - Get The Hawk Outta Here]] | [[Organization/Partners/HawkEye 360.md\|HawkEye 360]]          | 2025-06-26 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 520 km \| 97.45° \| Unknown | ✅       |
| [[Launch/Launches/066 - The Mountain God Guards.md\|066 - The Mountain God Guards]] | [[Organization/Partners/iQPS.md\|iQPS]]                        | 2025-06-11 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg     | ✅       |
| [[Launch/Launches/065 - Full Stream Ahead.md\|065 - Full Stream Ahead]]             | [[Organization/Partners/BlackSky.md\|BlackSky]]                | 2025-06-03 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 470 km \| 59° \| 138 kg     | ✅       |
| [[Launch/Launches/064 - The Sea God Sees.md\|064 - The Sea God Sees]]               | [[Organization/Partners/iQPS.md\|iQPS]]                        | 2025-05-17 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg     | ✅       |

%% DATAVIEW_PUBLISHER: end %%

### Q1 2025

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
WHERE launch_date AND (
  startswith(launch_date, "2025-01") OR
  startswith(launch_date, "2025-02") OR
  startswith(launch_date, "2025-03")
)
SORT launch_date DESC

```
%%

| Launch                                                                                            | Customer                                                          | Date (UTC) | Vehicle                                                 | Orbit & Mass             | Outcome |
| ------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- | ---------- | ------------------------------------------------------- | ------------------------ | ------- |
| [[Launch/Launches/063 - Finding Hot Wildfires Near You.md\|063 - Finding Hot Wildfires Near You]] | [[Organization/Partners/Orora Technlogies.md\|Orora Technlogies]] | 2025-03-26 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 550 km \| 97° \| Unknown | ✅       |
| [[Launch/Launches/062 - High Five.md\|062 - High Five]]                                           | [[Organization/Partners/Kinéis.md\|Kinéis]]                       | 2025-03-18 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 643 km \| 97° \| 150 kg  | ✅       |
| [[Launch/Launches/061 - The Lightning God Reigns.md\|061 - The Lightning God Reigns]]             | [[Organization/Partners/iQPS.md\|iQPS]]                           | 2025-03-15 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg  | ✅       |
| [[Launch/Launches/060 - Fasten Your Space Belts.md\|060 - Fasten Your Space Belts]]               | [[Organization/Partners/BlackSky.md\|BlackSky]]                   | 2025-02-19 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 470 km \| 59° \| 138 kg  | ✅       |
| [[Launch/Launches/059 - IOT 4 You and Me.md\|059 - IOT 4 You and Me]]                             | [[Organization/Partners/Kinéis.md\|Kinéis]]                       | 2025-02-04 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 643 km \| 97° \| 150 kg  | ✅       |

%% DATAVIEW_PUBLISHER: end %%

## 2024

### Q4 2024

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2024-10") OR startswith(launch_date, "2024-11") OR startswith(launch_date, "2024-12"))
SORT launch_date DESC

```
%%

| Launch                                                                                                                    | Customer                                                                                       | Date (UTC) | Vehicle                                                 | Orbit & Mass             | Outcome |
| ------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------- | ------------------------ | ------- |
| [[Launch/Launches/058 - Owl The Way Up.md\|058 - Owl The Way Up]]                                                         | [[Organization/Partners/Synspective.md\|Synspective]]                                          | 2024-12-21 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 574 km \| 97° \| 100 kg  | ✅       |
| [[Launch/Launches/057 - Stonehenge.md\|057 - Stonehenge]]                                                                 | Unknown*                                                                                       | 2024-12-13 | [[Space Systems/Launch Vehicles/HASTE.md\|HASTE]]       | Suborbital \| unknown    | ✅       |
| [[Launch/Launches/056 - Ice AIS Baby.md\|056 - Ice AIS Baby]]                                                             | [[Organization/Partners/Kinéis.md\|Kinéis]]                                                    | 2024-11-25 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 643 km \| 97° \| 150 kg  | ✅       |
| [[Launch/Launches/055 - HASTE A La Vista.md\|055 - HASTE A La Vista]]                                                     | [[Organization/Partners/U.S. Department of Defense.md\|U.S. Department of Defense]]            | 2024-11-24 | [[Space Systems/Launch Vehicles/HASTE.md\|HASTE]]       | Suborbital \| unknown    | ✅       |
| [[Launch/Launches/054 - Changes In Latitudes, Changes In Attitudes.md\|054 - Changes In Latitudes, Changes In Attitudes]] | <ul><li>[[Organization/Partners/E-Space.md\|E-Space]]</li><li>Confidential Customer</li></ul> | 2024-11-05 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | Classified \| Classified | ✅       |

%% DATAVIEW_PUBLISHER: end %%

### Q3 2024

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2024-07") OR startswith(launch_date, "2024-08") OR startswith(launch_date, "2024-09"))
SORT launch_date DESC

```
%%

| Launch                                                                                          | Customer                                                  | Date (UTC) | Vehicle                                                 | Orbit & Mass            | Outcome |
| ----------------------------------------------------------------------------------------------- | --------------------------------------------------------- | ---------- | ------------------------------------------------------- | ----------------------- | ------- |
| [[Launch/Launches/053 - Kinéis Killed the RadIOT Star.md\|053 - Kinéis Killed the RadIOT Star]] | [[Organization/Partners/Kinéis.md\|Kinéis]]               | 2024-09-20 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 643 km \| 98° \| 150 kg | ✅       |
| [[Launch/Launches/052 - A Sky Full Of SARs.md\|052 - A Sky Full Of SARs]]                       | [[Organization/Partners/Capella Space.md\|Capella Space]] | 2024-08-11 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 615 km \| 53° \| 165 kg | ✅       |
| [[Launch/Launches/051 - Owl For One, One For Owl.md\|051 - Owl For One, One For Owl]]           | [[Organization/Partners/Synspective.md\|Synspective]]     | 2024-08-02 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 543 km \| 43° \| 100 kg | ✅       |

%% DATAVIEW_PUBLISHER: end %%

### Q2 2024

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2024-04") OR startswith(launch_date, "2024-05") OR startswith(launch_date, "2024-06"))
SORT launch_date DESC

```
%%

| Launch                                                                            | Customer                                                                                                      | Date (UTC) | Vehicle                                                 | Orbit & Mass                                       | Outcome |
| --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------- | -------------------------------------------------- | ------- |
| [[Launch/Launches/050 - No Time Toulouse.md\|050 - No Time Toulouse]]             | [[Organization/Partners/Kinéis.md\|Kinéis]]                                                                   | 2024-06-18 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 635 km \| 98° \| 150 kg                            | ✅       |
| [[Launch/Launches/049 - PREFIRE and ICE.md\|049 - PREFIRE and ICE]]               | [[Organization/Partners/NASA.md\|NASA]]                                                                       | 2024-06-05 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 525 km \| 97.5° \| 15 kg                           | ✅       |
| [[Launch/Launches/048 - Ready, Aim, Prefire.md\|048 - Ready, Aim, Prefire]]       | [[Organization/Partners/NASA.md\|NASA]]                                                                       | 2024-05-25 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 525 km \| 97.5° \| 15 kg                           | ✅       |
| [[Launch/Launches/047 - Beginning Of The Swarm.md\|047 - Beginning Of The Swarm]] | <ul><li>[[Organization/Partners/NASA.md\|NASA]]</li><li>[[Organization/Partners/KAIST.md\|KAIST]]</li></ul> | 2024-04-23 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 520 km (Neonsat-1), 1,000 km (ACS3), 97° \| 115 kg | ✅       |

%% DATAVIEW_PUBLISHER: end %%

### Q1 2024

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2024-01") OR startswith(launch_date, "2024-02") OR startswith(launch_date, "2024-03"))
SORT launch_date DESC

```
%%

| Launch                                                                        | Customer                                                                                                                                                          | Date (UTC) | Vehicle                                                 | Orbit & Mass             | Outcome |
| ----------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------- | ------------------------ | ------- |
| [[Launch/Launches/046 - Live And Let Fly.md\|046 - Live And Let Fly]]         | [[Organization/Partners/National Reconnaissance Office (NRO).md\|National Reconnaissance Office (NRO)]]                                                           | 2024-03-21 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | Classified \| Classified | ✅       |
| [[Launch/Launches/045 - Owl Night Long.md\|045 - Owl Night Long]]             | [[Organization/Partners/Synspective.md\|Synspective]]                                                                                                             | 2024-03-12 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 561 km \| 97° \| 100 kg  | ✅       |
| [[Launch/Launches/044 - On Closer Inspection.md\|044 - On Closer Inspection]] | [[Organization/Partners/Astroscale-Japan.md\|Astroscale-Japan]]                                                                                                   | 2024-02-19 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 600 km \| 98° \| 150 kg  | ✅       |
| [[Launch/Launches/043 - Four Of A Kind.md\|043 - Four Of A Kind]]             | <ul><li>[[Organization/Partners/Spire Global.md\|Spire Global]]</li><li>[[Organization/Partners/NorthStar Earth & Space.md\|NorthStar Earth & Space]]</li></ul> | 2024-01-31 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 530 km \| 97° \| 112 kg  | ✅       |

%% DATAVIEW_PUBLISHER: end %%

## 2023

### Q4 2023

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2023-10") OR startswith(launch_date, "2023-11") OR startswith(launch_date, "2023-12"))
SORT launch_date DESC

```
%%

| Launch                                                                        | Customer                                | Date (UTC) | Vehicle                                                 | Orbit & Mass            | Outcome |
| ----------------------------------------------------------------------------- | --------------------------------------- | ---------- | ------------------------------------------------------- | ----------------------- | ------- |
| [[Launch/Launches/042 - The Moon God Awakens.md\|042 - The Moon God Awakens]] | [[Organization/Partners/iQPS.md\|iQPS]] | 2023-12-15 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 575 km \| 42° \| 100 kg | ✅       |

%% DATAVIEW_PUBLISHER: end %%

### Q3 2023

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2023-07") OR startswith(launch_date, "2023-08") OR startswith(launch_date, "2023-09"))
SORT launch_date DESC

```
%%

| Launch                                                                                | Customer                                                                                                                                                                                                                                                                                                                                             | Date (UTC) | Vehicle                                                 | Orbit & Mass               | Outcome |
| ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------- | -------------------------- | ------- |
| [[Launch/Launches/041 - We Will Never Desert You.md\|041 - We Will Never Desert You]] | [[Organization/Partners/Capella Space.md\|Capella Space]]                                                                                                                                                                                                                                                                                            | 2023-09-19 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 640 km \| 53° \| 165 kg    | ❌       |
| [[Launch/Launches/040 - We Love The Nightlife.md\|040 - We Love The Nightlife]]       | [[Organization/Partners/Capella Space.md\|Capella Space]]                                                                                                                                                                                                                                                                                            | 2023-08-24 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 640 km \| 53° \| 165 kg    | ✅       |
| [[Launch/Launches/039 - Baby Come Back.md\|039 - Baby Come Back]]                     | <ul><li>[[Organization/Partners/NASA.md\|NASA]]</li><li>[[Organization/Partners/UTIAS Space Flight Laboratory.md\|UTIAS Space Flight Laboratory]]</li><li>[[Organization/Partners/Telesat.md\|Telesat]]</li><li>[[Organization/Partners/Spire Global.md\|Spire Global]]</li><li>[[Organization/Partners/CesiumAstro.md\|CesiumAstro]]</li></ul> | 2023-07-18 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 1000 km \| 99.45° \| 86 kg | ✅       |

%% DATAVIEW_PUBLISHER: end %%

### Q2 2023

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2023-04") OR startswith(launch_date, "2023-05") OR startswith(launch_date, "2023-06"))
SORT launch_date DESC

```
%%

| Launch                                                                                    | Customer                                    | Date (UTC) | Vehicle                                                 | Orbit & Mass           | Outcome |
| ----------------------------------------------------------------------------------------- | ------------------------------------------- | ---------- | ------------------------------------------------------- | ---------------------- | ------- |
| [[Launch/Launches/038 - Scout's Arrow.md\|038 - Scout's Arrow]]                           | [[Organization/Partners/Leidos.md\|Leidos]] | 2023-06-18 | [[Space Systems/Launch Vehicles/HASTE.md\|HASTE]]       | Suborbital \| unknown  | ✅       |
| [[Launch/Launches/037 - Coming To A Storm Near You.md\|037 - Coming To A Storm Near You]] | [[Organization/Partners/NASA.md\|NASA]]     | 2023-05-26 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 550 km \| 32° \| 10 kg | ✅       |
| [[Launch/Launches/036 - Rocket Like A Hurricane.md\|036 - Rocket Like A Hurricane]]       | [[Organization/Partners/NASA.md\|NASA]]     | 2023-05-08 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 550 km \| 32° \| 10 kg | ✅       |

%% DATAVIEW_PUBLISHER: end %%

### Q1 2023

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2023-01") OR startswith(launch_date, "2023-02") OR startswith(launch_date, "2023-03"))
SORT launch_date DESC

```
%%

| Launch                                                                                          | Customer                                                  | Date (UTC) | Vehicle                                                 | Orbit & Mass             | Outcome |
| ----------------------------------------------------------------------------------------------- | --------------------------------------------------------- | ---------- | ------------------------------------------------------- | ------------------------ | ------- |
| [[Launch/Launches/035 - The Beat Goes On.md\|035 - The Beat Goes On]]                           | [[Organization/Partners/BlackSky.md\|BlackSky]]           | 2023-03-24 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 450 km \| 42° \| 120 kg  | ✅       |
| [[Launch/Launches/034 - Stronger Together.md\|034 - Stronger Together]]                         | [[Organization/Partners/Capella Space.md\|Capella Space]] | 2023-03-16 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 600 km \| 44° \| 224 kg  | ✅       |
| [[Launch/Launches/033 - Virginia is for Launch Lovers.md\|033 - Virginia is for Launch Lovers]] | [[Organization/Partners/HawkEye 360.md\|HawkEye 360]]     | 2023-01-24 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 550 km \| 40.5° \| 40 kg | ✅       |

%% DATAVIEW_PUBLISHER: end %%


## 2022


### Q4 2022

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2022-10") OR startswith(launch_date, "2022-11") OR startswith(launch_date, "2022-12"))
SORT launch_date DESC

```
%%

| Launch                                                                          | Customer                                                                                                      | Date (UTC) | Vehicle                                                 | Orbit & Mass              | Outcome |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------- | ------------------------- | ------- |
| [[Launch/Launches/032 - Catch Me If You Can.md\|032 - Catch Me If You Can]]     | [[Organization/Partners/Swedish National Space Agency.md\|Swedish National Space Agency]]                     | 2022-11-04 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 585 km \| 97.66° \| 50 kg | ✅       |
| [[Launch/Launches/031 - It Argos Up From Here.md\|031 - It Argos Up From Here]] | [[Organization/Partners/General Atomics Electromagnetic Systems.md\|General Atomics Electromagnetic Systems]] | 2022-10-07 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 750 km \| 98° \| 118 kg   | ✅       |

%% DATAVIEW_PUBLISHER: end %%

### Q3 2022

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2022-07") OR startswith(launch_date, "2022-08") OR startswith(launch_date, "2022-09"))
SORT launch_date DESC

```
%%

| Launch                                                                                  | Customer                                                                                                | Date (UTC) | Vehicle                                                 | Orbit & Mass                | Outcome |
| --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------- | --------------------------- | ------- |
| [[Launch/Launches/030 - The Owl Spreads Its Wings.md\|030 - The Owl Spreads Its Wings]] | [[Organization/Partners/Synspective.md\|Synspective]]                                                   | 2022-09-15 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 563 km \| 97° \| 100 kg     | ✅       |
| [[Launch/Launches/029 - Antipodean Adventure.md\|029 - Antipodean Adventure]]           | [[Organization/Partners/National Reconnaissance Office (NRO).md\|National Reconnaissance Office (NRO)]] | 2022-08-04 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 620 km \| 70° \| Classified | ✅       |
| [[Launch/Launches/028 - Wise One Looks Ahead.md\|028 - Wise One Looks Ahead]]           | [[Organization/Partners/National Reconnaissance Office (NRO).md\|National Reconnaissance Office (NRO)]] | 2022-07-13 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 620 km \| 40° \| Classified | ✅       |

%% DATAVIEW_PUBLISHER: end %%

### Q2 2022

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2022-04") OR startswith(launch_date, "2022-05") OR startswith(launch_date, "2022-06"))
SORT launch_date DESC

```
%%

| Launch                                                                            | Customer                                                                                                                                                                                                                                                                                                                                                                                                                                          | Date (UTC) | Vehicle                                                 | Orbit & Mass                                       | Outcome |
| --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------- | -------------------------------------------------- | ------- |
| [[Launch/Launches/027 - CAPSTONE.md\|027 - CAPSTONE]]                             | <ul><li>[[Organization/Partners/NASA.md\|NASA]]</li><li>[[Organization/Partners/Advanced Space.md\|Advanced Space]]</li></ul>                                                                                                                                                                                                                                                                                                                   | 2022-06-28 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | Translunar Injection (TLI) \| 320kg LEO / 80kg TLI | ✅       |
| [[Launch/Launches/026 - There And Back Again.md\|026 - There And Back Again]]     | <ul><li>[[Organization/Partners/Alba Orbital.md\|Alba Orbital]]</li><li>[[Organization/Partners/Astrix Astronautics.md\|Astrix Astronautics]]</li><li>[[Organization/Partners/Aurora Propulsion Technologies.md\|Aurora Propulsion Technologies]]</li><li>[[Organization/Partners/E-Space.md\|E-Space]]</li><li>[[Organization/Partners/Spaceflight.md\|Spaceflight]]</li><li>[[Organization/Partners/Unseenlabs.md\|Unseenlabs]]</li></ul> | 2022-05-02 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 520 km \| 94° \| Unknown                           | ✅       |
| [[Launch/Launches/025 - Without Mission A Beat.md\|025 - Without Mission A Beat]] | [[Organization/Partners/BlackSky.md\|BlackSky]]                                                                                                                                                                                                                                                                                                                                                                                                   | 2022-04-02 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 430 km \| 53° \| 120 kg                            | ✅       |

%% DATAVIEW_PUBLISHER: end %%

### Q1 2022

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2022-01") OR startswith(launch_date, "2022-02") OR startswith(launch_date, "2022-03"))
SORT launch_date DESC

```
%%

| Launch                                                                                  | Customer                                              | Date (UTC) | Vehicle                                                 | Orbit & Mass            | Outcome |
| --------------------------------------------------------------------------------------- | ----------------------------------------------------- | ---------- | ------------------------------------------------------- | ----------------------- | ------- |
| [[Launch/Launches/024 - The Owl's Night Continues.md\|024 - The Owl's Night Continues]] | [[Organization/Partners/Synspective.md\|Synspective]] | 2022-02-28 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 561 km \| 97° \| 150 kg | ✅       |

%% DATAVIEW_PUBLISHER: end %%

## 2021

### Q4 2021

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2021-10") OR startswith(launch_date, "2021-11") OR startswith(launch_date, "2021-12"))
SORT launch_date DESC

```
%%

| Launch                                                                          | Customer                                                                                                                          | Date (UTC) | Vehicle                                                 | Orbit & Mass            | Outcome |
| ------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------- | ----------------------- | ------- |
| [[Launch/Launches/023 - A Data With Destiny.md\|023 - A Data With Destiny]]     | [[Organization/Partners/BlackSky.md\|BlackSky]]                                                                                   | 2021-12-09 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 430 km \| 42° \| 120 kg | ✅       |
| [[Launch/Launches/022 - Love At First Insight.md\|022 - Love At First Insight]] | <ul><li>[[Organization/Partners/BlackSky.md\|BlackSky]]</li><li>[[Organization/Partners/Spaceflight.md\|Spaceflight]]</li></ul> | 2021-11-18 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 430 km \| 42° \| 120 kg | ✅       |

%% DATAVIEW_PUBLISHER: end %%

### Q3 2021

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2021-07") OR startswith(launch_date, "2021-08") OR startswith(launch_date, "2021-09"))
SORT launch_date DESC

```
%%

| Launch                                                                                      | Customer                                                        | Date (UTC) | Vehicle                                                 | Orbit & Mass             | Outcome |
| ------------------------------------------------------------------------------------------- | --------------------------------------------------------------- | ---------- | ------------------------------------------------------- | ------------------------ | ------- |
| [[Launch/Launches/021 - It's A Little Chile Up Here.md\|021 - It's A Little Chile Up Here]] | [[Organization/Partners/U.S. Space Force.md\|U.S. Space Force]] | 2021-07-29 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 600 km \| 37° \| Unknown | ✅       |

%% DATAVIEW_PUBLISHER: end %%

### Q2 2021

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2021-04") OR startswith(launch_date, "2021-05") OR startswith(launch_date, "2021-06"))
SORT launch_date DESC

```
%%

| Launch                                                                      | Customer                                        | Date (UTC) | Vehicle                                                 | Orbit & Mass            | Outcome |
| --------------------------------------------------------------------------- | ----------------------------------------------- | ---------- | ------------------------------------------------------- | ----------------------- | ------- |
| [[Launch/Launches/020 - Running Out Of Toes.md\|020 - Running Out Of Toes]] | [[Organization/Partners/BlackSky.md\|BlackSky]] | 2021-05-15 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 430 km \| 50° \| 120 kg | ❌       |

%% DATAVIEW_PUBLISHER: end %%

### Q1 2021
 
%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2021-01") OR startswith(launch_date, "2021-02") OR startswith(launch_date, "2021-03"))
SORT launch_date DESC

```
%%

| Launch                                                                                        | Customer                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Date (UTC) | Vehicle                                                 | Orbit & Mass                        | Outcome |
| --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------- | ----------------------------------- | ------- |
| [[Launch/Launches/019 - They Go Up So Fast.md\|019 - They Go Up So Fast]]                     | <ul><li>[[Organization/Partners/BlackSky.md\|BlackSky]]</li><li>[[Organization/Partners/Tyvak Nano-Satellite Systems.md\|Tyvak Nano-Satellite Systems]]</li><li>[[Organization/Partners/Fleet Space.md\|Fleet Space]]</li><li>[[Organization/Partners/Myriota.md\|Myriota]]</li><li>[[Organization/Partners/UNSW Canberra Space.md\|UNSW Canberra Space]]</li><li>[[Organization/Partners/Care Weather.md\|Care Weather]]</li><li>[[Organization/Partners/U.S. Army Space and Missile Defense Command.md\|U.S. Army Space and Missile Defense Command]]</li><li>[[Organization/Partners/Trisept.md\|Trisept]]</li></ul> | 2021-03-22 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 450 km and 550 km \| 45° \| Unknown | ✅       |
| [[Launch/Launches/018 - Another One Leaves the Crust.md\|018 - Another One Leaves the Crust]] | [[Organization/Partners/OHB Group.md\|OHB Group]]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | 2021-01-20 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 1200 km \| 90° \| 50 kg             | ✅       |

%% DATAVIEW_PUBLISHER: end %%

## 2020

### Q4 2020

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2020-10") OR startswith(launch_date, "2020-11") OR startswith(launch_date, "2020-12"))
SORT launch_date DESC

```
%%

| Launch                                                                            | Customer                                                                                                                                                                                                                                                                                                                         | Date (UTC) | Vehicle                                                 | Orbit & Mass              | Outcome |
| --------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------- | ------------------------- | ------- |
| [[Launch/Launches/017 - The Owl's Night Begins.md\|017 - The Owl's Night Begins]] | [[Organization/Partners/Synspective.md\|Synspective]]                                                                                                                                                                                                                                                                            | 2020-12-15 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 500 km \| 97.3° \| 150 kg | ✅       |
| [[Launch/Launches/016 - Return to Sender.md\|016 - Return to Sender]]             | <ul><li>[[Organization/Partners/Trisept.md\|Trisept]]</li><li>[[Organization/Partners/Unseenlabs.md\|Unseenlabs]]</li><li>[[Organization/Partners/Swarm.md\|Swarm]]</li><li>[[Organization/Partners/The University of Auckland.md\|The University of Auckland]]</li><li>[[Organization/Partners/Valve.md\|Valve]]</li></ul> | 2020-11-20 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 500 km \| 97.3° \| 200 kg | ✅       |
| [[Launch/Launches/015 - In Focus.md\|015 - In Focus]]                             | <ul><li>[[Organization/Partners/Planet Labs.md\|Planet Labs]]</li><li>[[Organization/Partners/Spaceflight.md\|Spaceflight]]</li><li>[[Organization/Partners/Canon Electronics.md\|Canon Electronics]]</li></ul>                                                                                                               | 2020-10-28 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 500 km \| 97.5° \| 72 kg  | ✅       |

%% DATAVIEW_PUBLISHER: end %%

### Q3 2020

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2020-07") OR startswith(launch_date, "2020-08") OR startswith(launch_date, "2020-09"))
SORT launch_date DESC

```
%%

| Launch                                                                                                | Customer                                                                                                                                                                                                                                                                                      | Date (UTC) | Vehicle                                                 | Orbit & Mass             | Outcome |
| ----------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------- | ------------------------ | ------- |
| [[Launch/Launches/014 - I Can't Believe It's Not Optical.md\|014 - I Can't Believe It's Not Optical]] | [[Organization/Partners/Capella Space.md\|Capella Space]]                                                                                                                                                                                                                                     | 2020-08-31 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 500 km \| 45° \| 100 kg  | ✅       |
| [[Launch/Launches/013 - Pics Or It Didn't Happen.md\|013 - Pics Or It Didn't Happen]]                 | <ul><li>[[Organization/Partners/Planet Labs.md\|Planet Labs]]</li><li>[[Organization/Partners/Spaceflight.md\|Spaceflight]]</li><li>[[Organization/Partners/Canon Electronics.md\|Canon Electronics]]</li><li>[[Organization/Partners/In-Space Missions.md\|In-Space Missions]]</li></ul> | 2020-07-04 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 500 km \| 97.5° \| 75 kg | ❌       |

%% DATAVIEW_PUBLISHER: end %%

### Q2 2020

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2020-04") OR startswith(launch_date, "2020-05") OR startswith(launch_date, "2020-06"))
SORT launch_date DESC

```
%%

| Launch                                                                  | Customer                                                                                                                                                                                                                                                                                                                              | Date (UTC) | Vehicle                                                 | Orbit & Mass                         | Outcome |
| ----------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------- | ------------------------------------ | ------- |
| [[Launch/Launches/012 - Don't Stop Me Now.md\|012 - Don't Stop Me Now]] | <ul><li>[[Organization/Partners/Boston University.md\|Boston University]]</li><li>[[Organization/Partners/NASA.md\|NASA]]</li><li>[[Organization/Partners/National Reconnaissance Office (NRO).md\|National Reconnaissance Office (NRO)]]</li><li>[[Organization/Partners/UNSW Canberra Space.md\|UNSW Canberra Space]]</li></ul> | 2020-06-13 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 570 x 590 km \| 97.75° \| Classified | ✅       |

%% DATAVIEW_PUBLISHER: end %%

### Q1 2020

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2020-01") OR startswith(launch_date, "2020-02") OR startswith(launch_date, "2020-03"))
SORT launch_date DESC

```
%%

| Launch                                                                    | Customer                                                                                                | Date (UTC) | Vehicle                                                 | Orbit & Mass                | Outcome |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------- | --------------------------- | ------- |
| [[Launch/Launches/011 - Birds of a Feather.md\|011 - Birds of a Feather]] | [[Organization/Partners/National Reconnaissance Office (NRO).md\|National Reconnaissance Office (NRO)]] | 2020-01-31 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 400 km \| 37° \| Classified | ✅       |

%% DATAVIEW_PUBLISHER: end %%

## 2019


### Q4 2019

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2019-10") OR startswith(launch_date, "2019-11") OR startswith(launch_date, "2019-12"))
SORT launch_date DESC

```
%%

| Launch                                                                            | Customer                                                                                                                                                                                 | Date (UTC) | Vehicle                                                 | Orbit & Mass                 | Outcome |
| --------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------- | ---------------------------- | ------- |
| [[Launch/Launches/010 - Running Out Of Fingers.md\|010 - Running Out Of Fingers]] | <ul><li>[[Organization/Partners/Alba Orbital.md\|Alba Orbital]]</li><li>[[Organization/Partners/Spaceflight.md\|Spaceflight]]</li><li>[[Organization/Partners/ALE.md\|ALE]]</li></ul> | 2019-12-06 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 385 x 400 km \| 97° \| 77 kg | ✅       |
| [[Launch/Launches/009 - As The Crow Flies.md\|009 - As The Crow Flies]]           | [[Organization/Partners/Astro Digital.md\|Astro Digital]]                                                                                                                                | 2019-10-17 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 1200 km \| 87.9° \| 20 kg    | ✅       |

%% DATAVIEW_PUBLISHER: end %%

### Q3 2019

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2019-07") OR startswith(launch_date, "2019-08") OR startswith(launch_date, "2019-09"))
SORT launch_date DESC

```
%%

| Launch                                                                  | Customer                                                                                                                                                                                             | Date (UTC) | Vehicle                                                 | Orbit & Mass             | Outcome |
| ----------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------- | ------------------------ | ------- |
| [[Launch/Launches/008 - Look Ma, No Hands.md\|008 - Look Ma, No Hands]] | <ul><li>[[Organization/Partners/BlackSky.md\|BlackSky]]</li><li>[[Organization/Partners/U.S. Air Force.md\|U.S. Air Force]]</li><li>[[Organization/Partners/Unseenlabs.md\|Unseenlabs]]</li></ul> | 2019-08-19 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 510 km \| 94.8° \| 80 kg | ✅       |

%% DATAVIEW_PUBLISHER: end %%

### Q2 2019

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2019-04") OR startswith(launch_date, "2019-05") OR startswith(launch_date, "2019-06"))
SORT launch_date DESC

```
%%

| Launch                                                        | Customer                                                                                                                                                                                                                 | Date (UTC) | Vehicle                                                 | Orbit & Mass            | Outcome |
| ------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | ------------------------------------------------------- | ----------------------- | ------- |
| [[Launch/Launches/007 - Make it Rain.md\|007 - Make it Rain]] | <ul><li>[[Organization/Partners/Spaceflight.md\|Spaceflight]]</li><li>[[Organization/Partners/BlackSky.md\|BlackSky]]</li><li>[[Organization/Partners/Melbourne Space Program.md\|Melbourne Space Program]]</li></ul> | 2019-06-29 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 450 km \| 45° \| 80 kg  | ✅       |
| [[Launch/Launches/006 - STP-27RD.md\|006 - STP-27RD]]         | <ul><li>[[Organization/Partners/U.S. Air Force.md\|U.S. Air Force]]</li><li>[[Organization/Partners/York Space Systems.md\|York Space Systems]]</li></ul>                                                              | 2019-05-05 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 500 km \| 40° \| 180 kg | ✅       |

%% DATAVIEW_PUBLISHER: end %%

### Q1 2019

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2019-01") OR startswith(launch_date, "2019-02") OR startswith(launch_date, "2019-03"))
SORT launch_date DESC

```
%%

| Launch                                                    | Customer                                  | Date (UTC) | Vehicle                                                 | Orbit & Mass              | Outcome |
| --------------------------------------------------------- | ----------------------------------------- | ---------- | ------------------------------------------------------- | ------------------------- | ------- |
| [[Launch/Launches/005 - DARPA R3D2.md\|005 - DARPA R3D2]] | [[Organization/Partners/DARPA.md\|DARPA]] | 2019-03-28 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 425 km \| 39.5° \| 150 kg | ✅       |

%% DATAVIEW_PUBLISHER: end %%

## 2018

### Q4 2018

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2018-10") OR startswith(launch_date, "2018-11") OR startswith(launch_date, "2018-12"))
SORT launch_date DESC

```
%%

| Launch                                                                    | Customer                                                                                                                                                                                                                                   | Date (UTC) | Vehicle                                                 | Orbit & Mass           | Outcome |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | ------------------------------------------------------- | ---------------------- | ------- |
| [[Launch/Launches/004 - NASA ELaNa-19.md\|004 - NASA ELaNa-19]]           | [[Organization/Partners/NASA.md\|NASA]]                                                                                                                                                                                                    | 2018-12-16 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 500 km \| 85° \| 78 kg | ✅       |
| [[Launch/Launches/003 - It's Business Time.md\|003 - It's Business Time]] | <ul><li>[[Organization/Partners/Spire Global.md\|Spire Global]]</li><li>[[Organization/Partners/Tyvak Nano-Satellite Systems.md\|Tyvak Nano-Satellite Systems]]</li><li>[[Organization/Partners/Fleet Space.md\|Fleet Space]]</li></ul> | 2018-11-11 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 500 km \| 85° \| 45 kg | ✅       |

%% DATAVIEW_PUBLISHER: end %%

### Q1 2018

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2018-01") OR startswith(launch_date, "2018-02") OR startswith(launch_date, "2018-03"))
SORT launch_date DESC

```
%%

| Launch                                                          | Customer                                                                                                                                  | Date (UTC) | Vehicle                                                 | Orbit & Mass             | Outcome |
| --------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------- | ------------------------ | ------- |
| [[Launch/Launches/002 - Still Testing.md\|002 - Still Testing]] | <ul><li>[[Organization/Partners/Planet Labs.md\|Planet Labs]]</li><li>[[Organization/Partners/Spire Global.md\|Spire Global]]</li></ul> | 2018-01-21 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 400 km \| 82.9° \| 13 kg | ✅       |

%% DATAVIEW_PUBLISHER: end %%

## 2017

### Q2 2017

%% DATAVIEW_PUBLISHER: start
```
TABLE WITHOUT ID
  file.link as "Launch", customer as "Customer",
  regexreplace(launch_date, " .*", "") as "Date (UTC)", vehicle as "Vehicle",
  (target_orbit + " | " + payload_mass) as "Orbit & Mass", outcome as "Outcome"
FROM "Launch/Launches"
WHERE launch_date AND (startswith(launch_date, "2017-04") OR startswith(launch_date, "2017-05") OR startswith(launch_date, "2017-06"))
SORT launch_date DESC

```
%%

| Launch                                                      | Customer | Date (UTC) | Vehicle                                                 | Orbit & Mass          | Outcome |
| ----------------------------------------------------------- | -------- | ---------- | ------------------------------------------------------- | --------------------- | ------- |
| [[Launch/Launches/001 - It's a Test.md\|001 - It's a Test]] | N/A      | 2017-05-25 | [[Space Systems/Launch Vehicles/Electron.md\|Electron]] | 500 km \| 85° \| 0 kg | ❌       |

%% DATAVIEW_PUBLISHER: end %%