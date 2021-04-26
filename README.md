# CH341A_Modem

USB bus convert chip CH341A (+ USB RJ-45 50 meters extension adapter)

CH341A... ... ... It also supplies common MODEM communication signal on order to expand UART (or GPIO) for computer or upgrade common synchronous interface device (SPI) to USB bus directly. ... ... ... 

Wow! Just a 50 meters-wireline modem !!!!!!

First,

Install libusb api library : $sudo apt-get install libusb-1.0-0-dev

How to use:

$./ch341prog -a  : D4-pin pull-down(low) 

$./ch341prog -b  : D4-pin pull-up(high)
