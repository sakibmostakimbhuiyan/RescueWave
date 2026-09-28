# 🌊 RescueWave: Sensor-Based Autonomous Flood Relief Boat

> A low-cost boat prototype that detects obstacles in real time with ultrasonic sensors and adjusts its own path, designed with flood rescue in mind.

![Status](https://img.shields.io/badge/status-prototype-orange)
![Year](https://img.shields.io/badge/built-2022-blue)
![License](https://img.shields.io/badge/license-MIT-green)

<!-- Add a photo of the boat here -->
<!-- ![RescueWave](docs/boat.jpg) -->

## 🎯 The Problem

Every monsoon, floods in Bangladesh cut off communities and make rescue slow and dangerous. Reaching submerged, obstacle-filled areas with conventional boats is difficult and puts rescuers at risk.

RescueWave explores a simple idea: a small, affordable boat that can find its own way through flooded terrain.

## ⚙️ How It Works (2022 Prototype)

1. **Sense:** Ultrasonic sensors continuously detect objects and obstacles around the boat.
2. **Process:** The controller reads the sensor data in real time.
3. **Navigate:** The boat automatically adjusts its movement and direction based on what it detects.

```
Ultrasonic Sensors ──► Controller ──► Motors ──► Navigation
```

## 🚤 Mission Workflow

**Phase 1: Scout**
1. The boat travels through the flooded area, detecting obstacles with ultrasonic sensors and navigating around them.
2. It looks for stranded people.
3. When someone is found, it captures a photo and records the location.
4. It returns with the photos and locations so the rescue team knows exactly where help is needed.

**Phase 2: Deliver**
1. The team loads relief supplies (food, water, medicine, etc.) onto the boat.
2. The boat autonomously travels to the stranded people and delivers the supplies.

> Note: Which parts of this workflow were fully working in the 2022 prototype will be documented here as they are recovered and verified.

## 🔧 Hardware

| Component | Purpose |
|---|---|
| Ultrasonic sensors | Real-time object / obstacle detection |
| Microcontroller | _TBD_ |
| Motors + driver | Propulsion and steering |
| Battery | Power |

Wiring and pin details will be added in [`hardware/`](hardware/).

## 📌 Project Status

Originally built around 2022 as a prototype. This repository documents the design and will be updated with code, photos, and test results as they are recovered and verified.

## 🗺️ Roadmap (Future Vision)

- [ ] Publish original control code in `src/`
- [ ] Add circuit diagram and photos
- [ ] Improve person identification and location accuracy
- [ ] GPS-based navigation to reach the person and deliver supplies

## 🌍 Why It Matters

Faster, safer access to flood-hit areas can save lives. RescueWave shows that a simple sensor-driven design can be a starting point for affordable rescue technology.

## 📄 License

MIT License. See [LICENSE](LICENSE).

## 👤 Author

**Sakib Mostakim Bhuiyan** · [GitHub](https://github.com/sakibmostakimbhuiyan)
