# Linux Environment Setup

**Author:** Donny Luc  
**Date:** May 2022


## Package Commands

```bash
sudo apt install update
sudo apt install upgrade
```


## Set Default Text Editor

```bash
sudo update-alternatives --config editor
```


## Download Ultimate Vimrc

Follow the instructions [here](https://github.com/amix/vimrc).


## Set Password Feedback

Run the command `sudo visudo` and append `pwfeedback` to the first Defaults settings:

```vim
Defaults        env_reset,pwfeedback
```
