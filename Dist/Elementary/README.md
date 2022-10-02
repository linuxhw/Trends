Elementary - Hardware Trends
----------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary/Desktop/README.md) and [notebooks](/Dist/Elementary/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/linuxhw/TestCoverage)

Period: Sep, 2022.

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
| Elementary 6.1 | 46        | 100%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Elementary | 46        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.15.0-46-generic         | 30        | 65.22%  |
| 5.15.0-48-generic         | 10        | 21.74%  |
| 5.11.0-43-generic         | 2         | 4.35%   |
| 6.0.0-060000rc7-generic   | 1         | 2.17%   |
| 5.19.11-xanmod1           | 1         | 2.17%   |
| 5.19.0-8.2-liquorix-amd64 | 1         | 2.17%   |
| 5.11.0-44-generic         | 1         | 2.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 40        | 86.96%  |
| 5.11.0  | 3         | 6.52%   |
| 6.0.0   | 1         | 2.17%   |
| 5.19.11 | 1         | 2.17%   |
| 5.19.0  | 1         | 2.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 40        | 86.96%  |
| 5.11    | 3         | 6.52%   |
| 5.19    | 2         | 4.35%   |
| 6.0     | 1         | 2.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 46        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Pantheon | 46        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 46        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 42        | 91.3%   |
| LightDM | 4         | 8.7%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 20        | 43.48%  |
| ru_RU | 4         | 8.7%    |
| es_ES | 4         | 8.7%    |
| nl_NL | 3         | 6.52%   |
| it_IT | 3         | 6.52%   |
| fr_FR | 3         | 6.52%   |
| de_DE | 3         | 6.52%   |
| en_GB | 2         | 4.35%   |
| tr_TR | 1         | 2.17%   |
| pt_BR | 1         | 2.17%   |
| pl_PL | 1         | 2.17%   |
| de_CH | 1         | 2.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 34        | 73.91%  |
| BIOS | 12        | 26.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type | Computers | Percent |
|------|-----------|---------|
| Ext4 | 46        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 43        | 93.48%  |
| GPT     | 3         | 6.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 45        | 97.83%  |
| Yes       | 1         | 2.17%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Apple               | 9         | 19.57%  |
| Lenovo              | 7         | 15.22%  |
| ASUSTek Computer    | 6         | 13.04%  |
| Dell                | 5         | 10.87%  |
| Acer                | 3         | 6.52%   |
| Hewlett-Packard     | 2         | 4.35%   |
| Gigabyte Technology | 2         | 4.35%   |
| TUXEDO              | 1         | 2.17%   |
| Toshiba             | 1         | 2.17%   |
| Packard Bell        | 1         | 2.17%   |
| MSI                 | 1         | 2.17%   |
| Medion              | 1         | 2.17%   |
| Intel               | 1         | 2.17%   |
| IceWhale Technology | 1         | 2.17%   |
| HUAWEI              | 1         | 2.17%   |
| Google              | 1         | 2.17%   |
| Fanless Mini PC     | 1         | 2.17%   |
| Clevo               | 1         | 2.17%   |
| ASRock              | 1         | 2.17%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Apple MacBookAir6,2                    | 2         | 4.35%   |
| TUXEDO Book XP14 Gen12                 | 1         | 2.17%   |
| Toshiba PORTEGE Z30-B                  | 1         | 2.17%   |
| Packard Bell IMEDIA S1300              | 1         | 2.17%   |
| MSI PS63 Modern 8RD                    | 1         | 2.17%   |
| Medion Akoya E6422 MD99680             | 1         | 2.17%   |
| Lenovo ThinkPad X270 W10DG 20K5S2VL00  | 1         | 2.17%   |
| Lenovo ThinkPad T470 20JNS08H00        | 1         | 2.17%   |
| Lenovo ThinkPad T460 20FMS271BR        | 1         | 2.17%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0GD00   | 1         | 2.17%   |
| Lenovo MIIX 510-12IKB 80XE             | 1         | 2.17%   |
| Lenovo Legion Y540-15IRH 81SX          | 1         | 2.17%   |
| Lenovo IdeaPad 510-15IKB 80SV          | 1         | 2.17%   |
| Intel NUC11PAHi5                       | 1         | 2.17%   |
| IceWhale ZimaBoard 832 ZMB             | 1         | 2.17%   |
| HUAWEI HVY-WXX9                        | 1         | 2.17%   |
| HP Laptop 15-bw0xx                     | 1         | 2.17%   |
| HP ENVY m6                             | 1         | 2.17%   |
| Google Blooglet                        | 1         | 2.17%   |
| Gigabyte G41MT-S2                      | 1         | 2.17%   |
| Gigabyte F2A88XM-D3HP                  | 1         | 2.17%   |
| Fanless Mini PC Quieter 3              | 1         | 2.17%   |
| Dell Vostro 5402                       | 1         | 2.17%   |
| Dell Latitude E6540                    | 1         | 2.17%   |
| Dell Latitude E5450                    | 1         | 2.17%   |
| Dell Inspiron 5458                     | 1         | 2.17%   |
| Dell Inspiron 3493                     | 1         | 2.17%   |
| Clevo W54xEU                           | 1         | 2.17%   |
| ASUS X555LAB                           | 1         | 2.17%   |
| ASUS X555DG                            | 1         | 2.17%   |
| ASUS VivoBook_ASUSLaptop X512DK_X512DK | 1         | 2.17%   |
| ASUS TUF Gaming Z490-PLUS              | 1         | 2.17%   |
| ASUS P8H77-V LE                        | 1         | 2.17%   |
| ASUS GL702VSK                          | 1         | 2.17%   |
| ASRock X370 Taichi                     | 1         | 2.17%   |
| Apple MacPro5,1                        | 1         | 2.17%   |
| Apple Macmini7,1                       | 1         | 2.17%   |
| Apple Macmini5,2                       | 1         | 2.17%   |
| Apple MacBookPro8,2                    | 1         | 2.17%   |
| Apple MacBookPro11,4                   | 1         | 2.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 4         | 8.7%    |
| Dell Latitude           | 2         | 4.35%   |
| Dell Inspiron           | 2         | 4.35%   |
| Apple MacBookPro11      | 2         | 4.35%   |
| Apple MacBookAir6       | 2         | 4.35%   |
| Acer Aspire             | 2         | 4.35%   |
| TUXEDO Book             | 1         | 2.17%   |
| Toshiba PORTEGE         | 1         | 2.17%   |
| Packard Bell IMEDIA     | 1         | 2.17%   |
| MSI PS63                | 1         | 2.17%   |
| Medion Akoya            | 1         | 2.17%   |
| Lenovo MIIX             | 1         | 2.17%   |
| Lenovo Legion           | 1         | 2.17%   |
| Lenovo IdeaPad          | 1         | 2.17%   |
| Intel NUC11PAHi5        | 1         | 2.17%   |
| IceWhale ZimaBoard      | 1         | 2.17%   |
| HUAWEI HVY-WXX9         | 1         | 2.17%   |
| HP Laptop               | 1         | 2.17%   |
| HP ENVY                 | 1         | 2.17%   |
| Google Blooglet         | 1         | 2.17%   |
| Gigabyte G41MT-S2       | 1         | 2.17%   |
| Gigabyte F2A88XM-D3HP   | 1         | 2.17%   |
| Fanless Mini PC Quieter | 1         | 2.17%   |
| Dell Vostro             | 1         | 2.17%   |
| Clevo W54xEU            | 1         | 2.17%   |
| ASUS X555LAB            | 1         | 2.17%   |
| ASUS X555DG             | 1         | 2.17%   |
| ASUS VivoBook           | 1         | 2.17%   |
| ASUS TUF                | 1         | 2.17%   |
| ASUS P8H77-V            | 1         | 2.17%   |
| ASUS GL702VSK           | 1         | 2.17%   |
| ASRock X370             | 1         | 2.17%   |
| Apple MacPro5           | 1         | 2.17%   |
| Apple Macmini7          | 1         | 2.17%   |
| Apple Macmini5          | 1         | 2.17%   |
| Apple MacBookPro8       | 1         | 2.17%   |
| Apple iMac8             | 1         | 2.17%   |
| Acer Nitro              | 1         | 2.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2017 | 7         | 15.22%  |
| 2015 | 6         | 13.04%  |
| 2020 | 5         | 10.87%  |
| 2013 | 5         | 10.87%  |
| 2019 | 4         | 8.7%    |
| 2022 | 3         | 6.52%   |
| 2016 | 3         | 6.52%   |
| 2012 | 3         | 6.52%   |
| 2010 | 3         | 6.52%   |
| 2014 | 2         | 4.35%   |
| 2011 | 2         | 4.35%   |
| 2021 | 1         | 2.17%   |
| 2018 | 1         | 2.17%   |
| 2008 | 1         | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 31        | 67.39%  |
| Desktop    | 9         | 19.57%  |
| Mini pc    | 4         | 8.7%    |
| Tablet     | 1         | 2.17%   |
| All in one | 1         | 2.17%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 39        | 84.78%  |
| Enabled  | 7         | 15.22%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 45        | 97.83%  |
| Yes  | 1         | 2.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 15        | 32.61%  |
| 3.01-4.0   | 11        | 23.91%  |
| 16.01-24.0 | 8         | 17.39%  |
| 8.01-16.0  | 7         | 15.22%  |
| 32.01-64.0 | 3         | 6.52%   |
| 24.01-32.0 | 1         | 2.17%   |
| 1.01-2.0   | 1         | 2.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 16        | 34.78%  |
| 3.01-4.0  | 10        | 21.74%  |
| 2.01-3.0  | 9         | 19.57%  |
| 4.01-8.0  | 8         | 17.39%  |
| 8.01-16.0 | 2         | 4.35%   |
| 0.51-1.0  | 1         | 2.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 34        | 73.91%  |
| 2      | 10        | 21.74%  |
| 4      | 1         | 2.17%   |
| 3      | 1         | 2.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 78.26%  |
| Yes       | 10        | 21.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 86.96%  |
| No        | 6         | 13.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 91.3%   |
| No        | 4         | 8.7%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 82.61%  |
| No        | 8         | 17.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country         | Computers | Percent |
|-----------------|-----------|---------|
| USA             | 8         | 17.39%  |
| Italy           | 7         | 15.22%  |
| Russia          | 4         | 8.7%    |
| Germany         | 4         | 8.7%    |
| Brazil          | 3         | 6.52%   |
| UK              | 2         | 4.35%   |
| Switzerland     | 2         | 4.35%   |
| Mexico          | 2         | 4.35%   |
| Colombia        | 2         | 4.35%   |
| Belgium         | 2         | 4.35%   |
| Venezuela       | 1         | 2.17%   |
| Turkey          | 1         | 2.17%   |
| Poland          | 1         | 2.17%   |
| Pakistan        | 1         | 2.17%   |
| North Macedonia | 1         | 2.17%   |
| Netherlands     | 1         | 2.17%   |
| Indonesia       | 1         | 2.17%   |
| Iceland         | 1         | 2.17%   |
| France          | 1         | 2.17%   |
| Costa Rica      | 1         | 2.17%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City           | Computers | Percent |
|----------------|-----------|---------|
| Pozza di Fassa | 4         | 8.7%    |
| Yuba City      | 2         | 4.35%   |
| Moscow         | 2         | 4.35%   |
| Harelbeke      | 2         | 4.35%   |
| Fortaleza      | 2         | 4.35%   |
| Caslano        | 2         | 4.35%   |
| Yaroslavl      | 1         | 2.17%   |
| Woodbridge     | 1         | 2.17%   |
| Warsaw         | 1         | 2.17%   |
| Strumica       | 1         | 2.17%   |
| Sleman         | 1         | 2.17%   |
| San José      | 1         | 2.17%   |
| San Antonio    | 1         | 2.17%   |
| Queretaro      | 1         | 2.17%   |
| Podolsk        | 1         | 2.17%   |
| Nottingham     | 1         | 2.17%   |
| Morelia        | 1         | 2.17%   |
| Monza          | 1         | 2.17%   |
| Milan          | 1         | 2.17%   |
| Manchester     | 1         | 2.17%   |
| Lesneven       | 1         | 2.17%   |
| Konya          | 1         | 2.17%   |
| Kirkcaldy      | 1         | 2.17%   |
| Islamabad      | 1         | 2.17%   |
| Henderson      | 1         | 2.17%   |
| Hanau          | 1         | 2.17%   |
| Hamburg        | 1         | 2.17%   |
| Gorredijk      | 1         | 2.17%   |
| Fort Worth     | 1         | 2.17%   |
| Empoli         | 1         | 2.17%   |
| Egilsstaðir   | 1         | 2.17%   |
| Dortmund       | 1         | 2.17%   |
| Cota           | 1         | 2.17%   |
| Castle Rock    | 1         | 2.17%   |
| Caracas        | 1         | 2.17%   |
| Brasília      | 1         | 2.17%   |
| Barbosa        | 1         | 2.17%   |
| Altlandsberg   | 1         | 2.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Toshiba                      | 8         | 8      | 13.56%  |
| Samsung Electronics          | 8         | 10     | 13.56%  |
| WDC                          | 6         | 6      | 10.17%  |
| Apple                        | 5         | 5      | 8.47%   |
| Kingston                     | 4         | 4      | 6.78%   |
| A-DATA Technology            | 4         | 4      | 6.78%   |
| Unknown                      | 2         | 2      | 3.39%   |
| Seagate                      | 2         | 3      | 3.39%   |
| SanDisk                      | 2         | 2      | 3.39%   |
| Phison                       | 2         | 2      | 3.39%   |
| HGST                         | 2         | 2      | 3.39%   |
| Crucial                      | 2         | 2      | 3.39%   |
| Corsair                      | 2         | 2      | 3.39%   |
| Yangtze Memory Technologies  | 1         | 1      | 1.69%   |
| SPCC                         | 1         | 1      | 1.69%   |
| Shenzhen Longsys Electronics | 1         | 1      | 1.69%   |
| Realtek Semiconductor        | 1         | 1      | 1.69%   |
| Kingston Technology Company  | 1         | 1      | 1.69%   |
| Intenso                      | 1         | 1      | 1.69%   |
| Hitachi                      | 1         | 1      | 1.69%   |
| Generic-                     | 1         | 1      | 1.69%   |
| Fujitsu                      | 1         | 1      | 1.69%   |
| Unknown                      | 1         | 1      | 1.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                              | 4         | 6.45%   |
| Unknown MMC Card  32GB                              | 2         | 3.23%   |
| Apple SSD SD0256F 256GB                             | 2         | 3.23%   |
| Yangtze Memory YMTC PC005 512GB                     | 1         | 1.61%   |
| WDC WD5000LPCX-60VHAT0 500GB                        | 1         | 1.61%   |
| WDC WD5000AAKX-603CA0 500GB                         | 1         | 1.61%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 1.61%   |
| WDC WD10EADX-22TDHB0 1TB                            | 1         | 1.61%   |
| WDC WD Blue SA510 2.5 500GB SSD                     | 1         | 1.61%   |
| WDC PC SN520 SDAPNUW-512G                           | 1         | 1.61%   |
| Toshiba THNSNJ256GMCU 256GB SSD                     | 1         | 1.61%   |
| Toshiba THNSNF128GCSS 128GB SSD                     | 1         | 1.61%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1.61%   |
| Toshiba MK5061GSYN 500GB                            | 1         | 1.61%   |
| SPCC Solid State Disk 512GB                         | 1         | 1.61%   |
| Shenzhen Longsys M2 Series NVMe SSD 250G            | 1         | 1.61%   |
| Seagate ST31500341AS 1TB                            | 1         | 1.61%   |
| Seagate ST2000LX001-1RG174 2TB                      | 1         | 1.61%   |
| Seagate ST1000DM003-1ER162 1TB                      | 1         | 1.61%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD                 | 1         | 1.61%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD                 | 1         | 1.61%   |
| Samsung SSD 860 EVO 1TB                             | 1         | 1.61%   |
| Samsung SSD 850 EVO 500GB                           | 1         | 1.61%   |
| Samsung SP0812C 80GB                                | 1         | 1.61%   |
| Samsung NVMe SSD Drive 512GB                        | 1         | 1.61%   |
| Samsung NVMe SSD Drive 256GB                        | 1         | 1.61%   |
| Samsung NVMe SSD Drive 250GB                        | 1         | 1.61%   |
| Samsung NVMe SSD Drive 1TB                          | 1         | 1.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 1         | 1.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1.61%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD                | 1         | 1.61%   |
| Realtek ADATA SX6000PNP 512GB                       | 1         | 1.61%   |
| Phison SSD 128GB PS3109-S9                          | 1         | 1.61%   |
| Phison NVMe SSD Drive 1TB                           | 1         | 1.61%   |
| Kingston Company U-SNS8154P3 NVMe SSD 512GB         | 1         | 1.61%   |
| Kingston SV300S37A240G 240GB SSD                    | 1         | 1.61%   |
| Kingston SV300S37A120G 120GB SSD                    | 1         | 1.61%   |
| Kingston SA400S37240G 240GB SSD                     | 1         | 1.61%   |
| Kingston SA400S37120G 120GB SSD                     | 1         | 1.61%   |
| Intenso SSD SATAIII 120GB                           | 1         | 1.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 6         | 6      | 31.58%  |
| WDC                 | 4         | 4      | 21.05%  |
| Seagate             | 2         | 3      | 10.53%  |
| HGST                | 2         | 2      | 10.53%  |
| Samsung Electronics | 1         | 1      | 5.26%   |
| Hitachi             | 1         | 1      | 5.26%   |
| Generic-            | 1         | 1      | 5.26%   |
| Fujitsu             | 1         | 1      | 5.26%   |
| Apple               | 1         | 1      | 5.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 4         | 4      | 15.38%  |
| Apple               | 4         | 4      | 15.38%  |
| Samsung Electronics | 3         | 3      | 11.54%  |
| A-DATA Technology   | 3         | 3      | 11.54%  |
| Toshiba             | 2         | 2      | 7.69%   |
| SanDisk             | 2         | 2      | 7.69%   |
| Crucial             | 2         | 2      | 7.69%   |
| Corsair             | 2         | 2      | 7.69%   |
| WDC                 | 1         | 1      | 3.85%   |
| SPCC                | 1         | 1      | 3.85%   |
| Phison              | 1         | 1      | 3.85%   |
| Intenso             | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 26        | 26     | 44.07%  |
| HDD  | 18        | 20     | 30.51%  |
| NVMe | 12        | 13     | 20.34%  |
| MMC  | 3         | 3      | 5.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 36        | 45     | 69.23%  |
| NVMe | 12        | 13     | 23.08%  |
| MMC  | 3         | 3      | 5.77%   |
| SAS  | 1         | 1      | 1.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 30     | 65.85%  |
| 0.51-1.0   | 11        | 13     | 26.83%  |
| 1.01-2.0   | 2         | 2      | 4.88%   |
| 2.01-3.0   | 1         | 1      | 2.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 23        | 50%     |
| 251-500    | 9         | 19.57%  |
| 501-1000   | 8         | 17.39%  |
| 21-50      | 3         | 6.52%   |
| 1001-2000  | 2         | 4.35%   |
| 51-100     | 1         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 21        | 45.65%  |
| 21-50     | 15        | 32.61%  |
| 251-500   | 3         | 6.52%   |
| 51-100    | 3         | 6.52%   |
| 101-250   | 2         | 4.35%   |
| 1001-2000 | 1         | 2.17%   |
| 501-1000  | 1         | 2.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                      | Computers | Drives | Percent |
|----------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

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

