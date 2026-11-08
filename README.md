# Mechanical Clock // HackClub Fallen Project

[![Hack Club Fallen](https://img.shields.io/badge/Hack%20Club-Fallen-FF4747?style=for-the-badge)](https://fallen.hackclub.com/)

A mechanical clock which displays analogue time only using gears and one motor.

It's interesting because it has 3 hands moving at different speeds powered up by one motor, so the gears have to change the speed of the motor and then connected to shafts to make the 3 hands move at different speeds.


## The Backstory
I am making a project in school in a club, and I've decided to log it with Hack Club Fallen and make it open source. 

I have currently not even completed the planning phase, so I plan to complete this whole project in the coming days.

I chose this project because I've never worked with gears before, and I thought that this would be the most ideal way to deepen my learning while building something effective and a nice open-source project.

## Compilation & Assembly

### We will be using:
- **ESP-IDF** - to compile and flash the firmware to the ESP32-S3
- **Techsoft Design 2d** - to design and export clock designs
- **VS Code** - as the IDE for our overall project

### 1. Flash the firmware to the custom PCB

**Set the target device as an ESP32-S3**
```powershell
idf.py set-target esp32s3
```

**Open the built in terminal menu to configure variables**
```powershell
idf.py menuconfig
```

**Firmware Compilation**
```powershell
idf.py build
```

**Firmware Flashing & Serial Monitoring**
```powershell
# Replace COM3 with your own port
idf.py -p COM3 flash monitor
```

### 2. Assembly
For assembly steps, follow my instructions inside [```assembly.md```](assembly.md)

## File Structure
[To be finalised]

```text
Mechanical Clock
├── .github/
├── 2d-models/
|   ├── gears/
|   |    ├──
|   |    └──
|   ├──
|   └──
├── assets/
|   ├── assembly/
|   ├── plan/
|   └── README/
├── PCB and Schematics/
|   ├──
|   ├──
|   └──
├── firmware/
|   ├── components
|   |    ├── display_driver/
|   |    └── lvgl/
|   ├── main/
|   |    ├── include/
|   |    ├── CMakeLists.txt
|   |    ├── main.c
|   |    └── ui_app.c
|   ├── include/
|   ├── CMakeLists.txt
|   ├── idf_component.yml
|   └── sdkconfig
├── .env.example
├── .gitignore
├── assembly.md
├── BOM.csv
├── LICENSE
├── plan.md
└── README.md
```

---
## The Project Plan
[`plan.md`](plan.md)

## Images of final Product
[to be added]



---

Built by Abdullah Ahmer for **Hack Club Fallen**