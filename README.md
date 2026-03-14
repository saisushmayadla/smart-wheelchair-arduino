# ♿ Bluetooth Smart Wheelchair

A smart assistive mobility system that allows a wheelchair to be controlled wirelessly using Bluetooth communication and an Arduino-based control system.

---

## 🚀 Features

- Wireless control of wheelchair using Bluetooth
- Smartphone-based navigation (forward, backward, left, right)
- Arduino UNO microcontroller for processing commands
- Motor driver for efficient DC motor control
- Improves independent mobility for users with disabilities

---

## 🧠 Technologies Used

- Arduino UNO
- HC-05 Bluetooth Module
- L298N Motor Driver
- DC Geared Motors
- Embedded C / Arduino IDE
- 12V Battery Power System

---

## 📁 Project Structure
```
smart-wheelchair/
├── code/
│ └── smart_wheelchair.ino
├── CAD
│ └── Wheel chair Cad Video
├── Circuit/
│ └── circuit_diagram.jpeg
├── Images/
│ └── wheelchair_prototype.jpeg
│ └── wheelchair_sketch.jpeg
├── Components/
| └── Bill_of_materials.png
| └── Components_list.png
| └── Components_functionality.jpeg
│ └── Components_image.jpeg
├── Working_videos/
| └── First working success video of wheelchair.MP4
│ └── Main video.MPA4
└── README.md

```
---
## 🧩 CAD Model

The smart wheelchair structure was designed using CAD software to model the mechanical framework and component placement.

🔗 View the CAD Model:
https://a360.co/3EUiIGC

## ⚙️ System Components

The following hardware components are used in this project:

- Arduino UNO
- HC-05 Bluetooth Module
- L298N Motor Driver
- DC Geared Motors
- 12V Battery
- Wheelchair Frame
- Jumper Wires

---

## 🔧 Working Principle

The HC-05 Bluetooth module receives commands from a smartphone application through Bluetooth communication.

The Arduino UNO processes the received commands and sends control signals to the L298N motor driver.

The motor driver controls the DC motors attached to the wheelchair wheels, allowing the wheelchair to move in different directions such as forward, backward, left, and right.

---

## 📲 Control Commands

The wheelchair can be controlled using a mobile Bluetooth controller app.

Example commands:

| Command | Movement |
|---------|---------|
| ⬆️ | Forward |
| ⬇️ | Backward |
| ⬅️ | Left |
| ➡️ | Right |

---

## 🖥️ Software Setup

1. Open Arduino IDE
2. Connect Arduino UNO to your computer
3. Upload the `smart_wheelchair.ino` code
4. Pair your smartphone with the HC-05 Bluetooth module
5. Use a Bluetooth controller app to send movement commands

---
## CHALLENGES FACED ⚠️

- Gyro sensor malfunctioned during final stages.
- Had to quickly adapt the system to smartphone-based control.
- Faced Bluetooth pairing delays during testing
- Power regulation issues for motor load.


## 🚀 Future Scope

- Add voice control for accessibility.
- Implement obstacle detection using ultrasonic sensors.
- Integrate GPS tracking.
- Develop a dedicated mobile application.
- Upgrade to gesture recognition using ML models.
- Implement emergency auto-stop feature.
  
---

## 👥 Project Team

This project was developed as part of our academic project.

| Name | Role & Contribution |
|-----|---------------------|
| Sai Sushma | Hardware setup, circuit integration, component testing, and system implementation|
| B.V.S Lahari () | Arduino programming, Bluetooth communication logic, and documentation |

---

## 📜 License

This project is developed for educational and research purposes.  
Feel free to use and modify it for learning.

---

## 🙌 Acknowledgments

- Arduino documentation and tutorials  
- Embedded systems lab resources
- Faculty mentors and project guides for their guidance
