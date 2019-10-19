# Binary Clock

Within this tutorial you are going to create a binary clock using a micro:bit. Binary is a numbering system computers use.

you will keep track of the time by displayng the hours, minutes and seconds as seperate binary numbers on the micro:bit LED display.

## Reading the clock

To read the clock you start on the top row of LEDs, this row represents the hours.

Each column of LEDs represents a number. From right to left the columns are numbered 1, 2, 4, 8 and 16. By adding these 5 numbers you can get every value of a 24 hour clock.

The middle two rows represent the minutes and the bottom two rows represent the seconds. Since for the minutes and seconds you need to be able to count up to 60, the left LED on the upper rows represents 32. (See the graphical representation below)

![Binary Clock](BinaryClock.png)

## You Will Need

* 1 x micro:bit

* 1 x micro USB cable

* [EduBlocks Code Editor](http://app.edublocks.org/) (http://app.edublocks.org/)

## Code

### Creating Variables

There are a few variables that you will need, so let's get these out of the way first.

To create a variable click on **Variables** then click on **Create variable...**. This will bring up a text box for you to enter the name of the variable.  Do this for each of the following varibales

[ ] secLeds

[ ] minLeds

[ ] hourLeds

[ ] hours

[ ] minutes

[ ] seconds

[ ] adjust

[ ] vBit

[ ] lastTime

[ ] tick

[ ] displayBinary

[ ] now

[ ] elapsedMs

### Importing micro:bit library and settig up variables

1. Click on **Basic**  
   
2. Click and drag a **from microbit import *** and drop it in the coding area.
   
3. Click on **Variables** Click and drag **adjust = 0** block to the coding area and attach it under **from microbit import ***.
   
4. Click on the small arrow next to **adjust** and click on  **secLeds**
   
5. Click on the **0** and type **[[4,4], [3,4], [2,4], [1,4], [0,4],[0,3]]**
   
6. Click on **Variables**. Click and drag **adjust = 0** block to the coding area and attach it under **secLeds = [[4,4], [3,4], [2,4], [1,4], [0,4], [0,3]]**
   
7. Click on the small arrow next to **adjust** and click on **minLeds**
   
8. Click on the **0** and type **[[4,2], [3,2], [2,2], [1,2], [0,2], [0,1]]**
   
9.  Click on **Variables**. Click and drag **adjust = 0** block to the coding area and attach it under **minLeds = [[4,2], [3,2], [2,2], [1,2], [0,2], [0,1]]**
    
10. Click on the small arrow next to **adjust** and click on **hourLeds**
    
11. Click on the **0** and type **[[4,0], [3,0], [2,0], [1,0], [0,0]]**
    
12. Click on **Variables**. Click and drag **adjust = 0** block to the coding area and attach it under **hourLeds = [[4,0], [3,0], [2,0], [1,0], [0,0]]**
    
13. Click on the small arrow next to **adjust** and click on **hours**
    
14. Click on **Variables**. Click and drag **adjust = 0** block to the coding area and attach it under **hours = 0**
    
15. Click on the small arrow next to **adjust** and click on **minutes**
    
16. Click on **Variables**. Click and drag **adjust = 0** block to the coding area and attach it under **minutes = 0**
    
17. Click on the small arrow next to **adjust** and click on **seconds**
    
18. Click on **Variables**. Click and drag **adjust = 0** block to the coding area and attach it under **seconds = 0**
    
19.  Click on the **0** and type **-10**

Your code should now look like this:
![Code Block 1](CodeBlock01.png)