# ATmega1284P_Board
ATmega1284P board design is based on the [MightyCore](https://github.com/MCUdude/MightyCore).

The board features fairly easy to hand solder components, such as 0805 resistors, capacitors and LEDs, and it is breadboard friendly (100 mil spacing pin headers) with an orderly pin arrangement [(0 to 23, and A0 to A7)](https://camo.githubusercontent.com/318afd7cb36e720ea851fb34409d54c36701d0300eade1ba0faea744f00fc5db/68747470733a2f2f692e696d6775722e636f6d2f4b3334785a62342e6a7067) of the TQFP-44 package. 

The programming connector is a standard FTDI USB-UART adapter pin-out. The solder jumper (JP1) is closed by default. The board can be powered from the breadboard pin headers or the FTDI programming header. Using an FTDI TTL-232RG-VIP USB-UART adapter, the TTL voltage (Vttl) would be the same as the Vcc.

The Bill of Materials is also included (see file ATmega1284P.csv).
![Image](https://github.com/DCelectronics/ATmega1284P_Board/blob/main/ATMEGA1284P_FRONT.png)
![Image](https://github.com/DCelectronics/ATmega1284P_Board/blob/main/ATMEGA1284P_BACK.png)
