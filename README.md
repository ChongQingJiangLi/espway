# ESPway
A segway-like balancing two-wheel robot built on ESP8266. It is controlled over WiFi via a HTML/JS GUI and a WebSocket. This is a work in progress.

## Building
This project is meant to be built against the ESP8266 NONOS SDK V2.0.0 20160810. You can use the [`esp-open-sdk` Makefile](https://github.com/pfalcon/esp-open-sdk) to setup the SDK and compiler toolchain. A Unix-based platform is recommended for building.

## Dependencies
The project utilizes some third-party libraries, in their respective folders:

* [libesphttpd](https://github.com/Spritetm/libesphttpd) by Jeroen Domburg (Spritetm) under "THE BEER-WARE LICENSE"
* [ESP8266_new_pwm](https://github.com/StefanBruens/ESP8266_new_pwm) by StefanBruens under GPLv2-or-later
* [esp8266ws2812i2s](https://github.com/cnlohr/esp8266ws2812i2s) by Charles Lohr, under the Espressif MIT License, permitting use on ESP8266 systems only

Kudos to all the above developers. Without these libraries this project wouldn't exist in such quality. The libraries are intentionally included in this repo because I had to make some minor adjustments to be able to build them under the NONOS SDK and strict `-Wall -Werror` compile flags.

## License
The project is licensed under GPLv3.

