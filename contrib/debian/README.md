
Debian
====================
This directory contains files used to package xtellad/xtella-qt
for Debian-based Linux systems. If you compile xtellad/xtella-qt yourself, there are some useful files here.

## xtella: URI support ##


xtella-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install xtella-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your xtellaqt binary to `/usr/bin`
and the `../../share/pixmaps/xtella128.png` to `/usr/share/pixmaps`

xtella-qt.protocol (KDE)

