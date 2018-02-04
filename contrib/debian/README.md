
Debian
====================
This directory contains files used to package socialkreditsd/socialkredits-qt
for Debian-based Linux systems. If you compile socialkreditsd/socialkredits-qt yourself, there are some useful files here.

## socialkredits: URI support ##


socialkredits-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install socialkredits-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your socialkredits-qt binary to `/usr/bin`
and the `../../share/pixmaps/socialkredits128.png` to `/usr/share/pixmaps`

socialkredits-qt.protocol (KDE)

