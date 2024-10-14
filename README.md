# Mesh-Tab
The iPhone of Meshtastic devices instead of the BlackBerry


## List of things that needs to be done

- [ ] add support for the display
- [ ] deside on a lora module 
- [ ] choose gps
- [X] choose battery charging ic

## Target Hardware

The following hardware is to be considered as targets till better alternatives are found.

- ESP32 board
  - [Vision Master T190 board](https://heltec.org/project/mesh-node-t114/) - This is a temporary board being considered for testing since it has all the same specs as the Tdeck, but eventually, we'll make our own.
- Touch Display 3 inch or larger
  - [2.4 inch TFT LCD Shield Touch Panel Display Module](https://www.aliexpress.us/item/3256802101900425.html) - Since it uses the same driver as the Tdeck, it will make it easier to incorporate into the current Tdeck firmware.
- GPS module
  - [L76K GPS](https://www.waveshare.com/wiki/L76K_GPS_Module)- Due to its Ultra-low power consumption, it should be a good choice to use. 
- Powerswitch - A requirement to protect the battery and ensure the device is ready to use when needed.
- Wake button - To be considered to turn the screen on after sleep as well as additional functions.
- Buzzer - Great for notifications.
- I2C - Allows additional interfaces for future expansion or functionalities a user needs.
