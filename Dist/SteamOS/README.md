SteamOS - Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/SteamOS/Desktop/README.md) and [notebooks](/Dist/SteamOS/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/linuxhw/TestCoverage)

Period: Aug, 2022.

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

| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SteamOS 3.3     | 50        | 60.98%  |
| SteamOS 3.3.1   | 26        | 31.71%  |
| SteamOS 3.2     | 3         | 3.66%   |
| SteamOS Rolling | 1         | 1.22%   |
| SteamOS 3.1     | 1         | 1.22%   |
| SteamOS         | 1         | 1.22%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| SteamOS | 82        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version                                            | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| 5.13.0-valve21-1-neptune-02209-g2a5bdc1102a0       | 33        | 40.24%  |
| 5.13.0-valve21.1-1-neptune-02211-gc54cda5a36f3     | 26        | 31.71%  |
| 5.13.0-valve22-1-neptune-02213-gb68995364335       | 9         | 10.98%  |
| 5.13.0-valve24-1-neptune-02226-g5b8545e4c5a1       | 6         | 7.32%   |
| 5.13.0-valve23-1-neptune-02219-gf0b4ecc8cab6       | 2         | 2.44%   |
| 5.13.0-valve15-1-neptune-02197-gf6ec7ad3762a       | 2         | 2.44%   |
| 5.13.0-valve10.1-2-neptune-dri-02144-g7fffaf925dfb | 2         | 2.44%   |
| 5.18.1-arch1_testHoloISO_20220606.1811             | 1         | 1.22%   |
| 5.13.0-valve10.3-1-neptune-02176-g5fe416c4acd8     | 1         | 1.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.0  | 81        | 98.78%  |
| 5.18.1  | 1         | 1.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13    | 81        | 98.78%  |
| 5.18    | 1         | 1.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 82        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name      | Computers | Percent |
|-----------|-----------|---------|
| KDE5      | 80        | 97.56%  |
| gamescope | 2         | 2.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 80        | 97.56%  |
| Wayland | 2         | 2.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 81        | 98.78%  |
| SDDM    | 1         | 1.22%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 76        | 92.68%  |
| de_DE | 2         | 2.44%   |
| zh_CN | 1         | 1.22%   |
| et_EE | 1         | 1.22%   |
| en_GB | 1         | 1.22%   |
| C     | 1         | 1.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 81        | 98.78%  |
| EFI  | 1         | 1.22%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 81        | 98.78%  |
| Ext4  | 1         | 1.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 81        | 98.78%  |
| GPT     | 1         | 1.22%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 81        | 98.78%  |
| Yes       | 1         | 1.22%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 82        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Valve               | 61        | 74.39%  |
| ASUSTek Computer    | 4         | 4.88%   |
| MSI                 | 3         | 3.66%   |
| Hewlett-Packard     | 3         | 3.66%   |
| Gigabyte Technology | 3         | 3.66%   |
| Dell                | 3         | 3.66%   |
| Lenovo              | 2         | 2.44%   |
| Microsoft           | 1         | 1.22%   |
| Apple               | 1         | 1.22%   |
| AMI                 | 1         | 1.22%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Valve Jupiter                          | 61        | 74.39%  |
| ASUS All Series                        | 2         | 2.44%   |
| MSI MS-7C02                            | 1         | 1.22%   |
| MSI MPG H510 Trident 3 (MS-B935)       | 1         | 1.22%   |
| MSI H310 Gaming Trident3 (MS-B920)     | 1         | 1.22%   |
| Microsoft Surface Pro 8                | 1         | 1.22%   |
| Lenovo Legion Y740-15IRHg 81UH         | 1         | 1.22%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2    | 1         | 1.22%   |
| HP Pavilion x360 Convertible 14-dy0xxx | 1         | 1.22%   |
| HP Laptop 14z-fq0000                   | 1         | 1.22%   |
| HP 27-p055na                           | 1         | 1.22%   |
| Gigabyte X570 GAMING X                 | 1         | 1.22%   |
| Gigabyte H310M S2V 2.0                 | 1         | 1.22%   |
| Gigabyte AB350-Gaming 3                | 1         | 1.22%   |
| Dell XPS 13 9360                       | 1         | 1.22%   |
| Dell Precision 7720                    | 1         | 1.22%   |
| Dell OptiPlex 9010                     | 1         | 1.22%   |
| ASUS TUF Gaming X570-PLUS              | 1         | 1.22%   |
| ASUS PRIME B550-PLUS                   | 1         | 1.22%   |
| Apple iMac18,3                         | 1         | 1.22%   |
| Unknown                                | 1         | 1.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Valve Jupiter         | 61        | 74.39%  |
| ASUS All              | 2         | 2.44%   |
| MSI MS-7C02           | 1         | 1.22%   |
| MSI MPG               | 1         | 1.22%   |
| MSI H310              | 1         | 1.22%   |
| Microsoft Surface     | 1         | 1.22%   |
| Lenovo Legion         | 1         | 1.22%   |
| Lenovo IdeaPad        | 1         | 1.22%   |
| HP Pavilion           | 1         | 1.22%   |
| HP Laptop             | 1         | 1.22%   |
| HP 27-p055na          | 1         | 1.22%   |
| Gigabyte X570         | 1         | 1.22%   |
| Gigabyte H310M        | 1         | 1.22%   |
| Gigabyte AB350-Gaming | 1         | 1.22%   |
| Dell XPS              | 1         | 1.22%   |
| Dell Precision        | 1         | 1.22%   |
| Dell OptiPlex         | 1         | 1.22%   |
| ASUS TUF              | 1         | 1.22%   |
| ASUS PRIME            | 1         | 1.22%   |
| Apple iMac18          | 1         | 1.22%   |
| Unknown               | 1         | 1.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 61        | 74.39%  |
| 2021 | 5         | 6.1%    |
| 2019 | 5         | 6.1%    |
| 2020 | 3         | 3.66%   |
| 2017 | 3         | 3.66%   |
| 2016 | 3         | 3.66%   |
| 2014 | 1         | 1.22%   |
| 2013 | 1         | 1.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 67        | 81.71%  |
| Desktop     | 11        | 13.41%  |
| All in one  | 2         | 2.44%   |
| Tablet      | 1         | 1.22%   |
| Convertible | 1         | 1.22%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 82        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 82        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 63        | 76.83%  |
| 16.01-24.0  | 10        | 12.2%   |
| 4.01-8.0    | 3         | 3.66%   |
| 32.01-64.0  | 2         | 2.44%   |
| 64.01-256.0 | 2         | 2.44%   |
| 3.01-4.0    | 1         | 1.22%   |
| 24.01-32.0  | 1         | 1.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 35        | 42.68%  |
| 3.01-4.0 | 25        | 30.49%  |
| 1.01-2.0 | 12        | 14.63%  |
| 4.01-8.0 | 10        | 12.2%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 2      | 47        | 57.32%  |
| 1      | 30        | 36.59%  |
| 3      | 4         | 4.88%   |
| 4      | 1         | 1.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 81        | 98.78%  |
| Yes       | 1         | 1.22%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 49        | 59.76%  |
| Yes       | 33        | 40.24%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 92.68%  |
| No        | 6         | 7.32%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 90.24%  |
| No        | 8         | 9.76%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country   | Computers | Percent |
|-----------|-----------|---------|
| USA       | 44        | 53.66%  |
| UK        | 8         | 9.76%   |
| Canada    | 7         | 8.54%   |
| Germany   | 4         | 4.88%   |
| Spain     | 3         | 3.66%   |
| Poland    | 3         | 3.66%   |
| Oman      | 2         | 2.44%   |
| Turkey    | 1         | 1.22%   |
| Sweden    | 1         | 1.22%   |
| Russia    | 1         | 1.22%   |
| Kuwait    | 1         | 1.22%   |
| Italy     | 1         | 1.22%   |
| Guatemala | 1         | 1.22%   |
| France    | 1         | 1.22%   |
| Estonia   | 1         | 1.22%   |
| Czechia   | 1         | 1.22%   |
| China     | 1         | 1.22%   |
| Cambodia  | 1         | 1.22%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City               | Computers | Percent |
|--------------------|-----------|---------|
| Muscat             | 2         | 2.44%   |
| Brooklyn           | 2         | 2.44%   |
| Bristol            | 2         | 2.44%   |
| Yekaterinburg      | 1         | 1.22%   |
| Wise               | 1         | 1.22%   |
| Wausau             | 1         | 1.22%   |
| Vilas              | 1         | 1.22%   |
| Vechelde           | 1         | 1.22%   |
| Ulm                | 1         | 1.22%   |
| Toronto            | 1         | 1.22%   |
| Thief River Falls  | 1         | 1.22%   |
| Sylmar             | 1         | 1.22%   |
| Sunnyvale          | 1         | 1.22%   |
| Stuttgart          | 1         | 1.22%   |
| Sterling Heights   | 1         | 1.22%   |
| Skarzysko-Kamienna | 1         | 1.22%   |
| Seattle            | 1         | 1.22%   |
| Santa Clara        | 1         | 1.22%   |
| San Antonio        | 1         | 1.22%   |
| Rockville          | 1         | 1.22%   |
| Ringwood           | 1         | 1.22%   |
| Québec            | 1         | 1.22%   |
| Przezmierowo       | 1         | 1.22%   |
| Prague             | 1         | 1.22%   |
| Poznan             | 1         | 1.22%   |
| Phnom Penh         | 1         | 1.22%   |
| Philadelphia       | 1         | 1.22%   |
| Pärnu             | 1         | 1.22%   |
| Park City          | 1         | 1.22%   |
| Paris              | 1         | 1.22%   |
| Ottawa             | 1         | 1.22%   |
| Nottingham         | 1         | 1.22%   |
| North Shields      | 1         | 1.22%   |
| New Orleans        | 1         | 1.22%   |
| Moore              | 1         | 1.22%   |
| Mixco              | 1         | 1.22%   |
| Milton Keynes      | 1         | 1.22%   |
| Milan              | 1         | 1.22%   |
| Middleboro         | 1         | 1.22%   |
| Manchester         | 1         | 1.22%   |
| Madrid             | 1         | 1.22%   |
| Louisville         | 1         | 1.22%   |
| Los Angeles        | 1         | 1.22%   |
| Lloydminster       | 1         | 1.22%   |
| Leganés           | 1         | 1.22%   |
| Langley            | 1         | 1.22%   |
| Jeffersonville     | 1         | 1.22%   |
| Jefferson City     | 1         | 1.22%   |
| Jacksonville Beach | 1         | 1.22%   |
| Jacksonville       | 1         | 1.22%   |
| Istanbul           | 1         | 1.22%   |
| Henderson          | 1         | 1.22%   |
| Hartford City      | 1         | 1.22%   |
| Haltom City        | 1         | 1.22%   |
| Grass Valley       | 1         | 1.22%   |
| Gothenburg         | 1         | 1.22%   |
| Gainesville        | 1         | 1.22%   |
| Fremont            | 1         | 1.22%   |
| Fort St. John      | 1         | 1.22%   |
| Fayette            | 1         | 1.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Unknown                     | 35        | 35     | 25.36%  |
| Phison                      | 29        | 29     | 21.01%  |
| Kingston                    | 23        | 23     | 16.67%  |
| Unknown                     | 11        | 11     | 7.97%   |
| Samsung Electronics         | 10        | 12     | 7.25%   |
| Sandisk                     | 5         | 5      | 3.62%   |
| Silicon Motion              | 4         | 4      | 2.9%    |
| WDC                         | 3         | 3      | 2.17%   |
| O2 Micro                    | 3         | 3      | 2.17%   |
| Toshiba                     | 2         | 3      | 1.45%   |
| SK hynix                    | 2         | 2      | 1.45%   |
| Seagate                     | 2         | 2      | 1.45%   |
| Yangtze Memory Technologies | 1         | 1      | 0.72%   |
| TrekStor                    | 1         | 1      | 0.72%   |
| SSK                         | 1         | 1      | 0.72%   |
| Realtek Semiconductor       | 1         | 1      | 0.72%   |
| Micron/Crucial Technology   | 1         | 1      | 0.72%   |
| Micron Technology           | 1         | 1      | 0.72%   |
| KIOXIA                      | 1         | 1      | 0.72%   |
| HS-SSD-C100                 | 1         | 1      | 0.72%   |
| Apple                       | 1         | 1      | 0.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Phison NVMe SSD Drive 512GB             | 22        | 15.71%  |
| Unknown MMC Card  512GB                 | 13        | 9.29%   |
| Kingston NVMe SSD Drive 256GB           | 12        | 8.57%   |
| Unknown                                 | 11        | 7.86%   |
| Kingston NVMe SSD Drive 512GB           | 10        | 7.14%   |
| Unknown MMC Card  128GB                 | 8         | 5.71%   |
| Phison NVMe SSD Drive 256GB             | 5         | 3.57%   |
| Unknown MMC Card  256GB                 | 4         | 2.86%   |
| Silicon Motion NVMe SSD Drive 512GB     | 4         | 2.86%   |
| Unknown MMC Card  32GB                  | 3         | 2.14%   |
| Samsung NVMe SSD Drive 1TB              | 3         | 2.14%   |
| O2 Micro NVMe SSD Drive 64GB            | 3         | 2.14%   |
| Unknown MMC Card  64GB                  | 2         | 1.43%   |
| Unknown MMC Card  393GB                 | 2         | 1.43%   |
| Samsung SM963 2.5" NVMe PCIe SSD 1024GB | 2         | 1.43%   |
| Yangtze Memory NVMe SSD Drive 1024GB    | 1         | 0.71%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.71%   |
| WDC WDBNCE0010PNC 1TB SSD               | 1         | 0.71%   |
| WDC WD10EZEX-00BN5A0 1TB                | 1         | 0.71%   |
| Unknown SK256  256GB                    | 1         | 0.71%   |
| Unknown MMC Card  250GB                 | 1         | 0.71%   |
| Unknown MMC Card  16GB                  | 1         | 0.71%   |
| TrekStor DS picco SSD 128GB             | 1         | 0.71%   |
| Toshiba NVMe SSD Drive 512GB            | 1         | 0.71%   |
| Toshiba HDWD130 3TB                     | 1         | 0.71%   |
| SSK Disk 256GB                          | 1         | 0.71%   |
| SK hynix NVMe SSD Drive 512GB           | 1         | 0.71%   |
| SK hynix NVMe SSD Drive 1024GB          | 1         | 0.71%   |
| Seagate ST3500312CS 500GB               | 1         | 0.71%   |
| Seagate ST1000LM049-2GH172 1TB          | 1         | 0.71%   |
| SanDisk X400 M.2 2280 128GB SSD         | 1         | 0.71%   |
| SanDisk NVMe SSD Drive 500GB            | 1         | 0.71%   |
| SanDisk NVMe SSD Drive 2TB              | 1         | 0.71%   |
| SanDisk NVMe SSD Drive 1TB              | 1         | 0.71%   |
| Sandisk Microsoft Xbox Series X 930GB   | 1         | 0.71%   |
| Samsung SSD 870 EVO 500GB               | 1         | 0.71%   |
| Samsung SM963 2.5" NVMe PCIe SSD 128GB  | 1         | 0.71%   |
| Samsung SM963 2.5" NVMe PCIe SSD 121GB  | 1         | 0.71%   |
| Samsung PSSD T7 1TB                     | 1         | 0.71%   |
| Samsung NVMe SSD Drive 512GB            | 1         | 0.71%   |
| Samsung NVMe SSD Drive 250GB            | 1         | 0.71%   |
| Samsung MZ7TD128HAFV-000L1 128GB SSD    | 1         | 0.71%   |
| Realtek NVMe SSD Drive 256GB            | 1         | 0.71%   |
| Phison NVMe SSD Drive 2TB               | 1         | 0.71%   |
| Phison ESMP512GKB4C3-E13TS 512GB        | 1         | 0.71%   |
| Micron/Crucial NVMe SSD Drive 1TB       | 1         | 0.71%   |
| Micron NVMe SSD Drive 512GB             | 1         | 0.71%   |
| KIOXIA NVMe SSD Drive 512GB             | 1         | 0.71%   |
| Kingston SA400S37240G 240GB SSD         | 1         | 0.71%   |
| HS-SSD-C100 240G                        | 1         | 0.71%   |
| Apple HDD ST3000DM001 3TB               | 1         | 0.71%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Toshiba | 1         | 2      | 20%     |
| Apple   | 1         | 1      | 20%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 37.5%   |
| WDC                 | 2         | 2      | 25%     |
| TrekStor            | 1         | 1      | 12.5%   |
| SanDisk             | 1         | 1      | 12.5%   |
| Kingston            | 1         | 1      | 12.5%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 77        | 79     | 56.2%   |
| MMC     | 45        | 45     | 32.85%  |
| SSD     | 7         | 8      | 5.11%   |
| HDD     | 5         | 6      | 3.65%   |
| Unknown | 3         | 3      | 2.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 77        | 79     | 57.04%  |
| MMC  | 45        | 45     | 33.33%  |
| SATA | 10        | 14     | 7.41%   |
| SAS  | 3         | 3      | 2.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 5         | 7      | 45.45%  |
| 0.51-1.0   | 4         | 4      | 36.36%  |
| 2.01-3.0   | 2         | 3      | 18.18%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 39        | 47.56%  |
| 101-250    | 21        | 25.61%  |
| 501-1000   | 15        | 18.29%  |
| 51-100     | 4         | 4.88%   |
| 1001-2000  | 2         | 2.44%   |
| 2001-3000  | 1         | 1.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 101-250  | 29        | 35.37%  |
| 251-500  | 21        | 25.61%  |
| 1-20     | 12        | 14.63%  |
| 51-100   | 12        | 14.63%  |
| 21-50    | 7         | 8.54%   |
| 501-1000 | 1         | 1.22%   |

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
| Detected | 82        | 140    | 98.8%   |
| Works    | 1         | 1      | 1.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Phison Electronics           | 29        | 31.18%  |
| Kingston Technology Company  | 22        | 23.66%  |
| Intel                        | 10        | 10.75%  |
| Samsung Electronics          | 8         | 8.6%    |
| AMD                          | 5         | 5.38%   |
| Silicon Motion               | 4         | 4.3%    |
| SanDisk                      | 4         | 4.3%    |
| O2 Micro                     | 3         | 3.23%   |
| SK hynix                     | 2         | 2.15%   |
| Yangtze Memory Technologies  | 1         | 1.08%   |
| Toshiba America Info Systems | 1         | 1.08%   |
| Realtek Semiconductor        | 1         | 1.08%   |
| Micron/Crucial Technology    | 1         | 1.08%   |
| Micron Technology            | 1         | 1.08%   |
| KIOXIA                       | 1         | 1.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Phison PS5013 E13 NVMe Controller                                             | 28        | 29.47%  |
| Kingston Company OM3PDP3 NVMe SSD                                             | 22        | 23.16%  |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 4         | 4.21%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 4         | 4.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 3         | 3.16%   |
| Samsung NVMe SSD Controller 980                                               | 3         | 3.16%   |
| O2 Micro Non-Volatile memory controller                                       | 3         | 3.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 3         | 3.16%   |
| SK hynix Gold P31 SSD                                                         | 2         | 2.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 2         | 2.11%   |
| Yangtze Memory Non-Volatile memory controller                                 | 1         | 1.05%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1         | 1.05%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 1         | 1.05%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 1         | 1.05%   |
| SanDisk PC SN530 NVMe SSD                                                     | 1         | 1.05%   |
| SanDisk Non-Volatile memory controller                                        | 1         | 1.05%   |
| Realtek Realtek Non-Volatile memory controller                                | 1         | 1.05%   |
| Phison Electronics Non-Volatile memory controller                             | 1         | 1.05%   |
| Micron/Crucial Non-Volatile memory controller                                 | 1         | 1.05%   |
| Micron Non-Volatile memory controller                                         | 1         | 1.05%   |
| KIOXIA NVMe SSD Controller BG4                                                | 1         | 1.05%   |
| Intel Volume Management Device NVMe RAID Controller                           | 1         | 1.05%   |
| Intel SATA Controller [RAID mode]                                             | 1         | 1.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 1         | 1.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 1         | 1.05%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                     | 1         | 1.05%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 1         | 1.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 1         | 1.05%   |
| AMD 500 Series Chipset SATA Controller                                        | 1         | 1.05%   |
| AMD 400 Series Chipset SATA Controller                                        | 1         | 1.05%   |
| AMD 300 Series Chipset SATA Controller                                        | 1         | 1.05%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 77        | 83.7%   |
| SATA | 13        | 14.13%  |
| RAID | 2         | 2.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 68        | 82.93%  |
| Intel  | 14        | 17.07%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Custom APU 0405                     | 61        | 74.39%  |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 2.44%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz     | 1         | 1.22%   |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz    | 1         | 1.22%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 1.22%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 1         | 1.22%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1         | 1.22%   |
| Intel Core i7-7560U CPU @ 2.40GHz       | 1         | 1.22%   |
| Intel Core i5-6400T CPU @ 2.20GHz       | 1         | 1.22%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 1         | 1.22%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 1         | 1.22%   |
| Intel Core i3-9100F CPU @ 3.60GHz       | 1         | 1.22%   |
| Intel Atom x7-Z8750 CPU @ 1.60GHz       | 1         | 1.22%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz | 1         | 1.22%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 1         | 1.22%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 1         | 1.22%   |
| AMD Ryzen 7 5700G with Radeon Graphics  | 1         | 1.22%   |
| AMD Ryzen 7 2700 Eight-Core Processor   | 1         | 1.22%   |
| AMD Ryzen 7 1700X Eight-Core Processor  | 1         | 1.22%   |
| AMD Ryzen 5 5600H with Radeon Graphics  | 1         | 1.22%   |
| AMD Ryzen 5 4500U with Radeon Graphics  | 1         | 1.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model         | Computers | Percent |
|---------------|-----------|---------|
| Other         | 64        | 78.05%  |
| Intel Core i7 | 4         | 4.88%   |
| AMD Ryzen 7   | 4         | 4.88%   |
| Intel Core i5 | 3         | 3.66%   |
| Intel Xeon    | 2         | 2.44%   |
| AMD Ryzen 5   | 2         | 2.44%   |
| Intel Core i3 | 1         | 1.22%   |
| Intel Atom    | 1         | 1.22%   |
| AMD Ryzen 9   | 1         | 1.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 71        | 86.59%  |
| 8      | 5         | 6.1%    |
| 6      | 4         | 4.88%   |
| 12     | 1         | 1.22%   |
| 2      | 1         | 1.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 82        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 75        | 91.46%  |
| 1      | 7         | 8.54%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 82        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 81        | 98.78%  |
| 0x08900201 | 1         | 1.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 62        | 75.61%  |
| KabyLake   | 5         | 6.1%    |
| Zen 3      | 4         | 4.88%   |
| TigerLake  | 2         | 2.44%   |
| Skylake    | 2         | 2.44%   |
| Haswell    | 2         | 2.44%   |
| Zen+       | 1         | 1.22%   |
| Zen 2      | 1         | 1.22%   |
| Zen        | 1         | 1.22%   |
| Silvermont | 1         | 1.22%   |
| IvyBridge  | 1         | 1.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 72        | 84.71%  |
| Intel  | 7         | 8.24%   |
| Nvidia | 6         | 7.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 61        | 71.76%  |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 4.71%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 2.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.35%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                                 | 1         | 1.18%   |
| Nvidia GP104GLM [Quadro P4000 Mobile]                                                    | 1         | 1.18%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 1.18%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.18%   |
| Intel Iris Plus Graphics 640                                                             | 1         | 1.18%   |
| Intel HD Graphics 530                                                                    | 1         | 1.18%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.18%   |
| AMD Renoir                                                                               | 1         | 1.18%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 1         | 1.18%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 1         | 1.18%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1         | 1.18%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1         | 1.18%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 1         | 1.18%   |
| AMD Cezanne                                                                              | 1         | 1.18%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| 1 x AMD      | 70        | 85.37%  |
| 1 x Nvidia   | 5         | 6.1%    |
| 1 x Intel    | 5         | 6.1%    |
| Intel + AMD  | 1         | 1.22%   |
| AMD + Nvidia | 1         | 1.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 76        | 92.68%  |
| Proprietary | 6         | 7.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 76        | 92.68%  |
| 3.01-4.0   | 3         | 3.66%   |
| 7.01-8.0   | 1         | 1.22%   |
| 5.01-6.0   | 1         | 1.22%   |
| 0.51-1.0   | 1         | 1.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| ANX                  | 58        | 62.37%  |
| Goldstar             | 4         | 4.3%    |
| Ancor Communications | 4         | 4.3%    |
| Samsung Electronics  | 3         | 3.23%   |
| BOE                  | 3         | 3.23%   |
| ASUSTek Computer     | 3         | 3.23%   |
| Philips              | 2         | 2.15%   |
| Dell                 | 2         | 2.15%   |
| Valve                | 1         | 1.08%   |
| Sony                 | 1         | 1.08%   |
| Sharp                | 1         | 1.08%   |
| Pixio                | 1         | 1.08%   |
| Microsoft            | 1         | 1.08%   |
| LG Display           | 1         | 1.08%   |
| Huion                | 1         | 1.08%   |
| Hewlett-Packard      | 1         | 1.08%   |
| HannStar             | 1         | 1.08%   |
| DZX                  | 1         | 1.08%   |
| Chimei Innolux       | 1         | 1.08%   |
| AU Optronics         | 1         | 1.08%   |
| Apple                | 1         | 1.08%   |
| Acer                 | 1         | 1.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| ANX ANX7530 U ANX7539 800x1280                                          | 58        | 62.37%  |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch        | 2         | 2.15%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                     | 1         | 1.08%   |
| Sony TV *00 SNY7A04 3840x2160 1218x685mm 55.0-inch                      | 1         | 1.08%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                 | 1         | 1.08%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch       | 1         | 1.08%   |
| Samsung Electronics C49HG9x SAM0E5D 2560x1080 1196x336mm 48.9-inch      | 1         | 1.08%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch       | 1         | 1.08%   |
| Pixio PX277P PNS0277 2560x1440 620x370mm 28.4-inch                      | 1         | 1.08%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1         | 1.08%   |
| Philips 197EL PHLC08B 1366x768 410x230mm 18.5-inch                      | 1         | 1.08%   |
| Microsoft Xbox One MSH0001 1920x1080 1430x800mm 64.5-inch               | 1         | 1.08%   |
| LG Display LCD Monitor LGD06B1 2880x1920 274x183mm 13.0-inch            | 1         | 1.08%   |
| Huion GT221 HAT2150 1920x1080 476x267mm 21.5-inch                       | 1         | 1.08%   |
| Hewlett-Packard All-in-One HWP4259 2560x1440 526x296mm 23.8-inch        | 1         | 1.08%   |
| HannStar HF289H HSD190B 1920x1200 610x350mm 27.7-inch                   | 1         | 1.08%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                | 1         | 1.08%   |
| Goldstar ULTRAGEAR GSM774A 3440x1440 800x335mm 34.1-inch                | 1         | 1.08%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                  | 1         | 1.08%   |
| Goldstar 27MU67 GSM5B00 3840x2160 600x340mm 27.2-inch                   | 1         | 1.08%   |
| DZX K3-1 DZX1581 1920x1080 350x190mm 15.7-inch                          | 1         | 1.08%   |
| Dell P2312H DEL4077 1920x1080 510x287mm 23.0-inch                       | 1         | 1.08%   |
| Dell P2217H DELA0D8 1920x1080 476x267mm 21.5-inch                       | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch        | 1         | 1.08%   |
| BOE LCD Monitor BOE09F0 1920x1080 309x174mm 14.0-inch                   | 1         | 1.08%   |
| BOE LCD Monitor BOE094E 1366x768 309x174mm 14.0-inch                    | 1         | 1.08%   |
| BOE LCD Monitor BOE083B 1920x1080 344x193mm 15.5-inch                   | 1         | 1.08%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch          | 1         | 1.08%   |
| ASUSTek Computer VG32VQ1B AUS32E0 2560x1440 697x392mm 31.5-inch         | 1         | 1.08%   |
| ASUSTek Computer PG43U AUS43A1 3840x2160 941x529mm 42.5-inch            | 1         | 1.08%   |
| ASUSTek Computer PA248QV AUS2487 1920x1200 520x320mm 24.0-inch          | 1         | 1.08%   |
| Apple iMac APPAE11 3840x2160 597x336mm 27.0-inch                        | 1         | 1.08%   |
| Ancor Communications ASUS VH242H ACI24F3 1920x1080 521x293mm 23.5-inch  | 1         | 1.08%   |
| Ancor Communications ASUS VG278HE ACI27E3 1920x1080 598x336mm 27.0-inch | 1         | 1.08%   |
| Acer VG270U ACR06C9 2560x1440 600x340mm 27.2-inch                       | 1         | 1.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 800x1280          | 59        | 64.13%  |
| 1920x1080 (FHD)   | 16        | 17.39%  |
| 3840x2160 (4K)    | 4         | 4.35%   |
| 2560x1440 (QHD)   | 4         | 4.35%   |
| 1920x1200 (WUXGA) | 2         | 2.17%   |
| 1366x768 (WXGA)   | 2         | 2.17%   |
| 3840x1080         | 1         | 1.09%   |
| 3440x1440         | 1         | 1.09%   |
| 3200x1800 (QHD+)  | 1         | 1.09%   |
| 2880x1920         | 1         | 1.09%   |
| 2560x1080         | 1         | 1.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 58        | 63.04%  |
| 27      | 7         | 7.61%   |
| 23      | 6         | 6.52%   |
| 15      | 3         | 3.26%   |
| 34      | 2         | 2.17%   |
| 21      | 2         | 2.17%   |
| 14      | 2         | 2.17%   |
| 13      | 2         | 2.17%   |
| 64      | 1         | 1.09%   |
| 55      | 1         | 1.09%   |
| 49      | 1         | 1.09%   |
| 42      | 1         | 1.09%   |
| 31      | 1         | 1.09%   |
| 28      | 1         | 1.09%   |
| 24      | 1         | 1.09%   |
| 18      | 1         | 1.09%   |
| 17      | 1         | 1.09%   |
| 7       | 1         | 1.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 58        | 63.04%  |
| 501-600     | 13        | 14.13%  |
| 301-350     | 5         | 5.43%   |
| 601-700     | 3         | 3.26%   |
| 401-500     | 3         | 3.26%   |
| 1001-1500   | 3         | 3.26%   |
| 701-800     | 2         | 2.17%   |
| 201-300     | 2         | 2.17%   |
| 351-400     | 1         | 1.09%   |
| 901-1000    | 1         | 1.09%   |
| 1-100       | 1         | 1.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 0.62  | 58        | 63.74%  |
| 16/9  | 27        | 29.67%  |
| 21/9  | 2         | 2.2%    |
| 32/9  | 1         | 1.1%    |
| 3/2   | 1         | 1.1%    |
| 16/10 | 1         | 1.1%    |
| 0.67  | 1         | 1.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 58        | 63.04%  |
| 301-350        | 7         | 7.61%   |
| 201-250        | 7         | 7.61%   |
| 351-500        | 4         | 4.35%   |
| 101-110        | 3         | 3.26%   |
| More than 1000 | 2         | 2.17%   |
| 81-90          | 2         | 2.17%   |
| 71-80          | 2         | 2.17%   |
| 501-1000       | 2         | 2.17%   |
| 1-40           | 1         | 1.09%   |
| 251-300        | 1         | 1.09%   |
| 151-200        | 1         | 1.09%   |
| 141-150        | 1         | 1.09%   |
| 121-130        | 1         | 1.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 58        | 63.04%  |
| 51-100        | 15        | 16.3%   |
| 101-120       | 7         | 7.61%   |
| 121-160       | 6         | 6.52%   |
| 161-240       | 3         | 3.26%   |
| More than 240 | 2         | 2.17%   |
| 1-50          | 1         | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 70        | 85.37%  |
| 2     | 11        | 13.41%  |
| 3     | 1         | 1.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 72        | 69.23%  |
| Intel                 | 10        | 9.62%   |
| ASIX Electronics      | 9         | 8.65%   |
| Broadcom              | 4         | 3.85%   |
| TP-Link               | 1         | 0.96%   |
| Samsung Electronics   | 1         | 0.96%   |
| Qualcomm Atheros      | 1         | 0.96%   |
| MediaTek              | 1         | 0.96%   |
| Lenovo                | 1         | 0.96%   |
| Huawei Technologies   | 1         | 0.96%   |
| Google                | 1         | 0.96%   |
| DisplayLink           | 1         | 0.96%   |
| Dell                  | 1         | 0.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 61        | 53.51%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 7.89%   |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 7.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 5.26%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.75%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 1.75%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.88%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.88%   |
| Realtek Realtek Network controller                                | 1         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.88%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.88%   |
| Intel Wireless 7265                                               | 1         | 0.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 0.88%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 0.88%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.88%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.88%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 0.88%   |
| Huawei JNY-LX1                                                    | 1         | 0.88%   |
| Google Pixel 6                                                    | 1         | 0.88%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.88%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                              | 1         | 0.88%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 0.88%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 0.88%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter                | 1         | 0.88%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 62        | 80.52%  |
| Intel                 | 7         | 9.09%   |
| Broadcom              | 4         | 5.19%   |
| TP-Link               | 1         | 1.3%    |
| Qualcomm Atheros      | 1         | 1.3%    |
| MediaTek              | 1         | 1.3%    |
| Dell                  | 1         | 1.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 61        | 79.22%  |
| Intel Wi-Fi 6 AX200                                           | 2         | 2.6%    |
| Intel Cannon Lake PCH CNVi WiFi                               | 2         | 2.6%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 2         | 2.6%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1         | 1.3%    |
| Realtek Realtek Network controller                            | 1         | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 1.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 1.3%    |
| Intel Wireless 7265                                           | 1         | 1.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 1         | 1.3%    |
| Intel Wi-Fi 6 AX201                                           | 1         | 1.3%    |
| Dell DW5811e Snapdragonâ¢ X7 LTE                          | 1         | 1.3%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 1         | 1.3%    |
| Broadcom BCM4356 802.11ac Wireless Network Adapter            | 1         | 1.3%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 16        | 43.24%  |
| ASIX Electronics      | 9         | 24.32%  |
| Intel                 | 6         | 16.22%  |
| Samsung Electronics   | 1         | 2.7%    |
| Lenovo                | 1         | 2.7%    |
| Huawei Technologies   | 1         | 2.7%    |
| Google                | 1         | 2.7%    |
| DisplayLink           | 1         | 2.7%    |
| Broadcom              | 1         | 2.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 24.32%  |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 24.32%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 16.22%  |
| Intel Ethernet Connection (2) I218-V                              | 2         | 5.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.7%    |
| Lenovo ThinkPad Lan                                               | 1         | 2.7%    |
| Intel Ethernet Controller I225-V                                  | 1         | 2.7%    |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 2.7%    |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.7%    |
| Huawei JNY-LX1                                                    | 1         | 2.7%    |
| Google Pixel 6                                                    | 1         | 2.7%    |
| DisplayLink Dell Universal Dock D6000                             | 1         | 2.7%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 2.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 76        | 69.72%  |
| Ethernet | 33        | 30.28%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 68        | 76.4%   |
| Ethernet | 21        | 23.6%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 72        | 87.8%   |
| 2     | 10        | 12.2%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 56        | 68.29%  |
| Yes  | 26        | 31.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| IMC Networks                    | 61        | 82.43%  |
| Intel                           | 7         | 9.46%   |
| TP-Link                         | 1         | 1.35%   |
| Realtek Semiconductor           | 1         | 1.35%   |
| Qualcomm Atheros Communications | 1         | 1.35%   |
| Integrated System Solution      | 1         | 1.35%   |
| Foxconn / Hon Hai               | 1         | 1.35%   |
| Apple                           | 1         | 1.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| IMC Networks Bluetooth Radio                          | 61        | 82.43%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2         | 2.7%    |
| Intel AX200 Bluetooth                                 | 2         | 2.7%    |
| TP-Link UB500 Adapter                                 | 1         | 1.35%   |
| Realtek Bluetooth Radio                               | 1         | 1.35%   |
| Qualcomm Atheros  Bluetooth Device                    | 1         | 1.35%   |
| Intel Bluetooth wireless interface                    | 1         | 1.35%   |
| Intel AX210 Bluetooth                                 | 1         | 1.35%   |
| Intel AX201 Bluetooth                                 | 1         | 1.35%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 1.35%   |
| Foxconn / Hon Hai Wireless_Device                     | 1         | 1.35%   |
| Apple Bluetooth USB Host Controller                   | 1         | 1.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| AMD             | 72        | 74.23%  |
| Intel           | 13        | 13.4%   |
| Nvidia          | 5         | 5.15%   |
| Logitech        | 2         | 2.06%   |
| SteelSeries ApS | 1         | 1.03%   |
| Quanta          | 1         | 1.03%   |
| GN Netcom       | 1         | 1.03%   |
| Creative Labs   | 1         | 1.03%   |
| Corsair         | 1         | 1.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Rembrandt Radeon High Definition Audio Controller               | 61        | 58.1%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 4         | 3.81%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 3         | 2.86%   |
| AMD Family 17h/19h HD Audio Controller                              | 3         | 2.86%   |
| Nvidia GP107GL High Definition Audio Controller                     | 2         | 1.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 2         | 1.9%    |
| Intel Cannon Lake PCH cAVS                                          | 2         | 1.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2         | 1.9%    |
| AMD Starship/Matisse HD Audio Controller                            | 2         | 1.9%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                             | 2         | 1.9%    |
| AMD Navi 10 HDMI Audio                                              | 2         | 1.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 2         | 1.9%    |
| SteelSeries ApS SteelSeries Arctis Pro                              | 1         | 0.95%   |
| Quanta USB Audio                                                    | 1         | 0.95%   |
| Nvidia TU106 High Definition Audio Controller                       | 1         | 0.95%   |
| Nvidia GP104 High Definition Audio Controller                       | 1         | 0.95%   |
| Nvidia GM204 High Definition Audio Controller                       | 1         | 0.95%   |
| Logitech PRO X                                                      | 1         | 0.95%   |
| Logitech G432 Gaming Headset                                        | 1         | 0.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 0.95%   |
| Intel Tiger Lake-H HD Audio Controller                              | 1         | 0.95%   |
| Intel Sunrise Point-LP HD Audio                                     | 1         | 0.95%   |
| Intel CM238 HD Audio Controller                                     | 1         | 0.95%   |
| Intel C610/X99 series chipset HD Audio Controller                   | 1         | 0.95%   |
| Intel 9 Series Chipset Family HD Audio Controller                   | 1         | 0.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 0.95%   |
| Intel 200 Series PCH HD Audio                                       | 1         | 0.95%   |
| GN Netcom Jabra Link 370                                            | 1         | 0.95%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]       | 1         | 0.95%   |
| Corsair VOID ELITE Wireless Gaming Dongle                           | 1         | 0.95%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind   | Computers | Percent |
|--------|-----------|---------|
| LPDDR5 | 1         | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 1         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size | Computers | Percent |
|------|-----------|---------|
| 4096 | 1         | 100%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 4266  | 1         | 100%    |

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

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Chicony Electronics | 4         | 44.44%  |
| SunplusIT           | 1         | 11.11%  |
| Quanta              | 1         | 11.11%  |
| Microdia            | 1         | 11.11%  |
| Apple               | 1         | 11.11%  |
| Acer                | 1         | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| SunplusIT CODi A05020 Webcam            | 1         | 11.11%  |
| Quanta HD Camera                        | 1         | 11.11%  |
| Microdia Integrated Webcam HD           | 1         | 11.11%  |
| Chicony Integrated Camera (1280x720@30) | 1         | 11.11%  |
| Chicony HP Wide Vision HD Camera        | 1         | 11.11%  |
| Chicony HP TrueVision HD Camera         | 1         | 11.11%  |
| Chicony HP High Definition 1MP Webcam   | 1         | 11.11%  |
| Apple FaceTime HD Camera (Built-in)     | 1         | 11.11%  |
| Acer Integrated Camera                  | 1         | 11.11%  |

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

| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| SCM Microsystems | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| SCM Microsystems SCR3500 A Contact Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 78        | 95.12%  |
| 1     | 3         | 3.66%   |
| 2     | 1         | 1.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 2         | 33.33%  |
| Multimedia controller | 2         | 33.33%  |
| Unassigned class      | 1         | 16.67%  |
| Chipcard              | 1         | 16.67%  |

