# Dat
Personal configuration files based on [Mathias Bynens's dotfiles](https://github.com/mathiasbynens/dotfiles)

## Installation
```bash
git clone git@github.com:ucarmetin/dat.git && cd dotfiles && source bootstrap.sh
```

## Update
`cd` into your local `dotfiles` repository and then:

```bash
source bootstrap.sh

# Avoid confirmation prompt
set -- -f; source bootstrap.sh
```

## OSX defaults
```bash
source .osx
```

## Install brew & cask packages
```bash
source brew.sh
source brew-cask.sh
```

