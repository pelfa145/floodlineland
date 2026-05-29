# FLOODLINE — Real-Time IoT Flood Detection System

Official landing page and project showcase for **FLOODLINE**: a real-time IoT-based flood detection and contingency alert interface via Progressive Web Application.

## Project Title

**FLOODLINE: Real-Time IoT Based Flood Detection and Contingency Alert Interface via Progressive Web Application**

Capstone Research Project 2025–2026 | Dumingag Senior High School

---

## 🏆 Awards & Recognition

This project was highly recognized during the Capstone Research presentations, receiving the following accolades:
*   **Best in Capstone Innovation** — For outstanding implementation of low-cost, high-impact IoT technology.
*   **Best in Demonstration** — For flawless real-time hardware-to-software synchronization and sub-second latency testing.
*   **Best in Oral Presentation** — For exceptional defense, clarity, and articulation of the research study.

---

## The Problem

Communities near Dumingag, Zamboanga del Sur face critical gaps in flood monitoring:

- **Insufficient lead time** — Traditional monitoring leaves residents with only minutes to react
- **Communication failure** — Reliance on word-of-mouth and manual markers leads to inconsistent warnings
- **Nighttime surges** — Unpredictable water level spikes during heavy rainfall pose severe risks with minimal visible warning

## The Solution

FLOODLINE combines IoT hardware with a cloud-connected PWA to deliver:

- **Sub-second latency** flood monitoring
- **100% accuracy** in controlled testing
- **3-tier alert system** with local and digital notifications
- **Fail-safe physical alerts** that work without internet
- **Community-first pricing** — 90% more cost-effective than commercial alternatives

## System Architecture

### Hardware
| Component | Specification | Purpose |
|-----------|--------------|---------|
| Sensors | 3x XKC-Y26-V non-contact capacitive | Detect water through casing, debris-resistant |
| Microcontroller | Arduino Uno | Local hardware interrupts, physical alerts |
| Connectivity | ESP32 WiFi module | Wireless cloud synchronization |
| Power | Dual 18650 lithium cells (7.4V) | Continuous operation during power outages |
| Alert Output | LED tower + 90dB piezo buzzer | Visual and audible community warnings |

### Software
- **Firebase Realtime Database** — Cloud data sync
- **Progressive Web Application** — Mobile-first monitoring dashboard
- **OpenWeatherMap API** — Integrated weather data

### Alert Levels
| Level | LED Color | Trigger | Action |
|-------|-----------|---------|--------|
| 1 | Blue | Water rising | Prepare for possible evacuation |
| 2 | Blue (flashing) | Critical level | Evacuate while you still can |
| 3 | Red (flashing) | Extreme danger | Seek higher ground immediately |

## Cost Breakdown

| Component | Cost (₱) |
|-----------|----------|
| Non-Contact Liquid Sensors (3pcs) | ₱1,650 |
| ESP-32 Starter Kit | ₱843 |
| Arduino Uno Microcontroller | ₱455 |
| Lithium Battery | ₱388 |
| Jumper Wires and Wirings | ₱200 |
| Physical Tower Materials | ₱120 |
| Buck Converter | ₱62 |
| Piezo Buzzer | ₱59 |
| **Total** | **₱3,777** |

## Team & Responsibilities

### Technical Development
*   **Jadon Cyrus T. Paran** — System Integration, Hardware Assembly, Firmware Programming, Cloud Database Architecture, PWA & UI/UX Development

### Research & Documentation
*   **Pia Theresa A. Dela Raiz** — Lead Research Writer & Manuscript Editor
*   **Stefanie B. Malalay** — Co-Writer & Technical Documentation Coordinator
*   **Steven O. Poculan** — Research Methodologist & Literature Reviewer
*   **Marian Isabel A. Paller** — Data Presentation & Formatting Specialist
*   **Princess Eve L. Borling** — Statistical Data Analyst & Data Transcription
*   **Alyanna Heart L. Batestil** — Research Correspondence & Presentation Coordinator
*   **Jess A. Panganoron** — Field Survey Manager & Testing Logistics

## Live Demo

- **Landing Page**: [View this site live](https://pelfa145.github.io/floodlineland/)
- **Live Dashboard**: [Flood Safety PWA](https://pelfa145.github.io/floodlineapp/)

## Deployment

This is a **single-page static site** with all CSS inlined:

1. Clone or download this repository
2. Open `index.html` in any browser, or deploy to any static host
3. For GitHub Pages: Settings > Pages > select `main` branch

---

**FLOODLINE** — Protecting Dumingag through IoT innovation and proactive alerting.
© 2025–2026 Capstone Project | Dumingag Senior High School
