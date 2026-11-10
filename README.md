# Powertrain & Engine Management Simulator

An interactive, real-time automotive powertrain and engine telemetry simulator running entirely in the browser.

## Overview

A client-side simulation dashboard that models internal combustion engine kinematics, air-path thermodynamics, GDI fuel injection, 48V mild-hybrid power flow, 7-speed dual-clutch transmission, and ECU supervisory control in real time.

## Key Highlights

- **Real-Time Dynamics**: Synchronized engine speed, brake torque, boost pressure, fuel mass, and thermal balance.
- **8 Interactive Modules**: Airflow progression, 720° piston kinematics, Wiebe combustion, hybrid power flow, sensor telemetry, and a virtual oscilloscope.
- **ECU Fault Injection**: Simulate sensor failures and observe supervisory torque limitation and limp-home strategies.
- **Zero-Build Architecture**: Completely standalone single-file deliverable (`index.html`) powered by Tailwind CSS and Chart.js via CDN.

## Getting Started

Open `index.html` directly in any web browser, or deploy instantly to GitHub Pages.

```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

