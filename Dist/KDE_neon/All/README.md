KDE neon - Hardware Trends
--------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/KDE_neon/Desktop/README.md) and [notebooks](/Dist/KDE_neon/Notebook/README.md).

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

![OS](./images/pie_chart/os_name.svg)

![OS](./images/line_chart/os_name.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| KDE neon 22.04 | 83        | 97.65%  |
| KDE neon 20.04 | 2         | 2.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE neon | 85        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.19.0-43-generic    | 47        | 55.29%  |
| 5.19.0-45-generic    | 23        | 27.06%  |
| 5.19.0-42-generic    | 3         | 3.53%   |
| 5.19.0-41-generic    | 3         | 3.53%   |
| 6.3.7-060307-generic | 1         | 1.18%   |
| 6.3.1-060301-generic | 1         | 1.18%   |
| 5.19.0-38-generic    | 1         | 1.18%   |
| 5.15.0-75-generic    | 1         | 1.18%   |
| 5.15.0-73-generic    | 1         | 1.18%   |
| 5.15.0-72-generic    | 1         | 1.18%   |
| 5.15.0-70-generic    | 1         | 1.18%   |
| 5.15.0-60-generic    | 1         | 1.18%   |
| 5.15.0-52-generic    | 1         | 1.18%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19.0  | 77        | 90.59%  |
| 5.15.0  | 6         | 7.06%   |
| 6.3.7   | 1         | 1.18%   |
| 6.3.1   | 1         | 1.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19    | 77        | 90.59%  |
| 5.15    | 6         | 7.06%   |
| 6.3     | 2         | 2.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 85        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| KDE5 | 83        | 97.65%  |
| KDE  | 2         | 2.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 75        | 88.24%  |
| Wayland | 10        | 11.76%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 64        | 75.29%  |
| SDDM    | 21        | 24.71%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang   | Computers | Percent |
|--------|-----------|---------|
| en_US  | 37        | 43.53%  |
| en_GB  | 13        | 15.29%  |
| es_MX  | 5         | 5.88%   |
| de_DE  | 4         | 4.71%   |
| es_ES  | 3         | 3.53%   |
| ru_RU  | 2         | 2.35%   |
| pt_BR  | 2         | 2.35%   |
| en_CA  | 2         | 2.35%   |
| C      | 2         | 2.35%   |
| tr_TR  | 1         | 1.18%   |
| pt_PT  | 1         | 1.18%   |
| nl_BE  | 1         | 1.18%   |
| ja_JP  | 1         | 1.18%   |
| it_IT  | 1         | 1.18%   |
| hsb_DE | 1         | 1.18%   |
| hr_HR  | 1         | 1.18%   |
| fr_FR  | 1         | 1.18%   |
| fr_CA  | 1         | 1.18%   |
| es_CL  | 1         | 1.18%   |
| en_ZA  | 1         | 1.18%   |
| en_PH  | 1         | 1.18%   |
| en_AU  | 1         | 1.18%   |
| de_AT  | 1         | 1.18%   |
| cs_CZ  | 1         | 1.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 70        | 82.35%  |
| EFI  | 15        | 17.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 76        | 89.41%  |
| Tmpfs   | 6         | 7.06%   |
| Overlay | 2         | 2.35%   |
| Xfs     | 1         | 1.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 62        | 72.94%  |
| GPT     | 21        | 24.71%  |
| MBR     | 2         | 2.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 79        | 92.94%  |
| Yes       | 6         | 7.06%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 89.41%  |
| Yes       | 9         | 10.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Hewlett-Packard                      | 16        | 18.82%  |
| Lenovo                               | 14        | 16.47%  |
| Dell                                 | 11        | 12.94%  |
| MSI                                  | 7         | 8.24%   |
| Gigabyte Technology                  | 6         | 7.06%   |
| ASUSTek Computer                     | 6         | 7.06%   |
| ASRock                               | 4         | 4.71%   |
| Apple                                | 4         | 4.71%   |
| Toshiba                              | 3         | 3.53%   |
| Acer                                 | 3         | 3.53%   |
| Positivo                             | 2         | 2.35%   |
| Intel                                | 2         | 2.35%   |
| Timi                                 | 1         | 1.18%   |
| Sony                                 | 1         | 1.18%   |
| Shenzhen Meigao Electronic Equipment | 1         | 1.18%   |
| Razer                                | 1         | 1.18%   |
| GEO                                  | 1         | 1.18%   |
| COM1                                 | 1         | 1.18%   |
| AZW                                  | 1         | 1.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                            | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| MSI MS-7A38                                     | 2         | 2.35%   |
| Toshiba Satellite P870                          | 1         | 1.18%   |
| Toshiba Satellite C855-233                      | 1         | 1.18%   |
| Toshiba dynabook Satellite B552/H               | 1         | 1.18%   |
| Timi RedmiBook Pro 15S                          | 1         | 1.18%   |
| Sony SVF1521J7EW                                | 1         | 1.18%   |
| Shenzhen Meigao Electronic Equipment UM773 Lite | 1         | 1.18%   |
| Razer Blade 17 (2022) - RZ09-0423               | 1         | 1.18%   |
| Positivo Q4128C-S                               | 1         | 1.18%   |
| Positivo Mobile                                 | 1         | 1.18%   |
| MSI MS-7C95                                     | 1         | 1.18%   |
| MSI MS-7C75                                     | 1         | 1.18%   |
| MSI MS-7B17                                     | 1         | 1.18%   |
| MSI GP72 7RDX                                   | 1         | 1.18%   |
| MSI Bravo 17 A4DDR                              | 1         | 1.18%   |
| Lenovo Y520-15IKBN 80WK                         | 1         | 1.18%   |
| Lenovo ThinkPad X270 20HMS12K00                 | 1         | 1.18%   |
| Lenovo ThinkPad W530 244723U                    | 1         | 1.18%   |
| Lenovo ThinkPad T440p 20AWS43W00                | 1         | 1.18%   |
| Lenovo ThinkPad T14 Gen 2i 20W000S3AD           | 1         | 1.18%   |
| Lenovo ThinkPad P51 20HJS02H00                  | 1         | 1.18%   |
| Lenovo ThinkPad E590 20NB001JUS                 | 1         | 1.18%   |
| Lenovo Legion Pro 5 16IRX8 82WK                 | 1         | 1.18%   |
| Lenovo IdeaPadFlex 5 15ITL05 82HT               | 1         | 1.18%   |
| Lenovo IdeaPad Z410 20292                       | 1         | 1.18%   |
| Lenovo IdeaPad Y510P 20217                      | 1         | 1.18%   |
| Lenovo IdeaPad 5 15ALC05 82LN                   | 1         | 1.18%   |
| Lenovo IdeaPad 110S-11IBR 80WG                  | 1         | 1.18%   |
| Lenovo IdeaCentre AIO 310-20IAP F0CL003YCL      | 1         | 1.18%   |
| Intel DQ77KB AAG81483-500                       | 1         | 1.18%   |
| Intel DP965LT AAD41694-301                      | 1         | 1.18%   |
| HP ProDesk 400 G4 SFF                           | 1         | 1.18%   |
| HP ProBook 440 G4                               | 1         | 1.18%   |
| HP Pavilion tp01-0030 Desktop Rfrbd PC          | 1         | 1.18%   |
| HP Pavilion m6                                  | 1         | 1.18%   |
| HP Pavilion g6                                  | 1         | 1.18%   |
| HP OMEN by Laptop 15-ce0xx                      | 1         | 1.18%   |
| HP Laptop 17-cn0xxx                             | 1         | 1.18%   |
| HP Laptop 17-ca0xxx                             | 1         | 1.18%   |
| HP Laptop 15-db0xxx                             | 1         | 1.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 6         | 7.06%   |
| Dell Precision                             | 5         | 5.88%   |
| Lenovo IdeaPad                             | 4         | 4.71%   |
| HP Laptop                                  | 4         | 4.71%   |
| HP Pavilion                                | 3         | 3.53%   |
| Toshiba Satellite                          | 2         | 2.35%   |
| MSI MS-7A38                                | 2         | 2.35%   |
| HP EliteBook                               | 2         | 2.35%   |
| HP Compaq                                  | 2         | 2.35%   |
| Dell Latitude                              | 2         | 2.35%   |
| Dell Inspiron                              | 2         | 2.35%   |
| ASUS TUF                                   | 2         | 2.35%   |
| ASUS PRIME                                 | 2         | 2.35%   |
| Acer Aspire                                | 2         | 2.35%   |
| Toshiba dynabook                           | 1         | 1.18%   |
| Timi RedmiBook                             | 1         | 1.18%   |
| Sony SVF1521J7EW                           | 1         | 1.18%   |
| Shenzhen Meigao Electronic Equipment UM773 | 1         | 1.18%   |
| Razer Blade                                | 1         | 1.18%   |
| Positivo Q4128C-S                          | 1         | 1.18%   |
| Positivo Mobile                            | 1         | 1.18%   |
| MSI MS-7C95                                | 1         | 1.18%   |
| MSI MS-7C75                                | 1         | 1.18%   |
| MSI MS-7B17                                | 1         | 1.18%   |
| MSI GP72                                   | 1         | 1.18%   |
| MSI Bravo                                  | 1         | 1.18%   |
| Lenovo Y520-15IKBN                         | 1         | 1.18%   |
| Lenovo Legion                              | 1         | 1.18%   |
| Lenovo IdeaPadFlex                         | 1         | 1.18%   |
| Lenovo IdeaCentre                          | 1         | 1.18%   |
| Intel DQ77KB                               | 1         | 1.18%   |
| Intel DP965LT                              | 1         | 1.18%   |
| HP ProDesk                                 | 1         | 1.18%   |
| HP ProBook                                 | 1         | 1.18%   |
| HP OMEN                                    | 1         | 1.18%   |
| HP ENVY                                    | 1         | 1.18%   |
| HP Elite                                   | 1         | 1.18%   |
| Gigabyte X570                              | 1         | 1.18%   |
| Gigabyte P55V6                             | 1         | 1.18%   |
| Gigabyte H310M                             | 1         | 1.18%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 12        | 14.12%  |
| 2020 | 11        | 12.94%  |
| 2021 | 9         | 10.59%  |
| 2013 | 9         | 10.59%  |
| 2017 | 7         | 8.24%   |
| 2012 | 7         | 8.24%   |
| 2019 | 6         | 7.06%   |
| 2016 | 5         | 5.88%   |
| 2022 | 4         | 4.71%   |
| 2015 | 4         | 4.71%   |
| 2011 | 3         | 3.53%   |
| 2023 | 2         | 2.35%   |
| 2007 | 2         | 2.35%   |
| 2014 | 1         | 1.18%   |
| 2010 | 1         | 1.18%   |
| 2009 | 1         | 1.18%   |
| 2008 | 1         | 1.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 50        | 58.82%  |
| Desktop     | 31        | 36.47%  |
| Convertible | 2         | 2.35%   |
| Mini pc     | 1         | 1.18%   |
| All in one  | 1         | 1.18%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 80        | 94.12%  |
| Enabled  | 5         | 5.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 85        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 18        | 21.18%  |
| 16.01-24.0  | 18        | 21.18%  |
| 8.01-16.0   | 15        | 17.65%  |
| 32.01-64.0  | 13        | 15.29%  |
| 3.01-4.0    | 12        | 14.12%  |
| 24.01-32.0  | 4         | 4.71%   |
| 64.01-256.0 | 4         | 4.71%   |
| 1.01-2.0    | 1         | 1.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 28        | 32.94%  |
| 1.01-2.0   | 21        | 24.71%  |
| 3.01-4.0   | 14        | 16.47%  |
| 4.01-8.0   | 11        | 12.94%  |
| 8.01-16.0  | 7         | 8.24%   |
| 24.01-32.0 | 2         | 2.35%   |
| 16.01-24.0 | 1         | 1.18%   |
| 0.01-0.5   | 1         | 1.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 39        | 45.88%  |
| 2      | 30        | 35.29%  |
| 3      | 8         | 9.41%   |
| 4      | 6         | 7.06%   |
| 10     | 1         | 1.18%   |
| 5      | 1         | 1.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 61        | 71.76%  |
| Yes       | 24        | 28.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 85.88%  |
| No        | 12        | 14.12%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 85.88%  |
| No        | 12        | 14.12%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 68.24%  |
| No        | 27        | 31.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 22        | 25.88%  |
| Brazil       | 5         | 5.88%   |
| Spain        | 4         | 4.71%   |
| Germany      | 4         | 4.71%   |
| UK           | 3         | 3.53%   |
| Canada       | 3         | 3.53%   |
| Australia    | 3         | 3.53%   |
| Tunisia      | 2         | 2.35%   |
| Thailand     | 2         | 2.35%   |
| Philippines  | 2         | 2.35%   |
| Norway       | 2         | 2.35%   |
| Mexico       | 2         | 2.35%   |
| India        | 2         | 2.35%   |
| France       | 2         | 2.35%   |
| Austria      | 2         | 2.35%   |
| Turkey       | 1         | 1.18%   |
| Switzerland  | 1         | 1.18%   |
| Sweden       | 1         | 1.18%   |
| South Africa | 1         | 1.18%   |
| Slovakia     | 1         | 1.18%   |
| Singapore    | 1         | 1.18%   |
| Russia       | 1         | 1.18%   |
| Romania      | 1         | 1.18%   |
| Portugal     | 1         | 1.18%   |
| Peru         | 1         | 1.18%   |
| Lithuania    | 1         | 1.18%   |
| Latvia       | 1         | 1.18%   |
| Japan        | 1         | 1.18%   |
| Italy        | 1         | 1.18%   |
| Ireland      | 1         | 1.18%   |
| Indonesia    | 1         | 1.18%   |
| Hungary      | 1         | 1.18%   |
| El Salvador  | 1         | 1.18%   |
| Czechia      | 1         | 1.18%   |
| Croatia      | 1         | 1.18%   |
| Colombia     | 1         | 1.18%   |
| Chile        | 1         | 1.18%   |
| Belgium      | 1         | 1.18%   |
| Bangladesh   | 1         | 1.18%   |
| Argentina    | 1         | 1.18%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City              | Computers | Percent |
|-------------------|-----------|---------|
| Wichita           | 2         | 2.35%   |
| Vienna            | 2         | 2.35%   |
| Tunis             | 2         | 2.35%   |
| Cleveland         | 2         | 2.35%   |
| Yokohama          | 1         | 1.18%   |
| Wilsdruff         | 1         | 1.18%   |
| Wil               | 1         | 1.18%   |
| Vyškov           | 1         | 1.18%   |
| Villeneuve-Loubet | 1         | 1.18%   |
| Valencia          | 1         | 1.18%   |
| Tønsberg         | 1         | 1.18%   |
| Tunja             | 1         | 1.18%   |
| Trujillo          | 1         | 1.18%   |
| Split             | 1         | 1.18%   |
| Singapore         | 1         | 1.18%   |
| Savannah          | 1         | 1.18%   |
| San Francisco     | 1         | 1.18%   |
| Saint-Jerome      | 1         | 1.18%   |
| Riga              | 1         | 1.18%   |
| Quincy            | 1         | 1.18%   |
| Preston           | 1         | 1.18%   |
| Philadelphia      | 1         | 1.18%   |
| Perth             | 1         | 1.18%   |
| Paris             | 1         | 1.18%   |
| Pamplona          | 1         | 1.18%   |
| Palmdale          | 1         | 1.18%   |
| Palmas            | 1         | 1.18%   |
| Oslo              | 1         | 1.18%   |
| Osasco            | 1         | 1.18%   |
| Oaxaca City       | 1         | 1.18%   |
| Normal            | 1         | 1.18%   |
| New York          | 1         | 1.18%   |
| Mumbai            | 1         | 1.18%   |
| Moscow            | 1         | 1.18%   |
| Mexico City       | 1         | 1.18%   |
| Mažeikiai        | 1         | 1.18%   |
| Mannheim          | 1         | 1.18%   |
| Madrid            | 1         | 1.18%   |
| Longmont          | 1         | 1.18%   |
| Long Beach        | 1         | 1.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 18        | 21     | 12.59%  |
| WDC                         | 17        | 17     | 11.89%  |
| Seagate                     | 17        | 26     | 11.89%  |
| Toshiba                     | 11        | 11     | 7.69%   |
| Kingston                    | 11        | 12     | 7.69%   |
| SanDisk                     | 8         | 9      | 5.59%   |
| Unknown                     | 6         | 6      | 4.2%    |
| Phison Electronics          | 5         | 5      | 3.5%    |
| Crucial                     | 5         | 6      | 3.5%    |
| SK hynix                    | 4         | 4      | 2.8%    |
| SPCC                        | 3         | 4      | 2.1%    |
| Realtek Semiconductor       | 3         | 3      | 2.1%    |
| HGST                        | 3         | 3      | 2.1%    |
| China                       | 3         | 3      | 2.1%    |
| SABRENT                     | 2         | 2      | 1.4%    |
| LITEON                      | 2         | 2      | 1.4%    |
| KIOXIA                      | 2         | 2      | 1.4%    |
| Apple                       | 2         | 3      | 1.4%    |
| ADATA Technology            | 2         | 3      | 1.4%    |
| USB3.0                      | 1         | 2      | 0.7%    |
| Silicon Motion              | 1         | 1      | 0.7%    |
| RX7                         | 1         | 1      | 0.7%    |
| PNY                         | 1         | 1      | 0.7%    |
| Patriot                     | 1         | 1      | 0.7%    |
| Micron/Crucial Technology   | 1         | 1      | 0.7%    |
| Micron Technology           | 1         | 1      | 0.7%    |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.7%    |
| LITEON C                    | 1         | 1      | 0.7%    |
| Lenovo                      | 1         | 1      | 0.7%    |
| KIOXIA-EXCERIA              | 1         | 1      | 0.7%    |
| Kingston Technology Company | 1         | 1      | 0.7%    |
| KingSpec                    | 1         | 1      | 0.7%    |
| KingFast                    | 1         | 1      | 0.7%    |
| Intel                       | 1         | 1      | 0.7%    |
| INNOVATION IT               | 1         | 1      | 0.7%    |
| Inland                      | 1         | 1      | 0.7%    |
| Hitachi                     | 1         | 1      | 0.7%    |
| A-DATA Technology           | 1         | 1      | 0.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                                            | 3         | 1.97%   |
| Seagate ST2000DM008-2FR102 2TB                                    | 3         | 1.97%   |
| Seagate ST1000DM010-2EP102 1TB                                    | 3         | 1.97%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                                | 3         | 1.97%   |
| Phison E12 NVMe Controller 1TB                                    | 3         | 1.97%   |
| Kingston SA400S37240G 240GB SSD                                   | 3         | 1.97%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                                  | 2         | 1.32%   |
| Toshiba MQ01ABD100 1TB                                            | 2         | 1.32%   |
| Seagate ST2000LM007-1R8174 2TB                                    | 2         | 1.32%   |
| Seagate ST1000LM035-1RK172 1TB                                    | 2         | 1.32%   |
| Samsung SSD 980 1TB                                               | 2         | 1.32%   |
| Samsung SSD 860 EVO 500GB                                         | 2         | 1.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB               | 2         | 1.32%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB               | 2         | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB                | 2         | 1.32%   |
| Realtek RTS5763DL NVMe SSD Controller 512GB                       | 2         | 1.32%   |
| LITEON L8H-256V2G-HP 256GB SSD                                    | 2         | 1.32%   |
| Kingston SA400S37480G 480GB SSD                                   | 2         | 1.32%   |
| Kingston SA400S37120G 120GB SSD                                   | 2         | 1.32%   |
| HGST HTS721010A9E630 1TB                                          | 2         | 1.32%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 512GB | 2         | 1.32%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                                  | 1         | 0.66%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                                  | 1         | 0.66%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                  | 1         | 0.66%   |
| WDC WDBNCE5000PNC 500GB SSD                                       | 1         | 0.66%   |
| WDC WD5000BPVT-24HXZT3 500GB                                      | 1         | 0.66%   |
| WDC WD5000BEVT-60ZAT1 500GB                                       | 1         | 0.66%   |
| WDC WD50 00LPLX-60ZNT 500GB                                       | 1         | 0.66%   |
| WDC WD3200AAKS-00G3A0 320GB                                       | 1         | 0.66%   |
| WDC WD30EZRZ-00GXCB0 3TB                                          | 1         | 0.66%   |
| WDC WD20EARX-00PASB0 2TB                                          | 1         | 0.66%   |
| WDC WD10SPZX-22Z10T0 1TB                                          | 1         | 0.66%   |
| WDC WD10JPVX-22JC3T0 1TB                                          | 1         | 0.66%   |
| WDC WD10JPCX-24UE4T0 1TB                                          | 1         | 0.66%   |
| WDC WD10EZEX-75WN4A1 1TB                                          | 1         | 0.66%   |
| WDC WD10EZEX-60M2NA0 1TB                                          | 1         | 0.66%   |
| USB3.0 Disk 500GB                                                 | 1         | 0.66%   |
| Unknown MMC Card  32GB                                            | 1         | 0.66%   |
| Unknown MMC Card  256GB                                           | 1         | 0.66%   |
| Unknown MMC Card  128GB                                           | 1         | 0.66%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 26     | 39.53%  |
| WDC                 | 11        | 11     | 25.58%  |
| Toshiba             | 8         | 8      | 18.6%   |
| HGST                | 3         | 3      | 6.98%   |
| USB3.0              | 1         | 2      | 2.33%   |
| Samsung Electronics | 1         | 1      | 2.33%   |
| Hitachi             | 1         | 1      | 2.33%   |
| Apple               | 1         | 1      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 10        | 11     | 21.74%  |
| WDC                 | 6         | 6      | 13.04%  |
| Samsung Electronics | 6         | 6      | 13.04%  |
| Crucial             | 4         | 5      | 8.7%    |
| SPCC                | 3         | 4      | 6.52%   |
| China               | 3         | 3      | 6.52%   |
| Toshiba             | 2         | 2      | 4.35%   |
| SanDisk             | 2         | 2      | 4.35%   |
| LITEON              | 2         | 2      | 4.35%   |
| PNY                 | 1         | 1      | 2.17%   |
| Patriot             | 1         | 1      | 2.17%   |
| LITEON C            | 1         | 1      | 2.17%   |
| KIOXIA-EXCERIA      | 1         | 1      | 2.17%   |
| KingSpec            | 1         | 1      | 2.17%   |
| INNOVATION IT       | 1         | 1      | 2.17%   |
| Inland              | 1         | 1      | 2.17%   |
| A-DATA Technology   | 1         | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 39        | 51     | 31.71%  |
| SSD     | 39        | 49     | 31.71%  |
| HDD     | 36        | 53     | 29.27%  |
| MMC     | 6         | 6      | 4.88%   |
| Unknown | 3         | 3      | 2.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 63        | 90     | 54.31%  |
| NVMe | 39        | 50     | 33.62%  |
| SAS  | 8         | 16     | 6.9%    |
| MMC  | 6         | 6      | 5.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 42        | 54     | 51.22%  |
| 0.51-1.0   | 23        | 25     | 28.05%  |
| 1.01-2.0   | 13        | 14     | 15.85%  |
| 3.01-4.0   | 2         | 2      | 2.44%   |
| 2.01-3.0   | 1         | 1      | 1.22%   |
| 4.01-10.0  | 1         | 6      | 1.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 25        | 29.41%  |
| 501-1000       | 17        | 20%     |
| 251-500        | 16        | 18.82%  |
| More than 3000 | 7         | 8.24%   |
| 1001-2000      | 6         | 7.06%   |
| 51-100         | 5         | 5.88%   |
| 1-20           | 4         | 4.71%   |
| 2001-3000      | 2         | 2.35%   |
| Unknown        | 2         | 2.35%   |
| 21-50          | 1         | 1.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 34        | 40%     |
| 51-100         | 12        | 14.12%  |
| 21-50          | 10        | 11.76%  |
| 101-250        | 10        | 11.76%  |
| 251-500        | 6         | 7.06%   |
| More than 3000 | 4         | 4.71%   |
| 1001-2000      | 4         | 4.71%   |
| 501-1000       | 3         | 3.53%   |
| Unknown        | 2         | 2.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD20EARX-00PASB0 2TB        | 1         | 1      | 25%     |
| WDC WD10SPZX-22Z10T0 1TB        | 1         | 1      | 25%     |
| Seagate ST1000LM035-1RK172 1TB  | 1         | 1      | 25%     |
| Samsung Electronics HD154UI 1TB | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 50%     |
| Seagate             | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 50%     |
| Seagate             | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 100%    |

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
| Detected | 73        | 137    | 79.35%  |
| Works    | 15        | 21     | 16.3%   |
| Malfunc  | 4         | 4      | 4.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 51        | 42.5%   |
| AMD                          | 23        | 19.17%  |
| Samsung Electronics          | 12        | 10%     |
| SanDisk                      | 6         | 5%      |
| Phison Electronics           | 5         | 4.17%   |
| SK hynix                     | 4         | 3.33%   |
| Realtek Semiconductor        | 3         | 2.5%    |
| Toshiba America Info Systems | 2         | 1.67%   |
| Micron/Crucial Technology    | 2         | 1.67%   |
| Kingston Technology Company  | 2         | 1.67%   |
| ADATA Technology             | 2         | 1.67%   |
| Silicon Motion               | 1         | 0.83%   |
| Nvidia                       | 1         | 0.83%   |
| Micron Technology            | 1         | 0.83%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.83%   |
| Marvell Technology Group     | 1         | 0.83%   |
| Lenovo                       | 1         | 0.83%   |
| KIOXIA                       | 1         | 0.83%   |
| Apple                        | 1         | 0.83%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 14        | 10.53%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 5.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 4.51%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 3.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 3.76%   |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 3.76%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 3.01%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 3.01%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 2.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 2.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 2.26%   |
| Phison E12 NVMe Controller                                                     | 3         | 2.26%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 2.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 2.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.5%    |
| Realtek RTS5763DL NVMe SSD Controller                                          | 2         | 1.5%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 1.5%    |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.5%    |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 1.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.5%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.5%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 1.5%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2         | 1.5%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.75%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.75%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.75%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.75%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.75%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 1         | 0.75%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.75%   |
| Realtek NVMe Controller                                                        | 1         | 0.75%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.75%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.75%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.75%   |
| Micron NVMe Storage Controller                                                 | 1         | 0.75%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1         | 0.75%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                      | 1         | 0.75%   |
| Lenovo Non-Volatile memory controller                                          | 1         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 66        | 55.46%  |
| NVMe | 39        | 32.77%  |
| RAID | 7         | 5.88%   |
| IDE  | 6         | 5.04%   |
| SAS  | 1         | 0.84%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 61        | 71.76%  |
| AMD    | 24        | 28.24%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 2.35%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 2         | 2.35%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 2.35%   |
| Intel Xeon E-2186G CPU @ 3.80GHz            | 1         | 1.18%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz          | 1         | 1.18%   |
| Intel Xeon CPU 5150 @ 2.66GHz               | 1         | 1.18%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz      | 1         | 1.18%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 1.18%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz            | 1         | 1.18%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.18%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1         | 1.18%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 1         | 1.18%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.18%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 1.18%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.18%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.18%   |
| Intel Core i7-3820QM CPU @ 2.70GHz          | 1         | 1.18%   |
| Intel Core i7-3770T CPU @ 2.50GHz           | 1         | 1.18%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.18%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1         | 1.18%   |
| Intel Core i7-2820QM CPU @ 2.30GHz          | 1         | 1.18%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 1         | 1.18%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 1.18%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.18%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 1.18%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 1.18%   |
| Intel Core i5-7267U CPU @ 3.10GHz           | 1         | 1.18%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.18%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1         | 1.18%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.18%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 1.18%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.18%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 1.18%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.18%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 1.18%   |
| Intel Core i3-9100F CPU @ 3.60GHz           | 1         | 1.18%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 1         | 1.18%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 1.18%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 1         | 1.18%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 1.18%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 17        | 20%     |
| Intel Core i5           | 15        | 17.65%  |
| Other                   | 9         | 10.59%  |
| AMD Ryzen 7             | 9         | 10.59%  |
| Intel Core i3           | 7         | 8.24%   |
| AMD Ryzen 5             | 6         | 7.06%   |
| Intel Celeron           | 5         | 5.88%   |
| Intel Xeon              | 3         | 3.53%   |
| AMD Ryzen 9             | 3         | 3.53%   |
| AMD Ryzen 3             | 2         | 2.35%   |
| Intel Pentium Gold      | 1         | 1.18%   |
| Intel Pentium Dual-Core | 1         | 1.18%   |
| Intel Core m5           | 1         | 1.18%   |
| Intel Core 2 Quad       | 1         | 1.18%   |
| Intel Core 2 Duo        | 1         | 1.18%   |
| Intel Atom              | 1         | 1.18%   |
| AMD FX                  | 1         | 1.18%   |
| AMD A6                  | 1         | 1.18%   |
| AMD A10                 | 1         | 1.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 33        | 38.82%  |
| 2      | 24        | 28.24%  |
| 8      | 14        | 16.47%  |
| 6      | 9         | 10.59%  |
| 12     | 2         | 2.35%   |
| 24     | 1         | 1.18%   |
| 14     | 1         | 1.18%   |
| 1      | 1         | 1.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 84        | 98.82%  |
| 2      | 1         | 1.18%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 64        | 75.29%  |
| 1      | 21        | 24.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 85        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 82.35%  |
| 0x806c1    | 3         | 3.53%   |
| 0x506e3    | 3         | 3.53%   |
| 0xa0671    | 1         | 1.18%   |
| 0x406e3    | 1         | 1.18%   |
| 0x306c3    | 1         | 1.18%   |
| 0x0a601203 | 1         | 1.18%   |
| 0x0a50000c | 1         | 1.18%   |
| 0x0a404102 | 1         | 1.18%   |
| 0x08600106 | 1         | 1.18%   |
| 0x06006705 | 1         | 1.18%   |
| 0x06000852 | 1         | 1.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 16.47%  |
| Skylake       | 9         | 10.59%  |
| IvyBridge     | 9         | 10.59%  |
| Zen 3         | 7         | 8.24%   |
| Zen 2         | 7         | 8.24%   |
| Unknown       | 6         | 7.06%   |
| Haswell       | 5         | 5.88%   |
| TigerLake     | 4         | 4.71%   |
| SandyBridge   | 3         | 3.53%   |
| Piledriver    | 3         | 3.53%   |
| Zen           | 2         | 2.35%   |
| Silvermont    | 2         | 2.35%   |
| Penryn        | 2         | 2.35%   |
| Icelake       | 2         | 2.35%   |
| Goldmont      | 2         | 2.35%   |
| Core          | 2         | 2.35%   |
| CometLake     | 2         | 2.35%   |
| Zen+          | 1         | 1.18%   |
| Westmere      | 1         | 1.18%   |
| Goldmont plus | 1         | 1.18%   |
| Excavator     | 1         | 1.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 48        | 44.86%  |
| Nvidia | 38        | 35.51%  |
| AMD    | 21        | 19.63%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 5.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 4.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 3.7%    |
| Intel HD Graphics 530                                                                    | 4         | 3.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 2.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.78%   |
| AMD Renoir                                                                               | 3         | 2.78%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 2.78%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 2         | 1.85%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 1.85%   |
| Intel HD Graphics 630                                                                    | 2         | 1.85%   |
| Intel HD Graphics 620                                                                    | 2         | 1.85%   |
| Intel HD Graphics 500                                                                    | 2         | 1.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.85%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2         | 1.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.93%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                     | 1         | 0.93%   |
| Nvidia TU116 [GeForce GTX 1650]                                                          | 1         | 0.93%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.93%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 0.93%   |
| Nvidia TU104GL [Quadro RTX 4000]                                                         | 1         | 0.93%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.93%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1         | 0.93%   |
| Nvidia GP107GL [Quadro P400]                                                             | 1         | 0.93%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.93%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                             | 1         | 0.93%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.93%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 0.93%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.93%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.93%   |
| Nvidia GM107GL [Quadro K620]                                                             | 1         | 0.93%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.93%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                                     | 1         | 0.93%   |
| Nvidia GK107M [GeForce GT 755M]                                                          | 1         | 0.93%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 1         | 0.93%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 1         | 0.93%   |
| Nvidia GK104GLM [Quadro K4100M]                                                          | 1         | 0.93%   |
| Nvidia GK104GL [Quadro K5000]                                                            | 1         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 26        | 30.59%  |
| Intel + Nvidia | 20        | 23.53%  |
| 1 x AMD        | 19        | 22.35%  |
| 1 x Nvidia     | 18        | 21.18%  |
| 2 x AMD        | 1         | 1.18%   |
| Intel + AMD    | 1         | 1.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 72        | 84.71%  |
| Proprietary | 13        | 15.29%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 68        | 80%     |
| 1.01-2.0   | 4         | 4.71%   |
| 0.01-0.5   | 4         | 4.71%   |
| 5.01-6.0   | 3         | 3.53%   |
| 7.01-8.0   | 2         | 2.35%   |
| 3.01-4.0   | 2         | 2.35%   |
| 8.01-16.0  | 1         | 1.18%   |
| 0.51-1.0   | 1         | 1.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 14        | 13.59%  |
| Samsung Electronics     | 13        | 12.62%  |
| Goldstar                | 10        | 9.71%   |
| Chimei Innolux          | 9         | 8.74%   |
| LG Display              | 8         | 7.77%   |
| Dell                    | 8         | 7.77%   |
| BOE                     | 8         | 7.77%   |
| Hewlett-Packard         | 6         | 5.83%   |
| ASUSTek Computer        | 3         | 2.91%   |
| Apple                   | 3         | 2.91%   |
| Acer                    | 3         | 2.91%   |
| Philips                 | 2         | 1.94%   |
| ONN                     | 2         | 1.94%   |
| BenQ                    | 2         | 1.94%   |
| AOC                     | 2         | 1.94%   |
| TMX                     | 1         | 0.97%   |
| Sceptre Tech            | 1         | 0.97%   |
| Newskill                | 1         | 0.97%   |
| LGD                     | 1         | 0.97%   |
| Lenovo                  | 1         | 0.97%   |
| Iiyama                  | 1         | 0.97%   |
| HUAWEI                  | 1         | 0.97%   |
| Grundig                 | 1         | 0.97%   |
| CSO                     | 1         | 0.97%   |
| Chi Mei Optoelectronics | 1         | 0.97%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| ONN ONA24HB19T01 ONN0101 1920x1080 517x323mm 24.0-inch                 | 2         | 1.87%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 1.87%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch       | 2         | 1.87%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch        | 2         | 1.87%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch                | 1         | 0.93%   |
| Sceptre Tech Sceptre K32 SPT0C98 1920x1080 700x390mm 31.5-inch         | 1         | 0.93%   |
| Samsung Electronics SyncMaster SAM043F 1920x1200 518x324mm 24.1-inch   | 1         | 0.93%   |
| Samsung Electronics SyncMaster SAM0423 1920x1080                       | 1         | 0.93%   |
| Samsung Electronics SyncMaster SAM0161 1280x1024 338x270mm 17.0-inch   | 1         | 0.93%   |
| Samsung Electronics SA300/SA350 SAM078A 1366x768 410x230mm 18.5-inch   | 1         | 0.93%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 1         | 0.93%   |
| Samsung Electronics S24C650 SAM0B15 1920x1200 518x324mm 24.1-inch      | 1         | 0.93%   |
| Samsung Electronics S20D300 SAM0B3A 1600x900 430x240mm 19.4-inch       | 1         | 0.93%   |
| Samsung Electronics Odyssey G40B SAM727E 1920x1080 597x336mm 27.0-inch | 1         | 0.93%   |
| Samsung Electronics LS49AG95 SAM71AC 3840x1080 1193x336mm 48.8-inch    | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch   | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC270F 1366x768 344x193mm 15.5-inch   | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SAM07D0 1360x768 700x390mm 31.5-inch   | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SAM0503 1920x1080                      | 1         | 0.93%   |
| Samsung Electronics 173HT02-T01 SEC5044 1920x1080 382x215mm 17.3-inch  | 1         | 0.93%   |
| Philips WXGA TV (3) PHL1E52 1360x768 708x398mm 32.0-inch               | 1         | 0.93%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch                | 1         | 0.93%   |
| Newskill RGB-27QHD NSL2711 2560x1440 530x280mm 23.6-inch               | 1         | 0.93%   |
| LGD LCD Monitor 1920x1080                                              | 1         | 0.93%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch           | 1         | 0.93%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch           | 1         | 0.93%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch           | 1         | 0.93%   |
| LG Display LCD Monitor LGD04A5 1920x1280 253x169mm 12.0-inch           | 1         | 0.93%   |
| LG Display LCD Monitor LGD0457 1920x1080 345x194mm 15.6-inch           | 1         | 0.93%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch            | 1         | 0.93%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch           | 1         | 0.93%   |
| LG Display LCD Monitor LGD0215 1920x1080 345x194mm 15.6-inch           | 1         | 0.93%   |
| Lenovo LEN-AIO310-E LEN0017 1440x900 520x320mm 24.0-inch               | 1         | 0.93%   |
| Iiyama XB2776QS-B1 IVM660E 2560x1440 597x336mm 27.0-inch               | 1         | 0.93%   |
| HUAWEI SSN-24 HWV6E4E 1920x1080 527x296mm 23.8-inch                    | 1         | 0.93%   |
| Hewlett-Packard w1907 HWP26A3 1440x900 408x255mm 18.9-inch             | 1         | 0.93%   |
| Hewlett-Packard V270 HPN3521 1920x1080 598x336mm 27.0-inch             | 1         | 0.93%   |
| Hewlett-Packard LV2311 HWP300E 1920x1080 510x287mm 23.0-inch           | 1         | 0.93%   |
| Hewlett-Packard E27u G4 HPN36EE 2560x1440 597x336mm 27.0-inch          | 1         | 0.93%   |
| Hewlett-Packard E231 HWP3065 1920x1080 509x286mm 23.0-inch             | 1         | 0.93%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 44        | 46.81%  |
| 1366x768 (WXGA)   | 14        | 14.89%  |
| 2560x1440 (QHD)   | 9         | 9.57%   |
| 3840x2160 (4K)    | 7         | 7.45%   |
| 1600x900 (HD+)    | 3         | 3.19%   |
| 1280x1024 (SXGA)  | 3         | 3.19%   |
| 2560x1080         | 2         | 2.13%   |
| 1440x900 (WXGA+)  | 2         | 2.13%   |
| 1360x768          | 2         | 2.13%   |
| 1280x800 (WXGA)   | 2         | 2.13%   |
| 3840x1080         | 1         | 1.06%   |
| 3200x2000         | 1         | 1.06%   |
| 2880x1800         | 1         | 1.06%   |
| 2560x1600         | 1         | 1.06%   |
| 1920x1280         | 1         | 1.06%   |
| 1920x1200 (WUXGA) | 1         | 1.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 22        | 22%     |
| 27      | 11        | 11%     |
| 17      | 11        | 11%     |
| 24      | 10        | 10%     |
| 23      | 6         | 6%      |
| 13      | 6         | 6%      |
| 31      | 5         | 5%      |
| 21      | 4         | 4%      |
| 19      | 4         | 4%      |
| 14      | 4         | 4%      |
| 12      | 3         | 3%      |
| Unknown | 3         | 3%      |
| 34      | 2         | 2%      |
| 18      | 2         | 2%      |
| 11      | 2         | 2%      |
| 54      | 1         | 1%      |
| 48      | 1         | 1%      |
| 32      | 1         | 1%      |
| 25      | 1         | 1%      |
| 16      | 1         | 1%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 33.33%  |
| 501-600     | 23        | 23.96%  |
| 351-400     | 10        | 10.42%  |
| 401-500     | 9         | 9.38%   |
| 201-300     | 8         | 8.33%   |
| 601-700     | 6         | 6.25%   |
| 701-800     | 3         | 3.13%   |
| Unknown     | 3         | 3.13%   |
| 1001-1500   | 2         | 2.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 71        | 80.68%  |
| 16/10   | 9         | 10.23%  |
| 5/4     | 3         | 3.41%   |
| 21/9    | 2         | 2.27%   |
| 32/9    | 1         | 1.14%   |
| 3/2     | 1         | 1.14%   |
| Unknown | 1         | 1.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 22        | 22%     |
| 201-250        | 16        | 16%     |
| 301-350        | 11        | 11%     |
| 81-90          | 9         | 9%      |
| 121-130        | 9         | 9%      |
| 351-500        | 8         | 8%      |
| 251-300        | 5         | 5%      |
| 151-200        | 4         | 4%      |
| 141-150        | 4         | 4%      |
| 61-70          | 3         | 3%      |
| Unknown        | 3         | 3%      |
| 51-60          | 2         | 2%      |
| More than 1000 | 1         | 1%      |
| 71-80          | 1         | 1%      |
| 111-120        | 1         | 1%      |
| 501-1000       | 1         | 1%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 29        | 31.18%  |
| 101-120       | 25        | 26.88%  |
| 51-100        | 25        | 26.88%  |
| 161-240       | 6         | 6.45%   |
| More than 240 | 3         | 3.23%   |
| Unknown       | 3         | 3.23%   |
| 1-50          | 2         | 2.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 62        | 72.94%  |
| 2     | 18        | 21.18%  |
| 3     | 4         | 4.71%   |
| 4     | 1         | 1.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 53        | 39.55%  |
| Intel                           | 44        | 32.84%  |
| Qualcomm Atheros                | 8         | 5.97%   |
| Broadcom                        | 7         | 5.22%   |
| Ralink Technology               | 5         | 3.73%   |
| MediaTek                        | 4         | 2.99%   |
| ASIX Electronics                | 4         | 2.99%   |
| TP-Link                         | 1         | 0.75%   |
| Qualcomm Atheros Communications | 1         | 0.75%   |
| QNAP System                     | 1         | 0.75%   |
| Nvidia                          | 1         | 0.75%   |
| Linksys                         | 1         | 0.75%   |
| JMicron Technology              | 1         | 0.75%   |
| Fibocom                         | 1         | 0.75%   |
| D-Link                          | 1         | 0.75%   |
| Broadcom Limited                | 1         | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 18.87%  |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 4.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 3.14%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 3.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 3.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.52%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 2.52%   |
| Intel Wireless 8260                                               | 4         | 2.52%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 2.52%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.89%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 1.26%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 2         | 1.26%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2         | 1.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.26%   |
| Realtek 802.11ac NIC                                              | 2         | 1.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.26%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2         | 1.26%   |
| Intel Wireless-AC 9260                                            | 2         | 1.26%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.26%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.26%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.26%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 1.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.26%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.26%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.63%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1         | 0.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.63%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.63%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.63%   |
| Ralink RT5572 Wireless Adapter                                    | 1         | 0.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 34        | 44.74%  |
| Realtek Semiconductor           | 16        | 21.05%  |
| Broadcom                        | 7         | 9.21%   |
| Qualcomm Atheros                | 6         | 7.89%   |
| Ralink Technology               | 5         | 6.58%   |
| MediaTek                        | 4         | 5.26%   |
| TP-Link                         | 1         | 1.32%   |
| Qualcomm Atheros Communications | 1         | 1.32%   |
| Fibocom                         | 1         | 1.32%   |
| D-Link                          | 1         | 1.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 5         | 6.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 4         | 5.19%   |
| Ralink MT7601U Wireless Adapter                               | 4         | 5.19%   |
| Intel Wireless 8260                                           | 4         | 5.19%   |
| Intel Wireless 8265 / 8275                                    | 3         | 3.9%    |
| Realtek RTL8723DE Wireless Network Adapter                    | 2         | 2.6%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter               | 2         | 2.6%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 2         | 2.6%    |
| Realtek 802.11ac NIC                                          | 2         | 2.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 2         | 2.6%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 2         | 2.6%    |
| Intel Wireless-AC 9260                                        | 2         | 2.6%    |
| Intel Wi-Fi 6 AX201                                           | 2         | 2.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 2         | 2.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 2         | 2.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 2.6%    |
| Intel Cannon Lake PCH CNVi WiFi                               | 2         | 2.6%    |
| Broadcom BCM43142 802.11b/g/n                                 | 2         | 2.6%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 1         | 1.3%    |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 1         | 1.3%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 1         | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 1.3%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 1         | 1.3%    |
| Realtek RTL8191SEvB Wireless LAN Controller                   | 1         | 1.3%    |
| Ralink RT5572 Wireless Adapter                                | 1         | 1.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 1         | 1.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 1.3%    |
| Qualcomm Atheros AR9271 802.11n                               | 1         | 1.3%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1         | 1.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 1.3%    |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter            | 1         | 1.3%    |
| Intel Wireless 7265                                           | 1         | 1.3%    |
| Intel Wireless 7260                                           | 1         | 1.3%    |
| Intel Wireless 3160                                           | 1         | 1.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 1         | 1.3%    |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 1         | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 1.3%    |
| Intel Centrino Ultimate-N 6300                                | 1         | 1.3%    |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                 | 1         | 1.3%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 45        | 56.25%  |
| Intel                 | 22        | 27.5%   |
| ASIX Electronics      | 4         | 5%      |
| Qualcomm Atheros      | 3         | 3.75%   |
| QNAP System           | 1         | 1.25%   |
| Nvidia                | 1         | 1.25%   |
| Linksys               | 1         | 1.25%   |
| JMicron Technology    | 1         | 1.25%   |
| Broadcom Limited      | 1         | 1.25%   |
| Broadcom              | 1         | 1.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 36.59%  |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 8.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 6.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 6.1%    |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 4.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.44%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.44%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.22%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.22%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.22%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.22%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.22%   |
| QNAP System QNAP QNA-UC5G1T USB to 5GbE Adapter                   | 1         | 1.22%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.22%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 1.22%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.22%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.22%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.22%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.22%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.22%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.22%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.22%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.22%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.22%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.22%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.22%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.22%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.22%   |
| Intel 82566DC Gigabit Network Connection                          | 1         | 1.22%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1         | 1.22%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.22%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 73        | 50%     |
| Ethernet | 73        | 50%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 47        | 52.22%  |
| Ethernet | 43        | 47.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 48        | 56.47%  |
| 1     | 32        | 37.65%  |
| 3     | 3         | 3.53%   |
| 0     | 2         | 2.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 51        | 60%     |
| Yes  | 34        | 40%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 50%     |
| Realtek Semiconductor           | 9         | 15.52%  |
| Foxconn / Hon Hai               | 3         | 5.17%   |
| Toshiba                         | 2         | 3.45%   |
| Qualcomm Atheros Communications | 2         | 3.45%   |
| MediaTek                        | 2         | 3.45%   |
| Cambridge Silicon Radio         | 2         | 3.45%   |
| Apple                           | 2         | 3.45%   |
| Opticis                         | 1         | 1.72%   |
| Lite-On Technology              | 1         | 1.72%   |
| Integrated System Solution      | 1         | 1.72%   |
| Hewlett-Packard                 | 1         | 1.72%   |
| Foxconn International           | 1         | 1.72%   |
| Broadcom                        | 1         | 1.72%   |
| Unknown                         | 1         | 1.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 20.69%  |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 8.62%   |
| Intel AX200 Bluetooth                               | 5         | 8.62%   |
| Realtek Bluetooth Radio                             | 4         | 6.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 5.17%   |
| Intel AX201 Bluetooth                               | 3         | 5.17%   |
| Toshiba RT Bluetooth Radio                          | 2         | 3.45%   |
| MediaTek Wireless_Device                            | 2         | 3.45%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 3.45%   |
| Intel Bluetooth Device                              | 2         | 3.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 3.45%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.72%   |
| Opticis Bluetooth Radio                             | 1         | 1.72%   |
| Lite-On Bluetooth Device                            | 1         | 1.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.72%   |
| Integrated System Solution Bluetooth Device         | 1         | 1.72%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.72%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.72%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 1.72%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.72%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 1.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.72%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.72%   |
| Apple Bluetooth Host Controller                     | 1         | 1.72%   |
| Unknown                                             | 1         | 1.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 60        | 44.12%  |
| Nvidia                | 29        | 21.32%  |
| AMD                   | 25        | 18.38%  |
| Logitech              | 4         | 2.94%   |
| C-Media Electronics   | 3         | 2.21%   |
| Realtek Semiconductor | 2         | 1.47%   |
| Corsair               | 2         | 1.47%   |
| Sony                  | 1         | 0.74%   |
| Scarlett              | 1         | 0.74%   |
| Razer USA             | 1         | 0.74%   |
| Plantronics           | 1         | 0.74%   |
| Medeli Electronics    | 1         | 0.74%   |
| JMTek                 | 1         | 0.74%   |
| GN Netcom             | 1         | 0.74%   |
| Fry's Electronics     | 1         | 0.74%   |
| Creative Technology   | 1         | 0.74%   |
| Creative Labs         | 1         | 0.74%   |
| ASUSTek Computer      | 1         | 0.74%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 6.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 5.59%   |
| Intel Sunrise Point-LP HD Audio                                            | 8         | 4.97%   |
| AMD Starship/Matisse HD Audio Controller                                   | 8         | 4.97%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 3.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 3.11%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 3.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 3.11%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 2.48%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 2.48%   |
| Intel CM238 HD Audio Controller                                            | 4         | 2.48%   |
| Nvidia TU104 HD Audio Controller                                           | 3         | 1.86%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 1.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.86%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 1.86%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.24%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.24%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 1.24%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.24%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 1.24%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.24%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.24%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 1.24%   |
| Corsair VOID ELITE Wireless Gaming Dongle                                  | 2         | 1.24%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 1.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.24%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.24%   |
| Sony DualSense wireless controller (PS5)                                   | 1         | 0.62%   |
| Scarlett Scarlett 2i2 Camera                                               | 1         | 0.62%   |
| Realtek Semiconductor USB Condenser Microphone                             | 1         | 0.62%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.62%   |
| Razer USA Razer BlackShark V2 Pro                                          | 1         | 0.62%   |
| Plantronics Blackwire 5220 Series                                          | 1         | 0.62%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.62%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.62%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.62%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.62%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.62%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 4         | 22.22%  |
| Samsung Electronics | 4         | 22.22%  |
| Kingston            | 2         | 11.11%  |
| Corsair             | 2         | 11.11%  |
| Unknown             | 1         | 5.56%   |
| Ramaxel Technology  | 1         | 5.56%   |
| Micron Technology   | 1         | 5.56%   |
| G.Skill             | 1         | 5.56%   |
| Crucial             | 1         | 5.56%   |
| A-DATA Technology   | 1         | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s      | 3         | 16.67%  |
| Unknown RAM Module 8GB DIMM 1600MT/s                       | 1         | 5.56%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 5.56%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s    | 1         | 5.56%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s     | 1         | 5.56%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s     | 1         | 5.56%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s     | 1         | 5.56%   |
| Ramaxel RAM RMSA3320ME88HBF-3200 16GB SODIMM DDR4 3200MT/s | 1         | 5.56%   |
| Micron RAM 8ATF1G64AZ-2G3E1 8GB DIMM DDR4 2400MT/s         | 1         | 5.56%   |
| Kingston RAM KF556S40-16 16GB SODIMM DDR5 5600MT/s         | 1         | 5.56%   |
| Kingston RAM 9905469-063.A00LF 4GB SODIMM DDR3 1600MT/s    | 1         | 5.56%   |
| G.Skill RAM F4-3200C22-32GRS 32GB SODIMM DDR4 3200MT/s     | 1         | 5.56%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s    | 1         | 5.56%   |
| Corsair RAM CMK32GX5M2D6000Z36 16GB DIMM DDR5 6000MT/s     | 1         | 5.56%   |
| Corsair RAM CMH16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s      | 1         | 5.56%   |
| A-DATA RAM Module 4GB SODIMM DDR4 1866MT/s                 | 1         | 5.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 10        | 62.5%   |
| DDR5    | 3         | 18.75%  |
| LPDDR4  | 1         | 6.25%   |
| DDR3    | 1         | 6.25%   |
| Unknown | 1         | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 12        | 75%     |
| DIMM   | 4         | 25%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 8         | 47.06%  |
| 16384 | 6         | 35.29%  |
| 4096  | 2         | 11.76%  |
| 32768 | 1         | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 8         | 50%     |
| 1600  | 2         | 12.5%   |
| 6000  | 1         | 6.25%   |
| 5600  | 1         | 6.25%   |
| 4800  | 1         | 6.25%   |
| 2667  | 1         | 6.25%   |
| 2400  | 1         | 6.25%   |
| 1866  | 1         | 6.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)

![Printer Vendor](./images/line_chart/printer_vendor.svg)

| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung Info. Systems America | 1         | 33.33%  |
| Dymo-CoStar                   | 1         | 33.33%  |
| Canon                         | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)

![Printer Model](./images/line_chart/printer_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Samsung Info. Systems America SAMSUNG SRP-270 | 1         | 33.33%  |
| Dymo-CoStar DYMO LabelWriter 450 Turbo        | 1         | 33.33%  |
| Canon PIXMA MP280                             | 1         | 33.33%  |

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
| Chicony Electronics                    | 14        | 25.93%  |
| Sunplus Innovation Technology          | 6         | 11.11%  |
| Microdia                               | 5         | 9.26%   |
| Bison Electronics                      | 4         | 7.41%   |
| Apple                                  | 4         | 7.41%   |
| Lite-On Technology                     | 3         | 5.56%   |
| Syntek                                 | 2         | 3.7%    |
| Realtek Semiconductor                  | 2         | 3.7%    |
| Logitech                               | 2         | 3.7%    |
| IMC Networks                           | 2         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.7%    |
| Unknown                                | 1         | 1.85%   |
| Suyin                                  | 1         | 1.85%   |
| SunplusIT                              | 1         | 1.85%   |
| Luxvisions Innotech Limited            | 1         | 1.85%   |
| Importek                               | 1         | 1.85%   |
| Generalplus Technology                 | 1         | 1.85%   |
| Acer                                   | 1         | 1.85%   |
| 2M UVC CAMERA                          | 1         | 1.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 3         | 5.56%   |
| Chicony HP TrueVision HD Camera                     | 3         | 5.56%   |
| Bison Integrated Camera                             | 3         | 5.56%   |
| Chicony HD WebCam                                   | 2         | 3.7%    |
| Unknown HD camera                                   | 1         | 1.85%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.85%   |
| Syntek Integrated Camera                            | 1         | 1.85%   |
| Suyin HP TrueVision HD                              | 1         | 1.85%   |
| SunplusIT MTD camera                                | 1         | 1.85%   |
| Sunplus XiaoMi USB 2.0 Webcam                       | 1         | 1.85%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.85%   |
| Sunplus HD WebCam                                   | 1         | 1.85%   |
| Sunplus HD 720P webcam                              | 1         | 1.85%   |
| Sunplus Full HD webcam                              | 1         | 1.85%   |
| Sunplus Camera                                      | 1         | 1.85%   |
| Realtek Integrated_Webcam_HD                        | 1         | 1.85%   |
| Realtek HP Wide Vision FHD Camera                   | 1         | 1.85%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 1.85%   |
| Microdia Integrated_Webcam_HD                       | 1         | 1.85%   |
| Microdia Integrated Webcam HD                       | 1         | 1.85%   |
| Microdia Integrated Webcam                          | 1         | 1.85%   |
| Microdia Dell Laptop Integrated Webcam HD           | 1         | 1.85%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 1.85%   |
| Logitech Webcam C270                                | 1         | 1.85%   |
| Logitech C922 Pro Stream Webcam                     | 1         | 1.85%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 1.85%   |
| Lite-On Integrated Camera                           | 1         | 1.85%   |
| Lite-On HP HD Camera                                | 1         | 1.85%   |
| Importek TOSHIBA Web Camera - HD                    | 1         | 1.85%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 1.85%   |
| IMC Networks Integrated RGB Camera                  | 1         | 1.85%   |
| Generalplus WEB CAM                                 | 1         | 1.85%   |
| Chicony USB 2.0 Camera                              | 1         | 1.85%   |
| Chicony Lenovo EasyCamera                           | 1         | 1.85%   |
| Chicony Integrated Camera [ThinkPad]                | 1         | 1.85%   |
| Chicony HP Truevision HD                            | 1         | 1.85%   |
| Chicony HP Full HD Camera                           | 1         | 1.85%   |
| Chicony HD User Facing                              | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 1.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 66.67%  |
| Synaptics                  | 2         | 16.67%  |
| Shenzhen Goodix Technology | 1         | 8.33%   |
| LighTuning Technology      | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 3         | 25%     |
| Validity Sensors Synaptics WBDI                   | 2         | 16.67%  |
| Validity Sensors VFS471 Fingerprint Reader        | 1         | 8.33%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 8.33%   |
| Validity Sensors Fingerprint scanner              | 1         | 8.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 8.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader  | 1         | 8.33%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 8.33%   |
| LighTuning Fingerprint Sensor                     | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./images/line_chart/chipcard_vendor.svg)

| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 42.86%  |
| Alcor Micro | 3         | 42.86%  |
| Upek        | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)

![Chipcard Model](./images/line_chart/chipcard_model.svg)

| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 42.86%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 14.29%  |
| Broadcom 5880                                                                | 1         | 14.29%  |
| Broadcom 58200                                                               | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 58        | 68.24%  |
| 1     | 20        | 23.53%  |
| 2     | 6         | 7.06%   |
| 3     | 1         | 1.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 12        | 34.29%  |
| Chipcard              | 7         | 20%     |
| Multimedia controller | 5         | 14.29%  |
| Net/wireless          | 4         | 11.43%  |
| Camera                | 3         | 8.57%   |
| Graphics card         | 2         | 5.71%   |
| Video                 | 1         | 2.86%   |
| Sound                 | 1         | 2.86%   |

