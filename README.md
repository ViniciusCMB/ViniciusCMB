<div align="center">

# Vinícius Monnerat
### Avionics & Firmware Engineer · Mission Systems · BI & Data

**Mechanical Engineering (IPRJ-UERJ)** — Avionics/Telemetry Sector Manager at [Serra Rocketry](https://www.instagram.com/serrarocketry/)

</div>

---

## About

I build embedded systems and mission-critical software for rockets and satellites. My work spans the full stack of a flight mission: from the firmware running on an ESP32 in a spinning PocketQube, through LoRa telemetry downlinks, to the ground station WebUI and the data analysis pipeline that turns raw CSV into certified motor classifications.

Day to day I work with **C/C++ on ESP32 (FreeRTOS, FSM, RTOS)**, **Python (RocketPy, Flask, NumPy, Pandas)**, **Laravel/PHP for web platforms**, and **BI tools (Spotfire, Power BI)** for turning engineering and mission data into dashboards that drive decisions. I'm a member of the **RocketPy-Team LibDev** — contributing to the open-source 6-DOF trajectory simulation library used worldwide.

I care about **determinism, testability, and fault tolerance**. Every design decision passes through three filters: **compliance** (rules/safety), **Murphy** (redundancy, no single points of failure), and **time** (can we actually build, integrate, and test this before launch?).

---

## Current Missions

### 🚀 Flight Computer V2 — Missions Dédalo (1 km) & Thonyan (500 m)
OOP firmware architecture on ESP32 with FreeRTOS and a 4-state finite state machine for flight phases. Validated against real flight data from LASC. Includes KiCad electronics, bench testing, and FMECA analysis.
> [`flight-computer`](https://github.com/ViniciusCMB/flight-computer) · [`flight-simulations`](https://github.com/ViniciusCMB/flight-simulations)

### 🛰️ Helike — PocketQube 1P (LASC 2026)
ESP32-C3 satellite with bioinspired autorotating recovery system (SRAB, inspired by maple seed aerodynamics) and LoRa triangulation with 3 ground beacons. Full stack: firmware, hardware (KiCad), mission report, and analysis notebooks.
> [`satellite`](https://github.com/ViniciusCMB/satellite) · [`recovery-webui`](https://github.com/ViniciusCMB/recovery-webui)

### 🔧 Static Fire Testing Pipeline
Thrust stand (ESP32 + HX711 load cell) → CSV → Flask analysis app → Simpson integration for total impulse, NAR/TRA motor classification, PDF reports. End-to-end from hardware to certified report.
> [`thrust-stand`](https://github.com/ViniciusCMB/thrust-stand) · [`analysis`](https://github.com/ViniciusCMB/analysis)

### 📈 RocketPy LibDev Team
Contributing to [RocketPy](https://github.com/RocketPy-Team/RocketPy) — the open-source 6-DOF rocket trajectory simulator. Member of the RocketPy-Team organization, working on core library development, flight simulations, and data analysis for competitions (EuRoC, LASC).

---

## Selected Projects

| Project | What it does | Stack |
|---------|-------------|-------|
| [**git-auto-commit**](https://github.com/ViniciusCMB/git-auto-commit) | AI-powered commit message generator running locally with Ollama. Enforces conventional commit format. | Python, LangChain, Ollama |
| [**agendamento-core-template**](https://github.com/ViniciusCMB/agendamento-core-template) | White-label scheduling platform for automotive aesthetics. Laravel + Filament + Livewire. | Laravel 12, PHP, Filament 5 |
| [**RE-maintenance-assistant**](https://github.com/ViniciusCMB/RE-maintenance-assistant) | Smart maintenance tracker for Royal Enfield motorcycles using OEM manual data. | Python, Jupyter |
| [**AI-study-buddy**](https://github.com/ViniciusCMB/AI-study-buddy) | AI-powered study assistant with context-aware Q&A. | Python, PySide6, SQLite |
| [**pet-feeder**](https://github.com/ViniciusCMB/pet-feeder) | Automatic pet feeder with Wi-Fi scheduling, ESP8266. | C++, ESP8266, Arduino |
| [**homelab**](https://github.com/ViniciusCMB/homelab) | Self-hosted Docker infrastructure with 16 services (Home Assistant, Nextcloud, AdGuard, etc). | Docker, Shell, GitOps |
| [**analysis**](https://github.com/ViniciusCMB/analysis) | Flask web app + CLI for rocket motor static fire analysis. Reports, classification, visualizations. | Python, Flask, ReportLab |

<details>
<summary><b>📚 Academic work (IPRJ-UERJ)</b></summary>

| Project | Description |
|---------|-------------|
| [metodos-num](https://github.com/ViniciusCMB/metodos-num) | Numerical methods for differential equations (2024.2 & 2025.2) |
| [calc-numerico](https://github.com/ViniciusCMB/calc-numerico) | Numerical calculus: root-finding, LU decomposition, linear systems |
| [fisexp3](https://github.com/ViniciusCMB/fisexp3) | Physics 3 lab — electromagnetism experiments with Jupyter |
| [dinamica](https://github.com/ViniciusCMB/dinamica) | Particle dynamics simulations (elastic pendulum, double pendulum) |
| [baja-modeling](https://github.com/ViniciusCMB/baja-modeling) | Baja SAE vehicle modeling notebooks |
| [TEMC](https://github.com/ViniciusCMB/TEMC) | Special topics in mathematics & computation |
| [flight-trajectory](https://github.com/ViniciusCMB/flight-trajectory) | Rocket flight trajectory modeling (propulsive, ballistic, coast) |

</details>

---

## Tech Stack

<div align="center">

**🔧 Embedded & Hardware**

`C` `C++` `ESP32` `ESP32-C3` `Arduino` `PlatformIO` `KiCad` `FreeRTOS` `LoRa (RFM95W)`

**🚀 Aerospace & Simulation**

`RocketPy` `6-DOF Simulation` `Flight Dynamics` `Telemetry` `Avionics` `FMECA`

**🐍 Python & Data**

`Python` `NumPy` `Pandas` `SciPy` `Matplotlib` `Jupyter` `Flask` `ReportLab`

**📊 BI & Analytics**

`Spotfire` `Power BI` `Data Visualization` `ETL`

**🌐 Web & Backend**

`Laravel` `Filament` `Livewire` `PHP` `Blade` `Flask` `Firebase`

**🤖 AI & LLM**

`LangChain` `Ollama` `OpenCV` `scikit-learn` `LLaVA`

**⚙️ DevOps & Tools**

`Linux` `Fedora` `Docker` `Git` `LaTeX` `NeoVim` `Klipper`

</div>

---

<div align="center">

### 📈 GitHub Activity

<img src="https://github-readme-stats.vercel.app/api?username=ViniciusCMB&show_icons=true&theme=transparent&include_all_commits=true&count_private=true&hide_border=true" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ViniciusCMB&layout=compact&theme=transparent&hide_border=true" height="165" />

</div>

---

<div align="center">

### 📫 Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vinicius-c-monnerat/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ViniciusCMB)

</div>