![Drive Status](./All/images/pie_chart/drive_status.svg)

![Drive Status](./All/images/line_chart/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 44        | 58     | 91.67%  |
| Works    | 3         | 3      | 6.25%   |
| Malfunc  | 1         | 1      | 2.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 28        | 51.85%  |
| Samsung Electronics          | 7         | 12.96%  |
| AMD                          | 7         | 12.96%  |
| Nvidia                       | 2         | 3.7%    |
| Marvell Technology Group     | 2         | 3.7%    |
| Yangtze Memory Technologies  | 1         | 1.85%   |
| Shenzhen Longsys Electronics | 1         | 1.85%   |
| SanDisk                      | 1         | 1.85%   |
| Realtek Semiconductor        | 1         | 1.85%   |
| Phison Electronics           | 1         | 1.85%   |
| Kingston Technology Company  | 1         | 1.85%   |
| ASMedia Technology           | 1         | 1.85%   |
| ADATA Technology             | 1         | 1.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 12.28%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 10.53%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 3.51%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 3.51%   |
| Nvidia MCP61 SATA Controller                                                   | 2         | 3.51%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 2         | 3.51%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 3.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 3.51%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 3.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 3.51%   |
| Yangtze Memory Non-Volatile memory controller                                  | 1         | 1.75%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                    | 1         | 1.75%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 1.75%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.75%   |
| Samsung Electronics SATA controller                                            | 1         | 1.75%   |
| Samsung Apple PCIe SSD                                                         | 1         | 1.75%   |
| Realtek Realtek Non-Volatile memory controller                                 | 1         | 1.75%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 1.75%   |
| Nvidia MCP61 IDE                                                               | 1         | 1.75%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 1.75%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.75%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 1.75%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 1.75%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.75%   |
| Intel Comet Lake PCH-H RAID                                                    | 1         | 1.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.75%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.75%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1         | 1.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.75%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 1.75%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 1.75%   |
| AMD X370 Series Chipset SATA Controller                                        | 1         | 1.75%   |
| ADATA Non-Volatile memory controller                                           | 1         | 1.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 35        | 64.81%  |
| NVMe | 12        | 22.22%  |
| IDE  | 4         | 7.41%   |
| RAID | 3         | 5.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 36        | 78.26%  |
| AMD    | 10        | 21.74%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz               | 2         | 4.35%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 2         | 4.35%   |
| Intel Core i5-4250U CPU @ 1.30GHz               | 2         | 4.35%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 4.35%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 2         | 4.35%   |
| Intel Xeon CPU X5680 @ 3.33GHz                  | 1         | 2.17%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1         | 2.17%   |
| Intel Pentium CPU 2030M @ 2.50GHz               | 1         | 2.17%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 2.17%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 2.17%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 2.17%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 2.17%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 1         | 2.17%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz              | 1         | 2.17%   |
| Intel Core i7-4750HQ CPU @ 2.00GHz              | 1         | 2.17%   |
| Intel Core i7-4600M CPU @ 2.90GHz               | 1         | 2.17%   |
| Intel Core i7-2635QM CPU @ 2.00GHz              | 1         | 2.17%   |
| Intel Core i5-9300H CPU @ 2.40GHz               | 1         | 2.17%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 1         | 2.17%   |
| Intel Core i5-4278U CPU @ 2.60GHz               | 1         | 2.17%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 1         | 2.17%   |
| Intel Core i5-2310 CPU @ 2.90GHz                | 1         | 2.17%   |
| Intel Core i3-6100U CPU @ 2.30GHz               | 1         | 2.17%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 1         | 2.17%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 1         | 2.17%   |
| Intel Core i3-10100F CPU @ 3.60GHz              | 1         | 2.17%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 1         | 2.17%   |
| Intel Core 2 Duo CPU E8135 @ 2.40GHz            | 1         | 2.17%   |
| Intel Celeron N5105 @ 2.00GHz                   | 1         | 2.17%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 1         | 2.17%   |
| Intel Celeron CPU N3450 @ 1.10GHz               | 1         | 2.17%   |
| AMD Ryzen 5 4600H with Radeon Graphics          | 1         | 2.17%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 1         | 2.17%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 1         | 2.17%   |
| AMD Athlon II X4 645 Processor                  | 1         | 2.17%   |
| AMD Athlon II X2 250 Processor                  | 1         | 2.17%   |
| AMD A8-5557M APU with Radeon HD Graphics        | 1         | 2.17%   |
| AMD A10-9620P RADEON R5, 10 COMPUTE CORES 4C+6G | 1         | 2.17%   |
| AMD A10-8700P Radeon R6, 10 Compute Cores 4C+6G | 1         | 2.17%   |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 1         | 2.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 11        | 23.91%  |
| Intel Core i7           | 9         | 19.57%  |
| Intel Core i3           | 5         | 10.87%  |
| Other                   | 4         | 8.7%    |
| AMD A10                 | 4         | 8.7%    |
| Intel Celeron           | 3         | 6.52%   |
| AMD Ryzen 5             | 3         | 6.52%   |
| Intel Xeon              | 1         | 2.17%   |
| Intel Pentium Dual-Core | 1         | 2.17%   |
| Intel Pentium           | 1         | 2.17%   |
| Intel Core 2 Duo        | 1         | 2.17%   |
| AMD Athlon II X4        | 1         | 2.17%   |
| AMD Athlon II X2        | 1         | 2.17%   |
| AMD A8                  | 1         | 2.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 26        | 56.52%  |
| 4      | 16        | 34.78%  |
| 6      | 3         | 6.52%   |
| 12     | 1         | 2.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 45        | 97.83%  |
| 2      | 1         | 2.17%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 37        | 80.43%  |
| 1      | 9         | 19.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 46        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 4         | 8.7%    |
| 0x406e3    | 4         | 8.7%    |
| 0x40651    | 4         | 8.7%    |
| 0x306d4    | 3         | 6.52%   |
| 0x206a7    | 3         | 6.52%   |
| 0x906ea    | 2         | 4.35%   |
| 0x806e9    | 2         | 4.35%   |
| 0x40661    | 2         | 4.35%   |
| 0x06001119 | 2         | 4.35%   |
| Unknown    | 2         | 4.35%   |
| 0xa0653    | 1         | 2.17%   |
| 0x906e9    | 1         | 2.17%   |
| 0x906c0    | 1         | 2.17%   |
| 0x806eb    | 1         | 2.17%   |
| 0x506c9    | 1         | 2.17%   |
| 0x306c3    | 1         | 2.17%   |
| 0x306a9    | 1         | 2.17%   |
| 0x206c2    | 1         | 2.17%   |
| 0x1067a    | 1         | 2.17%   |
| 0x10676    | 1         | 2.17%   |
| 0x08600106 | 1         | 2.17%   |
| 0x08108102 | 1         | 2.17%   |
| 0x0800820d | 1         | 2.17%   |
| 0x0600611a | 1         | 2.17%   |
| 0x06006118 | 1         | 2.17%   |
| 0x06003106 | 1         | 2.17%   |
| 0x010000c8 | 1         | 2.17%   |
| 0x010000c7 | 1         | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 7         | 15.22%  |
| KabyLake      | 6         | 13.04%  |
| TigerLake     | 4         | 8.7%    |
| Skylake       | 4         | 8.7%    |
| SandyBridge   | 3         | 6.52%   |
| Broadwell     | 3         | 6.52%   |
| Zen+          | 2         | 4.35%   |
| Piledriver    | 2         | 4.35%   |
| Penryn        | 2         | 4.35%   |
| K10           | 2         | 4.35%   |
| Excavator     | 2         | 4.35%   |
| Zen 2         | 1         | 2.17%   |
| Westmere      | 1         | 2.17%   |
| Tremont       | 1         | 2.17%   |
| Steamroller   | 1         | 2.17%   |
| IvyBridge     | 1         | 2.17%   |
| IceLake       | 1         | 2.17%   |
| Goldmont plus | 1         | 2.17%   |
| Goldmont      | 1         | 2.17%   |
| CometLake     | 1         | 2.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 31        | 57.41%  |
| AMD    | 15        | 27.78%  |
| Nvidia | 8         | 14.81%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 4         | 6.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 4         | 6.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 4         | 6.9%    |
| Intel HD Graphics 5500                                                                | 3         | 5.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 3         | 5.17%   |
| Intel HD Graphics 620                                                                 | 2         | 3.45%   |
| Intel Crystal Well Integrated Graphics Controller                                     | 2         | 3.45%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 2         | 3.45%   |
| Nvidia TU117M                                                                         | 1         | 1.72%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 1         | 1.72%   |
| Nvidia GP108M [GeForce MX330]                                                         | 1         | 1.72%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Max-Q]                                             | 1         | 1.72%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 1         | 1.72%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                              | 1         | 1.72%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 1         | 1.72%   |
| Nvidia GK110 [GeForce GTX 780]                                                        | 1         | 1.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 1.72%   |
| Intel JasperLake [UHD Graphics]                                                       | 1         | 1.72%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 1         | 1.72%   |
| Intel HD Graphics 500                                                                 | 1         | 1.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 1.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 1         | 1.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 1         | 1.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 1         | 1.72%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 1         | 1.72%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                | 1         | 1.72%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                                     | 1         | 1.72%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.72%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 1         | 1.72%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 1         | 1.72%   |
| AMD RV610/M74 [Mobility Radeon HD 2400 XT]                                            | 1         | 1.72%   |
| AMD Richland [Radeon HD 8650G]                                                        | 1         | 1.72%   |
| AMD Richland [Radeon HD 8550G]                                                        | 1         | 1.72%   |
| AMD Renoir                                                                            | 1         | 1.72%   |
| AMD Redwood PRO GL [FirePro V3800]                                                    | 1         | 1.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 1.72%   |
| AMD Mars XTX [Radeon HD 8790M]                                                        | 1         | 1.72%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                            | 1         | 1.72%   |
| AMD Kaveri [Radeon R7 Graphics]                                                       | 1         | 1.72%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 1         | 1.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 22        | 47.83%  |
| 1 x AMD        | 9         | 19.57%  |
| Intel + Nvidia | 5         | 10.87%  |
| 2 x AMD        | 4         | 8.7%    |
| 1 x Nvidia     | 3         | 6.52%   |
| Intel + AMD    | 2         | 4.35%   |
| Other          | 1         | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 40        | 86.96%  |
| Proprietary | 6         | 13.04%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 56.52%  |
| 0.01-0.5   | 7         | 15.22%  |
| 1.01-2.0   | 4         | 8.7%    |
| 0.51-1.0   | 4         | 8.7%    |
| 7.01-8.0   | 2         | 4.35%   |
| 5.01-6.0   | 1         | 2.17%   |
| 3.01-4.0   | 1         | 2.17%   |
| 2.01-3.0   | 1         | 2.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 9         | 19.15%  |
| Apple                | 7         | 14.89%  |
| LG Display           | 6         | 12.77%  |
| Chimei Innolux       | 4         | 8.51%   |
| AU Optronics         | 4         | 8.51%   |
| AOC                  | 4         | 8.51%   |
| Goldstar             | 2         | 4.26%   |
| Eizo                 | 2         | 4.26%   |
| Dell                 | 2         | 4.26%   |
| Vizio                | 1         | 2.13%   |
| Tech Concepts        | 1         | 2.13%   |
| Sharp                | 1         | 2.13%   |
| PANDA                | 1         | 2.13%   |
| Lenovo               | 1         | 2.13%   |
| BOE Technology Group | 1         | 2.13%   |
| Acer                 | 1         | 2.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Eizo EV2450 ENC2531 1920x1080 528x297mm 23.9-inch                | 2         | 4.26%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch   | 2         | 4.26%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch             | 2         | 4.26%   |
| Vizio VO320E VIZ0035 1280x720 700x390mm 31.5-inch                | 1         | 2.13%   |
| Tech Concepts LCD Monitor      DTV 1360x768                      | 1         | 2.13%   |
| Sharp HDMI SHP1048 1920x1080 1330x750mm 60.1-inch                | 1         | 2.13%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch          | 1         | 2.13%   |
| LG Display LCD Monitor LGD0551 1920x1080 309x174mm 14.0-inch     | 1         | 2.13%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch     | 1         | 2.13%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch      | 1         | 2.13%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch      | 1         | 2.13%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch     | 1         | 2.13%   |
| LG Display LCD Monitor LGD03E3 1366x768 310x174mm 14.0-inch      | 1         | 2.13%   |
| Lenovo LEN L1711pC LEN13B7 1280x1024 360x300mm 18.4-inch         | 1         | 2.13%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch         | 1         | 2.13%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch         | 1         | 2.13%   |
| Dell P2417H DELA0DC 1920x1080 527x296mm 23.8-inch                | 1         | 2.13%   |
| Dell 1704FPV DEL3016 1280x1024 340x270mm 17.1-inch               | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch  | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch  | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN1355 1366x768 293x165mm 13.2-inch  | 1         | 2.13%   |
| BOE Technology Group LCD Monitor 1920x1080                       | 1         | 2.13%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch            | 1         | 2.13%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch            | 1         | 2.13%   |
| BOE LCD Monitor BOE0864 1920x1080 344x194mm 15.5-inch            | 1         | 2.13%   |
| BOE LCD Monitor BOE082E 1920x1080 309x174mm 14.0-inch            | 1         | 2.13%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch            | 1         | 2.13%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch             | 1         | 2.13%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch            | 1         | 2.13%   |
| BOE LCD Monitor BOE065E 1920x1080 344x194mm 15.5-inch            | 1         | 2.13%   |
| BOE LCD Monitor BOE05C2 1366x768 309x173mm 13.9-inch             | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch    | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch    | 1         | 2.13%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch           | 1         | 2.13%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch            | 1         | 2.13%   |
| Apple Color LCD APPA019 2880x1800 331x207mm 15.4-inch            | 1         | 2.13%   |
| Apple Color LCD APP9C6B 1680x1050 433x270mm 20.1-inch            | 1         | 2.13%   |
| Apple Cinema HD APP921C 1920x1200 495x310mm 23.0-inch            | 1         | 2.13%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch              | 1         | 2.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 22        | 47.83%  |
| 1366x768 (WXGA)    | 11        | 23.91%  |
| 1440x900 (WXGA+)   | 3         | 6.52%   |
| 2880x1800          | 2         | 4.35%   |
| 2560x1440 (QHD)    | 2         | 4.35%   |
| 1280x1024 (SXGA)   | 2         | 4.35%   |
| 3840x2160 (4K)     | 1         | 2.17%   |
| 1920x1200 (WUXGA)  | 1         | 2.17%   |
| 1680x1050 (WSXGA+) | 1         | 2.17%   |
| 1360x768           | 1         | 2.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 15        | 31.91%  |
| 14      | 7         | 14.89%  |
| 24      | 6         | 12.77%  |
| 13      | 5         | 10.64%  |
| 23      | 2         | 4.26%   |
| 18      | 2         | 4.26%   |
| Unknown | 2         | 4.26%   |
| 60      | 1         | 2.13%   |
| 36      | 1         | 2.13%   |
| 33      | 1         | 2.13%   |
| 27      | 1         | 2.13%   |
| 20      | 1         | 2.13%   |
| 17      | 1         | 2.13%   |
| 16      | 1         | 2.13%   |
| 12      | 1         | 2.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 25        | 53.19%  |
| 501-600     | 8         | 17.02%  |
| 201-300     | 4         | 8.51%   |
| 401-500     | 3         | 6.38%   |
| 701-800     | 2         | 4.26%   |
| 351-400     | 2         | 4.26%   |
| Unknown     | 2         | 4.26%   |
| 1001-1500   | 1         | 2.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 31        | 68.89%  |
| 16/10   | 9         | 20%     |
| Unknown | 2         | 4.44%   |
| 6/5     | 1         | 2.22%   |
| 5/4     | 1         | 2.22%   |
| 3/2     | 1         | 2.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 34.04%  |
| 81-90          | 9         | 19.15%  |
| 201-250        | 6         | 12.77%  |
| 71-80          | 3         | 6.38%   |
| 251-300        | 2         | 4.26%   |
| 151-200        | 2         | 4.26%   |
| 141-150        | 2         | 4.26%   |
| Unknown        | 2         | 4.26%   |
| More than 1000 | 1         | 2.13%   |
| 61-70          | 1         | 2.13%   |
| 351-500        | 1         | 2.13%   |
| 301-350        | 1         | 2.13%   |
| 501-1000       | 1         | 2.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 17        | 36.17%  |
| 51-100  | 14        | 29.79%  |
| 101-120 | 9         | 19.15%  |
| 161-240 | 3         | 6.38%   |
| 1-50    | 2         | 4.26%   |
| Unknown | 2         | 4.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 44        | 95.65%  |
| 2     | 2         | 4.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 23        | 31.51%  |
| Realtek Semiconductor    | 21        | 28.77%  |
| Qualcomm Atheros         | 7         | 9.59%   |
| Broadcom                 | 7         | 9.59%   |
| Broadcom Limited         | 4         | 5.48%   |
| Sierra Wireless          | 2         | 2.74%   |
| OPPO Electronics         | 2         | 2.74%   |
| Nvidia                   | 2         | 2.74%   |
| MediaTek                 | 2         | 2.74%   |
| Ralink Technology        | 1         | 1.37%   |
| Marvell Technology Group | 1         | 1.37%   |
| Fibocom                  | 1         | 1.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 19.32%  |
| Intel Wireless 8260                                               | 4         | 4.55%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 3.41%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 3.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 2.27%   |
| OPPO RMX2117                                                      | 2         | 2.27%   |
| Nvidia MCP61 Ethernet                                             | 2         | 2.27%   |
| MediaTek Nokia 5.1 Plus                                           | 2         | 2.27%   |
| Intel Wireless 8265 / 8275                                        | 2         | 2.27%   |
| Intel Wireless 7265                                               | 2         | 2.27%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 2.27%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.27%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 2.27%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.27%   |
| Sierra Wireless EM7455                                            | 1         | 1.14%   |
| Sierra Wireless EM7305                                            | 1         | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.14%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.14%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 1.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 1.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.14%   |
| Realtek 802.11ac NIC                                              | 1         | 1.14%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.14%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.14%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1.14%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.14%   |
| Intel Wireless 3165                                               | 1         | 1.14%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.14%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1         | 1.14%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.14%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.14%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.14%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.14%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.14%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 45.65%  |
| Realtek Semiconductor | 6         | 13.04%  |
| Qualcomm Atheros      | 6         | 13.04%  |
| Broadcom              | 5         | 10.87%  |
| Broadcom Limited      | 4         | 8.7%    |
| Sierra Wireless       | 2         | 4.35%   |
| Ralink Technology     | 1         | 2.17%   |
| Fibocom               | 1         | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                        | 4         | 8.7%    |
| Intel Wi-Fi 6 AX201                                        | 3         | 6.52%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 3         | 6.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 2         | 4.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2         | 4.35%   |
| Intel Wireless 8265 / 8275                                 | 2         | 4.35%   |
| Intel Wireless 7265                                        | 2         | 4.35%   |
| Intel Wi-Fi 6 AX200                                        | 2         | 4.35%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 2         | 4.35%   |
| Sierra Wireless EM7455                                     | 1         | 2.17%   |
| Sierra Wireless EM7305                                     | 1         | 2.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.17%   |
| Realtek RTL8723DE Wireless Network Adapter                 | 1         | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1         | 2.17%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter            | 1         | 2.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 1         | 2.17%   |
| Realtek 802.11ac NIC                                       | 1         | 2.17%   |
| Ralink MT7601U Wireless Adapter                            | 1         | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1         | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 1         | 2.17%   |
| Intel Wireless 3165                                        | 1         | 2.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1         | 2.17%   |
| Intel Wi-Fi 6 AX201 160MHz                                 | 1         | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1         | 2.17%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 2.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 1         | 2.17%   |
| Fibocom L831-EAU                                           | 1         | 2.17%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                     | 1         | 2.17%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                | 1         | 2.17%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 1         | 2.17%   |
| Broadcom BCM4331 802.11a/b/g/n                             | 1         | 2.17%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller     | 1         | 2.17%   |
| Broadcom BCM4321 802.11a/b/g/n                             | 1         | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 20        | 47.62%  |
| Intel                    | 10        | 23.81%  |
| Broadcom                 | 3         | 7.14%   |
| Qualcomm Atheros         | 2         | 4.76%   |
| OPPO Electronics         | 2         | 4.76%   |
| Nvidia                   | 2         | 4.76%   |
| MediaTek                 | 2         | 4.76%   |
| Marvell Technology Group | 1         | 2.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 40.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 4.76%   |
| OPPO RMX2117                                                      | 2         | 4.76%   |
| Nvidia MCP61 Ethernet                                             | 2         | 4.76%   |
| MediaTek Nokia 5.1 Plus                                           | 2         | 4.76%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 4.76%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 4.76%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 4.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.38%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 2.38%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 2.38%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.38%   |
| Intel Ethernet Controller I225-V                                  | 1         | 2.38%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.38%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.38%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 2.38%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 2.38%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 2.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 42        | 51.22%  |
| Ethernet | 40        | 48.78%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 66.67%  |
| Ethernet | 16        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 32        | 69.57%  |
| 1     | 13        | 28.26%  |
| 3     | 1         | 2.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 28        | 60.87%  |
| Yes  | 18        | 39.13%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 55.26%  |
| Apple                           | 9         | 23.68%  |
| Realtek Semiconductor           | 3         | 7.89%   |
| Lite-On Technology              | 2         | 5.26%   |
| Qualcomm Atheros Communications | 1         | 2.63%   |
| IMC Networks                    | 1         | 2.63%   |
| Foxconn / Hon Hai               | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 9         | 23.68%  |
| Apple Bluetooth Host Controller                | 5         | 13.16%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 4         | 10.53%  |
| Intel AX201 Bluetooth                          | 4         | 10.53%  |
| Realtek Bluetooth Radio                        | 2         | 5.26%   |
| Intel AX200 Bluetooth                          | 2         | 5.26%   |
| Apple Bluetooth USB Host Controller            | 2         | 5.26%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 2.63%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 2.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 2.63%   |
| Lite-On Bluetooth Device                       | 1         | 2.63%   |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 2.63%   |
| Intel AX210 Bluetooth                          | 1         | 2.63%   |
| IMC Networks Bluetooth Device                  | 1         | 2.63%   |
| Foxconn / Hon Hai Bluetooth Device             | 1         | 2.63%   |
| Apple Built-in Bluetooth 2.0+EDR HCI           | 1         | 2.63%   |
| Apple Bluetooth HCI                            | 1         | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 62.07%  |
| AMD                   | 13        | 22.41%  |
| Nvidia                | 6         | 10.34%  |
| Realtek Semiconductor | 1         | 1.72%   |
| Logitech              | 1         | 1.72%   |
| Anlya.cn              | 1         | 1.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 6         | 7.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 5.26%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 5.26%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 5.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 3.95%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 3.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 3.95%   |
| AMD FCH Azalia Controller                                                  | 3         | 3.95%   |
| Nvidia MCP61 High Definition Audio                                         | 2         | 2.63%   |
| Intel Crystal Well HD Audio Controller                                     | 2         | 2.63%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 2.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.63%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 2.63%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 2.63%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 2.63%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 2.63%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.32%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.32%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 1.32%   |
| Nvidia GK110 High Definition Audio Controller                              | 1         | 1.32%   |
| Logitech Logitech USB Microphone                                           | 1         | 1.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.32%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.32%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.32%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.32%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.32%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.32%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.32%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.32%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 1.32%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.32%   |
| Anlya.cn ATE1133                                                           | 1         | 1.32%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 1.32%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 1.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.32%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1.32%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1         | 1.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 57.14%  |
| SK hynix            | 1         | 14.29%  |
| Micron Technology   | 1         | 14.29%  |
| A-DATA Technology   | 1         | 14.29%  |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 1         | 14.29%  |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s  | 1         | 14.29%  |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 1         | 14.29%  |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s | 1         | 14.29%  |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 1         | 14.29%  |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s     | 1         | 14.29%  |
| A-DATA RAM Module 8192MB SODIMM DDR4 2667MT/s             | 1         | 14.29%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| DDR4 | 3         | 60%     |
| DDR3 | 2         | 40%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 5         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 3         | 42.86%  |
| 4096  | 3         | 42.86%  |
| 16384 | 1         | 14.29%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 4         | 57.14%  |
| 8400  | 1         | 14.29%  |
| 2133  | 1         | 14.29%  |
| 1600  | 1         | 14.29%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)

