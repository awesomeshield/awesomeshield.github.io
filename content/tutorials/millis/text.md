# millis ( )

`millis()` tells you how much time has gone by since the Arduino was last turned on, or reset.

*Returns:* It returns the number of milliseconds as a `long`. It can't count past 50 days, so it resets to `0` after about that much time.

## Tips
The `millis()` function lets you add timing to your project, without using `delay()`.
