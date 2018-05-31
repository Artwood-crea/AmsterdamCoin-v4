
Debian
====================
This directory contains files used to package amsterdamcoind/creacoin-qt
for Debian-based Linux systems. If you compile amsterdamcoind/creacoin-qt yourself, there are some useful files here.

## creacoin: URI support ##


creacoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install creacoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your amsterdamcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/amsterdamcoin128.png` to `/usr/share/pixmaps`

creacoin-qt.protocol (KDE)

