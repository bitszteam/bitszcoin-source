
Debian
====================
This directory contains files used to package bitszcoind/bitszcoin-qt
for Debian-based Linux systems. If you compile bitszcoind/bitszcoin-qt yourself, there are some useful files here.

## bitszcoin: URI support ##


bitszcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitszcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitszcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitszcoin128.png` to `/usr/share/pixmaps`

bitszcoin-qt.protocol (KDE)

