# under construction

# JC4827W543R
a.k.a. cheap-black-device (CBD)

### about the device
* [purchased at](https://www.aliexpress.com/item/1005006729377800.html)
* [manufacturer](http://www.jczn1688.com/)

### intention
* developing using arduino framework with visual code and platformio
* exploring the device by developing a toy game
* developing a platform-independent toy game engine featuring:
  - smooth scrolling tile map
  - sprites in layers with pixel precision on-screen collision detection
  - intuitive definition of game objects and logic
  - decent performance, ~30 frames per second on the device

### development environment
* Visual Code 1.89.0
* PlatformIO 6.1.15
* Espressif 32 (6.6.0) > Espressif ESP32 Dev Module
* packages:
  - framework-arduinoespressif32 @ 3.20014.231204 (2.0.14) 
  - tool-esptoolpy @ 1.40501.0 (4.5.1) 
  - toolchain-xtensa-esp32 @ 8.4.0+2021r2-patch5
* dependencies:
  - https://github.com/calint/Arduino_GFX#2024-05-06--21-57
  - https://github.com/PaulStoffregen/XPT2046_Touchscreen#v1.4
