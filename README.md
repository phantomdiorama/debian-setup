# debian-setup
 
## debian install

Debian XFCE Non-free: https://cdimage.debian.org/cdimage/unofficial/non-free/cd-including-firmware/current-live/amd64/iso-hybrid/

## sources

add `contrib` and `non-free` to **sources.list** (see [here](https://wiki.debian.org/SourcesList))

```
sudo nano /etc/apt/sources.list
```

## programs

```
sudo apt install netsurf-gtk vlc cmus htop pandoc ripgrep rclone wget focuswriter
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

## Maintenance

```
sudo apt update
sudo apt upgrade
```

## Further Set Up

- [Looks](/looks.md)
- [Usability](/use.md)
- [Firefox addons](/firefox.md)
