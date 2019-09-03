# VL53L0X_NUCLEO
This VL53L0x library was modified from that of the Arduino version made by Pololu Corporation.
Firstly, constructor of the class was updated to cope with interrupt handling.
Secondly, API of Timer,InterruptIn and I2C class are accomodated to use mbed OS5.
Lastly, main program using this library can run without blocking.
 it is tested with NUCLEO F401RE board.
