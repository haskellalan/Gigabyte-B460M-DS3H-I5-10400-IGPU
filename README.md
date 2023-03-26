# Gigabyte-B460M-DS3H-V1-I5-10400-IGPU Hackintosh


My setup:

-i5 10400 (Comet Lake)

-Gigabyte B460M-DS3H V1 

-BIOS version: F5

-UHD 630 IGPU

-16 GB RAM

-256 GB NVME SSD

-512 GB SATA HDD

-NVIDIA GTX 1660TI (Disabled on Hackintosh, Turing GPUs are not supported. Used only for windows dual boot)



HDMI and USB mapped

Catalina and Big Sur tested at the moment.

The config.plist is configured to run UHD 630 as the primary display, the HDMI cable must be connected to the motherboard in order to get video and be able to boot. 

If you have an uncompatible discrete GPU and want to run windows dual boot, you will need to add -wegnoegpu to the boot arguments, also, according to what OS you want to boot, you will need to change BIOS settings and switch the HDMI cable from motherboard to gpu and vice versa. 
I recommend saving two BIOS profiles, one for hackintosh and one for Windows.

BIOS settins for Hackintosh:

-in progress
