
**GEOST** is a Tucson-based aerospace company, acquired by Rocket Lab in 2025, that specializes in advanced **electro-optical (EO)** and **infrared (IR)** sensors for missile detection, fire control, and satellite threat monitoring. Their payloads are being integrated into the **U.S. Space Development Agency (SDA)**'s **Tracking Layer** constellation for missile defense.

---

## 🔬 What is Electro-Optical?

> A sensor system that uses **optics (lenses, mirrors)** to gather light — including **visible, infrared, or ultraviolet** — and converts it into **electronic signals** for imaging, detection, or tracking.

Electro-optical payloads operate like highly specialized cameras, but often “see” **outside the visible spectrum**, such as in the **infrared**, to detect missile plumes or laser threats.

**Cant See Through Weather / Thick Clouds** (Opportunity for AST / large phased array to detect RF signatures to fill that gap?)

Saw some confusion: EO vs Optical Lasercom Terminals - kinda unclear what GEOST does here, not much information, no contracts that I could find

## What is IR? 
Predator vision. 
Able to detect things outside the visible spectrum, like heat. 

## 3 Sensor Payloads - Suite of payloads for whole solution

- **Mercury** - Detect - more deployed
- **Pheonix** - Track - Ground Station Component - Fire Solution - fewer deployed
- --
- Starlite - directed energy sensor - potentially every Tranche 3 Tracking

---

# ⚙️ SDA Tracking Layer Payloads from GEOST

"Each T2 Tracking Layer satellite will carry an IR payload to detect and track missiles using their heat signatures"

GEOST doesn't really share info about products but we have some info based on previous contracts

Mercury + Phoenix: 18 total sensors (16 Mercury, 2 Phoenix) for Sierra Space’s SDA Tranche 2 (launches expected by 2026–2027)

---

## 🚨 **Mercury** – Wide-Field Infrared Missile Warning Sensor

**Purpose:**
To provide **early detection of missile launches**, including hypersonic glide vehicles, by identifying hot exhaust plumes from space.

> “All they’re doing is basically identifying that there’s an object, a missile or a threat, in that frame and in that picture.”

### 🧠 How It Works:

* **Type:** Wide-field infrared (IR) sensor (likely mid-wave or short-wave IR)
* **Field of View:** Wide-area coverage (\~tens of degrees)
* **Spectral Band:** Designed to detect the heat signature of missile plumes. Mid-Wave or Long-Wave IR likely (3–5μm or 8–12μm likely)
* **Weather**: Missile plume sensors like GEOST's Mercury are likely MWIR or LWIR, optimized to detect the bright heat of a launch, which can sometimes be seen through thin cirrus or broken clouds — but not reliably through heavy weather or storms.
* **Processing:** Onboard compute detects and tracks moving hot objects
* **Orbit:** Optimized for **LEO** to enable fast revisit times and global constellation coverage

### 🛠️ Technical Highlights:

* Detects ballistic and hypersonic missile launches via **thermal signature**
* Performs **real-time detection and initial trajectory estimation**
* Fully autonomous threat detection with **minimal latency**
* Integrates into SDA’s **distributed constellation** for resilient coverage

---

## 🎯 **Phoenix** – High-Resolution Fire Control Sensor

**Purpose:**
To provide **precise tracking data** required for fire control systems to generate **interceptor firing solutions** after a missile has been detected. Provides a Fine-tuned trajectory and position data suitable for **interceptor targeting**

> “It’s accurate enough and tracking enough that you can actually see that object and create what they call a firing solution against it.”

### 🧠 How It Works:

* **Type:** Narrow-field high-resolution infrared sensor
* **Field of View:** Small — zoomed-in on known object tracks
* **Function:** Continuously tracks known missile targets with high accuracy
* **Output:** Fine-tuned trajectory and position data suitable for **interceptor targeting**

### 🛠️ Technical Highlights:

* Tracks fast-moving missile threats with **sub-pixel accuracy**
* Works in tandem with Mercury (or similar) to transition from **“detect” to “track”**
* Generates data needed for **hit-to-kill guidance**
* (Both of these payloads ) are Designed to be **small and affordable**, ideal for mass deployment in LEO constellations



## Analogy

"Security Cameras and Motion Sensors in a Smart Home"

Phoenix is like the motion sensors: they are always watching a broad area, detecting heat signatures and movement (infrared).

Mercury is like the security cameras: once motion is detected, they zoom in with sharper detail (electro-optical), helping identify what the object actually is.

Together, they provide broad coverage plus detail—Phoenix alerts you to a potential intruder, and Mercury helps you tell whether it’s the dog, a neighbor, or a burglar.

---



## ✨ **Starlite** – Compact Resiliency & Threat Detection Payload

## “directed energy sensor”

**Purpose:**
To enhance **satellite survivability** by autonomously detecting and reporting **electronic interference** and **directed energy threats** such as jamming, spoofing, or laser dazzling.
### Size of  Soda Can

Note: "Each T2 Tracking Layer satellite will carry an IR payload to detect and track missiles using their heat signatures, optical communications terminals to connect the satellites to each other and to SDA’s Transport Layer of data relay birds, and Ka-band and S-band communications payloads.  Some will also be equipped with a “directed energy sensor,” a sign SDA is at least planning for potential laser-interference attempts against their systems."

TT&C - Telemetry, Tracking, and Command

https://breakingdefense.com/2023/09/geost-sensors-to-detect-interference-will-fly-on-sda-satellites/

It appears Tranche 3 has directed energy sensors as a requirement for all birds

“resiliency feature to protect against directed energy attack mechanisms” 


> “Designed to see something anomalous happening, say something, and let others act on it.”

### 🧠 How It Works:

* **Type:** Multi-modal EO + RF payload
* **Sensors:**

  * **EO detectors** (visible/NIR) for laser or optical interference
  * **RF spectrum monitors** for uplink jamming/spoofing
* **Onboard AI:** Baselines environmental “normal” and flags anomalies
* **Data Handling:** Sends threat reports to a **dedicated ground system**

### 🛠️ Technical Highlights:

* Soda-can sized package for **low-SWaP** integration
* Detects hostile activity (e.g. GPS jamming, uplink interference, laser targeting)
* Executes “**See → Say → Act**”:

  * **See** the threat (via EO or RF sensing)
  * **Say** by reporting to operators or adjacent nodes
  * **Act** via autonomous countermeasure triggers or notification trees
* Integrated with SDA’s broader **space defense infrastructure**

---

## 🚀 Deployment Status

As of June 2025:

* GEOST has **not yet flown any of these payloads**.
* **Starlite**: 8 units contracted for Northrop Grumman’s SDA Tranche 1 satellites (launch expected 2025)
* **Mercury + Phoenix**: 18 total sensors (16 Mercury, 2 Phoenix) for Sierra Space’s SDA Tranche 2 (launches expected by 2026–2027)

---

