# Alpine Scripts

### Prerequisites

You cant use these scripts right after the alpine installation.

1. You should have set up alpine with the `setup-alpine` command.
2. You shloud have installed the Xorg base with `setup-xorg-base`.

### Installation

To use the setup script(s) you need to already have `bash` and `curl` installed.

1. Download the `download-scripts`script with `curl https://raw.githubusercontent.com/demondave/scripts/main/download-scripts > download-scripts`
2. Now use `bash download-scripts` to download the other setup scripts.
3. The script will now download the `bspwm-lightdm` script.

## bspwm-lightdm

This script will install the following packages: 
  `bspwm` as window manager   
  `lightdm-gtk-greeter` as login manager
  `rxvt-unicode` (urxvt) as terminal emulator
  `polybar` as bar
  `picom` as composer
  `feh` for desktop wallpapers
  and some other packages which you can find in the `bspwm-lightdm` script.




