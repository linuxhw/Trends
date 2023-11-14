SteamOS - Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/SteamOS/Desktop/README.md) and [notebooks](/Dist/SteamOS/Notebook/README.md).

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

![OS](./All/images/pie_chart/os_name.svg)

![OS](./All/images/line_chart/os_name.svg)

| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SteamOS 3.4.11  | 32        | 41.03%  |
| SteamOS 3.4.10  | 14        | 17.95%  |
| SteamOS 3.5.1   | 10        | 12.82%  |
| SteamOS 4       | 8         | 10.26%  |
| SteamOS 3.5     | 6         | 7.69%   |
| SteamOS 3.6     | 3         | 3.85%   |
| SteamOS Rolling | 1         | 1.28%   |
| SteamOS 3.4.8   | 1         | 1.28%   |
| SteamOS 3.4.6   | 1         | 1.28%   |
| SteamOS 3.4.4   | 1         | 1.28%   |
| SteamOS 3.4     | 1         | 1.28%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| SteamOS | 78        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.13.0-valve37-1-neptune   | 46        | 58.97%  |
| 6.1.52-valve3-1-neptune-61 | 10        | 12.82%  |
| 6.1.52-valve2-1-neptune-61 | 10        | 12.82%  |
| 6.4.12-zen1-1-zen          | 5         | 6.41%   |
| 6.3.7-zen1-1-zen           | 3         | 3.85%   |
| 5.13.0-valve36-1-neptune   | 3         | 3.85%   |
| 5.13.0-valve21.3-1-neptune | 1         | 1.28%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.0  | 50        | 64.1%   |
| 6.1.52  | 20        | 25.64%  |
| 6.4.12  | 5         | 6.41%   |
| 6.3.7   | 3         | 3.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13    | 50        | 64.1%   |
| 6.1     | 20        | 25.64%  |
| 6.4     | 5         | 6.41%   |
| 6.3     | 3         | 3.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 78        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| KDE5 | 78        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 78        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 77        | 98.72%  |
| SDDM    | 1         | 1.28%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 67        | 85.9%   |
| ru_RU | 2         | 2.56%   |
| fr_FR | 2         | 2.56%   |
| en_GB | 2         | 2.56%   |
| de_DE | 2         | 2.56%   |
| pt_BR | 1         | 1.28%   |
| en_IE | 1         | 1.28%   |
| C     | 1         | 1.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 77        | 98.72%  |
| EFI  | 1         | 1.28%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 78        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 77        | 98.72%  |
| GPT     | 1         | 1.28%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 77        | 98.72%  |
| Yes       | 1         | 1.28%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 78        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Valve                                | 69        | 88.46%  |
| Hewlett-Packard                      | 4         | 5.13%   |
| Gigabyte Technology                  | 2         | 2.56%   |
| Acer                                 | 2         | 2.56%   |
| Shenzhen Meigao Electronic Equipment | 1         | 1.28%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                                | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Valve Jupiter                                       | 69        | 88.46%  |
| Shenzhen Meigao Electronic Equipment Mercury series | 1         | 1.28%   |
| HP Victus by Gaming Laptop 16-s0xxx                 | 1         | 1.28%   |
| HP Victus by 15L Gaming Desktop TG02-0xxx           | 1         | 1.28%   |
| HP Pavilion Laptop 15-eh0xxx                        | 1         | 1.28%   |
| HP EliteDesk 800 G3 DM 35W                          | 1         | 1.28%   |
| Gigabyte B550M S2H                                  | 1         | 1.28%   |
| Gigabyte B450 AORUS PRO WIFI                        | 1         | 1.28%   |
| Acer Swift SFA16-41                                 | 1         | 1.28%   |
| Acer Nitro AN515-56                                 | 1         | 1.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Valve Jupiter                                | 69        | 88.46%  |
| HP Victus                                    | 2         | 2.56%   |
| Shenzhen Meigao Electronic Equipment Mercury | 1         | 1.28%   |
| HP Pavilion                                  | 1         | 1.28%   |
| HP EliteDesk                                 | 1         | 1.28%   |
| Gigabyte B550M                               | 1         | 1.28%   |
| Gigabyte B450                                | 1         | 1.28%   |
| Acer Swift                                   | 1         | 1.28%   |
| Acer Nitro                                   | 1         | 1.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2023 | 46        | 58.97%  |
| 2022 | 27        | 34.62%  |
| 2020 | 2         | 2.56%   |
| 2021 | 1         | 1.28%   |
| 2018 | 1         | 1.28%   |
| 2017 | 1         | 1.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 73        | 93.59%  |
| Desktop  | 4         | 5.13%   |
| Mini pc  | 1         | 1.28%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 78        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 78        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 72        | 92.31%  |
| 16.01-24.0 | 3         | 3.85%   |
| 4.01-8.0   | 1         | 1.28%   |
| 32.01-64.0 | 1         | 1.28%   |
| 24.01-32.0 | 1         | 1.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 34        | 43.59%  |
| 3.01-4.0  | 22        | 28.21%  |
| 2.01-3.0  | 17        | 21.79%  |
| 8.01-16.0 | 5         | 6.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 2      | 48        | 61.54%  |
| 1      | 26        | 33.33%  |
| 5      | 2         | 2.56%   |
| 3      | 2         | 2.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 77        | 98.72%  |
| Yes       | 1         | 1.28%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 56        | 71.79%  |
| Yes       | 22        | 28.21%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 98.72%  |
| No        | 1         | 1.28%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 98.72%  |
| No        | 1         | 1.28%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 33        | 42.31%  |
| Russia      | 8         | 10.26%  |
| Germany     | 7         | 8.97%   |
| UK          | 5         | 6.41%   |
| France      | 3         | 3.85%   |
| Canada      | 3         | 3.85%   |
| Brazil      | 3         | 3.85%   |
| Spain       | 2         | 2.56%   |
| Philippines | 2         | 2.56%   |
| Australia   | 2         | 2.56%   |
| Tunisia     | 1         | 1.28%   |
| Poland      | 1         | 1.28%   |
| Japan       | 1         | 1.28%   |
| Israel      | 1         | 1.28%   |
| Indonesia   | 1         | 1.28%   |
| Iceland     | 1         | 1.28%   |
| Hungary     | 1         | 1.28%   |
| Hong Kong   | 1         | 1.28%   |
| Denmark     | 1         | 1.28%   |
| Argentina   | 1         | 1.28%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City               | Computers | Percent |
|--------------------|-----------|---------|
| Moscow             | 4         | 5.13%   |
| Rostov-on-Don      | 2         | 2.56%   |
| Dallas             | 2         | 2.56%   |
| Austin             | 2         | 2.56%   |
| Yuma               | 1         | 1.28%   |
| Wyoming            | 1         | 1.28%   |
| Wiesau             | 1         | 1.28%   |
| Vitória           | 1         | 1.28%   |
| Valencia           | 1         | 1.28%   |
| Tunis              | 1         | 1.28%   |
| Toronto            | 1         | 1.28%   |
| Tel Aviv           | 1         | 1.28%   |
| Sydney             | 1         | 1.28%   |
| St Louis           | 1         | 1.28%   |
| Sparks             | 1         | 1.28%   |
| South Tangerang    | 1         | 1.28%   |
| Somerset           | 1         | 1.28%   |
| Salt Lake City     | 1         | 1.28%   |
| Rochdale           | 1         | 1.28%   |
| Ringe              | 1         | 1.28%   |
| Reykjavik          | 1         | 1.28%   |
| Rangely            | 1         | 1.28%   |
| Perkiomenville     | 1         | 1.28%   |
| Pasadena           | 1         | 1.28%   |
| Paris              | 1         | 1.28%   |
| Pampow             | 1         | 1.28%   |
| Osasco             | 1         | 1.28%   |
| Nuremberg          | 1         | 1.28%   |
| Novosibirsk        | 1         | 1.28%   |
| North Versailles   | 1         | 1.28%   |
| Nashville          | 1         | 1.28%   |
| Munich             | 1         | 1.28%   |
| Mollet del Vallès | 1         | 1.28%   |
| Melbourne          | 1         | 1.28%   |
| Makati City        | 1         | 1.28%   |
| London             | 1         | 1.28%   |
| Livingston         | 1         | 1.28%   |
| Lillebonne         | 1         | 1.28%   |
| Leetonia           | 1         | 1.28%   |
| Las Vegas          | 1         | 1.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Unknown                     | 40        | 40     | 29.2%   |
| Kingston Technology Company | 18        | 18     | 13.14%  |
| Samsung Electronics         | 15        | 15     | 10.95%  |
| Phison Electronics          | 14        | 14     | 10.22%  |
| Sandisk                     | 11        | 11     | 8.03%   |
| Unknown                     | 9         | 9      | 6.57%   |
| O2 Micro                    | 6         | 6      | 4.38%   |
| Silicon Motion              | 4         | 4      | 2.92%   |
| Micron Technology           | 4         | 4      | 2.92%   |
| Seagate                     | 2         | 4      | 1.46%   |
| WDC WDB                     | 1         | 1      | 0.73%   |
| WDC                         | 1         | 1      | 0.73%   |
| Toshiba                     | 1         | 1      | 0.73%   |
| SPCC                        | 1         | 1      | 0.73%   |
| SK hynix                    | 1         | 1      | 0.73%   |
| Realtek Semiconductor       | 1         | 1      | 0.73%   |
| Micron/Crucial Technology   | 1         | 1      | 0.73%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.73%   |
| KIOXIA                      | 1         | 1      | 0.73%   |
| JMicron Technology          | 1         | 1      | 0.73%   |
| Intel                       | 1         | 1      | 0.73%   |
| Hitachi                     | 1         | 1      | 0.73%   |
| Crucial                     | 1         | 1      | 0.73%   |
| A-DATA Technology           | 1         | 1      | 0.73%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown MMC Card  512GB                               | 20        | 14.39%  |
| Kingston Company OM3PDP3 NVMe SSD 512GB               | 18        | 12.95%  |
| Unknown MMC Card  256GB                               | 11        | 7.91%   |
| Phison PS5013 E13 NVMe Controller 256GB               | 11        | 7.91%   |
| Unknown                                               | 9         | 6.47%   |
| O2 Micro E2M2 64GB                                    | 6         | 4.32%   |
| Samsung MZ9LQ512HBLU-00BVL 512GB                      | 4         | 2.88%   |
| Unknown MMC Card  128GB                               | 3         | 2.16%   |
| Sandisk WDC PC SN530 SDBPTPZ-1T00 1024GB              | 3         | 2.16%   |
| Sandisk WD PC SN740 SDDPTQE-2T00 2TB                  | 3         | 2.16%   |
| Samsung MZ9LQ256HBJD-00BVL 256GB                      | 3         | 2.16%   |
| Silicon Motion SPCC M.2 PCIe SSD 1TB                  | 2         | 1.44%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 2         | 1.44%   |
| Sandisk WD PC SN740 SDDPTQD-1T00 1024GB               | 2         | 1.44%   |
| Samsung PM991a NVMe 512GB                             | 2         | 1.44%   |
| Samsung MZ9LQ512HBLU-00B00 512GB                      | 2         | 1.44%   |
| Phison Sabrent SB-2130-1TB                            | 2         | 1.44%   |
| Micron 2400_MTFDKBK2T0QFM 2TB                         | 2         | 1.44%   |
| WDC WDB NCE5000PNC 500GB SSD                          | 1         | 0.72%   |
| WDC WD10 0EMAZ-00WJTA0 10TB                           | 1         | 0.72%   |
| Unknown MMC Card  997GB                               | 1         | 0.72%   |
| Unknown MMC Card  64GB                                | 1         | 0.72%   |
| Unknown MMC Card  393GB                               | 1         | 0.72%   |
| Unknown MMC Card  32GB                                | 1         | 0.72%   |
| Unknown MMC Card  249GB                               | 1         | 0.72%   |
| Unknown MMC Card  16GB                                | 1         | 0.72%   |
| Toshiba HDWD105 500GB                                 | 1         | 0.72%   |
| SPCC Solid State Disk 256GB                           | 1         | 0.72%   |
| SK hynix BC711 NVMe 256GB                             | 1         | 0.72%   |
| Seagate ST500DM002-1BD142 500GB                       | 1         | 0.72%   |
| Seagate ST3500830AS 500GB                             | 1         | 0.72%   |
| Seagate ST2000DM006-2DM164 2TB                        | 1         | 0.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 1         | 0.72%   |
| Sandisk WD CH SN560 SDCPTPD-1T00-1024 930GB           | 1         | 0.72%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                    | 1         | 0.72%   |
| Sandisk PC SN530 NVMe SSD 450GB                       | 1         | 0.72%   |
| Samsung SSD 990 PRO 2TB                               | 1         | 0.72%   |
| Samsung PM991 NVMe 256GB                              | 1         | 0.72%   |
| Samsung MZ9LQ1T0HBLB-00B00 1024GB                     | 1         | 0.72%   |
| Samsung HD502HI 500GB                                 | 1         | 0.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 4      | 33.33%  |
| WDC                 | 1         | 1      | 16.67%  |
| Toshiba             | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| Hitachi             | 1         | 1      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC WDB           | 1         | 1      | 25%     |
| SPCC              | 1         | 1      | 25%     |
| Crucial           | 1         | 1      | 25%     |
| A-DATA Technology | 1         | 1      | 25%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 77        | 77     | 57.46%  |
| MMC     | 49        | 49     | 36.57%  |
| SSD     | 4         | 4      | 2.99%   |
| HDD     | 3         | 8      | 2.24%   |
| Unknown | 1         | 1      | 0.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 77        | 77     | 58.33%  |
| MMC  | 49        | 49     | 37.12%  |
| SAS  | 3         | 4      | 2.27%   |
| SATA | 3         | 9      | 2.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4         | 8      | 50%     |
| 1.01-2.0   | 2         | 2      | 25%     |
| 4.01-10.0  | 1         | 1      | 12.5%   |
| 0.51-1.0   | 1         | 1      | 12.5%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 25        | 32.05%  |
| 101-250        | 17        | 21.79%  |
| 501-1000       | 17        | 21.79%  |
| 1001-2000      | 10        | 12.82%  |
| 51-100         | 6         | 7.69%   |
| More than 3000 | 2         | 2.56%   |
| 2001-3000      | 1         | 1.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 19        | 24.36%  |
| 101-250        | 18        | 23.08%  |
| 501-1000       | 11        | 14.1%   |
| 21-50          | 10        | 12.82%  |
| 1-20           | 8         | 10.26%  |
| 1001-2000      | 7         | 8.97%   |
| 51-100         | 4         | 5.13%   |
| More than 3000 | 1         | 1.28%   |

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
| Detected | 78        | 138    | 98.73%  |
| Works    | 1         | 1      | 1.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Kingston Technology Company | 18        | 21.69%  |
| Samsung Electronics         | 14        | 16.87%  |
| Phison Electronics          | 14        | 16.87%  |
| SanDisk                     | 11        | 13.25%  |
| O2 Micro                    | 6         | 7.23%   |
| Silicon Motion              | 4         | 4.82%   |
| Micron Technology           | 4         | 4.82%   |
| Intel                       | 3         | 3.61%   |
| AMD                         | 3         | 3.61%   |
| SK hynix                    | 1         | 1.2%    |
| Realtek Semiconductor       | 1         | 1.2%    |
| Micron/Crucial Technology   | 1         | 1.2%    |
| MAXIO Technology (Hangzhou) | 1         | 1.2%    |
| Marvell Technology Group    | 1         | 1.2%    |
| KIOXIA                      | 1         | 1.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Kingston Company OM3PDP3 NVMe SSD                                 | 18        | 20.93%  |
| Samsung NVMe SSD Controller 980 (DRAM-less)                       | 13        | 15.12%  |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)               | 11        | 12.79%  |
| O2 Micro FORESEE E2M2 NVMe SSD                                    | 6         | 6.98%   |
| Sandisk PC SN740 NVMe SSD (DRAM-less)                             | 5         | 5.81%   |
| Micron 2400 NVMe SSD (DRAM-less)                                  | 4         | 4.65%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                             | 3         | 3.49%   |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)               | 3         | 3.49%   |
| Silicon Motion SM2269XT (DRAM-less) NVMe SSD Controller           | 2         | 2.33%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers | 2         | 2.33%   |
| AMD FCH SATA Controller [AHCI mode]                               | 2         | 2.33%   |
| AMD 400 Series Chipset SATA Controller                            | 2         | 2.33%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive              | 1         | 1.16%   |
| Sandisk WD CH SN560 NVMe SSD                                      | 1         | 1.16%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                         | 1         | 1.16%   |
| SanDisk PC SN530 NVMe SSD                                         | 1         | 1.16%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                       | 1         | 1.16%   |
| Realtek RTS5762 NVMe SSD Controller                               | 1         | 1.16%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                              | 1         | 1.16%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                      | 1         | 1.16%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller  | 1         | 1.16%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                        | 1         | 1.16%   |
| Intel Volume Management Device NVMe RAID Controller               | 1         | 1.16%   |
| Intel Tiger Lake-LP SATA Controller                               | 1         | 1.16%   |
| Intel SSD 670p Series [Keystone Harbor]                           | 1         | 1.16%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                  | 1         | 1.16%   |
| AMD 500 Series Chipset SATA Controller                            | 1         | 1.16%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 77        | 92.77%  |
| SATA | 5         | 6.02%   |
| RAID | 1         | 1.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 76        | 97.44%  |
| Intel  | 2         | 2.56%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| AMD Custom APU 0405                        | 69        | 88.46%  |
| AMD Ryzen 7 6800U with Radeon Graphics     | 2         | 2.56%   |
| Intel Core i5-6500T CPU @ 2.50GHz          | 1         | 1.28%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz    | 1         | 1.28%   |
| AMD Ryzen 7 7840HS w/ Radeon 780M Graphics | 1         | 1.28%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 1         | 1.28%   |
| AMD Ryzen 5 4500U with Radeon Graphics     | 1         | 1.28%   |
| AMD Ryzen 5 4500 6-Core Processor          | 1         | 1.28%   |
| AMD Ryzen 5 2600X Six-Core Processor       | 1         | 1.28%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model         | Computers | Percent |
|---------------|-----------|---------|
| Other         | 70        | 89.74%  |
| AMD Ryzen 5   | 4         | 5.13%   |
| AMD Ryzen 7   | 3         | 3.85%   |
| Intel Core i5 | 1         | 1.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 71        | 91.03%  |
| 6      | 4         | 5.13%   |
| 8      | 3         | 3.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 78        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 76        | 97.44%  |
| 1      | 2         | 2.56%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 78        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 98.72%  |
| 0x08900201 | 1         | 1.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name      | Computers | Percent |
|-----------|-----------|---------|
| Unknown   | 72        | 92.31%  |
| Zen 2     | 2         | 2.56%   |
| Zen+      | 1         | 1.28%   |
| Zen 3     | 1         | 1.28%   |
| TigerLake | 1         | 1.28%   |
| Skylake   | 1         | 1.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 76        | 95%     |
| Nvidia | 2         | 2.5%    |
| Intel  | 2         | 2.5%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| AMD VanGogh [AMD Custom GPU 0405]                             | 69        | 85.19%  |
| AMD Rembrandt [Radeon 680M]                                   | 2         | 2.47%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]               | 1         | 1.23%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]               | 1         | 1.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                     | 1         | 1.23%   |
| Intel HD Graphics 530                                         | 1         | 1.23%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)] | 1         | 1.23%   |
| AMD Phoenix1                                                  | 1         | 1.23%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT] | 1         | 1.23%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]       | 1         | 1.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]  | 1         | 1.23%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                | 1         | 1.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 74        | 94.87%  |
| 2 x AMD        | 1         | 1.28%   |
| Intel + Nvidia | 1         | 1.28%   |
| 1 x Intel      | 1         | 1.28%   |
| AMD + Nvidia   | 1         | 1.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver | Computers | Percent |
|--------|-----------|---------|
| Free   | 78        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 98.72%  |
| 0.51-1.0   | 1         | 1.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Valve                | 69        | 69%     |
| Goldstar             | 5         | 5%      |
| Samsung Electronics  | 3         | 3%      |
| RTK                  | 2         | 2%      |
| Lenovo               | 2         | 2%      |
| ASUSTek Computer     | 2         | 2%      |
| ViewSonic            | 1         | 1%      |
| Unknown (XXX)        | 1         | 1%      |
| Toshiba              | 1         | 1%      |
| Seiki                | 1         | 1%      |
| Sceptre Tech         | 1         | 1%      |
| Philips              | 1         | 1%      |
| ONN                  | 1         | 1%      |
| LTM                  | 1         | 1%      |
| LG Display           | 1         | 1%      |
| INNOCN               | 1         | 1%      |
| HannStar             | 1         | 1%      |
| Element              | 1         | 1%      |
| Dell                 | 1         | 1%      |
| BOE                  | 1         | 1%      |
| AU Optronics         | 1         | 1%      |
| Ancor Communications | 1         | 1%      |
| Acer                 | 1         | 1%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                     | 69        | 68.32%  |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch           | 1         | 0.99%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch          | 1         | 0.99%   |
| Toshiba TV TSB0032 3840x2160                                            | 1         | 0.99%   |
| Seiki SM28UTR SEK2862 3840x2160 708x398mm 32.0-inch                     | 1         | 0.99%   |
| Sceptre Tech Sceptre Z27 SPT0AB4 3840x2160 575x323mm 26.0-inch          | 1         | 0.99%   |
| Samsung Electronics T24B350 SAM0940 1920x1080 521x293mm 23.5-inch       | 1         | 0.99%   |
| Samsung Electronics S32D850 SAM0BCA 2560x1440 708x398mm 32.0-inch       | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SDC416B 3840x2400 344x215mm 16.0-inch   | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 1872x1053mm 84.6-inch | 1         | 0.99%   |
| RTK TYPE C RTKBC32 2560x1600 347x215mm 16.1-inch                        | 1         | 0.99%   |
| RTK Pi-X1 RTKA2A2 3840x2160 609x355mm 27.8-inch                         | 1         | 0.99%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                 | 1         | 0.99%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                     | 1         | 0.99%   |
| LTM LCD LTM2C02 1920x1080 886x498mm 40.0-inch                           | 1         | 0.99%   |
| LG Display LCD Monitor LGD062F 1920x1080 344x194mm 15.5-inch            | 1         | 0.99%   |
| Lenovo Q27q-10 LEN65F4 2560x1440 597x336mm 27.0-inch                    | 1         | 0.99%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 597x336mm 27.0-inch                | 1         | 0.99%   |
| INNOCN PU15-PRE IOC1501 3840x2160 344x194mm 15.5-inch                   | 1         | 0.99%   |
| HannStar HL161ABB HSD61C7 1366x768 344x193mm 15.5-inch                  | 1         | 0.99%   |
| Goldstar ULTRAGEAR GSM5BB2 1920x1080 527x296mm 23.8-inch                | 1         | 0.99%   |
| Goldstar TV SSCR2 GSM8080 3840x2160                                     | 1         | 0.99%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                  | 1         | 0.99%   |
| Goldstar L1953HR GSM4B42 1280x1024 376x301mm 19.0-inch                  | 1         | 0.99%   |
| Goldstar 32inch FHD GSM76F5 1920x1080 698x392mm 31.5-inch               | 1         | 0.99%   |
| Element ELEFW195 ELE3553 1920x1080 708x398mm 32.0-inch                  | 1         | 0.99%   |
| Dell U2722D DEL422F 2560x1440 597x336mm 27.0-inch                       | 1         | 0.99%   |
| BOE LCD Monitor BOE0B9F 1920x1080 355x200mm 16.0-inch                   | 1         | 0.99%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch          | 1         | 0.99%   |
| ASUSTek Computer VG32V AUS32A3 2560x1440 697x393mm 31.5-inch            | 1         | 0.99%   |
| ASUSTek Computer ROG PG258Q AUS25B1 1920x1080 544x303mm 24.5-inch       | 1         | 0.99%   |
| Ancor Communications VX238 ACI23C1 1920x1080 510x290mm 23.1-inch        | 1         | 0.99%   |
| Acer XF270H B ACR064D 1920x1080 598x336mm 27.0-inch                     | 1         | 0.99%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 800x1280         | 69        | 68.32%  |
| 1920x1080 (FHD)  | 14        | 13.86%  |
| 3840x2160 (4K)   | 9         | 8.91%   |
| 2560x1440 (QHD)  | 5         | 4.95%   |
| 3840x2400        | 1         | 0.99%   |
| 2560x1600        | 1         | 0.99%   |
| 1366x768 (WXGA)  | 1         | 0.99%   |
| 1280x1024 (SXGA) | 1         | 0.99%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 7       | 69        | 68.32%  |
| 27      | 7         | 6.93%   |
| 15      | 4         | 3.96%   |
| 32      | 3         | 2.97%   |
| 31      | 3         | 2.97%   |
| 23      | 3         | 2.97%   |
| 72      | 2         | 1.98%   |
| 24      | 2         | 1.98%   |
| 16      | 2         | 1.98%   |
| 84      | 1         | 0.99%   |
| 54      | 1         | 0.99%   |
| 40      | 1         | 0.99%   |
| 21      | 1         | 0.99%   |
| 19      | 1         | 0.99%   |
| Unknown | 1         | 0.99%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 1-100       | 69        | 69%     |
| 501-600     | 10        | 10%     |
| 301-350     | 5         | 5%      |
| 601-700     | 4         | 4%      |
| 701-800     | 3         | 3%      |
| 1501-2000   | 3         | 3%      |
| 351-400     | 2         | 2%      |
| 801-900     | 1         | 1%      |
| 401-500     | 1         | 1%      |
| 1001-1500   | 1         | 1%      |
| Unknown     | 1         | 1%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 0.67  | 69        | 69.7%   |
| 16/9  | 28        | 28.28%  |
| 5/4   | 1         | 1.01%   |
| 16/10 | 1         | 1.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 1-40           | 69        | 68.32%  |
| 301-350        | 7         | 6.93%   |
| 351-500        | 6         | 5.94%   |
| 201-250        | 5         | 4.95%   |
| 101-110        | 5         | 4.95%   |
| More than 1000 | 4         | 3.96%   |
| 251-300        | 1         | 0.99%   |
| 151-200        | 1         | 0.99%   |
| 111-120        | 1         | 0.99%   |
| 501-1000       | 1         | 0.99%   |
| Unknown        | 1         | 0.99%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 161-240       | 69        | 69.7%   |
| 51-100        | 17        | 17.17%  |
| 121-160       | 5         | 5.05%   |
| 101-120       | 5         | 5.05%   |
| More than 240 | 2         | 2.02%   |
| Unknown       | 1         | 1.01%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 56        | 71.79%  |
| 2     | 21        | 26.92%  |
| 3     | 1         | 1.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 73        | 78.49%  |
| ASIX Electronics      | 9         | 9.68%   |
| Intel                 | 6         | 6.45%   |
| MediaTek              | 3         | 3.23%   |
| Lenovo                | 1         | 1.08%   |
| DisplayLink           | 1         | 1.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 70        | 69.31%  |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 8.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 3.96%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 2.97%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 1.98%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.98%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.99%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.99%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                | 1         | 0.99%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 0.99%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 0.99%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.99%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 0.99%   |
| DisplayLink Plugable UD-3900                                      | 1         | 0.99%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 70        | 89.74%  |
| Intel                 | 5         | 6.41%   |
| MediaTek              | 3         | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 70        | 89.74%  |
| Intel Wi-Fi 6 AX200                                           | 2         | 2.56%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1         | 1.28%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 1.28%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter            | 1         | 1.28%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 1         | 1.28%   |
| Intel Wi-Fi 6 AX201                                           | 1         | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 1         | 1.28%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 10        | 43.48%  |
| ASIX Electronics      | 9         | 39.13%  |
| Intel                 | 2         | 8.7%    |
| Lenovo                | 1         | 4.35%   |
| DisplayLink           | 1         | 4.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 39.13%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 17.39%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 13.04%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 8.7%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 4.35%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 4.35%   |
| Intel I211 Gigabit Network Connection                             | 1         | 4.35%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 4.35%   |
| DisplayLink Plugable UD-3900                                      | 1         | 4.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 77        | 77.78%  |
| Ethernet | 22        | 22.22%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 74        | 94.87%  |
| Ethernet | 4         | 5.13%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 73        | 93.59%  |
| 2     | 5         | 6.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 47        | 60.26%  |
| Yes  | 31        | 39.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| IMC Networks          | 70        | 90.91%  |
| Intel                 | 5         | 6.49%   |
| Realtek Semiconductor | 1         | 1.3%    |
| Foxconn / Hon Hai     | 1         | 1.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| IMC Networks Bluetooth Radio      | 69        | 89.61%  |
| Intel AX200 Bluetooth             | 2         | 2.6%    |
| Realtek Bluetooth Radio           | 1         | 1.3%    |
| Intel Wireless-AC 3168 Bluetooth  | 1         | 1.3%    |
| Intel AX210 Bluetooth             | 1         | 1.3%    |
| Intel AX201 Bluetooth             | 1         | 1.3%    |
| IMC Networks Wireless_Device      | 1         | 1.3%    |
| Foxconn / Hon Hai Wireless_Device | 1         | 1.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| AMD            | 76        | 89.41%  |
| Nvidia         | 2         | 2.35%   |
| Intel          | 2         | 2.35%   |
| MVSILICON.INC. | 1         | 1.18%   |
| Logitech       | 1         | 1.18%   |
| Lenovo         | 1         | 1.18%   |
| Corsair        | 1         | 1.18%   |
| Astro Gaming   | 1         | 1.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| AMD Rembrandt Radeon High Definition Audio Controller          | 72        | 76.6%   |
| AMD Family 17h/19h HD Audio Controller                         | 6         | 6.38%   |
| AMD Renoir Radeon High Definition Audio Controller             | 3         | 3.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller | 1         | 1.06%   |
| Nvidia Audio device                                            | 1         | 1.06%   |
| MVSILICON.INC. MV USB AUDIO                                    | 1         | 1.06%   |
| Logitech Zone 900 Receiver                                     | 1         | 1.06%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                      | 1         | 1.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller    | 1         | 1.06%   |
| Intel 200 Series PCH HD Audio                                  | 1         | 1.06%   |
| Corsair VOID PRO Wireless Gaming Headset                       | 1         | 1.06%   |
| Astro Gaming A50                                               | 1         | 1.06%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                        | 1         | 1.06%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller            | 1         | 1.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]     | 1         | 1.06%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]   | 1         | 1.06%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM K3LK7K70BM-BGCP000 4GB SODIMM LPDDR5 4266MT/s | 1         | 100%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind   | Computers | Percent |
|--------|-----------|---------|
| LPDDR5 | 1         | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 1         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size | Computers | Percent |
|------|-----------|---------|
| 4096 | 1         | 100%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 4266  | 1         | 100%    |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)

![Camera Vendor](./All/images/line_chart/camera_vendor.svg)

| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung Electronics                    | 1         | 20%     |
| Quanta                                 | 1         | 20%     |
| Luxvisions Innotech Limited            | 1         | 20%     |
| Chicony Electronics                    | 1         | 20%     |
| Cheng Uei Precision Industry (Foxlink) | 1         | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung Galaxy series, misc. (MTP mode)                         | 1         | 20%     |
| Quanta Acer FHD User Facing                                     | 1         | 20%     |
| Luxvisions Innotech Limited HP True Vision FHD Camera           | 1         | 20%     |
| Chicony HD User Facing                                          | 1         | 20%     |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 20%     |

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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 76        | 97.44%  |
| 1     | 2         | 2.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type          | Computers | Percent |
|---------------|-----------|---------|
| Graphics card | 1         | 50%     |
| Card reader   | 1         | 50%     |

