##FAT12 Various Modes

Following the re-format, and zero-ing of the 1.44" disk, the following images
were created using DD on linux with the following command:

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

###FAT12 Spec Document

I do not hold the license for this, it comes from the Rose-Hulman Institute of Technology. 
