# Voice-Controlled Surgical Robotic Arm 🤖
**Project for ICT215: Robotics and Embedded Systems**
**Department of Biomedical Engineering, Bells University of Technology**

## 👥 Team Members (Group 2)
1. **Ahamiole Ehizole Excel** (2024/13444)
2. **Akinpelu Diekololaoluwa Salimot** (2024/12922)
3. **Ajala Rhoda Temidayo** (2024/13605)
4. **Akinlade Nazir Olayemi** (2024/13323)
5. **Afumuzor Victoria** (2024/13735)

---

## 📝 Project Abstract
This project implements a **4-DOF (Degree of Freedom) Robotic Arm** designed to assist in surgical environments by automating the retrieval of tools. The system is controlled via voice commands to minimize physical contact and maintain sterility.

**Key features include:**
* **Voice Activation:** Recognizes "SCALPEL" and "FORCEPS" to autonomously retrieve tools.
* **Safety Mechanism:** An integrated force sensor (potentiometer) detects if the grip is too tight (>800 analog value) and automatically releases the tool to prevent damage.
* **Emergency Reset:** A "RESET" command returns the arm to a safe home position.

## 🛠️ Components Used
* **Microcontroller:** Arduino Uno
* **Actuators:** 4x Servo Motors (Base, Shoulder, Elbow, Gripper)
* **Sensors:** Potentiometer (simulating a Force Sensitive Resistor)
* **Software:** Arduino IDE (Logic), Proteus 8 (Simulation)

## 🚀 How to Run the Simulation
1.  **Clone the Repo:** Download this repository to your computer.
2.  **Open Proteus:** Launch Proteus 8 and open the `surgical_arm_circuit.pdsprj` file.
3.  **Load the Firmware:** * Double-click the Arduino board in the schematic.
    * Click the folder icon and select the `surgical_arm_code.ino.hex` file included in this repo.
4.  **Run:** Press the Play button in Proteus.
5.  **Interact:** Open the **Virtual Terminal** and type `SCALPEL` to see the arm move.

---
*© 2026 Group 2 BME. All Rights Reserved.*
