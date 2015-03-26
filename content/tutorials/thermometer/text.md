# Thermometer

You can use the temperature sensor on the awesome shield as a thermometer.

***

*You can use the template sketch as a starting point for this project. [Click here to clone it.](https://codebender.cc/sketch:88120)*

***

#### "Hello, World!"
You'll need a place that the Arduino can show you the temperature value. You can send information from the Arduino back to your computer through the USB cable, using `Serial`.

`Serial.print("hi");`

This line of code will send `hi` to your laptop, as text.

Try writing a sketch that sends `"Hello, World!"`. Once you upload your sketch, you can click the "Open Serial Monitor" button in codebender to see any information that the Arduino is sending to your computer.

![Open Serial Monitor Button](/content/photos/open-serial-screen-shot.jpg "Open Serial Monitor Button")


#### Checking the temperature
You can tell the Arduino to check the temperature, using the Awesome Shield's temperature sensor. Here's how:

`awesome.temperatureSensor.check()`

When the Arduino runs the program, it will check the temperature, and replace this code with the temperature it finds. So, for example:

`awesome.temperatureSensor.check()` would be replaced with `25.0` if the room is 25 degrees Celsius.

Try replacing `"Hello, World!"` from your last sketch with this code that reads the temperature, and see what happens.


#### Tidying it up
If you used `Serial.print()` inside the loop, you might have noticed that the Arduino sends the temperature over and over again, without any spaces or labels. This can get a little hard to read.

Try using `serial.print()` to add some text as well, so that your message reads something like "The temperature is 25.0 degrees Celsius."

After you've used `Serial.print()` to create your temperature message, try adding `Serial.println();` at the end. This function makes a new line (`ln` is short for "line"), which is like hitting "enter" in a word processor.

#### Example
