Elementary - Hardware Trends
----------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary/Desktop/README.md) and [notebooks](/Dist/Elementary/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: Jan, 2024.

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

| Name           | Computers | Percent |
|----------------|-----------|---------|
| Elementary 7.1 | 34        | 94.44%  |
| Elementary 6.1 | 2         | 5.56%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Elementary | 36        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 6.5.0-14-generic     | 11        | 30.56%  |
| 6.2.0-39-generic     | 9         | 25%     |
| 6.2.0-33-generic     | 7         | 19.44%  |
| 6.5.0-15-generic     | 5         | 13.89%  |
| 5.15.0-91-generic    | 2         | 5.56%   |
| 6.5.5-060505-generic | 1         | 2.78%   |
| 6.2.0-26-generic     | 1         | 2.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.0   | 17        | 47.22%  |
| 6.5.0   | 16        | 44.44%  |
| 5.15.0  | 2         | 5.56%   |
| 6.5.5   | 1         | 2.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.5     | 17        | 47.22%  |
| 6.2     | 17        | 47.22%  |
| 5.15    | 2         | 5.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 36        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Pantheon | 36        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 36        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 27        | 75%     |
| LightDM | 9         | 25%     |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 13        | 36.11%  |
| es_ES | 5         | 13.89%  |
| de_DE | 5         | 13.89%  |
| ru_RU | 4         | 11.11%  |
| it_IT | 2         | 5.56%   |
| tr_TR | 1         | 2.78%   |
| pt_BR | 1         | 2.78%   |
| hu_HU | 1         | 2.78%   |
| fr_FR | 1         | 2.78%   |
| fi_FI | 1         | 2.78%   |
| da_DK | 1         | 2.78%   |
| ar_EG | 1         | 2.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 29        | 80.56%  |
| EFI  | 7         | 19.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 31        | 86.11%  |
| Tmpfs | 4         | 11.11%  |
| Btrfs | 1         | 2.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 27        | 75%     |
| GPT     | 9         | 25%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 97.22%  |
| Yes       | 1         | 2.78%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Apple                | 8         | 22.22%  |
| Lenovo               | 6         | 16.67%  |
| Hewlett-Packard      | 4         | 11.11%  |
| Dell                 | 4         | 11.11%  |
| Gigabyte Technology  | 2         | 5.56%   |
| ASRock               | 2         | 5.56%   |
| Acer                 | 2         | 5.56%   |
| TECNO Mobile Limited | 1         | 2.78%   |
| Samsung Electronics  | 1         | 2.78%   |
| Positivo             | 1         | 2.78%   |
| Packard Bell         | 1         | 2.78%   |
| Medion               | 1         | 2.78%   |
| HUAWEI               | 1         | 2.78%   |
| Fujitsu              | 1         | 2.78%   |
| ASUSTek Computer     | 1         | 2.78%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Apple MacBookPro7,1                      | 2         | 5.56%   |
| TECNO Mobile Limited MEGABOOK T14TA      | 1         | 2.78%   |
| Samsung RC410/RC510/RC710                | 1         | 2.78%   |
| Positivo C4128A-15                       | 1         | 2.78%   |
| Packard Bell EasyNote TS11HR             | 1         | 2.78%   |
| Medion E11202                            | 1         | 2.78%   |
| Lenovo V17 G2 ITL 82NX                   | 1         | 2.78%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S2G103 | 1         | 2.78%   |
| Lenovo ThinkPad T480 20L6S3ED18          | 1         | 2.78%   |
| Lenovo ThinkPad T470 20JNS08H00          | 1         | 2.78%   |
| Lenovo ThinkPad L440 20AT0030MD          | 1         | 2.78%   |
| Lenovo IdeaPad 330S-15IKB 81F5           | 1         | 2.78%   |
| HUAWEI BOD-WXX9                          | 1         | 2.78%   |
| HP Pavilion g6                           | 1         | 2.78%   |
| HP Laptop 17-by3xxx                      | 1         | 2.78%   |
| HP EliteBook 840 G1                      | 1         | 2.78%   |
| HP Compaq Elite 8300 SFF                 | 1         | 2.78%   |
| Gigabyte EP43-UD3L                       | 1         | 2.78%   |
| Gigabyte B560M DS3H                      | 1         | 2.78%   |
| Fujitsu LIFEBOOK E734                    | 1         | 2.78%   |
| Dell XPS 13 7390 2-in-1                  | 1         | 2.78%   |
| Dell OptiPlex 9020                       | 1         | 2.78%   |
| Dell Latitude E7440                      | 1         | 2.78%   |
| Dell Latitude E7240                      | 1         | 2.78%   |
| ASUS VivoBook_ASUSLaptop X1504ZA_R1504ZA | 1         | 2.78%   |
| ASRock Z390 Phantom Gaming-ITX/ac        | 1         | 2.78%   |
| ASRock B75M-DGS R2.0                     | 1         | 2.78%   |
| Apple Macmini7,1                         | 1         | 2.78%   |
| Apple MacBookPro9,2                      | 1         | 2.78%   |
| Apple MacBook6,1                         | 1         | 2.78%   |
| Apple MacBook5,1                         | 1         | 2.78%   |
| Apple iMac13,1                           | 1         | 2.78%   |
| Apple iMac12,2                           | 1         | 2.78%   |
| Acer Aspire E5-573G                      | 1         | 2.78%   |
| Acer Aspire E5-571                       | 1         | 2.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 4         | 11.11%  |
| Dell Latitude                 | 2         | 5.56%   |
| Apple MacBookPro7             | 2         | 5.56%   |
| Acer Aspire                   | 2         | 5.56%   |
| TECNO Mobile Limited MEGABOOK | 1         | 2.78%   |
| Samsung RC410                 | 1         | 2.78%   |
| Positivo C4128A-15            | 1         | 2.78%   |
| Packard Bell EasyNote         | 1         | 2.78%   |
| Medion E11202                 | 1         | 2.78%   |
| Lenovo V17                    | 1         | 2.78%   |
| Lenovo IdeaPad                | 1         | 2.78%   |
| HUAWEI BOD-WXX9               | 1         | 2.78%   |
| HP Pavilion                   | 1         | 2.78%   |
| HP Laptop                     | 1         | 2.78%   |
| HP EliteBook                  | 1         | 2.78%   |
| HP Compaq                     | 1         | 2.78%   |
| Gigabyte EP43-UD3L            | 1         | 2.78%   |
| Gigabyte B560M                | 1         | 2.78%   |
| Fujitsu LIFEBOOK              | 1         | 2.78%   |
| Dell XPS                      | 1         | 2.78%   |
| Dell OptiPlex                 | 1         | 2.78%   |
| ASUS VivoBook                 | 1         | 2.78%   |
| ASRock Z390                   | 1         | 2.78%   |
| ASRock B75M-DGS               | 1         | 2.78%   |
| Apple Macmini7                | 1         | 2.78%   |
| Apple MacBookPro9             | 1         | 2.78%   |
| Apple MacBook6                | 1         | 2.78%   |
| Apple MacBook5                | 1         | 2.78%   |
| Apple iMac13                  | 1         | 2.78%   |
| Apple iMac12                  | 1         | 2.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2014 | 5         | 13.89%  |
| 2021 | 4         | 11.11%  |
| 2013 | 4         | 11.11%  |
| 2011 | 4         | 11.11%  |
| 2023 | 3         | 8.33%   |
| 2018 | 3         | 8.33%   |
| 2015 | 3         | 8.33%   |
| 2009 | 3         | 8.33%   |
| 2012 | 2         | 5.56%   |
| 2010 | 2         | 5.56%   |
| 2020 | 1         | 2.78%   |
| 2019 | 1         | 2.78%   |
| 2017 | 1         | 2.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 26        | 72.22%  |
| Desktop     | 6         | 16.67%  |
| All in one  | 2         | 5.56%   |
| Convertible | 1         | 2.78%   |
| Mini pc     | 1         | 2.78%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 36        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 36        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 14        | 38.89%  |
| 16.01-24.0 | 8         | 22.22%  |
| 3.01-4.0   | 7         | 19.44%  |
| 32.01-64.0 | 4         | 11.11%  |
| 8.01-16.0  | 2         | 5.56%   |
| 24.01-32.0 | 1         | 2.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 3.01-4.0 | 12        | 33.33%  |
| 2.01-3.0 | 11        | 30.56%  |
| 1.01-2.0 | 7         | 19.44%  |
| 4.01-8.0 | 5         | 13.89%  |
| 0.51-1.0 | 1         | 2.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 26        | 72.22%  |
| 2      | 8         | 22.22%  |
| 4      | 1         | 2.78%   |
| 3      | 1         | 2.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 25        | 69.44%  |
| Yes       | 11        | 30.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 80.56%  |
| No        | 7         | 19.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 88.89%  |
| No        | 4         | 11.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 77.78%  |
| No        | 8         | 22.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 5         | 13.89%  |
| Russia      | 3         | 8.33%   |
| Germany     | 3         | 8.33%   |
| Spain       | 2         | 5.56%   |
| Mexico      | 2         | 5.56%   |
| Brazil      | 2         | 5.56%   |
| Austria     | 2         | 5.56%   |
| UK          | 1         | 2.78%   |
| Turkey      | 1         | 2.78%   |
| Switzerland | 1         | 2.78%   |
| Slovakia    | 1         | 2.78%   |
| Romania     | 1         | 2.78%   |
| Puerto Rico | 1         | 2.78%   |
| Netherlands | 1         | 2.78%   |
| Italy       | 1         | 2.78%   |
| Hungary     | 1         | 2.78%   |
| France      | 1         | 2.78%   |
| Finland     | 1         | 2.78%   |
| Denmark     | 1         | 2.78%   |
| Canada      | 1         | 2.78%   |
| Belgium     | 1         | 2.78%   |
| Belarus     | 1         | 2.78%   |
| Argentina   | 1         | 2.78%   |
| Algeria     | 1         | 2.78%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City             | Computers | Percent |
|------------------|-----------|---------|
| Vienna           | 2         | 5.56%   |
| Moscow           | 2         | 5.56%   |
| Zhodzina         | 1         | 2.78%   |
| Zamora           | 1         | 2.78%   |
| Valby            | 1         | 2.78%   |
| Turku            | 1         | 2.78%   |
| Tahitotfalu      | 1         | 2.78%   |
| Sebastian        | 1         | 2.78%   |
| Rio Grande       | 1         | 2.78%   |
| Resistencia      | 1         | 2.78%   |
| Puebla City      | 1         | 2.78%   |
| Pelion           | 1         | 2.78%   |
| Paris            | 1         | 2.78%   |
| Oceanside        | 1         | 2.78%   |
| Nivelles         | 1         | 2.78%   |
| New Egypt        | 1         | 2.78%   |
| Murcia           | 1         | 2.78%   |
| Mundelein        | 1         | 2.78%   |
| Monza            | 1         | 2.78%   |
| Martin           | 1         | 2.78%   |
| Izmir            | 1         | 2.78%   |
| Ilsede           | 1         | 2.78%   |
| Greenwich        | 1         | 2.78%   |
| Grande Prairie   | 1         | 2.78%   |
| Feira de Santana | 1         | 2.78%   |
| Embu             | 1         | 2.78%   |
| Dordrecht        | 1         | 2.78%   |
| Chinchón        | 1         | 2.78%   |
| Chelyabinsk      | 1         | 2.78%   |
| Bremen           | 1         | 2.78%   |
| Berlin           | 1         | 2.78%   |
| Bellinzona       | 1         | 2.78%   |
| Baia Mare        | 1         | 2.78%   |
| Abadla           | 1         | 2.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 6         | 6      | 13.04%  |
| WDC                          | 4         | 5      | 8.7%    |
| Kingston                     | 4         | 4      | 8.7%    |
| Seagate                      | 3         | 3      | 6.52%   |
| KIOXIA                       | 3         | 3      | 6.52%   |
| Unknown                      | 2         | 2      | 4.35%   |
| Toshiba                      | 2         | 2      | 4.35%   |
| SanDisk                      | 2         | 2      | 4.35%   |
| Intel                        | 2         | 2      | 4.35%   |
| Crucial                      | 2         | 2      | 4.35%   |
| Apple                        | 2         | 2      | 4.35%   |
| XrayDisk                     | 1         | 1      | 2.17%   |
| Transcend                    | 1         | 1      | 2.17%   |
| SSK                          | 1         | 3      | 2.17%   |
| Shenzhen Longsys Electronics | 1         | 1      | 2.17%   |
| Phison Electronics           | 1         | 1      | 2.17%   |
| Patriot                      | 1         | 1      | 2.17%   |
| Micron/Crucial Technology    | 1         | 1      | 2.17%   |
| Micron Technology            | 1         | 1      | 2.17%   |
| MAXIO Technology (Hangzhou)  | 1         | 1      | 2.17%   |
| KingFast                     | 1         | 1      | 2.17%   |
| Hitachi                      | 1         | 1      | 2.17%   |
| HGST                         | 1         | 1      | 2.17%   |
| FC-1307                      | 1         | 1      | 2.17%   |
| Unknown                      | 1         | 1      | 2.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SUV500MS480G 480GB SSD                    | 2         | 4.17%   |
| XrayDisk 256GB SSD                                 | 1         | 2.08%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                   | 1         | 2.08%   |
| WDC WD1600AAJS-60M0A0 160GB                        | 1         | 2.08%   |
| WDC WD10EZEX-22MFCA0 1TB                           | 1         | 2.08%   |
| WDC WD10EZEX-21M2NA0 1TB                           | 1         | 2.08%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 1         | 2.08%   |
| Unknown MMC Card  64GB                             | 1         | 2.08%   |
| Unknown MMC Card  128GB                            | 1         | 2.08%   |
| Transcend TS256GMTS430S 256GB SSD                  | 1         | 2.08%   |
| Toshiba MQ04ABF100 1TB                             | 1         | 2.08%   |
| Toshiba MK3275GSX 320GB                            | 1         | 2.08%   |
| SSK Storage 2TB                                    | 1         | 2.08%   |
| SSK Disk 240GB                                     | 1         | 2.08%   |
| Shenzhen Longsys FORESEE XP1000F512G 512GB         | 1         | 2.08%   |
| Seagate ST9250315AS 250GB                          | 1         | 2.08%   |
| Seagate ST500LT012-1DG142 500GB                    | 1         | 2.08%   |
| Seagate ST500DM002-1BD142 500GB                    | 1         | 2.08%   |
| Sandisk WDC PC SN530 SDBPMPZ-256G-1101 256GB       | 1         | 2.08%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD                | 1         | 2.08%   |
| Samsung SSD 970 EVO 1TB S5H9NS1NA36053L            | 1         | 2.08%   |
| Samsung SSD 860 EVO 250GB                          | 1         | 2.08%   |
| Samsung SSD 850 PRO 128GB                          | 1         | 2.08%   |
| Samsung SSD 850 EVO 500GB                          | 1         | 2.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 1         | 2.08%   |
| Samsung MZ7TE256HMHP-00004 256GB SSD               | 1         | 2.08%   |
| Phison PS5013 E13 NVMe Controller 256GB            | 1         | 2.08%   |
| Patriot Burst 120GB SSD                            | 1         | 2.08%   |
| Micron/Crucial CT2000P5PSSD8 2TB                   | 1         | 2.08%   |
| Micron 2450_MTFDKBA256TFK 256GB                    | 1         | 2.08%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB | 1         | 2.08%   |
| KIOXIA KBG40ZPZ1T02 NVMe 1024GB                    | 1         | 2.08%   |
| KIOXIA KBG40ZNV512G 512GB                          | 1         | 2.08%   |
| KIOXIA KBG40ZNV256G 256GB                          | 1         | 2.08%   |
| Kingston SV300S37A120G 120GB SSD                   | 1         | 2.08%   |
| Kingston SA400S37120G 120GB SSD                    | 1         | 2.08%   |
| KingFast 512GB                                     | 1         | 2.08%   |
| Intel SSDSCKJF240A5L 240GB                         | 1         | 2.08%   |
| Intel SSD 660P Series 1024GB                       | 1         | 2.08%   |
| Hitachi HTS543216A7A384 160GB                      | 1         | 2.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 4      | 21.43%  |
| Seagate | 3         | 3      | 21.43%  |
| Toshiba | 2         | 2      | 14.29%  |
| Apple   | 2         | 2      | 14.29%  |
| SSK     | 1         | 2      | 7.14%   |
| Hitachi | 1         | 1      | 7.14%   |
| HGST    | 1         | 1      | 7.14%   |
| FC-1307 | 1         | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 25%     |
| Kingston            | 4         | 4      | 25%     |
| Crucial             | 2         | 2      | 12.5%   |
| XrayDisk            | 1         | 1      | 6.25%   |
| WDC                 | 1         | 1      | 6.25%   |
| Transcend           | 1         | 1      | 6.25%   |
| SanDisk             | 1         | 1      | 6.25%   |
| Patriot             | 1         | 1      | 6.25%   |
| Intel               | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 14        | 16     | 33.33%  |
| HDD     | 14        | 16     | 33.33%  |
| NVMe    | 11        | 13     | 26.19%  |
| MMC     | 2         | 3      | 4.76%   |
| Unknown | 1         | 1      | 2.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 26        | 31     | 65%     |
| NVMe | 11        | 12     | 27.5%   |
| MMC  | 2         | 3      | 5%      |
| SAS  | 1         | 3      | 2.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 22        | 25     | 78.57%  |
| 0.51-1.0   | 6         | 7      | 21.43%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 16        | 44.44%  |
| 251-500    | 9         | 25%     |
| 501-1000   | 6         | 16.67%  |
| 51-100     | 3         | 8.33%   |
| 2001-3000  | 1         | 2.78%   |
| 1001-2000  | 1         | 2.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 15        | 41.67%  |
| 21-50    | 12        | 33.33%  |
| 251-500  | 3         | 8.33%   |
| 101-250  | 3         | 8.33%   |
| 501-1000 | 2         | 5.56%   |
| 51-100   | 1         | 2.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 31        | 41     | 86.11%  |
| Works    | 5         | 8      | 13.89%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 28        | 63.64%  |
| Nvidia                       | 4         | 9.09%   |
| KIOXIA                       | 3         | 6.82%   |
| Samsung Electronics          | 2         | 4.55%   |
| Shenzhen Longsys Electronics | 1         | 2.27%   |
| SanDisk                      | 1         | 2.27%   |
| Phison Electronics           | 1         | 2.27%   |
| Micron/Crucial Technology    | 1         | 2.27%   |
| Micron Technology            | 1         | 2.27%   |
| MAXIO Technology (Hangzhou)  | 1         | 2.27%   |
| JMicron Technology           | 1         | 2.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                                                              | Computers | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                                       | 5         | 10.2%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                                                         | 3         | 6.12%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]                                       | 3         | 6.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 2         | 4.08%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                                                           | 2         | 4.08%   |
| Nvidia MCP79 AHCI Controller                                                                                       | 2         | 4.08%   |
| Intel Volume Management Device NVMe RAID Controller                                                                | 2         | 4.08%   |
| Intel Tiger Lake-LP SATA Controller                                                                                | 2         | 4.08%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 2         | 4.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                                                     | 2         | 4.08%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 1         | 2.04%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                                                              | 1         | 2.04%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                                                | 1         | 2.04%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                                                               | 1         | 2.04%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                                                        | 1         | 2.04%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                                           | 1         | 2.04%   |
| JMicron JMB368 IDE controller                                                                                      | 1         | 2.04%   |
| Intel SSD 660P Series                                                                                              | 1         | 2.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                                             | 1         | 2.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                                           | 1         | 2.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                                                         | 1         | 2.04%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                                                         | 1         | 2.04%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                                                         | 1         | 2.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]                                     | 1         | 2.04%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]                                      | 1         | 2.04%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]                                      | 1         | 2.04%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile                                         | 1         | 2.04%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 1         | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)                             | 1         | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)                             | 1         | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                                       | 1         | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller                                      | 1         | 2.04%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                                               | 1         | 2.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                                                     | 1         | 2.04%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 25        | 56.82%  |
| NVMe | 11        | 25%     |
| RAID | 4         | 9.09%   |
| IDE  | 4         | 9.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 36        | 100%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 5.56%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 5.56%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 2         | 5.56%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 2         | 5.56%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 1         | 2.78%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 2.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 2.78%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 1         | 2.78%   |
| Intel Core i7-4578U CPU @ 3.00GHz       | 1         | 2.78%   |
| Intel Core i7-3770S CPU @ 3.10GHz       | 1         | 2.78%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 1         | 2.78%   |
| Intel Core i7-10700 CPU @ 2.90GHz       | 1         | 2.78%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 1         | 2.78%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 2.78%   |
| Intel Core i5-4310M CPU @ 2.70GHz       | 1         | 2.78%   |
| Intel Core i5-4200M CPU @ 2.50GHz       | 1         | 2.78%   |
| Intel Core i5-3330S CPU @ 2.70GHz       | 1         | 2.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 2.78%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 1         | 2.78%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 1         | 2.78%   |
| Intel Core i3-4010U CPU @ 1.70GHz       | 1         | 2.78%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 1         | 2.78%   |
| Intel Core i3 CPU M 380 @ 2.53GHz       | 1         | 2.78%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz   | 1         | 2.78%   |
| Intel Core 2 Duo CPU P8800 @ 2.66GHz    | 1         | 2.78%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz    | 1         | 2.78%   |
| Intel Celeron N4020C CPU @ 1.10GHz      | 1         | 2.78%   |
| Intel Celeron CPU N3450 @ 1.10GHz       | 1         | 2.78%   |
| Intel 12th Gen Core i3-1215U            | 1         | 2.78%   |
| Intel 11th Gen Core i5-1155G7 @ 2.50GHz | 1         | 2.78%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 1         | 2.78%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 1         | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i7     | 11        | 30.56%  |
| Intel Core i5     | 11        | 30.56%  |
| Other             | 4         | 11.11%  |
| Intel Core 2 Duo  | 4         | 11.11%  |
| Intel Core i3     | 3         | 8.33%   |
| Intel Celeron     | 2         | 5.56%   |
| Intel Core 2 Quad | 1         | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 20        | 55.56%  |
| 4      | 13        | 36.11%  |
| 6      | 2         | 5.56%   |
| 8      | 1         | 2.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 36        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 26        | 72.22%  |
| 1      | 10        | 27.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 36        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 34        | 94.44%  |
| 0x806c1 | 1         | 2.78%   |
| 0x206a7 | 1         | 2.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 10        | 27.78%  |
| Penryn        | 5         | 13.89%  |
| SandyBridge   | 4         | 11.11%  |
| TigerLake     | 3         | 8.33%   |
| KabyLake      | 3         | 8.33%   |
| IvyBridge     | 3         | 8.33%   |
| IceLake       | 2         | 5.56%   |
| Westmere      | 1         | 2.78%   |
| Skylake       | 1         | 2.78%   |
| Goldmont plus | 1         | 2.78%   |
| Goldmont      | 1         | 2.78%   |
| CometLake     | 1         | 2.78%   |
| Unknown       | 1         | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 28        | 66.67%  |
| Nvidia | 11        | 26.19%  |
| AMD    | 3         | 7.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                            | 7         | 16.67%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 9.52%   |
| Nvidia MCP89 [GeForce 320M]                                                 | 2         | 4.76%   |
| Nvidia C79 [GeForce 9400M]                                                  | 2         | 4.76%   |
| Intel UHD Graphics 620                                                      | 2         | 4.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 4.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 4.76%   |
| Nvidia GT218M [GeForce 315M]                                                | 1         | 2.38%   |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 2.38%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1         | 2.38%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1         | 2.38%   |
| Nvidia GM108M [GeForce 940M]                                                | 1         | 2.38%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1         | 2.38%   |
| Nvidia GK107M [GeForce GT 640M Mac Edition]                                 | 1         | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 2.38%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                   | 1         | 2.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 2.38%   |
| Intel Iris Plus Graphics G7                                                 | 1         | 2.38%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 1         | 2.38%   |
| Intel HD Graphics 500                                                       | 1         | 2.38%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 2.38%   |
| Intel Core Processor Integrated Graphics Controller                         | 1         | 2.38%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1         | 2.38%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                     | 1         | 2.38%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 1         | 2.38%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                  | 1         | 2.38%   |
| AMD Mars [Radeon HD 8730M]                                                  | 1         | 2.38%   |
| AMD Blackcomb [Radeon HD 6970M/6990M]                                       | 1         | 2.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 22        | 61.11%  |
| 1 x Nvidia     | 8         | 22.22%  |
| Intel + Nvidia | 3         | 8.33%   |
| Intel + AMD    | 2         | 5.56%   |
| 1 x AMD        | 1         | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 32        | 88.89%  |
| Proprietary | 3         | 8.33%   |
| Unknown     | 1         | 2.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 91.67%  |
| 0.01-0.5   | 2         | 5.56%   |
| 3.01-4.0   | 1         | 2.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Apple               | 7         | 19.44%  |
| LG Display          | 6         | 16.67%  |
| AU Optronics        | 6         | 16.67%  |
| Samsung Electronics | 3         | 8.33%   |
| Hewlett-Packard     | 2         | 5.56%   |
| Goldstar            | 2         | 5.56%   |
| Chimei Innolux      | 2         | 5.56%   |
| BOE                 | 2         | 5.56%   |
| Sharp               | 1         | 2.78%   |
| Philips             | 1         | 2.78%   |
| Mi                  | 1         | 2.78%   |
| KDB                 | 1         | 2.78%   |
| HKC                 | 1         | 2.78%   |
| Dell                | 1         | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch               | 2         | 5.56%   |
| Sharp LCD Monitor SHP14A8 3840x2400 288x180mm 13.4-inch              | 1         | 2.78%   |
| Samsung Electronics SyncMaster SAM0247 1280x1024 376x301mm 19.0-inch | 1         | 2.78%   |
| Samsung Electronics LS27A600U SAM7172 2560x1440 600x340mm 27.2-inch  | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch | 1         | 2.78%   |
| Philips 244E PHLC036 1920x1080 521x293mm 23.5-inch                   | 1         | 2.78%   |
| Mi 27 NFGL XMIB004 1920x1080 598x336mm 27.0-inch                     | 1         | 2.78%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 1         | 2.78%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x174mm 14.0-inch         | 1         | 2.78%   |
| LG Display LCD Monitor LGD03EA 1920x1080 309x174mm 14.0-inch         | 1         | 2.78%   |
| LG Display LCD Monitor LGD03DC 1366x768 277x156mm 12.5-inch          | 1         | 2.78%   |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch          | 1         | 2.78%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch          | 1         | 2.78%   |
| KDB LCD Monitor KDB1130 1366x768 256x144mm 11.6-inch                 | 1         | 2.78%   |
| HKC LCD Monitor HKC0200 1920x1200 302x188mm 14.0-inch                | 1         | 2.78%   |
| Hewlett-Packard ENVY 27 HPN3367 3840x2160 597x336mm 27.0-inch        | 1         | 2.78%   |
| Hewlett-Packard 27f HPN354C 1920x1080 598x336mm 27.0-inch            | 1         | 2.78%   |
| Goldstar W2443 GSM571B 1920x1080 474x296mm 22.0-inch                 | 1         | 2.78%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 1         | 2.78%   |
| Dell S2718H/HX DELD0B2 1920x1080 598x336mm 27.0-inch                 | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN175E 1920x1080 381x214mm 17.2-inch     | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN1541 1366x768 344x193mm 15.5-inch      | 1         | 2.78%   |
| BOE LCD Monitor BOE09C1 1920x1080 382x215mm 17.3-inch                | 1         | 2.78%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch       | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO103D 1920x1080 309x173mm 13.9-inch       | 1         | 2.78%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch               | 1         | 2.78%   |
| Apple LCD Monitor APP9C89 1280x800 286x179mm 13.3-inch               | 1         | 2.78%   |
| Apple iMac APPA012 1920x1080 475x267mm 21.5-inch                     | 1         | 2.78%   |
| Apple iMac APPA007 2560x1440 597x336mm 27.0-inch                     | 1         | 2.78%   |
| Apple Color LCD APP9CC0 1280x800 261x163mm 12.1-inch                 | 1         | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 13        | 36.11%  |
| 1366x768 (WXGA)   | 10        | 27.78%  |
| 1280x800 (WXGA)   | 5         | 13.89%  |
| 2560x1440 (QHD)   | 3         | 8.33%   |
| 3840x2160 (4K)    | 2         | 5.56%   |
| 3840x2400         | 1         | 2.78%   |
| 1920x1200 (WUXGA) | 1         | 2.78%   |
| 1280x1024 (SXGA)  | 1         | 2.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 8         | 22.22%  |
| 27     | 7         | 19.44%  |
| 13     | 7         | 19.44%  |
| 14     | 5         | 13.89%  |
| 17     | 2         | 5.56%   |
| 12     | 2         | 5.56%   |
| 23     | 1         | 2.78%   |
| 22     | 1         | 2.78%   |
| 21     | 1         | 2.78%   |
| 19     | 1         | 2.78%   |
| 11     | 1         | 2.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 41.67%  |
| 501-600     | 8         | 22.22%  |
| 201-300     | 8         | 22.22%  |
| 351-400     | 3         | 8.33%   |
| 401-500     | 2         | 5.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 26        | 74.29%  |
| 16/10 | 8         | 22.86%  |
| 5/4   | 1         | 2.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 10        | 27.78%  |
| 101-110        | 8         | 22.22%  |
| 301-350        | 7         | 19.44%  |
| 201-250        | 3         | 8.33%   |
| 71-80          | 2         | 5.56%   |
| 61-70          | 2         | 5.56%   |
| 121-130        | 2         | 5.56%   |
| 51-60          | 1         | 2.78%   |
| 151-200        | 1         | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 15        | 42.86%  |
| 121-160       | 10        | 28.57%  |
| 51-100        | 5         | 14.29%  |
| 161-240       | 4         | 11.43%  |
| More than 240 | 1         | 2.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 32        | 88.89%  |
| 2     | 3         | 8.33%   |
| 0     | 1         | 2.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 15        | 28.3%   |
| Realtek Semiconductor             | 11        | 20.75%  |
| Broadcom                          | 11        | 20.75%  |
| Qualcomm Atheros                  | 4         | 7.55%   |
| Samsung Electronics               | 2         | 3.77%   |
| Nvidia                            | 2         | 3.77%   |
| Broadcom Limited                  | 2         | 3.77%   |
| TP-Link                           | 1         | 1.89%   |
| Sierra Wireless                   | 1         | 1.89%   |
| Qualcomm Atheros Communications   | 1         | 1.89%   |
| MediaTek                          | 1         | 1.89%   |
| Hewlett-Packard                   | 1         | 1.89%   |
| Ericsson Business Mobile Networks | 1         | 1.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 7         | 10.61%  |
| Intel Wireless 7260                                                    | 6         | 9.09%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 6.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3         | 4.55%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 3         | 4.55%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 3.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2         | 3.03%   |
| Nvidia MCP79 Ethernet                                                  | 2         | 3.03%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 3.03%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 3.03%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 2         | 3.03%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 3.03%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 3.03%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                  | 1         | 1.52%   |
| Sierra Wireless EM7305 Modem                                           | 1         | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1         | 1.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 1.52%   |
| Qualcomm Atheros AR9271 802.11n                                        | 1         | 1.52%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 1         | 1.52%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 1         | 1.52%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 1         | 1.52%   |
| Intel Wireless 8265 / 8275                                             | 1         | 1.52%   |
| Intel Wireless 8260                                                    | 1         | 1.52%   |
| Intel Wireless 7265                                                    | 1         | 1.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 1         | 1.52%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.52%   |
| Intel Ethernet Connection I217-V                                       | 1         | 1.52%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 1.52%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 1         | 1.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1         | 1.52%   |
| HP lt4112 Gobi 4G Module Network Device                                | 1         | 1.52%   |
| Ericsson Business Mobile Networks N5321 gw                             | 1         | 1.52%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 1.52%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 1         | 1.52%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                                 | 1         | 1.52%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 1         | 1.52%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 1         | 1.52%   |
| Broadcom BCM43142 802.11b/g/n                                          | 1         | 1.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 1         | 1.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 13        | 36.11%  |
| Broadcom                          | 7         | 19.44%  |
| Realtek Semiconductor             | 4         | 11.11%  |
| Qualcomm Atheros                  | 4         | 11.11%  |
| Broadcom Limited                  | 2         | 5.56%   |
| TP-Link                           | 1         | 2.78%   |
| Sierra Wireless                   | 1         | 2.78%   |
| Qualcomm Atheros Communications   | 1         | 2.78%   |
| MediaTek                          | 1         | 2.78%   |
| Hewlett-Packard                   | 1         | 2.78%   |
| Ericsson Business Mobile Networks | 1         | 2.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                  | 6         | 16.67%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 3         | 8.33%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 3         | 8.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 2         | 5.56%   |
| Intel Wi-Fi 6 AX201                                                  | 2         | 5.56%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                | 1         | 2.78%   |
| Sierra Wireless EM7305 Modem                                         | 1         | 2.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1         | 2.78%   |
| Qualcomm Atheros AR9271 802.11n                                      | 1         | 2.78%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 1         | 2.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 1         | 2.78%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                    | 1         | 2.78%   |
| Intel Wireless 8265 / 8275                                           | 1         | 2.78%   |
| Intel Wireless 8260                                                  | 1         | 2.78%   |
| Intel Wireless 7265                                                  | 1         | 2.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 1         | 2.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 2.78%   |
| HP lt4112 Gobi 4G Module Network Device                              | 1         | 2.78%   |
| Ericsson Business Mobile Networks N5321 gw                           | 1         | 2.78%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 1         | 2.78%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                               | 1         | 2.78%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 1         | 2.78%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 1         | 2.78%   |
| Broadcom BCM43142 802.11b/g/n                                        | 1         | 2.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 1         | 2.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 11        | 36.67%  |
| Realtek Semiconductor | 8         | 26.67%  |
| Broadcom              | 7         | 23.33%  |
| Samsung Electronics   | 2         | 6.67%   |
| Nvidia                | 2         | 6.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 7         | 23.33%  |
| Intel Ethernet Connection I218-LM                                      | 4         | 13.33%  |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 6.67%   |
| Nvidia MCP79 Ethernet                                                  | 2         | 6.67%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 6.67%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 2         | 6.67%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 6.67%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 6.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 3.33%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 3.33%   |
| Intel Ethernet Connection I217-V                                       | 1         | 3.33%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 3.33%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 3.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1         | 3.33%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 52.46%  |
| Ethernet | 29        | 47.54%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 67.57%  |
| Ethernet | 12        | 32.43%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 22        | 61.11%  |
| 1     | 14        | 38.89%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 20        | 55.56%  |
| Yes  | 16        | 44.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 42.86%  |
| Apple                           | 8         | 28.57%  |
| Realtek Semiconductor           | 3         | 10.71%  |
| Qualcomm Atheros Communications | 1         | 3.57%   |
| Lite-On Technology              | 1         | 3.57%   |
| IMC Networks                    | 1         | 3.57%   |
| Foxconn / Hon Hai               | 1         | 3.57%   |
| Cambridge Silicon Radio         | 1         | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 28.57%  |
| Apple Bluetooth Host Controller                     | 5         | 17.86%  |
| Intel AX201 Bluetooth                               | 3         | 10.71%  |
| Realtek Bluetooth Radio                             | 2         | 7.14%   |
| Apple Bluetooth USB Host Controller                 | 2         | 7.14%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.57%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 3.57%   |
| Lite-On BCM43142A0                                  | 1         | 3.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 3.57%   |
| IMC Networks Wireless_Device                        | 1         | 3.57%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 3.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.57%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 32        | 74.42%  |
| Nvidia | 9         | 20.93%  |
| AMD    | 2         | 4.65%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 13.21%  |
| Intel 8 Series HD Audio Controller                                         | 7         | 13.21%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 7.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 5.66%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 5.66%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 5.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 5.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 5.66%   |
| Nvidia MCP89 High Definition Audio                                         | 2         | 3.77%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 3.77%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 3.77%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.89%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.89%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 1.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.89%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.89%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 1.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.89%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.89%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 1.89%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 1.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1.89%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                 | 1         | 1.89%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 33.33%  |
| SK hynix            | 1         | 16.67%  |
| Kingston            | 1         | 16.67%  |
| Elpida              | 1         | 16.67%  |
| Corsair             | 1         | 16.67%  |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s            | 1         | 16.67%  |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s             | 1         | 16.67%  |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s   | 1         | 16.67%  |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 2667MT/s | 1         | 16.67%  |
| Elpida RAM EBJ40UG8EFU0-GN-F 4GB SODIMM DDR3 1600MT/s   | 1         | 16.67%  |
| Corsair RAM Module 4GB SODIMM DDR3 1067MT/s             | 1         | 16.67%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| DDR3 | 4         | 66.67%  |
| DDR4 | 2         | 33.33%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 6         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 2         | 33.33%  |
| 4096  | 2         | 33.33%  |
| 16384 | 1         | 16.67%  |
| 2048  | 1         | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 2         | 33.33%  |
| 1600  | 2         | 33.33%  |
| 1067  | 2         | 33.33%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)

