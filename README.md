# GNOME Shell Extension - Dynamic Transparent Top Bar

### SUPPORT MY WORK
<a href="https://buymeacoffee.com/momo424">
  <img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" >
</a>

A GNOME Shell extension that brings dynamic transparent top bar.

## License

This program is distributed under the terms of the GNU General Public License, version 2 or later.

## Development

### Wayland

Start child shell instance with reloaded extensions
```
MUTTER_DEBUG_DUMMY_MODE_SPECS=1920x1080 dbus-run-session -- gnome-shell --nested --wayland
```

### Xorg

Reload shell by pressing ALT+F2 type r in the input then enter.

### Compile schemas
```
cd ~/.local/share/gnome-shell/extensions/transparent-top-bar@ftpix.com
glib-compile-schemas schemas/
```



https://github.com/user-attachments/assets/0919e405-d5ed-4f77-a4cb-573849978dba

