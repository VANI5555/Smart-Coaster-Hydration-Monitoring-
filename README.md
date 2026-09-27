# Smart Coaster for Hydration Monitoring

An ESP32-based smart coaster designed to monitor beverage consumption and support hydration tracking using load-cell sensing, HX711 data acquisition, OLED display, RTC-based timing, and Bluetooth Low Energy (BLE) communication.

## Project Overview

The Smart Coaster is an embedded IoT project that combines sensor interfacing, real-time data acquisition, embedded firmware, and wireless communication.

A load cell placed beneath the coaster detects changes in the weight of a bottle or container. The HX711 module amplifies and digitizes the load-cell signal, while the ESP32 processes the acquired data. The measured information can be displayed locally through an OLED display and communicated wirelessly using BLE.

## Key Features

* Real-time weight measurement using a load cell
* HX711-based sensor signal acquisition
* ESP32-based embedded processing
* OLED display for local data visualization
* RTC-based timing and monitoring
* BLE communication for wireless data transfer
* Sensor calibration and data processing
* Hardware and firmware integration

## System Components

| Component    | Purpose                                      |
| ------------ | -------------------------------------------- |
| ESP32        | Main microcontroller and processing unit     |
| Load Cell    | Detects changes in container weight          |
| HX711        | Amplifies and digitizes the load-cell signal |
| OLED Display | Displays measurement information             |
| RTC          | Provides time-based monitoring               |
| BLE          | Enables wireless communication               |

## Working Principle

The system operates through the following process:

1. A bottle or container is placed on the smart coaster.
2. The load cell senses the weight of the container.
3. The HX711 acquires and amplifies the load-cell signal.
4. The ESP32 processes the sensor data.
5. Weight changes are used to estimate beverage consumption.
6. The measured information is displayed on the OLED.
7. BLE communication enables wireless transfer of relevant data.
8. RTC-based timing supports time-dependent monitoring and reminders.

## System Architecture

```text
Bottle / Container
       ↓
   Load Cell
       ↓
     HX711
       ↓
     ESP32
    ↙     ↘
 OLED       BLE
 Display     ↓
          Wireless
       Data Transfer

       RTC
        ↓
 Time-based Monitoring
```

## Hardware

The project integrates the following hardware:

* ESP32 development board
* Load cell
* HX711 load-cell amplifier/ADC
* OLED display
* RTC module
* Supporting power and interconnection circuitry

## Embedded Software

The ESP32 firmware is responsible for:

* Sensor data acquisition
* Load-cell calibration
* Weight measurement
* Data processing
* OLED data display
* RTC-based timing
* BLE communication
* Embedded hardware-software integration

## Project Images

### Smart Coaster Prototype

![Smart Coaster](smart%20coaster%20final.jpeg)

### Load Cell and HX711

![Load Cell with HX711](load%20cell%20with%20HX711.jpeg)

### Load Cell Working

![Load Cell Working](load%20cell%20working.jpeg)

### Circuit

![Smart Coaster Circuit](smart%20coaster%20ckt.jpeg)

### Implementation

![Implementation](implementation.jpeg)

## Project Presentation

The detailed project presentation is available here:

[View Project Presentation](smart%20coaster%20project%20ppt.pptx)

## Technologies Used

* C / Embedded C
* ESP32
* HX711
* Load Cell
* OLED
* RTC
* BLE
* I²C
* Embedded Firmware
* Sensor Interfacing
* Data Acquisition

## Project Status

**Ongoing**

The project is being developed with a focus on reliable sensor measurement, embedded firmware, hardware-software integration, and real-time hydration monitoring.

## Author

**Vani Kakhandaki**
Electronics and Communication Engineering
KLE Technological University

---

*This repository contains project documentation and implementation-related material for academic and project demonstration purposes.*
