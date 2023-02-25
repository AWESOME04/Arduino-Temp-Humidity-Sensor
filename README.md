# Arduino-Temp-Humidity-Sensor

This project aims to use the Arduino Nano 33 BLE Sense board to measure and print out the humidity and temperature values of your surroundings in real time. This is made possible by the embedded HTS221 sensor. 

Goals and objectives

•	Learn how to output raw sensor data from the Arduino Nano 33 BLE Sense.
•	Use the HTS221 library.
•	Print temperature and humidity values in the Serial Monitor when they are within a certain range. 
•	Create your own temperature and humidity monitor.

Hardware and Software Required

•	An Arduino Nano 33 BLE Sense board
•	A Micro USB cable to connect the Arduino board to your desktop machine.
•	To program the board, I used the  Arduino IDE.

The HTS221 Sensor

![image](https://user-images.githubusercontent.com/102630199/219319823-46def6b0-f064-4bb6-8f1f-dafbdc17d054.png)

  
Temperature sensors are components that convert physical temperature into digital data. Likewise, humidity sensors are able to measure atmospheric moisture levels and translate that into electrical signal. As such, temperature and humidity sensors are essential for environmental monitoring especially in and around sensitive electronic equipment.
The HTS221 is an ultra-compact sensor for relative humidity and temperature. We will use the I2C protocol to communicate with the sensor and get data from it. The sensor's range of different values are the following:

•	Humidity accuracy: ± 3.5% rH, 20 to +80% rH
•	Humidity range: 0 to 100 %
•	Temperature accuracy: ± 0.5 °C,15 to +40 °C
•	Temperature range: -40 to 120°C

These types of sensors are used more than you would think and are found in various everyday objects! 
Some of the useful ways they are used are seen in the following applications:

•	Air conditioning, heating and ventilation.
•	Air humidifiers.
•	Refrigerators.
•	Wearable devices.
•	Smart home automation.
•	Industrial automation.
•	Respiratory equipment.
•	Asset and goods tracking.

Procedure

•	Click on the Libraries tab, search for the HTS221 library, then in Examples, open the ReadSensors example. Once the sketch is open, rename it as Temp_Humidity.

•	Now, connect the Arduino Nano 33 BLE Sense to the computer to check that the Web Editor recognizes it,


Results

After you have successfully verified and uploaded the sketch to the board, open the Serial Monitor from the menu on the left. You will now see the new values printed as shown below:
![image](https://user-images.githubusercontent.com/102630199/219320108-2a79135a-f24a-4502-8df4-5ca1948e0df4.png)


REFERENCES

[1] https://docs.arduino.cc/tutorials/nano-33-ble-sense/humidity-and-temperature-sensor
