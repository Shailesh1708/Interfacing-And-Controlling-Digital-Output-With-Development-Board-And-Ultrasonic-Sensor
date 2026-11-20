# NAME: Shailesh S S
# REG NO: 212225040397
# EXP NO: 3


# AIM

To Interface And Control Digital Output With Development Board And Ultrasonic Sensor

# COMPONENTS REQUIRED:

1.      Ultrasonic Sensor

2.      1 KΩ resistor

3.      Arduino Uno

4.      USB Interfacing cable


# Procedure:
Open Tinkercad → Circuits and create a new circuit.

Place an Arduino Uno R3 in the workspace.

Add a breadboard.

Add an HC-SR04 ultrasonic sensor.

Connect the VCC pin of the sensor to Arduino 5V.

Connect the GND pin to Arduino GND.

Connect TRIG to Arduino digital pin 9.

Connect ECHO to Arduino digital pin 10.

Add an LED to the breadboard.

Connect the LED anode to digital pin 7 through a 220 Ω resistor.

Connect the LED cathode to GND.


# Algorithm – Ultrasonic Sensor with Digital Output

Start

Connect the HC-SR04 ultrasonic sensor to the Arduino.

Connect the LED to digital pin 7.

Set TRIG as an output pin.

Set ECHO as an input pin.

Send a short pulse through the TRIG pin.

Receive the reflected signal through the ECHO pin.

Calculate the distance of the object using the echo time.

Check whether the distance is less than the specified limit (for example, 20 cm).

If the distance is less than 20 cm, turn ON the LED.

Otherwise, turn OFF the LED.

Repeat steps 6–11 continuously.

Stop.
# GitHub Repostary
<img width="1584" height="912" alt="Screenshot 2026-08-17 104958" src="https://github.com/user-attachments/assets/a374c50e-9b14-4b7e-ba8a-cf3d949806f2" />
<img width="962" height="726" alt="Screenshot 2026-08-17 105604" src="https://github.com/user-attachments/assets/a0c28ef5-37c1-4aef-9125-646b44d9a6eb" />

# Result
The HC-SR04 ultrasonic sensor was successfully interfaced with the Arduino Uno in Tinkercad. The sensor detected the distance of an object, and the LED was controlled based on the detected distance.

When the object was less than 20 cm, the LED turned ON. When the object was more than 20 cm, the LED turned OFF.
