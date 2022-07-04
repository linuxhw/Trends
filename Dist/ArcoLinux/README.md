ArcoLinux - Hardware Trends
---------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/ArcoLinux/Desktop/README.md) and [notebooks](/Dist/ArcoLinux/Notebook/README.md).

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

![OS](./All/images/pie_chart/os_name.svg)

![OS](./All/images/line_chart/os_name.svg)

| Name              | Computers | Percent |
|-------------------|-----------|---------|
| ArcoLinux Rolling | 53        | 98.15%  |
| ArcoLinux         | 1         | 1.85%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name      | Computers | Percent |
|-----------|-----------|---------|
| ArcoLinux | 54        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.18.3-arch1-1          | 8         | 14.81%  |
| 5.18.1-arch1-1          | 8         | 14.81%  |
| 5.18.5-arch1-1          | 5         | 9.26%   |
| 5.18.7-arch1-1          | 4         | 7.41%   |
| 5.18.6-arch1-1          | 4         | 7.41%   |
| 5.18.5-zen1-1-zen       | 4         | 7.41%   |
| 5.15.49-1-lts           | 3         | 5.56%   |
| 5.15.48-1-lts           | 3         | 5.56%   |
| 5.15.50-1-lts           | 2         | 3.7%    |
| 5.15.45-1-lts           | 2         | 3.7%    |
| 5.15.44-1-lts           | 2         | 3.7%    |
| 5.18.7-zen1-1-zen       | 1         | 1.85%   |
| 5.18.3-zen1-1-zen       | 1         | 1.85%   |
| 5.18.2-zen1-1-zen       | 1         | 1.85%   |
| 5.18.2-arch1-1          | 1         | 1.85%   |
| 5.18.1-zen1-1-zen       | 1         | 1.85%   |
| 5.17.6-arch1-1          | 1         | 1.85%   |
| 5.17.11-xanmod1-1-x64v2 | 1         | 1.85%   |
| 5.16.10-arch1-1         | 1         | 1.85%   |
| 5.14.14-arch1-1         | 1         | 1.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.18.5  | 9         | 16.67%  |
| 5.18.3  | 9         | 16.67%  |
| 5.18.1  | 9         | 16.67%  |
| 5.18.7  | 5         | 9.26%   |
| 5.18.6  | 4         | 7.41%   |
| 5.15.49 | 3         | 5.56%   |
| 5.15.48 | 3         | 5.56%   |
| 5.18.2  | 2         | 3.7%    |
| 5.15.50 | 2         | 3.7%    |
| 5.15.45 | 2         | 3.7%    |
| 5.15.44 | 2         | 3.7%    |
| 5.17.6  | 1         | 1.85%   |
| 5.17.11 | 1         | 1.85%   |
| 5.16.10 | 1         | 1.85%   |
| 5.14.14 | 1         | 1.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.18    | 38        | 70.37%  |
| 5.15    | 12        | 22.22%  |
| 5.17    | 2         | 3.7%    |
| 5.16    | 1         | 1.85%   |
| 5.14    | 1         | 1.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 54        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| XFCE       | 13        | 24.07%  |
| KDE5       | 11        | 20.37%  |
| X-Cinnamon | 8         | 14.81%  |
| i3         | 4         | 7.41%   |
| GNOME      | 4         | 7.41%   |
| awesome    | 4         | 7.41%   |
| qtile      | 3         | 5.56%   |
| Unknown    | 3         | 5.56%   |
| Unity      | 1         | 1.85%   |
| spectrwm   | 1         | 1.85%   |
| LeftWM     | 1         | 1.85%   |
| Cinnamon   | 1         | 1.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 46        | 85.19%  |
| Tty     | 6         | 11.11%  |
| Unknown | 2         | 3.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 31        | 57.41%  |
| LightDM | 17        | 31.48%  |
| Unknown | 3         | 5.56%   |
| GDM     | 2         | 3.7%    |
| Ly      | 1         | 1.85%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 36        | 66.67%  |
| en_GB | 3         | 5.56%   |
| de_DE | 3         | 5.56%   |
| en_IN | 2         | 3.7%    |
| en_CA | 2         | 3.7%    |
| tr_TR | 1         | 1.85%   |
| sv_SE | 1         | 1.85%   |
| ru_RU | 1         | 1.85%   |
| pl_PL | 1         | 1.85%   |
| it_IT | 1         | 1.85%   |
| es_AR | 1         | 1.85%   |
| en_AU | 1         | 1.85%   |
| de_AT | 1         | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 44        | 81.48%  |
| BIOS | 10        | 18.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 38        | 70.37%  |
| Btrfs   | 14        | 25.93%  |
| Xfs     | 1         | 1.85%   |
| Overlay | 1         | 1.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 44        | 81.48%  |
| MBR     | 8         | 14.81%  |
| Unknown | 2         | 3.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 81.48%  |
| Yes       | 10        | 18.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 57.41%  |
| Yes       | 23        | 42.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| MSI                  | 9         | 16.67%  |
| Lenovo               | 8         | 14.81%  |
| ASUSTek Computer     | 7         | 12.96%  |
| Dell                 | 6         | 11.11%  |
| Gigabyte Technology  | 5         | 9.26%   |
| Hewlett-Packard      | 4         | 7.41%   |
| ASRock               | 2         | 3.7%    |
| Acer                 | 2         | 3.7%    |
| Toshiba              | 1         | 1.85%   |
| System76             | 1         | 1.85%   |
| Schenker             | 1         | 1.85%   |
| Razer                | 1         | 1.85%   |
| PLEXHD               | 1         | 1.85%   |
| Notebook             | 1         | 1.85%   |
| Medion               | 1         | 1.85%   |
| Intel Client Systems | 1         | 1.85%   |
| Casper               | 1         | 1.85%   |
| Biostar              | 1         | 1.85%   |
| Apple                | 1         | 1.85%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Toshiba Satellite Pro S300               | 1         | 1.85%   |
| System76 Oryx Pro                        | 1         | 1.85%   |
| Schenker VISION 15 (SVS15E21)            | 1         | 1.85%   |
| Razer Blade                              | 1         | 1.85%   |
| PLEXHD X79 Turbo                         | 1         | 1.85%   |
| Notebook PA70ES                          | 1         | 1.85%   |
| MSI MS-7C84                              | 1         | 1.85%   |
| MSI MS-7C37                              | 1         | 1.85%   |
| MSI MS-7C35                              | 1         | 1.85%   |
| MSI MS-7B98                              | 1         | 1.85%   |
| MSI MS-7B86                              | 1         | 1.85%   |
| MSI MS-7B84                              | 1         | 1.85%   |
| MSI MS-7A62                              | 1         | 1.85%   |
| MSI MS-7817                              | 1         | 1.85%   |
| MSI GL65 Leopard 10SEK                   | 1         | 1.85%   |
| Medion E7214                             | 1         | 1.85%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS14X04 | 1         | 1.85%   |
| Lenovo ThinkPad T470s 20HGS1D000         | 1         | 1.85%   |
| Lenovo ThinkPad T420 4236EF4             | 1         | 1.85%   |
| Lenovo ThinkPad T420 4180DY4             | 1         | 1.85%   |
| Lenovo ThinkPad E15 Gen 2 20T8000TCK     | 1         | 1.85%   |
| Lenovo Legion Y540-15IRH 81SX            | 1         | 1.85%   |
| Lenovo IdeaPad 330-17ICH 81FL            | 1         | 1.85%   |
| Lenovo B590 20206                        | 1         | 1.85%   |
| Intel Client Systems LAPKC71F            | 1         | 1.85%   |
| HP ZBook Studio G3                       | 1         | 1.85%   |
| HP Laptop 15-da1xxx                      | 1         | 1.85%   |
| HP Laptop 14-dk1xxx                      | 1         | 1.85%   |
| HP EliteBook 840 G3                      | 1         | 1.85%   |
| Gigabyte Z370XP SLI                      | 1         | 1.85%   |
| Gigabyte X570 AORUS PRO WIFI             | 1         | 1.85%   |
| Gigabyte H87-HD3                         | 1         | 1.85%   |
| Gigabyte B550 AORUS ELITE V2             | 1         | 1.85%   |
| Gigabyte AB350N-Gaming WIFI              | 1         | 1.85%   |
| Dell OptiPlex 7010                       | 1         | 1.85%   |
| Dell OptiPlex 3040                       | 1         | 1.85%   |
| Dell OptiPlex 3020                       | 1         | 1.85%   |
| Dell Latitude 5421                       | 1         | 1.85%   |
| Dell Inspiron 546                        | 1         | 1.85%   |
| Dell Inspiron 5459                       | 1         | 1.85%   |
| Casper C600 NOTEBOOK DISCRETE            | 1         | 1.85%   |
| Biostar J3060NH                          | 1         | 1.85%   |
| ASUS TUF Gaming B550M-E WIFI             | 1         | 1.85%   |
| ASUS ROG Strix G733ZX_G733ZX             | 1         | 1.85%   |
| ASUS PRIME Z490-A                        | 1         | 1.85%   |
| ASUS PRIME A320M-K                       | 1         | 1.85%   |
| ASUS M5A78L-M LX PLUS                    | 1         | 1.85%   |
| ASUS GL703VD                             | 1         | 1.85%   |
| ASUS All Series                          | 1         | 1.85%   |
| ASRock Z370 Extreme4                     | 1         | 1.85%   |
| ASRock X299 Taichi CLX                   | 1         | 1.85%   |
| Apple MacBookPro5,4                      | 1         | 1.85%   |
| Acer Aspire ES1-571                      | 1         | 1.85%   |
| Acer Aspire E1-572G                      | 1         | 1.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 5         | 9.26%   |
| Dell OptiPlex                 | 3         | 5.56%   |
| HP Laptop                     | 2         | 3.7%    |
| Dell Inspiron                 | 2         | 3.7%    |
| ASUS PRIME                    | 2         | 3.7%    |
| Acer Aspire                   | 2         | 3.7%    |
| Toshiba Satellite             | 1         | 1.85%   |
| System76 Oryx                 | 1         | 1.85%   |
| Schenker VISION               | 1         | 1.85%   |
| Razer Blade                   | 1         | 1.85%   |
| PLEXHD X79                    | 1         | 1.85%   |
| Notebook PA70ES               | 1         | 1.85%   |
| MSI MS-7C84                   | 1         | 1.85%   |
| MSI MS-7C37                   | 1         | 1.85%   |
| MSI MS-7C35                   | 1         | 1.85%   |
| MSI MS-7B98                   | 1         | 1.85%   |
| MSI MS-7B86                   | 1         | 1.85%   |
| MSI MS-7B84                   | 1         | 1.85%   |
| MSI MS-7A62                   | 1         | 1.85%   |
| MSI MS-7817                   | 1         | 1.85%   |
| MSI GL65                      | 1         | 1.85%   |
| Medion E7214                  | 1         | 1.85%   |
| Lenovo Legion                 | 1         | 1.85%   |
| Lenovo IdeaPad                | 1         | 1.85%   |
| Lenovo B590                   | 1         | 1.85%   |
| Intel Client Systems LAPKC71F | 1         | 1.85%   |
| HP ZBook                      | 1         | 1.85%   |
| HP EliteBook                  | 1         | 1.85%   |
| Gigabyte Z370XP               | 1         | 1.85%   |
| Gigabyte X570                 | 1         | 1.85%   |
| Gigabyte H87-HD3              | 1         | 1.85%   |
| Gigabyte B550                 | 1         | 1.85%   |
| Gigabyte AB350N-Gaming        | 1         | 1.85%   |
| Dell Latitude                 | 1         | 1.85%   |
| Casper C600                   | 1         | 1.85%   |
| Biostar J3060NH               | 1         | 1.85%   |
| ASUS TUF                      | 1         | 1.85%   |
| ASUS ROG                      | 1         | 1.85%   |
| ASUS M5A78L-M                 | 1         | 1.85%   |
| ASUS GL703VD                  | 1         | 1.85%   |
| ASUS All                      | 1         | 1.85%   |
| ASRock Z370                   | 1         | 1.85%   |
| ASRock X299                   | 1         | 1.85%   |
| Apple MacBookPro5             | 1         | 1.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 9         | 16.67%  |
| 2017 | 7         | 12.96%  |
| 2016 | 7         | 12.96%  |
| 2020 | 6         | 11.11%  |
| 2021 | 5         | 9.26%   |
| 2018 | 5         | 9.26%   |
| 2013 | 4         | 7.41%   |
| 2011 | 3         | 5.56%   |
| 2009 | 2         | 3.7%    |
| 2022 | 1         | 1.85%   |
| 2015 | 1         | 1.85%   |
| 2014 | 1         | 1.85%   |
| 2012 | 1         | 1.85%   |
| 2010 | 1         | 1.85%   |
| 2008 | 1         | 1.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 29        | 53.7%   |
| Desktop  | 25        | 46.3%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 54        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 54        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 13        | 24.07%  |
| 32.01-64.0  | 11        | 20.37%  |
| 4.01-8.0    | 10        | 18.52%  |
| 8.01-16.0   | 9         | 16.67%  |
| 3.01-4.0    | 4         | 7.41%   |
| 64.01-256.0 | 4         | 7.41%   |
| 2.01-3.0    | 2         | 3.7%    |
| 24.01-32.0  | 1         | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 15        | 27.78%  |
| 2.01-3.0  | 11        | 20.37%  |
| 1.01-2.0  | 9         | 16.67%  |
| 3.01-4.0  | 7         | 12.96%  |
| 8.01-16.0 | 5         | 9.26%   |
| 0.51-1.0  | 5         | 9.26%   |
| 0.01-0.5  | 2         | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 25        | 46.3%   |
| 2      | 15        | 27.78%  |
| 3      | 7         | 12.96%  |
| 4      | 5         | 9.26%   |
| 7      | 2         | 3.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 81.48%  |
| Yes       | 10        | 18.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 96.3%   |
| No        | 2         | 3.7%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 70.37%  |
| No        | 16        | 29.63%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 66.67%  |
| No        | 18        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 12        | 22.22%  |
| Germany      | 6         | 11.11%  |
| Turkey       | 3         | 5.56%   |
| Canada       | 3         | 5.56%   |
| Belgium      | 3         | 5.56%   |
| Poland       | 2         | 3.7%    |
| Netherlands  | 2         | 3.7%    |
| Italy        | 2         | 3.7%    |
| India        | 2         | 3.7%    |
| France       | 2         | 3.7%    |
| Argentina    | 2         | 3.7%    |
| Switzerland  | 1         | 1.85%   |
| Sweden       | 1         | 1.85%   |
| Sri Lanka    | 1         | 1.85%   |
| Slovakia     | 1         | 1.85%   |
| Saudi Arabia | 1         | 1.85%   |
| Russia       | 1         | 1.85%   |
| Portugal     | 1         | 1.85%   |
| Peru         | 1         | 1.85%   |
| Libya        | 1         | 1.85%   |
| Hong Kong    | 1         | 1.85%   |
| Estonia      | 1         | 1.85%   |
| Cyprus       | 1         | 1.85%   |
| Barbados     | 1         | 1.85%   |
| Austria      | 1         | 1.85%   |
| Australia    | 1         | 1.85%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City            | Computers | Percent |
|-----------------|-----------|---------|
| Lier            | 3         | 5.56%   |
| Montevrain      | 2         | 3.7%    |
| Leipzig         | 2         | 3.7%    |
| Zurich          | 1         | 1.85%   |
| Wroclaw         | 1         | 1.85%   |
| Weinbach        | 1         | 1.85%   |
| Vienna          | 1         | 1.85%   |
| Türi           | 1         | 1.85%   |
| Trenčín       | 1         | 1.85%   |
| Torres Vedras   | 1         | 1.85%   |
| South Jordan    | 1         | 1.85%   |
| Seattle         | 1         | 1.85%   |
| Rosenheim       | 1         | 1.85%   |
| Rosario         | 1         | 1.85%   |
| Riyadh          | 1         | 1.85%   |
| Perth           | 1         | 1.85%   |
| Omsk            | 1         | 1.85%   |
| Norwalk         | 1         | 1.85%   |
| Noida           | 1         | 1.85%   |
| Nieuw-Vennep    | 1         | 1.85%   |
| Nicosia         | 1         | 1.85%   |
| Mysłowice      | 1         | 1.85%   |
| Myrtle Beach    | 1         | 1.85%   |
| Mumbai          | 1         | 1.85%   |
| Mattoon         | 1         | 1.85%   |
| Mar del Plata   | 1         | 1.85%   |
| Maharagama      | 1         | 1.85%   |
| Louisville      | 1         | 1.85%   |
| London          | 1         | 1.85%   |
| Lima            | 1         | 1.85%   |
| Leer            | 1         | 1.85%   |
| Las Vegas       | 1         | 1.85%   |
| Izmir           | 1         | 1.85%   |
| Istanbul        | 1         | 1.85%   |
| Houston         | 1         | 1.85%   |
| Härnösand     | 1         | 1.85%   |
| Greater Sudbury | 1         | 1.85%   |
| Edmonton        | 1         | 1.85%   |
| Düsseldorf     | 1         | 1.85%   |
| Cypress         | 1         | 1.85%   |
| Crothersville   | 1         | 1.85%   |
| Chicago         | 1         | 1.85%   |
| Central         | 1         | 1.85%   |
| Byron Center    | 1         | 1.85%   |
| Bursa           | 1         | 1.85%   |
| Bridgetown      | 1         | 1.85%   |
| Bologna         | 1         | 1.85%   |
| Benghazi        | 1         | 1.85%   |
| Asti            | 1         | 1.85%   |
| Amsterdam       | 1         | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 30     | 22.22%  |
| Samsung Electronics | 16        | 23     | 17.78%  |
| Seagate             | 11        | 14     | 12.22%  |
| Toshiba             | 6         | 6      | 6.67%   |
| Crucial             | 5         | 6      | 5.56%   |
| Gigabyte Technology | 4         | 4      | 4.44%   |
| Hitachi             | 3         | 3      | 3.33%   |
| Unknown             | 2         | 2      | 2.22%   |
| SanDisk             | 2         | 2      | 2.22%   |
| PNY                 | 2         | 2      | 2.22%   |
| KIOXIA              | 2         | 2      | 2.22%   |
| Intel               | 2         | 2      | 2.22%   |
| XrayDisk            | 1         | 1      | 1.11%   |
| UMIS                | 1         | 1      | 1.11%   |
| Transcend           | 1         | 1      | 1.11%   |
| Silicon Motion      | 1         | 1      | 1.11%   |
| Phison              | 1         | 1      | 1.11%   |
| Patriot             | 1         | 1      | 1.11%   |
| Micron Technology   | 1         | 1      | 1.11%   |
| LITEONIT            | 1         | 1      | 1.11%   |
| LaCie               | 1         | 1      | 1.11%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.11%   |
| Kingston            | 1         | 1      | 1.11%   |
| HGST                | 1         | 1      | 1.11%   |
| Corsair             | 1         | 1      | 1.11%   |
| ASMT                | 1         | 1      | 1.11%   |
| A-DATA Technology   | 1         | 1      | 1.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| WDC WD10EADS-00L5B1 1TB              | 2         | 1.87%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.87%   |
| Samsung SSD 980 PRO 1TB              | 2         | 1.87%   |
| Samsung SSD 970 EVO Plus 500GB       | 2         | 1.87%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 1.87%   |
| Samsung SSD 860 EVO 250GB            | 2         | 1.87%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.87%   |
| Samsung SSD 850 EVO 120GB            | 2         | 1.87%   |
| XrayDisk SSD 1TB                     | 1         | 0.93%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.93%   |
| WDC WDS500G1X0E-00AFY0 500GB         | 1         | 0.93%   |
| WDC WDS250G2B0A-00SM50 250GB SSD     | 1         | 0.93%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.93%   |
| WDC WDS240G1G0B-00RC30 240GB SSD     | 1         | 0.93%   |
| WDC WDS200T2B0A-00SM50 2TB SSD       | 1         | 0.93%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.93%   |
| WDC WDBNCE5000PNC 500GB SSD          | 1         | 0.93%   |
| WDC WD6400AAKS-65Z7B0 640GB          | 1         | 0.93%   |
| WDC WD5002ABYS-01B1B0 500GB          | 1         | 0.93%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 1         | 0.93%   |
| WDC WD5000AAKX-001CA0 500GB          | 1         | 0.93%   |
| WDC WD5000AAKS-75V0A0 500GB          | 1         | 0.93%   |
| WDC WD3200BPVT-75ZEST0 320GB         | 1         | 0.93%   |
| WDC WD20SPZX-22UA7T0 2TB             | 1         | 0.93%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 0.93%   |
| WDC WD2001FASS-00W2B0 2TB            | 1         | 0.93%   |
| WDC WD10SPZX-60Z10T1 1TB             | 1         | 0.93%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1         | 0.93%   |
| WDC WD10EZEX-00BN5A0 1TB             | 1         | 0.93%   |
| WDC WD10EUCX-63YZ1Y0 1TB             | 1         | 0.93%   |
| WDC WD10EFRX-68JCSN0 1TB             | 1         | 0.93%   |
| WDC WD1001FALS-00J7B0 1TB            | 1         | 0.93%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB | 1         | 0.93%   |
| WDC PC SN530 SDBPMPZ-512G-1001 512GB | 1         | 0.93%   |
| Unknown SD128  128GB                 | 1         | 0.93%   |
| Unknown APPSD  134GB                 | 1         | 0.93%   |
| UMIS RPFTJ128PDD2EWX 128GB           | 1         | 0.93%   |
| Transcend TS480GSSD220S 480GB        | 1         | 0.93%   |
| Toshiba THNSNJ256GCSU 256GB SSD      | 1         | 0.93%   |
| Toshiba THNSF5256GPU7 256GB          | 1         | 0.93%   |
| Toshiba MQ01ABF050M 500GB            | 1         | 0.93%   |
| Toshiba MQ01ABF050 500GB             | 1         | 0.93%   |
| Toshiba HDWF180 8TB                  | 1         | 0.93%   |
| Toshiba DT01ACA050 500GB             | 1         | 0.93%   |
| Silicon Motion NVME SSD 256GB        | 1         | 0.93%   |
| Seagate ST9500325AS 500GB            | 1         | 0.93%   |
| Seagate ST4000DM004-2CV104 4TB       | 1         | 0.93%   |
| Seagate ST3000DM008-2DM166 3TB       | 1         | 0.93%   |
| Seagate ST2000DX002-2DV164 2TB       | 1         | 0.93%   |
| Seagate ST2000DM001-9YN164 2TB       | 1         | 0.93%   |
| Seagate ST2000DM001-1ER164 2TB       | 1         | 0.93%   |
| Seagate ST2000DM001-1CH164 2TB       | 1         | 0.93%   |
| Seagate ST1000LX015-1U7172 1TB       | 1         | 0.93%   |
| Seagate ST1000LM048-2E7172 1TB       | 1         | 0.93%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 0.93%   |
| Seagate ST1000DM003-1ER162 1TB       | 1         | 0.93%   |
| Seagate Expansion 1TB                | 1         | 0.93%   |
| SanDisk X400 M.2 2280 256GB SSD      | 1         | 0.93%   |
| SanDisk SSD PLUS 240GB               | 1         | 0.93%   |
| Samsung SSD 980 500GB                | 1         | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 12        | 20     | 37.5%   |
| Seagate | 11        | 14     | 34.38%  |
| Toshiba | 4         | 4      | 12.5%   |
| Hitachi | 3         | 3      | 9.38%   |
| HGST    | 1         | 1      | 3.13%   |
| ASMT    | 1         | 1      | 3.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 33.33%  |
| WDC                 | 7         | 7      | 21.21%  |
| SanDisk             | 2         | 2      | 6.06%   |
| PNY                 | 2         | 2      | 6.06%   |
| Crucial             | 2         | 2      | 6.06%   |
| XrayDisk            | 1         | 1      | 3.03%   |
| Transcend           | 1         | 1      | 3.03%   |
| Toshiba             | 1         | 1      | 3.03%   |
| Patriot             | 1         | 1      | 3.03%   |
| LITEONIT            | 1         | 1      | 3.03%   |
| KIOXIA-EXCERIA      | 1         | 1      | 3.03%   |
| Kingston            | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |
| A-DATA Technology   | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 30        | 34     | 35.29%  |
| HDD     | 27        | 43     | 31.76%  |
| NVMe    | 25        | 31     | 29.41%  |
| MMC     | 2         | 2      | 2.35%   |
| Unknown | 1         | 1      | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 42        | 75     | 58.33%  |
| NVMe | 25        | 31     | 34.72%  |
| SAS  | 3         | 3      | 4.17%   |
| MMC  | 2         | 2      | 2.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 30        | 42     | 51.72%  |
| 0.51-1.0   | 18        | 23     | 31.03%  |
| 1.01-2.0   | 7         | 9      | 12.07%  |
| 3.01-4.0   | 1         | 1      | 1.72%   |
| 2.01-3.0   | 1         | 1      | 1.72%   |
| 4.01-10.0  | 1         | 1      | 1.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 13        | 24.07%  |
| 101-250        | 12        | 22.22%  |
| 251-500        | 8         | 14.81%  |
| 1001-2000      | 6         | 11.11%  |
| 501-1000       | 6         | 11.11%  |
| 2001-3000      | 3         | 5.56%   |
| Unknown        | 3         | 5.56%   |
| 1-20           | 2         | 3.7%    |
| 51-100         | 1         | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 10        | 18.52%  |
| 21-50          | 9         | 16.67%  |
| 1-20           | 8         | 14.81%  |
| 251-500        | 7         | 12.96%  |
| 501-1000       | 6         | 11.11%  |
| 1001-2000      | 5         | 9.26%   |
| More than 3000 | 3         | 5.56%   |
| 51-100         | 3         | 5.56%   |
| Unknown        | 3         | 5.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD6400AAKS-65Z7B0 640GB              | 1         | 1      | 7.14%   |
| WDC WD5000AAKX-00ERMA0 500GB             | 1         | 1      | 7.14%   |
| WDC WD5000AAKX-001CA0 500GB              | 1         | 1      | 7.14%   |
| WDC WD2001FASS-00W2B0 2TB                | 1         | 1      | 7.14%   |
| WDC WD10EADS-00L5B1 1TB                  | 1         | 1      | 7.14%   |
| Toshiba MQ01ABF050 500GB                 | 1         | 1      | 7.14%   |
| Toshiba DT01ACA050 500GB                 | 1         | 1      | 7.14%   |
| Seagate ST2000DX002-2DV164 2TB           | 1         | 1      | 7.14%   |
| Seagate ST2000DM001-1ER164 2TB           | 1         | 1      | 7.14%   |
| Seagate ST1000LX015-1U7172 1TB           | 1         | 1      | 7.14%   |
| Samsung Electronics SSD 970 EVO Plus 1TB | 1         | 1      | 7.14%   |
| Patriot P210 256GB SSD                   | 1         | 1      | 7.14%   |
| Hitachi HTS543225L9SA00 250GB            | 1         | 1      | 7.14%   |
| HGST HTS545050A7E380 500GB               | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 5      | 30.77%  |
| Seagate             | 3         | 3      | 23.08%  |
| Toshiba             | 2         | 2      | 15.38%  |
| Samsung Electronics | 1         | 1      | 7.69%   |
| Patriot             | 1         | 1      | 7.69%   |
| Hitachi             | 1         | 1      | 7.69%   |
| HGST                | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 5      | 36.36%  |
| Seagate | 3         | 3      | 27.27%  |
| Toshiba | 2         | 2      | 18.18%  |
| Hitachi | 1         | 1      | 9.09%   |
| HGST    | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 12     | 83.33%  |
| NVMe | 1         | 1      | 8.33%   |
| SSD  | 1         | 1      | 8.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)

