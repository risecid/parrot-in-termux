# parrot-in-termux

 Contact [![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/rian1337)

# Version Info
Installer Version 1.0

## What's This?

This is a script that allows you to install Parrot Os in your termux application without a rooted device

### Installations Guide

1. Update termux: `apt-get update && apt-get upgrade -y`
2. Install wget: `apt-get install wget proot git curl -y`
3. Go to HOME folder: `cd ~`
4. Download script: `git clone https://github.com/RiSecID/parrot-in-termux.git`
5. Go to script folder: `cd parrot-in-termux`
6. Give execution permission: `chmod +x parrot.sh`
7. Run the script: `bash parrot.sh -y`
8. Now just start ubuntu: `./startparrot.sh`

### Fixed All Trouble
1. Remove old sources "rm /etc/apt/sources.list"
2. Add new repository in sources list with "echo "deb http://mirrors.ustc.edu.cn/parrot parrot main contrib non-free" >> /etc/apt/sources.list"
3. Import new gpg key "wget http://archive.parrotsec.org/parrot/misc/archive.gpg -O $2/etc/apt/trusted.gpg.d/parrot-archive-key.asc"

### Information
[![Stars](https://img.shields.io/packagist/stars/RiSecID/parrot-in-termux)
[![Languages](https://img.shields.io/github/languages/count/RiSecID/parrot-in-termux)
[![License](https://img.shields.io/hexpm/l/plug)
