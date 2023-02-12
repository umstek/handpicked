# System configuration for Ubuntu 22.04 (or similar and/or on WSL2)

## Upgrade packages

```sh
sudo apt update
sudo apt upgrade
sudo apt autoremove
```

## Configure ZSH

```sh
sudo apt install zsh
chsh -s $(which zsh)
# restart shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
omz theme set agnoster
```

## Create home folders

```sh
# whatever you want
mkdir src work x
```

## Configure Git

```sh
git config --global init.defaultBranch main # better default branch name
git config --global user.name "REPLACE WITH YOUR NAME"
git config --global user.email replace-with-your@email.com
git config --global core.editor "code --wait" # use vscode to edit commit messages instead of nano and vim
git config --global core.autocrlf false # stop Windows messing with file endings (not needed for linux actually)
```

## Install Python 3 and set defaults

```sh
sudo apt install python3 # this is probably already installed
sudo update-alternatives --install /usr/bin/python python /usr/bin/python3 1
```

## Install NodeJS

```sh
# Use latest NVM script from here https://github.com/nvm-sh/nvm
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
nvm install --lts # or nvm install node for latest non-lts versions
```
