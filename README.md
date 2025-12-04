# 🐝 BeeDuo System
### Dual-UART USB to RS232/RS485 Converter with OLED Display

**BeeDuo System** is a compact two-board ecosystem built around the **CP2105 Dual UART bridge**, designed for engineers, embedded developers, and field technicians working with serial communication.  
It provides **USB → RS232/RS485** conversion, protocol switching, and live data monitoring through an onboard **OLED display**.

---

## 🚀 Features

### 🟡 **BeeDuo Core (Board 1) — USB Dual UART Module**
- Powered by **CP2105 Dual UART**
- Independent **UART0** and **UART1** channels
- High-speed, stable USB connection
- Plug-and-play on Windows, Linux, and macOS
- Compact hardware for development or integration

### 🟡 **BeeDuo Interface (Board 2) — RS232 / RS485 + OLED**
- Supports **RS232**, **RS485**, or **Dual RS485** mode
- On-board switching:
  - **RS232 ↔ RS485**
  - **Dual RS485** (both UARTs mapped to RS485)
- **0.96" OLED display** for live monitoring:
  - Baud rate
  - Mode status
  - Data activity
  - Error indicators

---

## 🧩 Architecture

The system is made of **two modular boards**:

1. **BeeDuo Core**  
   Handles USB communication and provides dual UART signals.

2. **BeeDuo Interface**  
   Converts UART to RS232/RS485 and displays runtime info on the OLED.

Use them together as a complete system or individually for custom projects.

---

## 💡 Why BeeDuo?

- Dual UART flexibility  
- Protocol switching without rewiring  
- Real-time OLED diagnostics  
- Modular field-friendly design  
- Ideal for testing, debugging, and industrial interfacing  

---

## 📁 Repository Structure
/BeeDuo_System
│
├── BeeDuo_Core/ # CP2105 USB to Dual UART Board
├── BeeDuo_Interface/ # RS232/RS485 + OLED Display Board
├── Firmware/ # Display control & mode switching logic
├── Hardware/ # Schematics, KiCad files, Gerbers
├── Enclosure/ # 3D-printable enclosure (optional)
└── Docs/ # Datasheets, pinouts, manuals


---

## 🛠️ Planned Add-Ons
- UART monitoring and logging tools  
- Printable protective case  

---

## 📜 License
MIT License – free to use, modify, and build upon.

