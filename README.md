## Jasper gtk theme

![Jasper](preview.png?raw=true)

## Donate

If you like my project, you can buy me a coffee:

<span class="paypal"><a href="https://www.paypal.me/vinceliuice" title="Donate to this project using Paypal"><img src="https://www.paypalobjects.com/webstatic/mktg/Logo/pp-logo-100px.png" alt="PayPal donate button" /></a></span>

## Requirements

- GTK `>=3.20`
- `gnome-themes-extra` (or `gnome-themes-standard`)
- Murrine engine — The package name depends on the distro.
  - `gtk-engine-murrine` on Arch Linux
  - `gtk-murrine-engine` on Fedora
  - `gtk2-engine-murrine` on openSUSE
  - `gtk2-engines-murrine` on Debian, Ubuntu, etc.
- `sassc` — build dependency

- `Icon theme` [Colloid teal icon theme](https://github.com/vinceliuice/Colloid-icon-theme)

- `Wallpaper` [Vimix wallpapers](https://github.com/vinceliuice/vimix-kde/tree/master/wallpaper)

## Installation

### Manual Installation

Run the following commands in the terminal:

```sh
./install.sh
```

> Tip: `./install.sh` allows the following options:

```
-d, --dest DIR          Specify destination directory (Default: $HOME/.themes)

-n, --name NAME         Specify theme name (Default: Jasper)

-t, --theme VARIANT     Specify theme color variant(s) [default|purple|pink|red|orange|yellow|green|blue|grey|all] (Default: teal)

-c, --color VARIANT     Specify color variant(s) [standard|light|dark] (Default: All variants)

-s, --size VARIANT      Specify size variant [standard|compact] (Default: standard variant)

-l, --libadwaita        Link installed gtk-4.0 theme to config folder for all libadwaita app use this theme

-r, --remove,
-u, --uninstall         Uninstall/Remove installed themes

--tweaks                Specify versions for tweaks [nord|dracula|black|macos] (only nord and dracula can not mix use with!)
                        1. nord:     Nord ColorScheme version
                        2. dracula   Dracula ColorScheme version
                        3. black:    Blackness color version
                        4. macos:    Macos style windows button

-h, --help              Show help
```

> For more information, run: `./install.sh --help`

### Flatpak Installation

Automatically install your host GTK+ theme as a Flatpak. Use this:

- [stylepak](https://github.com/refi64/stylepak)

