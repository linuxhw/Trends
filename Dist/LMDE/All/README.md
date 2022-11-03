LMDE - Hardware Trends
----------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/LMDE/Desktop/README.md) and [notebooks](/Dist/LMDE/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/linuxhw/TestCoverage)

Period: Oct, 2022.

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

| Name   | Computers | Percent |
|--------|-----------|---------|
| LMDE 5 | 26        | 96.3%   |
| LMDE 4 | 1         | 3.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| LMDE | 27        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.0-18-amd64          | 13        | 48.15%  |
| 5.10.0-19-amd64          | 6         | 22.22%  |
| 5.10.0-12-amd64          | 5         | 18.52%  |
| 6.0.2-x64v2-rt11-xanmod1 | 1         | 3.7%    |
| 5.15.70-xanmod1          | 1         | 3.7%    |
| 5.15.64-xanmod1          | 1         | 3.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 24        | 88.89%  |
| 6.0.2   | 1         | 3.7%    |
| 5.15.70 | 1         | 3.7%    |
| 5.15.64 | 1         | 3.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 24        | 88.89%  |
| 5.15    | 2         | 7.41%   |
| 6.0     | 1         | 3.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 27        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 24        | 88.89%  |
| Cinnamon   | 2         | 7.41%   |
| XFCE       | 1         | 3.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 27        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 22        | 81.48%  |
| LightDM | 5         | 18.52%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 8         | 29.63%  |
| ru_RU | 5         | 18.52%  |
| de_DE | 3         | 11.11%  |
| es_ES | 2         | 7.41%   |
| sk_SK | 1         | 3.7%    |
| pt_BR | 1         | 3.7%    |
| ko_KR | 1         | 3.7%    |
| it_IT | 1         | 3.7%    |
| en_IN | 1         | 3.7%    |
| en_CA | 1         | 3.7%    |
| de_AT | 1         | 3.7%    |
| da_DK | 1         | 3.7%    |
| cs_CZ | 1         | 3.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 14        | 51.85%  |
| BIOS | 13        | 48.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 24        | 88.89%  |
| Btrfs | 2         | 7.41%   |
| Tmpfs | 1         | 3.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 22        | 81.48%  |
| GPT     | 4         | 14.81%  |
| MBR     | 1         | 3.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 26        | 96.3%   |
| Yes       | 1         | 3.7%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 6         | 22.22%  |
| Hewlett-Packard     | 5         | 18.52%  |
| Lenovo              | 4         | 14.81%  |
| Dell                | 3         | 11.11%  |
| Samsung Electronics | 2         | 7.41%   |
| Toshiba             | 1         | 3.7%    |
| Sony                | 1         | 3.7%    |
| MSI                 | 1         | 3.7%    |
| Fujitsu             | 1         | 3.7%    |
| AZW                 | 1         | 3.7%    |
| ASRock              | 1         | 3.7%    |
| Unknown             | 1         | 3.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Toshiba Satellite L855D                | 1         | 3.7%    |
| Sony SVF1532W4E                        | 1         | 3.7%    |
| Samsung DeskTop System                 | 1         | 3.7%    |
| Samsung 355V4C/356V4C/3445VC/3545VC    | 1         | 3.7%    |
| MSI MS-7C52                            | 1         | 3.7%    |
| Lenovo Legion 5 Pro 16ACH6H 82JQ       | 1         | 3.7%    |
| Lenovo IdeaPad S340-15APITouch 81QG    | 1         | 3.7%    |
| Lenovo IdeaPad 320-15IKB 80XL          | 1         | 3.7%    |
| Lenovo IdeaPad 3 15ADA05 81W1          | 1         | 3.7%    |
| HP Pavilion dv6                        | 1         | 3.7%    |
| HP Laptop 15-dw3xxx                    | 1         | 3.7%    |
| HP Laptop 15-da0xxx                    | 1         | 3.7%    |
| HP Laptop 14-cf3xxx                    | 1         | 3.7%    |
| HP EliteDesk 800 G3 SFF                | 1         | 3.7%    |
| Fujitsu CELSIUS W410                   | 1         | 3.7%    |
| Dell XPS L701X                         | 1         | 3.7%    |
| Dell Vostro 430                        | 1         | 3.7%    |
| Dell Inspiron 5420                     | 1         | 3.7%    |
| AZW MINI S                             | 1         | 3.7%    |
| ASUS X510UQR                           | 1         | 3.7%    |
| ASUS VivoBook_ASUSLaptop X705FD_N705FD | 1         | 3.7%    |
| ASUS VivoBook_ASUSLaptop X571GT_X571GT | 1         | 3.7%    |
| ASUS ROG CROSSHAIR VIII HERO           | 1         | 3.7%    |
| ASUS K54LY                             | 1         | 3.7%    |
| ASUS All Series                        | 1         | 3.7%    |
| ASRock A320M-HDV R4.0                  | 1         | 3.7%    |
| Unknown                                | 1         | 3.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo IdeaPad    | 3         | 11.11%  |
| HP Laptop         | 3         | 11.11%  |
| ASUS VivoBook     | 2         | 7.41%   |
| Toshiba Satellite | 1         | 3.7%    |
| Sony SVF1532W4E   | 1         | 3.7%    |
| Samsung DeskTop   | 1         | 3.7%    |
| Samsung 355V4C    | 1         | 3.7%    |
| MSI MS-7C52       | 1         | 3.7%    |
| Lenovo Legion     | 1         | 3.7%    |
| HP Pavilion       | 1         | 3.7%    |
| HP EliteDesk      | 1         | 3.7%    |
| Fujitsu CELSIUS   | 1         | 3.7%    |
| Dell XPS          | 1         | 3.7%    |
| Dell Vostro       | 1         | 3.7%    |
| Dell Inspiron     | 1         | 3.7%    |
| AZW MINI          | 1         | 3.7%    |
| ASUS X510UQR      | 1         | 3.7%    |
| ASUS ROG          | 1         | 3.7%    |
| ASUS K54LY        | 1         | 3.7%    |
| ASUS All          | 1         | 3.7%    |
| ASRock A320M-HDV  | 1         | 3.7%    |
| Unknown           | 1         | 3.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 4         | 14.81%  |
| 2019 | 3         | 11.11%  |
| 2018 | 3         | 11.11%  |
| 2017 | 3         | 11.11%  |
| 2012 | 3         | 11.11%  |
| 2022 | 2         | 7.41%   |
| 2011 | 2         | 7.41%   |
| 2021 | 1         | 3.7%    |
| 2015 | 1         | 3.7%    |
| 2014 | 1         | 3.7%    |
| 2013 | 1         | 3.7%    |
| 2010 | 1         | 3.7%    |
| 2009 | 1         | 3.7%    |
| 2008 | 1         | 3.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 18        | 66.67%  |
| Desktop  | 9         | 33.33%  |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 26        | 96.3%   |
| Enabled  | 1         | 3.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 27        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 9         | 33.33%  |
| 16.01-24.0 | 7         | 25.93%  |
| 4.01-8.0   | 6         | 22.22%  |
| 32.01-64.0 | 2         | 7.41%   |
| 3.01-4.0   | 2         | 7.41%   |
| 1.01-2.0   | 1         | 3.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 10        | 37.04%  |
| 2.01-3.0  | 9         | 33.33%  |
| 3.01-4.0  | 4         | 14.81%  |
| 4.01-8.0  | 3         | 11.11%  |
| 8.01-16.0 | 1         | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 18        | 66.67%  |
| 2      | 8         | 29.63%  |
| 5      | 1         | 3.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 16        | 59.26%  |
| Yes       | 11        | 40.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 92.59%  |
| No        | 2         | 7.41%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 74.07%  |
| No        | 7         | 25.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 62.96%  |
| No        | 10        | 37.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country     | Computers | Percent |
|-------------|-----------|---------|
| Russia      | 6         | 22.22%  |
| USA         | 4         | 14.81%  |
| Germany     | 3         | 11.11%  |
| Ecuador     | 2         | 7.41%   |
| Sweden      | 1         | 3.7%    |
| South Korea | 1         | 3.7%    |
| Slovenia    | 1         | 3.7%    |
| Slovakia    | 1         | 3.7%    |
| Italy       | 1         | 3.7%    |
| India       | 1         | 3.7%    |
| Denmark     | 1         | 3.7%    |
| Czechia     | 1         | 3.7%    |
| Canada      | 1         | 3.7%    |
| Brazil      | 1         | 3.7%    |
| Belgium     | 1         | 3.7%    |
| Austria     | 1         | 3.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Moscow               | 2         | 7.41%   |
| Guayaquil            | 2         | 7.41%   |
| Bend                 | 2         | 7.41%   |
| Viggianello          | 1         | 3.7%    |
| Ulyanovsk            | 1         | 3.7%    |
| St Petersburg        | 1         | 3.7%    |
| Schruns              | 1         | 3.7%    |
| Prague               | 1         | 3.7%    |
| Pensacola            | 1         | 3.7%    |
| Oberhausen           | 1         | 3.7%    |
| Nizhniy Novgorod     | 1         | 3.7%    |
| Nitra                | 1         | 3.7%    |
| Malmo                | 1         | 3.7%    |
| London               | 1         | 3.7%    |
| Ljubljana            | 1         | 3.7%    |
| Krasnodar            | 1         | 3.7%    |
| Juiz de Fora         | 1         | 3.7%    |
| Hyderabad            | 1         | 3.7%    |
| Freiburg im Breisgau | 1         | 3.7%    |
| Farciennes           | 1         | 3.7%    |
| Copenhagen           | 1         | 3.7%    |
| Columbia City        | 1         | 3.7%    |
| Buk-gu               | 1         | 3.7%    |
| Bitburg              | 1         | 3.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 8      | 22.86%  |
| Seagate             | 7         | 7      | 20%     |
| SK hynix            | 4         | 4      | 11.43%  |
| Crucial             | 3         | 3      | 8.57%   |
| SanDisk             | 2         | 3      | 5.71%   |
| Kingston            | 2         | 2      | 5.71%   |
| Union Memory        | 1         | 1      | 2.86%   |
| Toshiba             | 1         | 1      | 2.86%   |
| Samsung Electronics | 1         | 4      | 2.86%   |
| Phison Electronics  | 1         | 1      | 2.86%   |
| Micron Technology   | 1         | 1      | 2.86%   |
| Gigabyte Technology | 1         | 1      | 2.86%   |
| BR                  | 1         | 1      | 2.86%   |
| Apple               | 1         | 1      | 2.86%   |
| Unknown             | 1         | 1      | 2.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 5         | 12.82%  |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 2.56%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD        | 1         | 2.56%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 2.56%   |
| WDC WD5000LPSX-08A6W 500GB              | 1         | 2.56%   |
| WDC WD3200BEVT-60ZCT0 320GB             | 1         | 2.56%   |
| WDC WD10JPVX-75JC3T0 1TB                | 1         | 2.56%   |
| WDC WD1002FAEX-00Z3A0 1TB               | 1         | 2.56%   |
| WDC PC SA530 SDASN8Y1T00 1024GB         | 1         | 2.56%   |
| Union Memory UMIS RPJTJ512MEE1OWX 512GB | 1         | 2.56%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 2.56%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB    | 1         | 2.56%   |
| SK hynix HFM256GDJTNG-8310A 256GB       | 1         | 2.56%   |
| SK hynix BC711 HFM512GD3JX013N 512GB    | 1         | 2.56%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB | 1         | 2.56%   |
| Seagate ST3320418AS 320GB               | 1         | 2.56%   |
| Seagate Expansion SW 8TB                | 1         | 2.56%   |
| Sandisk WD_BLACK SN750 SE 500GB         | 1         | 2.56%   |
| SanDisk Ultra II 480GB SSD              | 1         | 2.56%   |
| SanDisk NVMe SSD Drive 500GB            | 1         | 2.56%   |
| Samsung SSD 850 PRO 256GB               | 1         | 2.56%   |
| Samsung SSD 850 EVO 500GB               | 1         | 2.56%   |
| Samsung NVMe SSD Drive 500GB            | 1         | 2.56%   |
| Samsung NVMe SSD Drive 250GB            | 1         | 2.56%   |
| Phison PS5013 E13 NVMe Controller 256GB | 1         | 2.56%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 1         | 2.56%   |
| Kingston SVP100S296G 96GB SSD           | 1         | 2.56%   |
| Kingston SA400S37480G 480GB SSD         | 1         | 2.56%   |
| Gigabyte GP-GSTFS31120GNTD 120GB        | 1         | 2.56%   |
| Crucial CT525MX300SSD1 528GB            | 1         | 2.56%   |
| Crucial CT1000MX500SSD1 1TB             | 1         | 2.56%   |
| Crucial CT1000BX500SSD1 1TB             | 1         | 2.56%   |
| BR 512GB                                | 1         | 2.56%   |
| Apple SSD SD256E 256GB                  | 1         | 2.56%   |
| Unknown                                 | 1         | 2.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 7      | 53.85%  |
| WDC     | 5         | 5      | 38.46%  |
| Toshiba | 1         | 1      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 3         | 3      | 23.08%  |
| WDC                 | 2         | 2      | 15.38%  |
| Kingston            | 2         | 2      | 15.38%  |
| SanDisk             | 1         | 1      | 7.69%   |
| Samsung Electronics | 1         | 2      | 7.69%   |
| Micron Technology   | 1         | 1      | 7.69%   |
| Gigabyte Technology | 1         | 1      | 7.69%   |
| Apple               | 1         | 1      | 7.69%   |
| Unknown             | 1         | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 13        | 13     | 38.24%  |
| SSD     | 11        | 14     | 32.35%  |
| NVMe    | 8         | 10     | 23.53%  |
| Unknown | 2         | 2      | 5.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 23        | 28     | 71.88%  |
| NVMe | 8         | 10     | 25%     |
| SAS  | 1         | 1      | 3.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 12        | 14     | 48%     |
| 0.51-1.0   | 11        | 11     | 44%     |
| 1.01-2.0   | 1         | 1      | 4%      |
| 4.01-10.0  | 1         | 1      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 8         | 29.63%  |
| 501-1000       | 7         | 25.93%  |
| More than 3000 | 3         | 11.11%  |
| 101-250        | 3         | 11.11%  |
| 1001-2000      | 2         | 7.41%   |
| 51-100         | 2         | 7.41%   |
| 2001-3000      | 1         | 3.7%    |
| 1-20           | 1         | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 9         | 33.33%  |
| 21-50     | 7         | 25.93%  |
| 101-250   | 3         | 11.11%  |
| 501-1000  | 3         | 11.11%  |
| 251-500   | 2         | 7.41%   |
| 2001-3000 | 1         | 3.7%    |
| 1001-2000 | 1         | 3.7%    |
| 51-100    | 1         | 3.7%    |

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

