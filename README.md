Script to use [dmenu](https://tools.suckless.org/dmenu/) for launching programs,
switching to open windows and searching the web.

Just run
```sh
dmenu_webandwm
```

If you want the menu to have
[gruvbox](https://github.com/gruvbox-community/gruvbox) colors and a custom
font, launch it like this:

```sh
dmenu_webandwm -m 0 -fn "Hack Nerd Font:size=10:antialias=true:autohint=true" -nb "#32302F" -nf "#EBDBB2" -sb "#D65D0E" -sf "#F2E5BC"
```

# Features

* select and launch programs available in `$PATH` 
* prefix your input with `?` to launch/switch to firefox and search the web
* prefix your input with `!` to enter a DuckDuckGo
  [bang](https://duckduckgo.com/bang)

# Dependencies

* `xdg-open`
* `awk`
* `wmctrl`
* `dmenu`
* `zsh`

# Install it on Arch Linux

```sh
makepkg -sif PKGBUILD
```
