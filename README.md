# Gnome-Shell Keyboard Modifiers Status

 Gnome-Shell extension that shows keyboard modifiers status. It's much useful when sticky keys are active.
 
## Install

- From Gnome extensions site

    https://extensions.gnome.org/extension/975/keyboard-modifiers-status/

- Manually

    1. Extract it into a subfolder `keyboard_modifiers_status@sneetsher` in `~/.local/share/gnome-shell/extensions/`
    2. Restart gnome-shell (or logout/login), Enable it in Gnome Tweak, Then restart gnome-shell again.
    
## Debug

Beside LookingGlass tools, this is a simple commandline to fetch and display the modifiers state. To run:

    gjs ~/.local/share/gnome-shell/extensions/keyboard_modifiers_status@sneetsher/test_gjs_gdk_modifiers.js
