# Blinking LED

Within this tutorial we are going to use Scratch and a Raspberry Pi to make an LED blink on and off.

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
Lets build the circuit. Make sure you have your LED the right way round. The positive leg is the longer leg on the LED, this is represented by the bent leg in the diagram below:

![LED Circuit](Images/LED_Diagram.png)

## Code
The first thing we need to do is load scratch. To do this go to menu -> programming -> scratch.

1. Once Scratch has opened click on the ![Events menu](Images/Events_menu.png)

2. Drag a ![When green flag clicked](Images/green_flag_clicked.png) block to the coding area.

3. Next we need to go to the ![Control Menu](Images/Control_menu.png) and drag  a ![forever](Images/Forever_block.png) block. Attach this under the ![Green flag clicked](Images/green_flag_clicked.png) block.

4. We now need to go to the ![More blocks](Images/More_blocks.png) menu.

5. We now need to click on ![Add an extension](Images/Add_extension.png). Then double click ![Pi GPIO](Images/Pi_gpio.png) extension.

6. Next we need a ![Set GPIO to](Images/Set_GPIO_to.png) block. Attach this in the ![Forever](Images/Forever_block.png) block. Click in the white circle and type *18*.

7. we now need to go back to the ![Control Menu](Images/Control_menu.png) and drag a  ![Wait 1 second](Images/Wait_1.png) block and attach it under the ![Set GPIO to 18](Images/Set_GPIO_to_18.png) block.

8. We now need to go back to the ![More Blocks](Images/More_blocks.png) menu and get another ![Set GPIO to](Images/Set_GPIO_to.png) and attach it under the ![Wait 1 second](Images/Wait_1.png) block. Again click in the circle and type *18* then click on the black arrow and select *output low*.

9. Again go back to the ![Control Menu](Images/Control_menu.png) and drag another ![Wait 1](Images/Wait_1.png) block and attach it under the ![Set GPIO to 18 Low](Images/Set_GPIO_to_18_low.png) and click in the box that says 1 and change it to *2*.

Your code should look like this ![Code](Images/Blink_code_2.png)

## What The Code Does
* ![When Green flag clicked](Images/green_flag_clicked.png) This tells Scratch to run the code when the green flag is clicked.

* ![forever](Images/Forever_block.png). This makes the code loop forever.

* ![Set GPIO 18](Images/Set_GPIO_to_18.png) This tells the raspberry pi to turn GPIO pin 18 on, which is where your LED is attached.

* ![Wait 1](Images/Wait_1.png) This makes the code pause for 1 second.

* ![Set GPIO 18 Low](Images/Set_GPIO_to_18_low.png) This tells the raspberry pi to turn GPIO pin 18 off, which is where your LED is attached.

* ![wait 2](Images/Wait_2.png) This makes the code pause for 2 seconds.

## Running The Code
Now that we have finished the code to run it click ![the green flag](Images/Green_Flag.png). You should now see the LED blink on and off, if you don't go back and see where you went wrong.

To stop the code click on the ![red circle](Images/Red_dot.png)

Well done you have just made an LED blink on and off.

### Keep Having FUN while LEARNING!
