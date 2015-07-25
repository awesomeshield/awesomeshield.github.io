# Button

The button is a simple switch. When the button is pressed down, it makes an electrical connection. The Arduino can detect this electrical connection, and figures out whether or not the button is being down.

***

## Functions

#### awesome.button.*isDown()*

The `isDown()` function checks if the button is currently down (is being pressed) or not (is not being pressed).

Inputs: It doesn't take any inputs.

Returns: It returns a `bool`. This bool is `true` if the button is down and `false` if it is up.

#### awesome.button.*isUp()*

The `isUp()` function works a lot like the `isDown()` function, but tells you when the button is up.

Inputs: It doesn't take any inputs.

Returns: It returns a `bool`. This bool is `true` if the button is up and `false` if it is down.

#### Tips
The button is handy for an easy input device. It works really nicely with if().
