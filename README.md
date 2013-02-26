rpi-linux-configs
=================

Configurations used to compile Raspberry Pi kernels w/PPS-GPIO.

The file names indicate branch names. 

For example:

* rpi-3.2.27.config can be used to build the rpi-3.2.27 raspberrypi/linux kernel branch

* rpi-3.6.y.config can be used to build up the rpi-3.6.y branch

These configurations were extracted from installations. If you ever need
to do this, just run the following from a shell:

	$ zcat /proc/config.gz > raspberry_pi_kernel.config
