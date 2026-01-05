# ESP32-Based Temperature and Pressure Monitoring System

## Project Overview
This project focuses on the design and implementation of an ESP32-based environmental monitoring system capable of measuring temperature, atmospheric pressure, and altitude in real time. The system integrates an ESP32 microcontroller with a BMP280 sensor, enabling wireless data transmission and cloud-based storage for monitoring and analysis.

The collected sensor data is transmitted over Wi-Fi and stored in Firebase Realtime Database and Firestore, with a web application used for visualization.

---

## Objectives
- Design a low-cost and efficient environmental monitoring system
- Interface the ESP32 microcontroller with the BMP280 sensor
- Transmit sensor data wirelessly using Wi-Fi
- Store real-time and long-term data in cloud databases
- Visualize environmental data through a web application

---

## Hardware Components
- ESP32 Development Board
- BMP280 Temperature and Pressure Sensor
- Breadboard
- Jumper Wires
- USB Cable

---

## Software and Technologies Used
- Arduino IDE
- ESP32 Board Package
- Firebase Realtime Database
- Firebase Firestore
- Wi-Fi Communication
- React.js
- Material UI

---

## System Architecture
1. The BMP280 sensor measures temperature, pressure, and altitude
2. The ESP32 microcontroller reads sensor data using I2C communication
3. Data is transmitted wirelessly via Wi-Fi
4. Real-time sensor values are stored in Firebase Realtime Database
5. Averaged data is periodically stored in Firebase Firestore
6. A web application retrieves and displays the stored data

---

## Features
- Real-time temperature, pressure, and altitude monitoring
- Wireless data transmission
- Cloud-based data storage
- Web-based data visualization
- Low power consumption
- Scalable IoT architecture

---

## Experimental Procedure
1. Connect the ESP32 and BMP280 sensor using a breadboard
2. Program the ESP32 using Arduino IDE
3. Verify sensor readings through the Serial Monitor
4. Transmit sensor data to Firebase databases
5. Display data using the web application

---

## Results
- Accurate temperature and pressure measurements
- Stable wireless data transmission
- Successful real-time and long-term cloud storage
- Functional web dashboard for data visualization

---

## Applications
- Weather monitoring systems
- Indoor climate control
- Environmental monitoring
- IoT-based smart systems
- Altitude tracking

---

## Conclusion
The ESP32-based temperature and pressure monitoring system demonstrates an effective and economical approach to real-time environmental sensing. The integration of cloud storage and web-based visualization enhances usability and scalability, making the system suitable for a wide range of IoT applications.

---

## Author
Anisha Maria Lobo  
B.Sc. Physics, Semester VI  
St Aloysius (Deemed to be University), Mangaluru

## License
This project is intended for academic and educational purposes.
