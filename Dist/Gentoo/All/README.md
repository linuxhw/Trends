Gentoo - Hardware Trends
------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Gentoo/Desktop/README.md) and [notebooks](/Dist/Gentoo/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: Sep, 2023.

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

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Gentoo 2.14 | 40        | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| Gentoo | 40        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 6.1.46-gentoo                      | 8         | 20%     |
| 6.1.53-gentoo-r1                   | 3         | 7.5%    |
| 6.5.1-gentoo                       | 2         | 5%      |
| 6.1.46-gentoo-dist                 | 2         | 5%      |
| 6.5.4-gentoo-x86_64                | 1         | 2.5%    |
| 6.5.4-gentoo                       | 1         | 2.5%    |
| 6.5.3-gentoo-dist                  | 1         | 2.5%    |
| 6.5.3-gentoo-ali                   | 1         | 2.5%    |
| 6.5.2-gentoo-x86_64                | 1         | 2.5%    |
| 6.5.2-gentoo                       | 1         | 2.5%    |
| 6.5.1-gentoo-x86_64                | 1         | 2.5%    |
| 6.5.0-gentoo                       | 1         | 2.5%    |
| 6.5.0-cachyos                      | 1         | 2.5%    |
| 6.4.14-gentoo-dist-hardened        | 1         | 2.5%    |
| 6.4.14-gentoo-dist                 | 1         | 2.5%    |
| 6.4.13-gentoo                      | 1         | 2.5%    |
| 6.4.11-gentoo-hardened1            | 1         | 2.5%    |
| 6.4.10-gentoo-x86_64               | 1         | 2.5%    |
| 6.3.9-zen1-flat                    | 1         | 2.5%    |
| 6.1.53-gentoo-x86_64               | 1         | 2.5%    |
| 6.1.53-gentoo-dist                 | 1         | 2.5%    |
| 6.1.50-gentoo                      | 1         | 2.5%    |
| 6.1.46-gentoo-x86_64               | 1         | 2.5%    |
| 6.1.46-gentoo-nouveau-01           | 1         | 2.5%    |
| 6.1.46-gentoo-fomys-work           | 1         | 2.5%    |
| 6.1.41-gentoo-gentoo-dist-hardened | 1         | 2.5%    |
| 6.1.1-gentoo-x86_64                | 1         | 2.5%    |
| 5.15.32-gentoo-r1-x86_64           | 1         | 2.5%    |
| 5.15.0-43-generic                  | 1         | 2.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.46  | 13        | 32.5%   |
| 6.1.53  | 5         | 12.5%   |
| 6.5.1   | 3         | 7.5%    |
| 6.5.4   | 2         | 5%      |
| 6.5.3   | 2         | 5%      |
| 6.5.2   | 2         | 5%      |
| 6.5.0   | 2         | 5%      |
| 6.4.14  | 2         | 5%      |
| 6.4.13  | 1         | 2.5%    |
| 6.4.11  | 1         | 2.5%    |
| 6.4.10  | 1         | 2.5%    |
| 6.3.9   | 1         | 2.5%    |
| 6.1.50  | 1         | 2.5%    |
| 6.1.41  | 1         | 2.5%    |
| 6.1.1   | 1         | 2.5%    |
| 5.15.32 | 1         | 2.5%    |
| 5.15.0  | 1         | 2.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 21        | 52.5%   |
| 6.5     | 11        | 27.5%   |
| 6.4     | 5         | 12.5%   |
| 5.15    | 2         | 5%      |
| 6.3     | 1         | 2.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 40        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Unknown  | 14        | 35%     |
| XFCE     | 8         | 20%     |
| KDE5     | 6         | 15%     |
| GNOME    | 4         | 10%     |
| MATE     | 2         | 5%      |
| Hyprland | 2         | 5%      |
| LXQt     | 1         | 2.5%    |
| i3       | 1         | 2.5%    |
| DWM      | 1         | 2.5%    |
| awesome  | 1         | 2.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 17        | 42.5%   |
| Tty     | 9         | 22.5%   |
| Wayland | 8         | 20%     |
| Unknown | 6         | 15%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 13        | 32.5%   |
| LightDM | 10        | 25%     |
| SDDM    | 9         | 22.5%   |
| SLiM    | 4         | 10%     |
| GREETD  | 3         | 7.5%    |
| GDM     | 1         | 2.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 15        | 37.5%   |
| de_DE   | 4         | 10%     |
| C.UTF8  | 4         | 10%     |
| Unknown | 4         | 10%     |
| fr_FR   | 3         | 7.5%    |
| en_GB   | 3         | 7.5%    |
| ru_RU   | 2         | 5%      |
| es_ES   | 2         | 5%      |
| en_IE   | 1         | 2.5%    |
| cs_CZ   | 1         | 2.5%    |
| C       | 1         | 2.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 30        | 75%     |
| BIOS | 10        | 25%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 21        | 52.5%   |
| Btrfs | 10        | 25%     |
| F2fs  | 4         | 10%     |
| Xfs   | 3         | 7.5%    |
| Zfs   | 2         | 5%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 34        | 85%     |
| MBR     | 3         | 7.5%    |
| Unknown | 3         | 7.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 28        | 70%     |
| Yes       | 12        | 30%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 87.5%   |
| Yes       | 5         | 12.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 9         | 22.5%   |
| Hewlett-Packard     | 7         | 17.5%   |
| Lenovo              | 6         | 15%     |
| Gigabyte Technology | 4         | 10%     |
| Dell                | 3         | 7.5%    |
| Timi                | 1         | 2.5%    |
| System76            | 1         | 2.5%    |
| Supermicro          | 1         | 2.5%    |
| MSI                 | 1         | 2.5%    |
| Fujitsu             | 1         | 2.5%    |
| Framework           | 1         | 2.5%    |
| Fanless Mini PC     | 1         | 2.5%    |
| BESSTAR Tech        | 1         | 2.5%    |
| ASRock              | 1         | 2.5%    |
| Apple               | 1         | 2.5%    |
| Acer                | 1         | 2.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Timi RedmiBook Pro 15S                    | 1         | 2.5%    |
| System76 Pangolin                         | 1         | 2.5%    |
| Supermicro SYS-5038MD-H24TRF-OS012        | 1         | 2.5%    |
| MSI MS-7D89                               | 1         | 2.5%    |
| Lenovo ThinkPad X1 Extreme 2nd 20QVS10E00 | 1         | 2.5%    |
| Lenovo ThinkPad T16 Gen 1 21CHCTO1WW      | 1         | 2.5%    |
| Lenovo ThinkPad T15p Gen 3 21DACTO1WW     | 1         | 2.5%    |
| Lenovo ThinkPad P43s 20RHCTO1WW           | 1         | 2.5%    |
| Lenovo ThinkPad E15 Gen 2 20T8000MPB      | 1         | 2.5%    |
| Lenovo Legion 5 15ACH6H 82JU              | 1         | 2.5%    |
| HP Z420 Workstation                       | 1         | 2.5%    |
| HP ProBook 450 G5                         | 1         | 2.5%    |
| HP ProBook 430 G5                         | 1         | 2.5%    |
| HP Laptop 14s-dq2xxx                      | 1         | 2.5%    |
| HP EliteBook 8540w                        | 1         | 2.5%    |
| HP EliteBook 845 G7 Notebook PC           | 1         | 2.5%    |
| HP EliteBook 830 G6                       | 1         | 2.5%    |
| Gigabyte B75M-D2V                         | 1         | 2.5%    |
| Gigabyte AORUS 17 XE4                     | 1         | 2.5%    |
| Gigabyte AB350-Gaming                     | 1         | 2.5%    |
| Gigabyte A520 AORUS ELITE                 | 1         | 2.5%    |
| Fujitsu ESPRIMO E700                      | 1         | 2.5%    |
| Framework Laptop (13th Gen Intel Core)    | 1         | 2.5%    |
| Fanless Mini PC PCG02 GLE                 | 1         | 2.5%    |
| Dell Precision M4800                      | 1         | 2.5%    |
| Dell Inspiron 531                         | 1         | 2.5%    |
| Dell Inspiron 16 5625                     | 1         | 2.5%    |
| BESSTAR Tech HM90                         | 1         | 2.5%    |
| ASUS ROG Zephyrus G14 GA401II_GA401II     | 1         | 2.5%    |
| ASUS ROG STRIX Z590-F GAMING WIFI         | 1         | 2.5%    |
| ASUS ROG STRIX X670E-F GAMING WIFI        | 1         | 2.5%    |
| ASUS ROG Strix G814JI_G814JI              | 1         | 2.5%    |
| ASUS PRIME Z690-P WIFI D4                 | 1         | 2.5%    |
| ASUS PRIME N100I-D D4                     | 1         | 2.5%    |
| ASUS PRIME H310M-E/BR                     | 1         | 2.5%    |
| ASUS PRIME B550M-K                        | 1         | 2.5%    |
| ASUS M3A78-CM                             | 1         | 2.5%    |
| ASRock B85M                               | 1         | 2.5%    |
| Apple MacBookPro11,2                      | 1         | 2.5%    |
| Acer Aspire A515-45                       | 1         | 2.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Lenovo ThinkPad                    | 5         | 12.5%   |
| ASUS ROG                           | 4         | 10%     |
| ASUS PRIME                         | 4         | 10%     |
| HP EliteBook                       | 3         | 7.5%    |
| HP ProBook                         | 2         | 5%      |
| Dell Inspiron                      | 2         | 5%      |
| Timi RedmiBook                     | 1         | 2.5%    |
| System76 Pangolin                  | 1         | 2.5%    |
| Supermicro SYS-5038MD-H24TRF-OS012 | 1         | 2.5%    |
| MSI MS-7D89                        | 1         | 2.5%    |
| Lenovo Legion                      | 1         | 2.5%    |
| HP Z420                            | 1         | 2.5%    |
| HP Laptop                          | 1         | 2.5%    |
| Gigabyte B75M-D2V                  | 1         | 2.5%    |
| Gigabyte AORUS                     | 1         | 2.5%    |
| Gigabyte AB350-Gaming              | 1         | 2.5%    |
| Gigabyte A520                      | 1         | 2.5%    |
| Fujitsu ESPRIMO                    | 1         | 2.5%    |
| Framework Laptop                   | 1         | 2.5%    |
| Fanless Mini PC PCG02              | 1         | 2.5%    |
| Dell Precision                     | 1         | 2.5%    |
| BESSTAR Tech HM90                  | 1         | 2.5%    |
| ASUS M3A78-CM                      | 1         | 2.5%    |
| ASRock B85M                        | 1         | 2.5%    |
| Apple MacBookPro11                 | 1         | 2.5%    |
| Acer Aspire                        | 1         | 2.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 9         | 22.5%   |
| 2022 | 5         | 12.5%   |
| 2023 | 4         | 10%     |
| 2020 | 4         | 10%     |
| 2019 | 3         | 7.5%    |
| 2018 | 3         | 7.5%    |
| 2017 | 3         | 7.5%    |
| 2013 | 3         | 7.5%    |
| 2012 | 2         | 5%      |
| 2011 | 1         | 2.5%    |
| 2010 | 1         | 2.5%    |
| 2008 | 1         | 2.5%    |
| 2007 | 1         | 2.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 22        | 55%     |
| Desktop  | 17        | 42.5%   |
| Stick pc | 1         | 2.5%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 38        | 95%     |
| Enabled  | 2         | 5%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 40        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 16        | 40%     |
| 4.01-8.0    | 7         | 17.5%   |
| 64.01-256.0 | 5         | 12.5%   |
| 8.01-16.0   | 5         | 12.5%   |
| 16.01-24.0  | 4         | 10%     |
| 24.01-32.0  | 2         | 5%      |
| 3.01-4.0    | 1         | 2.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 8         | 20%     |
| 2.01-3.0   | 8         | 20%     |
| 1.01-2.0   | 8         | 20%     |
| 3.01-4.0   | 6         | 15%     |
| 0.51-1.0   | 4         | 10%     |
| 8.01-16.0  | 3         | 7.5%    |
| 16.01-24.0 | 2         | 5%      |
| 0.01-0.5   | 1         | 2.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 52.5%   |
| 2      | 14        | 35%     |
| 3      | 4         | 10%     |
| 6      | 1         | 2.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 77.5%   |
| Yes       | 9         | 22.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 87.5%   |
| No        | 5         | 12.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 65%     |
| No        | 14        | 35%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 62.5%   |
| No        | 15        | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country     | Computers | Percent |
|-------------|-----------|---------|
| Germany     | 7         | 17.5%   |
| USA         | 5         | 12.5%   |
| Poland      | 5         | 12.5%   |
| UK          | 4         | 10%     |
| Spain       | 4         | 10%     |
| Russia      | 3         | 7.5%    |
| France      | 3         | 7.5%    |
| Netherlands | 2         | 5%      |
| Sweden      | 1         | 2.5%    |
| Portugal    | 1         | 2.5%    |
| Ireland     | 1         | 2.5%    |
| Iran        | 1         | 2.5%    |
| China       | 1         | 2.5%    |
| Canada      | 1         | 2.5%    |
| Brazil      | 1         | 2.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City             | Computers | Percent |
|------------------|-----------|---------|
| Warsaw           | 3         | 7.5%    |
| Krefeld          | 2         | 5%      |
| Cieszyn          | 2         | 5%      |
| Xiaolou          | 1         | 2.5%    |
| Ufa              | 1         | 2.5%    |
| Toulouse         | 1         | 2.5%    |
| Torredembarra    | 1         | 2.5%    |
| Stockholm        | 1         | 2.5%    |
| St Petersburg    | 1         | 2.5%    |
| Purmerend        | 1         | 2.5%    |
| Port Glasgow     | 1         | 2.5%    |
| Olympia          | 1         | 2.5%    |
| Nuremberg        | 1         | 2.5%    |
| Moscow           | 1         | 2.5%    |
| Mönchengladbach | 1         | 2.5%    |
| Mogi das Cruzes  | 1         | 2.5%    |
| Marshall         | 1         | 2.5%    |
| Madrid           | 1         | 2.5%    |
| London           | 1         | 2.5%    |
| Lisbon           | 1         | 2.5%    |
| Lesigny          | 1         | 2.5%    |
| Leeds            | 1         | 2.5%    |
| Ivry-sur-Seine   | 1         | 2.5%    |
| Isle of Lewis    | 1         | 2.5%    |
| Isfahan          | 1         | 2.5%    |
| Huntsville       | 1         | 2.5%    |
| Girona           | 1         | 2.5%    |
| Dumfries         | 1         | 2.5%    |
| Dublin           | 1         | 2.5%    |
| Detmold          | 1         | 2.5%    |
| Cologne          | 1         | 2.5%    |
| Carlsbad         | 1         | 2.5%    |
| Berlin           | 1         | 2.5%    |
| Arona            | 1         | 2.5%    |
| Amsterdam        | 1         | 2.5%    |
| Ajax             | 1         | 2.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 12        | 16     | 19.35%  |
| Seagate                     | 6         | 6      | 9.68%   |
| Sandisk                     | 6         | 6      | 9.68%   |
| Phison Electronics          | 5         | 5      | 8.06%   |
| Micron Technology           | 3         | 4      | 4.84%   |
| Intel                       | 3         | 3      | 4.84%   |
| GOODRAM                     | 3         | 3      | 4.84%   |
| WDC                         | 2         | 2      | 3.23%   |
| Toshiba                     | 2         | 2      | 3.23%   |
| SK hynix                    | 2         | 2      | 3.23%   |
| KIOXIA                      | 2         | 2      | 3.23%   |
| Hitachi                     | 2         | 4      | 3.23%   |
| Crucial                     | 2         | 2      | 3.23%   |
| Yangtze Memory Technologies | 1         | 1      | 1.61%   |
| Unknown                     | 1         | 1      | 1.61%   |
| Union Memory                | 1         | 1      | 1.61%   |
| Teleplan                    | 1         | 1      | 1.61%   |
| SPCC                        | 1         | 1      | 1.61%   |
| SABRENT                     | 1         | 1      | 1.61%   |
| Micron/Crucial Technology   | 1         | 1      | 1.61%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 1.61%   |
| Kingston                    | 1         | 2      | 1.61%   |
| Kingchuxing                 | 1         | 1      | 1.61%   |
| China                       | 1         | 1      | 1.61%   |
| Unknown                     | 1         | 1      | 1.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 4         | 6.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 3         | 4.76%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 2         | 3.17%   |
| SanDisk SSD PLUS 240GB                              | 2         | 3.17%   |
| Samsung SSD 860 EVO 500GB                           | 2         | 3.17%   |
| Intel SSD 660P Series 1024GB                        | 2         | 3.17%   |
| GOODRAM SSDPR-CL100-480-G2 480GB                    | 2         | 3.17%   |
| Yangtze Memory ZHITAI TiPlus5000 1TB                | 1         | 1.59%   |
| WDC WD3200AAJS-00L7A0 320GB                         | 1         | 1.59%   |
| WDC WD10EALX-009BA0 1TB                             | 1         | 1.59%   |
| Unknown MMC Card  128GB                             | 1         | 1.59%   |
| Union Memory UMIS RPJTJ512MEE1OWX 512GB             | 1         | 1.59%   |
| Toshiba HDWE150 5TB                                 | 1         | 1.59%   |
| Toshiba HDWD240 4TB                                 | 1         | 1.59%   |
| Teleplan TP1000G 1TB                                | 1         | 1.59%   |
| SPCC Solid State Disk 1TB                           | 1         | 1.59%   |
| SK hynix SKHynix_HFS512GD9TNG-L5B0B 512GB           | 1         | 1.59%   |
| SK hynix PC401 NVMe Solid State Drive 256GB         | 1         | 1.59%   |
| Seagate ST6000DM003-2CY186 6TB                      | 1         | 1.59%   |
| Seagate ST4000DM004-2CV104 4TB                      | 1         | 1.59%   |
| Seagate ST2000DM005-2CW102 2TB                      | 1         | 1.59%   |
| Seagate ST2000DL003-9VT166 2TB                      | 1         | 1.59%   |
| Seagate ST18000NM003D-3DL103 18TB                   | 1         | 1.59%   |
| Seagate ST12000NM0008-2H3101 12TB                   | 1         | 1.59%   |
| Sandisk WD_BLACK SN850X 2000GB                      | 1         | 1.59%   |
| Sandisk WD Blue SN570 1TB                           | 1         | 1.59%   |
| Samsung SSD 980 1TB                                 | 1         | 1.59%   |
| Samsung SSD 860 QVO 2TB                             | 1         | 1.59%   |
| Samsung SSD 850 EVO 500GB                           | 1         | 1.59%   |
| Samsung MZVLQ256HAJD-000H1 256GB                    | 1         | 1.59%   |
| SABRENT Disk 752GB                                  | 1         | 1.59%   |
| Phison PS5013 E13 NVMe Controller 512GB             | 1         | 1.59%   |
| Phison PCIe SSD 1TB                                 | 1         | 1.59%   |
| Phison ESR01TBMFCT-E8GBTOEM4                        | 1         | 1.59%   |
| Phison E12 NVMe Controller 2TB                      | 1         | 1.59%   |
| Phison Corsair MP600 PRO XT 2TB                     | 1         | 1.59%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 1         | 1.59%   |
| Micron MTFDKBA256TFK 256GB                          | 1         | 1.59%   |
| Micron 2400_MTFDKBA1T0QFM 1024GB                    | 1         | 1.59%   |
| Micron 2210_MTFDHBA512QFD 512GB                     | 1         | 1.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 6         | 6      | 42.86%  |
| WDC      | 2         | 2      | 14.29%  |
| Toshiba  | 2         | 2      | 14.29%  |
| Hitachi  | 2         | 4      | 14.29%  |
| Teleplan | 1         | 1      | 7.14%   |
| SABRENT  | 1         | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 5      | 26.67%  |
| GOODRAM             | 3         | 3      | 20%     |
| SanDisk             | 2         | 2      | 13.33%  |
| Crucial             | 2         | 2      | 13.33%  |
| SPCC                | 1         | 1      | 6.67%   |
| Kingchuxing         | 1         | 1      | 6.67%   |
| China               | 1         | 1      | 6.67%   |
| Unknown             | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 27        | 37     | 52.94%  |
| SSD  | 13        | 16     | 25.49%  |
| HDD  | 10        | 16     | 19.61%  |
| MMC  | 1         | 1      | 1.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 27        | 37     | 57.45%  |
| SATA | 18        | 31     | 38.3%   |
| SAS  | 1         | 1      | 2.13%   |
| MMC  | 1         | 1      | 2.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 11        | 12     | 39.29%  |
| 0.51-1.0   | 8         | 8      | 28.57%  |
| 3.01-4.0   | 2         | 2      | 7.14%   |
| 10.01-20.0 | 2         | 2      | 7.14%   |
| 1.01-2.0   | 2         | 3      | 7.14%   |
| 4.01-10.0  | 2         | 2      | 7.14%   |
| 2.01-3.0   | 1         | 3      | 3.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 11        | 27.5%   |
| More than 3000 | 8         | 20%     |
| 251-500        | 6         | 15%     |
| 1001-2000      | 4         | 10%     |
| Unknown        | 4         | 10%     |
| 101-250        | 3         | 7.5%    |
| 1-20           | 2         | 5%      |
| 51-100         | 2         | 5%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 7         | 17.5%   |
| More than 3000 | 6         | 15%     |
| 251-500        | 5         | 12.5%   |
| 21-50          | 5         | 12.5%   |
| 101-250        | 5         | 12.5%   |
| 501-1000       | 5         | 12.5%   |
| Unknown        | 4         | 10%     |
| 51-100         | 2         | 5%      |
| 1001-2000      | 1         | 2.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Toshiba HDWD240 4TB            | 1         | 1      | 50%     |
| Seagate ST2000DM005-2CW102 2TB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

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

![Drive Status](./images/pie_chart/drive_status.svg)

![Drive Status](./images/line_chart/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 36        | 56     | 81.82%  |
| Detected | 6         | 12     | 13.64%  |
| Malfunc  | 2         | 2      | 4.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 18        | 30%     |
| AMD                         | 11        | 18.33%  |
| Samsung Electronics         | 8         | 13.33%  |
| Phison Electronics          | 5         | 8.33%   |
| SanDisk                     | 4         | 6.67%   |
| Micron Technology           | 3         | 5%      |
| SK hynix                    | 2         | 3.33%   |
| KIOXIA                      | 2         | 3.33%   |
| ASMedia Technology          | 2         | 3.33%   |
| Union Memory (Shenzhen)     | 1         | 1.67%   |
| Nvidia                      | 1         | 1.67%   |
| Micron/Crucial Technology   | 1         | 1.67%   |
| MAXIO Technology (Hangzhou) | 1         | 1.67%   |
| Kingston Technology Company | 1         | 1.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 11.59%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 5.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 4.35%   |
| Phison E18 PCIe4 NVMe Controller                                               | 3         | 4.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 4.35%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 2.9%    |
| Samsung NVMe SSD Controller 980                                                | 2         | 2.9%    |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.9%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.9%    |
| Intel SSD 660P Series                                                          | 2         | 2.9%    |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 2.9%    |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 512GB                          | 1         | 1.45%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 1         | 1.45%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 1.45%   |
| Sandisk Western Digital WD Black SN850X NVMe SSD                               | 1         | 1.45%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1         | 1.45%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.45%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.45%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 1.45%   |
| Nvidia MCP61 IDE                                                               | 1         | 1.45%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 1.45%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 1         | 1.45%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 1         | 1.45%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 1         | 1.45%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1         | 1.45%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 1         | 1.45%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 1.45%   |
| Kingston Company KC3000/Renegade NVMe SSD                                      | 1         | 1.45%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 1         | 1.45%   |
| Intel SSD 600P Series                                                          | 1         | 1.45%   |
| Intel SATA controller                                                          | 1         | 1.45%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.45%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 1.45%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 1         | 1.45%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 1         | 1.45%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 1         | 1.45%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1         | 1.45%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                           | 1         | 1.45%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 26        | 44.07%  |
| SATA | 26        | 44.07%  |
| RAID | 3         | 5.08%   |
| IDE  | 3         | 5.08%   |
| SAS  | 1         | 1.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 24        | 60%     |
| AMD    | 16        | 40%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-12700H              | 2         | 5%      |
| AMD Ryzen 7 5800H with Radeon Graphics     | 2         | 5%      |
| Intel Xeon CPU E5-1680 v2 @ 3.00GHz        | 1         | 2.5%    |
| Intel Xeon CPU D-1531 @ 2.20GHz            | 1         | 2.5%    |
| Intel N100                                 | 1         | 2.5%    |
| Intel Core i9-10850K CPU @ 3.60GHz         | 1         | 2.5%    |
| Intel Core i7-9750H CPU @ 2.60GHz          | 1         | 2.5%    |
| Intel Core i7-8700 CPU @ 3.20GHz           | 1         | 2.5%    |
| Intel Core i7-8665U CPU @ 1.90GHz          | 1         | 2.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz          | 1         | 2.5%    |
| Intel Core i7-4910MQ CPU @ 2.90GHz         | 1         | 2.5%    |
| Intel Core i7-4750HQ CPU @ 2.00GHz         | 1         | 2.5%    |
| Intel Core i7-2600 CPU @ 3.40GHz           | 1         | 2.5%    |
| Intel Core i7 CPU M 620 @ 2.67GHz          | 1         | 2.5%    |
| Intel Core i5-8365U CPU @ 1.60GHz          | 1         | 2.5%    |
| Intel Core i5-8250U CPU @ 1.60GHz          | 1         | 2.5%    |
| Intel Core i5-2400 CPU @ 3.10GHz           | 1         | 2.5%    |
| Intel Core i3-4130 CPU @ 3.40GHz           | 1         | 2.5%    |
| Intel Celeron J4125 CPU @ 2.00GHz          | 1         | 2.5%    |
| Intel 13th Gen Core i9-13980HX             | 1         | 2.5%    |
| Intel 13th Gen Core i9-13900               | 1         | 2.5%    |
| Intel 13th Gen Core i7-1370P               | 1         | 2.5%    |
| Intel 12th Gen Core i5-12600K              | 1         | 2.5%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 1         | 2.5%    |
| AMD Ryzen 9 7900X 12-Core Processor        | 1         | 2.5%    |
| AMD Ryzen 9 4900H with Radeon Graphics     | 1         | 2.5%    |
| AMD Ryzen 7 PRO 6850U with Radeon Graphics | 1         | 2.5%    |
| AMD Ryzen 7 6800U with Radeon Graphics     | 1         | 2.5%    |
| AMD Ryzen 7 5825U with Radeon Graphics     | 1         | 2.5%    |
| AMD Ryzen 7 5800X 8-Core Processor         | 1         | 2.5%    |
| AMD Ryzen 7 5700G with Radeon Graphics     | 1         | 2.5%    |
| AMD Ryzen 7 4800HS with Radeon Graphics    | 1         | 2.5%    |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics | 1         | 2.5%    |
| AMD Ryzen 5 5500U with Radeon Graphics     | 1         | 2.5%    |
| AMD Ryzen 5 4500U with Radeon Graphics     | 1         | 2.5%    |
| AMD Ryzen 5 2600 Six-Core Processor        | 1         | 2.5%    |
| AMD Phenom II X4 955 Processor             | 1         | 2.5%    |
| AMD Athlon 64 X2 Dual Core Processor 5000+ | 1         | 2.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model            | Computers | Percent |
|------------------|-----------|---------|
| Other            | 8         | 20%     |
| Intel Core i7    | 8         | 20%     |
| AMD Ryzen 7      | 7         | 17.5%   |
| Intel Core i5    | 3         | 7.5%    |
| AMD Ryzen 5      | 3         | 7.5%    |
| Intel Xeon       | 2         | 5%      |
| AMD Ryzen 9      | 2         | 5%      |
| Intel Core i9    | 1         | 2.5%    |
| Intel Core i3    | 1         | 2.5%    |
| Intel Celeron    | 1         | 2.5%    |
| AMD Ryzen 7 PRO  | 1         | 2.5%    |
| AMD Ryzen 5 PRO  | 1         | 2.5%    |
| AMD Phenom II X4 | 1         | 2.5%    |
| AMD Athlon 64 X2 | 1         | 2.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 12        | 30%     |
| 8      | 10        | 25%     |
| 6      | 7         | 17.5%   |
| 14     | 3         | 7.5%    |
| 24     | 2         | 5%      |
| 10     | 2         | 5%      |
| 2      | 2         | 5%      |
| 12     | 1         | 2.5%    |
| 1      | 1         | 2.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 40        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 32        | 80%     |
| 1      | 7         | 17.5%   |
| 4      | 1         | 2.5%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 40        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 32.5%   |
| 0x806ea    | 2         | 5%      |
| 0x0a50000d | 2         | 5%      |
| 0x0a50000c | 2         | 5%      |
| 0x0a404102 | 2         | 5%      |
| 0xb06e0    | 1         | 2.5%    |
| 0xb06a2    | 1         | 2.5%    |
| 0xb0671    | 1         | 2.5%    |
| 0x906ea    | 1         | 2.5%    |
| 0x906a3    | 1         | 2.5%    |
| 0x90672    | 1         | 2.5%    |
| 0x806ec    | 1         | 2.5%    |
| 0x806c1    | 1         | 2.5%    |
| 0x706a8    | 1         | 2.5%    |
| 0x50663    | 1         | 2.5%    |
| 0x306e4    | 1         | 2.5%    |
| 0x306c3    | 1         | 2.5%    |
| 0x0a601203 | 1         | 2.5%    |
| 0x0a20120a | 1         | 2.5%    |
| 0x08608102 | 1         | 2.5%    |
| 0x08600106 | 1         | 2.5%    |
| 0x08600104 | 1         | 2.5%    |
| 0x08600103 | 1         | 2.5%    |
| 0x0800820d | 1         | 2.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 6         | 15%     |
| Unknown          | 6         | 15%     |
| Zen 3            | 5         | 12.5%   |
| Zen 2            | 4         | 10%     |
| Alderlake Hybrid | 4         | 10%     |
| Haswell          | 3         | 7.5%    |
| SandyBridge      | 2         | 5%      |
| Zen+             | 1         | 2.5%    |
| Westmere         | 1         | 2.5%    |
| TigerLake        | 1         | 2.5%    |
| K8 Hammer        | 1         | 2.5%    |
| K10              | 1         | 2.5%    |
| IvyBridge        | 1         | 2.5%    |
| Gracemont        | 1         | 2.5%    |
| Goldmont plus    | 1         | 2.5%    |
| CometLake        | 1         | 2.5%    |
| Broadwell        | 1         | 2.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| AMD               | 17        | 34%     |
| Nvidia            | 16        | 32%     |
| Intel             | 16        | 32%     |
| ASPEED Technology | 1         | 2%      |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                | 4         | 7.84%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                            | 3         | 5.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 5.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 3.92%   |
| Intel UHD Graphics 620                                                    | 2         | 3.92%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 2         | 3.92%   |
| AMD Rembrandt [Radeon 680M]                                               | 2         | 3.92%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 2         | 3.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 1.96%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                | 1         | 1.96%   |
| Nvidia GT216GLM [Quadro FX 880M]                                          | 1         | 1.96%   |
| Nvidia GP108GLM [Quadro P520]                                             | 1         | 1.96%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 1         | 1.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 1         | 1.96%   |
| Nvidia GM108M [GeForce 930MX]                                             | 1         | 1.96%   |
| Nvidia GK208B [GeForce GT 710]                                            | 1         | 1.96%   |
| Nvidia GK106GLM [Quadro K2100M]                                           | 1         | 1.96%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 1.96%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 1         | 1.96%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                             | 1         | 1.96%   |
| Nvidia GA104 [GeForce RTX 3060 Ti GDDR6X]                                 | 1         | 1.96%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                        | 1         | 1.96%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                    | 1         | 1.96%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                           | 1         | 1.96%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 1.96%   |
| Intel Raptor Lake-S UHD Graphics                                          | 1         | 1.96%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                | 1         | 1.96%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 1         | 1.96%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 1.96%   |
| Intel Crystal Well Integrated Graphics Controller                         | 1         | 1.96%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1         | 1.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 1.96%   |
| Intel Alder Lake-N [UHD Graphics]                                         | 1         | 1.96%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1         | 1.96%   |
| ASPEED Technology ASPEED Graphics Family                                  | 1         | 1.96%   |
| AMD RS780C [Radeon 3100]                                                  | 1         | 1.96%   |
| AMD Lucienne                                                              | 1         | 1.96%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                        | 1         | 1.96%   |
| AMD Barcelo                                                               | 1         | 1.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 15        | 37.5%   |
| Intel + Nvidia | 8         | 20%     |
| 1 x Intel      | 8         | 20%     |
| 1 x Nvidia     | 6         | 15%     |
| AMD + Nvidia   | 2         | 5%      |
| 1 x ASPEED     | 1         | 2.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 29        | 72.5%   |
| Proprietary | 8         | 20%     |
| Unknown     | 3         | 7.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 55%     |
| 0.01-0.5   | 7         | 17.5%   |
| 1.01-2.0   | 3         | 7.5%    |
| 8.01-16.0  | 3         | 7.5%    |
| 0.51-1.0   | 3         | 7.5%    |
| 7.01-8.0   | 1         | 2.5%    |
| 3.01-4.0   | 1         | 2.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 14.58%  |
| AU Optronics        | 7         | 14.58%  |
| Goldstar            | 5         | 10.42%  |
| Dell                | 3         | 6.25%   |
| Chimei Innolux      | 3         | 6.25%   |
| BOE                 | 3         | 6.25%   |
| Philips             | 2         | 4.17%   |
| PANDA               | 2         | 4.17%   |
| LG Display          | 2         | 4.17%   |
| Iiyama              | 2         | 4.17%   |
| BenQ                | 2         | 4.17%   |
| Unknown             | 1         | 2.08%   |
| UGD                 | 1         | 2.08%   |
| Toshiba             | 1         | 2.08%   |
| TMX                 | 1         | 2.08%   |
| Sharp               | 1         | 2.08%   |
| Lenovo              | 1         | 2.08%   |
| Hewlett-Packard     | 1         | 2.08%   |
| Eizo                | 1         | 2.08%   |
| Apple               | 1         | 2.08%   |
| AOC                 | 1         | 2.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 1         | 2%      |
| UGD Artist13.3pro UGD1302 1920x1080 294x165mm 13.3-inch                 | 1         | 2%      |
| Toshiba TV TSB0108 1920x540                                             | 1         | 2%      |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch                 | 1         | 2%      |
| Sharp LQ173M1JW12 SHP1563 1920x1080 382x215mm 17.3-inch                 | 1         | 2%      |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch    | 1         | 2%      |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch     | 1         | 2%      |
| Samsung Electronics SMS27A650 SAM082E 1920x1080 598x336mm 27.0-inch     | 1         | 2%      |
| Samsung Electronics S22C200 SAM09B6 1920x1080 477x268mm 21.5-inch       | 1         | 2%      |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch       | 1         | 2%      |
| Samsung Electronics LS28AG700N SAM7177 3840x2160 632x360mm 28.6-inch    | 1         | 2%      |
| Samsung Electronics LCD Monitor SAM7003 3840x2160 1872x1053mm 84.6-inch | 1         | 2%      |
| Philips PHL 288P6L PHL08F2 3840x2160 621x341mm 27.9-inch                | 1         | 2%      |
| Philips PHL 278E8Q PHLC161 1920x1080 598x336mm 27.0-inch                | 1         | 2%      |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch                 | 1         | 2%      |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                 | 1         | 2%      |
| LG Display LCD Monitor LGD06CA 1920x1080 309x174mm 14.0-inch            | 1         | 2%      |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch            | 1         | 2%      |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                | 1         | 2%      |
| Iiyama PL2783Q IVM661F 2560x1440 597x336mm 27.0-inch                    | 1         | 2%      |
| Iiyama PL2209HD IVM560B 1920x1080 478x269mm 21.6-inch                   | 1         | 2%      |
| Hewlett-Packard 22er HWP331B 1920x1080 476x268mm 21.5-inch              | 1         | 2%      |
| Goldstar ULTRAWIDE GSM5AFB 2560x1080 798x334mm 34.1-inch                | 1         | 2%      |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                | 1         | 2%      |
| Goldstar ULTRAGEAR GSM775C 1920x1080 698x393mm 31.5-inch                | 1         | 2%      |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                    | 1         | 2%      |
| Goldstar LG HDR 4K GSM774F 3840x2160 700x400mm 31.7-inch                | 1         | 2%      |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                  | 1         | 2%      |
| Eizo L557 ENC1690 1280x1024 337x270mm 17.0-inch                         | 1         | 2%      |
| Eizo L557 ENC1689 1280x1024 337x270mm 17.0-inch                         | 1         | 2%      |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                        | 1         | 2%      |
| Dell U2410 DELF016 1920x1200 520x320mm 24.0-inch                        | 1         | 2%      |
| Dell P2418D DELD0C2 2560x1440 526x296mm 23.8-inch                       | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN1614 1920x1200 344x215mm 16.0-inch        | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN1613 1920x1200 344x215mm 16.0-inch        | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 1         | 2%      |
| BOE NE180QDM-NZ2 BOE0B35 2560x1600 388x242mm 18.0-inch                  | 1         | 2%      |
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                   | 1         | 2%      |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                   | 1         | 2%      |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                      | 1         | 2%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 21        | 51.22%  |
| 3840x2160 (4K)    | 6         | 14.63%  |
| 1920x1200 (WUXGA) | 3         | 7.32%   |
| 2560x1440 (QHD)   | 2         | 4.88%   |
| 3200x2000         | 1         | 2.44%   |
| 2880x1800         | 1         | 2.44%   |
| 2560x1600         | 1         | 2.44%   |
| 2560x1080         | 1         | 2.44%   |
| 2288x1287         | 1         | 2.44%   |
| 2256x1504         | 1         | 2.44%   |
| 1920x540          | 1         | 2.44%   |
| 1366x768 (WXGA)   | 1         | 2.44%   |
| 1280x1024 (SXGA)  | 1         | 2.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 10        | 21.74%  |
| 27     | 5         | 10.87%  |
| 21     | 5         | 10.87%  |
| 24     | 4         | 8.7%    |
| 14     | 4         | 8.7%    |
| 13     | 4         | 8.7%    |
| 31     | 2         | 4.35%   |
| 17     | 2         | 4.35%   |
| 16     | 2         | 4.35%   |
| 142    | 1         | 2.17%   |
| 84     | 1         | 2.17%   |
| 72     | 1         | 2.17%   |
| 34     | 1         | 2.17%   |
| 32     | 1         | 2.17%   |
| 28     | 1         | 2.17%   |
| 23     | 1         | 2.17%   |
| 18     | 1         | 2.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 17        | 37.78%  |
| 501-600        | 8         | 17.78%  |
| 401-500        | 6         | 13.33%  |
| 201-300        | 4         | 8.89%   |
| 601-700        | 3         | 6.67%   |
| 701-800        | 2         | 4.44%   |
| 351-400        | 2         | 4.44%   |
| 1501-2000      | 2         | 4.44%   |
| More than 2000 | 1         | 2.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 28        | 71.79%  |
| 16/10 | 7         | 17.95%  |
| 5/4   | 1         | 2.56%   |
| 3/2   | 1         | 2.56%   |
| 21/9  | 1         | 2.56%   |
| 1.00  | 1         | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 21.74%  |
| 201-250        | 7         | 15.22%  |
| 81-90          | 5         | 10.87%  |
| 301-350        | 5         | 10.87%  |
| 351-500        | 4         | 8.7%    |
| More than 1000 | 3         | 6.52%   |
| 71-80          | 3         | 6.52%   |
| 251-300        | 2         | 4.35%   |
| 151-200        | 2         | 4.35%   |
| 141-150        | 2         | 4.35%   |
| 111-120        | 2         | 4.35%   |
| 121-130        | 1         | 2.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 19        | 40.43%  |
| 51-100        | 12        | 25.53%  |
| 101-120       | 7         | 14.89%  |
| 161-240       | 5         | 10.64%  |
| More than 240 | 2         | 4.26%   |
| 1-50          | 2         | 4.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 26        | 65%     |
| 2     | 6         | 15%     |
| 3     | 4         | 10%     |
| 0     | 4         | 10%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 24        | 40.68%  |
| Intel                 | 23        | 38.98%  |
| MediaTek              | 4         | 6.78%   |
| ASIX Electronics      | 3         | 5.08%   |
| Broadcom              | 2         | 3.39%   |
| Samsung Electronics   | 1         | 1.69%   |
| Qualcomm              | 1         | 1.69%   |
| Nvidia                | 1         | 1.69%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 27.54%  |
| Intel Wi-Fi 6 AX200                                               | 4         | 5.8%    |
| Intel Ethernet Controller I225-V                                  | 3         | 4.35%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 4.35%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.9%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2         | 2.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 2.9%    |
| Intel Wireless 8265 / 8275                                        | 2         | 2.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 2.9%    |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 2.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 2.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 2.9%    |
| Intel 700 Series Chipset Family Wi-Fi                             | 2         | 2.9%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.45%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 1.45%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.45%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 1         | 1.45%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.45%   |
| Intel Wireless 7260                                               | 1         | 1.45%   |
| Intel Wireless 3165                                               | 1         | 1.45%   |
| Intel I350 Gigabit Network Connection                             | 1         | 1.45%   |
| Intel Ethernet Controller I226-V                                  | 1         | 1.45%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.45%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.45%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.45%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.45%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1         | 1.45%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.45%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.45%   |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                       | 1         | 1.45%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 69.23%  |
| MediaTek              | 4         | 15.38%  |
| Realtek Semiconductor | 2         | 7.69%   |
| Qualcomm              | 1         | 3.85%   |
| Broadcom              | 1         | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 4         | 15.38%  |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 2         | 7.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 7.69%   |
| Intel Wireless 8265 / 8275                                    | 2         | 7.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2         | 7.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 2         | 7.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 2         | 7.69%   |
| Intel 700 Series Chipset Family Wi-Fi                         | 2         | 7.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 3.85%   |
| Qualcomm QCNFA765 Wireless Network Adapter                    | 1         | 3.85%   |
| Intel Wireless 7260                                           | 1         | 3.85%   |
| Intel Wireless 3165                                           | 1         | 3.85%   |
| Intel Centrino Ultimate-N 6300                                | 1         | 3.85%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 1         | 3.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 1         | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 23        | 54.76%  |
| Intel                 | 13        | 30.95%  |
| ASIX Electronics      | 3         | 7.14%   |
| Samsung Electronics   | 1         | 2.38%   |
| Nvidia                | 1         | 2.38%   |
| Broadcom              | 1         | 2.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 44.19%  |
| Intel Ethernet Controller I225-V                                  | 3         | 6.98%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 6.98%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 4.65%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 4.65%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.33%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 2.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.33%   |
| Nvidia MCP61 Ethernet                                             | 1         | 2.33%   |
| Intel I350 Gigabit Network Connection                             | 1         | 2.33%   |
| Intel Ethernet Controller I226-V                                  | 1         | 2.33%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.33%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 2.33%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 2.33%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.33%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.33%   |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                       | 1         | 2.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 35        | 57.38%  |
| WiFi     | 26        | 42.62%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 56.41%  |
| Ethernet | 17        | 43.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 21        | 52.5%   |
| 1     | 16        | 40%     |
| 7     | 1         | 2.5%    |
| 3     | 1         | 2.5%    |
| 0     | 1         | 2.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 30        | 75%     |
| Yes  | 10        | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 16        | 64%     |
| Realtek Semiconductor   | 2         | 8%      |
| MediaTek                | 2         | 8%      |
| USI                     | 1         | 4%      |
| Lite-On Technology      | 1         | 4%      |
| Foxconn / Hon Hai       | 1         | 4%      |
| Cambridge Silicon Radio | 1         | 4%      |
| Apple                   | 1         | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 16%     |
| Intel Bluetooth Device                              | 4         | 16%     |
| Intel AX200 Bluetooth                               | 3         | 12%     |
| Realtek Bluetooth Radio                             | 2         | 8%      |
| MediaTek Wireless_Device                            | 2         | 8%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 8%      |
| Intel AX210 Bluetooth                               | 2         | 8%      |
| USI Bluetooth Device                                | 1         | 4%      |
| Lite-On Wireless_Device                             | 1         | 4%      |
| Intel AX201 Bluetooth                               | 1         | 4%      |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth         | 1         | 4%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4%      |
| Apple Bluetooth Host Controller                     | 1         | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 23        | 34.85%  |
| AMD                                  | 18        | 27.27%  |
| Nvidia                               | 13        | 19.7%   |
| C-Media Electronics                  | 2         | 3.03%   |
| Thesycon Systemsoftware & Consulting | 1         | 1.52%   |
| SteelSeries ApS                      | 1         | 1.52%   |
| Realtek Semiconductor                | 1         | 1.52%   |
| Razer USA                            | 1         | 1.52%   |
| Micro Star International             | 1         | 1.52%   |
| JBL                                  | 1         | 1.52%   |
| Generalplus Technology               | 1         | 1.52%   |
| FIFINE Microphones                   | 1         | 1.52%   |
| ASUSTek Computer                     | 1         | 1.52%   |
| AKG C44-USB Microphone               | 1         | 1.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 13.92%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 10.13%  |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 3.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 3.8%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 3.8%    |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 2.53%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2.53%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 2.53%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 2.53%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 2         | 2.53%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2         | 2.53%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 2.53%   |
| Thesycon Systemsoftware & Consulting SABAJ USB AUDIO                       | 1         | 1.27%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                              | 1         | 1.27%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.27%   |
| Razer USA Kraken Tournament Edition                                        | 1         | 1.27%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.27%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.27%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 1.27%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.27%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.27%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.27%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 1.27%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 1.27%   |
| Nvidia Audio device                                                        | 1         | 1.27%   |
| Micro Star International USB Audio                                         | 1         | 1.27%   |
| JBL Quantum 400                                                            | 1         | 1.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.27%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 1.27%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 1         | 1.27%   |
| Intel Crystal Well HD Audio Controller                                     | 1         | 1.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.27%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1         | 1.27%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1         | 1.27%   |
| Intel Alder Lake-N HD Graphics SGPC                                        | 1         | 1.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.27%   |
| Generalplus Technology USB Audio Device                                    | 1         | 1.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 9         | 21.95%  |
| SK hynix            | 7         | 17.07%  |
| Micron Technology   | 6         | 14.63%  |
| Crucial             | 6         | 14.63%  |
| Kingston            | 3         | 7.32%   |
| Corsair             | 3         | 7.32%   |
| G.Skill             | 2         | 4.88%   |
| Elpida              | 2         | 4.88%   |
| Unknown (ABCD)      | 1         | 2.44%   |
| Unknown             | 1         | 2.44%   |
| A-DATA Technology   | 1         | 2.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 2         | 4.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 4.44%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 4.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 4.44%   |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s        | 2         | 4.44%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1         | 2.22%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 1         | 2.22%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s            | 1         | 2.22%   |
| SK hynix RAM HMT351U6EFR8A-PB 8GB DIMM DDR3 1333MT/s             | 1         | 2.22%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 1         | 2.22%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 2.22%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 2.22%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 2.22%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s     | 1         | 2.22%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.22%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.22%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s          | 1         | 2.22%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 1         | 2.22%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB SODIMM LPDDR5 6400MT/s       | 1         | 2.22%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 2.22%   |
| Micron RAM 36JSF2G72PZ-1G9N1 16GB DIMM DDR3 1866MT/s             | 1         | 2.22%   |
| Micron RAM 36JSF2G72PZ-1G9E1 16GB DIMM DDR3 1866MT/s             | 1         | 2.22%   |
| Micron RAM 18ADF2G72AZ-2G6H1R 16GB DIMM DDR4 2667MT/s            | 1         | 2.22%   |
| Kingston RAM KPN424-ELG 1GB DIMM DDR2 667MT/s                    | 1         | 2.22%   |
| Kingston RAM KF556S40-32 32GB SODIMM DDR5 5600MT/s               | 1         | 2.22%   |
| Kingston RAM KF556C36-32 32GB DIMM DDR5 5600MT/s                 | 1         | 2.22%   |
| G.Skill RAM F4-4400C19-16GVK 16GB DIMM DDR4 4000MT/s             | 1         | 2.22%   |
| G.Skill RAM F3-12800CL9-2GBNQ 2GB DIMM DDR3 1333MT/s             | 1         | 2.22%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 1         | 2.22%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 1         | 2.22%   |
| Crucial RAM CT8G4DFRA32A.M4FB 8GB DIMM DDR4 3200MT/s             | 1         | 2.22%   |
| Crucial RAM CT32G4SFD832A.16FB2 32GB SODIMM DDR4 3200MT/s        | 1         | 2.22%   |
| Crucial RAM CT32G4SFD8266.C16FE 32GB SODIMM DDR4 2667MT/s        | 1         | 2.22%   |
| Crucial RAM CT32G4DFD832A.C16FE 32GB DIMM DDR4 3200MT/s          | 1         | 2.22%   |
| Crucial RAM CT16G4SFRA32A.C8FF 16GB SODIMM DDR4 3200MT/s         | 1         | 2.22%   |
| Crucial RAM CT16G4SFRA32A.C8FE 16GB SODIMM DDR4 3200MT/s         | 1         | 2.22%   |
| Corsair RAM CMV16GX4M1A2400C16 16GB DIMM DDR4 2400MT/s           | 1         | 2.22%   |
| Corsair RAM CMT64GX5M2B5600Z40 32GB DIMM DDR5 4800MT/s           | 1         | 2.22%   |
| Corsair RAM CM4X16GF3200C16K4 16GB DIMM DDR4 2667MT/s            | 1         | 2.22%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                      | 1         | 2.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 22        | 59.46%  |
| DDR3   | 6         | 16.22%  |
| DDR5   | 4         | 10.81%  |
| LPDDR5 | 2         | 5.41%   |
| DDR2   | 2         | 5.41%   |
| LPDDR4 | 1         | 2.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 23        | 62.16%  |
| DIMM         | 13        | 35.14%  |
| Row Of Chips | 1         | 2.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 16        | 38.1%   |
| 16384 | 13        | 30.95%  |
| 32768 | 7         | 16.67%  |
| 2048  | 3         | 7.14%   |
| 4096  | 2         | 4.76%   |
| 1024  | 1         | 2.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 11        | 28.21%  |
| 2667  | 7         | 17.95%  |
| 2400  | 4         | 10.26%  |
| 4800  | 3         | 7.69%   |
| 6400  | 2         | 5.13%   |
| 5600  | 2         | 5.13%   |
| 1600  | 2         | 5.13%   |
| 667   | 2         | 5.13%   |
| 49926 | 1         | 2.56%   |
| 4000  | 1         | 2.56%   |
| 3600  | 1         | 2.56%   |
| 1866  | 1         | 2.56%   |
| 1334  | 1         | 2.56%   |
| 1333  | 1         | 2.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)

![Printer Vendor](./images/line_chart/printer_vendor.svg)

| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)

