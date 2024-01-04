Linux - Hardware Trends (Notebooks)
-----------------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: Dec, 2023.

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

| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 22.04                 | 408       | 12.61%  |
| Fedora 39                    | 304       | 9.39%   |
| Linux Mint 21.2              | 244       | 7.54%   |
| Debian 12                    | 182       | 5.62%   |
| Arch Rolling                 | 145       | 4.48%   |
| Ubuntu 23.10                 | 143       | 4.42%   |
| OpenMandriva 5.0             | 120       | 3.71%   |
| Pop!_OS 22.04                | 89        | 2.75%   |
| OpenMandriva 23.08           | 84        | 2.6%    |
| Zorin 16                     | 80        | 2.47%   |
| ROSA 12.4                    | 80        | 2.47%   |
| SteamOS 3.5.7                | 79        | 2.44%   |
| BlackPanther 18.1            | 73        | 2.26%   |
| ArcoLinux Rolling            | 67        | 2.07%   |
| OpenMandriva 23.11           | 49        | 1.51%   |
| Ubuntu 20.04                 | 48        | 1.48%   |
| EndeavourOS Rolling          | 41        | 1.27%   |
| Zorin 17                     | 40        | 1.24%   |
| Kali 2023.4                  | 39        | 1.21%   |
| openSUSE Tumbleweed-XXXXXXXX | 36        | 1.11%   |
| Fedora 38                    | 36        | 1.11%   |
| Kubuntu 22.04                | 34        | 1.05%   |
| Manjaro                      | 33        | 1.02%   |
| Kubuntu 23.10                | 31        | 0.96%   |
| Xero Rolling                 | 29        | 0.9%    |
| KDE neon 22.04               | 27        | 0.83%   |
| Debian                       | 25        | 0.77%   |
| Ubuntu 23.04                 | 24        | 0.74%   |
| Linux Mint 20.3              | 22        | 0.68%   |
| Debian Testing/unstable      | 21        | 0.65%   |
| Xubuntu 22.04                | 20        | 0.62%   |
| LMDE 6                       | 20        | 0.62%   |
| Linux Mint 21.1              | 20        | 0.62%   |
| Gentoo 2.14                  | 16        | 0.49%   |
| Nobara 38                    | 15        | 0.46%   |
| Manjaro 23.1.0               | 15        | 0.46%   |
| Elementary 7.1               | 15        | 0.46%   |
| MX 23                        | 14        | 0.43%   |
| openSUSE Leap-15.5           | 13        | 0.4%    |
| Ubuntu MATE 22.04            | 12        | 0.37%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 642       | 19.84%  |
| Fedora        | 357       | 11.03%  |
| Linux Mint    | 317       | 9.8%    |
| OpenMandriva  | 287       | 8.87%   |
| Debian        | 242       | 7.48%   |
| Arch          | 145       | 4.48%   |
| Zorin         | 124       | 3.83%   |
| ROSA          | 102       | 3.15%   |
| SteamOS       | 98        | 3.03%   |
| Pop!_OS       | 90        | 2.78%   |
| Kubuntu       | 75        | 2.32%   |
| BlackPanther  | 74        | 2.29%   |
| ArcoLinux     | 69        | 2.13%   |
| Manjaro       | 62        | 1.92%   |
| openSUSE      | 53        | 1.64%   |
| Kali          | 45        | 1.39%   |
| EndeavourOS   | 42        | 1.3%    |
| Xubuntu       | 31        | 0.96%   |
| Xero          | 29        | 0.9%    |
| KDE neon      | 27        | 0.83%   |
| LMDE          | 21        | 0.65%   |
| Nobara        | 20        | 0.62%   |
| Lubuntu       | 19        | 0.59%   |
| Ubuntu MATE   | 18        | 0.56%   |
| NixOS         | 17        | 0.53%   |
| MX            | 17        | 0.53%   |
| Garuda Linux  | 17        | 0.53%   |
| Gentoo        | 16        | 0.49%   |
| Elementary    | 16        | 0.49%   |
| Parrot        | 11        | 0.34%   |
| Ubuntu Unity  | 9         | 0.28%   |
| Endless       | 9         | 0.28%   |
| ALT Linux     | 9         | 0.28%   |
| TUXEDO OS     | 8         | 0.25%   |
| blendOS       | 7         | 0.22%   |
| ChimeraOS     | 6         | 0.19%   |
| Ubuntu Studio | 5         | 0.15%   |
| Ubuntu Budgie | 5         | 0.15%   |
| Red OS        | 5         | 0.15%   |
| BunsenLabs    | 5         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version                           | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| 6.2.0-39-generic                  | 278       | 8.59%   |
| 5.15.0-91-generic                 | 239       | 7.39%   |
| 6.2.0-37-generic                  | 201       | 6.21%   |
| 6.6.2-desktop-1omv2390            | 159       | 4.91%   |
| 6.5.0-14-generic                  | 134       | 4.14%   |
| 5.15.0-89-generic                 | 90        | 2.78%   |
| 6.1.0-16-amd64                    | 83        | 2.56%   |
| 6.4.11-desktop-1omv2390           | 81        | 2.5%    |
| 6.1.52-valve9-1-neptune-61        | 78        | 2.41%   |
| 6.1.58-generic-1rosa2021.1-x86_64 | 58        | 1.79%   |
| 6.1.0-13-amd64                    | 58        | 1.79%   |
| 6.6.7-arch1-1                     | 57        | 1.76%   |
| 6.6.4-200.fc39.x86_64             | 56        | 1.73%   |
| 6.6.6-200.fc39.x86_64             | 53        | 1.64%   |
| 6.6.8-200.fc39.x86_64             | 52        | 1.61%   |
| 6.5.6-76060506-generic            | 44        | 1.36%   |
| 6.6.7-200.fc39.x86_64             | 43        | 1.33%   |
| 6.6.4-arch1-1                     | 41        | 1.27%   |
| 6.6.6-76060606-generic            | 39        | 1.21%   |
| 6.1.0-15-amd64                    | 39        | 1.21%   |
| 5.15.85-desktop-1bP               | 38        | 1.17%   |
| 6.5.0-kali3-amd64                 | 37        | 1.14%   |
| 6.6.3-arch1-1                     | 35        | 1.08%   |
| 6.6.2-201.fc39.x86_64             | 34        | 1.05%   |
| 6.6.8-arch1-1                     | 33        | 1.02%   |
| 6.5.0-13-generic                  | 33        | 1.02%   |
| 6.2.0-26-generic                  | 30        | 0.93%   |
| 6.6.3-200.fc39.x86_64             | 26        | 0.8%    |
| 6.5.0-9-generic                   | 25        | 0.77%   |
| 5.15.0-76-generic                 | 25        | 0.77%   |
| 6.5.6-300.fc39.x86_64             | 24        | 0.74%   |
| 5.10.10-64                        | 22        | 0.68%   |
| 6.6.6-1-default                   | 20        | 0.62%   |
| 6.1.20-generic-2rosa2021.1-x86_64 | 18        | 0.56%   |
| 5.4.0-169-generic                 | 18        | 0.56%   |
| 6.5.0-5-amd64                     | 16        | 0.49%   |
| 5.6.14-desktop-2bP                | 16        | 0.49%   |
| 6.6.1-arch1-1                     | 15        | 0.46%   |
| 5.15.0-88-generic                 | 15        | 0.46%   |
| 6.6.8-2-MANJARO                   | 14        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.0   | 541       | 16.72%  |
| 5.15.0  | 417       | 12.89%  |
| 6.5.0   | 313       | 9.67%   |
| 6.1.0   | 227       | 7.01%   |
| 6.6.2   | 207       | 6.4%    |
| 6.6.6   | 144       | 4.45%   |
| 6.6.7   | 142       | 4.39%   |
| 6.6.8   | 128       | 3.96%   |
| 6.6.4   | 123       | 3.8%    |
| 6.1.52  | 95        | 2.94%   |
| 6.6.3   | 94        | 2.9%    |
| 6.4.11  | 84        | 2.6%    |
| 6.5.6   | 74        | 2.29%   |
| 6.1.58  | 60        | 1.85%   |
| 5.4.0   | 55        | 1.7%    |
| 5.15.85 | 38        | 1.17%   |
| 5.10.10 | 22        | 0.68%   |
| 6.6.1   | 21        | 0.65%   |
| 5.10.0  | 19        | 0.59%   |
| 6.6.5   | 18        | 0.56%   |
| 6.5.13  | 18        | 0.56%   |
| 6.1.20  | 18        | 0.56%   |
| 5.6.14  | 17        | 0.53%   |
| 6.1.69  | 14        | 0.43%   |
| 6.7.0   | 13        | 0.4%    |
| 6.5.9   | 13        | 0.4%    |
| 6.5.12  | 13        | 0.4%    |
| 6.1.64  | 13        | 0.4%    |
| 5.14.21 | 13        | 0.4%    |
| 4.18.16 | 13        | 0.4%    |
| 6.1.67  | 12        | 0.37%   |
| 4.15.0  | 12        | 0.37%   |
| 5.19.0  | 10        | 0.31%   |
| 6.4.8   | 9         | 0.28%   |
| 5.14.0  | 9         | 0.28%   |
| 6.6.0   | 8         | 0.25%   |
| 6.5.5   | 8         | 0.25%   |
| 6.5.11  | 8         | 0.25%   |
| 6.1.68  | 8         | 0.25%   |
| 6.2.6   | 7         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.6     | 885       | 27.35%  |
| 6.2     | 563       | 17.4%   |
| 6.1     | 479       | 14.8%   |
| 6.5     | 466       | 14.4%   |
| 5.15    | 466       | 14.4%   |
| 6.4     | 108       | 3.34%   |
| 5.10    | 63        | 1.95%   |
| 5.4     | 58        | 1.79%   |
| 5.14    | 22        | 0.68%   |
| 6.3     | 21        | 0.65%   |
| 5.6     | 17        | 0.53%   |
| 4.18    | 16        | 0.49%   |
| 6.7     | 13        | 0.4%    |
| 4.15    | 12        | 0.37%   |
| 5.19    | 11        | 0.34%   |
| 6.0     | 7         | 0.22%   |
| 5.16    | 6         | 0.19%   |
| 5.13    | 6         | 0.19%   |
| 5.17    | 4         | 0.12%   |
| 5.8     | 3         | 0.09%   |
| 5.11    | 3         | 0.09%   |
| 6       | 1         | 0.03%   |
| 5.18    | 1         | 0.03%   |
| 5.1     | 1         | 0.03%   |
| 4.9     | 1         | 0.03%   |
| 4.8     | 1         | 0.03%   |
| 4.19    | 1         | 0.03%   |
| 4.13    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 3211      | 99.23%  |
| i686    | 20        | 0.62%   |
| aarch64 | 4         | 0.12%   |
| armv7l  | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 1396      | 43.14%  |
| KDE5             | 938       | 28.99%  |
| X-Cinnamon       | 290       | 8.96%   |
| XFCE             | 212       | 6.55%   |
| MATE             | 77        | 2.38%   |
| Unknown          | 67        | 2.07%   |
| LXQt             | 53        | 1.64%   |
| LXDE             | 28        | 0.87%   |
| Cinnamon         | 26        | 0.8%    |
| i3               | 21        | 0.65%   |
| Pantheon         | 18        | 0.56%   |
| Hyprland         | 15        | 0.46%   |
| Budgie           | 14        | 0.43%   |
| Unity            | 8         | 0.25%   |
| GNOME Classic    | 7         | 0.22%   |
| Deepin           | 7         | 0.22%   |
| sway             | 6         | 0.19%   |
| lightdm-xsession | 6         | 0.19%   |
| KDE              | 5         | 0.15%   |
| Endless:GNOME    | 5         | 0.15%   |
| KDE4             | 4         | 0.12%   |
| GNOME Flashback  | 4         | 0.12%   |
| Enlightenment    | 3         | 0.09%   |
| Unicorn:XFCE     | 2         | 0.06%   |
| KDE6             | 2         | 0.06%   |
| Jwm              | 2         | 0.06%   |
| icewm            | 2         | 0.06%   |
| GNOME-Classic    | 2         | 0.06%   |
| BunsenLabs       | 2         | 0.06%   |
| xmonad           | 1         | 0.03%   |
| Trinity          | 1         | 0.03%   |
| qtile-default    | 1         | 0.03%   |
| qtile            | 1         | 0.03%   |
| none+i3          | 1         | 0.03%   |
| MakuluGameR      | 1         | 0.03%   |
| Lubuntu          | 1         | 0.03%   |
| GNUstep          | 1         | 0.03%   |
| gamescope        | 1         | 0.03%   |
| fly              | 1         | 0.03%   |
| fluxbox          | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1718      | 53.09%  |
| Wayland | 1424      | 44%     |
| Unknown | 55        | 1.7%    |
| Tty     | 38        | 1.17%   |
| Web     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1088      | 33.62%  |
| SDDM    | 746       | 23.05%  |
| GDM3    | 712       | 22%     |
| LightDM | 427       | 13.2%   |
| GDM     | 224       | 6.92%   |
| NODM    | 22        | 0.68%   |
| KDM     | 4         | 0.12%   |
| SLIMSKI | 2         | 0.06%   |
| SLiM    | 2         | 0.06%   |
| LXDM    | 2         | 0.06%   |
| GREETD  | 2         | 0.06%   |
| XDM     | 1         | 0.03%   |
| TDM     | 1         | 0.03%   |
| LY-DM   | 1         | 0.03%   |
| FLY-DM  | 1         | 0.03%   |
| EMPTTY  | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1355      | 41.87%  |
| de_DE   | 276       | 8.53%   |
| ru_RU   | 209       | 6.46%   |
| fr_FR   | 177       | 5.47%   |
| en_GB   | 145       | 4.48%   |
| it_IT   | 119       | 3.68%   |
| Unknown | 100       | 3.09%   |
| pt_BR   | 88        | 2.72%   |
| es_ES   | 86        | 2.66%   |
| pl_PL   | 85        | 2.63%   |
| C       | 77        | 2.38%   |
| en_IN   | 50        | 1.55%   |
| en_CA   | 49        | 1.51%   |
| es_MX   | 36        | 1.11%   |
| en_AU   | 26        | 0.8%    |
| pt_PT   | 19        | 0.59%   |
| nl_NL   | 18        | 0.56%   |
| de_AT   | 18        | 0.56%   |
| tr_TR   | 17        | 0.53%   |
| hu_HU   | 14        | 0.43%   |
| es_CO   | 14        | 0.43%   |
| es_AR   | 14        | 0.43%   |
| de_CH   | 14        | 0.43%   |
| cs_CZ   | 14        | 0.43%   |
| zh_CN   | 12        | 0.37%   |
| POSIX   | 10        | 0.31%   |
| en_IL   | 10        | 0.31%   |
| sv_SE   | 9         | 0.28%   |
| es_CL   | 9         | 0.28%   |
| ro_RO   | 8         | 0.25%   |
| fr_CA   | 8         | 0.25%   |
| zh_TW   | 7         | 0.22%   |
| ja_JP   | 7         | 0.22%   |
| en_ZA   | 7         | 0.22%   |
| en_DK   | 7         | 0.22%   |
| nb_NO   | 6         | 0.19%   |
| es_UY   | 6         | 0.19%   |
| en_NZ   | 6         | 0.19%   |
| en_IE   | 6         | 0.19%   |
| da_DK   | 6         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1869      | 57.76%  |
| BIOS | 1367      | 42.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 1844      | 56.98%  |
| Btrfs    | 655       | 20.24%  |
| Tmpfs    | 435       | 13.44%  |
| Overlay  | 216       | 6.67%   |
| Xfs      | 29        | 0.9%    |
| Rootfs   | 22        | 0.68%   |
| Zfs      | 20        | 0.62%   |
| F2fs     | 6         | 0.19%   |
| Ext3     | 3         | 0.09%   |
| Bcachefs | 2         | 0.06%   |
| Unknown  | 2         | 0.06%   |
| Ext2     | 1         | 0.03%   |
| Aufs     | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1872      | 57.85%  |
| Unknown | 1027      | 31.74%  |
| MBR     | 337       | 10.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2830      | 87.45%  |
| Yes       | 406       | 12.55%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2406      | 74.35%  |
| Yes       | 830       | 25.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 690       | 21.32%  |
| Hewlett-Packard     | 534       | 16.5%   |
| Dell                | 446       | 13.78%  |
| ASUSTek Computer    | 404       | 12.48%  |
| Acer                | 259       | 8%      |
| Apple               | 105       | 3.24%   |
| Valve               | 97        | 3%      |
| MSI                 | 67        | 2.07%   |
| Toshiba             | 59        | 1.82%   |
| HUAWEI              | 55        | 1.7%    |
| Samsung Electronics | 40        | 1.24%   |
| Google              | 35        | 1.08%   |
| Sony                | 33        | 1.02%   |
| Unknown             | 31        | 0.96%   |
| Fujitsu             | 29        | 0.9%    |
| Medion              | 28        | 0.87%   |
| Framework           | 25        | 0.77%   |
| TUXEDO              | 16        | 0.49%   |
| Alienware           | 16        | 0.49%   |
| Packard Bell        | 15        | 0.46%   |
| Notebook            | 12        | 0.37%   |
| System76            | 11        | 0.34%   |
| Timi                | 10        | 0.31%   |
| Razer               | 8         | 0.25%   |
| LG Electronics      | 8         | 0.25%   |
| Gigabyte Technology | 8         | 0.25%   |
| Clevo               | 8         | 0.25%   |
| Chuwi               | 8         | 0.25%   |
| Positivo            | 7         | 0.22%   |
| Panasonic           | 6         | 0.19%   |
| Fujitsu Siemens     | 6         | 0.19%   |
| eMachines           | 6         | 0.19%   |
| HONOR               | 5         | 0.15%   |
| GPU Company         | 5         | 0.15%   |
| GPD                 | 5         | 0.15%   |
| Gateway             | 5         | 0.15%   |
| PC Specialist       | 4         | 0.12%   |
| Monster             | 4         | 0.12%   |
| Irbis               | 4         | 0.12%   |
| Dynabook            | 4         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Valve Jupiter                              | 75        | 2.32%   |
| Unknown                                    | 44        | 1.36%   |
| Valve Galileo                              | 22        | 0.68%   |
| HP Notebook                                | 22        | 0.68%   |
| Framework Laptop 13 (AMD Ryzen 7040Series) | 16        | 0.49%   |
| HP ProBook 650 G1                          | 10        | 0.31%   |
| HP Pavilion dv6                            | 10        | 0.31%   |
| Dell Latitude 7490                         | 10        | 0.31%   |
| Apple MacBookAir7,2                        | 10        | 0.31%   |
| HP ProBook 650 G2                          | 9         | 0.28%   |
| Dell Latitude E6440                        | 9         | 0.28%   |
| Lenovo ThinkPad X230 2325V2Y               | 8         | 0.25%   |
| HUAWEI BOD-WXX9                            | 8         | 0.25%   |
| HP Pavilion dv7                            | 8         | 0.25%   |
| HP Pavilion 15                             | 8         | 0.25%   |
| Apple MacBookPro9,2                        | 8         | 0.25%   |
| Apple MacBookAir9,1                        | 8         | 0.25%   |
| Apple MacBookAir6,2                        | 8         | 0.25%   |
| HP Pavilion 17                             | 7         | 0.22%   |
| HP Laptop 15-da0xxx                        | 7         | 0.22%   |
| HP EliteBook 840 G6                        | 7         | 0.22%   |
| ASUS Zenbook 15 UM3504DA_UM3504DA          | 7         | 0.22%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2        | 6         | 0.19%   |
| HP ProBook 450 G3                          | 6         | 0.19%   |
| HP Pavilion Notebook                       | 6         | 0.19%   |
| HP Pavilion g6                             | 6         | 0.19%   |
| HP EliteBook 840 G3                        | 6         | 0.19%   |
| Dell Latitude E7440                        | 6         | 0.19%   |
| Dell Latitude E6430                        | 6         | 0.19%   |
| Dell Latitude E6400                        | 6         | 0.19%   |
| Dell Inspiron 1545                         | 6         | 0.19%   |
| Acer Nitro AN515-58                        | 6         | 0.19%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1        | 5         | 0.15%   |
| Lenovo G50-45 80E3                         | 5         | 0.15%   |
| HUAWEI BoDE-WXX9                           | 5         | 0.15%   |
| HP Victus by Laptop 16-e0xxx               | 5         | 0.15%   |
| HP ProBook 4540s                           | 5         | 0.15%   |
| HP Laptop 17-cp0xxx                        | 5         | 0.15%   |
| HP EliteBook 840 G5                        | 5         | 0.15%   |
| HP 250 G8 Notebook PC                      | 5         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 349       | 10.78%  |
| Dell Latitude         | 184       | 5.69%   |
| Acer Aspire           | 158       | 4.88%   |
| Lenovo IdeaPad        | 147       | 4.54%   |
| Dell Inspiron         | 119       | 3.68%   |
| ASUS VivoBook         | 112       | 3.46%   |
| HP Pavilion           | 100       | 3.09%   |
| HP ProBook            | 82        | 2.53%   |
| HP Laptop             | 81        | 2.5%    |
| HP EliteBook          | 80        | 2.47%   |
| Valve Jupiter         | 75        | 2.32%   |
| Toshiba Satellite     | 49        | 1.51%   |
| Lenovo Legion         | 47        | 1.45%   |
| ASUS ROG              | 46        | 1.42%   |
| Dell Precision        | 45        | 1.39%   |
| Dell XPS              | 44        | 1.36%   |
| Unknown               | 44        | 1.36%   |
| Acer Nitro            | 42        | 1.3%    |
| ASUS ASUS             | 41        | 1.27%   |
| Lenovo ThinkBook      | 31        | 0.96%   |
| HP ZBook              | 30        | 0.93%   |
| ASUS Zenbook          | 29        | 0.9%    |
| Fujitsu LIFEBOOK      | 28        | 0.87%   |
| Framework Laptop      | 25        | 0.77%   |
| Dell Vostro           | 24        | 0.74%   |
| Acer Swift            | 23        | 0.71%   |
| Valve Galileo         | 22        | 0.68%   |
| HP Notebook           | 22        | 0.68%   |
| Lenovo Yoga           | 18        | 0.56%   |
| HP Compaq             | 17        | 0.53%   |
| HP Victus             | 15        | 0.46%   |
| HP ENVY               | 15        | 0.46%   |
| Packard Bell EasyNote | 14        | 0.43%   |
| HP 255                | 14        | 0.43%   |
| HP OMEN               | 13        | 0.4%    |
| HP 250                | 13        | 0.4%    |
| Lenovo V15            | 12        | 0.37%   |
| Apple MacBookPro11    | 12        | 0.37%   |
| Apple MacBookAir7     | 12        | 0.37%   |
| HP 15                 | 10        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2023    | 403       | 12.45%  |
| 2021    | 337       | 10.41%  |
| 2022    | 289       | 8.93%   |
| 2020    | 271       | 8.37%   |
| 2019    | 222       | 6.86%   |
| 2013    | 219       | 6.77%   |
| 2018    | 206       | 6.37%   |
| 2012    | 197       | 6.09%   |
| 2011    | 178       | 5.5%    |
| 2015    | 149       | 4.6%    |
| 2017    | 145       | 4.48%   |
| 2016    | 144       | 4.45%   |
| 2014    | 134       | 4.14%   |
| 2010    | 106       | 3.28%   |
| 2009    | 83        | 2.56%   |
| 2008    | 79        | 2.44%   |
| 2007    | 54        | 1.67%   |
| 2006    | 9         | 0.28%   |
| Unknown | 8         | 0.25%   |
| 2005    | 3         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3236      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2942      | 90.91%  |
| Enabled  | 294       | 9.09%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3189      | 98.55%  |
| Yes  | 47        | 1.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 922       | 28.49%  |
| 8.01-16.0   | 631       | 19.5%   |
| 16.01-24.0  | 581       | 17.95%  |
| 3.01-4.0    | 541       | 16.72%  |
| 32.01-64.0  | 309       | 9.55%   |
| 24.01-32.0  | 84        | 2.6%    |
| 1.01-2.0    | 64        | 1.98%   |
| 64.01-256.0 | 53        | 1.64%   |
| 2.01-3.0    | 41        | 1.27%   |
| 0.51-1.0    | 6         | 0.19%   |
| 0.01-0.5    | 3         | 0.09%   |
| Unknown     | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 941       | 29.08%  |
| 2.01-3.0   | 836       | 25.83%  |
| 4.01-8.0   | 637       | 19.68%  |
| 3.01-4.0   | 506       | 15.64%  |
| 8.01-16.0  | 152       | 4.7%    |
| 0.51-1.0   | 125       | 3.86%   |
| 0.01-0.5   | 19        | 0.59%   |
| 16.01-24.0 | 15        | 0.46%   |
| 32.01-64.0 | 2         | 0.06%   |
| 24.01-32.0 | 2         | 0.06%   |
| Unknown    | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2343      | 72.4%   |
| 2      | 771       | 23.83%  |
| 3      | 86        | 2.66%   |
| 4      | 16        | 0.49%   |
| 0      | 16        | 0.49%   |
| 6      | 2         | 0.06%   |
| 7      | 1         | 0.03%   |
| 5      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2334      | 72.13%  |
| Yes       | 902       | 27.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2444      | 75.53%  |
| No        | 792       | 24.47%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3192      | 98.64%  |
| No        | 44        | 1.36%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2672      | 82.57%  |
| No        | 564       | 17.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 500       | 15.45%  |
| Germany     | 370       | 11.43%  |
| Russia      | 232       | 7.17%   |
| France      | 188       | 5.81%   |
| Italy       | 176       | 5.44%   |
| Poland      | 134       | 4.14%   |
| Brazil      | 128       | 3.96%   |
| Canada      | 126       | 3.89%   |
| UK          | 102       | 3.15%   |
| Spain       | 101       | 3.12%   |
| Hungary     | 91        | 2.81%   |
| India       | 85        | 2.63%   |
| Netherlands | 49        | 1.51%   |
| Mexico      | 49        | 1.51%   |
| Austria     | 47        | 1.45%   |
| Romania     | 42        | 1.3%    |
| Switzerland | 41        | 1.27%   |
| Czechia     | 34        | 1.05%   |
| Australia   | 34        | 1.05%   |
| Turkey      | 32        | 0.99%   |
| Portugal    | 30        | 0.93%   |
| Sweden      | 24        | 0.74%   |
| Indonesia   | 24        | 0.74%   |
| Colombia    | 24        | 0.74%   |
| Belgium     | 24        | 0.74%   |
| Argentina   | 24        | 0.74%   |
| Greece      | 22        | 0.68%   |
| China       | 22        | 0.68%   |
| Bulgaria    | 21        | 0.65%   |
| Norway      | 20        | 0.62%   |
| Slovakia    | 19        | 0.59%   |
| Finland     | 19        | 0.59%   |
| Japan       | 17        | 0.53%   |
| Israel      | 16        | 0.49%   |
| Belarus     | 15        | 0.46%   |
| Taiwan      | 14        | 0.43%   |
| Chile       | 14        | 0.43%   |
| Philippines | 13        | 0.4%    |
| Ireland     | 12        | 0.37%   |
| Denmark     | 12        | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Moscow        | 62        | 1.92%   |
| Berlin        | 37        | 1.14%   |
| Warsaw        | 34        | 1.05%   |
| Milan         | 31        | 0.96%   |
| Roubaix       | 28        | 0.87%   |
| Budapest      | 25        | 0.77%   |
| Vienna        | 24        | 0.74%   |
| Paris         | 24        | 0.74%   |
| Munich        | 24        | 0.74%   |
| Sao Paulo     | 23        | 0.71%   |
| St Petersburg | 19        | 0.59%   |
| Prague        | 17        | 0.53%   |
| Istanbul      | 17        | 0.53%   |
| Hamburg       | 16        | 0.49%   |
| Toronto       | 15        | 0.46%   |
| Los Angeles   | 15        | 0.46%   |
| Madrid        | 14        | 0.43%   |
| Helsinki      | 14        | 0.43%   |
| Bucharest     | 14        | 0.43%   |
| Rome          | 13        | 0.4%    |
| Québec       | 13        | 0.4%    |
| Poznan        | 13        | 0.4%    |
| Sofia         | 12        | 0.37%   |
| Milano        | 12        | 0.37%   |
| Amsterdam     | 12        | 0.37%   |
| Cologne       | 11        | 0.34%   |
| Sydney        | 10        | 0.31%   |
| New York      | 10        | 0.31%   |
| Montreal      | 10        | 0.31%   |
| Mexico City   | 10        | 0.31%   |
| Dublin        | 10        | 0.31%   |
| Bogotá       | 10        | 0.31%   |
| Bengaluru     | 10        | 0.31%   |
| Barcelona     | 10        | 0.31%   |
| Zurich        | 9         | 0.28%   |
| Portland      | 9         | 0.28%   |
| Minsk         | 9         | 0.28%   |
| Buenos Aires  | 9         | 0.28%   |
| Brussels      | 9         | 0.28%   |
| Yekaterinburg | 8         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 688       | 758    | 17.05%  |
| SanDisk                     | 301       | 319    | 7.46%   |
| WDC                         | 297       | 305    | 7.36%   |
| Seagate                     | 270       | 275    | 6.69%   |
| Unknown                     | 226       | 246    | 5.6%    |
| Toshiba                     | 211       | 216    | 5.23%   |
| Kingston                    | 196       | 200    | 4.86%   |
| SK hynix                    | 191       | 193    | 4.73%   |
| Micron Technology           | 167       | 170    | 4.14%   |
| Crucial                     | 135       | 137    | 3.35%   |
| Intel                       | 126       | 136    | 3.12%   |
| Hitachi                     | 75        | 75     | 1.86%   |
| HGST                        | 74        | 74     | 1.83%   |
| Apple                       | 73        | 86     | 1.81%   |
| Phison Electronics          | 62        | 62     | 1.54%   |
| Unknown                     | 56        | 56     | 1.39%   |
| KIOXIA                      | 53        | 53     | 1.31%   |
| A-DATA Technology           | 52        | 53     | 1.29%   |
| Micron/Crucial Technology   | 46        | 50     | 1.14%   |
| China                       | 46        | 47     | 1.14%   |
| Kingston Technology Company | 40        | 40     | 0.99%   |
| SPCC                        | 31        | 31     | 0.77%   |
| Silicon Motion              | 29        | 29     | 0.72%   |
| Intenso                     | 27        | 27     | 0.67%   |
| MAXIO Technology (Hangzhou) | 25        | 26     | 0.62%   |
| Phison                      | 23        | 24     | 0.57%   |
| PNY                         | 18        | 18     | 0.45%   |
| Netac                       | 18        | 19     | 0.45%   |
| Transcend                   | 17        | 17     | 0.42%   |
| Lexar                       | 17        | 18     | 0.42%   |
| ADATA Technology            | 16        | 16     | 0.4%    |
| LITEON                      | 15        | 15     | 0.37%   |
| Team                        | 14        | 14     | 0.35%   |
| Patriot                     | 14        | 14     | 0.35%   |
| LITEONIT                    | 14        | 14     | 0.35%   |
| JMicron Technology          | 14        | 15     | 0.35%   |
| GOODRAM                     | 13        | 13     | 0.32%   |
| Fujitsu                     | 13        | 13     | 0.32%   |
| SSSTC                       | 11        | 11     | 0.27%   |
| KingSpec                    | 11        | 11     | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 86        | 2.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 66        | 1.58%   |
| Unknown                                             | 56        | 1.34%   |
| Kingston SA400S37240G 240GB SSD                     | 46        | 1.1%    |
| Seagate ST1000LM035-1RK172 1TB                      | 42        | 1.01%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 41        | 0.98%   |
| Unknown MMC Card  32GB                              | 37        | 0.89%   |
| Unknown MMC Card  64GB                              | 35        | 0.84%   |
| Unknown MMC Card  128GB                             | 33        | 0.79%   |
| Toshiba MQ01ABD100 1TB                              | 30        | 0.72%   |
| Seagate ST500LT012-1DG142 500GB                     | 27        | 0.65%   |
| Phison PS5013 E13 NVMe Controller 512GB             | 26        | 0.62%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                 | 26        | 0.62%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB             | 26        | 0.62%   |
| Toshiba MQ01ABF050 500GB                            | 24        | 0.58%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 22        | 0.53%   |
| Intel SSDPEKNU512GZ 512GB                           | 22        | 0.53%   |
| Seagate ST9500325AS 500GB                           | 21        | 0.5%    |
| Kingston SA400S37480G 480GB SSD                     | 21        | 0.5%    |
| Unknown MMC Card  512GB                             | 20        | 0.48%   |
| Intel SSD 660P Series 1TB                           | 20        | 0.48%   |
| HGST HTS721010A9E630 1TB                            | 20        | 0.48%   |
| Crucial CT1000MX500SSD1 1TB                         | 19        | 0.46%   |
| Toshiba MQ04ABF100 1TB                              | 18        | 0.43%   |
| Micron 2400_MTFDKBA512QFM 512GB                     | 18        | 0.43%   |
| Kingston SA400S37120G 120GB SSD                     | 18        | 0.43%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB      | 17        | 0.41%   |
| SanDisk NVMe SSD Drive 1TB                          | 17        | 0.41%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 256GB  | 17        | 0.41%   |
| Crucial CT240BX500SSD1 240GB                        | 17        | 0.41%   |
| SK hynix BC511 512GB                                | 16        | 0.38%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 128GB     | 16        | 0.38%   |
| SanDisk NVMe SSD Drive 512GB                        | 16        | 0.38%   |
| Samsung SSD 870 EVO 500GB                           | 16        | 0.38%   |
| Crucial CT500MX500SSD1 500GB                        | 16        | 0.38%   |
| Samsung SSD 980 1TB                                 | 15        | 0.36%   |
| HGST HTS541010A9E680 1TB                            | 15        | 0.36%   |
| Unknown MMC Card  256GB                             | 14        | 0.34%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 14        | 0.34%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 250GB | 14        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 262       | 266    | 30.64%  |
| WDC                 | 201       | 204    | 23.51%  |
| Toshiba             | 154       | 155    | 18.01%  |
| Hitachi             | 75        | 75     | 8.77%   |
| HGST                | 74        | 74     | 8.65%   |
| Samsung Electronics | 19        | 19     | 2.22%   |
| Fujitsu             | 13        | 13     | 1.52%   |
| SABRENT             | 10        | 11     | 1.17%   |
| Unknown             | 9         | 9      | 1.05%   |
| Apple               | 7         | 7      | 0.82%   |
| USB3.0              | 5         | 5      | 0.58%   |
| ASMT                | 5         | 6      | 0.58%   |
| Intenso             | 3         | 3      | 0.35%   |
| External            | 3         | 3      | 0.35%   |
| USB                 | 2         | 2      | 0.23%   |
| TO Exter            | 2         | 2      | 0.23%   |
| KESU                | 2         | 2      | 0.23%   |
| SSK                 | 1         | 1      | 0.12%   |
| LIO-ORG             | 1         | 4      | 0.12%   |
| LaCie               | 1         | 1      | 0.12%   |
| Initio              | 1         | 1      | 0.12%   |
| Inateck             | 1         | 1      | 0.12%   |
| Generic-            | 1         | 1      | 0.12%   |
| AXAGON              | 1         | 1      | 0.12%   |
| Apricorn            | 1         | 1      | 0.12%   |
| Unknown             | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 232       | 245    | 19.24%  |
| Kingston            | 151       | 153    | 12.52%  |
| Crucial             | 118       | 119    | 9.78%   |
| SanDisk             | 82        | 86     | 6.8%    |
| WDC                 | 54        | 54     | 4.48%   |
| China               | 46        | 47     | 3.81%   |
| Apple               | 40        | 40     | 3.32%   |
| A-DATA Technology   | 38        | 39     | 3.15%   |
| Intel               | 31        | 31     | 2.57%   |
| SPCC                | 29        | 29     | 2.4%    |
| Micron Technology   | 26        | 26     | 2.16%   |
| Intenso             | 22        | 22     | 1.82%   |
| Toshiba             | 21        | 21     | 1.74%   |
| SK hynix            | 20        | 20     | 1.66%   |
| PNY                 | 18        | 18     | 1.49%   |
| Transcend           | 14        | 14     | 1.16%   |
| Netac               | 14        | 14     | 1.16%   |
| LITEONIT            | 14        | 14     | 1.16%   |
| LITEON              | 13        | 13     | 1.08%   |
| GOODRAM             | 12        | 12     | 1%      |
| Patriot             | 11        | 11     | 0.91%   |
| KingSpec            | 11        | 11     | 0.91%   |
| Team                | 10        | 10     | 0.83%   |
| Apacer              | 10        | 10     | 0.83%   |
| Lexar               | 9         | 10     | 0.75%   |
| JMicron Technology  | 8         | 9      | 0.66%   |
| Phison              | 6         | 6      | 0.5%    |
| Hewlett-Packard     | 5         | 5      | 0.41%   |
| ASMT                | 5         | 5      | 0.41%   |
| Unknown             | 5         | 5      | 0.41%   |
| OCZ                 | 4         | 4      | 0.33%   |
| Gigabyte Technology | 4         | 4      | 0.33%   |
| Fanxiang            | 4         | 4      | 0.33%   |
| Dogfish             | 4         | 4      | 0.33%   |
| XrayDisk            | 3         | 3      | 0.25%   |
| Wibtek              | 3         | 3      | 0.25%   |
| Seagate             | 3         | 3      | 0.25%   |
| Plextor             | 3         | 3      | 0.25%   |
| KIOXIA-EXCERIA      | 3         | 3      | 0.25%   |
| HS-SSD-E100         | 3         | 3      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1578      | 1785   | 41.17%  |
| SSD     | 1127      | 1232   | 29.4%   |
| HDD     | 823       | 868    | 21.47%  |
| MMC     | 245       | 266    | 6.39%   |
| Unknown | 60        | 62     | 1.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1731      | 1984   | 46.65%  |
| NVMe | 1578      | 1776   | 42.52%  |
| MMC  | 245       | 266    | 6.6%    |
| SAS  | 157       | 187    | 4.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1256      | 1371   | 64.15%  |
| 0.51-1.0   | 568       | 590    | 29.01%  |
| 1.01-2.0   | 114       | 119    | 5.82%   |
| 3.01-4.0   | 14        | 14     | 0.72%   |
| 4.01-10.0  | 5         | 5      | 0.26%   |
| 2.01-3.0   | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 805       | 24.88%  |
| 251-500        | 782       | 24.17%  |
| 501-1000       | 574       | 17.74%  |
| 1001-2000      | 255       | 7.88%   |
| 1-20           | 248       | 7.66%   |
| 51-100         | 185       | 5.72%   |
| More than 3000 | 118       | 3.65%   |
| Unknown        | 115       | 3.55%   |
| 21-50          | 89        | 2.75%   |
| 2001-3000      | 65        | 2.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1133      | 35.01%  |
| 21-50          | 569       | 17.58%  |
| 101-250        | 486       | 15.02%  |
| 51-100         | 401       | 12.39%  |
| 251-500        | 260       | 8.03%   |
| 501-1000       | 166       | 5.13%   |
| Unknown        | 115       | 3.55%   |
| 1001-2000      | 65        | 2.01%   |
| 2001-3000      | 19        | 0.59%   |
| More than 3000 | 17        | 0.53%   |
| 0              | 5         | 0.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB               | 9         | 9      | 3.91%   |
| Toshiba MQ01ABF050 500GB                | 8         | 8      | 3.48%   |
| Seagate ST500LT012-1DG142 500GB         | 8         | 8      | 3.48%   |
| HGST HTS541010A9E680 1TB                | 7         | 7      | 3.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 4         | 4      | 1.74%   |
| HGST HTS725050A7E630 500GB              | 4         | 4      | 1.74%   |
| HGST HTS545050A7E680 500GB              | 4         | 4      | 1.74%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 3         | 3      | 1.3%    |
| Seagate ST9320325AS 320GB               | 3         | 3      | 1.3%    |
| Hitachi HTS727575A9E364 752GB           | 3         | 3      | 1.3%    |
| HGST HTS545050A7E380 500GB              | 3         | 3      | 1.3%    |
| WDC WD5000LPVX-22V0TT0 500GB            | 2         | 2      | 0.87%   |
| WDC WD5000LPLX-60ZNTT1 500GB            | 2         | 2      | 0.87%   |
| WDC WD10SPZX-60Z10T0 1TB                | 2         | 2      | 0.87%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 2      | 0.87%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 2         | 2      | 0.87%   |
| Seagate ST9500420AS 500GB               | 2         | 2      | 0.87%   |
| Seagate ST500LT012-9WS142 500GB         | 2         | 2      | 0.87%   |
| Seagate ST500LM021-1KJ152 500GB         | 2         | 2      | 0.87%   |
| Seagate ST2000LM007-1R8174 2TB          | 2         | 2      | 0.87%   |
| Seagate ST2000LM003 HN-M201RAD 2TB      | 2         | 2      | 0.87%   |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 2      | 0.87%   |
| SanDisk SSD PLUS 480GB                  | 2         | 2      | 0.87%   |
| Kingston SA400S37960G 960GB SSD         | 2         | 2      | 0.87%   |
| Kingston SA400S37240G 240GB SSD         | 2         | 2      | 0.87%   |
| Hitachi HTS723232A7A364 320GB           | 2         | 2      | 0.87%   |
| Hitachi HTS547564A9E384 640GB           | 2         | 2      | 0.87%   |
| Hitachi HTS545050A7E380 500GB           | 2         | 2      | 0.87%   |
| HGST HTS721010A9E630 1TB                | 2         | 2      | 0.87%   |
| A-DATA Technology SU800 256GB SSD       | 2         | 2      | 0.87%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 1      | 0.43%   |
| WDC WDS100T2G0A-00JH30 1TB SSD          | 1         | 1      | 0.43%   |
| WDC WD7500BPVX-60JC3T0 752GB            | 1         | 1      | 0.43%   |
| WDC WD7500BPVT-60HXZT3 752GB            | 1         | 1      | 0.43%   |
| WDC WD5000LPCX-75VHAT0 500GB            | 1         | 1      | 0.43%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 1         | 1      | 0.43%   |
| WDC WD5000LPCX-24C6HT0 500GB            | 1         | 1      | 0.43%   |
| WDC WD5000LPCX-00VHAT0 500GB            | 1         | 1      | 0.43%   |
| WDC WD5000BPKT-75PK4T0 500GB            | 1         | 1      | 0.43%   |
| WDC WD5000BEVT-22A0RT0 500GB            | 1         | 1      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 53     | 23.25%  |
| WDC                 | 40        | 41     | 17.54%  |
| Toshiba             | 22        | 23     | 9.65%   |
| HGST                | 21        | 21     | 9.21%   |
| Hitachi             | 17        | 17     | 7.46%   |
| Samsung Electronics | 8         | 8      | 3.51%   |
| Intel               | 8         | 8      | 3.51%   |
| Kingston            | 7         | 7      | 3.07%   |
| SK hynix            | 6         | 6      | 2.63%   |
| SanDisk             | 6         | 6      | 2.63%   |
| Fujitsu             | 5         | 5      | 2.19%   |
| Micron Technology   | 4         | 4      | 1.75%   |
| A-DATA Technology   | 4         | 4      | 1.75%   |
| Crucial             | 3         | 3      | 1.32%   |
| China               | 3         | 3      | 1.32%   |
| LITEONIT            | 2         | 2      | 0.88%   |
| Apple               | 2         | 2      | 0.88%   |
| UMIS                | 1         | 1      | 0.44%   |
| Transcend           | 1         | 1      | 0.44%   |
| Timetec             | 1         | 1      | 0.44%   |
| Team                | 1         | 1      | 0.44%   |
| Silicon Motion      | 1         | 1      | 0.44%   |
| SABRENT             | 1         | 1      | 0.44%   |
| Phison              | 1         | 1      | 0.44%   |
| OCZ                 | 1         | 1      | 0.44%   |
| Netac               | 1         | 1      | 0.44%   |
| Neo                 | 1         | 1      | 0.44%   |
| Lexar               | 1         | 1      | 0.44%   |
| Kimtigo             | 1         | 1      | 0.44%   |
| Intenso             | 1         | 1      | 0.44%   |
| HS-SSD-C160         | 1         | 1      | 0.44%   |
| Dogfish             | 1         | 1      | 0.44%   |
| Aura                | 1         | 1      | 0.44%   |
| Apacer              | 1         | 1      | 0.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 53     | 34.42%  |
| WDC                 | 34        | 35     | 22.08%  |
| Toshiba             | 21        | 22     | 13.64%  |
| HGST                | 21        | 21     | 13.64%  |
| Hitachi             | 17        | 17     | 11.04%  |
| Fujitsu             | 5         | 5      | 3.25%   |
| Samsung Electronics | 2         | 2      | 1.3%    |
| SABRENT             | 1         | 1      | 0.65%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 151       | 156    | 67.11%  |
| SSD  | 57        | 57     | 25.33%  |
| NVMe | 17        | 17     | 7.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)

