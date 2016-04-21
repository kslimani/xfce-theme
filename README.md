XFCE4 custom theme
==================

* This theme is a mix of Numix Holo and Greybird GTK themes.
* Window borders is Numix Holo.
* Icons are Cheser theme.
* Cursor is DMZ white theme.

Required packages installation :
```
apt-get install dmz-cursor-theme gtk2-engines-murrine
```

XFCE theme manager
------------------

Download page : http://keithhedger.hostingsiteforfree.com/pages/apps.html#themeed

Installation (as root user) :

```
apt-get install build-essential automake autotools-dev autoconf glib-2.0-dev libgtk2.0-dev libxfce4ui-1-dev
tar -zxvf Xfce-Theme-Manager-0.3.4.tar.gz
cd Xfce-Theme-Manager-0.3.4
./autogen.sh --prefix=/usr
make
make install
```

Theme Configuration :

* WM font is Titillium Web (SemiBold, size 10).
* App font is Titillium Web (SemiBold, size 10).
