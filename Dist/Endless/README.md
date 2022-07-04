Endless - Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Endless/Desktop/README.md) and [notebooks](/Dist/Endless/Notebook/README.md).

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

| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Endless 4.0.6         | 20        | 62.5%   |
| Endless 4.0.7         | 3         | 9.38%   |
| Endless 3.9.7         | 3         | 9.38%   |
| Endless 4.0.4         | 2         | 6.25%   |
| Endless 3.9.3-nexthw1 | 1         | 3.13%   |
| Endless 3.9.1         | 1         | 3.13%   |
| Endless 3.8.3-nexthw1 | 1         | 3.13%   |
| Endless 3.7.8         | 1         | 3.13%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Endless | 32        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.11.0-35-generic | 25        | 78.13%  |
| 5.8.0-14-generic  | 4         | 12.5%   |
| 5.6.0-7-generic   | 1         | 3.13%   |
| 5.3.0-28-generic  | 1         | 3.13%   |
| 5.11.0-12-generic | 1         | 3.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 26        | 81.25%  |
| 5.8.0   | 4         | 12.5%   |
| 5.6.0   | 1         | 3.13%   |
| 5.3.0   | 1         | 3.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 26        | 81.25%  |
| 5.8     | 4         | 12.5%   |
| 5.6     | 1         | 3.13%   |
| 5.3     | 1         | 3.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 32        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name  | Computers | Percent |
|-------|-----------|---------|
| GNOME | 32        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 32        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 32        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| pt_BR | 15        | 46.88%  |
| en_US | 10        | 31.25%  |
| ru_RU | 1         | 3.13%   |
| ro_RO | 1         | 3.13%   |
| pt_PT | 1         | 3.13%   |
| it_IT | 1         | 3.13%   |
| hu_HU | 1         | 3.13%   |
| es_CL | 1         | 3.13%   |
| es_BO | 1         | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 23        | 71.88%  |
| BIOS | 9         | 28.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 31        | 96.88%  |
| Tmpfs | 1         | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 32        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 9         | 28.13%  |
| Acer                | 7         | 21.88%  |
| Dell                | 6         | 18.75%  |
| Hewlett-Packard     | 3         | 9.38%   |
| Gigabyte Technology | 2         | 6.25%   |
| Positivo            | 1         | 3.13%   |
| Packard Bell        | 1         | 3.13%   |
| Microsoft           | 1         | 3.13%   |
| Kllisre             | 1         | 3.13%   |
| AMI                 | 1         | 3.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Acer Nitro AN515-44                        | 4         | 12.5%   |
| Dell Latitude E6530                        | 2         | 6.25%   |
| Dell Inspiron 1525                         | 2         | 6.25%   |
| ASUS VivoBook_ASUSLaptop X515JA_X515JA     | 2         | 6.25%   |
| Positivo J14GL11                           | 1         | 3.13%   |
| Packard Bell EasyNote MH36                 | 1         | 3.13%   |
| Microsoft Surface Book 2                   | 1         | 3.13%   |
| Kllisre B75 V1.1                           | 1         | 3.13%   |
| HP Pavilion dv7                            | 1         | 3.13%   |
| HP Laptop 17z-ca100                        | 1         | 3.13%   |
| HP 20-c023w                                | 1         | 3.13%   |
| Gigabyte H97M-D3H                          | 1         | 3.13%   |
| Gigabyte GA-78LMT-S2P                      | 1         | 3.13%   |
| Dell PowerEdge 2900                        | 1         | 3.13%   |
| Dell Latitude E6330                        | 1         | 3.13%   |
| ASUS Z550SA                                | 1         | 3.13%   |
| ASUS X542UN                                | 1         | 3.13%   |
| ASUS X541UAK                               | 1         | 3.13%   |
| ASUS VivoBook_ASUSLaptop X513EA_X513EA     | 1         | 3.13%   |
| ASUS VivoBook_ASUSLaptop X513EA_K513EA     | 1         | 3.13%   |
| ASUS VivoBook 15_ASUS Laptop X507LA        | 1         | 3.13%   |
| ASUS VivoBook 14_ASUS Laptop X407MA_X407MA | 1         | 3.13%   |
| AMI F3C                                    | 1         | 3.13%   |
| Acer Nitro AN515-54                        | 1         | 3.13%   |
| Acer Aspire E1-421                         | 1         | 3.13%   |
| Acer Aspire A514-54G                       | 1         | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ASUS VivoBook         | 6         | 18.75%  |
| Acer Nitro            | 5         | 15.63%  |
| Dell Latitude         | 3         | 9.38%   |
| Dell Inspiron         | 2         | 6.25%   |
| Acer Aspire           | 2         | 6.25%   |
| Positivo J14GL11      | 1         | 3.13%   |
| Packard Bell EasyNote | 1         | 3.13%   |
| Microsoft Surface     | 1         | 3.13%   |
| Kllisre B75           | 1         | 3.13%   |
| HP Pavilion           | 1         | 3.13%   |
| HP Laptop             | 1         | 3.13%   |
| HP 20-c023w           | 1         | 3.13%   |
| Gigabyte H97M-D3H     | 1         | 3.13%   |
| Gigabyte GA-78LMT-S2P | 1         | 3.13%   |
| Dell PowerEdge        | 1         | 3.13%   |
| ASUS Z550SA           | 1         | 3.13%   |
| ASUS X542UN           | 1         | 3.13%   |
| ASUS X541UAK          | 1         | 3.13%   |
| AMI F3C               | 1         | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 8         | 25%     |
| 2021 | 4         | 12.5%   |
| 2012 | 4         | 12.5%   |
| 2008 | 4         | 12.5%   |
| 2018 | 3         | 9.38%   |
| 2017 | 2         | 6.25%   |
| 2016 | 2         | 6.25%   |
| 2014 | 2         | 6.25%   |
| 2019 | 1         | 3.13%   |
| 2011 | 1         | 3.13%   |
| 2009 | 1         | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 26        | 81.25%  |
| Desktop    | 3         | 9.38%   |
| Tablet     | 1         | 3.13%   |
| All in one | 1         | 3.13%   |
| Server     | 1         | 3.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 24        | 75%     |
| Enabled  | 8         | 25%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 32        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 10        | 31.25%  |
| 3.01-4.0   | 10        | 31.25%  |
| 8.01-16.0  | 7         | 21.88%  |
| 1.01-2.0   | 4         | 12.5%   |
| 2.01-3.0   | 1         | 3.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 16        | 50%     |
| 2.01-3.0 | 6         | 18.75%  |
| 0.51-1.0 | 5         | 15.63%  |
| 3.01-4.0 | 4         | 12.5%   |
| 4.01-8.0 | 1         | 3.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 24        | 75%     |
| 2      | 8         | 25%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 18        | 56.25%  |
| Yes       | 14        | 43.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 75%     |
| No        | 8         | 25%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 90.63%  |
| No        | 3         | 9.38%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 71.88%  |
| No        | 9         | 28.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| Brazil       | 15        | 46.88%  |
| USA          | 6         | 18.75%  |
| Chile        | 2         | 6.25%   |
| Uzbekistan   | 1         | 3.13%   |
| South Africa | 1         | 3.13%   |
| Portugal     | 1         | 3.13%   |
| Nigeria      | 1         | 3.13%   |
| Italy        | 1         | 3.13%   |
| Iran         | 1         | 3.13%   |
| Indonesia    | 1         | 3.13%   |
| Hungary      | 1         | 3.13%   |
| Canada       | 1         | 3.13%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City                | Computers | Percent |
|---------------------|-----------|---------|
| Dallas              | 2         | 6.25%   |
| Criciúma           | 2         | 6.25%   |
| Witbank             | 1         | 3.13%   |
| Villa Alegre        | 1         | 3.13%   |
| Valparaíso         | 1         | 3.13%   |
| Uba                 | 1         | 3.13%   |
| Tucson              | 1         | 3.13%   |
| Tres Rios           | 1         | 3.13%   |
| Tashkent            | 1         | 3.13%   |
| Serramanna          | 1         | 3.13%   |
| Sao Paulo           | 1         | 3.13%   |
| Sao Carlos          | 1         | 3.13%   |
| Santa Cruz do Sul   | 1         | 3.13%   |
| San Francisco       | 1         | 3.13%   |
| Rio de Janeiro      | 1         | 3.13%   |
| Povoa de Santa Iria | 1         | 3.13%   |
| Phoenix             | 1         | 3.13%   |
| Oakville            | 1         | 3.13%   |
| Nova Iguaçu        | 1         | 3.13%   |
| Langarūd           | 1         | 3.13%   |
| Kano                | 1         | 3.13%   |
| Itabira             | 1         | 3.13%   |
| Green Forest        | 1         | 3.13%   |
| Debrecen            | 1         | 3.13%   |
| Cruz Machado        | 1         | 3.13%   |
| Colombo             | 1         | 3.13%   |
| Caiaponia           | 1         | 3.13%   |
| Brasília           | 1         | 3.13%   |
| Banda Aceh          | 1         | 3.13%   |
| Amparo              | 1         | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 13.16%  |
| Unknown             | 4         | 4      | 10.53%  |
| Seagate             | 4         | 4      | 10.53%  |
| Samsung Electronics | 3         | 3      | 7.89%   |
| Kingston            | 3         | 3      | 7.89%   |
| Toshiba             | 2         | 2      | 5.26%   |
| SanDisk             | 2         | 2      | 5.26%   |
| Phison              | 2         | 2      | 5.26%   |
| ADATA Technology    | 2         | 2      | 5.26%   |
| Silicon Motion      | 1         | 1      | 2.63%   |
| PNY                 | 1         | 1      | 2.63%   |
| MidasForce          | 1         | 1      | 2.63%   |
| Maxtor              | 1         | 1      | 2.63%   |
| LITEONIT            | 1         | 1      | 2.63%   |
| Intel               | 1         | 1      | 2.63%   |
| HS-SSD-C100         | 1         | 1      | 2.63%   |
| Hitachi             | 1         | 1      | 2.63%   |
| HGST                | 1         | 1      | 2.63%   |
| Fujitsu             | 1         | 1      | 2.63%   |
| Corsair             | 1         | 1      | 2.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| WDC WD10SPZX-21Z10T0 1TB              | 3         | 7.89%   |
| Toshiba MQ01ABF050 500GB              | 2         | 5.26%   |
| SanDisk NVMe SSD Drive 512GB          | 2         | 5.26%   |
| Samsung NVMe SSD Drive 256GB          | 2         | 5.26%   |
| Phison NVMe SSD Drive 256GB           | 2         | 5.26%   |
| ADATA NVMe SSD Drive 256GB            | 2         | 5.26%   |
| WDC WD5000LPCX-80VHAT0 500GB          | 1         | 2.63%   |
| WDC WD3200BPVT-22JJ5T0 320GB          | 1         | 2.63%   |
| Unknown SD/MMC/MS PRO 128GB           | 1         | 2.63%   |
| Unknown MMC Card  942MB               | 1         | 2.63%   |
| Unknown MMC Card  32GB                | 1         | 2.63%   |
| Unknown MMC Card  2GB                 | 1         | 2.63%   |
| Silicon Motion NVMe SSD Drive 256GB   | 1         | 2.63%   |
| Seagate ST9160314AS 160GB             | 1         | 2.63%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 2.63%   |
| Seagate ST500LM030-1RK17D 500GB       | 1         | 2.63%   |
| Seagate ST3000DM001-9YN166 3TB        | 1         | 2.63%   |
| Samsung SSD 750 EVO 250GB             | 1         | 2.63%   |
| PNY CS900 500GB SSD                   | 1         | 2.63%   |
| MidasForce SSD 256GB                  | 1         | 2.63%   |
| Maxtor STM3160215AS 160GB             | 1         | 2.63%   |
| LITEONIT LCM-128M3S 2.5 7mm 128GB SSD | 1         | 2.63%   |
| Kingston SA400S37240G 240GB SSD       | 1         | 2.63%   |
| Kingston NVMe SSD Drive 500GB         | 1         | 2.63%   |
| Kingston NVMe SSD Drive 256GB         | 1         | 2.63%   |
| Intel NVMe SSD Drive 128GB            | 1         | 2.63%   |
| HS-SSD-C100 480G                      | 1         | 2.63%   |
| Hitachi HTS543216L9A300 160GB         | 1         | 2.63%   |
| HGST HTS541010B7E610 1TB              | 1         | 2.63%   |
| Fujitsu MHZ2080BH G2 80GB             | 1         | 2.63%   |
| Corsair Force GT 120GB SSD            | 1         | 2.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 31.25%  |
| Seagate | 4         | 4      | 25%     |
| Toshiba | 2         | 2      | 12.5%   |
| Unknown | 1         | 1      | 6.25%   |
| Maxtor  | 1         | 1      | 6.25%   |
| Hitachi | 1         | 1      | 6.25%   |
| HGST    | 1         | 1      | 6.25%   |
| Fujitsu | 1         | 1      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 16.67%  |
| PNY                 | 1         | 1      | 16.67%  |
| MidasForce          | 1         | 1      | 16.67%  |
| LITEONIT            | 1         | 1      | 16.67%  |
| Kingston            | 1         | 1      | 16.67%  |
| Corsair             | 1         | 1      | 16.67%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 16        | 16     | 42.11%  |
| NVMe    | 12        | 12     | 31.58%  |
| SSD     | 6         | 6      | 15.79%  |
| MMC     | 3         | 3      | 7.89%   |
| Unknown | 1         | 1      | 2.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 22        | 22     | 57.89%  |
| NVMe | 12        | 12     | 31.58%  |
| MMC  | 3         | 3      | 7.89%   |
| SAS  | 1         | 1      | 2.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 16        | 17     | 76.19%  |
| 0.51-1.0   | 4         | 4      | 19.05%  |
| 2.01-3.0   | 1         | 1      | 4.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 13        | 40.63%  |
| 251-500    | 10        | 31.25%  |
| 501-1000   | 4         | 12.5%   |
| 51-100     | 3         | 9.38%   |
| 21-50      | 1         | 3.13%   |
| 2001-3000  | 1         | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 21-50    | 18        | 56.25%  |
| 51-100   | 6         | 18.75%  |
| 1-20     | 3         | 9.38%   |
| 251-500  | 2         | 6.25%   |
| 101-250  | 2         | 6.25%   |
| 501-1000 | 1         | 3.13%   |

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
| Detected | 32        | 38     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 23        | 57.5%   |
| AMD                         | 6         | 15%     |
| SanDisk                     | 2         | 5%      |
| Samsung Electronics         | 2         | 5%      |
| Phison Electronics          | 2         | 5%      |
| Kingston Technology Company | 2         | 5%      |
| ADATA Technology            | 2         | 5%      |
| Silicon Motion              | 1         | 2.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 10.64%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 10.64%  |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 6.38%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 3         | 6.38%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 4.26%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 4.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 4.26%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 4.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 4.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 4.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 4.26%   |
| ADATA Non-Volatile memory controller                                             | 2         | 4.26%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 2.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 2.13%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 2.13%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                               | 1         | 2.13%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 2.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 2.13%   |
| Intel PROSet/Wireless WiFi Software extension                                    | 1         | 2.13%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1         | 2.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 2.13%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 2.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 2.13%   |
| Intel 631xESB/632xESB/3100 Chipset SATA IDE Controller                           | 1         | 2.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 2.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 23        | 48.94%  |
| NVMe | 12        | 25.53%  |
| RAID | 7         | 14.89%  |
| IDE  | 5         | 10.64%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 25        | 78.13%  |
| AMD    | 7         | 21.88%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 12.5%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 6.25%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 6.25%   |
| Intel Xeon CPU E5335 @ 2.00GHz                | 1         | 3.13%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 3.13%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 3.13%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 3.13%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 3.13%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 3.13%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 3.13%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 1         | 3.13%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 3.13%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 1         | 3.13%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 3.13%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 3.13%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 3.13%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 1         | 3.13%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 3.13%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 3.13%   |
| Intel Celeron CPU J3060 @ 1.60GHz             | 1         | 3.13%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 3.13%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 3.13%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 3.13%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 3.13%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.13%   |
| AMD FX-8120 Eight-Core Processor              | 1         | 3.13%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 1         | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 6         | 18.75%  |
| Intel Core i3           | 4         | 12.5%   |
| AMD Ryzen 7             | 4         | 12.5%   |
| Other                   | 3         | 9.38%   |
| Intel Core i5           | 3         | 9.38%   |
| Intel Celeron           | 3         | 9.38%   |
| Intel Xeon              | 1         | 3.13%   |
| Intel Pentium Silver    | 1         | 3.13%   |
| Intel Pentium Dual-Core | 1         | 3.13%   |
| Intel Pentium Dual      | 1         | 3.13%   |
| Intel Core 2 Duo        | 1         | 3.13%   |
| Intel Atom              | 1         | 3.13%   |
| AMD Ryzen 5             | 1         | 3.13%   |
| AMD FX                  | 1         | 3.13%   |
| AMD E1                  | 1         | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 14        | 43.75%  |
| 2      | 14        | 43.75%  |
| 8      | 4         | 12.5%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 32        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 20        | 62.5%   |
| 1      | 12        | 37.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 32        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x08600103 | 4         | 12.5%   |
| 0x806c1    | 3         | 9.38%   |
| 0x406c4    | 3         | 9.38%   |
| 0x306a9    | 3         | 9.38%   |
| 0x806ea    | 2         | 6.25%   |
| 0x706e5    | 2         | 6.25%   |
| 0x706a1    | 2         | 6.25%   |
| 0x6fd      | 2         | 6.25%   |
| 0x206a7    | 2         | 6.25%   |
| 0x906ed    | 1         | 3.13%   |
| 0x6fb      | 1         | 3.13%   |
| 0x406e3    | 1         | 3.13%   |
| 0x306d4    | 1         | 3.13%   |
| 0x306c3    | 1         | 3.13%   |
| 0x1067a    | 1         | 3.13%   |
| 0x08108109 | 1         | 3.13%   |
| 0x0600063e | 1         | 3.13%   |
| 0x05000119 | 1         | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| Zen 2         | 4         | 12.5%   |
| TigerLake     | 3         | 9.38%   |
| Silvermont    | 3         | 9.38%   |
| KabyLake      | 3         | 9.38%   |
| IvyBridge     | 3         | 9.38%   |
| Core          | 3         | 9.38%   |
| SandyBridge   | 2         | 6.25%   |
| IceLake       | 2         | 6.25%   |
| Goldmont plus | 2         | 6.25%   |
| Zen+          | 1         | 3.13%   |
| Skylake       | 1         | 3.13%   |
| Penryn        | 1         | 3.13%   |
| Haswell       | 1         | 3.13%   |
| Bulldozer     | 1         | 3.13%   |
| Broadwell     | 1         | 3.13%   |
| Bobcat        | 1         | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 23        | 53.49%  |
| Nvidia | 10        | 23.26%  |
| AMD    | 10        | 23.26%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia TU117M                                                                            | 4         | 8.89%   |
| AMD Renoir                                                                               | 4         | 8.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 6.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 6.67%   |
| Intel UHD Graphics 620                                                                   | 2         | 4.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 4.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 4.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 4.44%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 4.44%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 2.22%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 2.22%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 2.22%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 2.22%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 2.22%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 1         | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 2.22%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 2.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 2.22%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.22%   |
| Intel HD Graphics 5500                                                                   | 1         | 2.22%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 2.22%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 2.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 2.22%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 2.22%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 2.22%   |
| AMD RS780L [Radeon 3000]                                                                 | 1         | 2.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 2.22%   |
| AMD ES1000                                                                               | 1         | 2.22%   |
| AMD Cypress PRO [Radeon HD 5850]                                                         | 1         | 2.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 50%     |
| Intel + Nvidia | 5         | 15.63%  |
| AMD + Nvidia   | 4         | 12.5%   |
| 1 x AMD        | 4         | 12.5%   |
| Intel + AMD    | 2         | 6.25%   |
| 1 x Nvidia     | 1         | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 24        | 75%     |
| Proprietary | 8         | 25%     |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 56.25%  |
| 0.01-0.5   | 5         | 15.63%  |
| 3.01-4.0   | 3         | 9.38%   |
| 1.01-2.0   | 3         | 9.38%   |
| 0.51-1.0   | 3         | 9.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 6         | 19.35%  |
| LG Display          | 5         | 16.13%  |
| PANDA               | 4         | 12.9%   |
| BOE                 | 4         | 12.9%   |
| Samsung Electronics | 2         | 6.45%   |
| Goldstar            | 2         | 6.45%   |
| AU Optronics        | 2         | 6.45%   |
| Panasonic           | 1         | 3.23%   |
| Optoma              | 1         | 3.23%   |
| LG Philips          | 1         | 3.23%   |
| KDC                 | 1         | 3.23%   |
| Hewlett-Packard     | 1         | 3.23%   |
| AOC                 | 1         | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 4         | 12.9%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch         | 2         | 6.45%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 2         | 6.45%   |
| BOE LCD Monitor BOE07AA 1366x768 344x194mm 15.5-inch                 | 2         | 6.45%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 330x210mm 15.4-inch | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 261x163mm 12.1-inch | 1         | 3.23%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch          | 1         | 3.23%   |
| Optoma SVGA OTM0321 1280x1024                                        | 1         | 3.23%   |
| LG Philips LCD Monitor LPLB900 1280x800 330x210mm 15.4-inch          | 1         | 3.23%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 1         | 3.23%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch         | 1         | 3.23%   |
| LG Display LCD Monitor LGD034C 1366x768 293x165mm 13.2-inch          | 1         | 3.23%   |
| KDC LCD Monitor KDC0830 1920x1080 344x193mm 15.5-inch                | 1         | 3.23%   |
| Hewlett-Packard ALL-in-One HWP4245 1600x900 434x236mm 19.4-inch      | 1         | 3.23%   |
| Goldstar L1510BF GSM3B7E 1024x768 304x228mm 15.0-inch                | 1         | 3.23%   |
| Goldstar E2355V GSM58FE 1920x1080 510x290mm 23.1-inch                | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN142E 1366x768 309x173mm 13.9-inch      | 1         | 3.23%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                 | 1         | 3.23%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                 | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch        | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch        | 1         | 3.23%   |
| AOC 936W AOC1936 1366x768 410x230mm 18.5-inch                        | 1         | 3.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 12        | 38.71%  |
| 1366x768 (WXGA)  | 11        | 35.48%  |
| 1600x900 (HD+)   | 2         | 6.45%   |
| 1280x800 (WXGA)  | 2         | 6.45%   |
| 3840x2160 (4K)   | 1         | 3.23%   |
| 1440x900 (WXGA+) | 1         | 3.23%   |
| 1280x1024 (SXGA) | 1         | 3.23%   |
| 1024x768 (XGA)   | 1         | 3.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 18        | 58.06%  |
| 13      | 5         | 16.13%  |
| 17      | 3         | 9.68%   |
| 23      | 1         | 3.23%   |
| 19      | 1         | 3.23%   |
| 18      | 1         | 3.23%   |
| 14      | 1         | 3.23%   |
| Unknown | 1         | 3.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 74.19%  |
| 351-400     | 3         | 9.68%   |
| 401-500     | 2         | 6.45%   |
| 501-600     | 1         | 3.23%   |
| 201-300     | 1         | 3.23%   |
| Unknown     | 1         | 3.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 26        | 83.87%  |
| 16/10 | 3         | 9.68%   |
| 5/4   | 1         | 3.23%   |
| 4/3   | 1         | 3.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 58.06%  |
| 81-90          | 5         | 16.13%  |
| 121-130        | 3         | 9.68%   |
| 71-80          | 1         | 3.23%   |
| 201-250        | 1         | 3.23%   |
| 151-200        | 1         | 3.23%   |
| 141-150        | 1         | 3.23%   |
| Unknown        | 1         | 3.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 12        | 38.71%  |
| 121-160       | 11        | 35.48%  |
| 51-100        | 6         | 19.35%  |
| More than 240 | 1         | 3.23%   |
| Unknown       | 1         | 3.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 32        | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 18        | 34.62%  |
| Intel                           | 15        | 28.85%  |
| Qualcomm Atheros                | 5         | 9.62%   |
| Marvell Technology Group        | 3         | 5.77%   |
| Broadcom                        | 3         | 5.77%   |
| Texas Instruments               | 1         | 1.92%   |
| Samsung Electronics             | 1         | 1.92%   |
| Ralink Technology               | 1         | 1.92%   |
| Ralink                          | 1         | 1.92%   |
| Qualcomm Atheros Communications | 1         | 1.92%   |
| MediaTek                        | 1         | 1.92%   |
| Huawei Technologies             | 1         | 1.92%   |
| Dell                            | 1         | 1.92%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 13.33%  |
| Intel Wi-Fi 6 AX200                                               | 5         | 8.33%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 6.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 5%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 5%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 3.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 3.33%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 3.33%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 3.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 3.33%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 3.33%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 3.33%   |
| Texas Instruments CC2531 ZigBee                                   | 1         | 1.67%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.67%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1         | 1.67%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                            | 1         | 1.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.67%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.67%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.67%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 1.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.67%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 1         | 1.67%   |
| Intel Wireless 3165                                               | 1         | 1.67%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 1.67%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 1.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 1.67%   |
| Huawei E353/E3131                                                 | 1         | 1.67%   |
| Dell Wireless 5630 (EVDO-HSPA) Mobile Broadband Mini-Card         | 1         | 1.67%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                    | 1         | 1.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 45.45%  |
| Realtek Semiconductor           | 6         | 18.18%  |
| Qualcomm Atheros                | 4         | 12.12%  |
| Broadcom                        | 2         | 6.06%   |
| Ralink Technology               | 1         | 3.03%   |
| Ralink                          | 1         | 3.03%   |
| Qualcomm Atheros Communications | 1         | 3.03%   |
| MediaTek                        | 1         | 3.03%   |
| Marvell Technology Group        | 1         | 3.03%   |
| Dell                            | 1         | 3.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 5         | 15.15%  |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 3         | 9.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 2         | 6.06%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 6.06%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 2         | 6.06%   |
| Intel Centrino Ultimate-N 6300                                | 2         | 6.06%   |
| Broadcom BCM4312 802.11b/g LP-PHY                             | 2         | 6.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 3.03%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter               | 1         | 3.03%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                        | 1         | 3.03%   |
| Ralink MT7601U Wireless Adapter                               | 1         | 3.03%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                     | 1         | 3.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 3.03%   |
| Qualcomm Atheros AR9271 802.11n                               | 1         | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1         | 3.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 3.03%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless             | 1         | 3.03%   |
| Intel Wireless 3165                                           | 1         | 3.03%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection | 1         | 3.03%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                 | 1         | 3.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 1         | 3.03%   |
| Dell Wireless 5630 (EVDO-HSPA) Mobile Broadband Mini-Card     | 1         | 3.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 16        | 61.54%  |
| Intel                    | 3         | 11.54%  |
| Qualcomm Atheros         | 2         | 7.69%   |
| Marvell Technology Group | 2         | 7.69%   |
| Samsung Electronics      | 1         | 3.85%   |
| Huawei Technologies      | 1         | 3.85%   |
| Broadcom                 | 1         | 3.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 30.77%  |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 15.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 11.54%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 11.54%  |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 7.69%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 7.69%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 3.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 3.85%   |
| Huawei E353/E3131                                                 | 1         | 3.85%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                    | 1         | 3.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 53.7%   |
| Ethernet | 24        | 44.44%  |
| Modem    | 1         | 1.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 87.1%   |
| Ethernet | 4         | 12.9%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 19        | 59.38%  |
| 1     | 11        | 34.38%  |
| 3     | 1         | 3.13%   |
| 0     | 1         | 3.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 25        | 78.13%  |
| Yes  | 7         | 21.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 11        | 47.83%  |
| Realtek Semiconductor | 4         | 17.39%  |
| IMC Networks          | 3         | 13.04%  |
| Dell                  | 3         | 13.04%  |
| Marvell Semiconductor | 1         | 4.35%   |
| Lite-On Technology    | 1         | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                            | 5         | 21.74%  |
| Realtek Bluetooth Radio                          | 3         | 13.04%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 3         | 13.04%  |
| IMC Networks Bluetooth Device                    | 3         | 13.04%  |
| Dell BCM20702A0 Bluetooth Module                 | 2         | 8.7%    |
| Realtek  Bluetooth 4.2 Adapter                   | 1         | 4.35%   |
| Marvell Bluetooth and Wireless LAN Composite     | 1         | 4.35%   |
| Lite-On Wireless_Device                          | 1         | 4.35%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 4.35%   |
| Intel Bluetooth wireless interface               | 1         | 4.35%   |
| Intel Bluetooth Device                           | 1         | 4.35%   |
| Dell Wireless 355 Bluetooth                      | 1         | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 23        | 60.53%  |
| AMD    | 8         | 21.05%  |
| Nvidia | 7         | 18.42%  |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 11.9%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 11.9%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 9.52%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 7.14%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 7.14%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 4.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 4.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 4.76%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 4.76%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 2.38%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 2.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 2.38%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 2.38%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 2.38%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 2.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 2.38%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 2.38%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 2.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2.38%   |
| AMD FCH Azalia Controller                                                                         | 1         | 2.38%   |
| AMD Cypress HDMI Audio [Radeon HD 5830/5850/5870 / 6850/6870 Rebrand]                             | 1         | 2.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

