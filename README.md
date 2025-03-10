# Waybar Configuration

This repository contains my [waybar](https://github.com/kovidgoyal/kitty) configuration. 

## Dependencies

For the configuration to function as intended, the [DaddyTimeMono Nerd font](https://www.nerdfonts.com/font-downloads)
should be installed alongside [Noto Serif CJK](https://github.com/notofonts/noto-cjk) 
for rendering Japanese characters and [Noto Emoji](https://github.com/googlefonts/noto-emoji) 
for rendering the weather information. For the weather requests the `python` library `requests` is used, which needs 
to be installed (for `pacman` it is called `python-requests`).

## Install

To install this we suggest creating a symbolic link, for instance by using [GNU Stow](https://www.gnu.org/software/stow/).
In that case one can run `stow waybar -t ~` in the repository root which will create a symbolic link with `~/.config/waybar`. 
Be careful that a symbolic doesn't already exist! To remove the symbolic link created here 
one can run `stow -D waybar` in the repository root.
