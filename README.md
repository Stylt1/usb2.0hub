View this project on [CADLAB.io](https://cadlab.io/project/30472). 

# usb2.0hub






3D Renders:
<img width="1923" height="1321" alt="Snímek obrazovky 2026-07-14 v 21 36 32" src="https://github.com/user-attachments/assets/59c51e70-261d-4d27-8e77-90c16c9fd7dc" />
<img width="1930" height="1332" alt="Snímek obrazovky 2026-07-14 v 21 35 33" src="https://github.com/user-attachments/assets/38fb9fdf-d87b-458f-ab48-dab8ab6f8b59" />
<img width="759" height="1334" alt="Snímek obrazovky 2026-07-14 v 21 34 42" src="https://github.com/user-attachments/assets/5a82f42f-5ee5-475c-9b3a-07785f0adf8b" />










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
