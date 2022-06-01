Lubuntu - Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu/Desktop/README.md) and [notebooks](/Dist/Lubuntu/Notebook/README.md).

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

![OS](./All/images/pie_chart/os_name.svg)

![OS](./All/images/line_chart/os_name.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| Lubuntu 22.04 | 19        | 39.58%  |
| Lubuntu 20.04 | 14        | 29.17%  |
| Lubuntu 21.10 | 10        | 20.83%  |
| Lubuntu 21.04 | 2         | 4.17%   |
| Lubuntu 18.04 | 2         | 4.17%   |
| Lubuntu 20.10 | 1         | 2.08%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Lubuntu | 48        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 5.13.0-40-generic  | 11        | 22.92%  |
| 5.15.0-30-generic  | 7         | 14.58%  |
| 5.15.0-27-generic  | 6         | 12.5%   |
| 5.15.0-33-generic  | 3         | 6.25%   |
| 5.15.0-25-generic  | 3         | 6.25%   |
| 5.13.0-41-generic  | 3         | 6.25%   |
| 5.4.0-53-generic   | 2         | 4.17%   |
| 5.13.0-19-generic  | 2         | 4.17%   |
| 5.8.0-63-generic   | 1         | 2.08%   |
| 5.4.0-96-generic   | 1         | 2.08%   |
| 5.4.0-65-generic   | 1         | 2.08%   |
| 5.4.0-54-generic   | 1         | 2.08%   |
| 5.4.0-113-generic  | 1         | 2.08%   |
| 5.4.0-100-generic  | 1         | 2.08%   |
| 5.13.0-44-generic  | 1         | 2.08%   |
| 5.11.0-49-generic  | 1         | 2.08%   |
| 5.11.0-41-generic  | 1         | 2.08%   |
| 5.11.0-16-generic  | 1         | 2.08%   |
| 4.15.0-101-generic | 1         | 2.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 19        | 39.58%  |
| 5.13.0  | 17        | 35.42%  |
| 5.4.0   | 7         | 14.58%  |
| 5.11.0  | 3         | 6.25%   |
| 5.8.0   | 1         | 2.08%   |
| 4.15.0  | 1         | 2.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 19        | 39.58%  |
| 5.13    | 17        | 35.42%  |
| 5.4     | 7         | 14.58%  |
| 5.11    | 3         | 6.25%   |
| 5.8     | 1         | 2.08%   |
| 4.15    | 1         | 2.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 46        | 95.83%  |
| i686   | 2         | 4.17%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| LXQt | 45        | 93.75%  |
| LXDE | 3         | 6.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 45        | 93.75%  |
| Tty     | 2         | 4.17%   |
| Wayland | 1         | 2.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 39        | 81.25%  |
| LightDM | 5         | 10.42%  |
| Unknown | 2         | 4.17%   |
| LXDM    | 1         | 2.08%   |
| GDM     | 1         | 2.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 16        | 33.33%  |
| fr_FR | 4         | 8.33%   |
| en_GB | 4         | 8.33%   |
| pt_BR | 3         | 6.25%   |
| it_IT | 3         | 6.25%   |
| C     | 3         | 6.25%   |
| pl_PL | 2         | 4.17%   |
| nl_NL | 1         | 2.08%   |
| fr_CH | 1         | 2.08%   |
| fr_BE | 1         | 2.08%   |
| es_MX | 1         | 2.08%   |
| es_CR | 1         | 2.08%   |
| es_CL | 1         | 2.08%   |
| es_AR | 1         | 2.08%   |
| en_IN | 1         | 2.08%   |
| en_CA | 1         | 2.08%   |
| en_AU | 1         | 2.08%   |
| de_DE | 1         | 2.08%   |
| de_CH | 1         | 2.08%   |
| cv_RU | 1         | 2.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 29        | 60.42%  |
| EFI  | 19        | 39.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 43        | 89.58%  |
| Overlay | 4         | 8.33%   |
| Aufs    | 1         | 2.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 19        | 39.58%  |
| GPT     | 18        | 37.5%   |
| MBR     | 11        | 22.92%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 91.67%  |
| Yes       | 4         | 8.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 66.67%  |
| Yes       | 16        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 6         | 12.5%   |
| Hewlett-Packard     | 5         | 10.42%  |
| ASUSTek Computer    | 5         | 10.42%  |
| Acer                | 4         | 8.33%   |
| Toshiba             | 3         | 6.25%   |
| Intel               | 3         | 6.25%   |
| Dell                | 3         | 6.25%   |
| Unknown             | 3         | 6.25%   |
| Mediacom            | 2         | 4.17%   |
| Google              | 2         | 4.17%   |
| Fujitsu             | 2         | 4.17%   |
| AMI                 | 2         | 4.17%   |
| YASHI               | 1         | 2.08%   |
| Samsung Electronics | 1         | 2.08%   |
| Positivo            | 1         | 2.08%   |
| Pegatron            | 1         | 2.08%   |
| Packard Bell        | 1         | 2.08%   |
| Microsoft           | 1         | 2.08%   |
| Gigabyte Technology | 1         | 2.08%   |
| ASRock              | 1         | 2.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                                         | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Lenovo IdeaPad Slim 1-14AST-05 81VS                          | 3         | 6.25%   |
| Unknown                                                      | 3         | 6.25%   |
| Mediacom WinPad 11,6 FullHD- WPU11                           | 2         | 4.17%   |
| YASHI MYBOOK 360                                             | 1         | 2.08%   |
| Toshiba Satellite P20                                        | 1         | 2.08%   |
| Toshiba Satellite L40                                        | 1         | 2.08%   |
| Toshiba Satellite C670D-12N                                  | 1         | 2.08%   |
| Samsung RV415/RV515                                          | 1         | 2.08%   |
| Positivo AT300b                                              | 1         | 2.08%   |
| Pegatron AY748AA-ABA p6320y                                  | 1         | 2.08%   |
| Packard Bell EasyNote TE11HC                                 | 1         | 2.08%   |
| Microsoft Surface Pro                                        | 1         | 2.08%   |
| Lenovo ThinkCentre E73 10AS00CVUM                            | 1         | 2.08%   |
| Lenovo Legion Y540-15IRH 81SX                                | 1         | 2.08%   |
| Lenovo IdeaPad 310-15IKB 80TV                                | 1         | 2.08%   |
| Intel X79 (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V304 | 1         | 2.08%   |
| Intel Infoway                                                | 1         | 2.08%   |
| Intel DQ57TM                                                 | 1         | 2.08%   |
| HP Pavilion g6                                               | 1         | 2.08%   |
| HP Pavilion g4                                               | 1         | 2.08%   |
| HP OMEN by Laptop                                            | 1         | 2.08%   |
| HP EliteBook 8570p                                           | 1         | 2.08%   |
| HP Berknip                                                   | 1         | 2.08%   |
| Google Terra                                                 | 1         | 2.08%   |
| Google Relm                                                  | 1         | 2.08%   |
| Gigabyte G31M-ES2L                                           | 1         | 2.08%   |
| Fujitsu LIFEBOOK S751                                        | 1         | 2.08%   |
| Fujitsu ESPRIMO C910                                         | 1         | 2.08%   |
| Dell System Inspiron 17 7000 Series 7737                     | 1         | 2.08%   |
| Dell Precision WorkStation T5500                             | 1         | 2.08%   |
| Dell OptiPlex 7020                                           | 1         | 2.08%   |
| ASUS X402CA                                                  | 1         | 2.08%   |
| ASUS X205TA                                                  | 1         | 2.08%   |
| ASUS VivoBook 14_ASUS Laptop E406SAS                         | 1         | 2.08%   |
| ASUS Rampage III GENE                                        | 1         | 2.08%   |
| ASUS K55VD                                                   | 1         | 2.08%   |
| ASRock FM2A85X Extreme6                                      | 1         | 2.08%   |
| AMI VTC1010                                                  | 1         | 2.08%   |
| AMI UB-15MS10                                                | 1         | 2.08%   |
| Acer Swift SF114-34                                          | 1         | 2.08%   |
| Acer Aspire XC100                                            | 1         | 2.08%   |
| Acer Aspire V5-573G                                          | 1         | 2.08%   |
| Acer Aspire A317-33                                          | 1         | 2.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 4         | 8.33%   |
| Toshiba Satellite     | 3         | 6.25%   |
| Acer Aspire           | 3         | 6.25%   |
| Unknown               | 3         | 6.25%   |
| Mediacom WinPad       | 2         | 4.17%   |
| HP Pavilion           | 2         | 4.17%   |
| YASHI MYBOOK          | 1         | 2.08%   |
| Samsung RV415         | 1         | 2.08%   |
| Positivo AT300b       | 1         | 2.08%   |
| Pegatron AY748AA-ABA  | 1         | 2.08%   |
| Packard Bell EasyNote | 1         | 2.08%   |
| Microsoft Surface     | 1         | 2.08%   |
| Lenovo ThinkCentre    | 1         | 2.08%   |
| Lenovo Legion         | 1         | 2.08%   |
| Intel X79             | 1         | 2.08%   |
| Intel Infoway         | 1         | 2.08%   |
| Intel DQ57TM          | 1         | 2.08%   |
| HP OMEN               | 1         | 2.08%   |
| HP EliteBook          | 1         | 2.08%   |
| HP Berknip            | 1         | 2.08%   |
| Google Terra          | 1         | 2.08%   |
| Google Relm           | 1         | 2.08%   |
| Gigabyte G31M-ES2L    | 1         | 2.08%   |
| Fujitsu LIFEBOOK      | 1         | 2.08%   |
| Fujitsu ESPRIMO       | 1         | 2.08%   |
| Dell System           | 1         | 2.08%   |
| Dell Precision        | 1         | 2.08%   |
| Dell OptiPlex         | 1         | 2.08%   |
| ASUS X402CA           | 1         | 2.08%   |
| ASUS X205TA           | 1         | 2.08%   |
| ASUS VivoBook         | 1         | 2.08%   |
| ASUS Rampage          | 1         | 2.08%   |
| ASUS K55VD            | 1         | 2.08%   |
| ASRock FM2A85X        | 1         | 2.08%   |
| AMI VTC1010           | 1         | 2.08%   |
| AMI UB-15MS10         | 1         | 2.08%   |
| Acer Swift            | 1         | 2.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 7         | 14.58%  |
| 2011 | 7         | 14.58%  |
| 2021 | 6         | 12.5%   |
| 2013 | 5         | 10.42%  |
| 2012 | 4         | 8.33%   |
| 2016 | 3         | 6.25%   |
| 2015 | 3         | 6.25%   |
| 2022 | 2         | 4.17%   |
| 2020 | 2         | 4.17%   |
| 2014 | 2         | 4.17%   |
| 2008 | 2         | 4.17%   |
| 2017 | 1         | 2.08%   |
| 2010 | 1         | 2.08%   |
| 2009 | 1         | 2.08%   |
| 2007 | 1         | 2.08%   |
| 2004 | 1         | 2.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 31        | 64.58%  |
| Desktop  | 14        | 29.17%  |
| Mini pc  | 2         | 4.17%   |
| Tablet   | 1         | 2.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 46        | 95.83%  |
| Enabled  | 2         | 4.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 45        | 93.75%  |
| Yes  | 3         | 6.25%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 15        | 31.25%  |
| 4.01-8.0   | 14        | 29.17%  |
| 1.01-2.0   | 9         | 18.75%  |
| 8.01-16.0  | 4         | 8.33%   |
| 16.01-24.0 | 3         | 6.25%   |
| 32.01-64.0 | 1         | 2.08%   |
| 24.01-32.0 | 1         | 2.08%   |
| 2.01-3.0   | 1         | 2.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 22        | 45.83%  |
| 0.51-1.0 | 14        | 29.17%  |
| 2.01-3.0 | 8         | 16.67%  |
| 4.01-8.0 | 3         | 6.25%   |
| 3.01-4.0 | 1         | 2.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 62.5%   |
| 2      | 15        | 31.25%  |
| 0      | 2         | 4.17%   |
| 4      | 1         | 2.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 34        | 70.83%  |
| Yes       | 14        | 29.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 79.17%  |
| No        | 10        | 20.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 72.92%  |
| No        | 13        | 27.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 26        | 54.17%  |
| Yes       | 22        | 45.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 9         | 18.75%  |
| France       | 6         | 12.5%   |
| UK           | 4         | 8.33%   |
| Italy        | 4         | 8.33%   |
| Germany      | 3         | 6.25%   |
| Brazil       | 3         | 6.25%   |
| Poland       | 2         | 4.17%   |
| Ukraine      | 1         | 2.08%   |
| Turkey       | 1         | 2.08%   |
| Switzerland  | 1         | 2.08%   |
| Spain        | 1         | 2.08%   |
| South Africa | 1         | 2.08%   |
| Romania      | 1         | 2.08%   |
| Netherlands  | 1         | 2.08%   |
| Mexico       | 1         | 2.08%   |
| Latvia       | 1         | 2.08%   |
| Kenya        | 1         | 2.08%   |
| India        | 1         | 2.08%   |
| Costa Rica   | 1         | 2.08%   |
| Chile        | 1         | 2.08%   |
| Canada       | 1         | 2.08%   |
| Belgium      | 1         | 2.08%   |
| Australia    | 1         | 2.08%   |
| Argentina    | 1         | 2.08%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sankt Leon-Rot    | 2         | 4.17%   |
| Perth Amboy       | 2         | 4.17%   |
| New York          | 2         | 4.17%   |
| White Plains      | 1         | 2.08%   |
| Warsaw            | 1         | 2.08%   |
| Vilvoorde         | 1         | 2.08%   |
| Vero Beach        | 1         | 2.08%   |
| Valencia          | 1         | 2.08%   |
| Ulhasnagar        | 1         | 2.08%   |
| Taylorsville      | 1         | 2.08%   |
| Strasbourg        | 1         | 2.08%   |
| Sheboygan         | 1         | 2.08%   |
| Sao Paulo         | 1         | 2.08%   |
| Puteaux           | 1         | 2.08%   |
| Puente Alto       | 1         | 2.08%   |
| Pretoria          | 1         | 2.08%   |
| Pontypool         | 1         | 2.08%   |
| Poitiers          | 1         | 2.08%   |
| Pisa              | 1         | 2.08%   |
| Piombino Dese     | 1         | 2.08%   |
| Paris             | 1         | 2.08%   |
| Palermo           | 1         | 2.08%   |
| Orléans          | 1         | 2.08%   |
| Novo Gama         | 1         | 2.08%   |
| Nottingham        | 1         | 2.08%   |
| Notting Hill Gate | 1         | 2.08%   |
| Natal             | 1         | 2.08%   |
| Mombasa           | 1         | 2.08%   |
| Milan             | 1         | 2.08%   |
| Mexico City       | 1         | 2.08%   |
| Melbourne         | 1         | 2.08%   |
| Leiden            | 1         | 2.08%   |
| Lebanon           | 1         | 2.08%   |
| Kyiv              | 1         | 2.08%   |
| Kitchener         | 1         | 2.08%   |
| Karlsruhe         | 1         | 2.08%   |
| Jozefoslaw        | 1         | 2.08%   |
| Heredia           | 1         | 2.08%   |
| Échirolles       | 1         | 2.08%   |
| Derby             | 1         | 2.08%   |
| Buenos Aires      | 1         | 2.08%   |
| Bucharest         | 1         | 2.08%   |
| Bern              | 1         | 2.08%   |
| Alaşehir         | 1         | 2.08%   |
| Adazi             | 1         | 2.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Unknown             | 12        | 20     | 22.22%  |
| WDC                 | 9         | 9      | 16.67%  |
| Hitachi             | 5         | 5      | 9.26%   |
| Toshiba             | 4         | 4      | 7.41%   |
| Seagate             | 4         | 4      | 7.41%   |
| Samsung Electronics | 3         | 3      | 5.56%   |
| Kingston            | 2         | 2      | 3.7%    |
| Verbatim            | 1         | 1      | 1.85%   |
| SPCC                | 1         | 1      | 1.85%   |
| SK Hynix            | 1         | 1      | 1.85%   |
| SanDisk             | 1         | 1      | 1.85%   |
| Patriot             | 1         | 1      | 1.85%   |
| Kston               | 1         | 1      | 1.85%   |
| Intel               | 1         | 1      | 1.85%   |
| IBM/Hitachi         | 1         | 1      | 1.85%   |
| HGST                | 1         | 1      | 1.85%   |
| Fujitsu             | 1         | 1      | 1.85%   |
| Crucial             | 1         | 1      | 1.85%   |
| China               | 1         | 1      | 1.85%   |
| Apple               | 1         | 2      | 1.85%   |
| 2.5"                | 1         | 1      | 1.85%   |
| Unknown             | 1         | 1      | 1.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown SD/MMC/MS PRO 999GB           | 3         | 4.76%   |
| Unknown MMC64G  64GB                  | 3         | 4.76%   |
| Unknown NCard  32GB                   | 2         | 3.17%   |
| Seagate ST500DM002-1BD142 500GB       | 2         | 3.17%   |
| WDC WDS200T2B0A-00SM50 2TB SSD        | 1         | 1.59%   |
| WDC WD5000LUCT-62C26Y0 500GB          | 1         | 1.59%   |
| WDC WD5000AAKX-08U6AA0 500GB          | 1         | 1.59%   |
| WDC WD5000AAKX-07U6AA0 500GB          | 1         | 1.59%   |
| WDC WD2500AAJS-07M0A0 250GB           | 1         | 1.59%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1         | 1.59%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1         | 1.59%   |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB  | 1         | 1.59%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB  | 1         | 1.59%   |
| Verbatim Vi550 S3 SSD 256GB           | 1         | 1.59%   |
| Unknown SU01G  968MB                  | 1         | 1.59%   |
| Unknown SF64G  64GB                   | 1         | 1.59%   |
| Unknown SDW32G  32GB                  | 1         | 1.59%   |
| Unknown SD  32GB                      | 1         | 1.59%   |
| Unknown MBG4GC  32GB                  | 1         | 1.59%   |
| Unknown HAG4a2  16GB                  | 1         | 1.59%   |
| Unknown ED2S5  128GB                  | 1         | 1.59%   |
| Unknown DA4032  32GB                  | 1         | 1.59%   |
| Unknown BJNB4R  32GB                  | 1         | 1.59%   |
| Unknown Biwin  32GB                   | 1         | 1.59%   |
| Unknown ASTC  32GB                    | 1         | 1.59%   |
| Unknown 128G32  128GB                 | 1         | 1.59%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1.59%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1.59%   |
| Toshiba MK5059GSXP 500GB              | 1         | 1.59%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD   | 1         | 1.59%   |
| SPCC Solid State Disk 120GB           | 1         | 1.59%   |
| SK Hynix HFS128G3BTND-N210A 128GB SSD | 1         | 1.59%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1.59%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1.59%   |
| SanDisk SD6SB1M256G1022I 256GB SSD    | 1         | 1.59%   |
| Samsung NVMe SSD Drive 256GB          | 1         | 1.59%   |
| Samsung NVMe SSD Drive 128GB          | 1         | 1.59%   |
| Samsung HM121HI 120GB                 | 1         | 1.59%   |
| Patriot Memory 500GB SSD              | 1         | 1.59%   |
| Kston SSD 128GB                       | 1         | 1.59%   |
| Kingston SNVS500G 500GB               | 1         | 1.59%   |
| Kingston OM8PDP3512B-A01 512GB        | 1         | 1.59%   |
| Intel SSDMCEAC240B3 240GB             | 1         | 1.59%   |
| IBM/Hitachi IC25N060ATMR04-0 64GB     | 1         | 1.59%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1.59%   |
| Hitachi HTS547564A9E384 640GB         | 1         | 1.59%   |
| Hitachi HTS543232A7A384 320GB         | 1         | 1.59%   |
| Hitachi HDS721616PLA320 160GB         | 1         | 1.59%   |
| Hitachi HDP725025GLA380 250GB         | 1         | 1.59%   |
| HGST HTS721010A9E630 1TB              | 1         | 1.59%   |
| Fujitsu MHY2120BH 120GB               | 1         | 1.59%   |
| Crucial CT2000BX500SSD1 2TB           | 1         | 1.59%   |
| China SATA SSD 256GB                  | 1         | 1.59%   |
| Apple NVMe SSD Drive 8KB              | 1         | 1.59%   |
| Apple NVMe SSD Drive 1TB              | 1         | 1.59%   |
| 2.5" SATA SSD 3MG2-P 64GB             | 1         | 1.59%   |
| Unknown                               | 1         | 1.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 24%     |
| Hitachi             | 5         | 5      | 20%     |
| Seagate             | 4         | 4      | 16%     |
| Unknown             | 3         | 3      | 12%     |
| Toshiba             | 3         | 3      | 12%     |
| Samsung Electronics | 1         | 1      | 4%      |
| IBM/Hitachi         | 1         | 1      | 4%      |
| HGST                | 1         | 1      | 4%      |
| Fujitsu             | 1         | 1      | 4%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 1         | 1      | 9.09%   |
| Verbatim | 1         | 1      | 9.09%   |
| SPCC     | 1         | 1      | 9.09%   |
| SK Hynix | 1         | 1      | 9.09%   |
| SanDisk  | 1         | 1      | 9.09%   |
| Patriot  | 1         | 1      | 9.09%   |
| Kston    | 1         | 1      | 9.09%   |
| Intel    | 1         | 1      | 9.09%   |
| Crucial  | 1         | 1      | 9.09%   |
| China    | 1         | 1      | 9.09%   |
| 2.5"     | 1         | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 25     | 43.4%   |
| MMC  | 13        | 18     | 24.53%  |
| SSD  | 9         | 11     | 16.98%  |
| NVMe | 8         | 9      | 15.09%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 28        | 32     | 52.83%  |
| MMC  | 13        | 18     | 24.53%  |
| NVMe | 8         | 9      | 15.09%  |
| SAS  | 4         | 4      | 7.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 23        | 24     | 67.65%  |
| 0.51-1.0   | 9         | 9      | 26.47%  |
| 1.01-2.0   | 2         | 3      | 5.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 17        | 35.42%  |
| 251-500        | 7         | 14.58%  |
| 51-100         | 6         | 12.5%   |
| 21-50          | 5         | 10.42%  |
| 1-20           | 4         | 8.33%   |
| 501-1000       | 4         | 8.33%   |
| Unknown        | 3         | 6.25%   |
| More than 3000 | 1         | 2.08%   |
| 2001-3000      | 1         | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 21        | 43.75%  |
| 21-50          | 11        | 22.92%  |
| 101-250        | 6         | 12.5%   |
| 51-100         | 4         | 8.33%   |
| Unknown        | 3         | 6.25%   |
| More than 3000 | 1         | 2.08%   |
| 251-500        | 1         | 2.08%   |
| 501-1000       | 1         | 2.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000LUCT-62C26Y0 500GB          | 1         | 1      | 12.5%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1         | 1      | 12.5%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1      | 12.5%   |
| Toshiba MK5059GSXP 500GB              | 1         | 1      | 12.5%   |
| SK Hynix HFS128G3BTND-N210A 128GB SSD | 1         | 1      | 12.5%   |
| Samsung Electronics HM121HI 120GB     | 1         | 1      | 12.5%   |
| Hitachi HTS547564A9E384 640GB         | 1         | 1      | 12.5%   |
| Fujitsu MHY2120BH 120GB               | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 25%     |
| Toshiba             | 2         | 2      | 25%     |
| SK Hynix            | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| Hitachi             | 1         | 1      | 12.5%   |
| Fujitsu             | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 28.57%  |
| Toshiba             | 2         | 2      | 28.57%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 1      | 14.29%  |
| Fujitsu             | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 7      | 87.5%   |
| SSD  | 1         | 1      | 12.5%   |

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
| Detected | 27        | 41     | 55.1%   |
| Works    | 14        | 14     | 28.57%  |
| Malfunc  | 8         | 8      | 16.33%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 25        | 56.82%  |
| AMD                          | 10        | 22.73%  |
| Sandisk                      | 2         | 4.55%   |
| Samsung Electronics          | 2         | 4.55%   |
| Kingston Technology Company  | 2         | 4.55%   |
| Toshiba America Info Systems | 1         | 2.27%   |
| Nvidia                       | 1         | 2.27%   |
| Marvell Technology Group     | 1         | 2.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 13.46%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 7.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 3.85%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2         | 3.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 3.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 3.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 3.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 3.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 3.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 3.85%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 1.92%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 1         | 1.92%   |
| Sandisk PC SN520 NVMe SSD                                                      | 1         | 1.92%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 1.92%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.92%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                   | 1         | 1.92%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                           | 1         | 1.92%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.92%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 1.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 1.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 1.92%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 1.92%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.92%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.92%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                   | 1         | 1.92%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.92%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 1.92%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.92%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                          | 1         | 1.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1         | 1.92%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1         | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1         | 1.92%   |
| AMD FCH IDE Controller                                                         | 1         | 1.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 32        | 66.67%  |
| IDE  | 9         | 18.75%  |
| NVMe | 7         | 14.58%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 36        | 75%     |
| AMD    | 12        | 25%     |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 6.25%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 3         | 6.25%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 4.17%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 4.17%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 4.17%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 2         | 4.17%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 4.17%   |
| AMD E-300 APU with Radeon HD Graphics         | 2         | 4.17%   |
| Intel Xeon CPU X5650 @ 2.67GHz                | 1         | 2.08%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz            | 1         | 2.08%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 2.08%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 1         | 2.08%   |
| Intel Pentium 4 CPU 2.80GHz                   | 1         | 2.08%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 2.08%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 2.08%   |
| Intel Core i7-3540M CPU @ 3.00GHz             | 1         | 2.08%   |
| Intel Core i7 CPU X 980 @ 3.33GHz             | 1         | 2.08%   |
| Intel Core i5-9300HF CPU @ 2.40GHz            | 1         | 2.08%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 2.08%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 2.08%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 2.08%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2.08%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 1         | 2.08%   |
| Intel Core i3-4170 CPU @ 3.70GHz              | 1         | 2.08%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 1         | 2.08%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 2.08%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz          | 1         | 2.08%   |
| Intel Celeron N5100 @ 1.10GHz                 | 1         | 2.08%   |
| Intel Celeron CPU B820 @ 1.70GHz              | 1         | 2.08%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 1         | 2.08%   |
| Intel Atom CPU E3827 @ 1.74GHz                | 1         | 2.08%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 2.08%   |
| AMD Ryzen 3 3250C 15W with Radeon Graphics    | 1         | 2.08%   |
| AMD Phenom II X4 820 Processor                | 1         | 2.08%   |
| AMD E2-1800 APU with Radeon HD Graphics       | 1         | 2.08%   |
| AMD E1-1500 APU with Radeon HD Graphics       | 1         | 2.08%   |
| AMD A6-4400M APU with Radeon HD Graphics      | 1         | 2.08%   |
| AMD A10-6800K APU with Radeon HD Graphics     | 1         | 2.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 8         | 16.67%  |
| Intel Celeron        | 8         | 16.67%  |
| Intel Atom           | 7         | 14.58%  |
| Intel Core i7        | 4         | 8.33%   |
| AMD A6               | 4         | 8.33%   |
| Intel Xeon           | 2         | 4.17%   |
| Intel Core i3        | 2         | 4.17%   |
| Intel Core 2 Duo     | 2         | 4.17%   |
| AMD E                | 2         | 4.17%   |
| Intel Pentium Silver | 1         | 2.08%   |
| Intel Pentium Dual   | 1         | 2.08%   |
| Intel Pentium 4      | 1         | 2.08%   |
| AMD Ryzen 9          | 1         | 2.08%   |
| AMD Ryzen 3          | 1         | 2.08%   |
| AMD Phenom II X4     | 1         | 2.08%   |
| AMD E2               | 1         | 2.08%   |
| AMD E1               | 1         | 2.08%   |
| AMD A10              | 1         | 2.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 28        | 58.33%  |
| 4      | 14        | 29.17%  |
| 1      | 3         | 6.25%   |
| 6      | 2         | 4.17%   |
| 8      | 1         | 2.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 48        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 62.5%   |
| 2      | 18        | 37.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 47        | 97.92%  |
| 32-bit         | 1         | 2.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 31.25%  |
| 0x406c4    | 3         | 6.25%   |
| 0x306a9    | 3         | 6.25%   |
| 0x206a7    | 3         | 6.25%   |
| 0x05000119 | 3         | 6.25%   |
| 0x906c0    | 2         | 4.17%   |
| 0x406c3    | 2         | 4.17%   |
| 0x40651    | 2         | 4.17%   |
| 0x06006705 | 2         | 4.17%   |
| 0x906ed    | 1         | 2.08%   |
| 0x806e9    | 1         | 2.08%   |
| 0x706a8    | 1         | 2.08%   |
| 0x6fd      | 1         | 2.08%   |
| 0x6fa      | 1         | 2.08%   |
| 0x30679    | 1         | 2.08%   |
| 0x30678    | 1         | 2.08%   |
| 0x206d7    | 1         | 2.08%   |
| 0x206c2    | 1         | 2.08%   |
| 0x0a50000c | 1         | 2.08%   |
| 0x08200103 | 1         | 2.08%   |
| 0x06001119 | 1         | 2.08%   |
| 0x06001116 | 1         | 2.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 10        | 20.83%  |
| SandyBridge   | 4         | 8.33%   |
| Haswell       | 4         | 8.33%   |
| Bobcat        | 4         | 8.33%   |
| Westmere      | 3         | 6.25%   |
| KabyLake      | 3         | 6.25%   |
| IvyBridge     | 3         | 6.25%   |
| Excavator     | 3         | 6.25%   |
| Tremont       | 2         | 4.17%   |
| Piledriver    | 2         | 4.17%   |
| Goldmont plus | 2         | 4.17%   |
| Core          | 2         | 4.17%   |
| Zen 3         | 1         | 2.08%   |
| Zen           | 1         | 2.08%   |
| Skylake       | 1         | 2.08%   |
| Penryn        | 1         | 2.08%   |
| NetBurst      | 1         | 2.08%   |
| K10           | 1         | 2.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 29        | 54.72%  |
| AMD    | 14        | 26.42%  |
| Nvidia | 10        | 18.87%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 12.5%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 5.36%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 5.36%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 5.36%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 3.57%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 3.57%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 3.57%   |
| Intel HD Graphics 620                                                                    | 2         | 3.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 3.57%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 3.57%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.57%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 3.57%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.79%   |
| Nvidia NV31M [GeForce FX Go5600]                                                         | 1         | 1.79%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 1.79%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.79%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.79%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.79%   |
| Nvidia GK107GL [Quadro K420]                                                             | 1         | 1.79%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 1.79%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.79%   |
| Nvidia C78 [GeForce 9100]                                                                | 1         | 1.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.79%   |
| Intel HD Graphics 530                                                                    | 1         | 1.79%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.79%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 1.79%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 1.79%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 1.79%   |
| AMD Trinity 2 [Radeon HD 7520G]                                                          | 1         | 1.79%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 1.79%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.79%   |
| AMD Richland [Radeon HD 8670D]                                                           | 1         | 1.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.79%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 1         | 1.79%   |
| AMD Cezanne                                                                              | 1         | 1.79%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 1.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 24        | 50%     |
| 1 x AMD        | 13        | 27.08%  |
| 1 x Nvidia     | 6         | 12.5%   |
| Intel + Nvidia | 4         | 8.33%   |
| 2 x AMD        | 1         | 2.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 44        | 91.67%  |
| Proprietary | 2         | 4.17%   |
| Unknown     | 2         | 4.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 66.67%  |
| 0.01-0.5   | 8         | 16.67%  |
| 1.01-2.0   | 4         | 8.33%   |
| 0.51-1.0   | 3         | 6.25%   |
| 5.01-6.0   | 1         | 2.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 6         | 14.29%  |
| AU Optronics            | 6         | 14.29%  |
| Samsung Electronics     | 5         | 11.9%   |
| BOE                     | 5         | 11.9%   |
| Hewlett-Packard         | 4         | 9.52%   |
| Chimei Innolux          | 4         | 9.52%   |
| Goldstar                | 2         | 4.76%   |
| CPT                     | 2         | 4.76%   |
| Videoseven              | 1         | 2.38%   |
| Toshiba                 | 1         | 2.38%   |
| LG Philips              | 1         | 2.38%   |
| Lenovo                  | 1         | 2.38%   |
| Iiyama                  | 1         | 2.38%   |
| Dell                    | 1         | 2.38%   |
| Chi Mei Optoelectronics | 1         | 2.38%   |
| Ancor Communications    | 1         | 2.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                     | 2         | 4.65%   |
| Videoseven L19FM IGM0812 1280x1024 376x301mm 19.0-inch                   | 1         | 2.33%   |
| Toshiba TV TSB0106 1920x1080 708x398mm 32.0-inch                         | 1         | 2.33%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 1         | 2.33%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch     | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC4449 1366x768 309x174mm 14.0-inch     | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch     | 1         | 2.33%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 1         | 2.33%   |
| LG Philips LCD Monitor LPLEC00 1280x800 331x207mm 15.4-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch             | 1         | 2.33%   |
| LG Display LCD Monitor LGD03E9 1366x768 345x194mm 15.6-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD0365 1600x900 382x215mm 17.3-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch              | 1         | 2.33%   |
| Lenovo LEN LI1931ewA LEN65A1 1366x768 409x230mm 18.5-inch                | 1         | 2.33%   |
| Lenovo LEN E2054A LEN60DF 1440x900 420x260mm 19.4-inch                   | 1         | 2.33%   |
| Iiyama PL2452 IVM610A 1920x1080 521x293mm 23.5-inch                      | 1         | 2.33%   |
| Hewlett-Packard w2338h HWP281B 1920x1080 509x286mm 23.0-inch             | 1         | 2.33%   |
| Hewlett-Packard L2245w HWP26FB 1680x1050 473x296mm 22.0-inch             | 1         | 2.33%   |
| Hewlett-Packard 23xi HWP3032 1920x1080 509x286mm 23.0-inch               | 1         | 2.33%   |
| Hewlett-Packard 2311x HWP293A 1920x1080 510x287mm 23.0-inch              | 1         | 2.33%   |
| Goldstar M228WA GSM563C 1680x1050 434x270mm 20.1-inch                    | 1         | 2.33%   |
| Goldstar HD PLUS GSM5AC5 1600x900 440x250mm 19.9-inch                    | 1         | 2.33%   |
| Dell AW2518HF DELA102 1920x1080 544x303mm 24.5-inch                      | 1         | 2.33%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                     | 1         | 2.33%   |
| CPT LCD Monitor CPT003C 1366x768 309x174mm 14.0-inch                     | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN15D9 1920x1080 344x193mm 15.5-inch         | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 2.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 1         | 2.33%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                    | 1         | 2.33%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                    | 1         | 2.33%   |
| BOE LCD Monitor BOE0700 1920x1080 340x190mm 15.3-inch                    | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO41ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO115C 1366x768 256x144mm 11.6-inch            | 1         | 2.33%   |
| Ancor Communications ASUS VH242 ACI24FA 1920x1080 521x293mm 23.5-inch    | 1         | 2.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 16        | 39.02%  |
| 1920x1080 (FHD)    | 11        | 26.83%  |
| 1600x900 (HD+)     | 4         | 9.76%   |
| 1680x1050 (WSXGA+) | 2         | 4.88%   |
| 1280x800 (WXGA)    | 2         | 4.88%   |
| 1280x1024 (SXGA)   | 2         | 4.88%   |
| 3840x2160 (4K)     | 1         | 2.44%   |
| 2736x1824          | 1         | 2.44%   |
| 1920x540           | 1         | 2.44%   |
| 1440x900 (WXGA+)   | 1         | 2.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 11        | 26.19%  |
| 23     | 5         | 11.9%   |
| 13     | 5         | 11.9%   |
| 19     | 4         | 9.52%   |
| 14     | 4         | 9.52%   |
| 17     | 3         | 7.14%   |
| 11     | 3         | 7.14%   |
| 47     | 1         | 2.38%   |
| 27     | 1         | 2.38%   |
| 24     | 1         | 2.38%   |
| 22     | 1         | 2.38%   |
| 20     | 1         | 2.38%   |
| 18     | 1         | 2.38%   |
| 12     | 1         | 2.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 48.78%  |
| 501-600     | 6         | 14.63%  |
| 351-400     | 5         | 12.2%   |
| 401-500     | 4         | 9.76%   |
| 201-300     | 4         | 9.76%   |
| 601-700     | 1         | 2.44%   |
| 1001-1500   | 1         | 2.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 32        | 80%     |
| 16/10 | 5         | 12.5%   |
| 5/4   | 2         | 5%      |
| 3/2   | 1         | 2.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 23.81%  |
| 81-90          | 9         | 21.43%  |
| 201-250        | 6         | 14.29%  |
| 151-200        | 5         | 11.9%   |
| 51-60          | 3         | 7.14%   |
| 121-130        | 3         | 7.14%   |
| 71-80          | 1         | 2.38%   |
| 301-350        | 1         | 2.38%   |
| 251-300        | 1         | 2.38%   |
| 141-150        | 1         | 2.38%   |
| 501-1000       | 1         | 2.38%   |
| 91-100         | 1         | 2.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 15        | 37.5%   |
| 101-120 | 13        | 32.5%   |
| 121-160 | 11        | 27.5%   |
| 1-50    | 1         | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 43        | 89.58%  |
| 2     | 4         | 8.33%   |
| 0     | 1         | 2.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 26        | 36.11%  |
| Intel                    | 20        | 27.78%  |
| Qualcomm Atheros         | 9         | 12.5%   |
| Ralink Technology        | 3         | 4.17%   |
| Ralink                   | 3         | 4.17%   |
| Marvell Technology Group | 2         | 2.78%   |
| Broadcom                 | 2         | 2.78%   |
| Samsung Electronics      | 1         | 1.39%   |
| Nvidia                   | 1         | 1.39%   |
| MEDIATEK                 | 1         | 1.39%   |
| ICS Advent               | 1         | 1.39%   |
| Hewlett-Packard          | 1         | 1.39%   |
| Fibocom                  | 1         | 1.39%   |
| Broadcom Limited         | 1         | 1.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 13        | 16.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4         | 5%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 3         | 3.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 3         | 3.75%   |
| Intel Wireless 7265                                                           | 3         | 3.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3         | 3.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 2.5%    |
| Ralink MT7601U Wireless Adapter                                               | 2         | 2.5%    |
| Intel Wireless 7260                                                           | 2         | 2.5%    |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 2         | 2.5%    |
| Intel Ethernet Controller I225-V                                              | 2         | 2.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2         | 2.5%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1         | 1.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 1.25%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1         | 1.25%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 1         | 1.25%   |
| Realtek RTL8150 Fast Ethernet Adapter                                         | 1         | 1.25%   |
| Realtek 802.11ac NIC                                                          | 1         | 1.25%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.25%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.25%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.25%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 1         | 1.25%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1         | 1.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 1.25%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 1.25%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1         | 1.25%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1         | 1.25%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.25%   |
| Nvidia MCP77 Ethernet                                                         | 1         | 1.25%   |
| MEDIATEK MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 1         | 1.25%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                             | 1         | 1.25%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                       | 1         | 1.25%   |
| Intel Wi-Fi 6 AX200                                                           | 1         | 1.25%   |
| Intel I210 Gigabit Network Connection                                         | 1         | 1.25%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.25%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 1         | 1.25%   |
| Intel Centrino Wireless-N 2230                                                | 1         | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1         | 1.25%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Modem Controller                          | 1         | 1.25%   |
| Intel 82578DM Gigabit Network Connection                                      | 1         | 1.25%   |
| Intel 82567V-2 Gigabit Network Connection                                     | 1         | 1.25%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                       | 1         | 1.25%   |
| HP hs2350 HSPA+ MobileBroadband                                               | 1         | 1.25%   |
| Fibocom L831-EAU-00                                                           | 1         | 1.25%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1         | 1.25%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 1         | 1.25%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                       | 1         | 1.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 1.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 13        | 34.21%  |
| Qualcomm Atheros         | 8         | 21.05%  |
| Realtek Semiconductor    | 7         | 18.42%  |
| Ralink Technology        | 3         | 7.89%   |
| Ralink                   | 3         | 7.89%   |
| MEDIATEK                 | 1         | 2.63%   |
| Marvell Technology Group | 1         | 2.63%   |
| Broadcom Limited         | 1         | 2.63%   |
| Broadcom                 | 1         | 2.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 3         | 7.89%   |
| Intel Wireless 7265                                                           | 3         | 7.89%   |
| Ralink MT7601U Wireless Adapter                                               | 2         | 5.26%   |
| Intel Wireless 7260                                                           | 2         | 5.26%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 2         | 5.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2         | 5.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 2.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1         | 2.63%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 1         | 2.63%   |
| Realtek 802.11ac NIC                                                          | 1         | 2.63%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 2.63%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1         | 2.63%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 1         | 2.63%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 1         | 2.63%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1         | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 2.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 2.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 2.63%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 2.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 2.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1         | 2.63%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 2.63%   |
| MEDIATEK MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 1         | 2.63%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                             | 1         | 2.63%   |
| Intel Wi-Fi 6 AX200                                                           | 1         | 2.63%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 1         | 2.63%   |
| Intel Centrino Wireless-N 2230                                                | 1         | 2.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1         | 2.63%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                       | 1         | 2.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 2.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 22        | 56.41%  |
| Intel                    | 9         | 23.08%  |
| Broadcom                 | 2         | 5.13%   |
| Samsung Electronics      | 1         | 2.56%   |
| Qualcomm Atheros         | 1         | 2.56%   |
| Nvidia                   | 1         | 2.56%   |
| Marvell Technology Group | 1         | 2.56%   |
| ICS Advent               | 1         | 2.56%   |
| Fibocom                  | 1         | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 32.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 10%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 7.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 7.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 5%      |
| Intel Ethernet Controller I225-V                                  | 2         | 5%      |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 2.5%    |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1         | 2.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.5%    |
| Nvidia MCP77 Ethernet                                             | 1         | 2.5%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 2.5%    |
| Intel I210 Gigabit Network Connection                             | 1         | 2.5%    |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.5%    |
| Intel 82578DM Gigabit Network Connection                          | 1         | 2.5%    |
| Intel 82567V-2 Gigabit Network Connection                         | 1         | 2.5%    |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 2.5%    |
| Fibocom L831-EAU-00                                               | 1         | 2.5%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 2.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 37        | 50%     |
| WiFi     | 35        | 47.3%   |
| Modem    | 2         | 2.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 60%     |
| Ethernet | 18        | 40%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 20        | 41.67%  |
| 2     | 18        | 37.5%   |
| 0     | 6         | 12.5%   |
| 3     | 3         | 6.25%   |
| 4     | 1         | 2.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 39        | 81.25%  |
| Yes  | 9         | 18.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 50%     |
| Realtek Semiconductor           | 3         | 13.64%  |
| Ralink                          | 1         | 4.55%   |
| Qualcomm Atheros Communications | 1         | 4.55%   |
| MediaTek                        | 1         | 4.55%   |
| Marvell Semiconductor           | 1         | 4.55%   |
| IMC Networks                    | 1         | 4.55%   |
| Foxconn / Hon Hai               | 1         | 4.55%   |
| Cambridge Silicon Radio         | 1         | 4.55%   |
| Broadcom                        | 1         | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 27.27%  |
| Realtek Bluetooth Radio                             | 3         | 13.64%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 9.09%   |
| Ralink RT3290 Bluetooth                             | 1         | 4.55%   |
| Qualcomm Atheros Bluetooth                          | 1         | 4.55%   |
| MediaTek Wireless_Device                            | 1         | 4.55%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 4.55%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 4.55%   |
| Intel AX201 Bluetooth                               | 1         | 4.55%   |
| Intel AX200 Bluetooth                               | 1         | 4.55%   |
| IMC Networks Bluetooth Device                       | 1         | 4.55%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 4.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.55%   |
| Broadcom HP Portable SoftSailing                    | 1         | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 30        | 53.57%  |
| AMD                                          | 14        | 25%     |
| Nvidia                                       | 7         | 12.5%   |
| C-Media Electronics                          | 2         | 3.57%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 1.79%   |
| Nordic Semiconductor ASA                     | 1         | 1.79%   |
| Logitech                                     | 1         | 1.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 8.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 4.41%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 4.41%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 4.41%   |
| AMD High Definition Audio Controller                                                              | 3         | 4.41%   |
| AMD FCH Azalia Controller                                                                         | 3         | 4.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 4.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 2.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 2.94%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 2.94%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 2.94%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 2.94%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 2.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 2.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.94%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.94%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 1.47%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.47%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 1.47%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 1.47%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.47%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.47%   |
| Nordic Semiconductor ASA SG Control Mic                                                           | 1         | 1.47%   |
| Logitech H600 [Wireless Headset]                                                                  | 1         | 1.47%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.47%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.47%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                                              | 1         | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 1.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.47%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 1.47%   |
| C-Media Electronics Audio Adapter                                                                 | 1         | 1.47%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 1.47%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.47%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.47%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.47%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 1.47%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 1.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 9         | 23.08%  |
| Samsung Electronics | 8         | 20.51%  |
| Unknown             | 7         | 17.95%  |
| Micron Technology   | 7         | 17.95%  |
| Kingston            | 3         | 7.69%   |
| Elpida              | 3         | 7.69%   |
| Smart               | 1         | 2.56%   |
| Unknown             | 1         | 2.56%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s | 3         | 7.14%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                 | 2         | 4.76%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 4.76%   |
| Unknown RAM Module 512MB SODIMM DDR2                        | 1         | 2.38%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s              | 1         | 2.38%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                 | 1         | 2.38%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 1         | 2.38%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                  | 1         | 2.38%   |
| Unknown RAM Module 1GB SODIMM DDR2                          | 1         | 2.38%   |
| Unknown RAM GSA8G4SCL156P-21 8192MB SODIMM DDR4 2133MT/s    | 1         | 2.38%   |
| Smart RAM SH564128FH8NZPHSCG 4096MB SODIMM DDR3 1334MT/s    | 1         | 2.38%   |
| SK Hynix RAM HMT451S6MFR6A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 2.38%   |
| SK Hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 2.38%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s   | 1         | 2.38%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1334MT/s   | 1         | 2.38%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 2.38%   |
| SK Hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s        | 1         | 2.38%   |
| SK Hynix RAM HMT125R7TFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1         | 2.38%   |
| SK Hynix RAM H9CCNNN8GTMLAR-NUD 2GB LPDDR3 1600MT/s         | 1         | 2.38%   |
| Samsung RAM U6E3S4AA-MGCR 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 2.38%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM 1600MT/s            | 1         | 2.38%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 1         | 2.38%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 2.38%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s    | 1         | 2.38%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 1         | 2.38%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s         | 1         | 2.38%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s        | 1         | 2.38%   |
| Micron RAM 4ATF51264HZ-3G2R1 4096MB SODIMM DDR4 3200MT/s    | 1         | 2.38%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4096MB SODIMM DDR4 2133MT/s    | 1         | 2.38%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s      | 1         | 2.38%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2400MT/s      | 1         | 2.38%   |
| Kingston RAM LV26D4S9S8HJ-8 8GB SODIMM DDR4 2667MT/s        | 1         | 2.38%   |
| Kingston RAM CBD32D4S2S8MF-16 16GB SODIMM DDR4 3200MT/s     | 1         | 2.38%   |
| Kingston RAM 99U5469-046.A00LF 4096MB SODIMM DDR3 1333MT/s  | 1         | 2.38%   |
| Elpida RAM EBJ41UF8BDW0-GN-F 4096MB DIMM DDR3 1600MT/s      | 1         | 2.38%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s       | 1         | 2.38%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s       | 1         | 2.38%   |
| Unknown                                                     | 1         | 2.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 18        | 56.25%  |
| DDR4   | 10        | 31.25%  |
| DDR2   | 2         | 6.25%   |
| LPDDR4 | 1         | 3.13%   |
| LPDDR3 | 1         | 3.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 24        | 75%     |
| Row Of Chips | 4         | 12.5%   |
| DIMM         | 3         | 9.38%   |
| Unknown      | 1         | 3.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 18        | 50%     |
| 2048  | 8         | 22.22%  |
| 8192  | 5         | 13.89%  |
| 16384 | 2         | 5.56%   |
| 1024  | 2         | 5.56%   |
| 512   | 1         | 2.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 11        | 30.56%  |
| 1866    | 4         | 11.11%  |
| 1334    | 4         | 11.11%  |
| 2667    | 3         | 8.33%   |
| 1333    | 3         | 8.33%   |
| 1066    | 3         | 8.33%   |
| 3200    | 2         | 5.56%   |
| 2133    | 2         | 5.56%   |
| 4267    | 1         | 2.78%   |
| 2400    | 1         | 2.78%   |
| 667     | 1         | 2.78%   |
| Unknown | 1         | 2.78%   |

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
| Chicony Electronics                    | 7         | 26.92%  |
| Quanta                                 | 3         | 11.54%  |
| IMC Networks                           | 3         | 11.54%  |
| Sunplus Innovation Technology          | 2         | 7.69%   |
| Realtek Semiconductor                  | 2         | 7.69%   |
| Microdia                               | 2         | 7.69%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 7.69%   |
| Silicon Motion                         | 1         | 3.85%   |
| Pixart Imaging                         | 1         | 3.85%   |
| Lite-On Technology                     | 1         | 3.85%   |
| Apple                                  | 1         | 3.85%   |
| Alcor Micro                            | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony EasyCamera                                              | 3         | 11.54%  |
| Chicony HD WebCam                                               | 2         | 7.69%   |
| Sunplus HP HD Webcam [Fixed]                                    | 1         | 3.85%   |
| Sunplus Asus Webcam                                             | 1         | 3.85%   |
| Silicon Motion WebCam SC-0311139N                               | 1         | 3.85%   |
| Realtek USB Camera                                              | 1         | 3.85%   |
| Realtek EasyCamera                                              | 1         | 3.85%   |
| Quanta VGA User Facing                                          | 1         | 3.85%   |
| Quanta HD User Facing                                           | 1         | 3.85%   |
| Quanta Chromebook HD Camera                                     | 1         | 3.85%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                            | 1         | 3.85%   |
| Microdia Integrated_Webcam_HD                                   | 1         | 3.85%   |
| Microdia HP Webcam-50                                           | 1         | 3.85%   |
| Lite-On Integrated Camera                                       | 1         | 3.85%   |
| IMC Networks VGA UVC WebCam                                     | 1         | 3.85%   |
| IMC Networks USB2.0 UVC HD Webcam                               | 1         | 3.85%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 1         | 3.85%   |
| Chicony HP Wide Vision HD                                       | 1         | 3.85%   |
| Chicony CNF9055 Toshiba Webcam                                  | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD         | 1         | 3.85%   |
| Apple iPhone 5/5C/5S/6/SE                                       | 1         | 3.85%   |
| Alcor Micro SHUNCCM2MP                                          | 1         | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Validity Sensors VFS491 | 1         | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./All/images/line_chart/chipcard_vendor.svg)

| Vendor   | Computers | Percent |
|----------|-----------|---------|
| O2 Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 40        | 83.33%  |
| 1     | 5         | 10.42%  |
| 2     | 3         | 6.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Net/wireless       | 2         | 18.18%  |
| Graphics card      | 2         | 18.18%  |
| Camera             | 2         | 18.18%  |
| Bluetooth          | 2         | 18.18%  |
| Modem              | 1         | 9.09%   |
| Fingerprint reader | 1         | 9.09%   |
| Chipcard           | 1         | 9.09%   |

