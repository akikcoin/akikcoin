
Debian
====================
This directory contains files used to package akikd/akik-qt
for Debian-based Linux systems. If you compile akikd/akik-qt yourself, there are some useful files here.

## akik: URI support ##


akik-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install akik-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your akikqt binary to `/usr/bin`
and the `../../share/pixmaps/akik128.png` to `/usr/share/pixmaps`

akik-qt.protocol (KDE)

