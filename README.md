# Dat
Personal configuration files based on [Mathias Bynens's dotfiles](https://github.com/mathiasbynens/dotfiles)

## Installation

**Warning:** If you want to give these dotfiles a try, you should first fork this repository, review the code, and remove things you don’t want or need. Don’t blindly use my settings unless you know what that entails. Use at your own risk!

### Using Git and the bootstrap script

You can clone the repository wherever you want. (I like to keep it in `~/Projects/dotfiles`, with `~/dotfiles` as a symlink.) The bootstrapper script will pull in the latest version and copy the files to your home folder.

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

## Sync the fork
```bash
git fetch origin -v; git fetch upstream -v; git merge upstream/master
```

