Lubuntu - Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu/Desktop/README.md) and [notebooks](/Dist/Lubuntu/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/linuxhw/TestCoverage)

Period: Jul, 2022.

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

| Name          | Computers | Percent |
|---------------|-----------|---------|
| Lubuntu 22.04 | 15        | 45.45%  |
| Lubuntu 20.04 | 10        | 30.3%   |
| Lubuntu 18.04 | 6         | 18.18%  |
| Lubuntu 22.10 | 1         | 3.03%   |
| Lubuntu 12.04 | 1         | 3.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Lubuntu | 33        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 5.15.0-41-generic  | 11        | 33.33%  |
| 5.4.0-122-generic  | 4         | 12.12%  |
| 5.15.0-43-generic  | 3         | 9.09%   |
| 4.15.0-188-generic | 3         | 9.09%   |
| 5.15.0-40-generic  | 2         | 6.06%   |
| 5.15.0-25-generic  | 2         | 6.06%   |
| 4.15.0-189-generic | 2         | 6.06%   |
| 5.4.0-104-generic  | 1         | 3.03%   |
| 5.15.0-35-generic  | 1         | 3.03%   |
| 5.15.0-30-generic  | 1         | 3.03%   |
| 5.13.0-30-generic  | 1         | 3.03%   |
| 4.15.0-167-generic | 1         | 3.03%   |
| 3.13.0-185-generic | 1         | 3.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 20        | 60.61%  |
| 4.15.0  | 6         | 18.18%  |
| 5.4.0   | 5         | 15.15%  |
| 5.13.0  | 1         | 3.03%   |
| 3.13.0  | 1         | 3.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 20        | 60.61%  |
| 4.15    | 6         | 18.18%  |
| 5.4     | 5         | 15.15%  |
| 5.13    | 1         | 3.03%   |
| 3.13    | 1         | 3.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 28        | 84.85%  |
| i686   | 5         | 15.15%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| LXQt       | 23        | 69.7%   |
| LXDE       | 7         | 21.21%  |
| GNOME      | 2         | 6.06%   |
| X-Cinnamon | 1         | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 33        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 19        | 57.58%  |
| LightDM | 8         | 24.24%  |
| Unknown | 4         | 12.12%  |
| GDM3    | 1         | 3.03%   |
| GDM     | 1         | 3.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 13        | 39.39%  |
| de_DE   | 6         | 18.18%  |
| en_GB   | 3         | 9.09%   |
| it_IT   | 2         | 6.06%   |
| ru_UA   | 1         | 3.03%   |
| pl_PL   | 1         | 3.03%   |
| nl_BE   | 1         | 3.03%   |
| fr_FR   | 1         | 3.03%   |
| es_MX   | 1         | 3.03%   |
| es_ES   | 1         | 3.03%   |
| es_CL   | 1         | 3.03%   |
| es_BO   | 1         | 3.03%   |
| Unknown | 1         | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 26        | 78.79%  |
| EFI  | 7         | 21.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 31        | 93.94%  |
| Zfs   | 1         | 3.03%   |
| Btrfs | 1         | 3.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 24        | 72.73%  |
| GPT     | 5         | 15.15%  |
| MBR     | 4         | 12.12%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 81.82%  |
| Yes       | 6         | 18.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 20        | 60.61%  |
| Yes       | 13        | 39.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| MSI                 | 5         | 15.15%  |
| Dell                | 5         | 15.15%  |
| Hewlett-Packard     | 4         | 12.12%  |
| Lenovo              | 3         | 9.09%   |
| Toshiba             | 2         | 6.06%   |
| ASUSTek Computer    | 2         | 6.06%   |
| ASRock              | 2         | 6.06%   |
| Standard            | 1         | 3.03%   |
| Sony                | 1         | 3.03%   |
| Samsung Electronics | 1         | 3.03%   |
| Nokia               | 1         | 3.03%   |
| Intel               | 1         | 3.03%   |
| Google              | 1         | 3.03%   |
| Fujitsu             | 1         | 3.03%   |
| Foxconn             | 1         | 3.03%   |
| Chuwi               | 1         | 3.03%   |
| AMI                 | 1         | 3.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Dell Dimension 9100                    | 2         | 6.06%   |
| Toshiba Satellite A300                 | 1         | 3.03%   |
| Toshiba NB250                          | 1         | 3.03%   |
| Standard AHV                           | 1         | 3.03%   |
| Sony VPCEB15FM                         | 1         | 3.03%   |
| Samsung N130                           | 1         | 3.03%   |
| Nokia Booklet 3G                       | 1         | 3.03%   |
| MSI MS-7D16                            | 1         | 3.03%   |
| MSI MS-7C37                            | 1         | 3.03%   |
| MSI MS-7B09                            | 1         | 3.03%   |
| MSI MS-7721                            | 1         | 3.03%   |
| MSI ER883AA-ABA M7470N                 | 1         | 3.03%   |
| Lenovo IdeaPad S145-15IGM 81MX         | 1         | 3.03%   |
| Lenovo IdeaPad 330-15IKB 81DC          | 1         | 3.03%   |
| Lenovo G50-30 80G0                     | 1         | 3.03%   |
| Intel DQ57TM                           | 1         | 3.03%   |
| HP Presario CQ56                       | 1         | 3.03%   |
| HP Laptop 17-cn0xxx                    | 1         | 3.03%   |
| HP Compaq 8200 ELITE SMALL FORM FACTOR | 1         | 3.03%   |
| HP 245 G2                              | 1         | 3.03%   |
| Google Celes                           | 1         | 3.03%   |
| Fujitsu LIFEBOOK AH531                 | 1         | 3.03%   |
| Foxconn CQ1002DE                       | 1         | 3.03%   |
| Dell XPS M1330                         | 1         | 3.03%   |
| Dell OptiPlex 7010                     | 1         | 3.03%   |
| Dell Inspiron N5010                    | 1         | 3.03%   |
| Chuwi GemiBook Pro                     | 1         | 3.03%   |
| ASUS M5A78L LE                         | 1         | 3.03%   |
| ASUS 900                               | 1         | 3.03%   |
| ASRock M3A785GMH/128M                  | 1         | 3.03%   |
| ASRock A75M-HVS                        | 1         | 3.03%   |
| AMI Z83-V                              | 1         | 3.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo IdeaPad    | 2         | 6.06%   |
| Dell Dimension    | 2         | 6.06%   |
| Toshiba Satellite | 1         | 3.03%   |
| Toshiba NB250     | 1         | 3.03%   |
| Standard AHV      | 1         | 3.03%   |
| Sony VPCEB15FM    | 1         | 3.03%   |
| Samsung N130      | 1         | 3.03%   |
| Nokia Booklet     | 1         | 3.03%   |
| MSI MS-7D16       | 1         | 3.03%   |
| MSI MS-7C37       | 1         | 3.03%   |
| MSI MS-7B09       | 1         | 3.03%   |
| MSI MS-7721       | 1         | 3.03%   |
| MSI ER883AA-ABA   | 1         | 3.03%   |
| Lenovo G50-30     | 1         | 3.03%   |
| Intel DQ57TM      | 1         | 3.03%   |
| HP Presario       | 1         | 3.03%   |
| HP Laptop         | 1         | 3.03%   |
| HP Compaq         | 1         | 3.03%   |
| HP 245            | 1         | 3.03%   |
| Google Celes      | 1         | 3.03%   |
| Fujitsu LIFEBOOK  | 1         | 3.03%   |
| Foxconn CQ1002DE  | 1         | 3.03%   |
| Dell XPS          | 1         | 3.03%   |
| Dell OptiPlex     | 1         | 3.03%   |
| Dell Inspiron     | 1         | 3.03%   |
| Chuwi GemiBook    | 1         | 3.03%   |
| ASUS M5A78L       | 1         | 3.03%   |
| ASUS 900          | 1         | 3.03%   |
| ASRock M3A785GMH  | 1         | 3.03%   |
| ASRock A75M-HVS   | 1         | 3.03%   |
| AMI Z83-V         | 1         | 3.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 5         | 15.15%  |
| 2010 | 4         | 12.12%  |
| 2021 | 3         | 9.09%   |
| 2013 | 3         | 9.09%   |
| 2009 | 3         | 9.09%   |
| 2008 | 3         | 9.09%   |
| 2006 | 3         | 9.09%   |
| 2019 | 2         | 6.06%   |
| 2017 | 2         | 6.06%   |
| 2020 | 1         | 3.03%   |
| 2018 | 1         | 3.03%   |
| 2016 | 1         | 3.03%   |
| 2014 | 1         | 3.03%   |
| 2012 | 1         | 3.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 18        | 54.55%  |
| Desktop  | 15        | 45.45%  |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 31        | 93.94%  |
| Enabled  | 2         | 6.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 32        | 96.97%  |
| Yes  | 1         | 3.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 10        | 30.3%   |
| 0.51-1.0    | 7         | 21.21%  |
| 4.01-8.0    | 5         | 15.15%  |
| 8.01-16.0   | 4         | 12.12%  |
| 2.01-3.0    | 2         | 6.06%   |
| 16.01-24.0  | 2         | 6.06%   |
| 32.01-64.0  | 1         | 3.03%   |
| 64.01-256.0 | 1         | 3.03%   |
| 1.01-2.0    | 1         | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 13        | 39.39%  |
| 2.01-3.0   | 8         | 24.24%  |
| 0.51-1.0   | 6         | 18.18%  |
| 0.01-0.5   | 2         | 6.06%   |
| 4.01-8.0   | 1         | 3.03%   |
| 32.01-64.0 | 1         | 3.03%   |
| 3.01-4.0   | 1         | 3.03%   |
| Unknown    | 1         | 3.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 19        | 57.58%  |
| 2      | 8         | 24.24%  |
| 5      | 2         | 6.06%   |
| 17     | 1         | 3.03%   |
| 6      | 1         | 3.03%   |
| 4      | 1         | 3.03%   |
| 3      | 1         | 3.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 18        | 54.55%  |
| Yes       | 15        | 45.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 84.85%  |
| No        | 5         | 15.15%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 81.82%  |
| No        | 6         | 18.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 20        | 60.61%  |
| Yes       | 13        | 39.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country   | Computers | Percent |
|-----------|-----------|---------|
| USA       | 7         | 21.21%  |
| Germany   | 7         | 21.21%  |
| UK        | 3         | 9.09%   |
| Italy     | 2         | 6.06%   |
| Vietnam   | 1         | 3.03%   |
| Ukraine   | 1         | 3.03%   |
| Slovakia  | 1         | 3.03%   |
| Russia    | 1         | 3.03%   |
| Poland    | 1         | 3.03%   |
| Mexico    | 1         | 3.03%   |
| Ireland   | 1         | 3.03%   |
| France    | 1         | 3.03%   |
| Egypt     | 1         | 3.03%   |
| Chile     | 1         | 3.03%   |
| Bulgaria  | 1         | 3.03%   |
| Bolivia   | 1         | 3.03%   |
| Belgium   | 1         | 3.03%   |
| Argentina | 1         | 3.03%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Largo                  | 2         | 6.06%   |
| Cossington             | 2         | 6.06%   |
| Zeuthen                | 1         | 3.03%   |
| Wetteren               | 1         | 3.03%   |
| Varna                  | 1         | 3.03%   |
| Strzyzow               | 1         | 3.03%   |
| Stedesand              | 1         | 3.03%   |
| Southampton            | 1         | 3.03%   |
| South Burlington       | 1         | 3.03%   |
| Sonico                 | 1         | 3.03%   |
| Santiago               | 1         | 3.03%   |
| Saint Paul             | 1         | 3.03%   |
| Rossano Veneto         | 1         | 3.03%   |
| Nitra                  | 1         | 3.03%   |
| Münster               | 1         | 3.03%   |
| Moscow                 | 1         | 3.03%   |
| Montigny-le-Bretonneux | 1         | 3.03%   |
| Mexico City            | 1         | 3.03%   |
| Maipu                  | 1         | 3.03%   |
| La Paz                 | 1         | 3.03%   |
| Kyiv                   | 1         | 3.03%   |
| Ho Chi Minh City       | 1         | 3.03%   |
| Giessen                | 1         | 3.03%   |
| Garbsen                | 1         | 3.03%   |
| Dublin                 | 1         | 3.03%   |
| Chicago                | 1         | 3.03%   |
| Castrop-Rauxel         | 1         | 3.03%   |
| Cairo                  | 1         | 3.03%   |
| Bradford               | 1         | 3.03%   |
| Bloomington            | 1         | 3.03%   |
| Battenberg             | 1         | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 11     | 13.73%  |
| Seagate             | 7         | 8      | 13.73%  |
| Toshiba             | 6         | 6      | 11.76%  |
| Samsung Electronics | 6         | 9      | 11.76%  |
| Hitachi             | 4         | 4      | 7.84%   |
| Crucial             | 3         | 15     | 5.88%   |
| Unknown             | 2         | 2      | 3.92%   |
| SanDisk             | 2         | 2      | 3.92%   |
| HGST                | 2         | 2      | 3.92%   |
| W800S               | 1         | 1      | 1.96%   |
| TO Exter            | 1         | 1      | 1.96%   |
| Team                | 1         | 1      | 1.96%   |
| SPCC                | 1         | 1      | 1.96%   |
| SK hynix            | 1         | 1      | 1.96%   |
| Kingston            | 1         | 2      | 1.96%   |
| Intenso             | 1         | 1      | 1.96%   |
| Hewlett-Packard     | 1         | 2      | 1.96%   |
| China               | 1         | 1      | 1.96%   |
| ASUS-PHISON         | 1         | 1      | 1.96%   |
| Apricorn            | 1         | 1      | 1.96%   |
| A-DATA Technology   | 1         | 1      | 1.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB                      | 2         | 3.39%   |
| Seagate ST3120213AS 120GB                   | 2         | 3.39%   |
| WDC WDS100T1X0E-00AFY0 1TB                  | 1         | 1.69%   |
| WDC WD5000AAKX-75U6AA0 500GB                | 1         | 1.69%   |
| WDC WD5000AAKX-07U6AA0 500GB                | 1         | 1.69%   |
| WDC WD3200BEVT-75A23T0 320GB                | 1         | 1.69%   |
| WDC WD30EZRZ-00GXCB0 3TB                    | 1         | 1.69%   |
| WDC WD20EZBX-00AYRA0 2TB                    | 1         | 1.69%   |
| WDC WD10TPVT-00HT5T0 1TB                    | 1         | 1.69%   |
| WDC WD10SPZX-24Z10T0 1TB                    | 1         | 1.69%   |
| WDC WD10EZRZ-00Z5HB0 1TB                    | 1         | 1.69%   |
| WDC WD10EURX-63C57Y0 1TB                    | 1         | 1.69%   |
| WDC WD1001FALS-41K1B0 1TB                   | 1         | 1.69%   |
| W800S 256GB SSD                             | 1         | 1.69%   |
| Unknown MMC Card  32GB                      | 1         | 1.69%   |
| Unknown DA4064  64GB                        | 1         | 1.69%   |
| Toshiba MK2565GSXV 250GB                    | 1         | 1.69%   |
| Toshiba MK2546GSX 250GB                     | 1         | 1.69%   |
| Toshiba MK1646GSX 160GB                     | 1         | 1.69%   |
| Toshiba MK1235GSL 120GB                     | 1         | 1.69%   |
| TO Exter nal USB 3.0 1TB                    | 1         | 1.69%   |
| Team TM8PS7256G 256GB SSD                   | 1         | 1.69%   |
| SPCC Solid State Disk 120GB                 | 1         | 1.69%   |
| SK hynix NVMe SSD Drive 256GB               | 1         | 1.69%   |
| Seagate ST500DM002-1BD142 500GB             | 1         | 1.69%   |
| Seagate ST360012A 64GB                      | 1         | 1.69%   |
| Seagate ST2000VN000-1HJ164 2TB              | 1         | 1.69%   |
| Seagate ST2000NE001-2M5101 2TB              | 1         | 1.69%   |
| Seagate ST1000DX001-1CM162 1TB              | 1         | 1.69%   |
| Seagate FireCuda 520 SSD ZP500GM30002 500GB | 1         | 1.69%   |
| SanDisk SSD PLUS 120GB                      | 1         | 1.69%   |
| SanDisk DF4032  32GB                        | 1         | 1.69%   |
| Samsung SSD 970 EVO 500GB                   | 1         | 1.69%   |
| Samsung SSD 840 Series 120GB                | 1         | 1.69%   |
| Samsung NVMe SSD Drive 512GB                | 1         | 1.69%   |
| Samsung NVMe SSD Drive 500GB                | 1         | 1.69%   |
| Samsung MZ7LN128HAHQ-000L2 128GB SSD        | 1         | 1.69%   |
| Samsung HD502IJ 500GB                       | 1         | 1.69%   |
| Samsung HD502HJ 500GB                       | 1         | 1.69%   |
| Samsung HD103SI 1TB                         | 1         | 1.69%   |
| Kingston SV300S37A120G 120GB SSD            | 1         | 1.69%   |
| Intenso SSD Sata III 960GB                  | 1         | 1.69%   |
| Hitachi HTS545032B9SA00 320GB               | 1         | 1.69%   |
| Hitachi HTS545032B9A300 320GB               | 1         | 1.69%   |
| Hitachi HDS721616PLA380 160GB               | 1         | 1.69%   |
| Hitachi HDS721010CLA632 1TB                 | 1         | 1.69%   |
| HGST HTS545050A7E680 500GB                  | 1         | 1.69%   |
| HGST HTS545032A7E380 320GB                  | 1         | 1.69%   |
| HP SSD S700 1TB                             | 1         | 1.69%   |
| Crucial CT960BX500SSD1 960GB                | 1         | 1.69%   |
| Crucial CT240BX500SSD1 240GB                | 1         | 1.69%   |
| Crucial CT240BX200SSD1 240GB                | 1         | 1.69%   |
| Crucial CT1000BX500SSD1 1TB                 | 1         | 1.69%   |
| China SH00R480GB SSD                        | 1         | 1.69%   |
| ASUS-PHISON SSD 16GB                        | 1         | 1.69%   |
| Apricorn SATAWire 6G                        | 1         | 1.69%   |
| A-DATA SU800 1024GB SSD                     | 1         | 1.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 10     | 24.14%  |
| Seagate             | 7         | 7      | 24.14%  |
| Toshiba             | 6         | 6      | 20.69%  |
| Hitachi             | 4         | 4      | 13.79%  |
| Samsung Electronics | 2         | 3      | 6.9%    |
| HGST                | 2         | 2      | 6.9%    |
| Apricorn            | 1         | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 3         | 15     | 18.75%  |
| Samsung Electronics | 2         | 2      | 12.5%   |
| W800S               | 1         | 1      | 6.25%   |
| TO Exter            | 1         | 1      | 6.25%   |
| Team                | 1         | 1      | 6.25%   |
| SPCC                | 1         | 1      | 6.25%   |
| SanDisk             | 1         | 1      | 6.25%   |
| Kingston            | 1         | 2      | 6.25%   |
| Intenso             | 1         | 1      | 6.25%   |
| Hewlett-Packard     | 1         | 2      | 6.25%   |
| China               | 1         | 1      | 6.25%   |
| ASUS-PHISON         | 1         | 1      | 6.25%   |
| A-DATA Technology   | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 33     | 48.78%  |
| SSD  | 14        | 30     | 34.15%  |
| NVMe | 4         | 7      | 9.76%   |
| MMC  | 3         | 3      | 7.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 29        | 61     | 78.38%  |
| NVMe | 4         | 7      | 10.81%  |
| MMC  | 3         | 3      | 8.11%   |
| SAS  | 1         | 2      | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 23        | 30     | 60.53%  |
| 0.51-1.0   | 10        | 27     | 26.32%  |
| 1.01-2.0   | 4         | 5      | 10.53%  |
| 2.01-3.0   | 1         | 1      | 2.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 8         | 24.24%  |
| 101-250        | 8         | 24.24%  |
| 21-50          | 4         | 12.12%  |
| 501-1000       | 3         | 9.09%   |
| 51-100         | 3         | 9.09%   |
| 2001-3000      | 2         | 6.06%   |
| 1001-2000      | 2         | 6.06%   |
| 1-20           | 2         | 6.06%   |
| More than 3000 | 1         | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 16        | 48.48%  |
| 21-50     | 8         | 24.24%  |
| 501-1000  | 4         | 12.12%  |
| 101-250   | 2         | 6.06%   |
| 1001-2000 | 2         | 6.06%   |
| 51-100    | 1         | 3.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-75A23T0 320GB      | 1         | 1      | 20%     |
| Seagate ST360012A 64GB            | 1         | 1      | 20%     |
| SanDisk SSD PLUS 120GB            | 1         | 1      | 20%     |
| Samsung Electronics HD502IJ 500GB | 1         | 1      | 20%     |
| Hitachi HTS545032B9A300 320GB     | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 20%     |
| Seagate             | 1         | 1      | 20%     |
| SanDisk             | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| Hitachi             | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 25%     |
| Seagate             | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |
| Hitachi             | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 4      | 75%     |
| SSD  | 1         | 1      | 25%     |

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
| Detected | 27        | 55     | 79.41%  |
| Works    | 4         | 13     | 11.76%  |
| Malfunc  | 3         | 5      | 8.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 22        | 57.89%  |
| AMD                      | 9         | 23.68%  |
| Samsung Electronics      | 2         | 5.26%   |
| SK hynix                 | 1         | 2.63%   |
| Seagate Technology       | 1         | 2.63%   |
| SanDisk                  | 1         | 2.63%   |
| Marvell Technology Group | 1         | 2.63%   |
| ASMedia Technology       | 1         | 2.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 5         | 9.8%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3         | 5.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 3.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 3.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 3.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 3.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 3.92%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1         | 1.96%   |
| Seagate FireCuda 520 SSD                                                                | 1         | 1.96%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1         | 1.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 1.96%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 1.96%   |
| Marvell Group 88SE9480 SAS/SATA 6Gb/s RAID controller                                   | 1         | 1.96%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1         | 1.96%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                              | 1         | 1.96%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 1         | 1.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1         | 1.96%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1         | 1.96%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 1         | 1.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 1.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 1.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 1.96%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1         | 1.96%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                  | 1         | 1.96%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1         | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.96%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1         | 1.96%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 1.96%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1         | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1         | 1.96%   |
| AMD IXP SB4x0 Serial ATA Controller                                                     | 1         | 1.96%   |
| AMD IXP SB4x0 IDE Controller                                                            | 1         | 1.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 25        | 58.14%  |
| IDE  | 12        | 27.91%  |
| NVMe | 4         | 9.3%    |
| RAID | 2         | 4.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 24        | 72.73%  |
| AMD    | 9         | 27.27%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Pentium D CPU 2.80GHz                    | 2         | 6.06%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz    | 1         | 3.03%   |
| Intel Core i7-2620M CPU @ 2.70GHz              | 1         | 3.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz              | 1         | 3.03%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1         | 3.03%   |
| Intel Core i5-2410M CPU @ 2.30GHz              | 1         | 3.03%   |
| Intel Core i5 CPU M 520 @ 2.40GHz              | 1         | 3.03%   |
| Intel Core i5 CPU 650 @ 3.20GHz                | 1         | 3.03%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1         | 3.03%   |
| Intel Core i3-10100F CPU @ 3.60GHz             | 1         | 3.03%   |
| Intel Core i3 CPU M 380 @ 2.53GHz              | 1         | 3.03%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz           | 1         | 3.03%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz           | 1         | 3.03%   |
| Intel Celeron N5100 @ 1.10GHz                  | 1         | 3.03%   |
| Intel Celeron N4000 CPU @ 1.10GHz              | 1         | 3.03%   |
| Intel Celeron M processor 900MHz               | 1         | 3.03%   |
| Intel Celeron CPU N3060 @ 1.60GHz              | 1         | 3.03%   |
| Intel Celeron CPU N2830 @ 2.16GHz              | 1         | 3.03%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz              | 1         | 3.03%   |
| Intel Atom CPU Z530 @ 1.60GHz                  | 1         | 3.03%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 1         | 3.03%   |
| Intel Atom CPU N270 @ 1.60GHz                  | 1         | 3.03%   |
| Intel 11th Gen Core i3-1125G4 @ 2.00GHz        | 1         | 3.03%   |
| AMD Ryzen Threadripper 2950X 16-Core Processor | 1         | 3.03%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 1         | 3.03%   |
| AMD Phenom II X4 965 Processor                 | 1         | 3.03%   |
| AMD FX-6300 Six-Core Processor                 | 1         | 3.03%   |
| AMD E1-2100 APU with Radeon HD Graphics        | 1         | 3.03%   |
| AMD E-350 Processor                            | 1         | 3.03%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+     | 1         | 3.03%   |
| AMD A8-6600K APU with Radeon HD Graphics       | 1         | 3.03%   |
| AMD A8-3850 APU with Radeon HD Graphics        | 1         | 3.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 5         | 15.15%  |
| Intel Celeron           | 4         | 12.12%  |
| Intel Atom              | 4         | 12.12%  |
| Intel Core i3           | 3         | 9.09%   |
| Intel Pentium D         | 2         | 6.06%   |
| Intel Core 2 Duo        | 2         | 6.06%   |
| AMD A8                  | 2         | 6.06%   |
| Other                   | 1         | 3.03%   |
| Intel Pentium Dual-Core | 1         | 3.03%   |
| Intel Core i7           | 1         | 3.03%   |
| Intel Celeron M         | 1         | 3.03%   |
| AMD Ryzen Threadripper  | 1         | 3.03%   |
| AMD Ryzen 7             | 1         | 3.03%   |
| AMD Phenom II X4        | 1         | 3.03%   |
| AMD FX                  | 1         | 3.03%   |
| AMD E1                  | 1         | 3.03%   |
| AMD E                   | 1         | 3.03%   |
| AMD Athlon 64 X2        | 1         | 3.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 19        | 57.58%  |
| 4      | 7         | 21.21%  |
| 1      | 4         | 12.12%  |
| 16     | 1         | 3.03%   |
| 8      | 1         | 3.03%   |
| 3      | 1         | 3.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 33        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 17        | 51.52%  |
| 2      | 16        | 48.48%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 30        | 90.91%  |
| 32-bit         | 3         | 9.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 33.33%  |
| 0x6fd      | 2         | 6.06%   |
| 0x406c4    | 2         | 6.06%   |
| 0x20655    | 2         | 6.06%   |
| 0x106c2    | 2         | 6.06%   |
| 0xa0653    | 1         | 3.03%   |
| 0x906c0    | 1         | 3.03%   |
| 0x806e9    | 1         | 3.03%   |
| 0x806c1    | 1         | 3.03%   |
| 0x6d8      | 1         | 3.03%   |
| 0x206a7    | 1         | 3.03%   |
| 0x106ca    | 1         | 3.03%   |
| 0x1067a    | 1         | 3.03%   |
| 0x0a201009 | 1         | 3.03%   |
| 0x0800820d | 1         | 3.03%   |
| 0x0700010f | 1         | 3.03%   |
| 0x06001119 | 1         | 3.03%   |
| 0x05000029 | 1         | 3.03%   |
| 0x010000c8 | 1         | 3.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| Westmere      | 3         | 9.09%   |
| Silvermont    | 3         | 9.09%   |
| SandyBridge   | 3         | 9.09%   |
| Bonnell       | 3         | 9.09%   |
| Piledriver    | 2         | 6.06%   |
| NetBurst      | 2         | 6.06%   |
| Core          | 2         | 6.06%   |
| Zen+          | 1         | 3.03%   |
| Zen 3         | 1         | 3.03%   |
| Tremont       | 1         | 3.03%   |
| TigerLake     | 1         | 3.03%   |
| Penryn        | 1         | 3.03%   |
| P6            | 1         | 3.03%   |
| KabyLake      | 1         | 3.03%   |
| K8 Hammer     | 1         | 3.03%   |
| K10 Llano     | 1         | 3.03%   |
| K10           | 1         | 3.03%   |
| Jaguar        | 1         | 3.03%   |
| IvyBridge     | 1         | 3.03%   |
| Goldmont plus | 1         | 3.03%   |
| CometLake     | 1         | 3.03%   |
| Bobcat        | 1         | 3.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 20        | 57.14%  |
| Nvidia | 8         | 22.86%  |
| AMD    | 7         | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 7.5%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 5%      |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 5%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 5%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 5%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 5%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 5%      |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                                    | 2         | 5%      |
| AMD RV370 [Radeon X600/X600 SE]                                                          | 2         | 5%      |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 2.5%    |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 2.5%    |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 1         | 2.5%    |
| Nvidia G86 [Quadro NVS 290]                                                              | 1         | 2.5%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 2.5%    |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                      | 1         | 2.5%    |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 2.5%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 2.5%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 2.5%    |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 1         | 2.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.5%    |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 2.5%    |
| Intel HD Graphics 620                                                                    | 1         | 2.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 2.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 2.5%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 2.5%    |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 2.5%    |
| AMD RS480 [Radeon Xpress 200 Series]                                                     | 1         | 2.5%    |
| AMD Richland [Radeon HD 8570D]                                                           | 1         | 2.5%    |
| AMD Kabini [Radeon HD 8210]                                                              | 1         | 2.5%    |
| AMD Juniper XT [Radeon HD 5770]                                                          | 1         | 2.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 54.55%  |
| 1 x Nvidia     | 7         | 21.21%  |
| 1 x AMD        | 5         | 15.15%  |
| 2 x AMD        | 2         | 6.06%   |
| Intel + Nvidia | 1         | 3.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 28        | 84.85%  |
| Proprietary | 3         | 9.09%   |
| Unknown     | 2         | 6.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 63.64%  |
| 0.01-0.5   | 6         | 18.18%  |
| 3.01-4.0   | 2         | 6.06%   |
| 1.01-2.0   | 2         | 6.06%   |
| 7.01-8.0   | 1         | 3.03%   |
| 0.51-1.0   | 1         | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 17.86%  |
| LG Display          | 5         | 17.86%  |
| Chimei Innolux      | 4         | 14.29%  |
| Hewlett-Packard     | 3         | 10.71%  |
| AU Optronics        | 2         | 7.14%   |
| Videoseven          | 1         | 3.57%   |
| Toshiba             | 1         | 3.57%   |
| SHD                 | 1         | 3.57%   |
| HannStar            | 1         | 3.57%   |
| Goldstar            | 1         | 3.57%   |
| Dell                | 1         | 3.57%   |
| CPT                 | 1         | 3.57%   |
| BenQ                | 1         | 3.57%   |
| Acer                | 1         | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Videoseven L19FM IGM0812 1280x1024 376x301mm 19.0-inch               | 1         | 3.57%   |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch             | 1         | 3.57%   |
| SHD 701Lite SHD02BD 1920x1080 110x62mm 5.0-inch                      | 1         | 3.57%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SEC544E 1024x600 223x125mm 10.1-inch | 1         | 3.57%   |
| Samsung Electronics LC27G7xT SAM105C 2560x1440 597x336mm 27.0-inch   | 1         | 3.57%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 1         | 3.57%   |
| LG Display LCD Monitor LGD044B 1366x768 344x194mm 15.5-inch          | 1         | 3.57%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch          | 1         | 3.57%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 1         | 3.57%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 1         | 3.57%   |
| LG Display LCD Monitor LGD02CF 1366x768 344x194mm 15.5-inch          | 1         | 3.57%   |
| Hewlett-Packard W2071d HWP299E 1600x900 443x249mm 20.0-inch          | 1         | 3.57%   |
| Hewlett-Packard E201 HWP305E 1600x900 443x249mm 20.0-inch            | 1         | 3.57%   |
| Hewlett-Packard 2011 HWP2935 1600x900 443x249mm 20.0-inch            | 1         | 3.57%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch             | 1         | 3.57%   |
| Goldstar L1952T GSM4AE1 1280x1024 376x301mm 19.0-inch                | 1         | 3.57%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                   | 1         | 3.57%   |
| CPT LCD Monitor CPT1401 1280x800 331x207mm 15.4-inch                 | 1         | 3.57%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch     | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN176F 1920x1080 381x214mm 17.2-inch     | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 1         | 3.57%   |
| BenQ FP93GX BNQ76D5 1280x1024 376x301mm 19.0-inch                    | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO11D5 1280x720 222x125mm 10.0-inch        | 1         | 3.57%   |
| Acer EB490QK ACR061A 3840x2160 1074x604mm 48.5-inch                  | 1         | 3.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 8         | 29.63%  |
| 1920x1080 (FHD)  | 5         | 18.52%  |
| 1600x900 (HD+)   | 3         | 11.11%  |
| 1280x1024 (SXGA) | 3         | 11.11%  |
| 1280x800 (WXGA)  | 2         | 7.41%   |
| 1024x600         | 2         | 7.41%   |
| 3840x2160 (4K)   | 1         | 3.7%    |
| 2560x1440 (QHD)  | 1         | 3.7%    |
| 2160x1440        | 1         | 3.7%    |
| 1280x720 (HD)    | 1         | 3.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 7         | 25%     |
| 20     | 3         | 10.71%  |
| 19     | 3         | 10.71%  |
| 14     | 3         | 10.71%  |
| 10     | 3         | 10.71%  |
| 27     | 2         | 7.14%   |
| 48     | 1         | 3.57%   |
| 23     | 1         | 3.57%   |
| 21     | 1         | 3.57%   |
| 17     | 1         | 3.57%   |
| 13     | 1         | 3.57%   |
| 11     | 1         | 3.57%   |
| 5      | 1         | 3.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 9         | 32.14%  |
| 201-300     | 6         | 21.43%  |
| 401-500     | 4         | 14.29%  |
| 351-400     | 4         | 14.29%  |
| 501-600     | 3         | 10.71%  |
| 101-200     | 1         | 3.57%   |
| 1001-1500   | 1         | 3.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 21        | 77.78%  |
| 5/4   | 3         | 11.11%  |
| 16/10 | 2         | 7.41%   |
| 3/2   | 1         | 3.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 7         | 25.93%  |
| 151-200        | 6         | 22.22%  |
| 81-90          | 4         | 14.81%  |
| 41-50          | 3         | 11.11%  |
| 301-350        | 2         | 7.41%   |
| More than 1000 | 1         | 3.7%    |
| 51-60          | 1         | 3.7%    |
| 1-40           | 1         | 3.7%    |
| 201-250        | 1         | 3.7%    |
| 121-130        | 1         | 3.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 12        | 42.86%  |
| 51-100        | 10        | 35.71%  |
| 121-160       | 4         | 14.29%  |
| More than 240 | 1         | 3.57%   |
| 161-240       | 1         | 3.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 30        | 90.91%  |
| 0     | 2         | 6.06%   |
| 2     | 1         | 3.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 19        | 36.54%  |
| Intel                    | 14        | 26.92%  |
| Qualcomm Atheros         | 7         | 13.46%  |
| Marvell Technology Group | 2         | 3.85%   |
| Broadcom                 | 2         | 3.85%   |
| TP-Link                  | 1         | 1.92%   |
| Samsung Electronics      | 1         | 1.92%   |
| Ralink Technology        | 1         | 1.92%   |
| Ralink                   | 1         | 1.92%   |
| MediaTek                 | 1         | 1.92%   |
| JMicron Technology       | 1         | 1.92%   |
| Broadcom Limited         | 1         | 1.92%   |
| ADMtek                   | 1         | 1.92%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 8         | 14.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 10.53%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 3         | 5.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 3.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 2         | 3.51%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 2         | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 3.51%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller            | 2         | 3.51%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                          | 1         | 1.75%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1         | 1.75%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                    | 1         | 1.75%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                        | 1         | 1.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 1         | 1.75%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 1.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.75%   |
| Realtek 802.11ac NIC                                                           | 1         | 1.75%   |
| Ralink RT5370 Wireless Adapter                                                 | 1         | 1.75%   |
| Ralink RT2561/RT61 802.11g PCI                                                 | 1         | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 1         | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 1         | 1.75%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1         | 1.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 1.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 1.75%   |
| MediaTek moto e(6) plus                                                        | 1         | 1.75%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.75%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 1.75%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 1.75%   |
| Intel Wireless 7265                                                            | 1         | 1.75%   |
| Intel Wireless 3165                                                            | 1         | 1.75%   |
| Intel Wi-Fi 6 AX200                                                            | 1         | 1.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 1         | 1.75%   |
| Intel I211 Gigabit Network Connection                                          | 1         | 1.75%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 1         | 1.75%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 1         | 1.75%   |
| Intel 82578DM Gigabit Network Connection                                       | 1         | 1.75%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 1.75%   |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100                           | 1         | 1.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 8         | 29.63%  |
| Realtek Semiconductor | 7         | 25.93%  |
| Qualcomm Atheros      | 7         | 25.93%  |
| Broadcom              | 2         | 7.41%   |
| TP-Link               | 1         | 3.7%    |
| Ralink Technology     | 1         | 3.7%    |
| Ralink                | 1         | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 11.11%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 7.41%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 7.41%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller     | 2         | 7.41%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1         | 3.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 3.7%    |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 3.7%    |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                 | 1         | 3.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 3.7%    |
| Realtek 802.11ac NIC                                                    | 1         | 3.7%    |
| Ralink RT5370 Wireless Adapter                                          | 1         | 3.7%    |
| Ralink RT2561/RT61 802.11g PCI                                          | 1         | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 3.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 3.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 3.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 3.7%    |
| Intel Wireless 7265                                                     | 1         | 3.7%    |
| Intel Wireless 3165                                                     | 1         | 3.7%    |
| Intel Wi-Fi 6 AX200                                                     | 1         | 3.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 3.7%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 3.7%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 16        | 53.33%  |
| Intel                    | 6         | 20%     |
| Marvell Technology Group | 2         | 6.67%   |
| Samsung Electronics      | 1         | 3.33%   |
| Qualcomm Atheros         | 1         | 3.33%   |
| MediaTek                 | 1         | 3.33%   |
| JMicron Technology       | 1         | 3.33%   |
| Broadcom Limited         | 1         | 3.33%   |
| ADMtek                   | 1         | 3.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 8         | 26.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 20%     |
| Intel NM10/ICH7 Family LAN Controller                                          | 2         | 6.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 6.67%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 3.33%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 3.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 3.33%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1         | 3.33%   |
| MediaTek moto e(6) plus                                                        | 1         | 3.33%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 3.33%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 3.33%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 3.33%   |
| Intel I211 Gigabit Network Connection                                          | 1         | 3.33%   |
| Intel 82578DM Gigabit Network Connection                                       | 1         | 3.33%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 3.33%   |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100                           | 1         | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 28        | 50.91%  |
| WiFi     | 27        | 49.09%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 18        | 56.25%  |
| Ethernet | 14        | 43.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 17        | 51.52%  |
| 1     | 14        | 42.42%  |
| 3     | 1         | 3.03%   |
| 0     | 1         | 3.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 25        | 75.76%  |
| Yes  | 8         | 24.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 5         | 38.46%  |
| Realtek Semiconductor           | 3         | 23.08%  |
| Qualcomm Atheros Communications | 2         | 15.38%  |
| Toshiba                         | 1         | 7.69%   |
| Foxconn / Hon Hai               | 1         | 7.69%   |
| Dell                            | 1         | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                                                             | 2         | 15.38%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 15.38%  |
| Intel Bluetooth wireless interface                                                  | 2         | 15.38%  |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 7.69%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 7.69%   |
| Intel Bluetooth Device                                                              | 1         | 7.69%   |
| Intel AX201 Bluetooth                                                               | 1         | 7.69%   |
| Intel AX200 Bluetooth                                                               | 1         | 7.69%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 7.69%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 23        | 58.97%  |
| AMD                 | 8         | 20.51%  |
| Nvidia              | 6         | 15.38%  |
| Creative Labs       | 1         | 2.56%   |
| C-Media Electronics | 1         | 2.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 9.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 7.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 7.14%   |
| AMD FCH Azalia Controller                                                                         | 3         | 7.14%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 4.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 4.76%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 4.76%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 4.76%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 2.38%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 2.38%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 2.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 2.38%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 2.38%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 2.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 2.38%   |
| Intel Audio device                                                                                | 1         | 2.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 2.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 2.38%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 2.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 2.38%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1         | 2.38%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                     | 1         | 2.38%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 2.38%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 2.38%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 2.38%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 1         | 2.38%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 1         | 2.38%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 2.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 6         | 33.33%  |
| SK hynix            | 5         | 27.78%  |
| Samsung Electronics | 3         | 16.67%  |
| G.Skill             | 2         | 11.11%  |
| Nanya Technology    | 1         | 5.56%   |
| Micron Technology   | 1         | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8192MB DIMM 667MT/s                         | 1         | 5.26%   |
| Unknown RAM Module 4GB SODIMM DDR3                             | 1         | 5.26%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 1         | 5.26%   |
| Unknown RAM Module 1GB SODIMM DDR2                             | 1         | 5.26%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                  | 1         | 5.26%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s                  | 1         | 5.26%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                     | 1         | 5.26%   |
| SK hynix RAM HYMP125S64CR8-S6 2GB SODIMM DDR2 800MT/s          | 1         | 5.26%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s           | 1         | 5.26%   |
| SK hynix RAM HYMP112S64CR6-S6 1024MB SODIMM DDR2 800MT/s       | 1         | 5.26%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 5.26%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 1         | 5.26%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 5.26%   |
| Samsung RAM M471B2873FHS-CH9 1024MB SODIMM DDR3 1334MT/s       | 1         | 5.26%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                | 1         | 5.26%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s           | 1         | 5.26%   |
| Micron RAM 53E1G32D4NQ-046WTE 4GB Row Of Chips LPDDR4 3200MT/s | 1         | 5.26%   |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 3600MT/s            | 1         | 5.26%   |
| G.Skill RAM F4-2400C15-4GVR 4096MB DIMM DDR4 2134MT/s          | 1         | 5.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR2    | 6         | 35.29%  |
| DDR3    | 5         | 29.41%  |
| LPDDR4  | 2         | 11.76%  |
| DDR4    | 2         | 11.76%  |
| LPDDR3  | 1         | 5.88%   |
| Unknown | 1         | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 64.71%  |
| DIMM         | 4         | 23.53%  |
| Row Of Chips | 1         | 5.88%   |
| Unknown      | 1         | 5.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size | Computers | Percent |
|------|-----------|---------|
| 4096 | 6         | 31.58%  |
| 2048 | 5         | 26.32%  |
| 1024 | 5         | 26.32%  |
| 8192 | 3         | 15.79%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 2         | 11.76%  |
| 667     | 2         | 11.76%  |
| Unknown | 2         | 11.76%  |
| 3600    | 1         | 5.88%   |
| 3200    | 1         | 5.88%   |
| 2667    | 1         | 5.88%   |
| 2400    | 1         | 5.88%   |
| 1867    | 1         | 5.88%   |
| 1334    | 1         | 5.88%   |
| 1066    | 1         | 5.88%   |
| 975     | 1         | 5.88%   |
| 800     | 1         | 5.88%   |
| 533     | 1         | 5.88%   |
| 400     | 1         | 5.88%   |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)

