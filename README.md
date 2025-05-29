# A-smart-parking-system
Smart Parking Management System - Park Ease
 Project Overview
 This project, "Park Ease", is a Smart Parking Management System designed to address urban 
parking challenges using Arduino microcontrollers, IR sensors, and LCD displays with I2C 
communication. The system provides real-time monitoring and management of parking space 
occupancy.
 Components- Arduino Uno R3- IR sensors- Servo motor- LCD display with I2C interface- Breadboard and jumper wires- Power supply
 Demonstration Instructions
 Setting Up the Hardware
 1. Connect the IR Sensors:
    - Attach the IR sensors to the breadboard.
 ir_car1 to pin 5
    - Connect each sensor to the Arduino pins as follows:
 ir_car2 to pin 6
 ir_car3 to pin 7
 ir_car4 to pin 8
 ir_enter to pin 2
 ir_back to pin 4
 2. Servo Motor:- Attach the servo motor to pin 3 of the Arduino.- Ensure it is mounted properly to control the gate mechanism.
 3. LCD Display:- Connect the LCD display with I2C interface to the Arduino.
    - Ensure the I2C address is set to 0x27 and the dimensions are 20x4.
 4. Power Supply:
    - Connect the Arduino and other components to a suitable power source.
 Programming the Arduino
 1. Install the Arduino IDE:
    - Download and install the [Arduino IDE](https://www.arduino.cc/en/software) if not already 
installed.
 2. Upload the Sketch:- Open the sketch file and write the code (SmartParkingSystem.ino).- Connect the Arduino to your computer via USB.
    - Select the correct board and port from the Tools menu.
    - Upload the sketch to the Arduino.
 3. Libraries used:
    -Servo.h: For controlling the servo motor.
    -Wire.h: For I2C communication.
    -LiquidCrystal_I2C.h: For interfacing the LCD display with I2C communication
 Video
 1. Open Arduino IDE 
2. Write the code
 3. Establish connection to PC
  4.Run the program
 5.Demonstration of Working
 Conclusion
 This README provides a step-by-step guide to demonstrate the "Park Ease" Smart Parking 
Management System. By following these instructions, you can effectively showcase the 
functionality and benefits of the system using the prototype you built.
