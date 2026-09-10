# dummypkg
Create Dummy Packages with Pacman to bypass useless dependencies.

Originally from https://bbs.archlinux.org/viewtopic.php?id=61001 by user Themaister.

This version tries to improve a little with newer pacman.

Usage:
- `dummypkg -S <package> <version>` Installs a dummy package.
- `dummypkg -R <package>` Removes the dummy package.
- `dummypkg -l` Lists all dummy packages installed.
- `dummypkg -h` Shows the help page.

dummypkg requires access to a privilege-escalation mechanism. It automatically detects sudo, doas, run0, or su. At least one must be available and configured.
________________________________________
## License is pending approval by the creator. My changes are GPL V3 or later if possible.
