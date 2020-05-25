# Enviro

<b>You can sense temperature, pressure, light, local color, accelerometer readings, and magnetometer data using the EnviroPhat sensor and Raspberry Pi Zero W.</b>

## <a  href="https://shop.pimoroni.com/products/enviro-phat">Getting EnviroPhat<br><img src="images/enviroPhat.png" width=300></a>

## <a href="https://thepihut.com/collections/raspberry-pi/products/raspberry-pi-zero-w">Getting Raspberry Pi Zero W
<img src="images/RasPiZeroHeader.jpg" width=200>
<br>The Raspberry Pi Mega Kit includes a Raspberry Pi Zero W</a> with GPIO header attached plus a 16GB MicroSD memory card with the Raspbian operating system installed.  You can use your own memory card and <a href="https://www.raspberrypi.org/downloads/raspbian/">download and install Raspbian</a> 

## Interacting with Raspberry Pi Zero W

To connect directly to your Raspberry Pi Zero W, you will need a miniHDMI-to-HDMI adaptor and a microUSB-to-USB adaptor.  Power Raspberry Pi with a wall plug or a USB battery capable of powering mobile phones.

You can connect remotely using Secure Shell (SSH).  First, you must enable SSH.  Click the <img src="images/raspberry.png" width=40> raspberry icon on the menu.  Select ```Preferences```, then select ```Raspberry Pi Configuration```.  Click the ```Interfaces``` tab and enable ```SSH```.  

![Window for enabling SSH as described in text](images/SSH.png)


## Building your device

Solder a pin header to the EnviroPhat board and snap the board onto your Raspberry Pi.  Follow this [tutorial](https://learn.pimoroni.com/tutorial/sandyj/getting-started-with-enviro-phat) to install the EnviroPhat software and test your device.


## Verifying the version of Python

The Raspbian operating system comes with two versions of Python pre-installed.  This tutorial uses Python 3.  Verify that this version is installed:

```
python3 --version
$ Python 3.4.2
```

```
pip3 --version
$ pip 1.5.6 from /usr/lib/python3/dist-packages (python 3.4)
```

## Investigating your data

[Charting EnviroPhat data on ThingSpeak](https://thingspeak.com/channels/865246)

## Learning as we go

- As of October, 2019, Raspberry Pi Buster operating system appears to have a WiFi Bug.  You may want to use Stretch until a solution is found.  Learn more:  https://www.raspberrypi.org/forums/viewtopic.php?t=252984
