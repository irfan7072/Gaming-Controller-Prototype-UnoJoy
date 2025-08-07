# 🎮 Gaming Controller – Prototype (UnoJoy Version)

This is the *initial prototype* of our custom game controller built using *Arduino Uno* and the *UnoJoy library*, allowing it to function as a standard USB gamepad.

## 🚀 Features
- Dual joystick support
- 10+ tactile push buttons
- Emulates a USB game controller on Windows
- Breadboard-based prototype

## 🔧 Tools & Technologies
- Arduino Uno
- UnoJoy firmware + library
- Arduino IDE
- Atmel FLIP
- Joystick & push button modules

## 🛠 Setup Instructions
1. Clone this repo and open the .ino file in Arduino IDE.
2. Upload the sketch to the Arduino Uno.
3. Flash the UnoJoy firmware using *Atmel FLIP* to turn the Uno into a USB HID gamepad.
4. Plug into a PC → Go to *Control Panel > Devices > Game Controllers* to test functionality.

## 💡 Notes
- Prototype is wired on a breadboard.
- UnoJoy enables the Uno to emulate an Xbox-style controller.
- No driver installation needed (recognized by Windows).

## 📂 Other Versions
- [HID Version (Keyboard and Mouse Compatible) ](https://github.com/irfan7072/Gaming-Controller-HID)
- [Final LeoJoy Version](https://github.com/irfan7072/Gaming-Controller-Final-LeoJoy)
