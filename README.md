# dotfiles

![Desktop Screenshot](desktop.png)

## alacritty

I use the Dracula alacritty theme from here: https://draculatheme.com/alacritty

## bspwm

I use the rounded corner patch (included in the folder).

## firefox

Theme is based on
[minimal-function-fox](https://github.com/mut-ex/minimal-functional-fox).
See the README of that repo for how to get it setup. I only ended up using the
userChrome.css and userContent.css files for my setup.

Install the [nightTab](https://addons.mozilla.org/en-US/firefox/addon/nighttab/)
extension to get the new tab page shown in my screenshot.

## ncmpcpp

I have configured the layout to my liking.

## pcmanfm

I have changed the settings to my liking and added the "hide menubar" patch.

## picom

I believe I use pretty standard settings for this.

## polybar

My polybar files are based on the "polybar-4" theme from this repo:
https://github.com/adi1090x/polybar-themes. If you wish to recreate my polybar
look, you can either use this theme or my files as a starting point. My files
will have most of the things taken out that aren't used directly in my polybar,
so keep that in mind if you want to add things that aren't in my bar.

To get started, copy the contents of the `polybar` directory into:
`~/.config/polybar`

### fonts

I use the agave Nerd Font for the main font, icomoon-feather for the icon font and umeboshi for the hiragana (Japanese) font.
These can be found in the `fonts` directory, and should be added to your
system fonts to be useable. I copy mine into `~/.fonts`, then run
`fc-cache -f -v`.

### config

My config has three bars, my main bar, my sytem tray bar and my second monitor bar (vertical)

### modules

Contains configs for modules built into polybar.

### user_modules

Contains modules created by me. This is also where I recommend adding your own
custom modules.

### launching

Make sure `launch.sh` is executable by running: `chmod +x launch.sh`.
Add `launch.sh` as a startup script so polybar launches every time you log in.

## rofi

I use the Dracula rofi theme from here: https://draculatheme.com/rofi. I also use the rofi-power-menu script for a power menu launched from polybar.

## sxhkd

For bspwm and rofi keybindings.

## vscode

### extensions

Install the Dracula extension.

### settings.json

Contains the relevant parts of my `settings.json` file.

## folders 

Papirus-Dark. Can be found here https://github.com/PapirusDevelopmentTeam/papirus-icon-theme.