
Debian
====================
This directory contains files used to package unod/uno-qt
for Debian-based Linux systems. If you compile unod/uno-qt yourself, there are some useful files here.

## uno: URI support ##


uno-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install uno-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your uno-qt binary to `/usr/bin`
and the `../../share/pixmaps/uno128.png` to `/usr/share/pixmaps`

uno-qt.protocol (KDE)

