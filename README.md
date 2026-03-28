This repo is thanks to the work of others.

The b43-tools were obtained from the repo of mbuesch at ( https://github.com/mbuesch/b43-tools ).
The b43-firmware-install script is original copyright (C) 2011 Dmitry Mikhirev ( obtained from https://github.com/mikhirev/b43-firmware-install ) and modified/updated by asylumlinux.
The firmware files (for kernel versions above 3.2) obtained via the b43-firmware-install script are pulled from our repo but this, too, was cloned from the repo provided by minios ( https://github.com/minios-linux/b43-firmware/releases ). The firmware for kernel versions older than 3.2 are pulled from an outside source (see install script code if interested).

Aside from modifications to the install script, the files herein represent the work of the aforementioned and their presence in our repo does not in any way imply our ownership over these FOSS projects. They are provided here only as a means of simplifying our use in helping others and to consolidate the tools.

For the purposes of using these toolds in the Beyond Linux From Scratch project on a pc/mac with 4331 wireless, the following steps are suggested:

git clone https://github.com/asylumlinux/blfs_wl.git
cd to b43-tools/fwcutter
./configure
make
as root: make install
cd ..
chmod +x b43-firmware-install.sh
./b43-firmware-install.sh
