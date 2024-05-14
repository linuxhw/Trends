Linux - Hardware Trends
-----------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Desktop/README.md) and [notebooks](/Notebook/README.md).

Distribution-specific reports: [Arch](/Dist/Arch), [ArcoLinux](/Dist/ArcoLinux), [BlackPanther](/Dist/BlackPanther), [CentOS](/Dist/CentOS), [Clear Linux](/Dist/Clear_Linux), [Debian](/Dist/Debian), [Elementary](/Dist/Elementary), [EndeavourOS](/Dist/EndeavourOS), [Endless](/Dist/Endless), [Fedora](/Dist/Fedora), [Garuda Linux](/Dist/Garuda_Linux), [Gentoo](/Dist/Gentoo), [Kali](/Dist/Kali), [KDE neon](/Dist/KDE_neon), [Kubuntu](/Dist/Kubuntu), [Linux Mint](/Dist/Linux_Mint), [Manjaro](/Dist/Manjaro), [OpenMandriva](/Dist/OpenMandriva), [openSUSE](/Dist/openSUSE), [Pop!_OS](/Dist/Pop!_OS), [Red OS](/Dist/Red_OS), [ROSA](/Dist/ROSA), [SteamOS](/Dist/SteamOS), [Ubuntu MATE](/Dist/Ubuntu_MATE), [Ubuntu](/Dist/Ubuntu), [Xubuntu](/Dist/Xubuntu), [Zorin](/Dist/Zorin).

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: Apr, 2024.

