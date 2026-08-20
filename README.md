# ESP32-Plant-Water-Control-System
🌱 Smart Indoor Water Plant System

An **ESP32-based IoT plant monitoring and automatic watering system** designed to keep indoor plants healthy with minimal human intervention.

The system monitors **soil moisture, water-tank level, battery voltage, and pump status**. When the soil becomes dry, it automatically checks the tank level and activates the water pump. The pump operates in controlled cycles and stops when the soil reaches the required moisture level or when the tank becomes empty.

📡 **Firebase** is used for remote monitoring of sensor and pump data.

📶 The system supports **automatic saved Wi-Fi connection** and provides an **ESP32 Access Point with a web interface** for configuring Wi-Fi when no saved network is available.

### ⚙️ Key Features

* 🌱 Automatic plant watering
* 💧 Water-tank monitoring & pump protection
* 🔋 Battery voltage monitoring
* ☁️ Firebase IoT monitoring
* 📶 Smart Wi-Fi configuration
* 💡 Wi-Fi status LED indication
* 🧵 FreeRTOS task & queue architecture

**Built with:** ESP32 • ESP-IDF • FreeRTOS • C • Firebase • Wi-Fi • Ultrasonic Sensor • ADC

> **Sense → Decide → Act → Monitor 🌱⚡**
