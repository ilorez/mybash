## Overview of Ilorez's shell Configuration

### Description
This repo contain some files like functions, aliases, exports and linker which is the mean files and some other files like personal/intra that is like what name say a personal file Ilorez use in some cases. 

### how to use
- first should clone the repo
- after that dependent on shell type that you use [zsh, bash ...].
For example:

```bash
vim ~/.bashrc
or 
vim ~/.zshrc
```

- now you should include the linker from repo that you clone
- and include functions || aliases || imports like what want

```bash
# Include linker
source $HOME/path/to/cloned/repo/linker
# for example
# source $HOME/.myshells/linker

# let's now include:
# aliases
source $ALIASES_FILE
# functions
source $FUNCTIONS_FILE
# exports
source $EXPORTS_FILE
```

NOTE: change the MY_SHELLS_PATH  in 'linker' file with your path to shells folder which mean the path to repo that you clone

