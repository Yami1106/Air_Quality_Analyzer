<div align="center">

# Air Quality Analyzer — IoT Monitoring System

[![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)](https://isocpp.org)
[![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)](https://arduino.cc)

*Real-time air quality monitoring with ESP8266 + MQ135, visualised on a live ThingSpeak cloud dashboard.*

</div>

---

## Overview

A complete IoT sensing and telemetry system that measures air quality using the MQ135 gas sensor and transmits readings over Wi-Fi to a cloud dashboard for real-time monitoring and historical analysis.

---

## Hardware

| Component | Role |
|---|---|
| ESP8266 (NodeMCU) | Wi-Fi microcontroller + data transmission |
| MQ135 gas sensor | Detects CO₂, ammonia, benzene, smoke |
| ThingSpeak | Cloud data logging + live dashboard |

---

## System flow

```
MQ135 sensor → ADC reading → PPM conversion
             → ESP8266 Wi-Fi → ThingSpeak API
             → Live dashboard (graphs + alerts)
```

---

## Features

- Continuous air quality sensing with configurable sampling rate
- Wi-Fi telemetry to ThingSpeak cloud platform
- Real-time visualisation dashboard
- Historical data logging for trend analysis

---

## Tech stack

`C++` · `Arduino IDE` · `ESP8266` · `ThingSpeak API`

---

<div align="center">
<a href="https://github.com/Yami1106">Ashish Sukumar</a>
</div>
