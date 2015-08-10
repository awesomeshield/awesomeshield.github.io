# delay ( )

delay ( ) tells the Arduino to wait for a certain amount of time. After waiting, it will the instruction on the next line of code.

*Inputs:* It takes an input, which is an `int`. This `int` tells the Arduino how long to wait for. It's a number of milliseconds. 1000 milliseconds is the same as 1 second. So `delay(1000)` will wait for 1 second.

#### Tips
delay() is lets you separate instructions by a certain amount of time. For example, you could turn the LED on, use delay to wait for one second, and then turn it off.
