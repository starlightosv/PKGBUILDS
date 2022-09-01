# EndeavourOS systemd-boot

**original source:** https://gitlab.com/dalto.8/eos-systemd-boot

**Repository for EndeavourOS:** https://github.com/endeavouros-team/eos-systemd-boot

A package to enable systemd-boot automation using kernel-install on EndeavourOS

The hooks were adapted from the AUR package originally written by Tilmann Meyer

**The package basically does a few things:**

* Masks the mkinitcpio hooks as they are redundant with kernel-install
* Installs hooks to automate the installation and removal of kernels using kernel-install
* Adds support for generating fallback images to kernel-install
