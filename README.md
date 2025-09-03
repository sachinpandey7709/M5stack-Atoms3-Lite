# M5Stack AtomS3 Lite as USB Rubber Ducky 🦆⚡

The **M5Stack AtomS3 Lite** is a compact ESP32-S3 based IoT development board that can also be programmed to emulate a **USB HID keyboard**.  
Using this capability, it can act like a **USB Rubber Ducky**, automatically typing keystrokes and executing predefined scripts when plugged into a computer.

---

## ⚠️ Disclaimer
This project is intended **only for educational and ethical penetration testing purposes**.  
The author does **not take responsibility** for any misuse.  
Use it **only on systems you own or have explicit permission to test**.

---

## 📦 Requirements
- M5Stack AtomS3 Lite (ESP32-S3 based board)  
- USB-C cable  
- Arduino IDE or PlatformIO  
- HID/USB libraries for ESP32-S3  

---

## Flashing Process using Command Prompt
```bash
esptool.exe --port COM11 --baud 460800 write_flash -z 0 combined.bin

```
- Your M5stack-Atoms3-Lite is ready to use
