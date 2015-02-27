# for ( ) { }

for() loops through a set of instructions a certain number of times.

***

#### Inputs
It three inputs, separated by semicolons, like this: `for ( input1; input2; input3 )`

*input 1*: you declare a looping variable, for example `x`. You also give the starting value of the variable, for example `1`. This might look like `int x = 1`
*input 2*: you give a test condition that can be `true` or `false`, and uses your looping variable. This could look like `x < 4`.
*input 3*: you increase or decrease the value of your looping variable. This increase or decrease will happen once eery time the instructions inside the `for()` loop's curly braces are followed. You can use `x++` to increase it by one, or `x--` to decrease it by one.

Example:

```
for ( int x=1; x<3, x++ ) {
  // instructions to be followed during looping go here
}
```
When an Arduino sees this example for loop, it will:

1.  start off with `x=1`
2.  check to see if `x` is less than `3`
3.  this will be true, because `x` is equal to `1`
4.  then it will follow the instructions inside the for loop's curly braces
5.  when it's done following the instructions, it will increase `x` by `1`, making `x = 2`
6.  then it will start over...

7.  it will check to see if `x < 3`
8.  this will be true, because `x = 2`
9.  it will follow the instructions inside the loop again
10. it will increase `x` by `1`, making `x = 3`
11. then it will start over...

12.  it will check to see if `x < 3`
13.  this will be false, because `x = 3`
14.  it won't follow the instructions inside the loop
15. it will end the for loop, and move on to the next line of code after the loop


#### Returns
It doesn't return any values.

#### Tips
for() is really handy when you're trying to repead something a certain number of times. Let's say you want to flash and LED 10 times, you could use a for() loop. Check out the example below to see how this works.

#### Example
<iframe style="height: 510px; width: 100%; margin: 10px 0 10px;" allowTransparency="true" src="https://codebender.cc/embed/sketch:70635" frameborder="0"></iframe>
