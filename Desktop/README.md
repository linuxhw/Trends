Linux - Hardware Trends (Desktops)
----------------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: Oct, 2023.

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
| Ubuntu 22.04                 | 312      | 14.32%  |
| Linux Mint 21.2              | 167      | 7.66%   |
| Fedora 38                    | 157      | 7.21%   |
| Debian 12                    | 130      | 5.97%   |
| Arch Rolling                 | 87       | 3.99%   |
| ROSA 12.4                    | 85       | 3.9%    |
| Ubuntu 23.04                 | 81       | 3.72%   |
| Pop!_OS 22.04                | 75       | 3.44%   |
| OpenMandriva 23.08           | 67       | 3.07%   |
| Zorin 16                     | 60       | 2.75%   |
| OpenMandriva 23.10           | 49       | 2.25%   |
| ArcoLinux Rolling            | 49       | 2.25%   |
| BlackPanther 18.1            | 46       | 2.11%   |
| Ubuntu 20.04                 | 44       | 2.02%   |
| Manjaro                      | 42       | 1.93%   |
| Ubuntu 23.10                 | 35       | 1.61%   |
| KDE neon 22.04               | 28       | 1.28%   |
| Gentoo 2.14                  | 28       | 1.28%   |
| EndeavourOS Rolling          | 26       | 1.19%   |
| Kubuntu 22.04                | 24       | 1.1%    |
| Debian 11                    | 24       | 1.1%    |
| openSUSE Tumbleweed-XXXXXXXX | 23       | 1.06%   |
| OpenMandriva 4.3             | 19       | 0.87%   |
| Nobara 38                    | 19       | 0.87%   |
| Kubuntu 23.04                | 19       | 0.87%   |
| Debian                       | 19       | 0.87%   |
| LMDE 6                       | 18       | 0.83%   |
| Linux Mint 21.1              | 17       | 0.78%   |
| openSUSE Leap-15.5           | 16       | 0.73%   |
| Linux Mint 20.3              | 15       | 0.69%   |
| Fedora 39                    | 12       | 0.55%   |
| Xubuntu 22.04                | 11       | 0.5%    |
| OpenMandriva 23.03           | 11       | 0.5%    |
| Kubuntu 23.10                | 11       | 0.5%    |
| Elementary 7.1               | 11       | 0.5%    |
| Xero Rolling                 | 10       | 0.46%   |
| Ubuntu 18.04                 | 10       | 0.46%   |
| Red OS 7.3                   | 10       | 0.46%   |
| Manjaro 23.0.4               | 10       | 0.46%   |
| Linux Mint 21                | 10       | 0.46%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name             | Desktops | Percent |
|------------------|----------|---------|
| Ubuntu           | 489      | 22.44%  |
| Linux Mint       | 221      | 10.14%  |
| Debian           | 176      | 8.08%   |
| Fedora           | 173      | 7.94%   |
| OpenMandriva     | 171      | 7.85%   |
| ROSA             | 104      | 4.77%   |
| Arch             | 87       | 3.99%   |
| Pop!_OS          | 75       | 3.44%   |
| Zorin            | 62       | 2.85%   |
| Manjaro          | 62       | 2.85%   |
| Kubuntu          | 57       | 2.62%   |
| BlackPanther     | 52       | 2.39%   |
| ArcoLinux        | 49       | 2.25%   |
| openSUSE         | 44       | 2.02%   |
| KDE neon         | 29       | 1.33%   |
| Gentoo           | 29       | 1.33%   |
| EndeavourOS      | 26       | 1.19%   |
| Nobara           | 22       | 1.01%   |
| Xubuntu          | 21       | 0.96%   |
| LMDE             | 19       | 0.87%   |
| Garuda Linux     | 16       | 0.73%   |
| Elementary       | 12       | 0.55%   |
| MX               | 11       | 0.5%    |
| Xero             | 10       | 0.46%   |
| Red OS           | 10       | 0.46%   |
| Lubuntu          | 10       | 0.46%   |
| Kali             | 10       | 0.46%   |
| ChimeraOS        | 8        | 0.37%   |
| Ubuntu MATE      | 7        | 0.32%   |
| NixOS            | 7        | 0.32%   |
| ALT Linux        | 6        | 0.28%   |
| AlmaLinux        | 6        | 0.28%   |
| Ubuntu Unity     | 5        | 0.23%   |
| Rocky Linux      | 5        | 0.23%   |
| org.kde.Platform | 5        | 0.23%   |
| BigLinux         | 5        | 0.23%   |
| Alpine           | 5        | 0.23%   |
| Void Linux       | 4        | 0.18%   |
| SteamOS          | 4        | 0.18%   |
| CentOS           | 4        | 0.18%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version                           | Desktops | Percent |
|-----------------------------------|----------|---------|
| 6.2.0-34-generic                  | 192      | 8.81%   |
| 6.2.0-35-generic                  | 126      | 5.78%   |
| 5.15.0-86-generic                 | 115      | 5.28%   |
| 6.1.0-13-amd64                    | 85       | 3.9%    |
| 5.15.0-87-generic                 | 81       | 3.72%   |
| 6.2.0-33-generic                  | 63       | 2.89%   |
| 6.4.11-desktop-1omv2390           | 58       | 2.66%   |
| 5.15.0-84-generic                 | 54       | 2.48%   |
| 6.5.5-200.fc38.x86_64             | 49       | 2.25%   |
| 6.5.5-desktop-1omv2390            | 45       | 2.07%   |
| 6.5.6-200.fc38.x86_64             | 41       | 1.88%   |
| 6.5.4-76060504-generic            | 41       | 1.88%   |
| 6.1.46-generic-2rosa2021.1-x86_64 | 40       | 1.84%   |
| 6.1.0-12-amd64                    | 33       | 1.51%   |
| 6.5.0-9-generic                   | 32       | 1.47%   |
| 6.5.7-200.fc38.x86_64             | 31       | 1.42%   |
| 6.5.7-arch1-1                     | 28       | 1.28%   |
| 6.5.5-1-MANJARO                   | 27       | 1.24%   |
| 6.5.9-arch2-1                     | 26       | 1.19%   |
| 6.1.20-generic-2rosa2021.1-x86_64 | 26       | 1.19%   |
| 5.6.14-desktop-2bP                | 26       | 1.19%   |
| 6.5.8-arch1-1                     | 22       | 1.01%   |
| 6.5.6-76060506-generic            | 21       | 0.96%   |
| 6.5.5-arch1-1                     | 21       | 0.96%   |
| 5.15.0-76-generic                 | 20       | 0.92%   |
| 6.2.0-26-generic                  | 19       | 0.87%   |
| 5.19.0-38-generic                 | 17       | 0.78%   |
| 6.5.0-10-generic                  | 14       | 0.64%   |
| 6.4.8-desktop-2omv2390            | 14       | 0.64%   |
| 6.2.9-300.fc38.x86_64             | 14       | 0.64%   |
| 6.2.0-36-generic                  | 14       | 0.64%   |
| 5.16.7-desktop-1omv4003           | 14       | 0.64%   |
| 6.5.8-200.fc38.x86_64             | 13       | 0.6%    |
| 6.5.5-zen1-1-zen                  | 13       | 0.6%    |
| 4.18.16-desktop-1bP               | 13       | 0.6%    |
| 6.5.4-1-default                   | 12       | 0.55%   |
| 6.2.6-desktop-1omv2390            | 12       | 0.55%   |
| 5.10.0-26-amd64                   | 12       | 0.55%   |
| 6.4.6-76060406-generic            | 11       | 0.5%    |
| 6.1.58-generic-1rosa2021.1-x86_64 | 11       | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.0   | 437      | 20.06%  |
| 5.15.0  | 322      | 14.78%  |
| 6.5.5   | 180      | 8.26%   |
| 6.1.0   | 148      | 6.79%   |
| 6.5.6   | 107      | 4.91%   |
| 6.5.7   | 91       | 4.18%   |
| 6.5.0   | 83       | 3.81%   |
| 6.4.11  | 61       | 2.8%    |
| 6.5.4   | 57       | 2.62%   |
| 6.5.8   | 55       | 2.52%   |
| 5.4.0   | 45       | 2.07%   |
| 6.5.9   | 43       | 1.97%   |
| 6.1.46  | 42       | 1.93%   |
| 5.19.0  | 30       | 1.38%   |
| 6.1.20  | 26       | 1.19%   |
| 5.6.14  | 26       | 1.19%   |
| 6.5.3   | 24       | 1.1%    |
| 5.10.0  | 20       | 0.92%   |
| 4.15.0  | 19       | 0.87%   |
| 5.14.21 | 17       | 0.78%   |
| 6.2.16  | 16       | 0.73%   |
| 6.1.55  | 16       | 0.73%   |
| 6.1.58  | 15       | 0.69%   |
| 6.4.8   | 14       | 0.64%   |
| 6.2.9   | 14       | 0.64%   |
| 5.16.7  | 14       | 0.64%   |
| 4.18.16 | 13       | 0.6%    |
| 6.2.6   | 12       | 0.55%   |
| 5.14.0  | 12       | 0.55%   |
| 6.4.6   | 11       | 0.5%    |
| 6.1.57  | 10       | 0.46%   |
| 6.6.0   | 9        | 0.41%   |
| 6.1.53  | 9        | 0.41%   |
| 6.1.52  | 8        | 0.37%   |
| 5.15.85 | 8        | 0.37%   |
| 6.4.12  | 7        | 0.32%   |
| 6.1.1   | 7        | 0.32%   |
| 4.18.0  | 7        | 0.32%   |
| 6.4.0   | 6        | 0.28%   |
| 6.5.2   | 5        | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Desktops | Percent |
|---------|----------|---------|
| 6.5     | 647      | 29.69%  |
| 6.2     | 481      | 22.07%  |
| 5.15    | 344      | 15.79%  |
| 6.1     | 307      | 14.09%  |
| 6.4     | 120      | 5.51%   |
| 5.4     | 52       | 2.39%   |
| 5.10    | 37       | 1.7%    |
| 5.19    | 31       | 1.42%   |
| 5.14    | 30       | 1.38%   |
| 5.6     | 26       | 1.19%   |
| 5.16    | 20       | 0.92%   |
| 4.18    | 20       | 0.92%   |
| 4.15    | 19       | 0.87%   |
| 6.3     | 16       | 0.73%   |
| 6.6     | 9        | 0.41%   |
| 6.0     | 3        | 0.14%   |
| 5.11    | 3        | 0.14%   |
| 5.8     | 2        | 0.09%   |
| 5.17    | 2        | 0.09%   |
| 5.13    | 2        | 0.09%   |
| 4.19    | 2        | 0.09%   |
| 96.5    | 1        | 0.05%   |
| 5.18    | 1        | 0.05%   |
| 5.0     | 1        | 0.05%   |
| 4.9     | 1        | 0.05%   |
| 4.4     | 1        | 0.05%   |
| 3.10    | 1        | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 2166     | 99.4%   |
| i686   | 13       | 0.6%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| GNOME                   | 874      | 40.11%  |
| KDE5                    | 599      | 27.49%  |
| X-Cinnamon              | 205      | 9.41%   |
| Unknown                 | 140      | 6.42%   |
| XFCE                    | 120      | 5.51%   |
| MATE                    | 74       | 3.4%    |
| LXQt                    | 38       | 1.74%   |
| Cinnamon                | 28       | 1.28%   |
| i3                      | 18       | 0.83%   |
| Pantheon                | 12       | 0.55%   |
| Hyprland                | 9        | 0.41%   |
| GNOME Classic           | 7        | 0.32%   |
| Budgie                  | 7        | 0.32%   |
| LXDE                    | 6        | 0.28%   |
| KDE4                    | 6        | 0.28%   |
| KDE                     | 6        | 0.28%   |
| Deepin                  | 6        | 0.28%   |
| Unity                   | 4        | 0.18%   |
| sway                    | 3        | 0.14%   |
| GNOME Flashback         | 3        | 0.14%   |
| ICEWM                   | 2        | 0.09%   |
| awesome                 | 2        | 0.09%   |
| x-session-manager       | 1        | 0.05%   |
| Wayfire:wayfire:wlroots | 1        | 0.05%   |
| Unicorn:XFCE            | 1        | 0.05%   |
| UKUI                    | 1        | 0.05%   |
| Trinity                 | 1        | 0.05%   |
| openbox                 | 1        | 0.05%   |
| onyx:GNOME              | 1        | 0.05%   |
| fly                     | 1        | 0.05%   |
| Enlightenment           | 1        | 0.05%   |
| DDE                     | 1        | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1285     | 58.97%  |
| Wayland | 731      | 33.55%  |
| Tty     | 84       | 3.85%   |
| Unknown | 78       | 3.58%   |
| Web     | 1        | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 789      | 36.21%  |
| SDDM    | 510      | 23.41%  |
| GDM3    | 444      | 20.38%  |
| LightDM | 260      | 11.93%  |
| GDM     | 153      | 7.02%   |
| KDM     | 6        | 0.28%   |
| LXDM    | 5        | 0.23%   |
| XDM     | 4        | 0.18%   |
| LY-DM   | 3        | 0.14%   |
| SLiM    | 2        | 0.09%   |
| NODM    | 1        | 0.05%   |
| GREETD  | 1        | 0.05%   |
| FLY-DM  | 1        | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 823      | 37.77%  |
| de_DE   | 219      | 10.05%  |
| ru_RU   | 193      | 8.86%   |
| en_GB   | 105      | 4.82%   |
| it_IT   | 99       | 4.54%   |
| fr_FR   | 90       | 4.13%   |
| Unknown | 71       | 3.26%   |
| pt_BR   | 68       | 3.12%   |
| C       | 58       | 2.66%   |
| es_ES   | 51       | 2.34%   |
| en_CA   | 45       | 2.07%   |
| en_AU   | 45       | 2.07%   |
| pl_PL   | 29       | 1.33%   |
| nl_NL   | 16       | 0.73%   |
| es_MX   | 16       | 0.73%   |
| hu_HU   | 14       | 0.64%   |
| en_IN   | 14       | 0.64%   |
| en_ZA   | 13       | 0.6%    |
| zh_CN   | 12       | 0.55%   |
| es_AR   | 12       | 0.55%   |
| tr_TR   | 11       | 0.5%    |
| fi_FI   | 10       | 0.46%   |
| de_AT   | 10       | 0.46%   |
| ja_JP   | 9        | 0.41%   |
| cs_CZ   | 9        | 0.41%   |
| sv_SE   | 8        | 0.37%   |
| nl_BE   | 7        | 0.32%   |
| en_NZ   | 7        | 0.32%   |
| zh_TW   | 6        | 0.28%   |
| es_CO   | 6        | 0.28%   |
| de_CH   | 6        | 0.28%   |
| pt_PT   | 5        | 0.23%   |
| es_VE   | 5        | 0.23%   |
| fr_CA   | 4        | 0.18%   |
| en_IE   | 4        | 0.18%   |
| C.UTF8  | 4        | 0.18%   |
| sk_SK   | 3        | 0.14%   |
| ru_UA   | 3        | 0.14%   |
| lt_LT   | 3        | 0.14%   |
| ko_KR   | 3        | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1135     | 52.09%  |
| EFI  | 1044     | 47.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 1259     | 57.78%  |
| Btrfs    | 352      | 16.15%  |
| Tmpfs    | 342      | 15.7%   |
| Overlay  | 146      | 6.7%    |
| Xfs      | 42       | 1.93%   |
| Zfs      | 18       | 0.83%   |
| F2fs     | 8        | 0.37%   |
| Ext3     | 4        | 0.18%   |
| Unknown  | 3        | 0.14%   |
| Ext2     | 2        | 0.09%   |
| Reiserfs | 1        | 0.05%   |
| Jfs      | 1        | 0.05%   |
| Aufs     | 1        | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1219     | 55.94%  |
| Unknown | 694      | 31.85%  |
| MBR     | 266      | 12.21%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1755     | 80.54%  |
| Yes       | 424      | 19.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1485     | 68.15%  |
| Yes       | 694      | 31.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 506      | 23.22%  |
| Gigabyte Technology                  | 391      | 17.94%  |
| MSI                                  | 286      | 13.13%  |
| ASRock                               | 178      | 8.17%   |
| Hewlett-Packard                      | 167      | 7.66%   |
| Dell                                 | 162      | 7.43%   |
| Lenovo                               | 81       | 3.72%   |
| Intel                                | 65       | 2.98%   |
| Unknown                              | 43       | 1.97%   |
| Acer                                 | 35       | 1.61%   |
| Fujitsu                              | 23       | 1.06%   |
| Biostar                              | 22       | 1.01%   |
| AZW                                  | 20       | 0.92%   |
| Supermicro                           | 19       | 0.87%   |
| Pegatron                             | 19       | 0.87%   |
| Foxconn                              | 12       | 0.55%   |
| ECS                                  | 12       | 0.55%   |
| MACHINIST                            | 11       | 0.5%    |
| Shenzhen Meigao Electronic Equipment | 10       | 0.46%   |
| Medion                               | 7        | 0.32%   |
| Huanan                               | 7        | 0.32%   |
| Inventec                             | 6        | 0.28%   |
| Fujitsu Siemens                      | 6        | 0.28%   |
| Packard Bell                         | 4        | 0.18%   |
| ASRockRack                           | 4        | 0.18%   |
| AMI                                  | 4        | 0.18%   |
| Shuttle                              | 3        | 0.14%   |
| Positivo                             | 3        | 0.14%   |
| Gateway                              | 3        | 0.14%   |
| EPSON DIRECT                         | 3        | 0.14%   |
| eMachines                            | 3        | 0.14%   |
| Apple                                | 3        | 0.14%   |
| Win element                          | 2        | 0.09%   |
| Trigkey                              | 2        | 0.09%   |
| SZMZ                                 | 2        | 0.09%   |
| System76                             | 2        | 0.09%   |
| Samsung Electronics                  | 2        | 0.09%   |
| LattePanda                           | 2        | 0.09%   |
| Google                               | 2        | 0.09%   |
| GEEKOM                               | 2        | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 43       | 1.97%   |
| ASUS All Series                    | 33       | 1.51%   |
| MSI MS-7C37                        | 16       | 0.73%   |
| Dell OptiPlex 9020                 | 12       | 0.55%   |
| Dell OptiPlex 7010                 | 12       | 0.55%   |
| ASUS TUF Gaming X570-PLUS          | 12       | 0.55%   |
| MSI MS-7C56                        | 11       | 0.5%    |
| MSI MS-7C02                        | 11       | 0.5%    |
| Dell OptiPlex 7050                 | 10       | 0.46%   |
| ASUS ROG STRIX B550-F GAMING       | 10       | 0.46%   |
| MSI MS-7B79                        | 9        | 0.41%   |
| ASUS PRIME A320M-K                 | 9        | 0.41%   |
| MSI MS-7C95                        | 8        | 0.37%   |
| MSI MS-7B86                        | 8        | 0.37%   |
| MSI MS-7817                        | 8        | 0.37%   |
| Intel H61                          | 8        | 0.37%   |
| HP Compaq Elite 8300 SFF           | 8        | 0.37%   |
| Gigabyte B550M DS3H                | 8        | 0.37%   |
| Gigabyte B450M DS3H                | 8        | 0.37%   |
| Dell OptiPlex 780                  | 8        | 0.37%   |
| MSI MS-7D75                        | 7        | 0.32%   |
| MSI MS-7C91                        | 7        | 0.32%   |
| MSI MS-7B89                        | 7        | 0.32%   |
| Intel X99                          | 7        | 0.32%   |
| Gigabyte B550 AORUS ELITE V2       | 7        | 0.32%   |
| Gigabyte 970A-DS3P                 | 7        | 0.32%   |
| ASUS TUF Gaming B550M-PLUS         | 7        | 0.32%   |
| ASUS ROG STRIX X670E-E GAMING WIFI | 7        | 0.32%   |
| Supermicro SYS-6018R-TDW           | 6        | 0.28%   |
| Intel Jasper Lake Client Platform  | 6        | 0.28%   |
| HP Z440 Workstation                | 6        | 0.28%   |
| Gigabyte X570 I AORUS PRO WIFI     | 6        | 0.28%   |
| Gigabyte B550M AORUS PRO-P         | 6        | 0.28%   |
| Gigabyte A320M-S2H                 | 6        | 0.28%   |
| Dell OptiPlex 790                  | 6        | 0.28%   |
| ASUS TUF Gaming B550-PLUS          | 6        | 0.28%   |
| ASUS PRIME X570-PRO                | 6        | 0.28%   |
| ASUS PRIME B450M-A                 | 6        | 0.28%   |
| ASUS M5A97 R2.0                    | 6        | 0.28%   |
| MSI MS-7D25                        | 5        | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 119      | 5.46%   |
| Dell OptiPlex      | 93       | 4.27%   |
| ASUS ROG           | 92       | 4.22%   |
| ASUS TUF           | 62       | 2.85%   |
| Lenovo ThinkCentre | 47       | 2.16%   |
| Unknown            | 43       | 1.97%   |
| HP Compaq          | 38       | 1.74%   |
| Dell Precision     | 35       | 1.61%   |
| ASUS All           | 33       | 1.51%   |
| HP EliteDesk       | 31       | 1.42%   |
| Gigabyte B550M     | 23       | 1.06%   |
| Gigabyte B450M     | 22       | 1.01%   |
| Fujitsu ESPRIMO    | 21       | 0.96%   |
| Acer Aspire        | 21       | 0.96%   |
| Gigabyte X570      | 20       | 0.92%   |
| HP ProDesk         | 19       | 0.87%   |
| Gigabyte B550      | 17       | 0.78%   |
| MSI MS-7C37        | 16       | 0.73%   |
| Lenovo IdeaCentre  | 16       | 0.73%   |
| HP Pavilion        | 12       | 0.55%   |
| Gigabyte Z390      | 12       | 0.55%   |
| ASUS M5A78L-M      | 12       | 0.55%   |
| MSI MS-7C56        | 11       | 0.5%    |
| MSI MS-7C02        | 11       | 0.5%    |
| Intel H61          | 10       | 0.46%   |
| Gigabyte B450      | 10       | 0.46%   |
| Dell Inspiron      | 10       | 0.46%   |
| ASUS M5A97         | 10       | 0.46%   |
| ASRock B450        | 10       | 0.46%   |
| MSI MS-7B79        | 9        | 0.41%   |
| Gigabyte X570S     | 9        | 0.41%   |
| Dell XPS           | 9        | 0.41%   |
| MSI MS-7C95        | 8        | 0.37%   |
| MSI MS-7B86        | 8        | 0.37%   |
| MSI MS-7817        | 8        | 0.37%   |
| Gigabyte 970A-DS3P | 8        | 0.37%   |
| ASRock X570        | 8        | 0.37%   |
| ASRock B550        | 8        | 0.37%   |
| MSI MS-7D75        | 7        | 0.32%   |
| MSI MS-7C91        | 7        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 208      | 9.55%   |
| 2020    | 199      | 9.13%   |
| 2022    | 187      | 8.58%   |
| 2019    | 171      | 7.85%   |
| 2021    | 167      | 7.66%   |
| 2013    | 166      | 7.62%   |
| 2012    | 161      | 7.39%   |
| 2017    | 129      | 5.92%   |
| 2014    | 122      | 5.6%    |
| 2011    | 115      | 5.28%   |
| 2023    | 110      | 5.05%   |
| 2015    | 92       | 4.22%   |
| 2010    | 85       | 3.9%    |
| 2009    | 85       | 3.9%    |
| 2016    | 75       | 3.44%   |
| 2008    | 48       | 2.2%    |
| 2007    | 33       | 1.51%   |
| 2006    | 18       | 0.83%   |
| 2005    | 5        | 0.23%   |
| 2004    | 1        | 0.05%   |
| 2001    | 1        | 0.05%   |
| Unknown | 1        | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2179     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2102     | 96.47%  |
| Enabled  | 77       | 3.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2176     | 99.86%  |
| Yes  | 3        | 0.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 577      | 26.48%  |
| 32.01-64.0      | 417      | 19.14%  |
| 8.01-16.0       | 343      | 15.74%  |
| 4.01-8.0        | 290      | 13.31%  |
| 3.01-4.0        | 200      | 9.18%   |
| 64.01-256.0     | 198      | 9.09%   |
| 24.01-32.0      | 91       | 4.18%   |
| 1.01-2.0        | 31       | 1.42%   |
| 2.01-3.0        | 21       | 0.96%   |
| More than 256.0 | 9        | 0.41%   |
| 0.51-1.0        | 1        | 0.05%   |
| Unknown         | 1        | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 580      | 26.62%  |
| 2.01-3.0    | 494      | 22.67%  |
| 4.01-8.0    | 437      | 20.06%  |
| 3.01-4.0    | 318      | 14.59%  |
| 8.01-16.0   | 156      | 7.16%   |
| 0.51-1.0    | 100      | 4.59%   |
| 0.01-0.5    | 37       | 1.7%    |
| 16.01-24.0  | 32       | 1.47%   |
| 24.01-32.0  | 11       | 0.5%    |
| 32.01-64.0  | 9        | 0.41%   |
| 64.01-256.0 | 4        | 0.18%   |
| Unknown     | 1        | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 803      | 36.85%  |
| 2      | 622      | 28.55%  |
| 3      | 367      | 16.84%  |
| 4      | 179      | 8.21%   |
| 5      | 86       | 3.95%   |
| 6      | 57       | 2.62%   |
| 7      | 27       | 1.24%   |
| 0      | 11       | 0.5%    |
| 9      | 10       | 0.46%   |
| 8      | 10       | 0.46%   |
| 11     | 2        | 0.09%   |
| 10     | 2        | 0.09%   |
| 410    | 1        | 0.05%   |
| 19     | 1        | 0.05%   |
| 17     | 1        | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1388     | 63.7%   |
| Yes       | 791      | 36.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2159     | 99.08%  |
| No        | 20       | 0.92%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1097     | 50.34%  |
| Yes       | 1082     | 49.66%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1315     | 60.35%  |
| Yes       | 864      | 39.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 409      | 18.77%  |
| Germany      | 256      | 11.75%  |
| Russia       | 233      | 10.69%  |
| Italy        | 121      | 5.55%   |
| France       | 110      | 5.05%   |
| Brazil       | 100      | 4.59%   |
| UK           | 84       | 3.85%   |
| Canada       | 72       | 3.3%    |
| Hungary      | 66       | 3.03%   |
| Spain        | 60       | 2.75%   |
| Poland       | 46       | 2.11%   |
| Australia    | 46       | 2.11%   |
| Netherlands  | 35       | 1.61%   |
| Argentina    | 27       | 1.24%   |
| India        | 26       | 1.19%   |
| Switzerland  | 23       | 1.06%   |
| Turkey       | 22       | 1.01%   |
| Sweden       | 22       | 1.01%   |
| Mexico       | 22       | 1.01%   |
| Finland      | 21       | 0.96%   |
| Japan        | 20       | 0.92%   |
| Belgium      | 20       | 0.92%   |
| Austria      | 19       | 0.87%   |
| Czechia      | 17       | 0.78%   |
| South Africa | 14       | 0.64%   |
| Romania      | 14       | 0.64%   |
| Portugal     | 14       | 0.64%   |
| Taiwan       | 13       | 0.6%    |
| Norway       | 12       | 0.55%   |
| Greece       | 12       | 0.55%   |
| Colombia     | 12       | 0.55%   |
| China        | 12       | 0.55%   |
| Bulgaria     | 12       | 0.55%   |
| Indonesia    | 9        | 0.41%   |
| New Zealand  | 8        | 0.37%   |
| Denmark      | 8        | 0.37%   |
| Belarus      | 8        | 0.37%   |
| Vietnam      | 7        | 0.32%   |
| Venezuela    | 7        | 0.32%   |
| Thailand     | 7        | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City            | Desktops | Percent |
|-----------------|----------|---------|
| Moscow          | 61       | 2.8%    |
| Budapest        | 19       | 0.87%   |
| Sydney          | 18       | 0.83%   |
| Berlin          | 18       | 0.83%   |
| Warsaw          | 15       | 0.69%   |
| Voronezh        | 15       | 0.69%   |
| Toronto         | 15       | 0.69%   |
| Paris           | 15       | 0.69%   |
| Vienna          | 11       | 0.5%    |
| St Petersburg   | 11       | 0.5%    |
| Sao Paulo       | 11       | 0.5%    |
| Munich          | 10       | 0.46%   |
| Los Angeles     | 10       | 0.46%   |
| Melbourne       | 9        | 0.41%   |
| New York        | 8        | 0.37%   |
| Sofia           | 7        | 0.32%   |
| Rio de Janeiro  | 7        | 0.32%   |
| Montreal        | 7        | 0.32%   |
| Milan           | 7        | 0.32%   |
| Johannesburg    | 7        | 0.32%   |
| Istanbul        | 7        | 0.32%   |
| Hamburg         | 7        | 0.32%   |
| Buenos Aires    | 7        | 0.32%   |
| Zurich          | 6        | 0.28%   |
| Taipei          | 6        | 0.28%   |
| San Jose        | 6        | 0.28%   |
| Rome            | 6        | 0.28%   |
| Miami           | 6        | 0.28%   |
| Madrid          | 6        | 0.28%   |
| Krasnodar       | 6        | 0.28%   |
| Kansas City     | 6        | 0.28%   |
| Helsinki        | 6        | 0.28%   |
| Chelyabinsk     | 6        | 0.28%   |
| Atlanta         | 6        | 0.28%   |
| Singapore       | 5        | 0.23%   |
| Seattle         | 5        | 0.23%   |
| Perm            | 5        | 0.23%   |
| Nussdorf am Inn | 5        | 0.23%   |
| Minsk           | 5        | 0.23%   |
| Mexico City     | 5        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 654      | 862    | 15.96%  |
| Seagate                     | 628      | 824    | 15.32%  |
| Samsung Electronics         | 622      | 912    | 15.17%  |
| Kingston                    | 242      | 274    | 5.9%    |
| SanDisk                     | 208      | 246    | 5.07%   |
| Toshiba                     | 188      | 214    | 4.59%   |
| Crucial                     | 183      | 202    | 4.46%   |
| Hitachi                     | 101      | 116    | 2.46%   |
| Micron/Crucial Technology   | 66       | 75     | 1.61%   |
| Phison Electronics          | 64       | 71     | 1.56%   |
| China                       | 63       | 66     | 1.54%   |
| Intel                       | 62       | 87     | 1.51%   |
| A-DATA Technology           | 59       | 66     | 1.44%   |
| Unknown                     | 57       | 71     | 1.39%   |
| HGST                        | 52       | 75     | 1.27%   |
| SPCC                        | 40       | 48     | 0.98%   |
| Silicon Motion              | 40       | 40     | 0.98%   |
| Kingston Technology Company | 38       | 42     | 0.93%   |
| PNY                         | 33       | 42     | 0.81%   |
| SK hynix                    | 32       | 33     | 0.78%   |
| Patriot                     | 28       | 29     | 0.68%   |
| Intenso                     | 28       | 29     | 0.68%   |
| Maxtor                      | 24       | 24     | 0.59%   |
| Micron Technology           | 23       | 23     | 0.56%   |
| Apacer                      | 23       | 25     | 0.56%   |
| Realtek Semiconductor       | 21       | 22     | 0.51%   |
| MAXIO Technology (Hangzhou) | 21       | 22     | 0.51%   |
| Unknown                     | 19       | 19     | 0.46%   |
| KingSpec                    | 18       | 20     | 0.44%   |
| ADATA Technology            | 18       | 21     | 0.44%   |
| Team                        | 17       | 18     | 0.41%   |
| Lexar                       | 17       | 18     | 0.41%   |
| Netac                       | 15       | 15     | 0.37%   |
| Corsair                     | 15       | 29     | 0.37%   |
| Hewlett-Packard             | 14       | 14     | 0.34%   |
| Transcend                   | 13       | 13     | 0.32%   |
| OCZ                         | 13       | 13     | 0.32%   |
| Gigabyte Technology         | 13       | 13     | 0.32%   |
| GOODRAM                     | 12       | 13     | 0.29%   |
| Fujitsu                     | 10       | 10     | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 115      | 2.45%   |
| Seagate ST2000DM008-2FR102 2TB                        | 64       | 1.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 55       | 1.17%   |
| Kingston SA400S37240G 240GB SSD                       | 55       | 1.17%   |
| Seagate ST1000DM010-2EP102 1TB                        | 46       | 0.98%   |
| Samsung SSD 850 EVO 250GB                             | 41       | 0.87%   |
| Samsung SSD 860 EVO 500GB                             | 40       | 0.85%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 40       | 0.85%   |
| Seagate ST500DM002-1BD142 500GB                       | 38       | 0.81%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 36       | 0.77%   |
| Toshiba DT01ACA100 1TB                                | 36       | 0.77%   |
| Samsung SSD 980 1TB                                   | 35       | 0.74%   |
| Kingston SA400S37480G 480GB SSD                       | 33       | 0.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 29       | 0.62%   |
| Samsung SSD 870 EVO 1TB                               | 29       | 0.62%   |
| Samsung SSD 860 EVO 1TB                               | 26       | 0.55%   |
| Crucial CT500MX500SSD1 500GB                          | 26       | 0.55%   |
| Crucial CT1000MX500SSD1 1TB                           | 25       | 0.53%   |
| Seagate ST1000DM003-1ER162 1TB                        | 23       | 0.49%   |
| Seagate ST1000DM003-1CH162 1TB                        | 23       | 0.49%   |
| Samsung SSD 850 EVO 500GB                             | 23       | 0.49%   |
| Unknown SD/MMC/MS PRO 16GB                            | 22       | 0.47%   |
| Seagate ST2000DM006-2DM164 2TB                        | 22       | 0.47%   |
| Kingston SA400S37120G 120GB SSD                       | 21       | 0.45%   |
| Crucial CT240BX500SSD1 240GB                          | 20       | 0.43%   |
| Seagate ST4000DM004-2CV104 4TB                        | 19       | 0.4%    |
| Samsung SSD 870 QVO 1TB                               | 19       | 0.4%    |
| Phison E16 PCIe4 NVMe Controller 500GB                | 19       | 0.4%    |
| Kingston SV300S37A120G 120GB SSD                      | 19       | 0.4%    |
| Unknown                                               | 19       | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 18       | 0.38%   |
| Toshiba DT01ACA050 500GB                              | 18       | 0.38%   |
| Samsung SSD 980 500GB                                 | 18       | 0.38%   |
| Samsung SSD 860 EVO 250GB                             | 18       | 0.38%   |
| Crucial CT480BX500SSD1 480GB                          | 18       | 0.38%   |
| Seagate ST3500418AS 500GB                             | 17       | 0.36%   |
| Seagate ST2000DM008-2UB102 2TB                        | 17       | 0.36%   |
| Samsung SSD 990 PRO 2TB                               | 16       | 0.34%   |
| Phison E12 NVMe Controller 1TB                        | 16       | 0.34%   |
| WDC WD10EZEX-00BN5A0 1TB                              | 15       | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 607      | 799    | 36.7%   |
| WDC                 | 571      | 738    | 34.52%  |
| Toshiba             | 161      | 183    | 9.73%   |
| Hitachi             | 101      | 116    | 6.11%   |
| Samsung Electronics | 83       | 100    | 5.02%   |
| HGST                | 51       | 74     | 3.08%   |
| Unknown             | 23       | 23     | 1.39%   |
| Maxtor              | 22       | 22     | 1.33%   |
| Fujitsu             | 10       | 10     | 0.6%    |
| USB3.0              | 3        | 3      | 0.18%   |
| Hewlett-Packard     | 3        | 3      | 0.18%   |
| Apple               | 3        | 3      | 0.18%   |
| SSK                 | 2        | 2      | 0.12%   |
| Intenso             | 2        | 2      | 0.12%   |
| HPE                 | 2        | 2      | 0.12%   |
| Unknown             | 2        | 2      | 0.12%   |
| SABRENT             | 1        | 1      | 0.06%   |
| QNAP                | 1        | 6      | 0.06%   |
| Maxone              | 1        | 1      | 0.06%   |
| Magnetic Data       | 1        | 1      | 0.06%   |
| Initio              | 1        | 1      | 0.06%   |
| IBM/Hitachi         | 1        | 1      | 0.06%   |
| ASMT                | 1        | 1      | 0.06%   |
| ASMedia             | 1        | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 331      | 411    | 22.04%  |
| Kingston            | 177      | 194    | 11.78%  |
| Crucial             | 166      | 175    | 11.05%  |
| SanDisk             | 101      | 113    | 6.72%   |
| WDC                 | 97       | 100    | 6.46%   |
| China               | 63       | 66     | 4.19%   |
| A-DATA Technology   | 52       | 58     | 3.46%   |
| SPCC                | 35       | 42     | 2.33%   |
| PNY                 | 31       | 37     | 2.06%   |
| Intel               | 28       | 49     | 1.86%   |
| Patriot             | 26       | 27     | 1.73%   |
| Toshiba             | 20       | 21     | 1.33%   |
| Intenso             | 19       | 20     | 1.26%   |
| Apacer              | 19       | 21     | 1.26%   |
| KingSpec            | 18       | 20     | 1.2%    |
| Team                | 16       | 17     | 1.07%   |
| Micron Technology   | 16       | 16     | 1.07%   |
| OCZ                 | 13       | 13     | 0.87%   |
| GOODRAM             | 12       | 13     | 0.8%    |
| Corsair             | 12       | 23     | 0.8%    |
| Transcend           | 11       | 11     | 0.73%   |
| SK hynix            | 11       | 11     | 0.73%   |
| Netac               | 10       | 10     | 0.67%   |
| Hewlett-Packard     | 10       | 10     | 0.67%   |
| Lexar               | 9        | 10     | 0.6%    |
| Gigabyte Technology | 8        | 8      | 0.53%   |
| XrayDisk            | 7        | 7      | 0.47%   |
| Unknown             | 7        | 7      | 0.47%   |
| Smartbuy            | 6        | 6      | 0.4%    |
| SABRENT             | 6        | 6      | 0.4%    |
| Emtec               | 6        | 6      | 0.4%    |
| Verbatim            | 5        | 5      | 0.33%   |
| KingFast            | 5        | 5      | 0.33%   |
| T-FORCE             | 4        | 4      | 0.27%   |
| Seagate             | 4        | 4      | 0.27%   |
| Mushkin             | 4        | 4      | 0.27%   |
| LITEONIT            | 4        | 4      | 0.27%   |
| KingDian            | 4        | 4      | 0.27%   |
| Kimtigo             | 4        | 4      | 0.27%   |
| Fanxiang            | 4        | 4      | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1288     | 2095   | 37.44%  |
| SSD     | 1213     | 2100   | 35.26%  |
| NVMe    | 851      | 1192   | 24.74%  |
| Unknown | 81       | 93     | 2.35%   |
| MMC     | 7        | 10     | 0.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1859     | 4043   | 64.08%  |
| NVMe | 849      | 1180   | 29.27%  |
| SAS  | 186      | 257    | 6.41%   |
| MMC  | 7        | 10     | 0.24%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1264     | 2262   | 46.5%   |
| 0.51-1.0   | 801      | 1052   | 29.47%  |
| 1.01-2.0   | 339      | 419    | 12.47%  |
| 3.01-4.0   | 129      | 186    | 4.75%   |
| 2.01-3.0   | 92       | 129    | 3.38%   |
| 4.01-10.0  | 71       | 106    | 2.61%   |
| 10.01-20.0 | 21       | 40     | 0.77%   |
| 20.01-50.0 | 1        | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 410      | 18.82%  |
| 251-500        | 364      | 16.7%   |
| 501-1000       | 361      | 16.57%  |
| More than 3000 | 313      | 14.36%  |
| 1001-2000      | 272      | 12.48%  |
| 2001-3000      | 128      | 5.87%   |
| Unknown        | 118      | 5.42%   |
| 1-20           | 93       | 4.27%   |
| 51-100         | 84       | 3.85%   |
| 21-50          | 36       | 1.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 557      | 25.56%  |
| 21-50          | 316      | 14.5%   |
| 101-250        | 264      | 12.12%  |
| 51-100         | 229      | 10.51%  |
| 251-500        | 212      | 9.73%   |
| 501-1000       | 174      | 7.99%   |
| 1001-2000      | 133      | 6.1%    |
| More than 3000 | 126      | 5.78%   |
| Unknown        | 118      | 5.42%   |
| 2001-3000      | 50       | 2.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                                   | Desktops | Drives | Percent |
|-----------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB         | 8        | 8      | 2.41%   |
| Seagate ST3500418AS 500GB               | 6        | 8      | 1.81%   |
| Seagate ST1000DM010-2EP102 1TB          | 5        | 5      | 1.51%   |
| Toshiba DT01ACA100 1TB                  | 4        | 4      | 1.2%    |
| Seagate ST1000DM003-1ER162 1TB          | 4        | 4      | 1.2%    |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 3        | 3      | 0.9%    |
| WDC WD5000AAKS-00UU3A0 500GB            | 3        | 3      | 0.9%    |
| WDC WD20EZRX-00D8PB0 2TB                | 3        | 3      | 0.9%    |
| Seagate ST31000524AS 1TB                | 3        | 3      | 0.9%    |
| Seagate ST2000DM008-2FR102 2TB          | 3        | 4      | 0.9%    |
| SanDisk SSD PLUS 1000GB                 | 3        | 3      | 0.9%    |
| Samsung Electronics SSD 870 EVO 500GB   | 3        | 3      | 0.9%    |
| Samsung Electronics SSD 870 EVO 1TB     | 3        | 3      | 0.9%    |
| Samsung Electronics HD501LJ 500GB       | 3        | 4      | 0.9%    |
| Neo Forza NFS121SA312-6007000 120GB SSD | 3        | 3      | 0.9%    |
| Intel SSDSC2BB800G7 800GB               | 3        | 3      | 0.9%    |
| Hitachi HDP725050GLA360 500GB           | 3        | 3      | 0.9%    |
| WDC WD5000AAKX-00ERMA0 500GB            | 2        | 2      | 0.6%    |
| WDC WD5000AAKS-22A7B0 500GB             | 2        | 2      | 0.6%    |
| WDC WD5000AAKS-007AA0 500GB             | 2        | 2      | 0.6%    |
| WDC WD30EFRX-68EUZN0 3TB                | 2        | 2      | 0.6%    |
| WDC WD2500AAKX-001CA0 250GB             | 2        | 2      | 0.6%    |
| WDC WD20EFRX-68EUZN0 2TB                | 2        | 2      | 0.6%    |
| WDC WD2002FAEX-007BA0 2TB               | 2        | 2      | 0.6%    |
| WDC WD10PURZ-85U8XY0 1TB                | 2        | 2      | 0.6%    |
| Toshiba MK1655GSX 160GB                 | 2        | 2      | 0.6%    |
| Toshiba DT01ACA050 500GB                | 2        | 2      | 0.6%    |
| Seagate ST500LT012-9WS142 500GB         | 2        | 2      | 0.6%    |
| Seagate ST4000DM000-1F2168 4TB          | 2        | 2      | 0.6%    |
| Seagate ST3250410AS 250GB               | 2        | 2      | 0.6%    |
| Seagate ST3160815AS 160GB               | 2        | 2      | 0.6%    |
| Seagate ST31000528AS 1TB                | 2        | 2      | 0.6%    |
| Seagate ST2000DM006-2DM164 2TB          | 2        | 3      | 0.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 2        | 2      | 0.6%    |
| Seagate ST1000DM003-1SB10C 1TB          | 2        | 2      | 0.6%    |
| Seagate ST1000DM003-1CH162 1TB          | 2        | 2      | 0.6%    |
| Kingston SA400S37480G 480GB SSD         | 2        | 2      | 0.6%    |
| Hitachi HTS543232A7A384 320GB           | 2        | 2      | 0.6%    |
| Hitachi HDS721050CLA662 500GB           | 2        | 2      | 0.6%    |
| HGST HTS725050A7E630 500GB              | 2        | 2      | 0.6%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 88       | 99     | 27.5%   |
| Seagate             | 84       | 95     | 26.25%  |
| Samsung Electronics | 35       | 38     | 10.94%  |
| Hitachi             | 19       | 20     | 5.94%   |
| Toshiba             | 17       | 17     | 5.31%   |
| Maxtor              | 9        | 9      | 2.81%   |
| Intel               | 9        | 11     | 2.81%   |
| Kingston            | 8        | 8      | 2.5%    |
| HGST                | 6        | 6      | 1.88%   |
| A-DATA Technology   | 6        | 7      | 1.88%   |
| Corsair             | 5        | 5      | 1.56%   |
| SanDisk             | 3        | 3      | 0.94%   |
| Neo                 | 3        | 3      | 0.94%   |
| Crucial             | 3        | 3      | 0.94%   |
| China               | 3        | 3      | 0.94%   |
| Fujitsu             | 2        | 2      | 0.63%   |
| ASMedia             | 2        | 2      | 0.63%   |
| XrayDisk            | 1        | 1      | 0.31%   |
| Silicon Motion      | 1        | 1      | 0.31%   |
| PNY                 | 1        | 1      | 0.31%   |
| OCZ                 | 1        | 1      | 0.31%   |
| Netac               | 1        | 1      | 0.31%   |
| Micron Technology   | 1        | 1      | 0.31%   |
| Magnetic Data       | 1        | 1      | 0.31%   |
| KingFast            | 1        | 1      | 0.31%   |
| JMicron Technology  | 1        | 1      | 0.31%   |
| IBM/Hitachi         | 1        | 1      | 0.31%   |
| HS-SSD-C100         | 1        | 1      | 0.31%   |
| HPE                 | 1        | 1      | 0.31%   |
| Gigastone           | 1        | 1      | 0.31%   |
| Gamers              | 1        | 1      | 0.31%   |
| EXRAM               | 1        | 1      | 0.31%   |
| Colorful            | 1        | 1      | 0.31%   |
| BAITITON            | 1        | 1      | 0.31%   |
| Unknown             | 1        | 1      | 0.31%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 84       | 95     | 35.44%  |
| WDC                 | 80       | 91     | 33.76%  |
| Hitachi             | 19       | 20     | 8.02%   |
| Samsung Electronics | 17       | 20     | 7.17%   |
| Toshiba             | 15       | 15     | 6.33%   |
| Maxtor              | 9        | 9      | 3.8%    |
| HGST                | 6        | 6      | 2.53%   |
| Fujitsu             | 2        | 2      | 0.84%   |
| Magnetic Data       | 1        | 1      | 0.42%   |
| IBM/Hitachi         | 1        | 1      | 0.42%   |
| HPE                 | 1        | 1      | 0.42%   |
| ASMedia             | 1        | 1      | 0.42%   |
| Unknown             | 1        | 1      | 0.42%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 213      | 263    | 71.96%  |
| SSD     | 73       | 76     | 24.66%  |
| NVMe    | 9        | 9      | 3.04%   |
| Unknown | 1        | 1      | 0.34%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)

