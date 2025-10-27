# RFID-Smart-Door-Lock
Welcome to the Smart Door Lock Security System project repository! This open-source project focuses on enhancing traditional door locking systems using the power of IoT (Internet of Things) technology. By combining the NodeMCU ESP8266 microcontroller with the Blynk app platform.

```markdown
# 🔐 Automatic Door Lock System using RFID RC522

A smart, secure, and contactless access control system built using Arduino, RFID RC522, and a servo motor. Designed for both residential and commercial spaces, this project enhances safety and user convenience.

![Project Demo](![CIRCUIT DIAGRAM](https://github.com/ritvik78/RFID-Smart-Door-Lock/blob/main/CIRCUIT_DIAGRAM.jpg)) 
*Illustration for reference only.*
<img src="https://github.com/ritvik78/RFID-Smart-Door-Lock/blob/main/CIRCUIT_DIAGRAM.jpg" alt="C#" width="40"/>
---

## 🎯 Aim

To design and develop a **prototype of an RFID-based automatic door lock system** using the **RFID RC522 module** and **servo motor**, enabling secure, efficient, and contactless access.

---

## ✅ Objectives

- Enable door access using RFID cards/key fobs for authorized users.
- Use RFID RC522 for reading unique card IDs.
- Control a servo motor for lock/unlock mechanism.
- Deny unauthorized access with real-time feedback via Serial Monitor.
- Ensure easy customization and deployment.

---

## 🛠️ Hardware Used

- Arduino Uno
- RFID RC522 Module
- Servo Motor
- Breadboard & Jumper Wires
- Power Supply

---

## 🧠 Methodology

1. **Initialize**: Setup Arduino, RFID, and servo.
2. **Card Detection**: Continuously scan for RFID cards.
3. **Authorization**:
   - If UID is **authorized** → Unlock door (servo rotates).
   - If UID is **unauthorized** → Access denied.
4. **Feedback**: Display messages via Serial Monitor.

```

START → Initialize Modules → Scan Card
↓               ↓
Card Detected? → Read UID → Authorized?
↓               ↓        ↓
NO            YES     → YES: Unlock
→ NO: Deny

```

---

## ✨ Novelty

- **Contactless access** using RFID.
- **Real-time monitoring** and feedback.
- **Customizable UIDs** for user management.
- **Expandable system** — Add Wi-Fi/Bluetooth for remote access.
- **Energy-efficient** and easily deployable.

---

## 🧾 Deliverables

- Functional prototype with RFID-based locking.
- Secure access based on unique card IDs.
- Real-time access logs via Serial Monitor.
- Adaptable system for residential/commercial spaces.

---

## 📚 References

- *IoT Projects with Arduino and Raspberry Pi* – Rajesh Singh, Anita Gehlot  
- *Embedded Systems* – Raj Kamal  
- *Arduino Projects for Engineers* – Neerparaj Rai  
- *Cyber-Physical Systems* – Siddesh & Ghosh  
- *RFID Design Principles* – Harvey Lehpamer  

---

## 📡 IEEE Standards

- **IEEE 802.11** – Wireless communication standard for future integration.
- **IEEE 2410-2019** – Design of Cyber-Physical Systems.

---

## 👨‍💻 Authors

| Name              | Roll No     |
|-------------------|-------------|
| Rithik Verma      | 102399003   |
| Jaskaran Singh    | 102399002   |
| Abhilasha Tiwari  | 102399001   |
| Dhruv Singh Jaat  | 102219042   |
| Archit Khurana    | 102269010   |


**Department**: Electrical & Instrumentation Engineering  
**Institution**: Thapar Institute of Engineering & Technology, Patiala  
**Academic Year**: 2024–25  
**Supervisor**: Mr. Dharmendra Kumar (Asst. Professor)

---

## 📷 Schematic

>![CIRCUIT DIAGRAM](https://github.com/user-attachments/assets/1fc85702-566e-4420-97ad-88f767554480)
 
> ![HARDWARE IMAGE](https://github.com/ritvik78/RFID-Smart-Door-Lock/blob/main/HARDWARE%20IMAGE.jpg)


---
