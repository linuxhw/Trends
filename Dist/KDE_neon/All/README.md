KDE neon - Hardware Trends
--------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/KDE_neon/Desktop/README.md) and [notebooks](/Dist/KDE_neon/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/linuxhw/TestCoverage)

Period: Nov, 2022.

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

| Name           | Computers | Percent |
|----------------|-----------|---------|
| KDE neon 22.04 | 98        | 95.15%  |
| KDE neon 20.04 | 5         | 4.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE neon | 103       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.15.0-52-generic    | 60        | 58.25%  |
| 5.15.0-53-generic    | 36        | 34.95%  |
| 5.15.0-50-generic    | 2         | 1.94%   |
| 6.0.7-060007-generic | 1         | 0.97%   |
| 5.19.15-xanmod1      | 1         | 0.97%   |
| 5.15.0-54-generic    | 1         | 0.97%   |
| 5.13.0-30-generic    | 1         | 0.97%   |
| 5.11.0-27-generic    | 1         | 0.97%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 99        | 96.12%  |
| 6.0.7   | 1         | 0.97%   |
| 5.19.15 | 1         | 0.97%   |
| 5.13.0  | 1         | 0.97%   |
| 5.11.0  | 1         | 0.97%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 99        | 96.12%  |
| 6.0     | 1         | 0.97%   |
| 5.19    | 1         | 0.97%   |
| 5.13    | 1         | 0.97%   |
| 5.11    | 1         | 0.97%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 103       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| KDE5 | 101       | 98.06%  |
| KDE  | 2         | 1.94%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 97        | 94.17%  |
| Wayland | 6         | 5.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 72        | 69.9%   |
| SDDM    | 31        | 30.1%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 30        | 29.13%  |
| en_GB      | 12        | 11.65%  |
| de_DE      | 10        | 9.71%   |
| en_AG      | 8         | 7.77%   |
| fr_FR      | 7         | 6.8%    |
| pt_BR      | 5         | 4.85%   |
| ru_RU      | 3         | 2.91%   |
| it_IT      | 3         | 2.91%   |
| en_CA      | 3         | 2.91%   |
| tr_TR      | 2         | 1.94%   |
| sv_SE      | 2         | 1.94%   |
| en_IN      | 2         | 1.94%   |
| el_GR      | 2         | 1.94%   |
| pt_PT      | 1         | 0.97%   |
| pl_PL      | 1         | 0.97%   |
| nl_NL      | 1         | 0.97%   |
| fr_BE      | 1         | 0.97%   |
| es_VE      | 1         | 0.97%   |
| es_MX      | 1         | 0.97%   |
| es_CL      | 1         | 0.97%   |
| en_ZA      | 1         | 0.97%   |
| en_PH      | 1         | 0.97%   |
| el_GR@euro | 1         | 0.97%   |
| cs_CZ      | 1         | 0.97%   |
| ca_AD      | 1         | 0.97%   |
| C          | 1         | 0.97%   |
| bg_BG      | 1         | 0.97%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 89        | 86.41%  |
| EFI  | 14        | 13.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 101       | 98.06%  |
| Xfs     | 1         | 0.97%   |
| Overlay | 1         | 0.97%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 71        | 68.93%  |
| GPT     | 24        | 23.3%   |
| MBR     | 8         | 7.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 99        | 96.12%  |
| Yes       | 4         | 3.88%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 91        | 88.35%  |
| Yes       | 12        | 11.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| ASUSTek Computer         | 22        | 21.36%  |
| Hewlett-Packard          | 15        | 14.56%  |
| Dell                     | 12        | 11.65%  |
| Lenovo                   | 11        | 10.68%  |
| MSI                      | 6         | 5.83%   |
| Acer                     | 6         | 5.83%   |
| Toshiba                  | 4         | 3.88%   |
| Intel                    | 3         | 2.91%   |
| Gigabyte Technology      | 3         | 2.91%   |
| Samsung Electronics      | 2         | 1.94%   |
| Notebook                 | 2         | 1.94%   |
| K.A.Technologies Limited | 2         | 1.94%   |
| ASRock                   | 2         | 1.94%   |
| Timi                     | 1         | 0.97%   |
| Sony                     | 1         | 0.97%   |
| Razer                    | 1         | 0.97%   |
| Purism                   | 1         | 0.97%   |
| Pegatron                 | 1         | 0.97%   |
| PCWare                   | 1         | 0.97%   |
| HUAWEI                   | 1         | 0.97%   |
| GPU Company              | 1         | 0.97%   |
| Fujitsu                  | 1         | 0.97%   |
| Foxconn                  | 1         | 0.97%   |
| eMachines                | 1         | 0.97%   |
| AXDIA International      | 1         | 0.97%   |
| Apple                    | 1         | 0.97%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| K.A.Technologies Limited TM1               | 2         | 1.94%   |
| Dell OptiPlex 3050                         | 2         | 1.94%   |
| ASUS All Series                            | 2         | 1.94%   |
| Toshiba TECRA M11                          | 1         | 0.97%   |
| Toshiba Satellite L750                     | 1         | 0.97%   |
| Toshiba Satellite C70D-B                   | 1         | 0.97%   |
| Toshiba Satellite A305                     | 1         | 0.97%   |
| Timi Xiaomi Book Pro 16 2022               | 1         | 0.97%   |
| Sony VPCEA23FB                             | 1         | 0.97%   |
| Samsung 550P5C/550P7C                      | 1         | 0.97%   |
| Samsung 305V4A/305V5A                      | 1         | 0.97%   |
| Razer Blade Stealth                        | 1         | 0.97%   |
| Purism Librem 14                           | 1         | 0.97%   |
| Pegatron IPXSB-H61                         | 1         | 0.97%   |
| PCWare IPX4005G                            | 1         | 0.97%   |
| Notebook PA70ES                            | 1         | 0.97%   |
| Notebook NL40_50CU                         | 1         | 0.97%   |
| MSI MS-7D22                                | 1         | 0.97%   |
| MSI MS-7C95                                | 1         | 0.97%   |
| MSI MS-7C94                                | 1         | 0.97%   |
| MSI MS-7C37                                | 1         | 0.97%   |
| MSI MS-7B84                                | 1         | 0.97%   |
| MSI MS-7B79                                | 1         | 0.97%   |
| Lenovo Yoga 720-15IKB 80X7                 | 1         | 0.97%   |
| Lenovo ThinkPad X1 Yoga 1st 20FQCTO1WW     | 1         | 0.97%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWS21H00 | 1         | 0.97%   |
| Lenovo ThinkPad T470s 20HFCTO1WW           | 1         | 0.97%   |
| Lenovo ThinkPad T420 4236WR1               | 1         | 0.97%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3003CUS       | 1         | 0.97%   |
| Lenovo ThinkCentre M900 10FCS24N00         | 1         | 0.97%   |
| Lenovo IdeaPadFlex 5 15ITL05 82HT          | 1         | 0.97%   |
| Lenovo IdeaPad S340-15IWL 81N8             | 1         | 0.97%   |
| Lenovo IdeaPad 5 Pro 16ARH7 82SN           | 1         | 0.97%   |
| Lenovo IdeaPad 320-15IKB 81BG              | 1         | 0.97%   |
| Intel NUC11PAHi5                           | 1         | 0.97%   |
| Intel H55                                  | 1         | 0.97%   |
| Intel DQ77KB AAG81483-500                  | 1         | 0.97%   |
| HUAWEI KLVL-WXXW                           | 1         | 0.97%   |
| HP ZBook 15u G6                            | 1         | 0.97%   |
| HP Victus by Laptop 16-d0xxx               | 1         | 0.97%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lenovo ThinkPad              | 5         | 4.85%   |
| Dell Inspiron                | 4         | 3.88%   |
| ASUS PRIME                   | 4         | 3.88%   |
| Acer Aspire                  | 4         | 3.88%   |
| Toshiba Satellite            | 3         | 2.91%   |
| Lenovo IdeaPad               | 3         | 2.91%   |
| HP Pavilion                  | 3         | 2.91%   |
| HP EliteBook                 | 3         | 2.91%   |
| Dell Vostro                  | 3         | 2.91%   |
| Dell OptiPlex                | 3         | 2.91%   |
| ASUS VivoBook                | 3         | 2.91%   |
| K.A.Technologies Limited TM1 | 2         | 1.94%   |
| HP Laptop                    | 2         | 1.94%   |
| ASUS All                     | 2         | 1.94%   |
| Toshiba TECRA                | 1         | 0.97%   |
| Timi Xiaomi                  | 1         | 0.97%   |
| Sony VPCEA23FB               | 1         | 0.97%   |
| Samsung 550P5C               | 1         | 0.97%   |
| Samsung 305V4A               | 1         | 0.97%   |
| Razer Blade                  | 1         | 0.97%   |
| Purism Librem                | 1         | 0.97%   |
| Pegatron IPXSB-H61           | 1         | 0.97%   |
| PCWare IPX4005G              | 1         | 0.97%   |
| Notebook PA70ES              | 1         | 0.97%   |
| Notebook NL40                | 1         | 0.97%   |
| MSI MS-7D22                  | 1         | 0.97%   |
| MSI MS-7C95                  | 1         | 0.97%   |
| MSI MS-7C94                  | 1         | 0.97%   |
| MSI MS-7C37                  | 1         | 0.97%   |
| MSI MS-7B84                  | 1         | 0.97%   |
| MSI MS-7B79                  | 1         | 0.97%   |
| Lenovo Yoga                  | 1         | 0.97%   |
| Lenovo ThinkCentre           | 1         | 0.97%   |
| Lenovo IdeaPadFlex           | 1         | 0.97%   |
| Intel NUC11PAHi5             | 1         | 0.97%   |
| Intel H55                    | 1         | 0.97%   |
| Intel DQ77KB                 | 1         | 0.97%   |
| HUAWEI KLVL-WXXW             | 1         | 0.97%   |
| HP ZBook                     | 1         | 0.97%   |
| HP Victus                    | 1         | 0.97%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 14        | 13.59%  |
| 2018 | 11        | 10.68%  |
| 2017 | 11        | 10.68%  |
| 2019 | 10        | 9.71%   |
| 2014 | 8         | 7.77%   |
| 2010 | 8         | 7.77%   |
| 2020 | 7         | 6.8%    |
| 2012 | 7         | 6.8%    |
| 2011 | 6         | 5.83%   |
| 2022 | 5         | 4.85%   |
| 2016 | 4         | 3.88%   |
| 2015 | 4         | 3.88%   |
| 2013 | 3         | 2.91%   |
| 2007 | 2         | 1.94%   |
| 2009 | 1         | 0.97%   |
| 2008 | 1         | 0.97%   |
| 2006 | 1         | 0.97%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 64        | 62.14%  |
| Desktop     | 34        | 33.01%  |
| Convertible | 4         | 3.88%   |
| Mini pc     | 1         | 0.97%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 98        | 95.15%  |
| Enabled  | 5         | 4.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 102       | 99.03%  |
| Yes  | 1         | 0.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 31        | 30.1%   |
| 16.01-24.0  | 26        | 25.24%  |
| 8.01-16.0   | 14        | 13.59%  |
| 32.01-64.0  | 12        | 11.65%  |
| 3.01-4.0    | 11        | 10.68%  |
| 24.01-32.0  | 3         | 2.91%   |
| 1.01-2.0    | 3         | 2.91%   |
| 64.01-256.0 | 2         | 1.94%   |
| 2.01-3.0    | 1         | 0.97%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 40        | 38.83%  |
| 1.01-2.0  | 27        | 26.21%  |
| 4.01-8.0  | 18        | 17.48%  |
| 3.01-4.0  | 12        | 11.65%  |
| 8.01-16.0 | 4         | 3.88%   |
| 0.51-1.0  | 2         | 1.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 58        | 56.31%  |
| 2      | 28        | 27.18%  |
| 3      | 11        | 10.68%  |
| 11     | 1         | 0.97%   |
| 10     | 1         | 0.97%   |
| 7      | 1         | 0.97%   |
| 6      | 1         | 0.97%   |
| 5      | 1         | 0.97%   |
| 4      | 1         | 0.97%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 70        | 67.96%  |
| Yes       | 33        | 32.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 92        | 89.32%  |
| No        | 11        | 10.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 80.58%  |
| No        | 20        | 19.42%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 66.99%  |
| No        | 34        | 33.01%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 22        | 21.36%  |
| Germany            | 11        | 10.68%  |
| UK                 | 7         | 6.8%    |
| France             | 6         | 5.83%   |
| Brazil             | 6         | 5.83%   |
| Italy              | 5         | 4.85%   |
| India              | 4         | 3.88%   |
| Greece             | 4         | 3.88%   |
| Sweden             | 3         | 2.91%   |
| Spain              | 3         | 2.91%   |
| Russia             | 3         | 2.91%   |
| Netherlands        | 3         | 2.91%   |
| Canada             | 3         | 2.91%   |
| Turkey             | 2         | 1.94%   |
| Tunisia            | 2         | 1.94%   |
| Poland             | 2         | 1.94%   |
| Ghana              | 2         | 1.94%   |
| Bulgaria           | 2         | 1.94%   |
| South Africa       | 1         | 0.97%   |
| Portugal           | 1         | 0.97%   |
| Philippines        | 1         | 0.97%   |
| Mexico             | 1         | 0.97%   |
| Malaysia           | 1         | 0.97%   |
| Israel             | 1         | 0.97%   |
| Iran               | 1         | 0.97%   |
| Indonesia          | 1         | 0.97%   |
| Dominican Republic | 1         | 0.97%   |
| Czechia            | 1         | 0.97%   |
| Chile              | 1         | 0.97%   |
| Belgium            | 1         | 0.97%   |
| Algeria            | 1         | 0.97%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Porto Alegre                | 2         | 1.94%   |
| Kansas City                 | 2         | 1.94%   |
| Brattleboro                 | 2         | 1.94%   |
| Atlanta                     | 2         | 1.94%   |
| Accra                       | 2         | 1.94%   |
| Zuidwolde                   | 1         | 0.97%   |
| Xhoris                      | 1         | 0.97%   |
| Wodzisław Śląski         | 1         | 0.97%   |
| Wiesbaden                   | 1         | 0.97%   |
| West Islip                  | 1         | 0.97%   |
| Warren                      | 1         | 0.97%   |
| Vila Real de Santo António | 1         | 0.97%   |
| Varna                       | 1         | 0.97%   |
| Vancouver                   | 1         | 0.97%   |
| Valence                     | 1         | 0.97%   |
| Vaernamo                    | 1         | 0.97%   |
| Turin                       | 1         | 0.97%   |
| Tunis                       | 1         | 0.97%   |
| Trenton                     | 1         | 0.97%   |
| The Hague                   | 1         | 0.97%   |
| Tehran                      | 1         | 0.97%   |
| Sterling                    | 1         | 0.97%   |
| Stapelfeld                  | 1         | 0.97%   |
| Sofia                       | 1         | 0.97%   |
| Serres                      | 1         | 0.97%   |
| Schuettorf                  | 1         | 0.97%   |
| Santiago de los Caballeros  | 1         | 0.97%   |
| Santiago                    | 1         | 0.97%   |
| Sant Vicenc de Montalt      | 1         | 0.97%   |
| Saltillo                    | 1         | 0.97%   |
| Saint-Nazaire               | 1         | 0.97%   |
| Saint-Julien-les-Villas     | 1         | 0.97%   |
| Rochester                   | 1         | 0.97%   |
| Rochefort                   | 1         | 0.97%   |
| Rio de Janeiro              | 1         | 0.97%   |
| Richmond Hill               | 1         | 0.97%   |
| Rhodes                      | 1         | 0.97%   |
| Rechitsy                    | 1         | 0.97%   |
| Rapid City                  | 1         | 0.97%   |
| Portogruaro                 | 1         | 0.97%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 33        | 44     | 21.15%  |
| WDC                         | 18        | 20     | 11.54%  |
| Seagate                     | 16        | 21     | 10.26%  |
| Sandisk                     | 11        | 12     | 7.05%   |
| Crucial                     | 10        | 11     | 6.41%   |
| Toshiba                     | 7         | 10     | 4.49%   |
| SK hynix                    | 6         | 6      | 3.85%   |
| Phison Electronics          | 6         | 12     | 3.85%   |
| Hitachi                     | 5         | 5      | 3.21%   |
| KIOXIA                      | 4         | 4      | 2.56%   |
| Kingston Technology Company | 4         | 5      | 2.56%   |
| Kingston                    | 4         | 4      | 2.56%   |
| Unknown                     | 3         | 3      | 1.92%   |
| Netac                       | 3         | 3      | 1.92%   |
| Intel                       | 3         | 4      | 1.92%   |
| China                       | 3         | 3      | 1.92%   |
| A-DATA Technology           | 3         | 3      | 1.92%   |
| Micron/Crucial Technology   | 2         | 2      | 1.28%   |
| Micron Technology           | 2         | 2      | 1.28%   |
| HGST                        | 2         | 2      | 1.28%   |
| GOODRAM                     | 2         | 2      | 1.28%   |
| Unknown                     | 2         | 2      | 1.28%   |
| USB3.0                      | 1         | 1      | 0.64%   |
| Silicon Motion              | 1         | 1      | 0.64%   |
| Lexar                       | 1         | 1      | 0.64%   |
| Intenso                     | 1         | 1      | 0.64%   |
| Hewlett-Packard             | 1         | 1      | 0.64%   |
| Gigabyte Technology         | 1         | 1      | 0.64%   |
| ADATA Technology            | 1         | 1      | 0.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 9         | 5.23%   |
| Seagate ST1000LM035-1RK172 1TB                       | 5         | 2.91%   |
| Phison PS5013 E13 NVMe Controller 256GB              | 4         | 2.33%   |
| Toshiba MQ01ABD100 1TB                               | 3         | 1.74%   |
| Netac SSD 256GB                                      | 3         | 1.74%   |
| Kingston Company A2000 NVMe SSD 500GB                | 3         | 1.74%   |
| Toshiba MQ01ABF050 500GB                             | 2         | 1.16%   |
| Sandisk WD Blue SN570 500GB                          | 2         | 1.16%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                   | 2         | 1.16%   |
| Samsung SSD 980 1TB                                  | 2         | 1.16%   |
| Samsung SSD 860 EVO 500GB                            | 2         | 1.16%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 250GB  | 2         | 1.16%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 250GB | 2         | 1.16%   |
| Samsung MZVLQ512HALU-000H1 512GB                     | 2         | 1.16%   |
| Samsung HD642JJ 640GB                                | 2         | 1.16%   |
| Phison E12 NVMe Controller 2TB                       | 2         | 1.16%   |
| Micron/Crucial P2 NVMe PCIe SSD 250GB                | 2         | 1.16%   |
| KIOXIA KBG40ZNS256G NVMe 256GB                       | 2         | 1.16%   |
| Crucial CT240BX500SSD1 240GB                         | 2         | 1.16%   |
| Crucial CT1000MX500SSD1 1TB                          | 2         | 1.16%   |
| Unknown                                              | 2         | 1.16%   |
| WDC WDS500G2B0A 500GB SSD                            | 1         | 0.58%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                     | 1         | 0.58%   |
| WDC WD60EFRX-68MYMN1 6TB                             | 1         | 0.58%   |
| WDC WD5003AZEX-00K1GA0 500GB                         | 1         | 0.58%   |
| WDC WD5000LPCX-21VHAT0 500GB                         | 1         | 0.58%   |
| WDC WD3200LPLX-75ZNTT0 320GB                         | 1         | 0.58%   |
| WDC WD3200BPVT-22JJ5T0 320GB                         | 1         | 0.58%   |
| WDC WD3200BEVT-22ZCT0 320GB                          | 1         | 0.58%   |
| WDC WD20EARX-00PASB0 2TB                             | 1         | 0.58%   |
| WDC WD15EARS-60MVWB0 1TB                             | 1         | 0.58%   |
| WDC WD10SPZX-21Z10T0 1TB                             | 1         | 0.58%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 1         | 0.58%   |
| WDC WD10JPVX-00JC3T0 1TB                             | 1         | 0.58%   |
| WDC WD10JPCX-24UE4T0 1TB                             | 1         | 0.58%   |
| WDC WD10EZEX-22MFCA0 1TB                             | 1         | 0.58%   |
| WDC WD10EZEX-00BN5A0 1TB                             | 1         | 0.58%   |
| WDC WD1003FZEX-00MK2A0 1TB                           | 1         | 0.58%   |
| WDC WD Blue SA510 2.5 1TB                            | 1         | 0.58%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB                 | 1         | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 21     | 33.33%  |
| WDC                 | 14        | 16     | 29.17%  |
| Toshiba             | 7         | 10     | 14.58%  |
| Hitachi             | 5         | 5      | 10.42%  |
| Samsung Electronics | 3         | 4      | 6.25%   |
| HGST                | 2         | 2      | 4.17%   |
| Unknown             | 1         | 1      | 2.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 13     | 24%     |
| Crucial             | 10        | 11     | 20%     |
| WDC                 | 3         | 3      | 6%      |
| SK hynix            | 3         | 3      | 6%      |
| SanDisk             | 3         | 3      | 6%      |
| Netac               | 3         | 3      | 6%      |
| Kingston            | 3         | 3      | 6%      |
| China               | 3         | 3      | 6%      |
| A-DATA Technology   | 3         | 3      | 6%      |
| GOODRAM             | 2         | 2      | 4%      |
| USB3.0              | 1         | 1      | 2%      |
| Lexar               | 1         | 1      | 2%      |
| Intel               | 1         | 1      | 2%      |
| Hewlett-Packard     | 1         | 1      | 2%      |
| Gigabyte Technology | 1         | 1      | 2%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 48        | 70     | 34.29%  |
| SSD     | 44        | 52     | 31.43%  |
| HDD     | 42        | 59     | 30%     |
| MMC     | 3         | 3      | 2.14%   |
| Unknown | 3         | 3      | 2.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 73        | 108    | 55.73%  |
| NVMe | 48        | 69     | 36.64%  |
| SAS  | 7         | 7      | 5.34%   |
| MMC  | 3         | 3      | 2.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 48        | 58     | 57.14%  |
| 0.51-1.0   | 29        | 40     | 34.52%  |
| 2.01-3.0   | 2         | 2      | 2.38%   |
| 1.01-2.0   | 2         | 3      | 2.38%   |
| 4.01-10.0  | 2         | 4      | 2.38%   |
| 10.01-20.0 | 1         | 4      | 1.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 24        | 23.3%   |
| 101-250        | 22        | 21.36%  |
| 501-1000       | 20        | 19.42%  |
| 1001-2000      | 10        | 9.71%   |
| 51-100         | 9         | 8.74%   |
| 21-50          | 6         | 5.83%   |
| More than 3000 | 4         | 3.88%   |
| 1-20           | 4         | 3.88%   |
| Unknown        | 3         | 2.91%   |
| 2001-3000      | 1         | 0.97%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 39        | 37.86%  |
| 51-100         | 18        | 17.48%  |
| 21-50          | 17        | 16.5%   |
| 101-250        | 8         | 7.77%   |
| 251-500        | 7         | 6.8%    |
| 501-1000       | 5         | 4.85%   |
| More than 3000 | 4         | 3.88%   |
| Unknown        | 3         | 2.91%   |
| 1001-2000      | 2         | 1.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-22JJ5T0 320GB   | 1         | 1      | 50%     |
| Seagate ST1000LM035-1RK172 1TB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

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
| Detected | 92        | 168    | 85.98%  |
| Works    | 13        | 17     | 12.15%  |
| Malfunc  | 2         | 2      | 1.87%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 65        | 44.52%  |
| AMD                         | 23        | 15.75%  |
| Samsung Electronics         | 21        | 14.38%  |
| SanDisk                     | 8         | 5.48%   |
| Phison Electronics          | 6         | 4.11%   |
| Kingston Technology Company | 5         | 3.42%   |
| KIOXIA                      | 4         | 2.74%   |
| SK hynix                    | 3         | 2.05%   |
| JMicron Technology          | 3         | 2.05%   |
| Micron/Crucial Technology   | 2         | 1.37%   |
| Micron Technology           | 2         | 1.37%   |
| ASMedia Technology          | 2         | 1.37%   |
| Silicon Motion              | 1         | 0.68%   |
| ADATA Technology            | 1         | 0.68%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 17        | 10.12%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10        | 5.95%   |
| Samsung NVMe SSD Controller 980                                                         | 6         | 3.57%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 5         | 2.98%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4         | 2.38%   |
| Phison PS5013 E13 NVMe Controller                                                       | 4         | 2.38%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4         | 2.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 2.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 4         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 4         | 2.38%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 3         | 1.79%   |
| SanDisk WD Blue SN570 NVMe SSD                                                          | 3         | 1.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3         | 1.79%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 3         | 1.79%   |
| Kingston Company A2000 NVMe SSD                                                         | 3         | 1.79%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 1.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 1.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3         | 1.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3         | 1.79%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 1.79%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 1.79%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2         | 1.19%   |
| SanDisk Non-Volatile memory controller                                                  | 2         | 1.19%   |
| Phison E12 NVMe Controller                                                              | 2         | 1.19%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2         | 1.19%   |
| Micron Non-Volatile memory controller                                                   | 2         | 1.19%   |
| Kingston Company Company Non-Volatile memory controller                                 | 2         | 1.19%   |
| JMicron JMB360 AHCI Controller                                                          | 2         | 1.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 1.19%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 1.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 1.19%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2         | 1.19%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 1.19%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 2         | 1.19%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 1.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.19%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.19%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 74        | 51.39%  |
| NVMe | 48        | 33.33%  |
| RAID | 12        | 8.33%   |
| IDE  | 10        | 6.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 78        | 75.73%  |
| AMD    | 25        | 24.27%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz        | 3         | 2.91%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 3         | 2.91%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 3         | 2.91%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 1.94%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 2         | 1.94%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 1.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 2         | 1.94%   |
| Intel Core i3 CPU M 330 @ 2.13GHz       | 2         | 1.94%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 1.94%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 1.94%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz | 2         | 1.94%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 2         | 1.94%   |
| Intel Xeon CPU E31245 @ 3.30GHz         | 1         | 0.97%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 0.97%   |
| Intel Core i7-8700T CPU @ 2.40GHz       | 1         | 0.97%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 0.97%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 0.97%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1         | 0.97%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 0.97%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 1         | 0.97%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 1         | 0.97%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 1         | 0.97%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 1         | 0.97%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 1         | 0.97%   |
| Intel Core i7-3770T CPU @ 2.50GHz       | 1         | 0.97%   |
| Intel Core i7-2820QM CPU @ 2.30GHz      | 1         | 0.97%   |
| Intel Core i7-10710U CPU @ 1.10GHz      | 1         | 0.97%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 0.97%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 0.97%   |
| Intel Core i5-7600K CPU @ 3.80GHz       | 1         | 0.97%   |
| Intel Core i5-6400T CPU @ 2.20GHz       | 1         | 0.97%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 0.97%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 1         | 0.97%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 1         | 0.97%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 1         | 0.97%   |
| Intel Core i5-3330 CPU @ 3.00GHz        | 1         | 0.97%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 1         | 0.97%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 1         | 0.97%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 1         | 0.97%   |
| Intel Core i5-10600K CPU @ 4.10GHz      | 1         | 0.97%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 25        | 24.27%  |
| Intel Core i7           | 21        | 20.39%  |
| AMD Ryzen 5             | 11        | 10.68%  |
| Other                   | 10        | 9.71%   |
| Intel Core i3           | 10        | 9.71%   |
| Intel Celeron           | 7         | 6.8%    |
| AMD Ryzen 7             | 3         | 2.91%   |
| AMD A8                  | 2         | 1.94%   |
| Intel Xeon              | 1         | 0.97%   |
| Intel Core 2 Duo        | 1         | 0.97%   |
| Intel Core 2            | 1         | 0.97%   |
| Intel Celeron M         | 1         | 0.97%   |
| Intel Atom              | 1         | 0.97%   |
| AMD Turion 64 X2 Mobile | 1         | 0.97%   |
| AMD Ryzen Threadripper  | 1         | 0.97%   |
| AMD Ryzen 9             | 1         | 0.97%   |
| AMD Ryzen 3             | 1         | 0.97%   |
| AMD Phenom II X6        | 1         | 0.97%   |
| AMD FX                  | 1         | 0.97%   |
| AMD E1                  | 1         | 0.97%   |
| AMD Athlon II X2        | 1         | 0.97%   |
| AMD A6                  | 1         | 0.97%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 41        | 39.81%  |
| 2      | 34        | 33.01%  |
| 6      | 16        | 15.53%  |
| 8      | 5         | 4.85%   |
| 12     | 3         | 2.91%   |
| 1      | 3         | 2.91%   |
| 16     | 1         | 0.97%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 103       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 77        | 74.76%  |
| 1      | 26        | 25.24%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 103       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 79        | 76.7%   |
| 0x806ea    | 3         | 2.91%   |
| 0x806c1    | 2         | 1.94%   |
| 0x306a9    | 2         | 1.94%   |
| 0xa0653    | 1         | 0.97%   |
| 0x906e9    | 1         | 0.97%   |
| 0x906a3    | 1         | 0.97%   |
| 0x806ec    | 1         | 0.97%   |
| 0x806e9    | 1         | 0.97%   |
| 0x806d1    | 1         | 0.97%   |
| 0x706a8    | 1         | 0.97%   |
| 0x6f6      | 1         | 0.97%   |
| 0x506e3    | 1         | 0.97%   |
| 0x406e3    | 1         | 0.97%   |
| 0x306d4    | 1         | 0.97%   |
| 0x306c3    | 1         | 0.97%   |
| 0x30678    | 1         | 0.97%   |
| 0x206a7    | 1         | 0.97%   |
| 0x20652    | 1         | 0.97%   |
| 0x07030105 | 1         | 0.97%   |
| 0x010000dc | 1         | 0.97%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 19        | 18.45%  |
| Haswell          | 8         | 7.77%   |
| Unknown          | 7         | 6.8%    |
| Zen 3            | 6         | 5.83%   |
| Westmere         | 6         | 5.83%   |
| TigerLake        | 6         | 5.83%   |
| Skylake          | 6         | 5.83%   |
| SandyBridge      | 6         | 5.83%   |
| IvyBridge        | 5         | 4.85%   |
| Zen+             | 3         | 2.91%   |
| Zen              | 3         | 2.91%   |
| Goldmont plus    | 3         | 2.91%   |
| Core             | 3         | 2.91%   |
| CometLake        | 3         | 2.91%   |
| Silvermont       | 2         | 1.94%   |
| K10 Llano        | 2         | 1.94%   |
| K10              | 2         | 1.94%   |
| IceLake          | 2         | 1.94%   |
| Goldmont         | 2         | 1.94%   |
| Broadwell        | 2         | 1.94%   |
| Zen 2            | 1         | 0.97%   |
| Steamroller      | 1         | 0.97%   |
| Puma             | 1         | 0.97%   |
| Piledriver       | 1         | 0.97%   |
| Penryn           | 1         | 0.97%   |
| K8 Hammer        | 1         | 0.97%   |
| Alderlake Hybrid | 1         | 0.97%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 63        | 48.84%  |
| Nvidia | 41        | 31.78%  |
| AMD    | 25        | 19.38%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 6         | 4.55%   |
| Intel Core Processor Integrated Graphics Controller                         | 4         | 3.03%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 2.27%   |
| Intel UHD Graphics 620                                                      | 3         | 2.27%   |
| Intel HD Graphics 620                                                       | 3         | 2.27%   |
| Intel HD Graphics 530                                                       | 3         | 2.27%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 2.27%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 2.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3         | 2.27%   |
| AMD Lucienne                                                                | 3         | 2.27%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 1.52%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2         | 1.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 1.52%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 1.52%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 2         | 1.52%   |
| Intel HD Graphics 630                                                       | 2         | 1.52%   |
| Intel HD Graphics 5500                                                      | 2         | 1.52%   |
| Intel HD Graphics 500                                                       | 2         | 1.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.52%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 1.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 2         | 1.52%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 1.52%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2         | 1.52%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 1.52%   |
| Nvidia TU117M                                                               | 1         | 0.76%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1         | 0.76%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1         | 0.76%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 1         | 0.76%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1         | 0.76%   |
| Nvidia GT216M [GeForce GT 325M]                                             | 1         | 0.76%   |
| Nvidia GP108M [GeForce MX330]                                               | 1         | 0.76%   |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 0.76%   |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 0.76%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                 | 1         | 0.76%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                | 1         | 0.76%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.76%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 42        | 40.78%  |
| Intel + Nvidia | 19        | 18.45%  |
| 1 x Nvidia     | 18        | 17.48%  |
| 1 x AMD        | 17        | 16.5%   |
| AMD + Nvidia   | 4         | 3.88%   |
| 2 x AMD        | 2         | 1.94%   |
| Intel + AMD    | 1         | 0.97%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 90        | 87.38%  |
| Proprietary | 12        | 11.65%  |
| Unknown     | 1         | 0.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 89        | 86.41%  |
| 1.01-2.0   | 4         | 3.88%   |
| 7.01-8.0   | 3         | 2.91%   |
| 3.01-4.0   | 3         | 2.91%   |
| 0.01-0.5   | 3         | 2.91%   |
| 0.51-1.0   | 1         | 0.97%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 19        | 16.52%  |
| AU Optronics            | 16        | 13.91%  |
| BOE                     | 13        | 11.3%   |
| LG Display              | 12        | 10.43%  |
| Goldstar                | 7         | 6.09%   |
| Dell                    | 7         | 6.09%   |
| AOC                     | 5         | 4.35%   |
| Acer                    | 5         | 4.35%   |
| Ancor Communications    | 4         | 3.48%   |
| Iiyama                  | 3         | 2.61%   |
| Hewlett-Packard         | 3         | 2.61%   |
| Sharp                   | 2         | 1.74%   |
| Gigabyte Technology     | 2         | 1.74%   |
| Chimei Innolux          | 2         | 1.74%   |
| Chi Mei Optoelectronics | 2         | 1.74%   |
| Vizio                   | 1         | 0.87%   |
| Philips                 | 1         | 0.87%   |
| PANDA                   | 1         | 0.87%   |
| Panasonic               | 1         | 0.87%   |
| NEC Computers           | 1         | 0.87%   |
| Lenovo                  | 1         | 0.87%   |
| InfoVision              | 1         | 0.87%   |
| Idek Iiyama             | 1         | 0.87%   |
| Hitachi                 | 1         | 0.87%   |
| CASIO                   | 1         | 0.87%   |
| BenQ                    | 1         | 0.87%   |
| ASUSTek Computer        | 1         | 0.87%   |
| Apple                   | 1         | 0.87%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 3         | 2.52%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch   | 2         | 1.68%   |
| Samsung Electronics LCD Monitor SAM065F 1360x768                       | 2         | 1.68%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch           | 2         | 1.68%   |
| BOE LCD Monitor BOE06F8 1366x768 293x165mm 13.2-inch                   | 2         | 1.68%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch          | 2         | 1.68%   |
| Vizio D43f-F1 VIZ1027 1920x1080 940x529mm 42.5-inch                    | 1         | 0.84%   |
| Sharp LQ133Z1JW26 SHP1493 3200x1800 294x165mm 13.3-inch                | 1         | 0.84%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 294x165mm 13.3-inch                | 1         | 0.84%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                       | 1         | 0.84%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 530x300mm 24.0-inch    | 1         | 0.84%   |
| Samsung Electronics SMT24A550 SAM07B3 1920x1080 530x300mm 24.0-inch    | 1         | 0.84%   |
| Samsung Electronics S16B110 SAM097E 1366x768 360x210mm 16.4-inch       | 1         | 0.84%   |
| Samsung Electronics LS24AG32x SAM71D9 1920x1080 527x296mm 23.8-inch    | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch   | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC524D 1366x768 353x198mm 15.9-inch   | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch   | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch   | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch   | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch  | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC424B 3840x2160 344x194mm 15.5-inch  | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4173 3840x2400 344x215mm 16.0-inch  | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch  | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SAM0B90 3840x2160 1210x680mm 54.6-inch | 1         | 0.84%   |
| Samsung Electronics LCD Monitor S27E332 3200x1080                      | 1         | 0.84%   |
| Philips 170S PHL0839 1280x1024 338x270mm 17.0-inch                     | 1         | 0.84%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                | 1         | 0.84%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch            | 1         | 0.84%   |
| NEC Computers LCD Monitor LCD190V                                      | 1         | 0.84%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch            | 1         | 0.84%   |
| LG Display LCD Monitor LGD05F3 1920x1080 309x174mm 14.0-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD0506 1366x768 344x194mm 15.5-inch            | 1         | 0.84%   |
| LG Display LCD Monitor LGD0493 1366x768 344x194mm 15.5-inch            | 1         | 0.84%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD0396 1600x900 382x215mm 17.3-inch            | 1         | 0.84%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch           | 1         | 0.84%   |
| Lenovo G27q-20 LEN66C3 2560x1440 597x336mm 27.0-inch                   | 1         | 0.84%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 46        | 41.44%  |
| 1366x768 (WXGA)    | 18        | 16.22%  |
| 3840x2160 (4K)     | 12        | 10.81%  |
| 2560x1440 (QHD)    | 10        | 9.01%   |
| 1600x900 (HD+)     | 4         | 3.6%    |
| 2560x1600          | 2         | 1.8%    |
| 1680x1050 (WSXGA+) | 2         | 1.8%    |
| 1360x768           | 2         | 1.8%    |
| 1280x800 (WXGA)    | 2         | 1.8%    |
| 1280x1024 (SXGA)   | 2         | 1.8%    |
| Unknown            | 2         | 1.8%    |
| 3840x2400          | 1         | 0.9%    |
| 3600x1080          | 1         | 0.9%    |
| 3440x1440          | 1         | 0.9%    |
| 3200x1800 (QHD+)   | 1         | 0.9%    |
| 3200x1080          | 1         | 0.9%    |
| 2560x1080          | 1         | 0.9%    |
| 2160x1440          | 1         | 0.9%    |
| 1920x1200 (WUXGA)  | 1         | 0.9%    |
| 1440x900 (WXGA+)   | 1         | 0.9%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 33        | 29.2%   |
| 27      | 11        | 9.73%   |
| 24      | 9         | 7.96%   |
| 17      | 9         | 7.96%   |
| 13      | 8         | 7.08%   |
| 23      | 6         | 5.31%   |
| 14      | 6         | 5.31%   |
| 16      | 5         | 4.42%   |
| Unknown | 5         | 4.42%   |
| 31      | 3         | 2.65%   |
| 84      | 2         | 1.77%   |
| 34      | 2         | 1.77%   |
| 22      | 2         | 1.77%   |
| 18      | 2         | 1.77%   |
| 11      | 2         | 1.77%   |
| 72      | 1         | 0.88%   |
| 49      | 1         | 0.88%   |
| 33      | 1         | 0.88%   |
| 32      | 1         | 0.88%   |
| 25      | 1         | 0.88%   |
| 21      | 1         | 0.88%   |
| 20      | 1         | 0.88%   |
| 19      | 1         | 0.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 43        | 39.45%  |
| 501-600     | 24        | 22.02%  |
| 351-400     | 12        | 11.01%  |
| 201-300     | 9         | 8.26%   |
| 401-500     | 5         | 4.59%   |
| Unknown     | 5         | 4.59%   |
| 601-700     | 4         | 3.67%   |
| 701-800     | 3         | 2.75%   |
| 1501-2000   | 3         | 2.75%   |
| 1001-1500   | 1         | 0.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 84        | 82.35%  |
| 16/10   | 10        | 9.8%    |
| 5/4     | 3         | 2.94%   |
| 21/9    | 2         | 1.96%   |
| Unknown | 2         | 1.96%   |
| 3/2     | 1         | 0.98%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 30.91%  |
| 201-250        | 17        | 15.45%  |
| 301-350        | 11        | 10%     |
| 81-90          | 9         | 8.18%   |
| 351-500        | 6         | 5.45%   |
| 121-130        | 6         | 5.45%   |
| 71-80          | 5         | 4.55%   |
| Unknown        | 5         | 4.55%   |
| More than 1000 | 4         | 3.64%   |
| 111-120        | 4         | 3.64%   |
| 141-150        | 3         | 2.73%   |
| 51-60          | 2         | 1.82%   |
| 151-200        | 2         | 1.82%   |
| 251-300        | 1         | 0.91%   |
| 131-140        | 1         | 0.91%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 35        | 32.41%  |
| 121-160       | 30        | 27.78%  |
| 101-120       | 25        | 23.15%  |
| 161-240       | 7         | 6.48%   |
| More than 240 | 5         | 4.63%   |
| Unknown       | 5         | 4.63%   |
| 1-50          | 1         | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 83        | 80.58%  |
| 2     | 18        | 17.48%  |
| 3     | 2         | 1.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 62        | 38.99%  |
| Intel                           | 46        | 28.93%  |
| Qualcomm Atheros                | 20        | 12.58%  |
| Broadcom                        | 6         | 3.77%   |
| Samsung Electronics             | 3         | 1.89%   |
| Ralink                          | 3         | 1.89%   |
| MediaTek                        | 3         | 1.89%   |
| Broadcom Limited                | 2         | 1.26%   |
| ASIX Electronics                | 2         | 1.26%   |
| Xiaomi                          | 1         | 0.63%   |
| TP-Link                         | 1         | 0.63%   |
| Sierra Wireless                 | 1         | 0.63%   |
| Ralink Technology               | 1         | 0.63%   |
| Qualcomm Atheros Communications | 1         | 0.63%   |
| NetGear                         | 1         | 0.63%   |
| Motorola PCS                    | 1         | 0.63%   |
| MosChip Semiconductor           | 1         | 0.63%   |
| Marvell Technology Group        | 1         | 0.63%   |
| JMicron Technology              | 1         | 0.63%   |
| DisplayLink                     | 1         | 0.63%   |
| Dell                            | 1         | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 20.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 5.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 2.09%   |
| Intel Wireless 8265 / 8275                                        | 4         | 2.09%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 2.09%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 1.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 1.57%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.57%   |
| Intel I211 Gigabit Network Connection                             | 3         | 1.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.57%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 1.05%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 1.05%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.05%   |
| Realtek Realtek Network controller                                | 2         | 1.05%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 1.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.05%   |
| Intel Wireless-AC 9260                                            | 2         | 1.05%   |
| Intel Wireless 8260                                               | 2         | 1.05%   |
| Intel Wireless 7265                                               | 2         | 1.05%   |
| Intel Wireless 7260                                               | 2         | 1.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 1.05%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.05%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.05%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.05%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.05%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.05%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.05%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.05%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.52%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.52%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 42.05%  |
| Realtek Semiconductor           | 17        | 19.32%  |
| Qualcomm Atheros                | 17        | 19.32%  |
| Broadcom                        | 5         | 5.68%   |
| Ralink                          | 3         | 3.41%   |
| MediaTek                        | 2         | 2.27%   |
| Broadcom Limited                | 2         | 2.27%   |
| Sierra Wireless                 | 1         | 1.14%   |
| Ralink Technology               | 1         | 1.14%   |
| Qualcomm Atheros Communications | 1         | 1.14%   |
| NetGear                         | 1         | 1.14%   |
| Dell                            | 1         | 1.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 5         | 5.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 4         | 4.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 4         | 4.55%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 4.55%   |
| Intel Wi-Fi 6 AX201                                                                   | 4         | 4.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 3.41%   |
| Intel Wi-Fi 6 AX200                                                                   | 3         | 3.41%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 2.27%   |
| Realtek Realtek Network controller                                                    | 2         | 2.27%   |
| Realtek 802.11n WLAN Adapter                                                          | 2         | 2.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 2         | 2.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 2         | 2.27%   |
| Intel Wireless-AC 9260                                                                | 2         | 2.27%   |
| Intel Wireless 8260                                                                   | 2         | 2.27%   |
| Intel Wireless 7265                                                                   | 2         | 2.27%   |
| Intel Wireless 7260                                                                   | 2         | 2.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 2         | 2.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 2.27%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 2         | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 2.27%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 2         | 2.27%   |
| Sierra Wireless EM7305 Modem                                                          | 1         | 1.14%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 1         | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.14%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                            | 1         | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 1.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 1.14%   |
| Realtek 802.11ac NIC                                                                  | 1         | 1.14%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                     | 1         | 1.14%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                             | 1         | 1.14%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                             | 1         | 1.14%   |
| Ralink RT2800 802.11n PCI                                                             | 1         | 1.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 1.14%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 1.14%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 1.14%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.14%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                           | 1         | 1.14%   |
| Intel WLAN controller                                                                 | 1         | 1.14%   |
| Intel Wireless 3160                                                                   | 1         | 1.14%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 56        | 54.9%   |
| Intel                    | 27        | 26.47%  |
| Qualcomm Atheros         | 4         | 3.92%   |
| Samsung Electronics      | 3         | 2.94%   |
| Broadcom                 | 2         | 1.96%   |
| ASIX Electronics         | 2         | 1.96%   |
| Xiaomi                   | 1         | 0.98%   |
| TP-Link                  | 1         | 0.98%   |
| Motorola PCS             | 1         | 0.98%   |
| MosChip Semiconductor    | 1         | 0.98%   |
| MediaTek                 | 1         | 0.98%   |
| Marvell Technology Group | 1         | 0.98%   |
| JMicron Technology       | 1         | 0.98%   |
| DisplayLink              | 1         | 0.98%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 39        | 37.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 9.71%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 3         | 2.91%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 2.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 2.91%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 2         | 1.94%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 1.94%   |
| Intel Ethernet Controller I225-V                                               | 2         | 1.94%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.94%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.94%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.94%   |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 1.94%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.97%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.97%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.97%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.97%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 1         | 0.97%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.97%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.97%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.97%   |
| Motorola PCS motorola one                                                      | 1         | 0.97%   |
| MosChip MCS7830 10/100 Mbps Ethernet adapter                                   | 1         | 0.97%   |
| MediaTek TECNO F1                                                              | 1         | 0.97%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.97%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.97%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.97%   |
| Intel Ethernet Controller I226-V                                               | 1         | 0.97%   |
| Intel Ethernet Connection I218-V                                               | 1         | 0.97%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.97%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.97%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.97%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.97%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.97%   |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 0.97%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.97%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.97%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.97%   |
| DisplayLink Dell Universal Dock D6000                                          | 1         | 0.97%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 92        | 52.57%  |
| WiFi     | 83        | 47.43%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 57        | 55.88%  |
| Ethernet | 45        | 44.12%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 60        | 58.25%  |
| 1     | 34        | 33.01%  |
| 3     | 5         | 4.85%   |
| 0     | 4         | 3.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 67        | 65.05%  |
| Yes  | 36        | 34.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 44.93%  |
| Qualcomm Atheros Communications | 8         | 11.59%  |
| Realtek Semiconductor           | 6         | 8.7%    |
| Lite-On Technology              | 4         | 5.8%    |
| IMC Networks                    | 4         | 5.8%    |
| Broadcom                        | 4         | 5.8%    |
| Cambridge Silicon Radio         | 3         | 4.35%   |
| ASUSTek Computer                | 3         | 4.35%   |
| Foxconn / Hon Hai               | 2         | 2.9%    |
| Toshiba                         | 1         | 1.45%   |
| Realtek                         | 1         | 1.45%   |
| Hewlett-Packard                 | 1         | 1.45%   |
| Apple                           | 1         | 1.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 15.94%  |
| Realtek Bluetooth Radio                             | 5         | 7.25%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 7.25%   |
| Intel AX201 Bluetooth                               | 5         | 7.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 4.35%   |
| Intel AX200 Bluetooth                               | 3         | 4.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 4.35%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 2.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 2.9%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.9%    |
| Intel Bluetooth Device                              | 2         | 2.9%    |
| Intel AX210 Bluetooth                               | 2         | 2.9%    |
| IMC Networks Bluetooth Radio                        | 2         | 2.9%    |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 2         | 2.9%    |
| Toshiba BCM43142A0                                  | 1         | 1.45%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.45%   |
| Realtek Bluetooth Radio                             | 1         | 1.45%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.45%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.45%   |
| Lite-On Wireless_Device                             | 1         | 1.45%   |
| Lite-On Bluetooth Device                            | 1         | 1.45%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.45%   |
| IMC Networks Wireless_Device                        | 1         | 1.45%   |
| IMC Networks Bluetooth Device                       | 1         | 1.45%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.45%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.45%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.45%   |
| Broadcom Bluetooth 3.0 Device                       | 1         | 1.45%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.45%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.45%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.45%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 1.45%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 77        | 50.99%  |
| AMD                    | 31        | 20.53%  |
| Nvidia                 | 28        | 18.54%  |
| C-Media Electronics    | 4         | 2.65%   |
| Texas Instruments      | 1         | 0.66%   |
| SlrTek                 | 1         | 0.66%   |
| Razer USA              | 1         | 0.66%   |
| Nintendo               | 1         | 0.66%   |
| JBL                    | 1         | 0.66%   |
| FIFINE Microphones     | 1         | 0.66%   |
| Elgato Systems         | 1         | 0.66%   |
| Creative Labs          | 1         | 0.66%   |
| Corsair                | 1         | 0.66%   |
| Conexant Systems       | 1         | 0.66%   |
| AKAI Professional M.I. | 1         | 0.66%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 8         | 4.57%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 4%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 3.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 3.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 3.43%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 3.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 2.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 2.86%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 2.86%   |
| Intel 200 Series PCH HD Audio                                              | 5         | 2.86%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 2.29%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.29%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 2.29%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 2.29%   |
| AMD FCH Azalia Controller                                                  | 4         | 2.29%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3         | 1.71%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.71%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.71%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 1.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.71%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.14%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.14%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 1.14%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 1.14%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.14%   |
| Nvidia GA102 High Definition Audio Controller                              | 2         | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.14%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 1.14%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.14%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.14%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.14%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 1.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.14%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.14%   |
| Intel Audio device                                                         | 2         | 1.14%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.14%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 18.52%  |
| SK hynix            | 4         | 14.81%  |
| Micron Technology   | 4         | 14.81%  |
| Kingston            | 4         | 14.81%  |
| Unknown             | 2         | 7.41%   |
| Crucial             | 2         | 7.41%   |
| Unknown (ABCD)      | 1         | 3.7%    |
| Team                | 1         | 3.7%    |
| GOODRAM             | 1         | 3.7%    |
| G.Skill             | 1         | 3.7%    |
| Elpida              | 1         | 3.7%    |
| Corsair             | 1         | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Kingston RAM Module 16GB SODIMM DDR4 2400MT/s                    | 2         | 7.14%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 1         | 3.57%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1066MT/s                   | 1         | 3.57%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 3.57%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 1         | 3.57%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8192MB DIMM DDR3 1600MT/s          | 1         | 3.57%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 3.57%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 3.57%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2048MB Row Of Chips 6400MT/s     | 1         | 3.57%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 3.57%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 3.57%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 3.57%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 3.57%   |
| Samsung RAM M378B5173QH0-CK0 4096MB DIMM DDR3 1600MT/s           | 1         | 3.57%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 3.57%   |
| Micron RAM Module 16GB SODIMM DDR4 3200MT/s                      | 1         | 3.57%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 1         | 3.57%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 1         | 3.57%   |
| Kingston RAM KF3000C15D4/8GX 8GB DIMM DDR4 3000MT/s              | 1         | 3.57%   |
| Kingston RAM 9905428-056.A00G 4GB SODIMM DDR3 1334MT/s           | 1         | 3.57%   |
| GOODRAM RAM IR2400D464L15S/8G 8GB DIMM DDR4 3200MT/s             | 1         | 3.57%   |
| G.Skill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s           | 1         | 3.57%   |
| Elpida RAM EDFB232A1MA-JD-F 8GB SODIMM LPDDR3 1867MT/s           | 1         | 3.57%   |
| Elpida RAM EDFB232A1MA-JD-F 8GB Chip LPDDR3 1867MT/s             | 1         | 3.57%   |
| Crucial RAM CT8G4SFS824A.C8FE 8GB SODIMM DDR4 2667MT/s           | 1         | 3.57%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 1         | 3.57%   |
| Corsair RAM CM4X4GD3000C15K4 4GB DIMM DDR4 2133MT/s              | 1         | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 9         | 40.91%  |
| DDR3   | 6         | 27.27%  |
| LPDDR4 | 3         | 13.64%  |
| LPDDR3 | 2         | 9.09%   |
| SDRAM  | 1         | 4.55%   |
| LPDDR5 | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 13        | 59.09%  |
| DIMM         | 5         | 22.73%  |
| Row Of Chips | 3         | 13.64%  |
| Chip         | 1         | 4.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 10        | 41.67%  |
| 4096  | 7         | 29.17%  |
| 16384 | 4         | 16.67%  |
| 1024  | 2         | 8.33%   |
| 2048  | 1         | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 4         | 16.67%  |
| 1600    | 4         | 16.67%  |
| 2400    | 3         | 12.5%   |
| 2667    | 2         | 8.33%   |
| 2133    | 2         | 8.33%   |
| 8400    | 1         | 4.17%   |
| 6400    | 1         | 4.17%   |
| 4267    | 1         | 4.17%   |
| 3000    | 1         | 4.17%   |
| 1867    | 1         | 4.17%   |
| 1866    | 1         | 4.17%   |
| 1334    | 1         | 4.17%   |
| 1066    | 1         | 4.17%   |
| Unknown | 1         | 4.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)

