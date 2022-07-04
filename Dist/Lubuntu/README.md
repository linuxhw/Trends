Lubuntu - Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu/Desktop/README.md) and [notebooks](/Dist/Lubuntu/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/linuxhw/TestCoverage)

Period: Jun, 2022.

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

| Name          | Computers | Percent |
|---------------|-----------|---------|
| Lubuntu 22.04 | 18        | 64.29%  |
| Lubuntu 21.10 | 4         | 14.29%  |
| Lubuntu 20.04 | 3         | 10.71%  |
| Lubuntu 22.10 | 1         | 3.57%   |
| Lubuntu 21.04 | 1         | 3.57%   |
| Lubuntu 18.04 | 1         | 3.57%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Lubuntu | 28        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.15.0-39-generic     | 4         | 14.29%  |
| 5.15.0-40-generic     | 3         | 10.71%  |
| 5.15.0-35-generic     | 3         | 10.71%  |
| 5.15.0-30-generic     | 3         | 10.71%  |
| 5.4.0-113-generic     | 2         | 7.14%   |
| 5.15.0-37-generic     | 2         | 7.14%   |
| 5.15.0-33-generic     | 2         | 7.14%   |
| 5.18.0-051800-generic | 1         | 3.57%   |
| 5.15.0-25-generic     | 1         | 3.57%   |
| 5.13.0-52-generic     | 1         | 3.57%   |
| 5.13.0-48-generic     | 1         | 3.57%   |
| 5.13.0-46-generic     | 1         | 3.57%   |
| 5.13.0-35-generic     | 1         | 3.57%   |
| 5.13.0-19-generic     | 1         | 3.57%   |
| 5.11.0-49-generic     | 1         | 3.57%   |
| 4.15.0-180-generic    | 1         | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 18        | 64.29%  |
| 5.13.0  | 5         | 17.86%  |
| 5.4.0   | 2         | 7.14%   |
| 5.18.0  | 1         | 3.57%   |
| 5.11.0  | 1         | 3.57%   |
| 4.15.0  | 1         | 3.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 18        | 64.29%  |
| 5.13    | 5         | 17.86%  |
| 5.4     | 2         | 7.14%   |
| 5.18    | 1         | 3.57%   |
| 5.11    | 1         | 3.57%   |
| 4.15    | 1         | 3.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 27        | 96.43%  |
| i686   | 1         | 3.57%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| LXQt   | 25        | 89.29%  |
| LXDE   | 2         | 7.14%   |
| Budgie | 1         | 3.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 27        | 96.43%  |
| Tty  | 1         | 3.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 24        | 85.71%  |
| LightDM | 2         | 7.14%   |
| XDM     | 1         | 3.57%   |
| GDM     | 1         | 3.57%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| fr_FR | 6         | 21.43%  |
| en_US | 6         | 21.43%  |
| en_GB | 4         | 14.29%  |
| pt_BR | 3         | 10.71%  |
| de_DE | 3         | 10.71%  |
| C     | 2         | 7.14%   |
| nl_BE | 1         | 3.57%   |
| ja_JP | 1         | 3.57%   |
| it_IT | 1         | 3.57%   |
| es_ES | 1         | 3.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 21        | 75%     |
| EFI  | 7         | 25%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 26        | 92.86%  |
| Overlay | 2         | 7.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 12        | 42.86%  |
| GPT     | 9         | 32.14%  |
| MBR     | 7         | 25%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 96.43%  |
| Yes       | 1         | 3.57%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 22        | 78.57%  |
| Yes       | 6         | 21.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 17.86%  |
| ASUSTek Computer    | 5         | 17.86%  |
| MSI                 | 3         | 10.71%  |
| Dell                | 3         | 10.71%  |
| Lenovo              | 2         | 7.14%   |
| Intel               | 2         | 7.14%   |
| Gigabyte Technology | 2         | 7.14%   |
| Apple               | 2         | 7.14%   |
| Sony                | 1         | 3.57%   |
| Google              | 1         | 3.57%   |
| Gateway             | 1         | 3.57%   |
| AMI                 | 1         | 3.57%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Sony VGN-SZ71WN_C                 | 1         | 3.57%   |
| MSI VR630                         | 1         | 3.57%   |
| MSI MS-AA1511                     | 1         | 3.57%   |
| MSI MS-7641                       | 1         | 3.57%   |
| Lenovo Yoga 710-11IKB 80V6        | 1         | 3.57%   |
| Lenovo ThinkCentre M83 10ANCTO1WW | 1         | 3.57%   |
| Intel Infoway                     | 1         | 3.57%   |
| Intel DQ57TM                      | 1         | 3.57%   |
| HP ProBook 640 G1                 | 1         | 3.57%   |
| HP Pavilion Sleekbook 15 PC       | 1         | 3.57%   |
| HP Pavilion g6                    | 1         | 3.57%   |
| HP Notebook                       | 1         | 3.57%   |
| HP G62                            | 1         | 3.57%   |
| Google Bobba360                   | 1         | 3.57%   |
| Gigabyte H370AORUSGAMING3WIFI     | 1         | 3.57%   |
| Gigabyte GA-MA69G-S3H             | 1         | 3.57%   |
| Gateway Sonic-C                   | 1         | 3.57%   |
| Dell Studio 1537                  | 1         | 3.57%   |
| Dell OptiPlex 3020M               | 1         | 3.57%   |
| Dell Latitude XT                  | 1         | 3.57%   |
| ASUS PRIME X370-A                 | 1         | 3.57%   |
| ASUS N56VZ                        | 1         | 3.57%   |
| ASUS M4N78-AM                     | 1         | 3.57%   |
| ASUS E403SA                       | 1         | 3.57%   |
| ASUS 1000H                        | 1         | 3.57%   |
| Apple MacBookPro8,1               | 1         | 3.57%   |
| Apple MacBookPro10,1              | 1         | 3.57%   |
| AMI VTC1010                       | 1         | 3.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| HP Pavilion                   | 2         | 7.14%   |
| Sony VGN-SZ71WN               | 1         | 3.57%   |
| MSI VR630                     | 1         | 3.57%   |
| MSI MS-AA1511                 | 1         | 3.57%   |
| MSI MS-7641                   | 1         | 3.57%   |
| Lenovo Yoga                   | 1         | 3.57%   |
| Lenovo ThinkCentre            | 1         | 3.57%   |
| Intel Infoway                 | 1         | 3.57%   |
| Intel DQ57TM                  | 1         | 3.57%   |
| HP ProBook                    | 1         | 3.57%   |
| HP Notebook                   | 1         | 3.57%   |
| HP G62                        | 1         | 3.57%   |
| Google Bobba360               | 1         | 3.57%   |
| Gigabyte H370AORUSGAMING3WIFI | 1         | 3.57%   |
| Gigabyte GA-MA69G-S3H         | 1         | 3.57%   |
| Gateway Sonic-C               | 1         | 3.57%   |
| Dell Studio                   | 1         | 3.57%   |
| Dell OptiPlex                 | 1         | 3.57%   |
| Dell Latitude                 | 1         | 3.57%   |
| ASUS PRIME                    | 1         | 3.57%   |
| ASUS N56VZ                    | 1         | 3.57%   |
| ASUS M4N78-AM                 | 1         | 3.57%   |
| ASUS E403SA                   | 1         | 3.57%   |
| ASUS 1000H                    | 1         | 3.57%   |
| Apple MacBookPro8             | 1         | 3.57%   |
| Apple MacBookPro10            | 1         | 3.57%   |
| AMI VTC1010                   | 1         | 3.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 4         | 14.29%  |
| 2008 | 4         | 14.29%  |
| 2015 | 3         | 10.71%  |
| 2007 | 3         | 10.71%  |
| 2018 | 2         | 7.14%   |
| 2017 | 2         | 7.14%   |
| 2012 | 2         | 7.14%   |
| 2010 | 2         | 7.14%   |
| 2009 | 2         | 7.14%   |
| 2022 | 1         | 3.57%   |
| 2016 | 1         | 3.57%   |
| 2014 | 1         | 3.57%   |
| 2013 | 1         | 3.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 18        | 64.29%  |
| Desktop    | 8         | 28.57%  |
| Mini pc    | 1         | 3.57%   |
| All in one | 1         | 3.57%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 27        | 96.43%  |
| Enabled  | 1         | 3.57%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 26        | 92.86%  |
| Yes  | 2         | 7.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 10        | 35.71%  |
| 4.01-8.0   | 9         | 32.14%  |
| 2.01-3.0   | 4         | 14.29%  |
| 16.01-24.0 | 3         | 10.71%  |
| 32.01-64.0 | 1         | 3.57%   |
| 1.01-2.0   | 1         | 3.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 11        | 39.29%  |
| 0.51-1.0 | 11        | 39.29%  |
| 2.01-3.0 | 3         | 10.71%  |
| 4.01-8.0 | 2         | 7.14%   |
| 0.01-0.5 | 1         | 3.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 24        | 85.71%  |
| 2      | 3         | 10.71%  |
| 3      | 1         | 3.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 50%     |
| No        | 14        | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 92.86%  |
| No        | 2         | 7.14%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 78.57%  |
| No        | 6         | 21.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 53.57%  |
| No        | 13        | 46.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country     | Computers | Percent |
|-------------|-----------|---------|
| France      | 6         | 21.43%  |
| USA         | 3         | 10.71%  |
| Germany     | 3         | 10.71%  |
| Brazil      | 3         | 10.71%  |
| UK          | 2         | 7.14%   |
| Spain       | 2         | 7.14%   |
| Ukraine     | 1         | 3.57%   |
| Sweden      | 1         | 3.57%   |
| Portugal    | 1         | 3.57%   |
| Netherlands | 1         | 3.57%   |
| Japan       | 1         | 3.57%   |
| Italy       | 1         | 3.57%   |
| Canada      | 1         | 3.57%   |
| Belgium     | 1         | 3.57%   |
| Belarus     | 1         | 3.57%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Paris                | 3         | 10.71%  |
| Wolfhagen            | 1         | 3.57%   |
| Vitebsk              | 1         | 3.57%   |
| Valentigney          | 1         | 3.57%   |
| Valencia             | 1         | 3.57%   |
| Tokorozawa           | 1         | 3.57%   |
| Stockholm            | 1         | 3.57%   |
| Shildon              | 1         | 3.57%   |
| Roswell              | 1         | 3.57%   |
| Rio de Janeiro       | 1         | 3.57%   |
| Richmond             | 1         | 3.57%   |
| Portland             | 1         | 3.57%   |
| Oshawa               | 1         | 3.57%   |
| Novo Gama            | 1         | 3.57%   |
| Mieuxce              | 1         | 3.57%   |
| Lisbon               | 1         | 3.57%   |
| Kyiv                 | 1         | 3.57%   |
| Hoogstraten          | 1         | 3.57%   |
| Giebelstadt          | 1         | 3.57%   |
| Frankfurt am Main    | 1         | 3.57%   |
| Fortaleza            | 1         | 3.57%   |
| el Prat de Llobregat | 1         | 3.57%   |
| Cirey-sur-Vezouze    | 1         | 3.57%   |
| Bradford             | 1         | 3.57%   |
| Berkel en Rodenrijs  | 1         | 3.57%   |
| Arluno               | 1         | 3.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 7      | 19.35%  |
| Hitachi             | 5         | 5      | 16.13%  |
| Toshiba             | 3         | 3      | 9.68%   |
| Seagate             | 3         | 3      | 9.68%   |
| Unknown             | 2         | 2      | 6.45%   |
| Samsung Electronics | 2         | 2      | 6.45%   |
| Crucial             | 2         | 2      | 6.45%   |
| Apacer              | 2         | 2      | 6.45%   |
| Teclast             | 1         | 1      | 3.23%   |
| SK hynix            | 1         | 1      | 3.23%   |
| Maxtor              | 1         | 1      | 3.23%   |
| Lenovo              | 1         | 1      | 3.23%   |
| A-DATA Technology   | 1         | 1      | 3.23%   |
| 2.5"                | 1         | 1      | 3.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| WDC WD800BB-00CAA1 80GB                         | 1         | 3.13%   |
| WDC WD5000AAKX-07U6AA0 500GB                    | 1         | 3.13%   |
| WDC WD40EZAZ-00SF3B0 4TB                        | 1         | 3.13%   |
| WDC WD3200BEVT-22ZCT0 320GB                     | 1         | 3.13%   |
| WDC WD3200BEVT-00A0RT0 320GB                    | 1         | 3.13%   |
| WDC WD3200AAJS-00L7A0 320GB                     | 1         | 3.13%   |
| WDC WD10JPVX-60JC3T0 1TB                        | 1         | 3.13%   |
| Unknown DA4032  32GB                            | 1         | 3.13%   |
| Unknown CGND3R  64GB                            | 1         | 3.13%   |
| Toshiba MK8009GAH 80GB                          | 1         | 3.13%   |
| Toshiba MK6465GSX 640GB                         | 1         | 3.13%   |
| Toshiba DT01ABA100V 1TB                         | 1         | 3.13%   |
| Teclast 240GB A800 SSD                          | 1         | 3.13%   |
| SK hynix HFS128G39MND-3310A 128GB SSD           | 1         | 3.13%   |
| Seagate ST9320325ASG 320GB                      | 1         | 3.13%   |
| Seagate ST500DM002-1BD142 500GB                 | 1         | 3.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 3.13%   |
| Samsung SSD 970 EVO 500GB                       | 1         | 3.13%   |
| Samsung HM121HI 120GB                           | 1         | 3.13%   |
| Maxtor STM3160215AS 160GB                       | 1         | 3.13%   |
| Lenovo SSD SL700 480G                           | 1         | 3.13%   |
| Hitachi HUA723030ALA640 81Y2460 81Y3844IBMH 3TB | 1         | 3.13%   |
| Hitachi HTS723232A7A364 320GB                   | 1         | 3.13%   |
| Hitachi HTS545050A7E380 500GB                   | 1         | 3.13%   |
| Hitachi HTS543232L9A300 320GB                   | 1         | 3.13%   |
| Hitachi HDT722520DLA380 200GB                   | 1         | 3.13%   |
| Crucial M4-CT128M4SSD2 128GB                    | 1         | 3.13%   |
| Crucial CT1000BX500SSD1 1TB                     | 1         | 3.13%   |
| Apacer AS350 256GB SSD                          | 1         | 3.13%   |
| Apacer 16GB SATA Flash Drive SSD                | 1         | 3.13%   |
| A-DATA SU740 1TB SSD                            | 1         | 3.13%   |
| 2.5" SATA SSD 3MG2-P 64GB                       | 1         | 3.13%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 7      | 31.58%  |
| Hitachi             | 5         | 5      | 26.32%  |
| Toshiba             | 3         | 3      | 15.79%  |
| Seagate             | 3         | 3      | 15.79%  |
| Samsung Electronics | 1         | 1      | 5.26%   |
| Maxtor              | 1         | 1      | 5.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Crucial           | 2         | 2      | 22.22%  |
| Apacer            | 2         | 2      | 22.22%  |
| Teclast           | 1         | 1      | 11.11%  |
| SK hynix          | 1         | 1      | 11.11%  |
| Lenovo            | 1         | 1      | 11.11%  |
| A-DATA Technology | 1         | 1      | 11.11%  |
| 2.5"              | 1         | 1      | 11.11%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 20     | 60%     |
| SSD  | 9         | 9      | 30%     |
| MMC  | 2         | 2      | 6.67%   |
| NVMe | 1         | 1      | 3.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 26        | 29     | 89.66%  |
| MMC  | 2         | 2      | 6.9%    |
| NVMe | 1         | 1      | 3.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 21     | 71.43%  |
| 0.51-1.0   | 6         | 6      | 21.43%  |
| 3.01-4.0   | 1         | 1      | 3.57%   |
| 2.01-3.0   | 1         | 1      | 3.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 7         | 25%     |
| 101-250    | 5         | 17.86%  |
| 501-1000   | 5         | 17.86%  |
| 51-100     | 5         | 17.86%  |
| 1-20       | 3         | 10.71%  |
| 21-50      | 2         | 7.14%   |
| 2001-3000  | 1         | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 16        | 57.14%  |
| 21-50    | 6         | 21.43%  |
| 101-250  | 3         | 10.71%  |
| 251-500  | 2         | 7.14%   |
| 501-1000 | 1         | 3.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD3200AAJS-00L7A0 320GB        | 1         | 1      | 14.29%  |
| Toshiba MK6465GSX 640GB            | 1         | 1      | 14.29%  |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 14.29%  |
| Samsung Electronics HM121HI 120GB  | 1         | 1      | 14.29%  |
| Hitachi HTS723232A7A364 320GB      | 1         | 1      | 14.29%  |
| Hitachi HTS545050A7E380 500GB      | 1         | 1      | 14.29%  |
| Apacer 16GB SATA Flash Drive SSD   | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 2         | 2      | 28.57%  |
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| Seagate             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Apacer              | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 2         | 2      | 33.33%  |
| WDC                 | 1         | 1      | 16.67%  |
| Toshiba             | 1         | 1      | 16.67%  |
| Seagate             | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 6      | 85.71%  |
| SSD  | 1         | 1      | 14.29%  |

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
| Detected | 12        | 13     | 42.86%  |
| Works    | 9         | 12     | 32.14%  |
| Malfunc  | 7         | 7      | 25%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 16        | 57.14%  |
| AMD                 | 7         | 25%     |
| Nvidia              | 3         | 10.71%  |
| Samsung Electronics | 1         | 3.57%   |
| JMicron Technology  | 1         | 3.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 8.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 8.11%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 8.11%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 5.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 5.41%   |
| AMD SB600 IDE                                                                  | 2         | 5.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 2.7%    |
| Nvidia nForce SATA Controller                                                  | 1         | 2.7%    |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 2.7%    |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                   | 1         | 2.7%    |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 1         | 2.7%    |
| JMicron JMB363 SATA/IDE Controller                                             | 1         | 2.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 2.7%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 2.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 2.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 2.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 2.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 2.7%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 1         | 2.7%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 2.7%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                          | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1         | 2.7%    |
| AMD X370 Series Chipset SATA Controller                                        | 1         | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1         | 2.7%    |
| AMD SB600 Non-Raid-5 SATA                                                      | 1         | 2.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 21        | 65.63%  |
| IDE  | 10        | 31.25%  |
| NVMe | 1         | 3.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 20        | 71.43%  |
| AMD    | 8         | 28.57%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Pentium CPU 987 @ 1.50GHz                 | 1         | 3.57%   |
| Intel Core i7-4600M CPU @ 2.90GHz               | 1         | 3.57%   |
| Intel Core i7-3615QM CPU @ 2.30GHz              | 1         | 3.57%   |
| Intel Core i7-3610QM CPU @ 2.30GHz              | 1         | 3.57%   |
| Intel Core i5-9400F CPU @ 2.90GHz               | 1         | 3.57%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz                | 1         | 3.57%   |
| Intel Core i5-4590T CPU @ 2.00GHz               | 1         | 3.57%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 1         | 3.57%   |
| Intel Core i5-2415M CPU @ 2.30GHz               | 1         | 3.57%   |
| Intel Core i5 CPU 650 @ 3.20GHz                 | 1         | 3.57%   |
| Intel Core 2 Duo CPU U7700 @ 1.33GHz            | 1         | 3.57%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz            | 1         | 3.57%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz            | 1         | 3.57%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz            | 1         | 3.57%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                | 1         | 3.57%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 1         | 3.57%   |
| Intel Celeron Dual-Core CPU T3100 @ 1.90GHz     | 1         | 3.57%   |
| Intel Celeron CPU N3150 @ 1.60GHz               | 1         | 3.57%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 1         | 3.57%   |
| Intel Atom CPU E3827 @ 1.74GHz                  | 1         | 3.57%   |
| AMD Ryzen 7 2700 Eight-Core Processor           | 1         | 3.57%   |
| AMD Phenom II N830 Triple-Core Processor        | 1         | 3.57%   |
| AMD FX-6350 Six-Core Processor                  | 1         | 3.57%   |
| AMD Athlon X2 Dual-Core QL-62                   | 1         | 3.57%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+      | 1         | 3.57%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+      | 1         | 3.57%   |
| AMD A6-4400M APU with Radeon HD Graphics        | 1         | 3.57%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G | 1         | 3.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 6         | 21.43%  |
| Intel Core 2 Duo        | 4         | 14.29%  |
| Intel Core i7           | 3         | 10.71%  |
| Intel Celeron           | 2         | 7.14%   |
| Intel Atom              | 2         | 7.14%   |
| AMD Athlon 64 X2        | 2         | 7.14%   |
| Intel Pentium           | 1         | 3.57%   |
| Intel Core 2            | 1         | 3.57%   |
| Intel Celeron Dual-Core | 1         | 3.57%   |
| AMD Ryzen 7             | 1         | 3.57%   |
| AMD Phenom II           | 1         | 3.57%   |
| AMD FX                  | 1         | 3.57%   |
| AMD Athlon X2           | 1         | 3.57%   |
| AMD A6                  | 1         | 3.57%   |
| AMD A10                 | 1         | 3.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 16        | 57.14%  |
| 4      | 5         | 17.86%  |
| 1      | 3         | 10.71%  |
| 3      | 2         | 7.14%   |
| 8      | 1         | 3.57%   |
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
| 1      | 17        | 60.71%  |
| 2      | 11        | 39.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 27        | 96.43%  |
| 32-bit         | 1         | 3.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 32.14%  |
| 0x306c3    | 3         | 10.71%  |
| 0x306a9    | 2         | 7.14%   |
| 0x206a7    | 2         | 7.14%   |
| 0x906ea    | 1         | 3.57%   |
| 0x806e9    | 1         | 3.57%   |
| 0x6fa      | 1         | 3.57%   |
| 0x6f6      | 1         | 3.57%   |
| 0x406c3    | 1         | 3.57%   |
| 0x30679    | 1         | 3.57%   |
| 0x106c2    | 1         | 3.57%   |
| 0x1067a    | 1         | 3.57%   |
| 0x0600611a | 1         | 3.57%   |
| 0x06001116 | 1         | 3.57%   |
| 0x06000852 | 1         | 3.57%   |
| 0x010000c8 | 1         | 3.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Penryn          | 3         | 10.71%  |
| Haswell         | 3         | 10.71%  |
| Core            | 3         | 10.71%  |
| Silvermont      | 2         | 7.14%   |
| SandyBridge     | 2         | 7.14%   |
| Piledriver      | 2         | 7.14%   |
| KabyLake        | 2         | 7.14%   |
| K8 Hammer       | 2         | 7.14%   |
| IvyBridge       | 2         | 7.14%   |
| Zen+            | 1         | 3.57%   |
| Westmere        | 1         | 3.57%   |
| K8 & K10 hybrid | 1         | 3.57%   |
| K10             | 1         | 3.57%   |
| Goldmont plus   | 1         | 3.57%   |
| Excavator       | 1         | 3.57%   |
| Bonnell         | 1         | 3.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 15        | 48.39%  |
| Nvidia | 9         | 29.03%  |
| AMD    | 7         | 22.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 5.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 5.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 5.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 5.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 5.56%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 2.78%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 2.78%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 2.78%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 2.78%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 2.78%   |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 2.78%   |
| Nvidia C79 [ION]                                                                         | 1         | 2.78%   |
| Nvidia C77 [GeForce 9100M G]                                                             | 1         | 2.78%   |
| Nvidia C77 [GeForce 8200]                                                                | 1         | 2.78%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 2.78%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 2.78%   |
| Intel HD Graphics 615                                                                    | 1         | 2.78%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 2.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 2.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.78%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 2.78%   |
| AMD Trinity 2 [Radeon HD 7520G]                                                          | 1         | 2.78%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 2.78%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 2.78%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 1         | 2.78%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 1         | 2.78%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 2.78%   |
| AMD RS690 [Radeon X1200]                                                                 | 1         | 2.78%   |
| AMD RS600M [Radeon Xpress 1250]                                                          | 1         | 2.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 12        | 42.86%  |
| 1 x Nvidia     | 7         | 25%     |
| 1 x AMD        | 4         | 14.29%  |
| 2 x AMD        | 2         | 7.14%   |
| Other          | 1         | 3.57%   |
| Intel + Nvidia | 1         | 3.57%   |
| AMD + Nvidia   | 1         | 3.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 27        | 96.43%  |
| Proprietary | 1         | 3.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 67.86%  |
| 0.01-0.5   | 6         | 21.43%  |
| 7.01-8.0   | 1         | 3.57%   |
| 5.01-6.0   | 1         | 3.57%   |
| 1.01-2.0   | 1         | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| LG Display           | 3         | 10.34%  |
| Chimei Innolux       | 3         | 10.34%  |
| AU Optronics         | 3         | 10.34%  |
| Samsung Electronics  | 2         | 6.9%    |
| Dell                 | 2         | 6.9%    |
| CPT                  | 2         | 6.9%    |
| Apple                | 2         | 6.9%    |
| Ancor Communications | 2         | 6.9%    |
| Videoseven           | 1         | 3.45%   |
| Unknown              | 1         | 3.45%   |
| MSI                  | 1         | 3.45%   |
| IOD                  | 1         | 3.45%   |
| Hewlett-Packard      | 1         | 3.45%   |
| HannStar             | 1         | 3.45%   |
| Gigabyte Technology  | 1         | 3.45%   |
| Eizo                 | 1         | 3.45%   |
| BOE                  | 1         | 3.45%   |
| BenQ                 | 1         | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 2         | 6.67%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                  | 2         | 6.67%   |
| Videoseven L19FM IGM0812 1280x1024 376x301mm 19.0-inch                | 1         | 3.33%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 3.33%   |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 3.33%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch  | 1         | 3.33%   |
| MSI Wind Net MSI7459 1600x900 462x272mm 21.1-inch                     | 1         | 3.33%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch          | 1         | 3.33%   |
| IOD LCD-A153G IOD0F46 1024x768 304x228mm 15.0-inch                    | 1         | 3.33%   |
| Hewlett-Packard L2245w HWP26FB 1680x1050 473x296mm 22.0-inch          | 1         | 3.33%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 3.33%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 598x336mm 27.0-inch        | 1         | 3.33%   |
| Eizo L565 ENC1651 1280x1024 337x270mm 17.0-inch                       | 1         | 3.33%   |
| Dell P190S DEL405A 1280x1024 376x301mm 19.0-inch                      | 1         | 3.33%   |
| Dell E2011H DEL406C 1600x900 443x249mm 20.0-inch                      | 1         | 3.33%   |
| Dell E1909W DELF00D 1440x900 408x255mm 18.9-inch                      | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch       | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN1137 1920x1080 256x144mm 11.6-inch      | 1         | 3.33%   |
| BOE NV116WHM-T16 BOE0956 1366x768 256x144mm 11.6-inch                 | 1         | 3.33%   |
| BenQ GW2265 BNQ78D1 1920x1080 477x268mm 21.5-inch                     | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO8114 1280x800 261x163mm 12.1-inch         | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO333C 1366x768 309x173mm 13.9-inch         | 1         | 3.33%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                | 1         | 3.33%   |
| Apple Color LCD APPA00F 2880x1800 331x207mm 15.4-inch                 | 1         | 3.33%   |
| Ancor Communications VW22A ACI22E3 1680x1050 473x296mm 22.0-inch      | 1         | 3.33%   |
| Ancor Communications VE228 ACI22FA 1920x1080 480x270mm 21.7-inch      | 1         | 3.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 6         | 20%     |
| 1366x768 (WXGA)    | 6         | 20%     |
| 1280x800 (WXGA)    | 4         | 13.33%  |
| 1680x1050 (WSXGA+) | 3         | 10%     |
| 2288x1287          | 2         | 6.67%   |
| 1600x900 (HD+)     | 2         | 6.67%   |
| 1280x1024 (SXGA)   | 2         | 6.67%   |
| 2880x1800          | 1         | 3.33%   |
| 2560x1440 (QHD)    | 1         | 3.33%   |
| 1440x900 (WXGA+)   | 1         | 3.33%   |
| 1024x768 (XGA)     | 1         | 3.33%   |
| 1024x600           | 1         | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 10        | 33.33%  |
| 19     | 3         | 10%     |
| 22     | 2         | 6.67%   |
| 21     | 2         | 6.67%   |
| 13     | 2         | 6.67%   |
| 11     | 2         | 6.67%   |
| 142    | 1         | 3.33%   |
| 27     | 1         | 3.33%   |
| 24     | 1         | 3.33%   |
| 20     | 1         | 3.33%   |
| 17     | 1         | 3.33%   |
| 16     | 1         | 3.33%   |
| 14     | 1         | 3.33%   |
| 12     | 1         | 3.33%   |
| 10     | 1         | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 12        | 40%     |
| 401-500        | 6         | 20%     |
| 201-300        | 5         | 16.67%  |
| 351-400        | 4         | 13.33%  |
| 501-600        | 2         | 6.67%   |
| More than 2000 | 1         | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 15        | 51.72%  |
| 16/10 | 9         | 31.03%  |
| 5/4   | 3         | 10.34%  |
| 4/3   | 1         | 3.45%   |
| 1.00  | 1         | 3.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 34.48%  |
| 201-250        | 4         | 13.79%  |
| 151-200        | 4         | 13.79%  |
| 81-90          | 3         | 10.34%  |
| 51-60          | 2         | 6.9%    |
| More than 1000 | 1         | 3.45%   |
| 61-70          | 1         | 3.45%   |
| 41-50          | 1         | 3.45%   |
| 301-350        | 1         | 3.45%   |
| 141-150        | 1         | 3.45%   |
| 121-130        | 1         | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 12        | 42.86%  |
| 101-120 | 9         | 32.14%  |
| 121-160 | 4         | 14.29%  |
| 161-240 | 2         | 7.14%   |
| 1-50    | 1         | 3.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 25        | 89.29%  |
| 2     | 2         | 7.14%   |
| 3     | 1         | 3.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 12        | 26.67%  |
| Intel                           | 9         | 20%     |
| Qualcomm Atheros                | 7         | 15.56%  |
| Broadcom                        | 5         | 11.11%  |
| Ralink                          | 2         | 4.44%   |
| Marvell Technology Group        | 2         | 4.44%   |
| Broadcom Limited                | 2         | 4.44%   |
| Trident Microsystems            | 1         | 2.22%   |
| Ralink Technology               | 1         | 2.22%   |
| Qualcomm Atheros Communications | 1         | 2.22%   |
| Qualcomm                        | 1         | 2.22%   |
| Nvidia                          | 1         | 2.22%   |
| Logitec                         | 1         | 2.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 9.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 7.69%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 2         | 3.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 3.85%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 3.85%   |
| Intel Wireless 7260                                               | 2         | 3.85%   |
| Trident Microsystems 4DWave DX                                    | 1         | 1.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.92%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.92%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 1.92%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.92%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 1.92%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 1.92%   |
| Qualcomm Redmi 9T                                                 | 1         | 1.92%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter   | 1         | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.92%   |
| Qualcomm Atheros UB94                                             | 1         | 1.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 1.92%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.92%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.92%   |
| Nvidia MCP77 Ethernet                                             | 1         | 1.92%   |
| Logitec LAN-W150N/U2 Wireless LAN Adapter                         | 1         | 1.92%   |
| Intel WiFi Link 5100                                              | 1         | 1.92%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 1.92%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 1.92%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.92%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.92%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.92%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.92%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.92%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 1.92%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.92%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.92%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.92%   |
| Broadcom NetXtreme BCM5756ME Gigabit Ethernet PCI Express         | 1         | 1.92%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.92%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                            | 1         | 1.92%   |
| Broadcom Limited BCM4311 802.11a/b/g                              | 1         | 1.92%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 1         | 1.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.92%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 7         | 29.17%  |
| Qualcomm Atheros                | 5         | 20.83%  |
| Realtek Semiconductor           | 3         | 12.5%   |
| Ralink                          | 2         | 8.33%   |
| Broadcom Limited                | 2         | 8.33%   |
| Broadcom                        | 2         | 8.33%   |
| Ralink Technology               | 1         | 4.17%   |
| Qualcomm Atheros Communications | 1         | 4.17%   |
| Logitec                         | 1         | 4.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                       | 2         | 8.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 2         | 8.33%   |
| Intel Wireless 7260                                             | 2         | 8.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                 | 1         | 4.17%   |
| Realtek RTL8191SEvB Wireless LAN Controller                     | 1         | 4.17%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter        | 1         | 4.17%   |
| Ralink RT5370 Wireless Adapter                                  | 1         | 4.17%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1         | 4.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 1         | 4.17%   |
| Qualcomm Atheros UB94                                           | 1         | 4.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 1         | 4.17%   |
| Logitec LAN-W150N/U2 Wireless LAN Adapter                       | 1         | 4.17%   |
| Intel WiFi Link 5100                                            | 1         | 4.17%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection   | 1         | 4.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection           | 1         | 4.17%   |
| Intel Centrino Wireless-N 2230                                  | 1         | 4.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 1         | 4.17%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                          | 1         | 4.17%   |
| Broadcom Limited BCM4311 802.11a/b/g                            | 1         | 4.17%   |
| Broadcom BCM4331 802.11a/b/g/n                                  | 1         | 4.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter             | 1         | 4.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 11        | 39.29%  |
| Intel                    | 6         | 21.43%  |
| Broadcom                 | 4         | 14.29%  |
| Qualcomm Atheros         | 2         | 7.14%   |
| Marvell Technology Group | 2         | 7.14%   |
| Trident Microsystems     | 1         | 3.57%   |
| Qualcomm                 | 1         | 3.57%   |
| Nvidia                   | 1         | 3.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 17.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 14.29%  |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 7.14%   |
| Trident Microsystems 4DWave DX                                    | 1         | 3.57%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 3.57%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 3.57%   |
| Qualcomm Redmi 9T                                                 | 1         | 3.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 3.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 3.57%   |
| Nvidia MCP77 Ethernet                                             | 1         | 3.57%   |
| Intel I210 Gigabit Network Connection                             | 1         | 3.57%   |
| Intel Ethernet Connection I217-V                                  | 1         | 3.57%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.57%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 3.57%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 3.57%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 3.57%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 3.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 3.57%   |
| Broadcom NetXtreme BCM5756ME Gigabit Ethernet PCI Express         | 1         | 3.57%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 3.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 26        | 54.17%  |
| WiFi     | 22        | 45.83%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 16        | 57.14%  |
| Ethernet | 12        | 42.86%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 17        | 60.71%  |
| 1     | 9         | 32.14%  |
| 3     | 1         | 3.57%   |
| 0     | 1         | 3.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 15        | 53.57%  |
| Yes  | 13        | 46.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 4         | 25%     |
| Qualcomm Atheros Communications | 2         | 12.5%   |
| Apple                           | 2         | 12.5%   |
| Realtek Semiconductor           | 1         | 6.25%   |
| Logitech                        | 1         | 6.25%   |
| IMC Networks                    | 1         | 6.25%   |
| Dell                            | 1         | 6.25%   |
| Cambridge Silicon Radio         | 1         | 6.25%   |
| Broadcom                        | 1         | 6.25%   |
| ASUSTek Computer                | 1         | 6.25%   |
| Alps Electric                   | 1         | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 2         | 12.5%   |
| Apple Bluetooth Host Controller                     | 2         | 12.5%   |
| Realtek Bluetooth Radio                             | 1         | 6.25%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 6.25%   |
| Qualcomm Atheros Bluetooth                          | 1         | 6.25%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1         | 6.25%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 6.25%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 6.25%   |
| Dell Wireless 360 Bluetooth                         | 1         | 6.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 6.25%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 6.25%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 6.25%   |
| Alps Electric Bluetooth Adapter                     | 1         | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 18        | 48.65%  |
| Nvidia              | 8         | 21.62%  |
| AMD                 | 8         | 21.62%  |
| Logitech            | 1         | 2.7%    |
| Ensoniq             | 1         | 2.7%    |
| C-Media Electronics | 1         | 2.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 8.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 6.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 6.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 6.52%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 4.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 4.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 4.35%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 2.17%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 2.17%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 2.17%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 2.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 2.17%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 2.17%   |
| Logitech PRO X Wireless Gaming Headset                                                            | 1         | 2.17%   |
| Logitech Blue Microphones                                                                         | 1         | 2.17%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 2.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 2.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 2.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 2.17%   |
| Ensoniq ES1371/ES1373 / Creative Labs CT2518                                                      | 1         | 2.17%   |
| C-Media Electronics CM108 Audio Controller                                                        | 1         | 2.17%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 2.17%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 2.17%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 1         | 2.17%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 2.17%   |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                                                  | 1         | 2.17%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 2.17%   |
| AMD FCH Azalia Controller                                                                         | 1         | 2.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 2.17%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 2.17%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 7         | 31.82%  |
| Unknown             | 4         | 18.18%  |
| Micron Technology   | 3         | 13.64%  |
| Samsung Electronics | 2         | 9.09%   |
| Corsair             | 2         | 9.09%   |
| Unknown             | 2         | 9.09%   |
| Smart               | 1         | 4.55%   |
| HMD                 | 1         | 4.55%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 10.71%  |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 2         | 7.14%   |
| Unknown                                                      | 2         | 7.14%   |
| Unknown RAM Module 4GB SODIMM DDR3 800MT/s                   | 1         | 3.57%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                  | 1         | 3.57%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                   | 1         | 3.57%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s        | 1         | 3.57%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB DIMM SDRAM 1639MT/s        | 1         | 3.57%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB DIMM SDRAM 2048MT/s        | 1         | 3.57%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s       | 1         | 3.57%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s         | 1         | 3.57%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 3.57%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 3.57%   |
| SK hynix RAM HMT125S6TFR8C-H9 2048MB SODIMM DDR3 1334MT/s    | 1         | 3.57%   |
| SK hynix RAM HMA425S6AFR6N-TF 2GB SODIMM DDR4 1866MT/s       | 1         | 3.57%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                  | 1         | 3.57%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 3.57%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s     | 1         | 3.57%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s        | 1         | 3.57%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s       | 1         | 3.57%   |
| HMD RAM HMDN304GU648D1B9C 4GB SODIMM DDR3 1333MT/s           | 1         | 3.57%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s       | 1         | 3.57%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s        | 1         | 3.57%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3200MT/s        | 1         | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 11        | 57.89%  |
| DDR4    | 3         | 15.79%  |
| DDR2    | 2         | 10.53%  |
| SDRAM   | 1         | 5.26%   |
| LPDDR3  | 1         | 5.26%   |
| Unknown | 1         | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 12        | 63.16%  |
| DIMM         | 6         | 31.58%  |
| Row Of Chips | 1         | 5.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 11        | 47.83%  |
| 2048  | 7         | 30.43%  |
| 8192  | 3         | 13.04%  |
| 16384 | 1         | 4.35%   |
| 1024  | 1         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 9         | 37.5%   |
| 1333  | 4         | 16.67%  |
| 3200  | 2         | 8.33%   |
| 667   | 2         | 8.33%   |
| 2400  | 1         | 4.17%   |
| 2048  | 1         | 4.17%   |
| 1867  | 1         | 4.17%   |
| 1866  | 1         | 4.17%   |
| 1639  | 1         | 4.17%   |
| 1334  | 1         | 4.17%   |
| 800   | 1         | 4.17%   |

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

| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 3         | 21.43%  |
| Realtek Semiconductor                  | 2         | 14.29%  |
| Apple                                  | 2         | 14.29%  |
| Suyin                                  | 1         | 7.14%   |
| Sunplus Innovation Technology          | 1         | 7.14%   |
| Ricoh                                  | 1         | 7.14%   |
| Microdia                               | 1         | 7.14%   |
| IMC Networks                           | 1         | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 7.14%   |
| Acer                                   | 1         | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek USB Camera                                  | 2         | 13.33%  |
| Suyin HP TrueVision HD                              | 1         | 6.67%   |
| Sunplus Asus Webcam                                 | 1         | 6.67%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 6.67%   |
| Microdia HP Webcam-50                               | 1         | 6.67%   |
| IMC Networks EasyCamera                             | 1         | 6.67%   |
| Chicony HP Truevision HD                            | 1         | 6.67%   |
| Chicony HD WebCam                                   | 1         | 6.67%   |
| Chicony 5MP World Facing                            | 1         | 6.67%   |
| Chicony 2.0M UVC Webcam / CNF7129                   | 1         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 6.67%   |
| Apple FaceTime HD Camera (Built-in)                 | 1         | 6.67%   |
| Apple FaceTime HD Camera                            | 1         | 6.67%   |
| Acer BisonCam, NB Pro                               | 1         | 6.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 1         | 33.33%  |
| Upek               | 1         | 33.33%  |
| STMicroelectronics | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 33.33%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 33.33%  |
| STMicroelectronics Fingerprint Reader                  | 1         | 33.33%  |

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
| 0     | 23        | 82.14%  |
| 1     | 5         | 17.86%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 3         | 60%     |
| Net/ethernet       | 1         | 20%     |
| Graphics card      | 1         | 20%     |

