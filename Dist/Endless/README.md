Endless Hardware Trends
-----------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Endless users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Endless/Desktop/README.md) and [notebooks](/Dist/Endless/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

Period: Oct, 2021.

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
| Endless 3.9.5         | 40        | 71.43%  |
| Endless 3.7.4         | 3         | 5.36%   |
| Endless 3.9.1-nexthw2 | 2         | 3.57%   |
| Endless 3.8.0         | 2         | 3.57%   |
| Endless 4.0.0         | 1         | 1.79%   |
| Endless 3.9.3-nexthw1 | 1         | 1.79%   |
| Endless 3.9.2         | 1         | 1.79%   |
| Endless 3.9.0         | 1         | 1.79%   |
| Endless 3.8.7         | 1         | 1.79%   |
| Endless 3.8.5         | 1         | 1.79%   |
| Endless 3.7.8         | 1         | 1.79%   |
| Endless 3.4.3-nexthw1 | 1         | 1.79%   |
| Endless 3.4.2-nexthw1 | 1         | 1.79%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Endless | 56        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.8.0-14-generic  | 42        | 75%     |
| 5.3.0-19-generic  | 3         | 5.36%   |
| 5.4.0-19-generic  | 2         | 3.57%   |
| 5.10.0-10-generic | 2         | 3.57%   |
| 4.16.0-4-generic  | 2         | 3.57%   |
| 5.4.0-42-generic  | 1         | 1.79%   |
| 5.4.0-39-generic  | 1         | 1.79%   |
| 5.3.0-28-generic  | 1         | 1.79%   |
| 5.11.0-35-generic | 1         | 1.79%   |
| 5.11.0-12-generic | 1         | 1.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8.0   | 42        | 75%     |
| 5.4.0   | 4         | 7.14%   |
| 5.3.0   | 4         | 7.14%   |
| 5.11.0  | 2         | 3.57%   |
| 5.10.0  | 2         | 3.57%   |
| 4.16.0  | 2         | 3.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8     | 42        | 75%     |
| 5.4     | 4         | 7.14%   |
| 5.3     | 4         | 7.14%   |
| 5.11    | 2         | 3.57%   |
| 5.10    | 2         | 3.57%   |
| 4.16    | 2         | 3.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 56        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name  | Computers | Percent |
|-------|-----------|---------|
| GNOME | 56        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 56        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 56        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang        | Computers | Percent |
|-------------|-----------|---------|
| pt_BR       | 22        | 39.29%  |
| ru_RU.UTF_8 | 6         | 10.71%  |
| ro_RO       | 5         | 8.93%   |
| en_US       | 5         | 8.93%   |
| es_ES       | 3         | 5.36%   |
| ru_RU       | 2         | 3.57%   |
| hu_HU       | 2         | 3.57%   |
| fr_FR       | 2         | 3.57%   |
| pt_PT       | 1         | 1.79%   |
| pl_PL       | 1         | 1.79%   |
| it_IT       | 1         | 1.79%   |
| id_ID       | 1         | 1.79%   |
| es_MX       | 1         | 1.79%   |
| es_CO       | 1         | 1.79%   |
| en_GB       | 1         | 1.79%   |
| en_AU       | 1         | 1.79%   |
| cs_CZ       | 1         | 1.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 46        | 82.14%  |
| BIOS | 10        | 17.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 53        | 94.64%  |
| Tmpfs | 3         | 5.36%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 55        | 98.21%  |
| GPT     | 1         | 1.79%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 55        | 98.21%  |
| Yes       | 1         | 1.79%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 56        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 21        | 37.5%   |
| Acer                | 20        | 35.71%  |
| Lenovo              | 2         | 3.57%   |
| Hewlett-Packard     | 2         | 3.57%   |
| Dell                | 2         | 3.57%   |
| ASRock              | 2         | 3.57%   |
| Standard            | 1         | 1.79%   |
| Notebook            | 1         | 1.79%   |
| LG Electronics      | 1         | 1.79%   |
| Intel               | 1         | 1.79%   |
| Gigabyte Technology | 1         | 1.79%   |
| DIGIBOARD           | 1         | 1.79%   |
| Chuwi               | 1         | 1.79%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Acer Nitro AN515-54                        | 6         | 10.71%  |
| ASUS VivoBook_ASUSLaptop X415JA_X415JA     | 2         | 3.57%   |
| ASUS ASUS Vivo AIO V241EA_V241EA           | 2         | 3.57%   |
| Acer Nitro AN517-51                        | 2         | 3.57%   |
| Acer Nitro AN515-43                        | 2         | 3.57%   |
| Acer Aspire A515-54G                       | 2         | 3.57%   |
| Acer Aspire A315-34                        | 2         | 3.57%   |
| Standard AHV                               | 1         | 1.79%   |
| Notebook W840SN Series                     | 1         | 1.79%   |
| LG U460-G.BG31P1                           | 1         | 1.79%   |
| Lenovo ThinkCentre M73 10AXS0FX01          | 1         | 1.79%   |
| Lenovo IdeaPad L340-17API 81LY             | 1         | 1.79%   |
| HP 650                                     | 1         | 1.79%   |
| HP 2000                                    | 1         | 1.79%   |
| Gigabyte H310N 2.0                         | 1         | 1.79%   |
| DIGIBOARD CU-7592                          | 1         | 1.79%   |
| Dell OptiPlex 790                          | 1         | 1.79%   |
| Dell Latitude E7240                        | 1         | 1.79%   |
| Chuwi GemiBook                             | 1         | 1.79%   |
| ASUS ZenBook UX431DA_UM431DA               | 1         | 1.79%   |
| ASUS Z550SA                                | 1         | 1.79%   |
| ASUS X540NV                                | 1         | 1.79%   |
| ASUS X540LA                                | 1         | 1.79%   |
| ASUS VivoBook_ASUSLaptop X513EAN_X513EA    | 1         | 1.79%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA     | 1         | 1.79%   |
| ASUS VivoBook_ASUSLaptop X509JA            | 1         | 1.79%   |
| ASUS VivoBook_ASUSLaptop X509DA_M509DA     | 1         | 1.79%   |
| ASUS VivoBook_ASUSLaptop X430FA_S430FA     | 1         | 1.79%   |
| ASUS VivoBook_ASUSLaptop X415EA_X415EA     | 1         | 1.79%   |
| ASUS VivoBook_ASUSLaptop X415EA_P1411CEA   | 1         | 1.79%   |
| ASUS VivoBook_ASUSLaptop E510MAB_E510MA    | 1         | 1.79%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 1         | 1.79%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 1         | 1.79%   |
| ASUS VivoBook 15_ASUS Laptop X507UAR       | 1         | 1.79%   |
| ASUS PRIME B450M-GAMING/BR                 | 1         | 1.79%   |
| ASUS H110M-D                               | 1         | 1.79%   |
| ASRock N73V-S                              | 1         | 1.79%   |
| ASRock A88M-G                              | 1         | 1.79%   |
| Acer Nitro AN515-55                        | 1         | 1.79%   |
| Acer Nitro AN515-44                        | 1         | 1.79%   |
| Acer Aspire A515-54                        | 1         | 1.79%   |
| Acer Aspire A315-53                        | 1         | 1.79%   |
| Acer Aspire A315-51                        | 1         | 1.79%   |
| Acer Aspire A315-42G                       | 1         | 1.79%   |
| Unknown                                    | 1         | 1.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS VivoBook      | 13        | 23.21%  |
| Acer Nitro         | 12        | 21.43%  |
| Acer Aspire        | 8         | 14.29%  |
| ASUS ASUS          | 2         | 3.57%   |
| Standard AHV       | 1         | 1.79%   |
| Notebook W840SN    | 1         | 1.79%   |
| LG U460-G.BG31P1   | 1         | 1.79%   |
| Lenovo ThinkCentre | 1         | 1.79%   |
| Lenovo IdeaPad     | 1         | 1.79%   |
| HP 650             | 1         | 1.79%   |
| HP 2000            | 1         | 1.79%   |
| Gigabyte H310N     | 1         | 1.79%   |
| DIGIBOARD CU-7592  | 1         | 1.79%   |
| Dell OptiPlex      | 1         | 1.79%   |
| Dell Latitude      | 1         | 1.79%   |
| Chuwi GemiBook     | 1         | 1.79%   |
| ASUS ZenBook       | 1         | 1.79%   |
| ASUS Z550SA        | 1         | 1.79%   |
| ASUS X540NV        | 1         | 1.79%   |
| ASUS X540LA        | 1         | 1.79%   |
| ASUS PRIME         | 1         | 1.79%   |
| ASUS H110M-D       | 1         | 1.79%   |
| ASRock N73V-S      | 1         | 1.79%   |
| ASRock A88M-G      | 1         | 1.79%   |
| Unknown            | 1         | 1.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 19        | 33.93%  |
| 2021 | 10        | 17.86%  |
| 2019 | 10        | 17.86%  |
| 2018 | 6         | 10.71%  |
| 2013 | 4         | 7.14%   |
| 2016 | 3         | 5.36%   |
| 2011 | 2         | 3.57%   |
| 2017 | 1         | 1.79%   |
| 2009 | 1         | 1.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 46        | 82.14%  |
| Desktop    | 8         | 14.29%  |
| All in one | 2         | 3.57%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 36        | 64.29%  |
| Enabled  | 20        | 35.71%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 56        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 28        | 50%     |
| 3.01-4.0   | 16        | 28.57%  |
| 8.01-16.0  | 7         | 12.5%   |
| 16.01-24.0 | 5         | 8.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 32        | 57.14%  |
| 2.01-3.0 | 16        | 28.57%  |
| 4.01-8.0 | 4         | 7.14%   |
| 3.01-4.0 | 2         | 3.57%   |
| 0.51-1.0 | 2         | 3.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 40        | 71.43%  |
| 2      | 14        | 25%     |
| 3      | 1         | 1.79%   |
| 0      | 1         | 1.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 47        | 83.93%  |
| Yes       | 9         | 16.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 71.43%  |
| No        | 16        | 28.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 91.07%  |
| No        | 5         | 8.93%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 83.93%  |
| No        | 9         | 16.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country     | Computers | Percent |
|-------------|-----------|---------|
| Brazil      | 23        | 41.07%  |
| Romania     | 5         | 8.93%   |
| Russia      | 4         | 7.14%   |
| USA         | 3         | 5.36%   |
| Spain       | 3         | 5.36%   |
| Kazakhstan  | 3         | 5.36%   |
| Hungary     | 2         | 3.57%   |
| Australia   | 2         | 3.57%   |
| Ukraine     | 1         | 1.79%   |
| South Korea | 1         | 1.79%   |
| Poland      | 1         | 1.79%   |
| Morocco     | 1         | 1.79%   |
| Mexico      | 1         | 1.79%   |
| Kenya       | 1         | 1.79%   |
| Italy       | 1         | 1.79%   |
| France      | 1         | 1.79%   |
| El Salvador | 1         | 1.79%   |
| Czechia     | 1         | 1.79%   |
| Canada      | 1         | 1.79%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Rio de Janeiro       | 3         | 5.36%   |
| Porto Alegre         | 2         | 3.57%   |
| Bucharest            | 2         | 3.57%   |
| Almaty               | 2         | 3.57%   |
| Tulle                | 1         | 1.79%   |
| Sydney               | 1         | 1.79%   |
| St Petersburg        | 1         | 1.79%   |
| Songpa-dong          | 1         | 1.79%   |
| Sinop                | 1         | 1.79%   |
| Selenginsk           | 1         | 1.79%   |
| S??o Paulo           | 1         | 1.79%   |
| S??o Carlos          | 1         | 1.79%   |
| San Salvador         | 1         | 1.79%   |
| Roque Gonzales       | 1         | 1.79%   |
| Rio Verde            | 1         | 1.79%   |
| Ramenskoye           | 1         | 1.79%   |
| Quer?©taro City      | 1         | 1.79%   |
| Pontevedra           | 1         | 1.79%   |
| Ploie??ti            | 1         | 1.79%   |
| Perth                | 1         | 1.79%   |
| Ostr??w Wielkopolski | 1         | 1.79%   |
| Novo Hamburgo        | 1         | 1.79%   |
| Niter??i             | 1         | 1.79%   |
| Newnan               | 1         | 1.79%   |
| Nairobi              | 1         | 1.79%   |
| Moscow               | 1         | 1.79%   |
| Moh??cs              | 1         | 1.79%   |
| Mar?­lia             | 1         | 1.79%   |
| Manaus               | 1         | 1.79%   |
| Karaganda            | 1         | 1.79%   |
| Itu                  | 1         | 1.79%   |
| Itabira              | 1         | 1.79%   |
| Iasi                 | 1         | 1.79%   |
| Gibsonburg           | 1         | 1.79%   |
| Fortaleza            | 1         | 1.79%   |
| Florian??polis       | 1         | 1.79%   |
| Edmonton             | 1         | 1.79%   |
| Duque de Caxias      | 1         | 1.79%   |
| Dnipro               | 1         | 1.79%   |
| Cocal do Sul         | 1         | 1.79%   |
| Cluj-Napoca          | 1         | 1.79%   |
| Cerreto Guidi        | 1         | 1.79%   |
| Casablanca           | 1         | 1.79%   |
| Campo Grande         | 1         | 1.79%   |
| Budapest             | 1         | 1.79%   |
| Bucyrus              | 1         | 1.79%   |
| Brno                 | 1         | 1.79%   |
| Belo Horizonte       | 1         | 1.79%   |
| Barcelona            | 1         | 1.79%   |
| Aluminio             | 1         | 1.79%   |
| Alcasser             | 1         | 1.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 17        | 17     | 23.94%  |
| Intel                 | 16        | 16     | 22.54%  |
| Sandisk               | 7         | 7      | 9.86%   |
| Seagate               | 6         | 7      | 8.45%   |
| Kingston              | 6         | 6      | 8.45%   |
| Unknown               | 3         | 3      | 4.23%   |
| HGST                  | 3         | 3      | 4.23%   |
| Toshiba               | 2         | 2      | 2.82%   |
| SK Hynix              | 2         | 2      | 2.82%   |
| A-DATA Technology     | 2         | 2      | 2.82%   |
| StoreJet              | 1         | 1      | 1.41%   |
| Samsung Electronics   | 1         | 1      | 1.41%   |
| Realtek Semiconductor | 1         | 1      | 1.41%   |
| PLEXTOR               | 1         | 1      | 1.41%   |
| Netac                 | 1         | 2      | 1.41%   |
| Hitachi               | 1         | 1      | 1.41%   |
| ADATA Technology      | 1         | 1      | 1.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel NVMe SSD Drive 512GB           | 11        | 15.28%  |
| WDC WD10SPZX-21Z10T0 1TB             | 10        | 13.89%  |
| Sandisk NVMe SSD Drive 256GB         | 3         | 4.17%   |
| Unknown MMC Card  16GB               | 2         | 2.78%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 2.78%   |
| Intel SSDPEKKW256G7 256GB            | 2         | 2.78%   |
| Intel NVMe SSD Drive 128GB           | 2         | 2.78%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 1.39%   |
| WDC WD5000LPCX-80VHAT1 500GB         | 1         | 1.39%   |
| WDC WD5000LPCX-80VHAT0 500GB         | 1         | 1.39%   |
| WDC WD20SPZX-08UA7 2TB               | 1         | 1.39%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 1.39%   |
| WDC WD1001FALS-00U9B0 1TB            | 1         | 1.39%   |
| WDC PC SN520 SDAPNUW-256G-1202 256GB | 1         | 1.39%   |
| Unknown MMC Card  64GB               | 1         | 1.39%   |
| Toshiba TR200 480GB SSD              | 1         | 1.39%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1.39%   |
| StoreJet Transcend 240GB             | 1         | 1.39%   |
| SK Hynix NVMe SSD Drive 512GB        | 1         | 1.39%   |
| SK Hynix NVMe SSD Drive 256GB        | 1         | 1.39%   |
| Seagate ST500DM002-1SB10A 500GB      | 1         | 1.39%   |
| Seagate ST3320418AS 320GB            | 1         | 1.39%   |
| Seagate ST320LT012-9WS14C 320GB      | 1         | 1.39%   |
| Seagate ST320DM000-1BD14C 320GB      | 1         | 1.39%   |
| Seagate ST1000LM049-2GH172 1TB       | 1         | 1.39%   |
| SanDisk SD9SN8W256G1102 256GB SSD    | 1         | 1.39%   |
| SanDisk SD9SB8W256G1102 256GB SSD    | 1         | 1.39%   |
| SanDisk SD8SN8U-512G-1006 512GB SSD  | 1         | 1.39%   |
| Sandisk NVMe SSD Drive 128GB         | 1         | 1.39%   |
| Samsung NVMe SSD Drive 256GB         | 1         | 1.39%   |
| Realtek NVMe SSD Drive 128GB         | 1         | 1.39%   |
| PLEXTOR PX-256M5M 256GB SSD          | 1         | 1.39%   |
| Netac SSD 128GB                      | 1         | 1.39%   |
| Kingston SVP200S360G 64GB SSD        | 1         | 1.39%   |
| Kingston SV300S37A120G 120GB SSD     | 1         | 1.39%   |
| Kingston SHSS37A120G 120GB SSD       | 1         | 1.39%   |
| Kingston SA400S37480G 480GB SSD      | 1         | 1.39%   |
| Kingston NVMe SSD Drive 512GB        | 1         | 1.39%   |
| Kingston NVMe SSD Drive 256GB        | 1         | 1.39%   |
| Intel SSDSCKKW256G8 256GB            | 1         | 1.39%   |
| Hitachi HUA722020ALA330 2TB          | 1         | 1.39%   |
| HGST HTS725050A7E630 500GB           | 1         | 1.39%   |
| HGST HTS545050B7E660 500GB           | 1         | 1.39%   |
| HGST HTS545050A7E380 500GB           | 1         | 1.39%   |
| ADATA NVMe SSD Drive 128GB           | 1         | 1.39%   |
| A-DATA SU650NS38 120GB SSD           | 1         | 1.39%   |
| A-DATA IM2S3338-128GD2 128GB SSD     | 1         | 1.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 15        | 15     | 57.69%  |
| Seagate | 6         | 7      | 23.08%  |
| HGST    | 3         | 3      | 11.54%  |
| Toshiba | 1         | 1      | 3.85%   |
| Hitachi | 1         | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Kingston          | 4         | 4      | 26.67%  |
| SanDisk           | 3         | 3      | 20%     |
| A-DATA Technology | 2         | 2      | 13.33%  |
| WDC               | 1         | 1      | 6.67%   |
| Toshiba           | 1         | 1      | 6.67%   |
| StoreJet          | 1         | 1      | 6.67%   |
| PLEXTOR           | 1         | 1      | 6.67%   |
| Netac             | 1         | 2      | 6.67%   |
| Intel             | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 26        | 27     | 38.81%  |
| HDD  | 24        | 27     | 35.82%  |
| SSD  | 14        | 16     | 20.9%   |
| MMC  | 3         | 3      | 4.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 34        | 42     | 53.13%  |
| NVMe | 26        | 27     | 40.63%  |
| MMC  | 3         | 3      | 4.69%   |
| SAS  | 1         | 1      | 1.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 25     | 53.85%  |
| 0.51-1.0   | 16        | 16     | 41.03%  |
| 1.01-2.0   | 2         | 2      | 5.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 22        | 39.29%  |
| 101-250        | 17        | 30.36%  |
| 501-1000       | 9         | 16.07%  |
| 21-50          | 3         | 5.36%   |
| 51-100         | 2         | 3.57%   |
| More than 3000 | 1         | 1.79%   |
| 1001-2000      | 1         | 1.79%   |
| 1-20           | 1         | 1.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 27        | 48.21%  |
| 101-250   | 9         | 16.07%  |
| 1-20      | 8         | 14.29%  |
| 51-100    | 7         | 12.5%   |
| 251-500   | 4         | 7.14%   |
| 2001-3000 | 1         | 1.79%   |

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
| Detected | 55        | 70     | 96.49%  |
| Works    | 2         | 3      | 3.51%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 43        | 65.15%  |
| AMD                         | 11        | 16.67%  |
| Sandisk                     | 4         | 6.06%   |
| SK Hynix                    | 2         | 3.03%   |
| Kingston Technology Company | 2         | 3.03%   |
| Samsung Electronics         | 1         | 1.52%   |
| Realtek Semiconductor       | 1         | 1.52%   |
| Nvidia                      | 1         | 1.52%   |
| ADATA Technology            | 1         | 1.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 18        | 20.22%  |
| Intel PROSet/Wireless WiFi Software extension                                    | 14        | 15.73%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 11.24%  |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 5.62%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 5         | 5.62%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 5.62%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 3         | 3.37%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 2.25%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 2.25%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 2.25%   |
| SK Hynix BC511                                                                   | 1         | 1.12%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 1.12%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 1.12%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 1.12%   |
| Realtek RTS5763DL NVMe SSD Controller                                            | 1         | 1.12%   |
| Nvidia MCP73 SATA Controller (IDE mode)                                          | 1         | 1.12%   |
| Nvidia MCP73 IDE Controller                                                      | 1         | 1.12%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 1.12%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 1.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.12%   |
| Intel SSD 660P Series                                                            | 1         | 1.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.12%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.12%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 1.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.12%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1         | 1.12%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1         | 1.12%   |
| AMD FCH IDE Controller                                                           | 1         | 1.12%   |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 1.12%   |
| ADATA Non-Volatile memory controller                                             | 1         | 1.12%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 49        | 56.32%  |
| NVMe | 26        | 29.89%  |
| RAID | 9         | 10.34%  |
| IDE  | 3         | 3.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 45        | 80.36%  |
| AMD    | 11        | 19.64%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-9300H CPU @ 2.40GHz             | 6         | 10.71%  |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 5.36%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 5.36%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 5.36%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 5.36%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 3.57%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 3.57%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 3.57%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 3.57%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 1         | 1.79%   |
| Intel Pentium Gold 7505 @ 2.00GHz             | 1         | 1.79%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz   | 1         | 1.79%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 1         | 1.79%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 1.79%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 1         | 1.79%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 1.79%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 1.79%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.79%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.79%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.79%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 1         | 1.79%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 1.79%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 1         | 1.79%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.79%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.79%   |
| Intel Core i3-4130T CPU @ 2.90GHz             | 1         | 1.79%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 1         | 1.79%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 1.79%   |
| Intel Celeron J4115 CPU @ 1.80GHz             | 1         | 1.79%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 1.79%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 1.79%   |
| Intel Celeron CPU 1000M @ 1.80GHz             | 1         | 1.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.79%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 1.79%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 1.79%   |
| AMD Ryzen 5 3350G with Radeon Vega Graphics   | 1         | 1.79%   |
| AMD E-300 APU with Radeon HD Graphics         | 1         | 1.79%   |
| AMD A8-6500 APU with Radeon HD Graphics       | 1         | 1.79%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 1         | 1.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 13        | 23.21%  |
| Intel Celeron           | 8         | 14.29%  |
| Intel Core i7           | 7         | 12.5%   |
| Intel Core i3           | 7         | 12.5%   |
| Other                   | 4         | 7.14%   |
| AMD Ryzen 7             | 4         | 7.14%   |
| AMD Ryzen 5             | 4         | 7.14%   |
| Intel Pentium Gold      | 2         | 3.57%   |
| Intel Pentium           | 2         | 3.57%   |
| Intel Pentium Dual-Core | 1         | 1.79%   |
| Intel Pentium Dual      | 1         | 1.79%   |
| AMD E                   | 1         | 1.79%   |
| AMD A8                  | 1         | 1.79%   |
| AMD A6                  | 1         | 1.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 27        | 48.21%  |
| 4      | 26        | 46.43%  |
| 6      | 2         | 3.57%   |
| 8      | 1         | 1.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 56        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 41        | 73.21%  |
| 1      | 15        | 26.79%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 56        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x906ea    | 6         | 10.71%  |
| 0x806c1    | 5         | 8.93%   |
| 0x08108109 | 5         | 8.93%   |
| Unknown    | 4         | 7.14%   |
| 0x906ed    | 3         | 5.36%   |
| 0x806ec    | 3         | 5.36%   |
| 0x706a8    | 3         | 5.36%   |
| 0x806ea    | 2         | 3.57%   |
| 0x706e5    | 2         | 3.57%   |
| 0x706a1    | 2         | 3.57%   |
| 0x506c9    | 2         | 3.57%   |
| 0x40651    | 2         | 3.57%   |
| 0x306a9    | 2         | 3.57%   |
| 0x206a7    | 2         | 3.57%   |
| 0xa0652    | 1         | 1.79%   |
| 0x806eb    | 1         | 1.79%   |
| 0x6fd      | 1         | 1.79%   |
| 0x506e3    | 1         | 1.79%   |
| 0x406e3    | 1         | 1.79%   |
| 0x406c4    | 1         | 1.79%   |
| 0x306d4    | 1         | 1.79%   |
| 0x306c3    | 1         | 1.79%   |
| 0x1067a    | 1         | 1.79%   |
| 0x08600103 | 1         | 1.79%   |
| 0x08108102 | 1         | 1.79%   |
| 0x06006705 | 1         | 1.79%   |
| 0x06001119 | 1         | 1.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 15        | 26.79%  |
| Zen+          | 7         | 12.5%   |
| TigerLake     | 5         | 8.93%   |
| Goldmont plus | 5         | 8.93%   |
| IceLake       | 4         | 7.14%   |
| Haswell       | 3         | 5.36%   |
| Skylake       | 2         | 3.57%   |
| SandyBridge   | 2         | 3.57%   |
| IvyBridge     | 2         | 3.57%   |
| Goldmont      | 2         | 3.57%   |
| Zen 2         | 1         | 1.79%   |
| Silvermont    | 1         | 1.79%   |
| Piledriver    | 1         | 1.79%   |
| Penryn        | 1         | 1.79%   |
| Excavator     | 1         | 1.79%   |
| Core          | 1         | 1.79%   |
| CometLake     | 1         | 1.79%   |
| Broadwell     | 1         | 1.79%   |
| Bobcat        | 1         | 1.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Intel          | 43        | 57.33%  |
| Nvidia         | 20        | 26.67%  |
| AMD            | 11        | 14.67%  |
| Silicon Motion | 1         | 1.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 13.16%  |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 10.53%  |
| AMD Picasso                                                                              | 7         | 9.21%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 6.58%   |
| Intel Tiger Lake UHD Graphics                                                            | 4         | 5.26%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 5.26%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 3.95%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 2.63%   |
| Intel UHD Graphics 620                                                                   | 2         | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 2.63%   |
| Silicon Motion SM501 VoyagerGX Rev. AA                                                   | 1         | 1.32%   |
| Nvidia TU117M                                                                            | 1         | 1.32%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 1.32%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 1.32%   |
| Nvidia GK107M [GeForce GT 745M]                                                          | 1         | 1.32%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1         | 1.32%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.32%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 1         | 1.32%   |
| Nvidia C73 [GeForce 7100 / nForce 620i]                                                  | 1         | 1.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.32%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.32%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.32%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.32%   |
| Intel HD Graphics 510                                                                    | 1         | 1.32%   |
| Intel HD Graphics 500                                                                    | 1         | 1.32%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.32%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1         | 1.32%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 1         | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.32%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 1.32%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1         | 1.32%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 1.32%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1.32%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.32%   |
| AMD Renoir                                                                               | 1         | 1.32%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                                       | 1         | 1.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 28        | 50%     |
| Intel + Nvidia         | 14        | 25%     |
| 1 x AMD                | 8         | 14.29%  |
| AMD + Nvidia           | 3         | 5.36%   |
| 1 x Nvidia             | 2         | 3.57%   |
| Intel + Silicon Motion | 1         | 1.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 41        | 73.21%  |
| Proprietary | 15        | 26.79%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 76.79%  |
| 1.01-2.0   | 9         | 16.07%  |
| 0.01-0.5   | 3         | 5.36%   |
| 7.01-8.0   | 1         | 1.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| BOE                 | 16        | 27.59%  |
| Chimei Innolux      | 10        | 17.24%  |
| AU Optronics        | 10        | 17.24%  |
| LG Display          | 5         | 8.62%   |
| Samsung Electronics | 4         | 6.9%    |
| PANDA               | 3         | 5.17%   |
| ASUSTek Computer    | 2         | 3.45%   |
| ViewSonic           | 1         | 1.72%   |
| Sony                | 1         | 1.72%   |
| RTK                 | 1         | 1.72%   |
| Philips             | 1         | 1.72%   |
| Lenovo              | 1         | 1.72%   |
| Dell                | 1         | 1.72%   |
| Apple               | 1         | 1.72%   |
| AOC                 | 1         | 1.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 4         | 6.9%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 3         | 5.17%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 2         | 3.45%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 2         | 3.45%   |
| BOE LCD Monitor BOE0839 1920x1080 382x215mm 17.3-inch                | 2         | 3.45%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                | 2         | 3.45%   |
| BOE LCD Monitor BOE07AA 1366x768 344x194mm 15.5-inch                 | 2         | 3.45%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 2         | 3.45%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 2         | 3.45%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch       | 2         | 3.45%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 2         | 3.45%   |
| ASUSTek Computer V241FA ASU282C 1920x1080 527x296mm 23.8-inch        | 2         | 3.45%   |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch           | 1         | 1.72%   |
| Sony TV *00 SNY3705 3840x2160 1439x809mm 65.0-inch                   | 1         | 1.72%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch    | 1         | 1.72%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch    | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch | 1         | 1.72%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 1         | 1.72%   |
| RTK QHD RTK6410 2560x1440 597x336mm 27.0-inch                        | 1         | 1.72%   |
| Philips 190S PHL083F 1280x1024 376x301mm 19.0-inch                   | 1         | 1.72%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch              | 1         | 1.72%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch          | 1         | 1.72%   |
| Lenovo LEN L192p LEN24CB 1280x1024 376x301mm 19.0-inch               | 1         | 1.72%   |
| Dell E170S DELA04A 1280x1024 338x270mm 17.0-inch                     | 1         | 1.72%   |
| Chimei Innolux P130ZDZ-EF1 CMN8201 2160x1440 275x183mm 13.0-inch     | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch      | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 1         | 1.72%   |
| BOE LCD Monitor BOE07F7 1920x1080 309x174mm 14.0-inch                | 1         | 1.72%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                | 1         | 1.72%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 1         | 1.72%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                | 1         | 1.72%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                | 1         | 1.72%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                 | 1         | 1.72%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 1         | 1.72%   |
| BOE LCD Monitor BOE05DA 1366x768 277x156mm 12.5-inch                 | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch        | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch       | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO113D 1920x1080 309x173mm 13.9-inch       | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO103C 1366x768 310x170mm 13.9-inch        | 1         | 1.72%   |
| Apple iMac APPA007 2560x1440 597x336mm 27.0-inch                     | 1         | 1.72%   |
| AOC 2200W AOC2200 1920x1080 476x268mm 21.5-inch                      | 1         | 1.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 30        | 52.63%  |
| 1366x768 (WXGA)  | 19        | 33.33%  |
| 1280x1024 (SXGA) | 3         | 5.26%   |
| 3840x2160 (4K)   | 2         | 3.51%   |
| 2560x1440 (QHD)  | 1         | 1.75%   |
| 2160x1440        | 1         | 1.75%   |
| 1600x900 (HD+)   | 1         | 1.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 33        | 57.89%  |
| 13     | 6         | 10.53%  |
| 23     | 4         | 7.02%   |
| 17     | 4         | 7.02%   |
| 14     | 3         | 5.26%   |
| 27     | 2         | 3.51%   |
| 65     | 1         | 1.75%   |
| 21     | 1         | 1.75%   |
| 20     | 1         | 1.75%   |
| 19     | 1         | 1.75%   |
| 12     | 1         | 1.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 42        | 73.68%  |
| 501-600     | 5         | 8.77%   |
| 351-400     | 5         | 8.77%   |
| 201-300     | 2         | 3.51%   |
| 601-700     | 1         | 1.75%   |
| 401-500     | 1         | 1.75%   |
| 1001-1500   | 1         | 1.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 53        | 92.98%  |
| 5/4   | 3         | 5.26%   |
| 3/2   | 1         | 1.75%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inchÂ² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 33        | 57.89%  |
| 81-90          | 8         | 14.04%  |
| 201-250        | 4         | 7.02%   |
| 151-200        | 3         | 5.26%   |
| 121-130        | 3         | 5.26%   |
| 301-350        | 2         | 3.51%   |
| More than 1000 | 1         | 1.75%   |
| 71-80          | 1         | 1.75%   |
| 61-70          | 1         | 1.75%   |
| 141-150        | 1         | 1.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 27        | 47.37%  |
| 101-120 | 21        | 36.84%  |
| 51-100  | 8         | 14.04%  |
| 161-240 | 1         | 1.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 55        | 98.21%  |
| 2     | 1         | 1.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 43        | 48.86%  |
| Intel                 | 24        | 27.27%  |
| Qualcomm Atheros      | 12        | 13.64%  |
| MediaTek              | 2         | 2.27%   |
| Xiaomi                | 1         | 1.14%   |
| Samsung Electronics   | 1         | 1.14%   |
| Ralink Technology     | 1         | 1.14%   |
| Ralink                | 1         | 1.14%   |
| Nvidia                | 1         | 1.14%   |
| JMicron Technology    | 1         | 1.14%   |
| Unknown               | 1         | 1.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 29.79%  |
| Intel Wi-Fi 6 AX200                                               | 9         | 9.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 8.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 5.32%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 4.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 3.19%   |
| Intel Wireless 8265 / 8275                                        | 3         | 3.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 2.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 2.13%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 2.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 2.13%   |
| Intel Wireless 7260                                               | 2         | 2.13%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 2.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.06%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.06%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 1.06%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 1.06%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 1.06%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 1.06%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.06%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.06%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.06%   |
| Nvidia MCP73 Ethernet                                             | 1         | 1.06%   |
| MEDIATEK Network controller                                       | 1         | 1.06%   |
| MediaTek moto g(8) power lite                                     | 1         | 1.06%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.06%   |
| Intel Wireless 7265                                               | 1         | 1.06%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 1.06%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.06%   |
| Unknown                                                           | 1         | 1.06%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 44.23%  |
| Realtek Semiconductor | 15        | 28.85%  |
| Qualcomm Atheros      | 11        | 21.15%  |
| Ralink Technology     | 1         | 1.92%   |
| Ralink                | 1         | 1.92%   |
| MEDIATEK              | 1         | 1.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 9         | 17.31%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 8         | 15.38%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 5         | 9.62%   |
| Intel Wi-Fi 6 AX201                                        | 4         | 7.69%   |
| Intel Wireless 8265 / 8275                                 | 3         | 5.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 2         | 3.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 2         | 3.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 2         | 3.85%   |
| Intel Wireless 7260                                        | 2         | 3.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 2         | 3.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 1.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 1.92%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 1         | 1.92%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter            | 1         | 1.92%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                    | 1         | 1.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 1         | 1.92%   |
| Ralink MT7601U Wireless Adapter                            | 1         | 1.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                  | 1         | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 1         | 1.92%   |
| MEDIATEK Network controller                                | 1         | 1.92%   |
| Intel Wireless 7265                                        | 1         | 1.92%   |
| Intel Gemini Lake PCH CNVi WiFi                            | 1         | 1.92%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 1.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 33        | 80.49%  |
| Intel                 | 2         | 4.88%   |
| Xiaomi                | 1         | 2.44%   |
| Samsung Electronics   | 1         | 2.44%   |
| Qualcomm Atheros      | 1         | 2.44%   |
| Nvidia                | 1         | 2.44%   |
| MediaTek              | 1         | 2.44%   |
| JMicron Technology    | 1         | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 68.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 7.32%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 4.88%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.44%   |
| Nvidia MCP73 Ethernet                                             | 1         | 2.44%   |
| MediaTek moto g(8) power lite                                     | 1         | 2.44%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.44%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 51        | 55.43%  |
| Ethernet | 40        | 43.48%  |
| Unknown  | 1         | 1.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 51        | 56.67%  |
| Ethernet | 39        | 43.33%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 31        | 55.36%  |
| 1     | 23        | 41.07%  |
| 0     | 2         | 3.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 39        | 69.64%  |
| Yes  | 17        | 30.36%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 23        | 48.94%  |
| Lite-On Technology      | 11        | 23.4%   |
| IMC Networks            | 7         | 14.89%  |
| Realtek Semiconductor   | 4         | 8.51%   |
| Ralink                  | 1         | 2.13%   |
| Cambridge Silicon Radio | 1         | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Lite-On Bluetooth Device                            | 10        | 21.28%  |
| Intel AX200 Bluetooth                               | 9         | 19.15%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 14.89%  |
| IMC Networks Bluetooth Radio                        | 6         | 12.77%  |
| Realtek Bluetooth Radio                             | 3         | 6.38%   |
| Intel Bluetooth wireless interface                  | 3         | 6.38%   |
| Intel Bluetooth Device                              | 3         | 6.38%   |
| Realtek RTL8723A Bluetooth                          | 1         | 2.13%   |
| Ralink RT3290 Bluetooth                             | 1         | 2.13%   |
| Lite-On Bluetooth Radio                             | 1         | 2.13%   |
| Intel AX201 Bluetooth                               | 1         | 2.13%   |
| IMC Networks Wireless_Device                        | 1         | 2.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 43        | 60.56%  |
| Nvidia              | 14        | 19.72%  |
| AMD                 | 11        | 15.49%  |
| C-Media Electronics | 2         | 2.82%   |
| JMTek               | 1         | 1.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 9         | 10.59%  |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 9.41%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 8         | 9.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 8.24%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 5.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 5.88%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 4.71%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 3.53%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 3.53%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 2.35%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 2.35%   |
| AMD FCH Azalia Controller                                                                         | 2         | 2.35%   |
| Nvidia MCP73 High Definition Audio                                                                | 1         | 1.18%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 1.18%   |
| Nvidia GF104 High Definition Audio Controller                                                     | 1         | 1.18%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1.18%   |
| Nvidia Audio device                                                                               | 1         | 1.18%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 1.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.18%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.18%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.18%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 1.18%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.18%   |
| C-Media Electronics CM108 Audio Controller                                                        | 1         | 1.18%   |
| C-Media Electronics Audio Adapter                                                                 | 1         | 1.18%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.18%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.18%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                                             | 1         | 1.18%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.18%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 50%     |
| Kingston            | 1         | 50%     |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s  | 1         | 50%     |
| Kingston RAM 99U5428-073.A00G 8GB SODIMM DDR3 1600MT/s | 1         | 50%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| DDR4 | 1         | 50%     |
| DDR3 | 1         | 50%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 2         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size | Computers | Percent |
|------|-----------|---------|
| 8192 | 1         | 50%     |
| 4096 | 1         | 50%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 3266  | 1         | 50%     |
| 1600  | 1         | 50%     |

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

| Model                | Computers | Percent |
|----------------------|-----------|---------|
| HP Deskjet 2050 J510 | 1         | 100%    |

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

| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Quanta                        | 16        | 34.04%  |
| IMC Networks                  | 15        | 31.91%  |
| Chicony Electronics           | 9         | 19.15%  |
| Sunplus Innovation Technology | 2         | 4.26%   |
| Samsung Electronics           | 2         | 4.26%   |
| Realtek Semiconductor         | 1         | 2.13%   |
| Nebraska Furniture Mart       | 1         | 2.13%   |
| Microdia                      | 1         | 2.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam     | 11        | 23.4%   |
| Quanta HD User Facing                  | 10        | 21.28%  |
| Chicony HD User Facing                 | 5         | 10.64%  |
| Quanta VGA WebCam                      | 3         | 6.38%   |
| IMC Networks USB2.0 HD UVC WebCam      | 3         | 6.38%   |
| Samsung Galaxy A5 (MTP)                | 2         | 4.26%   |
| Quanta USB2.0 HD UVC WebCam            | 2         | 4.26%   |
| Chicony VGA WebCam                     | 2         | 4.26%   |
| Chicony USB2.0 VGA UVC WebCam          | 2         | 4.26%   |
| Sunplus Laptop Integrated Webcam HD    | 1         | 2.13%   |
| Sunplus HP Truevision HD               | 1         | 2.13%   |
| Realtek HP Truevision HD               | 1         | 2.13%   |
| Quanta USB2.0 VGA UVC WebCam           | 1         | 2.13%   |
| Nebraska Furniture Mart USB 2.0 PC cam | 1         | 2.13%   |
| Microdia Webcam Vitade AF              | 1         | 2.13%   |
| IMC Networks Integrated Camera         | 1         | 2.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Elan Microelectronics | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| Elan ELAN:Fingerprint | 1         | 100%    |

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
| 0     | 48        | 85.71%  |
| 1     | 7         | 12.5%   |
| 2     | 1         | 1.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 5         | 55.56%  |
| Network               | 1         | 11.11%  |
| Net/wireless          | 1         | 11.11%  |
| Fingerprint reader    | 1         | 11.11%  |
| Bluetooth             | 1         | 11.11%  |

