# .dotfiles

## Similar projects

[Paul Irish's dotfiles](https://github.com/paulirish/dotfiles).
[Mathias's readme](https://github.com/mathiasbynens/dotfiles/).


## Overview of files

#### shell environment
* `.aliases`
* `.bash_profile`
* `.bash_prompt`
* `.extra` - not included. Create a file called `.extra` which you do not commit to this repo and just keep in your `~/`


## Mac OS X defaults

When setting up a new Mac, you may want to set some sensible OS X defaults (__untested__):

```bash
./.osx
```


## Installation

```bash
git clone https://github.com/stefandressler/dotfiles && cd dotfiles && ./sync.sh
```

To update later on, just run the sync again. (__untested__)
