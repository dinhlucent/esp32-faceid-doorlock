# ESP32-FaceID-DoorLock

A professional-grade smart door lock system featuring real-time face recognition using the ESP32-CAM module and an embedded web server.

## Features
- **Real-time Face Recognition**: Uses ESP-WHO framework for authorized identification.
- **Remote Monitoring**: Built-in web server to view live feeds and manage access.
- **Hardware Integration**: Controls 12V electronic locks via relay modules.
- **Visual Feedback**: LED indicators for system access status.

## Tech Stack
- **Language**: C++, Arduino
- **Framework**: ESP-WHO, ESP-IDF
- **Hardware**: ESP32-CAM, 12V Relay, Solenoid Lock

## Project Structure
```
├── README.md
├── LICENSE
├── firmware/           # Arduino/C++ source code
├── hardware/           # Schematics and PCB designs
├── docs/               # Technical presentations
└── media/              # Project photos and demonstration videos
```

## Getting Started

### Prerequisites
- Arduino IDE with ESP32 board support
- ESP-WHO development framework

### Installation
1. Open `firmware/CameraWebServer.ino` in Arduino IDE.
2. Select **AI Thinker ESP32-CAM** board.
3. Configure Wi-Fi credentials in the source.
4. Flash to the module.

### Wiring
Refer to diagrams in the [media/](media/) folder for relay and buck converter connections.

## Demo
Visual demonstrations and hardware setup photos are available in the [media/](media/) directory.

## License
MIT License — see [LICENSE](LICENSE)

---
Built by [DinhLucent](https://github.com/DinhLucent)