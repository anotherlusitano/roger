## Install
1. Clone the repo
2. Make `roger` executable with `chmod +x roger`
3. Put it in your `$PATH` and have fun :)

> [!WARNING]  
> Installing packages from a theme only works for Arch based distributions.

## Usage
```
Usage:
  roger [options] [theme]
  roger [options] [dotfiles] [theme]

Options:
  -n, --new
    Create a new theme
  -a, --add
    Add dotfiles to a theme
  -u, --use
    Use a theme
  -d, --delete
    Delete a theme
  -D, --destroy
    Delete a theme and uninstall all the packages of that theme
  -t, --theme
    Show the current theme
  -T, --themes
    Show all themes available
  -h, --help
    Show this help message and exit

Some example usages:
  roger -n MyCoolNordicTheme
  roger -u MyHyprlandTheme
  roger -a bspwm/ polybar/ sxhkd/ MyCoolNordicTheme
  roger -d MyCoolNordicTheme
  roger -D MyCoolNordicTheme
```

> [!IMPORTANT]  
> All themes are located in your `~/.roger` directory

## Why does roger exist?
Because I wake up one day and choose violence.
