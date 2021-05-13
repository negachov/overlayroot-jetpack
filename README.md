## pre requirement

### install package
```
# apt install overlayroot
```

### configuration
please edit /etc/overlayroot.conf or /etc/overlayroot.local.conf

ex)
```
# cat /etc/overlayroot.conf
overlayroot="tmpfs"
```

## replacing /boot/initrd
```
# cd overlayroot-jetpack
# ./update-initramfs-jetpack
# reboot
```
