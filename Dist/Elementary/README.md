Elementary - Hardware Trends
----------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary/Desktop/README.md) and [notebooks](/Dist/Elementary/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: Dec, 2025.

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
| Elementary 8   | 30        | 88.24%  |
| Elementary 7.1 | 3         | 8.82%   |
| Elementary 6.1 | 1         | 2.94%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Elementary | 34        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 6.14.0-37-generic  | 13        | 38.24%  |
| 6.14.0-36-generic  | 9         | 26.47%  |
| 6.14.0-29-generic  | 6         | 17.65%  |
| 6.8.0-87-generic   | 2         | 5.88%   |
| 6.8.0-49-generic   | 1         | 2.94%   |
| 6.8.0-40-generic   | 1         | 2.94%   |
| 6.11.0-19-generic  | 1         | 2.94%   |
| 5.15.0-139-generic | 1         | 2.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.14.0  | 28        | 82.35%  |
| 6.8.0   | 4         | 11.76%  |
| 6.11.0  | 1         | 2.94%   |
| 5.15.0  | 1         | 2.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.14    | 28        | 82.35%  |
| 6.8     | 4         | 11.76%  |
| 6.11    | 1         | 2.94%   |
| 5.15    | 1         | 2.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 34        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Pantheon | 34        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 19        | 55.88%  |
| X11     | 15        | 44.12%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 32        | 94.12%  |
| LightDM | 2         | 5.88%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 14        | 41.18%  |
| fr_FR | 5         | 14.71%  |
| es_ES | 5         | 14.71%  |
| de_DE | 3         | 8.82%   |
| it_IT | 2         | 5.88%   |
| ru_RU | 1         | 2.94%   |
| nl_NL | 1         | 2.94%   |
| nb_NO | 1         | 2.94%   |
| en_GB | 1         | 2.94%   |
| da_DK | 1         | 2.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 32        | 94.12%  |
| EFI  | 2         | 5.88%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type | Computers | Percent |
|------|-----------|---------|
| Ext4 | 34        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 32        | 94.12%  |
| GPT     | 2         | 5.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 34        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 34        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Apple               | 10        | 29.41%  |
| Hewlett-Packard     | 7         | 20.59%  |
| Dell                | 7         | 20.59%  |
| ASUSTek Computer    | 3         | 8.82%   |
| Lenovo              | 2         | 5.88%   |
| Acer                | 2         | 5.88%   |
| Timi                | 1         | 2.94%   |
| IceWhale Technology | 1         | 2.94%   |
| Biostar             | 1         | 2.94%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Apple MacBookPro8,1                  | 4         | 11.76%  |
| Apple iMac10,1                       | 2         | 5.88%   |
| Timi TM1701                          | 1         | 2.94%   |
| Lenovo ThinkCentre M92P 3237A1U      | 1         | 2.94%   |
| Lenovo LOQ 15APH8 82XT               | 1         | 2.94%   |
| IceWhale ZBB001-BK30032 ZMB          | 1         | 2.94%   |
| HP Victus by Gaming Laptop 15-fb0xxx | 1         | 2.94%   |
| HP ProBook 455 G8 Notebook PC        | 1         | 2.94%   |
| HP Pavilion dv7                      | 1         | 2.94%   |
| HP Pavilion dv6                      | 1         | 2.94%   |
| HP Laptop 15-bs1xx                   | 1         | 2.94%   |
| HP EliteBook 845 G7 Notebook PC      | 1         | 2.94%   |
| HP 15 Notebook PC                    | 1         | 2.94%   |
| Dell XPS 15 9530                     | 1         | 2.94%   |
| Dell Vostro1710                      | 1         | 2.94%   |
| Dell OptiPlex 7010                   | 1         | 2.94%   |
| Dell Latitude E5550                  | 1         | 2.94%   |
| Dell Latitude E5470                  | 1         | 2.94%   |
| Dell Latitude 7480                   | 1         | 2.94%   |
| Dell Latitude 5580                   | 1         | 2.94%   |
| Biostar H61MLV2                      | 1         | 2.94%   |
| ASUS PRIME B450M-A II                | 1         | 2.94%   |
| ASUS K93SV                           | 1         | 2.94%   |
| ASUS GL752VW                         | 1         | 2.94%   |
| Apple MacBookPro9,2                  | 1         | 2.94%   |
| Apple MacBookPro9,1                  | 1         | 2.94%   |
| Apple MacBookPro11,1                 | 1         | 2.94%   |
| Apple iMac9,1                        | 1         | 2.94%   |
| Acer Veriton Z4640G                  | 1         | 2.94%   |
| Acer Aspire E1-572                   | 1         | 2.94%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell Latitude           | 4         | 11.76%  |
| Apple MacBookPro8       | 4         | 11.76%  |
| HP Pavilion             | 2         | 5.88%   |
| Apple MacBookPro9       | 2         | 5.88%   |
| Apple iMac10            | 2         | 5.88%   |
| Timi TM1701             | 1         | 2.94%   |
| Lenovo ThinkCentre      | 1         | 2.94%   |
| Lenovo LOQ              | 1         | 2.94%   |
| IceWhale ZBB001-BK30032 | 1         | 2.94%   |
| HP Victus               | 1         | 2.94%   |
| HP ProBook              | 1         | 2.94%   |
| HP Laptop               | 1         | 2.94%   |
| HP EliteBook            | 1         | 2.94%   |
| HP 15                   | 1         | 2.94%   |
| Dell XPS                | 1         | 2.94%   |
| Dell Vostro1710         | 1         | 2.94%   |
| Dell OptiPlex           | 1         | 2.94%   |
| Biostar H61MLV2         | 1         | 2.94%   |
| ASUS PRIME              | 1         | 2.94%   |
| ASUS K93SV              | 1         | 2.94%   |
| ASUS GL752VW            | 1         | 2.94%   |
| Apple MacBookPro11      | 1         | 2.94%   |
| Apple iMac9             | 1         | 2.94%   |
| Acer Veriton            | 1         | 2.94%   |
| Acer Aspire             | 1         | 2.94%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2012 | 5         | 14.71%  |
| 2011 | 5         | 14.71%  |
| 2017 | 4         | 11.76%  |
| 2014 | 3         | 8.82%   |
| 2009 | 3         | 8.82%   |
| 2008 | 3         | 8.82%   |
| 2023 | 2         | 5.88%   |
| 2020 | 2         | 5.88%   |
| 2016 | 2         | 5.88%   |
| 2015 | 2         | 5.88%   |
| 2022 | 1         | 2.94%   |
| 2021 | 1         | 2.94%   |
| 2013 | 1         | 2.94%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 25        | 73.53%  |
| Desktop    | 5         | 14.71%  |
| All in one | 4         | 11.76%  |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 33        | 97.06%  |
| Enabled  | 1         | 2.94%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 34        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 9         | 26.47%  |
| 3.01-4.0   | 8         | 23.53%  |
| 16.01-24.0 | 7         | 20.59%  |
| 8.01-16.0  | 7         | 20.59%  |
| 32.01-64.0 | 2         | 5.88%   |
| 24.01-32.0 | 1         | 2.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 14        | 41.18%  |
| 1.01-2.0 | 9         | 26.47%  |
| 3.01-4.0 | 7         | 20.59%  |
| 4.01-8.0 | 4         | 11.76%  |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 22        | 64.71%  |
| 2      | 9         | 26.47%  |
| 3      | 3         | 8.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 19        | 55.88%  |
| Yes       | 15        | 44.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 85.29%  |
| No        | 5         | 14.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 91.18%  |
| No        | 3         | 8.82%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 76.47%  |
| No        | 8         | 23.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country   | Computers | Percent |
|-----------|-----------|---------|
| USA       | 6         | 17.65%  |
| France    | 4         | 11.76%  |
| UK        | 3         | 8.82%   |
| Italy     | 3         | 8.82%   |
| Germany   | 3         | 8.82%   |
| Spain     | 2         | 5.88%   |
| Indonesia | 2         | 5.88%   |
| Slovakia  | 1         | 2.94%   |
| Russia    | 1         | 2.94%   |
| Portugal  | 1         | 2.94%   |
| Norway    | 1         | 2.94%   |
| Mexico    | 1         | 2.94%   |
| Japan     | 1         | 2.94%   |
| India     | 1         | 2.94%   |
| Denmark   | 1         | 2.94%   |
| Canada    | 1         | 2.94%   |
| Bolivia   | 1         | 2.94%   |
| Belgium   | 1         | 2.94%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City            | Computers | Percent |
|-----------------|-----------|---------|
| Milan           | 2         | 5.88%   |
| Žilina         | 1         | 2.94%   |
| Vechelde        | 1         | 2.94%   |
| Vadodara        | 1         | 2.94%   |
| Toronto         | 1         | 2.94%   |
| Toms River      | 1         | 2.94%   |
| St Petersburg   | 1         | 2.94%   |
| Seattle         | 1         | 2.94%   |
| Salatiga        | 1         | 2.94%   |
| Rosny-sous-Bois | 1         | 2.94%   |
| Porto           | 1         | 2.94%   |
| Overijse        | 1         | 2.94%   |
| Oslo            | 1         | 2.94%   |
| New York        | 1         | 2.94%   |
| Münster        | 1         | 2.94%   |
| Manchester      | 1         | 2.94%   |
| Madrid          | 1         | 2.94%   |
| Lille           | 1         | 2.94%   |
| La Paz          | 1         | 2.94%   |
| Jakarta         | 1         | 2.94%   |
| Ixtapaluca      | 1         | 2.94%   |
| High Wycombe    | 1         | 2.94%   |
| Gonzales        | 1         | 2.94%   |
| Chatan          | 1         | 2.94%   |
| Cesson          | 1         | 2.94%   |
| Calcinaia       | 1         | 2.94%   |
| Brumath         | 1         | 2.94%   |
| Brondby Strand  | 1         | 2.94%   |
| Bromley         | 1         | 2.94%   |
| Berlin          | 1         | 2.94%   |
| Barcelona       | 1         | 2.94%   |
| Aurora          | 1         | 2.94%   |
| Atlanta         | 1         | 2.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 9         | 9      | 18.75%  |
| Sandisk                      | 5         | 5      | 10.42%  |
| Kingston                     | 5         | 6      | 10.42%  |
| Seagate                      | 4         | 4      | 8.33%   |
| WDC                          | 3         | 3      | 6.25%   |
| Toshiba                      | 3         | 3      | 6.25%   |
| SK hynix                     | 2         | 2      | 4.17%   |
| KingSpec                     | 2         | 2      | 4.17%   |
| Hitachi                      | 2         | 2      | 4.17%   |
| Crucial                      | 2         | 2      | 4.17%   |
| V-GeN                        | 1         | 1      | 2.08%   |
| Unknown                      | 1         | 1      | 2.08%   |
| Shenzhen Longsys Electronics | 1         | 1      | 2.08%   |
| Patriot                      | 1         | 1      | 2.08%   |
| MAXIO Technology (Hangzhou)  | 1         | 1      | 2.08%   |
| Kingston Technology Company  | 1         | 1      | 2.08%   |
| JMicron Technology           | 1         | 1      | 2.08%   |
| Fujitsu                      | 1         | 1      | 2.08%   |
| China                        | 1         | 1      | 2.08%   |
| Apple                        | 1         | 1      | 2.08%   |
| A-DATA Technology            | 1         | 1      | 2.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                          | 3         | 6.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 2         | 4.17%   |
| WDC WD5000BPKX-75HPJT0 500GB                       | 1         | 2.08%   |
| WDC WD1600BEVT-00A1TT0 160GB                       | 1         | 2.08%   |
| WDC WD10EZEX-00MFCA0 1TB                           | 1         | 2.08%   |
| V-GeN V-GEN07SM19EG240GBIT                         | 1         | 2.08%   |
| Unknown MMC Card  32GB                             | 1         | 2.08%   |
| Toshiba THNSNJ256GCSU 256GB SSD                    | 1         | 2.08%   |
| Toshiba MQ01ABD100V -63 1TB                        | 1         | 2.08%   |
| Toshiba MK3259GSXP 320GB                           | 1         | 2.08%   |
| SK hynix SC311 SATA 512GB SSD                      | 1         | 2.08%   |
| SK hynix PC711 HFS512GDE9X073N 512GB               | 1         | 2.08%   |
| Shenzhen Longsys Lexar SSD NM620 256GB             | 1         | 2.08%   |
| Seagate ST9500420AS 500GB                          | 1         | 2.08%   |
| Seagate ST9320325AS 320GB                          | 1         | 2.08%   |
| Seagate ST500LT012-1DG142 500GB                    | 1         | 2.08%   |
| Seagate ST31000528AS 1TB                           | 1         | 2.08%   |
| Sandisk Western Digital SN560E 1TB                 | 1         | 2.08%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB              | 1         | 2.08%   |
| Sandisk WD Black SN850 1TB                         | 1         | 2.08%   |
| SanDisk NVMe SSD Drive 500GB                       | 1         | 2.08%   |
| SanDisk 3.2 Gen 1 250GB SSD                        | 1         | 2.08%   |
| Samsung SSD 850 EVO 500GB                          | 1         | 2.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 1         | 2.08%   |
| Samsung MZYTN512HDJH-000 512GB SSD                 | 1         | 2.08%   |
| Samsung MZNLF128HCHP-00004 128GB SSD               | 1         | 2.08%   |
| Patriot Burst Elite 240GB SSD                      | 1         | 2.08%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 2TB   | 1         | 2.08%   |
| Kingston Company SNV2S1000G 1TB                    | 1         | 2.08%   |
| Kingston SKC600512G 512GB SSD                      | 1         | 2.08%   |
| Kingston SHSS37A240G 240GB SSD                     | 1         | 2.08%   |
| Kingston SA400S37480G 480GB SSD                    | 1         | 2.08%   |
| Kingston SA400S37240G 240GB SSD                    | 1         | 2.08%   |
| Kingston OCP0S3128B-A0 128GB SSD                   | 1         | 2.08%   |
| KingSpec P3-1TB SSD                                | 1         | 2.08%   |
| KingSpec MT-256 256GB SSD                          | 1         | 2.08%   |
| JMicron Disk 1TB                                   | 1         | 2.08%   |
| Hitachi HTS545050B9A300 500GB                      | 1         | 2.08%   |
| Hitachi HTS545032B9A302 320GB                      | 1         | 2.08%   |
| Fujitsu MJA2500BH G2 500GB                         | 1         | 2.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 33.33%  |
| WDC     | 3         | 3      | 25%     |
| Toshiba | 2         | 2      | 16.67%  |
| Hitachi | 2         | 2      | 16.67%  |
| Fujitsu | 1         | 1      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 26.09%  |
| Kingston            | 5         | 6      | 21.74%  |
| KingSpec            | 2         | 2      | 8.7%    |
| Crucial             | 2         | 2      | 8.7%    |
| Toshiba             | 1         | 1      | 4.35%   |
| SK hynix            | 1         | 1      | 4.35%   |
| SanDisk             | 1         | 1      | 4.35%   |
| Patriot             | 1         | 1      | 4.35%   |
| JMicron Technology  | 1         | 1      | 4.35%   |
| China               | 1         | 1      | 4.35%   |
| Apple               | 1         | 1      | 4.35%   |
| A-DATA Technology   | 1         | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 18        | 24     | 45%     |
| HDD     | 12        | 12     | 30%     |
| NVMe    | 8         | 11     | 20%     |
| MMC     | 1         | 1      | 2.5%    |
| Unknown | 1         | 1      | 2.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 27        | 34     | 69.23%  |
| NVMe | 8         | 11     | 20.51%  |
| SAS  | 3         | 3      | 7.69%   |
| MMC  | 1         | 1      | 2.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 22        | 28     | 75.86%  |
| 0.51-1.0   | 7         | 8      | 24.14%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 15        | 44.12%  |
| 101-250    | 9         | 26.47%  |
| 501-1000   | 6         | 17.65%  |
| 21-50      | 1         | 2.94%   |
| 1001-2000  | 1         | 2.94%   |
| 1-20       | 1         | 2.94%   |
| 51-100     | 1         | 2.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 15        | 44.12%  |
| 21-50    | 13        | 38.24%  |
| 101-250  | 4         | 11.76%  |
| 501-1000 | 1         | 2.94%   |
| 51-100   | 1         | 2.94%   |

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
| Detected | 34        | 48     | 97.14%  |
| Works    | 1         | 1      | 2.86%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 22        | 55%     |
| Sandisk                          | 4         | 10%     |
| Samsung Electronics              | 4         | 10%     |
| Nvidia                           | 3         | 7.5%    |
| AMD                              | 2         | 5%      |
| SK hynix                         | 1         | 2.5%    |
| Silicon Integrated Systems [SiS] | 1         | 2.5%    |
| Shenzhen Longsys Electronics     | 1         | 2.5%    |
| MAXIO Technology (Hangzhou)      | 1         | 2.5%    |
| Kingston Technology Company      | 1         | 2.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 13.95%  |
| Nvidia MCP79 AHCI Controller                                                            | 3         | 6.98%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 6.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 4.65%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2         | 4.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2         | 4.65%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 2         | 4.65%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 1         | 2.33%   |
| Silicon Integrated Systems [SiS] AHCI IDE Controller (0106)                             | 1         | 2.33%   |
| Shenzhen Longsys Lexar NM610 PRO NVME SSD (DRAM-less)                                   | 1         | 2.33%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1         | 2.33%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                              | 1         | 2.33%   |
| Sandisk WD Blue SN5100 NVMe SSD (DRAM-less)                                             | 1         | 2.33%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 1         | 2.33%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                              | 1         | 2.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 2.33%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 1         | 2.33%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 1         | 2.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1         | 2.33%   |
| Intel RST Volume Management Device Controller                                           | 1         | 2.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 2.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 2.33%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 2.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 2.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 2.33%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1         | 2.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 24        | 63.16%  |
| NVMe | 8         | 21.05%  |
| RAID | 4         | 10.53%  |
| IDE  | 2         | 5.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 28        | 82.35%  |
| AMD    | 6         | 17.65%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2435M CPU @ 2.40GHz           | 3         | 8.82%   |
| Intel Core 2 Duo CPU E7600 @ 3.06GHz        | 2         | 5.88%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1         | 2.94%   |
| Intel Pentium CPU 4417U @ 2.30GHz           | 1         | 2.94%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 2.94%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 2.94%   |
| Intel Core i7-3615QM CPU @ 2.30GHz          | 1         | 2.94%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 2.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 2.94%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 2.94%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 2.94%   |
| Intel Core i5-4278U CPU @ 2.60GHz           | 1         | 2.94%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 2.94%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1         | 2.94%   |
| Intel Core i5-3470T CPU @ 2.90GHz           | 1         | 2.94%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 2.94%   |
| Intel Core i5-2415M CPU @ 2.30GHz           | 1         | 2.94%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 2.94%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1         | 2.94%   |
| Intel Core i3-5010U CPU @ 2.10GHz           | 1         | 2.94%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 1         | 2.94%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 1         | 2.94%   |
| Intel Core 2 Duo CPU E8135 @ 2.66GHz        | 1         | 2.94%   |
| Intel Atom Processor E3950 @ 1.60GHz        | 1         | 2.94%   |
| Intel 13th Gen Core i7-13700H               | 1         | 2.94%   |
| AMD Ryzen 7 7840HS w/ Radeon 780M Graphics  | 1         | 2.94%   |
| AMD Ryzen 7 5800U with Radeon Graphics      | 1         | 2.94%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics  | 1         | 2.94%   |
| AMD Ryzen 5 5600H with Radeon Graphics      | 1         | 2.94%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 1         | 2.94%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 1         | 2.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 13        | 38.24%  |
| Intel Core 2 Duo | 5         | 14.71%  |
| Intel Core i7    | 4         | 11.76%  |
| Intel Pentium    | 2         | 5.88%   |
| Intel Core i3    | 2         | 5.88%   |
| AMD Ryzen 7      | 2         | 5.88%   |
| AMD Ryzen 5      | 2         | 5.88%   |
| Other            | 1         | 2.94%   |
| Intel Atom       | 1         | 2.94%   |
| AMD Ryzen 5 PRO  | 1         | 2.94%   |
| AMD A8           | 1         | 2.94%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 21        | 61.76%  |
| 4      | 7         | 20.59%  |
| 6      | 3         | 8.82%   |
| 8      | 2         | 5.88%   |
| 14     | 1         | 2.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 34        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 25        | 73.53%  |
| 1      | 9         | 26.47%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 34        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 33        | 97.06%  |
| 0x1067a | 1         | 2.94%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| SandyBridge | 6         | 17.65%  |
| Penryn      | 5         | 14.71%  |
| IvyBridge   | 5         | 14.71%  |
| KabyLake    | 4         | 11.76%  |
| Skylake     | 3         | 8.82%   |
| Zen 3       | 2         | 5.88%   |
| Haswell     | 2         | 5.88%   |
| Unknown     | 2         | 5.88%   |
| Zen+        | 1         | 2.94%   |
| Zen 2       | 1         | 2.94%   |
| Puma        | 1         | 2.94%   |
| Goldmont    | 1         | 2.94%   |
| Broadwell   | 1         | 2.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 22        | 53.66%  |
| Nvidia | 10        | 24.39%  |
| AMD    | 9         | 21.95%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 6         | 14.63%  |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 2         | 4.88%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                     | 2         | 4.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 4.88%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 4.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 4.88%   |
| Nvidia MCP7A [GeForce 9400]                                               | 1         | 2.44%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 2.44%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 2.44%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                               | 1         | 2.44%   |
| Nvidia GF108M [GeForce GT 540M]                                           | 1         | 2.44%   |
| Nvidia GF108 [GeForce GT 730]                                             | 1         | 2.44%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 2.44%   |
| Nvidia G86M [GeForce 8600M GS]                                            | 1         | 2.44%   |
| Nvidia C79 [GeForce 9400]                                                 | 1         | 2.44%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                           | 1         | 2.44%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                     | 1         | 2.44%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 1         | 2.44%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                   | 1         | 2.44%   |
| Intel Kaby Lake-U GT1 [HD Graphics 610]                                   | 1         | 2.44%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                   | 1         | 2.44%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                  | 1         | 2.44%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                  | 1         | 2.44%   |
| Intel Apollo Lake [HD Graphics 505]                                       | 1         | 2.44%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 1         | 2.44%   |
| AMD RV730/M96-XT [Mobility Radeon HD 4670]                                | 1         | 2.44%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]          | 1         | 2.44%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]               | 1         | 2.44%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                  | 1         | 2.44%   |
| AMD Phoenix1                                                              | 1         | 2.44%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 1         | 2.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 50%     |
| 1 x AMD        | 6         | 17.65%  |
| 1 x Nvidia     | 4         | 11.76%  |
| Intel + Nvidia | 4         | 11.76%  |
| AMD + Nvidia   | 2         | 5.88%   |
| Intel + AMD    | 1         | 2.94%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 33        | 97.06%  |
| Proprietary | 1         | 2.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 91.18%  |
| 0.01-0.5   | 2         | 5.88%   |
| 0.51-1.0   | 1         | 2.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Apple                   | 10        | 32.26%  |
| AU Optronics            | 5         | 16.13%  |
| BOE                     | 4         | 12.9%   |
| LG Display              | 3         | 9.68%   |
| Samsung Electronics     | 2         | 6.45%   |
| Chimei Innolux          | 2         | 6.45%   |
| AOC                     | 2         | 6.45%   |
| Goldstar                | 1         | 3.23%   |
| Chi Mei Optoelectronics | 1         | 3.23%   |
| Acer                    | 1         | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch             | 2         | 6.45%   |
| Apple LCD Monitor APP9CCB 1280x800 286x179mm 13.3-inch                    | 2         | 6.45%   |
| Samsung Electronics S27E650 SAM0CC9 1920x1080 598x336mm 27.0-inch         | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch      | 1         | 3.23%   |
| LG Display LCD Monitor LGD06CA 1920x1080 309x174mm 14.0-inch              | 1         | 3.23%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch              | 1         | 3.23%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch              | 1         | 3.23%   |
| Goldstar 32 FHD GSM7700 1920x1080 698x392mm 31.5-inch                     | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch          | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x174mm 14.0-inch           | 1         | 3.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1807 1920x1080 408x230mm 18.4-inch | 1         | 3.23%   |
| BOE LCD Monitor BOE094D 1920x1080 344x194mm 15.5-inch                     | 1         | 3.23%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                     | 1         | 3.23%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                     | 1         | 3.23%   |
| BOE LCD Monitor BOE06EE 1920x1080 309x173mm 13.9-inch                     | 1         | 3.23%   |
| AU Optronics LCD Monitor AUOE3A1 1920x1080 344x193mm 15.5-inch            | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch             | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO11ED 1920x1080 344x193mm 15.5-inch            | 1         | 3.23%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                    | 1         | 3.23%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                    | 1         | 3.23%   |
| Apple Color LCD APPA020 2560x1600 286x179mm 13.3-inch                     | 1         | 3.23%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                      | 1         | 3.23%   |
| Apple Color LCD APP9CBC 1920x1080 475x267mm 21.5-inch                     | 1         | 3.23%   |
| Apple Color LCD APP9CB7 1680x1050 331x207mm 15.4-inch                     | 1         | 3.23%   |
| Apple Color LCD APP9CB5 2560x1440 597x336mm 27.0-inch                     | 1         | 3.23%   |
| Apple Color LCD APP9C96 1920x1200 520x320mm 24.0-inch                     | 1         | 3.23%   |
| AOC K27U3D AOC2703 3840x2160 597x336mm 27.0-inch                          | 1         | 3.23%   |
| AOC 2481W AOC2481 1920x1080 527x296mm 23.8-inch                           | 1         | 3.23%   |
| Acer AIO LCD ACRF132 1920x1080 509x286mm 23.0-inch                        | 1         | 3.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 14        | 46.67%  |
| 1366x768 (WXGA)    | 5         | 16.67%  |
| 1280x800 (WXGA)    | 5         | 16.67%  |
| 1920x1200 (WUXGA)  | 2         | 6.67%   |
| 3840x2160 (4K)     | 1         | 3.33%   |
| 2560x1600          | 1         | 3.33%   |
| 2560x1440 (QHD)    | 1         | 3.33%   |
| 1680x1050 (WSXGA+) | 1         | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 12        | 38.71%  |
| 13     | 7         | 22.58%  |
| 27     | 3         | 9.68%   |
| 14     | 2         | 6.45%   |
| 31     | 1         | 3.23%   |
| 26     | 1         | 3.23%   |
| 24     | 1         | 3.23%   |
| 23     | 1         | 3.23%   |
| 21     | 1         | 3.23%   |
| 18     | 1         | 3.23%   |
| 17     | 1         | 3.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 48.39%  |
| 501-600     | 6         | 19.35%  |
| 201-300     | 6         | 19.35%  |
| 401-500     | 2         | 6.45%   |
| 601-700     | 1         | 3.23%   |
| 351-400     | 1         | 3.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 20        | 66.67%  |
| 16/10 | 10        | 33.33%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 11        | 35.48%  |
| 81-90          | 6         | 19.35%  |
| 301-350        | 4         | 12.9%   |
| 71-80          | 3         | 9.68%   |
| 201-250        | 2         | 6.45%   |
| 351-500        | 1         | 3.23%   |
| 251-300        | 1         | 3.23%   |
| 141-150        | 1         | 3.23%   |
| 121-130        | 1         | 3.23%   |
| 111-120        | 1         | 3.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 13        | 41.94%  |
| 121-160 | 11        | 35.48%  |
| 51-100  | 5         | 16.13%  |
| 161-240 | 2         | 6.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 33        | 97.06%  |
| 2     | 1         | 2.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 14        | 27.45%  |
| Intel                 | 14        | 27.45%  |
| Broadcom              | 9         | 17.65%  |
| Qualcomm Atheros      | 5         | 9.8%    |
| Nvidia                | 3         | 5.88%   |
| MediaTek              | 2         | 3.92%   |
| TP-Link               | 1         | 1.96%   |
| Qualcomm              | 1         | 1.96%   |
| Broadcom Limited      | 1         | 1.96%   |
| ASIX Electronics      | 1         | 1.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12        | 18.75%  |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 6         | 9.38%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 6         | 9.38%   |
| Nvidia MCP79 Ethernet                                                  | 3         | 4.69%   |
| Intel Wireless 7265                                                    | 3         | 4.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 2         | 3.13%   |
| Intel Wireless 8265 / 8275                                             | 2         | 3.13%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 3.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 3.13%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                              | 1         | 1.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1         | 1.56%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1         | 1.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 1.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 1.56%   |
| Realtek 802.11ac NIC                                                   | 1         | 1.56%   |
| Qualcomm YUPIK-QRD _SN:AC1D5909                                        | 1         | 1.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1         | 1.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1         | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1         | 1.56%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1         | 1.56%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 1         | 1.56%   |
| Intel Wireless 8260                                                    | 1         | 1.56%   |
| Intel WiGig(802.11ad) wireless network connection                      | 1         | 1.56%   |
| Intel Wi-Fi 6 AX200                                                    | 1         | 1.56%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 1         | 1.56%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 1         | 1.56%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.56%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 1.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1         | 1.56%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                          | 1         | 1.56%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 1         | 1.56%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 1         | 1.56%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 1         | 1.56%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                      | 1         | 1.56%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 1.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 11        | 35.48%  |
| Broadcom              | 8         | 25.81%  |
| Qualcomm Atheros      | 5         | 16.13%  |
| Realtek Semiconductor | 3         | 9.68%   |
| MediaTek              | 2         | 6.45%   |
| TP-Link               | 1         | 3.23%   |
| Broadcom Limited      | 1         | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4331 802.11a/b/g/n                                       | 6         | 18.75%  |
| Intel Wireless 7265                                                  | 3         | 9.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 2         | 6.25%   |
| Intel Wireless 8265 / 8275                                           | 2         | 6.25%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                            | 1         | 3.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 3.13%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 3.13%   |
| Realtek 802.11ac NIC                                                 | 1         | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1         | 3.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1         | 3.13%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 1         | 3.13%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 1         | 3.13%   |
| Intel Wireless 8260                                                  | 1         | 3.13%   |
| Intel WiGig(802.11ad) wireless network connection                    | 1         | 3.13%   |
| Intel Wi-Fi 6 AX200                                                  | 1         | 3.13%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 1         | 3.13%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection              | 1         | 3.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1         | 3.13%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 1         | 3.13%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 1         | 3.13%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 1         | 3.13%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                    | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 13        | 41.94%  |
| Broadcom              | 7         | 22.58%  |
| Intel                 | 6         | 19.35%  |
| Nvidia                | 3         | 9.68%   |
| Qualcomm              | 1         | 3.23%   |
| ASIX Electronics      | 1         | 3.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12        | 37.5%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 6         | 18.75%  |
| Nvidia MCP79 Ethernet                                                  | 3         | 9.38%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 6.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 6.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 3.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 3.13%   |
| Qualcomm YUPIK-QRD _SN:AC1D5909                                        | 1         | 3.13%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 3.13%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 3.13%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 1         | 3.13%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 3.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 51.67%  |
| Ethernet | 29        | 48.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 72.97%  |
| Ethernet | 10        | 27.03%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 24        | 70.59%  |
| 1     | 8         | 23.53%  |
| 3     | 1         | 2.94%   |
| 0     | 1         | 2.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 19        | 55.88%  |
| Yes  | 15        | 44.12%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 38.46%  |
| Apple                           | 10        | 38.46%  |
| Realtek Semiconductor           | 2         | 7.69%   |
| Foxconn / Hon Hai               | 2         | 7.69%   |
| Qualcomm Atheros Communications | 1         | 3.85%   |
| Lite-On Technology              | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 6         | 23.08%  |
| Apple Bluetooth Host Controller                  | 5         | 19.23%  |
| Apple Built-in Bluetooth 2.0+EDR HCI             | 3         | 11.54%  |
| Apple Bluetooth USB Host Controller              | 2         | 7.69%   |
| Realtek Bluetooth Radio                          | 1         | 3.85%   |
| Realtek Bluetooth 5.4 Radio                      | 1         | 3.85%   |
| Qualcomm Atheros  Bluetooth Device               | 1         | 3.85%   |
| Lite-On Atheros AR3012 Bluetooth                 | 1         | 3.85%   |
| Intel Wireless-AC 3168 Bluetooth                 | 1         | 3.85%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 3.85%   |
| Intel Bluetooth Device                           | 1         | 3.85%   |
| Intel AX200 Bluetooth                            | 1         | 3.85%   |
| Foxconn / Hon Hai Wireless_Device                | 1         | 3.85%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter     | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 25        | 60.98%  |
| Nvidia | 8         | 19.51%  |
| AMD    | 8         | 19.51%  |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 14.29%  |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 10.2%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 8.16%   |
| AMD Ryzen HD Audio Controller                                              | 4         | 8.16%   |
| Nvidia MCP79 High Definition Audio                                         | 3         | 6.12%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 3         | 6.12%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 4.08%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 4.08%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 4.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 4.08%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 4.08%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 2.04%   |
| Nvidia GA107 High Definition Audio Controller                              | 1         | 2.04%   |
| Nvidia AD107 High Definition Audio Controller                              | 1         | 2.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.04%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 1         | 2.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 2.04%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.04%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 2.04%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 2.04%   |
| AMD FCH Azalia Controller                                                  | 1         | 2.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 2.04%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 2.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| SK hynix          | 1         | 33.33%  |
| Micron Technology | 1         | 33.33%  |
| Crucial           | 1         | 33.33%  |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8C-PB 8GB SODIMM DDR3 1600MT/s | 1         | 33.33%  |
| Micron RAM Module 16GB SODIMM DDR4 3200MT/s            | 1         | 33.33%  |
| Crucial RAM Module 8GB SODIMM DDR3 1600MT/s            | 1         | 33.33%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| DDR3 | 2         | 66.67%  |
| DDR4 | 1         | 33.33%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 3         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 2         | 66.67%  |
| 16384 | 1         | 33.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 2         | 66.67%  |
| 3200  | 1         | 33.33%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)

