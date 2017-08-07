# Turning an LED on (Scratch 2)

Within this tutorial we are going to make an LED turn on using scratch and a Raspberry Pi.

## Equipment You Will Need
* 1 x red LED
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
![LED Circuit](Images/LED_Diagram.png)

## Code
The first thing we need to do is load scratch. To do this go to menu -> programming -> scratch.

1. Once Scratch has opened click on the ![Events](Images/Events_menu.png) menu and drag a ![When green flag clicked](Images/Green_Flag_Clicked.png) block into the coding area.

2. Next click on the ![More blocks](Images/More_blocks.png) menu.

3. Next click on ![Add an Extension](Images/Add_extension.png) and double click on ![Pi GPIO](Images/Pi_GPIO.png) Icon. This will enable the Raspberry Pi GPIO pin extension.

4. Next drag a ![Set GPIO to](Images/Set_GPIO_to.png) block into the coding area and attach it to ![When green flag clicked](Images/Green_Flag_Clicked.png) block.

5. Now click in the circle and type 18 (this is the GPIO pin we are using on the Pi).

Your code should now look like this ![Code](Images/code_2.png)

<div class="page-break"></div>

## What The Code Does
* ![When Green flag clicked](Images/green_flag_clicked.png) This tells Scratch to run the code when the green flag is clicked.

* ![Set GPIO To](Images/Set_GPIO_to_18.png) This tells the raspberry pi to turn GPIO pin 18 on, which is where your LED is attached.

## Running The Code
Now that we have finished the code to run it click ![the green flag](Images/Green_Flag.png). You should now see the LED turn on, if you don't go back and see where you went wrong.

### Keep Having FUN while LEARNING!
