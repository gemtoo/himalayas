# Himalayas Gentoo overlay
## Package descriptions
This overlay contains packages with my patches.
1. `media-gfx/pimp` is a based version of `GIMP` image editor. Where all occurrencies of `GIMP` are recursively replaced with `PIMP` during the build time. Because `GIMP` is a wack name and its a disgrace to use image editor with such ugly name. `PIMP` stands for "Perfect Image Manipulation Program". Because the only wrong part about `GIMP` was its name.
2. `net-misc/subnetcalc` is a CLI subnet calculator that is not present in default Gentoo repos.
3. `sys-boot/grub` is a patched version of `GRUB` bootloader that has been silenced the fuck up. No more 'Welcome to GRUB!' messages or some other meaningless trash in the console.