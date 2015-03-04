# Color LED

LEDs are very efficient lights. LED stands for "Light Emitting Diode". The Awesome Shield has a full color LED. It's really three LEDs stuck together. One is red, one is green, and one is blue. By blending these three colors together at different strengths, you can create all the colors of the rainbow.

***

## Functions

### awesome.colorLED.*turnOn()*

The `turnOn()` function turns the color LED on.

#### Inputs
It needs an input. It can take two type of inputs.

##### Color Names
You can give it a single input, with certain color names written in capitals. For example, `awesome.colorLED.turnOn(GREEN)` will light the LED up green. The colors you can name are: `WHITE`, `RED`, `GREEN`, `BLUE`, `YELLOW`, `PURPLE`, and `CYAN`.

##### Color Strengths
You can give it three inputs, which will be set as the power of the red, green and blue elements inside the color LED. The order of the color strengths is red, green, then blue. For example, `awesome.colorLED.turnOn(100, 0 , 255)` sets the red element to 100, the green to 0, and the blue to 255. These number inputs are `int`s, and the maximum value is 255.

#### Returns
It doesn't return any variables.

#### Tips

By using variables that change over time for the color strength inputs, you can make neat projects that fade from one color to the next.

***

### awesome.colorLED.*turnOff()* and awesome.greenLED.*turnOff()*

The `turnOff()` function turns the LED off. This turns off each of the three elements inside the color LED.

#### Inputs
It doesn't take any inputs.

#### Returns
It doesn't return any variables.

#### Tips
Don't forget to turn your LEDs off when you're done with them. Otherwise you won't notice when you turn them on a second time.

#### Example
<iframe style="height: 510px; width: 100%; margin: 10px 0 10px;" allowTransparency="true" src="https://codebender.cc/embed/sketch:90338" frameborder="0"></iframe>
