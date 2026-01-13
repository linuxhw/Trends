Xubuntu - Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Xubuntu/Desktop/README.md) and [notebooks](/Dist/Xubuntu/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: Dec, 2025.

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
| Xubuntu 24.04 | 25        | 55.56%  |
| Xubuntu 25.10 | 9         | 20%     |
| Xubuntu 22.04 | 5         | 11.11%  |
| Xubuntu 20.04 | 2         | 4.44%   |
| Xubuntu 18.04 | 2         | 4.44%   |
| Xubuntu 25.04 | 1         | 2.22%   |
| Xubuntu 22.10 | 1         | 2.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Xubuntu | 45        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 6.8.0-90-generic      | 7         | 15.56%  |
| 6.8.0-88-generic      | 5         | 11.11%  |
| 6.17.0-7-generic      | 5         | 11.11%  |
| 6.14.0-37-generic     | 5         | 11.11%  |
| 6.14.0-36-generic     | 5         | 11.11%  |
| 6.17.0-8-generic      | 2         | 4.44%   |
| 5.15.0-163-generic    | 2         | 4.44%   |
| 4.15.0-213-generic    | 2         | 4.44%   |
| 6.8.0-88-lowlatency   | 1         | 2.22%   |
| 6.8.0-87-generic      | 1         | 2.22%   |
| 6.8.0-41-generic      | 1         | 2.22%   |
| 6.18.2                | 1         | 2.22%   |
| 6.17.6-061706-generic | 1         | 2.22%   |
| 6.17.0-5-generic      | 1         | 2.22%   |
| 6.14.0-15-generic     | 1         | 2.22%   |
| 5.4.0-216-generic     | 1         | 2.22%   |
| 5.19.0-46-generic     | 1         | 2.22%   |
| 5.15.0-43-generic     | 1         | 2.22%   |
| 5.15.0-139-generic    | 1         | 2.22%   |
| 5.15.0-118-lowlatency | 1         | 2.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.8.0   | 15        | 33.33%  |
| 6.14.0  | 11        | 24.44%  |
| 6.17.0  | 8         | 17.78%  |
| 5.15.0  | 5         | 11.11%  |
| 4.15.0  | 2         | 4.44%   |
| 6.18.2  | 1         | 2.22%   |
| 6.17.6  | 1         | 2.22%   |
| 5.4.0   | 1         | 2.22%   |
| 5.19.0  | 1         | 2.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.8     | 15        | 33.33%  |
| 6.14    | 11        | 24.44%  |
| 6.17    | 9         | 20%     |
| 5.15    | 5         | 11.11%  |
| 4.15    | 2         | 4.44%   |
| 6.18    | 1         | 2.22%   |
| 5.4     | 1         | 2.22%   |
| 5.19    | 1         | 2.22%   |

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

| Name | Computers | Percent |
|------|-----------|---------|
| XFCE | 41        | 91.11%  |
| i3   | 2         | 4.44%   |
| KDE5 | 1         | 2.22%   |
| KDE  | 1         | 2.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 44        | 97.78%  |
| Wayland | 1         | 2.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 43        | 95.56%  |
| SDDM    | 2         | 4.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 19        | 42.22%  |
| fr_FR | 8         | 17.78%  |
| de_DE | 3         | 6.67%   |
| C     | 3         | 6.67%   |
| ru_RU | 2         | 4.44%   |
| es_ES | 2         | 4.44%   |
| tr_TR | 1         | 2.22%   |
| pl_PL | 1         | 2.22%   |
| nl_NL | 1         | 2.22%   |
| nl_BE | 1         | 2.22%   |
| ja_JP | 1         | 2.22%   |
| it_IT | 1         | 2.22%   |
| en_NZ | 1         | 2.22%   |
| en_GB | 1         | 2.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 23        | 51.11%  |
| BIOS | 22        | 48.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 25        | 55.56%  |
| Tmpfs   | 16        | 35.56%  |
| Overlay | 2         | 4.44%   |
| Zfs     | 1         | 2.22%   |
| Btrfs   | 1         | 2.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 36        | 80%     |
| MBR  | 9         | 20%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 84.44%  |
| Yes       | 7         | 15.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 26        | 57.78%  |
| Yes       | 19        | 42.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 10        | 22.22%  |
| Hewlett-Packard                      | 6         | 13.33%  |
| ASUSTek Computer                     | 5         | 11.11%  |
| Dell                                 | 4         | 8.89%   |
| Toshiba                              | 3         | 6.67%   |
| MSI                                  | 2         | 4.44%   |
| ASRock                               | 2         | 4.44%   |
| Apple                                | 2         | 4.44%   |
| Acer                                 | 2         | 4.44%   |
| TongFang                             | 1         | 2.22%   |
| Shenzhen Meigao Electronic Equipment | 1         | 2.22%   |
| Medion                               | 1         | 2.22%   |
| Intel                                | 1         | 2.22%   |
| Google                               | 1         | 2.22%   |
| Gigabyte Technology                  | 1         | 2.22%   |
| Framework                            | 1         | 2.22%   |
| Chuwi                                | 1         | 2.22%   |
| AZW                                  | 1         | 2.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Toshiba Satellite L55-C                               | 1         | 2.22%   |
| Toshiba Satellite L300                                | 1         | 2.22%   |
| Toshiba Satellite C855-2DG                            | 1         | 2.22%   |
| TongFang GM7IX0N                                      | 1         | 2.22%   |
| Shenzhen Meigao Electronic Equipment EliteMini Series | 1         | 2.22%   |
| MSI MS-7998                                           | 1         | 2.22%   |
| MSI GF63 Thin 11UC                                    | 1         | 2.22%   |
| Medion Akoya P2120 D MD8836/2452                      | 1         | 2.22%   |
| Lenovo ThinkPad X220 42912WG                          | 1         | 2.22%   |
| Lenovo ThinkPad T480 20L6SE5A00                       | 1         | 2.22%   |
| Lenovo ThinkPad P16 Gen 3 21RQCTO1WW                  | 1         | 2.22%   |
| Lenovo ThinkPad P15 Gen 1 20SUS6TY0B                  | 1         | 2.22%   |
| Lenovo ThinkCentre M910q 10MUS0B600                   | 1         | 2.22%   |
| Lenovo ThinkCentre M73 10B5A002NZ                     | 1         | 2.22%   |
| Lenovo ThinkBook 14 G6 ABP 21KJ                       | 1         | 2.22%   |
| Lenovo IdeaPad Slim 3 15ABR8 82XM                     | 1         | 2.22%   |
| Lenovo IdeaPad 3 17ADA05 81W2                         | 1         | 2.22%   |
| Lenovo IdeaPad 100-15IBD 80QQ                         | 1         | 2.22%   |
| Intel NUC10i7FNK                                      | 1         | 2.22%   |
| HP Z210 CMT Workstation                               | 1         | 2.22%   |
| HP ProBook 6570b                                      | 1         | 2.22%   |
| HP ProBook 4520s                                      | 1         | 2.22%   |
| HP OmniBook 5 Laptop 16-af1xxx                        | 1         | 2.22%   |
| HP EliteBook 8570p                                    | 1         | 2.22%   |
| HP EliteBook 640 14 inch G9 Notebook PC               | 1         | 2.22%   |
| Google Swanky                                         | 1         | 2.22%   |
| Gigabyte H61M-S2PV                                    | 1         | 2.22%   |
| Framework Laptop 13 (AMD Ryzen AI 300 Series)         | 1         | 2.22%   |
| Dell Studio XPS 7100                                  | 1         | 2.22%   |
| Dell Precision M6500                                  | 1         | 2.22%   |
| Dell OptiPlex 7010                                    | 1         | 2.22%   |
| Dell Latitude 5431                                    | 1         | 2.22%   |
| Chuwi CoreBook X                                      | 1         | 2.22%   |
| AZW MINI S                                            | 1         | 2.22%   |
| ASUS TUF Gaming FX505DT_FX505DT                       | 1         | 2.22%   |
| ASUS ROG CROSSHAIR VIII DARK HERO                     | 1         | 2.22%   |
| ASUS P8H61-MX R2.0                                    | 1         | 2.22%   |
| ASUS P7P55D                                           | 1         | 2.22%   |
| ASUS B150-PLUS                                        | 1         | 2.22%   |
| ASRock B450 Pro4                                      | 1         | 2.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name                                           | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Lenovo ThinkPad                                | 4         | 8.89%   |
| Toshiba Satellite                              | 3         | 6.67%   |
| Lenovo IdeaPad                                 | 3         | 6.67%   |
| Lenovo ThinkCentre                             | 2         | 4.44%   |
| HP ProBook                                     | 2         | 4.44%   |
| HP EliteBook                                   | 2         | 4.44%   |
| ASRock B450                                    | 2         | 4.44%   |
| Apple iMac14                                   | 2         | 4.44%   |
| TongFang GM7IX0N                               | 1         | 2.22%   |
| Shenzhen Meigao Electronic Equipment EliteMini | 1         | 2.22%   |
| MSI MS-7998                                    | 1         | 2.22%   |
| MSI GF63                                       | 1         | 2.22%   |
| Medion Akoya                                   | 1         | 2.22%   |
| Lenovo ThinkBook                               | 1         | 2.22%   |
| Intel NUC10i7FNK                               | 1         | 2.22%   |
| HP Z210                                        | 1         | 2.22%   |
| HP OmniBook                                    | 1         | 2.22%   |
| Google Swanky                                  | 1         | 2.22%   |
| Gigabyte H61M-S2PV                             | 1         | 2.22%   |
| Framework Laptop                               | 1         | 2.22%   |
| Dell Studio                                    | 1         | 2.22%   |
| Dell Precision                                 | 1         | 2.22%   |
| Dell OptiPlex                                  | 1         | 2.22%   |
| Dell Latitude                                  | 1         | 2.22%   |
| Chuwi CoreBook                                 | 1         | 2.22%   |
| AZW MINI                                       | 1         | 2.22%   |
| ASUS TUF                                       | 1         | 2.22%   |
| ASUS ROG                                       | 1         | 2.22%   |
| ASUS P8H61-MX                                  | 1         | 2.22%   |
| ASUS P7P55D                                    | 1         | 2.22%   |
| ASUS B150-PLUS                                 | 1         | 2.22%   |
| Acer Swift                                     | 1         | 2.22%   |
| Acer Aspire                                    | 1         | 2.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2015 | 6         | 13.33%  |
| 2018 | 5         | 11.11%  |
| 2025 | 4         | 8.89%   |
| 2012 | 4         | 8.89%   |
| 2023 | 3         | 6.67%   |
| 2021 | 3         | 6.67%   |
| 2020 | 3         | 6.67%   |
| 2013 | 3         | 6.67%   |
| 2010 | 3         | 6.67%   |
| 2024 | 2         | 4.44%   |
| 2022 | 2         | 4.44%   |
| 2014 | 2         | 4.44%   |
| 2019 | 1         | 2.22%   |
| 2016 | 1         | 2.22%   |
| 2011 | 1         | 2.22%   |
| 2009 | 1         | 2.22%   |
| 2008 | 1         | 2.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 26        | 57.78%  |
| Desktop    | 14        | 31.11%  |
| Mini pc    | 3         | 6.67%   |
| All in one | 2         | 4.44%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 38        | 84.44%  |
| Enabled  | 7         | 15.56%  |

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
| 16.01-24.0  | 11        | 24.44%  |
| 8.01-16.0   | 10        | 22.22%  |
| 4.01-8.0    | 7         | 15.56%  |
| 32.01-64.0  | 6         | 13.33%  |
| 3.01-4.0    | 5         | 11.11%  |
| 64.01-256.0 | 4         | 8.89%   |
| 24.01-32.0  | 2         | 4.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 15        | 33.33%  |
| 1.01-2.0   | 11        | 24.44%  |
| 2.01-3.0   | 8         | 17.78%  |
| 3.01-4.0   | 4         | 8.89%   |
| 8.01-16.0  | 4         | 8.89%   |
| 0.51-1.0   | 2         | 4.44%   |
| 16.01-24.0 | 1         | 2.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 24        | 53.33%  |
| 2      | 16        | 35.56%  |
| 6      | 2         | 4.44%   |
| 3      | 2         | 4.44%   |
| 5      | 1         | 2.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 28        | 62.22%  |
| Yes       | 17        | 37.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 88.89%  |
| No        | 5         | 11.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 86.67%  |
| No        | 6         | 13.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 66.67%  |
| No        | 15        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 9         | 20%     |
| France      | 9         | 20%     |
| Germany     | 4         | 8.89%   |
| New Zealand | 3         | 6.67%   |
| Italy       | 3         | 6.67%   |
| UK          | 2         | 4.44%   |
| Sweden      | 2         | 4.44%   |
| Spain       | 2         | 4.44%   |
| Russia      | 2         | 4.44%   |
| Canada      | 2         | 4.44%   |
| Belgium     | 2         | 4.44%   |
| Turkey      | 1         | 2.22%   |
| Poland      | 1         | 2.22%   |
| Norway      | 1         | 2.22%   |
| India       | 1         | 2.22%   |
| Australia   | 1         | 2.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Colorado Springs        | 2         | 4.44%   |
| Tula                    | 1         | 2.22%   |
| Toulon                  | 1         | 2.22%   |
| Thouars                 | 1         | 2.22%   |
| Strasbourg              | 1         | 2.22%   |
| Stockholm               | 1         | 2.22%   |
| Stavanger               | 1         | 2.22%   |
| Selm                    | 1         | 2.22%   |
| Reutlingen              | 1         | 2.22%   |
| Redding                 | 1         | 2.22%   |
| Portland                | 1         | 2.22%   |
| Perth                   | 1         | 2.22%   |
| Paris                   | 1         | 2.22%   |
| Naples                  | 1         | 2.22%   |
| Mostoles                | 1         | 2.22%   |
| Moscow                  | 1         | 2.22%   |
| Milan                   | 1         | 2.22%   |
| Lugo                    | 1         | 2.22%   |
| Lower Hutt              | 1         | 2.22%   |
| Lincoln                 | 1         | 2.22%   |
| Les Hogues              | 1         | 2.22%   |
| Lenoir                  | 1         | 2.22%   |
| Lansdowne               | 1         | 2.22%   |
| La Croix-de-la-Rochette | 1         | 2.22%   |
| Kortrijk                | 1         | 2.22%   |
| Kitchener               | 1         | 2.22%   |
| Kernersville            | 1         | 2.22%   |
| Hanover                 | 1         | 2.22%   |
| Grasse                  | 1         | 2.22%   |
| Gothenburg              | 1         | 2.22%   |
| Gdansk                  | 1         | 2.22%   |
| Decatur                 | 1         | 2.22%   |
| Dannevirke              | 1         | 2.22%   |
| Dallas                  | 1         | 2.22%   |
| Christchurch            | 1         | 2.22%   |
| Busto Arsizio           | 1         | 2.22%   |
| Bingley                 | 1         | 2.22%   |
| Berlin                  | 1         | 2.22%   |
| Bengaluru               | 1         | 2.22%   |
| Barnet                  | 1         | 2.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 9         | 11     | 14.52%  |
| Seagate                     | 8         | 12     | 12.9%   |
| WDC                         | 7         | 9      | 11.29%  |
| Crucial                     | 6         | 7      | 9.68%   |
| SanDisk                     | 5         | 6      | 8.06%   |
| Toshiba                     | 4         | 4      | 6.45%   |
| KIOXIA                      | 3         | 3      | 4.84%   |
| Hitachi                     | 3         | 4      | 4.84%   |
| Micron Technology           | 2         | 2      | 3.23%   |
| Kingston                    | 2         | 2      | 3.23%   |
| China                       | 2         | 2      | 3.23%   |
| Unknown                     | 1         | 1      | 1.61%   |
| Realtek Semiconductor       | 1         | 1      | 1.61%   |
| Phison Electronics          | 1         | 1      | 1.61%   |
| Phison                      | 1         | 2      | 1.61%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 1.61%   |
| Kingston Technology Company | 1         | 2      | 1.61%   |
| KingSpec                    | 1         | 1      | 1.61%   |
| Intel                       | 1         | 1      | 1.61%   |
| Fanxiang                    | 1         | 2      | 1.61%   |
| EDILOCA                     | 1         | 1      | 1.61%   |
| Apple                       | 1         | 2      | 1.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| SanDisk SSD PLUS 1000GB                           | 2         | 2.86%   |
| Samsung SSD 850 EVO 250GB                         | 2         | 2.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 2.86%   |
| Crucial CT1000MX500SSD1 1TB                       | 2         | 2.86%   |
| WDC WDS500G2B0A-00SM50 500GB                      | 1         | 1.43%   |
| WDC WD800JD-00LSA0 80GB                           | 1         | 1.43%   |
| WDC WD2003FYYS-05T9B0 2TB                         | 1         | 1.43%   |
| WDC WD1600AAJS-07PSA0 160GB                       | 1         | 1.43%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 1         | 1.43%   |
| WDC WD10EURX-73FH1Y0 1TB                          | 1         | 1.43%   |
| WDC WD1001FAES-75W7A0 1TB                         | 1         | 1.43%   |
| WDC WD10 JPVX-60JC3T1 1TB                         | 1         | 1.43%   |
| WDC PC SN540 SDDPNPF-512G-1032 512GB              | 1         | 1.43%   |
| Unknown MMC Card  16GB                            | 1         | 1.43%   |
| Toshiba MQ01ABD050V 500GB                         | 1         | 1.43%   |
| Toshiba MK3261GSYN 320GB                          | 1         | 1.43%   |
| Toshiba HDWD110 1TB                               | 1         | 1.43%   |
| Toshiba BG3 NVMe SSD Controller 256GB             | 1         | 1.43%   |
| Seagate ST500LT012-9WS142 500GB                   | 1         | 1.43%   |
| Seagate ST4000NE 001-2MA101 4TB                   | 1         | 1.43%   |
| Seagate ST3000DM008-2DM166 3TB                    | 1         | 1.43%   |
| Seagate ST250LM004 HN-M250MBB 250GB               | 1         | 1.43%   |
| Seagate ST2000DM001-1ER164 2TB                    | 1         | 1.43%   |
| Seagate ST2000DM001-1CH164 2TB                    | 1         | 1.43%   |
| Seagate ST1000LM035-1RK172 1TB                    | 1         | 1.43%   |
| Seagate ST1000DM003-9YN162 1TB                    | 1         | 1.43%   |
| Seagate Expansion SW 5TB                          | 1         | 1.43%   |
| SanDisk SDSSDH3 500G                              | 1         | 1.43%   |
| SanDisk SD9SN8W256G1014 256GB SSD                 | 1         | 1.43%   |
| SanDisk NVMe SSD Drive 2TB                        | 1         | 1.43%   |
| SanDisk NVMe SSD Drive 256GB                      | 1         | 1.43%   |
| Samsung SSD 870 EVO 1TB                           | 1         | 1.43%   |
| Samsung SSD 850 EVO 500GB                         | 1         | 1.43%   |
| Samsung MZVLC2T0HBLD-00BLL 2TB                    | 1         | 1.43%   |
| Samsung MZVLC1T0HFLU-00BLL 1TB                    | 1         | 1.43%   |
| Samsung MZNLF128HCHP-00000 128GB SSD              | 1         | 1.43%   |
| Samsung MZ7PC128HAFU-000H1 128GB SSD              | 1         | 1.43%   |
| Realtek SPCC M.2 PCIe SSD 1024GB                  | 1         | 1.43%   |
| Phison Sabrent Rocket 4.0 Plus 2TB                | 1         | 1.43%   |
| Phison PSENN001TA87QC0 1024GB                     | 1         | 1.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 12     | 40%     |
| WDC     | 5         | 7      | 25%     |
| Toshiba | 3         | 3      | 15%     |
| Hitachi | 3         | 4      | 15%     |
| Apple   | 1         | 1      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 28.57%  |
| Crucial             | 6         | 7      | 28.57%  |
| SanDisk             | 3         | 4      | 14.29%  |
| China               | 2         | 2      | 9.52%   |
| WDC                 | 1         | 1      | 4.76%   |
| Kingston            | 1         | 1      | 4.76%   |
| KingSpec            | 1         | 1      | 4.76%   |
| Apple               | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 20        | 25     | 34.48%  |
| HDD  | 19        | 27     | 32.76%  |
| SSD  | 18        | 24     | 31.03%  |
| MMC  | 1         | 1      | 1.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 30        | 45     | 55.56%  |
| NVMe | 20        | 25     | 37.04%  |
| SAS  | 3         | 6      | 5.56%   |
| MMC  | 1         | 1      | 1.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 19        | 24     | 46.34%  |
| 0.51-1.0   | 14        | 16     | 34.15%  |
| 1.01-2.0   | 5         | 5      | 12.2%   |
| 3.01-4.0   | 1         | 4      | 2.44%   |
| 2.01-3.0   | 1         | 1      | 2.44%   |
| 4.01-10.0  | 1         | 1      | 2.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 9         | 20%     |
| 251-500        | 8         | 17.78%  |
| 101-250        | 7         | 15.56%  |
| 1001-2000      | 5         | 11.11%  |
| 1-20           | 5         | 11.11%  |
| 51-100         | 4         | 8.89%   |
| More than 3000 | 3         | 6.67%   |
| 2001-3000      | 3         | 6.67%   |
| Unknown        | 1         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 14        | 31.11%  |
| 101-250        | 6         | 13.33%  |
| 501-1000       | 6         | 13.33%  |
| 251-500        | 5         | 11.11%  |
| 21-50          | 4         | 8.89%   |
| 51-100         | 4         | 8.89%   |
| 2001-3000      | 2         | 4.44%   |
| 1001-2000      | 2         | 4.44%   |
| More than 3000 | 1         | 2.22%   |
| Unknown        | 1         | 2.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD2003FYYS-05T9B0 2TB      | 1         | 1      | 33.33%  |
| WDC WD10JPVX-22JC3T0 1TB       | 1         | 1      | 33.33%  |
| Seagate ST1000DM003-9YN162 1TB | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 66.67%  |
| Seagate | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 66.67%  |
| Seagate | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 100%    |

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
| Works    | 25        | 44     | 52.08%  |
| Detected | 20        | 30     | 41.67%  |
| Malfunc  | 3         | 3      | 6.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 29        | 49.15%  |
| AMD                          | 6         | 10.17%  |
| SanDisk                      | 3         | 5.08%   |
| Samsung Electronics          | 3         | 5.08%   |
| MAXIO Technology (Hangzhou)  | 3         | 5.08%   |
| KIOXIA                       | 3         | 5.08%   |
| Phison Electronics           | 2         | 3.39%   |
| Micron Technology            | 2         | 3.39%   |
| Kingston Technology Company  | 2         | 3.39%   |
| Toshiba America Info Systems | 1         | 1.69%   |
| Realtek Semiconductor        | 1         | 1.69%   |
| Marvell Technology Group     | 1         | 1.69%   |
| JMicron Technology           | 1         | 1.69%   |
| INNOGRIT                     | 1         | 1.69%   |
| ASMedia Technology           | 1         | 1.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 4         | 5.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 4.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 2.99%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                                | 2         | 2.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 2.99%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2         | 2.99%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 2.99%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2         | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 2.99%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 2.99%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)                     | 1         | 1.49%   |
| Sandisk WD PC SN740 NVMe SSD 512GB (DRAM-less)                                          | 1         | 1.49%   |
| SanDisk WD PC SN540 / Green SN350 NVMe SSD 1 TB (DRAM-less)                             | 1         | 1.49%   |
| Sandisk WD Black SN850X NVMe SSD                                                        | 1         | 1.49%   |
| Samsung NVMe SSD 9100 PRO [PM9E1]                                                       | 1         | 1.49%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                       | 1         | 1.49%   |
| Phison PS5027-E27T PCIe4 NVMe Controller (DRAM-less)                                    | 1         | 1.49%   |
| Phison E18 PCIe4 NVMe Controller                                                        | 1         | 1.49%   |
| Micron 2500 NVMe SSD (DRAM-less)                                                        | 1         | 1.49%   |
| Micron 2200S NVMe SSD [Cassandra]                                                       | 1         | 1.49%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 1         | 1.49%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                              | 1         | 1.49%   |
| KIOXIA NVMe SSD Controller XG8                                                          | 1         | 1.49%   |
| KIOXIA NVMe SSD Controller XG7                                                          | 1         | 1.49%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                              | 1         | 1.49%   |
| Kingston Company NV2 NVMe SSD [E21T] (DRAM-less)                                        | 1         | 1.49%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                                    | 1         | 1.49%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1         | 1.49%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1         | 1.49%   |
| Intel Tiger Lake SATA AHCI Controller                                                   | 1         | 1.49%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                        | 1         | 1.49%   |
| Intel SATA Controller [RAID mode]                                                       | 1         | 1.49%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 1.49%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 1.49%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 1.49%   |
| Intel Alder Lake-N SATA AHCI Controller                                                 | 1         | 1.49%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 1.49%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 1         | 1.49%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1         | 1.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 26        | 46.43%  |
| NVMe | 20        | 35.71%  |
| IDE  | 7         | 12.5%   |
| RAID | 3         | 5.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 35        | 77.78%  |
| AMD    | 10        | 22.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 4.44%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 2.22%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 2.22%   |
| Intel N150                                    | 1         | 2.22%   |
| Intel Core Ultra 9 285HX                      | 1         | 2.22%   |
| Intel Core Ultra 7 255U                       | 1         | 2.22%   |
| Intel Core i9-14900HX                         | 1         | 2.22%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 2.22%   |
| Intel Core i7-4771 CPU @ 3.50GHz              | 1         | 2.22%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 2.22%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 2.22%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 2.22%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 2.22%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 1         | 2.22%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 2.22%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 2.22%   |
| Intel Core i7 CPU X 940 @ 2.13GHz             | 1         | 2.22%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 1         | 2.22%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 2.22%   |
| Intel Core i5-6500T CPU @ 2.50GHz             | 1         | 2.22%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 2.22%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 2.22%   |
| Intel Core i5-4260U CPU @ 1.40GHz             | 1         | 2.22%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 2.22%   |
| Intel Core i5-2320 CPU @ 3.00GHz              | 1         | 2.22%   |
| Intel Core i5 CPU 760 @ 2.80GHz               | 1         | 2.22%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 1         | 2.22%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 2.22%   |
| Intel Core i3-2348M CPU @ 2.30GHz             | 1         | 2.22%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 1         | 2.22%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 2.22%   |
| Intel 12th Gen Core i7-1270P                  | 1         | 2.22%   |
| Intel 12th Gen Core i7-1265U                  | 1         | 2.22%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 2.22%   |
| AMD Ryzen AI 9 HX 370 w/ Radeon 890M          | 1         | 2.22%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 1         | 2.22%   |
| AMD Ryzen 7 8845HS w/ Radeon 780M Graphics    | 1         | 2.22%   |
| AMD Ryzen 7 5825U with Radeon Graphics        | 1         | 2.22%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 1         | 2.22%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 2.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 11        | 24.44%  |
| Intel Core i7           | 10        | 22.22%  |
| Other                   | 5         | 11.11%  |
| Intel Core i3           | 4         | 8.89%   |
| AMD Ryzen 7             | 4         | 8.89%   |
| Intel Core              | 2         | 4.44%   |
| AMD Ryzen 5             | 2         | 4.44%   |
| Intel Pentium Silver    | 1         | 2.22%   |
| Intel Pentium Dual-Core | 1         | 2.22%   |
| Intel Core i9           | 1         | 2.22%   |
| Intel Celeron           | 1         | 2.22%   |
| AMD Ryzen 9             | 1         | 2.22%   |
| AMD Phenom II X6        | 1         | 2.22%   |
| AMD Athlon              | 1         | 2.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 16        | 35.56%  |
| 2      | 13        | 28.89%  |
| 6      | 5         | 11.11%  |
| 8      | 4         | 8.89%   |
| 12     | 3         | 6.67%   |
| 24     | 2         | 4.44%   |
| 16     | 1         | 2.22%   |
| 10     | 1         | 2.22%   |

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
| 2      | 30        | 66.67%  |
| 1      | 15        | 33.33%  |

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

| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 38        | 84.44%  |
| 0x306a9 | 3         | 6.67%   |
| 0x206a7 | 2         | 4.44%   |
| 0xb06e0 | 1         | 2.22%   |
| 0x1067a | 1         | 2.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 6         | 13.33%  |
| Zen 3             | 4         | 8.89%   |
| Skylake           | 4         | 8.89%   |
| SandyBridge       | 4         | 8.89%   |
| IvyBridge         | 4         | 8.89%   |
| Haswell           | 4         | 8.89%   |
| Zen+              | 2         | 4.44%   |
| Nehalem           | 2         | 4.44%   |
| KabyLake          | 2         | 4.44%   |
| CometLake         | 2         | 4.44%   |
| Broadwell         | 2         | 4.44%   |
| Zen 2             | 1         | 2.22%   |
| Westmere          | 1         | 2.22%   |
| Silvermont        | 1         | 2.22%   |
| Penryn            | 1         | 2.22%   |
| Meteorlake Hybrid | 1         | 2.22%   |
| Lunarlake Hybrid  | 1         | 2.22%   |
| K10               | 1         | 2.22%   |
| Icelake           | 1         | 2.22%   |
| Goldmont plus     | 1         | 2.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 24        | 47.06%  |
| Nvidia | 14        | 27.45%  |
| AMD    | 13        | 25.49%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 2         | 3.7%    |
| Intel Skylake-S GT2 [HD Graphics 530]                                     | 2         | 3.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 3.7%    |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                  | 2         | 3.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 3.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 3.7%    |
| AMD Barcelo                                                               | 2         | 3.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 1.85%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 1         | 1.85%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 1         | 1.85%   |
| Nvidia GT218 [GeForce 210]                                                | 1         | 1.85%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 1         | 1.85%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 1.85%   |
| Nvidia GK104M [GeForce GTX 775M Mac Edition]                              | 1         | 1.85%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 1.85%   |
| Nvidia GB206GLM [RTX PRO 2000 Blackwell Generation Laptop GPU]            | 1         | 1.85%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 1.85%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                            | 1         | 1.85%   |
| Nvidia G92GLM [Quadro FX 3800M]                                           | 1         | 1.85%   |
| Nvidia G92 [GeForce 9800 GT]                                              | 1         | 1.85%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                           | 1         | 1.85%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 1         | 1.85%   |
| Intel Raptor Lake-S UHD Graphics                                          | 1         | 1.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 1.85%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                   | 1         | 1.85%   |
| Intel GeminiLake [UHD Graphics 605]                                       | 1         | 1.85%   |
| Intel Comet Lake UHD Graphics                                             | 1         | 1.85%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                          | 1         | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 1.85%   |
| Intel Arrow Lake-U [Intel Graphics]                                       | 1         | 1.85%   |
| Intel Arrow Lake-S [Intel Graphics]                                       | 1         | 1.85%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 1         | 1.85%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 1         | 1.85%   |
| Intel Alder Lake-N [Intel Graphics]                                       | 1         | 1.85%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 1         | 1.85%   |
| AMD Whistler LE [Radeon HD 6610M/7610M]                                   | 1         | 1.85%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                  | 1         | 1.85%   |
| AMD Strix [Radeon 880M / 890M]                                            | 1         | 1.85%   |
| AMD RV620 LE [Radeon HD 3450]                                             | 1         | 1.85%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                | 1         | 1.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 19        | 42.22%  |
| 1 x AMD        | 11        | 24.44%  |
| 1 x Nvidia     | 8         | 17.78%  |
| Intel + Nvidia | 5         | 11.11%  |
| 2 x AMD        | 1         | 2.22%   |
| AMD + Nvidia   | 1         | 2.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 35        | 77.78%  |
| Unknown     | 6         | 13.33%  |
| Proprietary | 4         | 8.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 64.44%  |
| 0.51-1.0   | 5         | 11.11%  |
| 1.01-2.0   | 3         | 6.67%   |
| 3.01-4.0   | 2         | 4.44%   |
| 8.01-16.0  | 2         | 4.44%   |
| 0.01-0.5   | 2         | 4.44%   |
| 7.01-8.0   | 1         | 2.22%   |
| 5.01-6.0   | 1         | 2.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 7         | 14%     |
| Chimei Innolux       | 5         | 10%     |
| BOE                  | 5         | 10%     |
| LG Display           | 3         | 6%      |
| Goldstar             | 3         | 6%      |
| AU Optronics         | 3         | 6%      |
| Apple                | 3         | 6%      |
| NEC Computers        | 2         | 4%      |
| Lenovo               | 2         | 4%      |
| Hewlett-Packard      | 2         | 4%      |
| Dell                 | 2         | 4%      |
| Acer                 | 2         | 4%      |
| Vizio                | 1         | 2%      |
| Philips              | 1         | 2%      |
| MSI                  | 1         | 2%      |
| Medion               | 1         | 2%      |
| LG Philips           | 1         | 2%      |
| Fujitsu Siemens      | 1         | 2%      |
| FL_                  | 1         | 2%      |
| DPL                  | 1         | 2%      |
| CSOT                 | 1         | 2%      |
| AOC                  | 1         | 2%      |
| Ancor Communications | 1         | 2%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 2         | 3.85%   |
| Vizio D24-D1 VIZ1005 1920x1080 521x293mm 23.5-inch                    | 1         | 1.92%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 521x293mm 23.5-inch   | 1         | 1.92%   |
| Samsung Electronics LS24C36x SAM7314 1920x1080 598x336mm 27.0-inch    | 1         | 1.92%   |
| Samsung Electronics LS24C33xG SAM7435 1920x1080 527x296mm 23.8-inch   | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 367x230mm 17.1-inch | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch  | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SDC4A52 1366x768 344x194mm 15.5-inch  | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SDC4214 1920x1200 344x215mm 16.0-inch | 1         | 1.92%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 1.92%   |
| Philips 190S5 PHL0824 1280x1024 376x301mm 19.0-inch                   | 1         | 1.92%   |
| NEC Computers LCD72VM NEC6659 1280x1024 338x270mm 17.0-inch           | 1         | 1.92%   |
| NEC Computers E224Wi NEC6950 1920x1080 476x267mm 21.5-inch            | 1         | 1.92%   |
| MSI MD272QP MSI40B1 2560x1440 600x330mm 27.0-inch                     | 1         | 1.92%   |
| Medion MD20435 MED36D5 1920x1080 521x293mm 23.5-inch                  | 1         | 1.92%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch           | 1         | 1.92%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 1.92%   |
| LG Display LCD Monitor LGD042D 1920x1080 294x165mm 13.3-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 1         | 1.92%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 597x336mm 27.0-inch              | 1         | 1.92%   |
| Lenovo LCD Monitor LEN9052 1920x1080 344x194mm 15.5-inch              | 1         | 1.92%   |
| Hewlett-Packard ZR2440w HWP2956 1920x1200 520x320mm 24.0-inch         | 1         | 1.92%   |
| Hewlett-Packard E243i HPN3462 1920x1200 518x324mm 24.1-inch           | 1         | 1.92%   |
| Goldstar ULTRAWIDE GSM5BF8 2560x1080 673x284mm 28.8-inch              | 1         | 1.92%   |
| Goldstar HDR WQHD+ GSM774D 3840x1600 879x366mm 37.5-inch              | 1         | 1.92%   |
| Goldstar FHD GSM5C85 1920x1080 597x336mm 27.0-inch                    | 1         | 1.92%   |
| Goldstar E1940 GSM4BD6 1360x768 406x229mm 18.4-inch                   | 1         | 1.92%   |
| Fujitsu Siemens P24W-7 LED FUS084F 1920x1200 518x324mm 24.1-inch      | 1         | 1.92%   |
| FL_ HDMI2K FL_2701 2560x1440 480x270mm 21.7-inch                      | 1         | 1.92%   |
| DPL HDMI DPL2700 2560x1440 597x336mm 27.0-inch                        | 1         | 1.92%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 1         | 1.92%   |
| Dell S2723HC DEL4297 1920x1080 597x336mm 27.0-inch                    | 1         | 1.92%   |
| CSOT LCD Monitor CSO1423 1920x1200 302x189mm 14.0-inch                | 1         | 1.92%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1416 1920x1080 309x173mm 13.9-inch      | 1         | 1.92%   |
| BOE NE135A1M-NY1 BOE0CB4 2880x1920 285x190mm 13.5-inch                | 1         | 1.92%   |
| BOE LCD Monitor BOE0D43 3840x2400 345x215mm 16.0-inch                 | 1         | 1.92%   |
| BOE LCD Monitor BOE0A99 2560x1600 366x229mm 17.0-inch                 | 1         | 1.92%   |
| BOE LCD Monitor BOE08E4 1600x900 382x215mm 17.3-inch                  | 1         | 1.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 21        | 42%     |
| 2560x1440 (QHD)    | 5         | 10%     |
| 1920x1200 (WUXGA)  | 5         | 10%     |
| 1366x768 (WXGA)    | 4         | 8%      |
| 1680x1050 (WSXGA+) | 2         | 4%      |
| 1600x900 (HD+)     | 2         | 4%      |
| 1440x900 (WXGA+)   | 2         | 4%      |
| 1280x1024 (SXGA)   | 2         | 4%      |
| 3840x2400          | 1         | 2%      |
| 3840x1600          | 1         | 2%      |
| 2880x1920          | 1         | 2%      |
| 2560x1600          | 1         | 2%      |
| 2560x1080          | 1         | 2%      |
| 2160x1440          | 1         | 2%      |
| 1360x768           | 1         | 2%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 27     | 8         | 15.38%  |
| 17     | 7         | 13.46%  |
| 15     | 7         | 13.46%  |
| 24     | 5         | 9.62%   |
| 13     | 5         | 9.62%   |
| 21     | 4         | 7.69%   |
| 23     | 2         | 3.85%   |
| 19     | 2         | 3.85%   |
| 16     | 2         | 3.85%   |
| 14     | 2         | 3.85%   |
| 40     | 1         | 1.92%   |
| 37     | 1         | 1.92%   |
| 31     | 1         | 1.92%   |
| 28     | 1         | 1.92%   |
| 22     | 1         | 1.92%   |
| 20     | 1         | 1.92%   |
| 18     | 1         | 1.92%   |
| 12     | 1         | 1.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 29.17%  |
| 501-600     | 13        | 27.08%  |
| 351-400     | 7         | 14.58%  |
| 401-500     | 6         | 12.5%   |
| 201-300     | 4         | 8.33%   |
| 801-900     | 2         | 4.17%   |
| 601-700     | 2         | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 29        | 60.42%  |
| 16/10 | 13        | 27.08%  |
| 5/4   | 2         | 4.17%   |
| 3/2   | 2         | 4.17%   |
| 21/9  | 2         | 4.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 8         | 15.69%  |
| 101-110        | 7         | 13.73%  |
| 81-90          | 6         | 11.76%  |
| 201-250        | 6         | 11.76%  |
| 251-300        | 5         | 9.8%    |
| 151-200        | 4         | 7.84%   |
| 121-130        | 4         | 7.84%   |
| 351-500        | 2         | 3.92%   |
| 141-150        | 2         | 3.92%   |
| 131-140        | 2         | 3.92%   |
| 111-120        | 2         | 3.92%   |
| 71-80          | 1         | 1.96%   |
| 61-70          | 1         | 1.96%   |
| 501-1000       | 1         | 1.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 18        | 36.73%  |
| 101-120       | 14        | 28.57%  |
| 121-160       | 11        | 22.45%  |
| 161-240       | 4         | 8.16%   |
| More than 240 | 2         | 4.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 35        | 77.78%  |
| 2     | 6         | 13.33%  |
| 3     | 3         | 6.67%   |
| 0     | 1         | 2.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 24        | 37.5%   |
| Intel                                  | 23        | 35.94%  |
| Broadcom                               | 5         | 7.81%   |
| Qualcomm Atheros                       | 3         | 4.69%   |
| MediaTek                               | 3         | 4.69%   |
| Suzhou Motorcomm Electronic Technology | 1         | 1.56%   |
| Realtek                                | 1         | 1.56%   |
| Ralink Technology                      | 1         | 1.56%   |
| Ralink                                 | 1         | 1.56%   |
| Ericsson Business Mobile Networks      | 1         | 1.56%   |
| D-Link System                          | 1         | 1.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 12        | 13.79%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 5.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 4.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 4.6%    |
| Intel Wireless 8265 / 8275                                              | 3         | 3.45%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 2.3%    |
| Realtek RTL8125 2.5GbE Controller                                       | 2         | 2.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.3%    |
| Intel Wireless 7265                                                     | 2         | 2.3%    |
| Intel I211 Gigabit Network Connection                                   | 2         | 2.3%    |
| Intel Ethernet Connection (16) I219-LM                                  | 2         | 2.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 2.3%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                       | 2         | 2.3%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter            | 2         | 2.3%    |
| Suzhou Motorcomm Electronic YT6801 Gigabit Ethernet Controller          | 1         | 1.15%   |
| Realtek USB 10/100/1G/2.5G/5G LAN                                       | 1         | 1.15%   |
| Realtek RTL8852BE-VT PCIe 802.11ax Wireless Network Controller          | 1         | 1.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.15%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.15%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.15%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.15%   |
| Realtek 802.11ac WLAN Adapter                                           | 1         | 1.15%   |
| Realtek 802.11ax WLAN Adapter                                           | 1         | 1.15%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 1.15%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 1.15%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.15%   |
| MediaTek Wi-Fi 6 MT7920 Wireless Network Adapter                        | 1         | 1.15%   |
| MediaTek MT7925 (RZ717) Wi-Fi 7 160MHz                                  | 1         | 1.15%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]    | 1         | 1.15%   |
| Intel Wireless 7260                                                     | 1         | 1.15%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2         | 1         | 1.15%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 1         | 1.15%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.15%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 1.15%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.15%   |
| Intel Ethernet Controller I226-LM                                       | 1         | 1.15%   |
| Intel Ethernet Connection (4) I219-V                                    | 1         | 1.15%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 45.24%  |
| Realtek Semiconductor | 10        | 23.81%  |
| Qualcomm Atheros      | 3         | 7.14%   |
| MediaTek              | 3         | 7.14%   |
| Broadcom              | 3         | 7.14%   |
| Realtek               | 1         | 2.38%   |
| Ralink Technology     | 1         | 2.38%   |
| Ralink                | 1         | 2.38%   |
| D-Link System         | 1         | 2.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 3         | 7.14%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 4.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 4.76%   |
| Intel Wireless 7265                                                     | 2         | 4.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 4.76%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter            | 2         | 4.76%   |
| Realtek RTL8852BE-VT PCIe 802.11ax Wireless Network Controller          | 1         | 2.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.38%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 2.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 2.38%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 2.38%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 2.38%   |
| Realtek 802.11ac WLAN Adapter                                           | 1         | 2.38%   |
| Realtek 802.11ax WLAN Adapter                                           | 1         | 2.38%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 2.38%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 2.38%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 2.38%   |
| MediaTek Wi-Fi 6 MT7920 Wireless Network Adapter                        | 1         | 2.38%   |
| MediaTek MT7925 (RZ717) Wi-Fi 7 160MHz                                  | 1         | 2.38%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]    | 1         | 2.38%   |
| Intel Wireless 7260                                                     | 1         | 2.38%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2         | 1         | 2.38%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 1         | 2.38%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 2.38%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 2.38%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 2.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 2.38%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 2.38%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 2.38%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 2.38%   |
| Intel Alder Lake-N PCH CNVi WiFi                                        | 1         | 2.38%   |
| Intel 700 Series Chipset CNVi WiFi                                      | 1         | 2.38%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]       | 1         | 2.38%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 2.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 22        | 51.16%  |
| Intel                                  | 15        | 34.88%  |
| Broadcom                               | 4         | 9.3%    |
| Suzhou Motorcomm Electronic Technology | 1         | 2.33%   |
| Qualcomm Atheros                       | 1         | 2.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12        | 27.27%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 11.36%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 9.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 9.09%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 4.55%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 4.55%   |
| Intel Ethernet Connection (16) I219-LM                                 | 2         | 4.55%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 2         | 4.55%   |
| Suzhou Motorcomm Electronic YT6801 Gigabit Ethernet Controller         | 1         | 2.27%   |
| Realtek USB 10/100/1G/2.5G/5G LAN                                      | 1         | 2.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 2.27%   |
| Intel Ethernet Controller I226-LM                                      | 1         | 2.27%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 2.27%   |
| Intel Ethernet Connection (2) I219-V                                   | 1         | 2.27%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 2.27%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1         | 2.27%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 2.27%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 2.27%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                        | 1         | 2.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 40        | 50%     |
| WiFi     | 39        | 48.75%  |
| Modem    | 1         | 1.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 24        | 50%     |
| Ethernet | 24        | 50%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 29        | 64.44%  |
| 1     | 15        | 33.33%  |
| 3     | 1         | 2.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 30        | 66.67%  |
| Yes  | 15        | 33.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 15        | 48.39%  |
| Realtek Semiconductor   | 3         | 9.68%   |
| MediaTek                | 3         | 9.68%   |
| Toshiba                 | 2         | 6.45%   |
| IMC Networks            | 2         | 6.45%   |
| Broadcom                | 2         | 6.45%   |
| Apple                   | 2         | 6.45%   |
| Mercucys                | 1         | 3.23%   |
| Cambridge Silicon Radio | 1         | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 19.35%  |
| Intel AX201 Bluetooth                               | 4         | 12.9%   |
| Realtek Bluetooth Radio                             | 3         | 9.68%   |
| MediaTek Wireless_Device                            | 3         | 9.68%   |
| Intel Bluetooth Device                              | 2         | 6.45%   |
| IMC Networks Bluetooth Radio                        | 2         | 6.45%   |
| Apple Bluetooth Host Controller                     | 2         | 6.45%   |
| Toshiba RT Bluetooth Radio                          | 1         | 3.23%   |
| Toshiba BCM43142A0                                  | 1         | 3.23%   |
| Mercucys Mercusys MA530 Adapter                     | 1         | 3.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 3.23%   |
| Intel AX210 Bluetooth                               | 1         | 3.23%   |
| Intel AX200 Bluetooth                               | 1         | 3.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.23%   |
| Broadcom HP Portable SoftSailing                    | 1         | 3.23%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 34        | 50.75%  |
| AMD                 | 14        | 20.9%   |
| Nvidia              | 10        | 14.93%  |
| RODE Microphones    | 1         | 1.49%   |
| Midiplus            | 1         | 1.49%   |
| MAG Technology      | 1         | 1.49%   |
| M-Audio             | 1         | 1.49%   |
| Logitech            | 1         | 1.49%   |
| GYROCOM C&C         | 1         | 1.49%   |
| DSEA A/S            | 1         | 1.49%   |
| Creative Labs       | 1         | 1.49%   |
| C-Media Electronics | 1         | 1.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 6         | 7.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 4.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 4.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 3.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 3.7%    |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 3         | 3.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.47%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.47%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.47%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 2.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 2.47%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.47%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 2.47%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 2.47%   |
| AMD Radeon High Definition Audio Controller                                | 2         | 2.47%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2         | 2.47%   |
| RODE Microphones RODE AI-1                                                 | 1         | 1.23%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.23%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 1.23%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.23%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.23%   |
| Nvidia GB206 High Definition Audio Controller                              | 1         | 1.23%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 1.23%   |
| Nvidia AD107 High Definition Audio Controller                              | 1         | 1.23%   |
| Midiplus Midi Plus                                                         | 1         | 1.23%   |
| MAG Technology ARC AMP DAC                                                 | 1         | 1.23%   |
| M-Audio M-Audio Fast Track MKII                                            | 1         | 1.23%   |
| Logitech V20 portable speakers (USB powered)                               | 1         | 1.23%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.23%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.23%   |
| Intel Raptor Lake High Definition Audio Controller                         | 1         | 1.23%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.23%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.23%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.23%   |
| Intel Arrow Lake cAVS                                                      | 1         | 1.23%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                    | 1         | 1.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 9         | 29.03%  |
| Samsung Electronics | 6         | 19.35%  |
| Unknown             | 3         | 9.68%   |
| A-DATA Technology   | 3         | 9.68%   |
| Kingston            | 2         | 6.45%   |
| Crucial             | 2         | 6.45%   |
| Unknown             | 2         | 6.45%   |
| Ramaxel Technology  | 1         | 3.23%   |
| Micron Technology   | 1         | 3.23%   |
| G.Skill             | 1         | 3.23%   |
| Corsair             | 1         | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Unknown                                                       | 2         | 5.71%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                   | 1         | 2.86%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                      | 1         | 2.86%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                      | 1         | 2.86%   |
| Unknown RAM DDR4 NB 16G 2666 16384MB SODIMM DDR4 2667MT/s     | 1         | 2.86%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 2.86%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 2.86%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM 1334MT/s             | 1         | 2.86%   |
| SK hynix RAM HMCGY8MGBSB212N 48GB SODIMM DDR5 5600MT/s        | 1         | 2.86%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s        | 1         | 2.86%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 2.86%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 1         | 2.86%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 1         | 2.86%   |
| SK hynix RAM H58G66CK8BX147 16GB Row Of Chips LPDDR5 8533MT/s | 1         | 2.86%   |
| Samsung RAM Module 4GB DIMM DDR3 1333MT/s                     | 1         | 2.86%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s         | 1         | 2.86%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s         | 1         | 2.86%   |
| Samsung RAM M471B1G73DH0-YK0 8GB SODIMM DDR3 1600MT/s         | 1         | 2.86%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s        | 1         | 2.86%   |
| Samsung RAM M471A1G44CB0-CWE 8GB Row Of Chips DDR4 3200MT/s   | 1         | 2.86%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s   | 1         | 2.86%   |
| Ramaxel RAM RMR5030EF68F9W1600 4GB DIMM DDR3 1600MT/s         | 1         | 2.86%   |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s         | 1         | 2.86%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s         | 1         | 2.86%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1333MT/s         | 1         | 2.86%   |
| G.Skill RAM F4-3600C16-32GTRS 32GB DIMM DDR4 3600MT/s         | 1         | 2.86%   |
| Crucial RAM ST51264BA1339.16FM 4GB DIMM DDR3 1333MT/s         | 1         | 2.86%   |
| Crucial RAM CT8G4DFS824A.C8FR 8GB DIMM DDR4 2400MT/s          | 1         | 2.86%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s        | 1         | 2.86%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s                   | 1         | 2.86%   |
| A-DATA RAM DDR4 3000 2OZ 8GB DIMM DDR4 3000MT/s               | 1         | 2.86%   |
| A-DATA RAM CBDAD5S560016G-BAD 16GB SODIMM DDR5 5600MT/s       | 1         | 2.86%   |
| A-DATA RAM AX4U32008G16A-DR30 8GB DIMM DDR4 2933MT/s          | 1         | 2.86%   |
| A-DATA RAM AD5S560032G-SFW 32GB SODIMM DDR5 5600MT/s          | 1         | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 14        | 46.67%  |
| DDR3   | 10        | 33.33%  |
| DDR5   | 4         | 13.33%  |
| LPDDR5 | 1         | 3.33%   |
| DDR    | 1         | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 18        | 60%     |
| DIMM         | 9         | 30%     |
| Row Of Chips | 3         | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 11        | 34.38%  |
| 4096  | 9         | 28.13%  |
| 16384 | 7         | 21.88%  |
| 32768 | 3         | 9.38%   |
| 49152 | 1         | 3.13%   |
| 2048  | 1         | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 8         | 23.53%  |
| 3200  | 5         | 14.71%  |
| 2667  | 4         | 11.76%  |
| 5600  | 3         | 8.82%   |
| 2400  | 3         | 8.82%   |
| 1333  | 3         | 8.82%   |
| 3600  | 2         | 5.88%   |
| 8533  | 1         | 2.94%   |
| 4800  | 1         | 2.94%   |
| 3800  | 1         | 2.94%   |
| 3000  | 1         | 2.94%   |
| 2933  | 1         | 2.94%   |
| 1334  | 1         | 2.94%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)

