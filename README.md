# Toxic-Trace
A portable device which can detect a concentration of heavy metal in water using uv vis spectroscopy method

# IronSense Pro – Portable Iron Detection System

## Overview

IronSense Pro is a portable, IoT-enabled system for measuring iron concentration in water using optical colorimetry. It provides a low-cost and compact alternative to conventional laboratory instruments such as UV-Vis spectrophotometers.

---

## Key Features

* Real-time iron concentration measurement (ppm)
* Compact and portable design
* IoT-based data monitoring
* Calibration-based accurate estimation
* Low power consumption

---

## System Components

**Hardware**

* ESP32 microcontroller
* Spectral sensor (AS7343 / AS7262)
* LED light source
* OLED display
* Push-button interface

**Software**

* Embedded firmware (Arduino / C)
* Calibration algorithm (absorbance-based)
* Firebase Realtime Database
* Web dashboard (HTML, Chart.js)

---

## Working Principle

The system operates based on the Beer-Lambert Law:

A = log(I₀ / I)

* I₀: Reference intensity
* I: Sample intensity
* A: Absorbance

Absorbance is mapped to concentration using a linear calibration model.

---

## Workflow

1. Capture reference intensity (DI water)
2. Measure sample intensity
3. Compute absorbance
4. Estimate concentration using calibration
5. Display and upload results

---

## Project Structure

```
IronSense-Pro/
│── firmware/
│── hardware/
│── web_dashboard/
│── data/
│── README.md
```

---

## Applications

* Water quality monitoring
* Industrial wastewater analysis
* Environmental testing

---

## Limitations

* Requires proper calibration
* Sensitive to external light conditions

---

