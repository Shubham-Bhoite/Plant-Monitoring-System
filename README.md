# Plant Monitoring System Using IoT
## Overview
- The aim of this project is to automate agriculture using IoT.
- In this project we used different type of sensors for collecting data from Agriculture.
- I Used Blynk Cloud for accessing sensors from anywhere from world.
- We can autom automate Water pump.

## How It Works
- I Used Soil Moisture Sensor, DHT11 Sensor(Tempereture And Humidity) for collecting Data.
- After collecting data from sensor it will send to Blynk Cloud
- Blynk can control Hardware devices from remotely, it can display sensor data, it can store data, vizualize it and do many other cool things.

- Soil Moisture Sensor collects moiture presents in soil i.e how much quantity of water present in the water.
- DHT11 Sensor is collecting Tempereture and Humidity present in the air surround the agriculture.
- Blynk Cloud will show all collected data in the form of Graphs and Charts so we can easily monitor our plants from anywhere.
### Working Of Blynk
<p align="center">             
<img src="Images/BlynkWorking.png?raw=true" alt="How Blynk Works "></p>

## Hardware and Softwares We Need 
1) NodeMCU ESP8266
2) Soil Moisture Sensor
3) DHT11 Sensor
4) 5v Relay Module
5) BreadBoard
6) Jumper Wires
7) Water Pump 12v
8) 12v Battery
9) Blynk Cloud Account
10) Arduino IDE

## Circuit Diagram
<p align="center">             
<img src="Images/CircuitDiagram.jpg?raw=true" alt="Circuit Diagram For Plant Monitoring System"></p>

## How To Configure System
1. Connect The Hardwares According To Circuit Diagram.
2. Download Code From This Repository.
3. Download Required Libraries Into Arduino IDE
4. Connect NodeMCU to PC & Upload The Code into it.
5. Open Blynk Web App Or Mobile App and Create New Device.
6. Create Template and Add DataStreams:
Pin V2,V5,V5 & D0 for Soil Moisture,Humidity,Tempereture and Motor Pump Respectively.
7. Create Web/Mobile Dashboard Using DataStreams Like Charts, Graphs,etc.