# 🚗 SCOROO Telemetry Dashboard

Vehicle Telemetry + Navigation System for DayZ

A real-time multi-screen dashboard that pulls vehicle telemetry data from DayZ and displays it across 3 synchronized screens.

---

## 📁 Installation Location

Copy the dashboard folder to:

```text
%localappdata%\DayZ\DayZCarTelemetry\
```

Or manually:

```text
C:\Users\YourName\AppData\Local\DayZ\DayZCarTelemetry\
```

---

## 📂 File Structure

```text
DayZCarTelemetry/
├── car_telemetry.json          # Vehicle data (auto-generated)
├── map.html                    # Map screen
├── map1.html                   # Terrain map
├── nav1.html                   # Navigation screen
├── radio.html                  # FM radio screen
├── speed.html                  # Classic dashboard
├── speed1.html                 # Sport dashboard
├── speed2.html                 # Digital dashboard
├── index.html                  # Main dashboard
├── start_dashboard.bat         # Launcher
├── map_images/
│   ├── car.svg
│   ├── DayZ_1.25.0_*.jpg
│   └── (all SVG icons and map assets)
└── README.md
```

---

## 🚀 How to Start

### Method 1: Double Click

Run:

```text
start_dashboard.bat
```

### Method 2: Manual Start

Open Command Prompt inside the dashboard folder and run:

```bash
python -m http.server 3600
```

Then open:

```text
http://localhost:3600
```

in your browser.

---

## 🎮 How to Use

### 1. In DayZ

* Enter any vehicle.
* The telemetry mod automatically writes live data to:

```text
car_telemetry.json
```

### 2. Dashboard Features

#### 🗺️ Map Screen

* Click towns to set destinations
* Search locations
* Zoom in and out
* Live vehicle tracking

#### 🧭 Navigation Screen

* Turn-by-turn directions
* Distance to destination
* ETA calculation
* Compass heading

#### 🚗 Dashboard Screens

Switch between:

* Classic Dashboard
* Sport Dashboard
* Digital Dashboard

### 3. Controls

| Control              | Function                                    |
| -------------------- | ------------------------------------------- |
| Theme Buttons        | Change map, navigation and dashboard styles |
| Landscape / Portrait | Toggle screen orientation                   |
| Frameless Mode       | Hide headers for fullscreen displays        |

---

## 🛠️ Requirements

* Python 3.x
* Modern web browser (Chrome, Edge, Firefox)
* DayZ
* SCOROO Telemetry Mod

---

## 📡 Data Flow

```text
DayZ Vehicle
      │
      ▼
car_telemetry.json
      │
      ▼
SCOROO Dashboard
      │
      ├── Map Screen
      ├── Navigation Screen
      └── Dashboard Screen
```

Live updates every 100ms.

Telemetry includes:

* Vehicle Position
* Heading
* Speed
* RPM
* Gear
* Fuel Level
* Coolant Temperature
* Vehicle Warnings

---

## 🚁 Helicopter Version (Coming Soon)

Planned 6-screen aviation dashboard featuring:

* Altitude
* Vertical Speed
* Rotor RPM
* Engine Temperature
* Fuel Monitoring
* Artificial Horizon
* GPS Navigation
* Flight Warnings

---

## 🔗 Links

### GitHub Repository

https://github.com/scoroo/SCOROO-Telemetry-Dashboard

### DayZ Workshop

https://steamcommunity.com/profiles/76561198972868854/myworkshopfiles/?appid=221100

---

## ⚡ Quick Start

1. Copy the folder to:

```text
%localappdata%\DayZ\DayZCarTelemetry\
```

2. Run:

```text
start_dashboard.bat
```

3. Open:

```text
http://localhost:3600
```

4. Enter a vehicle in DayZ.

5. Watch live telemetry update across all dashboard screens.

---

## ⚠️ Important Notes

* Python 3 must be installed.
* Start the local server before opening the dashboard.
* Keep all files together in the same folder.
* Compatible with all DayZ vehicles supported by the telemetry mod.

---

## 📜 Author

**SCOROO**

Enjoy your SCOROO Telemetry Dashboard! 🏎️💨

