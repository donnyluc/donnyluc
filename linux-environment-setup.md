# Linux Environment Setup

**Author:** Donny Luc  
**Date:** May 2022


## Package Commands

```bash
sudo apt update
sudo apt upgrade
```


## Set Vim As Default Text Editor

```bash
sudo update-alternatives --config editor
```

Download ultimate vimrc [here](https://github.com/amix/vimrc).

## Set Password Feedback

Run the command `sudo visudo` and append `pwfeedback` to the first Defaults settings:

```vim
Defaults        env_reset,pwfeedback
```


## Download Oh My Zsh
```bash
sudo apt install git zsh -y
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```






