# 🚗💡 Car Black Box System




## 🧭 Overview

Imagine a world where every car trip is monitored like a flight!  
This **Car Black Box** project brings aviation-style black box functionality to vehicles. It **logs critical driving parameters**, detects anomalies like **over-speeding or high engine temperature**, and stores event data securely — just like an aircraft's black box.

Ideal for **fleet management**, **accident analysis**, and **proactive maintenance**.

---

## 🎯 Objectives

- 📌 Record key vehicle data during operation
- 🔐 Enable secure access to data
- 🧑‍💼 Help transport managers monitor vehicle efficiency and driver behavior
---

## 🚦 Features

| Feature                | Description |
|------------------------|-------------|
| 🧾 **Event Logging**   | Logs gear shifts, speed, fuel usage, engine temperature |
| 🔒 **Password Access** | Restricts data access to authorized personnel |
| 📤 **Data Export**     | Send logs to PC via UART |
| 📁 **Log Storage**     | Save logs to EEPROM or SD card |

**Login Authentication**  
  Secure access to logs via a password prompt.

- 📝 **View Trip Logs**  
  Displays logs including:
  - Gear position
  - Speed
  - Fuel usage
  - Engine temperature
  - Trip distance
  - Time-stamped events via RTC

- 🔍 **Filter Logs**  
  View logs for:
  - Specific date/time
  - Over-speeding incidents
  - Engine overheat warnings

- 💾 **Download Logs**  
  Export logs via UART to CSV or text files.

- 🧹 **Clear Logs**  
  Optionally reset log memory after export.

---

## 🧰 Tech Stack

- **🧠 Microcontroller**: PIC (e.g., PIC18F4580)
- **💬 Communication**: UART for log transfer
- **📡 Sensors**:
  - Speed (Hall effect or simulated)
  - Engine Temperature (LM35 or similar)
- **💾 Storage**: EEPROM / SD Card
- **💻 Tools**: MPLAB X IDE, XC8 Compiler
- **🔌 Interfaces**: LCD (for display), UART (for communication)

---


