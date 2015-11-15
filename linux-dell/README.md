this is a testing branch with the bcrm4350 patch included
move the .bin file to /lib/firmware/brcm

to compile do below in stock arch:
makepkg -sf --skipinteg

Recommended: Use modprobed-db and edit pkgbuild to utilize it.  Will shave down compiling from 45+min to 10min or less.

Patches included:
1-bcrm4350 firmware
2-patch fix for [drm:intel_dp_aux_ch [i915]] *ERROR* dp aux hw did not signal timeout (has irq:1)!

