# YoRHa GRUB theme

There are 2 folders for resolution, 4k which I have tested and know looks accurate, and 1080p which is an unverified guess, so tweaking number values may be needed.

Basically to install, just copy the folder you need to /boot/grub/themes and edit your /etc/default/grub file to include

`GRUB_THEME="/boot/grub/themes/YoRHa-4k/theme.txt"`

or

`GRUB_THEME="/boot/grub/themes/YoRHa-1080p/theme.txt"`

depending on which folder you copied

There should already be a commented example somewhere in the file

After that, finalize your changes with `sudo update-grub`
