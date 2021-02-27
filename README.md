# Usradioguy-_Basic_Goestools_Image
This is a basic img file that can be installed onto a Raspberry Pi (4)
This requires it to be written directly onto micro sd of at least 32GB
using software such as Win32disk Imager or Balena Etcher


It includes Raspberry PI lite OS Release date: January 11th 2021
Kernel version: 5.4, Goestools with basic configuration, and Spyserver


To install, download the img file from my site at http://usradioguy.com/goestools/..., (the img file is about 16GB, far to large for a github repository)
Then, using Win32 Disk Imager or Balena Etcher
Write the image to a micro SD card of at least 32GB.

Then, if you plan on using wifi, you will need to edite the wpa_supplicant.conf file
and enter in your own WIFI name and password, example:

    country=US

    ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev

    update_config=1

    network={

    ssid="YOURWIFINETWORKNAME"

    psk="YOURWIFINETWORKPASsWORD"

    }

___________

Install the sd card into the raspberry pi and power it on.
From this point you will need to ssh into the PI with puTTY.

You will also need to configure the goesrecv.conf to match your dongle.
It is currently configured for a Nooelec SmarTee XTR.

**Further details and dish setup can be found on my site at http://usradioguy.com**

![usradioguysmall](https://user-images.githubusercontent.com/47005123/109399000-ba295380-7905-11eb-84a3-493262bbd184.gif)