![Printer Model](./images/line_chart/printer_model.svg)

| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| HP LaserJet M14-M17       | 1         | 50%     |
| Canon PIXMA MG2900 Series | 1         | 50%     |

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)

![Camera Vendor](./images/line_chart/camera_vendor.svg)

| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 3         | 15%     |
| Microdia                      | 2         | 10%     |
| Luxvisions Innotech Limited   | 2         | 10%     |
| Logitech                      | 2         | 10%     |
| Lite-On Technology            | 2         | 10%     |
| Sunplus Innovation Technology | 1         | 5%      |
| Sonix Technology              | 1         | 5%      |
| Silicon Motion                | 1         | 5%      |
| Realtek Semiconductor         | 1         | 5%      |
| Quanta                        | 1         | 5%      |
| IMC Networks                  | 1         | 5%      |
| Goodong                       | 1         | 5%      |
| DHZJ-221208-K                 | 1         | 5%      |
| A4Tech                        | 1         | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Lite-On HP HD Camera                          | 2         | 10%     |
| Sunplus XiaoMi USB 2.0 Webcam                 | 1         | 5%      |
| Sonix USB2.0 HD UVC WebCam                    | 1         | 5%      |
| Silicon Motion 300k Pixel Camera              | 1         | 5%      |
| Realtek Laptop Camera                         | 1         | 5%      |
| Quanta HP TrueVision HD Camera                | 1         | 5%      |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 5%      |
| Microdia Integrated_Webcam_FHD                | 1         | 5%      |
| Luxvisions Innotech Limited Integrated Camera | 1         | 5%      |
| Luxvisions Innotech Limited HP HD Camera      | 1         | 5%      |
| Logitech HD Webcam C525                       | 1         | 5%      |
| Logitech C922 Pro Stream Webcam               | 1         | 5%      |
| IMC Networks Integrated Camera                | 1         | 5%      |
| Goodong USB Camera                            | 1         | 5%      |
| DHZJ-221208-K USB Camera                      | 1         | 5%      |
| Chicony ThinkPad T490 Webcam                  | 1         | 5%      |
| Chicony Integrated Camera                     | 1         | 5%      |
| Chicony HD User Facing                        | 1         | 5%      |
| A4Tech HD 720P PC Camera                      | 1         | 5%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Synaptics        | 5         | 71.43%  |
| Validity Sensors | 2         | 28.57%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 3         | 42.86%  |
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 28.57%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 14.29%  |
| Synaptics Fingerprint reader [HP G6]                      | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./images/line_chart/chipcard_vendor.svg)

| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 60%     |
| OmniKey     | 1         | 20%     |
| Broadcom    | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)

![Chipcard Model](./images/line_chart/chipcard_model.svg)

| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 3         | 60%     |
| OmniKey CardMan 3021 / 3121                    | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 18        | 45%     |
| 1     | 8         | 20%     |
| 2     | 5         | 12.5%   |
| 3     | 4         | 10%     |
| 5     | 2         | 5%      |
| 4     | 2         | 5%      |
| 6     | 1         | 2.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 9         | 18%     |
| Graphics card            | 8         | 16%     |
| Fingerprint reader       | 7         | 14%     |
| Chipcard                 | 5         | 10%     |
| Bluetooth                | 5         | 10%     |
| Multimedia controller    | 4         | 8%      |
| Net/wireless             | 3         | 6%      |
| Network                  | 2         | 4%      |
| Card reader              | 2         | 4%      |
| Storage/ide              | 1         | 2%      |
| Storage/ata              | 1         | 2%      |
| Sound                    | 1         | 2%      |
| Firewire controller      | 1         | 2%      |
| Camera                   | 1         | 2%      |

