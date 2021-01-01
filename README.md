zimfw-emacs
===========

Useful [Emacs][2] aliases and settings. This will set emacs to be your
default editor for shell operations like editting git commit messages

Installation
------------

Once you have emacs already on your system, add the following to your .zimrc:

``` shell
zmodule cowboyd/zimfw-emacs --branch v1
```

Then run:

``` shellsession
$ zimfw install
```

See [zimfw][1] for more details

Aliases
-------

  * `e` edit a file or directory by connecting to an emacs server. If
    an emacs server is not started, it will be created for you.

[1]: https://github.com/zimfw/zimfw
[2]: https://www.gnu.org/software/emacs/
