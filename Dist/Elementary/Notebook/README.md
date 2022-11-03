Elementary - Hardware Trends (Notebooks)
----------------------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/linuxhw/TestCoverage)

Period: Oct, 2022.

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

| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Elementary 6.1   | 23        | 95.83%  |
| Elementary 5.1.7 | 1         | 4.17%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Elementary | 24        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.15.0-48-generic      | 10        | 41.67%  |
| 5.15.0-50-generic      | 6         | 25%     |
| 5.15.0-52-generic      | 2         | 8.33%   |
| 5.11.0-43-generic      | 2         | 8.33%   |
| 5.19.12-051912-generic | 1         | 4.17%   |
| 5.15.0-43-generic      | 1         | 4.17%   |
| 5.13.0-40-generic      | 1         | 4.17%   |
| 4.15.0-163-generic     | 1         | 4.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 19        | 79.17%  |
| 5.11.0  | 2         | 8.33%   |
| 5.19.12 | 1         | 4.17%   |
| 5.13.0  | 1         | 4.17%   |
| 4.15.0  | 1         | 4.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 19        | 79.17%  |
| 5.11    | 2         | 8.33%   |
| 5.19    | 1         | 4.17%   |
| 5.13    | 1         | 4.17%   |
| 4.15    | 1         | 4.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 24        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Pantheon | 24        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 24        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 21        | 87.5%   |
| LightDM | 3         | 12.5%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 12        | 50%     |
| de_DE | 3         | 12.5%   |
| fr_FR | 2         | 8.33%   |
| tr_TR | 1         | 4.17%   |
| ru_RU | 1         | 4.17%   |
| pt_PT | 1         | 4.17%   |
| it_IT | 1         | 4.17%   |
| es_MX | 1         | 4.17%   |
| es_ES | 1         | 4.17%   |
| en_GB | 1         | 4.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 15        | 62.5%   |
| BIOS | 9         | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type | Notebooks | Percent |
|------|-----------|---------|
| Ext4 | 23        | 95.83%  |
| Xfs  | 1         | 4.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 21        | 87.5%   |
| GPT     | 3         | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 10        | 41.67%  |
| ASUSTek Computer | 4         | 16.67%  |
| Hewlett-Packard  | 3         | 12.5%   |
| Toshiba          | 2         | 8.33%   |
| MSI              | 2         | 8.33%   |
| HUAWEI           | 1         | 4.17%   |
| Dell             | 1         | 4.17%   |
| Apple            | 1         | 4.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba TECRA A11                        | 1         | 4.17%   |
| Toshiba Satellite C855-1WX               | 1         | 4.17%   |
| MSI Modern 14 B10MW                      | 1         | 4.17%   |
| MSI GE70 2QE                             | 1         | 4.17%   |
| Lenovo V130-15IKB 81HN                   | 1         | 4.17%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A7008AMZ | 1         | 4.17%   |
| Lenovo ThinkPad T470 20JNS08H00          | 1         | 4.17%   |
| Lenovo ThinkPad T420 4236JY2             | 1         | 4.17%   |
| Lenovo ThinkPad E14 Gen 3 20YDCTO1WW     | 1         | 4.17%   |
| Lenovo ThinkPad E14 20RA004VPH           | 1         | 4.17%   |
| Lenovo Legion 5 15IMH05H 81Y6            | 1         | 4.17%   |
| Lenovo IdeaPad S340-15IIL 81VW           | 1         | 4.17%   |
| Lenovo IdeaPad 510-15IKB 80SV            | 1         | 4.17%   |
| Lenovo IdeaPad 3 15ITL05 81X8            | 1         | 4.17%   |
| HUAWEI NBLK-WAX9X                        | 1         | 4.17%   |
| HP Pavilion dv7                          | 1         | 4.17%   |
| HP Laptop 17-ca3xxx                      | 1         | 4.17%   |
| HP Laptop 15-bw0xx                       | 1         | 4.17%   |
| Dell Inspiron 15-3567                    | 1         | 4.17%   |
| ASUS ZenBook S UX391UA                   | 1         | 4.17%   |
| ASUS VivoBook_ASUSLaptop X512DK_X512DK   | 1         | 4.17%   |
| ASUS UX31A                               | 1         | 4.17%   |
| ASUS ROG Zephyrus M16 GU603HE_GU603HE    | 1         | 4.17%   |
| Apple MacBookPro10,1                     | 1         | 4.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 5         | 20.83%  |
| Lenovo IdeaPad     | 3         | 12.5%   |
| HP Laptop          | 2         | 8.33%   |
| Toshiba TECRA      | 1         | 4.17%   |
| Toshiba Satellite  | 1         | 4.17%   |
| MSI Modern         | 1         | 4.17%   |
| MSI GE70           | 1         | 4.17%   |
| Lenovo V130-15IKB  | 1         | 4.17%   |
| Lenovo Legion      | 1         | 4.17%   |
| HUAWEI NBLK-WAX9X  | 1         | 4.17%   |
| HP Pavilion        | 1         | 4.17%   |
| Dell Inspiron      | 1         | 4.17%   |
| ASUS ZenBook       | 1         | 4.17%   |
| ASUS VivoBook      | 1         | 4.17%   |
| ASUS UX31A         | 1         | 4.17%   |
| ASUS ROG           | 1         | 4.17%   |
| Apple MacBookPro10 | 1         | 4.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 5         | 20.83%  |
| 2021 | 3         | 12.5%   |
| 2020 | 3         | 12.5%   |
| 2017 | 2         | 8.33%   |
| 2016 | 2         | 8.33%   |
| 2014 | 2         | 8.33%   |
| 2012 | 2         | 8.33%   |
| 2018 | 1         | 4.17%   |
| 2015 | 1         | 4.17%   |
| 2011 | 1         | 4.17%   |
| 2010 | 1         | 4.17%   |
| 2008 | 1         | 4.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 24        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 20        | 83.33%  |
| Enabled  | 4         | 16.67%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 24        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 13        | 54.17%  |
| 16.01-24.0 | 4         | 16.67%  |
| 8.01-16.0  | 4         | 16.67%  |
| 32.01-64.0 | 2         | 8.33%   |
| 3.01-4.0   | 1         | 4.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 9         | 37.5%   |
| 1.01-2.0  | 8         | 33.33%  |
| 4.01-8.0  | 3         | 12.5%   |
| 3.01-4.0  | 2         | 8.33%   |
| 8.01-16.0 | 1         | 4.17%   |
| 0.51-1.0  | 1         | 4.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 20        | 83.33%  |
| 2      | 2         | 8.33%   |
| 4      | 1         | 4.17%   |
| 3      | 1         | 4.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 70.83%  |
| Yes       | 7         | 29.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 75%     |
| No        | 6         | 25%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 95.83%  |
| No        | 1         | 4.17%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| USA                    | 3         | 12.5%   |
| Russia                 | 3         | 12.5%   |
| India                  | 2         | 8.33%   |
| Germany                | 2         | 8.33%   |
| France                 | 2         | 8.33%   |
| UK                     | 1         | 4.17%   |
| Turkey                 | 1         | 4.17%   |
| Thailand               | 1         | 4.17%   |
| Spain                  | 1         | 4.17%   |
| Slovenia               | 1         | 4.17%   |
| Portugal               | 1         | 4.17%   |
| Philippines            | 1         | 4.17%   |
| Nepal                  | 1         | 4.17%   |
| Mexico                 | 1         | 4.17%   |
| Italy                  | 1         | 4.17%   |
| Canada                 | 1         | 4.17%   |
| Bosnia and Herzegovina | 1         | 4.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Visakhapatnam    | 1         | 4.17%   |
| Vipava           | 1         | 4.17%   |
| Toronto          | 1         | 4.17%   |
| Strasbourg       | 1         | 4.17%   |
| St Petersburg    | 1         | 4.17%   |
| Paris            | 1         | 4.17%   |
| Northampton      | 1         | 4.17%   |
| Nazaré          | 1         | 4.17%   |
| Munich           | 1         | 4.17%   |
| Moscow           | 1         | 4.17%   |
| Monza            | 1         | 4.17%   |
| Mönchengladbach | 1         | 4.17%   |
| Mahopac          | 1         | 4.17%   |
| Madrid           | 1         | 4.17%   |
| Khimki           | 1         | 4.17%   |
| Kathmandu        | 1         | 4.17%   |
| Jonesborough     | 1         | 4.17%   |
| Istanbul         | 1         | 4.17%   |
| Gradacac         | 1         | 4.17%   |
| Chihuahua City   | 1         | 4.17%   |
| Chennai          | 1         | 4.17%   |
| Caloocan City    | 1         | 4.17%   |
| Bellevue         | 1         | 4.17%   |
| Bangkok          | 1         | 4.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Sandisk                   | 5         | 5      | 17.24%  |
| Seagate                   | 4         | 4      | 13.79%  |
| Samsung Electronics       | 4         | 4      | 13.79%  |
| WDC                       | 3         | 3      | 10.34%  |
| Toshiba                   | 2         | 2      | 6.9%    |
| SK hynix                  | 2         | 2      | 6.9%    |
| Unknown                   | 1         | 1      | 3.45%   |
| Union Memory              | 1         | 1      | 3.45%   |
| Realtek Semiconductor     | 1         | 1      | 3.45%   |
| PNY                       | 1         | 1      | 3.45%   |
| Pioneer                   | 1         | 1      | 3.45%   |
| Micron/Crucial Technology | 1         | 1      | 3.45%   |
| Intel                     | 1         | 2      | 3.45%   |
| Crucial                   | 1         | 1      | 3.45%   |
| Apple                     | 1         | 1      | 3.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1TB | 2         | 6.67%   |
| Samsung SSD 850 EVO 250GB                      | 2         | 6.67%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 1         | 3.33%   |
| WDC WD Elements 512GB                          | 1         | 3.33%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB           | 1         | 3.33%   |
| Unknown MMC Card  1GB                          | 1         | 3.33%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB        | 1         | 3.33%   |
| Toshiba NVMe Controller 512GB                  | 1         | 3.33%   |
| Toshiba KXG50ZNV512G 512GB                     | 1         | 3.33%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB      | 1         | 3.33%   |
| SK hynix HFS128G39TNF-N3A0A 128GB SSD          | 1         | 3.33%   |
| Seagate ST9320423AS 320GB                      | 1         | 3.33%   |
| Seagate ST9250320AS 250GB                      | 1         | 3.33%   |
| Seagate ST2000LM 007-1R8174 2TB                | 1         | 3.33%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 1         | 3.33%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB             | 1         | 3.33%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD            | 1         | 3.33%   |
| SanDisk SD5SE2256G1002E 256GB SSD              | 1         | 3.33%   |
| Samsung MZNTD512HAGL-000L1 512GB SSD           | 1         | 3.33%   |
| Samsung HM640JJ 640GB                          | 1         | 3.33%   |
| Realtek ADATA SX6000PNP 512GB                  | 1         | 3.33%   |
| PNY CS900 120GB SSD                            | 1         | 3.33%   |
| Pioneer APS-SL3N-120 120GB                     | 1         | 3.33%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB          | 1         | 3.33%   |
| Intel SSDPEKNU010TZ 1TB                        | 1         | 3.33%   |
| Intel SSD 660P Series 1024GB                   | 1         | 3.33%   |
| Crucial CT960BX500SSD1 960GB                   | 1         | 3.33%   |
| Apple SSD SM512E 500GB                         | 1         | 3.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 80%     |
| Samsung Electronics | 1         | 1      | 20%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 27.27%  |
| SanDisk             | 2         | 2      | 18.18%  |
| WDC                 | 1         | 1      | 9.09%   |
| SK hynix            | 1         | 1      | 9.09%   |
| PNY                 | 1         | 1      | 9.09%   |
| Pioneer             | 1         | 1      | 9.09%   |
| Crucial             | 1         | 1      | 9.09%   |
| Apple               | 1         | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 10        | 12     | 37.04%  |
| SSD     | 10        | 11     | 37.04%  |
| HDD     | 5         | 5      | 18.52%  |
| MMC     | 1         | 1      | 3.7%    |
| Unknown | 1         | 1      | 3.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 14        | 15     | 53.85%  |
| NVMe | 10        | 12     | 38.46%  |
| SAS  | 1         | 2      | 3.85%   |
| MMC  | 1         | 1      | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 10        | 11     | 66.67%  |
| 0.51-1.0   | 4         | 4      | 26.67%  |
| 1.01-2.0   | 1         | 1      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 12        | 50%     |
| 251-500    | 5         | 20.83%  |
| 501-1000   | 4         | 16.67%  |
| 21-50      | 1         | 4.17%   |
| 2001-3000  | 1         | 4.17%   |
| 51-100     | 1         | 4.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 21-50     | 9         | 37.5%   |
| 1-20      | 5         | 20.83%  |
| 51-100    | 5         | 20.83%  |
| 251-500   | 2         | 8.33%   |
| 101-250   | 2         | 8.33%   |
| 1001-2000 | 1         | 4.17%   |

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

| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 22        | 28     | 91.67%  |
| Works    | 2         | 2      | 8.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 16        | 53.33%  |
| SanDisk                      | 4         | 13.33%  |
| AMD                          | 4         | 13.33%  |
| Toshiba America Info Systems | 2         | 6.67%   |
| Union Memory (Shenzhen)      | 1         | 3.33%   |
| SK hynix                     | 1         | 3.33%   |
| Realtek Semiconductor        | 1         | 3.33%   |
| Micron/Crucial Technology    | 1         | 3.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 12.12%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 3         | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 9.09%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 6.06%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 6.06%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 3.03%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 3.03%   |
| Toshiba America Info Systems NVMe Controller                                     | 1         | 3.03%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 3.03%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 3.03%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 3.03%   |
| Realtek Realtek Non-Volatile memory controller                                   | 1         | 3.03%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 3.03%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 3.03%   |
| Intel SSD 660P Series                                                            | 1         | 3.03%   |
| Intel Non-Volatile memory controller                                             | 1         | 3.03%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 3.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 3.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 3.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 3.03%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 3.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 3.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 18        | 58.06%  |
| NVMe | 10        | 32.26%  |
| RAID | 3         | 9.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 18        | 75%     |
| AMD    | 6         | 25%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 8.33%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 8.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 4.17%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 4.17%   |
| Intel Core i7-4550U CPU @ 1.50GHz             | 1         | 4.17%   |
| Intel Core i7-3820QM CPU @ 2.70GHz            | 1         | 4.17%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 4.17%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 4.17%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 4.17%   |
| Intel Core i5-4210H CPU @ 2.90GHz             | 1         | 4.17%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 4.17%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 4.17%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz            | 1         | 4.17%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 4.17%   |
| Intel Core i3-2328M CPU @ 2.20GHz             | 1         | 4.17%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 1         | 4.17%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 4.17%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 4.17%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 4.17%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 4.17%   |
| AMD Phenom II N640 Dual-Core Processor        | 1         | 4.17%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 4.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i5 | 8         | 33.33%  |
| Intel Core i7 | 6         | 25%     |
| AMD Ryzen 5   | 4         | 16.67%  |
| Other         | 3         | 12.5%   |
| Intel Core i3 | 2         | 8.33%   |
| AMD Phenom II | 1         | 4.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 14        | 58.33%  |
| 4      | 6         | 25%     |
| 6      | 3         | 12.5%   |
| 8      | 1         | 4.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 24        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 21        | 87.5%   |
| 1      | 3         | 12.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 24        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806e9    | 3         | 12.5%   |
| 0x806ec    | 2         | 8.33%   |
| 0x306a9    | 2         | 8.33%   |
| 0x206a7    | 2         | 8.33%   |
| Unknown    | 2         | 8.33%   |
| 0xa0652    | 1         | 4.17%   |
| 0x806ea    | 1         | 4.17%   |
| 0x806c1    | 1         | 4.17%   |
| 0x706e5    | 1         | 4.17%   |
| 0x40651    | 1         | 4.17%   |
| 0x306c3    | 1         | 4.17%   |
| 0x20655    | 1         | 4.17%   |
| 0x08608103 | 1         | 4.17%   |
| 0x08600106 | 1         | 4.17%   |
| 0x08108109 | 1         | 4.17%   |
| 0x08108102 | 1         | 4.17%   |
| 0x06006704 | 1         | 4.17%   |
| 0x010000c8 | 1         | 4.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 6         | 25%     |
| Zen+        | 2         | 8.33%   |
| SandyBridge | 2         | 8.33%   |
| IvyBridge   | 2         | 8.33%   |
| Haswell     | 2         | 8.33%   |
| Unknown     | 2         | 8.33%   |
| Zen 2       | 1         | 4.17%   |
| Westmere    | 1         | 4.17%   |
| TigerLake   | 1         | 4.17%   |
| Skylake     | 1         | 4.17%   |
| K10         | 1         | 4.17%   |
| IceLake     | 1         | 4.17%   |
| Excavator   | 1         | 4.17%   |
| CometLake   | 1         | 4.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 17        | 56.67%  |
| AMD    | 8         | 26.67%  |
| Nvidia | 5         | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                         | 3         | 9.09%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 6.06%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 6.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 6.06%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 6.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 6.06%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 1         | 3.03%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 3.03%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 1         | 3.03%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                   | 1         | 3.03%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 1         | 3.03%   |
| Intel UHD Graphics 620                                                        | 1         | 3.03%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 1         | 3.03%   |
| Intel Tiger Lake UHD Graphics                                                 | 1         | 3.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 1         | 3.03%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                        | 1         | 3.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 3.03%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 3.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 3.03%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 3.03%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                     | 1         | 3.03%   |
| AMD Renoir                                                                    | 1         | 3.03%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                  | 1         | 3.03%   |
| AMD Lucienne                                                                  | 1         | 3.03%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                          | 1         | 3.03%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 1         | 3.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 11        | 45.83%  |
| Intel + Nvidia | 4         | 16.67%  |
| 2 x AMD        | 3         | 12.5%   |
| 1 x AMD        | 3         | 12.5%   |
| Intel + AMD    | 2         | 8.33%   |
| 1 x Nvidia     | 1         | 4.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 21        | 87.5%   |
| Proprietary | 3         | 12.5%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 54.17%  |
| 1.01-2.0   | 6         | 25%     |
| 0.51-1.0   | 2         | 8.33%   |
| 0.01-0.5   | 2         | 8.33%   |
| 5.01-6.0   | 1         | 4.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| BOE              | 7         | 23.33%  |
| AU Optronics     | 7         | 23.33%  |
| LG Display       | 4         | 13.33%  |
| Chimei Innolux   | 4         | 13.33%  |
| ViewSonic        | 2         | 6.67%   |
| Dell             | 2         | 6.67%   |
| TopView          | 1         | 3.33%   |
| BenQ             | 1         | 3.33%   |
| ASUSTek Computer | 1         | 3.33%   |
| Apple            | 1         | 3.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| ViewSonic VP2768 Series VSC2034 2560x1440 597x336mm 27.0-inch    | 1         | 3.33%   |
| ViewSonic VA2406-FHD VSC3B66 1920x1080 527x296mm 23.8-inch       | 1         | 3.33%   |
| TopView HD TV TOPC37E 1920x1080 700x390mm 31.5-inch              | 1         | 3.33%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch      | 1         | 3.33%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch     | 1         | 3.33%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x174mm 14.0-inch     | 1         | 3.33%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch      | 1         | 3.33%   |
| Dell S2415H DELA0B5 1920x1080 527x296mm 23.8-inch                | 1         | 3.33%   |
| Dell D2020H DELF11F 1600x900 432x243mm 19.5-inch                 | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN175E 1920x1080 381x214mm 17.2-inch | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN1348 1920x1080 293x165mm 13.2-inch | 1         | 3.33%   |
| BOE LCD Monitor BOE0A0B 2560x1600 344x215mm 16.0-inch            | 1         | 3.33%   |
| BOE LCD Monitor BOE08DF 1920x1080 344x194mm 15.5-inch            | 1         | 3.33%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch            | 1         | 3.33%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch            | 1         | 3.33%   |
| BOE LCD Monitor BOE0816 1366x768 344x193mm 15.5-inch             | 1         | 3.33%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch            | 1         | 3.33%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch            | 1         | 3.33%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch    | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch    | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO492D 1920x1080 293x165mm 13.2-inch   | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch   | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch    | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch   | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch    | 1         | 3.33%   |
| ASUSTek Computer MB16AC AUS1641 1920x1080 344x194mm 15.5-inch    | 1         | 3.33%   |
| Apple Color LCD APPA00E 2880x1800 331x207mm 15.4-inch            | 1         | 3.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 15        | 55.56%  |
| 1366x768 (WXGA) | 6         | 22.22%  |
| 2560x1440 (QHD) | 2         | 7.41%   |
| 1600x900 (HD+)  | 2         | 7.41%   |
| 2880x1800       | 1         | 3.7%    |
| 2560x1600       | 1         | 3.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 11        | 36.67%  |
| 13     | 5         | 16.67%  |
| 14     | 4         | 13.33%  |
| 17     | 3         | 10%     |
| 31     | 1         | 3.33%   |
| 27     | 1         | 3.33%   |
| 24     | 1         | 3.33%   |
| 23     | 1         | 3.33%   |
| 21     | 1         | 3.33%   |
| 19     | 1         | 3.33%   |
| 16     | 1         | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 19        | 63.33%  |
| 501-600     | 3         | 10%     |
| 351-400     | 3         | 10%     |
| 401-500     | 2         | 6.67%   |
| 201-300     | 2         | 6.67%   |
| 601-700     | 1         | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 22        | 91.67%  |
| 16/10 | 2         | 8.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 11        | 36.67%  |
| 81-90          | 7         | 23.33%  |
| 201-250        | 3         | 10%     |
| 121-130        | 3         | 10%     |
| 71-80          | 2         | 6.67%   |
| 351-500        | 1         | 3.33%   |
| 301-350        | 1         | 3.33%   |
| 151-200        | 1         | 3.33%   |
| 111-120        | 1         | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 12        | 41.38%  |
| 101-120 | 8         | 27.59%  |
| 161-240 | 5         | 17.24%  |
| 51-100  | 4         | 13.79%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 18        | 75%     |
| 2     | 6         | 25%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 37.84%  |
| Realtek Semiconductor | 13        | 35.14%  |
| Qualcomm Atheros      | 3         | 8.11%   |
| MediaTek              | 2         | 5.41%   |
| Broadcom              | 2         | 5.41%   |
| Sierra Wireless       | 1         | 2.7%    |
| D-Link                | 1         | 2.7%    |
| Broadcom Limited      | 1         | 2.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 8         | 17.78%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 2         | 4.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 2         | 4.44%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 2         | 4.44%   |
| Intel Wireless 8265 / 8275                                           | 2         | 4.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 4.44%   |
| Sierra Wireless EM7345 4G LTE                                        | 1         | 2.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1         | 2.22%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 2.22%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 2.22%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 1         | 2.22%   |
| Realtek Realtek Ethernet controller                                  | 1         | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1         | 2.22%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller            | 1         | 2.22%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 1         | 2.22%   |
| Intel Wireless 8260                                                  | 1         | 2.22%   |
| Intel Wireless 7260                                                  | 1         | 2.22%   |
| Intel Wireless 3160                                                  | 1         | 2.22%   |
| Intel Wi-Fi 6 AX201                                                  | 1         | 2.22%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 1         | 2.22%   |
| Intel Ethernet Connection I219-LM                                    | 1         | 2.22%   |
| Intel Ethernet Connection I218-V                                     | 1         | 2.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 2.22%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1         | 2.22%   |
| Intel Centrino Advanced-N 6235                                       | 1         | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 1         | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 1         | 2.22%   |
| Intel 82577LC Gigabit Network Connection                             | 1         | 2.22%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 1         | 2.22%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                    | 1         | 2.22%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                               | 1         | 2.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 1         | 2.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 50%     |
| Realtek Semiconductor | 5         | 19.23%  |
| Qualcomm Atheros      | 2         | 7.69%   |
| MediaTek              | 2         | 7.69%   |
| Sierra Wireless       | 1         | 3.85%   |
| D-Link                | 1         | 3.85%   |
| Broadcom Limited      | 1         | 3.85%   |
| Broadcom              | 1         | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 2         | 7.69%   |
| Intel Wireless 8265 / 8275                                           | 2         | 7.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 7.69%   |
| Sierra Wireless EM7345 4G LTE                                        | 1         | 3.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1         | 3.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 3.85%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 3.85%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 1         | 3.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1         | 3.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 1         | 3.85%   |
| Intel Wireless 8260                                                  | 1         | 3.85%   |
| Intel Wireless 7260                                                  | 1         | 3.85%   |
| Intel Wireless 3160                                                  | 1         | 3.85%   |
| Intel Wi-Fi 6 AX201                                                  | 1         | 3.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 1         | 3.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 3.85%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1         | 3.85%   |
| Intel Centrino Advanced-N 6235                                       | 1         | 3.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 1         | 3.85%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 1         | 3.85%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                               | 1         | 3.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 1         | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 12        | 66.67%  |
| Intel                 | 4         | 22.22%  |
| Qualcomm Atheros      | 1         | 5.56%   |
| Broadcom              | 1         | 5.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 42.11%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 10.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 10.53%  |
| Realtek Realtek Ethernet controller                               | 1         | 5.26%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 5.26%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 5.26%   |
| Intel Ethernet Connection I218-V                                  | 1         | 5.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 5.26%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 5.26%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 5.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 24        | 57.14%  |
| Ethernet | 18        | 42.86%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 80%     |
| Ethernet | 5         | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 17        | 70.83%  |
| 1     | 7         | 29.17%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 20        | 83.33%  |
| Yes  | 4         | 16.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 47.83%  |
| Realtek Semiconductor           | 3         | 13.04%  |
| Toshiba                         | 2         | 8.7%    |
| Broadcom                        | 2         | 8.7%    |
| Realtek                         | 1         | 4.35%   |
| Qualcomm Atheros Communications | 1         | 4.35%   |
| IMC Networks                    | 1         | 4.35%   |
| Foxconn / Hon Hai               | 1         | 4.35%   |
| Apple                           | 1         | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 5         | 21.74%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3         | 13.04%  |
| Intel AX201 Bluetooth                          | 2         | 8.7%    |
| Toshiba RT Bluetooth Radio                     | 1         | 4.35%   |
| Toshiba Integrated Bluetooth HCI               | 1         | 4.35%   |
| Realtek RTL8821A Bluetooth                     | 1         | 4.35%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 4.35%   |
| Realtek Bluetooth Radio                        | 1         | 4.35%   |
| Realtek Bluetooth Radio                        | 1         | 4.35%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 4.35%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 4.35%   |
| IMC Networks Wireless_Device                   | 1         | 4.35%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 4.35%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR           | 1         | 4.35%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 4.35%   |
| Apple Bluetooth Host Controller                | 1         | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 18        | 62.07%  |
| AMD                 | 6         | 20.69%  |
| Nvidia              | 3         | 10.34%  |
| Huawei Technologies | 1         | 3.45%   |
| Goldvish            | 1         | 3.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 5         | 13.51%  |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 10.81%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 8.11%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 5.41%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 5.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 5.41%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 2.7%    |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 2.7%    |
| Nvidia Audio device                                                        | 1         | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.7%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 2.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 2.7%    |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.7%    |
| Intel Comet Lake PCH cAVS                                                  | 1         | 2.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 2.7%    |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2.7%    |
| Huawei Technologies CM-Q3                                                  | 1         | 2.7%    |
| Goldvish USB PnP Audio Device                                              | 1         | 2.7%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 2.7%    |
| AMD High Definition Audio Controller                                       | 1         | 2.7%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 2.7%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 2.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| SK hynix | 2         | 50%     |
| Elpida   | 1         | 25%     |
| Crucial  | 1         | 25%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s           | 1         | 25%     |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s | 1         | 25%     |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 25%     |
| Crucial RAM CT8G4SFRA32A.C8FP 8192MB SODIMM DDR4 3200MT/s | 1         | 25%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind | Notebooks | Percent |
|------|-----------|---------|
| DDR3 | 2         | 66.67%  |
| DDR4 | 1         | 33.33%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 3         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size | Notebooks | Percent |
|------|-----------|---------|
| 8192 | 2         | 66.67%  |
| 4096 | 1         | 33.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 2         | 66.67%  |
| 3200  | 1         | 33.33%  |

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)

