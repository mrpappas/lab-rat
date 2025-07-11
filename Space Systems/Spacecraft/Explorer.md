[[Home|🏠]] <span style="color: LightSlateGray">></span> [[Space Systems]] <span style="color: LightSlateGray">></span> Explorer
## Summary

Explorer is a high Delta-v spacecraft with large propellant tanks, deep space capable avionics, and ranging transponders. Explorer enables small spacecraft missions to planetary destinations like Mars and Venus, the Moon, highly eccentric Earth orbits, geosynchronous Earth orbit (GEO), Earth-moon Lagrange points, Earth-sun Lagrange points, and near Earth objects (NEOs). Depending on the mission profile, Explorer can be launched on [[Electron]], [[Neutron]] or other launch vehicles. Explorer gained flight heritage during the [[CAPSTONE]] mission to the Moon for NASA and forms the basis of the twin spacecraft Rocket Lab is developing for the [[ESCAPADE]] mission to Mars for NASA and the University of California, Berkeley.  
🔗 https://rocketlabcorp.com/space-systems/spacecraft/

![[Pasted image 20250630195149.png]]
## Missions

| Mission      | Status      |
| ------------ | ----------- |
| [[CAPSTONE]] | Launched    |
| [[ESCAPADE]] | In Progress |
## Spacecraft

