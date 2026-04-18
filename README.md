# low-power-air-quality-node
# Low-Power Air Quality Monitoring Node

## Overview
This project implements a low-power environmental sensor node using ESP32. It monitors air quality, performs local decision-making, and sends alerts via Blynk.

## Features
- Air quality monitoring (MQ135)
- Temperature monitoring (DHT11)
- Threshold-based alert system
- Mobile notifications
- Power-aware design

## Hardware
- ESP32
- MQ135
- DHT11

## How to Run
1. Install Arduino IDE
2. Install ESP32 board package
3. Install Blynk & DHT libraries
4. Upload code

## Limitations
- MQ135 consumes high power
- WiFi not ideal for off-grid

## Future Improvements
- Replace with BME680
- Use LoRa communication

## Credits
- ESP32 Datasheet (Espressif)
- Blynk IoT Library
- Adafruit DHT Library
