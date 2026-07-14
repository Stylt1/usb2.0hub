# usb2.0hub





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
