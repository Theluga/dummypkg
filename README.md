# dummypkg
Create Dummy Packages with Pacman to bypass useless dependencies.

Originally from https://bbs.archlinux.org/viewtopic.php?id=61001 by user Themaister.

This version tries to improve a little with newer pacman.

Usage:
dummypkg -S <package> <version> # Installs dummypkg
dummypkg -R <package> #removes it
dummypkg -l #lists all packages installed by dummypkg

Place this file with execution permission on your path (like /usr/bin).

If you delete this script, remeber to delete /etc/dummy folder.
