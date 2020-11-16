# LED Matrix

## Objective

Learn how to use the LED matrix on the micro:bit which can be used as a screen to output data.

We are going to explore how to use the LED matrix with EduBlocks.

 ---
 **NOTE:** You will need to a micro:bit to complete this tutorial.

---

## Starting EduBlocks

1. Open your favourite web browser(we recommend Google Chrome)
2. Within the address bar type[app.edublocks.org](app.edublocks.org)
3. Click on micro:bit.

## Code Blocks

These are the blocks that we can use to control the LED matrix.

1. **Display.scroll("Hello World")**
![Display Text](Images/DisplayText.png) This does exactly what it says and scrolls text on the LED matrix.

2. **display.scroll(0)**
![Display Number](Images/DisplayNumber.png) This does exactly as it says and scrolls a number on the LED matrix.

3. **display.scroll(Image.HAPPY)**
![Display Image](Images/DisplayImage.png) This allows us to display preconfigured images on the LED matrix.

4. **display.set_Pixel(0,0,5)**
![Set Pixel](Images/DisplayPixel.png) This lights up one of the LEDs on the matrix by taking a value for the row, column and brightness you want the LED

5. **display.off()**
![Display off](Images/DisplayOff.png) This displays an arrow or compass direction on the LED matrix

6. **image**
![Create an Image](Images/CreateImage.png) This allows you to create your own images by changing the 0's(off) to 5's(on).

## Displaying Text

1. Click on Basic. Click and drag a from microbit import * block to the code area and drop it.

2. Click on Basic. Click and drag a while True: block to the code area and attach it under from microbit import *.

3. Click on Display. Click and drag a display.scroll("Hello World") block to the code area and attach it within the while True: block.

4. Click where it says "untitled" at the top of the page and give your project a meaningful name. Then click on Save to save your project.

5. Click Download Hex to download your program to your computer.

6. Locate where your micro:bit program downloaded on your computer this will normally be the Downloads folder. Click and drag your program across to your micro:bit to run your program on your micro:bit.

Your code should look like this:

![Display Text Code](Images/DisplayTextCode.png)

## Displaying Numbers

1. Click on Basic. Click and drag a from microbit import * block to the code area and drop it.

2. Click on Basic. Click and drag a while True: block to the code area and attach it under from microbit import *.

3. Click on Display. Click and drag a display.scroll("0") block to the code area and attach it within the while True: block. Click where it says "0" and choose your own number to scroll on the micro:bit.

4. Click where it says "untitled" at the top of the page and give your project a meaningful name. Then click on Save to save your project.

5. Click Download Hex to download your program to your computer.

6. Locate where your micro:bit program downloaded on your computer this will normally be the Downloads folder. Click and drag your program across to your micro:bit to run your program on your micro:bit.

Your code should look like this:

![Display Numbers Code](Images/DisplayNumberCode.png)

## Display Image

1. Click on Basic. Click and drag a from microbit import * block to the code area and drop it.

2. Click on Basic. Click and drag a while True: block to the code area and attach it under from microbit import *.

3. Click on Display. Click and drag a display.show(Image.HAPPY) block to the code area and attach it within the while True: block. You can change "HAPPY" to various pre-made images. Find a full list of the images here [https://bit.ly/2IaPXI1](https://microbit-micropython.readthedocs.io/en/v1.0.1/image.html#attributes)

4. Click where it says "untitled" at the top of the page and give your project a meaningful name. Then click on Save to save your project.

5. Click Download Hex to download your program to your computer.

6. Locate where your micro:bit program downloaded on your computer this will normally be the Downloads folder. Click and drag your program across to your micro:bit to run your program on your micro:bit.

Your code should look like this:

![Display Image](Images/DisplayImageCode.png)

## Set Pixel

1. Click on Basic. Click and drag a from microbit import * block to the code area and drop it.

2. Click on Basic. Click and drag a while True: block to the code area and attach it under from microbit import *.

3. Click on Display. Click and drag a display.set_pixel(0,0,5) block to the code area and attach it within the while True: block. You can change the two "0s" to any number up to 4 depending on what LED you want to turn on. We recommend keeping the brightness at 5, but if you want to change this you can pick any number from 0-9.

4. Click where it says "untitled" at the top of the page and give your project a meaningful name. Then click on Save to save your project.

5. Click Download Hex to download your program to your computer.

6. Locate where your micro:bit program downloaded on your computer this will normally be the Downloads folder. Click and drag your program across to your micro:bit to run your program on your micro:bit.

Your Code should look like this:

![Set Pixel Code](Images/DisplayPixelCode.png)

## Create Image

1. Click on Basic. Click and drag a from microbit import * block to the code area and drop it.

2. Click on Display. Click and drag an image=("") block to the code area and attach it under from microbit import *.

3. Create your own image by changing the 0s to 5s where you want the LEDs to light up.

4. Click on Basic. Click and drag a while True: block to the code area and attach it under image=("").

5. Click on Display. Click and drag a display.show() block to the code area and attach it within the while True: block.

6. Click on Variables. Click and drag an image block to the code area and attach it within the display.show block.

7. Click where it says "untitled" at the top of the page and give your project a meaningful name. Then click on Save to save your project.

8. Click Download Hex to download your program to your computer.

9. Locate where your micro:bit program downloaded on your computer this will normally be the Downloads folder. Click and drag your program across to your micro:bit to run your program on your micro:bit.

Your code should look like this:

![Create image code](Images/CreateImageCode.png)

## Turn the Display Off

We are going to re-purpose our code from above and add to it for this next bit of code.

1. Click on Basic. Click and drag a sleep(1000) block to the code area and attach it under the display.show(image) block.

2. Click where it says "1000" and change this to "5000". This changes the program from pausing for 1 second to pause 5 seconds.

3. Click on Display. Click and drag a display.on() block to the code area and attach it under sleep(5000). Click on the little arrow next to on and click on off.

4. Click on the name of the old program and give this one a new name and click on save.

5. Click Download Hex to download your program to your computer.

6. Locate where your micro:bit program downloaded on your computer this will normally be the Downloads folder. Click and drag your program across to your micro:bit to run your program on your micro:bit.

Your code should look like this:

![Display Off Code](Images/DisplayOffCode.png)

## Conclusion

We have now learned how to use the LED matrix on the micro:bit

> ## Challenge
>
> You now know how to use all the display blocks on their own.
>
> Why not try and use a few of them together to create your own program.
