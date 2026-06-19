# SCOROO Telemetry Dashboard
## 🚗 Vehicle Telemetry + Navigation System for DayZ

A real-time multi-screen dashboard that pulls vehicle telemetry data from DayZ and displays it across 3 synchronized screens.

---

## 📁 Where to Install
%localappdata%\DayZ\DayZCarTelemetry\

text

Or manually:
C:\Users\YourName\AppData\Local\DayZ\DayZCarTelemetry\

text

---

## 📂 File Structure
DayZCarTelemetry/
========car_telemetry.json
========map.html
========map1.html
========nav1.html
========radio.html
========speed.html
========speed1.html
========speed2.html
========index.html
========start_dashboard.bat
========map_images/
================car.svg
================ DayZ_1.25.0_*.jpg
================(all SVG icons)
========README.md

text

---

## 🚀 How to Start

### Method 1: Double-click
Double-click start_dashboard.bat

text

### Method 2: Manual
Open Command Prompt in the DayZCarTelemetry folder
Type: python -m http.server 3600
Open browser: http://localhost:3600

text

---

## 🎮 How to Use

### 1. In DayZ
- Get in any vehicle
- The mod automatically writes telemetry data to `car_telemetry.json`

### 2. In Dashboard
- **Map** – Click towns to set destination, search locations, zoom in/out
- **Navigation** – Shows turn-by-turn arrows, ETA, distance, compass
- **Speed** – Switch between Classic/Sport/Digital styles

### 3. Controls
- **Theme Buttons** – Switch map style, nav mode, dash style
- **Landscape/Portrait** – Toggle layout
- **Frameless** – Hide headers for full-screen view

---

## 🛠️ Requirements

- Python 3.x installed (for HTTP server)
- Modern browser (Chrome/Edge/Firefox)
- DayZ with SCOROO Telemetry Mod

---

## 📡 Data Flow
DayZ Vehicle → car_telemetry.json → Dashboard (3 screens)
↓ ↓ ↓
Position Speed/RPM Live Updates
Heading Fuel/Temp Every 100ms
Gear Warnings Cross-Screen Sync

text

---

## 🚁 Helicopter Version (Coming Soon)

A 6-dash helicopter telemetry variant with:
- Altitude, vertical speed, rotor RPM
- Engine temp, fuel, artificial horizon
- GPS map, navigation, and warning system

---

## 🔗 Links

- **GitHub:** https://github.com/scoroo/SCOROO-Telemetry-Dashboard
- **Author:** SCOROO

---

## 📝 Quick Start Summary

1. Copy folder to `%localappdata%\DayZ\DayZCarTelemetry\`
2. Double-click `start_dashboard.bat`
3. Open `http://localhost:3600` in browser
4. Get in a vehicle in DayZ
5. Watch live telemetry on all 3 screens!

---

## ⚠️ Important

- Python 3 must be installed
- Run the .bat file before opening the browser
- All files must stay in the same folder
- The mod works with any vehicle in DayZ

---

**Enjoy your SCOROO Telemetry Dashboard!** 🏎️💨
