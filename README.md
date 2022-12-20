# EmbeddedFinalProject
This is the code the smart home system written for the Smart Home Sensor designed for Adam Kinsley, Brian Dalmar, and Nick Saccomanno's
Intro to Embedded Systems Final Project. The design is intended to read two ADC values and one I2C value, and upload them to ThingSpeak.
There are five files in this repository.

Three of the five files in this repository, LightSensor, MotionSensor, and MotionSensor, are for reading the value from each individual sensor used.

AllSensors compiles these three files and retrieves data from each sensor.

SerialCommunication relays the sensor data to a ThingSpeak channel.
