LMDE - Hardware Trends
----------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/LMDE/Desktop/README.md) and [notebooks](/Dist/LMDE/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/linuxhw/TestCoverage)

Period: Jan, 2023.

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

| Name   | Computers | Percent |
|--------|-----------|---------|
| LMDE 5 | 36        | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| LMDE | 36        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version         | Computers | Percent |
|-----------------|-----------|---------|
| 5.10.0-20-amd64 | 20        | 55.56%  |
| 5.10.0-21-amd64 | 11        | 30.56%  |
| 5.10.0-20-686   | 1         | 2.78%   |
| 5.10.0-18-amd64 | 1         | 2.78%   |
| 5.10.0-17-amd64 | 1         | 2.78%   |
| 5.10.0-12-686   | 1         | 2.78%   |
| 4.19.0-23-amd64 | 1         | 2.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 35        | 97.22%  |
| 4.19.0  | 1         | 2.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 35        | 97.22%  |
| 4.19    | 1         | 2.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 34        | 94.44%  |
| i686   | 2         | 5.56%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 32        | 88.89%  |
| Cinnamon   | 2         | 5.56%   |
| MATE       | 1         | 2.78%   |
| awesome    | 1         | 2.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 36        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 23        | 63.89%  |
| LightDM | 13        | 36.11%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| de_DE | 8         | 22.22%  |
| en_US | 7         | 19.44%  |
| pt_BR | 5         | 13.89%  |
| ru_RU | 4         | 11.11%  |
| pl_PL | 2         | 5.56%   |
| it_IT | 2         | 5.56%   |
| fr_FR | 2         | 5.56%   |
| es_ES | 2         | 5.56%   |
| en_ZA | 1         | 2.78%   |
| en_NZ | 1         | 2.78%   |
| en_GB | 1         | 2.78%   |
| el_GR | 1         | 2.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 21        | 58.33%  |
| EFI  | 15        | 41.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 35        | 97.22%  |
| Btrfs | 1         | 2.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 23        | 63.89%  |
| MBR     | 7         | 19.44%  |
| GPT     | 6         | 16.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 86.11%  |
| Yes       | 5         | 13.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 29        | 80.56%  |
| Yes       | 7         | 19.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 6         | 16.67%  |
| ASUSTek Computer    | 5         | 13.89%  |
| Toshiba             | 3         | 8.33%   |
| Gigabyte Technology | 3         | 8.33%   |
| Fujitsu             | 3         | 8.33%   |
| Dell                | 3         | 8.33%   |
| Intel               | 2         | 5.56%   |
| Acer                | 2         | 5.56%   |
| Samsung Electronics | 1         | 2.78%   |
| MSI                 | 1         | 2.78%   |
| Kruger&Matz         | 1         | 2.78%   |
| Hewlett-Packard     | 1         | 2.78%   |
| Google              | 1         | 2.78%   |
| Dynabook            | 1         | 2.78%   |
| Compaq              | 1         | 2.78%   |
| ASRock              | 1         | 2.78%   |
| ADVANSUS            | 1         | 2.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Toshiba Satellite L305                | 1         | 2.78%   |
| Toshiba PORTEGE Z30-B                 | 1         | 2.78%   |
| Toshiba PORTEGE M780                  | 1         | 2.78%   |
| Samsung RV415/RV515                   | 1         | 2.78%   |
| MSI MS-7721                           | 1         | 2.78%   |
| Lenovo ThinkPad X270 W10DG 20K5S3HG00 | 1         | 2.78%   |
| Lenovo ThinkPad W541 20EGS24J00       | 1         | 2.78%   |
| Lenovo IdeaPad 320-15AST 80XV         | 1         | 2.78%   |
| Lenovo IdeaPad 3 15ITL6 82H8          | 1         | 2.78%   |
| Lenovo B560                           | 1         | 2.78%   |
| Lenovo B50-70 20384                   | 1         | 2.78%   |
| Kruger&Matz KM1406                    | 1         | 2.78%   |
| Intel H61M-DS2V                       | 1         | 2.78%   |
| Intel B75                             | 1         | 2.78%   |
| HP Laptop 15s-eq3xxx                  | 1         | 2.78%   |
| Google Candy                          | 1         | 2.78%   |
| Gigabyte X570 AORUS ULTRA             | 1         | 2.78%   |
| Gigabyte X470 AORUS ULTRA GAMING      | 1         | 2.78%   |
| Gigabyte B560 DS3H AC-Y1              | 1         | 2.78%   |
| Fujitsu M2010                         | 1         | 2.78%   |
| Fujitsu LIFEBOOK S751                 | 1         | 2.78%   |
| Fujitsu LIFEBOOK E736                 | 1         | 2.78%   |
| Dynabook Satellite Pro C50-G          | 1         | 2.78%   |
| Dell Vostro 1700                      | 1         | 2.78%   |
| Dell Precision 5520                   | 1         | 2.78%   |
| Dell OptiPlex 780                     | 1         | 2.78%   |
| Compaq 420                            | 1         | 2.78%   |
| ASUS ROG STRIX Z490-H GAMING          | 1         | 2.78%   |
| ASUS ROG CROSSHAIR VIII HERO          | 1         | 2.78%   |
| ASUS P7P55D                           | 1         | 2.78%   |
| ASUS M5A78L-M PLUS/USB3               | 1         | 2.78%   |
| ASUS K54L                             | 1         | 2.78%   |
| ASRock Z87 Pro3                       | 1         | 2.78%   |
| ADVANSUS 945G                         | 1         | 2.78%   |
| Acer Aspire XC-780                    | 1         | 2.78%   |
| Acer Aspire 3810T                     | 1         | 2.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Toshiba PORTEGE    | 2         | 5.56%   |
| Lenovo ThinkPad    | 2         | 5.56%   |
| Lenovo IdeaPad     | 2         | 5.56%   |
| Fujitsu LIFEBOOK   | 2         | 5.56%   |
| ASUS ROG           | 2         | 5.56%   |
| Acer Aspire        | 2         | 5.56%   |
| Toshiba Satellite  | 1         | 2.78%   |
| Samsung RV415      | 1         | 2.78%   |
| MSI MS-7721        | 1         | 2.78%   |
| Lenovo B560        | 1         | 2.78%   |
| Lenovo B50-70      | 1         | 2.78%   |
| Kruger&Matz KM1406 | 1         | 2.78%   |
| Intel H61M-DS2V    | 1         | 2.78%   |
| Intel B75          | 1         | 2.78%   |
| HP Laptop          | 1         | 2.78%   |
| Google Candy       | 1         | 2.78%   |
| Gigabyte X570      | 1         | 2.78%   |
| Gigabyte X470      | 1         | 2.78%   |
| Gigabyte B560      | 1         | 2.78%   |
| Fujitsu M2010      | 1         | 2.78%   |
| Dynabook Satellite | 1         | 2.78%   |
| Dell Vostro        | 1         | 2.78%   |
| Dell Precision     | 1         | 2.78%   |
| Dell OptiPlex      | 1         | 2.78%   |
| Compaq 420         | 1         | 2.78%   |
| ASUS P7P55D        | 1         | 2.78%   |
| ASUS M5A78L-M      | 1         | 2.78%   |
| ASUS K54L          | 1         | 2.78%   |
| ASRock Z87         | 1         | 2.78%   |
| ADVANSUS 945G      | 1         | 2.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 5         | 13.89%  |
| 2011 | 4         | 11.11%  |
| 2009 | 4         | 11.11%  |
| 2022 | 3         | 8.33%   |
| 2017 | 3         | 8.33%   |
| 2016 | 3         | 8.33%   |
| 2010 | 3         | 8.33%   |
| 2018 | 2         | 5.56%   |
| 2015 | 2         | 5.56%   |
| 2014 | 2         | 5.56%   |
| 2020 | 1         | 2.78%   |
| 2019 | 1         | 2.78%   |
| 2013 | 1         | 2.78%   |
| 2008 | 1         | 2.78%   |
| 2007 | 1         | 2.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 22        | 61.11%  |
| Desktop  | 14        | 38.89%  |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 34        | 94.44%  |
| Enabled  | 2         | 5.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 35        | 97.22%  |
| Yes  | 1         | 2.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 11        | 30.56%  |
| 3.01-4.0   | 7         | 19.44%  |
| 4.01-8.0   | 6         | 16.67%  |
| 32.01-64.0 | 5         | 13.89%  |
| 16.01-24.0 | 5         | 13.89%  |
| 2.01-3.0   | 1         | 2.78%   |
| 1.01-2.0   | 1         | 2.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 20        | 55.56%  |
| 2.01-3.0  | 7         | 19.44%  |
| 0.51-1.0  | 4         | 11.11%  |
| 4.01-8.0  | 2         | 5.56%   |
| 3.01-4.0  | 2         | 5.56%   |
| 8.01-16.0 | 1         | 2.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 16        | 44.44%  |
| 2      | 12        | 33.33%  |
| 3      | 5         | 13.89%  |
| 5      | 2         | 5.56%   |
| 4      | 1         | 2.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 23        | 63.89%  |
| Yes       | 13        | 36.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 83.33%  |
| No        | 6         | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 83.33%  |
| No        | 6         | 16.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 24        | 66.67%  |
| Yes       | 12        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 8         | 22.22%  |
| USA          | 6         | 16.67%  |
| Brazil       | 5         | 13.89%  |
| Russia       | 3         | 8.33%   |
| Italy        | 3         | 8.33%   |
| Spain        | 2         | 5.56%   |
| Poland       | 2         | 5.56%   |
| South Africa | 1         | 2.78%   |
| Serbia       | 1         | 2.78%   |
| New Zealand  | 1         | 2.78%   |
| Netherlands  | 1         | 2.78%   |
| Kazakhstan   | 1         | 2.78%   |
| Greece       | 1         | 2.78%   |
| France       | 1         | 2.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City               | Computers | Percent |
|--------------------|-----------|---------|
| Volos              | 1         | 2.78%   |
| Varese             | 1         | 2.78%   |
| St Petersburg      | 1         | 2.78%   |
| Solingen           | 1         | 2.78%   |
| Sao Lourenço      | 1         | 2.78%   |
| San Jose           | 1         | 2.78%   |
| Salem              | 1         | 2.78%   |
| Ponteranica        | 1         | 2.78%   |
| Policoro           | 1         | 2.78%   |
| Pirot              | 1         | 2.78%   |
| Petrozavodsk       | 1         | 2.78%   |
| New York           | 1         | 2.78%   |
| Munich             | 1         | 2.78%   |
| Moscow             | 1         | 2.78%   |
| Mogi das Cruzes    | 1         | 2.78%   |
| Malente            | 1         | 2.78%   |
| Málaga            | 1         | 2.78%   |
| Madrid             | 1         | 2.78%   |
| Maceió            | 1         | 2.78%   |
| Lüneburg          | 1         | 2.78%   |
| Krakow             | 1         | 2.78%   |
| Hamburg            | 1         | 2.78%   |
| Halle              | 1         | 2.78%   |
| Gasny              | 1         | 2.78%   |
| Fortaleza          | 1         | 2.78%   |
| Dallas             | 1         | 2.78%   |
| Dąbrowa Górnicza | 1         | 2.78%   |
| Curitiba           | 1         | 2.78%   |
| Columbia City      | 1         | 2.78%   |
| Centurion          | 1         | 2.78%   |
| Brunssum           | 1         | 2.78%   |
| Berlin             | 1         | 2.78%   |
| Bad Kreuznach      | 1         | 2.78%   |
| Auckland           | 1         | 2.78%   |
| Astana             | 1         | 2.78%   |
| Arlington          | 1         | 2.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 15     | 15.25%  |
| Seagate             | 7         | 8      | 11.86%  |
| WDC                 | 6         | 7      | 10.17%  |
| Unknown             | 6         | 6      | 10.17%  |
| Toshiba             | 4         | 4      | 6.78%   |
| SanDisk             | 3         | 3      | 5.08%   |
| SK hynix            | 2         | 2      | 3.39%   |
| HGST                | 2         | 2      | 3.39%   |
| Crucial             | 2         | 2      | 3.39%   |
| A-DATA Technology   | 2         | 2      | 3.39%   |
| WALRAM              | 1         | 1      | 1.69%   |
| Transcend           | 1         | 1      | 1.69%   |
| TGT                 | 1         | 1      | 1.69%   |
| TakeMS              | 1         | 1      | 1.69%   |
| Phison              | 1         | 1      | 1.69%   |
| Micron Technology   | 1         | 1      | 1.69%   |
| MAXSUN              | 1         | 1      | 1.69%   |
| Kingston            | 1         | 2      | 1.69%   |
| Intel               | 1         | 1      | 1.69%   |
| G521N               | 1         | 1      | 1.69%   |
| Fujitsu             | 1         | 1      | 1.69%   |
| FORESEE             | 1         | 1      | 1.69%   |
| Emtec               | 1         | 1      | 1.69%   |
| China               | 1         | 1      | 1.69%   |
| ASMT                | 1         | 1      | 1.69%   |
| ADATA Technology    | 1         | 1      | 1.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST500LM012 HN-M500MBB 500GB                 | 2         | 3.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 2         | 3.03%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 1         | 1.52%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 1         | 1.52%   |
| WDC WD1600BEVS-26VAT0 160GB                         | 1         | 1.52%   |
| WDC WD10EZRX-00DC0B0 1TB                            | 1         | 1.52%   |
| WDC WD10EARS-00Y5B1 1TB                             | 1         | 1.52%   |
| WDC WD1002FAEX-00Z3A0 1TB                           | 1         | 1.52%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB                | 1         | 1.52%   |
| WALRAM 120G                                         | 1         | 1.52%   |
| Unknown SD32G  32GB                                 | 1         | 1.52%   |
| Unknown SD/MMC/MS PRO 2GB                           | 1         | 1.52%   |
| Unknown SC128  128GB                                | 1         | 1.52%   |
| Unknown MMC Card  952MB                             | 1         | 1.52%   |
| Unknown MMC Card  64GB                              | 1         | 1.52%   |
| Unknown HAG2e  16GB                                 | 1         | 1.52%   |
| Transcend TS128GMTS430S 128GB SSD                   | 1         | 1.52%   |
| Toshiba THNSNJ256GMCU 256GB SSD                     | 1         | 1.52%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1.52%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 1.52%   |
| Toshiba MK3265GSX 320GB                             | 1         | 1.52%   |
| TGT EGON T2 240GB                                   | 1         | 1.52%   |
| TakeMS SSD UTX-2200 120GB                           | 1         | 1.52%   |
| SK hynix PC401 NVMe Solid State Drive 256GB         | 1         | 1.52%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 1         | 1.52%   |
| Seagate ST9250315AS 250GB                           | 1         | 1.52%   |
| Seagate ST4000DM004-2CV104 4TB                      | 1         | 1.52%   |
| Seagate ST3250318AS 249GB                           | 1         | 1.52%   |
| Seagate ST31500341AS 1TB                            | 1         | 1.52%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1.52%   |
| SanDisk X600 2.5 7MM SATA 256GB SSD                 | 1         | 1.52%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 1         | 1.52%   |
| SanDisk SD7UB3Q256G1001 256GB SSD                   | 1         | 1.52%   |
| Samsung SSD 980 1TB                                 | 1         | 1.52%   |
| Samsung SSD 970 EVO 500GB                           | 1         | 1.52%   |
| Samsung SSD 870 EVO 1TB                             | 1         | 1.52%   |
| Samsung SSD 860 EVO 500GB                           | 1         | 1.52%   |
| Samsung SSD 860 EVO 250GB                           | 1         | 1.52%   |
| Samsung SSD 850 PRO 256GB                           | 1         | 1.52%   |
| Samsung SSD 850 EVO 500GB                           | 1         | 1.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 8      | 33.33%  |
| WDC                 | 5         | 6      | 23.81%  |
| Toshiba             | 3         | 3      | 14.29%  |
| Samsung Electronics | 2         | 2      | 9.52%   |
| HGST                | 2         | 2      | 9.52%   |
| Unknown             | 1         | 1      | 4.76%   |
| Fujitsu             | 1         | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 8      | 27.27%  |
| SanDisk             | 2         | 2      | 9.09%   |
| A-DATA Technology   | 2         | 2      | 9.09%   |
| Transcend           | 1         | 1      | 4.55%   |
| Toshiba             | 1         | 1      | 4.55%   |
| TakeMS              | 1         | 1      | 4.55%   |
| SK hynix            | 1         | 1      | 4.55%   |
| Micron Technology   | 1         | 1      | 4.55%   |
| Kingston            | 1         | 2      | 4.55%   |
| Intel               | 1         | 1      | 4.55%   |
| FORESEE             | 1         | 1      | 4.55%   |
| Emtec               | 1         | 1      | 4.55%   |
| Crucial             | 1         | 1      | 4.55%   |
| China               | 1         | 1      | 4.55%   |
| ASMT                | 1         | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 18        | 25     | 33.96%  |
| HDD     | 18        | 23     | 33.96%  |
| NVMe    | 8         | 11     | 15.09%  |
| MMC     | 5         | 5      | 9.43%   |
| Unknown | 4         | 4      | 7.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 30        | 48     | 63.83%  |
| NVMe | 8         | 11     | 17.02%  |
| MMC  | 5         | 5      | 10.64%  |
| SAS  | 4         | 4      | 8.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 23        | 34     | 67.65%  |
| 0.51-1.0   | 10        | 12     | 29.41%  |
| 3.01-4.0   | 1         | 2      | 2.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 14        | 38.89%  |
| 501-1000       | 8         | 22.22%  |
| 251-500        | 7         | 19.44%  |
| 21-50          | 2         | 5.56%   |
| 1001-2000      | 2         | 5.56%   |
| More than 3000 | 1         | 2.78%   |
| 2001-3000      | 1         | 2.78%   |
| 51-100         | 1         | 2.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 101-250   | 10        | 27.78%  |
| 21-50     | 9         | 25%     |
| 1-20      | 8         | 22.22%  |
| 51-100    | 4         | 11.11%  |
| 251-500   | 2         | 5.56%   |
| 501-1000  | 2         | 5.56%   |
| 2001-3000 | 1         | 2.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9250315AS 250GB           | 1         | 1      | 33.33%  |
| Samsung Electronics SSD 870 EVO 1TB | 1         | 1      | 33.33%  |
| Intel SSDSC2CT240A3 240GB           | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| Intel               | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 2      | 66.67%  |
| HDD  | 1         | 1      | 33.33%  |

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
| Detected | 29        | 48     | 67.44%  |
| Works    | 11        | 17     | 25.58%  |
| Malfunc  | 3         | 3      | 6.98%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 27        | 61.36%  |
| AMD                       | 7         | 15.91%  |
| Samsung Electronics       | 3         | 6.82%   |
| SanDisk                   | 2         | 4.55%   |
| SK hynix                  | 1         | 2.27%   |
| Phison Electronics        | 1         | 2.27%   |
| Micron/Crucial Technology | 1         | 2.27%   |
| JMicron Technology        | 1         | 2.27%   |
| ADATA Technology          | 1         | 2.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 7.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 5.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 3.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 3.92%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 3.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 3.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 3.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 3.92%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 1.96%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.96%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 1.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.96%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 1.96%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.96%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1         | 1.96%   |
| JMicron JMB363 SATA/IDE Controller                                               | 1         | 1.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.96%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.96%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 1.96%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 1.96%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 1.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.96%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 1.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.96%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1         | 1.96%   |
| Intel 500 Series Chipset Family SATA RAID Controller                             | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 1.96%   |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 1.96%   |
| ADATA ADATA XPG GAMMIXS1 1L Media                                                | 1         | 1.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 29        | 64.44%  |
| NVMe | 8         | 17.78%  |
| IDE  | 5         | 11.11%  |
| RAID | 3         | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 28        | 77.78%  |
| AMD    | 8         | 22.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor           | 2         | 5.56%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz       | 1         | 2.78%   |
| Intel Pentium CPU P6100 @ 2.00GHz            | 1         | 2.78%   |
| Intel Pentium CPU N3700 @ 1.60GHz            | 1         | 2.78%   |
| Intel Genuine CPU U7300 @ 1.30GHz            | 1         | 2.78%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz           | 1         | 2.78%   |
| Intel Core i7-6600U CPU @ 2.60GHz            | 1         | 2.78%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz           | 1         | 2.78%   |
| Intel Core i7-4770 CPU @ 3.40GHz             | 1         | 2.78%   |
| Intel Core i7-3770S CPU @ 3.10GHz            | 1         | 2.78%   |
| Intel Core i7-10700K CPU @ 3.80GHz           | 1         | 2.78%   |
| Intel Core i5-7400 CPU @ 3.00GHz             | 1         | 2.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 1         | 2.78%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 1         | 2.78%   |
| Intel Core i5-2450M CPU @ 2.50GHz            | 1         | 2.78%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 1         | 2.78%   |
| Intel Core i3-4010U CPU @ 1.70GHz            | 1         | 2.78%   |
| Intel Core i3-2330M CPU @ 2.20GHz            | 1         | 2.78%   |
| Intel Core i3-2100 CPU @ 3.10GHz             | 1         | 2.78%   |
| Intel Core i3 CPU M 370 @ 2.40GHz            | 1         | 2.78%   |
| Intel Core i3 CPU 560 @ 3.33GHz              | 1         | 2.78%   |
| Intel Core 2 Quad CPU Q6700 @ 2.66GHz        | 1         | 2.78%   |
| Intel Core 2 Duo CPU T5470 @ 1.60GHz         | 1         | 2.78%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz         | 1         | 2.78%   |
| Intel Celeron N4000 CPU @ 1.10GHz            | 1         | 2.78%   |
| Intel Celeron CPU N2840 @ 2.16GHz            | 1         | 2.78%   |
| Intel Atom CPU N280 @ 1.66GHz                | 1         | 2.78%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz      | 1         | 2.78%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz      | 1         | 2.78%   |
| AMD Ryzen 7 5800X 8-Core Processor           | 1         | 2.78%   |
| AMD Ryzen 5 5625U with Radeon Graphics       | 1         | 2.78%   |
| AMD Phenom II X4 965 Processor               | 1         | 2.78%   |
| AMD E-300 APU with Radeon HD Graphics        | 1         | 2.78%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 2.78%   |
| AMD A4-4000 APU with Radeon HD Graphics      | 1         | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 6         | 16.67%  |
| Intel Core i5      | 5         | 13.89%  |
| Intel Core i3      | 5         | 13.89%  |
| Other              | 3         | 8.33%   |
| AMD Ryzen 7        | 3         | 8.33%   |
| Intel Pentium      | 2         | 5.56%   |
| Intel Core 2 Duo   | 2         | 5.56%   |
| Intel Celeron      | 2         | 5.56%   |
| Intel Pentium Dual | 1         | 2.78%   |
| Intel Genuine      | 1         | 2.78%   |
| Intel Core 2 Quad  | 1         | 2.78%   |
| Intel Atom         | 1         | 2.78%   |
| AMD Ryzen 5        | 1         | 2.78%   |
| AMD Phenom II X4   | 1         | 2.78%   |
| AMD E              | 1         | 2.78%   |
| AMD A4             | 1         | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 19        | 52.78%  |
| 4      | 9         | 25%     |
| 8      | 5         | 13.89%  |
| 1      | 2         | 5.56%   |
| 6      | 1         | 2.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 36        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 23        | 63.89%  |
| 1      | 13        | 36.11%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 35        | 97.22%  |
| 32-bit         | 1         | 2.78%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 3         | 8.33%   |
| 0x20655    | 3         | 8.33%   |
| 0x906e9    | 2         | 5.56%   |
| 0x6fd      | 2         | 5.56%   |
| 0x406e3    | 2         | 5.56%   |
| 0x306c3    | 2         | 5.56%   |
| 0x1067a    | 2         | 5.56%   |
| 0xa0671    | 1         | 2.78%   |
| 0xa0655    | 1         | 2.78%   |
| 0x806ec    | 1         | 2.78%   |
| 0x806c1    | 1         | 2.78%   |
| 0x706a1    | 1         | 2.78%   |
| 0x6fb      | 1         | 2.78%   |
| 0x406c3    | 1         | 2.78%   |
| 0x40651    | 1         | 2.78%   |
| 0x306d4    | 1         | 2.78%   |
| 0x306a9    | 1         | 2.78%   |
| 0x30678    | 1         | 2.78%   |
| 0x106c2    | 1         | 2.78%   |
| 0x0a50000d | 1         | 2.78%   |
| 0x0a201016 | 1         | 2.78%   |
| 0x08701030 | 1         | 2.78%   |
| 0x08701021 | 1         | 2.78%   |
| 0x06006705 | 1         | 2.78%   |
| 0x06001119 | 1         | 2.78%   |
| 0x05000119 | 1         | 2.78%   |
| 0x010000c8 | 1         | 2.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| Westmere      | 3         | 8.33%   |
| SandyBridge   | 3         | 8.33%   |
| KabyLake      | 3         | 8.33%   |
| Haswell       | 3         | 8.33%   |
| Core          | 3         | 8.33%   |
| Zen 3         | 2         | 5.56%   |
| Zen 2         | 2         | 5.56%   |
| Skylake       | 2         | 5.56%   |
| Silvermont    | 2         | 5.56%   |
| Penryn        | 2         | 5.56%   |
| TigerLake     | 1         | 2.78%   |
| Piledriver    | 1         | 2.78%   |
| K10           | 1         | 2.78%   |
| IvyBridge     | 1         | 2.78%   |
| Goldmont plus | 1         | 2.78%   |
| Excavator     | 1         | 2.78%   |
| CometLake     | 1         | 2.78%   |
| Broadwell     | 1         | 2.78%   |
| Bonnell       | 1         | 2.78%   |
| Bobcat        | 1         | 2.78%   |
| Unknown       | 1         | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 20        | 51.28%  |
| Nvidia | 13        | 33.33%  |
| AMD    | 6         | 15.38%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 7.32%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 4.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 4.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 4.88%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 2.44%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 2.44%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                                     | 1         | 2.44%   |
| Nvidia GP107GL [Quadro P620]                                                             | 1         | 2.44%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 2.44%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 2.44%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 2.44%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1         | 2.44%   |
| Nvidia G92 [GeForce GTS 250]                                                             | 1         | 2.44%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 1         | 2.44%   |
| Nvidia G72 [GeForce 7200 GS / 7300 SE]                                                   | 1         | 2.44%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 2.44%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 2.44%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 2.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.44%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 2.44%   |
| Intel HD Graphics 630                                                                    | 1         | 2.44%   |
| Intel HD Graphics 5500                                                                   | 1         | 2.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.44%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 2.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 2.44%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1         | 2.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.44%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 2.44%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1         | 2.44%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 2.44%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 2.44%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                        | 1         | 2.44%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1         | 2.44%   |
| AMD Barcelo                                                                              | 1         | 2.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 47.22%  |
| 1 x Nvidia     | 11        | 30.56%  |
| 1 x AMD        | 5         | 13.89%  |
| Intel + Nvidia | 2         | 5.56%   |
| 2 x AMD        | 1         | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 27        | 75%     |
| Proprietary | 6         | 16.67%  |
| Unknown     | 3         | 8.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 61.11%  |
| 1.01-2.0   | 4         | 11.11%  |
| 0.01-0.5   | 4         | 11.11%  |
| 5.01-6.0   | 3         | 8.33%   |
| 7.01-8.0   | 1         | 2.78%   |
| 8.01-16.0  | 1         | 2.78%   |
| 0.51-1.0   | 1         | 2.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 19.35%  |
| LG Display          | 4         | 12.9%   |
| Sharp               | 3         | 9.68%   |
| Goldstar            | 3         | 9.68%   |
| Chimei Innolux      | 3         | 9.68%   |
| BOE                 | 2         | 6.45%   |
| AU Optronics        | 2         | 6.45%   |
| Unknown             | 1         | 3.23%   |
| SLD                 | 1         | 3.23%   |
| PLN                 | 1         | 3.23%   |
| Panasonic           | 1         | 3.23%   |
| Hewlett-Packard     | 1         | 3.23%   |
| Dell                | 1         | 3.23%   |
| AUS                 | 1         | 3.23%   |
| Acer                | 1         | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor Dell SE2717H/HX 1920x1080                        | 1         | 3.13%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                 | 1         | 3.13%   |
| Sharp LQ133M1JW02 SHP141A 1920x1080 294x165mm 13.3-inch              | 1         | 3.13%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 294x165mm 13.3-inch              | 1         | 3.13%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch              | 1         | 3.13%   |
| Samsung Electronics SyncMaster SAM05C8 1920x1080 520x290mm 23.4-inch | 1         | 3.13%   |
| Samsung Electronics SMFX2490HD SAM074A 1920x1080 530x300mm 24.0-inch | 1         | 3.13%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch | 1         | 3.13%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1         | 3.13%   |
| PLN LCD Monitor PXL2790MW 1920x1080                                  | 1         | 3.13%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch         | 1         | 3.13%   |
| LG Display LP101WSA-TLA1 LGD01B9 1024x600 224x126mm 10.1-inch        | 1         | 3.13%   |
| LG Display LCD Monitor LGD0439 1366x768 344x194mm 15.5-inch          | 1         | 3.13%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 1         | 3.13%   |
| LG Display LCD Monitor LGD01F7 1366x768 293x165mm 13.2-inch          | 1         | 3.13%   |
| Hewlett-Packard 25x HPN357F 1920x1080 544x303mm 24.5-inch            | 1         | 3.13%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch             | 1         | 3.13%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 1         | 3.13%   |
| Goldstar E2411 GSM583B 1920x1080 477x268mm 21.5-inch                 | 1         | 3.13%   |
| Dell P2419H DELD0D8 1920x1080 527x296mm 23.8-inch                    | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN1469 1366x768 309x174mm 14.0-inch      | 1         | 3.13%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                | 1         | 3.13%   |
| BOE LCD Monitor BOE068C 1366x768 256x144mm 11.6-inch                 | 1         | 3.13%   |
| AUS LCD Monitor ASUS VP278 1920x1080                                 | 1         | 3.13%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch       | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 1         | 3.13%   |
| Acer LCD Monitor B243W 1920x1200                                     | 1         | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 12        | 40%     |
| 1366x768 (WXGA)   | 12        | 40%     |
| 3840x2160 (4K)    | 2         | 6.67%   |
| 3440x1440         | 1         | 3.33%   |
| 2560x1080         | 1         | 3.33%   |
| 1920x1200 (WUXGA) | 1         | 3.33%   |
| 1024x600          | 1         | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 9         | 28.13%  |
| 13      | 5         | 15.63%  |
| 24      | 4         | 12.5%   |
| Unknown | 4         | 12.5%   |
| 34      | 2         | 6.25%   |
| 23      | 2         | 6.25%   |
| 18      | 1         | 3.13%   |
| 17      | 1         | 3.13%   |
| 14      | 1         | 3.13%   |
| 12      | 1         | 3.13%   |
| 11      | 1         | 3.13%   |
| 10      | 1         | 3.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 38.71%  |
| 201-300     | 6         | 19.35%  |
| 501-600     | 5         | 16.13%  |
| Unknown     | 4         | 12.9%   |
| 701-800     | 2         | 6.45%   |
| 401-500     | 1         | 3.23%   |
| 351-400     | 1         | 3.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 23        | 76.67%  |
| Unknown | 4         | 13.33%  |
| 21/9    | 2         | 6.67%   |
| 16/10   | 1         | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 9         | 29.03%  |
| 201-250        | 4         | 12.9%   |
| Unknown        | 4         | 12.9%   |
| 81-90          | 3         | 9.68%   |
| 71-80          | 3         | 9.68%   |
| 351-500        | 2         | 6.45%   |
| 61-70          | 1         | 3.23%   |
| 51-60          | 1         | 3.23%   |
| 41-50          | 1         | 3.23%   |
| 251-300        | 1         | 3.23%   |
| 141-150        | 1         | 3.23%   |
| 121-130        | 1         | 3.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 10        | 32.26%  |
| 51-100        | 8         | 25.81%  |
| 121-160       | 5         | 16.13%  |
| Unknown       | 4         | 12.9%   |
| More than 240 | 2         | 6.45%   |
| 161-240       | 2         | 6.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 31        | 86.11%  |
| 0     | 3         | 8.33%   |
| 2     | 2         | 5.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 20        | 40%     |
| Realtek Semiconductor     | 17        | 34%     |
| Qualcomm Atheros          | 6         | 12%     |
| TP-Link                   | 2         | 4%      |
| Spreadtrum Communications | 1         | 2%      |
| Sierra Wireless           | 1         | 2%      |
| Ralink Technology         | 1         | 2%      |
| Ralink                    | 1         | 2%      |
| Broadcom Limited          | 1         | 2%      |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 7         | 11.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 5         | 7.94%   |
| Intel I211 Gigabit Network Connection                                   | 3         | 4.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 3.17%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 2         | 3.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 3.17%   |
| Intel Wireless 8260                                                     | 2         | 3.17%   |
| Intel Wireless 7260                                                     | 2         | 3.17%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 3.17%   |
| Intel Ethernet Connection I219-V                                        | 2         | 3.17%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 1.59%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 1.59%   |
| Spreadtrum Unisoc Phone                                                 | 1         | 1.59%   |
| Sierra Wireless EM7305                                                  | 1         | 1.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.59%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.59%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 1.59%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 1.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.59%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 1.59%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.59%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.59%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 1         | 1.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 1.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 1.59%   |
| Intel Wireless 8265 / 8275                                              | 1         | 1.59%   |
| Intel Wireless 7265                                                     | 1         | 1.59%   |
| Intel WiMAX/WiFi Link 5150                                              | 1         | 1.59%   |
| Intel WiMAX Connection 2400m                                            | 1         | 1.59%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.59%   |
| Intel Ethernet Controller I225-V                                        | 1         | 1.59%   |
| Intel Ethernet Connection I217-V                                        | 1         | 1.59%   |
| Intel Ethernet Connection I217-LM                                       | 1         | 1.59%   |
| Intel Ethernet Connection (3) I218-V                                    | 1         | 1.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.59%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.59%   |
| Intel 82579V Gigabit Network Connection                                 | 1         | 1.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 48.39%  |
| Realtek Semiconductor | 6         | 19.35%  |
| Qualcomm Atheros      | 5         | 16.13%  |
| TP-Link               | 2         | 6.45%   |
| Sierra Wireless       | 1         | 3.23%   |
| Ralink Technology     | 1         | 3.23%   |
| Ralink                | 1         | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 6.45%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 6.45%   |
| Intel Wireless 8260                                                     | 2         | 6.45%   |
| Intel Wireless 7260                                                     | 2         | 6.45%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 6.45%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 3.23%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 3.23%   |
| Sierra Wireless EM7305                                                  | 1         | 3.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 3.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 3.23%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 3.23%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 3.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 3.23%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 3.23%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 3.23%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 1         | 3.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 3.23%   |
| Intel Wireless 8265 / 8275                                              | 1         | 3.23%   |
| Intel Wireless 7265                                                     | 1         | 3.23%   |
| Intel WiMAX/WiFi Link 5150                                              | 1         | 3.23%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 3.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 3.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 3.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 3.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 3.23%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 3.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 14        | 43.75%  |
| Realtek Semiconductor     | 13        | 40.63%  |
| Qualcomm Atheros          | 3         | 9.38%   |
| Spreadtrum Communications | 1         | 3.13%   |
| Broadcom Limited          | 1         | 3.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 21.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 15.63%  |
| Intel I211 Gigabit Network Connection                             | 3         | 9.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 6.25%   |
| Intel Ethernet Connection I219-V                                  | 2         | 6.25%   |
| Spreadtrum Unisoc Phone                                           | 1         | 3.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 3.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 3.13%   |
| Intel WiMAX Connection 2400m                                      | 1         | 3.13%   |
| Intel Ethernet Controller I225-V                                  | 1         | 3.13%   |
| Intel Ethernet Connection I217-V                                  | 1         | 3.13%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.13%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 3.13%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 3.13%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 3.13%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 3.13%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 3.13%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 3.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 50%     |
| Ethernet | 30        | 50%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 21        | 53.85%  |
| WiFi     | 18        | 46.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 20        | 55.56%  |
| 1     | 13        | 36.11%  |
| 0     | 3         | 8.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 21        | 58.33%  |
| Yes  | 15        | 41.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 8         | 66.67%  |
| Realtek Semiconductor           | 2         | 16.67%  |
| Qualcomm Atheros Communications | 1         | 8.33%   |
| Foxconn / Hon Hai               | 1         | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface | 4         | 33.33%  |
| Intel Bluetooth Device             | 2         | 16.67%  |
| Realtek RTL8821A Bluetooth         | 1         | 8.33%   |
| Realtek Bluetooth Radio            | 1         | 8.33%   |
| Qualcomm Atheros AR3011 Bluetooth  | 1         | 8.33%   |
| Intel Wireless-AC 3168 Bluetooth   | 1         | 8.33%   |
| Intel AX200 Bluetooth              | 1         | 8.33%   |
| Foxconn / Hon Hai Bluetooth Device | 1         | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 28        | 58.33%  |
| Nvidia   | 9         | 18.75%  |
| AMD      | 9         | 18.75%  |
| Logitech | 1         | 2.08%   |
| JMTek    | 1         | 2.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 5.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 5.36%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 5.36%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 3.57%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2         | 3.57%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 3.57%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 3.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 3.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 3.57%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 3.57%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.79%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.79%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 1.79%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 1.79%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1         | 1.79%   |
| Logitech ClearChat Pro USB                                                                        | 1         | 1.79%   |
| JMTek KLIM Talk                                                                                   | 1         | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.79%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.79%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 1.79%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.79%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.79%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.79%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.79%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.79%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 1.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.79%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.79%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.79%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.79%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.79%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.79%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 26.67%  |
| SK hynix            | 2         | 13.33%  |
| Micron Technology   | 2         | 13.33%  |
| Kingston            | 2         | 13.33%  |
| Unknown             | 1         | 6.67%   |
| Strontium           | 1         | 6.67%   |
| G.Skill             | 1         | 6.67%   |
| Crucial             | 1         | 6.67%   |
| Corsair             | 1         | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                                | 1         | 5.88%   |
| Strontium RAM SRT4G86S0-H9H 4GB SODIMM DDR3 1067MT/s                      | 1         | 5.88%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s                    | 1         | 5.88%   |
| SK hynix RAM 161616161616161616161616161616161616 1GB SODIMM DDR2 667MT/s | 1         | 5.88%   |
| SK hynix RAM 0C0C0C0C0C0C0C0C0C0C0C0C0C0C0C0C0C0C 1GB SODIMM DDR2 667MT/s | 1         | 5.88%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                               | 1         | 5.88%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                     | 1         | 5.88%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                     | 1         | 5.88%   |
| Samsung RAM M4 70T5663QZ3-CE6 2GB SODIMM DDR 667MT/s                      | 1         | 5.88%   |
| Micron RAM MT40A512M16TB-062E:R 4GB Row Of Chips DDR4 3200MT/s            | 1         | 5.88%   |
| Micron RAM 8ATF1G64HZ-2G6E3 8GB SODIMM DDR4 2667MT/s                      | 1         | 5.88%   |
| Micron RAM 4ATF51264HZ-3G2R1 4GB SODIMM DDR4 3200MT/s                     | 1         | 5.88%   |
| Kingston RAM M08GD16P1600C10 8GB SODIMM DDR3 1600MT/s                     | 1         | 5.88%   |
| Kingston RAM 99U5428-047.A00LF 4GB SODIMM 1067MT/s                        | 1         | 5.88%   |
| G.Skill RAM F3-1600C11-4GRSL 4GB SODIMM DDR3                              | 1         | 5.88%   |
| Crucial RAM CT16G4DFD8266.M16FE 16GB DIMM DDR4 2667MT/s                   | 1         | 5.88%   |
| Corsair RAM CMW32GX4M2Z3600C18 16GB DIMM DDR4 3733MT/s                    | 1         | 5.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind  | Computers | Percent |
|-------|-----------|---------|
| DDR4  | 5         | 38.46%  |
| DDR3  | 4         | 30.77%  |
| DDR2  | 3         | 23.08%  |
| SDRAM | 1         | 7.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 10        | 76.92%  |
| DIMM         | 2         | 15.38%  |
| Row Of Chips | 1         | 7.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 4         | 30.77%  |
| 8192  | 3         | 23.08%  |
| 4096  | 3         | 23.08%  |
| 16384 | 2         | 15.38%  |
| 1024  | 1         | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 3         | 21.43%  |
| 3200  | 2         | 14.29%  |
| 1067  | 2         | 14.29%  |
| 667   | 2         | 14.29%  |
| 4199  | 1         | 7.14%   |
| 3733  | 1         | 7.14%   |
| 2133  | 1         | 7.14%   |
| 1600  | 1         | 7.14%   |
| 533   | 1         | 7.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)

