# i3-display-swap
A simple python script to swap workspaces between displays in i3.

## Dependencies
1. i3ipc
2. dmenu

## Usage
Launching it from a workspace not on your primary display will swap that workspace with the one currently in your primary display. Launching it from your primary display will spawn a dmenu prompt asking you with which display to swap.

## Credit where credit is due
This script is basically an improved version of https://github.com/giuseppe-dandrea/i3-swap-workspaces-between-screens designed to work with more than two monitors.
