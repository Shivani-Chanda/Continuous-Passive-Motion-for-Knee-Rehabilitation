# Continuous-Passive-Motion-for-Knee-Rehabilitation

## Introduction
CPM therapy helps joints move without you having to do anything. It's often used after surgery, like knee replacements, to keep your joints flexible and prevent stiffness. The machine gently moves your joint back and forth, making it easier for you to recover.
## Controls of CPM Machine
The CPM machine facilitates foot movement by converting the DC motor's rotation into translational motion through a rack and pinion mechanism. Precision control is crucial, especially in critical and sensitive scenarios, where both position and speed must be managed meticulously. For this purpose, a **PID controller** was implemented on an Arduino Mega. The controller takes position data from an encoder as input, calculates the error relative to the target position, and generates a speed output.
1. Arduino Mega 2560 
2. DC motor with encoder
3. l298n motor driver
4. 12V Battery
### Hardware Connections
- The Arduino Mega and motor driver are powered using a 12V battery.
- The encoder is powered directly from the Arduino, and its feedback pins are connected to the Arduino.
- The motor is connected to the motor driver, and the motor driver receives its input signal from the Arduino.


