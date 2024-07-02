Name        : C.KUMARI SELVI 
Company     : CODTECH IT SOLUTIONS
ID          : CT08DS2045
Domain      : Internet Of Things 
Duration    : 10th June-10th July 2024
OVERVIEW OF THE PROJECT:
PROJECT : WEATHER MONITORING SYSTEM 
![Screenshot 2024-07-02 184128](https://github.com/KUMARISELVI/CODTECH-Task-1/assets/145418381/bc3540c9-26a5-4b20-a7f3-b916954ae028)

OBJECTIVE :
The objective of this project is to collect data on temperature, humidity, and atmospheric pressure. The aim is to monitor real time data visualization, data update, and gives alerts and notifications.
KEY ACTIVITIES:
Real-Time Data Visualization:
Dashboard Creation: Design a web-based dashboard or mobile app using frameworks like React, Angular, or Flutter.
Real-Time Updates: Implement real-time data updates on the dashboard using WebSockets or other real-time communication protocols.
Data Visualization: Use libraries like Chart.js, D3.js, or Google Charts to visualize the temperature, humidity, and pressure data.
Alerts and Notifications:
Threshold Alerts: Implement functionality to send alerts or notifications if the readings cross predefined thresholds.
Mobile Notifications: Use services like Firebase Cloud Messaging (FCM) or Push Notifications to send real-time alerts to mobile devices.
TECHNOLOGIES USED :
Software Components
Arduino IDE:The development environment used to write and upload code to the ESP8266.
Blynk:
Blynk Library: Used for connecting the ESP8266 to the Blynk cloud platform, enabling remote monitoring and control.
Blynk App: A mobile application that provides a user-friendly interface to visualize data and interact with the weather station.
LiquidCrystal_I2C Library: A library to interface with the LCD display over I2C.
DHT Library: A library to read data from the DHT11 sensor.
ESP8266WiFi Library: A library to handle Wi-Fi connectivity on the ESP8266.
BlynkSimpleEsp8266 Library: A specific implementation of the Blynk library for the ESP8266.
Key Functionalities:
Wi-Fi Connectivity: The ESP8266 connects to a specified Wi-Fi network using the credentials provided.
Data Reading and Mapping: The code reads temperature and humidity from the DHT11 sensor.
An analog sensor value (possibly rainfall) is read and mapped to a specific range.
Data Transmission: The sensor data is sent to the Blynk cloud platform using virtual pins.
Local Display: The LCD displays real-time temperature, humidity, and other sensor data.
LED Widget Control: The code controls an LED widget in the Blynk app based on a digital input, indicating high or low light levels.