![Failed Drives](./images/line_chart/drive_failed.svg)

| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Toshiba HDWD110 1TB       | 1        | 1      | 33.33%  |
| Intel SSDSC2BB480G7 480GB | 1        | 4      | 33.33%  |
| HGST HTS541010A9E680 1TB  | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)

![Failed Drive Vendor](./images/line_chart/drive_failed_vendor.svg)

| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 1        | 1      | 33.33%  |
| Intel   | 1        | 4      | 33.33%  |
| HGST    | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)

![Drive Status](./images/line_chart/drive_status.svg)

| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1142     | 2557   | 46.37%  |
| Works    | 1034     | 2578   | 41.98%  |
| Malfunc  | 284      | 349    | 11.53%  |
| Failed   | 3        | 6      | 0.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1329     | 39.05%  |
| AMD                              | 803      | 23.6%   |
| Samsung Electronics              | 307      | 9.02%   |
| SanDisk                          | 133      | 3.91%   |
| ASMedia Technology               | 114      | 3.35%   |
| Kingston Technology Company      | 111      | 3.26%   |
| Phison Electronics               | 88       | 2.59%   |
| Micron/Crucial Technology        | 88       | 2.59%   |
| Marvell Technology Group         | 63       | 1.85%   |
| JMicron Technology               | 57       | 1.67%   |
| Silicon Motion                   | 47       | 1.38%   |
| MAXIO Technology (Hangzhou)      | 34       | 1%      |
| Nvidia                           | 29       | 0.85%   |
| ADATA Technology                 | 29       | 0.85%   |
| Realtek Semiconductor            | 28       | 0.82%   |
| SK hynix                         | 21       | 0.62%   |
| Seagate Technology               | 13       | 0.38%   |
| Shenzhen Longsys Electronics     | 12       | 0.35%   |
| Toshiba America Info Systems     | 11       | 0.32%   |
| Broadcom / LSI                   | 11       | 0.32%   |
| VIA Technologies                 | 10       | 0.29%   |
| LSI Logic / Symbios Logic        | 10       | 0.29%   |
| KIOXIA                           | 9        | 0.26%   |
| Micron Technology                | 7        | 0.21%   |
| INNOGRIT                         | 7        | 0.21%   |
| Solidigm                         | 4        | 0.12%   |
| Silicon Image                    | 4        | 0.12%   |
| Adaptec                          | 4        | 0.12%   |
| Hosin Global Electronics         | 3        | 0.09%   |
| Union Memory (Shenzhen)          | 2        | 0.06%   |
| Transcend                        | 2        | 0.06%   |
| Silicon Integrated Systems [SiS] | 2        | 0.06%   |
| Netac Technology                 | 2        | 0.06%   |
| Biwin Storage Technology         | 2        | 0.06%   |
| ULi Electronics                  | 1        | 0.03%   |
| Shenzhen Shichuangyi Electronics | 1        | 0.03%   |
| O2 Micro                         | 1        | 0.03%   |
| Lite-On Technology               | 1        | 0.03%   |
| HighPoint Technologies           | 1        | 0.03%   |
| HGST                             | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 443      | 10.79%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 162      | 3.95%   |
| AMD 500 Series Chipset SATA Controller                                                  | 158      | 3.85%   |
| AMD 400 Series Chipset SATA Controller                                                  | 152      | 3.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 149      | 3.63%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 103      | 2.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 97       | 2.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 92       | 2.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 82       | 2%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 79       | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 79       | 1.92%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 77       | 1.88%   |
| Intel SATA Controller [RAID mode]                                                       | 74       | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 73       | 1.78%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 67       | 1.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 66       | 1.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 64       | 1.56%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 62       | 1.51%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 58       | 1.41%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 56       | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 52       | 1.27%   |
| AMD FCH SATA Controller D                                                               | 48       | 1.17%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                                    | 46       | 1.12%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 42       | 1.02%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 40       | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 36       | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 36       | 0.88%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 33       | 0.8%    |
| AMD 300 Series Chipset SATA Controller                                                  | 32       | 0.78%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 31       | 0.76%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 31       | 0.76%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                                  | 30       | 0.73%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 29       | 0.71%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 29       | 0.71%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 27       | 0.66%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                                      | 26       | 0.63%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 25       | 0.61%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 25       | 0.61%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 25       | 0.61%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 24       | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1819     | 56.07%  |
| NVMe | 850      | 26.2%   |
| IDE  | 381      | 11.74%  |
| RAID | 163      | 5.02%   |
| SAS  | 25       | 0.77%   |
| SCSI | 6        | 0.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 1325     | 60.81%  |
| AMD          | 851      | 39.05%  |
| Unknown      | 2        | 0.09%   |
| CentaurHauls | 1        | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 44       | 2.02%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 36       | 1.65%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 31       | 1.42%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 30       | 1.38%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 28       | 1.28%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 24       | 1.1%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 24       | 1.1%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 23       | 1.06%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 23       | 1.06%   |
| AMD FX-8350 Eight-Core Processor            | 23       | 1.06%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 21       | 0.96%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 21       | 0.96%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 21       | 0.96%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 20       | 0.92%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 19       | 0.87%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 19       | 0.87%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 18       | 0.83%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 18       | 0.83%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 18       | 0.83%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 17       | 0.78%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 16       | 0.73%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 16       | 0.73%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 16       | 0.73%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 15       | 0.69%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 15       | 0.69%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 14       | 0.64%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 14       | 0.64%   |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 14       | 0.64%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 13       | 0.6%    |
| Intel Core i5-10400 CPU @ 2.90GHz           | 13       | 0.6%    |
| AMD Ryzen 5 5600 6-Core Processor           | 13       | 0.6%    |
| AMD Ryzen 5 5500                            | 13       | 0.6%    |
| Intel Core i7-8700K CPU @ 3.70GHz           | 12       | 0.55%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 12       | 0.55%   |
| Intel 12th Gen Core i5-12400                | 12       | 0.55%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 12       | 0.55%   |
| AMD FX-6300 Six-Core Processor              | 12       | 0.55%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 11       | 0.5%    |
| Intel Core i5-4460 CPU @ 3.20GHz            | 11       | 0.5%    |
| Intel Core i5-3570 CPU @ 3.40GHz            | 11       | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 360      | 16.52%  |
| Intel Core i7           | 263      | 12.07%  |
| AMD Ryzen 5             | 252      | 11.56%  |
| AMD Ryzen 7             | 174      | 7.99%   |
| Other                   | 168      | 7.71%   |
| Intel Xeon              | 134      | 6.15%   |
| Intel Core i3           | 119      | 5.46%   |
| AMD Ryzen 9             | 117      | 5.37%   |
| Intel Celeron           | 65       | 2.98%   |
| AMD FX                  | 65       | 2.98%   |
| Intel Core 2 Duo        | 49       | 2.25%   |
| AMD Ryzen 3             | 40       | 1.84%   |
| Intel Pentium           | 38       | 1.74%   |
| Intel Pentium Dual-Core | 33       | 1.51%   |
| Intel Core 2 Quad       | 31       | 1.42%   |
| Intel Core i9           | 26       | 1.19%   |
| AMD A10                 | 20       | 0.92%   |
| AMD Athlon II X2        | 16       | 0.73%   |
| AMD A8                  | 16       | 0.73%   |
| Intel Core 2            | 15       | 0.69%   |
| AMD Phenom II X4        | 15       | 0.69%   |
| AMD Athlon II X4        | 15       | 0.69%   |
| AMD Ryzen 5 PRO         | 12       | 0.55%   |
| AMD A6                  | 12       | 0.55%   |
| AMD Phenom II X6        | 11       | 0.5%    |
| AMD Ryzen Threadripper  | 9        | 0.41%   |
| AMD A4                  | 9        | 0.41%   |
| Intel Atom              | 8        | 0.37%   |
| AMD Athlon 64 X2        | 8        | 0.37%   |
| Intel Pentium 4         | 7        | 0.32%   |
| Intel Pentium Dual      | 6        | 0.28%   |
| AMD Athlon              | 6        | 0.28%   |
| AMD Phenom II X2        | 5        | 0.23%   |
| AMD GX                  | 5        | 0.23%   |
| AMD G                   | 5        | 0.23%   |
| AMD Athlon Dual Core    | 4        | 0.18%   |
| Intel Pentium Gold      | 3        | 0.14%   |
| Intel Genuine           | 3        | 0.14%   |
| AMD Ryzen 7 PRO         | 3        | 0.14%   |
| AMD PRO A10             | 3        | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 770      | 35.34%  |
| 6       | 404      | 18.54%  |
| 2       | 393      | 18.04%  |
| 8       | 267      | 12.25%  |
| 12      | 95       | 4.36%   |
| 16      | 87       | 3.99%   |
| 10      | 40       | 1.84%   |
| 1       | 35       | 1.61%   |
| 24      | 28       | 1.28%   |
| 3       | 26       | 1.19%   |
| 14      | 20       | 0.92%   |
| 28      | 4        | 0.18%   |
| 32      | 3        | 0.14%   |
| 18      | 3        | 0.14%   |
| 36      | 2        | 0.09%   |
| 20      | 1        | 0.05%   |
| Unknown | 1        | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2135     | 97.98%  |
| 2       | 43       | 1.97%   |
| Unknown | 1        | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1363     | 62.55%  |
| 1       | 815      | 37.4%   |
| Unknown | 1        | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2171     | 99.63%  |
| 32-bit         | 5        | 0.23%   |
| Unknown        | 3        | 0.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1079     | 49.52%  |
| 0x306c3    | 84       | 3.85%   |
| 0x0a601203 | 52       | 2.39%   |
| 0x1067a    | 48       | 2.2%    |
| 0x0a20120a | 48       | 2.2%    |
| 0x08701021 | 44       | 2.02%   |
| 0x306a9    | 42       | 1.93%   |
| 0x206a7    | 42       | 1.93%   |
| 0x0a50000d | 36       | 1.65%   |
| 0x0800820d | 33       | 1.51%   |
| 0x906ea    | 29       | 1.33%   |
| 0x506e3    | 29       | 1.33%   |
| 0x08701030 | 29       | 1.33%   |
| 0x08108109 | 26       | 1.19%   |
| 0x010000c8 | 26       | 1.19%   |
| 0x06000852 | 25       | 1.15%   |
| 0x906e9    | 20       | 0.92%   |
| 0x0a50000c | 20       | 0.92%   |
| 0x306f2    | 18       | 0.83%   |
| 0x0a201016 | 16       | 0.73%   |
| 0xa0653    | 15       | 0.69%   |
| 0x08101016 | 15       | 0.69%   |
| 0x06001119 | 15       | 0.69%   |
| 0x406f1    | 13       | 0.6%    |
| 0x0a201025 | 13       | 0.6%    |
| 0x08001138 | 12       | 0.55%   |
| 0x90672    | 10       | 0.46%   |
| 0x306e4    | 10       | 0.46%   |
| 0x06003106 | 10       | 0.46%   |
| 0xa0671    | 9        | 0.41%   |
| 0x106a5    | 9        | 0.41%   |
| 0x0a601206 | 9        | 0.41%   |
| 0x08600106 | 9        | 0.41%   |
| 0xb0671    | 8        | 0.37%   |
| 0xa0655    | 8        | 0.37%   |
| 0x08701013 | 8        | 0.37%   |
| 0x08001137 | 8        | 0.37%   |
| 0x706a8    | 7        | 0.32%   |
| 0x6fb      | 7        | 0.32%   |
| 0x0a201009 | 7        | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 247      | 11.34%  |
| Zen 3            | 226      | 10.37%  |
| KabyLake         | 186      | 8.54%   |
| Unknown          | 159      | 7.3%    |
| Zen 2            | 146      | 6.7%    |
| IvyBridge        | 138      | 6.33%   |
| SandyBridge      | 115      | 5.28%   |
| Skylake          | 108      | 4.96%   |
| Penryn           | 107      | 4.91%   |
| Zen+             | 92       | 4.22%   |
| Piledriver       | 80       | 3.67%   |
| Alderlake Hybrid | 73       | 3.35%   |
| K10              | 70       | 3.21%   |
| CometLake        | 70       | 3.21%   |
| Zen              | 57       | 2.62%   |
| Core             | 44       | 2.02%   |
| Nehalem          | 33       | 1.51%   |
| Westmere         | 26       | 1.19%   |
| Icelake          | 26       | 1.19%   |
| Broadwell        | 22       | 1.01%   |
| Excavator        | 18       | 0.83%   |
| K8 Hammer        | 16       | 0.73%   |
| Steamroller      | 15       | 0.69%   |
| Silvermont       | 15       | 0.69%   |
| Goldmont plus    | 15       | 0.69%   |
| NetBurst         | 11       | 0.5%    |
| Bulldozer        | 11       | 0.5%    |
| Tremont          | 10       | 0.46%   |
| K10 Llano        | 8        | 0.37%   |
| Bobcat           | 8        | 0.37%   |
| Jaguar           | 7        | 0.32%   |
| Gracemont        | 6        | 0.28%   |
| Goldmont         | 5        | 0.23%   |
| Bonnell          | 4        | 0.18%   |
| Puma             | 3        | 0.14%   |
| TigerLake        | 2        | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 855      | 36.46%  |
| AMD                                          | 787      | 33.56%  |
| Intel                                        | 676      | 28.83%  |
| ASPEED Technology                            | 16       | 0.68%   |
| Matrox Electronics Systems                   | 7        | 0.3%    |
| ATI Technologies                             | 2        | 0.09%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.04%   |
| VIA Technologies                             | 1        | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 120      | 4.99%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 81       | 3.37%   |
| AMD Raphael                                                                 | 58       | 2.41%   |
| Intel HD Graphics 530                                                       | 54       | 2.25%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 53       | 2.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 51       | 2.12%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 49       | 2.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 48       | 2%      |
| Nvidia GK208B [GeForce GT 710]                                              | 40       | 1.66%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 39       | 1.62%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 36       | 1.5%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 34       | 1.41%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 34       | 1.41%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 34       | 1.41%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 32       | 1.33%   |
| Intel HD Graphics 630                                                       | 29       | 1.21%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 29       | 1.21%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 25       | 1.04%   |
| Intel AlderLake-S GT1                                                       | 25       | 1.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 25       | 1.04%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 23       | 0.96%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 23       | 0.96%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 23       | 0.96%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 22       | 0.91%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 22       | 0.91%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 21       | 0.87%   |
| Nvidia GK208B [GeForce GT 730]                                              | 20       | 0.83%   |
| Nvidia GF119 [GeForce GT 610]                                               | 20       | 0.83%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 20       | 0.83%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 20       | 0.83%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 19       | 0.79%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 19       | 0.79%   |
| Nvidia GT218 [GeForce 210]                                                  | 18       | 0.75%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 17       | 0.71%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 17       | 0.71%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 17       | 0.71%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 17       | 0.71%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 16       | 0.67%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 16       | 0.67%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 16       | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 752      | 34.51%  |
| 1 x AMD         | 670      | 30.75%  |
| 1 x Intel       | 554      | 25.42%  |
| 2 x AMD         | 50       | 2.29%   |
| Intel + Nvidia  | 48       | 2.2%    |
| AMD + Nvidia    | 41       | 1.88%   |
| Intel + AMD     | 21       | 0.96%   |
| 1 x ASPEED      | 16       | 0.73%   |
| 2 x Nvidia      | 6        | 0.28%   |
| Other           | 5        | 0.23%   |
| 1 x Matrox      | 5        | 0.23%   |
| 2 x Intel       | 4        | 0.18%   |
| 3 x Nvidia      | 1        | 0.05%   |
| 3 x AMD         | 1        | 0.05%   |
| 1 x XGI         | 1        | 0.05%   |
| Nvidia + Matrox | 1        | 0.05%   |
| Intel + 2 x AMD | 1        | 0.05%   |
| AMD + VIA       | 1        | 0.05%   |
| AMD + Matrox    | 1        | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1558     | 71.5%   |
| Proprietary | 505      | 23.18%  |
| Unknown     | 116      | 5.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1048     | 48.1%   |
| 1.01-2.0   | 236      | 10.83%  |
| 7.01-8.0   | 206      | 9.45%   |
| 0.01-0.5   | 184      | 8.44%   |
| 3.01-4.0   | 142      | 6.52%   |
| 0.51-1.0   | 138      | 6.33%   |
| 8.01-16.0  | 110      | 5.05%   |
| 5.01-6.0   | 69       | 3.17%   |
| 16.01-24.0 | 28       | 1.28%   |
| 2.01-3.0   | 16       | 0.73%   |
| 4.01-5.0   | 2        | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 387      | 17.04%  |
| Goldstar             | 270      | 11.89%  |
| Dell                 | 231      | 10.17%  |
| Hewlett-Packard      | 162      | 7.13%   |
| Acer                 | 151      | 6.65%   |
| AOC                  | 119      | 5.24%   |
| Philips              | 107      | 4.71%   |
| BenQ                 | 100      | 4.4%    |
| Ancor Communications | 96       | 4.23%   |
| ViewSonic            | 49       | 2.16%   |
| Lenovo               | 49       | 2.16%   |
| ASUSTek Computer     | 45       | 1.98%   |
| Iiyama               | 36       | 1.59%   |
| Sony                 | 26       | 1.14%   |
| Eizo                 | 25       | 1.1%    |
| Unknown              | 23       | 1.01%   |
| MSI                  | 22       | 0.97%   |
| Fujitsu Siemens      | 21       | 0.92%   |
| Gigabyte Technology  | 20       | 0.88%   |
| LG Electronics       | 18       | 0.79%   |
| RTK                  | 14       | 0.62%   |
| Unknown              | 13       | 0.57%   |
| Sceptre Tech         | 11       | 0.48%   |
| Panasonic            | 11       | 0.48%   |
| NEC Computers        | 11       | 0.48%   |
| Mi                   | 11       | 0.48%   |
| Vizio                | 10       | 0.44%   |
| Hitachi              | 10       | 0.44%   |
| HKC                  | 9        | 0.4%    |
| HannStar             | 9        | 0.4%    |
| ___                  | 7        | 0.31%   |
| Medion               | 7        | 0.31%   |
| HUAWEI               | 6        | 0.26%   |
| Toshiba              | 5        | 0.22%   |
| Plain Tree Systems   | 5        | 0.22%   |
| Packard Bell         | 5        | 0.22%   |
| Denver               | 5        | 0.22%   |
| AGO                  | 5        | 0.22%   |
| Vestel Elektronik    | 4        | 0.18%   |
| RGT                  | 4        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 20       | 0.83%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 14       | 0.58%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 14       | 0.58%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 14       | 0.58%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 13       | 0.54%   |
| AOC Q27P2W AOC2702 2560x1440 597x336mm 27.0-inch                      | 13       | 0.54%   |
| Unknown                                                               | 13       | 0.54%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 12       | 0.5%    |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 12       | 0.5%    |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 10       | 0.42%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 9        | 0.37%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch              | 8        | 0.33%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 7        | 0.29%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 7        | 0.29%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 7        | 0.29%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 530x300mm 24.0-inch     | 6        | 0.25%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 6        | 0.25%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 6        | 0.25%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 6        | 0.25%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 5        | 0.21%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 5        | 0.21%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 5        | 0.21%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 5        | 0.21%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 5        | 0.21%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 5        | 0.21%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 5        | 0.21%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 5        | 0.21%   |
| Dell SE198WFP DELF004 1440x900 408x255mm 18.9-inch                    | 5        | 0.21%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 5        | 0.21%   |
| ___ LCD TV ___9000 1360x768                                           | 4        | 0.17%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 4        | 0.17%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 4        | 0.17%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 4        | 0.17%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 4        | 0.17%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 4        | 0.17%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch           | 4        | 0.17%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 4        | 0.17%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                   | 4        | 0.17%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                     | 4        | 0.17%   |
| Dell P2414H DELA09A 1920x1080 527x297mm 23.8-inch                     | 4        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1055     | 48.04%  |
| 3840x2160 (4K)     | 251      | 11.43%  |
| 2560x1440 (QHD)    | 199      | 9.06%   |
| 1280x1024 (SXGA)   | 121      | 5.51%   |
| 1680x1050 (WSXGA+) | 96       | 4.37%   |
| 1920x1200 (WUXGA)  | 69       | 3.14%   |
| 1366x768 (WXGA)    | 60       | 2.73%   |
| 1440x900 (WXGA+)   | 58       | 2.64%   |
| 1600x900 (HD+)     | 50       | 2.28%   |
| 3440x1440          | 43       | 1.96%   |
| 2560x1080          | 40       | 1.82%   |
| Unknown            | 26       | 1.18%   |
| 3840x1080          | 25       | 1.14%   |
| 1360x768           | 24       | 1.09%   |
| 2288x1287          | 15       | 0.68%   |
| 1024x768 (XGA)     | 12       | 0.55%   |
| 1920x540           | 7        | 0.32%   |
| 1600x1200          | 6        | 0.27%   |
| 1280x720 (HD)      | 6        | 0.27%   |
| 2560x1600          | 5        | 0.23%   |
| 4480x1440          | 3        | 0.14%   |
| 3840x1600          | 3        | 0.14%   |
| 2048x1152          | 3        | 0.14%   |
| 1400x1050          | 3        | 0.14%   |
| 1280x768           | 2        | 0.09%   |
| 9600x1440          | 1        | 0.05%   |
| 7040x1440          | 1        | 0.05%   |
| 5760x2160          | 1        | 0.05%   |
| 5200x1080          | 1        | 0.05%   |
| 4800x1080          | 1        | 0.05%   |
| 3468x1468          | 1        | 0.05%   |
| 3360x1080          | 1        | 0.05%   |
| 3360x1050          | 1        | 0.05%   |
| 3200x1080          | 1        | 0.05%   |
| 2880x1024          | 1        | 0.05%   |
| 2720x768           | 1        | 0.05%   |
| 2560x1024          | 1        | 0.05%   |
| 1920x1440          | 1        | 0.05%   |
| 1360x765           | 1        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 368      | 16.25%  |
| 24      | 321      | 14.17%  |
| 23      | 295      | 13.02%  |
| 21      | 262      | 11.57%  |
| 31      | 132      | 5.83%   |
| 19      | 123      | 5.43%   |
| Unknown | 119      | 5.25%   |
| 34      | 70       | 3.09%   |
| 22      | 67       | 2.96%   |
| 18      | 61       | 2.69%   |
| 17      | 61       | 2.69%   |
| 20      | 53       | 2.34%   |
| 84      | 38       | 1.68%   |
| 72      | 32       | 1.41%   |
| 40      | 28       | 1.24%   |
| 54      | 23       | 1.02%   |
| 15      | 23       | 1.02%   |
| 32      | 19       | 0.84%   |
| 28      | 17       | 0.75%   |
| 26      | 16       | 0.71%   |
| 142     | 14       | 0.62%   |
| 48      | 14       | 0.62%   |
| 25      | 13       | 0.57%   |
| 52      | 10       | 0.44%   |
| 46      | 10       | 0.44%   |
| 29      | 8        | 0.35%   |
| 12      | 7        | 0.31%   |
| 49      | 5        | 0.22%   |
| 65      | 4        | 0.18%   |
| 43      | 4        | 0.18%   |
| 33      | 4        | 0.18%   |
| 16      | 4        | 0.18%   |
| 13      | 4        | 0.18%   |
| 42      | 3        | 0.13%   |
| 39      | 3        | 0.13%   |
| 37      | 3        | 0.13%   |
| 36      | 3        | 0.13%   |
| 14      | 3        | 0.13%   |
| 75      | 2        | 0.09%   |
| 61      | 2        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 906      | 41.39%  |
| 401-500        | 494      | 22.57%  |
| 601-700        | 195      | 8.91%   |
| Unknown        | 119      | 5.44%   |
| 701-800        | 96       | 4.39%   |
| 301-350        | 79       | 3.61%   |
| 1001-1500      | 78       | 3.56%   |
| 351-400        | 77       | 3.52%   |
| 1501-2000      | 74       | 3.38%   |
| 801-900        | 33       | 1.51%   |
| More than 2000 | 14       | 0.64%   |
| 201-300        | 13       | 0.59%   |
| 901-1000       | 11       | 0.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1458     | 70.57%  |
| 16/10   | 238      | 11.52%  |
| 5/4     | 114      | 5.52%   |
| Unknown | 91       | 4.4%    |
| 21/9    | 87       | 4.21%   |
| 4/3     | 32       | 1.55%   |
| 32/9    | 15       | 0.73%   |
| 1.00    | 15       | 0.73%   |
| 6/5     | 8        | 0.39%   |
| 3/2     | 8        | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 734      | 33.06%  |
| 301-350        | 381      | 17.16%  |
| 151-200        | 254      | 11.44%  |
| 351-500        | 244      | 10.99%  |
| More than 1000 | 137      | 6.17%   |
| 251-300        | 130      | 5.86%   |
| Unknown        | 119      | 5.36%   |
| 141-150        | 104      | 4.68%   |
| 501-1000       | 72       | 3.24%   |
| 101-110        | 21       | 0.95%   |
| 71-80          | 9        | 0.41%   |
| 81-90          | 4        | 0.18%   |
| 131-140        | 4        | 0.18%   |
| 111-120        | 3        | 0.14%   |
| 91-100         | 2        | 0.09%   |
| 51-60          | 1        | 0.05%   |
| 121-130        | 1        | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1312     | 62.12%  |
| 101-120       | 431      | 20.41%  |
| Unknown       | 119      | 5.63%   |
| 1-50          | 102      | 4.83%   |
| 121-160       | 102      | 4.83%   |
| 161-240       | 45       | 2.13%   |
| More than 240 | 1        | 0.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1611     | 73.93%  |
| 2     | 360      | 16.52%  |
| 0     | 147      | 6.75%   |
| 3     | 51       | 2.34%   |
| 4     | 8        | 0.37%   |
| 5     | 2        | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 1412     | 45.84%  |
| Intel                           | 945      | 30.68%  |
| Qualcomm Atheros                | 136      | 4.42%   |
| MediaTek                        | 110      | 3.57%   |
| Broadcom                        | 72       | 2.34%   |
| Ralink Technology               | 60       | 1.95%   |
| TP-Link                         | 58       | 1.88%   |
| Nvidia                          | 24       | 0.78%   |
| Ralink                          | 17       | 0.55%   |
| Microsoft                       | 17       | 0.55%   |
| Aquantia                        | 17       | 0.55%   |
| NetGear                         | 15       | 0.49%   |
| Marvell Technology Group        | 15       | 0.49%   |
| Qualcomm Atheros Communications | 12       | 0.39%   |
| Broadcom Limited                | 12       | 0.39%   |
| D-Link System                   | 11       | 0.36%   |
| D-Link                          | 11       | 0.36%   |
| ASUSTek Computer                | 10       | 0.32%   |
| Samsung Electronics             | 9        | 0.29%   |
| ASIX Electronics                | 9        | 0.29%   |
| IMC Networks                    | 7        | 0.23%   |
| Huawei Technologies             | 7        | 0.23%   |
| Xiaomi                          | 6        | 0.19%   |
| QinHeng Electronics             | 6        | 0.19%   |
| DisplayLink                     | 6        | 0.19%   |
| AVM                             | 6        | 0.19%   |
| VIA Technologies                | 5        | 0.16%   |
| Linksys                         | 5        | 0.16%   |
| Belkin Components               | 5        | 0.16%   |
| Motorola PCS                    | 4        | 0.13%   |
| Google                          | 4        | 0.13%   |
| Edimax Technology               | 4        | 0.13%   |
| Microchip Technology            | 3        | 0.1%    |
| Arduino SA                      | 3        | 0.1%    |
| ZTE WCDMA Technologies MSM      | 2        | 0.06%   |
| Wacom                           | 2        | 0.06%   |
| OPPO Electronics                | 2        | 0.06%   |
| InterBiometrics                 | 2        | 0.06%   |
| ICS Advent                      | 2        | 0.06%   |
| BUFFALO                         | 2        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1032     | 28.75%  |
| Realtek RTL8125 2.5GbE Controller                                 | 209      | 5.82%   |
| Intel I211 Gigabit Network Connection                             | 107      | 2.98%   |
| Intel Ethernet Controller I225-V                                  | 100      | 2.79%   |
| Intel Wi-Fi 6 AX200                                               | 96       | 2.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 75       | 2.09%   |
| Intel Ethernet Connection (2) I219-V                              | 70       | 1.95%   |
| Intel Ethernet Connection I217-LM                                 | 66       | 1.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 64       | 1.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 46       | 1.28%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 46       | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 40       | 1.11%   |
| Intel Ethernet Connection (7) I219-V                              | 38       | 1.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 37       | 1.03%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 36       | 1%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 35       | 0.97%   |
| Realtek 802.11ac NIC                                              | 33       | 0.92%   |
| Ralink MT7601U Wireless Adapter                                   | 31       | 0.86%   |
| Intel Ethernet Connection (2) I219-LM                             | 31       | 0.86%   |
| Intel 700 Series Chipset Family Wi-Fi                             | 29       | 0.81%   |
| Intel Ethernet Connection I217-V                                  | 28       | 0.78%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 26       | 0.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 24       | 0.67%   |
| Intel Ethernet Controller I226-V                                  | 24       | 0.67%   |
| Intel Wireless 7265                                               | 22       | 0.61%   |
| Intel I210 Gigabit Network Connection                             | 22       | 0.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 22       | 0.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21       | 0.58%   |
| Intel Wireless-AC 9260                                            | 20       | 0.56%   |
| Intel 82579V Gigabit Network Connection                           | 20       | 0.56%   |
| Intel Ethernet Connection (14) I219-V                             | 19       | 0.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 18       | 0.5%    |
| Nvidia MCP61 Ethernet                                             | 17       | 0.47%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 17       | 0.47%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 16       | 0.45%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 15       | 0.42%   |
| Intel Wireless 7260                                               | 15       | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                             | 15       | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 14       | 0.39%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 13       | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 404      | 35.25%  |
| Realtek Semiconductor                 | 288      | 25.13%  |
| MediaTek                              | 108      | 9.42%   |
| Qualcomm Atheros                      | 73       | 6.37%   |
| Ralink Technology                     | 60       | 5.24%   |
| TP-Link                               | 57       | 4.97%   |
| Broadcom                              | 27       | 2.36%   |
| Ralink                                | 17       | 1.48%   |
| Microsoft                             | 17       | 1.48%   |
| NetGear                               | 15       | 1.31%   |
| Qualcomm Atheros Communications       | 12       | 1.05%   |
| D-Link                                | 10       | 0.87%   |
| ASUSTek Computer                      | 10       | 0.87%   |
| IMC Networks                          | 7        | 0.61%   |
| D-Link System                         | 7        | 0.61%   |
| AVM                                   | 6        | 0.52%   |
| Linksys                               | 5        | 0.44%   |
| Belkin Components                     | 5        | 0.44%   |
| Edimax Technology                     | 4        | 0.35%   |
| Broadcom Limited                      | 4        | 0.35%   |
| Wacom                                 | 2        | 0.17%   |
| BUFFALO                               | 2        | 0.17%   |
| ZyDAS                                 | 1        | 0.09%   |
| Xiaomi                                | 1        | 0.09%   |
| Tenda                                 | 1        | 0.09%   |
| Sitecom Europe                        | 1        | 0.09%   |
| Mercucys                              | 1        | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 96       | 8.31%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 64       | 5.54%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 46       | 3.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 40       | 3.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 37       | 3.2%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 36       | 3.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 35       | 3.03%   |
| Realtek 802.11ac NIC                                           | 33       | 2.86%   |
| Ralink MT7601U Wireless Adapter                                | 31       | 2.68%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 29       | 2.51%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 26       | 2.25%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 24       | 2.08%   |
| Intel Wireless 7265                                            | 22       | 1.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 22       | 1.9%    |
| Intel Wireless-AC 9260                                         | 20       | 1.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 18       | 1.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 17       | 1.47%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 15       | 1.3%    |
| Intel Wireless 7260                                            | 15       | 1.3%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 13       | 1.13%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 12       | 1.04%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 11       | 0.95%   |
| Qualcomm Atheros AR9271 802.11n                                | 11       | 0.95%   |
| Intel Wireless 8260                                            | 11       | 0.95%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 11       | 0.95%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 10       | 0.87%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 9        | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9        | 0.78%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 9        | 0.78%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 9        | 0.78%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 9        | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9        | 0.78%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 8        | 0.69%   |
| Ralink RT5370 Wireless Adapter                                 | 8        | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 8        | 0.69%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 8        | 0.69%   |
| Intel Wireless 8265 / 8275                                     | 8        | 0.69%   |
| Intel Wireless 3165                                            | 8        | 0.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 7        | 0.61%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 7        | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1316     | 56.53%  |
| Intel                             | 751      | 32.26%  |
| Qualcomm Atheros                  | 72       | 3.09%   |
| Broadcom                          | 46       | 1.98%   |
| Nvidia                            | 24       | 1.03%   |
| Aquantia                          | 17       | 0.73%   |
| Marvell Technology Group          | 15       | 0.64%   |
| Samsung Electronics               | 9        | 0.39%   |
| ASIX Electronics                  | 9        | 0.39%   |
| Broadcom Limited                  | 8        | 0.34%   |
| Huawei Technologies               | 6        | 0.26%   |
| DisplayLink                       | 6        | 0.26%   |
| Xiaomi                            | 5        | 0.21%   |
| VIA Technologies                  | 5        | 0.21%   |
| Google                            | 4        | 0.17%   |
| D-Link System                     | 4        | 0.17%   |
| Motorola PCS                      | 3        | 0.13%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.09%   |
| OPPO Electronics                  | 2        | 0.09%   |
| MediaTek                          | 2        | 0.09%   |
| ICS Advent                        | 2        | 0.09%   |
| Vimtron Electronics               | 1        | 0.04%   |
| TP-Link                           | 1        | 0.04%   |
| Tehuti Networks                   | 1        | 0.04%   |
| Sundance Technology Inc / IC Plus | 1        | 0.04%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.04%   |
| Qualcomm                          | 1        | 0.04%   |
| Novatel Wireless                  | 1        | 0.04%   |
| NetXen Incorporated               | 1        | 0.04%   |
| Mellanox Technologies             | 1        | 0.04%   |
| Lenovo                            | 1        | 0.04%   |
| JMicron Technology                | 1        | 0.04%   |
| HMD Global                        | 1        | 0.04%   |
| Hewlett-Packard                   | 1        | 0.04%   |
| Emulex                            | 1        | 0.04%   |
| D-Link                            | 1        | 0.04%   |
| Compal Electronics                | 1        | 0.04%   |
| American Megatrends               | 1        | 0.04%   |
| ADMtek                            | 1        | 0.04%   |
| Accton Technology                 | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1032     | 42.7%   |
| Realtek RTL8125 2.5GbE Controller                                 | 209      | 8.65%   |
| Intel I211 Gigabit Network Connection                             | 107      | 4.43%   |
| Intel Ethernet Controller I225-V                                  | 100      | 4.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 75       | 3.1%    |
| Intel Ethernet Connection (2) I219-V                              | 70       | 2.9%    |
| Intel Ethernet Connection I217-LM                                 | 66       | 2.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 46       | 1.9%    |
| Intel Ethernet Connection (7) I219-V                              | 38       | 1.57%   |
| Intel Ethernet Connection (2) I219-LM                             | 31       | 1.28%   |
| Intel Ethernet Connection I217-V                                  | 28       | 1.16%   |
| Intel Ethernet Controller I226-V                                  | 24       | 0.99%   |
| Intel I210 Gigabit Network Connection                             | 22       | 0.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21       | 0.87%   |
| Intel 82579V Gigabit Network Connection                           | 20       | 0.83%   |
| Intel Ethernet Connection (14) I219-V                             | 19       | 0.79%   |
| Nvidia MCP61 Ethernet                                             | 17       | 0.7%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 16       | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                             | 15       | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 14       | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 13       | 0.54%   |
| Intel I350 Gigabit Network Connection                             | 13       | 0.54%   |
| Intel Ethernet Connection (5) I219-LM                             | 13       | 0.54%   |
| Intel Ethernet Connection (2) I218-V                              | 12       | 0.5%    |
| Intel 82574L Gigabit Network Connection                           | 12       | 0.5%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 12       | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 10       | 0.41%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 9        | 0.37%   |
| Intel Ethernet Connection (17) I219-V                             | 9        | 0.37%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 9        | 0.37%   |
| Realtek Killer E3000 2.5GbE Controller                            | 8        | 0.33%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8        | 0.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7        | 0.29%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7        | 0.29%   |
| Intel Ethernet Controller X550                                    | 7        | 0.29%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 7        | 0.29%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 6        | 0.25%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6        | 0.25%   |
| Intel Ethernet Connection (2) I218-LM                             | 6        | 0.25%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5        | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2158     | 66.38%  |
| WiFi     | 1076     | 33.1%   |
| Modem    | 16       | 0.49%   |
| Unknown  | 1        | 0.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1670     | 74.32%  |
| WiFi     | 577      | 25.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1282     | 58.83%  |
| 2     | 754      | 34.6%   |
| 3     | 96       | 4.41%   |
| 4     | 21       | 0.96%   |
| 0     | 14       | 0.64%   |
| 5     | 6        | 0.28%   |
| 6     | 4        | 0.18%   |
| 11    | 1        | 0.05%   |
| 7     | 1        | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1493     | 68.52%  |
| Yes  | 686      | 31.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 382      | 42.87%  |
| Cambridge Silicon Radio         | 156      | 17.51%  |
| Realtek Semiconductor           | 98       | 11%     |
| MediaTek                        | 75       | 8.42%   |
| ASUSTek Computer                | 36       | 4.04%   |
| Broadcom                        | 33       | 3.7%    |
| IMC Networks                    | 26       | 2.92%   |
| TP-Link                         | 22       | 2.47%   |
| Qualcomm Atheros Communications | 16       | 1.8%    |
| Foxconn / Hon Hai               | 9        | 1.01%   |
| Realtek                         | 7        | 0.79%   |
| Apple                           | 5        | 0.56%   |
| Lite-On Technology              | 4        | 0.45%   |
| Edimax Technology               | 4        | 0.45%   |
| Belkin Components               | 3        | 0.34%   |
| Logitech                        | 2        | 0.22%   |
| Integrated System Solution      | 2        | 0.22%   |
| Dynex                           | 2        | 0.22%   |
| Actions                         | 2        | 0.22%   |
| Unknown                         | 2        | 0.22%   |
| Mobile Action Technology        | 1        | 0.11%   |
| Kensington                      | 1        | 0.11%   |
| HTC (High Tech Computer)        | 1        | 0.11%   |
| Conwise Technology              | 1        | 0.11%   |
| AboCom Systems                  | 1        | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 156      | 17.49%  |
| Intel AX200 Bluetooth                                    | 92       | 10.31%  |
| Realtek Bluetooth Radio                                  | 80       | 8.97%   |
| MediaTek Wireless_Device                                 | 75       | 8.41%   |
| Intel AX210 Bluetooth                                    | 61       | 6.84%   |
| Intel Bluetooth wireless interface                       | 59       | 6.61%   |
| Intel Wireless-AC 3168 Bluetooth                         | 40       | 4.48%   |
| Intel Bluetooth Device                                   | 39       | 4.37%   |
| Intel AX201 Bluetooth                                    | 38       | 4.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 29       | 3.25%   |
| TP-Link UB500 Adapter                                    | 22       | 2.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 19       | 2.13%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 17       | 1.91%   |
| Realtek  Bluetooth 4.2 Adapter                           | 14       | 1.57%   |
| IMC Networks Wireless_Device                             | 14       | 1.57%   |
| IMC Networks Bluetooth Radio                             | 11       | 1.23%   |
| ASUS ASUS USB-BT500                                      | 10       | 1.12%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 8        | 0.9%    |
| ASUS Bluetooth Radio                                     | 8        | 0.9%    |
| Realtek Bluetooth Radio                                  | 7        | 0.78%   |
| Qualcomm Atheros  Bluetooth Device                       | 7        | 0.78%   |
| Foxconn / Hon Hai Wireless_Device                        | 7        | 0.78%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 6        | 0.67%   |
| ASUS BCM20702A0                                          | 5        | 0.56%   |
| Edimax Bluetooth Adapter                                 | 4        | 0.45%   |
| Broadcom BCM2045 Bluetooth                               | 4        | 0.45%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 3        | 0.34%   |
| ASUS Qualcomm Bluetooth 4.1                              | 3        | 0.34%   |
| Realtek RTL8821A Bluetooth                               | 2        | 0.22%   |
| Realtek RTL8723B Bluetooth                               | 2        | 0.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 2        | 0.22%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 2        | 0.22%   |
| Logitech BT Mini-Receiver (HCI mode)                     | 2        | 0.22%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 2        | 0.22%   |
| Integrated System Solution Bluetooth Device              | 2        | 0.22%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth              | 2        | 0.22%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 2        | 0.22%   |
| Broadcom Bluetooth 3.0 Device                            | 2        | 0.22%   |
| Belkin Components Bluetooth Mini Dongle                  | 2        | 0.22%   |
| ASUS Bluetooth Adapter                                   | 2        | 0.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 1263     | 33.76%  |
| AMD                                             | 1014     | 27.11%  |
| Nvidia                                          | 816      | 21.81%  |
| C-Media Electronics                             | 97       | 2.59%   |
| Logitech                                        | 48       | 1.28%   |
| Creative Labs                                   | 45       | 1.2%    |
| ASUSTek Computer                                | 37       | 0.99%   |
| Texas Instruments                               | 30       | 0.8%    |
| Micro Star International                        | 28       | 0.75%   |
| JMTek                                           | 22       | 0.59%   |
| GN Netcom                                       | 19       | 0.51%   |
| SteelSeries ApS                                 | 18       | 0.48%   |
| Kingston Technology                             | 18       | 0.48%   |
| Razer USA                                       | 16       | 0.43%   |
| Focusrite-Novation                              | 15       | 0.4%    |
| Generalplus Technology                          | 14       | 0.37%   |
| Blue Microphones                                | 14       | 0.37%   |
| Creative Technology                             | 12       | 0.32%   |
| Jieli Technology                                | 10       | 0.27%   |
| Corsair                                         | 9        | 0.24%   |
| VIA Technologies                                | 7        | 0.19%   |
| Plantronics                                     | 6        | 0.16%   |
| Hewlett-Packard                                 | 6        | 0.16%   |
| Dell                                            | 6        | 0.16%   |
| Tenx Technology                                 | 5        | 0.13%   |
| Sennheiser Communications                       | 5        | 0.13%   |
| RODE Microphones                                | 5        | 0.13%   |
| Zoran Co. Personal Media Division (Nogatech)    | 4        | 0.11%   |
| Thesycon Systemsoftware & Consulting            | 4        | 0.11%   |
| Sony                                            | 4        | 0.11%   |
| Realtek Semiconductor                           | 4        | 0.11%   |
| Native Instruments                              | 4        | 0.11%   |
| M-Audio                                         | 4        | 0.11%   |
| Giga-Byte Technology                            | 4        | 0.11%   |
| BEHRINGER International                         | 4        | 0.11%   |
| Astro Gaming                                    | 4        | 0.11%   |
| XMOS                                            | 3        | 0.08%   |
| Samson Technologies                             | 3        | 0.08%   |
| ROCCAT                                          | 3        | 0.08%   |
| Licensed by Sony Computer Entertainment America | 3        | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 254      | 5.68%   |
| AMD Family 17h/19h HD Audio Controller                                     | 226      | 5.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 185      | 4.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 128      | 2.86%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 128      | 2.86%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 127      | 2.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 115      | 2.57%   |
| Intel 200 Series PCH HD Audio                                              | 106      | 2.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 105      | 2.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 104      | 2.33%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 103      | 2.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 100      | 2.24%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 88       | 1.97%   |
| Intel Cannon Lake PCH cAVS                                                 | 74       | 1.65%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 72       | 1.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 69       | 1.54%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 67       | 1.5%    |
| Intel Alder Lake-S HD Audio Controller                                     | 66       | 1.48%   |
| AMD FCH Azalia Controller                                                  | 60       | 1.34%   |
| Nvidia GP107GL High Definition Audio Controller                            | 59       | 1.32%   |
| Nvidia TU116 High Definition Audio Controller                              | 55       | 1.23%   |
| Nvidia GA104 High Definition Audio Controller                              | 54       | 1.21%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 51       | 1.14%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 51       | 1.14%   |
| Nvidia GP104 High Definition Audio Controller                              | 46       | 1.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 46       | 1.03%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 43       | 0.96%   |
| Nvidia GA106 High Definition Audio Controller                              | 42       | 0.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 40       | 0.89%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 37       | 0.83%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 37       | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 36       | 0.8%    |
| Intel Smart Sound Technology (SST) Audio Controller                        | 35       | 0.78%   |
| Nvidia High Definition Audio Controller                                    | 33       | 0.74%   |
| Nvidia GP108 High Definition Audio Controller                              | 33       | 0.74%   |
| Nvidia GA102 High Definition Audio Controller                              | 32       | 0.72%   |
| Nvidia Audio device                                                        | 32       | 0.72%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 32       | 0.72%   |
| ASUSTek Computer USB Audio                                                 | 32       | 0.72%   |
| AMD Navi 10 HDMI Audio                                                     | 31       | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Kingston                                | 268      | 18.86%  |
| Unknown                                 | 187      | 13.16%  |
| Corsair                                 | 173      | 12.17%  |
| Samsung Electronics                     | 154      | 10.84%  |
| Crucial                                 | 121      | 8.52%   |
| G.Skill                                 | 103      | 7.25%   |
| SK hynix                                | 84       | 5.91%   |
| Micron Technology                       | 65       | 4.57%   |
| Unknown                                 | 36       | 2.53%   |
| A-DATA Technology                       | 32       | 2.25%   |
| Team                                    | 22       | 1.55%   |
| Patriot                                 | 17       | 1.2%    |
| Nanya Technology                        | 13       | 0.91%   |
| AMD                                     | 13       | 0.91%   |
| Unknown (ABCD)                          | 10       | 0.7%    |
| Ramaxel Technology                      | 10       | 0.7%    |
| Transcend                               | 8        | 0.56%   |
| Kingmax                                 | 8        | 0.56%   |
| Apacer                                  | 8        | 0.56%   |
| Elpida                                  | 7        | 0.49%   |
| Silicon Power                           | 5        | 0.35%   |
| Silicon Power Computer & Communications | 4        | 0.28%   |
| GOODRAM                                 | 4        | 0.28%   |
| Unknown (0x7FFF)                        | 3        | 0.21%   |
| Smart                                   | 3        | 0.21%   |
| PNY                                     | 3        | 0.21%   |
| Hewlett-Packard                         | 3        | 0.21%   |
| Wodposit                                | 2        | 0.14%   |
| Unknown (0x1636)                        | 2        | 0.14%   |
| Unknown (0x0E9D)                        | 2        | 0.14%   |
| Unknown (09D5)                          | 2        | 0.14%   |
| Timetec                                 | 2        | 0.14%   |
| Sesame                                  | 2        | 0.14%   |
| Qimonda                                 | 2        | 0.14%   |
| Neo Forza                               | 2        | 0.14%   |
| Lexar Co Limited                        | 2        | 0.14%   |
| Lexar                                   | 2        | 0.14%   |
| Kllisre                                 | 2        | 0.14%   |
| KingSpec                                | 2        | 0.14%   |
| CSX                                     | 2        | 0.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown                                                        | 36       | 2.35%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 22       | 1.43%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 13       | 0.85%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 12       | 0.78%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 10       | 0.65%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s            | 10       | 0.65%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 9        | 0.59%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 9        | 0.59%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 9        | 0.59%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 8        | 0.52%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 8        | 0.52%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 7        | 0.46%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s         | 7        | 0.46%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s           | 7        | 0.46%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s            | 7        | 0.46%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 6        | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 6        | 0.39%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 6        | 0.39%   |
| Micron RAM 36ASF4G72PZ-2G3B1 32GB DIMM DDR4 2400MT/s           | 6        | 0.39%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 6        | 0.39%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 3600MT/s          | 6        | 0.39%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s             | 6        | 0.39%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 6        | 0.39%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s          | 6        | 0.39%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                    | 6        | 0.39%   |
| Team RAM TEAMGROUP-UD4-3200 8192MB DIMM DDR4 3733MT/s          | 5        | 0.33%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s            | 5        | 0.33%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s             | 5        | 0.33%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 5        | 0.33%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 5        | 0.33%   |
| Kingston RAM KF556C40-32 32GB DIMM DDR5 5808MT/s               | 5        | 0.33%   |
| G.Skill RAM F5-6000J3040G32G 32GB DIMM DDR5 6000MT/s           | 5        | 0.33%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s           | 5        | 0.33%   |
| Crucial RAM CT16G56C46S5.M8G1 16GB SODIMM DDR5 5600MT/s        | 5        | 0.33%   |
| Crucial RAM CT102464BD160B.M16 8GB DIMM DDR3 1600MT/s          | 5        | 0.33%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s         | 5        | 0.33%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s         | 5        | 0.33%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                    | 4        | 0.26%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                       | 4        | 0.26%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                   | 4        | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 612      | 49.55%  |
| DDR3    | 338      | 27.37%  |
| DDR5    | 89       | 7.21%   |
| Unknown | 70       | 5.67%   |
| DDR2    | 53       | 4.29%   |
| SDRAM   | 41       | 3.32%   |
| DDR     | 16       | 1.3%    |
| LPDDR4  | 12       | 0.97%   |
| DRAM    | 3        | 0.24%   |
| LPDDR5  | 1        | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1104     | 90.64%  |
| SODIMM       | 106      | 8.7%    |
| Row Of Chips | 3        | 0.25%   |
| RIMM         | 3        | 0.25%   |
| FB-DIMM      | 1        | 0.08%   |
| Unknown      | 1        | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 482      | 35.86%  |
| 4096  | 269      | 20.01%  |
| 16384 | 264      | 19.64%  |
| 2048  | 151      | 11.24%  |
| 32768 | 113      | 8.41%   |
| 1024  | 47       | 3.5%    |
| 512   | 11       | 0.82%   |
| 49152 | 3        | 0.22%   |
| 256   | 2        | 0.15%   |
| 65536 | 1        | 0.07%   |
| 6144  | 1        | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 205      | 14.94%  |
| 3200    | 173      | 12.61%  |
| 1333    | 142      | 10.35%  |
| 3600    | 108      | 7.87%   |
| 2400    | 94       | 6.85%   |
| 2667    | 92       | 6.71%   |
| 2133    | 73       | 5.32%   |
| 800     | 37       | 2.7%    |
| 667     | 34       | 2.48%   |
| 4800    | 33       | 2.41%   |
| Unknown | 26       | 1.9%    |
| 2666    | 23       | 1.68%   |
| 3733    | 22       | 1.6%    |
| 1867    | 22       | 1.6%    |
| 1866    | 21       | 1.53%   |
| 6000    | 17       | 1.24%   |
| 3000    | 17       | 1.24%   |
| 5600    | 15       | 1.09%   |
| 3800    | 15       | 1.09%   |
| 2933    | 13       | 0.95%   |
| 1800    | 13       | 0.95%   |
| 1066    | 12       | 0.87%   |
| 3400    | 11       | 0.8%    |
| 3266    | 11       | 0.8%    |
| 400     | 11       | 0.8%    |
| 3666    | 10       | 0.73%   |
| 3533    | 10       | 0.73%   |
| 5200    | 9        | 0.66%   |
| 3466    | 8        | 0.58%   |
| 533     | 7        | 0.51%   |
| 6400    | 6        | 0.44%   |
| 4000    | 6        | 0.44%   |
| 5808    | 5        | 0.36%   |
| 3866    | 5        | 0.36%   |
| 3534    | 5        | 0.36%   |
| 2800    | 5        | 0.36%   |
| 2733    | 5        | 0.36%   |
| 1067    | 5        | 0.36%   |
| 2134    | 4        | 0.29%   |
| 3334    | 3        | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)

