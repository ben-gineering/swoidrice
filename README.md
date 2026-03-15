# The Voidrice (Luke Smith <https://lukesmith.xyz>'s dotfiles)

These are the dotfiles deployed by [LARBS](https://larbs.xyz) and as seen on
[my YouTube channel](https://youtube.com/c/lukesmithxyz).

- Very useful scripts are in `~/.local/bin/`
- Settings for:
	- vim/nvim (text editor)
	- zsh (shell)
	- lf (file manager)
	- mpd/ncmpcpp (music)
	- nsxiv (image/gif viewer)
	- mpv (video player)
	- other stuff like xdg default programs, inputrc and more, etc.
- All configs that can be in `~/.config/` are.
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/shell/bm-files`
	- Directory bookmarks in `~/.config/shell/bm-dirs`

## Usage

These dotfiles are designed for Wayland/Sway and work with:

- [sway](https://github.com/swaywm/sway) (window manager)
- [waybar](https://github.com/Alexays/Waybar) (status bar)
- [foot](https://codeberg.org/dnkl/foot) (terminal emulator)
- [rofi](https://github.com/davatorium/rofi) (application launcher)

I also recommend trying out
[mutt-wizard](https://github.com/lukesmithxyz/mutt-wizard), which additionally
works with this setup. It gives you an easy-to-install terminal-based email
client regardless of your email provider. It is integrated into these dotfiles
as well.

## Install these dotfiles and all dependencies

Use [LARBS](https://larbs.xyz) to autoinstall everything:

```
curl -LO larbs.xyz/larbs.sh
```

or clone the repo files directly to your home directory and install the
[dependencies](https://github.com/LukeSmithxyz/LARBS/blob/master/static/progs.csv).

## Track Your Home Directory with Git

This repository uses an inverse `.gitignore` strategy to track only specific
dotfiles in your home directory. By default, git ignores everything except
the explicitly listed configuration files and directories.

To use this repository as your home directory git tracking:

1. Clone this repo to your home directory:
   ```
   git clone https://gitlab.com/b.engineer/swoidrice.git ~/.local/src/swoidrice
   ```

2. The `.gitignore` file ignores all files by default and only tracks
   explicitly listed dotfiles (configs in `.config/`, `.local/bin/`, etc.)

3. Add or modify tracked files in `.gitignore` as needed for your setup.

This approach allows you to version-control your dotfiles while keeping
your home directory clean of untracked personal files.

## Default Desktop Artwork

Thomas Thiemeyer's *The Road to Samarkand* ([fb](https://www.facebook.com/t.thiemeyer/), [insta](https://www.instagram.com/tthiemeyer/), [shop](https://www.redbubble.com/de/people/TThiemeyer/shop))
