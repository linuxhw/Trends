Linux - Hardware Trends (Desktops)
----------------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/linuxhw/TestCoverage)

Period: Sep, 2022.

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

| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 22.04                 | 316      | 17.24%  |
| Debian 11                    | 136      | 7.42%   |
| Fedora 36                    | 121      | 6.6%    |
| ROSA 12.2                    | 106      | 5.78%   |
| Linux Mint 21                | 99       | 5.4%    |
| Ubuntu 20.04                 | 98       | 5.35%   |
| OpenMandriva 4.3             | 94       | 5.13%   |
| Pop!_OS 22.04                | 74       | 4.04%   |
| Zorin 16                     | 51       | 2.78%   |
| Linux Mint 20.3              | 51       | 2.78%   |
| Arch                         | 48       | 2.62%   |
| Xubuntu 20.04                | 39       | 2.13%   |
| Arch Rolling                 | 37       | 2.02%   |
| OpenMandriva 4.50            | 33       | 1.8%    |
| Kubuntu 22.04                | 28       | 1.53%   |
| KDE neon 20.04               | 28       | 1.53%   |
| Nobara 36                    | 23       | 1.25%   |
| Manjaro                      | 22       | 1.2%    |
| ArcoLinux Rolling            | 18       | 0.98%   |
| Manjaro 22.0.0               | 17       | 0.93%   |
| Fedora 37                    | 17       | 0.93%   |
| openSUSE Tumbleweed-XXXXXXXX | 15       | 0.82%   |
| LMDE 5                       | 15       | 0.82%   |
| Gentoo 2.8                   | 15       | 0.82%   |
| Xubuntu 22.04                | 14       | 0.76%   |
| Ubuntu MATE 22.04            | 13       | 0.71%   |
| ROSA R11.1                   | 13       | 0.71%   |
| EndeavourOS Rolling          | 12       | 0.65%   |
| OpenMandriva 4.2             | 11       | 0.6%    |
| Kali 2022.3                  | 11       | 0.6%    |
| OpenMandriva 4.90            | 10       | 0.55%   |
| BlackPanther 18.1            | 10       | 0.55%   |
| SteamOS 3.3                  | 9        | 0.49%   |
| Manjaro 21.3.7               | 9        | 0.49%   |
| Elementary 6.1               | 9        | 0.49%   |
| Red OS 7.3.1                 | 8        | 0.44%   |
| Fedora 35                    | 8        | 0.44%   |
| Linux Mint 20.1              | 7        | 0.38%   |
| Linux Mint 19.3              | 7        | 0.38%   |
| MX 21                        | 6        | 0.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 428      | 23.35%  |
| Linux Mint    | 173      | 9.44%   |
| Debian        | 152      | 8.29%   |
| Fedora        | 149      | 8.13%   |
| OpenMandriva  | 148      | 8.07%   |
| ROSA          | 125      | 6.82%   |
| Arch          | 85       | 4.64%   |
| Pop!_OS       | 75       | 4.09%   |
| Xubuntu       | 57       | 3.11%   |
| Zorin         | 54       | 2.95%   |
| Manjaro       | 49       | 2.67%   |
| Kubuntu       | 35       | 1.91%   |
| KDE neon      | 31       | 1.69%   |
| Nobara        | 23       | 1.25%   |
| openSUSE      | 22       | 1.2%    |
| EndeavourOS   | 18       | 0.98%   |
| ArcoLinux     | 18       | 0.98%   |
| Ubuntu MATE   | 16       | 0.87%   |
| LMDE          | 16       | 0.87%   |
| Gentoo        | 15       | 0.82%   |
| Kali          | 11       | 0.6%    |
| Red OS        | 10       | 0.55%   |
| Lubuntu       | 10       | 0.55%   |
| BlackPanther  | 10       | 0.55%   |
| SteamOS       | 9        | 0.49%   |
| Elementary    | 9        | 0.49%   |
| MX            | 7        | 0.38%   |
| Endless       | 7        | 0.38%   |
| Ubuntu Budgie | 5        | 0.27%   |
| Ubuntu Unity  | 4        | 0.22%   |
| Garuda Linux  | 4        | 0.22%   |
| Clear Linux   | 4        | 0.22%   |
| CentOS        | 4        | 0.22%   |
| EuroLinux     | 3        | 0.16%   |
| ALT Linux     | 3        | 0.16%   |
| Ubuntu Studio | 2        | 0.11%   |
| Slackware     | 2        | 0.11%   |
| Rocky Linux   | 2        | 0.11%   |
| Reborn OS     | 2        | 0.11%   |
| PostmarketOS  | 2        | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version                                      | Desktops | Percent |
|----------------------------------------------|----------|---------|
| 5.15.0-47-generic                            | 263      | 14.35%  |
| 5.15.0-48-generic                            | 190      | 10.37%  |
| 5.15.0-46-generic                            | 127      | 6.93%   |
| 5.16.7-desktop-1omv4003                      | 90       | 4.91%   |
| 5.4.0-125-generic                            | 72       | 3.93%   |
| 5.19.0-76051900-generic                      | 65       | 3.55%   |
| 5.10.0-7-amd64                               | 48       | 2.62%   |
| 5.10.74-generic-2rosa2021.1-x86_64           | 46       | 2.51%   |
| 5.10.118-generic-2rosa2021.1-x86_64          | 41       | 2.24%   |
| 5.4.0-126-generic                            | 35       | 1.91%   |
| 5.10.0-18-amd64                              | 33       | 1.8%    |
| 5.19.5-desktop-1omv4090                      | 31       | 1.69%   |
| 5.19.9-200.fc36.x86_64                       | 30       | 1.64%   |
| 5.10.0-17-amd64                              | 30       | 1.64%   |
| 5.15.0-43-generic                            | 24       | 1.31%   |
| 5.19.6-200.fc36.x86_64                       | 23       | 1.25%   |
| 5.19.8-200.fc36.x86_64                       | 21       | 1.15%   |
| 5.19.9-arch1-1                               | 15       | 0.82%   |
| 5.19.7-arch1-1                               | 13       | 0.71%   |
| 5.19.11-arch1-1                              | 13       | 0.71%   |
| 5.15.60-1-MANJARO                            | 13       | 0.71%   |
| 5.19.4-200.fc36.x86_64                       | 11       | 0.6%    |
| 5.15.65-1-MANJARO                            | 11       | 0.6%    |
| 5.15.0-41-generic                            | 11       | 0.6%    |
| 5.19.6-arch1-1                               | 10       | 0.55%   |
| 5.19.9-zen1-1-zen                            | 9        | 0.49%   |
| 5.19.8-1-default                             | 9        | 0.49%   |
| 5.19.10-arch1-1                              | 9        | 0.49%   |
| 5.19.0-1-amd64                               | 9        | 0.49%   |
| 5.17.5-300.fc36.x86_64                       | 9        | 0.49%   |
| 5.10.14-desktop-1omv4002                     | 9        | 0.49%   |
| 5.4.0-124-generic                            | 8        | 0.44%   |
| 5.19.9-300.fc37.x86_64                       | 8        | 0.44%   |
| 5.19.9-201.fsync.fc36.x86_64                 | 8        | 0.44%   |
| 5.19.7-zen2-1-zen                            | 8        | 0.44%   |
| 5.18.12-desktop-3omv4090                     | 8        | 0.44%   |
| 5.15.43-generic-2rosa2021.1-x86_64           | 8        | 0.44%   |
| 5.13.0-valve24-1-neptune-02226-g5b8545e4c5a1 | 8        | 0.44%   |
| 4.18.16-desktop-1bP                          | 8        | 0.44%   |
| 5.19.7-200.fc36.x86_64                       | 7        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.15.0   | 634      | 34.59%  |
| 5.4.0    | 140      | 7.64%   |
| 5.10.0   | 129      | 7.04%   |
| 5.16.7   | 90       | 4.91%   |
| 5.19.0   | 86       | 4.69%   |
| 5.19.9   | 75       | 4.09%   |
| 5.19.7   | 47       | 2.56%   |
| 5.10.74  | 47       | 2.56%   |
| 5.19.6   | 45       | 2.45%   |
| 5.19.8   | 44       | 2.4%    |
| 5.19.5   | 43       | 2.35%   |
| 5.10.118 | 42       | 2.29%   |
| 5.18.0   | 26       | 1.42%   |
| 5.19.11  | 24       | 1.31%   |
| 5.13.0   | 24       | 1.31%   |
| 5.19.10  | 23       | 1.25%   |
| 5.19.4   | 18       | 0.98%   |
| 5.15.60  | 14       | 0.76%   |
| 6.0.0    | 13       | 0.71%   |
| 5.15.65  | 13       | 0.71%   |
| 5.11.0   | 12       | 0.65%   |
| 4.15.0   | 11       | 0.6%    |
| 5.17.5   | 9        | 0.49%   |
| 5.10.14  | 9        | 0.49%   |
| 5.18.12  | 8        | 0.44%   |
| 5.15.43  | 8        | 0.44%   |
| 4.18.16  | 8        | 0.44%   |
| 5.16.13  | 7        | 0.38%   |
| 5.15.59  | 7        | 0.38%   |
| 5.15.53  | 7        | 0.38%   |
| 5.15.35  | 7        | 0.38%   |
| 5.14.0   | 7        | 0.38%   |
| 5.4.83   | 6        | 0.33%   |
| 5.18.19  | 6        | 0.33%   |
| 5.18.18  | 6        | 0.33%   |
| 5.18.10  | 6        | 0.33%   |
| 5.15.67  | 6        | 0.33%   |
| 5.19.2   | 5        | 0.27%   |
| 5.19.1   | 5        | 0.27%   |
| 5.18.17  | 5        | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 724      | 39.5%   |
| 5.19    | 419      | 22.86%  |
| 5.10    | 234      | 12.77%  |
| 5.4     | 153      | 8.35%   |
| 5.16    | 102      | 5.56%   |
| 5.18    | 64       | 3.49%   |
| 5.13    | 26       | 1.42%   |
| 5.17    | 21       | 1.15%   |
| 5.11    | 15       | 0.82%   |
| 6.0     | 13       | 0.71%   |
| 5.14    | 12       | 0.65%   |
| 4.18    | 12       | 0.65%   |
| 4.15    | 11       | 0.6%    |
| 4.19    | 7        | 0.38%   |
| 5.8     | 5        | 0.27%   |
| 5.3     | 3        | 0.16%   |
| 5.6     | 2        | 0.11%   |
| 5.5     | 2        | 0.11%   |
| 4.9     | 2        | 0.11%   |
| 3.10    | 2        | 0.11%   |
| 5.9     | 1        | 0.05%   |
| 5.0     | 1        | 0.05%   |
| 4.4     | 1        | 0.05%   |
| 3.13    | 1        | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 1815     | 99.02%  |
| i686    | 14       | 0.76%   |
| aarch64 | 2        | 0.11%   |
| s390x   | 1        | 0.05%   |
| ppc64le | 1        | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 773      | 42.17%  |
| KDE5             | 443      | 24.17%  |
| XFCE             | 152      | 8.29%   |
| X-Cinnamon       | 151      | 8.24%   |
| Unknown          | 132      | 7.2%    |
| MATE             | 58       | 3.16%   |
| LXQt             | 24       | 1.31%   |
| Cinnamon         | 22       | 1.2%    |
| Pantheon         | 11       | 0.6%    |
| KDE4             | 10       | 0.55%   |
| i3               | 10       | 0.55%   |
| Budgie           | 8        | 0.44%   |
| GNOME Flashback  | 7        | 0.38%   |
| LXDE             | 6        | 0.33%   |
| Unity            | 4        | 0.22%   |
| sway             | 3        | 0.16%   |
| lightdm-xsession | 3        | 0.16%   |
| GNOME Classic    | 3        | 0.16%   |
| Deepin           | 2        | 0.11%   |
| awesome          | 2        | 0.11%   |
| xmonad           | 1        | 0.05%   |
| trinity          | 1        | 0.05%   |
| qtile            | 1        | 0.05%   |
| openbox          | 1        | 0.05%   |
| LeftWM           | 1        | 0.05%   |
| KDE              | 1        | 0.05%   |
| herbstluftwm     | 1        | 0.05%   |
| Enlightenment    | 1        | 0.05%   |
| bspwm            | 1        | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1254     | 68.41%  |
| Wayland | 444      | 24.22%  |
| Unknown | 72       | 3.93%   |
| Tty     | 63       | 3.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 643      | 35.08%  |
| GDM3    | 358      | 19.53%  |
| SDDM    | 342      | 18.66%  |
| LightDM | 281      | 15.33%  |
| GDM     | 188      | 10.26%  |
| KDM     | 9        | 0.49%   |
| LXDM    | 3        | 0.16%   |
| XDM     | 2        | 0.11%   |
| SLiM    | 2        | 0.11%   |
| Ly      | 2        | 0.11%   |
| XINIT   | 1        | 0.05%   |
| GREETD  | 1        | 0.05%   |
| FLY-DM  | 1        | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 665      | 36.28%  |
| ru_RU   | 259      | 14.13%  |
| de_DE   | 165      | 9%      |
| it_IT   | 90       | 4.91%   |
| pt_BR   | 86       | 4.69%   |
| fr_FR   | 82       | 4.47%   |
| en_GB   | 70       | 3.82%   |
| en_CA   | 44       | 2.4%    |
| es_ES   | 41       | 2.24%   |
| Unknown | 37       | 2.02%   |
| en_AU   | 32       | 1.75%   |
| pl_PL   | 26       | 1.42%   |
| C       | 25       | 1.36%   |
| en_IN   | 18       | 0.98%   |
| es_AR   | 14       | 0.76%   |
| es_MX   | 13       | 0.71%   |
| hu_HU   | 12       | 0.65%   |
| zh_CN   | 8        | 0.44%   |
| nl_NL   | 8        | 0.44%   |
| fr_BE   | 7        | 0.38%   |
| fr_CA   | 6        | 0.33%   |
| en_NZ   | 6        | 0.33%   |
| de_AT   | 6        | 0.33%   |
| sv_SE   | 5        | 0.27%   |
| en_IE   | 5        | 0.27%   |
| de_CH   | 5        | 0.27%   |
| nl_BE   | 4        | 0.22%   |
| ja_JP   | 4        | 0.22%   |
| fi_FI   | 4        | 0.22%   |
| es_UY   | 4        | 0.22%   |
| es_CL   | 4        | 0.22%   |
| en_IL   | 4        | 0.22%   |
| el_GR   | 4        | 0.22%   |
| cs_CZ   | 4        | 0.22%   |
| tr_TR   | 3        | 0.16%   |
| pt_PT   | 3        | 0.16%   |
| es_VE   | 3        | 0.16%   |
| en_SG   | 3        | 0.16%   |
| en_PH   | 3        | 0.16%   |
| en_HK   | 3        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1057     | 57.67%  |
| EFI  | 776      | 42.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 1365     | 74.47%  |
| Btrfs    | 222      | 12.11%  |
| Overlay  | 193      | 10.53%  |
| Xfs      | 27       | 1.47%   |
| Zfs      | 16       | 0.87%   |
| F2fs     | 3        | 0.16%   |
| Ext3     | 2        | 0.11%   |
| Ext2     | 2        | 0.11%   |
| Reiserfs | 1        | 0.05%   |
| Aufs     | 1        | 0.05%   |
| Unknown  | 1        | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 872      | 47.57%  |
| GPT     | 685      | 37.37%  |
| MBR     | 276      | 15.06%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1470     | 80.2%   |
| Yes       | 363      | 19.8%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1202     | 65.58%  |
| Yes       | 631      | 34.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 492      | 26.84%  |
| Gigabyte Technology | 346      | 18.88%  |
| MSI                 | 200      | 10.91%  |
| ASRock              | 180      | 9.82%   |
| Dell                | 132      | 7.2%    |
| Hewlett-Packard     | 128      | 6.98%   |
| Lenovo              | 69       | 3.76%   |
| Intel               | 40       | 2.18%   |
| ECS                 | 28       | 1.53%   |
| Acer                | 27       | 1.47%   |
| Unknown             | 22       | 1.2%    |
| Biostar             | 18       | 0.98%   |
| Foxconn             | 15       | 0.82%   |
| Medion              | 13       | 0.71%   |
| BESSTAR Tech        | 11       | 0.6%    |
| Pegatron            | 10       | 0.55%   |
| Huanan              | 10       | 0.55%   |
| Fujitsu             | 9        | 0.49%   |
| Supermicro          | 5        | 0.27%   |
| Gateway             | 5        | 0.27%   |
| AZW                 | 5        | 0.27%   |
| Apple               | 5        | 0.27%   |
| Positivo            | 4        | 0.22%   |
| PCWare              | 4        | 0.22%   |
| Packard Bell        | 4        | 0.22%   |
| MACHINIST           | 4        | 0.22%   |
| AMI                 | 4        | 0.22%   |
| System76            | 3        | 0.16%   |
| Shuttle             | 3        | 0.16%   |
| OEM                 | 3        | 0.16%   |
| Fujitsu Siemens     | 3        | 0.16%   |
| ASRockRack          | 3        | 0.16%   |
| Alienware           | 3        | 0.16%   |
| MiTAC               | 2        | 0.11%   |
| Minix               | 2        | 0.11%   |
| Colorful Technology | 2        | 0.11%   |
| Wistron             | 1        | 0.05%   |
| Thecus              | 1        | 0.05%   |
| RDW                 | 1        | 0.05%   |
| Protectli           | 1        | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 48       | 2.62%   |
| Unknown                        | 25       | 1.36%   |
| MSI MS-7C37                    | 19       | 1.04%   |
| ASRock H470M-HVS               | 17       | 0.93%   |
| Gigabyte H410M S2H             | 15       | 0.82%   |
| ECS G31T-M9                    | 14       | 0.76%   |
| MSI MS-7C91                    | 12       | 0.65%   |
| ASUS TUF Gaming X570-PLUS      | 11       | 0.6%    |
| ASUS PRIME A320M-K             | 11       | 0.6%    |
| MSI MS-7B86                    | 9        | 0.49%   |
| Gigabyte B450M DS3H            | 9        | 0.49%   |
| MSI MS-7C56                    | 8        | 0.44%   |
| MSI MS-7721                    | 8        | 0.44%   |
| Dell OptiPlex 7010             | 8        | 0.44%   |
| ASUS ROG STRIX B550-F GAMING   | 8        | 0.44%   |
| ASUS ROG CROSSHAIR VIII HERO   | 8        | 0.44%   |
| MSI MS-7B79                    | 7        | 0.38%   |
| MSI MS-7A38                    | 7        | 0.38%   |
| MSI MS-7817                    | 7        | 0.38%   |
| Gigabyte A320M-S2H             | 7        | 0.38%   |
| Gigabyte 970A-DS3P             | 7        | 0.38%   |
| Dell OptiPlex 755              | 7        | 0.38%   |
| Gigabyte B450 I AORUS PRO WIFI | 6        | 0.33%   |
| ASUS TUF Gaming B550-PLUS      | 6        | 0.33%   |
| ASUS ROG STRIX B450-F GAMING   | 6        | 0.33%   |
| MSI MS-7C02                    | 5        | 0.27%   |
| Intel H61                      | 5        | 0.27%   |
| HP EliteDesk 800 G1 SFF        | 5        | 0.27%   |
| Dell OptiPlex 9020             | 5        | 0.27%   |
| Dell OptiPlex 780              | 5        | 0.27%   |
| Dell OptiPlex 390              | 5        | 0.27%   |
| ASUS TUF Gaming B550M-PLUS     | 5        | 0.27%   |
| ASUS PRIME H310M-E R2.0        | 5        | 0.27%   |
| ASUS M5A97 R2.0                | 5        | 0.27%   |
| ASRock B450M Pro4              | 5        | 0.27%   |
| ASRock B450 Pro4               | 5        | 0.27%   |
| MSI MS-7693                    | 4        | 0.22%   |
| MSI MS-7599                    | 4        | 0.22%   |
| HP Compaq Pro 6300 MT          | 4        | 0.22%   |
| HP Compaq Elite 8300 USDT      | 4        | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 104      | 5.67%   |
| Dell OptiPlex       | 77       | 4.2%    |
| ASUS ROG            | 73       | 3.98%   |
| ASUS TUF            | 53       | 2.89%   |
| ASUS All            | 48       | 2.62%   |
| HP Compaq           | 46       | 2.51%   |
| Lenovo ThinkCentre  | 35       | 1.91%   |
| Dell Precision      | 27       | 1.47%   |
| Unknown             | 25       | 1.36%   |
| HP EliteDesk        | 20       | 1.09%   |
| MSI MS-7C37         | 19       | 1.04%   |
| Acer Aspire         | 19       | 1.04%   |
| Gigabyte H410M      | 17       | 0.93%   |
| ASRock H470M-HVS    | 17       | 0.93%   |
| Gigabyte X570       | 16       | 0.87%   |
| Gigabyte B450       | 16       | 0.87%   |
| Gigabyte B450M      | 14       | 0.76%   |
| ECS G31T-M9         | 14       | 0.76%   |
| MSI MS-7C91         | 12       | 0.65%   |
| Lenovo IdeaCentre   | 12       | 0.65%   |
| HP ProDesk          | 12       | 0.65%   |
| Lenovo ThinkStation | 11       | 0.6%    |
| Gigabyte A320M-S2H  | 11       | 0.6%    |
| ASUS M5A97          | 11       | 0.6%    |
| ASRock B450M        | 10       | 0.55%   |
| MSI MS-7B86         | 9        | 0.49%   |
| Dell Inspiron       | 9        | 0.49%   |
| ASUS P8H61-M        | 9        | 0.49%   |
| ASUS M5A78L-M       | 9        | 0.49%   |
| MSI MS-7C56         | 8        | 0.44%   |
| MSI MS-7721         | 8        | 0.44%   |
| HP Pavilion         | 8        | 0.44%   |
| Gigabyte Z590       | 8        | 0.44%   |
| Gigabyte B550       | 8        | 0.44%   |
| ASUS Pro            | 8        | 0.44%   |
| ASRock B450         | 8        | 0.44%   |
| MSI MS-7B79         | 7        | 0.38%   |
| MSI MS-7A38         | 7        | 0.38%   |
| MSI MS-7817         | 7        | 0.38%   |
| Gigabyte Z390       | 7        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 192      | 10.47%  |
| 2020    | 185      | 10.09%  |
| 2021    | 161      | 8.78%   |
| 2019    | 152      | 8.29%   |
| 2012    | 146      | 7.97%   |
| 2013    | 144      | 7.86%   |
| 2011    | 122      | 6.66%   |
| 2014    | 114      | 6.22%   |
| 2017    | 98       | 5.35%   |
| 2010    | 93       | 5.07%   |
| 2016    | 82       | 4.47%   |
| 2015    | 80       | 4.36%   |
| 2009    | 77       | 4.2%    |
| 2022    | 60       | 3.27%   |
| 2008    | 56       | 3.06%   |
| 2007    | 42       | 2.29%   |
| 2006    | 19       | 1.04%   |
| Unknown | 5        | 0.27%   |
| 2005    | 4        | 0.22%   |
| 2004    | 1        | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1833     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1790     | 97.65%  |
| Enabled  | 43       | 2.35%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1829     | 99.78%  |
| Yes  | 4        | 0.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 475      | 25.91%  |
| 32.01-64.0      | 333      | 18.17%  |
| 8.01-16.0       | 317      | 17.29%  |
| 4.01-8.0        | 261      | 14.24%  |
| 3.01-4.0        | 235      | 12.82%  |
| 64.01-256.0     | 93       | 5.07%   |
| 1.01-2.0        | 49       | 2.67%   |
| 24.01-32.0      | 44       | 2.4%    |
| 2.01-3.0        | 16       | 0.87%   |
| More than 256.0 | 6        | 0.33%   |
| 0.51-1.0        | 4        | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 590      | 32.19%  |
| 2.01-3.0    | 402      | 21.93%  |
| 4.01-8.0    | 270      | 14.73%  |
| 3.01-4.0    | 238      | 12.98%  |
| 0.51-1.0    | 176      | 9.6%    |
| 8.01-16.0   | 103      | 5.62%   |
| 0.01-0.5    | 20       | 1.09%   |
| 16.01-24.0  | 18       | 0.98%   |
| 24.01-32.0  | 7        | 0.38%   |
| 64.01-256.0 | 5        | 0.27%   |
| 32.01-64.0  | 3        | 0.16%   |
| Unknown     | 1        | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 650      | 35.46%  |
| 2      | 545      | 29.73%  |
| 3      | 289      | 15.77%  |
| 4      | 182      | 9.93%   |
| 5      | 77       | 4.2%    |
| 6      | 36       | 1.96%   |
| 0      | 17       | 0.93%   |
| 7      | 16       | 0.87%   |
| 8      | 7        | 0.38%   |
| 9      | 5        | 0.27%   |
| 10     | 4        | 0.22%   |
| 11     | 3        | 0.16%   |
| 46     | 1        | 0.05%   |
| 13     | 1        | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1049     | 57.23%  |
| Yes       | 784      | 42.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1816     | 99.07%  |
| No        | 17       | 0.93%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1019     | 55.59%  |
| Yes       | 814      | 44.41%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1234     | 67.32%  |
| Yes       | 599      | 32.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 325      | 17.73%  |
| Russia      | 281      | 15.33%  |
| Germany     | 199      | 10.86%  |
| Italy       | 118      | 6.44%   |
| Brazil      | 109      | 5.95%   |
| France      | 82       | 4.47%   |
| UK          | 65       | 3.55%   |
| Canada      | 63       | 3.44%   |
| Spain       | 48       | 2.62%   |
| Australia   | 37       | 2.02%   |
| Poland      | 33       | 1.8%    |
| Hungary     | 24       | 1.31%   |
| Netherlands | 22       | 1.2%    |
| Austria     | 22       | 1.2%    |
| India       | 21       | 1.15%   |
| Belgium     | 21       | 1.15%   |
| Mexico      | 20       | 1.09%   |
| Argentina   | 18       | 0.98%   |
| Switzerland | 16       | 0.87%   |
| Sweden      | 16       | 0.87%   |
| Finland     | 16       | 0.87%   |
| China       | 13       | 0.71%   |
| Greece      | 11       | 0.6%    |
| Slovakia    | 10       | 0.55%   |
| Japan       | 10       | 0.55%   |
| Ukraine     | 9        | 0.49%   |
| Serbia      | 9        | 0.49%   |
| Romania     | 9        | 0.49%   |
| Norway      | 9        | 0.49%   |
| New Zealand | 9        | 0.49%   |
| Hong Kong   | 9        | 0.49%   |
| Chile       | 9        | 0.49%   |
| Turkey      | 7        | 0.38%   |
| Slovenia    | 7        | 0.38%   |
| Portugal    | 7        | 0.38%   |
| Israel      | 7        | 0.38%   |
| Denmark     | 7        | 0.38%   |
| Czechia     | 7        | 0.38%   |
| Philippines | 6        | 0.33%   |
| Ireland     | 6        | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City              | Desktops | Percent |
|-------------------|----------|---------|
| Voronezh          | 72       | 3.93%   |
| Moscow            | 37       | 2.02%   |
| St Petersburg     | 20       | 1.09%   |
| Milan             | 14       | 0.76%   |
| Berlin            | 14       | 0.76%   |
| Vienna            | 12       | 0.65%   |
| Sao Paulo         | 12       | 0.65%   |
| Melbourne         | 12       | 0.65%   |
| Rome              | 11       | 0.6%    |
| Rio de Janeiro    | 11       | 0.6%    |
| Unknown           | 11       | 0.6%    |
| Yekaterinburg     | 9        | 0.49%   |
| Paris             | 9        | 0.49%   |
| Munich            | 9        | 0.49%   |
| Amsterdam         | 9        | 0.49%   |
| Montreal          | 8        | 0.44%   |
| Helsinki          | 8        | 0.44%   |
| Sydney            | 7        | 0.38%   |
| Novosibirsk       | 7        | 0.38%   |
| Nizhniy Novgorod  | 7        | 0.38%   |
| Krasnodar         | 7        | 0.38%   |
| Košice           | 7        | 0.38%   |
| Hamburg           | 7        | 0.38%   |
| Frankfurt am Main | 7        | 0.38%   |
| Chelyabinsk       | 7        | 0.38%   |
| Budapest          | 7        | 0.38%   |
| Belgrade          | 7        | 0.38%   |
| Warsaw            | 6        | 0.33%   |
| Vladivostok       | 6        | 0.33%   |
| Vancouver         | 6        | 0.33%   |
| Seattle           | 6        | 0.33%   |
| Saratov           | 6        | 0.33%   |
| Los Angeles       | 6        | 0.33%   |
| Seville           | 5        | 0.27%   |
| San Francisco     | 5        | 0.27%   |
| Ljubljana         | 5        | 0.27%   |
| Kolkata           | 5        | 0.27%   |
| Chicago           | 5        | 0.27%   |
| Central           | 5        | 0.27%   |
| Buenos Aires      | 5        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 650      | 848    | 18.88%  |
| Seagate                     | 593      | 828    | 17.22%  |
| Samsung Electronics         | 503      | 746    | 14.61%  |
| Kingston                    | 218      | 242    | 6.33%   |
| Toshiba                     | 214      | 236    | 6.22%   |
| Crucial                     | 159      | 180    | 4.62%   |
| SanDisk                     | 151      | 174    | 4.39%   |
| Hitachi                     | 103      | 115    | 2.99%   |
| A-DATA Technology           | 49       | 53     | 1.42%   |
| HGST                        | 42       | 49     | 1.22%   |
| Intel                       | 40       | 44     | 1.16%   |
| China                       | 40       | 45     | 1.16%   |
| Unknown                     | 37       | 51     | 1.07%   |
| Netac                       | 33       | 33     | 0.96%   |
| SK hynix                    | 30       | 30     | 0.87%   |
| Phison Electronics          | 28       | 32     | 0.81%   |
| SPCC                        | 27       | 31     | 0.78%   |
| Silicon Motion              | 26       | 26     | 0.76%   |
| Patriot                     | 24       | 25     | 0.7%    |
| Phison                      | 22       | 29     | 0.64%   |
| Micron/Crucial Technology   | 21       | 23     | 0.61%   |
| PNY                         | 19       | 19     | 0.55%   |
| Maxtor                      | 19       | 21     | 0.55%   |
| Intenso                     | 16       | 17     | 0.46%   |
| Transcend                   | 14       | 14     | 0.41%   |
| Realtek Semiconductor       | 13       | 13     | 0.38%   |
| OCZ                         | 13       | 14     | 0.38%   |
| Micron Technology           | 13       | 13     | 0.38%   |
| Team                        | 12       | 16     | 0.35%   |
| Corsair                     | 11       | 13     | 0.32%   |
| Apacer                      | 11       | 12     | 0.32%   |
| JMicron Technology          | 10       | 10     | 0.29%   |
| Gigabyte Technology         | 10       | 10     | 0.29%   |
| Unknown                     | 10       | 11     | 0.29%   |
| GOODRAM                     | 9        | 9      | 0.26%   |
| Kingston Technology Company | 8        | 8      | 0.23%   |
| KingSpec                    | 8        | 8      | 0.23%   |
| Lexar                       | 7        | 8      | 0.2%    |
| AMD                         | 7        | 7      | 0.2%    |
| XPG                         | 6        | 6      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                       | 57       | 1.42%   |
| Seagate ST500DM002-1BD142 500GB                       | 50       | 1.25%   |
| Seagate ST1000DM010-2EP102 1TB                        | 42       | 1.05%   |
| Toshiba HDWD110 1TB                                   | 41       | 1.02%   |
| Seagate ST2000DM008-2FR102 2TB                        | 41       | 1.02%   |
| Samsung SSD 860 EVO 500GB                             | 40       | 1%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB   | 35       | 0.87%   |
| Samsung SSD 860 EVO 1TB                               | 33       | 0.82%   |
| Samsung SSD 850 EVO 250GB                             | 33       | 0.82%   |
| Toshiba DT01ACA100 1TB                                | 29       | 0.72%   |
| Kingston SA400S37480G 480GB SSD                       | 26       | 0.65%   |
| Seagate ST1000DM003-1ER162 1TB                        | 25       | 0.62%   |
| Crucial CT240BX500SSD1 240GB                          | 25       | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 24       | 0.6%    |
| Crucial CT500MX500SSD1 500GB                          | 24       | 0.6%    |
| Seagate ST1000DM003-1CH162 1TB                        | 23       | 0.57%   |
| Toshiba DT01ACA050 500GB                              | 22       | 0.55%   |
| Samsung SSD 860 EVO 250GB                             | 22       | 0.55%   |
| Kingston SA400S37120G 120GB SSD                       | 22       | 0.55%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 21       | 0.52%   |
| Seagate ST4000DM004-2CV104 4TB                        | 21       | 0.52%   |
| Samsung SSD 850 EVO 500GB                             | 20       | 0.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 20       | 0.5%    |
| Crucial CT480BX500SSD1 480GB                          | 20       | 0.5%    |
| Seagate ST3500418AS 500GB                             | 19       | 0.47%   |
| Seagate ST1000DM003-1SB102 1TB                        | 19       | 0.47%   |
| Netac SSD 240GB                                       | 19       | 0.47%   |
| Samsung NVMe SSD Drive 1TB                            | 17       | 0.42%   |
| Kingston SV300S37A120G 120GB SSD                      | 17       | 0.42%   |
| Crucial CT1000MX500SSD1 1TB                           | 17       | 0.42%   |
| Seagate ST2000DM001-1ER164 2TB                        | 16       | 0.4%    |
| Samsung NVMe SSD Drive 500GB                          | 16       | 0.4%    |
| Samsung SSD 980 PRO 1TB                               | 15       | 0.37%   |
| Seagate ST2000DM006-2DM164 2TB                        | 14       | 0.35%   |
| Seagate ST2000DM001-1CH164 2TB                        | 14       | 0.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 14       | 0.35%   |
| Samsung SSD 970 EVO Plus 500GB                        | 14       | 0.35%   |
| Samsung SSD 970 EVO Plus 1TB                          | 14       | 0.35%   |
| WDC WD30EFRX-68EUZN0 3TB                              | 13       | 0.32%   |
| Toshiba DT01ACA200 2TB                                | 13       | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 579      | 806    | 35.59%  |
| WDC                 | 567      | 711    | 34.85%  |
| Toshiba             | 194      | 213    | 11.92%  |
| Hitachi             | 103      | 115    | 6.33%   |
| Samsung Electronics | 76       | 92     | 4.67%   |
| HGST                | 42       | 49     | 2.58%   |
| Maxtor              | 17       | 19     | 1.04%   |
| Unknown             | 14       | 14     | 0.86%   |
| ASMedia             | 4        | 4      | 0.25%   |
| Apple               | 3        | 3      | 0.18%   |
| WD MediaMax         | 2        | 2      | 0.12%   |
| RSH-319             | 2        | 2      | 0.12%   |
| JMicron Technology  | 2        | 2      | 0.12%   |
| HPE                 | 2        | 2      | 0.12%   |
| Fujitsu             | 2        | 2      | 0.12%   |
| ExcelStor           | 2        | 2      | 0.12%   |
| ASMT                | 2        | 3      | 0.12%   |
| Unknown             | 2        | 3      | 0.12%   |
| USB3.0              | 1        | 1      | 0.06%   |
| USB                 | 1        | 1      | 0.06%   |
| SATAFIRM            | 1        | 1      | 0.06%   |
| SAGE                | 1        | 1      | 0.06%   |
| MARVELL             | 1        | 1      | 0.06%   |
| KESU                | 1        | 1      | 0.06%   |
| Intenso             | 1        | 1      | 0.06%   |
| Inateck             | 1        | 1      | 0.06%   |
| HGST HTS            | 1        | 1      | 0.06%   |
| Hewlett-Packard     | 1        | 2      | 0.06%   |
| Hajaan              | 1        | 1      | 0.06%   |
| External            | 1        | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 280      | 355    | 22.62%  |
| Kingston            | 174      | 188    | 14.05%  |
| Crucial             | 143      | 159    | 11.55%  |
| WDC                 | 99       | 105    | 8%      |
| SanDisk             | 87       | 93     | 7.03%   |
| A-DATA Technology   | 41       | 45     | 3.31%   |
| China               | 40       | 45     | 3.23%   |
| Netac               | 26       | 26     | 2.1%    |
| Patriot             | 24       | 25     | 1.94%   |
| SPCC                | 23       | 26     | 1.86%   |
| PNY                 | 19       | 19     | 1.53%   |
| Intel               | 17       | 20     | 1.37%   |
| Transcend           | 13       | 13     | 1.05%   |
| Toshiba             | 13       | 15     | 1.05%   |
| OCZ                 | 13       | 14     | 1.05%   |
| Intenso             | 13       | 14     | 1.05%   |
| Corsair             | 11       | 13     | 0.89%   |
| Team                | 10       | 13     | 0.81%   |
| Apacer              | 10       | 11     | 0.81%   |
| GOODRAM             | 9        | 9      | 0.73%   |
| KingSpec            | 8        | 8      | 0.65%   |
| Gigabyte Technology | 8        | 8      | 0.65%   |
| SK hynix            | 7        | 7      | 0.57%   |
| Micron Technology   | 7        | 7      | 0.57%   |
| Lexar               | 6        | 7      | 0.48%   |
| AMD                 | 6        | 6      | 0.48%   |
| Unknown             | 6        | 6      | 0.48%   |
| Verbatim            | 4        | 4      | 0.32%   |
| TCSUNBOW            | 4        | 4      | 0.32%   |
| Plextor             | 4        | 4      | 0.32%   |
| LITEONIT            | 4        | 4      | 0.32%   |
| LITEON              | 4        | 4      | 0.32%   |
| KingFast            | 4        | 4      | 0.32%   |
| Emtec               | 4        | 4      | 0.32%   |
| WALRAM              | 3        | 3      | 0.24%   |
| TO Exter            | 3        | 3      | 0.24%   |
| Smartbuy            | 3        | 4      | 0.24%   |
| Seagate             | 3        | 3      | 0.24%   |
| NGFF                | 3        | 3      | 0.24%   |
| KingDian            | 3        | 3      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1277     | 2057   | 43.39%  |
| SSD     | 1029     | 1384   | 34.96%  |
| NVMe    | 565      | 766    | 19.2%   |
| Unknown | 60       | 76     | 2.04%   |
| MMC     | 12       | 15     | 0.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1673     | 3349   | 70.32%  |
| NVMe | 558      | 752    | 23.46%  |
| SAS  | 136      | 182    | 5.72%   |
| MMC  | 12       | 15     | 0.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1230     | 1788   | 49.38%  |
| 0.51-1.0   | 704      | 889    | 28.26%  |
| 1.01-2.0   | 269      | 339    | 10.8%   |
| 3.01-4.0   | 124      | 161    | 4.98%   |
| 2.01-3.0   | 73       | 92     | 2.93%   |
| 4.01-10.0  | 72       | 141    | 2.89%   |
| 10.01-20.0 | 19       | 31     | 0.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 407      | 22.2%   |
| 251-500        | 299      | 16.31%  |
| 501-1000       | 282      | 15.38%  |
| 1001-2000      | 208      | 11.35%  |
| More than 3000 | 200      | 10.91%  |
| 1-20           | 116      | 6.33%   |
| Unknown        | 116      | 6.33%   |
| 2001-3000      | 99       | 5.4%    |
| 51-100         | 64       | 3.49%   |
| 21-50          | 42       | 2.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 542      | 29.57%  |
| 21-50          | 259      | 14.13%  |
| 101-250        | 196      | 10.69%  |
| 51-100         | 183      | 9.98%   |
| 501-1000       | 166      | 9.06%   |
| 251-500        | 138      | 7.53%   |
| Unknown        | 116      | 6.33%   |
| 1001-2000      | 106      | 5.78%   |
| More than 3000 | 91       | 4.96%   |
| 2001-3000      | 36       | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 14       | 14     | 4.23%   |
| Seagate ST3500418AS 500GB             | 9        | 10     | 2.72%   |
| Hitachi HDS721050CLA362 500GB         | 5        | 5      | 1.51%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 4        | 4      | 1.21%   |
| Toshiba DT01ACA050 500GB              | 4        | 4      | 1.21%   |
| Seagate ST3250310AS 250GB             | 4        | 4      | 1.21%   |
| WDC WD15EARS-00MVWB0 1TB              | 3        | 3      | 0.91%   |
| Seagate ST9500325AS 500GB             | 3        | 3      | 0.91%   |
| Seagate ST2000DM008-2FR102 2TB        | 3        | 3      | 0.91%   |
| Seagate ST2000DM001-1CH164 2TB        | 3        | 3      | 0.91%   |
| Seagate ST1000DM010-2EP102 1TB        | 3        | 3      | 0.91%   |
| Samsung Electronics SP2504C 250GB     | 3        | 3      | 0.91%   |
| Samsung Electronics HD103UJ 1TB       | 3        | 3      | 0.91%   |
| HGST HTS545050A7E680 500GB            | 3        | 3      | 0.91%   |
| WDC WD5000AAKX-003CA0 500GB           | 2        | 2      | 0.6%    |
| WDC WD5000AADS-00S9B0 500GB           | 2        | 2      | 0.6%    |
| WDC WD4001FAEX-00MJRA0 4TB            | 2        | 2      | 0.6%    |
| WDC WD3200BEVT-22ZCT0 320GB           | 2        | 2      | 0.6%    |
| WDC WD3200AAJS-00L7A0 320GB           | 2        | 2      | 0.6%    |
| WDC WD2500AAJS-00L7A0 250GB           | 2        | 2      | 0.6%    |
| WDC WD10EURX-63FH1Y0 1TB              | 2        | 2      | 0.6%    |
| WDC WD10EARS-00Y5B1 1TB               | 2        | 2      | 0.6%    |
| WDC WD10EARS-00MVWB0 1TB              | 2        | 2      | 0.6%    |
| Toshiba MQ01ABF050 500GB              | 2        | 2      | 0.6%    |
| Toshiba MK1637GSX 160GB               | 2        | 2      | 0.6%    |
| Toshiba HDWD110 1TB                   | 2        | 2      | 0.6%    |
| Toshiba DT01ACA100 1TB                | 2        | 2      | 0.6%    |
| Seagate ST500LT012-9WS142 500GB       | 2        | 2      | 0.6%    |
| Seagate ST500LT012-1DG142 500GB       | 2        | 2      | 0.6%    |
| Seagate ST3500312CS 500GB             | 2        | 2      | 0.6%    |
| Seagate ST3320620AS 320GB             | 2        | 2      | 0.6%    |
| Seagate ST3320613AS 320GB             | 2        | 2      | 0.6%    |
| Seagate ST3250410AS 250GB             | 2        | 2      | 0.6%    |
| Seagate ST3250318AS 250GB             | 2        | 2      | 0.6%    |
| Seagate ST3000DM001-1ER166 3TB        | 2        | 3      | 0.6%    |
| Seagate ST2000DM001-1ER164 2TB        | 2        | 3      | 0.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2        | 2      | 0.6%    |
| Seagate ST1000DM003-1CH162 1TB        | 2        | 2      | 0.6%    |
| Samsung Electronics SSD 870 EVO 500GB | 2        | 2      | 0.6%    |
| Samsung Electronics HM321HI 320GB     | 2        | 2      | 0.6%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 92       | 110    | 29.77%  |
| WDC                 | 84       | 90     | 27.18%  |
| Hitachi             | 33       | 34     | 10.68%  |
| Samsung Electronics | 28       | 32     | 9.06%   |
| Toshiba             | 18       | 18     | 5.83%   |
| Crucial             | 8        | 10     | 2.59%   |
| HGST                | 6        | 6      | 1.94%   |
| Kingston            | 5        | 6      | 1.62%   |
| Intel               | 4        | 4      | 1.29%   |
| SanDisk             | 3        | 3      | 0.97%   |
| Maxtor              | 3        | 4      | 0.97%   |
| Transcend           | 2        | 2      | 0.65%   |
| SK hynix            | 2        | 2      | 0.65%   |
| Innodisk            | 2        | 2      | 0.65%   |
| China               | 2        | 2      | 0.65%   |
| A-DATA Technology   | 2        | 2      | 0.65%   |
| YS                  | 1        | 1      | 0.32%   |
| WD MediaMax         | 1        | 1      | 0.32%   |
| SABRENT             | 1        | 1      | 0.32%   |
| Reeioon             | 1        | 1      | 0.32%   |
| OWC                 | 1        | 1      | 0.32%   |
| OCZ-VERTEX3         | 1        | 1      | 0.32%   |
| Neo                 | 1        | 1      | 0.32%   |
| LITEON              | 1        | 1      | 0.32%   |
| Inateck             | 1        | 1      | 0.32%   |
| HPE                 | 1        | 1      | 0.32%   |
| GLOWAY              | 1        | 1      | 0.32%   |
| Corsair             | 1        | 1      | 0.32%   |
| Avant               | 1        | 1      | 0.32%   |
| Apacer              | 1        | 1      | 0.32%   |
| AMD                 | 1        | 1      | 0.32%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 92       | 110    | 36.51%  |
| WDC                 | 81       | 86     | 32.14%  |
| Hitachi             | 33       | 34     | 13.1%   |
| Toshiba             | 18       | 18     | 7.14%   |
| Samsung Electronics | 16       | 18     | 6.35%   |
| HGST                | 6        | 6      | 2.38%   |
| Maxtor              | 3        | 4      | 1.19%   |
| WD MediaMax         | 1        | 1      | 0.4%    |
| Inateck             | 1        | 1      | 0.4%    |
| HPE                 | 1        | 1      | 0.4%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 226      | 279    | 79.58%  |
| SSD  | 53       | 58     | 18.66%  |
| NVMe | 5        | 5      | 1.76%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)

