# 🌸 Smart Pollination System

### AI-Powered Robotic Pollination for Precision Agriculture

An intelligent agricultural robotics system designed to automate greenhouse pollination through computer vision, embedded systems, IoT-based environmental monitoring, and robotic actuation.

**🏆 Research Publication:** This project resulted in a published research paper at **ESIC 2026**.

---

## 📌 Overview

The Smart Pollination System is an AI-integrated robotic framework developed to improve pollination efficiency in greenhouse environments.

Traditional greenhouse pollination relies heavily on manual labor, making the process time-consuming and labor-intensive. This project addresses these challenges by integrating real-time flower detection, robotic movement, automated brush-based pollination, and environmental monitoring into a unified system.

Built around Raspberry Pi 5, the system uses YOLOv8 for flower detection, a camera module for live video streaming, and a servo-controlled brush mechanism for targeted pollination.

The system also incorporates a DHT11 sensor to monitor temperature and humidity, transmitting environmental data to the ThingSpeak IoT platform for real-time visualization.

## ✨ Key Features

- **AI-Based Flower Detection:** Real-time flower identification using YOLOv8 and OpenCV.
- **Robotic Navigation:** Wireless robot movement using DC motors and UDP communication.
- **Automated Pollination:** Servo-controlled brush mechanism triggered upon successful flower detection.
- **Environmental Monitoring:** Temperature and humidity monitoring using DHT11.
- **IoT Integration:** Cloud-based environmental data visualization using MATLAB ThingSpeak.
- **Live Video Streaming:** MJPEG camera streaming for real-time monitoring.
- **Human-in-the-Loop Control:** Desktop-based Tkinter interface for navigation and system monitoring.

## 🏗️ System Architecture

The system consists of four major modules:

1. **Input Module:** Camera module and DHT11 environmental sensor.
2. **Processing Module:** Raspberry Pi 5 for embedded hardware control and communication.
3. **Control & AI Module:** Desktop-based YOLOv8 flower detection, OpenCV processing, and operator interface.
4. **Output & IoT Module:** Servo motor pollination, DC motor navigation, and ThingSpeak environmental monitoring.

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Embedded Platform | Raspberry Pi 5 |
| Computer Vision | OpenCV |
| Deep Learning | YOLOv8 |
| Sensors | DHT11 |
| Motor Control | L293D, DC Motors, SG90 Servo |
| Communication | UDP, HTTP, Wi-Fi |
| GUI | Tkinter |
| IoT Platform | ThingSpeak |
| Visualization | MATLAB |
| Development Tools | VS Code, PuTTY |

## ⚙️ Working Methodology

1. The camera captures live images from the greenhouse environment.
2. Video frames are streamed to the desktop system using MJPEG over Wi-Fi.
3. YOLOv8 processes the frames and identifies flowers using confidence-based detection.
4. Once a flower is detected, the desktop AI module sends a UDP command to the Raspberry Pi.
5. The Raspberry Pi activates the servo motor, which operates the brush mechanism to simulate artificial pollination.
6. DC motors facilitate robotic navigation through operator-controlled commands.
7. Simultaneously, DHT11 collects temperature and humidity readings and uploads them to ThingSpeak.

## 🧪 Experimental Results

The prototype was tested in a controlled greenhouse-like environment using artificial flowers.

The experimental implementation demonstrated:

- Successful real-time flower detection.
- Wireless robotic navigation.
- Servo-based automated pollination.
- Continuous temperature and humidity monitoring.
- Successful cloud-based environmental data visualization.
- Integration of AI processing with embedded robotic control.

## 📄 Research Publication

This project resulted in a research paper published at **ESIC 2026**.

The research explores the integration of artificial intelligence, computer vision, IoT, and robotics for intelligent greenhouse pollination.

## 📚 Project Documentation

The complete project documentation is available in the repository.

**Project Report:** `docs/Smart_Pollination_System_Report.pdf`

## 🚀 Future Enhancements

- Fully autonomous greenhouse navigation.
- Improved flower detection under varying lighting conditions.
- Integration of advanced environmental sensors.
- Multi-robot coordination.
- Enhanced pollination accuracy and performance evaluation.

## 👩‍💻 Contributors

Developed as an academic research and engineering project at BNMIT, Department of Computer Science and Engineering.

---

**Keywords:** Artificial Intelligence | YOLOv8 | Robotics | Raspberry Pi 5 | Computer Vision | IoT | Precision Agriculture | Smart Farming
