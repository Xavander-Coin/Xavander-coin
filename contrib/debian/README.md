
Debian
====================
This directory contains files used to package xavanderd/xavander-qt
for Debian-based Linux systems. If you compile xavanderd/xavander-qt yourself, there are some useful files here.

## xavander: URI support ##


xavander-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install xavander-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your xavanderqt binary to `/usr/bin`
and the `../../share/pixmaps/xavander128.png` to `/usr/share/pixmaps`

xavander-qt.protocol (KDE)

