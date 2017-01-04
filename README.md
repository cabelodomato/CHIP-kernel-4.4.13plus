CHIP-kernel-4.4.13+

Next Thing Co kernel, for CHIP with the kernel 4.4.13-ntc-mlc, compiled with additional modules and firmwares.

This kernel includes all the firmwares from kernel.org linux-firmware git repository (http://git.kernel.org/cgit/linux/kernel/git/firmware/linux-firmware.git).

So far, I have had 3 different usb wifi working on it, out-of-the-box.

Please let me know if you are happy with this kernel or have had any problems.

Download it to your CHIP root directory then:

tar -zxvf 4.4.13+

if you want to make it your default kernel, do:

mv /boot/zImage /boot/zImage.original
cp /boot/vmlinuz-4.4.13+ /boot/zImage

Enjoy!