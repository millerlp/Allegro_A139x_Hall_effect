# Allegro_A139x_Hall_effect
 Library for Allegro A1395, A1393, A1931 Hall effect sensors
 
 This library is built to be compatible with the EnviroDIY ModularSensors
 library framework. https://github.com/EnviroDIY/ModularSensors
 
 This library allows you to create an Allegro_A139x object that is compatible with 
 the EnviroDIY Modular Sensors framework as a Sensor object and associated Variable
 object. With this, you can obtain the ADC reading from a single A1395 (A1393, A1391) 
 hall effect sensor as a raw 'count' (0-1023 value from the ADC), and ultimately 
 store it alongside other variables that the EnviroDIY ModularSensors library can create.
 
 See the example Arduino file simple_logging_Hall.ino in the examples/ directory. That file is set up so that you can plug an Allegro A139x series sensor into the 3V3 power supply, ground, and analog pin A3. The SLEEP pin on the A139x should also be tied to 3V3 so that the sensor is awake and usable. 
 
