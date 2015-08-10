# Light Sensor

The light sensor is a photocell. Its resistance changes depending on how much light is shining on it. The Arduino can measure this resistance.

***

## Functions

#### awesome.lightSensor.*reading()*

The `reading()` function gets a light reading from the light sensor.

*Returns:* It returns an `int`, which is the light level between 0-1023

## Tips
The sensor reading changes if you cover it with your hand, or shine a light on it. You can use the light sensor to detect and simple gesture: a hand passing over it.
