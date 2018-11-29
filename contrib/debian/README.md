
Debian
====================
This directory contains files used to package bopucoind/bopucoin-qt
for Debian-based Linux systems. If you compile bopucoind/bopucoin-qt yourself, there are some useful files here.

## bopucoin: URI support ##


bopucoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bopucoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bopucoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bopucoin128.png` to `/usr/share/pixmaps`

bopucoin-qt.protocol (KDE)

