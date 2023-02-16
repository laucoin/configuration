# Git configuration

## Prerequisites

Install git:
- Linux (Debian/Ubuntu)
    ```bash
    sudo apt install git
    ```
- Linux (CentOS)
    ```bash
    sudo yum install git
    ```
- MacOS
    if need install [Homebrew](https://brew.sh/)
    ```bash
    brew install git
    ```

## Setup

1. Create symbolic link of .gitconfig into your home
    ```bash
    ln -s ~/Documents/Git/Perso/configuration/git/gitconfig ~/.gitconfig
    ```
    If the previous command failed, maybe is due to an existing `~/.gitconfig`, If you don't have any existing config, you can force with `-f`:
    ```bash
    ln -f -s ~/Documents/Git/Perso/configuration/git/gitconfig ~/.gitconfig
    ```
2. Make hook executable
    ```bash
    chmod +x ~/Documents/Git/Perso/configuration/git/git-templates/hooks/*
    ```

## Help

If you want to understand this configuration, you can check [git documentation](https://git-scm.com/doc).