# Pia-the-Robot – Replication & Learning Project

## Hardware Replication & Exploration
<img src="Pia-the-Robot-Replication(NO).png" width="100%" style="max-height:200px; object-fit:cover;" />

I was inspired by [Pia-the-robot](https://github.com/BtreeComputingServcies/pia-the-robot), which itself was inspired by [Mira](https://www.youtube.com/watch).

---

## Project Overview

This repository documents my process of replicating, assembling, and exploring the Pia-the-Robot platform based on the original open-source design.

The main objectives are:
1. Rebuild Pia using [Raspberry Pi Pico](https://thepihut.com/products/raspberry-pi-pico-w?srsltid=AfmBOopVhjwxGJgmFiPiU_dQihIodUADGCJEcOd47JI0liRDAYfdv12_)  
2. Study expressive movement and mechanical structure  
3. Understand basic servo kinematics  
4. Document assembly, wiring, and control steps  
5. Learn from an existing open-source robotic system  

This project is continuously updated as part of my learning process.

---

## Hardware Used

| **Components** | Details |
|----------------|---------|
| **Microcontroller** | Raspberry Pi Pico |
| **Servos** | DF9GMS 180° micro servos (X, Y, Z axes) |
| **Magnets** | [6x3mm & 8x1mm](https://www.supermagnete.de/eng/disc-magnets-neodymium/disc-magnet-6mm-3mm_S-06-03-N?group=product_finder) (2 from each) |
| **3D Printed Parts** | All STL files from "Pia the Robot" on [Printables](https://www.printables.com/model/190775-pia-the-robot) |
| **Power** | USB 5V (initial) |
| **Misc** | Jumper wires, screws, servo horns, breadboard |

---

## Servo Control Summary

Pia uses 3 servos controlled by PWM signals at 50 Hz:

1. Y-axis: head tilt left and right  
2. X-axis: head tilt forward and backward  
3. Z-axis: head rotation clockwise and anti-clockwise  

Control is implemented using gradual angle changes to achieve smoother and more natural motion.

---

## 3D Printed Parts

All parts were printed from the Pia-the-Robot model available on [Printables](https://www.printables.com/model/190775-pia-the-robot).

---

## Notes

This work is based on an existing open-source design and is documented here as part of my learning and hands-on exploration.
