# Toggle Switch

The toggle switch is a simple switch. When the switch is at the end labelled "on" on the Awesome Shield, it makes an electrical connection. The Arduino can detect this electrical connection, and figures out of the switch is set to "on" or "off".

***

## Functions

### awesome.toggle.*check()*

The `check()` function checks if the switch is set to "on" or "off".

#### Inputs
It doesn't take any inputs.

#### Returns
It returns an `bool`. This bool is `true` if the switch is set to "on" and `false` if it's set to "off".

#### Tips
The switch is handy when you want to have two different modes that your program runs in. For example, one mode could silence the buzzer. It works really nicely with if().

#### Example
<iframe style="height: 510px; width: 100%; margin: 10px 0 10px;" allowTransparency="true" src="https://codebender.cc/embed/sketch:90348" frameborder="0"></iframe>
