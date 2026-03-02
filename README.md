# Maxis Linux

Maxis Linux is a custom Arch-based Linux distribution focused on a clean live
environment and a custom installer workflow.

This repository contains the ArchISO profile, live filesystem customizations,
boot configuration, and installer assets used to build the ISO image.

## Preview

![Maxis Linux preview](./hyperland-just-basic-v0-cw1l6luc9z1b1.webp)

## Highlights

- Arch Linux base with `pacman` ecosystem
- Custom live environment under `airootfs/`
- Integrated Maxis installer
- Calamares modules and post-install scripts
- Custom branding and boot assets

## Repository layout

- `airootfs/`: files copied into the live system root
- `packages.x86_64`: packages included in the ISO
- `profiledef.sh`: ArchISO profile metadata and build settings
- `pacman.conf`: package manager configuration for ISO build
- `efiboot/`, `grub/`, `syslinux/`: bootloader configs
- `local/repo/`: local package repository used during build

## Build ISO (ArchISO)

1. Install required tools:
   ```bash
   sudo pacman -S archiso
   ```
2. Build from repository root:
   ```bash
   cd Linexin
   sudo mkarchiso -v .
   ```
3. Output ISO appears in `out/`.

## Download

There is currently no official public ISO mirror.
Please build the ISO yourself from this repository using the steps above.

## Status

The project is under active development and may contain bugs.

## License

This project is open source and licensed under the terms in
[LICENSE](./LICENSE).
