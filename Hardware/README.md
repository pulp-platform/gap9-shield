# GAP9Shield Hardware Documentation  

## Introduction  
This section provides all the necessary design files and resources for the hardware development of the **GAP9Shield**, a high-performance, low-power module designed for AI-driven applications on nano-drones. The GAP9Shield hardware is designed to optimize performance for nano-drones while maintaining a lightweight and compact form factor. Key features include:  
- **High-Performance ToF Sensors**: Enable obstacle avoidance and environmental mapping with high accuracy and low latency.  
- **GAP9 SoC Integration**: Ensures efficient processing for AI workloads with ultra-low power consumption.  
- **Easy Assembly**: Modular design allows for straightforward assembly and soldering.
 
 he hardware integrates multiple components, including the GAP9 SoC, a high-definition camera, and a 5D ranging array. The provided resources are organized into three folders, detailed below. 

---

## Folder Structure  

### 1. Hardware  
The `Hardware` folder contains all the design files necessary for the GAP9Shield and its associated subsystems. Each folder includes files created in **Altium Designer**, enabling straightforward editing and fabrication.


#### 1.1 gap9_deck_v2  
- **Description**: This folder contains the complete design files for the main shield PCB, integrating the GAP9 SoC, NINA-W102 Wi-Fi/BLE module, and OV5647 camera.  
- **Features**:  
  - 6-layer PCB with dimensions of 50mm x 27mm.  
  - Optimized layout for compactness and power efficiency.  
  - Interfaces for the ToF subsystems and external peripherals.

#### 1.2 ToF-FrontBack  
- **Description**: This folder contains design files for the **front** and **back** Time-of-Flight (ToF) sensor PCBs.  
- **Notes**:  
  - PCBs use the VL53L1 laser-based ToF sensors.  
  - These sensors enable precise distance measurements of up to 400 cm.  
  - These PCBs must be mounted first and soldered to the main PCB.

#### 1.3 ToF-LeftRight  
- **Description**: This folder contains design files for the **left** and **right** ToF sensor PCBs.  
- **Notes**:  
  - Utilizes the same VL53L1 ToF sensors as the front and back PCBs.  
  - These PCBs must also be mounted and soldered to the main PCB.  


---

For additional details, contact the development team.  
