# Smart Irrigation System using Arduino

This project implements an automatic irrigation system using an Arduino UNO, a soil moisture sensor (FC-28), and a relay-controlled motor pump. The system detects the soil's moisture level and activates the water pump only when the soil is dry.

## Components Used

- Arduino UNO
- FC-28 Soil Moisture Sensor
- 5V Relay Module (1 Channel)
- 9V Battery with Connector
- DC Motor (simulating a water pump)
- Jumper Wires
- Breadboard


## Working Principle

- The soil moisture sensor detects the moisture content in the soil.
- The digital output of the sensor is connected to the Arduino input pin.
- Based on the moisture level, the Arduino controls the relay connected to a DC motor (representing the water pump).
- If the soil is dry (sensor output LOW), the relay is turned ON and water is supplied.
- If the soil is wet (sensor output HIGH), the relay is turned OFF and water supply stops.


