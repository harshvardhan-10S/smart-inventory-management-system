# 📦 Smart Inventory Management System
_A Load-Cell & IoT Based Automated Stock Monitoring System_

---

## 📌 Overview
The **Smart Inventory Management System** automates stock tracking using a load cell (HX711), microcontroller (ESP8266/Arduino), and IoT cloud monitoring.  
It eliminates manual stock counting, reduces errors, and improves supply-chain efficiency.

---

## 🎯 Objectives
- Maintain accurate, real-time inventory levels  
- Reduce stockouts and overstocking  
- Automate stock counting using sensors  
- Improve supply chain visibility  
- Enable remote monitoring using IoT  

---

## 🧠 Problem Statement
Traditional inventory systems rely on manual processes, leading to:  
- Overstocking  
- Stockouts  
- Wastage  
- Manual counting errors  
- Delayed stock updates  

This project solves these issues using **load-cell automation + cloud monitoring**.

---

## 📚 Literature Review (Summary)
Based on uploaded research files, the study explores:  
- IoT-based stock monitoring  
- Load-cell accuracy (HX711 + microcontroller)  
- RFID for item identification  
- Cloud dashboards for monitoring  
- Ultrasonic and environmental sensing  
- Smart storage systems using NodeMCU & Arduino

These technologies show that a **weight + IoT approach** is low-cost, scalable, and accurate.

---

## 🧰 Components Used
- Load Cell (5–10 kg)  
- HX711 Amplifier Module  
- ESP8266 NodeMCU / Arduino  
- OLED Display (128×64 I2C)  
- RFID Module (optional)  
- Ultrasonic Sensor (optional)  
- DHT22 Temperature/Humidity Sensor  
- PIR Sensor  
- DS3231 RTC Module  
- Buzzer/LED for low-stock alert  

---

## ⚙️ Working Principle

### ✔ 1. Weight-Based Stock Calculation
The load cell measures total weight.  
With known unit weight:

### ✔ 2. Local Alerts
- OLED displays live weight & item count  
- Buzzer/LED alerts if stock < threshold  

### ✔ 3. IoT Cloud Monitoring
- ESP8266 uploads data to ThingSpeak  
- Cloud graphs show live inventory  
- Alerts can be sent using APIs  

### ✔ 4. Optional Sensors
- RFID → item identification  
- Ultrasonic → shelf height monitoring  
- DHT22 → environment monitoring  
- PIR → security  

---

## 📝 Project Files Included
- Smart Inventory Management System Report (PDF)  
- Smart Inventory Research Paper (PDF)  
- Arduino Code (`inventory.ino`)  
- Circuit & block diagrams (optional)  

---

## 📊 Results & Discussion
According to research:  
- System provides **high accuracy** using load cell + HX711  
- Reduces manual errors and improves speed  
- Cloud dashboard improves decision-making  
- Cost-effective and scalable for multiple shelves  
- Suitable for retail, warehouses, and industry  

---

## 🚀 Future Scope
- AI-based demand forecasting  
- Mobile app integration  
- Multi-shelf inventory cloud dashboard  
- RFID + camera vision tracking  
- Robotics for automated warehouse management  

---

## 📝 Conclusion
The Smart Inventory Management System offers an efficient, accurate, and scalable solution for real-time inventory tracking.  
Using load cells, IoT connectivity, and cloud dashboards, it reduces manual effort, improves accuracy, and strengthens supply-chain management.

---

## 👨‍💻 Developer
**Harshvardhan Shinde**  
Electronics & Telecommunication Engineering (ENTC)  
VIT Pune
