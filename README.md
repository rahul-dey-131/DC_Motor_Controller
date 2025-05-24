# ⚙️ DC Motor Speed Controller using PID – MATLAB App

This project is a graphical MATLAB app that simulates and controls the speed of a DC motor using a PID controller. It was built using Simulink, Simscape, and App Designer. It’s designed for educational use and engineering prototyping, allowing full interactivity and customization.

> 🎯 Includes the **editable source files** (`.slx`, `.mlapp`) and a ready-to-use `.mlappinstaller` for quick setup.

---

## 📌 Features

* 🎛️ **User-friendly GUI** developed in MATLAB App Designer
* ⚙️ **Auto-tuned PID** using MATLAB’s PID tuner
* 📊 Real-time visualization of:

  * Speed (RPM) vs Time
  * Armature Voltage vs Time
  * Armature Current vs Time
* 🧮 Custom inputs:

  * Ra – Armature Resistance
  * La – Armature Inductance
  * K – Motor Constant
  * J – Moment of Inertia
  * B – Friction Coefficient
  * Desired RPM
  * Simulation Time

---

## 📥 Installation

### Requirements

* **MATLAB R2023b** or later
* Toolboxes:

  * Simulink
  * Simscape
  * Simscape Electrical
  * Control System Toolbox
  * MATLAB App Designer

### Using the Installer

1. Download `DC_Motor_Controller.mlappinstaller` from this repo.
2. Double-click it or run it in MATLAB:

   ```matlab
   matlab.apputil.install('DC_Motor_Controller.mlappinstaller')
   ```
3. Open from the **Apps** tab in MATLAB.

---

## 👨‍💻 For Developers

You're welcome to **modify and extend** the project:

* `Controller_Model.slx`: Simulink model of the DC motor and PID loop
* `New_Controller_App.mlapp`: Full GUI source code (editable in App Designer)
* Easily tweak components, improve visual design, or integrate other controllers!

---

## 🧠 Key Concepts

* Practical PID control implementation
* Parameterized Simulink simulation via `SimulationInput`
* Avoids base workspace dependencies (compilation-friendly)
* MATLAB GUI design & deployment

---

## 📁 Files in This Repo

| File Name                            | Description                                    |
| ------------------------------------ | ---------------------------------------------- |
| `Controller_Model.slx`               | Simulink model of the motor and PID controller |
| `New_Controller_App.mlapp`           | GUI source file (editable in App Designer)     |
| `DC_Motor_Controller.mlappinstaller` | Installer for plug-and-play usage              |
| `Logo.png`                           | App logo for GUI                               |
| `Splash Screen.png`                  | Startup splash screen                          |
| `README.md`                          | This documentation                             |

---

## 🖼️ Preview

![Demo](https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExcDc1Zmprbmlxbjhzb2FhNjF4bWQ5YWpiczRzYWowdDF0YXZ1ODBubyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/W74DBHtklceEIJYMr4/giphy.gif)
---

## 🙋 Contact

Developed by **Rahul Dey**

🔗 [LinkedIn](https://www.linkedin.com/in/rahul-dey-240e01/)

📧 [rahuldeybl156@gmail.com](mailto:rahuldeybl156@gmail.com)

---

Let me know if you’d like me to bundle this into a ready-to-use `README.md` file or create image thumbnails for GitHub display.
