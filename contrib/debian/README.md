
Debian
====================
This directory contains files used to package catthisd/catthis-qt
for Debian-based Linux systems. If you compile catthisd/catthis-qt yourself, there are some useful files here.

## catthis: URI support ##


catthis-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install catthis-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your catthisqt binary to `/usr/bin`
and the `../../share/pixmaps/catthis128.png` to `/usr/share/pixmaps`

catthis-qt.protocol (KDE)

