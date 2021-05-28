# xf86-video-qxl-0.1.5-6-x86_64 , ubuntu , linux , x86_64 , video-qxl
xf86 video qxl

Rebuild port view https://youtu.be/GBAtFq2aD8E

xorg-include.zip inpack sudo cp -r  'spice' 'xorg' /usr/include

xf86-video-qxl-0.1.5.zip inpack /tmp

$ make

$ sudo make install

$  sudo strip -s '/lib/xorg/modules/drivers/qxl_drv.so'