![Printer Vendor](./images/line_chart/printer_vendor.svg)

| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)

![Printer Model](./images/line_chart/printer_model.svg)

| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Seiko Epson ET-2820 Series | 1         | 100%    |

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

| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 5         | 27.78%  |
| Suyin                         | 2         | 11.11%  |
| Sunplus Innovation Technology | 2         | 11.11%  |
| Silicon Motion                | 2         | 11.11%  |
| Realtek Semiconductor         | 2         | 11.11%  |
| Quanta                        | 1         | 5.56%   |
| Microdia                      | 1         | 5.56%   |
| IMC Networks                  | 1         | 5.56%   |
| Alcor Micro                   | 1         | 5.56%   |
| Acer                          | 1         | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Suyin Lenovo EasyCamera            | 1         | 5.56%   |
| Suyin Integrated_Webcam_HD         | 1         | 5.56%   |
| Sunplus USB Camera                 | 1         | 5.56%   |
| Sunplus FHD Camera Microphone      | 1         | 5.56%   |
| Silicon Motion WebCam SC-0311139N  | 1         | 5.56%   |
| Silicon Motion 300k Pixel Camera   | 1         | 5.56%   |
| Realtek MTD camera                 | 1         | 5.56%   |
| Realtek Lenovo EasyCamera          | 1         | 5.56%   |
| Quanta USB Webcam                  | 1         | 5.56%   |
| Microdia Integrated_Webcam_HD      | 1         | 5.56%   |
| IMC Networks Integrated Camera     | 1         | 5.56%   |
| Chicony TOSHIBA Web Camera - FHD   | 1         | 5.56%   |
| Chicony Integrated Camera          | 1         | 5.56%   |
| Chicony HP TrueVision HD Camera    | 1         | 5.56%   |
| Chicony EasyCamera                 | 1         | 5.56%   |
| Chicony CNF9113                    | 1         | 5.56%   |
| Alcor Micro Asus Integrated Webcam | 1         | 5.56%   |
| Acer Integrated Camera             | 1         | 5.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 2         | 40%     |
| Microsoft             | 1         | 20%     |
| LighTuning Technology | 1         | 20%     |
| AuthenTec             | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader | 1         | 20%     |
| Validity Sensors VFS Fingerprint sensor     | 1         | 20%     |
| Microsoft Fingerprint Reader                | 1         | 20%     |
| LighTuning Fingerprint Reader               | 1         | 20%     |
| AuthenTec AES1600                           | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./images/line_chart/chipcard_vendor.svg)

| Vendor   | Computers | Percent |
|----------|-----------|---------|
| O2 Micro | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)

![Chipcard Model](./images/line_chart/chipcard_model.svg)

| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader | 2         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 24        | 66.67%  |
| 1     | 11        | 30.56%  |
| 2     | 1         | 2.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Graphics card      | 5         | 35.71%  |
| Fingerprint reader | 5         | 35.71%  |
| Chipcard           | 2         | 14.29%  |
| Storage/raid       | 1         | 7.14%   |
| Net/wireless       | 1         | 7.14%   |

