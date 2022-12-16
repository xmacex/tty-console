# tty-console

Norns tty console.

Maps a tty to the framebuffer. Login, and command line unix action ensues!

Some fun ideas include to setup Tidal Cycles and SuperCollider, and run Emacs to livecode them.

## Requirements

- norns
- USB keyboard

## Instructions

Make sure `fbset` package is installed and this should work.

Use a very, very small font e.g. [TamSyn5x9r](http://www.fial.com/~scott/tamsyn-font/) by loading it from a PSF file with `setfont`. I have this in my .bashrc file, an alternative would be to set the font on startup.

A blinking underscore cursor will remain on the screen once this screen is loaded. Restart norns to get rid of it.

The login session will stay open when jumping to another script. It is best to exit it with `logout` or `exit` command.
