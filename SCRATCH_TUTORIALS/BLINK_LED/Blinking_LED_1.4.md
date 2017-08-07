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
![LED Circuit](Images/LED_Diagram.png)

## Code
The first thing we need to do is load scratch. To do this go to menu -> programming -> scratch.

1. Once Scratch has opened click on the ![Control menu](Images/Control_menu.png)

2. Drag a ![When green flag clicked](Images/green_flag_clicked.png) block to the coding area.

3. Next we need a ![Broadcast](Images/Broadcast.png) block. Connect it to the ![When green flag clicked](Images/green_flag_clicked.png) block.

4. Now click on the little black arrow and click the next/edit button. You should get a text box like this ![Text Box](Images/Text_Box.png). In the textbox type *gpioserveron* and click OK.

5. Drag another ![Broadcast](Images/Broadcast.png) block into the coding area and attach it to the ![GPIO Server On](Images/gpio_server_on.png) block. Click on the black arrow and click on new/edit. This time type *config18out* and click OK.

6. Next we need a ![forever](Images/Forever_block.png) block. Attach this under the ![config 18 out](Images/config_18_out.png) block.

7. We now need another ![Broadcast](Images/Broadcast.png) block this time attach it within the ![forever](Images/Forever_block.png) block. Again click on the black arrow and edit/new. This time type *gpio18on*.

8. We now need a ![Wait 1 second](Images/Wait_1.png) block. Attach this under the ![gpio 18 on](Images/gpio_18_on.png) block.

9. Next we need another ![Broadcast](Images/Broadcast.png) block. Attach this under the ![Wait 1 second](Images/Wait_1.png) block. Click on the black arrow and edit/new within the text box type *gpio18off*.

10. we now need another ![Wait 1 second](Images/Wait_1.png) block and attach it under the ![gpio 18 off](Images/gpio_18_off.png) block. Click within the white space and change the 1 to a 2.

Your code should look like this ![Code](Images/Blink_code.png)

## What The Code Does
* ![When Green flag clicked](Images/green_flag_clicked.png) This tells Scratch to run the code when the green flag is clicked.

* ![GPIO server on](Images/gpio_server_on.png) This tells Scratch to interact with the GPIO pins on the pi.

* ![Configure pin 18](Images/config_18_out.png) This configures pin 18 on the raspberry pi as an output.

* ![forever](Images/Forever_block.png). This makes the code loop forever.

* ![GPIO 18 on](Images/gpio_18_on.png) This tells the raspberry pi to turn GPIO pin 18 on, which is where your LED is attached.

* ![Wait 1](Images/Wait_1.png) This makes the code pause for 1 second.

* ![GPIO 18 off](Images/gpio_18_off.png) This tells the raspberry pi to turn GPIO pin 18 off, which is where your LED is attached.

* ![wait 2](Images/Wait_2.png) This makes the code pause for 2 seconds.

## Running The Code
Now that we have finished the code to run it click ![the green flag](Images/Green_Flag.png). You should now see the LED blink on and off, if you don't go back and see where you went wrong.

To stop the code click on the ![red circle](Images/Red_dot.png)

Well done you have just made an LED blink on and off.

### Keep Having FUN while LEARNING!
