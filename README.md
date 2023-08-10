# fwcd's Arch Repository

An [unofficial package repository](https://wiki.archlinux.org/title/unofficial_user_repositories) hosting prebuilt/binary packages for Arch Linux (`pacman`), mainly sourced from the [AUR](https://aur.archlinux.org).

## Usage

Add the following to your `/etc/pacman.conf`:

```
[fwcd]
Server = https://github.com/fwcd/arch-repo/releases/latest/download
SigLevel = Never
```

## See also

- [`archlinuxarm-images`](https://github.com/fwcd/archlinuxarm-images.git) (Unofficial prepartitioned images of Arch Linux ARM)
- [`archlinuxarm-docker`](https://github.com/fwcd/archlinuxarm-docker.git) (Unofficial Docker images of Arch Linux ARM)
