<div align="center">

# 🔬 ParaSense Labs

### *Building Tomorrow's Paranormal Detection Tools*

[![Website](https://img.shields.io/badge/Website-parasenselabs.se-blue?style=flat-square)](https://parasenselabs.se)
[![Location](https://img.shields.io/badge/Location-Stockholm%2C%20Sweden-green?style=flat-square)](#)
[![Status](https://img.shields.io/badge/Status-Active%20Development-orange?style=flat-square)](#)

**Open-source paranormal research devices built with Arduino, ESP32, and 3D-printing**

[About](#about) • [Our Devices](#our-devices) • [Technology](#technology) • [Get Involved](#get-involved) • [Contact](#contact)

</div>

---

## 🎯 About

ParaSense Labs designs and builds **open-source detection devices** for paranormal investigation. Every device is documented, tested, and shared freely so anyone can build their own equipment.

We believe in:
- 🔓 **Open Hardware** - All designs, code, and schematics freely available
- 🔬 **Scientific Approach** - Measuring, not guessing
- 🛠️ **DIY Accessible** - Built with common components and 3D-printing
- 📊 **Transparent Results** - Sharing what works (and what doesn't)

> *"If you can't measure it, you can't investigate it."*

---

## 🔧 Our Devices

### ✅ In Testing (Built & Working)

#### 🎵 Music Box
**Proximity-activated audio player**

A paranormal "trigger device" that plays music when something approaches. Uses ultrasonic sensors to detect movement in front of the device.

- **Sensors:** HC-SR04 ultrasonic distance sensor
- **Controller:** Arduino/ESP32
- **Purpose:** Trigger device - attracts and detects interaction
- **Status:** ✅ Built and field-tested
- **Repo:** *Coming soon*

---

#### ⚡ Proximity Sensor
**Static electricity detection unit**

Detects changes in static electricity using a Darlington transistor circuit. Highly sensitive to nearby presence without physical contact.

- **Circuit:** Darlington pair amplifier
- **Detection:** Static electric field changes
- **Purpose:** Non-contact proximity detection
- **Status:** ✅ Built and testing
- **Repo:** *Coming soon*

---

### 🔄 In Development

#### 🌑 Shadow Sensor
**Light variance detection system**

Detects sudden changes in ambient light levels that could indicate a shadow passing by. Filters out gradual changes (clouds, sunset) to focus on rapid anomalies.

- **Sensors:** Photoresistors/photodiodes
- **Detection:** Rapid light level changes
- **Purpose:** Shadow movement detection
- **Status:** 🟡 Planning stage
- **Repo:** *Coming soon*

---

#### 📡 Excluder
**Environmental baseline mapper**

Scans and logs all "normal" activity in an investigation area before you start. Maps WiFi networks, Bluetooth devices, magnetic fields, and EMF sources so you know what's naturally there.

- **Scans:** WiFi, Bluetooth, EMF, magnetic fields
- **Purpose:** Establish environmental baseline
- **Output:** Detailed map of normal activity
- **Status:** 🟡 Active development
- **Use case:** Run this FIRST to know what to ignore
- **Repo:** *Coming soon*

> 💡 **Why the Excluder matters:** If there's a WiFi router or Bluetooth speaker in the room, you need to know *before* your EMF detector starts going off!

---

### 🔮 Future Concepts

- **Multi-sensor node** - Combined unit with multiple detection methods
- **Data logger** - Long-term recording with SD card storage
- **Synchronized network** - Multiple units working together
- **Temperature variance detector** - Mapping cold spots scientifically

---

## 🛠️ Technology Stack

### Hardware Platform