![Failed Drives](./images/line_chart/drive_failed.svg)

| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 25%     |
| Samsung Electronics HM160HC 160GB  | 1         | 1      | 25%     |
| JMicron Technology Tech 250GB      | 1         | 1      | 25%     |
| HGST HTS541010A9E680 1TB           | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)

![Failed Drive Vendor](./images/line_chart/drive_failed_vendor.svg)

| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |
| JMicron Technology  | 1         | 1      | 25%     |
| HGST                | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)

![Drive Status](./images/line_chart/drive_status.svg)

| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1696      | 2200   | 50.07%  |
| Works    | 1465      | 1779   | 43.25%  |
| Malfunc  | 222       | 230    | 6.55%   |
| Failed   | 4         | 4      | 0.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1994      | 50.65%  |
| Samsung Electronics                     | 474       | 12.04%  |
| AMD                                     | 303       | 7.7%    |
| SanDisk                                 | 261       | 6.63%   |
| SK hynix                                | 169       | 4.29%   |
| Micron Technology                       | 142       | 3.61%   |
| Kingston Technology Company             | 86        | 2.18%   |
| Phison Electronics                      | 83        | 2.11%   |
| Micron/Crucial Technology               | 63        | 1.6%    |
| KIOXIA                                  | 52        | 1.32%   |
| Toshiba America Info Systems            | 39        | 0.99%   |
| Silicon Motion                          | 37        | 0.94%   |
| MAXIO Technology (Hangzhou)             | 37        | 0.94%   |
| ADATA Technology                        | 28        | 0.71%   |
| Apple                                   | 22        | 0.56%   |
| Nvidia                                  | 18        | 0.46%   |
| Shenzhen Longsys Electronics            | 16        | 0.41%   |
| Union Memory (Shenzhen)                 | 15        | 0.38%   |
| Solid State Storage Technology          | 14        | 0.36%   |
| Solidigm                                | 12        | 0.3%    |
| Realtek Semiconductor                   | 12        | 0.3%    |
| Marvell Technology Group                | 10        | 0.25%   |
| INNOGRIT                                | 10        | 0.25%   |
| O2 Micro                                | 9         | 0.23%   |
| Netac Technology                        | 4         | 0.1%    |
| Transcend                               | 3         | 0.08%   |
| Silicon Integrated Systems [SiS]        | 3         | 0.08%   |
| Lite-On Technology                      | 3         | 0.08%   |
| Lenovo                                  | 3         | 0.08%   |
| Hosin Global Electronics                | 3         | 0.08%   |
| Biwin Storage Technology                | 3         | 0.08%   |
| Yangtze Memory Technologies             | 2         | 0.05%   |
| Shenzhen Unionmemory Information System | 2         | 0.05%   |
| ASMedia Technology                      | 2         | 0.05%   |
| VIA Technologies                        | 1         | 0.03%   |
| Seagate Technology                      | 1         | 0.03%   |
| Nextorage                               | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 264       | 6.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 213       | 5.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 197       | 4.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 168       | 4.03%   |
| Intel Volume Management Device NVMe RAID Controller                            | 164       | 3.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 146       | 3.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 142       | 3.4%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 135       | 3.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 106       | 2.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 98        | 2.35%   |
| Intel Tiger Lake-LP SATA Controller                                            | 84        | 2.01%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 83        | 1.99%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 82        | 1.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 79        | 1.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 64        | 1.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 60        | 1.44%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 57        | 1.37%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 54        | 1.29%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 51        | 1.22%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 49        | 1.17%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 48        | 1.15%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 46        | 1.1%    |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 44        | 1.05%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 43        | 1.03%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 42        | 1.01%   |
| Intel Comet Lake SATA AHCI Controller                                          | 42        | 1.01%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 41        | 0.98%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 38        | 0.91%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 33        | 0.79%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 32        | 0.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 32        | 0.77%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 32        | 0.77%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 31        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 31        | 0.74%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 30        | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 30        | 0.72%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 30        | 0.72%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 28        | 0.67%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 28        | 0.67%   |
| Intel SSD 660P Series                                                          | 28        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1927      | 48.09%  |
| NVMe | 1575      | 39.31%  |
| RAID | 390       | 9.73%   |
| IDE  | 115       | 2.87%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2513      | 77.66%  |
| AMD          | 717       | 22.16%  |
| Unknown      | 3         | 0.09%   |
| ARM          | 2         | 0.06%   |
| CentaurHauls | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Custom APU 0405                           | 97        | 3%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 58        | 1.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 41        | 1.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 38        | 1.17%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 37        | 1.14%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 35        | 1.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 32        | 0.99%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 32        | 0.99%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 30        | 0.93%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 30        | 0.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 30        | 0.93%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 30        | 0.93%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 29        | 0.9%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 28        | 0.87%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 27        | 0.83%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 27        | 0.83%   |
| Intel 12th Gen Core i7-12700H                 | 27        | 0.83%   |
| Intel 12th Gen Core i5-1235U                  | 27        | 0.83%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 27        | 0.83%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 26        | 0.8%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 25        | 0.77%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 25        | 0.77%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 25        | 0.77%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 24        | 0.74%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 24        | 0.74%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 23        | 0.71%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 22        | 0.68%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 22        | 0.68%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 21        | 0.65%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 21        | 0.65%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 21        | 0.65%   |
| Intel 12th Gen Core i7-1255U                  | 21        | 0.65%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 20        | 0.62%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 20        | 0.62%   |
| Intel 13th Gen Core i9-13900H                 | 20        | 0.62%   |
| Intel 12th Gen Core i5-12450H                 | 19        | 0.59%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 19        | 0.59%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 18        | 0.56%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 17        | 0.53%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 17        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 707       | 21.85%  |
| Other                   | 654       | 20.21%  |
| Intel Core i7           | 546       | 16.87%  |
| Intel Core i3           | 240       | 7.42%   |
| Intel Celeron           | 187       | 5.78%   |
| AMD Ryzen 7             | 179       | 5.53%   |
| AMD Ryzen 5             | 161       | 4.98%   |
| Intel Core 2 Duo        | 100       | 3.09%   |
| Intel Pentium           | 62        | 1.92%   |
| AMD Ryzen 3             | 39        | 1.21%   |
| AMD Ryzen 9             | 38        | 1.17%   |
| Intel Atom              | 31        | 0.96%   |
| AMD Ryzen 7 PRO         | 30        | 0.93%   |
| Intel Pentium Dual-Core | 24        | 0.74%   |
| AMD A6                  | 24        | 0.74%   |
| AMD A8                  | 19        | 0.59%   |
| AMD A4                  | 17        | 0.53%   |
| AMD E1                  | 16        | 0.49%   |
| AMD A10                 | 14        | 0.43%   |
| Intel Pentium Silver    | 12        | 0.37%   |
| Intel Pentium Dual      | 11        | 0.34%   |
| AMD E2                  | 10        | 0.31%   |
| Intel Genuine           | 8         | 0.25%   |
| AMD E                   | 8         | 0.25%   |
| AMD Athlon II Dual-Core | 8         | 0.25%   |
| Intel Xeon              | 7         | 0.22%   |
| AMD Ryzen 5 PRO         | 7         | 0.22%   |
| Intel Core 2            | 6         | 0.19%   |
| Intel Celeron Dual-Core | 6         | 0.19%   |
| Intel Core m3           | 5         | 0.15%   |
| Intel Core i9           | 5         | 0.15%   |
| AMD Athlon              | 5         | 0.15%   |
| Intel Core M            | 4         | 0.12%   |
| Intel Celeron M         | 4         | 0.12%   |
| AMD Turion 64 X2 Mobile | 4         | 0.12%   |
| AMD PRO A10             | 4         | 0.12%   |
| Intel Pentium M         | 3         | 0.09%   |
| Intel Pentium Gold      | 3         | 0.09%   |
| Intel Core m5           | 3         | 0.09%   |
| AMD Phenom II           | 3         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1398      | 43.2%   |
| 4      | 982       | 30.35%  |
| 8      | 289       | 8.93%   |
| 6      | 245       | 7.57%   |
| 14     | 98        | 3.03%   |
| 10     | 97        | 3%      |
| 12     | 59        | 1.82%   |
| 1      | 39        | 1.21%   |
| 24     | 17        | 0.53%   |
| 16     | 10        | 0.31%   |
| 5      | 2         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3236      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2566      | 79.3%   |
| 1      | 669       | 20.67%  |
| 4      | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3217      | 99.41%  |
| 32-bit         | 11        | 0.34%   |
| 64-bit         | 4         | 0.12%   |
| Unknown        | 4         | 0.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2023      | 62.52%  |
| 0x306a9    | 70        | 2.16%   |
| 0x206a7    | 70        | 2.16%   |
| 0x0a50000d | 50        | 1.55%   |
| 0x806c1    | 45        | 1.39%   |
| 0x406e3    | 43        | 1.33%   |
| 0x0a50000c | 42        | 1.3%    |
| 0x0a704103 | 38        | 1.17%   |
| 0x08108109 | 38        | 1.17%   |
| 0x806ec    | 36        | 1.11%   |
| 0x306c3    | 35        | 1.08%   |
| 0x0a404102 | 34        | 1.05%   |
| 0x08608103 | 33        | 1.02%   |
| 0x1067a    | 32        | 0.99%   |
| 0x40651    | 31        | 0.96%   |
| 0x806ea    | 30        | 0.93%   |
| 0x306d4    | 29        | 0.9%    |
| 0x20655    | 25        | 0.77%   |
| 0x806e9    | 23        | 0.71%   |
| 0x08600106 | 22        | 0.68%   |
| 0x906a3    | 21        | 0.65%   |
| 0x6fd      | 18        | 0.56%   |
| 0x906ea    | 17        | 0.53%   |
| 0xb06a2    | 16        | 0.49%   |
| 0x906a4    | 15        | 0.46%   |
| 0xa0652    | 14        | 0.43%   |
| 0x706a8    | 14        | 0.43%   |
| 0x506c9    | 14        | 0.43%   |
| 0x706e5    | 13        | 0.4%    |
| 0x30678    | 13        | 0.4%    |
| 0x20652    | 13        | 0.4%    |
| 0x07030105 | 12        | 0.37%   |
| 0x06006705 | 12        | 0.37%   |
| 0x10676    | 11        | 0.34%   |
| 0x806d1    | 10        | 0.31%   |
| 0x706a1    | 10        | 0.31%   |
| 0x08608104 | 10        | 0.31%   |
| 0x05000119 | 10        | 0.31%   |
| 0x906e9    | 9         | 0.28%   |
| 0x08608102 | 9         | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 490       | 15.14%  |
| Unknown          | 398       | 12.3%   |
| Haswell          | 220       | 6.8%    |
| Alderlake Hybrid | 215       | 6.64%   |
| SandyBridge      | 195       | 6.03%   |
| IvyBridge        | 194       | 6%      |
| TigerLake        | 192       | 5.93%   |
| Skylake          | 166       | 5.13%   |
| Zen 3            | 129       | 3.99%   |
| Penryn           | 112       | 3.46%   |
| Broadwell        | 102       | 3.15%   |
| Westmere         | 95        | 2.94%   |
| Icelake          | 80        | 2.47%   |
| Goldmont plus    | 77        | 2.38%   |
| Silvermont       | 69        | 2.13%   |
| Zen+             | 66        | 2.04%   |
| Zen 2            | 64        | 1.98%   |
| CometLake        | 64        | 1.98%   |
| Core             | 52        | 1.61%   |
| Excavator        | 43        | 1.33%   |
| Goldmont         | 33        | 1.02%   |
| Puma             | 29        | 0.9%    |
| K10              | 19        | 0.59%   |
| Bobcat           | 19        | 0.59%   |
| Zen              | 18        | 0.56%   |
| Bonnell          | 17        | 0.53%   |
| Piledriver       | 14        | 0.43%   |
| Jaguar           | 14        | 0.43%   |
| Tremont          | 12        | 0.37%   |
| P6               | 8         | 0.25%   |
| K8 Hammer        | 7         | 0.22%   |
| Gracemont        | 7         | 0.22%   |
| K10 Llano        | 6         | 0.19%   |
| Nehalem          | 4         | 0.12%   |
| Steamroller      | 3         | 0.09%   |
| K8 & K10 hybrid  | 3         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2329      | 57.15%  |
| Nvidia                           | 879       | 21.57%  |
| AMD                              | 862       | 21.15%  |
| Silicon Integrated Systems [SiS] | 3         | 0.07%   |
| Zhaoxin                          | 1         | 0.02%   |
| VIA Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 183       | 4.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 170       | 4.07%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 153       | 3.66%   |
| Intel UHD Graphics 620                                                                   | 118       | 2.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 116       | 2.78%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 104       | 2.49%   |
| Intel HD Graphics 620                                                                    | 88        | 2.11%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 87        | 2.08%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 85        | 2.04%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 84        | 2.01%   |
| Intel HD Graphics 5500                                                                   | 76        | 1.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 75        | 1.8%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 75        | 1.8%    |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 75        | 1.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 74        | 1.77%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 73        | 1.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 73        | 1.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 71        | 1.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 71        | 1.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 66        | 1.58%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 64        | 1.53%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 63        | 1.51%   |
| AMD Lucienne                                                                             | 63        | 1.51%   |
| AMD Phoenix1                                                                             | 56        | 1.34%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 51        | 1.22%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 47        | 1.13%   |
| AMD Rembrandt [Radeon 680M]                                                              | 42        | 1.01%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 39        | 0.93%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 39        | 0.93%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 38        | 0.91%   |
| AMD Barcelo                                                                              | 38        | 0.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 35        | 0.84%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 34        | 0.81%   |
| Intel HD Graphics 530                                                                    | 34        | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 34        | 0.81%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 33        | 0.79%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 31        | 0.74%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                          | 30        | 0.72%   |
| Intel HD Graphics 630                                                                    | 29        | 0.69%   |
| Intel HD Graphics 500                                                                    | 29        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 1552      | 47.96%  |
| Intel + Nvidia         | 627       | 19.38%  |
| 1 x AMD                | 595       | 18.39%  |
| 1 x Nvidia             | 135       | 4.17%   |
| AMD + Nvidia           | 111       | 3.43%   |
| Intel + AMD            | 99        | 3.06%   |
| 2 x AMD                | 57        | 1.76%   |
| 2 x Intel              | 42        | 1.3%    |
| Other                  | 8         | 0.25%   |
| 2 x Nvidia             | 3         | 0.09%   |
| 1 x SiS                | 3         | 0.09%   |
| 2 x Intel + 1 x Nvidia | 2         | 0.06%   |
| 1 x Zhaoxin            | 1         | 0.03%   |
| 1 x VIA                | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2766      | 85.48%  |
| Proprietary | 397       | 12.27%  |
| Unknown     | 73        | 2.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2356      | 72.81%  |
| 0.01-0.5   | 331       | 10.23%  |
| 1.01-2.0   | 205       | 6.33%   |
| 0.51-1.0   | 130       | 4.02%   |
| 3.01-4.0   | 127       | 3.92%   |
| 7.01-8.0   | 37        | 1.14%   |
| 5.01-6.0   | 33        | 1.02%   |
| 2.01-3.0   | 9         | 0.28%   |
| 8.01-16.0  | 8         | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 659       | 17.98%  |
| BOE                     | 570       | 15.55%  |
| Chimei Innolux          | 520       | 14.19%  |
| LG Display              | 437       | 11.92%  |
| Samsung Electronics     | 357       | 9.74%   |
| Apple                   | 103       | 2.81%   |
| Valve                   | 94        | 2.56%   |
| Dell                    | 87        | 2.37%   |
| Goldstar                | 81        | 2.21%   |
| Sharp                   | 79        | 2.16%   |
| Lenovo                  | 70        | 1.91%   |
| Chi Mei Optoelectronics | 69        | 1.88%   |
| PANDA                   | 62        | 1.69%   |
| Hewlett-Packard         | 38        | 1.04%   |
| CSO                     | 38        | 1.04%   |
| Philips                 | 34        | 0.93%   |
| InfoVision              | 33        | 0.9%    |
| Acer                    | 30        | 0.82%   |
| AOC                     | 20        | 0.55%   |
| LG Philips              | 19        | 0.52%   |
| ASUSTek Computer        | 19        | 0.52%   |
| Ancor Communications    | 19        | 0.52%   |
| Sony                    | 17        | 0.46%   |
| TMX                     | 14        | 0.38%   |
| BenQ                    | 13        | 0.35%   |
| Iiyama                  | 12        | 0.33%   |
| ViewSonic               | 11        | 0.3%    |
| Panasonic               | 11        | 0.3%    |
| HannStar                | 7         | 0.19%   |
| CPT                     | 7         | 0.19%   |
| Vizio                   | 5         | 0.14%   |
| Mi                      | 5         | 0.14%   |
| HKC                     | 5         | 0.14%   |
| Eizo                    | 5         | 0.14%   |
| Toshiba                 | 4         | 0.11%   |
| STA                     | 4         | 0.11%   |
| SLD                     | 4         | 0.11%   |
| RTK                     | 4         | 0.11%   |
| MSI                     | 4         | 0.11%   |
| KDB                     | 4         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 72        | 1.95%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 31        | 0.84%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 29        | 0.78%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 26        | 0.7%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 25        | 0.68%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 23        | 0.62%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 22        | 0.59%   |
| Valve ANX7530 U VLV3003 800x1280 100x160mm 7.4-inch                      | 20        | 0.54%   |
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                    | 18        | 0.49%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 18        | 0.49%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 16        | 0.43%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 16        | 0.43%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 16        | 0.43%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 15        | 0.41%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 15        | 0.41%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 14        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 13        | 0.35%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 13        | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 12        | 0.32%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 12        | 0.32%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 11        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 11        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 11        | 0.3%    |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 11        | 0.3%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 11        | 0.3%    |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 11        | 0.3%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 11        | 0.3%    |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 10        | 0.27%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 10        | 0.27%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 10        | 0.27%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 10        | 0.27%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 10        | 0.27%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch           | 10        | 0.27%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 10        | 0.27%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 9         | 0.24%   |
| Samsung Electronics LCD Monitor SDC4180 2880x1620 344x194mm 15.5-inch    | 9         | 0.24%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 9         | 0.24%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 9         | 0.24%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                    | 9         | 0.24%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 9         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1484      | 42.64%  |
| 1366x768 (WXGA)    | 851       | 24.45%  |
| 1600x900 (HD+)     | 159       | 4.57%   |
| 1920x1200 (WUXGA)  | 132       | 3.79%   |
| 3840x2160 (4K)     | 128       | 3.68%   |
| 2560x1600          | 106       | 3.05%   |
| 2560x1440 (QHD)    | 100       | 2.87%   |
| 800x1280           | 94        | 2.7%    |
| 1280x800 (WXGA)    | 85        | 2.44%   |
| 1440x900 (WXGA+)   | 61        | 1.75%   |
| 2880x1800          | 48        | 1.38%   |
| 2256x1504          | 24        | 0.69%   |
| 1680x1050 (WSXGA+) | 22        | 0.63%   |
| 2160x1440          | 18        | 0.52%   |
| 3200x1800 (QHD+)   | 15        | 0.43%   |
| 2560x1080          | 14        | 0.4%    |
| 1280x1024 (SXGA)   | 13        | 0.37%   |
| 3840x2400          | 12        | 0.34%   |
| 3440x1440          | 11        | 0.32%   |
| 1024x600           | 11        | 0.32%   |
| 3200x2000          | 10        | 0.29%   |
| 1920x540           | 10        | 0.29%   |
| 2880x1620          | 9         | 0.26%   |
| 1360x768           | 8         | 0.23%   |
| 3072x1920          | 7         | 0.2%    |
| 3840x1080          | 5         | 0.14%   |
| 2520x1680          | 5         | 0.14%   |
| 3456x2160          | 4         | 0.11%   |
| 1920x1280          | 4         | 0.11%   |
| 1600x1200          | 4         | 0.11%   |
| 2240x1400          | 3         | 0.09%   |
| 1280x720 (HD)      | 3         | 0.09%   |
| 3120x2080          | 2         | 0.06%   |
| 1680x945           | 2         | 0.06%   |
| Unknown            | 2         | 0.06%   |
| 3840x1600          | 1         | 0.03%   |
| 3000x2000          | 1         | 0.03%   |
| 2960x1050          | 1         | 0.03%   |
| 2944x1840          | 1         | 0.03%   |
| 2400x1600          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1454      | 39.63%  |
| 13      | 501       | 13.65%  |
| 14      | 452       | 12.32%  |
| 17      | 255       | 6.95%   |
| 16      | 134       | 3.65%   |
| 27      | 117       | 3.19%   |
| 24      | 111       | 3.03%   |
| 7       | 95        | 2.59%   |
| 23      | 86        | 2.34%   |
| 12      | 79        | 2.15%   |
| 21      | 69        | 1.88%   |
| 11      | 51        | 1.39%   |
| 31      | 39        | 1.06%   |
| 18      | 31        | 0.84%   |
| Unknown | 24        | 0.65%   |
| 34      | 22        | 0.6%    |
| 19      | 16        | 0.44%   |
| 10      | 15        | 0.41%   |
| 20      | 13        | 0.35%   |
| 40      | 12        | 0.33%   |
| 84      | 11        | 0.3%    |
| 72      | 10        | 0.27%   |
| 22      | 10        | 0.27%   |
| 54      | 9         | 0.25%   |
| 32      | 7         | 0.19%   |
| 49      | 5         | 0.14%   |
| 65      | 3         | 0.08%   |
| 48      | 3         | 0.08%   |
| 29      | 3         | 0.08%   |
| 26      | 3         | 0.08%   |
| 52      | 2         | 0.05%   |
| 46      | 2         | 0.05%   |
| 37      | 2         | 0.05%   |
| 28      | 2         | 0.05%   |
| 25      | 2         | 0.05%   |
| 142     | 1         | 0.03%   |
| 85      | 1         | 0.03%   |
| 75      | 1         | 0.03%   |
| 74      | 1         | 0.03%   |
| 69      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2232      | 61.17%  |
| 201-300        | 391       | 10.72%  |
| 351-400        | 323       | 8.85%   |
| 501-600        | 290       | 7.95%   |
| 401-500        | 127       | 3.48%   |
| 1-100          | 95        | 2.6%    |
| 601-700        | 60        | 1.64%   |
| 701-800        | 31        | 0.85%   |
| 1001-1500      | 27        | 0.74%   |
| 1501-2000      | 25        | 0.69%   |
| Unknown        | 24        | 0.66%   |
| 801-900        | 17        | 0.47%   |
| 901-1000       | 4         | 0.11%   |
| 101-200        | 2         | 0.05%   |
| More than 2000 | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2570      | 78.33%  |
| 16/10   | 487       | 14.84%  |
| 0.67    | 73        | 2.22%   |
| 3/2     | 60        | 1.83%   |
| 21/9    | 26        | 0.79%   |
| 0.62    | 23        | 0.7%    |
| 5/4     | 11        | 0.34%   |
| 4/3     | 11        | 0.34%   |
| 32/9    | 10        | 0.3%    |
| Unknown | 7         | 0.21%   |
| 3.73    | 1         | 0.03%   |
| 1.00    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1465      | 39.96%  |
| 81-90          | 784       | 21.39%  |
| 121-130        | 232       | 6.33%   |
| 201-250        | 217       | 5.92%   |
| 71-80          | 156       | 4.26%   |
| 301-350        | 121       | 3.3%    |
| 111-120        | 116       | 3.16%   |
| 1-40           | 97        | 2.65%   |
| 351-500        | 75        | 2.05%   |
| 61-70          | 74        | 2.02%   |
| 151-200        | 54        | 1.47%   |
| 51-60          | 51        | 1.39%   |
| More than 1000 | 45        | 1.23%   |
| 251-300        | 33        | 0.9%    |
| 141-150        | 33        | 0.9%    |
| 501-1000       | 28        | 0.76%   |
| 91-100         | 24        | 0.65%   |
| Unknown        | 24        | 0.65%   |
| 131-140        | 22        | 0.6%    |
| 41-50          | 15        | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1483      | 41.18%  |
| 101-120       | 959       | 26.63%  |
| 51-100        | 504       | 14%     |
| 161-240       | 479       | 13.3%   |
| More than 240 | 115       | 3.19%   |
| 1-50          | 37        | 1.03%   |
| Unknown       | 24        | 0.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2584      | 79.85%  |
| 2     | 495       | 15.3%   |
| 0     | 93        | 2.87%   |
| 3     | 60        | 1.85%   |
| 4     | 3         | 0.09%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1721      | 34.12%  |
| Intel                             | 1669      | 33.09%  |
| Qualcomm Atheros                  | 552       | 10.94%  |
| Broadcom                          | 258       | 5.11%   |
| MediaTek                          | 211       | 4.18%   |
| Broadcom Limited                  | 78        | 1.55%   |
| ASIX Electronics                  | 56        | 1.11%   |
| Qualcomm                          | 46        | 0.91%   |
| Marvell Technology Group          | 44        | 0.87%   |
| TP-Link                           | 36        | 0.71%   |
| Ralink                            | 35        | 0.69%   |
| DisplayLink                       | 29        | 0.57%   |
| Samsung Electronics               | 27        | 0.54%   |
| Ralink Technology                 | 27        | 0.54%   |
| Ericsson Business Mobile Networks | 23        | 0.46%   |
| Dell                              | 23        | 0.46%   |
| Lenovo                            | 22        | 0.44%   |
| Sierra Wireless                   | 20        | 0.4%    |
| Xiaomi                            | 19        | 0.38%   |
| Nvidia                            | 13        | 0.26%   |
| Hewlett-Packard                   | 11        | 0.22%   |
| Motorola PCS                      | 10        | 0.2%    |
| NetGear                           | 8         | 0.16%   |
| Fibocom                           | 8         | 0.16%   |
| JMicron Technology                | 7         | 0.14%   |
| Huawei Technologies               | 7         | 0.14%   |
| OPPO Electronics                  | 6         | 0.12%   |
| D-Link                            | 6         | 0.12%   |
| Qualcomm Atheros Communications   | 5         | 0.1%    |
| Apple                             | 5         | 0.1%    |
| Google                            | 4         | 0.08%   |
| Edimax Technology                 | 4         | 0.08%   |
| D-Link System                     | 4         | 0.08%   |
| ASUSTek Computer                  | 4         | 0.08%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.06%   |
| Qualcomm Technologies             | 3         | 0.06%   |
| Microsoft                         | 3         | 0.06%   |
| Attansic Technology               | 3         | 0.06%   |
| OpenMoko                          | 2         | 0.04%   |
| MicroPython                       | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 944       | 15.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 227       | 3.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 173       | 2.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 162       | 2.67%   |
| Intel Wi-Fi 6 AX201                                               | 146       | 2.41%   |
| Intel Wireless 8265 / 8275                                        | 128       | 2.11%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 126       | 2.08%   |
| Intel Wi-Fi 6 AX200                                               | 108       | 1.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 103       | 1.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 102       | 1.68%   |
| Intel Wireless 7260                                               | 93        | 1.53%   |
| Intel Wireless 7265                                               | 92        | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 87        | 1.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 84        | 1.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 83        | 1.37%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 81        | 1.34%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 80        | 1.32%   |
| Intel Wireless 8260                                               | 79        | 1.3%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 75        | 1.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 74        | 1.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 67        | 1.1%    |
| Intel Ethernet Connection (4) I219-LM                             | 60        | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 57        | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 56        | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 52        | 0.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 52        | 0.86%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 50        | 0.82%   |
| ASIX AX88179 Gigabit Ethernet                                     | 50        | 0.82%   |
| Intel Wireless 3165                                               | 48        | 0.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 48        | 0.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 47        | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 46        | 0.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 44        | 0.73%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 42        | 0.69%   |
| Intel Ethernet Connection I217-LM                                 | 40        | 0.66%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 37        | 0.61%   |
| Broadcom BCM43142 802.11b/g/n                                     | 37        | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 36        | 0.59%   |
| Intel Ethernet Connection I219-LM                                 | 34        | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 33        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1612      | 47.76%  |
| Realtek Semiconductor             | 587       | 17.39%  |
| Qualcomm Atheros                  | 464       | 13.75%  |
| Broadcom                          | 211       | 6.25%   |
| MediaTek                          | 203       | 6.01%   |
| Broadcom Limited                  | 59        | 1.75%   |
| Qualcomm                          | 43        | 1.27%   |
| Ralink                            | 35        | 1.04%   |
| TP-Link                           | 34        | 1.01%   |
| Ralink Technology                 | 27        | 0.8%    |
| Sierra Wireless                   | 20        | 0.59%   |
| Dell                              | 17        | 0.5%    |
| NetGear                           | 8         | 0.24%   |
| Fibocom                           | 8         | 0.24%   |
| D-Link                            | 6         | 0.18%   |
| Qualcomm Atheros Communications   | 5         | 0.15%   |
| Ericsson Business Mobile Networks | 5         | 0.15%   |
| Edimax Technology                 | 4         | 0.12%   |
| D-Link System                     | 4         | 0.12%   |
| ASUSTek Computer                  | 4         | 0.12%   |
| Microsoft                         | 3         | 0.09%   |
| Hewlett-Packard                   | 3         | 0.09%   |
| Qualcomm Technologies             | 2         | 0.06%   |
| Belkin Components                 | 2         | 0.06%   |
| Unknown                           | 2         | 0.06%   |
| Xiaomi                            | 1         | 0.03%   |
| Sitecom Europe                    | 1         | 0.03%   |
| Qcom                              | 1         | 0.03%   |
| PLANEX                            | 1         | 0.03%   |
| Micro Star International          | 1         | 0.03%   |
| Mercucys                          | 1         | 0.03%   |
| Linksys                           | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 173       | 5.1%    |
| Intel Wi-Fi 6 AX201                                                  | 146       | 4.3%    |
| Intel Wireless 8265 / 8275                                           | 128       | 3.77%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 126       | 3.71%   |
| Intel Wi-Fi 6 AX200                                                  | 108       | 3.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 103       | 3.04%   |
| Intel Wireless 7260                                                  | 93        | 2.74%   |
| Intel Wireless 7265                                                  | 92        | 2.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 87        | 2.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 84        | 2.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 83        | 2.45%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 81        | 2.39%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 80        | 2.36%   |
| Intel Wireless 8260                                                  | 79        | 2.33%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 75        | 2.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 74        | 2.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 67        | 1.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 57        | 1.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 56        | 1.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 52        | 1.53%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 52        | 1.53%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 50        | 1.47%   |
| Intel Wireless 3165                                                  | 48        | 1.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 48        | 1.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 46        | 1.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 44        | 1.3%    |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 42        | 1.24%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 37        | 1.09%   |
| Broadcom BCM43142 802.11b/g/n                                        | 37        | 1.09%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 33        | 0.97%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                    | 32        | 0.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 29        | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 27        | 0.8%    |
| Intel Centrino Advanced-N 6200                                       | 27        | 0.8%    |
| Intel Gemini Lake PCH CNVi WiFi                                      | 26        | 0.77%   |
| Intel Wireless 3160                                                  | 25        | 0.74%   |
| Intel Centrino Advanced-N 6235                                       | 24        | 0.71%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 24        | 0.71%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 23        | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 22        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1424      | 55.54%  |
| Intel                                  | 614       | 23.95%  |
| Qualcomm Atheros                       | 156       | 6.08%   |
| Broadcom                               | 86        | 3.35%   |
| ASIX Electronics                       | 56        | 2.18%   |
| Marvell Technology Group               | 44        | 1.72%   |
| DisplayLink                            | 29        | 1.13%   |
| Samsung Electronics                    | 21        | 0.82%   |
| Broadcom Limited                       | 19        | 0.74%   |
| Xiaomi                                 | 18        | 0.7%    |
| Lenovo                                 | 18        | 0.7%    |
| Nvidia                                 | 13        | 0.51%   |
| MediaTek                               | 8         | 0.31%   |
| JMicron Technology                     | 7         | 0.27%   |
| OPPO Electronics                       | 6         | 0.23%   |
| Motorola PCS                           | 6         | 0.23%   |
| Hewlett-Packard                        | 5         | 0.2%    |
| Apple                                  | 5         | 0.2%    |
| Huawei Technologies                    | 4         | 0.16%   |
| Google                                 | 4         | 0.16%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.12%   |
| Qualcomm                               | 3         | 0.12%   |
| Attansic Technology                    | 3         | 0.12%   |
| TP-Link                                | 2         | 0.08%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.04%   |
| VIA Technologies                       | 1         | 0.04%   |
| Spreadtrum Communications              | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Research In Motion                     | 1         | 0.04%   |
| QinHeng Electronics                    | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.04%   |
| Novatel Wireless                       | 1         | 0.04%   |
| Linksys                                | 1         | 0.04%   |
| Cypress Semiconductor                  | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 944       | 36.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 227       | 8.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 162       | 6.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 102       | 3.93%   |
| Intel Ethernet Connection (4) I219-LM                             | 60        | 2.31%   |
| ASIX AX88179 Gigabit Ethernet                                     | 50        | 1.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 47        | 1.81%   |
| Intel Ethernet Connection I217-LM                                 | 40        | 1.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 36        | 1.39%   |
| Intel Ethernet Connection I219-LM                                 | 34        | 1.31%   |
| Intel Ethernet Connection I218-LM                                 | 33        | 1.27%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 31        | 1.19%   |
| Intel 82577LM Gigabit Network Connection                          | 29        | 1.12%   |
| Intel Ethernet Connection (3) I218-LM                             | 28        | 1.08%   |
| Intel Ethernet Connection (4) I219-V                              | 27        | 1.04%   |
| Intel Ethernet Connection I219-V                                  | 24        | 0.92%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 20        | 0.77%   |
| Intel Ethernet Connection (13) I219-V                             | 20        | 0.77%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 19        | 0.73%   |
| Intel Ethernet Connection (6) I219-LM                             | 19        | 0.73%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 18        | 0.69%   |
| Intel 82567LM Gigabit Network Connection                          | 18        | 0.69%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 18        | 0.69%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 17        | 0.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 17        | 0.65%   |
| Intel Ethernet Connection (16) I219-V                             | 16        | 0.62%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 15        | 0.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 14        | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 14        | 0.54%   |
| Intel Ethernet Connection (6) I219-V                              | 14        | 0.54%   |
| Intel Ethernet Connection (16) I219-LM                            | 13        | 0.5%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 12        | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 11        | 0.42%   |
| Nvidia MCP79 Ethernet                                             | 11        | 0.42%   |
| Intel Ethernet Connection I217-V                                  | 11        | 0.42%   |
| Intel Ethernet Connection (5) I219-LM                             | 11        | 0.42%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 10        | 0.38%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 10        | 0.38%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 10        | 0.38%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 10        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3192      | 56.03%  |
| Ethernet | 2432      | 42.69%  |
| Modem    | 54        | 0.95%   |
| Unknown  | 19        | 0.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2666      | 80.18%  |
| Ethernet | 659       | 19.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2165      | 66.9%   |
| 1     | 1003      | 31%     |
| 0     | 52        | 1.61%   |
| 3     | 16        | 0.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2171      | 67.09%  |
| Yes  | 1065      | 32.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1308      | 48.66%  |
| Realtek Semiconductor           | 311       | 11.57%  |
| IMC Networks                    | 255       | 9.49%   |
| Qualcomm Atheros Communications | 166       | 6.18%   |
| Foxconn / Hon Hai               | 127       | 4.72%   |
| Broadcom                        | 113       | 4.2%    |
| Lite-On Technology              | 91        | 3.39%   |
| Apple                           | 83        | 3.09%   |
| Dell                            | 34        | 1.26%   |
| MediaTek                        | 31        | 1.15%   |
| Hewlett-Packard                 | 31        | 1.15%   |
| Cambridge Silicon Radio         | 25        | 0.93%   |
| Ralink                          | 22        | 0.82%   |
| Realtek                         | 21        | 0.78%   |
| Toshiba                         | 16        | 0.6%    |
| Foxconn International           | 12        | 0.45%   |
| USI                             | 11        | 0.41%   |
| Alps Electric                   | 8         | 0.3%    |
| Taiyo Yuden                     | 5         | 0.19%   |
| ASUSTek Computer                | 4         | 0.15%   |
| Askey Computer                  | 4         | 0.15%   |
| TP-Link                         | 2         | 0.07%   |
| Ralink Technology               | 2         | 0.07%   |
| Fujitsu                         | 2         | 0.07%   |
| Micro Star International        | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| 8BitDo                          | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 457       | 17%     |
| Intel Bluetooth wireless interface                  | 431       | 16.03%  |
| Realtek Bluetooth Radio                             | 238       | 8.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 179       | 6.66%   |
| Intel AX200 Bluetooth                               | 103       | 3.83%   |
| IMC Networks Wireless_Device                        | 87        | 3.24%   |
| Qualcomm Atheros  Bluetooth Device                  | 76        | 2.83%   |
| IMC Networks 802.11ac WLAN Adapter                  | 75        | 2.79%   |
| Intel AX210 Bluetooth                               | 47        | 1.75%   |
| Realtek  Bluetooth 4.2 Adapter                      | 44        | 1.64%   |
| IMC Networks Bluetooth Radio                        | 43        | 1.6%    |
| Apple Bluetooth Host Controller                     | 43        | 1.6%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 39        | 1.45%   |
| Foxconn / Hon Hai Bluetooth Device                  | 35        | 1.3%    |
| Apple Bluetooth USB Host Controller                 | 34        | 1.26%   |
| MediaTek Wireless_Device                            | 30        | 1.12%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 27        | 1%      |
| Foxconn / Hon Hai Wireless_Device                   | 27        | 1%      |
| IMC Networks Bluetooth Device                       | 25        | 0.93%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 25        | 0.93%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 25        | 0.93%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 24        | 0.89%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 23        | 0.86%   |
| Lite-On Bluetooth Device                            | 23        | 0.86%   |
| HP Broadcom 2070 Bluetooth Combo                    | 23        | 0.86%   |
| Ralink RT3290 Bluetooth                             | 22        | 0.82%   |
| Realtek Bluetooth Radio                             | 21        | 0.78%   |
| Lite-On Wireless_Device                             | 21        | 0.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 21        | 0.78%   |
| Broadcom BCM2045B (BDC-2.1)                         | 20        | 0.74%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 19        | 0.71%   |
| Foxconn / Hon Hai Bluetooth Adapter                 | 19        | 0.71%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 18        | 0.67%   |
| Dell DW375 Bluetooth Module                         | 17        | 0.63%   |
| Realtek RTL8723B Bluetooth                          | 14        | 0.52%   |
| Lite-On Atheros AR3012 Bluetooth                    | 13        | 0.48%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 13        | 0.48%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 12        | 0.45%   |
| Foxconn International BCM43142A0 Bluetooth module   | 12        | 0.45%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 12        | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2473      | 61.03%  |
| AMD                              | 776       | 19.15%  |
| Nvidia                           | 521       | 12.86%  |
| C-Media Electronics              | 35        | 0.86%   |
| Lenovo                           | 21        | 0.52%   |
| Realtek Semiconductor            | 17        | 0.42%   |
| GN Netcom                        | 17        | 0.42%   |
| Hewlett-Packard                  | 16        | 0.39%   |
| Apple                            | 15        | 0.37%   |
| Logitech                         | 14        | 0.35%   |
| Texas Instruments                | 12        | 0.3%    |
| JMTek                            | 11        | 0.27%   |
| Generalplus Technology           | 10        | 0.25%   |
| Sony                             | 9         | 0.22%   |
| ASUSTek Computer                 | 9         | 0.22%   |
| Plantronics                      | 5         | 0.12%   |
| Creative Technology              | 5         | 0.12%   |
| BR23                             | 5         | 0.12%   |
| Razer USA                        | 4         | 0.1%    |
| Kingston Technology              | 4         | 0.1%    |
| Yamaha                           | 3         | 0.07%   |
| SteelSeries ApS                  | 3         | 0.07%   |
| Silicon Integrated Systems [SiS] | 3         | 0.07%   |
| Nordic Semiconductor ASA         | 3         | 0.07%   |
| Dell                             | 3         | 0.07%   |
| Corsair                          | 3         | 0.07%   |
| Unknown                          | 3         | 0.07%   |
| Tenx Technology                  | 2         | 0.05%   |
| Silicon Motion                   | 2         | 0.05%   |
| Sennheiser Communications        | 2         | 0.05%   |
| Microchip Technology             | 2         | 0.05%   |
| Mark of the Unicorn              | 2         | 0.05%   |
| Focusrite-Novation               | 2         | 0.05%   |
| Conexant Systems                 | 2         | 0.05%   |
| Audio-Technica                   | 2         | 0.05%   |
| AKAI Professional M.I.           | 2         | 0.05%   |
| Zhaoxin                          | 1         | 0.02%   |
| YSTEK Technology                 | 1         | 0.02%   |
| Yealink Network Technology       | 1         | 0.02%   |
| XMOS                             | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 450       | 9.15%   |
| Intel Sunrise Point-LP HD Audio                                            | 340       | 6.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 227       | 4.62%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 221       | 4.5%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 199       | 4.05%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 192       | 3.91%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 172       | 3.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 160       | 3.25%   |
| Nvidia Audio device                                                        | 119       | 2.42%   |
| Intel Haswell-ULT HD Audio Controller                                      | 117       | 2.38%   |
| Intel 8 Series HD Audio Controller                                         | 117       | 2.38%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 102       | 2.07%   |
| Intel Broadwell-U Audio Controller                                         | 102       | 2.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 101       | 2.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 100       | 2.03%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 99        | 2.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 99        | 2.01%   |
| Intel Cannon Lake PCH cAVS                                                 | 90        | 1.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 81        | 1.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 80        | 1.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 78        | 1.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 78        | 1.59%   |
| AMD FCH Azalia Controller                                                  | 77        | 1.57%   |
| Intel Comet Lake PCH-LP cAVS                                               | 71        | 1.44%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 66        | 1.34%   |
| Intel Comet Lake PCH cAVS                                                  | 58        | 1.18%   |
| AMD Kabini HDMI/DP Audio                                                   | 58        | 1.18%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 45        | 0.92%   |
| Intel CM238 HD Audio Controller                                            | 42        | 0.85%   |
| Nvidia GA106 High Definition Audio Controller                              | 40        | 0.81%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 40        | 0.81%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 39        | 0.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 37        | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 36        | 0.73%   |
| Nvidia GF108 High Definition Audio Controller                              | 35        | 0.71%   |
| Nvidia GP107GL High Definition Audio Controller                            | 34        | 0.69%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 34        | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 33        | 0.67%   |
| Nvidia GA104 High Definition Audio Controller                              | 29        | 0.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 28        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 605       | 26.89%  |
| SK hynix                                | 509       | 22.62%  |
| Micron Technology                       | 320       | 14.22%  |
| Kingston                                | 167       | 7.42%   |
| Unknown                                 | 126       | 5.6%    |
| Crucial                                 | 95        | 4.22%   |
| A-DATA Technology                       | 56        | 2.49%   |
| Elpida                                  | 47        | 2.09%   |
| Ramaxel Technology                      | 40        | 1.78%   |
| Nanya Technology                        | 34        | 1.51%   |
| Unknown (ABCD)                          | 31        | 1.38%   |
| Unknown                                 | 31        | 1.38%   |
| Corsair                                 | 24        | 1.07%   |
| G.Skill                                 | 18        | 0.8%    |
| Team                                    | 9         | 0.4%    |
| GOODRAM                                 | 8         | 0.36%   |
| Transcend                               | 7         | 0.31%   |
| Smart                                   | 7         | 0.31%   |
| Timetec                                 | 6         | 0.27%   |
| Patriot                                 | 6         | 0.27%   |
| ChangXin Memory                         | 6         | 0.27%   |
| Silicon Power                           | 5         | 0.22%   |
| Apacer                                  | 5         | 0.22%   |
| ACPI Digital                            | 5         | 0.22%   |
| Teikon                                  | 4         | 0.18%   |
| SHARETRONIC                             | 4         | 0.18%   |
| PNY                                     | 4         | 0.18%   |
| ASint Technology                        | 4         | 0.18%   |
| AMD                                     | 4         | 0.18%   |
| Sesame                                  | 3         | 0.13%   |
| Qimonda                                 | 3         | 0.13%   |
| Kllisre                                 | 3         | 0.13%   |
| Goldkey                                 | 3         | 0.13%   |
| ff                                      | 3         | 0.13%   |
| 4ea5                                    | 3         | 0.13%   |
| Unknown (0x0E9D)                        | 2         | 0.09%   |
| Unknown (0x0B5E)                        | 2         | 0.09%   |
| Silicon Power Computer & Communications | 2         | 0.09%   |
| Lexar                                   | 2         | 0.09%   |
| fef5                                    | 2         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 43        | 1.8%    |
| Unknown                                                          | 31        | 1.3%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 28        | 1.17%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 25        | 1.05%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 23        | 0.96%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 23        | 0.96%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 0.96%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 22        | 0.92%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 22        | 0.92%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 21        | 0.88%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 20        | 0.84%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 20        | 0.84%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 20        | 0.84%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 19        | 0.79%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 18        | 0.75%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 17        | 0.71%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 16        | 0.67%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 16        | 0.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.63%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.59%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 0.59%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 14        | 0.59%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.54%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 13        | 0.54%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 13        | 0.54%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 12        | 0.5%    |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 12        | 0.5%    |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 11        | 0.46%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 11        | 0.46%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 11        | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 10        | 0.42%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 10        | 0.42%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 10        | 0.42%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 10        | 0.42%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 10        | 0.42%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 10        | 0.42%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 10        | 0.42%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 10        | 0.42%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 10        | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 9         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 844       | 44.07%  |
| DDR3    | 567       | 29.61%  |
| DDR5    | 117       | 6.11%   |
| LPDDR4  | 115       | 6.01%   |
| LPDDR5  | 89        | 4.65%   |
| DDR2    | 81        | 4.23%   |
| LPDDR3  | 39        | 2.04%   |
| SDRAM   | 36        | 1.88%   |
| Unknown | 18        | 0.94%   |
| DDR     | 5         | 0.26%   |
| DRAM    | 4         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1674      | 86.96%  |
| Row Of Chips | 209       | 10.86%  |
| Unknown      | 19        | 0.99%   |
| Chip         | 12        | 0.62%   |
| DIMM         | 11        | 0.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 785       | 37.78%  |
| 4096  | 581       | 27.96%  |
| 16384 | 330       | 15.88%  |
| 2048  | 242       | 11.65%  |
| 32768 | 74        | 3.56%   |
| 1024  | 60        | 2.89%   |
| 512   | 4         | 0.19%   |
| 3072  | 1         | 0.05%   |
| 1536  | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 454       | 22.16%  |
| 1600    | 408       | 19.91%  |
| 2667    | 306       | 14.93%  |
| 2400    | 135       | 6.59%   |
| 1334    | 82        | 4%      |
| 6400    | 75        | 3.66%   |
| 2133    | 75        | 3.66%   |
| 4800    | 70        | 3.42%   |
| 1333    | 66        | 3.22%   |
| 5600    | 47        | 2.29%   |
| 667     | 37        | 1.81%   |
| 800     | 33        | 1.61%   |
| 1067    | 32        | 1.56%   |
| Unknown | 32        | 1.56%   |
| 4267    | 29        | 1.42%   |
| 1867    | 24        | 1.17%   |
| 3266    | 21        | 1.02%   |
| 4266    | 19        | 0.93%   |
| 4199    | 16        | 0.78%   |
| 2048    | 16        | 0.78%   |
| 3733    | 13        | 0.63%   |
| 975     | 12        | 0.59%   |
| 1066    | 9         | 0.44%   |
| 333     | 7         | 0.34%   |
| 7500    | 6         | 0.29%   |
| 2933    | 5         | 0.24%   |
| 8400    | 4         | 0.2%    |
| 5500    | 3         | 0.15%   |
| 533     | 3         | 0.15%   |
| 7467    | 2         | 0.1%    |
| 5200    | 2         | 0.1%    |
| 4000    | 1         | 0.05%   |
| 3600    | 1         | 0.05%   |
| 3000    | 1         | 0.05%   |
| 1866    | 1         | 0.05%   |
| 933     | 1         | 0.05%   |
| 400     | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)

