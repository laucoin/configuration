# ACK configuration

## Prerequisites

Install ack:
- Linux (Debian/Ubuntu)
    ```bash
    sudo apt install ack
    ```
- Linux (CentOS)
    ```bash
    sudo yum install ack
    ```
- MacOS
    if need install [Homebrew](https://brew.sh/)
    ```bash
    brew install ack
    ```

## Setup

Create symbolic link of .ackrc into your home
```bash
ln -s ~/Documents/Git/Perso/configuration/ack/ackrc ~/.ackrc
```
If the previous command failed, maybe is due to an existing `~/.ackrc`, If you don't have any existing config, you can force with `-f`:
```bash
ln -f -s ~/Documents/Git/Perso/configuration/ack/ackrc ~/.ackrc
```

## Help

If you want to understand this configuration, you can check [ack documentation](https://beyondgrep.com/documentation/).