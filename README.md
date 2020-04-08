## Krayan GTK Theme

Krayan is a flat Material Design theme for GTK3, GTK2, and GNOME Shell based on the well aquitted [Layan GTK theme](https://github.com/vinceliuice/Layan-gtk-theme) by [Kevin D'souza](https://github.com/krypticallusion) and [Diab Neiroukh](https://github.com/lazerl0rd). It has a slightly darker twist on the colour scheme and prefers "Open Sans"-style fonts.

### Info

#### GTK3

GTK+ version 3.20 or later is required

#### GTK2 

GTK2 requires at least Murrine Engine version 0.98.1.1 and the Pixbuf Engine.

Arch:

```
pacman -S gtk-engine-murrine gtk-engines
```

Debian-based distros (Ubuntu, Mint, etc.):

```
sudo apt-get install gtk2-engines-murrine gtk2-engines-pixbuf
```

"Enterprise Linux"-based distros (Fedora, RedHat, etc.):

```
yum install gtk-murrine-engine gtk2-engines
```

Others:

Search for the engines in your distributions repository or install the engines from source.

### Installation

Arch (available at the [AUR](https://aur.archlinux.org/packages/krayan-gtk-theme-git)):

```
yay -S gtk-engine-murrine gtk-engines
```

Others:

Clone this repository, open the terminal at current directory, and then run `./install.sh`.

### Removal

Run the installation script which will detect and remove Krayan.
