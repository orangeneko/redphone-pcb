## About
Redphone - simple handmade open source mobile phone

## PCB
![logo](./doc/img/pcb_top.png)
![logo](./doc/img/pcb_bottom.png)

## Hardware
* Cortex M4 STM32F429
* FPGA EP4CE6E22
* 800x480 LCD on RM68120 controller
* Capasitive LG P715 touch screen
* Memory (SDRAM MT48LC16M16A2TG, MicroSD, EEPROM 24LC256)
* Audio system based on (WM8903, MP34DT01 mic, headphone, ring, minijack)
* Wi-Fi on ESP8266
* GSM & Bluetooth on SIM800C
* NRF24L01+
* Sensors (MPU9250, APDS-9960, BME280, HDC1000, DS18B20)
* GPS MC-1010-G
* OV26400 camera & led
* Power domain (SGS4 Battery, MAX8903A charger, TPS63001, TPS63000, MAX8815A, LP3990TL, PT4181)
* USB type-C for connection to JTAG & SWD

## Software
* Latest linux kernel
* Firmware based on FreeRTOS, lwIP and Graphix (GUI C++ library)
