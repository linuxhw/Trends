BlackPanther - Hardware Trends
------------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/BlackPanther/Desktop/README.md) and [notebooks](/Dist/BlackPanther/Notebook/README.md).

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

![OS](./images/pie_chart/os_name.svg)

![OS](./images/line_chart/os_name.svg)

| Name              | Computers | Percent |
|-------------------|-----------|---------|
| BlackPanther 18.1 | 39        | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| BlackPanther | 39        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.6.14-desktop-2bP  | 25        | 64.1%   |
| 4.18.16-desktop-1bP | 14        | 35.9%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.6.14  | 25        | 64.1%   |
| 4.18.16 | 14        | 35.9%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.6     | 25        | 64.1%   |
| 4.18    | 14        | 35.9%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 39        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| KDE5 | 39        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 39        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| SDDM | 39        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 39        | 100%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 24        | 61.54%  |
| EFI  | 15        | 38.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Overlay | 34        | 87.18%  |
| Ext4    | 4         | 10.26%  |
| Xfs     | 1         | 2.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 23        | 58.97%  |
| MBR  | 16        | 41.03%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 51.28%  |
| No        | 19        | 48.72%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 20        | 51.28%  |
| Yes       | 19        | 48.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 23.08%  |
| Dell                | 8         | 20.51%  |
| Gigabyte Technology | 5         | 12.82%  |
| ASUSTek Computer    | 4         | 10.26%  |
| Acer                | 3         | 7.69%   |
| Lenovo              | 2         | 5.13%   |
| ZOTAC               | 1         | 2.56%   |
| Toshiba             | 1         | 2.56%   |
| MSI                 | 1         | 2.56%   |
| Intel               | 1         | 2.56%   |
| GIADA               | 1         | 2.56%   |
| Fujitsu             | 1         | 2.56%   |
| eMachines           | 1         | 2.56%   |
| Apple               | 1         | 2.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| HP 250 G1                           | 2         | 5.13%   |
| ZOTAC ZBOXNANO-AD12                 | 1         | 2.56%   |
| Toshiba Satellite C660              | 1         | 2.56%   |
| MSI MS-7817                         | 1         | 2.56%   |
| Lenovo Z710 20250                   | 1         | 2.56%   |
| Lenovo 7052-A9G                     | 1         | 2.56%   |
| Intel DN2820FYK H24582-203          | 1         | 2.56%   |
| HP ProBook 650 G2                   | 1         | 2.56%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 1         | 2.56%   |
| HP Pavilion dv5                     | 1         | 2.56%   |
| HP Laptop 17-ak0xx                  | 1         | 2.56%   |
| HP Laptop 15-dw1xxx                 | 1         | 2.56%   |
| HP Compaq 6910p                     | 1         | 2.56%   |
| Gigabyte Z390 UD                    | 1         | 2.56%   |
| Gigabyte H61M-S2PV                  | 1         | 2.56%   |
| Gigabyte H61M-S1                    | 1         | 2.56%   |
| Gigabyte B450M GAMING               | 1         | 2.56%   |
| Gigabyte AB350M-DS3H V2             | 1         | 2.56%   |
| GIADA SHARKBAY                      | 1         | 2.56%   |
| Fujitsu LIFEBOOK U745               | 1         | 2.56%   |
| eMachines E725                      | 1         | 2.56%   |
| Dell Precision WorkStation T5500    | 1         | 2.56%   |
| Dell Precision Tower 5810           | 1         | 2.56%   |
| Dell OptiPlex GX520                 | 1         | 2.56%   |
| Dell OptiPlex 390                   | 1         | 2.56%   |
| Dell Latitude E6230                 | 1         | 2.56%   |
| Dell Latitude D630                  | 1         | 2.56%   |
| Dell Inspiron 7737                  | 1         | 2.56%   |
| Dell Inspiron 5558                  | 1         | 2.56%   |
| ASUS PRIME B365M-A                  | 1         | 2.56%   |
| ASUS P8H61-M LX2                    | 1         | 2.56%   |
| ASUS K52F                           | 1         | 2.56%   |
| ASUS All Series                     | 1         | 2.56%   |
| Apple MacBookAir5,2                 | 1         | 2.56%   |
| Acer TravelMate 8571                | 1         | 2.56%   |
| Acer Nitro AN515-51                 | 1         | 2.56%   |
| Acer Aspire A315-21G                | 1         | 2.56%   |
| Unknown                             | 1         | 2.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| HP Pavilion          | 2         | 5.13%   |
| HP Laptop            | 2         | 5.13%   |
| HP 250               | 2         | 5.13%   |
| Dell Precision       | 2         | 5.13%   |
| Dell OptiPlex        | 2         | 5.13%   |
| Dell Latitude        | 2         | 5.13%   |
| Dell Inspiron        | 2         | 5.13%   |
| ZOTAC ZBOXNANO-AD12  | 1         | 2.56%   |
| Toshiba Satellite    | 1         | 2.56%   |
| MSI MS-7817          | 1         | 2.56%   |
| Lenovo Z710          | 1         | 2.56%   |
| Lenovo 7052-A9G      | 1         | 2.56%   |
| Intel DN2820FYK      | 1         | 2.56%   |
| HP ProBook           | 1         | 2.56%   |
| HP Compaq            | 1         | 2.56%   |
| Gigabyte Z390        | 1         | 2.56%   |
| Gigabyte H61M-S2PV   | 1         | 2.56%   |
| Gigabyte H61M-S1     | 1         | 2.56%   |
| Gigabyte B450M       | 1         | 2.56%   |
| Gigabyte AB350M-DS3H | 1         | 2.56%   |
| GIADA SHARKBAY       | 1         | 2.56%   |
| Fujitsu LIFEBOOK     | 1         | 2.56%   |
| eMachines E725       | 1         | 2.56%   |
| ASUS PRIME           | 1         | 2.56%   |
| ASUS P8H61-M         | 1         | 2.56%   |
| ASUS K52F            | 1         | 2.56%   |
| ASUS All             | 1         | 2.56%   |
| Apple MacBookAir5    | 1         | 2.56%   |
| Acer TravelMate      | 1         | 2.56%   |
| Acer Nitro           | 1         | 2.56%   |
| Acer Aspire          | 1         | 2.56%   |
| Unknown              | 1         | 2.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2014 | 6         | 15.38%  |
| 2012 | 5         | 12.82%  |
| 2013 | 4         | 10.26%  |
| 2018 | 3         | 7.69%   |
| 2017 | 3         | 7.69%   |
| 2009 | 3         | 7.69%   |
| 2019 | 2         | 5.13%   |
| 2015 | 2         | 5.13%   |
| 2011 | 2         | 5.13%   |
| 2010 | 2         | 5.13%   |
| 2008 | 2         | 5.13%   |
| 2007 | 2         | 5.13%   |
| 2020 | 1         | 2.56%   |
| 2016 | 1         | 2.56%   |
| 2006 | 1         | 2.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 22        | 56.41%  |
| Desktop  | 16        | 41.03%  |
| Mini pc  | 1         | 2.56%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 39        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 39        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 13        | 33.33%  |
| 8.01-16.0  | 13        | 33.33%  |
| 4.01-8.0   | 5         | 12.82%  |
| 1.01-2.0   | 5         | 12.82%  |
| 16.01-24.0 | 2         | 5.13%   |
| 32.01-64.0 | 1         | 2.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 18        | 46.15%  |
| 1.01-2.0 | 12        | 30.77%  |
| 0.01-0.5 | 9         | 23.08%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 28        | 71.79%  |
| 2      | 9         | 23.08%  |
| 4      | 1         | 2.56%   |
| 3      | 1         | 2.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 61.54%  |
| No        | 15        | 38.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 97.44%  |
| No        | 1         | 2.56%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 74.36%  |
| No        | 10        | 25.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 56.41%  |
| No        | 17        | 43.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country   | Computers | Percent |
|-----------|-----------|---------|
| Hungary   | 35        | 89.74%  |
| Slovakia  | 1         | 2.56%   |
| Germany   | 1         | 2.56%   |
| Canada    | 1         | 2.56%   |
| Australia | 1         | 2.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Budapest                | 3         | 7.69%   |
| Zalaegerszeg            | 2         | 5.13%   |
| Szolnok                 | 2         | 5.13%   |
| Szajol                  | 2         | 5.13%   |
| Nyiregyhaza             | 2         | 5.13%   |
| Kecskemét              | 2         | 5.13%   |
| Fertoszentmiklos        | 2         | 5.13%   |
| Veroce                  | 1         | 2.56%   |
| Vamospercs              | 1         | 2.56%   |
| Tatabánya              | 1         | 2.56%   |
| Szombathely             | 1         | 2.56%   |
| Szekszárd              | 1         | 2.56%   |
| Rackeve                 | 1         | 2.56%   |
| Pfaffenhofen an der Ilm | 1         | 2.56%   |
| Peteri                  | 1         | 2.56%   |
| Oroshaza                | 1         | 2.56%   |
| Melbourne               | 1         | 2.56%   |
| Lieskovec               | 1         | 2.56%   |
| Kisvarda                | 1         | 2.56%   |
| Kiskunhalas             | 1         | 2.56%   |
| Hodmezovasarhely        | 1         | 2.56%   |
| Győr                   | 1         | 2.56%   |
| Gyongyos                | 1         | 2.56%   |
| Ercsi                   | 1         | 2.56%   |
| Dorog                   | 1         | 2.56%   |
| Debrecen                | 1         | 2.56%   |
| Csongrad                | 1         | 2.56%   |
| Csevharaszt             | 1         | 2.56%   |
| Bikal                   | 1         | 2.56%   |
| Barrie                  | 1         | 2.56%   |
| Adony                   | 1         | 2.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 11        | 12     | 20.75%  |
| WDC                 | 8         | 8      | 15.09%  |
| Samsung Electronics | 6         | 6      | 11.32%  |
| Toshiba             | 5         | 5      | 9.43%   |
| HGST                | 4         | 5      | 7.55%   |
| Seagate             | 2         | 3      | 3.77%   |
| Intenso             | 2         | 2      | 3.77%   |
| Gigabyte Technology | 2         | 2      | 3.77%   |
| Zheino              | 1         | 1      | 1.89%   |
| Timetec             | 1         | 1      | 1.89%   |
| SPCC                | 1         | 1      | 1.89%   |
| SanDisk             | 1         | 1      | 1.89%   |
| Patriot             | 1         | 1      | 1.89%   |
| KIOXIA              | 1         | 1      | 1.89%   |
| Kingmax             | 1         | 1      | 1.89%   |
| Intel               | 1         | 1      | 1.89%   |
| Fujitsu             | 1         | 1      | 1.89%   |
| Crucial             | 1         | 1      | 1.89%   |
| Apple               | 1         | 1      | 1.89%   |
| Apacer              | 1         | 1      | 1.89%   |
| A-DATA Technology   | 1         | 1      | 1.89%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 3         | 5.45%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 3.64%   |
| HGST HTS545032A7E380 320GB           | 2         | 3.64%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD | 2         | 3.64%   |
| Zheino CHN-NGFFNV2280-256 256GB      | 1         | 1.82%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 1.82%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 1         | 1.82%   |
| WDC WD5000AAKS-007AA0 500GB          | 1         | 1.82%   |
| WDC WD2502ABYS-02B7A0 256GB          | 1         | 1.82%   |
| WDC WD1200BEVS-75UST0 120GB          | 1         | 1.82%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 1.82%   |
| WDC WD10JPLX-00MBPT0 1TB             | 1         | 1.82%   |
| WDC WD10EZEX-00KUWA0 1TB             | 1         | 1.82%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1.82%   |
| Toshiba MQ01ABD100 1TB               | 1         | 1.82%   |
| Toshiba MK8009GAH 80GB               | 1         | 1.82%   |
| Toshiba MK5065GSX 500GB              | 1         | 1.82%   |
| Toshiba DT01ACA100 1TB               | 1         | 1.82%   |
| Timetec SD08 512GB                   | 1         | 1.82%   |
| SPCC Solid State Disk 128GB          | 1         | 1.82%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1.82%   |
| Seagate ST2000LM015-2E8174 2TB       | 1         | 1.82%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1.82%   |
| SanDisk SDSSDH3512G 512GB            | 1         | 1.82%   |
| Samsung SSD 980 500GB                | 1         | 1.82%   |
| Samsung SSD 960 EVO 500GB            | 1         | 1.82%   |
| Samsung SSD 830 Series 128GB         | 1         | 1.82%   |
| Samsung SSD 750 EVO 250GB            | 1         | 1.82%   |
| Samsung MZ7LN256HCHP-00000 256GB SSD | 1         | 1.82%   |
| Samsung HD200HJ 200GB                | 1         | 1.82%   |
| Patriot Burst 120GB SSD              | 1         | 1.82%   |
| KIOXIA KXG60ZNV256G 256GB            | 1         | 1.82%   |
| Kingston SV300S37A60G 64GB SSD       | 1         | 1.82%   |
| Kingston SV300S37A120G 120GB SSD     | 1         | 1.82%   |
| Kingston SS200S330G 32GB SSD         | 1         | 1.82%   |
| Kingston SMS200S3120G 120GB SSD      | 1         | 1.82%   |
| Kingston SA400S37960G 960GB SSD      | 1         | 1.82%   |
| Kingston SA400S37120G 120GB SSD      | 1         | 1.82%   |
| Kingston SA2000M8250G 250GB          | 1         | 1.82%   |
| Kingmax SSD 480GB                    | 1         | 1.82%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 35%     |
| Toshiba             | 5         | 5      | 25%     |
| HGST                | 4         | 5      | 20%     |
| Seagate             | 2         | 3      | 10%     |
| Samsung Electronics | 1         | 1      | 5%      |
| Fujitsu             | 1         | 1      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 10        | 11     | 38.46%  |
| Samsung Electronics | 3         | 3      | 11.54%  |
| Intenso             | 2         | 2      | 7.69%   |
| Gigabyte Technology | 2         | 2      | 7.69%   |
| WDC                 | 1         | 1      | 3.85%   |
| Timetec             | 1         | 1      | 3.85%   |
| SPCC                | 1         | 1      | 3.85%   |
| SanDisk             | 1         | 1      | 3.85%   |
| Patriot             | 1         | 1      | 3.85%   |
| Kingmax             | 1         | 1      | 3.85%   |
| Crucial             | 1         | 1      | 3.85%   |
| Apple               | 1         | 1      | 3.85%   |
| A-DATA Technology   | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 25        | 27     | 49.02%  |
| HDD  | 20        | 22     | 39.22%  |
| NVMe | 6         | 7      | 11.76%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 38        | 48     | 84.44%  |
| NVMe | 6         | 7      | 13.33%  |
| SAS  | 1         | 1      | 2.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 36     | 75%     |
| 0.51-1.0   | 9         | 10     | 20.45%  |
| 3.01-4.0   | 1         | 2      | 2.27%   |
| 1.01-2.0   | 1         | 1      | 2.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 92.31%  |
| 101-250    | 3         | 7.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB | Computers | Percent |
|---------|-----------|---------|
| Unknown | 36        | 92.31%  |
| 1-20    | 3         | 7.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS545032A7E380 320GB            | 2         | 2      | 20%     |
| WDC WD5000AAKS-007AA0 500GB           | 1         | 1      | 10%     |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 10%     |
| Toshiba MK8009GAH 80GB                | 1         | 1      | 10%     |
| Toshiba MK5065GSX 500GB               | 1         | 1      | 10%     |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 10%     |
| Samsung Electronics SSD 750 EVO 250GB | 1         | 1      | 10%     |
| Samsung Electronics HD200HJ 200GB     | 1         | 1      | 10%     |
| Apple SSD TS064E 64GB                 | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 3         | 3      | 30%     |
| Samsung Electronics | 2         | 2      | 20%     |
| HGST                | 2         | 2      | 20%     |
| WDC                 | 1         | 1      | 10%     |
| Seagate             | 1         | 1      | 10%     |
| Apple               | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 3         | 3      | 37.5%   |
| HGST                | 2         | 2      | 25%     |
| WDC                 | 1         | 1      | 12.5%   |
| Seagate             | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 8      | 80%     |
| SSD  | 2         | 2      | 20%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)

