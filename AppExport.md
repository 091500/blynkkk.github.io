# App Export

## Firmware for ESP8266, NodeMCU, BlynkBoard, etc.

#### Prepare development environment
1. Install [Arduino IDE](https://www.arduino.cc/en/Main/Software)
2. Install [Blynk Library](https://github.com/blynkkk/blynk-library/releases/latest)
3. Install [ESP8266 core for Arduino](https://github.com/esp8266/Arduino#installing-with-boards-manager)
4. If your board has a NeoPixel RGB LED, install [Adafruit NeoPixel](https://github.com/adafruit/Adafruit_NeoPixel) library from Library Manager

#### Build your Firmware
1. Open our example in Arduino IDE: ```File -> Examples -> Blynk -> Provisioning -> Blynk_ESP8266```
2. Open ```Settings.h``` tab.
3. Configure your firmware:
  * ```BOARD_NAME``` - ...
  * ```BOARD_VENDOR``` - ...
  * ```PRODUCT_WIFI_SSID``` - ...
  
#### Upload firmare
1. Select your board type: ```Tools -> Board -> [Your Board]```
2. Select your port: ```Tools -> Port -> [...]```
3. Verify and Upload!

Note that for Blynk Board, you can select board type ```NodeMCU 1.0```.
