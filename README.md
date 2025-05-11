🚪 Arduino Automated Gate System Demo
🛠️ Components Used
Ultrasonic Sensor (HC-SR04)

Servo Motor (e.g., SG90)

Red LED (Anode at Pin 4, Cathode at Pin 8)

Blue LED (Anode at Pin 5, Cathode at Pin 7)

Active Buzzer (Pin 12)

Arduino Uno or similar

Jumper wires, Breadboard, Resistors (for LEDs)

🎯 Project Purpose
This project demonstrates a contactless, sensor-based automated gate system with visual (LED) and audio (buzzer) indicators.

🎬 How It Works (Demo Walkthrough)
1. Startup
Red LED turns ON (indicating the gate is closed).

Blue LED and buzzer remain OFF.

2. Object Detected (Within 50 cm)
The ultrasonic sensor detects an object approaching.

The servo motor rotates to 90°, opening the gate.

The red LED turns OFF, and the blue LED turns ON.

A gentle buzzer beeps periodically (every 500ms, 50ms ON) to indicate an open gate.

3. Object Leaves
Once the object is no longer detected and 5 seconds have passed:

The servo motor rotates back to 0°, closing the gate.

The red LED turns ON, and blue LED + buzzer turn OFF.

