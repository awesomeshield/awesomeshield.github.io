# Thermistor

The thermistor is a simple temperature sensor. It's really a resistor, and it's resistance changes depending on the temperature. The Arduino can sense this resistance, and then it uses the Awesome Shield library to calculate the temperature.

***

## Functions

### awesome.temperatureSensor.*check()*

The `check()` function gets a temperature reading from.

#### Inputs
It doesn't take any inputs.

#### Returns
It returns a `float`, which is the temperature in degrees Celsius.

#### Tips
Ordinarily, the thermistor checks the air temperature. But it can check other temperatures. For example, if you put your finger on the thermistor, it will read your skin temperature.

#### Example
<iframe style="height: 510px; width: 100%; margin: 10px 0 10px;" allowTransparency="true" src="https://codebender.cc/embed/sketch:90338" frameborder="0"></iframe>
