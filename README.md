# PiCam
A Raspberry Pi based motion sensing, and Bluetooth enabled, security camera. The basic idea is that the Pi is aware of Bluetooth devices in its vicinity, and will only detect/record motion events when specified devices are not within range. For example: You could specify your iPhone's BT address and your spouse's, but not your children's. The Pi would NOT detect/record motion events when you and your spouse are home, but if the kids were home alone, it would be detecting/recording motion events.

Feel free to make suggestions or use the code for your own project.

### What hardware you'll need:
* A Raspberry Pi computer (I used the Model 2 B) _Model A+ WILL NOT work for this project, as we need either (1) USB and (1) Ethernet, or (2) USB_
* A power supply and MicroSD card (minimum 16GB)
* The Raspberry Pi camera module (or the PiNoIR module)
* A Bluetooth adapter (I used the Kinivo BTD-400 purchased on [Amazon.com](http://www.amazon.com/Kinivo-BTD-400-Bluetooth-4-0-adapter/dp/B007Q45EF4))
* Nwazet Pi Camera Box Bundle (purchased from [ModMyPi.com](http://www.modmypi.com/raspberry-pi/camera/nwazet-pi-camera-box-bundle-case,-lens-and-wall-mount-b-plus)) *optional*

### Putting it all together:
* Install the operating system onto the MicroSD card (I used [Raspbian](https://www.raspberrypi.org/downloads/)). [Learn how to install an operating system image](https://www.raspberrypi.org/documentation/installation/installing-images/)
* Install the MicroSD card in the Pi and power it on (plug it in)
* After logging in (user: pi, password: raspberry), run `sudo raspi-config` and do the following:
  * Expand the filesystem
  * Enable the camera (camera should not be connected to the Pi at this point)
  * Enable SSH
  * Change user password *optional/recommended*
  * Change the hostname *optional/fun*

