# Weather Reporting System using NodeMCU (ESP8266) 🌦️📡

## 📚 Project Description

This project is an **IoT-based Weather Reporting System** developed using the **NodeMCU (ESP8266)** microcontroller. It monitors **air quality**, **temperature**, **humidity**, and **rainfall** in real-time using various sensors, and displays the data on a **16x2 LCD display**. The system can also send this data wirelessly to cloud platforms for remote monitoring and logging.

## 🔧 Hardware Components

- 🌐 **NodeMCU ESP8266** – Wi-Fi enabled microcontroller
- 🌡️ **DHT11** – Temperature and humidity sensor
- 🌫️ **MQ135** – Air quality/gas sensor
- 🌧️ **Rain Sensor** – Detects presence of rain
- 📟 **16x2 LCD Display** – Shows real-time data
- 🔌 **Breadboard, jumper wires, resistors**

## ⚙️ Features

- Live monitoring of:
  - Temperature (°C)
  - Humidity (%)
  - Rain detection (Yes/No)
  - Air quality (Ppm scale)
- Real-time data display on LCD
- IoT-enabled (optional: Blynk, ThingSpeak, Firebase)
- Low-cost, energy-efficient design


## 💻 Software Requirements

- Arduino IDE
- ESP8266 Board Manager
- Libraries:
  - `Adafruit_Sensor`
  - `DHT.h`
  - `LiquidCrystal_I2C.h`
  - `Wire.h`

## 🚀 Installation & Setup

1. Install **Arduino IDE** and add the ESP8266 board via Board Manager.
2. Install required libraries from the Library Manager.
3. Connect your NodeMCU to PC via USB.
4. Upload the code using Arduino IDE.
5. Open Serial Monitor (9600 baud rate) to debug values.

## 🖼️ Screenshots

![Screenshot 2025-05-07 213216](https://github.com/user-attachments/assets/f05c5d3a-f60f-48b8-a724-d003111a4f28)
![Screenshot 2025-05-07 213223](https://github.com/user-attachments/assets/1951f1eb-93be-4d13-a65c-4323105728a8)









