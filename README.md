Smart Blinds works with Alexa - Without any mqtt, rest, bridge, broker or HUB
--------------------------------------------
These smartblinds would not need any kind of SmartThings or hub. You can do this just by ESP8266 and a SG90 servo.

List of Things:
Servo Motor 9G
https://www.amazon.com/gp/product/B015H5AVZG/ref=oh_aui_detailpage_o00_s00?ie=UTF8&psc=1

ESP-12E - I choose this with development board (NodeMCU v3) that has a 5v output as well. So no need for any extra power supply
https://www.amazon.com/gp/product/B0741QFVJD/ref=oh_aui_detailpage_o00_s01?ie=UTF8&psc=1

And thats it! 

1- Connect the ESP chip with laptop
2 - Flash it with attached program (If you need information on how to program you ESP8266-12E, here is a good link : http://www.instructables.com/id/Programming-the-ESP8266-12E-using-Arduino-software/)
3 - Open Alexa app and search for Blinds under SmartThings (Or ask Alexa to search for devices)
4 - Attach the servo with the blinds (This depends upon the kind of setup you want. There are some resources available, just google it.)
5 - Enjoy your Smart Blinds ... ask Alexa to open and close :)


Also, if you don't want to run extra around and what this to 100% wife approved, get a solar power bank and attach that with ESP8266-12E.

Thanks to :

kakopappa
https://github.com/kakopappa/arduino-esp8266-alexa-wemo-switch

C_Hobbs
https://community.smartthings.com/t/release-absolute-simplest-esp8266-smart-blinds-no-mqtt-rest-bridge-or-broker-just-your-board-and-your-hub/48814

-----------------
