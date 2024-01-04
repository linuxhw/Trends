CentOS - Hardware Trends
------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/CentOS/Desktop/README.md) and [notebooks](/Dist/CentOS/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: Dec, 2023.

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

| Name     | Computers | Percent |
|----------|-----------|---------|
| CentOS 7 | 73        | 96.05%  |
| CentOS 9 | 3         | 3.95%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| CentOS | 76        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 3.10.0-1160.102.1.el7.x86_64 | 44        | 57.89%  |
| 3.10.0-1160.90.1.el7.x86_64  | 10        | 13.16%  |
| 3.10.0-1160.95.1.el7.x86_64  | 8         | 10.53%  |
| 3.10.0-1160.45.1.el7.x86_64  | 4         | 5.26%   |
| 3.10.0-1160.88.1.el7.x86_64  | 3         | 3.95%   |
| 5.14.0-391.el9.x86_64        | 2         | 2.63%   |
| 3.10.0-1160.83.1.el7.x86_64  | 2         | 2.63%   |
| 3.10.0-1160.105.1.el7.x86_64 | 2         | 2.63%   |
| 5.14.0-390.el9.x86_64        | 1         | 1.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 3.10.0  | 73        | 96.05%  |
| 5.14.0  | 3         | 3.95%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 3.10    | 73        | 96.05%  |
| 5.14    | 3         | 3.95%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 76        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| GNOME    | 72        | 94.74%  |
| MATE     | 2         | 2.63%   |
| KDE5     | 1         | 1.32%   |
| Cinnamon | 1         | 1.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 74        | 97.37%  |
| Wayland | 2         | 2.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 71        | 93.42%  |
| Unknown | 3         | 3.95%   |
| LightDM | 2         | 2.63%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 70        | 92.11%  |
| en_US   | 2         | 2.63%   |
| en_AU   | 2         | 2.63%   |
| pt_BR   | 1         | 1.32%   |
| ja_JP   | 1         | 1.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 64        | 84.21%  |
| BIOS | 12        | 15.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type | Computers | Percent |
|------|-----------|---------|
| Ext4 | 36        | 47.37%  |
| Ext3 | 32        | 42.11%  |
| Xfs  | 8         | 10.53%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 63        | 82.89%  |
| MBR     | 11        | 14.47%  |
| Unknown | 2         | 2.63%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 74        | 97.37%  |
| Yes       | 2         | 2.63%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| MSI                 | 37        | 48.68%  |
| Gigabyte Technology | 29        | 38.16%  |
| ASUSTek Computer    | 6         | 7.89%   |
| Intel               | 2         | 2.63%   |
| SHANGZHAOYUAN       | 1         | 1.32%   |
| Dell                | 1         | 1.32%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| MSI MS-7C31                 | 15        | 19.74%  |
| Gigabyte H81M-S2H           | 15        | 19.74%  |
| MSI MS-7A15                 | 9         | 11.84%  |
| MSI MS-7B53                 | 6         | 7.89%   |
| MSI MS-7A74                 | 6         | 7.89%   |
| Gigabyte H81M-DS2           | 4         | 5.26%   |
| ASUS H110M-K                | 4         | 5.26%   |
| Gigabyte H81M-S2PV          | 3         | 3.95%   |
| Gigabyte B560M AORUS PRO    | 2         | 2.63%   |
| Gigabyte B360M-HD3          | 2         | 2.63%   |
| SHANGZHAOYUAN B85M-PRO V1.1 | 1         | 1.32%   |
| MSI MS-7E01                 | 1         | 1.32%   |
| Intel S1200SP               | 1         | 1.32%   |
| Intel S1200RP_SE            | 1         | 1.32%   |
| Gigabyte H81M-S2PH          | 1         | 1.32%   |
| Gigabyte EP45-DS3L          | 1         | 1.32%   |
| Gigabyte B250M-HD3          | 1         | 1.32%   |
| Dell OptiPlex 7010          | 1         | 1.32%   |
| ASUS PRIME H670-PLUS D4     | 1         | 1.32%   |
| ASUS M5A78L-M LX V2         | 1         | 1.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| MSI MS-7C31            | 15        | 19.74%  |
| Gigabyte H81M-S2H      | 15        | 19.74%  |
| MSI MS-7A15            | 9         | 11.84%  |
| MSI MS-7B53            | 6         | 7.89%   |
| MSI MS-7A74            | 6         | 7.89%   |
| Gigabyte H81M-DS2      | 4         | 5.26%   |
| ASUS H110M-K           | 4         | 5.26%   |
| Gigabyte H81M-S2PV     | 3         | 3.95%   |
| Gigabyte B560M         | 2         | 2.63%   |
| Gigabyte B360M-HD3     | 2         | 2.63%   |
| SHANGZHAOYUAN B85M-PRO | 1         | 1.32%   |
| MSI MS-7E01            | 1         | 1.32%   |
| Intel S1200SP          | 1         | 1.32%   |
| Intel S1200RP          | 1         | 1.32%   |
| Gigabyte H81M-S2PH     | 1         | 1.32%   |
| Gigabyte EP45-DS3L     | 1         | 1.32%   |
| Gigabyte B250M-HD3     | 1         | 1.32%   |
| Dell OptiPlex          | 1         | 1.32%   |
| ASUS PRIME             | 1         | 1.32%   |
| ASUS M5A78L-M          | 1         | 1.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 15        | 19.74%  |
| 2014 | 15        | 19.74%  |
| 2016 | 10        | 13.16%  |
| 2018 | 9         | 11.84%  |
| 2013 | 8         | 10.53%  |
| 2017 | 6         | 7.89%   |
| 2015 | 6         | 7.89%   |
| 2021 | 3         | 3.95%   |
| 2022 | 2         | 2.63%   |
| 2011 | 1         | 1.32%   |
| 2008 | 1         | 1.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Desktop | 74        | 97.37%  |
| Server  | 2         | 2.63%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 75        | 98.68%  |
| Enabled  | 1         | 1.32%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 76        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 69        | 90.79%  |
| 32.01-64.0  | 2         | 2.63%   |
| 16.01-24.0  | 2         | 2.63%   |
| 24.01-32.0  | 1         | 1.32%   |
| 64.01-256.0 | 1         | 1.32%   |
| 8.01-16.0   | 1         | 1.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 41        | 53.95%  |
| 0.51-1.0   | 24        | 31.58%  |
| 2.01-3.0   | 5         | 6.58%   |
| 3.01-4.0   | 4         | 5.26%   |
| 4.01-8.0   | 1         | 1.32%   |
| 16.01-24.0 | 1         | 1.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 71        | 93.42%  |
| 3      | 2         | 2.63%   |
| 6      | 1         | 1.32%   |
| 4      | 1         | 1.32%   |
| 2      | 1         | 1.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 96.05%  |
| Yes       | 3         | 3.95%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 75        | 98.68%  |
| Yes       | 1         | 1.32%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 75        | 98.68%  |
| Yes       | 1         | 1.32%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country   | Computers | Percent |
|-----------|-----------|---------|
| Australia | 72        | 94.74%  |
| USA       | 1         | 1.32%   |
| Japan     | 1         | 1.32%   |
| China     | 1         | 1.32%   |
| Brazil    | 1         | 1.32%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City         | Computers | Percent |
|--------------|-----------|---------|
| Melbourne    | 71        | 93.42%  |
| Sydney       | 1         | 1.32%   |
| Porto Alegre | 1         | 1.32%   |
| Nagoya       | 1         | 1.32%   |
| Hangzhou     | 1         | 1.32%   |
| Durham       | 1         | 1.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 70        | 72     | 86.42%  |
| Seagate             | 5         | 5      | 6.17%   |
| Toshiba             | 1         | 2      | 1.23%   |
| Sandisk             | 1         | 2      | 1.23%   |
| Samsung Electronics | 1         | 5      | 1.23%   |
| Kingston            | 1         | 1      | 1.23%   |
| Intel               | 1         | 1      | 1.23%   |
| Crucial             | 1         | 2      | 1.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| WDC WD10EZEX-08WN4A0 1TB       | 30        | 36.14%  |
| WDC WD10EZEX-00MFCA0 1TB       | 18        | 21.69%  |
| WDC WD10EZEX-00WN4A0 1TB       | 9         | 10.84%  |
| WDC WD10EZEX-60WN4A0 1TB       | 5         | 6.02%   |
| WDC WD10EZEX-75WN4A0 1TB       | 4         | 4.82%   |
| WDC WD10EZEX-00BBHA0 1TB       | 2         | 2.41%   |
| Seagate ST1000DM010-2EP102 1TB | 2         | 2.41%   |
| Seagate ST1000DM003-1SB10C 1TB | 2         | 2.41%   |
| WDC WD10EZEX-22MFCA0 1TB       | 1         | 1.2%    |
| WDC WD10EZEX-08M2NA0 1TB       | 1         | 1.2%    |
| WDC WD Blue SA510 2.5 500GB    | 1         | 1.2%    |
| Toshiba DT01ACA200 2TB         | 1         | 1.2%    |
| Seagate ST2000VN004-2E4164 2TB | 1         | 1.2%    |
| Sandisk WD_BLACK SN770 1TB     | 1         | 1.2%    |
| SanDisk SDSSDH3 1T00 1TB       | 1         | 1.2%    |
| Samsung HD501LJ 500GB          | 1         | 1.2%    |
| Kingston SFYRD2000G 2TB        | 1         | 1.2%    |
| Intel SSDSA2M080G2LE 80GB      | 1         | 1.2%    |
| Crucial CT525MX300SSD1 528GB   | 1         | 1.2%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 69        | 71     | 90.79%  |
| Seagate             | 5         | 5      | 6.58%   |
| Toshiba             | 1         | 2      | 1.32%   |
| Samsung Electronics | 1         | 5      | 1.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 25%     |
| SanDisk | 1         | 1      | 25%     |
| Intel   | 1         | 1      | 25%     |
| Crucial | 1         | 2      | 25%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 74        | 83     | 93.67%  |
| SSD  | 3         | 5      | 3.8%    |
| NVMe | 2         | 2      | 2.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 75        | 88     | 97.4%   |
| NVMe | 2         | 2      | 2.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 72        | 78     | 94.74%  |
| 1.01-2.0   | 2         | 3      | 2.63%   |
| 0.01-0.5   | 2         | 7      | 2.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 501-1000   | 70        | 92.11%  |
| 1001-2000  | 4         | 5.26%   |
| 251-500    | 1         | 1.32%   |
| 21-50      | 1         | 1.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 101-250  | 29        | 38.16%  |
| 51-100   | 21        | 27.63%  |
| 1-20     | 17        | 22.37%  |
| 251-500  | 4         | 5.26%   |
| 21-50    | 3         | 3.95%   |
| 501-1000 | 2         | 2.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC WD10EZEX-08WN4A0 1TB  | 2         | 2      | 66.67%  |
| Intel SSDSA2M080G2LE 80GB | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 2         | 2      | 66.67%  |
| Intel  | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 2         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 66.67%  |
| SSD  | 1         | 1      | 33.33%  |

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
| Works    | 72        | 82     | 93.51%  |
| Malfunc  | 3         | 3      | 3.9%    |
| Detected | 2         | 5      | 2.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 75        | 96.15%  |
| SanDisk                     | 1         | 1.28%   |
| Kingston Technology Company | 1         | 1.28%   |
| AMD                         | 1         | 1.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 25        | 31.25%  |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 23        | 28.75%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 14        | 17.5%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 8         | 10%     |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 2.5%    |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 1.25%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 1         | 1.25%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1         | 1.25%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1         | 1.25%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                           | 1         | 1.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1         | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1         | 1.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 76        | 96.2%   |
| NVMe | 2         | 2.53%   |
| IDE  | 1         | 1.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 75        | 98.68%  |
| AMD    | 1         | 1.32%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5-4460 CPU @ 3.20GHz     | 22        | 28.95%  |
| Intel Core i5-9400 CPU @ 2.90GHz     | 21        | 27.63%  |
| Intel Core i5-7400 CPU @ 3.00GHz     | 16        | 21.05%  |
| Intel Core i7-7700 CPU @ 3.60GHz     | 4         | 5.26%   |
| Intel Core i7-8700 CPU @ 3.20GHz     | 2         | 2.63%   |
| Intel Core i5-10400 CPU @ 2.90GHz    | 2         | 2.63%   |
| Intel Xeon CPU E3-1240 v5 @ 3.50GHz  | 1         | 1.32%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz  | 1         | 1.32%   |
| Intel Core i7-4770K CPU @ 3.50GHz    | 1         | 1.32%   |
| Intel Core i7-3770 CPU @ 3.40GHz     | 1         | 1.32%   |
| Intel Core i3-4160 CPU @ 3.60GHz     | 1         | 1.32%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz | 1         | 1.32%   |
| Intel 13th Gen Core i7-13700K        | 1         | 1.32%   |
| Intel 12th Gen Core i5-12600K        | 1         | 1.32%   |
| AMD FX-4130 Quad-Core Processor      | 1         | 1.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 61        | 80.26%  |
| Intel Core i7    | 8         | 10.53%  |
| Other            | 2         | 2.63%   |
| Intel Xeon       | 2         | 2.63%   |
| Intel Core i3    | 1         | 1.32%   |
| Intel Core 2 Duo | 1         | 1.32%   |
| AMD FX           | 1         | 1.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 46        | 60.53%  |
| 6      | 25        | 32.89%  |
| 2      | 3         | 3.95%   |
| 16     | 1         | 1.32%   |
| 10     | 1         | 1.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 76        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 60        | 78.95%  |
| 2      | 16        | 21.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 76        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 23        | 30.26%  |
| 0x906e9    | 20        | 26.32%  |
| 0x906ea    | 16        | 21.05%  |
| 0x906ec    | 4         | 5.26%   |
| Unknown    | 4         | 5.26%   |
| 0x906ed    | 3         | 3.95%   |
| 0xa0653    | 2         | 2.63%   |
| 0x506e3    | 1         | 1.32%   |
| 0x306a9    | 1         | 1.32%   |
| 0x1067a    | 1         | 1.32%   |
| 0x0600063e | 1         | 1.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 43        | 56.58%  |
| Haswell          | 25        | 32.89%  |
| CometLake        | 2         | 2.63%   |
| Alderlake Hybrid | 2         | 2.63%   |
| Skylake          | 1         | 1.32%   |
| Penryn           | 1         | 1.32%   |
| IvyBridge        | 1         | 1.32%   |
| Bulldozer        | 1         | 1.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 71        | 89.87%  |
| Nvidia                     | 5         | 6.33%   |
| Matrox Electronics Systems | 2         | 2.53%   |
| AMD                        | 1         | 1.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 23        | 29.11%  |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 23        | 29.11%  |
| Intel HD Graphics 630                                                       | 20        | 25.32%  |
| Nvidia GF119 [GeForce GT 610]                                               | 2         | 2.53%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)           | 2         | 2.53%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2         | 2.53%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1         | 1.27%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1         | 1.27%   |
| Nvidia G72 [GeForce 7300 GS]                                                | 1         | 1.27%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 1         | 1.27%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1         | 1.27%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1         | 1.27%   |
| AMD RS780L [Radeon 3000]                                                    | 1         | 1.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 70        | 92.11%  |
| Nvidia + Matrox | 2         | 2.63%   |
| 1 x Nvidia      | 2         | 2.63%   |
| Intel + Nvidia  | 1         | 1.32%   |
| 1 x AMD         | 1         | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 71        | 93.42%  |
| Unknown     | 4         | 5.26%   |
| Proprietary | 1         | 1.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 71        | 93.42%  |
| 1.01-2.0   | 3         | 3.95%   |
| 0.01-0.5   | 2         | 2.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Philips  | 5         | 41.67%  |
| AOC      | 3         | 25%     |
| Iiyama   | 1         | 8.33%   |
| HKC      | 1         | 8.33%   |
| Goldstar | 1         | 8.33%   |
| Dell     | 1         | 8.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch  | 1         | 8.33%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch  | 1         | 8.33%   |
| Philips PHL 241V8B PHLC314 1920x1080 527x296mm 23.8-inch | 1         | 8.33%   |
| Philips PHL 223V7 PHLC154 1920x1080 476x268mm 21.5-inch  | 1         | 8.33%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch  | 1         | 8.33%   |
| Iiyama PL2888H IVM7106 1920x1080 620x340mm 27.8-inch     | 1         | 8.33%   |
| HKC 24N1 HKC2413 1920x1080 527x296mm 23.8-inch           | 1         | 8.33%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch   | 1         | 8.33%   |
| Dell P2317H DEL40F2 1920x1080 509x286mm 23.0-inch        | 1         | 8.33%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch          | 1         | 8.33%   |
| AOC 2217 AOC2217 1680x1050 470x300mm 22.0-inch           | 1         | 8.33%   |
| AOC 1960W AOC1960 1366x768 410x230mm 18.5-inch           | 1         | 8.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 9         | 81.82%  |
| 1680x1050 (WSXGA+) | 1         | 9.09%   |
| 1440x900 (WXGA+)   | 1         | 9.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 23     | 5         | 41.67%  |
| 21     | 3         | 25%     |
| 27     | 1         | 8.33%   |
| 24     | 1         | 8.33%   |
| 22     | 1         | 8.33%   |
| 19     | 1         | 8.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 6         | 50%     |
| 401-500     | 4         | 33.33%  |
| 601-700     | 1         | 8.33%   |
| 351-400     | 1         | 8.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 9         | 81.82%  |
| 5/4   | 1         | 9.09%   |
| 16/10 | 1         | 9.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 9         | 81.82%  |
| 301-350        | 1         | 9.09%   |
| 151-200        | 1         | 9.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 9         | 75%     |
| 101-120 | 3         | 25%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 66        | 86.84%  |
| 1     | 8         | 10.53%  |
| 2     | 2         | 2.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 72        | 90%     |
| Intel                 | 6         | 7.5%    |
| D-Link System         | 1         | 1.25%   |
| Aquantia              | 1         | 1.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 69        | 84.15%  |
| Realtek RTL8125 2.5GbE Controller                                   | 2         | 2.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 2         | 2.44%   |
| Intel I210 Gigabit Network Connection                               | 2         | 2.44%   |
| Intel Ethernet Controller I225-V                                    | 2         | 2.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 1         | 1.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 1         | 1.22%   |
| Intel 700 Series Chipset Family Wi-Fi                               | 1         | 1.22%   |
| D-Link System RTL8139 Ethernet                                      | 1         | 1.22%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1         | 100%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel 700 Series Chipset Family Wi-Fi | 1         | 100%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 72        | 91.14%  |
| Intel                 | 5         | 6.33%   |
| D-Link System         | 1         | 1.27%   |
| Aquantia              | 1         | 1.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 69        | 85.19%  |
| Realtek RTL8125 2.5GbE Controller                                   | 2         | 2.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 2         | 2.47%   |
| Intel I210 Gigabit Network Connection                               | 2         | 2.47%   |
| Intel Ethernet Controller I225-V                                    | 2         | 2.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 1         | 1.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 1         | 1.23%   |
| D-Link System RTL8139 Ethernet                                      | 1         | 1.23%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 76        | 98.7%   |
| WiFi     | 1         | 1.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 76        | 100%    |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 56        | 73.68%  |
| 1     | 19        | 25%     |
| 3     | 1         | 1.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 73        | 96.05%  |
| Yes  | 3         | 3.95%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1         | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Bluetooth Device | 1         | 100%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 72        | 93.51%  |
| Nvidia | 4         | 5.19%   |
| AMD    | 1         | 1.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 24        | 23.53%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 24        | 23.53%  |
| Intel 200 Series PCH HD Audio                                       | 23        | 22.55%  |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 13        | 12.75%  |
| Intel Cannon Lake PCH cAVS                                          | 8         | 7.84%   |
| Nvidia GF119 HDMI Audio Controller                                  | 2         | 1.96%   |
| Intel Smart Sound Technology (SST) Audio Controller                 | 2         | 1.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 1         | 0.98%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]       | 1         | 0.98%   |
| Intel Alder Lake-S HD Audio Controller                              | 1         | 0.98%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1    | 1         | 0.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 0.98%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 1         | 0.98%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Kingston          | 24        | 32.88%  |
| Crucial           | 16        | 21.92%  |
| G.Skill           | 13        | 17.81%  |
| GeIL              | 9         | 12.33%  |
| Team              | 4         | 5.48%   |
| Unknown           | 2         | 2.74%   |
| PNY               | 2         | 2.74%   |
| SK hynix          | 1         | 1.37%   |
| Apacer            | 1         | 1.37%   |
| A-DATA Technology | 1         | 1.37%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Kingston RAM CL16-16-16 D4-2400 8192MB DIMM DDR4 2400MT/s  | 9         | 12.33%  |
| GeIL RAM CL11-11-11 D3-1600 4GB DIMM 1600MT/s              | 9         | 12.33%  |
| G.Skill RAM F4-2666C19-8GIS 8GB DIMM DDR4 3000MT/s         | 9         | 12.33%  |
| Kingston RAM 9905678-173.A00G 8192MB DIMM DDR4 2400MT/s    | 5         | 6.85%   |
| Crucial RAM CT8G4DFD8213.C16FBD2 8192MB DIMM DDR4 2500MT/s | 5         | 6.85%   |
| Team RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s        | 4         | 5.48%   |
| G.Skill RAM F3-1600C11-8GNT 8GB DIMM DDR3 1600MT/s         | 4         | 5.48%   |
| Crucial RAM CT8G4DFS8213.C8FDD1 8192MB DIMM DDR4 2400MT/s  | 4         | 5.48%   |
| Kingston RAM 99U5471-058.A00LF 8192MB DIMM DDR3 1600MT/s   | 3         | 4.11%   |
| Crucial RAM CT102464BD160B.M16 8GB DIMM DDR3 1600MT/s      | 3         | 4.11%   |
| PNY RAM M4U08S681LJJJ43-12 8192MB DIMM DDR4 2666MT/s       | 2         | 2.74%   |
| Kingston RAM KHX1600C9D3/8GX 8192MB DIMM DDR3 2133MT/s     | 2         | 2.74%   |
| Crucial RAM CT8G4DFS8266.C8FN 8192MB DIMM DDR4 2667MT/s    | 2         | 2.74%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                     | 1         | 1.37%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                     | 1         | 1.37%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s       | 1         | 1.37%   |
| Kingston RAM CL15-15-15 D4-2400 8192MB DIMM DDR4 2400MT/s  | 1         | 1.37%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s      | 1         | 1.37%   |
| Kingston RAM 9965525-139.A00LF 8192MB DIMM DDR3 1600MT/s   | 1         | 1.37%   |
| Kingston RAM 9905702-137.A00G 8GB DIMM DDR4 2400MT/s       | 1         | 1.37%   |
| Kingston RAM 9905702-119.A00G 8GB DIMM DDR4 2667MT/s       | 1         | 1.37%   |
| Crucial RAM CT8G4DFS8213.M8FB 8192MB DIMM DDR4 2133MT/s    | 1         | 1.37%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s      | 1         | 1.37%   |
| Apacer RAM 78.C1GET.4210C 8192MB DIMM DDR3 1600MT/s        | 1         | 1.37%   |
| A-DATA RAM Module 8192MB DIMM DDR3 1600MT/s                | 1         | 1.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 44        | 61.11%  |
| DDR3    | 26        | 36.11%  |
| Unknown | 2         | 2.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| DIMM | 72        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 58        | 79.45%  |
| 16384 | 13        | 17.81%  |
| 4096  | 1         | 1.37%   |
| 2048  | 1         | 1.37%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 2400  | 24        | 32.88%  |
| 1600  | 23        | 31.51%  |
| 3000  | 9         | 12.33%  |
| 2500  | 5         | 6.85%   |
| 2667  | 3         | 4.11%   |
| 2133  | 3         | 4.11%   |
| 2666  | 2         | 2.74%   |
| 1800  | 2         | 2.74%   |
| 800   | 1         | 1.37%   |
| 667   | 1         | 1.37%   |

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

Zero info for selected period =(

Camera Model
------------

Camera device models

Zero info for selected period =(

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
| 0     | 72        | 94.74%  |
| 2     | 2         | 2.63%   |
| 1     | 2         | 2.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 4         | 66.67%  |
| Communication controller | 2         | 33.33%  |

