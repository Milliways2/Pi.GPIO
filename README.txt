This package provides a class to control the GPIO on a Raspberry Pi.

Note that this module is unsuitable for real-time or timing critical applications.  This is because you
can not predict when Python will be busy garbage collecting.  It also runs under the Linux kernel which
is not suitable for real time applications - it is multitasking O/S and another process may be given
priority over the CPU, causing jitter in your program.

Note that the current release does not support SPI, I2C or serial functionality on the Pi.

Software PWM is available to use on all channels.

NOTE hardware PWM and PAD configuration require root access (use sudo).

Pi.GPIO is backwards compatible with RPi.GPIO and includes extended functionality.

For examples and documentation of RPi.GPIO, visit http://sourceforge.net/p/raspberry-gpio-python/wiki/Home/

To produce html documentation for this module run: python3 -m pydoc -w Pi.GPIO