![Failed Drives](./All/images/line_chart/drive_failed.svg)

| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)

![Failed Drive Vendor](./All/images/line_chart/drive_failed_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)

![Drive Status](./All/images/line_chart/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 47        | 86     | 70.15%  |
| Malfunc  | 12        | 14     | 17.91%  |
| Detected | 7         | 10     | 10.45%  |
| Failed   | 1         | 1      | 1.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 35        | 43.75%  |
| AMD                          | 13        | 16.25%  |
| Samsung Electronics          | 9         | 11.25%  |
| Phison Electronics           | 5         | 6.25%   |
| SanDisk                      | 3         | 3.75%   |
| Micron/Crucial Technology    | 3         | 3.75%   |
| ASMedia Technology           | 3         | 3.75%   |
| Toshiba America Info Systems | 2         | 2.5%    |
| Micron Technology            | 2         | 2.5%    |
| Union Memory (Shenzhen)      | 1         | 1.25%   |
| Silicon Motion               | 1         | 1.25%   |
| Nvidia                       | 1         | 1.25%   |
| KIOXIA                       | 1         | 1.25%   |
| Broadcom / LSI               | 1         | 1.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 9.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 6.82%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 5         | 5.68%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 4.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 3.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 3.41%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 3.41%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 3.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 2.27%   |
| Micron Non-Volatile memory controller                                            | 2         | 2.27%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 2.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 2.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 2.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 2         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 2.27%   |
| AMD FCH SATA Controller D                                                        | 2         | 2.27%   |
| AMD 500 Series Chipset SATA Controller                                           | 2         | 2.27%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 1.14%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 1.14%   |
| Toshiba America Info Systems NVMe Controller                                     | 1         | 1.14%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 1.14%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 1.14%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 1.14%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.14%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 1.14%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 1.14%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.14%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 1.14%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 1.14%   |
| Micron/Crucial NVMe Controller                                                   | 1         | 1.14%   |
| Micron/Crucial Non-Volatile memory controller                                    | 1         | 1.14%   |
| KIOXIA Non-Volatile memory controller                                            | 1         | 1.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.14%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 1.14%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 1.14%   |
| Intel Comet Lake PCH-H RAID                                                      | 1         | 1.14%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.14%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1         | 1.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 1.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 1.14%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.14%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 1.14%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                   | 1         | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.14%   |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 1.14%   |
| AMD 300 Series Chipset SATA Controller                                           | 1         | 1.14%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 42        | 55.26%  |
| NVMe | 25        | 32.89%  |
| RAID | 7         | 9.21%   |
| IDE  | 2         | 2.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 40        | 74.07%  |
| AMD    | 14        | 25.93%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 5.56%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 3.7%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 3.7%    |
| AMD Ryzen 9 5900X 12-Core Processor           | 2         | 3.7%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 2         | 3.7%    |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz           | 1         | 1.85%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz           | 1         | 1.85%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1         | 1.85%   |
| Intel Core i9-10900X CPU @ 3.70GHz            | 1         | 1.85%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 1.85%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1         | 1.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.85%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.85%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.85%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 1.85%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.85%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 1         | 1.85%   |
| Intel Core i7-4770S CPU @ 3.10GHz             | 1         | 1.85%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1         | 1.85%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.85%   |
| Intel Core i7-10700K CPU @ 3.80GHz            | 1         | 1.85%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 1         | 1.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.85%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 1.85%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 1.85%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.85%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 1.85%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.85%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 1         | 1.85%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 1         | 1.85%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 1         | 1.85%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 1.85%   |
| Intel Celeron CPU J3060 @ 1.60GHz             | 1         | 1.85%   |
| Intel Celeron CPU 1000M @ 1.80GHz             | 1         | 1.85%   |
| Intel 12th Gen Core i9-12900H                 | 1         | 1.85%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 1         | 1.85%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 1.85%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.85%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 1.85%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 1         | 1.85%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 1.85%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 1         | 1.85%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 1         | 1.85%   |
| AMD Ryzen 5 3600 6-Core Processor             | 1         | 1.85%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 1         | 1.85%   |
| AMD Phenom 9750 Quad-Core Processor           | 1         | 1.85%   |
| AMD FX-6300 Six-Core Processor                | 1         | 1.85%   |
| AMD A6-9500E RADEON R5, 6 COMPUTE CORES 2C+4G | 1         | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 17        | 31.48%  |
| Intel Core i5    | 7         | 12.96%  |
| Other            | 4         | 7.41%   |
| Intel Core i3    | 4         | 7.41%   |
| AMD Ryzen 9      | 3         | 5.56%   |
| AMD Ryzen 7      | 3         | 5.56%   |
| AMD Ryzen 3      | 3         | 5.56%   |
| Intel Xeon       | 2         | 3.7%    |
| Intel Core 2 Duo | 2         | 3.7%    |
| Intel Celeron    | 2         | 3.7%    |
| AMD Ryzen 5      | 2         | 3.7%    |
| Intel Pentium    | 1         | 1.85%   |
| Intel Core i9    | 1         | 1.85%   |
| AMD Phenom       | 1         | 1.85%   |
| AMD FX           | 1         | 1.85%   |
| AMD A6           | 1         | 1.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 17        | 31.48%  |
| 4      | 12        | 22.22%  |
| 6      | 11        | 20.37%  |
| 8      | 7         | 12.96%  |
| 12     | 3         | 5.56%   |
| 14     | 1         | 1.85%   |
| 10     | 1         | 1.85%   |
| 3      | 1         | 1.85%   |
| 1      | 1         | 1.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 54        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 44        | 81.48%  |
| 1      | 10        | 18.52%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 54        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x906ea    | 7         | 12.96%  |
| 0x406e3    | 3         | 5.56%   |
| 0x306c3    | 3         | 5.56%   |
| Unknown    | 3         | 5.56%   |
| 0x906e9    | 2         | 3.7%    |
| 0x806e9    | 2         | 3.7%    |
| 0x806d1    | 2         | 3.7%    |
| 0x506e3    | 2         | 3.7%    |
| 0x306a9    | 2         | 3.7%    |
| 0x206a7    | 2         | 3.7%    |
| 0x08701021 | 2         | 3.7%    |
| 0x08101016 | 2         | 3.7%    |
| 0xa0655    | 1         | 1.85%   |
| 0xa0652    | 1         | 1.85%   |
| 0x906a3    | 1         | 1.85%   |
| 0x806ec    | 1         | 1.85%   |
| 0x806c1    | 1         | 1.85%   |
| 0x50657    | 1         | 1.85%   |
| 0x406c4    | 1         | 1.85%   |
| 0x40651    | 1         | 1.85%   |
| 0x306e4    | 1         | 1.85%   |
| 0x306d4    | 1         | 1.85%   |
| 0x20652    | 1         | 1.85%   |
| 0x1067a    | 1         | 1.85%   |
| 0x10676    | 1         | 1.85%   |
| 0x0a201205 | 1         | 1.85%   |
| 0x0a201016 | 1         | 1.85%   |
| 0x0a201009 | 1         | 1.85%   |
| 0x08701013 | 1         | 1.85%   |
| 0x08600103 | 1         | 1.85%   |
| 0x08108109 | 1         | 1.85%   |
| 0x06006118 | 1         | 1.85%   |
| 0x0600081c | 1         | 1.85%   |
| 0x01000095 | 1         | 1.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 13        | 24.07%  |
| Skylake          | 6         | 11.11%  |
| Haswell          | 5         | 9.26%   |
| Zen 3            | 4         | 7.41%   |
| Zen 2            | 4         | 7.41%   |
| IvyBridge        | 3         | 5.56%   |
| Zen              | 2         | 3.7%    |
| SandyBridge      | 2         | 3.7%    |
| Penryn           | 2         | 3.7%    |
| Icelake          | 2         | 3.7%    |
| CometLake        | 2         | 3.7%    |
| Zen+             | 1         | 1.85%   |
| Westmere         | 1         | 1.85%   |
| TigerLake        | 1         | 1.85%   |
| Silvermont       | 1         | 1.85%   |
| Piledriver       | 1         | 1.85%   |
| K10              | 1         | 1.85%   |
| Excavator        | 1         | 1.85%   |
| Broadwell        | 1         | 1.85%   |
| Alderlake Hybrid | 1         | 1.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 27        | 42.19%  |
| Nvidia           | 22        | 34.38%  |
| AMD              | 14        | 21.88%  |
| ATI Technologies | 1         | 1.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 4.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 4.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 4.69%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2         | 3.13%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 3.13%   |
| Intel HD Graphics 620                                                                    | 2         | 3.13%   |
| Intel HD Graphics 530                                                                    | 2         | 3.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.13%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 3.13%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.56%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 1.56%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1         | 1.56%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.56%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.56%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                             | 1         | 1.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1.56%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 1.56%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 1.56%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1         | 1.56%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1.56%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 1.56%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 1.56%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 1.56%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1         | 1.56%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                                           | 1         | 1.56%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.56%   |
| Intel HD Graphics 630                                                                    | 1         | 1.56%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.56%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.56%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 1.56%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 1.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 1.56%   |
| ATI Technologies Wani [Radeon R5/R6/R7 Graphics]                                         | 1         | 1.56%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 1.56%   |
| AMD RS780 [Radeon HD 3200]                                                               | 1         | 1.56%   |
| AMD Renoir                                                                               | 1         | 1.56%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.56%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 1         | 1.56%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                                  | 1         | 1.56%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 1         | 1.56%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 1         | 1.56%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1         | 1.56%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1         | 1.56%   |
| AMD Cezanne                                                                              | 1         | 1.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 29.63%  |
| 1 x Nvidia     | 14        | 25.93%  |
| 1 x AMD        | 13        | 24.07%  |
| Intel + Nvidia | 8         | 14.81%  |
| Intel + AMD    | 2         | 3.7%    |
| 2 x Intel      | 1         | 1.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 35        | 64.81%  |
| Proprietary | 18        | 33.33%  |
| Unknown     | 1         | 1.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 44.44%  |
| 3.01-4.0   | 6         | 11.11%  |
| 1.01-2.0   | 6         | 11.11%  |
| 0.01-0.5   | 6         | 11.11%  |
| 7.01-8.0   | 4         | 7.41%   |
| 5.01-6.0   | 4         | 7.41%   |
| 8.01-16.0  | 4         | 7.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| LG Display           | 9         | 14.75%  |
| Goldstar             | 8         | 13.11%  |
| AU Optronics         | 8         | 13.11%  |
| Samsung Electronics  | 6         | 9.84%   |
| BOE                  | 6         | 9.84%   |
| Dell                 | 5         | 8.2%    |
| Philips              | 3         | 4.92%   |
| Chimei Innolux       | 2         | 3.28%   |
| BenQ                 | 2         | 3.28%   |
| Ancor Communications | 2         | 3.28%   |
| ViewSonic            | 1         | 1.64%   |
| Unknown              | 1         | 1.64%   |
| Sceptre Tech         | 1         | 1.64%   |
| PRO                  | 1         | 1.64%   |
| MSI                  | 1         | 1.64%   |
| JRY                  | 1         | 1.64%   |
| Gigabyte Technology  | 1         | 1.64%   |
| ASUSTek Computer     | 1         | 1.64%   |
| Apple                | 1         | 1.64%   |
| Acer                 | 1         | 1.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| ViewSonic VX2363 Series VSC6B2F 1920x1080 509x286mm 23.0-inch           | 1         | 1.61%   |
| Unknown LCD Monitor MEC MD20491 1920x1080                               | 1         | 1.61%   |
| Sceptre Tech F27 SPT0ABF 1920x1080 409x230mm 18.5-inch                  | 1         | 1.61%   |
| Samsung Electronics S27R35x SAM1053 1920x1080 598x336mm 27.0-inch       | 1         | 1.61%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch       | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SAM0D3A 3840x2160 1872x1053mm 84.6-inch | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 1210x680mm 54.6-inch  | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch  | 1         | 1.61%   |
| Samsung Electronics C49RG9x SAM0F99 3840x1080 1193x336mm 48.8-inch      | 1         | 1.61%   |
| PRO TYPE-C PRO40F3 1920x1080 344x193mm 15.5-inch                        | 1         | 1.61%   |
| Philips PHL 252B9 PHL092C 1920x1200 540x340mm 25.1-inch                 | 1         | 1.61%   |
| Philips PHL 243V5 PHLC002 1920x1080 521x293mm 23.5-inch                 | 1         | 1.61%   |
| Philips FTV PHL2478 1360x768 521x293mm 23.5-inch                        | 1         | 1.61%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                          | 1         | 1.61%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch             | 1         | 1.61%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch            | 1         | 1.61%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch            | 1         | 1.61%   |
| LG Display LCD Monitor LGD05B9 1920x1080 382x215mm 17.3-inch            | 1         | 1.61%   |
| LG Display LCD Monitor LGD0502 2560x1440 310x174mm 14.0-inch            | 1         | 1.61%   |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch            | 1         | 1.61%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch            | 1         | 1.61%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch             | 1         | 1.61%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch             | 1         | 1.61%   |
| JRY HDMI JRY2380 1920x1080 527x296mm 23.8-inch                          | 1         | 1.61%   |
| Goldstar ULTRAWIDE GSM76FA 2560x1080 531x298mm 24.0-inch                | 1         | 1.61%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch                | 1         | 1.61%   |
| Goldstar QHD GSM772A 2560x1440 697x392mm 31.5-inch                      | 1         | 1.61%   |
| Goldstar LG HDR QHD GSM5B95 2560x1440 700x390mm 31.5-inch               | 1         | 1.61%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch               | 1         | 1.61%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                  | 1         | 1.61%   |
| Goldstar E1940 GSM4BD6 1360x768 406x229mm 18.4-inch                     | 1         | 1.61%   |
| Goldstar 23EA53 GSM59A9 1920x1080 510x290mm 23.1-inch                   | 1         | 1.61%   |
| Goldstar 22EN43 GSM59D8 1920x1080 480x270mm 21.7-inch                   | 1         | 1.61%   |
| Gigabyte Technology AORUS FV43U GBT4300 3840x2160 697x392mm 31.5-inch   | 1         | 1.61%   |
| Dell SX2210 DELA046 1920x1080 477x268mm 21.5-inch                       | 1         | 1.61%   |
| Dell S2817Q DEL40EE 3840x2160 620x340mm 27.8-inch                       | 1         | 1.61%   |
| Dell P2720DC DELD0FC 2560x1440 600x340mm 27.2-inch                      | 1         | 1.61%   |
| Dell P2415Q DELA0BE 3840x2160 530x300mm 24.0-inch                       | 1         | 1.61%   |
| Dell 2407WFP DELA017 1920x1200 520x330mm 24.2-inch                      | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch         | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN1400 1920x1080 309x173mm 13.9-inch        | 1         | 1.61%   |
| BOE LCD Monitor BOE0A69 2560x1440 381x214mm 17.2-inch                   | 1         | 1.61%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 1         | 1.61%   |
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                   | 1         | 1.61%   |
| BOE LCD Monitor BOE08F5 1920x1080 344x194mm 15.5-inch                   | 1         | 1.61%   |
| BOE LCD Monitor BOE07B6 1920x1080 382x215mm 17.3-inch                   | 1         | 1.61%   |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                    | 1         | 1.61%   |
| BenQ GW2780 BNQ78E6 1920x1080 598x336mm 27.0-inch                       | 1         | 1.61%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                      | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch          | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch          | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO319D 1920x1080 380x210mm 17.1-inch          | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch           | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch          | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch           | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch           | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO103D 1920x1080 309x173mm 13.9-inch          | 1         | 1.61%   |
| ASUSTek Computer VG32V AUS32A3 2560x1440 697x393mm 31.5-inch            | 1         | 1.61%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                  | 1         | 1.61%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch   | 1         | 1.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 29        | 50.88%  |
| 2560x1440 (QHD)   | 8         | 14.04%  |
| 1366x768 (WXGA)   | 7         | 12.28%  |
| 3840x2160 (4K)    | 5         | 8.77%   |
| 1920x1200 (WUXGA) | 2         | 3.51%   |
| 1360x768          | 2         | 3.51%   |
| 3840x1080         | 1         | 1.75%   |
| 2560x1080         | 1         | 1.75%   |
| 1600x900 (HD+)    | 1         | 1.75%   |
| 1440x900 (WXGA+)  | 1         | 1.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 13        | 21.67%  |
| 27      | 7         | 11.67%  |
| 23      | 6         | 10%     |
| 17      | 6         | 10%     |
| 21      | 4         | 6.67%   |
| 14      | 4         | 6.67%   |
| 13      | 4         | 6.67%   |
| 31      | 3         | 5%      |
| 24      | 3         | 5%      |
| 48      | 2         | 3.33%   |
| 84      | 1         | 1.67%   |
| 54      | 1         | 1.67%   |
| 42      | 1         | 1.67%   |
| 34      | 1         | 1.67%   |
| 32      | 1         | 1.67%   |
| 25      | 1         | 1.67%   |
| 18      | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 35.59%  |
| 501-600     | 15        | 25.42%  |
| 351-400     | 6         | 10.17%  |
| 401-500     | 5         | 8.47%   |
| 601-700     | 4         | 6.78%   |
| 1001-1500   | 3         | 5.08%   |
| 701-800     | 2         | 3.39%   |
| 1501-2000   | 1         | 1.69%   |
| 901-1000    | 1         | 1.69%   |
| Unknown     | 1         | 1.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 46        | 88.46%  |
| 16/10   | 3         | 5.77%   |
| 32/9    | 1         | 1.92%   |
| 21/9    | 1         | 1.92%   |
| Unknown | 1         | 1.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 13        | 21.67%  |
| 201-250        | 11        | 18.33%  |
| 81-90          | 8         | 13.33%  |
| 301-350        | 7         | 11.67%  |
| 121-130        | 6         | 10%     |
| 351-500        | 5         | 8.33%   |
| More than 1000 | 3         | 5%      |
| 251-300        | 2         | 3.33%   |
| 501-1000       | 2         | 3.33%   |
| 151-200        | 1         | 1.67%   |
| 141-150        | 1         | 1.67%   |
| Unknown        | 1         | 1.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 18        | 31.03%  |
| 121-160 | 17        | 29.31%  |
| 101-120 | 16        | 27.59%  |
| 161-240 | 4         | 6.9%    |
| 1-50    | 2         | 3.45%   |
| Unknown | 1         | 1.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 40        | 74.07%  |
| 2     | 9         | 16.67%  |
| 0     | 3         | 5.56%   |
| 3     | 2         | 3.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 43.21%  |
| Realtek Semiconductor | 33        | 40.74%  |
| Qualcomm Atheros      | 4         | 4.94%   |
| Broadcom              | 3         | 3.7%    |
| Ralink Technology     | 2         | 2.47%   |
| TP-Link               | 1         | 1.23%   |
| Sierra Wireless       | 1         | 1.23%   |
| Samsung Electronics   | 1         | 1.23%   |
| Nvidia                | 1         | 1.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 26.32%  |
| Intel Wi-Fi 6 AX200                                               | 8         | 8.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 5.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 5.26%   |
| Intel Wireless 8260                                               | 3         | 3.16%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 3.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.11%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 2.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.11%   |
| Intel Wireless 8265 / 8275                                        | 2         | 2.11%   |
| Intel Wireless 3165                                               | 2         | 2.11%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 2.11%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 2.11%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 1.05%   |
| Sierra Wireless EM7455                                            | 1         | 1.05%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.05%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.05%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.05%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.05%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.05%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.05%   |
| Intel Wireless 3160                                               | 1         | 1.05%   |
| Intel WiFi Link 5100                                              | 1         | 1.05%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.05%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.05%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.05%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.05%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 1         | 1.05%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.05%   |
| Intel 82567V Gigabit Network Connection                           | 1         | 1.05%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.05%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 1         | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.05%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 29        | 72.5%   |
| Realtek Semiconductor | 3         | 7.5%    |
| Ralink Technology     | 2         | 5%      |
| Qualcomm Atheros      | 2         | 5%      |
| Broadcom              | 2         | 5%      |
| TP-Link               | 1         | 2.5%    |
| Sierra Wireless       | 1         | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 8         | 20%     |
| Intel Cannon Lake PCH CNVi WiFi                            | 5         | 12.5%   |
| Intel Wireless 8260                                        | 3         | 7.5%    |
| Ralink MT7601U Wireless Adapter                            | 2         | 5%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 2         | 5%      |
| Intel Wireless 8265 / 8275                                 | 2         | 5%      |
| Intel Wireless 3165                                        | 2         | 5%      |
| Intel Tiger Lake PCH CNVi WiFi                             | 2         | 5%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 2         | 5%      |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano] | 1         | 2.5%    |
| Sierra Wireless EM7455                                     | 1         | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.5%    |
| Realtek RTL8723DE Wireless Network Adapter                 | 1         | 2.5%    |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 2.5%    |
| Intel Wireless 3160                                        | 1         | 2.5%    |
| Intel WiFi Link 5100                                       | 1         | 2.5%    |
| Intel Wi-Fi 6 AX201                                        | 1         | 2.5%    |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 2.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                           | 1         | 2.5%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller     | 1         | 2.5%    |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 32        | 59.26%  |
| Intel                 | 17        | 31.48%  |
| Qualcomm Atheros      | 2         | 3.7%    |
| Samsung Electronics   | 1         | 1.85%   |
| Nvidia                | 1         | 1.85%   |
| Broadcom              | 1         | 1.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 45.45%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 9.09%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 5.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 3.64%   |
| Intel Ethernet Controller I225-V                                  | 2         | 3.64%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.82%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.82%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.82%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.82%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.82%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.82%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.82%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.82%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.82%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.82%   |
| Intel 82567V Gigabit Network Connection                           | 1         | 1.82%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 52        | 57.78%  |
| WiFi     | 38        | 42.22%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 53.7%   |
| Ethernet | 25        | 46.3%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 35        | 64.81%  |
| 1     | 18        | 33.33%  |
| 3     | 1         | 1.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 41        | 75.93%  |
| Yes  | 13        | 24.07%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 24        | 66.67%  |
| Cambridge Silicon Radio | 4         | 11.11%  |
| Lite-On Technology      | 2         | 5.56%   |
| Broadcom                | 2         | 5.56%   |
| Realtek Semiconductor   | 1         | 2.78%   |
| Foxconn / Hon Hai       | 1         | 2.78%   |
| ASUSTek Computer        | 1         | 2.78%   |
| Apple                   | 1         | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 19.44%  |
| Intel AX200 Bluetooth                               | 7         | 19.44%  |
| Intel Bluetooth Device                              | 5         | 13.89%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 13.89%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 11.11%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.78%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 2.78%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.78%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.78%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.78%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2.78%   |
| ASUS ASUS USB-BT500                                 | 1         | 2.78%   |
| Apple Bluetooth Host Controller                     | 1         | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 39        | 44.32%  |
| Nvidia                     | 19        | 21.59%  |
| AMD                        | 17        | 19.32%  |
| RODE Microphones           | 2         | 2.27%   |
| Kingston Technology        | 2         | 2.27%   |
| Sony                       | 1         | 1.14%   |
| SM950 Microphone           | 1         | 1.14%   |
| Samson Technologies        | 1         | 1.14%   |
| Razer USA                  | 1         | 1.14%   |
| PreSonus Audio Electronics | 1         | 1.14%   |
| Plantronics                | 1         | 1.14%   |
| Logitech                   | 1         | 1.14%   |
| Corsair                    | 1         | 1.14%   |
| ATI Technologies           | 1         | 1.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 6.06%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 6.06%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 5.05%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 5.05%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 5.05%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 4.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 3.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 3.03%   |
| RODE Microphones RODE NT-USB                                                                      | 2         | 2.02%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 2.02%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 2.02%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 2.02%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 2.02%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 2.02%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 2.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 2.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 2.02%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 2.02%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 2.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 2.02%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 2.02%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 2.02%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 1.01%   |
| SM950 Microphone SM950 Microphone                                                                 | 1         | 1.01%   |
| Samson Technologies Q2U handheld mic with XLR                                                     | 1         | 1.01%   |
| Razer USA RZ19-0229 Gaming Microphone                                                             | 1         | 1.01%   |
| PreSonus Audio Electronics AudioBox 22 VSL                                                        | 1         | 1.01%   |
| Plantronics Blackwire 3220 Series                                                                 | 1         | 1.01%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.01%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.01%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1         | 1.01%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.01%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1.01%   |
| Logitech Logi Z407                                                                                | 1         | 1.01%   |
| Kingston Technology HyperX SoloCast                                                               | 1         | 1.01%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 1         | 1.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.01%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.01%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.01%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.01%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.01%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.01%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.01%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 1.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.01%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.01%   |
| Corsair Corsair VOID RGB USB Gaming Headset                                                       | 1         | 1.01%   |
| ATI Technologies Kabini HDMI/DP Audio                                                             | 1         | 1.01%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 1         | 1.01%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 1.01%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.01%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1         | 1.01%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 1.01%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 22.22%  |
| SK hynix            | 9         | 14.29%  |
| Micron Technology   | 7         | 11.11%  |
| Kingston            | 6         | 9.52%   |
| G.Skill             | 6         | 9.52%   |
| Corsair             | 5         | 7.94%   |
| Unknown             | 4         | 6.35%   |
| Crucial             | 4         | 6.35%   |
| Ramaxel Technology  | 2         | 3.17%   |
| Team                | 1         | 1.59%   |
| Silicon Power       | 1         | 1.59%   |
| Nanya Technology    | 1         | 1.59%   |
| Goldkey             | 1         | 1.59%   |
| Avant               | 1         | 1.59%   |
| A-DATA Technology   | 1         | 1.59%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 2         | 2.94%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s      | 2         | 2.94%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s      | 2         | 2.94%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3000MT/s    | 2         | 2.94%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                 | 1         | 1.47%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                   | 1         | 1.47%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                        | 1         | 1.47%   |
| Unknown RAM Module 16GB DIMM DDR4 3600MT/s                  | 1         | 1.47%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s       | 1         | 1.47%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                | 1         | 1.47%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                | 1         | 1.47%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s        | 1         | 1.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s   | 1         | 1.47%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s        | 1         | 1.47%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 1.47%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 1         | 1.47%   |
| SK hynix RAM HMT125S6TFR8C-G7 2GB SODIMM DDR3 1067MT/s      | 1         | 1.47%   |
| SK hynix RAM HMT112S6TFR8C-G7 1GB SODIMM DDR3 1066MT/s      | 1         | 1.47%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s      | 1         | 1.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 1         | 1.47%   |
| Silicon Power RAM SP008GBLFU240B02 8GB DIMM DDR4 2400MT/s   | 1         | 1.47%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 1.47%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s       | 1         | 1.47%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 1.47%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 1         | 1.47%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s      | 1         | 1.47%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 1         | 1.47%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 1         | 1.47%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 1         | 1.47%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16384MB SODIMM 4800MT/s      | 1         | 1.47%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s      | 1         | 1.47%   |
| Samsung RAM M4 70T2864QZ3-CF7 1GB SODIMM DDR2 2048MT/s      | 1         | 1.47%   |
| Samsung RAM M393B1K70QB0 8GB DIMM DDR3 1866MT/s             | 1         | 1.47%   |
| Samsung RAM K4EBE304EE-EGCF 8GB SODIMM LPDDR3 1867MT/s      | 1         | 1.47%   |
| Samsung RAM K4EBE304EE-EGCF 8GB Chip LPDDR3 1867MT/s        | 1         | 1.47%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s   | 1         | 1.47%   |
| Ramaxel RAM RMR5030EF68F9W1600 4GB DIMM DDR3 1600MT/s       | 1         | 1.47%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR 2048MT/s           | 1         | 1.47%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB DIMM DDR3 1600MT/s         | 1         | 1.47%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s    | 1         | 1.47%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s        | 1         | 1.47%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 1.47%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 1         | 1.47%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s     | 1         | 1.47%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s           | 1         | 1.47%   |
| Kingston RAM KHX2400C12D4/8GX 8GB DIMM DDR4 2400MT/s        | 1         | 1.47%   |
| Kingston RAM ACR256X64D3S1333C9 2048MB SODIMM DDR3 1334MT/s | 1         | 1.47%   |
| Kingston RAM ACR16D3LS1NBG/4G 4GB SODIMM DDR3 1600MT/s      | 1         | 1.47%   |
| Kingston RAM 99U5702-025.A00G 8GB DIMM DDR4 2667MT/s        | 1         | 1.47%   |
| Goldkey RAM GKE800SO102408-2666A 8GB SODIMM DDR4 2667MT/s   | 1         | 1.47%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s       | 1         | 1.47%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s         | 1         | 1.47%   |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 3200MT/s          | 1         | 1.47%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s        | 1         | 1.47%   |
| Crucial RAM CT4G4SFS824A.C8FHP 4GB SODIMM DDR4 2133MT/s     | 1         | 1.47%   |
| Crucial RAM CT32G4SFD832A.M16FF 32GB SODIMM DDR4 3200MT/s   | 1         | 1.47%   |
| Crucial RAM BLT8G3D1608ET3LX0. 8GB DIMM DDR3 1867MT/s       | 1         | 1.47%   |
| Crucial RAM BL16G36C16U4BL.M8FB1 16GB DIMM DDR4 2667MT/s    | 1         | 1.47%   |
| Corsair RAM CMW32GX4M2Z3600C18 16GB DIMM DDR4 3733MT/s      | 1         | 1.47%   |
| Corsair RAM CMK8GX4M2A2133C13 4GB DIMM DDR4 2933MT/s        | 1         | 1.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 32        | 60.38%  |
| DDR3    | 15        | 28.3%   |
| Unknown | 2         | 3.77%   |
| SDRAM   | 1         | 1.89%   |
| LPDDR4  | 1         | 1.89%   |
| LPDDR3  | 1         | 1.89%   |
| DDR2    | 1         | 1.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 50%     |
| DIMM         | 25        | 46.3%   |
| Row Of Chips | 1         | 1.85%   |
| Chip         | 1         | 1.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 26        | 44.07%  |
| 16384 | 12        | 20.34%  |
| 4096  | 12        | 20.34%  |
| 2048  | 6         | 10.17%  |
| 1024  | 2         | 3.39%   |
| 32768 | 1         | 1.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 10        | 17.86%  |
| 1600  | 10        | 17.86%  |
| 3200  | 5         | 8.93%   |
| 3600  | 4         | 7.14%   |
| 3466  | 3         | 5.36%   |
| 2133  | 3         | 5.36%   |
| 1867  | 3         | 5.36%   |
| 2933  | 2         | 3.57%   |
| 2400  | 2         | 3.57%   |
| 2048  | 2         | 3.57%   |
| 1067  | 2         | 3.57%   |
| 8400  | 1         | 1.79%   |
| 4800  | 1         | 1.79%   |
| 4267  | 1         | 1.79%   |
| 3866  | 1         | 1.79%   |
| 3733  | 1         | 1.79%   |
| 3400  | 1         | 1.79%   |
| 1866  | 1         | 1.79%   |
| 1334  | 1         | 1.79%   |
| 1333  | 1         | 1.79%   |
| 1066  | 1         | 1.79%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)

