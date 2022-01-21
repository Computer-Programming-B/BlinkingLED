micro:bit Blinking LED
--------------------
In this assignment you will connect an LED to the micro:bit with alligator clips. You will then write a program that blinks the first letter of your name in Morse code. You can find the codes for each letter on [Wikipedia's Morse Code page](https://en.wikipedia.org/wiki/Morse_code). We'll use the following Morse Code timing rules:

* The length of a dot is 1 time unit
* A dash is 3 time units
* The space between symbols (dots and dashes) of the same letter is 1 time unit
* The space between letters is 3 time units
* The space between words is 7 time units.

Here's a sample program that signals Morse Code for the letter "A".
```python
# Add your Python code here. E.g.
from microbit import *

while True:
    pin0.write_digital(1) #dot
    sleep(100)            #one unit
    pin0.write_digital(0) #off
    sleep(100)            #one unit
    pin0.write_digital(1) #dash
    sleep(300)            #three units
    pin0.write_digital(0) #off
    sleep(700)            #seven units
```

If your first name starts with "A", use the first letter of your last name since the sample program uses "A".

Submit the code and a short video of your program running. You may find slides 99 - 106 of the [slide presentation](https://docs.google.com/presentation/d/1aiGcnPn8uoCJdX8p7_qoI3Hh3_KOhUtFeB3Byw0tacA/edit?usp=sharing) helpful in completing this assignment.
  
Extensions
----------
You can add more blinks to your program to spell out a longer message.

Samples of Student Work
----------
*none yet!*
