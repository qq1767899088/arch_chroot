# arch_chroot
```
busybox losetup -f disk.img
busybox losetup -a
```
```
busybox mount -t ext4 /dev/block/loop0 ./root/
```
```
busybox mount --bind /dev dev
busybox mount --bind /proc proc
```
```

```
```
busybox chroot . /bin/bash -l
```
