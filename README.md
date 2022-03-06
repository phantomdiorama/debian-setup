## debian install

Debian XFCE Non-free: https://cdimage.debian.org/cdimage/unofficial/non-free/cd-including-firmware/current-live/amd64/iso-hybrid/

## sources (optional)

add `contrib` and `non-free` to **sources.list** (see [here](https://wiki.debian.org/SourcesList))

```
sudo nano /etc/apt/sources.list
```

## programs

### shell

```
sudo apt install htop pandoc ripgrep rclone wget cmus 
```

### gui

```
sudo apt install netsurf-gtk vlc focuswriter rofi
```

### skype

```
wget https://go.skype.com/skypeforlinux-64.deb
sudo apt install ./skypeforlinux-64.deb
```

### zola

```
wget https://github.com/barnumbirr/zola-debian/releases/download/v0.15.3-1/zola_0.15.3-1_amd64_bullseye.deb
sudo dpkg -i zola_<version>_amd64_debian_<debian_version>.deb
```

## maintenance

```
sudo apt update
sudo apt upgrade
```

## further set up

- [Looks](/looks.md)
- [Usability](/use.md)
- [Firefox addons](/firefox.md)
