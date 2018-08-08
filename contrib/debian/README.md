
Debian
====================
This directory contains files used to package cannabitsd/cannabits-qt
for Debian-based Linux systems. If you compile cannabitsd/cannabits-qt yourself, there are some useful files here.

## cannabits: URI support ##


cannabits-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cannabits-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cannabitsqt binary to `/usr/bin`
and the `../../share/pixmaps/cannabits128.png` to `/usr/share/pixmaps`

cannabits-qt.protocol (KDE)

