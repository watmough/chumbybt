Huan's Public Bittorrent Sync + Webkit Chumby release
=============

You would have to do all the customizations on on-device folder. 

Edit network_config for your wifi network if you want to connect the Chumby to your wifi network. The sample config file is on on_device/psp folder. Remove .sample to create our own.

Then, if you need to mount a nfs share, copy nfsmount.sample to nfsmount and edit accordingly.

Then, use ./repack-update.sh to pack the new update pack, it will unpack the usual chumby stuff overlay our customizations on top of it.

Copy the copy-to-flash-drive folder to the ROOT of a USB flash drive.

Plug the USB flash drive to the back of the chumby and press THE SCREEN when the chumby is booting up. You'll be presented with a choice of upgrading the chumby. Enjoy.
