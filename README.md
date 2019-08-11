Realtek 8812au driver for linux kernel 4.15
==============

** THERE IS ABSOLUTELY NO WARRANTY **
If you decide to use it, you are responsible for any consequences.
See the GNU General Public License for more details.

What is it?
--------------

The original driver 8812au by Realtek for Linux kernel version 3 has been modified to support kernel 4.15

It was tried with USB adapter TP-Link Model No. Archer T4UH (2357:010e) with vanilla kernel 4.15.14 on Gentoo.

Also successfully tried with Zyxel NWD6605 (0586:3426) on Ubuntu Bionic with kernel 4.15.0-55-generic.

It might also work for other USB adapters:
0BDA:8812
0BDA:881A
0BDA:881B
0BDA:881C
050D:1106
2001:330E
7392:A822
0DF6:0074
04BB:0952
0789:016E
0409:0408
0B05:17D2
0E66:0022
2001:3313
1058:0632
1740:0100
2019:AB30
07B8:8812
2001:3315
2001:3316
2357:0101
2357:0103
2357:010D
2357:010E
2357:010F

Instalation
--------------

make && sudo make install

