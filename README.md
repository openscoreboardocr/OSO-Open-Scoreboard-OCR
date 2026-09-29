<p align="center">
  <img src="assets/oso-logo.png" alt="OSO Open Scoreboard OCR logo" width="180">
</p>

<h1 align="center">OSO – Open Scoreboard OCR for vMix, OBS & Live Sports Broadcasting</h1>

<p align="center">
  Free Windows scoreboard OCR software for extracting scoreboard clocks, scores and numeric data from cameras, capture devices, images and video.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Windows-x64-0078D4?logo=windows&logoColor=white">
  <img src="https://img.shields.io/badge/Status-Beta-orange">
  <img src="https://img.shields.io/badge/vMix-Friendly-1688F0">
  <img src="https://img.shields.io/badge/OBS-Friendly-302E31?logo=obsstudio&logoColor=white">
  <img src="https://img.shields.io/badge/OCR-Scoreboard-blue">
</p>

<p align="center">
  <a href="https://github.com/openscoreboardocr/OSO-Open-Scoreboard-OCR/releases/latest">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-1688F0?style=for-the-badge&logo=github">
  </a>
  &nbsp;
  <a href="https://buymeacoffee.com/andremgomes">
    <img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-Support%20Development-FFDD00?style=for-the-badge">
  </a>
</p>

<p align="center">
  <img src="assets/oso-screenshot.png" alt="OSO Open Scoreboard OCR Windows software for vMix and live sports broadcasting" width="100%">
</p>

---

## What is OSO?

**OSO – Open Scoreboard OCR** is a free Windows scoreboard OCR tool designed for live sports broadcasting, streaming and video production.

It reads information directly from a physical scoreboard using OCR and converts the recognized values into data that can be used by broadcast graphics systems.

OSO can recognize:

- Scoreboard clocks
- Scores
- Fouls
- Other numeric scoreboard values
- Tenths of a second

The recognized data can be exported as **XML** or **JSON**, making it suitable for workflows using:

- vMix
- OBS Studio
- Broadcast graphics
- Data-driven titles
- Custom live production systems

OSO is currently an **early beta** and is still actively being developed.

---

## Scoreboard OCR for vMix

OSO can be used as a scoreboard OCR solution for **vMix live productions**.

The application reads the physical scoreboard from a camera, video source or capture device and exports the recognized values to XML or JSON.

These values can then be connected to **vMix Data Sources** and used directly inside GT Titles or custom scoreboard graphics.

Typical workflow:

```text
Physical Scoreboard
        ↓
Camera / Capture Device
        ↓
OSO – Open Scoreboard OCR
        ↓
XML / JSON
        ↓
vMix Data Sources
        ↓
GT Title / Broadcast Graphics
