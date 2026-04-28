# 🎨 CNC Pen Plotter with Automatic Tool Changer

This project implements a DIY CNC drawing machine capable of automatically switching pens to create multi-color drawings.

It combines mechanical design, embedded systems, and motion control using Arduino and GRBL firmware.

---

## Features

- Automatic pen/tool changing mechanism
- Multi-color drawing capability
- 3-axis CNC motion system (X, Y, Z)
- G-code based control
- Servo-based gripper for tool switching
- High precision drawing (0.6mm pen tested)

---

## System Architecture

Image → G-code → Arduino (GRBL) → Stepper Motors → Drawing Output

---

## Hardware Components

- 8 x15 x 45mm Linear Bearing (x2)
- 8 x 15 x 25mm Linear Bearing (x1)
- 12v Nema 17 stepper motors (x2)
- GT2 Timing belt and pulleys
- Micro servo (x1)
- Elegoo Arduino Uno (x1)
- Stepper drivers - TMC2208 (x2)
- Contact switch (x2)
- Arduino CNC Shield (x1): https
- 30mm 5V Fan (x1)
- 8mm Chromed Steel Rod (35cm x2 & 5.5cm x1)
- 30cm long linear rail with block - MGN12H (x1)
- Electrical wire
- 12v power supply - 2A or greater (x1)
- Barrel Connector - Female (x1)
- 6mm Idler Wheel - 3mm Bore (1)
- Wooden panel to mount project at least 36x42cm
- 3D Printer Filament
- M5 x 25mm (x2)
- 3 x 18 (x3)
- M3 x 12 (x2)
- M3 x10 (x3)
- M3 x 6 (X14)
- M3 nuts (x9)
- M5 nut (x1)
- Short wood screws (x8)

---

## Software Stack

- GRBL firmware (motion control)
- Inkscape (image → G-code)
- GRBL-Plotter / Universal G-code Sender

---

## 🔁 Working Principle

1. Convert image into G-code
2. Send G-code to Arduino
3. Stepper motors move pen in XY plane
4. Z-axis lifts/lowers pen
5. Servo switches pens automatically for color changes

---

## Challenges

- Mechanical alignment and precision
- Tool changer calibration
- G-code optimization
- Belt tension and vibration issues

---

## Future Improvements

- Closed-loop control (encoders)
- Vision-based calibration
- AI-based drawing optimization
- Web interface for remote control

---

## Author

HarshDeep Singh  
(Mechatronics + AI + Robotics)
