<p align="center">
  <img src="Photos/banner orange.png" width="100%">
</p>

# Hi, I'm Renato Brant 👋

<p align="center">
  <a href="https://www.youtube.com/@Brant_Channel" target="_blank">
    <img src="https://img.shields.io/badge/YouTube-Brant_Channel-red?style=for-the-badge&logo=youtube">
  </a>
  <a href="https://www.linkedin.com/in/renatobrant/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Renato_Brant-blue?style=for-the-badge&logo=linkedin">
  </a>
  <a href="https://github.com/Renbrant" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-Renbrant-black?style=for-the-badge&logo=github">
  </a>
</p>

---

## 🚀 About Me

I'm Renato Brant — a technology enthusiast, maker, and lifelong learner with roots in **Mechatronics Engineering**.

My professional career is focused on **Global Business Development, Strategy, Automotive Technology, GNSS, ADAS, and high-precision positioning systems**, but this GitHub space is where I reconnect with my engineering soul.

Here I share hands-on projects involving:

- Embedded systems
- ESP32 / ESPHome / Home Assistant
- Smart home automation
- Hardware prototyping
- Audio electronics
- Camera and media tools
- Open-source learning projects

Most of these projects started from a real need in my own home, studio, car, church, or workshop — and then became something worth documenting and sharing.

---

## 🧠 What I Like to Build

