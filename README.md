# m
m is a lightweight tool for working with bookmarks in the terminal.

## Usage
m uses `$HOME/.marks` to store bookmarks. Bookmarks can be managed by editing
the marks file in your favorite editor. m even provide a shortcut for doing
this: `m -e`.

### Structure
The structure of `$HOME/.marks` is very similar to how you define hosts in `/etc/hosts`. Bookmarks are define in the format: `<key> <path>`.

**Example**

    hosts   /etc/hosts
    awesome /code/work/projects/awesome

### Command-line interface

    $ m
    Usage:
      m [OPTION] [BOOKMARK]

    General Options:
      -h, --help    Usage
      -l, --list    List bookmarks
      -e, --edit    Edit BOOKMARK with $EDITOR

## Installation
Put [m](https://raw.github.com/KevinSjoberg/m/master/m) in a directory of your
choice. I chose `$HOME/bin/m`. Source it via your `$HOME/.bashrc`.

## Alternatives

  * [bashmarks](https://github.com/huyng/bashmarks)
