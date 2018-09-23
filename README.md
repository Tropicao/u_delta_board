# uDelta printer board

## What is it
This board aims to upgrade a 3D printer board to make it autonomous. It is used to drive a 3D printer remotely (without a traditionnal host computer connected), with the following features :
* embedded hacker board running Octoprint
* board output to pilot drive power source to switch it on/off remotely
* Slicer integrated
* interface to plug a webcam

## What hardware is needed
The current version of the board is designed to integrate a [NanoPi Duo](http://wiki.friendlyarm.com/wiki/index.php/NanoPi_Duo) from Friendly Arm. It is an inexpensive ARM board based on Allwinner processor, with following characteristics :
* ARM Quad A7 (Allwinner H2+)
* 512MB MB
* OS image on Micro TF card
* Embedded Wifi
* Various peripherals : USB, Ethernet, serial audio input/output, SPI, I2C, gpios, etc

## Notes
Git versionning done with the help of the guide from [plotkicadsch](
https://jnavila.github.io/plotkicadsch/).
