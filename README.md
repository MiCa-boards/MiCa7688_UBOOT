# MiCa7688-uboot
This feeds holds the UBoot bootloader source code for the MiCa7688

# Compile

Start by cloning the tree

`git clone https://github.com/emavap/MiCa7688_UBOOT.git`

We need to install the cross toolchain required to build the source

`sudo tar xjf buildroot-gcc342.tar.bz2 -C /opt/`

Finally we can start building the source

`make`

Notes: Uboot firmware is uboot.bin NOT uboot.img
