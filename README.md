# Gito Portfolio - COSC 111B (Internet of Things)

## Overview
This repository contains a collection of IoT projects developed for COSC 111B. It tracks the progression from basic Arduino I/O to advanced Python-integrated web APIs.

## Project Structure

### Midterms: Embedded Foundations
- **Lab 1 & 2**: Basic digital and analog LED sequences using arrays.
- **Lab 3**: Fire detection system using Thermistors and LDRs.
- **Lab 4**: Reactive serial control based on light levels.
- **Midterms Lab**: A Smart Lighting system with Automatic/Manual state switching.

### Finals: Connected Systems
- **Lab 5**: Python-based terminal menu for multi-color LED control.
- **Lab 6**: Full-duplex serial communication (Button-to-Python-to-LED).
- **Lab 7**: IoT Web API using FastAPI for remote LED management.
- **Finals Lab**: Physical-to-Digital trigger system using Python `requests`.

## Technology Stack
- **Hardware**: Arduino Uno, LDR, Thermistor, RGB LEDs.
- **Languages**: C++ (Arduino), Python.
- **Frameworks**: FastAPI, Uvicorn.
- **Libraries**: PySerial, Requests.

## Setup Instructions
1. Upload the `.ino` file to the Arduino.
2. Ensure the correct COM port is set in the `.py` files.
3. For FastAPI projects, run `uvicorn LabAct7:app --reload`.
