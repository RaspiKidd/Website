# Turning An LED On
Within this tutorial we are going to turn an LED on using EduBlocks and a Raspberry Pi.

## Equipment You Will Need

* 1 x  LED
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
The fist thing we need to do is open EduBlocks. do this by double clicking on the ![EduBlocks](Images/EduBlocks.png) desktop icon.

1. Click on the ![GPIOZero menu](Images/GPIO_Zero.png) and click on the ![General menu](Images/General_Zero.png) and locate the ![import gpiozero *](Images/Import_GPIOzero.png) and drag it to the coding area.

2. Next Click on the ![Outputs menu](Images/Outputs.png) menu. Then click on the ![LED menu](Images/LED.png) From here locate the ![led = LED pin](Images/LED_Pin.png) and drag it to the coding area and attach it under the ![import gpiozero *](Images/Import_GPIOzero.png). where it says pin change that to say *18*.

3. Next locate the ![led.on()](Images/LED_On.png) and attach it under the ![led = LED pin](Images/LED_Pin.png)

Your code should now look like this:
![LED on](Images/LED_On_Code.png)

## Running Your Code
To run your code click on ![Run](Images/Run1.png) in the top far right corner.

You should now see your LED turn on.

### Keep having FUN while LEARNING!
