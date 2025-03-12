# 🚀 Accident Detection & Alert System  

## 📊 Overview  
This project detects accidents using a **vibration sensor** and **accelerometer**. Upon detection, the system retrieves **GPS coordinates** and sends an **SMS alert** using a **SIM900 GSM module**, helping responders locate the accident site.  

## 🛠 Components  
- **Arduino UNO**  
- **TinyGPS Module**  
- **SIM900 GSM Module**  
- **Accelerometer (ADXL335)**  
- **Vibration Sensor**  

## 🎨 Features  
✅ Accident detection using **sensors**  
✅ Sends **SMS alerts with GPS coordinates**  
✅ **Google Maps link** for tracking  
✅ Uses **SIM900** for communication  

## 🌍 How It Works  
1. The **accelerometer** and **vibration sensor** detect an accident.  
2. The **GPS module** fetches the location.  
3. The **SIM900 module** sends an **SMS alert** with a **Google Maps link**.  

## 💻 Setup Instructions  
1. **Upload** the Arduino code (`accident_alert.ino`).  
2. **Connect components** as per the circuit.  
3. **Insert a SIM card** in the **SIM900 module**.  
4. **Power the system** and monitor on **Serial Monitor**.  

