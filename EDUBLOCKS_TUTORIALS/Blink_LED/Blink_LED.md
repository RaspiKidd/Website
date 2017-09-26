# Blinking LED
Within this tutorial we are going to make an LED blink on and off using EduBlocks and a Raspberry Pi.

## Equipment You Will Need

* 1 x LED
* 2 x male to female jumper wires
* 1 x breadboard
* 1 x 330 ohm resistor
* Raspberry Pi
* keyboard
* Mouse
* SD Card with Raspbian installed
* HDMI cable
* Compatible Screen
* Power Supply

## The Circuit
Lets build the circuit. Make sure you have your LED the right way round. The positive leg is the longer leg on the LED, this is represented by the bent leg in the diagram below:

![LED Circuit](Images/LED_Diagram.png)

## Code
The fist thing we need to do is open EduBlocks. do this by double clicking on the ![EduBlocks](Images/EduBlocks.png) desktop icon.(if you don't have EduBlocks installed check out the [getting started guide]())

1. Click on the ![GPIOZero menu](Images/GPIO_Zero.png) and click on the ![General menu](Images/General_Zero.png). Then locate the ![from gpiozero import *](Images/Import_GPIOzero.png) and drag it to the coding area.

2. Now Click on the ![Outputs menu](Images/Outputs.png) menu. Then click on the ![LED menu](Images/LED.png) From here locate the ![led=LED block](Images/LED_Pin.png) and in the bit that is says pin type *18*.

3. Next locate the ![led.on](Images/LED_On.png) and click on the arrow next to on and click on ![blink](Images/LED_menu.png)

Your code should now look like this:
![LED blink](Images/LED_Blink1.png)

## Running Your Code
To run your code click on ![Run](Images/Run1.png) in the top far right corner.

You should now see your LED turn on.

### Keep having FUN while LEARNING!
