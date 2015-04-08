Numix-Reload is a custom theme based in Numix

### Numix (parent theme)

Numix is a modern flat theme with a combination of light and dark elements. It supports Gnome, Unity, XFCE and Openbox.

Numix is a part of the [Numix Project](http://numixproject.org).

### Manual installation

Extract the zip file to the themes directory i.e. `/usr/share/themes/`

To set the theme in Gnome, run the following commands in Terminal,

```
gsettings set org.gnome.desktop.interface gtk-theme "Numix-reload"
gsettings set org.gnome.desktop.wm.preferences theme "Numix-reload"
```

To set the theme in Xfce, run the following commands in Terminal,

```
xfconf-query -c xsettings -p /Net/ThemeName -s "Numix-reload"
xfconf-query -c xfwm4 -p /general/theme -s "Numix-reload"
```

### Requirements

GTK+ 3.6 or above

Murrine theme engine