![Failed Drives](./images/line_chart/drive_failed.svg)

| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC WD800BB-22JHA0 80GB   | 1        | 1      | 50%     |
| WDC WD1600YS-23SHB0 160GB | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)

![Failed Drive Vendor](./images/line_chart/drive_failed_vendor.svg)

| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 2        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)

![Drive Status](./images/line_chart/drive_status.svg)

| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 940      | 2127   | 45.48%  |
| Works    | 855      | 1827   | 41.36%  |
| Malfunc  | 270      | 342    | 13.06%  |
| Failed   | 2        | 2      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 1144     | 43.22%  |
| AMD                            | 615      | 23.23%  |
| Samsung Electronics            | 224      | 8.46%   |
| SanDisk                        | 96       | 3.63%   |
| ASMedia Technology             | 90       | 3.4%    |
| Phison Electronics             | 56       | 2.12%   |
| Kingston Technology Company    | 56       | 2.12%   |
| JMicron Technology             | 50       | 1.89%   |
| Nvidia                         | 49       | 1.85%   |
| Marvell Technology Group       | 48       | 1.81%   |
| Micron/Crucial Technology      | 40       | 1.51%   |
| Silicon Motion                 | 31       | 1.17%   |
| SK hynix                       | 22       | 0.83%   |
| Realtek Semiconductor          | 21       | 0.79%   |
| ADATA Technology               | 13       | 0.49%   |
| LSI Logic / Symbios Logic      | 11       | 0.42%   |
| VIA Technologies               | 10       | 0.38%   |
| Seagate Technology             | 10       | 0.38%   |
| Toshiba America Info Systems   | 8        | 0.3%    |
| Broadcom / LSI                 | 8        | 0.3%    |
| Silicon Image                  | 7        | 0.26%   |
| Micron Technology              | 6        | 0.23%   |
| KIOXIA                         | 6        | 0.23%   |
| Shenzhen Longsys Electronics   | 4        | 0.15%   |
| MAXIO Technology (Hangzhou)    | 4        | 0.15%   |
| Unknown                        | 3        | 0.11%   |
| Lite-On Technology             | 3        | 0.11%   |
| Union Memory (Shenzhen)        | 2        | 0.08%   |
| Netac Technology               | 2        | 0.08%   |
| ULi Electronics                | 1        | 0.04%   |
| Transcend                      | 1        | 0.04%   |
| Solid State Storage Technology | 1        | 0.04%   |
| PMC-Sierra                     | 1        | 0.04%   |
| HighPoint Technologies         | 1        | 0.04%   |
| Biwin Storage Technology       | 1        | 0.04%   |
| Apple                          | 1        | 0.04%   |
| 3ware                          | 1        | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 355      | 10.83%  |
| AMD 400 Series Chipset SATA Controller                                                  | 135      | 4.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 125      | 3.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 124      | 3.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 98       | 2.99%   |
| AMD 500 Series Chipset SATA Controller                                                  | 96       | 2.93%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 88       | 2.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 77       | 2.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 74       | 2.26%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 73       | 2.23%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 71       | 2.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 69       | 2.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 65       | 1.98%   |
| Intel SATA Controller [RAID mode]                                                       | 61       | 1.86%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 57       | 1.74%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 56       | 1.71%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 52       | 1.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 51       | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 44       | 1.34%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 44       | 1.34%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 41       | 1.25%   |
| AMD FCH SATA Controller D                                                               | 40       | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 38       | 1.16%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 36       | 1.1%    |
| Samsung NVMe SSD Controller 980                                                         | 32       | 0.98%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 32       | 0.98%   |
| AMD 300 Series Chipset SATA Controller                                                  | 31       | 0.95%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 29       | 0.88%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 29       | 0.88%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 24       | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 23       | 0.7%    |
| Phison E12 NVMe Controller                                                              | 23       | 0.7%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 22       | 0.67%   |
| Nvidia MCP61 SATA Controller                                                            | 22       | 0.67%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 21       | 0.64%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 21       | 0.64%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 20       | 0.61%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 20       | 0.61%   |
| Kingston Company Company Non-Volatile memory controller                                 | 20       | 0.61%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 19       | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1495     | 57.5%   |
| NVMe | 558      | 21.46%  |
| IDE  | 402      | 15.46%  |
| RAID | 119      | 4.58%   |
| SAS  | 22       | 0.85%   |
| SCSI | 4        | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 1166     | 63.61%  |
| AMD              | 662      | 36.12%  |
| Unknown          | 2        | 0.11%   |
| PowerNV FP5466G2 | 1        | 0.05%   |
| IBM/S390         | 1        | 0.05%   |
| CentaurHauls     | 1        | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 44       | 2.4%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 34       | 1.85%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 31       | 1.69%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 29       | 1.58%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 24       | 1.31%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 23       | 1.25%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 23       | 1.25%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 22       | 1.2%    |
| AMD FX-8350 Eight-Core Processor            | 20       | 1.09%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 19       | 1.04%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 19       | 1.04%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 18       | 0.98%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 18       | 0.98%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 17       | 0.93%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 16       | 0.87%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 15       | 0.82%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 15       | 0.82%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 15       | 0.82%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 15       | 0.82%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 14       | 0.76%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 13       | 0.71%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 13       | 0.71%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 13       | 0.71%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 12       | 0.65%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 12       | 0.65%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 11       | 0.6%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 11       | 0.6%    |
| Intel Core i7-2600 CPU @ 3.40GHz            | 11       | 0.6%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 11       | 0.6%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 11       | 0.6%    |
| Intel Core i3-2100 CPU @ 3.10GHz            | 11       | 0.6%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 11       | 0.6%    |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 10       | 0.55%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 10       | 0.55%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 10       | 0.55%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 10       | 0.55%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 10       | 0.55%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 10       | 0.55%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 10       | 0.55%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 10       | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 294      | 16.04%  |
| Intel Core i7           | 203      | 11.07%  |
| AMD Ryzen 5             | 192      | 10.47%  |
| Intel Core i3           | 166      | 9.06%   |
| AMD Ryzen 7             | 120      | 6.55%   |
| Intel Xeon              | 106      | 5.78%   |
| Other                   | 82       | 4.47%   |
| Intel Core 2 Duo        | 66       | 3.6%    |
| Intel Celeron           | 64       | 3.49%   |
| AMD Ryzen 9             | 64       | 3.49%   |
| AMD FX                  | 59       | 3.22%   |
| Intel Pentium           | 50       | 2.73%   |
| Intel Pentium Dual-Core | 32       | 1.75%   |
| Intel Core 2 Quad       | 28       | 1.53%   |
| AMD Ryzen 3             | 25       | 1.36%   |
| Intel Core i9           | 20       | 1.09%   |
| AMD A10                 | 20       | 1.09%   |
| AMD Athlon II X2        | 18       | 0.98%   |
| AMD Ryzen Threadripper  | 16       | 0.87%   |
| AMD Athlon II X4        | 14       | 0.76%   |
| AMD Athlon 64 X2        | 14       | 0.76%   |
| Intel Pentium Gold      | 13       | 0.71%   |
| AMD A6                  | 13       | 0.71%   |
| AMD Phenom II X4        | 12       | 0.65%   |
| AMD A8                  | 12       | 0.65%   |
| Intel Core 2            | 11       | 0.6%    |
| Intel Atom              | 11       | 0.6%    |
| AMD Ryzen 5 PRO         | 10       | 0.55%   |
| AMD Athlon              | 10       | 0.55%   |
| Intel Pentium Dual      | 9        | 0.49%   |
| AMD Phenom II X6        | 9        | 0.49%   |
| Intel Pentium D         | 6        | 0.33%   |
| Intel Pentium 4         | 6        | 0.33%   |
| AMD A4                  | 6        | 0.33%   |
| AMD Ryzen 7 PRO         | 5        | 0.27%   |
| AMD Phenom II X2        | 5        | 0.27%   |
| AMD Sempron             | 4        | 0.22%   |
| AMD Opteron             | 4        | 0.22%   |
| AMD Athlon II X3        | 4        | 0.22%   |
| AMD Ryzen 3 PRO         | 3        | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 666      | 36.33%  |
| 2       | 463      | 25.26%  |
| 6       | 295      | 16.09%  |
| 8       | 214      | 11.67%  |
| 12      | 73       | 3.98%   |
| 16      | 35       | 1.91%   |
| 1       | 29       | 1.58%   |
| 10      | 20       | 1.09%   |
| 3       | 19       | 1.04%   |
| 32      | 7        | 0.38%   |
| 20      | 4        | 0.22%   |
| Unknown | 3        | 0.16%   |
| 24      | 2        | 0.11%   |
| 18      | 2        | 0.11%   |
| 44      | 1        | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1804     | 98.42%  |
| 2       | 26       | 1.42%   |
| Unknown | 3        | 0.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1100     | 60.01%  |
| 1       | 729      | 39.77%  |
| Unknown | 3        | 0.16%   |
| 4       | 1        | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1828     | 99.73%  |
| Unknown        | 3        | 0.16%   |
| 32-bit         | 2        | 0.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 509      | 27.77%  |
| 0x306c3    | 125      | 6.82%   |
| 0x306a9    | 96       | 5.24%   |
| 0x08701021 | 88       | 4.8%    |
| 0x206a7    | 87       | 4.75%   |
| 0x1067a    | 72       | 3.93%   |
| 0x506e3    | 54       | 2.95%   |
| 0xa0653    | 45       | 2.45%   |
| 0x906ea    | 44       | 2.4%    |
| 0x0a201016 | 44       | 2.4%    |
| 0x0800820d | 40       | 2.18%   |
| 0xa0655    | 32       | 1.75%   |
| 0xa0671    | 28       | 1.53%   |
| 0x906e9    | 25       | 1.36%   |
| 0x08108109 | 23       | 1.25%   |
| 0x010000c8 | 22       | 1.2%    |
| 0x90672    | 20       | 1.09%   |
| 0x06000852 | 20       | 1.09%   |
| 0x6fb      | 16       | 0.87%   |
| 0x906eb    | 15       | 0.82%   |
| 0x306f2    | 15       | 0.82%   |
| 0x06001119 | 15       | 0.82%   |
| 0x0a50000d | 13       | 0.71%   |
| 0x08701013 | 13       | 0.71%   |
| 0x906ed    | 12       | 0.65%   |
| 0x6fd      | 12       | 0.65%   |
| 0x206d7    | 12       | 0.65%   |
| 0x06003106 | 12       | 0.65%   |
| 0x106e5    | 11       | 0.6%    |
| 0x08001138 | 11       | 0.6%    |
| 0x20655    | 10       | 0.55%   |
| 0x0a50000c | 10       | 0.55%   |
| 0x08600106 | 10       | 0.55%   |
| 0x08001137 | 10       | 0.55%   |
| 0x0a20120a | 9        | 0.49%   |
| 0x0a201009 | 9        | 0.49%   |
| 0x706a8    | 8        | 0.44%   |
| 0x306e4    | 8        | 0.44%   |
| 0x06000822 | 8        | 0.44%   |
| 0x406c4    | 7        | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 202      | 11.02%  |
| Zen 2            | 154      | 8.4%    |
| Zen 3            | 141      | 7.69%   |
| KabyLake         | 139      | 7.58%   |
| IvyBridge        | 139      | 7.58%   |
| SandyBridge      | 131      | 7.15%   |
| Penryn           | 110      | 6%      |
| Zen+             | 89       | 4.86%   |
| Skylake          | 89       | 4.86%   |
| CometLake        | 88       | 4.8%    |
| Piledriver       | 76       | 4.15%   |
| K10              | 71       | 3.87%   |
| Zen              | 56       | 3.06%   |
| Core             | 48       | 2.62%   |
| Unknown          | 43       | 2.35%   |
| Westmere         | 31       | 1.69%   |
| Silvermont       | 31       | 1.69%   |
| Nehalem          | 30       | 1.64%   |
| Icelake          | 21       | 1.15%   |
| Alderlake Hybrid | 21       | 1.15%   |
| K8 Hammer        | 18       | 0.98%   |
| Steamroller      | 17       | 0.93%   |
| NetBurst         | 14       | 0.76%   |
| Excavator        | 12       | 0.65%   |
| Broadwell        | 11       | 0.6%    |
| Goldmont plus    | 10       | 0.55%   |
| Bulldozer        | 9        | 0.49%   |
| Jaguar           | 7        | 0.38%   |
| Goldmont         | 7        | 0.38%   |
| K10 Llano        | 5        | 0.27%   |
| TigerLake        | 4        | 0.22%   |
| Bonnell          | 4        | 0.22%   |
| Puma             | 3        | 0.16%   |
| Tremont          | 2        | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 782      | 40.31%  |
| Intel                      | 580      | 29.9%   |
| AMD                        | 556      | 28.66%  |
| ASPEED Technology          | 11       | 0.57%   |
| Matrox Electronics Systems | 7        | 0.36%   |
| VIA Technologies           | 2        | 0.1%    |
| ATI Technologies           | 2        | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 88       | 4.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 84       | 4.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 69       | 3.49%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 44       | 2.23%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 43       | 2.18%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 43       | 2.18%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 39       | 1.97%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 39       | 1.97%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 39       | 1.97%   |
| Intel HD Graphics 530                                                                    | 36       | 1.82%   |
| AMD Cezanne                                                                              | 31       | 1.57%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 27       | 1.37%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 26       | 1.32%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 25       | 1.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 25       | 1.27%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 25       | 1.27%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 23       | 1.16%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 23       | 1.16%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 22       | 1.11%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 21       | 1.06%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 19       | 0.96%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 19       | 0.96%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 19       | 0.96%   |
| Nvidia GT218 [GeForce 210]                                                               | 18       | 0.91%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 18       | 0.91%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 18       | 0.91%   |
| Intel HD Graphics 630                                                                    | 18       | 0.91%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 18       | 0.91%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 17       | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 17       | 0.86%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 16       | 0.81%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 15       | 0.76%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 15       | 0.76%   |
| AMD Renoir                                                                               | 15       | 0.76%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 15       | 0.76%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 14       | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 14       | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 13       | 0.66%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 12       | 0.61%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 12       | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Nvidia              | 717      | 39.12%  |
| 1 x AMD                 | 502      | 27.39%  |
| 1 x Intel               | 493      | 26.9%   |
| Intel + Nvidia          | 31       | 1.69%   |
| 2 x AMD                 | 23       | 1.25%   |
| AMD + Nvidia            | 15       | 0.82%   |
| 2 x Nvidia              | 13       | 0.71%   |
| Intel + AMD             | 10       | 0.55%   |
| Other                   | 5        | 0.27%   |
| 1 x ASPEED              | 5        | 0.27%   |
| 2 x Intel               | 3        | 0.16%   |
| Nvidia + ASPEED         | 3        | 0.16%   |
| 1 x Matrox              | 3        | 0.16%   |
| AMD + Matrox            | 3        | 0.16%   |
| 1 x VIA                 | 2        | 0.11%   |
| AMD + ASPEED            | 2        | 0.11%   |
| 3 x AMD                 | 1        | 0.05%   |
| 2 x Nvidia + 1 x ASPEED | 1        | 0.05%   |
| Nvidia + Matrox         | 1        | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1268     | 69.18%  |
| Proprietary | 441      | 24.06%  |
| Unknown     | 124      | 6.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 893      | 48.72%  |
| 1.01-2.0   | 198      | 10.8%   |
| 0.51-1.0   | 161      | 8.78%   |
| 7.01-8.0   | 154      | 8.4%    |
| 3.01-4.0   | 150      | 8.18%   |
| 0.01-0.5   | 116      | 6.33%   |
| 8.01-16.0  | 68       | 3.71%   |
| 5.01-6.0   | 56       | 3.06%   |
| 2.01-3.0   | 25       | 1.36%   |
| 16.01-24.0 | 10       | 0.55%   |
| 4.01-5.0   | 2        | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 317      | 17.4%   |
| Goldstar             | 214      | 11.75%  |
| Dell                 | 168      | 9.22%   |
| AOC                  | 145      | 7.96%   |
| Hewlett-Packard      | 122      | 6.7%    |
| Acer                 | 119      | 6.53%   |
| BenQ                 | 88       | 4.83%   |
| Philips              | 87       | 4.77%   |
| Ancor Communications | 75       | 4.12%   |
| ASUSTek Computer     | 37       | 2.03%   |
| ViewSonic            | 33       | 1.81%   |
| Lenovo               | 32       | 1.76%   |
| Iiyama               | 27       | 1.48%   |
| LG Electronics       | 21       | 1.15%   |
| Sony                 | 19       | 1.04%   |
| MSI                  | 16       | 0.88%   |
| Eizo                 | 14       | 0.77%   |
| Vizio                | 12       | 0.66%   |
| Fujitsu Siemens      | 12       | 0.66%   |
| NEC Computers        | 11       | 0.6%    |
| Unknown              | 10       | 0.55%   |
| Unknown              | 9        | 0.49%   |
| Sceptre Tech         | 8        | 0.44%   |
| Medion               | 8        | 0.44%   |
| Mi                   | 7        | 0.38%   |
| Gigabyte Technology  | 7        | 0.38%   |
| Toshiba              | 6        | 0.33%   |
| Panasonic            | 6        | 0.33%   |
| Hitachi              | 6        | 0.33%   |
| HannStar             | 6        | 0.33%   |
| ___                  | 5        | 0.27%   |
| Vestel Elektronik    | 5        | 0.27%   |
| HPN                  | 5        | 0.27%   |
| CHR                  | 5        | 0.27%   |
| Sharp                | 4        | 0.22%   |
| RTK                  | 4        | 0.22%   |
| Packard Bell         | 4        | 0.22%   |
| HKC                  | 4        | 0.22%   |
| Gateway              | 4        | 0.22%   |
| FUS                  | 4        | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 23       | 1.19%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 19       | 0.98%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 13       | 0.67%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                      | 9        | 0.47%   |
| Unknown                                                               | 9        | 0.47%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 8        | 0.41%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 8        | 0.41%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 8        | 0.41%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 8        | 0.41%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 7        | 0.36%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 7        | 0.36%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 7        | 0.36%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 7        | 0.36%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 7        | 0.36%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 7        | 0.36%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 6        | 0.31%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch    | 5        | 0.26%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 480x270mm 21.7-inch     | 5        | 0.26%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 5        | 0.26%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 5        | 0.26%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                | 5        | 0.26%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 600x340mm 27.2-inch                | 5        | 0.26%   |
| CHR CH7511B CHR7511 1920x1080 519x324mm 24.1-inch                     | 5        | 0.26%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 5        | 0.26%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 5        | 0.26%   |
| AOC 27B1 AOC2701 1920x1080 598x336mm 27.0-inch                        | 5        | 0.26%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 5        | 0.26%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                      | 5        | 0.26%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 380x300mm 19.1-inch  | 4        | 0.21%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 4        | 0.21%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 4        | 0.21%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 4        | 0.21%   |
| Samsung Electronics S22C200 SAM09B7 1920x1080 477x268mm 21.5-inch     | 4        | 0.21%   |
| Goldstar LG ULTRAWIDE GSM76F9 2560x1080 800x340mm 34.2-inch           | 4        | 0.21%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 4        | 0.21%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 4        | 0.21%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                          | 4        | 0.21%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 4        | 0.21%   |
| Acer R240HY ACR046F 1920x1080 527x296mm 23.8-inch                     | 4        | 0.21%   |
| ___ TV ___9000 1360x768                                               | 3        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 814      | 45.47%  |
| 3840x2160 (4K)     | 186      | 10.39%  |
| 2560x1440 (QHD)    | 139      | 7.77%   |
| 1280x1024 (SXGA)   | 111      | 6.2%    |
| 1680x1050 (WSXGA+) | 89       | 4.97%   |
| 1366x768 (WXGA)    | 67       | 3.74%   |
| 1440x900 (WXGA+)   | 65       | 3.63%   |
| 1920x1200 (WUXGA)  | 50       | 2.79%   |
| 1600x900 (HD+)     | 47       | 2.63%   |
| 2560x1080          | 34       | 1.9%    |
| Unknown            | 33       | 1.84%   |
| 3440x1440          | 30       | 1.68%   |
| 1360x768           | 23       | 1.28%   |
| 3840x1080          | 18       | 1.01%   |
| 1920x540           | 13       | 0.73%   |
| 1600x1200          | 9        | 0.5%    |
| 1024x768 (XGA)     | 9        | 0.5%    |
| 1280x720 (HD)      | 8        | 0.45%   |
| 2560x1600          | 7        | 0.39%   |
| 2288x1287          | 5        | 0.28%   |
| 3840x1600          | 3        | 0.17%   |
| 5760x1080          | 2        | 0.11%   |
| 3600x1080          | 2        | 0.11%   |
| 3280x1080          | 2        | 0.11%   |
| 1400x1050          | 2        | 0.11%   |
| 1280x960           | 2        | 0.11%   |
| 1152x864           | 2        | 0.11%   |
| 8320x1440          | 1        | 0.06%   |
| 800x480            | 1        | 0.06%   |
| 6400x2160          | 1        | 0.06%   |
| 6400x1080          | 1        | 0.06%   |
| 5760x2160          | 1        | 0.06%   |
| 5120x1440          | 1        | 0.06%   |
| 5040x1050          | 1        | 0.06%   |
| 4000x2560          | 1        | 0.06%   |
| 3840x1200          | 1        | 0.06%   |
| 3600x1200          | 1        | 0.06%   |
| 3520x1080          | 1        | 0.06%   |
| 3286x1080          | 1        | 0.06%   |
| 3200x1080          | 1        | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 279      | 15.36%  |
| 24      | 270      | 14.87%  |
| 23      | 233      | 12.83%  |
| 21      | 197      | 10.85%  |
| Unknown | 136      | 7.49%   |
| 19      | 124      | 6.83%   |
| 31      | 78       | 4.3%    |
| 18      | 76       | 4.19%   |
| 22      | 59       | 3.25%   |
| 20      | 53       | 2.92%   |
| 34      | 51       | 2.81%   |
| 17      | 46       | 2.53%   |
| 15      | 24       | 1.32%   |
| 84      | 23       | 1.27%   |
| 32      | 22       | 1.21%   |
| 72      | 12       | 0.66%   |
| 54      | 12       | 0.66%   |
| 25      | 12       | 0.66%   |
| 28      | 10       | 0.55%   |
| 48      | 9        | 0.5%    |
| 26      | 9        | 0.5%    |
| 40      | 8        | 0.44%   |
| 33      | 8        | 0.44%   |
| 37      | 6        | 0.33%   |
| 29      | 6        | 0.33%   |
| 60      | 5        | 0.28%   |
| 52      | 5        | 0.28%   |
| 46      | 5        | 0.28%   |
| 39      | 4        | 0.22%   |
| 142     | 3        | 0.17%   |
| 65      | 3        | 0.17%   |
| 64      | 3        | 0.17%   |
| 42      | 3        | 0.17%   |
| 36      | 3        | 0.17%   |
| 75      | 2        | 0.11%   |
| 47      | 2        | 0.11%   |
| 38      | 2        | 0.11%   |
| 86      | 1        | 0.06%   |
| 69      | 1        | 0.06%   |
| 63      | 1        | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 711      | 40.33%  |
| 401-500        | 435      | 24.67%  |
| 601-700        | 138      | 7.83%   |
| Unknown        | 136      | 7.71%   |
| 701-800        | 83       | 4.71%   |
| 351-400        | 73       | 4.14%   |
| 301-350        | 69       | 3.91%   |
| 1001-1500      | 48       | 2.72%   |
| 1501-2000      | 39       | 2.21%   |
| 801-900        | 21       | 1.19%   |
| 901-1000       | 5        | 0.28%   |
| More than 2000 | 3        | 0.17%   |
| 201-300        | 1        | 0.06%   |
| 101-200        | 1        | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1132     | 67.22%  |
| 16/10   | 218      | 12.95%  |
| Unknown | 113      | 6.71%   |
| 5/4     | 103      | 6.12%   |
| 21/9    | 60       | 3.56%   |
| 4/3     | 24       | 1.43%   |
| 6/5     | 10       | 0.59%   |
| 32/9    | 8        | 0.48%   |
| 3/2     | 8        | 0.48%   |
| 1.00    | 4        | 0.24%   |
| 2.00    | 1        | 0.06%   |
| 1.98    | 1        | 0.06%   |
| 1.96    | 1        | 0.06%   |
| 0.80    | 1        | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 591      | 33.31%  |
| 301-350        | 284      | 16.01%  |
| 151-200        | 239      | 13.47%  |
| 351-500        | 169      | 9.53%   |
| Unknown        | 136      | 7.67%   |
| 251-300        | 108      | 6.09%   |
| 141-150        | 101      | 5.69%   |
| More than 1000 | 78       | 4.4%    |
| 501-1000       | 39       | 2.2%    |
| 101-110        | 17       | 0.96%   |
| 111-120        | 6        | 0.34%   |
| 131-140        | 2        | 0.11%   |
| 81-90          | 1        | 0.06%   |
| 71-80          | 1        | 0.06%   |
| 1-40           | 1        | 0.06%   |
| 91-100         | 1        | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1089     | 63.31%  |
| 101-120 | 319      | 18.55%  |
| Unknown | 136      | 7.91%   |
| 121-160 | 73       | 4.24%   |
| 1-50    | 67       | 3.9%    |
| 161-240 | 36       | 2.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1374     | 74.96%  |
| 2     | 276      | 15.06%  |
| 0     | 146      | 7.97%   |
| 3     | 33       | 1.8%    |
| 4     | 3        | 0.16%   |
| 6     | 1        | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1170     | 45.24%  |
| Intel                                  | 770      | 29.78%  |
| Qualcomm Atheros                       | 150      | 5.8%    |
| Ralink Technology                      | 67       | 2.59%   |
| TP-Link                                | 62       | 2.4%    |
| Broadcom                               | 59       | 2.28%   |
| Nvidia                                 | 42       | 1.62%   |
| MediaTek                               | 26       | 1.01%   |
| Microsoft                              | 20       | 0.77%   |
| Ralink                                 | 16       | 0.62%   |
| Marvell Technology Group               | 15       | 0.58%   |
| NetGear                                | 13       | 0.5%    |
| Samsung Electronics                    | 12       | 0.46%   |
| Qualcomm Atheros Communications        | 12       | 0.46%   |
| D-Link                                 | 12       | 0.46%   |
| Aquantia                               | 12       | 0.46%   |
| Broadcom Limited                       | 11       | 0.43%   |
| VIA Technologies                       | 10       | 0.39%   |
| D-Link System                          | 9        | 0.35%   |
| Xiaomi                                 | 8        | 0.31%   |
| Huawei Technologies                    | 7        | 0.27%   |
| IMC Networks                           | 6        | 0.23%   |
| ASUSTek Computer                       | 6        | 0.23%   |
| ASIX Electronics                       | 5        | 0.19%   |
| Qualcomm                               | 4        | 0.15%   |
| Microchip Technology                   | 4        | 0.15%   |
| InterBiometrics                        | 4        | 0.15%   |
| Edimax Technology                      | 4        | 0.15%   |
| Motorola PCS                           | 3        | 0.12%   |
| Mellanox Technologies                  | 3        | 0.12%   |
| Linksys                                | 3        | 0.12%   |
| American Megatrends                    | 3        | 0.12%   |
| U-Blox                                 | 2        | 0.08%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.08%   |
| Sitecom Europe                         | 2        | 0.08%   |
| Google                                 | 2        | 0.08%   |
| Belkin Components                      | 2        | 0.08%   |
| AVM                                    | 2        | 0.08%   |
| Unknown                                | 2        | 0.08%   |
| ZyXEL Communications                   | 1        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 912      | 31.14%  |
| Intel I211 Gigabit Network Connection                             | 118      | 4.03%   |
| Intel Wi-Fi 6 AX200                                               | 113      | 3.86%   |
| Realtek RTL8125 2.5GbE Controller                                 | 112      | 3.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 75       | 2.56%   |
| Intel Ethernet Controller I225-V                                  | 60       | 2.05%   |
| Intel Ethernet Connection (2) I219-V                              | 51       | 1.74%   |
| Realtek 802.11ac NIC                                              | 47       | 1.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 43       | 1.47%   |
| Intel Ethernet Connection I217-LM                                 | 43       | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 34       | 1.16%   |
| Intel 82579V Gigabit Network Connection                           | 30       | 1.02%   |
| Ralink MT7601U Wireless Adapter                                   | 29       | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 29       | 0.99%   |
| Intel Ethernet Connection (7) I219-V                              | 26       | 0.89%   |
| Intel Ethernet Connection (2) I218-V                              | 26       | 0.89%   |
| Intel Wireless-AC 9260                                            | 24       | 0.82%   |
| Intel I210 Gigabit Network Connection                             | 23       | 0.79%   |
| Intel 82574L Gigabit Network Connection                           | 23       | 0.79%   |
| Intel Wireless 7265                                               | 21       | 0.72%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 21       | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 20       | 0.68%   |
| Nvidia MCP61 Ethernet                                             | 20       | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 20       | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 18       | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17       | 0.58%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 16       | 0.55%   |
| Intel Ethernet Connection I217-V                                  | 16       | 0.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14       | 0.48%   |
| Ralink RT5370 Wireless Adapter                                    | 14       | 0.48%   |
| Intel Ethernet Connection (14) I219-V                             | 14       | 0.48%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 14       | 0.48%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 13       | 0.44%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 12       | 0.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 12       | 0.41%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 12       | 0.41%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 11       | 0.38%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 11       | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11       | 0.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 11       | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 306      | 35.33%  |
| Realtek Semiconductor           | 194      | 22.4%   |
| Qualcomm Atheros                | 70       | 8.08%   |
| Ralink Technology               | 67       | 7.74%   |
| TP-Link                         | 59       | 6.81%   |
| Broadcom                        | 26       | 3%      |
| MediaTek                        | 25       | 2.89%   |
| Microsoft                       | 20       | 2.31%   |
| Ralink                          | 16       | 1.85%   |
| NetGear                         | 13       | 1.5%    |
| Qualcomm Atheros Communications | 12       | 1.39%   |
| D-Link                          | 12       | 1.39%   |
| D-Link System                   | 7        | 0.81%   |
| IMC Networks                    | 6        | 0.69%   |
| ASUSTek Computer                | 6        | 0.69%   |
| Edimax Technology               | 4        | 0.46%   |
| Linksys                         | 3        | 0.35%   |
| Broadcom Limited                | 3        | 0.35%   |
| Sitecom Europe                  | 2        | 0.23%   |
| Belkin Components               | 2        | 0.23%   |
| AVM                             | 2        | 0.23%   |
| ZyXEL Communications            | 1        | 0.12%   |
| ZyDAS                           | 1        | 0.12%   |
| Wilocity                        | 1        | 0.12%   |
| Wacom                           | 1        | 0.12%   |
| Tenda                           | 1        | 0.12%   |
| Micro Star International        | 1        | 0.12%   |
| Mercucys                        | 1        | 0.12%   |
| Marvell Technology Group        | 1        | 0.12%   |
| Guillemot                       | 1        | 0.12%   |
| Gemtek                          | 1        | 0.12%   |
| BUFFALO                         | 1        | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 113      | 12.91%  |
| Realtek 802.11ac NIC                                           | 47       | 5.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 34       | 3.89%   |
| Ralink MT7601U Wireless Adapter                                | 29       | 3.31%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 29       | 3.31%   |
| Intel Wireless-AC 9260                                         | 24       | 2.74%   |
| Intel Wireless 7265                                            | 21       | 2.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 20       | 2.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 18       | 2.06%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 16       | 1.83%   |
| Ralink RT5370 Wireless Adapter                                 | 14       | 1.6%    |
| Intel Alder Lake-S PCH CNVi WiFi                               | 14       | 1.6%    |
| Ralink RT2870/RT3070 Wireless Adapter                          | 13       | 1.49%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 12       | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 12       | 1.37%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 11       | 1.26%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 11       | 1.26%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 11       | 1.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 11       | 1.26%   |
| Qualcomm Atheros AR9271 802.11n                                | 11       | 1.26%   |
| Intel Wireless 3165                                            | 11       | 1.26%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 11       | 1.26%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 10       | 1.14%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 10       | 1.14%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 9        | 1.03%   |
| Microsoft XBOX ACC                                             | 9        | 1.03%   |
| Microsoft Xbox 360 Wireless Adapter                            | 9        | 1.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 8        | 0.91%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 8        | 0.91%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 8        | 0.91%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 7        | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 7        | 0.8%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 7        | 0.8%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 6        | 0.69%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 6        | 0.69%   |
| Realtek RTL8187 Wireless Adapter                               | 6        | 0.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6        | 0.69%   |
| Intel Wireless 8260                                            | 6        | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6        | 0.69%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]           | 6        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1087     | 55.18%  |
| Intel                                  | 620      | 31.47%  |
| Qualcomm Atheros                       | 86       | 4.37%   |
| Nvidia                                 | 42       | 2.13%   |
| Broadcom                               | 33       | 1.68%   |
| Marvell Technology Group               | 14       | 0.71%   |
| Samsung Electronics                    | 12       | 0.61%   |
| Aquantia                               | 12       | 0.61%   |
| VIA Technologies                       | 10       | 0.51%   |
| Xiaomi                                 | 8        | 0.41%   |
| Broadcom Limited                       | 8        | 0.41%   |
| ASIX Electronics                       | 5        | 0.25%   |
| Qualcomm                               | 4        | 0.2%    |
| Huawei Technologies                    | 4        | 0.2%    |
| TP-Link                                | 3        | 0.15%   |
| Motorola PCS                           | 3        | 0.15%   |
| Mellanox Technologies                  | 3        | 0.15%   |
| American Megatrends                    | 3        | 0.15%   |
| Google                                 | 2        | 0.1%    |
| D-Link System                          | 2        | 0.1%    |
| Spreadtrum Communications              | 1        | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.05%   |
| OPPO Electronics                       | 1        | 0.05%   |
| OnePlus Technology (Shenzhen)          | 1        | 0.05%   |
| JMicron Technology                     | 1        | 0.05%   |
| Emulex                                 | 1        | 0.05%   |
| DisplayLink                            | 1        | 0.05%   |
| ADMtek                                 | 1        | 0.05%   |
| 3Com                                   | 1        | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 912      | 44.93%  |
| Intel I211 Gigabit Network Connection                             | 118      | 5.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 112      | 5.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 75       | 3.69%   |
| Intel Ethernet Controller I225-V                                  | 60       | 2.96%   |
| Intel Ethernet Connection (2) I219-V                              | 51       | 2.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 43       | 2.12%   |
| Intel Ethernet Connection I217-LM                                 | 43       | 2.12%   |
| Intel 82579V Gigabit Network Connection                           | 30       | 1.48%   |
| Intel Ethernet Connection (7) I219-V                              | 26       | 1.28%   |
| Intel Ethernet Connection (2) I218-V                              | 26       | 1.28%   |
| Intel I210 Gigabit Network Connection                             | 23       | 1.13%   |
| Intel 82574L Gigabit Network Connection                           | 23       | 1.13%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 21       | 1.03%   |
| Nvidia MCP61 Ethernet                                             | 20       | 0.99%   |
| Intel Ethernet Connection (2) I219-LM                             | 20       | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17       | 0.84%   |
| Intel Ethernet Connection I217-V                                  | 16       | 0.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14       | 0.69%   |
| Intel Ethernet Connection (14) I219-V                             | 14       | 0.69%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 12       | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11       | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11       | 0.54%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 10       | 0.49%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 9        | 0.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 8        | 0.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 8        | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 8        | 0.39%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8        | 0.39%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 8        | 0.39%   |
| Intel Ethernet Connection (2) I218-LM                             | 8        | 0.39%   |
| Intel Ethernet Connection (11) I219-V                             | 8        | 0.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 7        | 0.34%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7        | 0.34%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 7        | 0.34%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 6        | 0.3%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6        | 0.3%    |
| Nvidia MCP77 Ethernet                                             | 6        | 0.3%    |
| Intel Ethernet Controller X550                                    | 6        | 0.3%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 6        | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1816     | 68.43%  |
| WiFi     | 814      | 30.67%  |
| Modem    | 19       | 0.72%   |
| Unknown  | 5        | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1422     | 75.76%  |
| WiFi     | 453      | 24.13%  |
| Unknown  | 2        | 0.11%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1164     | 63.5%   |
| 2     | 563      | 30.71%  |
| 3     | 82       | 4.47%   |
| 0     | 13       | 0.71%   |
| 4     | 7        | 0.38%   |
| 12    | 1        | 0.05%   |
| 8     | 1        | 0.05%   |
| 6     | 1        | 0.05%   |
| 5     | 1        | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1353     | 73.81%  |
| Yes  | 480      | 26.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 284      | 46.03%  |
| Cambridge Silicon Radio         | 134      | 21.72%  |
| Realtek Semiconductor           | 44       | 7.13%   |
| ASUSTek Computer                | 33       | 5.35%   |
| Broadcom                        | 28       | 4.54%   |
| Qualcomm Atheros Communications | 22       | 3.57%   |
| MediaTek                        | 17       | 2.76%   |
| IMC Networks                    | 11       | 1.78%   |
| Apple                           | 10       | 1.62%   |
| TP-Link                         | 7        | 1.13%   |
| Lite-On Technology              | 4        | 0.65%   |
| Integrated System Solution      | 3        | 0.49%   |
| Foxconn / Hon Hai               | 3        | 0.49%   |
| Edimax Technology               | 3        | 0.49%   |
| Belkin Components               | 2        | 0.32%   |
| Toshiba                         | 1        | 0.16%   |
| SINO WEALTH                     | 1        | 0.16%   |
| Realtek                         | 1        | 0.16%   |
| Ralink                          | 1        | 0.16%   |
| Logitech                        | 1        | 0.16%   |
| HTC (High Tech Computer)        | 1        | 0.16%   |
| Hewlett-Packard                 | 1        | 0.16%   |
| Dell                            | 1        | 0.16%   |
| D-Link System                   | 1        | 0.16%   |
| D-Link                          | 1        | 0.16%   |
| Cypress Semiconductor           | 1        | 0.16%   |
| Unknown                         | 1        | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 134      | 21.72%  |
| Intel AX200 Bluetooth                                 | 106      | 17.18%  |
| Intel Bluetooth wireless interface                    | 45       | 7.29%   |
| Realtek Bluetooth Radio                               | 33       | 5.35%   |
| Intel Wireless-AC 3168 Bluetooth                      | 33       | 5.35%   |
| Intel AX210 Bluetooth                                 | 28       | 4.54%   |
| Intel AX201 Bluetooth                                 | 26       | 4.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 24       | 3.89%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 19       | 3.08%   |
| MediaTek Wireless_Device                              | 17       | 2.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 16       | 2.59%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 14       | 2.27%   |
| Realtek  Bluetooth 4.2 Adapter                        | 10       | 1.62%   |
| ASUS ASUS USB-BT500                                   | 8        | 1.3%    |
| TP-Link UB500 Adapter                                 | 7        | 1.13%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 7        | 1.13%   |
| Qualcomm Atheros  Bluetooth Device                    | 6        | 0.97%   |
| IMC Networks Bluetooth Radio                          | 6        | 0.97%   |
| ASUS Bluetooth Radio                                  | 6        | 0.97%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 4        | 0.65%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 4        | 0.65%   |
| Apple Bluetooth USB Host Controller                   | 4        | 0.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 3        | 0.49%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 3        | 0.49%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 3        | 0.49%   |
| Edimax Bluetooth Adapter                              | 3        | 0.49%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 3        | 0.49%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 2        | 0.32%   |
| Lite-On Bluetooth Device                              | 2        | 0.32%   |
| Intel Bluetooth Device                                | 2        | 0.32%   |
| IMC Networks Wireless_Device                          | 2        | 0.32%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2        | 0.32%   |
| Broadcom BCM2045 Bluetooth                            | 2        | 0.32%   |
| ASUS BCM20702A0                                       | 2        | 0.32%   |
| Toshiba Bluetooth USB Host Controller                 | 1        | 0.16%   |
| SINO WEALTH RK Bluetooth Keyboar                      | 1        | 0.16%   |
| Realtek RTL8723B Bluetooth                            | 1        | 0.16%   |
| Realtek Bluetooth Radio                               | 1        | 0.16%   |
| Ralink RT3290 Bluetooth                               | 1        | 0.16%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1        | 0.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 1107     | 35.56%  |
| AMD                     | 785      | 25.22%  |
| Nvidia                  | 741      | 23.8%   |
| C-Media Electronics     | 86       | 2.76%   |
| Logitech                | 43       | 1.38%   |
| Creative Labs           | 41       | 1.32%   |
| Texas Instruments       | 24       | 0.77%   |
| Razer USA               | 17       | 0.55%   |
| JMTek                   | 16       | 0.51%   |
| ASUSTek Computer        | 16       | 0.51%   |
| Kingston Technology     | 14       | 0.45%   |
| Creative Technology     | 14       | 0.45%   |
| Corsair                 | 12       | 0.39%   |
| Generalplus Technology  | 11       | 0.35%   |
| VIA Technologies        | 10       | 0.32%   |
| Focusrite-Novation      | 9        | 0.29%   |
| SteelSeries ApS         | 7        | 0.22%   |
| Realtek Semiconductor   | 7        | 0.22%   |
| Giga-Byte Technology    | 6        | 0.19%   |
| XMOS                    | 5        | 0.16%   |
| Sony                    | 5        | 0.16%   |
| Samson Technologies     | 5        | 0.16%   |
| Plantronics             | 5        | 0.16%   |
| Blue Microphones        | 5        | 0.16%   |
| SAVITECH                | 4        | 0.13%   |
| M-Audio                 | 4        | 0.13%   |
| GN Netcom               | 4        | 0.13%   |
| Dell                    | 4        | 0.13%   |
| BR25                    | 4        | 0.13%   |
| BEHRINGER International | 4        | 0.13%   |
| ZOOM                    | 3        | 0.1%    |
| Tenx Technology         | 3        | 0.1%    |
| RODE Microphones        | 3        | 0.1%    |
| Lenovo                  | 3        | 0.1%    |
| GHW Micro               | 3        | 0.1%    |
| DSEA A/S                | 3        | 0.1%    |
| Cambridge Silicon Radio | 3        | 0.1%    |
| Astro Gaming            | 3        | 0.1%    |
| Yamaha                  | 2        | 0.06%   |
| QinHeng Electronics     | 2        | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 227      | 6.34%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 142      | 3.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 130      | 3.63%   |
| AMD Family 17h/19h HD Audio Controller                                     | 104      | 2.9%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 100      | 2.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 99       | 2.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 95       | 2.65%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 95       | 2.65%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 88       | 2.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 81       | 2.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 77       | 2.15%   |
| Intel 200 Series PCH HD Audio                                              | 77       | 2.15%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 71       | 1.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 66       | 1.84%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 61       | 1.7%    |
| Intel Cannon Lake PCH cAVS                                                 | 58       | 1.62%   |
| Nvidia GP107GL High Definition Audio Controller                            | 57       | 1.59%   |
| AMD FCH Azalia Controller                                                  | 56       | 1.56%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 42       | 1.17%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 42       | 1.17%   |
| Nvidia GF108 High Definition Audio Controller                              | 41       | 1.14%   |
| Nvidia TU116 High Definition Audio Controller                              | 40       | 1.12%   |
| Nvidia TU106 High Definition Audio Controller                              | 40       | 1.12%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 40       | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 39       | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                              | 37       | 1.03%   |
| Nvidia GA102 High Definition Audio Controller                              | 35       | 0.98%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 35       | 0.98%   |
| Intel Alder Lake-S HD Audio Controller                                     | 35       | 0.98%   |
| Intel Comet Lake PCH cAVS                                                  | 34       | 0.95%   |
| AMD Navi 10 HDMI Audio                                                     | 34       | 0.95%   |
| Nvidia GP104 High Definition Audio Controller                              | 33       | 0.92%   |
| Nvidia GA104 High Definition Audio Controller                              | 32       | 0.89%   |
| Intel Comet Lake PCH-V cAVS                                                | 31       | 0.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 31       | 0.87%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 31       | 0.87%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 30       | 0.84%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 28       | 0.78%   |
| Nvidia High Definition Audio Controller                                    | 27       | 0.75%   |
| Nvidia GM206 High Definition Audio Controller                              | 26       | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Kingston                                | 191      | 16.39%  |
| Unknown                                 | 150      | 12.88%  |
| Corsair                                 | 140      | 12.02%  |
| Crucial                                 | 119      | 10.21%  |
| SK hynix                                | 111      | 9.53%   |
| Samsung Electronics                     | 105      | 9.01%   |
| G.Skill                                 | 80       | 6.87%   |
| Micron Technology                       | 44       | 3.78%   |
| Team                                    | 26       | 2.23%   |
| A-DATA Technology                       | 22       | 1.89%   |
| Hikvision                               | 18       | 1.55%   |
| Unknown                                 | 18       | 1.55%   |
| Patriot                                 | 17       | 1.46%   |
| AMD                                     | 17       | 1.46%   |
| Nanya Technology                        | 13       | 1.12%   |
| Ramaxel Technology                      | 8        | 0.69%   |
| GOODRAM                                 | 7        | 0.6%    |
| Elpida                                  | 7        | 0.6%    |
| Unknown (ABCD)                          | 6        | 0.52%   |
| Smart                                   | 6        | 0.52%   |
| PNY                                     | 6        | 0.52%   |
| Kllisre                                 | 3        | 0.26%   |
| Wilk Elektronik                         | 2        | 0.17%   |
| Wilk                                    | 2        | 0.17%   |
| Transcend                               | 2        | 0.17%   |
| Kingmax                                 | 2        | 0.17%   |
| Innodisk                                | 2        | 0.17%   |
| Golden Empire                           | 2        | 0.17%   |
| GeIL                                    | 2        | 0.17%   |
| Atermiter                               | 2        | 0.17%   |
| ASint Technology                        | 2        | 0.17%   |
| Unknown (8AFD)                          | 1        | 0.09%   |
| Unknown (2C0B)                          | 1        | 0.09%   |
| Unknown (0x0C97)                        | 1        | 0.09%   |
| Unknown (0A23)                          | 1        | 0.09%   |
| Unknown (0000EF0010C8)                  | 1        | 0.09%   |
| Unifosa                                 | 1        | 0.09%   |
| Super Talent                            | 1        | 0.09%   |
| Silicon Power Computer & Communications | 1        | 0.09%   |
| Silicon Power                           | 1        | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                               | 18       | 1.42%   |
| Unknown                                                         | 18       | 1.42%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s         | 17       | 1.34%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s           | 15       | 1.19%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s           | 10       | 0.79%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s           | 10       | 0.79%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                       | 8        | 0.63%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                            | 8        | 0.63%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s            | 8        | 0.63%   |
| Unknown RAM Module 2GB DIMM 800MT/s                             | 7        | 0.55%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s              | 7        | 0.55%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s             | 7        | 0.55%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3400MT/s                    | 7        | 0.55%   |
| Unknown RAM Module 4GB DIMM SDRAM                               | 6        | 0.47%   |
| Unknown RAM Module 2GB DIMM 667MT/s                             | 6        | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB DIMM DDR3 2133MT/s | 6        | 0.47%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s            | 6        | 0.47%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s             | 6        | 0.47%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s           | 6        | 0.47%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s           | 6        | 0.47%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s          | 6        | 0.47%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s           | 6        | 0.47%   |
| Unknown RAM Module 1GB DIMM 800MT/s                             | 5        | 0.4%    |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                       | 5        | 0.4%    |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s             | 5        | 0.4%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s            | 5        | 0.4%    |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s          | 5        | 0.4%    |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s             | 5        | 0.4%    |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 5        | 0.4%    |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s           | 5        | 0.4%    |
| G.Skill RAM F4-3000C16-8GTZR 8GB DIMM DDR4 3200MT/s             | 5        | 0.4%    |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s          | 5        | 0.4%    |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                        | 4        | 0.32%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                        | 4        | 0.32%   |
| Unknown RAM Module 2GB DIMM 400MT/s                             | 4        | 0.32%   |
| Unknown RAM Module 1GB DIMM SDRAM                               | 4        | 0.32%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s              | 4        | 0.32%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s            | 4        | 0.32%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 4        | 0.32%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s             | 4        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 529      | 51.06%  |
| DDR3    | 330      | 31.85%  |
| Unknown | 64       | 6.18%   |
| SDRAM   | 52       | 5.02%   |
| DDR2    | 39       | 3.76%   |
| LPDDR4  | 11       | 1.06%   |
| DDR     | 10       | 0.97%   |
| DRAM    | 1        | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 953      | 93.34%  |
| SODIMM       | 62       | 6.07%   |
| Row Of Chips | 3        | 0.29%   |
| RIMM         | 2        | 0.2%    |
| Unknown      | 1        | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 387      | 34.99%  |
| 4096  | 272      | 24.59%  |
| 16384 | 210      | 18.99%  |
| 2048  | 146      | 13.2%   |
| 32768 | 50       | 4.52%   |
| 1024  | 35       | 3.16%   |
| 512   | 3        | 0.27%   |
| 65536 | 2        | 0.18%   |
| 1536  | 1        | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 208      | 18.2%   |
| 3200    | 143      | 12.51%  |
| 1333    | 123      | 10.76%  |
| 2667    | 89       | 7.79%   |
| 3600    | 73       | 6.39%   |
| 2400    | 73       | 6.39%   |
| 2133    | 53       | 4.64%   |
| 800     | 40       | 3.5%    |
| Unknown | 35       | 3.06%   |
| 667     | 28       | 2.45%   |
| 2666    | 24       | 2.1%    |
| 3000    | 21       | 1.84%   |
| 2933    | 21       | 1.84%   |
| 1867    | 21       | 1.84%   |
| 3400    | 18       | 1.57%   |
| 3466    | 16       | 1.4%    |
| 1866    | 13       | 1.14%   |
| 1800    | 12       | 1.05%   |
| 1066    | 12       | 1.05%   |
| 1067    | 10       | 0.87%   |
| 3266    | 7        | 0.61%   |
| 1334    | 7        | 0.61%   |
| 400     | 7        | 0.61%   |
| 3733    | 6        | 0.52%   |
| 3333    | 6        | 0.52%   |
| 3800    | 5        | 0.44%   |
| 3500    | 5        | 0.44%   |
| 533     | 5        | 0.44%   |
| 3334    | 4        | 0.35%   |
| 3100    | 4        | 0.35%   |
| 2866    | 4        | 0.35%   |
| 2733    | 4        | 0.35%   |
| 333     | 4        | 0.35%   |
| 3866    | 3        | 0.26%   |
| 2800    | 3        | 0.26%   |
| 2465    | 3        | 0.26%   |
| 2200    | 3        | 0.26%   |
| 1400    | 3        | 0.26%   |
| 5600    | 2        | 0.17%   |
| 3666    | 2        | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)

