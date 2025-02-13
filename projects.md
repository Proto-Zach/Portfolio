---
title: "Projects"
layout: default
---

# Intro

Throughout my career as an engineer and maker, I have worked on a variety of projects that blend **mechanical design, electronics, and hands-on fabrication**. Each project presented unique challenges, requiring creative problem-solving and technical expertise to develop functional and well-optimized solutions. Below is a collection of selected projects, showcasing my approach to **design, prototyping, and iterative development**.  

Click on a project title to jump directly to its section.  


## Table of Contents

✦ **[Drone Hunting Camera](#drone-hunting-camera)** – AI-driven camera system for drone threat assessment.  
✦ **[3D Printer Toolchanger](#3d-printer-toolchanger)** – A quick-swap toolhead system for an Ender 3 V2.  
✦ **[Engineer’s Toolkit](#engineers-toolkit)** – A compact, everyday carry toolkit for engineers.  
✦ **[Fall Prevention Exoskeleton](#fall-prevention-exoskeleton)** – A lower limb exoskeleton, designed to prevent slips,  trips, and falls.  
✦ **[Soft Actuator](#soft-actuator)** – A bistable actuator, developed to study the snap through mechanics of hollow shells of revolution.  
✦ **[Scale](#scale)** – A simple kitchen scale, inspired by Greek cooking.  
✦ **[Drone](#drone)** – A 3D printed drone, capable of basic flight manuevers.  


---

## Drone Targeting Camera  

### Overview  
This project involved designing an **AI-driven camera system** capable of analyzing drone swarms in real-time. The goal was to classify drones based on threat level and provide prioritization data for defensive measures.  

### My Role  
I developed the **camera testbed** and **sensor integration system**, ensuring that the device could capture and process multiple spectrums of light, including RGB, infrared, and night vision.  

### Design Constraints  
- Must be a **stationary system** with easy deployment.  
- Requires **six peripheral cameras** for full situational awareness.  
- Integrated **NVIDIA Jetson AGX Orin** for AI-based drone recognition.  
- Powered by an **18V battery with buck/boost converters** for power regulation.  
- Must use materials **freely available to Rowan University students**.  

### Design Features  

**➀ Acrylic + 3D Printed Frame**  
- The enclosure was laser-cut from acrylic for visibility, with **PETG 3D-printed brackets** for durability.  
- **TPU feet** were added for shock absorption and surface adaptability.  

**➁ Multi-Sensor Camera System**  
- Includes an **RGB/Night Vision camera** and **IR sensor** for night operation.  
- **Zoom camera & range finder** provide accurate target acquisition.  
- **Threaded brass inserts** allow for easy mounting and prototyping.  

### Images  
<div align="center">
  <img src="path/to/drone_camera_image1.png" alt="Drone Targeting Camera - Front View" style="border-radius: 15px; border: 3px solid black;" width="75%">
  <p>Front view of the drone targeting camera.</p>
  <img src="path/to/drone_camera_image2.png" alt="Camera Sensors" style="border-radius: 15px; border: 3px solid black;" width="75%">
  <p>Close-up of integrated sensors and cameras.</p>
</div>

[🔝 Back to top](#table-of-contents)  


---

## 3D Printer Toolchanger  

### Overview  
Enhancing a **Creality Ender 3 V2** by adding a **low-power laser engraving module** for PCB prototyping while maintaining **print quality and repeatability**.  

### My Role  
Developed a **quick-swap toolhead system** that allows users to switch between a **standard 3D printing extruder** and a **laser engraver** without recalibrating the printer.  

### Design Constraints  
- Must use **minimal materials and budget**.  
- Toolhead must maintain **consistent positioning between swaps**.  
- Must be **thermally resistant** to prevent heat warping.  
- Safety considerations: **fume removal, protective glasses, and filtered exhaust**.  

### Design Features  

**➀ Snap-Fit Dovetails**  
- **Dovetail-style mounting system** eliminates the need for screws/fasteners.  
- SLA-printed mounts ensure **tight fitment and heat resistance**.  

**➁ Signal Re-routing for PWM Control**  
- Integrated a **toggle switch** to reroute the **PWM signal** from the print head’s cooling fan to the laser module.  
- This allows precise power control without modifying the printer's firmware.  

### Images  
<div align="center">
  <img src="path/to/toolchanger_image1.png" alt="3D Printer Toolchanger - Dovetail Mount" style="border-radius: 15px; border: 3px solid black;" width="75%">
  <p>Dovetail mounting system for easy tool swaps.</p>
</div>

[🔝 Back to top](#table-of-contents)  

---

## Engineer’s Toolkit  

### Overview  
A **compact, organized toolkit** designed for engineers who frequently move between **classes, labs, and research meetings**. This set includes **essential tools** without adding excess weight.  

### My Role  
Designed a **portable storage system** and **selected the most versatile tools** for on-the-go use.  

### Design Constraints  
- Must be **small and lightweight**.  
- **Only essential tools** included for maximum functionality.  
- **Secure storage** prevents tool loss and damage.  

### Design Features  

**➀ Compact Casing**  
- Repurposed a **clipboard storage case** with **foam padding** to keep tools secure.  
- Maintains a **professional appearance** while storing everything in one place.  

**➁ Selected Tools**  
- Micro-screwdriver set with **interchangeable bits**.  
- X-Acto knife for **precision cutting**.  
- **Vernier calipers** for accurate measurements.  
- Tweezers, pliers, and side cutters.  

### Images  
<div align="center">
  <img src="path/to/toolkit_image1.png" alt="Engineer’s Toolkit - Open View" style="border-radius: 15px; border: 3px solid black;" width="75%">
  <p>All essential tools neatly stored.</p>
</div>

[🔝 Back to top](#table-of-contents)  

---
## Drone

---
## Scale

---
## Fall Prevention Exoskeleton

---
## Soft Actuator

---

&copy; [Zachary Roberts] - [2025]. All rights reserved.
