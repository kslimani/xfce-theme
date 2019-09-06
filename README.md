# XFCE4 custom theme

__UPDATE:__ this theme is broken since XFCE 4.12+ and therefore deprecated. Instead, take a look at [Numix theme project](https://github.com/numixproject/numix-gtk-theme).

* This theme is a mix of Numix Holo and Greybird GTK themes.
* Window borders is Numix Holo.
* Icons are Cheser theme.
* Cursor is DMZ white theme.
* GTK3 theme is based on this [Numix Holo](https://github.com/dar5hak/Numix-Holo) on Github.

Required packages installation :
```
apt-get install dmz-cursor-theme gtk2-engines-murrine
```

## XFCE theme manager

Source code : [https://github.com/KeithDHedger/Xfce-Theme-Manager](https://github.com/KeithDHedger/Xfce-Theme-Manager)

Installation (as root user) :

```
apt-get install build-essential automake autotools-dev autoconf glib-2.0-dev libgtk2.0-dev libxfce4ui-1-dev
tar -zxvf Xfce-Theme-Manager-0.3.8.tar.gz
cd Xfce-Theme-Manager-0.3.8
./autogen.sh --prefix=/usr
make
make install
```

Theme Configuration :

* Icons is Cheser
* Cursors is DMZ (White)
* WM font is Titillium Web (SemiBold, size 10)
* App font is Titillium Web (SemiBold, size 10)
* Desktop properties / Wallpaper : saturation is 1.0
* Dashboard bar size is 30 pixels

## Numix modifications

* change selected menu color from `#00a2ff` to `#204487`
* enable scrollbar buttons and set silder width to 16
