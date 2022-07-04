Elementary - Hardware Trends
----------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary/Desktop/README.md) and [notebooks](/Dist/Elementary/Notebook/README.md).

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

![OS](./images/pie_chart/os_name.svg)

![OS](./images/line_chart/os_name.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| Elementary 6.1   | 42        | 93.33%  |
| Elementary 5.1.7 | 3         | 6.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Elementary | 45        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.13.0-51-generic     | 13        | 28.89%  |
| 5.13.0-48-generic     | 9         | 20%     |
| 5.13.0-44-generic     | 8         | 17.78%  |
| 5.11.0-43-generic     | 5         | 11.11%  |
| 5.4.0-120-generic     | 2         | 4.44%   |
| 5.13.0-39-generic     | 2         | 4.44%   |
| 5.4.0-42-generic      | 1         | 2.22%   |
| 5.18.3-051803-generic | 1         | 2.22%   |
| 5.17.3-xanmod1        | 1         | 2.22%   |
| 5.14.0-1042-oem       | 1         | 2.22%   |
| 5.13.0-41-generic     | 1         | 2.22%   |
| 5.13.0-40-generic     | 1         | 2.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.0  | 34        | 75.56%  |
| 5.11.0  | 5         | 11.11%  |
| 5.4.0   | 3         | 6.67%   |
| 5.18.3  | 1         | 2.22%   |
| 5.17.3  | 1         | 2.22%   |
| 5.14.0  | 1         | 2.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13    | 34        | 75.56%  |
| 5.11    | 5         | 11.11%  |
| 5.4     | 3         | 6.67%   |
| 5.18    | 1         | 2.22%   |
| 5.17    | 1         | 2.22%   |
| 5.14    | 1         | 2.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 45        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Pantheon | 45        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 45        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 37        | 82.22%  |
| LightDM | 8         | 17.78%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 23        | 51.11%  |
| pt_BR | 3         | 6.67%   |
| fr_FR | 3         | 6.67%   |
| de_DE | 3         | 6.67%   |
| it_IT | 2         | 4.44%   |
| zh_CN | 1         | 2.22%   |
| ru_RU | 1         | 2.22%   |
| pt_PT | 1         | 2.22%   |
| pl_PL | 1         | 2.22%   |
| nl_NL | 1         | 2.22%   |
| hu_HU | 1         | 2.22%   |
| es_PE | 1         | 2.22%   |
| es_ES | 1         | 2.22%   |
| en_GB | 1         | 2.22%   |
| en_CA | 1         | 2.22%   |
| de_CH | 1         | 2.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 32        | 71.11%  |
| BIOS | 13        | 28.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 43        | 95.56%  |
| Btrfs | 2         | 4.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 38        | 84.44%  |
| GPT     | 6         | 13.33%  |
| MBR     | 1         | 2.22%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 95.56%  |
| Yes       | 2         | 4.44%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 91.11%  |
| Yes       | 4         | 8.89%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 20%     |
| ASUSTek Computer    | 7         | 15.56%  |
| Apple               | 7         | 15.56%  |
| Lenovo              | 3         | 6.67%   |
| Dell                | 3         | 6.67%   |
| Toshiba             | 2         | 4.44%   |
| Samsung Electronics | 2         | 4.44%   |
| MSI                 | 2         | 4.44%   |
| Gigabyte Technology | 2         | 4.44%   |
| Acer                | 2         | 4.44%   |
| T-bao               | 1         | 2.22%   |
| Pegatron            | 1         | 2.22%   |
| Microsoft           | 1         | 2.22%   |
| Compaq              | 1         | 2.22%   |
| ASRock              | 1         | 2.22%   |
| Alienware           | 1         | 2.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Apple iMac8,1                           | 2         | 4.44%   |
| Toshiba Satellite T130                  | 1         | 2.22%   |
| Toshiba Satellite C870-1H2              | 1         | 2.22%   |
| T-bao MINI PC                           | 1         | 2.22%   |
| Samsung Lumpy                           | 1         | 2.22%   |
| Samsung 300E5M/300E5L                   | 1         | 2.22%   |
| Pegatron p7-1174                        | 1         | 2.22%   |
| MSI MS-7D52                             | 1         | 2.22%   |
| MSI MS-7851                             | 1         | 2.22%   |
| Microsoft Surface Pro 2                 | 1         | 2.22%   |
| Lenovo V15-IIL 82C5                     | 1         | 2.22%   |
| Lenovo ThinkPad E14 Gen 3 20YDS06K00    | 1         | 2.22%   |
| Lenovo ThinkCentre M73 10B6001SUS       | 1         | 2.22%   |
| HP Stream Laptop 14-cb1xxx              | 1         | 2.22%   |
| HP ProBook 455R G6                      | 1         | 2.22%   |
| HP ProBook 4540s                        | 1         | 2.22%   |
| HP Pavilion g4                          | 1         | 2.22%   |
| HP Pavilion dv5                         | 1         | 2.22%   |
| HP Notebook                             | 1         | 2.22%   |
| HP EliteBook 2170p                      | 1         | 2.22%   |
| HP Compaq Pro 6300 MT                   | 1         | 2.22%   |
| HP 23-q120d                             | 1         | 2.22%   |
| Gigabyte Z690 AORUS MASTER              | 1         | 2.22%   |
| Gigabyte B450 AORUS ELITE               | 1         | 2.22%   |
| Dell OptiPlex 5040                      | 1         | 2.22%   |
| Dell Latitude E5510                     | 1         | 2.22%   |
| Dell Inspiron 5537                      | 1         | 2.22%   |
| Compaq Presario CQ-23                   | 1         | 2.22%   |
| ASUS X553MA                             | 1         | 2.22%   |
| ASUS UX303LAB                           | 1         | 2.22%   |
| ASUS SABERTOOTH X58                     | 1         | 2.22%   |
| ASUS ROG Zephyrus G14 GA401IHR_GA401IHR | 1         | 2.22%   |
| ASUS PRIME B550-PLUS                    | 1         | 2.22%   |
| ASUS PRIME A320M-K/BR                   | 1         | 2.22%   |
| ASUS GR8                                | 1         | 2.22%   |
| ASRock Z490 Pro4                        | 1         | 2.22%   |
| Apple Macmini5,1                        | 1         | 2.22%   |
| Apple MacBookPro14,2                    | 1         | 2.22%   |
| Apple MacBookAir7,2                     | 1         | 2.22%   |
| Apple MacBookAir4,2                     | 1         | 2.22%   |
| Apple MacBook4,1                        | 1         | 2.22%   |
| Alienware m17 R3                        | 1         | 2.22%   |
| Acer TravelMate 5760                    | 1         | 2.22%   |
| Acer Aspire A315-21                     | 1         | 2.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Toshiba Satellite  | 2         | 4.44%   |
| HP ProBook         | 2         | 4.44%   |
| HP Pavilion        | 2         | 4.44%   |
| ASUS PRIME         | 2         | 4.44%   |
| Apple iMac8        | 2         | 4.44%   |
| T-bao MINI         | 1         | 2.22%   |
| Samsung Lumpy      | 1         | 2.22%   |
| Samsung 300E5M     | 1         | 2.22%   |
| Pegatron p7-1174   | 1         | 2.22%   |
| MSI MS-7D52        | 1         | 2.22%   |
| MSI MS-7851        | 1         | 2.22%   |
| Microsoft Surface  | 1         | 2.22%   |
| Lenovo V15-IIL     | 1         | 2.22%   |
| Lenovo ThinkPad    | 1         | 2.22%   |
| Lenovo ThinkCentre | 1         | 2.22%   |
| HP Stream          | 1         | 2.22%   |
| HP Notebook        | 1         | 2.22%   |
| HP EliteBook       | 1         | 2.22%   |
| HP Compaq          | 1         | 2.22%   |
| HP 23-q120d        | 1         | 2.22%   |
| Gigabyte Z690      | 1         | 2.22%   |
| Gigabyte B450      | 1         | 2.22%   |
| Dell OptiPlex      | 1         | 2.22%   |
| Dell Latitude      | 1         | 2.22%   |
| Dell Inspiron      | 1         | 2.22%   |
| Compaq Presario    | 1         | 2.22%   |
| ASUS X553MA        | 1         | 2.22%   |
| ASUS UX303LAB      | 1         | 2.22%   |
| ASUS SABERTOOTH    | 1         | 2.22%   |
| ASUS ROG           | 1         | 2.22%   |
| ASUS GR8           | 1         | 2.22%   |
| ASRock Z490        | 1         | 2.22%   |
| Apple Macmini5     | 1         | 2.22%   |
| Apple MacBookPro14 | 1         | 2.22%   |
| Apple MacBookAir7  | 1         | 2.22%   |
| Apple MacBookAir4  | 1         | 2.22%   |
| Apple MacBook4     | 1         | 2.22%   |
| Alienware m17      | 1         | 2.22%   |
| Acer TravelMate    | 1         | 2.22%   |
| Acer Aspire        | 1         | 2.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2012 | 5         | 11.11%  |
| 2021 | 4         | 8.89%   |
| 2020 | 4         | 8.89%   |
| 2017 | 4         | 8.89%   |
| 2008 | 4         | 8.89%   |
| 2022 | 3         | 6.67%   |
| 2015 | 3         | 6.67%   |
| 2014 | 3         | 6.67%   |
| 2013 | 3         | 6.67%   |
| 2011 | 3         | 6.67%   |
| 2019 | 2         | 4.44%   |
| 2018 | 2         | 4.44%   |
| 2016 | 2         | 4.44%   |
| 2010 | 2         | 4.44%   |
| 2009 | 1         | 2.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 27        | 60%     |
| Desktop    | 14        | 31.11%  |
| All in one | 2         | 4.44%   |
| Tablet     | 1         | 2.22%   |
| Mini pc    | 1         | 2.22%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 41        | 91.11%  |
| Enabled  | 4         | 8.89%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 44        | 97.78%  |
| Yes  | 1         | 2.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 13        | 28.89%  |
| 3.01-4.0    | 12        | 26.67%  |
| 4.01-8.0    | 10        | 22.22%  |
| 16.01-24.0  | 6         | 13.33%  |
| 32.01-64.0  | 2         | 4.44%   |
| 64.01-256.0 | 1         | 2.22%   |
| 1.01-2.0    | 1         | 2.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 21        | 46.67%  |
| 2.01-3.0 | 14        | 31.11%  |
| 3.01-4.0 | 6         | 13.33%  |
| 4.01-8.0 | 4         | 8.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 24        | 53.33%  |
| 2      | 16        | 35.56%  |
| 3      | 4         | 8.89%   |
| 5      | 1         | 2.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 71.11%  |
| Yes       | 13        | 28.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 86.67%  |
| No        | 6         | 13.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 80%     |
| No        | 9         | 20%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 68.89%  |
| No        | 14        | 31.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 11        | 24.44%  |
| Brazil      | 4         | 8.89%   |
| Netherlands | 2         | 4.44%   |
| Italy       | 2         | 4.44%   |
| Indonesia   | 2         | 4.44%   |
| Germany     | 2         | 4.44%   |
| France      | 2         | 4.44%   |
| Canada      | 2         | 4.44%   |
| Argentina   | 2         | 4.44%   |
| Zambia      | 1         | 2.22%   |
| UK          | 1         | 2.22%   |
| Turkey      | 1         | 2.22%   |
| Switzerland | 1         | 2.22%   |
| Sweden      | 1         | 2.22%   |
| Russia      | 1         | 2.22%   |
| Portugal    | 1         | 2.22%   |
| Poland      | 1         | 2.22%   |
| Peru        | 1         | 2.22%   |
| Israel      | 1         | 2.22%   |
| India       | 1         | 2.22%   |
| Hungary     | 1         | 2.22%   |
| China       | 1         | 2.22%   |
| Belgium     | 1         | 2.22%   |
| Austria     | 1         | 2.22%   |
| Australia   | 1         | 2.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Yucca Valley                | 1         | 2.22%   |
| Wuhan                       | 1         | 2.22%   |
| Wroclaw                     | 1         | 2.22%   |
| Warrenton                   | 1         | 2.22%   |
| Voerde                      | 1         | 2.22%   |
| The Hague                   | 1         | 2.22%   |
| Tel Aviv                    | 1         | 2.22%   |
| Sydney                      | 1         | 2.22%   |
| Sidney Center               | 1         | 2.22%   |
| Sao Francisco de Itabapoana | 1         | 2.22%   |
| Rio de Janeiro              | 1         | 2.22%   |
| Porto Mantovano             | 1         | 2.22%   |
| Porto                       | 1         | 2.22%   |
| Plano                       | 1         | 2.22%   |
| Plan-de-Cuques              | 1         | 2.22%   |
| Ottawa                      | 1         | 2.22%   |
| North Shields               | 1         | 2.22%   |
| New Carlisle                | 1         | 2.22%   |
| Mumbai                      | 1         | 2.22%   |
| Mount Pleasant              | 1         | 2.22%   |
| Milwaukee                   | 1         | 2.22%   |
| Lusaka                      | 1         | 2.22%   |
| Luleå                      | 1         | 2.22%   |
| Los Angeles                 | 1         | 2.22%   |
| Liestal                     | 1         | 2.22%   |
| Krenglbach                  | 1         | 2.22%   |
| Kingston                    | 1         | 2.22%   |
| Kimry                       | 1         | 2.22%   |
| Jatiasih                    | 1         | 2.22%   |
| Jakarta                     | 1         | 2.22%   |
| Istanbul                    | 1         | 2.22%   |
| Iquitos                     | 1         | 2.22%   |
| Guarulhos                   | 1         | 2.22%   |
| Furci Siculo                | 1         | 2.22%   |
| Feuquieres-en-Vimeu         | 1         | 2.22%   |
| Dipperz                     | 1         | 2.22%   |
| Córdoba                    | 1         | 2.22%   |
| Chattanooga                 | 1         | 2.22%   |
| Caseros                     | 1         | 2.22%   |
| Brussels                    | 1         | 2.22%   |
| Brasília                   | 1         | 2.22%   |
| Baton Rouge                 | 1         | 2.22%   |
| Babolna                     | 1         | 2.22%   |
| Almere Stad                 | 1         | 2.22%   |
| Albany                      | 1         | 2.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 10        | 12     | 14.93%  |
| Samsung Electronics       | 8         | 9      | 11.94%  |
| Seagate                   | 7         | 7      | 10.45%  |
| Toshiba                   | 6         | 6      | 8.96%   |
| Kingston                  | 5         | 5      | 7.46%   |
| HGST                      | 4         | 4      | 5.97%   |
| Crucial                   | 3         | 4      | 4.48%   |
| Apple                     | 3         | 4      | 4.48%   |
| Unknown                   | 2         | 2      | 2.99%   |
| Silicon Motion            | 2         | 2      | 2.99%   |
| SanDisk                   | 2         | 2      | 2.99%   |
| V-GeN                     | 1         | 1      | 1.49%   |
| Team                      | 1         | 1      | 1.49%   |
| SK hynix                  | 1         | 1      | 1.49%   |
| Realtek Semiconductor     | 1         | 1      | 1.49%   |
| PNY                       | 1         | 1      | 1.49%   |
| Patriot                   | 1         | 1      | 1.49%   |
| OCZ                       | 1         | 1      | 1.49%   |
| Micron/Crucial Technology | 1         | 1      | 1.49%   |
| Micron Technology         | 1         | 1      | 1.49%   |
| Kingchuxing               | 1         | 1      | 1.49%   |
| Hitachi                   | 1         | 1      | 1.49%   |
| Faspeed                   | 1         | 1      | 1.49%   |
| EVM                       | 1         | 1      | 1.49%   |
| Apacer                    | 1         | 1      | 1.49%   |
| A-DATA Technology         | 1         | 1      | 1.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB               | 2         | 2.86%   |
| HGST HTS545050A7E680 500GB           | 2         | 2.86%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 1.43%   |
| WDC WD5000BPVT-22HXZT1 500GB         | 1         | 1.43%   |
| WDC WD5000AAKS-00UU3A0 500GB         | 1         | 1.43%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 1.43%   |
| WDC WD30EZRZ-00Z5HB0 3TB             | 1         | 1.43%   |
| WDC WD1600AABS-00PRA0 160GB          | 1         | 1.43%   |
| WDC WD15EARS-60MVWB0 1TB             | 1         | 1.43%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1         | 1.43%   |
| WDC WD10EZEX-00ZF5A0 1TB             | 1         | 1.43%   |
| WDC WD10EURX-63UY4Y0 1TB             | 1         | 1.43%   |
| WDC WD10 JPVX-22JC3T0 1TB            | 1         | 1.43%   |
| V-GeN V-GEN01SM21AR128SDK 128GB      | 1         | 1.43%   |
| Unknown MMC Card  64GB               | 1         | 1.43%   |
| Unknown MMC Card  30MB               | 1         | 1.43%   |
| Toshiba MQ04ABF100 1TB               | 1         | 1.43%   |
| Toshiba MK5055GSX 500GB              | 1         | 1.43%   |
| Toshiba HDWF180 8TB                  | 1         | 1.43%   |
| Toshiba DT01ACA100 1TB               | 1         | 1.43%   |
| Team T253X1480G 480GB SSD            | 1         | 1.43%   |
| SK hynix NVMe SSD Drive 256GB        | 1         | 1.43%   |
| Silicon Motion NVMe SSD Drive 1TB    | 1         | 1.43%   |
| Silicon Motion NVMe SSD Drive 128GB  | 1         | 1.43%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1.43%   |
| Seagate ST3500630AS 500GB            | 1         | 1.43%   |
| Seagate ST3500418ASQ 500GB           | 1         | 1.43%   |
| Seagate ST1000DM010-2EP102 1TB       | 1         | 1.43%   |
| Seagate ST1000DM003-1ER162 1TB       | 1         | 1.43%   |
| Seagate ST1000DM003-1CH162 1TB       | 1         | 1.43%   |
| Seagate ST1000DL002-9TT153 1TB       | 1         | 1.43%   |
| SanDisk SDSSDH3512G 512GB            | 1         | 1.43%   |
| SanDisk SD7SB3Q256G1002 256GB SSD    | 1         | 1.43%   |
| Samsung SSD PM810 2.5 7mm 128GB      | 1         | 1.43%   |
| Samsung SSD 860 EVO 250GB            | 1         | 1.43%   |
| Samsung NVMe SSD Drive 512GB         | 1         | 1.43%   |
| Samsung NVMe SSD Drive 2TB           | 1         | 1.43%   |
| Samsung MZMTD256HAGM-000MV 256GB SSD | 1         | 1.43%   |
| Samsung MZALQ256HBJD-00BL1 256GB     | 1         | 1.43%   |
| Samsung MZ7TD128HAFV-000L1 128GB SSD | 1         | 1.43%   |
| Samsung HM160HI 160GB                | 1         | 1.43%   |
| Samsung HD500LJ 500GB                | 1         | 1.43%   |
| Realtek NVMe SSD Drive 1024GB        | 1         | 1.43%   |
| PNY CS900 120GB SSD                  | 1         | 1.43%   |
| Patriot Burst 240GB SSD              | 1         | 1.43%   |
| OCZ VERTEX3 120GB SSD                | 1         | 1.43%   |
| Micron/Crucial NVMe SSD Drive 500GB  | 1         | 1.43%   |
| Micron 1100_MTFDDAK256TBN 256GB SSD  | 1         | 1.43%   |
| Kingston SUV400S37240G 240GB SSD     | 1         | 1.43%   |
| Kingston SNVS500G 500GB              | 1         | 1.43%   |
| Kingston SA400S37240G 240GB SSD      | 1         | 1.43%   |
| Kingston NVMe SSD Drive 2TB          | 1         | 1.43%   |
| Kingston NVMe SSD Drive 1TB          | 1         | 1.43%   |
| Kingchuxing 64GB                     | 1         | 1.43%   |
| Hitachi HTS727550A9E364 500GB        | 1         | 1.43%   |
| HGST HTS721010A9E630 1TB             | 1         | 1.43%   |
| HGST HTS541010A9E680 1TB             | 1         | 1.43%   |
| Faspeed K7-256G-CD 256GB             | 1         | 1.43%   |
| EVM 512GB SSD                        | 1         | 1.43%   |
| Crucial M4-CT064M4SSD2 64GB          | 1         | 1.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 11     | 31.03%  |
| Seagate             | 7         | 7      | 24.14%  |
| Toshiba             | 6         | 6      | 20.69%  |
| HGST                | 4         | 4      | 13.79%  |
| Samsung Electronics | 2         | 2      | 6.9%    |
| Hitachi             | 1         | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 19.05%  |
| SanDisk             | 2         | 2      | 9.52%   |
| Kingston            | 2         | 2      | 9.52%   |
| Crucial             | 2         | 2      | 9.52%   |
| Apple               | 2         | 2      | 9.52%   |
| WDC                 | 1         | 1      | 4.76%   |
| Team                | 1         | 1      | 4.76%   |
| PNY                 | 1         | 1      | 4.76%   |
| Patriot             | 1         | 1      | 4.76%   |
| OCZ                 | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 1      | 4.76%   |
| EVM                 | 1         | 1      | 4.76%   |
| Apacer              | 1         | 1      | 4.76%   |
| A-DATA Technology   | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 25        | 31     | 41.67%  |
| SSD     | 19        | 21     | 31.67%  |
| NVMe    | 11        | 15     | 18.33%  |
| Unknown | 3         | 3      | 5%      |
| MMC     | 2         | 2      | 3.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 38        | 53     | 71.7%   |
| NVMe | 11        | 15     | 20.75%  |
| SAS  | 2         | 2      | 3.77%   |
| MMC  | 2         | 2      | 3.77%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 32     | 63.41%  |
| 0.51-1.0   | 13        | 17     | 31.71%  |
| 2.01-3.0   | 1         | 2      | 2.44%   |
| 4.01-10.0  | 1         | 1      | 2.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 22        | 48.89%  |
| 501-1000   | 8         | 17.78%  |
| 51-100     | 5         | 11.11%  |
| 251-500    | 4         | 8.89%   |
| 1001-2000  | 4         | 8.89%   |
| 21-50      | 1         | 2.22%   |
| 1-20       | 1         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 17        | 37.78%  |
| 21-50    | 12        | 26.67%  |
| 51-100   | 10        | 22.22%  |
| 251-500  | 2         | 4.44%   |
| 101-250  | 2         | 4.44%   |
| 501-1000 | 2         | 4.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD5000AAKS-00UU3A0 500GB | 1         | 1      | 50%     |
| Apple SSD SM256C 256GB       | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 50%     |
| Apple  | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 50%     |
| HDD  | 1         | 1      | 50%     |

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
| Detected | 38        | 59     | 82.61%  |
| Works    | 6         | 11     | 13.04%  |
| Malfunc  | 2         | 2      | 4.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 30        | 54.55%  |
| AMD                         | 9         | 16.36%  |
| Samsung Electronics         | 4         | 7.27%   |
| Kingston Technology Company | 3         | 5.45%   |
| Silicon Motion              | 2         | 3.64%   |
| Micron/Crucial Technology   | 2         | 3.64%   |
| SK hynix                    | 1         | 1.82%   |
| Realtek Semiconductor       | 1         | 1.82%   |
| Marvell Technology Group    | 1         | 1.82%   |
| JMicron Technology          | 1         | 1.82%   |
| Apple                       | 1         | 1.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 9.68%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 6.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 6.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 4.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 4.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 4.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 4.84%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 3.23%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 3.23%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 3.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 3.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 3.23%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 1.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.61%   |
| Samsung Electronics SATA controller                                            | 1         | 1.61%   |
| Realtek Realtek Non-Volatile memory controller                                 | 1         | 1.61%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                     | 1         | 1.61%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.61%   |
| Kingston Company KC2000 NVMe SSD                                               | 1         | 1.61%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 1.61%   |
| JMicron JMB362 SATA Controller                                                 | 1         | 1.61%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.61%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.61%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.61%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1         | 1.61%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1         | 1.61%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1         | 1.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.61%   |
| Apple S3X NVMe Controller                                                      | 1         | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1         | 1.61%   |
| AMD RS690 PCI to PCI Bridge (PCI Express Port 2)                               | 1         | 1.61%   |
| AMD FCH SATA Controller D                                                      | 1         | 1.61%   |
| AMD 500 Series Chipset SATA Controller                                         | 1         | 1.61%   |
| AMD 400 Series Chipset SATA Controller                                         | 1         | 1.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 39        | 69.64%  |
| NVMe | 11        | 19.64%  |
| IDE  | 5         | 8.93%   |
| RAID | 1         | 1.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 34        | 75.56%  |
| AMD    | 11        | 24.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 4.44%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 2.22%   |
| Intel Genuine CPU U4100 @ 1.30GHz             | 1         | 2.22%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 2.22%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 2.22%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1         | 2.22%   |
| Intel Core i7-3667U CPU @ 2.00GHz             | 1         | 2.22%   |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 1         | 2.22%   |
| Intel Core i7-2677M CPU @ 1.80GHz             | 1         | 2.22%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 2.22%   |
| Intel Core i7-10700K CPU @ 3.80GHz            | 1         | 2.22%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 2.22%   |
| Intel Core i7 CPU 950 @ 3.07GHz               | 1         | 2.22%   |
| Intel Core i5-7267U CPU @ 3.10GHz             | 1         | 2.22%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 2.22%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 1         | 2.22%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 1         | 2.22%   |
| Intel Core i5-4460T CPU @ 1.90GHz             | 1         | 2.22%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 2.22%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 2.22%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 2.22%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 1         | 2.22%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 2.22%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 1         | 2.22%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 1         | 2.22%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 2.22%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 1         | 2.22%   |
| Intel Core 2 Duo CPU E8335 @ 2.66GHz          | 1         | 2.22%   |
| Intel Core 2 Duo CPU E8235 @ 2.80GHz          | 1         | 2.22%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 2.22%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 1         | 2.22%   |
| Intel Celeron CPU 867 @ 1.30GHz               | 1         | 2.22%   |
| Intel 12th Gen Core i9-12900KF                | 1         | 2.22%   |
| AMD Turion X2 Ultra Dual-Core Mobile ZM-87    | 1         | 2.22%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 1         | 2.22%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 1         | 2.22%   |
| AMD Ryzen 7 4800HS with Radeon Graphics       | 1         | 2.22%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 2.22%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 2.22%   |
| AMD Ryzen 7 1700 Eight-Core Processor         | 1         | 2.22%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 1         | 2.22%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 2.22%   |
| AMD A8-3800 APU with Radeon HD Graphics       | 1         | 2.22%   |
| AMD A4-9120 RADEON R3, 4 COMPUTE CORES 2C+2G  | 1         | 2.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i7                        | 10        | 22.22%  |
| Intel Core i5                        | 10        | 22.22%  |
| Intel Core i3                        | 5         | 11.11%  |
| AMD Ryzen 7                          | 5         | 11.11%  |
| Intel Core 2 Duo                     | 3         | 6.67%   |
| Intel Celeron                        | 3         | 6.67%   |
| AMD Ryzen 5                          | 2         | 4.44%   |
| Other                                | 1         | 2.22%   |
| Intel Pentium                        | 1         | 2.22%   |
| Intel Genuine                        | 1         | 2.22%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 2.22%   |
| AMD Ryzen 9                          | 1         | 2.22%   |
| AMD A8                               | 1         | 2.22%   |
| AMD A4                               | 1         | 2.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 25        | 55.56%  |
| 4      | 11        | 24.44%  |
| 8      | 5         | 11.11%  |
| 16     | 1         | 2.22%   |
| 12     | 1         | 2.22%   |
| 6      | 1         | 2.22%   |
| 1      | 1         | 2.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 45        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 29        | 64.44%  |
| 1      | 16        | 35.56%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 45        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 5         | 11.11%  |
| 0x206a7    | 4         | 8.89%   |
| 0x40651    | 3         | 6.67%   |
| 0x306c3    | 3         | 6.67%   |
| 0x10676    | 3         | 6.67%   |
| 0x406e3    | 2         | 4.44%   |
| 0x306d4    | 2         | 4.44%   |
| 0x30678    | 2         | 4.44%   |
| 0x08108109 | 2         | 4.44%   |
| Unknown    | 2         | 4.44%   |
| 0xa0655    | 1         | 2.22%   |
| 0xa0652    | 1         | 2.22%   |
| 0x90672    | 1         | 2.22%   |
| 0x806e9    | 1         | 2.22%   |
| 0x706e5    | 1         | 2.22%   |
| 0x706a8    | 1         | 2.22%   |
| 0x506e3    | 1         | 2.22%   |
| 0x20655    | 1         | 2.22%   |
| 0x106a5    | 1         | 2.22%   |
| 0x1067a    | 1         | 2.22%   |
| 0x0a50000c | 1         | 2.22%   |
| 0x0a201205 | 1         | 2.22%   |
| 0x08608103 | 1         | 2.22%   |
| 0x08001138 | 1         | 2.22%   |
| 0x06006705 | 1         | 2.22%   |
| 0x03000027 | 1         | 2.22%   |
| 0x02000057 | 1         | 2.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 6         | 13.33%  |
| IvyBridge        | 5         | 11.11%  |
| SandyBridge      | 4         | 8.89%   |
| Penryn           | 4         | 8.89%   |
| Zen 3            | 3         | 6.67%   |
| Skylake          | 3         | 6.67%   |
| Zen+             | 2         | 4.44%   |
| Silvermont       | 2         | 4.44%   |
| CometLake        | 2         | 4.44%   |
| Broadwell        | 2         | 4.44%   |
| Zen 2            | 1         | 2.22%   |
| Zen              | 1         | 2.22%   |
| Westmere         | 1         | 2.22%   |
| Nehalem          | 1         | 2.22%   |
| KabyLake         | 1         | 2.22%   |
| K8 & K10 hybrid  | 1         | 2.22%   |
| K10 Llano        | 1         | 2.22%   |
| IceLake          | 1         | 2.22%   |
| Goldmont plus    | 1         | 2.22%   |
| Excavator        | 1         | 2.22%   |
| Alderlake Hybrid | 1         | 2.22%   |
| Unknown          | 1         | 2.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 26        | 47.27%  |
| AMD    | 20        | 36.36%  |
| Nvidia | 9         | 16.36%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 4         | 7.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 4         | 7.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 3         | 5.36%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 3.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 2         | 3.57%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                       | 2         | 3.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 3.57%   |
| AMD Cezanne                                                                           | 2         | 3.57%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 1.79%   |
| Nvidia TU106 [GeForce GTX 1650]                                                       | 1         | 1.79%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                | 1         | 1.79%   |
| Nvidia GT218 [GeForce 210]                                                            | 1         | 1.79%   |
| Nvidia GP107GL [Quadro P620]                                                          | 1         | 1.79%   |
| Nvidia GM107M [GeForce GTX 860M]                                                      | 1         | 1.79%   |
| Nvidia GM107 [GeForce GTX 750]                                                        | 1         | 1.79%   |
| Nvidia GK104 [GeForce GTX 670]                                                        | 1         | 1.79%   |
| Nvidia GF108 [GeForce GT 730]                                                         | 1         | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 1.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 1         | 1.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 1         | 1.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 1.79%   |
| Intel Iris Plus Graphics G7                                                           | 1         | 1.79%   |
| Intel Iris Plus Graphics 650                                                          | 1         | 1.79%   |
| Intel HD Graphics 6000                                                                | 1         | 1.79%   |
| Intel HD Graphics 5500                                                                | 1         | 1.79%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 1.79%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 1.79%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 1         | 1.79%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller             | 1         | 1.79%   |
| AMD Venus PRO [Radeon HD 8850M / R9 M265X]                                            | 1         | 1.79%   |
| AMD Turks GL [FirePro V3900]                                                          | 1         | 1.79%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.79%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 1         | 1.79%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 1.79%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 1         | 1.79%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 1         | 1.79%   |
| AMD RV710 [Radeon HD 4350/4550]                                                       | 1         | 1.79%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                          | 1         | 1.79%   |
| AMD Renoir                                                                            | 1         | 1.79%   |
| AMD Redwood LE [Radeon HD 5550/5570/5630/6390/6490/7570]                              | 1         | 1.79%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]                     | 1         | 1.79%   |
| AMD Navi 24 [Radeon RX 6400 / 6500 XT]                                                | 1         | 1.79%   |
| AMD Lucienne                                                                          | 1         | 1.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 40%     |
| 1 x AMD        | 13        | 28.89%  |
| 1 x Nvidia     | 5         | 11.11%  |
| Intel + AMD    | 5         | 11.11%  |
| Intel + Nvidia | 2         | 4.44%   |
| AMD + Nvidia   | 2         | 4.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 41        | 91.11%  |
| Proprietary | 3         | 6.67%   |
| Unknown     | 1         | 2.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 51.11%  |
| 1.01-2.0   | 9         | 20%     |
| 0.51-1.0   | 5         | 11.11%  |
| 0.01-0.5   | 5         | 11.11%  |
| 3.01-4.0   | 3         | 6.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 10        | 19.23%  |
| Chimei Innolux       | 6         | 11.54%  |
| Apple                | 6         | 11.54%  |
| Goldstar             | 4         | 7.69%   |
| AU Optronics         | 4         | 7.69%   |
| Philips              | 3         | 5.77%   |
| LG Display           | 3         | 5.77%   |
| BOE                  | 3         | 5.77%   |
| Dell                 | 2         | 3.85%   |
| ___                  | 1         | 1.92%   |
| Unknown              | 1         | 1.92%   |
| TMX                  | 1         | 1.92%   |
| Sony                 | 1         | 1.92%   |
| Onkyo                | 1         | 1.92%   |
| LLP                  | 1         | 1.92%   |
| Hitachi              | 1         | 1.92%   |
| Hewlett-Packard      | 1         | 1.92%   |
| AOC                  | 1         | 1.92%   |
| Ancor Communications | 1         | 1.92%   |
| Acer                 | 1         | 1.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| ___ LCD TV ___0101 1360x768                                           | 1         | 1.89%   |
| Unknown LCD TV 0101 1920x1080 1600x900mm 72.3-inch                    | 1         | 1.89%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 1.89%   |
| Sony TV SNYD703 1360x768                                              | 1         | 1.89%   |
| Samsung Electronics SMBX2035 SAM06FD 1600x900 443x249mm 20.0-inch     | 1         | 1.89%   |
| Samsung Electronics S27R35x SAM1053 1920x1080 598x336mm 27.0-inch     | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SEC3953 1366x768 256x144mm 11.6-inch  | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SEC3142 1280x800 261x163mm 12.1-inch  | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch  | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SAM723F 3840x2160 950x540mm 43.0-inch | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 1         | 1.89%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch    | 1         | 1.89%   |
| Philips PHL 241V8 PHLC212 1920x1080 527x296mm 23.8-inch               | 1         | 1.89%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch               | 1         | 1.89%   |
| Philips LCD Monitor PHL 498P9 5120x1440                               | 1         | 1.89%   |
| Onkyo PA-R200 ONK0C6B 1920x1080                                       | 1         | 1.89%   |
| LLP 32V3H-H6A LLP4C54 1440x900 697x392mm 31.5-inch                    | 1         | 1.89%   |
| LG Display LCD Monitor LGD070C 1920x1080 309x174mm 14.0-inch          | 1         | 1.89%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 1.89%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 1         | 1.89%   |
| Hitachi X224W DVI HIT7D0B 1680x1050 473x296mm 22.0-inch               | 1         | 1.89%   |
| Hewlett-Packard ALL-in-One HWP4224 1920x1080 509x286mm 23.0-inch      | 1         | 1.89%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 1         | 1.89%   |
| Goldstar ULTRAGEAR GSM7765 2560x1440 697x392mm 31.5-inch              | 1         | 1.89%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch             | 1         | 1.89%   |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch                | 1         | 1.89%   |
| Dell S2721HGF DEL41E7 1920x1080 597x336mm 27.0-inch                   | 1         | 1.89%   |
| Dell P2414H DELA09B 1920x1080 527x297mm 23.8-inch                     | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch       | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 344x194mm 15.5-inch       | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN150D 1920x1080 344x193mm 15.5-inch      | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN1361 1920x1080 293x165mm 13.2-inch      | 1         | 1.89%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 1         | 1.89%   |
| BOE LCD Monitor BOE062B 1920x1080 344x193mm 15.5-inch                 | 1         | 1.89%   |
| BOE LCD Monitor BOE05F0 1366x768 309x173mm 13.9-inch                  | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO402C 1366x768 293x164mm 13.2-inch         | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO329B 3840x2160 381x214mm 17.2-inch        | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch         | 1         | 1.89%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                | 1         | 1.89%   |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                 | 1         | 1.89%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 1         | 1.89%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 1         | 1.89%   |
| Apple Color LCD APP9C8E 1920x1200 520x320mm 24.0-inch                 | 1         | 1.89%   |
| Apple Color LCD APP9C6B 1680x1050 433x270mm 20.1-inch                 | 1         | 1.89%   |
| AOC 2490W1 AOC2490 1920x1080 527x296mm 23.8-inch                      | 1         | 1.89%   |
| Ancor Communications LCD Monitor ASUS VS239 1920x1080                 | 1         | 1.89%   |
| Ancor Communications ASUS VS239 ACI23D2 1920x1080 509x286mm 23.0-inch | 1         | 1.89%   |
| Acer G206HQL ACR035A 1600x900 432x239mm 19.4-inch                     | 1         | 1.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 18        | 36.73%  |
| 1366x768 (WXGA)    | 13        | 26.53%  |
| 1600x900 (HD+)     | 4         | 8.16%   |
| 2560x1440 (QHD)    | 2         | 4.08%   |
| 1680x1050 (WSXGA+) | 2         | 4.08%   |
| 1440x900 (WXGA+)   | 2         | 4.08%   |
| 5120x1440          | 1         | 2.04%   |
| 3840x2160 (4K)     | 1         | 2.04%   |
| 2880x1800          | 1         | 2.04%   |
| 2560x1080          | 1         | 2.04%   |
| 1920x1200 (WUXGA)  | 1         | 2.04%   |
| 1360x768           | 1         | 2.04%   |
| 1280x800 (WXGA)    | 1         | 2.04%   |
| 1280x1024 (SXGA)   | 1         | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 9         | 16.98%  |
| 13      | 8         | 15.09%  |
| 24      | 4         | 7.55%   |
| 14      | 4         | 7.55%   |
| 31      | 3         | 5.66%   |
| 23      | 3         | 5.66%   |
| 21      | 3         | 5.66%   |
| 17      | 3         | 5.66%   |
| Unknown | 3         | 5.66%   |
| 72      | 2         | 3.77%   |
| 27      | 2         | 3.77%   |
| 20      | 2         | 3.77%   |
| 43      | 1         | 1.89%   |
| 28      | 1         | 1.89%   |
| 22      | 1         | 1.89%   |
| 19      | 1         | 1.89%   |
| 18      | 1         | 1.89%   |
| 11      | 1         | 1.89%   |
| 10      | 1         | 1.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 28.85%  |
| 501-600     | 9         | 17.31%  |
| 201-300     | 8         | 15.38%  |
| 401-500     | 7         | 13.46%  |
| 601-700     | 4         | 7.69%   |
| 351-400     | 3         | 5.77%   |
| Unknown     | 3         | 5.77%   |
| 1501-2000   | 2         | 3.85%   |
| 901-1000    | 1         | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 37        | 78.72%  |
| 16/10   | 7         | 14.89%  |
| Unknown | 2         | 4.26%   |
| 21/9    | 1         | 2.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 9         | 16.98%  |
| 81-90          | 8         | 15.09%  |
| 201-250        | 8         | 15.09%  |
| 71-80          | 4         | 7.55%   |
| 251-300        | 4         | 7.55%   |
| 351-500        | 3         | 5.66%   |
| 151-200        | 3         | 5.66%   |
| Unknown        | 3         | 5.66%   |
| More than 1000 | 2         | 3.77%   |
| 301-350        | 2         | 3.77%   |
| 121-130        | 2         | 3.77%   |
| 51-60          | 1         | 1.89%   |
| 41-50          | 1         | 1.89%   |
| 141-150        | 1         | 1.89%   |
| 131-140        | 1         | 1.89%   |
| 501-1000       | 1         | 1.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 19        | 35.85%  |
| 51-100        | 17        | 32.08%  |
| 121-160       | 6         | 11.32%  |
| 1-50          | 3         | 5.66%   |
| 161-240       | 3         | 5.66%   |
| Unknown       | 3         | 5.66%   |
| More than 240 | 2         | 3.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 36        | 80%     |
| 2     | 8         | 17.78%  |
| 0     | 1         | 2.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 29        | 42.03%  |
| Broadcom                        | 9         | 13.04%  |
| Qualcomm Atheros                | 8         | 11.59%  |
| Intel                           | 8         | 11.59%  |
| TP-Link                         | 3         | 4.35%   |
| Marvell Technology Group        | 3         | 4.35%   |
| Ralink                          | 2         | 2.9%    |
| Broadcom Limited                | 2         | 2.9%    |
| Xiaomi                          | 1         | 1.45%   |
| TRENDnet                        | 1         | 1.45%   |
| Qualcomm Atheros Communications | 1         | 1.45%   |
| MediaTek                        | 1         | 1.45%   |
| Aquantia                        | 1         | 1.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 15        | 18.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 6         | 7.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 3.75%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 3         | 3.75%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 2         | 2.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 2.5%    |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 2         | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 2         | 2.5%    |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 2         | 2.5%    |
| Broadcom BCM43142 802.11b/g/n                                                         | 2         | 2.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 2.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                        | 1         | 1.25%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU]            | 1         | 1.25%   |
| TP-Link Archer T4U ver.3                                                              | 1         | 1.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.25%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1         | 1.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 1.25%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1         | 1.25%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.25%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 1.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 1         | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 1         | 1.25%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                            | 1         | 1.25%   |
| Realtek Killer E3000 2.5GbE Controller                                                | 1         | 1.25%   |
| Realtek 802.11ac NIC                                                                  | 1         | 1.25%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                             | 1         | 1.25%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 1         | 1.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 1.25%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 1.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 1.25%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 1.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 1.25%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                 | 1         | 1.25%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 1.25%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 1         | 1.25%   |
| Intel Wireless 7265                                                                   | 1         | 1.25%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 1.25%   |
| Intel Ethernet Connection I218-V                                                      | 1         | 1.25%   |
| Intel Ethernet Connection (2) I219-V                                                  | 1         | 1.25%   |
| Intel Ethernet Connection (11) I219-V                                                 | 1         | 1.25%   |
| Intel Centrino Advanced-N 6235                                                        | 1         | 1.25%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                      | 1         | 1.25%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                     | 1         | 1.25%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                             | 1         | 1.25%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 1         | 1.25%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                           | 1         | 1.25%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 1.25%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 1         | 1.25%   |
| Aquantia Ethernet controller                                                          | 1         | 1.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 11        | 27.5%   |
| Broadcom                        | 9         | 22.5%   |
| Qualcomm Atheros                | 7         | 17.5%   |
| Intel                           | 4         | 10%     |
| TP-Link                         | 3         | 7.5%    |
| Ralink                          | 2         | 5%      |
| TRENDnet                        | 1         | 2.5%    |
| Qualcomm Atheros Communications | 1         | 2.5%    |
| MediaTek                        | 1         | 2.5%    |
| Broadcom Limited                | 1         | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 7.32%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 2         | 4.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 4.88%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 2         | 4.88%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 2         | 4.88%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 2         | 4.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 4.88%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU]            | 1         | 2.44%   |
| TP-Link Archer T4U ver.3                                                              | 1         | 2.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 2.44%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1         | 2.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 2.44%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1         | 2.44%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 2.44%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 2.44%   |
| Realtek 802.11ac NIC                                                                  | 1         | 2.44%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                             | 1         | 2.44%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 1         | 2.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 2.44%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 2.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 2.44%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 2.44%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 2.44%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 1         | 2.44%   |
| Intel Wireless 7265                                                                   | 1         | 2.44%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 2.44%   |
| Intel Centrino Advanced-N 6235                                                        | 1         | 2.44%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                      | 1         | 2.44%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 1         | 2.44%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                           | 1         | 2.44%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 2.44%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 1         | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 25        | 64.1%   |
| Intel                    | 5         | 12.82%  |
| Marvell Technology Group | 3         | 7.69%   |
| Qualcomm Atheros         | 2         | 5.13%   |
| Xiaomi                   | 1         | 2.56%   |
| Broadcom Limited         | 1         | 2.56%   |
| Broadcom                 | 1         | 2.56%   |
| Aquantia                 | 1         | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 38.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 15.38%  |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 7.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.56%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 2.56%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 2.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.56%   |
| Intel Ethernet Connection I218-V                                  | 1         | 2.56%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.56%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 2.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.56%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 1         | 2.56%   |
| Aquantia Ethernet controller                                      | 1         | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 39        | 52%     |
| WiFi     | 36        | 48%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 66.67%  |
| Ethernet | 15        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 25        | 55.56%  |
| 1     | 19        | 42.22%  |
| 0     | 1         | 2.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 31        | 68.89%  |
| Yes  | 14        | 31.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 7         | 21.88%  |
| Apple                           | 6         | 18.75%  |
| Intel                           | 5         | 15.63%  |
| Broadcom                        | 4         | 12.5%   |
| Qualcomm Atheros Communications | 2         | 6.25%   |
| Lite-On Technology              | 2         | 6.25%   |
| Toshiba                         | 1         | 3.13%   |
| Ralink                          | 1         | 3.13%   |
| Marvell Semiconductor           | 1         | 3.13%   |
| IMC Networks                    | 1         | 3.13%   |
| Cambridge Silicon Radio         | 1         | 3.13%   |
| ASUSTek Computer                | 1         | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 5         | 15.63%  |
| Apple Bluetooth HCI                                 | 3         | 9.38%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 6.25%   |
| Toshiba Askey for                                   | 1         | 3.13%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.13%   |
| Realtek Bluetooth 5.1 Radio                         | 1         | 3.13%   |
| Ralink RT3290 Bluetooth                             | 1         | 3.13%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 3.13%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 3.13%   |
| Lite-On Bluetooth Device                            | 1         | 3.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.13%   |
| Intel Bluetooth wireless interface                  | 1         | 3.13%   |
| Intel Bluetooth Device                              | 1         | 3.13%   |
| Intel AX210 Bluetooth                               | 1         | 3.13%   |
| Intel AX200 Bluetooth                               | 1         | 3.13%   |
| IMC Networks Wireless_Device                        | 1         | 3.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.13%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 3.13%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 3.13%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 3.13%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 3.13%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 3.13%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 3.13%   |
| Apple Bluetooth USB Host Controller                 | 1         | 3.13%   |
| Apple Bluetooth Host Controller                     | 1         | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 34        | 60.71%  |
| AMD                      | 13        | 23.21%  |
| Nvidia                   | 8         | 14.29%  |
| Micro Star International | 1         | 1.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 8.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 6.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 5.41%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 5.41%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 4.05%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 4.05%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 4.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 4.05%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 4.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 2.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.7%    |
| Intel Comet Lake PCH cAVS                                                  | 2         | 2.7%    |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 2.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.35%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.35%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.35%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.35%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.35%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.35%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.35%   |
| Micro Star International USB Audio                                         | 1         | 1.35%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.35%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.35%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1         | 1.35%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 1.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.35%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 1.35%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1         | 1.35%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.35%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 1.35%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1         | 1.35%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 1.35%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1.35%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1         | 1.35%   |
| AMD High Definition Audio Controller                                       | 1         | 1.35%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.35%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 1.35%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 2         | 22.22%  |
| Kingston            | 2         | 22.22%  |
| Unknown             | 1         | 11.11%  |
| Samsung Electronics | 1         | 11.11%  |
| G.Skill             | 1         | 11.11%  |
| Crucial             | 1         | 11.11%  |
| A-DATA Technology   | 1         | 11.11%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8192MB DIMM 1066MT/s                  | 1         | 11.11%  |
| SK hynix RAM Module 2048MB SODIMM DDR3 1333MT/s          | 1         | 11.11%  |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s   | 1         | 11.11%  |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1         | 11.11%  |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s        | 1         | 11.11%  |
| Kingston RAM 9905783-049.A01G 16384MB DIMM 4800MT/s      | 1         | 11.11%  |
| G.Skill RAM F3-14900CL9-2GBXM 2048MB DIMM DDR3 1600MT/s  | 1         | 11.11%  |
| Crucial RAM CT25664BA1339.C8FE 2048MB DIMM DDR3 1333MT/s | 1         | 11.11%  |
| A-DATA RAM Module 4096MB DIMM DDR4 2400MT/s              | 1         | 11.11%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 3         | 42.86%  |
| DDR4    | 2         | 28.57%  |
| Unknown | 2         | 28.57%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 4         | 57.14%  |
| SODIMM | 3         | 42.86%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 3         | 37.5%   |
| 4096  | 2         | 25%     |
| 2048  | 2         | 25%     |
| 16384 | 1         | 12.5%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 2         | 22.22%  |
| 1333  | 2         | 22.22%  |
| 4800  | 1         | 11.11%  |
| 3200  | 1         | 11.11%  |
| 2933  | 1         | 11.11%  |
| 2400  | 1         | 11.11%  |
| 1066  | 1         | 11.11%  |

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

| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 9         | 36%     |
| Apple                                  | 4         | 16%     |
| Silicon Motion                         | 2         | 8%      |
| Quanta                                 | 2         | 8%      |
| Microdia                               | 2         | 8%      |
| Suyin                                  | 1         | 4%      |
| Realtek Semiconductor                  | 1         | 4%      |
| Microsoft                              | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4%      |
| Alcor Micro                            | 1         | 4%      |
| 8SSC20F27145V1SR1BX02P8                | 1         | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony USB 2.0 Camera                                  | 2         | 7.69%   |
| Chicony HP HD Webcam [Fixed]                            | 2         | 7.69%   |
| Apple Built-in iSight                                   | 2         | 7.69%   |
| Suyin Asus Integrated Webcam                            | 1         | 3.85%   |
| Silicon Motion WebCam SC-10HDP11538N                    | 1         | 3.85%   |
| Silicon Motion Web Camera                               | 1         | 3.85%   |
| Realtek Integrated_Webcam_HD                            | 1         | 3.85%   |
| Quanta HP Webcam                                        | 1         | 3.85%   |
| Quanta HP HD Camera                                     | 1         | 3.85%   |
| Microsoft Rear LifeCam                                  | 1         | 3.85%   |
| Microsoft Front LifeCam                                 | 1         | 3.85%   |
| Microdia Dell Laptop Integrated Webcam HD               | 1         | 3.85%   |
| Microdia Camera                                         | 1         | 3.85%   |
| Chicony VGA WebCam                                      | 1         | 3.85%   |
| Chicony USB2.0 HD UVC WebCam                            | 1         | 3.85%   |
| Chicony Integrated Camera                               | 1         | 3.85%   |
| Chicony HP Webcam                                       | 1         | 3.85%   |
| Chicony HP High Definition 1MP Webcam                   | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 1         | 3.85%   |
| Apple FaceTime Camera                                   | 1         | 3.85%   |
| Apple Built-in iSight [Micron]                          | 1         | 3.85%   |
| Alcor Micro Acer Integrated Webcam                      | 1         | 3.85%   |
| 8SSC20F27145V1SR1BX02P8 Integrated Camera               | 1         | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 50%     |
| Synaptics                  | 1         | 25%     |
| Shenzhen Goodix Technology | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS491                                    | 2         | 50%     |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 25%     |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 25%     |

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
| 0     | 33        | 73.33%  |
| 1     | 7         | 15.56%  |
| 2     | 5         | 11.11%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 6         | 35.29%  |
| Fingerprint reader    | 4         | 23.53%  |
| Graphics card         | 3         | 17.65%  |
| Multimedia controller | 2         | 11.76%  |
| Card reader           | 1         | 5.88%   |
| Bluetooth             | 1         | 5.88%   |

