# mac-setup

## Starters
Got to http://sourabhbajaj.com/mac-setup/ and follow instructions to install XCode, Homebrew (for casks see below), iTerm2 with Oh My Zsh...

## Apps

### Casks

```sh
brew cask install \
    1password \
    atom \
    brave \
    caffeine \
    cheatsheet \
    docker \
    dropbox \
    elm-platform \
    flux \
    google-chrome \
    handbrake \
    lisanet-gimp \
    sequel-pro \
    sourcetree \
    spectacle \
    spotify \
    sublime-text \
    the-unarchiver \
    virtualbox \
    vlc \
    

```

### [Brave browser](https://brave.com/download/)

### [`pdftk`](https://www.pdflabs.com/tools/pdftk-server/)

## Python

Use `brew install python2 python3` along with 

```sh
pip2 install --upgrade pip setuptools
pip3 install --upgrade pip setuptools wheel
```

Add Brew's `python2` to `PATH` to use it as `python`. Just follow instructions after `brew install`.

## Node.js
Install `nvm` with these instructions to get the latest version: https://github.com/creationix/nvm#installation

Install `yarn`:
```sh
brew install yarn --without-node
```

## Elm
```sh
brew cask install elm-platform
```

## Local databases
```sh
brew install mysql sqlite3 mongodb postgresql
```

Remember to add Brew's `sqlite3` to `PATH`.

Use `brew services run|start|stop|restart <formulae>|--all` to start/stop/restart database services.


