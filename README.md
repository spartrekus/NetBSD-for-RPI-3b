# NetBSD-for-RPI-3b

wget http://nycdn.netbsd.org/pub/NetBSD-daily/netbsd-9/latest/evbarm-earmv7hf/binary/gzimg/armv7.img.gz


zcat armv7.img.gz  >  /dev/da0  

Advantages:
- NetBSD for all archs.
- Very performant for fast internet
- SVN working well.
- Large IBM fonts by default, which are large for good reading.
- 9.x beta, running well, need some pkgin.



bugs:
- The logitech gaming keyboard G213 has some issue, it can repeat the keys endlessly.
- USB Dongles sometimes. Archer T1 not working.
- No overscan by default



