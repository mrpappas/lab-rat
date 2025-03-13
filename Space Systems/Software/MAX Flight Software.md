
**Subsidiary:** [[Advanced Solutions Inc]]

>[!summary]
>MAX (Modular Autonomous eXtendible) is a comprehensive Flight Software framework. It is also a collection of C++ objects and algorithms uniquely designed for use on nearly any type of aerospace vehicle. Though the typical vehicle application is satellites, MAX has also been applied to payloads, transfer vehicles, lunar landers, space-planes, and atmospheric flight vehicles.
>
>🔗 https://www.rocketlabusa.com/space-systems/space-software/
[📄 MAX and SOLIS Documentation](https://max.rocketlabusa.com/docs#Welcome.md) 
📰 [[RL-MAX-FSW-Brochure- (1).pdf|Max FSW Brochure]]

## 🛠️ Features

- Full [FSW](https://www.nasa.gov/wp-content/uploads/2015/04/flight_software.pdf) library for all spacecraft functions including [GN&C](https://en.wikipedia.org/wiki/Guidance,_navigation,_and_control)
- [ODySSy](https://www.youtube.com/watch?v=KpcWV5Au-sc&t=1s) - Onboard Dynamic Simulation System
- Max Constellation
- [SEQUENCER](https://www.youtube.com/watch?v=QdgcHttgbSY) – Providing highly autonomous operation
- [MAX DevTool](https://www.youtube.com/watch?v=JFpChd3BHV8) - Auto-Coding for customizing your flight software
- MAX GDS (Ground Data System) for interacting with MAX



![[Pasted image 20250312184721.png]]

## Max Constellation

>[!warning]
>Not many specifics are known at this time. This page will be updated as new information becomes available. 

MAX Constellation is an evolution of Rocket Lab’s MAX Flight Software, the industry-leader in on-board software that has been proven in every orbit and to the surface of the moon. MAX Constellation builds on this success by delivering enhanced performance, automation, and cybersecurity for constellation-class programs. MAX Constellation includes ODySSy, Rocket Lab’s powerful digital twin platform, providing high-fidelity simulations of spacecraft components, dynamics, and environments.

## ODySSy

When MAX Flight Software is running in [[SOLIS]] or on a flight processor in the lab, it (typically) does not interact with real actuators, sensors, or the space environment. To replace those interactions, while allowing the flight software to behave just like it will in space, ASI has developed ODySSy as simulation software that closes the loop for MAX. What makes ODySSy unique from simulation software used on other spacecraft is that it is running "onboard". In a world where processors are more and more capable the downside of having extra computational overhead is outweighed by the massive benefit of avoiding having to integrate external simulation software. ODySSy was built to integrate seamlessly with MAX. And when a spacecraft is ready to fly (and simulation is no longer required), users simply don't include the ODySSy components in the config files and ODySSy will no be instantiated.

![[Pasted image 20250312215731.png]]


## SEQUENCER

MAX utilizes sequences for autonomy and automatic commanding without ground intervention. Many of the startup processes are completed with sequences that begin immediately after boot, but there are a variety of applications for sequencing. The Sequencer, an ASI product, parses and executes the sequences on board. These sequences are scripted in [FlightJAS](https://max.rocketlabusa.com/docs#MAX/Sequencing/FlightJAS.md), a language that is derived and extended from the JAS (Just Another Syntax) language from L3Harris.

![[Pasted image 20250312220457.png]]

## MAX DevTool

MAX DevTool provides a quick way to develop new and custom software components to integrate into MAX FSW. An input XML file defines the software components, connections, and parameters to create. The DevTool reads this file and outputs auto-generated MAX C++ framework files as a Visual Studio solution and/or makefiles. All you must provide is algorithmic implementation for the various framework stubs.

![[Pasted image 20250312220409.png]]

---

<div class="responsive-video">
<iframe src="https://www.youtube.com/embed/7oozDn1OVa4" title="Introduction to MAX | ASI by Rocket Lab" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

