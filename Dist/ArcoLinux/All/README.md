ArcoLinux Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by ArcoLinux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/ArcoLinux/Desktop/README.md) and [notebooks](/Dist/ArcoLinux/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

Period: Feb, 2022.

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

| Name              | Computers | Percent |
|-------------------|-----------|---------|
| ArcoLinux Rolling | 57        | 91.94%  |
| ArcoLinux         | 5         | 8.06%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name      | Computers | Percent |
|-----------|-----------|---------|
| ArcoLinux | 62        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.16.10-arch1-1              | 10        | 16.13%  |
| 5.16.8-arch1-1               | 7         | 11.29%  |
| 5.16.5-arch1-1               | 6         | 9.68%   |
| 5.16.9-arch1-1               | 5         | 8.06%   |
| 5.16.4-arch1-1               | 4         | 6.45%   |
| 5.16.11-arch1-1              | 4         | 6.45%   |
| 5.15.10-arch1-1              | 4         | 6.45%   |
| 5.16.7-arch1-1               | 3         | 4.84%   |
| 5.16.5-zen1-1-zen            | 3         | 4.84%   |
| 5.16.10-zen1-1-zen           | 2         | 3.23%   |
| 5.4.181-1-lts54              | 1         | 1.61%   |
| 5.17.0-rc4-1-mainline        | 1         | 1.61%   |
| 5.16.8-zen1-1-zen            | 1         | 1.61%   |
| 5.16.4-zen1-1-zen            | 1         | 1.61%   |
| 5.16.2-arch1-1               | 1         | 1.61%   |
| 5.16.11-zen1-1-zen           | 1         | 1.61%   |
| 5.15.24-1-lts                | 1         | 1.61%   |
| 5.15.23-2-lts                | 1         | 1.61%   |
| 5.15.22-1-lts                | 1         | 1.61%   |
| 5.15.21-1-lts                | 1         | 1.61%   |
| 5.15.19-xanmod1-tt-1         | 1         | 1.61%   |
| 5.15.19-hardened1-1-hardened | 1         | 1.61%   |
| 5.15.19-1-lts                | 1         | 1.61%   |
| 5.15.13-arch1-1              | 1         | 1.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.10 | 12        | 19.35%  |
| 5.16.5  | 9         | 14.52%  |
| 5.16.8  | 8         | 12.9%   |
| 5.16.9  | 5         | 8.06%   |
| 5.16.4  | 5         | 8.06%   |
| 5.16.11 | 5         | 8.06%   |
| 5.15.10 | 4         | 6.45%   |
| 5.16.7  | 3         | 4.84%   |
| 5.15.19 | 3         | 4.84%   |
| 5.4.181 | 1         | 1.61%   |
| 5.17.0  | 1         | 1.61%   |
| 5.16.2  | 1         | 1.61%   |
| 5.15.24 | 1         | 1.61%   |
| 5.15.23 | 1         | 1.61%   |
| 5.15.22 | 1         | 1.61%   |
| 5.15.21 | 1         | 1.61%   |
| 5.15.13 | 1         | 1.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 48        | 77.42%  |
| 5.15    | 12        | 19.35%  |
| 5.4     | 1         | 1.61%   |
| 5.17    | 1         | 1.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 62        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 19        | 30.65%  |
| XFCE       | 15        | 24.19%  |
| i3         | 7         | 11.29%  |
| awesome    | 5         | 8.06%   |
| X-Cinnamon | 4         | 6.45%   |
| LeftWM     | 4         | 6.45%   |
| GNOME      | 2         | 3.23%   |
| dwm        | 2         | 3.23%   |
| bspwm      | 2         | 3.23%   |
| qtile      | 1         | 1.61%   |
| openbox    | 1         | 1.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 56        | 90.32%  |
| Wayland | 3         | 4.84%   |
| Tty     | 3         | 4.84%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 42        | 67.74%  |
| LightDM | 14        | 22.58%  |
| Unknown | 6         | 9.68%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 36        | 58.06%  |
| en_GB | 5         | 8.06%   |
| en_CA | 4         | 6.45%   |
| de_DE | 3         | 4.84%   |
| es_ES | 2         | 3.23%   |
| en_IN | 2         | 3.23%   |
| en_AU | 2         | 3.23%   |
| sv_SE | 1         | 1.61%   |
| ru_UA | 1         | 1.61%   |
| pt_PT | 1         | 1.61%   |
| it_IT | 1         | 1.61%   |
| hu_HU | 1         | 1.61%   |
| fr_FR | 1         | 1.61%   |
| fr_CA | 1         | 1.61%   |
| el_GR | 1         | 1.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 44        | 70.97%  |
| BIOS | 18        | 29.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 48        | 77.42%  |
| Btrfs   | 10        | 16.13%  |
| Overlay | 3         | 4.84%   |
| Unknown | 1         | 1.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 46        | 74.19%  |
| MBR     | 10        | 16.13%  |
| Unknown | 6         | 9.68%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 69.35%  |
| Yes       | 19        | 30.65%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 34        | 54.84%  |
| Yes       | 28        | 45.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 20        | 32.26%  |
| Lenovo              | 12        | 19.35%  |
| Dell                | 8         | 12.9%   |
| Gigabyte Technology | 4         | 6.45%   |
| Hewlett-Packard     | 3         | 4.84%   |
| Acer                | 3         | 4.84%   |
| Supermicro          | 1         | 1.61%   |
| Razer               | 1         | 1.61%   |
| Notebook            | 1         | 1.61%   |
| Medion              | 1         | 1.61%   |
| HUAWEI              | 1         | 1.61%   |
| Fujitsu             | 1         | 1.61%   |
| Compal              | 1         | 1.61%   |
| Casper              | 1         | 1.61%   |
| Biostar             | 1         | 1.61%   |
| ASRock              | 1         | 1.61%   |
| Apple               | 1         | 1.61%   |
| Unknown             | 1         | 1.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                               | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| ASUS PRIME X570-P                                  | 2         | 3.23%   |
| Supermicro Super Server                            | 1         | 1.61%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 1.61%   |
| Notebook PA70ES                                    | 1         | 1.61%   |
| Medion MS-7707                                     | 1         | 1.61%   |
| Lenovo V15-IIL 82C5                                | 1         | 1.61%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS        | 1         | 1.61%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S04N1H           | 1         | 1.61%   |
| Lenovo ThinkPad W510 4389BB4                       | 1         | 1.61%   |
| Lenovo ThinkPad T420 4180DY4                       | 1         | 1.61%   |
| Lenovo ThinkPad T14 Gen 1 20UDCTO1WW               | 1         | 1.61%   |
| Lenovo ThinkPad S430 68852BU                       | 1         | 1.61%   |
| Lenovo ThinkPad R61/R61i 8934A7F                   | 1         | 1.61%   |
| Lenovo ThinkPad P14s Gen 2a 21A0000CMH             | 1         | 1.61%   |
| Lenovo ThinkPad E14 Gen 2 20TA0018AD               | 1         | 1.61%   |
| Lenovo IdeaPad Slim 7 Pro 14IHU5 82QT              | 1         | 1.61%   |
| Lenovo IdeaPad Flex-14API 81SS                     | 1         | 1.61%   |
| HUAWEI KLVL-WXX9                                   | 1         | 1.61%   |
| HP ZBook 15 G5                                     | 1         | 1.61%   |
| HP Pavilion Gaming Laptop 15-dk2xxx                | 1         | 1.61%   |
| HP 255 G7 Notebook PC                              | 1         | 1.61%   |
| Gigabyte Nobilis                                   | 1         | 1.61%   |
| Gigabyte B550 AORUS MASTER                         | 1         | 1.61%   |
| Gigabyte B450M DS3H                                | 1         | 1.61%   |
| Gigabyte B365M H                                   | 1         | 1.61%   |
| Fujitsu LIFEBOOK E756                              | 1         | 1.61%   |
| Dell XPS 15 9570                                   | 1         | 1.61%   |
| Dell Vostro 270                                    | 1         | 1.61%   |
| Dell Precision 5550                                | 1         | 1.61%   |
| Dell Latitude E7240                                | 1         | 1.61%   |
| Dell Latitude E5430 non-vPro                       | 1         | 1.61%   |
| Dell Latitude E5400                                | 1         | 1.61%   |
| Dell Inspiron 5567                                 | 1         | 1.61%   |
| Dell Inspiron 15-3567                              | 1         | 1.61%   |
| Compal PBL21                                       | 1         | 1.61%   |
| Casper C600 NOTEBOOK DISCRETE                      | 1         | 1.61%   |
| Biostar J3060NH                                    | 1         | 1.61%   |
| ASUS Z170-A                                        | 1         | 1.61%   |
| ASUS Z170 PRO GAMING                               | 1         | 1.61%   |
| ASUS X750LN                                        | 1         | 1.61%   |
| ASUS VivoBook_ASUSLaptop X515DAP_M515DA            | 1         | 1.61%   |
| ASUS VivoBook_ASUSLaptop X509DA_D509DA             | 1         | 1.61%   |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA            | 1         | 1.61%   |
| ASUS TUF Z390M-PRO GAMING                          | 1         | 1.61%   |
| ASUS TUF Z390-PRO GAMING                           | 1         | 1.61%   |
| ASUS STRIX Z270F GAMING                            | 1         | 1.61%   |
| ASUS ROG STRIX X470-F GAMING                       | 1         | 1.61%   |
| ASUS ROG Strix G513IC_G513IC                       | 1         | 1.61%   |
| ASUS ROG STRIX B550-F GAMING                       | 1         | 1.61%   |
| ASUS ROG STRIX B450-F GAMING II                    | 1         | 1.61%   |
| ASUS ROG Maximus XI FORMULA                        | 1         | 1.61%   |
| ASUS PRIME Z490-A                                  | 1         | 1.61%   |
| ASUS K54L                                          | 1         | 1.61%   |
| ASUS K53E                                          | 1         | 1.61%   |
| ASUS CM6870                                        | 1         | 1.61%   |
| ASRock B450M Steel Legend                          | 1         | 1.61%   |
| Apple MacBookPro11,2                               | 1         | 1.61%   |
| Acer Nitro AN515-54                                | 1         | 1.61%   |
| Acer Aspire V3-771                                 | 1         | 1.61%   |
| Acer Aspire A515-41G                               | 1         | 1.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 9         | 14.52%  |
| ASUS ROG           | 5         | 8.06%   |
| Dell Latitude      | 3         | 4.84%   |
| ASUS VivoBook      | 3         | 4.84%   |
| ASUS PRIME         | 3         | 4.84%   |
| Lenovo IdeaPad     | 2         | 3.23%   |
| Dell Inspiron      | 2         | 3.23%   |
| ASUS TUF           | 2         | 3.23%   |
| Acer Aspire        | 2         | 3.23%   |
| Supermicro Super   | 1         | 1.61%   |
| Razer Blade        | 1         | 1.61%   |
| Notebook PA70ES    | 1         | 1.61%   |
| Medion MS-7707     | 1         | 1.61%   |
| Lenovo V15-IIL     | 1         | 1.61%   |
| HUAWEI KLVL-WXX9   | 1         | 1.61%   |
| HP ZBook           | 1         | 1.61%   |
| HP Pavilion        | 1         | 1.61%   |
| HP 255             | 1         | 1.61%   |
| Gigabyte Nobilis   | 1         | 1.61%   |
| Gigabyte B550      | 1         | 1.61%   |
| Gigabyte B450M     | 1         | 1.61%   |
| Gigabyte B365M     | 1         | 1.61%   |
| Fujitsu LIFEBOOK   | 1         | 1.61%   |
| Dell XPS           | 1         | 1.61%   |
| Dell Vostro        | 1         | 1.61%   |
| Dell Precision     | 1         | 1.61%   |
| Compal PBL21       | 1         | 1.61%   |
| Casper C600        | 1         | 1.61%   |
| Biostar J3060NH    | 1         | 1.61%   |
| ASUS Z170-A        | 1         | 1.61%   |
| ASUS Z170          | 1         | 1.61%   |
| ASUS X750LN        | 1         | 1.61%   |
| ASUS STRIX         | 1         | 1.61%   |
| ASUS K54L          | 1         | 1.61%   |
| ASUS K53E          | 1         | 1.61%   |
| ASUS CM6870        | 1         | 1.61%   |
| ASRock B450M       | 1         | 1.61%   |
| Apple MacBookPro11 | 1         | 1.61%   |
| Acer Nitro         | 1         | 1.61%   |
| Unknown            | 1         | 1.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 12        | 19.35%  |
| 2019 | 8         | 12.9%   |
| 2018 | 8         | 12.9%   |
| 2021 | 6         | 9.68%   |
| 2016 | 5         | 8.06%   |
| 2011 | 5         | 8.06%   |
| 2017 | 4         | 6.45%   |
| 2015 | 3         | 4.84%   |
| 2013 | 3         | 4.84%   |
| 2012 | 3         | 4.84%   |
| 2014 | 2         | 3.23%   |
| 2010 | 1         | 1.61%   |
| 2008 | 1         | 1.61%   |
| 2007 | 1         | 1.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 39        | 62.9%   |
| Desktop  | 22        | 35.48%  |
| Server   | 1         | 1.61%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 62        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 62        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 14        | 22.58%  |
| 8.01-16.0   | 14        | 22.58%  |
| 16.01-24.0  | 13        | 20.97%  |
| 4.01-8.0    | 11        | 17.74%  |
| 3.01-4.0    | 7         | 11.29%  |
| 64.01-256.0 | 3         | 4.84%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 20        | 32.26%  |
| 2.01-3.0  | 19        | 30.65%  |
| 4.01-8.0  | 9         | 14.52%  |
| 3.01-4.0  | 7         | 11.29%  |
| 0.51-1.0  | 4         | 6.45%   |
| 8.01-16.0 | 3         | 4.84%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 27        | 43.55%  |
| 2      | 19        | 30.65%  |
| 4      | 6         | 9.68%   |
| 3      | 6         | 9.68%   |
| 5      | 2         | 3.23%   |
| 7      | 1         | 1.61%   |
| 6      | 1         | 1.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 70.97%  |
| Yes       | 18        | 29.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 83.87%  |
| No        | 10        | 16.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 77.42%  |
| No        | 14        | 22.58%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 67.74%  |
| No        | 20        | 32.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 13        | 20.97%  |
| Canada                 | 5         | 8.06%   |
| Germany                | 4         | 6.45%   |
| Spain                  | 3         | 4.84%   |
| India                  | 3         | 4.84%   |
| UK                     | 2         | 3.23%   |
| Portugal               | 2         | 3.23%   |
| Netherlands            | 2         | 3.23%   |
| Indonesia              | 2         | 3.23%   |
| France                 | 2         | 3.23%   |
| Bulgaria               | 2         | 3.23%   |
| Belgium                | 2         | 3.23%   |
| Australia              | 2         | 3.23%   |
| Ukraine                | 1         | 1.61%   |
| UAE                    | 1         | 1.61%   |
| Turkey                 | 1         | 1.61%   |
| Switzerland            | 1         | 1.61%   |
| Sweden                 | 1         | 1.61%   |
| Slovenia               | 1         | 1.61%   |
| Romania                | 1         | 1.61%   |
| Poland                 | 1         | 1.61%   |
| Norway                 | 1         | 1.61%   |
| Mexico                 | 1         | 1.61%   |
| Lithuania              | 1         | 1.61%   |
| Italy                  | 1         | 1.61%   |
| Hungary                | 1         | 1.61%   |
| Greece                 | 1         | 1.61%   |
| Georgia                | 1         | 1.61%   |
| Cuba                   | 1         | 1.61%   |
| Bosnia and Herzegovina | 1         | 1.61%   |
| Barbados               | 1         | 1.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Madrid                   | 2         | 3.23%   |
| Wilrijk                  | 1         | 1.61%   |
| Whitby                   | 1         | 1.61%   |
| Walnut Creek             | 1         | 1.61%   |
| Toronto                  | 1         | 1.61%   |
| Svilengrad               | 1         | 1.61%   |
| Surabaya                 | 1         | 1.61%   |
| Srebrenik                | 1         | 1.61%   |
| Šiauliai                | 1         | 1.61%   |
| Salaberry-de-Valleyfield | 1         | 1.61%   |
| Rome                     | 1         | 1.61%   |
| Rexburg                  | 1         | 1.61%   |
| Rathfriland              | 1         | 1.61%   |
| Queens                   | 1         | 1.61%   |
| Portland                 | 1         | 1.61%   |
| Pennsville               | 1         | 1.61%   |
| Paris                    | 1         | 1.61%   |
| Oslo                     | 1         | 1.61%   |
| Olympia                  | 1         | 1.61%   |
| Novi Pazar               | 1         | 1.61%   |
| Nieuw-Vennep             | 1         | 1.61%   |
| Newcastle                | 1         | 1.61%   |
| Narasapuram              | 1         | 1.61%   |
| Milton Keynes            | 1         | 1.61%   |
| MÃ¼nster               | 1         | 1.61%   |
| Martin                   | 1         | 1.61%   |
| Los Angeles              | 1         | 1.61%   |
| Ljubljana                | 1         | 1.61%   |
| Lethbridge               | 1         | 1.61%   |
| Leiria                   | 1         | 1.61%   |
| LaSalle                  | 1         | 1.61%   |
| Kyiv                     | 1         | 1.61%   |
| K'alak'i T'bilisi        | 1         | 1.61%   |
| Jaszbereny               | 1         | 1.61%   |
| Houston                  | 1         | 1.61%   |
| Hoellviken               | 1         | 1.61%   |
| High Point               | 1         | 1.61%   |
| Havana                   | 1         | 1.61%   |
| Haarlem                  | 1         | 1.61%   |
| Grimbergen               | 1         | 1.61%   |
| Gdynia                   | 1         | 1.61%   |
| Frankfurt am Main        | 1         | 1.61%   |
| Fort Collins             | 1         | 1.61%   |
| Farrukhabad              | 1         | 1.61%   |
| Dublin                   | 1         | 1.61%   |
| Dubai                    | 1         | 1.61%   |
| Ciudad Nezahualcoyotl    | 1         | 1.61%   |
| Carpentras               | 1         | 1.61%   |
| Butte                    | 1         | 1.61%   |
| Bursa                    | 1         | 1.61%   |
| Buchs / Buchs (Dorf)     | 1         | 1.61%   |
| Bucharest                | 1         | 1.61%   |
| Brisbane                 | 1         | 1.61%   |
| Bridgetown               | 1         | 1.61%   |
| Bonn                     | 1         | 1.61%   |
| Berlin                   | 1         | 1.61%   |
| Bengaluru                | 1         | 1.61%   |
| Barcelona                | 1         | 1.61%   |
| Bagusan                  | 1         | 1.61%   |
| Athens                   | 1         | 1.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 32     | 21.9%   |
| WDC                 | 20        | 29     | 19.05%  |
| Seagate             | 15        | 20     | 14.29%  |
| Crucial             | 7         | 7      | 6.67%   |
| SK Hynix            | 5         | 5      | 4.76%   |
| Intel               | 4         | 4      | 3.81%   |
| Toshiba             | 3         | 3      | 2.86%   |
| SanDisk             | 3         | 4      | 2.86%   |
| Phison              | 3         | 3      | 2.86%   |
| Kingston            | 3         | 3      | 2.86%   |
| HGST                | 3         | 3      | 2.86%   |
| XPG                 | 1         | 1      | 0.95%   |
| Unknown             | 1         | 1      | 0.95%   |
| Transcend           | 1         | 1      | 0.95%   |
| TO Exter            | 1         | 1      | 0.95%   |
| SPCC                | 1         | 1      | 0.95%   |
| PNY                 | 1         | 1      | 0.95%   |
| LITEONIT            | 1         | 1      | 0.95%   |
| Hitachi             | 1         | 1      | 0.95%   |
| Hewlett-Packard     | 1         | 1      | 0.95%   |
| Gigabyte Technology | 1         | 1      | 0.95%   |
| Corsair             | 1         | 1      | 0.95%   |
| China               | 1         | 1      | 0.95%   |
| ASMT                | 1         | 1      | 0.95%   |
| ASMedia             | 1         | 1      | 0.95%   |
| Apple               | 1         | 1      | 0.95%   |
| A-DATA Technology   | 1         | 1      | 0.95%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                 | 3         | 2.38%   |
| WDC WD20EARX-00PASB0 2TB                  | 2         | 1.59%   |
| Seagate ST1000LM049-2GH172 1TB            | 2         | 1.59%   |
| Samsung SSD 980 1TB                       | 2         | 1.59%   |
| Samsung SSD 970 EVO 500GB                 | 2         | 1.59%   |
| Samsung SSD 860 EVO 500GB                 | 2         | 1.59%   |
| Samsung SSD 850 EVO 500GB                 | 2         | 1.59%   |
| HGST HTS545050A7E680 500GB                | 2         | 1.59%   |
| Crucial CT500MX500SSD1 500GB              | 2         | 1.59%   |
| Crucial CT1000MX500SSD1 1TB               | 2         | 1.59%   |
| XPG GAMMIX S11 Pro 1TB                    | 1         | 0.79%   |
| WDC WDS500G1X0E-00AFY0 500GB              | 1         | 0.79%   |
| WDC WDS250G2B0A-00SM50 250GB SSD          | 1         | 0.79%   |
| WDC WD7500BPVT-60HXZT3 752GB              | 1         | 0.79%   |
| WDC WD7500BPVT-22HXZT3 752GB              | 1         | 0.79%   |
| WDC WD6400BEVT-60A0RT0 640GB              | 1         | 0.79%   |
| WDC WD5003ABYX-01WERA2 500GB              | 1         | 0.79%   |
| WDC WD5000HHTZ-75N21V0 500GB              | 1         | 0.79%   |
| WDC WD5000AZRX-00A8LB0 500GB              | 1         | 0.79%   |
| WDC WD5000AAKX-75U6AA0 500GB              | 1         | 0.79%   |
| WDC WD5000AAKX-603CA0 500GB               | 1         | 0.79%   |
| WDC WD4005FZBX-00K5WB0 4TB                | 1         | 0.79%   |
| WDC WD3200LPVX-75V0TT0 320GB              | 1         | 0.79%   |
| WDC WD30EZRX-00SPEB0 3TB                  | 1         | 0.79%   |
| WDC WD20EZRZ-00Z5HB0 2TB                  | 1         | 0.79%   |
| WDC WD10SPZX-80Z10T2 1TB                  | 1         | 0.79%   |
| WDC WD10SPZX-75Z10T2 1TB                  | 1         | 0.79%   |
| WDC WD10SPZX-60Z10T0 1TB                  | 1         | 0.79%   |
| WDC WD10EZEX-75WN4A0 1TB                  | 1         | 0.79%   |
| WDC WD10EZEX-60WN4A1 1TB                  | 1         | 0.79%   |
| WDC WD10EZEX-08WN4A0 1TB                  | 1         | 0.79%   |
| WDC WD1003FBYX-01Y7B1 1TB                 | 1         | 0.79%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB        | 1         | 0.79%   |
| WDC PC SN720 SDAPNTW-256G-1101 256GB      | 1         | 0.79%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB      | 1         | 0.79%   |
| WDC PC SN520 SDAPNUW-256G-1202 256GB      | 1         | 0.79%   |
| Unknown DA4064  64GB                      | 1         | 0.79%   |
| Transcend TS480GSSD220S 480GB             | 1         | 0.79%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 0.79%   |
| Toshiba MK5076GSX 500GB                   | 1         | 0.79%   |
| Toshiba DT01ABA100V 1TB                   | 1         | 0.79%   |
| TO Exter nal USB 3.0 2TB                  | 1         | 0.79%   |
| SPCC 2.5 SSD 512GB                        | 1         | 0.79%   |
| SK Hynix SKHynix_HFS512GDE9X081N 512GB    | 1         | 0.79%   |
| SK Hynix SKHynix_HFS001TD9TNI-L2B0B 1TB   | 1         | 0.79%   |
| SK Hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 1         | 0.79%   |
| SK Hynix SKHynix_HFM256GD3HX015N 256GB    | 1         | 0.79%   |
| SK Hynix PC711 NVMe 512GB                 | 1         | 0.79%   |
| Seagate ST9320325AS 320GB                 | 1         | 0.79%   |
| Seagate ST6000DM003-2CY186 6TB            | 1         | 0.79%   |
| Seagate ST4000DM004-2CV104 4TB            | 1         | 0.79%   |
| Seagate ST3500312CS 500GB                 | 1         | 0.79%   |
| Seagate ST330006 51NS 3TB                 | 1         | 0.79%   |
| Seagate ST32000542AS 2TB                  | 1         | 0.79%   |
| Seagate ST31000528AS 1TB                  | 1         | 0.79%   |
| Seagate ST31000524AS 1TB                  | 1         | 0.79%   |
| Seagate ST3000DM 001-1E6166 3TB           | 1         | 0.79%   |
| Seagate ST2000DM008-2FR102 2TB            | 1         | 0.79%   |
| Seagate ST2000DM006-2DM164 2TB            | 1         | 0.79%   |
| Seagate ST1000LM048-2E7172 1TB            | 1         | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 17        | 23     | 40.48%  |
| Seagate         | 15        | 20     | 35.71%  |
| Toshiba         | 3         | 3      | 7.14%   |
| HGST            | 3         | 3      | 7.14%   |
| Hitachi         | 1         | 1      | 2.38%   |
| Hewlett-Packard | 1         | 1      | 2.38%   |
| ASMT            | 1         | 1      | 2.38%   |
| ASMedia         | 1         | 1      | 2.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 17     | 40.54%  |
| Crucial             | 6         | 6      | 16.22%  |
| SanDisk             | 3         | 4      | 8.11%   |
| Kingston            | 2         | 2      | 5.41%   |
| Intel               | 2         | 2      | 5.41%   |
| WDC                 | 1         | 1      | 2.7%    |
| Transcend           | 1         | 1      | 2.7%    |
| TO Exter            | 1         | 1      | 2.7%    |
| SPCC                | 1         | 1      | 2.7%    |
| PNY                 | 1         | 1      | 2.7%    |
| LITEONIT            | 1         | 1      | 2.7%    |
| China               | 1         | 1      | 2.7%    |
| Apple               | 1         | 1      | 2.7%    |
| A-DATA Technology   | 1         | 1      | 2.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 36        | 53     | 38.3%   |
| SSD  | 29        | 40     | 30.85%  |
| NVMe | 28        | 35     | 29.79%  |
| MMC  | 1         | 1      | 1.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 47        | 82     | 55.95%  |
| NVMe | 28        | 35     | 33.33%  |
| SAS  | 8         | 11     | 9.52%   |
| MMC  | 1         | 1      | 1.19%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 30        | 41     | 41.67%  |
| 0.51-1.0   | 26        | 30     | 36.11%  |
| 1.01-2.0   | 8         | 11     | 11.11%  |
| 2.01-3.0   | 3         | 4      | 4.17%   |
| 4.01-10.0  | 3         | 4      | 4.17%   |
| 3.01-4.0   | 2         | 3      | 2.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 20        | 32.26%  |
| 501-1000       | 11        | 17.74%  |
| 101-250        | 8         | 12.9%   |
| More than 3000 | 7         | 11.29%  |
| 1001-2000      | 6         | 9.68%   |
| 51-100         | 6         | 9.68%   |
| 1-20           | 2         | 3.23%   |
| 2001-3000      | 1         | 1.61%   |
| Unknown        | 1         | 1.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 19        | 30.65%  |
| 21-50          | 14        | 22.58%  |
| 101-250        | 8         | 12.9%   |
| 51-100         | 5         | 8.06%   |
| 251-500        | 4         | 6.45%   |
| 1001-2000      | 4         | 6.45%   |
| 501-1000       | 4         | 6.45%   |
| More than 3000 | 3         | 4.84%   |
| Unknown        | 1         | 1.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD6400BEVT-60A0RT0 640GB       | 1         | 1      | 8.33%   |
| WDC WD5000AAKX-603CA0 500GB        | 1         | 1      | 8.33%   |
| WDC WD20EARX-00PASB0 2TB           | 1         | 1      | 8.33%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 8.33%   |
| Seagate ST3500312CS 500GB          | 1         | 1      | 8.33%   |
| Seagate ST31000528AS 1TB           | 1         | 1      | 8.33%   |
| Seagate ST1000LM049-2GH172 1TB     | 1         | 1      | 8.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 8.33%   |
| Intel SSDSA2M160G2GC 160GB         | 1         | 1      | 8.33%   |
| HGST HTS725050A7E630 500GB         | 1         | 1      | 8.33%   |
| HGST HTS545050A7E680 500GB         | 1         | 1      | 8.33%   |
| ASMedia AS2115 8TB                 | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 41.67%  |
| WDC     | 3         | 3      | 25%     |
| HGST    | 2         | 2      | 16.67%  |
| Intel   | 1         | 1      | 8.33%   |
| ASMedia | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 45.45%  |
| WDC     | 3         | 3      | 27.27%  |
| HGST    | 2         | 2      | 18.18%  |
| ASMedia | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 11     | 91.67%  |
| SSD  | 1         | 1      | 8.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)

