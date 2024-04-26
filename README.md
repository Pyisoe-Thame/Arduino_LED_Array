
# 8x24 LED Array, Atmega328PB

This is my PCB Design practice project. ATmega328PB is the upgraded version of ATmega328P which is no longer recommeded for new design at this time. Instead Atmega328PB is in production of microchip with more or less the same price. The distinct feature of this MCU that I noticed is it has an extra SPI protocol and some expansion on memories.

The circuit 4 74595A shift registers; one for 8 LED rows and the others for the columns.
In the circuit I used all four 595 chips have the same CLK pin connect together and 3 of them are daisy-chained to shift a total of 24 columns, the rest one is used for columns each pin cooperated
by a PNP transistor.

While it may not be able to give HIGH to all the LEDs at once, you can use time division multiplexing to achieve the same visual effect by lighting each led at multiple time slots at high frequency.

## Features

- Arudino compatible Atmega328PB-AU
- DC Jack to 5V AMS1117
- Programming with ICSP
- 74HC595A shift registers
- 24 columns, 8 rows of output LEDs


## Screenshots

<p align="center">Front View</p>
![Front View](https://github.com/Pyisoe-Thame/Arduino_LED_Array/blob/main/images/PCB%20Preview%20(F).JPG)

<p align="center">Back View</p>
![Back View](https://github.com/Pyisoe-Thame/Arduino_LED_Array/blob/main/images/PCB%20Preview%20(B).JPG)

<p align="center">Preview with Components</p>
![Preview with Components](https://github.com/Pyisoe-Thame/Arduino_LED_Array/blob/main/images/Preview%20with%20Components.JPG)



## License

[MIT](https://choosealicense.com/licenses/mit/)

