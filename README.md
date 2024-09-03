# Naien i3wm

![NaienI3WM-preview](https://github.com/user-attachments/assets/11cae767-7962-457b-a4c3-ba37a1b4f28f)

## Instalation
 Packages to be installed:
 - i3wm group Packages (WM)

 - Kitty (Terminal Emulator)
 - Fastfetch (Neofetch fork)
 - dmenu (application launcher)
 - picom (X Compositor)
 ### Manual

```
$ sudo pacman -S i3 kitty fastfetch dmenu picom

$ git clone https://github.com/menaie/naieni3wm.git
```

After cloning the git, you should enter on the ``i3`` folder and modify the ``config`` file according to your needs.

After modifying the config file, you should move all the files to their required spaces.

```
(outside naieni3wm folder) $ sudo mv naieni3wm/kitty/kitty.conf naieni3wm/kitty/current-theme.conf ~/.config/kitty/
$ sudo mv naieni3wm/i3/config naieni3wm/i3/picom.conf ~/.config/i3/
$ sudo mv naieni3wm/fastfetch/config.jsonc ~/.config/fastfetch
```

# Firefox theme

If you want (should), you can use my firefox theme, Naien, which is available at [addons.mozilla.org](addons.mozilla.org)
