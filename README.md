ECE281_CE4
==========

####Lab
For part a, I just needed to check the box to allow changes to RAM.  Then I gave the needed locations labels that I
used when storing the values.  Afterwards, it was simply a matter of loading the correct values and then storing them
in the RAM locations.

For part b, I gave a label to the first RAM location and loaded it.  To multiply by two, I added the same number from
the location.  To subtract by four, I added C, which is the hex equivalent of the binary value for negative four. This
effectively subtracted four from the current value.  When the starting value is set at one or zero, since the value
multiplied by two is less than four, the result comes out at the other end of the hex values.

For part c, I input from port 3.  I then output the value to port 0 and subracted one.  To subtract one, I added F
based on the same reasoning for part b.  Afterwards, I output the value to port 1, subracted by one again, and output
the third value to port 2.  At the end of the program, I jumped back to a loop that was set at the first output so that
the program would continue to decrease the output values.  Initially, I was subtracting a third time, which caused the
program to jump values rather than go down by one each loop.  Ryan Redhead pointed out that I needed to add by one at
the end to return to the value just below the first output.

For all parts, I matched the target end address.

#Functionality
- Simple Memory Manipulation (part a)
- Mathematics (part b)
- Loops (part c)
