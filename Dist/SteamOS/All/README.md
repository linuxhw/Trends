SteamOS - Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/SteamOS/Desktop/README.md) and [notebooks](/Dist/SteamOS/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: Jun, 2023.

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

| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SteamOS 3.4.8   | 51        | 63.75%  |
| SteamOS 3.4     | 10        | 12.5%   |
| SteamOS 3.4.6   | 7         | 8.75%   |
| SteamOS Rolling | 5         | 6.25%   |
| SteamOS 3.5     | 2         | 2.5%    |
| SteamOS         | 2         | 2.5%    |
| SteamOS 4       | 1         | 1.25%   |
| SteamOS 3.4.9   | 1         | 1.25%   |
| SteamOS 3.4.4   | 1         | 1.25%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| SteamOS | 80        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version                                | Computers | Percent |
|----------------------------------------|-----------|---------|
| 5.13.0-valve36-1-neptune               | 61        | 76.25%  |
| 5.13.0-valve21.3-1-neptune             | 8         | 10%     |
| 6.1.21-valve1-3-neptune-61             | 6         | 7.5%    |
| 6.3.9-zen1-1-zen                       | 1         | 1.25%   |
| 6.1.21-valve1-1-neptune-61             | 1         | 1.25%   |
| 6.1.12-valve2-2-neptune-61             | 1         | 1.25%   |
| 5.18.1-arch1_testHoloISO_20220606.1811 | 1         | 1.25%   |
| 5.15.93-1-lts                          | 1         | 1.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.0  | 69        | 86.25%  |
| 6.1.21  | 7         | 8.75%   |
| 6.3.9   | 1         | 1.25%   |
| 6.1.12  | 1         | 1.25%   |
| 5.18.1  | 1         | 1.25%   |
| 5.15.93 | 1         | 1.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13    | 69        | 86.25%  |
| 6.1     | 8         | 10%     |
| 6.3     | 1         | 1.25%   |
| 5.18    | 1         | 1.25%   |
| 5.15    | 1         | 1.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 80        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| KDE5    | 79        | 98.75%  |
| Unknown | 1         | 1.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 77        | 96.25%  |
| Tty  | 3         | 3.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 75        | 93.75%  |
| SDDM    | 5         | 6.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 67        | 83.75%  |
| zh_CN | 5         | 6.25%   |
| ru_UA | 2         | 2.5%    |
| en_DE | 2         | 2.5%    |
| ru_RU | 1         | 1.25%   |
| n_US  | 1         | 1.25%   |
| es_ES | 1         | 1.25%   |
| de_DE | 1         | 1.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 74        | 92.5%   |
| EFI  | 6         | 7.5%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 79        | 98.75%  |
| Tmpfs | 1         | 1.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 74        | 92.5%   |
| GPT     | 6         | 7.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 77        | 96.25%  |
| Yes       | 3         | 3.75%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 95%     |
| Yes       | 4         | 5%      |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Valve               | 63        | 78.75%  |
| ASUSTek Computer    | 5         | 6.25%   |
| GPD                 | 3         | 3.75%   |
| Dell                | 3         | 3.75%   |
| Sony                | 1         | 1.25%   |
| MAXSUN              | 1         | 1.25%   |
| Lenovo              | 1         | 1.25%   |
| Hewlett-Packard     | 1         | 1.25%   |
| Gigabyte Technology | 1         | 1.25%   |
| ASRock              | 1         | 1.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Valve Jupiter                      | 63        | 78.75%  |
| Sony VGN-Z520N                     | 1         | 1.25%   |
| MAXSUN MS-H81IL TR M.2             | 1         | 1.25%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS | 1         | 1.25%   |
| HP EliteDesk 705 G5 SFF            | 1         | 1.25%   |
| GPD G1619-04                       | 1         | 1.25%   |
| GPD G1619-01                       | 1         | 1.25%   |
| GPD G1618-04                       | 1         | 1.25%   |
| Gigabyte Z170X-Gaming 6            | 1         | 1.25%   |
| Dell Venue 11 Pro 7140             | 1         | 1.25%   |
| Dell Precision 5520                | 1         | 1.25%   |
| Dell Inspiron 5535                 | 1         | 1.25%   |
| ASUS S400CA                        | 1         | 1.25%   |
| ASUS ROG STRIX B550-I GAMING       | 1         | 1.25%   |
| ASUS ROG STRIX B550-F GAMING       | 1         | 1.25%   |
| ASUS ROG Ally RC71L_RC71L          | 1         | 1.25%   |
| ASUS H110M-D                       | 1         | 1.25%   |
| ASRock H310CM-DVS                  | 1         | 1.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Valve Jupiter         | 63        | 78.75%  |
| ASUS ROG              | 3         | 3.75%   |
| Sony VGN-Z520N        | 1         | 1.25%   |
| MAXSUN MS-H81IL       | 1         | 1.25%   |
| Lenovo Yoga           | 1         | 1.25%   |
| HP EliteDesk          | 1         | 1.25%   |
| GPD G1619-04          | 1         | 1.25%   |
| GPD G1619-01          | 1         | 1.25%   |
| GPD G1618-04          | 1         | 1.25%   |
| Gigabyte Z170X-Gaming | 1         | 1.25%   |
| Dell Venue            | 1         | 1.25%   |
| Dell Precision        | 1         | 1.25%   |
| Dell Inspiron         | 1         | 1.25%   |
| ASUS S400CA           | 1         | 1.25%   |
| ASUS H110M-D          | 1         | 1.25%   |
| ASRock H310CM-DVS     | 1         | 1.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 59        | 73.75%  |
| 2023 | 8         | 10%     |
| 2020 | 3         | 3.75%   |
| 2018 | 2         | 2.5%    |
| 2017 | 2         | 2.5%    |
| 2021 | 1         | 1.25%   |
| 2015 | 1         | 1.25%   |
| 2014 | 1         | 1.25%   |
| 2013 | 1         | 1.25%   |
| 2012 | 1         | 1.25%   |
| 2009 | 1         | 1.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 71        | 88.75%  |
| Desktop    | 7         | 8.75%   |
| Tablet     | 1         | 1.25%   |
| All in one | 1         | 1.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 80        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 80        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 67        | 83.75%  |
| 16.01-24.0 | 4         | 5%      |
| 4.01-8.0   | 3         | 3.75%   |
| 32.01-64.0 | 2         | 2.5%    |
| 24.01-32.0 | 2         | 2.5%    |
| 3.01-4.0   | 1         | 1.25%   |
| 2.01-3.0   | 1         | 1.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 3.01-4.0  | 26        | 32.5%   |
| 2.01-3.0  | 26        | 32.5%   |
| 4.01-8.0  | 24        | 30%     |
| 1.01-2.0  | 2         | 2.5%    |
| 8.01-16.0 | 2         | 2.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 2      | 54        | 67.5%   |
| 1      | 21        | 26.25%  |
| 4      | 2         | 2.5%    |
| 3      | 2         | 2.5%    |
| 5      | 1         | 1.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 79        | 98.75%  |
| Yes       | 1         | 1.25%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 49        | 61.25%  |
| Yes       | 31        | 38.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 97.5%   |
| No        | 2         | 2.5%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 93.75%  |
| No        | 5         | 6.25%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 30        | 37.5%   |
| UK           | 6         | 7.5%    |
| Germany      | 6         | 7.5%    |
| China        | 5         | 6.25%   |
| Spain        | 4         | 5%      |
| Russia       | 3         | 3.75%   |
| Poland       | 3         | 3.75%   |
| Netherlands  | 3         | 3.75%   |
| Philippines  | 2         | 2.5%    |
| Canada       | 2         | 2.5%    |
| Austria      | 2         | 2.5%    |
| Ukraine      | 1         | 1.25%   |
| UAE          | 1         | 1.25%   |
| Thailand     | 1         | 1.25%   |
| Sweden       | 1         | 1.25%   |
| Saudi Arabia | 1         | 1.25%   |
| Mexico       | 1         | 1.25%   |
| Italy        | 1         | 1.25%   |
| India        | 1         | 1.25%   |
| Hungary      | 1         | 1.25%   |
| Hong Kong    | 1         | 1.25%   |
| Georgia      | 1         | 1.25%   |
| France       | 1         | 1.25%   |
| Brazil       | 1         | 1.25%   |
| Argentina    | 1         | 1.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City               | Computers | Percent |
|--------------------|-----------|---------|
| Shenzhen           | 2         | 2.5%    |
| Quezon City        | 2         | 2.5%    |
| Omaha              | 2         | 2.5%    |
| Zhukovskiy         | 1         | 1.25%   |
| Yinchuan           | 1         | 1.25%   |
| Windsor            | 1         | 1.25%   |
| Washington         | 1         | 1.25%   |
| Warsaw             | 1         | 1.25%   |
| Warendorf          | 1         | 1.25%   |
| Wanchai            | 1         | 1.25%   |
| Vostochnaya        | 1         | 1.25%   |
| Vienna             | 1         | 1.25%   |
| Torrejón de Ardoz | 1         | 1.25%   |
| Toronto            | 1         | 1.25%   |
| Tholey             | 1         | 1.25%   |
| Teddington         | 1         | 1.25%   |
| Tbilisi            | 1         | 1.25%   |
| Szczecin           | 1         | 1.25%   |
| Sherwood           | 1         | 1.25%   |
| Seattle            | 1         | 1.25%   |
| Schwenksville      | 1         | 1.25%   |
| Sassenberg         | 1         | 1.25%   |
| Sao Paulo          | 1         | 1.25%   |
| Santo Tome         | 1         | 1.25%   |
| San Jose           | 1         | 1.25%   |
| Salzburg           | 1         | 1.25%   |
| Rockwall           | 1         | 1.25%   |
| Rochester          | 1         | 1.25%   |
| Reus               | 1         | 1.25%   |
| Rancho Cordova     | 1         | 1.25%   |
| Puebla City        | 1         | 1.25%   |
| Palma              | 1         | 1.25%   |
| Olsztyn            | 1         | 1.25%   |
| Odenton            | 1         | 1.25%   |
| Nuremberg          | 1         | 1.25%   |
| Norrtaelje         | 1         | 1.25%   |
| Nakhon Ratchasima  | 1         | 1.25%   |
| Medina             | 1         | 1.25%   |
| Massena            | 1         | 1.25%   |
| Littleton          | 1         | 1.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Unknown                        | 42        | 42     | 29.37%  |
| Kingston Technology Company    | 18        | 18     | 12.59%  |
| Phison Electronics             | 16        | 16     | 11.19%  |
| Samsung Electronics            | 14        | 16     | 9.79%   |
| O2 Micro                       | 13        | 13     | 9.09%   |
| Unknown                        | 9         | 9      | 6.29%   |
| Sandisk                        | 5         | 5      | 3.5%    |
| Silicon Motion                 | 4         | 4      | 2.8%    |
| WDC                            | 3         | 4      | 2.1%    |
| Toshiba                        | 2         | 2      | 1.4%    |
| Seagate                        | 2         | 2      | 1.4%    |
| Micron/Crucial Technology      | 2         | 2      | 1.4%    |
| MAXIO Technology (Hangzhou)    | 2         | 2      | 1.4%    |
| Kingston                       | 2         | 3      | 1.4%    |
| Crucial                        | 2         | 3      | 1.4%    |
| Solid State Storage Technology | 1         | 1      | 0.7%    |
| SK hynix                       | 1         | 1      | 0.7%    |
| Realtek                        | 1         | 1      | 0.7%    |
| Netac                          | 1         | 1      | 0.7%    |
| Micron Technology              | 1         | 1      | 0.7%    |
| Biwin Storage Technology       | 1         | 1      | 0.7%    |
| 2.5                            | 1         | 1      | 0.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown MMC Card  512GB                               | 20        | 13.79%  |
| Kingston Company OM3PDP3 NVMe SSD 256GB               | 18        | 12.41%  |
| Phison PS5013 E13 NVMe Controller 512GB               | 13        | 8.97%   |
| O2 Micro E2M2 64GB                                    | 13        | 8.97%   |
| Unknown                                               | 9         | 6.21%   |
| Unknown MMC Card  256GB                               | 7         | 4.83%   |
| Samsung MZ9LQ256HBJD-00BVL 256GB                      | 4         | 2.76%   |
| Unknown MMC Card  32GB                                | 3         | 2.07%   |
| Unknown MMC Card  128GB                               | 3         | 2.07%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 3         | 2.07%   |
| Samsung MZ9LQ512HBLU-00BVL 512GB                      | 3         | 2.07%   |
| Unknown MMC Card  64GB                                | 2         | 1.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB   | 2         | 1.38%   |
| Phison Sabrent SB-2130-1TB                            | 2         | 1.38%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                   | 2         | 1.38%   |
| WDC WDS200T2B0A-00SM50 2TB SSD                        | 1         | 0.69%   |
| WDC WD20EARS-00MVWB0 2TB                              | 1         | 0.69%   |
| WDC WD Blue SA510 2.5 250GB                           | 1         | 0.69%   |
| Unknown MMC Card  500GB                               | 1         | 0.69%   |
| Unknown MMC Card  498GB                               | 1         | 0.69%   |
| Unknown MMC Card  393GB                               | 1         | 0.69%   |
| Unknown MMC Card  249GB                               | 1         | 0.69%   |
| Unknown MMC Card  1TB                                 | 1         | 0.69%   |
| Unknown MMC Card  1GB                                 | 1         | 0.69%   |
| Unknown MMC Card  196GB                               | 1         | 0.69%   |
| Toshiba XG6 NVMe SSD Controller 2TB                   | 1         | 0.69%   |
| Toshiba DT01ACA100 1TB                                | 1         | 0.69%   |
| Solid State Storage SSSTC XA1-311024 930GB            | 1         | 0.69%   |
| SK hynix BC711 NVMe 256GB                             | 1         | 0.69%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 480GB   | 1         | 0.69%   |
| Seagate ST500LT012-9WS142 500GB                       | 1         | 0.69%   |
| Seagate ST1000DM010-2EP102 1TB                        | 1         | 0.69%   |
| SanDisk X110 M.2 2260 128GB SSD                       | 1         | 0.69%   |
| Sandisk WDC PC SN530 SDBPTPZ-1T00 1024GB              | 1         | 0.69%   |
| Sandisk WD PC SN740 SDDPTQE-2T00 2TB                  | 1         | 0.69%   |
| SanDisk SSD PLUS 480GB                                | 1         | 0.69%   |
| Sandisk PC SN740 NVMe WD 512GB                        | 1         | 0.69%   |
| Samsung SSD 850 EVO M.2 1TB                           | 1         | 0.69%   |
| Samsung SSD 850 EVO 500GB                             | 1         | 0.69%   |
| Samsung SSD 840 EVO 120GB                             | 1         | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 40%     |
| WDC                 | 1         | 1      | 20%     |
| Toshiba             | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 23.08%  |
| WDC                 | 2         | 3      | 15.38%  |
| SanDisk             | 2         | 2      | 15.38%  |
| Kingston            | 2         | 3      | 15.38%  |
| Crucial             | 2         | 3      | 15.38%  |
| Netac               | 1         | 1      | 7.69%   |
| 2.5                 | 1         | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 73        | 76     | 52.52%  |
| MMC  | 51        | 51     | 36.69%  |
| SSD  | 10        | 16     | 7.19%   |
| HDD  | 5         | 5      | 3.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 73        | 75     | 53.68%  |
| MMC  | 51        | 51     | 37.5%   |
| SATA | 10        | 20     | 7.35%   |
| SAS  | 2         | 2      | 1.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9         | 12     | 60%     |
| 0.51-1.0   | 4         | 6      | 26.67%  |
| 1.01-2.0   | 2         | 3      | 13.33%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 32        | 40%     |
| 101-250        | 14        | 17.5%   |
| 501-1000       | 12        | 15%     |
| 51-100         | 9         | 11.25%  |
| 1001-2000      | 6         | 7.5%    |
| More than 3000 | 2         | 2.5%    |
| 21-50          | 2         | 2.5%    |
| 2001-3000      | 2         | 2.5%    |
| Unknown        | 1         | 1.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 251-500   | 28        | 35%     |
| 21-50     | 12        | 15%     |
| 101-250   | 12        | 15%     |
| 1-20      | 11        | 13.75%  |
| 501-1000  | 9         | 11.25%  |
| 51-100    | 4         | 5%      |
| 2001-3000 | 2         | 2.5%    |
| 1001-2000 | 1         | 1.25%   |
| Unknown   | 1         | 1.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Detected | 77        | 140    | 91.67%  |
| Works    | 6         | 7      | 7.14%   |
| Malfunc  | 1         | 1      | 1.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Kingston Technology Company    | 18        | 20.69%  |
| Phison Electronics             | 16        | 18.39%  |
| O2 Micro                       | 13        | 14.94%  |
| Samsung Electronics            | 11        | 12.64%  |
| Intel                          | 9         | 10.34%  |
| Silicon Motion                 | 4         | 4.6%    |
| AMD                            | 4         | 4.6%    |
| SanDisk                        | 3         | 3.45%   |
| Micron/Crucial Technology      | 2         | 2.3%    |
| MAXIO Technology (Hangzhou)    | 2         | 2.3%    |
| Toshiba America Info Systems   | 1         | 1.15%   |
| Solid State Storage Technology | 1         | 1.15%   |
| SK hynix                       | 1         | 1.15%   |
| Micron Technology              | 1         | 1.15%   |
| Biwin Storage Technology       | 1         | 1.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Kingston Company OM3PDP3 NVMe SSD                                              | 18        | 20.69%  |
| Phison PS5013 E13 NVMe Controller                                              | 13        | 14.94%  |
| O2 Micro Non-Volatile memory controller                                        | 13        | 14.94%  |
| Samsung NVMe SSD Controller 980                                                | 8         | 9.2%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3         | 3.45%   |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                            | 3         | 3.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 3.45%   |
| Sandisk PC SN740 NVMe SSD                                                      | 2         | 2.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 2.3%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 2.3%    |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 2.3%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 1.15%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 1.15%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 1.15%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 1.15%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 1.15%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.15%   |
| Micron NVMe Controller                                                         | 1         | 1.15%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602                                   | 1         | 1.15%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1         | 1.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.15%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.15%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 1.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1         | 1.15%   |
| Biwin Storage Non-Volatile memory controller                                   | 1         | 1.15%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1         | 1.15%   |
| AMD 400 Series Chipset SATA Controller                                         | 1         | 1.15%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 73        | 84.88%  |
| SATA | 13        | 15.12%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 71        | 88.75%  |
| Intel  | 9         | 11.25%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Custom APU 0405                             | 63        | 78.75%  |
| Intel Processor 5Y10 CPU @ 0.80GHz              | 1         | 1.25%   |
| Intel Core i7-8700K CPU @ 3.70GHz               | 1         | 1.25%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz              | 1         | 1.25%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1         | 1.25%   |
| Intel Core i7-4790K CPU @ 4.00GHz               | 1         | 1.25%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 1         | 1.25%   |
| Intel Core i5-3317U CPU @ 1.70GHz               | 1         | 1.25%   |
| Intel Core i5-1035G7 CPU @ 1.20GHz              | 1         | 1.25%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz            | 1         | 1.25%   |
| AMD Ryzen Z1 Extreme                            | 1         | 1.25%   |
| AMD Ryzen 9 5900HX with Radeon Graphics         | 1         | 1.25%   |
| AMD Ryzen 7 7840U w/ Radeon 780M Graphics       | 1         | 1.25%   |
| AMD Ryzen 7 6800U with Radeon Graphics          | 1         | 1.25%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 1         | 1.25%   |
| AMD Ryzen 5 PRO 3400G with Radeon Vega Graphics | 1         | 1.25%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 1         | 1.25%   |
| AMD A10-5745M APU with Radeon HD Graphics       | 1         | 1.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model            | Computers | Percent |
|------------------|-----------|---------|
| Other            | 65        | 81.25%  |
| Intel Core i7    | 4         | 5%      |
| Intel Core i5    | 3         | 3.75%   |
| AMD Ryzen 7      | 3         | 3.75%   |
| Intel Core 2 Duo | 1         | 1.25%   |
| AMD Ryzen 9      | 1         | 1.25%   |
| AMD Ryzen 5 PRO  | 1         | 1.25%   |
| AMD Ryzen 5      | 1         | 1.25%   |
| AMD A10          | 1         | 1.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 69        | 86.25%  |
| 8      | 5         | 6.25%   |
| 2      | 4         | 5%      |
| 6      | 2         | 2.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 80        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 77        | 96.25%  |
| 1      | 3         | 3.75%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 80        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 76        | 95%     |
| 0x0a704103 | 2         | 2.5%    |
| 0x08900201 | 2         | 2.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 82.5%   |
| Zen 3      | 3         | 3.75%   |
| KabyLake   | 3         | 3.75%   |
| Zen+       | 1         | 1.25%   |
| Skylake    | 1         | 1.25%   |
| Piledriver | 1         | 1.25%   |
| Penryn     | 1         | 1.25%   |
| IvyBridge  | 1         | 1.25%   |
| IceLake    | 1         | 1.25%   |
| Haswell    | 1         | 1.25%   |
| Broadwell  | 1         | 1.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 73        | 87.95%  |
| Intel  | 6         | 7.23%   |
| Nvidia | 4         | 4.82%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD VanGogh [AMD Custom GPU 0405]                                    | 63        | 74.12%  |
| Intel HD Graphics 630                                                | 2         | 2.35%   |
| AMD Phoenix1                                                         | 2         | 2.35%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                           | 2         | 2.35%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]         | 2         | 2.35%   |
| Nvidia GP108 [GeForce GT 1030]                                       | 1         | 1.18%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                  | 1         | 1.18%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                | 1         | 1.18%   |
| Nvidia G98M [GeForce 9300M GS]                                       | 1         | 1.18%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller         | 1         | 1.18%   |
| Intel Iris Plus Graphics G7                                          | 1         | 1.18%   |
| Intel HD Graphics 5300                                               | 1         | 1.18%   |
| Intel 3rd Gen Core processor Graphics Controller                     | 1         | 1.18%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                             | 1         | 1.18%   |
| AMD Richland [Radeon HD 8610G]                                       | 1         | 1.18%   |
| AMD Rembrandt [Radeon 680M]                                          | 1         | 1.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 1         | 1.18%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]        | 1         | 1.18%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]           | 1         | 1.18%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 71        | 88.75%  |
| 1 x Intel      | 3         | 3.75%   |
| 2 x AMD        | 2         | 2.5%    |
| 1 x Nvidia     | 2         | 2.5%    |
| Intel + Nvidia | 2         | 2.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 78        | 97.5%   |
| Proprietary | 2         | 2.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 74        | 92.5%   |
| 5.01-6.0   | 1         | 1.25%   |
| 3.01-4.0   | 1         | 1.25%   |
| 2.01-3.0   | 1         | 1.25%   |
| 1.01-2.0   | 1         | 1.25%   |
| 0.51-1.0   | 1         | 1.25%   |
| 0.01-0.5   | 1         | 1.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Valve                | 61        | 62.24%  |
| Samsung Electronics  | 7         | 7.14%   |
| Goldstar             | 2         | 2.04%   |
| Dell                 | 2         | 2.04%   |
| Ancor Communications | 2         | 2.04%   |
| Acer                 | 2         | 2.04%   |
| Westinghouse         | 1         | 1.02%   |
| Vizio                | 1         | 1.02%   |
| TMX                  | 1         | 1.02%   |
| Sharp                | 1         | 1.02%   |
| Pixio                | 1         | 1.02%   |
| ONN                  | 1         | 1.02%   |
| LG Display           | 1         | 1.02%   |
| Lenovo               | 1         | 1.02%   |
| JRY                  | 1         | 1.02%   |
| JDI                  | 1         | 1.02%   |
| INNOCN               | 1         | 1.02%   |
| HKM                  | 1         | 1.02%   |
| Hitachi              | 1         | 1.02%   |
| Hewlett-Packard      | 1         | 1.02%   |
| GPD                  | 1         | 1.02%   |
| Flipbook             | 1         | 1.02%   |
| CSO                  | 1         | 1.02%   |
| Chimei Innolux       | 1         | 1.02%   |
| BOE                  | 1         | 1.02%   |
| ASUSTek Computer     | 1         | 1.02%   |
| AOC                  | 1         | 1.02%   |
| AGO                  | 1         | 1.02%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                     | 61        | 62.24%  |
| Westinghouse WD32FE2120 WET6487 1366x768 700x390mm 31.5-inch            | 1         | 1.02%   |
| Vizio D32fM-K01 VIZ1044 1920x1080 698x392mm 31.5-inch                   | 1         | 1.02%   |
| TMX TL070FVXS01-0 TMX0002 1920x1080 160x100mm 7.4-inch                  | 1         | 1.02%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                 | 1         | 1.02%   |
| Samsung Electronics T24C550 SAM0BA5 1366x768 521x293mm 23.5-inch        | 1         | 1.02%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch    | 1         | 1.02%   |
| Samsung Electronics QBQ90S SAM7202 3840x2160 1872x1053mm 84.6-inch      | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch   | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1872x1053mm 84.6-inch | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 1         | 1.02%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1         | 1.02%   |
| Pixio G27P WAM2700 3840x2160 600x330mm 27.0-inch                        | 1         | 1.02%   |
| ONN onn. TV ONN0C94 1920x1080 698x392mm 31.5-inch                       | 1         | 1.02%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch             | 1         | 1.02%   |
| Lenovo LEN P24q-20 LEN61F5 2560x1440 527x296mm 23.8-inch                | 1         | 1.02%   |
| JRY HDMI JRY3200 1920x1080 368x207mm 16.6-inch                          | 1         | 1.02%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                      | 1         | 1.02%   |
| INNOCN PU15-PRE IOC1501 3840x2160 344x194mm 15.5-inch                   | 1         | 1.02%   |
| HKM UG27 HKM2700 1920x1080 597x336mm 27.0-inch                          | 1         | 1.02%   |
| Hitachi HISENSE HEC0030 3840x2160 1095x616mm 49.5-inch                  | 1         | 1.02%   |
| Hewlett-Packard 20wm HWP3085 1600x900 443x249mm 20.0-inch               | 1         | 1.02%   |
| GPD G1618-04 GPD0598 1920x1080                                          | 1         | 1.02%   |
| Goldstar ULTRAGEAR GSM5C02 1920x1080 600x340mm 27.2-inch                | 1         | 1.02%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 1         | 1.02%   |
| Flipbook NexDock YUK40F4 1920x1080 293x165mm 13.2-inch                  | 1         | 1.02%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                       | 1         | 1.02%   |
| Dell G2722HS DEL427F 1920x1080 597x336mm 27.0-inch                      | 1         | 1.02%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                   | 1         | 1.02%   |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 344x193mm 15.5-inch         | 1         | 1.02%   |
| BOE TV080WUM-NL0 BOE0003 800x1280 108x172mm 8.0-inch                    | 1         | 1.02%   |
| ASUSTek Computer MG248 AUS24A4 1920x1080 531x299mm 24.0-inch            | 1         | 1.02%   |
| AOC 2476WM AOC2476 1920x1080 521x293mm 23.5-inch                        | 1         | 1.02%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch   | 1         | 1.02%   |
| Ancor Communications ASUS PB277 ACI27B5 2560x1440 597x336mm 27.0-inch   | 1         | 1.02%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                   | 1         | 1.02%   |
| Acer V226HQL ACR032D 1920x1080 477x268mm 21.5-inch                      | 1         | 1.02%   |
| Acer G245HQ ACR012B 1920x1080 521x293mm 23.5-inch                       | 1         | 1.02%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 800x1280         | 61        | 62.89%  |
| 1920x1080 (FHD)  | 16        | 16.49%  |
| 3840x2160 (4K)   | 7         | 7.22%   |
| 1366x768 (WXGA)  | 5         | 5.15%   |
| 2560x1440 (QHD)  | 2         | 2.06%   |
| 2880x1800        | 1         | 1.03%   |
| 2560x1600        | 1         | 1.03%   |
| 2560x1080        | 1         | 1.03%   |
| 1600x900 (HD+)   | 1         | 1.03%   |
| 1600x2560        | 1         | 1.03%   |
| 1280x1024 (SXGA) | 1         | 1.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 7       | 62        | 63.27%  |
| 27      | 5         | 5.1%    |
| 31      | 4         | 4.08%   |
| 84      | 3         | 3.06%   |
| 24      | 3         | 3.06%   |
| 23      | 3         | 3.06%   |
| 15      | 3         | 3.06%   |
| 40      | 2         | 2.04%   |
| 21      | 2         | 2.04%   |
| 14      | 2         | 2.04%   |
| 34      | 1         | 1.02%   |
| 20      | 1         | 1.02%   |
| 19      | 1         | 1.02%   |
| 18      | 1         | 1.02%   |
| 16      | 1         | 1.02%   |
| 13      | 1         | 1.02%   |
| 12      | 1         | 1.02%   |
| 8       | 1         | 1.02%   |
| Unknown | 1         | 1.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 1-100       | 61        | 62.89%  |
| 501-600     | 10        | 10.31%  |
| 301-350     | 5         | 5.15%   |
| 601-700     | 4         | 4.12%   |
| 401-500     | 4         | 4.12%   |
| 1501-2000   | 3         | 3.09%   |
| 801-900     | 2         | 2.06%   |
| 351-400     | 2         | 2.06%   |
| 201-300     | 2         | 2.06%   |
| 101-200     | 2         | 2.06%   |
| 701-800     | 1         | 1.03%   |
| Unknown     | 1         | 1.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 0.67  | 61        | 62.89%  |
| 16/9  | 30        | 30.93%  |
| 16/10 | 2         | 2.06%   |
| 5/4   | 1         | 1.03%   |
| 4/3   | 1         | 1.03%   |
| 21/9  | 1         | 1.03%   |
| 0.63  | 1         | 1.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 1-40           | 63        | 64.95%  |
| 201-250        | 7         | 7.22%   |
| 351-500        | 5         | 5.15%   |
| 301-350        | 5         | 5.15%   |
| More than 1000 | 3         | 3.09%   |
| 101-110        | 3         | 3.09%   |
| 81-90          | 2         | 2.06%   |
| 71-80          | 2         | 2.06%   |
| 151-200        | 2         | 2.06%   |
| 501-1000       | 2         | 2.06%   |
| 141-150        | 1         | 1.03%   |
| 111-120        | 1         | 1.03%   |
| Unknown        | 1         | 1.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 161-240       | 62        | 65.26%  |
| 51-100        | 16        | 16.84%  |
| 101-120       | 7         | 7.37%   |
| More than 240 | 5         | 5.26%   |
| 1-50          | 2         | 2.11%   |
| 121-160       | 2         | 2.11%   |
| Unknown       | 1         | 1.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 59        | 73.75%  |
| 2     | 20        | 25%     |
| 3     | 1         | 1.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 72        | 74.23%  |
| Intel                 | 10        | 10.31%  |
| ASIX Electronics      | 8         | 8.25%   |
| Qualcomm Atheros      | 3         | 3.09%   |
| MediaTek              | 1         | 1.03%   |
| DisplayLink           | 1         | 1.03%   |
| Dell                  | 1         | 1.03%   |
| Broadcom              | 1         | 1.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 63        | 55.26%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 9.65%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 7.02%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 3.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 2.63%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 2.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 1.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.75%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.88%   |
| Realtek 802.11ac NIC                                              | 1         | 0.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.88%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.88%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.88%   |
| Intel Wireless 8265 / 8275                                        | 1         | 0.88%   |
| Intel Wireless 7265                                               | 1         | 0.88%   |
| Intel WiFi Link 5100                                              | 1         | 0.88%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.88%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.88%   |
| DisplayLink USB 3.0 Docking Station                               | 1         | 0.88%   |
| Dell DW5810e LTE WWAN                                             | 1         | 0.88%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1         | 0.88%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 66        | 83.54%  |
| Intel                 | 9         | 11.39%  |
| Qualcomm Atheros      | 2         | 2.53%   |
| MediaTek              | 1         | 1.27%   |
| Broadcom              | 1         | 1.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 63        | 79.75%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 3         | 3.8%    |
| Intel Wi-Fi 6 AX200                                           | 3         | 3.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 1.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 1.27%   |
| Realtek 802.11ac NIC                                          | 1         | 1.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 1         | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1         | 1.27%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1         | 1.27%   |
| Intel Wireless 8265 / 8275                                    | 1         | 1.27%   |
| Intel Wireless 7265                                           | 1         | 1.27%   |
| Intel WiFi Link 5100                                          | 1         | 1.27%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 1         | 1.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 19        | 55.88%  |
| ASIX Electronics      | 8         | 23.53%  |
| Intel                 | 4         | 11.76%  |
| Qualcomm Atheros      | 2         | 5.88%   |
| DisplayLink           | 1         | 2.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 32.35%  |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 23.53%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 11.76%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 5.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 5.88%   |
| Intel Ethernet Controller I225-V                                  | 2         | 5.88%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2.94%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.94%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.94%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.94%   |
| DisplayLink USB 3.0 Docking Station                               | 1         | 2.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 78        | 70.91%  |
| Ethernet | 31        | 28.18%  |
| Unknown  | 1         | 0.91%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 72        | 87.8%   |
| Ethernet | 10        | 12.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 72        | 90%     |
| 2     | 7         | 8.75%   |
| 3     | 1         | 1.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 50        | 62.5%   |
| Yes  | 30        | 37.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| IMC Networks                    | 62        | 81.58%  |
| Intel                           | 8         | 10.53%  |
| Realtek Semiconductor           | 1         | 1.32%   |
| Qualcomm Atheros Communications | 1         | 1.32%   |
| Foxconn / Hon Hai               | 1         | 1.32%   |
| Cambridge Silicon Radio         | 1         | 1.32%   |
| Apple                           | 1         | 1.32%   |
| Alps Electric                   | 1         | 1.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Bluetooth Radio                        | 62        | 81.58%  |
| Intel AX210 Bluetooth                               | 3         | 3.95%   |
| Intel AX200 Bluetooth                               | 3         | 3.95%   |
| Intel Bluetooth wireless interface                  | 2         | 2.63%   |
| Realtek Bluetooth Radio                             | 1         | 1.32%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.32%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.32%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.32%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 1.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| AMD                        | 73        | 80.22%  |
| Intel                      | 9         | 9.89%   |
| Nvidia                     | 2         | 2.2%    |
| C-Media Electronics        | 2         | 2.2%    |
| Razer USA                  | 1         | 1.1%    |
| PreSonus Audio Electronics | 1         | 1.1%    |
| Plantronics                | 1         | 1.1%    |
| Logitech                   | 1         | 1.1%    |
| JMTek                      | 1         | 1.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Rembrandt Radeon High Definition Audio Controller               | 66        | 65.35%  |
| AMD Family 17h/19h HD Audio Controller                              | 6         | 5.94%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                             | 3         | 2.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2         | 1.98%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 2         | 1.98%   |
| Razer USA Razer Kraken V3 Pro                                       | 1         | 0.99%   |
| PreSonus Audio Electronics AudioBox USB 96                          | 1         | 0.99%   |
| Plantronics Poly BT700                                              | 1         | 0.99%   |
| Nvidia GP108 High Definition Audio Controller                       | 1         | 0.99%   |
| Nvidia GP106 High Definition Audio Controller                       | 1         | 0.99%   |
| Logitech G432 Gaming Headset                                        | 1         | 0.99%   |
| JMTek USB PnP Audio Device                                          | 1         | 0.99%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller           | 1         | 0.99%   |
| Intel CM238 HD Audio Controller                                     | 1         | 0.99%   |
| Intel Broadwell-U Audio Controller                                  | 1         | 0.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                      | 1         | 0.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 1         | 0.99%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 0.99%   |
| Intel 200 Series PCH HD Audio                                       | 1         | 0.99%   |
| C-Media Electronics USB Audio Device                                | 1         | 0.99%   |
| C-Media Electronics BIRD UM1                                        | 1         | 0.99%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                          | 1         | 0.99%   |
| AMD Trinity HDMI Audio Controller                                   | 1         | 0.99%   |
| AMD Starship/Matisse HD Audio Controller                            | 1         | 0.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 1         | 0.99%   |
| AMD FCH Azalia Controller                                           | 1         | 0.99%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 1         | 0.99%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 3         | 42.86%  |
| Samsung Electronics | 2         | 28.57%  |
| SK hynix            | 1         | 14.29%  |
| Kingston            | 1         | 14.29%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| SK hynix RAM H9JCNNNCP3MLCR-N6E 4GB DIMM LPDDR5 6400MT/s   | 1         | 14.29%  |
| Samsung RAM K3LKBKB0BM-MGCP 4GB SODIMM LPDDR5 6400MT/s     | 1         | 14.29%  |
| Samsung RAM K3LK7K70BM-BGCP000 4GB SODIMM LPDDR5 4266MT/s  | 1         | 14.29%  |
| Micron RAM MT62F2G32D4DS-026 WT 8GB SODIMM LPDDR5 7500MT/s | 1         | 14.29%  |
| Micron RAM MT62F1G32D4DR-031 WT 4GB SODIMM LPDDR5 6400MT/s | 1         | 14.29%  |
| Micron RAM 8JTF5126 4HZ1G6D 1 4GB SODIMM DDR3 1600MT/s     | 1         | 14.29%  |
| Kingston RAM 9905417-054.A00G 4GB SODIMM DDR3 1600MT/s     | 1         | 14.29%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind   | Computers | Percent |
|--------|-----------|---------|
| LPDDR5 | 5         | 83.33%  |
| DDR3   | 1         | 16.67%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 5         | 83.33%  |
| DIMM   | 1         | 16.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size | Computers | Percent |
|------|-----------|---------|
| 4096 | 5         | 83.33%  |
| 8192 | 1         | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 6400  | 3         | 50%     |
| 7500  | 1         | 16.67%  |
| 4266  | 1         | 16.67%  |
| 1600  | 1         | 16.67%  |

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

| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Microdia                      | 2         | 18.18%  |
| Logitech                      | 2         | 18.18%  |
| Tripath Technology            | 1         | 9.09%   |
| Sunplus Innovation Technology | 1         | 9.09%   |
| Ricoh                         | 1         | 9.09%   |
| Realtek Semiconductor         | 1         | 9.09%   |
| IPEVO                         | 1         | 9.09%   |
| IMC Networks                  | 1         | 9.09%   |
| Alpha Imaging Technology      | 1         | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Logitech HD Pro Webcam C920               | 2         | 18.18%  |
| Tripath USB Camera                        | 1         | 9.09%   |
| Sunplus Asus Webcam                       | 1         | 9.09%   |
| Ricoh Sony Vaio Integrated Webcam         | 1         | 9.09%   |
| Realtek Integrated_Webcam_FHD             | 1         | 9.09%   |
| Microdia Integrated_Webcam_HD             | 1         | 9.09%   |
| Microdia Dell Laptop Integrated Webcam HD | 1         | 9.09%   |
| IPEVO V4K                                 | 1         | 9.09%   |
| IMC Networks Integrated Camera            | 1         | 9.09%   |
| Alpha Imaging Integrated_Webcam_8M        | 1         | 9.09%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Upek               | 1         | 50%     |
| Focal-systems.Corp | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 50%     |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 50%     |

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
| 0     | 75        | 93.75%  |
| 2     | 2         | 2.5%    |
| 1     | 2         | 2.5%    |
| 3     | 1         | 1.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 2         | 25%     |
| Graphics card         | 2         | 25%     |
| Fingerprint reader    | 2         | 25%     |
| Multimedia controller | 1         | 12.5%   |
| Camera                | 1         | 12.5%   |

