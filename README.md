# Instructions for installing my dotfiles

This repository contains dotfiles for my system. Git and GNU Stow are used to manage the dotfiles.

## Requirements

Make sure that git and stow are installed on your system.

### Git

**Debian**
```
apt install git
```

**Arch Linux**
```
pacman -S git
```

**Fedora**
```
dnf install git
```

### Stow
**Debian**
```
apt install stow
```

**Arch Linux**
```
pacman -S stow
```

**Fedora**
```
dnf install stow
```

## Installing the dotfiles to your system

Clone the repository to your home directory
```
git clone https://github.com/klasserom1/dotfiles.git
```

After that, cd into the dotfiles directory (Assuming you're in home)

```
cd dotfiles
```

Finally, use stow to create symlinks:

```
stow .
```
