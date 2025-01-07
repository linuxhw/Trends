Gentoo - Hardware Trends
------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Gentoo/Desktop/README.md) and [notebooks](/Dist/Gentoo/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: Dec, 2024.

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

![OS](./All/images/pie_chart/os_name.svg)

![OS](./All/images/line_chart/os_name.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Gentoo 2.17 | 32        | 91.43%  |
| Gentoo 2.15 | 3         | 8.57%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| Gentoo | 35        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 6.6.62-gentoo                 | 5         | 14.29%  |
| 6.12.6-gentoo                 | 4         | 11.43%  |
| 6.6.62-gentoo-x86_64          | 2         | 5.71%   |
| 6.6.62-gentoo-dist            | 2         | 5.71%   |
| 6.12.4-gentoo                 | 2         | 5.71%   |
| 6.12.1-gentoo                 | 2         | 5.71%   |
| 6.9.7-gentoo                  | 1         | 2.86%   |
| 6.6.67-gentoo                 | 1         | 2.86%   |
| 6.6.62-gentoo-gentoo-dist     | 1         | 2.86%   |
| 6.6.52-gentoo-x86_64          | 1         | 2.86%   |
| 6.6.47-gentoo-x86_64          | 1         | 2.86%   |
| 6.6.38-gentoo-mans            | 1         | 2.86%   |
| 6.12.7-tkg-eevdf              | 1         | 2.86%   |
| 6.12.7                        | 1         | 2.86%   |
| 6.12.6-zen1                   | 1         | 2.86%   |
| 6.12.6-stiroy                 | 1         | 2.86%   |
| 6.12.6-gentoo-system76        | 1         | 2.86%   |
| 6.12.4-gentoo-125             | 1         | 2.86%   |
| 6.12.3-gentoo                 | 1         | 2.86%   |
| 6.12.1-gentoo-x86_64          | 1         | 2.86%   |
| 6.12.0-rc7                    | 1         | 2.86%   |
| 6.11.11-gentoo-hpz820-mgreene | 1         | 2.86%   |
| 5.15.174-gentoo-dist          | 1         | 2.86%   |
| 4.9.113-vs2.3.9.7             | 1         | 2.86%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version  | Computers | Percent |
|----------|-----------|---------|
| 6.6.62   | 10        | 28.57%  |
| 6.12.6   | 7         | 20%     |
| 6.12.4   | 3         | 8.57%   |
| 6.12.1   | 3         | 8.57%   |
| 6.12.7   | 2         | 5.71%   |
| 6.9.7    | 1         | 2.86%   |
| 6.6.67   | 1         | 2.86%   |
| 6.6.52   | 1         | 2.86%   |
| 6.6.47   | 1         | 2.86%   |
| 6.6.38   | 1         | 2.86%   |
| 6.12.3   | 1         | 2.86%   |
| 6.12.0   | 1         | 2.86%   |
| 6.11.11  | 1         | 2.86%   |
| 5.15.174 | 1         | 2.86%   |
| 4.9.113  | 1         | 2.86%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.12    | 17        | 48.57%  |
| 6.6     | 14        | 40%     |
| 6.9     | 1         | 2.86%   |
| 6.11    | 1         | 2.86%   |
| 5.15    | 1         | 2.86%   |
| 4.9     | 1         | 2.86%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 34        | 97.14%  |
| aarch64 | 1         | 2.86%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 37.14%  |
| GNOME      | 5         | 14.29%  |
| LXQt       | 4         | 11.43%  |
| KDE6       | 3         | 8.57%   |
| XFCE       | 2         | 5.71%   |
| Xsession   | 1         | 2.86%   |
| X-Cinnamon | 1         | 2.86%   |
| Sway       | 1         | 2.86%   |
| niri       | 1         | 2.86%   |
| MATE       | 1         | 2.86%   |
| KDE5       | 1         | 2.86%   |
| ICEWM      | 1         | 2.86%   |
| Hyprland   | 1         | 2.86%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 13        | 37.14%  |
| Wayland | 13        | 37.14%  |
| Unknown | 6         | 17.14%  |
| Tty     | 3         | 8.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 15        | 42.86%  |
| Unknown | 10        | 28.57%  |
| GDM     | 5         | 14.29%  |
| LightDM | 4         | 11.43%  |
| XDM     | 1         | 2.86%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 16        | 45.71%  |
| en_GB   | 3         | 8.57%   |
| C.UTF8  | 3         | 8.57%   |
| Unknown | 3         | 8.57%   |
| C       | 2         | 5.71%   |
| zh_CN   | 1         | 2.86%   |
| ru_RU   | 1         | 2.86%   |
| pl_PL   | 1         | 2.86%   |
| ja_JP   | 1         | 2.86%   |
| el_GR   | 1         | 2.86%   |
| de_DE   | 1         | 2.86%   |
| cs_CZ   | 1         | 2.86%   |
| ca_ES   | 1         | 2.86%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 28        | 80%     |
| BIOS | 7         | 20%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 15        | 42.86%  |
| Xfs      | 8         | 22.86%  |
| Btrfs    | 4         | 11.43%  |
| F2fs     | 3         | 8.57%   |
| Zfs      | 2         | 5.71%   |
| Jfs      | 2         | 5.71%   |
| Bcachefs | 1         | 2.86%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 32        | 91.43%  |
| MBR     | 2         | 5.71%   |
| Unknown | 1         | 2.86%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 22        | 62.86%  |
| Yes       | 13        | 37.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 25        | 71.43%  |
| Yes       | 10        | 28.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 10        | 28.57%  |
| Gigabyte Technology | 6         | 17.14%  |
| ASUSTek Computer    | 6         | 17.14%  |
| Hewlett-Packard     | 3         | 8.57%   |
| Dell                | 2         | 5.71%   |
| Acer                | 2         | 5.71%   |
| System76            | 1         | 2.86%   |
| Oracle              | 1         | 2.86%   |
| Notebook            | 1         | 2.86%   |
| NEC Computers       | 1         | 2.86%   |
| Infinix             | 1         | 2.86%   |
| ASRock              | 1         | 2.86%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| System76 Darter Pro                       | 1         | 2.86%   |
| Oracle Sun Fire X4170 M3                  | 1         | 2.86%   |
| Notebook W510LU                           | 1         | 2.86%   |
| NEC Computers PC-VL150FS                  | 1         | 2.86%   |
| Lenovo Yoga 14sARH 2021 82LB              | 1         | 2.86%   |
| Lenovo ThinkStation P3 Tower 30GS00C6GE   | 1         | 2.86%   |
| Lenovo ThinkPad T14s Gen 6 21N1000SYA     | 1         | 2.86%   |
| Lenovo ThinkPad T14 Gen 3 21CGS06G0L      | 1         | 2.86%   |
| Lenovo ThinkPad T14 Gen 3 21AJS2C81M      | 1         | 2.86%   |
| Lenovo ThinkPad P16 Gen 1 21D6004XUS      | 1         | 2.86%   |
| Lenovo ThinkPad E15 Gen 2 20T8000MPB      | 1         | 2.86%   |
| Lenovo ThinkBook 15 G4 ABA 21DL           | 1         | 2.86%   |
| Lenovo Legion R9000P2021H 82JQ            | 1         | 2.86%   |
| Lenovo IdeaPad 5 15ALC05 82LN             | 1         | 2.86%   |
| Infinix YL51A5                            | 1         | 2.86%   |
| HP Z820 Workstation                       | 1         | 2.86%   |
| HP Pavilion Notebook                      | 1         | 2.86%   |
| HP EliteBook 655 15.6 inch G9 Notebook PC | 1         | 2.86%   |
| Gigabyte Z68X-UD3-B3                      | 1         | 2.86%   |
| Gigabyte X570S UD                         | 1         | 2.86%   |
| Gigabyte B650M AORUS ELITE AX ICE         | 1         | 2.86%   |
| Gigabyte B650 AORUS ELITE AX              | 1         | 2.86%   |
| Gigabyte AB350-Gaming                     | 1         | 2.86%   |
| Gigabyte A520 AORUS ELITE                 | 1         | 2.86%   |
| Dell PowerEdge R630                       | 1         | 2.86%   |
| Dell Latitude 7420                        | 1         | 2.86%   |
| ASUS ROG STRIX Z390-F GAMING              | 1         | 2.86%   |
| ASUS ROG STRIX X670E-E GAMING WIFI        | 1         | 2.86%   |
| ASUS ROG STRIX B650E-E GAMING WIFI        | 1         | 2.86%   |
| ASUS M3A78-CM                             | 1         | 2.86%   |
| ASUS ASUS TUF Gaming A17 FA706IH_FA706IH  | 1         | 2.86%   |
| ASUS ASUS TUF Gaming A16 FA617NT_FA617NT  | 1         | 2.86%   |
| ASRock X870 Steel Legend WiFi             | 1         | 2.86%   |
| Acer TravelMate B113                      | 1         | 2.86%   |
| Acer Aspire A517-52G                      | 1         | 2.86%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 5         | 14.29%  |
| ASUS ROG                 | 3         | 8.57%   |
| ASUS ASUS                | 2         | 5.71%   |
| System76 Darter          | 1         | 2.86%   |
| Oracle Sun               | 1         | 2.86%   |
| Notebook W510LU          | 1         | 2.86%   |
| NEC Computers PC-VL150FS | 1         | 2.86%   |
| Lenovo Yoga              | 1         | 2.86%   |
| Lenovo ThinkStation      | 1         | 2.86%   |
| Lenovo ThinkBook         | 1         | 2.86%   |
| Lenovo Legion            | 1         | 2.86%   |
| Lenovo IdeaPad           | 1         | 2.86%   |
| Infinix YL51A5           | 1         | 2.86%   |
| HP Z820                  | 1         | 2.86%   |
| HP Pavilion              | 1         | 2.86%   |
| HP EliteBook             | 1         | 2.86%   |
| Gigabyte Z68X-UD3-B3     | 1         | 2.86%   |
| Gigabyte X570S           | 1         | 2.86%   |
| Gigabyte B650M           | 1         | 2.86%   |
| Gigabyte B650            | 1         | 2.86%   |
| Gigabyte AB350-Gaming    | 1         | 2.86%   |
| Gigabyte A520            | 1         | 2.86%   |
| Dell PowerEdge           | 1         | 2.86%   |
| Dell Latitude            | 1         | 2.86%   |
| ASUS M3A78-CM            | 1         | 2.86%   |
| ASRock X870              | 1         | 2.86%   |
| Acer TravelMate          | 1         | 2.86%   |
| Acer Aspire              | 1         | 2.86%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 8         | 22.86%  |
| 2024 | 6         | 17.14%  |
| 2021 | 5         | 14.29%  |
| 2020 | 4         | 11.43%  |
| 2012 | 3         | 8.57%   |
| 2023 | 2         | 5.71%   |
| 2019 | 1         | 2.86%   |
| 2018 | 1         | 2.86%   |
| 2017 | 1         | 2.86%   |
| 2015 | 1         | 2.86%   |
| 2013 | 1         | 2.86%   |
| 2011 | 1         | 2.86%   |
| 2008 | 1         | 2.86%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 19        | 54.29%  |
| Desktop  | 14        | 40%     |
| Server   | 2         | 5.71%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 34        | 97.14%  |
| Enabled  | 1         | 2.86%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 34        | 97.14%  |
| Yes  | 1         | 2.86%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 10        | 28.57%  |
| 8.01-16.0       | 10        | 28.57%  |
| 64.01-256.0     | 5         | 14.29%  |
| 24.01-32.0      | 4         | 11.43%  |
| 4.01-8.0        | 2         | 5.71%   |
| 16.01-24.0      | 2         | 5.71%   |
| More than 256.0 | 1         | 2.86%   |
| 2.01-3.0        | 1         | 2.86%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 8         | 22.86%  |
| 2.01-3.0   | 8         | 22.86%  |
| 1.01-2.0   | 6         | 17.14%  |
| 8.01-16.0  | 6         | 17.14%  |
| 3.01-4.0   | 3         | 8.57%   |
| 0.51-1.0   | 2         | 5.71%   |
| 24.01-32.0 | 1         | 2.86%   |
| 16.01-24.0 | 1         | 2.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 17        | 48.57%  |
| 2      | 9         | 25.71%  |
| 6      | 4         | 11.43%  |
| 3      | 4         | 11.43%  |
| 4      | 1         | 2.86%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 29        | 82.86%  |
| Yes       | 6         | 17.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 88.57%  |
| No        | 4         | 11.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 62.86%  |
| No        | 13        | 37.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 62.86%  |
| No        | 13        | 37.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country     | Computers | Percent |
|-------------|-----------|---------|
| Poland      | 6         | 17.14%  |
| USA         | 5         | 14.29%  |
| Russia      | 3         | 8.57%   |
| Germany     | 3         | 8.57%   |
| Spain       | 2         | 5.71%   |
| Czechia     | 2         | 5.71%   |
| China       | 2         | 5.71%   |
| UK          | 1         | 2.86%   |
| Sweden      | 1         | 2.86%   |
| Serbia      | 1         | 2.86%   |
| Netherlands | 1         | 2.86%   |
| Latvia      | 1         | 2.86%   |
| Japan       | 1         | 2.86%   |
| India       | 1         | 2.86%   |
| Greece      | 1         | 2.86%   |
| France      | 1         | 2.86%   |
| Egypt       | 1         | 2.86%   |
| Australia   | 1         | 2.86%   |
| Argentina   | 1         | 2.86%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City          | Computers | Percent |
|---------------|-----------|---------|
| Suffolk       | 2         | 5.71%   |
| Moscow        | 2         | 5.71%   |
| Kielce        | 2         | 5.71%   |
| Cieszyn       | 2         | 5.71%   |
| Xi'an         | 1         | 2.86%   |
| Utrecht       | 1         | 2.86%   |
| Tychy         | 1         | 2.86%   |
| Tucson        | 1         | 2.86%   |
| Stockholm     | 1         | 2.86%   |
| Šlapanice    | 1         | 2.86%   |
| Riga          | 1         | 2.86%   |
| Ramenskoye    | 1         | 2.86%   |
| Northwich     | 1         | 2.86%   |
| Naha          | 1         | 2.86%   |
| Mahon         | 1         | 2.86%   |
| Leverkusen    | 1         | 2.86%   |
| Kollam        | 1         | 2.86%   |
| Gdansk        | 1         | 2.86%   |
| Gaillac       | 1         | 2.86%   |
| Fulda         | 1         | 2.86%   |
| Dresden       | 1         | 2.86%   |
| Chomutov      | 1         | 2.86%   |
| Carl Junction | 1         | 2.86%   |
| Cairo         | 1         | 2.86%   |
| Buenos Aires  | 1         | 2.86%   |
| Bijie         | 1         | 2.86%   |
| Belgrade      | 1         | 2.86%   |
| Barcelona     | 1         | 2.86%   |
| Athens        | 1         | 2.86%   |
| Albany        | 1         | 2.86%   |
| Adelaide      | 1         | 2.86%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 13        | 20     | 21.31%  |
| SanDisk                      | 7         | 8      | 11.48%  |
| WDC                          | 6         | 8      | 9.84%   |
| Seagate                      | 6         | 7      | 9.84%   |
| Micron Technology            | 5         | 5      | 8.2%    |
| SK hynix                     | 3         | 3      | 4.92%   |
| GOODRAM                      | 3         | 3      | 4.92%   |
| Toshiba                      | 2         | 3      | 3.28%   |
| Phison Electronics           | 2         | 2      | 3.28%   |
| Hitachi                      | 2         | 4      | 3.28%   |
| ADATA Technology             | 2         | 2      | 3.28%   |
| Yangtze Memory Technologies  | 1         | 1      | 1.64%   |
| Unknown                      | 1         | 1      | 1.64%   |
| Union Memory                 | 1         | 1      | 1.64%   |
| SPCC                         | 1         | 1      | 1.64%   |
| Shenzhen Longsys Electronics | 1         | 1      | 1.64%   |
| Kingston Technology Company  | 1         | 1      | 1.64%   |
| Intel                        | 1         | 1      | 1.64%   |
| Hewlett-Packard              | 1         | 2      | 1.64%   |
| Crucial                      | 1         | 1      | 1.64%   |
| 2.5S1T                       | 1         | 1      | 1.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 3         | 4.29%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 2         | 2.86%   |
| Samsung SSD 870 EVO 1TB                              | 2         | 2.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 2         | 2.86%   |
| GOODRAM SSDPR-CL100-480-G2 480GB                     | 2         | 2.86%   |
| Yangtze Memory ZHITAI TiPlus7100 1TB                 | 1         | 1.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 1         | 1.43%   |
| WDC WD82PURZ-85TEUY0 8TB                             | 1         | 1.43%   |
| WDC WD30EZRX-00D8PB0 3TB                             | 1         | 1.43%   |
| WDC WD30EFRX-68EUZN0 3TB                             | 1         | 1.43%   |
| WDC WD Blue SA510 2.5 1000GB SSD                     | 1         | 1.43%   |
| Unknown MMC Card  2GB                                | 1         | 1.43%   |
| Union Memory UMIS RPJTJ512MEE1OWX 512GB              | 1         | 1.43%   |
| Toshiba HDWE150 5TB                                  | 1         | 1.43%   |
| Toshiba HDWD130 3TB                                  | 1         | 1.43%   |
| Toshiba DT01ACA050 500GB                             | 1         | 1.43%   |
| SPCC Solid State Disk 240GB                          | 1         | 1.43%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB               | 1         | 1.43%   |
| SK hynix SKHynix_HFS002TEJ9X102N 2TB                 | 1         | 1.43%   |
| SK hynix PC711 NVMe 512GB                            | 1         | 1.43%   |
| Shenzhen Longsys FORESEE XP1000F512G 512GB           | 1         | 1.43%   |
| Seagate XS800LE10003 800GB                           | 1         | 1.43%   |
| Seagate XS400LE10003 400GB                           | 1         | 1.43%   |
| Seagate ST4000DM004-2CV104 4TB                       | 1         | 1.43%   |
| Seagate ST3500418AS 500GB                            | 1         | 1.43%   |
| Seagate ST2000VN004-2E4164 2TB                       | 1         | 1.43%   |
| Seagate ST12000NM0008-2H3101 12TB                    | 1         | 1.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 1         | 1.43%   |
| Sandisk WD_BLACK SN850X 2000GB                       | 1         | 1.43%   |
| Sandisk WD_BLACK SN770 1TB                           | 1         | 1.43%   |
| Sandisk WDC PC SN530 SDBPMPZ-512G-1101 512GB         | 1         | 1.43%   |
| Sandisk WD PC SN740 SDDPNQD-512G-1002 512GB          | 1         | 1.43%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 1         | 1.43%   |
| SanDisk SDSSDH3500G 500GB                            | 1         | 1.43%   |
| SanDisk SD7SB3Q128G1002 128GB SSD                    | 1         | 1.43%   |
| Samsung SSD 990 PRO 2TB                              | 1         | 1.43%   |
| Samsung SSD 870 QVO 1TB                              | 1         | 1.43%   |
| Samsung SSD 870 EVO 4TB                              | 1         | 1.43%   |
| Samsung SSD 870 EVO 2TB                              | 1         | 1.43%   |
| Samsung SSD 860 EVO 1TB                              | 1         | 1.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| Seagate         | 5         | 5      | 35.71%  |
| WDC             | 4         | 6      | 28.57%  |
| Toshiba         | 2         | 3      | 14.29%  |
| Hitachi         | 2         | 4      | 14.29%  |
| Hewlett-Packard | 1         | 2      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 11     | 41.18%  |
| GOODRAM             | 3         | 3      | 17.65%  |
| WDC                 | 2         | 2      | 11.76%  |
| SanDisk             | 2         | 2      | 11.76%  |
| SPCC                | 1         | 1      | 5.88%   |
| Intel               | 1         | 1      | 5.88%   |
| Crucial             | 1         | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 25        | 31     | 46.3%   |
| SSD     | 15        | 21     | 27.78%  |
| HDD     | 11        | 20     | 20.37%  |
| Unknown | 2         | 3      | 3.7%    |
| MMC     | 1         | 1      | 1.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 25        | 31     | 55.56%  |
| SATA | 17        | 40     | 37.78%  |
| SAS  | 2         | 4      | 4.44%   |
| MMC  | 1         | 1      | 2.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 11        | 17     | 37.93%  |
| 0.51-1.0   | 8         | 10     | 27.59%  |
| 2.01-3.0   | 3         | 6      | 10.34%  |
| 3.01-4.0   | 2         | 2      | 6.9%    |
| 1.01-2.0   | 2         | 3      | 6.9%    |
| 4.01-10.0  | 2         | 2      | 6.9%    |
| 10.01-20.0 | 1         | 1      | 3.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 7         | 20%     |
| More than 3000 | 6         | 17.14%  |
| 251-500        | 6         | 17.14%  |
| 2001-3000      | 4         | 11.43%  |
| 1001-2000      | 3         | 8.57%   |
| Unknown        | 3         | 8.57%   |
| 1-20           | 2         | 5.71%   |
| 51-100         | 2         | 5.71%   |
| 21-50          | 1         | 2.86%   |
| 101-250        | 1         | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 6         | 17.14%  |
| 101-250        | 5         | 14.29%  |
| 251-500        | 4         | 11.43%  |
| 1-20           | 4         | 11.43%  |
| More than 3000 | 3         | 8.57%   |
| 21-50          | 3         | 8.57%   |
| 1001-2000      | 3         | 8.57%   |
| 51-100         | 3         | 8.57%   |
| Unknown        | 3         | 8.57%   |
| 2001-3000      | 1         | 2.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD30EZRX-00D8PB0 3TB           | 1         | 1      | 50%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 100%    |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)

![Drive Status](./All/images/line_chart/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 34        | 66     | 85%     |
| Detected | 4         | 8      | 10%     |
| Malfunc  | 2         | 2      | 5%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| AMD                          | 12        | 20.34%  |
| Intel                        | 11        | 18.64%  |
| Samsung Electronics          | 9         | 15.25%  |
| SanDisk                      | 5         | 8.47%   |
| Micron Technology            | 5         | 8.47%   |
| SK hynix                     | 3         | 5.08%   |
| Phison Electronics           | 2         | 3.39%   |
| LSI Logic / Symbios Logic    | 2         | 3.39%   |
| ASMedia Technology           | 2         | 3.39%   |
| ADATA Technology             | 2         | 3.39%   |
| Yangtze Memory Technologies  | 1         | 1.69%   |
| Union Memory (Shenzhen)      | 1         | 1.69%   |
| Shenzhen Longsys Electronics | 1         | 1.69%   |
| Marvell Technology Group     | 1         | 1.69%   |
| Kingston Technology Company  | 1         | 1.69%   |
| Broadcom / LSI               | 1         | 1.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                                                              | Computers | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                                                | 5         | 7.69%   |
| AMD 600 Series Chipset SATA Controller                                                                             | 5         | 7.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 3         | 4.62%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                                               | 2         | 3.08%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                                            | 2         | 3.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 2         | 3.08%   |
| Micron 2210 NVMe SSD [Cobain]                                                                                      | 2         | 3.08%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                                                          | 2         | 3.08%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                                                      | 2         | 3.08%   |
| Yangtze Memory ZHITAI TiPlus7100                                                                                   | 1         | 1.54%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 512GB                                                              | 1         | 1.54%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                                                 | 1         | 1.54%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 1         | 1.54%   |
| Sandisk WD Black SN850X NVMe SSD                                                                                   | 1         | 1.54%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)                                          | 1         | 1.54%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                                                              | 1         | 1.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                                                      | 1         | 1.54%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                                                        | 1         | 1.54%   |
| Samsung NVMe SSD Controller PM9C1a (DRAM-less)                                                                     | 1         | 1.54%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 1         | 1.54%   |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)                                                                | 1         | 1.54%   |
| Phison E12 NVMe Controller                                                                                         | 1         | 1.54%   |
| Micron 7450 PRO NVMe SSD                                                                                           | 1         | 1.54%   |
| Micron 3400 NVMe SSD [Hendrix]                                                                                     | 1         | 1.54%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                                                        | 1         | 1.54%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                                                       | 1         | 1.54%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                                            | 1         | 1.54%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                                                            | 1         | 1.54%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                                               | 1         | 1.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                                                 | 1         | 1.54%   |
| Intel Volume Management Device NVMe RAID Controller                                                                | 1         | 1.54%   |
| Intel Tiger Lake-LP SATA Controller                                                                                | 1         | 1.54%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                                                         | 1         | 1.54%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                                                         | 1         | 1.54%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                                                   | 1         | 1.54%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                                                | 1         | 1.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller                                   | 1         | 1.54%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                                                 | 1         | 1.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 1         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5)                            | 1         | 1.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 25        | 47.17%  |
| SATA | 22        | 41.51%  |
| RAID | 2         | 3.77%   |
| SAS  | 2         | 3.77%   |
| IDE  | 2         | 3.77%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor   | Computers | Percent |
|----------|-----------|---------|
| AMD      | 19        | 54.29%  |
| Intel    | 15        | 42.86%  |
| Qualcomm | 1         | 2.86%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 7 5825U with Radeon Graphics      | 2         | 5.71%   |
| Qualcomm Processor                          | 1         | 2.86%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1         | 2.86%   |
| Intel Xeon CPU E5-2667 v4 @ 3.20GHz         | 1         | 2.86%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz          | 1         | 2.86%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 2.86%   |
| Intel Core Ultra 7 155H                     | 1         | 2.86%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1         | 2.86%   |
| Intel Core i9-14900K                        | 1         | 2.86%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1         | 2.86%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 1         | 2.86%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1         | 2.86%   |
| Intel Celeron CPU 1017U @ 1.60GHz           | 1         | 2.86%   |
| Intel 12th Gen Core i9-12900HX              | 1         | 2.86%   |
| Intel 12th Gen Core i7-1270P                | 1         | 2.86%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz     | 1         | 2.86%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 1         | 2.86%   |
| AMD Ryzen 9 7950X3D 16-Core Processor       | 1         | 2.86%   |
| AMD Ryzen 9 7900X 12-Core Processor         | 1         | 2.86%   |
| AMD Ryzen 7 PRO 6850U with Radeon Graphics  | 1         | 2.86%   |
| AMD Ryzen 7 9800X3D 8-Core Processor        | 1         | 2.86%   |
| AMD Ryzen 7 9700X 8-Core Processor          | 1         | 2.86%   |
| AMD Ryzen 7 7735HS with Radeon Graphics     | 1         | 2.86%   |
| AMD Ryzen 7 7700X 8-Core Processor          | 1         | 2.86%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 1         | 2.86%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 1         | 2.86%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 1         | 2.86%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 1         | 2.86%   |
| AMD Ryzen 5 5625U with Radeon Graphics      | 1         | 2.86%   |
| AMD Ryzen 5 4600H with Radeon Graphics      | 1         | 2.86%   |
| AMD Ryzen 5 4500U with Radeon Graphics      | 1         | 2.86%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1         | 2.86%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 1         | 2.86%   |
| AMD Phenom II X4 955 Processor              | 1         | 2.86%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model            | Computers | Percent |
|------------------|-----------|---------|
| AMD Ryzen 7      | 10        | 28.57%  |
| Other            | 5         | 14.29%  |
| AMD Ryzen 5      | 5         | 14.29%  |
| Intel Xeon       | 3         | 8.57%   |
| Intel Core i9    | 2         | 5.71%   |
| AMD Ryzen 9      | 2         | 5.71%   |
| Intel Pentium    | 1         | 2.86%   |
| Intel Core i7    | 1         | 2.86%   |
| Intel Core i5    | 1         | 2.86%   |
| Intel Core i3    | 1         | 2.86%   |
| Intel Core       | 1         | 2.86%   |
| Intel Celeron    | 1         | 2.86%   |
| AMD Ryzen 7 PRO  | 1         | 2.86%   |
| AMD Phenom II X4 | 1         | 2.86%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 8      | 13        | 37.14%  |
| 16     | 6         | 17.14%  |
| 4      | 6         | 17.14%  |
| 6      | 4         | 11.43%  |
| 2      | 3         | 8.57%   |
| 12     | 2         | 5.71%   |
| 24     | 1         | 2.86%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 32        | 91.43%  |
| 2      | 3         | 8.57%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 30        | 85.71%  |
| 1      | 5         | 14.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 34        | 97.14%  |
| 64-bit         | 1         | 2.86%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 68.57%  |
| 0x0a500011 | 2         | 5.71%   |
| 0x806c1    | 1         | 2.86%   |
| 0x206d7    | 1         | 2.86%   |
| 0x0b404023 | 1         | 2.86%   |
| 0x0a50000c | 1         | 2.86%   |
| 0x08608108 | 1         | 2.86%   |
| 0x0860010d | 1         | 2.86%   |
| 0x08600103 | 1         | 2.86%   |
| 0x0800820d | 1         | 2.86%   |
| 0x010000db | 1         | 2.86%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 9         | 25.71%  |
| Zen 3             | 5         | 14.29%  |
| SandyBridge       | 4         | 11.43%  |
| Zen 2             | 3         | 8.57%   |
| Alderlake Hybrid  | 3         | 8.57%   |
| Zen+              | 2         | 5.71%   |
| TigerLake         | 2         | 5.71%   |
| Broadwell         | 2         | 5.71%   |
| Silvermont        | 1         | 2.86%   |
| Meteorlake Hybrid | 1         | 2.86%   |
| KabyLake          | 1         | 2.86%   |
| K10               | 1         | 2.86%   |
| IvyBridge         | 1         | 2.86%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| AMD                        | 21        | 52.5%   |
| Intel                      | 10        | 25%     |
| Nvidia                     | 7         | 17.5%   |
| Matrox Electronics Systems | 1         | 2.5%    |
| ASPEED Technology          | 1         | 2.5%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 3         | 6.52%   |
| AMD Raphael                                                                              | 3         | 6.52%   |
| AMD Barcelo                                                                              | 3         | 6.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 4.35%   |
| AMD Rembrandt [Radeon 680M]                                                              | 2         | 4.35%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 2         | 4.35%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2         | 4.35%   |
| AMD Granite Ridge [Radeon Graphics]                                                      | 2         | 4.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 4.35%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 4.35%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 2.17%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 2.17%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 2.17%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 2.17%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 2.17%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                                     | 1         | 2.17%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 2.17%   |
| Nvidia GA104GLM [RTX A4500 Laptop GPU]                                                   | 1         | 2.17%   |
| Matrox Electronics Systems G200eR2                                                       | 1         | 2.17%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                               | 1         | 2.17%   |
| Intel Meteor Lake-P [Intel Arc Graphics]                                                 | 1         | 2.17%   |
| Intel HD Graphics 5500                                                                   | 1         | 2.17%   |
| Intel DG2 [Arc A770]                                                                     | 1         | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.17%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 1         | 2.17%   |
| Intel Alder Lake-HX GT1 [UHD Graphics 770]                                               | 1         | 2.17%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 2.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 2.17%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 1         | 2.17%   |
| AMD RS780C [Radeon 3100]                                                                 | 1         | 2.17%   |
| AMD Navi 33 [Radeon RX 7600/7600 XT/7600M XT/7600S/7700S / PRO W7600]                    | 1         | 2.17%   |
| AMD Lucienne                                                                             | 1         | 2.17%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 2.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 14        | 40%     |
| 1 x Intel      | 6         | 17.14%  |
| 2 x AMD        | 4         | 11.43%  |
| Intel + Nvidia | 3         | 8.57%   |
| AMD + Nvidia   | 3         | 8.57%   |
| Other          | 1         | 2.86%   |
| 2 x Nvidia     | 1         | 2.86%   |
| 2 x Intel      | 1         | 2.86%   |
| 1 x Matrox     | 1         | 2.86%   |
| 1 x ASPEED     | 1         | 2.86%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 27        | 77.14%  |
| Proprietary | 5         | 14.29%  |
| Unknown     | 3         | 8.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 40%     |
| 7.01-8.0   | 6         | 17.14%  |
| 1.01-2.0   | 6         | 17.14%  |
| 0.01-0.5   | 5         | 14.29%  |
| 0.51-1.0   | 3         | 8.57%   |
| 8.01-16.0  | 1         | 2.86%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 6         | 15%     |
| Samsung Electronics     | 4         | 10%     |
| BOE                     | 4         | 10%     |
| CSO                     | 3         | 7.5%    |
| AU Optronics            | 3         | 7.5%    |
| ViewSonic               | 2         | 5%      |
| Eizo                    | 2         | 5%      |
| Dell                    | 2         | 5%      |
| Sceptre Tech            | 1         | 2.5%    |
| Mi                      | 1         | 2.5%    |
| MDT                     | 1         | 2.5%    |
| LG Display              | 1         | 2.5%    |
| Lenovo                  | 1         | 2.5%    |
| INNOCN                  | 1         | 2.5%    |
| Iiyama                  | 1         | 2.5%    |
| HKC                     | 1         | 2.5%    |
| Goldstar                | 1         | 2.5%    |
| Denver                  | 1         | 2.5%    |
| Chi Mei Optoelectronics | 1         | 2.5%    |
| BenQ                    | 1         | 2.5%    |
| Apple                   | 1         | 2.5%    |
| AOC                     | 1         | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 2         | 4.88%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch            | 1         | 2.44%   |
| ViewSonic VG3448 VSC0D38 3440x1440 800x335mm 34.1-inch                | 1         | 2.44%   |
| Sceptre Tech Sceptre M27 SPT6C03 1920x1080 530x300mm 24.0-inch        | 1         | 2.44%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch     | 1         | 2.44%   |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch  | 1         | 2.44%   |
| Samsung Electronics SyncMaster SAM0352 1680x1050 459x296mm 21.5-inch  | 1         | 2.44%   |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch     | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 2.44%   |
| Mi P27FBA-RX XMIB010 1920x1080 597x336mm 27.0-inch                    | 1         | 2.44%   |
| MDT Internal Display MDT1F41 1920x1080 344x194mm 15.5-inch            | 1         | 2.44%   |
| LG Display LCD Monitor LGD06AA 3840x2400 344x215mm 16.0-inch          | 1         | 2.44%   |
| Lenovo LEN S27q-10 LEN61E8 2560x1440 597x336mm 27.0-inch              | 1         | 2.44%   |
| INNOCN 49C1R IOCFFFF 1920x1080 1197x337mm 49.0-inch                   | 1         | 2.44%   |
| Iiyama PLE2483H IVM6113 1920x1080 530x300mm 24.0-inch                 | 1         | 2.44%   |
| HKC 24E3 HKC2431 1920x1080 527x296mm 23.8-inch                        | 1         | 2.44%   |
| Goldstar ULTRAGEAR+ GSM780F 3840x2160 697x392mm 31.5-inch             | 1         | 2.44%   |
| Eizo FS2333 ENC2344 1920x1080 510x287mm 23.0-inch                     | 1         | 2.44%   |
| Eizo EV2480 ENC3225 1920x1080 528x297mm 23.9-inch                     | 1         | 2.44%   |
| Denver PrimetekH3CQC LHCFFFF 3840x1080 1197x337mm 49.0-inch           | 1         | 2.44%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 1         | 2.44%   |
| Dell LCD Monitor SX2210 1920x1080                                     | 1         | 2.44%   |
| CSO LCD Monitor CSO1600 2560x1600 345x215mm 16.0-inch                 | 1         | 2.44%   |
| CSO LCD Monitor CSO1506 1920x1080 344x194mm 15.5-inch                 | 1         | 2.44%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                 | 1         | 2.44%   |
| Chimei Innolux N160JME_GE1 CMN1624 1920x1200 344x215mm 16.0-inch      | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN1457 1920x1200 301x188mm 14.0-inch      | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN1418 1920x1080 309x173mm 13.9-inch      | 1         | 2.44%   |
| Chi Mei Optoelectronics CMC 19AW CMO2198 1440x900 408x255mm 18.9-inch | 1         | 2.44%   |
| BOE LCD Monitor BOE0C26 1920x1200 300x190mm 14.0-inch                 | 1         | 2.44%   |
| BOE LCD Monitor BOE0ACA 2560x1600 340x210mm 15.7-inch                 | 1         | 2.44%   |
| BOE LCD Monitor BOE0A35 1920x1200 302x189mm 14.0-inch                 | 1         | 2.44%   |
| BOE LCD Monitor BOE0825 1920x1080 382x215mm 17.3-inch                 | 1         | 2.44%   |
| BenQ E2200HD BNQ790C 1920x1080 477x268mm 21.5-inch                    | 1         | 2.44%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 301x188mm 14.0-inch        | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO8294 1920x1080 382x215mm 17.3-inch        | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch         | 1         | 2.44%   |
| Apple LCD Monitor APP9CF4 1366x768 256x144mm 11.6-inch                | 1         | 2.44%   |
| AOC 22B2WG5 AOC2202 1920x1080 477x268mm 21.5-inch                     | 1         | 2.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 15        | 40.54%  |
| 1920x1200 (WUXGA)  | 6         | 16.22%  |
| 3840x2160 (4K)     | 4         | 10.81%  |
| 1366x768 (WXGA)    | 3         | 8.11%   |
| 2560x1600          | 2         | 5.41%   |
| 2560x1440 (QHD)    | 2         | 5.41%   |
| 3840x2400          | 1         | 2.7%    |
| 3440x1440          | 1         | 2.7%    |
| 2880x1800          | 1         | 2.7%    |
| 1680x1050 (WSXGA+) | 1         | 2.7%    |
| 1440x900 (WXGA+)   | 1         | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 21      | 6         | 15.79%  |
| 15      | 5         | 13.16%  |
| 14      | 5         | 13.16%  |
| 31      | 4         | 10.53%  |
| 24      | 3         | 7.89%   |
| 16      | 3         | 7.89%   |
| 27      | 2         | 5.26%   |
| 17      | 2         | 5.26%   |
| 11      | 2         | 5.26%   |
| 49      | 1         | 2.63%   |
| 34      | 1         | 2.63%   |
| 23      | 1         | 2.63%   |
| 19      | 1         | 2.63%   |
| 13      | 1         | 2.63%   |
| Unknown | 1         | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 35.14%  |
| 501-600     | 6         | 16.22%  |
| 401-500     | 6         | 16.22%  |
| 601-700     | 4         | 10.81%  |
| 201-300     | 3         | 8.11%   |
| 351-400     | 2         | 5.41%   |
| 701-800     | 1         | 2.7%    |
| 1001-1500   | 1         | 2.7%    |
| Unknown     | 1         | 2.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 22        | 59.46%  |
| 16/10   | 12        | 32.43%  |
| 32/9    | 1         | 2.7%    |
| 21/9    | 1         | 2.7%    |
| Unknown | 1         | 2.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 8         | 21.05%  |
| 81-90          | 6         | 15.79%  |
| 351-500        | 5         | 13.16%  |
| 111-120        | 4         | 10.53%  |
| 101-110        | 4         | 10.53%  |
| 51-60          | 2         | 5.26%   |
| 301-350        | 2         | 5.26%   |
| 151-200        | 2         | 5.26%   |
| 121-130        | 2         | 5.26%   |
| 251-300        | 1         | 2.63%   |
| 501-1000       | 1         | 2.63%   |
| Unknown        | 1         | 2.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 12        | 30.77%  |
| 51-100        | 9         | 23.08%  |
| 101-120       | 8         | 20.51%  |
| 161-240       | 6         | 15.38%  |
| More than 240 | 2         | 5.13%   |
| 1-50          | 1         | 2.56%   |
| Unknown       | 1         | 2.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 25        | 71.43%  |
| 2     | 7         | 20%     |
| 0     | 2         | 5.71%   |
| 3     | 1         | 2.86%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 21        | 45.65%  |
| Intel                 | 15        | 32.61%  |
| Broadcom              | 3         | 6.52%   |
| MediaTek              | 2         | 4.35%   |
| Qualcomm Technologies | 1         | 2.17%   |
| Qualcomm              | 1         | 2.17%   |
| Microsoft             | 1         | 2.17%   |
| Lenovo                | 1         | 2.17%   |
| Dell                  | 1         | 2.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12        | 21.05%  |
| Realtek RTL8125 2.5GbE Controller                                      | 4         | 7.02%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 2         | 3.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 3.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 3.51%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 3.51%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 3.51%   |
| Intel Wi-Fi 6 AX200                                                    | 2         | 3.51%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 1         | 1.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 1.75%   |
| Realtek 802.11ac WLAN Adapter                                          | 1         | 1.75%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]       | 1         | 1.75%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 1         | 1.75%   |
| Microsoft Xbox 360 Wireless Adapter                                    | 1         | 1.75%   |
| Lenovo USB-C Dock Ethernet                                             | 1         | 1.75%   |
| Intel Wireless 7265                                                    | 1         | 1.75%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 1         | 1.75%   |
| Intel Meteor Lake PCH CNVi WiFi                                        | 1         | 1.75%   |
| Intel Ethernet Controller I226-V                                       | 1         | 1.75%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.75%   |
| Intel Ethernet Controller I219-LM                                      | 1         | 1.75%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 1         | 1.75%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 1.75%   |
| Intel Ethernet Connection (17) I219-LM                                 | 1         | 1.75%   |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 1.75%   |
| Intel Centrino Advanced-N 6235                                         | 1         | 1.75%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 1         | 1.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 1         | 1.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1         | 1.75%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 1.75%   |
| Dell iDRAC Virtual NIC                                                 | 1         | 1.75%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 1         | 1.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 1.75%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                        | 1         | 1.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 10        | 45.45%  |
| Realtek Semiconductor | 8         | 36.36%  |
| MediaTek              | 2         | 9.09%   |
| Qualcomm              | 1         | 4.55%   |
| Microsoft             | 1         | 4.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 9.09%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 2         | 9.09%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 9.09%   |
| Intel Wi-Fi 6 AX200                                           | 2         | 9.09%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller   | 1         | 4.55%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 1         | 4.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 4.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 4.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 4.55%   |
| Realtek 802.11ac WLAN Adapter                                 | 1         | 4.55%   |
| Qualcomm QCNFA765 Wireless Network Adapter                    | 1         | 4.55%   |
| Microsoft Xbox 360 Wireless Adapter                           | 1         | 4.55%   |
| Intel Wireless 7265                                           | 1         | 4.55%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 1         | 4.55%   |
| Intel Meteor Lake PCH CNVi WiFi                               | 1         | 4.55%   |
| Intel Centrino Advanced-N 6235                                | 1         | 4.55%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 1         | 4.55%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 1         | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 19        | 57.58%  |
| Intel                 | 8         | 24.24%  |
| Broadcom              | 3         | 9.09%   |
| Qualcomm Technologies | 1         | 3.03%   |
| Lenovo                | 1         | 3.03%   |
| Dell                  | 1         | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12        | 34.29%  |
| Realtek RTL8125 2.5GbE Controller                                      | 4         | 11.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 5.71%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 2.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 2.86%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]       | 1         | 2.86%   |
| Lenovo USB-C Dock Ethernet                                             | 1         | 2.86%   |
| Intel Ethernet Controller I226-V                                       | 1         | 2.86%   |
| Intel Ethernet Controller I225-V                                       | 1         | 2.86%   |
| Intel Ethernet Controller I219-LM                                      | 1         | 2.86%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 1         | 2.86%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 2.86%   |
| Intel Ethernet Connection (17) I219-LM                                 | 1         | 2.86%   |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1         | 2.86%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 2.86%   |
| Dell iDRAC Virtual NIC                                                 | 1         | 2.86%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 1         | 2.86%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 2.86%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                        | 1         | 2.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 31        | 58.49%  |
| WiFi     | 22        | 41.51%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 20        | 55.56%  |
| WiFi     | 16        | 44.44%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 17        | 48.57%  |
| 1     | 16        | 45.71%  |
| 4     | 2         | 5.71%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 28        | 80%     |
| Yes  | 7         | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 9         | 40.91%  |
| Realtek Semiconductor   | 7         | 31.82%  |
| IMC Networks            | 2         | 9.09%   |
| USI                     | 1         | 4.55%   |
| MediaTek                | 1         | 4.55%   |
| Lite-On Technology      | 1         | 4.55%   |
| Cambridge Silicon Radio | 1         | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 6         | 27.27%  |
| Intel AX211 Bluetooth                               | 3         | 13.64%  |
| Intel AX201 Bluetooth                               | 2         | 9.09%   |
| USI Bluetooth Device                                | 1         | 4.55%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 4.55%   |
| MediaTek Wireless_Device                            | 1         | 4.55%   |
| Lite-On Bluetooth Radio                             | 1         | 4.55%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 4.55%   |
| Intel Bluetooth wireless interface                  | 1         | 4.55%   |
| Intel AX210 Bluetooth                               | 1         | 4.55%   |
| Intel AX200 Bluetooth                               | 1         | 4.55%   |
| IMC Networks Wireless_Device                        | 1         | 4.55%   |
| IMC Networks Bluetooth Radio                        | 1         | 4.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AMD                 | 21        | 42.86%  |
| Intel               | 13        | 26.53%  |
| Nvidia              | 4         | 8.16%   |
| Creative Technology | 3         | 6.12%   |
| ASUSTek Computer    | 2         | 4.08%   |
| XMOS                | 1         | 2.04%   |
| Logitech            | 1         | 2.04%   |
| Lenovo              | 1         | 2.04%   |
| Kingston Technology | 1         | 2.04%   |
| C-Media Electronics | 1         | 2.04%   |
| ASRock              | 1         | 2.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 15        | 21.13%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 11.27%  |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 7         | 9.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.82%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 2         | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 2.82%   |
| Creative Technology Sound BlasterX G6                                                             | 2         | 2.82%   |
| ASUSTek Computer USB Audio                                                                        | 2         | 2.82%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 2.82%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 2.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 2.82%   |
| XMOS iFi (by AMR) HD USB Audio                                                                    | 1         | 1.41%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 1.41%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 1.41%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 1.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.41%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1.41%   |
| Logitech Logitech G PRO X Gaming Headset                                                          | 1         | 1.41%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                                         | 1         | 1.41%   |
| Kingston Technology HyperX QuadCast                                                               | 1         | 1.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.41%   |
| Intel Meteor Lake-P HD Audio Controller                                                           | 1         | 1.41%   |
| Intel DG2 Audio Controller                                                                        | 1         | 1.41%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.41%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 1.41%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.41%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 1.41%   |
| Creative Technology Pebble V3                                                                     | 1         | 1.41%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 1.41%   |
| ASRock USB Audio                                                                                  | 1         | 1.41%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.41%   |
| AMD Navi 31 HDMI/DP Audio                                                                         | 1         | 1.41%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 1.41%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 1.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 33.33%  |
| SK hynix            | 6         | 15.38%  |
| Kingston            | 4         | 10.26%  |
| Micron Technology   | 3         | 7.69%   |
| G.Skill             | 3         | 7.69%   |
| A-DATA Technology   | 3         | 7.69%   |
| Unknown             | 2         | 5.13%   |
| Crucial             | 2         | 5.13%   |
| Silicon Power       | 1         | 2.56%   |
| Neo Forza           | 1         | 2.56%   |
| Unknown             | 1         | 2.56%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 4.65%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                     | 1         | 2.33%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                    | 1         | 2.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 2.33%   |
| SK hynix RAM HMCG88MEBSA092N 32GB SODIMM DDR5 4800MT/s       | 1         | 2.33%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 2.33%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 2.33%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 2.33%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 2.33%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s   | 1         | 2.33%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s  | 1         | 2.33%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                    | 1         | 2.33%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                 | 1         | 2.33%   |
| Samsung RAM Module 16GB DIMM DDR3 1600MT/s                   | 1         | 2.33%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.33%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 2.33%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 2.33%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 2.33%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 2.33%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s      | 1         | 2.33%   |
| Samsung RAM M393B5270DH0-YK0 4GB DIMM DDR3 1600MT/s          | 1         | 2.33%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2400MT/s         | 1         | 2.33%   |
| Samsung RAM M323R4GA3BB0-CQKOD 32GB DIMM DDR5 4800MT/s       | 1         | 2.33%   |
| Samsung RAM K4UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 2.33%   |
| Neo Forza RAM NMSO516F81-5600J 16GB SODIMM DDR5 5600MT/s     | 1         | 2.33%   |
| Micron RAM MT53E1G32D4NQ-046WTE 8GB SODIMM LPDDR4 3200MT/s   | 1         | 2.33%   |
| Micron RAM MT40A1G16RC-062E:B 8GB Row Of Chips DDR4 3200MT/s | 1         | 2.33%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 1         | 2.33%   |
| Kingston RAM KHX3200C16D4/4GX 4GB DIMM DDR4 3600MT/s         | 1         | 2.33%   |
| Kingston RAM KHX2133C11D3/8GX 8GB DIMM DDR3 2133MT/s         | 1         | 2.33%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s       | 1         | 2.33%   |
| Kingston RAM 9965426-088.A00LF 4GB DIMM DDR3 1600MT/s        | 1         | 2.33%   |
| Kingston RAM 9965426-079.A00LF 4GB DIMM DDR3 1600MT/s        | 1         | 2.33%   |
| G.Skill RAM F5-6000J3040G32G 32GB DIMM DDR5 6000MT/s         | 1         | 2.33%   |
| G.Skill RAM F5-5600J2834F16G 16GB DIMM DDR5 5600MT/s         | 1         | 2.33%   |
| G.Skill RAM F4-4400C19-16GVK 16GB DIMM DDR4 4000MT/s         | 1         | 2.33%   |
| Crucial RAM CT16G4SFRA32A.M16FE 16GB SODIMM DDR4 3200MT/s    | 1         | 2.33%   |
| Crucial RAM BLS16G4D30AESB.M16FE 16GB DIMM DDR4 3200MT/s     | 1         | 2.33%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                  | 1         | 2.33%   |
| A-DATA RAM AX5U6000C3032G-BLABK 32GB DIMM DDR5 4800MT/s      | 1         | 2.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 13        | 39.39%  |
| DDR5   | 9         | 27.27%  |
| DDR3   | 7         | 21.21%  |
| LPDDR4 | 2         | 6.06%   |
| LPDDR5 | 1         | 3.03%   |
| DDR2   | 1         | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 15        | 44.12%  |
| DIMM         | 15        | 44.12%  |
| Row Of Chips | 4         | 11.76%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 13        | 36.11%  |
| 16384 | 9         | 25%     |
| 32768 | 7         | 19.44%  |
| 4096  | 4         | 11.11%  |
| 2048  | 2         | 5.56%   |
| 1024  | 1         | 2.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 11        | 31.43%  |
| 4800  | 5         | 14.29%  |
| 1600  | 5         | 14.29%  |
| 6000  | 2         | 5.71%   |
| 5600  | 2         | 5.71%   |
| 3600  | 2         | 5.71%   |
| 6400  | 1         | 2.86%   |
| 4267  | 1         | 2.86%   |
| 4000  | 1         | 2.86%   |
| 2667  | 1         | 2.86%   |
| 2400  | 1         | 2.86%   |
| 2133  | 1         | 2.86%   |
| 1333  | 1         | 2.86%   |
| 667   | 1         | 2.86%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)

