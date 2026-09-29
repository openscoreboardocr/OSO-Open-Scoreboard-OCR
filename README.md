<p align="center">
  <img src="assets/oso-logo.png" alt="OSO Open Scoreboard OCR" width="180">
</p>

<h1 align="center">OSO – Open Scoreboard OCR</h1>

<p align="center">
  A lightweight Windows OCR tool for extracting scoreboard clocks, scores and other numeric data for live broadcast workflows.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Windows-x64-0078D4?logo=windows&logoColor=white">
  <img src="https://img.shields.io/badge/Status-Beta-orange">
  <img src="https://img.shields.io/badge/vMix-Friendly-1688F0">
  <img src="https://img.shields.io/badge/OBS-Friendly-302E31?logo=obsstudio&logoColor=white">
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
  <img src="assets/oso-screenshot.png" alt="OSO Open Scoreboard OCR Screenshot" width="100%">
</p>

---

## About

**OSO – Open Scoreboard OCR** is an independent Windows application designed to read information from physical scoreboards using OCR and make that data available for live broadcast workflows.

The project started as a personal tool for smaller productions where dedicated scoreboard data systems are not always available or affordable.

OSO is currently in **early beta** and is still being actively developed.

The main goal is to provide a simple and accessible way to extract scoreboard information and send it to graphics or broadcast systems without requiring expensive dedicated hardware.

---

## Features

- OCR reading of scoreboard clocks
- Support for `MM:SS` clock formats
- Support for tenths of a second
- Temporal anti-jump filtering
- Perspective correction
- Adjustable ROI selection
- Multiple OCR image-processing controls
- Extra ROIs for additional numeric fields
- Score reading
- Fouls reading
- Custom numeric fields
- XML output
- JSON output
- vMix-friendly Data Source workflow
- OBS-friendly external data workflow
- Camera / capture device input
- Image input
- Video input for testing
- Custom-trained OCR model for scoreboard digits
- Windows x64 installer

---

## Broadcast Workflow

```text
Physical Scoreboard
        ↓
Camera / Capture Device
        ↓
OSO – Open Scoreboard OCR
        ↓
XML / JSON
        ↓
vMix / Graphics / Broadcast Workflow
