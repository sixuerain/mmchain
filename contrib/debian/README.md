
Debian
====================
This directory contains files used to package mmchaind/mmchain-qt
for Debian-based Linux systems. If you compile mmchaind/mmchain-qt yourself, there are some useful files here.

## mmchain: URI support ##


mmchain-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mmchain-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mmchain-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

mmchain-qt.protocol (KDE)

