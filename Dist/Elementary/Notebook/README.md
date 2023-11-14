Elementary - Hardware Trends (Notebooks)
----------------------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: Oct, 2023.

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

| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Elementary 7.1 | 24        | 88.89%  |
| Elementary 6.1 | 3         | 11.11%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Elementary | 27        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 6.2.0-34-generic    | 8         | 29.63%  |
| 6.2.0-35-generic    | 7         | 25.93%  |
| 6.2.0-33-generic    | 6         | 22.22%  |
| 6.5.5-x64v3-xanmod1 | 1         | 3.7%    |
| 6.2.0-26-generic    | 1         | 3.7%    |
| 5.15.0-86-generic   | 1         | 3.7%    |
| 5.15.0-84-generic   | 1         | 3.7%    |
| 5.15.0-69-generic   | 1         | 3.7%    |
| 5.15.0-58-generic   | 1         | 3.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.0   | 22        | 81.48%  |
| 5.15.0  | 4         | 14.81%  |
| 6.5.5   | 1         | 3.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 22        | 81.48%  |
| 5.15    | 4         | 14.81%  |
| 6.5     | 1         | 3.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 27        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Pantheon | 27        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 27        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 22        | 81.48%  |
| LightDM | 5         | 18.52%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 9         | 33.33%  |
| de_DE | 5         | 18.52%  |
| it_IT | 4         | 14.81%  |
| ru_RU | 3         | 11.11%  |
| es_ES | 2         | 7.41%   |
| pt_BR | 1         | 3.7%    |
| fr_FR | 1         | 3.7%    |
| fr_CA | 1         | 3.7%    |
| de_CH | 1         | 3.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 23        | 85.19%  |
| EFI  | 4         | 14.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 23        | 85.19%  |
| Tmpfs   | 2         | 7.41%   |
| Overlay | 1         | 3.7%    |
| Btrfs   | 1         | 3.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 22        | 81.48%  |
| GPT     | 3         | 11.11%  |
| MBR     | 2         | 7.41%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 27        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 92.59%  |
| Yes       | 2         | 7.41%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Dell             | 6         | 22.22%  |
| Apple            | 6         | 22.22%  |
| Lenovo           | 4         | 14.81%  |
| Hewlett-Packard  | 4         | 14.81%  |
| ASUSTek Computer | 4         | 14.81%  |
| HUAWEI           | 1         | 3.7%    |
| Google           | 1         | 3.7%    |
| Acer             | 1         | 3.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Apple MacBookPro6,2                    | 2         | 7.41%   |
| Lenovo ThinkPad T440p 20AN0069US       | 1         | 3.7%    |
| Lenovo IdeaPad 5 14ITL05 82FE          | 1         | 3.7%    |
| Lenovo IdeaPad 330S-15IKB 81F5         | 1         | 3.7%    |
| Lenovo B570 1068FRG                    | 1         | 3.7%    |
| HUAWEI NBLK-WAX9X                      | 1         | 3.7%    |
| HP Pavilion dv7                        | 1         | 3.7%    |
| HP Pavilion 17                         | 1         | 3.7%    |
| HP Pavilion 15                         | 1         | 3.7%    |
| HP EliteBook 2570p                     | 1         | 3.7%    |
| Google Cave                            | 1         | 3.7%    |
| Dell Vostro 1510                       | 1         | 3.7%    |
| Dell Vostro 15 3515                    | 1         | 3.7%    |
| Dell Latitude E7270                    | 1         | 3.7%    |
| Dell Latitude E6520                    | 1         | 3.7%    |
| Dell Latitude E6400                    | 1         | 3.7%    |
| Dell Inspiron 1545                     | 1         | 3.7%    |
| ASUS Zenbook UX3402VA_UX3402VA         | 1         | 3.7%    |
| ASUS Zenbook UM3402YA_UM3402YA         | 1         | 3.7%    |
| ASUS X555LAB                           | 1         | 3.7%    |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA | 1         | 3.7%    |
| Apple MacBookPro7,1                    | 1         | 3.7%    |
| Apple MacBookPro5,3                    | 1         | 3.7%    |
| Apple MacBookPro11,5                   | 1         | 3.7%    |
| Apple MacBook7,1                       | 1         | 3.7%    |
| Acer Nitro AN517-54                    | 1         | 3.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| HP Pavilion        | 3         | 11.11%  |
| Dell Latitude      | 3         | 11.11%  |
| Lenovo IdeaPad     | 2         | 7.41%   |
| Dell Vostro        | 2         | 7.41%   |
| ASUS Zenbook       | 2         | 7.41%   |
| Apple MacBookPro6  | 2         | 7.41%   |
| Lenovo ThinkPad    | 1         | 3.7%    |
| Lenovo B570        | 1         | 3.7%    |
| HUAWEI NBLK-WAX9X  | 1         | 3.7%    |
| HP EliteBook       | 1         | 3.7%    |
| Google Cave        | 1         | 3.7%    |
| Dell Inspiron      | 1         | 3.7%    |
| ASUS X555LAB       | 1         | 3.7%    |
| ASUS VivoBook      | 1         | 3.7%    |
| Apple MacBookPro7  | 1         | 3.7%    |
| Apple MacBookPro5  | 1         | 3.7%    |
| Apple MacBookPro11 | 1         | 3.7%    |
| Apple MacBook7     | 1         | 3.7%    |
| Acer Nitro         | 1         | 3.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Notebooks | Percent |
|------|-----------|---------|
| 2010 | 4         | 14.81%  |
| 2008 | 4         | 14.81%  |
| 2013 | 3         | 11.11%  |
| 2022 | 2         | 7.41%   |
| 2021 | 2         | 7.41%   |
| 2019 | 2         | 7.41%   |
| 2016 | 2         | 7.41%   |
| 2011 | 2         | 7.41%   |
| 2023 | 1         | 3.7%    |
| 2020 | 1         | 3.7%    |
| 2018 | 1         | 3.7%    |
| 2014 | 1         | 3.7%    |
| 2012 | 1         | 3.7%    |
| 2009 | 1         | 3.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 27        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 26        | 96.3%   |
| Enabled  | 1         | 3.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 26        | 96.3%   |
| Yes  | 1         | 3.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 9         | 33.33%  |
| 16.01-24.0 | 6         | 22.22%  |
| 3.01-4.0   | 5         | 18.52%  |
| 8.01-16.0  | 4         | 14.81%  |
| 2.01-3.0   | 2         | 7.41%   |
| 32.01-64.0 | 1         | 3.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 11        | 40.74%  |
| 1.01-2.0  | 7         | 25.93%  |
| 3.01-4.0  | 4         | 14.81%  |
| 4.01-8.0  | 3         | 11.11%  |
| 8.01-16.0 | 1         | 3.7%    |
| 0.51-1.0  | 1         | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 70.37%  |
| 2      | 8         | 29.63%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 15        | 55.56%  |
| Yes       | 12        | 44.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 77.78%  |
| No        | 6         | 22.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 74.07%  |
| No        | 7         | 25.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Italy       | 5         | 18.52%  |
| USA         | 4         | 14.81%  |
| Germany     | 3         | 11.11%  |
| Brazil      | 3         | 11.11%  |
| Mexico      | 2         | 7.41%   |
| Canada      | 2         | 7.41%   |
| Thailand    | 1         | 3.7%    |
| Switzerland | 1         | 3.7%    |
| Sweden      | 1         | 3.7%    |
| Slovakia    | 1         | 3.7%    |
| Russia      | 1         | 3.7%    |
| France      | 1         | 3.7%    |
| Belarus     | 1         | 3.7%    |
| Armenia     | 1         | 3.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Yerevan        | 1         | 3.7%    |
| Yekaterinburg  | 1         | 3.7%    |
| Vitebsk        | 1         | 3.7%    |
| Savannah       | 1         | 3.7%    |
| Sainte-Therese | 1         | 3.7%    |
| Rome           | 1         | 3.7%    |
| Puebla City    | 1         | 3.7%    |
| Phoenix        | 1         | 3.7%    |
| Parma          | 1         | 3.7%    |
| Nîmes         | 1         | 3.7%    |
| Milton         | 1         | 3.7%    |
| Milano         | 1         | 3.7%    |
| Milan          | 1         | 3.7%    |
| Mascouche      | 1         | 3.7%    |
| Linhares       | 1         | 3.7%    |
| León          | 1         | 3.7%    |
| Leipzig        | 1         | 3.7%    |
| Koblenz        | 1         | 3.7%    |
| Johanneshov    | 1         | 3.7%    |
| Grossenhain    | 1         | 3.7%    |
| Galanta        | 1         | 3.7%    |
| Foz do Iguaçu | 1         | 3.7%    |
| Chiang Mai     | 1         | 3.7%    |
| Bowling Green  | 1         | 3.7%    |
| Aversa         | 1         | 3.7%    |
| Aracaju        | 1         | 3.7%    |
| Aarburg        | 1         | 3.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 9      | 25%     |
| WDC                 | 5         | 5      | 15.63%  |
| Sandisk             | 3         | 3      | 9.38%   |
| Toshiba             | 2         | 2      | 6.25%   |
| Seagate             | 2         | 2      | 6.25%   |
| Intel               | 2         | 2      | 6.25%   |
| Hitachi             | 2         | 2      | 6.25%   |
| Unknown             | 1         | 2      | 3.13%   |
| TS-RDF2             | 1         | 1      | 3.13%   |
| SPCC                | 1         | 1      | 3.13%   |
| Kingston            | 1         | 1      | 3.13%   |
| Fanxiang            | 1         | 1      | 3.13%   |
| China               | 1         | 1      | 3.13%   |
| Apple               | 1         | 1      | 3.13%   |
| A-DATA Technology   | 1         | 1      | 3.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                         | 2         | 5.88%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                  | 1         | 2.94%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 1         | 2.94%   |
| WDC WD5000LPVX-00V0TT0 500GB                      | 1         | 2.94%   |
| WDC WD5000BPVT-24HXZT3 500GB                      | 1         | 2.94%   |
| WDC WD10SPZX-21Z10T0 1TB                          | 1         | 2.94%   |
| Unknown MMC Card  64GB                            | 1         | 2.94%   |
| Unknown MMC Card  512GB                           | 1         | 2.94%   |
| TS-RDF2 Transcend 128GB                           | 1         | 2.94%   |
| Toshiba MQ04ABF100 1TB                            | 1         | 2.94%   |
| Toshiba KXG60ZNV512G 512GB                        | 1         | 2.94%   |
| SPCC Solid State Disk 512GB                       | 1         | 2.94%   |
| Seagate ST1000LX015-1U7172 1TB                    | 1         | 2.94%   |
| Seagate BUP Slim 1TB                              | 1         | 2.94%   |
| SanDisk X400 M.2 2280 128GB SSD                   | 1         | 2.94%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                | 1         | 2.94%   |
| SanDisk SDSSDHII960G 960GB                        | 1         | 2.94%   |
| Samsung SSD PM810 2.5 128GB                       | 1         | 2.94%   |
| Samsung SSD 750 EVO 250GB                         | 1         | 2.94%   |
| Samsung PM991a NVMe 256GB                         | 1         | 2.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 1         | 2.94%   |
| Samsung MZVL4512HBLU-00BTW 512GB                  | 1         | 2.94%   |
| Samsung MZALQ256HBJD-00BL2 256GB                  | 1         | 2.94%   |
| Samsung HM250HI 250GB                             | 1         | 2.94%   |
| Kingston SA400S37120G 120GB SSD                   | 1         | 2.94%   |
| Intel SSDSC2BF180A4H 180GB                        | 1         | 2.94%   |
| Intel SSDPEKNU512GZ 512GB                         | 1         | 2.94%   |
| Hitachi HTS545025B9SA02 250GB                     | 1         | 2.94%   |
| Hitachi HTS542512K9SA00 120GB                     | 1         | 2.94%   |
| Fanxiang S101 1TB MX                              | 1         | 2.94%   |
| China SSD 256GB                                   | 1         | 2.94%   |
| Apple SSD TS128C 121GB                            | 1         | 2.94%   |
| A-DATA IM2P33F8ABR2-256GB                         | 1         | 2.94%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 33.33%  |
| Seagate             | 2         | 2      | 22.22%  |
| Hitachi             | 2         | 2      | 22.22%  |
| Toshiba             | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 4      | 25%     |
| WDC                 | 2         | 2      | 16.67%  |
| SanDisk             | 2         | 2      | 16.67%  |
| SPCC                | 1         | 1      | 8.33%   |
| Kingston            | 1         | 1      | 8.33%   |
| Intel               | 1         | 1      | 8.33%   |
| China               | 1         | 1      | 8.33%   |
| Apple               | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 12        | 13     | 38.71%  |
| NVMe    | 8         | 8      | 25.81%  |
| HDD     | 8         | 9      | 25.81%  |
| Unknown | 2         | 2      | 6.45%   |
| MMC     | 1         | 2      | 3.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 19        | 22     | 63.33%  |
| NVMe | 8         | 8      | 26.67%  |
| SAS  | 2         | 2      | 6.67%   |
| MMC  | 1         | 2      | 3.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 15        | 16     | 71.43%  |
| 0.51-1.0   | 6         | 6      | 28.57%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 13        | 48.15%  |
| 251-500    | 5         | 18.52%  |
| 501-1000   | 4         | 14.81%  |
| 1001-2000  | 3         | 11.11%  |
| 21-50      | 1         | 3.7%    |
| 1-20       | 1         | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 11        | 40.74%  |
| 21-50    | 9         | 33.33%  |
| 251-500  | 3         | 11.11%  |
| 101-250  | 2         | 7.41%   |
| 501-1000 | 1         | 3.7%    |
| 51-100   | 1         | 3.7%    |

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

| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 24        | 30     | 88.89%  |
| Works    | 3         | 4      | 11.11%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 17        | 58.62%  |
| Samsung Electronics          | 4         | 13.79%  |
| Nvidia                       | 3         | 10.34%  |
| AMD                          | 2         | 6.9%    |
| Toshiba America Info Systems | 1         | 3.45%   |
| SanDisk                      | 1         | 3.45%   |
| ADATA Technology             | 1         | 3.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 9.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 9.68%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 2         | 6.45%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 2         | 6.45%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 2         | 6.45%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 3.23%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                              | 1         | 3.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 3.23%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                          | 1         | 3.23%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 3.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 3.23%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                  | 1         | 3.23%   |
| Intel Tiger Lake SATA AHCI Controller                                                  | 1         | 3.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 1         | 3.23%   |
| Intel SSD 670p Series [Keystone Harbor]                                                | 1         | 3.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 3.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 3.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 3.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 1         | 3.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 3.23%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 1         | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 3.23%   |
| ADATA IM2P33F8 series NVMe SSD (DRAM-less)                                             | 1         | 3.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 16        | 53.33%  |
| NVMe | 8         | 26.67%  |
| RAID | 4         | 13.33%  |
| IDE  | 2         | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 22        | 81.48%  |
| AMD    | 5         | 18.52%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 7.41%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 7.41%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 7.41%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 3.7%    |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 3.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 3.7%    |
| Intel Core i7-4980HQ CPU @ 2.80GHz            | 1         | 3.7%    |
| Intel Core i7-4712MQ CPU @ 2.30GHz            | 1         | 3.7%    |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 3.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 3.7%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 3.7%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 3.7%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 3.7%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 3.7%    |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 1         | 3.7%    |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz          | 1         | 3.7%    |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 1         | 3.7%    |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz   | 1         | 3.7%    |
| Intel 13th Gen Core i5-1340P                  | 1         | 3.7%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 3.7%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 3.7%    |
| AMD Ryzen 5 5625U with Radeon Graphics        | 1         | 3.7%    |
| AMD Ryzen 5 3450U with Radeon Vega Mobile Gfx | 1         | 3.7%    |
| AMD A4-5000 APU with Radeon HD Graphics       | 1         | 3.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 6         | 22.22%  |
| Intel Core 2 Duo        | 5         | 18.52%  |
| Intel Core i7           | 4         | 14.81%  |
| AMD Ryzen 5             | 4         | 14.81%  |
| Other                   | 3         | 11.11%  |
| Intel Pentium           | 1         | 3.7%    |
| Intel Core m3           | 1         | 3.7%    |
| Intel Core i3           | 1         | 3.7%    |
| Intel Celeron Dual-Core | 1         | 3.7%    |
| AMD A4                  | 1         | 3.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 16        | 59.26%  |
| 4      | 8         | 29.63%  |
| 12     | 1         | 3.7%    |
| 8      | 1         | 3.7%    |
| 6      | 1         | 3.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 27        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 19        | 70.37%  |
| 1      | 8         | 29.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 27        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 85.19%  |
| 0x08108109 | 2         | 7.41%   |
| 0x40661    | 1         | 3.7%    |
| 0x106e5    | 1         | 3.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Penryn           | 6         | 22.22%  |
| Zen+             | 3         | 11.11%  |
| Haswell          | 3         | 11.11%  |
| Westmere         | 2         | 7.41%   |
| Skylake          | 2         | 7.41%   |
| SandyBridge      | 2         | 7.41%   |
| Zen 3            | 1         | 3.7%    |
| TigerLake        | 1         | 3.7%    |
| Nehalem          | 1         | 3.7%    |
| KabyLake         | 1         | 3.7%    |
| Jaguar           | 1         | 3.7%    |
| IvyBridge        | 1         | 3.7%    |
| Icelake          | 1         | 3.7%    |
| Broadwell        | 1         | 3.7%    |
| Alderlake Hybrid | 1         | 3.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 16        | 50%     |
| Nvidia | 9         | 28.13%  |
| AMD    | 7         | 21.88%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 8.82%   |
| Nvidia MCP89 [GeForce 320M]                                               | 2         | 5.88%   |
| Nvidia GT216M [GeForce GT 330M]                                           | 2         | 5.88%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 5.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 5.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 2.94%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 2.94%   |
| Nvidia GF119M [NVS 4200M]                                                 | 1         | 2.94%   |
| Nvidia G98M [Quadro NVS 160M]                                             | 1         | 2.94%   |
| Nvidia G96CM [GeForce 9600M GT]                                           | 1         | 2.94%   |
| Nvidia C79 [GeForce 9400M]                                                | 1         | 2.94%   |
| Intel UHD Graphics 620                                                    | 1         | 2.94%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 1         | 2.94%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 1         | 2.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 2.94%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 1         | 2.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 2.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 2.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 2.94%   |
| Intel HD Graphics 5500                                                    | 1         | 2.94%   |
| Intel HD Graphics 515                                                     | 1         | 2.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 2.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 2.94%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 1         | 2.94%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                           | 1         | 2.94%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                  | 1         | 2.94%   |
| AMD Kabini [Radeon HD 8330]                                               | 1         | 2.94%   |
| AMD Barcelo                                                               | 1         | 2.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 11        | 40.74%  |
| 1 x AMD        | 7         | 25.93%  |
| Intel + Nvidia | 5         | 18.52%  |
| 1 x Nvidia     | 3         | 11.11%  |
| 2 x Nvidia     | 1         | 3.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 24        | 88.89%  |
| Proprietary | 2         | 7.41%   |
| Unknown     | 1         | 3.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 88.89%  |
| 0.51-1.0   | 2         | 7.41%   |
| 1.01-2.0   | 1         | 3.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 8         | 27.59%  |
| Samsung Electronics     | 5         | 17.24%  |
| Apple                   | 5         | 17.24%  |
| BOE                     | 3         | 10.34%  |
| LG Display              | 2         | 6.9%    |
| Mi                      | 1         | 3.45%   |
| Goldstar                | 1         | 3.45%   |
| Chimei Innolux          | 1         | 3.45%   |
| Chi Mei Optoelectronics | 1         | 3.45%   |
| Ancor Communications    | 1         | 3.45%   |
| Acer                    | 1         | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 2         | 6.9%    |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch     | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch     | 1         | 3.45%   |
| Mi 27 NFGL XMIB004 1920x1080 598x336mm 27.0-inch                         | 1         | 3.45%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 1         | 3.45%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 1         | 3.45%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch         | 1         | 3.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 3.45%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 1         | 3.45%   |
| BOE LCD Monitor BOE07F1 1920x1080 344x193mm 15.5-inch                    | 1         | 3.45%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                     | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch           | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO43EC 1366x768 344x193mm 15.5-inch            | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch           | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO233E 1600x900 309x174mm 14.0-inch            | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch           | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO2077 1440x900 331x207mm 15.4-inch            | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch            | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 1         | 3.45%   |
| Apple LCD Monitor APP9CBE 1280x800 286x179mm 13.3-inch                   | 1         | 3.45%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                   | 1         | 3.45%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                    | 1         | 3.45%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 1         | 3.45%   |
| Apple Color LCD APP9CB6 1680x1050 331x207mm 15.4-inch                    | 1         | 3.45%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch   | 1         | 3.45%   |
| Acer X223W ACR0050 1680x1050 474x296mm 22.0-inch                         | 1         | 3.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 8         | 27.59%  |
| 1920x1080 (FHD)    | 7         | 24.14%  |
| 2880x1800          | 3         | 10.34%  |
| 1440x900 (WXGA+)   | 3         | 10.34%  |
| 1680x1050 (WSXGA+) | 2         | 6.9%    |
| 1600x900 (HD+)     | 2         | 6.9%    |
| 1280x800 (WXGA)    | 2         | 6.9%    |
| 3840x2160 (4K)     | 1         | 3.45%   |
| 2560x1080          | 1         | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 12        | 41.38%  |
| 13     | 4         | 13.79%  |
| 17     | 3         | 10.34%  |
| 14     | 3         | 10.34%  |
| 12     | 3         | 10.34%  |
| 27     | 2         | 6.9%    |
| 34     | 1         | 3.45%   |
| 22     | 1         | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 55.17%  |
| 201-300     | 5         | 17.24%  |
| 351-400     | 4         | 13.79%  |
| 701-800     | 1         | 3.45%   |
| 601-700     | 1         | 3.45%   |
| 501-600     | 1         | 3.45%   |
| 401-500     | 1         | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 17        | 60.71%  |
| 16/10 | 10        | 35.71%  |
| 21/9  | 1         | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 41.38%  |
| 81-90          | 7         | 24.14%  |
| 61-70          | 3         | 10.34%  |
| 301-350        | 2         | 6.9%    |
| 121-130        | 2         | 6.9%    |
| 351-500        | 1         | 3.45%   |
| 201-250        | 1         | 3.45%   |
| 131-140        | 1         | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 10        | 34.48%  |
| 101-120       | 8         | 27.59%  |
| 51-100        | 7         | 24.14%  |
| More than 240 | 2         | 6.9%    |
| 161-240       | 2         | 6.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 23        | 85.19%  |
| 2     | 3         | 11.11%  |
| 0     | 1         | 3.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 10        | 22.22%  |
| Intel                           | 10        | 22.22%  |
| Broadcom                        | 9         | 20%     |
| Qualcomm Atheros                | 3         | 6.67%   |
| MediaTek                        | 3         | 6.67%   |
| Nvidia                          | 2         | 4.44%   |
| Broadcom Limited                | 2         | 4.44%   |
| Xiaomi                          | 1         | 2.22%   |
| Qualcomm Atheros Communications | 1         | 2.22%   |
| Marvell Technology Group        | 1         | 2.22%   |
| Hewlett-Packard                 | 1         | 2.22%   |
| Dell                            | 1         | 2.22%   |
| D-Link System                   | 1         | 2.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 5         | 9.09%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 3         | 5.45%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 3         | 5.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2         | 3.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 3.64%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 2         | 3.64%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1         | 1.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 1.82%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1         | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.82%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 1.82%   |
| Nvidia MCP89 Ethernet                                                         | 1         | 1.82%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 1.82%   |
| MediaTek Wiko U316AT                                                          | 1         | 1.82%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 1         | 1.82%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                           | 1         | 1.82%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 1         | 1.82%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.82%   |
| Intel Wireless 8260                                                           | 1         | 1.82%   |
| Intel Wireless 7265                                                           | 1         | 1.82%   |
| Intel Wireless 7260                                                           | 1         | 1.82%   |
| Intel Wi-Fi 6 AX201                                                           | 1         | 1.82%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.82%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 1.82%   |
| Intel Raptor Lake PCH CNVi WiFi                                               | 1         | 1.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 1.82%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 1.82%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 1.82%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 1.82%   |
| HP un2430 Mobile Broadband Module                                             | 1         | 1.82%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                          | 1         | 1.82%   |
| D-Link System WUA-2340 RangeBooster G Adapter(rev.A) [Atheros AR5523]         | 1         | 1.82%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                             | 1         | 1.82%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                       | 1         | 1.82%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                     | 1         | 1.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 29.03%  |
| Broadcom                        | 9         | 29.03%  |
| Realtek Semiconductor           | 3         | 9.68%   |
| Qualcomm Atheros                | 3         | 9.68%   |
| MediaTek                        | 2         | 6.45%   |
| Broadcom Limited                | 2         | 6.45%   |
| Qualcomm Atheros Communications | 1         | 3.23%   |
| Dell                            | 1         | 3.23%   |
| D-Link System                   | 1         | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM43224 802.11a/b/g/n                                               | 3         | 9.38%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 2         | 6.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 3.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 3.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 3.13%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 3.13%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 1         | 3.13%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                           | 1         | 3.13%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 3.13%   |
| Intel Wireless 8260                                                           | 1         | 3.13%   |
| Intel Wireless 7265                                                           | 1         | 3.13%   |
| Intel Wireless 7260                                                           | 1         | 3.13%   |
| Intel Wi-Fi 6 AX201                                                           | 1         | 3.13%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 3.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 3.13%   |
| Intel Raptor Lake PCH CNVi WiFi                                               | 1         | 3.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 3.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 3.13%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                          | 1         | 3.13%   |
| D-Link System WUA-2340 RangeBooster G Adapter(rev.A) [Atheros AR5523]         | 1         | 3.13%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                       | 1         | 3.13%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                     | 1         | 3.13%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 3.13%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 1         | 3.13%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 1         | 3.13%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 8         | 36.36%  |
| Intel                    | 5         | 22.73%  |
| Broadcom                 | 4         | 18.18%  |
| Nvidia                   | 2         | 9.09%   |
| Xiaomi                   | 1         | 4.55%   |
| MediaTek                 | 1         | 4.55%   |
| Marvell Technology Group | 1         | 4.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 22.73%  |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 13.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 9.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 9.09%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 4.55%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 4.55%   |
| Nvidia MCP89 Ethernet                                             | 1         | 4.55%   |
| Nvidia MCP79 Ethernet                                             | 1         | 4.55%   |
| MediaTek Wiko U316AT                                              | 1         | 4.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 4.55%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 4.55%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 4.55%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 4.55%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 4.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 55.1%   |
| Ethernet | 21        | 42.86%  |
| Modem    | 1         | 2.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 21        | 75%     |
| Ethernet | 7         | 25%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 19        | 70.37%  |
| 1     | 7         | 25.93%  |
| 3     | 1         | 3.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 17        | 62.96%  |
| Yes  | 10        | 37.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 7         | 35%     |
| Apple                           | 6         | 30%     |
| Broadcom                        | 2         | 10%     |
| Realtek Semiconductor           | 1         | 5%      |
| Realtek                         | 1         | 5%      |
| Qualcomm Atheros Communications | 1         | 5%      |
| Foxconn / Hon Hai               | 1         | 5%      |
| Dell                            | 1         | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Apple Bluetooth Host Controller      | 6         | 30%     |
| Intel Bluetooth wireless interface   | 4         | 20%     |
| Intel AX201 Bluetooth                | 2         | 10%     |
| Realtek Bluetooth Radio              | 1         | 5%      |
| Realtek Bluetooth Radio              | 1         | 5%      |
| Qualcomm Atheros  Bluetooth Device   | 1         | 5%      |
| Intel Bluetooth Device               | 1         | 5%      |
| Foxconn / Hon Hai BT                 | 1         | 5%      |
| Dell DW375 Bluetooth Module          | 1         | 5%      |
| Broadcom HP Portable SoftSailing     | 1         | 5%      |
| Broadcom BCM43142A0 Bluetooth Device | 1         | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 19        | 52.78%  |
| Nvidia                               | 7         | 19.44%  |
| AMD                                  | 7         | 19.44%  |
| Thesycon Systemsoftware & Consulting | 1         | 2.78%   |
| JBL                                  | 1         | 2.78%   |
| Huawei Technologies                  | 1         | 2.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 9.09%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 6.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 6.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 6.82%   |
| Nvidia MCP89 High Definition Audio                                         | 2         | 4.55%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 4.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 4.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 4.55%   |
| Thesycon Systemsoftware & Consulting DX3 Pro+                              | 1         | 2.27%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 2.27%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 2.27%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 2.27%   |
| JBL Quantum 400                                                            | 1         | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.27%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 2.27%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 1         | 2.27%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.27%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 2.27%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 2.27%   |
| Huawei Technologies KT USB Audio                                           | 1         | 2.27%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 2.27%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 2.27%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 2.27%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 2.27%   |
| AMD FCH Azalia Controller                                                  | 1         | 2.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| SK hynix          | 1         | 33.33%  |
| Micron Technology | 1         | 33.33%  |
| Crucial           | 1         | 33.33%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s  | 1         | 33.33%  |
| Micron RAM MT62F1G32D4DR-031 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 33.33%  |
| Crucial RAM CT102464BF832B 16GB SODIMM DDR4 3200MT/s          | 1         | 33.33%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 2         | 66.67%  |
| LPDDR5 | 1         | 33.33%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Row Of Chips | 2         | 66.67%  |
| SODIMM       | 1         | 33.33%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 16384 | 1         | 33.33%  |
| 8192  | 1         | 33.33%  |
| 4096  | 1         | 33.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 6400  | 1         | 33.33%  |
| 3200  | 1         | 33.33%  |
| 2667  | 1         | 33.33%  |

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)

