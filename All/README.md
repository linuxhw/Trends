Linux - Hardware Trends
-----------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Desktop/README.md) and [notebooks](/Notebook/README.md).

Distribution-specific reports: [Arch](/Dist/Arch), [ArcoLinux](/Dist/ArcoLinux), [BlackPanther](/Dist/BlackPanther), [CentOS](/Dist/CentOS), [Clear Linux](/Dist/Clear_Linux), [Debian](/Dist/Debian), [Elementary](/Dist/Elementary), [EndeavourOS](/Dist/EndeavourOS), [Endless](/Dist/Endless), [Fedora](/Dist/Fedora), [Garuda Linux](/Dist/Garuda_Linux), [Gentoo](/Dist/Gentoo), [Kali](/Dist/Kali), [KDE neon](/Dist/KDE_neon), [Kubuntu](/Dist/Kubuntu), [Linux Mint](/Dist/Linux_Mint), [Manjaro](/Dist/Manjaro), [OpenMandriva](/Dist/OpenMandriva), [openSUSE](/Dist/openSUSE), [Pop!_OS](/Dist/Pop!_OS), [Red OS](/Dist/Red_OS), [ROSA](/Dist/ROSA), [SteamOS](/Dist/SteamOS), [Ubuntu MATE](/Dist/Ubuntu_MATE), [Ubuntu](/Dist/Ubuntu), [Xubuntu](/Dist/Xubuntu), [Zorin](/Dist/Zorin).

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/linuxhw/TestCoverage)

