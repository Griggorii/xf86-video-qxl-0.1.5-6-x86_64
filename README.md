# xf86-video-qxl-0.1.5-6-x86_64 , ubuntu , linux , x86_64 , video-qxl
xf86 video qxl

Rebuild port view https://youtu.be/GBAtFq2aD8E

xorg-include.zip inpack folder spice xorg copy to /usr/include

$ sudo cp -r  'spice' 'xorg' /usr/include

$ sudo rm /usr/include/pciaccess.h

xf86-video-qxl-0.1.5.zip inpack /tmp run terminal /tmp/xf86-video-qxl-0.1.5 command

$ make

$ sudo make install

$  sudo strip -s '/lib/xorg/modules/drivers/qxl_drv.so'