![Printer Vendor](./images/line_chart/printer_vendor.svg)

| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Brother Industries     | 8         | 25%     |
| Samsung Electronics    | 5         | 15.63%  |
| Hewlett-Packard        | 5         | 15.63%  |
| Dymo-CoStar            | 3         | 9.38%   |
| Canon                  | 3         | 9.38%   |
| Seiko Epson            | 2         | 6.25%   |
| Pantum                 | 1         | 3.13%   |
| Panasonic (Matsushita) | 1         | 3.13%   |
| Oki Data               | 1         | 3.13%   |
| Minolta                | 1         | 3.13%   |
| Lexmark International  | 1         | 3.13%   |
| Kyocera                | 1         | 3.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)

![Printer Model](./images/line_chart/printer_model.svg)

| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung M2020 Series                                         | 2         | 6.25%   |
| HP LaserJet 1020                                             | 2         | 6.25%   |
| Brother DCP-L2530DW series                                   | 2         | 6.25%   |
| Seiko Epson L382 Series                                      | 1         | 3.13%   |
| Seiko Epson ET-2850 Series                                   | 1         | 3.13%   |
| Samsung M267x 287x Series                                    | 1         | 3.13%   |
| Samsung CLX-3180 Series                                      | 1         | 3.13%   |
| Samsung C48x Series                                          | 1         | 3.13%   |
| Pantum M6500W-series                                         | 1         | 3.13%   |
| Panasonic (Matsushita) KX-MB2030 Multifunction Laser Printer | 1         | 3.13%   |
| Oki Data USB Device                                          | 1         | 3.13%   |
| Minolta PagePro 1300W                                        | 1         | 3.13%   |
| Lexmark International MS421dn                                | 1         | 3.13%   |
| Kyocera FS-1125MFP                                           | 1         | 3.13%   |
| HP LaserJet P1006                                            | 1         | 3.13%   |
| HP DeskJet 4100 series                                       | 1         | 3.13%   |
| HP DeskJet 3700 series                                       | 1         | 3.13%   |
| Dymo-CoStar LabelWriter 450                                  | 1         | 3.13%   |
| Dymo-CoStar LabelWriter 400                                  | 1         | 3.13%   |
| Dymo-CoStar DYMO LabelWriter 4XL                             | 1         | 3.13%   |
| Canon PIXMA MG3600 Series                                    | 1         | 3.13%   |
| Canon PIXMA MG3500 Series                                    | 1         | 3.13%   |
| Canon LBP6020                                                | 1         | 3.13%   |
| Brother MFC-J5730DW                                          | 1         | 3.13%   |
| Brother MFC-J4540DW                                          | 1         | 3.13%   |
| Brother HL-L2350DW series                                    | 1         | 3.13%   |
| Brother HL-2240D series                                      | 1         | 3.13%   |
| Brother HL-2030 Laser Printer                                | 1         | 3.13%   |
| Brother HL-1210W series                                      | 1         | 3.13%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)

