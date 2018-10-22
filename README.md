# AlexaWithRaspberryPi
Using open source software to set up a Raspberry Pi to work as a smart speaker utilizing Amazon's AI, Alexa, and developing open source Alexa Skills to be used on the Raspberry Pi smart speaker.

## Raspberry Pi Setup and SSH
The Raspberry Pi is a tiny and affordable computer that you can use to learn programming through fun, practical projects.
1. Follow the steps on the following website to install Raspbian (the OS for Raspberry Pi) onto the microSD card. https://www.raspberrypi.org/documentation/installation/installing-images/
  a. Don’t use NOOBS, skip to "Writing an image to the SD card". You may want to check out "Download the image".
  b. All necessary downloads are on the microSD card, so copy them over to the laptop you’re working on before you start.
2. Once you finish installing Raspbian, remount the disk. It should now be named "boot". Open the disk and make an empty folder named "ssh".
3. Insert the microSD card on the bottom of the Raspberry Pi, and connect it to a power source, which will turn it on.
4. Secure Shell (SSH) can be used for remote command-line login and remote command execution (in other words, you can access the Raspberry Pi from the terminal on your computer).
Raspberry Pi has SSH turned off as default, and making a folder named "ssh" automatically enables it on boot before deleting the empty folder.
5. To SSH into the Raspberry Pi
  a. Make sure both the Pi and your computer are on the same Wi-Fi.
  b. Open the terminal on the Pi, and enter "ifconfig".
  c. Take note of the IP address under the "wlan" section (in the form of 192.168.72.1).
  d. On your computer, type in "ssh pi@192.168.72.1".
  e. Type "raspberry" when it asks for a password.

## Installing Alexa onto the Pi
https://lifehacker.com/the-simplest-way-to-build-a-raspberry-pi-powered-amazon-1794218212

## Alexa Skills Tutorial
https://www.codecademy.com/learn/learn-alexa
