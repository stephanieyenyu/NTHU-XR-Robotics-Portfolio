# Digital Twin: UR3e Robotic Arm Control

## 🎥 Demo & Screenshots
**Click the link below to view the Real-time Digital Twin demo:**
### 🔗 [View Project Demo on Cloud Drive](在此貼上你的雲端連結)

---

## 📌 Overview
This project establishes a real-time **Digital Twin** for the Universal Robots **UR3e**. It bridges the gap between the physical industrial robot and the Unity simulation environment using TCP/IP communication.

## ⚙️ Technical Implementation
* **TCP/IP Socket Communication:** Established a direct socket connection to the UR Controller (Port 30003) to receive real-time data streams at 125Hz.
  
* **Big-Endian Data Parsing:** Handled the binary data conversion process, transforming raw byte streams from the robot controller into usable float values for Unity.

* **Coordinate System Mapping:** Solved the spatial mismatch between Unity’s Left-Handed Coordinate System and the Robot’s Right-Handed System to ensure precise movement synchronization.