Period: Jan, 2023.

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
| OpenMandriva 23.01           | 1129      | 17.17%  |
| Ubuntu 22.04                 | 835       | 12.7%   |
| Linux Mint 21.1              | 417       | 6.34%   |
| Fedora 37                    | 406       | 6.17%   |
| Ubuntu 22.10                 | 297       | 4.52%   |
| Debian 11                    | 282       | 4.29%   |
| Pop!_OS 22.04                | 233       | 3.54%   |
| Arch Rolling                 | 201       | 3.06%   |
| ROSA 12.3                    | 199       | 3.03%   |
| Zorin 16                     | 177       | 2.69%   |
| Ubuntu 20.04                 | 164       | 2.49%   |
| OpenMandriva 4.3             | 116       | 1.76%   |
| KDE neon 22.04               | 103       | 1.57%   |
| Linux Mint 20.3              | 101       | 1.54%   |
| Manjaro                      | 87        | 1.32%   |
| Kubuntu 22.04                | 77        | 1.17%   |
| SteamOS 3.4.4                | 76        | 1.16%   |
| ArcoLinux Rolling            | 66        | 1%      |
| openSUSE Tumbleweed-XXXXXXXX | 64        | 0.97%   |
| Linux Mint 21                | 60        | 0.91%   |
| Ubuntu 18.04                 | 57        | 0.87%   |
| Debian                       | 56        | 0.85%   |
| Kubuntu 22.10                | 55        | 0.84%   |
| Kali 2022.4                  | 52        | 0.79%   |
| EndeavourOS Rolling          | 49        | 0.75%   |
| Manjaro 22.0.0               | 48        | 0.73%   |
| Gentoo 2.9                   | 47        | 0.71%   |
| Elementary 6.1               | 40        | 0.61%   |
| Nobara 37                    | 39        | 0.59%   |
| Fedora 36                    | 37        | 0.56%   |
| Xubuntu 22.04                | 36        | 0.55%   |
| LMDE 5                       | 36        | 0.55%   |
| BlackPanther 18.1            | 35        | 0.53%   |
| Lubuntu 22.04                | 29        | 0.44%   |
| Ubuntu MATE 22.04            | 27        | 0.41%   |
| Xubuntu 20.04                | 26        | 0.4%    |
| Manjaro 22.0                 | 24        | 0.36%   |
| MX 21                        | 22        | 0.33%   |
| Nobara 36                    | 19        | 0.29%   |
| OpenMandriva 4.50            | 18        | 0.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1362      | 20.71%  |
| OpenMandriva  | 1311      | 19.94%  |
| Linux Mint    | 630       | 9.58%   |
| Fedora        | 459       | 6.98%   |
| Debian        | 351       | 5.34%   |
| Pop!_OS       | 236       | 3.59%   |
| ROSA          | 230       | 3.5%    |
| Arch          | 201       | 3.06%   |
| Zorin         | 189       | 2.87%   |
| Manjaro       | 178       | 2.71%   |
| Kubuntu       | 151       | 2.3%    |
| KDE neon      | 110       | 1.67%   |
| SteamOS       | 101       | 1.54%   |
| Xubuntu       | 82        | 1.25%   |
| openSUSE      | 79        | 1.2%    |
| ArcoLinux     | 71        | 1.08%   |
| Nobara        | 58        | 0.88%   |
| Kali          | 57        | 0.87%   |
| EndeavourOS   | 49        | 0.75%   |
| Gentoo        | 48        | 0.73%   |
| Elementary    | 45        | 0.68%   |
| Ubuntu MATE   | 44        | 0.67%   |
| Lubuntu       | 39        | 0.59%   |
| LMDE          | 36        | 0.55%   |
| BlackPanther  | 35        | 0.53%   |
| Endless       | 30        | 0.46%   |
| ALT Linux     | 28        | 0.43%   |
| Garuda Linux  | 26        | 0.4%    |
| Red OS        | 24        | 0.36%   |
| MX            | 22        | 0.33%   |
| Ubuntu Unity  | 21        | 0.32%   |
| Rocky Linux   | 17        | 0.26%   |
| Parrot        | 14        | 0.21%   |
| Ubuntu Budgie | 12        | 0.18%   |
| AlmaLinux     | 12        | 0.18%   |
| NixOS         | 9         | 0.14%   |
| CentOS        | 9         | 0.14%   |
| BunsenLabs    | 9         | 0.14%   |
| Raspbian      | 8         | 0.12%   |
| Xero          | 7         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 6.1.1-desktop-1omv2290             | 1098      | 16.7%   |
| 5.15.0-58-generic                  | 877       | 13.34%  |
| 5.15.0-56-generic                  | 459       | 6.98%   |
| 5.15.0-57-generic                  | 333       | 5.06%   |
| 6.0.12-76060006-generic            | 212       | 3.22%   |
| 5.10.0-20-amd64                    | 191       | 2.9%    |
| 5.19.0-29-generic                  | 164       | 2.49%   |
| 5.16.7-desktop-1omv4003            | 111       | 1.69%   |
| 5.4.0-137-generic                  | 96        | 1.46%   |
| 5.13.0-valve36-1-neptune           | 86        | 1.31%   |
| 5.15.79-generic-1rosa2021.1-x86_64 | 80        | 1.22%   |
| 6.1.1-1-MANJARO                    | 79        | 1.2%    |
| 5.19.0-28-generic                  | 74        | 1.13%   |
| 6.1.7-200.fc37.x86_64              | 68        | 1.03%   |
| 6.0.15-300.fc37.x86_64             | 68        | 1.03%   |
| 5.15.0-43-generic                  | 60        | 0.91%   |
| 5.19.0-26-generic                  | 59        | 0.9%    |
| 6.1.6-200.fc37.x86_64              | 57        | 0.87%   |
| 5.15.75-generic-1rosa2021.1-x86_64 | 57        | 0.87%   |
| 5.4.0-136-generic                  | 53        | 0.81%   |
| 6.0.18-300.fc37.x86_64             | 46        | 0.7%    |
| 5.4.0-135-generic                  | 46        | 0.7%    |
| 5.10.0-21-amd64                    | 43        | 0.65%   |
| 6.0.16-300.fc37.x86_64             | 41        | 0.62%   |
| 6.1.4-arch1-1                      | 40        | 0.61%   |
| 5.15.85-1-MANJARO                  | 39        | 0.59%   |
| 6.1.7-arch1-1                      | 37        | 0.56%   |
| 6.1.5-200.fc37.x86_64              | 35        | 0.53%   |
| 6.0.0-kali6-amd64                  | 34        | 0.52%   |
| 5.19.0-21-generic                  | 33        | 0.5%    |
| 6.1.1-arch1-1                      | 31        | 0.47%   |
| 6.0.7-301.fc37.x86_64              | 31        | 0.47%   |
| 6.0.0-6-amd64                      | 31        | 0.47%   |
| 6.0.17-300.fc37.x86_64             | 29        | 0.44%   |
| 6.1.8-arch1-1                      | 27        | 0.41%   |
| 5.10.0-2-amd64                     | 27        | 0.41%   |
| 6.1.3-arch1-1                      | 23        | 0.35%   |
| 6.1.2-arch1-1                      | 22        | 0.33%   |
| 6.1.7-1-MANJARO                    | 21        | 0.32%   |
| 5.6.14-desktop-2bP                 | 20        | 0.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.0   | 1865      | 28.36%  |
| 6.1.1    | 1238      | 18.83%  |
| 5.19.0   | 381       | 5.79%   |
| 5.10.0   | 316       | 4.81%   |
| 5.4.0    | 266       | 4.05%   |
| 6.0.12   | 229       | 3.48%   |
| 6.1.7    | 176       | 2.68%   |
| 6.1.6    | 143       | 2.17%   |
| 6.0.0    | 132       | 2.01%   |
| 6.1.4    | 114       | 1.73%   |
| 5.16.7   | 111       | 1.69%   |
| 5.13.0   | 111       | 1.69%   |
| 6.0.15   | 89        | 1.35%   |
| 5.15.79  | 83        | 1.26%   |
| 6.1.8    | 75        | 1.14%   |
| 6.1.5    | 74        | 1.13%   |
| 5.15.75  | 67        | 1.02%   |
| 6.1.3    | 59        | 0.9%    |
| 6.0.16   | 53        | 0.81%   |
| 6.0.18   | 52        | 0.79%   |
| 6.1.2    | 51        | 0.78%   |
| 5.15.85  | 46        | 0.7%    |
| 6.1.0    | 45        | 0.68%   |
| 5.14.0   | 44        | 0.67%   |
| 4.15.0   | 43        | 0.65%   |
| 6.0.7    | 36        | 0.55%   |
| 6.0.17   | 32        | 0.49%   |
| 5.11.0   | 31        | 0.47%   |
| 6.0.10   | 24        | 0.36%   |
| 6.0.14   | 20        | 0.3%    |
| 5.6.14   | 20        | 0.3%    |
| 5.15.86  | 20        | 0.3%    |
| 5.15.80  | 20        | 0.3%    |
| 5.10.155 | 19        | 0.29%   |
| 5.10.14  | 17        | 0.26%   |
| 5.8.0    | 15        | 0.23%   |
| 4.18.16  | 15        | 0.23%   |
| 6.0.9    | 14        | 0.21%   |
| 5.17.0   | 14        | 0.21%   |
| 5.15.84  | 14        | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version   | Computers | Percent |
|-----------|-----------|---------|
| 5.15      | 2205      | 33.53%  |
| 6.1       | 1975      | 30.03%  |
| 6.0       | 723       | 10.99%  |
| 5.19      | 416       | 6.33%   |
| 5.10      | 406       | 6.17%   |
| 5.4       | 287       | 4.36%   |
| 5.16      | 127       | 1.93%   |
| 5.13      | 112       | 1.7%    |
| 5.14      | 60        | 0.91%   |
| 4.15      | 43        | 0.65%   |
| 5.18      | 35        | 0.53%   |
| 5.11      | 33        | 0.5%    |
| 5.17      | 32        | 0.49%   |
| 4.18      | 24        | 0.36%   |
| 5.6       | 20        | 0.3%    |
| 5.8       | 15        | 0.23%   |
| 4.19      | 15        | 0.23%   |
| 6.2       | 12        | 0.18%   |
| 3.10      | 8         | 0.12%   |
| 4.4       | 7         | 0.11%   |
| 4.9       | 5         | 0.08%   |
| 5.12      | 4         | 0.06%   |
| 5.3       | 2         | 0.03%   |
| 5.0       | 2         | 0.03%   |
| 5.9       | 1         | 0.02%   |
| 4.8       | 1         | 0.02%   |
| 4.16      | 1         | 0.02%   |
| 4.14.194  | 1         | 0.02%   |
| 4.10      | 1         | 0.02%   |
| 3.4       | 1         | 0.02%   |
| 2.6       | 1         | 0.02%   |
| Unknown   | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 6466      | 98.33%  |
| i686        | 59        | 0.9%    |
| aarch64     | 31        | 0.47%   |
| armv7l      | 14        | 0.21%   |
| armv6l      | 2         | 0.03%   |
| riscv64     | 1         | 0.02%   |
| mips        | 1         | 0.02%   |
| loongarch64 | 1         | 0.02%   |
| armv8l      | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 2653      | 40.34%  |
| KDE5              | 2171      | 33.01%  |
| X-Cinnamon        | 577       | 8.77%   |
| XFCE              | 382       | 5.81%   |
| Unknown           | 215       | 3.27%   |
| MATE              | 183       | 2.78%   |
| LXQt              | 70        | 1.06%   |
| Pantheon          | 49        | 0.75%   |
| Cinnamon          | 44        | 0.67%   |
| i3                | 33        | 0.5%    |
| LXDE              | 28        | 0.43%   |
| Unity             | 22        | 0.33%   |
| Budgie            | 17        | 0.26%   |
| KDE               | 16        | 0.24%   |
| GNOME Flashback   | 13        | 0.2%    |
| KDE4              | 9         | 0.14%   |
| sway              | 8         | 0.12%   |
| hyprland          | 7         | 0.11%   |
| GNOME Classic     | 7         | 0.11%   |
| Deepin            | 7         | 0.11%   |
| openbox           | 6         | 0.09%   |
| lightdm-xsession  | 6         | 0.09%   |
| awesome           | 6         | 0.09%   |
| dwm               | 5         | 0.08%   |
| LeftWM            | 4         | 0.06%   |
| BunsenLabs        | 4         | 0.06%   |
| qtile             | 3         | 0.05%   |
| bspwm             | 3         | 0.05%   |
| xmonad            | 2         | 0.03%   |
| Trinity           | 2         | 0.03%   |
| i3-with-shmlog    | 2         | 0.03%   |
| fly               | 2         | 0.03%   |
| fluxbox           | 2         | 0.03%   |
| Enlightenment     | 2         | 0.03%   |
| chadwm            | 2         | 0.03%   |
| x-session-manager | 1         | 0.02%   |
| X-Generic         | 1         | 0.02%   |
| wayfire-session   | 1         | 0.02%   |
| TOS:GNOME         | 1         | 0.02%   |
| sussy_bspwm       | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 4529      | 68.87%  |
| Wayland     | 1776      | 27.01%  |
| Tty         | 153       | 2.33%   |
| Unknown     | 117       | 1.78%   |
| Unspecified | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1850      | 28.13%  |
| SDDM    | 1795      | 27.3%   |
| GDM3    | 1320      | 20.07%  |
| LightDM | 878       | 13.35%  |
| GDM     | 692       | 10.52%  |
| XDM     | 10        | 0.15%   |
| SLiM    | 10        | 0.15%   |
| KDM     | 8         | 0.12%   |
| LXDM    | 4         | 0.06%   |
| Ly      | 2         | 0.03%   |
| GREETD  | 2         | 0.03%   |
| FLY-DM  | 2         | 0.03%   |
| TDM     | 1         | 0.02%   |
| NODM    | 1         | 0.02%   |
| LYNDE   | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2957      | 44.97%  |
| ru_RU   | 540       | 8.21%   |
| de_DE   | 498       | 7.57%   |
| fr_FR   | 314       | 4.77%   |
| en_GB   | 312       | 4.74%   |
| pt_BR   | 218       | 3.32%   |
| it_IT   | 215       | 3.27%   |
| es_ES   | 150       | 2.28%   |
| pl_PL   | 148       | 2.25%   |
| en_CA   | 116       | 1.76%   |
| Unknown | 109       | 1.66%   |
| C       | 96        | 1.46%   |
| en_AU   | 81        | 1.23%   |
| nl_NL   | 58        | 0.88%   |
| es_MX   | 54        | 0.82%   |
| cs_CZ   | 52        | 0.79%   |
| en_IN   | 50        | 0.76%   |
| de_AT   | 34        | 0.52%   |
| hu_HU   | 29        | 0.44%   |
| de_CH   | 28        | 0.43%   |
| zh_CN   | 27        | 0.41%   |
| en_NZ   | 26        | 0.4%    |
| es_CO   | 23        | 0.35%   |
| tr_TR   | 22        | 0.33%   |
| es_AR   | 22        | 0.33%   |
| sv_SE   | 18        | 0.27%   |
| pt_PT   | 18        | 0.27%   |
| fr_CA   | 17        | 0.26%   |
| en_ZA   | 16        | 0.24%   |
| en_IE   | 16        | 0.24%   |
| es_CL   | 15        | 0.23%   |
| el_GR   | 15        | 0.23%   |
| fi_FI   | 14        | 0.21%   |
| ro_RO   | 13        | 0.2%    |
| fr_BE   | 12        | 0.18%   |
| da_DK   | 11        | 0.17%   |
| nb_NO   | 10        | 0.15%   |
| ja_JP   | 10        | 0.15%   |
| es_VE   | 10        | 0.15%   |
| en_DK   | 10        | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 3528      | 53.65%  |
| BIOS | 3048      | 46.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 4267      | 64.89%  |
| Overlay | 1232      | 18.73%  |
| Btrfs   | 906       | 13.78%  |
| Xfs     | 75        | 1.14%   |
| Zfs     | 54        | 0.82%   |
| F2fs    | 11        | 0.17%   |
| Tmpfs   | 10        | 0.15%   |
| Ext3    | 9         | 0.14%   |
| Ext2    | 5         | 0.08%   |
| Unknown | 3         | 0.05%   |
| XXXXXXX | 2         | 0.03%   |
| Jfs     | 1         | 0.02%   |
| Aufs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3909      | 59.44%  |
| Unknown | 1673      | 25.44%  |
| MBR     | 994       | 15.12%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5158      | 78.44%  |
| Yes       | 1418      | 21.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4577      | 69.6%   |
| Yes       | 1999      | 30.4%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1104      | 16.79%  |
| Lenovo                  | 963       | 14.64%  |
| Hewlett-Packard         | 879       | 13.37%  |
| Dell                    | 748       | 11.37%  |
| Gigabyte Technology     | 469       | 7.13%   |
| MSI                     | 393       | 5.98%   |
| Acer                    | 385       | 5.85%   |
| ASRock                  | 228       | 3.47%   |
| Apple                   | 149       | 2.27%   |
| Intel                   | 98        | 1.49%   |
| Valve                   | 90        | 1.37%   |
| Toshiba                 | 76        | 1.16%   |
| Samsung Electronics     | 59        | 0.9%    |
| Unknown                 | 57        | 0.87%   |
| HUAWEI                  | 50        | 0.76%   |
| Fujitsu                 | 50        | 0.76%   |
| Google                  | 42        | 0.64%   |
| Sony                    | 37        | 0.56%   |
| Medion                  | 29        | 0.44%   |
| Microsoft               | 28        | 0.43%   |
| AZW                     | 28        | 0.43%   |
| Raspberry Pi Foundation | 26        | 0.4%    |
| Notebook                | 25        | 0.38%   |
| Pegatron                | 24        | 0.36%   |
| Timi                    | 19        | 0.29%   |
| System76                | 18        | 0.27%   |
| Chuwi                   | 17        | 0.26%   |
| Alienware               | 17        | 0.26%   |
| TUXEDO                  | 16        | 0.24%   |
| Foxconn                 | 15        | 0.23%   |
| Supermicro              | 14        | 0.21%   |
| Biostar                 | 14        | 0.21%   |
| Positivo                | 13        | 0.2%    |
| Packard Bell            | 13        | 0.2%    |
| ECS                     | 13        | 0.2%    |
| Clevo                   | 13        | 0.2%    |
| Gateway                 | 11        | 0.17%   |
| GPU Company             | 10        | 0.15%   |
| BESSTAR Tech            | 10        | 0.15%   |
| Schenker                | 9         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Valve Jupiter                      | 90        | 1.37%   |
| Unknown                            | 74        | 1.13%   |
| ASUS All Series                    | 71        | 1.08%   |
| HP Notebook                        | 26        | 0.4%    |
| ASUS TUF Gaming X570-PLUS          | 19        | 0.29%   |
| ASUS PRIME A320M-K                 | 17        | 0.26%   |
| Dell OptiPlex 7010                 | 16        | 0.24%   |
| Gigabyte B550M DS3H                | 14        | 0.21%   |
| MSI MS-7C91                        | 13        | 0.2%    |
| MSI MS-7C37                        | 13        | 0.2%    |
| ASUS M5A97 R2.0                    | 13        | 0.2%    |
| MSI MS-7C56                        | 12        | 0.18%   |
| MSI MS-7C02                        | 12        | 0.18%   |
| HP Pavilion dv6                    | 11        | 0.17%   |
| Gigabyte B450M DS3H                | 11        | 0.17%   |
| ASRock B450M Pro4                  | 11        | 0.17%   |
| Dell XPS 15 9570                   | 10        | 0.15%   |
| Dell OptiPlex 790                  | 10        | 0.15%   |
| Gigabyte A320M-S2H                 | 9         | 0.14%   |
| ASUS ROG STRIX B550-F GAMING       | 9         | 0.14%   |
| ASUS PRIME B450M-A                 | 9         | 0.14%   |
| RPi Raspberry Pi 4 Model B Rev 1.1 | 8         | 0.12%   |
| MSI MS-7B89                        | 8         | 0.12%   |
| MSI MS-7B86                        | 8         | 0.12%   |
| HP Pavilion Notebook               | 8         | 0.12%   |
| HP Pavilion g6                     | 8         | 0.12%   |
| HP Pavilion 15                     | 8         | 0.12%   |
| HP Laptop 15s-eq2xxx               | 8         | 0.12%   |
| Dell OptiPlex 9020                 | 8         | 0.12%   |
| Dell OptiPlex 3020                 | 8         | 0.12%   |
| Dell Latitude E6420                | 8         | 0.12%   |
| AZW SER                            | 8         | 0.12%   |
| ASUS TUF Gaming FX505DT_FX505DT    | 8         | 0.12%   |
| ASUS TUF Gaming B550M-PLUS         | 8         | 0.12%   |
| ASUS TUF Gaming B550-PLUS          | 8         | 0.12%   |
| ASUS PRIME X570-P                  | 8         | 0.12%   |
| Apple MacBookPro8,1                | 8         | 0.12%   |
| MSI MS-7D22                        | 7         | 0.11%   |
| MSI MS-7817                        | 7         | 0.11%   |
| MSI MS-7693                        | 7         | 0.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 385       | 5.85%   |
| Acer Aspire        | 261       | 3.97%   |
| Lenovo IdeaPad     | 215       | 3.27%   |
| Dell Latitude      | 191       | 2.9%    |
| Dell Inspiron      | 176       | 2.68%   |
| ASUS PRIME         | 158       | 2.4%    |
| HP Pavilion        | 152       | 2.31%   |
| ASUS ROG           | 137       | 2.08%   |
| Dell OptiPlex      | 120       | 1.82%   |
| HP EliteBook       | 114       | 1.73%   |
| ASUS VivoBook      | 94        | 1.43%   |
| ASUS TUF           | 92        | 1.4%    |
| Valve Jupiter      | 90        | 1.37%   |
| HP Laptop          | 88        | 1.34%   |
| Dell XPS           | 87        | 1.32%   |
| Dell Precision     | 77        | 1.17%   |
| HP ProBook         | 75        | 1.14%   |
| Unknown            | 74        | 1.13%   |
| HP Compaq          | 72        | 1.09%   |
| ASUS All           | 71        | 1.08%   |
| Lenovo ThinkCentre | 64        | 0.97%   |
| Toshiba Satellite  | 61        | 0.93%   |
| HP ENVY            | 48        | 0.73%   |
| Lenovo Legion      | 47        | 0.71%   |
| Lenovo Yoga        | 38        | 0.58%   |
| Acer Nitro         | 33        | 0.5%    |
| HP ZBook           | 32        | 0.49%   |
| Dell Vostro        | 32        | 0.49%   |
| ASUS ZenBook       | 31        | 0.47%   |
| HP EliteDesk       | 30        | 0.46%   |
| ASUS ASUS          | 30        | 0.46%   |
| Acer Swift         | 30        | 0.46%   |
| Microsoft Surface  | 28        | 0.43%   |
| Gigabyte B450M     | 27        | 0.41%   |
| RPi Raspberry      | 26        | 0.4%    |
| HP Notebook        | 26        | 0.4%    |
| HP OMEN            | 23        | 0.35%   |
| Fujitsu LIFEBOOK   | 23        | 0.35%   |
| ASUS M5A97         | 23        | 0.35%   |
| Gigabyte B550M     | 22        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 768       | 11.68%  |
| 2020    | 682       | 10.37%  |
| 2022    | 661       | 10.05%  |
| 2019    | 532       | 8.09%   |
| 2018    | 520       | 7.91%   |
| 2012    | 503       | 7.65%   |
| 2013    | 404       | 6.14%   |
| 2017    | 394       | 5.99%   |
| 2011    | 372       | 5.66%   |
| 2014    | 318       | 4.84%   |
| 2015    | 316       | 4.81%   |
| 2016    | 293       | 4.46%   |
| 2010    | 245       | 3.73%   |
| 2009    | 194       | 2.95%   |
| 2008    | 178       | 2.71%   |
| 2007    | 91        | 1.38%   |
| Unknown | 52        | 0.79%   |
| 2006    | 27        | 0.41%   |
| 2005    | 17        | 0.26%   |
| 2023    | 3         | 0.05%   |
| 2003    | 3         | 0.05%   |
| 2004    | 1         | 0.02%   |
| 2002    | 1         | 0.02%   |
| 2001    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3494      | 53.13%  |
| Desktop        | 2489      | 37.85%  |
| Convertible    | 201       | 3.06%   |
| Mini pc        | 125       | 1.9%    |
| All in one     | 93        | 1.41%   |
| Tablet         | 72        | 1.09%   |
| Server         | 55        | 0.84%   |
| System on chip | 41        | 0.62%   |
| Phone          | 4         | 0.06%   |
| Other          | 2         | 0.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6148      | 93.49%  |
| Enabled  | 428       | 6.51%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6515      | 99.07%  |
| Yes  | 61        | 0.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1545      | 23.49%  |
| 16.01-24.0      | 1400      | 21.29%  |
| 8.01-16.0       | 1223      | 18.6%   |
| 3.01-4.0        | 1026      | 15.6%   |
| 32.01-64.0      | 768       | 11.68%  |
| 64.01-256.0     | 206       | 3.13%   |
| 1.01-2.0        | 177       | 2.69%   |
| 24.01-32.0      | 144       | 2.19%   |
| 2.01-3.0        | 52        | 0.79%   |
| 0.51-1.0        | 20        | 0.3%    |
| More than 256.0 | 10        | 0.15%   |
| 0.01-0.5        | 5         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 2281      | 34.69%  |
| 2.01-3.0    | 1706      | 25.94%  |
| 4.01-8.0    | 1033      | 15.71%  |
| 3.01-4.0    | 812       | 12.35%  |
| 0.51-1.0    | 329       | 5%      |
| 8.01-16.0   | 285       | 4.33%   |
| 0.01-0.5    | 59        | 0.9%    |
| 16.01-24.0  | 41        | 0.62%   |
| 32.01-64.0  | 11        | 0.17%   |
| 24.01-32.0  | 10        | 0.15%   |
| 64.01-256.0 | 6         | 0.09%   |
| Unknown     | 2         | 0.03%   |
| 0           | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3835      | 58.32%  |
| 2      | 1677      | 25.5%   |
| 3      | 516       | 7.85%   |
| 4      | 260       | 3.95%   |
| 5      | 121       | 1.84%   |
| 0      | 50        | 0.76%   |
| 6      | 48        | 0.73%   |
| 7      | 32        | 0.49%   |
| 8      | 13        | 0.2%    |
| 9      | 6         | 0.09%   |
| 10     | 4         | 0.06%   |
| 28     | 3         | 0.05%   |
| 18     | 2         | 0.03%   |
| 13     | 2         | 0.03%   |
| 27     | 1         | 0.02%   |
| 26     | 1         | 0.02%   |
| 25     | 1         | 0.02%   |
| 20     | 1         | 0.02%   |
| 17     | 1         | 0.02%   |
| 12     | 1         | 0.02%   |
| 11     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4387      | 66.71%  |
| Yes       | 2189      | 33.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5495      | 83.56%  |
| No        | 1081      | 16.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5048      | 76.76%  |
| No        | 1528      | 23.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4151      | 63.12%  |
| No        | 2425      | 36.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1244      | 18.92%  |
| Germany      | 676       | 10.28%  |
| Russia       | 611       | 9.29%   |
| France       | 378       | 5.75%   |
| Italy        | 318       | 4.84%   |
| Brazil       | 312       | 4.74%   |
| UK           | 261       | 3.97%   |
| Canada       | 234       | 3.56%   |
| Spain        | 201       | 3.06%   |
| Poland       | 188       | 2.86%   |
| Netherlands  | 155       | 2.36%   |
| Australia    | 122       | 1.86%   |
| Hungary      | 87        | 1.32%   |
| India        | 81        | 1.23%   |
| Czechia      | 81        | 1.23%   |
| Mexico       | 80        | 1.22%   |
| Switzerland  | 75        | 1.14%   |
| Turkey       | 66        | 1%      |
| Austria      | 64        | 0.97%   |
| Sweden       | 57        | 0.87%   |
| Romania      | 57        | 0.87%   |
| Finland      | 55        | 0.84%   |
| Belgium      | 55        | 0.84%   |
| Portugal     | 49        | 0.75%   |
| Japan        | 49        | 0.75%   |
| Greece       | 48        | 0.73%   |
| Indonesia    | 45        | 0.68%   |
| Argentina    | 43        | 0.65%   |
| New Zealand  | 39        | 0.59%   |
| Norway       | 37        | 0.56%   |
| Colombia     | 36        | 0.55%   |
| Serbia       | 33        | 0.5%    |
| Denmark      | 33        | 0.5%    |
| Slovakia     | 28        | 0.43%   |
| China        | 28        | 0.43%   |
| Chile        | 28        | 0.43%   |
| South Africa | 27        | 0.41%   |
| Ukraine      | 26        | 0.4%    |
| Bulgaria     | 26        | 0.4%    |
| Ireland      | 23        | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 128       | 1.95%   |
| St Petersburg     | 56        | 0.85%   |
| Berlin            | 53        | 0.81%   |
| Voronezh          | 49        | 0.75%   |
| Warsaw            | 43        | 0.65%   |
| Madrid            | 40        | 0.61%   |
| Sao Paulo         | 39        | 0.59%   |
| London            | 39        | 0.59%   |
| Paris             | 38        | 0.58%   |
| Sydney            | 37        | 0.56%   |
| Milan             | 37        | 0.56%   |
| Rome              | 36        | 0.55%   |
| Vienna            | 35        | 0.53%   |
| Prague            | 32        | 0.49%   |
| New York          | 30        | 0.46%   |
| Melbourne         | 29        | 0.44%   |
| Hamburg           | 29        | 0.44%   |
| Amsterdam         | 28        | 0.43%   |
| Budapest          | 27        | 0.41%   |
| Munich            | 25        | 0.38%   |
| Frankfurt am Main | 22        | 0.33%   |
| Athens            | 22        | 0.33%   |
| Montreal          | 21        | 0.32%   |
| Novosibirsk       | 20        | 0.3%    |
| Istanbul          | 20        | 0.3%    |
| Helsinki          | 20        | 0.3%    |
| Barcelona         | 20        | 0.3%    |
| Toronto           | 19        | 0.29%   |
| Krasnodar         | 19        | 0.29%   |
| Cologne           | 19        | 0.29%   |
| Belgrade          | 19        | 0.29%   |
| San Jose          | 17        | 0.26%   |
| Mexico City       | 17        | 0.26%   |
| Auckland          | 17        | 0.26%   |
| Stuttgart         | 16        | 0.24%   |
| Seattle           | 16        | 0.24%   |
| Bucharest         | 16        | 0.24%   |
| Rio de Janeiro    | 15        | 0.23%   |
| Jakarta           | 15        | 0.23%   |
| Dublin            | 15        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1525      | 1882   | 15.56%  |
| WDC                         | 1333      | 1632   | 13.6%   |
| Seagate                     | 1201      | 1551   | 12.26%  |
| Kingston                    | 593       | 631    | 6.05%   |
| Sandisk                     | 534       | 574    | 5.45%   |
| Toshiba                     | 514       | 558    | 5.25%   |
| Unknown                     | 417       | 486    | 4.26%   |
| Crucial                     | 406       | 449    | 4.14%   |
| Intel                       | 264       | 301    | 2.69%   |
| SK hynix                    | 260       | 264    | 2.65%   |
| Hitachi                     | 222       | 257    | 2.27%   |
| Micron Technology           | 186       | 194    | 1.9%    |
| HGST                        | 148       | 174    | 1.51%   |
| China                       | 135       | 141    | 1.38%   |
| A-DATA Technology           | 125       | 131    | 1.28%   |
| Phison Electronics          | 115       | 122    | 1.17%   |
| KIOXIA                      | 108       | 110    | 1.1%    |
| Silicon Motion              | 77        | 81     | 0.79%   |
| Kingston Technology Company | 75        | 78     | 0.77%   |
| SPCC                        | 73        | 83     | 0.75%   |
| Unknown                     | 71        | 73     | 0.72%   |
| Apple                       | 68        | 76     | 0.69%   |
| PNY                         | 67        | 71     | 0.68%   |
| Micron/Crucial Technology   | 61        | 62     | 0.62%   |
| Patriot                     | 51        | 52     | 0.52%   |
| Intenso                     | 48        | 55     | 0.49%   |
| Phison                      | 43        | 46     | 0.44%   |
| Apacer                      | 43        | 45     | 0.44%   |
| Netac                       | 41        | 45     | 0.42%   |
| JMicron Technology          | 41        | 41     | 0.42%   |
| GOODRAM                     | 37        | 44     | 0.38%   |
| LITEON                      | 33        | 33     | 0.34%   |
| OCZ                         | 32        | 35     | 0.33%   |
| Maxtor                      | 31        | 33     | 0.32%   |
| Transcend                   | 28        | 28     | 0.29%   |
| Team                        | 28        | 28     | 0.29%   |
| ADATA Technology            | 28        | 29     | 0.29%   |
| Lexar                       | 26        | 26     | 0.27%   |
| Realtek Semiconductor       | 25        | 26     | 0.26%   |
| Gigabyte Technology         | 23        | 24     | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 200       | 1.87%   |
| Kingston SA400S37240G 240GB SSD                       | 146       | 1.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 84        | 0.79%   |
| Kingston SA400S37480G 480GB SSD                       | 83        | 0.78%   |
| Unknown                                               | 71        | 0.66%   |
| Samsung SSD 860 EVO 500GB                             | 70        | 0.66%   |
| Seagate ST1000DM010-2EP102 1TB                        | 66        | 0.62%   |
| Seagate ST2000DM008-2FR102 2TB                        | 61        | 0.57%   |
| Samsung SSD 850 EVO 250GB                             | 57        | 0.53%   |
| Unknown MMC Card  64GB                                | 56        | 0.52%   |
| Seagate ST1000LM035-1RK172 1TB                        | 56        | 0.52%   |
| Seagate ST500DM002-1BD142 500GB                       | 55        | 0.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 54        | 0.51%   |
| Crucial CT500MX500SSD1 500GB                          | 54        | 0.51%   |
| Crucial CT1000MX500SSD1 1TB                           | 54        | 0.51%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1TB        | 53        | 0.5%    |
| Unknown MMC Card  32GB                                | 52        | 0.49%   |
| Kingston SA400S37120G 120GB SSD                       | 52        | 0.49%   |
| Intel SSD 660P Series 512GB                           | 51        | 0.48%   |
| Samsung SSD 850 EVO 500GB                             | 50        | 0.47%   |
| Unknown SD/MMC/MS PRO 2GB                             | 49        | 0.46%   |
| Phison PS5013 E13 NVMe Controller 256GB               | 45        | 0.42%   |
| Crucial CT240BX500SSD1 240GB                          | 45        | 0.42%   |
| Toshiba MQ04ABF100 1TB                                | 44        | 0.41%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 44        | 0.41%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 42        | 0.39%   |
| Samsung SSD 980 1TB                                   | 41        | 0.38%   |
| Toshiba MQ01ABD100 1TB                                | 40        | 0.37%   |
| Unknown MMC Card  128GB                               | 39        | 0.37%   |
| Toshiba DT01ACA100 1TB                                | 38        | 0.36%   |
| Kingston SV300S37A120G 120GB SSD                      | 38        | 0.36%   |
| Samsung SSD 870 EVO 500GB                             | 37        | 0.35%   |
| Toshiba MQ01ABF050 500GB                              | 36        | 0.34%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                    | 36        | 0.34%   |
| Samsung SSD 970 EVO Plus 500GB                        | 36        | 0.34%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 36        | 0.34%   |
| Samsung SSD 860 EVO 250GB                             | 35        | 0.33%   |
| HGST HTS721010A9E630 1TB                              | 32        | 0.3%    |
| Seagate ST500LT012-1DG142 500GB                       | 31        | 0.29%   |
| Phison E12 NVMe Controller 1TB                        | 31        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1178      | 1510   | 35.87%  |
| WDC                 | 1013      | 1244   | 30.85%  |
| Toshiba             | 399       | 435    | 12.15%  |
| Hitachi             | 222       | 257    | 6.76%   |
| HGST                | 148       | 174    | 4.51%   |
| Samsung Electronics | 139       | 158    | 4.23%   |
| Unknown             | 51        | 52     | 1.55%   |
| Maxtor              | 26        | 28     | 0.79%   |
| Apple               | 24        | 24     | 0.73%   |
| Fujitsu             | 21        | 21     | 0.64%   |
| SABRENT             | 10        | 11     | 0.3%    |
| ASMT                | 8         | 9      | 0.24%   |
| USB3.0              | 6         | 6      | 0.18%   |
| Intenso             | 6         | 6      | 0.18%   |
| Hewlett-Packard     | 5         | 9      | 0.15%   |
| HGST HTS            | 4         | 4      | 0.12%   |
| USB                 | 3         | 3      | 0.09%   |
| JMicron Technology  | 2         | 2      | 0.06%   |
| ExcelStor           | 2         | 2      | 0.06%   |
| ASMedia             | 2         | 2      | 0.06%   |
| Unknown             | 2         | 2      | 0.06%   |
| VSTORAGE            | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| SAGE                | 1         | 1      | 0.03%   |
| Phison              | 1         | 1      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| Lenovo              | 1         | 8      | 0.03%   |
| KESU                | 1         | 1      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |
| IBM/Hitachi         | 1         | 1      | 0.03%   |
| HPE                 | 1         | 1      | 0.03%   |
| FreeBSD             | 1         | 1      | 0.03%   |
| Fantom              | 1         | 1      | 0.03%   |
| External            | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 653       | 782    | 19.96%  |
| Kingston            | 462       | 490    | 14.12%  |
| Crucial             | 352       | 391    | 10.76%  |
| SanDisk             | 269       | 281    | 8.22%   |
| WDC                 | 202       | 212    | 6.17%   |
| China               | 134       | 140    | 4.1%    |
| A-DATA Technology   | 96        | 99     | 2.93%   |
| Intel               | 75        | 84     | 2.29%   |
| SPCC                | 66        | 74     | 2.02%   |
| PNY                 | 61        | 65     | 1.86%   |
| Micron Technology   | 53        | 60     | 1.62%   |
| Patriot             | 50        | 51     | 1.53%   |
| SK hynix            | 45        | 45     | 1.38%   |
| Toshiba             | 40        | 40     | 1.22%   |
| Apacer              | 38        | 40     | 1.16%   |
| GOODRAM             | 37        | 42     | 1.13%   |
| Intenso             | 35        | 41     | 1.07%   |
| Apple               | 33        | 33     | 1.01%   |
| OCZ                 | 32        | 35     | 0.98%   |
| Netac               | 32        | 35     | 0.98%   |
| LITEON              | 31        | 31     | 0.95%   |
| Unknown             | 31        | 31     | 0.95%   |
| Transcend           | 26        | 26     | 0.79%   |
| Team                | 23        | 23     | 0.7%    |
| JMicron Technology  | 21        | 21     | 0.64%   |
| Lexar               | 20        | 20     | 0.61%   |
| LITEONIT            | 17        | 17     | 0.52%   |
| Hewlett-Packard     | 15        | 15     | 0.46%   |
| KIOXIA-EXCERIA      | 14        | 14     | 0.43%   |
| XrayDisk            | 12        | 12     | 0.37%   |
| KingDian            | 11        | 12     | 0.34%   |
| Gigabyte Technology | 11        | 11     | 0.34%   |
| TO Exter            | 10        | 10     | 0.31%   |
| Seagate             | 10        | 10     | 0.31%   |
| KingSpec            | 10        | 10     | 0.31%   |
| Emtec               | 9         | 9      | 0.28%   |
| Smartbuy            | 7         | 7      | 0.21%   |
| Plextor             | 7         | 7      | 0.21%   |
| Mushkin             | 7         | 7      | 0.21%   |
| Dogfish             | 7         | 7      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 2831      | 3552   | 32.12%  |
| HDD     | 2777      | 3979   | 31.5%   |
| NVMe    | 2661      | 3106   | 30.19%  |
| MMC     | 390       | 437    | 4.42%   |
| Unknown | 156       | 191    | 1.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4498      | 7196   | 56.51%  |
| NVMe | 2656      | 3098   | 33.37%  |
| SAS  | 415       | 534    | 5.21%   |
| MMC  | 390       | 437    | 4.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3275      | 4239   | 55.86%  |
| 0.51-1.0   | 1694      | 2056   | 28.89%  |
| 1.01-2.0   | 470       | 602    | 8.02%   |
| 3.01-4.0   | 169       | 222    | 2.88%   |
| 4.01-10.0  | 124       | 193    | 2.11%   |
| 2.01-3.0   | 105       | 155    | 1.79%   |
| 10.01-20.0 | 25        | 63     | 0.43%   |
| 0          | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1486      | 22.6%   |
| 251-500        | 1340      | 20.38%  |
| 501-1000       | 948       | 14.42%  |
| 1-20           | 914       | 13.9%   |
| 1001-2000      | 525       | 7.98%   |
| 51-100         | 359       | 5.46%   |
| More than 3000 | 345       | 5.25%   |
| Unknown        | 267       | 4.06%   |
| 21-50          | 201       | 3.06%   |
| 2001-3000      | 191       | 2.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2664      | 40.51%  |
| 21-50          | 980       | 14.9%   |
| 101-250        | 807       | 12.27%  |
| 51-100         | 616       | 9.37%   |
| 251-500        | 501       | 7.62%   |
| 501-1000       | 354       | 5.38%   |
| Unknown        | 267       | 4.06%   |
| 1001-2000      | 194       | 2.95%   |
| More than 3000 | 113       | 1.72%   |
| 2001-3000      | 78        | 1.19%   |
| 0              | 2         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 14        | 14     | 1.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 13        | 13     | 1.69%   |
| Seagate ST9500325AS 500GB             | 9         | 9      | 1.17%   |
| Toshiba MQ01ABF050 500GB              | 8         | 8      | 1.04%   |
| Seagate ST2000DM001-1CH164 2TB        | 8         | 8      | 1.04%   |
| Samsung Electronics SSD 870 EVO 1TB   | 8         | 9      | 1.04%   |
| Unknown                               | 8         | 8      | 1.04%   |
| Toshiba MQ01ABD100 1TB                | 7         | 7      | 0.91%   |
| HGST HTS545050A7E680 500GB            | 7         | 7      | 0.91%   |
| Seagate ST500LT012-1DG142 500GB       | 6         | 6      | 0.78%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 6         | 6      | 0.78%   |
| Seagate ST31000524AS 1TB              | 6         | 6      | 0.78%   |
| Kingston SV300S37A120G 120GB SSD      | 6         | 6      | 0.78%   |
| Seagate ST500LT012-9WS142 500GB       | 5         | 5      | 0.65%   |
| Seagate ST3500413AS 500GB             | 5         | 5      | 0.65%   |
| Seagate ST2000DM008-2FR102 2TB        | 5         | 5      | 0.65%   |
| Seagate ST2000DL003-9VT166 2TB        | 5         | 5      | 0.65%   |
| Kingston SA400S37480G 480GB SSD       | 5         | 5      | 0.65%   |
| HGST HTS721010A9E630 1TB              | 5         | 5      | 0.65%   |
| WDC WD10JPVX-22JC3T0 1TB              | 4         | 4      | 0.52%   |
| Toshiba MQ04ABF100 1TB                | 4         | 4      | 0.52%   |
| Toshiba MQ01ABD075 752GB              | 4         | 4      | 0.52%   |
| Toshiba DT01ACA050 500GB              | 4         | 4      | 0.52%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 4         | 4      | 0.52%   |
| Seagate ST500LM021-1KJ152 500GB       | 4         | 4      | 0.52%   |
| Seagate ST3320613AS 320GB             | 4         | 4      | 0.52%   |
| Seagate ST250DM000-1BD141 250GB       | 4         | 4      | 0.52%   |
| Seagate ST1000DM010-2EP102 1TB        | 4         | 4      | 0.52%   |
| Samsung Electronics SSD 870 EVO 500GB | 4         | 4      | 0.52%   |
| Kingston SA400S37120G 120GB SSD       | 4         | 4      | 0.52%   |
| Hitachi HTS547575A9E384 752GB         | 4         | 4      | 0.52%   |
| HGST HTS725050A7E630 500GB            | 4         | 4      | 0.52%   |
| HGST HTS541010A9E680 1TB              | 4         | 4      | 0.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 3         | 3      | 0.39%   |
| WDC WD5000AAKX-08U6AA0 500GB          | 3         | 3      | 0.39%   |
| WDC WD5000AAKX-001CA0 500GB           | 3         | 3      | 0.39%   |
| WDC WD30EFRX-68EUZN0 3TB              | 3         | 3      | 0.39%   |
| WDC WD10JPVX-60JC3T0 1TB              | 3         | 3      | 0.39%   |
| WDC WD10EZEX-60ZF5A0 1TB              | 3         | 3      | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB              | 3         | 3      | 0.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 207       | 226    | 27.9%   |
| WDC                          | 155       | 167    | 20.89%  |
| Toshiba                      | 63        | 64     | 8.49%   |
| Samsung Electronics          | 50        | 58     | 6.74%   |
| Hitachi                      | 50        | 53     | 6.74%   |
| HGST                         | 30        | 32     | 4.04%   |
| Kingston                     | 27        | 27     | 3.64%   |
| Intel                        | 18        | 18     | 2.43%   |
| SK hynix                     | 14        | 14     | 1.89%   |
| SanDisk                      | 13        | 13     | 1.75%   |
| Crucial                      | 12        | 12     | 1.62%   |
| Maxtor                       | 8         | 9      | 1.08%   |
| China                        | 8         | 8      | 1.08%   |
| Unknown                      | 8         | 8      | 1.08%   |
| A-DATA Technology            | 7         | 7      | 0.94%   |
| OCZ                          | 5         | 5      | 0.67%   |
| Netac                        | 5         | 5      | 0.67%   |
| Fujitsu                      | 5         | 5      | 0.67%   |
| Apple                        | 4         | 4      | 0.54%   |
| XPG                          | 3         | 3      | 0.4%    |
| Patriot                      | 3         | 3      | 0.4%    |
| Initio                       | 3         | 3      | 0.4%    |
| XrayDisk                     | 2         | 2      | 0.27%   |
| USB3.0                       | 2         | 2      | 0.27%   |
| Teclast                      | 2         | 2      | 0.27%   |
| Plextor                      | 2         | 2      | 0.27%   |
| Micron/Crucial Technology    | 2         | 2      | 0.27%   |
| Micron Technology            | 2         | 8      | 0.27%   |
| LITEONIT                     | 2         | 2      | 0.27%   |
| KingSpec                     | 2         | 2      | 0.27%   |
| Hewlett-Packard              | 2         | 2      | 0.27%   |
| ASMT                         | 2         | 2      | 0.27%   |
| Apacer                       | 2         | 2      | 0.27%   |
| Wibtek                       | 1         | 1      | 0.13%   |
| USB                          | 1         | 1      | 0.13%   |
| TwinMOS                      | 1         | 1      | 0.13%   |
| T-FORCE                      | 1         | 1      | 0.13%   |
| SUNEAST                      | 1         | 1      | 0.13%   |
| SPCC                         | 1         | 1      | 0.13%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 207       | 226    | 38.4%   |
| WDC                 | 141       | 152    | 26.16%  |
| Toshiba             | 61        | 62     | 11.32%  |
| Hitachi             | 50        | 53     | 9.28%   |
| HGST                | 30        | 32     | 5.57%   |
| Samsung Electronics | 27        | 31     | 5.01%   |
| Maxtor              | 8         | 9      | 1.48%   |
| Fujitsu             | 5         | 5      | 0.93%   |
| USB3.0              | 2         | 2      | 0.37%   |
| ASMT                | 2         | 2      | 0.37%   |
| Apple               | 2         | 2      | 0.37%   |
| USB                 | 1         | 1      | 0.19%   |
| IBM/Hitachi         | 1         | 1      | 0.19%   |
| Hewlett-Packard     | 1         | 1      | 0.19%   |
| ASMedia             | 1         | 1      | 0.19%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 498       | 580    | 71.14%  |
| SSD  | 167       | 178    | 23.86%  |
| NVMe | 35        | 37     | 5%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)

