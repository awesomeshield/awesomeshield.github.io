# Button

The button is a simple switch. When the button is pressed down, it makes an electrical connection. The Arduino can detect this electrical connection, and figures out whether or not the button is being pressed.

***

## Functions

#### awesome.button.*check()*

The `check()` function checks if the button is being pressed (ie. is down) or is being left alone (ie. is up).

#### Inputs
It doesn't take any inputs.

#### Returns
It returns an `bool`. This bool is `true` if the button is pressed (down) and `false` if it's not pressed (up).

#### Tips
The button is handy for an easy input device. It works really nicely with if().

#### Example
<iframe style="height: 510px; width: 100%; margin: 10px 0 10px;" allowTransparency="true" src="https://codebender.cc/embed/sketch:89603" frameborder="0"></iframe>
