
Debian
====================
This directory contains files used to package masternodesmed/masternodesme-qt
for Debian-based Linux systems. If you compile masternodesmed/masternodesme-qt yourself, there are some useful files here.

## masternodesme: URI support ##


masternodesme-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install masternodesme-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your masternodesmeqt binary to `/usr/bin`
and the `../../share/pixmaps/masternodesme128.png` to `/usr/share/pixmaps`

masternodesme-qt.protocol (KDE)

