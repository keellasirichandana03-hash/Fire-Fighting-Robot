# 🤖 Autonomous Fire Fighting Robot

<p align="center">
  <a href="https://www.linkedin.com/in/keella-siri-chandana-lakshmi-priyanka-166654259/">
    <img src="https://img.shields.io/badge/LinkedIn-K Siri Chandana-blue?logo=linkedin" />
  </a>
</p>

## 📌 Project Overview
An autonomous fire fighting robot built using Arduino that 
automatically detects fire, sprays water to extinguish it, 
and sends emergency SMS and call alerts to the user if the 
fire is not extinguished within a set time.

---

## ⚙️ Features
- 🔥 Automatic fire detection using fire sensor
- 💧 Auto water spraying on fire detection
- ⏱️ If fire not extinguished in 5 seconds — sends emergency SMS
- 📞 If fire not extinguished in 15 seconds — calls and sends SMS
- 🤖 Fully autonomous robot movement using wheels and motors
- 🔧 Servo motor controls water spray direction

---

## 🛠️ Hardware Components

| Component | Purpose |
|---|---|
| Arduino UNO | Main controller |
| Fire Sensor | Detects fire |
| Servo Motor | Controls water spray direction |
| GSM Module (SIM800L) | Sends SMS and makes calls |
| Water Pump | Sprays water on fire |
| Wheels + DC Motors | Robot movement |
| Motor Driver (L298N) | Controls DC motors |
| Power Supply | Powers the robot |
| Jumper Wires | Connections |
| Breadboard | Circuit connections |

---

## 🔌 How It Works

### Module 1 — Fire Detection & Water Spray
1. Fire sensor continuously monitors surroundings
2. When fire detected → Water pump activates immediately
3. Servo motor directs water spray toward fire
4. Robot moves toward fire automatically

### Module 2 — 5 Second Alert
1. If fire is not extinguished within 5 seconds
2. GSM module sends emergency SMS to user
3. Water spray continues simultaneously

### Module 3 — 15 Second Alert
1. If fire still not extinguished after 15 seconds
2. GSM module calls the user and sends another SMS
3. Robot continues spraying water while alerting

---

## 📦 Libraries Required
Servo.h
SoftwareSerial.h

---

## 🚀 How to Run

Assemble all hardware components as per circuit diagram
Open Arduino IDE
Install required libraries

Servo.h — built in Arduino IDE
SoftwareSerial.h — built in Arduino IDE


Open fire_fighting_robot.ino file
Connect Arduino to laptop via USB
Select correct COM port in Arduino IDE
Upload the code to Arduino board
Power the robot and test


---

## 📷 Project Screenshots

### 🤖 Robot Setup
<img width="465" height="667" alt="Screenshot 2025-01-28 181237" src="https://github.com/user-attachments/assets/85fb606e-485c-4f6c-a92a-894a6ee8092b" />


### 🔌 Circuit Diagram
<img width="1211" height="685" alt="Screenshot 2025-01-29 205436" src="https://github.com/user-attachments/assets/c9a8b216-6cf6-4835-823a-1a19f41d9a84" />


### 📱 SMS Alert
<img width="411" height="243" alt="image" src="https://github.com/user-attachments/assets/e09f9544-ca83-4f89-b58c-edbfee012350" />


---

## 👩‍💻 Author

| Field | Details |
|---|---|
| **Name** | K Siri Chandana Lakshmi Priyanka |
| **Degree** | B.Tech |
| **College** | BVRIT Hyderabad College of Engineering for Women |
| **Email** | keellasirichandana03@gmail.com |
| **LinkedIn** | [linkedin.com/in/keella-siri-chandana](https://www.linkedin.com/in/keella-siri-chandana-lakshmi-priyanka-166654259/) |

---

## 📄 License
This project is open source and available under the 
[MIT License](LICENSE).

---

## ⭐ Support
If you find this project helpful, 
please give it a star ⭐ on GitHub!
