# pwm2usb

Porting any generic PWM based RC reciever as HID-gamepads with STM32F427 MCU. Currently supports up to 4 channels.

## Pin Assignment (for PWM signal outputs)

Channel 1 --> PA0  
Channel 2 --> PH9  
Channel 3 --> PA1  
Channel 4 --> PA2

## How To Build

simply run `make` at the project root and you will see `build/pwm2usb.elf` and `build/pwm2usb.bin` ready to go.

## How to Flash

see [here](https://github.com/illini-robomaster/iRM_Embedded_2018/blob/master/tutorials/FLASH.md)

