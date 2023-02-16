# Zsh configuration

## Prerequisites

Install zsh, git and curl:
- Linux (Debian/Ubuntu)
    ```bash
    sudo apt install zsh git curl
    ```
- Linux (CentOS)
    ```bash
    sudo yum install zsh git curl
    ```
- MacOS
    if need install [Homebrew](https://brew.sh/)
    ```bash
    brew install zsh git curl
    ```

## Setup

1. Change the default shell:
    ```bash
    chsh -s $(which zsh)
    ```
2. Install oh-my-zsh:
    ```bash
    sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
    ```
3. Install [Inconsolata font](https://fonts.google.com/specimen/Inconsolata) and change your terminal default font
4. Install zsh-autosuggestions plugin:
    ```bash
    git clone https://github.com/zsh-users/zsh-autosuggestions ~/.zsh/zsh-autosuggestions
    ```
5. Install zsh-syntax-highlighting plugin:
    ```bash
    git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
    ```
6. Create symbolic link of .zshrc into your home
    ```bash
    ln -s ~/Documents/Git/Perso/configuration/zsh/zshrc ~/.zshrc
    ```
    If the previous command failed, maybe is due to an existing `~/.zshrc`, If you don't have any existing config, you can force with `-f`:
    ```bash
    ln -f -s ~/Documents/Git/Perso/configuration/zsh/zshrc ~/.zshrc
    ```