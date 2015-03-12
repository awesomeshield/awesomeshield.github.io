# millis ( ) { }

`millis()` tells you how much time has gone by since the Arduino was last turned on, or reset.

***

#### Inputs
It doesn't take any inputs.

#### Returns
It returns the number of milliseconds as a `long`. It can't count past 50 days worth of milliseconds, so it resets to `0` after about that much time.

#### Tips
millis() is really useful when you want that depends on time (like a timer or a metronome), but you don't want to use delay().

#### Example
<iframe style="height: 510px; width: 100%; margin: 10px 0 10px;" allowTransparency="true" src="https://codebender.cc/embed/sketch:70635" frameborder="0"></iframe>
