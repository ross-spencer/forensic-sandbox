# FAT12 Various Modes

Following the re-format, and zero-ing of the 1.44" disk, the following images
were created with the floppy disk mounted, using DD on linux with the following
command:

    dd if=/dev/sdb of=forensic-sandbox/fat12-various-modes/<img name>

The images were created in the following order by way of seeing how the state
of the disk evolved over time through various operations. What is recorded, and
The impact on indexes and so forth.

* fs-empty-disk.img
* fs-one-file.img
* fs-two-files.img
* fs-folder-images.img
* fs-manually-deleted-files.img
* fs-all-files-rewritten.img

## Mounting the disks

* Create a media directory: `sudo mkdir /media/diskette`
* Mount the disk using: `sudo mount -o loop <img-name> /media/diskette/`
* Have a look what's on there: `ls /media/diskette/`
* Safely unmount using: `sudo umount /media/diskette`

## FAT12 Spec Document

I do not hold the license for the FAT12 specification below, it comes from the
Rose-Hulman Institute of Technology.

http://www.disc.ua.es/~gil/FAT12Description.pdf
