# Arch Linux - PushLinux

To be able to build you install this package

sudo pacman -S archiso

Download also the PushLiux keyring from github and install it with pacman -U.

https://github.com/PeterDauwe/pushlinux_repo/tree/master/x86_64

Download the last version.
Install with pacman -U nameofthefile

Or run the script import-pushlinux-key.sh to download and sign it.

Do check out the archiso.readme.

Use the correct version of archiso.

Start building your own pushlinux version with 

sudo ./build.sh -v