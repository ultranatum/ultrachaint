
Debian
====================
This directory contains files used to package ultrachaintd/ultrachaint-qt
for Debian-based Linux systems. If you compile ultrachaintd/ultrachaint-qt yourself, there are some useful files here.

## ultrachaint: URI support ##


ultrachaint-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ultrachaint-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ultrachaintqt binary to `/usr/bin`
and the `../../share/pixmaps/ultrachaint128.png` to `/usr/share/pixmaps`

ultrachaint-qt.protocol (KDE)

