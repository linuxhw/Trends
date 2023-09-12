Elementary - Hardware Trends
----------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary/Desktop/README.md) and [notebooks](/Dist/Elementary/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: Aug, 2023.

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

| Name             | Computers | Percent |
|------------------|-----------|---------|
| Elementary 7     | 39        | 78%     |
| Elementary 6.1   | 10        | 20%     |
| Elementary 5.1.7 | 1         | 2%      |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Elementary | 50        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 6.2.0-26-generic  | 23        | 46%     |
| 5.15.0-58-generic | 8         | 16%     |
| 6.2.0-31-generic  | 4         | 8%      |
| 5.19.0-50-generic | 3         | 6%      |
| 5.15.0-79-generic | 3         | 6%      |
| 5.15.0-71-generic | 2         | 4%      |
| 5.15.0-52-generic | 2         | 4%      |
| 5.4.0-73-generic  | 1         | 2%      |
| 5.15.0-78-generic | 1         | 2%      |
| 5.15.0-76-generic | 1         | 2%      |
| 5.15.0-57-generic | 1         | 2%      |
| 5.15.0-46-generic | 1         | 2%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.0   | 27        | 54%     |
| 5.15.0  | 19        | 38%     |
| 5.19.0  | 3         | 6%      |
| 5.4.0   | 1         | 2%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 27        | 54%     |
| 5.15    | 19        | 38%     |
| 5.19    | 3         | 6%      |
| 5.4     | 1         | 2%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 50        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Pantheon | 49        | 98%     |
| GNOME    | 1         | 2%      |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 50        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 37        | 74%     |
| LightDM | 13        | 26%     |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 26        | 52%     |
| ru_RU | 6         | 12%     |
| fr_FR | 4         | 8%      |
| pl_PL | 3         | 6%      |
| pt_BR | 2         | 4%      |
| en_CA | 2         | 4%      |
| de_DE | 2         | 4%      |
| nl_NL | 1         | 2%      |
| it_IT | 1         | 2%      |
| es_ES | 1         | 2%      |
| de_CH | 1         | 2%      |
| bg_BG | 1         | 2%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 37        | 74%     |
| EFI  | 13        | 26%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 45        | 90%     |
| Tmpfs | 5         | 10%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 37        | 74%     |
| GPT     | 9         | 18%     |
| MBR     | 4         | 8%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 49        | 98%     |
| Yes       | 1         | 2%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 45        | 90%     |
| Yes       | 5         | 10%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Apple               | 12        | 24%     |
| Hewlett-Packard     | 9         | 18%     |
| Lenovo              | 8         | 16%     |
| Dell                | 4         | 8%      |
| Acer                | 4         | 8%      |
| ASUSTek Computer    | 2         | 4%      |
| Pegatron            | 1         | 2%      |
| Packard Bell        | 1         | 2%      |
| Medion              | 1         | 2%      |
| LG Electronics      | 1         | 2%      |
| HUAWEI              | 1         | 2%      |
| Google              | 1         | 2%      |
| Gigabyte Technology | 1         | 2%      |
| Gateway             | 1         | 2%      |
| Digma               | 1         | 2%      |
| ASRock              | 1         | 2%      |
| Unknown             | 1         | 2%      |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell OptiPlex 790                        | 2         | 4%      |
| Apple MacBookAir6,2                      | 2         | 4%      |
| Apple iMac12,1                           | 2         | 4%      |
| Pegatron Pro 3010 Microtower PC          | 1         | 2%      |
| Packard Bell EasyNote LS11HR             | 1         | 2%      |
| Medion E15301                            | 1         | 2%      |
| LG V320-M.BG33P1                         | 1         | 2%      |
| Lenovo Yoga 530-14ARR 81H9               | 1         | 2%      |
| Lenovo ThinkPad X201 Tablet 2985DMG      | 1         | 2%      |
| Lenovo ThinkPad T540p 20BFS02S00         | 1         | 2%      |
| Lenovo ThinkPad T470 20JNS08H00          | 1         | 2%      |
| Lenovo ThinkPad Edge E330 33542E4        | 1         | 2%      |
| Lenovo Legion Y530-15ICH 81FV            | 1         | 2%      |
| Lenovo IdeaPad 3 14ALC6 82KT             | 1         | 2%      |
| Lenovo G570 20079                        | 1         | 2%      |
| HUAWEI KLVD-WXX9                         | 1         | 2%      |
| HP ZBook 15                              | 1         | 2%      |
| HP ProDesk 600 G1 SFF                    | 1         | 2%      |
| HP ProBook 4310s                         | 1         | 2%      |
| HP Pavilion Laptop 15-eg0xxx             | 1         | 2%      |
| HP G60                                   | 1         | 2%      |
| HP EliteBook 850 G3                      | 1         | 2%      |
| HP EliteBook 840 G3                      | 1         | 2%      |
| HP EliteBook 2560p                       | 1         | 2%      |
| HP 350 G1                                | 1         | 2%      |
| Google Eldrid                            | 1         | 2%      |
| Gigabyte B560M H                         | 1         | 2%      |
| Gateway ZX4931                           | 1         | 2%      |
| Digma EVE 11 C421Y ES1067EW              | 1         | 2%      |
| Dell OptiPlex 330                        | 1         | 2%      |
| Dell Inspiron 15 3511                    | 1         | 2%      |
| ASUS VivoBook_ASUSLaptop X515JA_R565JA   | 1         | 2%      |
| ASUS VivoBook_ASUSLaptop M1502IA_M1502IA | 1         | 2%      |
| ASRock X370 Pro4                         | 1         | 2%      |
| Apple Macmini5,1                         | 1         | 2%      |
| Apple MacBookPro9,2                      | 1         | 2%      |
| Apple MacBookPro8,1                      | 1         | 2%      |
| Apple MacBookPro6,2                      | 1         | 2%      |
| Apple MacBookPro5,5                      | 1         | 2%      |
| Apple iMac8,1                            | 1         | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 4         | 8%      |
| HP EliteBook          | 3         | 6%      |
| Dell OptiPlex         | 3         | 6%      |
| ASUS VivoBook         | 2         | 4%      |
| Apple MacBookAir6     | 2         | 4%      |
| Apple iMac12          | 2         | 4%      |
| Pegatron Pro          | 1         | 2%      |
| Packard Bell EasyNote | 1         | 2%      |
| Medion E15301         | 1         | 2%      |
| LG V320-M.BG33P1      | 1         | 2%      |
| Lenovo Yoga           | 1         | 2%      |
| Lenovo Legion         | 1         | 2%      |
| Lenovo IdeaPad        | 1         | 2%      |
| Lenovo G570           | 1         | 2%      |
| HUAWEI KLVD-WXX9      | 1         | 2%      |
| HP ZBook              | 1         | 2%      |
| HP ProDesk            | 1         | 2%      |
| HP ProBook            | 1         | 2%      |
| HP Pavilion           | 1         | 2%      |
| HP G60                | 1         | 2%      |
| HP 350                | 1         | 2%      |
| Google Eldrid         | 1         | 2%      |
| Gigabyte B560M        | 1         | 2%      |
| Gateway ZX4931        | 1         | 2%      |
| Digma EVE             | 1         | 2%      |
| Dell Inspiron         | 1         | 2%      |
| ASRock X370           | 1         | 2%      |
| Apple Macmini5        | 1         | 2%      |
| Apple MacBookPro9     | 1         | 2%      |
| Apple MacBookPro8     | 1         | 2%      |
| Apple MacBookPro6     | 1         | 2%      |
| Apple MacBookPro5     | 1         | 2%      |
| Apple iMac8           | 1         | 2%      |
| Apple iMac7           | 1         | 2%      |
| Apple iMac10          | 1         | 2%      |
| Acer TravelMate       | 1         | 2%      |
| Acer Swift            | 1         | 2%      |
| Acer Predator         | 1         | 2%      |
| Acer Aspire           | 1         | 2%      |
| Unknown               | 1         | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2012 | 7         | 14%     |
| 2011 | 7         | 14%     |
| 2021 | 6         | 12%     |
| 2013 | 5         | 10%     |
| 2018 | 4         | 8%      |
| 2009 | 4         | 8%      |
| 2010 | 3         | 6%      |
| 2023 | 2         | 4%      |
| 2017 | 2         | 4%      |
| 2016 | 2         | 4%      |
| 2008 | 2         | 4%      |
| 2007 | 2         | 4%      |
| 2020 | 1         | 2%      |
| 2019 | 1         | 2%      |
| 2015 | 1         | 2%      |
| 2014 | 1         | 2%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 32        | 64%     |
| Desktop     | 9         | 18%     |
| All in one  | 7         | 14%     |
| Convertible | 1         | 2%      |
| Mini pc     | 1         | 2%      |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 49        | 98%     |
| Enabled  | 1         | 2%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 49        | 98%     |
| Yes  | 1         | 2%      |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 16        | 32%     |
| 4.01-8.0   | 14        | 28%     |
| 16.01-24.0 | 11        | 22%     |
| 8.01-16.0  | 6         | 12%     |
| 32.01-64.0 | 1         | 2%      |
| 2.01-3.0   | 1         | 2%      |
| 1.01-2.0   | 1         | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 16        | 32%     |
| 1.01-2.0  | 16        | 32%     |
| 3.01-4.0  | 10        | 20%     |
| 8.01-16.0 | 5         | 10%     |
| 4.01-8.0  | 2         | 4%      |
| 0.51-1.0  | 1         | 2%      |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 34        | 68%     |
| 2      | 13        | 26%     |
| 3      | 3         | 6%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 29        | 58%     |
| Yes       | 21        | 42%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 78%     |
| No        | 11        | 22%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 90%     |
| No        | 5         | 10%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 76%     |
| No        | 12        | 24%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 9         | 18%     |
| Russia      | 5         | 10%     |
| UK          | 3         | 6%      |
| Indonesia   | 3         | 6%      |
| Germany     | 3         | 6%      |
| France      | 3         | 6%      |
| Switzerland | 2         | 4%      |
| Poland      | 2         | 4%      |
| Italy       | 2         | 4%      |
| Canada      | 2         | 4%      |
| Brazil      | 2         | 4%      |
| Venezuela   | 1         | 2%      |
| Ukraine     | 1         | 2%      |
| Sweden      | 1         | 2%      |
| Spain       | 1         | 2%      |
| Portugal    | 1         | 2%      |
| Peru        | 1         | 2%      |
| Pakistan    | 1         | 2%      |
| Netherlands | 1         | 2%      |
| India       | 1         | 2%      |
| Egypt       | 1         | 2%      |
| Colombia    | 1         | 2%      |
| Bulgaria    | 1         | 2%      |
| Belgium     | 1         | 2%      |
| Australia   | 1         | 2%      |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City               | Computers | Percent |
|--------------------|-----------|---------|
| Muralto            | 2         | 4%      |
| Moscow             | 2         | 4%      |
| Wouldham           | 1         | 2%      |
| Windsor            | 1         | 2%      |
| Wilsdruff          | 1         | 2%      |
| Warsaw             | 1         | 2%      |
| Spokane            | 1         | 2%      |
| Sorel-Tracy        | 1         | 2%      |
| Sheffield          | 1         | 2%      |
| Sacramento         | 1         | 2%      |
| Plovdiv            | 1         | 2%      |
| Padova             | 1         | 2%      |
| Obninsk            | 1         | 2%      |
| Novosibirsk        | 1         | 2%      |
| North Myrtle Beach | 1         | 2%      |
| Nantes             | 1         | 2%      |
| Naaldwijk          | 1         | 2%      |
| Murowana Goslina   | 1         | 2%      |
| Munich             | 1         | 2%      |
| Monza              | 1         | 2%      |
| Montería          | 1         | 2%      |
| Melbourne          | 1         | 2%      |
| Mariupol           | 1         | 2%      |
| Los Angeles        | 1         | 2%      |
| Lisbon             | 1         | 2%      |
| Lima               | 1         | 2%      |
| Lille              | 1         | 2%      |
| Kudus              | 1         | 2%      |
| Karachi            | 1         | 2%      |
| Jakarta            | 1         | 2%      |
| Imphal             | 1         | 2%      |
| Hultsfred          | 1         | 2%      |
| Houston            | 1         | 2%      |
| Heusden-Zolder     | 1         | 2%      |
| Hamburg            | 1         | 2%      |
| Fortaleza          | 1         | 2%      |
| Forest Grove       | 1         | 2%      |
| Elektrostal        | 1         | 2%      |
| Córdoba           | 1         | 2%      |
| Colorado Springs   | 1         | 2%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC                          | 7         | 7      | 10.14%  |
| Seagate                      | 7         | 7      | 10.14%  |
| Samsung Electronics          | 6         | 6      | 8.7%    |
| Kingston                     | 5         | 5      | 7.25%   |
| SanDisk                      | 4         | 4      | 5.8%    |
| Hitachi                      | 4         | 4      | 5.8%    |
| Toshiba                      | 3         | 3      | 4.35%   |
| VISIPRO                      | 2         | 2      | 2.9%    |
| Unknown                      | 2         | 2      | 2.9%    |
| SK hynix                     | 2         | 2      | 2.9%    |
| Micron Technology            | 2         | 2      | 2.9%    |
| Intel                        | 2         | 2      | 2.9%    |
| Crucial                      | 2         | 2      | 2.9%    |
| China                        | 2         | 2      | 2.9%    |
| Apple                        | 2         | 2      | 2.9%    |
| A-DATA Technology            | 2         | 2      | 2.9%    |
| Unknown                      | 2         | 2      | 2.9%    |
| USB30                        | 1         | 1      | 1.45%   |
| Union Memory (Shenzhen)      | 1         | 1      | 1.45%   |
| Transcend                    | 1         | 1      | 1.45%   |
| Shenzhen Longsys Electronics | 1         | 1      | 1.45%   |
| Realtek Semiconductor        | 1         | 1      | 1.45%   |
| PNY                          | 1         | 1      | 1.45%   |
| Phison                       | 1         | 1      | 1.45%   |
| KIOXIA                       | 1         | 1      | 1.45%   |
| Kingston Technology Company  | 1         | 1      | 1.45%   |
| KingDian                     | 1         | 1      | 1.45%   |
| HGST                         | 1         | 1      | 1.45%   |
| FORESEE                      | 1         | 1      | 1.45%   |
| Apacer                       | 1         | 1      | 1.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| SK hynix BC501 NVMe Solid State Drive 512GB           | 2         | 2.9%    |
| Apple SSD SD0128F 121GB                               | 2         | 2.9%    |
| Unknown                                               | 2         | 2.9%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 1         | 1.45%   |
| WDC WD800JD-75MSA3 80GB                               | 1         | 1.45%   |
| WDC WD6400AAKS-22A7B2 640GB                           | 1         | 1.45%   |
| WDC WD5000AAKS-00V6A0 500GB                           | 1         | 1.45%   |
| WDC WD3200AAJS-40RYA0 320GB                           | 1         | 1.45%   |
| WDC WD20EZRX-22D8PB0 2TB                              | 1         | 1.45%   |
| WDC WD Green 2.5 1000GB                               | 1         | 1.45%   |
| VISIPRO SSD 256GB                                     | 1         | 1.45%   |
| VISIPRO SDVPSA1910256 256GB SSD                       | 1         | 1.45%   |
| USB30 Disk 256GB                                      | 1         | 1.45%   |
| Unknown SD/MMC/MS PRO 1GB                             | 1         | 1.45%   |
| Unknown MMC Card  16GB                                | 1         | 1.45%   |
| Union Memory (Shenzhen) RPFTJ128PDD2EWX 128GB         | 1         | 1.45%   |
| Transcend TS128GSSD370S 128GB                         | 1         | 1.45%   |
| Toshiba MQ01ABD100 1TB                                | 1         | 1.45%   |
| Toshiba MK3263GSX 320GB                               | 1         | 1.45%   |
| Toshiba MK3256GSY 320GB                               | 1         | 1.45%   |
| Shenzhen Longsys FORESEE P900F128GH 128GB             | 1         | 1.45%   |
| Seagate ST96812A Disk 64GB                            | 1         | 1.45%   |
| Seagate ST500LM021-1KJ152 500GB                       | 1         | 1.45%   |
| Seagate ST4000DM004-2CV104 4TB                        | 1         | 1.45%   |
| Seagate ST3500418ASQ 500GB                            | 1         | 1.45%   |
| Seagate ST3500418AS 500GB                             | 1         | 1.45%   |
| Seagate ST1000LM035-1RK172 1TB                        | 1         | 1.45%   |
| Seagate ST1000DM010-2EP102 1TB                        | 1         | 1.45%   |
| SanDisk SSD U110 16GB                                 | 1         | 1.45%   |
| SanDisk SDSSDA-1T                                     | 1         | 1.45%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD                   | 1         | 1.45%   |
| SanDisk 3.2 Gen 1 496GB SSD                           | 1         | 1.45%   |
| Samsung SSD 980 500GB                                 | 1         | 1.45%   |
| Samsung SSD 980 1TB                                   | 1         | 1.45%   |
| Samsung SSD 870 EVO 1TB                               | 1         | 1.45%   |
| Samsung SSD 850 EVO 250GB                             | 1         | 1.45%   |
| Samsung SSD 840 EVO 250GB                             | 1         | 1.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 1         | 1.45%   |
| Realtek ADATA SX6000LNP 128GB                         | 1         | 1.45%   |
| PNY CS900 240GB SSD                                   | 1         | 1.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 7      | 33.33%  |
| WDC     | 5         | 5      | 23.81%  |
| Hitachi | 4         | 4      | 19.05%  |
| Toshiba | 3         | 3      | 14.29%  |
| Unknown | 1         | 1      | 4.76%   |
| HGST    | 1         | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 5         | 5      | 16.13%  |
| SanDisk             | 4         | 4      | 12.9%   |
| Samsung Electronics | 3         | 3      | 9.68%   |
| WDC                 | 2         | 2      | 6.45%   |
| VISIPRO             | 2         | 2      | 6.45%   |
| Crucial             | 2         | 2      | 6.45%   |
| China               | 2         | 2      | 6.45%   |
| Apple               | 2         | 2      | 6.45%   |
| A-DATA Technology   | 2         | 2      | 6.45%   |
| USB30               | 1         | 1      | 3.23%   |
| Transcend           | 1         | 1      | 3.23%   |
| PNY                 | 1         | 1      | 3.23%   |
| Phison              | 1         | 1      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| KingDian            | 1         | 1      | 3.23%   |
| Apacer              | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 30        | 31     | 46.15%  |
| HDD     | 19        | 21     | 29.23%  |
| NVMe    | 13        | 14     | 20%     |
| MMC     | 2         | 2      | 3.08%   |
| Unknown | 1         | 1      | 1.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 41        | 48     | 67.21%  |
| NVMe | 13        | 14     | 21.31%  |
| SAS  | 5         | 5      | 8.2%    |
| MMC  | 2         | 2      | 3.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 38     | 70.21%  |
| 0.51-1.0   | 11        | 11     | 23.4%   |
| 1.01-2.0   | 2         | 2      | 4.26%   |
| 3.01-4.0   | 1         | 1      | 2.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 21        | 42%     |
| 251-500    | 12        | 24%     |
| 501-1000   | 6         | 12%     |
| 51-100     | 5         | 10%     |
| 21-50      | 2         | 4%      |
| 2001-3000  | 2         | 4%      |
| 1001-2000  | 2         | 4%      |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 21        | 42%     |
| 21-50     | 17        | 34%     |
| 251-500   | 4         | 8%      |
| 101-250   | 3         | 6%      |
| 51-100    | 3         | 6%      |
| 1001-2000 | 1         | 2%      |
| 501-1000  | 1         | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HTS547564A9E384 640GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

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

![Drive Status](./All/images/pie_chart/drive_status.svg)

![Drive Status](./All/images/line_chart/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 44        | 59     | 81.48%  |
| Works    | 9         | 9      | 16.67%  |
| Malfunc  | 1         | 1      | 1.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 40        | 67.8%   |
| Samsung Electronics          | 3         | 5.08%   |
| AMD                          | 3         | 5.08%   |
| SK hynix                     | 2         | 3.39%   |
| Nvidia                       | 2         | 3.39%   |
| Marvell Technology Group     | 2         | 3.39%   |
| Union Memory (Shenzhen)      | 1         | 1.69%   |
| Shenzhen Longsys Electronics | 1         | 1.69%   |
| Realtek Semiconductor        | 1         | 1.69%   |
| Micron Technology            | 1         | 1.69%   |
| KIOXIA                       | 1         | 1.69%   |
| Kingston Technology Company  | 1         | 1.69%   |
| ASMedia Technology           | 1         | 1.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 7.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 7.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 6.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 4.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 4.62%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 4.62%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 3.08%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 3.08%   |
| Nvidia MCP79 AHCI Controller                                                   | 2         | 3.08%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 2         | 3.08%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2         | 3.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 3.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 3.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 3.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 3.08%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 NVMe SSD 128GB                          | 1         | 1.54%   |
| Shenzhen Longsys Non-Volatile memory controller                                | 1         | 1.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.54%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                              | 1         | 1.54%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 1         | 1.54%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 1         | 1.54%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 1.54%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.54%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.54%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 1.54%   |
| Intel SSD 660P Series                                                          | 1         | 1.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.54%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 1.54%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.54%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 1.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 1.54%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1         | 1.54%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 1.54%   |
| AMD X370 Series Chipset SATA Controller                                        | 1         | 1.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 42        | 67.74%  |
| NVMe | 13        | 20.97%  |
| IDE  | 4         | 6.45%   |
| RAID | 3         | 4.84%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 45        | 90%     |
| AMD    | 5         | 10%     |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 8%      |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 4%      |
| Intel Core i5-2400S CPU @ 2.50GHz           | 2         | 4%      |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2         | 4%      |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 2%      |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1         | 2%      |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 2%      |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 2%      |
| Intel Pentium CPU 6805 @ 1.10GHz            | 1         | 2%      |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 2%      |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 2%      |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 2%      |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 2%      |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 2%      |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 2%      |
| Intel Core i7 CPU L 620 @ 2.00GHz           | 1         | 2%      |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 2%      |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 2%      |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 2%      |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 2%      |
| Intel Core i5-4260U CPU @ 1.40GHz           | 1         | 2%      |
| Intel Core i5-4250U CPU @ 1.30GHz           | 1         | 2%      |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 2%      |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 2%      |
| Intel Core i5-2500S CPU @ 2.70GHz           | 1         | 2%      |
| Intel Core i5-2435M CPU @ 2.40GHz           | 1         | 2%      |
| Intel Core i5-2415M CPU @ 2.30GHz           | 1         | 2%      |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 2%      |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1         | 2%      |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 2%      |
| Intel Core i3-2377M CPU @ 1.50GHz           | 1         | 2%      |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz        | 1         | 2%      |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz        | 1         | 2%      |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 1         | 2%      |
| Intel Core 2 Duo CPU E8135 @ 2.40GHz        | 1         | 2%      |
| Intel Core 2 Duo CPU E7600 @ 3.06GHz        | 1         | 2%      |
| Intel Celeron N4020 CPU @ 1.10GHz           | 1         | 2%      |
| Intel Celeron CPU B800 @ 1.50GHz            | 1         | 2%      |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 1         | 2%      |
| AMD Ryzen 7 4800HS with Radeon Graphics     | 1         | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 18        | 36%     |
| Intel Core i7           | 7         | 14%     |
| Other                   | 5         | 10%     |
| Intel Core 2 Duo        | 5         | 10%     |
| Intel Pentium Dual-Core | 3         | 6%      |
| Intel Core i3           | 3         | 6%      |
| Intel Celeron           | 2         | 4%      |
| AMD Ryzen 7             | 2         | 4%      |
| AMD Ryzen 5             | 2         | 4%      |
| Intel Pentium Dual      | 1         | 2%      |
| Intel Pentium           | 1         | 2%      |
| AMD Ryzen 3             | 1         | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 29        | 58%     |
| 4      | 17        | 34%     |
| 8      | 2         | 4%      |
| 6      | 2         | 4%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 50        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 34        | 68%     |
| 1      | 16        | 32%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 50        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 70%     |
| 0x206a7    | 5         | 10%     |
| 0x906e9    | 1         | 2%      |
| 0x806c1    | 1         | 2%      |
| 0x706e5    | 1         | 2%      |
| 0x706a8    | 1         | 2%      |
| 0x6fd      | 1         | 2%      |
| 0x406e3    | 1         | 2%      |
| 0x306c3    | 1         | 2%      |
| 0x306a9    | 1         | 2%      |
| 0x10676    | 1         | 2%      |
| 0x08600106 | 1         | 2%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| SandyBridge   | 11        | 22%     |
| Penryn        | 7         | 14%     |
| Haswell       | 6         | 12%     |
| TigerLake     | 4         | 8%      |
| Skylake       | 4         | 8%      |
| KabyLake      | 3         | 6%      |
| IvyBridge     | 3         | 6%      |
| Zen 2         | 2         | 4%      |
| Westmere      | 2         | 4%      |
| Core          | 2         | 4%      |
| Unknown       | 2         | 4%      |
| Zen+          | 1         | 2%      |
| Zen           | 1         | 2%      |
| IceLake       | 1         | 2%      |
| Goldmont plus | 1         | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 38        | 63.33%  |
| AMD    | 12        | 20%     |
| Nvidia | 10        | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 10        | 16.67%  |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 4         | 6.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 3         | 5%      |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 5%      |
| Intel 3rd Gen Core processor Graphics Controller                              | 3         | 5%      |
| Intel Core Processor Integrated Graphics Controller                           | 2         | 3.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 2         | 3.33%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                        | 2         | 3.33%   |
| Nvidia TU117M [GeForce MX450]                                                 | 1         | 1.67%   |
| Nvidia MCP7A [GeForce 9400]                                                   | 1         | 1.67%   |
| Nvidia GT216M [GeForce GT 330M]                                               | 1         | 1.67%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 1.67%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 1.67%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 1.67%   |
| Nvidia GK208GLM [Quadro K610M]                                                | 1         | 1.67%   |
| Nvidia GK107 [GeForce GTX 650]                                                | 1         | 1.67%   |
| Nvidia G96C [GeForce GT 120]                                                  | 1         | 1.67%   |
| Nvidia C79 [GeForce 9400M]                                                    | 1         | 1.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.67%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                     | 1         | 1.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.67%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 1.67%   |
| Intel HD Graphics 630                                                         | 1         | 1.67%   |
| Intel HD Graphics 530                                                         | 1         | 1.67%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 1.67%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.67%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                        | 1         | 1.67%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 1         | 1.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.67%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                     | 1         | 1.67%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 1         | 1.67%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                             | 1         | 1.67%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                               | 1         | 1.67%   |
| AMD RV610/M74 [Mobility Radeon HD 2400 XT]                                    | 1         | 1.67%   |
| AMD Renoir                                                                    | 1         | 1.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 1         | 1.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 1.67%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                | 1         | 1.67%   |
| AMD Lucienne                                                                  | 1         | 1.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 29        | 58%     |
| 1 x AMD        | 10        | 20%     |
| 1 x Nvidia     | 5         | 10%     |
| Intel + Nvidia | 4         | 8%      |
| Intel + AMD    | 2         | 4%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 48        | 96%     |
| Proprietary | 2         | 4%      |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 88%     |
| 0.01-0.5   | 3         | 6%      |
| 0.51-1.0   | 2         | 4%      |
| 3.01-4.0   | 1         | 2%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Apple                   | 11        | 21.15%  |
| AU Optronics            | 8         | 15.38%  |
| LG Display              | 5         | 9.62%   |
| Chimei Innolux          | 5         | 9.62%   |
| Samsung Electronics     | 4         | 7.69%   |
| BOE                     | 4         | 7.69%   |
| Goldstar                | 3         | 5.77%   |
| NEC Computers           | 2         | 3.85%   |
| XCX                     | 1         | 1.92%   |
| ViewSonic               | 1         | 1.92%   |
| Sharp                   | 1         | 1.92%   |
| RGT                     | 1         | 1.92%   |
| RCA                     | 1         | 1.92%   |
| Lenovo                  | 1         | 1.92%   |
| Hewlett-Packard         | 1         | 1.92%   |
| Chi Mei Optoelectronics | 1         | 1.92%   |
| AOC                     | 1         | 1.92%   |
| Acer                    | 1         | 1.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                         | 2         | 3.77%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 2         | 3.77%   |
| Apple Color LCD APP9C6B 1680x1050 433x270mm 20.1-inch                    | 2         | 3.77%   |
| XCX LCD Monitor XCX0844 1366x768 256x144mm 11.6-inch                     | 1         | 1.89%   |
| ViewSonic VP201b VSC6911 1600x1200 408x306mm 20.1-inch                   | 1         | 1.89%   |
| Sharp HDMI SHP1048 1920x1080 820x460mm 37.0-inch                         | 1         | 1.89%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch      | 1         | 1.89%   |
| Samsung Electronics LF24T40 SAM703C 1920x1080 521x293mm 23.5-inch        | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch     | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 1.89%   |
| RGT LCD Monitor RGT1352 1920x1080 480x270mm 21.7-inch                    | 1         | 1.89%   |
| RCA RTR3261-B-CA RCA0B01 1920x1080 698x392mm 31.5-inch                   | 1         | 1.89%   |
| NEC Computers EA234WMi NEC691E 1920x1080 509x286mm 23.0-inch             | 1         | 1.89%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD06FF 1920x1080 344x194mm 15.5-inch             | 1         | 1.89%   |
| LG Display LCD Monitor LGD05F7 1920x1080 344x194mm 15.5-inch             | 1         | 1.89%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 1         | 1.89%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD01DA 1366x768 294x166mm 13.3-inch              | 1         | 1.89%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 1.89%   |
| Hewlett-Packard L2245w HWP26FB 1680x1050 473x296mm 22.0-inch             | 1         | 1.89%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                      | 1         | 1.89%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch                 | 1         | 1.89%   |
| Goldstar ULTRAGEAR GSM5C0A 1920x1080 600x340mm 27.2-inch                 | 1         | 1.89%   |
| Goldstar LG ULTRAWIDE GSM5BF7 2560x1080 670x280mm 28.6-inch              | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch         | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch         | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch         | 1         | 1.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO1721 1600x900 382x215mm 17.3-inch | 1         | 1.89%   |
| BOE LCD Monitor BOE09AE 1920x1080 309x174mm 14.0-inch                    | 1         | 1.89%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 1         | 1.89%   |
| BOE LCD Monitor BOE07AA 1366x768 344x194mm 15.5-inch                     | 1         | 1.89%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO4999 1920x1080 344x193mm 15.5-inch           | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch            | 1         | 1.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 23        | 45.1%   |
| 1366x768 (WXGA)    | 10        | 19.61%  |
| 1680x1050 (WSXGA+) | 4         | 7.84%   |
| 1440x900 (WXGA+)   | 4         | 7.84%   |
| 1280x800 (WXGA)    | 4         | 7.84%   |
| 2560x1080          | 2         | 3.92%   |
| 3840x2160 (4K)     | 1         | 1.96%   |
| 2160x1440          | 1         | 1.96%   |
| 1600x900 (HD+)     | 1         | 1.96%   |
| 1600x1200          | 1         | 1.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 14        | 26.42%  |
| 13      | 11        | 20.75%  |
| 21      | 6         | 11.32%  |
| 20      | 3         | 5.66%   |
| 14      | 3         | 5.66%   |
| 23      | 2         | 3.77%   |
| 22      | 2         | 3.77%   |
| 11      | 2         | 3.77%   |
| 60      | 1         | 1.89%   |
| 36      | 1         | 1.89%   |
| 34      | 1         | 1.89%   |
| 28      | 1         | 1.89%   |
| 27      | 1         | 1.89%   |
| 24      | 1         | 1.89%   |
| 19      | 1         | 1.89%   |
| 17      | 1         | 1.89%   |
| 12      | 1         | 1.89%   |
| Unknown | 1         | 1.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 19        | 35.85%  |
| 401-500     | 12        | 22.64%  |
| 201-300     | 12        | 22.64%  |
| 501-600     | 4         | 7.55%   |
| 701-800     | 2         | 3.77%   |
| 601-700     | 1         | 1.89%   |
| 351-400     | 1         | 1.89%   |
| 1001-1500   | 1         | 1.89%   |
| Unknown     | 1         | 1.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 34        | 66.67%  |
| 16/10   | 11        | 21.57%  |
| 3/2     | 2         | 3.92%   |
| 21/9    | 2         | 3.92%   |
| 4/3     | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 14        | 26.42%  |
| 81-90          | 11        | 20.75%  |
| 201-250        | 9         | 16.98%  |
| 151-200        | 6         | 11.32%  |
| 71-80          | 3         | 5.66%   |
| 51-60          | 2         | 3.77%   |
| More than 1000 | 1         | 1.89%   |
| 61-70          | 1         | 1.89%   |
| 351-500        | 1         | 1.89%   |
| 301-350        | 1         | 1.89%   |
| 251-300        | 1         | 1.89%   |
| 121-130        | 1         | 1.89%   |
| 501-1000       | 1         | 1.89%   |
| Unknown        | 1         | 1.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 19        | 36.54%  |
| 101-120 | 19        | 36.54%  |
| 51-100  | 11        | 21.15%  |
| 1-50    | 1         | 1.92%   |
| 161-240 | 1         | 1.92%   |
| Unknown | 1         | 1.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 45        | 90%     |
| 2     | 5         | 10%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 22        | 30.56%  |
| Realtek Semiconductor           | 18        | 25%     |
| Broadcom                        | 10        | 13.89%  |
| Qualcomm Atheros                | 7         | 9.72%   |
| Marvell Technology Group        | 3         | 4.17%   |
| Broadcom Limited                | 3         | 4.17%   |
| TP-Link                         | 2         | 2.78%   |
| Nvidia                          | 2         | 2.78%   |
| Samsung Electronics             | 1         | 1.39%   |
| Ralink Technology               | 1         | 1.39%   |
| Ralink                          | 1         | 1.39%   |
| Qualcomm Atheros Communications | 1         | 1.39%   |
| NetGear                         | 1         | 1.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 11.36%  |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 5.68%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 4.55%   |
| Intel Wireless 8260                                               | 3         | 3.41%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 3.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.41%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 3.41%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2         | 2.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 2.27%   |
| Nvidia MCP79 Ethernet                                             | 2         | 2.27%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 2.27%   |
| Intel Wireless 3165                                               | 2         | 2.27%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.27%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 2.27%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 2.27%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 2.27%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 2         | 2.27%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 2         | 2.27%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 1.14%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 1.14%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.14%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1         | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.14%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1         | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.14%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.14%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 1.14%   |
| Realtek 802.11ax WLAN Adapter                                     | 1         | 1.14%   |
| Realtek 802.11ac NIC                                              | 1         | 1.14%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 1.14%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.14%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 1.14%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 1.14%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.14%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.14%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]           | 1         | 1.14%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 38.3%   |
| Broadcom                        | 8         | 17.02%  |
| Qualcomm Atheros                | 7         | 14.89%  |
| Realtek Semiconductor           | 6         | 12.77%  |
| TP-Link                         | 2         | 4.26%   |
| Broadcom Limited                | 2         | 4.26%   |
| Ralink Technology               | 1         | 2.13%   |
| Ralink                          | 1         | 2.13%   |
| Qualcomm Atheros Communications | 1         | 2.13%   |
| NetGear                         | 1         | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 4         | 8.16%   |
| Intel Wireless 8260                                            | 3         | 6.12%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 6.12%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2         | 4.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 4.08%   |
| Intel Wireless 3165                                            | 2         | 4.08%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 4.08%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 4.08%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 4.08%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 2         | 4.08%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 2         | 4.08%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 2.04%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 2.04%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.04%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 2.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 2.04%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 2.04%   |
| Realtek 802.11ax WLAN Adapter                                  | 1         | 2.04%   |
| Realtek 802.11ac NIC                                           | 1         | 2.04%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 2.04%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 2.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 2.04%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 2.04%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 2.04%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 2.04%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]        | 1         | 2.04%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 2.04%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 1         | 2.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 2.04%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 2.04%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 1         | 2.04%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1         | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 12        | 30.77%  |
| Intel                    | 11        | 28.21%  |
| Broadcom                 | 7         | 17.95%  |
| Marvell Technology Group | 3         | 7.69%   |
| Qualcomm Atheros         | 2         | 5.13%   |
| Nvidia                   | 2         | 5.13%   |
| Samsung Electronics      | 1         | 2.56%   |
| Broadcom Limited         | 1         | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 25.64%  |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 12.82%  |
| Intel Ethernet Connection I217-LM                                 | 3         | 7.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 7.69%   |
| Nvidia MCP79 Ethernet                                             | 2         | 5.13%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 5.13%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 5.13%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 2.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.56%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 2.56%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.56%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.56%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1         | 2.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 2.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.56%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 1         | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 54.22%  |
| Ethernet | 38        | 45.78%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 61.54%  |
| Ethernet | 20        | 38.46%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 28        | 56%     |
| 1     | 21        | 42%     |
| 0     | 1         | 2%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 35        | 70%     |
| Yes  | 15        | 30%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 39.47%  |
| Apple                           | 12        | 31.58%  |
| IMC Networks                    | 2         | 5.26%   |
| Hewlett-Packard                 | 2         | 5.26%   |
| Realtek Semiconductor           | 1         | 2.63%   |
| Ralink                          | 1         | 2.63%   |
| Qualcomm Atheros Communications | 1         | 2.63%   |
| Lite-On Technology              | 1         | 2.63%   |
| Foxconn / Hon Hai               | 1         | 2.63%   |
| Broadcom                        | 1         | 2.63%   |
| Unknown                         | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 5         | 13.16%  |
| Intel Centrino Bluetooth Wireless Transceiver  | 4         | 10.53%  |
| Apple Bluetooth Host Controller                | 4         | 10.53%  |
| Intel AX201 Bluetooth                          | 3         | 7.89%   |
| Apple Built-in Bluetooth 2.0+EDR HCI           | 3         | 7.89%   |
| Apple Bluetooth USB Host Controller            | 3         | 7.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2         | 5.26%   |
| IMC Networks Bluetooth Radio                   | 2         | 5.26%   |
| HP Broadcom 2070 Bluetooth Combo               | 2         | 5.26%   |
| Apple Bluetooth HCI                            | 2         | 5.26%   |
| Realtek Bluetooth Radio                        | 1         | 2.63%   |
| Ralink RT3290 Bluetooth                        | 1         | 2.63%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 2.63%   |
| Lite-On Bluetooth Device                       | 1         | 2.63%   |
| Intel AX200 Bluetooth                          | 1         | 2.63%   |
| Foxconn / Hon Hai BCM20702A0                   | 1         | 2.63%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 2.63%   |
| Unknown                                        | 1         | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 43        | 70.49%  |
| Nvidia | 8         | 13.11%  |
| AMD    | 8         | 13.11%  |
| Sony   | 1         | 1.64%   |
| JMTek  | 1         | 1.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 14.08%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 5.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 5.63%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 5.63%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 4.23%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 4.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 4.23%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 4.23%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 2.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 2.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 2.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 2.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.82%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 2.82%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 2.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.82%   |
| Sony DualSense Wireless Controller                                         | 1         | 1.41%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.41%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 1.41%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.41%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 1.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.41%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.41%   |
| JMTek SSS Headphone Set                                                    | 1         | 1.41%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.41%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.41%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.41%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.41%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1         | 1.41%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 1.41%   |
| AMD Navi 10 HDMI Audio                                                     | 1         | 1.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 35.71%  |
| Micron Technology   | 3         | 21.43%  |
| Unknown (ABCD)      | 1         | 7.14%   |
| Unknown             | 1         | 7.14%   |
| SK hynix            | 1         | 7.14%   |
| Kingston            | 1         | 7.14%   |
| Elpida              | 1         | 7.14%   |
| Unknown             | 1         | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 7.14%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 1         | 7.14%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 7.14%   |
| Samsung RAM M471B5273EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 7.14%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 7.14%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 7.14%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 7.14%   |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3 1600MT/s              | 1         | 7.14%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 7.14%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 1         | 7.14%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 7.14%   |
| Kingston RAM Module 2GB DIMM DDR3 1333MT/s                       | 1         | 7.14%   |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                       | 1         | 7.14%   |
| Unknown                                                          | 1         | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 6         | 54.55%  |
| DDR4   | 4         | 36.36%  |
| LPDDR4 | 1         | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 9         | 81.82%  |
| DIMM   | 2         | 18.18%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size | Computers | Percent |
|------|-----------|---------|
| 8192 | 7         | 63.64%  |
| 4096 | 2         | 18.18%  |
| 2048 | 2         | 18.18%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 5         | 41.67%  |
| 3200  | 3         | 25%     |
| 2667  | 1         | 8.33%   |
| 2400  | 1         | 8.33%   |
| 1333  | 1         | 8.33%   |
| 800   | 1         | 8.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)

