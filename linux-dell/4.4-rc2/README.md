Broadcom manual firmware no longer needed as of 4.4.x
You must add nvme into modules for mkinitcpio

To compile do below in stock arch:
makepkg -sf --skipinteg

Recommended: Use modprobed-db and edit pkgbuild to utilize it.  Will shave down compiling from 45+min to 10min or less.

Patches included:
2-patch fix for [drm:intel_dp_aux_ch [i915]] *ERROR* dp aux hw did not signal timeout (has irq:1)!
3-white noise fix where you hear status after suspend and resume.  this fix will merge into 4.4-rc3 kernel
4-libcfs-fix startin 4.4 rc2 we need to have this patched to continue building kernel
