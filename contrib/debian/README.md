
Debian
====================
This directory contains files used to package tourerd/tourer-qt
for Debian-based Linux systems. If you compile tourerd/tourer-qt yourself, there are some useful files here.

## pivx: URI support ##


tourer-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tourer-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tourer-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

tourer-qt.protocol (KDE)

