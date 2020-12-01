# Pi.GPIO
A module to control Raspberry Pi GPIO channels  
This repository is a clone of RPi.GPIO 0.7.0 by Ben Croston

This is compatible with RPi.GPIO with 3 additions:-

`read_gpio` Returns the GPIO level.  Returns HIGH=1=True or LOW=0=False  
`get_alt` Return the current GPIO mode (0-7)  
`get_pullupdn`  Return the current GPIO pullup pulldown on Pi4
