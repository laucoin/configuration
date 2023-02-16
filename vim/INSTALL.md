# Vim configuration

## Prerequisites

Install vim:
- Linux (Debian/Ubuntu)
    ```bash
    sudo apt install vim
    ```
- Linux (CentOS)
    ```bash
    sudo yum install vim
    ```
- MacOS
    if need install [Homebrew](https://brew.sh/)
    ```bash
    brew install vim
    ```

## Setup

1. Install [dracula theme](https://draculatheme.com/vim)
2. Create symbolic link of vimrc into your .vim folder
    ```bash
    ln -s ~/Documents/Git/Perso/configuration/vim/vimrc ~/.vim/vimrc
    ```
    If the previous command failed, maybe is due to an existing `~/.vim/vimrc`, If you don't have any existing config, you can force with `-f`:
    ```bash
    ln -f -s ~/Documents/Git/Perso/configuration/vim/vimrc ~/.vim/vimrc
    ```

## Help

If you want to understand this configuration, you can check [vim documentation](https://vimhelp.org/).