
Debian
====================
This directory contains files used to package onecommacoind/onecommacoin-qt
for Debian-based Linux systems. If you compile onecommacoind/onecommacoin-qt yourself, there are some useful files here.

## onecommacoin: URI support ##


onecommacoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install onecommacoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your onecommacoinqt binary to `/usr/bin`
and the `../../share/pixmaps/onecommacoin128.png` to `/usr/share/pixmaps`

onecommacoin-qt.protocol (KDE)

