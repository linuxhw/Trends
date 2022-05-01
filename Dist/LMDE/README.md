LMDE Hardware Trends
--------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by LMDE users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/LMDE/Desktop/README.md) and [notebooks](/Dist/LMDE/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/linuxhw/TestCoverage)

Period: Apr, 2022.

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

| Name   | Computers | Percent |
|--------|-----------|---------|
| LMDE 5 | 34        | 85%     |
| LMDE 4 | 6         | 15%     |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| LMDE | 40        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.10.0-13-amd64      | 23        | 57.5%   |
| 5.10.0-12-amd64      | 6         | 15%     |
| 5.10.0-13-686        | 4         | 10%     |
| 4.19.0-20-amd64      | 3         | 7.5%    |
| 5.16.0-0.bpo.3-amd64 | 1         | 2.5%    |
| 4.19.0-20-686        | 1         | 2.5%    |
| 4.19.0-19-686        | 1         | 2.5%    |
| 4.19.0-13-amd64      | 1         | 2.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 33        | 82.5%   |
| 4.19.0  | 6         | 15%     |
| 5.16.0  | 1         | 2.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 33        | 82.5%   |
| 4.19    | 6         | 15%     |
| 5.16    | 1         | 2.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 34        | 85%     |
| i686   | 6         | 15%     |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 38        | 95%     |
| Cinnamon   | 2         | 5%      |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 40        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 29        | 72.5%   |
| LightDM | 11        | 27.5%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 19        | 47.5%   |
| ru_RU | 4         | 10%     |
| de_DE | 4         | 10%     |
| en_GB | 3         | 7.5%    |
| es_ES | 2         | 5%      |
| pt_BR | 1         | 2.5%    |
| pl_PL | 1         | 2.5%    |
| nl_AW | 1         | 2.5%    |
| it_IT | 1         | 2.5%    |
| fr_FR | 1         | 2.5%    |
| es_PE | 1         | 2.5%    |
| es_MX | 1         | 2.5%    |
| es_EC | 1         | 2.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 22        | 55%     |
| BIOS | 18        | 45%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 37        | 92.5%   |
| Tmpfs   | 2         | 5%      |
| Overlay | 1         | 2.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 29        | 72.5%   |
| GPT     | 9         | 22.5%   |
| MBR     | 2         | 5%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 39        | 97.5%   |
| Yes       | 1         | 2.5%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 87.5%   |
| Yes       | 5         | 12.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 8         | 20%     |
| ASUSTek Computer    | 6         | 15%     |
| Lenovo              | 5         | 12.5%   |
| Hewlett-Packard     | 5         | 12.5%   |
| Acer                | 5         | 12.5%   |
| MSI                 | 2         | 5%      |
| Toshiba             | 1         | 2.5%    |
| Samsung Electronics | 1         | 2.5%    |
| Panasonic           | 1         | 2.5%    |
| LincPlus            | 1         | 2.5%    |
| Howard Computers    | 1         | 2.5%    |
| Foxconn             | 1         | 2.5%    |
| Dixonsxp            | 1         | 2.5%    |
| ASRock              | 1         | 2.5%    |
| Apple               | 1         | 2.5%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Acer AOD270                         | 2         | 5%      |
| Toshiba Satellite L455              | 1         | 2.5%    |
| Samsung 730QDA                      | 1         | 2.5%    |
| Panasonic CF-H2BJJHZDE              | 1         | 2.5%    |
| MSI MS-7B79                         | 1         | 2.5%    |
| MSI MS-7977                         | 1         | 2.5%    |
| LincPlus LINNCPLUS P1               | 1         | 2.5%    |
| Lenovo Yoga 7 15ITL5 82BJ           | 1         | 2.5%    |
| Lenovo ThinkStation P510 30B5005CUS | 1         | 2.5%    |
| Lenovo ThinkPad W541 20EGS24J00     | 1         | 2.5%    |
| Lenovo ThinkCentre M720s 10SUS9KW00 | 1         | 2.5%    |
| Lenovo IdeaPadFlex 5 14ITL05 82HS   | 1         | 2.5%    |
| Howard Computers R7X                | 1         | 2.5%    |
| HP ProBook 450 G8 Notebook PC       | 1         | 2.5%    |
| HP Presario C500 (GF581UA#ABA)      | 1         | 2.5%    |
| HP Pavilion Laptop 15-eh1xxx        | 1         | 2.5%    |
| HP EliteBook 840 G1                 | 1         | 2.5%    |
| HP 14                               | 1         | 2.5%    |
| Foxconn Cinema Series               | 1         | 2.5%    |
| Dell XPS A2010                      | 1         | 2.5%    |
| Dell Vostro 3500                    | 1         | 2.5%    |
| Dell Precision 7520                 | 1         | 2.5%    |
| Dell Latitude E6400                 | 1         | 2.5%    |
| Dell Latitude 5511                  | 1         | 2.5%    |
| Dell Latitude 3410                  | 1         | 2.5%    |
| Dell Inspiron 660                   | 1         | 2.5%    |
| Dell Inspiron 14 5410 2-in-1        | 1         | 2.5%    |
| ASUS PRIME H610M-A D4               | 1         | 2.5%    |
| ASUS PRIME B350M-A                  | 1         | 2.5%    |
| ASUS P6T                            | 1         | 2.5%    |
| ASUS P5G41T-M LX3                   | 1         | 2.5%    |
| ASUS N61Jv                          | 1         | 2.5%    |
| ASUS 901                            | 1         | 2.5%    |
| ASRock A320M-DGS                    | 1         | 2.5%    |
| Apple MacBookPro14,1                | 1         | 2.5%    |
| Acer Aspire X3910                   | 1         | 2.5%    |
| Acer Aspire E5-553G                 | 1         | 2.5%    |
| Acer AOA110                         | 1         | 2.5%    |
| Unknown                             | 1         | 2.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell Latitude          | 3         | 7.5%    |
| Dell Inspiron          | 2         | 5%      |
| ASUS PRIME             | 2         | 5%      |
| Acer Aspire            | 2         | 5%      |
| Acer AOD270            | 2         | 5%      |
| Toshiba Satellite      | 1         | 2.5%    |
| Samsung 730QDA         | 1         | 2.5%    |
| Panasonic CF-H2BJJHZDE | 1         | 2.5%    |
| MSI MS-7B79            | 1         | 2.5%    |
| MSI MS-7977            | 1         | 2.5%    |
| LincPlus LINNCPLUS     | 1         | 2.5%    |
| Lenovo Yoga            | 1         | 2.5%    |
| Lenovo ThinkStation    | 1         | 2.5%    |
| Lenovo ThinkPad        | 1         | 2.5%    |
| Lenovo ThinkCentre     | 1         | 2.5%    |
| Lenovo IdeaPadFlex     | 1         | 2.5%    |
| Howard Computers R7X   | 1         | 2.5%    |
| HP ProBook             | 1         | 2.5%    |
| HP Presario            | 1         | 2.5%    |
| HP Pavilion            | 1         | 2.5%    |
| HP EliteBook           | 1         | 2.5%    |
| HP 14                  | 1         | 2.5%    |
| Foxconn Cinema         | 1         | 2.5%    |
| Dell XPS               | 1         | 2.5%    |
| Dell Vostro            | 1         | 2.5%    |
| Dell Precision         | 1         | 2.5%    |
| ASUS P6T               | 1         | 2.5%    |
| ASUS P5G41T-M          | 1         | 2.5%    |
| ASUS N61Jv             | 1         | 2.5%    |
| ASUS 901               | 1         | 2.5%    |
| ASRock A320M-DGS       | 1         | 2.5%    |
| Apple MacBookPro14     | 1         | 2.5%    |
| Acer AOA110            | 1         | 2.5%    |
| Unknown                | 1         | 2.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 6         | 15%     |
| 2020 | 6         | 15%     |
| 2017 | 4         | 10%     |
| 2010 | 4         | 10%     |
| 2013 | 3         | 7.5%    |
| 2012 | 3         | 7.5%    |
| 2008 | 3         | 7.5%    |
| 2007 | 3         | 7.5%    |
| 2019 | 2         | 5%      |
| 2015 | 2         | 5%      |
| 2009 | 2         | 5%      |
| 2016 | 1         | 2.5%    |
| 2011 | 1         | 2.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 23        | 57.5%   |
| Desktop     | 13        | 32.5%   |
| Convertible | 3         | 7.5%    |
| Tablet      | 1         | 2.5%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 36        | 90%     |
| Enabled  | 4         | 10%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 40        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 9         | 22.5%   |
| 4.01-8.0   | 8         | 20%     |
| 8.01-16.0  | 7         | 17.5%   |
| 1.01-2.0   | 5         | 12.5%   |
| 32.01-64.0 | 4         | 10%     |
| 16.01-24.0 | 4         | 10%     |
| 2.01-3.0   | 3         | 7.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 15        | 37.5%   |
| 2.01-3.0 | 11        | 27.5%   |
| 3.01-4.0 | 7         | 17.5%   |
| 0.51-1.0 | 5         | 12.5%   |
| 4.01-8.0 | 2         | 5%      |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 25        | 62.5%   |
| 2      | 8         | 20%     |
| 4      | 3         | 7.5%    |
| 3      | 3         | 7.5%    |
| 6      | 1         | 2.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 29        | 72.5%   |
| Yes       | 11        | 27.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 82.5%   |
| No        | 7         | 17.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 77.5%   |
| No        | 9         | 22.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 22        | 55%     |
| Yes       | 18        | 45%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country   | Computers | Percent |
|-----------|-----------|---------|
| USA       | 13        | 32.5%   |
| UK        | 3         | 7.5%    |
| Russia    | 3         | 7.5%    |
| Germany   | 3         | 7.5%    |
| France    | 3         | 7.5%    |
| Spain     | 2         | 5%      |
| Venezuela | 1         | 2.5%    |
| Sweden    | 1         | 2.5%    |
| Romania   | 1         | 2.5%    |
| Poland    | 1         | 2.5%    |
| Peru      | 1         | 2.5%    |
| Mexico    | 1         | 2.5%    |
| Latvia    | 1         | 2.5%    |
| Kenya     | 1         | 2.5%    |
| Italy     | 1         | 2.5%    |
| Ecuador   | 1         | 2.5%    |
| Canada    | 1         | 2.5%    |
| Brazil    | 1         | 2.5%    |
| Belgium   | 1         | 2.5%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Vincennes                | 1         | 2.5%    |
| Veurne                   | 1         | 2.5%    |
| Vaslui                   | 1         | 2.5%    |
| Toledo                   | 1         | 2.5%    |
| Stockbridge              | 1         | 2.5%    |
| Spearfish                | 1         | 2.5%    |
| Scarborough              | 1         | 2.5%    |
| San Antonio de Los Altos | 1         | 2.5%    |
| Rochester                | 1         | 2.5%    |
| Riga                     | 1         | 2.5%    |
| Rhyl                     | 1         | 2.5%    |
| Rho                      | 1         | 2.5%    |
| Queens                   | 1         | 2.5%    |
| Peterborough             | 1         | 2.5%    |
| Nottingham               | 1         | 2.5%    |
| National City            | 1         | 2.5%    |
| Nairobi                  | 1         | 2.5%    |
| Murphy                   | 1         | 2.5%    |
| Moscow                   | 1         | 2.5%    |
| Mieuxce                  | 1         | 2.5%    |
| Menomonee Falls          | 1         | 2.5%    |
| Marrero                  | 1         | 2.5%    |
| Mannheim                 | 1         | 2.5%    |
| Madrid                   | 1         | 2.5%    |
| Limoges                  | 1         | 2.5%    |
| Lima                     | 1         | 2.5%    |
| Lebanon                  | 1         | 2.5%    |
| Lawrenceville            | 1         | 2.5%    |
| Knurow                   | 1         | 2.5%    |
| Hollister                | 1         | 2.5%    |
| Hamburg                  | 1         | 2.5%    |
| Guayaquil                | 1         | 2.5%    |
| Eppingen                 | 1         | 2.5%    |
| Darlington               | 1         | 2.5%    |
| Ciudad Juárez           | 1         | 2.5%    |
| Chelyabinsk              | 1         | 2.5%    |
| Castejon                 | 1         | 2.5%    |
| Belém                   | 1         | 2.5%    |
| Arkhangelsk              | 1         | 2.5%    |
| AElvdalen                | 1         | 2.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 10        | 16     | 17.54%  |
| Samsung Electronics            | 8         | 8      | 14.04%  |
| Seagate                        | 7         | 8      | 12.28%  |
| Kingston                       | 4         | 4      | 7.02%   |
| Hitachi                        | 4         | 5      | 7.02%   |
| Unknown                        | 3         | 3      | 5.26%   |
| SanDisk                        | 3         | 3      | 5.26%   |
| Transcend                      | 2         | 3      | 3.51%   |
| Toshiba                        | 2         | 2      | 3.51%   |
| Intel                          | 2         | 2      | 3.51%   |
| HGST                           | 2         | 2      | 3.51%   |
| Solid State Storage Technology | 1         | 1      | 1.75%   |
| OCZ-VERTEX                     | 1         | 1      | 1.75%   |
| Micron/Crucial Technology      | 1         | 1      | 1.75%   |
| Micron Technology              | 1         | 1      | 1.75%   |
| LITEON                         | 1         | 1      | 1.75%   |
| KingSpec                       | 1         | 1      | 1.75%   |
| China                          | 1         | 1      | 1.75%   |
| ASUS-PHISON                    | 1         | 1      | 1.75%   |
| Apple                          | 1         | 2      | 1.75%   |
| Acer                           | 1         | 1      | 1.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Samsung SSD 970 EVO Plus 1TB             | 3         | 4.84%   |
| WDC WDBNCE5000PNC 500GB SSD              | 1         | 1.61%   |
| WDC WD5000BPVX-00JC3T0 500GB             | 1         | 1.61%   |
| WDC WD5000AAKX-75U6AA0 500GB             | 1         | 1.61%   |
| WDC WD3200BPVT-35ZEST0 320GB             | 1         | 1.61%   |
| WDC WD3200AAJS-22B4A0 320GB              | 1         | 1.61%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 1         | 1.61%   |
| WDC WD1600BEVT-22ZCT0 160GB              | 1         | 1.61%   |
| WDC WD10EFRX-68JCSN0 1TB                 | 1         | 1.61%   |
| WDC WD10EFRX-68FYTN0 1TB                 | 1         | 1.61%   |
| WDC WD10EAVS-00D7B0 1TB                  | 1         | 1.61%   |
| WDC WD1003FZEX-00MK2A0 1TB               | 1         | 1.61%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB     | 1         | 1.61%   |
| WDC PC SN530 NVMe 256GB                  | 1         | 1.61%   |
| Unknown MMC Card  7GB                    | 1         | 1.61%   |
| Unknown MMC Card  4GB                    | 1         | 1.61%   |
| Unknown Biwin  64GB                      | 1         | 1.61%   |
| Transcend TS480GSSD220S 480GB            | 1         | 1.61%   |
| Transcend TS240GSSD220S 240GB            | 1         | 1.61%   |
| Transcend TS128GMTS430S 128GB SSD        | 1         | 1.61%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1.61%   |
| Toshiba DT01ACA050 500GB                 | 1         | 1.61%   |
| Solid State Storage NVMe SSD Drive 256GB | 1         | 1.61%   |
| Seagate STT_FPM28GLSE 128GB              | 1         | 1.61%   |
| Seagate ST500LT012-1DG142 500GB          | 1         | 1.61%   |
| Seagate ST3500312CS 500GB                | 1         | 1.61%   |
| Seagate ST3250318AS 250GB                | 1         | 1.61%   |
| Seagate ST320LM001 HN-M320MBB 320GB      | 1         | 1.61%   |
| Seagate ST2000DM008-2FR102 2TB           | 1         | 1.61%   |
| Seagate ST1000DM003-1SB102 1TB           | 1         | 1.61%   |
| SanDisk SSD PLUS 480GB                   | 1         | 1.61%   |
| SanDisk SD7UB3Q256G1001 256GB SSD        | 1         | 1.61%   |
| Sandisk NVMe SSD Drive 512GB             | 1         | 1.61%   |
| Samsung SSD 980 1TB                      | 1         | 1.61%   |
| Samsung SSD 850 EVO 250GB                | 1         | 1.61%   |
| Samsung NVMe SSD Drive 256GB             | 1         | 1.61%   |
| Samsung MZALQ512HBLU-00BL2 512GB         | 1         | 1.61%   |
| Samsung HD161HJ 160GB                    | 1         | 1.61%   |
| OCZ-VERTEX PLUS R2 128GB SSD             | 1         | 1.61%   |
| Micron/Crucial NVMe SSD Drive 2TB        | 1         | 1.61%   |
| Micron NVMe SSD Drive 512GB              | 1         | 1.61%   |
| LITEON CV3-CE256-11 SATA 256GB SSD       | 1         | 1.61%   |
| Kingston SV300S37A60G 64GB SSD           | 1         | 1.61%   |
| Kingston SA400S37240G 240GB SSD          | 1         | 1.61%   |
| Kingston SA400S37120G 120GB SSD          | 1         | 1.61%   |
| Kingston SA400M8240G 240GB SSD           | 1         | 1.61%   |
| KingSpec MT-128 128GB                    | 1         | 1.61%   |
| Intel SSDSCKKF256G8 SATA 256GB           | 1         | 1.61%   |
| Intel NVMe SSD Drive 256GB               | 1         | 1.61%   |
| Hitachi HTS541680J9SA00 80GB             | 1         | 1.61%   |
| Hitachi HDT725025VLA380 250GB            | 1         | 1.61%   |
| Hitachi HDS5C1032CLA382 320GB            | 1         | 1.61%   |
| Hitachi HDP725050GLA360 500GB            | 1         | 1.61%   |
| HGST HTS725050A7E630 500GB               | 1         | 1.61%   |
| HGST HTS545050A7E380 500GB               | 1         | 1.61%   |
| China SATA SSD 256GB                     | 1         | 1.61%   |
| ASUS-PHISON SSD 4GB                      | 1         | 1.61%   |
| Apple NVMe SSD Drive 8KB                 | 1         | 1.61%   |
| Apple NVMe SSD Drive 121GB               | 1         | 1.61%   |
| Acer SSD SA100 480GB                     | 1         | 1.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 13     | 31.82%  |
| Seagate             | 6         | 7      | 27.27%  |
| Hitachi             | 4         | 5      | 18.18%  |
| Toshiba             | 2         | 2      | 9.09%   |
| HGST                | 2         | 2      | 9.09%   |
| Samsung Electronics | 1         | 1      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 4         | 4      | 23.53%  |
| Transcend           | 2         | 3      | 11.76%  |
| SanDisk             | 2         | 2      | 11.76%  |
| WDC                 | 1         | 1      | 5.88%   |
| Samsung Electronics | 1         | 1      | 5.88%   |
| OCZ-VERTEX          | 1         | 1      | 5.88%   |
| LITEON              | 1         | 1      | 5.88%   |
| KingSpec            | 1         | 1      | 5.88%   |
| Intel               | 1         | 1      | 5.88%   |
| China               | 1         | 1      | 5.88%   |
| ASUS-PHISON         | 1         | 1      | 5.88%   |
| Acer                | 1         | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 19        | 30     | 37.25%  |
| SSD     | 15        | 18     | 29.41%  |
| NVMe    | 13        | 15     | 25.49%  |
| MMC     | 3         | 3      | 5.88%   |
| Unknown | 1         | 1      | 1.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 30        | 49     | 65.22%  |
| NVMe | 13        | 15     | 28.26%  |
| MMC  | 3         | 3      | 6.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 36     | 81.25%  |
| 0.51-1.0   | 4         | 9      | 12.5%   |
| 2.01-3.0   | 1         | 2      | 3.13%   |
| 1.01-2.0   | 1         | 1      | 3.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 12        | 30%     |
| 251-500        | 10        | 25%     |
| 1-20           | 4         | 10%     |
| 501-1000       | 4         | 10%     |
| 51-100         | 4         | 10%     |
| More than 3000 | 2         | 5%      |
| 21-50          | 2         | 5%      |
| 1001-2000      | 2         | 5%      |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 24        | 60%     |
| 21-50     | 7         | 17.5%   |
| 101-250   | 5         | 12.5%   |
| 51-100    | 2         | 5%      |
| 251-500   | 1         | 2.5%    |
| 1001-2000 | 1         | 2.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST3250318AS 250GB      | 1         | 1      | 50%     |
| Intel SSDSCKKF256G8 SATA 256GB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Intel   | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 50%     |
| HDD  | 1         | 1      | 50%     |

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
| Detected | 31        | 50     | 70.45%  |
| Works    | 11        | 15     | 25%     |
| Malfunc  | 2         | 2      | 4.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 30        | 57.69%  |
| AMD                            | 8         | 15.38%  |
| Samsung Electronics            | 6         | 11.54%  |
| Sandisk                        | 3         | 5.77%   |
| Solid State Storage Technology | 1         | 1.92%   |
| Micron/Crucial Technology      | 1         | 1.92%   |
| Micron Technology              | 1         | 1.92%   |
| JMicron Technology             | 1         | 1.92%   |
| Apple                          | 1         | 1.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 5         | 7.94%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 4         | 6.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 4.76%   |
| Samsung NVMe SSD Controller 980                                                        | 3         | 4.76%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 3         | 4.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 3.17%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 3.17%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                      | 2         | 3.17%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 2         | 3.17%   |
| Solid State Storage Non-Volatile memory controller                                     | 1         | 1.59%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 1         | 1.59%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 1.59%   |
| Sandisk Non-Volatile memory controller                                                 | 1         | 1.59%   |
| Micron/Crucial NVMe Controller                                                         | 1         | 1.59%   |
| Micron Non-Volatile memory controller                                                  | 1         | 1.59%   |
| JMicron JMB363 SATA/IDE Controller                                                     | 1         | 1.59%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 1         | 1.59%   |
| Intel SSD 600P Series                                                                  | 1         | 1.59%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 1         | 1.59%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 1.59%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 1.59%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 1         | 1.59%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                             | 1         | 1.59%   |
| Intel C610/X99 series chipset IDE-r Controller                                         | 1         | 1.59%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                       | 1         | 1.59%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 1.59%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                     | 1         | 1.59%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                   | 1         | 1.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 1.59%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.59%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 1         | 1.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 1         | 1.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 1.59%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]           | 1         | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.59%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 1         | 1.59%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.59%   |
| Apple S3X NVMe Controller                                                              | 1         | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                       | 1         | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 1.59%   |
| AMD IXP SB4x0 Serial ATA Controller                                                    | 1         | 1.59%   |
| AMD IXP SB4x0 IDE Controller                                                           | 1         | 1.59%   |
| AMD FCH SATA Controller D                                                              | 1         | 1.59%   |
| AMD 400 Series Chipset SATA Controller                                                 | 1         | 1.59%   |
| AMD 300 Series Chipset SATA Controller                                                 | 1         | 1.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 29        | 51.79%  |
| NVMe | 13        | 23.21%  |
| IDE  | 9         | 16.07%  |
| RAID | 5         | 8.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 33        | 82.5%   |
| AMD    | 7         | 17.5%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 3         | 7.5%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 2         | 5%      |
| Intel Atom CPU N270 @ 1.60GHz                   | 2         | 5%      |
| Intel Atom CPU N2600 @ 1.60GHz                  | 2         | 5%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 5%      |
| Intel Xeon CPU X5675 @ 3.07GHz                  | 1         | 2.5%    |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz             | 1         | 2.5%    |
| Intel Pentium CPU G645 @ 2.90GHz                | 1         | 2.5%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 2.5%    |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1         | 2.5%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz              | 1         | 2.5%    |
| Intel Core i5-8400 CPU @ 2.80GHz                | 1         | 2.5%    |
| Intel Core i5-7360U CPU @ 2.30GHz               | 1         | 2.5%    |
| Intel Core i5-4300U CPU @ 1.90GHz               | 1         | 2.5%    |
| Intel Core i5-2557M CPU @ 1.70GHz               | 1         | 2.5%    |
| Intel Core i5-10300H CPU @ 2.50GHz              | 1         | 2.5%    |
| Intel Core i5-10210U CPU @ 1.60GHz              | 1         | 2.5%    |
| Intel Core i3 CPU M 330 @ 2.13GHz               | 1         | 2.5%    |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 2.5%    |
| Intel Core 2 Duo CPU E8235 @ 2.80GHz            | 1         | 2.5%    |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz            | 1         | 2.5%    |
| Intel Celeron N4020 CPU @ 1.10GHz               | 1         | 2.5%    |
| Intel Celeron M CPU 520 @ 1.60GHz               | 1         | 2.5%    |
| Intel Celeron M CPU 440 @ 1.86GHz               | 1         | 2.5%    |
| Intel Celeron CPU N2815 @ 1.86GHz               | 1         | 2.5%    |
| Intel 12th Gen Core i3-12100F                   | 1         | 2.5%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 1         | 2.5%    |
| AMD Ryzen 7 5700U with Radeon Graphics          | 1         | 2.5%    |
| AMD Ryzen 7 4800H with Radeon Graphics          | 1         | 2.5%    |
| AMD Ryzen 7 1700 Eight-Core Processor           | 1         | 2.5%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 1         | 2.5%    |
| AMD Phenom II X2 555 Processor                  | 1         | 2.5%    |
| AMD Athlon 220GE with Radeon Vega Graphics      | 1         | 2.5%    |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G | 1         | 2.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Other                   | 7         | 17.5%   |
| Intel Core i5           | 6         | 15%     |
| Intel Atom              | 4         | 10%     |
| Intel Core i7           | 3         | 7.5%    |
| Intel Core 2 Duo        | 3         | 7.5%    |
| AMD Ryzen 7             | 3         | 7.5%    |
| Intel Xeon              | 2         | 5%      |
| Intel Pentium Dual-Core | 2         | 5%      |
| Intel Celeron M         | 2         | 5%      |
| Intel Celeron           | 2         | 5%      |
| Intel Pentium           | 1         | 2.5%    |
| Intel Core i3           | 1         | 2.5%    |
| AMD Ryzen 5             | 1         | 2.5%    |
| AMD Phenom II X2        | 1         | 2.5%    |
| AMD Athlon              | 1         | 2.5%    |
| AMD A10                 | 1         | 2.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 18        | 45%     |
| 4      | 12        | 30%     |
| 1      | 4         | 10%     |
| 8      | 3         | 7.5%    |
| 6      | 3         | 7.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 40        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 28        | 70%     |
| 1      | 12        | 30%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 36        | 90%     |
| 32-bit         | 4         | 10%     |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 6         | 15%     |
| 0x6fd      | 2         | 5%      |
| 0x506e3    | 2         | 5%      |
| 0x30661    | 2         | 5%      |
| 0x206a7    | 2         | 5%      |
| 0x106c2    | 2         | 5%      |
| 0x1067a    | 2         | 5%      |
| 0xa0652    | 1         | 2.5%    |
| 0x906ea    | 1         | 2.5%    |
| 0x90675    | 1         | 2.5%    |
| 0x806ec    | 1         | 2.5%    |
| 0x806e9    | 1         | 2.5%    |
| 0x706a8    | 1         | 2.5%    |
| 0x6f6      | 1         | 2.5%    |
| 0x6ec      | 1         | 2.5%    |
| 0x406f1    | 1         | 2.5%    |
| 0x40651    | 1         | 2.5%    |
| 0x306c3    | 1         | 2.5%    |
| 0x30673    | 1         | 2.5%    |
| 0x206c2    | 1         | 2.5%    |
| 0x20652    | 1         | 2.5%    |
| 0x10676    | 1         | 2.5%    |
| 0x08608103 | 1         | 2.5%    |
| 0x08600103 | 1         | 2.5%    |
| 0x08108109 | 1         | 2.5%    |
| 0x0810100b | 1         | 2.5%    |
| 0x08001137 | 1         | 2.5%    |
| 0x0600611a | 1         | 2.5%    |
| Unknown    | 1         | 2.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| TigerLake     | 6         | 15%     |
| Bonnell       | 4         | 10%     |
| Penryn        | 3         | 7.5%    |
| KabyLake      | 3         | 7.5%    |
| Core          | 3         | 7.5%    |
| Zen           | 2         | 5%      |
| Westmere      | 2         | 5%      |
| Skylake       | 2         | 5%      |
| SandyBridge   | 2         | 5%      |
| Haswell       | 2         | 5%      |
| Unknown       | 2         | 5%      |
| Zen+          | 1         | 2.5%    |
| Zen 2         | 1         | 2.5%    |
| Silvermont    | 1         | 2.5%    |
| P6            | 1         | 2.5%    |
| K10           | 1         | 2.5%    |
| Goldmont plus | 1         | 2.5%    |
| Excavator     | 1         | 2.5%    |
| CometLake     | 1         | 2.5%    |
| Broadwell     | 1         | 2.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 25        | 56.82%  |
| Nvidia | 12        | 27.27%  |
| AMD    | 7         | 15.91%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 5         | 10.42%  |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 3         | 6.25%   |
| Nvidia GT218 [GeForce 210]                                                            | 2         | 4.17%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                            | 2         | 4.17%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                       | 2         | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 2         | 4.17%   |
| Nvidia GT216M [GeForce GT 325M]                                                       | 1         | 2.08%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 1         | 2.08%   |
| Nvidia GM204GL [Quadro M4000]                                                         | 1         | 2.08%   |
| Nvidia GM204 [GeForce GTX 970]                                                        | 1         | 2.08%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                 | 1         | 2.08%   |
| Nvidia GK208B [GeForce GT 730]                                                        | 1         | 2.08%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 1         | 2.08%   |
| Nvidia GK106GLM [Quadro K2100M]                                                       | 1         | 2.08%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                                     | 1         | 2.08%   |
| Nvidia G98M [Quadro NVS 160M]                                                         | 1         | 2.08%   |
| Intel Tiger Lake UHD Graphics                                                         | 1         | 2.08%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 1         | 2.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 2.08%   |
| Intel Iris Plus Graphics 640                                                          | 1         | 2.08%   |
| Intel HD Graphics 530                                                                 | 1         | 2.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 1         | 2.08%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 2.08%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 2.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 2.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 1         | 2.08%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 1         | 2.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 1         | 2.08%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                | 1         | 2.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 1         | 2.08%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 1         | 2.08%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 2.08%   |
| AMD RV710 [Radeon HD 4350/4550]                                                       | 1         | 2.08%   |
| AMD Renoir                                                                            | 1         | 2.08%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                              | 1         | 2.08%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 1         | 2.08%   |
| AMD Lucienne                                                                          | 1         | 2.08%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                        | 1         | 2.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 52.5%   |
| 1 x Nvidia     | 9         | 22.5%   |
| 1 x AMD        | 6         | 15%     |
| Intel + Nvidia | 3         | 7.5%    |
| 2 x AMD        | 1         | 2.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 38        | 95%     |
| Proprietary | 1         | 2.5%    |
| Unknown     | 1         | 2.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 55%     |
| 1.01-2.0   | 5         | 12.5%   |
| 0.01-0.5   | 5         | 12.5%   |
| 0.51-1.0   | 4         | 10%     |
| 3.01-4.0   | 3         | 7.5%    |
| 7.01-8.0   | 1         | 2.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 8         | 18.6%   |
| Samsung Electronics     | 4         | 9.3%    |
| Dell                    | 4         | 9.3%    |
| BOE                     | 4         | 9.3%    |
| PANDA                   | 2         | 4.65%   |
| LG Display              | 2         | 4.65%   |
| Chimei Innolux          | 2         | 4.65%   |
| Chi Mei Optoelectronics | 2         | 4.65%   |
| Acer                    | 2         | 4.65%   |
| Sharp                   | 1         | 2.33%   |
| Quanta Display          | 1         | 2.33%   |
| Planar                  | 1         | 2.33%   |
| Philips                 | 1         | 2.33%   |
| Panasonic               | 1         | 2.33%   |
| Medion                  | 1         | 2.33%   |
| LG Philips              | 1         | 2.33%   |
| Hewlett-Packard         | 1         | 2.33%   |
| HannStar                | 1         | 2.33%   |
| BenQ                    | 1         | 2.33%   |
| Apple                   | 1         | 2.33%   |
| AOC                     | 1         | 2.33%   |
| Ancor Communications    | 1         | 2.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 2         | 4.55%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 1         | 2.27%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 380x300mm 19.1-inch     | 1         | 2.27%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch       | 1         | 2.27%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch       | 1         | 2.27%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 2.27%   |
| Quanta Display LCD Monitor QDS004B 1280x800 331x207mm 15.4-inch          | 1         | 2.27%   |
| Planar PLL2210W PLN2210 1920x1080 476x268mm 21.5-inch                    | 1         | 2.27%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch                | 1         | 2.27%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 1         | 2.27%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                  | 1         | 2.27%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch              | 1         | 2.27%   |
| Medion MD20328 MED3942 1600x900 462x272mm 21.1-inch                      | 1         | 2.27%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch             | 1         | 2.27%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch             | 1         | 2.27%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch              | 1         | 2.27%   |
| HannStar HSD160PHW1 HSD0640 1366x768 353x199mm 16.0-inch                 | 1         | 2.27%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                         | 1         | 2.27%   |
| Dell S2721D DELA199 2560x1440 597x336mm 27.0-inch                        | 1         | 2.27%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                        | 1         | 2.27%   |
| Dell LCD Monitor P2217 1680x1050                                         | 1         | 2.27%   |
| Dell 2007WFP DELA019 1680x1050 434x270mm 20.1-inch                       | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 1         | 2.27%   |
| BOE LCD Monitor BOE099E 1920x1080 344x194mm 15.5-inch                    | 1         | 2.27%   |
| BOE LCD Monitor BOE08FA 1920x1080 294x165mm 13.3-inch                    | 1         | 2.27%   |
| BOE LCD Monitor BOE07C6 1366x768 309x173mm 13.9-inch                     | 1         | 2.27%   |
| BOE LCD Monitor BOE0713 1920x1080 344x193mm 15.5-inch                    | 1         | 2.27%   |
| BenQ T90X BNQ76AF 1280x1024 376x301mm 19.0-inch                          | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO26ED 1920x1080 344x194mm 15.5-inch           | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO223D 1920x1080 309x174mm 14.0-inch           | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO12EC 1366x768 344x193mm 15.5-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch             | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO1020 1024x600 195x113mm 8.9-inch             | 1         | 2.27%   |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                    | 1         | 2.27%   |
| AOC 2036 AOC2036 1600x900 443x249mm 20.0-inch                            | 1         | 2.27%   |
| Ancor Communications ASUS MX299 ACI2931 2560x1080 673x284mm 28.8-inch    | 1         | 2.27%   |
| Acer V203HV ACR01D3 1600x900 443x249mm 20.0-inch                         | 1         | 2.27%   |
| Acer P223WB ACR000E 1680x1050 473x296mm 22.0-inch                        | 1         | 2.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 14        | 34.15%  |
| 1366x768 (WXGA)    | 5         | 12.2%   |
| 1600x900 (HD+)     | 4         | 9.76%   |
| 1024x600           | 4         | 9.76%   |
| 1680x1050 (WSXGA+) | 3         | 7.32%   |
| 2560x1440 (QHD)    | 2         | 4.88%   |
| 1280x800 (WXGA)    | 2         | 4.88%   |
| 1280x1024 (SXGA)   | 2         | 4.88%   |
| 3840x2160 (4K)     | 1         | 2.44%   |
| 2880x1800          | 1         | 2.44%   |
| 2560x1080          | 1         | 2.44%   |
| 1920x1200 (WUXGA)  | 1         | 2.44%   |
| 1440x900 (WXGA+)   | 1         | 2.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 11        | 25%     |
| 13      | 5         | 11.36%  |
| 20      | 4         | 9.09%   |
| 14      | 4         | 9.09%   |
| 21      | 3         | 6.82%   |
| 27      | 2         | 4.55%   |
| 24      | 2         | 4.55%   |
| 19      | 2         | 4.55%   |
| 10      | 2         | 4.55%   |
| 8       | 2         | 4.55%   |
| 32      | 1         | 2.27%   |
| 28      | 1         | 2.27%   |
| 23      | 1         | 2.27%   |
| 22      | 1         | 2.27%   |
| 17      | 1         | 2.27%   |
| 16      | 1         | 2.27%   |
| Unknown | 1         | 2.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 41.46%  |
| 401-500     | 7         | 17.07%  |
| 201-300     | 5         | 12.2%   |
| 501-600     | 4         | 9.76%   |
| 351-400     | 3         | 7.32%   |
| 101-200     | 2         | 4.88%   |
| 701-800     | 1         | 2.44%   |
| 601-700     | 1         | 2.44%   |
| Unknown     | 1         | 2.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 29        | 72.5%   |
| 16/10   | 7         | 17.5%   |
| 5/4     | 2         | 5%      |
| 21/9    | 1         | 2.5%    |
| Unknown | 1         | 2.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 27.91%  |
| 81-90          | 6         | 13.95%  |
| 151-200        | 6         | 13.95%  |
| 201-250        | 4         | 9.3%    |
| 71-80          | 3         | 6.98%   |
| 251-300        | 3         | 6.98%   |
| 41-50          | 2         | 4.65%   |
| 1-40           | 2         | 4.65%   |
| 301-350        | 2         | 4.65%   |
| 351-500        | 1         | 2.33%   |
| 121-130        | 1         | 2.33%   |
| Unknown        | 1         | 2.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 16        | 37.21%  |
| 121-160       | 13        | 30.23%  |
| 101-120       | 9         | 20.93%  |
| More than 240 | 2         | 4.65%   |
| 161-240       | 2         | 4.65%   |
| Unknown       | 1         | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 35        | 87.5%   |
| 2     | 4         | 10%     |
| 3     | 1         | 2.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 21        | 36.84%  |
| Intel                 | 17        | 29.82%  |
| Qualcomm Atheros      | 8         | 14.04%  |
| Broadcom              | 5         | 8.77%   |
| Ralink Technology     | 2         | 3.51%   |
| Ralink                | 2         | 3.51%   |
| Microchip Technology  | 1         | 1.75%   |
| Mercucys              | 1         | 1.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 11        | 15.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 4         | 5.56%   |
| Intel Wi-Fi 6 AX201                                                                           | 4         | 5.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 2.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 2         | 2.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 2         | 2.78%   |
| Realtek 802.11ac NIC                                                                          | 2         | 2.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2         | 2.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2         | 2.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2         | 2.78%   |
| Intel Wireless 7260                                                                           | 2         | 2.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 2.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1         | 1.39%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1         | 1.39%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1         | 1.39%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1         | 1.39%   |
| Realtek RTL8187B Wireless Adapter                                                             | 1         | 1.39%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.39%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 1.39%   |
| Ralink RT2561/RT61 rev B 802.11g                                                              | 1         | 1.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1         | 1.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1         | 1.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 1         | 1.39%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                                | 1         | 1.39%   |
| Microchip LAN9500/LAN9500i                                                                    | 1         | 1.39%   |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1         | 1.39%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 1.39%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 1.39%   |
| Intel Ultimate N WiFi Link 5300                                                               | 1         | 1.39%   |
| Intel I210 Gigabit Fiber Network Connection                                                   | 1         | 1.39%   |
| Intel Ethernet Connection I218-LM                                                             | 1         | 1.39%   |
| Intel Ethernet Connection I217-LM                                                             | 1         | 1.39%   |
| Intel Ethernet Connection (7) I219-V                                                          | 1         | 1.39%   |
| Intel Ethernet Connection (5) I219-LM                                                         | 1         | 1.39%   |
| Intel Ethernet Connection (2) I218-LM                                                         | 1         | 1.39%   |
| Intel Ethernet Connection (17) I219-V                                                         | 1         | 1.39%   |
| Intel Ethernet Connection (11) I219-V                                                         | 1         | 1.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 1         | 1.39%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1         | 1.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 1         | 1.39%   |
| Intel 82567V-2 Gigabit Network Connection                                                     | 1         | 1.39%   |
| Intel 82567LM Gigabit Network Connection                                                      | 1         | 1.39%   |
| Intel 82566DC-2 Gigabit Network Connection                                                    | 1         | 1.39%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                                            | 1         | 1.39%   |
| Broadcom BCM4321 802.11a/b/g/n                                                                | 1         | 1.39%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 1         | 1.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 11        | 33.33%  |
| Realtek Semiconductor | 7         | 21.21%  |
| Qualcomm Atheros      | 5         | 15.15%  |
| Broadcom              | 5         | 15.15%  |
| Ralink Technology     | 2         | 6.06%   |
| Ralink                | 2         | 6.06%   |
| Mercucys              | 1         | 3.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                                           | 4         | 11.11%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 5.56%   |
| Realtek 802.11ac NIC                                                                          | 2         | 5.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2         | 5.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2         | 5.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2         | 5.56%   |
| Intel Wireless 7260                                                                           | 2         | 5.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 5.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1         | 2.78%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1         | 2.78%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1         | 2.78%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1         | 2.78%   |
| Realtek RTL8187B Wireless Adapter                                                             | 1         | 2.78%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 2.78%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 2.78%   |
| Ralink RT2561/RT61 rev B 802.11g                                                              | 1         | 2.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 2.78%   |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1         | 2.78%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 2.78%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 2.78%   |
| Intel Ultimate N WiFi Link 5300                                                               | 1         | 2.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 1         | 2.78%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1         | 2.78%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                                            | 1         | 2.78%   |
| Broadcom BCM4321 802.11a/b/g/n                                                                | 1         | 2.78%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 1         | 2.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 19        | 54.29%  |
| Intel                 | 11        | 31.43%  |
| Qualcomm Atheros      | 4         | 11.43%  |
| Microchip Technology  | 1         | 2.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 30.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 11.11%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 5.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 5.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.78%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.78%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 2.78%   |
| Microchip LAN9500/LAN9500i                                        | 1         | 2.78%   |
| Intel I210 Gigabit Fiber Network Connection                       | 1         | 2.78%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.78%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.78%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 2.78%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 2.78%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 2.78%   |
| Intel Ethernet Connection (17) I219-V                             | 1         | 2.78%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 2.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.78%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1         | 2.78%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.78%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1         | 2.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 33        | 51.56%  |
| WiFi     | 31        | 48.44%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 24        | 55.81%  |
| Ethernet | 19        | 44.19%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 20        | 50%     |
| 1     | 19        | 47.5%   |
| 0     | 1         | 2.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 26        | 65%     |
| Yes  | 14        | 35%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 50%     |
| Realtek Semiconductor           | 3         | 16.67%  |
| Dell                            | 2         | 11.11%  |
| Qualcomm Atheros Communications | 1         | 5.56%   |
| Lite-On Technology              | 1         | 5.56%   |
| Foxconn / Hon Hai               | 1         | 5.56%   |
| ASUSTek Computer                | 1         | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                         | 5         | 27.78%  |
| Realtek Bluetooth Radio                        | 3         | 16.67%  |
| Intel Bluetooth wireless interface             | 2         | 11.11%  |
| Qualcomm Atheros  Bluetooth Device             | 1         | 5.56%   |
| Lite-On Bluetooth Device                       | 1         | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 5.56%   |
| Intel AX200 Bluetooth                          | 1         | 5.56%   |
| Foxconn / Hon Hai Acer Module                  | 1         | 5.56%   |
| Dell Wireless 370 Bluetooth Mini-card          | 1         | 5.56%   |
| Dell BT Mini-Receiver                          | 1         | 5.56%   |
| ASUS Broadcom Bluetooth 2.1                    | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 32        | 58.18%  |
| Nvidia                | 11        | 20%     |
| AMD                   | 8         | 14.55%  |
| Texas Instruments     | 1         | 1.82%   |
| Tenx Technology       | 1         | 1.82%   |
| Realtek Semiconductor | 1         | 1.82%   |
| GN Netcom             | 1         | 1.82%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 9.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 9.52%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 6.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 4.76%   |
| Nvidia High Definition Audio Controller                                    | 2         | 3.17%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 3.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 3.17%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 3.17%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 3.17%   |
| Texas Instruments PCM2702 16-bit stereo audio DAC                          | 1         | 1.59%   |
| Tenx Technology USB AUDIO                                                  | 1         | 1.59%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.59%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.59%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 1.59%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.59%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 1.59%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1         | 1.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.59%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.59%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.59%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.59%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.59%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.59%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.59%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 1.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.59%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1         | 1.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.59%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.59%   |
| GN Netcom Jabra EVOLVE 20 MS                                               | 1         | 1.59%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.59%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 1.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.59%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.59%   |
| AMD IXP SB4x0 High Definition Audio Controller                             | 1         | 1.59%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 1.59%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.59%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 1.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 3         | 25%     |
| SK Hynix            | 2         | 16.67%  |
| Kingston            | 2         | 16.67%  |
| Unknown (ABCD)      | 1         | 8.33%   |
| Unknown             | 1         | 8.33%   |
| Nanya Technology    | 1         | 8.33%   |
| G.Skill             | 1         | 8.33%   |
| A-DATA Technology   | 1         | 8.33%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 7.69%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 1         | 7.69%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 7.69%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 7.69%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 7.69%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 7.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 7.69%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s             | 1         | 7.69%   |
| Nanya RAM NT1GT64U8HB0BY-3C 1024MB DIMM DDR2 667MT/s             | 1         | 7.69%   |
| Kingston RAM KMKYF9-MIB 8192MB SODIMM DDR4 2400MT/s              | 1         | 7.69%   |
| Kingston RAM 9965589-033.D00G 8192MB DIMM DDR4 2400MT/s          | 1         | 7.69%   |
| G.Skill RAM F4-3000C16-16GVRB 16GB DIMM DDR4 3200MT/s            | 1         | 7.69%   |
| A-DATA RAM Module 8GB SODIMM DDR4 1200MT/s                       | 1         | 7.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 9         | 75%     |
| SDRAM   | 1         | 8.33%   |
| LPDDR4  | 1         | 8.33%   |
| Unknown | 1         | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 6         | 50%     |
| DIMM         | 5         | 41.67%  |
| Row Of Chips | 1         | 8.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 7         | 53.85%  |
| 16384 | 2         | 15.38%  |
| 4096  | 2         | 15.38%  |
| 2048  | 1         | 7.69%   |
| 1024  | 1         | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 5         | 41.67%  |
| 2400  | 3         | 25%     |
| 2667  | 1         | 8.33%   |
| 1333  | 1         | 8.33%   |
| 1200  | 1         | 8.33%   |
| 667   | 1         | 8.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)

