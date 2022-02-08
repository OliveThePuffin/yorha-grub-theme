# YoRHa GRUB theme

![Alt text](preview.png?raw=true "Preview")

There are 2 folders for resolution, 4k and 1080p.

Basically to install, just copy the folder you need to `/boot/grub/themes/` and edit your `/etc/default/grub` file to include

`GRUB_THEME="/boot/grub/themes/YoRHa-4k/theme.txt"`

or

`GRUB_THEME="/boot/grub/themes/YoRHa-1080p/theme.txt"`

depending on which folder you copied

There should already be a commented example somewhere in the file

After that, finalize your changes with `sudo update-grub`
