# Abraham Joseph <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="40px">
<p align="center">
</p>


<p align="center">
  <b>ECE Student • Embedded Systems • Project Builder</b>
</p>


> Electronics enthusiast · Embedded systems tinkerer · Competitive problem-solver  
> S6 EC (Electronics Dept) — passionate about low-level hardware, IoT, and real-world prototypes.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-abraham--joseph-blue?logo=linkedin)](https://www.linkedin.com/in/abraham-joseph-370186291/)
[![Email](https://img.shields.io/badge/Email-abrahamjosephxd@gmail.com-orange?logo=gmail)]

---

## About me
![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00F7FF&center=true&vCenter=true&width=600&lines=Hello)

I'm an electronics engineering student with hands-on experience designing embedded systems and IoT prototypes. I enjoy building practical projects that combine microcontrollers, communication modules, and sensors. I also compete in hardware/software debugging and enjoy teaching basics (e.g., 3D printing) to younger students.
<p align="center">
  <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.svg" width="600" />
</p>

<p align="center">
  <b>ECE Student • Embedded Systems • Project Builder</b>
</p>



Core strengths:
- Embedded development with Raspberry Pi Pico / ESP series
- GSM/SMS modules (SIM800L) and low-power comms
- Sensor interfacing, keypad/UI and actuator control
- Rapid prototyping: wiring, PCBs, 3D printing
- Problem solving & debugging under contest pressure

---

## Skills & Technologies

- **Languages:** C/C++ (Arduino/ESP-IDF), MicroPython, Python, Bash
- **Microcontrollers & Boards:** Raspberry Pi Pico/Pico W, ESP32, Arduino
- **Communication:** GSM (SIM800L), UART, I2C, SPI
- **Hardware:** MOSFETs (IRFZ44N), buzzers, keypads (4x4), push buttons, sensors (gyros/IMU)
- **Tools:** Git, GitHub, KiCad (or eagle), basic soldering, 3D printing (FDM)
- **Concepts:** Embedded firmware, interrupts, low-power design, UART parsing, prototyping

---

## Selected Projects

### 1. Vehicle Anti-Theft System (Raspberry Pi Pico W + SIM800L)
**Repo:** `vehicle-anti-theft-pico-w` (suggested)  
**Summary:** Real-time anti-theft system using a Pico W as the main controller, SIM800L for SMS/alerts, 4x4 keypad for arming/disarming, buzzer alarm, and MOSFET-driven outputs.  
**Features**
- Arm/disarm via keypad
- Send SMS alerts using SIM800L when alarm triggered
- Local buzzer + LED alarms
- Optional remote control via GSM SMS commands
- Basic tamper detection (e.g., shock sensor or unauthorized door opening)

**Key files (suggested)**
- `main.py` / `main.c` — firmware logic
- `sim800.py` — AT command wrapper for SIM800L
- `wiring_diagram.png` — schematic or hand-drawn wiring
- `README.md` — project documentation & build instructions

**Why it matters:** low-cost, replicable theft-deterrent system — great for learning UART, power management, and robust debugging.

---

### 2. GSM Communication Utilities
**Summary:** Utility modules and examples demonstrating robust serial comms with SIM800L (send SMS, parse incoming SMS, handle network registration and retries).  
**Files**
- `sim800_utils/` — library
- `examples/send_sms.py` — usage demo
- `docs/` — troubleshooting notes (voltage/regulation tips for SIM800L)

---

### 3. Course/Assignment Repos
**Examples**
- `z-transforms-assignment` — worked on z-transform assessment (April/May 2025).
- `probability-graded-assignment-7` — assignments and solutions for probability course.

Include your assignment PDFs, solution code (with comments), and short explanatory writeups to show your academic progress.

---

## Achievements & Activities
- 🏆 **1st Prize** — Debugging competition at IEEE Summit **YESS25** (team members: Abraham Joseph S5EC, Soorya John S3EC) held at NIT Calicut.  
- 🎓 Delivered a short class/intro session about **3D printing** to grade 11–12 students.  
- Regular participant in electronics & embedded system labs and competitions.

---

## How to run / Quick start

1. Clone this repo:
   ```bash
   git clone https://github.com/<your-username>/vehicle-anti-theft-pico-w.git
   cd vehicle-anti-theft-pico-w
