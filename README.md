# Arduino Temperature and Humidity Sensor

![Temperature and Humidity Sensor](https://user-images.githubusercontent.com/102630199/228667051-57312b82-f4bf-4b89-b1c3-980dafaa0428.jpg)

## Project Overview

This project utilizes the Arduino Nano 33 BLE Sense board and the embedded HTS221 sensor to measure and display real-time temperature and humidity values. The primary goal is to familiarize users with reading raw sensor data, utilizing the HTS221 library, and printing sensor values in the Serial Monitor.

## Goals and Objectives

- Learn how to output raw sensor data from the Arduino Nano 33 BLE Sense.
- Utilize the HTS221 library for temperature and humidity sensor functionality.
- Print temperature and humidity values in the Serial Monitor within a specified range.
- Create a customized temperature and humidity monitoring system.

## Hardware and Software Required

- Arduino Nano 33 BLE Sense board
- Micro USB cable for connecting the Arduino board to a desktop machine.
- Arduino IDE for programming the board.

## The HTS221 Sensor

![HTS221 Sensor](https://user-images.githubusercontent.com/102630199/219319823-46def6b0-f064-4bb6-8f1f-dafbdc17d054.png)

Temperature and humidity sensors, such as the HTS221, play a crucial role in converting physical temperature and atmospheric moisture levels into digital data. The HTS221 sensor, with its compact design, communicates via the I2C protocol and has the following specifications:

- Humidity accuracy: ± 3.5% rH, 20 to +80% rH
- Humidity range: 0 to 100%
- Temperature accuracy: ± 0.5 °C, 15 to +40 °C
- Temperature range: -40 to 120°C

Applications of such sensors span across various domains, including air conditioning, wearable devices, smart home automation, industrial automation, and more.

## Procedure

1. Open the Arduino IDE, navigate to the Libraries tab, and find the HTS221 library. Open the ReadSensors example and rename it as Temp_Humidity.
2. Connect the Arduino Nano 33 BLE Sense to the computer and ensure the Web Editor recognizes it.

## Results

After verifying and uploading the sketch to the board, open the Serial Monitor to view the real-time temperature and humidity values. The values will be displayed as shown below:

![Temperature and Humidity Values](https://user-images.githubusercontent.com/102630199/219320108-2a79135a-f24a-4502-8df4-5ca1948e0df4.png)

## References

1. [Arduino Nano 33 BLE Sense - Humidity and Temperature Sensor Tutorial](https://docs.arduino.cc/tutorials/nano-33-ble-sense/humidity-and-temperature-sensor)

Feel free to reach out for any additional information or assistance!
