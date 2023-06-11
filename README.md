# Project Description:
The objective is to design and implement a digital circuit that acts like a digital lock for a safe which accepts a binary passcode, compare it to a preset code by a comparator and takes an action depending on the validity of the entered value.  If a wrong code is entered for three successive trials, the lock should no longer accept a new value unless a Reset switch is pressed.

# Project Requirements:
1.  A 3-bit binary passcode is entered through switches (Preferably dipswitches for ease of use). The preset code is also adjusted through dipswitches.
2.  A switch is used to pass the input to the comparator via flip flops.
3.  Wrong trials counter is incremented each time a code is passed and a false indication is given by the comparator. Ready-made counter IC could be used.
4.  Output action is to illuminate a green LED in case of correct code or a red LED otherwise and another output LED is to be illuminated when wrong trials counter reaches three. 