![Printer Vendor](./All/images/line_chart/printer_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)

![Printer Model](./All/images/line_chart/printer_model.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung SCX-3400 Series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)

![Scanner Vendor](./All/images/line_chart/scanner_vendor.svg)

| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)

![Scanner Model](./All/images/line_chart/scanner_model.svg)

| Model            | Computers | Percent |
|------------------|-----------|---------|
| HP ScanJet 2400c | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)

![Camera Vendor](./All/images/line_chart/camera_vendor.svg)

| Vendor                                            | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Electronics                               | 9         | 24.32%  |
| Logitech                                          | 8         | 21.62%  |
| IMC Networks                                      | 4         | 10.81%  |
| Cheng Uei Precision Industry (Foxlink)            | 3         | 8.11%   |
| Sunplus Innovation Technology                     | 2         | 5.41%   |
| Realtek Semiconductor                             | 2         | 5.41%   |
| Acer                                              | 2         | 5.41%   |
| Suyin                                             | 1         | 2.7%    |
| STMicroelectronics Imaging Division (VLSI Vision) | 1         | 2.7%    |
| Quanta                                            | 1         | 2.7%    |
| OmniVision Technologies                           | 1         | 2.7%    |
| Microdia                                          | 1         | 2.7%    |
| AVerMedia Technologies                            | 1         | 2.7%    |
| Apple                                             | 1         | 2.7%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                   | 3         | 8.11%   |
| Chicony Integrated Camera                                        | 3         | 8.11%   |
| Sunplus FHD Camera Microphone                                    | 2         | 5.41%   |
| Logitech HD Pro Webcam C920                                      | 2         | 5.41%   |
| Chicony HD Webcam                                                | 2         | 5.41%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera   | 2         | 5.41%   |
| Suyin Integrated_Webcam_HD                                       | 1         | 2.7%    |
| STMicroelectronics Imaging Division (VLSI Vision) STV0680 Camera | 1         | 2.7%    |
| Realtek WEB CAMERA M9 Pro                                        | 1         | 2.7%    |
| Realtek Acer 640 x 480 laptop camera                             | 1         | 2.7%    |
| Quanta USB HD Webcam                                             | 1         | 2.7%    |
| OmniVision Monitor Webcam                                        | 1         | 2.7%    |
| Microdia Sonix USB 2.0 Camera                                    | 1         | 2.7%    |
| Logitech Webcam Pro 9000                                         | 1         | 2.7%    |
| Logitech Webcam C930e                                            | 1         | 2.7%    |
| Logitech Webcam C925e                                            | 1         | 2.7%    |
| Logitech Webcam C270                                             | 1         | 2.7%    |
| Logitech HD Webcam B910                                          | 1         | 2.7%    |
| Logitech C920 PRO HD Webcam                                      | 1         | 2.7%    |
| IMC Networks USB2.0 HD UVC WebCam                                | 1         | 2.7%    |
| Chicony USB 2.0 Camera                                           | 1         | 2.7%    |
| Chicony HP HD Camera                                             | 1         | 2.7%    |
| Chicony HD WebCam (Acer)                                         | 1         | 2.7%    |
| Chicony CNA7157                                                  | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera              | 1         | 2.7%    |
| AVerMedia Live Streamer CAM 313                                  | 1         | 2.7%    |
| Apple Built-in iSight                                            | 1         | 2.7%    |
| Acer EasyCamera                                                  | 1         | 2.7%    |
| Acer BisonCam,NB Pro                                             | 1         | 2.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 40%     |
| Synaptics        | 2         | 40%     |
| AuthenTec        | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 20%     |
| Validity Sensors Synaptics WBDI            | 1         | 20%     |
| Synaptics WBDI Device                      | 1         | 20%     |
| AuthenTec AES1600                          | 1         | 20%     |
| Unknown                                    | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./All/images/line_chart/chipcard_vendor.svg)

| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model          | Computers | Percent |
|----------------|-----------|---------|
| Broadcom 58200 | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 44        | 81.48%  |
| 1     | 7         | 12.96%  |
| 2     | 3         | 5.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 4         | 33.33%  |
| Graphics card            | 3         | 25%     |
| Network                  | 1         | 8.33%   |
| Net/wireless             | 1         | 8.33%   |
| Multimedia controller    | 1         | 8.33%   |
| Communication controller | 1         | 8.33%   |
| Chipcard                 | 1         | 8.33%   |