![Failed Drives](./images/line_chart/drive_failed.svg)

| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD7501AALS-00J7B0 752GB                      | 1         | 1      | 5.56%   |
| WDC WD7500BPVT-22HXZT3 752GB                     | 1         | 1      | 5.56%   |
| WDC WD5000AAKS-00C8A0 500GB                      | 1         | 1      | 5.56%   |
| WDC WD10EARX-22N0YB0 1TB                         | 1         | 1      | 5.56%   |
| Seagate ST9500325AS 500GB                        | 1         | 1      | 5.56%   |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 5.56%   |
| Seagate ST3750640NS 752GB                        | 1         | 1      | 5.56%   |
| Seagate ST31000528AS 1TB                         | 1         | 1      | 5.56%   |
| Seagate ST250DM000-1BD141 250GB                  | 1         | 1      | 5.56%   |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 5.56%   |
| Samsung Electronics MZ7PC128HAFU-000H1 128GB SSD | 1         | 1      | 5.56%   |
| Samsung Electronics HD502HJ 500GB                | 1         | 1      | 5.56%   |
| Samsung Electronics HD103UJ 1TB                  | 1         | 1      | 5.56%   |
| KingDian S400 120GB SSD                          | 1         | 1      | 5.56%   |
| Intel SSDPEKKW256G7 256GB                        | 1         | 1      | 5.56%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 5.56%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 5.56%   |
| HGST HTS725025A7 250GB                           | 1         | 1      | 5.56%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)

