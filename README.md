# Naien i3wm

![NaienI3WM-preview2](https://github.com/user-attachments/assets/6e6ff683-7789-420e-bab0-e9ab3af069b6)


## Instalation
 Packages to be installed:
 - i3wm group Packages (WM)
 - Kitty (Terminal Emulator)
 - Fastfetch (Neofetch fork)
 - dmenu (application launcher)
 - picom (X Compositor)
 - nwg-look (GTK Theme Manager)
 ### Manual

```
$ sudo pacman -S i3 kitty fastfetch dmenu picom nwg-look

$ git clone https://github.com/menaie/naieni3wm.git
```

After cloning the git, you should enter on the ``i3`` folder and modify the ``config`` file according to your needs.

After modifying the config file, you should move all the files to their required spaces.

```
$ sudo mv ~/naieni3wm/kitty/kitty.conf naieni3wm/kitty/current-theme.conf ~/.config/kitty/
$ sudo mv ~/naieni3wm/i3/config naieni3wm/i3/picom.conf ~/.config/i3/
$ sudo mv ~/naieni3wm/fastfetch/config.jsonc ~/.config/fastfetch
```

# Firefox theme / GTK Theme

If you want (should), you can use my firefox theme ``Naien`` which is available at addons.mozilla.org
And the GTK Theme, extract "naien-gtk3.tar.gz" and move the "naien" folder (which has the index.theme file inside) to "~/.themes" and use nwg-look to put it.
