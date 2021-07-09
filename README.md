# remastering-linux-debian-10


2021 - 6 - 9

install remaster-iso
sudo remaster-iso

usage :
1. sudo su (remaster-iso mush be run with root user)
2. remaster-extract -i debian_live_10.iso (This command will extract data from the debian iso file, and you can edit certain parts such as boot background, menu.cfg, etc.)
3. remaster-squashfs-editor (This command will allow you to install the specific packages you want to install on your remastering linux, and replace some files as well.)
4. After you've finished installing everything you need, you can run the command exit, or ctrl + D to exit the chroot, and select Y to save the changes to the linux you're remastering.
5. remaster-compose (this command will regenerate the iso file that you previously extracted into an iso file again, so you can burn it on your flash drive or run it on a virtual machine)
