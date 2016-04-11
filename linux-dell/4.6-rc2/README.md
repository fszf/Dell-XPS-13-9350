## linux 4.6-rc2
## dsmethod.patch
#This patch fixes the WD15 dock WOO HOO

Please consider editing the pkgbuild to enable modprobed-db.  
For Arch users install this from aur
https://aur.archlinux.org/packages/modprobed-db
And read the archwiki:
https://wiki.archlinux.org/index.php/Modprobed-db

Just remember to plug in all your devices and run it. This will speed up your compile time down to 8 minutes.,

##intelfix
#I've been noticing some flickering going on and decided to use this patch
https://patchwork.freedesktop.org/patch/66697/

So far I haven't experienced the flicker but I will update as I go.
