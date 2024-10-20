# Mesh-Tab
The iPhone of Meshtastic devices instead of the BlackBerry

## Target Hardware

The following hardware is to be considered as targets till better alternatives are found.

- ESP32 board
  - [Vision Master T190 board](https://heltec.org/project/mesh-node-t114/) - This is a temporary board being considered for testing since it has all the same specs as the Tdeck, but eventually, we'll make our own.
- Nrf52 board
  - [promicro](https://vi.aliexpress.com/item/1005007040333351.html)
- Touch Display 3 inch or larger
  - [2.4 inch TFT LCD Shield Touch Panel Display Module](https://www.aliexpress.us/item/3256802101900425.html) - Since it uses the same driver as the Tdeck, it will make it easier to incorporate into the current Tdeck firmware.
  - [ESP-32-S3 5-inch](https://vi.aliexpress.com/item/1005006715581887.html) - Integrated esp32 to handle the ui
  - [ESP32-S3 Development Board 4.0 "480 * 480 Smart Display](https://vi.aliexpress.com/item/1005006478501734.html)  - Recommended by the UI maker 😅 also has integrated esp32 to handle the UI (no support yet but supposedly not hard to add)
  - [T-Display S3 Pro](https://www.lilygo.cc/products/t-display-s3-pro?variant=43111690141877) -  iPhone like T-Deck replacement
- Lora Module
  - [Ra-01sh](https://vi.aliexpress.com/item/1005002561194884.html)
  - [Wio-SX1262](https://www.seeedstudio.com/Wio-SX1262-Wireless-Module-p-5981.html)
- GPS module
  - [L76K GPS](https://www.waveshare.com/wiki/L76K_GPS_Module)- Due to its Ultra-low power consumption, it should be a good choice to use. 
- Powerswitch - A requirement to protect the battery and ensure the device is ready to use when needed.
- Wake button - To be considered to turn the screen on after sleep as well as additional functions.
- Buzzer - Great for notifications.
- I2C - Allows additional interfaces for future expansion or functionalities a user needs.
