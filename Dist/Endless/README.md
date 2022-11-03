Endless - Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Endless/Desktop/README.md) and [notebooks](/Dist/Endless/Notebook/README.md).

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

![OS](./All/images/pie_chart/os_name.svg)

![OS](./All/images/line_chart/os_name.svg)

| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Endless 4.0.10        | 13        | 46.43%  |
| Endless 4.0.9         | 8         | 28.57%  |
| Endless 4.0.4         | 2         | 7.14%   |
| Endless 4.0.8         | 1         | 3.57%   |
| Endless 3.9.7         | 1         | 3.57%   |
| Endless 3.9.3-nexthw1 | 1         | 3.57%   |
| Endless 3.7.8         | 1         | 3.57%   |
| Endless 3.7.7-nexthw1 | 1         | 3.57%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Endless | 28        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.11.0-35-generic | 24        | 85.71%  |
| 5.8.0-14-generic  | 1         | 3.57%   |
| 5.4.0-7-generic   | 1         | 3.57%   |
| 5.3.0-28-generic  | 1         | 3.57%   |
| 5.11.0-12-generic | 1         | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 25        | 89.29%  |
| 5.8.0   | 1         | 3.57%   |
| 5.4.0   | 1         | 3.57%   |
| 5.3.0   | 1         | 3.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 25        | 89.29%  |
| 5.8     | 1         | 3.57%   |
| 5.4     | 1         | 3.57%   |
| 5.3     | 1         | 3.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 28        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name  | Computers | Percent |
|-------|-----------|---------|
| GNOME | 28        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 28        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 28        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 11        | 39.29%  |
| pt_BR | 7         | 25%     |
| de_DE | 3         | 10.71%  |
| sl_SI | 1         | 3.57%   |
| ro_RO | 1         | 3.57%   |
| pt_PT | 1         | 3.57%   |
| es_MX | 1         | 3.57%   |
| es_ES | 1         | 3.57%   |
| es_CO | 1         | 3.57%   |
| bs_BA | 1         | 3.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 19        | 67.86%  |
| BIOS | 9         | 32.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type | Computers | Percent |
|------|-----------|---------|
| Ext4 | 28        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 28        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 28        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 28        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 9         | 32.14%  |
| Acer                | 9         | 32.14%  |
| Dell                | 4         | 14.29%  |
| ASRock              | 2         | 7.14%   |
| Toshiba             | 1         | 3.57%   |
| Lenovo              | 1         | 3.57%   |
| Hewlett-Packard     | 1         | 3.57%   |
| Gigabyte Technology | 1         | 3.57%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Acer Nitro AN515-44                        | 3         | 10.71%  |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 2         | 7.14%   |
| Toshiba NB300                              | 1         | 3.57%   |
| Lenovo G500 20236                          | 1         | 3.57%   |
| HP G71                                     | 1         | 3.57%   |
| Gigabyte Z77X-UP4 TH                       | 1         | 3.57%   |
| Dell XPS 13 9360                           | 1         | 3.57%   |
| Dell OptiPlex 3010                         | 1         | 3.57%   |
| Dell Latitude E6530                        | 1         | 3.57%   |
| Dell Inspiron 3542                         | 1         | 3.57%   |
| ASUS X540NA                                | 1         | 3.57%   |
| ASUS X505BP                                | 1         | 3.57%   |
| ASUS VivoBook_ASUSLaptop X513EAN_F513EA    | 1         | 3.57%   |
| ASUS VivoBook_ASUSLaptop X415MA_X415MA     | 1         | 3.57%   |
| ASUS VivoBook_ASUSLaptop E510MAB_E510MA    | 1         | 3.57%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 1         | 3.57%   |
| ASUS ASUS Vivo AIO V222GAR_V222GA          | 1         | 3.57%   |
| ASRock H61M-DGS                            | 1         | 3.57%   |
| ASRock A320M-DGS                           | 1         | 3.57%   |
| Acer Swift SF314-511                       | 1         | 3.57%   |
| Acer Swift SF113-31                        | 1         | 3.57%   |
| Acer Predator G3-571                       | 1         | 3.57%   |
| Acer Aspire A317-52                        | 1         | 3.57%   |
| Acer Aspire A315-34                        | 1         | 3.57%   |
| Acer Aspire 5750                           | 1         | 3.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name              | Computers | Percent |
|-------------------|-----------|---------|
| ASUS VivoBook     | 6         | 21.43%  |
| Acer Nitro        | 3         | 10.71%  |
| Acer Aspire       | 3         | 10.71%  |
| Acer Swift        | 2         | 7.14%   |
| Toshiba NB300     | 1         | 3.57%   |
| Lenovo G500       | 1         | 3.57%   |
| HP G71            | 1         | 3.57%   |
| Gigabyte Z77X-UP4 | 1         | 3.57%   |
| Dell XPS          | 1         | 3.57%   |
| Dell OptiPlex     | 1         | 3.57%   |
| Dell Latitude     | 1         | 3.57%   |
| Dell Inspiron     | 1         | 3.57%   |
| ASUS X540NA       | 1         | 3.57%   |
| ASUS X505BP       | 1         | 3.57%   |
| ASUS ASUS         | 1         | 3.57%   |
| ASRock H61M-DGS   | 1         | 3.57%   |
| ASRock A320M-DGS  | 1         | 3.57%   |
| Acer Predator     | 1         | 3.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 5         | 17.86%  |
| 2017 | 5         | 17.86%  |
| 2021 | 4         | 14.29%  |
| 2012 | 4         | 14.29%  |
| 2019 | 2         | 7.14%   |
| 2018 | 2         | 7.14%   |
| 2009 | 2         | 7.14%   |
| 2016 | 1         | 3.57%   |
| 2014 | 1         | 3.57%   |
| 2013 | 1         | 3.57%   |
| 2011 | 1         | 3.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 23        | 82.14%  |
| Desktop    | 4         | 14.29%  |
| All in one | 1         | 3.57%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 22        | 78.57%  |
| Enabled  | 6         | 21.43%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 28        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 12        | 42.86%  |
| 4.01-8.0   | 10        | 35.71%  |
| 16.01-24.0 | 3         | 10.71%  |
| 32.01-64.0 | 1         | 3.57%   |
| 1.01-2.0   | 1         | 3.57%   |
| 8.01-16.0  | 1         | 3.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 15        | 53.57%  |
| 2.01-3.0 | 8         | 28.57%  |
| 0.51-1.0 | 3         | 10.71%  |
| 3.01-4.0 | 2         | 7.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 26        | 92.86%  |
| 2      | 2         | 7.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 20        | 71.43%  |
| Yes       | 8         | 28.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 67.86%  |
| No        | 9         | 32.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 89.29%  |
| No        | 3         | 10.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 78.57%  |
| No        | 6         | 21.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country                | Computers | Percent |
|------------------------|-----------|---------|
| Brazil                 | 7         | 25%     |
| USA                    | 5         | 17.86%  |
| Germany                | 4         | 14.29%  |
| Romania                | 2         | 7.14%   |
| Spain                  | 1         | 3.57%   |
| Slovenia               | 1         | 3.57%   |
| Portugal               | 1         | 3.57%   |
| Kazakhstan             | 1         | 3.57%   |
| India                  | 1         | 3.57%   |
| Georgia                | 1         | 3.57%   |
| Colombia               | 1         | 3.57%   |
| Bosnia and Herzegovina | 1         | 3.57%   |
| Australia              | 1         | 3.57%   |
| Argentina              | 1         | 3.57%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City              | Computers | Percent |
|-------------------|-----------|---------|
| Goiânia          | 2         | 7.14%   |
| Fortaleza         | 2         | 7.14%   |
| Dallas            | 2         | 7.14%   |
| Willcox           | 1         | 3.57%   |
| San Francisco     | 1         | 3.57%   |
| Salvador          | 1         | 3.57%   |
| Rio de Janeiro    | 1         | 3.57%   |
| Recife            | 1         | 3.57%   |
| Rathenow          | 1         | 3.57%   |
| Port Townsend     | 1         | 3.57%   |
| Mula              | 1         | 3.57%   |
| Lukavica          | 1         | 3.57%   |
| Ljubljana         | 1         | 3.57%   |
| Lisbon            | 1         | 3.57%   |
| K'alak'i T'bilisi | 1         | 3.57%   |
| Hanover           | 1         | 3.57%   |
| Göttingen        | 1         | 3.57%   |
| Frankfurt am Main | 1         | 3.57%   |
| Córdoba          | 1         | 3.57%   |
| Brisbane          | 1         | 3.57%   |
| Branesti          | 1         | 3.57%   |
| Bogotá           | 1         | 3.57%   |
| Bhopal            | 1         | 3.57%   |
| Aktau             | 1         | 3.57%   |
| Agigea            | 1         | 3.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 4         | 4      | 13.79%  |
| Sandisk                     | 4         | 4      | 13.79%  |
| Samsung Electronics         | 4         | 4      | 13.79%  |
| Kingston                    | 4         | 4      | 13.79%  |
| WDC                         | 2         | 2      | 6.9%    |
| Toshiba                     | 2         | 2      | 6.9%    |
| Micron Technology           | 2         | 2      | 6.9%    |
| Crucial                     | 2         | 2      | 6.9%    |
| Win Memory                  | 1         | 1      | 3.45%   |
| Kingston Technology Company | 1         | 1      | 3.45%   |
| Intel                       | 1         | 1      | 3.45%   |
| China                       | 1         | 1      | 3.45%   |
| Apple                       | 1         | 1      | 3.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 4         | 13.79%  |
| Micron 2210_MTFDHBA512QFD 512GB                     | 2         | 6.9%    |
| Win Memory SWR256G-301II 256GB                      | 1         | 3.45%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 1         | 3.45%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 1         | 3.45%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 3.45%   |
| Toshiba MK2555GSX 250GB                             | 1         | 3.45%   |
| Seagate ST9320325AS 320GB                           | 1         | 3.45%   |
| Seagate ST500LM030-1RK17D 500GB                     | 1         | 3.45%   |
| Seagate ST3500312CS 500GB                           | 1         | 3.45%   |
| Seagate ST3000DM001-9YN166 3TB                      | 1         | 3.45%   |
| Samsung SSD SM841 2.5 7mm 256GB                     | 1         | 3.45%   |
| Samsung SSD 860 EVO M.2 500GB                       | 1         | 3.45%   |
| Samsung SSD 750 EVO 250GB                           | 1         | 3.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 250GB | 1         | 3.45%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB             | 1         | 3.45%   |
| Kingston RBUSNS8180DS3128GH 128GB SSD               | 1         | 3.45%   |
| Kingston RBUSC180DS37256GJ 256GB SSD                | 1         | 3.45%   |
| Kingston RBUSC180DS37128GJ 128GB SSD                | 1         | 3.45%   |
| Kingston OM8P0S3256B-AB 256GB SSD                   | 1         | 3.45%   |
| Intel Micron_2210_MTFDHBA1T0QFD 1024GB              | 1         | 3.45%   |
| Crucial CT500MX500SSD1 500GB                        | 1         | 3.45%   |
| Crucial CT240M500SSD1 240GB                         | 1         | 3.45%   |
| China SSD 240GB                                     | 1         | 3.45%   |
| Apple HDD HTS545050A7E362 500GB                     | 1         | 3.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 44.44%  |
| WDC     | 2         | 2      | 22.22%  |
| Toshiba | 2         | 2      | 22.22%  |
| Apple   | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 4         | 4      | 36.36%  |
| Samsung Electronics | 3         | 3      | 27.27%  |
| Crucial             | 2         | 2      | 18.18%  |
| Win Memory          | 1         | 1      | 9.09%   |
| China               | 1         | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 11        | 11     | 37.93%  |
| NVMe | 9         | 9      | 31.03%  |
| HDD  | 9         | 9      | 31.03%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 20        | 20     | 68.97%  |
| NVMe | 9         | 9      | 31.03%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 16        | 16     | 80%     |
| 0.51-1.0   | 3         | 3      | 15%     |
| 2.01-3.0   | 1         | 1      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 12        | 42.86%  |
| 251-500    | 9         | 32.14%  |
| 501-1000   | 4         | 14.29%  |
| 2001-3000  | 1         | 3.57%   |
| 1-20       | 1         | 3.57%   |
| Unknown    | 1         | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB | Computers | Percent |
|---------|-----------|---------|
| 21-50   | 13        | 46.43%  |
| 101-250 | 5         | 17.86%  |
| 51-100  | 5         | 17.86%  |
| 1-20    | 3         | 10.71%  |
| 251-500 | 1         | 3.57%   |
| Unknown | 1         | 3.57%   |

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
| Detected | 28        | 29     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 23        | 63.89%  |
| AMD                         | 5         | 13.89%  |
| SanDisk                     | 4         | 11.11%  |
| Micron Technology           | 2         | 5.56%   |
| Samsung Electronics         | 1         | 2.78%   |
| Kingston Technology Company | 1         | 2.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 5         | 12.82%  |
| AMD FCH SATA Controller [AHCI mode]                                           | 5         | 12.82%  |
| SanDisk WD Blue SN550 NVMe SSD                                                | 4         | 10.26%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 3         | 7.69%   |
| Micron Non-Volatile memory controller                                         | 2         | 5.13%   |
| Intel Volume Management Device NVMe RAID Controller                           | 2         | 5.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 2         | 5.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 2         | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2         | 5.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1         | 2.56%   |
| Kingston Company OM3PDP3 NVMe SSD                                             | 1         | 2.56%   |
| Intel Tiger Lake-LP SATA Controller                                           | 1         | 2.56%   |
| Intel PROSet/Wireless WiFi Software extension                                 | 1         | 2.56%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 1         | 2.56%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 1         | 2.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 1         | 2.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1         | 2.56%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 1         | 2.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 1         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 1         | 2.56%   |
| AMD FCH SATA Controller D                                                     | 1         | 2.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 25        | 65.79%  |
| NVMe | 9         | 23.68%  |
| RAID | 4         | 10.53%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 23        | 82.14%  |
| AMD    | 5         | 17.86%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Celeron N4020 CPU @ 1.10GHz            | 2         | 7.14%   |
| AMD Ryzen 7 4800H with Radeon Graphics       | 2         | 7.14%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz     | 1         | 3.57%   |
| Intel Pentium CPU N4200 @ 1.10GHz            | 1         | 3.57%   |
| Intel Pentium CPU G620 @ 2.60GHz             | 1         | 3.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz           | 1         | 3.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz            | 1         | 3.57%   |
| Intel Core i7-3520M CPU @ 2.90GHz            | 1         | 3.57%   |
| Intel Core i5-4210U CPU @ 1.70GHz            | 1         | 3.57%   |
| Intel Core i5-3570K CPU @ 3.40GHz            | 1         | 3.57%   |
| Intel Core i5-3470 CPU @ 3.20GHz             | 1         | 3.57%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz           | 1         | 3.57%   |
| Intel Core i3-7100U CPU @ 2.40GHz            | 1         | 3.57%   |
| Intel Core i3-7020U CPU @ 2.30GHz            | 1         | 3.57%   |
| Intel Core i3-3110M CPU @ 2.40GHz            | 1         | 3.57%   |
| Intel Core i3-2350M CPU @ 2.30GHz            | 1         | 3.57%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz         | 1         | 3.57%   |
| Intel Celeron N4000 CPU @ 1.10GHz            | 1         | 3.57%   |
| Intel Celeron J4025 CPU @ 2.00GHz            | 1         | 3.57%   |
| Intel Celeron CPU N3350 @ 1.10GHz            | 1         | 3.57%   |
| Intel Atom CPU N450 @ 1.66GHz                | 1         | 3.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz      | 1         | 3.57%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 1         | 3.57%   |
| AMD Ryzen 5 4600H with Radeon Graphics       | 1         | 3.57%   |
| AMD Ryzen 3 1200 Quad-Core Processor         | 1         | 3.57%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 3.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Celeron        | 5         | 17.86%  |
| Intel Core i5        | 4         | 14.29%  |
| Intel Core i3        | 4         | 14.29%  |
| Other                | 3         | 10.71%  |
| Intel Core i7        | 3         | 10.71%  |
| Intel Pentium        | 2         | 7.14%   |
| AMD Ryzen 7          | 2         | 7.14%   |
| Intel Pentium Silver | 1         | 3.57%   |
| Intel Core 2 Duo     | 1         | 3.57%   |
| Intel Atom           | 1         | 3.57%   |
| AMD Ryzen 5          | 1         | 3.57%   |
| AMD Ryzen 3          | 1         | 3.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 15        | 53.57%  |
| 4      | 9         | 32.14%  |
| 8      | 2         | 7.14%   |
| 6      | 1         | 3.57%   |
| 1      | 1         | 3.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 28        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 15        | 53.57%  |
| 1      | 13        | 46.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 28        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x706a8    | 4         | 14.29%  |
| 0x306a9    | 4         | 14.29%  |
| 0x806e9    | 3         | 10.71%  |
| 0x08600103 | 3         | 10.71%  |
| 0x806c1    | 2         | 7.14%   |
| 0x506c9    | 2         | 7.14%   |
| 0x206a7    | 2         | 7.14%   |
| 0x906e9    | 1         | 3.57%   |
| 0x706e5    | 1         | 3.57%   |
| 0x706a1    | 1         | 3.57%   |
| 0x40651    | 1         | 3.57%   |
| 0x106ca    | 1         | 3.57%   |
| 0x1067a    | 1         | 3.57%   |
| 0x08001138 | 1         | 3.57%   |
| 0x06006705 | 1         | 3.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| Goldmont plus | 5         | 17.86%  |
| KabyLake      | 4         | 14.29%  |
| IvyBridge     | 4         | 14.29%  |
| Zen 2         | 3         | 10.71%  |
| TigerLake     | 2         | 7.14%   |
| SandyBridge   | 2         | 7.14%   |
| Goldmont      | 2         | 7.14%   |
| Zen           | 1         | 3.57%   |
| Penryn        | 1         | 3.57%   |
| IceLake       | 1         | 3.57%   |
| Haswell       | 1         | 3.57%   |
| Excavator     | 1         | 3.57%   |
| Bonnell       | 1         | 3.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 22        | 64.71%  |
| Nvidia | 8         | 23.53%  |
| AMD    | 4         | 11.76%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                              | Computers | Percent |
|------------------------------------------------------------------------------------|-----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                                | 4         | 11.43%  |
| Nvidia TU117M                                                                      | 3         | 8.57%   |
| Intel HD Graphics 620                                                              | 3         | 8.57%   |
| AMD Renoir                                                                         | 3         | 8.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                          | 2         | 5.71%   |
| Intel 3rd Gen Core processor Graphics Controller                                   | 2         | 5.71%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller          | 2         | 5.71%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                            | 1         | 2.86%   |
| Nvidia GM204 [GeForce GTX 970]                                                     | 1         | 2.86%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]               | 1         | 2.86%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                  | 1         | 2.86%   |
| Nvidia GF108GLM [NVS 5200M]                                                        | 1         | 2.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                   | 1         | 2.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                       | 1         | 2.86%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                             | 1         | 2.86%   |
| Intel HD Graphics 630                                                              | 1         | 2.86%   |
| Intel HD Graphics 500                                                              | 1         | 2.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                                   | 1         | 2.86%   |
| Intel GeminiLake [UHD Graphics 605]                                                | 1         | 2.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller | 1         | 2.86%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller            | 1         | 2.86%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                             | 1         | 2.86%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                           | 1         | 2.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 19        | 67.86%  |
| Intel + Nvidia | 3         | 10.71%  |
| AMD + Nvidia   | 3         | 10.71%  |
| 1 x Nvidia     | 2         | 7.14%   |
| 2 x AMD        | 1         | 3.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 23        | 82.14%  |
| Proprietary | 5         | 17.86%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 75%     |
| 0.01-0.5   | 3         | 10.71%  |
| 1.01-2.0   | 2         | 7.14%   |
| 3.01-4.0   | 1         | 3.57%   |
| 0.51-1.0   | 1         | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| BOE                 | 7         | 28%     |
| PANDA               | 5         | 20%     |
| LG Display          | 5         | 20%     |
| Chimei Innolux      | 2         | 8%      |
| AU Optronics        | 2         | 8%      |
| Sharp               | 1         | 4%      |
| Samsung Electronics | 1         | 4%      |
| Dell                | 1         | 4%      |
| Acer                | 1         | 4%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 3         | 12%     |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 2         | 8%      |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch              | 1         | 4%      |
| Samsung Electronics LCD Monitor SEC544E 1024x600 223x125mm 10.1-inch | 1         | 4%      |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch              | 1         | 4%      |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch              | 1         | 4%      |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 1         | 4%      |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 1         | 4%      |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch         | 1         | 4%      |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 1         | 4%      |
| LG Display LCD Monitor LGD0226 1600x900 382x215mm 17.3-inch          | 1         | 4%      |
| Dell G2410 DEL404B 1920x1080 531x298mm 24.0-inch                     | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 1         | 4%      |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                | 1         | 4%      |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 1         | 4%      |
| BOE LCD Monitor BOE0788 1920x1080 381x214mm 17.2-inch                | 1         | 4%      |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                 | 1         | 4%      |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                | 1         | 4%      |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 1         | 4%      |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 1         | 4%      |
| Acer XV240Y ACR082E 1920x1080 527x296mm 23.8-inch                    | 1         | 4%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution      | Computers | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 15        | 60%     |
| 1366x768 (WXGA) | 8         | 32%     |
| 1600x900 (HD+)  | 1         | 4%      |
| 1024x600        | 1         | 4%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 16        | 64%     |
| 13     | 3         | 12%     |
| 17     | 2         | 8%      |
| 24     | 1         | 4%      |
| 23     | 1         | 4%      |
| 14     | 1         | 4%      |
| 10     | 1         | 4%      |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 18        | 72%     |
| 201-300     | 3         | 12%     |
| 501-600     | 2         | 8%      |
| 351-400     | 2         | 8%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 25        | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 64%     |
| 81-90          | 2         | 8%      |
| 71-80          | 2         | 8%      |
| 201-250        | 2         | 8%      |
| 121-130        | 2         | 8%      |
| 41-50          | 1         | 4%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 11        | 44%     |
| 101-120 | 10        | 40%     |
| 161-240 | 2         | 8%      |
| 51-100  | 2         | 8%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 24        | 85.71%  |
| 0     | 3         | 10.71%  |
| 2     | 1         | 3.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 19        | 44.19%  |
| Intel                 | 11        | 25.58%  |
| Qualcomm Atheros      | 7         | 16.28%  |
| Ralink Technology     | 2         | 4.65%   |
| Broadcom              | 2         | 4.65%   |
| Samsung Electronics   | 1         | 2.33%   |
| Belkin Components     | 1         | 2.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 9         | 20%     |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 6.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 3         | 6.67%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 3         | 6.67%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 6.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 4.44%   |
| Intel Wireless 8265 / 8275                                              | 2         | 4.44%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 4.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 1         | 2.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 2.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 2.22%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 2.22%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 2.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 2.22%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 2.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 2.22%   |
| Intel Wireless 7265                                                     | 1         | 2.22%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 2.22%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 2.22%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 1         | 2.22%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 1         | 2.22%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 2.22%   |
| Belkin Components F7D1101 v1 Basic Wireless Adapter [Realtek RTL8188SU] | 1         | 2.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 11        | 42.31%  |
| Qualcomm Atheros      | 6         | 23.08%  |
| Realtek Semiconductor | 5         | 19.23%  |
| Ralink Technology     | 2         | 7.69%   |
| Broadcom              | 1         | 3.85%   |
| Belkin Components     | 1         | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 11.54%  |
| Intel Wi-Fi 6 AX200                                                     | 3         | 11.54%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 7.69%   |
| Intel Wireless 8265 / 8275                                              | 2         | 7.69%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 7.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 3.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 3.85%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 3.85%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 3.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 3.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 3.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 3.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 3.85%   |
| Intel Wireless 7265                                                     | 1         | 3.85%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 3.85%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 3.85%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 3.85%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 3.85%   |
| Belkin Components F7D1101 v1 Basic Wireless Adapter [Realtek RTL8188SU] | 1         | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 15        | 78.95%  |
| Samsung Electronics   | 1         | 5.26%   |
| Qualcomm Atheros      | 1         | 5.26%   |
| Intel                 | 1         | 5.26%   |
| Broadcom              | 1         | 5.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 47.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 15.79%  |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 15.79%  |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 5.26%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 5.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 5.26%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 5.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 56.82%  |
| Ethernet | 19        | 43.18%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 23        | 85.19%  |
| Ethernet | 4         | 14.81%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 14        | 50%     |
| 2     | 12        | 42.86%  |
| 3     | 1         | 3.57%   |
| 0     | 1         | 3.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 18        | 64.29%  |
| Yes  | 10        | 35.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 45.45%  |
| IMC Networks                    | 4         | 18.18%  |
| Qualcomm Atheros Communications | 2         | 9.09%   |
| Lite-On Technology              | 2         | 9.09%   |
| Toshiba                         | 1         | 4.55%   |
| Foxconn International           | 1         | 4.55%   |
| Dell                            | 1         | 4.55%   |
| Cambridge Silicon Radio         | 1         | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 18.18%  |
| IMC Networks Bluetooth Radio                        | 4         | 18.18%  |
| Intel AX200 Bluetooth                               | 3         | 13.64%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 9.09%   |
| Intel AX201 Bluetooth                               | 2         | 9.09%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 4.55%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 4.55%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 4.55%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 4.55%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 4.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 23        | 67.65%  |
| Nvidia | 7         | 20.59%  |
| AMD    | 4         | 11.76%  |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 13.89%  |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 8.33%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 8.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 8.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 8.33%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 8.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 5.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 5.56%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 2.78%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 2.78%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 2.78%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 2.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 2.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 2.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.78%   |
| Intel CM238 HD Audio Controller                                            | 1         | 2.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.78%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.78%   |
| AMD High Definition Audio Controller                                       | 1         | 2.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 2.78%   |

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

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)

