---
name: Missile Defense Agency
website: https://www.mda.mil/
---
[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Partners]] <span style="color: LightSlateGray">></span> Missile Defense Agency
## Partner Details

**Website**: https://www.mda.mil/

The Missile Defense Agency (MDA) is a U.S. Department of Defense agency responsible for developing and fielding a layered Ballistic Missile Defense System (BMDS) to protect the U.S., its forces, allies, and friends from missile attacks in all flight phases. Formed in 2002, the MDA researches, develops, tests, and acquires systems that detect, track, intercept, and destroy incoming missiles, working to counter evolving threats from short-range to intercontinental ballistic missiles. 

![[Pasted image 20251211021925.png|300]]

## ## Launches

%%DATAVIEW_PUBLISHER: start
```
table launch_date as "Date", location as "Location", vehicle as "Vehicle", target_orbit + " | " + payload_mass as "Orbit & Mass", outcome as "Outcome"
from "Launch/Launches"
where contains(customer, [[]])
sort launch_date desc
```
%%

| File                                                              | Date             | Location                                               | Vehicle                    | Orbit & Mass          | Outcome |
| ----------------------------------------------------------------- | ---------------- | ------------------------------------------------------ | -------------------------- | --------------------- | ------- |
| [[Launch/Launches/075 - Prometheus Run.md\|075 - Prometheus Run]] | 2025-11-18 13:00 | [[Locations/Launch Complex 2.md#Launch Pad 0C\|LC2-0]] | [[Launch/HASTE.md\|HASTE]] | Suborbital \| unknown | ✅       |

%%DATAVIEW_PUBLISHER: end %%

## News
%%DATAVIEW_PUBLISHER: start
```
table published as "Published"
from "News"
where contains(customer, [[]])
sort published desc
```
%%

| File                                                                                                                                                                                                               | Published         |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------- |
| [[News/Rocket Lab Successfully Launches HASTE Mission for Defense Innovation Unit, Missile Defense Agency.md\|Rocket Lab Successfully Launches HASTE Mission for Defense Innovation Unit, Missile Defense Agency]] | November 18, 2025 |

%%DATAVIEW_PUBLISHER: end %%