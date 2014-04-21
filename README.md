##Antiforensics for Udev##

A series of scripts for Udev that will detect insertion of a mouse jiggler and
lock xfce.

###Usage###
* Place the script `udev-lock` in `/usr/local/bin/`
* Place the file `72-security.rules` in `/etc/udev/rules.d/`
* Rebooot

When a mouse jiggler is inserted, the screen will lock (xscreensaver).

###Notes###
Udev does some of this by default, but it doesn't have the USB ids for all
relevant devices.