![Printer Vendor](./All/images/line_chart/printer_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 1         | 50%     |
| Samsung Electronics | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)

![Printer Model](./All/images/line_chart/printer_model.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L355 Series | 1         | 50%     |
| Samsung M2020 Series    | 1         | 50%     |

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
| Quanta                | 9         | 36%     |
| IMC Networks          | 6         | 24%     |
| Chicony Electronics   | 4         | 16%     |
| Microdia              | 3         | 12%     |
| Suyin                 | 1         | 4%      |
| Realtek Semiconductor | 1         | 4%      |
| Aveo Technology       | 1         | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam | 6         | 24%     |
| Quanta HD User Facing              | 3         | 12%     |
| Quanta USB2.0 HD UVC WebCam        | 2         | 8%      |
| Suyin USB 2.0 Camera               | 1         | 4%      |
| Realtek Lenovo EasyCamera          | 1         | 4%      |
| Quanta VGA WebCam                  | 1         | 4%      |
| Quanta USB2.0 VGA UVC WebCam       | 1         | 4%      |
| Quanta HP Webcam-101               | 1         | 4%      |
| Quanta HD Webcam                   | 1         | 4%      |
| Microdia Integrated_Webcam_HD      | 1         | 4%      |
| Microdia Integrated Webcam HD      | 1         | 4%      |
| Microdia Dell Integrated HD Webcam | 1         | 4%      |
| Chicony VGA WebCam                 | 1         | 4%      |
| Chicony HD WebCam                  | 1         | 4%      |
| Chicony HD User Facing             | 1         | 4%      |
| Chicony 1.3M HD WebCam             | 1         | 4%      |
| Aveo USB2.0 Camera                 | 1         | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| LighTuning Technology | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| LighTuning EgisTec Touch Fingerprint Sensor | 1         | 100%    |

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
| 0     | 22        | 78.57%  |
| 1     | 6         | 21.43%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 3         | 50%     |
| Net/wireless          | 1         | 16.67%  |
| Fingerprint reader    | 1         | 16.67%  |
| Chipcard              | 1         | 16.67%  |

