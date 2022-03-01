EndeavourOS Hardware Trends
---------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by EndeavourOS users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/EndeavourOS/Desktop/README.md) and [notebooks](/Dist/EndeavourOS/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

Period: Feb, 2022.

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

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| EndeavourOS Rolling | 33        | 89.19%  |
| EndeavourOS         | 4         | 10.81%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| EndeavourOS | 37        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.16.10-arch1-1       | 7         | 18.92%  |
| 5.16.8-arch1-1        | 5         | 13.51%  |
| 5.16.4-arch1-1        | 3         | 8.11%   |
| 5.15.18-1-lts         | 3         | 8.11%   |
| 5.16.7-arch1-1        | 2         | 5.41%   |
| 5.16.5-arch1-1        | 2         | 5.41%   |
| 5.17.0-rc4-1-mainline | 1         | 2.7%    |
| 5.16.9-arch1-1        | 1         | 2.7%    |
| 5.16.8-zen1-2-zen     | 1         | 2.7%    |
| 5.16.7-lqx1-1-lqx     | 1         | 2.7%    |
| 5.16.5-zen1-1.1-zen   | 1         | 2.7%    |
| 5.16.4-zen1-1-zen     | 1         | 2.7%    |
| 5.16.4-242-tkg-pds    | 1         | 2.7%    |
| 5.16.3-arch1-1        | 1         | 2.7%    |
| 5.16.1-arch1-g14-2    | 1         | 2.7%    |
| 5.15.8-arch1-1        | 1         | 2.7%    |
| 5.15.24-246-tkg-pds   | 1         | 2.7%    |
| 5.15.23-2-lts         | 1         | 2.7%    |
| 5.15.22-1-lts         | 1         | 2.7%    |
| 5.15.19-1-lts         | 1         | 2.7%    |
| 5.11.14-arch1-1       | 1         | 2.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.10 | 7         | 18.92%  |
| 5.16.8  | 6         | 16.22%  |
| 5.16.4  | 5         | 13.51%  |
| 5.16.7  | 3         | 8.11%   |
| 5.16.5  | 3         | 8.11%   |
| 5.15.18 | 3         | 8.11%   |
| 5.17.0  | 1         | 2.7%    |
| 5.16.9  | 1         | 2.7%    |
| 5.16.3  | 1         | 2.7%    |
| 5.16.1  | 1         | 2.7%    |
| 5.15.8  | 1         | 2.7%    |
| 5.15.24 | 1         | 2.7%    |
| 5.15.23 | 1         | 2.7%    |
| 5.15.22 | 1         | 2.7%    |
| 5.15.19 | 1         | 2.7%    |
| 5.11.14 | 1         | 2.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 27        | 72.97%  |
| 5.15    | 8         | 21.62%  |
| 5.17    | 1         | 2.7%    |
| 5.11    | 1         | 2.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 37        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| XFCE       | 12        | 32.43%  |
| KDE5       | 12        | 32.43%  |
| GNOME      | 8         | 21.62%  |
| X-Cinnamon | 1         | 2.7%    |
| MATE       | 1         | 2.7%    |
| LXDE       | 1         | 2.7%    |
| jwm        | 1         | 2.7%    |
| Cinnamon   | 1         | 2.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 30        | 81.08%  |
| Wayland | 5         | 13.51%  |
| Tty     | 2         | 5.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 17        | 45.95%  |
| SDDM    | 11        | 29.73%  |
| GDM     | 5         | 13.51%  |
| Unknown | 4         | 10.81%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 19        | 51.35%  |
| fr_FR | 3         | 8.11%   |
| en_GB | 3         | 8.11%   |
| en_CA | 2         | 5.41%   |
| de_AT | 2         | 5.41%   |
| pl_PL | 1         | 2.7%    |
| nl_BE | 1         | 2.7%    |
| it_IT | 1         | 2.7%    |
| en_PH | 1         | 2.7%    |
| en_NZ | 1         | 2.7%    |
| en_HK | 1         | 2.7%    |
| en_AU | 1         | 2.7%    |
| de_DE | 1         | 2.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 24        | 64.86%  |
| BIOS | 13        | 35.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 23        | 62.16%  |
| Btrfs   | 13        | 35.14%  |
| Overlay | 1         | 2.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 24        | 64.86%  |
| MBR     | 7         | 18.92%  |
| Unknown | 6         | 16.22%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 83.78%  |
| Yes       | 6         | 16.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 26        | 70.27%  |
| Yes       | 11        | 29.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 6         | 16.22%  |
| Hewlett-Packard     | 6         | 16.22%  |
| Dell                | 5         | 13.51%  |
| ASUSTek Computer    | 5         | 13.51%  |
| MSI                 | 3         | 8.11%   |
| Acer                | 3         | 8.11%   |
| HUAWEI              | 2         | 5.41%   |
| ASRock              | 2         | 5.41%   |
| ZOTAC               | 1         | 2.7%    |
| Radxa               | 1         | 2.7%    |
| Notebook            | 1         | 2.7%    |
| Gigabyte Technology | 1         | 2.7%    |
| Eluktronics         | 1         | 2.7%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| ASRock B450M Pro4                     | 2         | 5.41%   |
| ZOTAC ZBOXNANO-CI520NANO/CI540NANO    | 1         | 2.7%    |
| Radxa ROCK Pi X                       | 1         | 2.7%    |
| Notebook NH5x_7xDPx                   | 1         | 2.7%    |
| MSI MS-7C37                           | 1         | 2.7%    |
| MSI MS-7C02                           | 1         | 2.7%    |
| MSI MS-7798                           | 1         | 2.7%    |
| Lenovo ThinkPad T470 W10DG 20JNS0DB00 | 1         | 2.7%    |
| Lenovo ThinkPad T440p 20AWS0U500      | 1         | 2.7%    |
| Lenovo ThinkPad E550 20DF0030US       | 1         | 2.7%    |
| Lenovo ThinkBook 15 G2 ITL 20VE       | 1         | 2.7%    |
| Lenovo IdeaPad Z510 20287             | 1         | 2.7%    |
| Lenovo IdeaPad 3 15ITL6 82H8          | 1         | 2.7%    |
| HUAWEI MACH-WX9                       | 1         | 2.7%    |
| HUAWEI HLYL-WXX9                      | 1         | 2.7%    |
| HP Z230 Tower Workstation             | 1         | 2.7%    |
| HP Pavilion g6                        | 1         | 2.7%    |
| HP Pavilion dv7                       | 1         | 2.7%    |
| HP Pavilion Aero Laptop 13-be0xxx     | 1         | 2.7%    |
| HP Pavilion 10 TS                     | 1         | 2.7%    |
| HP 250 G7 Notebook PC                 | 1         | 2.7%    |
| Gigabyte B450 AORUS ELITE             | 1         | 2.7%    |
| Eluktronics Prometheus XVII           | 1         | 2.7%    |
| Dell XPS 8700                         | 1         | 2.7%    |
| Dell Latitude E6400                   | 1         | 2.7%    |
| Dell Latitude E4310                   | 1         | 2.7%    |
| Dell Latitude 3420                    | 1         | 2.7%    |
| Dell G3 3500                          | 1         | 2.7%    |
| ASUS UX490UA                          | 1         | 2.7%    |
| ASUS TUF GAMING X570-PRO              | 1         | 2.7%    |
| ASUS TUF GAMING X570-PLUS             | 1         | 2.7%    |
| ASUS ROG Zephyrus M16 GU603HR_GU603HR | 1         | 2.7%    |
| ASUS ROG Flow X13 GV301QH_GV301QH     | 1         | 2.7%    |
| Acer Spin SP314-54N                   | 1         | 2.7%    |
| Acer Aspire V5-471                    | 1         | 2.7%    |
| Acer Aspire E1-572G                   | 1         | 2.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| HP Pavilion              | 4         | 10.81%  |
| Lenovo ThinkPad          | 3         | 8.11%   |
| Dell Latitude            | 3         | 8.11%   |
| Lenovo IdeaPad           | 2         | 5.41%   |
| ASUS TUF                 | 2         | 5.41%   |
| ASUS ROG                 | 2         | 5.41%   |
| ASRock B450M             | 2         | 5.41%   |
| Acer Aspire              | 2         | 5.41%   |
| ZOTAC ZBOXNANO-CI520NANO | 1         | 2.7%    |
| Radxa ROCK               | 1         | 2.7%    |
| Notebook NH5x            | 1         | 2.7%    |
| MSI MS-7C37              | 1         | 2.7%    |
| MSI MS-7C02              | 1         | 2.7%    |
| MSI MS-7798              | 1         | 2.7%    |
| Lenovo ThinkBook         | 1         | 2.7%    |
| HUAWEI MACH-WX9          | 1         | 2.7%    |
| HUAWEI HLYL-WXX9         | 1         | 2.7%    |
| HP Z230                  | 1         | 2.7%    |
| HP 250                   | 1         | 2.7%    |
| Gigabyte B450            | 1         | 2.7%    |
| Eluktronics Prometheus   | 1         | 2.7%    |
| Dell XPS                 | 1         | 2.7%    |
| Dell G3                  | 1         | 2.7%    |
| ASUS UX490UA             | 1         | 2.7%    |
| Acer Spin                | 1         | 2.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 8         | 21.62%  |
| 2018 | 6         | 16.22%  |
| 2020 | 5         | 13.51%  |
| 2013 | 5         | 13.51%  |
| 2014 | 3         | 8.11%   |
| 2019 | 2         | 5.41%   |
| 2017 | 2         | 5.41%   |
| 2012 | 2         | 5.41%   |
| 2008 | 2         | 5.41%   |
| 2011 | 1         | 2.7%    |
| 2010 | 1         | 2.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 25        | 67.57%  |
| Desktop     | 10        | 27.03%  |
| Convertible | 1         | 2.7%    |
| Mini pc     | 1         | 2.7%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 37        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 37        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 10        | 27.03%  |
| 8.01-16.0   | 8         | 21.62%  |
| 4.01-8.0    | 6         | 16.22%  |
| 32.01-64.0  | 5         | 13.51%  |
| 3.01-4.0    | 4         | 10.81%  |
| 64.01-256.0 | 2         | 5.41%   |
| 24.01-32.0  | 1         | 2.7%    |
| 1.01-2.0    | 1         | 2.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 9         | 24.32%  |
| 3.01-4.0   | 8         | 21.62%  |
| 1.01-2.0   | 7         | 18.92%  |
| 4.01-8.0   | 6         | 16.22%  |
| 0.51-1.0   | 4         | 10.81%  |
| 8.01-16.0  | 2         | 5.41%   |
| 16.01-24.0 | 1         | 2.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 56.76%  |
| 2      | 8         | 21.62%  |
| 5      | 5         | 13.51%  |
| 3      | 2         | 5.41%   |
| 4      | 1         | 2.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 26        | 70.27%  |
| Yes       | 11        | 29.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 83.78%  |
| No        | 6         | 16.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 83.78%  |
| No        | 6         | 16.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 67.57%  |
| No        | 12        | 32.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 10        | 27.03%  |
| France      | 3         | 8.11%   |
| Canada      | 3         | 8.11%   |
| Turkey      | 2         | 5.41%   |
| Germany     | 2         | 5.41%   |
| Belgium     | 2         | 5.41%   |
| Austria     | 2         | 5.41%   |
| Ukraine     | 1         | 2.7%    |
| UK          | 1         | 2.7%    |
| Thailand    | 1         | 2.7%    |
| Spain       | 1         | 2.7%    |
| Poland      | 1         | 2.7%    |
| Philippines | 1         | 2.7%    |
| New Zealand | 1         | 2.7%    |
| Netherlands | 1         | 2.7%    |
| Italy       | 1         | 2.7%    |
| Hong Kong   | 1         | 2.7%    |
| Finland     | 1         | 2.7%    |
| Brazil      | 1         | 2.7%    |
| Australia   | 1         | 2.7%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Toms River           | 3         | 8.11%   |
| Innsbruck            | 2         | 5.41%   |
| Victoria             | 1         | 2.7%    |
| Tuen Mun             | 1         | 2.7%    |
| Toronto              | 1         | 2.7%    |
| Tarsus               | 1         | 2.7%    |
| Sydney               | 1         | 2.7%    |
| Sint-Amands          | 1         | 2.7%    |
| Schaafheim           | 1         | 2.7%    |
| Ringgold             | 1         | 2.7%    |
| Recife               | 1         | 2.7%    |
| Pipe Creek           | 1         | 2.7%    |
| Paris                | 1         | 2.7%    |
| Paladina             | 1         | 2.7%    |
| Orlando              | 1         | 2.7%    |
| Makati City          | 1         | 2.7%    |
| Madrid               | 1         | 2.7%    |
| Lyon                 | 1         | 2.7%    |
| Los Angeles          | 1         | 2.7%    |
| Katowice             | 1         | 2.7%    |
| Jumet                | 1         | 2.7%    |
| Jenks                | 1         | 2.7%    |
| Irpin                | 1         | 2.7%    |
| Hendon               | 1         | 2.7%    |
| Helsinki             | 1         | 2.7%    |
| Edmonton             | 1         | 2.7%    |
| Duisburg             | 1         | 2.7%    |
| Del Valle            | 1         | 2.7%    |
| Boulogne-Billancourt | 1         | 2.7%    |
| Bodrum               | 1         | 2.7%    |
| Bangkok              | 1         | 2.7%    |
| Austin               | 1         | 2.7%    |
| Auckland             | 1         | 2.7%    |
| Amsterdam            | 1         | 2.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 16     | 22.95%  |
| WDC                 | 10        | 13     | 16.39%  |
| Seagate             | 8         | 9      | 13.11%  |
| SanDisk             | 4         | 4      | 6.56%   |
| Toshiba             | 3         | 3      | 4.92%   |
| Kingston            | 3         | 5      | 4.92%   |
| Unknown             | 2         | 3      | 3.28%   |
| Micron Technology   | 2         | 2      | 3.28%   |
| Intel               | 2         | 2      | 3.28%   |
| Crucial             | 2         | 2      | 3.28%   |
| XPG                 | 1         | 1      | 1.64%   |
| SSSTC               | 1         | 1      | 1.64%   |
| SPCC                | 1         | 1      | 1.64%   |
| SK Hynix            | 1         | 1      | 1.64%   |
| PNY                 | 1         | 1      | 1.64%   |
| PLEXTOR             | 1         | 1      | 1.64%   |
| Phison              | 1         | 1      | 1.64%   |
| Mushkin             | 1         | 1      | 1.64%   |
| LITEON              | 1         | 1      | 1.64%   |
| Fujitsu             | 1         | 1      | 1.64%   |
| Corsair             | 1         | 1      | 1.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 2.94%   |
| Seagate ST2000DM006-2DM164 2TB       | 2         | 2.94%   |
| Seagate Expansion+ 2TB               | 2         | 2.94%   |
| Samsung SSD 970 EVO 500GB            | 2         | 2.94%   |
| Samsung SSD 860 EVO 500GB            | 2         | 2.94%   |
| XPG NVMe SSD Drive 2TB               | 1         | 1.47%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 1.47%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 1.47%   |
| WDC WD5000LPVT-22G33T0 500GB         | 1         | 1.47%   |
| WDC WD5000BEVT-60ZAT1 500GB          | 1         | 1.47%   |
| WDC WD20EARS-00MVWB0 2TB             | 1         | 1.47%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 1.47%   |
| WDC WD10EZRX-00L4HB0 1TB             | 1         | 1.47%   |
| WDC WD100EMAZ-00WJTA0 10TB           | 1         | 1.47%   |
| WDC PC SN530 SDBPTPZ-512G-1002 512GB | 1         | 1.47%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 1.47%   |
| Unknown SLD64G  64GB                 | 1         | 1.47%   |
| Unknown SD/MMC 16GB                  | 1         | 1.47%   |
| Unknown M.S./M.S.Pro/HG 16GB         | 1         | 1.47%   |
| Toshiba THNSNJ128GMCU 128GB SSD      | 1         | 1.47%   |
| Toshiba KBG40ZMT128G MEMORY 128GB    | 1         | 1.47%   |
| Toshiba DT01ACA300 3TB               | 1         | 1.47%   |
| SSSTC CL1-3D256-Q11 NVMe 256GB       | 1         | 1.47%   |
| SPCC M.2 PCIe SSD 256GB              | 1         | 1.47%   |
| SK Hynix BC511 NVMe 512GB            | 1         | 1.47%   |
| Seagate ST320LT012-1DG14C 320GB      | 1         | 1.47%   |
| Seagate ST3000DM007-1WY10G 3TB       | 1         | 1.47%   |
| Seagate ST2000LM015-2E8174 2TB       | 1         | 1.47%   |
| Seagate ST2000DX001-1CM164 2TB       | 1         | 1.47%   |
| Seagate ST2000DM001-1CH164 2TB       | 1         | 1.47%   |
| SanDisk X400 2.5 7MM 128GB SSD       | 1         | 1.47%   |
| SanDisk SDSSDA240G 240GB             | 1         | 1.47%   |
| SanDisk SD8SN8U256G1002 256GB SSD    | 1         | 1.47%   |
| Sandisk NVMe SSD Drive 2TB           | 1         | 1.47%   |
| Samsung SSD 980 500GB                | 1         | 1.47%   |
| Samsung SSD 970 EVO Plus 250GB       | 1         | 1.47%   |
| Samsung SSD 870 QVO 1TB              | 1         | 1.47%   |
| Samsung SSD 870 EVO 250GB            | 1         | 1.47%   |
| Samsung SSD 860 EVO 1TB              | 1         | 1.47%   |
| Samsung SSD 850 PRO 2TB              | 1         | 1.47%   |
| Samsung SSD 840 Series 250GB         | 1         | 1.47%   |
| Samsung NVMe SSD Drive 2TB           | 1         | 1.47%   |
| Samsung MZVL21T0HCLR-00B00 1TB       | 1         | 1.47%   |
| Samsung MZALQ512HBLU-00BL2 512GB     | 1         | 1.47%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD | 1         | 1.47%   |
| PNY CS1211 120GB SSD 754D117-551     | 1         | 1.47%   |
| PLEXTOR PX-1TM10PG 1TB               | 1         | 1.47%   |
| Phison NVMe SSD Drive 2TB            | 1         | 1.47%   |
| Mushkin MKNSSDCR480GB                | 1         | 1.47%   |
| Micron 5100_MTFDDAK960TCB 960GB SSD  | 1         | 1.47%   |
| Micron 1300_MTFDDAK1T0TDL 1TB SSD    | 1         | 1.47%   |
| LITEON CA3-8D512 512GB               | 1         | 1.47%   |
| Kingston SUV500240G 240GB SSD        | 1         | 1.47%   |
| Kingston SA400S37120G 120GB SSD      | 1         | 1.47%   |
| Kingston SA400M8120G 120GB SSD       | 1         | 1.47%   |
| Kingston NVMe SSD Drive 256GB        | 1         | 1.47%   |
| Kingston HyperX Fury 3D 240GB SSD    | 1         | 1.47%   |
| Intel SSDSC2KW256G8 256GB            | 1         | 1.47%   |
| Intel SSDPEKNW512G8H 512GB           | 1         | 1.47%   |
| Fujitsu MHZ2250BJ FFS G2 250GB       | 1         | 1.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 9      | 47.06%  |
| WDC     | 7         | 9      | 41.18%  |
| Toshiba | 1         | 1      | 5.88%   |
| Fujitsu | 1         | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 9      | 33.33%  |
| SanDisk             | 3         | 3      | 12.5%   |
| Kingston            | 3         | 4      | 12.5%   |
| Micron Technology   | 2         | 2      | 8.33%   |
| Crucial             | 2         | 2      | 8.33%   |
| WDC                 | 1         | 1      | 4.17%   |
| Toshiba             | 1         | 1      | 4.17%   |
| PNY                 | 1         | 1      | 4.17%   |
| Mushkin             | 1         | 1      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| Corsair             | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 19        | 26     | 36.54%  |
| NVMe    | 17        | 21     | 32.69%  |
| HDD     | 14        | 20     | 26.92%  |
| MMC     | 1         | 1      | 1.92%   |
| Unknown | 1         | 2      | 1.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 25        | 44     | 54.35%  |
| NVMe | 17        | 21     | 36.96%  |
| SAS  | 3         | 4      | 6.52%   |
| MMC  | 1         | 1      | 2.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 19        | 25     | 50%     |
| 1.01-2.0   | 8         | 10     | 21.05%  |
| 0.51-1.0   | 8         | 8      | 21.05%  |
| 2.01-3.0   | 2         | 2      | 5.26%   |
| 4.01-10.0  | 1         | 1      | 2.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 10        | 27.03%  |
| 251-500        | 8         | 21.62%  |
| 1001-2000      | 6         | 16.22%  |
| More than 3000 | 4         | 10.81%  |
| 501-1000       | 4         | 10.81%  |
| 2001-3000      | 2         | 5.41%   |
| Unknown        | 2         | 5.41%   |
| 51-100         | 1         | 2.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 10        | 27.03%  |
| 51-100         | 6         | 16.22%  |
| 21-50          | 5         | 13.51%  |
| 101-250        | 5         | 13.51%  |
| 251-500        | 3         | 8.11%   |
| 1001-2000      | 3         | 8.11%   |
| Unknown        | 2         | 5.41%   |
| More than 3000 | 1         | 2.7%    |
| 2001-3000      | 1         | 2.7%    |
| 501-1000       | 1         | 2.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD5000LPVT-22G33T0 500GB   | 1         | 1      | 25%     |
| SanDisk SDSSDA240G 240GB       | 1         | 1      | 25%     |
| Crucial CT1050MX300SSD1 1050GB | 1         | 1      | 25%     |
| Corsair Force LS SSD 120GB     | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 25%     |
| SanDisk | 1         | 1      | 25%     |
| Crucial | 1         | 1      | 25%     |
| Corsair | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 3         | 3      | 75%     |
| HDD  | 1         | 1      | 25%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)

