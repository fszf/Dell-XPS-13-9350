###Hello
This is a collection of current fixes and my pkgbuild.  I hope it helps someone.  If you like it, star this repo.  Thank you.

###Instructions
git clone - makepkg - pacman

###Notes
1. I've restructured my git to organize between different kernel versions.
2. Please remember to add in nvme into mkinitcpio modules for 4.4.x
3. Take a look at the pkgbuild.  It changes based on kernel and rc version
4. New subfolders created {archive, mainline, stable}.  Mainline is just for testing purposes and it seems kind of buggy so I will be using stable most of the time.
5. It seems the dock only works with 4.6 + dsmethod patch.  I guess I am stuck with it.

###UPDATE
As of two months ago I no longer am using the Mainline branch of linux.  I find that the intel-drm-nightly branch to have far better fixes that were not yet pushed into Mainline.  As we are on bleeding edge technology with TB3 and NVME etc, it just made more sense to use this branch.

However, there is a *new* nvme fix, which I've applied from 4.8-rc4.  Hence the recent update to the Mainline branch.  We are actively testing this fix on the arch forums https://bbs.archlinux.org/viewtopic.php?pid=1651473#p1651473

Join us!  
