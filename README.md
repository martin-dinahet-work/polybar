# A simple, nice looking bar!

## Introduction:
This bar is made for the i3 Window manager, but can work in any environment.
This is a work in progress, some stuff may change along the road.
Feel free to give advice or request some change!

## Screenshots:
TODO

## Prerequisites:
- Git
- Polybar
- A Nerd Font (for icons)

## Installation:
1. Make a backup of your current polybar config (optional)
```console
$ mv ~/.config/polybar/ ~/.config/polybar.bak/
```
2. Clone the repository
```console
$ git clone https://github.com/martin-dinahet-work/polybar.git ~/.config/polybar/
```
3. Start polybar and see the results!
```console
$ polybar
```
4. Make polybar start automatically in your i3 session (optional)
```i3
exec_always --no-startup-id ~/.config/polybar/polybar.sh
```

## Modules:
TODO
