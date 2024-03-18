# reinstall-DE/WM/BASE-for-EndeavourOS
we now offer a script/package to get DE/WM installed by list of packages from ISO:

https://github.com/endeavouros-team/PKGBUILDS/tree/master/eos-packagelist

You can install on EndeavourOS: `sudo pacman -S eos-packagelist`

We will keep this repo also updated and if you may need to use it will work like before:


`git clone https://github.com/endeavouros-team/EndeavourOS-packages-lists.git`

`cd EndeavourOS-packages-lists`

`ls`
will list the files

`sudo pacman -S --needed - < <de-wm-name to reinstall>`

!!make sure to fully update your OS before installing a bunch of new packages!!

`yay` or at least `sudo pacman -Syu`

where `<de-wm-name to reinstall>` is one of the text files from this repo including `eos-base-group` what will install needed packages would be there on a default install.

example:

`sudo pacman -S --needed - < xfce4`

`sudo pacman -S --needed - < i3`

`sudo pacman -S --needed - < budgie`

`sudo pacman -S --needed - < cinnamon`

`sudo pacman -S --needed - < gnome`

`sudo pacman -S --needed - < kde`

`sudo pacman -S --needed - < lxde`

`sudo pacman -S --needed - < lxqt`

`sudo pacman -S --needed - < mate`

---

`sudo pacman -S --needed - < eos-base-group` (base system packages)

`sudo pacman -S --needed - < eos-apps` (common EndeavourOS apps)

`sudo pacman -S --needed - < printer` (cups)

`sudo pacman -S --needed - < hp-printer` (HP printer and scanner Hewlett-Packard)

## Disclaimer

Note that installing DE packages this way can cause various problems, e.g. running multiple conflicting bluetooth managers etc.

So doing this is at your own risk. If you proceed, you should be experienced enough to be able to fix any potential problems caused by using these instructions.
