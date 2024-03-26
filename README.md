# Abouot this fork

This is a fork of [this repo](https://github.com/kronikpillow/voidrice) which I like aethetically but I removed several scripts and configurations I personally don't like nor use.

# The Voidrice (Luke Smith <https://lukesmith.xyz>'s dotfiles)

These are the dotfiles deployed by [my fork of LARBS](https://github.com/garaqta/LARBS)

- Very useful scripts are in `~/.local/bin/`
- Settings for:
	- vim/nvim (text editor)
	- zsh (shell)
	- lf (file manager)
	- sxiv (image/gif viewer)
	- mpv (video player)
	- other stuff like xdg default programs, inputrc and more, etc.
- I try to minimize what's directly in `~` so:
	- All configs that can be in `~/.config/` are.
	- Some environmental variables have been set in `~/.zprofile` to move configs into `~/.config/`
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/shell/bm-files`
	- Directory bookmarks in `~/.config/shell/bm-dirs`

## Usage

These dotfiles are intended to go with ***my fork's*** of Luke's suckless programs
- [dwm](https://github.com/garaqta/LARBS-dwm) (window manager)
- [dwmblocks](https://github.com/garaqta/LARBS-dwmblocks) (statusbar)
- [st](https://github.com/garaqta/LARBS-st) (terminal emulator)
- [dmenu](https://github.com/garaqta/LARBS-dmenu) (launcher)

which essentially contain 2 branches
- ***master*** which is essentially just a rice
- ***config*** which contains other patches, tweaks, and keybindings



## Differences
- I have riced my dotfiles with the Nord color scheme everywhere possible
- some of Luke's aliases to me simply don't make sense, like `sudo su`
so i removed them, i sometimes find it convenient to keep user environment
when in root, at other times when i want a clean root I just 'su -l' instead.
- my xinit invokes gnome-keyring and I use the [pam step](https://wiki.archlinux.org/title/GNOME/Keyring#PAM_step) to unlock it
- my dotfiles make use of `systemd services` and `systemd --user services`

## Install these dotfiles and all dependencies

I find that Luke's installer comes with missing dependancies comparing to
his dotfiles, Use my [fork of LARBS](https://https://github.com/garaqta/LARBS) to autoinstall everything instead:

```
curl -LO https://raw.githubusercontent.com/garaqta/LARBS/master/larbs.sh
```

or clone the repo files directly to your home directory and install the
[dependencies](https://github.com/garaqta/LARBS/blob/master/progs.csv).

## Default Desktop Artwork

My daughter (Ana Coppola from Ichigo Mashimaro, art by Barasui)
