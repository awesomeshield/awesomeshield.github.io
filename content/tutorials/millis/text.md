# millis ( ) { }

`millis()` tells you how much time has gone by since the Arduino was last turned on, or reset.

***

#### Inputs
It doesn't take any inputs.

#### Returns
It returns the number of milliseconds as a `long`. It can't count past 50 days worth of milliseconds, so it resets to `0` after about that much time.

#### Tips
`millis()` is really useful when you want that depends on time (like a timer or a metronome), but you don't want to use delay().

#### Example
We haven't quite written an example yet. If you want, you can send us something you build with `millis` and we'll put it here! :-)
