# Temperature Sensor

The thermistor is a simple temperature sensor. It's a resistor, and it's electrical resistance changes depending on the temperature. The Arduino can measure this resistance. Then it uses the Awesome Shield library to calculate the temperature from the resistance.

***

## Functions

### awesome.temperatureSensor.*reading()*

The `reading()` function gets a temperature reading from the temperature sensor.

*Returns:* It returns a `float`, which is the temperature in degrees Celsius.

## Tips
Ordinarily, the thermistor checks the air temperature. But it can check other temperatures. For example, if you put your finger on the thermistor, it will read your skin temperature.
