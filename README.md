# 🤖 Lift And Navigation Control Equipment (LANCE Bot)

**Smart India Hackathon 2020 – Hardware Edition**  
**Team: LANCE**  
**Category: Student Innovation**  
**Project Type: Autonomous Robotics**  
📺 [Project Video Demo](https://www.youtube.com/watch?v=ViAYeuPM1gA)

---

## 🚀 Overview

** LANCE Bot** is an autonomous material handling robot designed to automate lifting and navigation tasks in warehouse environments. It was developed as part of the Smart India Hackathon 2020 (Hardware Edition) to address the growing need for contactless, intelligent, and scalable warehouse automation—especially relevant during the COVID-19 pandemic.

The robot integrates real-time SLAM-based navigation, object detection, and remote video streaming. Users can control the bot via any device on the same local network.

---

## 🧠 Problem Statement

Manual labor and human-operated forklifts dominate warehouses in India. This project proposes an automated solution to:
- Reduce human intervention.
- Improve operational efficiency.
- Enable remote and intelligent movement of heavy goods.

---

## 🛠️ Key Features

- 🗺️ Autonomous mapping and navigation using **SLAM (Simultaneous Localization and Mapping)**
- 🎥 Real-time video streaming via **Socket Programming**
- 🧠 Object detection using **OpenCV** and **TensorFlow**
- 🤖 Dual mechanism support: **Forklift** and **Robotic Arm**
- 📡 Local network access and control from any device
- 💸 Cost-effective and scalable design

---

## 🔧 Technology Stack

| Component              | Description                                        |
|------------------------|----------------------------------------------------|
| **Microcontroller**     | Raspberry Pi 4                                    |
| **OS & Middleware**     | ROS Melodic + RPLiDAR (Hector SLAM)               |
| **Sensors**             | RPLiDAR, HC-SR04 Ultrasonic Sensor, Pi Camera     |
| **Computer Vision**     | TensorFlow, OpenCV                                |
| **Programming Language**| Python                                            |
| **Mechanics**           | Prismatic Joint Forklift with Live Mapping        |

---

## 🧱 System Architecture

1. **User Input**: Source and Destination via local web interface  
2. **Map Generation**: Using RPLiDAR-based SLAM  
3. **Object Detection**: Identifies obstacles with OpenCV + Pi Camera  
4. **Navigation**: Dynamic path planning & obstacle avoidance  
5. **Pick & Place**: Robotic Arm or Forklift mechanism  

---

## 📸 Prototype Snapshots

- 📍 Location tracking on network dashboard  
- 🧠 Live object detection  
- 🏗️ Warehouse movement with real-time feed  

(Refer to `SIH2020_round2.pptx.pdf` for images)

---

## 🔄 Dependencies & Assumptions

- Operates in **bounded environments** with **flat surfaces**
- Access limited to **authorized users** on the same Wi-Fi/local network
- SLAM-based mapping does **not require pre-installed markers**

---

## 👨‍💻 Team

**Team LANCE**  
Contributors: Vaishnavi Apsingkar and 6 others

---

## 📢 Acknowledgments

- Smart India Hackathon 2020 (Hardware Edition)
- Ministry of Education, Government of India
- Mentors, evaluators, and institutional support

---

## 📽️ Demo

🎥 Watch our project in action:  
**[👉 Click here to watch the demo video](https://www.youtube.com/watch?v=ViAYeuPM1gA)**
