Use `lsblk` -f to find out the UUIDs and filesystems of the partition you want to mount.

make mount directory

f.ex.

`sudo mkdir /media/WD1T`

Then go to /etc/fstab

and add

UUID=<uuid> <pathtomount> <filesystem> defaults 0 0

UUID=f49df586-3f5c-4e0e-915b-ac862db75ef3 /media/WD1T ext4 defaults 0 0