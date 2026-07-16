# YoctoTraining

**Custom Embedded Linux Image Generation with Yocto Project**

![Linux](https://img.shields.io/badge/OS-Linux-yellow)
![Yocto](https://img.shields.io/badge/Yocto-Project-green)
![ARM](https://img.shields.io/badge/Arch-ARM-red)
![QEMU](https://img.shields.io/badge/Emulator-QEMU-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📖 Overview

Hands-on training materials for building custom embedded Linux images with the Yocto Project. Covers the complete pipeline from Poky/BitBake fundamentals to Raspberry Pi 3 deployment.

## 📚 Topics

| # | Topic | Description |
|:-:|:------|:------------|
| 1 | Embedded Linux | Bootloader, kernel, rootfs fundamentals |
| 2 | Yocto Overview | Poky, BitBake, OpenEmbedded ecosystem |
| 3 | Build Setup | Host preparation, dependencies, configuration |
| 4 | Metadata & Layers | Recipes, configurations, layer priority |
| 5 | BitBake | Task execution, caching, dependencies |
| 6 | QEMU | x86_64 and ARM virtual targets |
| 7 | Custom Images | Adding packages, modifying configurations |
| 8 | Raspberry Pi 3 | Real hardware build and deployment |

## 🚀 Quick Start

```bash
git clone git://git.yoctoproject.org/poky
cd poky && source oe-init-build-env
bitbake core-image-minimal
runqemu qemux86-64
```

## 📄 License

MIT License.

## 📬 Contact

**Mustafa YILMAZ** — Embedded Software Engineer
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black)](https://github.com/mustafaylmz1995)
