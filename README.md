# arch_chroot
```
truncate -s 10G./disk.img \
mkfs.ext4 disk.img
```
```
```

```
busybox losetup -f disk.img \
busybox losetup -a
```
```
busybox mount -t ext4 /dev/block/loop0 ./root/
```
```
busybox mount --bind /dev dev \
busybox mount --bind /proc proc
```
```

```
```
busybox chroot . /bin/bash -l
```
