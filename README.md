# carbonized

**carbonized** is a vim/terminal theme inspired by the [Carbon keycap set](https://geekhack.org/index.php?topic=79693.0) by T0mb3ry.

## screenshots

<table>
<tr></tr><tr><td align="center"><h5>carbonized-light</h5></td>
<td align="center"><img src="img/screenshot-carbonized-light.png" alt="screenshot of the carbonized-light vim theme" width="256"> <img src="img/screenshot-carbonized-dark.png" alt="screenshot of the carbonized-dark vim theme" width="256"></td>
<td align="center"><h5>carbonized-dark</h5></td></tr>
</table>

## installation

### step 1: download the colour scheme

#### option A: manually

Download the desired [colourscheme files](https://github.com/nightsense/carbonized/tree/master/colors) and place in directory `~/.vim/colors/` (Linux/Mac) or `%userprofile%\vimfiles\colors\` (Windows).

#### option B: using a plugin manager

For easy management of Vim colour schemes (and other plugins), try a plugin manager. With [vim-plug](https://github.com/junegunn/vim-plug), for instance, just add `Plug 'nightsense/carbonized'` to the list of plugins in `vimrc`, then run `PlugUpdate`.

### step 2: activate the colour scheme

To activate the carbonized theme, add one of the following lines to your `vimrc`:
- `colorscheme carbonized-light`
- `colorscheme carbonized-dark`

For Neovim, add `set termguicolors` to enable truecolour support.

### step 3: configure terminal colours (if using Vim in a terminal)

In order for carbonized to work properly in terminal Vim, set the terminal's colours to match those of the active Vim theme.

## terminal themes

As of now, this repository provides the following [terminal configuration files](https://github.com/nightsense/carbonized/tree/master/terminal):
- [`Xresources`](https://github.com/nightsense/carbonized/tree/master/terminal/Xresources) files for **xterm** and **urxvt** (Linux)
- [`.colorscheme`](https://github.com/nightsense/carbonized/tree/master/terminal/konsole%20%26%20qterminal) files for **Konsole** and **QTerminal** (Linux)
- [`gsettings`](https://github.com/nightsense/carbonized/tree/master/terminal/pantheon-terminal.md) 'command blocks' for **pantheon-terminal** (elementary OS)

For **GNOME Terminal**, run the [install script](https://github.com/nightsense/carbonized/tree/master/terminal/gnome-terminal) for the desired carbonized theme to create a "profile" for it. Then select the profile with the right-click menu, or set the profile as default via Edit > Preferences > Profiles.
