Elementary - Hardware Trends
----------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary/Desktop/README.md) and [notebooks](/Dist/Elementary/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/linuxhw/TestCoverage)

Period: Jul, 2022.

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
| Elementary 6.1 | 45        | 97.83%  |
| Elementary 6   | 1         | 2.17%   |

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

| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-41-generic | 21        | 45.65%  |
| 5.13.0-52-generic | 16        | 34.78%  |
| 5.13.0-51-generic | 3         | 6.52%   |
| 5.11.0-43-generic | 3         | 6.52%   |
| 5.4.0-122-generic | 1         | 2.17%   |
| 5.13.0-28-generic | 1         | 2.17%   |
| 5.11.0-25-generic | 1         | 2.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 21        | 45.65%  |
| 5.13.0  | 20        | 43.48%  |
| 5.11.0  | 4         | 8.7%    |
| 5.4.0   | 1         | 2.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 21        | 45.65%  |
| 5.13    | 20        | 43.48%  |
| 5.11    | 4         | 8.7%    |
| 5.4     | 1         | 2.17%   |

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
| Unknown | 37        | 80.43%  |
| LightDM | 9         | 19.57%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 17        | 36.96%  |
| de_DE | 5         | 10.87%  |
| ru_RU | 3         | 6.52%   |
| pt_BR | 3         | 6.52%   |
| it_IT | 3         | 6.52%   |
| es_ES | 3         | 6.52%   |
| uk_UA | 2         | 4.35%   |
| nl_NL | 2         | 4.35%   |
| en_GB | 2         | 4.35%   |
| en_AU | 2         | 4.35%   |
| tr_TR | 1         | 2.17%   |
| fr_FR | 1         | 2.17%   |
| fi_FI | 1         | 2.17%   |
| C     | 1         | 2.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 31        | 67.39%  |
| BIOS | 15        | 32.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 43        | 93.48%  |
| Xfs     | 1         | 2.17%   |
| Overlay | 1         | 2.17%   |
| Btrfs   | 1         | 2.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 39        | 84.78%  |
| GPT     | 6         | 13.04%  |
| MBR     | 1         | 2.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 91.3%   |
| Yes       | 4         | 8.7%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 93.48%  |
| Yes       | 3         | 6.52%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 19.57%  |
| Dell                | 7         | 15.22%  |
| ASUSTek Computer    | 7         | 15.22%  |
| Apple               | 5         | 10.87%  |
| Acer                | 5         | 10.87%  |
| Lenovo              | 4         | 8.7%    |
| Sony                | 2         | 4.35%   |
| MSI                 | 2         | 4.35%   |
| Gigabyte Technology | 2         | 4.35%   |
| Intel               | 1         | 2.17%   |
| HUAWEI              | 1         | 2.17%   |
| Casper              | 1         | 2.17%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| HP Notebook                            | 2         | 4.35%   |
| Sony VPCYB20AL                         | 1         | 2.17%   |
| Sony SVF1521F6EW                       | 1         | 2.17%   |
| MSI MS-7B84                            | 1         | 2.17%   |
| MSI MS-7A38                            | 1         | 2.17%   |
| Lenovo ThinkPad T480 20L6S9WY00        | 1         | 2.17%   |
| Lenovo IdeaPad Yoga 13 20175           | 1         | 2.17%   |
| Lenovo IdeaPad S540-14API 81NH         | 1         | 2.17%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1    | 1         | 2.17%   |
| Intel X79                              | 1         | 2.17%   |
| HUAWEI HLYL-WXX9                       | 1         | 2.17%   |
| HP ProBook 430 G2                      | 1         | 2.17%   |
| HP Pavilion g6                         | 1         | 2.17%   |
| HP Pavilion g4                         | 1         | 2.17%   |
| HP Laptop 15-dy1xxx                    | 1         | 2.17%   |
| HP EliteBook 8460p                     | 1         | 2.17%   |
| HP EliteBook 845 G8 Notebook PC        | 1         | 2.17%   |
| HP 255 G7 Notebook PC                  | 1         | 2.17%   |
| Gigabyte Z87X-OC                       | 1         | 2.17%   |
| Gigabyte GA-78LMT-USB3 6.0             | 1         | 2.17%   |
| Dell XPS 15 9500                       | 1         | 2.17%   |
| Dell XPS 13 9360                       | 1         | 2.17%   |
| Dell OptiPlex 9020                     | 1         | 2.17%   |
| Dell Latitude E6320                    | 1         | 2.17%   |
| Dell Latitude D630                     | 1         | 2.17%   |
| Dell Latitude 3190                     | 1         | 2.17%   |
| Dell Inspiron 3593                     | 1         | 2.17%   |
| Casper NIRVANA NOTEBOOK                | 1         | 2.17%   |
| ASUS VivoBook_ASUSLaptop X509JB_R521JB | 1         | 2.17%   |
| ASUS TUF X470-PLUS GAMING              | 1         | 2.17%   |
| ASUS ROG STRIX B450-F GAMING           | 1         | 2.17%   |
| ASUS ROG STRIX B360-H GAMING           | 1         | 2.17%   |
| ASUS P8H61-M LX R2.0                   | 1         | 2.17%   |
| ASUS N56VB                             | 1         | 2.17%   |
| ASUS K43E                              | 1         | 2.17%   |
| Apple MacBookPro8,1                    | 1         | 2.17%   |
| Apple MacBookPro11,5                   | 1         | 2.17%   |
| Apple MacBook4,1                       | 1         | 2.17%   |
| Apple iMac7,1                          | 1         | 2.17%   |
| Apple iMac11,2                         | 1         | 2.17%   |
| Acer Aspire X1420G                     | 1         | 2.17%   |
| Acer Aspire V3-771                     | 1         | 2.17%   |
| Acer Aspire AV15-51                    | 1         | 2.17%   |
| Acer Aspire A315-32                    | 1         | 2.17%   |
| Acer Aspire 1830T                      | 1         | 2.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Acer Aspire            | 5         | 10.87%  |
| Lenovo IdeaPad         | 3         | 6.52%   |
| Dell Latitude          | 3         | 6.52%   |
| HP Pavilion            | 2         | 4.35%   |
| HP Notebook            | 2         | 4.35%   |
| HP EliteBook           | 2         | 4.35%   |
| Dell XPS               | 2         | 4.35%   |
| ASUS ROG               | 2         | 4.35%   |
| Sony VPCYB20AL         | 1         | 2.17%   |
| Sony SVF1521F6EW       | 1         | 2.17%   |
| MSI MS-7B84            | 1         | 2.17%   |
| MSI MS-7A38            | 1         | 2.17%   |
| Lenovo ThinkPad        | 1         | 2.17%   |
| Intel X79              | 1         | 2.17%   |
| HUAWEI HLYL-WXX9       | 1         | 2.17%   |
| HP ProBook             | 1         | 2.17%   |
| HP Laptop              | 1         | 2.17%   |
| HP 255                 | 1         | 2.17%   |
| Gigabyte Z87X-OC       | 1         | 2.17%   |
| Gigabyte GA-78LMT-USB3 | 1         | 2.17%   |
| Dell OptiPlex          | 1         | 2.17%   |
| Dell Inspiron          | 1         | 2.17%   |
| Casper NIRVANA         | 1         | 2.17%   |
| ASUS VivoBook          | 1         | 2.17%   |
| ASUS TUF               | 1         | 2.17%   |
| ASUS P8H61-M           | 1         | 2.17%   |
| ASUS N56VB             | 1         | 2.17%   |
| ASUS K43E              | 1         | 2.17%   |
| Apple MacBookPro8      | 1         | 2.17%   |
| Apple MacBookPro11     | 1         | 2.17%   |
| Apple MacBook4         | 1         | 2.17%   |
| Apple iMac7            | 1         | 2.17%   |
| Apple iMac11           | 1         | 2.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 7         | 15.22%  |
| 2019 | 6         | 13.04%  |
| 2018 | 6         | 13.04%  |
| 2021 | 5         | 10.87%  |
| 2012 | 4         | 8.7%    |
| 2016 | 3         | 6.52%   |
| 2014 | 3         | 6.52%   |
| 2010 | 3         | 6.52%   |
| 2020 | 2         | 4.35%   |
| 2013 | 2         | 4.35%   |
| 2007 | 2         | 4.35%   |
| 2017 | 1         | 2.17%   |
| 2015 | 1         | 2.17%   |
| 2008 | 1         | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 33        | 71.74%  |
| Desktop    | 11        | 23.91%  |
| All in one | 2         | 4.35%   |

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
| No   | 46        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 13        | 28.26%  |
| 4.01-8.0    | 11        | 23.91%  |
| 16.01-24.0  | 10        | 21.74%  |
| 8.01-16.0   | 7         | 15.22%  |
| 32.01-64.0  | 3         | 6.52%   |
| 64.01-256.0 | 1         | 2.17%   |
| 1.01-2.0    | 1         | 2.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 18        | 39.13%  |
| 2.01-3.0  | 16        | 34.78%  |
| 3.01-4.0  | 6         | 13.04%  |
| 4.01-8.0  | 3         | 6.52%   |
| 8.01-16.0 | 2         | 4.35%   |
| 0.51-1.0  | 1         | 2.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 33        | 71.74%  |
| 2      | 9         | 19.57%  |
| 3      | 2         | 4.35%   |
| 5      | 1         | 2.17%   |
| 4      | 1         | 2.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 25        | 54.35%  |
| Yes       | 21        | 45.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 80.43%  |
| No        | 9         | 19.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 86.96%  |
| No        | 6         | 13.04%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 80.43%  |
| No        | 9         | 19.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 10        | 21.74%  |
| Germany     | 6         | 13.04%  |
| Brazil      | 4         | 8.7%    |
| UK          | 3         | 6.52%   |
| Russia      | 3         | 6.52%   |
| Italy       | 3         | 6.52%   |
| Netherlands | 2         | 4.35%   |
| Venezuela   | 1         | 2.17%   |
| Ukraine     | 1         | 2.17%   |
| Turkey      | 1         | 2.17%   |
| Portugal    | 1         | 2.17%   |
| Poland      | 1         | 2.17%   |
| Norway      | 1         | 2.17%   |
| Mexico      | 1         | 2.17%   |
| Iran        | 1         | 2.17%   |
| Indonesia   | 1         | 2.17%   |
| Hungary     | 1         | 2.17%   |
| France      | 1         | 2.17%   |
| Finland     | 1         | 2.17%   |
| Belgium     | 1         | 2.17%   |
| Australia   | 1         | 2.17%   |
| Argentina   | 1         | 2.17%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Hamburg              | 2         | 4.35%   |
| Ypres                | 1         | 2.17%   |
| Wroclaw              | 1         | 2.17%   |
| Vladivostok          | 1         | 2.17%   |
| Villa Bosch          | 1         | 2.17%   |
| Uden                 | 1         | 2.17%   |
| Traben-Trarbach      | 1         | 2.17%   |
| The Hague            | 1         | 2.17%   |
| Tehran               | 1         | 2.17%   |
| Taubate              | 1         | 2.17%   |
| Tampere              | 1         | 2.17%   |
| Sydney               | 1         | 2.17%   |
| Sunnyvale            | 1         | 2.17%   |
| Stuttgart            | 1         | 2.17%   |
| Stockton-on-Tees     | 1         | 2.17%   |
| Seattle              | 1         | 2.17%   |
| Santa Teresa di Riva | 1         | 2.17%   |
| Rome                 | 1         | 2.17%   |
| Oaxaca City          | 1         | 2.17%   |
| Nottingham           | 1         | 2.17%   |
| Naples               | 1         | 2.17%   |
| Munich               | 1         | 2.17%   |
| Moscow               | 1         | 2.17%   |
| Mérida              | 1         | 2.17%   |
| Lowell               | 1         | 2.17%   |
| Loures               | 1         | 2.17%   |
| Louisville           | 1         | 2.17%   |
| Liverpool            | 1         | 2.17%   |
| Ligonier             | 1         | 2.17%   |
| Kryvyi Rih           | 1         | 2.17%   |
| Istanbul             | 1         | 2.17%   |
| Henderson            | 1         | 2.17%   |
| Foz do Iguaçu       | 1         | 2.17%   |
| Forest Park          | 1         | 2.17%   |
| Denver               | 1         | 2.17%   |
| Cologne              | 1         | 2.17%   |
| Chelyabinsk          | 1         | 2.17%   |
| Chartres             | 1         | 2.17%   |
| Caxias do Sul        | 1         | 2.17%   |
| Calhoun              | 1         | 2.17%   |
| Budapest             | 1         | 2.17%   |
| Bogor                | 1         | 2.17%   |
| Bergen               | 1         | 2.17%   |
| Belo Horizonte       | 1         | 2.17%   |
| Austin               | 1         | 2.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 10     | 16.95%  |
| Samsung Electronics | 9         | 11     | 15.25%  |
| Seagate             | 8         | 8      | 13.56%  |
| Toshiba             | 4         | 6      | 6.78%   |
| Kingston            | 4         | 5      | 6.78%   |
| HGST                | 4         | 4      | 6.78%   |
| SanDisk             | 2         | 2      | 3.39%   |
| PNY                 | 2         | 2      | 3.39%   |
| Micron Technology   | 2         | 2      | 3.39%   |
| KIOXIA              | 2         | 2      | 3.39%   |
| ZTE                 | 1         | 1      | 1.69%   |
| UMIS                | 1         | 1      | 1.69%   |
| SK hynix            | 1         | 1      | 1.69%   |
| Silicon Motion      | 1         | 1      | 1.69%   |
| Plextor             | 1         | 1      | 1.69%   |
| Patriot             | 1         | 1      | 1.69%   |
| Lexar               | 1         | 1      | 1.69%   |
| KingFast            | 1         | 1      | 1.69%   |
| China               | 1         | 1      | 1.69%   |
| BORY                | 1         | 1      | 1.69%   |
| Apple               | 1         | 1      | 1.69%   |
| A-DATA Technology   | 1         | 1      | 1.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| WDC WD10EZEX-00BN5A0 1TB                    | 2         | 3.17%   |
| Samsung SSD 860 QVO 1TB                     | 2         | 3.17%   |
| ZTE MMC Storage 942MB                       | 1         | 1.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD            | 1         | 1.59%   |
| WDC WD5000BPVT-60HXZT3 500GB                | 1         | 1.59%   |
| WDC WD1600BEKT-08PVMT1 160GB                | 1         | 1.59%   |
| WDC WD10SPZX-60Z10T0 1TB                    | 1         | 1.59%   |
| WDC WD10SPZX-24Z10 1TB                      | 1         | 1.59%   |
| WDC WD10SPZX-21Z10T0 1TB                    | 1         | 1.59%   |
| WDC WD10JPVX-60JC3T0 1TB                    | 1         | 1.59%   |
| WDC WD10EADX-22TDHB0 1TB                    | 1         | 1.59%   |
| UMIS RPFTJ256PDD2MWX 256GB                  | 1         | 1.59%   |
| Toshiba NVMe SSD Drive 512GB                | 1         | 1.59%   |
| Toshiba MQ01ABF050 500GB                    | 1         | 1.59%   |
| Toshiba HDWD130 3TB                         | 1         | 1.59%   |
| Toshiba DT01ACA300 3TB                      | 1         | 1.59%   |
| Toshiba DT01ACA100 1TB                      | 1         | 1.59%   |
| SK hynix NVMe SSD Drive 256GB               | 1         | 1.59%   |
| Silicon Motion NVMe SSD Drive 128GB         | 1         | 1.59%   |
| Seagate ST9500420AS 500GB                   | 1         | 1.59%   |
| Seagate ST9320325AS 320GB                   | 1         | 1.59%   |
| Seagate ST500LT012-9WS142 500GB             | 1         | 1.59%   |
| Seagate ST3500418AS 500GB                   | 1         | 1.59%   |
| Seagate ST3250820AS Q 250GB                 | 1         | 1.59%   |
| Seagate ST2000DM008-2FR102 2TB              | 1         | 1.59%   |
| Seagate BarraCuda Q1 SSD ZA960CV10001 960GB | 1         | 1.59%   |
| Seagate Backup+ Hub BK 4TB                  | 1         | 1.59%   |
| SanDisk SDSSDA120G 120GB                    | 1         | 1.59%   |
| SanDisk NVMe SSD Drive 1024GB               | 1         | 1.59%   |
| Samsung SSD 980 500GB                       | 1         | 1.59%   |
| Samsung SSD 860 EVO 250GB                   | 1         | 1.59%   |
| Samsung SSD 850 EVO M.2 250GB               | 1         | 1.59%   |
| Samsung SSD 840 EVO 120GB                   | 1         | 1.59%   |
| Samsung NVMe SSD Drive 512GB                | 1         | 1.59%   |
| Samsung MZMPC128HBFU-000L1 128GB SSD        | 1         | 1.59%   |
| Samsung MZALQ512HBLU-00BL2 512GB            | 1         | 1.59%   |
| Samsung MZ7TE128HMGR-000H1 128GB SSD        | 1         | 1.59%   |
| Samsung HD502HI 500GB                       | 1         | 1.59%   |
| PNY SSD2SC240G1CS1754D117-820 240GB         | 1         | 1.59%   |
| PNY CS900 240GB SSD                         | 1         | 1.59%   |
| Plextor PX-64M5S 64GB SSD                   | 1         | 1.59%   |
| Patriot Burst 240GB SSD                     | 1         | 1.59%   |
| Micron NVMe SSD Drive 256GB                 | 1         | 1.59%   |
| Micron 2200S NVMe 512GB                     | 1         | 1.59%   |
| Lexar 128GB SSD                             | 1         | 1.59%   |
| KIOXIA NVMe SSD Drive 256GB                 | 1         | 1.59%   |
| KIOXIA NVMe SSD Drive 128GB                 | 1         | 1.59%   |
| Kingston SV300S37A240G 240GB SSD            | 1         | 1.59%   |
| Kingston SA400S37960G 960GB SSD             | 1         | 1.59%   |
| Kingston SA400S37240G 240GB SSD             | 1         | 1.59%   |
| Kingston NVMe SSD Drive 512GB               | 1         | 1.59%   |
| Kingston NVMe SSD Drive 500GB               | 1         | 1.59%   |
| KingFast 1024GB                             | 1         | 1.59%   |
| HGST HTS725050A7E630 500GB                  | 1         | 1.59%   |
| HGST HTS721010A9E630 1TB                    | 1         | 1.59%   |
| HGST HTS541010B7E610 1TB                    | 1         | 1.59%   |
| HGST HTS541010A9E680 1TB                    | 1         | 1.59%   |
| China SSD 512GB                             | 1         | 1.59%   |
| BORY R500 1TB                               | 1         | 1.59%   |
| Apple SSD SM1024G 1TB                       | 1         | 1.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 37.5%   |
| Seagate             | 7         | 7      | 29.17%  |
| HGST                | 4         | 4      | 16.67%  |
| Toshiba             | 3         | 5      | 12.5%   |
| Samsung Electronics | 1         | 1      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 30%     |
| Kingston            | 3         | 3      | 15%     |
| PNY                 | 2         | 2      | 10%     |
| WDC                 | 1         | 1      | 5%      |
| Seagate             | 1         | 1      | 5%      |
| SanDisk             | 1         | 1      | 5%      |
| Plextor             | 1         | 1      | 5%      |
| Patriot             | 1         | 1      | 5%      |
| Lexar               | 1         | 1      | 5%      |
| China               | 1         | 1      | 5%      |
| Apple               | 1         | 1      | 5%      |
| A-DATA Technology   | 1         | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 23        | 26     | 39.66%  |
| SSD     | 19        | 21     | 32.76%  |
| NVMe    | 13        | 14     | 22.41%  |
| Unknown | 3         | 3      | 5.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 36        | 48     | 70.59%  |
| NVMe | 13        | 14     | 25.49%  |
| SAS  | 2         | 2      | 3.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 23        | 25     | 54.76%  |
| 0.51-1.0   | 15        | 17     | 35.71%  |
| 2.01-3.0   | 2         | 3      | 4.76%   |
| 3.01-4.0   | 1         | 1      | 2.38%   |
| 1.01-2.0   | 1         | 1      | 2.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 19        | 41.3%   |
| 501-1000       | 13        | 28.26%  |
| 251-500        | 10        | 21.74%  |
| More than 3000 | 2         | 4.35%   |
| 2001-3000      | 1         | 2.17%   |
| 51-100         | 1         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 20        | 43.48%  |
| 21-50          | 8         | 17.39%  |
| 101-250        | 6         | 13.04%  |
| 251-500        | 5         | 10.87%  |
| 51-100         | 3         | 6.52%   |
| 1001-2000      | 2         | 4.35%   |
| More than 3000 | 1         | 2.17%   |
| 501-1000       | 1         | 2.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Kingston SV300S37A240G 240GB SSD | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Kingston | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 100%    |

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
| Detected | 39        | 52     | 84.78%  |
| Works    | 6         | 11     | 13.04%  |
| Malfunc  | 1         | 1      | 2.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 29        | 53.7%   |
| AMD                          | 10        | 18.52%  |
| Samsung Electronics          | 3         | 5.56%   |
| Micron Technology            | 2         | 3.7%    |
| KIOXIA                       | 2         | 3.7%    |
| Kingston Technology Company  | 2         | 3.7%    |
| Union Memory (Shenzhen)      | 1         | 1.85%   |
| Toshiba America Info Systems | 1         | 1.85%   |
| SK hynix                     | 1         | 1.85%   |
| Silicon Motion               | 1         | 1.85%   |
| SanDisk                      | 1         | 1.85%   |
| Nvidia                       | 1         | 1.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 6         | 9.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 7.94%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 6.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 3         | 4.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 4.76%   |
| Micron Non-Volatile memory controller                                                   | 2         | 3.17%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 2         | 3.17%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 3.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 3.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 3.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 3.17%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 1         | 1.59%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1         | 1.59%   |
| SK hynix Gold P31 SSD                                                                   | 1         | 1.59%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 1.59%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 1.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 1.59%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 1.59%   |
| Samsung Electronics SATA controller                                                     | 1         | 1.59%   |
| Nvidia MCP61 SATA Controller                                                            | 1         | 1.59%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1         | 1.59%   |
| Kingston Company A2000 NVMe SSD                                                         | 1         | 1.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1         | 1.59%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1         | 1.59%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1         | 1.59%   |
| Intel SATA Controller [RAID mode]                                                       | 1         | 1.59%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 1         | 1.59%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1         | 1.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1         | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 1         | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 1         | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 1.59%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1         | 1.59%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1         | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1         | 1.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 34        | 57.63%  |
| NVMe | 13        | 22.03%  |
| IDE  | 8         | 13.56%  |
| RAID | 4         | 6.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 33        | 71.74%  |
| AMD    | 13        | 28.26%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 2         | 4.35%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz              | 1         | 2.17%   |
| Intel Pentium CPU B950 @ 2.10GHz                | 1         | 2.17%   |
| Intel Core i7-7560U CPU @ 2.40GHz               | 1         | 2.17%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz              | 1         | 2.17%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1         | 2.17%   |
| Intel Core i7-3632QM CPU @ 2.20GHz              | 1         | 2.17%   |
| Intel Core i7-2620M CPU @ 2.70GHz               | 1         | 2.17%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1         | 2.17%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 2.17%   |
| Intel Core i5-9400F CPU @ 2.90GHz               | 1         | 2.17%   |
| Intel Core i5-8350U CPU @ 1.70GHz               | 1         | 2.17%   |
| Intel Core i5-4670K CPU @ 3.40GHz               | 1         | 2.17%   |
| Intel Core i5-3317U CPU @ 1.70GHz               | 1         | 2.17%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 1         | 2.17%   |
| Intel Core i5-2540M CPU @ 2.60GHz               | 1         | 2.17%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 1         | 2.17%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 1         | 2.17%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 1         | 2.17%   |
| Intel Core i3-5010U CPU @ 2.10GHz               | 1         | 2.17%   |
| Intel Core i3-3217U CPU @ 1.80GHz               | 1         | 2.17%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 1         | 2.17%   |
| Intel Core i3 CPU U 380 @ 1.33GHz               | 1         | 2.17%   |
| Intel Core i3 CPU 540 @ 3.07GHz                 | 1         | 2.17%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz            | 1         | 2.17%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz            | 1         | 2.17%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 2.17%   |
| Intel Celeron N4120 CPU @ 1.10GHz               | 1         | 2.17%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 2.17%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 1         | 2.17%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz         | 1         | 2.17%   |
| Intel 11th Gen Core i5-1155G7 @ 2.50GHz         | 1         | 2.17%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 1         | 2.17%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics      | 1         | 2.17%   |
| AMD Ryzen 5 4600H with Radeon Graphics          | 1         | 2.17%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1         | 2.17%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 1         | 2.17%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 1         | 2.17%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 1         | 2.17%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 1         | 2.17%   |
| AMD FX-8370E Eight-Core Processor               | 1         | 2.17%   |
| AMD E-240 Processor                             | 1         | 2.17%   |
| AMD Athlon II X4 645 Processor                  | 1         | 2.17%   |
| AMD A6-3400M APU with Radeon HD Graphics        | 1         | 2.17%   |
| AMD A12-9700P RADEON R7, 10 COMPUTE CORES 4C+6G | 1         | 2.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 8         | 17.39%  |
| Intel Core i3    | 8         | 17.39%  |
| Intel Core i7    | 7         | 15.22%  |
| AMD Ryzen 5      | 6         | 13.04%  |
| Intel Core 2 Duo | 3         | 6.52%   |
| Intel Celeron    | 3         | 6.52%   |
| Other            | 2         | 4.35%   |
| Intel Xeon       | 1         | 2.17%   |
| Intel Pentium    | 1         | 2.17%   |
| AMD Ryzen 7      | 1         | 2.17%   |
| AMD Ryzen 5 PRO  | 1         | 2.17%   |
| AMD FX           | 1         | 2.17%   |
| AMD E            | 1         | 2.17%   |
| AMD Athlon II X4 | 1         | 2.17%   |
| AMD A6           | 1         | 2.17%   |
| AMD A12          | 1         | 2.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 21        | 45.65%  |
| 4      | 16        | 34.78%  |
| 6      | 6         | 13.04%  |
| 8      | 2         | 4.35%   |
| 1      | 1         | 2.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 46        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 33        | 71.74%  |
| 1      | 13        | 28.26%  |

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
| 0x206a7    | 5         | 10.87%  |
| 0x306a9    | 4         | 8.7%    |
| 0x706e5    | 3         | 6.52%   |
| 0x306c3    | 2         | 4.35%   |
| 0x20655    | 2         | 4.35%   |
| 0x08108109 | 2         | 4.35%   |
| 0xa0652    | 1         | 2.17%   |
| 0x906ea    | 1         | 2.17%   |
| 0x806ea    | 1         | 2.17%   |
| 0x806e9    | 1         | 2.17%   |
| 0x806c2    | 1         | 2.17%   |
| 0x806c1    | 1         | 2.17%   |
| 0x706a8    | 1         | 2.17%   |
| 0x706a1    | 1         | 2.17%   |
| 0x6fd      | 1         | 2.17%   |
| 0x6fa      | 1         | 2.17%   |
| 0x406e3    | 1         | 2.17%   |
| 0x406c4    | 1         | 2.17%   |
| 0x40661    | 1         | 2.17%   |
| 0x306d4    | 1         | 2.17%   |
| 0x206d7    | 1         | 2.17%   |
| 0x10676    | 1         | 2.17%   |
| 0x0a50000c | 1         | 2.17%   |
| 0x08701021 | 1         | 2.17%   |
| 0x08701013 | 1         | 2.17%   |
| 0x08600104 | 1         | 2.17%   |
| 0x0810100b | 1         | 2.17%   |
| 0x0800820d | 1         | 2.17%   |
| 0x0600611a | 1         | 2.17%   |
| 0x06000852 | 1         | 2.17%   |
| 0x05000029 | 1         | 2.17%   |
| 0x03000027 | 1         | 2.17%   |
| 0x010000c8 | 1         | 2.17%   |
| Unknown    | 1         | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| SandyBridge   | 6         | 13.04%  |
| IvyBridge     | 5         | 10.87%  |
| Zen+          | 3         | 6.52%   |
| Zen 2         | 3         | 6.52%   |
| KabyLake      | 3         | 6.52%   |
| IceLake       | 3         | 6.52%   |
| Haswell       | 3         | 6.52%   |
| Westmere      | 2         | 4.35%   |
| TigerLake     | 2         | 4.35%   |
| Goldmont plus | 2         | 4.35%   |
| Core          | 2         | 4.35%   |
| Zen 3         | 1         | 2.17%   |
| Zen           | 1         | 2.17%   |
| Skylake       | 1         | 2.17%   |
| Silvermont    | 1         | 2.17%   |
| Piledriver    | 1         | 2.17%   |
| Penryn        | 1         | 2.17%   |
| K10 Llano     | 1         | 2.17%   |
| K10           | 1         | 2.17%   |
| Excavator     | 1         | 2.17%   |
| CometLake     | 1         | 2.17%   |
| Broadwell     | 1         | 2.17%   |
| Bobcat        | 1         | 2.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 27        | 51.92%  |
| AMD    | 18        | 34.62%  |
| Nvidia | 7         | 13.46%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 9.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 7.41%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 5.56%   |
| Nvidia GK107M [GeForce GT 740M]                                                          | 2         | 3.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 3.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 3.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 3.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 3.7%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 3.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 3.7%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 1.85%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 1.85%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1         | 1.85%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1.85%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.85%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.85%   |
| Intel Iris Plus Graphics 640                                                             | 1         | 1.85%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.85%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1.85%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.85%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                          | 1         | 1.85%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                                        | 1         | 1.85%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 1.85%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 1.85%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.85%   |
| AMD RV730/M96-XT [Mobility Radeon HD 4670]                                               | 1         | 1.85%   |
| AMD RV610/M74 [Mobility Radeon HD 2400 XT]                                               | 1         | 1.85%   |
| AMD RS780L [Radeon 3000]                                                                 | 1         | 1.85%   |
| AMD Renoir                                                                               | 1         | 1.85%   |
| AMD Redwood PRO GL [FirePro V3800]                                                       | 1         | 1.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.85%   |
| AMD Navi 24 [Radeon RX 6400 / 6500 XT]                                                   | 1         | 1.85%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1         | 1.85%   |
| AMD Cezanne                                                                              | 1         | 1.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 45.65%  |
| 1 x AMD        | 17        | 36.96%  |
| Intel + Nvidia | 5         | 10.87%  |
| 1 x Nvidia     | 2         | 4.35%   |
| Intel + AMD    | 1         | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 41        | 89.13%  |
| Proprietary | 5         | 10.87%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 50%     |
| 0.01-0.5   | 8         | 17.39%  |
| 1.01-2.0   | 6         | 13.04%  |
| 3.01-4.0   | 3         | 6.52%   |
| 0.51-1.0   | 3         | 6.52%   |
| 5.01-6.0   | 2         | 4.35%   |
| 2.01-3.0   | 1         | 2.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 7         | 12.96%  |
| Samsung Electronics     | 5         | 9.26%   |
| Chi Mei Optoelectronics | 5         | 9.26%   |
| Apple                   | 5         | 9.26%   |
| LG Display              | 4         | 7.41%   |
| BOE                     | 4         | 7.41%   |
| Hewlett-Packard         | 3         | 5.56%   |
| Goldstar                | 3         | 5.56%   |
| Chimei Innolux          | 3         | 5.56%   |
| Sony                    | 2         | 3.7%    |
| Sharp                   | 2         | 3.7%    |
| Dell                    | 2         | 3.7%    |
| AOC                     | 2         | 3.7%    |
| Vizio                   | 1         | 1.85%   |
| SANYO                   | 1         | 1.85%   |
| Philips                 | 1         | 1.85%   |
| InfoVision              | 1         | 1.85%   |
| Iiyama                  | 1         | 1.85%   |
| HannStar                | 1         | 1.85%   |
| Ancor Communications    | 1         | 1.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Vizio VO320E VIZ0035 1280x720 700x390mm 31.5-inch                         | 1         | 1.85%   |
| Sony TV SNYA401 1920x1080                                                 | 1         | 1.85%   |
| Sony TV SNY9600 1920x540 735x420mm 33.3-inch                              | 1         | 1.85%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 1         | 1.85%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                   | 1         | 1.85%   |
| SANYO Casper SAN2213 1600x900 304x228mm 15.0-inch                         | 1         | 1.85%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch         | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC3859 1366x768 293x165mm 13.2-inch      | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch      | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch     | 1         | 1.85%   |
| Philips PHL 275E1 PHLC20C 2560x1440 597x336mm 27.0-inch                   | 1         | 1.85%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch               | 1         | 1.85%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch               | 1         | 1.85%   |
| LG Display LCD Monitor LGD0360 1600x900 294x166mm 13.3-inch               | 1         | 1.85%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch               | 1         | 1.85%   |
| InfoVision LCD Monitor IVO8CDF 1920x1080 309x174mm 14.0-inch              | 1         | 1.85%   |
| Iiyama PL2483H IVM6138 1920x1080 531x299mm 24.0-inch                      | 1         | 1.85%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch               | 1         | 1.85%   |
| Hewlett-Packard P204 HPN3631 1600x900 432x240mm 19.5-inch                 | 1         | 1.85%   |
| Hewlett-Packard LE2201w HWP2843 1680x1050 473x296mm 22.0-inch             | 1         | 1.85%   |
| HannStar Hanns.G HH221 HSD20A9 1920x1080 477x268mm 21.5-inch              | 1         | 1.85%   |
| Goldstar M2094D-PZ GSM4E8F 1680x1050 433x270mm 20.1-inch                  | 1         | 1.85%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                 | 1         | 1.85%   |
| Goldstar E2360 GSM57E3 1920x1080 510x290mm 23.1-inch                      | 1         | 1.85%   |
| Dell SE2422HX DELA1CA 1920x1080 527x296mm 23.8-inch                       | 1         | 1.85%   |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                        | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch           | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch           | 1         | 1.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 1.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO15AB 1366x768 340x190mm 15.3-inch  | 1         | 1.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO1426 1280x800 303x190mm 14.1-inch  | 1         | 1.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO1113 1366x768 256x144mm 11.6-inch  | 1         | 1.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO1100 1366x768 256x144mm 11.6-inch  | 1         | 1.85%   |
| BOE LCD Monitor BOE08E7 1920x1080 344x193mm 15.5-inch                     | 1         | 1.85%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                     | 1         | 1.85%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 1         | 1.85%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                      | 1         | 1.85%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch            | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch             | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch            | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch             | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch             | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO0C9C 1920x1080 344x193mm 15.5-inch            | 1         | 1.85%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                    | 1         | 1.85%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                    | 1         | 1.85%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                     | 1         | 1.85%   |
| Apple Color LCD APP9CDE 1920x1080 475x267mm 21.5-inch                     | 1         | 1.85%   |
| Apple Color LCD APP9C6A 1680x1050 433x270mm 20.1-inch                     | 1         | 1.85%   |
| AOC F22 AOC2200 1920x1080 476x268mm 21.5-inch                             | 1         | 1.85%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                          | 1         | 1.85%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch     | 1         | 1.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 21        | 40.38%  |
| 1366x768 (WXGA)    | 16        | 30.77%  |
| 1680x1050 (WSXGA+) | 4         | 7.69%   |
| 1280x800 (WXGA)    | 3         | 5.77%   |
| 1600x900 (HD+)     | 2         | 3.85%   |
| 3840x2160 (4K)     | 1         | 1.92%   |
| 3200x1800 (QHD+)   | 1         | 1.92%   |
| 2880x1800          | 1         | 1.92%   |
| 2560x1440 (QHD)    | 1         | 1.92%   |
| 1920x540           | 1         | 1.92%   |
| 1920x1200 (WUXGA)  | 1         | 1.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 16        | 30.19%  |
| 13     | 8         | 15.09%  |
| 23     | 5         | 9.43%   |
| 21     | 4         | 7.55%   |
| 14     | 4         | 7.55%   |
| 11     | 3         | 5.66%   |
| 24     | 2         | 3.77%   |
| 22     | 2         | 3.77%   |
| 20     | 2         | 3.77%   |
| 72     | 1         | 1.89%   |
| 36     | 1         | 1.89%   |
| 33     | 1         | 1.89%   |
| 27     | 1         | 1.89%   |
| 19     | 1         | 1.89%   |
| 17     | 1         | 1.89%   |
| 16     | 1         | 1.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 40.38%  |
| 401-500     | 9         | 17.31%  |
| 201-300     | 8         | 15.38%  |
| 501-600     | 7         | 13.46%  |
| 351-400     | 4         | 7.69%   |
| 701-800     | 2         | 3.85%   |
| 1501-2000   | 1         | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 38        | 80.85%  |
| 16/10 | 8         | 17.02%  |
| 3/2   | 1         | 2.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 17        | 33.33%  |
| 81-90          | 9         | 17.65%  |
| 201-250        | 9         | 17.65%  |
| 151-200        | 5         | 9.8%    |
| 71-80          | 3         | 5.88%   |
| 51-60          | 3         | 5.88%   |
| More than 1000 | 1         | 1.96%   |
| 351-500        | 1         | 1.96%   |
| 301-350        | 1         | 1.96%   |
| 121-130        | 1         | 1.96%   |
| 501-1000       | 1         | 1.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 19        | 37.25%  |
| 121-160       | 14        | 27.45%  |
| 51-100        | 14        | 27.45%  |
| 1-50          | 2         | 3.92%   |
| More than 240 | 1         | 1.96%   |
| 161-240       | 1         | 1.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 38        | 82.61%  |
| 2     | 8         | 17.39%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 22        | 33.85%  |
| Intel                      | 16        | 24.62%  |
| Qualcomm Atheros           | 10        | 15.38%  |
| Broadcom                   | 8         | 12.31%  |
| Ralink Technology          | 2         | 3.08%   |
| Marvell Technology Group   | 2         | 3.08%   |
| ZTE WCDMA Technologies MSM | 1         | 1.54%   |
| TP-Link                    | 1         | 1.54%   |
| Ralink                     | 1         | 1.54%   |
| Qualcomm                   | 1         | 1.54%   |
| Nvidia                     | 1         | 1.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 12        | 14.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 7         | 8.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 3         | 3.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 3         | 3.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 2         | 2.44%   |
| Ralink MT7601U Wireless Adapter                                     | 2         | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 2         | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 2         | 2.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 2         | 2.44%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller             | 2         | 2.44%   |
| Intel Wireless 8265 / 8275                                          | 2         | 2.44%   |
| Intel Wi-Fi 6 AX201                                                 | 2         | 2.44%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 2         | 2.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 2         | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 2         | 2.44%   |
| Broadcom BCM4321 802.11a/b/g/n                                      | 2         | 2.44%   |
| ZTE WCDMA MSM ZTE MSM                                               | 1         | 1.22%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1         | 1.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 1         | 1.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 1         | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1         | 1.22%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                              | 1         | 1.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1         | 1.22%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                           | 1         | 1.22%   |
| Qualcomm QCNFA765 Wireless Network Adapter                          | 1         | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1         | 1.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 1         | 1.22%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 1         | 1.22%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 1         | 1.22%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 1         | 1.22%   |
| Nvidia MCP61 Ethernet                                               | 1         | 1.22%   |
| Intel Wireless-AC 9260                                              | 1         | 1.22%   |
| Intel Wi-Fi 6 AX200                                                 | 1         | 1.22%   |
| Intel I211 Gigabit Network Connection                               | 1         | 1.22%   |
| Intel Ethernet Connection I217-V                                    | 1         | 1.22%   |
| Intel Ethernet Connection I217-LM                                   | 1         | 1.22%   |
| Intel Ethernet Connection (7) I219-V                                | 1         | 1.22%   |
| Intel Ethernet Connection (4) I219-LM                               | 1         | 1.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                     | 1         | 1.22%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 1         | 1.22%   |
| Intel Centrino Ultimate-N 6300                                      | 1         | 1.22%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                   | 1         | 1.22%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                   | 1         | 1.22%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express            | 1         | 1.22%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                         | 1         | 1.22%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 1         | 1.22%   |
| Broadcom BCM4331 802.11a/b/g/n                                      | 1         | 1.22%   |
| Broadcom BCM43142 802.11b/g/n                                       | 1         | 1.22%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                   | 1         | 1.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 30.23%  |
| Realtek Semiconductor | 9         | 20.93%  |
| Qualcomm Atheros      | 9         | 20.93%  |
| Broadcom              | 7         | 16.28%  |
| Ralink Technology     | 2         | 4.65%   |
| TP-Link               | 1         | 2.33%   |
| Ralink                | 1         | 2.33%   |
| Qualcomm              | 1         | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 3         | 6.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 2         | 4.65%   |
| Ralink MT7601U Wireless Adapter                                     | 2         | 4.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 2         | 4.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 2         | 4.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 2         | 4.65%   |
| Intel Wireless 8265 / 8275                                          | 2         | 4.65%   |
| Intel Wi-Fi 6 AX201                                                 | 2         | 4.65%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 2         | 4.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 2         | 4.65%   |
| Broadcom BCM4321 802.11a/b/g/n                                      | 2         | 4.65%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1         | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 1         | 2.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 1         | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1         | 2.33%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                              | 1         | 2.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                           | 1         | 2.33%   |
| Qualcomm QCNFA765 Wireless Network Adapter                          | 1         | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1         | 2.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 1         | 2.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 1         | 2.33%   |
| Intel Wireless-AC 9260                                              | 1         | 2.33%   |
| Intel Wi-Fi 6 AX200                                                 | 1         | 2.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                     | 1         | 2.33%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 1         | 2.33%   |
| Intel Centrino Ultimate-N 6300                                      | 1         | 2.33%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                         | 1         | 2.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 1         | 2.33%   |
| Broadcom BCM4331 802.11a/b/g/n                                      | 1         | 2.33%   |
| Broadcom BCM43142 802.11b/g/n                                       | 1         | 2.33%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                   | 1         | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 19        | 50%     |
| Intel                      | 7         | 18.42%  |
| Qualcomm Atheros           | 5         | 13.16%  |
| Broadcom                   | 3         | 7.89%   |
| Marvell Technology Group   | 2         | 5.26%   |
| ZTE WCDMA Technologies MSM | 1         | 2.63%   |
| Nvidia                     | 1         | 2.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 30.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 17.95%  |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 7.69%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 5.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.13%   |
| ZTE WCDMA MSM ZTE MSM                                             | 1         | 2.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.56%   |
| Nvidia MCP61 Ethernet                                             | 1         | 2.56%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.56%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.56%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.56%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 2.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 2.56%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 51.95%  |
| Ethernet | 37        | 48.05%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 33        | 71.74%  |
| Ethernet | 13        | 28.26%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 29        | 63.04%  |
| 1     | 16        | 34.78%  |
| 0     | 1         | 2.17%   |

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
| Intel                           | 10        | 26.32%  |
| Apple                           | 5         | 13.16%  |
| Realtek Semiconductor           | 4         | 10.53%  |
| Foxconn / Hon Hai               | 3         | 7.89%   |
| Cambridge Silicon Radio         | 3         | 7.89%   |
| Qualcomm Atheros Communications | 2         | 5.26%   |
| Lite-On Technology              | 2         | 5.26%   |
| IMC Networks                    | 2         | 5.26%   |
| Dell                            | 2         | 5.26%   |
| Broadcom                        | 2         | 5.26%   |
| Realtek                         | 1         | 2.63%   |
| Ralink                          | 1         | 2.63%   |
| Edimax Technology               | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 3         | 7.89%   |
| Intel AX201 Bluetooth                               | 3         | 7.89%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 7.89%   |
| Realtek Bluetooth Radio                             | 2         | 5.26%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5.26%   |
| Apple Bluetooth Host Controller                     | 2         | 5.26%   |
| Apple Bluetooth HCI                                 | 2         | 5.26%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 2.63%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.63%   |
| Realtek Bluetooth Radio                             | 1         | 2.63%   |
| Ralink RT3290 Bluetooth                             | 1         | 2.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.63%   |
| Lite-On Bluetooth Device                            | 1         | 2.63%   |
| Intel Bluetooth Device                              | 1         | 2.63%   |
| Intel AX200 Bluetooth                               | 1         | 2.63%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.63%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 2.63%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 2.63%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.63%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 2.63%   |
| Edimax Bluetooth Adapter                            | 1         | 2.63%   |
| Dell Wireless 360 Bluetooth                         | 1         | 2.63%   |
| Dell DW375 Bluetooth Module                         | 1         | 2.63%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1         | 2.63%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.63%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 32        | 53.33%  |
| AMD                 | 17        | 28.33%  |
| Nvidia              | 5         | 8.33%   |
| C-Media Electronics | 3         | 5%      |
| Razer USA           | 1         | 1.67%   |
| Logitech            | 1         | 1.67%   |
| Creative Labs       | 1         | 1.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 6.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 6.94%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 5.56%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 4.17%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 4.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 4.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 4.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 4.17%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 2.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 2.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.78%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 2.78%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 2.78%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 2.78%   |
| Razer USA RC30-026902, Gaming Headset [Nari Essential, Wireless, Receiver]                        | 1         | 1.39%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.39%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 1.39%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.39%   |
| Logitech Headset H390                                                                             | 1         | 1.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.39%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.39%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.39%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.39%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 1         | 1.39%   |
| C-Media Electronics USB Microphone                                                                | 1         | 1.39%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 1         | 1.39%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                     | 1         | 1.39%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.39%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                                             | 1         | 1.39%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.39%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 1         | 1.39%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 1.39%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.39%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 1         | 1.39%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.39%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.39%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.39%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1         | 1.39%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 1.39%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 1.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 3         | 30%     |
| Micron Technology   | 2         | 20%     |
| Transcend           | 1         | 10%     |
| SK hynix            | 1         | 10%     |
| Crucial             | 1         | 10%     |
| Corsair             | 1         | 10%     |
| A-DATA Technology   | 1         | 10%     |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Transcend RAM JM3200HSE-16G 16384MB SODIMM DDR4 3200MT/s | 1         | 10%     |
| SK hynix RAM HMT42GR7BMR4C 16384MB DIMM DDR3 1066MT/s    | 1         | 10%     |
| Samsung RAM Module 2048MB SODIMM DDR3 1333MT/s           | 1         | 10%     |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s | 1         | 10%     |
| Samsung RAM M393B2K70DM0 16384MB DIMM DDR3 1066MT/s      | 1         | 10%     |
| Micron RAM Module 8192MB SODIMM DDR3 1600MT/s            | 1         | 10%     |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s    | 1         | 10%     |
| Crucial RAM Module 2048MB SODIMM DDR2 667MT/s            | 1         | 10%     |
| Corsair RAM Module 4096MB SODIMM DDR3 1333MT/s           | 1         | 10%     |
| A-DATA RAM Module 16384MB DIMM DDR4 2667MT/s             | 1         | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| DDR4 | 3         | 42.86%  |
| DDR3 | 3         | 42.86%  |
| DDR2 | 1         | 14.29%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 5         | 71.43%  |
| DIMM   | 2         | 28.57%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 16384 | 3         | 33.33%  |
| 8192  | 2         | 22.22%  |
| 4096  | 2         | 22.22%  |
| 2048  | 2         | 22.22%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 2         | 25%     |
| 2667  | 2         | 25%     |
| 1600  | 1         | 12.5%   |
| 1333  | 1         | 12.5%   |
| 1066  | 1         | 12.5%   |
| 667   | 1         | 12.5%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)