![Scanner Vendor](./images/line_chart/scanner_vendor.svg)

| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)

![Scanner Model](./images/line_chart/scanner_model.svg)

| Model           | Computers | Percent |
|-----------------|-----------|---------|
| HP scanjet 8270 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)

![Camera Vendor](./images/line_chart/camera_vendor.svg)

| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 6         | 35.29%  |
| Microdia                               | 5         | 29.41%  |
| Z-Star Microelectronics                | 1         | 5.88%   |
| Luxvisions Innotech Limited            | 1         | 5.88%   |
| IMC Networks                           | 1         | 5.88%   |
| Genesys Logic                          | 1         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5.88%   |
| AVerMedia Technologies                 | 1         | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Microdia Webcam                                      | 2         | 11.76%  |
| Chicony USB 2.0 Camera                               | 2         | 11.76%  |
| Z-Star Webcam                                        | 1         | 5.88%   |
| Microdia Lenovo EasyCamera                           | 1         | 5.88%   |
| Microdia Amcrest AWC2198 USB Webcam                  | 1         | 5.88%   |
| Microdia 1.3 MPixel Integrated Webcam                | 1         | 5.88%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 1         | 5.88%   |
| IMC Networks EasyCamera                              | 1         | 5.88%   |
| Genesys Logic USB 2.0 Camera                         | 1         | 5.88%   |
| Chicony Integrated Camera                            | 1         | 5.88%   |
| Chicony HP Truevision HD camera                      | 1         | 5.88%   |
| Chicony Fujitsu Integrated Camera                    | 1         | 5.88%   |
| Chicony 720p HD Camera                               | 1         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101 | 1         | 5.88%   |
| AVerMedia Live Streamer CAM 313                      | 1         | 5.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| STMicroelectronics | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| STMicroelectronics Fingerprint Reader | 1         | 100%    |

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
| 0     | 24        | 72.73%  |
| 1     | 8         | 24.24%  |
| 2     | 1         | 3.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 3         | 33.33%  |
| Graphics card            | 2         | 22.22%  |
| Storage                  | 1         | 11.11%  |
| Sound                    | 1         | 11.11%  |
| Fingerprint reader       | 1         | 11.11%  |
| Communication controller | 1         | 11.11%  |

