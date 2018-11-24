
Debian
====================
This directory contains files used to package makeatord/makeator-qt
for Debian-based Linux systems. If you compile makeatord/makeator-qt yourself, there are some useful files here.

## makeator: URI support ##


makeator-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install makeator-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your makeatorqt binary to `/usr/bin`
and the `../../share/pixmaps/makeator128.png` to `/usr/share/pixmaps`

makeator-qt.protocol (KDE)

