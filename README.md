# YoRHa GRUB theme

![Alt text](preview.png?raw=true "Preview")

### There are different folders for different screen resolutions.
 - 4k (3840 x 2160)
 - 2k (2560 x 1440)
 - 1k (1920 x 1080)

## To install:

### Step 1
Find your monitor's resolution and copy the corresponding folder to `/boot/grub/themes`

### Step 2
Edit your `/etc/default/grub` file to include

`GRUB_THEME="/boot/grub/themes/ *folder you copied* /theme.txt"`

**For example:**
`GRUB_THEME="/boot/grub/themes/YoRHa-4k/theme.txt"`

### Step 3
Finalize your changes with `sudo update-grub`
