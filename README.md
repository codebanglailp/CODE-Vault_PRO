# 🔐 CODE Vault PRO

> A Secure Offline Embedded Vault System built with ESP8266
> Designed for privacy, local control, and lightweight security.

---

## 📌 Overview

**CODE Vault PRO** হলো একটি Secure Embedded Data Vault System যা ESP8266 ব্যবহার করে তৈরি।
এটি সম্পূর্ণ Offline ভিত্তিক — কোনো Cloud dependency নেই।

WiFi access + OLED display + Button navigation + LittleFS secure storage ব্যবহার করে একটি lightweight কিন্তু powerful vault system তৈরি করা হয়েছে।

---

## 🚀 Core Features

- 🔒 PIN-Based Lock System
- 📟 OLED Menu Interface (SSD1306)
- 🔘 Physical Button Navigation
- 🌐 WiFi STA Configuration
- 📂 LittleFS Local Storage
- 🔋 Real Battery Monitoring
- ⏰ NTP Date & Time Sync
- 📱 Real QR Code Generation
- 🕒 Auto Screen Timeout
- 🛜 Secure WiFi Config Portal
- 💾 Fully Offline Secure Operation

---

## 🛠 Supported Boards

- ESP8266MOD
- NodeMCU
- LOLIN (WEMOS) D1 Mini
- D1 R2

> Multi-board support ready (configurable pin mapping)

---

## 🔌 Hardware Requirements

| Component          | Description                    |
| ------------------ | ------------------------------ |
| ESP8266 Board      | NodeMCU / D1 Mini / ESP8266MOD |
| OLED Display       | SSD1306 I2C (128x64)           |
| Push Buttons       | 2–3 Buttons                    |
| Battery (Optional) | 18650 + TP4056                 |
| Storage            | LittleFS                       |

---

## 📍 Example Pin Configuration (D1 Mini)

| Component   | GPIO        |
| ----------- | ----------- |
| OLED SDA    | D2 (GPIO4)  |
| OLED SCL    | D1 (GPIO5)  |
| OK Button   | D6 (GPIO12) |
| BACK Button | D7 (GPIO13) |
| Battery ADC | A0          |

> ⚠ Board অনুযায়ী pin পরিবর্তন করতে হবে।

---

## 💻 Software Requirements

- Arduino IDE (1.8.19 Recommended)
- ESP8266 Board Package
- LittleFS Data Upload Tool

### 📚 Required Libraries

- ESP8266WiFi
- LittleFS
- Adafruit SSD1306
- Adafruit GFX
- ArduinoJson
- NTPClient

---

## ⚙ Installation Guide

### 1️⃣ Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/CODE-Vault_PRO.git
```

---

### 2️⃣ Open in Arduino IDE

- Open `.ino` file
- Select correct ESP8266 board
- Select correct COM port

---

### 3️⃣ Upload LittleFS Data

Install LittleFS uploader tool and upload `/data` folder.

---

### 4️⃣ Upload Firmware

Click **Upload**

---

## 🌍 Web Interface

Device boot হলে:

- WiFi Config Mode এ যাবে
  অথবা
- Saved WiFi তে connect হবে

Browser এ গিয়ে IP Address দিয়ে Web UI access করা যাবে।

---

## 🔐 Security Recommendations

- Default PIN change করুন
- Strong WiFi Password ব্যবহার করুন
- Public network এ ব্যবহার করলে সতর্ক থাকুন

---

## 📦 Generate .bin File

Arduino IDE:

```
Sketch → Export Compiled Binary
```

---

## 📸 Screenshots

Add your device photos inside:

```
/screenshots/
```

---

## 📜 License

MIT License

---

## 👨‍💻 Developed By

**CODE Bangla**
Embedded Security Developer 🚀

---
