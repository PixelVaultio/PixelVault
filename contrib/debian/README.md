
Debian
====================
This directory contains files used to package pixeld/pixel-qt
for Debian-based Linux systems. If you compile pixeld/pixel-qt yourself, there are some useful files here.

## pixel: URI support ##


pixel-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pixel-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pixelqt binary to `/usr/bin`
and the `../../share/pixmaps/pixel128.png` to `/usr/share/pixmaps`

pixel-qt.protocol (KDE)