![Failed Drives](./images/line_chart/drive_failed.svg)

| Model                      | Computers | Drives | Percent |
|----------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)

![Failed Drive Vendor](./images/line_chart/drive_failed_vendor.svg)

| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)

![Drive Status](./images/line_chart/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 49        | 97     | 66.22%  |
| Detected | 13        | 19     | 17.57%  |
| Malfunc  | 11        | 12     | 14.86%  |
| Failed   | 1         | 1      | 1.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 40        | 47.06%  |
| Samsung Electronics         | 14        | 16.47%  |
| AMD                         | 13        | 15.29%  |
| SK Hynix                    | 5         | 5.88%   |
| Sandisk                     | 5         | 5.88%   |
| Phison Electronics          | 5         | 5.88%   |
| Micron/Crucial Technology   | 1         | 1.18%   |
| Kingston Technology Company | 1         | 1.18%   |
| ADATA Technology            | 1         | 1.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 9         | 9.68%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 9         | 9.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 4         | 4.3%    |
| AMD 400 Series Chipset SATA Controller                                                 | 4         | 4.3%    |
| SK Hynix Gold P31 SSD                                                                  | 3         | 3.23%   |
| Samsung NVMe SSD Controller 980                                                        | 3         | 3.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 3         | 3.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 3         | 3.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 3.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 3         | 3.23%   |
| Phison E16 PCIe4 NVMe Controller                                                       | 2         | 2.15%   |
| Phison E12 NVMe Controller                                                             | 2         | 2.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 2.15%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]           | 2         | 2.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 2         | 2.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 2         | 2.15%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                               | 2         | 2.15%   |
| SK Hynix Non-Volatile memory controller                                                | 1         | 1.08%   |
| SK Hynix BC511                                                                         | 1         | 1.08%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                             | 1         | 1.08%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 1         | 1.08%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 1.08%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.08%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.08%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 1.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 1.08%   |
| Samsung Apple PCIe SSD                                                                 | 1         | 1.08%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 1.08%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 1         | 1.08%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 1.08%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 1.08%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 1         | 1.08%   |
| Intel SSD 660P Series                                                                  | 1         | 1.08%   |
| Intel Non-Volatile memory controller                                                   | 1         | 1.08%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 1.08%   |
| Intel Comet Lake PCH-H RAID                                                            | 1         | 1.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 1.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 1.08%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]            | 1         | 1.08%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]            | 1         | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 1         | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 1         | 1.08%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                            | 1         | 1.08%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 46        | 56.1%   |
| NVMe | 28        | 34.15%  |
| RAID | 5         | 6.1%    |
| IDE  | 3         | 3.66%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 44        | 70.97%  |
| AMD    | 18        | 29.03%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor               | 3         | 4.84%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 3.23%   |
| Intel Core i7-10850H CPU @ 2.70GHz              | 2         | 3.23%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 2         | 3.23%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 3.23%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 2         | 3.23%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 3.23%   |
| Intel Xeon CPU E3-1240 v6 @ 3.70GHz             | 1         | 1.61%   |
| Intel Pentium CPU G2020 @ 2.90GHz               | 1         | 1.61%   |
| Intel Pentium CPU B950 @ 2.10GHz                | 1         | 1.61%   |
| Intel Core i9-9900K CPU @ 3.60GHz               | 1         | 1.61%   |
| Intel Core i7-9700K CPU @ 3.60GHz               | 1         | 1.61%   |
| Intel Core i7-8850H CPU @ 2.60GHz               | 1         | 1.61%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1         | 1.61%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 1.61%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1         | 1.61%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz              | 1         | 1.61%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 1         | 1.61%   |
| Intel Core i7-4500U CPU @ 1.80GHz               | 1         | 1.61%   |
| Intel Core i7-3820 CPU @ 3.60GHz                | 1         | 1.61%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1         | 1.61%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 1.61%   |
| Intel Core i7-10700K CPU @ 3.80GHz              | 1         | 1.61%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz               | 1         | 1.61%   |
| Intel Core i5-9600K CPU @ 3.70GHz               | 1         | 1.61%   |
| Intel Core i5-9400F CPU @ 2.90GHz               | 1         | 1.61%   |
| Intel Core i5-9300H CPU @ 2.40GHz               | 1         | 1.61%   |
| Intel Core i5-6600K CPU @ 3.50GHz               | 1         | 1.61%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 1.61%   |
| Intel Core i5-4310U CPU @ 2.00GHz               | 1         | 1.61%   |
| Intel Core i5-3340M CPU @ 2.70GHz               | 1         | 1.61%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 1         | 1.61%   |
| Intel Core i5-2430M CPU @ 2.40GHz               | 1         | 1.61%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 1         | 1.61%   |
| Intel Core i5-2300 CPU @ 2.80GHz                | 1         | 1.61%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 1         | 1.61%   |
| Intel Core i3-7100U CPU @ 2.40GHz               | 1         | 1.61%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 1         | 1.61%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 1.61%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz            | 1         | 1.61%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 1         | 1.61%   |
| Intel Celeron CPU J3060 @ 1.60GHz               | 1         | 1.61%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz         | 1         | 1.61%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 1.61%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz         | 1         | 1.61%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics      | 1         | 1.61%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 1         | 1.61%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 1         | 1.61%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1         | 1.61%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 1         | 1.61%   |
| AMD Ryzen 3 3250U with Radeon Graphics          | 1         | 1.61%   |
| AMD A6-5400K APU with Radeon HD Graphics        | 1         | 1.61%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G    | 1         | 1.61%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 1         | 1.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 17        | 27.42%  |
| Intel Core i5    | 14        | 22.58%  |
| AMD Ryzen 5      | 8         | 12.9%   |
| AMD Ryzen 7      | 4         | 6.45%   |
| Other            | 3         | 4.84%   |
| Intel Pentium    | 2         | 3.23%   |
| Intel Core i3    | 2         | 3.23%   |
| Intel Core 2 Duo | 2         | 3.23%   |
| Intel Celeron    | 2         | 3.23%   |
| AMD Ryzen 7 PRO  | 2         | 3.23%   |
| Intel Xeon       | 1         | 1.61%   |
| Intel Core i9    | 1         | 1.61%   |
| AMD Ryzen 3      | 1         | 1.61%   |
| AMD A6           | 1         | 1.61%   |
| AMD A4           | 1         | 1.61%   |
| AMD A12          | 1         | 1.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 22        | 35.48%  |
| 4      | 17        | 27.42%  |
| 6      | 13        | 20.97%  |
| 8      | 9         | 14.52%  |
| 1      | 1         | 1.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 62        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 50        | 80.65%  |
| 1      | 12        | 19.35%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 62        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 11.29%  |
| 0x906ea    | 5         | 8.06%   |
| 0x306a9    | 5         | 8.06%   |
| 0x206a7    | 4         | 6.45%   |
| 0xa0652    | 3         | 4.84%   |
| 0x806c1    | 3         | 4.84%   |
| 0x40651    | 3         | 4.84%   |
| 0x08701021 | 3         | 4.84%   |
| 0x08600106 | 3         | 4.84%   |
| 0x08108109 | 3         | 4.84%   |
| 0x906ec    | 2         | 3.23%   |
| 0x906e9    | 2         | 3.23%   |
| 0x506e3    | 2         | 3.23%   |
| 0x0a201016 | 2         | 3.23%   |
| 0xa0655    | 1         | 1.61%   |
| 0x806e9    | 1         | 1.61%   |
| 0x706e5    | 1         | 1.61%   |
| 0x706a8    | 1         | 1.61%   |
| 0x6fd      | 1         | 1.61%   |
| 0x406e3    | 1         | 1.61%   |
| 0x406c4    | 1         | 1.61%   |
| 0x40661    | 1         | 1.61%   |
| 0x206d7    | 1         | 1.61%   |
| 0x106e5    | 1         | 1.61%   |
| 0x0a201009 | 1         | 1.61%   |
| 0x08108102 | 1         | 1.61%   |
| 0x0800820d | 1         | 1.61%   |
| 0x06006705 | 1         | 1.61%   |
| 0x06001119 | 1         | 1.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 12        | 19.35%  |
| Zen 2         | 6         | 9.68%   |
| SandyBridge   | 6         | 9.68%   |
| Zen+          | 5         | 8.06%   |
| IvyBridge     | 5         | 8.06%   |
| Zen 3         | 4         | 6.45%   |
| Skylake       | 4         | 6.45%   |
| Haswell       | 4         | 6.45%   |
| CometLake     | 4         | 6.45%   |
| TigerLake     | 3         | 4.84%   |
| Excavator     | 2         | 3.23%   |
| Core          | 2         | 3.23%   |
| Silvermont    | 1         | 1.61%   |
| Piledriver    | 1         | 1.61%   |
| Nehalem       | 1         | 1.61%   |
| IceLake       | 1         | 1.61%   |
| Goldmont plus | 1         | 1.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 33        | 42.31%  |
| Nvidia | 27        | 34.62%  |
| AMD    | 18        | 23.08%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 4.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 4.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 3.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 3.7%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 3.7%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 3.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 3.7%    |
| AMD Renoir                                                                               | 3         | 3.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 2.47%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2         | 2.47%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 2.47%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.47%   |
| Intel HD Graphics 620                                                                    | 2         | 2.47%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 2.47%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 1.23%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 1.23%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 1.23%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 1.23%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.23%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 1.23%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1         | 1.23%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 1.23%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 1.23%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.23%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.23%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 1.23%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 1.23%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.23%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 1.23%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 1.23%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 1.23%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.23%   |
| Nvidia GK107M [GeForce GT 730M]                                                          | 1         | 1.23%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 1.23%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 1         | 1.23%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.23%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 1.23%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.23%   |
| Intel HD Graphics 630                                                                    | 1         | 1.23%   |
| Intel HD Graphics 530                                                                    | 1         | 1.23%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.23%   |
| Intel Crystal Well Integrated Graphics Controller                                        | 1         | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.23%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.23%   |
| AMD Trinity 2 [Radeon HD 7540D]                                                          | 1         | 1.23%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.23%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.23%   |
| AMD Navi 21 [Radeon RX 6900 XT]                                                          | 1         | 1.23%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 1         | 1.23%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1         | 1.23%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1         | 1.23%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1         | 1.23%   |
| AMD Cezanne                                                                              | 1         | 1.23%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 1         | 1.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 29.03%  |
| 1 x Nvidia     | 15        | 24.19%  |
| 1 x AMD        | 14        | 22.58%  |
| Intel + Nvidia | 11        | 17.74%  |
| 2 x AMD        | 2         | 3.23%   |
| Intel + AMD    | 1         | 1.61%   |
| AMD + Nvidia   | 1         | 1.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 36        | 58.06%  |
| Proprietary | 24        | 38.71%  |
| Unknown     | 2         | 3.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 53.23%  |
| 1.01-2.0   | 7         | 11.29%  |
| 3.01-4.0   | 5         | 8.06%   |
| 8.01-16.0  | 5         | 8.06%   |
| 7.01-8.0   | 4         | 6.45%   |
| 0.01-0.5   | 4         | 6.45%   |
| 5.01-6.0   | 3         | 4.84%   |
| 0.51-1.0   | 1         | 1.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 9         | 11.54%  |
| Samsung Electronics     | 8         | 10.26%  |
| Dell                    | 8         | 10.26%  |
| LG Display              | 7         | 8.97%   |
| Chimei Innolux          | 7         | 8.97%   |
| AU Optronics            | 4         | 5.13%   |
| Hewlett-Packard         | 3         | 3.85%   |
| Goldstar                | 3         | 3.85%   |
| Sony                    | 2         | 2.56%   |
| Sharp                   | 2         | 2.56%   |
| BenQ                    | 2         | 2.56%   |
| AOC                     | 2         | 2.56%   |
| Ancor Communications    | 2         | 2.56%   |
| Acer                    | 2         | 2.56%   |
| VIZ                     | 1         | 1.28%   |
| ViewSonic               | 1         | 1.28%   |
| VIE                     | 1         | 1.28%   |
| Vestel Elektronik       | 1         | 1.28%   |
| PANDA                   | 1         | 1.28%   |
| Nixeus                  | 1         | 1.28%   |
| NEC Computers           | 1         | 1.28%   |
| MiTAC                   | 1         | 1.28%   |
| LG Philips              | 1         | 1.28%   |
| Lenovo                  | 1         | 1.28%   |
| Gigabyte Technology     | 1         | 1.28%   |
| Eizo                    | 1         | 1.28%   |
| CSO                     | 1         | 1.28%   |
| Chi Mei Optoelectronics | 1         | 1.28%   |
| Belinea                 | 1         | 1.28%   |
| ASUSTek Computer        | 1         | 1.28%   |
| Apple                   | 1         | 1.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 2         | 2.47%   |
| VIZ LCD Monitor E60-E3 3840x2160                                          | 1         | 1.23%   |
| ViewSonic VG2756-2K VSC543A 2560x1440 597x336mm 27.0-inch                 | 1         | 1.23%   |
| VIE A2256 VIE2150 1920x1080 368x207mm 16.6-inch                           | 1         | 1.23%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1100x620mm 49.7-inch     | 1         | 1.23%   |
| Sony TV SNYEE01 1920x1080                                                 | 1         | 1.23%   |
| Sony TV SNYE903 1920x1080                                                 | 1         | 1.23%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 1         | 1.23%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 1         | 1.23%   |
| Samsung Electronics SyncMaster SAM0274 1440x900 410x260mm 19.1-inch       | 1         | 1.23%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 477x268mm 21.5-inch     | 1         | 1.23%   |
| Samsung Electronics S24C300 SAM0A24 1920x1080 531x299mm 24.0-inch         | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDC3150 1920x1080 344x194mm 15.5-inch     | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 700x390mm 31.5-inch     | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080 480x270mm 21.7-inch     | 1         | 1.23%   |
| Samsung Electronics C27F398 SAM0D45 1920x1080 598x336mm 27.0-inch         | 1         | 1.23%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 1         | 1.23%   |
| PANDA LCD Monitor NCP0058 1920x1080 344x194mm 15.5-inch                   | 1         | 1.23%   |
| Nixeus NX-VUE24 NIX2415 1920x1080 477x268mm 21.5-inch                     | 1         | 1.23%   |
| NEC Computers PA271W NEC67DA 2560x1440 600x340mm 27.2-inch                | 1         | 1.23%   |
| MiTAC DSGi TV SZM0308 1920x1080 880x490mm 39.7-inch                       | 1         | 1.23%   |
| LG Philips LCD Monitor LPL012B 1280x800 304x190mm 14.1-inch               | 1         | 1.23%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch               | 1         | 1.23%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x174mm 14.0-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD0391 1600x900 382x215mm 17.3-inch               | 1         | 1.23%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch               | 1         | 1.23%   |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch                   | 1         | 1.23%   |
| Hewlett-Packard w2408 HWP26CF 1920x1200 520x320mm 24.0-inch               | 1         | 1.23%   |
| Hewlett-Packard 24es HWP3320 1920x1080 527x296mm 23.8-inch                | 1         | 1.23%   |
| Hewlett-Packard 23f HPN3543 1920x1080 509x286mm 23.0-inch                 | 1         | 1.23%   |
| Goldstar ULTRAWIDE GSM76FA 2560x1080 531x298mm 24.0-inch                  | 1         | 1.23%   |
| Goldstar 34GL750 GSM773B 2560x1080 800x340mm 34.2-inch                    | 1         | 1.23%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch                  | 1         | 1.23%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch            | 1         | 1.23%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                         | 1         | 1.23%   |
| Dell U2719DX DEL41A4 2560x1440 597x336mm 27.0-inch                        | 1         | 1.23%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                          | 1         | 1.23%   |
| Dell U2415 DELA0B9 1920x1200 518x324mm 24.1-inch                          | 1         | 1.23%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                         | 1         | 1.23%   |
| Dell SX2210 DELA046 1920x1080 477x268mm 21.5-inch                         | 1         | 1.23%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                       | 1         | 1.23%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                         | 1         | 1.23%   |
| Dell E228WFP DELD014 1680x1050 473x296mm 22.0-inch                        | 1         | 1.23%   |
| Dell E207WFP DELD011 1680x1050 430x270mm 20.0-inch                        | 1         | 1.23%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                     | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 344x194mm 15.5-inch           | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch           | 1         | 1.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 1.23%   |
| BOE LCD Monitor BOE09CC 1920x1080 344x194mm 15.5-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE090F 1920x1080 344x194mm 15.5-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE08EC 3840x2160 344x194mm 15.5-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 1         | 1.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 32        | 46.38%  |
| 1366x768 (WXGA)    | 11        | 15.94%  |
| 2560x1440 (QHD)    | 7         | 10.14%  |
| 3840x2160 (4K)     | 3         | 4.35%   |
| 2560x1080          | 3         | 4.35%   |
| 2880x1800          | 2         | 2.9%    |
| 1920x1200 (WUXGA)  | 2         | 2.9%    |
| 1680x1050 (WSXGA+) | 2         | 2.9%    |
| 1280x800 (WXGA)    | 2         | 2.9%    |
| 2160x1440          | 1         | 1.45%   |
| 1920x540           | 1         | 1.45%   |
| 1600x900 (HD+)     | 1         | 1.45%   |
| 1440x900 (WXGA+)   | 1         | 1.45%   |
| 1280x1024 (SXGA)   | 1         | 1.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 23        | 30.26%  |
| 27      | 8         | 10.53%  |
| 24      | 8         | 10.53%  |
| 14      | 8         | 10.53%  |
| 17      | 4         | 5.26%   |
| 23      | 3         | 3.95%   |
| 21      | 3         | 3.95%   |
| 72      | 2         | 2.63%   |
| 40      | 2         | 2.63%   |
| 34      | 2         | 2.63%   |
| 84      | 1         | 1.32%   |
| 54      | 1         | 1.32%   |
| 39      | 1         | 1.32%   |
| 31      | 1         | 1.32%   |
| 28      | 1         | 1.32%   |
| 22      | 1         | 1.32%   |
| 20      | 1         | 1.32%   |
| 19      | 1         | 1.32%   |
| 16      | 1         | 1.32%   |
| 13      | 1         | 1.32%   |
| 12      | 1         | 1.32%   |
| 11      | 1         | 1.32%   |
| Unknown | 1         | 1.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 42.47%  |
| 501-600     | 16        | 21.92%  |
| 401-500     | 6         | 8.22%   |
| 351-400     | 5         | 6.85%   |
| 801-900     | 3         | 4.11%   |
| 201-300     | 3         | 4.11%   |
| 1501-2000   | 3         | 4.11%   |
| 701-800     | 2         | 2.74%   |
| 601-700     | 2         | 2.74%   |
| 1001-1500   | 1         | 1.37%   |
| Unknown     | 1         | 1.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 52        | 77.61%  |
| 16/10   | 9         | 13.43%  |
| 21/9    | 3         | 4.48%   |
| 5/4     | 1         | 1.49%   |
| 3/2     | 1         | 1.49%   |
| Unknown | 1         | 1.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 30.67%  |
| 81-90          | 9         | 12%     |
| 201-250        | 9         | 12%     |
| 301-350        | 8         | 10.67%  |
| More than 1000 | 4         | 5.33%   |
| 251-300        | 4         | 5.33%   |
| 151-200        | 4         | 5.33%   |
| 351-500        | 3         | 4%      |
| 121-130        | 3         | 4%      |
| 501-1000       | 3         | 4%      |
| 61-70          | 1         | 1.33%   |
| 51-60          | 1         | 1.33%   |
| 141-150        | 1         | 1.33%   |
| 111-120        | 1         | 1.33%   |
| Unknown        | 1         | 1.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 22        | 31.88%  |
| 121-160       | 21        | 30.43%  |
| 101-120       | 17        | 24.64%  |
| 1-50          | 3         | 4.35%   |
| 161-240       | 3         | 4.35%   |
| More than 240 | 2         | 2.9%    |
| Unknown       | 1         | 1.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 42        | 67.74%  |
| 2     | 14        | 22.58%  |
| 4     | 2         | 3.23%   |
| 3     | 2         | 3.23%   |
| 0     | 2         | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 35        | 38.89%  |
| Intel                 | 35        | 38.89%  |
| Qualcomm Atheros      | 8         | 8.89%   |
| Broadcom              | 4         | 4.44%   |
| Broadcom Limited      | 2         | 2.22%   |
| Samsung Electronics   | 1         | 1.11%   |
| Ralink Technology     | 1         | 1.11%   |
| Ralink                | 1         | 1.11%   |
| MEDIATEK              | 1         | 1.11%   |
| DisplayLink           | 1         | 1.11%   |
| Aquantia              | 1         | 1.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 22.22%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 3.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 3.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 3.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 2.78%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 2.78%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 2.78%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 2.78%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 2.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 1.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.85%   |
| Intel Wireless 7260                                               | 2         | 1.85%   |
| Intel Wireless 3165                                               | 2         | 1.85%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.85%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.85%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.85%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.85%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.93%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.93%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.93%   |
| Realtek Realtek Network controller                                | 1         | 0.93%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.93%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.93%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.93%   |
| Intel Wireless 8260                                               | 1         | 0.93%   |
| Intel Wireless 7265                                               | 1         | 0.93%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 0.93%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 0.93%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.93%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.93%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.93%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 0.93%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 0.93%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.93%   |
| DisplayLink USB 3.0 Dual Video Dock                               | 1         | 0.93%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.93%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.93%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 1         | 0.93%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 1         | 0.93%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1         | 0.93%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 0.93%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.93%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 48.98%  |
| Realtek Semiconductor | 12        | 24.49%  |
| Qualcomm Atheros      | 7         | 14.29%  |
| Broadcom              | 2         | 4.08%   |
| Ralink Technology     | 1         | 2.04%   |
| Ralink                | 1         | 2.04%   |
| MEDIATEK              | 1         | 2.04%   |
| Broadcom Limited      | 1         | 2.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 8.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 8.16%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 6.12%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 6.12%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 4.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 4.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 4.08%   |
| Intel Wireless 7260                                            | 2         | 4.08%   |
| Intel Wireless 3165                                            | 2         | 4.08%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 4.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 4.08%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.04%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.04%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 2.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 2.04%   |
| Realtek Realtek Network controller                             | 1         | 2.04%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 2.04%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 2.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 2.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 2.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 2.04%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 2.04%   |
| Intel Wireless 8260                                            | 1         | 2.04%   |
| Intel Wireless 7265                                            | 1         | 2.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 2.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 2.04%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 2.04%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 2.04%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 1         | 2.04%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1         | 2.04%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 29        | 51.79%  |
| Intel                 | 18        | 32.14%  |
| Qualcomm Atheros      | 3         | 5.36%   |
| Broadcom              | 2         | 3.57%   |
| Samsung Electronics   | 1         | 1.79%   |
| DisplayLink           | 1         | 1.79%   |
| Broadcom Limited      | 1         | 1.79%   |
| Aquantia              | 1         | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 40.68%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 6.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 5.08%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 5.08%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 5.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 3.39%   |
| Intel I211 Gigabit Network Connection                             | 2         | 3.39%   |
| Intel Ethernet Controller I225-V                                  | 2         | 3.39%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 3.39%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.69%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.69%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.69%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.69%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.69%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.69%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.69%   |
| DisplayLink USB 3.0 Dual Video Dock                               | 1         | 1.69%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.69%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.69%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 1         | 1.69%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 52        | 52%     |
| WiFi     | 48        | 48%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 57.97%  |
| Ethernet | 29        | 42.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 34        | 54.84%  |
| 1     | 25        | 40.32%  |
| 3     | 3         | 4.84%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 44        | 70.97%  |
| Yes  | 18        | 29.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 47.62%  |
| Realtek Semiconductor           | 5         | 11.9%   |
| Qualcomm Atheros Communications | 3         | 7.14%   |
| Lite-On Technology              | 3         | 7.14%   |
| IMC Networks                    | 3         | 7.14%   |
| Cambridge Silicon Radio         | 3         | 7.14%   |
| Broadcom                        | 2         | 4.76%   |
| Realtek                         | 1         | 2.38%   |
| Dell                            | 1         | 2.38%   |
| Apple                           | 1         | 2.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 7         | 16.67%  |
| Intel Bluetooth wireless interface                  | 5         | 11.9%   |
| Intel AX201 Bluetooth                               | 5         | 11.9%   |
| Realtek Bluetooth Radio                             | 4         | 9.52%   |
| Intel AX200 Bluetooth                               | 3         | 7.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 7.14%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 4.76%   |
| Lite-On Bluetooth Device                            | 2         | 4.76%   |
| IMC Networks Bluetooth Radio                        | 2         | 4.76%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.38%   |
| Realtek Bluetooth Radio                             | 1         | 2.38%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.38%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 2.38%   |
| IMC Networks Wireless_Device                        | 1         | 2.38%   |
| Dell BCM20702A0                                     | 1         | 2.38%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 2.38%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2.38%   |
| Apple Bluetooth Host Controller                     | 1         | 2.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 43        | 43.43%  |
| Nvidia                    | 21        | 21.21%  |
| AMD                       | 20        | 20.2%   |
| Sennheiser Communications | 2         | 2.02%   |
| Yamaha                    | 1         | 1.01%   |
| SAVITECH                  | 1         | 1.01%   |
| Samsung Electronics       | 1         | 1.01%   |
| RODE Microphones          | 1         | 1.01%   |
| Realtek Semiconductor     | 1         | 1.01%   |
| Razer USA                 | 1         | 1.01%   |
| Kingston Technology       | 1         | 1.01%   |
| Generalplus Technology    | 1         | 1.01%   |
| Creative Technology       | 1         | 1.01%   |
| Cambridge Silicon Radio   | 1         | 1.01%   |
| C-Media Electronics       | 1         | 1.01%   |
| Blue Microphones          | 1         | 1.01%   |
| ASUSTek Computer          | 1         | 1.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 5.98%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 5.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 5.13%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 4.27%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 3.42%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 3.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 3.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 3.42%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 2.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 2.56%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 2.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.56%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.56%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.71%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 2         | 1.71%   |
| Nvidia Audio device                                                                               | 2         | 1.71%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 1.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.71%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                                         | 2         | 1.71%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.71%   |
| Yamaha Steinberg UR22mkII                                                                         | 1         | 0.85%   |
| Sennheiser Communications Sennheiser USB headset                                                  | 1         | 0.85%   |
| Sennheiser Communications SC260 for MS II                                                         | 1         | 0.85%   |
| SAVITECH SA9023 USB Audio                                                                         | 1         | 0.85%   |
| Samsung Electronics USBC Headset                                                                  | 1         | 0.85%   |
| RODE Microphones RODE NT-USB                                                                      | 1         | 0.85%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.85%   |
| Razer USA RC30-026902, Gaming Headset [Nari Essential, Wireless, Receiver]                        | 1         | 0.85%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.85%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.85%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.85%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.85%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.85%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.85%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 1         | 0.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.85%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 0.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 0.85%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.85%   |
| Creative Technology SB Omni Surround 5.1                                                          | 1         | 0.85%   |
| Cambridge Silicon Radio Audioengine HD3                                                           | 1         | 0.85%   |
| C-Media Electronics USB Audio Device                                                              | 1         | 0.85%   |
| Blue Microphones Yeti Stereo Microphone                                                           | 1         | 0.85%   |
| ASUSTek Computer STRIX SOUND CARD                                                                 | 1         | 0.85%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.85%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 0.85%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.85%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.85%   |
| AMD FCH Azalia Controller                                                                         | 1         | 0.85%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 0.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1         | 0.85%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.85%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 22.39%  |
| SK Hynix            | 10        | 14.93%  |
| Kingston            | 8         | 11.94%  |
| Corsair             | 6         | 8.96%   |
| Micron Technology   | 5         | 7.46%   |
| Crucial             | 5         | 7.46%   |
| Team                | 3         | 4.48%   |
| Unknown             | 2         | 2.99%   |
| G.Skill             | 2         | 2.99%   |
| Avant               | 2         | 2.99%   |
| A-DATA Technology   | 2         | 2.99%   |
| Silicon Power       | 1         | 1.49%   |
| Patriot             | 1         | 1.49%   |
| Lexar Co Limited    | 1         | 1.49%   |
| Goldkey             | 1         | 1.49%   |
| GeIL                | 1         | 1.49%   |
| ASint Technology    | 1         | 1.49%   |
| Apacer              | 1         | 1.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s        | 2         | 2.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s           | 2         | 2.82%   |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 1.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                       | 1         | 1.41%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s             | 1         | 1.41%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s              | 1         | 1.41%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 8400MT/s            | 1         | 1.41%   |
| SK Hynix RAM Module 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.41%   |
| SK Hynix RAM HMT851S6AMR6R-PB N0 4GB Chip DDR3 1600MT/s         | 1         | 1.41%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.41%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.41%   |
| SK Hynix RAM HMT351S6CFR8A-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 1.41%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 1.41%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.41%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 1         | 1.41%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 1.41%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s       | 1         | 1.41%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s       | 1         | 1.41%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s     | 1         | 1.41%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 1.41%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                    | 1         | 1.41%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s           | 1         | 1.41%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.41%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.41%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s          | 1         | 1.41%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s          | 1         | 1.41%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s          | 1         | 1.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.41%   |
| Samsung RAM M378B5273DH0-CK0 4096MB DIMM DDR3 2200MT/s          | 1         | 1.41%   |
| Samsung RAM K4F8E304HB-MGCj 4GB SODIMM DDR4 2400MT/s            | 1         | 1.41%   |
| Patriot RAM PSD34G160082S 4GB SODIMM DDR3 1600MT/s              | 1         | 1.41%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB DIMM DDR3 1600MT/s             | 1         | 1.41%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s         | 1         | 1.41%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.41%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s           | 1         | 1.41%   |
| Micron RAM 18ADF2G72AZ-2G3B1 16GB DIMM DDR4 2666MT/s            | 1         | 1.41%   |
| Micron RAM 18ADF2G72AZ-2G3A1 16GB DIMM DDR4 2400MT/s            | 1         | 1.41%   |
| Lexar Co Limited RAM LD4AU016G-H3200GST 16GB DIMM DDR4 3200MT/s | 1         | 1.41%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s               | 1         | 1.41%   |
| Kingston RAM KHX2666C15D4/8G 8GB DIMM DDR4 2667MT/s             | 1         | 1.41%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s               | 1         | 1.41%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s             | 1         | 1.41%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s             | 1         | 1.41%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s               | 1         | 1.41%   |
| Kingston RAM HP655410-150 4GB DIMM DDR3 1600MT/s                | 1         | 1.41%   |
| Kingston RAM ACR16D3LU1NGG/4G 4GB DIMM DDR3 1600MT/s            | 1         | 1.41%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s          | 1         | 1.41%   |
| Goldkey RAM BKH400UD51208 4GB DIMM DDR3 1600MT/s                | 1         | 1.41%   |
| GeIL RAM CL9-9-9 D3-1333 8GB DIMM DDR3 1333MT/s                 | 1         | 1.41%   |
| G.Skill RAM F4-2666C18-16GRS 16GB SODIMM DDR4 2667MT/s          | 1         | 1.41%   |
| G.Skill RAM F3-12800CL9-4 4GB DIMM DDR3 1600MT/s                | 1         | 1.41%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s           | 1         | 1.41%   |
| Crucial RAM CT51264AC800.C16FC 4GB SODIMM DDR2 800MT/s          | 1         | 1.41%   |
| Crucial RAM CT4G4SFS824A.C8FHP 4GB SODIMM DDR4 2133MT/s         | 1         | 1.41%   |
| Crucial RAM BLS16G4D32AESE.M16FE 16GB DIMM DDR4 3733MT/s        | 1         | 1.41%   |
| Crucial RAM BLS16G4D240FSB.16FBD 16GB DIMM DDR4 2400MT/s        | 1         | 1.41%   |
| Corsair RAM CMW32GX4M2Z3200C16 16GB DIMM DDR4 3200MT/s          | 1         | 1.41%   |
| Corsair RAM CMW16GX4M2C3000C15 8GB DIMM DDR4 3200MT/s           | 1         | 1.41%   |
| Corsair RAM CMSX8GX4M1A2666C18 8GB SODIMM DDR4 2667MT/s         | 1         | 1.41%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s          | 1         | 1.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 36        | 64.29%  |
| DDR3   | 17        | 30.36%  |
| LPDDR4 | 2         | 3.57%   |
| DDR2   | 1         | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 31        | 54.39%  |
| DIMM         | 22        | 38.6%   |
| Row Of Chips | 3         | 5.26%   |
| Chip         | 1         | 1.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 21        | 35%     |
| 8192  | 20        | 33.33%  |
| 16384 | 16        | 26.67%  |
| 32768 | 2         | 3.33%   |
| 2048  | 1         | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 16        | 26.23%  |
| 1600  | 13        | 21.31%  |
| 2667  | 9         | 14.75%  |
| 2400  | 5         | 8.2%    |
| 1333  | 3         | 4.92%   |
| 3266  | 2         | 3.28%   |
| 8400  | 1         | 1.64%   |
| 4267  | 1         | 1.64%   |
| 3733  | 1         | 1.64%   |
| 3600  | 1         | 1.64%   |
| 3400  | 1         | 1.64%   |
| 3334  | 1         | 1.64%   |
| 3000  | 1         | 1.64%   |
| 2933  | 1         | 1.64%   |
| 2666  | 1         | 1.64%   |
| 2200  | 1         | 1.64%   |
| 2133  | 1         | 1.64%   |
| 1334  | 1         | 1.64%   |
| 800   | 1         | 1.64%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)

