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
- 3D shape of the positioning and anti-theft PCB layer.
  
![image](https://github.com/user-attachments/assets/172d292d-629b-4b57-853e-ef1ebd6459d8)

![image](https://github.com/user-attachments/assets/cf0b9f07-e95a-42bf-8d6d-3f4359622625)

- 3D shape of the remote control PCB layer.

![image](https://github.com/user-attachments/assets/fd65eb62-8b5a-4f1d-84d5-d4f4d954369a)

- Interface for tracking vehicle location history, showing each updated position when a change occurs.

![image](https://github.com/user-attachments/assets/524fa7b6-587c-4355-9ef9-756c41c1abb3)




