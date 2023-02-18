# ubuntu_snippets
Snippets for Ubuntu Operating System

## Customize Screen
My favorite adjustments can be done using `dconf-editor` & `gnome tweaks`, relevant articles are following:
### Customize Dock Panel & Adjust Title Bar
```
gsettings set org.gnome.shell.extensions.dash-to-dock extend-height false
gsettings set org.gnome.shell.extensions.dash-to-dock dock-position BOTTOM
gsettings set org.gnome.shell.extensions.dash-to-dock dash-max-icon-size 32
gsettings set org.gnome.shell.extensions.dash-to-dock unity-backlit-items false
gsettings set  org.gnome.desktop.wm.preferences button-layout 'close,minimize,maximize:'

# gsettings set org.gnome.shell.extensions.dash-to-dock transparency-mode FIXED
```

### Brightness Control
* [Brightness Control](https://askubuntu.com/a/397104)

## Install GPU Libraries
1. Install NVIDIA Drivers and check `nvidia-smi`
2. Install the Docker & NVIDIA Docker 
3. Install the Miniconda
    
    a. Create environment and install `tensorflow-gpu` or `pytorch-gpu` (according to your need)

## Docker Directories
1. You can change docker root directory by following [GUIDE](https://blog.adriel.co.nz/2018/01/25/change-docker-data-directory-in-debian-jessie)

## VS CODE
1. Disable unresolved imports `"python.languageServer": "Jedi"`

## Usefuls
1. [Auto Mount Directory](https://www.linuxbabe.com/desktop-linux/how-to-automount-file-systems-on-linux)
2. **AnyDesk Auto Login** `sudo nano /etc/gdm3/custom.conf`

## Writeup Setup
1. Install Latex & TexStudio using this [Link](https://linuxconfig.org/how-to-install-latex-on-ubuntu-18-04-bionic-beaver-linux)
