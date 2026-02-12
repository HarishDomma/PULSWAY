# 🚑 PulseWay | Emergency Traffic AI (LifeLineX)

**Version:** v2.2.0-MISSION-READY  
**Developed by:** PulseWay AI Team  

---

## 🌍 Overview

**PulseWay** is a real-time emergency response simulation and intelligent traffic management dashboard.

It demonstrates an AI-driven **"Green Wave" system** that prioritizes emergency vehicles (ambulances, fire trucks) by dynamically overriding traffic signals using V2X (Vehicle-to-Everything) communication.

In life-threatening medical emergencies, seconds matter. PulseWay visualizes how centralized AI coordination can eliminate traffic bottlenecks and ensure a frictionless path to hospitals.

---

## 🚀 Key Features

### 🗺 Real-Time Map Integration
- Powered by Leaflet.js
- High-fidelity tracking of emergency units
- Lightweight CartoDB Light tile layers

### 🚨 Dynamic Dispatch System
- Mission lifecycle management
- From priority alert → accident zone → hospital delivery
- Dual-phase operational flow

### 🧠 AI Green-Wave Logic
- Automatic traffic signal override within a **1km radius**
- Smart signal preemption and restoration
- Optimized to minimize urban congestion

### 📡 V2X Telemetry Terminal
- Live communication logs between:
  - 🚑 Emergency Vehicle  
  - ☁ Cloud AI  
  - 🚦 Smart Traffic Infrastructure  

---

## 🔁 Dual-Phase Mission Flow

### 🟢 Phase 1 – Dispatch
- Standard navigation to the accident zone
- Regular traffic signal interaction

### 🔴 Phase 2 – Emergency Return
- High-priority transport to hospital
- AI-controlled "Green Wave" activated
- Signal preemption enabled

---

## 🛠 Tech Stack

| Layer       | Technology Used |
|------------|-----------------|
| Frontend   | HTML5 |
| Styling    | Tailwind CSS |
| Mapping    | Leaflet.js + CartoDB Light |
| Logic      | Vanilla JavaScript (ES6+) |

---

## 🧠 System Logic – The "Green Wave"

The AI follows a rule-based traffic preemption protocol:

### 1️⃣ Proximity Trigger
When the ambulance enters **1000m (1km)** radius of a smart signal,  
the system sends an override command.

### 2️⃣ Signal Preemption
Traffic signal changes:

