Lubuntu - Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu/Desktop/README.md) and [notebooks](/Dist/Lubuntu/Notebook/README.md).

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

| Name          | Computers | Percent |
|---------------|-----------|---------|
| Lubuntu 22.04 | 14        | 48.28%  |
| Lubuntu 20.04 | 7         | 24.14%  |
| Lubuntu 22.10 | 4         | 13.79%  |
| Lubuntu 18.04 | 3         | 10.34%  |
| Lubuntu 21.10 | 1         | 3.45%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Lubuntu | 29        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.15.0-50-generic          | 6         | 20.69%  |
| 5.4.0-131-generic          | 3         | 10.34%  |
| 5.15.0-48-generic          | 3         | 10.34%  |
| 5.15.0-43-generic          | 3         | 10.34%  |
| 5.19.0-23-generic          | 2         | 6.9%    |
| 5.15.0-52-generic          | 2         | 6.9%    |
| 6.0.0-060000-generic       | 1         | 3.45%   |
| 5.4.0-132-generic          | 1         | 3.45%   |
| 5.4.0-128-generic          | 1         | 3.45%   |
| 5.4.0-126-generic          | 1         | 3.45%   |
| 5.19.0-21-generic          | 1         | 3.45%   |
| 5.19.0-16.2-liquorix-amd64 | 1         | 3.45%   |
| 5.15.0-47-generic          | 1         | 3.45%   |
| 5.13.0-40-generic          | 1         | 3.45%   |
| 5.11.0-27-generic          | 1         | 3.45%   |
| 4.15.0-91-generic          | 1         | 3.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 15        | 51.72%  |
| 5.4.0   | 6         | 20.69%  |
| 5.19.0  | 4         | 13.79%  |
| 6.0.0   | 1         | 3.45%   |
| 5.13.0  | 1         | 3.45%   |
| 5.11.0  | 1         | 3.45%   |
| 4.15.0  | 1         | 3.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 15        | 51.72%  |
| 5.4     | 6         | 20.69%  |
| 5.19    | 4         | 13.79%  |
| 6.0     | 1         | 3.45%   |
| 5.13    | 1         | 3.45%   |
| 5.11    | 1         | 3.45%   |
| 4.15    | 1         | 3.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 28        | 96.55%  |
| i686   | 1         | 3.45%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| LXQt    | 23        | 79.31%  |
| LXDE    | 4         | 13.79%  |
| Lubuntu | 1         | 3.45%   |
| i3      | 1         | 3.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 26        | 89.66%  |
| Wayland | 2         | 6.9%    |
| Tty     | 1         | 3.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 20        | 68.97%  |
| LightDM | 4         | 13.79%  |
| GDM     | 2         | 6.9%    |
| Unknown | 2         | 6.9%    |
| SLiM    | 1         | 3.45%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 5         | 17.24%  |
| fr_FR | 4         | 13.79%  |
| it_IT | 3         | 10.34%  |
| C     | 3         | 10.34%  |
| en_GB | 2         | 6.9%    |
| pt_BR | 1         | 3.45%   |
| pl_PL | 1         | 3.45%   |
| lt_LT | 1         | 3.45%   |
| ja_JP | 1         | 3.45%   |
| es_ES | 1         | 3.45%   |
| es_AR | 1         | 3.45%   |
| en_ZA | 1         | 3.45%   |
| en_PH | 1         | 3.45%   |
| en_IN | 1         | 3.45%   |
| en_CA | 1         | 3.45%   |
| el_GR | 1         | 3.45%   |
| de_DE | 1         | 3.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 20        | 68.97%  |
| EFI  | 9         | 31.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 26        | 89.66%  |
| Overlay | 3         | 10.34%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 14        | 48.28%  |
| GPT     | 14        | 48.28%  |
| Unknown | 1         | 3.45%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 93.1%   |
| Yes       | 2         | 6.9%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 22        | 75.86%  |
| Yes       | 7         | 24.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 7         | 24.14%  |
| Acer                | 5         | 17.24%  |
| Hewlett-Packard     | 2         | 6.9%    |
| Fujitsu             | 2         | 6.9%    |
| Dell                | 2         | 6.9%    |
| Toshiba             | 1         | 3.45%   |
| Teclast             | 1         | 3.45%   |
| LG Electronics      | 1         | 3.45%   |
| Kiano               | 1         | 3.45%   |
| Intel               | 1         | 3.45%   |
| Google              | 1         | 3.45%   |
| Gigabyte Technology | 1         | 3.45%   |
| Fujitsu Siemens     | 1         | 3.45%   |
| ASUSTek Computer    | 1         | 3.45%   |
| ASRock              | 1         | 3.45%   |
| AOpen               | 1         | 3.45%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba Satellite C655D                    | 1         | 3.45%   |
| Teclast F7 Plus                            | 1         | 3.45%   |
| LG 22V280-L.BJ31P1                         | 1         | 3.45%   |
| Lenovo ThinkPad T410 2537CS0               | 1         | 3.45%   |
| Lenovo ThinkPad SL510 2847CXG              | 1         | 3.45%   |
| Lenovo ThinkCentre M81 5048E2G             | 1         | 3.45%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 1         | 3.45%   |
| Lenovo IdeaPad 330-14AST 81D5              | 1         | 3.45%   |
| Lenovo G50-70 20351                        | 1         | 3.45%   |
| Lenovo B590 20208                          | 1         | 3.45%   |
| Kiano SlimNote 14.1                        | 1         | 3.45%   |
| Intel D33217GKE G76540-203                 | 1         | 3.45%   |
| HP Z400 Workstation                        | 1         | 3.45%   |
| HP 431 Notebook                            | 1         | 3.45%   |
| Google Apel                                | 1         | 3.45%   |
| Gigabyte F2A58M-HD2                        | 1         | 3.45%   |
| Fujitsu Siemens AMILO Li 2727              | 1         | 3.45%   |
| Fujitsu LIFEBOOK U904                      | 1         | 3.45%   |
| Fujitsu FUTRO S900                         | 1         | 3.45%   |
| Dell Latitude E5430 non-vPro               | 1         | 3.45%   |
| Dell Inspiron N5010                        | 1         | 3.45%   |
| ASUS VivoBook 15_ASUS Laptop X507MA_F507MA | 1         | 3.45%   |
| ASRock H110M-HDV                           | 1         | 3.45%   |
| AOpen ESPRIMO Q9000                        | 1         | 3.45%   |
| Acer Extensa 2509                          | 1         | 3.45%   |
| Acer Aspire one                            | 1         | 3.45%   |
| Acer Aspire E1-571                         | 1         | 3.45%   |
| Acer Aspire 4739Z                          | 1         | 3.45%   |
| Acer AcerPower M8                          | 1         | 3.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 3         | 10.34%  |
| Lenovo ThinkPad       | 2         | 6.9%    |
| Lenovo IdeaPad        | 2         | 6.9%    |
| Toshiba Satellite     | 1         | 3.45%   |
| Teclast F7            | 1         | 3.45%   |
| LG 22V280-L.BJ31P1    | 1         | 3.45%   |
| Lenovo ThinkCentre    | 1         | 3.45%   |
| Lenovo G50-70         | 1         | 3.45%   |
| Lenovo B590           | 1         | 3.45%   |
| Kiano SlimNote        | 1         | 3.45%   |
| Intel D33217GKE       | 1         | 3.45%   |
| HP Z400               | 1         | 3.45%   |
| HP 431                | 1         | 3.45%   |
| Google Apel           | 1         | 3.45%   |
| Gigabyte F2A58M-HD2   | 1         | 3.45%   |
| Fujitsu Siemens AMILO | 1         | 3.45%   |
| Fujitsu LIFEBOOK      | 1         | 3.45%   |
| Fujitsu FUTRO         | 1         | 3.45%   |
| Dell Latitude         | 1         | 3.45%   |
| Dell Inspiron         | 1         | 3.45%   |
| ASUS VivoBook         | 1         | 3.45%   |
| ASRock H110M-HDV      | 1         | 3.45%   |
| AOpen ESPRIMO         | 1         | 3.45%   |
| Acer Extensa          | 1         | 3.45%   |
| Acer AcerPower        | 1         | 3.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 4         | 13.79%  |
| 2009 | 4         | 13.79%  |
| 2018 | 3         | 10.34%  |
| 2013 | 3         | 10.34%  |
| 2012 | 3         | 10.34%  |
| 2010 | 3         | 10.34%  |
| 2015 | 2         | 6.9%    |
| 2014 | 2         | 6.9%    |
| 2007 | 2         | 6.9%    |
| 2022 | 1         | 3.45%   |
| 2019 | 1         | 3.45%   |
| 2016 | 1         | 3.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 20        | 68.97%  |
| Desktop    | 8         | 27.59%  |
| All in one | 1         | 3.45%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 29        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 28        | 96.55%  |
| Yes  | 1         | 3.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 13        | 44.83%  |
| 1.01-2.0   | 6         | 20.69%  |
| 4.01-8.0   | 5         | 17.24%  |
| 16.01-24.0 | 2         | 6.9%    |
| 8.01-16.0  | 2         | 6.9%    |
| 2.01-3.0   | 1         | 3.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 11        | 37.93%  |
| 0.51-1.0  | 10        | 34.48%  |
| 3.01-4.0  | 4         | 13.79%  |
| 2.01-3.0  | 2         | 6.9%    |
| 4.01-8.0  | 1         | 3.45%   |
| 8.01-16.0 | 1         | 3.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 72.41%  |
| 2      | 6         | 20.69%  |
| 3      | 1         | 3.45%   |
| 0      | 1         | 3.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 55.17%  |
| No        | 13        | 44.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 86.21%  |
| No        | 4         | 13.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 82.76%  |
| No        | 5         | 17.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 51.72%  |
| No        | 14        | 48.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| France       | 5         | 17.24%  |
| Italy        | 3         | 10.34%  |
| USA          | 2         | 6.9%    |
| Hungary      | 2         | 6.9%    |
| Brazil       | 2         | 6.9%    |
| Vietnam      | 1         | 3.45%   |
| UK           | 1         | 3.45%   |
| Spain        | 1         | 3.45%   |
| South Africa | 1         | 3.45%   |
| Poland       | 1         | 3.45%   |
| Philippines  | 1         | 3.45%   |
| Lithuania    | 1         | 3.45%   |
| Japan        | 1         | 3.45%   |
| Ireland      | 1         | 3.45%   |
| Indonesia    | 1         | 3.45%   |
| India        | 1         | 3.45%   |
| Greece       | 1         | 3.45%   |
| Germany      | 1         | 3.45%   |
| Canada       | 1         | 3.45%   |
| Argentina    | 1         | 3.45%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City         | Computers | Percent |
|--------------|-----------|---------|
| Sarospatak   | 2         | 6.9%    |
| Winnipeg     | 1         | 3.45%   |
| Vilnius      | 1         | 3.45%   |
| Vannes       | 1         | 3.45%   |
| Tychy        | 1         | 3.45%   |
| Thessaloniki | 1         | 3.45%   |
| Tegal        | 1         | 3.45%   |
| Tandil       | 1         | 3.45%   |
| Rome         | 1         | 3.45%   |
| Pretoria     | 1         | 3.45%   |
| Porto Alegre | 1         | 3.45%   |
| Oberkotzau   | 1         | 3.45%   |
| Nus          | 1         | 3.45%   |
| New York     | 1         | 3.45%   |
| Montpellier  | 1         | 3.45%   |
| Minato-ku    | 1         | 3.45%   |
| Millville    | 1         | 3.45%   |
| Milan        | 1         | 3.45%   |
| Marseille    | 1         | 3.45%   |
| Manajao      | 1         | 3.45%   |
| Lagord       | 1         | 3.45%   |
| Huelva       | 1         | 3.45%   |
| Hanoi        | 1         | 3.45%   |
| Dublin       | 1         | 3.45%   |
| Camborne     | 1         | 3.45%   |
| Bengaluru    | 1         | 3.45%   |
| Bauru        | 1         | 3.45%   |
| Abbeville    | 1         | 3.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 7      | 18.18%  |
| Unknown             | 5         | 6      | 15.15%  |
| Seagate             | 4         | 4      | 12.12%  |
| Samsung Electronics | 3         | 3      | 9.09%   |
| Kingston            | 3         | 3      | 9.09%   |
| Hitachi             | 2         | 2      | 6.06%   |
| Vaseky              | 1         | 1      | 3.03%   |
| Toshiba             | 1         | 1      | 3.03%   |
| SPCC                | 1         | 1      | 3.03%   |
| Rogueware           | 1         | 1      | 3.03%   |
| LITEONIT            | 1         | 1      | 3.03%   |
| KingSpec            | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |
| HGST                | 1         | 1      | 3.03%   |
| Gigabyte Technology | 1         | 1      | 3.03%   |
| Crucial             | 1         | 1      | 3.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 2.94%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 2.94%   |
| WDC WD3200BPVT-22ZEST0 320GB         | 1         | 2.94%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 2.94%   |
| WDC WD1200BEVS-22UST0 120GB          | 1         | 2.94%   |
| WDC WD1003FBYX-01Y7B0 1TB            | 1         | 2.94%   |
| Vaseky V800/128G 128GB SSD           | 1         | 2.94%   |
| Unknown SD/MMC/MS PRO 1TB            | 1         | 2.94%   |
| Unknown MMC64G  64GB                 | 1         | 2.94%   |
| Unknown MMC Card  64GB               | 1         | 2.94%   |
| Unknown MMC Card  4GB                | 1         | 2.94%   |
| Unknown MMC Card  32GB               | 1         | 2.94%   |
| Unknown 00000  16GB                  | 1         | 2.94%   |
| Toshiba MK5065GSXN 500GB             | 1         | 2.94%   |
| SPCC Solid State Disk 120GB          | 1         | 2.94%   |
| Seagate ST9500325AS 500GB            | 1         | 2.94%   |
| Seagate ST9320325AS 320GB            | 1         | 2.94%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 2.94%   |
| Seagate ST3200826AS 200GB            | 1         | 2.94%   |
| Samsung SSD 860 PRO 512GB            | 1         | 2.94%   |
| Samsung SSD 860 EVO mSATA 500GB      | 1         | 2.94%   |
| Samsung MZ7LN128HCHP-00000 128GB SSD | 1         | 2.94%   |
| Rogueware 2.5'' 512GB SSD            | 1         | 2.94%   |
| LITEONIT LMT-128M6M mSATA 128GB SSD  | 1         | 2.94%   |
| Kingston SV300S37A60G 64GB SSD       | 1         | 2.94%   |
| Kingston SA400S37240G 240GB SSD      | 1         | 2.94%   |
| Kingston SA400S37120G 120GB SSD      | 1         | 2.94%   |
| KingSpec NT-256 256GB SSD            | 1         | 2.94%   |
| Intel SSDSA2CW160G3 160GB            | 1         | 2.94%   |
| Hitachi HDS721680PLA380 82GB         | 1         | 2.94%   |
| Hitachi HDS721025CLA682 250GB        | 1         | 2.94%   |
| HGST HTS545050A7E380 500GB           | 1         | 2.94%   |
| Gigabyte GP-GSTFS31120GNTD 120GB     | 1         | 2.94%   |
| Crucial CT240BX500SSD1 240GB         | 1         | 2.94%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 6      | 35.71%  |
| Seagate | 4         | 4      | 28.57%  |
| Hitachi | 2         | 2      | 14.29%  |
| Unknown | 1         | 1      | 7.14%   |
| Toshiba | 1         | 1      | 7.14%   |
| HGST    | 1         | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 20%     |
| Kingston            | 3         | 3      | 20%     |
| WDC                 | 1         | 1      | 6.67%   |
| Vaseky              | 1         | 1      | 6.67%   |
| SPCC                | 1         | 1      | 6.67%   |
| Rogueware           | 1         | 1      | 6.67%   |
| LITEONIT            | 1         | 1      | 6.67%   |
| KingSpec            | 1         | 1      | 6.67%   |
| Intel               | 1         | 1      | 6.67%   |
| Gigabyte Technology | 1         | 1      | 6.67%   |
| Crucial             | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 15        | 15     | 44.12%  |
| HDD  | 14        | 15     | 41.18%  |
| MMC  | 5         | 5      | 14.71%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 25        | 29     | 80.65%  |
| MMC  | 5         | 5      | 16.13%  |
| SAS  | 1         | 1      | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 23        | 25     | 88.46%  |
| 0.51-1.0   | 3         | 5      | 11.54%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 11        | 37.93%  |
| 101-250    | 11        | 37.93%  |
| 21-50      | 3         | 10.34%  |
| 1-20       | 2         | 6.9%    |
| 1001-2000  | 1         | 3.45%   |
| 51-100     | 1         | 3.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 15        | 51.72%  |
| 21-50     | 8         | 27.59%  |
| 101-250   | 4         | 13.79%  |
| 1001-2000 | 1         | 3.45%   |
| 51-100    | 1         | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD1003FBYX-01Y7B0 1TB       | 1         | 2      | 20%     |
| Toshiba MK5065GSXN 500GB        | 1         | 1      | 20%     |
| Seagate ST9320325AS 320GB       | 1         | 1      | 20%     |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 20%     |
| KingSpec NT-256 256GB SSD       | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 2         | 2      | 40%     |
| WDC      | 1         | 2      | 20%     |
| Toshiba  | 1         | 1      | 20%     |
| KingSpec | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 50%     |
| WDC     | 1         | 2      | 25%     |
| Toshiba | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 5      | 80%     |
| SSD  | 1         | 1      | 20%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)

