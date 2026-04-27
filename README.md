# VacuumTube (RPM Support Fork)
<p>
    <a href="https://github.com/elytraVIII/VacuumTube-rpm/stargazers">
      <img alt="Stars" title="Stars" src="https://img.shields.io/github/stars/elytraVIII/VacuumTube-rpm?style=shield&label=%E2%AD%90%20Stars&branch=main&kill_cache=1%22" />
    </a>
    <a href="https://github.com/elytraVIII/VacuumTube-rpm/releases/latest">
      <img alt="Latest Release" title="Latest Release" src="https://img.shields.io/github/v/release/elytraVIII/VacuumTube-rpm?style=shield&label=%F0%9F%9A%80%20Release">
    </a>
    <a href="https://github.com/elytraVIII/VacuumTube-rpm/blob/main/LICENSE">
      <img alt="License" title="License" src="https://img.shields.io/github/license/elytraVIII/VacuumTube-rpm?label=%F0%9F%93%9C%20License" />
    </a>
</p>

VacuumTube is an unofficial wrapper of YouTube Leanback (the console and Smart TV version of YouTube) for the desktop, with a built-in adblocker and minor enhancements. This fork is dedicated to providing and maintaining **RPM support** for Fedora, RHEL, Rocky Linux, and openSUSE.

## Installing

This fork provides RPM packages for RPM-based Linux distributions.

### Fedora / RHEL / Rocky Linux / openSUSE

- [x86_64 (.rpm)](https://github.com/elytraVIII/VacuumTube-rpm/releases/latest/download/VacuumTube-x86_64.rpm)
- [Arm® 64 (.rpm)](https://github.com/elytraVIII/VacuumTube-rpm/releases/latest/download/VacuumTube-arm64.rpm)

## Building from Source

```sh
git clone https://github.com/elytraVIII/VacuumTube-rpm
cd VacuumTube-rpm

# Install Dependencies
npm i

# Run without packaging
npm run start

# Package RPM builds
npm run linux:build
```

## Original Project
For other formats like Flatpak, AppImage, .deb, or Windows/macOS builds, please visit the original repository: [shy1132/VacuumTube](https://github.com/shy1132/VacuumTube).
