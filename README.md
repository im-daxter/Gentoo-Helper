# 🛠️ gentoo_helper

> **Automated Gentoo Linux installation script tailored for zLuuzis.**

![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)
![Shell Script](https://img.shields.io/badge/Language-Shell_Script-4EAA25?logo=gnu-bash&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Gentoo_Linux-dddaff?logo=gentoo&logoColor=ffffff)

---

## 🌐 Language / Idioma
* 🇺🇸 [English Version](#-english-version)
* 🇧🇷 [Versão em Português](#-versão-em-português)

---

## 🇺🇸 English Version

This is a Bash Shell script developed to automate the basic installation of Gentoo Linux quickly and practically, custom-configured for the user [**zLuuzis**](https://github.com/zLuuzis).

### 🚀 Features
* **Automated Network:** Configuration via `nmtui` or `nmcli`.
* **Partitioning:** Interactive drive management with `cfdisk`.
* **Automation:** Automatic formatting and mounting of partitions.
* **Optimized Build:** `make.conf` pre-tuned for native processors and NVIDIA graphics cards.
* **Syncing:** Automated Portage and Binhost synchronization.
* **Kernel & Tools:** Automatic deployment of `gentoo-kernel-bin` and essential tools.
* **Init System:** Fast setup of users, hostname, and basic services (OpenRC).

### ⚠️ Prerequisites
> [!IMPORTANT]
> Before running the script, make sure that:
> 1. You booted the computer using the official Gentoo installation ISO.
> 2. You are running as the **root** user (the script checks this automatically).
> 3. There is an active internet connection or an available network interface.

### ⚙️ How to Use
```bash
# 1. Download the script
wget [https://raw.githubusercontent.com/im-daxter/gentoo_helper/main/gentoo_helper.sh](https://raw.githubusercontent.com/im-daxter/gentoo_helper/main/gentoo_helper.sh)

# 2. Grant execution permissions
chmod +x gentoo_helper.sh

# 3. Run as root
./gentoo_helper.sh
