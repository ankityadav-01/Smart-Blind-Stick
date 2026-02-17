# 🦯 Smart Blind Stick using Arduino & AI Object Detection

## 📌 Overview
Smart Blind Stick is an assistive device designed for visually impaired people.
It detects obstacles using sensors and AI-based object detection and alerts the user via buzzer and voice output.

## 🎯 Features
- Obstacle detection using ultrasonic sensor
- AI-based object detection using ESP32-CAM
- Voice feedback using text-to-speech
- Lightweight and portable
- Real-time environment sensing

## 🛠️ Technologies Used
- Arduino Uno
- ESP32-CAM
- Ultrasonic Sensor (HC-SR04)
- Buzzer
- Battery module
- TensorFlow Lite (for object detection)

## ⚙️ Working
1. Ultrasonic sensor detects obstacles.
2. ESP32-CAM captures images.
3. AI model detects objects.
4. User gets voice alert via speaker/buzzer.

## 🧠 AI Model
- Framework: TensorFlow Lite
- Dataset: Custom dataset for obstacle detection
- Output: Object class + voice alert

## 🔌 Circuit Diagram
![Circuit](hardware/circuit_diagram.png)

## 📸 Prototype
![Prototype](images/prototype.jpg)

## 📂 Installation

### Arduino Setup
- Install Arduino IDE
- Upload `arduino_code.ino`

### ESP32 Setup
- Install ESP32 board in Arduino IDE
- Upload `esp32_cam_code.ino`

## ▶️ How to Run
1. Connect sensors and ESP32-CAM.
2. Power ON the device.
3. Stick starts detecting obstacles automatically.

## 📈 Future Improvements
- GPS tracking
- Mobile app integration
- Vibration feedback

## 👨‍💻 Author
Ankit Kumar Yadav