![Printer Vendor](./All/images/line_chart/printer_vendor.svg)

| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)

![Printer Model](./All/images/line_chart/printer_model.svg)

| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP HP LaserJet M14-M17 | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)

![Camera Vendor](./All/images/line_chart/camera_vendor.svg)

| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 8         | 34.78%  |
| Sonix Technology              | 3         | 13.04%  |
| Sunplus Innovation Technology | 2         | 8.7%    |
| Luxvisions Innotech Limited   | 2         | 8.7%    |
| Logitech                      | 2         | 8.7%    |
| Quanta                        | 1         | 4.35%   |
| MacroSilicon                  | 1         | 4.35%   |
| Jieli Technology              | 1         | 4.35%   |
| IMC Networks                  | 1         | 4.35%   |
| Generalplus Technology        | 1         | 4.35%   |
| Bison Electronics             | 1         | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 4         | 17.39%  |
| Sonix USB2.0 HD UVC WebCam                        | 2         | 8.7%    |
| Sunplus Integrated_Webcam_FHD                     | 1         | 4.35%   |
| Sunplus DICOTA 4K                                 | 1         | 4.35%   |
| Sonix Integrated Webcam_FHD                       | 1         | 4.35%   |
| Quanta HD User Facing                             | 1         | 4.35%   |
| MacroSilicon USB Video                            | 1         | 4.35%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 1         | 4.35%   |
| Luxvisions Innotech Limited HP HD Camera          | 1         | 4.35%   |
| Logitech StreamCam                                | 1         | 4.35%   |
| Logitech HD Webcam C525                           | 1         | 4.35%   |
| Jieli USB PHY 2.0                                 | 1         | 4.35%   |
| IMC Networks Integrated Camera                    | 1         | 4.35%   |
| Generalplus GENERAL WEBCAM                        | 1         | 4.35%   |
| Chicony HP Truevision HD                          | 1         | 4.35%   |
| Chicony HD WebCam (Acer)                          | 1         | 4.35%   |
| Chicony Chicony USB2.0 Camera                     | 1         | 4.35%   |
| Chicony Chicony USB 2.0 Camera                    | 1         | 4.35%   |
| Bison Integrated Camera                           | 1         | 4.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 2         | 66.67%  |
| Shenzhen Goodix Technology | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Synaptics UWP WBDI Device           | 2         | 66.67%  |
| Shenzhen Goodix  FingerPrint Device | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./All/images/line_chart/chipcard_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 1         | 50%     |
| Advanced Card Systems | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Broadcom 58200                | 1         | 50%     |
| Advanced Card Systems ACR122U | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 16        | 45.71%  |
| 0     | 14        | 40%     |
| 3     | 2         | 5.71%   |
| 2     | 2         | 5.71%   |
| 5     | 1         | 2.86%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 5         | 16.67%  |
| Multimedia controller    | 4         | 13.33%  |
| Fingerprint reader       | 3         | 10%     |
| Communication controller | 3         | 10%     |
| Camera                   | 3         | 10%     |
| Bluetooth                | 3         | 10%     |
| Network                  | 2         | 6.67%   |
| Net/wireless             | 2         | 6.67%   |
| Chipcard                 | 2         | 6.67%   |
| Unassigned class         | 1         | 3.33%   |
| Sound                    | 1         | 3.33%   |
| Firewire controller      | 1         | 3.33%   |

