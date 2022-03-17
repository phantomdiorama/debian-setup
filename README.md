## debian install

Debian XFCE Non-free: [download](https://cdimage.debian.org/cdimage/unofficial/non-free/cd-including-firmware/current-live/amd64/iso-hybrid/)

#### sources (optional)

add `contrib` and `non-free` to **sources.list** (see [here](https://wiki.debian.org/SourcesList))

```
sudo nano /etc/apt/sources.list
```

## programs

#### shell

```
sudo apt install htop pandoc ripgrep rclone wget cmus 
```

#### gui

```
sudo apt install netsurf-gtk vlc focuswriter rofi geany
```

#### skype

```
wget https://go.skype.com/skypeforlinux-64.deb
sudo apt install ./skypeforlinux-64.deb
```

#### zola

```
wget https://github.com/barnumbirr/zola-debian/releases/download/v0.15.3-1/zola_0.15.3-1_amd64_bullseye.deb
sudo dpkg -i zola_<version>_amd64_debian_<debian_version>.deb
```

## looks

get greybird gtk theme & papirus icons:

```
sudo apt install greybird-gtk-theme
sudo apt install papirus-icon-theme
```

## further set up

- [Usability](/use.md)
- [Firefox addons](/firefox.md)
- [dots](/dots.md)