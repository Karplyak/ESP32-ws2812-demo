# ESP32 WS2812 driver and rainbow demo

### Superceded by https://github.com/MartyMacGyver/ESP32-digital-RGB-LED-drivers
The new repo has more comprehensive demos and libraries for both ESP-IDF and Arduino-ESP32

<hr>

This is a driver for the WS2812 RGB LEDs which uses the RMT peripheral
on the ESP32. It uses interrupts from the RMT peripheral to keep the
buffer filled until all the bytes have been sent to the LED array.

<hr>

Original code by Chris Osborn <fozztexx@fozztexx.com>
For more information see http://insentricity.com/a.cl/268
