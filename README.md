# usb2.0hub






3D Renders:
<img width="1560" height="1306" alt="Snímek obrazovky 2026-07-14 v 21 22 59" src="https://github.com/user-attachments/assets/0598ed6d-f893-43b4-b634-4fb6ff7ee5d5" />
<img width="1299" height="767" alt="Snímek obrazovky 2026-07-14 v 21 22 10" src="https://github.com/user-attachments/assets/7a30efaa-0453-4d52-b2c3-f2638624de9d" />
<img width="856" height="1293" alt="Snímek obrazovky 2026-07-14 v 21 21 46" src="https://github.com/user-attachments/assets/2e50bb1c-4e28-402e-ac71-d6bf79e00d23" />









## 🚀 USB 2.0 High-Speed Hub

This project is a custom-designed **4-port USB 2.0 hub** built around the WCH CH334F controller. It is optimized for stable data transmission and reliable power distribution.

### ⚡ Core Specifications
* **Protocol:** USB 2.0 High-Speed
* **Transfer Rate:** Up to 480 Mbps
* **Controller IC:** CH334F
* **Upstream Port:** 1x USB [Type-C] (Connection to PC/Host)
* **Downstream Ports:** 4x USB [Type-A] (Connection for peripherals)

### 🛠️ PCB Design & Stackup
To ensure signal integrity and proper 90Ω differential impedance for the USB data lines, the board is designed as a **4-layer PCB**. 

**Layer Stackup:**
1. **Top Layer:** Signal (Main high-speed routing and components)
2. **Inner Layer 1:** GND Plane (Solid ground reference)
3. **Inner Layer 2:** Power Plane (Power distribution)
4. **Bottom Layer:** Second Signal (Low-speed routing and signal crossovers)
