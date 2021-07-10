
Debian
====================
This directory contains files used to package ibitcoind/ibitcoin-qt
for Debian-based Linux systems. If you compile ibitcoind/ibitcoin-qt yourself, there are some useful files here.

## ibitcoin: URI support ##


ibitcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ibitcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ibitcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/ibitcoin128.png` to `/usr/share/pixmaps`

ibitcoin-qt.protocol (KDE)

