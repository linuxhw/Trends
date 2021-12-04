Endless Hardware Trends
-----------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Endless users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Endless/Desktop/README.md) and [notebooks](/Dist/Endless/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

Period: Nov, 2021.

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

| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Endless 3.9.5         | 32        | 59.26%  |
| Endless 4.0.0         | 6         | 11.11%  |
| Endless 3.9.6         | 5         | 9.26%   |
| Endless 3.9.1         | 3         | 5.56%   |
| Endless 3.9.4         | 2         | 3.7%    |
| Endless 3.8.0         | 2         | 3.7%    |
| Endless 3.9.3-nexthw1 | 1         | 1.85%   |
| Endless 3.8.3-nexthw1 | 1         | 1.85%   |
| Endless 3.7.6         | 1         | 1.85%   |
| Endless 3.7.4         | 1         | 1.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Endless | 54        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.8.0-14-generic  | 42        | 77.78%  |
| 5.11.0-35-generic | 6         | 11.11%  |
| 5.4.0-19-generic  | 2         | 3.7%    |
| 5.6.0-7-generic   | 1         | 1.85%   |
| 5.3.0-23-generic  | 1         | 1.85%   |
| 5.3.0-19-generic  | 1         | 1.85%   |
| 5.11.0-12-generic | 1         | 1.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8.0   | 42        | 77.78%  |
| 5.11.0  | 7         | 12.96%  |
| 5.4.0   | 2         | 3.7%    |
| 5.3.0   | 2         | 3.7%    |
| 5.6.0   | 1         | 1.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8     | 42        | 77.78%  |
| 5.11    | 7         | 12.96%  |
| 5.4     | 2         | 3.7%    |
| 5.3     | 2         | 3.7%    |
| 5.6     | 1         | 1.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 54        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name  | Computers | Percent |
|-------|-----------|---------|
| GNOME | 54        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 54        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 54        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang        | Computers | Percent |
|-------------|-----------|---------|
| pt_BR       | 18        | 33.33%  |
| en_US       | 13        | 24.07%  |
| ru_RU.UTF_8 | 4         | 7.41%   |
| ro_RO       | 2         | 3.7%    |
| it_IT       | 2         | 3.7%    |
| hu_HU       | 2         | 3.7%    |
| fr_FR       | 2         | 3.7%    |
| es_ES       | 2         | 3.7%    |
| sr_RS@latin | 1         | 1.85%   |
| sl_SI       | 1         | 1.85%   |
| sk_SK       | 1         | 1.85%   |
| ru_RU       | 1         | 1.85%   |
| pt_PT       | 1         | 1.85%   |
| id_ID       | 1         | 1.85%   |
| es_MX       | 1         | 1.85%   |
| en_IE       | 1         | 1.85%   |
| de_DE       | 1         | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 41        | 75.93%  |
| BIOS | 13        | 24.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 53        | 98.15%  |
| Tmpfs | 1         | 1.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 54        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 54        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 54        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| Acer             | 21        | 38.89%  |
| ASUSTek Computer | 16        | 29.63%  |
| Hewlett-Packard  | 4         | 7.41%   |
| Sony             | 2         | 3.7%    |
| MSI              | 2         | 3.7%    |
| Foxconn          | 2         | 3.7%    |
| Dell             | 2         | 3.7%    |
| Toshiba          | 1         | 1.85%   |
| Semp Toshiba     | 1         | 1.85%   |
| Packard Bell     | 1         | 1.85%   |
| IP3 Tech         | 1         | 1.85%   |
| ASRock           | 1         | 1.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Acer Nitro AN515-44                       | 6         | 11.11%  |
| Acer Nitro AN515-54                       | 4         | 7.41%   |
| Acer Aspire A315-53                       | 2         | 3.7%    |
| Toshiba Satellite Pro C850-1D5            | 1         | 1.85%   |
| Sony VPCYB1S1E                            | 1         | 1.85%   |
| Sony VPCCB35FG                            | 1         | 1.85%   |
| Semp Toshiba IS 1462B                     | 1         | 1.85%   |
| Packard Bell EasyNote TN36                | 1         | 1.85%   |
| MSI VR610                                 | 1         | 1.85%   |
| MSI MS-7C89                               | 1         | 1.85%   |
| IP3 Tech Endless                          | 1         | 1.85%   |
| HP Pavilion dv7                           | 1         | 1.85%   |
| HP ENVY 15                                | 1         | 1.85%   |
| HP 550-153w                               | 1         | 1.85%   |
| HP 255 G8 Notebook PC                     | 1         | 1.85%   |
| Foxconn Pro 3330 MT                       | 1         | 1.85%   |
| Foxconn G41MXE/G41MXE-K                   | 1         | 1.85%   |
| Dell Latitude E7440                       | 1         | 1.85%   |
| Dell Inspiron N5110                       | 1         | 1.85%   |
| ASUS X541UAK                              | 1         | 1.85%   |
| ASUS X540NA                               | 1         | 1.85%   |
| ASUS X450CP                               | 1         | 1.85%   |
| ASUS X442UAR                              | 1         | 1.85%   |
| ASUS VivoBook_ASUSLaptop X712FA_X712FA    | 1         | 1.85%   |
| ASUS VivoBook_ASUSLaptop X513EA_K513EA    | 1         | 1.85%   |
| ASUS VivoBook_ASUSLaptop X513EAN_X513EA   | 1         | 1.85%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA    | 1         | 1.85%   |
| ASUS VivoBook_ASUS Laptop E406MA_E406MA   | 1         | 1.85%   |
| ASUS VivoBook E14 E402YA_E402YA           | 1         | 1.85%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR      | 1         | 1.85%   |
| ASUS VivoBook 15_ASUS Laptop X540BA       | 1         | 1.85%   |
| ASUS PRIME H310M-E R2.0/BR                | 1         | 1.85%   |
| ASUS ASUS Vivo AIO V241EA_V241EA          | 1         | 1.85%   |
| ASUS ASUS EXPERTBOOK B1400CEPEY_B1400CEPE | 1         | 1.85%   |
| ASUS ASUS D300TA_S300MA                   | 1         | 1.85%   |
| ASRock A88M-G                             | 1         | 1.85%   |
| Acer TravelMate P253                      | 1         | 1.85%   |
| Acer Nitro AN517-51                       | 1         | 1.85%   |
| Acer Nitro AN515-43                       | 1         | 1.85%   |
| Acer Aspire ES1-533                       | 1         | 1.85%   |
| Acer Aspire C22-865                       | 1         | 1.85%   |
| Acer Aspire A515-54G                      | 1         | 1.85%   |
| Acer Aspire A515-54                       | 1         | 1.85%   |
| Acer Aspire A315-34                       | 1         | 1.85%   |
| Acer Aspire 4745                          | 1         | 1.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Nitro            | 12        | 22.22%  |
| ASUS VivoBook         | 8         | 14.81%  |
| Acer Aspire           | 8         | 14.81%  |
| ASUS ASUS             | 3         | 5.56%   |
| Toshiba Satellite     | 1         | 1.85%   |
| Sony VPCYB1S1E        | 1         | 1.85%   |
| Sony VPCCB35FG        | 1         | 1.85%   |
| Semp Toshiba IS       | 1         | 1.85%   |
| Packard Bell EasyNote | 1         | 1.85%   |
| MSI VR610             | 1         | 1.85%   |
| MSI MS-7C89           | 1         | 1.85%   |
| IP3 Tech Endless      | 1         | 1.85%   |
| HP Pavilion           | 1         | 1.85%   |
| HP ENVY               | 1         | 1.85%   |
| HP 550-153w           | 1         | 1.85%   |
| HP 255                | 1         | 1.85%   |
| Foxconn Pro           | 1         | 1.85%   |
| Foxconn G41MXE        | 1         | 1.85%   |
| Dell Latitude         | 1         | 1.85%   |
| Dell Inspiron         | 1         | 1.85%   |
| ASUS X541UAK          | 1         | 1.85%   |
| ASUS X540NA           | 1         | 1.85%   |
| ASUS X450CP           | 1         | 1.85%   |
| ASUS X442UAR          | 1         | 1.85%   |
| ASUS PRIME            | 1         | 1.85%   |
| ASRock A88M-G         | 1         | 1.85%   |
| Acer TravelMate       | 1         | 1.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 15        | 27.78%  |
| 2021 | 10        | 18.52%  |
| 2019 | 9         | 16.67%  |
| 2018 | 3         | 5.56%   |
| 2011 | 3         | 5.56%   |
| 2017 | 2         | 3.7%    |
| 2013 | 2         | 3.7%    |
| 2012 | 2         | 3.7%    |
| 2010 | 2         | 3.7%    |
| 2009 | 2         | 3.7%    |
| 2016 | 1         | 1.85%   |
| 2015 | 1         | 1.85%   |
| 2014 | 1         | 1.85%   |
| 2007 | 1         | 1.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 44        | 81.48%  |
| Desktop    | 7         | 12.96%  |
| All in one | 2         | 3.7%    |
| Mini pc    | 1         | 1.85%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 39        | 72.22%  |
| Enabled  | 15        | 27.78%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 54        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 21        | 38.89%  |
| 3.01-4.0   | 19        | 35.19%  |
| 8.01-16.0  | 8         | 14.81%  |
| 1.01-2.0   | 3         | 5.56%   |
| 16.01-24.0 | 2         | 3.7%    |
| 24.01-32.0 | 1         | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 26        | 48.15%  |
| 2.01-3.0 | 14        | 25.93%  |
| 0.51-1.0 | 8         | 14.81%  |
| 3.01-4.0 | 5         | 9.26%   |
| 4.01-8.0 | 1         | 1.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 42        | 77.78%  |
| 2      | 12        | 22.22%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 79.63%  |
| Yes       | 11        | 20.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 85.19%  |
| No        | 8         | 14.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 94.44%  |
| No        | 3         | 5.56%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 79.63%  |
| No        | 11        | 20.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| Brazil       | 20        | 37.04%  |
| USA          | 4         | 7.41%   |
| Romania      | 4         | 7.41%   |
| Russia       | 3         | 5.56%   |
| Spain        | 2         | 3.7%    |
| South Africa | 2         | 3.7%    |
| Italy        | 2         | 3.7%    |
| Hungary      | 2         | 3.7%    |
| Belarus      | 2         | 3.7%    |
| UK           | 1         | 1.85%   |
| Tunisia      | 1         | 1.85%   |
| Slovenia     | 1         | 1.85%   |
| Slovakia     | 1         | 1.85%   |
| Serbia       | 1         | 1.85%   |
| Portugal     | 1         | 1.85%   |
| Mexico       | 1         | 1.85%   |
| Ireland      | 1         | 1.85%   |
| Indonesia    | 1         | 1.85%   |
| Guadeloupe   | 1         | 1.85%   |
| Germany      | 1         | 1.85%   |
| Egypt        | 1         | 1.85%   |
| Bangladesh   | 1         | 1.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| S??o Paulo               | 3         | 5.56%   |
| Moscow                   | 3         | 5.56%   |
| Bucharest                | 3         | 5.56%   |
| Florian??polis           | 2         | 3.7%    |
| Bucyrus                  | 2         | 3.7%    |
| Blumenau                 | 2         | 3.7%    |
| Tunis                    | 1         | 1.85%   |
| Tuban                    | 1         | 1.85%   |
| Shannon                  | 1         | 1.85%   |
| Sao Jose                 | 1         | 1.85%   |
| Sao Joao de Meriti       | 1         | 1.85%   |
| Santa Cruz de Tenerife   | 1         | 1.85%   |
| Sant Carles de la Rapita | 1         | 1.85%   |
| Rostock                  | 1         | 1.85%   |
| Rio de Janeiro           | 1         | 1.85%   |
| Rakamaz                  | 1         | 1.85%   |
| Porto Velho              | 1         | 1.85%   |
| Port Elizabeth           | 1         | 1.85%   |
| Paco do Lumiar           | 1         | 1.85%   |
| Oaxaca City              | 1         | 1.85%   |
| Nitra                    | 1         | 1.85%   |
| Niles                    | 1         | 1.85%   |
| Nagykallo                | 1         | 1.85%   |
| Mogilev                  | 1         | 1.85%   |
| Minsk                    | 1         | 1.85%   |
| Ljubljana                | 1         | 1.85%   |
| Lisbon                   | 1         | 1.85%   |
| Les Abymes               | 1         | 1.85%   |
| Lauria                   | 1         | 1.85%   |
| Lagoa Santa              | 1         | 1.85%   |
| Johannesburg             | 1         | 1.85%   |
| Jessore                  | 1         | 1.85%   |
| Hackney                  | 1         | 1.85%   |
| Faenza                   | 1         | 1.85%   |
| Embu                     | 1         | 1.85%   |
| Duque de Caxias          | 1         | 1.85%   |
| Divin??polis             | 1         | 1.85%   |
| Denver                   | 1         | 1.85%   |
| Curitiba                 | 1         | 1.85%   |
| Crici??ma                | 1         | 1.85%   |
| Canoas                   | 1         | 1.85%   |
| Cairo                    | 1         | 1.85%   |
| Boninal                  | 1         | 1.85%   |
| Bocsa                    | 1         | 1.85%   |
| Belgrade                 | 1         | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 13     | 21.31%  |
| Intel               | 10        | 10     | 16.39%  |
| Sandisk             | 8         | 8      | 13.11%  |
| Kingston            | 6         | 6      | 9.84%   |
| Toshiba             | 4         | 4      | 6.56%   |
| Seagate             | 4         | 4      | 6.56%   |
| Samsung Electronics | 4         | 4      | 6.56%   |
| Unknown             | 3         | 3      | 4.92%   |
| Hitachi             | 2         | 2      | 3.28%   |
| Crucial             | 2         | 2      | 3.28%   |
| SK Hynix            | 1         | 1      | 1.64%   |
| Silicon Motion      | 1         | 1      | 1.64%   |
| HGST HTS            | 1         | 1      | 1.64%   |
| HGST                | 1         | 1      | 1.64%   |
| ADATA Technology    | 1         | 1      | 1.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Sandisk NVMe SSD Drive 512GB          | 8         | 13.11%  |
| WDC WD10SPZX-21Z10T0 1TB              | 6         | 9.84%   |
| Intel NVMe SSD Drive 512GB            | 6         | 9.84%   |
| Unknown MMC Card  64GB                | 2         | 3.28%   |
| Toshiba MQ04ABF100 1TB                | 2         | 3.28%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 3.28%   |
| Kingston SA400S37120G 120GB SSD       | 2         | 3.28%   |
| Intel NVMe SSD Drive 256GB            | 2         | 3.28%   |
| Intel NVMe SSD Drive 128GB            | 2         | 3.28%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1.64%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 1.64%   |
| WDC WD5000LPCX-21VHAT0 500GB          | 1         | 1.64%   |
| WDC WD5000AVDS-63U7B1 500GB           | 1         | 1.64%   |
| WDC WD3200BEVT-22ZCT0 320GB           | 1         | 1.64%   |
| WDC WD2500BEVS-75UST0 250GB           | 1         | 1.64%   |
| WDC WD1600BEVS-22RST0 160GB           | 1         | 1.64%   |
| Unknown MMC Card  16GB                | 1         | 1.64%   |
| Toshiba THNSFJ256GCSU 256GB SSD       | 1         | 1.64%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1.64%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD | 1         | 1.64%   |
| Silicon Motion NVMe SSD Drive 256GB   | 1         | 1.64%   |
| Seagate ST2000LX001-1RG174 2TB        | 1         | 1.64%   |
| Seagate ST2000LM007-1R8174 2TB        | 1         | 1.64%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1.64%   |
| Samsung NVMe SSD Drive 256GB          | 1         | 1.64%   |
| Samsung HM321HI 320GB                 | 1         | 1.64%   |
| Samsung HM160HI 160GB                 | 1         | 1.64%   |
| Samsung HD103SI 1TB                   | 1         | 1.64%   |
| Kingston RBUSC180DS37256GJ 256GB SSD  | 1         | 1.64%   |
| Kingston NVMe SSD Drive 512GB         | 1         | 1.64%   |
| Hitachi HTS545050B9A300 500GB         | 1         | 1.64%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1.64%   |
| HGST HTS541010B7E610 1TB              | 1         | 1.64%   |
| HGST HTS 541075A9E680 752GB           | 1         | 1.64%   |
| Crucial CT240BX500SSD1 240GB          | 1         | 1.64%   |
| Crucial CT120BX500SSD1 120GB          | 1         | 1.64%   |
| ADATA NVMe SSD Drive 128GB            | 1         | 1.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 11     | 44%     |
| Seagate             | 4         | 4      | 16%     |
| Toshiba             | 3         | 3      | 12%     |
| Samsung Electronics | 3         | 3      | 12%     |
| Hitachi             | 2         | 2      | 8%      |
| HGST HTS            | 1         | 1      | 4%      |
| HGST                | 1         | 1      | 4%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Kingston | 5         | 5      | 45.45%  |
| WDC      | 2         | 2      | 18.18%  |
| Crucial  | 2         | 2      | 18.18%  |
| Toshiba  | 1         | 1      | 9.09%   |
| SK Hynix | 1         | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 25     | 40%     |
| NVMe | 22        | 22     | 36.67%  |
| SSD  | 11        | 11     | 18.33%  |
| MMC  | 3         | 3      | 5%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 34        | 35     | 56.67%  |
| NVMe | 22        | 22     | 36.67%  |
| MMC  | 3         | 3      | 5%      |
| SAS  | 1         | 1      | 1.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 21     | 57.14%  |
| 0.51-1.0   | 13        | 13     | 37.14%  |
| 1.01-2.0   | 2         | 2      | 5.71%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 18        | 33.33%  |
| 251-500    | 17        | 31.48%  |
| 501-1000   | 13        | 24.07%  |
| 1001-2000  | 2         | 3.7%    |
| 1-20       | 2         | 3.7%    |
| 51-100     | 2         | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 21-50    | 23        | 42.59%  |
| 1-20     | 15        | 27.78%  |
| 51-100   | 8         | 14.81%  |
| 101-250  | 5         | 9.26%   |
| 251-500  | 2         | 3.7%    |
| 501-1000 | 1         | 1.85%   |

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

![Drive Status](./images/pie_chart/drive_status.svg)

![Drive Status](./images/line_chart/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 54        | 61     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 41        | 63.08%  |
| AMD                         | 12        | 18.46%  |
| Sandisk                     | 8         | 12.31%  |
| Silicon Motion              | 1         | 1.54%   |
| Samsung Electronics         | 1         | 1.54%   |
| Kingston Technology Company | 1         | 1.54%   |
| ADATA Technology            | 1         | 1.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 12.2%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 10.98%  |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 7         | 8.54%   |
| Intel PROSet/Wireless WiFi Software extension                                  | 7         | 8.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 7.32%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 4.88%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 4         | 4.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 4.88%   |
| Intel SSD 660P Series                                                          | 3         | 3.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 3         | 3.66%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 2.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 2.44%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 2.44%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 1.22%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 1.22%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.22%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.22%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 1.22%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 1.22%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 1.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.22%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1         | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.22%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 1         | 1.22%   |
| AMD SB600 IDE                                                                  | 1         | 1.22%   |
| AMD FCH IDE Controller                                                         | 1         | 1.22%   |
| ADATA Non-Volatile memory controller                                           | 1         | 1.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 49        | 60.49%  |
| NVMe | 22        | 27.16%  |
| RAID | 6         | 7.41%   |
| IDE  | 4         | 4.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 41        | 75.93%  |
| AMD    | 13        | 24.07%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 4600H with Radeon Graphics        | 4         | 7.41%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 5.56%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 5.56%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 2         | 3.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 3.7%    |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 3.7%    |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 3.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 3.7%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 1.85%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 1.85%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 1         | 1.85%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 1.85%   |
| Intel Pentium CPU 4417U @ 2.30GHz             | 1         | 1.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.85%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.85%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 1         | 1.85%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 1.85%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.85%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.85%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.85%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 1         | 1.85%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.85%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.85%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 1.85%   |
| Intel Core i3-9100F CPU @ 3.60GHz             | 1         | 1.85%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 1.85%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.85%   |
| Intel Core i3-4370 CPU @ 3.80GHz              | 1         | 1.85%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 1         | 1.85%   |
| Intel Celeron N4000C CPU @ 1.10GHz            | 1         | 1.85%   |
| Intel Celeron G5905 CPU @ 3.50GHz             | 1         | 1.85%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 1.85%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.85%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 1.85%   |
| AMD E2-7015 APU with AMD Radeon R2 Graphics   | 1         | 1.85%   |
| AMD E-350 Processor                           | 1         | 1.85%   |
| AMD Athlon Silver 3050U with Radeon Graphics  | 1         | 1.85%   |
| AMD Athlon 64 X2 Dual-Core Processor TK-55    | 1         | 1.85%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 1         | 1.85%   |
| AMD A10-5800K APU with Radeon HD Graphics     | 1         | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 13        | 24.07%  |
| Intel Core i3           | 9         | 16.67%  |
| Intel Core i7           | 5         | 9.26%   |
| Other                   | 4         | 7.41%   |
| AMD Ryzen 5             | 4         | 7.41%   |
| Intel Pentium           | 3         | 5.56%   |
| Intel Celeron           | 3         | 5.56%   |
| AMD Ryzen 7             | 3         | 5.56%   |
| Intel Pentium Dual-Core | 2         | 3.7%    |
| Intel Pentium Silver    | 1         | 1.85%   |
| Intel Pentium Dual      | 1         | 1.85%   |
| AMD E2                  | 1         | 1.85%   |
| AMD E                   | 1         | 1.85%   |
| AMD Athlon 64 X2        | 1         | 1.85%   |
| AMD Athlon              | 1         | 1.85%   |
| AMD A4                  | 1         | 1.85%   |
| AMD A10                 | 1         | 1.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 27        | 50%     |
| 4      | 19        | 35.19%  |
| 6      | 6         | 11.11%  |
| 8      | 2         | 3.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 54        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 38        | 70.37%  |
| 1      | 16        | 29.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 54        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x08600103 | 6         | 11.11%  |
| 0x806c1    | 4         | 7.41%   |
| 0x306a9    | 4         | 7.41%   |
| 0x906ed    | 3         | 5.56%   |
| 0x906ea    | 3         | 5.56%   |
| 0x506c9    | 3         | 5.56%   |
| 0x206a7    | 3         | 5.56%   |
| Unknown    | 3         | 5.56%   |
| 0x806ec    | 2         | 3.7%    |
| 0x806ea    | 2         | 3.7%    |
| 0x806e9    | 2         | 3.7%    |
| 0x706a1    | 2         | 3.7%    |
| 0x1067a    | 2         | 3.7%    |
| 0x08108109 | 2         | 3.7%    |
| 0xa0653    | 1         | 1.85%   |
| 0x806eb    | 1         | 1.85%   |
| 0x706e5    | 1         | 1.85%   |
| 0x6fd      | 1         | 1.85%   |
| 0x406e3    | 1         | 1.85%   |
| 0x40651    | 1         | 1.85%   |
| 0x306c3    | 1         | 1.85%   |
| 0x20655    | 1         | 1.85%   |
| 0x106e5    | 1         | 1.85%   |
| 0x07030106 | 1         | 1.85%   |
| 0x06006705 | 1         | 1.85%   |
| 0x06001119 | 1         | 1.85%   |
| 0x05000029 | 1         | 1.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 25.93%  |
| Zen 2         | 6         | 11.11%  |
| TigerLake     | 4         | 7.41%   |
| IvyBridge     | 4         | 7.41%   |
| SandyBridge   | 3         | 5.56%   |
| Goldmont      | 3         | 5.56%   |
| Zen+          | 2         | 3.7%    |
| Penryn        | 2         | 3.7%    |
| Haswell       | 2         | 3.7%    |
| Goldmont plus | 2         | 3.7%    |
| CometLake     | 2         | 3.7%    |
| Westmere      | 1         | 1.85%   |
| Skylake       | 1         | 1.85%   |
| Puma          | 1         | 1.85%   |
| Piledriver    | 1         | 1.85%   |
| Nehalem       | 1         | 1.85%   |
| K8 Hammer     | 1         | 1.85%   |
| IceLake       | 1         | 1.85%   |
| Excavator     | 1         | 1.85%   |
| Core          | 1         | 1.85%   |
| Bobcat        | 1         | 1.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 38        | 53.52%  |
| AMD    | 18        | 25.35%  |
| Nvidia | 15        | 21.13%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                              | Computers | Percent |
|------------------------------------------------------------------------------------|-----------|---------|
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                    | 6         | 8.45%   |
| Nvidia TU117M                                                                      | 6         | 8.45%   |
| AMD Renoir                                                                         | 6         | 8.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                          | 5         | 7.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                          | 4         | 5.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                   | 4         | 5.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller          | 3         | 4.23%   |
| Intel UHD Graphics 620                                                             | 2         | 2.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                       | 2         | 2.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                               | 2         | 2.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller | 2         | 2.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]               | 2         | 2.82%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                                 | 2         | 2.82%   |
| Nvidia GP108M [GeForce MX330]                                                      | 1         | 1.41%   |
| Nvidia GP108M [GeForce MX250]                                                      | 1         | 1.41%   |
| Nvidia GK208B [GeForce GT 710]                                                     | 1         | 1.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                         | 1         | 1.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                | 1         | 1.41%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                  | 1         | 1.41%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                               | 1         | 1.41%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                             | 1         | 1.41%   |
| Intel HD Graphics 620                                                              | 1         | 1.41%   |
| Intel HD Graphics 500                                                              | 1         | 1.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                                   | 1         | 1.41%   |
| Intel GeminiLake [UHD Graphics 605]                                                | 1         | 1.41%   |
| Intel GeminiLake [UHD Graphics 600]                                                | 1         | 1.41%   |
| Intel Core Processor Integrated Graphics Controller                                | 1         | 1.41%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                           | 1         | 1.41%   |
| Intel Comet Lake UHD Graphics                                                      | 1         | 1.41%   |
| Intel 4 Series Chipset Integrated Graphics Controller                              | 1         | 1.41%   |
| AMD Wrestler [Radeon HD 6310]                                                      | 1         | 1.41%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                             | 1         | 1.41%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                           | 1         | 1.41%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                         | 1         | 1.41%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                          | 1         | 1.41%   |
| AMD Mullins [Radeon R2 Graphics]                                                   | 1         | 1.41%   |
| AMD Mars LE [Radeon HD 8530M / R5 M240]                                            | 1         | 1.41%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                           | 1         | 1.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 28        | 51.85%  |
| 1 x AMD        | 8         | 14.81%  |
| Intel + Nvidia | 7         | 12.96%  |
| AMD + Nvidia   | 7         | 12.96%  |
| Intel + AMD    | 3         | 5.56%   |
| 1 x Nvidia     | 1         | 1.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 39        | 72.22%  |
| Proprietary | 15        | 27.78%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 64.81%  |
| 0.01-0.5   | 11        | 20.37%  |
| 0.51-1.0   | 4         | 7.41%   |
| 7.01-8.0   | 2         | 3.7%    |
| 3.01-4.0   | 1         | 1.85%   |
| 1.01-2.0   | 1         | 1.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 10        | 18.52%  |
| Samsung Electronics     | 8         | 14.81%  |
| Chimei Innolux          | 7         | 12.96%  |
| AU Optronics            | 7         | 12.96%  |
| PANDA                   | 6         | 11.11%  |
| LG Display              | 5         | 9.26%   |
| Chi Mei Optoelectronics | 2         | 3.7%    |
| SAC                     | 1         | 1.85%   |
| MTD                     | 1         | 1.85%   |
| KDC                     | 1         | 1.85%   |
| HUAWEI                  | 1         | 1.85%   |
| HSI                     | 1         | 1.85%   |
| Dell                    | 1         | 1.85%   |
| ASUSTek Computer        | 1         | 1.85%   |
| AOC                     | 1         | 1.85%   |
| Acer                    | 1         | 1.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 5         | 9.26%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                    | 3         | 5.56%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 3.7%    |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 2         | 3.7%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 2         | 3.7%    |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch        | 1         | 1.85%   |
| Samsung Electronics SyncMaster SAM047D 1920x1080 410x230mm 18.5-inch     | 1         | 1.85%   |
| Samsung Electronics S22B300 SAM08AC 1680x1050 480x270mm 21.7-inch        | 1         | 1.85%   |
| Samsung Electronics S19A10N SAM083E 1366x768 410x230mm 18.5-inch         | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC3959 1366x768 344x194mm 15.5-inch     | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC3142 1366x768 256x144mm 11.6-inch     | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SAM0C44 3840x2160 890x500mm 40.2-inch    | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SAM0900 1920x1080 700x390mm 31.5-inch    | 1         | 1.85%   |
| SAC LED MONITOR SAC2213 1600x900 477x268mm 21.5-inch                     | 1         | 1.85%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 1         | 1.85%   |
| MTD LCD Monitor MTD0001 1280x800 303x190mm 14.1-inch                     | 1         | 1.85%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 1         | 1.85%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch             | 1         | 1.85%   |
| LG Display LCD Monitor LGD0621 1920x1080 382x215mm 17.3-inch             | 1         | 1.85%   |
| LG Display LCD Monitor LGD028D 1366x768 310x174mm 14.0-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch             | 1         | 1.85%   |
| KDC LCD Monitor KDC0830 1920x1080 344x193mm 15.5-inch                    | 1         | 1.85%   |
| HUAWEI AD80HW HWV2402 1920x1080 527x296mm 23.8-inch                      | 1         | 1.85%   |
| HSI HiTV HSI0001 3840x2160 708x398mm 32.0-inch                           | 1         | 1.85%   |
| Dell S2319NX DELD0DC 1920x1080 509x286mm 23.0-inch                       | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1535 1366x768 344x193mm 15.5-inch          | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 310x170mm 13.9-inch          | 1         | 1.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 1.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 1         | 1.85%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                    | 1         | 1.85%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                    | 1         | 1.85%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 1         | 1.85%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch           | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch           | 1         | 1.85%   |
| ASUSTek Computer V241FA ASU282C 1920x1080 527x296mm 23.8-inch            | 1         | 1.85%   |
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                       | 1         | 1.85%   |
| Acer AIO LCD ACR40B0 1920x1080 476x267mm 21.5-inch                       | 1         | 1.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution      | Computers | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 28        | 52.83%  |
| 1366x768 (WXGA) | 18        | 33.96%  |
| 3840x2160 (4K)  | 3         | 5.66%   |
| 1280x800 (WXGA) | 2         | 3.77%   |
| 1600x900 (HD+)  | 1         | 1.89%   |
| 1360x768        | 1         | 1.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 31        | 57.41%  |
| 23     | 4         | 7.41%   |
| 14     | 4         | 7.41%   |
| 13     | 4         | 7.41%   |
| 21     | 2         | 3.7%    |
| 18     | 2         | 3.7%    |
| 17     | 2         | 3.7%    |
| 84     | 1         | 1.85%   |
| 34     | 1         | 1.85%   |
| 31     | 1         | 1.85%   |
| 27     | 1         | 1.85%   |
| 24     | 1         | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 39        | 72.22%  |
| 501-600     | 5         | 9.26%   |
| 401-500     | 4         | 7.41%   |
| 601-700     | 2         | 3.7%    |
| 351-400     | 2         | 3.7%    |
| 701-800     | 1         | 1.85%   |
| 1501-2000   | 1         | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 50        | 94.34%  |
| 16/10 | 2         | 3.77%   |
| 21/9  | 1         | 1.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 31        | 57.41%  |
| 81-90          | 8         | 14.81%  |
| 201-250        | 6         | 11.11%  |
| 351-500        | 2         | 3.7%    |
| 141-150        | 2         | 3.7%    |
| 121-130        | 2         | 3.7%    |
| More than 1000 | 1         | 1.85%   |
| 301-350        | 1         | 1.85%   |
| 151-200        | 1         | 1.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 24        | 44.44%  |
| 101-120 | 17        | 31.48%  |
| 51-100  | 12        | 22.22%  |
| 1-50    | 1         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 52        | 96.3%   |
| 2     | 1         | 1.85%   |
| 0     | 1         | 1.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 40        | 45.98%  |
| Intel                    | 23        | 26.44%  |
| Qualcomm Atheros         | 17        | 19.54%  |
| Broadcom                 | 2         | 2.3%    |
| Ralink                   | 1         | 1.15%   |
| Qualcomm                 | 1         | 1.15%   |
| MEDIATEK                 | 1         | 1.15%   |
| Marvell Technology Group | 1         | 1.15%   |
| Dell                     | 1         | 1.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 27        | 27.55%  |
| Intel Wi-Fi 6 AX200                                                     | 11        | 11.22%  |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 6         | 6.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 6.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 4.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 4.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 3.06%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 3.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.02%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.02%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.02%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.02%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 1.02%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.02%   |
| Qualcomm BOLT!-JUNO                                                     | 1         | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 1.02%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 1.02%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                           | 1         | 1.02%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 1         | 1.02%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.02%   |
| MEDIATEK Network controller                                             | 1         | 1.02%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 1         | 1.02%   |
| Intel Wireless 7260                                                     | 1         | 1.02%   |
| Intel Wireless 3165                                                     | 1         | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.02%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.02%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.02%   |
| Intel Ethernet Connection (13) I219-V                                   | 1         | 1.02%   |
| Intel Ethernet Connection (12) I219-V                                   | 1         | 1.02%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.02%   |
| Dell Hub of E-Port Replicator                                           | 1         | 1.02%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 1         | 1.02%   |
| Broadcom BCM43225 802.11b/g/n                                           | 1         | 1.02%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 42.31%  |
| Qualcomm Atheros      | 16        | 30.77%  |
| Realtek Semiconductor | 10        | 19.23%  |
| Ralink                | 1         | 1.92%   |
| MEDIATEK              | 1         | 1.92%   |
| Dell                  | 1         | 1.92%   |
| Broadcom              | 1         | 1.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 11        | 21.15%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 11.54%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 7.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 5.77%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 5.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 3.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 3.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.92%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.92%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 1.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.92%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.92%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 1.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 1.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.92%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 1.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.92%   |
| MEDIATEK Network controller                                             | 1         | 1.92%   |
| Intel Wireless 7260                                                     | 1         | 1.92%   |
| Intel Wireless 3165                                                     | 1         | 1.92%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.92%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.92%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 1.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.92%   |
| Dell Hub of E-Port Replicator                                           | 1         | 1.92%   |
| Broadcom BCM43225 802.11b/g/n                                           | 1         | 1.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 37        | 80.43%  |
| Qualcomm Atheros         | 3         | 6.52%   |
| Intel                    | 3         | 6.52%   |
| Qualcomm                 | 1         | 2.17%   |
| Marvell Technology Group | 1         | 2.17%   |
| Broadcom                 | 1         | 2.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 58.7%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 6         | 13.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 8.7%    |
| Qualcomm BOLT!-JUNO                                               | 1         | 2.17%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.17%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 2.17%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.17%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 2.17%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.17%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 2.17%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 2.17%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 51        | 53.13%  |
| Ethernet | 45        | 46.88%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 48        | 51.61%  |
| Ethernet | 45        | 48.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 38        | 70.37%  |
| 1     | 16        | 29.63%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 34        | 62.96%  |
| Yes  | 20        | 37.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 21        | 48.84%  |
| Lite-On Technology      | 8         | 18.6%   |
| IMC Networks            | 7         | 16.28%  |
| Foxconn / Hon Hai       | 2         | 4.65%   |
| Realtek Semiconductor   | 1         | 2.33%   |
| Ralink                  | 1         | 2.33%   |
| Hewlett-Packard         | 1         | 2.33%   |
| Cambridge Silicon Radio | 1         | 2.33%   |
| Broadcom                | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                               | 11        | 25.58%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 11.63%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 4         | 9.3%    |
| IMC Networks Bluetooth Radio                                                        | 4         | 9.3%    |
| Lite-On Bluetooth Device                                                            | 2         | 4.65%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 4.65%   |
| Intel Bluetooth Device                                                              | 2         | 4.65%   |
| IMC Networks Bluetooth Device                                                       | 2         | 4.65%   |
| Realtek Bluetooth Radio                                                             | 1         | 2.33%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 2.33%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 2.33%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 2.33%   |
| Intel Bluetooth wireless interface                                                  | 1         | 2.33%   |
| IMC Networks Wireless_Device                                                        | 1         | 2.33%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 2.33%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 2.33%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 2.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 2.33%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Intel       | 41        | 58.57%  |
| AMD         | 15        | 21.43%  |
| Nvidia      | 12        | 17.14%  |
| Plantronics | 1         | 1.43%   |
| Corsair     | 1         | 1.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 11        | 14.29%  |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 8         | 10.39%  |
| Intel Sunrise Point-LP HD Audio                                            | 6         | 7.79%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 6.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 5.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 5.19%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 3         | 3.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 3.9%    |
| Intel Comet Lake PCH-V cAVS                                                | 2         | 2.6%    |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 2.6%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.6%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.6%    |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                      | 2         | 2.6%    |
| AMD FCH Azalia Controller                                                  | 2         | 2.6%    |
| Plantronics Blackwire 3225 Series                                          | 1         | 1.3%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.3%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.3%    |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.3%    |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.3%    |
| Intel 200 Series PCH HD Audio                                              | 1         | 1.3%    |
| Corsair VOID ELITE Wireless Gaming Dongle                                  | 1         | 1.3%    |
| AMD Wrestler HDMI Audio                                                    | 1         | 1.3%    |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 1.3%    |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.3%    |
| AMD High Definition Audio Controller                                       | 1         | 1.3%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.3%    |

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

![Printer Vendor](./images/pie_chart/printer_vendor.svg)

![Printer Vendor](./images/line_chart/printer_vendor.svg)

| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)

