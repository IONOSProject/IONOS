
Debian
====================
This directory contains files used to package ionosd/ionos-qt
for Debian-based Linux systems. If you compile ionosd/ionos-qt yourself, there are some useful files here.

## ionos: URI support ##


ionos-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ionos-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ionosqt binary to `/usr/bin`
and the `../../share/pixmaps/ionos128.png` to `/usr/share/pixmaps`

ionos-qt.protocol (KDE)

