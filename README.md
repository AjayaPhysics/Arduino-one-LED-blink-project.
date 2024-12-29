# Arduino-one-LED-blink-project.
# Arduino Single LED Blink Project

## Overview
This project demonstrates how to make an LED blink using an Arduino. It is a simple and beginner-friendly project to understand the basics of Arduino programming and circuit connections.

---

## Components Needed
| Component            | Quantity | Description                                  |
|----------------------|----------|----------------------------------------------|
| Arduino Uno          | 1        | Microcontroller to control the LED blinking |
| LED                  | 1        | For blinking (any colour)                   |
| 220-ohm Resistor     | 1        | To limit the current to the LED             |
| Breadboard (optional)| 1        | For easier wiring                           |
| Jumper Wires         | 2        | For making connections                      |

---

## Circuit Connections

| Arduino Pin        | Component               | Connection                               |
|---------------------|-------------------------|------------------------------------------|
| Pin 13 (Digital)   | Resistor (220 ohms)     | Connected to the anode (+) of the LED    |
| GND                | LED cathode (-)        | Direct connection or via breadboard      |

### **Circuit Diagram**
Pin 13 (Digital) -> Resistor (220 ohms) -> LED Anode (+)
GND             -> LED Cathode (-)

Here's how you can connect and code for an Arduino single  LED blink project.
Components Needed:
Arduino Uno (or any compatible Arduino board)
LED (1 piece)
220-ohm resistor
Breadboard (optional)
Jumper wires
Circuit Connection:
LED Connections:
Anode (+) (long leg of the LED) connects to pin 13 of the Arduino.
Cathode (-) (short leg of the LED) connects to the ground (GND) via a 220-ohm resistor.
(You can also use a breadboard for easier connections.)
Pin diagram:

Pin 13 (Digital) -> Resistor (220 ohms) -> LED anode (+)
Ground (GND) -> LED cathode (-)
