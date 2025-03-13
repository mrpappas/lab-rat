---

subsidiary: "[[Advanced Solutions Inc]]"
---

**Subsidiary:** [[Advanced Solutions Inc]]

>[!summary]
>Flight proven off-the-shelf flight software providing the foundation for complex space missions from day one.
>
MAX FSW Includes:
>- Full [FSW](https://www.nasa.gov/wp-content/uploads/2015/04/flight_software.pdf) library for all spacecraft functions including [GN&C](https://en.wikipedia.org/wiki/Guidance,_navigation,_and_control)
>- [SEQUENCER](https://www.youtube.com/watch?v=QdgcHttgbSY) – Providing highly autonomous operation
>- [ODySSy](https://www.youtube.com/watch?v=KpcWV5Au-sc&t=1s) - Onboard Dynamic Simulation System
>- [MAX DevTool](https://www.youtube.com/watch?v=JFpChd3BHV8) - Auto-Coding for customizing your flight software
>- MAX GDS (Ground Data System) for interacting with MAX
>
>🔗 https://www.rocketlabusa.com/space-systems/space-software/max-flight-software/
[📄 MAX and SOLIS Documentation](https://max.rocketlabusa.com/docs#Welcome.md)

![[Pasted image 20250312184721.png]]
## ODySSy

ODySSy (On-board Dynamic Simulation System) is a subset of MAX components providing full life-cycle Built-In Simulation/Test for rapid spacecraft AI&T, a key for maintaining any aggressive schedule. This makes MAX FSW unique in that it allows testing of actual mission sequences on the spacecraft while in various stages of development, assembly, test and launch operations; all without any external support equipment or simulators.

## SEQUENCER

MAX utilizes sequences for autonomy and automatic commanding without ground intervention. Many of the startup processes are completed with sequences that begin immediately after boot, but there are a variety of applications for sequencing. The Sequencer, an ASI product, parses and executes the sequences on board. These sequences are scripted in [FlightJAS](https://max.rocketlabusa.com/docs#MAX/Sequencing/FlightJAS.md), a language that is derived and extended from the JAS (Just Another Syntax) language from L3Harris.

## MAX DevTool

MAX DevTool provides a quick way to develop new and custom software components to integrate into MAX FSW. An input XML file defines the software components, connections, and parameters to create. The DevTool reads this file and outputs auto-generated MAX C++ framework files as a Visual Studio solution and/or makefiles. All you must provide is algorithmic implementation for the various framework stubs.



<div class="responsive-video">
<iframe src="https://www.youtube.com/embed/7oozDn1OVa4" title="Introduction to MAX | ASI by Rocket Lab" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>