Zero info for selected period =(

Memory Model
------------

Memory module models

Zero info for selected period =(

Memory Kind
-----------

Memory module kinds

Zero info for selected period =(

Memory Form Factor
------------------

Physical design of the memory module

Zero info for selected period =(

Memory Size
-----------

Memory module size

Zero info for selected period =(

Memory Speed
------------

Memory module speed

Zero info for selected period =(

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
| Quanta                                 | 6         | 25%     |
| IMC Networks                           | 4         | 16.67%  |
| Chicony Electronics                    | 4         | 16.67%  |
| Sonix Technology                       | 2         | 8.33%   |
| Microdia                               | 2         | 8.33%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 8.33%   |
| Sunplus Innovation Technology          | 1         | 4.17%   |
| OmniVision Technologies                | 1         | 4.17%   |
| GEMBIRD                                | 1         | 4.17%   |
| Acer                                   | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Quanta HD User Facing                                       | 5         | 20.83%  |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 12.5%   |
| Sonix USB2.0 HD UVC WebCam                                  | 2         | 8.33%   |
| Microdia Dell Integrated HD Webcam                          | 2         | 8.33%   |
| Chicony USB2.0 VGA UVC WebCam                               | 2         | 8.33%   |
| Sunplus HD WebCam                                           | 1         | 4.17%   |
| Quanta USB2.0 HD UVC WebCam                                 | 1         | 4.17%   |
| OmniVision OV2640 Webcam                                    | 1         | 4.17%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 4.17%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]           | 1         | 4.17%   |
| Chicony HP TrueVision HD Camera                             | 1         | 4.17%   |
| Chicony HD User Facing                                      | 1         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) HP Integrated Webcam | 1         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) FE03FF-99            | 1         | 4.17%   |
| Acer HP TrueVision HD Webcam                                | 1         | 4.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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

| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 23        | 71.88%  |
| 1     | 8         | 25%     |
| 2     | 1         | 3.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 6         | 60%     |
| Net/wireless          | 2         | 20%     |
| Chipcard              | 2         | 20%     |

