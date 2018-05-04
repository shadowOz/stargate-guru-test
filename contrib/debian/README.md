
Debian
====================
This directory contains files used to package stargated/stargate-qt
for Debian-based Linux systems. If you compile stargated/stargate-qt yourself, there are some useful files here.

## stargate: URI support ##


stargate-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install stargate-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your stargate-qt binary to `/usr/bin`
and the `../../share/pixmaps/stargate128.png` to `/usr/share/pixmaps`

stargate-qt.protocol (KDE)