1. [[#Lunar Photon]]
2. [[#ESCAPADE]]

### Lunar Photon

#### Summary
**Lunar Photon** was developed as a high Delta-v variant of the [[Photon]] bus (now called Explorer) to deliver the [[#Payload|CAPSTONE]] spacecraft onto a ballistic transfer orbit to the Moon. As part of the mission, Lunar Photon, with Advanced Space’s CAPSTONE attached, orbited the Earth in elliptical phasing orbits over six days to build up velocity for a Trans Lunar Injection (TLI) to deploy CAPSTONE into the deep space, low energy transfer orbit to the vicinity of the Moon.

[[CAPSTONE|🛰️ CAPSTONE Mission]]

![[Pasted image 20250630194253.png|400]]

#### Specifications

🔗 [Lunar Photon Brochure](https://rocketlabcorp.com/assets/Uploads/EXC22_017%20-%20Photon%20Doc_%C6%92%20[Web].pdf)

| Specification                | Value                                                                                                                         |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| Dry Mass                     | 55 kg                                                                                                                         |
| Orbit Options                | LEO, MEO, GEO, Moon, Mars, Venus                                                                                              |
| Volume                       | 1.4 m x 1.1 m x 1.0 m                                                                                                         |
| Avionics                     | Single string, radiation tolerant                                                                                             |
| Propulsion                   | [[Curie Engine#HyperCurie\|HyperCurie]]                                                                                       |
| Solar Array Power            | 140 W (BOL), body fixed solar panels                                                                                          |
| Communications               | [[Frontier Radio#Frontier-S\|Frontier S]] radio 2.5 kbps to 1Mbps downlink, 2 kbps uplink, ranging and doppler for navigation |
| Launch Vehicle Compatibility | Electron and ESPA Grande Rideshare Compatible                                                                                 |
| Available Payload Volume     | Electron Fairing                                                                                                              |
| Receive Frequency Range      | 2067-2110 MHz                                                                                                                 |
| Transmit Frequency Range     | 2245-2290 MHz                                                                                                                 |
| Delta-V                      | >3.2 km/sec                                                                                                                   |
| Mission Assurance            | NASA Class D equivalent                                                                                                       |
| Pointing Accuracy            | 0.3                                                                                                                           |
| Onboard Data Storage         | 1-9GB                                                                                                                         |
| Link Performance             | G/TSys -30.6 dB/K,<br>EIRP -2 dBW<br>(On Boresight)                                                                           |
| Energy Storage               | Two 8s1p (33.6V 4200mAh) strings connected in parallel to SPOC                                                                |
| Attitude Control             | Star trackers, reaction wheels, cold gas reaction, and fine sun sensors                                                       |
| Payload Interfaces           | Ethernet, USB, and Serial                                                                                                     |
| RHCP                         | Up and down                                                                                                                   |

#### Payload

##### [[Advanced Space#CAPSTONE]]

![[Advanced Space#CAPSTONE#Summary]]



### ESCAPADE

#### Summary
**NASA’s Escape and Plasma Acceleration and Dynamics Explorers (ESCAPADE)** mission will measure plasma and magnetic fields around the red planet, helping scientists learn more about the processes that strip away atoms from Mars’ magnetosphere and upper atmosphere, driving Martian climate change. Rocket Lab has designed and built twin spacecraft based on the Explorer bus, called Blue and Gold, to enable the mission.

🚀 [[ESCAPADE|ESCAPADE Mission]]

![[Pasted image 20250701021732.png]]


#### Specifications

🔗 [ESCAPADE Press Kit](https://rocketlabcorp.com/assets/Uploads/RL-ESCAPADE-Press-Kit2.pdf)

| Specification                   | Value                                                                                                                                                                                                                                                       |
| ------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Size                            | Stowed: 1.20 m x 1.65 m x 1.09 m<br>Deployed: 4.88 m x 1.65 m x 1.09 m                                                                                                                                                                                      |
| Dry Mass                        | 209 kg                                                                                                                                                                                                                                                      |
| Wet Mass                        | 535 kg                                                                                                                                                                                                                                                      |
| Propulsion                      | [[Curie Engine#HyperCurie\|HyperCurie]]                                                                                                                                                                                                                     |
| On-board tanks                  | • 2x fuel tanks, additively manufactured metal<br>• 2x oxidizer tanks, additively manufactured metal<br>• 2x pressurant (He) tanks, Composite Overwrap Pressure<br>Vessel (COPV)<br>• 4x RCS (N2) tanks, COPV                                               |
| Power                           | **Science (nominal) mode power draw:**<br>128 W (about as much as a tea kettle)<br>**Power generation at Earth:** 800W<br>**Power generation at Mars (aphelion):** 288W<br>**Energy storage:** 7s5p battery assembly                                        |
| Avionics                        | Redundant flight computer and redundant radios                                                                                                                                                                                                              |
| Guidance and Navigation Control | **Sensors**: 2x Star Trackers, 4x Fine Sun Sensors<br>**Actuators**: 4x Reaction Wheels, Reaction Control thrusters                                                                                                                                         |
| Communications                  | **Total planned downlinked science data:** 45Gb<br>**Rocket Lab Frontier-X radios**<br>**Antennas**:<br>• 4x low-gain patch antennas<br>• 2x medium gain patch antennas<br>• 1x radial line slot array high gain antenna<br>**Uplink and Downlink**: X-band |

#### Science Payloads

Each identical spacecraft has three science experiments payloads onboard: 
1. [[#EMAG]]
2. [[#EESA]]
3. [[#ELP]] 
🔗 https://escapade.ssl.berkeley.edu/instruments/

![[Pasted image 20250711172704.png]]
##### EMAG
Developed by the [NASA Goddard Spaceflight Center](https://www.nasa.gov/goddard/), EMAG is a [magnetometer](https://en.wikipedia.org/wiki/Magnetometer) that will measure DC magnetic fields from 0 - 2 μT, with an accuracy of 0.5 nT and angular resolution of 20° for field strengths above 1 nT, mounted at the end of the boom to reduce magnetic noise from the spacecraft. 

| Specifications  | Value |
| --------------- | ----- |
| Mass (kg)       | 0.45  |
| Power (W)       | 1.30  |
| Data rate (bps) | 21.5  |

![[Pasted image 20250702185638.png]]
##### EESA 
EESA consists of two [electrostatic analyzers](https://en.wikipedia.org/wiki/Electrostatic_analyzer) to detect suprathermal ions (EESA-i) and electrons (EESA-e). EESA-i will measure ion energetics between 0.5 eV - 30 keV and EESA-e will measure electron energetics between 10 eV and 10 keV. Both instruments have an energy resolution (ΔE/E) of 17% and angular resolution of 23°x 23°. EESA-e has a pitch-angle distribution (PAD) ranging from 20 - 160°. EESA was developed by UCB SSL.

| Specifications  | Value    |
| --------------- | -------- |
| Mass (kg)       | 5.34     |
| Power (W)       | 6.10     |
| Data rate (bps) | 183 + 67 |

![[Pasted image 20250702185746.png]]
##### ELP
Developed by the [Space and Atmospheric Instrumentation Lab](https://daytonabeach.erau.edu/college-arts-sciences/research/sail) at Embry-Riddle Aeronautical University, is a [Langmuir probe](https://en.wikipedia.org/wiki/Langmuir_probe) consisting of three separate sensors: the multi-needle Langmuir probe (mNLP) consists of 4 thin needles mounted in two pairs ~3/4 way up the boom and measures thermal electron density; the two planar ion probes (PIPs) are mounted on the instrument deck and measure thermal ion density, and the floating potential probe (FPP) is also mounted on the spacecraft deck and measures changes in relative spacecraft electrostatic potential.

| Specifications  | Value |
| --------------- | ----- |
| Mass (kg)       | 0.54  |
| Power (W)       | 0.95  |
| Data rate (bps) | 10.8  |
![[Pasted image 20250702185758.png]]