![Printer Vendor](./All/images/line_chart/printer_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)

![Printer Model](./All/images/line_chart/printer_model.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 300 | 1         | 100%    |

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

| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Apple                                  | 6         | 20.69%  |
| Chicony Electronics                    | 4         | 13.79%  |
| Cheng Uei Precision Industry (Foxlink) | 3         | 10.34%  |
| Bison Electronics                      | 3         | 10.34%  |
| Microdia                               | 2         | 6.9%    |
| Suyin                                  | 1         | 3.45%   |
| Sunplus Innovation Technology          | 1         | 3.45%   |
| Sonix Technology                       | 1         | 3.45%   |
| ShineTech                              | 1         | 3.45%   |
| Samsung Electronics                    | 1         | 3.45%   |
| Quanta                                 | 1         | 3.45%   |
| OYT Tech                               | 1         | 3.45%   |
| MacroSilicon                           | 1         | 3.45%   |
| Logitech                               | 1         | 3.45%   |
| Acer                                   | 1         | 3.45%   |
| Unknown                                | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Apple Built-in iSight                                | 3         | 10.34%  |
| Microdia Integrated Webcam                           | 2         | 6.9%    |
| Chicony Integrated Camera                            | 2         | 6.9%    |
| Bison Integrated Camera                              | 2         | 6.9%    |
| Apple FaceTime HD Camera (Built-in)                  | 2         | 6.9%    |
| Suyin HD WebCam                                      | 1         | 3.45%   |
| Sunplus 1.3M HD WebCam                               | 1         | 3.45%   |
| Sonix Usb Camera                                     | 1         | 3.45%   |
| ShineTech USB2.0 HD UVC WebCam                       | 1         | 3.45%   |
| Samsung Galaxy series, misc. (MTP mode)              | 1         | 3.45%   |
| Quanta HD Camera                                     | 1         | 3.45%   |
| OYT Tech OYV1RDFF1                                   | 1         | 3.45%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]        | 1         | 3.45%   |
| Logitech Webcam C925e                                | 1         | 3.45%   |
| Chicony HD WebCam                                    | 1         | 3.45%   |
| Chicony FJ Camera                                    | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101 | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam     | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam  | 1         | 3.45%   |
| Bison Integrated IR Camera                           | 1         | 3.45%   |
| Apple FaceTime HD Camera                             | 1         | 3.45%   |
| Acer SunplusIT Integrated Camera                     | 1         | 3.45%   |
| Unknown                                              | 1         | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 50%     |
| Synaptics                  | 1         | 25%     |
| Shenzhen Goodix Technology | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader       | 1         | 25%     |
| Validity Sensors VFS 5011 fingerprint sensor     | 1         | 25%     |
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 25%     |
| Shenzhen Goodix  Fingerprint Device              | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./All/images/line_chart/chipcard_vendor.svg)

| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 66.67%  |
| O2 Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 66.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 24        | 66.67%  |
| 1     | 9         | 25%     |
| 2     | 3         | 8.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 5         | 33.33%  |
| Fingerprint reader    | 4         | 26.67%  |
| Chipcard              | 3         | 20%     |
| Multimedia controller | 1         | 6.67%   |
| Graphics card         | 1         | 6.67%   |
| Camera                | 1         | 6.67%   |

