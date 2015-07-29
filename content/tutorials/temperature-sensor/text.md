# Temperature Sensor

The temperature sensor is an electrical resistor. Its resistance changes depending on the temperature. The Arduino can measure the resistance. Then it uses the Awesome Shield library to calculate the temperature.

***

## Functions

### awesome.temperatureSensor.*reading()*

The `reading()` function gets a temperature reading using the temperature sensor.

*Returns:* It returns a `float`, which is the temperature in degrees Celsius.

## Tips
Normally the thermistor checks the air temperature. But it can check other temperatures. If you put your finger on the thermistor it will read your skin temperature.