![Printer Vendor](./images/line_chart/printer_vendor.svg)

| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 33       | 30.56%  |
| Brother Industries    | 21       | 19.44%  |
| Canon                 | 16       | 14.81%  |
| Seiko Epson           | 15       | 13.89%  |
| Samsung Electronics   | 6        | 5.56%   |
| Dymo-CoStar           | 5        | 4.63%   |
| Xerox                 | 2        | 1.85%   |
| Prolific Technology   | 2        | 1.85%   |
| Pantum                | 2        | 1.85%   |
| Zebra                 | 1        | 0.93%   |
| XiaoMi                | 1        | 0.93%   |
| QinHeng Electronics   | 1        | 0.93%   |
| nemonic               | 1        | 0.93%   |
| Lexmark International | 1        | 0.93%   |
| GG IMAGE              | 1        | 0.93%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)

![Printer Model](./images/line_chart/printer_model.svg)

| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seiko Epson ET-2710 Series           | 3        | 2.75%   |
| HP LaserJet P1102                    | 3        | 2.75%   |
| Brother Printer                      | 3        | 2.75%   |
| Prolific PL2305 Parallel Port        | 2        | 1.83%   |
| HP OfficeJet 6950                    | 2        | 1.83%   |
| HP LaserJet P1005                    | 2        | 1.83%   |
| HP LaserJet M14-M17                  | 2        | 1.83%   |
| HP LaserJet 1320                     | 2        | 1.83%   |
| HP LaserJet 1018                     | 2        | 1.83%   |
| HP DeskJet 4100 series               | 2        | 1.83%   |
| HP DeskJet 2600 series               | 2        | 1.83%   |
| Brother HL-L2350DW series            | 2        | 1.83%   |
| Zebra Printer                        | 1        | 0.92%   |
| XiaoMi MIIIW MECH-KBPro              | 1        | 0.92%   |
| Xerox Phaser 6500N                   | 1        | 0.92%   |
| Xerox Phaser 3010                    | 1        | 0.92%   |
| Seiko Epson XP-4100 Series           | 1        | 0.92%   |
| Seiko Epson XP-3100 Series           | 1        | 0.92%   |
| Seiko Epson XP-2100 Series           | 1        | 0.92%   |
| Seiko Epson WF-2870 Series           | 1        | 0.92%   |
| Seiko Epson L6160 Series             | 1        | 0.92%   |
| Seiko Epson L300 Series              | 1        | 0.92%   |
| Seiko Epson L132 Series              | 1        | 0.92%   |
| Seiko Epson ET-3760 Series           | 1        | 0.92%   |
| Seiko Epson ET-2820 Series           | 1        | 0.92%   |
| Seiko Epson ET-2600 Series           | 1        | 0.92%   |
| Seiko Epson ET-1810 Series           | 1        | 0.92%   |
| Seiko Epson AL-M310DN                | 1        | 0.92%   |
| Samsung ML-2510 Series               | 1        | 0.92%   |
| Samsung ML-2250 Series               | 1        | 0.92%   |
| Samsung ML-1865                      | 1        | 0.92%   |
| Samsung ML-1640 Series Laser Printer | 1        | 0.92%   |
| Samsung M2070 Series                 | 1        | 0.92%   |
| Samsung Composite Device             | 1        | 0.92%   |
| QinHeng CH340S                       | 1        | 0.92%   |
| Pantum P2200W series                 | 1        | 0.92%   |
| Pantum P2200-series                  | 1        | 0.92%   |
| nemonic MIP-001                      | 1        | 0.92%   |
| Lexmark International MC2425adw      | 1        | 0.92%   |
| HP Officejet J4680                   | 1        | 0.92%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)