![Printer Vendor](./All/images/line_chart/printer_vendor.svg)

| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)

![Printer Model](./All/images/line_chart/printer_model.svg)

| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| HP OfficeJet 5200 series | 1         | 100%    |

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
| Chicony Electronics                    | 8         | 26.67%  |
| Realtek Semiconductor                  | 4         | 13.33%  |
| Microdia                               | 3         | 10%     |
| Acer                                   | 3         | 10%     |
| Quanta                                 | 2         | 6.67%   |
| Logitech                               | 2         | 6.67%   |
| IMC Networks                           | 2         | 6.67%   |
| Apple                                  | 2         | 6.67%   |
| Syntek                                 | 1         | 3.33%   |
| Suyin                                  | 1         | 3.33%   |
| Sunplus Innovation Technology          | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 4         | 13.33%  |
| Realtek USB Camera                                             | 2         | 6.67%   |
| Syntek EasyCamera                                              | 1         | 3.33%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 3.33%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 3.33%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 3.33%   |
| Realtek Built-In Video Camera                                  | 1         | 3.33%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 3.33%   |
| Quanta HD Webcam                                               | 1         | 3.33%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 3.33%   |
| Microdia Integrated Webcam                                     | 1         | 3.33%   |
| Microdia CameraA                                               | 1         | 3.33%   |
| Logitech Webcam C270                                           | 1         | 3.33%   |
| Logitech C922 Pro Stream Webcam                                | 1         | 3.33%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 3.33%   |
| IMC Networks HD Camera                                         | 1         | 3.33%   |
| Chicony USB2.0 Camera                                          | 1         | 3.33%   |
| Chicony TOSHIBA Web Camera - FHD                               | 1         | 3.33%   |
| Chicony HP Truevision HD                                       | 1         | 3.33%   |
| Chicony HD WebCam (Acer)                                       | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 3.33%   |
| Apple FaceTime HD Camera                                       | 1         | 3.33%   |
| Apple Built-in iSight                                          | 1         | 3.33%   |
| Acer Integrated Camera                                         | 1         | 3.33%   |
| Acer HD Webcam                                                 | 1         | 3.33%   |
| Acer BisonCam, NB Pro                                          | 1         | 3.33%   |

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

| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS Fingerprint sensor      | 1         | 25%     |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 25%     |
| Shenzhen Goodix  Fingerprint Device          | 1         | 25%     |
| Unknown                                      | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./All/images/line_chart/chipcard_vendor.svg)

| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| O2 Micro    | 1         | 33.33%  |
| Broadcom    | 1         | 33.33%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 35        | 76.09%  |
| 1     | 9         | 19.57%  |
| 2     | 2         | 4.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 4         | 30.77%  |
| Fingerprint reader    | 4         | 30.77%  |
| Chipcard              | 3         | 23.08%  |
| Net/wireless          | 2         | 15.38%  |

