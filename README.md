# h4x0rs-little-helper
A RP2040 based hardware debug tool with UART, Touchscreen and LiPo Boost Circuit

![image](https://user-images.githubusercontent.com/6614616/192500275-f1a54059-b106-4018-8d1f-6d3cc863b05c.png)

# Specifications
* RP2040 Dual-Core Cortex M0+ MCU
* 2MB Flash
* USB Type-C for programming, host and device mode
* USB Type-A for usb host (keyboard, mass storage, ..)
* ILI9341 Display with XPT2046 Display
* 8-bit I/O Port
* UART Header
* LiPo Boost Circuit (for 5V USB Host Power + MCU)
* 8 LEDs for byte display and 1 LED for UART RX
* 4 Buttons (Baud up, Baud down, 2x User Buttons)
* AW9523 I2C Port Expander

# Usecases
* UART Serial Terminal (VT100)
* MIDI monitor (with clock jitter measurement)
* Simple I/O monitor / logic analyser
* Stand-alone I2C scanner and tester
* SPI sniffer

# Behind the scenes
* TFT_eSPI as display driver
* LVGL for GUI
* PIO for 8-bit I/O
* FATFS for flash filesystem
* TinyUSB for USB Host and Device
