# Dotfiles

dotfiles for my i3 + lemonbar setup on ArchLinux

I use this configuration for my laptop which runs **[i3-gaps window manager](https://github.com/Airblader/i3)** (a fork of i3) on
**[Arch Linux](https://www.archlinux.org/)**.

## Dependencies

*Note: I hope I've covered all dependencies here, but something might be missing*

This setup is intended for **[i3-gaps](https://github.com/Airblader/i3)** by Airblader. I haven't tested it with regular i3-- you'll probably have to make a few changes if you want to use that. Only tested on ArchLinux-- I can't make any guarantees about its compatibility with other distros.

* `conky` -- Lightweight system monitor for X (for dropbox and todo-cli dislays)
* `[dropbox-cli]`(https://aur.archlinux.org/packages/dropbox-cli) -- Command line interface for dropbox
* `mpc` -- Client for `mpd`, responsible for telling lemonbar about the currently playing media.
* `mpd` -- Flexible, powerful, server-side application for playing music with `ncmpcpp` as client
* `mutt` -- Small but very powerful text-based mail client
* `msmtp` -- A mini smtp client
* `offlineimap` -- Synchronizes emails between two repositories
# `pass` -- Stores, retrieves, generates, and synchronizes passwords securely  
* `ranger` -- A simple, vim-like file manager
* `[Siji Icon Font]`(https://aur.archlinux.org/packages/siji-git/) -- Iconic bitmap font, used in `lemonbar`
* `terminus-font` -- Monospace bitmap font (for X11 and console)
* `vim` -- Vi Improved, a highly configurable, improved version of the vi text editor
* `xprop` -- X11 window info program, makes the window title section work
* `xsetroot` -- to set the wallpaper



## Installation

```
git clone https://github.com/okubax/dotfiles.git
cd dotfiles
./dots.sh

```

### General

1. First, install the dependencies listed in the section above.

2. `bin/` contains my custom scripts. Add them to your `$PATH` and ensure that they are executable. 

3. My default shell is zsh and I use the [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) framework to manage my zsh configuration.

4. Terminal colorschemes and wallpaper with script to load random color and match wallpaer to it on every startup is the work of [dkeg](https://github.com/dkeg/crayolo).


### Wallpaper

Wallpaper is set by the random-color-picker script in the Xresources.d folder, if you don't want this, remove the script (you will have to set a color scheme for yur terminal manually as this scipt handles that.

## Screenshot

![ScreenShot](https://raw.githubusercontent.com/okubax/dotfiles/master/screenshot.png)
