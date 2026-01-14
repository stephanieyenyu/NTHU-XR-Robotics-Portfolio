# AR Smart Navigation Assistant

## Demo & Screenshots
**Click the link below to view the mobile AR demo:**
### [AR Smart Navigation Assistant Demo](https://drive.google.com/drive/folders/1aC1xBnlhtPrTU1PR1Pj2C_XU3ZUDGN5A?usp=drive_link)

---

## Overview
A mobile AR application leverages **AR Foundation** to recognize the physical environment and overlay digital navigation cues. This serves as a prototype for indoor navigation systems.

## Technical Implementation
* **SLAM (Simultaneous Localization and Mapping):** Utilized ARCore/ARKit subsystems to track the device's position in real-time relative to the environment.

* **Plane Detection & Raycasting:** Implemented algorithms to detect horizontal and vertical surfaces (floors/walls) and successfully anchor virtual objects using screen-to-world raycasting.

* **Spatial Anchors:** Ensured that placed virtual objects remain stable and drift-free even when the camera moves rapidly or loses focus temporarily.
