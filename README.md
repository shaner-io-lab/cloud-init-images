# Cloud Init Config

## Raspberry Pis

### Download Server Image

1. [Download](https://cdimage.ubuntu.com/releases/jammy/release/) the Ubuntu preinstalled server image
    
    This image is bootable and can be flashed to SD cards for the Pi

1. 


sudo losetup -Pf --show ubuntu-image.img

lsblk

sudo mount /dev/loop0p1 /mnt/image



sudo umount /mnt/image
sudo losetup -d /dev/loop0



diskutil list
diskutil unmountDisk /dev/disk
sudo dd if=/path/to/your/image-file.img of=/dev/rdisk2 bs=1m status=progress