![Printer Vendor](./images/line_chart/printer_vendor.svg)

| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Hewlett-Packard        | 25       | 30.12%  |
| Canon                  | 17       | 20.48%  |
| Brother Industries     | 14       | 16.87%  |
| Seiko Epson            | 12       | 14.46%  |
| Samsung Electronics    | 6        | 7.23%   |
| QinHeng Electronics    | 4        | 4.82%   |
| Xerox                  | 1        | 1.2%    |
| Panasonic (Matsushita) | 1        | 1.2%    |
| Lexmark International  | 1        | 1.2%    |
| Dymo-CoStar            | 1        | 1.2%    |
| Datamax-O'Neil         | 1        | 1.2%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)

![Printer Model](./images/line_chart/printer_model.svg)

| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| QinHeng CH340S                        | 4        | 4.71%   |
| HP LaserJet M14-M17                   | 3        | 3.53%   |
| Seiko Epson L3250 Series              | 2        | 2.35%   |
| Seiko Epson L3110 Series              | 2        | 2.35%   |
| Seiko Epson ET-2710 Series            | 2        | 2.35%   |
| HP OfficeJet 3830 series              | 2        | 2.35%   |
| HP LaserJet Professional P1102w       | 2        | 2.35%   |
| HP DeskJet 2300 series                | 2        | 2.35%   |
| Canon PIXMA MP240                     | 2        | 2.35%   |
| Canon LiDE 400                        | 2        | 2.35%   |
| Canon LBP2900                         | 2        | 2.35%   |
| Xerox WorkCentre 3119 Series          | 1        | 1.18%   |
| Seiko Epson XP-7100 Series            | 1        | 1.18%   |
| Seiko Epson XP-4100 Series            | 1        | 1.18%   |
| Seiko Epson XP-3150 Series            | 1        | 1.18%   |
| Seiko Epson WF-7310 Series            | 1        | 1.18%   |
| Seiko Epson L3160 Series              | 1        | 1.18%   |
| Seiko Epson L222 Series               | 1        | 1.18%   |
| Seiko Epson AL-M300                   | 1        | 1.18%   |
| Samsung SCX-4200 series               | 1        | 1.18%   |
| Samsung ML-216x Series Laser Printer  | 1        | 1.18%   |
| Samsung ML-191x/ML-252x Laser Printer | 1        | 1.18%   |
| Samsung M332x 382x 402x Series        | 1        | 1.18%   |
| Samsung M2070 Series                  | 1        | 1.18%   |
| Samsung C43x Series                   | 1        | 1.18%   |
| Panasonic (Matsushita) KX-MB1500RU    | 1        | 1.18%   |
| Lexmark International MS710           | 1        | 1.18%   |
| HP Smart Tank 7000 series             | 1        | 1.18%   |
| HP Smart Install                      | 1        | 1.18%   |
| HP OfficeJet Pro 8020 series          | 1        | 1.18%   |
| HP OfficeJet Pro 7740 series          | 1        | 1.18%   |
| HP OfficeJet Pro 7730 series          | 1        | 1.18%   |
| HP OfficeJet 5200 series              | 1        | 1.18%   |
| HP LaserJet P2015 series              | 1        | 1.18%   |
| HP LaserJet P1102                     | 1        | 1.18%   |
| HP LaserJet 4250                      | 1        | 1.18%   |
| HP LaserJet 1150                      | 1        | 1.18%   |
| HP LaserJet 1020                      | 1        | 1.18%   |
| HP LaserJet 1012                      | 1        | 1.18%   |
| HP Ink Tank Wireless 410 series       | 1        | 1.18%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)