![Printer Vendor](./All/images/line_chart/printer_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 50%     |
| Hewlett-Packard     | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)

![Printer Model](./All/images/line_chart/printer_model.svg)

| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung C48x Series Color Laser Multifunction Printer | 1         | 50%     |
| HP LaserJet 1300                                      | 1         | 50%     |

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
| Apple                                  | 11        | 28.95%  |
| Chicony Electronics                    | 6         | 15.79%  |
| Cheng Uei Precision Industry (Foxlink) | 3         | 7.89%   |
| Sonix Technology                       | 2         | 5.26%   |
| Quanta                                 | 2         | 5.26%   |
| Lite-On Technology                     | 2         | 5.26%   |
| IMC Networks                           | 2         | 5.26%   |
| Bison Electronics                      | 2         | 5.26%   |
| Y Media                                | 1         | 2.63%   |
| Suyin                                  | 1         | 2.63%   |
| Sunplus Innovation Technology          | 1         | 2.63%   |
| Shine-optics                           | 1         | 2.63%   |
| Samsung Electronics                    | 1         | 2.63%   |
| Microdia                               | 1         | 2.63%   |
| Lenovo                                 | 1         | 2.63%   |
| Arkmicro Technologies                  | 1         | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Apple Built-in iSight                                           | 5         | 13.16%  |
| Chicony Integrated Camera                                       | 2         | 5.26%   |
| Bison Lenovo Integrated Webcam                                  | 2         | 5.26%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                 | 2         | 5.26%   |
| Apple FaceTime HD Camera (Built-in)                             | 2         | 5.26%   |
| Apple FaceTime HD Camera                                        | 2         | 5.26%   |
| Y Media USB Camera                                              | 1         | 2.63%   |
| Suyin 1.3M HD WebCam                                            | 1         | 2.63%   |
| Sunplus HP HD Webcam [Fixed]                                    | 1         | 2.63%   |
| Sonix USB 2.0 Camera                                            | 1         | 2.63%   |
| Sonix HP Webcam-101                                             | 1         | 2.63%   |
| Shine-optics USB2.0 HD UVC WebCam                               | 1         | 2.63%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 1         | 2.63%   |
| Quanta ov9734_techfront_camera                                  | 1         | 2.63%   |
| Quanta HP Wide Vision HD Camera                                 | 1         | 2.63%   |
| Microdia Integrated_Webcam_HD                                   | 1         | 2.63%   |
| Lite-On Integrated Camera                                       | 1         | 2.63%   |
| Lite-On HP HD Webcam                                            | 1         | 2.63%   |
| Lenovo Integrated Webcam                                        | 1         | 2.63%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 1         | 2.63%   |
| IMC Networks Integrated Camera                                  | 1         | 2.63%   |
| Chicony Integrated HD WebCam                                    | 1         | 2.63%   |
| Chicony HP HD Webcam                                            | 1         | 2.63%   |
| Chicony HD WebCam                                               | 1         | 2.63%   |
| Chicony CNF8243 Webcam                                          | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera             | 1         | 2.63%   |
| Arkmicro USB2.0 PC CAMERA                                       | 1         | 2.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 62.5%   |
| Shenzhen Goodix Technology | 1         | 12.5%   |
| LighTuning Technology      | 1         | 12.5%   |
| Elan Microelectronics      | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader  | 3         | 37.5%   |
| Validity Sensors VFS471 Fingerprint Reader  | 1         | 12.5%   |
| Validity Sensors Swipe Fingerprint Sensor   | 1         | 12.5%   |
| Shenzhen Goodix  Fingerprint Device         | 1         | 12.5%   |
| LighTuning EgisTec Touch Fingerprint Sensor | 1         | 12.5%   |
| Elan ELAN:ARM-M4                            | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./All/images/line_chart/chipcard_vendor.svg)

| Vendor  | Computers | Percent |
|---------|-----------|---------|
| OmniKey | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| OmniKey CardMan 3121 (HID Technologies) | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 33        | 66%     |
| 1     | 14        | 28%     |
| 2     | 3         | 6%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 8         | 40%     |
| Net/wireless          | 4         | 20%     |
| Multimedia controller | 4         | 20%     |
| Graphics card         | 2         | 10%     |
| Chipcard              | 1         | 5%      |
| Bluetooth             | 1         | 5%      |

