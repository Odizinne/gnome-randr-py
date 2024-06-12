# gnome-randr

This tries to reimplement the some of the functionality of 'xrandr' for the gnome desktop using mutter's dbus-api.

Fork of https://gitlab.com/Oschowa/gnome-randr/ with improved fractional scaling support.

## Added features

- Added `--short` arg

This is now the default when no args are provided. 
short output behave a bit like xrandr in formating, making easier function creation for script that needs to parse xrandr or gnome-randr depending on $XDG_SESSION_TYPE

To use old config print, you must use `--current`