![Printer Vendor](./images/line_chart/printer_vendor.svg)

| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)

![Printer Model](./images/line_chart/printer_model.svg)

| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| HP OfficeJet 3830 series | 1         | 100%    |

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
| Chicony Electronics           | 11        | 31.43%  |
| Logitech                      | 6         | 17.14%  |
| IMC Networks                  | 4         | 11.43%  |
| Sunplus Innovation Technology | 2         | 5.71%   |
| Apple                         | 2         | 5.71%   |
| Samsung Electronics           | 1         | 2.86%   |
| Ricoh                         | 1         | 2.86%   |
| Primax Electronics            | 1         | 2.86%   |
| Microdia                      | 1         | 2.86%   |
| Luxvisions Innotech Limited   | 1         | 2.86%   |
| Genesys Logic                 | 1         | 2.86%   |
| Generalplus Technology        | 1         | 2.86%   |
| Framework                     | 1         | 2.86%   |
| Cubeternet                    | 1         | 2.86%   |
| Bison Electronics             | 1         | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                        | 3         | 8.57%   |
| Chicony TOSHIBA Web Camera - HD                       | 3         | 8.57%   |
| Logitech Webcam C270                                  | 2         | 5.71%   |
| Apple FaceTime HD Camera (Built-in)                   | 2         | 5.71%   |
| Sunplus Laptop Integrated WebCam HD                   | 1         | 2.86%   |
| Sunplus Integrated_Webcam_FHD                         | 1         | 2.86%   |
| Samsung Galaxy series, misc. (MTP mode)               | 1         | 2.86%   |
| Ricoh Dell Laptop Integrated Webcam                   | 1         | 2.86%   |
| Primax HP HD Webcam [Fixed]                           | 1         | 2.86%   |
| Microdia USB 2.0 Camera                               | 1         | 2.86%   |
| Luxvisions Innotech Limited HP True Vision FHD Camera | 1         | 2.86%   |
| Logitech Webcam C250                                  | 1         | 2.86%   |
| Logitech Webcam C170                                  | 1         | 2.86%   |
| Logitech QuickCam Pro 5000                            | 1         | 2.86%   |
| Logitech BRIO Ultra HD Webcam                         | 1         | 2.86%   |
| IMC Networks USB2.0 HD UVC WebCam                     | 1         | 2.86%   |
| Genesys Logic Camera                                  | 1         | 2.86%   |
| Generalplus 808 Camera #9 (web-cam mode)              | 1         | 2.86%   |
| Framework Laptop Webcam Module (2nd Gen)              | 1         | 2.86%   |
| Cubeternet USB2.0 Camera                              | 1         | 2.86%   |
| Chicony Lenovo Integrated Camera (0.3MP)              | 1         | 2.86%   |
| Chicony Integrated Camera                             | 1         | 2.86%   |
| Chicony HP Laptop Integrated Webcam [2 MP Fixed]      | 1         | 2.86%   |
| Chicony HP HD Webcam [Fixed]                          | 1         | 2.86%   |
| Chicony HP HD Camera                                  | 1         | 2.86%   |
| Chicony HD WebCam                                     | 1         | 2.86%   |
| Chicony FHD Webcam                                    | 1         | 2.86%   |
| Chicony Camera                                        | 1         | 2.86%   |
| Bison SunplusIT Integrated Camera                     | 1         | 2.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 1         | 50%     |
| LighTuning Technology | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Synaptics UWP WBDI Device                   | 1         | 50%     |
| LighTuning EgisTec Touch Fingerprint Sensor | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./images/line_chart/chipcard_vendor.svg)

| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)

![Chipcard Model](./images/line_chart/chipcard_model.svg)

| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                              | 1         | 50%     |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard) | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 36        | 80%     |
| 1     | 7         | 15.56%  |
| 2     | 2         | 4.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Graphics card      | 3         | 27.27%  |
| Net/wireless       | 2         | 18.18%  |
| Fingerprint reader | 2         | 18.18%  |
| Chipcard           | 2         | 18.18%  |
| Net/ethernet       | 1         | 9.09%   |
| Bluetooth          | 1         | 9.09%   |

