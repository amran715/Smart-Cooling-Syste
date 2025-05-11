 Arduino and LM35

## Overview
This project demonstrates a smart cooling system using an Arduino, an LM35 temperature sensor, and a fan. The system automatically turns on the fan when the temperature exceeds a specified threshold (30°C in this case).

## Components
- Arduino UNO
- LM35 temperature sensor
- 5V fan or relay module
- Jumper wires
- Breadboard

## Instructions
1. Connect the LM35 sensor to the A0 pin of the Arduino.
2. Connect the fan or relay module to pin 9.
3. Upload the provided Arduino code to your Arduino.
4. Open the Serial Monitor to view the temperature readings.
5. When the temperature exceeds 30°C, the fan will turn on automatically.

## Code Explanation
- The LM35 reads the temperature and sends an analog signal to the Arduino.
- The Arduino converts this analog signal to a temperature value and prints it on the Serial Monitor.
- If the temperature exceeds 30°C, the fan is turned on using a relay.

## Additional Features
- You can adjust the temperature threshold in the code to suit your needs.
