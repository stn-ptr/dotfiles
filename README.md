# dotfiles

Configuration files for various environments

## Requirements

* git
* stow

## Packages

* bash
* git
* tmux
* vim
* zsh

## Setup

### SSH

Create a new SSH key:

```shell
mkdir ~/.ssh
chmod 700 ~/.ssh
ssh-keygen -t ed25519
```

### Git

Install Git

```shell
sudo apt update
sudo apt install git
```

No more configuration needs to be 

### stow

Install stow

```shell
sudo apt install stow
```

### dotfiles


1. Clone this repository, usually to ~/.dotfiles

    git clone git@github.com:stn-ptr/dotfiles.git .dotfiles

2. Link dotfiles `stow -d .dotfiles --dotfiles <PACKAGE>`

## ToDo

* Install script

