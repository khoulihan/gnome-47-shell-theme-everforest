## Everforest Gnome Shell Theme

This is a slight tweak to the Adwaita shell theme for Gnome 47 to use colours
from the [Everforest neovim theme](https://github.com/sainnhe/everforest), and
additional suitable colours where necessary. Only the dark version of the theme
is adapted.

The base source code can be found [here](https://gitlab.gnome.org/GNOME/gnome-shell/-/tree/main/data/theme?ref_type=heads).

See the documentation in the original source for advice on tweaking this theme
further.

## Building

I couldn't get the Meson build working, but I was able to build the theme using
the `sassc` command directly:

`sassc -a ./gnome-shell-dark.scss ~/.themes/everforest-dark-shell/gnome-shell/gnome-shell.css`

## Migration

This repository has been [migrated to Codeberg](https://codeberg.org/khoulihan/gnome-47-shell-theme-everforest), though it is unlikely to receive any further updates anyway.