![Scanner Vendor](./images/line_chart/scanner_vendor.svg)

| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 20       | 62.5%   |
| Seiko Epson     | 7        | 21.88%  |
| Plustek         | 2        | 6.25%   |
| Hewlett-Packard | 2        | 6.25%   |
| Mustek Systems  | 1        | 3.13%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)

![Scanner Model](./images/line_chart/scanner_model.svg)

| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 220                                 | 4        | 12.5%   |
| Canon CanoScan LiDE 210                                 | 4        | 12.5%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 3        | 9.38%   |
| Canon CanoScan LiDE 110                                 | 3        | 9.38%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 2        | 6.25%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1        | 3.13%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 3.13%   |
| Seiko Epson GT-F700 [Perfection V350]                   | 1        | 3.13%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]           | 1        | 3.13%   |
| Plustek USB Scanner                                     | 1        | 3.13%   |
| Plustek 1200dpi USB Scanner                             | 1        | 3.13%   |
| Mustek Systems BearPaw 2448 TA Plus                     | 1        | 3.13%   |
| HP ScanJet G4050                                        | 1        | 3.13%   |
| HP Scanjet G2710                                        | 1        | 3.13%   |
| Canon CanoScan N650U/N656U                              | 1        | 3.13%   |
| Canon CanoScan LiDE 90                                  | 1        | 3.13%   |
| Canon CanoScan LiDE 700F                                | 1        | 3.13%   |
| Canon CanoScan LiDE 70                                  | 1        | 3.13%   |
| Canon CanoScan LiDE 500F                                | 1        | 3.13%   |
| Canon CanoScan LIDE 25                                  | 1        | 3.13%   |
| Canon CanoScan 8800F                                    | 1        | 3.13%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)

