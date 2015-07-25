# Toggle Switch

The toggle switch is a simple switch. When the switch is at the end labelled "on", it makes an electrical connection. The Arduino can detect this electrical connection, and figure out of the switch is set to "on" or "off".

***

## Functions

#### awesome.toggle.*isOn()*

The `isOn()` function checks if the switch is set to "on".

*Returns:* It returns a `bool`. This bool is `true` if the switch is set to "on" and `false` if it's set to "off".

#### awesome.toggle.*isOff()*

The `isOff()` function checks if the switch is set to "off".

*Returns:* It returns a `bool`. This bool is `true` if the switch is set to "off" and `false` if it's set to "on".

## Tips
The switch is handy when you want to have two different modes that your program runs in. For example, one mode could silence the buzzer. It works well with if().
