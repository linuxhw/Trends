Endless - Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Endless/Desktop/README.md) and [notebooks](/Dist/Endless/Notebook/README.md).

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

| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Endless 4.0.13        | 17        | 56.67%  |
| Endless 3.9.7         | 7         | 23.33%  |
| Endless 3.9.3-nexthw1 | 2         | 6.67%   |
| Endless 5.0.0         | 1         | 3.33%   |
| Endless 4.0.4         | 1         | 3.33%   |
| Endless 4.0.10        | 1         | 3.33%   |
| Endless 3.8.7-nexthw2 | 1         | 3.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Endless | 30        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.11.0-35-generic | 19        | 63.33%  |
| 5.8.0-14-generic  | 8         | 26.67%  |
| 5.11.0-12-generic | 2         | 6.67%   |
| 5.15.0-47-generic | 1         | 3.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 21        | 70%     |
| 5.8.0   | 8         | 26.67%  |
| 5.15.0  | 1         | 3.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 21        | 70%     |
| 5.8     | 8         | 26.67%  |
| 5.15    | 1         | 3.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 30        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name  | Computers | Percent |
|-------|-----------|---------|
| GNOME | 30        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 29        | 96.67%  |
| Wayland | 1         | 3.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 30        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| pt_BR | 13        | 43.33%  |
| en_US | 5         | 16.67%  |
| ro_RO | 2         | 6.67%   |
| fr_FR | 2         | 6.67%   |
| es_CO | 2         | 6.67%   |
| ru_RU | 1         | 3.33%   |
| hu_HU | 1         | 3.33%   |
| hr_HR | 1         | 3.33%   |
| es_MX | 1         | 3.33%   |
| es_ES | 1         | 3.33%   |
| de_DE | 1         | 3.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 23        | 76.67%  |
| BIOS | 7         | 23.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 29        | 96.67%  |
| Tmpfs | 1         | 3.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 30        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| ASUSTek Computer | 17        | 56.67%  |
| Acer             | 6         | 20%     |
| Lenovo           | 5         | 16.67%  |
| Packard Bell     | 1         | 3.33%   |
| Dell             | 1         | 3.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop X515DA_X515DA     | 3         | 10%     |
| Acer Nitro AN515-44                        | 2         | 6.67%   |
| Packard Bell EasyNote ML65                 | 1         | 3.33%   |
| Lenovo ThinkPad W520 4284Y54               | 1         | 3.33%   |
| Lenovo ThinkCentre M58e 7303BZ2            | 1         | 3.33%   |
| Lenovo IdeaPad S145-14IWL 81MU             | 1         | 3.33%   |
| Lenovo IdeaPad 320-15IKB 80YH              | 1         | 3.33%   |
| Lenovo G450 2949                           | 1         | 3.33%   |
| Dell XPS 13 9360                           | 1         | 3.33%   |
| ASUS ZenBook UX425UA_UM425UA               | 1         | 3.33%   |
| ASUS Z550SA                                | 1         | 3.33%   |
| ASUS X510UNR                               | 1         | 3.33%   |
| ASUS VivoBook_ASUSLaptop X515JA_X515JA     | 1         | 3.33%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA     | 1         | 3.33%   |
| ASUS VivoBook_ASUSLaptop X513EAN_X513EAN   | 1         | 3.33%   |
| ASUS VivoBook_ASUSLaptop X513EAN_K513EA    | 1         | 3.33%   |
| ASUS VivoBook_ASUSLaptop X415JA_X415JA     | 1         | 3.33%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 1         | 3.33%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 1         | 3.33%   |
| ASUS VivoBook 12_ASUS Laptop E203MA_E203MA | 1         | 3.33%   |
| ASUS S301LA                                | 1         | 3.33%   |
| ASUS ASUS EXPERTBOOK B1500CEAE_B1500CEAE   | 1         | 3.33%   |
| ASUS All Series                            | 1         | 3.33%   |
| Acer Nitro AN515-54                        | 1         | 3.33%   |
| Acer Aspire A517-51                        | 1         | 3.33%   |
| Acer Aspire A315-54                        | 1         | 3.33%   |
| Acer Aspire A315-21                        | 1         | 3.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ASUS VivoBook         | 11        | 36.67%  |
| Acer Nitro            | 3         | 10%     |
| Acer Aspire           | 3         | 10%     |
| Lenovo IdeaPad        | 2         | 6.67%   |
| Packard Bell EasyNote | 1         | 3.33%   |
| Lenovo ThinkPad       | 1         | 3.33%   |
| Lenovo ThinkCentre    | 1         | 3.33%   |
| Lenovo G450           | 1         | 3.33%   |
| Dell XPS              | 1         | 3.33%   |
| ASUS ZenBook          | 1         | 3.33%   |
| ASUS Z550SA           | 1         | 3.33%   |
| ASUS X510UNR          | 1         | 3.33%   |
| ASUS S301LA           | 1         | 3.33%   |
| ASUS ASUS             | 1         | 3.33%   |
| ASUS All              | 1         | 3.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 6         | 20%     |
| 2020 | 6         | 20%     |
| 2017 | 4         | 13.33%  |
| 2019 | 3         | 10%     |
| 2018 | 3         | 10%     |
| 2016 | 2         | 6.67%   |
| 2015 | 1         | 3.33%   |
| 2013 | 1         | 3.33%   |
| 2011 | 1         | 3.33%   |
| 2010 | 1         | 3.33%   |
| 2009 | 1         | 3.33%   |
| 2008 | 1         | 3.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 28        | 93.33%  |
| Desktop  | 2         | 6.67%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 25        | 83.33%  |
| Enabled  | 5         | 16.67%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 30        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 12        | 40%     |
| 3.01-4.0   | 10        | 33.33%  |
| 8.01-16.0  | 4         | 13.33%  |
| 16.01-24.0 | 2         | 6.67%   |
| 2.01-3.0   | 1         | 3.33%   |
| 1.01-2.0   | 1         | 3.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 11        | 36.67%  |
| 2.01-3.0 | 8         | 26.67%  |
| 4.01-8.0 | 4         | 13.33%  |
| 0.51-1.0 | 4         | 13.33%  |
| 3.01-4.0 | 3         | 10%     |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 26        | 86.67%  |
| 2      | 4         | 13.33%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 24        | 80%     |
| Yes       | 6         | 20%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 50%     |
| No        | 15        | 50%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 96.67%  |
| No        | 1         | 3.33%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 83.33%  |
| No        | 5         | 16.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country   | Computers | Percent |
|-----------|-----------|---------|
| Brazil    | 13        | 43.33%  |
| Romania   | 3         | 10%     |
| Colombia  | 3         | 10%     |
| Russia    | 2         | 6.67%   |
| Germany   | 2         | 6.67%   |
| France    | 2         | 6.67%   |
| USA       | 1         | 3.33%   |
| Spain     | 1         | 3.33%   |
| Indonesia | 1         | 3.33%   |
| Hungary   | 1         | 3.33%   |
| Croatia   | 1         | 3.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Sao Paulo            | 4         | 13.33%  |
| Campo Grande         | 2         | 6.67%   |
| Zheleznodorozhnyy    | 1         | 3.33%   |
| Vélizy-Villacoublay | 1         | 3.33%   |
| Tunja                | 1         | 3.33%   |
| Szombathely          | 1         | 3.33%   |
| Stolberg             | 1         | 3.33%   |
| Sighetu Marmaţiei   | 1         | 3.33%   |
| Rosenheim            | 1         | 3.33%   |
| Recife               | 1         | 3.33%   |
| Râmnicu Vâlcea     | 1         | 3.33%   |
| Quijas               | 1         | 3.33%   |
| Popesti-Leordeni     | 1         | 3.33%   |
| Osijek               | 1         | 3.33%   |
| Moscow               | 1         | 3.33%   |
| Lorica               | 1         | 3.33%   |
| Itabirito            | 1         | 3.33%   |
| Fortaleza            | 1         | 3.33%   |
| Fameck               | 1         | 3.33%   |
| Depok                | 1         | 3.33%   |
| Dallas               | 1         | 3.33%   |
| Campina Grande       | 1         | 3.33%   |
| Camaçari            | 1         | 3.33%   |
| Birigui              | 1         | 3.33%   |
| Barranquilla         | 1         | 3.33%   |
| Barra Do Garcas      | 1         | 3.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 17.65%  |
| ADATA Technology    | 5         | 5      | 14.71%  |
| Sandisk             | 4         | 4      | 11.76%  |
| WDC                 | 3         | 3      | 8.82%   |
| Micron Technology   | 3         | 3      | 8.82%   |
| Toshiba             | 2         | 2      | 5.88%   |
| Samsung Electronics | 2         | 2      | 5.88%   |
| Intel               | 2         | 2      | 5.88%   |
| China               | 2         | 2      | 5.88%   |
| XrayDisk            | 1         | 1      | 2.94%   |
| Unknown             | 1         | 1      | 2.94%   |
| SK hynix            | 1         | 1      | 2.94%   |
| Phison Electronics  | 1         | 1      | 2.94%   |
| Hitachi             | 1         | 1      | 2.94%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| ADATA SM2P32A8-256GC1 256GB                         | 5         | 14.71%  |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 3         | 8.82%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 2         | 5.88%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 5.88%   |
| XrayDisk 480GB SSD                                  | 1         | 2.94%   |
| WDC WD5000LPCX-80VHAT0 500GB                        | 1         | 2.94%   |
| Unknown MMC Card  64GB                              | 1         | 2.94%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 2.94%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 2.94%   |
| SK hynix HFM512GD3JX013N 512GB                      | 1         | 2.94%   |
| Seagate ST9250827AS 250GB                           | 1         | 2.94%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 2.94%   |
| Seagate ST3500312CS 500GB                           | 1         | 2.94%   |
| Seagate ST3250318AS 249GB                           | 1         | 2.94%   |
| SanDisk SD9SN8W128G1002 128GB SSD                   | 1         | 2.94%   |
| Samsung SSD 870 EVO 500GB                           | 1         | 2.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 2.94%   |
| Phison PS5013 E13 NVMe Controller 256GB             | 1         | 2.94%   |
| Micron 2210_MTFDHBA512QFD 512GB                     | 1         | 2.94%   |
| Micron 1300_MTFDDAK256TDL 256GB SSD                 | 1         | 2.94%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 1         | 2.94%   |
| Intel WDC PC SN520 SDAPNUW-512G-1014 512GB          | 1         | 2.94%   |
| Intel IM2P33F8BR1-128GB                             | 1         | 2.94%   |
| Hitachi HTS543225A7A384 250GB                       | 1         | 2.94%   |
| China SSD 480GB                                     | 1         | 2.94%   |
| China SSD 128GB                                     | 1         | 2.94%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 50%     |
| WDC     | 3         | 3      | 25%     |
| Toshiba | 2         | 2      | 16.67%  |
| Hitachi | 1         | 1      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Micron Technology   | 2         | 2      | 28.57%  |
| China               | 2         | 2      | 28.57%  |
| XrayDisk            | 1         | 1      | 14.29%  |
| SanDisk             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 14        | 14     | 41.18%  |
| HDD  | 12        | 12     | 35.29%  |
| SSD  | 7         | 7      | 20.59%  |
| MMC  | 1         | 1      | 2.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 17        | 19     | 53.13%  |
| NVMe | 14        | 14     | 43.75%  |
| MMC  | 1         | 1      | 3.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 14        | 14     | 73.68%  |
| 0.51-1.0   | 5         | 5      | 26.32%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 11        | 36.67%  |
| 251-500    | 10        | 33.33%  |
| 501-1000   | 5         | 16.67%  |
| 1-20       | 2         | 6.67%   |
| 1001-2000  | 1         | 3.33%   |
| 51-100     | 1         | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 21-50    | 16        | 53.33%  |
| 101-250  | 4         | 13.33%  |
| 1-20     | 3         | 10%     |
| 51-100   | 3         | 10%     |
| 251-500  | 2         | 6.67%   |
| 501-1000 | 2         | 6.67%   |

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

