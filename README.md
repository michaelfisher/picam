# PiCam
A Raspberry Pi based motion sensing, and Bluetooth enabled, security camera. The basic idea is that the Pi is aware of Bluetooth devices in its vicinity, and will only detect/record motion events when specified devices are not within range. For example: You could specify your iPhone's BT address and your spouse's, but not your children's. The Pi would NOT detect/record motion events when you and your spouse are home, but if the kids were home alone, it would be detecting/recording motion events.

Feel free to make suggestions or use the code for your own project.

### What hardware you'll need
* A Raspberry Pi computer with Raspbian installed (I used the Model 2 B)
* The Raspberry Pi camera module (or the PiNoIR module)
* A Bluetooth adapter (I used the Kinivo BTD-400 purchased on [Amazon.com](http://www.amazon.com/Kinivo-BTD-400-Bluetooth-4-0-adapter/dp/B007Q45EF4))
* Nwazet Pi Camera Box Bundle (purchased from [ModMyPi.com](http://www.modmypi.com/raspberry-pi/camera/nwazet-pi-camera-box-bundle-case,-lens-and-wall-mount-b-plus)) *optional*

