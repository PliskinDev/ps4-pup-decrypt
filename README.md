# ps4-pup-decrypt

A utility to invoke the PS4 kernel to decrypt the contents of an update file.

The default (hardcoded) operation is to decrypt /mnt/usb0/PS4UPDATE.PUP.

This will output a number of files (depending if a normal or a recovery update):

    /mnt/usb0/PS4UPDATE1.PUP.dec
    /mnt/usb0/PS4UPDATE2.PUP.dec
    /mnt/usb0/PS4UPDATE3.PUP.dec
    /mnt/usb0/PS4UPDATE4.PUP.dec
    
    These decrypted updates can then be unpacked using
    https://github.com/mizdx/ps4-pup-unpack/
