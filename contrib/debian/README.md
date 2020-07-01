
Debian
====================
This directory contains files used to package mdld/mdl-qt
for Debian-based Linux systems. If you compile mdld/mdl-qt yourself, there are some useful files here.

## mdl: URI support ##


mdl-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mdl-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mdlqt binary to `/usr/bin`
and the `../../share/pixmaps/mdl128.png` to `/usr/share/pixmaps`

mdl-qt.protocol (KDE)

