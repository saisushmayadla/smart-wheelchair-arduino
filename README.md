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
smart-wheelchair/
├── code/
│ └── smart_wheelchair.ino
├── circuit/
│ └── circuit_diagram.png
├── images/
│ └── wheelchair_prototype.jpg
├── components/
│ └── components_list.txt
└── README.md

---

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

## 🚀 Future Improvements

- Add voice control support
- Implement obstacle detection using ultrasonic sensors
- Integrate GPS tracking
- Develop a dedicated mobile application
- Add AI-based navigation assistance

---

## 👥 Project Team

This project was developed as part of our academic project.

| Name | Role |
|-----|-----|
| Sai Sushma | Hardware Integration & Testing |
| Team Members | Circuit Design & Development |

---

## 📜 License

This project is developed for educational and research purposes.  
Feel free to use and modify it for learning.

---

## 🙌 Acknowledgments

- Arduino documentation and tutorials  
- Embedded systems lab resources
- Faculty mentors and project guides for their guidance
