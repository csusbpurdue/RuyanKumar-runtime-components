# runtime-components

This repo has my config files (bashrc, zshrc, vimrc, gdbinit, gitconfig) for CS class. I put them here so I can set up a new computer or server without redoing everything.

## Files

- .bashrc - settings for bash
- .zshrc - settings for zsh (the default shell on my Mac)
- .vimrc - settings for vim
- .gdbinit - settings for gdb
- .gitconfig - settings for git
- install.sh - copies these files into my home folder

## How to use

    git clone git@github.com:RuyanKumar/runtime-components.git
    cd runtime-components
    ./install.sh

The script backs up any old files before it replaces them. Open a new terminal afterward so the changes load.
