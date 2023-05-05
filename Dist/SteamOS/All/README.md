SteamOS - Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/SteamOS/Desktop/README.md) and [notebooks](/Dist/SteamOS/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: Apr, 2023.

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

| Name          | Computers | Percent |
|---------------|-----------|---------|
| SteamOS 3.4.6 | 57        | 82.61%  |
| SteamOS 3.4   | 5         | 7.25%   |
| SteamOS 4     | 3         | 4.35%   |
| SteamOS 3.5   | 2         | 2.9%    |
| SteamOS       | 2         | 2.9%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| SteamOS | 69        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version                                | Computers | Percent |
|----------------------------------------|-----------|---------|
| 5.13.0-valve36-1-neptune               | 57        | 82.61%  |
| 6.1.21-valve1-1-neptune-61             | 4         | 5.8%    |
| 5.13.0-valve21.3-1-neptune             | 3         | 4.35%   |
| 5.15.93-1-lts                          | 2         | 2.9%    |
| 6.1.21-valve1-2-neptune-61             | 1         | 1.45%   |
| 5.18.1-arch1_testHoloISO_20220606.1811 | 1         | 1.45%   |
| 5.13.0-valve37-1-neptune               | 1         | 1.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.0  | 61        | 88.41%  |
| 6.1.21  | 5         | 7.25%   |
| 5.15.93 | 2         | 2.9%    |
| 5.18.1  | 1         | 1.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13    | 61        | 88.41%  |
| 6.1     | 5         | 7.25%   |
| 5.15    | 2         | 2.9%    |
| 5.18    | 1         | 1.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 69        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name      | Computers | Percent |
|-----------|-----------|---------|
| KDE5      | 66        | 95.65%  |
| Unknown   | 2         | 2.9%    |
| gamescope | 1         | 1.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 69        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 69        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 62        | 89.86%  |
| de_DE | 2         | 2.9%    |
| ru_RU | 1         | 1.45%   |
| pl_PL | 1         | 1.45%   |
| es_ES | 1         | 1.45%   |
| ba_RU | 1         | 1.45%   |
| an_ES | 1         | 1.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 67        | 97.1%   |
| EFI  | 2         | 2.9%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 68        | 98.55%  |
| Tmpfs | 1         | 1.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 67        | 97.1%   |
| GPT     | 2         | 2.9%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 67        | 97.1%   |
| Yes       | 2         | 2.9%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 69        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Valve               | 59        | 85.51%  |
| ASUSTek Computer    | 4         | 5.8%    |
| Gigabyte Technology | 2         | 2.9%    |
| Lenovo              | 1         | 1.45%   |
| Hewlett-Packard     | 1         | 1.45%   |
| Dell                | 1         | 1.45%   |
| Unknown             | 1         | 1.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Valve Jupiter                             | 59        | 85.51%  |
| Lenovo Legion 5 17IMH05H 81Y8             | 1         | 1.45%   |
| HP Victus by 15L Gaming Desktop TG02-0xxx | 1         | 1.45%   |
| Gigabyte Z97X-UD5H                        | 1         | 1.45%   |
| Gigabyte H77N-WIFI                        | 1         | 1.45%   |
| Dell Venue 11 Pro 7130 vPro               | 1         | 1.45%   |
| ASUS ZenBook UX435EG_UX435EG              | 1         | 1.45%   |
| ASUS TUF B365M-PLUS GAMING                | 1         | 1.45%   |
| ASUS P8H61-M LX3 PLUS R2.0                | 1         | 1.45%   |
| ASUS All Series                           | 1         | 1.45%   |
| Unknown                                   | 1         | 1.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Valve Jupiter      | 59        | 85.51%  |
| Lenovo Legion      | 1         | 1.45%   |
| HP Victus          | 1         | 1.45%   |
| Gigabyte Z97X-UD5H | 1         | 1.45%   |
| Gigabyte H77N-WIFI | 1         | 1.45%   |
| Dell Venue         | 1         | 1.45%   |
| ASUS ZenBook       | 1         | 1.45%   |
| ASUS TUF           | 1         | 1.45%   |
| ASUS P8H61-M       | 1         | 1.45%   |
| ASUS All           | 1         | 1.45%   |
| Unknown            | 1         | 1.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 57        | 82.61%  |
| 2023 | 4         | 5.8%    |
| 2014 | 2         | 2.9%    |
| 2012 | 2         | 2.9%    |
| 2021 | 1         | 1.45%   |
| 2020 | 1         | 1.45%   |
| 2019 | 1         | 1.45%   |
| 2015 | 1         | 1.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 62        | 89.86%  |
| Desktop  | 6         | 8.7%    |
| Mini pc  | 1         | 1.45%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 69        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 69        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 59        | 85.51%  |
| 16.01-24.0 | 5         | 7.25%   |
| 32.01-64.0 | 3         | 4.35%   |
| 4.01-8.0   | 1         | 1.45%   |
| 3.01-4.0   | 1         | 1.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 28        | 40.58%  |
| 3.01-4.0  | 24        | 34.78%  |
| 4.01-8.0  | 12        | 17.39%  |
| 8.01-16.0 | 3         | 4.35%   |
| 1.01-2.0  | 2         | 2.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 2      | 39        | 56.52%  |
| 1      | 29        | 42.03%  |
| 3      | 1         | 1.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 66        | 95.65%  |
| Yes       | 3         | 4.35%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 60.87%  |
| Yes       | 27        | 39.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 95.65%  |
| No        | 3         | 4.35%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 97.1%   |
| No        | 2         | 2.9%    |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 24        | 34.78%  |
| Germany      | 7         | 10.14%  |
| France       | 4         | 5.8%    |
| Spain        | 3         | 4.35%   |
| Russia       | 3         | 4.35%   |
| Austria      | 3         | 4.35%   |
| UK           | 2         | 2.9%    |
| Taiwan       | 2         | 2.9%    |
| Poland       | 2         | 2.9%    |
| Israel       | 2         | 2.9%    |
| India        | 2         | 2.9%    |
| Uzbekistan   | 1         | 1.45%   |
| UAE          | 1         | 1.45%   |
| Turkey       | 1         | 1.45%   |
| Switzerland  | 1         | 1.45%   |
| Saudi Arabia | 1         | 1.45%   |
| Philippines  | 1         | 1.45%   |
| Peru         | 1         | 1.45%   |
| Netherlands  | 1         | 1.45%   |
| Mexico       | 1         | 1.45%   |
| Indonesia    | 1         | 1.45%   |
| Czechia      | 1         | 1.45%   |
| Canada       | 1         | 1.45%   |
| Bulgaria     | 1         | 1.45%   |
| Brazil       | 1         | 1.45%   |
| Australia    | 1         | 1.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Moscow                 | 3         | 4.35%   |
| Taipei                 | 2         | 2.9%    |
| Zaragoza               | 1         | 1.45%   |
| Wausau                 | 1         | 1.45%   |
| Warsaw                 | 1         | 1.45%   |
| Virginia Beach         | 1         | 1.45%   |
| Vienna                 | 1         | 1.45%   |
| Valencia               | 1         | 1.45%   |
| Urvillers              | 1         | 1.45%   |
| Tashkent               | 1         | 1.45%   |
| Sydney                 | 1         | 1.45%   |
| Star City              | 1         | 1.45%   |
| Somerset               | 1         | 1.45%   |
| Saint Albans           | 1         | 1.45%   |
| Rousse                 | 1         | 1.45%   |
| Rosedale               | 1         | 1.45%   |
| Rancho Santa Margarita | 1         | 1.45%   |
| Quezon City            | 1         | 1.45%   |
| Quedlinburg            | 1         | 1.45%   |
| Puebla City            | 1         | 1.45%   |
| Prague                 | 1         | 1.45%   |
| Petah Tikva            | 1         | 1.45%   |
| Oignies                | 1         | 1.45%   |
| Ocean Springs          | 1         | 1.45%   |
| Nova Iguaçu           | 1         | 1.45%   |
| Noida                  | 1         | 1.45%   |
| Newport                | 1         | 1.45%   |
| Netanya                | 1         | 1.45%   |
| Minneapolis            | 1         | 1.45%   |
| Medina                 | 1         | 1.45%   |
| Marseille              | 1         | 1.45%   |
| Makassar               | 1         | 1.45%   |
| Madrid                 | 1         | 1.45%   |
| Lynnwood               | 1         | 1.45%   |
| Lübeck                | 1         | 1.45%   |
| Loganville             | 1         | 1.45%   |
| Livingston             | 1         | 1.45%   |
| Liberty Lake           | 1         | 1.45%   |
| Lausen                 | 1         | 1.45%   |
| Lakeland               | 1         | 1.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Unknown                     | 28        | 28     | 25.23%  |
| Samsung Electronics         | 17        | 17     | 15.32%  |
| Phison Electronics          | 12        | 12     | 10.81%  |
| Kingston Technology Company | 12        | 12     | 10.81%  |
| O2 Micro                    | 9         | 9      | 8.11%   |
| Unknown                     | 9         | 9      | 8.11%   |
| Sandisk                     | 6         | 6      | 5.41%   |
| Silicon Motion              | 4         | 4      | 3.6%    |
| WDC                         | 3         | 3      | 2.7%    |
| KIOXIA                      | 3         | 3      | 2.7%    |
| Intel                       | 2         | 2      | 1.8%    |
| Toshiba                     | 1         | 1      | 0.9%    |
| SK hynix                    | 1         | 1      | 0.9%    |
| Seagate                     | 1         | 1      | 0.9%    |
| Kingchuxing                 | 1         | 2      | 0.9%    |
| Hitachi                     | 1         | 1      | 0.9%    |
| Crucial                     | 1         | 1      | 0.9%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Unknown MMC Card  512GB                                | 16        | 14.29%  |
| Phison PS5013 E13 NVMe Controller 500GB                | 11        | 9.82%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB                | 11        | 9.82%   |
| O2 Micro E2M2 64GB                                     | 9         | 8.04%   |
| Unknown                                                | 9         | 8.04%   |
| Samsung MZ9LQ256HBJD-00BVL 256GB                       | 8         | 7.14%   |
| Unknown MMC Card  256GB                                | 5         | 4.46%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 1024GB | 4         | 3.57%   |
| Samsung MZ9LQ512HBLU-00BVL 512GB                       | 4         | 3.57%   |
| Unknown MMC Card  128GB                                | 3         | 2.68%   |
| Sandisk WD PC SN740 SDDPTQD-1T00 1024GB                | 3         | 2.68%   |
| Unknown MMC Card  393GB                                | 2         | 1.79%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                       | 1         | 0.89%   |
| WDC WD4005FZBX-00K5WB0 4TB                             | 1         | 0.89%   |
| WDC WD1003FZEX-00K3CA0 1TB                             | 1         | 0.89%   |
| Unknown MMC Card  64GB                                 | 1         | 0.89%   |
| Unknown MMC Card  498GB                                | 1         | 0.89%   |
| Toshiba DT01ACA100 1TB                                 | 1         | 0.89%   |
| SK hynix BC711 NVMe 512GB                              | 1         | 0.89%   |
| Seagate ST1000DM010-2EP102 1TB                         | 1         | 0.89%   |
| Sandisk WDC PC SN530 SDBPTPZ-1T00 1TB                  | 1         | 0.89%   |
| Sandisk WD Green SN350 1TB                             | 1         | 0.89%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB       | 1         | 0.89%   |
| Samsung SSD 870 EVO 4TB                                | 1         | 0.89%   |
| Samsung SSD 840 EVO 250GB                              | 1         | 0.89%   |
| Samsung PM991a NVMe 512GB                              | 1         | 0.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB      | 1         | 0.89%   |
| Samsung MZ9LQ1T0HBLB-00B00 1024GB                      | 1         | 0.89%   |
| Phison Sabrent SB-2130-1TB                             | 1         | 0.89%   |
| KIOXIA KBG50ZNS512G 512GB                              | 1         | 0.89%   |
| KIOXIA KBG50ZNS1T02 NVMe 1024GB                        | 1         | 0.89%   |
| KIOXIA KBG50ZNS1T02 1024GB                             | 1         | 0.89%   |
| Kingston Company SNV2S2000G 2TB                        | 1         | 0.89%   |
| Kingchuxing SSD 256GB                                  | 1         | 0.89%   |
| Kingchuxing 256GB                                      | 1         | 0.89%   |
| Intel SSDPEKNU512GZH 512GB                             | 1         | 0.89%   |
| Intel SSD 660P Series 512GB                            | 1         | 0.89%   |
| Hitachi HDT721016SLA380 160GB                          | 1         | 0.89%   |
| Crucial CT500BX500SSD1 500GB                           | 1         | 0.89%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 40%     |
| Toshiba | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |
| Hitachi | 1         | 1      | 20%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 40%     |
| WDC                 | 1         | 1      | 20%     |
| Kingchuxing         | 1         | 1      | 20%     |
| Crucial             | 1         | 1      | 20%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 64        | 64     | 57.66%  |
| MMC     | 37        | 37     | 33.33%  |
| SSD     | 5         | 5      | 4.5%    |
| HDD     | 4         | 5      | 3.6%    |
| Unknown | 1         | 1      | 0.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 64        | 64     | 58.72%  |
| MMC  | 37        | 37     | 33.94%  |
| SATA | 8         | 11     | 7.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 5         | 5      | 55.56%  |
| 3.01-4.0   | 2         | 2      | 22.22%  |
| 0.51-1.0   | 2         | 3      | 22.22%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 23        | 33.33%  |
| 251-500        | 21        | 30.43%  |
| 501-1000       | 12        | 17.39%  |
| 51-100         | 8         | 11.59%  |
| 1001-2000      | 3         | 4.35%   |
| More than 3000 | 2         | 2.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 101-250   | 19        | 27.54%  |
| 251-500   | 18        | 26.09%  |
| 51-100    | 11        | 15.94%  |
| 21-50     | 8         | 11.59%  |
| 501-1000  | 6         | 8.7%    |
| 1-20      | 5         | 7.25%   |
| 2001-3000 | 1         | 1.45%   |
| 1001-2000 | 1         | 1.45%   |

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
| Detected | 70        | 109    | 95.89%  |
| Works    | 3         | 3      | 4.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Samsung Electronics         | 15        | 20.27%  |
| Phison Electronics          | 12        | 16.22%  |
| Kingston Technology Company | 12        | 16.22%  |
| O2 Micro                    | 9         | 12.16%  |
| Intel                       | 9         | 12.16%  |
| SanDisk                     | 6         | 8.11%   |
| Silicon Motion              | 4         | 5.41%   |
| KIOXIA                      | 3         | 4.05%   |
| AMD                         | 2         | 2.7%    |
| SK hynix                    | 1         | 1.35%   |
| Marvell Technology Group    | 1         | 1.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller 980                                                         | 14        | 18.18%  |
| Phison PS5013 E13 NVMe Controller                                                       | 11        | 14.29%  |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 11        | 14.29%  |
| O2 Micro Non-Volatile memory controller                                                 | 9         | 11.69%  |
| SanDisk Non-Volatile memory controller                                                  | 5         | 6.49%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4         | 5.19%   |
| KIOXIA Non-Volatile memory controller                                                   | 3         | 3.9%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 2         | 2.6%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 1         | 1.3%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 1.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 1.3%    |
| Phison Electronics Non-Volatile memory controller                                       | 1         | 1.3%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1         | 1.3%    |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 1.3%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 1         | 1.3%    |
| Intel SSD 660P Series                                                                   | 1         | 1.3%    |
| Intel Non-Volatile memory controller                                                    | 1         | 1.3%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1         | 1.3%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 1.3%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1         | 1.3%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.3%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1         | 1.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 1.3%    |
| AMD 400 Series Chipset SATA Controller                                                  | 1         | 1.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 64        | 86.49%  |
| SATA | 8         | 10.81%  |
| RAID | 1         | 1.35%   |
| IDE  | 1         | 1.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 61        | 88.41%  |
| Intel  | 8         | 11.59%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Custom APU 0405                     | 59        | 85.51%  |
| Intel Core i7-5820K CPU @ 3.30GHz       | 1         | 1.45%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 1         | 1.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 1         | 1.45%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.45%   |
| Intel Core i5-4300Y CPU @ 1.60GHz       | 1         | 1.45%   |
| Intel Core i3-9100F CPU @ 3.60GHz       | 1         | 1.45%   |
| Intel Celeron CPU G1620 @ 2.70GHz       | 1         | 1.45%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 1         | 1.45%   |
| AMD Ryzen 5 5600U with Radeon Graphics  | 1         | 1.45%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 1         | 1.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model         | Computers | Percent |
|---------------|-----------|---------|
| Other         | 60        | 86.96%  |
| Intel Core i7 | 4         | 5.8%    |
| AMD Ryzen 5   | 2         | 2.9%    |
| Intel Core i5 | 1         | 1.45%   |
| Intel Core i3 | 1         | 1.45%   |
| Intel Celeron | 1         | 1.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 63        | 91.3%   |
| 6      | 4         | 5.8%    |
| 2      | 2         | 2.9%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 69        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 67        | 97.1%   |
| 1      | 2         | 2.9%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 69        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 95.65%  |
| 0x08900201 | 2         | 2.9%    |
| 0x40651    | 1         | 1.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name      | Computers | Percent |
|-----------|-----------|---------|
| Unknown   | 59        | 85.51%  |
| Haswell   | 3         | 4.35%   |
| Zen 3     | 2         | 2.9%    |
| IvyBridge | 2         | 2.9%    |
| TigerLake | 1         | 1.45%   |
| KabyLake  | 1         | 1.45%   |
| CometLake | 1         | 1.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 64        | 88.89%  |
| Intel  | 5         | 6.94%   |
| Nvidia | 3         | 4.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD VanGogh [AMD Custom GPU 0405]                                           | 59        | 80.82%  |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 2.74%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2         | 2.74%   |
| Nvidia TU117M [GeForce MX450]                                               | 1         | 1.37%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 1.37%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1         | 1.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 1.37%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 1.37%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 1         | 1.37%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]              | 1         | 1.37%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 1         | 1.37%   |
| AMD Tonga XT / Amethyst XT [Radeon R9 380X / R9 M295X]                      | 1         | 1.37%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 1         | 1.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 62        | 89.86%  |
| Intel + Nvidia | 2         | 2.9%    |
| 1 x Intel      | 2         | 2.9%    |
| 2 x AMD        | 1         | 1.45%   |
| 1 x Nvidia     | 1         | 1.45%   |
| Intel + AMD    | 1         | 1.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver | Computers | Percent |
|--------|-----------|---------|
| Free   | 69        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 97.1%   |
| 3.01-4.0   | 2         | 2.9%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Valve               | 58        | 70.73%  |
| Samsung Electronics | 4         | 4.88%   |
| Sceptre Tech        | 2         | 2.44%   |
| Philips             | 2         | 2.44%   |
| Goldstar            | 2         | 2.44%   |
| Dell                | 2         | 2.44%   |
| ASUSTek Computer    | 2         | 2.44%   |
| Toshiba             | 1         | 1.22%   |
| Sony                | 1         | 1.22%   |
| RTD                 | 1         | 1.22%   |
| Panasonic           | 1         | 1.22%   |
| ONN                 | 1         | 1.22%   |
| Mi                  | 1         | 1.22%   |
| BOE                 | 1         | 1.22%   |
| AU Optronics        | 1         | 1.22%   |
| AOC                 | 1         | 1.22%   |
| Acer                | 1         | 1.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 58        | 70.73%  |
| Toshiba ScreenXpert TSB8888 1080x2160                                 | 1         | 1.22%   |
| Sony TV *02 SNY9403 1920x1080 1218x685mm 55.0-inch                    | 1         | 1.22%   |
| Sceptre Tech Sceptre Z27 SPT6B0B 3840x2160 597x336mm 27.0-inch        | 1         | 1.22%   |
| Sceptre Tech Sceptre T24 SPT09AB 1920x1080 520x320mm 24.0-inch        | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SAM7269 3840x2160 700x390mm 31.5-inch | 1         | 1.22%   |
| Samsung Electronics C49RG9x SAM0F99 3840x1080 1193x336mm 48.8-inch    | 1         | 1.22%   |
| Samsung Electronics C27R500 SAM0F9D 1920x1080 598x336mm 27.0-inch     | 1         | 1.22%   |
| RTD Display RTD0002 2560x1600 344x215mm 16.0-inch                     | 1         | 1.22%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 1         | 1.22%   |
| Philips FTV PHL04C3 1920x1080 1440x810mm 65.0-inch                    | 1         | 1.22%   |
| Panasonic TV MEIA0A6 1920x1080 698x392mm 31.5-inch                    | 1         | 1.22%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 1         | 1.22%   |
| Mi Monitor XMI2701 2560x1440 597x336mm 27.0-inch                      | 1         | 1.22%   |
| Goldstar TV SSCR2 GSM8080 3840x2160                                   | 1         | 1.22%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 1.22%   |
| Dell U2410 DELF016 1920x1200 518x324mm 24.1-inch                      | 1         | 1.22%   |
| Dell S2721HGF DEL41E8 1920x1080 600x340mm 27.2-inch                   | 1         | 1.22%   |
| BOE LCD Monitor BOE0976 1920x1080 309x174mm 14.0-inch                 | 1         | 1.22%   |
| AU Optronics LCD Monitor AUO439D 1920x1080 382x215mm 17.3-inch        | 1         | 1.22%   |
| ASUSTek Computer VG289Q1A AUS28CA 3840x2160 621x341mm 27.9-inch       | 1         | 1.22%   |
| ASUSTek Computer MB16AMT AUS1661 1920x1080 344x194mm 15.5-inch        | 1         | 1.22%   |
| AOC 24P2W1DG5 AOC2402 1920x1080 527x296mm 23.8-inch                   | 1         | 1.22%   |
| Acer GN246HL ACR02FA 1920x1080 531x299mm 24.0-inch                    | 1         | 1.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 800x1280          | 58        | 71.6%   |
| 1920x1080 (FHD)   | 11        | 13.58%  |
| 3840x2160 (4K)    | 6         | 7.41%   |
| 3840x1080         | 1         | 1.23%   |
| 2560x1600         | 1         | 1.23%   |
| 2560x1440 (QHD)   | 1         | 1.23%   |
| 1920x1200 (WUXGA) | 1         | 1.23%   |
| 1366x768 (WXGA)   | 1         | 1.23%   |
| 1280x1024 (SXGA)  | 1         | 1.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 7      | 58        | 71.6%   |
| 27     | 4         | 4.94%   |
| 31     | 3         | 3.7%    |
| 24     | 2         | 2.47%   |
| 18     | 2         | 2.47%   |
| 72     | 1         | 1.23%   |
| 65     | 1         | 1.23%   |
| 55     | 1         | 1.23%   |
| 48     | 1         | 1.23%   |
| 32     | 1         | 1.23%   |
| 26     | 1         | 1.23%   |
| 23     | 1         | 1.23%   |
| 21     | 1         | 1.23%   |
| 17     | 1         | 1.23%   |
| 16     | 1         | 1.23%   |
| 15     | 1         | 1.23%   |
| 14     | 1         | 1.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 1-100       | 58        | 71.6%   |
| 501-600     | 6         | 7.41%   |
| 601-700     | 5         | 6.17%   |
| 401-500     | 3         | 3.7%    |
| 301-350     | 3         | 3.7%    |
| 1001-1500   | 3         | 3.7%    |
| 701-800     | 1         | 1.23%   |
| 351-400     | 1         | 1.23%   |
| 1501-2000   | 1         | 1.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 0.67  | 58        | 71.6%   |
| 16/9  | 18        | 22.22%  |
| 16/10 | 2         | 2.47%   |
| 4/3   | 1         | 1.23%   |
| 32/9  | 1         | 1.23%   |
| 2.12  | 1         | 1.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 1-40           | 58        | 71.6%   |
| 351-500        | 4         | 4.94%   |
| 301-350        | 4         | 4.94%   |
| More than 1000 | 3         | 3.7%    |
| 201-250        | 3         | 3.7%    |
| 251-300        | 2         | 2.47%   |
| 141-150        | 2         | 2.47%   |
| 81-90          | 1         | 1.23%   |
| 121-130        | 1         | 1.23%   |
| 111-120        | 1         | 1.23%   |
| 101-110        | 1         | 1.23%   |
| 501-1000       | 1         | 1.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 161-240 | 58        | 73.42%  |
| 51-100  | 11        | 13.92%  |
| 121-160 | 5         | 6.33%   |
| 101-120 | 3         | 3.8%    |
| 1-50    | 2         | 2.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 55        | 79.71%  |
| 2     | 13        | 18.84%  |
| 3     | 1         | 1.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 65        | 78.31%  |
| ASIX Electronics      | 8         | 9.64%   |
| Intel                 | 7         | 8.43%   |
| Raspberry Pi          | 1         | 1.2%    |
| Qualcomm Atheros      | 1         | 1.2%    |
| Broadcom              | 1         | 1.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 60        | 63.16%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 11.58%  |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 7.37%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 5.26%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1         | 1.05%   |
| Raspberry Pi Pico                                                 | 1         | 1.05%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.05%   |
| Intel Wireless 7265                                               | 1         | 1.05%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.05%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.05%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.05%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.05%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 1.05%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.05%   |
| ASIX AX88772B                                                     | 1         | 1.05%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 61        | 92.42%  |
| Intel                 | 4         | 6.06%   |
| Broadcom              | 1         | 1.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter    | 60        | 90.91%  |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller | 1         | 1.52%   |
| Intel Wireless 7265                                         | 1         | 1.52%   |
| Intel Wi-Fi 6 AX201                                         | 1         | 1.52%   |
| Intel Comet Lake PCH CNVi WiFi                              | 1         | 1.52%   |
| Intel Centrino Wireless-N 2230                              | 1         | 1.52%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter          | 1         | 1.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 16        | 57.14%  |
| ASIX Electronics      | 8         | 28.57%  |
| Intel                 | 3         | 10.71%  |
| Qualcomm Atheros      | 1         | 3.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 39.29%  |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 25%     |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 17.86%  |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 3.57%   |
| Intel Ethernet Connection I217-V                                  | 1         | 3.57%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 3.57%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 3.57%   |
| ASIX AX88772B                                                     | 1         | 3.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 66        | 70.21%  |
| Ethernet | 27        | 28.72%  |
| Modem    | 1         | 1.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 59        | 81.94%  |
| Ethernet | 13        | 18.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 64        | 92.75%  |
| 2     | 3         | 4.35%   |
| 3     | 2         | 2.9%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 43        | 62.32%  |
| Yes  | 26        | 37.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| IMC Networks            | 59        | 88.06%  |
| Intel                   | 4         | 5.97%   |
| Realtek Semiconductor   | 2         | 2.99%   |
| Cambridge Silicon Radio | 1         | 1.49%   |
| Apple                   | 1         | 1.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Bluetooth Radio                        | 59        | 88.06%  |
| Realtek Bluetooth Radio                             | 2         | 2.99%   |
| Intel AX201 Bluetooth                               | 2         | 2.99%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.49%   |
| Intel Bluetooth wireless interface                  | 1         | 1.49%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.49%   |
| Apple Bluetooth Host Controller                     | 1         | 1.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| AMD                      | 64        | 76.19%  |
| Intel                    | 8         | 9.52%   |
| Nvidia                   | 2         | 2.38%   |
| Generalplus Technology   | 2         | 2.38%   |
| C-Media Electronics      | 2         | 2.38%   |
| Sony                     | 1         | 1.19%   |
| Silicon Motion           | 1         | 1.19%   |
| Nordic Semiconductor ASA | 1         | 1.19%   |
| Logitech                 | 1         | 1.19%   |
| Hewlett-Packard          | 1         | 1.19%   |
| Focusrite-Novation       | 1         | 1.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Rembrandt Radeon High Definition Audio Controller                      | 59        | 66.29%  |
| Generalplus Technology USB Audio Device                                    | 2         | 2.25%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 2.25%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 2.25%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 2.25%   |
| Sony DualSense wireless controller (PS5)                                   | 1         | 1.12%   |
| Silicon Motion SMI USB Display                                             | 1         | 1.12%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.12%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.12%   |
| Nordic Semiconductor ASA USB Composite Device                              | 1         | 1.12%   |
| Logitech G935 Gaming Headset                                               | 1         | 1.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.12%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.12%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.12%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.12%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 1.12%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1         | 1.12%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.12%   |
| Intel 200 Series PCH HD Audio                                              | 1         | 1.12%   |
| Hewlett-Packard USB Audio                                                  | 1         | 1.12%   |
| Focusrite-Novation XStation                                                | 1         | 1.12%   |
| C-Media Electronics YOWU-SELKIRK-3G                                        | 1         | 1.12%   |
| C-Media Electronics USB Audio Device                                       | 1         | 1.12%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 1         | 1.12%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1         | 1.12%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 2         | 66.67%  |
| Samsung Electronics | 1         | 33.33%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM K3LK7K70BM-BGCP000 4GB SODIMM LPDDR5 4266MT/s  | 1         | 33.33%  |
| Micron RAM MT62F1G32D4DR-031 WT 4GB SODIMM LPDDR5 6400MT/s | 1         | 33.33%  |
| Micron RAM Module 2GB SODIMM DDR3 1600MT/s                 | 1         | 33.33%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind   | Computers | Percent |
|--------|-----------|---------|
| LPDDR5 | 2         | 66.67%  |
| DDR3   | 1         | 33.33%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 3         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size | Computers | Percent |
|------|-----------|---------|
| 4096 | 2         | 66.67%  |
| 2048 | 1         | 33.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 6400  | 1         | 33.33%  |
| 4266  | 1         | 33.33%  |
| 1600  | 1         | 33.33%  |

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

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 3         | 42.86%  |
| Razer USA                | 1         | 14.29%  |
| IMC Networks             | 1         | 14.29%  |
| Chicony Electronics      | 1         | 14.29%  |
| Alpha Imaging Technology | 1         | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Realtek Integrated Webcam          | 1         | 14.29%  |
| Realtek Full HD webcam             | 1         | 14.29%  |
| Realtek FULL HD WEB CAM            | 1         | 14.29%  |
| Razer USA Razer Kiyo X             | 1         | 14.29%  |
| IMC Networks USB2.0 HD UVC WebCam  | 1         | 14.29%  |
| Chicony Integrated Camera          | 1         | 14.29%  |
| Alpha Imaging Integrated_Webcam_8M | 1         | 14.29%  |

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

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 66        | 95.65%  |
| 1     | 2         | 2.9%    |
| 2     | 1         | 1.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 2         | 40%     |
| Unassigned class      | 1         | 20%     |
| Net/wireless          | 1         | 20%     |
| Multimedia controller | 1         | 20%     |

