
Debian
====================
This directory contains files used to package trioned/trione-qt
for Debian-based Linux systems. If you compile trioned/trione-qt yourself, there are some useful files here.

## trione: URI support ##


trione-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install trione-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your trione-qt binary to `/usr/bin`
and the `../../share/pixmaps/trione128.png` to `/usr/share/pixmaps`

trione-qt.protocol (KDE)

