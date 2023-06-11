Elementary - Hardware Trends
----------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary/Desktop/README.md) and [notebooks](/Dist/Elementary/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: May, 2023.

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

| Name           | Computers | Percent |
|----------------|-----------|---------|
| Elementary 7   | 36        | 81.82%  |
| Elementary 6.1 | 8         | 18.18%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Elementary | 44        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.19.0-41-generic | 21        | 47.73%  |
| 5.15.0-58-generic | 8         | 18.18%  |
| 5.19.0-42-generic | 4         | 9.09%   |
| 5.15.0-71-generic | 3         | 6.82%   |
| 6.2.14-surface    | 1         | 2.27%   |
| 6.1.0-1013-oem    | 1         | 2.27%   |
| 5.19.0-43-generic | 1         | 2.27%   |
| 5.15.0-72-generic | 1         | 2.27%   |
| 5.15.0-69-generic | 1         | 2.27%   |
| 5.15.0-56-generic | 1         | 2.27%   |
| 5.13.0-28-generic | 1         | 2.27%   |
| 5.11.0-43-generic | 1         | 2.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19.0  | 26        | 59.09%  |
| 5.15.0  | 14        | 31.82%  |
| 6.2.14  | 1         | 2.27%   |
| 6.1.0   | 1         | 2.27%   |
| 5.13.0  | 1         | 2.27%   |
| 5.11.0  | 1         | 2.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19    | 26        | 59.09%  |
| 5.15    | 14        | 31.82%  |
| 6.2     | 1         | 2.27%   |
| 6.1     | 1         | 2.27%   |
| 5.13    | 1         | 2.27%   |
| 5.11    | 1         | 2.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 44        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Pantheon | 44        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 44        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 30        | 68.18%  |
| LightDM | 14        | 31.82%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 18        | 40.91%  |
| ru_RU | 6         | 13.64%  |
| es_ES | 5         | 11.36%  |
| de_DE | 4         | 9.09%   |
| pt_PT | 2         | 4.55%   |
| sv_SE | 1         | 2.27%   |
| pt_BR | 1         | 2.27%   |
| pl_PL | 1         | 2.27%   |
| nl_NL | 1         | 2.27%   |
| it_IT | 1         | 2.27%   |
| hu_HU | 1         | 2.27%   |
| fr_FR | 1         | 2.27%   |
| en_GB | 1         | 2.27%   |
| C     | 1         | 2.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 31        | 70.45%  |
| EFI  | 13        | 29.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 42        | 95.45%  |
| Tmpfs   | 1         | 2.27%   |
| Overlay | 1         | 2.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 30        | 68.18%  |
| GPT     | 12        | 27.27%  |
| MBR     | 2         | 4.55%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 95.45%  |
| Yes       | 2         | 4.55%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 39        | 88.64%  |
| Yes       | 5         | 11.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 11        | 25%     |
| Lenovo              | 7         | 15.91%  |
| ASUSTek Computer    | 6         | 13.64%  |
| Dell                | 4         | 9.09%   |
| HUAWEI              | 2         | 4.55%   |
| Acer                | 2         | 4.55%   |
| Samsung Electronics | 1         | 2.27%   |
| PCBOX               | 1         | 2.27%   |
| Multilaser          | 1         | 2.27%   |
| MSI                 | 1         | 2.27%   |
| Microsoft           | 1         | 2.27%   |
| Intel               | 1         | 2.27%   |
| HONOR               | 1         | 2.27%   |
| Gigabyte Technology | 1         | 2.27%   |
| Clevo               | 1         | 2.27%   |
| Chuwi               | 1         | 2.27%   |
| Alienware           | 1         | 2.27%   |
| Unknown             | 1         | 2.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 2.27%   |
| PCBOX Kant                                 | 1         | 2.27%   |
| Multilaser PC150                           | 1         | 2.27%   |
| MSI GE62VR 6RF                             | 1         | 2.27%   |
| Microsoft Surface Pro 7                    | 1         | 2.27%   |
| Lenovo ThinkPad P51s 20HB001TUS            | 1         | 2.27%   |
| Lenovo ThinkCentre M710q 10MQS8UK00        | 1         | 2.27%   |
| Lenovo ThinkBook 13s G3 ACN 20YA           | 1         | 2.27%   |
| Lenovo IdeaPad 320-15IKB 80XL              | 1         | 2.27%   |
| Lenovo IdeaPad 3 15ALC6 82KU               | 1         | 2.27%   |
| Lenovo IdeaCentre 510S-08IKL 90GB00E3IN    | 1         | 2.27%   |
| Lenovo G580 20150                          | 1         | 2.27%   |
| Intel Jasper Lake Client Platform          | 1         | 2.27%   |
| HUAWEI NBLB-WAX9N                          | 1         | 2.27%   |
| HUAWEI KLVL-WXX9                           | 1         | 2.27%   |
| HONOR BMH-WCX9                             | 1         | 2.27%   |
| HP ProBook 4540s                           | 1         | 2.27%   |
| HP ProBook 450 G6                          | 1         | 2.27%   |
| HP ProBook 440 G6                          | 1         | 2.27%   |
| HP ProBook 4310s                           | 1         | 2.27%   |
| HP Pavilion Notebook                       | 1         | 2.27%   |
| HP Pavilion Laptop 14-ce3xxx               | 1         | 2.27%   |
| HP Laptop 17-by3xxx                        | 1         | 2.27%   |
| HP Laptop 15s-eq0xxx                       | 1         | 2.27%   |
| HP EliteDesk 705 G1 DM                     | 1         | 2.27%   |
| HP EliteBook 840 14 inch G9 Notebook PC    | 1         | 2.27%   |
| HP 1998                                    | 1         | 2.27%   |
| Gigabyte GA-E6010N                         | 1         | 2.27%   |
| Dell Precision 5530                        | 1         | 2.27%   |
| Dell OptiPlex 3070                         | 1         | 2.27%   |
| Dell Latitude E5470                        | 1         | 2.27%   |
| Dell Inspiron 15 5510                      | 1         | 2.27%   |
| Clevo NL41MU2                              | 1         | 2.27%   |
| Chuwi UBook Pro                            | 1         | 2.27%   |
| ASUS ZenBook UX325EA_UX325EA               | 1         | 2.27%   |
| ASUS X550WA                                | 1         | 2.27%   |
| ASUS VivoBook_ASUSLaptop X510QA_X510QA     | 1         | 2.27%   |
| ASUS ROG STRIX B350-F GAMING               | 1         | 2.27%   |
| ASUS PRIME B450-PLUS                       | 1         | 2.27%   |
| ASUS P8H61-MX R2.0                         | 1         | 2.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name               | Computers | Percent |
|--------------------|-----------|---------|
| HP ProBook         | 4         | 9.09%   |
| Lenovo IdeaPad     | 2         | 4.55%   |
| HP Pavilion        | 2         | 4.55%   |
| HP Laptop          | 2         | 4.55%   |
| Acer Aspire        | 2         | 4.55%   |
| Samsung 300E4A     | 1         | 2.27%   |
| PCBOX Kant         | 1         | 2.27%   |
| Multilaser PC150   | 1         | 2.27%   |
| MSI GE62VR         | 1         | 2.27%   |
| Microsoft Surface  | 1         | 2.27%   |
| Lenovo ThinkPad    | 1         | 2.27%   |
| Lenovo ThinkCentre | 1         | 2.27%   |
| Lenovo ThinkBook   | 1         | 2.27%   |
| Lenovo IdeaCentre  | 1         | 2.27%   |
| Lenovo G580        | 1         | 2.27%   |
| Intel Jasper       | 1         | 2.27%   |
| HUAWEI NBLB-WAX9N  | 1         | 2.27%   |
| HUAWEI KLVL-WXX9   | 1         | 2.27%   |
| HONOR BMH-WCX9     | 1         | 2.27%   |
| HP EliteDesk       | 1         | 2.27%   |
| HP EliteBook       | 1         | 2.27%   |
| HP 1998            | 1         | 2.27%   |
| Gigabyte GA-E6010N | 1         | 2.27%   |
| Dell Precision     | 1         | 2.27%   |
| Dell OptiPlex      | 1         | 2.27%   |
| Dell Latitude      | 1         | 2.27%   |
| Dell Inspiron      | 1         | 2.27%   |
| Clevo NL41MU2      | 1         | 2.27%   |
| Chuwi UBook        | 1         | 2.27%   |
| ASUS ZenBook       | 1         | 2.27%   |
| ASUS X550WA        | 1         | 2.27%   |
| ASUS VivoBook      | 1         | 2.27%   |
| ASUS ROG           | 1         | 2.27%   |
| ASUS PRIME         | 1         | 2.27%   |
| ASUS P8H61-MX      | 1         | 2.27%   |
| Alienware m15      | 1         | 2.27%   |
| Unknown            | 1         | 2.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 11        | 25%     |
| 2020 | 5         | 11.36%  |
| 2022 | 4         | 9.09%   |
| 2021 | 4         | 9.09%   |
| 2018 | 4         | 9.09%   |
| 2015 | 3         | 6.82%   |
| 2012 | 3         | 6.82%   |
| 2017 | 2         | 4.55%   |
| 2016 | 2         | 4.55%   |
| 2014 | 2         | 4.55%   |
| 2011 | 2         | 4.55%   |
| 2013 | 1         | 2.27%   |
| 2009 | 1         | 2.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 31        | 70.45%  |
| Desktop  | 9         | 20.45%  |
| Tablet   | 3         | 6.82%   |
| Mini pc  | 1         | 2.27%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 40        | 90.91%  |
| Enabled  | 4         | 9.09%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 44        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 18        | 40.91%  |
| 16.01-24.0  | 8         | 18.18%  |
| 8.01-16.0   | 7         | 15.91%  |
| 32.01-64.0  | 4         | 9.09%   |
| 3.01-4.0    | 4         | 9.09%   |
| 24.01-32.0  | 1         | 2.27%   |
| 64.01-256.0 | 1         | 2.27%   |
| 1.01-2.0    | 1         | 2.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 18        | 40.91%  |
| 3.01-4.0  | 10        | 22.73%  |
| 1.01-2.0  | 9         | 20.45%  |
| 4.01-8.0  | 5         | 11.36%  |
| 8.01-16.0 | 2         | 4.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 32        | 72.73%  |
| 2      | 10        | 22.73%  |
| 5      | 1         | 2.27%   |
| 4      | 1         | 2.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 79.55%  |
| Yes       | 9         | 20.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 72.73%  |
| No        | 12        | 27.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 88.64%  |
| No        | 5         | 11.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 79.55%  |
| No        | 9         | 20.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| Russia       | 6         | 13.64%  |
| Germany      | 6         | 13.64%  |
| USA          | 5         | 11.36%  |
| India        | 3         | 6.82%   |
| Brazil       | 3         | 6.82%   |
| Portugal     | 2         | 4.55%   |
| Netherlands  | 2         | 4.55%   |
| Mexico       | 2         | 4.55%   |
| Italy        | 2         | 4.55%   |
| UK           | 1         | 2.27%   |
| Turkey       | 1         | 2.27%   |
| Sweden       | 1         | 2.27%   |
| Saudi Arabia | 1         | 2.27%   |
| Poland       | 1         | 2.27%   |
| Peru         | 1         | 2.27%   |
| Indonesia    | 1         | 2.27%   |
| Hungary      | 1         | 2.27%   |
| France       | 1         | 2.27%   |
| Ecuador      | 1         | 2.27%   |
| Colombia     | 1         | 2.27%   |
| China        | 1         | 2.27%   |
| Argentina    | 1         | 2.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Moscow                  | 3         | 6.82%   |
| Wiesbaden               | 1         | 2.27%   |
| Villingen-Schwenningen  | 1         | 2.27%   |
| Villefranche-sur-Saône | 1         | 2.27%   |
| Viareggio               | 1         | 2.27%   |
| Stockholm               | 1         | 2.27%   |
| St Petersburg           | 1         | 2.27%   |
| Shanghai                | 1         | 2.27%   |
| Salt Lake City          | 1         | 2.27%   |
| Rostov-on-Don           | 1         | 2.27%   |
| Portimao                | 1         | 2.27%   |
| Newcastle upon Tyne     | 1         | 2.27%   |
| Munich                  | 1         | 2.27%   |
| Monza                   | 1         | 2.27%   |
| Lisbon                  | 1         | 2.27%   |
| Lima                    | 1         | 2.27%   |
| Leiden                  | 1         | 2.27%   |
| Langen                  | 1         | 2.27%   |
| Lancaster               | 1         | 2.27%   |
| Jeddah                  | 1         | 2.27%   |
| Jakarta                 | 1         | 2.27%   |
| Jagiella                | 1         | 2.27%   |
| Istanbul                | 1         | 2.27%   |
| Hürth                  | 1         | 2.27%   |
| Hummelstown             | 1         | 2.27%   |
| Hamburg                 | 1         | 2.27%   |
| Guayaquil               | 1         | 2.27%   |
| Faridabad               | 1         | 2.27%   |
| Ecatepec                | 1         | 2.27%   |
| Delhi                   | 1         | 2.27%   |
| Curitiba                | 1         | 2.27%   |
| Cuernavaca              | 1         | 2.27%   |
| Córdoba                | 1         | 2.27%   |
| Chelyabinsk             | 1         | 2.27%   |
| Chandigarh              | 1         | 2.27%   |
| Budapest                | 1         | 2.27%   |
| Brasília               | 1         | 2.27%   |
| Bogotá                 | 1         | 2.27%   |
| Blumenau                | 1         | 2.27%   |
| Ashburn                 | 1         | 2.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 8      | 14.04%  |
| Samsung Electronics | 7         | 7      | 12.28%  |
| Seagate             | 4         | 5      | 7.02%   |
| SanDisk             | 4         | 4      | 7.02%   |
| Crucial             | 4         | 4      | 7.02%   |
| Toshiba             | 3         | 3      | 5.26%   |
| KIOXIA              | 3         | 3      | 5.26%   |
| SK hynix            | 2         | 2      | 3.51%   |
| Kingston            | 2         | 2      | 3.51%   |
| Intel               | 2         | 2      | 3.51%   |
| HGST                | 2         | 2      | 3.51%   |
| Hewlett-Packard     | 2         | 2      | 3.51%   |
| XrayDisk            | 1         | 1      | 1.75%   |
| Unknown             | 1         | 2      | 1.75%   |
| PNY                 | 1         | 1      | 1.75%   |
| Netac               | 1         | 1      | 1.75%   |
| Micron Technology   | 1         | 1      | 1.75%   |
| MaiChai             | 1         | 1      | 1.75%   |
| LuminouTek          | 1         | 1      | 1.75%   |
| JMicron Technology  | 1         | 1      | 1.75%   |
| Intenso             | 1         | 1      | 1.75%   |
| Hitachi             | 1         | 1      | 1.75%   |
| Fujitsu             | 1         | 1      | 1.75%   |
| China               | 1         | 1      | 1.75%   |
| BIWIN               | 1         | 1      | 1.75%   |
| ACASIS              | 1         | 2      | 1.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                            | 2         | 3.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 2         | 3.39%   |
| HP SSD S600 120GB                                   | 2         | 3.39%   |
| XrayDisk 512GB SSD                                  | 1         | 1.69%   |
| WDC WDS100T2B0C-00PXH0 1TB                          | 1         | 1.69%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 1.69%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 1         | 1.69%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                | 1         | 1.69%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB                | 1         | 1.69%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB                | 1         | 1.69%   |
| Unknown MMC Card  8GB                               | 1         | 1.69%   |
| Unknown MMC Card  32GB                              | 1         | 1.69%   |
| Toshiba MK3256GSY 320GB                             | 1         | 1.69%   |
| Toshiba DT01ACA200 2TB                              | 1         | 1.69%   |
| Toshiba DT01ACA050 500GB                            | 1         | 1.69%   |
| SK hynix PC711 NVMe 1TB                             | 1         | 1.69%   |
| SK hynix BC711 NVMe 512GB                           | 1         | 1.69%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1.69%   |
| Seagate ST3500418AS 500GB                           | 1         | 1.69%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1.69%   |
| Seagate ST1000VT001-1RE172 1TB                      | 1         | 1.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1.69%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 1         | 1.69%   |
| SanDisk SSD PLUS 120GB                              | 1         | 1.69%   |
| SanDisk SDSSDA240G 240GB                            | 1         | 1.69%   |
| SanDisk SD8TB8U512G1001 512GB SSD                   | 1         | 1.69%   |
| Samsung SSD 970 EVO Plus 500GB                      | 1         | 1.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 1         | 1.69%   |
| Samsung MZVLQ512HALU-00000 512GB                    | 1         | 1.69%   |
| Samsung MZALQ512HBLU-00BL2 512GB                    | 1         | 1.69%   |
| PNY CS1311 960GB SSD                                | 1         | 1.69%   |
| Netac SSD 256GB                                     | 1         | 1.69%   |
| Micron MTFDDAK256TBN-1AR1ZABHA 256GB SSD            | 1         | 1.69%   |
| MaiChai 512G                                        | 1         | 1.69%   |
| LuminouTek 128GB                                    | 1         | 1.69%   |
| KIOXIA KBG50ZNV512G 512GB                           | 1         | 1.69%   |
| KIOXIA KBG40ZPZ256G TOSHIBA MEMORY 256GB            | 1         | 1.69%   |
| KIOXIA KBG40ZNV512G 512GB                           | 1         | 1.69%   |
| Kingston SA400S37960G 960GB SSD                     | 1         | 1.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 26.67%  |
| Seagate | 4         | 5      | 26.67%  |
| Toshiba | 3         | 3      | 20%     |
| HGST    | 2         | 2      | 13.33%  |
| Hitachi | 1         | 1      | 6.67%   |
| Fujitsu | 1         | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Crucial           | 4         | 4      | 22.22%  |
| SanDisk           | 3         | 3      | 16.67%  |
| Kingston          | 2         | 2      | 11.11%  |
| Hewlett-Packard   | 2         | 2      | 11.11%  |
| XrayDisk          | 1         | 1      | 5.56%   |
| PNY               | 1         | 1      | 5.56%   |
| Netac             | 1         | 1      | 5.56%   |
| Micron Technology | 1         | 1      | 5.56%   |
| MaiChai           | 1         | 1      | 5.56%   |
| Intenso           | 1         | 1      | 5.56%   |
| China             | 1         | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 19        | 20     | 35.85%  |
| SSD     | 17        | 18     | 32.08%  |
| HDD     | 13        | 16     | 24.53%  |
| Unknown | 3         | 4      | 5.66%   |
| MMC     | 1         | 2      | 1.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 25        | 35     | 53.19%  |
| NVMe | 19        | 20     | 40.43%  |
| SAS  | 2         | 3      | 4.26%   |
| MMC  | 1         | 2      | 2.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 16        | 20     | 53.33%  |
| 0.51-1.0   | 12        | 12     | 40%     |
| 1.01-2.0   | 2         | 2      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 16        | 36.36%  |
| 251-500    | 13        | 29.55%  |
| 501-1000   | 9         | 20.45%  |
| 1001-2000  | 2         | 4.55%   |
| 21-50      | 1         | 2.27%   |
| 2001-3000  | 1         | 2.27%   |
| 1-20       | 1         | 2.27%   |
| 51-100     | 1         | 2.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 17        | 38.64%  |
| 251-500   | 8         | 18.18%  |
| 21-50     | 8         | 18.18%  |
| 51-100    | 7         | 15.91%  |
| 101-250   | 3         | 6.82%   |
| 1001-2000 | 1         | 2.27%   |

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
| Detected | 33        | 45     | 73.33%  |
| Works    | 12        | 15     | 26.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 28        | 50.91%  |
| AMD                 | 9         | 16.36%  |
| Samsung Electronics | 7         | 12.73%  |
| SanDisk             | 5         | 9.09%   |
| KIOXIA              | 3         | 5.45%   |
| SK hynix            | 2         | 3.64%   |
| INNOGRIT            | 1         | 1.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 8         | 13.33%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 5%      |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 2         | 3.33%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2         | 3.33%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 2         | 3.33%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 3.33%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 2         | 3.33%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 3.33%   |
| Intel SSD 660P Series                                                                   | 2         | 3.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 3.33%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 2         | 3.33%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 3.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 3.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2         | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 3.33%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 3.33%   |
| SanDisk NVMe Controller                                                                 | 1         | 1.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 1.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 1.67%   |
| KIOXIA Non-Volatile memory controller                                                   | 1         | 1.67%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 1         | 1.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1         | 1.67%   |
| Intel SATA Controller [RAID mode]                                                       | 1         | 1.67%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 1         | 1.67%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 1.67%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 1.67%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 1.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 1.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 1.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1         | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.67%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 1.67%   |
| INNOGRIT Non-Volatile memory controller                                                 | 1         | 1.67%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1         | 1.67%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1         | 1.67%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1         | 1.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 31        | 55.36%  |
| NVMe | 19        | 33.93%  |
| RAID | 5         | 8.93%   |
| IDE  | 1         | 1.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 31        | 70.45%  |
| AMD    | 13        | 29.55%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 4.55%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 4.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 4.55%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 2.27%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 2.27%   |
| Intel Core i7-7700T CPU @ 2.90GHz             | 1         | 2.27%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 2.27%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 2.27%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 2.27%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 2.27%   |
| Intel Core i5-9400T CPU @ 1.80GHz             | 1         | 2.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 2.27%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 1         | 2.27%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 2.27%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 2.27%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 2.27%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz            | 1         | 2.27%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 1         | 2.27%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 1         | 2.27%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz          | 1         | 2.27%   |
| Intel Celeron N5105 @ 2.00GHz                 | 1         | 2.27%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 1         | 2.27%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 2.27%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 1         | 2.27%   |
| Intel Celeron CPU B830 @ 1.80GHz              | 1         | 2.27%   |
| Intel 12th Gen Core i7-1255U                  | 1         | 2.27%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 2.27%   |
| Intel 11th Gen Core i7-11390H @ 3.40GHz       | 1         | 2.27%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 1         | 2.27%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 2.27%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 1         | 2.27%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 2.27%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 2.27%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.27%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 1         | 2.27%   |
| AMD E1-6010 APU with AMD Radeon R2 Graphics   | 1         | 2.27%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 1         | 2.27%   |
| AMD A8 PRO-7600B R7, 10 Compute Cores 4C+6G   | 1         | 2.27%   |
| AMD A4-9120e RADEON R3, 4 COMPUTE CORES 2C+2G | 1         | 2.27%   |
| AMD A4-6210 APU with AMD Radeon R3 Graphics   | 1         | 2.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 11        | 25%     |
| Intel Core i7    | 6         | 13.64%  |
| Other            | 5         | 11.36%  |
| Intel Celeron    | 5         | 11.36%  |
| AMD Ryzen 5      | 4         | 9.09%   |
| Intel Core i3    | 2         | 4.55%   |
| AMD Ryzen 7      | 2         | 4.55%   |
| AMD A8           | 2         | 4.55%   |
| AMD A4           | 2         | 4.55%   |
| Intel Pentium    | 1         | 2.27%   |
| Intel Core 2 Duo | 1         | 2.27%   |
| AMD Ryzen 3      | 1         | 2.27%   |
| AMD E1           | 1         | 2.27%   |
| AMD A12          | 1         | 2.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 22        | 50%     |
| 2      | 13        | 29.55%  |
| 6      | 5         | 11.36%  |
| 8      | 3         | 6.82%   |
| 10     | 1         | 2.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 44        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 29        | 65.91%  |
| 1      | 15        | 34.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 44        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 61.36%  |
| 0x806ec    | 2         | 4.55%   |
| 0x706e5    | 2         | 4.55%   |
| 0x906e9    | 1         | 2.27%   |
| 0x906a4    | 1         | 2.27%   |
| 0x806eb    | 1         | 2.27%   |
| 0x806d1    | 1         | 2.27%   |
| 0x806c1    | 1         | 2.27%   |
| 0x706a1    | 1         | 2.27%   |
| 0x306a9    | 1         | 2.27%   |
| 0x1067a    | 1         | 2.27%   |
| 0x0a50000d | 1         | 2.27%   |
| 0x08600106 | 1         | 2.27%   |
| 0x07030106 | 1         | 2.27%   |
| 0x06006705 | 1         | 2.27%   |
| 0x0600611a | 1         | 2.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 9         | 20.45%  |
| Icelake          | 4         | 9.09%   |
| TigerLake        | 3         | 6.82%   |
| SandyBridge      | 3         | 6.82%   |
| Puma             | 3         | 6.82%   |
| Unknown          | 3         | 6.82%   |
| Zen 3            | 2         | 4.55%   |
| Skylake          | 2         | 4.55%   |
| Silvermont       | 2         | 4.55%   |
| IvyBridge        | 2         | 4.55%   |
| Goldmont plus    | 2         | 4.55%   |
| Excavator        | 2         | 4.55%   |
| Zen+             | 1         | 2.27%   |
| Zen 2            | 1         | 2.27%   |
| Zen              | 1         | 2.27%   |
| Steamroller      | 1         | 2.27%   |
| Penryn           | 1         | 2.27%   |
| Haswell          | 1         | 2.27%   |
| Alderlake Hybrid | 1         | 2.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 28        | 52.83%  |
| AMD    | 16        | 30.19%  |
| Nvidia | 9         | 16.98%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 3         | 5.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 2         | 3.7%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 2         | 3.7%    |
| Intel HD Graphics 630                                                                 | 2         | 3.7%    |
| Intel HD Graphics 620                                                                 | 2         | 3.7%    |
| Intel HD Graphics 530                                                                 | 2         | 3.7%    |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 3.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 2         | 3.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 2         | 3.7%    |
| AMD Lucienne                                                                          | 2         | 3.7%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 2         | 3.7%    |
| Nvidia TU117M [GeForce MX450]                                                         | 1         | 1.85%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 1         | 1.85%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 1.85%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 1         | 1.85%   |
| Nvidia GM108M [GeForce MX130]                                                         | 1         | 1.85%   |
| Nvidia GM108M [GeForce 920MX]                                                         | 1         | 1.85%   |
| Nvidia GM108GLM [Quadro M520 Mobile]                                                  | 1         | 1.85%   |
| Nvidia GF119M [GeForce GT 520MX]                                                      | 1         | 1.85%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 1         | 1.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 1.85%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 1.85%   |
| Intel JasperLake [UHD Graphics]                                                       | 1         | 1.85%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                | 1         | 1.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 1.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 1         | 1.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 1         | 1.85%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 1         | 1.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 1         | 1.85%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                | 1         | 1.85%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 1         | 1.85%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.85%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 1         | 1.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 1         | 1.85%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                     | 1         | 1.85%   |
| AMD Renoir                                                                            | 1         | 1.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 1         | 1.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 1.85%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 1         | 1.85%   |
| AMD Mullins [Radeon R3 Graphics]                                                      | 1         | 1.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 19        | 43.18%  |
| 1 x AMD        | 14        | 31.82%  |
| Intel + Nvidia | 8         | 18.18%  |
| 2 x AMD        | 1         | 2.27%   |
| 1 x Nvidia     | 1         | 2.27%   |
| Intel + AMD    | 1         | 2.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 39        | 88.64%  |
| Proprietary | 3         | 6.82%   |
| Unknown     | 2         | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 81.82%  |
| 1.01-2.0   | 3         | 6.82%   |
| 0.01-0.5   | 3         | 6.82%   |
| 7.01-8.0   | 1         | 2.27%   |
| 0.51-1.0   | 1         | 2.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 7         | 14.58%  |
| LG Display              | 6         | 12.5%   |
| Chimei Innolux          | 6         | 12.5%   |
| AU Optronics            | 4         | 8.33%   |
| Sharp                   | 3         | 6.25%   |
| Samsung Electronics     | 3         | 6.25%   |
| Dell                    | 3         | 6.25%   |
| PANDA                   | 2         | 4.17%   |
| Hewlett-Packard         | 2         | 4.17%   |
| BenQ                    | 2         | 4.17%   |
| ___                     | 1         | 2.08%   |
| Vizio                   | 1         | 2.08%   |
| Unknown                 | 1         | 2.08%   |
| Positivo                | 1         | 2.08%   |
| Lenovo                  | 1         | 2.08%   |
| INS                     | 1         | 2.08%   |
| InfoVision              | 1         | 2.08%   |
| Goldstar                | 1         | 2.08%   |
| Chi Mei Optoelectronics | 1         | 2.08%   |
| Acer                    | 1         | 2.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| ___ LCDTV16 ___3393 1366x768                                             | 1         | 2%      |
| Vizio E420VL VIZ0057 1920x1080 930x520mm 41.9-inch                       | 1         | 2%      |
| Unknown LCDTV16 3393 1920x1080 1600x900mm 72.3-inch                      | 1         | 2%      |
| Sharp LCD Monitor SHP151C 1920x1080 344x194mm 15.5-inch                  | 1         | 2%      |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 1         | 2%      |
| Sharp LCD Monitor SHP1482 2880x1920 259x173mm 12.3-inch                  | 1         | 2%      |
| Samsung Electronics LCD Monitor SEC4249 1366x768 309x174mm 14.0-inch     | 1         | 2%      |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 1         | 2%      |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch    | 1         | 2%      |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 700x390mm 31.5-inch    | 1         | 2%      |
| Positivo MC35120QWQHD NON3503 3440x1440 819x346mm 35.0-inch              | 1         | 2%      |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch                  | 1         | 2%      |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 1         | 2%      |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch             | 1         | 2%      |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch              | 1         | 2%      |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 1         | 2%      |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 1         | 2%      |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 2%      |
| LG Display LCD Monitor LGD01DA 1366x768 294x166mm 13.3-inch              | 1         | 2%      |
| Lenovo LI2215sD LEN65CC 1920x1080 476x267mm 21.5-inch                    | 1         | 2%      |
| INS NS24DF310NA19 INS2483 1920x1080 521x293mm 23.5-inch                  | 1         | 2%      |
| InfoVision LCD Monitor IVO854A 1920x1200 286x179mm 13.3-inch             | 1         | 2%      |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch              | 1         | 2%      |
| Hewlett-Packard E201 HWP305C 1600x900 443x249mm 20.0-inch                | 1         | 2%      |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 1         | 2%      |
| Dell P2421 DELA172 1920x1200 518x324mm 24.1-inch                         | 1         | 2%      |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 1         | 2%      |
| Dell P2213 DELF043 1680x1050 473x296mm 22.0-inch                         | 1         | 2%      |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                        | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN175E 1920x1080 381x214mm 17.2-inch         | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN152E 1920x1080 344x193mm 15.5-inch         | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN1502 1920x1080 344x193mm 15.5-inch         | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 2%      |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 2%      |
| BOE LCD Monitor BOE09D3 1920x1080 344x194mm 15.5-inch                    | 1         | 2%      |
| BOE LCD Monitor BOE0936 1920x1080 344x194mm 15.5-inch                    | 1         | 2%      |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 1         | 2%      |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 1         | 2%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 24        | 51.06%  |
| 1366x768 (WXGA)    | 11        | 23.4%   |
| 1600x900 (HD+)     | 3         | 6.38%   |
| 3440x1440          | 1         | 2.13%   |
| 2880x1920          | 1         | 2.13%   |
| 2736x1824          | 1         | 2.13%   |
| 2560x1600          | 1         | 2.13%   |
| 2160x1440          | 1         | 2.13%   |
| 1920x1280          | 1         | 2.13%   |
| 1920x1200 (WUXGA)  | 1         | 2.13%   |
| 1680x1050 (WSXGA+) | 1         | 2.13%   |
| 1280x1024 (SXGA)   | 1         | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 15        | 30%     |
| 14      | 6         | 12%     |
| 13      | 6         | 12%     |
| 24      | 4         | 8%      |
| 21      | 3         | 6%      |
| 12      | 3         | 6%      |
| 17      | 2         | 4%      |
| 72      | 1         | 2%      |
| 60      | 1         | 2%      |
| 54      | 1         | 2%      |
| 35      | 1         | 2%      |
| 29      | 1         | 2%      |
| 23      | 1         | 2%      |
| 22      | 1         | 2%      |
| 20      | 1         | 2%      |
| 19      | 1         | 2%      |
| 11      | 1         | 2%      |
| Unknown | 1         | 2%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 46.94%  |
| 201-300     | 8         | 16.33%  |
| 501-600     | 5         | 10.2%   |
| 401-500     | 4         | 8.16%   |
| 351-400     | 3         | 6.12%   |
| 1001-1500   | 2         | 4.08%   |
| 801-900     | 1         | 2.04%   |
| 601-700     | 1         | 2.04%   |
| 1501-2000   | 1         | 2.04%   |
| Unknown     | 1         | 2.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 35        | 77.78%  |
| 3/2   | 4         | 8.89%   |
| 16/10 | 4         | 8.89%   |
| 6/5   | 1         | 2.22%   |
| 21/9  | 1         | 2.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 30%     |
| 81-90          | 9         | 18%     |
| 201-250        | 7         | 14%     |
| 71-80          | 4         | 8%      |
| More than 1000 | 3         | 6%      |
| 151-200        | 3         | 6%      |
| 61-70          | 2         | 4%      |
| 351-500        | 2         | 4%      |
| 121-130        | 2         | 4%      |
| 51-60          | 1         | 2%      |
| 251-300        | 1         | 2%      |
| Unknown        | 1         | 2%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 17        | 34.69%  |
| 101-120       | 15        | 30.61%  |
| 51-100        | 8         | 16.33%  |
| 161-240       | 4         | 8.16%   |
| 1-50          | 3         | 6.12%   |
| More than 240 | 1         | 2.04%   |
| Unknown       | 1         | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 34        | 77.27%  |
| 2     | 7         | 15.91%  |
| 0     | 2         | 4.55%   |
| 3     | 1         | 2.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 25        | 35.71%  |
| Intel                    | 21        | 30%     |
| Qualcomm Atheros         | 7         | 10%     |
| Broadcom                 | 5         | 7.14%   |
| TP-Link                  | 2         | 2.86%   |
| Qualcomm                 | 2         | 2.86%   |
| Huawei Technologies      | 2         | 2.86%   |
| Sierra Wireless          | 1         | 1.43%   |
| Ralink Technology        | 1         | 1.43%   |
| NetGear                  | 1         | 1.43%   |
| Marvell Technology Group | 1         | 1.43%   |
| Broadcom Limited         | 1         | 1.43%   |
| ASIX Electronics         | 1         | 1.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 17.72%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 5.06%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 3.8%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 2         | 2.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 2.53%   |
| Intel Wireless 8265 / 8275                                        | 2         | 2.53%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 2.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 2.53%   |
| Huawei ANE-LX1                                                    | 2         | 2.53%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.27%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 1.27%   |
| Sierra Wireless EM7455                                            | 1         | 1.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.27%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 1.27%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.27%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 1.27%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 1         | 1.27%   |
| Qualcomm Fairphone 4 5G                                           | 1         | 1.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.27%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.27%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.27%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.27%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]           | 1         | 1.27%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.27%   |
| Intel Wireless-AC 9260                                            | 1         | 1.27%   |
| Intel Wireless 8260                                               | 1         | 1.27%   |
| Intel Wireless 3165                                               | 1         | 1.27%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.27%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.27%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 1.27%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.27%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.27%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 44.19%  |
| Realtek Semiconductor | 10        | 23.26%  |
| Qualcomm Atheros      | 5         | 11.63%  |
| Broadcom              | 3         | 6.98%   |
| TP-Link               | 1         | 2.33%   |
| Sierra Wireless       | 1         | 2.33%   |
| Ralink Technology     | 1         | 2.33%   |
| Qualcomm              | 1         | 2.33%   |
| NetGear               | 1         | 2.33%   |
| Broadcom Limited      | 1         | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 9.3%    |
| Intel Wi-Fi 6 AX201                                            | 3         | 6.98%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 4.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 4.65%   |
| Intel Wireless 8265 / 8275                                     | 2         | 4.65%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 4.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 4.65%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 2.33%   |
| Sierra Wireless EM7455                                         | 1         | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 2.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 2.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 2.33%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 2.33%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 2.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 2.33%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]        | 1         | 2.33%   |
| Intel Wireless-AC 9260                                         | 1         | 2.33%   |
| Intel Wireless 8260                                            | 1         | 2.33%   |
| Intel Wireless 3165                                            | 1         | 2.33%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 2.33%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 2.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 2.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 2.33%   |
| Intel Centrino Wireless-N 130                                  | 1         | 2.33%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 1         | 2.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 1         | 2.33%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 1         | 2.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1         | 2.33%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1         | 2.33%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 19        | 52.78%  |
| Intel                    | 6         | 16.67%  |
| Qualcomm Atheros         | 3         | 8.33%   |
| Huawei Technologies      | 2         | 5.56%   |
| Broadcom                 | 2         | 5.56%   |
| TP-Link                  | 1         | 2.78%   |
| Qualcomm                 | 1         | 2.78%   |
| Marvell Technology Group | 1         | 2.78%   |
| ASIX Electronics         | 1         | 2.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 38.89%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 5.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 5.56%   |
| Huawei ANE-LX1                                                    | 2         | 5.56%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 2.78%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 2.78%   |
| Qualcomm Fairphone 4 5G                                           | 1         | 2.78%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2.78%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.78%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 2.78%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.78%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.78%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.78%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.78%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 2.78%   |
| Broadcom NetXtreme II BCM5706 Gigabit Ethernet                    | 1         | 2.78%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 2.78%   |
| ASIX AX88772B                                                     | 1         | 2.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 54.93%  |
| Ethernet | 32        | 45.07%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 79.07%  |
| Ethernet | 9         | 20.93%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 21        | 47.73%  |
| 1     | 19        | 43.18%  |
| 3     | 2         | 4.55%   |
| 0     | 2         | 4.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 33        | 75%     |
| Yes  | 11        | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 50%     |
| Realtek Semiconductor           | 6         | 16.67%  |
| Qualcomm Atheros Communications | 4         | 11.11%  |
| Foxconn / Hon Hai               | 3         | 8.33%   |
| Realtek                         | 1         | 2.78%   |
| Lite-On Technology              | 1         | 2.78%   |
| IMC Networks                    | 1         | 2.78%   |
| Hewlett-Packard                 | 1         | 2.78%   |
| Cambridge Silicon Radio         | 1         | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 13.89%  |
| Intel AX201 Bluetooth                               | 5         | 13.89%  |
| Realtek Bluetooth Radio                             | 4         | 11.11%  |
| Intel Bluetooth wireless interface                  | 4         | 11.11%  |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 5.56%   |
| Intel Bluetooth Device                              | 2         | 5.56%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 5.56%   |
| Realtek Bluetooth Radio                             | 1         | 2.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2.78%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.78%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 2.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.78%   |
| Intel AX200 Bluetooth                               | 1         | 2.78%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.78%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.78%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 2.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 31        | 54.39%  |
| AMD                   | 15        | 26.32%  |
| C-Media Electronics   | 4         | 7.02%   |
| Nvidia                | 3         | 5.26%   |
| Trust                 | 1         | 1.75%   |
| Realtek Semiconductor | 1         | 1.75%   |
| Hewlett-Packard       | 1         | 1.75%   |
| GN Netcom             | 1         | 1.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 9.86%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 7.04%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 5.63%   |
| AMD FCH Azalia Controller                                                  | 4         | 5.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 4.23%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 4.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 4.23%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3         | 4.23%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 2.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 2.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 2.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 2.82%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 2.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.82%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 2.82%   |
| Trust GXT 232 Microphone                                                   | 1         | 1.41%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.41%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 1.41%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 1.41%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.41%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.41%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.41%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.41%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 1.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.41%   |
| Hewlett-Packard USB Audio                                                  | 1         | 1.41%   |
| GN Netcom Jabra Engage 75                                                  | 1         | 1.41%   |
| C-Media Electronics USB Advanced Audio Device                              | 1         | 1.41%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 1.41%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 1.41%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1         | 1.41%   |
| AMD High Definition Audio Controller                                       | 1         | 1.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 28.57%  |
| Micron Technology   | 4         | 28.57%  |
| SK hynix            | 2         | 14.29%  |
| Unknown (ABCD)      | 1         | 7.14%   |
| Kingston            | 1         | 7.14%   |
| G.Skill             | 1         | 7.14%   |
| A-DATA Technology   | 1         | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 7.14%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                     | 1         | 7.14%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 7.14%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 7.14%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                     | 1         | 7.14%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 7.14%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s              | 1         | 7.14%   |
| Micron RAM MT53E1G32D2NP-046 8GB Row Of Chips LPDDR4 4267MT/s    | 1         | 7.14%   |
| Micron RAM Module 8GB SODIMM DDR4 2667MT/s                       | 1         | 7.14%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 7.14%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 7.14%   |
| Kingston RAM HX318C10F/8 8GB DIMM DDR3 1600MT/s                  | 1         | 7.14%   |
| G.Skill RAM F4-3200C22-32GRS 32GB SODIMM DDR4 3200MT/s           | 1         | 7.14%   |
| A-DATA RAM Module 4GB DIMM DDR3 1600MT/s                         | 1         | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 6         | 46.15%  |
| LPDDR4 | 3         | 23.08%  |
| DDR3   | 3         | 23.08%  |
| DDR5   | 1         | 7.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 9         | 69.23%  |
| Row Of Chips | 2         | 15.38%  |
| DIMM         | 2         | 15.38%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 9         | 69.23%  |
| 32768 | 1         | 7.69%   |
| 16384 | 1         | 7.69%   |
| 4096  | 1         | 7.69%   |
| 2048  | 1         | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 4         | 28.57%  |
| 4267  | 2         | 14.29%  |
| 3200  | 2         | 14.29%  |
| 1600  | 2         | 14.29%  |
| 4800  | 1         | 7.14%   |
| 2400  | 1         | 7.14%   |
| 2000  | 1         | 7.14%   |
| 1333  | 1         | 7.14%   |

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
| Chicony Electronics                    | 6         | 17.65%  |
| Realtek Semiconductor                  | 5         | 14.71%  |
| Quanta                                 | 5         | 14.71%  |
| Microdia                               | 2         | 5.88%   |
| IMC Networks                           | 2         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.88%   |
| Bison Electronics                      | 2         | 5.88%   |
| Sunplus Technology                     | 1         | 2.94%   |
| Sunplus Innovation Technology          | 1         | 2.94%   |
| Silicon Motion                         | 1         | 2.94%   |
| Luxvisions Innotech Limited            | 1         | 2.94%   |
| Logitech                               | 1         | 2.94%   |
| Lite-On Technology                     | 1         | 2.94%   |
| Generalplus Technology                 | 1         | 2.94%   |
| Cubeternet                             | 1         | 2.94%   |
| Alcor Micro                            | 1         | 2.94%   |
| Acer                                   | 1         | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                     | 2         | 5.71%   |
| Quanta HP HD Camera                              | 2         | 5.71%   |
| Bison Integrated Camera                          | 2         | 5.71%   |
| Sunplus 1.3M HD WebCam                           | 1         | 2.86%   |
| Sunplus Integrated_Webcam_HD                     | 1         | 2.86%   |
| Silicon Motion WebCam SC-03FFL11939N             | 1         | 2.86%   |
| Realtek Front Camera                             | 1         | 2.86%   |
| Realtek EasyCamera                               | 1         | 2.86%   |
| Realtek Back Camera                              | 1         | 2.86%   |
| Realtek Acer 640 x 480 laptop camera             | 1         | 2.86%   |
| Quanta USB2.0 HD UVC WebCam                      | 1         | 2.86%   |
| Quanta HP TrueVision HD Camera                   | 1         | 2.86%   |
| Quanta HD Camera                                 | 1         | 2.86%   |
| Microdia Webcam Vitade AF                        | 1         | 2.86%   |
| Microdia Integrated_Webcam_HD                    | 1         | 2.86%   |
| Luxvisions Innotech Limited HP 5MP Camera        | 1         | 2.86%   |
| Logitech C922 Pro Stream Webcam                  | 1         | 2.86%   |
| Lite-On HP Wide Vision HD Camera                 | 1         | 2.86%   |
| IMC Networks VGA UVC WebCam                      | 1         | 2.86%   |
| IMC Networks ov9734_azurewave_camera             | 1         | 2.86%   |
| Generalplus 808 Camera #9 (web-cam mode)         | 1         | 2.86%   |
| Cubeternet USB2.0 Camera                         | 1         | 2.86%   |
| Chicony USB2.0 VGA UVC WebCam                    | 1         | 2.86%   |
| Chicony Lenovo EasyCamera                        | 1         | 2.86%   |
| Chicony Integrated Camera                        | 1         | 2.86%   |
| Chicony HP Truevision HD                         | 1         | 2.86%   |
| Chicony HP HD Webcam [Fixed]                     | 1         | 2.86%   |
| Chicony CNF8243 Webcam                           | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 1         | 2.86%   |
| Alcor Micro USB 2.0 Camera                       | 1         | 2.86%   |
| Acer BisonCam,NB Pro                             | 1         | 2.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 3         | 37.5%   |
| Validity Sensors           | 2         | 25%     |
| Synaptics                  | 2         | 25%     |
| Elan Microelectronics      | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 37.5%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 12.5%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 12.5%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 12.5%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 12.5%   |
| Elan ELAN:Fingerprint                                                      | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./images/line_chart/chipcard_vendor.svg)

| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)

![Chipcard Model](./images/line_chart/chipcard_model.svg)

| Model         | Computers | Percent |
|---------------|-----------|---------|
| Broadcom 5880 | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 28        | 63.64%  |
| 1     | 13        | 29.55%  |
| 2     | 3         | 6.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 8         | 42.11%  |
| Multimedia controller    | 3         | 15.79%  |
| Graphics card            | 3         | 15.79%  |
| Net/wireless             | 2         | 10.53%  |
| Net/ethernet             | 1         | 5.26%   |
| Communication controller | 1         | 5.26%   |
| Chipcard                 | 1         | 5.26%   |