![Scanner Vendor](./images/line_chart/scanner_vendor.svg)

| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 17       | 70.83%  |
| Hewlett-Packard             | 3        | 12.5%   |
| Acer Peripherals (now BenQ) | 2        | 8.33%   |
| Seiko Epson                 | 1        | 4.17%   |
| Mustek Systems              | 1        | 4.17%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)

![Scanner Model](./images/line_chart/scanner_model.svg)

| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                  | 3        | 12.5%   |
| Canon CanoScan LiDE 100                             | 3        | 12.5%   |
| Canon CanoScan LiDE 200                             | 2        | 8.33%   |
| Canon CanoScan LiDE 120                             | 2        | 8.33%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO] | 1        | 4.17%   |
| Mustek Systems ScanExpress 1200 UB                  | 1        | 4.17%   |
| HP ScanJet 2400c                                    | 1        | 4.17%   |
| HP ScanJet 2200c                                    | 1        | 4.17%   |
| HP PSC 1200                                         | 1        | 4.17%   |
| Canon CanoScan N650U/N656U                          | 1        | 4.17%   |
| Canon CanoScan LiDE 90                              | 1        | 4.17%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40              | 1        | 4.17%   |
| Canon CanoScan LIDE 25                              | 1        | 4.17%   |
| Canon CanoScan LiDE 220                             | 1        | 4.17%   |
| Canon CanoScan LiDE 110                             | 1        | 4.17%   |
| Canon CanoScan 3200F                                | 1        | 4.17%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U         | 1        | 4.17%   |
| Acer Peripherals (now BenQ) Benq 5000               | 1        | 4.17%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)

