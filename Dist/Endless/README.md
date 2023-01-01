Endless - Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Endless/Desktop/README.md) and [notebooks](/Dist/Endless/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/linuxhw/TestCoverage)

Period: Dec, 2022.

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
| Endless 4.0.13        | 17        | 54.84%  |
| Endless 3.9.7         | 4         | 12.9%   |
| Endless 4.0.10        | 3         | 9.68%   |
| Endless 3.9.3-nexthw1 | 2         | 6.45%   |
| Endless 4.0.9         | 1         | 3.23%   |
| Endless 4.0.4         | 1         | 3.23%   |
| Endless 4.0.11        | 1         | 3.23%   |
| Endless 3.7.8         | 1         | 3.23%   |
| Endless 3.4.3-nexthw1 | 1         | 3.23%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Endless | 31        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.11.0-35-generic | 23        | 74.19%  |
| 5.8.0-14-generic  | 4         | 12.9%   |
| 5.11.0-12-generic | 2         | 6.45%   |
| 5.3.0-28-generic  | 1         | 3.23%   |
| 4.16.0-4-generic  | 1         | 3.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 25        | 80.65%  |
| 5.8.0   | 4         | 12.9%   |
| 5.3.0   | 1         | 3.23%   |
| 4.16.0  | 1         | 3.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 25        | 80.65%  |
| 5.8     | 4         | 12.9%   |
| 5.3     | 1         | 3.23%   |
| 4.16    | 1         | 3.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 31        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name  | Computers | Percent |
|-------|-----------|---------|
| GNOME | 31        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 31        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 31        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| pt_BR | 12        | 38.71%  |
| en_US | 7         | 22.58%  |
| de_DE | 3         | 9.68%   |
| es_ES | 2         | 6.45%   |
| ru_RU | 1         | 3.23%   |
| ro_RO | 1         | 3.23%   |
| pl_PL | 1         | 3.23%   |
| nl_NL | 1         | 3.23%   |
| hu_HU | 1         | 3.23%   |
| fr_FR | 1         | 3.23%   |
| es_MX | 1         | 3.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 24        | 77.42%  |
| BIOS | 7         | 22.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 29        | 93.55%  |
| Tmpfs | 2         | 6.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 31        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 17        | 54.84%  |
| Acer                | 6         | 19.35%  |
| Hewlett-Packard     | 3         | 9.68%   |
| Lenovo              | 2         | 6.45%   |
| Dell                | 2         | 6.45%   |
| Samsung Electronics | 1         | 3.23%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop X515DA_X515DA            | 5         | 16.13%  |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA            | 2         | 6.45%   |
| Samsung RV420/RV520/RV720/E3530/S3530/E3420/E3520 | 1         | 3.23%   |
| Lenovo Y520-15IKBN 80WK                           | 1         | 3.23%   |
| Lenovo IdeaPad 110-14IBR 80T6                     | 1         | 3.23%   |
| HP Pavilion 17                                    | 1         | 3.23%   |
| HP EliteDesk 800 G1 SFF                           | 1         | 3.23%   |
| HP Compaq 8000 Elite USDT PC                      | 1         | 3.23%   |
| Dell Latitude E6520                               | 1         | 3.23%   |
| Dell Inspiron 3542                                | 1         | 3.23%   |
| ASUS X451CAP                                      | 1         | 3.23%   |
| ASUS VivoBook_ASUSLaptop X515MA_X515MA            | 1         | 3.23%   |
| ASUS VivoBook_ASUSLaptop X409DA_M409DA            | 1         | 3.23%   |
| ASUS VivoBook_ASUSLaptop E410MAB_E410MA           | 1         | 3.23%   |
| ASUS VivoBook 15_ASUS Laptop X540BA               | 1         | 3.23%   |
| ASUS VivoBook 15_ASUS Laptop X507UAR              | 1         | 3.23%   |
| ASUS VivoBook 15_ASUS Laptop X507MA_X507MA        | 1         | 3.23%   |
| ASUS T101HA                                       | 1         | 3.23%   |
| ASUS N71Vn                                        | 1         | 3.23%   |
| ASUS M5A97 R2.0                                   | 1         | 3.23%   |
| Acer Nitro N50-610                                | 1         | 3.23%   |
| Acer Nitro AN517-51                               | 1         | 3.23%   |
| Acer Nitro AN515-54                               | 1         | 3.23%   |
| Acer Aspire XC-704                                | 1         | 3.23%   |
| Acer Aspire A515-54G                              | 1         | 3.23%   |
| Acer Aspire 5735                                  | 1         | 3.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS VivoBook      | 13        | 41.94%  |
| Acer Nitro         | 3         | 9.68%   |
| Acer Aspire        | 3         | 9.68%   |
| Samsung RV420      | 1         | 3.23%   |
| Lenovo Y520-15IKBN | 1         | 3.23%   |
| Lenovo IdeaPad     | 1         | 3.23%   |
| HP Pavilion        | 1         | 3.23%   |
| HP EliteDesk       | 1         | 3.23%   |
| HP Compaq          | 1         | 3.23%   |
| Dell Latitude      | 1         | 3.23%   |
| Dell Inspiron      | 1         | 3.23%   |
| ASUS X451CAP       | 1         | 3.23%   |
| ASUS T101HA        | 1         | 3.23%   |
| ASUS N71Vn         | 1         | 3.23%   |
| ASUS M5A97         | 1         | 3.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 7         | 22.58%  |
| 2019 | 4         | 12.9%   |
| 2021 | 3         | 9.68%   |
| 2018 | 3         | 9.68%   |
| 2013 | 3         | 9.68%   |
| 2017 | 2         | 6.45%   |
| 2011 | 2         | 6.45%   |
| 2009 | 2         | 6.45%   |
| 2016 | 1         | 3.23%   |
| 2015 | 1         | 3.23%   |
| 2014 | 1         | 3.23%   |
| 2012 | 1         | 3.23%   |
| 2008 | 1         | 3.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 25        | 80.65%  |
| Desktop  | 5         | 16.13%  |
| Tablet   | 1         | 3.23%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 25        | 80.65%  |
| Enabled  | 6         | 19.35%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 31        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 16        | 51.61%  |
| 3.01-4.0   | 9         | 29.03%  |
| 8.01-16.0  | 3         | 9.68%   |
| 16.01-24.0 | 2         | 6.45%   |
| 1.01-2.0   | 1         | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 16        | 51.61%  |
| 2.01-3.0 | 7         | 22.58%  |
| 0.51-1.0 | 4         | 12.9%   |
| 4.01-8.0 | 2         | 6.45%   |
| 3.01-4.0 | 2         | 6.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 23        | 74.19%  |
| 2      | 8         | 25.81%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 21        | 67.74%  |
| Yes       | 10        | 32.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 54.84%  |
| No        | 14        | 45.16%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 96.77%  |
| No        | 1         | 3.23%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 74.19%  |
| No        | 8         | 25.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country     | Computers | Percent |
|-------------|-----------|---------|
| Brazil      | 12        | 38.71%  |
| Romania     | 3         | 9.68%   |
| Germany     | 3         | 9.68%   |
| USA         | 2         | 6.45%   |
| Spain       | 2         | 6.45%   |
| UK          | 1         | 3.23%   |
| Russia      | 1         | 3.23%   |
| Poland      | 1         | 3.23%   |
| New Zealand | 1         | 3.23%   |
| Netherlands | 1         | 3.23%   |
| Indonesia   | 1         | 3.23%   |
| Hungary     | 1         | 3.23%   |
| France      | 1         | 3.23%   |
| Colombia    | 1         | 3.23%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Sao Paulo             | 2         | 6.45%   |
| Whangarei             | 1         | 3.23%   |
| Veszprém             | 1         | 3.23%   |
| Uruacu                | 1         | 3.23%   |
| Templin               | 1         | 3.23%   |
| Sao José dos Pinhais | 1         | 3.23%   |
| Santos                | 1         | 3.23%   |
| Salamanca             | 1         | 3.23%   |
| Quijas                | 1         | 3.23%   |
| Porto Alegre          | 1         | 3.23%   |
| Popesti-Leordeni      | 1         | 3.23%   |
| Pelotas               | 1         | 3.23%   |
| Mons-en-Baroeul       | 1         | 3.23%   |
| Manaus                | 1         | 3.23%   |
| Maastricht            | 1         | 3.23%   |
| Leipzig               | 1         | 3.23%   |
| Kolpino               | 1         | 3.23%   |
| Jakarta               | 1         | 3.23%   |
| Itabirito             | 1         | 3.23%   |
| Iasi                  | 1         | 3.23%   |
| Gora Kalwaria         | 1         | 3.23%   |
| Goldsboro             | 1         | 3.23%   |
| Goiânia              | 1         | 3.23%   |
| Gilbert               | 1         | 3.23%   |
| Formosa               | 1         | 3.23%   |
| Curitiba              | 1         | 3.23%   |
| Campina               | 1         | 3.23%   |
| Bogotá               | 1         | 3.23%   |
| Bochum                | 1         | 3.23%   |
| Barnsley              | 1         | 3.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 5         | 5      | 13.51%  |
| Samsung Electronics         | 5         | 5      | 13.51%  |
| ADATA Technology            | 5         | 5      | 13.51%  |
| WDC                         | 4         | 4      | 10.81%  |
| SanDisk                     | 3         | 3      | 8.11%   |
| Kingston                    | 3         | 3      | 8.11%   |
| Intel                       | 3         | 3      | 8.11%   |
| Unknown                     | 2         | 3      | 5.41%   |
| Phison Electronics          | 2         | 2      | 5.41%   |
| V7                          | 1         | 1      | 2.7%    |
| Toshiba                     | 1         | 1      | 2.7%    |
| Micron Technology           | 1         | 1      | 2.7%    |
| Kingston Technology Company | 1         | 1      | 2.7%    |
| Hitachi                     | 1         | 1      | 2.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| ADATA SM2P32A8-256GC1 256GB                         | 5         | 13.16%  |
| Phison PS5013 E13 NVMe Controller 512GB             | 2         | 5.26%   |
| Intel KINGSTON RBUSNS8154P3512GJ1 512GB             | 2         | 5.26%   |
| WDC WD3200BEKT-08PVMT1 320GB                        | 1         | 2.63%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 1         | 2.63%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 1         | 2.63%   |
| WDC WD10EZEX-21WN4A0 1TB                            | 1         | 2.63%   |
| V7 SSD 512GB                                        | 1         | 2.63%   |
| Unknown SD/MMC/MS PRO 64GB                          | 1         | 2.63%   |
| Unknown MMC Card  64GB                              | 1         | 2.63%   |
| Unknown MMC Card  128GB                             | 1         | 2.63%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 2.63%   |
| Seagate ST9250410AS 250GB                           | 1         | 2.63%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 2.63%   |
| Seagate ST500DM002-1BD142 500GB                     | 1         | 2.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 2.63%   |
| Seagate ST1000DM003-1CH162 1TB                      | 1         | 2.63%   |
| Sandisk WD Blue SN550 NVMe SSD 500GB                | 1         | 2.63%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 256GB     | 1         | 2.63%   |
| SanDisk SD9SN8W256G1102 256GB SSD                   | 1         | 2.63%   |
| Samsung SSD 870 EVO 250GB                           | 1         | 2.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 2.63%   |
| Samsung MZVLQ256HAJD-00000 256GB                    | 1         | 2.63%   |
| Samsung HM160HI 160GB                               | 1         | 2.63%   |
| Samsung HD103SI 1TB                                 | 1         | 2.63%   |
| Micron 1300_MTFDDAK256TDL 256GB SSD                 | 1         | 2.63%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB             | 1         | 2.63%   |
| Kingston SUV400S37120G 120GB SSD                    | 1         | 2.63%   |
| Kingston SA400S37480G 480GB SSD                     | 1         | 2.63%   |
| Kingston SA400S37240G 240GB SSD                     | 1         | 2.63%   |
| Intel IM2P33F8BR1-128GB                             | 1         | 2.63%   |
| Hitachi HTS543225L9A300 250GB                       | 1         | 2.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 35.71%  |
| WDC                 | 4         | 4      | 28.57%  |
| Samsung Electronics | 2         | 2      | 14.29%  |
| Unknown             | 1         | 1      | 7.14%   |
| Toshiba             | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 3         | 3      | 42.86%  |
| V7                  | 1         | 1      | 14.29%  |
| SanDisk             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Micron Technology   | 1         | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 15        | 15     | 41.67%  |
| HDD  | 13        | 14     | 36.11%  |
| SSD  | 7         | 7      | 19.44%  |
| MMC  | 1         | 2      | 2.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 18        | 20     | 51.43%  |
| NVMe | 15        | 15     | 42.86%  |
| SAS  | 1         | 1      | 2.86%   |
| MMC  | 1         | 2      | 2.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 12        | 13     | 63.16%  |
| 0.51-1.0   | 7         | 8      | 36.84%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 16        | 51.61%  |
| 251-500    | 6         | 19.35%  |
| 501-1000   | 5         | 16.13%  |
| 21-50      | 1         | 3.23%   |
| 1001-2000  | 1         | 3.23%   |
| 1-20       | 1         | 3.23%   |
| Unknown    | 1         | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 21-50    | 16        | 51.61%  |
| 1-20     | 4         | 12.9%   |
| 51-100   | 4         | 12.9%   |
| 251-500  | 3         | 9.68%   |
| 101-250  | 2         | 6.45%   |
| 501-1000 | 1         | 3.23%   |
| Unknown  | 1         | 3.23%   |

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
| Detected | 31        | 38     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 21        | 50%     |
| AMD                         | 9         | 21.43%  |
| ADATA Technology            | 5         | 11.9%   |
| SanDisk                     | 2         | 4.76%   |
| Samsung Electronics         | 2         | 4.76%   |
| Phison Electronics          | 2         | 4.76%   |
| Kingston Technology Company | 1         | 2.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 16.67%  |
| ADATA A Non-Volatile memory controller                                           | 5         | 10.42%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 8.33%   |
| Intel PROSet/Wireless WiFi Software extension                                    | 3         | 6.25%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 6.25%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 4.17%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 4.17%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 4.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 4.17%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 2.08%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 2.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 2.08%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 2.08%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 2.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 2.08%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 2.08%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 1         | 2.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 2.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 2.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 2.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 2.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 2.08%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 1         | 2.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 2.08%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 27        | 56.25%  |
| NVMe | 15        | 31.25%  |
| RAID | 4         | 8.33%   |
| IDE  | 2         | 4.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 22        | 70.97%  |
| AMD    | 9         | 29.03%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 19.35%  |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 6.45%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 6.45%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 3.23%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 3.23%   |
| Intel Pentium CPU J3710 @ 1.60GHz             | 1         | 3.23%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 3.23%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 3.23%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 3.23%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 3.23%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 3.23%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 1         | 3.23%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 3.23%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 3.23%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 1         | 3.23%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 3.23%   |
| Intel Core i3-2375M CPU @ 1.50GHz             | 1         | 3.23%   |
| Intel Core 2 Quad CPU Q9505 @ 2.83GHz         | 1         | 3.23%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 1         | 3.23%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 3.23%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 3.23%   |
| AMD FX-4350 Quad-Core Processor               | 1         | 3.23%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 3.23%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 1         | 3.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 7         | 22.58%  |
| AMD Ryzen 5          | 6         | 19.35%  |
| Other                | 3         | 9.68%   |
| Intel Celeron        | 3         | 9.68%   |
| Intel Core i7        | 2         | 6.45%   |
| Intel Core i3        | 2         | 6.45%   |
| Intel Pentium Silver | 1         | 3.23%   |
| Intel Pentium Dual   | 1         | 3.23%   |
| Intel Pentium        | 1         | 3.23%   |
| Intel Core 2 Quad    | 1         | 3.23%   |
| Intel Core 2 Duo     | 1         | 3.23%   |
| Intel Atom           | 1         | 3.23%   |
| AMD FX               | 1         | 3.23%   |
| AMD A8               | 1         | 3.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 16        | 51.61%  |
| 2      | 13        | 41.94%  |
| 6      | 2         | 6.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 31        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 18        | 58.06%  |
| 1      | 13        | 41.94%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 31        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x08108109 | 5         | 16.13%  |
| 0x406c4    | 3         | 9.68%   |
| 0x206a7    | 3         | 9.68%   |
| 0x906ed    | 2         | 6.45%   |
| 0x806c1    | 2         | 6.45%   |
| 0x706a8    | 2         | 6.45%   |
| 0x1067a    | 2         | 6.45%   |
| 0xa0653    | 1         | 3.23%   |
| 0x906e9    | 1         | 3.23%   |
| 0x806ec    | 1         | 3.23%   |
| 0x806ea    | 1         | 3.23%   |
| 0x706a1    | 1         | 3.23%   |
| 0x6fd      | 1         | 3.23%   |
| 0x40651    | 1         | 3.23%   |
| 0x306c3    | 1         | 3.23%   |
| 0x07030105 | 1         | 3.23%   |
| 0x06006705 | 1         | 3.23%   |
| 0x06000852 | 1         | 3.23%   |
| Unknown    | 1         | 3.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| Zen+          | 6         | 19.35%  |
| KabyLake      | 5         | 16.13%  |
| Silvermont    | 3         | 9.68%   |
| SandyBridge   | 3         | 9.68%   |
| Goldmont plus | 3         | 9.68%   |
| TigerLake     | 2         | 6.45%   |
| Penryn        | 2         | 6.45%   |
| Haswell       | 2         | 6.45%   |
| Puma          | 1         | 3.23%   |
| Piledriver    | 1         | 3.23%   |
| Excavator     | 1         | 3.23%   |
| Core          | 1         | 3.23%   |
| CometLake     | 1         | 3.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 19        | 54.29%  |
| AMD    | 9         | 25.71%  |
| Nvidia | 7         | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 17.14%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 8.57%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 5.71%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 5.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 5.71%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 5.71%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 5.71%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1         | 2.86%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 2.86%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 2.86%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 2.86%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 1         | 2.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 2.86%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.86%   |
| Intel HD Graphics 630                                                                    | 1         | 2.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.86%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 2.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.86%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1         | 2.86%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                                        | 1         | 2.86%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 2.86%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 2.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 15        | 48.39%  |
| 1 x AMD        | 9         | 29.03%  |
| Intel + Nvidia | 4         | 12.9%   |
| 1 x Nvidia     | 3         | 9.68%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 26        | 83.87%  |
| Proprietary | 5         | 16.13%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 67.74%  |
| 1.01-2.0   | 6         | 19.35%  |
| 0.51-1.0   | 3         | 9.68%   |
| 0.01-0.5   | 1         | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 9         | 30%     |
| Chimei Innolux       | 6         | 20%     |
| LG Display           | 4         | 13.33%  |
| AU Optronics         | 4         | 13.33%  |
| Samsung Electronics  | 2         | 6.67%   |
| Philips              | 1         | 3.33%   |
| NEC Computers        | 1         | 3.33%   |
| Goldstar             | 1         | 3.33%   |
| AOC                  | 1         | 3.33%   |
| Ancor Communications | 1         | 3.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE07AA 1366x768 344x194mm 15.5-inch                  | 6         | 20%     |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 10%     |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 6.67%   |
| Philips FTV PHL04C3 1920x1080 1440x810mm 65.0-inch                    | 1         | 3.33%   |
| NEC Computers EA223WM NEC688F 1680x1050 474x296mm 22.0-inch           | 1         | 3.33%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch          | 1         | 3.33%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 1         | 3.33%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 3.33%   |
| LG Display LCD Monitor LGD03FB 1920x1080 382x215mm 17.3-inch          | 1         | 3.33%   |
| Goldstar D2342P GSM5842 1920x1080 510x290mm 23.1-inch                 | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 1         | 3.33%   |
| BOE LCD Monitor BOE0839 1920x1080 382x215mm 17.3-inch                 | 1         | 3.33%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 1         | 3.33%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                  | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch         | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch         | 1         | 3.33%   |
| AOC 32G2WG3 AOC3202 1920x1080 698x393mm 31.5-inch                     | 1         | 3.33%   |
| Ancor Communications ASUS VS229 ACI22C2 1920x1080 477x268mm 21.5-inch | 1         | 3.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 16        | 55.17%  |
| 1920x1080 (FHD)    | 9         | 31.03%  |
| 3840x2160 (4K)     | 2         | 6.9%    |
| 1680x1050 (WSXGA+) | 1         | 3.45%   |
| 1600x900 (HD+)     | 1         | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 18        | 60%     |
| 17     | 3         | 10%     |
| 14     | 2         | 6.67%   |
| 13     | 2         | 6.67%   |
| 65     | 1         | 3.33%   |
| 31     | 1         | 3.33%   |
| 23     | 1         | 3.33%   |
| 22     | 1         | 3.33%   |
| 21     | 1         | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 66.67%  |
| 351-400     | 5         | 16.67%  |
| 401-500     | 2         | 6.67%   |
| 601-700     | 1         | 3.33%   |
| 501-600     | 1         | 3.33%   |
| 1001-1500   | 1         | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 28        | 96.55%  |
| 16/10 | 1         | 3.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 60%     |
| 81-90          | 4         | 13.33%  |
| 201-250        | 3         | 10%     |
| 121-130        | 3         | 10%     |
| More than 1000 | 1         | 3.33%   |
| 351-500        | 1         | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 16        | 53.33%  |
| 121-160 | 8         | 26.67%  |
| 51-100  | 5         | 16.67%  |
| 1-50    | 1         | 3.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 29        | 93.55%  |
| 2     | 1         | 3.23%   |
| 0     | 1         | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 22        | 52.38%  |
| Intel                    | 11        | 26.19%  |
| Qualcomm Atheros         | 6         | 14.29%  |
| Microsoft                | 1         | 2.38%   |
| Marvell Technology Group | 1         | 2.38%   |
| Broadcom                 | 1         | 2.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 19.15%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 17.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 8.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 4.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 4.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 4.26%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 4.26%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 4.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 2.13%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 2.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 2.13%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.13%   |
| Microsoft XBOX ACC                                                | 1         | 2.13%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 2.13%   |
| Intel Wireless 8265 / 8275                                        | 1         | 2.13%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 2.13%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 2.13%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 2.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 2.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.13%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 2.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 2.13%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 13        | 43.33%  |
| Intel                 | 9         | 30%     |
| Qualcomm Atheros      | 6         | 20%     |
| Microsoft             | 1         | 3.33%   |
| Broadcom              | 1         | 3.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 30%     |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 6.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 6.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 6.67%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 6.67%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 6.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 3.33%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 3.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 3.33%   |
| Microsoft XBOX ACC                                             | 1         | 3.33%   |
| Intel Wireless 8265 / 8275                                     | 1         | 3.33%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 1         | 3.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 3.33%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 3.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1         | 3.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 12        | 70.59%  |
| Intel                    | 3         | 17.65%  |
| Qualcomm Atheros         | 1         | 5.88%   |
| Marvell Technology Group | 1         | 5.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 47.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 23.53%  |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 5.88%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 5.88%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 5.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 5.88%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 5.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 63.83%  |
| Ethernet | 17        | 36.17%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 90.63%  |
| Ethernet | 3         | 9.38%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 17        | 54.84%  |
| 2     | 14        | 45.16%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 17        | 54.84%  |
| Yes  | 14        | 45.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| IMC Networks                    | 10        | 43.48%  |
| Intel                           | 6         | 26.09%  |
| Realtek Semiconductor           | 2         | 8.7%    |
| Qualcomm Atheros Communications | 1         | 4.35%   |
| Lite-On Technology              | 1         | 4.35%   |
| Dell                            | 1         | 4.35%   |
| Cambridge Silicon Radio         | 1         | 4.35%   |
| Broadcom                        | 1         | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Bluetooth Radio                        | 8         | 34.78%  |
| Realtek RTL8821A Bluetooth                          | 2         | 8.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 8.7%    |
| Intel AX200 Bluetooth                               | 2         | 8.7%    |
| IMC Networks Bluetooth Device                       | 2         | 8.7%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 4.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 4.35%   |
| Intel Bluetooth wireless interface                  | 1         | 4.35%   |
| Intel AX201 Bluetooth                               | 1         | 4.35%   |
| Dell DW375 Bluetooth Module                         | 1         | 4.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.35%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 21        | 60%     |
| AMD    | 9         | 25.71%  |
| Nvidia | 5         | 14.29%  |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 13.04%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 13.04%  |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 6.52%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 4.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 4.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 4.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 4.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 4.35%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 2.17%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 2.17%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 2.17%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 2.17%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.17%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 2.17%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 2.17%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 2.17%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 2.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 2.17%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 2.17%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 2.17%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 2.17%   |
| AMD High Definition Audio Controller                                                              | 1         | 2.17%   |
| AMD FCH Azalia Controller                                                                         | 1         | 2.17%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 2.17%   |

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

| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Sonix Technology              | 7         | 26.92%  |
| IMC Networks                  | 6         | 23.08%  |
| Chicony Electronics           | 5         | 19.23%  |
| Microdia                      | 2         | 7.69%   |
| Suyin                         | 1         | 3.85%   |
| Sunplus Innovation Technology | 1         | 3.85%   |
| Silicon Motion                | 1         | 3.85%   |
| Quanta                        | 1         | 3.85%   |
| Apple                         | 1         | 3.85%   |
| Acer                          | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Sonix USB2.0 HD UVC WebCam           | 6         | 23.08%  |
| IMC Networks USB2.0 VGA UVC WebCam   | 5         | 19.23%  |
| Chicony HD User Facing               | 2         | 7.69%   |
| Suyin UVC 1.3MPixel WebCam           | 1         | 3.85%   |
| Sunplus Laptop_Integrated_Webcam_FHD | 1         | 3.85%   |
| Sonix USB2.0 VGAUVC WebCam           | 1         | 3.85%   |
| Silicon Motion WebCam SC-0311139N    | 1         | 3.85%   |
| Quanta HD User Facing                | 1         | 3.85%   |
| Microdia Integrated_Webcam_HD        | 1         | 3.85%   |
| Microdia Integrated Camera           | 1         | 3.85%   |
| IMC Networks USB2.0 HD UVC WebCam    | 1         | 3.85%   |
| Chicony USB2.0 HD UVC WebCam         | 1         | 3.85%   |
| Chicony HP Truevision HD camera      | 1         | 3.85%   |
| Chicony EasyCamera                   | 1         | 3.85%   |
| Apple iPhone5/5C/5S/6                | 1         | 3.85%   |
| Acer EasyCamera                      | 1         | 3.85%   |

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

| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 24        | 77.42%  |
| 1     | 6         | 19.35%  |
| 2     | 1         | 3.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 5         | 62.5%   |
| Storage               | 1         | 12.5%   |
| Net/wireless          | 1         | 12.5%   |
| Chipcard              | 1         | 12.5%   |

