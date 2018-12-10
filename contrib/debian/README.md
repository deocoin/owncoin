
Debian
====================
This directory contains files used to package deocoind/deocoin-qt
for Debian-based Linux systems. If you compile deocoind/deocoin-qt yourself, there are some useful files here.

## deocoin: URI support ##


deocoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install deocoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your deocoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/deocoin128.png` to `/usr/share/pixmaps`

deocoin-qt.protocol (KDE)

