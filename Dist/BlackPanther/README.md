BlackPanther - Hardware Trends
------------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/BlackPanther/Desktop/README.md) and [notebooks](/Dist/BlackPanther/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: Jun, 2023.

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
| BlackPanther 18.1 | 82        | 90.11%  |
| BlackPanther 22.1 | 7         | 7.69%   |
| BlackPanther 16.2 | 2         | 2.2%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| BlackPanther | 91        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.6.14-desktop-2bP     | 36        | 39.56%  |
| 5.15.85-desktop-1bP    | 25        | 27.47%  |
| 4.18.16-desktop-1bP    | 23        | 25.27%  |
| 6.3.3-desktop-1bP      | 4         | 4.4%    |
| 4.9.20-desktop-pae-1bP | 2         | 2.2%    |
| 6.1.0-1bP              | 1         | 1.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.6.14  | 36        | 39.56%  |
| 5.15.85 | 25        | 27.47%  |
| 4.18.16 | 23        | 25.27%  |
| 6.3.3   | 4         | 4.4%    |
| 4.9.20  | 2         | 2.2%    |
| 6.1.0   | 1         | 1.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.6     | 36        | 39.56%  |
| 5.15    | 25        | 27.47%  |
| 4.18    | 23        | 25.27%  |
| 6.3     | 4         | 4.4%    |
| 4.9     | 2         | 2.2%    |
| 6.1     | 1         | 1.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 89        | 97.8%   |
| i686   | 2         | 2.2%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| KDE5    | 89        | 97.8%   |
| Unknown | 2         | 2.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 91        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| SDDM | 91        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 91        | 100%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 46        | 50.55%  |
| EFI  | 45        | 49.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 63        | 69.23%  |
| Overlay | 28        | 30.77%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 46        | 50.55%  |
| MBR  | 45        | 49.45%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 68        | 74.73%  |
| Yes       | 23        | 25.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 48        | 52.75%  |
| Yes       | 43        | 47.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 18        | 19.78%  |
| Gigabyte Technology | 15        | 16.48%  |
| Hewlett-Packard     | 12        | 13.19%  |
| Lenovo              | 10        | 10.99%  |
| ASUSTek Computer    | 10        | 10.99%  |
| Fujitsu             | 6         | 6.59%   |
| ASRock              | 5         | 5.49%   |
| MSI                 | 4         | 4.4%    |
| Acer                | 3         | 3.3%    |
| Samsung Electronics | 2         | 2.2%    |
| Fujitsu Siemens     | 2         | 2.2%    |
| eMachines           | 2         | 2.2%    |
| Toshiba             | 1         | 1.1%    |
| Apple               | 1         | 1.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Dell OptiPlex 3020                          | 4         | 4.4%    |
| HP 250 G1                                   | 3         | 3.3%    |
| Gigabyte Z390 UD                            | 2         | 2.2%    |
| Gigabyte G31M-ES2L                          | 2         | 2.2%    |
| Fujitsu ESPRIMO Q556/2                      | 2         | 2.2%    |
| eMachines E725                              | 2         | 2.2%    |
| Dell Latitude 7390                          | 2         | 2.2%    |
| ASRock G41M-VS3                             | 2         | 2.2%    |
| Toshiba Satellite C660D                     | 1         | 1.1%    |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 1.1%    |
| Samsung RV410/RV510/S3510/E3510             | 1         | 1.1%    |
| MSI MS-7C91                                 | 1         | 1.1%    |
| MSI MS-7309                                 | 1         | 1.1%    |
| MSI GT60 2OC/2OD                            | 1         | 1.1%    |
| MSI GP75 Leopard 9SE                        | 1         | 1.1%    |
| Lenovo V15-ADA 82C7                         | 1         | 1.1%    |
| Lenovo ThinkPad X200 74595FG                | 1         | 1.1%    |
| Lenovo ThinkPad T540p 20BE003YUK            | 1         | 1.1%    |
| Lenovo ThinkCentre M93p 10A7003AUK          | 1         | 1.1%    |
| Lenovo ThinkCentre M73 10B6001SUS           | 1         | 1.1%    |
| Lenovo IdeaPad Y700-15ISK 80NV              | 1         | 1.1%    |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2         | 1         | 1.1%    |
| Lenovo IdeaPad 330-15IKB 81DE               | 1         | 1.1%    |
| Lenovo IdeaPad 330-15AST 81D6               | 1         | 1.1%    |
| Lenovo 10A8-S1WL00                          | 1         | 1.1%    |
| HP ProDesk 600 G1 SFF                       | 1         | 1.1%    |
| HP ProBook 650 G2                           | 1         | 1.1%    |
| HP ProBook 640 G8 Notebook PC               | 1         | 1.1%    |
| HP Pavilion Gaming Laptop 15-ec1xxx         | 1         | 1.1%    |
| HP Notebook                                 | 1         | 1.1%    |
| HP Laptop 15-dw1xxx                         | 1         | 1.1%    |
| HP EliteDesk 705 G3 SFF                     | 1         | 1.1%    |
| HP EliteBook 2540p                          | 1         | 1.1%    |
| HP Compaq Pro 6300 SFF                      | 1         | 1.1%    |
| Gigabyte Z270N-WIFI                         | 1         | 1.1%    |
| Gigabyte P67A-D3-B3                         | 1         | 1.1%    |
| Gigabyte P35-S3G                            | 1         | 1.1%    |
| Gigabyte H61M-S1                            | 1         | 1.1%    |
| Gigabyte H110M-S2V-CF                       | 1         | 1.1%    |
| Gigabyte GA-890GPA-UD3H                     | 1         | 1.1%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell Latitude           | 6         | 6.59%   |
| Dell Inspiron           | 5         | 5.49%   |
| Lenovo IdeaPad          | 4         | 4.4%    |
| Fujitsu ESPRIMO         | 4         | 4.4%    |
| Dell OptiPlex           | 4         | 4.4%    |
| HP 250                  | 3         | 3.3%    |
| Lenovo ThinkPad         | 2         | 2.2%    |
| Lenovo ThinkCentre      | 2         | 2.2%    |
| HP ProBook              | 2         | 2.2%    |
| Gigabyte Z390           | 2         | 2.2%    |
| Gigabyte G31M-ES2L      | 2         | 2.2%    |
| eMachines E725          | 2         | 2.2%    |
| ASRock G41M-VS3         | 2         | 2.2%    |
| Acer Aspire             | 2         | 2.2%    |
| Toshiba Satellite       | 1         | 1.1%    |
| Samsung RV411           | 1         | 1.1%    |
| Samsung RV410           | 1         | 1.1%    |
| MSI MS-7C91             | 1         | 1.1%    |
| MSI MS-7309             | 1         | 1.1%    |
| MSI GT60                | 1         | 1.1%    |
| MSI GP75                | 1         | 1.1%    |
| Lenovo V15-ADA          | 1         | 1.1%    |
| Lenovo 10A8-S1WL00      | 1         | 1.1%    |
| HP ProDesk              | 1         | 1.1%    |
| HP Pavilion             | 1         | 1.1%    |
| HP Notebook             | 1         | 1.1%    |
| HP Laptop               | 1         | 1.1%    |
| HP EliteDesk            | 1         | 1.1%    |
| HP EliteBook            | 1         | 1.1%    |
| HP Compaq               | 1         | 1.1%    |
| Gigabyte Z270N-WIFI     | 1         | 1.1%    |
| Gigabyte P67A-D3-B3     | 1         | 1.1%    |
| Gigabyte P35-S3G        | 1         | 1.1%    |
| Gigabyte H61M-S1        | 1         | 1.1%    |
| Gigabyte H110M-S2V-CF   | 1         | 1.1%    |
| Gigabyte GA-890GPA-UD3H | 1         | 1.1%    |
| Gigabyte GA-880GM-D2H   | 1         | 1.1%    |
| Gigabyte G41M-ES2L      | 1         | 1.1%    |
| Gigabyte F2A88XM-D3HP   | 1         | 1.1%    |
| Gigabyte B450M          | 1         | 1.1%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2010 | 11        | 12.09%  |
| 2018 | 9         | 9.89%   |
| 2017 | 8         | 8.79%   |
| 2015 | 8         | 8.79%   |
| 2014 | 8         | 8.79%   |
| 2013 | 7         | 7.69%   |
| 2008 | 7         | 7.69%   |
| 2012 | 6         | 6.59%   |
| 2011 | 6         | 6.59%   |
| 2016 | 4         | 4.4%    |
| 2009 | 4         | 4.4%    |
| 2021 | 3         | 3.3%    |
| 2020 | 3         | 3.3%    |
| 2019 | 3         | 3.3%    |
| 2007 | 2         | 2.2%    |
| 2023 | 1         | 1.1%    |
| 2006 | 1         | 1.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 46        | 50.55%  |
| Notebook   | 44        | 48.35%  |
| All in one | 1         | 1.1%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 91        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 91        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 28        | 30.77%  |
| 8.01-16.0  | 22        | 24.18%  |
| 4.01-8.0   | 19        | 20.88%  |
| 16.01-24.0 | 10        | 10.99%  |
| 1.01-2.0   | 8         | 8.79%   |
| 32.01-64.0 | 2         | 2.2%    |
| 2.01-3.0   | 2         | 2.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 41        | 45.05%  |
| 0.51-1.0 | 33        | 36.26%  |
| 0.01-0.5 | 8         | 8.79%   |
| 2.01-3.0 | 6         | 6.59%   |
| 4.01-8.0 | 2         | 2.2%    |
| 3.01-4.0 | 1         | 1.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 50        | 54.95%  |
| 2      | 31        | 34.07%  |
| 3      | 7         | 7.69%   |
| 5      | 2         | 2.2%    |
| 0      | 1         | 1.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 60.44%  |
| No        | 36        | 39.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 97.8%   |
| No        | 2         | 2.2%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 70.33%  |
| No        | 27        | 29.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 51.65%  |
| No        | 44        | 48.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country  | Computers | Percent |
|----------|-----------|---------|
| Hungary  | 72        | 79.12%  |
| Germany  | 5         | 5.49%   |
| Slovakia | 4         | 4.4%    |
| UK       | 3         | 3.3%    |
| Romania  | 2         | 2.2%    |
| Serbia   | 1         | 1.1%    |
| Greece   | 1         | 1.1%    |
| France   | 1         | 1.1%    |
| Canada   | 1         | 1.1%    |
| Austria  | 1         | 1.1%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Budapest                | 20        | 21.98%  |
| Zalaegerszeg            | 3         | 3.3%    |
| Hajduboszormeny         | 3         | 3.3%    |
| Tatabánya              | 2         | 2.2%    |
| Tamasi                  | 2         | 2.2%    |
| Szolnok                 | 2         | 2.2%    |
| Szekszárd              | 2         | 2.2%    |
| Seligenstadt            | 2         | 2.2%    |
| Sarbogard               | 2         | 2.2%    |
| Pfaffenhofen an der Ilm | 2         | 2.2%    |
| Karcag                  | 2         | 2.2%    |
| Jaszapati               | 2         | 2.2%    |
| Harlow                  | 2         | 2.2%    |
| Győr                   | 2         | 2.2%    |
| Fertoszentmiklos        | 2         | 2.2%    |
| Debrecen                | 2         | 2.2%    |
| Vienna                  | 1         | 1.1%    |
| Velky Meder             | 1         | 1.1%    |
| Tornaľa                | 1         | 1.1%    |
| Tapiobicske             | 1         | 1.1%    |
| Taksony                 | 1         | 1.1%    |
| Szombathely             | 1         | 1.1%    |
| Szigetujfalu            | 1         | 1.1%    |
| Szigetszentmiklos       | 1         | 1.1%    |
| Szentendre              | 1         | 1.1%    |
| Rožňava               | 1         | 1.1%    |
| Pomaz                   | 1         | 1.1%    |
| Pécs                   | 1         | 1.1%    |
| Papa                    | 1         | 1.1%    |
| Oroshaza                | 1         | 1.1%    |
| Obarok                  | 1         | 1.1%    |
| Nyul                    | 1         | 1.1%    |
| Nyiregyhaza             | 1         | 1.1%    |
| Nick                    | 1         | 1.1%    |
| Nancy                   | 1         | 1.1%    |
| Nagykanizsa             | 1         | 1.1%    |
| Miskolc                 | 1         | 1.1%    |
| Milnthorpe              | 1         | 1.1%    |
| Miercurea-Ciuc          | 1         | 1.1%    |
| Mezotur                 | 1         | 1.1%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 31     | 19.55%  |
| Samsung Electronics | 20        | 24     | 15.04%  |
| Kingston            | 16        | 18     | 12.03%  |
| Toshiba             | 11        | 11     | 8.27%   |
| Seagate             | 10        | 11     | 7.52%   |
| SanDisk             | 6         | 7      | 4.51%   |
| Intenso             | 5         | 5      | 3.76%   |
| Patriot             | 4         | 4      | 3.01%   |
| Unknown             | 3         | 3      | 2.26%   |
| SPCC                | 3         | 3      | 2.26%   |
| HGST                | 3         | 3      | 2.26%   |
| A-DATA Technology   | 3         | 3      | 2.26%   |
| Micron Technology   | 2         | 2      | 1.5%    |
| Intel               | 2         | 2      | 1.5%    |
| Hitachi             | 2         | 2      | 1.5%    |
| Crucial             | 2         | 2      | 1.5%    |
| Zheino              | 1         | 1      | 0.75%   |
| Verbatim            | 1         | 1      | 0.75%   |
| Timetec             | 1         | 1      | 0.75%   |
| SSSTC               | 1         | 1      | 0.75%   |
| SK hynix            | 1         | 1      | 0.75%   |
| LITEON              | 1         | 1      | 0.75%   |
| KIOXIA              | 1         | 1      | 0.75%   |
| Kingmax             | 1         | 1      | 0.75%   |
| JMicron Technology  | 1         | 1      | 0.75%   |
| Hewlett-Packard     | 1         | 1      | 0.75%   |
| Gigabyte Technology | 1         | 1      | 0.75%   |
| China               | 1         | 2      | 0.75%   |
| ASENNO              | 1         | 1      | 0.75%   |
| Apple               | 1         | 1      | 0.75%   |
| Apacer              | 1         | 1      | 0.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37480G 480GB SSD     | 5         | 3.45%   |
| Kingston SA400S37240G 240GB SSD     | 5         | 3.45%   |
| Seagate ST500DM002-1BD142 500GB     | 4         | 2.76%   |
| Toshiba DT01ACA100 1TB              | 3         | 2.07%   |
| Samsung SSD 860 EVO 500GB           | 3         | 2.07%   |
| Kingston SUV400S37120G 120GB SSD    | 3         | 2.07%   |
| WDC WD5000AAKS-007AA0 500GB         | 2         | 1.38%   |
| WDC WD30EFRX-68EUZN0 3TB            | 2         | 1.38%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 1.38%   |
| SanDisk SDSSDH3512G 512GB           | 2         | 1.38%   |
| Samsung SSD 970 EVO Plus 2TB        | 2         | 1.38%   |
| Samsung SSD 830 Series 64GB         | 2         | 1.38%   |
| Patriot Burst 120GB SSD             | 2         | 1.38%   |
| Micron 1100_MTFDDAK256TBN 256GB SSD | 2         | 1.38%   |
| Intenso SSD 120GB                   | 2         | 1.38%   |
| Intenso Portable SSD 128GB          | 2         | 1.38%   |
| Hitachi HTS545050B9A300 500GB       | 2         | 1.38%   |
| HGST HTS545032A7E380 320GB          | 2         | 1.38%   |
| Zheino CHN-NGFFNV2280-256 256GB     | 1         | 0.69%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1         | 0.69%   |
| WDC WD800JD-75MSA3 80GB             | 1         | 0.69%   |
| WDC WD6400AAKS-07A7B0 640GB         | 1         | 0.69%   |
| WDC WD5003AZEX-00MK2A0 500GB        | 1         | 0.69%   |
| WDC WD5000LPVX-80V0TT0 500GB        | 1         | 0.69%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 1         | 0.69%   |
| WDC WD5000BPVT-24HXZT3 500GB        | 1         | 0.69%   |
| WDC WD5000BPVT-00HXZT1 500GB        | 1         | 0.69%   |
| WDC WD5000BPKT-75PK4T0 500GB        | 1         | 0.69%   |
| WDC WD5000AAKX-221CA1 500GB         | 1         | 0.69%   |
| WDC WD5000AAKS-65YGA0 500GB         | 1         | 0.69%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 1         | 0.69%   |
| WDC WD5000AACS-00G8B1 500GB         | 1         | 0.69%   |
| WDC WD3200BEVT-08A23T1 320GB        | 1         | 0.69%   |
| WDC WD30EZRZ-00GXCB0 3TB            | 1         | 0.69%   |
| WDC WD30EZRX-00DC0B0 3TB            | 1         | 0.69%   |
| WDC WD2500BEVT-00ZCT0 250GB         | 1         | 0.69%   |
| WDC WD20SPZX-22UA7T0 2TB            | 1         | 0.69%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 1         | 0.69%   |
| WDC WD15EARX-00PASB0 1TB            | 1         | 0.69%   |
| WDC WD1200BEVS-22UST0 120GB         | 1         | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 25        | 30     | 48.08%  |
| Seagate             | 10        | 11     | 19.23%  |
| Toshiba             | 9         | 9      | 17.31%  |
| Samsung Electronics | 3         | 3      | 5.77%   |
| HGST                | 3         | 3      | 5.77%   |
| Hitachi             | 2         | 2      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 15     | 21.21%  |
| Kingston            | 14        | 16     | 21.21%  |
| SanDisk             | 5         | 5      | 7.58%   |
| Intenso             | 5         | 5      | 7.58%   |
| Patriot             | 4         | 4      | 6.06%   |
| SPCC                | 3         | 3      | 4.55%   |
| Micron Technology   | 2         | 2      | 3.03%   |
| Intel               | 2         | 2      | 3.03%   |
| Crucial             | 2         | 2      | 3.03%   |
| A-DATA Technology   | 2         | 2      | 3.03%   |
| WDC                 | 1         | 1      | 1.52%   |
| Verbatim            | 1         | 1      | 1.52%   |
| Toshiba             | 1         | 1      | 1.52%   |
| Timetec             | 1         | 1      | 1.52%   |
| SK hynix            | 1         | 1      | 1.52%   |
| LITEON              | 1         | 1      | 1.52%   |
| Kingmax             | 1         | 1      | 1.52%   |
| Hewlett-Packard     | 1         | 1      | 1.52%   |
| Gigabyte Technology | 1         | 1      | 1.52%   |
| China               | 1         | 2      | 1.52%   |
| ASENNO              | 1         | 1      | 1.52%   |
| Apple               | 1         | 1      | 1.52%   |
| Apacer              | 1         | 1      | 1.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 57        | 70     | 46.72%  |
| HDD  | 49        | 58     | 40.16%  |
| NVMe | 13        | 16     | 10.66%  |
| MMC  | 3         | 3      | 2.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 85        | 126    | 81.73%  |
| NVMe | 13        | 15     | 12.5%   |
| SAS  | 3         | 3      | 2.88%   |
| MMC  | 3         | 3      | 2.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 74        | 90     | 68.52%  |
| 0.51-1.0   | 27        | 30     | 25%     |
| 2.01-3.0   | 3         | 4      | 2.78%   |
| 1.01-2.0   | 3         | 3      | 2.78%   |
| 3.01-4.0   | 1         | 1      | 0.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 26        | 28.57%  |
| Unknown        | 26        | 28.57%  |
| 251-500        | 14        | 15.38%  |
| 501-1000       | 6         | 6.59%   |
| 21-50          | 5         | 5.49%   |
| 1001-2000      | 5         | 5.49%   |
| 51-100         | 4         | 4.4%    |
| More than 3000 | 2         | 2.2%    |
| 1-20           | 2         | 2.2%    |
| 2001-3000      | 1         | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 26        | 28.57%  |
| 1-20           | 24        | 26.37%  |
| 51-100         | 13        | 14.29%  |
| 21-50          | 12        | 13.19%  |
| 101-250        | 8         | 8.79%   |
| 501-1000       | 3         | 3.3%    |
| 1001-2000      | 2         | 2.2%    |
| More than 3000 | 1         | 1.1%    |
| 251-500        | 1         | 1.1%    |
| 2001-3000      | 1         | 1.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD5000AAKS-007AA0 500GB                      | 2         | 2      | 6.67%   |
| Seagate ST500LT012-9WS142 500GB                  | 2         | 2      | 6.67%   |
| Seagate ST500DM002-1BD142 500GB                  | 2         | 2      | 6.67%   |
| Hitachi HTS545050B9A300 500GB                    | 2         | 2      | 6.67%   |
| HGST HTS545032A7E380 320GB                       | 2         | 2      | 6.67%   |
| WDC WD6400AAKS-07A7B0 640GB                      | 1         | 1      | 3.33%   |
| WDC WD5000LPVX-80V0TT0 500GB                     | 1         | 1      | 3.33%   |
| WDC WD5000AAKS-00UU3A0 500GB                     | 1         | 1      | 3.33%   |
| WDC WD5000AACS-00G8B1 500GB                      | 1         | 1      | 3.33%   |
| WDC WD3200BEVT-08A23T1 320GB                     | 1         | 1      | 3.33%   |
| WDC WD30EFRX-68EUZN0 3TB                         | 1         | 1      | 3.33%   |
| WDC WD2500BEVT-00ZCT0 250GB                      | 1         | 1      | 3.33%   |
| WDC WD10PURZ-85U8XY0 1TB                         | 1         | 1      | 3.33%   |
| WDC WD10JPLX-00MBPT0 1TB                         | 1         | 1      | 3.33%   |
| Toshiba MK3252GSX 320GB                          | 1         | 1      | 3.33%   |
| Toshiba DT01ACA050 500GB                         | 1         | 1      | 3.33%   |
| Timetec SD08 512GB SSD                           | 1         | 1      | 3.33%   |
| Samsung Electronics SSD 750 EVO 250GB            | 1         | 1      | 3.33%   |
| Samsung Electronics MZ7LN256HMJP-000H1 256GB SSD | 1         | 1      | 3.33%   |
| Samsung Electronics HD103UJ 1TB                  | 1         | 1      | 3.33%   |
| Intel SSDSC2KF240H6L 240GB                       | 1         | 1      | 3.33%   |
| Intel SSDSA1M160G2HP 160GB                       | 1         | 1      | 3.33%   |
| China SSD 240GB                                  | 1         | 1      | 3.33%   |
| Apple SSD TS064E 64GB                            | 1         | 1      | 3.33%   |
| A-DATA Technology SU630 240GB SSD                | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 11     | 36.67%  |
| Seagate             | 4         | 4      | 13.33%  |
| Samsung Electronics | 3         | 3      | 10%     |
| Toshiba             | 2         | 2      | 6.67%   |
| Intel               | 2         | 2      | 6.67%   |
| Hitachi             | 2         | 2      | 6.67%   |
| HGST                | 2         | 2      | 6.67%   |
| Timetec             | 1         | 1      | 3.33%   |
| China               | 1         | 1      | 3.33%   |
| Apple               | 1         | 1      | 3.33%   |
| A-DATA Technology   | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 11     | 50%     |
| Seagate             | 4         | 4      | 18.18%  |
| Toshiba             | 2         | 2      | 9.09%   |
| Hitachi             | 2         | 2      | 9.09%   |
| HGST                | 2         | 2      | 9.09%   |
| Samsung Electronics | 1         | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 22     | 72.41%  |
| SSD  | 8         | 8      | 27.59%  |

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
| Works    | 73        | 110    | 66.97%  |
| Malfunc  | 29        | 30     | 26.61%  |
| Detected | 7         | 7      | 6.42%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 69        | 64.49%  |
| AMD                            | 17        | 15.89%  |
| Samsung Electronics            | 5         | 4.67%   |
| Nvidia                         | 4         | 3.74%   |
| Toshiba America Info Systems   | 2         | 1.87%   |
| Silicon Motion                 | 2         | 1.87%   |
| Kingston Technology Company    | 2         | 1.87%   |
| JMicron Technology             | 2         | 1.87%   |
| Solid State Storage Technology | 1         | 0.93%   |
| Silicon Image                  | 1         | 0.93%   |
| SanDisk                        | 1         | 0.93%   |
| ASMedia Technology             | 1         | 0.93%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10        | 8%      |
| AMD FCH SATA Controller [AHCI mode]                                                     | 10        | 8%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 7         | 5.6%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 4%      |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 4%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 3.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 2.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 2.4%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3         | 2.4%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 2.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 2.4%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 2.4%    |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1.6%    |
| Nvidia MCP61 SATA Controller                                                            | 2         | 1.6%    |
| Nvidia MCP61 IDE                                                                        | 2         | 1.6%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 1.6%    |
| Intel SATA Controller [RAID mode]                                                       | 2         | 1.6%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.6%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.6%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 1.6%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2         | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 1.6%    |
| AMD FCH IDE Controller                                                                  | 2         | 1.6%    |
| AMD 500 Series Chipset SATA Controller                                                  | 2         | 1.6%    |
| AMD 300 Series Chipset SATA Controller                                                  | 2         | 1.6%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 0.8%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1         | 0.8%    |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                          | 1         | 0.8%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 0.8%    |
| Silicon Motion Non-Volatile memory controller                                           | 1         | 0.8%    |
| Silicon Image SiI 3512 [SATALink/SATARaid] Serial ATA Controller                        | 1         | 0.8%    |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 1         | 0.8%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.8%    |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 1         | 0.8%    |
| Nvidia MCP73 SATA Controller (IDE mode)                                                 | 1         | 0.8%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 73        | 65.77%  |
| IDE  | 17        | 15.32%  |
| NVMe | 13        | 11.71%  |
| RAID | 8         | 7.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 71        | 78.02%  |
| AMD    | 20        | 21.98%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i3-4160 CPU @ 3.60GHz            | 5         | 5.49%   |
| Intel Celeron CPU 1000M @ 1.80GHz           | 3         | 3.3%    |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2         | 2.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 2.2%    |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2.2%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2         | 2.2%    |
| Intel Core i5-2540M CPU @ 2.60GHz           | 2         | 2.2%    |
| Intel Core i3-6100T CPU @ 3.20GHz           | 2         | 2.2%    |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2         | 2.2%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2         | 2.2%    |
| Intel Xeon CPU W3550 @ 3.07GHz              | 1         | 1.1%    |
| Intel Xeon CPU E5530 @ 2.40GHz              | 1         | 1.1%    |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1         | 1.1%    |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.1%    |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.1%    |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 1.1%    |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 1.1%    |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 1.1%    |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 1.1%    |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.1%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 1.1%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 1.1%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.1%    |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 1.1%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 1.1%    |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 1.1%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.1%    |
| Intel Core i7-4510U CPU @ 2.00GHz           | 1         | 1.1%    |
| Intel Core i7 CPU L 640 @ 2.13GHz           | 1         | 1.1%    |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 1.1%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.1%    |
| Intel Core i5-5200U CPU @ 2.20GHz           | 1         | 1.1%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1         | 1.1%    |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 1.1%    |
| Intel Core i5-3427U CPU @ 1.80GHz           | 1         | 1.1%    |
| Intel Core i5-3340M CPU @ 2.70GHz           | 1         | 1.1%    |
| Intel Core i5-2300 CPU @ 2.80GHz            | 1         | 1.1%    |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 1         | 1.1%    |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1         | 1.1%    |
| Intel Core i3-5005U CPU @ 2.00GHz           | 1         | 1.1%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 19        | 20.88%  |
| Intel Core i3           | 15        | 16.48%  |
| Intel Core i7           | 10        | 10.99%  |
| Intel Core 2 Duo        | 8         | 8.79%   |
| Intel Celeron           | 5         | 5.49%   |
| AMD Ryzen 5             | 5         | 5.49%   |
| Other                   | 3         | 3.3%    |
| Intel Xeon              | 3         | 3.3%    |
| Intel Pentium Dual-Core | 3         | 3.3%    |
| Intel Pentium           | 3         | 3.3%    |
| AMD Ryzen 7             | 2         | 2.2%    |
| AMD A8                  | 2         | 2.2%    |
| Intel Core 2 Quad       | 1         | 1.1%    |
| Intel Core 2            | 1         | 1.1%    |
| Intel Celeron Dual-Core | 1         | 1.1%    |
| AMD V140                | 1         | 1.1%    |
| AMD Ryzen 3             | 1         | 1.1%    |
| AMD Phenom II X4        | 1         | 1.1%    |
| AMD FX                  | 1         | 1.1%    |
| AMD Athlon II X2        | 1         | 1.1%    |
| AMD Athlon Dual Core    | 1         | 1.1%    |
| AMD Athlon 64 X2        | 1         | 1.1%    |
| AMD Athlon 64           | 1         | 1.1%    |
| AMD A4                  | 1         | 1.1%    |
| AMD A10                 | 1         | 1.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 52        | 57.14%  |
| 4      | 26        | 28.57%  |
| 6      | 5         | 5.49%   |
| 1      | 5         | 5.49%   |
| 8      | 2         | 2.2%    |
| 3      | 1         | 1.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 91        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 52        | 57.14%  |
| 1      | 39        | 42.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 91        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 10        | 10.99%  |
| Unknown    | 10        | 10.99%  |
| 0x1067a    | 9         | 9.89%   |
| 0x306a9    | 7         | 7.69%   |
| 0x506e3    | 5         | 5.49%   |
| 0x206a7    | 4         | 4.4%    |
| 0x20655    | 4         | 4.4%    |
| 0x806e9    | 3         | 3.3%    |
| 0x08108109 | 3         | 3.3%    |
| 0x906ea    | 2         | 2.2%    |
| 0x806ea    | 2         | 2.2%    |
| 0x806c1    | 2         | 2.2%    |
| 0x306d4    | 2         | 2.2%    |
| 0x106a5    | 2         | 2.2%    |
| 0x010000c8 | 2         | 2.2%    |
| 0x906eb    | 1         | 1.1%    |
| 0x906e9    | 1         | 1.1%    |
| 0x806ec    | 1         | 1.1%    |
| 0x6fd      | 1         | 1.1%    |
| 0x6fa      | 1         | 1.1%    |
| 0x6f2      | 1         | 1.1%    |
| 0x506c9    | 1         | 1.1%    |
| 0x406c3    | 1         | 1.1%    |
| 0x40651    | 1         | 1.1%    |
| 0x30678    | 1         | 1.1%    |
| 0x10677    | 1         | 1.1%    |
| 0x10676    | 1         | 1.1%    |
| 0x10661    | 1         | 1.1%    |
| 0x0a50000d | 1         | 1.1%    |
| 0x0a20120a | 1         | 1.1%    |
| 0x08600109 | 1         | 1.1%    |
| 0x08600106 | 1         | 1.1%    |
| 0x08001137 | 1         | 1.1%    |
| 0x06006704 | 1         | 1.1%    |
| 0x0600611a | 1         | 1.1%    |
| 0x06003109 | 1         | 1.1%    |
| 0x06003106 | 1         | 1.1%    |
| 0x06001119 | 1         | 1.1%    |
| 0x010000b6 | 1         | 1.1%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Haswell     | 12        | 13.19%  |
| Penryn      | 11        | 12.09%  |
| KabyLake    | 11        | 12.09%  |
| IvyBridge   | 8         | 8.79%   |
| Skylake     | 7         | 7.69%   |
| Westmere    | 4         | 4.4%    |
| SandyBridge | 4         | 4.4%    |
| Core        | 4         | 4.4%    |
| Zen+        | 3         | 3.3%    |
| K8 Hammer   | 3         | 3.3%    |
| K10         | 3         | 3.3%    |
| Broadwell   | 3         | 3.3%    |
| Zen 3       | 2         | 2.2%    |
| Zen 2       | 2         | 2.2%    |
| TigerLake   | 2         | 2.2%    |
| Steamroller | 2         | 2.2%    |
| Silvermont  | 2         | 2.2%    |
| Piledriver  | 2         | 2.2%    |
| Nehalem     | 2         | 2.2%    |
| Excavator   | 2         | 2.2%    |
| Zen         | 1         | 1.1%    |
| Goldmont    | 1         | 1.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 52        | 50.49%  |
| Nvidia | 30        | 29.13%  |
| AMD    | 21        | 20.39%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 6         | 5.66%   |
| Intel HD Graphics 530                                                                 | 6         | 5.66%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller             | 5         | 4.72%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 5         | 4.72%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 3         | 2.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 3         | 2.83%   |
| Intel HD Graphics 620                                                                 | 3         | 2.83%   |
| Intel HD Graphics 5500                                                                | 3         | 2.83%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                     | 2         | 1.89%   |
| Intel UHD Graphics 620                                                                | 2         | 1.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 1.89%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 2         | 1.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 2         | 1.89%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 1.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 1.89%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                        | 2         | 1.89%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                      | 2         | 1.89%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 0.94%   |
| Nvidia TU117 [GeForce GTX 1650]                                                       | 1         | 0.94%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 1         | 0.94%   |
| Nvidia GT218M [NVS 3100M]                                                             | 1         | 0.94%   |
| Nvidia GT218M [GeForce 315M]                                                          | 1         | 0.94%   |
| Nvidia GT218 [GeForce 210]                                                            | 1         | 0.94%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 1         | 0.94%   |
| Nvidia GP104 [GeForce GTX 1080]                                                       | 1         | 0.94%   |
| Nvidia GM108M [GeForce 845M]                                                          | 1         | 0.94%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 0.94%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 0.94%   |
| Nvidia GK208BM [GeForce 920M]                                                         | 1         | 0.94%   |
| Nvidia GK107M [GeForce GT 750M]                                                       | 1         | 0.94%   |
| Nvidia GK106M [GeForce GTX 770M]                                                      | 1         | 0.94%   |
| Nvidia GK106GL [Quadro K4000]                                                         | 1         | 0.94%   |
| Nvidia GF119M [GeForce GT 520M]                                                       | 1         | 0.94%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                     | 1         | 0.94%   |
| Nvidia GF108 [GeForce GT 630]                                                         | 1         | 0.94%   |
| Nvidia GA106 [Geforce RTX 3050]                                                       | 1         | 0.94%   |
| Nvidia G98 [GeForce 8400]                                                             | 1         | 0.94%   |
| Nvidia G96CM [GeForce 9600M GT]                                                       | 1         | 0.94%   |
| Nvidia G96CGL [Quadro FX 580]                                                         | 1         | 0.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 42        | 46.15%  |
| 1 x Nvidia     | 19        | 20.88%  |
| 1 x AMD        | 16        | 17.58%  |
| Intel + Nvidia | 8         | 8.79%   |
| 2 x AMD        | 2         | 2.2%    |
| AMD + Nvidia   | 2         | 2.2%    |
| 2 x Nvidia     | 1         | 1.1%    |
| Intel + AMD    | 1         | 1.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 88        | 96.7%   |
| Unknown | 3         | 3.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 51.65%  |
| 0.51-1.0   | 18        | 19.78%  |
| 1.01-2.0   | 10        | 10.99%  |
| 0.01-0.5   | 9         | 9.89%   |
| 3.01-4.0   | 4         | 4.4%    |
| 7.01-8.0   | 1         | 1.1%    |
| 5.01-6.0   | 1         | 1.1%    |
| 2.01-3.0   | 1         | 1.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 14        | 15.56%  |
| LG Display              | 14        | 15.56%  |
| Chimei Innolux          | 6         | 6.67%   |
| AU Optronics            | 6         | 6.67%   |
| Goldstar                | 5         | 5.56%   |
| Dell                    | 5         | 5.56%   |
| Ancor Communications    | 5         | 5.56%   |
| Acer                    | 5         | 5.56%   |
| BenQ                    | 4         | 4.44%   |
| Philips                 | 3         | 3.33%   |
| BOE                     | 3         | 3.33%   |
| Vestel Elektronik       | 2         | 2.22%   |
| PANDA                   | 2         | 2.22%   |
| Lenovo                  | 2         | 2.22%   |
| Hewlett-Packard         | 2         | 2.22%   |
| Chi Mei Optoelectronics | 2         | 2.22%   |
| Unknown                 | 1         | 1.11%   |
| NCS                     | 1         | 1.11%   |
| Medion                  | 1         | 1.11%   |
| LMV                     | 1         | 1.11%   |
| LG Philips              | 1         | 1.11%   |
| Iiyama                  | 1         | 1.11%   |
| Fujitsu Siemens         | 1         | 1.11%   |
| Eizo                    | 1         | 1.11%   |
| CVT                     | 1         | 1.11%   |
| Apple                   | 1         | 1.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 3         | 3.23%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch  | 2         | 2.15%   |
| Samsung Electronics LS27AG30x SAM717A 1920x1080 597x336mm 27.0-inch   | 2         | 2.15%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 2         | 2.15%   |
| BenQ EW277HDR BNQ7948 1920x1080 598x336mm 27.0-inch                   | 2         | 2.15%   |
| Ancor Communications ASUS VW198 ACI19AA 1680x1050 450x300mm 21.3-inch | 2         | 2.15%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 2         | 2.15%   |
| Acer V193HQV ACR013E 1366x768 410x230mm 18.5-inch                     | 2         | 2.15%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 1.08%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1         | 1.08%   |
| Samsung Electronics SyncMaster SAM01B8 1280x1024 338x270mm 17.0-inch  | 1         | 1.08%   |
| Samsung Electronics S27E500 SAM0D0D 1920x1080 598x336mm 27.0-inch     | 1         | 1.08%   |
| Samsung Electronics S24R35x SAM100E 1920x1080 527x296mm 23.8-inch     | 1         | 1.08%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 1         | 1.08%   |
| Samsung Electronics S24D300 SAM0B45 1920x1080 521x293mm 23.5-inch     | 1         | 1.08%   |
| Samsung Electronics S22B370 SAM08BD 1920x1080 477x268mm 21.5-inch     | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC304F 1680x945 409x230mm 18.5-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 1.08%   |
| Samsung Electronics LCD Monitor C49J89x 1680x1050                     | 1         | 1.08%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch    | 1         | 1.08%   |
| Philips 221B PHL08A1 1920x1080 477x268mm 21.5-inch                    | 1         | 1.08%   |
| Philips 196V4 PHLC0AF 1366x768 410x230mm 18.5-inch                    | 1         | 1.08%   |
| Philips 190WV PHLC014 1440x900 408x255mm 18.9-inch                    | 1         | 1.08%   |
| PANDA LCD Monitor NCP0065 1920x1080 309x174mm 14.0-inch               | 1         | 1.08%   |
| PANDA LCD Monitor NCP0058 1920x1080 344x194mm 15.5-inch               | 1         | 1.08%   |
| NCS LCD Monitor NCS2275 1920x1080 256x192mm 12.6-inch                 | 1         | 1.08%   |
| Medion MD20666 MED3673 1920x1080 533x312mm 24.3-inch                  | 1         | 1.08%   |
| LMV LM19V LMV00BE 1280x1024 337x270mm 17.0-inch                       | 1         | 1.08%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch           | 1         | 1.08%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 1         | 1.08%   |
| LG Display LCD Monitor LGD06F5 1920x1080 344x194mm 15.5-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD0589 1920x1080 294x165mm 13.3-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD036C 1366x768 277x156mm 12.5-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD0365 1600x900 382x215mm 17.3-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD02CF 1366x768 344x194mm 15.5-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD024F 1280x800 260x160mm 12.0-inch           | 1         | 1.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 38        | 43.18%  |
| 1366x768 (WXGA)    | 19        | 21.59%  |
| 1280x1024 (SXGA)   | 9         | 10.23%  |
| 1680x1050 (WSXGA+) | 7         | 7.95%   |
| 1440x900 (WXGA+)   | 4         | 4.55%   |
| 1600x900 (HD+)     | 3         | 3.41%   |
| 1280x800 (WXGA)    | 3         | 3.41%   |
| 3840x2160 (4K)     | 2         | 2.27%   |
| 3840x1080          | 1         | 1.14%   |
| 2288x1287          | 1         | 1.14%   |
| 1680x945           | 1         | 1.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 24        | 25.81%  |
| 21      | 11        | 11.83%  |
| 17      | 10        | 10.75%  |
| 27      | 7         | 7.53%   |
| 23      | 7         | 7.53%   |
| 19      | 5         | 5.38%   |
| 18      | 5         | 5.38%   |
| 24      | 4         | 4.3%    |
| 12      | 4         | 4.3%    |
| 22      | 3         | 3.23%   |
| 14      | 3         | 3.23%   |
| 13      | 3         | 3.23%   |
| 84      | 2         | 2.15%   |
| 142     | 1         | 1.08%   |
| 49      | 1         | 1.08%   |
| 26      | 1         | 1.08%   |
| 11      | 1         | 1.08%   |
| Unknown | 1         | 1.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 31        | 33.33%  |
| 401-500        | 21        | 22.58%  |
| 501-600        | 18        | 19.35%  |
| 351-400        | 11        | 11.83%  |
| 201-300        | 7         | 7.53%   |
| 1501-2000      | 2         | 2.15%   |
| More than 2000 | 1         | 1.08%   |
| 1001-1500      | 1         | 1.08%   |
| Unknown        | 1         | 1.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 61        | 70.11%  |
| 5/4     | 9         | 10.34%  |
| 16/10   | 9         | 10.34%  |
| 3/2     | 4         | 4.6%    |
| 4/3     | 1         | 1.15%   |
| 32/9    | 1         | 1.15%   |
| 1.00    | 1         | 1.15%   |
| Unknown | 1         | 1.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 26.09%  |
| 201-250        | 20        | 21.74%  |
| 151-200        | 9         | 9.78%   |
| 141-150        | 9         | 9.78%   |
| 301-350        | 7         | 7.61%   |
| 81-90          | 5         | 5.43%   |
| 121-130        | 4         | 4.35%   |
| More than 1000 | 3         | 3.26%   |
| 61-70          | 3         | 3.26%   |
| 71-80          | 2         | 2.17%   |
| 251-300        | 2         | 2.17%   |
| 51-60          | 1         | 1.09%   |
| 131-140        | 1         | 1.09%   |
| 501-1000       | 1         | 1.09%   |
| Unknown        | 1         | 1.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 44        | 47.83%  |
| 101-120 | 24        | 26.09%  |
| 121-160 | 20        | 21.74%  |
| 161-240 | 2         | 2.17%   |
| 1-50    | 1         | 1.09%   |
| Unknown | 1         | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 81        | 89.01%  |
| 2     | 7         | 7.69%   |
| 0     | 2         | 2.2%    |
| 3     | 1         | 1.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 51        | 38.64%  |
| Intel                           | 30        | 22.73%  |
| Qualcomm Atheros                | 22        | 16.67%  |
| Broadcom                        | 8         | 6.06%   |
| Ralink                          | 4         | 3.03%   |
| TP-Link                         | 3         | 2.27%   |
| Ralink Technology               | 3         | 2.27%   |
| Nvidia                          | 3         | 2.27%   |
| Qualcomm Atheros Communications | 2         | 1.52%   |
| Samsung Electronics             | 1         | 0.76%   |
| Marvell Technology Group        | 1         | 0.76%   |
| IMC Networks                    | 1         | 0.76%   |
| Edimax Technology               | 1         | 0.76%   |
| D-Link System                   | 1         | 0.76%   |
| Broadcom Limited                | 1         | 0.76%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 40        | 25.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 4.46%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 3.18%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 1.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 1.91%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.91%   |
| Intel Wireless 7265                                               | 3         | 1.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.91%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 2         | 1.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 1.27%   |
| Ralink RT5372 Wireless Adapter                                    | 2         | 1.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.27%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 1.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 1.27%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.27%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 1.27%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.27%   |
| Nvidia MCP61 Ethernet                                             | 2         | 1.27%   |
| Intel Wireless 8260                                               | 2         | 1.27%   |
| Intel Wireless 7260                                               | 2         | 1.27%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.27%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.27%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.27%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.27%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 1.27%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.27%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.27%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 1.27%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1         | 0.64%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.64%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 22        | 34.38%  |
| Qualcomm Atheros                | 13        | 20.31%  |
| Realtek Semiconductor           | 9         | 14.06%  |
| Broadcom                        | 5         | 7.81%   |
| Ralink                          | 4         | 6.25%   |
| TP-Link                         | 3         | 4.69%   |
| Ralink Technology               | 3         | 4.69%   |
| Qualcomm Atheros Communications | 2         | 3.13%   |
| IMC Networks                    | 1         | 1.56%   |
| Edimax Technology               | 1         | 1.56%   |
| Broadcom Limited                | 1         | 1.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 3         | 4.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 3         | 4.69%   |
| Intel Wireless 8265 / 8275                                             | 3         | 4.69%   |
| Intel Wireless 7265                                                    | 3         | 4.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 3         | 4.69%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 2         | 3.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 3.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2         | 3.13%   |
| Ralink RT5372 Wireless Adapter                                         | 2         | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2         | 3.13%   |
| Qualcomm Atheros AR9271 802.11n                                        | 2         | 3.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2         | 3.13%   |
| Intel Wireless 8260                                                    | 2         | 3.13%   |
| Intel Wireless 7260                                                    | 2         | 3.13%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 3.13%   |
| Intel Centrino Advanced-N 6200                                         | 2         | 3.13%   |
| TP-Link 802.11ac WLAN Adapter                                          | 1         | 1.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 1.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 1.56%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1         | 1.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 1         | 1.56%   |
| Ralink MT7601U Wireless Adapter                                        | 1         | 1.56%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                              | 1         | 1.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1         | 1.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1         | 1.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 1         | 1.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 1         | 1.56%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                       | 1         | 1.56%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 1         | 1.56%   |
| Intel Wireless 3165                                                    | 1         | 1.56%   |
| Intel Wireless 3160                                                    | 1         | 1.56%   |
| Intel WiFi Link 5100                                                   | 1         | 1.56%   |
| Intel Ultimate N WiFi Link 5300                                        | 1         | 1.56%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 1         | 1.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1         | 1.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 1         | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 1         | 1.56%   |
| IMC Networks AW-NU222 802.11bgn Wireless Module [Ralink RT2770+RT2720] | 1         | 1.56%   |
| Edimax AC600 USB                                                       | 1         | 1.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 48        | 53.33%  |
| Intel                    | 21        | 23.33%  |
| Qualcomm Atheros         | 12        | 13.33%  |
| Broadcom                 | 4         | 4.44%   |
| Nvidia                   | 3         | 3.33%   |
| Marvell Technology Group | 1         | 1.11%   |
| D-Link System            | 1         | 1.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 40        | 43.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 7.61%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 5.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.26%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 2.17%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 2.17%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 2.17%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 2.17%   |
| Nvidia MCP61 Ethernet                                             | 2         | 2.17%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.17%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 2.17%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 2.17%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.17%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 2.17%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 2.17%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.09%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.09%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.09%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.09%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.09%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.09%   |
| Nvidia MCP73 Ethernet                                             | 1         | 1.09%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.09%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.09%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.09%   |
| D-Link System DL10050 Sundance Ethernet                           | 1         | 1.09%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 1.09%   |
| Broadcom NetLink BCM5787 Gigabit Ethernet PCI Express             | 1         | 1.09%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 89        | 57.79%  |
| WiFi     | 64        | 41.56%  |
| Modem    | 1         | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 46        | 51.11%  |
| Ethernet | 44        | 48.89%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 50        | 54.95%  |
| 1     | 40        | 43.96%  |
| 3     | 1         | 1.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 58        | 63.74%  |
| Yes  | 33        | 36.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 34.04%  |
| Cambridge Silicon Radio         | 11        | 23.4%   |
| Realtek Semiconductor           | 6         | 12.77%  |
| Qualcomm Atheros Communications | 5         | 10.64%  |
| Ralink                          | 3         | 6.38%   |
| Toshiba                         | 1         | 2.13%   |
| Logitech                        | 1         | 2.13%   |
| Lite-On Technology              | 1         | 2.13%   |
| Hewlett-Packard                 | 1         | 2.13%   |
| Broadcom                        | 1         | 2.13%   |
| Apple                           | 1         | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 25.53%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11        | 23.4%   |
| Realtek Bluetooth Radio                             | 6         | 12.77%  |
| Ralink RT3290 Bluetooth                             | 3         | 6.38%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 4.26%   |
| Intel AX201 Bluetooth                               | 2         | 4.26%   |
| Toshiba Askey Bluetooth Module                      | 1         | 2.13%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.13%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.13%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1         | 2.13%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.13%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.13%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.13%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 2.13%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 70        | 58.33%  |
| AMD                 | 23        | 19.17%  |
| Nvidia              | 21        | 17.5%   |
| Creative Labs       | 2         | 1.67%   |
| Texas Instruments   | 1         | 0.83%   |
| Promethean Limited  | 1         | 0.83%   |
| Logitech            | 1         | 0.83%   |
| Creative Technology | 1         | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                                           | Computers | Percent |
|-------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 11        | 7.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 9         | 6.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 8         | 5.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 7         | 4.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 7         | 4.73%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 6         | 4.05%   |
| Intel Sunrise Point-LP HD Audio                                                                 | 5         | 3.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 5         | 3.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 5         | 3.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 4         | 2.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 4         | 2.7%    |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 4         | 2.7%    |
| Nvidia High Definition Audio Controller                                                         | 3         | 2.03%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                         | 3         | 2.03%   |
| Intel Cannon Lake PCH cAVS                                                                      | 3         | 2.03%   |
| Intel Broadwell-U Audio Controller                                                              | 3         | 2.03%   |
| AMD FCH Azalia Controller                                                                       | 3         | 2.03%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                  | 2         | 1.35%   |
| Nvidia MCP61 High Definition Audio                                                              | 2         | 1.35%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 2         | 1.35%   |
| Nvidia GK106 HDMI Audio Controller                                                              | 2         | 1.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                     | 2         | 1.35%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 2         | 1.35%   |
| Intel 200 Series PCH HD Audio                                                                   | 2         | 1.35%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 2         | 1.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 2         | 1.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 2         | 1.35%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 2         | 1.35%   |
| AMD Kaveri HDMI/DP Audio Controller                                                             | 2         | 1.35%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                | 2         | 1.35%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                          | 2         | 1.35%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]               | 2         | 1.35%   |
| Texas Instruments PCM2902 Audio Codec                                                           | 1         | 0.68%   |
| Promethean Limited Audio                                                                        | 1         | 0.68%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 1         | 0.68%   |
| Nvidia MCP73 High Definition Audio                                                              | 1         | 0.68%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                       | 1         | 0.68%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 1         | 0.68%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 1         | 0.68%   |
| Nvidia GF116 High Definition Audio Controller                                                   | 1         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 24        | 23.08%  |
| SK hynix            | 19        | 18.27%  |
| Unknown             | 18        | 17.31%  |
| Micron Technology   | 12        | 11.54%  |
| Kingston            | 9         | 8.65%   |
| Crucial             | 5         | 4.81%   |
| Corsair             | 4         | 3.85%   |
| Nanya Technology    | 3         | 2.88%   |
| G.Skill             | 3         | 2.88%   |
| Elpida              | 2         | 1.92%   |
| Ramaxel Technology  | 1         | 0.96%   |
| Qimonda             | 1         | 0.96%   |
| PUSKILL             | 1         | 0.96%   |
| Kingmax             | 1         | 0.96%   |
| A-DATA Technology   | 1         | 0.96%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM 800MT/s                                       | 4         | 3.54%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                          | 4         | 3.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                        | 3         | 2.65%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                                     | 2         | 1.77%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                                      | 2         | 1.77%   |
| Unknown RAM Module 1024MB DIMM DDR2                                          | 2         | 1.77%   |
| SK hynix RAM HMT451U6BFR8A-PB 4096MB DIMM DDR3 1648MT/s                      | 2         | 1.77%   |
| SK hynix RAM HMT325S6CFR8A-PB 2048MB SODIMM DDR3 1600MT/s                    | 2         | 1.77%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                       | 2         | 1.77%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                        | 2         | 1.77%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                        | 2         | 1.77%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s                        | 2         | 1.77%   |
| Kingston RAM M378A1K43BB2-CRC 4096MB DIMM DDR4 2400MT/s                      | 2         | 1.77%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s                          | 2         | 1.77%   |
| Crucial RAM BLS4G4D240FSB.8FBD2 4096MB DIMM DDR4 2400MT/s                    | 2         | 1.77%   |
| Unknown RAM V02L3L84GB52852816 4096MB DIMM DDR3 1333MT/s                     | 1         | 0.88%   |
| Unknown RAM V02D4S84GB5285282400 4096MB SODIMM DDR4 2133MT/s                 | 1         | 0.88%   |
| Unknown RAM Module 8192MB DIMM DDR4 2667MT/s                                 | 1         | 0.88%   |
| Unknown RAM Module 4096MB DIMM SDRAM                                         | 1         | 0.88%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                                      | 1         | 0.88%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                                | 1         | 0.88%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                         | 1         | 0.88%   |
| Unknown RAM Module 2048MB DIMM DDR2                                          | 1         | 0.88%   |
| Unknown RAM DDR3 1600 8G 8192MB DIMM DDR3 1600MT/s                           | 1         | 0.88%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1333MT/s                              | 1         | 0.88%   |
| SK hynix RAM HYMP125S64CP8-Y5 2048MB SODIMM DDR2 667MT/s                     | 1         | 0.88%   |
| SK hynix RAM HMT451U7BFR8A-PB 4096MB DIMM DDR3 1600MT/s                      | 1         | 0.88%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.88%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.88%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.88%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.88%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                       | 1         | 0.88%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s                       | 1         | 0.88%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s                    | 1         | 0.88%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB DIMM DDR3 1333MT/s                      | 1         | 0.88%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                       | 1         | 0.88%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s                       | 1         | 0.88%   |
| SK hynix RAM DADADADADADADADADADADADADADADADADADA 2048MB SODIMM DDR2 800MT/s | 1         | 0.88%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                               | 1         | 0.88%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                               | 1         | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 40        | 43.01%  |
| DDR4    | 30        | 32.26%  |
| Unknown | 9         | 9.68%   |
| SDRAM   | 7         | 7.53%   |
| DDR2    | 7         | 7.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 46        | 50.55%  |
| DIMM         | 44        | 48.35%  |
| Row Of Chips | 1         | 1.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 39        | 39%     |
| 8192  | 25        | 25%     |
| 2048  | 25        | 25%     |
| 16384 | 6         | 6%      |
| 1024  | 5         | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 28        | 27.18%  |
| 800     | 10        | 9.71%   |
| 3200    | 9         | 8.74%   |
| 2400    | 8         | 7.77%   |
| 2667    | 7         | 6.8%    |
| 2133    | 7         | 6.8%    |
| 1333    | 7         | 6.8%    |
| 1334    | 5         | 4.85%   |
| Unknown | 4         | 3.88%   |
| 4199    | 2         | 1.94%   |
| 3266    | 2         | 1.94%   |
| 1648    | 2         | 1.94%   |
| 1067    | 2         | 1.94%   |
| 667     | 2         | 1.94%   |
| 3066    | 1         | 0.97%   |
| 2800    | 1         | 0.97%   |
| 2666    | 1         | 0.97%   |
| 2448    | 1         | 0.97%   |
| 2048    | 1         | 0.97%   |
| 2000    | 1         | 0.97%   |
| 1866    | 1         | 0.97%   |
| 1066    | 1         | 0.97%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)

