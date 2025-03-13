
**Subsidiary:** [[Advanced Solutions Inc]]

>[!summary]
SOLIS is a commercial plug-in to the [ANSYS, Inc Systems ToolKit (STKTM)](https://www.ansys.com/products/missions/ansys-stk) mission analysis software, providing integrated end-to-end spacecraft simulation. Running [[MAX Flight Software]] and [[MAX Flight Software#ODySSy|ODySSy]], SOLIS provides simulation capabilities of all major spacecraft subsystems.
>
>🔗 https://www.rocketlabusa.com/space-systems/space-software/
>[📄 MAX and SOLIS Documentation](https://max.rocketlabusa.com/docs#Welcome.md)

![[Pasted image 20250312190140.png]]
## 🛠️ Features

### Attitude Disturbance Modeling
- Magnetic dipole, gravity gradient, solar and aerodynamic forces

### Attitude Determination Modeling / Guidance
- Sun sensors, horizon sensors, rate sensors, IMUs, magnetometers, star trackers, simulated GPS
- Perfect attitude determination, fixed-gain filter, Kalman filter
- Orbit determination, ephemeris propagation

### Attitude Control Modeling
- Reaction wheels, magnetic torquers, thrusters
- Perfect control, PIID control
- Mode Control
- Idle, Inertial Hold, Rate Damp
- Numerous Tracking and Clocking Modes: Inertial Point, Sun Track, Nadir Track, Velocity Track, Mag Field Track, Target Tracking, Inertial Vector Tracking, Orbit Normal Track, Surface Relative Velocity Track, Rotisserie, External Guidance, Nadir Scan, Lat/Lon Scan
	- Eigen-Axis Slew, Optimized "Rendez-Slew"

### Power/Thermal Modeling
- Distance-dependent solar flux, central body infrared, albedo
- Finite element thermal; absorptivity, emissivity, conductivity, shunt
- Solar panel size, efficiency, articulation, temperature dependency
- Battery capacity, charge/discharge regulation
- Dynamic spacecraft loads; payload power, comm system power, reaction wheel power

### Payload/Communications/Data Modeling
- Off, On, Standby
- Define multiple payload modes; power consumption, data collection
- Transmitters, receivers, transceivers; data rates, overhead, power consumption
- Data recorder size, current state
- Command/telemetry availability when ground stations are visible

### Flight Emulation
- Mission sequence modeling, real-time commanding, telemetry

## ✅ Applications

- System/Mission Requirements
	Requirements definition, feasibility studies, component selection
- Conceptual Design
	Analyze various system concepts to determine which can meet mission requirements
- Preliminary Design
	Variations of conceptual designs are analyzed and refined
	Define subsystem and component level specifications
- Critical Design
	Final design verification of subsystem models and components
- Risk Reduction and IV&V
	Independent validation and sensitivity/margin analysis


![[Pasted image 20250312190058.png]]

<div class="responsive-video">
<iframe src="https://www.youtube.com/embed/DxgVA5zfLIc" title="Introduction to SOLIS | ASI by Rocket Lab" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