![Printer Vendor](./images/line_chart/printer_vendor.svg)

| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)

![Printer Model](./images/line_chart/printer_model.svg)

| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Brother MFC-L3750CDW | 1         | 100%    |

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

| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 10        | 22.22%  |
| IMC Networks                           | 8         | 17.78%  |
| Logitech                               | 5         | 11.11%  |
| Quanta                                 | 4         | 8.89%   |
| Realtek Semiconductor                  | 3         | 6.67%   |
| Sunplus Innovation Technology          | 2         | 4.44%   |
| Microdia                               | 2         | 4.44%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.44%   |
| Syntek                                 | 1         | 2.22%   |
| Razer USA                              | 1         | 2.22%   |
| OmniVision Technologies                | 1         | 2.22%   |
| Microsoft                              | 1         | 2.22%   |
| Lenovo                                 | 1         | 2.22%   |
| Hewlett-Packard                        | 1         | 2.22%   |
| GEMBIRD                                | 1         | 2.22%   |
| Apple                                  | 1         | 2.22%   |
| Anker                                  | 1         | 2.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 8         | 17.78%  |
| IMC Networks USB2.0 VGA UVC WebCam                  | 3         | 6.67%   |
| Quanta HD Webcam                                    | 2         | 4.44%   |
| Logitech Webcam C200                                | 2         | 4.44%   |
| IMC Networks Integrated Camera                      | 2         | 4.44%   |
| Syntek USB Video Device                             | 1         | 2.22%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 2.22%   |
| Sunplus HD WebCam                                   | 1         | 2.22%   |
| Realtek Integrated_Webcam_HD                        | 1         | 2.22%   |
| Realtek Integrated Webcam                           | 1         | 2.22%   |
| Realtek Asus laptop camera                          | 1         | 2.22%   |
| Razer USA Gaming Webcam [Kiyo]                      | 1         | 2.22%   |
| Quanta USB HD Webcam                                | 1         | 2.22%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 2.22%   |
| OmniVision Monitor Webcam                           | 1         | 2.22%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks | 1         | 2.22%   |
| Microdia Integrated_Webcam_HD                       | 1         | 2.22%   |
| Microdia Dell Integrated HD Webcam                  | 1         | 2.22%   |
| Logitech Webcam C930e                               | 1         | 2.22%   |
| Logitech HD Webcam C910                             | 1         | 2.22%   |
| Logitech HD Pro Webcam C920                         | 1         | 2.22%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 2.22%   |
| IMC Networks UVC VGA Webcam                         | 1         | 2.22%   |
| IMC Networks USB Camera                             | 1         | 2.22%   |
| IMC Networks USB 2.0 Camera                         | 1         | 2.22%   |
| HP Webcam HD 2300                                   | 1         | 2.22%   |
| GEMBIRD USB2.0 PC CAMERA                            | 1         | 2.22%   |
| Chicony USB 2.0 Camera                              | 1         | 2.22%   |
| Chicony HP Webcam                                   | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 2.22%   |
| Apple iPhone 5/5C/5S/6/SE                           | 1         | 2.22%   |
| Anker PowerConf C300                                | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 4         | 36.36%  |
| Validity Sensors           | 3         | 27.27%  |
| Shenzhen Goodix Technology | 3         | 27.27%  |
| Upek                       | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 27.27%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 9.09%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 9.09%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 9.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 9.09%   |
| Synaptics WBDI Device                                                      | 1         | 9.09%   |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 9.09%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./images/line_chart/chipcard_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Yubico.com            | 1         | 16.67%  |
| O2 Micro              | 1         | 16.67%  |
| Lenovo                | 1         | 16.67%  |
| Gemalto (was Gemplus) | 1         | 16.67%  |
| Cherry                | 1         | 16.67%  |
| Alcor Micro           | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)

![Chipcard Model](./images/line_chart/chipcard_model.svg)

| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Yubico.com Yubikey NEO(-N) OTP+CCID               | 1         | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader              | 1         | 16.67%  |
| Lenovo Integrated Smart Card Reader               | 1         | 16.67%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1         | 16.67%  |
| Cherry Smart Card Reader USB                      | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader               | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 44        | 70.97%  |
| 1     | 14        | 22.58%  |
| 2     | 4         | 6.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 11        | 50%     |
| Chipcard              | 5         | 22.73%  |
| Graphics card         | 3         | 13.64%  |
| Camera                | 2         | 9.09%   |
| Multimedia controller | 1         | 4.55%   |