![Printer Vendor](./All/images/line_chart/printer_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 40%     |
| Hewlett-Packard     | 2         | 40%     |
| QinHeng Electronics | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)

![Printer Model](./All/images/line_chart/printer_model.svg)

| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-1640 Series Laser Printer | 1         | 20%     |
| Samsung C48x Series                  | 1         | 20%     |
| QinHeng CH340S                       | 1         | 20%     |
| HP LaserJet 2600n                    | 1         | 20%     |
| HP DeskJet 2620 All-in-One Printer   | 1         | 20%     |

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
| Microdia                               | 9         | 17.65%  |
| Chicony Electronics                    | 9         | 17.65%  |
| Sunplus Innovation Technology          | 4         | 7.84%   |
| IMC Networks                           | 4         | 7.84%   |
| Suyin                                  | 3         | 5.88%   |
| Realtek Semiconductor                  | 3         | 5.88%   |
| Syntek                                 | 2         | 3.92%   |
| Silicon Motion                         | 2         | 3.92%   |
| Quanta                                 | 2         | 3.92%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.92%   |
| Apple                                  | 2         | 3.92%   |
| Alcor Micro                            | 2         | 3.92%   |
| Samsung Electronics                    | 1         | 1.96%   |
| Ricoh                                  | 1         | 1.96%   |
| Luxvisions Innotech Limited            | 1         | 1.96%   |
| KYE Systems (Mouse Systems)            | 1         | 1.96%   |
| Intel                                  | 1         | 1.96%   |
| Bison Electronics                      | 1         | 1.96%   |
| Acer                                   | 1         | 1.96%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Camera                                     | 3         | 5.88%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 3.92%   |
| Microdia Integrated HD Webcam                       | 2         | 3.92%   |
| Chicony HP Truevision HD                            | 2         | 3.92%   |
| Syntek Integrated Camera                            | 1         | 1.96%   |
| Syntek EasyCamera                                   | 1         | 1.96%   |
| Suyin Integrated_Webcam_HD                          | 1         | 1.96%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 1.96%   |
| Suyin Acer HD Crystal Eye webcam                    | 1         | 1.96%   |
| Sunplus HP Truevision HD                            | 1         | 1.96%   |
| Sunplus Full HD webcam                              | 1         | 1.96%   |
| Silicon Motion WebCam SCB-0355N                     | 1         | 1.96%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 1.96%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 1.96%   |
| Ricoh HD Webcam                                     | 1         | 1.96%   |
| Realtek USB2.0 VGA UVC WebCam                       | 1         | 1.96%   |
| Realtek Integrated Webcam_HD                        | 1         | 1.96%   |
| Realtek 2SF022                                      | 1         | 1.96%   |
| Quanta VGA WebCam                                   | 1         | 1.96%   |
| Quanta HP HD Camera                                 | 1         | 1.96%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 1.96%   |
| Microdia Sonix Integrated Webcam                    | 1         | 1.96%   |
| Microdia PC Microscope camera                       | 1         | 1.96%   |
| Microdia Dell Integrated HD Webcam                  | 1         | 1.96%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.96%   |
| KYE Systems (Mouse Systems) FaceCam 1000X           | 1         | 1.96%   |
| Intel RealSense 3D Camera (Front F200)              | 1         | 1.96%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.96%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 1.96%   |
| IMC Networks Integrated Camera                      | 1         | 1.96%   |
| IMC Networks EasyCamera                             | 1         | 1.96%   |
| Chicony VGA WebCam                                  | 1         | 1.96%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 1.96%   |
| Chicony HP Webcam [2 MP Macro]                      | 1         | 1.96%   |
| Chicony HP TrueVision HD Camera                     | 1         | 1.96%   |
| Chicony HD Webcam                                   | 1         | 1.96%   |
| Chicony FJ Camera                                   | 1         | 1.96%   |
| Chicony Acer CrystalEye Webcam                      | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 1.96%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 66.67%  |
| AuthenTec        | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS101 Fingerprint Reader   | 1         | 33.33%  |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 33.33%  |
| AuthenTec AES2810                            | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./All/images/line_chart/chipcard_vendor.svg)

| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 2         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 76        | 83.52%  |
| 1     | 14        | 15.38%  |
| 3     | 1         | 1.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 3         | 18.75%  |
| Fingerprint reader    | 3         | 18.75%  |
| Bluetooth             | 3         | 18.75%  |
| Chipcard              | 2         | 12.5%   |
| Camera                | 2         | 12.5%   |
| Storage               | 1         | 6.25%   |
| Multimedia controller | 1         | 6.25%   |
| Dvb card              | 1         | 6.25%   |

