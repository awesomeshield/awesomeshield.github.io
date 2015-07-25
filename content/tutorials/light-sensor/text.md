# Light Sensor

The photocell is a simple light sensor. It's really a resistor, and it's resistance changes depending on how much light is shining on it. The Arduino can sense this resistance, and then it uses the Awesome Shield library to calculate the light level.

***

## Functions

#### awesome.lightSensor.*reading()*

The `reading()` function gets a light reading from the light sensor.

*Returns:*
It returns an `int`, which is the light level in lux.

## Tips
The light level changes depending on how bright the room is, and also how covered up the light sensor is. You can use the light sensor to detect and simple gesture: a hand passing over it.
