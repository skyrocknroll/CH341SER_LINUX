# CH341SER_LINUX
### nodemcu esp8266 serial linux driver with latest kernel support 
## ChangeLog 
 * 1.0 - 1.1   modified to solve transmition between ch341 and ch341
 * 1.1 - 1.2   Support high Linux kernel
## Instructions

## Note: 
      1.Please run followed executable programs as root privilege
      2.Current Driver support versions of linux kernel range from 2.6.25 to 4.4.x
      3.Current Driver support 32bits and 64bits linux systems

## Usage:
	(load or unload linux driver of CH34x)
	//compile 
	make
	//load ch34x chips driver
	make load
	//unload ch34x chips driver
	make unload


The updated code is taken from here 

`https://raw.githubusercontent.com/torvalds/linux/master/drivers/usb/serial/ch341.c`