![Failed Drives](./All/images/line_chart/drive_failed.svg)

| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD1200BEVS-22UST0 120GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)

![Failed Drive Vendor](./All/images/line_chart/drive_failed_vendor.svg)

| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)

![Drive Status](./All/images/line_chart/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 13        | 16     | 41.94%  |
| Works    | 12        | 12     | 38.71%  |
| Malfunc  | 5         | 6      | 16.13%  |
| Failed   | 1         | 1      | 3.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 21        | 77.78%  |
| AMD    | 5         | 18.52%  |
| Nvidia | 1         | 3.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 9.68%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3         | 9.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 9.68%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 6.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 6.45%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 2         | 6.45%   |
| Nvidia MCP61 SATA Controller                                                            | 1         | 3.23%   |
| Nvidia MCP61 IDE                                                                        | 1         | 3.23%   |
| Intel SATA Controller [RAID mode]                                                       | 1         | 3.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 3.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 3.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 3.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 3.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 3.23%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 1         | 3.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 1         | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1         | 3.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1         | 3.23%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1         | 3.23%   |
| AMD FCH IDE Controller                                                                  | 1         | 3.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 23        | 79.31%  |
| IDE  | 4         | 13.79%  |
| RAID | 2         | 6.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 23        | 79.31%  |
| AMD    | 6         | 20.69%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i3 CPU M 370 @ 2.40GHz             | 3         | 10.34%  |
| Intel Celeron N4100 CPU @ 1.10GHz             | 2         | 6.9%    |
| Intel Xeon CPU W3565 @ 3.20GHz                | 1         | 3.45%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 3.45%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 3.45%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 3.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 3.45%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 3.45%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 3.45%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 3.45%   |
| Intel Core i3-2348M CPU @ 2.30GHz             | 1         | 3.45%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 1         | 3.45%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 3.45%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz          | 1         | 3.45%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 3.45%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 3.45%   |
| Intel Celeron CPU N2930 @ 1.83GHz             | 1         | 3.45%   |
| Intel Celeron CPU 560 @ 2.13GHz               | 1         | 3.45%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 1         | 3.45%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 1         | 3.45%   |
| AMD G-T40N Processor                          | 1         | 3.45%   |
| AMD C-50 Processor                            | 1         | 3.45%   |
| AMD Athlon 64 X2 Dual Core Processor 4800+    | 1         | 3.45%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 1         | 3.45%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 1         | 3.45%   |
| AMD A4-4000 APU with Radeon HD Graphics       | 1         | 3.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i3    | 8         | 27.59%  |
| Intel Celeron    | 6         | 20.69%  |
| Intel Core i5    | 4         | 13.79%  |
| Intel Atom       | 2         | 6.9%    |
| AMD A4           | 2         | 6.9%    |
| Intel Xeon       | 1         | 3.45%   |
| Intel Core i7    | 1         | 3.45%   |
| Intel Core 2 Duo | 1         | 3.45%   |
| AMD G            | 1         | 3.45%   |
| AMD C-50         | 1         | 3.45%   |
| AMD Athlon 64 X2 | 1         | 3.45%   |
| AMD A6           | 1         | 3.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 20        | 68.97%  |
| 4      | 6         | 20.69%  |
| 1      | 3         | 10.34%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 29        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 15        | 51.72%  |
| 2      | 14        | 48.28%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 28        | 96.55%  |
| 32-bit         | 1         | 3.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 31.03%  |
| 0x20655    | 4         | 13.79%  |
| 0x706a1    | 3         | 10.34%  |
| 0x306a9    | 2         | 6.9%    |
| 0x206a7    | 2         | 6.9%    |
| 0x706a8    | 1         | 3.45%   |
| 0x40651    | 1         | 3.45%   |
| 0x30678    | 1         | 3.45%   |
| 0x106c2    | 1         | 3.45%   |
| 0x106a5    | 1         | 3.45%   |
| 0x1067a    | 1         | 3.45%   |
| 0x10661    | 1         | 3.45%   |
| 0x06001119 | 1         | 3.45%   |
| 0x05000029 | 1         | 3.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| Westmere      | 4         | 13.79%  |
| Goldmont plus | 4         | 13.79%  |
| SandyBridge   | 3         | 10.34%  |
| IvyBridge     | 3         | 10.34%  |
| Silvermont    | 2         | 6.9%    |
| Haswell       | 2         | 6.9%    |
| Excavator     | 2         | 6.9%    |
| Bobcat        | 2         | 6.9%    |
| Skylake       | 1         | 3.45%   |
| Piledriver    | 1         | 3.45%   |
| Penryn        | 1         | 3.45%   |
| Nehalem       | 1         | 3.45%   |
| K8 Hammer     | 1         | 3.45%   |
| Core          | 1         | 3.45%   |
| Bonnell       | 1         | 3.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 21        | 70%     |
| AMD    | 6         | 20%     |
| Nvidia | 3         | 10%     |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                           | 4         | 12.5%   |
| Intel Core Processor Integrated Graphics Controller                           | 4         | 12.5%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 3         | 9.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 3         | 9.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 6.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 6.25%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 2         | 6.25%   |
| Nvidia GM107GL [Quadro K2200]                                                 | 1         | 3.13%   |
| Nvidia GK208B [GeForce GT 720]                                                | 1         | 3.13%   |
| Nvidia C61 [GeForce 6100 nForce 405]                                          | 1         | 3.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 3.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 3.13%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 3.13%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 3.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 3.13%   |
| AMD Wrestler [Radeon HD 6290]                                                 | 1         | 3.13%   |
| AMD Wrestler [Radeon HD 6250]                                                 | 1         | 3.13%   |
| AMD Trinity 2 [Radeon HD 7480D]                                               | 1         | 3.13%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 1         | 3.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| 1 x Intel   | 19        | 65.52%  |
| 1 x AMD     | 5         | 17.24%  |
| 1 x Nvidia  | 3         | 10.34%  |
| Other       | 1         | 3.45%   |
| Intel + AMD | 1         | 3.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 28        | 96.55%  |
| Proprietary | 1         | 3.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 82.76%  |
| 0.51-1.0   | 2         | 6.9%    |
| 0.01-0.5   | 2         | 6.9%    |
| 3.01-4.0   | 1         | 3.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 4         | 13.79%  |
| LG Display              | 4         | 13.79%  |
| BOE                     | 4         | 13.79%  |
| Chimei Innolux          | 3         | 10.34%  |
| Lenovo                  | 2         | 6.9%    |
| Iiyama                  | 2         | 6.9%    |
| Sharp                   | 1         | 3.45%   |
| Sampo                   | 1         | 3.45%   |
| RTK                     | 1         | 3.45%   |
| NEC Computers           | 1         | 3.45%   |
| LG Philips              | 1         | 3.45%   |
| LG Electronics          | 1         | 3.45%   |
| HannStar                | 1         | 3.45%   |
| Goldstar                | 1         | 3.45%   |
| Chi Mei Optoelectronics | 1         | 3.45%   |
| Acer                    | 1         | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch                  | 1         | 3.45%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch         | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SEC5842 1366x768 309x174mm 14.0-inch     | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 1         | 3.45%   |
| Sampo 800S STC0800 800x600 170x127mm 8.4-inch                            | 1         | 3.45%   |
| RTK LG AIO FHD RTK2136 1920x1080 477x268mm 21.5-inch                     | 1         | 3.45%   |
| NEC Computers LCD1990SX NEC66DB 1280x1024 376x301mm 19.0-inch            | 1         | 3.45%   |
| LG Philips LCD Monitor LPL1E01 1280x800 331x207mm 15.4-inch              | 1         | 3.45%   |
| LG Electronics LCD Monitor E2241 1920x1080                               | 1         | 3.45%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 1         | 3.45%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch              | 1         | 3.45%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 3.45%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch              | 1         | 3.45%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 1         | 3.45%   |
| Lenovo LCD Monitor LEN4035 1280x800 304x190mm 14.1-inch                  | 1         | 3.45%   |
| Iiyama PL2475HD IVM6108 1920x1080 521x293mm 23.5-inch                    | 1         | 3.45%   |
| Iiyama PL2283H IVM562E 1920x1080 496x292mm 22.7-inch                     | 1         | 3.45%   |
| HannStar HL190APB HSD62C3 1366x768 410x230mm 18.5-inch                   | 1         | 3.45%   |
| Goldstar HD PLUS GSM5AC5 1600x900 440x250mm 19.9-inch                    | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch          | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 3.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO1004 1024x600 222x125mm 10.0-inch | 1         | 3.45%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                     | 1         | 3.45%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                     | 1         | 3.45%   |
| BOE LCD Monitor BOE0637 1920x1080 309x173mm 13.9-inch                    | 1         | 3.45%   |
| BOE LCD Monitor BOE0600 1366x768 309x173mm 13.9-inch                     | 1         | 3.45%   |
| Acer X223W ACR0009 1680x1050 473x296mm 22.0-inch                         | 1         | 3.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 14        | 48.28%  |
| 1920x1080 (FHD)    | 6         | 20.69%  |
| 1600x900 (HD+)     | 2         | 6.9%    |
| 1280x800 (WXGA)    | 2         | 6.9%    |
| 800x600            | 1         | 3.45%   |
| 3200x1800 (QHD+)   | 1         | 3.45%   |
| 1680x1050 (WSXGA+) | 1         | 3.45%   |
| 1280x1024 (SXGA)   | 1         | 3.45%   |
| 1024x600           | 1         | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 9         | 31.03%  |
| 14      | 5         | 17.24%  |
| 23      | 3         | 10.34%  |
| 22      | 2         | 6.9%    |
| 19      | 2         | 6.9%    |
| 13      | 2         | 6.9%    |
| 20      | 1         | 3.45%   |
| 18      | 1         | 3.45%   |
| 11      | 1         | 3.45%   |
| 10      | 1         | 3.45%   |
| 8       | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 55.17%  |
| 401-500     | 5         | 17.24%  |
| 501-600     | 3         | 10.34%  |
| 201-300     | 2         | 6.9%    |
| 351-400     | 1         | 3.45%   |
| 101-200     | 1         | 3.45%   |
| Unknown     | 1         | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 23        | 79.31%  |
| 16/10   | 3         | 10.34%  |
| 5/4     | 1         | 3.45%   |
| 4/3     | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 9         | 31.03%  |
| 81-90          | 7         | 24.14%  |
| 201-250        | 5         | 17.24%  |
| 151-200        | 3         | 10.34%  |
| 51-60          | 1         | 3.45%   |
| 41-50          | 1         | 3.45%   |
| 1-40           | 1         | 3.45%   |
| 141-150        | 1         | 3.45%   |
| Unknown        | 1         | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 13        | 44.83%  |
| 51-100        | 12        | 41.38%  |
| 121-160       | 2         | 6.9%    |
| More than 240 | 1         | 3.45%   |
| Unknown       | 1         | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 29        | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 15        | 34.88%  |
| Intel                           | 12        | 27.91%  |
| Qualcomm Atheros                | 7         | 16.28%  |
| Broadcom                        | 3         | 6.98%   |
| TP-Link                         | 2         | 4.65%   |
| Sierra Wireless                 | 1         | 2.33%   |
| Qualcomm Atheros Communications | 1         | 2.33%   |
| Marvell Technology Group        | 1         | 2.33%   |
| ASIX Electronics                | 1         | 2.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 9         | 17.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 3         | 5.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 5.88%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 3.92%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 3.92%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 3.92%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 1.96%   |
| TP-Link 802.11ac NIC                                                    | 1         | 1.96%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 1.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.96%   |
| Realtek 802.11n NIC                                                     | 1         | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.96%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.96%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 1.96%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 1         | 1.96%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 1.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.96%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                 | 1         | 1.96%   |
| Intel Wireless 8265 / 8275                                              | 1         | 1.96%   |
| Intel Wireless 7260                                                     | 1         | 1.96%   |
| Intel Wireless 3165                                                     | 1         | 1.96%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.96%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.96%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.96%   |
| Intel Centrino Wireless-N 105                                           | 1         | 1.96%   |
| Intel 82579V Gigabit Network Connection                                 | 1         | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 1         | 1.96%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                       | 1         | 1.96%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                        | 1         | 1.96%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 1         | 1.96%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 1.96%   |
| ASIX AX88179 Gigabit Ethernet                                           | 1         | 1.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 38.46%  |
| Qualcomm Atheros                | 6         | 23.08%  |
| Realtek Semiconductor           | 5         | 19.23%  |
| TP-Link                         | 2         | 7.69%   |
| Sierra Wireless                 | 1         | 3.85%   |
| Qualcomm Atheros Communications | 1         | 3.85%   |
| Broadcom                        | 1         | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 11.54%  |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 7.69%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 7.69%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 3.85%   |
| TP-Link 802.11ac NIC                                                    | 1         | 3.85%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 3.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 3.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 3.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 3.85%   |
| Realtek 802.11n NIC                                                     | 1         | 3.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 3.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 3.85%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 3.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 3.85%   |
| Intel Wireless 8265 / 8275                                              | 1         | 3.85%   |
| Intel Wireless 7260                                                     | 1         | 3.85%   |
| Intel Wireless 3165                                                     | 1         | 3.85%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 3.85%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 3.85%   |
| Intel Centrino Wireless-N 105                                           | 1         | 3.85%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 12        | 48%     |
| Intel                    | 5         | 20%     |
| Qualcomm Atheros         | 3         | 12%     |
| Broadcom                 | 3         | 12%     |
| Marvell Technology Group | 1         | 4%      |
| ASIX Electronics         | 1         | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 36%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 12%     |
| Intel 82577LM Gigabit Network Connection                          | 2         | 8%      |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 4%      |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 4%      |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 4%      |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 4%      |
| Intel Ethernet Connection I218-LM                                 | 1         | 4%      |
| Intel 82579V Gigabit Network Connection                           | 1         | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 4%      |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 4%      |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 4%      |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 4%      |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 4%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 25        | 51.02%  |
| WiFi     | 24        | 48.98%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 66.67%  |
| Ethernet | 10        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 16        | 55.17%  |
| 1     | 12        | 41.38%  |
| 0     | 1         | 3.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 18        | 62.07%  |
| Yes  | 11        | 37.93%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 4         | 26.67%  |
| Realtek Semiconductor           | 2         | 13.33%  |
| Qualcomm Atheros Communications | 2         | 13.33%  |
| Dell                            | 2         | 13.33%  |
| Unknown                         | 1         | 6.67%   |
| Foxconn / Hon Hai               | 1         | 6.67%   |
| Cambridge Silicon Radio         | 1         | 6.67%   |
| Broadcom                        | 1         | 6.67%   |
| ASUSTek Computer                | 1         | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 3         | 20%     |
| Realtek Bluetooth Radio                             | 2         | 13.33%  |
| Unknown Bluetooth Device                            | 1         | 6.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 6.67%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 6.67%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 6.67%   |
| Dell Wireless 365 Bluetooth                         | 1         | 6.67%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 6.67%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 6.67%   |
| ASUS ASUS USB-BT500                                 | 1         | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 22        | 73.33%  |
| AMD    | 5         | 16.67%  |
| Nvidia | 3         | 10%     |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 11.11%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 11.11%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 11.11%  |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 5.56%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 5.56%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 5.56%   |
| AMD High Definition Audio Controller                                       | 2         | 5.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 5.56%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 2.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 2.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 2.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 2.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 2.78%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 2.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 2.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 2.78%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 2.78%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 2.78%   |
| AMD FCH Azalia Controller                                                  | 1         | 2.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 29.63%  |
| SK hynix            | 5         | 18.52%  |
| Micron Technology   | 3         | 11.11%  |
| Unknown             | 2         | 7.41%   |
| Smart               | 2         | 7.41%   |
| Elpida              | 2         | 7.41%   |
| Unknown (ABCD)      | 1         | 3.7%    |
| Ramaxel Technology  | 1         | 3.7%    |
| PNY                 | 1         | 3.7%    |
| Kingston            | 1         | 3.7%    |
| Corsair             | 1         | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 6.67%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 3.33%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 3.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 3.33%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 1         | 3.33%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 3.33%   |
| SK hynix RAM HMT325S6EFR8A-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 3.33%   |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 3.33%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 1         | 3.33%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s             | 1         | 3.33%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 3.33%   |
| Samsung RAM Module 2GB DIMM DDR3 1066MT/s                        | 1         | 3.33%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 3.33%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s            | 1         | 3.33%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 3.33%   |
| Samsung RAM M391B5673FH0-CH9 2GB DIMM DDR3 1333MT/s              | 1         | 3.33%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s              | 1         | 3.33%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s              | 1         | 3.33%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                  | 1         | 3.33%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 3.33%   |
| PNY RAM Module 8192MB SODIMM DDR3 1600MT/s                       | 1         | 3.33%   |
| Micron RAM Module 2GB SODIMM DDR3 1600MT/s                       | 1         | 3.33%   |
| Micron RAM 8KTF51264HZ-1G6N1 4096MB SODIMM DDR3 1600MT/s         | 1         | 3.33%   |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s      | 1         | 3.33%   |
| Kingston RAM 99U5474-028.A 4GB DIMM DDR3 1333MT/s                | 1         | 3.33%   |
| Elpida RAM EBJ41EF8BCFA-DJ-F 4GB DIMM DDR3 1333MT/s              | 1         | 3.33%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 3.33%   |
| Elpida RAM EBJ21EE8BDFA-DJ-F 2GB DIMM DDR3 1333MT/s              | 1         | 3.33%   |
| Corsair RAM CMSX8GX3M1A1600C10 8192MB SODIMM DDR3 1600MT/s       | 1         | 3.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 12        | 57.14%  |
| LPDDR4 | 3         | 14.29%  |
| DDR4   | 3         | 14.29%  |
| SDRAM  | 2         | 9.52%   |
| DDR2   | 1         | 4.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 14        | 70%     |
| DIMM         | 4         | 20%     |
| Row Of Chips | 1         | 5%      |
| Unknown      | 1         | 5%      |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size | Computers | Percent |
|------|-----------|---------|
| 4096 | 10        | 41.67%  |
| 2048 | 9         | 37.5%   |
| 8192 | 3         | 12.5%   |
| 1024 | 2         | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 6         | 26.09%  |
| 2667  | 4         | 17.39%  |
| 1333  | 3         | 13.04%  |
| 2400  | 2         | 8.7%    |
| 1334  | 2         | 8.7%    |
| 4199  | 1         | 4.35%   |
| 1867  | 1         | 4.35%   |
| 1866  | 1         | 4.35%   |
| 1067  | 1         | 4.35%   |
| 1066  | 1         | 4.35%   |
| 533   | 1         | 4.35%   |

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
| Microdia                               | 3         | 17.65%  |
| Sunplus Innovation Technology          | 2         | 11.76%  |
| Lenovo                                 | 2         | 11.76%  |
| IMC Networks                           | 2         | 11.76%  |
| Chicony Electronics                    | 2         | 11.76%  |
| Silicon Motion                         | 1         | 5.88%   |
| Realtek Semiconductor                  | 1         | 5.88%   |
| Importek                               | 1         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5.88%   |
| ALi                                    | 1         | 5.88%   |
| Alcor Micro                            | 1         | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Sunplus Laptop Integrated WebCam HD                  | 1         | 5.88%   |
| Sunplus HD WebCam                                    | 1         | 5.88%   |
| Silicon Motion 300k Pixel Camera                     | 1         | 5.88%   |
| Realtek Lenovo EasyCamera                            | 1         | 5.88%   |
| Microdia Sonix USB 2.0 Camera                        | 1         | 5.88%   |
| Microdia Integrated Webcam                           | 1         | 5.88%   |
| Microdia 1.3 MPixel Integrated Webcam                | 1         | 5.88%   |
| Lenovo Integrated Webcam [R5U877]                    | 1         | 5.88%   |
| Lenovo Integrated Webcam                             | 1         | 5.88%   |
| Importek TOSHIBA Web Camera                          | 1         | 5.88%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 1         | 5.88%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 1         | 5.88%   |
| Chicony Integrated Camera                            | 1         | 5.88%   |
| Chicony EasyCamera                                   | 1         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101 | 1         | 5.88%   |
| ALi WebCam                                           | 1         | 5.88%   |
| Alcor Micro USB 2.0 WebCamera                        | 1         | 5.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Upek             | 2         | 50%     |
| Validity Sensors | 1         | 25%     |
| AuthenTec        | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 50%     |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 25%     |
| AuthenTec AES2810                                      | 1         | 25%     |

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
| 0     | 23        | 79.31%  |
| 1     | 6         | 20.69%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 4         | 66.67%  |
| Net/wireless       | 2         | 33.33%  |

