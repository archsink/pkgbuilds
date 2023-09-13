# fwcd's Arch Repository

[![Build](https://github.com/fwcd/arch-repo/actions/workflows/build.yml/badge.svg)](https://github.com/fwcd/arch-repo/actions/workflows/build.yml)

An [unofficial package repository](https://wiki.archlinux.org/title/unofficial_user_repositories) for Arch Linux (`pacman`), mainly sourced from the [AUR](https://aur.archlinux.org). Binaries are built and deployed for the following architectures:

| Architecture | Release | Build |
| ------------ | ------- | ----- |
| [x86_64](https://github.com/fwcd/arch-repo-x86_64) | [![Release](https://img.shields.io/github/v/release/fwcd/arch-repo-x86_64)](https://github.com/fwcd/arch-repo-x86_64/releases/latest) | [![Build](https://github.com/fwcd/arch-repo-x86_64/actions/workflows/build.yml/badge.svg)](https://github.com/fwcd/arch-repo-x86_64/actions/workflows/build.yml) |
| [aarch64](https://github.com/fwcd/arch-repo-aarch64) | [![Release](https://img.shields.io/github/v/release/fwcd/arch-repo-aarch64)](https://github.com/fwcd/arch-repo-aarch64/releases/latest) | [![Build](https://github.com/fwcd/arch-repo-aarch64/actions/workflows/build.yml/badge.svg)](https://github.com/fwcd/arch-repo-aarch64/actions/workflows/build.yml) |
| [armv7h](https://github.com/fwcd/arch-repo-armv7h) | [![Release](https://img.shields.io/github/v/release/fwcd/arch-repo-armv7h)](https://github.com/fwcd/arch-repo-armv7h/releases/latest) | [![Build](https://github.com/fwcd/arch-repo-armv7h/actions/workflows/build.yml/badge.svg)](https://github.com/fwcd/arch-repo-armv7h/actions/workflows/build.yml) |
| [pentium4](https://github.com/fwcd/arch-repo-pentium4) | [![Release](https://img.shields.io/github/v/release/fwcd/arch-repo-pentium4)](https://github.com/fwcd/arch-repo-pentium4/releases/latest) | [![Build](https://github.com/fwcd/arch-repo-pentium4/actions/workflows/build.yml/badge.svg)](https://github.com/fwcd/arch-repo-pentium4/actions/workflows/build.yml) |
| [riscv64](https://github.com/fwcd/arch-repo-riscv64) | [![Release](https://img.shields.io/github/v/release/fwcd/arch-repo-riscv64)](https://github.com/fwcd/arch-repo-riscv64/releases/latest) | [![Build](https://github.com/fwcd/arch-repo-riscv64/actions/workflows/build.yml/badge.svg)](https://github.com/fwcd/arch-repo-riscv64/actions/workflows/build.yml) |

## Usage

Add the following to your `/etc/pacman.conf`:

```
[fwcd]
Server = https://github.com/fwcd/arch-repo-$arch/releases/latest/download
SigLevel = Never
```

## See also

- [`docker-archlinux`](https://github.com/fwcd/docker-archlinux) (Unofficial multi-platform Docker images of Arch Linux)
- [`archlinuxarm-images`](https://github.com/fwcd/archlinuxarm-images) (Unofficial prepartitioned images of Arch Linux ARM)