![Failed Drives](./All/images/line_chart/drive_failed.svg)

| Model                  | Computers | Drives | Percent |
|------------------------|-----------|--------|---------|
| LITEON CA3-8D512 512GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)

![Failed Drive Vendor](./All/images/line_chart/drive_failed_vendor.svg)

| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| LITEON | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)

![Drive Status](./All/images/line_chart/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 27        | 47     | 64.29%  |
| Detected | 10        | 18     | 23.81%  |
| Malfunc  | 4         | 4      | 9.52%   |
| Failed   | 1         | 1      | 2.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 21        | 41.18%  |
| AMD                            | 9         | 17.65%  |
| Samsung Electronics            | 7         | 13.73%  |
| Sandisk                        | 4         | 7.84%   |
| Solid State Storage Technology | 2         | 3.92%   |
| Phison Electronics             | 2         | 3.92%   |
| SK Hynix                       | 1         | 1.96%   |
| Lite-On Technology             | 1         | 1.96%   |
| KIOXIA                         | 1         | 1.96%   |
| Kingston Technology Company    | 1         | 1.96%   |
| ASMedia Technology             | 1         | 1.96%   |
| ADATA Technology               | 1         | 1.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 10.91%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 7.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 7.27%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 7.27%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 3         | 5.45%   |
| Solid State Storage Non-Volatile memory controller                             | 2         | 3.64%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 3.64%   |
| Sandisk Non-Volatile memory controller                                         | 2         | 3.64%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 3.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 3.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 3.64%   |
| SK Hynix BC511                                                                 | 1         | 1.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.82%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.82%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.82%   |
| Lite-On Non-Volatile memory controller                                         | 1         | 1.82%   |
| KIOXIA Non-Volatile memory controller                                          | 1         | 1.82%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 1.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.82%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 1.82%   |
| Intel SSD 660P Series                                                          | 1         | 1.82%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                               | 1         | 1.82%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.82%   |
| Intel Comet Lake PCH-H RAID                                                    | 1         | 1.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 1.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.82%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 1.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.82%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.82%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.82%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 1.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 27        | 56.25%  |
| NVMe | 17        | 35.42%  |
| RAID | 3         | 6.25%   |
| IDE  | 1         | 2.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 24        | 64.86%  |
| AMD    | 13        | 35.14%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3         | 8.11%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2         | 5.41%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 2         | 5.41%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 2         | 5.41%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz         | 1         | 2.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 2.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 2.7%    |
| Intel Core i7-10870H CPU @ 2.20GHz          | 1         | 2.7%    |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 2.7%    |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 2.7%    |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 2.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz           | 1         | 2.7%    |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 2.7%    |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 2.7%    |
| Intel Core i5-1035G4 CPU @ 1.10GHz          | 1         | 2.7%    |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 2.7%    |
| Intel Core i3-4020Y CPU @ 1.50GHz           | 1         | 2.7%    |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz        | 1         | 2.7%    |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz        | 1         | 2.7%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 1         | 2.7%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 1         | 2.7%    |
| AMD Ryzen 9 5950X 16-Core Processor         | 1         | 2.7%    |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 1         | 2.7%    |
| AMD Ryzen 7 5800U with Radeon Graphics      | 1         | 2.7%    |
| AMD Ryzen 7 5800HS with Radeon Graphics     | 1         | 2.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics      | 1         | 2.7%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 1         | 2.7%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 1         | 2.7%    |
| AMD Ryzen 5 3600 6-Core Processor           | 1         | 2.7%    |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 1         | 2.7%    |
| AMD Athlon II P360 Dual-Core Processor      | 1         | 2.7%    |
| AMD A4-1200 APU with Radeon HD Graphics     | 1         | 2.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 8         | 21.62%  |
| Intel Core i5    | 7         | 18.92%  |
| AMD Ryzen 7      | 6         | 16.22%  |
| Other            | 4         | 10.81%  |
| AMD Ryzen 5      | 3         | 8.11%   |
| Intel Core 2 Duo | 2         | 5.41%   |
| AMD Ryzen 9      | 2         | 5.41%   |
| Intel Xeon       | 1         | 2.7%    |
| Intel Core i3    | 1         | 2.7%    |
| Intel Atom       | 1         | 2.7%    |
| AMD Athlon II    | 1         | 2.7%    |
| AMD A4           | 1         | 2.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 13        | 35.14%  |
| 2      | 11        | 29.73%  |
| 8      | 9         | 24.32%  |
| 6      | 3         | 8.11%   |
| 16     | 1         | 2.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 37        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 31        | 83.78%  |
| 1      | 6         | 16.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 37        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 21.62%  |
| 0x806c1    | 3         | 8.11%   |
| 0x306c3    | 3         | 8.11%   |
| 0x0a50000c | 3         | 8.11%   |
| 0x40651    | 2         | 5.41%   |
| 0x306a9    | 2         | 5.41%   |
| 0x08701021 | 2         | 5.41%   |
| 0xa0652    | 1         | 2.7%    |
| 0x806eb    | 1         | 2.7%    |
| 0x806ea    | 1         | 2.7%    |
| 0x806e9    | 1         | 2.7%    |
| 0x806d1    | 1         | 2.7%    |
| 0x406e3    | 1         | 2.7%    |
| 0x406c4    | 1         | 2.7%    |
| 0x306d4    | 1         | 2.7%    |
| 0x20655    | 1         | 2.7%    |
| 0x1067a    | 1         | 2.7%    |
| 0x0a201016 | 1         | 2.7%    |
| 0x08101016 | 1         | 2.7%    |
| 0x0700010f | 1         | 2.7%    |
| 0x010000c8 | 1         | 2.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Haswell    | 6         | 16.22%  |
| Zen 3      | 5         | 13.51%  |
| Zen 2      | 5         | 13.51%  |
| TigerLake  | 3         | 8.11%   |
| KabyLake   | 3         | 8.11%   |
| Penryn     | 2         | 5.41%   |
| IvyBridge  | 2         | 5.41%   |
| IceLake    | 2         | 5.41%   |
| CometLake  | 2         | 5.41%   |
| Zen        | 1         | 2.7%    |
| Westmere   | 1         | 2.7%    |
| Skylake    | 1         | 2.7%    |
| Silvermont | 1         | 2.7%    |
| K10        | 1         | 2.7%    |
| Jaguar     | 1         | 2.7%    |
| Broadwell  | 1         | 2.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 19        | 42.22%  |
| Nvidia | 14        | 31.11%  |
| AMD    | 12        | 26.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne                                                                              | 4         | 8.89%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 6.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 6.67%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 4.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 4.44%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 4.44%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 2.22%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 2.22%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 2.22%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 2.22%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 2.22%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 2.22%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 2.22%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 2.22%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 2.22%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1         | 2.22%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 1         | 2.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 2.22%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.22%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 2.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 2.22%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 1         | 2.22%   |
| Intel HD Graphics 620                                                                    | 1         | 2.22%   |
| Intel HD Graphics 5500                                                                   | 1         | 2.22%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.22%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 1         | 2.22%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.22%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 2.22%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 2.22%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 1         | 2.22%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 2.22%   |
| AMD Renoir                                                                               | 1         | 2.22%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1         | 2.22%   |
| AMD Kabini [Radeon HD 8180]                                                              | 1         | 2.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 35.14%  |
| 1 x AMD        | 9         | 24.32%  |
| 1 x Nvidia     | 7         | 18.92%  |
| Intel + Nvidia | 5         | 13.51%  |
| AMD + Nvidia   | 2         | 5.41%   |
| Intel + AMD    | 1         | 2.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 26        | 70.27%  |
| Proprietary | 11        | 29.73%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 59.46%  |
| 0.01-0.5   | 6         | 16.22%  |
| 7.01-8.0   | 4         | 10.81%  |
| 3.01-4.0   | 3         | 8.11%   |
| 8.01-16.0  | 1         | 2.7%    |
| 0.51-1.0   | 1         | 2.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 12.5%   |
| AU Optronics        | 6         | 12.5%   |
| Chimei Innolux      | 5         | 10.42%  |
| LG Display          | 4         | 8.33%   |
| BOE                 | 4         | 8.33%   |
| Acer                | 4         | 8.33%   |
| Dell                | 3         | 6.25%   |
| Iiyama              | 2         | 4.17%   |
| Goldstar            | 2         | 4.17%   |
| AOC                 | 2         | 4.17%   |
| Valve               | 1         | 2.08%   |
| Sharp               | 1         | 2.08%   |
| Philips             | 1         | 2.08%   |
| LG Philips          | 1         | 2.08%   |
| Lenovo              | 1         | 2.08%   |
| JDI                 | 1         | 2.08%   |
| HKC                 | 1         | 2.08%   |
| Gigabyte Technology | 1         | 2.08%   |
| CTV                 | 1         | 2.08%   |
| BenQ                | 1         | 2.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Valve Index HMD VLV91A8                                               | 1         | 2.08%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 2.08%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 886x498mm 40.0-inch | 1         | 2.08%   |
| Samsung Electronics C27F398 SAM0D45 1920x1080 598x336mm 27.0-inch     | 1         | 2.08%   |
| Samsung Electronics C24FG7x SAM0E43 1920x1080 532x304mm 24.1-inch     | 1         | 2.08%   |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch              | 1         | 2.08%   |
| LG Philips LCD Monitor LPL0140 1440x900 300x190mm 14.0-inch           | 1         | 2.08%   |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch          | 1         | 2.08%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 2.08%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 2.08%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch           | 1         | 2.08%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch              | 1         | 2.08%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 1         | 2.08%   |
| Iiyama PL2792Q IVM6637 2560x1440 597x336mm 27.0-inch                  | 1         | 2.08%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                  | 1         | 2.08%   |
| HKC SG27QC HKC274F 2560x1440 597x336mm 27.0-inch                      | 1         | 2.08%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1         | 2.08%   |
| Goldstar 32GK850G GSM7708 2560x1440 598x336mm 27.0-inch               | 1         | 2.08%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 598x336mm 27.0-inch        | 1         | 2.08%   |
| Dell S2721D DELA199 2560x1440 597x336mm 27.0-inch                     | 1         | 2.08%   |
| Dell P3421W DELA1A8 3440x1440 800x335mm 34.1-inch                     | 1         | 2.08%   |
| Dell 1704FPV DEL3015 1280x1024 338x270mm 17.0-inch                    | 1         | 2.08%   |
| CTV CTV CTV0030 1920x1080 708x398mm 32.0-inch                         | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch      | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN14E6 1366x768 309x173mm 13.9-inch       | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN1040 1366x768 222x125mm 10.0-inch       | 1         | 2.08%   |
| BOE LCD Monitor BOE0977 2560x1440 381x214mm 17.2-inch                 | 1         | 2.08%   |
| BOE LCD Monitor BOE084A 1920x1080 344x194mm 15.5-inch                 | 1         | 2.08%   |
| BOE LCD Monitor BOE081D 1920x1080 309x174mm 14.0-inch                 | 1         | 2.08%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 1         | 2.08%   |
| BenQ GL2780 BNQ78EC 1920x1080 598x336mm 27.0-inch                     | 1         | 2.08%   |
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch        | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO6496 1920x1200 286x178mm 13.3-inch        | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch         | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch         | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO383D 1920x1080 309x174mm 14.0-inch        | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO35EC 1366x768 340x190mm 15.3-inch         | 1         | 2.08%   |
| AOC AG241QG4 AOC2410 2560x1440 527x296mm 23.8-inch                    | 1         | 2.08%   |
| AOC 27B2 AOC2702 1920x1080 598x336mm 27.0-inch                        | 1         | 2.08%   |
| Acer XB270HU ACR0408 2560x1440 600x340mm 27.2-inch                    | 1         | 2.08%   |
| Acer SB220Q ACR06AB 1920x1080 476x268mm 21.5-inch                     | 1         | 2.08%   |
| Acer S200HQL ACR0365 1600x900 432x239mm 19.4-inch                     | 1         | 2.08%   |
| Acer S191HQL ACR021C 1366x768 410x230mm 18.5-inch                     | 1         | 2.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 19        | 39.58%  |
| 1366x768 (WXGA)   | 9         | 18.75%  |
| 2560x1440 (QHD)   | 8         | 16.67%  |
| 3840x2160 (4K)    | 2         | 4.17%   |
| 1920x1200 (WUXGA) | 2         | 4.17%   |
| 3440x1440         | 1         | 2.08%   |
| 3000x2000         | 1         | 2.08%   |
| 2560x1600         | 1         | 2.08%   |
| 2560x1080         | 1         | 2.08%   |
| 1600x900 (HD+)    | 1         | 2.08%   |
| 1440x900 (WXGA+)  | 1         | 2.08%   |
| 1280x1024 (SXGA)  | 1         | 2.08%   |
| Unknown           | 1         | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 9         | 19.15%  |
| 27      | 8         | 17.02%  |
| 13      | 5         | 10.64%  |
| 24      | 4         | 8.51%   |
| 14      | 4         | 8.51%   |
| 17      | 3         | 6.38%   |
| 34      | 2         | 4.26%   |
| 16      | 2         | 4.26%   |
| 47      | 1         | 2.13%   |
| 40      | 1         | 2.13%   |
| 32      | 1         | 2.13%   |
| 26      | 1         | 2.13%   |
| 23      | 1         | 2.13%   |
| 21      | 1         | 2.13%   |
| 19      | 1         | 2.13%   |
| 18      | 1         | 2.13%   |
| 10      | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 34.04%  |
| 501-600     | 14        | 29.79%  |
| 351-400     | 4         | 8.51%   |
| 201-300     | 4         | 8.51%   |
| 701-800     | 3         | 6.38%   |
| 401-500     | 3         | 6.38%   |
| 801-900     | 1         | 2.13%   |
| 1001-1500   | 1         | 2.13%   |
| Unknown     | 1         | 2.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 31        | 75.61%  |
| 16/10   | 4         | 9.76%   |
| 21/9    | 2         | 4.88%   |
| 5/4     | 1         | 2.44%   |
| 4/3     | 1         | 2.44%   |
| 3/2     | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 21.28%  |
| 301-350        | 9         | 19.15%  |
| 81-90          | 7         | 14.89%  |
| 201-250        | 4         | 8.51%   |
| 351-500        | 3         | 6.38%   |
| 71-80          | 2         | 4.26%   |
| 251-300        | 2         | 4.26%   |
| 141-150        | 2         | 4.26%   |
| 121-130        | 2         | 4.26%   |
| 501-1000       | 2         | 4.26%   |
| 41-50          | 1         | 2.13%   |
| 151-200        | 1         | 2.13%   |
| 111-120        | 1         | 2.13%   |
| Unknown        | 1         | 2.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 15        | 31.91%  |
| 51-100        | 14        | 29.79%  |
| 121-160       | 11        | 23.4%   |
| 161-240       | 4         | 8.51%   |
| More than 240 | 1         | 2.13%   |
| 1-50          | 1         | 2.13%   |
| Unknown       | 1         | 2.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 26        | 70.27%  |
| 2     | 10        | 27.03%  |
| 3     | 1         | 2.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 25        | 43.1%   |
| Intel                             | 25        | 43.1%   |
| Qualcomm Atheros                  | 3         | 5.17%   |
| Broadcom                          | 2         | 3.45%   |
| TP-Link                           | 1         | 1.72%   |
| Ericsson Business Mobile Networks | 1         | 1.72%   |
| ASIX Electronics                  | 1         | 1.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 26.15%  |
| Intel Wi-Fi 6 AX200                                               | 5         | 7.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 4.62%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 4.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 3.08%   |
| Intel Wireless 8260                                               | 2         | 3.08%   |
| Intel Wireless 7265                                               | 2         | 3.08%   |
| Intel Wireless 7260                                               | 2         | 3.08%   |
| Intel Wireless 3160                                               | 2         | 3.08%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.08%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1         | 1.54%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.54%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.54%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 1.54%   |
| Realtek 802.11ac NIC                                              | 1         | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 1.54%   |
| Intel Wireless-AC 9260                                            | 1         | 1.54%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.54%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 1.54%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 1.54%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.54%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.54%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.54%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.54%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.54%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.54%   |
| Ericsson Business Mobile Networks N5321 gw                        | 1         | 1.54%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.54%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.54%   |
| ASIX AX88772B Fast Ethernet Controller                            | 1         | 1.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 71.88%  |
| Realtek Semiconductor | 4         | 12.5%   |
| Qualcomm Atheros      | 3         | 9.38%   |
| TP-Link               | 1         | 3.13%   |
| Broadcom              | 1         | 3.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 5         | 15.63%  |
| Intel Wi-Fi 6 AX201                                            | 3         | 9.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 6.25%   |
| Intel Wireless 8260                                            | 2         | 6.25%   |
| Intel Wireless 7265                                            | 2         | 6.25%   |
| Intel Wireless 7260                                            | 2         | 6.25%   |
| Intel Wireless 3160                                            | 2         | 6.25%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1         | 3.13%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 3.13%   |
| Realtek 802.11ac NIC                                           | 1         | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 3.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 3.13%   |
| Intel Wireless-AC 9260                                         | 1         | 3.13%   |
| Intel Wireless 8265 / 8275                                     | 1         | 3.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 3.13%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 3.13%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 3.13%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 3.13%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 3.13%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 23        | 71.88%  |
| Intel                 | 7         | 21.88%  |
| Broadcom              | 1         | 3.13%   |
| ASIX Electronics      | 1         | 3.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 53.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 9.38%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 6.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 3.13%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 3.13%   |
| Intel Ethernet Controller I225-V                                  | 1         | 3.13%   |
| Intel Ethernet Connection I219-V                                  | 1         | 3.13%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 3.13%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 3.13%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 3.13%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 3.13%   |
| ASIX AX88772B Fast Ethernet Controller                            | 1         | 3.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 49.21%  |
| Ethernet | 31        | 49.21%  |
| Modem    | 1         | 1.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 60.98%  |
| Ethernet | 16        | 39.02%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 23        | 62.16%  |
| 1     | 14        | 37.84%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 26        | 70.27%  |
| Yes  | 11        | 29.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 76.92%  |
| Dell                  | 2         | 7.69%   |
| Realtek Semiconductor | 1         | 3.85%   |
| Lite-On Technology    | 1         | 3.85%   |
| Foxconn / Hon Hai     | 1         | 3.85%   |
| Broadcom              | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface       | 5         | 19.23%  |
| Intel AX201 Bluetooth                    | 5         | 19.23%  |
| Intel AX200 Bluetooth                    | 5         | 19.23%  |
| Intel Bluetooth Device                   | 4         | 15.38%  |
| Realtek Bluetooth Radio                  | 1         | 3.85%   |
| Lite-On Atheros AR3012 Bluetooth         | 1         | 3.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter | 1         | 3.85%   |
| Foxconn / Hon Hai Bluetooth Device       | 1         | 3.85%   |
| Dell Wireless 370 Bluetooth Mini-card    | 1         | 3.85%   |
| Dell DW375 Bluetooth Module              | 1         | 3.85%   |
| Broadcom BCM43142 Bluetooth 4.0          | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 35.94%  |
| AMD                   | 14        | 21.88%  |
| Nvidia                | 10        | 15.63%  |
| Logitech              | 3         | 4.69%   |
| XMOS                  | 2         | 3.13%   |
| Valve Software        | 2         | 3.13%   |
| C-Media Electronics   | 2         | 3.13%   |
| SteelSeries ApS       | 1         | 1.56%   |
| Sony                  | 1         | 1.56%   |
| Solid State System    | 1         | 1.56%   |
| Realtek Semiconductor | 1         | 1.56%   |
| Plantronics           | 1         | 1.56%   |
| JMTek                 | 1         | 1.56%   |
| Creative Technology   | 1         | 1.56%   |
| Corsair               | 1         | 1.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 6         | 7.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 4         | 5.19%   |
| AMD Starship/Matisse HD Audio Controller                            | 4         | 5.19%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 4         | 5.19%   |
| Nvidia GP107GL High Definition Audio Controller                     | 3         | 3.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 3         | 3.9%    |
| Intel Sunrise Point-LP HD Audio                                     | 3         | 3.9%    |
| Valve Software Valve VR Radio & HMD Mic                             | 2         | 2.6%    |
| Nvidia GA104 High Definition Audio Controller                       | 2         | 2.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 2         | 2.6%    |
| Intel Haswell-ULT HD Audio Controller                               | 2         | 2.6%    |
| Intel Comet Lake PCH cAVS                                           | 2         | 2.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                      | 2         | 2.6%    |
| Intel 8 Series HD Audio Controller                                  | 2         | 2.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 2         | 2.6%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 2         | 2.6%    |
| Unknown                                                             | 2         | 2.6%    |
| SteelSeries ApS SteelSeries Arctis 5                                | 1         | 1.3%    |
| Sony DualShock 4 [CUH-ZCT2x]                                        | 1         | 1.3%    |
| Solid State System FIFINE K669 Microphone                           | 1         | 1.3%    |
| Realtek Semiconductor Realtek USB2.0 Audio                          | 1         | 1.3%    |
| Plantronics Blackwire 3220 Series                                   | 1         | 1.3%    |
| Nvidia TU116 High Definition Audio Controller                       | 1         | 1.3%    |
| Nvidia TU104 HD Audio Controller                                    | 1         | 1.3%    |
| Nvidia GP104 High Definition Audio Controller                       | 1         | 1.3%    |
| Nvidia GA102 High Definition Audio Controller                       | 1         | 1.3%    |
| Nvidia Audio device                                                 | 1         | 1.3%    |
| Logitech [G533 Wireless Headset Dongle]                             | 1         | 1.3%    |
| Logitech Logitech USB Microphone                                    | 1         | 1.3%    |
| Logitech H390 headset with microphone                               | 1         | 1.3%    |
| JMTek USB PnP Audio Device                                          | 1         | 1.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller             | 1         | 1.3%    |
| Intel Tiger Lake-H HD Audio Controller                              | 1         | 1.3%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller           | 1         | 1.3%    |
| Intel Cannon Point-LP High Definition Audio Controller              | 1         | 1.3%    |
| Intel Broadwell-U Audio Controller                                  | 1         | 1.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio            | 1         | 1.3%    |
| Creative Technology SB X-Fi Surround 5.1                            | 1         | 1.3%    |
| Corsair VIRTUOSO SE USB Gaming Headset                              | 1         | 1.3%    |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                       | 1         | 1.3%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                   | 1         | 1.3%    |
| AMD SBx00 Azalia (Intel HDA)                                        | 1         | 1.3%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                    | 1         | 1.3%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                        | 1         | 1.3%    |
| AMD Navi 10 HDMI Audio                                              | 1         | 1.3%    |
| AMD Kabini HDMI/DP Audio                                            | 1         | 1.3%    |
| AMD FCH Azalia Controller                                           | 1         | 1.3%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 9         | 23.68%  |
| Kingston            | 8         | 21.05%  |
| SK Hynix            | 7         | 18.42%  |
| Samsung Electronics | 4         | 10.53%  |
| G.Skill             | 3         | 7.89%   |
| Team                | 2         | 5.26%   |
| Crucial             | 2         | 5.26%   |
| Unknown             | 1         | 2.63%   |
| Shenzhen Mic        | 1         | 2.63%   |
| Ramaxel Technology  | 1         | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                    | 1         | 2.5%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s             | 1         | 2.5%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s             | 1         | 2.5%    |
| SK Hynix RAM Module 4GB DIMM DDR3 1600MT/s                     | 1         | 2.5%    |
| SK Hynix RAM HMT451S6MFR8C-PB 4096MB SODIMM DDR3 1600MT/s      | 1         | 2.5%    |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s      | 1         | 2.5%    |
| SK Hynix RAM HMP351S6AFR8C-S6 4GB SODIMM DDR2 800MT/s          | 1         | 2.5%    |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s        | 1         | 2.5%    |
| SK Hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s        | 1         | 2.5%    |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s         | 1         | 2.5%    |
| Shenzhen Mic RAM MG8A3200C21WE-SA 16GB SODIMM DDR4 3200MT/s    | 1         | 2.5%    |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s       | 1         | 2.5%    |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s       | 1         | 2.5%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 2.5%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 1         | 2.5%    |
| Ramaxel RAM RMSA3260MB78HAF2400 8GB SODIMM DDR4 2400MT/s       | 1         | 2.5%    |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s        | 1         | 2.5%    |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 2.5%    |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s  | 1         | 2.5%    |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 1         | 2.5%    |
| Micron RAM 4KTF25664HZ-1G6E1 2GB SODIMM DDR3 1600MT/s          | 1         | 2.5%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s    | 1         | 2.5%    |
| Micron RAM 4ATF51264HZ-3G2E1 4GB SODIMM DDR4 3200MT/s          | 1         | 2.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 1         | 2.5%    |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s         | 1         | 2.5%    |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s          | 1         | 2.5%    |
| Kingston RAM K66GKY-MIN 8GB DIMM DDR3 1600MT/s                 | 1         | 2.5%    |
| Kingston RAM ACR16D3LS1NBG/4G 4GB SODIMM DDR3 1600MT/s         | 1         | 2.5%    |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 1600MT/s        | 1         | 2.5%    |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s        | 1         | 2.5%    |
| Kingston RAM 99U4342-017.A00G 4GB SODIMM DDR3 1600MT/s         | 1         | 2.5%    |
| Kingston RAM 9905471-074.A00LF 8GB DIMM DDR3 1600MT/s          | 1         | 2.5%    |
| Kingston RAM 9905428-043.A00LF 4GB SODIMM DDR3 1334MT/s        | 1         | 2.5%    |
| Kingston RAM 9905403-02X.B00LF 4GB DIMM DDR3 1600MT/s          | 1         | 2.5%    |
| G.Skill RAM F4-3200C16-8GTZRX 8GB DIMM DDR4 3200MT/s           | 1         | 2.5%    |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s          | 1         | 2.5%    |
| G.Skill RAM F4-2400C17-8GNT 8GB DIMM DDR4 2667MT/s             | 1         | 2.5%    |
| G.Skill RAM F4-2400C15-8GNT 8GB DIMM DDR4 2666MT/s             | 1         | 2.5%    |
| Crucial RAM CT8G4SFS8266.M8FD 8GB SODIMM DDR4 2667MT/s         | 1         | 2.5%    |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s     | 1         | 2.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 14        | 45.16%  |
| DDR3   | 13        | 41.94%  |
| LPDDR3 | 2         | 6.45%   |
| LPDDR4 | 1         | 3.23%   |
| DDR2   | 1         | 3.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 19        | 57.58%  |
| DIMM         | 10        | 30.3%   |
| Row Of Chips | 4         | 12.12%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 14        | 40%     |
| 4096  | 13        | 37.14%  |
| 16384 | 4         | 11.43%  |
| 32768 | 2         | 5.71%   |
| 2048  | 2         | 5.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 11        | 33.33%  |
| 3200  | 9         | 27.27%  |
| 2667  | 3         | 9.09%   |
| 2133  | 2         | 6.06%   |
| 1334  | 2         | 6.06%   |
| 4266  | 1         | 3.03%   |
| 3733  | 1         | 3.03%   |
| 3067  | 1         | 3.03%   |
| 2666  | 1         | 3.03%   |
| 2400  | 1         | 3.03%   |
| 800   | 1         | 3.03%   |

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
| IMC Networks                           | 6         | 20%     |
| Chicony Electronics                    | 4         | 13.33%  |
| Acer                                   | 3         | 10%     |
| Valve Software                         | 2         | 6.67%   |
| Sunplus Innovation Technology          | 2         | 6.67%   |
| Microdia                               | 2         | 6.67%   |
| Logitech                               | 2         | 6.67%   |
| Lite-On Technology                     | 2         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.67%   |
| Syntek                                 | 1         | 3.33%   |
| Primax Electronics                     | 1         | 3.33%   |
| Microsoft                              | 1         | 3.33%   |
| Google                                 | 1         | 3.33%   |
| DJKANA1BIF866I                         | 1         | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Valve Software 3D Camera                            | 2         | 6.67%   |
| Logitech HD Pro Webcam C920                         | 2         | 6.67%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 6.67%   |
| IMC Networks Integrated Camera                      | 2         | 6.67%   |
| Syntek Integrated Camera                            | 1         | 3.33%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 3.33%   |
| Sunplus HD WebCam                                   | 1         | 3.33%   |
| Primax Dell Laptop Integrated Webcam 2Mpix          | 1         | 3.33%   |
| Microsoft LifeCam VX-5000                           | 1         | 3.33%   |
| Microdia Integrated_Webcam_HD                       | 1         | 3.33%   |
| Microdia Integrated Webcam                          | 1         | 3.33%   |
| Lite-On Integrated Camera                           | 1         | 3.33%   |
| Lite-On HP Webcam                                   | 1         | 3.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 3.33%   |
| IMC Networks ov9734_azurewave_camera                | 1         | 3.33%   |
| Google Nexus/Pixel Device (MTP + debug)             | 1         | 3.33%   |
| DJKANA1BIF866I HP Wide Vision HD Camera             | 1         | 3.33%   |
| Chicony Lenovo Integrated Webcam                    | 1         | 3.33%   |
| Chicony HP Integrated Webcam                        | 1         | 3.33%   |
| Chicony HD Webcam                                   | 1         | 3.33%   |
| Chicony HD User Facing                              | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-50 | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 3.33%   |
| Acer Lenovo EasyCamera                              | 1         | 3.33%   |
| Acer HP Webcam                                      | 1         | 3.33%   |
| Acer BisonCam,NB Pro                                | 1         | 3.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 3         | 50%     |
| Validity Sensors           | 2         | 33.33%  |
| Elan Microelectronics      | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader          | 2         | 33.33%  |
| Validity Sensors VFS5011 Fingerprint Reader | 1         | 16.67%  |
| Validity Sensors Synaptics WBDI             | 1         | 16.67%  |
| Shenzhen Goodix  FingerPrint Device         | 1         | 16.67%  |
| Elan ELAN:Fingerprint                       | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./All/images/line_chart/chipcard_vendor.svg)

| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 66.67%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 22        | 59.46%  |
| 1     | 11        | 29.73%  |
| 2     | 3         | 8.11%   |
| 3     | 1         | 2.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 6         | 31.58%  |
| Chipcard              | 3         | 15.79%  |
| Net/wireless          | 2         | 10.53%  |
| Multimedia controller | 2         | 10.53%  |
| Graphics card         | 2         | 10.53%  |
| Camera                | 2         | 10.53%  |
| Sound                 | 1         | 5.26%   |
| Net/ethernet          | 1         | 5.26%   |

