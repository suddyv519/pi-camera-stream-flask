# Bluetooth RC Surveillance Car

## Team Members

- Sudharshan Venkatesh
- Jeremy Gibson

## Description
This RC car is remote controllable via the Adafruit Bluetooth app for directional control. There is a Raspberry Pi 3B attached as a slave device with the camera module, which streams live video to a web application.

## Hardware
- Mbed LPC1768 (1)
- Hobby DC Gear Motor - 140 rpm (2)
- Shadow robot chassis (1)
- Wheel - 65mm (2)
- Smartfun Dual H Bridge (1)
- Adafruit Bluefruit LE UART module (1)
- Battery pack/holder (2)
- Smartphone with Adafruit Bluetooth companion app (1)

### Pinouts
|Mbed|Dual H-Bridge|DC Motors|Battery|
|----|-------------|---------|-------|
|Vin |    Vmot     |         |   +   |
|Gnd|  Gnd        |          |   -   |
|Vout| Vcc |
|p21 |PWMB|
|p22|BIN2|
|p23|BIN1|
|p24|AIN1|
|p25|AIN2|
|p26|PWMA|
|Vout|/STBY|
|    |A01 |left-red|
|    |A02|left-black|
|    |B02|right-black|
|    |B01|right-red|


# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)


