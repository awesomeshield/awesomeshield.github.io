# Light Theremin

A theremin is an instrument that you control my moving your hand around. Usually they change the pitch of the note that's being played based on how far above the instrument your hand is. We're going to make one using the light sensor on the awesome shield.

***

#### Let's make some noise
You can use the `awesome.buzzer.beep(int time, int pitch)` function to beep the buzzer.


#### Returns
It doesn't return anything.

#### Tips
You should `delay` for a little while (`15` to `150` millis, depending on how much the servo needs to move) to let the servo move after you use `servo.write`.

#### Example
<iframe style="height: 510px; width: 100%; margin: 10px 0 10px;" allowTransparency="true" src="https://codebender.cc/embed/sketch:93429" frameborder="0"></iframe>
