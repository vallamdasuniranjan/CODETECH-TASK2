**NAME     :** VALLAMDASU NIRANJAN  
**COMPANY  :** CODTECH IT SOLUTIONS  
**ID       :** CT6ES607  
**DOMAIN   :** EMBEDDED SYSTEMS  
**DURATION :** June - Aug 2024  
**MENTOR   :** -  

## Project Overview: Temperature and Humidity Monitoring System Using DHT11 Sensor and OLED Display

## Objective:
The objective of this project is to create a temperature and humidity monitoring system using a DHT11 sensor to measure environmental conditions and an OLED display to show the readings. This project helps in understanding sensor integration, data visualization, and basic microcontroller interfacing using an Arduino.

## Components Required:
1. Arduino Board (e.g., Arduino Uno)
2. DHT11 or DHT22 Sensor (for temperature and humidity measurements)
3. OLED Display (e.g., 128x64 I2C OLED display)
4. Breadboard and Jumper Wires
5. Resistor (10k ohms for DHT22 if needed)

## Key Concepts:
**1. Arduino Board:** A microcontroller platform used for building digital devices.  
**2. DHT Sensor:** Measures temperature and humidity. DHT11 is basic and less accurate, while DHT22 offers better precision.  
**3. OLED Display:** A screen that displays information using organic light-emitting diodes.

## Steps to Implement the Project:

### Setting Up the Hardware:

#### DHT Sensor Connections:
1. Connect the VCC pin to 5V on the Arduino.
2. Connect the GND pin to GND on the Arduino.
3. Connect the DATA pin to a digital pin on the Arduino (e.g., pin 2).

#### OLED Display Connections:
1. Connect VCC to 3.3V or 5V on the Arduino (depending on the OLED module specifications).
2. Connect GND to GND on the Arduino.
3. Connect SCL to the SCL pin on the Arduino.
4. Connect SDA to the SDA pin on the Arduino.
![ARDUINO DHT11](https://github.com/vallamdasuniranjan/CODETECH-TASK2/assets/174948070/f9487030-e01a-40d7-a391-42f4d934cca3)
### Installing Required Libraries:
1. Install the DHT library and Adafruit GFX and SSD1306 libraries for the OLED display from the Arduino Library Manager.

### Writing the Arduino Sketch:
Open the Arduino IDE and write the following code which is uploaded in the (Arduino-DHT11-OLED).

### Uploading the Sketch:
1. Connect the Arduino to your computer via USB.
2. Select the appropriate board and port in the Arduino IDE.
3. Click "Upload" to compile and upload the sketch to the Arduino.

## Observing the Output:
Once the sketch is uploaded, the OLED display should show the temperature and humidity readings from the DHT sensor.
![IMG20240707182026](https://github.com/vallamdasuniranjan/CODETECH-TASK2/assets/174948070/4f987171-1998-482c-a381-b8ae9649071a)

## Learning Outcomes:
**1. Sensor Integration:** Learn how to connect and read data from the DHT sensor.  
**2. Display Handling:** Understand how to interface with an OLED display and visualize data.  
**3. Arduino Programming:** Gain experience in writing and uploading Arduino sketches.  
**4. Data Monitoring:** Develop a basic system for real-time environmental monitoring.

By completing this project, you will gain valuable experience in working with sensors, displays, and microcontroller programming, which are foundational skills for more advanced IoT and embedded systems projects.