![Camera Vendor](./images/line_chart/camera_vendor.svg)

| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 159      | 38.69%  |
| Microdia                      | 37       | 9%      |
| Microsoft                     | 25       | 6.08%   |
| Sunplus Innovation Technology | 23       | 5.6%    |
| Generalplus Technology        | 16       | 3.89%   |
| Samsung Electronics           | 13       | 3.16%   |
| Z-Star Microelectronics       | 11       | 2.68%   |
| KYE Systems (Mouse Systems)   | 9        | 2.19%   |
| HD 2MP WEBCAM                 | 9        | 2.19%   |
| Chicony Electronics           | 9        | 2.19%   |
| Apple                         | 8        | 1.95%   |
| Realtek Semiconductor         | 7        | 1.7%    |
| Jieli Technology              | 7        | 1.7%    |
| Trust                         | 6        | 1.46%   |
| ARC International             | 6        | 1.46%   |
| MacroSilicon                  | 5        | 1.22%   |
| Creative Technology           | 5        | 1.22%   |
| WaveRider Communications      | 4        | 0.97%   |
| Cubeternet                    | 4        | 0.97%   |
| lihappe8                      | 3        | 0.73%   |
| Hewlett-Packard               | 3        | 0.73%   |
| GEMBIRD                       | 3        | 0.73%   |
| eMeet                         | 3        | 0.73%   |
| AVerMedia Technologies        | 3        | 0.73%   |
| Unknown                       | 2        | 0.49%   |
| SunplusIT                     | 2        | 0.49%   |
| Razer USA                     | 2        | 0.49%   |
| Lenovo                        | 2        | 0.49%   |
| GenesysLogic Technology       | 2        | 0.49%   |
| Arkmicro Technologies         | 2        | 0.49%   |
| YGTek                         | 1        | 0.24%   |
| ValueHD                       | 1        | 0.24%   |
| Sweex                         | 1        | 0.24%   |
| Suyin                         | 1        | 0.24%   |
| SN0002                        | 1        | 0.24%   |
| SHENZHEN AONI ELECTRONIC      | 1        | 0.24%   |
| Ricoh                         | 1        | 0.24%   |
| Owl Labs                      | 1        | 0.24%   |
| OmniVision Technologies       | 1        | 0.24%   |
| LG Electronics                | 1        | 0.24%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C270                       | 34       | 8.23%   |
| Logitech HD Pro Webcam C920                | 22       | 5.33%   |
| Logitech C922 Pro Stream Webcam            | 18       | 4.36%   |
| Samsung Galaxy series, misc. (MTP mode)    | 13       | 3.15%   |
| Microsoft LifeCam HD-3000                  | 11       | 2.66%   |
| Logitech Webcam C310                       | 10       | 2.42%   |
| HD 2MP WEBCAM HD 2MP WEBCAM                | 9        | 2.18%   |
| Generalplus GENERAL WEBCAM                 | 9        | 2.18%   |
| Microdia USB 2.0 Camera                    | 8        | 1.94%   |
| Logitech HD Webcam C615                    | 8        | 1.94%   |
| Logitech C920 PRO HD Webcam                | 8        | 1.94%   |
| Logitech BRIO Ultra HD Webcam              | 8        | 1.94%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X            | 8        | 1.94%   |
| Sunplus Full HD webcam                     | 7        | 1.69%   |
| Microdia Webcam Vitade AF                  | 7        | 1.69%   |
| Microdia Camera                            | 7        | 1.69%   |
| Jieli USB PHY 2.0                          | 7        | 1.69%   |
| ARC International Camera                   | 6        | 1.45%   |
| Z-Star Venus USB2.0 Camera                 | 5        | 1.21%   |
| Microdia Sonix USB 2.0 Camera              | 5        | 1.21%   |
| Logitech Webcam C930e                      | 5        | 1.21%   |
| Logitech HD Webcam C525                    | 5        | 1.21%   |
| Generalplus WEB CAM                        | 5        | 1.21%   |
| WaveRider USB Live camera                  | 4        | 0.97%   |
| Sunplus MTD Camera                         | 4        | 0.97%   |
| Microdia Integrated Camera                 | 4        | 0.97%   |
| MacroSilicon USB Video                     | 4        | 0.97%   |
| Logitech Webcam C170                       | 4        | 0.97%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 4        | 0.97%   |
| Z-Star A4 TECH USB2.0 PC Camera E          | 3        | 0.73%   |
| Microsoft LifeCam Studio                   | 3        | 0.73%   |
| Microsoft LifeCam Cinema                   | 3        | 0.73%   |
| Logitech Webcam C925e                      | 3        | 0.73%   |
| Logitech StreamCam                         | 3        | 0.73%   |
| Logitech Logitech Webcam C160              | 3        | 0.73%   |
| Logitech HD Webcam C910                    | 3        | 0.73%   |
| lihappe8 USB 2.0 Camera                    | 3        | 0.73%   |
| GEMBIRD USB2.0 PC CAMERA                   | 3        | 0.73%   |
| Chicony HP 720p HD Monitor Webcam          | 3        | 0.73%   |
| Unknown HD camera                          | 2        | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 2        | 40%     |
| Focal-systems.Corp    | 1        | 20%     |
| Elan Microelectronics | 1        | 20%     |
| DigitalPersona        | 1        | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| LighTuning Fingerprint Sensor               | 2        | 40%     |
| Focal-systems.Corp FT9201Fingerprint.       | 1        | 20%     |
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 20%     |
| DigitalPersona Fingerprint Reader           | 1        | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./images/line_chart/chipcard_vendor.svg)

| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Alcor Micro                       | 3        | 18.75%  |
| Realtek Semiconductor             | 2        | 12.5%   |
| Gemalto (was Gemplus)             | 2        | 12.5%   |
| Chicony Electronics               | 2        | 12.5%   |
| VASCO Data Security International | 1        | 6.25%   |
| SCM Microsystems                  | 1        | 6.25%   |
| Reiner SCT Kartensysteme          | 1        | 6.25%   |
| OmniKey                           | 1        | 6.25%   |
| Bit4id                            | 1        | 6.25%   |
| Aladdin Knowledge Systems         | 1        | 6.25%   |
| Advanced Card Systems             | 1        | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)

![Chipcard Model](./images/line_chart/chipcard_model.svg)

| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                        | 3        | 18.75%  |
| Realtek Semiconductor Smart Card Reader Interface                          | 2        | 12.5%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 2        | 12.5%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 2        | 12.5%   |
| VASCO Data Security International Digipass 905 SmartCard Reader            | 1        | 6.25%   |
| SCM Microsystems SCR333 SmartCard Reader                                   | 1        | 6.25%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 6.25%   |
| OmniKey CardMan 3021 / 3121                                                | 1        | 6.25%   |
| Bit4id miniLector-s                                                        | 1        | 6.25%   |
| Aladdin Knowledge Systems Token JC                                         | 1        | 6.25%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 1        | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1841     | 84.49%  |
| 1     | 270      | 12.39%  |
| 2     | 34       | 1.56%   |
| 4     | 17       | 0.78%   |
| 3     | 11       | 0.5%    |
| 6     | 3        | 0.14%   |
| 5     | 2        | 0.09%   |
| 8     | 1        | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 160      | 37.12%  |
| Net/wireless             | 82       | 19.03%  |
| Unassigned class         | 47       | 10.9%   |
| Communication controller | 45       | 10.44%  |
| Sound                    | 18       | 4.18%   |
| Multimedia controller    | 15       | 3.48%   |
| Net/ethernet             | 13       | 3.02%   |
| Chipcard                 | 8        | 1.86%   |
| Camera                   | 8        | 1.86%   |
| Bluetooth                | 7        | 1.62%   |
| Network                  | 6        | 1.39%   |
| Fingerprint reader       | 5        | 1.16%   |
| Storage/raid             | 4        | 0.93%   |
| Card reader              | 3        | 0.7%    |
| Storage/nvme             | 2        | 0.46%   |
| Storage/ide              | 2        | 0.46%   |
| Firewire controller      | 2        | 0.46%   |
| Video                    | 1        | 0.23%   |
| Unclassified device      | 1        | 0.23%   |
| Tv card                  | 1        | 0.23%   |
| Storage/ata              | 1        | 0.23%   |