![Failed Drive Vendor](./images/line_chart/drive_failed_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 27.78%  |
| WDC                 | 4         | 4      | 22.22%  |
| Samsung Electronics | 4         | 4      | 22.22%  |
| Hitachi             | 2         | 2      | 11.11%  |
| KingDian            | 1         | 1      | 5.56%   |
| Intel               | 1         | 1      | 5.56%   |
| HGST                | 1         | 1      | 5.56%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)

![Drive Status](./images/line_chart/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3346      | 5409   | 46.44%  |
| Detected | 3157      | 5043   | 43.82%  |
| Malfunc  | 684       | 795    | 9.49%   |
| Failed   | 18        | 18     | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4026      | 46.74%  |
| AMD                              | 1437      | 16.68%  |
| Samsung Electronics              | 860       | 9.98%   |
| SanDisk                          | 421       | 4.89%   |
| Kingston Technology Company      | 212       | 2.46%   |
| SK hynix                         | 210       | 2.44%   |
| Phison Electronics               | 186       | 2.16%   |
| Micron Technology                | 134       | 1.56%   |
| ASMedia Technology               | 127       | 1.47%   |
| Micron/Crucial Technology        | 112       | 1.3%    |
| KIOXIA                           | 112       | 1.3%    |
| Silicon Motion                   | 104       | 1.21%   |
| Nvidia                           | 90        | 1.04%   |
| Toshiba America Info Systems     | 84        | 0.98%   |
| JMicron Technology               | 70        | 0.81%   |
| Marvell Technology Group         | 65        | 0.75%   |
| ADATA Technology                 | 55        | 0.64%   |
| Realtek Semiconductor            | 37        | 0.43%   |
| Solid State Storage Technology   | 29        | 0.34%   |
| Union Memory (Shenzhen)          | 25        | 0.29%   |
| LSI Logic / Symbios Logic        | 20        | 0.23%   |
| O2 Micro                         | 19        | 0.22%   |
| MAXIO Technology (Hangzhou)      | 18        | 0.21%   |
| Shenzhen Longsys Electronics     | 15        | 0.17%   |
| VIA Technologies                 | 14        | 0.16%   |
| Hewlett-Packard                  | 14        | 0.16%   |
| Silicon Integrated Systems [SiS] | 13        | 0.15%   |
| Broadcom / LSI                   | 13        | 0.15%   |
| Silicon Image                    | 12        | 0.14%   |
| Seagate Technology               | 11        | 0.13%   |
| Apple                            | 11        | 0.13%   |
| Lite-On Technology               | 10        | 0.12%   |
| INNOGRIT                         | 10        | 0.12%   |
| Netac Technology                 | 6         | 0.07%   |
| Lenovo                           | 4         | 0.05%   |
| Biwin Storage Technology         | 4         | 0.05%   |
| Transcend                        | 3         | 0.03%   |
| Integrated Technology Express    | 3         | 0.03%   |
| Adaptec                          | 3         | 0.03%   |
| Tekram Technology                | 2         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 943       | 9.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 384       | 3.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 273       | 2.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 264       | 2.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 249       | 2.55%   |
| Intel Volume Management Device NVMe RAID Controller                            | 246       | 2.52%   |
| Samsung NVMe SSD Controller 980                                                | 216       | 2.21%   |
| AMD 400 Series Chipset SATA Controller                                         | 203       | 2.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 201       | 2.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 172       | 1.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 159       | 1.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 155       | 1.59%   |
| AMD 500 Series Chipset SATA Controller                                         | 152       | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 140       | 1.43%   |
| Micron Non-Volatile memory controller                                          | 133       | 1.36%   |
| SanDisk Non-Volatile memory controller                                         | 119       | 1.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 119       | 1.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 118       | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 117       | 1.2%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 116       | 1.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 115       | 1.18%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 108       | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 108       | 1.1%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 106       | 1.08%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 101       | 1.03%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 96        | 0.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 93        | 0.95%   |
| Intel Tiger Lake-LP SATA Controller                                            | 92        | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 91        | 0.93%   |
| Kingston Company Company Non-Volatile memory controller                        | 90        | 0.92%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 89        | 0.91%   |
| Intel Comet Lake SATA AHCI Controller                                          | 89        | 0.91%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 88        | 0.9%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 86        | 0.88%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 81        | 0.83%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 81        | 0.83%   |
| Intel SATA Controller [RAID mode]                                              | 80        | 0.82%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 79        | 0.81%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 77        | 0.79%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 77        | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4681      | 54.07%  |
| NVMe | 2658      | 30.7%   |
| IDE  | 668       | 7.72%   |
| RAID | 607       | 7.01%   |
| SAS  | 33        | 0.38%   |
| SCSI | 11        | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 4652      | 70.74%  |
| AMD           | 1871      | 28.45%  |
| ARM           | 45        | 0.68%   |
| CentaurHauls  | 2         | 0.03%   |
| Unknown       | 2         | 0.03%   |
| sifive,u74-mc | 1         | 0.02%   |
| Qualcomm      | 1         | 0.02%   |
| MIPS          | 1         | 0.02%   |
| Loongson      | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 96        | 1.46%   |
| AMD Custom APU 0405                           | 90        | 1.37%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 86        | 1.31%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 63        | 0.96%   |
| AMD Ryzen 5 3600 6-Core Processor             | 60        | 0.91%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 52        | 0.79%   |
| Intel 12th Gen Core i7-12700H                 | 51        | 0.78%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 49        | 0.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 48        | 0.73%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 48        | 0.73%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 47        | 0.71%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 46        | 0.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 45        | 0.68%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 45        | 0.68%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 43        | 0.65%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 42        | 0.64%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 40        | 0.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 35        | 0.53%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 35        | 0.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 34        | 0.52%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 34        | 0.52%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 33        | 0.5%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 33        | 0.5%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 33        | 0.5%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 32        | 0.49%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 32        | 0.49%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 32        | 0.49%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 31        | 0.47%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 31        | 0.47%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 30        | 0.46%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 30        | 0.46%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 30        | 0.46%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 29        | 0.44%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 29        | 0.44%   |
| ARM Processor                                 | 29        | 0.44%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 28        | 0.43%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 27        | 0.41%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 27        | 0.41%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 27        | 0.41%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 26        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1282      | 19.5%   |
| Intel Core i7           | 1004      | 15.27%  |
| Other                   | 805       | 12.24%  |
| AMD Ryzen 5             | 515       | 7.83%   |
| Intel Core i3           | 474       | 7.21%   |
| AMD Ryzen 7             | 414       | 6.3%    |
| Intel Celeron           | 354       | 5.38%   |
| Intel Core 2 Duo        | 215       | 3.27%   |
| Intel Pentium           | 155       | 2.36%   |
| Intel Xeon              | 153       | 2.33%   |
| AMD Ryzen 9             | 126       | 1.92%   |
| Intel Atom              | 84        | 1.28%   |
| AMD FX                  | 84        | 1.28%   |
| AMD Ryzen 3             | 75        | 1.14%   |
| AMD A6                  | 59        | 0.9%    |
| Intel Pentium Dual-Core | 54        | 0.82%   |
| AMD A8                  | 51        | 0.78%   |
| Intel Core 2 Quad       | 40        | 0.61%   |
| AMD A10                 | 39        | 0.59%   |
| Intel Core i9           | 36        | 0.55%   |
| AMD A4                  | 36        | 0.55%   |
| AMD Phenom II X4        | 29        | 0.44%   |
| AMD E1                  | 29        | 0.44%   |
| Intel Pentium Silver    | 28        | 0.43%   |
| AMD Ryzen 7 PRO         | 28        | 0.43%   |
| AMD Ryzen 5 PRO         | 28        | 0.43%   |
| Intel Pentium Dual      | 24        | 0.36%   |
| AMD Athlon II X2        | 22        | 0.33%   |
| Intel Core 2            | 19        | 0.29%   |
| AMD Phenom II X6        | 19        | 0.29%   |
| AMD Athlon 64 X2        | 19        | 0.29%   |
| AMD E                   | 18        | 0.27%   |
| AMD Athlon              | 17        | 0.26%   |
| AMD E2                  | 15        | 0.23%   |
| Intel Pentium 4         | 13        | 0.2%    |
| Intel Pentium Gold      | 11        | 0.17%   |
| ARM BCM                 | 10        | 0.15%   |
| Intel Core m3           | 9         | 0.14%   |
| Intel Pentium M         | 8         | 0.12%   |
| Intel Genuine           | 8         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2315      | 35.2%   |
| 4       | 2281      | 34.69%  |
| 6       | 802       | 12.2%   |
| 8       | 637       | 9.69%   |
| 12      | 149       | 2.27%   |
| 1       | 110       | 1.67%   |
| 14      | 80        | 1.22%   |
| 16      | 66        | 1%      |
| 10      | 60        | 0.91%   |
| 3       | 34        | 0.52%   |
| Unknown | 11        | 0.17%   |
| 24      | 9         | 0.14%   |
| 20      | 5         | 0.08%   |
| 28      | 4         | 0.06%   |
| 48      | 3         | 0.05%   |
| 32      | 3         | 0.05%   |
| 36      | 2         | 0.03%   |
| 18      | 2         | 0.03%   |
| 64      | 1         | 0.02%   |
| 56      | 1         | 0.02%   |
| 40      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 6501      | 98.86%  |
| 2       | 61        | 0.93%   |
| Unknown | 11        | 0.17%   |
| 3       | 3         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4573      | 69.54%  |
| 1       | 1976      | 30.05%  |
| 4       | 12        | 0.18%   |
| Unknown | 11        | 0.17%   |
| 8       | 3         | 0.05%   |
| 12      | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6522      | 99.18%  |
| 32-bit         | 23        | 0.35%   |
| Unknown        | 23        | 0.35%   |
| 64-bit         | 8         | 0.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1763      | 26.81%  |
| 0x306a9    | 307       | 4.67%   |
| 0x206a7    | 270       | 4.11%   |
| 0x306c3    | 233       | 3.54%   |
| 0x806c1    | 210       | 3.19%   |
| 0x1067a    | 165       | 2.51%   |
| 0x906ea    | 141       | 2.14%   |
| 0x506e3    | 122       | 1.86%   |
| 0x806ea    | 117       | 1.78%   |
| 0x806ec    | 113       | 1.72%   |
| 0x0a50000c | 112       | 1.7%    |
| 0x806e9    | 109       | 1.66%   |
| 0x08701021 | 109       | 1.66%   |
| 0x40651    | 105       | 1.6%    |
| 0x906a3    | 97        | 1.48%   |
| 0x906e9    | 95        | 1.44%   |
| 0x406e3    | 95        | 1.44%   |
| 0x306d4    | 84        | 1.28%   |
| 0x20655    | 82        | 1.25%   |
| 0x706a8    | 74        | 1.13%   |
| 0x08108109 | 73        | 1.11%   |
| 0x08608103 | 70        | 1.06%   |
| 0x0a50000d | 60        | 0.91%   |
| 0x30678    | 56        | 0.85%   |
| 0x08600106 | 54        | 0.82%   |
| 0x6fd      | 53        | 0.81%   |
| 0xa0652    | 51        | 0.78%   |
| 0x0800820d | 51        | 0.78%   |
| 0x406c4    | 48        | 0.73%   |
| 0xa0653    | 44        | 0.67%   |
| 0x706e5    | 44        | 0.67%   |
| 0x906c0    | 43        | 0.65%   |
| 0x10676    | 41        | 0.62%   |
| 0x90672    | 40        | 0.61%   |
| 0x0a201016 | 40        | 0.61%   |
| 0x906ed    | 36        | 0.55%   |
| 0x706a1    | 36        | 0.55%   |
| 0x0a20120a | 36        | 0.55%   |
| 0xa0671    | 35        | 0.53%   |
| 0x806d1    | 35        | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 916       | 13.93%  |
| Haswell          | 500       | 7.6%    |
| Unknown          | 462       | 7.03%   |
| IvyBridge        | 447       | 6.8%    |
| SandyBridge      | 394       | 5.99%   |
| Zen 3            | 381       | 5.79%   |
| Skylake          | 320       | 4.87%   |
| Zen 2            | 304       | 4.62%   |
| TigerLake        | 278       | 4.23%   |
| Penryn           | 251       | 3.82%   |
| Zen+             | 229       | 3.48%   |
| Alderlake Hybrid | 193       | 2.93%   |
| Silvermont       | 181       | 2.75%   |
| CometLake        | 171       | 2.6%    |
| Westmere         | 151       | 2.3%    |
| Broadwell        | 134       | 2.04%   |
| Goldmont plus    | 133       | 2.02%   |
| Core             | 126       | 1.92%   |
| Piledriver       | 125       | 1.9%    |
| Icelake          | 125       | 1.9%    |
| Zen              | 114       | 1.73%   |
| K10              | 112       | 1.7%    |
| Excavator        | 84        | 1.28%   |
| Nehalem          | 54        | 0.82%   |
| Tremont          | 44        | 0.67%   |
| Goldmont         | 44        | 0.67%   |
| Bobcat           | 43        | 0.65%   |
| Jaguar           | 39        | 0.59%   |
| K8 Hammer        | 37        | 0.56%   |
| Puma             | 35        | 0.53%   |
| Bonnell          | 35        | 0.53%   |
| Steamroller      | 31        | 0.47%   |
| K10 Llano        | 27        | 0.41%   |
| NetBurst         | 21        | 0.32%   |
| Bulldozer        | 13        | 0.2%    |
| P6               | 11        | 0.17%   |
| K8 & K10 hybrid  | 10        | 0.15%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3647      | 47.37%  |
| Nvidia                                       | 2052      | 26.65%  |
| AMD                                          | 1933      | 25.11%  |
| Matrox Electronics Systems                   | 35        | 0.45%   |
| ASPEED Technology                            | 20        | 0.26%   |
| Silicon Integrated Systems [SiS]             | 5         | 0.06%   |
| VIA Technologies                             | 3         | 0.04%   |
| Zhaoxin                                      | 1         | 0.01%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| Loongson Technology                          | 1         | 0.01%   |
| ATI Technologies                             | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 291       | 3.68%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 239       | 3.02%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 222       | 2.81%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 172       | 2.17%   |
| Intel UHD Graphics 620                                                                   | 146       | 1.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 142       | 1.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 135       | 1.71%   |
| Intel HD Graphics 620                                                                    | 128       | 1.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 123       | 1.55%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 122       | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 120       | 1.52%   |
| AMD Renoir                                                                               | 120       | 1.52%   |
| Intel HD Graphics 530                                                                    | 116       | 1.47%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 114       | 1.44%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 113       | 1.43%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 111       | 1.4%    |
| AMD Lucienne                                                                             | 109       | 1.38%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 96        | 1.21%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 96        | 1.21%   |
| Intel Core Processor Integrated Graphics Controller                                      | 94        | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 90        | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 90        | 1.14%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 90        | 1.14%   |
| Intel HD Graphics 5500                                                                   | 85        | 1.07%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 84        | 1.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 82        | 1.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 77        | 0.97%   |
| Intel HD Graphics 630                                                                    | 73        | 0.92%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 68        | 0.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 68        | 0.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 66        | 0.83%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 61        | 0.77%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 58        | 0.73%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 55        | 0.7%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 53        | 0.67%   |
| AMD Rembrandt [Radeon 680M]                                                              | 50        | 0.63%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 49        | 0.62%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 49        | 0.62%   |
| Intel JasperLake [UHD Graphics]                                                          | 48        | 0.61%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 47        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 2576      | 39.17%  |
| 1 x AMD                 | 1496      | 22.75%  |
| 1 x Nvidia              | 1081      | 16.44%  |
| Intel + Nvidia          | 791       | 12.03%  |
| Intel + AMD             | 153       | 2.33%   |
| AMD + Nvidia            | 145       | 2.2%    |
| 2 x AMD                 | 132       | 2.01%   |
| Other                   | 57        | 0.87%   |
| 2 x Intel               | 57        | 0.87%   |
| 1 x Matrox              | 31        | 0.47%   |
| 2 x Nvidia              | 17        | 0.26%   |
| 1 x ASPEED              | 15        | 0.23%   |
| 1 x SiS                 | 5         | 0.08%   |
| 1 x VIA                 | 3         | 0.05%   |
| Nvidia + Matrox         | 3         | 0.05%   |
| Nvidia + ASPEED         | 3         | 0.05%   |
| Intel + 2 x Nvidia      | 3         | 0.05%   |
| 4 x Nvidia              | 1         | 0.02%   |
| 3 x AMD                 | 1         | 0.02%   |
| 1 x Zhaoxin             | 1         | 0.02%   |
| 1 x Loongson Technology | 1         | 0.02%   |
| Intel + ASPEED          | 1         | 0.02%   |
| AMD + XGI               | 1         | 0.02%   |
| AMD + Matrox            | 1         | 0.02%   |
| AMD + ASPEED            | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 5402      | 82.15%  |
| Proprietary | 927       | 14.1%   |
| Unknown     | 247       | 3.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4064      | 61.8%   |
| 0.01-0.5   | 642       | 9.76%   |
| 1.01-2.0   | 576       | 8.76%   |
| 0.51-1.0   | 363       | 5.52%   |
| 3.01-4.0   | 342       | 5.2%    |
| 7.01-8.0   | 257       | 3.91%   |
| 5.01-6.0   | 141       | 2.14%   |
| 8.01-16.0  | 122       | 1.86%   |
| 2.01-3.0   | 49        | 0.75%   |
| 16.01-24.0 | 17        | 0.26%   |
| 4.01-5.0   | 3         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 790       | 11.23%  |
| AU Optronics            | 779       | 11.07%  |
| BOE                     | 647       | 9.19%   |
| Chimei Innolux          | 606       | 8.61%   |
| LG Display              | 551       | 7.83%   |
| Goldstar                | 413       | 5.87%   |
| Dell                    | 381       | 5.41%   |
| Acer                    | 258       | 3.67%   |
| Hewlett-Packard         | 256       | 3.64%   |
| AOC                     | 164       | 2.33%   |
| Philips                 | 148       | 2.1%    |
| Lenovo                  | 145       | 2.06%   |
| BenQ                    | 136       | 1.93%   |
| Ancor Communications    | 133       | 1.89%   |
| Sharp                   | 125       | 1.78%   |
| Apple                   | 117       | 1.66%   |
| Chi Mei Optoelectronics | 99        | 1.41%   |
| ASUSTek Computer        | 95        | 1.35%   |
| Valve                   | 85        | 1.21%   |
| ViewSonic               | 84        | 1.19%   |
| PANDA                   | 82        | 1.17%   |
| InfoVision              | 68        | 0.97%   |
| Iiyama                  | 61        | 0.87%   |
| Sony                    | 49        | 0.7%    |
| CSO                     | 32        | 0.45%   |
| LG Philips              | 30        | 0.43%   |
| Eizo                    | 29        | 0.41%   |
| MSI                     | 28        | 0.4%    |
| Panasonic               | 25        | 0.36%   |
| NEC Computers           | 24        | 0.34%   |
| HannStar                | 22        | 0.31%   |
| Gigabyte Technology     | 21        | 0.3%    |
| Vizio                   | 20        | 0.28%   |
| Toshiba                 | 19        | 0.27%   |
| Unknown                 | 17        | 0.24%   |
| TMX                     | 17        | 0.24%   |
| Sceptre Tech            | 17        | 0.24%   |
| CPT                     | 17        | 0.24%   |
| HUAWEI                  | 16        | 0.23%   |
| Mi                      | 15        | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 85        | 1.18%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 30        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 29        | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 29        | 0.4%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 26        | 0.36%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 22        | 0.31%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 22        | 0.31%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 21        | 0.29%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 20        | 0.28%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 20        | 0.28%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 19        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 19        | 0.26%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                       | 19        | 0.26%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 17        | 0.24%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch              | 17        | 0.24%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 16        | 0.22%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 15        | 0.21%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 15        | 0.21%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 15        | 0.21%   |
| Unknown                                                                  | 15        | 0.21%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                    | 14        | 0.19%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 14        | 0.19%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 14        | 0.19%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 14        | 0.19%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch    | 13        | 0.18%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                  | 13        | 0.18%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 13        | 0.18%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 13        | 0.18%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 13        | 0.18%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                         | 13        | 0.18%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 12        | 0.17%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch         | 12        | 0.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 12        | 0.17%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                    | 12        | 0.17%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 12        | 0.17%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 12        | 0.17%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 12        | 0.17%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 11        | 0.15%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 11        | 0.15%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 11        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3072      | 45.52%  |
| 1366x768 (WXGA)    | 1127      | 16.7%   |
| 3840x2160 (4K)     | 452       | 6.7%    |
| 2560x1440 (QHD)    | 354       | 5.25%   |
| 1600x900 (HD+)     | 261       | 3.87%   |
| 1280x1024 (SXGA)   | 189       | 2.8%    |
| 1920x1200 (WUXGA)  | 157       | 2.33%   |
| 1680x1050 (WSXGA+) | 154       | 2.28%   |
| 1440x900 (WXGA+)   | 126       | 1.87%   |
| 1280x800 (WXGA)    | 117       | 1.73%   |
| 2560x1600          | 93        | 1.38%   |
| 800x1280           | 90        | 1.33%   |
| 3440x1440          | 89        | 1.32%   |
| 2560x1080          | 67        | 0.99%   |
| 2880x1800          | 39        | 0.58%   |
| 1360x768           | 37        | 0.55%   |
| 2160x1440          | 27        | 0.4%    |
| 1920x540           | 27        | 0.4%    |
| Unknown            | 25        | 0.37%   |
| 3840x2400          | 24        | 0.36%   |
| 1024x768 (XGA)     | 23        | 0.34%   |
| 3840x1080          | 19        | 0.28%   |
| 1024x600           | 17        | 0.25%   |
| 2288x1287          | 12        | 0.18%   |
| 1600x1200          | 12        | 0.18%   |
| 2736x1824          | 11        | 0.16%   |
| 3200x1800 (QHD+)   | 9         | 0.13%   |
| 1920x1280          | 9         | 0.13%   |
| 1280x720 (HD)      | 9         | 0.13%   |
| 3200x2000          | 7         | 0.1%    |
| 2256x1504          | 7         | 0.1%    |
| 3840x1600          | 6         | 0.09%   |
| 3000x2000          | 6         | 0.09%   |
| 1800x1200          | 6         | 0.09%   |
| 3456x2160          | 5         | 0.07%   |
| 3360x1080          | 5         | 0.07%   |
| 2880x1620          | 5         | 0.07%   |
| 2240x1400          | 5         | 0.07%   |
| 5760x1080          | 4         | 0.06%   |
| 3840x1200          | 4         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1732      | 24.63%  |
| 27      | 591       | 8.4%    |
| 13      | 583       | 8.29%   |
| 14      | 552       | 7.85%   |
| 24      | 504       | 7.17%   |
| 23      | 470       | 6.68%   |
| 17      | 399       | 5.67%   |
| 21      | 368       | 5.23%   |
| 31      | 190       | 2.7%    |
| 19      | 176       | 2.5%    |
| Unknown | 153       | 2.18%   |
| 34      | 123       | 1.75%   |
| 18      | 119       | 1.69%   |
| 12      | 114       | 1.62%   |
| 20      | 108       | 1.54%   |
| 22      | 96        | 1.36%   |
| 11      | 91        | 1.29%   |
| 16      | 87        | 1.24%   |
| 7       | 85        | 1.21%   |
| 84      | 64        | 0.91%   |
| 10      | 43        | 0.61%   |
| 72      | 40        | 0.57%   |
| 32      | 40        | 0.57%   |
| 40      | 38        | 0.54%   |
| 54      | 29        | 0.41%   |
| 25      | 28        | 0.4%    |
| 26      | 23        | 0.33%   |
| 28      | 20        | 0.28%   |
| 52      | 14        | 0.2%    |
| 48      | 14        | 0.2%    |
| 29      | 14        | 0.2%    |
| 46      | 12        | 0.17%   |
| 49      | 9         | 0.13%   |
| 42      | 9         | 0.13%   |
| 37      | 9         | 0.13%   |
| 35      | 9         | 0.13%   |
| 142     | 8         | 0.11%   |
| 65      | 8         | 0.11%   |
| 36      | 8         | 0.11%   |
| 47      | 7         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2657      | 38.4%   |
| 501-600        | 1456      | 21.04%  |
| 401-500        | 764       | 11.04%  |
| 201-300        | 553       | 7.99%   |
| 351-400        | 485       | 7.01%   |
| 601-700        | 282       | 4.08%   |
| 701-800        | 174       | 2.51%   |
| Unknown        | 153       | 2.21%   |
| 1501-2000      | 111       | 1.6%    |
| 1001-1500      | 107       | 1.55%   |
| 1-100          | 85        | 1.23%   |
| 801-900        | 65        | 0.94%   |
| 901-1000       | 19        | 0.27%   |
| More than 2000 | 8         | 0.12%   |
| 101-200        | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4945      | 77.04%  |
| 16/10   | 758       | 11.81%  |
| 5/4     | 178       | 2.77%   |
| 21/9    | 159       | 2.48%   |
| Unknown | 100       | 1.56%   |
| 3/2     | 89        | 1.39%   |
| 0.67    | 85        | 1.32%   |
| 4/3     | 51        | 0.79%   |
| 32/9    | 25        | 0.39%   |
| 6/5     | 9         | 0.14%   |
| 1.00    | 8         | 0.12%   |
| 0.62    | 6         | 0.09%   |
| 0.89    | 2         | 0.03%   |
| 3.33    | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 2.65    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1741      | 24.98%  |
| 201-250        | 1118      | 16.04%  |
| 81-90          | 895       | 12.84%  |
| 301-350        | 614       | 8.81%   |
| 151-200        | 400       | 5.74%   |
| 351-500        | 377       | 5.41%   |
| 121-130        | 283       | 4.06%   |
| 71-80          | 247       | 3.54%   |
| 251-300        | 211       | 3.03%   |
| More than 1000 | 191       | 2.74%   |
| 141-150        | 184       | 2.64%   |
| Unknown        | 153       | 2.2%    |
| 501-1000       | 114       | 1.64%   |
| 51-60          | 97        | 1.39%   |
| 61-70          | 94        | 1.35%   |
| 1-40           | 86        | 1.23%   |
| 111-120        | 72        | 1.03%   |
| 131-140        | 41        | 0.59%   |
| 41-50          | 37        | 0.53%   |
| 91-100         | 15        | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2249      | 32.98%  |
| 121-160       | 1851      | 27.14%  |
| 101-120       | 1685      | 24.71%  |
| 161-240       | 567       | 8.32%   |
| More than 240 | 160       | 2.35%   |
| 1-50          | 154       | 2.26%   |
| Unknown       | 153       | 2.24%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5268      | 80.11%  |
| 2     | 929       | 14.13%  |
| 0     | 276       | 4.2%    |
| 3     | 96        | 1.46%   |
| 4     | 5         | 0.08%   |
| 5     | 2         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3716      | 38.39%  |
| Intel                             | 3095      | 31.98%  |
| Qualcomm Atheros                  | 938       | 9.69%   |
| Broadcom                          | 510       | 5.27%   |
| MediaTek                          | 191       | 1.97%   |
| Broadcom Limited                  | 116       | 1.2%    |
| TP-Link                           | 108       | 1.12%   |
| Ralink Technology                 | 106       | 1.1%    |
| Marvell Technology Group          | 83        | 0.86%   |
| Ralink                            | 80        | 0.83%   |
| Nvidia                            | 71        | 0.73%   |
| ASIX Electronics                  | 68        | 0.7%    |
| Samsung Electronics               | 45        | 0.46%   |
| Xiaomi                            | 31        | 0.32%   |
| Sierra Wireless                   | 27        | 0.28%   |
| Qualcomm                          | 24        | 0.25%   |
| Qualcomm Atheros Communications   | 23        | 0.24%   |
| Huawei Technologies               | 23        | 0.24%   |
| DisplayLink                       | 22        | 0.23%   |
| Dell                              | 22        | 0.23%   |
| NetGear                           | 20        | 0.21%   |
| Lenovo                            | 19        | 0.2%    |
| ASUSTek Computer                  | 19        | 0.2%    |
| Microsoft                         | 18        | 0.19%   |
| Aquantia                          | 18        | 0.19%   |
| D-Link                            | 16        | 0.17%   |
| JMicron Technology                | 15        | 0.15%   |
| D-Link System                     | 14        | 0.14%   |
| Ericsson Business Mobile Networks | 13        | 0.13%   |
| OPPO Electronics                  | 12        | 0.12%   |
| Edimax Technology                 | 11        | 0.11%   |
| Linksys                           | 10        | 0.1%    |
| Hewlett-Packard                   | 10        | 0.1%    |
| Google                            | 10        | 0.1%    |
| Belkin Components                 | 10        | 0.1%    |
| Apple                             | 10        | 0.1%    |
| Silicon Integrated Systems [SiS]  | 9         | 0.09%   |
| Motorola PCS                      | 9         | 0.09%   |
| Fibocom                           | 9         | 0.09%   |
| VIA Technologies                  | 8         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2427      | 21.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 331       | 2.91%   |
| Intel Wi-Fi 6 AX200                                               | 284       | 2.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 237       | 2.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 215       | 1.89%   |
| Intel Wi-Fi 6 AX201                                               | 211       | 1.86%   |
| Realtek RTL8125 2.5GbE Controller                                 | 201       | 1.77%   |
| Intel Wireless 8265 / 8275                                        | 196       | 1.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 192       | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 167       | 1.47%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 144       | 1.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 143       | 1.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 135       | 1.19%   |
| Intel Wireless 7265                                               | 130       | 1.14%   |
| Intel I211 Gigabit Network Connection                             | 128       | 1.13%   |
| Intel Ethernet Controller I225-V                                  | 127       | 1.12%   |
| Intel Wireless 7260                                               | 120       | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 115       | 1.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 113       | 0.99%   |
| Intel Wireless 8260                                               | 106       | 0.93%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 97        | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 92        | 0.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 90        | 0.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 90        | 0.79%   |
| Intel Wireless 3165                                               | 87        | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 87        | 0.77%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 81        | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 78        | 0.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 76        | 0.67%   |
| Intel Ethernet Connection (2) I219-V                              | 74        | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 73        | 0.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 73        | 0.64%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 70        | 0.62%   |
| Intel Ethernet Connection (7) I219-V                              | 61        | 0.54%   |
| Intel Ethernet Connection (4) I219-LM                             | 59        | 0.52%   |
| ASIX AX88179 Gigabit Ethernet                                     | 59        | 0.52%   |
| Intel Wireless-AC 9260                                            | 55        | 0.48%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 53        | 0.47%   |
| Realtek 802.11ac NIC                                              | 53        | 0.47%   |
| Intel Ethernet Connection (2) I219-LM                             | 53        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2386      | 45.13%  |
| Realtek Semiconductor                 | 1040      | 19.67%  |
| Qualcomm Atheros                      | 762       | 14.41%  |
| Broadcom                              | 332       | 6.28%   |
| MediaTek                              | 182       | 3.44%   |
| Ralink Technology                     | 106       | 2%      |
| TP-Link                               | 98        | 1.85%   |
| Ralink                                | 80        | 1.51%   |
| Broadcom Limited                      | 66        | 1.25%   |
| Sierra Wireless                       | 27        | 0.51%   |
| Qualcomm Atheros Communications       | 23        | 0.44%   |
| NetGear                               | 19        | 0.36%   |
| ASUSTek Computer                      | 19        | 0.36%   |
| Qualcomm                              | 16        | 0.3%    |
| Microsoft                             | 15        | 0.28%   |
| D-Link                                | 15        | 0.28%   |
| Dell                                  | 12        | 0.23%   |
| Edimax Technology                     | 11        | 0.21%   |
| Marvell Technology Group              | 10        | 0.19%   |
| Belkin Components                     | 10        | 0.19%   |
| Fibocom                               | 9         | 0.17%   |
| D-Link System                         | 9         | 0.17%   |
| Linksys                               | 8         | 0.15%   |
| IMC Networks                          | 5         | 0.09%   |
| AVM                                   | 5         | 0.09%   |
| Mercucys                              | 4         | 0.08%   |
| Gemtek                                | 4         | 0.08%   |
| ZyDAS                                 | 2         | 0.04%   |
| Sitecom Europe                        | 2         | 0.04%   |
| Ericsson Business Mobile Networks     | 2         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.04%   |
| Texas Instruments                     | 1         | 0.02%   |
| Qcom                                  | 1         | 0.02%   |
| LSI                                   | 1         | 0.02%   |
| Elecom                                | 1         | 0.02%   |
| Belkin                                | 1         | 0.02%   |
| AboCom Systems                        | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 284       | 5.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 237       | 4.45%   |
| Intel Wi-Fi 6 AX201                                            | 211       | 3.97%   |
| Intel Wireless 8265 / 8275                                     | 196       | 3.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 167       | 3.14%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 144       | 2.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 143       | 2.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 135       | 2.54%   |
| Intel Wireless 7265                                            | 130       | 2.44%   |
| Intel Wireless 7260                                            | 120       | 2.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 115       | 2.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 113       | 2.12%   |
| Intel Wireless 8260                                            | 106       | 1.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 97        | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 92        | 1.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 90        | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 90        | 1.69%   |
| Intel Wireless 3165                                            | 87        | 1.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 87        | 1.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 81        | 1.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 76        | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 73        | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 73        | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 70        | 1.32%   |
| Intel Wireless-AC 9260                                         | 55        | 1.03%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 53        | 1%      |
| Realtek 802.11ac NIC                                           | 53        | 1%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 52        | 0.98%   |
| Ralink MT7601U Wireless Adapter                                | 51        | 0.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 48        | 0.9%    |
| Broadcom BCM43142 802.11b/g/n                                  | 47        | 0.88%   |
| Intel Wireless 3160                                            | 41        | 0.77%   |
| Realtek Realtek Network controller                             | 40        | 0.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 39        | 0.73%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 39        | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 38        | 0.71%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 38        | 0.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 37        | 0.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 36        | 0.68%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 36        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 3219      | 55.18%  |
| Intel                            | 1515      | 25.97%  |
| Qualcomm Atheros                 | 262       | 4.49%   |
| Broadcom                         | 258       | 4.42%   |
| Marvell Technology Group         | 74        | 1.27%   |
| Nvidia                           | 71        | 1.22%   |
| ASIX Electronics                 | 68        | 1.17%   |
| Broadcom Limited                 | 50        | 0.86%   |
| Samsung Electronics              | 44        | 0.75%   |
| Xiaomi                           | 31        | 0.53%   |
| DisplayLink                      | 22        | 0.38%   |
| Lenovo                           | 18        | 0.31%   |
| Huawei Technologies              | 18        | 0.31%   |
| Aquantia                         | 18        | 0.31%   |
| JMicron Technology               | 15        | 0.26%   |
| OPPO Electronics                 | 12        | 0.21%   |
| TP-Link                          | 10        | 0.17%   |
| Apple                            | 10        | 0.17%   |
| MediaTek                         | 9         | 0.15%   |
| Google                           | 9         | 0.15%   |
| VIA Technologies                 | 8         | 0.14%   |
| Silicon Integrated Systems [SiS] | 8         | 0.14%   |
| Qualcomm                         | 8         | 0.14%   |
| Motorola PCS                     | 6         | 0.1%    |
| Microchip Technology             | 6         | 0.1%    |
| ZTE WCDMA Technologies MSM       | 5         | 0.09%   |
| OnePlus Technology (Shenzhen)    | 5         | 0.09%   |
| Hewlett-Packard                  | 5         | 0.09%   |
| D-Link System                    | 5         | 0.09%   |
| American Megatrends              | 5         | 0.09%   |
| Insyde Software                  | 4         | 0.07%   |
| ICS Advent                       | 4         | 0.07%   |
| 3Com                             | 4         | 0.07%   |
| Microsoft                        | 3         | 0.05%   |
| Attansic Technology              | 3         | 0.05%   |
| Mellanox Technologies            | 2         | 0.03%   |
| Linksys                          | 2         | 0.03%   |
| Dell                             | 2         | 0.03%   |
| ZyXEL Communications             | 1         | 0.02%   |
| SysKonnect                       | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2427      | 40.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 331       | 5.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 215       | 3.61%   |
| Realtek RTL8125 2.5GbE Controller                                 | 201       | 3.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 192       | 3.22%   |
| Intel I211 Gigabit Network Connection                             | 128       | 2.15%   |
| Intel Ethernet Controller I225-V                                  | 127       | 2.13%   |
| Intel Ethernet Connection I217-LM                                 | 78        | 1.31%   |
| Intel Ethernet Connection (2) I219-V                              | 74        | 1.24%   |
| Intel Ethernet Connection (7) I219-V                              | 61        | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 59        | 0.99%   |
| ASIX AX88179 Gigabit Ethernet                                     | 59        | 0.99%   |
| Intel Ethernet Connection (2) I219-LM                             | 53        | 0.89%   |
| Intel Ethernet Connection I219-LM                                 | 49        | 0.82%   |
| Intel Ethernet Connection I217-V                                  | 40        | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 38        | 0.64%   |
| Intel 82579V Gigabit Network Connection                           | 38        | 0.64%   |
| Intel Ethernet Connection I218-LM                                 | 35        | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 34        | 0.57%   |
| Intel Ethernet Connection (2) I218-V                              | 33        | 0.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 31        | 0.52%   |
| Intel Ethernet Connection (4) I219-V                              | 31        | 0.52%   |
| Intel 82577LM Gigabit Network Connection                          | 30        | 0.5%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 30        | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 28        | 0.47%   |
| Intel Ethernet Connection (7) I219-LM                             | 28        | 0.47%   |
| Intel Ethernet Connection (10) I219-V                             | 28        | 0.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 28        | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 27        | 0.45%   |
| Intel I210 Gigabit Network Connection                             | 27        | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 26        | 0.44%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 26        | 0.44%   |
| Nvidia MCP79 Ethernet                                             | 26        | 0.44%   |
| Intel Ethernet Connection (13) I219-V                             | 25        | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 24        | 0.4%    |
| Intel Ethernet Connection (5) I219-LM                             | 24        | 0.4%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 24        | 0.4%    |
| Nvidia MCP61 Ethernet                                             | 23        | 0.39%   |
| Intel 82574L Gigabit Network Connection                           | 23        | 0.39%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 23        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5486      | 51.72%  |
| WiFi     | 5041      | 47.52%  |
| Modem    | 65        | 0.61%   |
| Unknown  | 16        | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3748      | 56.03%  |
| Ethernet | 2940      | 43.95%  |
| Unknown  | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3419      | 51.99%  |
| 1     | 2851      | 43.35%  |
| 0     | 127       | 1.93%   |
| 3     | 119       | 1.81%   |
| 4     | 43        | 0.65%   |
| 6     | 7         | 0.11%   |
| 5     | 5         | 0.08%   |
| 8     | 3         | 0.05%   |
| 42    | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4599      | 69.94%  |
| Yes  | 1977      | 30.06%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2004      | 47.76%  |
| Realtek Semiconductor           | 476       | 11.34%  |
| Qualcomm Atheros Communications | 284       | 6.77%   |
| IMC Networks                    | 275       | 6.55%   |
| Cambridge Silicon Radio         | 219       | 5.22%   |
| Broadcom                        | 170       | 4.05%   |
| Lite-On Technology              | 143       | 3.41%   |
| Apple                           | 138       | 3.29%   |
| Foxconn / Hon Hai               | 129       | 3.07%   |
| ASUSTek Computer                | 61        | 1.45%   |
| MediaTek                        | 45        | 1.07%   |
| Hewlett-Packard                 | 40        | 0.95%   |
| Dell                            | 32        | 0.76%   |
| TP-Link                         | 29        | 0.69%   |
| Realtek                         | 29        | 0.69%   |
| Toshiba                         | 27        | 0.64%   |
| Ralink                          | 20        | 0.48%   |
| Foxconn International           | 10        | 0.24%   |
| Alps Electric                   | 9         | 0.21%   |
| Marvell Semiconductor           | 8         | 0.19%   |
| Opticis                         | 7         | 0.17%   |
| USI                             | 5         | 0.12%   |
| Edimax Technology               | 5         | 0.12%   |
| Belkin Components               | 5         | 0.12%   |
| Integrated System Solution      | 4         | 0.1%    |
| Taiyo Yuden                     | 3         | 0.07%   |
| Dynex                           | 3         | 0.07%   |
| Askey Computer                  | 3         | 0.07%   |
| Micro Star International        | 2         | 0.05%   |
| Chicony Electronics             | 2         | 0.05%   |
| Sitecom Europe                  | 1         | 0.02%   |
| SINO WEALTH                     | 1         | 0.02%   |
| SIN                             | 1         | 0.02%   |
| Ralink Technology               | 1         | 0.02%   |
| Nintendo                        | 1         | 0.02%   |
| Motorola PCS                    | 1         | 0.02%   |
| Creative Technology             | 1         | 0.02%   |
| 3Com                            | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 664       | 15.8%   |
| Intel Bluetooth Device                              | 529       | 12.59%  |
| Realtek Bluetooth Radio                             | 345       | 8.21%   |
| Intel AX200 Bluetooth                               | 265       | 6.31%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 260       | 6.19%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 219       | 5.21%   |
| IMC Networks Bluetooth Radio                        | 160       | 3.81%   |
| Qualcomm Atheros  Bluetooth Device                  | 142       | 3.38%   |
| Intel AX210 Bluetooth                               | 89        | 2.12%   |
| Intel Wireless-AC 3168 Bluetooth                    | 86        | 2.05%   |
| Realtek  Bluetooth 4.2 Adapter                      | 80        | 1.9%    |
| Lite-On Bluetooth Device                            | 67        | 1.59%   |
| Apple Bluetooth Host Controller                     | 57        | 1.36%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 52        | 1.24%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 52        | 1.24%   |
| IMC Networks Wireless_Device                        | 52        | 1.24%   |
| Foxconn / Hon Hai Wireless_Device                   | 51        | 1.21%   |
| Apple Bluetooth USB Host Controller                 | 49        | 1.17%   |
| MediaTek Wireless_Device                            | 44        | 1.05%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 39        | 0.93%   |
| Foxconn / Hon Hai Bluetooth Device                  | 39        | 0.93%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 38        | 0.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 35        | 0.83%   |
| Lite-On Atheros AR3012 Bluetooth                    | 32        | 0.76%   |
| IMC Networks Bluetooth Device                       | 31        | 0.74%   |
| TP-Link TPuLink UB500 Adapter                       | 29        | 0.69%   |
| Realtek Bluetooth Radio                             | 29        | 0.69%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 26        | 0.62%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 24        | 0.57%   |
| HP Broadcom 2070 Bluetooth Combo                    | 21        | 0.5%    |
| Ralink RT3290 Bluetooth                             | 20        | 0.48%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 20        | 0.48%   |
| Realtek RTL8723B Bluetooth                          | 19        | 0.45%   |
| Lite-On Wireless_Device                             | 19        | 0.45%   |
| Realtek RTL8821A Bluetooth                          | 18        | 0.43%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 18        | 0.43%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 18        | 0.43%   |
| Broadcom BCM2045B (BDC-2.1)                         | 17        | 0.4%    |
| ASUS ASUS USB-BT500                                 | 17        | 0.4%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 16        | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4454      | 49.18%  |
| AMD                              | 2110      | 23.3%   |
| Nvidia                           | 1544      | 17.05%  |
| C-Media Electronics              | 142       | 1.57%   |
| Logitech                         | 70        | 0.77%   |
| Creative Labs                    | 48        | 0.53%   |
| GN Netcom                        | 39        | 0.43%   |
| ASUSTek Computer                 | 33        | 0.36%   |
| Texas Instruments                | 31        | 0.34%   |
| JMTek                            | 30        | 0.33%   |
| Generalplus Technology           | 30        | 0.33%   |
| Kingston Technology              | 29        | 0.32%   |
| Realtek Semiconductor            | 27        | 0.3%    |
| Creative Technology              | 27        | 0.3%    |
| Lenovo                           | 24        | 0.26%   |
| Hewlett-Packard                  | 23        | 0.25%   |
| SteelSeries ApS                  | 22        | 0.24%   |
| Razer USA                        | 21        | 0.23%   |
| Focusrite-Novation               | 21        | 0.23%   |
| Plantronics                      | 19        | 0.21%   |
| Dell                             | 13        | 0.14%   |
| Silicon Integrated Systems [SiS] | 12        | 0.13%   |
| Corsair                          | 12        | 0.13%   |
| Sony                             | 11        | 0.12%   |
| Micro Star International         | 10        | 0.11%   |
| Jieli Technology                 | 9         | 0.1%    |
| Blue Microphones                 | 9         | 0.1%    |
| Tenx Technology                  | 8         | 0.09%   |
| KTMicro                          | 8         | 0.09%   |
| Apple                            | 8         | 0.09%   |
| VIA Technologies                 | 7         | 0.08%   |
| Samson Technologies              | 6         | 0.07%   |
| Microsoft                        | 6         | 0.07%   |
| FiiO Electronics Technology      | 6         | 0.07%   |
| DSEA A/S                         | 6         | 0.07%   |
| BEHRINGER International          | 6         | 0.07%   |
| SAVITECH                         | 5         | 0.06%   |
| RODE Microphones                 | 5         | 0.06%   |
| PreSonus Audio Electronics       | 5         | 0.06%   |
| Medeli Electronics               | 5         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 745       | 6.85%   |
| Intel Sunrise Point-LP HD Audio                                            | 442       | 4.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 429       | 3.95%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 417       | 3.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 359       | 3.3%    |
| AMD Starship/Matisse HD Audio Controller                                   | 303       | 2.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 289       | 2.66%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 277       | 2.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 225       | 2.07%   |
| Intel Cannon Lake PCH cAVS                                                 | 221       | 2.03%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 210       | 1.93%   |
| AMD FCH Azalia Controller                                                  | 196       | 1.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 187       | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 184       | 1.69%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 165       | 1.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 162       | 1.49%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 158       | 1.45%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 157       | 1.44%   |
| Intel 8 Series HD Audio Controller                                         | 137       | 1.26%   |
| Intel Haswell-ULT HD Audio Controller                                      | 136       | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 132       | 1.21%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 127       | 1.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 125       | 1.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 121       | 1.11%   |
| Intel Comet Lake PCH-LP cAVS                                               | 119       | 1.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 118       | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 115       | 1.06%   |
| Intel 200 Series PCH HD Audio                                              | 115       | 1.06%   |
| Intel Broadwell-U Audio Controller                                         | 114       | 1.05%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 110       | 1.01%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 104       | 0.96%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 101       | 0.93%   |
| AMD Kabini HDMI/DP Audio                                                   | 100       | 0.92%   |
| Nvidia GA106 High Definition Audio Controller                              | 99        | 0.91%   |
| Intel Comet Lake PCH cAVS                                                  | 98        | 0.9%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 94        | 0.86%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 94        | 0.86%   |
| Nvidia GA104 High Definition Audio Controller                              | 91        | 0.84%   |
| Intel Alder Lake-S HD Audio Controller                                     | 88        | 0.81%   |
| Nvidia TU116 High Definition Audio Controller                              | 86        | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 974       | 20.41%  |
| SK hynix                     | 795       | 16.66%  |
| Kingston                     | 552       | 11.57%  |
| Micron Technology            | 474       | 9.93%   |
| Unknown                      | 406       | 8.51%   |
| Crucial                      | 293       | 6.14%   |
| Corsair                      | 260       | 5.45%   |
| G.Skill                      | 168       | 3.52%   |
| A-DATA Technology            | 104       | 2.18%   |
| Ramaxel Technology           | 71        | 1.49%   |
| Unknown                      | 66        | 1.38%   |
| Nanya Technology             | 62        | 1.3%    |
| Unknown (ABCD)               | 52        | 1.09%   |
| Elpida                       | 52        | 1.09%   |
| Team                         | 50        | 1.05%   |
| Patriot                      | 36        | 0.75%   |
| Smart                        | 29        | 0.61%   |
| GOODRAM                      | 29        | 0.61%   |
| AMD                          | 22        | 0.46%   |
| Transcend                    | 15        | 0.31%   |
| Apacer                       | 13        | 0.27%   |
| Goldkey                      | 10        | 0.21%   |
| Timetec                      | 9         | 0.19%   |
| Smart Brazil                 | 7         | 0.15%   |
| Silicon Power                | 7         | 0.15%   |
| PNY                          | 7         | 0.15%   |
| Wilk                         | 6         | 0.13%   |
| Teikon                       | 6         | 0.13%   |
| Qumo                         | 6         | 0.13%   |
| Kllisre                      | 6         | 0.13%   |
| Kingmax                      | 6         | 0.13%   |
| Hewlett-Packard              | 6         | 0.13%   |
| V-GeN                        | 5         | 0.1%    |
| Unifosa                      | 5         | 0.1%    |
| Toshiba                      | 5         | 0.1%    |
| PUSKILL                      | 5         | 0.1%    |
| Patriot Memory (PDP Systems) | 5         | 0.1%    |
| Patriot Memory               | 5         | 0.1%    |
| Neo Forza                    | 5         | 0.1%    |
| CSX                          | 5         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 66        | 1.3%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 43        | 0.85%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 37        | 0.73%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 35        | 0.69%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 33        | 0.65%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 33        | 0.65%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 31        | 0.61%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 31        | 0.61%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 30        | 0.59%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 27        | 0.53%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 26        | 0.51%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 24        | 0.47%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 23        | 0.45%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 22        | 0.43%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 22        | 0.43%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 21        | 0.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 20        | 0.39%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.39%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 20        | 0.39%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 19        | 0.37%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 19        | 0.37%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 18        | 0.35%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 18        | 0.35%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 18        | 0.35%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 18        | 0.35%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 18        | 0.35%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 17        | 0.33%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.33%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 17        | 0.33%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 16        | 0.31%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 0.31%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 16        | 0.31%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 16        | 0.31%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 16        | 0.31%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8192MB SODIMM DDR4 3200MT/s          | 16        | 0.31%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 15        | 0.29%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 15        | 0.29%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 15        | 0.29%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 15        | 0.29%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s              | 15        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2009      | 48.57%  |
| DDR3    | 1276      | 30.85%  |
| LPDDR4  | 208       | 5.03%   |
| DDR2    | 167       | 4.04%   |
| Unknown | 109       | 2.64%   |
| SDRAM   | 106       | 2.56%   |
| DDR5    | 106       | 2.56%   |
| LPDDR3  | 82        | 1.98%   |
| LPDDR5  | 43        | 1.04%   |
| DDR     | 27        | 0.65%   |
| DRAM    | 3         | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2266      | 54.84%  |
| DIMM         | 1504      | 36.4%   |
| Row Of Chips | 322       | 7.79%   |
| Unknown      | 19        | 0.46%   |
| Chip         | 15        | 0.36%   |
| RIMM         | 4         | 0.1%    |
| FB-DIMM      | 2         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1700      | 38.08%  |
| 4096  | 1260      | 28.23%  |
| 16384 | 643       | 14.4%   |
| 2048  | 554       | 12.41%  |
| 32768 | 172       | 3.85%   |
| 1024  | 116       | 2.6%    |
| 512   | 15        | 0.34%   |
| 256   | 2         | 0.04%   |
| 65536 | 1         | 0.02%   |
| 8     | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 834       | 18.61%  |
| 3200    | 789       | 17.6%   |
| 2667    | 552       | 12.32%  |
| 2400    | 350       | 7.81%   |
| 1333    | 287       | 6.4%    |
| 2133    | 213       | 4.75%   |
| 3600    | 134       | 2.99%   |
| 1334    | 117       | 2.61%   |
| 800     | 96        | 2.14%   |
| 667     | 91        | 2.03%   |
| 4800    | 81        | 1.81%   |
| 1867    | 71        | 1.58%   |
| Unknown | 64        | 1.43%   |
| 4267    | 61        | 1.36%   |
| 1067    | 57        | 1.27%   |
| 6400    | 45        | 1%      |
| 3000    | 40        | 0.89%   |
| 2666    | 40        | 0.89%   |
| 2933    | 39        | 0.87%   |
| 1066    | 39        | 0.87%   |
| 3266    | 38        | 0.85%   |
| 1866    | 38        | 0.85%   |
| 3400    | 37        | 0.83%   |
| 3733    | 35        | 0.78%   |
| 4266    | 33        | 0.74%   |
| 3466    | 28        | 0.62%   |
| 2048    | 21        | 0.47%   |
| 4199    | 20        | 0.45%   |
| 533     | 20        | 0.45%   |
| 3866    | 17        | 0.38%   |
| 975     | 14        | 0.31%   |
| 2800    | 13        | 0.29%   |
| 1800    | 13        | 0.29%   |
| 400     | 13        | 0.29%   |
| 3800    | 12        | 0.27%   |
| 5200    | 9         | 0.2%    |
| 1639    | 8         | 0.18%   |
| 8400    | 7         | 0.16%   |
| 6000    | 6         | 0.13%   |
| 3666    | 6         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)

