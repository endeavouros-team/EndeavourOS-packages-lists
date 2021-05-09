# reinstall-DE/WM/BASE-for-EndeavourOS

`git clone https://github.com/endeavouros-team/EndeavourOS-packages-lists.git`

`cd EndeavourOS-packages-lists`

`ls`
will list the files

`sudo pacman -S --needed - < <de-wm-name to reinstall>`

where `<de-wm-name to reinstall>` is one of the text files from this repo including `eos-base-group` what will install needed packages would be there on a default install.

example:

`sudo pacman -S --needed - < xfce4`

`sudo pacman -S --needed - < budgie`

`sudo pacman -S --needed - < cinnamon`

`sudo pacman -S --needed - < deepin`

`sudo pacman -S --needed - < gnome`

`sudo pacman -S --needed - < i3`

`sudo pacman -S --needed - < lxqt`

`sudo pacman -S --needed - < mate`

`sudo pacman -S --needed - < openbox`

`sudo pacman -S --needed - < plasma`

`sudo pacman -S --needed - < eos-base-group`