![Printer Vendor](./images/line_chart/printer_vendor.svg)

| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)

![Printer Model](./images/line_chart/printer_model.svg)

| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Seiko Epson WF-3520 Series | 1         | 50%     |
| Brother HL-L2320D series   | 1         | 50%     |

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
| Chicony Electronics                    | 14        | 20.9%   |
| Realtek Semiconductor                  | 7         | 10.45%  |
| IMC Networks                           | 6         | 8.96%   |
| Sunplus Innovation Technology          | 5         | 7.46%   |
| Logitech                               | 5         | 7.46%   |
| Acer                                   | 5         | 7.46%   |
| Quanta                                 | 4         | 5.97%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5.97%   |
| Y Media                                | 2         | 2.99%   |
| Suyin                                  | 2         | 2.99%   |
| Silicon Motion                         | 2         | 2.99%   |
| Samsung Electronics                    | 2         | 2.99%   |
| Microdia                               | 2         | 2.99%   |
| Lite-On Technology                     | 2         | 2.99%   |
| Apple                                  | 2         | 2.99%   |
| MacroSilicon                           | 1         | 1.49%   |
| DJKANA19IDX53W                         | 1         | 1.49%   |
| Arkmicro Technologies                  | 1         | 1.49%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD             | 3         | 4.48%   |
| Chicony integrated camera                | 3         | 4.48%   |
| Y Media USB Camera                       | 2         | 2.99%   |
| Samsung Galaxy series, misc. (MTP mode)  | 2         | 2.99%   |
| Quanta HP TrueVision HD Camera           | 2         | 2.99%   |
| IMC Networks USB2.0 HD UVC WebCam        | 2         | 2.99%   |
| IMC Networks Integrated Camera           | 2         | 2.99%   |
| Chicony HD WebCam                        | 2         | 2.99%   |
| Suyin Laptop_Integrated_Webcam_HD        | 1         | 1.49%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 1         | 1.49%   |
| Sunplus XiaoMi WebCam                    | 1         | 1.49%   |
| Sunplus USB Camera                       | 1         | 1.49%   |
| Sunplus MTD camera                       | 1         | 1.49%   |
| Sunplus Integrated_Webcam_HD             | 1         | 1.49%   |
| Sunplus Asus Webcam                      | 1         | 1.49%   |
| Silicon Motion WebCam SCB-1100N          | 1         | 1.49%   |
| Silicon Motion WebCam SC-13HDL11939N     | 1         | 1.49%   |
| Realtek USB Camera                       | 1         | 1.49%   |
| Realtek Lenovo easy camera               | 1         | 1.49%   |
| Realtek FJ Camera                        | 1         | 1.49%   |
| Realtek Dell_Monitor_IR_Webcam           | 1         | 1.49%   |
| Quanta USB2.0 VGA UVC WebCam             | 1         | 1.49%   |
| Quanta HD User Facing                    | 1         | 1.49%   |
| Microdia Integrated_Webcam_HD            | 1         | 1.49%   |
| Microdia Integrated Camera               | 1         | 1.49%   |
| MacroSilicon USB Video                   | 1         | 1.49%   |
| Logitech Webcam C930e                    | 1         | 1.49%   |
| Logitech Webcam C270                     | 1         | 1.49%   |
| Logitech StreamCam                       | 1         | 1.49%   |
| Logitech Logi Webcam C920e               | 1         | 1.49%   |
| Logitech HD Webcam C510                  | 1         | 1.49%   |
| Lite-On HP Wide Vision HD Camera         | 1         | 1.49%   |
| Lite-On HP HD Camera                     | 1         | 1.49%   |
| IMC Networks Integrated RGB Camera       | 1         | 1.49%   |
| IMC Networks HP TrueVision HD Camera     | 1         | 1.49%   |
| DJKANA19IDX53W HP Wide Vision HD Camera  | 1         | 1.49%   |
| Chicony USB2.0 VGA UVC WebCam            | 1         | 1.49%   |
| Chicony USB2.0 UVC WebCam                | 1         | 1.49%   |
| Chicony USB2.0 0.3M UVC WebCam           | 1         | 1.49%   |
| Chicony USB 2.0 Camera                   | 1         | 1.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 26.67%  |
| Synaptics                  | 3         | 20%     |
| Shenzhen Goodix Technology | 2         | 13.33%  |
| AuthenTec                  | 2         | 13.33%  |
| Upek                       | 1         | 6.67%   |
| LighTuning Technology      | 1         | 6.67%   |
| Focal-systems.Corp         | 1         | 6.67%   |
| Elan Microelectronics      | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 6.67%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 6.67%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 6.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 6.67%   |
| Synaptics WBDI Device                                                      | 1         | 6.67%   |
| Synaptics  WBDI                                                            | 1         | 6.67%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 6.67%   |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 6.67%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 6.67%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 6.67%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 6.67%   |
| Elan ELAN:ARM-M4                                                           | 1         | 6.67%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 6.67%   |
| AuthenTec AES1600                                                          | 1         | 6.67%   |

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

| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 71        | 68.93%  |
| 1     | 28        | 27.18%  |
| 2     | 3         | 2.91%   |
| 3     | 1         | 0.97%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 15        | 42.86%  |
| Net/wireless          | 6         | 17.14%  |
| Graphics card         | 5         | 14.29%  |
| Multimedia controller | 4         | 11.43%  |
| Camera                | 2         | 5.71%   |
| Storage/raid          | 1         | 2.86%   |
| Dvb card              | 1         | 2.86%   |
| Chipcard              | 1         | 2.86%   |

