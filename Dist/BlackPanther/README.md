BlackPanther - Hardware Trends
------------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/BlackPanther/Desktop/README.md) and [notebooks](/Dist/BlackPanther/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/linuxhw/TestCoverage)

Period: May, 2022.

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

| Name              | Computers | Percent |
|-------------------|-----------|---------|
| BlackPanther 18.1 | 28        | 100%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| BlackPanther | 28        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 4.18.16-desktop-1bP | 15        | 53.57%  |
| 5.6.14-desktop-2bP  | 13        | 46.43%  |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.16 | 15        | 53.57%  |
| 5.6.14  | 13        | 46.43%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 15        | 53.57%  |
| 5.6     | 13        | 46.43%  |

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

| Name | Computers | Percent |
|------|-----------|---------|
| KDE5 | 28        | 100%    |

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

| Name | Computers | Percent |
|------|-----------|---------|
| SDDM | 28        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 28        | 100%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 18        | 64.29%  |
| EFI  | 10        | 35.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Overlay | 17        | 60.71%  |
| Ext4    | 11        | 39.29%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type | Computers | Percent |
|------|-----------|---------|
| MBR  | 15        | 53.57%  |
| GPT  | 13        | 46.43%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 15        | 53.57%  |
| Yes       | 13        | 46.43%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 18        | 64.29%  |
| Yes       | 10        | 35.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 6         | 21.43%  |
| Hewlett-Packard     | 4         | 14.29%  |
| Dell                | 4         | 14.29%  |
| MSI                 | 3         | 10.71%  |
| Gigabyte Technology | 3         | 10.71%  |
| ASUSTek Computer    | 3         | 10.71%  |
| Fujitsu             | 2         | 7.14%   |
| Toshiba             | 1         | 3.57%   |
| HUAWEI              | 1         | 3.57%   |
| Acer                | 1         | 3.57%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Toshiba Satellite L775-18R     | 1         | 3.57%   |
| MSI MS-7A33                    | 1         | 3.57%   |
| MSI MS-7846                    | 1         | 3.57%   |
| MSI GT60 2OC/2OD               | 1         | 3.57%   |
| Lenovo Yoga 300-11IBY 80M0     | 1         | 3.57%   |
| Lenovo ThinkCentre A57 98517HG | 1         | 3.57%   |
| Lenovo IdeaPad 320-17ABR 80YN  | 1         | 3.57%   |
| Lenovo G580 20150              | 1         | 3.57%   |
| Lenovo G570 20079              | 1         | 3.57%   |
| Lenovo B590 20208              | 1         | 3.57%   |
| HUAWEI HVY-WXX9                | 1         | 3.57%   |
| HP ProBook 640 G8 Notebook PC  | 1         | 3.57%   |
| HP Presario CQ58               | 1         | 3.57%   |
| HP 620                         | 1         | 3.57%   |
| HP 255 G5 Notebook PC          | 1         | 3.57%   |
| Gigabyte H61M-S1               | 1         | 3.57%   |
| Gigabyte G41MT-S2              | 1         | 3.57%   |
| Gigabyte B450M GAMING          | 1         | 3.57%   |
| Fujitsu LIFEBOOK U745          | 1         | 3.57%   |
| Fujitsu ESPRIMO E7935          | 1         | 3.57%   |
| Dell OptiPlex 320              | 1         | 3.57%   |
| Dell OptiPlex 3050             | 1         | 3.57%   |
| Dell Latitude E6430            | 1         | 3.57%   |
| Dell Latitude E6230            | 1         | 3.57%   |
| ASUS PRIME B365M-A             | 1         | 3.57%   |
| ASUS P8B75-M LX PLUS           | 1         | 3.57%   |
| ASUS K53U                      | 1         | 3.57%   |
| Acer Aspire 6930G              | 1         | 3.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell OptiPlex      | 2         | 7.14%   |
| Dell Latitude      | 2         | 7.14%   |
| Toshiba Satellite  | 1         | 3.57%   |
| MSI MS-7A33        | 1         | 3.57%   |
| MSI MS-7846        | 1         | 3.57%   |
| MSI GT60           | 1         | 3.57%   |
| Lenovo Yoga        | 1         | 3.57%   |
| Lenovo ThinkCentre | 1         | 3.57%   |
| Lenovo IdeaPad     | 1         | 3.57%   |
| Lenovo G580        | 1         | 3.57%   |
| Lenovo G570        | 1         | 3.57%   |
| Lenovo B590        | 1         | 3.57%   |
| HUAWEI HVY-WXX9    | 1         | 3.57%   |
| HP ProBook         | 1         | 3.57%   |
| HP Presario        | 1         | 3.57%   |
| HP 620             | 1         | 3.57%   |
| HP 255             | 1         | 3.57%   |
| Gigabyte H61M-S1   | 1         | 3.57%   |
| Gigabyte G41MT-S2  | 1         | 3.57%   |
| Gigabyte B450M     | 1         | 3.57%   |
| Fujitsu LIFEBOOK   | 1         | 3.57%   |
| Fujitsu ESPRIMO    | 1         | 3.57%   |
| ASUS PRIME         | 1         | 3.57%   |
| ASUS P8B75-M       | 1         | 3.57%   |
| ASUS K53U          | 1         | 3.57%   |
| Acer Aspire        | 1         | 3.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2012 | 7         | 25%     |
| 2017 | 3         | 10.71%  |
| 2011 | 3         | 10.71%  |
| 2010 | 3         | 10.71%  |
| 2013 | 2         | 7.14%   |
| 2008 | 2         | 7.14%   |
| 2021 | 1         | 3.57%   |
| 2020 | 1         | 3.57%   |
| 2019 | 1         | 3.57%   |
| 2018 | 1         | 3.57%   |
| 2016 | 1         | 3.57%   |
| 2015 | 1         | 3.57%   |
| 2014 | 1         | 3.57%   |
| 2007 | 1         | 3.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 17        | 60.71%  |
| Desktop  | 11        | 39.29%  |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 28        | 100%    |

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
| 8.01-16.0  | 8         | 28.57%  |
| 4.01-8.0   | 6         | 21.43%  |
| 3.01-4.0   | 6         | 21.43%  |
| 1.01-2.0   | 4         | 14.29%  |
| 16.01-24.0 | 2         | 7.14%   |
| 32.01-64.0 | 1         | 3.57%   |
| 2.01-3.0   | 1         | 3.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 20        | 71.43%  |
| 1.01-2.0 | 5         | 17.86%  |
| 0.01-0.5 | 3         | 10.71%  |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 17        | 60.71%  |
| 2      | 7         | 25%     |
| 3      | 3         | 10.71%  |
| 4      | 1         | 3.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 57.14%  |
| No        | 12        | 42.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 96.43%  |
| No        | 1         | 3.57%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 71.43%  |
| No        | 8         | 28.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 15        | 53.57%  |
| Yes       | 13        | 46.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country  | Computers | Percent |
|----------|-----------|---------|
| Hungary  | 22        | 78.57%  |
| Germany  | 2         | 7.14%   |
| UK       | 1         | 3.57%   |
| Slovakia | 1         | 3.57%   |
| Poland   | 1         | 3.57%   |
| France   | 1         | 3.57%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City              | Computers | Percent |
|-------------------|-----------|---------|
| Budapest          | 7         | 25%     |
| Kapuvar           | 2         | 7.14%   |
| Veszprém         | 1         | 3.57%   |
| Tornaľa          | 1         | 3.57%   |
| Szerencs          | 1         | 3.57%   |
| Szekszárd        | 1         | 3.57%   |
| Székesfehérvár | 1         | 3.57%   |
| Ostringen         | 1         | 3.57%   |
| Oroshaza          | 1         | 3.57%   |
| Munich            | 1         | 3.57%   |
| Mezobereny        | 1         | 3.57%   |
| Krakow            | 1         | 3.57%   |
| Kisvarda          | 1         | 3.57%   |
| Kiskunlachaza     | 1         | 3.57%   |
| Hove              | 1         | 3.57%   |
| Houilles          | 1         | 3.57%   |
| Győr             | 1         | 3.57%   |
| Gyomro            | 1         | 3.57%   |
| Esztergom         | 1         | 3.57%   |
| Eger              | 1         | 3.57%   |
| Debrecen          | 1         | 3.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 17.07%  |
| Kingston            | 7         | 8      | 17.07%  |
| WDC                 | 6         | 6      | 14.63%  |
| Seagate             | 3         | 4      | 7.32%   |
| Toshiba             | 2         | 2      | 4.88%   |
| Hitachi             | 2         | 2      | 4.88%   |
| HGST                | 2         | 2      | 4.88%   |
| A-DATA Technology   | 2         | 2      | 4.88%   |
| Zheino              | 1         | 1      | 2.44%   |
| SSSTC               | 1         | 1      | 2.44%   |
| SPCC                | 1         | 1      | 2.44%   |
| MAXTOR              | 1         | 1      | 2.44%   |
| LITEONIT            | 1         | 1      | 2.44%   |
| JMicron             | 1         | 1      | 2.44%   |
| Crucial             | 1         | 1      | 2.44%   |
| China               | 1         | 1      | 2.44%   |
| ASMT                | 1         | 1      | 2.44%   |
| Apacer              | 1         | 1      | 2.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SV300S37A120G 120GB SSD     | 2         | 4.65%   |
| A-DATA SU630 240GB SSD               | 2         | 4.65%   |
| Zheino CHN-NGFFNV2280-256 256GB      | 1         | 2.33%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 2.33%   |
| WDC WD6400AAKS-65A7B2 640GB          | 1         | 2.33%   |
| WDC WD400BD-75MRA1 40GB              | 1         | 2.33%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 2.33%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 2.33%   |
| WDC WD10JPLX-00MBPT0 1TB             | 1         | 2.33%   |
| Toshiba MK6475GSX 640GB              | 1         | 2.33%   |
| Toshiba DT01ACA100 1TB               | 1         | 2.33%   |
| SSSTC CL1-8D256-HP 256GB             | 1         | 2.33%   |
| SPCC Solid State Disk 128GB          | 1         | 2.33%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 2.33%   |
| Seagate ST500LM000-SSHD-8GB          | 1         | 2.33%   |
| Seagate ST4000DM004-2CV104 4TB       | 1         | 2.33%   |
| Seagate ST2000DM008-2FR102 2TB       | 1         | 2.33%   |
| Samsung SSD 980 PRO 1TB              | 1         | 2.33%   |
| Samsung SSD 870 EVO 500GB            | 1         | 2.33%   |
| Samsung SSD 860 EVO 250GB            | 1         | 2.33%   |
| Samsung SSD 830 Series 128GB         | 1         | 2.33%   |
| Samsung MZVLB512HBJQ-00000 512GB     | 1         | 2.33%   |
| Samsung MZ7LN256HCHP-00000 256GB SSD | 1         | 2.33%   |
| Samsung HM160HI 160GB                | 1         | 2.33%   |
| Samsung HD103UJ 1TB                  | 1         | 2.33%   |
| MAXTOR 2B020H1 20GB                  | 1         | 2.33%   |
| LITEONIT LMT-128M6M mSATA 128GB SSD  | 1         | 2.33%   |
| Kingston SUV400S37240G 240GB SSD     | 1         | 2.33%   |
| Kingston SUV400S37120G 120GB SSD     | 1         | 2.33%   |
| Kingston SA400S37960G 960GB SSD      | 1         | 2.33%   |
| Kingston SA400S37120G 120GB SSD      | 1         | 2.33%   |
| Kingston SA2000M8250G 250GB          | 1         | 2.33%   |
| JMicron Tech 250GB                   | 1         | 2.33%   |
| Hitachi HTS727575A9E364 752GB        | 1         | 2.33%   |
| Hitachi HTS547550A9E384 500GB        | 1         | 2.33%   |
| HGST HTS545050A7E680 500GB           | 1         | 2.33%   |
| HGST HTS541010B7E610 1TB             | 1         | 2.33%   |
| Crucial M4-CT256M4SSD2 256GB         | 1         | 2.33%   |
| China SATA SSD 120GB                 | 1         | 2.33%   |
| ASMT USB 3.0 TOSATA 120GB            | 1         | 2.33%   |
| Apacer AS350 256GB SSD               | 1         | 2.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 29.41%  |
| Seagate             | 3         | 4      | 17.65%  |
| Toshiba             | 2         | 2      | 11.76%  |
| Samsung Electronics | 2         | 2      | 11.76%  |
| Hitachi             | 2         | 2      | 11.76%  |
| HGST                | 2         | 2      | 11.76%  |
| MAXTOR              | 1         | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 7      | 33.33%  |
| Samsung Electronics | 4         | 4      | 22.22%  |
| A-DATA Technology   | 2         | 2      | 11.11%  |
| WDC                 | 1         | 1      | 5.56%   |
| SPCC                | 1         | 1      | 5.56%   |
| LITEONIT            | 1         | 1      | 5.56%   |
| Crucial             | 1         | 1      | 5.56%   |
| China               | 1         | 1      | 5.56%   |
| Apacer              | 1         | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 17        | 19     | 44.74%  |
| HDD     | 15        | 18     | 39.47%  |
| NVMe    | 4         | 5      | 10.53%  |
| Unknown | 2         | 2      | 5.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 26        | 37     | 81.25%  |
| NVMe | 4         | 5      | 12.5%   |
| SAS  | 2         | 2      | 6.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 25     | 65.63%  |
| 0.51-1.0   | 8         | 9      | 25%     |
| 1.01-2.0   | 2         | 2      | 6.25%   |
| 3.01-4.0   | 1         | 1      | 3.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 60.71%  |
| 101-250    | 7         | 25%     |
| 21-50      | 1         | 3.57%   |
| 1-20       | 1         | 3.57%   |
| 501-1000   | 1         | 3.57%   |
| 51-100     | 1         | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB | Computers | Percent |
|---------|-----------|---------|
| Unknown | 17        | 60.71%  |
| 1-20    | 11        | 39.29%  |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD6400AAKS-65A7B2 640GB       | 1         | 1      | 8.33%   |
| WDC WD10JPLX-00MBPT0 1TB          | 1         | 1      | 8.33%   |
| Toshiba MK6475GSX 640GB           | 1         | 1      | 8.33%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 8.33%   |
| Seagate ST500LM000-SSHD-8GB       | 1         | 1      | 8.33%   |
| Samsung Electronics HM160HI 160GB | 1         | 1      | 8.33%   |
| Samsung Electronics HD103UJ 1TB   | 1         | 1      | 8.33%   |
| MAXTOR 2B020H1 20GB               | 1         | 1      | 8.33%   |
| Kingston SV300S37A120G 120GB SSD  | 1         | 1      | 8.33%   |
| Kingston SUV400S37240G 240GB SSD  | 1         | 1      | 8.33%   |
| HGST HTS545050A7E680 500GB        | 1         | 1      | 8.33%   |
| A-DATA Technology SU630 240GB SSD | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 16.67%  |
| Seagate             | 2         | 2      | 16.67%  |
| Samsung Electronics | 2         | 2      | 16.67%  |
| Kingston            | 2         | 2      | 16.67%  |
| Toshiba             | 1         | 1      | 8.33%   |
| MAXTOR              | 1         | 1      | 8.33%   |
| HGST                | 1         | 1      | 8.33%   |
| A-DATA Technology   | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 22.22%  |
| Seagate             | 2         | 2      | 22.22%  |
| Samsung Electronics | 2         | 2      | 22.22%  |
| Toshiba             | 1         | 1      | 11.11%  |
| MAXTOR              | 1         | 1      | 11.11%  |
| HGST                | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 9      | 75%     |
| SSD  | 3         | 3      | 25%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)

