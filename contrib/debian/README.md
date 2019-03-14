
Debian
====================
This directory contains files used to package vpubd/vpub-qt
for Debian-based Linux systems. If you compile vpubd/vpub-qt yourself, there are some useful files here.

## vpub: URI support ##


vpub-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install vpub-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your vpubqt binary to `/usr/bin`
and the `../../share/pixmaps/vpub128.png` to `/usr/share/pixmaps`

vpub-qt.protocol (KDE)