![Drive Status](./images/pie_chart/drive_status.svg)

![Drive Status](./images/line_chart/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 30        | 34     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 21        | 52.5%   |
| AMD                 | 7         | 17.5%   |
| ADATA Technology    | 5         | 12.5%   |
| SanDisk             | 3         | 7.5%    |
| SK hynix            | 1         | 2.5%    |
| Samsung Electronics | 1         | 2.5%    |
| Phison Electronics  | 1         | 2.5%    |
| Micron Technology   | 1         | 2.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 14.89%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 10.64%  |
| ADATA A Non-Volatile memory controller                                           | 5         | 10.64%  |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 8.51%   |
| Intel Tiger Lake-LP SATA Controller                                              | 4         | 8.51%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 6.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 6.38%   |
| Intel PROSet/Wireless WiFi Software extension                                    | 2         | 4.26%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 4.26%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 2.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 2.13%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 2.13%   |
| Micron Non-Volatile memory controller                                            | 1         | 2.13%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 2.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 2.13%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 2.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.13%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 2.13%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 2.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 2.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 2.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 24        | 52.17%  |
| NVMe | 14        | 30.43%  |
| RAID | 7         | 15.22%  |
| IDE  | 1         | 2.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 22        | 73.33%  |
| AMD    | 8         | 26.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 10%     |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 6.67%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 6.67%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 6.67%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 6.67%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 6.67%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 3.33%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 3.33%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 3.33%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 3.33%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 3.33%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 3.33%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 3.33%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 1         | 3.33%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz          | 1         | 3.33%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 1         | 3.33%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 3.33%   |
| Intel Celeron CPU J1900 @ 1.99GHz             | 1         | 3.33%   |
| Intel Celeron CPU B810 @ 1.60GHz              | 1         | 3.33%   |
| Intel Celeron CPU 4205U @ 1.80GHz             | 1         | 3.33%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 3.33%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 3.33%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 3.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Other                   | 6         | 20%     |
| Intel Core i5           | 6         | 20%     |
| Intel Celeron           | 6         | 20%     |
| AMD Ryzen 5             | 5         | 16.67%  |
| Intel Core i3           | 2         | 6.67%   |
| Intel Core 2 Duo        | 2         | 6.67%   |
| Intel Pentium Dual-Core | 1         | 3.33%   |
| Intel Core i7           | 1         | 3.33%   |
| AMD Ryzen 7             | 1         | 3.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 15        | 50%     |
| 4      | 12        | 40%     |
| 6      | 2         | 6.67%   |
| 8      | 1         | 3.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 19        | 63.33%  |
| 1      | 11        | 36.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 30        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 4         | 13.33%  |
| 0x1067a    | 3         | 10%     |
| 0x08108109 | 3         | 10%     |
| 0x806ea    | 2         | 6.67%   |
| 0x706e5    | 2         | 6.67%   |
| 0x706a1    | 2         | 6.67%   |
| 0x08600103 | 2         | 6.67%   |
| 0x906ea    | 1         | 3.33%   |
| 0x806eb    | 1         | 3.33%   |
| 0x806e9    | 1         | 3.33%   |
| 0x406e3    | 1         | 3.33%   |
| 0x406c4    | 1         | 3.33%   |
| 0x40651    | 1         | 3.33%   |
| 0x30679    | 1         | 3.33%   |
| 0x206a7    | 1         | 3.33%   |
| 0x08608103 | 1         | 3.33%   |
| 0x06006705 | 1         | 3.33%   |
| 0x06006704 | 1         | 3.33%   |
| Unknown    | 1         | 3.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 6         | 20%     |
| TigerLake     | 4         | 13.33%  |
| Zen+          | 3         | 10%     |
| Penryn        | 3         | 10%     |
| Zen 2         | 2         | 6.67%   |
| Silvermont    | 2         | 6.67%   |
| IceLake       | 2         | 6.67%   |
| Goldmont plus | 2         | 6.67%   |
| Excavator     | 2         | 6.67%   |
| Skylake       | 1         | 3.33%   |
| SandyBridge   | 1         | 3.33%   |
| Haswell       | 1         | 3.33%   |
| Unknown       | 1         | 3.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 21        | 61.76%  |
| AMD    | 9         | 26.47%  |
| Nvidia | 4         | 11.76%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 8.82%   |
| Nvidia TU117M                                                                            | 2         | 5.88%   |
| Intel UHD Graphics 620                                                                   | 2         | 5.88%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 5.88%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 5.88%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 5.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 5.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 5.88%   |
| AMD Renoir                                                                               | 2         | 5.88%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 2.94%   |
| Nvidia GF108GLM [Quadro 1000M]                                                           | 1         | 2.94%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                              | 1         | 2.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.94%   |
| Intel HD Graphics 620                                                                    | 1         | 2.94%   |
| Intel HD Graphics 520                                                                    | 1         | 2.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 2.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1         | 2.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 2.94%   |
| AMD RV620/M82 [Mobility Radeon HD 3410/3430]                                             | 1         | 2.94%   |
| AMD Lucienne                                                                             | 1         | 2.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 19        | 63.33%  |
| 1 x AMD        | 7         | 23.33%  |
| Intel + Nvidia | 2         | 6.67%   |
| AMD + Nvidia   | 2         | 6.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 27        | 90%     |
| Proprietary | 3         | 10%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 70%     |
| 0.01-0.5   | 6         | 20%     |
| 1.01-2.0   | 3         | 10%     |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 11        | 37.93%  |
| BOE                     | 5         | 17.24%  |
| AU Optronics            | 4         | 13.79%  |
| PANDA                   | 3         | 10.34%  |
| Sharp                   | 1         | 3.45%   |
| LG Philips              | 1         | 3.45%   |
| LG Display              | 1         | 3.45%   |
| Lenovo                  | 1         | 3.45%   |
| Hewlett-Packard         | 1         | 3.45%   |
| Chi Mei Optoelectronics | 1         | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 10.34%  |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 2         | 6.9%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 6.9%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 6.9%    |
| BOE LCD Monitor BOE07AA 1366x768 344x194mm 15.5-inch                     | 2         | 6.9%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 2         | 6.9%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 2         | 6.9%    |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 3.45%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 1         | 3.45%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch              | 1         | 3.45%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch             | 1         | 3.45%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 1         | 3.45%   |
| Hewlett-Packard LA1956x HWP3023 1280x1024 376x301mm 19.0-inch            | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch          | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch          | 1         | 3.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO1333 1366x768 293x164mm 13.2-inch | 1         | 3.45%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                     | 1         | 3.45%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO8098 1920x1080 309x174mm 14.0-inch           | 1         | 3.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 15        | 51.72%  |
| 1366x768 (WXGA)  | 11        | 37.93%  |
| 1600x900 (HD+)   | 1         | 3.45%   |
| 1280x800 (WXGA)  | 1         | 3.45%   |
| 1280x1024 (SXGA) | 1         | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 21        | 72.41%  |
| 13     | 3         | 10.34%  |
| 14     | 2         | 6.9%    |
| 19     | 1         | 3.45%   |
| 17     | 1         | 3.45%   |
| 11     | 1         | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 24        | 82.76%  |
| 201-300     | 3         | 10.34%  |
| 351-400     | 2         | 6.9%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 27        | 93.1%   |
| 5/4   | 1         | 3.45%   |
| 16/10 | 1         | 3.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 21        | 72.41%  |
| 81-90          | 3         | 10.34%  |
| 71-80          | 2         | 6.9%    |
| 51-60          | 1         | 3.45%   |
| 151-200        | 1         | 3.45%   |
| 121-130        | 1         | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 15        | 51.72%  |
| 101-120 | 11        | 37.93%  |
| 51-100  | 2         | 6.9%    |
| 161-240 | 1         | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 29        | 96.67%  |
| 0     | 1         | 3.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 19        | 46.34%  |
| Intel                             | 13        | 31.71%  |
| Qualcomm Atheros                  | 4         | 9.76%   |
| MediaTek                          | 2         | 4.88%   |
| Marvell Technology Group          | 1         | 2.44%   |
| Ericsson Business Mobile Networks | 1         | 2.44%   |
| Broadcom                          | 1         | 2.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 15.22%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 13.04%  |
| Intel Wi-Fi 6 AX201                                               | 4         | 8.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 6.52%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 6.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 4.35%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 4.35%   |
| Intel Wireless 8265 / 8275                                        | 2         | 4.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 2.17%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 2.17%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 2.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 2.17%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter               | 1         | 2.17%   |
| MediaTek File-CD Gadget                                           | 1         | 2.17%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 2.17%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 2.17%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 2.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 2.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.17%   |
| Ericsson Business Mobile Networks F5521gw                         | 1         | 2.17%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 2.17%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 1         | 2.17%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 44.83%  |
| Realtek Semiconductor | 10        | 34.48%  |
| Qualcomm Atheros      | 4         | 13.79%  |
| MediaTek              | 1         | 3.45%   |
| Broadcom              | 1         | 3.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 6         | 20.69%  |
| Intel Wi-Fi 6 AX201                                        | 4         | 13.79%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 3         | 10.34%  |
| Intel Wi-Fi 6 AX200                                        | 3         | 10.34%  |
| Intel Wireless 8265 / 8275                                 | 2         | 6.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 3.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1         | 3.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 1         | 3.45%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter   | 1         | 3.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 3.45%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter        | 1         | 3.45%   |
| Intel Gemini Lake PCH CNVi WiFi                            | 1         | 3.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 3.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 1         | 3.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 1         | 3.45%   |
| Broadcom BCM4312 802.11b/g LP-PHY                          | 1         | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 11        | 68.75%  |
| Intel                    | 2         | 12.5%   |
| MediaTek                 | 1         | 6.25%   |
| Marvell Technology Group | 1         | 6.25%   |
| Broadcom                 | 1         | 6.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 43.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 12.5%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 12.5%   |
| MediaTek File-CD Gadget                                           | 1         | 6.25%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 6.25%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 6.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 6.25%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 6.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 64.44%  |
| Ethernet | 15        | 33.33%  |
| Modem    | 1         | 2.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 86.67%  |
| Ethernet | 4         | 13.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 18        | 60%     |
| 2     | 12        | 40%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| Yes  | 19        | 63.33%  |
| No   | 11        | 36.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 48%     |
| IMC Networks                    | 7         | 28%     |
| Lite-On Technology              | 3         | 12%     |
| Realtek Semiconductor           | 1         | 4%      |
| Qualcomm Atheros Communications | 1         | 4%      |
| Foxconn / Hon Hai               | 1         | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| IMC Networks Bluetooth Radio                   | 7         | 28%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 4         | 16%     |
| Lite-On Bluetooth Device                       | 3         | 12%     |
| Intel Bluetooth wireless interface             | 3         | 12%     |
| Intel AX200 Bluetooth                          | 3         | 12%     |
| Intel Bluetooth Device                         | 2         | 8%      |
| Realtek Bluetooth Radio                        | 1         | 4%      |
| Qualcomm Atheros  Bluetooth Device             | 1         | 4%      |
| Foxconn / Hon Hai BT                           | 1         | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 22        | 64.71%  |
| AMD    | 9         | 26.47%  |
| Nvidia | 3         | 8.82%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 14.63%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 9.76%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 9.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 7.32%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 4.88%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 4.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 4.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 4.88%   |
| AMD High Definition Audio Controller                                                              | 2         | 4.88%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 4.88%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 2.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 2.44%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.44%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 2.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 2.44%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 2.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 2.44%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 2.44%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 1         | 2.44%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 2.44%   |

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

![Printer Vendor](./images/pie_chart/printer_vendor.svg)

![Printer Vendor](./images/line_chart/printer_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 1         | 50%     |
| Samsung Electronics | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)

![Printer Model](./images/line_chart/printer_model.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L220 Series | 1         | 50%     |
| Samsung M2020 Series    | 1         | 50%     |

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

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| IMC Networks        | 9         | 32.14%  |
| Quanta              | 5         | 17.86%  |
| Sonix Technology    | 4         | 14.29%  |
| Chicony Electronics | 4         | 14.29%  |
| Microdia            | 2         | 7.14%   |
| Syntek              | 1         | 3.57%   |
| Silicon Motion      | 1         | 3.57%   |
| Cubeternet          | 1         | 3.57%   |
| Acer                | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam       | 5         | 17.86%  |
| Sonix USB2.0 HD UVC WebCam               | 4         | 14.29%  |
| Chicony HD User Facing                   | 3         | 10.71%  |
| Quanta VGA WebCam                        | 2         | 7.14%   |
| Quanta USB2.0 HD UVC WebCam              | 2         | 7.14%   |
| IMC Networks USB2.0 HD UVC WebCam        | 2         | 7.14%   |
| Syntek EasyCamera                        | 1         | 3.57%   |
| Silicon Motion Lenovo EasyCamera         | 1         | 3.57%   |
| Quanta HD Webcam                         | 1         | 3.57%   |
| Microdia Sonix USB 2.0 Camera            | 1         | 3.57%   |
| Microdia Integrated Webcam HD            | 1         | 3.57%   |
| IMC Networks VGA UVC WebCam              | 1         | 3.57%   |
| IMC Networks USB2.0 UVC HD Webcam        | 1         | 3.57%   |
| Cubeternet USB2.0 Camera                 | 1         | 3.57%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 3.57%   |
| Acer Integrated Camera                   | 1         | 3.57%   |

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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 23        | 76.67%  |
| 1     | 5         | 16.67%  |
| 2     | 2         | 6.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 4         | 44.44%  |
| Net/wireless          | 2         | 22.22%  |
| Storage               | 1         | 11.11%  |
| Camera                | 1         | 11.11%  |
| Bluetooth             | 1         | 11.11%  |

