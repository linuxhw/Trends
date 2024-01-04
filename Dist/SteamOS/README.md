SteamOS - Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/SteamOS/Desktop/README.md) and [notebooks](/Dist/SteamOS/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: Dec, 2023.

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

| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| SteamOS 3.5.7            | 81        | 77.88%  |
| SteamOS 4                | 6         | 5.77%   |
| SteamOS 3.5.5            | 4         | 3.85%   |
| SteamOS 3.6              | 2         | 1.92%   |
| SteamOS 3.5.11           | 2         | 1.92%   |
| SteamOS 3.5.10           | 2         | 1.92%   |
| SteamOS 1.051-prerelease | 2         | 1.92%   |
| SteamOS 3.5.8            | 1         | 0.96%   |
| SteamOS 3.5.12           | 1         | 0.96%   |
| SteamOS 3.4.8            | 1         | 0.96%   |
| SteamOS 3.4.11           | 1         | 0.96%   |
| SteamOS 3.4              | 1         | 0.96%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| SteamOS | 104       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 6.1.52-valve9-1-neptune-61  | 80        | 76.92%  |
| 6.1.52-valve10-1-neptune-61 | 7         | 6.73%   |
| 6.3.7-zen1-1-zen            | 5         | 4.81%   |
| 6.1.52-valve7-1-neptune-61  | 4         | 3.85%   |
| 6.4.12-zen1-1-zen           | 3         | 2.88%   |
| 6.1.52-valve12-1-neptune-61 | 1         | 0.96%   |
| 6.1.52-valve11-1-neptune-61 | 1         | 0.96%   |
| 5.13.0-valve37-1-neptune    | 1         | 0.96%   |
| 5.13.0-valve36-1-neptune    | 1         | 0.96%   |
| 5.13.0-valve21.3-1-neptune  | 1         | 0.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.52  | 93        | 89.42%  |
| 6.3.7   | 5         | 4.81%   |
| 6.4.12  | 3         | 2.88%   |
| 5.13.0  | 3         | 2.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 93        | 89.42%  |
| 6.3     | 5         | 4.81%   |
| 6.4     | 3         | 2.88%   |
| 5.13    | 3         | 2.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 104       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name      | Computers | Percent |
|-----------|-----------|---------|
| KDE5      | 103       | 99.04%  |
| gamescope | 1         | 0.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 104       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 104       | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 80        | 76.92%  |
| de_DE | 6         | 5.77%   |
| ru_RU | 4         | 3.85%   |
| C     | 3         | 2.88%   |
| pl_PL | 2         | 1.92%   |
| it_IT | 2         | 1.92%   |
| fr_FR | 2         | 1.92%   |
| cs_CZ | 2         | 1.92%   |
| zh_TW | 1         | 0.96%   |
| zh_CN | 1         | 0.96%   |
| pt_BR | 1         | 0.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 104       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 104       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 104       | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 104       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 104       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Valve               | 92        | 88.46%  |
| ASRock              | 3         | 2.88%   |
| Gigabyte Technology | 2         | 1.92%   |
| ONE-NETBOOK         | 1         | 0.96%   |
| MSI                 | 1         | 0.96%   |
| Hewlett-Packard     | 1         | 0.96%   |
| AZW                 | 1         | 0.96%   |
| ASUSTek Computer    | 1         | 0.96%   |
| Apple               | 1         | 0.96%   |
| Anbernic            | 1         | 0.96%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Valve Jupiter                      | 72        | 69.23%  |
| Valve Galileo                      | 20        | 19.23%  |
| ONE-NETBOOK ONEXPLAYER Mini Pro    | 1         | 0.96%   |
| MSI MS-7C91                        | 1         | 0.96%   |
| HP ProBook 455 G3                  | 1         | 0.96%   |
| Gigabyte B560M DS3H V2             | 1         | 0.96%   |
| Gigabyte B550I AORUS PRO AX        | 1         | 0.96%   |
| AZW SER                            | 1         | 0.96%   |
| ASUS M5A99FX PRO R2.0              | 1         | 0.96%   |
| ASRock X570 Phantom Gaming-ITX/TB3 | 1         | 0.96%   |
| ASRock B550M Steel Legend          | 1         | 0.96%   |
| ASRock AB350M-HDV                  | 1         | 0.96%   |
| Apple MacBookPro15,1               | 1         | 0.96%   |
| Anbernic Win600                    | 1         | 0.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Valve Jupiter          | 72        | 69.23%  |
| Valve Galileo          | 20        | 19.23%  |
| ONE-NETBOOK ONEXPLAYER | 1         | 0.96%   |
| MSI MS-7C91            | 1         | 0.96%   |
| HP ProBook             | 1         | 0.96%   |
| Gigabyte B560M         | 1         | 0.96%   |
| Gigabyte B550I         | 1         | 0.96%   |
| AZW SER                | 1         | 0.96%   |
| ASUS M5A99FX           | 1         | 0.96%   |
| ASRock X570            | 1         | 0.96%   |
| ASRock B550M           | 1         | 0.96%   |
| ASRock AB350M-HDV      | 1         | 0.96%   |
| Apple MacBookPro15     | 1         | 0.96%   |
| Anbernic Win600        | 1         | 0.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year    | Computers | Percent |
|---------|-----------|---------|
| 2023    | 87        | 83.65%  |
| 2022    | 11        | 10.58%  |
| 2012    | 2         | 1.92%   |
| 2021    | 1         | 0.96%   |
| 2017    | 1         | 0.96%   |
| 2016    | 1         | 0.96%   |
| Unknown | 1         | 0.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 98        | 94.23%  |
| Desktop  | 4         | 3.85%   |
| Tablet   | 1         | 0.96%   |
| Mini pc  | 1         | 0.96%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 104       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 104       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 94        | 90.38%  |
| 32.01-64.0 | 5         | 4.81%   |
| 4.01-8.0   | 2         | 1.92%   |
| 16.01-24.0 | 2         | 1.92%   |
| 24.01-32.0 | 1         | 0.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 42        | 40.38%  |
| 3.01-4.0  | 41        | 39.42%  |
| 2.01-3.0  | 16        | 15.38%  |
| 8.01-16.0 | 4         | 3.85%   |
| 1.01-2.0  | 1         | 0.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 2      | 63        | 60.58%  |
| 1      | 37        | 35.58%  |
| 5      | 2         | 1.92%   |
| 4      | 1         | 0.96%   |
| 3      | 1         | 0.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 104       | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 66        | 63.46%  |
| Yes       | 38        | 36.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 103       | 99.04%  |
| No        | 1         | 0.96%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 76.92%  |
| No        | 24        | 23.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 39        | 37.5%   |
| Russia      | 10        | 9.62%   |
| Germany     | 10        | 9.62%   |
| UK          | 7         | 6.73%   |
| Canada      | 6         | 5.77%   |
| Poland      | 5         | 4.81%   |
| Italy       | 3         | 2.88%   |
| Mexico      | 2         | 1.92%   |
| Israel      | 2         | 1.92%   |
| France      | 2         | 1.92%   |
| Czechia     | 2         | 1.92%   |
| Brazil      | 2         | 1.92%   |
| Taiwan      | 1         | 0.96%   |
| Switzerland | 1         | 0.96%   |
| Slovakia    | 1         | 0.96%   |
| Singapore   | 1         | 0.96%   |
| Philippines | 1         | 0.96%   |
| New Zealand | 1         | 0.96%   |
| Malaysia    | 1         | 0.96%   |
| Kazakhstan  | 1         | 0.96%   |
| Ireland     | 1         | 0.96%   |
| Hungary     | 1         | 0.96%   |
| Hong Kong   | 1         | 0.96%   |
| Austria     | 1         | 0.96%   |
| Australia   | 1         | 0.96%   |
| Argentina   | 1         | 0.96%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City               | Computers | Percent |
|--------------------|-----------|---------|
| Moscow             | 3         | 2.88%   |
| New York           | 2         | 1.92%   |
| Manchester         | 2         | 1.92%   |
| Los Angeles        | 2         | 1.92%   |
| Flushing           | 2         | 1.92%   |
| Zerbst             | 1         | 0.96%   |
| York               | 1         | 0.96%   |
| Willimantic        | 1         | 0.96%   |
| Wiehl              | 1         | 0.96%   |
| Warsaw             | 1         | 0.96%   |
| Volgograd          | 1         | 0.96%   |
| Vladivostok        | 1         | 0.96%   |
| Vienna             | 1         | 0.96%   |
| Vancouver          | 1         | 0.96%   |
| Tyumen             | 1         | 0.96%   |
| Tuscaloosa         | 1         | 0.96%   |
| Tseung Kwan O      | 1         | 0.96%   |
| Trieste            | 1         | 0.96%   |
| Toronto            | 1         | 0.96%   |
| Tlaxcala City      | 1         | 0.96%   |
| Teufen AR          | 1         | 0.96%   |
| Tacoma             | 1         | 0.96%   |
| Surgut             | 1         | 0.96%   |
| Springfield        | 1         | 0.96%   |
| South Holland      | 1         | 0.96%   |
| South Bend         | 1         | 0.96%   |
| Singapore          | 1         | 0.96%   |
| Seattle            | 1         | 0.96%   |
| Saint-Pascal       | 1         | 0.96%   |
| Saint-Omer-Capelle | 1         | 0.96%   |
| Sacramento         | 1         | 0.96%   |
| Rožňava          | 1         | 0.96%   |
| Rosh HaAyin        | 1         | 0.96%   |
| Rockland           | 1         | 0.96%   |
| Rishon LeTsiyyon   | 1         | 0.96%   |
| Raleigh            | 1         | 0.96%   |
| Quilmes            | 1         | 0.96%   |
| Protivin           | 1         | 0.96%   |
| Prince George      | 1         | 0.96%   |
| Poznan             | 1         | 0.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Unknown                     | 40        | 41     | 22.22%  |
| Phison Electronics          | 28        | 28     | 15.56%  |
| Samsung Electronics         | 21        | 21     | 11.67%  |
| Unknown                     | 20        | 20     | 11.11%  |
| Kingston Technology Company | 17        | 17     | 9.44%   |
| Sandisk                     | 12        | 12     | 6.67%   |
| O2 Micro                    | 9         | 9      | 5%      |
| Micron Technology           | 6         | 6      | 3.33%   |
| Seagate                     | 4         | 4      | 2.22%   |
| WDC                         | 3         | 3      | 1.67%   |
| Silicon Motion              | 2         | 2      | 1.11%   |
| Realtek Semiconductor       | 2         | 2      | 1.11%   |
| Phison                      | 2         | 2      | 1.11%   |
| Patriot                     | 2         | 2      | 1.11%   |
| Solid State Storage         | 1         | 1      | 0.56%   |
| Netac Mo                    | 1         | 1      | 0.56%   |
| KIOXIA                      | 1         | 1      | 0.56%   |
| Intel                       | 1         | 1      | 0.56%   |
| Hitachi                     | 1         | 1      | 0.56%   |
| GLOWAY                      | 1         | 1      | 0.56%   |
| Crucial                     | 1         | 1      | 0.56%   |
| China                       | 1         | 1      | 0.56%   |
| Biwin Storage Technology    | 1         | 1      | 0.56%   |
| ASMT                        | 1         | 1      | 0.56%   |
| Apple                       | 1         | 1      | 0.56%   |
| Apacer                      | 1         | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 20        | 11.05%  |
| Unknown MMC Card  512GB                               | 18        | 9.94%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 18        | 9.94%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB               | 17        | 9.39%   |
| Samsung MZ9LQ512HBLU-00BVL 512GB                      | 11        | 6.08%   |
| O2 Micro E2M2 64GB                                    | 9         | 4.97%   |
| Unknown MMC Card  256GB                               | 6         | 3.31%   |
| Unknown MMC Card  128GB                               | 5         | 2.76%   |
| Sandisk WD PC SN740 SDDPTQD-1T00 1024GB               | 4         | 2.21%   |
| Samsung MZ9LQ256HBJD-00BVL 256GB                      | 4         | 2.21%   |
| Unknown MMC Card  64GB                                | 3         | 1.66%   |
| Unknown MMC Card  32GB                                | 3         | 1.66%   |
| Sandisk WD PC SN740 SDDPTQE-2T00 2TB                  | 3         | 1.66%   |
| Phison Sabrent SB-2130-1TB                            | 3         | 1.66%   |
| Phison ESMP001TKB5C3-E19TS 1024GB                     | 3         | 1.66%   |
| Micron 2400_MTFDKBK1T0QFM 1024GB                      | 3         | 1.66%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 500GB | 2         | 1.1%    |
| Samsung MZ9L41T0HBLB-00AVL 1024GB                     | 2         | 1.1%    |
| Phison Sabrent Rocket Q4 2TB                          | 2         | 1.1%    |
| Micron 2400_MTFDKBK512QFM 512GB                       | 2         | 1.1%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 1         | 0.55%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 1         | 0.55%   |
| WDC WD1600HLFS-75G6U1 160GB                           | 1         | 0.55%   |
| Unknown NVMe SSD Drive 1024GB                         | 1         | 0.55%   |
| Unknown MMC Card  7GB                                 | 1         | 0.55%   |
| Unknown MMC Card  393GB                               | 1         | 0.55%   |
| Unknown MMC Card  30MB                                | 1         | 0.55%   |
| Unknown MMC Card  250GB                               | 1         | 0.55%   |
| Unknown MMC Card  1073GB                              | 1         | 0.55%   |
| Solid State Storage CL1-3D512-Q11 NVMe SSSTC 512GB    | 1         | 0.55%   |
| Seagate ST3500320AS 500GB                             | 1         | 0.55%   |
| Seagate ST2000LM007-1R8174 2TB                        | 1         | 0.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 1         | 0.55%   |
| Seagate ST1000DM010-2DM162 1TB                        | 1         | 0.55%   |
| Sandisk WD_BLACK SN850X 2000GB                        | 1         | 0.55%   |
| Sandisk WD_BLACK SN770M 1TB                           | 1         | 0.55%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                    | 1         | 0.55%   |
| Sandisk PC SN530 NVMe WDC 256GB                       | 1         | 0.55%   |
| SanDisk Extreme 55AE 1TB SSD                          | 1         | 0.55%   |
| Samsung SSD 980 1TB                                   | 1         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 50%     |
| WDC     | 2         | 2      | 25%     |
| Hitachi | 1         | 1      | 12.5%   |
| ASMT    | 1         | 1      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 22.22%  |
| Patriot             | 2         | 2      | 22.22%  |
| WDC                 | 1         | 1      | 11.11%  |
| SanDisk             | 1         | 1      | 11.11%  |
| Crucial             | 1         | 1      | 11.11%  |
| China               | 1         | 1      | 11.11%  |
| Apacer              | 1         | 1      | 11.11%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 101       | 102    | 57.71%  |
| MMC     | 60        | 60     | 34.29%  |
| SSD     | 7         | 9      | 4%      |
| HDD     | 5         | 8      | 2.86%   |
| Unknown | 2         | 2      | 1.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 101       | 102    | 58.38%  |
| MMC  | 60        | 60     | 34.68%  |
| SATA | 8         | 14     | 4.62%   |
| SAS  | 4         | 5      | 2.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 7         | 8      | 46.67%  |
| 0.01-0.5   | 5         | 6      | 33.33%  |
| 1.01-2.0   | 2         | 2      | 13.33%  |
| 3.01-4.0   | 1         | 1      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 35        | 33.65%  |
| 251-500        | 26        | 25%     |
| 1001-2000      | 24        | 23.08%  |
| 101-250        | 8         | 7.69%   |
| 2001-3000      | 4         | 3.85%   |
| More than 3000 | 3         | 2.88%   |
| 51-100         | 3         | 2.88%   |
| 1-20           | 1         | 0.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 27        | 25.96%  |
| 101-250        | 23        | 22.12%  |
| 501-1000       | 20        | 19.23%  |
| 1001-2000      | 11        | 10.58%  |
| 21-50          | 7         | 6.73%   |
| 51-100         | 7         | 6.73%   |
| 1-20           | 6         | 5.77%   |
| 2001-3000      | 2         | 1.92%   |
| More than 3000 | 1         | 0.96%   |

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
| Detected | 104       | 181    | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Phison Electronics             | 30        | 26.79%  |
| Samsung Electronics            | 19        | 16.96%  |
| Kingston Technology Company    | 17        | 15.18%  |
| Sandisk                        | 11        | 9.82%   |
| O2 Micro                       | 9         | 8.04%   |
| AMD                            | 8         | 7.14%   |
| Micron Technology              | 6         | 5.36%   |
| Silicon Motion                 | 2         | 1.79%   |
| Realtek Semiconductor          | 2         | 1.79%   |
| Intel                          | 2         | 1.79%   |
| Solidigm                       | 1         | 0.89%   |
| Solid State Storage Technology | 1         | 0.89%   |
| KIOXIA                         | 1         | 0.89%   |
| Biwin Storage Technology       | 1         | 0.89%   |
| ASMedia Technology             | 1         | 0.89%   |
| Apple                          | 1         | 0.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)               | 18        | 15.93%  |
| Samsung NVMe SSD Controller 980 (DRAM-less)                       | 17        | 15.04%  |
| Kingston Company OM3PDP3 NVMe SSD                                 | 17        | 15.04%  |
| O2 Micro FORESEE E2M2 NVMe SSD                                    | 9         | 7.96%   |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)               | 8         | 7.08%   |
| Sandisk PC SN740 NVMe SSD (DRAM-less)                             | 7         | 6.19%   |
| Micron 2400 NVMe SSD (DRAM-less)                                  | 5         | 4.42%   |
| AMD FCH SATA Controller [AHCI mode]                               | 4         | 3.54%   |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)               | 3         | 2.65%   |
| AMD 500 Series Chipset SATA Controller                            | 3         | 2.65%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers | 2         | 1.77%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                     | 2         | 1.77%   |
| Solidigm P41 Plus NVMe SSD (DRAM-less) [Echo Harbor]              | 1         | 0.88%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                    | 1         | 0.88%   |
| Sandisk WD Black SN850X NVMe SSD                                  | 1         | 0.88%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                         | 1         | 0.88%   |
| Sandisk Non-Volatile memory controller                            | 1         | 0.88%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                             | 1         | 0.88%   |
| Realtek RTS5772DL NVMe SSD Controller (DRAM-less)                 | 1         | 0.88%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                 | 1         | 0.88%   |
| Phison E8 PCIe3 NVMe Controller                                   | 1         | 0.88%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                       | 1         | 0.88%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                        | 1         | 0.88%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                  | 1         | 0.88%   |
| Intel 500 Series Chipset Family SATA AHCI Controller              | 1         | 0.88%   |
| Biwin Storage Non-Volatile memory controller                      | 1         | 0.88%   |
| ASMedia ASM1062 Serial ATA Controller                             | 1         | 0.88%   |
| Apple ANS2 NVMe Controller                                        | 1         | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                 | 1         | 0.88%   |
| AMD 300 Series Chipset SATA Controller                            | 1         | 0.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 101       | 91.82%  |
| SATA | 9         | 8.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 102       | 98.08%  |
| Intel  | 2         | 1.92%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Custom APU 0405                             | 92        | 88.46%  |
| Intel Core i9-9880H CPU @ 2.30GHz               | 1         | 0.96%   |
| Intel Core i5-10600KF CPU @ 4.10GHz             | 1         | 0.96%   |
| AMD Ryzen 7 6800U with Radeon Graphics          | 1         | 0.96%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 1         | 0.96%   |
| AMD Ryzen 7 5800H with Radeon Graphics          | 1         | 0.96%   |
| AMD Ryzen 7 5700X 8-Core Processor              | 1         | 0.96%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 1         | 0.96%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 1         | 0.96%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 1         | 0.96%   |
| AMD FX-6300 Six-Core Processor                  | 1         | 0.96%   |
| AMD Athlon Silver 3050e with Radeon Graphics    | 1         | 0.96%   |
| AMD A10-8700P Radeon R6, 10 Compute Cores 4C+6G | 1         | 0.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model         | Computers | Percent |
|---------------|-----------|---------|
| Other         | 92        | 88.46%  |
| AMD Ryzen 7   | 4         | 3.85%   |
| AMD Ryzen 5   | 3         | 2.88%   |
| Intel Core i9 | 1         | 0.96%   |
| Intel Core i5 | 1         | 0.96%   |
| AMD FX        | 1         | 0.96%   |
| AMD Athlon    | 1         | 0.96%   |
| AMD A10       | 1         | 0.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 92        | 88.46%  |
| 8      | 4         | 3.85%   |
| 6      | 4         | 3.85%   |
| 2      | 2         | 1.92%   |
| 5      | 1         | 0.96%   |
| 3      | 1         | 0.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 104       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 103       | 99.04%  |
| 1      | 1         | 0.96%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 104       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 104       | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 93        | 89.42%  |
| Zen 3      | 5         | 4.81%   |
| Zen+       | 1         | 0.96%   |
| Zen        | 1         | 0.96%   |
| Piledriver | 1         | 0.96%   |
| KabyLake   | 1         | 0.96%   |
| Excavator  | 1         | 0.96%   |
| CometLake  | 1         | 0.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 103       | 99.04%  |
| Nvidia | 1         | 0.96%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD VanGogh [AMD Custom GPU 0405]                                    | 72        | 68.57%  |
| AMD VGA compatible controller                                        | 20        | 19.05%  |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]        | 3         | 2.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]         | 2         | 1.9%    |
| Nvidia GM206 [GeForce GTX 960]                                       | 1         | 0.95%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                  | 1         | 0.95%   |
| AMD Rembrandt [Radeon 680M]                                          | 1         | 0.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 1         | 0.95%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                             | 1         | 0.95%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                       | 1         | 0.95%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]              | 1         | 0.95%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]  | 1         | 0.95%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| 1 x AMD    | 102       | 98.08%  |
| 2 x AMD    | 1         | 0.96%   |
| 1 x Nvidia | 1         | 0.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver | Computers | Percent |
|--------|-----------|---------|
| Free   | 104       | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 104       | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Valve                | 89        | 72.36%  |
| Goldstar             | 6         | 4.88%   |
| Samsung Electronics  | 4         | 3.25%   |
| Philips              | 2         | 1.63%   |
| AOC                  | 2         | 1.63%   |
| Acer                 | 2         | 1.63%   |
| Vizio                | 1         | 0.81%   |
| Unknown (XXX)        | 1         | 0.81%   |
| Sony                 | 1         | 0.81%   |
| SGT                  | 1         | 0.81%   |
| SBE                  | 1         | 0.81%   |
| RTK                  | 1         | 0.81%   |
| MStar                | 1         | 0.81%   |
| Hitachi              | 1         | 0.81%   |
| GreenWood            | 1         | 0.81%   |
| GDH                  | 1         | 0.81%   |
| DHD                  | 1         | 0.81%   |
| Dell                 | 1         | 0.81%   |
| Chimei Innolux       | 1         | 0.81%   |
| BOE                  | 1         | 0.81%   |
| BenQ                 | 1         | 0.81%   |
| ASUSTek Computer     | 1         | 0.81%   |
| Apple                | 1         | 0.81%   |
| Ancor Communications | 1         | 0.81%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 69        | 56.1%   |
| Valve ANX7530 U VLV3003 800x1280 100x160mm 7.4-inch                   | 18        | 14.63%  |
| Valve ANX7530 U VLV3004 800x1280 100x160mm 7.4-inch                   | 2         | 1.63%   |
| Vizio E24-C1 VIZ1005 1920x1080 521x293mm 23.5-inch                    | 1         | 0.81%   |
| Unknown (XXX) Beyond TV XXX2851 1920x1080 1209x680mm 54.6-inch        | 1         | 0.81%   |
| Sony TV *30 SNY7105 3840x2160 1660x934mm 75.0-inch                    | 1         | 0.81%   |
| SGT ASM-160QCC SGT161A 2560x1600 354x199mm 16.0-inch                  | 1         | 0.81%   |
| SBE 2511600 SBE2442 1920x1080 478x269mm 21.6-inch                     | 1         | 0.81%   |
| Samsung Electronics T24C550 SAM0BA5 1366x768 521x293mm 23.5-inch      | 1         | 0.81%   |
| Samsung Electronics SyncMaster SAM0202 1680x1050 474x296mm 22.0-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SAM04FD 1280x720                      | 1         | 0.81%   |
| RTK 7911D RTK2A3B 720x1280 720x1280mm 57.8-inch                       | 1         | 0.81%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 1         | 0.81%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 1         | 0.81%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                        | 1         | 0.81%   |
| Hitachi HDMI HEC0030 1920x1080 1150x650mm 52.0-inch                   | 1         | 0.81%   |
| GreenWood ARZOPA GWD0141 1920x1080 309x174mm 14.0-inch                | 1         | 0.81%   |
| Goldstar ULTRAGEAR GSM5C1E 1920x1080 700x390mm 31.5-inch              | 1         | 0.81%   |
| Goldstar ULTRAGEAR GSM5BB8 1920x1080 600x340mm 27.2-inch              | 1         | 0.81%   |
| Goldstar ULTRAGEAR GSM5BB2 1920x1080 527x296mm 23.8-inch              | 1         | 0.81%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 1         | 0.81%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                  | 1         | 0.81%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 1         | 0.81%   |
| GDH Digital TV GDH0032 1440x900 708x398mm 32.0-inch                   | 1         | 0.81%   |
| DHD DeckHD-1200p DHD3001 1200x1920 100x150mm 7.1-inch                 | 1         | 0.81%   |
| Dell U2722D DEL422F 2560x1440 597x336mm 27.0-inch                     | 1         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch       | 1         | 0.81%   |
| BOE LCD Monitor BOE0204 1200x1920                                     | 1         | 0.81%   |
| BenQ EX2710Q BNQ7F87 2560x1440 597x336mm 27.0-inch                    | 1         | 0.81%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 621x341mm 27.9-inch          | 1         | 0.81%   |
| Apple Color LCD APPA040 2880x1800 331x207mm 15.4-inch                 | 1         | 0.81%   |
| AOC Q32G3WG3R3 AOCB305 2560x1440 697x392mm 31.5-inch                  | 1         | 0.81%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 1         | 0.81%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 1         | 0.81%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                     | 1         | 0.81%   |
| Acer G257HU ACR0416 2560x1440 552x311mm 24.9-inch                     | 1         | 0.81%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 800x1280           | 89        | 72.36%  |
| 1920x1080 (FHD)    | 13        | 10.57%  |
| 3840x2160 (4K)     | 8         | 6.5%    |
| 2560x1440 (QHD)    | 5         | 4.07%   |
| 1366x768 (WXGA)    | 3         | 2.44%   |
| 1200x1920          | 2         | 1.63%   |
| 2880x1800          | 1         | 0.81%   |
| 2560x1600          | 1         | 0.81%   |
| 1680x1050 (WSXGA+) | 1         | 0.81%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 7       | 90        | 73.17%  |
| 27      | 5         | 4.07%   |
| 31      | 3         | 2.44%   |
| 24      | 3         | 2.44%   |
| 23      | 3         | 2.44%   |
| 84      | 2         | 1.63%   |
| 21      | 2         | 1.63%   |
| 15      | 2         | 1.63%   |
| 75      | 1         | 0.81%   |
| 72      | 1         | 0.81%   |
| 65      | 1         | 0.81%   |
| 57      | 1         | 0.81%   |
| 54      | 1         | 0.81%   |
| 52      | 1         | 0.81%   |
| 33      | 1         | 0.81%   |
| 32      | 1         | 0.81%   |
| 22      | 1         | 0.81%   |
| 19      | 1         | 0.81%   |
| 16      | 1         | 0.81%   |
| 14      | 1         | 0.81%   |
| Unknown | 1         | 0.81%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 1-100       | 90        | 73.17%  |
| 501-600     | 10        | 8.13%   |
| 601-700     | 4         | 3.25%   |
| 1501-2000   | 4         | 3.25%   |
| 701-800     | 3         | 2.44%   |
| 401-500     | 3         | 2.44%   |
| 301-350     | 3         | 2.44%   |
| 1001-1500   | 3         | 2.44%   |
| 351-400     | 2         | 1.63%   |
| Unknown     | 1         | 0.81%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 0.67  | 70        | 57.85%  |
| 16/9  | 26        | 21.49%  |
| 0.62  | 21        | 17.36%  |
| 16/10 | 2         | 1.65%   |
| 5/4   | 1         | 0.83%   |
| 0.56  | 1         | 0.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 1-40           | 90        | 73.17%  |
| More than 1000 | 8         | 6.5%    |
| 201-250        | 7         | 5.69%   |
| 351-500        | 5         | 4.07%   |
| 301-350        | 5         | 4.07%   |
| 101-110        | 3         | 2.44%   |
| 151-200        | 2         | 1.63%   |
| 81-90          | 1         | 0.81%   |
| 251-300        | 1         | 0.81%   |
| Unknown        | 1         | 0.81%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 161-240       | 90        | 74.38%  |
| 51-100        | 16        | 13.22%  |
| 101-120       | 7         | 5.79%   |
| 1-50          | 4         | 3.31%   |
| 121-160       | 2         | 1.65%   |
| More than 240 | 1         | 0.83%   |
| Unknown       | 1         | 0.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 82        | 78.85%  |
| 2     | 22        | 21.15%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 84        | 66.14%  |
| Qualcomm              | 20        | 15.75%  |
| ASIX Electronics      | 10        | 7.87%   |
| Intel                 | 6         | 4.72%   |
| Microsoft             | 2         | 1.57%   |
| MediaTek              | 2         | 1.57%   |
| Qualcomm Atheros      | 1         | 0.79%   |
| Broadcom Limited      | 1         | 0.79%   |
| Broadcom              | 1         | 0.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 71        | 48.97%  |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 20        | 13.79%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 17        | 11.72%  |
| ASIX AX88179 Gigabit Ethernet                                     | 10        | 6.9%    |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 3.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.07%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 1.38%   |
| Realtek 802.11ac NIC                                              | 2         | 1.38%   |
| Microsoft Wireless XBox Controller Dongle                         | 2         | 1.38%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2         | 1.38%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 1.38%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.38%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.69%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                  | 1         | 0.69%   |
| Intel Wireless 7265                                               | 1         | 0.69%   |
| Intel Wireless 3165                                               | 1         | 0.69%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.69%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                           | 1         | 0.69%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                | 1         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 72        | 68.57%  |
| Qualcomm              | 20        | 19.05%  |
| Intel                 | 6         | 5.71%   |
| Microsoft             | 2         | 1.9%    |
| MediaTek              | 2         | 1.9%    |
| Qualcomm Atheros      | 1         | 0.95%   |
| Broadcom Limited      | 1         | 0.95%   |
| Broadcom              | 1         | 0.95%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter | 71        | 66.36%  |
| Qualcomm QCNFA765 Wireless Network Adapter               | 20        | 18.69%  |
| Realtek 802.11ac NIC                                     | 2         | 1.87%   |
| Microsoft Wireless XBox Controller Dongle                | 2         | 1.87%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                  | 2         | 1.87%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                   | 2         | 1.87%   |
| Intel Wi-Fi 6 AX200                                      | 2         | 1.87%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                  | 1         | 0.93%   |
| Qualcomm Atheros AR922X Wireless Network Adapter         | 1         | 0.93%   |
| Intel Wireless 7265                                      | 1         | 0.93%   |
| Intel Wireless 3165                                      | 1         | 0.93%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                  | 1         | 0.93%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter       | 1         | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 27        | 71.05%  |
| ASIX Electronics      | 10        | 26.32%  |
| Intel                 | 1         | 2.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 17        | 44.74%  |
| ASIX AX88179 Gigabit Ethernet                                     | 10        | 26.32%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 13.16%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 7.89%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 5.26%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 103       | 73.05%  |
| Ethernet | 38        | 26.95%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 96        | 88.07%  |
| Ethernet | 13        | 11.93%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 97        | 93.27%  |
| 2     | 7         | 6.73%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 64        | 61.54%  |
| Yes  | 40        | 38.46%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| IMC Networks            | 71        | 88.75%  |
| Intel                   | 5         | 6.25%   |
| MediaTek                | 2         | 2.5%    |
| Cambridge Silicon Radio | 1         | 1.25%   |
| Broadcom                | 1         | 1.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks 802.11ac WLAN Adapter                  | 71        | 88.75%  |
| MediaTek Wireless_Device                            | 2         | 2.5%    |
| Intel Bluetooth wireless interface                  | 2         | 2.5%    |
| Intel AX200 Bluetooth                               | 2         | 2.5%    |
| Intel AX210 Bluetooth                               | 1         | 1.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.25%   |
| Broadcom BCM20702A0                                 | 1         | 1.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| AMD                   | 104       | 88.14%  |
| Sony                  | 3         | 2.54%   |
| Kingston Technology   | 2         | 1.69%   |
| Intel                 | 2         | 1.69%   |
| Yamaha                | 1         | 0.85%   |
| Teenage Engineering   | 1         | 0.85%   |
| Realtek Semiconductor | 1         | 0.85%   |
| Razer USA             | 1         | 0.85%   |
| Nvidia                | 1         | 0.85%   |
| Corsair               | 1         | 0.85%   |
| Apple                 | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| AMD Rembrandt Radeon High Definition Audio Controller        | 93        | 72.66%  |
| AMD Navi 21/23 HDMI/DP Audio Controller                      | 4         | 3.13%   |
| AMD Family 17h/19h HD Audio Controller                       | 4         | 3.13%   |
| AMD Starship/Matisse HD Audio Controller                     | 3         | 2.34%   |
| Sony DualSense wireless controller (PS5)                     | 2         | 1.56%   |
| AMD Renoir Radeon High Definition Audio Controller           | 2         | 1.56%   |
| Yamaha AG06MK2                                               | 1         | 0.78%   |
| Teenage Engineering OP-1                                     | 1         | 0.78%   |
| Sony DualShock 4 [CUH-ZCT2x]                                 | 1         | 0.78%   |
| Realtek Semiconductor USB Audio                              | 1         | 0.78%   |
| Razer USA RZ19-0229 Gaming Microphone                        | 1         | 0.78%   |
| Nvidia GM206 High Definition Audio Controller                | 1         | 0.78%   |
| Kingston Technology HyperX Cloud Stinger Core Wireless DTS   | 1         | 0.78%   |
| Kingston Technology HyperX 7.1 Audio                         | 1         | 0.78%   |
| Intel USB PnP Sound Device                                   | 1         | 0.78%   |
| Intel Smart Sound Technology (SST) Audio Controller          | 1         | 0.78%   |
| Corsair Corsair VOID Surround USB Sound Adapter              | 1         | 0.78%   |
| Apple Audio Device                                           | 1         | 0.78%   |
| AMD SBx00 Azalia (Intel HDA)                                 | 1         | 0.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller          | 1         | 0.78%   |
| AMD Navi 31 HDMI/DP Audio                                    | 1         | 0.78%   |
| AMD Kabini HDMI/DP Audio                                     | 1         | 0.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller          | 1         | 0.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller             | 1         | 0.78%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]   | 1         | 0.78%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X] | 1         | 0.78%   |

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

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)

![Printer Vendor](./All/images/line_chart/printer_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 50%     |
| Canon               | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)

![Printer Model](./All/images/line_chart/printer_model.svg)

| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| Samsung M2020 Series      | 1         | 50%     |
| Canon PIXMA MG3600 Series | 1         | 50%     |

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
| Microsoft                              | 1         | 33.33%  |
| Generalplus Technology                 | 1         | 33.33%  |
| Cheng Uei Precision Industry (Foxlink) | 1         | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microsoft LifeCam HD-3000                           | 1         | 33.33%  |
| Generalplus GENERAL WEBCAM                          | 1         | 33.33%  |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 33.33%  |

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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 101       | 97.12%  |
| 1     | 2         | 1.92%   |
| 2     | 1         | 0.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type         | Computers | Percent |
|--------------|-----------|---------|
| Net/wireless | 3         | 75%     |
| Sound        | 1         | 25%     |

