# handy-shell-functions

A collection of shell functions, scripts and aliases that can come in handy (zshell is used, on manjaro for the scripts)

**Now that I've switch to [chezmoi](https://github.com/twpayne/chezmoi) to manage my files, I will archive this repository. See my [dotfiles](https://github.com/vogu66/dotfiles) for my current repo. Although at the time of writing not everything is there yet since I still need to remove some of the personal data. -- 2020-06-23**

-----

## Architecture

`./alias` is meant as a file in `~/.alias`
`./functions` is meant as a file in `~/.functions`

Both should be sourced in .zshrc (or the equivalent for other shells) as such :
```
source ~/.alias
source ~/.functions
```
In addition, `./bin` in this repository is meant as the folder `~/.bin`, and should be added to the path with `PATH=$PATH:~/.bin` in `~/.profile`.

## Contents

### Aliases

+ SSH
+ DETACH
+ LaTex
+ General
+ kill alarm (using shalarm, https://github.com/jahendrie/shalarm, can be handy if started with computer)

### Functions

+ kil - kill a process by name (twice pkill because programs like Discord behave weirdly)
+ detach - detach a process from the shell (disown) and remove the text output
+ gitUser - set the right user for your git repo authomatically (needs to be adapted to the right person)
+ ex - extract, from the Manjaro bash_profile
+ show your personal functions and stuff

### Bin

+ cleanup - update, remove some stuff, show latest errors - should not be used without understanding
+ gitUser - the backend behind gitUser from functions
+ light - lightens the load on your computer if you're on battery budget
+ heavy - allows to restart stuff that has been shut down by light -- doesn't take the stuff from light, needs to be adjusted manually.
