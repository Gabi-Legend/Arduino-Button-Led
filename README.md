# Arduino Button Controlled LED

A simple Arduino project demonstrating how to control an LED with a push button using the `INPUT_PULLUP` feature.

## 📌 Description
Pressing the button will turn the LED on.  
Releasing the button will turn the LED off.  
This project introduces basic input reading (`digitalRead`) and conditional logic in Arduino.

## 🛠 Hardware Required
- Arduino Uno / Nano / Mega
- LED (optional: can use onboard LED on pin 13)
- 220Ω resistor (if using external LED)
- Push button
- Breadboard
- Jumper wires

## 🔌 Circuit Connections
**Using INPUT_PULLUP (no external resistor needed):**

- Button one pin → Arduino pin 2  
- Button other pin → GND  
- LED anode (+) → pin 13 (or external pin)  
- LED cathode (–) → GND through 220Ω resistor (if external)
