# 🌡 ESP32 IoT Warehouse Monitoring System

A **real-time IoT-based Warehouse Monitoring System** using **ESP32**, **DHT11**, **Soil Moisture Sensor**, **MQ2 Gas Sensor**, and **Relay-controlled appliances**, integrated with **Blynk Cloud** and a **custom web dashboard**.

This project monitors environmental conditions and provides **automatic + manual control**, live visualization, and downloadable reports.

---

## 🚀 Features

- 📡 Real-time Temperature & Humidity monitoring (DHT11)
- 🌱 Warehouse Moisture monitoring (Soil Sensor)
- ☣️ Gas monitoring (NH3 & H2S via MQ2 – indicative values)
- 🌀 Automatic fan control based on temperature
- 💡 Manual light control via Blynk
- 🌐 Live Web Dashboard (no backend required)
- 📊 Interactive graphs & gauges
- 📄 Downloadable **CSV** and **PDF reports**
- 🌗 Dark / Light theme toggle
- ⚠️ Visual alerts for critical conditions

---

## 🧰 Tech Stack

### Hardware
- ESP32
- DHT11 Temperature & Humidity Sensor
- Soil Moisture Sensor
- MQ2 Gas Sensor
- Relay Module (Fan & Light)
- Fan / Bulb (Load)

### Software
- Arduino IDE
- Blynk IoT Cloud
- HTML, CSS, JavaScript
- Chart.js, JustGage, jsPDF

---

## 🔌 Hardware Connections

| Component | ESP32 Pin |
|---------|----------|
| DHT11 Data | GPIO 4 |
| Soil Moisture | GPIO 34 (Analog) |
| MQ2 Gas Sensor | GPIO 35 (Analog) |
| Fan Relay | GPIO 5 |
| Light Relay | GPIO 23 |
| VCC | 3.3V / 5V (as required) |
| GND | GND |

📷 **Connection Diagram:**  
See `diagrams/connection_diagram.png`

---

## 🌐 Dashboard Preview

📁 Location: `dashboard/index.html`  
Just open the file in any modern browser.

**Dashboard includes:**
- Live gauges
- Real-time line charts
- Fan status animation
- System alerts
- CSV & PDF report download

---

## ⚙️ Blynk Virtual Pins

| Virtual Pin | Function |
|-----------|---------|
| V0 | Temperature |
| V1 | Humidity |
| V2 | Fan Status |
| V3 | Soil Moisture |
| V4 | NH3 (Gas) |
| V5 | H2S (Gas) |
| V6 | Light Control |

---

## ▶️ How to Run

### ESP32 Setup
1. Open `esp32/esp32_iot_warehouse.ino`
2. Add your **WiFi SSID & Password**
3. Add your **Blynk Auth Token**
4. Upload to ESP32

### Dashboard
1. Open `dashboard/index.html`
2. Ensure ESP32 is online
3. View live data instantly

---

## 📄 Reports

- 📥 **CSV** → Download raw sensor data
- 📄 **PDF** → Auto-generated system report with averages

---

## 📌 Future Enhancements

- Cloud database (Firebase / MySQL)
- Mobile-friendly PWA
- AI-based prediction alerts
- Multi-node ESP32 support
- Role-based access dashboard

---

## 👨‍💻 Author

**Manoj**  
Computer Engineering Student  
IoT | Web | AI Projects  

⭐ If you like this project, give it a star!
