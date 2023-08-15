# fwcd's Arch Repository

[![Build](https://github.com/fwcd/arch-repo/actions/workflows/build.yml/badge.svg)](https://github.com/fwcd/arch-repo/actions/workflows/build.yml)

An [unofficial package repository](https://wiki.archlinux.org/title/unofficial_user_repositories) for Arch Linux (`pacman`), mainly sourced from the [AUR](https://aur.archlinux.org). Binaries are provided for [x86_64](https://github.com/fwcd/arch-repo-x86_64) and [aarch64](https://github.com/fwcd/arch-repo-aarch64).

## Usage

Add the following to your `/etc/pacman.conf`:

```
[fwcd]
Server = https://github.com/fwcd/arch-repo-$arch/releases/latest/download
SigLevel = Never
```

## See also

- [`archlinuxarm-images`](https://github.com/fwcd/archlinuxarm-images.git) (Unofficial prepartitioned images of Arch Linux ARM)
- [`archlinuxarm-docker`](https://github.com/fwcd/archlinuxarm-docker.git) (Unofficial Docker images of Arch Linux ARM)
