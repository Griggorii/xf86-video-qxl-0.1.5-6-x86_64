# xf86-video-qxl-0.1.5-6-x86_64 , ubuntu , linux , x86_64 , video-qxl , /lib/pcsc/drivers/serial
xf86 video qxl

Rebuild port view https://youtu.be/GBAtFq2aD8E

xorg-include.zip inpack folder spice xorg copy to /usr/include

$ sudo cp -r  'spice' 'xorg' /usr/include

$ sudo cp spiceqxl.xorg.conf /etc/X11

$ sudo tar xvpf include_xspice_xorg.tar.xz -C /

$ sudo rm /usr/include/pciaccess.h

$ sudo ln -s /usr/bin/x86_64-linux-gnu-ar /usr/bin/ar

$ sudo cp libc_nonshared.a /usr/lib/x86_64-linux-gnu/

$ sudo apt update

$ sudo apt install libspice-server-dev libspice-protocol-dev libxfont-dev libdrm-dev -y

xf86-video-qxl-0.1.5_20.04.zip inpack /tmp run terminal /tmp/xf86-video-qxl-0.1.5 command

$ make

$ sudo make install

$ sudo strip -s '/lib/xorg/modules/drivers/qxl_drv.so'

$ sudo strip -s '/lib/xorg/modules/drivers/spiceqxl_drv.so'

Setting flags editor#

$ sudo nano /etc/X11/spiceqxl.xorg.conf

Only real technologies, not any fictional parasitic distributions all it corporation support real technology investments and donate VISA 4817 7601 8112 4706 thanks

Dev redefvlopment generation .pot remove example:

$ sudo apt purge libfreetype-dev libfreetype6-dev libpng-dev libpthread-stubs0-dev libspice-protocol-dev libspice-server-dev libx11-dev libxau-dev libxcb1-dev libxdmcp-dev libxfont-dev x11proto-core-dev x11proto-dev xorg-sgml-doctools xtrans-dev -y
