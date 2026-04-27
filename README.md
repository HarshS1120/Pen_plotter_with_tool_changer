# 🎨 CNC Pen Plotter with Automatic Tool Changer

This project implements a DIY CNC drawing machine capable of automatically switching pens to create multi-color drawings.

It combines mechanical design, embedded systems, and motion control using Arduino and GRBL firmware.

---

## 🚀 Features

- 🖊️ Automatic pen/tool changing mechanism
- 🎨 Multi-color drawing capability
- 📐 3-axis CNC motion system (X, Y, Z)
- ⚙️ G-code based control
- 🔁 Servo-based gripper for tool switching
- 📊 High precision drawing (0.6mm pen tested)

---

## 🧠 System Architecture

Image → G-code → Arduino (GRBL) → Stepper Motors → Drawing Output

---

## 🛠️ Hardware Components

- Arduino UNO
- CNC Shield
- A4988 Stepper Drivers (×3)
- NEMA 17 Stepper Motors (×3)
- Servo Motor (tool changer)
- Linear rails + belts (GT2)
- Power supply (12V)

---

## ⚙️ Software Stack

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

## Results

(Add images/videos here)

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
