# YoctoTraining

**Custom Embedded Linux Image Generation with Yocto Project**

![Linux](https://img.shields.io/badge/OS-Linux-yellow)
![Yocto](https://img.shields.io/badge/Yocto-Project-green)
![ARM](https://img.shields.io/badge/Arch-ARM-red)
![QEMU](https://img.shields.io/badge/Emulator-QEMU-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📖 Overview

Hands-on training materials for building custom embedded Linux images with the Yocto Project. Covers the complete build pipeline — from Poky/BitBake fundamentals to Raspberry Pi 3 target deployment and QEMU emulation.

---

## 📚 Topics Covered

| # | Topic | Description |
|:-:|:------|:------------|
| 1 | Embedded Linux Fundamentals | Bootloader, kernel, rootfs |
| 2 | Yocto Project Overview | Poky, BitBake, OpenEmbedded |
| 3 | Build System Setup | Host preparation, dependencies |
| 4 | Metadata & Layers | Recipes, configurations, layer priority |
| 5 | BitBake | Task execution, dependencies, caching |
| 6 | QEMU Emulation | x86_64 & ARM virtual targets |
| 7 | Custom Images | Adding packages, modifying configs |
| 8 | Raspberry Pi 3 | Real hardware deployment |

---

## 🚀 Quick Start

```bash
sudo apt-get install gawk wget git diffstat unzip texinfo gcc \
  build-essential chrpath socat cpio python3 python3-pip \
  python3-pexpect xz-utils debianutils iputils-ping

git clone git://git.yoctoproject.org/poky
cd poky
source oe-init-build-env
bitbake core-image-minimal
runqemu qemux86-64
```

---

## 📄 License

MIT License.
