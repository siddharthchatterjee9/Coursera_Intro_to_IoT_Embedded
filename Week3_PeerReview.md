*All copyrights and licensing reserved; Chatterjee Solutions*
# Project Title - "Microcontroller Datasheet"
## PART 1. _Question:_ Research two microcontrollers and provide information about them from their datasheets. 
*There are several microcontroller manufacturers which you can investigate including Atmel, Microchip, Freescale, TI, etc.* 
*For each microcontroller, report the following information. (Be sure to include a link to an online reference where you found this information.)*
## PART 1 - _Solution:_ 
### 1st Microcontroller: NODE MCU ESP8266 https://components101.com/development-boards/nodemcu-esp8266-pinout-features-and-datasheet
1. Clock frequency: 80MHz to 160 MHz adjustable clock frequency
2. Bitwidth of the datapath: Tensilica Xtensa **32-bit** LX106 RISC microprocessor
3. Size of Flash Memory: 4 MB
4. Number of pins: Digital I/O Pins (DIO)-16, Analog Input Pins (ADC)-1
5. Does the microcontroller contain an Analog-to-Digital Converter? If so, how many bits of precision does it have? Yes, 1
### 2nd Microcontroller: Renesas RX71M  https://www.renesas.com/eu/en/products/microcontrollers-microprocessors/rx/rx700/rx71m.html#productInfo
1. Clock frequency: 240 MHz
2. Bitwidth of the datapath: 32-bit
3. Size of Flash Memory: 2 MB / 2.5 MB / 3 MB / 4 MB
4. Number of pins: 177-pin TFLGA, 176-pin LFBGA, 176-pin LQFP
5. Does the microcontroller contain an Analog-to-Digital Converter? If so, how many bits of precision does it have? Yes, 12 bit ADC
## PART 2. _Question:_ Research the Arduino and Raspberry Pi platforms. 
1. *Indicate if there are operating systems which can be used on each platform. If there are, list those operating systems.*
2. *State whether the operating systems are open source or not.* 
## PART 2 - _Solution:_
### For NODE MCU ESP8266/Tensilica Xtensa Family
1. Arduino-None, Raspberry Pi-None, The platform is basically built on the Espressif Non-OS SDK, FreeRTOS, Nucleus+, ThreadX, uC/OS-II/OS-III, Zephyr, or
embedded Linux operating systems  
2. Yes, it is based on open-source platform-RTOS SDK.
### For Renesas RX71M
1. Arduino: None, Raspberry Pi: Yes, The platform is based on RI600V4 Real-time OS for RX Family, conforming to the µITRON4.0 Specification, the predominant Real-time OS for embedded systems in Japan.
2. No, it is not open-source and the release info of different OS versions conforms to the µITRON4.0 Specification, the representative OS architecture for embedded control.