![Camera Vendor](./images/line_chart/camera_vendor.svg)

| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 152      | 39.48%  |
| Microdia                      | 38       | 9.87%   |
| Microsoft                     | 26       | 6.75%   |
| Sunplus Innovation Technology | 20       | 5.19%   |
| Generalplus Technology        | 16       | 4.16%   |
| Samsung Electronics           | 13       | 3.38%   |
| KYE Systems (Mouse Systems)   | 11       | 2.86%   |
| Realtek Semiconductor         | 6        | 1.56%   |
| IMC Networks                  | 6        | 1.56%   |
| MacroSilicon                  | 5        | 1.3%    |
| Z-Star Microelectronics       | 4        | 1.04%   |
| Creative Technology           | 4        | 1.04%   |
| Chicony Electronics           | 4        | 1.04%   |
| AVerMedia Technologies        | 4        | 1.04%   |
| ARC International             | 4        | 1.04%   |
| Apple                         | 4        | 1.04%   |
| A4Tech                        | 4        | 1.04%   |
| 2M UVC CAMERA                 | 4        | 1.04%   |
| Unknown                       | 3        | 0.78%   |
| Trust                         | 3        | 0.78%   |
| Jieli Technology              | 3        | 0.78%   |
| Hewlett-Packard               | 3        | 0.78%   |
| GEMBIRD                       | 3        | 0.78%   |
| Cubeternet                    | 3        | 0.78%   |
| Aveo Technology               | 3        | 0.78%   |
| Arkmicro Technologies         | 3        | 0.78%   |
| Sonix Technology              | 2        | 0.52%   |
| Razer USA                     | 2        | 0.52%   |
| Quanta                        | 2        | 0.52%   |
| Pixart Imaging                | 2        | 0.52%   |
| Philips (or NXP)              | 2        | 0.52%   |
| Novatek Microelectronics      | 2        | 0.52%   |
| Lenovo                        | 2        | 0.52%   |
| Huawei Technologies           | 2        | 0.52%   |
| Alcor Micro                   | 2        | 0.52%   |
| Xiongmai                      | 1        | 0.26%   |
| WCM_USB                       | 1        | 0.26%   |
| WaveRider Communications      | 1        | 0.26%   |
| Valve Software                | 1        | 0.26%   |
| Tobii Technology AB           | 1        | 0.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech Webcam C270                      | 30       | 7.77%   |
| Logitech HD Pro Webcam C920               | 25       | 6.48%   |
| Generalplus GENERAL WEBCAM                | 14       | 3.63%   |
| Samsung Galaxy A5 (MTP)                   | 13       | 3.37%   |
| Microdia Webcam Vitade AF                 | 12       | 3.11%   |
| Logitech C922 Pro Stream Webcam           | 11       | 2.85%   |
| Microdia CameraA                          | 9        | 2.33%   |
| Logitech BRIO Ultra HD Webcam             | 9        | 2.33%   |
| Microsoft LifeCam HD-3000                 | 8        | 2.07%   |
| Logitech Webcam C310                      | 8        | 2.07%   |
| Microdia USB 2.0 Camera                   | 6        | 1.55%   |
| Logitech HD Webcam C615                   | 6        | 1.55%   |
| Logitech C920 PRO HD Webcam               | 6        | 1.55%   |
| KYE Systems (Mouse Systems) FaceCam 1000X | 6        | 1.55%   |
| Sunplus HD 720P webcam                    | 5        | 1.3%    |
| Sunplus Aukey-PC-LM1E Camera              | 5        | 1.3%    |
| Microsoft LifeCam Cinema                  | 5        | 1.3%    |
| Logitech HD Webcam C910                   | 5        | 1.3%    |
| Logitech HD Webcam C525                   | 5        | 1.3%    |
| IMC Networks XHC Camera                   | 5        | 1.3%    |
| Microdia Sonix USB 2.0 Camera             | 4        | 1.04%   |
| MacroSilicon USB Video                    | 4        | 1.04%   |
| Logitech Webcam C925e                     | 4        | 1.04%   |
| Logitech Webcam C170                      | 4        | 1.04%   |
| ARC International Camera                  | 4        | 1.04%   |
| Apple iPhone5/5C/5S/6                     | 4        | 1.04%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam       | 4        | 1.04%   |
| Unknown HD camera                         | 3        | 0.78%   |
| Sunplus PAPALOOK_229AF                    | 3        | 0.78%   |
| Sunplus HK 1080P K20Pro                   | 3        | 0.78%   |
| Microdia Camera                           | 3        | 0.78%   |
| Logitech Logitech Webcam C100             | 3        | 0.78%   |
| Logitech C505 HD Webcam                   | 3        | 0.78%   |
| Jieli USB PHY 2.0                         | 3        | 0.78%   |
| Cubeternet USB2.0 Camera                  | 3        | 0.78%   |
| AVerMedia Live Streamer CAM 313           | 3        | 0.78%   |
| Z-Star Lenovo USB 2.0 UVC Camera          | 2        | 0.52%   |
| Realtek USB Camera                        | 2        | 0.52%   |
| Razer USA Gaming Webcam [Kiyo]            | 2        | 0.52%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro      | 2        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Upek                  | 1        | 16.67%  |
| Synaptics             | 1        | 16.67%  |
| LighTuning Technology | 1        | 16.67%  |
| Elan Microelectronics | 1        | 16.67%  |
| DigitalPersona        | 1        | 16.67%  |
| Dell                  | 1        | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 16.67%  |
| Synaptics  WBDI Fingerprint Reader - USB 052           | 1        | 16.67%  |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1        | 16.67%  |
| Elan fingerprint sensor [FeinTech FPS00200]            | 1        | 16.67%  |
| DigitalPersona Fingerprint Reader                      | 1        | 16.67%  |
| Dell MS819 Wired Mouse With Fingerprint Reader         | 1        | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./images/line_chart/chipcard_vendor.svg)

| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Advanced Card Systems      | 4        | 22.22%  |
| Alcor Micro                | 3        | 16.67%  |
| SCM Microsystems           | 2        | 11.11%  |
| Realtek Semiconductor      | 2        | 11.11%  |
| Clay Logic                 | 2        | 11.11%  |
| Precise Biometrics         | 1        | 5.56%   |
| In Focus Systems           | 1        | 5.56%   |
| Fujitsu Siemens Computers  | 1        | 5.56%   |
| Chicony Electronics        | 1        | 5.56%   |
| Athena Smartcard Solutions | 1        | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)

![Chipcard Model](./images/line_chart/chipcard_model.svg)

| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface          | 2        | 10.53%  |
| Clay Logic Nitrokey Pro                                    | 2        | 10.53%  |
| Alcor Micro Watchdata W 1981                               | 2        | 10.53%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader     | 1        | 5.26%   |
| SCM Microsystems Elektra331-USB SmartCard Reader           | 1        | 5.26%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader            | 1        | 5.26%   |
| Precise Biometrics 200 MC FingerPrint and SmartCard Reader | 1        | 5.26%   |
| In Focus Systems EMV Smartcard Reader                      | 1        | 5.26%   |
| Fujitsu Siemens Computers SmartCard Reader 2A              | 1        | 5.26%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard       | 1        | 5.26%   |
| Athena Smartcard Solutions ASEDrive CCID                   | 1        | 5.26%   |
| Alcor Micro AU9540 Smartcard Reader                        | 1        | 5.26%   |
| Advanced Card Systems ACR39U                               | 1        | 5.26%   |
| Advanced Card Systems ACR1281 1S Dual Reader               | 1        | 5.26%   |
| Advanced Card Systems ACR1252 Dual Reader                  | 1        | 5.26%   |
| Advanced Card Systems ACR122U                              | 1        | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1511     | 82.43%  |
| 1     | 273      | 14.89%  |
| 2     | 40       | 2.18%   |
| 3     | 5        | 0.27%   |
| 5     | 2        | 0.11%   |
| 8     | 1        | 0.05%   |
| 7     | 1        | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 157      | 42.2%   |
| Net/wireless             | 77       | 20.7%   |
| Unassigned class         | 29       | 7.8%    |
| Communication controller | 23       | 6.18%   |
| Sound                    | 19       | 5.11%   |
| Chipcard                 | 13       | 3.49%   |
| Net/ethernet             | 7        | 1.88%   |
| Camera                   | 7        | 1.88%   |
| Bluetooth                | 7        | 1.88%   |
| Storage/raid             | 5        | 1.34%   |
| Multimedia controller    | 5        | 1.34%   |
| Fingerprint reader       | 5        | 1.34%   |
| Card reader              | 5        | 1.34%   |
| Firewire controller      | 4        | 1.08%   |
| Network                  | 3        | 0.81%   |
| Dvb card                 | 3        | 0.81%   |
| Storage/ide              | 2        | 0.54%   |
| Modem                    | 1        | 0.27%   |