![Camera Vendor](./images/line_chart/camera_vendor.svg)

| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| IMC Networks          | 5         | 20.83%  |
| Apple                 | 5         | 20.83%  |
| Realtek Semiconductor | 3         | 12.5%   |
| Microdia              | 3         | 12.5%   |
| Chicony Electronics   | 2         | 8.33%   |
| Suyin                 | 1         | 4.17%   |
| Sonix Technology      | 1         | 4.17%   |
| Ricoh                 | 1         | 4.17%   |
| Quanta                | 1         | 4.17%   |
| Lite-On Technology    | 1         | 4.17%   |
| Acer                  | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Apple Built-in iSight                | 5         | 20.83%  |
| IMC Networks USB2.0 HD UVC WebCam    | 3         | 12.5%   |
| Suyin HP Truevision HD               | 1         | 4.17%   |
| Sonix USB2.0 FHD UVC WebCam          | 1         | 4.17%   |
| Ricoh Laptop_Integrated_Webcam_FHD   | 1         | 4.17%   |
| Realtek USB2.0-Camera                | 1         | 4.17%   |
| Realtek USB Camera                   | 1         | 4.17%   |
| Realtek Integrated_Webcam_HD         | 1         | 4.17%   |
| Quanta HD User Facing                | 1         | 4.17%   |
| Microdia Sonix Integrated Webcam     | 1         | 4.17%   |
| Microdia Integrated_Webcam_HD        | 1         | 4.17%   |
| Microdia Integrated Webcam           | 1         | 4.17%   |
| Lite-On Integrated Camera            | 1         | 4.17%   |
| IMC Networks ov9734_azurewave_camera | 1         | 4.17%   |
| IMC Networks Integrated Camera       | 1         | 4.17%   |
| Chicony Lenovo EasyCamera            | 1         | 4.17%   |
| Chicony HP Truevision HD camera      | 1         | 4.17%   |
| Acer Integrated Camera               | 1         | 4.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 50%     |
| Shenzhen Goodix Technology | 1         | 25%     |
| LighTuning Technology      | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS491                    | 1         | 25%     |
| Validity Sensors VFS301 Fingerprint Reader | 1         | 25%     |
| Shenzhen Goodix  Fingerprint Device        | 1         | 25%     |
| LighTuning ES603 Swipe Fingerprint Sensor  | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./images/line_chart/chipcard_vendor.svg)

| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)

![Chipcard Model](./images/line_chart/chipcard_model.svg)

| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 2         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 15        | 55.56%  |
| 1     | 8         | 29.63%  |
| 2     | 3         | 11.11%  |
| 3     | 1         | 3.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 4         | 25%     |
| Fingerprint reader    | 4         | 25%     |
| Storage               | 2         | 12.5%   |
| Graphics card         | 2         | 12.5%   |
| Chipcard              | 2         | 12.5%   |
| Multimedia controller | 1         | 6.25%   |
| Bluetooth             | 1         | 6.25%   |

