mt7628 u-boot from Ralink modified to open webpage on ethernet port
=======
Webpage can be triggered by gpio 38

DO NOT BUILD WITH GCC > 3.5.2 !!!

Suitable tool chain is available in toolchain

For VoCore2 run make menuconfig in Uboot directory, 
chip ID to mt7628, memory type to DDR2 and DRAM Component to 512 Mb

Credits:

Wolfgang Denk and all the others that work on Das U-boot, even though this project is based on a pre-historic version of u-boot their work is incredible.

Pepe2k whose webfailsafe for AR93xx routers was plagarized shamelessly in my work.

Manfeel whose blog gave me very helpful hints about byte order. I wish I had found this much earlier in my work since I duplicated much of his other work the hard way.
http://blog.csdn.net/manfeel/article/details/13096075

Vonger who gave us the VoCore and VoCore2

I take responsibility for the kludgy, ugly code you may find here, but it does work for me.
