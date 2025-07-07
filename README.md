# Rubber latex volume management system at the purchasing factory

## Introduction

This is a project using the ESP32 microcontroller to build an IoT-based rubber latex weight management system at purchasing factories.
- Use RFID (MFRC522) for customer identification at each weighing station.
- Collect weight data directly from industrial scales via RS232 interface.
- Transmit data between scales and central gateway using ESP-NOW protocol for local communication without internet.
- Gateway uploads data to a remote database via HTTPS for centralized processing.
- Desktop application (C++ Qt framework) allows admins, managers, and customers to manage accounts, prices, and view transaction history.
  
Knowledge used in the project:

- Use UART/RS232 protocol to read weight data from electronic scales.
- Use ESP-NOW protocol for fast, lightweight peer-to-peer wireless communication.
- Use RFID SPI protocol for contactless card identification.
- Use HTTPS protocol to securely upload data to server.
- Backend built with FastAPI (Python); frontend desktop app built with Qt (C++).
- Database used is MySQL.

## Result
- PCB layout of the system.
  
![image](https://github.com/user-attachments/assets/2bec9cd2-37ff-49a2-8b78-b8e95d6f17f4)

- PCB of the device placed at the scale.

![image](https://github.com/user-attachments/assets/e6abe984-4494-465e-b080-f387433ad407)

- The device placed at the scale.
  
![image](https://github.com/user-attachments/assets/e6dab6cc-8a36-4ba4-8a9d-a901c5c88fa7)





