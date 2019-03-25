# handy-shell-functions

A collection of shell functions, scripts and aliases that can come in handy (zshell is used, on manjaro for the scripts)

-----

## Architecture

`./Aliases` is meant as a file in `~/.alias`
`./Functions` is meant as a file in `~/.functions`

Both should be sourced in .zshrc (or the equivalent for other shells) as such :
```
source ~/.alias
source ~/.functions
```
In addition, `./Bin` in this repository is meant as the folder `~/.bin`, and should be added to the path with `PATH=$PATH:~/.bin` in `~/.profile`.

## Contents

### Aliases

+ SSH
+ DETACH
+ LaTex
+ General
+ kill alarm (using shalarm, https://github.com/jahendrie/shalarm, can be handy if started with computer)

### Functions

+ kil - kill a process by name
+ detach - detach a process from the shell (disown) and remove the text output
+ gitUser - set the right user for your git repo authomatically
+ ex - extract, from the Manjaro bash_profile
+ show your personal functions and stuff

### Bin

+ cleanup - update, remove some stuff, show latest errors - should not be used without understanding
+ light - lightens the load on your computer if you're on battery budget
