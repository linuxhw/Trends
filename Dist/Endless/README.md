Endless - Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Endless/Desktop/README.md) and [notebooks](/Dist/Endless/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: Feb, 2023.

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

| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Endless 5.0.0         | 19        | 45.24%  |
| Endless 4.0.13        | 9         | 21.43%  |
| Endless 3.9.7         | 4         | 9.52%   |
| Endless 4.0.14        | 3         | 7.14%   |
| Endless 5.0.1         | 2         | 4.76%   |
| Endless 4.0.10        | 1         | 2.38%   |
| Endless 3.9.3-nexthw1 | 1         | 2.38%   |
| Endless 3.8.7-nexthw2 | 1         | 2.38%   |
| Endless 3.8.3-nexthw1 | 1         | 2.38%   |
| Endless 3.4.0         | 1         | 2.38%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Endless | 42        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-47-generic | 21        | 50%     |
| 5.11.0-35-generic | 13        | 30.95%  |
| 5.8.0-14-generic  | 5         | 11.9%   |
| 5.6.0-7-generic   | 1         | 2.38%   |
| 5.11.0-12-generic | 1         | 2.38%   |
| 4.15.0-15-generic | 1         | 2.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 21        | 50%     |
| 5.11.0  | 14        | 33.33%  |
| 5.8.0   | 5         | 11.9%   |
| 5.6.0   | 1         | 2.38%   |
| 4.15.0  | 1         | 2.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 21        | 50%     |
| 5.11    | 14        | 33.33%  |
| 5.8     | 5         | 11.9%   |
| 5.6     | 1         | 2.38%   |
| 4.15    | 1         | 2.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 42        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name  | Computers | Percent |
|-------|-----------|---------|
| GNOME | 42        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 21        | 50%     |
| Wayland | 21        | 50%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 42        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 18        | 42.86%  |
| pt_BR | 11        | 26.19%  |
| de_DE | 3         | 7.14%   |
| hu_HU | 2         | 4.76%   |
| tr_TR | 1         | 2.38%   |
| ru_UA | 1         | 2.38%   |
| ru_RU | 1         | 2.38%   |
| nl_NL | 1         | 2.38%   |
| it_IT | 1         | 2.38%   |
| es_CO | 1         | 2.38%   |
| da_DK | 1         | 2.38%   |
| cs_CZ | 1         | 2.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 29        | 69.05%  |
| BIOS | 13        | 30.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type | Computers | Percent |
|------|-----------|---------|
| Ext4 | 42        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 42        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| ASUSTek Computer | 15        | 35.71%  |
| Lenovo           | 7         | 16.67%  |
| Acer             | 7         | 16.67%  |
| Dell             | 6         | 14.29%  |
| Hewlett-Packard  | 4         | 9.52%   |
| Toshiba          | 1         | 2.38%   |
| Microtech        | 1         | 2.38%   |
| Unknown          | 1         | 2.38%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop X515JA_X515JA     | 3         | 7.14%   |
| Lenovo IdeaPad 1 15ADA7 82R1               | 2         | 4.76%   |
| ASUS VivoBook_ASUSLaptop X515DA_X515DA     | 2         | 4.76%   |
| Acer Nitro AN515-54                        | 2         | 4.76%   |
| Toshiba Satellite L450                     | 1         | 2.38%   |
| Microtech CoreBook                         | 1         | 2.38%   |
| Lenovo ThinkPad W520 4284Y54               | 1         | 2.38%   |
| Lenovo ThinkPad T430 2347BS4               | 1         | 2.38%   |
| Lenovo ThinkCentre M57p 6073AG7            | 1         | 2.38%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK      | 1         | 2.38%   |
| Lenovo IdeaPad 110-14AST 80TQ              | 1         | 2.38%   |
| HP Stream Notebook PC 14                   | 1         | 2.38%   |
| HP Notebook                                | 1         | 2.38%   |
| HP 290 G1 SFF Business PC                  | 1         | 2.38%   |
| HP 250 G5 Notebook PC                      | 1         | 2.38%   |
| Dell Vostro 3446                           | 1         | 2.38%   |
| Dell OptiPlex 755                          | 1         | 2.38%   |
| Dell OptiPlex 390                          | 1         | 2.38%   |
| Dell OptiPlex 330                          | 1         | 2.38%   |
| Dell Latitude E6440                        | 1         | 2.38%   |
| Dell Inspiron 5523                         | 1         | 2.38%   |
| ASUS ZenBook UX431DA_UM431DA               | 1         | 2.38%   |
| ASUS X541UAK                               | 1         | 2.38%   |
| ASUS X540NA                                | 1         | 2.38%   |
| ASUS X200MA                                | 1         | 2.38%   |
| ASUS VivoBook_ASUSLaptop X515MA_X515MA     | 1         | 2.38%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA     | 1         | 2.38%   |
| ASUS VivoBook_ASUSLaptop E410MAB_E410MA    | 1         | 2.38%   |
| ASUS VivoBook 12_ASUS Laptop E203MA_E203MA | 1         | 2.38%   |
| ASUS Vivo AIO 16 V161GAR_V161GAR           | 1         | 2.38%   |
| ASUS ROG STRIX X570-E GAMING               | 1         | 2.38%   |
| Acer Aspire ES1-572                        | 1         | 2.38%   |
| Acer Aspire E5-476G                        | 1         | 2.38%   |
| Acer Aspire A517-51                        | 1         | 2.38%   |
| Acer Aspire A515-51G                       | 1         | 2.38%   |
| Acer Aspire A315-21                        | 1         | 2.38%   |
| Unknown                                    | 1         | 2.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS VivoBook      | 9         | 21.43%  |
| Acer Aspire        | 5         | 11.9%   |
| Lenovo IdeaPad     | 4         | 9.52%   |
| Dell OptiPlex      | 3         | 7.14%   |
| Lenovo ThinkPad    | 2         | 4.76%   |
| Acer Nitro         | 2         | 4.76%   |
| Toshiba Satellite  | 1         | 2.38%   |
| Microtech CoreBook | 1         | 2.38%   |
| Lenovo ThinkCentre | 1         | 2.38%   |
| HP Stream          | 1         | 2.38%   |
| HP Notebook        | 1         | 2.38%   |
| HP 290             | 1         | 2.38%   |
| HP 250             | 1         | 2.38%   |
| Dell Vostro        | 1         | 2.38%   |
| Dell Latitude      | 1         | 2.38%   |
| Dell Inspiron      | 1         | 2.38%   |
| ASUS ZenBook       | 1         | 2.38%   |
| ASUS X541UAK       | 1         | 2.38%   |
| ASUS X540NA        | 1         | 2.38%   |
| ASUS X200MA        | 1         | 2.38%   |
| ASUS Vivo          | 1         | 2.38%   |
| ASUS ROG           | 1         | 2.38%   |
| Unknown            | 1         | 2.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 6         | 14.29%  |
| 2019 | 6         | 14.29%  |
| 2020 | 5         | 11.9%   |
| 2017 | 5         | 11.9%   |
| 2016 | 3         | 7.14%   |
| 2014 | 3         | 7.14%   |
| 2022 | 2         | 4.76%   |
| 2018 | 2         | 4.76%   |
| 2012 | 2         | 4.76%   |
| 2011 | 2         | 4.76%   |
| 2008 | 2         | 4.76%   |
| 2015 | 1         | 2.38%   |
| 2013 | 1         | 2.38%   |
| 2009 | 1         | 2.38%   |
| 2007 | 1         | 2.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 34        | 80.95%  |
| Desktop    | 7         | 16.67%  |
| All in one | 1         | 2.38%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 34        | 80.95%  |
| Enabled  | 8         | 19.05%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 42        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 18        | 42.86%  |
| 3.01-4.0   | 15        | 35.71%  |
| 16.01-24.0 | 4         | 9.52%   |
| 1.01-2.0   | 2         | 4.76%   |
| 8.01-16.0  | 2         | 4.76%   |
| 2.01-3.0   | 1         | 2.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 21        | 50%     |
| 2.01-3.0 | 11        | 26.19%  |
| 0.51-1.0 | 8         | 19.05%  |
| 4.01-8.0 | 2         | 4.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 71.43%  |
| 2      | 11        | 26.19%  |
| 3      | 1         | 2.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 71.43%  |
| Yes       | 12        | 28.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 69.05%  |
| No        | 13        | 30.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 90.48%  |
| No        | 4         | 9.52%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 76.19%  |
| No        | 10        | 23.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country     | Computers | Percent |
|-------------|-----------|---------|
| Brazil      | 11        | 26.19%  |
| USA         | 4         | 9.52%   |
| Indonesia   | 4         | 9.52%   |
| Germany     | 4         | 9.52%   |
| Russia      | 3         | 7.14%   |
| Hungary     | 3         | 7.14%   |
| Turkey      | 1         | 2.38%   |
| Poland      | 1         | 2.38%   |
| Philippines | 1         | 2.38%   |
| Netherlands | 1         | 2.38%   |
| Italy       | 1         | 2.38%   |
| India       | 1         | 2.38%   |
| Greece      | 1         | 2.38%   |
| Denmark     | 1         | 2.38%   |
| Czechia     | 1         | 2.38%   |
| Colombia    | 1         | 2.38%   |
| Azerbaijan  | 1         | 2.38%   |
| Australia   | 1         | 2.38%   |
| Algeria     | 1         | 2.38%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City               | Computers | Percent |
|--------------------|-----------|---------|
| Depok              | 3         | 7.14%   |
| Rio de Janeiro     | 2         | 4.76%   |
| Moscow             | 2         | 4.76%   |
| Daytona Beach      | 2         | 4.76%   |
| Wuppertal          | 1         | 2.38%   |
| Warsaw             | 1         | 2.38%   |
| Volta Redonda      | 1         | 2.38%   |
| Tolga              | 1         | 2.38%   |
| Szombathely        | 1         | 2.38%   |
| Straubing          | 1         | 2.38%   |
| Seminole           | 1         | 2.38%   |
| Sao Paulo          | 1         | 2.38%   |
| Rokan              | 1         | 2.38%   |
| Ribeirao das Neves | 1         | 2.38%   |
| Porto Xavier       | 1         | 2.38%   |
| Porto Alegre       | 1         | 2.38%   |
| Paranavai          | 1         | 2.38%   |
| Kassel             | 1         | 2.38%   |
| Istanbul           | 1         | 2.38%   |
| Hueckelhoven       | 1         | 2.38%   |
| Guaruja            | 1         | 2.38%   |
| Gaglianico         | 1         | 2.38%   |
| Francisco Morato   | 1         | 2.38%   |
| Eureka Springs     | 1         | 2.38%   |
| Enkhuizen          | 1         | 2.38%   |
| Elista             | 1         | 2.38%   |
| Dunaújváros      | 1         | 2.38%   |
| Dianalund          | 1         | 2.38%   |
| Cesky Brod         | 1         | 2.38%   |
| Cegled             | 1         | 2.38%   |
| Brisbane           | 1         | 2.38%   |
| Bogotá            | 1         | 2.38%   |
| Belo Horizonte     | 1         | 2.38%   |
| Bareilly           | 1         | 2.38%   |
| Baku               | 1         | 2.38%   |
| Athens             | 1         | 2.38%   |
| Antipolo City      | 1         | 2.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 12        | 13     | 22.22%  |
| ADATA Technology            | 6         | 6      | 11.11%  |
| SK hynix                    | 5         | 5      | 9.26%   |
| Seagate                     | 5         | 5      | 9.26%   |
| Unknown                     | 4         | 4      | 7.41%   |
| Toshiba                     | 3         | 3      | 5.56%   |
| SanDisk                     | 3         | 3      | 5.56%   |
| Phison Electronics          | 2         | 2      | 3.7%    |
| Intel                       | 2         | 2      | 3.7%    |
| Wellcomm                    | 1         | 1      | 1.85%   |
| Samsung Electronics         | 1         | 1      | 1.85%   |
| PNY                         | 1         | 1      | 1.85%   |
| Micron Technology           | 1         | 1      | 1.85%   |
| LITEONIT                    | 1         | 1      | 1.85%   |
| Kingston Technology Company | 1         | 1      | 1.85%   |
| Kingston                    | 1         | 1      | 1.85%   |
| Hitachi                     | 1         | 1      | 1.85%   |
| China                       | 1         | 1      | 1.85%   |
| BHT                         | 1         | 1      | 1.85%   |
| A-DATA Technology           | 1         | 1      | 1.85%   |
| Unknown                     | 1         | 1      | 1.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| ADATA SM2P32A8-256GC1 256GB                 | 6         | 10.91%  |
| WDC WD10SPZX-21Z10T0 1TB                    | 3         | 5.45%   |
| Unknown MMC Card  128GB                     | 2         | 3.64%   |
| SK hynix HFM128GD3JX016N 128GB              | 2         | 3.64%   |
| Seagate ST500LT012-9WS142 500GB             | 2         | 3.64%   |
| Wellcomm Master 128GB SSD                   | 1         | 1.82%   |
| WDC WDS240G1G0A-00SS50 240GB SSD            | 1         | 1.82%   |
| WDC WDS120G2G0A-00JH30 120GB SSD            | 1         | 1.82%   |
| WDC WDS120G1G0A-00SS50 120GB SSD            | 1         | 1.82%   |
| WDC WD5000AAKX-001CA0 500GB                 | 1         | 1.82%   |
| WDC WD3200BPVT-00HXZT3 320GB                | 1         | 1.82%   |
| WDC WD2500BEVT-75ZCT2 250GB                 | 1         | 1.82%   |
| WDC WD10SPZX-24Z10 1TB                      | 1         | 1.82%   |
| WDC WD10JPVX-75JC3T0 1TB                    | 1         | 1.82%   |
| WDC WD10EZEX-75WN4A0 1TB                    | 1         | 1.82%   |
| WDC WD Green M.2 2280 480GB                 | 1         | 1.82%   |
| Unknown MMC Card  64GB                      | 1         | 1.82%   |
| Unknown MMC Card  134GB                     | 1         | 1.82%   |
| Toshiba MQ04ABF100 1TB                      | 1         | 1.82%   |
| Toshiba MQ01ABF050 500GB                    | 1         | 1.82%   |
| Toshiba MQ01ABD100 1TB                      | 1         | 1.82%   |
| SK hynix SH920 2.5 7MM 256GB SSD            | 1         | 1.82%   |
| SK hynix HFS128G39TND-N210A 128GB SSD       | 1         | 1.82%   |
| SK hynix BC501 NVMe Solid State Drive 512GB | 1         | 1.82%   |
| Seagate ST500LM030-1RK17D 500GB             | 1         | 1.82%   |
| Seagate ST500DM002-1BD142 500GB             | 1         | 1.82%   |
| Seagate ST1000LM035-1RK172 1TB              | 1         | 1.82%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB          | 1         | 1.82%   |
| SanDisk SDSSDH3500G 500GB                   | 1         | 1.82%   |
| Sandisk PC SN520 NVMe SSD 512GB             | 1         | 1.82%   |
| Samsung SSD 980 500GB                       | 1         | 1.82%   |
| PNY CS900 1TB SSD                           | 1         | 1.82%   |
| Phison PS5013 E13 NVMe Controller 500GB     | 1         | 1.82%   |
| Phison E12 NVMe Controller 1024GB           | 1         | 1.82%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD         | 1         | 1.82%   |
| LITEONIT LMT-32L3M mSATA 32GB SSD           | 1         | 1.82%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB     | 1         | 1.82%   |
| Kingston RBUSC180DS37128GJ 128GB SSD        | 1         | 1.82%   |
| Intel XPG GAMMIX S11 Pro 512GB              | 1         | 1.82%   |
| Intel WDC PC SN520 SDAPNUW-512G-1014 512GB  | 1         | 1.82%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 9         | 9      | 50%     |
| Seagate | 5         | 5      | 27.78%  |
| Toshiba | 3         | 3      | 16.67%  |
| Hitachi | 1         | 1      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 3         | 3      | 23.08%  |
| SK hynix          | 2         | 2      | 15.38%  |
| Wellcomm          | 1         | 1      | 7.69%   |
| SanDisk           | 1         | 1      | 7.69%   |
| PNY               | 1         | 1      | 7.69%   |
| Micron Technology | 1         | 1      | 7.69%   |
| LITEONIT          | 1         | 1      | 7.69%   |
| Kingston          | 1         | 1      | 7.69%   |
| China             | 1         | 1      | 7.69%   |
| A-DATA Technology | 1         | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 18        | 18     | 32.73%  |
| NVMe    | 17        | 17     | 30.91%  |
| SSD     | 13        | 13     | 23.64%  |
| MMC     | 4         | 4      | 7.27%   |
| Unknown | 3         | 3      | 5.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 28        | 34     | 57.14%  |
| NVMe | 17        | 17     | 34.69%  |
| MMC  | 4         | 4      | 8.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 19        | 21     | 65.52%  |
| 0.51-1.0   | 10        | 10     | 34.48%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 18        | 42.86%  |
| 251-500    | 9         | 21.43%  |
| 1-20       | 5         | 11.9%   |
| 501-1000   | 5         | 11.9%   |
| 21-50      | 2         | 4.76%   |
| 1001-2000  | 1         | 2.38%   |
| 51-100     | 1         | 2.38%   |
| Unknown    | 1         | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 21-50    | 16        | 38.1%   |
| 1-20     | 15        | 35.71%  |
| 251-500  | 3         | 7.14%   |
| 101-250  | 3         | 7.14%   |
| 51-100   | 3         | 7.14%   |
| 501-1000 | 1         | 2.38%   |
| Unknown  | 1         | 2.38%   |

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
| Detected | 42        | 55     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 31        | 57.41%  |
| AMD                         | 8         | 14.81%  |
| ADATA Technology            | 6         | 11.11%  |
| SK hynix                    | 3         | 5.56%   |
| SanDisk                     | 2         | 3.7%    |
| Phison Electronics          | 2         | 3.7%    |
| Samsung Electronics         | 1         | 1.85%   |
| Kingston Technology Company | 1         | 1.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 8         | 12.9%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 7         | 11.29%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 9.68%   |
| ADATA A Non-Volatile memory controller                                                  | 6         | 9.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 4.84%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 2         | 3.23%   |
| Intel PROSet/Wireless WiFi Software extension                                           | 2         | 3.23%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2         | 3.23%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1         | 1.61%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 1.61%   |
| SanDisk PC SN520 NVMe SSD                                                               | 1         | 1.61%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 1.61%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 1.61%   |
| Phison E12 NVMe Controller                                                              | 1         | 1.61%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1         | 1.61%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1         | 1.61%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 1         | 1.61%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1         | 1.61%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 1.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 1.61%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 1.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 1.61%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 1.61%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1         | 1.61%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1         | 1.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 1.61%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1         | 1.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1         | 1.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1         | 1.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 1.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 32        | 54.24%  |
| NVMe | 17        | 28.81%  |
| RAID | 6         | 10.17%  |
| IDE  | 4         | 6.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 32        | 76.19%  |
| AMD    | 10        | 23.81%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Celeron N4020 CPU @ 1.10GHz               | 3         | 7.14%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 3         | 7.14%   |
| Intel Core i5-9300H CPU @ 2.40GHz               | 2         | 4.76%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 2         | 4.76%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 2         | 4.76%   |
| AMD Athlon Silver 3050U with Radeon Graphics    | 2         | 4.76%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 2.38%   |
| Intel Core i7-3612QM CPU @ 2.10GHz              | 1         | 2.38%   |
| Intel Core i7-3537U CPU @ 2.00GHz               | 1         | 2.38%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 1         | 2.38%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 2.38%   |
| Intel Core i5-4310M CPU @ 2.70GHz               | 1         | 2.38%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1         | 2.38%   |
| Intel Core i3-8100 CPU @ 3.60GHz                | 1         | 2.38%   |
| Intel Core i3-7130U CPU @ 2.70GHz               | 1         | 2.38%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 1         | 2.38%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 1         | 2.38%   |
| Intel Core i3-2125 CPU @ 3.30GHz                | 1         | 2.38%   |
| Intel Core i3-10110U CPU @ 2.10GHz              | 1         | 2.38%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 1         | 2.38%   |
| Intel Core 2 Quad CPU Q6700 @ 2.66GHz           | 1         | 2.38%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 1         | 2.38%   |
| Intel Core 2 CPU 6600 @ 2.40GHz                 | 1         | 2.38%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 2.38%   |
| Intel Celeron CPU N3350 @ 1.10GHz               | 1         | 2.38%   |
| Intel Celeron CPU N2840 @ 2.16GHz               | 1         | 2.38%   |
| Intel Celeron CPU B810 @ 1.60GHz                | 1         | 2.38%   |
| Intel Celeron CPU 900 @ 2.20GHz                 | 1         | 2.38%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 1         | 2.38%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 1         | 2.38%   |
| AMD E1-6010 APU with AMD Radeon R2 Graphics     | 1         | 2.38%   |
| AMD A9-9400 RADEON R5, 5 COMPUTE CORES 2C+3G    | 1         | 2.38%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G   | 1         | 2.38%   |
| AMD A4 Micro-6400T APU + AMD Radeon R3 Graphics | 1         | 2.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 10        | 23.81%  |
| Intel Celeron     | 8         | 19.05%  |
| Intel Core i3     | 7         | 16.67%  |
| Intel Core i7     | 3         | 7.14%   |
| AMD Ryzen 5       | 3         | 7.14%   |
| Other             | 2         | 4.76%   |
| AMD Athlon        | 2         | 4.76%   |
| Intel Core 2 Quad | 1         | 2.38%   |
| Intel Core 2 Duo  | 1         | 2.38%   |
| Intel Core 2      | 1         | 2.38%   |
| AMD Ryzen 7       | 1         | 2.38%   |
| AMD E1            | 1         | 2.38%   |
| AMD A6            | 1         | 2.38%   |
| AMD A4            | 1         | 2.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 25        | 59.52%  |
| 4      | 14        | 33.33%  |
| 8      | 1         | 2.38%   |
| 6      | 1         | 2.38%   |
| 1      | 1         | 2.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 42        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 23        | 54.76%  |
| 1      | 19        | 45.24%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 42        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x08108109 | 4         | 9.52%   |
| 0x706e5    | 3         | 7.14%   |
| 0x706a8    | 3         | 7.14%   |
| 0x306a9    | 3         | 7.14%   |
| 0x906ea    | 2         | 4.76%   |
| 0x806ea    | 2         | 4.76%   |
| 0x806e9    | 2         | 4.76%   |
| 0x406e3    | 2         | 4.76%   |
| 0x206a7    | 2         | 4.76%   |
| 0x07030105 | 2         | 4.76%   |
| 0xa0660    | 1         | 2.38%   |
| 0x906ed    | 1         | 2.38%   |
| 0x906eb    | 1         | 2.38%   |
| 0x806c1    | 1         | 2.38%   |
| 0x706a1    | 1         | 2.38%   |
| 0x6fb      | 1         | 2.38%   |
| 0x6f6      | 1         | 2.38%   |
| 0x506c9    | 1         | 2.38%   |
| 0x40651    | 1         | 2.38%   |
| 0x306c3    | 1         | 2.38%   |
| 0x30678    | 1         | 2.38%   |
| 0x1067a    | 1         | 2.38%   |
| 0x10676    | 1         | 2.38%   |
| 0x08701021 | 1         | 2.38%   |
| 0x08108102 | 1         | 2.38%   |
| 0x06006705 | 1         | 2.38%   |
| 0x06006704 | 1         | 2.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 8         | 19.05%  |
| Zen+          | 5         | 11.9%   |
| Goldmont plus | 4         | 9.52%   |
| IvyBridge     | 3         | 7.14%   |
| IceLake       | 3         | 7.14%   |
| Skylake       | 2         | 4.76%   |
| SandyBridge   | 2         | 4.76%   |
| Puma          | 2         | 4.76%   |
| Penryn        | 2         | 4.76%   |
| Haswell       | 2         | 4.76%   |
| Excavator     | 2         | 4.76%   |
| Core          | 2         | 4.76%   |
| Zen 2         | 1         | 2.38%   |
| TigerLake     | 1         | 2.38%   |
| Silvermont    | 1         | 2.38%   |
| Goldmont      | 1         | 2.38%   |
| CometLake     | 1         | 2.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 31        | 63.27%  |
| AMD    | 11        | 22.45%  |
| Nvidia | 7         | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 10.2%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 4         | 8.16%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 3         | 6.12%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 3         | 6.12%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 6.12%   |
| Intel UHD Graphics 620                                                    | 2         | 4.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 4.08%   |
| Intel HD Graphics 620                                                     | 2         | 4.08%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 4.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 4.08%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 2         | 4.08%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 2.04%   |
| Nvidia GM108M [GeForce MX130]                                             | 1         | 2.04%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 2.04%   |
| Nvidia GF108GLM [Quadro 1000M]                                            | 1         | 2.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 1         | 2.04%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 1         | 2.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 2.04%   |
| Intel HD Graphics 500                                                     | 1         | 2.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 2.04%   |
| Intel Comet Lake UHD Graphics                                             | 1         | 2.04%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1         | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 2.04%   |
| Intel 82Q35 Express Integrated Graphics Controller                        | 1         | 2.04%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                    | 1         | 2.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 2.04%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                            | 1         | 2.04%   |
| AMD Mullins [Radeon R3E Graphics]                                         | 1         | 2.04%   |
| AMD Mullins [Radeon R2 Graphics]                                          | 1         | 2.04%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                        | 1         | 2.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 24        | 57.14%  |
| 1 x AMD        | 11        | 26.19%  |
| Intel + Nvidia | 7         | 16.67%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 37        | 88.1%   |
| Proprietary | 5         | 11.9%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 69.05%  |
| 1.01-2.0   | 7         | 16.67%  |
| 0.01-0.5   | 4         | 9.52%   |
| 3.01-4.0   | 1         | 2.38%   |
| 8.01-16.0  | 1         | 2.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 17        | 38.64%  |
| LG Display              | 6         | 13.64%  |
| Chimei Innolux          | 6         | 13.64%  |
| AU Optronics            | 3         | 6.82%   |
| Samsung Electronics     | 2         | 4.55%   |
| Lenovo                  | 2         | 4.55%   |
| Goldstar                | 2         | 4.55%   |
| Acer                    | 2         | 4.55%   |
| Philips                 | 1         | 2.27%   |
| PANDA                   | 1         | 2.27%   |
| Chi Mei Optoelectronics | 1         | 2.27%   |
| ASUSTek Computer        | 1         | 2.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE07AA 1366x768 344x194mm 15.5-inch                  | 4         | 9.09%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 6.82%   |
| Goldstar W1542 GSM3BB1 1280x720 332x187mm 15.0-inch                   | 2         | 4.55%   |
| BOE LCD Monitor BOE08E5 1366x768 344x194mm 15.5-inch                  | 2         | 4.55%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                  | 2         | 4.55%   |
| Samsung Electronics SyncMaster SAM0487 1920x1080                      | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch  | 1         | 2.27%   |
| Philips PHL 241V8 PHLC212 1920x1080 527x296mm 23.8-inch               | 1         | 2.27%   |
| PANDA LCD Monitor NCP0035 1920x1080 344x194mm 15.5-inch               | 1         | 2.27%   |
| LG Display LCD Monitor LGD6302 1366x768 344x194mm 15.5-inch           | 1         | 2.27%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch          | 1         | 2.27%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch          | 1         | 2.27%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 2.27%   |
| LG Display LCD Monitor LGD0466 1366x768 309x174mm 14.0-inch           | 1         | 2.27%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 1         | 2.27%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch               | 1         | 2.27%   |
| Lenovo C24-25 LEN66B0 1920x1080 527x296mm 23.8-inch                   | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch       | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 344x194mm 15.5-inch       | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch       | 1         | 2.27%   |
| Chi Mei Optoelectronics CMC 19AW CMO2198 1440x900 408x255mm 18.9-inch | 1         | 2.27%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                 | 1         | 2.27%   |
| BOE LCD Monitor BOE08B2 1366x768 309x174mm 14.0-inch                  | 1         | 2.27%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                 | 1         | 2.27%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 1         | 2.27%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                 | 1         | 2.27%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 1         | 2.27%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 1         | 2.27%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 1         | 2.27%   |
| BOE LCD Monitor BOE05F3 1366x768 309x173mm 13.9-inch                  | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch         | 1         | 2.27%   |
| ASUSTek Computer XG32V AUS32B1 2560x1440 697x393mm 31.5-inch          | 1         | 2.27%   |
| Acer QG241Y ACR06F9 1920x1080 527x296mm 23.8-inch                     | 1         | 2.27%   |
| Acer KA220HQ ACR0497 1920x1080 477x268mm 21.5-inch                    | 1         | 2.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 21        | 48.84%  |
| 1920x1080 (FHD)  | 16        | 37.21%  |
| 1600x900 (HD+)   | 2         | 4.65%   |
| 1280x720 (HD)    | 2         | 4.65%   |
| 2560x1440 (QHD)  | 1         | 2.33%   |
| 1440x900 (WXGA+) | 1         | 2.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 26        | 59.09%  |
| 14      | 4         | 9.09%   |
| 13      | 3         | 6.82%   |
| 24      | 2         | 4.55%   |
| 17      | 2         | 4.55%   |
| 11      | 2         | 4.55%   |
| 31      | 1         | 2.27%   |
| 23      | 1         | 2.27%   |
| 21      | 1         | 2.27%   |
| 19      | 1         | 2.27%   |
| Unknown | 1         | 2.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 75%     |
| 501-600     | 3         | 6.82%   |
| 401-500     | 2         | 4.55%   |
| 351-400     | 2         | 4.55%   |
| 201-300     | 2         | 4.55%   |
| 601-700     | 1         | 2.27%   |
| Unknown     | 1         | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 41        | 97.62%  |
| 16/10 | 1         | 2.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 54.55%  |
| 81-90          | 7         | 15.91%  |
| 201-250        | 4         | 9.09%   |
| 51-60          | 2         | 4.55%   |
| 121-130        | 2         | 4.55%   |
| 91-100         | 2         | 4.55%   |
| 351-500        | 1         | 2.27%   |
| 151-200        | 1         | 2.27%   |
| Unknown        | 1         | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 22        | 50%     |
| 121-160 | 14        | 31.82%  |
| 51-100  | 7         | 15.91%  |
| Unknown | 1         | 2.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 40        | 95.24%  |
| 2     | 2         | 4.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 30        | 48.39%  |
| Intel                             | 16        | 25.81%  |
| Qualcomm Atheros                  | 8         | 12.9%   |
| Samsung Electronics               | 2         | 3.23%   |
| T & A Mobile Phones               | 1         | 1.61%   |
| Qualcomm Atheros Communications   | 1         | 1.61%   |
| Ericsson Business Mobile Networks | 1         | 1.61%   |
| Dell                              | 1         | 1.61%   |
| Broadcom Limited                  | 1         | 1.61%   |
| Broadcom                          | 1         | 1.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 18.31%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 9.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 8.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 5.63%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 4.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 2.82%   |
| Realtek Realtek Network controller                                | 2         | 2.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 2.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 2.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.82%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2         | 2.82%   |
| T & A Mobile Phones Alcatel JOY TAB 2                             | 1         | 1.41%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.41%   |
| Realtek RTL8187B Wireless Adapter                                 | 1         | 1.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.41%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.41%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.41%   |
| Intel Wireless 3165                                               | 1         | 1.41%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.41%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.41%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.41%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 1.41%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.41%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 1.41%   |
| Intel Centrino Advanced-N 6235                                    | 1         | 1.41%   |
| Ericsson Business Mobile Networks F5521gw                         | 1         | 1.41%   |
| Dell Hub of E-Port Replicator                                     | 1         | 1.41%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 1         | 1.41%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 15        | 38.46%  |
| Intel                           | 14        | 35.9%   |
| Qualcomm Atheros                | 7         | 17.95%  |
| Qualcomm Atheros Communications | 1         | 2.56%   |
| Dell                            | 1         | 2.56%   |
| Broadcom                        | 1         | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 7         | 17.95%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 4         | 10.26%  |
| Intel Wi-Fi 6 AX200                                        | 3         | 7.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 2         | 5.13%   |
| Realtek Realtek Network controller                         | 2         | 5.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 2         | 5.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 2         | 5.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 2         | 5.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1         | 2.56%   |
| Realtek RTL8187B Wireless Adapter                          | 1         | 2.56%   |
| Qualcomm Atheros AR9271 802.11n                            | 1         | 2.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 1         | 2.56%   |
| Intel Wireless 8265 / 8275                                 | 1         | 2.56%   |
| Intel Wireless 3165                                        | 1         | 2.56%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 2.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 1         | 2.56%   |
| Intel Gemini Lake PCH CNVi WiFi                            | 1         | 2.56%   |
| Intel Centrino Wireless-N 2230                             | 1         | 2.56%   |
| Intel Centrino Advanced-N 6235                             | 1         | 2.56%   |
| Dell Hub of E-Port Replicator                              | 1         | 2.56%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 20        | 66.67%  |
| Intel                 | 6         | 20%     |
| Samsung Electronics   | 2         | 6.67%   |
| Qualcomm Atheros      | 1         | 3.33%   |
| Broadcom Limited      | 1         | 3.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 43.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 20%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 6.67%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2         | 6.67%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 3.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 3.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 3.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 3.33%   |
| Intel I211 Gigabit Network Connection                             | 1         | 3.33%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.33%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 1         | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 55.07%  |
| Ethernet | 29        | 42.03%  |
| Modem    | 1         | 1.45%   |
| Unknown  | 1         | 1.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 35        | 83.33%  |
| Ethernet | 7         | 16.67%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 22        | 52.38%  |
| 2     | 19        | 45.24%  |
| 3     | 1         | 2.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 27        | 64.29%  |
| Yes  | 15        | 35.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 34.38%  |
| IMC Networks                    | 9         | 28.13%  |
| Realtek Semiconductor           | 6         | 18.75%  |
| Lite-On Technology              | 3         | 9.38%   |
| Qualcomm Atheros Communications | 1         | 3.13%   |
| Cambridge Silicon Radio         | 1         | 3.13%   |
| Broadcom                        | 1         | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Bluetooth Radio                        | 7         | 21.88%  |
| Realtek Bluetooth Radio                             | 5         | 15.63%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 9.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 9.38%   |
| Intel AX200 Bluetooth                               | 3         | 9.38%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 6.25%   |
| Intel Bluetooth wireless interface                  | 2         | 6.25%   |
| IMC Networks Bluetooth Device                       | 2         | 6.25%   |
| Realtek RTL8821A Bluetooth                          | 1         | 3.13%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 3.13%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 3.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.13%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 32        | 66.67%  |
| AMD                    | 11        | 22.92%  |
| Nvidia                 | 4         | 8.33%   |
| Generalplus Technology | 1         | 2.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 6         | 10%     |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 5         | 8.33%   |
| AMD Family 17h/19h HD Audio Controller                                            | 5         | 8.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 4         | 6.67%   |
| Intel Cannon Lake PCH cAVS                                                        | 4         | 6.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 3         | 5%      |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 3         | 5%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 3         | 5%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 3         | 5%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 2         | 3.33%   |
| AMD Kabini HDMI/DP Audio                                                          | 2         | 3.33%   |
| AMD High Definition Audio Controller                                              | 2         | 3.33%   |
| AMD FCH Azalia Controller                                                         | 2         | 3.33%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 2         | 3.33%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1         | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1         | 1.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 1         | 1.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1         | 1.67%   |
| Intel Haswell-ULT HD Audio Controller                                             | 1         | 1.67%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 1         | 1.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 1         | 1.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1         | 1.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 1         | 1.67%   |
| Intel 8 Series HD Audio Controller                                                | 1         | 1.67%   |
| Generalplus Technology USB Audio Device                                           | 1         | 1.67%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1         | 1.67%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 1         | 1.67%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 1.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

Zero info for selected period =(

Memory Model
------------

Memory module models

Zero info for selected period =(

Memory Kind
-----------

Memory module kinds

Zero info for selected period =(

Memory Form Factor
------------------

Physical design of the memory module

Zero info for selected period =(

Memory Size
-----------

Memory module size

Zero info for selected period =(

Memory Speed
------------

Memory module speed

Zero info for selected period =(

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

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Chicony Electronics   | 9         | 25.71%  |
| IMC Networks          | 8         | 22.86%  |
| Sonix Technology      | 6         | 17.14%  |
| Quanta                | 5         | 14.29%  |
| Microdia              | 3         | 8.57%   |
| Suyin                 | 1         | 2.86%   |
| Realtek Semiconductor | 1         | 2.86%   |
| LG Electronics        | 1         | 2.86%   |
| Acer                  | 1         | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Sonix USB2.0 HD UVC WebCam                            | 5         | 14.29%  |
| IMC Networks USB2.0 VGA UVC WebCam                    | 4         | 11.43%  |
| Quanta HD Webcam                                      | 3         | 8.57%   |
| IMC Networks USB2.0 HD UVC WebCam                     | 3         | 8.57%   |
| Chicony Integrated Camera                             | 2         | 5.71%   |
| Chicony HP Webcam                                     | 2         | 5.71%   |
| Suyin HP Truevision HD                                | 1         | 2.86%   |
| Sonix USB2.0 VGAUVC WebCam                            | 1         | 2.86%   |
| Realtek MTD camera                                    | 1         | 2.86%   |
| Quanta VGA WebCam                                     | 1         | 2.86%   |
| Quanta HD User Facing                                 | 1         | 2.86%   |
| Microdia Laptop_Integrated_Webcam_HD                  | 1         | 2.86%   |
| Microdia Integrated_Webcam_HD                         | 1         | 2.86%   |
| Microdia Integrated Webcam                            | 1         | 2.86%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1         | 2.86%   |
| IMC Networks EasyCamera                               | 1         | 2.86%   |
| Chicony VGA Webcam                                    | 1         | 2.86%   |
| Chicony USB2.0 HD UVC WebCam                          | 1         | 2.86%   |
| Chicony Lenovo Integrated Camera (0.3MP)              | 1         | 2.86%   |
| Chicony HD User Facing                                | 1         | 2.86%   |
| Chicony Camera                                        | 1         | 2.86%   |
| Acer Integrated Camera                                | 1         | 2.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Elan Microelectronics | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| Elan ELAN:Fingerprint | 1         | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./All/images/line_chart/chipcard_vendor.svg)

| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 33        | 78.57%  |
| 1     | 9         | 21.43%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 2         | 22.22%  |
| Multimedia controller | 2         | 22.22%  |
| Storage/nvme          | 1         | 11.11%  |
| Storage/ide           | 1         | 11.11%  |
| Graphics card         | 1         | 11.11%  |
| Fingerprint reader    | 1         | 11.11%  |
| Chipcard              | 1         | 11.11%  |

