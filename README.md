<div align="center">

# Nour Aouini

### Electrical engineering student · Embedded systems & electronics

🎓 **ENSIT, Tunis** — engineering cycle  and Master 2 SIAA  
💼 Embedded DevOps intern at **Unistellar**, Marseille (May – Aug 2026)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-aouini--nour-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/aouini-nour)
[![Email](https://img.shields.io/badge/Email-aouininour2003@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:aouininour2003@gmail.com)
![Location](https://img.shields.io/badge/📍-Tunis,_Tunisia-lightgrey?style=flat-square)

</div>

---

I'm an electrical engineering student at ENSIT in Tunis, and I'm also doing a Master 2 in signal, image and advanced control (SIAA) there this year. I spent my 4th-year semester at ENSEA, near Paris, in the IoT track.

Most of what I build runs on STM32: drivers, FreeRTOS or bare-metal firmware, CAN and BLE links, and lately the PCB that goes with it.

This summer at Unistellar I set up a GitLab CI pipeline that cross-compiles the firmware in Docker and runs the tests on the real board. I also wrote a single IMU driver and a low-power mode for a dual-core STM32H747 under FreeRTOS.

The summer before, at Sagemcom in Ben Arous, I wrote a small Python (Tkinter) tool to test the UART, RS-232 and RS-485 ports of smart meters and check their Modbus CRC-16 frames. I also followed the production line and its test benches: metrology, SMT and wave soldering.

That same summer, the Ministry of Youth and Sports selected me to teach at the National Academy of Robotics and AI in Tunis. I ran hands-on workshops where young people programmed Arduino boards with sensors and DC motors.

---

## Projects

| Project | What it does | Stack |
|---|---|---|
| [bldc4-foc-controller](https://github.com/Nour3000/bldc4-foc-controller) | Field-oriented control board for four brushless motors, commanded over CAN FD. Control firmware tested in C and in Simulink against a motor model; 6-layer PCB in Altium. In progress. | STM32G474, C, Simulink, Altium |
| [capteur-intelligent-3-voies](https://github.com/Nour3000/capteur-intelligent-3-voies) | Three ultrasonic sensors at 0°, 120° and 240°, temperature-compensated distance, filtering and fault detection. Simulated in Proteus, PCB and Gerbers ready. | STM32F103, Proteus, MATLAB |
| [drone-gesture-control](https://github.com/Nour3000/drone-gesture-control) | Flies a drone with hand gestures. The STM32N6 NPU recognises 7 gestures on-device and sends commands over BLE. Team project at ENSEA. | STM32N6, NPU, FreeRTOS, BLE |
| [embassy-ensea-drivers](https://github.com/Nour3000/embassy-ensea-drivers) | Async Rust drivers for the ENSEA teaching board: bargraph, gamepad, encoder, TMC2226 stepper. | Rust, Embassy, STM32L476 |
| [robot-iot](https://github.com/Nour3000/robot-iot) | Bare-metal robot controlled over Bluetooth, with MQTT and Node-RED supervision. | STM32F407, C, MQTT |
| [can-led-synchronization](https://github.com/Nour3000/can-led-synchronization) | Two boards keep their LEDs in sync over a CAN 2.0 bus, no master. | STM32F407, CAN, MCP2551 |
| [esp32-smart-lighting](https://github.com/Nour3000/esp32-smart-lighting) | Street-light node that dims with light and motion, with Firebase telemetry. | ESP32, Firebase, Node-RED |

Currently working on a [4-channel motor controller](https://github.com/Nour3000/bldc4-foc-controller) (FOC, CAN) with an STM32G474, designed in Altium and modelled in Simulink.

---

## Tools I use

### Microcontrollers & RTOS

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-8BC34A?style=flat-square)
![Embassy](https://img.shields.io/badge/Embassy-000000?style=flat-square&logo=rust&logoColor=white)

### Languages

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![VHDL](https://img.shields.io/badge/VHDL-grey?style=flat-square)

### Buses & protocols

![CAN](https://img.shields.io/badge/CAN_2.0-FF6B35?style=flat-square)
![Modbus](https://img.shields.io/badge/Modbus-grey?style=flat-square)
![RS-485](https://img.shields.io/badge/RS--232%2F485-grey?style=flat-square)
![UART](https://img.shields.io/badge/UART-grey?style=flat-square)
![SPI](https://img.shields.io/badge/SPI-grey?style=flat-square)
![I2C](https://img.shields.io/badge/I2C-grey?style=flat-square)
![BLE](https://img.shields.io/badge/BLE-0082FC?style=flat-square&logo=bluetooth&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)

### Design & test

![Altium Designer](https://img.shields.io/badge/Altium_Designer-A5915F?style=flat-square&logo=altiumdesigner&logoColor=white)
![Proteus](https://img.shields.io/badge/Proteus-1F4E79?style=flat-square)
![MATLAB](https://img.shields.io/badge/MATLAB%2FSimulink-0076A8?style=flat-square&logo=mathworks&logoColor=white)
![LabVIEW](https://img.shields.io/badge/LabVIEW-FFDB00?style=flat-square&logo=labview&logoColor=black)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## Languages

🇹🇳 Arabic (native) • 🇬🇧 English (C1, TOEIC) • 🇫🇷 French (B2) • 🇩🇪 German (A2)

---

<div align="center">

Looking for an embedded systems / firmware end-of-studies internship (PFE) in 2027.

📫 **aouininour2003@gmail.com**

</div>
