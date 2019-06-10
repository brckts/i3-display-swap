# i3-display-swap
A simple python script to swap workspaces between displays in i3.

## Dependencies
1. i3ipc
2. dmenu

## Usage
Put it somewhere on your path and bind some keys to it.
Will swap focused workspace with the one on the primary display.
If the former is the latter, it will spawn a dmenu prompt asking you which display to swap it with.

## Credit where credit is due
This script is basically an improved version of https://github.com/giuseppe-dandrea/i3-swap-workspaces-between-screens designed to work with more than two monitors.