![Drive Status](./images/pie_chart/drive_status.svg)

![Drive Status](./images/line_chart/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 22        | 32     | 81.48%  |
| Works    | 5         | 7      | 18.52%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 18        | 51.43%  |
| AMD                     | 8         | 22.86%  |
| SK hynix                | 4         | 11.43%  |
| Union Memory (Shenzhen) | 1         | 2.86%   |
| SanDisk                 | 1         | 2.86%   |
| Samsung Electronics     | 1         | 2.86%   |
| Phison Electronics      | 1         | 2.86%   |
| ASMedia Technology      | 1         | 2.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 17.95%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 12.82%  |
| SK hynix Gold P31 SSD                                                          | 2         | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 5.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 5.13%   |
| AMD FCH SATA Controller D                                                      | 2         | 5.13%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 2.56%   |
| SK hynix BC511                                                                 | 1         | 2.56%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 2.56%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 2.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 2.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 2.56%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 2.56%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 2.56%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 2.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 2.56%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 2.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 2.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 2.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 2.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1         | 2.56%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 2.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 21        | 60%     |
| NVMe | 8         | 22.86%  |
| RAID | 6         | 17.14%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 18        | 66.67%  |
| AMD    | 9         | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 3.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 3.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 3.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 3.7%    |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 3.7%    |
| Intel Core i7-4770K CPU @ 3.50GHz             | 1         | 3.7%    |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 1         | 3.7%    |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 1         | 3.7%    |
| Intel Core i7 CPU 860 @ 2.80GHz               | 1         | 3.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 3.7%    |
| Intel Core i5-2400 CPU @ 3.10GHz              | 1         | 3.7%    |
| Intel Core i3-8130U CPU @ 2.20GHz             | 1         | 3.7%    |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 3.7%    |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 3.7%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 3.7%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 1         | 3.7%    |
| Intel Celeron N5095 @ 2.00GHz                 | 1         | 3.7%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 3.7%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 1         | 3.7%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 3.7%    |
| AMD Ryzen 5 5600H with Radeon Graphics        | 1         | 3.7%    |
| AMD Ryzen 5 3350G with Radeon Vega Graphics   | 1         | 3.7%    |
| AMD Ryzen 3 3250U with Radeon Graphics        | 1         | 3.7%    |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 1         | 3.7%    |
| AMD Athlon II P320 Dual-Core Processor        | 1         | 3.7%    |
| AMD A8-4500M APU with Radeon HD Graphics      | 1         | 3.7%    |
| AMD A10-4600M APU with Radeon HD Graphics     | 1         | 3.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model         | Computers | Percent |
|---------------|-----------|---------|
| Intel Core i7 | 8         | 29.63%  |
| Intel Core i3 | 5         | 18.52%  |
| Intel Core i5 | 2         | 7.41%   |
| AMD Ryzen 7   | 2         | 7.41%   |
| AMD Ryzen 5   | 2         | 7.41%   |
| AMD Ryzen 3   | 2         | 7.41%   |
| Other         | 1         | 3.7%    |
| Intel Core i9 | 1         | 3.7%    |
| Intel Celeron | 1         | 3.7%    |
| AMD Athlon II | 1         | 3.7%    |
| AMD A8        | 1         | 3.7%    |
| AMD A10       | 1         | 3.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 14        | 51.85%  |
| 2      | 9         | 33.33%  |
| 8      | 2         | 7.41%   |
| 6      | 2         | 7.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 27        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 22        | 81.48%  |
| 1      | 5         | 18.52%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 27        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x08108109 | 4         | 14.81%  |
| 0x806ea    | 2         | 7.41%   |
| 0x306a9    | 2         | 7.41%   |
| 0x206a7    | 2         | 7.41%   |
| 0x106e5    | 2         | 7.41%   |
| 0x06001119 | 2         | 7.41%   |
| 0x906ed    | 1         | 3.7%    |
| 0x906ea    | 1         | 3.7%    |
| 0x906e9    | 1         | 3.7%    |
| 0x906c0    | 1         | 3.7%    |
| 0x806eb    | 1         | 3.7%    |
| 0x806e9    | 1         | 3.7%    |
| 0x806c1    | 1         | 3.7%    |
| 0x706e5    | 1         | 3.7%    |
| 0x306c3    | 1         | 3.7%    |
| 0x0a50000c | 1         | 3.7%    |
| 0x08701021 | 1         | 3.7%    |
| 0x010000c8 | 1         | 3.7%    |
| Unknown    | 1         | 3.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 7         | 25.93%  |
| Zen+        | 4         | 14.81%  |
| SandyBridge | 2         | 7.41%   |
| Piledriver  | 2         | 7.41%   |
| Nehalem     | 2         | 7.41%   |
| IvyBridge   | 2         | 7.41%   |
| Haswell     | 2         | 7.41%   |
| Zen 3       | 1         | 3.7%    |
| Zen 2       | 1         | 3.7%    |
| Tremont     | 1         | 3.7%    |
| TigerLake   | 1         | 3.7%    |
| K10         | 1         | 3.7%    |
| IceLake     | 1         | 3.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Nvidia | 13        | 37.14%  |
| Intel  | 12        | 34.29%  |
| AMD    | 10        | 28.57%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 4         | 10.81%  |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                      | 2         | 5.41%   |
| Nvidia GM108M [GeForce 940MX]                                        | 2         | 5.41%   |
| Intel UHD Graphics 620                                               | 2         | 5.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 2         | 5.41%   |
| Nvidia TU117M [GeForce MX450]                                        | 1         | 2.7%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                | 1         | 2.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                              | 1         | 2.7%    |
| Nvidia GP107 [GeForce GTX 1050]                                      | 1         | 2.7%    |
| Nvidia GK208M [GeForce GT 740M]                                      | 1         | 2.7%    |
| Nvidia GK104 [GeForce GTX 760]                                       | 1         | 2.7%    |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                    | 1         | 2.7%    |
| Nvidia GF106M [GeForce GT 445M]                                      | 1         | 2.7%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                      | 1         | 2.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                           | 1         | 2.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 1         | 2.7%    |
| Intel JasperLake [UHD Graphics]                                      | 1         | 2.7%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                               | 1         | 2.7%    |
| Intel HD Graphics 630                                                | 1         | 2.7%    |
| Intel HD Graphics 620                                                | 1         | 2.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                     | 1         | 2.7%    |
| Intel 3rd Gen Core processor Graphics Controller                     | 1         | 2.7%    |
| AMD Trinity [Radeon HD 7660G]                                        | 1         | 2.7%    |
| AMD Trinity [Radeon HD 7640G]                                        | 1         | 2.7%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                            | 1         | 2.7%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                           | 1         | 2.7%    |
| AMD RV710 [Radeon HD 4350/4550]                                      | 1         | 2.7%    |
| AMD RS880M [Mobility Radeon HD 4225/4250]                            | 1         | 2.7%    |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]             | 1         | 2.7%    |
| AMD Barts PRO [Radeon HD 6850]                                       | 1         | 2.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 8         | 29.63%  |
| 1 x AMD        | 8         | 29.63%  |
| 1 x Nvidia     | 5         | 18.52%  |
| 1 x Intel      | 4         | 14.81%  |
| 2 x AMD        | 2         | 7.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 19        | 70.37%  |
| Proprietary | 6         | 22.22%  |
| Unknown     | 2         | 7.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 33.33%  |
| 1.01-2.0   | 6         | 22.22%  |
| 0.01-0.5   | 5         | 18.52%  |
| 0.51-1.0   | 3         | 11.11%  |
| 3.01-4.0   | 2         | 7.41%   |
| 5.01-6.0   | 1         | 3.7%    |
| 2.01-3.0   | 1         | 3.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 5         | 16.13%  |
| Hewlett-Packard         | 4         | 12.9%   |
| AU Optronics            | 4         | 12.9%   |
| Samsung Electronics     | 3         | 9.68%   |
| Goldstar                | 3         | 9.68%   |
| Chimei Innolux          | 2         | 6.45%   |
| BOE                     | 2         | 6.45%   |
| ViewSonic               | 1         | 3.23%   |
| Vestel Elektronik       | 1         | 3.23%   |
| Unknown                 | 1         | 3.23%   |
| Sony                    | 1         | 3.23%   |
| PLN                     | 1         | 3.23%   |
| Philips                 | 1         | 3.23%   |
| Lenovo Group Limited    | 1         | 3.23%   |
| Chi Mei Optoelectronics | 1         | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| ViewSonic VG2230wm VSCA21E 1680x1050 474x296mm 22.0-inch               | 1         | 3.23%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1         | 3.23%   |
| Unknown LCD Monitor SAMSUNG                                            | 1         | 3.23%   |
| Sony LCD Monitor TV 3840x1080                                          | 1         | 3.23%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch   | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch   | 1         | 3.23%   |
| Samsung Electronics LCD Monitor C27F390                                | 1         | 3.23%   |
| PLN LCD Monitor PXL2790MW 1920x1080                                    | 1         | 3.23%   |
| Philips 244E PHLC036 1920x1080 521x293mm 23.5-inch                     | 1         | 3.23%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch           | 1         | 3.23%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch           | 1         | 3.23%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch           | 1         | 3.23%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch            | 1         | 3.23%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch            | 1         | 3.23%   |
| Lenovo Group Limited LCD Monitor LEN G32qc-10 4480x1440                | 1         | 3.23%   |
| Hewlett-Packard w2216 HWP280B 1680x1050 465x291mm 21.6-inch            | 1         | 3.23%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch           | 1         | 3.23%   |
| Hewlett-Packard 27f HPN354B 1920x1080 598x336mm 27.0-inch              | 1         | 3.23%   |
| Hewlett-Packard 24y HPN3504 1920x1080 530x300mm 24.0-inch              | 1         | 3.23%   |
| Goldstar W2486 GSM5729 1920x1080 531x299mm 24.0-inch                   | 1         | 3.23%   |
| Goldstar M2380A GSM57EE 1920x1080 509x286mm 23.0-inch                  | 1         | 3.23%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch        | 1         | 3.23%   |
| Chi Mei Optoelectronics LCD Monitor 1600x900                           | 1         | 3.23%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                   | 1         | 3.23%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                   | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch         | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO3691 1366x768 344x193mm 15.5-inch          | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch          | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO20ED 1920x1080 344x194mm 15.5-inch         | 1         | 3.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 11        | 35.48%  |
| 1366x768 (WXGA)    | 9         | 29.03%  |
| 3840x2160 (4K)     | 2         | 6.45%   |
| 1680x1050 (WSXGA+) | 2         | 6.45%   |
| Unknown            | 2         | 6.45%   |
| 4480x1440          | 1         | 3.23%   |
| 3840x1080          | 1         | 3.23%   |
| 1600x900 (HD+)     | 1         | 3.23%   |
| 1440x900 (WXGA+)   | 1         | 3.23%   |
| 1280x1024 (SXGA)   | 1         | 3.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 11        | 37.93%  |
| Unknown | 4         | 13.79%  |
| 24      | 2         | 6.9%    |
| 23      | 2         | 6.9%    |
| 21      | 2         | 6.9%    |
| 17      | 2         | 6.9%    |
| 13      | 2         | 6.9%    |
| 84      | 1         | 3.45%   |
| 27      | 1         | 3.45%   |
| 22      | 1         | 3.45%   |
| 19      | 1         | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 48.15%  |
| 501-600     | 5         | 18.52%  |
| Unknown     | 4         | 14.81%  |
| 401-500     | 3         | 11.11%  |
| 351-400     | 1         | 3.7%    |
| 1501-2000   | 1         | 3.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 19        | 73.08%  |
| Unknown | 4         | 15.38%  |
| 16/10   | 2         | 7.69%   |
| 5/4     | 1         | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 11        | 37.93%  |
| 201-250        | 7         | 24.14%  |
| Unknown        | 4         | 13.79%  |
| 81-90          | 2         | 6.9%    |
| More than 1000 | 1         | 3.45%   |
| 301-350        | 1         | 3.45%   |
| 151-200        | 1         | 3.45%   |
| 141-150        | 1         | 3.45%   |
| 121-130        | 1         | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 10        | 35.71%  |
| 51-100  | 9         | 32.14%  |
| 121-160 | 5         | 17.86%  |
| Unknown | 4         | 14.29%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 20        | 74.07%  |
| 2     | 5         | 18.52%  |
| 0     | 2         | 7.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 20        | 52.63%  |
| Intel                 | 10        | 26.32%  |
| Qualcomm Atheros      | 4         | 10.53%  |
| Broadcom              | 3         | 7.89%   |
| Ralink Technology     | 1         | 2.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 34.04%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 4.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 4.26%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 4.26%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 2.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 2.13%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.13%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 2.13%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 2.13%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 2.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.13%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 2.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 2.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 2.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.13%   |
| Intel Wireless 8265 / 8275                                        | 1         | 2.13%   |
| Intel Wireless 3165                                               | 1         | 2.13%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.13%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.13%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 2.13%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 1         | 2.13%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 2.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 2.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.13%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.13%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 2.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 2.13%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 9         | 45%     |
| Intel                 | 6         | 30%     |
| Qualcomm Atheros      | 2         | 10%     |
| Broadcom              | 2         | 10%     |
| Ralink Technology     | 1         | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 9.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 9.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 4.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 4.76%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 4.76%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 4.76%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 4.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 4.76%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 4.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 4.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 4.76%   |
| Intel Wireless 8265 / 8275                                     | 1         | 4.76%   |
| Intel Wireless 3165                                            | 1         | 4.76%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 1         | 4.76%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 1         | 4.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 4.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 4.76%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 4.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 18        | 69.23%  |
| Intel                 | 4         | 15.38%  |
| Qualcomm Atheros      | 3         | 11.54%  |
| Broadcom              | 1         | 3.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 61.54%  |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 7.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 3.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 3.85%   |
| Intel I211 Gigabit Network Connection                             | 1         | 3.85%   |
| Intel Ethernet Connection I217-V                                  | 1         | 3.85%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 3.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 3.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 25        | 55.56%  |
| WiFi     | 20        | 44.44%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 15        | 53.57%  |
| Ethernet | 13        | 46.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 17        | 62.96%  |
| 1     | 10        | 37.04%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 22        | 81.48%  |
| Yes  | 5         | 18.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Realtek Semiconductor   | 7         | 38.89%  |
| Intel                   | 5         | 27.78%  |
| Cambridge Silicon Radio | 2         | 11.11%  |
| Lite-On Technology      | 1         | 5.56%   |
| IMC Networks            | 1         | 5.56%   |
| Foxconn / Hon Hai       | 1         | 5.56%   |
| Broadcom                | 1         | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 3         | 16.67%  |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 11.11%  |
| Intel Bluetooth wireless interface                  | 2         | 11.11%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 11.11%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 11.11%  |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 5.56%   |
| Realtek RTL8821A Bluetooth                          | 1         | 5.56%   |
| Lite-On Bluetooth Device                            | 1         | 5.56%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 5.56%   |
| IMC Networks Bluetooth Radio                        | 1         | 5.56%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 5.56%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 18        | 47.37%  |
| AMD                 | 12        | 31.58%  |
| Nvidia              | 7         | 18.42%  |
| C-Media Electronics | 1         | 2.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 5         | 10.87%  |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 4         | 8.7%    |
| Intel Sunrise Point-LP HD Audio                                                   | 3         | 6.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 3         | 6.52%   |
| Intel Cannon Lake PCH cAVS                                                        | 2         | 4.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2         | 4.35%   |
| AMD Trinity HDMI Audio Controller                                                 | 2         | 4.35%   |
| AMD FCH Azalia Controller                                                         | 2         | 4.35%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1         | 2.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 2.17%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1         | 2.17%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1         | 2.17%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1         | 2.17%   |
| Nvidia GF106 High Definition Audio Controller                                     | 1         | 2.17%   |
| Nvidia GA106 High Definition Audio Controller                                     | 1         | 2.17%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 1         | 2.17%   |
| Intel Jasper Lake HD Audio                                                        | 1         | 2.17%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 1         | 2.17%   |
| Intel Haswell-ULT HD Audio Controller                                             | 1         | 2.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 1         | 2.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 1         | 2.17%   |
| Intel 8 Series HD Audio Controller                                                | 1         | 2.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1         | 2.17%   |
| Intel 200 Series PCH HD Audio                                                     | 1         | 2.17%   |
| C-Media Electronics JLAB TALK GO MICROPHONE                                       | 1         | 2.17%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1         | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1         | 2.17%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 1         | 2.17%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 1         | 2.17%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 2.17%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                        | 1         | 2.17%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 40%     |
| Unknown             | 3         | 30%     |
| SK hynix            | 2         | 20%     |
| Corsair             | 1         | 10%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 2         | 20%     |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s               | 1         | 10%     |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s               | 1         | 10%     |
| Unknown RAM Module 8GB SODIMM DDR3                        | 1         | 10%     |
| SK hynix RAM HMA851S6DJR6N-VK 4096MB SODIMM DDR4 2667MT/s | 1         | 10%     |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 10%     |
| Samsung RAM Module 8GB DIMM DDR4 2400MT/s                 | 1         | 10%     |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 1         | 10%     |
| Corsair RAM VS2GB1333D4 2GB DIMM 1600MT/s                 | 1         | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| DDR4 | 5         | 71.43%  |
| DDR3 | 2         | 28.57%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 5         | 71.43%  |
| DIMM   | 2         | 28.57%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size | Computers | Percent |
|------|-----------|---------|
| 8192 | 4         | 57.14%  |
| 4096 | 3         | 42.86%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 3         | 33.33%  |
| 3266    | 2         | 22.22%  |
| 2400    | 2         | 22.22%  |
| 1600    | 1         | 11.11%  |
| Unknown | 1         | 11.11%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| IMC Networks                           | 5         | 27.78%  |
| Quanta                                 | 3         | 16.67%  |
| Acer                                   | 2         | 11.11%  |
| Z-Star Microelectronics                | 1         | 5.56%   |
| Syntek                                 | 1         | 5.56%   |
| Sunplus Innovation Technology          | 1         | 5.56%   |
| Microdia                               | 1         | 5.56%   |
| Luxvisions Innotech Limited            | 1         | 5.56%   |
| Importek                               | 1         | 5.56%   |
| Chicony Electronics                    | 1         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Quanta HP Webcam                                               | 2         | 11.11%  |
| Acer Integrated Camera                                         | 2         | 11.11%  |
| Z-Star WebCam SC-03FFL11739P                                   | 1         | 5.56%   |
| Syntek Integrated Camera                                       | 1         | 5.56%   |
| Sunplus EKACOM-K30                                             | 1         | 5.56%   |
| Quanta Laptop_Integrated_Webcam_2HDM                           | 1         | 5.56%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 1         | 5.56%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 5.56%   |
| Importek TOSHIBA Web Camera                                    | 1         | 5.56%   |
| IMC Networks VGA UVC WebCam                                    | 1         | 5.56%   |
| IMC Networks UVC VGA Webcam                                    | 1         | 5.56%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 1         | 5.56%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 5.56%   |
| IMC Networks EasyCamera                                        | 1         | 5.56%   |
| Chicony Front Camera                                           | 1         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 5.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS301 Fingerprint Reader | 1         | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 23        | 85.19%  |
| 1     | 3         | 11.11%  |
| 3     | 1         | 3.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 2         | 33.33%  |
| Graphics card         | 2         | 33.33%  |
| Net/wireless          | 1         | 16.67%  |
| Fingerprint reader    | 1         | 16.67%  |

