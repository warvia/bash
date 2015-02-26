#Just a place to store some bash config files.

#A nice ll alias for the OS X terminal. Just add that line to either .bashrc or .bash_profile
alias ll='ls -lAhG'

#An alias for running the bash calculator with decimal support for results. This tells the bash calculator to define the standard math library.
alias bc='bc -l'

#Some .vimrc configuration changes, this sets the color to brighter shades when viewed on a black background.
filetype plugin indent on
set term=builtin_ansi
colo desert
syntax on