![Printer Vendor](./All/images/line_chart/printer_vendor.svg)

| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)

![Printer Model](./All/images/line_chart/printer_model.svg)

| Model            | Computers | Percent |
|------------------|-----------|---------|
| Brother MFC-8440 | 1         | 100%    |

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
| Apple                                  | 9         | 33.33%  |
| Chicony Electronics                    | 4         | 14.81%  |
| Realtek Semiconductor                  | 3         | 11.11%  |
| Microdia                               | 2         | 7.41%   |
| Luxvisions Innotech Limited            | 2         | 7.41%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 7.41%   |
| Bison Electronics                      | 2         | 7.41%   |
| Sunplus Innovation Technology          | 1         | 3.7%    |
| Quanta                                 | 1         | 3.7%    |
| Alcor Micro                            | 1         | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Apple FaceTime HD Camera                                     | 6         | 22.22%  |
| Apple Built-in iSight                                        | 3         | 11.11%  |
| Sunplus Laptop Integrated Webcam HD                          | 1         | 3.7%    |
| Realtek Integrated_Webcam_HD                                 | 1         | 3.7%    |
| Realtek Integrated Webcam HD                                 | 1         | 3.7%    |
| Realtek HP Webcam                                            | 1         | 3.7%    |
| Quanta HP HD Camera                                          | 1         | 3.7%    |
| Microdia Sonix Integrated Webcam                             | 1         | 3.7%    |
| Microdia Integrated_Webcam_HD                                | 1         | 3.7%    |
| Luxvisions Innotech Limited Integrated Camera                | 1         | 3.7%    |
| Luxvisions Innotech Limited HP HD Camera                     | 1         | 3.7%    |
| Chicony USB2.0 HD UVC WebCam                                 | 1         | 3.7%    |
| Chicony USB2.0 FHD Camera                                    | 1         | 3.7%    |
| Chicony HP Wide Vision HD Camera                             | 1         | 3.7%    |
| Chicony HD WebCam (Acer)                                     | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam             | 1         | 3.7%    |
| Bison HP Webcam                                              | 1         | 3.7%    |
| Bison HP TrueVision HD Webcam                                | 1         | 3.7%    |
| Alcor Micro ASUS USB2.0 WebCam                               | 1         | 3.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 1         | 50%     |
| Elan Microelectronics | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Validity Sensors Fingerprint scanner | 1         | 50%     |
| Elan ELAN:Fingerprint                | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./All/images/line_chart/chipcard_vendor.svg)

| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 2         | 66.67%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 21        | 61.76%  |
| 1     | 11        | 32.35%  |
| 2     | 2         | 5.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 5         | 33.33%  |
| Chipcard              | 3         | 20%     |
| Net/wireless          | 2         | 13.33%  |
| Multimedia controller | 2         | 13.33%  |
| Fingerprint reader    | 2         | 13.33%  |
| Storage               | 1         | 6.67%   |