![Printer Vendor](./images/line_chart/printer_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 64        | 35.16%  |
| Canon                 | 34        | 18.68%  |
| Brother Industries    | 32        | 17.58%  |
| Seiko Epson           | 18        | 9.89%   |
| Samsung Electronics   | 13        | 7.14%   |
| Prolific Technology   | 4         | 2.2%    |
| Kyocera               | 3         | 1.65%   |
| Xerox                 | 2         | 1.1%    |
| STMicroelectronics    | 2         | 1.1%    |
| Ricoh                 | 2         | 1.1%    |
| QinHeng Electronics   | 2         | 1.1%    |
| Zebra                 | 1         | 0.55%   |
| Seiko Instruments     | 1         | 0.55%   |
| Oki Data              | 1         | 0.55%   |
| Minolta               | 1         | 0.55%   |
| Lexmark International | 1         | 0.55%   |
| Dymo-CoStar           | 1         | 0.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)

![Printer Model](./images/line_chart/printer_model.svg)

| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                             | 4         | 2.17%   |
| HP ENVY 5000 series                                       | 4         | 2.17%   |
| HP DeskJet 2700 series                                    | 4         | 2.17%   |
| Canon PIXMA MG2500 Series                                 | 4         | 2.17%   |
| Seiko Epson ET-2820 Series                                | 3         | 1.63%   |
| Samsung SCX-3400 Series                                   | 3         | 1.63%   |
| Samsung M2070 Series                                      | 3         | 1.63%   |
| HP LaserJet P1102                                         | 3         | 1.63%   |
| HP LaserJet 1018                                          | 3         | 1.63%   |
| Canon MF3110                                              | 3         | 1.63%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.09%   |
| Seiko Epson ET-2710 Series                                | 2         | 1.09%   |
| Samsung ML-2950 Series                                    | 2         | 1.09%   |
| Samsung M2020 Series                                      | 2         | 1.09%   |
| QinHeng CH340S                                            | 2         | 1.09%   |
| Kyocera FS-1120MFP                                        | 2         | 1.09%   |
| HP LaserJet P1005                                         | 2         | 1.09%   |
| HP LaserJet 1020                                          | 2         | 1.09%   |
| HP Ink Tank Wireless 410 series                           | 2         | 1.09%   |
| HP DeskJet F2492 All-in-One                               | 2         | 1.09%   |
| HP DeskJet 4100 series                                    | 2         | 1.09%   |
| HP DeskJet 2600 series                                    | 2         | 1.09%   |
| HP ColorLaserJet M253-M254                                | 2         | 1.09%   |
| Canon TR8500 series                                       | 2         | 1.09%   |
| Canon PIXMA MX490 Series                                  | 2         | 1.09%   |
| Canon CanoScan LiDE 300                                   | 2         | 1.09%   |
| Brother HL-L2390DW                                        | 2         | 1.09%   |
| Brother HL-L2370DW series                                 | 2         | 1.09%   |
| Brother HL-L2305 series                                   | 2         | 1.09%   |
| Zebra ZP 450 Printer                                      | 1         | 0.54%   |
| Xerox WorkCentre 3220                                     | 1         | 0.54%   |
| Xerox Phaser 3610                                         | 1         | 0.54%   |
| Seiko Instruments Smart Label Printer 620                 | 1         | 0.54%   |
| Seiko Epson XP-225 Series                                 | 1         | 0.54%   |
| Seiko Epson XP-100 Series                                 | 1         | 0.54%   |
| Seiko Epson WF-3520 Series                                | 1         | 0.54%   |
| Seiko Epson Printer                                       | 1         | 0.54%   |
| Seiko Epson L396 Series                                   | 1         | 0.54%   |
| Seiko Epson L355 Series                                   | 1         | 0.54%   |
| Seiko Epson L310 Series                                   | 1         | 0.54%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)

