
# Smart Dustbin using Arduino

A contactless smart dustbin prototype that uses an ultrasonic sensor to detect when someone comes near, so the user doesn't have to touch the bin.

## How it works
The HC-SR04 ultrasonic sensor continuously measures distance. The Arduino Uno reads this distance and responds automatically when someone is within range.

## Components used
- Arduino Uno
- HC-SR04 ultrasonic sensor
- Breadboard
- Jumper wires
- USB cable
- Cardboard box (prototype body)

## Pin connections

| Component | Pin | Arduino Uno |
|-----------|-----|-------------|
| HC-SR04   | VCC  | 5V   |
| HC-SR04   | TRIG | D9   |
| HC-SR04   | ECHO | D10  |
| HC-SR04   | GND  | GND  |
| Servo     | Red (VCC)       | 5V  |
| Servo     | Brown (GND)     | GND |
| Servo     | Orange (signal) | D11 |

The sensor and servo share 5V and GND through the breadboard.

## What I learned
- How ultrasonic sensors measure distance
- Wiring circuits on a breadboard
- Writing and debugging Arduino code

## Future improvements
More projects coming soon!

## Author
Dharsine G M| [LinkedIn](https://www.linkedin.com/in/dharsine)
