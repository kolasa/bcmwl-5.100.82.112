bcmwl-5.100.82.112
============

deb repository: bcmwl-kernel-source_5.100.82.112+bdcom-0ubuntu3_[i386 or amd64].deb

My driver patch for the Linux kernel >= 3.9.x ( and the next 3.10-rcx )

bcmwl-5.100.82.112 driver is the last good for BCM4313 card in my laptop (HP ProBook 6560b),

After install this driver on Ubuntu to prevent automatic update to version bcmwl-6.20, run the command:

sudo apt-mark hold bcmwl-kernel-source ( re-enable: hold -> unhold )

Why Driver 6.20 is not good for the card BCM4313 ?

Since the card interfere with my wifi network ( perhaps some other wifi network ) to work properly
but other connected devices work poorly or not at all.