![Camera Vendor](./images/line_chart/camera_vendor.svg)

| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8         | 34.78%  |
| IMC Networks                           | 5         | 21.74%  |
| Acer                                   | 3         | 13.04%  |
| Syntek                                 | 1         | 4.35%   |
| Suyin                                  | 1         | 4.35%   |
| Quanta                                 | 1         | 4.35%   |
| Microdia                               | 1         | 4.35%   |
| Lite-On Technology                     | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4.35%   |
| Apple                                  | 1         | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 5         | 21.74%  |
| IMC Networks USB2.0 HD UVC WebCam                | 3         | 13.04%  |
| Acer Integrated Camera                           | 2         | 8.7%    |
| Syntek EasyCamera                                | 1         | 4.35%   |
| Suyin HP Webcam                                  | 1         | 4.35%   |
| Quanta HP Webcam                                 | 1         | 4.35%   |
| Microdia Integrated_Webcam_HD                    | 1         | 4.35%   |
| Lite-On Integrated Camera                        | 1         | 4.35%   |
| IMC Networks ov9734_azurewave_camera             | 1         | 4.35%   |
| IMC Networks Integrated Camera                   | 1         | 4.35%   |
| Chicony USB2.0 UVC WebCam                        | 1         | 4.35%   |
| Chicony USB2.0 HD UVC WebCam                     | 1         | 4.35%   |
| Chicony TOSHIBA Web Camera - HD                  | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 1         | 4.35%   |
| Apple FaceTime HD Camera (Built-in)              | 1         | 4.35%   |
| Acer HD Webcam                                   | 1         | 4.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 4         | 50%     |
| Validity Sensors           | 2         | 25%     |
| Upek                       | 1         | 12.5%   |
| AuthenTec                  | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                    | 3         | 37.5%   |
| Validity Sensors VFS301 Fingerprint Reader             | 1         | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 12.5%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 12.5%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 12.5%   |
| AuthenTec Fingerprint Sensor                           | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./images/line_chart/chipcard_vendor.svg)

| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Lenovo | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)

![Chipcard Model](./images/line_chart/chipcard_model.svg)

| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 15        | 62.5%   |
| 1     | 8         | 33.33%  |
| 2     | 1         | 4.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 7         | 70%     |
| Net/ethernet          | 1         | 10%     |
| Multimedia controller | 1         | 10%     |
| Chipcard              | 1         | 10%     |

