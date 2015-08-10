# Buzzer

The buzzer is a simple speaker. It can make sounds, and you can use it to make music.

***

## Functions

#### awesome.buzzer.*turnOn(int frequency)*

The `turnOn()` function turns the buzzer on, so that it makes a sound.

*Inputs:* It takes an integer `frequency` as an input. A higher number will make a higher pitched sound. We usually use between `300-600`.

#### awesome.buzzer.*turnOff()*

The `turnOff()` function turns the buzzer off, so that it stops making a sound.

#### awesome.buzzer.*beep(int millis, int frequency)*

The `beep()` function turns the buzzer on at a certain frequency. Then it waits for a certain number of milliseconds, and then turns it off again.

*Inputs:* It takes two inputs `millis` and `frequency`. Both are `int`s. `Millis` is the number of milliseconds the buzzer will beep for. `frequency` controls how high pitched the sound will be.

#### awesome.buzzer.*isOn()*

The `isOn()` function checks to see if the buzzer is currently turned on.

*Returns:* it returns a `bool`. The `bool` is true if the buzzer is currently turned on, and `false` if it is currently turned off.

#### awesome.buzzer.*isOff()*

The `isOff()` function checks to see if the buzzer is currently turned off.

*Returns:* it returns a `bool`. The `bool` is `true` if the buzzer is currently turned off, and `false` if it is currently turned on.

## Tips
The buzzer is helpful helpful for alerts, and for making music!
