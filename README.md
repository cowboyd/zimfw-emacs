zsh-emacs
===========

Useful [Emacs][2] aliases and settings. This will set emacs to be your
default editor for shell operations like editting git commit messages

Installation
------------

Once you have emacs already on your system, add the following to your
zsh plugin manaher. For example:

``` shell
# antigen
antigen bundle cowboyd/zsh-emacs

#zim
zmodule cowboyd/zh-emacs --branch v1
```

Aliases
-------

  * `e` edit a file or directory by connecting to an emacs server. If
    an emacs server is not started, it will be created for you.
  * `equick` start up emacs with absolutely no initialization
    customization whatsoever. Useful for digging yourself out of a
    hole if you managed to bork your init files.

[1]: https://github.com/zimfw/zimfw
[2]: https://www.gnu.org/software/emacs/