Contents
--------

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
  - [ Kernel                   ](#kernel)
  - [ Kernel Family            ](#kernel-family)
  - [ Kernel Major Ver.        ](#kernel-major-ver)
  - [ Arch                     ](#arch)
  - [ DE                       ](#de)
  - [ Display Server           ](#display-server)
  - [ Display Manager          ](#display-manager)
  - [ OS Lang                  ](#os-lang)
  - [ Boot Mode                ](#boot-mode)
  - [ Filesystem               ](#filesystem)
  - [ Part. scheme             ](#part-scheme)
  - [ Dual Boot with Linux/BSD ](#dual-boot-with-linuxbsd)
  - [ Dual Boot (Win)          ](#dual-boot-win)

* [ Board ](#board)
  - [ Vendor                   ](#vendor)
  - [ Model                    ](#model)
  - [ Model Family             ](#model-family)
  - [ MFG Year                 ](#mfg-year)
  - [ Form Factor              ](#form-factor)
  - [ Secure Boot              ](#secure-boot)
  - [ Coreboot                 ](#coreboot)
  - [ RAM Size                 ](#ram-size)
  - [ RAM Used                 ](#ram-used)
  - [ Total Drives             ](#total-drives)
  - [ Has CD-ROM               ](#has-cd-rom)
  - [ Has Ethernet             ](#has-ethernet)
  - [ Has WiFi                 ](#has-wifi)
  - [ Has Bluetooth            ](#has-bluetooth)

* [ Location ](#location)
  - [ Country                  ](#country)
  - [ City                     ](#city)

* [ Drives ](#drives)
  - [ Drive Vendor             ](#drive-vendor)
  - [ Drive Model              ](#drive-model)
  - [ HDD Vendor               ](#hdd-vendor)
  - [ SSD Vendor               ](#ssd-vendor)
  - [ Drive Kind               ](#drive-kind)
  - [ Drive Connector          ](#drive-connector)
  - [ Drive Size               ](#drive-size)
  - [ Space Total              ](#space-total)
  - [ Space Used               ](#space-used)
  - [ Malfunc. Drives          ](#malfunc-drives)
  - [ Malfunc. Drive Vendor    ](#malfunc-drive-vendor)
  - [ Malfunc. HDD Vendor      ](#malfunc-hdd-vendor)
  - [ Malfunc. Drive Kind      ](#malfunc-drive-kind)
  - [ Failed Drives            ](#failed-drives)
  - [ Failed Drive Vendor      ](#failed-drive-vendor)
  - [ Drive Status             ](#drive-status)

* [ Storage controller ](#storage-controller)
  - [ Storage Vendor           ](#storage-vendor)
  - [ Storage Model            ](#storage-model)
  - [ Storage Kind             ](#storage-kind)

* [ Processor ](#processor)
  - [ CPU Vendor               ](#cpu-vendor)
  - [ CPU Model                ](#cpu-model)
  - [ CPU Model Family         ](#cpu-model-family)
  - [ CPU Cores                ](#cpu-cores)
  - [ CPU Sockets              ](#cpu-sockets)
  - [ CPU Threads              ](#cpu-threads)
  - [ CPU Op-Modes             ](#cpu-op-modes)
  - [ CPU Microcode            ](#cpu-microcode)
  - [ CPU Microarch            ](#cpu-microarch)

* [ Graphics ](#graphics)
  - [ GPU Vendor               ](#gpu-vendor)
  - [ GPU Model                ](#gpu-model)
  - [ GPU Combo                ](#gpu-combo)
  - [ GPU Driver               ](#gpu-driver)
  - [ GPU Memory               ](#gpu-memory)

* [ Monitor ](#monitor)
  - [ Monitor Vendor           ](#monitor-vendor)
  - [ Monitor Model            ](#monitor-model)
  - [ Monitor Resolution       ](#monitor-resolution)
  - [ Monitor Diagonal         ](#monitor-diagonal)
  - [ Monitor Width            ](#monitor-width)
  - [ Aspect Ratio             ](#aspect-ratio)
  - [ Monitor Area             ](#monitor-area)
  - [ Pixel Density            ](#pixel-density)
  - [ Multiple Monitors        ](#multiple-monitors)

* [ Network ](#network)
  - [ Net Controller Vendor    ](#net-controller-vendor)
  - [ Net Controller Model     ](#net-controller-model)
  - [ Wireless Vendor          ](#wireless-vendor)
  - [ Wireless Model           ](#wireless-model)
  - [ Ethernet Vendor          ](#ethernet-vendor)
  - [ Ethernet Model           ](#ethernet-model)
  - [ Net Controller Kind      ](#net-controller-kind)
  - [ Used Controller          ](#used-controller)
  - [ NICs                     ](#nics)
  - [ IPv6                     ](#ipv6)

* [ Bluetooth ](#bluetooth)
  - [ Bluetooth Vendor         ](#bluetooth-vendor)
  - [ Bluetooth Model          ](#bluetooth-model)

* [ Sound ](#sound)
  - [ Sound Vendor             ](#sound-vendor)
  - [ Sound Model              ](#sound-model)

* [ Memory ](#memory)
  - [ Memory Vendor            ](#memory-vendor)
  - [ Memory Model             ](#memory-model)
  - [ Memory Kind              ](#memory-kind)
  - [ Memory Form Factor       ](#memory-form-factor)
  - [ Memory Size              ](#memory-size)
  - [ Memory Speed             ](#memory-speed)

* [ Printers & scanners ](#printers--scanners)
  - [ Printer Vendor           ](#printer-vendor)
  - [ Printer Model            ](#printer-model)
  - [ Scanner Vendor           ](#scanner-vendor)
  - [ Scanner Model            ](#scanner-model)

* [ Camera ](#camera)
  - [ Camera Vendor            ](#camera-vendor)
  - [ Camera Model             ](#camera-model)

* [ Security ](#security)
  - [ Fingerprint Vendor       ](#fingerprint-vendor)
  - [ Fingerprint Model        ](#fingerprint-model)
  - [ Chipcard Vendor          ](#chipcard-vendor)
  - [ Chipcard Model           ](#chipcard-model)

* [ Unsupported ](#unsupported)
  - [ Unsupported Devices      ](#unsupported-devices)
  - [ Unsupported Device Types ](#unsupported-device-types)


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)

![OS](./images/line_chart/os_name.svg)

| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 22.04                 | 723       | 12.98%  |
| Fedora 39                    | 466       | 8.37%   |
| Debian 12                    | 355       | 6.38%   |
| Linux Mint 21.3              | 270       | 4.85%   |
| Fedora 40                    | 267       | 4.8%    |
| Arch Rolling                 | 236       | 4.24%   |
| ROSA 12.5                    | 227       | 4.08%   |
| Zorin 17                     | 206       | 3.7%    |
| Ubuntu 23.10                 | 184       | 3.3%    |
| Pop!_OS 22.04                | 159       | 2.86%   |
| OpenMandriva 23.08           | 147       | 2.64%   |
| ArcoLinux Rolling            | 137       | 2.46%   |
| Ubuntu 24.04                 | 119       | 2.14%   |
| KDE neon 22.04               | 91        | 1.63%   |
| OpenMandriva 5.0             | 88        | 1.58%   |
| Ubuntu 20.04                 | 82        | 1.47%   |
| BlackPanther 18.1            | 79        | 1.42%   |
| Manjaro                      | 76        | 1.36%   |
| openSUSE Tumbleweed-XXXXXXXX | 67        | 1.2%    |
| Kali 2024.1                  | 64        | 1.15%   |
| EndeavourOS Rolling          | 63        | 1.13%   |
| Kubuntu 22.04                | 59        | 1.06%   |
| Elementary 7.1               | 54        | 0.97%   |
| Nobara 39                    | 53        | 0.95%   |
| Linux Mint 21.2              | 50        | 0.9%    |
| Manjaro 23.1.4               | 49        | 0.88%   |
| Kubuntu 23.10                | 48        | 0.86%   |
| Debian 11                    | 46        | 0.83%   |
| SteamOS 3.5.17               | 42        | 0.75%   |
| Xubuntu 22.04                | 41        | 0.74%   |
| Debian                       | 38        | 0.68%   |
| openSUSE Leap-15.5           | 35        | 0.63%   |
| LMDE 6                       | 34        | 0.61%   |
| Zorin 16                     | 31        | 0.56%   |
| Gentoo 2.14                  | 31        | 0.56%   |
| MX 23                        | 26        | 0.47%   |
| Linux Mint 20.3              | 23        | 0.41%   |
| NixOS 24.05                  | 20        | 0.36%   |
| Lubuntu 22.04                | 20        | 0.36%   |
| Garuda Linux Soaring         | 20        | 0.36%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| Ubuntu           | 1133      | 20.35%  |
| Fedora           | 765       | 13.74%  |
| Debian           | 443       | 7.96%   |
| Linux Mint       | 375       | 6.73%   |
| OpenMandriva     | 320       | 5.75%   |
| ROSA             | 288       | 5.17%   |
| Zorin            | 239       | 4.29%   |
| Arch             | 236       | 4.24%   |
| Pop!_OS          | 162       | 2.91%   |
| ArcoLinux        | 142       | 2.55%   |
| Kubuntu          | 132       | 2.37%   |
| Manjaro          | 129       | 2.32%   |
| openSUSE         | 111       | 1.99%   |
| KDE neon         | 91        | 1.63%   |
| BlackPanther     | 84        | 1.51%   |
| Kali             | 69        | 1.24%   |
| Xubuntu          | 66        | 1.19%   |
| EndeavourOS      | 63        | 1.13%   |
| SteamOS          | 61        | 1.1%    |
| Elementary       | 58        | 1.04%   |
| Nobara           | 57        | 1.02%   |
| Gentoo           | 43        | 0.77%   |
| NixOS            | 37        | 0.66%   |
| LMDE             | 36        | 0.65%   |
| Ubuntu MATE      | 35        | 0.63%   |
| MX               | 34        | 0.61%   |
| Lubuntu          | 31        | 0.56%   |
| Garuda Linux     | 30        | 0.54%   |
| ALT Linux        | 20        | 0.36%   |
| Parrot           | 13        | 0.23%   |
| TUXEDO OS        | 12        | 0.22%   |
| Dts-distro       | 12        | 0.22%   |
| Cyber Infra      | 12        | 0.22%   |
| Void Linux       | 9         | 0.16%   |
| Red OS           | 9         | 0.16%   |
| BigLinux         | 9         | 0.16%   |
| Alpine           | 9         | 0.16%   |
| Raspbian         | 8         | 0.14%   |
| org.kde.Platform | 8         | 0.14%   |
| Arch ARM         | 8         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 6.5.0-27-generic                    | 423       | 7.6%    |
| 6.5.0-26-generic                    | 401       | 7.2%    |
| 6.5.0-28-generic                    | 371       | 6.66%   |
| 6.8.7-300.fc40.x86_64               | 178       | 3.2%    |
| 6.6.21-generic-8rosa2021.1-x86_64   | 145       | 2.6%    |
| 6.8.0-76060800daily20240311-generic | 141       | 2.53%   |
| 6.1.0-18-amd64                      | 136       | 2.44%   |
| 6.4.11-desktop-1omv2390             | 131       | 2.35%   |
| 5.15.0-101-generic                  | 124       | 2.23%   |
| 5.15.0-102-generic                  | 122       | 2.19%   |
| 6.1.0-20-amd64                      | 119       | 2.14%   |
| 6.6.2-desktop-1omv2390              | 108       | 1.94%   |
| 5.15.0-105-generic                  | 106       | 1.9%    |
| 6.8.0-31-generic                    | 104       | 1.87%   |
| 6.8.4-200.fc39.x86_64               | 91        | 1.63%   |
| 6.8.7-arch1-1                       | 87        | 1.56%   |
| 6.8.6-200.fc39.x86_64               | 80        | 1.44%   |
| 6.7.11-200.fc39.x86_64              | 74        | 1.33%   |
| 5.15.0-97-generic                   | 69        | 1.24%   |
| 6.8.2-arch2-1                       | 61        | 1.1%    |
| 6.8.5-201.fc39.x86_64               | 60        | 1.08%   |
| 6.5.6-300.fc39.x86_64               | 49        | 0.88%   |
| 6.1.52-valve16-1-neptune-61         | 49        | 0.88%   |
| 6.1.81-generic-2rosa2021.1-x86_64   | 45        | 0.81%   |
| 6.6.15-amd64                        | 42        | 0.75%   |
| 6.8.5-arch1-1                       | 41        | 0.74%   |
| 5.15.85-desktop-1bP                 | 41        | 0.74%   |
| 6.6.9-amd64                         | 38        | 0.68%   |
| 6.8.4-arch1-1                       | 37        | 0.66%   |
| 6.7.10-200.fc39.x86_64              | 37        | 0.66%   |
| 5.15.0-91-generic                   | 36        | 0.65%   |
| 6.8.7-200.fc39.x86_64               | 35        | 0.63%   |
| 6.6.26-1-MANJARO                    | 33        | 0.59%   |
| 5.14.21-150500.55.52-default        | 32        | 0.57%   |
| 6.1.0-4-amd64                       | 30        | 0.54%   |
| 6.8.5-301.fc40.x86_64               | 29        | 0.52%   |
| 6.5.0-18-generic                    | 29        | 0.52%   |
| 6.8.2-zen2-1-zen                    | 27        | 0.48%   |
| 6.8.7-arch1-2                       | 23        | 0.41%   |
| 6.6.25-1-MANJARO                    | 23        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.5.0   | 1356      | 24.35%  |
| 5.15.0  | 539       | 9.68%   |
| 6.8.7   | 429       | 7.7%    |
| 6.1.0   | 354       | 6.36%   |
| 6.8.0   | 295       | 5.3%    |
| 6.8.4   | 223       | 4.01%   |
| 6.8.5   | 202       | 3.63%   |
| 6.6.21  | 165       | 2.96%   |
| 6.8.2   | 136       | 2.44%   |
| 6.4.11  | 131       | 2.35%   |
| 6.8.6   | 128       | 2.3%    |
| 6.6.2   | 108       | 1.94%   |
| 6.7.11  | 81        | 1.45%   |
| 6.1.52  | 57        | 1.02%   |
| 6.5.6   | 50        | 0.9%    |
| 5.4.0   | 50        | 0.9%    |
| 6.8.1   | 48        | 0.86%   |
| 6.7.9   | 46        | 0.83%   |
| 6.2.0   | 46        | 0.83%   |
| 6.1.81  | 46        | 0.83%   |
| 6.6.26  | 43        | 0.77%   |
| 6.6.15  | 43        | 0.77%   |
| 6.7.10  | 41        | 0.74%   |
| 6.6.9   | 41        | 0.74%   |
| 6.6.25  | 41        | 0.74%   |
| 5.15.85 | 41        | 0.74%   |
| 5.14.21 | 37        | 0.66%   |
| 5.10.0  | 36        | 0.65%   |
| 6.6.28  | 25        | 0.45%   |
| 6.5.13  | 25        | 0.45%   |
| 6.7.12  | 23        | 0.41%   |
| 6.6.13  | 23        | 0.41%   |
| 6.6.10  | 22        | 0.4%    |
| 4.18.16 | 22        | 0.4%    |
| 6.9.0   | 21        | 0.38%   |
| 6.7.6   | 19        | 0.34%   |
| 6.6.27  | 19        | 0.34%   |
| 6.6.23  | 17        | 0.31%   |
| 6.4.8   | 17        | 0.31%   |
| 5.14.0  | 17        | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.8     | 1475      | 26.49%  |
| 6.5     | 1457      | 26.17%  |
| 6.6     | 622       | 11.17%  |
| 5.15    | 622       | 11.17%  |
| 6.1     | 553       | 9.93%   |
| 6.7     | 255       | 4.58%   |
| 6.4     | 156       | 2.8%    |
| 5.10    | 73        | 1.31%   |
| 6.2     | 60        | 1.08%   |
| 5.4     | 59        | 1.06%   |
| 5.14    | 54        | 0.97%   |
| 4.18    | 28        | 0.5%    |
| 6.9     | 21        | 0.38%   |
| 5.19    | 18        | 0.32%   |
| 4.15    | 18        | 0.32%   |
| 5.6     | 16        | 0.29%   |
| 6.3     | 14        | 0.25%   |
| 3.10    | 13        | 0.23%   |
| 5.16    | 11        | 0.2%    |
| 5.11    | 8         | 0.14%   |
| 6.0     | 6         | 0.11%   |
| 4.9     | 5         | 0.09%   |
| 4.19    | 5         | 0.09%   |
| 5.17    | 4         | 0.07%   |
| 5.8     | 3         | 0.05%   |
| 5.18    | 3         | 0.05%   |
| 5.13    | 3         | 0.05%   |
| 5.0     | 2         | 0.04%   |
| 5.9     | 1         | 0.02%   |
| 5.3     | 1         | 0.02%   |
| 4.4     | 1         | 0.02%   |
| 3.2     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 5466      | 98.17%  |
| aarch64 | 49        | 0.88%   |
| i686    | 42        | 0.75%   |
| armv7l  | 7         | 0.13%   |
| armv6l  | 3         | 0.05%   |
| mips    | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 2373      | 42.62%  |
| KDE5            | 1076      | 19.32%  |
| Unknown         | 396       | 7.11%   |
| X-Cinnamon      | 375       | 6.73%   |
| KDE6            | 375       | 6.73%   |
| XFCE            | 358       | 6.43%   |
| MATE            | 137       | 2.46%   |
| LXQt            | 104       | 1.87%   |
| Pantheon        | 59        | 1.06%   |
| Hyprland        | 49        | 0.88%   |
| Cinnamon        | 40        | 0.72%   |
| KDE             | 36        | 0.65%   |
| i3              | 27        | 0.48%   |
| KDE4            | 23        | 0.41%   |
| LXDE            | 17        | 0.31%   |
| GNOME Flashback | 14        | 0.25%   |
| sway            | 12        | 0.22%   |
| GNOME Classic   | 11        | 0.2%    |
| Budgie          | 10        | 0.18%   |
| Unity           | 7         | 0.13%   |
| openbox         | 7         | 0.13%   |
| icewm           | 6         | 0.11%   |
| Deepin          | 6         | 0.11%   |
| bspwm           | 6         | 0.11%   |
| fly             | 4         | 0.07%   |
| awesome         | 4         | 0.07%   |
| Trinity         | 3         | 0.05%   |
| qtile           | 3         | 0.05%   |
| Enlightenment   | 3         | 0.05%   |
| xmonad          | 2         | 0.04%   |
| Phosh:GNOME     | 2         | 0.04%   |
| LXDE-pi-wayfire | 2         | 0.04%   |
| GNOME-Classic   | 2         | 0.04%   |
| fluxbox         | 2         | 0.04%   |
| Endless:GNOME   | 2         | 0.04%   |
| dwm             | 2         | 0.04%   |
| chadwm          | 2         | 0.04%   |
| BunsenLabs      | 2         | 0.04%   |
| ubuntu          | 1         | 0.02%   |
| plasma          | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Wayland     | 2612      | 46.91%  |
| X11         | 2550      | 45.8%   |
| Unknown     | 220       | 3.95%   |
| Tty         | 185       | 3.32%   |
| Unspecified | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2143      | 38.49%  |
| SDDM    | 1186      | 21.3%   |
| GDM3    | 1082      | 19.43%  |
| LightDM | 742       | 13.33%  |
| GDM     | 366       | 6.57%   |
| KDM     | 11        | 0.2%    |
| LXDM    | 8         | 0.14%   |
| SLiM    | 7         | 0.13%   |
| SLIMSKI | 5         | 0.09%   |
| LY-DM   | 5         | 0.09%   |
| GREETD  | 5         | 0.09%   |
| XDM     | 2         | 0.04%   |
| Ly      | 2         | 0.04%   |
| FLY-DM  | 2         | 0.04%   |
| TDM     | 1         | 0.02%   |
| LEMURS  | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2304      | 41.38%  |
| ru_RU   | 495       | 8.89%   |
| de_DE   | 374       | 6.72%   |
| en_GB   | 255       | 4.58%   |
| it_IT   | 233       | 4.18%   |
| fr_FR   | 228       | 4.09%   |
| C       | 222       | 3.99%   |
| pt_BR   | 192       | 3.45%   |
| Unknown | 161       | 2.89%   |
| es_ES   | 121       | 2.17%   |
| pl_PL   | 106       | 1.9%    |
| en_CA   | 100       | 1.8%    |
| en_AU   | 77        | 1.38%   |
| en_IN   | 52        | 0.93%   |
| es_MX   | 42        | 0.75%   |
| tr_TR   | 40        | 0.72%   |
| nl_NL   | 40        | 0.72%   |
| hu_HU   | 35        | 0.63%   |
| es_AR   | 31        | 0.56%   |
| cs_CZ   | 31        | 0.56%   |
| zh_CN   | 30        | 0.54%   |
| de_AT   | 23        | 0.41%   |
| sv_SE   | 21        | 0.38%   |
| de_CH   | 19        | 0.34%   |
| pt_PT   | 17        | 0.31%   |
| es_CL   | 17        | 0.31%   |
| en_ZA   | 17        | 0.31%   |
| ja_JP   | 16        | 0.29%   |
| en_NZ   | 14        | 0.25%   |
| es_CO   | 13        | 0.23%   |
| en_IE   | 13        | 0.23%   |
| en_DK   | 13        | 0.23%   |
| fr_CA   | 12        | 0.22%   |
| nl_BE   | 10        | 0.18%   |
| fi_FI   | 10        | 0.18%   |
| el_GR   | 10        | 0.18%   |
| POSIX   | 9         | 0.16%   |
| en_IL   | 9         | 0.16%   |
| es_VE   | 8         | 0.14%   |
| da_DK   | 8         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2987      | 53.65%  |
| EFI  | 2581      | 46.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3145      | 56.48%  |
| Btrfs    | 1189      | 21.35%  |
| Tmpfs    | 734       | 13.18%  |
| Overlay  | 348       | 6.25%   |
| Xfs      | 76        | 1.36%   |
| Zfs      | 42        | 0.75%   |
| F2fs     | 17        | 0.31%   |
| Unknown  | 4         | 0.07%   |
| Ext3     | 3         | 0.05%   |
| Ext2     | 3         | 0.05%   |
| XXXXXXX  | 2         | 0.04%   |
| XXX      | 1         | 0.02%   |
| Rootfs   | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |
| Bcachefs | 1         | 0.02%   |
| Aufs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3148      | 56.54%  |
| Unknown | 1859      | 33.39%  |
| MBR     | 561       | 10.08%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4720      | 84.77%  |
| Yes       | 848       | 15.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4116      | 73.92%  |
| Yes       | 1452      | 26.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 889       | 15.97%  |
| Lenovo                               | 783       | 14.06%  |
| Hewlett-Packard                      | 738       | 13.25%  |
| Dell                                 | 589       | 10.58%  |
| Gigabyte Technology                  | 377       | 6.77%   |
| MSI                                  | 357       | 6.41%   |
| Acer                                 | 269       | 4.83%   |
| ASRock                               | 192       | 3.45%   |
| Apple                                | 192       | 3.45%   |
| Unknown                              | 87        | 1.56%   |
| Intel                                | 78        | 1.4%    |
| Supermicro                           | 64        | 1.15%   |
| Toshiba                              | 58        | 1.04%   |
| HUAWEI                               | 58        | 1.04%   |
| Valve                                | 56        | 1.01%   |
| Samsung Electronics                  | 48        | 0.86%   |
| Fujitsu                              | 39        | 0.7%    |
| Raspberry Pi Foundation              | 28        | 0.5%    |
| Google                               | 25        | 0.45%   |
| Microsoft                            | 24        | 0.43%   |
| AZW                                  | 24        | 0.43%   |
| Packard Bell                         | 23        | 0.41%   |
| Notebook                             | 23        | 0.41%   |
| Biostar                              | 23        | 0.41%   |
| Sony                                 | 21        | 0.38%   |
| Alienware                            | 20        | 0.36%   |
| Pegatron                             | 19        | 0.34%   |
| Medion                               | 19        | 0.34%   |
| ETegro Technologies                  | 16        | 0.29%   |
| Framework                            | 15        | 0.27%   |
| Shenzhen Meigao Electronic Equipment | 14        | 0.25%   |
| Positivo                             | 14        | 0.25%   |
| Chuwi                                | 14        | 0.25%   |
| TUXEDO                               | 12        | 0.22%   |
| Timi                                 | 11        | 0.2%    |
| AMI                                  | 10        | 0.18%   |
| System76                             | 9         | 0.16%   |
| ECS                                  | 8         | 0.14%   |
| Huanan                               | 7         | 0.13%   |
| Foxconn                              | 7         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 102       | 1.83%   |
| Valve Jupiter                      | 50        | 0.9%    |
| ASUS All Series                    | 33        | 0.59%   |
| Apple MacBookPro9,2                | 17        | 0.31%   |
| Supermicro X9DRW                   | 16        | 0.29%   |
| MSI MS-7C56                        | 16        | 0.29%   |
| ETegro Hyperion RS125 G4           | 16        | 0.29%   |
| HP Notebook                        | 15        | 0.27%   |
| ASUS PRIME A320M-K                 | 13        | 0.23%   |
| Supermicro SYS-1029P-WTR           | 12        | 0.22%   |
| Dell OptiPlex 7010                 | 12        | 0.22%   |
| MSI MS-7C95                        | 10        | 0.18%   |
| MSI MS-7C91                        | 10        | 0.18%   |
| Apple MacBookPro8,1                | 10        | 0.18%   |
| Apple MacBookAir7,2                | 10        | 0.18%   |
| MSI MS-7D25                        | 9         | 0.16%   |
| Lenovo ThinkCentre M79 10JAS05300  | 9         | 0.16%   |
| HUAWEI BOM-WXX9                    | 9         | 0.16%   |
| HP Pavilion Notebook               | 9         | 0.16%   |
| Dell Latitude 7490                 | 9         | 0.16%   |
| ASUS TUF Gaming B550-PLUS          | 9         | 0.16%   |
| ASUS M5A97 R2.0                    | 9         | 0.16%   |
| MSI MS-7E06                        | 8         | 0.14%   |
| MSI MS-7C37                        | 8         | 0.14%   |
| Intel X99                          | 8         | 0.14%   |
| HUAWEI HVY-WXX9                    | 8         | 0.14%   |
| HP ProLiant DL360 Gen9             | 8         | 0.14%   |
| HP 15                              | 8         | 0.14%   |
| Dell OptiPlex 7040                 | 8         | 0.14%   |
| AZW SER                            | 8         | 0.14%   |
| Apple MacBookPro12,1               | 8         | 0.14%   |
| Apple MacBookAir6,2                | 8         | 0.14%   |
| RPi Raspberry Pi 5 Model B Rev 1.0 | 7         | 0.13%   |
| MSI MS-7C02                        | 7         | 0.13%   |
| MSI MS-7B86                        | 7         | 0.13%   |
| ASUS TUF Gaming X570-PLUS          | 7         | 0.13%   |
| ASUS ROG STRIX B450-F GAMING       | 7         | 0.13%   |
| Apple MacBookPro14,1               | 7         | 0.13%   |
| Apple MacBookPro11,3               | 7         | 0.13%   |
| Apple MacBookPro11,1               | 7         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 346       | 6.21%   |
| Acer Aspire        | 174       | 3.13%   |
| Dell Latitude      | 171       | 3.07%   |
| ASUS ROG           | 139       | 2.5%    |
| ASUS PRIME         | 126       | 2.26%   |
| Lenovo IdeaPad     | 123       | 2.21%   |
| Dell Inspiron      | 120       | 2.16%   |
| HP Pavilion        | 109       | 1.96%   |
| HP EliteBook       | 105       | 1.89%   |
| Dell OptiPlex      | 104       | 1.87%   |
| Unknown            | 102       | 1.83%   |
| ASUS TUF           | 84        | 1.51%   |
| ASUS VivoBook      | 83        | 1.49%   |
| HP Laptop          | 78        | 1.4%    |
| HP ProBook         | 69        | 1.24%   |
| Dell Precision     | 61        | 1.1%    |
| Dell XPS           | 54        | 0.97%   |
| Valve Jupiter      | 50        | 0.9%    |
| Toshiba Satellite  | 50        | 0.9%    |
| Lenovo Legion      | 49        | 0.88%   |
| Lenovo Yoga        | 47        | 0.84%   |
| Lenovo ThinkCentre | 46        | 0.83%   |
| HP Compaq          | 40        | 0.72%   |
| ASUS All           | 33        | 0.59%   |
| ASUS ASUS          | 32        | 0.57%   |
| HP ZBook           | 31        | 0.56%   |
| HP ENVY            | 30        | 0.54%   |
| HP EliteDesk       | 30        | 0.54%   |
| RPi Raspberry      | 28        | 0.5%    |
| Lenovo ThinkBook   | 27        | 0.48%   |
| Acer Nitro         | 26        | 0.47%   |
| Microsoft Surface  | 24        | 0.43%   |
| Dell Vostro        | 24        | 0.43%   |
| Gigabyte X570      | 22        | 0.4%    |
| Apple MacBookPro11 | 22        | 0.4%    |
| HP ProLiant        | 21        | 0.38%   |
| HP ProDesk         | 21        | 0.38%   |
| Gigabyte B450M     | 21        | 0.38%   |
| Lenovo IdeaPadFlex | 20        | 0.36%   |
| HP Victus          | 20        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year    | Computers | Percent |
|---------|-----------|---------|
| 2023    | 554       | 9.95%   |
| 2020    | 513       | 9.21%   |
| 2021    | 511       | 9.18%   |
| 2022    | 494       | 8.87%   |
| 2018    | 418       | 7.51%   |
| 2019    | 368       | 6.61%   |
| 2012    | 366       | 6.57%   |
| 2013    | 356       | 6.39%   |
| 2017    | 306       | 5.5%    |
| 2011    | 261       | 4.69%   |
| 2016    | 254       | 4.56%   |
| 2014    | 252       | 4.53%   |
| 2015    | 223       | 4.01%   |
| 2010    | 180       | 3.23%   |
| 2009    | 154       | 2.77%   |
| 2008    | 117       | 2.1%    |
| 2024    | 88        | 1.58%   |
| 2007    | 61        | 1.1%    |
| Unknown | 57        | 1.02%   |
| 2006    | 25        | 0.45%   |
| 2005    | 5         | 0.09%   |
| 2004    | 2         | 0.04%   |
| 2003    | 1         | 0.02%   |
| 2002    | 1         | 0.02%   |
| 2000    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2902      | 52.12%  |
| Desktop        | 2099      | 37.7%   |
| Convertible    | 153       | 2.75%   |
| Server         | 118       | 2.12%   |
| Mini pc        | 94        | 1.69%   |
| All in one     | 78        | 1.4%    |
| Tablet         | 70        | 1.26%   |
| System on chip | 53        | 0.95%   |
| Other          | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 5264      | 94.54%  |
| Enabled  | 304       | 5.46%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5533      | 99.37%  |
| Yes  | 35        | 0.63%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1192      | 21.41%  |
| 16.01-24.0      | 1156      | 20.76%  |
| 8.01-16.0       | 961       | 17.26%  |
| 32.01-64.0      | 851       | 15.28%  |
| 3.01-4.0        | 692       | 12.43%  |
| 64.01-256.0     | 347       | 6.23%   |
| 24.01-32.0      | 171       | 3.07%   |
| 1.01-2.0        | 103       | 1.85%   |
| 2.01-3.0        | 39        | 0.7%    |
| More than 256.0 | 32        | 0.57%   |
| 0.51-1.0        | 16        | 0.29%   |
| 0.01-0.5        | 6         | 0.11%   |
| Unknown         | 2         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 1424      | 25.57%  |
| 2.01-3.0        | 1392      | 25%     |
| 4.01-8.0        | 1161      | 20.85%  |
| 3.01-4.0        | 833       | 14.96%  |
| 8.01-16.0       | 314       | 5.64%   |
| 0.51-1.0        | 252       | 4.53%   |
| 0.01-0.5        | 64        | 1.15%   |
| 16.01-24.0      | 56        | 1.01%   |
| 24.01-32.0      | 26        | 0.47%   |
| 64.01-256.0     | 21        | 0.38%   |
| 32.01-64.0      | 20        | 0.36%   |
| Unknown         | 3         | 0.05%   |
| More than 256.0 | 1         | 0.02%   |
| 0               | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3210      | 57.65%  |
| 2      | 1363      | 24.48%  |
| 3      | 485       | 8.71%   |
| 4      | 222       | 3.99%   |
| 5      | 98        | 1.76%   |
| 6      | 47        | 0.84%   |
| 0      | 36        | 0.65%   |
| 7      | 30        | 0.54%   |
| 10     | 19        | 0.34%   |
| 8      | 15        | 0.27%   |
| 9      | 13        | 0.23%   |
| 13     | 8         | 0.14%   |
| 11     | 7         | 0.13%   |
| 14     | 3         | 0.05%   |
| 12     | 3         | 0.05%   |
| 70     | 1         | 0.02%   |
| 41     | 1         | 0.02%   |
| 37     | 1         | 0.02%   |
| 35     | 1         | 0.02%   |
| 25     | 1         | 0.02%   |
| 24     | 1         | 0.02%   |
| 23     | 1         | 0.02%   |
| 21     | 1         | 0.02%   |
| 17     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4009      | 72%     |
| Yes       | 1559      | 28%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4659      | 83.67%  |
| No        | 909       | 16.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4283      | 76.92%  |
| No        | 1285      | 23.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3680      | 66.09%  |
| No        | 1888      | 33.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1016      | 18.25%  |
| Russia       | 646       | 11.6%   |
| Germany      | 504       | 9.05%   |
| Italy        | 282       | 5.06%   |
| Brazil       | 276       | 4.96%   |
| France       | 258       | 4.63%   |
| UK           | 204       | 3.66%   |
| Canada       | 182       | 3.27%   |
| Poland       | 164       | 2.95%   |
| Spain        | 152       | 2.73%   |
| Hungary      | 124       | 2.23%   |
| Netherlands  | 100       | 1.8%    |
| Australia    | 100       | 1.8%    |
| India        | 99        | 1.78%   |
| Mexico       | 76        | 1.36%   |
| Austria      | 69        | 1.24%   |
| Turkey       | 68        | 1.22%   |
| Sweden       | 67        | 1.2%    |
| Switzerland  | 62        | 1.11%   |
| Czechia      | 54        | 0.97%   |
| Argentina    | 53        | 0.95%   |
| Portugal     | 46        | 0.83%   |
| Norway       | 43        | 0.77%   |
| Finland      | 42        | 0.75%   |
| China        | 40        | 0.72%   |
| Belgium      | 37        | 0.66%   |
| Greece       | 36        | 0.65%   |
| Serbia       | 35        | 0.63%   |
| Romania      | 35        | 0.63%   |
| Japan        | 33        | 0.59%   |
| Chile        | 32        | 0.57%   |
| Bulgaria     | 30        | 0.54%   |
| South Africa | 29        | 0.52%   |
| Denmark      | 28        | 0.5%    |
| Colombia     | 28        | 0.5%    |
| New Zealand  | 22        | 0.4%    |
| Belarus      | 20        | 0.36%   |
| Vietnam      | 19        | 0.34%   |
| Slovakia     | 19        | 0.34%   |
| Israel       | 19        | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 230       | 4.13%   |
| St Petersburg     | 58        | 1.04%   |
| Budapest          | 47        | 0.84%   |
| Berlin            | 45        | 0.81%   |
| Sydney            | 43        | 0.77%   |
| Warsaw            | 41        | 0.74%   |
| Voronezh          | 36        | 0.65%   |
| Vienna            | 33        | 0.59%   |
| Sao Paulo         | 33        | 0.59%   |
| Milan             | 32        | 0.57%   |
| Istanbul          | 32        | 0.57%   |
| Los Angeles       | 30        | 0.54%   |
| Amsterdam         | 29        | 0.52%   |
| Rome              | 28        | 0.5%    |
| Paris             | 27        | 0.48%   |
| Rio de Janeiro    | 24        | 0.43%   |
| Montreal          | 23        | 0.41%   |
| Hamburg           | 23        | 0.41%   |
| Munich            | 22        | 0.4%    |
| Athens            | 22        | 0.4%    |
| Madrid            | 21        | 0.38%   |
| Belgrade          | 21        | 0.38%   |
| Toronto           | 20        | 0.36%   |
| Helsinki          | 20        | 0.36%   |
| Melbourne         | 19        | 0.34%   |
| Frankfurt am Main | 19        | 0.34%   |
| Sofia             | 18        | 0.32%   |
| Prague            | 18        | 0.32%   |
| New York          | 18        | 0.32%   |
| Stockholm         | 17        | 0.31%   |
| Yekaterinburg     | 16        | 0.29%   |
| Turin             | 16        | 0.29%   |
| Chicago           | 16        | 0.29%   |
| Bengaluru         | 16        | 0.29%   |
| Terrassa          | 15        | 0.27%   |
| Oslo              | 15        | 0.27%   |
| Novosibirsk       | 15        | 0.27%   |
| Minsk             | 15        | 0.27%   |
| Delhi             | 15        | 0.27%   |
| Poznan            | 14        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 1328      | 1754   | 15.84%  |
| WDC                          | 934       | 1197   | 11.14%  |
| Seagate                      | 856       | 1187   | 10.21%  |
| SanDisk                      | 571       | 624    | 6.81%   |
| Kingston                     | 451       | 518    | 5.38%   |
| Toshiba                      | 427       | 504    | 5.09%   |
| Unknown                      | 313       | 348    | 3.73%   |
| Crucial                      | 304       | 399    | 3.63%   |
| SK hynix                     | 242       | 243    | 2.89%   |
| Micron Technology            | 213       | 220    | 2.54%   |
| Intel                        | 206       | 234    | 2.46%   |
| Hitachi                      | 161       | 184    | 1.92%   |
| Phison Electronics           | 136       | 146    | 1.62%   |
| China                        | 113       | 120    | 1.35%   |
| A-DATA Technology            | 112       | 122    | 1.34%   |
| HGST                         | 108       | 224    | 1.29%   |
| Apple                        | 108       | 125    | 1.29%   |
| Kingston Technology Company  | 103       | 107    | 1.23%   |
| KIOXIA                       | 91        | 91     | 1.09%   |
| Micron/Crucial Technology    | 87        | 95     | 1.04%   |
| Unknown                      | 74        | 75     | 0.88%   |
| Silicon Motion               | 72        | 76     | 0.86%   |
| SPCC                         | 60        | 61     | 0.72%   |
| PNY                          | 52        | 60     | 0.62%   |
| MAXIO Technology (Hangzhou)  | 50        | 51     | 0.6%    |
| Intenso                      | 49        | 53     | 0.58%   |
| Fujitsu                      | 48        | 94     | 0.57%   |
| ADATA Technology             | 42        | 48     | 0.5%    |
| Patriot                      | 40        | 45     | 0.48%   |
| Realtek Semiconductor        | 35        | 36     | 0.42%   |
| Lexar                        | 35        | 38     | 0.42%   |
| Phison                       | 33        | 76     | 0.39%   |
| Team                         | 32        | 34     | 0.38%   |
| KingSpec                     | 32        | 35     | 0.38%   |
| Shenzhen Longsys Electronics | 31        | 33     | 0.37%   |
| Netac                        | 28        | 28     | 0.33%   |
| LITEON                       | 27        | 28     | 0.32%   |
| Hewlett-Packard              | 26        | 38     | 0.31%   |
| GOODRAM                      | 26        | 35     | 0.31%   |
| OCZ                          | 25        | 27     | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 199       | 2.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 124       | 1.35%   |
| Kingston SA400S37240G 240GB SSD                       | 96        | 1.05%   |
| Kingston SA400S37480G 480GB SSD                       | 76        | 0.83%   |
| Unknown                                               | 74        | 0.81%   |
| Seagate ST500DM002-1BD142 500GB                       | 53        | 0.58%   |
| Unknown MMC Card  64GB                                | 51        | 0.56%   |
| Crucial CT500MX500SSD1 500GB                          | 50        | 0.55%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                    | 48        | 0.52%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                   | 48        | 0.52%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 47        | 0.51%   |
| Seagate ST1000DM010-2EP102 1TB                        | 47        | 0.51%   |
| Samsung SSD 860 EVO 500GB                             | 46        | 0.5%    |
| Crucial CT1000MX500SSD1 1TB                           | 42        | 0.46%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 41        | 0.45%   |
| Samsung SSD 850 EVO 500GB                             | 41        | 0.45%   |
| Samsung SSD 850 EVO 250GB                             | 41        | 0.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB     | 41        | 0.45%   |
| Unknown MMC Card  128GB                               | 40        | 0.44%   |
| Phison E12 NVMe Controller 2TB                        | 40        | 0.44%   |
| Samsung SSD 980 1TB                                   | 39        | 0.43%   |
| Seagate ST2000DM008-2FR102 2TB                        | 37        | 0.4%    |
| Unknown MMC Card  32GB                                | 36        | 0.39%   |
| Kingston SA400S37120G 120GB SSD                       | 35        | 0.38%   |
| Unknown SD/MMC/MS PRO 128GB                           | 34        | 0.37%   |
| Seagate ST1000LM035-1RK172 1TB                        | 34        | 0.37%   |
| Toshiba MQ01ABD100 1TB                                | 33        | 0.36%   |
| Samsung SSD 860 EVO 1TB                               | 33        | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 32        | 0.35%   |
| Toshiba DT01ACA100 1TB                                | 31        | 0.34%   |
| Kingston Company SNV2S1000G 1TB                       | 31        | 0.34%   |
| Toshiba XG6 NVMe SSD Controller 1024GB                | 30        | 0.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 30        | 0.33%   |
| Samsung SSD 870 EVO 500GB                             | 30        | 0.33%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 256GB    | 30        | 0.33%   |
| HGST HTS721010A9E630 1TB                              | 30        | 0.33%   |
| Crucial CT480BX500SSD1 480GB                          | 30        | 0.33%   |
| Toshiba MQ01ABF050 500GB                              | 29        | 0.32%   |
| Samsung SSD 990 PRO 2TB                               | 29        | 0.32%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 29        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 834       | 1157   | 33.94%  |
| WDC                 | 755       | 965    | 30.73%  |
| Toshiba             | 330       | 402    | 13.43%  |
| Hitachi             | 160       | 183    | 6.51%   |
| HGST                | 107       | 222    | 4.35%   |
| Samsung Electronics | 78        | 82     | 3.17%   |
| Fujitsu             | 47        | 93     | 1.91%   |
| Unknown             | 35        | 35     | 1.42%   |
| Apple               | 30        | 30     | 1.22%   |
| Maxtor              | 15        | 16     | 0.61%   |
| JMicron Technology  | 15        | 15     | 0.61%   |
| Hewlett-Packard     | 9         | 17     | 0.37%   |
| SABRENT             | 7         | 7      | 0.28%   |
| ASMT                | 5         | 15     | 0.2%    |
| TO Exter            | 3         | 3      | 0.12%   |
| StoreJet            | 3         | 3      | 0.12%   |
| QUANTUM             | 2         | 2      | 0.08%   |
| Intenso             | 2         | 2      | 0.08%   |
| ExcelStor           | 2         | 2      | 0.08%   |
| ACASIS              | 2         | 2      | 0.08%   |
| WD MediaMax         | 1         | 1      | 0.04%   |
| USB3.0              | 1         | 1      | 0.04%   |
| STEC                | 1         | 1      | 0.04%   |
| SSK                 | 1         | 1      | 0.04%   |
| MSFT                | 1         | 1      | 0.04%   |
| Maxone              | 1         | 1      | 0.04%   |
| MARVELL             | 1         | 2      | 0.04%   |
| Lenovo              | 1         | 2      | 0.04%   |
| LaCie               | 1         | 1      | 0.04%   |
| Initio              | 1         | 1      | 0.04%   |
| ICY BOX             | 1         | 1      | 0.04%   |
| HPE                 | 1         | 1      | 0.04%   |
| HGST HTS            | 1         | 1      | 0.04%   |
| External            | 1         | 1      | 0.04%   |
| Config              | 1         | 1      | 0.04%   |
| Unknown             | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 543       | 672    | 19.91%  |
| Kingston            | 352       | 388    | 12.91%  |
| Crucial             | 266       | 307    | 9.75%   |
| SanDisk             | 201       | 213    | 7.37%   |
| WDC                 | 149       | 169    | 5.46%   |
| China               | 110       | 117    | 4.03%   |
| A-DATA Technology   | 92        | 98     | 3.37%   |
| Intel               | 81        | 94     | 2.97%   |
| Apple               | 58        | 58     | 2.13%   |
| SPCC                | 52        | 53     | 1.91%   |
| Micron Technology   | 52        | 58     | 1.91%   |
| Intenso             | 39        | 43     | 1.43%   |
| PNY                 | 38        | 43     | 1.39%   |
| Patriot             | 37        | 42     | 1.36%   |
| SK hynix            | 33        | 33     | 1.21%   |
| KingSpec            | 32        | 35     | 1.17%   |
| Toshiba             | 31        | 32     | 1.14%   |
| LITEON              | 26        | 27     | 0.95%   |
| OCZ                 | 25        | 27     | 0.92%   |
| Unknown             | 25        | 25     | 0.92%   |
| GOODRAM             | 24        | 26     | 0.88%   |
| Team                | 22        | 23     | 0.81%   |
| Netac               | 22        | 22     | 0.81%   |
| Transcend           | 21        | 22     | 0.77%   |
| Lexar               | 21        | 22     | 0.77%   |
| Apacer              | 19        | 19     | 0.7%    |
| Gigabyte Technology | 15        | 17     | 0.55%   |
| Hewlett-Packard     | 13        | 17     | 0.48%   |
| Fanxiang            | 12        | 12     | 0.44%   |
| AMD                 | 12        | 12     | 0.44%   |
| Corsair             | 11        | 12     | 0.4%    |
| Plextor             | 10        | 10     | 0.37%   |
| LITEONIT            | 9         | 9      | 0.33%   |
| Verbatim            | 8         | 11     | 0.29%   |
| Seagate             | 8         | 10     | 0.29%   |
| Emtec               | 7         | 7      | 0.26%   |
| Smartbuy            | 6         | 7      | 0.22%   |
| Qumo                | 6         | 6      | 0.22%   |
| KingDian            | 6         | 6      | 0.22%   |
| FORESEE             | 6         | 6      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2609      | 3385   | 35.11%  |
| SSD     | 2358      | 3044   | 31.74%  |
| HDD     | 2052      | 3271   | 27.62%  |
| MMC     | 280       | 309    | 3.77%   |
| Unknown | 131       | 151    | 1.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3533      | 5977   | 52.07%  |
| NVMe | 2604      | 3360   | 38.38%  |
| SAS  | 368       | 514    | 5.42%   |
| MMC  | 280       | 309    | 4.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2574      | 3404   | 55.58%  |
| 0.51-1.0   | 1287      | 1622   | 27.79%  |
| 1.01-2.0   | 401       | 546    | 8.66%   |
| 3.01-4.0   | 159       | 257    | 3.43%   |
| 4.01-10.0  | 96        | 279    | 2.07%   |
| 2.01-3.0   | 72        | 104    | 1.55%   |
| 10.01-20.0 | 40        | 99     | 0.86%   |
| 20.01-50.0 | 1         | 3      | 0.02%   |
| 0          | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1266      | 22.74%  |
| 251-500        | 1172      | 21.05%  |
| 501-1000       | 900       | 16.16%  |
| 1001-2000      | 551       | 9.9%    |
| More than 3000 | 439       | 7.88%   |
| 1-20           | 328       | 5.89%   |
| Unknown        | 304       | 5.46%   |
| 51-100         | 273       | 4.9%    |
| 2001-3000      | 188       | 3.38%   |
| 21-50          | 146       | 2.62%   |
| 0              | 1         | 0.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1714      | 30.78%  |
| 21-50          | 1022      | 18.35%  |
| 101-250        | 756       | 13.58%  |
| 51-100         | 590       | 10.6%   |
| 251-500        | 436       | 7.83%   |
| 501-1000       | 325       | 5.84%   |
| Unknown        | 304       | 5.46%   |
| 1001-2000      | 187       | 3.36%   |
| More than 3000 | 150       | 2.69%   |
| 2001-3000      | 78        | 1.4%    |
| 0              | 6         | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                | 11        | 11     | 2.03%   |
| Seagate ST500DM002-1BD142 500GB       | 11        | 11     | 2.03%   |
| Toshiba MQ01ABF050 500GB              | 7         | 7      | 1.29%   |
| Toshiba MQ01ABD050 500GB              | 4         | 4      | 0.74%   |
| Seagate ST9250315AS 250GB             | 4         | 9      | 0.74%   |
| Seagate ST500LT012-1DG142 500GB       | 4         | 4      | 0.74%   |
| Seagate ST3500418AS 500GB             | 4         | 4      | 0.74%   |
| SanDisk SSD PLUS 480GB                | 4         | 4      | 0.74%   |
| Samsung Electronics SSD 980 1TB       | 4         | 4      | 0.74%   |
| Samsung Electronics SSD 870 EVO 1TB   | 4         | 4      | 0.74%   |
| HGST HTS725050A7E630 500GB            | 4         | 4      | 0.74%   |
| HGST HTS541010A9E680 1TB              | 4         | 4      | 0.74%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 3         | 3      | 0.55%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 3         | 3      | 0.55%   |
| WDC WD5000AAKX-22ERMA0 500GB          | 3         | 3      | 0.55%   |
| WDC WD30EFRX-68EUZN0 3TB              | 3         | 3      | 0.55%   |
| WDC WD10SPZX-60Z10T0 1TB              | 3         | 3      | 0.55%   |
| WDC WD10EARS-00Y5B1 1TB               | 3         | 3      | 0.55%   |
| Toshiba MK2565GSX 250GB               | 3         | 3      | 0.55%   |
| Toshiba DT01ACA100 1TB                | 3         | 4      | 0.55%   |
| Seagate ST9500325AS 500GB             | 3         | 3      | 0.55%   |
| Seagate ST31000524AS 1TB              | 3         | 3      | 0.55%   |
| Seagate ST2000DM008-2FR102 2TB        | 3         | 3      | 0.55%   |
| Seagate ST2000DM001-1CH164 2TB        | 3         | 3      | 0.55%   |
| Seagate ST1000LM035-1RK172 1TB        | 3         | 3      | 0.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 3      | 0.55%   |
| Seagate ST1000DM003-1CH162 1TB        | 3         | 3      | 0.55%   |
| Samsung Electronics SSD 840 EVO 250GB | 3         | 3      | 0.55%   |
| Hitachi HTS545050A7E380 500GB         | 3         | 3      | 0.55%   |
| Hitachi HTS541612J9SA00 120GB         | 3         | 3      | 0.55%   |
| Hitachi HDP725050GLA360 500GB         | 3         | 3      | 0.55%   |
| HGST HTS545050A7E380 500GB            | 3         | 3      | 0.55%   |
| WDC WD6004FZWX-00BKVA0 6TB            | 2         | 2      | 0.37%   |
| WDC WD5000AAKX-75U6AA0 500GB          | 2         | 2      | 0.37%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 2         | 4      | 0.37%   |
| WDC WD5000AAKX-603CA0 500GB           | 2         | 2      | 0.37%   |
| WDC WD5000AAKS-00V1A0 500GB           | 2         | 2      | 0.37%   |
| WDC WD40EFRX-68N32N0 4TB              | 2         | 2      | 0.37%   |
| WDC WD1600BEVS-00VAT0 160GB           | 2         | 2      | 0.37%   |
| WDC WD10SPZX-24Z10 1TB                | 2         | 2      | 0.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 129       | 144    | 24.43%  |
| Seagate                        | 112       | 125    | 21.21%  |
| Toshiba                        | 59        | 61     | 11.17%  |
| Samsung Electronics            | 48        | 50     | 9.09%   |
| Hitachi                        | 43        | 44     | 8.14%   |
| Kingston                       | 15        | 15     | 2.84%   |
| Intel                          | 15        | 19     | 2.84%   |
| HGST                           | 14        | 14     | 2.65%   |
| SanDisk                        | 10        | 10     | 1.89%   |
| Crucial                        | 8         | 8      | 1.52%   |
| China                          | 7         | 7      | 1.33%   |
| SK hynix                       | 6         | 6      | 1.14%   |
| Maxtor                         | 5         | 5      | 0.95%   |
| A-DATA Technology              | 5         | 5      | 0.95%   |
| OCZ                            | 4         | 4      | 0.76%   |
| Micron Technology              | 4         | 4      | 0.76%   |
| Apple                          | 4         | 4      | 0.76%   |
| Neo                            | 3         | 3      | 0.57%   |
| Mushkin                        | 3         | 3      | 0.57%   |
| KingSpec                       | 3         | 3      | 0.57%   |
| Apacer                         | 3         | 3      | 0.57%   |
| Transcend                      | 2         | 2      | 0.38%   |
| SSSTC                          | 2         | 2      | 0.38%   |
| Plextor                        | 2         | 2      | 0.38%   |
| Fujitsu                        | 2         | 2      | 0.38%   |
| walram                         | 1         | 1      | 0.19%   |
| Timetec                        | 1         | 1      | 0.19%   |
| SPCC                           | 1         | 2      | 0.19%   |
| Solid State Storage Technology | 1         | 1      | 0.19%   |
| Smartbuy                       | 1         | 1      | 0.19%   |
| Silicon Motion                 | 1         | 1      | 0.19%   |
| Realtek Semiconductor          | 1         | 1      | 0.19%   |
| Qumo                           | 1         | 1      | 0.19%   |
| PNY                            | 1         | 1      | 0.19%   |
| Phison Electronics             | 1         | 1      | 0.19%   |
| LITEON                         | 1         | 1      | 0.19%   |
| LDLC                           | 1         | 1      | 0.19%   |
| KUU                            | 1         | 1      | 0.19%   |
| KINGCOMP                       | 1         | 1      | 0.19%   |
| Intenso                        | 1         | 2      | 0.19%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 118       | 133    | 31.89%  |
| Seagate             | 112       | 125    | 30.27%  |
| Toshiba             | 57        | 59     | 15.41%  |
| Hitachi             | 43        | 44     | 11.62%  |
| Samsung Electronics | 18        | 19     | 4.86%   |
| HGST                | 14        | 14     | 3.78%   |
| Maxtor              | 5         | 5      | 1.35%   |
| ICY BOX             | 1         | 1      | 0.27%   |
| Fujitsu             | 1         | 1      | 0.27%   |
| Apple               | 1         | 1      | 0.27%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 346       | 402    | 68.51%  |
| SSD  | 132       | 138    | 26.14%  |
| NVMe | 27        | 27     | 5.35%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)

![Failed Drives](./images/line_chart/drive_failed.svg)

| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| WDC WD3200AAJS-60Z0A0 320GB             | 1         | 3      | 12.5%   |
| WDC WD10JPVX-75JC3T0 1TB                | 1         | 1      | 12.5%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 1      | 12.5%   |
| Seagate ST500LT012-1DG142 500GB         | 1         | 1      | 12.5%   |
| Samsung Electronics SSD 980 500GB       | 1         | 1      | 12.5%   |
| Hitachi HDS721010DLE630 1TB             | 1         | 2      | 12.5%   |
| Hitachi HDS721010CLA332 1TB             | 1         | 1      | 12.5%   |
| ExcelStor Technology J8160S 160GB       | 1         | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)

![Failed Drive Vendor](./images/line_chart/drive_failed_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 4      | 25%     |
| Hitachi             | 2         | 3      | 25%     |
| SK hynix            | 1         | 1      | 12.5%   |
| Seagate             | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| ExcelStor           | 1         | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)

![Drive Status](./images/line_chart/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2947      | 4917   | 48.82%  |
| Works    | 2599      | 4665   | 43.06%  |
| Malfunc  | 482       | 567    | 7.99%   |
| Failed   | 8         | 11     | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 3276      | 42.86%  |
| AMD                                     | 1094      | 14.31%  |
| Samsung Electronics                     | 849       | 11.11%  |
| SanDisk                                 | 422       | 5.52%   |
| SK hynix                                | 207       | 2.71%   |
| Phison Electronics                      | 207       | 2.71%   |
| Kingston Technology Company             | 206       | 2.7%    |
| Micron Technology                       | 166       | 2.17%   |
| Micron/Crucial Technology               | 130       | 1.7%    |
| ASMedia Technology                      | 130       | 1.7%    |
| KIOXIA                                  | 90        | 1.18%   |
| Silicon Motion                          | 89        | 1.16%   |
| Toshiba America Info Systems            | 73        | 0.96%   |
| MAXIO Technology (Hangzhou)             | 73        | 0.96%   |
| Nvidia                                  | 63        | 0.82%   |
| ADATA Technology                        | 62        | 0.81%   |
| JMicron Technology                      | 52        | 0.68%   |
| Marvell Technology Group                | 51        | 0.67%   |
| Realtek Semiconductor                   | 46        | 0.6%    |
| Shenzhen Longsys Electronics            | 44        | 0.58%   |
| LSI Logic / Symbios Logic               | 39        | 0.51%   |
| Broadcom / LSI                          | 26        | 0.34%   |
| Solid State Storage Technology          | 25        | 0.33%   |
| Hewlett-Packard                         | 20        | 0.26%   |
| Apple                                   | 19        | 0.25%   |
| Union Memory (Shenzhen)                 | 18        | 0.24%   |
| Solidigm                                | 18        | 0.24%   |
| Yangtze Memory Technologies             | 15        | 0.2%    |
| INNOGRIT                                | 13        | 0.17%   |
| Adaptec                                 | 13        | 0.17%   |
| Lite-On Technology                      | 11        | 0.14%   |
| Seagate Technology                      | 9         | 0.12%   |
| O2 Micro                                | 9         | 0.12%   |
| VIA Technologies                        | 8         | 0.1%    |
| Hosin Global Electronics                | 8         | 0.1%    |
| Biwin Storage Technology                | 8         | 0.1%    |
| HighPoint Technologies                  | 7         | 0.09%   |
| Silicon Integrated Systems [SiS]        | 6         | 0.08%   |
| Silicon Image                           | 6         | 0.08%   |
| Shenzhen Unionmemory Information System | 5         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 612       | 7.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 280       | 3.27%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 218       | 2.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 212       | 2.48%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 196       | 2.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 195       | 2.28%   |
| Intel Volume Management Device NVMe RAID Controller                            | 194       | 2.27%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 163       | 1.91%   |
| AMD 500 Series Chipset SATA Controller                                         | 162       | 1.89%   |
| AMD 400 Series Chipset SATA Controller                                         | 143       | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 131       | 1.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 126       | 1.47%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 113       | 1.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 112       | 1.31%   |
| Intel SATA Controller [RAID mode]                                              | 108       | 1.26%   |
| AMD 600 Series Chipset SATA Controller                                         | 102       | 1.19%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 100       | 1.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 97        | 1.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 91        | 1.06%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 84        | 0.98%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 83        | 0.97%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 82        | 0.96%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 79        | 0.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 79        | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 77        | 0.9%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 74        | 0.87%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 74        | 0.87%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 74        | 0.87%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 73        | 0.85%   |
| Phison E12 NVMe Controller                                                     | 71        | 0.83%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 70        | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 70        | 0.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 69        | 0.81%   |
| Intel Tiger Lake-LP SATA Controller                                            | 67        | 0.78%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 66        | 0.77%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 66        | 0.77%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 65        | 0.76%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 63        | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 62        | 0.73%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 58        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3791      | 50.47%  |
| NVMe | 2606      | 34.69%  |
| RAID | 587       | 7.81%   |
| IDE  | 445       | 5.92%   |
| SAS  | 75        | 1%      |
| SCSI | 8         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3956      | 71.05%  |
| AMD          | 1550      | 27.84%  |
| ARM          | 55        | 0.99%   |
| Unknown      | 3         | 0.05%   |
| CentaurHauls | 2         | 0.04%   |
| Qualcomm     | 1         | 0.02%   |
| MIPS         | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 72        | 1.29%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 56        | 1.01%   |
| AMD Custom APU 0405                     | 50        | 0.9%    |
| ARM Processor                           | 44        | 0.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 41        | 0.74%   |
| AMD Ryzen 5 3600 6-Core Processor       | 39        | 0.7%    |
| AMD Ryzen 5 5500U with Radeon Graphics  | 38        | 0.68%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 35        | 0.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 34        | 0.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 34        | 0.61%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 34        | 0.61%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 32        | 0.57%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 32        | 0.57%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 31        | 0.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 31        | 0.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 30        | 0.54%   |
| Intel 12th Gen Core i7-12700H           | 30        | 0.54%   |
| AMD Ryzen 7 5700G with Radeon Graphics  | 30        | 0.54%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 28        | 0.5%    |
| AMD Ryzen 9 5950X 16-Core Processor     | 28        | 0.5%    |
| Intel N100                              | 27        | 0.48%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 27        | 0.48%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 27        | 0.48%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 27        | 0.48%   |
| Intel 12th Gen Core i5-1235U            | 26        | 0.47%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 25        | 0.45%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 25        | 0.45%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 24        | 0.43%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 24        | 0.43%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 23        | 0.41%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 23        | 0.41%   |
| Intel 13th Gen Core i7-13700H           | 23        | 0.41%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 22        | 0.4%    |
| Intel Core i7-3770 CPU @ 3.40GHz        | 22        | 0.4%    |
| Intel Core i5-2520M CPU @ 2.50GHz       | 22        | 0.4%    |
| Intel Core i5-10210U CPU @ 1.60GHz      | 22        | 0.4%    |
| Intel 12th Gen Core i7-1255U            | 22        | 0.4%    |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz     | 21        | 0.38%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 21        | 0.38%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 21        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1018      | 18.28%  |
| Other                   | 912       | 16.38%  |
| Intel Core i7           | 801       | 14.39%  |
| AMD Ryzen 5             | 409       | 7.35%   |
| AMD Ryzen 7             | 394       | 7.08%   |
| Intel Core i3           | 335       | 6.02%   |
| Intel Celeron           | 236       | 4.24%   |
| Intel Xeon              | 210       | 3.77%   |
| AMD Ryzen 9             | 167       | 3%      |
| Intel Core 2 Duo        | 137       | 2.46%   |
| Intel Pentium           | 105       | 1.89%   |
| Intel Atom              | 73        | 1.31%   |
| AMD Ryzen 3             | 54        | 0.97%   |
| AMD FX                  | 54        | 0.97%   |
| AMD A8                  | 48        | 0.86%   |
| Intel Pentium Dual-Core | 46        | 0.83%   |
| Intel Core i9           | 45        | 0.81%   |
| AMD A6                  | 40        | 0.72%   |
| AMD Ryzen 7 PRO         | 33        | 0.59%   |
| AMD A10                 | 32        | 0.57%   |
| Intel Core 2 Quad       | 25        | 0.45%   |
| AMD Ryzen Threadripper  | 25        | 0.45%   |
| AMD Ryzen 5 PRO         | 25        | 0.45%   |
| Intel Core              | 21        | 0.38%   |
| AMD Phenom II X4        | 20        | 0.36%   |
| AMD A4                  | 19        | 0.34%   |
| Intel Pentium Silver    | 17        | 0.31%   |
| Intel Xeon Silver       | 16        | 0.29%   |
| AMD Athlon II X2        | 16        | 0.29%   |
| Intel Pentium Gold      | 14        | 0.25%   |
| Intel Core 2            | 14        | 0.25%   |
| Intel Genuine           | 13        | 0.23%   |
| Intel Pentium Dual      | 12        | 0.22%   |
| AMD E1                  | 12        | 0.22%   |
| AMD Athlon 64 X2        | 12        | 0.22%   |
| AMD E2                  | 10        | 0.18%   |
| AMD E                   | 10        | 0.18%   |
| AMD Athlon              | 10        | 0.18%   |
| AMD PRO A8              | 9         | 0.16%   |
| ARM BCM                 | 8         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1746      | 31.36%  |
| 2       | 1648      | 29.6%   |
| 6       | 683       | 12.27%  |
| 8       | 612       | 10.99%  |
| 12      | 208       | 3.74%   |
| 16      | 148       | 2.66%   |
| 10      | 142       | 2.55%   |
| 14      | 113       | 2.03%   |
| 1       | 77        | 1.38%   |
| 24      | 49        | 0.88%   |
| 20      | 43        | 0.77%   |
| Unknown | 30        | 0.54%   |
| 3       | 21        | 0.38%   |
| 28      | 16        | 0.29%   |
| 64      | 14        | 0.25%   |
| 32      | 5         | 0.09%   |
| 18      | 5         | 0.09%   |
| 48      | 3         | 0.05%   |
| 40      | 2         | 0.04%   |
| 36      | 1         | 0.02%   |
| 22      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5414      | 97.23%  |
| 2       | 126       | 2.26%   |
| Unknown | 28        | 0.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4065      | 73.01%  |
| 1       | 1472      | 26.44%  |
| Unknown | 30        | 0.54%   |
| 8       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5503      | 98.83%  |
| 64-bit         | 22        | 0.4%    |
| 32-bit         | 22        | 0.4%    |
| Unknown        | 21        | 0.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4068      | 73.06%  |
| 0x206a7    | 78        | 1.4%    |
| 0x306a9    | 70        | 1.26%   |
| 0x1067a    | 52        | 0.93%   |
| 0x306c3    | 47        | 0.84%   |
| 0x806c1    | 36        | 0.65%   |
| 0x306e4    | 33        | 0.59%   |
| 0x0a50000d | 33        | 0.59%   |
| 0x906ea    | 31        | 0.56%   |
| 0x0a50000c | 28        | 0.5%    |
| 0x0a601206 | 26        | 0.47%   |
| 0x406e3    | 24        | 0.43%   |
| 0x40651    | 24        | 0.43%   |
| 0x806ea    | 23        | 0.41%   |
| 0x506e3    | 23        | 0.41%   |
| 0x06001119 | 23        | 0.41%   |
| 0x06003106 | 22        | 0.4%    |
| 0x806e9    | 21        | 0.38%   |
| 0x306d4    | 21        | 0.38%   |
| 0x010000c8 | 21        | 0.38%   |
| 0x406f1    | 20        | 0.36%   |
| 0x906e9    | 19        | 0.34%   |
| 0x0a404102 | 19        | 0.34%   |
| 0x08701021 | 19        | 0.34%   |
| 0x08608103 | 19        | 0.34%   |
| 0x08108109 | 18        | 0.32%   |
| 0x0800820d | 18        | 0.32%   |
| 0xb0671    | 17        | 0.31%   |
| 0x806ec    | 17        | 0.31%   |
| 0x08600106 | 17        | 0.31%   |
| 0x90672    | 15        | 0.27%   |
| 0x50657    | 15        | 0.27%   |
| 0x20655    | 15        | 0.27%   |
| 0x6fd      | 14        | 0.25%   |
| 0x406c4    | 14        | 0.25%   |
| 0x0a50000f | 14        | 0.25%   |
| 0x0a20120a | 14        | 0.25%   |
| 0x08701030 | 14        | 0.25%   |
| 0x06006705 | 14        | 0.25%   |
| 0x0830107a | 13        | 0.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 754       | 13.54%  |
| KabyLake          | 706       | 12.68%  |
| Haswell           | 414       | 7.44%   |
| IvyBridge         | 363       | 6.52%   |
| Zen 3             | 355       | 6.38%   |
| SandyBridge       | 299       | 5.37%   |
| Alderlake Hybrid  | 292       | 5.24%   |
| Skylake           | 283       | 5.08%   |
| Zen 2             | 228       | 4.09%   |
| TigerLake         | 204       | 3.66%   |
| Penryn            | 189       | 3.39%   |
| Broadwell         | 144       | 2.59%   |
| Silvermont        | 123       | 2.21%   |
| Zen+              | 119       | 2.14%   |
| Westmere          | 118       | 2.12%   |
| CometLake         | 116       | 2.08%   |
| Piledriver        | 87        | 1.56%   |
| IceLake           | 82        | 1.47%   |
| Goldmont plus     | 78        | 1.4%    |
| Core              | 76        | 1.36%   |
| Zen               | 73        | 1.31%   |
| K10               | 68        | 1.22%   |
| Excavator         | 49        | 0.88%   |
| Goldmont          | 41        | 0.74%   |
| Nehalem           | 40        | 0.72%   |
| Steamroller       | 39        | 0.7%    |
| Bonnell           | 29        | 0.52%   |
| Puma              | 28        | 0.5%    |
| Gracemont         | 24        | 0.43%   |
| Tremont           | 22        | 0.4%    |
| K8 Hammer         | 22        | 0.4%    |
| Jaguar            | 22        | 0.4%    |
| Bobcat            | 22        | 0.4%    |
| Meteorlake Hybrid | 14        | 0.25%   |
| K10 Llano         | 14        | 0.25%   |
| Bulldozer         | 10        | 0.18%   |
| P6                | 9         | 0.16%   |
| NetBurst          | 9         | 0.16%   |
| K8 & K10 hybrid   | 2         | 0.04%   |
| Sapphire Rapids   | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3014      | 46.4%   |
| Nvidia                           | 1709      | 26.31%  |
| AMD                              | 1633      | 25.14%  |
| Matrox Electronics Systems       | 67        | 1.03%   |
| ASPEED Technology                | 64        | 0.99%   |
| Silicon Integrated Systems [SiS] | 3         | 0.05%   |
| Huawei Technologies              | 3         | 0.05%   |
| Zhaoxin                          | 2         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 220       | 3.29%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 178       | 2.66%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 176       | 2.63%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 124       | 1.85%   |
| Intel UHD Graphics 620                                                                   | 121       | 1.81%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 115       | 1.72%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 102       | 1.53%   |
| Intel HD Graphics 620                                                                    | 97        | 1.45%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 97        | 1.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 94        | 1.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 85        | 1.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 84        | 1.26%   |
| AMD Raphael                                                                              | 82        | 1.23%   |
| AMD Lucienne                                                                             | 80        | 1.2%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 78        | 1.17%   |
| Intel HD Graphics 530                                                                    | 73        | 1.09%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 73        | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 68        | 1.02%   |
| AMD Rembrandt [Radeon 680M]                                                              | 68        | 1.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 67        | 1%      |
| AMD Phoenix1                                                                             | 67        | 1%      |
| Intel GeminiLake [UHD Graphics 600]                                                      | 65        | 0.97%   |
| Intel Core Processor Integrated Graphics Controller                                      | 65        | 0.97%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 65        | 0.97%   |
| Intel HD Graphics 630                                                                    | 64        | 0.96%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 64        | 0.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 63        | 0.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 59        | 0.88%   |
| Intel HD Graphics 5500                                                                   | 59        | 0.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 56        | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 55        | 0.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 54        | 0.81%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 50        | 0.75%   |
| AMD Barcelo                                                                              | 50        | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 46        | 0.69%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 45        | 0.67%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 45        | 0.67%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 45        | 0.67%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 44        | 0.66%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 44        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 2157      | 38.74%  |
| 1 x AMD                  | 1229      | 22.07%  |
| 1 x Nvidia               | 902       | 16.2%   |
| Intel + Nvidia           | 624       | 11.21%  |
| AMD + Nvidia             | 154       | 2.77%   |
| Intel + AMD              | 122       | 2.19%   |
| 2 x AMD                  | 117       | 2.1%    |
| Other                    | 66        | 1.19%   |
| 1 x Matrox               | 59        | 1.06%   |
| 1 x ASPEED               | 56        | 1.01%   |
| 2 x Intel                | 39        | 0.7%    |
| 2 x Nvidia               | 12        | 0.22%   |
| Nvidia + Matrox          | 7         | 0.13%   |
| Nvidia + ASPEED          | 5         | 0.09%   |
| 1 x SiS                  | 3         | 0.05%   |
| 1 x Huawei Technologies  | 3         | 0.05%   |
| AMD + ASPEED             | 3         | 0.05%   |
| 3 x AMD                  | 2         | 0.04%   |
| 1 x Zhaoxin              | 2         | 0.04%   |
| AMD + 2 x Nvidia         | 2         | 0.04%   |
| 2 x AMD + 1 x Nvidia     | 1         | 0.02%   |
| Intel + 2 x Nvidia       | 1         | 0.02%   |
| Intel + Matrox           | 1         | 0.02%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4288      | 77.01%  |
| Proprietary | 862       | 15.48%  |
| Unknown     | 418       | 7.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3893      | 69.92%  |
| 0.01-0.5   | 400       | 7.18%   |
| 1.01-2.0   | 329       | 5.91%   |
| 0.51-1.0   | 247       | 4.44%   |
| 7.01-8.0   | 214       | 3.84%   |
| 3.01-4.0   | 202       | 3.63%   |
| 8.01-16.0  | 148       | 2.66%   |
| 5.01-6.0   | 75        | 1.35%   |
| 16.01-24.0 | 39        | 0.7%    |
| 2.01-3.0   | 19        | 0.34%   |
| 4.01-5.0   | 2         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 705       | 11.96%  |
| AU Optronics            | 653       | 11.07%  |
| BOE                     | 603       | 10.23%  |
| Chimei Innolux          | 456       | 7.73%   |
| LG Display              | 404       | 6.85%   |
| Goldstar                | 345       | 5.85%   |
| Dell                    | 345       | 5.85%   |
| Acer                    | 201       | 3.41%   |
| Hewlett-Packard         | 193       | 3.27%   |
| Apple                   | 169       | 2.87%   |
| AOC                     | 145       | 2.46%   |
| Philips                 | 127       | 2.15%   |
| Lenovo                  | 107       | 1.81%   |
| BenQ                    | 104       | 1.76%   |
| Ancor Communications    | 88        | 1.49%   |
| Sharp                   | 81        | 1.37%   |
| ASUSTek Computer        | 79        | 1.34%   |
| Chi Mei Optoelectronics | 59        | 1%      |
| InfoVision              | 58        | 0.98%   |
| ViewSonic               | 55        | 0.93%   |
| Valve                   | 55        | 0.93%   |
| Iiyama                  | 45        | 0.76%   |
| PANDA                   | 41        | 0.7%    |
| CSO                     | 38        | 0.64%   |
| Unknown                 | 35        | 0.59%   |
| MSI                     | 28        | 0.47%   |
| Sony                    | 27        | 0.46%   |
| Mi                      | 23        | 0.39%   |
| NEC Computers           | 22        | 0.37%   |
| Toshiba                 | 20        | 0.34%   |
| TMX                     | 20        | 0.34%   |
| HKC                     | 20        | 0.34%   |
| LG Philips              | 18        | 0.31%   |
| Panasonic               | 17        | 0.29%   |
| HannStar                | 17        | 0.29%   |
| Gigabyte Technology     | 17        | 0.29%   |
| Unknown                 | 17        | 0.29%   |
| HUAWEI                  | 16        | 0.27%   |
| Fujitsu Siemens         | 16        | 0.27%   |
| Sceptre Tech            | 15        | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 46        | 0.76%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 30        | 0.5%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 24        | 0.4%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 23        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 22        | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 20        | 0.33%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 19        | 0.31%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 18        | 0.3%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 18        | 0.3%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 17        | 0.28%   |
| Unknown                                                                  | 17        | 0.28%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 16        | 0.26%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 15        | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 14        | 0.23%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 14        | 0.23%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 13        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 13        | 0.22%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                         | 13        | 0.22%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                      | 12        | 0.2%    |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                    | 12        | 0.2%    |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 11        | 0.18%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 11        | 0.18%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch             | 11        | 0.18%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 11        | 0.18%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 11        | 0.18%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 11        | 0.18%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 11        | 0.18%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 11        | 0.18%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 10        | 0.17%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 10        | 0.17%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 10        | 0.17%   |
| AOC 24B1W1G5 AOC2401 1920x1080 527x296mm 23.8-inch                       | 10        | 0.17%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                            | 9         | 0.15%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 9         | 0.15%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                    | 9         | 0.15%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 9         | 0.15%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 9         | 0.15%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 9         | 0.15%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch        | 8         | 0.13%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 8         | 0.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2509      | 44.37%  |
| 1366x768 (WXGA)    | 833       | 14.73%  |
| 3840x2160 (4K)     | 429       | 7.59%   |
| 2560x1440 (QHD)    | 324       | 5.73%   |
| 1920x1200 (WUXGA)  | 198       | 3.5%    |
| 1600x900 (HD+)     | 191       | 3.38%   |
| 1440x900 (WXGA+)   | 118       | 2.09%   |
| 2560x1600          | 115       | 2.03%   |
| 1280x1024 (SXGA)   | 113       | 2%      |
| 1280x800 (WXGA)    | 105       | 1.86%   |
| 3440x1440          | 102       | 1.8%    |
| 1680x1050 (WSXGA+) | 90        | 1.59%   |
| 2880x1800          | 76        | 1.34%   |
| 800x1280           | 54        | 0.95%   |
| 2560x1080          | 52        | 0.92%   |
| 2288x1287          | 32        | 0.57%   |
| 1360x768           | 31        | 0.55%   |
| 3840x2400          | 21        | 0.37%   |
| 3840x1080          | 19        | 0.34%   |
| 1920x1280          | 19        | 0.34%   |
| 2256x1504          | 18        | 0.32%   |
| 2160x1440          | 18        | 0.32%   |
| Unknown            | 18        | 0.32%   |
| 1024x768 (XGA)     | 17        | 0.3%    |
| 1920x540           | 16        | 0.28%   |
| 1024x600           | 15        | 0.27%   |
| 2736x1824          | 13        | 0.23%   |
| 1600x1200          | 12        | 0.21%   |
| 3200x2000          | 8         | 0.14%   |
| 3840x1600          | 5         | 0.09%   |
| 3456x2160          | 5         | 0.09%   |
| 3072x1920          | 5         | 0.09%   |
| 2520x1680          | 5         | 0.09%   |
| 2240x1400          | 5         | 0.09%   |
| 1280x960           | 5         | 0.09%   |
| 1280x720 (HD)      | 5         | 0.09%   |
| 3200x1800 (QHD+)   | 4         | 0.07%   |
| 3840x1100          | 3         | 0.05%   |
| 2880x1920          | 3         | 0.05%   |
| 2880x1620          | 3         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1375      | 23.37%  |
| 13      | 544       | 9.25%   |
| 27      | 506       | 8.6%    |
| 14      | 466       | 7.92%   |
| 24      | 454       | 7.72%   |
| 23      | 348       | 5.91%   |
| 21      | 309       | 5.25%   |
| 17      | 280       | 4.76%   |
| 31      | 171       | 2.91%   |
| 16      | 154       | 2.62%   |
| 19      | 149       | 2.53%   |
| 34      | 133       | 2.26%   |
| Unknown | 119       | 2.02%   |
| 18      | 102       | 1.73%   |
| 12      | 89        | 1.51%   |
| 20      | 71        | 1.21%   |
| 11      | 64        | 1.09%   |
| 22      | 63        | 1.07%   |
| 7       | 56        | 0.95%   |
| 84      | 50        | 0.85%   |
| 32      | 35        | 0.59%   |
| 72      | 34        | 0.58%   |
| 40      | 34        | 0.58%   |
| 54      | 31        | 0.53%   |
| 142     | 30        | 0.51%   |
| 26      | 23        | 0.39%   |
| 10      | 22        | 0.37%   |
| 28      | 21        | 0.36%   |
| 48      | 19        | 0.32%   |
| 52      | 14        | 0.24%   |
| 49      | 13        | 0.22%   |
| 25      | 12        | 0.2%    |
| 29      | 9         | 0.15%   |
| 37      | 8         | 0.14%   |
| 39      | 7         | 0.12%   |
| 38      | 7         | 0.12%   |
| 47      | 6         | 0.1%    |
| 46      | 6         | 0.1%    |
| 42      | 6         | 0.1%    |
| 36      | 6         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2218      | 38.38%  |
| 501-600        | 1207      | 20.89%  |
| 401-500        | 612       | 10.59%  |
| 201-300        | 479       | 8.29%   |
| 351-400        | 359       | 6.21%   |
| 601-700        | 254       | 4.4%    |
| 701-800        | 175       | 3.03%   |
| Unknown        | 119       | 2.06%   |
| 1001-1500      | 103       | 1.78%   |
| 1501-2000      | 90        | 1.56%   |
| 801-900        | 62        | 1.07%   |
| 1-100          | 54        | 0.93%   |
| More than 2000 | 30        | 0.52%   |
| 901-1000       | 14        | 0.24%   |
| 101-200        | 3         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3998      | 74.2%   |
| 16/10   | 784       | 14.55%  |
| 21/9    | 156       | 2.9%    |
| 5/4     | 117       | 2.17%   |
| 3/2     | 89        | 1.65%   |
| Unknown | 72        | 1.34%   |
| 0.67    | 48        | 0.89%   |
| 4/3     | 42        | 0.78%   |
| 1.00    | 30        | 0.56%   |
| 32/9    | 26        | 0.48%   |
| 0.62    | 8         | 0.15%   |
| 6/5     | 3         | 0.06%   |
| 3.40    | 3         | 0.06%   |
| 0.89    | 3         | 0.06%   |
| 3.20    | 2         | 0.04%   |
| 3.73    | 1         | 0.02%   |
| 3.33    | 1         | 0.02%   |
| 2.50    | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |
| 0.45    | 1         | 0.02%   |
| 0.25    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1385      | 23.76%  |
| 201-250        | 899       | 15.42%  |
| 81-90          | 785       | 13.46%  |
| 301-350        | 526       | 9.02%   |
| 351-500        | 366       | 6.28%   |
| 151-200        | 319       | 5.47%   |
| 71-80          | 216       | 3.7%    |
| 121-130        | 208       | 3.57%   |
| More than 1000 | 187       | 3.21%   |
| 251-300        | 174       | 2.98%   |
| 111-120        | 141       | 2.42%   |
| 141-150        | 130       | 2.23%   |
| Unknown        | 119       | 2.04%   |
| 501-1000       | 108       | 1.85%   |
| 61-70          | 69        | 1.18%   |
| 51-60          | 68        | 1.17%   |
| 1-40           | 57        | 0.98%   |
| 131-140        | 26        | 0.45%   |
| 91-100         | 26        | 0.45%   |
| 41-50          | 21        | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1827      | 32.07%  |
| 121-160       | 1570      | 27.56%  |
| 101-120       | 1346      | 23.63%  |
| 161-240       | 551       | 9.67%   |
| More than 240 | 145       | 2.55%   |
| 1-50          | 139       | 2.44%   |
| Unknown       | 119       | 2.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4289      | 77.03%  |
| 2     | 791       | 14.21%  |
| 0     | 370       | 6.65%   |
| 3     | 102       | 1.83%   |
| 4     | 16        | 0.29%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 3084      | 37.32%  |
| Intel                            | 2698      | 32.65%  |
| Qualcomm Atheros                 | 657       | 7.95%   |
| Broadcom                         | 456       | 5.52%   |
| MediaTek                         | 323       | 3.91%   |
| Broadcom Limited                 | 112       | 1.36%   |
| TP-Link                          | 111       | 1.34%   |
| ASIX Electronics                 | 65        | 0.79%   |
| Ralink Technology                | 64        | 0.77%   |
| Ralink                           | 59        | 0.71%   |
| Nvidia                           | 50        | 0.61%   |
| Marvell Technology Group         | 50        | 0.61%   |
| Samsung Electronics              | 43        | 0.52%   |
| Aquantia                         | 42        | 0.51%   |
| Qualcomm                         | 38        | 0.46%   |
| Microsoft                        | 22        | 0.27%   |
| Qualcomm Atheros Communications  | 21        | 0.25%   |
| Sierra Wireless                  | 19        | 0.23%   |
| DisplayLink                      | 17        | 0.21%   |
| D-Link                           | 17        | 0.21%   |
| ASUSTek Computer                 | 17        | 0.21%   |
| NetGear                          | 16        | 0.19%   |
| Hewlett-Packard                  | 16        | 0.19%   |
| Xiaomi                           | 14        | 0.17%   |
| Lenovo                           | 13        | 0.16%   |
| Huawei Technologies              | 12        | 0.15%   |
| Raspberry Pi                     | 10        | 0.12%   |
| Mellanox Technologies            | 10        | 0.12%   |
| JMicron Technology               | 10        | 0.12%   |
| Google                           | 10        | 0.12%   |
| FIBOCOM                          | 9         | 0.11%   |
| QinHeng Electronics              | 8         | 0.1%    |
| Microchip Technology             | 8         | 0.1%    |
| Linksys                          | 8         | 0.1%    |
| Dell                             | 8         | 0.1%    |
| AVM                              | 8         | 0.1%    |
| OPPO Electronics                 | 7         | 0.08%   |
| Motorola PCS                     | 7         | 0.08%   |
| Edimax Technology                | 7         | 0.08%   |
| Silicon Integrated Systems [SiS] | 6         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1955      | 20.02%  |
| Realtek RTL8125 2.5GbE Controller                                      | 276       | 2.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 244       | 2.5%    |
| Intel Wi-Fi 6 AX200                                                    | 226       | 2.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 177       | 1.81%   |
| Intel Wireless 8265 / 8275                                             | 159       | 1.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 152       | 1.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 149       | 1.53%   |
| Intel Wi-Fi 6 AX201                                                    | 149       | 1.53%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 144       | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 143       | 1.46%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 126       | 1.29%   |
| Intel Ethernet Controller I225-V                                       | 126       | 1.29%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 115       | 1.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 105       | 1.08%   |
| Intel I211 Gigabit Network Connection                                  | 104       | 1.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 97        | 0.99%   |
| Intel Wireless 7265                                                    | 97        | 0.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 90        | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 88        | 0.9%    |
| Intel Raptor Lake PCH CNVi WiFi                                        | 84        | 0.86%   |
| Intel Wireless 8260                                                    | 83        | 0.85%   |
| Intel Ethernet Connection I217-LM                                      | 78        | 0.8%    |
| Intel Wireless 7260                                                    | 77        | 0.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 71        | 0.73%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 70        | 0.72%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 69        | 0.71%   |
| Intel Wireless 3165                                                    | 66        | 0.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 63        | 0.65%   |
| Intel Ethernet Connection (2) I219-V                                   | 63        | 0.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 59        | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                                  | 59        | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 59        | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                          | 58        | 0.59%   |
| Intel Ethernet Connection (2) I219-LM                                  | 53        | 0.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 53        | 0.54%   |
| Intel I350 Gigabit Network Connection                                  | 50        | 0.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 50        | 0.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 48        | 0.49%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 47        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2016      | 44.83%  |
| Realtek Semiconductor                 | 834       | 18.55%  |
| Qualcomm Atheros                      | 510       | 11.34%  |
| MediaTek                              | 313       | 6.96%   |
| Broadcom                              | 289       | 6.43%   |
| TP-Link                               | 99        | 2.2%    |
| Broadcom Limited                      | 86        | 1.91%   |
| Ralink Technology                     | 64        | 1.42%   |
| Ralink                                | 59        | 1.31%   |
| Qualcomm                              | 35        | 0.78%   |
| Qualcomm Atheros Communications       | 21        | 0.47%   |
| Sierra Wireless                       | 19        | 0.42%   |
| Microsoft                             | 19        | 0.42%   |
| ASUSTek Computer                      | 16        | 0.36%   |
| NetGear                               | 15        | 0.33%   |
| D-Link                                | 15        | 0.33%   |
| Marvell Technology Group              | 12        | 0.27%   |
| FIBOCOM                               | 9         | 0.2%    |
| Linksys                               | 8         | 0.18%   |
| AVM                                   | 8         | 0.18%   |
| Edimax Technology                     | 7         | 0.16%   |
| Dell                                  | 6         | 0.13%   |
| Qualcomm Technologies                 | 5         | 0.11%   |
| Mercucys                              | 5         | 0.11%   |
| D-Link System                         | 5         | 0.11%   |
| ZTopInc                               | 3         | 0.07%   |
| Hewlett-Packard                       | 3         | 0.07%   |
| ZyXEL Communications                  | 2         | 0.04%   |
| IMC Networks                          | 2         | 0.04%   |
| Unknown                               | 2         | 0.04%   |
| ZyDAS                                 | 1         | 0.02%   |
| Z-Com                                 | 1         | 0.02%   |
| Wilocity                              | 1         | 0.02%   |
| TRENDnet                              | 1         | 0.02%   |
| Tenda                                 | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Cisco Aironet Wireless Communications | 1         | 0.02%   |
| BUFFALO                               | 1         | 0.02%   |
| Belkin Components                     | 1         | 0.02%   |
| AboCom Systems                        | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 226       | 5%      |
| Intel Wireless 8265 / 8275                                           | 159       | 3.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 149       | 3.3%    |
| Intel Wi-Fi 6 AX201                                                  | 149       | 3.3%    |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 144       | 3.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 143       | 3.16%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 126       | 2.79%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 115       | 2.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 105       | 2.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 97        | 2.15%   |
| Intel Wireless 7265                                                  | 97        | 2.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 90        | 1.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 88        | 1.95%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 84        | 1.86%   |
| Intel Wireless 8260                                                  | 83        | 1.84%   |
| Intel Wireless 7260                                                  | 77        | 1.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 71        | 1.57%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 70        | 1.55%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                    | 69        | 1.53%   |
| Intel Wireless 3165                                                  | 66        | 1.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 63        | 1.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 59        | 1.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 59        | 1.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 53        | 1.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 50        | 1.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 48        | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 47        | 1.04%   |
| Broadcom BCM43142 802.11b/g/n                                        | 45        | 1%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 43        | 0.95%   |
| Realtek 802.11ac NIC                                                 | 43        | 0.95%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                    | 40        | 0.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 40        | 0.88%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 38        | 0.84%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 37        | 0.82%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 36        | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 36        | 0.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                       | 35        | 0.77%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 34        | 0.75%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 33        | 0.73%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 33        | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2713      | 54.23%  |
| Intel                                  | 1394      | 27.86%  |
| Broadcom                               | 242       | 4.84%   |
| Qualcomm Atheros                       | 197       | 3.94%   |
| ASIX Electronics                       | 65        | 1.3%    |
| Nvidia                                 | 50        | 1%      |
| Samsung Electronics                    | 43        | 0.86%   |
| Aquantia                               | 42        | 0.84%   |
| Marvell Technology Group               | 38        | 0.76%   |
| Broadcom Limited                       | 27        | 0.54%   |
| DisplayLink                            | 17        | 0.34%   |
| Xiaomi                                 | 14        | 0.28%   |
| TP-Link                                | 12        | 0.24%   |
| Lenovo                                 | 12        | 0.24%   |
| Raspberry Pi                           | 10        | 0.2%    |
| JMicron Technology                     | 10        | 0.2%    |
| Google                                 | 10        | 0.2%    |
| Mellanox Technologies                  | 9         | 0.18%   |
| MediaTek                               | 9         | 0.18%   |
| Microchip Technology                   | 8         | 0.16%   |
| Hewlett-Packard                        | 8         | 0.16%   |
| OPPO Electronics                       | 7         | 0.14%   |
| Huawei Technologies                    | 7         | 0.14%   |
| Silicon Integrated Systems [SiS]       | 6         | 0.12%   |
| Motorola PCS                           | 5         | 0.1%    |
| American Megatrends                    | 4         | 0.08%   |
| VIA Technologies                       | 3         | 0.06%   |
| Qualcomm                               | 3         | 0.06%   |
| Insyde Software                        | 3         | 0.06%   |
| Apple                                  | 3         | 0.06%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.04%   |
| Suzhou Motorcomm Electronic Technology | 2         | 0.04%   |
| Solarflare Communications              | 2         | 0.04%   |
| Microsoft                              | 2         | 0.04%   |
| D-Link                                 | 2         | 0.04%   |
| 3Com                                   | 2         | 0.04%   |
| vivo                                   | 1         | 0.02%   |
| Vimtron Electronics                    | 1         | 0.02%   |
| Tehuti Networks                        | 1         | 0.02%   |
| Spreadtrum Communications              | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 1955      | 37.79%  |
| Realtek RTL8125 2.5GbE Controller                                              | 276       | 5.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 244       | 4.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 177       | 3.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 152       | 2.94%   |
| Intel Ethernet Controller I225-V                                               | 126       | 2.44%   |
| Intel I211 Gigabit Network Connection                                          | 104       | 2.01%   |
| Intel Ethernet Connection I217-LM                                              | 78        | 1.51%   |
| Intel Ethernet Connection (2) I219-V                                           | 63        | 1.22%   |
| Intel Ethernet Connection (4) I219-LM                                          | 59        | 1.14%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 58        | 1.12%   |
| Intel Ethernet Connection (2) I219-LM                                          | 53        | 1.02%   |
| Intel I350 Gigabit Network Connection                                          | 50        | 0.97%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 44        | 0.85%   |
| Intel Ethernet Connection (7) I219-V                                           | 39        | 0.75%   |
| Intel Ethernet Controller I226-V                                               | 36        | 0.7%    |
| Intel Ethernet Connection (4) I219-V                                           | 36        | 0.7%    |
| Intel I210 Gigabit Network Connection                                          | 35        | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                                          | 34        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 33        | 0.64%   |
| Intel Ethernet Connection I219-LM                                              | 32        | 0.62%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 30        | 0.58%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 29        | 0.56%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 25        | 0.48%   |
| Intel Ethernet Connection (13) I219-V                                          | 25        | 0.48%   |
| Intel 82579V Gigabit Network Connection                                        | 25        | 0.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 24        | 0.46%   |
| Intel Ethernet Connection I218-LM                                              | 24        | 0.46%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 24        | 0.46%   |
| Realtek Killer E2600 GbE Controller                                            | 22        | 0.43%   |
| Intel 82574L Gigabit Network Connection                                        | 22        | 0.43%   |
| Intel Ethernet Connection (2) I218-V                                           | 21        | 0.41%   |
| Intel 82577LM Gigabit Network Connection                                       | 21        | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 20        | 0.39%   |
| Nvidia MCP79 Ethernet                                                          | 20        | 0.39%   |
| Intel Ethernet Connection (5) I219-LM                                          | 19        | 0.37%   |
| Intel 82567LM Gigabit Network Connection                                       | 19        | 0.37%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 19        | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 18        | 0.35%   |
| Intel Ethernet Connection (6) I219-V                                           | 18        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4646      | 51.66%  |
| WiFi     | 4280      | 47.59%  |
| Modem    | 55        | 0.61%   |
| Unknown  | 12        | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3229      | 56.99%  |
| Ethernet | 2436      | 42.99%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2915      | 52.35%  |
| 1     | 2321      | 41.68%  |
| 3     | 145       | 2.6%    |
| 0     | 91        | 1.63%   |
| 4     | 50        | 0.9%    |
| 8     | 17        | 0.31%   |
| 5     | 17        | 0.31%   |
| 6     | 9         | 0.16%   |
| 7     | 2         | 0.04%   |
| 12    | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3863      | 69.38%  |
| Yes  | 1705      | 30.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1764      | 47.19%  |
| Realtek Semiconductor           | 444       | 11.88%  |
| IMC Networks                    | 232       | 6.21%   |
| Qualcomm Atheros Communications | 183       | 4.9%    |
| Apple                           | 179       | 4.79%   |
| Cambridge Silicon Radio         | 166       | 4.44%   |
| Foxconn / Hon Hai               | 155       | 4.15%   |
| Broadcom                        | 118       | 3.16%   |
| Lite-On Technology              | 101       | 2.7%    |
| MediaTek                        | 91        | 2.43%   |
| ASUSTek Computer                | 63        | 1.69%   |
| Dell                            | 33        | 0.88%   |
| TP-Link                         | 29        | 0.78%   |
| Hewlett-Packard                 | 27        | 0.72%   |
| Realtek                         | 24        | 0.64%   |
| Ralink                          | 21        | 0.56%   |
| USI                             | 18        | 0.48%   |
| Toshiba                         | 16        | 0.43%   |
| Marvell Semiconductor           | 11        | 0.29%   |
| Actions                         | 10        | 0.27%   |
| Foxconn International           | 9         | 0.24%   |
| Unknown                         | 9         | 0.24%   |
| Ralink Technology               | 7         | 0.19%   |
| Edimax Technology               | 5         | 0.13%   |
| Integrated System Solution      | 4         | 0.11%   |
| Taiyo Yuden                     | 2         | 0.05%   |
| SiW                             | 2         | 0.05%   |
| Qcom                            | 2         | 0.05%   |
| Opticis                         | 2         | 0.05%   |
| Logitech                        | 2         | 0.05%   |
| Chicony Electronics             | 2         | 0.05%   |
| Alps Electric                   | 2         | 0.05%   |
| SINO WEALTH                     | 1         | 0.03%   |
| National Semiconductor          | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Dynex                           | 1         | 0.03%   |
| Belkin Components               | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 364       | 9.74%   |
| Realtek Bluetooth Radio                             | 296       | 7.92%   |
| Intel Bluetooth wireless interface                  | 269       | 7.2%    |
| Intel AX211 Bluetooth                               | 240       | 6.42%   |
| Intel Bluetooth Device                              | 237       | 6.34%   |
| Intel AX200 Bluetooth                               | 222       | 5.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 173       | 4.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 166       | 4.44%   |
| Intel AX210 Bluetooth                               | 120       | 3.21%   |
| IMC Networks Wireless_Device                        | 102       | 2.73%   |
| MediaTek Wireless_Device                            | 89        | 2.38%   |
| IMC Networks Bluetooth Radio                        | 88        | 2.35%   |
| Apple Bluetooth Host Controller                     | 86        | 2.3%    |
| Qualcomm Atheros  Bluetooth Device                  | 78        | 2.09%   |
| Foxconn / Hon Hai Wireless_Device                   | 64        | 1.71%   |
| Apple Bluetooth USB Host Controller                 | 63        | 1.69%   |
| Intel Wireless-AC 3168 Bluetooth                    | 58        | 1.55%   |
| Realtek  Bluetooth 4.2 Adapter                      | 56        | 1.5%    |
| Realtek 802.11ac WLAN Adapter                       | 46        | 1.23%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 39        | 1.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 33        | 0.88%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 31        | 0.83%   |
| TP-Link UB500 Adapter                               | 29        | 0.78%   |
| Foxconn / Hon Hai Bluetooth Device                  | 29        | 0.78%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 28        | 0.75%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 28        | 0.75%   |
| Broadcom BCM2045B (BDC-2.1)                         | 27        | 0.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 25        | 0.67%   |
| Realtek Bluetooth Radio                             | 24        | 0.64%   |
| IMC Networks Bluetooth Device                       | 24        | 0.64%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 24        | 0.64%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 23        | 0.62%   |
| Ralink RT3290 Bluetooth                             | 21        | 0.56%   |
| Lite-On Bluetooth Device                            | 19        | 0.51%   |
| ASUS ASUS USB-BT500                                 | 19        | 0.51%   |
| USI Bluetooth Device                                | 18        | 0.48%   |
| Lite-On Wireless_Device                             | 17        | 0.45%   |
| Lite-On Atheros AR3012 Bluetooth                    | 17        | 0.45%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 17        | 0.45%   |
| HP Broadcom 2070 Bluetooth Combo                    | 16        | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3714      | 47.71%  |
| AMD                                          | 1783      | 22.9%   |
| Nvidia                                       | 1391      | 17.87%  |
| C-Media Electronics                          | 111       | 1.43%   |
| Logitech                                     | 58        | 0.75%   |
| Creative Labs                                | 51        | 0.66%   |
| ASUSTek Computer                             | 33        | 0.42%   |
| Razer USA                                    | 30        | 0.39%   |
| Kingston Technology                          | 29        | 0.37%   |
| Generalplus Technology                       | 29        | 0.37%   |
| Micro Star International                     | 28        | 0.36%   |
| Hewlett-Packard                              | 28        | 0.36%   |
| Texas Instruments                            | 26        | 0.33%   |
| GN Netcom                                    | 25        | 0.32%   |
| Realtek Semiconductor                        | 22        | 0.28%   |
| JMTek                                        | 22        | 0.28%   |
| Focusrite-Novation                           | 21        | 0.27%   |
| Plantronics                                  | 18        | 0.23%   |
| Creative Technology                          | 18        | 0.23%   |
| Lenovo                                       | 17        | 0.22%   |
| Zoran Co. Personal Media Division (Nogatech) | 15        | 0.19%   |
| SteelSeries ApS                              | 14        | 0.18%   |
| Sony                                         | 12        | 0.15%   |
| Corsair                                      | 12        | 0.15%   |
| Giga-Byte Technology                         | 10        | 0.13%   |
| Apple                                        | 10        | 0.13%   |
| ASRock                                       | 9         | 0.12%   |
| Samson Technologies                          | 8         | 0.1%    |
| Dell                                         | 8         | 0.1%    |
| Tenx Technology                              | 7         | 0.09%   |
| Unknown                                      | 7         | 0.09%   |
| Silicon Integrated Systems [SiS]             | 6         | 0.08%   |
| BR25                                         | 6         | 0.08%   |
| Blue Microphones                             | 6         | 0.08%   |
| Audio-Technica                               | 6         | 0.08%   |
| TX                                           | 5         | 0.06%   |
| Trust                                        | 5         | 0.06%   |
| Thesycon Systemsoftware & Consulting         | 5         | 0.06%   |
| SAVITECH                                     | 5         | 0.06%   |
| RODE Microphones                             | 5         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 727       | 7.77%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 359       | 3.84%   |
| Intel Sunrise Point-LP HD Audio                                            | 355       | 3.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 324       | 3.46%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 289       | 3.09%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 270       | 2.89%   |
| AMD Starship/Matisse HD Audio Controller                                   | 250       | 2.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 237       | 2.53%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 204       | 2.18%   |
| Nvidia Audio device                                                        | 197       | 2.11%   |
| Intel Cannon Lake PCH cAVS                                                 | 183       | 1.96%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 179       | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 162       | 1.73%   |
| AMD FCH Azalia Controller                                                  | 157       | 1.68%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 136       | 1.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 135       | 1.44%   |
| Intel 200 Series PCH HD Audio                                              | 123       | 1.31%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 122       | 1.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 120       | 1.28%   |
| Intel Haswell-ULT HD Audio Controller                                      | 117       | 1.25%   |
| Intel 8 Series HD Audio Controller                                         | 116       | 1.24%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 115       | 1.23%   |
| Intel Raptor Lake High Definition Audio Controller                         | 107       | 1.14%   |
| Nvidia GA106 High Definition Audio Controller                              | 97        | 1.04%   |
| Intel Broadwell-U Audio Controller                                         | 97        | 1.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 92        | 0.98%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 89        | 0.95%   |
| Nvidia GA104 High Definition Audio Controller                              | 87        | 0.93%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 86        | 0.92%   |
| Nvidia GP107GL High Definition Audio Controller                            | 85        | 0.91%   |
| Intel Alder Lake-S HD Audio Controller                                     | 83        | 0.89%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 83        | 0.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 79        | 0.84%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 78        | 0.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 78        | 0.83%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 78        | 0.83%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 75        | 0.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 71        | 0.76%   |
| Intel Comet Lake PCH cAVS                                                  | 69        | 0.74%   |
| AMD Kabini HDMI/DP Audio                                                   | 68        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 792       | 21.13%  |
| SK hynix                     | 584       | 15.58%  |
| Kingston                     | 446       | 11.9%   |
| Micron Technology            | 393       | 10.49%  |
| Unknown                      | 273       | 7.28%   |
| Corsair                      | 217       | 5.79%   |
| Crucial                      | 214       | 5.71%   |
| G.Skill                      | 118       | 3.15%   |
| Unknown                      | 94        | 2.51%   |
| A-DATA Technology            | 83        | 2.21%   |
| Unknown (ABCD)               | 46        | 1.23%   |
| Ramaxel Technology           | 42        | 1.12%   |
| Elpida                       | 39        | 1.04%   |
| Nanya Technology             | 36        | 0.96%   |
| AMD                          | 31        | 0.83%   |
| Team                         | 30        | 0.8%    |
| Transcend                    | 21        | 0.56%   |
| Patriot                      | 21        | 0.56%   |
| Smart                        | 17        | 0.45%   |
| GOODRAM                      | 16        | 0.43%   |
| Hewlett-Packard              | 12        | 0.32%   |
| Apacer                       | 11        | 0.29%   |
| Kllisre                      | 9         | 0.24%   |
| Timetec                      | 8         | 0.21%   |
| Kingmax                      | 8         | 0.21%   |
| GeIL                         | 8         | 0.21%   |
| Patriot Memory (PDP Systems) | 7         | 0.19%   |
| Goldkey                      | 6         | 0.16%   |
| Atermiter                    | 5         | 0.13%   |
| Unknown (0x0B45)             | 4         | 0.11%   |
| Unifosa                      | 4         | 0.11%   |
| PNY                          | 4         | 0.11%   |
| Patriot Memory               | 4         | 0.11%   |
| Netac                        | 4         | 0.11%   |
| Neo Forza                    | 4         | 0.11%   |
| Multilaser                   | 4         | 0.11%   |
| Lexar                        | 4         | 0.11%   |
| ChangXin Memory              | 4         | 0.11%   |
| ASint Technology             | 4         | 0.11%   |
| Unknown (0x0E9D)             | 3         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 94        | 2.34%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 33        | 0.82%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 28        | 0.7%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 26        | 0.65%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 25        | 0.62%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 25        | 0.62%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 23        | 0.57%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 23        | 0.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 22        | 0.55%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 21        | 0.52%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 20        | 0.5%    |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 18        | 0.45%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 18        | 0.45%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 17        | 0.42%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 16        | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 15        | 0.37%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.37%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 15        | 0.37%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 14        | 0.35%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 14        | 0.35%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 13        | 0.32%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 13        | 0.32%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 13        | 0.32%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 13        | 0.32%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 13        | 0.32%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 13        | 0.32%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 12        | 0.3%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 12        | 0.3%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.3%    |
| Samsung RAM M393A8G40AB2-CWE 64GB DIMM DDR4 3200MT/s             | 12        | 0.3%    |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3600MT/s           | 12        | 0.3%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s            | 12        | 0.3%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 0.27%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.27%   |
| Kingston RAM KF3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s           | 11        | 0.27%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s           | 11        | 0.27%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 10        | 0.25%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 10        | 0.25%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 10        | 0.25%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 10        | 0.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1460      | 45.33%  |
| DDR3    | 911       | 28.28%  |
| DDR5    | 257       | 7.98%   |
| LPDDR4  | 142       | 4.41%   |
| LPDDR5  | 117       | 3.63%   |
| DDR2    | 113       | 3.51%   |
| Unknown | 70        | 2.17%   |
| SDRAM   | 62        | 1.92%   |
| LPDDR3  | 50        | 1.55%   |
| DRAM    | 20        | 0.62%   |
| DDR     | 19        | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1677      | 52.15%  |
| DIMM            | 1230      | 38.25%  |
| Row Of Chips    | 278       | 8.64%   |
| Chip            | 12        | 0.37%   |
| Unknown         | 12        | 0.37%   |
| FB-DIMM         | 3         | 0.09%   |
| RIMM            | 2         | 0.06%   |
| Proprietary Car | 1         | 0.03%   |
| DIP             | 1         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 1262      | 35.91%  |
| 4096    | 836       | 23.79%  |
| 16384   | 678       | 19.29%  |
| 2048    | 361       | 10.27%  |
| 32768   | 250       | 7.11%   |
| 1024    | 79        | 2.25%   |
| 65536   | 15        | 0.43%   |
| 512     | 11        | 0.31%   |
| 49152   | 7         | 0.2%    |
| 3072    | 4         | 0.11%   |
| 24576   | 3         | 0.09%   |
| 12288   | 2         | 0.06%   |
| 256     | 2         | 0.06%   |
| 131072  | 1         | 0.03%   |
| 1536    | 1         | 0.03%   |
| 16      | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 617       | 17.6%   |
| 1600    | 611       | 17.43%  |
| 2667    | 359       | 10.24%  |
| 2400    | 224       | 6.39%   |
| 1333    | 203       | 5.79%   |
| 2133    | 141       | 4.02%   |
| 4800    | 131       | 3.74%   |
| 3600    | 116       | 3.31%   |
| 6400    | 101       | 2.88%   |
| 1334    | 80        | 2.28%   |
| 5600    | 71        | 2.03%   |
| 1867    | 66        | 1.88%   |
| 667     | 62        | 1.77%   |
| Unknown | 59        | 1.68%   |
| 4267    | 57        | 1.63%   |
| 800     | 56        | 1.6%    |
| 3733    | 35        | 1%      |
| 1067    | 35        | 1%      |
| 3800    | 29        | 0.83%   |
| 1866    | 29        | 0.83%   |
| 3266    | 28        | 0.8%    |
| 3000    | 27        | 0.77%   |
| 2666    | 27        | 0.77%   |
| 1066    | 25        | 0.71%   |
| 6000    | 24        | 0.68%   |
| 3400    | 23        | 0.66%   |
| 1800    | 17        | 0.49%   |
| 2933    | 15        | 0.43%   |
| 5200    | 13        | 0.37%   |
| 4266    | 13        | 0.37%   |
| 533     | 13        | 0.37%   |
| 4199    | 12        | 0.34%   |
| 2048    | 12        | 0.34%   |
| 7467    | 11        | 0.31%   |
| 3534    | 11        | 0.31%   |
| 7500    | 10        | 0.29%   |
| 3866    | 10        | 0.29%   |
| 3466    | 9         | 0.26%   |
| 975     | 9         | 0.26%   |
| 8400    | 8         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)

![Printer Vendor](./images/line_chart/printer_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 46        | 33.58%  |
| Brother Industries       | 24        | 17.52%  |
| Canon                    | 21        | 15.33%  |
| Samsung Electronics      | 16        | 11.68%  |
| Seiko Epson              | 12        | 8.76%   |
| Prolific Technology      | 4         | 2.92%   |
| Pantum                   | 3         | 2.19%   |
| Xerox                    | 2         | 1.46%   |
| Lexmark International    | 2         | 1.46%   |
| Zhuhai Poskey Technology | 1         | 0.73%   |
| QinHeng Electronics      | 1         | 0.73%   |
| NXP Semiconductors       | 1         | 0.73%   |
| Kyocera                  | 1         | 0.73%   |
| Dymo-CoStar              | 1         | 0.73%   |
| Dell                     | 1         | 0.73%   |
| Custom Engineering SPA   | 1         | 0.73%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)

![Printer Model](./images/line_chart/printer_model.svg)

| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                             | 4         | 2.92%   |
| Samsung M2070 Series                                   | 4         | 2.92%   |
| Prolific PL2305 Parallel Port                          | 4         | 2.92%   |
| HP LaserJet 1020                                       | 3         | 2.19%   |
| HP DeskJet 2600 series                                 | 3         | 2.19%   |
| Canon LiDE 300                                         | 3         | 2.19%   |
| Brother HL-L2320D series                               | 3         | 2.19%   |
| Samsung ML-2010P Mono Laser Printer                    | 2         | 1.46%   |
| HP Printing Support                                    | 2         | 1.46%   |
| HP LaserJet P2055 series                               | 2         | 1.46%   |
| HP LaserJet 1010                                       | 2         | 1.46%   |
| HP Laser 107w                                          | 2         | 1.46%   |
| HP HP LaserJet M14-M17                                 | 2         | 1.46%   |
| HP DeskJet 2700 series                                 | 2         | 1.46%   |
| Canon PIXMA MG2500 Series                              | 2         | 1.46%   |
| Canon LiDE 400                                         | 2         | 1.46%   |
| Brother MFC-L2710DW series                             | 2         | 1.46%   |
| Brother HL-1210W series                                | 2         | 1.46%   |
| Brother DCP-9020CDW                                    | 2         | 1.46%   |
| Zhuhai Poskey DT426B                                   | 1         | 0.73%   |
| Xerox Phaser 3260                                      | 1         | 0.73%   |
| Xerox Phaser 3010                                      | 1         | 0.73%   |
| Seiko Epson XP-2100 Series                             | 1         | 0.73%   |
| Seiko Epson XP-15000 Series                            | 1         | 0.73%   |
| Seiko Epson WF-2870 Series                             | 1         | 0.73%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 0.73%   |
| Seiko Epson L395 Series                                | 1         | 0.73%   |
| Seiko Epson L210 Series                                | 1         | 0.73%   |
| Seiko Epson ET-4800 Series                             | 1         | 0.73%   |
| Seiko Epson ET-2820 Series                             | 1         | 0.73%   |
| Samsung SCX-4200 series                                | 1         | 0.73%   |
| Samsung SCX-3200 Series                                | 1         | 0.73%   |
| Samsung ML-216x Series Laser Printer                   | 1         | 0.73%   |
| Samsung ML-1670 Series                                 | 1         | 0.73%   |
| Samsung ML-1660 Series                                 | 1         | 0.73%   |
| Samsung M332x 382x 402x Series                         | 1         | 0.73%   |
| Samsung M2020 Series                                   | 1         | 0.73%   |
| Samsung C460 Series                                    | 1         | 0.73%   |
| Samsung C43x Series                                    | 1         | 0.73%   |
| Samsung C1860 Series                                   | 1         | 0.73%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)

![Scanner Vendor](./images/line_chart/scanner_vendor.svg)

| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 17        | 60.71%  |
| Seiko Epson     | 8         | 28.57%  |
| Hewlett-Packard | 2         | 7.14%   |
| Mustek Systems  | 1         | 3.57%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)

![Scanner Model](./images/line_chart/scanner_model.svg)

| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 120                                 | 6         | 21.43%  |
| Canon CanoScan LiDE 210                                 | 3         | 10.71%  |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 2         | 7.14%   |
| Canon CanoScan LIDE 25                                  | 2         | 7.14%   |
| Canon CanoScan LiDE 220                                 | 2         | 7.14%   |
| Canon CanoScan LiDE 110                                 | 2         | 7.14%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 3.57%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]       | 1         | 3.57%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]           | 1         | 3.57%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]      | 1         | 3.57%   |
| Seiko Epson GT-7400U [Perfection 1270]                  | 1         | 3.57%   |
| Seiko Epson GT-6600U [Perfection 610]                   | 1         | 3.57%   |
| Mustek Systems ScanExpress 1200 UB                      | 1         | 3.57%   |
| HP Scanjet Professional 1000 Mobile Scanner             | 1         | 3.57%   |
| HP ScanJet 82x0C                                        | 1         | 3.57%   |
| Canon CanoScan LiDE 60                                  | 1         | 3.57%   |
| Canon CanoScan LiDE 500F                                | 1         | 3.57%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)

![Camera Vendor](./images/line_chart/camera_vendor.svg)

| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 632       | 19.84%  |
| IMC Networks                           | 265       | 8.32%   |
| Microdia                               | 245       | 7.69%   |
| Realtek Semiconductor                  | 197       | 6.19%   |
| Quanta                                 | 190       | 5.97%   |
| Logitech                               | 176       | 5.53%   |
| Sunplus Innovation Technology          | 158       | 4.96%   |
| Bison Electronics                      | 158       | 4.96%   |
| Apple                                  | 129       | 4.05%   |
| Luxvisions Innotech Limited            | 104       | 3.27%   |
| Cheng Uei Precision Industry (Foxlink) | 103       | 3.23%   |
| Suyin                                  | 85        | 2.67%   |
| Lite-On Technology                     | 83        | 2.61%   |
| Syntek                                 | 82        | 2.57%   |
| Acer                                   | 73        | 2.29%   |
| Sonix Technology                       | 41        | 1.29%   |
| Alcor Micro                            | 36        | 1.13%   |
| SunplusIT                              | 29        | 0.91%   |
| Silicon Motion                         | 29        | 0.91%   |
| Microsoft                              | 28        | 0.88%   |
| Samsung Electronics                    | 26        | 0.82%   |
| ShineTech                              | 20        | 0.63%   |
| Generalplus Technology                 | 19        | 0.6%    |
| Ricoh                                  | 16        | 0.5%    |
| icSpring                               | 16        | 0.5%    |
| ARC International                      | 12        | 0.38%   |
| Importek                               | 11        | 0.35%   |
| Z-Star Microelectronics                | 10        | 0.31%   |
| Lenovo                                 | 10        | 0.31%   |
| GEMBIRD                                | 9         | 0.28%   |
| MacroSilicon                           | 7         | 0.22%   |
| KYE Systems (Mouse Systems)            | 7         | 0.22%   |
| Creative Technology                    | 7         | 0.22%   |
| ALi                                    | 7         | 0.22%   |
| Trust                                  | 6         | 0.19%   |
| Primax Electronics                     | 6         | 0.19%   |
| AVerMedia Technologies                 | 6         | 0.19%   |
| 2M UVC CAMERA                          | 6         | 0.19%   |
| Razer USA                              | 5         | 0.16%   |
| OmniVision Technologies                | 5         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 153       | 4.77%   |
| Microdia Integrated_Webcam_HD                     | 88        | 2.74%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 86        | 2.68%   |
| IMC Networks Integrated Camera                    | 72        | 2.24%   |
| Realtek Integrated_Webcam_HD                      | 61        | 1.9%    |
| Syntek Integrated Camera                          | 58        | 1.81%   |
| Bison Integrated Camera                           | 48        | 1.5%    |
| Chicony HP HD Camera                              | 41        | 1.28%   |
| Chicony HD WebCam                                 | 40        | 1.25%   |
| Logitech Webcam C270                              | 39        | 1.22%   |
| Apple FaceTime HD Camera (Built-in)               | 38        | 1.18%   |
| Sunplus Integrated_Webcam_HD                      | 37        | 1.15%   |
| Apple FaceTime HD Camera                          | 34        | 1.06%   |
| Acer Integrated Camera                            | 33        | 1.03%   |
| Quanta HD User Facing                             | 30        | 0.94%   |
| Luxvisions Innotech Limited Integrated Camera     | 30        | 0.94%   |
| Apple Built-in iSight                             | 30        | 0.94%   |
| Quanta HP TrueVision HD Camera                    | 28        | 0.87%   |
| Lite-On Integrated Camera                         | 27        | 0.84%   |
| Samsung Galaxy series, misc. (MTP mode)           | 26        | 0.81%   |
| Sonix USB2.0 HD UVC WebCam                        | 24        | 0.75%   |
| Quanta ACER HD User Facing                        | 24        | 0.75%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 24        | 0.75%   |
| Microdia USB 2.0 Camera                           | 23        | 0.72%   |
| Logitech C922 Pro Stream Webcam                   | 22        | 0.69%   |
| Realtek USB Camera                                | 21        | 0.65%   |
| Lite-On HP HD Camera                              | 21        | 0.65%   |
| Chicony HP TrueVision HD Camera                   | 21        | 0.65%   |
| Bison HD Webcam                                   | 21        | 0.65%   |
| IMC Networks HD Camera                            | 20        | 0.62%   |
| Chicony Integrated Camera (1280x720@30)           | 20        | 0.62%   |
| Microdia Webcam Vitade AF                         | 18        | 0.56%   |
| Logitech HD Pro Webcam C920                       | 18        | 0.56%   |
| Chicony USB2.0 VGA UVC WebCam                     | 18        | 0.56%   |
| Chicony HD User Facing                            | 18        | 0.56%   |
| Bison BisonCam,NB Pro                             | 18        | 0.56%   |
| Quanta HP Wide Vision HD Camera                   | 17        | 0.53%   |
| Microdia Integrated Webcam                        | 17        | 0.53%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 17        | 0.53%   |
| Chicony TOSHIBA Web Camera - HD                   | 17        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 175       | 32.59%  |
| Synaptics                          | 157       | 29.24%  |
| Shenzhen Goodix Technology         | 90        | 16.76%  |
| Upek                               | 30        | 5.59%   |
| Elan Microelectronics              | 25        | 4.66%   |
| AuthenTec                          | 17        | 3.17%   |
| LighTuning Technology              | 16        | 2.98%   |
| Focal-systems.Corp                 | 6         | 1.12%   |
| STMicroelectronics                 | 5         | 0.93%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 0.74%   |
| FocalTech                          | 4         | 0.74%   |
| Samsung Electronics                | 3         | 0.56%   |
| Dell                               | 2         | 0.37%   |
| Next Biometrics                    | 1         | 0.19%   |
| HOLTEK                             | 1         | 0.19%   |
| GDMicroelectronics                 | 1         | 0.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 63        | 11.73%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 43        | 8.01%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 41        | 7.64%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 30        | 5.59%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 23        | 4.28%   |
| Validity Sensors Synaptics WBDI                                            | 19        | 3.54%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 19        | 3.54%   |
| Shenzhen Goodix Fingerprint Reader                                         | 19        | 3.54%   |
| Elan ELAN:ARM-M4                                                           | 18        | 3.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 17        | 3.17%   |
| Synaptics UWP WBDI Device                                                  | 16        | 2.98%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 15        | 2.79%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 2.42%   |
| Validity Sensors VFS491                                                    | 13        | 2.42%   |
| Synaptics  WBDI                                                            | 12        | 2.23%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 11        | 2.05%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 2.05%   |
| Validity Sensors Fingerprint scanner                                       | 10        | 1.86%   |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 1.68%   |
| Synaptics WBDI                                                             | 8         | 1.49%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 1.49%   |
| Shenzhen Goodix FingerPrint                                                | 8         | 1.49%   |
| AuthenTec AES2810                                                          | 8         | 1.49%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 1.3%    |
| Elan ELAN:Fingerprint                                                      | 7         | 1.3%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 6         | 1.12%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 0.93%   |
| Synaptics UWP WBDI                                                         | 5         | 0.93%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 0.93%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 0.93%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 0.93%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 0.93%   |
| Synaptics WBDI Device                                                      | 4         | 0.74%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 0.74%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.74%   |
| FocalTech Fingerprint Device                                               | 4         | 0.74%   |
| AuthenTec AES1600                                                          | 4         | 0.74%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.56%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./images/line_chart/chipcard_vendor.svg)

| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 115       | 46.37%  |
| Alcor Micro               | 79        | 31.85%  |
| O2 Micro                  | 12        | 4.84%   |
| Lenovo                    | 9         | 3.63%   |
| Upek                      | 8         | 3.23%   |
| Gemalto (was Gemplus)     | 5         | 2.02%   |
| Aladdin Knowledge Systems | 5         | 2.02%   |
| Yubico.com                | 3         | 1.21%   |
| SCM Microsystems          | 3         | 1.21%   |
| Chicony Electronics       | 3         | 1.21%   |
| CHERRY                    | 2         | 0.81%   |
| Reiner SCT Kartensysteme  | 1         | 0.4%    |
| Realtek Semiconductor     | 1         | 0.4%    |
| Fujitsu Siemens Computers | 1         | 0.4%    |
| Advanced Card Systems     | 1         | 0.4%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)

![Chipcard Model](./images/line_chart/chipcard_model.svg)

| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 78        | 31.45%  |
| Broadcom 58200                                                               | 43        | 17.34%  |
| Broadcom BCM5880 Secure Applications Processor                               | 29        | 11.69%  |
| Broadcom 5880                                                                | 25        | 10.08%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 17        | 6.85%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 11        | 4.44%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 3.23%   |
| Lenovo Integrated Smart Card Reader                                          | 8         | 3.23%   |
| Aladdin Knowledge Systems Token JC                                           | 5         | 2.02%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 1.21%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 3         | 1.21%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.81%   |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                                  | 2         | 0.81%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.4%    |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.4%    |
| SCM Microsystems Identiv SmartOS Reader                                      | 1         | 0.4%    |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.4%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.4%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.4%    |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.4%    |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.4%    |
| Gemalto (was Gemplus) eToken 5110+ FIPS                                      | 1         | 0.4%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.4%    |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.4%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.4%    |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.4%    |
| Advanced Card Systems ACR39U                                                 | 1         | 0.4%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3826      | 68.71%  |
| 1     | 1361      | 24.44%  |
| 2     | 269       | 4.83%   |
| 3     | 71        | 1.28%   |
| 4     | 29        | 0.52%   |
| 5     | 6         | 0.11%   |
| 8     | 2         | 0.04%   |
| 6     | 2         | 0.04%   |
| 9     | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 564       | 25.93%  |
| Fingerprint reader       | 528       | 24.28%  |
| Net/wireless             | 226       | 10.39%  |
| Chipcard                 | 188       | 8.64%   |
| Multimedia controller    | 185       | 8.51%   |
| Communication controller | 132       | 6.07%   |
| Unassigned class         | 97        | 4.46%   |
| Camera                   | 59        | 2.71%   |
| Bluetooth                | 57        | 2.62%   |
| Sound                    | 36        | 1.66%   |
| Storage                  | 24        | 1.1%    |
| Net/ethernet             | 21        | 0.97%   |
| Card reader              | 18        | 0.83%   |
| Storage/raid             | 17        | 0.78%   |
| Network                  | 7         | 0.32%   |
| Modem                    | 6         | 0.28%   |
| Storage/ata              | 2         | 0.09%   |
| Firewire controller      | 2         | 0.09%   |
| Wireless                 | 1         | 0.05%   |
| Video                    | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |
| Storage/ide              | 1         | 0.05%   |
| Flash memory             | 1         | 0.05%   |
| Dvb card                 | 1         | 0.05%   |

