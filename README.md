<p align="center">
  <img width="450" src="https://raw.githubusercontent.com/Pineconium/ChoacuryOS/main/projectlogo.png">
</p>

[![GitHub release](https://img.shields.io/github/release/Pineconium/ChoacuryOS?include_prereleases=&sort=semver&color=blue)](https://github.com/Pineconium/ChoacuryOS/releases/)
[![License](https://img.shields.io/badge/License-GPL--3.0-blue)](#license)
[![issues - ChoacuryOS](https://img.shields.io/github/issues/Pineconium/ChoacuryOS)](https://github.com/Pineconium/ChoacuryOS/issues)

[View documentation](https://teamchoacury.github.io/docs/)

Choacury, (pronounced as coch-curry or /kʰɔx-ˈkʌr.i/), is a custom-built operating system written in C, C++ and Assembly. Choacury is currently in a very **Pre-Alpha** stage, meaning some stuff isn't complete yet...

![ChoacuryScreenshot](https://raw.githubusercontent.com/Pineconium/ChoacuryOS/main/choacuryscreenshot.png)

If you want to help out on the project, feel free to contribute to the project! (see TODO.MD for what is needed doing). You can also modify Choacury to your liking if you want to make your own OS! You can also join the [development Discord server](https://discord.gg/qhgDWrzCvg) if you want.

# System Requirements
Currently, Choacury only works best with virtual machines. However, you *can* use real hardware if you want, just there might be some issues that will be fixed down the line.

For VirtualBox Users, here are the recommended VM requirements:
- Operating System: Other/Unknown
- Base Memory: 64 MB.
- Video Memory: 9 MB.
- Hard Disk: 2.00 GB.

# Compiling Choacury.
If you want to compile Choacury from the source code, here's what you'll need.
1. NASM, GCC, GRUB Multiboot, Makefile, and QEMU installed. (the compiler uses the `x86_64` version of QEMU. If you don't use that version of QEMU, replace `qemu-system-x86_64` in the compiler shell script with your version of QEMU)
2. A computer running any Linux distro (recommended, but there is a batch script for Windows devices as long as you have WSL installed).

# Contributing
Please read the [contribution guidelines](/CONTRIBUTING.md), and [code of conduct](/CODE_OF_CONDUCT.md) before you contribute.
**All contributions are welcomed! ❤️**
