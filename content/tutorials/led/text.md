# LED

LEDs are efficient lights. LED stands for "Light Emitting Diode". The Awesome Shield has a full color LED. It's really three LEDs stuck together. A red one, a green on, and a blue one. By blending these three colors together at different strengths, you can create all the colors of the rainbow. Nifty!

***

## Functions

#### awesome.LED.*turnOn()*

The `turnOn()` function turns the color LED on.

*Inputs:* This function needs an input. It can take two types, a color name, or a set of three color strengths.

###### Color Names
You can give it a single input, with certain color names written in capitals. For example, `awesome.colorLED.turnOn(GREEN)` will light the LED up green. The colors you can name are: `WHITE`, `RED`, `GREEN`, `BLUE`, `YELLOW`, `PURPLE`, and `CYAN`.

###### Color Strengths
You can give it three inputs, which will be set as the power of the red, green and blue elements inside the color LED. The order of the color strengths is: red, green, then blue. For example, `awesome.colorLED.turnOn(100, 0 , 255)` sets the red element to 100, the green to 0, and the blue to 255. These number inputs should be `int`s between 0 and 255.

#### awesome.LED.*turnOff()*

The `turnOff()` function turns the LED off. This turns off each of the three elements inside the color LED.

#### awesome.LED.*flash()*

The `flash()` turns the LED on, waits for a period of time, and then turns the LED off again.

*Inputs:* the `flash()` function can take two different sets of inputs:

###### Color Names
The `flash` function's first input is a number of milliseconds that it should turn the light on for. This input, `millis` is an int. Next, it needs to know what color to set the LED to. Just like the `awesome.LED.turnOn()` function, it can take a color name as an input, like `RED` or `YELLOW`. So for example, `awesome.LED.flash(1000, RED);` would flash the LED red for one second.

###### Color Strengths
The `flash` function's first input is the number of milliseconds that it should turn the light on for. This input, `millis`, is an int. Next, it needs to know what color to set the LED to. Just like the `awesome.LED.turnOn()` function, it can take a set of three `int`s that tell it what power to set the red, green, and blue elements to. For example `awesome.LED.flash(500, 255, 0, 0);` would flash the LED for 500 milliseconds, or a half a second, with red on full power, and green and blue both turned off.

#### awesome.LED.*isOn()*

The `isOn()` function checks to see if the LED is currently turned on.

*Returns:* it returns a `bool`, which is true if the LED is currently turned on, and `false` if it is currently turned off.

#### awesome.LED.*isOff()*

The `isOff()` function checks to see if the LED is currently turned off.

*Returns:* it returns a `bool`, which is `true` if the LED is currently turned off, and `false` if it is currently turned on.
