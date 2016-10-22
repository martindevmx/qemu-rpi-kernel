# qemu-rpi-kernel
IMPORTANT: for Debian users, please go to folder /tools/ and move the script /tools/qemu_choose_vm-debian.sh to /qemu-rpi-kernel-debian/ (it's the folder with all kernel versions, look like this: /qemu-rpi-kernel-debian/qemu_choose_vm-debian.sh) and run the shell with root permission. Remember: apply chmod +x to qemu_choose_vm-debian.sh! have fun!

Qemu kernel for emulating Rpi on QEMU

While I was searching the internet about emulating QEMU, most of the guides pointed to link https://xecdesign.com/downloads/linux-qemu/kernel-qemu which is dead as of now.
So making it available on github for someone who would like to use it.
Hope it helps.

This repo contains two types of kernels.

kernel-qemu-3.10.25-wheezy, which is the original kernel from link https://xecdesign.com/downloads/linux-qemu/kernel-qemu - Works fine with any wheezy image with changes mentioned in wiki.

kernel-qemu-4.x.xx-jessie, are newer kernels compiled compatible with jessie as well as they work well with older wheezy images. 

Build scripts are kept in tools folder for reference.

Go through wiki page for step by step guide how to emulate Raspberry Pi on Qemu on any platform (Win, linux or Mac OS)
