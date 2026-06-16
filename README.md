# CanSat 2026 Flight Computer

Custom flight computer developed for the PEU UNAM CanSat 2026 competition.

The board was designed as the main avionics system of the CanSat, responsible for sensor acquisition, telemetry transmission, and mission data processing during flight.

---

## Mission

The flight computer was designed to:

- Collect environmental and flight data
- Process sensor measurements in real time
- Transmit telemetry to the ground station
- Operate reliably throughout launch, descent, and landing

---

## Hardware

Main components:

- ESP32 Microcontroller
- LSM9DS1 IMU
- TMP117 Temperature Sensor
- DPS310 Pressure Sensor
- RFM69HCW LoRa Radio

---

## PCB Design

### Schematic

<p align="center">
  <img src="images/schematic.png" width="800">
</p>

### PCB Layout

<p align="center">
  <img src="images/pcb_layout.png" width="700">
</p>

### Assembled Board

<p align="center">
  <img src="images/flight_computer_pcb.jpg" width="700">
</p>

---

## Competition

The project was developed as part of the PEU UNAM CanSat 2026 competition in Mexico City.

The system successfully completed flight operations and telemetry transmission during the mission.

Telemetry performance:

- 135 packets transmitted
- 128 packets received
- 7 packets lost

---

## Team

John Brown University Golden Eagles

Contributors:

- Iker Garcia Morales
- Roberto Miguel Martínez

---

## Lessons Learned

This project provided practical experience in:

- PCB Design
- Sensor integration
- Embedded Systems
- RF Telemetry
- System level engineering
- Hardware debugging and validation

One of the most important lessons was designing for reliability and testability. Connector placement, debugging access, and subsystem integration became critical factors during development and testing.

---

## Portfolio

More details about the project:

https://ikeermora.github.io/portfolio/projects/cansat-flight-computer.html