![Failed Drives](./images/line_chart/drive_failed.svg)

| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Intel SSDPEKKW256G7 256GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)

![Failed Drive Vendor](./images/line_chart/drive_failed_vendor.svg)

| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| Intel  | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)

![Drive Status](./images/line_chart/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 31        | 44     | 72.09%  |
| Malfunc  | 10        | 10     | 23.26%  |
| Detected | 1         | 1      | 2.33%   |
| Failed   | 1         | 1      | 2.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 31        | 68.89%  |
| AMD                          | 8         | 17.78%  |
| Samsung Electronics          | 2         | 4.44%   |
| Toshiba America Info Systems | 1         | 2.22%   |
| Silicon Motion               | 1         | 2.22%   |
| Phison Electronics           | 1         | 2.22%   |
| Kingston Technology Company  | 1         | 2.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 5         | 8.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 6.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 6.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 5.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3         | 5.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 3.39%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                             | 2         | 3.39%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 3.39%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 2         | 3.39%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 3.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 3.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2         | 3.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 3.39%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 1.69%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 1.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 1.69%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 1.69%   |
| Phison Electronics Non-Volatile memory controller                                       | 1         | 1.69%   |
| Kingston Company A2000 NVMe SSD                                                         | 1         | 1.69%   |
| Intel SSD 600P Series                                                                   | 1         | 1.69%   |
| Intel SATA Controller [RAID mode]                                                       | 1         | 1.69%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1         | 1.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 1.69%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1         | 1.69%   |
| Intel C610/X99 series chipset IDE-r Controller                                          | 1         | 1.69%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1         | 1.69%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 1.69%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 1.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1         | 1.69%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1         | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1         | 1.69%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1         | 1.69%   |
| AMD FCH IDE Controller                                                                  | 1         | 1.69%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1         | 1.69%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1         | 1.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 28        | 57.14%  |
| IDE  | 11        | 22.45%  |
| NVMe | 6         | 12.24%  |
| RAID | 4         | 8.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 31        | 79.49%  |
| AMD    | 8         | 20.51%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Celeron CPU 1000M @ 1.80GHz            | 2         | 5.13%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics  | 2         | 5.13%   |
| Intel Xeon CPU E5530 @ 2.40GHz               | 1         | 2.56%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz          | 1         | 2.56%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz  | 1         | 2.56%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz  | 1         | 2.56%   |
| Intel Pentium CPU P6100 @ 2.00GHz            | 1         | 2.56%   |
| Intel Pentium CPU G620 @ 2.60GHz             | 1         | 2.56%   |
| Intel Pentium 4 CPU 3.20GHz                  | 1         | 2.56%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz           | 1         | 2.56%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz           | 1         | 2.56%   |
| Intel Core i7-5600U CPU @ 2.60GHz            | 1         | 2.56%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz           | 1         | 2.56%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 1         | 2.56%   |
| Intel Core i5-9400 CPU @ 2.90GHz             | 1         | 2.56%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 1         | 2.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz             | 1         | 2.56%   |
| Intel Core i5-3427U CPU @ 1.80GHz            | 1         | 2.56%   |
| Intel Core i5-3340M CPU @ 2.70GHz            | 1         | 2.56%   |
| Intel Core i5-2400 CPU @ 3.10GHz             | 1         | 2.56%   |
| Intel Core i3-8100 CPU @ 3.60GHz             | 1         | 2.56%   |
| Intel Core i3-4130 CPU @ 3.40GHz             | 1         | 2.56%   |
| Intel Core i3-4010U CPU @ 1.70GHz            | 1         | 2.56%   |
| Intel Core i3-3220 CPU @ 3.30GHz             | 1         | 2.56%   |
| Intel Core i3-2120 CPU @ 3.30GHz             | 1         | 2.56%   |
| Intel Core i3-10110U CPU @ 2.10GHz           | 1         | 2.56%   |
| Intel Core 2 Duo CPU U9400 @ 1.40GHz         | 1         | 2.56%   |
| Intel Core 2 Duo CPU U7600 @ 1.20GHz         | 1         | 2.56%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz         | 1         | 2.56%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz         | 1         | 2.56%   |
| Intel Celeron CPU N2830 @ 2.16GHz            | 1         | 2.56%   |
| AMD Sempron 3850 APU with Radeon R3          | 1         | 2.56%   |
| AMD Ryzen 5 4600H with Radeon Graphics       | 1         | 2.56%   |
| AMD E2-1800 APU with Radeon HD Graphics      | 1         | 2.56%   |
| AMD Athlon X2 Dual-Core QL-62                | 1         | 2.56%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 2.56%   |
| AMD A4-9120 RADEON R3, 4 COMPUTE CORES 2C+2G | 1         | 2.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 6         | 15.38%  |
| Intel Core i3           | 6         | 15.38%  |
| Intel Core i7           | 5         | 12.82%  |
| Intel Core 2 Duo        | 4         | 10.26%  |
| Intel Celeron           | 3         | 7.69%   |
| AMD Ryzen 5             | 3         | 7.69%   |
| Intel Xeon              | 2         | 5.13%   |
| Intel Pentium Dual-Core | 2         | 5.13%   |
| Intel Pentium           | 2         | 5.13%   |
| Other                   | 1         | 2.56%   |
| Intel Pentium 4         | 1         | 2.56%   |
| AMD Sempron             | 1         | 2.56%   |
| AMD E2                  | 1         | 2.56%   |
| AMD Athlon X2           | 1         | 2.56%   |
| AMD A4                  | 1         | 2.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 25        | 64.1%   |
| 4      | 11        | 28.21%  |
| 6      | 2         | 5.13%   |
| 1      | 1         | 2.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 39        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 53.85%  |
| 2      | 18        | 46.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 39        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 6         | 15.38%  |
| 0x206a7    | 3         | 7.69%   |
| 0x1067a    | 3         | 7.69%   |
| 0x6fd      | 2         | 5.13%   |
| 0x40651    | 2         | 5.13%   |
| 0x306d4    | 2         | 5.13%   |
| 0x306c3    | 2         | 5.13%   |
| 0x08108109 | 2         | 5.13%   |
| 0xf43      | 1         | 2.56%   |
| 0x906eb    | 1         | 2.56%   |
| 0x906ea    | 1         | 2.56%   |
| 0x906e9    | 1         | 2.56%   |
| 0x806ec    | 1         | 2.56%   |
| 0x506e3    | 1         | 2.56%   |
| 0x306f2    | 1         | 2.56%   |
| 0x30678    | 1         | 2.56%   |
| 0x20655    | 1         | 2.56%   |
| 0x106a5    | 1         | 2.56%   |
| 0x10676    | 1         | 2.56%   |
| 0x08600106 | 1         | 2.56%   |
| 0x0700010f | 1         | 2.56%   |
| 0x06006705 | 1         | 2.56%   |
| 0x06006704 | 1         | 2.56%   |
| 0x05000119 | 1         | 2.56%   |
| 0x02000032 | 1         | 2.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name            | Computers | Percent |
|-----------------|-----------|---------|
| IvyBridge       | 6         | 15.38%  |
| Haswell         | 5         | 12.82%  |
| Penryn          | 4         | 10.26%  |
| KabyLake        | 4         | 10.26%  |
| SandyBridge     | 3         | 7.69%   |
| Zen+            | 2         | 5.13%   |
| Excavator       | 2         | 5.13%   |
| Core            | 2         | 5.13%   |
| Broadwell       | 2         | 5.13%   |
| Zen 2           | 1         | 2.56%   |
| Westmere        | 1         | 2.56%   |
| Skylake         | 1         | 2.56%   |
| Silvermont      | 1         | 2.56%   |
| NetBurst        | 1         | 2.56%   |
| Nehalem         | 1         | 2.56%   |
| K8 & K10 hybrid | 1         | 2.56%   |
| Jaguar          | 1         | 2.56%   |
| Bobcat          | 1         | 2.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 24        | 54.55%  |
| Nvidia | 10        | 22.73%  |
| AMD    | 10        | 22.73%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 8.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 3         | 6.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 3         | 6.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 6.25%   |
| Intel HD Graphics 5500                                                    | 2         | 4.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 4.17%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 2         | 4.17%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 2.08%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 2.08%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 2.08%   |
| Nvidia GK208B [GeForce GT 720]                                            | 1         | 2.08%   |
| Nvidia GK107M [GeForce GT 750M]                                           | 1         | 2.08%   |
| Nvidia GK107M [GeForce GT 745M]                                           | 1         | 2.08%   |
| Nvidia GF108 [GeForce GT 630]                                             | 1         | 2.08%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                         | 1         | 2.08%   |
| Nvidia G96CGL [Quadro FX 580]                                             | 1         | 2.08%   |
| Nvidia G80 [GeForce 8800 GTS]                                             | 1         | 2.08%   |
| Intel HD Graphics 630                                                     | 1         | 2.08%   |
| Intel HD Graphics 530                                                     | 1         | 2.08%   |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 2.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 2.08%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1         | 2.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 2.08%   |
| Intel 82945G/GZ Integrated Graphics Controller                            | 1         | 2.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 2.08%   |
| AMD Wrestler [Radeon HD 7340]                                             | 1         | 2.08%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                              | 1         | 2.08%   |
| AMD Renoir                                                                | 1         | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 2.08%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                            | 1         | 2.08%   |
| AMD Kabini [Radeon HD 8280 / R3 Series]                                   | 1         | 2.08%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]          | 1         | 2.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 1         | 2.08%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                            | 1         | 2.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 20        | 51.28%  |
| 1 x AMD        | 8         | 20.51%  |
| 1 x Nvidia     | 5         | 12.82%  |
| Intel + Nvidia | 4         | 10.26%  |
| 2 x AMD        | 1         | 2.56%   |
| AMD + Nvidia   | 1         | 2.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 38        | 97.44%  |
| Unknown | 1         | 2.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 53.85%  |
| 0.01-0.5   | 7         | 17.95%  |
| 1.01-2.0   | 4         | 10.26%  |
| 0.51-1.0   | 4         | 10.26%  |
| 3.01-4.0   | 3         | 7.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 8         | 21.62%  |
| LG Display              | 7         | 18.92%  |
| AU Optronics            | 6         | 16.22%  |
| Goldstar                | 3         | 8.11%   |
| Medion                  | 2         | 5.41%   |
| Chimei Innolux          | 2         | 5.41%   |
| Chi Mei Optoelectronics | 2         | 5.41%   |
| PANDA                   | 1         | 2.7%    |
| Mi                      | 1         | 2.7%    |
| Lenovo                  | 1         | 2.7%    |
| HIC                     | 1         | 2.7%    |
| CVT                     | 1         | 2.7%    |
| Apple                   | 1         | 2.7%    |
| Ancor Communications    | 1         | 2.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 5.41%   |
| Samsung Electronics SyncMaster SAM0192 1280x1024 338x270mm 17.0-inch     | 1         | 2.7%    |
| Samsung Electronics S27E500 SAM0D0D 1920x1080 598x336mm 27.0-inch        | 1         | 2.7%    |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch        | 1         | 2.7%    |
| Samsung Electronics S24A31x SAM7114 1920x1080 527x296mm 23.8-inch        | 1         | 2.7%    |
| Samsung Electronics LS27AG30x SAM717A 1920x1080 597x336mm 27.0-inch      | 1         | 2.7%    |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 1         | 2.7%    |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch     | 1         | 2.7%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 1         | 2.7%    |
| PANDA LCD Monitor NCP0058 1920x1080 344x194mm 15.5-inch                  | 1         | 2.7%    |
| Mi 27 NFGL XMIB004 1920x1080 598x336mm 27.0-inch                         | 1         | 2.7%    |
| Medion MD20666 MED3674 1920x1080 533x312mm 24.3-inch                     | 1         | 2.7%    |
| Medion MD20666 MED3672 1920x1080 533x312mm 24.3-inch                     | 1         | 2.7%    |
| LG Display LCD Monitor LGD06F5 1920x1080 344x194mm 15.5-inch             | 1         | 2.7%    |
| LG Display LCD Monitor LGD036C 1366x768 277x156mm 12.5-inch              | 1         | 2.7%    |
| LG Display LCD Monitor LGD0365 1600x900 382x215mm 17.3-inch              | 1         | 2.7%    |
| LG Display LCD Monitor LGD0348 1920x1080 383x215mm 17.3-inch             | 1         | 2.7%    |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch              | 1         | 2.7%    |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                    | 1         | 2.7%    |
| HIC LCD Monitor HIC0001 1920x1080 256x192mm 12.6-inch                    | 1         | 2.7%    |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                      | 1         | 2.7%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 1         | 2.7%    |
| Goldstar E2260 GSM57E1 1920x1080 477x268mm 21.5-inch                     | 1         | 2.7%    |
| CVT CVTE TV CVT0003 1920x1080 575x323mm 26.0-inch                        | 1         | 2.7%    |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 1         | 2.7%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 1         | 2.7%    |
| Chi Mei Optoelectronics LCD Monitor CMO1424 1280x800 303x190mm 14.1-inch | 1         | 2.7%    |
| Chi Mei Optoelectronics LCD Monitor CMO1221 1280x800 261x163mm 12.1-inch | 1         | 2.7%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.7%    |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 1         | 2.7%    |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.7%    |
| AU Optronics LCD Monitor AUO32EC 1366x768 344x193mm 15.5-inch            | 1         | 2.7%    |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch            | 1         | 2.7%    |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 1         | 2.7%    |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 1         | 2.7%    |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch    | 1         | 2.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 16        | 44.44%  |
| 1366x768 (WXGA)    | 10        | 27.78%  |
| 1600x900 (HD+)     | 2         | 5.56%   |
| 1440x900 (WXGA+)   | 2         | 5.56%   |
| 1280x800 (WXGA)    | 2         | 5.56%   |
| 1280x1024 (SXGA)   | 2         | 5.56%   |
| 3840x2160 (4K)     | 1         | 2.78%   |
| 1680x1050 (WSXGA+) | 1         | 2.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 12        | 32.43%  |
| 17     | 5         | 13.51%  |
| 27     | 3         | 8.11%   |
| 24     | 3         | 8.11%   |
| 21     | 3         | 8.11%   |
| 12     | 3         | 8.11%   |
| 23     | 2         | 5.41%   |
| 14     | 2         | 5.41%   |
| 13     | 2         | 5.41%   |
| 26     | 1         | 2.7%    |
| 22     | 1         | 2.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 45.95%  |
| 501-600     | 9         | 24.32%  |
| 401-500     | 4         | 10.81%  |
| 201-300     | 4         | 10.81%  |
| 351-400     | 3         | 8.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 27        | 77.14%  |
| 16/10 | 5         | 14.29%  |
| 5/4   | 2         | 5.71%   |
| 4/3   | 1         | 2.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 32.43%  |
| 201-250        | 7         | 18.92%  |
| 81-90          | 4         | 10.81%  |
| 301-350        | 3         | 8.11%   |
| 251-300        | 3         | 8.11%   |
| 121-130        | 3         | 8.11%   |
| 61-70          | 2         | 5.41%   |
| 141-150        | 2         | 5.41%   |
| 71-80          | 1         | 2.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 14        | 38.89%  |
| 51-100  | 13        | 36.11%  |
| 121-160 | 8         | 22.22%  |
| 161-240 | 1         | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 36        | 92.31%  |
| 2     | 2         | 5.13%   |
| 0     | 1         | 2.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 24        | 41.38%  |
| Intel                 | 14        | 24.14%  |
| Qualcomm Atheros      | 6         | 10.34%  |
| Ralink                | 5         | 8.62%   |
| Broadcom              | 4         | 6.9%    |
| Xiaomi                | 1         | 1.72%   |
| TP-Link               | 1         | 1.72%   |
| Ralink Technology     | 1         | 1.72%   |
| JMicron Technology    | 1         | 1.72%   |
| Broadcom Limited      | 1         | 1.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 22        | 32.35%  |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 4.41%   |
| Intel Wireless 7260                                                     | 3         | 4.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 2         | 2.94%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 2         | 2.94%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 2.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 2.94%   |
| Intel 82566MM Gigabit Network Connection                                | 2         | 2.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 1.47%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 1.47%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.47%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 1.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 1.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 1.47%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.47%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 1.47%   |
| Intel Wireless 8260                                                     | 1         | 1.47%   |
| Intel Wireless 7265                                                     | 1         | 1.47%   |
| Intel Wireless 3160                                                     | 1         | 1.47%   |
| Intel WiFi Link 5100                                                    | 1         | 1.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.47%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.47%   |
| Intel Ethernet Connection I217-LM                                       | 1         | 1.47%   |
| Intel Ethernet Connection (3) I218-LM                                   | 1         | 1.47%   |
| Intel Ethernet Connection (2) I219-LM                                   | 1         | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.47%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                        | 1         | 1.47%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                | 1         | 1.47%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                 | 1         | 1.47%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 1.47%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 1.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 11        | 37.93%  |
| Realtek Semiconductor | 5         | 17.24%  |
| Ralink                | 5         | 17.24%  |
| Qualcomm Atheros      | 4         | 13.79%  |
| TP-Link               | 1         | 3.45%   |
| Ralink Technology     | 1         | 3.45%   |
| Broadcom Limited      | 1         | 3.45%   |
| Broadcom              | 1         | 3.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 10.34%  |
| Intel Wireless 7260                                                     | 3         | 10.34%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 6.9%    |
| Ralink RT2561/RT61 802.11g PCI                                          | 2         | 6.9%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 6.9%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 3.45%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 3.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 3.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 3.45%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 3.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 3.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 3.45%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 3.45%   |
| Intel Wireless 8260                                                     | 1         | 3.45%   |
| Intel Wireless 7265                                                     | 1         | 3.45%   |
| Intel Wireless 3160                                                     | 1         | 3.45%   |
| Intel WiFi Link 5100                                                    | 1         | 3.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 3.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 3.45%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 3.45%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 24        | 61.54%  |
| Intel                 | 8         | 20.51%  |
| Broadcom              | 3         | 7.69%   |
| Qualcomm Atheros      | 2         | 5.13%   |
| Xiaomi                | 1         | 2.56%   |
| JMicron Technology    | 1         | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 56.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 5.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.13%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 5.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.56%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.56%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.56%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 2.56%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 2.56%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1         | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 38        | 56.72%  |
| WiFi     | 29        | 43.28%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 20        | 54.05%  |
| WiFi     | 17        | 45.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 25        | 64.1%   |
| 1     | 14        | 35.9%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 27        | 69.23%  |
| Yes  | 12        | 30.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 6         | 27.27%  |
| Realtek Semiconductor   | 3         | 13.64%  |
| Ralink                  | 3         | 13.64%  |
| Lite-On Technology      | 2         | 9.09%   |
| Hewlett-Packard         | 2         | 9.09%   |
| Cambridge Silicon Radio | 2         | 9.09%   |
| Logitech                | 1         | 4.55%   |
| Foxconn / Hon Hai       | 1         | 4.55%   |
| Dell                    | 1         | 4.55%   |
| Apple                   | 1         | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 27.27%  |
| Ralink RT3290 Bluetooth                             | 3         | 13.64%  |
| Realtek Bluetooth Radio                             | 2         | 9.09%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 9.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 9.09%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 4.55%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1         | 4.55%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 4.55%   |
| Lite-On Bluetooth Device                            | 1         | 4.55%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 4.55%   |
| Dell Wireless 360 Bluetooth                         | 1         | 4.55%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 31        | 64.58%  |
| AMD           | 10        | 20.83%  |
| Nvidia        | 6         | 12.5%   |
| Creative Labs | 1         | 2.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                                           | Computers | Percent |
|-------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 5         | 8.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 4         | 6.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 3         | 5%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                  | 3         | 5%      |
| AMD Family 17h/19h HD Audio Controller                                                          | 3         | 5%      |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 2         | 3.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                         | 2         | 3.33%   |
| Intel Haswell-ULT HD Audio Controller                                                           | 2         | 3.33%   |
| Intel Broadwell-U Audio Controller                                                              | 2         | 3.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 2         | 3.33%   |
| Intel 8 Series HD Audio Controller                                                              | 2         | 3.33%   |
| AMD High Definition Audio Controller                                                            | 2         | 3.33%   |
| AMD FCH Azalia Controller                                                                       | 2         | 3.33%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                | 2         | 3.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                  | 1         | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 1         | 1.67%   |
| Nvidia GF108 High Definition Audio Controller                                                   | 1         | 1.67%   |
| Nvidia GA104 High Definition Audio Controller                                                   | 1         | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 1         | 1.67%   |
| Intel Comet Lake PCH-LP cAVS                                                                    | 1         | 1.67%   |
| Intel CM238 HD Audio Controller                                                                 | 1         | 1.67%   |
| Intel Cannon Lake PCH cAVS                                                                      | 1         | 1.67%   |
| Intel C610/X99 series chipset HD Audio Controller                                               | 1         | 1.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                      | 1         | 1.67%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 1         | 1.67%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                                               | 1         | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 1         | 1.67%   |
| Intel 200 Series PCH HD Audio                                                                   | 1         | 1.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 1         | 1.67%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 1         | 1.67%   |
| AMD Wrestler HDMI Audio                                                                         | 1         | 1.67%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 1         | 1.67%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                            | 1         | 1.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 1         | 1.67%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 1         | 1.67%   |
| AMD Kabini HDMI/DP Audio                                                                        | 1         | 1.67%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                          | 1         | 1.67%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 1         | 1.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 14        | 29.17%  |
| Samsung Electronics | 8         | 16.67%  |
| Kingston            | 6         | 12.5%   |
| Micron Technology   | 5         | 10.42%  |
| Unknown             | 2         | 4.17%   |
| Nanya Technology    | 2         | 4.17%   |
| Kingmax             | 2         | 4.17%   |
| Hikvision           | 2         | 4.17%   |
| G.Skill             | 2         | 4.17%   |
| Toshiba             | 1         | 2.08%   |
| Team                | 1         | 2.08%   |
| Elpida              | 1         | 2.08%   |
| Crucial             | 1         | 2.08%   |
| Corsair             | 1         | 2.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 3.77%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s        | 2         | 3.77%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                   | 1         | 1.89%   |
| Unknown RAM Module 2048MB DIMM DDR3 1067MT/s               | 1         | 1.89%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s         | 1         | 1.89%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s          | 1         | 1.89%   |
| Team RAM TEAMGROUP-UD3-1600 8192MB DIMM DDR3 1600MT/s      | 1         | 1.89%   |
| SK hynix RAM HYMP325S64AMP8-Y5 2048MB SODIMM DDR2 667MT/s  | 1         | 1.89%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s       | 1         | 1.89%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s   | 1         | 1.89%   |
| SK hynix RAM HMT41GU6AFR8A-PB 8192MB DIMM DDR3 1600MT/s    | 1         | 1.89%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 1.89%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s     | 1         | 1.89%   |
| SK hynix RAM HMT325S6CFR8A-PB 2048MB SODIMM DDR3 1600MT/s  | 1         | 1.89%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM 1600MT/s          | 1         | 1.89%   |
| SK hynix RAM HMT125U7TFR8C-H9 2048MB DIMM DDR3 1333MT/s    | 1         | 1.89%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2400MT/s  | 1         | 1.89%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s     | 1         | 1.89%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s     | 1         | 1.89%   |
| SK hynix RAM HMA41GR7MFR8N-TF 8192MB RIMM DDR4 2133MT/s    | 1         | 1.89%   |
| SK hynix RAM HMA41GR7AFR8N-TF 8192MB RIMM DDR4 2133MT/s    | 1         | 1.89%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s             | 1         | 1.89%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 1         | 1.89%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 1.89%   |
| Samsung RAM M4 70T5663QZ3-CE6 2048MB SODIMM DDR2 667MT/s   | 1         | 1.89%   |
| Samsung RAM M393A1G43DB0-CPB 8192MB RIMM DDR4 2133MT/s     | 1         | 1.89%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s     | 1         | 1.89%   |
| Nanya RAM NT4GC72B4NA1NL-BE 4096MB DIMM DDR3 1066MT/s      | 1         | 1.89%   |
| Nanya RAM NT4GC64C88B1NS-DI 4096MB SODIMM DDR3 1600MT/s    | 1         | 1.89%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s              | 1         | 1.89%   |
| Micron RAM Module 2048MB SODIMM DDR3 1600MT/s              | 1         | 1.89%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s      | 1         | 1.89%   |
| Micron RAM 4ATF51264HZ-2G3B1 4096MB SODIMM DDR4 2400MT/s   | 1         | 1.89%   |
| Micron RAM 4ATF51264HZ-2G3A1 4096MB SODIMM DDR4 2400MT/s   | 1         | 1.89%   |
| Kingston RAM M378A1K43BB2-CRC 4096MB DIMM DDR4 2400MT/s    | 1         | 1.89%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s        | 1         | 1.89%   |
| Kingston RAM 99U5584-009.A00LF 4096MB DIMM DDR3 1600MT/s   | 1         | 1.89%   |
| Kingston RAM 99U5584-001.A00LF 4096MB DIMM DDR3 1600MT/s   | 1         | 1.89%   |
| Kingston RAM 99U5428-063.A00LF 8192MB SODIMM DDR3 1600MT/s | 1         | 1.89%   |
| Kingston RAM 9905594-001.A00G 2048MB DIMM DDR3 1600MT/s    | 1         | 1.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 20        | 51.28%  |
| DDR4    | 11        | 28.21%  |
| DDR2    | 4         | 10.26%  |
| Unknown | 2         | 5.13%   |
| SDRAM   | 1         | 2.56%   |
| DDR     | 1         | 2.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 24        | 61.54%  |
| DIMM   | 14        | 35.9%   |
| RIMM   | 1         | 2.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 21        | 46.67%  |
| 8192  | 11        | 24.44%  |
| 2048  | 11        | 24.44%  |
| 16384 | 1         | 2.22%   |
| 1024  | 1         | 2.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 14        | 33.33%  |
| 2400  | 6         | 14.29%  |
| 3200  | 4         | 9.52%   |
| 667   | 3         | 7.14%   |
| 2133  | 2         | 4.76%   |
| 1866  | 2         | 4.76%   |
| 1066  | 2         | 4.76%   |
| 800   | 2         | 4.76%   |
| 2666  | 1         | 2.38%   |
| 2048  | 1         | 2.38%   |
| 1800  | 1         | 2.38%   |
| 1334  | 1         | 2.38%   |
| 1333  | 1         | 2.38%   |
| 1067  | 1         | 2.38%   |
| 533   | 1         | 2.38%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)

