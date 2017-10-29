# mac-setup

## Starters
Got to http://sourabhbajaj.com/mac-setup/ and follow instructions to install XCode, Homebrew (for casks see below), iTerm2 with Oh My Zsh...

## Apps

### Casks

```sh
brew cask install \
    atom \
    alfred \
    appcleaner \
    caffeine \
    cheatsheet \
    docker \
    dropbox \
    flux \
    google-chrome \
    handbrake \
    1password \
    spectacle \
    sublime-text \
    totalfinder \
    vlc \
    spotify \
    sequel-pro \
    sourcetree \
    virtualbox \
    the-unarchiver \
    

```

### [Brave browser](https://brave.com/download/)

### [Gimp on Mac](http://gimp.lisanet.de/Website/Download.html)

### [`pdftk`](https://www.pdflabs.com/tools/pdftk-server/)

## Python

Use `brew install python2 python3` along with 

```sh
pip2 install --upgrade pip setuptools
pip3 install --upgrade pip setuptools wheel
```

Add Brew's `python2` to `PATH` to use it as `python`. Just follow instructions after `brew install`.

## Node.js
Install `nvm` as instructed. Install `yarn`:
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


