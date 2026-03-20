# ⚡ EAVB ARCHON 15W Power Hub
**High-Efficiency DC-DC Step-Down Architecture with PMOS Protection**

Designed by **Elcyn Andrew V. Booc** | EAVB Electronics

The **ARCHON Power Hub** is a compact, industrial-grade power management module designed for autonomous robotics, IoT systems, and high-reliability embedded environments. Utilizing a 1.5 MHz switching frequency and the proprietary "Ocean Ground Strategy," ARCHON delivers up to 15W of continuous power with exceptional thermal stability and minimal EMI.

---

### 🛡️ Key Architectural Features
* **Zero-Drop Reverse Polarity Protection:** Utilizes an AO4407A P-Channel MOSFET instead of a standard Schottky diode, eliminating thermal dissipation and voltage drop at the input stage.
* **The "Ocean Ground Strategy":** A highly optimized SMD PCB layout utilizing extensive ground pours and thermal via stitching to turn the entire FR4 board into a passive heatsink.
* **High-Frequency Regulation:** Driven by the MP1584EN switching regulator operating at 1.5 MHz, allowing for extreme component density and rapid transient response.
* **Industrial Form Factor:** Exclusively utilizes Surface Mount Devices (SMD), including 0805 passives and SOIC-8 packaging, for a manufacturing-ready footprint.

---

### 📊 Absolute Maximum Ratings & Specifications

| Parameter | Specification | Notes |
| :--- | :--- | :--- |
| **Input Voltage Range** | 4.5V to 28V DC | Regulated |
| **Output Voltage** | 5.0V (Adjustable) | Tuned via precision resistor network |
| **Max Continuous Current** | 3A | Requires adequate airflow at max load |
| **Maximum Power Output** | 15W | |
| **Peak Efficiency ($\eta$)** | Up to 92% | Load dependent |
| **Switching Frequency** | 1.5 MHz | Reduces inductor size requirement |

---

### 📂 Repository Structure
* `/Hardware` - KiCad schematic (`.kicad_sch`), PCB layout (`.kicad_pcb`), and manufacturing Gerber files.
* `/Docs` - Official EAVB technical specifications, absolute maximum ratings, and theory of operation (PDF).

---

### ⚖️ Intellectual Property & Commercial Licensing
This hardware design is protected under the **CC BY-NC-SA 4.0** license. 
* **Non-Commercial Use:** Students, hobbyists, and researchers are free to study, build, and modify this architecture for personal or academic use, provided credit is given to **EAVB Electronics**.
* **Commercial Use:** Manufacturing this board for sale or integrating this architecture into a commercial product is strictly prohibited under this license.

> **💼 For Commercial Manufacturing Rights:** > Please contact the Lead Architect at **eavb.electronics@gmail.com** for corporate licensing agreements.
