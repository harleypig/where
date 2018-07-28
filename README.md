## where

An improved `which`.

`where` will identify a keyword (or builtin), a file, a function (and where it
was define) and an alias.

## Install

Create a symbolic link to `where` in whatever directory you are using as your bin directory.

## Example

```
$ where ls bad compgen gco gtoplevel
ls is hashed (/bin/ls)
bash: type: bad: not found

compgen is a shell builtin
gco 132 /home/harleypig/projects/dotfiles/.bash_sources.d/git
gtoplevel 18 /home/harleypig/projects/dotfiles/.bash_sources.d/git
```
