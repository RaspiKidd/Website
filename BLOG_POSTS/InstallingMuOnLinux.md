# Installing Mu

Mu is a simple code editor developed in Python for Python. Mu has built-in support for Adafruit Circuit Playground Express, micro:bit, PyGame and Python. Mu runs on Windows, Mac, Linux and even the Raspberry Pi.

## Installing Mu On Windows

1. Go to [codewith.mu](https://codewith.mu/)
2. Click on Download
3. Under Windows Installer click on either **32 bit** or **64 bit** depending on the Operating System you are running.
   To find out what version of Windows you are running follow these instructions:
   1. Open Explorer
   2. Right click on this PC
   3. Click on properties. Under system type it will say either **32 bit** or **64 bit** 
   ![system Properties]()  

Each Linux distro is a bit different, so for this guide, I am going to focus on Ubuntu. 

1. Mu requires Python3. You can check and see if you have Python3 installed by typing:
```
python3 --version
```
If nothing is displayed type:
```
sudo apt install python3
```
to install Python3.

2. You also need pip3 installed type:
```
pip3 --version
```
If it shows nothing you need to install pip3 by typing:
```
sudo apt install python3-pip
```

3. Finally to install Mu type:
```
pip3 install mu_editor
```
4. You can now run Mu from the command line by typing:
```
Mu
```

Now that you have Mu installed you can go and develop in Python3, Micro Python for micro:bit or even CircuitPython for the adafruit Circuit Playground Express. 
