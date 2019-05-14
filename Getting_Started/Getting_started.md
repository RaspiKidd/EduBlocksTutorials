# Getting Started

## What Is EduBlocks?
Edublocks is a program, which allows you to write real Python code but in block format like Scratch, with this in mind it is helping educators teach younger children  how to program in Python using blocks and by the time they are able to move on to text Python they will already understand the Python syntax.

EduBlocks can be used with the Raspberry Pi, micro:bit, Adafruit Circuit Python boards like the Circuit Playground Express and Python3 within a web browser like Chrome.

The Python3 and micro:bit modes of Edublocks will work as soon as you click on them. The Raspberry Pi and Adafruit Circuit Playground Express board needs a few extra steps to run. We will go through these steps below.

## How to Setup EduBlocks on Raspberry Pi
EduBlocks does not come installed on the Raspberry Pi by default, so for us to install it we need to open a terminal window to do this by clicking on the icon that looks like this ![Terminal Icon](Images/Terminal.png) It is located at the top of the screen along from the menu icon.

Once the Terminal has opened you will see a window similar to this: ![Terminal Window](Images/TerminalWindow.png)

Now we need to type the following command:

```bash
curl -sSL connect.edublocks.org | bash
```
Once you have typed the line above press enter. Now we just have to wait till its finished.

Now type The following and press enter:
```bash
edublocks-startup-enable
```
This will start EduBlocks when the Raspberry Pi starts up.

## How to Setup EduBlocks on the Circuit Playground Express
By default when buying a Circuit Playground Express it is set up to use MakeCode while we are wanting to run Circuit Python.

To install Circuit Python open up a web browser and type `https://circuitpython.org/board/circuitplayground_express/`
This will take you to the software page for the Circuit Playground Express (CPX). It is recommended that you install the most stable version of Circuit Python by clicking on Download .UF2 Now. This will download the latest version of Circuit Python to your computer.  

Once the download has complete we need to transfer the file to the CPX.

1. Plugin the CPX to your computer using a micro USB cable.
2. Double press the reset button. you should see all the neopixels turn green. If they turn red unplug the CPX and try again.
3. Locate the .UF2 file on your computer.
4. Click and drag the file and drop it over the **CPLAYBOOT** drive and drop it. All the neopixels will turn off and the CPX drive will load back up as **CIRCUITPY**

Your are now ready to program your CPX using EduBlocks.

## Starting EduBlocks
Open any web browser on any system and type `app.edublock.org` within the address bar.
You will see the following screen:
![Landing Screen](Images/StartupScreen.png)
Click on the mode that you want to use.

We will dig deeper into the different modes through other tutorials.
Until next time.

#### Keep having FUN while LEARNING!  
