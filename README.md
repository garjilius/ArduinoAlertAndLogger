# ArduinoAlertAndLogger
IoT Logging device.

This logging device consists on an Arduino Uno Wifi Rev 2, connected to the internet.
Arduino will log ambient data such as temperature and humidity to a Google Sheet. 
If connection fails, data will be logged to a SD card. 
A control panel, hosted by Arduino, allowes users to set parameteres such as the logging interval and date/time. It will also allow to handle phisical components on the device (as an example, turning on or off the display.).

Hardware: 
Arduino Uno WiFi rev. 2
DHT22 - Humidity & Temperature Sensor
LCD 20x4 i2c Display
Real Time Clock module RTC 1302
IR Motion Sensor HC-SR501
SPI microSD Card Reader 
Led
Resistors
Breadboard 

Full documentation is available (italian only at the moment) at the following url:
https://docs.google.com/document/d/1mT9lr5-akYNQww7m9ZU5IvrvnQj9yaphkOifaIx3o74/edit?usp=sharing

An english version for the documentation might be added in the future.

Feel free to use all parts of the code you might like!