![Printer Vendor](./All/images/line_chart/printer_vendor.svg)

| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Konica Minolta     | 1         | 33.33%  |
| Hewlett-Packard    | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)

![Printer Model](./All/images/line_chart/printer_model.svg)

| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| Konica Minolta 185    | 1         | 33.33%  |
| HP OfficeJet Pro 8730 | 1         | 33.33%  |
| Brother MFC-L2685DW   | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)

![Scanner Vendor](./All/images/line_chart/scanner_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)

![Scanner Model](./All/images/line_chart/scanner_model.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)

![Camera Vendor](./All/images/line_chart/camera_vendor.svg)

| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Microdia                               | 5         | 17.86%  |
| Chicony Electronics                    | 4         | 14.29%  |
| Suyin                                  | 3         | 10.71%  |
| Logitech                               | 3         | 10.71%  |
| Luxvisions Innotech Limited            | 2         | 7.14%   |
| Acer                                   | 2         | 7.14%   |
| Unknown                                | 1         | 3.57%   |
| Syntek                                 | 1         | 3.57%   |
| Sunplus Innovation Technology          | 1         | 3.57%   |
| Realtek Semiconductor                  | 1         | 3.57%   |
| OmniVision Technologies                | 1         | 3.57%   |
| MacroSilicon                           | 1         | 3.57%   |
| IMC Networks                           | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.57%   |
| ARC International                      | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                        | 5         | 17.86%  |
| Chicony HD WebCam                                    | 2         | 7.14%   |
| Acer Integrated Camera                               | 2         | 7.14%   |
| Unknown 720p HD Camera                               | 1         | 3.57%   |
| Syntek Integrated Camera                             | 1         | 3.57%   |
| Suyin WebCam                                         | 1         | 3.57%   |
| Suyin Acer CrystalEye Webcam                         | 1         | 3.57%   |
| Suyin 1.3M HD WebCam                                 | 1         | 3.57%   |
| Sunplus Aukey-PC-LM1E Camera                         | 1         | 3.57%   |
| Realtek Integrated Camera 2M                         | 1         | 3.57%   |
| OmniVision Integrated Webcam for Dell XPS 2010       | 1         | 3.57%   |
| MacroSilicon USB Video                               | 1         | 3.57%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 3.57%   |
| Luxvisions Innotech Limited HP HD Camera             | 1         | 3.57%   |
| Logitech Webcam C925e                                | 1         | 3.57%   |
| Logitech Webcam C270                                 | 1         | 3.57%   |
| Logitech Webcam C210                                 | 1         | 3.57%   |
| IMC Networks 2M Integrated Webcam                    | 1         | 3.57%   |
| Chicony HP Truevision HD camera                      | 1         | 3.57%   |
| Chicony 2.0M UVC Webcam / CNF7129                    | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam  | 1         | 3.57%   |
| ARC International Camera                             | 1         | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Validity Sensors    | 1         | 33.33%  |
| Synaptics           | 1         | 33.33%  |
| Samsung Electronics | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 33.33%  |
| Samsung Fingerprint Sensor Device - 730B   | 1         | 33.33%  |
| Unknown                                    | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./All/images/line_chart/chipcard_vendor.svg)

| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |
| Broadcom 5880                                  | 1         | 33.33%  |
| Broadcom 58200                                 | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 23        | 57.5%   |
| 1     | 16        | 40%     |
| 2     | 1         | 2.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 6         | 31.58%  |
| Multimedia controller | 4         | 21.05%  |
| Fingerprint reader    | 3         | 15.79%  |
| Chipcard              | 3         | 15.79%  |
| Unassigned class      | 1         | 5.26%   |
| Graphics card         | 1         | 5.26%   |
| Camera                | 1         | 5.26%   |

