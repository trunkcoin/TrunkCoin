
Debian
====================
This directory contains files used to package trunkd/trunk-qt
for Debian-based Linux systems. If you compile trunkd/trunk-qt yourself, there are some useful files here.

## trunk: URI support ##


trunk-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install trunk-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your trunkqt binary to `/usr/bin`
and the `../../share/pixmaps/trunk128.png` to `/usr/share/pixmaps`

trunk-qt.protocol (KDE)

