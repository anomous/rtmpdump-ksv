```RTMP Dump v2.4
(C) 2009 Andrej Stepanchuk
(C) 2009-2011 Howard Chu
(C) 2010 2a665470ced7adb7156fcef47f8199a6371c117b8a79e399a2771e0b36384090
(C) 2011 33ae1ce77301f4b4494faaa5f609f3c48b9dcf82
License: GPLv2
librtmp license: LGPLv2.1
http://rtmpdump.mplayerhq.hu/
```

## rtmpdump-ksv

An easy way to install rtmpdump with KSV's patches.

```
git clone https://github.com/chopraaa/rtmpdump-ksv.git

cd rtmpdump-ksv

patch -p0 -i Patch.diff

make

make install prefix=/usr

cd ../ && rm -rf rtmpdump-ksv
```
