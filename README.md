# ProcessFirmata
A specific implementation of Firmata on arduino for process control.

Goals:
1) maintain basic firmata compatability surrounding digital and analog IO
2) provide mechanisms for measuring, filtering and transmitting process control variables (temperature, flow, pressure etc) from SPI, I2C, 1-wire and analog inputs
3) provision for local control loops (Set/read parameters and internal values)
4) LCD and rotary encoder to set/monitor control loops
5) Custom NodeRed blocks to communicate with Process Firmata
