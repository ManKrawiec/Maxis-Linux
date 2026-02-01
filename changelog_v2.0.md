Please be informed those changes applies when compared v2.0 to raw v1.1 ISO

- affinity-installer is now affinity-installer2. It supports Affinity Photo 2, Designer 2, Publisher 2 and Affinity (2025).
- The system has now been fully separated from all packages present in it. All packages are now being downloaded from linexin-repo when the ISO is being built.
- GNOME Extensions have been moved outside system-based to user-based. This is to allow for them to be updated on a regular basis.
- Linexin Center now should fully support localizations to any language.
- Added new wallpapers
- DaVinci Installer tool has been fixed, since the version present in v1.1 no longer works for the newest version of DaVinci Resolve.
- Kinexin Desktop, based on Plasma-Desktop has been added.
- Desktop Presets have now support for Kinexin Desktop. It has:
    - Kinexin theme, which is Linexin Desktop-alike
    - 10is theme, which is Windows 10-alike,
    - 11is theme, which is Windows 11-alike,
    - 2worlds theme, which is special theme best for OLED screens,
    - Plasmexin theme, which is Breeze-based theme.
- The Linexin Installer has been modified:
    - Disk Utility has been replaced with Partition Selection. Now the partitioning is automatically handled by the installer and managing already existing ones is made through Gnome Disks.
    - Installer supports selection between two desktop environments: Linexin Desktop (GNOME-based) and Kinexin Desktop (KDE Plasma-based).
- System Updater now supports updating AUR packages. It will automatically reinstall kwin-effects present in Kinexin Desktop after kwin is updated, even if turned off, to maintain all functionalities.
- Linpama (Linexin Package Manager) has been added to the system. It functions as the Pacman and AUR wrapper and allows to install packages from Linexin Center.
...and many other smaller or under the hood changes