![Printer Vendor](./All/images/line_chart/printer_vendor.svg)

| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)

![Printer Model](./All/images/line_chart/printer_model.svg)

| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| HP OfficeJet 5200 series | 1         | 50%     |
| Brother MFC-J5335DW      | 1         | 50%     |

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
| Chicony Electronics                    | 7         | 20%     |
| Sunplus Innovation Technology          | 6         | 17.14%  |
| Quanta                                 | 5         | 14.29%  |
| Microdia                               | 3         | 8.57%   |
| IMC Networks                           | 3         | 8.57%   |
| Apple                                  | 3         | 8.57%   |
| Suyin                                  | 2         | 5.71%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.71%   |
| Realtek Semiconductor                  | 1         | 2.86%   |
| Logitech                               | 1         | 2.86%   |
| Alcor Micro                            | 1         | 2.86%   |
| Acer                                   | 1         | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                | 3         | 8.57%   |
| Quanta HP TrueVision HD Camera                              | 2         | 5.71%   |
| IMC Networks Integrated Camera                              | 2         | 5.71%   |
| Apple Built-in iSight                                       | 2         | 5.71%   |
| Suyin HP TrueVision HD Integrated Webcam                    | 1         | 2.86%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 2.86%   |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 2.86%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 2.86%   |
| Sunplus HD WebCam                                           | 1         | 2.86%   |
| Realtek Built-In Video Camera                               | 1         | 2.86%   |
| Quanta VGA WebCam                                           | 1         | 2.86%   |
| Quanta ov9734_techfront_camera                              | 1         | 2.86%   |
| Quanta HD User Facing                                       | 1         | 2.86%   |
| Microdia Integrated_Webcam_HD                               | 1         | 2.86%   |
| Microdia Integrated Webcam HD                               | 1         | 2.86%   |
| Microdia HDP Webcam USB                                     | 1         | 2.86%   |
| Logitech HD Webcam C615                                     | 1         | 2.86%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 1         | 2.86%   |
| Chicony UVC 1.00 device HD UVC WebCam                       | 1         | 2.86%   |
| Chicony Sony Visual Communication Camera                    | 1         | 2.86%   |
| Chicony Lenovo EasyCamera                                   | 1         | 2.86%   |
| Chicony Integrated Camera                                   | 1         | 2.86%   |
| Chicony HP TrueVision HD                                    | 1         | 2.86%   |
| Chicony HP HD Webcam                                        | 1         | 2.86%   |
| Chicony HP HD Camera                                        | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101        | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD     | 1         | 2.86%   |
| Apple FaceTime HD Camera                                    | 1         | 2.86%   |
| Alcor Micro Asus Integrated Webcam                          | 1         | 2.86%   |
| Acer Front Camera                                           | 1         | 2.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 3         | 60%     |
| Validity Sensors           | 1         | 20%     |
| Shenzhen Goodix Technology | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 20%     |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 20%     |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 20%     |
| Shenzhen Goodix FingerPrint                               | 1         | 20%     |
| Unknown                                                   | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./All/images/line_chart/chipcard_vendor.svg)

| Vendor   | Computers | Percent |
|----------|-----------|---------|
| O2 Micro | 1         | 50%     |
| Broadcom | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 34        | 73.91%  |
| 1     | 9         | 19.57%  |
| 2     | 3         | 6.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 35.71%  |
| Net/wireless          | 2         | 14.29%  |
| Graphics card         | 2         | 14.29%  |
| Chipcard              | 2         | 14.29%  |
| Bluetooth             | 2         | 14.29%  |
| Multimedia controller | 1         | 7.14%   |

