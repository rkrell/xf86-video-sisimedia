# xf86-video-sisimedia
X11 video driver for SiS 671/771 cards

This driver is written by Thomas Winischhofer and is a (nearly) complete re-write of a driver written for the SiS6326 and SiS530 by  Alan Hourihane and others.

This is especially dedicated to all folks reanimating old laptops with SIS Mirage S3 graphics cards, like the Fujitsu Esprimo V5335.

I picked up the original source code and applied all patches to avoid a patching hell during packaging.

Several patches include work contributed to the Arch Linux distribution.

References:
- http://www.linuxconsulting.ro/xorg-drivers/
  The original project derivated from the original SIS drivers.
- https://aur.archlinux.org/packages/xf86-video-sisimedia/
  The package at Arch Linux this code received several patches from, even though if they were partly modified.
- https://build.opensuse.org/package/show/home:renekrell/xf86-video-sisimedia
  My OBS project to package this code for openSUSE.