![Scanner Vendor](./images/line_chart/scanner_vendor.svg)

| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 17        | 50%     |
| Seiko Epson                 | 8         | 23.53%  |
| Hewlett-Packard             | 6         | 17.65%  |
| Mustek Systems              | 1         | 2.94%   |
| AGFA-Gevaert NV             | 1         | 2.94%   |
| Acer Peripherals (now BenQ) | 1         | 2.94%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)

![Scanner Model](./images/line_chart/scanner_model.svg)

| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                  | 7         | 20.59%  |
| Seiko Epson GT-X820 [Perfection V600 Photo]              | 2         | 5.88%   |
| HP ScanJet 3400cse                                       | 2         | 5.88%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 2         | 5.88%   |
| Canon CanoScan LiDE 220                                  | 2         | 5.88%   |
| Canon CanoScan LiDE 210                                  | 2         | 5.88%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]         | 1         | 2.94%   |
| Seiko Epson GT-X770 [Perfection V500]                    | 1         | 2.94%   |
| Seiko Epson GT-F700 [Perfection V350]                    | 1         | 2.94%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 1         | 2.94%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 2.94%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]        | 1         | 2.94%   |
| Mustek Systems ScanExpress 1200 UB                       | 1         | 2.94%   |
| HP Scanjet N6010                                         | 1         | 2.94%   |
| HP ScanJet G4010                                         | 1         | 2.94%   |
| HP ScanJet 7400c                                         | 1         | 2.94%   |
| HP ScanJet 2400c                                         | 1         | 2.94%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 1         | 2.94%   |
| Canon CanoScan LiDE 200                                  | 1         | 2.94%   |
| Canon CanoScan LiDE 120                                  | 1         | 2.94%   |
| Canon CanoScan LiDE 100                                  | 1         | 2.94%   |
| AGFA-Gevaert NV SnapScan e20                             | 1         | 2.94%   |
| Acer Peripherals (now BenQ) Benq 5560                    | 1         | 2.94%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)

