# C1M4

Final assessment of coursera course "Introduction to Embedded Systems Software and Development Environments"


## Description: 
<br>
This program generate one excuatble to run on specific platform, in this we have 2 platforms: 
* HOST
* MSP432

the program itself maniplautes memory and you have various of options from the makefile to inspect memory and size of code.

<br>


## Build options:

**Generate assembly:** <br>
`make main.asm PLATFORM=HOST`  
`cat main.asm`  
<br>

**Full build:**<br>
Everytime it will give a report on size.  
`make build PLATFORM=HOST`  
`./c1m2.out`  
`cat c1m1.map` : To see how the code is mapped in memory.

<br>

### Don't forget make clean

## Modifications needed:

 - itoa function to handle signed numbers.
 - sort out include libraries.


<br />