![Printer Model](./images/line_chart/printer_model.svg)

| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seiko Epson L3150 Series           | 1         | 50%     |
| HP DeskJet 2620 All-in-One Printer | 1         | 50%     |

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
| Quanta                                 | 14        | 31.11%  |
| IMC Networks                           | 12        | 26.67%  |
| Chicony Electronics                    | 10        | 22.22%  |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.44%   |
| Sunplus Innovation Technology          | 1         | 2.22%   |
| Samsung Electronics                    | 1         | 2.22%   |
| Ricoh                                  | 1         | 2.22%   |
| Microdia                               | 1         | 2.22%   |
| Luxvisions Innotech Limited            | 1         | 2.22%   |
| ALi                                    | 1         | 2.22%   |
| Acer                                   | 1         | 2.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Quanta HD User Facing                                                         | 11        | 24.44%  |
| IMC Networks USB2.0 VGA UVC WebCam                                            | 7         | 15.56%  |
| IMC Networks USB2.0 HD UVC WebCam                                             | 4         | 8.89%   |
| Chicony VGA WebCam                                                            | 3         | 6.67%   |
| Chicony HD User Facing                                                        | 3         | 6.67%   |
| Sunplus HD WebCam                                                             | 1         | 2.22%   |
| Samsung Galaxy A5 (MTP)                                                       | 1         | 2.22%   |
| Ricoh USB2.0 Camera                                                           | 1         | 2.22%   |
| Quanta VGA WebCam                                                             | 1         | 2.22%   |
| Quanta USB2.0 HD UVC WebCam                                                   | 1         | 2.22%   |
| Quanta HP Webcam                                                              | 1         | 2.22%   |
| Microdia Integrated Webcam                                                    | 1         | 2.22%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                           | 1         | 2.22%   |
| IMC Networks USB2.0 UVC HD Webcam                                             | 1         | 2.22%   |
| Chicony USB2.0 VGA UVC WebCam                                                 | 1         | 2.22%   |
| Chicony TOSHIBA Web Camera - HD                                               | 1         | 2.22%   |
| Chicony Sony Visual Communication Camera                                      | 1         | 2.22%   |
| Chicony CNF8015                                                               | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) SunplusIT INC. HP Truevision HD Webcam | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                              | 1         | 2.22%   |
| ALi Gateway Webcam                                                            | 1         | 2.22%   |
| Acer BisonCam, NB Pro                                                         | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS301 Fingerprint Reader | 1         | 50%     |
| Validity Sensors Swipe Fingerprint Sensor  | 1         | 50%     |

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
| 0     | 39        | 72.22%  |
| 1     | 15        | 27.78%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 7         | 46.67%  |
| Net/wireless          | 3         | 20%     |
| Fingerprint reader    | 2         | 13.33%  |
| Graphics card         | 1         | 6.67%   |
| Chipcard              | 1         | 6.67%   |
| Bluetooth             | 1         | 6.67%   |

