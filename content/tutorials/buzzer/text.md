# Buzzer

The buzzer is a very simple speaker. It can make a tone for a certain amount of time. We call this beeping.

***

## Functions

#### awesome.buzzer.*turnOn(int frequency)*

The `turnOn()` function turns the buzzer on, so that it makes a sound.

*Inputs:* It takes an integer `frequency` as an input. A higher number will make a higher pitched sound. We typically use between `300-600`.

#### awesome.buzzer.*turnOff()*

The `turnOff()` function turns the buzzer off, so that it stops making a sound.

#### awesome.buzzer.*beep(int millis, int frequency)*

The `beep()` function turns the buzzer on at a certain frequency, waits for a certain numebr of milliseconds, and then turns it off again.

*Inputs:* It takes two inputs `millis` and `frequency`. Both are `int`s. `Millis` is the number of milliseconds the buzzer will beep for. `frequency` controls how high pitched the sound will be.

#### awesome.buzzer.*isOn()*

The `isOn()` function checks to see if the buzzer is currently turned on.

*Returns:* it returns a `bool`, which is true if the buzzer is currently turned on, and `false` if it is currently turned off.

#### awesome.buzzer.*isOff()*

The `isOff()` function checks to see if the buzzer is currently turned off.

*Returns:* it returns a `bool`, which is `true` if the buzzer is currently turned off, and `false` if it is currently turned on.

## Tips
The buzzer is useful in projects where you might not be looking at your Awesome Shield, but need to know when something happens.
