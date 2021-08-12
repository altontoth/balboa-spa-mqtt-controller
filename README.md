# balboa-spa-mqtt-controller
 Balboa Spa MQTT Controller on NodeMCU v3
 
This project is derived from and inspired by the project located at https://github.com/NickB1/balboa-spa-mqtt-controller/

---

## What does it do?

This code accompanies DIY circuitry that allows for the modernization of an older Balboa-based spa (hot tub). This project will not work with all Balboa mainboard / top side controller combinations (non-wifi models). The controller is designed to sit in between the top side control and the hot tub controllers, and intercept serial communications between both components of your spa system. Once set-up, it is intended to allow you to connect your spa to a MQTT broker such as AdafruitIO to allow for remote operation and monitoring of the spa. Once you have the spa successfully integrated with MQTT services, you can expand that functionality into OpenHAB or Hass.io, etc. 

---

## Installation

1) Download the project and unzip. 
2) Ensure that you have the Adafruit MQTT libraries installed, as well as the NodeMCU board configurations.
3) Open the balboa-spa-mqtt-controller.ino file in the Arduino editor, and ensure that it has also opened up the additional 4 files. If not, you may have to go Sketch > Add File to add each file.
4) Ensure that your NodeMCU settings are set to match the board you are using. Sample settings can be found in the folder.
5) Upload the project to your NodeMCU. To ensure there are no issues, it is recommended that you remove the NodeMCU from the interface board before flashing.
6) Connect to the serial monitor to verify connectivity.
7) Install / Reinstall the NodeMCU into the inferface board, and connect the interface board to your hot tub.
8) Enjoy!

---

### Credits

* https://github.com/NickB1/balboa-spa-mqtt-controller/

---