![Scanner Vendor](./images/line_chart/scanner_vendor.svg)

| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Canon          | 3         | 60%     |
| Seiko Epson    | 1         | 20%     |
| Mustek Systems | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)

![Scanner Model](./images/line_chart/scanner_model.svg)

| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 20%     |
| Mustek Systems BearPaw 1200 CU Plus               | 1         | 20%     |
| Canon CanoScan N670U/N676U/LiDE 20                | 1         | 20%     |
| Canon CanoScan LiDE 220                           | 1         | 20%     |
| Canon CanoScan LiDE 120                           | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)

![Camera Vendor](./images/line_chart/camera_vendor.svg)

| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 646       | 22.96%  |
| IMC Networks                           | 304       | 10.81%  |
| Microdia                               | 237       | 8.43%   |
| Realtek Semiconductor                  | 212       | 7.54%   |
| Quanta                                 | 197       | 7%      |
| Bison Electronics                      | 178       | 6.33%   |
| Sunplus Innovation Technology          | 132       | 4.69%   |
| Cheng Uei Precision Industry (Foxlink) | 98        | 3.48%   |
| Suyin                                  | 81        | 2.88%   |
| Luxvisions Innotech Limited            | 77        | 2.74%   |
| Syntek                                 | 74        | 2.63%   |
| Sonix Technology                       | 65        | 2.31%   |
| Apple                                  | 65        | 2.31%   |
| Lite-On Technology                     | 62        | 2.2%    |
| Acer                                   | 55        | 1.96%   |
| Alcor Micro                            | 41        | 1.46%   |
| Logitech                               | 33        | 1.17%   |
| Ricoh                                  | 31        | 1.1%    |
| Silicon Motion                         | 27        | 0.96%   |
| ShineTech                              | 21        | 0.75%   |
| SunplusIT                              | 20        | 0.71%   |
| icSpring                               | 15        | 0.53%   |
| Lenovo                                 | 13        | 0.46%   |
| Z-Star Microelectronics                | 9         | 0.32%   |
| Primax Electronics                     | 9         | 0.32%   |
| Importek                               | 9         | 0.32%   |
| Samsung Electronics                    | 8         | 0.28%   |
| Microsoft                              | 7         | 0.25%   |
| DigiTech                               | 6         | 0.21%   |
| USB Camera CS                          | 5         | 0.18%   |
| ALi                                    | 5         | 0.18%   |
| Y Media                                | 4         | 0.14%   |
| Unknown                                | 4         | 0.14%   |
| Tripath Technology                     | 3         | 0.11%   |
| OmniVision Technologies                | 3         | 0.11%   |
| Intel                                  | 3         | 0.11%   |
| Genesys Logic                          | 3         | 0.11%   |
| DQYGF0A9IHU4ID                         | 3         | 0.11%   |
| 8SSC21D67422V1SR28902JL                | 3         | 0.11%   |
| Sunplus Technology                     | 2         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 142       | 5.02%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 95        | 3.36%   |
| Microdia Integrated_Webcam_HD                       | 93        | 3.29%   |
| IMC Networks Integrated Camera                      | 79        | 2.79%   |
| Bison Integrated Camera                             | 61        | 2.16%   |
| Realtek Integrated_Webcam_HD                        | 58        | 2.05%   |
| Chicony HD Webcam                                   | 58        | 2.05%   |
| Syntek Integrated Camera                            | 51        | 1.8%    |
| Sunplus Integrated_Webcam_HD                        | 39        | 1.38%   |
| Sonix USB2.0 HD UVC WebCam                          | 39        | 1.38%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 35        | 1.24%   |
| Realtek USB camera                                  | 34        | 1.2%    |
| Quanta HD User Facing                               | 34        | 1.2%    |
| Chicony HP HD Camera                                | 31        | 1.1%    |
| Microdia Integrated Webcam                          | 28        | 0.99%   |
| Chicony HD User Facing                              | 28        | 0.99%   |
| Chicony Integrated Camera (1280x720@30)             | 27        | 0.95%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 24        | 0.85%   |
| Quanta ACER HD User Facing                          | 23        | 0.81%   |
| Chicony USB2.0 HD UVC WebCam                        | 23        | 0.81%   |
| Chicony HP Truevision HD                            | 23        | 0.81%   |
| Sunplus HD WebCam                                   | 22        | 0.78%   |
| Chicony HP TrueVision HD Camera                     | 22        | 0.78%   |
| Quanta HP Wide Vision HD Camera                     | 21        | 0.74%   |
| Lite-On Integrated Camera                           | 21        | 0.74%   |
| Chicony FJ Camera                                   | 21        | 0.74%   |
| Quanta HP TrueVision HD Camera                      | 20        | 0.71%   |
| Quanta HP HD Camera                                 | 20        | 0.71%   |
| Lite-On HP HD Camera                                | 20        | 0.71%   |
| Bison HD Webcam                                     | 20        | 0.71%   |
| Sonix USB2.0 FHD UVC WebCam                         | 19        | 0.67%   |
| Chicony USB2.0 Camera                               | 19        | 0.67%   |
| Apple iPhone 5/5C/5S/6/SE                           | 19        | 0.67%   |
| Apple FaceTime HD Camera                            | 18        | 0.64%   |
| IMC Networks HD Camera                              | 17        | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 17        | 0.6%    |
| Microdia Integrated_Webcam_FHD                      | 16        | 0.57%   |
| Luxvisions Innotech Limited Integrated Camera       | 16        | 0.57%   |
| Bison SunplusIT Integrated Camera                   | 16        | 0.57%   |
| Alcor Micro USB 2.0 Camera                          | 16        | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 148       | 30.71%  |
| Synaptics                          | 132       | 27.39%  |
| Shenzhen Goodix Technology         | 76        | 15.77%  |
| Elan Microelectronics              | 35        | 7.26%   |
| LighTuning Technology              | 25        | 5.19%   |
| AuthenTec                          | 25        | 5.19%   |
| Upek                               | 22        | 4.56%   |
| STMicroelectronics                 | 5         | 1.04%   |
| Realtek USB2.0 Finger Print Bridge | 5         | 1.04%   |
| HOLTEK                             | 4         | 0.83%   |
| Focal-systems.Corp                 | 3         | 0.62%   |
| Samsung Electronics                | 1         | 0.21%   |
| GDMicroelectronics                 | 1         | 0.21%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 60        | 12.42%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 37        | 7.66%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 36        | 7.45%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 33        | 6.83%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 20        | 4.14%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 20        | 4.14%   |
| Elan ELAN:Fingerprint                                                      | 18        | 3.73%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 17        | 3.52%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 17        | 3.52%   |
| Elan ELAN:ARM-M4                                                           | 17        | 3.52%   |
| Validity Sensors Synaptics WBDI                                            | 15        | 3.11%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 2.9%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 2.28%   |
| Shenzhen Goodix Fingerprint Reader                                         | 11        | 2.28%   |
| Synaptics Fingerprint reader [HP G6]                                       | 10        | 2.07%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 1.66%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 8         | 1.66%   |
| AuthenTec AES2810                                                          | 8         | 1.66%   |
| Validity Sensors VFS491                                                    | 7         | 1.45%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.45%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.45%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 1.45%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 1.24%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.24%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 1.24%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 1.04%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 1.04%   |
| Synaptics WBDI                                                             | 5         | 1.04%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 1.04%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.04%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 5         | 1.04%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 0.83%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.83%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 0.83%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.83%   |
| HOLTEK FocalTech Fingerprint Device                                        | 4         | 0.83%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.62%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.62%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 0.62%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.62%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./images/line_chart/chipcard_vendor.svg)

| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 124       | 50.41%  |
| Alcor Micro                       | 67        | 27.24%  |
| O2 Micro                          | 14        | 5.69%   |
| Lenovo                            | 13        | 5.28%   |
| Upek                              | 11        | 4.47%   |
| Gemalto (was Gemplus)             | 4         | 1.63%   |
| VASCO Data Security International | 2         | 0.81%   |
| SCM Microsystems                  | 2         | 0.81%   |
| Realtek Semiconductor             | 2         | 0.81%   |
| Giesecke & Devrient               | 2         | 0.81%   |
| Advanced Card Systems             | 2         | 0.81%   |
| Reiner SCT Kartensysteme          | 1         | 0.41%   |
| OmniKey                           | 1         | 0.41%   |
| Chicony Electronics               | 1         | 0.41%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)

![Chipcard Model](./images/line_chart/chipcard_model.svg)

| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 67        | 27.24%  |
| Broadcom BCM5880 Secure Applications Processor                               | 37        | 15.04%  |
| Broadcom 5880                                                                | 34        | 13.82%  |
| Broadcom 58200                                                               | 32        | 13.01%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 21        | 8.54%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 14        | 5.69%   |
| Lenovo Integrated Smart Card Reader                                          | 13        | 5.28%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 11        | 4.47%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.22%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.81%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.81%   |
| Giesecke & Devrient StarSign CUT                                             | 2         | 0.81%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.41%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.41%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.41%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.41%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.41%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.41%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.41%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.41%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2033      | 62.82%  |
| 1     | 992       | 30.66%  |
| 2     | 168       | 5.19%   |
| 3     | 25        | 0.77%   |
| 4     | 7         | 0.22%   |
| 5     | 6         | 0.19%   |
| 6     | 4         | 0.12%   |
| 9     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 479       | 32.81%  |
| Graphics card            | 294       | 20.14%  |
| Chipcard                 | 202       | 13.84%  |
| Net/wireless             | 134       | 9.18%   |
| Multimedia controller    | 115       | 7.88%   |
| Camera                   | 56        | 3.84%   |
| Bluetooth                | 38        | 2.6%    |
| Communication controller | 31        | 2.12%   |
| Sound                    | 28        | 1.92%   |
| Storage                  | 24        | 1.64%   |
| Card reader              | 17        | 1.16%   |
| Net/ethernet             | 15        | 1.03%   |
| Modem                    | 9         | 0.62%   |
| Network                  | 8         | 0.55%   |
| Storage/raid             | 4         | 0.27%   |
| Firewire controller      | 2         | 0.14%   |
| Unassigned class         | 1         | 0.07%   |
| Storage/ide              | 1         | 0.07%   |
| Storage/ata              | 1         | 0.07%   |
| Dvb card                 | 1         | 0.07%   |