```text
Legacy hardware + modern connectivity
DIY electronics + practical use cases
Smart home + real-world automation
Engineering education + Portuguese-speaking makers
````

I enjoy projects that make old equipment smarter, everyday systems more useful, and complex engineering concepts easier to understand.

---

## 🛠 Featured Projects

---

### 🌡️ [Home Assistant HVAC Balancing](https://github.com/Renbrant/home-assistant-hvac-balancing)

<p align="center">
  <a href="https://github.com/Renbrant/home-assistant-hvac-balancing">
    <img src="https://raw.githubusercontent.com/Renbrant/home-assistant-hvac-balancing/main/Photos/home-assistant-hvac-balancing.png" width="100%" alt="Home Assistant HVAC Balancing Banner">
  </a>
</p>

A smart HVAC room-balancing system built with **Home Assistant**, temperature sensors, smart register booster fans, and Nest central blower control.

The project was created to solve real temperature imbalance between floors and rooms in my house. During summer, the upstairs bedrooms tend to become warmer than the Kitchen reference area, so Home Assistant dynamically increases airflow to those rooms.

Key highlights:

* Independent temperature monitoring for Kitchen and bedrooms
* Room-to-reference temperature delta calculation
* Dynamic 10-level booster fan control
* Temperature-based adaptive speed curve
* 0.2°F hysteresis to prevent rapid speed changes
* Minimum booster airflow while the HVAC is actively cooling
* Automatic Nest central blower assistance for larger temperature differences
* 5-minute post-circulation strategy
* Desired-state control architecture for unreliable Tuya feedback
* Xtend Tuya integration for unsupported booster fan controls
* ApexCharts dashboards for real-time and historical analysis
* HVAC electrical consumption monitoring
* Automatic startup recovery and periodic state reconciliation

The current implementation has been **field-tested primarily for summer cooling operation**, where Bed 1 and Bed 2 booster fans help move more conditioned air to the upper floor.

A future winter phase will investigate a separate heating strategy, including the possible addition of a **basement booster fan** to address the opposite seasonal problem: the basement becoming significantly colder than the rest of the house.

---

### 🌱 [irriBRANT — ESP32-C6 Irrigation Controller](https://github.com/Renbrant/ESP32-C6-Irrigation-Controller)

<p align="center">
  <a href="https://github.com/Renbrant/ESP32-C6-Irrigation-Controller">
    <img src="https://raw.githubusercontent.com/Renbrant/ESP32-C6-Irrigation-Controller/main/docs/banner2.png" width="100%" alt="irriBRANT Banner">
  </a>
</p>

A professional 9-zone smart irrigation controller powered by **ESP32-C6**, designed for Home Assistant integration through ESPHome.

Key highlights:

* 9 irrigation zones
* ESP32-C6 platform
* MCP23017 I/O expansion
* MOC3041 opto-isolated triac drivers
* BT136S / TO-252 triac-based AC switching
* 24VAC irrigation valve control
* Surge and inrush protection architecture
* Local scheduling architecture
* Offline-capable design direction
* Field test and validation phase

This is one of my most complete hardware projects, combining PCB design, firmware, AC switching, enclosure planning, and smart home integration.

---

### 🔌 [ESP32-C6 Serial Controller](https://github.com/Renbrant/ESP32-C6-Serial-Controler)

A bridge between **legacy RS232 equipment** and modern smart home platforms.

Designed to control devices such as projectors, AV receivers, and professional equipment using ESP32-C6 and bidirectional serial communication.

Use cases:

* Projector automation
* AV system control
* RS232 to Home Assistant bridge
* Legacy equipment modernization

---

### 🧩 [ESPHome Serial Controller](https://github.com/Renbrant/ESPHome_serial_controller)

An ESPHome-based serial control project focused on making serial devices easier to integrate into smart home dashboards and automations.

---

### 🎬 [Arduino OBS Deck](https://github.com/Renbrant/Arduino_deck)

<p align="center">
  <a href="https://github.com/Renbrant/Arduino_deck">
    <img src="https://raw.githubusercontent.com/Renbrant/Arduino_deck/main/docs/PROMO/Banner.png" width="100%" alt="Arduino OBS Deck Banner">
  </a>
</p>

A DIY hardware controller for **OBS Studio**, built around an Arduino Pro Micro.

Features:

* HID keyboard emulation
* 8-button analog matrix using voltage dividers
* LED feedback with 74HC595 shift-register control
* Dedicated buttons for streaming, recording, and audio control
* Designed for video production and live streaming workflows

This project combines hardware simplicity with practical studio automation.

---

### ⚡ [Power Supply Monitor Arduino](https://github.com/Renbrant/Power-Supply-Monitor-Arduino)

<p align="center">
  <a href="https://github.com/Renbrant/Power-Supply-Monitor-Arduino">
    <img src="https://raw.githubusercontent.com/Renbrant/Power-Supply-Monitor-Arduino/main/docs/promo/Banner2.png" width="100%" alt="Power Supply Monitor Banner">
  </a>
</p>

A DC power monitoring tool designed for audio amplifier testing.

Features:

* Real-time voltage monitoring
* Current monitoring
* Power monitoring
* ADS1115 voltage measurement
* ACS712 current sensing
* Useful for observing voltage drops and current behavior during amplifier tests

This project came from my audio amplifier builds and the need to better understand how power supplies behave under load.

---

### 🏎 [G29 Load Cell Brake Controller](https://github.com/Renbrant/g29-load-cell-brake-controller)

<p align="center">
  <a href="https://github.com/Renbrant/g29-load-cell-brake-controller">
    <img src="https://raw.githubusercontent.com/Renbrant/g29-load-cell-brake-controller/main/overview%202.png" width="100%" alt="G29 Load Cell Brake Controller Overview">
  </a>
</p>

A precision sim-racing brake controller that replaces potentiometer-based pedal sensing with a pressure-based load cell system.

Core components:

* Load cell sensor
* HX711 amplifier
* MCP4725 DAC output
* OLED display
* Adjustable sensitivity
* Adjustable response curve
* Pressure-based brake response

The goal is to improve brake feel, consistency, and realism in racing simulator setups.

---

### 📸 [Camera_CTR](https://github.com/Renbrant/Camera_CTR)

<p align="center">
  <a href="https://github.com/Renbrant/Camera_CTR">
    <img src="https://raw.githubusercontent.com/Renbrant/Camera_CTR/main/Docs/Promo/Banner%202.png" width="100%" alt="Camera CTR Banner">
  </a>
</p>

An Arduino-based camera trigger system for photography experiments.

Features include:

* High-speed lightning photography trigger
* Auto-threshold light sensor mode
* Sound trigger
* Time-lapse
* Long exposure control
* Interval timer
* EEPROM-based settings storage

Originally developed as an experimental photography tool, this project reflects my interest in combining electronics with creative media.

---

### 🎧 [Voxyl](https://github.com/Renbrant/voxyl)

<p align="center">
  <a href="https://github.com/Renbrant/voxyl">
    <img src="https://raw.githubusercontent.com/Renbrant/voxyl/refs/heads/main/promo/banner.png" width="100%" alt="Voxyl Banner">
  </a>
</p>

A modern social podcast aggregator that merges RSS podcast feeds with social curation.

Concept features:

* Podcast aggregation
* Shared playlists
* Social listening discovery
* Guest and community-driven audio curation
* Web app beta concept
* Community-oriented podcast discovery

Voxyl explores how podcast listening can become more social, discoverable, and community-centered.

---

### 👥 [Voxyl Community](https://github.com/Renbrant/voxyl-community)

A companion/community space related to the Voxyl podcast ecosystem.

---

## 🎯 Mission

My goal is to inspire Portuguese speakers — especially young Brazilians — to explore technology, electronics, engineering, and software development.

I believe engineering becomes less intimidating when people can see real projects being built step by step.

If one project, one video, or one repository helps someone say:

> “Maybe I can build this too.”

Then it was worth sharing.

---

# 🎬 Featured YouTube Tutorials

## 🔊 Audio Amplifier Build Series

<p align="center">
  <a href="https://youtu.be/l1M68YnMbZU">
    <img src="https://img.youtube.com/vi/l1M68YnMbZU/hqdefault.jpg" width="220">
  </a>
  <a href="https://youtu.be/7MVE_ADX2zo">
    <img src="https://img.youtube.com/vi/7MVE_ADX2zo/hqdefault.jpg" width="220">
  </a>
  <a href="https://youtu.be/xPFlc_-g1K4">
    <img src="https://img.youtube.com/vi/xPFlc_-g1K4/hqdefault.jpg" width="220">
  </a>
  <a href="https://youtu.be/RolH8he9F0Y">
    <img src="https://img.youtube.com/vi/RolH8he9F0Y/hqdefault.jpg" width="220">
  </a>
</p>

<p align="center">
  <b>Power Supply • Audio Amplifier • Potentiometer • Protection Circuit</b>
</p>

---

## 🎓 How Audio Amplifiers Work — CFAA Series

<p align="center">
  <a href="https://youtu.be/PB0AxsF32tQ">
    <img src="https://img.youtube.com/vi/PB0AxsF32tQ/hqdefault.jpg" width="220">
  </a>
  <a href="https://youtu.be/JykineyO8B4">
    <img src="https://img.youtube.com/vi/JykineyO8B4/hqdefault.jpg" width="220">
  </a>
  <a href="https://youtu.be/cbj_mQlaPwA">
    <img src="https://img.youtube.com/vi/cbj_mQlaPwA/hqdefault.jpg" width="220">
  </a>
  <a href="https://youtu.be/pkR1dIMp2M0">
    <img src="https://img.youtube.com/vi/pkR1dIMp2M0/hqdefault.jpg" width="220">
  </a>
</p>

<p align="center">
  <b>Beginner Electronics • Class A • Transistors • Class AB Amplifiers</b>
</p>

---

## 🔋 Battery & Power Projects

<p align="center">
  <a href="https://youtu.be/IuTdQumrNao">
    <img src="https://img.youtube.com/vi/IuTdQumrNao/hqdefault.jpg" width="220">
  </a>
  <a href="https://youtu.be/iv6pAZklRSs">
    <img src="https://img.youtube.com/vi/iv6pAZklRSs/hqdefault.jpg" width="220">
  </a>
  <a href="https://youtu.be/AEz9T3bA5AE">
    <img src="https://img.youtube.com/vi/AEz9T3bA5AE/hqdefault.jpg" width="220">
  </a>
</p>

<p align="center">
  <b>18650 Cells • Battery Basics • Pack Design • Portable Power</b>
</p>

---

## 🧰 Main Technologies I Use

<p align="center">
  <img src="https://img.shields.io/badge/ESP32-000000?style=for-the-badge&logo=espressif">
  <img src="https://img.shields.io/badge/ESPHome-000000?style=for-the-badge&logo=home-assistant">
  <img src="https://img.shields.io/badge/Home_Assistant-18BCF2?style=for-the-badge&logo=home-assistant&logoColor=white">
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white">
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/PCB_Design-FF6F00?style=for-the-badge">
</p>

---

## ⚡ Philosophy

**Build. Share. Inspire.**

I do not share projects because they are perfect.

I share them because real engineering is iterative — it starts with curiosity, continues through mistakes, and becomes valuable when others can learn from it.

Even if only a few people are impacted, it is worth it.

```
```