![Printer Vendor](./images/line_chart/printer_vendor.svg)

| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)

![Printer Model](./images/line_chart/printer_model.svg)

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)

![Camera Vendor](./images/line_chart/camera_vendor.svg)

| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 4         | 20%     |
| Suyin                                  | 3         | 15%     |
| Realtek Semiconductor                  | 3         | 15%     |
| Microdia                               | 3         | 15%     |
| Cheng Uei Precision Industry (Foxlink) | 2         | 10%     |
| Sunplus Innovation Technology          | 1         | 5%      |
| IMC Networks                           | 1         | 5%      |
| DLEQNA19IFK6G2                         | 1         | 5%      |
| Apple                                  | 1         | 5%      |
| Acer                                   | 1         | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Suyin Integrated_Webcam_HD                          | 1         | 5%      |
| Suyin HP webcam [dv6-1190en]                        | 1         | 5%      |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 5%      |
| Sunplus HP Truevision HD                            | 1         | 5%      |
| Realtek VGA WebCam                                  | 1         | 5%      |
| Realtek HD WebCam                                   | 1         | 5%      |
| Realtek FJ Camera                                   | 1         | 5%      |
| Microdia Integrated HD Webcam                       | 1         | 5%      |
| Microdia Dell Integrated HD Webcam                  | 1         | 5%      |
| Microdia Camera                                     | 1         | 5%      |
| IMC Networks Integrated Webcam                      | 1         | 5%      |
| DLEQNA19IFK6G2 HP TrueVision HD Camera              | 1         | 5%      |
| Chicony Webcam                                      | 1         | 5%      |
| Chicony HP TrueVision HD Camera                     | 1         | 5%      |
| Chicony HP Truevision HD                            | 1         | 5%      |
| Chicony CNF9055 Toshiba Webcam                      | 1         | 5%      |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 5%      |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 5%      |
| Apple FaceTime HD Camera (Built-in)                 | 1         | 5%      |
| Acer Lenovo Integrated Webcam                       | 1         | 5%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 1         | 33.33%  |
| LighTuning Technology | 1         | 33.33%  |
| AuthenTec             | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 33.33%  |
| LighTuning Fingerprint Reader              | 1         | 33.33%  |
| AuthenTec AES2501 Fingerprint Sensor       | 1         | 33.33%  |

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
| 0     | 30        | 76.92%  |
| 1     | 7         | 17.95%  |
| 2     | 2         | 5.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 3         | 27.27%  |
| Bluetooth          | 3         | 27.27%  |
| Graphics card      | 2         | 18.18%  |
| Chipcard           | 2         | 18.18%  |
| Unassigned class   | 1         | 9.09%   |

