Elementary Hardware Trends (Desktops)
-------------------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Elementary users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Full-feature report is available here: https://linux-hardware.org/?view=trends

Period: Jan, 2022.

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

| Name             | Desktops | Percent |
|------------------|----------|---------|
| Elementary 6.1   | 23       | 88.46%  |
| Elementary 5.1.7 | 2        | 7.69%   |
| Elementary 6     | 1        | 3.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name       | Desktops | Percent |
|------------|----------|---------|
| Elementary | 26       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.11.0-43-generic      | 7        | 26.92%  |
| 5.13.0-27-generic      | 6        | 23.08%  |
| 5.11.0-44-generic      | 4        | 15.38%  |
| 5.13.0-25-generic      | 2        | 7.69%   |
| 5.11.0-46-generic      | 2        | 7.69%   |
| 5.4.0-94-generic       | 1        | 3.85%   |
| 5.15.12-051512-generic | 1        | 3.85%   |
| 5.15.1-xanmod1         | 1        | 3.85%   |
| 5.11.0-43-lowlatency   | 1        | 3.85%   |
| 5.11.0-40-generic      | 1        | 3.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 15       | 57.69%  |
| 5.13.0  | 8        | 30.77%  |
| 5.4.0   | 1        | 3.85%   |
| 5.15.12 | 1        | 3.85%   |
| 5.15.1  | 1        | 3.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 15       | 57.69%  |
| 5.13    | 8        | 30.77%  |
| 5.15    | 2        | 7.69%   |
| 5.4     | 1        | 3.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 26       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 26       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 26       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 65.38%  |
| LightDM | 9        | 34.62%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 11       | 42.31%  |
| en_GB | 4        | 15.38%  |
| de_DE | 3        | 11.54%  |
| pl_PL | 2        | 7.69%   |
| ru_RU | 1        | 3.85%   |
| it_IT | 1        | 3.85%   |
| fr_FR | 1        | 3.85%   |
| fr_CA | 1        | 3.85%   |
| es_ES | 1        | 3.85%   |
| el_GR | 1        | 3.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 16       | 61.54%  |
| BIOS | 10       | 38.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 24       | 92.31%  |
| Btrfs | 2        | 7.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 69.23%  |
| GPT     | 7        | 26.92%  |
| MBR     | 1        | 3.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 88.46%  |
| Yes       | 3        | 11.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 80.77%  |
| Yes       | 5        | 19.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 8        | 30.77%  |
| ASRock              | 5        | 19.23%  |
| MSI                 | 4        | 15.38%  |
| Gigabyte Technology | 4        | 15.38%  |
| Hewlett-Packard     | 1        | 3.85%   |
| Foxconn             | 1        | 3.85%   |
| FIRICH              | 1        | 3.85%   |
| Acer                | 1        | 3.85%   |
| Unknown             | 1        | 3.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| MSI MS-7C52                  | 1        | 3.85%   |
| MSI MS-7C02                  | 1        | 3.85%   |
| MSI MS-7B79                  | 1        | 3.85%   |
| MSI MS-7A59                  | 1        | 3.85%   |
| HP ProDesk 600 G5 SFF        | 1        | 3.85%   |
| Gigabyte X570 AORUS ELITE    | 1        | 3.85%   |
| Gigabyte H61M-DS2            | 1        | 3.85%   |
| Gigabyte GA-970A-D3          | 1        | 3.85%   |
| Gigabyte B85M-DS3H-A         | 1        | 3.85%   |
| Foxconn p6616f               | 1        | 3.85%   |
| FIRICH J1900                 | 1        | 3.85%   |
| ASUS TUF GAMING B550M-PLUS   | 1        | 3.85%   |
| ASUS TUF B365M-PLUS GAMING   | 1        | 3.85%   |
| ASUS ROG STRIX X570-E GAMING | 1        | 3.85%   |
| ASUS ROG STRIX B360-H GAMING | 1        | 3.85%   |
| ASUS P8H61-M LX3 R2.0        | 1        | 3.85%   |
| ASUS M5A78L-M LX3            | 1        | 3.85%   |
| ASUS H61M-CS                 | 1        | 3.85%   |
| ASUS H110M-C                 | 1        | 3.85%   |
| ASRock Z370 Pro4             | 1        | 3.85%   |
| ASRock H97M Pro4             | 1        | 3.85%   |
| ASRock H61M-HVS              | 1        | 3.85%   |
| ASRock B450M-HDV R4.0        | 1        | 3.85%   |
| ASRock AB350M Pro4           | 1        | 3.85%   |
| Acer ConceptD CM100-51A      | 1        | 3.85%   |
| Unknown                      | 1        | 3.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS TUF             | 2        | 7.69%   |
| ASUS ROG             | 2        | 7.69%   |
| MSI MS-7C52          | 1        | 3.85%   |
| MSI MS-7C02          | 1        | 3.85%   |
| MSI MS-7B79          | 1        | 3.85%   |
| MSI MS-7A59          | 1        | 3.85%   |
| HP ProDesk           | 1        | 3.85%   |
| Gigabyte X570        | 1        | 3.85%   |
| Gigabyte H61M-DS2    | 1        | 3.85%   |
| Gigabyte GA-970A-D3  | 1        | 3.85%   |
| Gigabyte B85M-DS3H-A | 1        | 3.85%   |
| Foxconn p6616f       | 1        | 3.85%   |
| FIRICH J1900         | 1        | 3.85%   |
| ASUS P8H61-M         | 1        | 3.85%   |
| ASUS M5A78L-M        | 1        | 3.85%   |
| ASUS H61M-CS         | 1        | 3.85%   |
| ASUS H110M-C         | 1        | 3.85%   |
| ASRock Z370          | 1        | 3.85%   |
| ASRock H97M          | 1        | 3.85%   |
| ASRock H61M-HVS      | 1        | 3.85%   |
| ASRock B450M-HDV     | 1        | 3.85%   |
| ASRock AB350M        | 1        | 3.85%   |
| Acer ConceptD        | 1        | 3.85%   |
| Unknown              | 1        | 3.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 6        | 23.08%  |
| 2020 | 4        | 15.38%  |
| 2018 | 3        | 11.54%  |
| 2012 | 3        | 11.54%  |
| 2017 | 2        | 7.69%   |
| 2015 | 2        | 7.69%   |
| 2014 | 2        | 7.69%   |
| 2011 | 2        | 7.69%   |
| 2016 | 1        | 3.85%   |
| 2010 | 1        | 3.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 26       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 26       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Desktops | Percent |
|------|----------|---------|
| No   | 26       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 7        | 26.92%  |
| 32.01-64.0  | 5        | 19.23%  |
| 3.01-4.0    | 4        | 15.38%  |
| 8.01-16.0   | 4        | 15.38%  |
| 4.01-8.0    | 3        | 11.54%  |
| 64.01-256.0 | 2        | 7.69%   |
| 24.01-32.0  | 1        | 3.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 9        | 34.62%  |
| 4.01-8.0   | 7        | 26.92%  |
| 2.01-3.0   | 7        | 26.92%  |
| 32.01-64.0 | 1        | 3.85%   |
| 3.01-4.0   | 1        | 3.85%   |
| 8.01-16.0  | 1        | 3.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 10       | 38.46%  |
| 1      | 7        | 26.92%  |
| 3      | 6        | 23.08%  |
| 4      | 2        | 7.69%   |
| 6      | 1        | 3.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 69.23%  |
| Yes       | 8        | 30.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 25       | 96.15%  |
| No        | 1        | 3.85%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 14       | 53.85%  |
| No        | 12       | 46.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 73.08%  |
| Yes       | 7        | 26.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country   | Desktops | Percent |
|-----------|----------|---------|
| Germany   | 4        | 15.38%  |
| USA       | 3        | 11.54%  |
| UK        | 2        | 7.69%   |
| Poland    | 2        | 7.69%   |
| India     | 2        | 7.69%   |
| Thailand  | 1        | 3.85%   |
| Sri Lanka | 1        | 3.85%   |
| Spain     | 1        | 3.85%   |
| Lithuania | 1        | 3.85%   |
| Italy     | 1        | 3.85%   |
| Hong Kong | 1        | 3.85%   |
| Greece    | 1        | 3.85%   |
| France    | 1        | 3.85%   |
| Czechia   | 1        | 3.85%   |
| Canada    | 1        | 3.85%   |
| Brazil    | 1        | 3.85%   |
| Belarus   | 1        | 3.85%   |
| Argentina | 1        | 3.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City              | Desktops | Percent |
|-------------------|----------|---------|
| Warsaw            | 2        | 7.69%   |
| Znojmo            | 1        | 3.85%   |
| Wattala           | 1        | 3.85%   |
| Thrissur          | 1        | 3.85%   |
| Saguenay          | 1        | 3.85%   |
| Russell           | 1        | 3.85%   |
| Pune              | 1        | 3.85%   |
| Oldham            | 1        | 3.85%   |
| Oldenburg         | 1        | 3.85%   |
| Minsk             | 1        | 3.85%   |
| Milan             | 1        | 3.85%   |
| Ma??eikiai        | 1        | 3.85%   |
| London            | 1        | 3.85%   |
| Lamia             | 1        | 3.85%   |
| La Plata          | 1        | 3.85%   |
| Hamburg           | 1        | 3.85%   |
| Fortaleza         | 1        | 3.85%   |
| Dortmund          | 1        | 3.85%   |
| Colorado Springs  | 1        | 3.85%   |
| Chana             | 1        | 3.85%   |
| Central           | 1        | 3.85%   |
| Brownfield        | 1        | 3.85%   |
| Berlin            | 1        | 3.85%   |
| Barcelona         | 1        | 3.85%   |
| ?�pinay-sur-Seine | 1        | 3.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 15     | 20%     |
| Samsung Electronics | 7        | 7      | 12.73%  |
| Kingston            | 6        | 6      | 10.91%  |
| Seagate             | 5        | 5      | 9.09%   |
| Crucial             | 5        | 5      | 9.09%   |
| A-DATA Technology   | 3        | 3      | 5.45%   |
| Unknown             | 2        | 2      | 3.64%   |
| Toshiba             | 2        | 2      | 3.64%   |
| SanDisk             | 2        | 2      | 3.64%   |
| Phison              | 2        | 2      | 3.64%   |
| ASMT                | 2        | 2      | 3.64%   |
| Transcend           | 1        | 1      | 1.82%   |
| Team                | 1        | 1      | 1.82%   |
| PNY                 | 1        | 1      | 1.82%   |
| OCZ                 | 1        | 1      | 1.82%   |
| Micron Technology   | 1        | 1      | 1.82%   |
| Hitachi             | 1        | 1      | 1.82%   |
| HGST                | 1        | 1      | 1.82%   |
| GOODRAM             | 1        | 1      | 1.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Kingston NVMe SSD Drive 1TB              | 2        | 3.51%   |
| WDC WDS500G2B0A-00SM50 500GB SSD         | 1        | 1.75%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1        | 1.75%   |
| WDC WDS120G2G0A-00JH30 120GB SSD         | 1        | 1.75%   |
| WDC WD5000AAKX-00ERMA0 500GB             | 1        | 1.75%   |
| WDC WD5000AAKS-00UU3A0 500GB             | 1        | 1.75%   |
| WDC WD40EZAZ-00SF3B0 4TB                 | 1        | 1.75%   |
| WDC WD40EFRX-68N32N0 4TB                 | 1        | 1.75%   |
| WDC WD1600JS-55NCB1 160GB                | 1        | 1.75%   |
| WDC WD15EARX-00PASB0 1TB                 | 1        | 1.75%   |
| WDC WD10EZEX-08M2NA0 1TB                 | 1        | 1.75%   |
| WDC WD10EZEX-00BN5A0 1TB                 | 1        | 1.75%   |
| WDC WD1003FZEX-00MK2A0 1TB               | 1        | 1.75%   |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB       | 1        | 1.75%   |
| Unknown SD/MMC/MS PRO 128GB              | 1        | 1.75%   |
| Unknown 128G32  128GB                    | 1        | 1.75%   |
| Transcend TS512GSSD370S 512GB            | 1        | 1.75%   |
| Toshiba TR150 480GB SSD                  | 1        | 1.75%   |
| Toshiba HDWE160 6TB                      | 1        | 1.75%   |
| Team T253X1120G 120GB SSD                | 1        | 1.75%   |
| Seagate ST3750528AS 752GB                | 1        | 1.75%   |
| Seagate ST3500418AS 500GB                | 1        | 1.75%   |
| Seagate ST3500312CS 500GB                | 1        | 1.75%   |
| Seagate ST1000NM0011 1TB                 | 1        | 1.75%   |
| Seagate ST1000DM010-2EP102 1TB           | 1        | 1.75%   |
| SanDisk SSD PLUS 480GB                   | 1        | 1.75%   |
| SanDisk SDSSDX240GG25 240GB              | 1        | 1.75%   |
| Samsung SSD 950 PRO 512GB                | 1        | 1.75%   |
| Samsung SSD 860 QVO 1TB                  | 1        | 1.75%   |
| Samsung SSD 850 PRO 256GB                | 1        | 1.75%   |
| Samsung NVMe SSD Drive 500GB             | 1        | 1.75%   |
| Samsung NVMe SSD Drive 1TB               | 1        | 1.75%   |
| Samsung MZNTE512HMJH-000H1 512GB SSD     | 1        | 1.75%   |
| Samsung HD322HJ 320GB                    | 1        | 1.75%   |
| PNY CS900 480GB SSD                      | 1        | 1.75%   |
| Phison Sabrent 2TB                       | 1        | 1.75%   |
| Phison NVMe SSD Drive 1TB                | 1        | 1.75%   |
| OCZ AGILITY3 240GB SSD                   | 1        | 1.75%   |
| Micron MTFDDAK512TBN-1AR15ABHA 512GB SSD | 1        | 1.75%   |
| Kingston SHFS37A120G 120GB SSD           | 1        | 1.75%   |
| Kingston SA400S37240G 240GB SSD          | 1        | 1.75%   |
| Kingston SA2000M8250G 250GB              | 1        | 1.75%   |
| Kingston NVMe SSD Drive 500GB            | 1        | 1.75%   |
| Hitachi HTS547575A9E384 752GB            | 1        | 1.75%   |
| HGST HUS724030ALA640 3TB                 | 1        | 1.75%   |
| GOODRAM SSD 120GB                        | 1        | 1.75%   |
| Crucial CT525MX300SSD1 528GB             | 1        | 1.75%   |
| Crucial CT256M550SSD1 256GB              | 1        | 1.75%   |
| Crucial CT240BX500SSD1 240GB             | 1        | 1.75%   |
| Crucial CT120M500SSD1 120GB              | 1        | 1.75%   |
| Crucial CT120BX300SSD1 120GB             | 1        | 1.75%   |
| ASMT 2235 240GB                          | 1        | 1.75%   |
| ASMT 2115 500GB                          | 1        | 1.75%   |
| A-DATA SWORDFISH 250GB                   | 1        | 1.75%   |
| A-DATA SU800 2TB SSD                     | 1        | 1.75%   |
| A-DATA ISSS332-128GM 128GB SSD           | 1        | 1.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 9      | 41.18%  |
| Seagate             | 5        | 5      | 29.41%  |
| Unknown             | 1        | 1      | 5.88%   |
| Toshiba             | 1        | 1      | 5.88%   |
| Samsung Electronics | 1        | 1      | 5.88%   |
| Hitachi             | 1        | 1      | 5.88%   |
| HGST                | 1        | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Crucial             | 5        | 5      | 20%     |
| WDC                 | 3        | 5      | 12%     |
| Samsung Electronics | 3        | 3      | 12%     |
| SanDisk             | 2        | 2      | 8%      |
| Kingston            | 2        | 2      | 8%      |
| A-DATA Technology   | 2        | 2      | 8%      |
| Transcend           | 1        | 1      | 4%      |
| Toshiba             | 1        | 1      | 4%      |
| Team                | 1        | 1      | 4%      |
| PNY                 | 1        | 1      | 4%      |
| OCZ                 | 1        | 1      | 4%      |
| Micron Technology   | 1        | 1      | 4%      |
| GOODRAM             | 1        | 1      | 4%      |
| ASMT                | 1        | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 20       | 27     | 44.44%  |
| HDD     | 14       | 19     | 31.11%  |
| NVMe    | 9        | 11     | 20%     |
| MMC     | 1        | 1      | 2.22%   |
| Unknown | 1        | 1      | 2.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 23       | 44     | 63.89%  |
| NVMe | 9        | 11     | 25%     |
| SAS  | 3        | 3      | 8.33%   |
| MMC  | 1        | 1      | 2.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 17       | 28     | 56.67%  |
| 0.51-1.0   | 8        | 13     | 26.67%  |
| 3.01-4.0   | 2        | 2      | 6.67%   |
| 2.01-3.0   | 1        | 1      | 3.33%   |
| 1.01-2.0   | 1        | 1      | 3.33%   |
| 4.01-10.0  | 1        | 1      | 3.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 9        | 34.62%  |
| 501-1000       | 5        | 19.23%  |
| 251-500        | 4        | 15.38%  |
| 1001-2000      | 3        | 11.54%  |
| More than 3000 | 2        | 7.69%   |
| 2001-3000      | 2        | 7.69%   |
| 51-100         | 1        | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 101-250   | 6        | 23.08%  |
| 1-20      | 6        | 23.08%  |
| 21-50     | 4        | 15.38%  |
| 251-500   | 3        | 11.54%  |
| 2001-3000 | 2        | 7.69%   |
| 1001-2000 | 2        | 7.69%   |
| 51-100    | 2        | 7.69%   |
| 501-1000  | 1        | 3.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD1003FZEX-00MK2A0 1TB  | 1        | 1      | 25%     |
| Seagate ST3500312CS 500GB   | 1        | 1      | 25%     |
| HGST HUS724030ALA640 3TB    | 1        | 1      | 25%     |
| Crucial CT256M550SSD1 256GB | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 25%     |
| Seagate | 1        | 1      | 25%     |
| HGST    | 1        | 1      | 25%     |
| Crucial | 1        | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 33.33%  |
| Seagate | 1        | 1      | 33.33%  |
| HGST    | 1        | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 3      | 75%     |
| SSD  | 1        | 1      | 25%     |

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

| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 20       | 39     | 66.67%  |
| Works    | 7        | 16     | 23.33%  |
| Malfunc  | 3        | 4      | 10%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 14       | 38.89%  |
| AMD                         | 11       | 30.56%  |
| Kingston Technology Company | 4        | 11.11%  |
| Samsung Electronics         | 3        | 8.33%   |
| Phison Electronics          | 2        | 5.56%   |
| Sandisk                     | 1        | 2.78%   |
| Realtek Semiconductor       | 1        | 2.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 5        | 11.63%  |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 9.3%    |
| Kingston Company A2000 NVMe SSD                                                         | 3        | 6.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 6.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 6.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 4.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 4.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 4.65%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 2.33%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 2.33%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 2.33%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 2.33%   |
| Phison E12 NVMe Controller                                                              | 1        | 2.33%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                                      | 1        | 2.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 2.33%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 2.33%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 2.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 2.33%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 1        | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 2.33%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 2.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 23       | 63.89%  |
| NVMe | 9        | 25%     |
| IDE  | 4        | 11.11%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 15       | 57.69%  |
| AMD    | 11       | 42.31%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Intel Core i7-9700 CPU @ 3.00GHz           | 2        | 7.69%   |
| AMD Ryzen 9 3900X 12-Core Processor        | 2        | 7.69%   |
| AMD Ryzen 7 3700X 8-Core Processor         | 2        | 7.69%   |
| Intel Pentium CPU G3258 @ 3.20GHz          | 1        | 3.85%   |
| Intel Core i7-7700K CPU @ 4.20GHz          | 1        | 3.85%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 1        | 3.85%   |
| Intel Core i5-9400F CPU @ 2.90GHz          | 1        | 3.85%   |
| Intel Core i5-8400 CPU @ 2.80GHz           | 1        | 3.85%   |
| Intel Core i5-6400 CPU @ 2.70GHz           | 1        | 3.85%   |
| Intel Core i5-3330S CPU @ 2.70GHz          | 1        | 3.85%   |
| Intel Core i3-8100 CPU @ 3.60GHz           | 1        | 3.85%   |
| Intel Core i3-3220 CPU @ 3.30GHz           | 1        | 3.85%   |
| Intel Celeron CPU J1900 @ 1.99GHz          | 1        | 3.85%   |
| Intel Celeron CPU G530 @ 2.40GHz           | 1        | 3.85%   |
| Intel Celeron CPU G440 @ 1.60GHz           | 1        | 3.85%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz          | 1        | 3.85%   |
| AMD Ryzen 7 3800X 8-Core Processor         | 1        | 3.85%   |
| AMD Ryzen 7 2700 Eight-Core Processor      | 1        | 3.85%   |
| AMD Ryzen 5 2600 Six-Core Processor        | 1        | 3.85%   |
| AMD Phenom II X4 B55 Processor             | 1        | 3.85%   |
| AMD Phenom II X4 820 Processor             | 1        | 3.85%   |
| AMD FX-4100 Quad-Core Processor            | 1        | 3.85%   |
| AMD Athlon 200GE with Radeon Vega Graphics | 1        | 3.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Core i7    | 4        | 15.38%  |
| Intel Core i5    | 4        | 15.38%  |
| AMD Ryzen 7      | 4        | 15.38%  |
| Intel Celeron    | 3        | 11.54%  |
| Intel Core i3    | 2        | 7.69%   |
| AMD Ryzen 9      | 2        | 7.69%   |
| AMD Phenom II X4 | 2        | 7.69%   |
| Intel Pentium    | 1        | 3.85%   |
| Intel Atom       | 1        | 3.85%   |
| AMD Ryzen 5      | 1        | 3.85%   |
| AMD FX           | 1        | 3.85%   |
| AMD Athlon       | 1        | 3.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 9        | 34.62%  |
| 8      | 6        | 23.08%  |
| 2      | 5        | 19.23%  |
| 6      | 3        | 11.54%  |
| 12     | 2        | 7.69%   |
| 1      | 1        | 3.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 26       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 14       | 53.85%  |
| 2      | 12       | 46.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 26       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x08701021 | 3        | 11.54%  |
| 0x906ea    | 2        | 7.69%   |
| 0x306c3    | 2        | 7.69%   |
| 0x306a9    | 2        | 7.69%   |
| 0x206a7    | 2        | 7.69%   |
| 0x0800820d | 2        | 7.69%   |
| Unknown    | 2        | 7.69%   |
| 0x906ed    | 1        | 3.85%   |
| 0x906eb    | 1        | 3.85%   |
| 0x906e9    | 1        | 3.85%   |
| 0x506e3    | 1        | 3.85%   |
| 0x406c4    | 1        | 3.85%   |
| 0x30678    | 1        | 3.85%   |
| 0x08701013 | 1        | 3.85%   |
| 0x08101016 | 1        | 3.85%   |
| 0x0600063e | 1        | 3.85%   |
| 0x010000db | 1        | 3.85%   |
| 0x010000c8 | 1        | 3.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 6        | 23.08%  |
| Zen 2       | 5        | 19.23%  |
| Zen+        | 2        | 7.69%   |
| Silvermont  | 2        | 7.69%   |
| SandyBridge | 2        | 7.69%   |
| K10         | 2        | 7.69%   |
| IvyBridge   | 2        | 7.69%   |
| Haswell     | 2        | 7.69%   |
| Zen         | 1        | 3.85%   |
| Skylake     | 1        | 3.85%   |
| Bulldozer   | 1        | 3.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 12       | 42.86%  |
| Intel  | 9        | 32.14%  |
| AMD    | 7        | 25%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 7.14%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 7.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2        | 7.14%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2        | 7.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 7.14%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 3.57%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 3.57%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1        | 3.57%   |
| Nvidia GP107GL [Quadro P1000]                                                            | 1        | 3.57%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 3.57%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 3.57%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 1        | 3.57%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 3.57%   |
| Nvidia GF119 [GeForce GT 625 OEM]                                                        | 1        | 3.57%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 1        | 3.57%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                                           | 1        | 3.57%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1        | 3.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 3.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 3.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 3.57%   |
| AMD RS880 [Radeon HD 4200]                                                               | 1        | 3.57%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 3.57%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                              | 1        | 3.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 12       | 46.15%  |
| 1 x Intel   | 7        | 26.92%  |
| 1 x AMD     | 6        | 23.08%  |
| Intel + AMD | 1        | 3.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 16       | 61.54%  |
| Proprietary | 10       | 38.46%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 26.92%  |
| 1.01-2.0   | 6        | 23.08%  |
| 3.01-4.0   | 5        | 19.23%  |
| 7.01-8.0   | 2        | 7.69%   |
| 8.01-16.0  | 2        | 7.69%   |
| 0.01-0.5   | 2        | 7.69%   |
| 5.01-6.0   | 1        | 3.85%   |
| 0.51-1.0   | 1        | 3.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 7        | 22.58%  |
| Acer                | 4        | 12.9%   |
| Goldstar            | 3        | 9.68%   |
| AOC                 | 3        | 9.68%   |
| Hewlett-Packard     | 2        | 6.45%   |
| Dell                | 2        | 6.45%   |
| ViewSonic           | 1        | 3.23%   |
| Philips             | 1        | 3.23%   |
| MSI                 | 1        | 3.23%   |
| LG Electronics      | 1        | 3.23%   |
| Lenovo              | 1        | 3.23%   |
| Element             | 1        | 3.23%   |
| CHR                 | 1        | 3.23%   |
| BOE                 | 1        | 3.23%   |
| BenQ                | 1        | 3.23%   |
| AUS                 | 1        | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ViewSonic LCD Monitor VX2260WM 3840x1080                             | 1        | 3.03%   |
| ViewSonic LCD Monitor VX2260WM                                       | 1        | 3.03%   |
| Samsung Electronics T24D391 SAM0B72 1920x1080 521x293mm 23.5-inch    | 1        | 3.03%   |
| Samsung Electronics S27H85x SAM0E0E 2560x1440 597x336mm 27.0-inch    | 1        | 3.03%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch | 1        | 3.03%   |
| Samsung Electronics LCD Monitor SAM0530 1360x768                     | 1        | 3.03%   |
| Samsung Electronics LCD Monitor S22D300                              | 1        | 3.03%   |
| Samsung Electronics LC32G5xT SAM7088 2560x1440 698x393mm 31.5-inch   | 1        | 3.03%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1        | 3.03%   |
| Philips PHL 275E1 PHLC20C 2560x1440 597x336mm 27.0-inch              | 1        | 3.03%   |
| MSI MAG341CQ MSI1462 3440x1440 800x330mm 34.1-inch                   | 1        | 3.03%   |
| LG Electronics LCD Monitor 2D FHD LG TV 3840x1080                    | 1        | 3.03%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                 | 1        | 3.03%   |
| Hewlett-Packard LCD Monitor w17e 1440x900                            | 1        | 3.03%   |
| Hewlett-Packard 2010 HWP2889 1600x900 442x249mm 20.0-inch            | 1        | 3.03%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 1        | 3.03%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                | 1        | 3.03%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                 | 1        | 3.03%   |
| Element ELEFW328C ELE3553 1360x768 690x390mm 31.2-inch               | 1        | 3.03%   |
| Dell U2312HM DEL4073 1920x1080 510x290mm 23.1-inch                   | 1        | 3.03%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                    | 1        | 3.03%   |
| Dell P2214H DELA098 1920x1080 477x268mm 21.5-inch                    | 1        | 3.03%   |
| CHR 1 CHR7511 1024x768 518x333mm 24.2-inch                           | 1        | 3.03%   |
| BOE LCD Monitor BOE07B0 1920x1080 340x190mm 15.3-inch                | 1        | 3.03%   |
| BenQ LCD Monitor PD2700U 3840x2160                                   | 1        | 3.03%   |
| AUS LCD Monitor VG27AQL1A 2560x1440                                  | 1        | 3.03%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                  | 1        | 3.03%   |
| AOC 27B2 AOC2702 1920x1080 598x336mm 27.0-inch                       | 1        | 3.03%   |
| AOC 2343 AOC2343 1920x1080 509x286mm 23.0-inch                       | 1        | 3.03%   |
| Acer V206HQLB ACR051A 1366x768 434x236mm 19.4-inch                   | 1        | 3.03%   |
| Acer LCD Monitor K242HQK 3840x2160                                   | 1        | 3.03%   |
| Acer EK220Q ACR0757 1920x1080 477x268mm 21.5-inch                    | 1        | 3.03%   |
| Acer BM320 ACR0551 3840x2160 710x400mm 32.1-inch                     | 1        | 3.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 9        | 29.03%  |
| 2560x1440 (QHD)  | 6        | 19.35%  |
| 3840x2160 (4K)   | 5        | 16.13%  |
| 3840x1080        | 2        | 6.45%   |
| 1600x900 (HD+)   | 2        | 6.45%   |
| 1366x768 (WXGA)  | 2        | 6.45%   |
| Unknown          | 2        | 6.45%   |
| 3440x1440        | 1        | 3.23%   |
| 1440x900 (WXGA+) | 1        | 3.23%   |
| 1360x768         | 1        | 3.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 7        | 23.33%  |
| 23      | 4        | 13.33%  |
| 21      | 4        | 13.33%  |
| 27      | 3        | 10%     |
| 24      | 3        | 10%     |
| 32      | 2        | 6.67%   |
| 20      | 2        | 6.67%   |
| 34      | 1        | 3.33%   |
| 33      | 1        | 3.33%   |
| 31      | 1        | 3.33%   |
| 19      | 1        | 3.33%   |
| 15      | 1        | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 8        | 27.59%  |
| 401-500     | 7        | 24.14%  |
| Unknown     | 7        | 24.14%  |
| 701-800     | 4        | 13.79%  |
| 601-700     | 2        | 6.9%    |
| 301-350     | 1        | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 18       | 69.23%  |
| Unknown | 6        | 23.08%  |
| 21/9    | 1        | 3.85%   |
| 16/10   | 1        | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 27.59%  |
| Unknown        | 7        | 24.14%  |
| 351-500        | 5        | 17.24%  |
| 151-200        | 4        | 13.79%  |
| 301-350        | 3        | 10.34%  |
| 251-300        | 1        | 3.45%   |
| 91-100         | 1        | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 12       | 42.86%  |
| 101-120 | 7        | 25%     |
| Unknown | 7        | 25%     |
| 121-160 | 2        | 7.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 18       | 69.23%  |
| 2     | 8        | 30.77%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 42.5%   |
| Intel                 | 9        | 22.5%   |
| TP-Link               | 3        | 7.5%    |
| Ralink Technology     | 3        | 7.5%    |
| Broadcom              | 2        | 5%      |
| Samsung Electronics   | 1        | 2.5%    |
| Ralink                | 1        | 2.5%    |
| Qualcomm Atheros      | 1        | 2.5%    |
| Motorola PCS          | 1        | 2.5%    |
| Microsoft             | 1        | 2.5%    |
| Linksys               | 1        | 2.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13       | 28.89%  |
| Ralink MT7601U Wireless Adapter                                   | 3        | 6.67%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 6.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 4.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 4.44%   |
| Realtek 802.11ac NIC                                              | 2        | 4.44%   |
| Intel I211 Gigabit Network Connection                             | 2        | 4.44%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                             | 1        | 2.22%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 2.22%   |
| TP-Link 802.11ac NIC                                              | 1        | 2.22%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 2.22%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 2.22%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 2.22%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2.22%   |
| Motorola PCS Moto G (4)                                           | 1        | 2.22%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 2.22%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                         | 1        | 2.22%   |
| Intel Wireless-AC 9260                                            | 1        | 2.22%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 2.22%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2.22%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 2.22%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 2.22%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1        | 2.22%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 1        | 2.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| TP-Link               | 3        | 17.65%  |
| Realtek Semiconductor | 3        | 17.65%  |
| Ralink Technology     | 3        | 17.65%  |
| Intel                 | 3        | 17.65%  |
| Broadcom              | 2        | 11.76%  |
| Ralink                | 1        | 5.88%   |
| Microsoft             | 1        | 5.88%   |
| Linksys               | 1        | 5.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                    | 3        | 17.65%  |
| Realtek 802.11ac NIC                               | 2        | 11.76%  |
| TP-Link TL-WN822N Version 4 RTL8192EU              | 1        | 5.88%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                | 1        | 5.88%   |
| TP-Link 802.11ac NIC                               | 1        | 5.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                 | 1        | 5.88%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe          | 1        | 5.88%   |
| Microsoft Xbox 360 Wireless Adapter                | 1        | 5.88%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]          | 1        | 5.88%   |
| Intel Wireless-AC 9260                             | 1        | 5.88%   |
| Intel Wi-Fi 6 AX200                                | 1        | 5.88%   |
| Intel Cannon Lake PCH CNVi WiFi                    | 1        | 5.88%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC        | 1        | 5.88%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter | 1        | 5.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 60.71%  |
| Intel                 | 8        | 28.57%  |
| Samsung Electronics   | 1        | 3.57%   |
| Qualcomm Atheros      | 1        | 3.57%   |
| Motorola PCS          | 1        | 3.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13       | 46.43%  |
| Intel Ethernet Connection (2) I219-V                              | 3        | 10.71%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 7.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 7.14%   |
| Intel I211 Gigabit Network Connection                             | 2        | 7.14%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 3.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 3.57%   |
| Motorola PCS Moto G (4)                                           | 1        | 3.57%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 3.57%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 3.57%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 3.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 25       | 64.1%   |
| WiFi     | 14       | 35.9%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 24       | 68.57%  |
| WiFi     | 11       | 31.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 73.08%  |
| 2     | 5        | 19.23%  |
| 3     | 1        | 3.85%   |
| 0     | 1        | 3.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Desktops | Percent |
|------|----------|---------|
| No   | 20       | 76.92%  |
| Yes  | 6        | 23.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 3        | 42.86%  |
| Cambridge Silicon Radio | 2        | 28.57%  |
| Realtek Semiconductor   | 1        | 14.29%  |
| IMC Networks            | 1        | 14.29%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 28.57%  |
| Realtek Bluetooth Radio                             | 1        | 14.29%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 14.29%  |
| Intel Bluetooth Device                              | 1        | 14.29%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 14.29%  |
| IMC Networks BCM20702A0                             | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 12       | 27.91%  |
| Nvidia              | 11       | 25.58%  |
| AMD                 | 11       | 25.58%  |
| C-Media Electronics | 5        | 11.63%  |
| Razer USA           | 1        | 2.33%   |
| Logitech            | 1        | 2.33%   |
| Focusrite-Novation  | 1        | 2.33%   |
| Creative Labs       | 1        | 2.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 8.16%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4        | 8.16%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 6.12%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 6.12%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 6.12%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 4.08%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 4.08%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 4.08%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 4.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 4.08%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 4.08%   |
| Razer USA RC30-026902, Gaming Headset [Nari Essential, Wireless, Receiver] | 1        | 2.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 2.04%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 2.04%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 2.04%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 2.04%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 2.04%   |
| Logitech G733 Gaming Headset                                               | 1        | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1        | 2.04%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 2.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 2.04%   |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                          | 1        | 2.04%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1        | 2.04%   |
| C-Media Electronics USB Audio Device                                       | 1        | 2.04%   |
| C-Media Electronics SABAJ D3                                               | 1        | 2.04%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1        | 2.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 2.04%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 2.04%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 1        | 2.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 4        | 40%     |
| Unknown             | 1        | 10%     |
| Samsung Electronics | 1        | 10%     |
| Ramaxel Technology  | 1        | 10%     |
| PNY                 | 1        | 10%     |
| Patriot             | 1        | 10%     |
| Corsair             | 1        | 10%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s              | 1        | 10%     |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s              | 1        | 10%     |
| Ramaxel RAM RMUA5090KB78HAF2133 8192MB DIMM DDR4 2133MT/s | 1        | 10%     |
| PNY RAM 8GBF1X08QFHH38-135-K 8192MB DIMM DDR4 3200MT/s    | 1        | 10%     |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s       | 1        | 10%     |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s       | 1        | 10%     |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1866MT/s       | 1        | 10%     |
| Kingston RAM 9905625-030.A00G 8192MB DIMM DDR4 2133MT/s   | 1        | 10%     |
| Kingston RAM 9905471-015.A00LF 4096MB DIMM DDR3 1333MT/s  | 1        | 10%     |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s      | 1        | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 6        | 66.67%  |
| DDR3 | 3        | 33.33%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 9        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 6        | 66.67%  |
| 32768 | 1        | 11.11%  |
| 16384 | 1        | 11.11%  |
| 4096  | 1        | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 3        | 33.33%  |
| 2800  | 1        | 11.11%  |
| 2666  | 1        | 11.11%  |
| 2133  | 1        | 11.11%  |
| 1866  | 1        | 11.11%  |
| 1333  | 1        | 11.11%  |
| 1066  | 1        | 11.11%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)

![Printer Vendor](./images/line_chart/printer_vendor.svg)

| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)

![Printer Model](./images/line_chart/printer_model.svg)

| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Canon PIXMA MG3600 Series | 1        | 100%    |

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

| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Logitech | 1        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech B525 HD Webcam | 1        | 100%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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

| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 25       | 96.15%  |
| 1     | 1        | 3.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type         | Desktops | Percent |
|--------------|----------|---------|
| Net/wireless | 1        | 100%    |

