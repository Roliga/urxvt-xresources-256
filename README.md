urxvt-xresources-256
====================

By default only colors 0-15 are read from X resources by urxvt, this extension loads the rest.

Installation
------------

Simply place the `xresources-256` file in either `~/.urxvt/ext/` to install it just for your user, or `/usr/lib/urxvt/perl/` for a system-wide installation.

To enable this extension just add it to the end of the list of perl extensions in your `~/.Xresources` file, for example:

	URxvt.perl-ext-common: default,xresources-256
