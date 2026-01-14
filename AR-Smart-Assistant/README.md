# AR Smart Navigation Assistant

## Demo & Screenshots
**Click the link below to view the mobile AR demo:**
### [View Project Demo on Cloud Drive](在此貼上你的雲端連結)

---

## Overview
A mobile AR application leverages **AR Foundation** to recognize the physical environment and overlay digital navigation cues. This serves as a prototype for indoor navigation systems.

## Technical Implementation
* **SLAM (Simultaneous Localization and Mapping):** Utilized ARCore/ARKit subsystems to track the device's position in real-time relative to the environment.

* **Plane Detection & Raycasting:** Implemented algorithms to detect horizontal and vertical surfaces (floors/walls) and successfully anchor virtual objects using screen-to-world raycasting.

* **Spatial Anchors:** Ensured that placed virtual objects remain stable and drift-free even when the camera moves rapidly or loses focus temporarily.