![Failed Drives](./All/images/line_chart/drive_failed.svg)

| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Zheino CHN-NGFFNV2280-256 256GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)

![Failed Drive Vendor](./All/images/line_chart/drive_failed_vendor.svg)

| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| Zheino | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)

![Drive Status](./All/images/line_chart/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 20        | 29     | 57.14%  |
| Malfunc  | 12        | 12     | 34.29%  |
| Detected | 2         | 2      | 5.71%   |
| Failed   | 1         | 1      | 2.86%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 20        | 64.52%  |
| AMD                            | 7         | 22.58%  |
| Solid State Storage Technology | 1         | 3.23%   |
| Silicon Motion                 | 1         | 3.23%   |
| Samsung Electronics            | 1         | 3.23%   |
| Kingston Technology Company    | 1         | 3.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 4         | 10.26%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 5.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 2         | 5.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 5.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2         | 5.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2         | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 5.13%   |
| Solid State Storage Non-Volatile memory controller                                      | 1         | 2.56%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 2.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 2.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 2.56%   |
| Kingston Company A2000 NVMe SSD                                                         | 1         | 2.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1         | 2.56%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1         | 2.56%   |
| Intel SATA Controller [RAID mode]                                                       | 1         | 2.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 2.56%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 1         | 2.56%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 1         | 2.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 2.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1         | 2.56%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 2.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 2.56%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1         | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1         | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1         | 2.56%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 1         | 2.56%   |
| AMD SB600 IDE                                                                           | 1         | 2.56%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1         | 2.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 18        | 52.94%  |
| IDE  | 8         | 23.53%  |
| RAID | 4         | 11.76%  |
| NVMe | 4         | 11.76%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 21        | 75%     |
| AMD    | 7         | 25%     |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-3340M CPU @ 2.70GHz               | 2         | 7.14%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 1         | 3.57%   |
| Intel Pentium CPU G3420 @ 3.20GHz               | 1         | 3.57%   |
| Intel Pentium CPU B960 @ 2.20GHz                | 1         | 3.57%   |
| Intel Genuine CPU 2140 @ 1.60GHz                | 1         | 3.57%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 3.57%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz              | 1         | 3.57%   |
| Intel Core i7-2630QM CPU @ 2.00GHz              | 1         | 3.57%   |
| Intel Core i5-7500 CPU @ 3.40GHz                | 1         | 3.57%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1         | 3.57%   |
| Intel Core i5-2450M CPU @ 2.50GHz               | 1         | 3.57%   |
| Intel Core i3-8100 CPU @ 3.60GHz                | 1         | 3.57%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 1         | 3.57%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 1         | 3.57%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz           | 1         | 3.57%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 1         | 3.57%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz            | 1         | 3.57%   |
| Intel Core 2 CPU 4300 @ 1.80GHz                 | 1         | 3.57%   |
| Intel Celeron Dual-Core CPU T3100 @ 1.90GHz     | 1         | 3.57%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 1         | 3.57%   |
| AMD Ryzen 5 4600H with Radeon Graphics          | 1         | 3.57%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 1         | 3.57%   |
| AMD Ryzen 5 1400 Quad-Core Processor            | 1         | 3.57%   |
| AMD E-350 Processor                             | 1         | 3.57%   |
| AMD E-300 APU with Radeon HD Graphics           | 1         | 3.57%   |
| AMD A6-7310 APU with AMD Radeon R4 Graphics     | 1         | 3.57%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 1         | 3.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 5         | 17.86%  |
| Intel Pentium           | 3         | 10.71%  |
| Intel Core i7           | 3         | 10.71%  |
| Intel Core i3           | 3         | 10.71%  |
| AMD Ryzen 5             | 3         | 10.71%  |
| Intel Core 2 Duo        | 2         | 7.14%   |
| AMD E                   | 2         | 7.14%   |
| Other                   | 1         | 3.57%   |
| Intel Genuine           | 1         | 3.57%   |
| Intel Core 2 Quad       | 1         | 3.57%   |
| Intel Core 2            | 1         | 3.57%   |
| Intel Celeron Dual-Core | 1         | 3.57%   |
| AMD A6                  | 1         | 3.57%   |
| AMD A12                 | 1         | 3.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 15        | 53.57%  |
| 4      | 10        | 35.71%  |
| 1      | 2         | 7.14%   |
| 6      | 1         | 3.57%   |

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
| 1      | 16        | 57.14%  |
| 2      | 12        | 42.86%  |

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
| 0x306a9    | 5         | 17.86%  |
| 0x206a7    | 3         | 10.71%  |
| 0x1067a    | 3         | 10.71%  |
| 0x6f2      | 2         | 7.14%   |
| 0x306c3    | 2         | 7.14%   |
| 0x906eb    | 1         | 3.57%   |
| 0x906e9    | 1         | 3.57%   |
| 0x806c1    | 1         | 3.57%   |
| 0x6fb      | 1         | 3.57%   |
| 0x306d4    | 1         | 3.57%   |
| 0x30678    | 1         | 3.57%   |
| 0x08600106 | 1         | 3.57%   |
| 0x08108109 | 1         | 3.57%   |
| 0x08001137 | 1         | 3.57%   |
| 0x07030105 | 1         | 3.57%   |
| 0x06006118 | 1         | 3.57%   |
| 0x05000119 | 1         | 3.57%   |
| 0x05000029 | 1         | 3.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| IvyBridge   | 5         | 17.86%  |
| SandyBridge | 3         | 10.71%  |
| Penryn      | 3         | 10.71%  |
| Core        | 3         | 10.71%  |
| KabyLake    | 2         | 7.14%   |
| Haswell     | 2         | 7.14%   |
| Bobcat      | 2         | 7.14%   |
| Zen+        | 1         | 3.57%   |
| Zen 2       | 1         | 3.57%   |
| Zen         | 1         | 3.57%   |
| TigerLake   | 1         | 3.57%   |
| Silvermont  | 1         | 3.57%   |
| Puma        | 1         | 3.57%   |
| Excavator   | 1         | 3.57%   |
| Broadwell   | 1         | 3.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 16        | 50%     |
| AMD    | 9         | 28.13%  |
| Nvidia | 7         | 21.88%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 3         | 9.09%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 2         | 6.06%   |
| AMD Wrestler [Radeon HD 6310]                                                         | 2         | 6.06%   |
| Nvidia GP107 [GeForce GTX 1050]                                                       | 1         | 3.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 1         | 3.03%   |
| Nvidia GK107 [GeForce GTX 650]                                                        | 1         | 3.03%   |
| Nvidia GK106M [GeForce GTX 770M]                                                      | 1         | 3.03%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 1         | 3.03%   |
| Nvidia GF108M [GeForce GT 525M]                                                       | 1         | 3.03%   |
| Nvidia G96CM [GeForce 9600M GS]                                                       | 1         | 3.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 3.03%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 1         | 3.03%   |
| Intel Tiger Lake UHD Graphics                                                         | 1         | 3.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 3.03%   |
| Intel HD Graphics 630                                                                 | 1         | 3.03%   |
| Intel HD Graphics 5500                                                                | 1         | 3.03%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 1         | 3.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 1         | 3.03%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                | 1         | 3.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 1         | 3.03%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 1         | 3.03%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 1         | 3.03%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 3.03%   |
| AMD Renoir                                                                            | 1         | 3.03%   |
| AMD RC410 [Radeon Xpress 200/1100]                                                    | 1         | 3.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 3.03%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 1         | 3.03%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 1         | 3.03%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                      | 1         | 3.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 12        | 42.86%  |
| 1 x AMD        | 8         | 28.57%  |
| 1 x Nvidia     | 5         | 17.86%  |
| Intel + Nvidia | 2         | 7.14%   |
| 2 x AMD        | 1         | 3.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver | Computers | Percent |
|--------|-----------|---------|
| Free   | 28        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 12        | 42.86%  |
| 0.01-0.5   | 6         | 21.43%  |
| 0.51-1.0   | 4         | 14.29%  |
| 1.01-2.0   | 3         | 10.71%  |
| 5.01-6.0   | 1         | 3.57%   |
| 3.01-4.0   | 1         | 3.57%   |
| 2.01-3.0   | 1         | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 5         | 17.86%  |
| LG Display              | 5         | 17.86%  |
| AU Optronics            | 3         | 10.71%  |
| Dell                    | 2         | 7.14%   |
| Chimei Innolux          | 2         | 7.14%   |
| BOE                     | 2         | 7.14%   |
| S2-Tek                  | 1         | 3.57%   |
| PANDA                   | 1         | 3.57%   |
| Lenovo                  | 1         | 3.57%   |
| Impression              | 1         | 3.57%   |
| Hewlett-Packard         | 1         | 3.57%   |
| Goldstar                | 1         | 3.57%   |
| Chi Mei Optoelectronics | 1         | 3.57%   |
| BenQ                    | 1         | 3.57%   |
| Acer                    | 1         | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM01B8 1280x1024 338x270mm 17.0-inch     | 1         | 3.45%   |
| Samsung Electronics S27E500 SAM0D0D 1920x1080 598x336mm 27.0-inch        | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch     | 1         | 3.45%   |
| S2-Tek TV STK531A 1920x1080 930x530mm 42.1-inch                          | 1         | 3.45%   |
| PANDA LCD Monitor NCP0065 1920x1080 309x174mm 14.0-inch                  | 1         | 3.45%   |
| LG Display LCD Monitor LGD036C 1366x768 277x156mm 12.5-inch              | 1         | 3.45%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch              | 1         | 3.45%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 3.45%   |
| LG Display LCD Monitor LGD02AD 1366x768 344x194mm 15.5-inch              | 1         | 3.45%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 1         | 3.45%   |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                    | 1         | 3.45%   |
| Impression R19W11 IMP1911 1440x900 410x257mm 19.1-inch                   | 1         | 3.45%   |
| Hewlett-Packard L1502 HWP2600 1024x768 304x228mm 15.0-inch               | 1         | 3.45%   |
| Goldstar L204WT GSM4E48 1680x1050 434x270mm 20.1-inch                    | 1         | 3.45%   |
| Goldstar L204WT GSM4E47 1680x1050 434x270mm 20.1-inch                    | 1         | 3.45%   |
| Dell S2721D DELA19A 2560x1440 597x336mm 27.0-inch                        | 1         | 3.45%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                        | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch         | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 1         | 3.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 3.45%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 1         | 3.45%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                     | 1         | 3.45%   |
| BenQ G2010W BNQ7811 1680x1050 474x296mm 22.0-inch                        | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 1         | 3.45%   |
| Acer V193W ACR0025 1440x900 408x255mm 18.9-inch                          | 1         | 3.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 10        | 35.71%  |
| 1920x1080 (FHD)    | 8         | 28.57%  |
| 1680x1050 (WSXGA+) | 2         | 7.14%   |
| 1600x900 (HD+)     | 2         | 7.14%   |
| 1440x900 (WXGA+)   | 2         | 7.14%   |
| 1280x1024 (SXGA)   | 2         | 7.14%   |
| 2560x1440 (QHD)    | 1         | 3.57%   |
| 1024x768 (XGA)     | 1         | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 10        | 35.71%  |
| 17     | 4         | 14.29%  |
| 27     | 2         | 7.14%   |
| 14     | 2         | 7.14%   |
| 42     | 1         | 3.57%   |
| 22     | 1         | 3.57%   |
| 21     | 1         | 3.57%   |
| 20     | 1         | 3.57%   |
| 19     | 1         | 3.57%   |
| 18     | 1         | 3.57%   |
| 16     | 1         | 3.57%   |
| 13     | 1         | 3.57%   |
| 12     | 1         | 3.57%   |
| 11     | 1         | 3.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 50%     |
| 401-500     | 5         | 17.86%  |
| 351-400     | 4         | 14.29%  |
| 501-600     | 2         | 7.14%   |
| 201-300     | 2         | 7.14%   |
| 901-1000    | 1         | 3.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 21        | 75%     |
| 16/10 | 4         | 14.29%  |
| 5/4   | 2         | 7.14%   |
| 4/3   | 1         | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 11        | 39.29%  |
| 81-90          | 3         | 10.71%  |
| 151-200        | 3         | 10.71%  |
| 301-350        | 2         | 7.14%   |
| 201-250        | 2         | 7.14%   |
| 141-150        | 2         | 7.14%   |
| 121-130        | 2         | 7.14%   |
| 61-70          | 1         | 3.57%   |
| 51-60          | 1         | 3.57%   |
| 501-1000       | 1         | 3.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 11        | 39.29%  |
| 51-100  | 11        | 39.29%  |
| 121-160 | 6         | 21.43%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 28        | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 16        | 37.21%  |
| Intel                      | 11        | 25.58%  |
| Qualcomm Atheros           | 8         | 18.6%   |
| Broadcom Limited           | 2         | 4.65%   |
| Broadcom                   | 2         | 4.65%   |
| TP-Link                    | 1         | 2.33%   |
| Shenzhen Goodix Technology | 1         | 2.33%   |
| Microsoft                  | 1         | 2.33%   |
| Marvell Technology Group   | 1         | 2.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 26.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 4.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 4.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 4.08%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                             | 1         | 2.04%   |
| Shenzhen Goodix Unknow device                                     | 1         | 2.04%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 2.04%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 2.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 2.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 2.04%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.04%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.04%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 2.04%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 2.04%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1         | 2.04%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 2.04%   |
| Intel Wireless 7265                                               | 1         | 2.04%   |
| Intel Wireless 7260                                               | 1         | 2.04%   |
| Intel Wireless 3165                                               | 1         | 2.04%   |
| Intel Wireless 3160                                               | 1         | 2.04%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 2.04%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 2.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 2.04%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.04%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 2.04%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 2.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 2.04%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 2.04%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 2.04%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 1         | 2.04%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 42.86%  |
| Qualcomm Atheros      | 4         | 19.05%  |
| Realtek Semiconductor | 3         | 14.29%  |
| Broadcom              | 2         | 9.52%   |
| TP-Link               | 1         | 4.76%   |
| Microsoft             | 1         | 4.76%   |
| Broadcom Limited      | 1         | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 9.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 9.52%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                          | 1         | 4.76%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 4.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 4.76%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 4.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 4.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 4.76%   |
| Microsoft Xbox 360 Wireless Adapter                            | 1         | 4.76%   |
| Intel Wireless 7265                                            | 1         | 4.76%   |
| Intel Wireless 7260                                            | 1         | 4.76%   |
| Intel Wireless 3165                                            | 1         | 4.76%   |
| Intel Wireless 3160                                            | 1         | 4.76%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 4.76%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 4.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 4.76%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 4.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1         | 4.76%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 1         | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 15        | 55.56%  |
| Qualcomm Atheros         | 5         | 18.52%  |
| Intel                    | 5         | 18.52%  |
| Marvell Technology Group | 1         | 3.7%    |
| Broadcom Limited         | 1         | 3.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 48.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 7.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 7.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 3.7%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 3.7%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 3.7%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 3.7%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 3.7%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 3.7%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 3.7%    |
| Intel Ethernet Connection (13) I219-V                             | 1         | 3.7%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 3.7%    |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 3.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 27        | 56.25%  |
| WiFi     | 20        | 41.67%  |
| Unknown  | 1         | 2.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 15        | 50%     |
| Ethernet | 15        | 50%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 17        | 60.71%  |
| 1     | 11        | 39.29%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 22        | 78.57%  |
| Yes  | 6         | 21.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 46.15%  |
| Qualcomm Atheros Communications | 3         | 23.08%  |
| Foxconn / Hon Hai               | 2         | 15.38%  |
| Realtek Semiconductor           | 1         | 7.69%   |
| Cambridge Silicon Radio         | 1         | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 3         | 23.08%  |
| Realtek Bluetooth Radio                             | 1         | 7.69%   |
| Qualcomm Atheros Bluetooth                          | 1         | 7.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 7.69%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 7.69%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 7.69%   |
| Intel AX201 Bluetooth                               | 1         | 7.69%   |
| Intel AX200 Bluetooth                               | 1         | 7.69%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 7.69%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 20        | 55.56%  |
| AMD                 | 10        | 27.78%  |
| Nvidia              | 5         | 13.89%  |
| C-Media Electronics | 1         | 2.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 11.36%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 6.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 4.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 4.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 4.55%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 4.55%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 4.55%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 4.55%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 4.55%   |
| AMD FCH Azalia Controller                                                  | 2         | 4.55%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 4.55%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 2.27%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 2.27%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 2.27%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 2.27%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.27%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 2.27%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 2.27%   |
| C-Media Electronics Blue Snowball                                          | 1         | 2.27%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 2.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 2.27%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 2.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 2.27%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 2.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 21.88%  |
| SK Hynix            | 6         | 18.75%  |
| Micron Technology   | 5         | 15.63%  |
| Kingston            | 5         | 15.63%  |
| Unknown             | 3         | 9.38%   |
| Corsair             | 2         | 6.25%   |
| Nanya Technology    | 1         | 3.13%   |
| Kingmax             | 1         | 3.13%   |
| G.Skill             | 1         | 3.13%   |
| ASint Technology    | 1         | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s                    | 2         | 5.13%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                                    | 1         | 2.56%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                             | 1         | 2.56%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                               | 1         | 2.56%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.56%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.56%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s                 | 1         | 2.56%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.56%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s                    | 1         | 2.56%   |
| SK Hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM DDR3 1333MT/s                 | 1         | 2.56%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s                    | 1         | 2.56%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1334MT/s                 | 1         | 2.56%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                            | 1         | 2.56%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.56%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.56%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s                  | 1         | 2.56%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                     | 1         | 2.56%   |
| Samsung RAM M3 78T2953EZ3-CE6 1024MB DIMM DDR2 667MT/s                    | 1         | 2.56%   |
| Samsung RAM 4D332037385435363633515A332D43463720 2048MB DIMM DDR2 800MT/s | 1         | 2.56%   |
| Nanya RAM NT4GC64C88B1NS-DI 4096MB SODIMM DDR3 1600MT/s                   | 1         | 2.56%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                             | 1         | 2.56%   |
| Micron RAM Module 2048MB SODIMM DDR3 1333MT/s                             | 1         | 2.56%   |
| Micron RAM 8KTF25664HZ-1G6M1 2048MB SODIMM DDR3 1600MT/s                  | 1         | 2.56%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s                  | 1         | 2.56%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s             | 1         | 2.56%   |
| Kingston RAM Module 8192MB SODIMM DDR3 1600MT/s                           | 1         | 2.56%   |
| Kingston RAM M471B1G73BH0-YK0 8192MB SODIMM DDR3 1600MT/s                 | 1         | 2.56%   |
| Kingston RAM KPN424-ELJ 1024MB DIMM DDR 667MT/s                           | 1         | 2.56%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                         | 1         | 2.56%   |
| Kingston RAM KHX1600C10D3/8G 4096MB DIMM DDR3 1600MT/s                    | 1         | 2.56%   |
| Kingmax RAM GLAG42F-18--------- 8192MB DIMM DDR4 2666MT/s                 | 1         | 2.56%   |
| Kingmax RAM GLAF62F-D8--------- 4096MB DIMM DDR4 2400MT/s                 | 1         | 2.56%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s                     | 1         | 2.56%   |
| Corsair RAM CMX8GX3M2B1600C9 4096MB DIMM DDR3 1600MT/s                    | 1         | 2.56%   |
| Corsair RAM CMK32GX4M2A2400C16 16384MB DIMM DDR4 2400MT/s                 | 1         | 2.56%   |
| ASint RAM SSZ3128M8-EDJEF 2048MB SODIMM DDR3 1333MT/s                     | 1         | 2.56%   |
| ASint RAM SSY3128M8-EDJEF 1024MB SODIMM DDR3 1333MT/s                     | 1         | 2.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 16        | 55.17%  |
| DDR4    | 7         | 24.14%  |
| DDR2    | 4         | 13.79%  |
| SDRAM   | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 16        | 57.14%  |
| DIMM         | 11        | 39.29%  |
| Row Of Chips | 1         | 3.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 12        | 37.5%   |
| 8192  | 8         | 25%     |
| 2048  | 8         | 25%     |
| 1024  | 3         | 9.38%   |
| 16384 | 1         | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 11        | 35.48%  |
| 2400  | 4         | 12.9%   |
| 3200  | 3         | 9.68%   |
| 1333  | 3         | 9.68%   |
| 667   | 3         | 9.68%   |
| 3466  | 1         | 3.23%   |
| 2667  | 1         | 3.23%   |
| 2666  | 1         | 3.23%   |
| 1867  | 1         | 3.23%   |
| 1334  | 1         | 3.23%   |
| 800   | 1         | 3.23%   |
| 400   | 1         | 3.23%   |

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

| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| HP DeskJet 2620 All-in-One Printer | 1         | 100%    |

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
| Chicony Electronics                    | 6         | 35.29%  |
| Microdia                               | 2         | 11.76%  |
| Cheng Uei Precision Industry (Foxlink) | 2         | 11.76%  |
| Acer                                   | 2         | 11.76%  |
| Suyin                                  | 1         | 5.88%   |
| Realtek Semiconductor                  | 1         | 5.88%   |
| Quanta                                 | 1         | 5.88%   |
| Logitech                               | 1         | 5.88%   |
| IMC Networks                           | 1         | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Lenovo EasyCamera                        | 2         | 11.76%  |
| Acer Lenovo Integrated Webcam                    | 2         | 11.76%  |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 1         | 5.88%   |
| Realtek FJ Camera                                | 1         | 5.88%   |
| Quanta HP HD Camera                              | 1         | 5.88%   |
| Microdia Dell Integrated HD Webcam               | 1         | 5.88%   |
| Microdia Camera                                  | 1         | 5.88%   |
| Logitech HD Webcam C525                          | 1         | 5.88%   |
| IMC Networks EasyCamera                          | 1         | 5.88%   |
| Chicony HP Webcam-50                             | 1         | 5.88%   |
| Chicony HP Webcam                                | 1         | 5.88%   |
| Chicony CNFA078                                  | 1         | 5.88%   |
| Chicony CNF9055 Toshiba Webcam                   | 1         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) Webcam    | 1         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 1         | 5.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Upek   | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 100%    |

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

| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 23        | 82.14%  |
| 1     | 5         | 17.86%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 2         | 40%     |
| Chipcard           | 2         | 40%     |
| Network            | 1         | 20%     |

