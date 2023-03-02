openSUSE - Hardware Trends
--------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/openSUSE/Desktop/README.md) and [notebooks](/Dist/openSUSE/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: Feb, 2023.

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

| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| openSUSE Tumbleweed-XXXXXXXX | 54        | 79.41%  |
| openSUSE Leap-15.4           | 7         | 10.29%  |
| openSUSE Microos-XXXXXXXX    | 5         | 7.35%   |
| openSUSE Leap-15.5           | 1         | 1.47%   |
| openSUSE Leap-15.3           | 1         | 1.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| openSUSE | 68        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 6.1.10-1-default             | 21        | 30.88%  |
| 6.1.12-1-default             | 19        | 27.94%  |
| 6.1.8-1-default              | 16        | 23.53%  |
| 5.14.21-150400.24.41-default | 6         | 8.82%   |
| 6.1.10-5-default             | 1         | 1.47%   |
| 6.1.10-1-vanilla             | 1         | 1.47%   |
| 6.1.1-1-default              | 1         | 1.47%   |
| 5.3.18-150300.59.106-default | 1         | 1.47%   |
| 5.14.21-150500.37-default    | 1         | 1.47%   |
| 5.14.21-150400.24.46-default | 1         | 1.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.10  | 23        | 33.82%  |
| 6.1.12  | 19        | 27.94%  |
| 6.1.8   | 16        | 23.53%  |
| 5.14.21 | 8         | 11.76%  |
| 6.1.1   | 1         | 1.47%   |
| 5.3.18  | 1         | 1.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 59        | 86.76%  |
| 5.14    | 8         | 11.76%  |
| 5.3     | 1         | 1.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 68        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| KDE5    | 48        | 70.59%  |
| GNOME   | 9         | 13.24%  |
| XFCE    | 6         | 8.82%   |
| Unknown | 2         | 2.94%   |
| sway    | 1         | 1.47%   |
| LXQt    | 1         | 1.47%   |
| KDE     | 1         | 1.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 53        | 77.94%  |
| Wayland | 14        | 20.59%  |
| Tty     | 1         | 1.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 41        | 60.29%  |
| SDDM    | 16        | 23.53%  |
| LightDM | 10        | 14.71%  |
| XDM     | 1         | 1.47%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 30        | 44.12%  |
| de_DE | 14        | 20.59%  |
| POSIX | 4         | 5.88%   |
| en_GB | 4         | 5.88%   |
| pt_BR | 3         | 4.41%   |
| pl_PL | 3         | 4.41%   |
| es_ES | 3         | 4.41%   |
| nl_NL | 2         | 2.94%   |
| ro_RO | 1         | 1.47%   |
| it_IT | 1         | 1.47%   |
| fr_FR | 1         | 1.47%   |
| en_DE | 1         | 1.47%   |
| bg_BG | 1         | 1.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 46        | 67.65%  |
| BIOS | 22        | 32.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 53        | 77.94%  |
| Ext4    | 11        | 16.18%  |
| Xfs     | 2         | 2.94%   |
| Overlay | 1         | 1.47%   |
| Ext3    | 1         | 1.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 38        | 55.88%  |
| GPT     | 26        | 38.24%  |
| MBR     | 4         | 5.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 62        | 91.18%  |
| Yes       | 6         | 8.82%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 55        | 80.88%  |
| Yes       | 13        | 19.12%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 17        | 25%     |
| Hewlett-Packard     | 11        | 16.18%  |
| Lenovo              | 9         | 13.24%  |
| Dell                | 8         | 11.76%  |
| ASRock              | 3         | 4.41%   |
| Acer                | 3         | 4.41%   |
| MSI                 | 2         | 2.94%   |
| Unknown             | 2         | 2.94%   |
| TUXEDO              | 1         | 1.47%   |
| Toshiba             | 1         | 1.47%   |
| Sun Microsystems    | 1         | 1.47%   |
| SK hynix            | 1         | 1.47%   |
| Schenker            | 1         | 1.47%   |
| Samsung Electronics | 1         | 1.47%   |
| Medion              | 1         | 1.47%   |
| Inventec            | 1         | 1.47%   |
| HUAWEI              | 1         | 1.47%   |
| Google              | 1         | 1.47%   |
| Gigabyte Technology | 1         | 1.47%   |
| AXDIA International | 1         | 1.47%   |
| Apple               | 1         | 1.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 2         | 2.94%   |
| TUXEDO InfinityBook S 15/17 Gen7      | 1         | 1.47%   |
| Toshiba PORTEGE Z830                  | 1         | 1.47%   |
| Sun Microsystems Ultra 24             | 1         | 1.47%   |
| SK hynix HyBook                       | 1         | 1.47%   |
| Schenker VIA 15                       | 1         | 1.47%   |
| Samsung 550XDA                        | 1         | 1.47%   |
| MSI MS-7B61                           | 1         | 1.47%   |
| MSI MS-7522                           | 1         | 1.47%   |
| Medion P6624                          | 1         | 1.47%   |
| Lenovo ThinkPad W510 4391W3V          | 1         | 1.47%   |
| Lenovo ThinkPad T440s 20ARS2V900      | 1         | 1.47%   |
| Lenovo ThinkPad T14 Gen 2i 20W1S34Y00 | 1         | 1.47%   |
| Lenovo ThinkPad P50 20EN001SUS        | 1         | 1.47%   |
| Lenovo Legion 5 Pro 16ARH7H 82RG      | 1         | 1.47%   |
| Lenovo IdeaPad Y900-17ISK 80Q1        | 1         | 1.47%   |
| Lenovo IdeaPad S145-15API 81V7        | 1         | 1.47%   |
| Lenovo IdeaPad 5 Pro 16ARH7 82SN      | 1         | 1.47%   |
| Lenovo Flex 2-14D 20376               | 1         | 1.47%   |
| Inventec Z CLASS                      | 1         | 1.47%   |
| HUAWEI BOHK-WAX9X                     | 1         | 1.47%   |
| HP Z600 Workstation                   | 1         | 1.47%   |
| HP ProBook 6460b                      | 1         | 1.47%   |
| HP ProBook 4540s                      | 1         | 1.47%   |
| HP Pavilion Desktop TP01-2xxx         | 1         | 1.47%   |
| HP Notebook                           | 1         | 1.47%   |
| HP ENVY x360 Convertible 13-ag0xxx    | 1         | 1.47%   |
| HP ENVY Laptop 13-ah0xxx              | 1         | 1.47%   |
| HP EliteDesk 800 G4 DM 65W            | 1         | 1.47%   |
| HP Compaq 8200 Elite CMT PC           | 1         | 1.47%   |
| HP Compaq 6720s                       | 1         | 1.47%   |
| HP 870-115ng                          | 1         | 1.47%   |
| Google Lillipup                       | 1         | 1.47%   |
| Gigabyte Z390 AORUS ULTRA             | 1         | 1.47%   |
| Dell XPS 9320                         | 1         | 1.47%   |
| Dell XPS 8940                         | 1         | 1.47%   |
| Dell Precision T3610                  | 1         | 1.47%   |
| Dell Precision 5570                   | 1         | 1.47%   |
| Dell Latitude E7470                   | 1         | 1.47%   |
| Dell Latitude 5421                    | 1         | 1.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lenovo ThinkPad              | 4         | 5.88%   |
| Lenovo IdeaPad               | 3         | 4.41%   |
| ASUS ROG                     | 3         | 4.41%   |
| ASUS PRIME                   | 3         | 4.41%   |
| HP ProBook                   | 2         | 2.94%   |
| HP ENVY                      | 2         | 2.94%   |
| HP Compaq                    | 2         | 2.94%   |
| Dell XPS                     | 2         | 2.94%   |
| Dell Precision               | 2         | 2.94%   |
| Dell Latitude                | 2         | 2.94%   |
| Dell Inspiron                | 2         | 2.94%   |
| Acer Aspire                  | 2         | 2.94%   |
| Unknown                      | 2         | 2.94%   |
| TUXEDO InfinityBook          | 1         | 1.47%   |
| Toshiba PORTEGE              | 1         | 1.47%   |
| Sun Microsystems Ultra       | 1         | 1.47%   |
| SK hynix HyBook              | 1         | 1.47%   |
| Schenker VIA                 | 1         | 1.47%   |
| Samsung 550XDA               | 1         | 1.47%   |
| MSI MS-7B61                  | 1         | 1.47%   |
| MSI MS-7522                  | 1         | 1.47%   |
| Medion P6624                 | 1         | 1.47%   |
| Lenovo Legion                | 1         | 1.47%   |
| Lenovo Flex                  | 1         | 1.47%   |
| Inventec Z                   | 1         | 1.47%   |
| HUAWEI BOHK-WAX9X            | 1         | 1.47%   |
| HP Z600                      | 1         | 1.47%   |
| HP Pavilion                  | 1         | 1.47%   |
| HP Notebook                  | 1         | 1.47%   |
| HP EliteDesk                 | 1         | 1.47%   |
| HP 870-115ng                 | 1         | 1.47%   |
| Google Lillipup              | 1         | 1.47%   |
| Gigabyte Z390                | 1         | 1.47%   |
| AXDIA International WINDESK9 | 1         | 1.47%   |
| ASUS ZenBook                 | 1         | 1.47%   |
| ASUS X541NA                  | 1         | 1.47%   |
| ASUS VivoBook                | 1         | 1.47%   |
| ASUS TUF                     | 1         | 1.47%   |
| ASUS Pro                     | 1         | 1.47%   |
| ASUS M4A89GTD-PRO            | 1         | 1.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 12        | 17.65%  |
| 2022 | 9         | 13.24%  |
| 2020 | 7         | 10.29%  |
| 2019 | 5         | 7.35%   |
| 2018 | 5         | 7.35%   |
| 2015 | 5         | 7.35%   |
| 2010 | 5         | 7.35%   |
| 2012 | 4         | 5.88%   |
| 2017 | 3         | 4.41%   |
| 2016 | 2         | 2.94%   |
| 2014 | 2         | 2.94%   |
| 2013 | 2         | 2.94%   |
| 2011 | 2         | 2.94%   |
| 2023 | 1         | 1.47%   |
| 2009 | 1         | 1.47%   |
| 2008 | 1         | 1.47%   |
| 2007 | 1         | 1.47%   |
| 2006 | 1         | 1.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 38        | 55.88%  |
| Desktop     | 27        | 39.71%  |
| Convertible | 2         | 2.94%   |
| All in one  | 1         | 1.47%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 53        | 77.94%  |
| Enabled  | 15        | 22.06%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 67        | 98.53%  |
| Yes  | 1         | 1.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 16        | 23.53%  |
| 4.01-8.0    | 15        | 22.06%  |
| 16.01-24.0  | 15        | 22.06%  |
| 32.01-64.0  | 10        | 14.71%  |
| 3.01-4.0    | 6         | 8.82%   |
| 24.01-32.0  | 2         | 2.94%   |
| 64.01-256.0 | 2         | 2.94%   |
| 1.01-2.0    | 1         | 1.47%   |
| 0.51-1.0    | 1         | 1.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 17        | 25%     |
| 2.01-3.0  | 16        | 23.53%  |
| 3.01-4.0  | 15        | 22.06%  |
| 1.01-2.0  | 14        | 20.59%  |
| 8.01-16.0 | 4         | 5.88%   |
| 0.51-1.0  | 1         | 1.47%   |
| 0.01-0.5  | 1         | 1.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 40        | 58.82%  |
| 2      | 12        | 17.65%  |
| 4      | 7         | 10.29%  |
| 3      | 6         | 8.82%   |
| 5      | 3         | 4.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 48        | 70.59%  |
| Yes       | 20        | 29.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 77.94%  |
| No        | 15        | 22.06%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 75%     |
| No        | 17        | 25%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 73.53%  |
| No        | 18        | 26.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 18        | 26.47%  |
| USA          | 11        | 16.18%  |
| Italy        | 4         | 5.88%   |
| Brazil       | 4         | 5.88%   |
| Spain        | 3         | 4.41%   |
| Poland       | 3         | 4.41%   |
| Netherlands  | 3         | 4.41%   |
| UK           | 2         | 2.94%   |
| Romania      | 2         | 2.94%   |
| Belgium      | 2         | 2.94%   |
| Australia    | 2         | 2.94%   |
| Turkey       | 1         | 1.47%   |
| Sweden       | 1         | 1.47%   |
| South Africa | 1         | 1.47%   |
| Serbia       | 1         | 1.47%   |
| Philippines  | 1         | 1.47%   |
| France       | 1         | 1.47%   |
| Finland      | 1         | 1.47%   |
| Denmark      | 1         | 1.47%   |
| Cyprus       | 1         | 1.47%   |
| Canada       | 1         | 1.47%   |
| Bulgaria     | 1         | 1.47%   |
| Bolivia      | 1         | 1.47%   |
| Austria      | 1         | 1.47%   |
| Argentina    | 1         | 1.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City           | Computers | Percent |
|----------------|-----------|---------|
| Melbourne      | 2         | 2.94%   |
| Cherry Hill    | 2         | 2.94%   |
| Berlin         | 2         | 2.94%   |
| Zarnowiec      | 1         | 1.47%   |
| Warsaw         | 1         | 1.47%   |
| Viersen        | 1         | 1.47%   |
| Venice         | 1         | 1.47%   |
| Varna          | 1         | 1.47%   |
| Uccle          | 1         | 1.47%   |
| Tacoma         | 1         | 1.47%   |
| Stockholm      | 1         | 1.47%   |
| Steinhagen     | 1         | 1.47%   |
| Saskatoon      | 1         | 1.47%   |
| Sao Fidelis    | 1         | 1.47%   |
| Santa Cruz     | 1         | 1.47%   |
| Rio de Janeiro | 1         | 1.47%   |
| Rio Branco     | 1         | 1.47%   |
| Pretoria       | 1         | 1.47%   |
| Port Orchard   | 1         | 1.47%   |
| Pedro Leopoldo | 1         | 1.47%   |
| Paris          | 1         | 1.47%   |
| Painesville    | 1         | 1.47%   |
| Padova         | 1         | 1.47%   |
| Ozawkie        | 1         | 1.47%   |
| Oldenburg      | 1         | 1.47%   |
| Obertraubling  | 1         | 1.47%   |
| Norderstedt    | 1         | 1.47%   |
| Noia           | 1         | 1.47%   |
| Naples         | 1         | 1.47%   |
| Munich         | 1         | 1.47%   |
| Milford        | 1         | 1.47%   |
| Market Weston  | 1         | 1.47%   |
| Lodz           | 1         | 1.47%   |
| Linsengericht  | 1         | 1.47%   |
| Lincoln        | 1         | 1.47%   |
| Leskovac       | 1         | 1.47%   |
| Langenfeld     | 1         | 1.47%   |
| Kyrenia        | 1         | 1.47%   |
| Konya          | 1         | 1.47%   |
| Hoogvliet      | 1         | 1.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 17        | 22     | 16.04%  |
| WDC                         | 12        | 18     | 11.32%  |
| Seagate                     | 11        | 15     | 10.38%  |
| Toshiba                     | 10        | 10     | 9.43%   |
| Sandisk                     | 10        | 11     | 9.43%   |
| Kingston                    | 6         | 8      | 5.66%   |
| SK hynix                    | 5         | 5      | 4.72%   |
| Unknown                     | 4         | 4      | 3.77%   |
| Crucial                     | 4         | 4      | 3.77%   |
| Intel                       | 3         | 3      | 2.83%   |
| Silicon Motion              | 2         | 2      | 1.89%   |
| Phison Electronics          | 2         | 2      | 1.89%   |
| KIOXIA                      | 2         | 2      | 1.89%   |
| Kingston Technology Company | 2         | 2      | 1.89%   |
| Hitachi                     | 2         | 2      | 1.89%   |
| HGST                        | 2         | 2      | 1.89%   |
| Transcend                   | 1         | 1      | 0.94%   |
| SPCC                        | 1         | 1      | 0.94%   |
| Plextor                     | 1         | 1      | 0.94%   |
| Netac                       | 1         | 1      | 0.94%   |
| Maxtor                      | 1         | 1      | 0.94%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.94%   |
| LDLC                        | 1         | 1      | 0.94%   |
| Kimtigo                     | 1         | 1      | 0.94%   |
| Fanxiang                    | 1         | 1      | 0.94%   |
| Apple                       | 1         | 1      | 0.94%   |
| ADATA Technology            | 1         | 1      | 0.94%   |
| Unknown                     | 1         | 1      | 0.94%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Sandisk WD Blue SN550 NVMe SSD 1TB                   | 4         | 3.31%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 960GB | 4         | 3.31%   |
| Seagate ST1000DM010-2EP102 1TB                       | 3         | 2.48%   |
| Seagate Expansion 1TB                                | 3         | 2.48%   |
| WDC WD2500HHTZ-04N21V0 250GB                         | 2         | 1.65%   |
| Toshiba MQ01ABD100 1TB                               | 2         | 1.65%   |
| Toshiba KXG50ZNV256G 256GB                           | 2         | 1.65%   |
| Toshiba DT01ACA050 500GB                             | 2         | 1.65%   |
| SK hynix HFM512GD3JX013N 512GB                       | 2         | 1.65%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB    | 2         | 1.65%   |
| Samsung SSD 840 EVO 250GB                            | 2         | 1.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 512GB  | 2         | 1.65%   |
| Samsung NVMe SSD Controller SM951/PM951 256GB        | 2         | 1.65%   |
| Kingston SA400S37480G 480GB SSD                      | 2         | 1.65%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                     | 1         | 0.83%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                     | 1         | 0.83%   |
| WDC WDS240G1G0A-00SS50 240GB SSD                     | 1         | 0.83%   |
| WDC WD5000LPVT-22G33T0 500GB                         | 1         | 0.83%   |
| WDC WD5000LPCX-24C6HT0 500GB                         | 1         | 0.83%   |
| WDC WD5000HHTZ-04N21V0 500GB                         | 1         | 0.83%   |
| WDC WD40EFRX-68N32N0 4TB                             | 1         | 0.83%   |
| WDC WD3200BEKT-22KA9T0 320GB                         | 1         | 0.83%   |
| WDC WD20PURX-64P6ZY0 2TB                             | 1         | 0.83%   |
| WDC WD20EZRX-00D8PB0 2TB                             | 1         | 0.83%   |
| WDC WD10SPZX-24Z10 1TB                               | 1         | 0.83%   |
| WDC WD10SPCX-24HWST1 1TB                             | 1         | 0.83%   |
| WDC WD10EURX-63C57Y0 1TB                             | 1         | 0.83%   |
| WDC WD101FZBX-00ATAA0 10TB                           | 1         | 0.83%   |
| Unknown MMC Card  64GB                               | 1         | 0.83%   |
| Unknown MMC Card  32GB                               | 1         | 0.83%   |
| Unknown MMC Card  256GB                              | 1         | 0.83%   |
| Unknown MMC Card  128GB                              | 1         | 0.83%   |
| Transcend TS2TSSD220Q 2TB                            | 1         | 0.83%   |
| Toshiba THNSNB128GMCJ 128GB SSD                      | 1         | 0.83%   |
| Toshiba THNSFJ256GDNU A 256GB SSD                    | 1         | 0.83%   |
| Toshiba MQ01ABF050 500GB                             | 1         | 0.83%   |
| Toshiba DT01ACA100 1TB                               | 1         | 0.83%   |
| SPCC Solid State Disk 512GB                          | 1         | 0.83%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB               | 1         | 0.83%   |
| SK hynix PC801 NVMe 1TB                              | 1         | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 15     | 30.56%  |
| WDC                 | 10        | 15     | 27.78%  |
| Toshiba             | 6         | 6      | 16.67%  |
| Samsung Electronics | 3         | 4      | 8.33%   |
| Hitachi             | 2         | 2      | 5.56%   |
| HGST                | 2         | 2      | 5.56%   |
| Maxtor              | 1         | 1      | 2.78%   |
| Apple               | 1         | 1      | 2.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 21.21%  |
| SanDisk             | 5         | 5      | 15.15%  |
| Kingston            | 5         | 7      | 15.15%  |
| Crucial             | 4         | 4      | 12.12%  |
| WDC                 | 3         | 3      | 9.09%   |
| Toshiba             | 2         | 2      | 6.06%   |
| Transcend           | 1         | 1      | 3.03%   |
| SPCC                | 1         | 1      | 3.03%   |
| Plextor             | 1         | 1      | 3.03%   |
| Kimtigo             | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |
| Fanxiang            | 1         | 1      | 3.03%   |
| Unknown             | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 30        | 37     | 31.91%  |
| HDD     | 30        | 46     | 31.91%  |
| SSD     | 29        | 36     | 30.85%  |
| MMC     | 4         | 4      | 4.26%   |
| Unknown | 1         | 1      | 1.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 44        | 78     | 53.01%  |
| NVMe | 30        | 37     | 36.14%  |
| SAS  | 5         | 5      | 6.02%   |
| MMC  | 4         | 4      | 4.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 42     | 47.37%  |
| 0.51-1.0   | 19        | 27     | 33.33%  |
| 1.01-2.0   | 6         | 7      | 10.53%  |
| 3.01-4.0   | 2         | 3      | 3.51%   |
| 4.01-10.0  | 2         | 2      | 3.51%   |
| 2.01-3.0   | 1         | 1      | 1.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 25        | 36.76%  |
| 1001-2000      | 19        | 27.94%  |
| 501-1000       | 11        | 16.18%  |
| 2001-3000      | 5         | 7.35%   |
| 101-250        | 3         | 4.41%   |
| 251-500        | 2         | 2.94%   |
| 21-50          | 2         | 2.94%   |
| 1-20           | 1         | 1.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 15        | 22.06%  |
| 51-100         | 14        | 20.59%  |
| 1001-2000      | 10        | 14.71%  |
| 251-500        | 8         | 11.76%  |
| 501-1000       | 8         | 11.76%  |
| 21-50          | 4         | 5.88%   |
| 2001-3000      | 4         | 5.88%   |
| 1-20           | 4         | 5.88%   |
| More than 3000 | 1         | 1.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD5000HHTZ-04N21V0 500GB | 1         | 1      | 50%     |
| WDC WD20EZRX-00D8PB0 2TB     | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 2         | 2      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 2         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 100%    |

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
| Detected | 40        | 82     | 57.14%  |
| Works    | 28        | 40     | 40%     |
| Malfunc  | 2         | 2      | 2.86%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 40        | 40.82%  |
| AMD                          | 17        | 17.35%  |
| Samsung Electronics          | 9         | 9.18%   |
| SanDisk                      | 6         | 6.12%   |
| SK hynix                     | 5         | 5.1%    |
| Kingston Technology Company  | 3         | 3.06%   |
| JMicron Technology           | 3         | 3.06%   |
| Toshiba America Info Systems | 2         | 2.04%   |
| Silicon Motion               | 2         | 2.04%   |
| Phison Electronics           | 2         | 2.04%   |
| KIOXIA                       | 2         | 2.04%   |
| Nvidia                       | 1         | 1.02%   |
| Netac Technology             | 1         | 1.02%   |
| MAXIO Technology (Hangzhou)  | 1         | 1.02%   |
| Marvell Technology Group     | 1         | 1.02%   |
| LSI Logic / Symbios Logic    | 1         | 1.02%   |
| ASMedia Technology           | 1         | 1.02%   |
| ADATA Technology             | 1         | 1.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 9.91%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 3.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 3.6%    |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 3.6%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 2.7%    |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 2.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 2.7%    |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 2.7%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 1.8%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 1.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.8%    |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 1.8%    |
| JMicron JMB363 SATA/IDE Controller                                             | 2         | 1.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 1.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.8%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 1.8%    |
| SK hynix Platinum P41 NVMe Solid State Drive 2TB                               | 1         | 0.9%    |
| SK hynix BC511                                                                 | 1         | 0.9%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.9%    |
| Sandisk Non-Volatile memory controller                                         | 1         | 0.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 0.9%    |
| Samsung NVMe SSD Controller 980                                                | 1         | 0.9%    |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.9%    |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.9%    |
| Nvidia MCP55 SATA Controller                                                   | 1         | 0.9%    |
| Nvidia MCP55 IDE                                                               | 1         | 0.9%    |
| Netac Non-Volatile memory controller                                           | 1         | 0.9%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1         | 0.9%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 1         | 0.9%    |
| LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI          | 1         | 0.9%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 0.9%    |
| KIOXIA Non-Volatile memory controller                                          | 1         | 0.9%    |
| JMicron JMB368 IDE controller                                                  | 1         | 0.9%    |
| JMicron JMB361 AHCI/IDE                                                        | 1         | 0.9%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 46        | 49.46%  |
| NVMe | 30        | 32.26%  |
| IDE  | 9         | 9.68%   |
| RAID | 7         | 7.53%   |
| SCSI | 1         | 1.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 44        | 64.71%  |
| AMD    | 24        | 35.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-1260P                  | 3         | 4.41%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 4.41%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 4.41%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 2.94%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 2         | 2.94%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 2         | 2.94%   |
| AMD Phenom II X4 965 Processor                | 2         | 2.94%   |
| Intel Xeon CPU X5675 @ 3.07GHz                | 1         | 1.47%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz           | 1         | 1.47%   |
| Intel Xeon CPU E31270 @ 3.40GHz               | 1         | 1.47%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 1.47%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 1.47%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 1.47%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.47%   |
| Intel Core i7-6820HK CPU @ 2.70GHz            | 1         | 1.47%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 1.47%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 1.47%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 1.47%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 1.47%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.47%   |
| Intel Core i7 CPU 920 @ 2.67GHz               | 1         | 1.47%   |
| Intel Core i7 CPU 870 @ 2.93GHz               | 1         | 1.47%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 1         | 1.47%   |
| Intel Core i5-8500 CPU @ 3.00GHz              | 1         | 1.47%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 1         | 1.47%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.47%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 1         | 1.47%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.47%   |
| Intel Core i5-2467M CPU @ 1.60GHz             | 1         | 1.47%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.47%   |
| Intel Core i5-2400S CPU @ 2.50GHz             | 1         | 1.47%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.47%   |
| Intel Core i3-9100F CPU @ 3.60GHz             | 1         | 1.47%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 1         | 1.47%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz         | 1         | 1.47%   |
| Intel Celeron M CPU 530 @ 1.73GHz             | 1         | 1.47%   |
| Intel Atom CPU Z3735G @ 1.33GHz               | 1         | 1.47%   |
| Intel 12th Gen Core i7-12800H                 | 1         | 1.47%   |
| Intel 12th Gen Core i7-12650H                 | 1         | 1.47%   |
| Intel 11th Gen Core i9-11900 @ 2.50GHz        | 1         | 1.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Other                  | 13        | 19.12%  |
| Intel Core i5          | 10        | 14.71%  |
| Intel Core i7          | 9         | 13.24%  |
| AMD Ryzen 5            | 7         | 10.29%  |
| AMD Ryzen 7            | 5         | 7.35%   |
| Intel Xeon             | 4         | 5.88%   |
| AMD Ryzen 9            | 4         | 5.88%   |
| Intel Core i3          | 2         | 2.94%   |
| Intel Celeron          | 2         | 2.94%   |
| AMD Phenom II X4       | 2         | 2.94%   |
| Intel Pentium Silver   | 1         | 1.47%   |
| Intel Pentium          | 1         | 1.47%   |
| Intel Core 2 Quad      | 1         | 1.47%   |
| Intel Celeron M        | 1         | 1.47%   |
| Intel Atom             | 1         | 1.47%   |
| AMD Ryzen Threadripper | 1         | 1.47%   |
| AMD G                  | 1         | 1.47%   |
| AMD E1                 | 1         | 1.47%   |
| AMD Athlon             | 1         | 1.47%   |
| AMD A8                 | 1         | 1.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 28        | 41.18%  |
| 2      | 13        | 19.12%  |
| 8      | 8         | 11.76%  |
| 6      | 8         | 11.76%  |
| 12     | 6         | 8.82%   |
| 1      | 2         | 2.94%   |
| 24     | 1         | 1.47%   |
| 14     | 1         | 1.47%   |
| 10     | 1         | 1.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 67        | 98.53%  |
| 2      | 1         | 1.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 48        | 70.59%  |
| 1      | 20        | 29.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 68        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 11.76%  |
| 0x906a3    | 5         | 7.35%   |
| 0x806c1    | 4         | 5.88%   |
| 0x506e3    | 3         | 4.41%   |
| 0x206a7    | 3         | 4.41%   |
| 0x0a50000d | 3         | 4.41%   |
| 0x010000c8 | 3         | 4.41%   |
| 0x906ea    | 2         | 2.94%   |
| 0x706a8    | 2         | 2.94%   |
| 0x08108102 | 2         | 2.94%   |
| 0xa0671    | 1         | 1.47%   |
| 0x906ed    | 1         | 1.47%   |
| 0x906eb    | 1         | 1.47%   |
| 0x906c0    | 1         | 1.47%   |
| 0x806ec    | 1         | 1.47%   |
| 0x806ea    | 1         | 1.47%   |
| 0x806d1    | 1         | 1.47%   |
| 0x6fa      | 1         | 1.47%   |
| 0x506c9    | 1         | 1.47%   |
| 0x406e3    | 1         | 1.47%   |
| 0x40651    | 1         | 1.47%   |
| 0x306e4    | 1         | 1.47%   |
| 0x306c3    | 1         | 1.47%   |
| 0x306a9    | 1         | 1.47%   |
| 0x30678    | 1         | 1.47%   |
| 0x106e5    | 1         | 1.47%   |
| 0x106a4    | 1         | 1.47%   |
| 0x1067a    | 1         | 1.47%   |
| 0x0a50000c | 1         | 1.47%   |
| 0x0a404102 | 1         | 1.47%   |
| 0x0a404101 | 1         | 1.47%   |
| 0x0a20120a | 1         | 1.47%   |
| 0x08701030 | 1         | 1.47%   |
| 0x08701021 | 1         | 1.47%   |
| 0x08608103 | 1         | 1.47%   |
| 0x08108109 | 1         | 1.47%   |
| 0x0810100b | 1         | 1.47%   |
| 0x0800820d | 1         | 1.47%   |
| 0x0800111c | 1         | 1.47%   |
| 0x07030104 | 1         | 1.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 7         | 10.29%  |
| Zen 3            | 6         | 8.82%   |
| Alderlake Hybrid | 5         | 7.35%   |
| Zen+             | 4         | 5.88%   |
| TigerLake        | 4         | 5.88%   |
| Skylake          | 4         | 5.88%   |
| SandyBridge      | 4         | 5.88%   |
| Unknown          | 4         | 5.88%   |
| Nehalem          | 3         | 4.41%   |
| K10              | 3         | 4.41%   |
| Haswell          | 3         | 4.41%   |
| Zen 2            | 2         | 2.94%   |
| Zen              | 2         | 2.94%   |
| Westmere         | 2         | 2.94%   |
| IvyBridge        | 2         | 2.94%   |
| Icelake          | 2         | 2.94%   |
| Goldmont plus    | 2         | 2.94%   |
| Tremont          | 1         | 1.47%   |
| Steamroller      | 1         | 1.47%   |
| Silvermont       | 1         | 1.47%   |
| Puma             | 1         | 1.47%   |
| Penryn           | 1         | 1.47%   |
| Jaguar           | 1         | 1.47%   |
| Goldmont         | 1         | 1.47%   |
| Core             | 1         | 1.47%   |
| Bobcat           | 1         | 1.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 30        | 38.96%  |
| AMD    | 26        | 33.77%  |
| Nvidia | 21        | 27.27%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 5         | 6.33%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 4         | 5.06%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 3         | 3.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 3.8%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 2         | 2.53%   |
| Nvidia GA104 [GeForce RTX 3060]                                           | 2         | 2.53%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                 | 2         | 2.53%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 2.53%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 2.53%   |
| AMD Rembrandt [Radeon 680M]                                               | 2         | 2.53%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 2         | 2.53%   |
| Nvidia GT216GLM [Quadro FX 880M]                                          | 1         | 1.27%   |
| Nvidia GT215 [GeForce GT 320]                                             | 1         | 1.27%   |
| Nvidia GT215 [GeForce GT 240]                                             | 1         | 1.27%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                       | 1         | 1.27%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 1         | 1.27%   |
| Nvidia GM206 [GeForce GTX 950]                                            | 1         | 1.27%   |
| Nvidia GM204M [GeForce GTX 980M]                                          | 1         | 1.27%   |
| Nvidia GM204 [GeForce GTX 970]                                            | 1         | 1.27%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 1.27%   |
| Nvidia GM107GLM [Quadro M2000M]                                           | 1         | 1.27%   |
| Nvidia GK107M [GeForce GT 755M Mac Edition]                               | 1         | 1.27%   |
| Nvidia GK106GL [Quadro K4000]                                             | 1         | 1.27%   |
| Nvidia GF108M [GeForce GT 425M]                                           | 1         | 1.27%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 1         | 1.27%   |
| Nvidia GA107GLM [RTX A1000 Laptop GPU]                                    | 1         | 1.27%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 1.27%   |
| Nvidia GA104M [Geforce RTX 3070 Ti Laptop GPU]                            | 1         | 1.27%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 1.27%   |
| Intel UHD Graphics 620                                                    | 1         | 1.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 1.27%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 1         | 1.27%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 1.27%   |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                 | 1         | 1.27%   |
| Intel JasperLake [UHD Graphics]                                           | 1         | 1.27%   |
| Intel HD Graphics P530                                                    | 1         | 1.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 1.27%   |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 1.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 1.27%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1         | 1.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 24        | 35.29%  |
| 1 x AMD        | 20        | 29.41%  |
| 1 x Nvidia     | 13        | 19.12%  |
| Intel + Nvidia | 5         | 7.35%   |
| AMD + Nvidia   | 3         | 4.41%   |
| 2 x AMD        | 2         | 2.94%   |
| Intel + AMD    | 1         | 1.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 58        | 85.29%  |
| Proprietary | 8         | 11.76%  |
| Unknown     | 2         | 2.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 50%     |
| 1.01-2.0   | 7         | 10.29%  |
| 0.01-0.5   | 7         | 10.29%  |
| 7.01-8.0   | 5         | 7.35%   |
| 3.01-4.0   | 5         | 7.35%   |
| 0.51-1.0   | 5         | 7.35%   |
| 8.01-16.0  | 3         | 4.41%   |
| 24.01-32.0 | 1         | 1.47%   |
| 2.01-3.0   | 1         | 1.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 10        | 13.7%   |
| BOE                     | 7         | 9.59%   |
| Samsung Electronics     | 5         | 6.85%   |
| LG Display              | 5         | 6.85%   |
| Goldstar                | 5         | 6.85%   |
| Chimei Innolux          | 5         | 6.85%   |
| Hewlett-Packard         | 4         | 5.48%   |
| Dell                    | 4         | 5.48%   |
| Lenovo                  | 3         | 4.11%   |
| Sharp                   | 2         | 2.74%   |
| Philips                 | 2         | 2.74%   |
| Ancor Communications    | 2         | 2.74%   |
| Acer                    | 2         | 2.74%   |
| Unknown                 | 1         | 1.37%   |
| SLD                     | 1         | 1.37%   |
| Pixio                   | 1         | 1.37%   |
| PANDA                   | 1         | 1.37%   |
| Panasonic               | 1         | 1.37%   |
| Onkyo                   | 1         | 1.37%   |
| Medion                  | 1         | 1.37%   |
| LG Philips              | 1         | 1.37%   |
| LG Electronics          | 1         | 1.37%   |
| InnoLux Display         | 1         | 1.37%   |
| Eizo                    | 1         | 1.37%   |
| Chi Mei Optoelectronics | 1         | 1.37%   |
| BenQ                    | 1         | 1.37%   |
| ASUSTek Computer        | 1         | 1.37%   |
| Apple                   | 1         | 1.37%   |
| AOC                     | 1         | 1.37%   |
| Unknown                 | 1         | 1.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 1.3%    |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                  | 1         | 1.3%    |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch               | 1         | 1.3%    |
| Sharp LC55LBU591C SHP4353 3840x2160 800x450mm 36.1-inch               | 1         | 1.3%    |
| Samsung Electronics T27B350 SAM0945 1920x1080 598x336mm 27.0-inch     | 1         | 1.3%    |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch   | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch  | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch | 1         | 1.3%    |
| Pixio OZDSP27IPS WAM2700 2560x1440 597x336mm 27.0-inch                | 1         | 1.3%    |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1         | 1.3%    |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch               | 1         | 1.3%    |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch               | 1         | 1.3%    |
| Panasonic TV MEIC328 1920x1080 698x392mm 31.5-inch                    | 1         | 1.3%    |
| Onkyo TX-NR515 ONK0C51 3840x2160 800x450mm 36.1-inch                  | 1         | 1.3%    |
| Medion MD20435 MED36D6 1920x1080 521x293mm 23.5-inch                  | 1         | 1.3%    |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch           | 1         | 1.3%    |
| LG Electronics LCD Monitor LG ULTRAWIDE                               | 1         | 1.3%    |
| LG Display LCD Monitor LGD06CE 1920x1200 288x180mm 13.4-inch          | 1         | 1.3%    |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 1         | 1.3%    |
| LG Display LCD Monitor LGD0597 1920x1080 294x165mm 13.3-inch          | 1         | 1.3%    |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch          | 1         | 1.3%    |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 1.3%    |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch            | 1         | 1.3%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 1         | 1.3%    |
| Lenovo L27e-30 LEN66BE 1920x1080 597x336mm 27.0-inch                  | 1         | 1.3%    |
| InnoLux Display LCD Monitor INL0028 1366x768 309x174mm 14.0-inch      | 1         | 1.3%    |
| Hewlett-Packard LE2002x HWP2963 1600x900 443x249mm 20.0-inch          | 1         | 1.3%    |
| Hewlett-Packard E22 G4 HPN3683 1920x1080 476x267mm 21.5-inch          | 1         | 1.3%    |
| Hewlett-Packard 24m HPN3577 1920x1080 527x297mm 23.8-inch             | 1         | 1.3%    |
| Hewlett-Packard 2210 HWP288A 1920x1080 476x268mm 21.5-inch            | 1         | 1.3%    |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 1         | 1.3%    |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 1         | 1.3%    |
| Goldstar ULTRAGEAR GSM5BB2 1920x1080 527x296mm 23.8-inch              | 1         | 1.3%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 1         | 1.3%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 1.3%    |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 1         | 1.3%    |
| Eizo S1921 ENC1831 1280x1024 376x301mm 19.0-inch                      | 1         | 1.3%    |
| Dell U2715H DELD065 2560x1440 597x336mm 27.0-inch                     | 1         | 1.3%    |
| Dell U2415 DELA0B8 1920x1080 518x324mm 24.1-inch                      | 1         | 1.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 36        | 50%     |
| 1366x768 (WXGA)   | 8         | 11.11%  |
| 3840x2160 (4K)    | 5         | 6.94%   |
| 2560x1440 (QHD)   | 5         | 6.94%   |
| 1920x1200 (WUXGA) | 4         | 5.56%   |
| 2560x1600         | 3         | 4.17%   |
| 1600x900 (HD+)    | 2         | 2.78%   |
| 6400x1440         | 1         | 1.39%   |
| 4480x1440         | 1         | 1.39%   |
| 2560x1080         | 1         | 1.39%   |
| 2288x1287         | 1         | 1.39%   |
| 1440x900 (WXGA+)  | 1         | 1.39%   |
| 1360x768          | 1         | 1.39%   |
| 1280x800 (WXGA)   | 1         | 1.39%   |
| 1280x1024 (SXGA)  | 1         | 1.39%   |
| Unknown           | 1         | 1.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 15        | 20.83%  |
| 27      | 10        | 13.89%  |
| 13      | 10        | 13.89%  |
| 24      | 5         | 6.94%   |
| 23      | 4         | 5.56%   |
| 21      | 4         | 5.56%   |
| 17      | 4         | 5.56%   |
| 14      | 4         | 5.56%   |
| 16      | 3         | 4.17%   |
| 54      | 2         | 2.78%   |
| 31      | 2         | 2.78%   |
| 19      | 2         | 2.78%   |
| 142     | 1         | 1.39%   |
| 43      | 1         | 1.39%   |
| 34      | 1         | 1.39%   |
| 30      | 1         | 1.39%   |
| 20      | 1         | 1.39%   |
| 18      | 1         | 1.39%   |
| Unknown | 1         | 1.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 28        | 38.89%  |
| 501-600        | 18        | 25%     |
| 401-500        | 7         | 9.72%   |
| 351-400        | 5         | 6.94%   |
| 601-700        | 4         | 5.56%   |
| 201-300        | 4         | 5.56%   |
| 1001-1500      | 2         | 2.78%   |
| More than 2000 | 1         | 1.39%   |
| 701-800        | 1         | 1.39%   |
| 901-1000       | 1         | 1.39%   |
| Unknown        | 1         | 1.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 52        | 77.61%  |
| 16/10   | 11        | 16.42%  |
| 5/4     | 1         | 1.49%   |
| 21/9    | 1         | 1.49%   |
| 1.00    | 1         | 1.49%   |
| Unknown | 1         | 1.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 14        | 19.44%  |
| 81-90          | 10        | 13.89%  |
| 301-350        | 10        | 13.89%  |
| 201-250        | 9         | 12.5%   |
| 151-200        | 5         | 6.94%   |
| 71-80          | 4         | 5.56%   |
| 351-500        | 4         | 5.56%   |
| 121-130        | 4         | 5.56%   |
| 111-120        | 4         | 5.56%   |
| More than 1000 | 3         | 4.17%   |
| 251-300        | 2         | 2.78%   |
| 141-150        | 1         | 1.39%   |
| 501-1000       | 1         | 1.39%   |
| Unknown        | 1         | 1.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 23        | 31.94%  |
| 121-160 | 20        | 27.78%  |
| 101-120 | 18        | 25%     |
| 161-240 | 7         | 9.72%   |
| 1-50    | 3         | 4.17%   |
| Unknown | 1         | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 57        | 83.82%  |
| 2     | 9         | 13.24%  |
| 3     | 1         | 1.47%   |
| 0     | 1         | 1.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 36        | 38.3%   |
| Intel                                 | 36        | 38.3%   |
| Qualcomm Atheros                      | 8         | 8.51%   |
| Broadcom                              | 4         | 4.26%   |
| MediaTek                              | 3         | 3.19%   |
| Xiaomi                                | 1         | 1.06%   |
| Ralink Technology                     | 1         | 1.06%   |
| Nvidia                                | 1         | 1.06%   |
| Hewlett-Packard                       | 1         | 1.06%   |
| Dell                                  | 1         | 1.06%   |
| ASIX Electronics                      | 1         | 1.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 1.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 21.82%  |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 4.55%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 3.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 2.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.82%   |
| Intel Wireless 8260                                               | 2         | 1.82%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.82%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.82%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.82%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.91%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.91%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1         | 0.91%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.91%   |
| Realtek Realtek Network controller                                | 1         | 0.91%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.91%   |
| Realtek 802.11ac NIC                                              | 1         | 0.91%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.91%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.91%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.91%   |
| Nvidia MCP55 Ethernet                                             | 1         | 0.91%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.91%   |
| Intel Wireless-AC 9260                                            | 1         | 0.91%   |
| Intel Wireless Gigabit 17265                                      | 1         | 0.91%   |
| Intel Wireless 8265 / 8275                                        | 1         | 0.91%   |
| Intel Wireless 7265                                               | 1         | 0.91%   |
| Intel Wireless 7260                                               | 1         | 0.91%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1         | 0.91%   |
| Intel PRODUCT_MODEM                                               | 1         | 0.91%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 29        | 54.72%  |
| Realtek Semiconductor                 | 8         | 15.09%  |
| Qualcomm Atheros                      | 7         | 13.21%  |
| MediaTek                              | 3         | 5.66%   |
| Broadcom                              | 3         | 5.66%   |
| Ralink Technology                     | 1         | 1.89%   |
| Dell                                  | 1         | 1.89%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 1.89%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                                                                  | Computers | Percent |
|--------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                                                                       | 5         | 9.26%   |
| Intel Wi-Fi 6 AX201                                                                                    | 4         | 7.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                       | 3         | 5.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                               | 2         | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                             | 2         | 3.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                             | 2         | 3.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                          | 2         | 3.7%    |
| Intel Wireless 8260                                                                                    | 2         | 3.7%    |
| Intel Wi-Fi 6 AX200                                                                                    | 2         | 3.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                                                         | 2         | 3.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                               | 1         | 1.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                                        | 1         | 1.85%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                                        | 1         | 1.85%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                            | 1         | 1.85%   |
| Realtek Realtek Network controller                                                                     | 1         | 1.85%   |
| Realtek 802.11ac NIC                                                                                   | 1         | 1.85%   |
| Ralink RT5370 Wireless Adapter                                                                         | 1         | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                             | 1         | 1.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                       | 1         | 1.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                         | 1         | 1.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                          | 1         | 1.85%   |
| Intel Wireless-AC 9260                                                                                 | 1         | 1.85%   |
| Intel Wireless Gigabit 17265                                                                           | 1         | 1.85%   |
| Intel Wireless 8265 / 8275                                                                             | 1         | 1.85%   |
| Intel Wireless 7265                                                                                    | 1         | 1.85%   |
| Intel Wireless 7260                                                                                    | 1         | 1.85%   |
| Intel Wi-Fi 6 AX201 160MHz                                                                             | 1         | 1.85%   |
| Intel PRODUCT_MODEM                                                                                    | 1         | 1.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                      | 1         | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                                                         | 1         | 1.85%   |
| Intel Centrino Ultimate-N 6300                                                                         | 1         | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                           | 1         | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                                                        | 1         | 1.85%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                                                   | 1         | 1.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                                     | 1         | 1.85%   |
| Broadcom BCM43142 802.11b/g/n                                                                          | 1         | 1.85%   |
| Broadcom BCM4311 802.11b/g WLAN                                                                        | 1         | 1.85%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB600N v2 Dual-Band Wireless-N Network Adapter [Ralink RT3572] | 1         | 1.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 30        | 54.55%  |
| Intel                 | 18        | 32.73%  |
| Qualcomm Atheros      | 2         | 3.64%   |
| Broadcom              | 2         | 3.64%   |
| Xiaomi                | 1         | 1.82%   |
| Nvidia                | 1         | 1.82%   |
| ASIX Electronics      | 1         | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 43.64%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 3.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 3.64%   |
| Intel I211 Gigabit Network Connection                             | 2         | 3.64%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 3.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.82%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.82%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.82%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.82%   |
| Nvidia MCP55 Ethernet                                             | 1         | 1.82%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.82%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.82%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.82%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.82%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.82%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.82%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.82%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.82%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.82%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 1.82%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 1.82%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.82%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.82%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 53        | 50.48%  |
| WiFi     | 51        | 48.57%  |
| Modem    | 1         | 0.95%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 41        | 59.42%  |
| Ethernet | 28        | 40.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 33        | 48.53%  |
| 1     | 31        | 45.59%  |
| 3     | 2         | 2.94%   |
| 0     | 2         | 2.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 47        | 69.12%  |
| Yes  | 21        | 30.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 52%     |
| IMC Networks                    | 5         | 10%     |
| Realtek Semiconductor           | 4         | 8%      |
| Broadcom                        | 4         | 8%      |
| Qualcomm Atheros Communications | 3         | 6%      |
| Cambridge Silicon Radio         | 2         | 4%      |
| Realtek                         | 1         | 2%      |
| Lite-On Technology              | 1         | 2%      |
| Hewlett-Packard                 | 1         | 2%      |
| Foxconn / Hon Hai               | 1         | 2%      |
| ASUSTek Computer                | 1         | 2%      |
| Apple                           | 1         | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 9         | 18%     |
| Intel Bluetooth wireless interface                  | 5         | 10%     |
| Realtek Bluetooth Radio                             | 3         | 6%      |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 6%      |
| Intel Bluetooth Device                              | 3         | 6%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 6%      |
| Intel AX200 Bluetooth                               | 2         | 4%      |
| IMC Networks Wireless_Device                        | 2         | 4%      |
| IMC Networks Bluetooth Device                       | 2         | 4%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 4%      |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2%      |
| Realtek 802.11ac WLAN Adapter                       | 1         | 2%      |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2%      |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2%      |
| Lite-On Bluetooth Device                            | 1         | 2%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2%      |
| IMC Networks Bluetooth Radio                        | 1         | 2%      |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2%      |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 2%      |
| Broadcom Bluetooth Controller                       | 1         | 2%      |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 2%      |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2%      |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2%      |
| ASUS ASUS USB-BT500                                 | 1         | 2%      |
| Apple Bluetooth USB Host Controller                 | 1         | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 43        | 45.74%  |
| AMD                 | 29        | 30.85%  |
| Nvidia              | 17        | 18.09%  |
| No brand            | 1         | 1.06%   |
| GN Netcom           | 1         | 1.06%   |
| C-Media Electronics | 1         | 1.06%   |
| ASUSTek Computer    | 1         | 1.06%   |
| Unknown             | 1         | 1.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 12        | 10.26%  |
| AMD Renoir Radeon High Definition Audio Controller                                | 6         | 5.13%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 5         | 4.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 4         | 3.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 4         | 3.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 4         | 3.42%   |
| Nvidia GA104 High Definition Audio Controller                                     | 3         | 2.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3         | 2.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 3         | 2.56%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3         | 2.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3         | 2.56%   |
| AMD FCH Azalia Controller                                                         | 3         | 2.56%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2         | 1.71%   |
| Nvidia High Definition Audio Controller                                           | 2         | 1.71%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2         | 1.71%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2         | 1.71%   |
| Intel Sunrise Point-LP HD Audio                                                   | 2         | 1.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 2         | 1.71%   |
| Intel Cannon Lake PCH cAVS                                                        | 2         | 1.71%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2         | 1.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 2         | 1.71%   |
| Intel 200 Series PCH HD Audio                                                     | 2         | 1.71%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 2         | 1.71%   |
| AMD Navi 10 HDMI Audio                                                            | 2         | 1.71%   |
| AMD Kabini HDMI/DP Audio                                                          | 2         | 1.71%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2         | 1.71%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 1.71%   |
| Nvidia MCP55 High Definition Audio                                                | 1         | 0.85%   |
| Nvidia GT216 HDMI Audio Controller                                                | 1         | 0.85%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1         | 0.85%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1         | 0.85%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1         | 0.85%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 0.85%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1         | 0.85%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1         | 0.85%   |
| No brand CalDigit Pro Audio                                                       | 1         | 0.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1         | 0.85%   |
| Intel Jasper Lake HD Audio                                                        | 1         | 0.85%   |
| Intel Haswell-ULT HD Audio Controller                                             | 1         | 0.85%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 1         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 12        | 32.43%  |
| Samsung Electronics | 4         | 10.81%  |
| G.Skill             | 4         | 10.81%  |
| Unknown             | 3         | 8.11%   |
| Crucial             | 3         | 8.11%   |
| Team                | 2         | 5.41%   |
| Micron Technology   | 2         | 5.41%   |
| Unknown             | 2         | 5.41%   |
| Unknown (ABCD)      | 1         | 2.7%    |
| Kingston            | 1         | 2.7%    |
| Elpida              | 1         | 2.7%    |
| Corsair             | 1         | 2.7%    |
| Avant               | 1         | 2.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 5.41%   |
| Unknown                                                          | 2         | 5.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 2.7%    |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 2.7%    |
| Unknown RAM Module 1GB DIMM DDR 667MT/s                          | 1         | 2.7%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 2.7%    |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 2.7%    |
| Team RAM Module 16GB SODIMM DDR4 2667MT/s                        | 1         | 2.7%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.7%    |
| SK hynix RAM Module 1GB Row Of Chips LPDDR4 3733MT/s             | 1         | 2.7%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.7%    |
| SK hynix RAM HMT451R7AFR8C-RD 4GB DIMM DDR3 1866MT/s             | 1         | 2.7%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 2.7%    |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 2.7%    |
| SK hynix RAM HMAA2GU6CJR8N-XN 16GB DIMM DDR4 3200MT/s            | 1         | 2.7%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.7%    |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 2.7%    |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 1         | 2.7%    |
| Samsung RAM M471B5773DH0-CH9 2GB DDR3 1333MT/s                   | 1         | 2.7%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 2.7%    |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s            | 1         | 2.7%    |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s            | 1         | 2.7%    |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s              | 1         | 2.7%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 2.7%    |
| Kingston RAM 9905744-006.A00G 16GB SODIMM DDR4 2667MT/s          | 1         | 2.7%    |
| G.Skill RAM F4-3200C16-16GIS 16384MB DIMM DDR4 3600MT/s          | 1         | 2.7%    |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s               | 1         | 2.7%    |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2667MT/s               | 1         | 2.7%    |
| G.Skill RAM F4-2666C19-16GIS 16GB DIMM DDR4                      | 1         | 2.7%    |
| Elpida RAM EDJ8416E6MB-GN-F 4GB Chip DDR3 1600MT/s               | 1         | 2.7%    |
| Crucial RAM CT51264BD160BJ.M8F 4GB DIMM DDR3 1600MT/s            | 1         | 2.7%    |
| Crucial RAM CT16G4SFRA266.C16FR 16GB SODIMM DDR4 2667MT/s        | 1         | 2.7%    |
| Crucial RAM CT16G4DFD8266.C16FD1 16GB DIMM DDR4 2667MT/s         | 1         | 2.7%    |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s            | 1         | 2.7%    |
| Avant RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1         | 2.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 18        | 56.25%  |
| DDR3   | 8         | 25%     |
| LPDDR4 | 3         | 9.38%   |
| LPDDR5 | 2         | 6.25%   |
| DDR    | 1         | 3.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 17        | 50%     |
| DIMM         | 12        | 35.29%  |
| Row Of Chips | 3         | 8.82%   |
| Chip         | 1         | 2.94%   |
| Unknown      | 1         | 2.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 12        | 34.29%  |
| 16384 | 9         | 25.71%  |
| 4096  | 9         | 25.71%  |
| 1024  | 3         | 8.57%   |
| 32768 | 1         | 2.86%   |
| 2048  | 1         | 2.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 8         | 23.53%  |
| 2667  | 6         | 17.65%  |
| 1600  | 5         | 14.71%  |
| 2400  | 3         | 8.82%   |
| 6400  | 2         | 5.88%   |
| 3733  | 2         | 5.88%   |
| 1333  | 2         | 5.88%   |
| 4266  | 1         | 2.94%   |
| 3600  | 1         | 2.94%   |
| 3400  | 1         | 2.94%   |
| 1866  | 1         | 2.94%   |
| 1334  | 1         | 2.94%   |
| 667   | 1         | 2.94%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)

