# 🚩 Name the Flag

Interactive geography quiz game where players test their knowledge of country flags. Built as a lightweight, static web application designed to run seamlessly on **GitHub Pages**.

---

## ✨ Features

- **UN-Recognized Nations**
- **Dark Mode**
- **Smart Acronym & Alias Support**: Accepts common shorthand like `USA`, `UK`, `UAE`, `CAR`, `DRC`, `NZ`, `RSA`, and more.
- **Interactive Mechanics**:
  - Live 15-minute countdown timer.
  - Heart-based life system (3 attempts per flag).
  - Instant visual feedback and animated shake effects on wrong guesses.
  - Real-time country name autocomplete suggestions.
- **Zero Backend Required**: Fully static single-page application built using pure HTML, CSS, and vanilla JavaScript.

---

## 📁 Repository Structure

```text
Countries/
├── data/
│   ├── countries.json       # Country details and ISO codes
│   ├── .geo.json            # Map geometry data
│   └── flags/               # SVG flag files named by ISO CCA3 code
│       └── [country_code].svg
├── index.html               # Main application entry point
├── README.md                # Project documentation
