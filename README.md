# ubuntu_snippets
Snippets for Ubuntu Operating System

## Customize Screen
My favorite adjustments can be done using `dconf-editor` & `gnome tweaks`, relevant articles are following:
* [Customize Dock Panel](https://linuxconfig.org/how-to-customize-dock-panel-on-ubuntu-18-04-bionic-beaver-linux)
* [Adjust Title Bar](https://askubuntu.com/a/975432)
* Customize Terminal: `export PS1="\e[0;32m$(whoami):${PWD/*\//}# \e[m"`

## Install GPU Libraries
1. Install NVIDIA Drivers and check `nvidia-smi`
2. Install the Anaconda
3. Create environment and install `tensorflow-gpu` or `pytorch-gpu` (according to your need)

## Docker Directories
1. You can change docker root directory by following [GUIDE](https://blog.adriel.co.nz/2018/01/25/change-docker-data-directory-in-debian-jessie)

## Writeup Setup
1. Install Latex & TexStudio using this [Link](https://linuxconfig.org/how-to-install-latex-on-ubuntu-18-04-bionic-beaver-linux)