![Printer Vendor](./images/line_chart/printer_vendor.svg)

| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 66.67%  |
| Seiko Epson     | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)

![Printer Model](./images/line_chart/printer_model.svg)

| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Seiko Epson WF-2510 Series | 1         | 33.33%  |
| HP LaserJet CM1415fn       | 1         | 33.33%  |
| HP Color LaserJet CP1215   | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)

![Scanner Vendor](./images/line_chart/scanner_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)

![Scanner Model](./images/line_chart/scanner_model.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)

![Camera Vendor](./images/line_chart/camera_vendor.svg)

| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| IMC Networks                  | 7         | 15.91%  |
| Chicony Electronics           | 6         | 13.64%  |
| Acer                          | 5         | 11.36%  |
| Microdia                      | 4         | 9.09%   |
| Apple                         | 4         | 9.09%   |
| Realtek Semiconductor         | 3         | 6.82%   |
| Syntek                        | 2         | 4.55%   |
| Sunplus Innovation Technology | 2         | 4.55%   |
| Logitech                      | 2         | 4.55%   |
| Lite-On Technology            | 2         | 4.55%   |
| USB Camera CS                 | 1         | 2.27%   |
| Quanta                        | 1         | 2.27%   |
| Primax Electronics            | 1         | 2.27%   |
| Lenovo                        | 1         | 2.27%   |
| kingcome                      | 1         | 2.27%   |
| Generalplus Technology        | 1         | 2.27%   |
| ARC International             | 1         | 2.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam    | 3         | 6.67%   |
| Apple iPhone 5/5C/5S/6/SE            | 3         | 6.67%   |
| Syntek Integrated Camera             | 2         | 4.44%   |
| Realtek Integrated_Webcam_HD         | 2         | 4.44%   |
| IMC Networks USB2.0 VGA UVC WebCam   | 2         | 4.44%   |
| Acer Lenovo EasyCamera               | 2         | 4.44%   |
| Acer Integrated Camera               | 2         | 4.44%   |
| USB Camera CS USB Camera CS          | 1         | 2.22%   |
| Sunplus TOSHIBA Web Camera - HD      | 1         | 2.22%   |
| Sunplus Integrated_Webcam_HD         | 1         | 2.22%   |
| Realtek MTD camera                   | 1         | 2.22%   |
| Quanta VGA WebCam                    | 1         | 2.22%   |
| Primax HP HD Webcam [Fixed]          | 1         | 2.22%   |
| Microdia USB 2.0 Camera              | 1         | 2.22%   |
| Microdia Integrated_Webcam_HD        | 1         | 2.22%   |
| Microdia Integrated_Webcam_FHD       | 1         | 2.22%   |
| Microdia CameraA                     | 1         | 2.22%   |
| Logitech Webcam C270                 | 1         | 2.22%   |
| Logitech HD Webcam C525              | 1         | 2.22%   |
| Lite-On Integrated Camera            | 1         | 2.22%   |
| Lite-On HP Wide Vision HD Camera     | 1         | 2.22%   |
| Lite-On HP IR Camera                 | 1         | 2.22%   |
| Lenovo Integrated Webcam [R5U877]    | 1         | 2.22%   |
| kingcome 480p VGA Camera             | 1         | 2.22%   |
| IMC Networks USB2.0 UVC HD Webcam    | 1         | 2.22%   |
| IMC Networks ov9734_azurewave_camera | 1         | 2.22%   |
| Generalplus GENERAL WEBCAM           | 1         | 2.22%   |
| Chicony USB2.0 Camera                | 1         | 2.22%   |
| Chicony Integrated HP HD Webcam      | 1         | 2.22%   |
| Chicony Integrated Camera            | 1         | 2.22%   |
| Chicony HP Wide Vision HD Camera     | 1         | 2.22%   |
| Chicony HP Webcam                    | 1         | 2.22%   |
| Chicony HD Webcam                    | 1         | 2.22%   |
| ARC International Camera             | 1         | 2.22%   |
| Apple FaceTime HD Camera (Built-in)  | 1         | 2.22%   |
| Acer ThinkPad P50 Integrated Camera  | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 1         | 20%     |
| Upek                       | 1         | 20%     |
| Synaptics                  | 1         | 20%     |
| Shenzhen Goodix Technology | 1         | 20%     |
| Elan Microelectronics      | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 20%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 20%     |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 20%     |
| Elan fingerprint sensor [FeinTech FPS00200]            | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./images/line_chart/chipcard_vendor.svg)

| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)

![Chipcard Model](./images/line_chart/chipcard_model.svg)

| Model         | Computers | Percent |
|---------------|-----------|---------|
| Broadcom 5880 | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 51        | 75%     |
| 1     | 14        | 20.59%  |
| 2     | 3         | 4.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 6         | 33.33%  |
| Fingerprint reader    | 5         | 27.78%  |
| Multimedia controller | 3         | 16.67%  |
| Net/wireless          | 2         | 11.11%  |
| Firewire controller   | 1         | 5.56%   |
| Chipcard              | 1         | 5.56%   |

