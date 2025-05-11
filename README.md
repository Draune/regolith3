# My Regolith3 config

## Screenshots

![desktop_image](https://github.com/Draune/regolith3-config/blob/master/screenshots/desktop.png)

## Features

I use it with `regolith-look-gruvbox`

Features:
- increase gaps size (15px)
- disable smart gaps (means there will be gaps enven if a window is alone in a workspace)
- setup transparent windows
- setup autotiling (needs to be installed with `pip install autotiling`)
- remove i3bar (`apt remove i3xrocks regolith-i3-i3xrocks regolith-i3xrocks-config`)
- setup my custom conky in place of the i3bar
- change the focused window's borders
- remove floating windows' boarders (to get conky widgets without borders)

## Install

Installation steps (first, you need to install Regolith):

``` shell
# install the conky config
sudo apt install conky
git clone https://github.com/Draune/conky-config.git ~/.conky

# install dependencies for autotiling
pip install i3ipc
pip install autotiling

# install look
sudo apt install regolith-look-gruvbox

# install the regolith config
git clone https://github.com/Draune/regolith3 ~/.config/regolith3

# remove i3xrocks
sudo apt remove i3xrocks regolith-i3-i3xrocks regolith-i3xrocks-config

# You can now press Mod + Shift + R
```

