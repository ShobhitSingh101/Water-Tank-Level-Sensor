# Water-Tank-Level-Sensor

In this project, We maked an Arduino based Water Tank Level Controller System.
This project is based on Arduino and ultrasonic sensors.Ultrasonic sensors are working on the basis of ECHO.
We need to calculate the time of both sound waves travelling time. When they strike obstacles and return to the sensor. After calculation, we have the distance in the result. We used this concept to control the water tank. The water pump is automatically turned on when the water level is low and turned off when the level is high.
So that the module can measure the water surface and collect the data from the tank. When the water level is low about 30 cm, the Arduino turns on the pump and the LCD display shows “LOW WATER LEVEL” and the Led starts glowing.
When the space in the tank is about 12cm the pump will turn off and the LCD display shows “TANK IS FULL“. The buzzer starts beeping at this time and the LED turns off at this moment.
