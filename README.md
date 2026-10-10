# bazzite-eraque &nbsp; [![bluebuild build badge](https://github.com/erocks26/bazzite-eraque/actions/workflows/build.yml/badge.svg)](https://github.com/erocks26/bazzite-eraque/actions/workflows/build.yml)

Hi! I'm Ethan and this is the custom image I maintain for my personal computer. Right now it's pretty empty in here but it may grow over time. Who knows! Feel free to use this if you want I guess though I can't exactly promise support lol. 

## Features

- Bazzite core
- Wallpaper Engine KDE Plugin built in
- kvantum theming engine
- Virtualization (QEMU + KVM + libvirt) available

## Verification

These images are signed with [Sigstore](https://www.sigstore.dev/)'s [cosign](https://github.com/sigstore/cosign). You can verify the signature by downloading the `cosign.pub` file from this repo and running the following command:

```bash
cosign verify --key cosign.pub ghcr.io/erocks26/bazzite-eraque
```
