LMDE - Hardware Trends
----------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/LMDE/Desktop/README.md) and [notebooks](/Dist/LMDE/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/linuxhw/TestCoverage)

Period: May, 2022.

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

| Name   | Computers | Percent |
|--------|-----------|---------|
| LMDE 5 | 31        | 96.88%  |
| LMDE 4 | 1         | 3.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| LMDE | 32        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.10.0-14-amd64      | 22        | 68.75%  |
| 5.10.0-13-amd64      | 3         | 9.38%   |
| 5.10.0-12-amd64      | 3         | 9.38%   |
| 5.16.0-0.bpo.4-amd64 | 1         | 3.13%   |
| 5.10.0-14-686        | 1         | 3.13%   |
| 5.10.0-13-686        | 1         | 3.13%   |
| 4.19.0-16-amd64      | 1         | 3.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 30        | 93.75%  |
| 5.16.0  | 1         | 3.13%   |
| 4.19.0  | 1         | 3.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 30        | 93.75%  |
| 5.16    | 1         | 3.13%   |
| 4.19    | 1         | 3.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 30        | 93.75%  |
| i686   | 2         | 6.25%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 27        | 84.38%  |
| Cinnamon   | 3         | 9.38%   |
| XFCE       | 1         | 3.13%   |
| MATE       | 1         | 3.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 32        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 18        | 56.25%  |
| LightDM | 14        | 43.75%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 15        | 46.88%  |
| pt_BR | 4         | 12.5%   |
| en_GB | 3         | 9.38%   |
| es_ES | 2         | 6.25%   |
| en_CA | 2         | 6.25%   |
| ru_RU | 1         | 3.13%   |
| it_IT | 1         | 3.13%   |
| es_EC | 1         | 3.13%   |
| en_IE | 1         | 3.13%   |
| en_AU | 1         | 3.13%   |
| de_DE | 1         | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 20        | 62.5%   |
| BIOS | 12        | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 31        | 96.88%  |
| Overlay | 1         | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 18        | 56.25%  |
| GPT     | 11        | 34.38%  |
| MBR     | 3         | 9.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 29        | 90.63%  |
| Yes       | 3         | 9.38%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 28        | 87.5%   |
| Yes       | 4         | 12.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 7         | 21.88%  |
| Lenovo              | 5         | 15.63%  |
| Acer                | 4         | 12.5%   |
| MSI                 | 3         | 9.38%   |
| Dell                | 3         | 9.38%   |
| ASUSTek Computer    | 3         | 9.38%   |
| Gigabyte Technology | 2         | 6.25%   |
| Toshiba             | 1         | 3.13%   |
| Philco              | 1         | 3.13%   |
| Intel               | 1         | 3.13%   |
| Howard Computers    | 1         | 3.13%   |
| Apple               | 1         | 3.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                             | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Toshiba Satellite M55                            | 1         | 3.13%   |
| Philco 10D                                       | 1         | 3.13%   |
| MSI MS-7B79                                      | 1         | 3.13%   |
| MSI MS-7B17                                      | 1         | 3.13%   |
| MSI MS-7974                                      | 1         | 3.13%   |
| Lenovo ThinkPad T480 20L6S1RN00                  | 1         | 3.13%   |
| Lenovo ThinkCentre M92p 3238E9U                  | 1         | 3.13%   |
| Lenovo Legion 5 15ACH6H 82JU                     | 1         | 3.13%   |
| Lenovo IdeaPad 5 14ALC05 82LM                    | 1         | 3.13%   |
| Lenovo IdeaPad 3 15ITL6 82H8                     | 1         | 3.13%   |
| Intel DQ77MK AAG39642-400                        | 1         | 3.13%   |
| Howard Computers R7X                             | 1         | 3.13%   |
| HP ZBook Fury 17.3 inch G8 Mobile Workstation PC | 1         | 3.13%   |
| HP Z820 Workstation                              | 1         | 3.13%   |
| HP Notebook                                      | 1         | 3.13%   |
| HP Laptop 14-df0xxx                              | 1         | 3.13%   |
| HP Laptop 14-cf3xxx                              | 1         | 3.13%   |
| HP ENVY 17                                       | 1         | 3.13%   |
| HP Compaq Pro 6300 SFF                           | 1         | 3.13%   |
| Gigabyte Z68A-D3H-B3                             | 1         | 3.13%   |
| Gigabyte H110M-S2H                               | 1         | 3.13%   |
| Dell XPS 13 9305                                 | 1         | 3.13%   |
| Dell Inspiron 5566                               | 1         | 3.13%   |
| Dell Inspiron 5559                               | 1         | 3.13%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA           | 1         | 3.13%   |
| ASUS VivoBook E14 E402YA_L402YA                  | 1         | 3.13%   |
| ASUS P5QL PRO                                    | 1         | 3.13%   |
| Apple MacBookAir7,2                              | 1         | 3.13%   |
| Acer Veriton L6610G                              | 1         | 3.13%   |
| Acer Aspire V3-571G                              | 1         | 3.13%   |
| Acer Aspire One 522                              | 1         | 3.13%   |
| Acer Aspire E1-532                               | 1         | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Acer Aspire          | 3         | 9.38%   |
| Lenovo IdeaPad       | 2         | 6.25%   |
| HP Laptop            | 2         | 6.25%   |
| Dell Inspiron        | 2         | 6.25%   |
| ASUS VivoBook        | 2         | 6.25%   |
| Toshiba Satellite    | 1         | 3.13%   |
| Philco 10D           | 1         | 3.13%   |
| MSI MS-7B79          | 1         | 3.13%   |
| MSI MS-7B17          | 1         | 3.13%   |
| MSI MS-7974          | 1         | 3.13%   |
| Lenovo ThinkPad      | 1         | 3.13%   |
| Lenovo ThinkCentre   | 1         | 3.13%   |
| Lenovo Legion        | 1         | 3.13%   |
| Intel DQ77MK         | 1         | 3.13%   |
| Howard Computers R7X | 1         | 3.13%   |
| HP ZBook             | 1         | 3.13%   |
| HP Z820              | 1         | 3.13%   |
| HP Notebook          | 1         | 3.13%   |
| HP ENVY              | 1         | 3.13%   |
| HP Compaq            | 1         | 3.13%   |
| Gigabyte Z68A-D3H-B3 | 1         | 3.13%   |
| Gigabyte H110M-S2H   | 1         | 3.13%   |
| Dell XPS             | 1         | 3.13%   |
| ASUS P5QL            | 1         | 3.13%   |
| Apple MacBookAir7    | 1         | 3.13%   |
| Acer Veriton         | 1         | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 5         | 15.63%  |
| 2018 | 5         | 15.63%  |
| 2012 | 5         | 15.63%  |
| 2016 | 4         | 12.5%   |
| 2019 | 3         | 9.38%   |
| 2020 | 2         | 6.25%   |
| 2015 | 2         | 6.25%   |
| 2011 | 2         | 6.25%   |
| 2013 | 1         | 3.13%   |
| 2010 | 1         | 3.13%   |
| 2008 | 1         | 3.13%   |
| 2006 | 1         | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 21        | 65.63%  |
| Desktop  | 11        | 34.38%  |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 29        | 90.63%  |
| Enabled  | 3         | 9.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 32        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 11        | 34.38%  |
| 16.01-24.0  | 7         | 21.88%  |
| 3.01-4.0    | 4         | 12.5%   |
| 32.01-64.0  | 3         | 9.38%   |
| 8.01-16.0   | 3         | 9.38%   |
| 24.01-32.0  | 1         | 3.13%   |
| 2.01-3.0    | 1         | 3.13%   |
| 64.01-256.0 | 1         | 3.13%   |
| 1.01-2.0    | 1         | 3.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 13        | 40.63%  |
| 1.01-2.0 | 11        | 34.38%  |
| 3.01-4.0 | 5         | 15.63%  |
| 4.01-8.0 | 2         | 6.25%   |
| 0.51-1.0 | 1         | 3.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 20        | 62.5%   |
| 2      | 7         | 21.88%  |
| 3      | 3         | 9.38%   |
| 4      | 2         | 6.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 22        | 68.75%  |
| Yes       | 10        | 31.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 87.5%   |
| No        | 4         | 12.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 84.38%  |
| No        | 5         | 15.63%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 65.63%  |
| No        | 11        | 34.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country   | Computers | Percent |
|-----------|-----------|---------|
| USA       | 7         | 21.88%  |
| UK        | 5         | 15.63%  |
| Brazil    | 4         | 12.5%   |
| Russia    | 3         | 9.38%   |
| Spain     | 2         | 6.25%   |
| Canada    | 2         | 6.25%   |
| Australia | 2         | 6.25%   |
| Romania   | 1         | 3.13%   |
| Mexico    | 1         | 3.13%   |
| Malaysia  | 1         | 3.13%   |
| Lithuania | 1         | 3.13%   |
| Italy     | 1         | 3.13%   |
| Germany   | 1         | 3.13%   |
| Ecuador   | 1         | 3.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Neasden                 | 2         | 6.25%   |
| Moscow                  | 2         | 6.25%   |
| Melbourne               | 2         | 6.25%   |
| Vilnius                 | 1         | 3.13%   |
| Victoria                | 1         | 3.13%   |
| Vicente Guerrero        | 1         | 3.13%   |
| Trieste                 | 1         | 3.13%   |
| Toledo                  | 1         | 3.13%   |
| Spruce Grove            | 1         | 3.13%   |
| Saratov                 | 1         | 3.13%   |
| Sant Feliu de Llobregat | 1         | 3.13%   |
| Recife                  | 1         | 3.13%   |
| Petaling Jaya           | 1         | 3.13%   |
| Monaca                  | 1         | 3.13%   |
| Mammoth Lakes           | 1         | 3.13%   |
| Londonderry             | 1         | 3.13%   |
| London                  | 1         | 3.13%   |
| Lebanon                 | 1         | 3.13%   |
| Everett                 | 1         | 3.13%   |
| Detroit                 | 1         | 3.13%   |
| Branesti                | 1         | 3.13%   |
| Blairsville             | 1         | 3.13%   |
| Birmingham              | 1         | 3.13%   |
| Birigui                 | 1         | 3.13%   |
| Berlin                  | 1         | 3.13%   |
| Bandeirantes            | 1         | 3.13%   |
| Babahoyo                | 1         | 3.13%   |
| Avilés                 | 1         | 3.13%   |
| Andradina               | 1         | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 7         | 8      | 15.22%  |
| WDC                       | 6         | 8      | 13.04%  |
| Seagate                   | 5         | 6      | 10.87%  |
| Toshiba                   | 4         | 4      | 8.7%    |
| Crucial                   | 3         | 3      | 6.52%   |
| A-DATA Technology         | 3         | 3      | 6.52%   |
| Unknown                   | 2         | 2      | 4.35%   |
| SanDisk                   | 2         | 2      | 4.35%   |
| Micron Technology         | 2         | 2      | 4.35%   |
| Intel                     | 2         | 2      | 4.35%   |
| Hitachi                   | 2         | 2      | 4.35%   |
| SK Hynix                  | 1         | 1      | 2.17%   |
| PNY                       | 1         | 1      | 2.17%   |
| Patriot                   | 1         | 1      | 2.17%   |
| Micron/Crucial Technology | 1         | 1      | 2.17%   |
| KIOXIA                    | 1         | 2      | 2.17%   |
| Kingston                  | 1         | 1      | 2.17%   |
| BHT                       | 1         | 1      | 2.17%   |
| Apple                     | 1         | 1      | 2.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown SD/MMC/MS PRO 999GB           | 2         | 4.17%   |
| Micron NVMe SSD Drive 512GB           | 2         | 4.17%   |
| Crucial CT480BX500SSD1 480GB          | 2         | 4.17%   |
| A-DATA SU650 120GB SSD                | 2         | 4.17%   |
| WDC WD7500BPVT-22HXZT3 752GB          | 1         | 2.08%   |
| WDC WD60EZAZ-00ZGHB0 6TB              | 1         | 2.08%   |
| WDC WD3200BPVT-22JJ5T0 320GB          | 1         | 2.08%   |
| WDC WD3200AAKS-00SBA0 320GB           | 1         | 2.08%   |
| WDC WD3003FZEX-00Z4SA0 3TB            | 1         | 2.08%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB  | 1         | 2.08%   |
| Toshiba MQ01ABF032 320GB              | 1         | 2.08%   |
| Toshiba MQ01ABD100 1TB                | 1         | 2.08%   |
| Toshiba MK3275GSX 320GB               | 1         | 2.08%   |
| Toshiba MK3252GSX 320GB               | 1         | 2.08%   |
| SK Hynix HFS256G32MND-3310A 256GB SSD | 1         | 2.08%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 2.08%   |
| Seagate ST2000LM007-1R8174 2TB        | 1         | 2.08%   |
| Seagate ST2000DM008-2FR102 2TB        | 1         | 2.08%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 2.08%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 2.08%   |
| Seagate ST1000DM003-1CH162 1TB        | 1         | 2.08%   |
| SanDisk SDSSDA240G 240GB              | 1         | 2.08%   |
| SanDisk DF4064  64GB                  | 1         | 2.08%   |
| Samsung SSD 980 PRO 1TB               | 1         | 2.08%   |
| Samsung SSD 970 EVO Plus 1TB          | 1         | 2.08%   |
| Samsung SSD 860 EVO 1TB               | 1         | 2.08%   |
| Samsung SSD 850 EVO 500GB             | 1         | 2.08%   |
| Samsung SSD 850 EVO 250GB             | 1         | 2.08%   |
| Samsung PM991a NVMe 512GB             | 1         | 2.08%   |
| Samsung NVMe SSD Drive 1TB            | 1         | 2.08%   |
| Samsung MZMTE128HMGR-000MV 128GB SSD  | 1         | 2.08%   |
| PNY CS1311 480GB SSD                  | 1         | 2.08%   |
| Patriot P210 512GB SSD                | 1         | 2.08%   |
| Micron/Crucial NVMe SSD Drive 2TB     | 1         | 2.08%   |
| KIOXIA KXG60PNV2T04 2TB               | 1         | 2.08%   |
| Kingston SUV400S37120G 120GB SSD      | 1         | 2.08%   |
| Intel SSDSC2CW060A3 64GB              | 1         | 2.08%   |
| Intel SSDPEKNW512G8 512GB             | 1         | 2.08%   |
| Hitachi HTS543232A7A384 320GB         | 1         | 2.08%   |
| Hitachi HTS541010G9AT00 100GB         | 1         | 2.08%   |
| Crucial CT525MX300SSD1 528GB          | 1         | 2.08%   |
| BHT WR202I0064G E70245F5 64GB         | 1         | 2.08%   |
| Apple SSD SM0128G 121GB               | 1         | 2.08%   |
| A-DATA ED600 1TB SSD                  | 1         | 2.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 7      | 27.78%  |
| Seagate | 5         | 6      | 27.78%  |
| Toshiba | 4         | 4      | 22.22%  |
| Unknown | 2         | 2      | 11.11%  |
| Hitachi | 2         | 2      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 4      | 17.65%  |
| Crucial             | 3         | 3      | 17.65%  |
| A-DATA Technology   | 3         | 3      | 17.65%  |
| SK Hynix            | 1         | 1      | 5.88%   |
| SanDisk             | 1         | 1      | 5.88%   |
| PNY                 | 1         | 1      | 5.88%   |
| Patriot             | 1         | 1      | 5.88%   |
| Kingston            | 1         | 1      | 5.88%   |
| Intel               | 1         | 1      | 5.88%   |
| BHT                 | 1         | 1      | 5.88%   |
| Apple               | 1         | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 21     | 40.48%  |
| SSD  | 15        | 18     | 35.71%  |
| NVMe | 9         | 11     | 21.43%  |
| MMC  | 1         | 1      | 2.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 24        | 36     | 66.67%  |
| NVMe | 9         | 11     | 25%     |
| SAS  | 2         | 3      | 5.56%   |
| MMC  | 1         | 1      | 2.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 18        | 22     | 60%     |
| 0.51-1.0   | 8         | 11     | 26.67%  |
| 1.01-2.0   | 2         | 2      | 6.67%   |
| 2.01-3.0   | 1         | 3      | 3.33%   |
| 4.01-10.0  | 1         | 1      | 3.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 12        | 37.5%   |
| 51-100         | 5         | 15.63%  |
| 101-250        | 4         | 12.5%   |
| 501-1000       | 4         | 12.5%   |
| 1001-2000      | 3         | 9.38%   |
| More than 3000 | 1         | 3.13%   |
| 21-50          | 1         | 3.13%   |
| 2001-3000      | 1         | 3.13%   |
| 1-20           | 1         | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 21-50    | 11        | 34.38%  |
| 1-20     | 10        | 31.25%  |
| 501-1000 | 4         | 12.5%   |
| 101-250  | 3         | 9.38%   |
| 251-500  | 2         | 6.25%   |
| 51-100   | 2         | 6.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Detected | 19        | 28     | 57.58%  |
| Works    | 13        | 22     | 39.39%  |
| Malfunc  | 1         | 1      | 3.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 22        | 51.16%  |
| AMD                          | 8         | 18.6%   |
| Samsung Electronics          | 5         | 11.63%  |
| Micron Technology            | 2         | 4.65%   |
| Toshiba America Info Systems | 1         | 2.33%   |
| Sandisk                      | 1         | 2.33%   |
| Micron/Crucial Technology    | 1         | 2.33%   |
| Marvell Technology Group     | 1         | 2.33%   |
| Broadcom / LSI               | 1         | 2.33%   |
| ASMedia Technology           | 1         | 2.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 5         | 10.2%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 8.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 6.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 4.08%   |
| Micron Non-Volatile memory controller                                                   | 2         | 4.08%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 4.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 4.08%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 2.04%   |
| Sandisk Non-Volatile memory controller                                                  | 1         | 2.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 2.04%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 2.04%   |
| Samsung Electronics SATA controller                                                     | 1         | 2.04%   |
| Micron/Crucial NVMe Controller                                                          | 1         | 2.04%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1         | 2.04%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 1         | 2.04%   |
| Intel SSD 660P Series                                                                   | 1         | 2.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 2.04%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1         | 2.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 2.04%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1         | 2.04%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1         | 2.04%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1         | 2.04%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1         | 2.04%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1         | 2.04%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                  | 1         | 2.04%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 1         | 2.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1         | 2.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1         | 2.04%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1         | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 1         | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 2.04%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1         | 2.04%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 2.04%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1         | 2.04%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 24        | 55.81%  |
| NVMe | 9         | 20.93%  |
| IDE  | 5         | 11.63%  |
| RAID | 4         | 9.3%    |
| SAS  | 1         | 2.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 24        | 75%     |
| AMD    | 8         | 25%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2600 CPU @ 3.40GHz              | 2         | 6.25%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz           | 1         | 3.13%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 3.13%   |
| Intel Pentium M processor 1.73GHz             | 1         | 3.13%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 1         | 3.13%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 1         | 3.13%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 3.13%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 3.13%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1         | 3.13%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 3.13%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 1         | 3.13%   |
| Intel Core i5-3470S CPU @ 2.90GHz             | 1         | 3.13%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 3.13%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 3.13%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 3.13%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 3.13%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 1         | 3.13%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz          | 1         | 3.13%   |
| Intel Celeron 2955U @ 1.40GHz                 | 1         | 3.13%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 1         | 3.13%   |
| Intel 11th Gen Core i9-11950H @ 2.60GHz       | 1         | 3.13%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 3.13%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 3.13%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 1         | 3.13%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 3.13%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 3.13%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.13%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 1         | 3.13%   |
| AMD FX-4300 Quad-Core Processor               | 1         | 3.13%   |
| AMD E2-7015 APU with AMD Radeon R2 Graphics   | 1         | 3.13%   |
| AMD C-50 Processor                            | 1         | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 6         | 18.75%  |
| Intel Core i5        | 5         | 15.63%  |
| Other                | 3         | 9.38%   |
| Intel Core i3        | 3         | 9.38%   |
| AMD Ryzen 5          | 3         | 9.38%   |
| AMD Ryzen 7          | 2         | 6.25%   |
| Intel Xeon           | 1         | 3.13%   |
| Intel Pentium Silver | 1         | 3.13%   |
| Intel Pentium M      | 1         | 3.13%   |
| Intel Pentium        | 1         | 3.13%   |
| Intel Core 2 Duo     | 1         | 3.13%   |
| Intel Celeron        | 1         | 3.13%   |
| Intel Atom           | 1         | 3.13%   |
| AMD FX               | 1         | 3.13%   |
| AMD E2               | 1         | 3.13%   |
| AMD C-50             | 1         | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 15        | 46.88%  |
| 4      | 10        | 31.25%  |
| 8      | 4         | 12.5%   |
| 16     | 1         | 3.13%   |
| 6      | 1         | 3.13%   |
| 1      | 1         | 3.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 31        | 96.88%  |
| 2      | 1         | 3.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 22        | 68.75%  |
| 1      | 10        | 31.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 31        | 96.88%  |
| 32-bit         | 1         | 3.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x406e3    | 3         | 9.38%   |
| 0x306a9    | 3         | 9.38%   |
| Unknown    | 3         | 9.38%   |
| 0x806c1    | 2         | 6.25%   |
| 0x206a7    | 2         | 6.25%   |
| 0x906ed    | 1         | 3.13%   |
| 0x806e9    | 1         | 3.13%   |
| 0x806d1    | 1         | 3.13%   |
| 0x706e5    | 1         | 3.13%   |
| 0x706a1    | 1         | 3.13%   |
| 0x6d8      | 1         | 3.13%   |
| 0x506e3    | 1         | 3.13%   |
| 0x40651    | 1         | 3.13%   |
| 0x306d4    | 1         | 3.13%   |
| 0x306c3    | 1         | 3.13%   |
| 0x30661    | 1         | 3.13%   |
| 0x206d7    | 1         | 3.13%   |
| 0x08608103 | 1         | 3.13%   |
| 0x08600103 | 1         | 3.13%   |
| 0x08108109 | 1         | 3.13%   |
| 0x08108102 | 1         | 3.13%   |
| 0x07030106 | 1         | 3.13%   |
| 0x06000852 | 1         | 3.13%   |
| 0x05000029 | 1         | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| Skylake       | 4         | 12.5%   |
| IvyBridge     | 4         | 12.5%   |
| SandyBridge   | 3         | 9.38%   |
| Zen+          | 2         | 6.25%   |
| TigerLake     | 2         | 6.25%   |
| KabyLake      | 2         | 6.25%   |
| Icelake       | 2         | 6.25%   |
| Haswell       | 2         | 6.25%   |
| Zen 3         | 1         | 3.13%   |
| Zen 2         | 1         | 3.13%   |
| Puma          | 1         | 3.13%   |
| Piledriver    | 1         | 3.13%   |
| P6            | 1         | 3.13%   |
| Goldmont plus | 1         | 3.13%   |
| Core          | 1         | 3.13%   |
| Broadwell     | 1         | 3.13%   |
| Bonnell       | 1         | 3.13%   |
| Bobcat        | 1         | 3.13%   |
| Unknown       | 1         | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 16        | 44.44%  |
| Nvidia | 12        | 33.33%  |
| AMD    | 8         | 22.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                           | 3         | 8.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 5.56%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                         | 1         | 2.78%   |
| Nvidia GT218 [GeForce 210]                                                    | 1         | 2.78%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 2.78%   |
| Nvidia GM108M [GeForce 840M]                                                  | 1         | 2.78%   |
| Nvidia GM107GL [Quadro K620]                                                  | 1         | 2.78%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 1         | 2.78%   |
| Nvidia GK208B [GeForce GT 730]                                                | 1         | 2.78%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                             | 1         | 2.78%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                             | 1         | 2.78%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                             | 1         | 2.78%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                            | 1         | 2.78%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 1         | 2.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 1         | 2.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 2.78%   |
| Intel Tiger Lake UHD Graphics                                                 | 1         | 2.78%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 2.78%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 2.78%   |
| Intel HD Graphics 620                                                         | 1         | 2.78%   |
| Intel HD Graphics 6000                                                        | 1         | 2.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 2.78%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 2.78%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 2.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 2.78%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 1         | 2.78%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 2.78%   |
| AMD Wrestler [Radeon HD 6250]                                                 | 1         | 2.78%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 1         | 2.78%   |
| AMD RV635 [Radeon HD 3650/3750/4570/4580]                                     | 1         | 2.78%   |
| AMD Renoir                                                                    | 1         | 2.78%   |
| AMD Mullins [Radeon R2 Graphics]                                              | 1         | 2.78%   |
| AMD Lucienne                                                                  | 1         | 2.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 40.63%  |
| 1 x Nvidia     | 9         | 28.13%  |
| 1 x AMD        | 6         | 18.75%  |
| Intel + Nvidia | 2         | 6.25%   |
| Intel + AMD    | 1         | 3.13%   |
| AMD + Nvidia   | 1         | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 27        | 84.38%  |
| Proprietary | 4         | 12.5%   |
| Unknown     | 1         | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 50%     |
| 1.01-2.0   | 7         | 21.88%  |
| 0.01-0.5   | 4         | 12.5%   |
| 3.01-4.0   | 2         | 6.25%   |
| 0.51-1.0   | 2         | 6.25%   |
| 5.01-6.0   | 1         | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 5         | 14.29%  |
| BOE                  | 5         | 14.29%  |
| AU Optronics         | 4         | 11.43%  |
| Samsung Electronics  | 3         | 8.57%   |
| Philips              | 2         | 5.71%   |
| LG Display           | 2         | 5.71%   |
| Ancor Communications | 2         | 5.71%   |
| ___                  | 1         | 2.86%   |
| Unknown              | 1         | 2.86%   |
| Sharp                | 1         | 2.86%   |
| LG Philips           | 1         | 2.86%   |
| Lenovo               | 1         | 2.86%   |
| Insignia             | 1         | 2.86%   |
| InfoVision           | 1         | 2.86%   |
| DENON                | 1         | 2.86%   |
| BenQ                 | 1         | 2.86%   |
| ASUSTek Computer     | 1         | 2.86%   |
| Apple                | 1         | 2.86%   |
| Acer                 | 1         | 2.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| ___ LCDTV14 ___0101 1920x1080                                      | 1         | 2.86%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                 | 1         | 2.86%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch            | 1         | 2.86%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch  | 1         | 2.86%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch | 1         | 2.86%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch  | 1         | 2.86%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch            | 1         | 2.86%   |
| Philips LCD Monitor PHL 242V8 1920x1080                            | 1         | 2.86%   |
| LG Philips LCD Monitor LPL0001 1280x768 305x183mm 14.0-inch        | 1         | 2.86%   |
| LG Display LCD Monitor LGD04DA 1920x1080 344x194mm 15.5-inch       | 1         | 2.86%   |
| LG Display LCD Monitor LGD03FB 1920x1080 382x215mm 17.3-inch       | 1         | 2.86%   |
| Lenovo LEN L1900pA LEN114F 1280x1024 376x301mm 19.0-inch           | 1         | 2.86%   |
| Insignia NS-32F202NA22 BBY3292 1920x1080 697x392mm 31.5-inch       | 1         | 2.86%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch        | 1         | 2.86%   |
| DENON AVR DON005F 1920x1080                                        | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch   | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch    | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch    | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch    | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch   | 1         | 2.86%   |
| BOE LCD Monitor BOE08E8 1920x1080 340x190mm 15.3-inch              | 1         | 2.86%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch              | 1         | 2.86%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch               | 1         | 2.86%   |
| BOE LCD Monitor BOE072B 1920x1080 309x173mm 13.9-inch              | 1         | 2.86%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch               | 1         | 2.86%   |
| BenQ GL2750H BNQ78AD 1920x1080 598x336mm 27.0-inch                 | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch     | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch      | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch     | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO20D5 1280x720 222x125mm 10.0-inch      | 1         | 2.86%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch       | 1         | 2.86%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch               | 1         | 2.86%   |
| Ancor Communications VW246 ACI24F2 1920x1080 531x299mm 24.0-inch   | 1         | 2.86%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch   | 1         | 2.86%   |
| Acer LCD Monitor S240HL 1920x1080                                  | 1         | 2.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 20        | 62.5%   |
| 1366x768 (WXGA)   | 6         | 18.75%  |
| 3840x2160 (4K)    | 1         | 3.13%   |
| 1920x1200 (WUXGA) | 1         | 3.13%   |
| 1440x900 (WXGA+)  | 1         | 3.13%   |
| 1280x768          | 1         | 3.13%   |
| 1280x720 (HD)     | 1         | 3.13%   |
| 1280x1024 (SXGA)  | 1         | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 10        | 28.57%  |
| 13      | 6         | 17.14%  |
| 24      | 5         | 14.29%  |
| 72      | 2         | 5.71%   |
| 27      | 2         | 5.71%   |
| 21      | 2         | 5.71%   |
| 14      | 2         | 5.71%   |
| Unknown | 2         | 5.71%   |
| 31      | 1         | 2.86%   |
| 20      | 1         | 2.86%   |
| 17      | 1         | 2.86%   |
| 10      | 1         | 2.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 45.71%  |
| 501-600     | 7         | 20%     |
| 201-300     | 3         | 8.57%   |
| 401-500     | 2         | 5.71%   |
| 351-400     | 2         | 5.71%   |
| 1501-2000   | 2         | 5.71%   |
| Unknown     | 2         | 5.71%   |
| 601-700     | 1         | 2.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 26        | 86.67%  |
| Unknown | 2         | 6.67%   |
| 5/4     | 1         | 3.33%   |
| 16/10   | 1         | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 9         | 25.71%  |
| 81-90          | 6         | 17.14%  |
| 201-250        | 6         | 17.14%  |
| More than 1000 | 2         | 5.71%   |
| 71-80          | 2         | 5.71%   |
| 301-350        | 2         | 5.71%   |
| Unknown        | 2         | 5.71%   |
| 351-500        | 1         | 2.86%   |
| 41-50          | 1         | 2.86%   |
| 251-300        | 1         | 2.86%   |
| 151-200        | 1         | 2.86%   |
| 121-130        | 1         | 2.86%   |
| 91-100         | 1         | 2.86%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 11        | 31.43%  |
| 101-120 | 10        | 28.57%  |
| 51-100  | 9         | 25.71%  |
| 1-50    | 2         | 5.71%   |
| Unknown | 2         | 5.71%   |
| 161-240 | 1         | 2.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 26        | 81.25%  |
| 2     | 4         | 12.5%   |
| 3     | 1         | 3.13%   |
| 0     | 1         | 3.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 18        | 38.3%   |
| Intel                    | 17        | 36.17%  |
| Qualcomm Atheros         | 6         | 12.77%  |
| Broadcom                 | 2         | 4.26%   |
| Samsung Electronics      | 1         | 2.13%   |
| Marvell Technology Group | 1         | 2.13%   |
| JMicron Technology       | 1         | 2.13%   |
| Broadcom Limited         | 1         | 2.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 16.95%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 8.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 5.08%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 5.08%   |
| Intel Wireless 8265 / 8275                                        | 2         | 3.39%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 3.39%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 1.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.69%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.69%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                            | 1         | 1.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 1.69%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 1.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.69%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.69%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 1.69%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.69%   |
| Intel Wireless 7260                                               | 1         | 1.69%   |
| Intel Wireless 3165                                               | 1         | 1.69%   |
| Intel Wireless 3160                                               | 1         | 1.69%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.69%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.69%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection          | 1         | 1.69%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.69%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.69%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller  | 1         | 1.69%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.69%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.69%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 1         | 1.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 12        | 44.44%  |
| Realtek Semiconductor | 9         | 33.33%  |
| Qualcomm Atheros      | 5         | 18.52%  |
| Broadcom Limited      | 1         | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 3         | 11.11%  |
| Intel Wireless 8265 / 8275                                     | 2         | 7.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 3.7%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 3.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 3.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 3.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 3.7%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 3.7%    |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 1         | 3.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 3.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 3.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 3.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 3.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 3.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 3.7%    |
| Intel Wireless 7260                                            | 1         | 3.7%    |
| Intel Wireless 3165                                            | 1         | 3.7%    |
| Intel Wireless 3160                                            | 1         | 3.7%    |
| Intel Wi-Fi 6 AX201                                            | 1         | 3.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 3.7%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection       | 1         | 3.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 3.7%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 1         | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 14        | 48.28%  |
| Intel                    | 8         | 27.59%  |
| Qualcomm Atheros         | 2         | 6.9%    |
| Broadcom                 | 2         | 6.9%    |
| Samsung Electronics      | 1         | 3.45%   |
| Marvell Technology Group | 1         | 3.45%   |
| JMicron Technology       | 1         | 3.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 32.26%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 16.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 9.68%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 6.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 3.23%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 3.23%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 3.23%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 3.23%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 3.23%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 3.23%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 3.23%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.23%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 3.23%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 3.23%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 3.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 28        | 50%     |
| WiFi     | 27        | 48.21%  |
| Modem    | 1         | 1.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 68.75%  |
| Ethernet | 10        | 31.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 21        | 65.63%  |
| 1     | 11        | 34.38%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 23        | 71.88%  |
| Yes  | 9         | 28.13%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 52.38%  |
| Realtek Semiconductor           | 4         | 19.05%  |
| Cambridge Silicon Radio         | 2         | 9.52%   |
| Qualcomm Atheros Communications | 1         | 4.76%   |
| IMC Networks                    | 1         | 4.76%   |
| Foxconn / Hon Hai               | 1         | 4.76%   |
| Apple                           | 1         | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 23.81%  |
| Intel AX200 Bluetooth                               | 3         | 14.29%  |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 9.52%   |
| Realtek Bluetooth Radio                             | 2         | 9.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 9.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 9.52%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 4.76%   |
| Intel AX201 Bluetooth                               | 1         | 4.76%   |
| IMC Networks Bluetooth Device                       | 1         | 4.76%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 4.76%   |
| Apple Bluetooth USB Host Controller                 | 1         | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 23        | 51.11%  |
| Nvidia              | 11        | 24.44%  |
| AMD                 | 9         | 20%     |
| C-Media Electronics | 2         | 4.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 5         | 9.26%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 7.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 7.41%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 3.7%    |
| Nvidia Audio device                                                        | 2         | 3.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 3.7%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 3.7%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 3.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 3.7%    |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.85%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.85%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 1.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.85%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 1.85%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 1.85%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.85%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.85%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.85%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.85%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1         | 1.85%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.85%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 1.85%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.85%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.85%   |
| C-Media Electronics REIYIN Audio DA-02                                     | 1         | 1.85%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                        | 1         | 1.85%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 1.85%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                            | 1         | 1.85%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.85%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 3         | 20%     |
| Samsung Electronics | 3         | 20%     |
| Micron Technology   | 3         | 20%     |
| SK Hynix            | 2         | 13.33%  |
| Corsair             | 2         | 13.33%  |
| G.Skill             | 1         | 6.67%   |
| Crucial             | 1         | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s               | 1         | 6.25%   |
| Unknown RAM Module 512MB SODIMM DDR                       | 1         | 6.25%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 6.25%   |
| Unknown RAM Module 1GB SODIMM DDR                         | 1         | 6.25%   |
| SK Hynix RAM Module 32GB SODIMM DDR4 3200MT/s             | 1         | 6.25%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 6.25%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s               | 1         | 6.25%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 6.25%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 1         | 6.25%   |
| Micron RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s    | 1         | 6.25%   |
| Micron RAM 18JSF1G72PZ-1G9E1 8GB DIMM DDR3 1866MT/s       | 1         | 6.25%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s      | 1         | 6.25%   |
| G.Skill RAM F4-3000C16-16GVRB 16GB DIMM DDR4 3200MT/s     | 1         | 6.25%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s     | 1         | 6.25%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s     | 1         | 6.25%   |
| Corsair RAM CMSX32GX4M2A3200C22 16GB SODIMM DDR4 3200MT/s | 1         | 6.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 7         | 50%     |
| DDR4   | 5         | 35.71%  |
| LPDDR4 | 1         | 7.14%   |
| DDR    | 1         | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 9         | 64.29%  |
| DIMM         | 4         | 28.57%  |
| Row Of Chips | 1         | 7.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 4         | 26.67%  |
| 4096  | 4         | 26.67%  |
| 16384 | 2         | 13.33%  |
| 2048  | 2         | 13.33%  |
| 32768 | 1         | 6.67%   |
| 1024  | 1         | 6.67%   |
| 512   | 1         | 6.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 6         | 42.86%  |
| 3200    | 3         | 21.43%  |
| 4267    | 1         | 7.14%   |
| 2667    | 1         | 7.14%   |
| 2400    | 1         | 7.14%   |
| 1866    | 1         | 7.14%   |
| Unknown | 1         | 7.14%   |

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

| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 4         | 20%     |
| IMC Networks                  | 3         | 15%     |
| Suyin                         | 2         | 10%     |
| Quanta                        | 2         | 10%     |
| Microdia                      | 2         | 10%     |
| Sunplus Innovation Technology | 1         | 5%      |
| Realtek Semiconductor         | 1         | 5%      |
| Lite-On Technology            | 1         | 5%      |
| Intel                         | 1         | 5%      |
| Creative Technology           | 1         | 5%      |
| ARC International             | 1         | 5%      |
| Acer                          | 1         | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Suyin HP TrueVision HD                   | 1         | 5%      |
| Suyin HD WebCam                          | 1         | 5%      |
| Sunplus HD WebCam                        | 1         | 5%      |
| Realtek HP "Truevision HD" laptop camera | 1         | 5%      |
| Quanta HP Webcam                         | 1         | 5%      |
| Quanta HP HD Camera                      | 1         | 5%      |
| Microdia Integrated_Webcam_HD            | 1         | 5%      |
| Microdia Integrated Webcam HD            | 1         | 5%      |
| Lite-On HP TrueVision HD Camera          | 1         | 5%      |
| Intel RealSense 3D Camera (Front F200)   | 1         | 5%      |
| IMC Networks USB2.0 VGA UVC WebCam       | 1         | 5%      |
| IMC Networks USB2.0 HD UVC WebCam        | 1         | 5%      |
| IMC Networks Integrated Camera           | 1         | 5%      |
| Creative Live! Cam Sync HD [VF0770]      | 1         | 5%      |
| Chicony Integrated Camera (1280x720@30)  | 1         | 5%      |
| Chicony Integrated Camera                | 1         | 5%      |
| Chicony HD Webcam                        | 1         | 5%      |
| Chicony 1.3M Webcam                      | 1         | 5%      |
| ARC International Camera                 | 1         | 5%      |
| Acer Integrated Camera                   | 1         | 5%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 1         | 25%     |
| Synaptics                  | 1         | 25%     |
| Shenzhen Goodix Technology | 1         | 25%     |
| Elan Microelectronics      | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Validity Sensors Swipe Fingerprint Sensor | 1         | 25%     |
| Shenzhen Goodix  Fingerprint Device       | 1         | 25%     |
| Elan ELAN:Fingerprint                     | 1         | 25%     |
| Unknown                                   | 1         | 25%     |

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
| 0     | 26        | 81.25%  |
| 1     | 5         | 15.63%  |
| 2     | 1         | 3.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 3         | 42.86%  |
| Multimedia controller | 2         | 28.57%  |
| Net/wireless          | 1         | 14.29%  |
| Graphics card         | 1         | 14.29%  |