![Camera Vendor](./images/line_chart/camera_vendor.svg)

| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 818       | 21.2%   |
| IMC Networks                           | 378       | 9.8%    |
| Microdia                               | 342       | 8.86%   |
| Acer                                   | 298       | 7.72%   |
| Realtek Semiconductor                  | 254       | 6.58%   |
| Logitech                               | 227       | 5.88%   |
| Quanta                                 | 208       | 5.39%   |
| Sunplus Innovation Technology          | 184       | 4.77%   |
| Cheng Uei Precision Industry (Foxlink) | 147       | 3.81%   |
| Apple                                  | 122       | 3.16%   |
| Syntek                                 | 111       | 2.88%   |
| Suyin                                  | 97        | 2.51%   |
| Luxvisions Innotech Limited            | 82        | 2.12%   |
| Lite-On Technology                     | 73        | 1.89%   |
| Silicon Motion                         | 51        | 1.32%   |
| Alcor Micro                            | 43        | 1.11%   |
| Microsoft                              | 40        | 1.04%   |
| Sonix Technology                       | 32        | 0.83%   |
| Samsung Electronics                    | 28        | 0.73%   |
| Z-Star Microelectronics                | 24        | 0.62%   |
| Ricoh                                  | 18        | 0.47%   |
| SunplusIT                              | 15        | 0.39%   |
| Lenovo                                 | 15        | 0.39%   |
| ARC International                      | 15        | 0.39%   |
| Generalplus Technology                 | 14        | 0.36%   |
| Primax Electronics                     | 13        | 0.34%   |
| icSpring                               | 11        | 0.29%   |
| Importek                               | 10        | 0.26%   |
| MacroSilicon                           | 9         | 0.23%   |
| Jieli Technology                       | 8         | 0.21%   |
| Intel                                  | 7         | 0.18%   |
| Trust                                  | 6         | 0.16%   |
| KYE Systems (Mouse Systems)            | 6         | 0.16%   |
| Hewlett-Packard                        | 6         | 0.16%   |
| Y Media                                | 5         | 0.13%   |
| WaveRider Communications               | 5         | 0.13%   |
| Razer USA                              | 5         | 0.13%   |
| OmniVision Technologies                | 5         | 0.13%   |
| GEMBIRD                                | 5         | 0.13%   |
| Cubeternet                             | 5         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 173       | 4.45%   |
| Microdia Integrated_Webcam_HD                        | 136       | 3.5%    |
| IMC Networks USB2.0 HD UVC WebCam                    | 110       | 2.83%   |
| IMC Networks Integrated Camera                       | 104       | 2.67%   |
| Chicony HD WebCam                                    | 85        | 2.19%   |
| Acer Integrated Camera                               | 84        | 2.16%   |
| Realtek Integrated_Webcam_HD                         | 79        | 2.03%   |
| Syntek Integrated Camera                             | 73        | 1.88%   |
| Sunplus Integrated_Webcam_HD                         | 48        | 1.23%   |
| Logitech Webcam C270                                 | 45        | 1.16%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 42        | 1.08%   |
| Quanta HD User Facing                                | 39        | 1%      |
| Microdia USB 2.0 Camera                              | 39        | 1%      |
| Apple Built-in iSight                                | 38        | 0.98%   |
| Microdia Integrated Webcam                           | 36        | 0.93%   |
| Logitech HD Pro Webcam C920                          | 36        | 0.93%   |
| Acer Lenovo EasyCamera                               | 35        | 0.9%    |
| Apple iPhone 5/5C/5S/6/SE                            | 32        | 0.82%   |
| Chicony USB2.0 Camera                                | 31        | 0.8%    |
| Sunplus HD WebCam                                    | 30        | 0.77%   |
| Chicony HP HD Camera                                 | 30        | 0.77%   |
| Samsung Galaxy A5 (MTP)                              | 28        | 0.72%   |
| Chicony HP TrueVision HD Camera                      | 28        | 0.72%   |
| Chicony HP Truevision HD                             | 28        | 0.72%   |
| Chicony HD User Facing                               | 28        | 0.72%   |
| Apple FaceTime HD Camera (Built-in)                  | 28        | 0.72%   |
| Chicony HP Webcam                                    | 27        | 0.69%   |
| Microdia Webcam Vitade AF                            | 26        | 0.67%   |
| Acer BisonCam,NB Pro                                 | 26        | 0.67%   |
| Sonix USB2.0 HD UVC WebCam                           | 25        | 0.64%   |
| Chicony HP Wide Vision HD Camera                     | 25        | 0.64%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 23        | 0.59%   |
| Acer HD Webcam                                       | 23        | 0.59%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 22        | 0.57%   |
| Chicony USB2.0 VGA UVC WebCam                        | 22        | 0.57%   |
| Quanta HP HD Camera                                  | 21        | 0.54%   |
| Acer EasyCamera                                      | 21        | 0.54%   |
| Realtek USB Camera                                   | 20        | 0.51%   |
| Quanta HP Wide Vision HD Camera                      | 20        | 0.51%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 20        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 227       | 32.43%  |
| Synaptics                          | 174       | 24.86%  |
| Shenzhen Goodix Technology         | 116       | 16.57%  |
| Elan Microelectronics              | 56        | 8%      |
| LighTuning Technology              | 36        | 5.14%   |
| AuthenTec                          | 36        | 5.14%   |
| Upek                               | 31        | 4.43%   |
| STMicroelectronics                 | 6         | 0.86%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 0.57%   |
| Microsoft                          | 3         | 0.43%   |
| Focal-systems.Corp                 | 3         | 0.43%   |
| DigitalPersona                     | 3         | 0.43%   |
| Samsung Electronics                | 2         | 0.29%   |
| HOLTEK                             | 2         | 0.29%   |
| Next Biometrics                    | 1         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 75        | 10.71%  |
| Shenzhen Goodix  Fingerprint Device                                        | 67        | 9.57%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 51        | 7.29%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 41        | 5.86%   |
| Elan ELAN:ARM-M4                                                           | 38        | 5.43%   |
| Shenzhen Goodix Fingerprint Reader                                         | 36        | 5.14%   |
| Validity Sensors Synaptics WBDI                                            | 30        | 4.29%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 30        | 4.29%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 27        | 3.86%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 22        | 3.14%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 20        | 2.86%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 19        | 2.71%   |
| Elan ELAN:Fingerprint                                                      | 17        | 2.43%   |
| Validity Sensors VFS491                                                    | 16        | 2.29%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 16        | 2.29%   |
| Validity Sensors Fingerprint scanner                                       | 14        | 2%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 13        | 1.86%   |
| Synaptics  WBDI                                                            | 13        | 1.86%   |
| Shenzhen Goodix FingerPrint                                                | 13        | 1.86%   |
| AuthenTec AES2810                                                          | 12        | 1.71%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 10        | 1.43%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 9         | 1.29%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.29%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 1.29%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 1.14%   |
| LighTuning Fingerprint Sensor                                              | 7         | 1%      |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 6         | 0.86%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 0.86%   |
| AuthenTec AES1600                                                          | 6         | 0.86%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 0.71%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 0.71%   |
| LighTuning Fingerprint Reader                                              | 5         | 0.71%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.71%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 0.57%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.43%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.43%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.43%   |
| Microsoft Fingerprint Reader                                               | 3         | 0.43%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 0.43%   |
| DigitalPersona Fingerprint Reader                                          | 3         | 0.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./images/line_chart/chipcard_vendor.svg)

| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 126       | 42.42%  |
| Alcor Micro               | 88        | 29.63%  |
| Upek                      | 20        | 6.73%   |
| O2 Micro                  | 20        | 6.73%   |
| Lenovo                    | 16        | 5.39%   |
| Gemalto (was Gemplus)     | 4         | 1.35%   |
| Advanced Card Systems     | 4         | 1.35%   |
| Reiner SCT Kartensysteme  | 3         | 1.01%   |
| Clay Logic                | 3         | 1.01%   |
| Yubico.com                | 2         | 0.67%   |
| SCM Microsystems          | 2         | 0.67%   |
| Realtek Semiconductor     | 2         | 0.67%   |
| OmniKey                   | 2         | 0.67%   |
| Purism, SPC               | 1         | 0.34%   |
| Fujitsu Siemens Computers | 1         | 0.34%   |
| Chicony Electronics       | 1         | 0.34%   |
| Aladdin Knowledge Systems | 1         | 0.34%   |
| Aktiv                     | 1         | 0.34%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)

![Chipcard Model](./images/line_chart/chipcard_model.svg)

| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 87        | 29.29%  |
| Broadcom 58200                                                               | 39        | 13.13%  |
| Broadcom 5880                                                                | 36        | 12.12%  |
| Broadcom BCM5880 Secure Applications Processor                               | 34        | 11.45%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 20        | 6.73%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 6.06%   |
| Lenovo Integrated Smart Card Reader                                          | 15        | 5.05%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 15        | 5.05%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.01%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.67%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.67%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.67%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 0.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.67%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.67%   |
| SCM Microsystems uTrust 3700 F CL Reader                                     | 1         | 0.34%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.34%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 1         | 0.34%   |
| Purism, SPC Librem Key                                                       | 1         | 0.34%   |
| OmniKey 5022 Smart Card Reader                                               | 1         | 0.34%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.34%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.34%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.34%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.34%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.34%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.34%   |
| Clay Logic CanoKey Pigeon                                                    | 1         | 0.34%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.34%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.34%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.34%   |
| Aktiv Rutoken lite                                                           | 1         | 0.34%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.34%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.34%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4656      | 70.8%   |
| 1     | 1519      | 23.1%   |
| 2     | 329       | 5%      |
| 3     | 50        | 0.76%   |
| 4     | 15        | 0.23%   |
| 6     | 3         | 0.05%   |
| 5     | 3         | 0.05%   |
| 9     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 689       | 29.44%  |
| Graphics card            | 530       | 22.65%  |
| Net/wireless             | 270       | 11.54%  |
| Chipcard                 | 246       | 10.51%  |
| Multimedia controller    | 161       | 6.88%   |
| Communication controller | 94        | 4.02%   |
| Camera                   | 88        | 3.76%   |
| Unassigned class         | 54        | 2.31%   |
| Bluetooth                | 47        | 2.01%   |
| Sound                    | 39        | 1.67%   |
| Storage                  | 30        | 1.28%   |
| Net/ethernet             | 16        | 0.68%   |
| Card reader              | 16        | 0.68%   |
| Network                  | 15        | 0.64%   |
| Modem                    | 13        | 0.56%   |
| Storage/raid             | 9         | 0.38%   |
| Dvb card                 | 7         | 0.3%    |
| Tv card                  | 3         | 0.13%   |
| Storage/nvme             | 3         | 0.13%   |
| Storage/ide              | 3         | 0.13%   |
| Wireless                 | 2         | 0.09%   |
| Flash memory             | 2         | 0.09%   |
| Firewire controller      | 2         | 0.09%   |
| Storage/ata              | 1         | 0.04%   |

