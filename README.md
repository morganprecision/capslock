# Caps lock key mappings using xmodmap

The list of key mappings for the Caps Lock key in the `capslock.txt` file take
advantage of xmodmap to allow you to do all kinds of things without your fingers
having to leave "home row."

To activate the mappings, run the following command:

    xmodmap path/to/capslock.txt

Just add this line to your shell's startup file to have the mappings
auto-activated each time you log in.

Inspired by [this blog
post](http://www.ninthavenue.com.au/vim-key-bindings-in-ubuntu-using-xmodmap).
