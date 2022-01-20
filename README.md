micro:bit Blinking LED
--------------------
In this assignment you will connect an LED to the micro:bit with alligator clips. You will then write a program that blinks the first letter of your name in Morse code. You can find the codes for each letter on [Wikipedia's Morse Code page](https://en.wikipedia.org/wiki/Morse_code). Here's a sample program that creates a long and a short blink.
```python
# Add your Python code here. E.g.
from microbit import *

while True:
    pin0.write_digital(1)
    sleep(2000)  #long Blink
    pin0.write_digital(0)
    sleep(2000)   
    pin0.write_digital(1)
    sleep(500)  #short Blink
    pin0.write_digital(0)
    sleep(500) 
```

You will submit the code and a short video of your program running. You may find slides 99 - 104 of the [slide presentation](https://docs.google.com/presentation/d/1aiGcnPn8uoCJdX8p7_qoI3Hh3_KOhUtFeB3Byw0tacA/edit?usp=sharing) helpful in completing this assignment.
  
Extensions
----------
You can add more blinks to your program to spell out a longer message.

Samples of Student Work
----------
*none yet!*
