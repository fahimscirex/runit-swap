# runit-swap
Script for auto-creation and mounting of: zram swaps, swap files (through loop) devices, swap partitions.
It is configurable in /etc/runit-swap.conf.
Source:
```
/etc/runit-swap.conf
/usr/bin/runit-swap
/etc/runit/sv/swap/run
/etc/runit/sv/swap/finish
```
Using:
```
# ln -s /etc/runit/sv/swap /run/runit/service
```

Note:
=======
Dependence: util-linux >= 2.26
