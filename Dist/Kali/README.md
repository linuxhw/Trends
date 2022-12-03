Kali - Hardware Trends
----------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Kali/Desktop/README.md) and [notebooks](/Dist/Kali/Notebook/README.md).

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

![OS](./All/images/pie_chart/os_name.svg)

![OS](./All/images/line_chart/os_name.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Kali 2022.3 | 36        | 64.29%  |
| Kali 2022.4 | 20        | 35.71%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| Kali | 56        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.19.0-kali2-amd64   | 26        | 46.43%  |
| 6.0.0-kali3-amd64    | 15        | 26.79%  |
| 5.18.0-kali5-amd64   | 10        | 17.86%  |
| 5.18.0-kali7-amd64   | 3         | 5.36%   |
| 6.0.0-4-amd64        | 1         | 1.79%   |
| 5.18.0-kali5-686-pae | 1         | 1.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19.0  | 26        | 46.43%  |
| 6.0.0   | 16        | 28.57%  |
| 5.18.0  | 14        | 25%     |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19    | 26        | 46.43%  |
| 6.0     | 16        | 28.57%  |
| 5.18    | 14        | 25%     |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 55        | 98.21%  |
| i686   | 1         | 1.79%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 28        | 50%     |
| GNOME            | 15        | 26.79%  |
| KDE5             | 10        | 17.86%  |
| MATE             | 1         | 1.79%   |
| lightdm-xsession | 1         | 1.79%   |
| Unknown          | 1         | 1.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 52        | 92.86%  |
| Wayland | 3         | 5.36%   |
| Tty     | 1         | 1.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 30        | 53.57%  |
| GDM3    | 12        | 21.43%  |
| Unknown | 7         | 12.5%   |
| SDDM    | 6         | 10.71%  |
| GDM     | 1         | 1.79%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 36        | 64.29%  |
| en_IN | 5         | 8.93%   |
| ru_RU | 2         | 3.57%   |
| pt_BR | 2         | 3.57%   |
| en_GB | 2         | 3.57%   |
| nl_BE | 1         | 1.79%   |
| it_IT | 1         | 1.79%   |
| id_ID | 1         | 1.79%   |
| fr_FR | 1         | 1.79%   |
| es_HN | 1         | 1.79%   |
| es_ES | 1         | 1.79%   |
| en_ZA | 1         | 1.79%   |
| en_AU | 1         | 1.79%   |
| de_DE | 1         | 1.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 41        | 73.21%  |
| BIOS | 15        | 26.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 51        | 91.07%  |
| Overlay | 2         | 3.57%   |
| Ext2    | 2         | 3.57%   |
| Btrfs   | 1         | 1.79%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 43        | 76.79%  |
| MBR     | 7         | 12.5%   |
| Unknown | 6         | 10.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 94.64%  |
| Yes       | 3         | 5.36%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 50%     |
| No        | 28        | 50%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 13        | 23.21%  |
| Hewlett-Packard     | 11        | 19.64%  |
| Dell                | 10        | 17.86%  |
| Acer                | 5         | 8.93%   |
| MSI                 | 4         | 7.14%   |
| ASUSTek Computer    | 4         | 7.14%   |
| Google              | 3         | 5.36%   |
| Samsung Electronics | 1         | 1.79%   |
| Intel               | 1         | 1.79%   |
| Gigabyte Technology | 1         | 1.79%   |
| Colorful Technology | 1         | 1.79%   |
| Apple               | 1         | 1.79%   |
| Alienware           | 1         | 1.79%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung 950QED                         | 1         | 1.79%   |
| MSI MS-7D15                            | 1         | 1.79%   |
| MSI MS-7998                            | 1         | 1.79%   |
| MSI Modern 14 C12M                     | 1         | 1.79%   |
| MSI Katana GF76 12UC                   | 1         | 1.79%   |
| Lenovo ThinkPad X270 W10DG 20K60014MX  | 1         | 1.79%   |
| Lenovo ThinkPad X1 Yoga 4th 20QGS02E00 | 1         | 1.79%   |
| Lenovo ThinkPad T450 20BV0005US        | 1         | 1.79%   |
| Lenovo ThinkPad P52s 20LB0026US        | 1         | 1.79%   |
| Lenovo ThinkPad E15 Gen 2 20TD004NMX   | 1         | 1.79%   |
| Lenovo ThinkCentre M62z 51061A2        | 1         | 1.79%   |
| Lenovo Legion Y740-17IRHg 81UJ         | 1         | 1.79%   |
| Lenovo IdeaPad Gaming 3 15IMH05 82CG   | 1         | 1.79%   |
| Lenovo IdeaPad 330S-15ARR 81FB         | 1         | 1.79%   |
| Lenovo IdeaPad 320-15IAP 80XR          | 1         | 1.79%   |
| Lenovo IdeaPad 3 15IAU7 82RK           | 1         | 1.79%   |
| Lenovo IdeaPad 3 14IIL05 81WD          | 1         | 1.79%   |
| Lenovo IdeaPad 120S-11IAP 81A4         | 1         | 1.79%   |
| Intel NUC8i7HNK                        | 1         | 1.79%   |
| HP Stream Laptop 14-ax0XX              | 1         | 1.79%   |
| HP ProDesk 400 G3 SFF                  | 1         | 1.79%   |
| HP Pavilion Laptop 15-cs0xxx           | 1         | 1.79%   |
| HP Pavilion Laptop 14-dv0xxx           | 1         | 1.79%   |
| HP Pavilion 15                         | 1         | 1.79%   |
| HP Laptop 15-da0xxx                    | 1         | 1.79%   |
| HP ENVY x360 Convertible 15-cn1xxx     | 1         | 1.79%   |
| HP EliteBook 8570w                     | 1         | 1.79%   |
| HP EliteBook 840 G3                    | 1         | 1.79%   |
| HP 250 G7 Notebook PC                  | 1         | 1.79%   |
| HP 245 G3                              | 1         | 1.79%   |
| Google Nightfury                       | 1         | 1.79%   |
| Google Droid                           | 1         | 1.79%   |
| Google Delbin                          | 1         | 1.79%   |
| Gigabyte AB350M-DS3H                   | 1         | 1.79%   |
| Dell Vostro 1310                       | 1         | 1.79%   |
| Dell Precision 7550                    | 1         | 1.79%   |
| Dell Precision 3510                    | 1         | 1.79%   |
| Dell OptiPlex 7040                     | 1         | 1.79%   |
| Dell Latitude E7240                    | 1         | 1.79%   |
| Dell Latitude 5580                     | 1         | 1.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo IdeaPad       | 6         | 10.71%  |
| Lenovo ThinkPad      | 5         | 8.93%   |
| Dell Latitude        | 4         | 7.14%   |
| HP Pavilion          | 3         | 5.36%   |
| Acer Nitro           | 3         | 5.36%   |
| HP EliteBook         | 2         | 3.57%   |
| Dell Precision       | 2         | 3.57%   |
| Dell Inspiron        | 2         | 3.57%   |
| Samsung 950QED       | 1         | 1.79%   |
| MSI MS-7D15          | 1         | 1.79%   |
| MSI MS-7998          | 1         | 1.79%   |
| MSI Modern           | 1         | 1.79%   |
| MSI Katana           | 1         | 1.79%   |
| Lenovo ThinkCentre   | 1         | 1.79%   |
| Lenovo Legion        | 1         | 1.79%   |
| Intel NUC8i7HNK      | 1         | 1.79%   |
| HP Stream            | 1         | 1.79%   |
| HP ProDesk           | 1         | 1.79%   |
| HP Laptop            | 1         | 1.79%   |
| HP ENVY              | 1         | 1.79%   |
| HP 250               | 1         | 1.79%   |
| HP 245               | 1         | 1.79%   |
| Google Nightfury     | 1         | 1.79%   |
| Google Droid         | 1         | 1.79%   |
| Google Delbin        | 1         | 1.79%   |
| Gigabyte AB350M-DS3H | 1         | 1.79%   |
| Dell Vostro          | 1         | 1.79%   |
| Dell OptiPlex        | 1         | 1.79%   |
| Colorful DJ          | 1         | 1.79%   |
| ASUS N61Jv           | 1         | 1.79%   |
| ASUS N550JV          | 1         | 1.79%   |
| ASUS Maximus         | 1         | 1.79%   |
| ASUS ASUS            | 1         | 1.79%   |
| Apple iMac19         | 1         | 1.79%   |
| Alienware 17         | 1         | 1.79%   |
| Acer E1-532P         | 1         | 1.79%   |
| Acer Aspire          | 1         | 1.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 8         | 14.29%  |
| 2018 | 8         | 14.29%  |
| 2020 | 7         | 12.5%   |
| 2013 | 6         | 10.71%  |
| 2017 | 5         | 8.93%   |
| 2016 | 5         | 8.93%   |
| 2021 | 4         | 7.14%   |
| 2019 | 4         | 7.14%   |
| 2015 | 3         | 5.36%   |
| 2014 | 2         | 3.57%   |
| 2012 | 2         | 3.57%   |
| 2010 | 1         | 1.79%   |
| 2008 | 1         | 1.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 43        | 76.79%  |
| Desktop     | 8         | 14.29%  |
| Convertible | 3         | 5.36%   |
| Mini pc     | 1         | 1.79%   |
| All in one  | 1         | 1.79%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 56        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 53        | 94.64%  |
| Yes  | 3         | 5.36%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 20        | 35.71%  |
| 3.01-4.0    | 11        | 19.64%  |
| 16.01-24.0  | 8         | 14.29%  |
| 8.01-16.0   | 7         | 12.5%   |
| 32.01-64.0  | 6         | 10.71%  |
| 24.01-32.0  | 2         | 3.57%   |
| 64.01-256.0 | 1         | 1.79%   |
| 1.01-2.0    | 1         | 1.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 24        | 42.86%  |
| 1.01-2.0   | 14        | 25%     |
| 4.01-8.0   | 9         | 16.07%  |
| 3.01-4.0   | 5         | 8.93%   |
| 0.51-1.0   | 2         | 3.57%   |
| 16.01-24.0 | 1         | 1.79%   |
| 8.01-16.0  | 1         | 1.79%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 34        | 60.71%  |
| 2      | 15        | 26.79%  |
| 5      | 2         | 3.57%   |
| 0      | 2         | 3.57%   |
| 6      | 1         | 1.79%   |
| 4      | 1         | 1.79%   |
| 3      | 1         | 1.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 89.29%  |
| Yes       | 6         | 10.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 83.93%  |
| No        | 9         | 16.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 94.64%  |
| No        | 3         | 5.36%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 85.71%  |
| No        | 8         | 14.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 16        | 28.57%  |
| India        | 5         | 8.93%   |
| Spain        | 3         | 5.36%   |
| Indonesia    | 3         | 5.36%   |
| Germany      | 3         | 5.36%   |
| Bulgaria     | 3         | 5.36%   |
| Brazil       | 3         | 5.36%   |
| Italy        | 2         | 3.57%   |
| Canada       | 2         | 3.57%   |
| Belgium      | 2         | 3.57%   |
| Bangladesh   | 2         | 3.57%   |
| South Africa | 1         | 1.79%   |
| Russia       | 1         | 1.79%   |
| Qatar        | 1         | 1.79%   |
| Pakistan     | 1         | 1.79%   |
| Netherlands  | 1         | 1.79%   |
| Nepal        | 1         | 1.79%   |
| Moldova      | 1         | 1.79%   |
| Honduras     | 1         | 1.79%   |
| France       | 1         | 1.79%   |
| Finland      | 1         | 1.79%   |
| Australia    | 1         | 1.79%   |
| Armenia      | 1         | 1.79%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Rajkot                | 2         | 3.57%   |
| Houston               | 2         | 3.57%   |
| Dhaka                 | 2         | 3.57%   |
| Yerevan               | 1         | 1.79%   |
| Yekaterinburg         | 1         | 1.79%   |
| Udine                 | 1         | 1.79%   |
| Turku                 | 1         | 1.79%   |
| Toronto               | 1         | 1.79%   |
| Topi                  | 1         | 1.79%   |
| Tonawanda             | 1         | 1.79%   |
| Tegucigalpa           | 1         | 1.79%   |
| Tangerang             | 1         | 1.79%   |
| Sao Jose do Rio Preto | 1         | 1.79%   |
| Samokov               | 1         | 1.79%   |
| Rome                  | 1         | 1.79%   |
| Requena               | 1         | 1.79%   |
| Reading               | 1         | 1.79%   |
| Pune                  | 1         | 1.79%   |
| Pozuelo de Alarcón   | 1         | 1.79%   |
| Portland              | 1         | 1.79%   |
| Picayune              | 1         | 1.79%   |
| Philadelphia          | 1         | 1.79%   |
| Perth                 | 1         | 1.79%   |
| Penticton             | 1         | 1.79%   |
| Ooltewah              | 1         | 1.79%   |
| Onet-le-Chateau       | 1         | 1.79%   |
| Marietta              | 1         | 1.79%   |
| Lynn Haven            | 1         | 1.79%   |
| Kaski                 | 1         | 1.79%   |
| Jakarta               | 1         | 1.79%   |
| Huy                   | 1         | 1.79%   |
| Hanford               | 1         | 1.79%   |
| Guntur                | 1         | 1.79%   |
| Greensboro            | 1         | 1.79%   |
| Goshen                | 1         | 1.79%   |
| Foz do Iguaçu        | 1         | 1.79%   |
| Fort Worth            | 1         | 1.79%   |
| Erfurt                | 1         | 1.79%   |
| Enschede              | 1         | 1.79%   |
| Düren                | 1         | 1.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 15        | 20     | 18.99%  |
| Toshiba                   | 7         | 7      | 8.86%   |
| Seagate                   | 7         | 7      | 8.86%   |
| SanDisk                   | 7         | 7      | 8.86%   |
| WDC                       | 5         | 6      | 6.33%   |
| Kingston                  | 4         | 4      | 5.06%   |
| Hitachi                   | 4         | 4      | 5.06%   |
| Unknown                   | 3         | 3      | 3.8%    |
| KIOXIA                    | 3         | 4      | 3.8%    |
| SK hynix                  | 2         | 2      | 2.53%   |
| Micron Technology         | 2         | 2      | 2.53%   |
| KingSpec                  | 2         | 2      | 2.53%   |
| Intel                     | 2         | 2      | 2.53%   |
| Crucial                   | 2         | 2      | 2.53%   |
| Unknown                   | 2         | 3      | 2.53%   |
| XrayDisk                  | 1         | 1      | 1.27%   |
| V-GeN                     | 1         | 1      | 1.27%   |
| Team                      | 1         | 1      | 1.27%   |
| SPCC                      | 1         | 1      | 1.27%   |
| Silicon Motion            | 1         | 1      | 1.27%   |
| Rogueware                 | 1         | 1      | 1.27%   |
| Micron/Crucial Technology | 1         | 1      | 1.27%   |
| LITEON                    | 1         | 1      | 1.27%   |
| HGST                      | 1         | 1      | 1.27%   |
| Gritronix                 | 1         | 1      | 1.27%   |
| Apple                     | 1         | 2      | 1.27%   |
| A-DATA Technology         | 1         | 1      | 1.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST500LT012-9WS142 500GB                   | 2         | 2.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 2.38%   |
| Unknown                                           | 2         | 2.38%   |
| XrayDisk 512GB                                    | 1         | 1.19%   |
| WDC WD5000LPCX-24VHAT0 500GB                      | 1         | 1.19%   |
| WDC WD5000BEKT-60KA9T0 500GB                      | 1         | 1.19%   |
| WDC WD3200BEVT-75ZCT2 320GB                       | 1         | 1.19%   |
| WDC WD15EADS-00P8B0 1TB                           | 1         | 1.19%   |
| WDC WD10SPZX-21Z10T0 1TB                          | 1         | 1.19%   |
| WDC WD10EZEX-00WN4A0 1TB                          | 1         | 1.19%   |
| V-GeN V-GEN08SM22SCY512MTNV 512GB                 | 1         | 1.19%   |
| Unknown SU64G  64GB                               | 1         | 1.19%   |
| Unknown SS32G  32GB                               | 1         | 1.19%   |
| Unknown DA4064  64GB                              | 1         | 1.19%   |
| Toshiba MQ04ABF100 1TB                            | 1         | 1.19%   |
| Toshiba MQ02ABD100H 1TB                           | 1         | 1.19%   |
| Toshiba MQ01ABF050 500GB                          | 1         | 1.19%   |
| Toshiba MK5061GSY 500GB                           | 1         | 1.19%   |
| Toshiba HDWT140 4TB                               | 1         | 1.19%   |
| Toshiba DT01ACA200 2TB                            | 1         | 1.19%   |
| Toshiba DT01ACA050 500GB                          | 1         | 1.19%   |
| Team TM8PS7512G 512GB SSD                         | 1         | 1.19%   |
| SPCC Solid State Disk 256GB                       | 1         | 1.19%   |
| SK hynix HFM128GDJTNG-8310A 128GB                 | 1         | 1.19%   |
| SK hynix BC511 512GB                              | 1         | 1.19%   |
| Silicon Motion NE-512 512GB                       | 1         | 1.19%   |
| Seagate ST500DM002-1BD142 500GB                   | 1         | 1.19%   |
| Seagate ST1000LM035-1RK172 1TB                    | 1         | 1.19%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 1         | 1.19%   |
| Seagate Expansion HDD 5TB                         | 1         | 1.19%   |
| Seagate BUP Slim BK 2TB                           | 1         | 1.19%   |
| SanDisk X400 M.2 2280 512GB SSD                   | 1         | 1.19%   |
| SanDisk SDSSDA120G 120GB                          | 1         | 1.19%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD               | 1         | 1.19%   |
| SanDisk NVMe SSD Drive 512GB                      | 1         | 1.19%   |
| SanDisk Extreme 55AE 500GB SSD                    | 1         | 1.19%   |
| SanDisk DF4064  64GB                              | 1         | 1.19%   |
| SanDisk DF4032  32GB                              | 1         | 1.19%   |
| Samsung SSD PM871 M.2 2280 128GB                  | 1         | 1.19%   |
| Samsung SSD PM851 mSATA 128GB                     | 1         | 1.19%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 7         | 7      | 26.92%  |
| Seagate             | 7         | 7      | 26.92%  |
| WDC                 | 5         | 6      | 19.23%  |
| Hitachi             | 4         | 4      | 15.38%  |
| Samsung Electronics | 1         | 1      | 3.85%   |
| HGST                | 1         | 1      | 3.85%   |
| Apple               | 1         | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 9      | 30.43%  |
| SanDisk             | 4         | 4      | 17.39%  |
| Kingston            | 2         | 2      | 8.7%    |
| KingSpec            | 2         | 2      | 8.7%    |
| Crucial             | 2         | 2      | 8.7%    |
| Team                | 1         | 1      | 4.35%   |
| SPCC                | 1         | 1      | 4.35%   |
| Rogueware           | 1         | 1      | 4.35%   |
| LITEON              | 1         | 1      | 4.35%   |
| Gritronix           | 1         | 1      | 4.35%   |
| A-DATA Technology   | 1         | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 23        | 27     | 35.38%  |
| SSD     | 18        | 25     | 27.69%  |
| HDD     | 18        | 27     | 27.69%  |
| MMC     | 5         | 8      | 7.69%   |
| Unknown | 1         | 1      | 1.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 30        | 49     | 48.39%  |
| NVMe | 23        | 27     | 37.1%   |
| MMC  | 5         | 8      | 8.06%   |
| SAS  | 4         | 4      | 6.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 22        | 33     | 55%     |
| 0.51-1.0   | 14        | 15     | 35%     |
| 1.01-2.0   | 2         | 2      | 5%      |
| 3.01-4.0   | 1         | 1      | 2.5%    |
| 4.01-10.0  | 1         | 1      | 2.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 19        | 33.93%  |
| 251-500        | 12        | 21.43%  |
| 51-100         | 11        | 19.64%  |
| 501-1000       | 4         | 7.14%   |
| More than 3000 | 3         | 5.36%   |
| 1001-2000      | 3         | 5.36%   |
| 21-50          | 2         | 3.57%   |
| 2001-3000      | 1         | 1.79%   |
| 1-20           | 1         | 1.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 18        | 32.14%  |
| 1-20      | 17        | 30.36%  |
| 51-100    | 9         | 16.07%  |
| 101-250   | 5         | 8.93%   |
| 501-1000  | 4         | 7.14%   |
| 251-500   | 1         | 1.79%   |
| 2001-3000 | 1         | 1.79%   |
| 1001-2000 | 1         | 1.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB | 2         | 2      | 20%     |
| WDC WD5000BEKT-60KA9T0 500GB    | 1         | 1      | 10%     |
| WDC WD3200BEVT-75ZCT2 320GB     | 1         | 1      | 10%     |
| WDC WD10EZEX-00WN4A0 1TB        | 1         | 1      | 10%     |
| Toshiba DT01ACA050 500GB        | 1         | 1      | 10%     |
| Seagate ST500DM002-1BD142 500GB | 1         | 1      | 10%     |
| Kingston SUV500MS120G 120GB SSD | 1         | 1      | 10%     |
| Hitachi HTS542525K9SA00 250GB   | 1         | 1      | 10%     |
| Gritronix M.2 2280 256GB SSD    | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor    | Computers | Drives | Percent |
|-----------|-----------|--------|---------|
| Seagate   | 3         | 3      | 33.33%  |
| WDC       | 2         | 3      | 22.22%  |
| Toshiba   | 1         | 1      | 11.11%  |
| Kingston  | 1         | 1      | 11.11%  |
| Hitachi   | 1         | 1      | 11.11%  |
| Gritronix | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 42.86%  |
| WDC     | 2         | 3      | 28.57%  |
| Toshiba | 1         | 1      | 14.29%  |
| Hitachi | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 8      | 75%     |
| SSD  | 2         | 2      | 25%     |

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
| Works    | 34        | 47     | 54.84%  |
| Detected | 20        | 31     | 32.26%  |
| Malfunc  | 8         | 10     | 12.9%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 39        | 58.21%  |
| Samsung Electronics          | 9         | 13.43%  |
| AMD                          | 5         | 7.46%   |
| SK hynix                     | 2         | 2.99%   |
| Silicon Motion               | 2         | 2.99%   |
| Micron Technology            | 2         | 2.99%   |
| KIOXIA                       | 2         | 2.99%   |
| Kingston Technology Company  | 2         | 2.99%   |
| Toshiba America Info Systems | 1         | 1.49%   |
| SanDisk                      | 1         | 1.49%   |
| Micron/Crucial Technology    | 1         | 1.49%   |
| ASMedia Technology           | 1         | 1.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 10.96%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 6.85%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 5.48%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 5.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 4.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 4.11%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 4.11%   |
| Micron Non-Volatile memory controller                                          | 2         | 2.74%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 2.74%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.74%   |
| Intel Non-Volatile memory controller                                           | 2         | 2.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 2.74%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 2         | 2.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 2.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 2.74%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 1.37%   |
| SK hynix BC511                                                                 | 1         | 1.37%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 1.37%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 1.37%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 1.37%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 1.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.37%   |
| Samsung Electronics Non-Volatile memory controller                             | 1         | 1.37%   |
| Micron/Crucial NVMe Controller                                                 | 1         | 1.37%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.37%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 1.37%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.37%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.37%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.37%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.37%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 1.37%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.37%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.37%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.37%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.37%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1         | 1.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 33        | 47.14%  |
| NVMe | 23        | 32.86%  |
| RAID | 13        | 18.57%  |
| IDE  | 1         | 1.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 51        | 91.07%  |
| AMD    | 5         | 8.93%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 3.57%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 3.57%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 3.57%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 3.57%   |
| Intel 12th Gen Core i5-1235U                  | 2         | 3.57%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 3.57%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 3.57%   |
| Intel Xeon W-10885M CPU @ 2.40GHz             | 1         | 1.79%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 1         | 1.79%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 1.79%   |
| Intel Core i7-8705G CPU @ 3.10GHz             | 1         | 1.79%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.79%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.79%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 1.79%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.79%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 1.79%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 1.79%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 1.79%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1         | 1.79%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 1.79%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.79%   |
| Intel Core i5-8500 CPU @ 3.00GHz              | 1         | 1.79%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 1.79%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.79%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.79%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 1.79%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.79%   |
| Intel Core i5-3470S CPU @ 2.90GHz             | 1         | 1.79%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.79%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 1.79%   |
| Intel Core i3-9100F CPU @ 3.60GHz             | 1         | 1.79%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 1         | 1.79%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 1.79%   |
| Intel Core i3-2375M CPU @ 1.50GHz             | 1         | 1.79%   |
| Intel Core 2 Duo CPU T5670 @ 1.80GHz          | 1         | 1.79%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 1.79%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 1.79%   |
| Intel Celeron CPU 5205U @ 1.90GHz             | 1         | 1.79%   |
| Intel 12th Gen Core i7-12700H                 | 1         | 1.79%   |
| Intel 12th Gen Core i7-12650H                 | 1         | 1.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 15        | 26.79%  |
| Other            | 12        | 21.43%  |
| Intel Core i5    | 11        | 19.64%  |
| Intel Celeron    | 5         | 8.93%   |
| Intel Core i3    | 4         | 7.14%   |
| AMD Ryzen 5      | 3         | 5.36%   |
| Intel Pentium    | 2         | 3.57%   |
| Intel Xeon       | 1         | 1.79%   |
| Intel Core 2 Duo | 1         | 1.79%   |
| AMD E1           | 1         | 1.79%   |
| AMD A10          | 1         | 1.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 22        | 39.29%  |
| 4      | 21        | 37.5%   |
| 6      | 7         | 12.5%   |
| 10     | 3         | 5.36%   |
| 14     | 1         | 1.79%   |
| 12     | 1         | 1.79%   |
| 8      | 1         | 1.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 56        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 42        | 75%     |
| 1      | 14        | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 56        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 5         | 8.93%   |
| 0x506e3    | 5         | 8.93%   |
| 0x906ea    | 4         | 7.14%   |
| 0x906a3    | 3         | 5.36%   |
| 0x806ea    | 3         | 5.36%   |
| 0x806e9    | 3         | 5.36%   |
| 0x40651    | 3         | 5.36%   |
| 0xa0652    | 2         | 3.57%   |
| 0x906a4    | 2         | 3.57%   |
| 0x806ec    | 2         | 3.57%   |
| 0x506c9    | 2         | 3.57%   |
| 0x406e3    | 2         | 3.57%   |
| 0x306a9    | 2         | 3.57%   |
| 0x0810100b | 2         | 3.57%   |
| Unknown    | 2         | 3.57%   |
| 0x906e9    | 1         | 1.79%   |
| 0x806eb    | 1         | 1.79%   |
| 0x806d1    | 1         | 1.79%   |
| 0x706e5    | 1         | 1.79%   |
| 0x706a8    | 1         | 1.79%   |
| 0x6fd      | 1         | 1.79%   |
| 0x406c4    | 1         | 1.79%   |
| 0x306d4    | 1         | 1.79%   |
| 0x306c3    | 1         | 1.79%   |
| 0x206a7    | 1         | 1.79%   |
| 0x20652    | 1         | 1.79%   |
| 0x08001138 | 1         | 1.79%   |
| 0x07030105 | 1         | 1.79%   |
| 0x06001119 | 1         | 1.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 14        | 25%     |
| Skylake          | 7         | 12.5%   |
| TigerLake        | 5         | 8.93%   |
| Alderlake Hybrid | 5         | 8.93%   |
| Haswell          | 4         | 7.14%   |
| Zen              | 3         | 5.36%   |
| IvyBridge        | 3         | 5.36%   |
| IceLake          | 2         | 3.57%   |
| Goldmont         | 2         | 3.57%   |
| CometLake        | 2         | 3.57%   |
| Westmere         | 1         | 1.79%   |
| Silvermont       | 1         | 1.79%   |
| SandyBridge      | 1         | 1.79%   |
| Puma             | 1         | 1.79%   |
| Piledriver       | 1         | 1.79%   |
| Goldmont plus    | 1         | 1.79%   |
| Core             | 1         | 1.79%   |
| Broadwell        | 1         | 1.79%   |
| Unknown          | 1         | 1.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 46        | 61.33%  |
| Nvidia | 16        | 21.33%  |
| AMD    | 13        | 17.33%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                           | 4         | 5.19%   |
| Intel UHD Graphics 620                                              | 3         | 3.9%    |
| Intel HD Graphics 620                                               | 3         | 3.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                    | 3         | 3.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                          | 2         | 2.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                 | 2         | 2.6%    |
| Intel HD Graphics 530                                               | 2         | 2.6%    |
| Intel HD Graphics 500                                               | 2         | 2.6%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                           | 2         | 2.6%    |
| Intel Alder Lake-P Integrated Graphics Controller                   | 2         | 2.6%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]    | 2         | 2.6%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X] | 2         | 2.6%    |
| Nvidia TU117M [GeForce MX450]                                       | 1         | 1.3%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                     | 1         | 1.3%    |
| Nvidia TU117M                                                       | 1         | 1.3%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                       | 1         | 1.3%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                          | 1         | 1.3%    |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                            | 1         | 1.3%    |
| Nvidia GT216M [GeForce GT 325M]                                     | 1         | 1.3%    |
| Nvidia GP108GLM [Quadro P500 Mobile]                                | 1         | 1.3%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                 | 1         | 1.3%    |
| Nvidia GM204M [GeForce GTX 980M]                                    | 1         | 1.3%    |
| Nvidia GM108M [GeForce 930MX]                                       | 1         | 1.3%    |
| Nvidia GM108M [GeForce 840M]                                        | 1         | 1.3%    |
| Nvidia GK208B [GeForce GT 710]                                      | 1         | 1.3%    |
| Nvidia GK107M [GeForce GT 750M]                                     | 1         | 1.3%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                             | 1         | 1.3%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                     | 1         | 1.3%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller    | 1         | 1.3%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                | 1         | 1.3%    |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                           | 1         | 1.3%    |
| Intel RocketLake-S GT1 [UHD Graphics 730]                           | 1         | 1.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary) | 1         | 1.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)   | 1         | 1.3%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                              | 1         | 1.3%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                              | 1         | 1.3%    |
| Intel HD Graphics 630                                               | 1         | 1.3%    |
| Intel HD Graphics 5500                                              | 1         | 1.3%    |
| Intel HD Graphics 510                                               | 1         | 1.3%    |
| Intel GeminiLake [UHD Graphics 600]                                 | 1         | 1.3%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 27        | 48.21%  |
| Intel + Nvidia | 14        | 25%     |
| 1 x AMD        | 9         | 16.07%  |
| Intel + AMD    | 3         | 5.36%   |
| 1 x Nvidia     | 2         | 3.57%   |
| 2 x AMD        | 1         | 1.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 53        | 94.64%  |
| Proprietary | 2         | 3.57%   |
| Unknown     | 1         | 1.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 55.36%  |
| 3.01-4.0   | 9         | 16.07%  |
| 1.01-2.0   | 8         | 14.29%  |
| 5.01-6.0   | 3         | 5.36%   |
| 0.01-0.5   | 3         | 5.36%   |
| 0.51-1.0   | 2         | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 13        | 22.41%  |
| BOE                 | 11        | 18.97%  |
| LG Display          | 8         | 13.79%  |
| Chimei Innolux      | 7         | 12.07%  |
| Samsung Electronics | 4         | 6.9%    |
| PANDA               | 2         | 3.45%   |
| Hewlett-Packard     | 2         | 3.45%   |
| Dell                | 2         | 3.45%   |
| BenQ                | 2         | 3.45%   |
| Philips             | 1         | 1.72%   |
| Lenovo              | 1         | 1.72%   |
| HannStar            | 1         | 1.72%   |
| Goldstar            | 1         | 1.72%   |
| GDH                 | 1         | 1.72%   |
| CSO                 | 1         | 1.72%   |
| Apple               | 1         | 1.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch        | 2         | 3.45%   |
| Samsung Electronics LS32AG32x SAM71DE 1920x1080 698x393mm 31.5-inch     | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch   | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 1872x1053mm 84.6-inch | 1         | 1.72%   |
| Philips PHL 241E1 PHLC207 1920x1080 527x296mm 23.8-inch                 | 1         | 1.72%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                 | 1         | 1.72%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                 | 1         | 1.72%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch            | 1         | 1.72%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch            | 1         | 1.72%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch            | 1         | 1.72%   |
| LG Display LCD Monitor LGD05E0 1920x1080 382x215mm 17.3-inch            | 1         | 1.72%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch            | 1         | 1.72%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch            | 1         | 1.72%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch             | 1         | 1.72%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch            | 1         | 1.72%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                | 1         | 1.72%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch            | 1         | 1.72%   |
| Hewlett-Packard E273 HPN3470 1920x1080 598x336mm 27.0-inch              | 1         | 1.72%   |
| HannStar HSD160PHW1 HSD0640 1366x768 353x199mm 16.0-inch                | 1         | 1.72%   |
| Goldstar E2040 GSM4EB3 1600x900 443x249mm 20.0-inch                     | 1         | 1.72%   |
| GDH PHILCO GDH0030 1920x540 708x398mm 32.0-inch                         | 1         | 1.72%   |
| Dell SE2416H DELD081 1920x1080 527x296mm 23.8-inch                      | 1         | 1.72%   |
| Dell 2001FP DELA008 1600x1200 367x275mm 18.1-inch                       | 1         | 1.72%   |
| CSO LCD Monitor CSO1304 1920x1080 293x165mm 13.2-inch                   | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch         | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN153C 1920x1080 344x193mm 15.5-inch        | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN1499 1366x768 309x174mm 14.0-inch         | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch         | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch         | 1         | 1.72%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                   | 1         | 1.72%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                   | 1         | 1.72%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                    | 1         | 1.72%   |
| BOE LCD Monitor BOE06F9 1920x1080 344x193mm 15.5-inch                   | 1         | 1.72%   |
| BOE LCD Monitor BOE06F0 1366x768 344x194mm 15.5-inch                    | 1         | 1.72%   |
| BOE LCD Monitor BOE06CB 1920x1080 344x194mm 15.5-inch                   | 1         | 1.72%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                    | 1         | 1.72%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                   | 1         | 1.72%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                    | 1         | 1.72%   |
| BOE LCD Monitor BOE0632 1920x1080 344x194mm 15.5-inch                   | 1         | 1.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 32        | 57.14%  |
| 1366x768 (WXGA)  | 16        | 28.57%  |
| 3840x2160 (4K)   | 5         | 8.93%   |
| 1600x900 (HD+)   | 1         | 1.79%   |
| 1600x1200        | 1         | 1.79%   |
| 1440x900 (WXGA+) | 1         | 1.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 28        | 48.28%  |
| 14     | 7         | 12.07%  |
| 24     | 4         | 6.9%    |
| 13     | 4         | 6.9%    |
| 17     | 3         | 5.17%   |
| 20     | 2         | 3.45%   |
| 12     | 2         | 3.45%   |
| 84     | 1         | 1.72%   |
| 52     | 1         | 1.72%   |
| 31     | 1         | 1.72%   |
| 27     | 1         | 1.72%   |
| 21     | 1         | 1.72%   |
| 19     | 1         | 1.72%   |
| 16     | 1         | 1.72%   |
| 11     | 1         | 1.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 63.79%  |
| 501-600     | 5         | 8.62%   |
| 351-400     | 5         | 8.62%   |
| 401-500     | 4         | 6.9%    |
| 201-300     | 4         | 6.9%    |
| 601-700     | 1         | 1.72%   |
| 1501-2000   | 1         | 1.72%   |
| 1001-1500   | 1         | 1.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 52        | 96.3%   |
| 4/3   | 1         | 1.85%   |
| 16/10 | 1         | 1.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 29        | 50%     |
| 81-90          | 10        | 17.24%  |
| 201-250        | 4         | 6.9%    |
| 151-200        | 4         | 6.9%    |
| 121-130        | 3         | 5.17%   |
| More than 1000 | 2         | 3.45%   |
| 61-70          | 2         | 3.45%   |
| 71-80          | 1         | 1.72%   |
| 51-60          | 1         | 1.72%   |
| 351-500        | 1         | 1.72%   |
| 301-350        | 1         | 1.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 28        | 50%     |
| 101-120       | 11        | 19.64%  |
| 51-100        | 11        | 19.64%  |
| 161-240       | 3         | 5.36%   |
| More than 240 | 2         | 3.57%   |
| 1-50          | 1         | 1.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 51        | 91.07%  |
| 2     | 3         | 5.36%   |
| 3     | 1         | 1.79%   |
| 0     | 1         | 1.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 37.76%  |
| Realtek Semiconductor           | 29        | 29.59%  |
| Qualcomm Atheros                | 11        | 11.22%  |
| Broadcom                        | 6         | 6.12%   |
| Ralink Technology               | 2         | 2.04%   |
| Qualcomm Atheros Communications | 2         | 2.04%   |
| NetGear                         | 2         | 2.04%   |
| ASIX Electronics                | 2         | 2.04%   |
| Samsung Electronics             | 1         | 1.02%   |
| Lenovo                          | 1         | 1.02%   |
| ICS Advent                      | 1         | 1.02%   |
| Hewlett-Packard                 | 1         | 1.02%   |
| Fibocom                         | 1         | 1.02%   |
| Edimax Technology               | 1         | 1.02%   |
| Arduino SA                      | 1         | 1.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 13.22%  |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 4.13%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 4         | 3.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 3.31%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 3.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 2.48%   |
| Intel Wireless 8265 / 8275                                        | 3         | 2.48%   |
| Intel Wireless 8260                                               | 3         | 2.48%   |
| Intel Wireless 7265                                               | 3         | 2.48%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 2.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.65%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 1.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.65%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.65%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.65%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.83%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.83%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.83%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.83%   |
| Realtek RTL8187 Wireless Adapter                                  | 1         | 0.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.83%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.83%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.83%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.83%   |
| Ralink RT3072 Wireless Adapter                                    | 1         | 0.83%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.83%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.83%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.83%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.83%   |
| NetGear WNDA3100v2 802.11abgn [Broadcom BCM4323]                  | 1         | 0.83%   |
| NetGear A6210                                                     | 1         | 0.83%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 1         | 0.83%   |
| Intel Wireless 7260                                               | 1         | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 48.53%  |
| Realtek Semiconductor           | 11        | 16.18%  |
| Qualcomm Atheros                | 10        | 14.71%  |
| Broadcom                        | 5         | 7.35%   |
| Ralink Technology               | 2         | 2.94%   |
| Qualcomm Atheros Communications | 2         | 2.94%   |
| NetGear                         | 2         | 2.94%   |
| Hewlett-Packard                 | 1         | 1.47%   |
| Fibocom                         | 1         | 1.47%   |
| Edimax Technology               | 1         | 1.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 7.35%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 4         | 5.88%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 5.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 4.41%   |
| Intel Wireless 8265 / 8275                                     | 3         | 4.41%   |
| Intel Wireless 8260                                            | 3         | 4.41%   |
| Intel Wireless 7265                                            | 3         | 4.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 2.94%   |
| Qualcomm Atheros AR9271 802.11n                                | 2         | 2.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 2.94%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 2.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 2.94%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 1.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.47%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.47%   |
| Realtek RTL8187 Wireless Adapter                               | 1         | 1.47%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 1.47%   |
| Ralink RT3072 Wireless Adapter                                 | 1         | 1.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 1.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.47%   |
| NetGear WNDA3100v2 802.11abgn [Broadcom BCM4323]               | 1         | 1.47%   |
| NetGear A6210                                                  | 1         | 1.47%   |
| Intel Wireless 7260                                            | 1         | 1.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1.47%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 1.47%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.47%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 1.47%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.47%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.47%   |
| HP lt4120 Snapdragon X5 LTE                                    | 1         | 1.47%   |
| Fibocom L831-EAU                                               | 1         | 1.47%   |
| Edimax AC1200 USB                                              | 1         | 1.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 23        | 45.1%   |
| Intel                 | 17        | 33.33%  |
| Qualcomm Atheros      | 4         | 7.84%   |
| Broadcom              | 2         | 3.92%   |
| ASIX Electronics      | 2         | 3.92%   |
| Samsung Electronics   | 1         | 1.96%   |
| Lenovo                | 1         | 1.96%   |
| ICS Advent            | 1         | 1.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 30.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 7.69%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 5.77%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 3.85%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.92%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.92%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.92%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.92%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.92%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.92%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 1         | 1.92%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.92%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.92%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.92%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.92%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.92%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.92%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.92%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.92%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.92%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.92%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.92%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.92%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 1.92%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.92%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.92%   |
| ASIX AX88772B                                                     | 1         | 1.92%   |
| ASIX AX88772                                                      | 1         | 1.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 53        | 52.48%  |
| Ethernet | 47        | 46.53%  |
| Modem    | 1         | 0.99%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 66.07%  |
| Ethernet | 19        | 33.93%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 38        | 67.86%  |
| 1     | 16        | 28.57%  |
| 3     | 2         | 3.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 40        | 71.43%  |
| Yes  | 16        | 28.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 63.27%  |
| Qualcomm Atheros Communications | 4         | 8.16%   |
| Realtek Semiconductor           | 3         | 6.12%   |
| Lite-On Technology              | 3         | 6.12%   |
| Broadcom                        | 3         | 6.12%   |
| Logitech                        | 1         | 2.04%   |
| IMC Networks                    | 1         | 2.04%   |
| Dell                            | 1         | 2.04%   |
| Cambridge Silicon Radio         | 1         | 2.04%   |
| ASUSTek Computer                | 1         | 2.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 22.45%  |
| Intel AX201 Bluetooth                               | 11        | 22.45%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 12.24%  |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 8.16%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 4.08%   |
| Lite-On Bluetooth Device                            | 2         | 4.08%   |
| Realtek RTL8821A Bluetooth                          | 1         | 2.04%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1         | 2.04%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.04%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.04%   |
| Intel Bluetooth Device                              | 1         | 2.04%   |
| Intel AX200 Bluetooth                               | 1         | 2.04%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 2.04%   |
| Dell Wireless 360 Bluetooth                         | 1         | 2.04%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.04%   |
| Broadcom HP Portable SoftSailing                    | 1         | 2.04%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 2.04%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 2.04%   |
| ASUS BCM20702A0                                     | 1         | 2.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 51        | 63.75%  |
| AMD                       | 11        | 13.75%  |
| Nvidia                    | 10        | 12.5%   |
| Yamaha                    | 1         | 1.25%   |
| Texas Instruments         | 1         | 1.25%   |
| Sennheiser Communications | 1         | 1.25%   |
| Realtek Semiconductor     | 1         | 1.25%   |
| Logitech                  | 1         | 1.25%   |
| Lenovo                    | 1         | 1.25%   |
| C-Media Electronics       | 1         | 1.25%   |
| ASUSTek Computer          | 1         | 1.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 8.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 5.56%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 5.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 5.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 3.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 3.33%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 3.33%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 3.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 3.33%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 2.22%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 2.22%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 2.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 2.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 2.22%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 2.22%   |
| AMD FCH Azalia Controller                                                                         | 2         | 2.22%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 2.22%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 2.22%   |
| Yamaha AG06/AG03                                                                                  | 1         | 1.11%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 1.11%   |
| Sennheiser Communications EPOS BTD 800                                                            | 1         | 1.11%   |
| Realtek Semiconductor DIXON GAMING DN-GM30                                                        | 1         | 1.11%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.11%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.11%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 1.11%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 1.11%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 1.11%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.11%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.11%   |
| Logitech Logitech USB Microphone                                                                  | 1         | 1.11%   |
| Lenovo ThinkPad Dock Audio                                                                        | 1         | 1.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.11%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.11%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.11%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.11%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.11%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 17        | 31.48%  |
| SK hynix            | 12        | 22.22%  |
| Micron Technology   | 7         | 12.96%  |
| Kingston            | 6         | 11.11%  |
| Crucial             | 4         | 7.41%   |
| Corsair             | 3         | 5.56%   |
| Unifosa             | 1         | 1.85%   |
| Smart Brazil        | 1         | 1.85%   |
| Ramaxel Technology  | 1         | 1.85%   |
| Elpida              | 1         | 1.85%   |
| ASint Technology    | 1         | 1.85%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 3         | 5.45%   |
| Unifosa RAM GU332G0AJEPR8H2L.. 2GB SODIMM DDR2 667MT/s       | 1         | 1.82%   |
| Smart Brazil RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 2933MT/s | 1         | 1.82%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 1.82%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.82%   |
| SK hynix RAM HMAA4GS7AJR8N-XN 32GB SODIMM DDR4 3200MT/s      | 1         | 1.82%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.82%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 1.82%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.82%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.82%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 1         | 1.82%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 1         | 1.82%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 1         | 1.82%   |
| SK hynix RAM H9HCNNNBKMMLXR-NEE 1GB LPDDR4 3733MT/s          | 1         | 1.82%   |
| SK hynix RAM H9HCNNN8KUMLHR-NME 1GB LPDDR4 2400MT/s          | 1         | 1.82%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                    | 1         | 1.82%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR3 2133MT/s          | 1         | 1.82%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s        | 1         | 1.82%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.82%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.82%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s     | 1         | 1.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s  | 1         | 1.82%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 1.82%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 1.82%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.82%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 1         | 1.82%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s           | 1         | 1.82%   |
| Samsung RAM M378B5173QH0-CK0 4096MB DIMM DDR3 1600MT/s       | 1         | 1.82%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB SODIMM LPDDR4 2400MT/s       | 1         | 1.82%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 1         | 1.82%   |
| Micron RAM Module 1GB Row Of Chips LPDDR5 6400MT/s           | 1         | 1.82%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s        | 1         | 1.82%   |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s        | 1         | 1.82%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 1         | 1.82%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s       | 1         | 1.82%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s        | 1         | 1.82%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s        | 1         | 1.82%   |
| Kingston RAM KF3200C20S4/16G 16GB SODIMM DDR4 3200MT/s       | 1         | 1.82%   |
| Kingston RAM K821PJ-MID 16GB SODIMM DDR4 2400MT/s            | 1         | 1.82%   |
| Kingston RAM ACR26D4S9S8ME-8 8GB SODIMM DDR4 2667MT/s        | 1         | 1.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 28        | 59.57%  |
| DDR3   | 10        | 21.28%  |
| LPDDR4 | 3         | 6.38%   |
| SDRAM  | 2         | 4.26%   |
| LPDDR5 | 1         | 2.13%   |
| LPDDR3 | 1         | 2.13%   |
| DDR5   | 1         | 2.13%   |
| DDR2   | 1         | 2.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 36        | 76.6%   |
| DIMM         | 6         | 12.77%  |
| Row Of Chips | 3         | 6.38%   |
| Unknown      | 2         | 4.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 20        | 41.67%  |
| 4096  | 16        | 33.33%  |
| 16384 | 6         | 12.5%   |
| 2048  | 3         | 6.25%   |
| 1024  | 2         | 4.17%   |
| 32768 | 1         | 2.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 10        | 20.41%  |
| 3200  | 8         | 16.33%  |
| 1600  | 8         | 16.33%  |
| 2133  | 6         | 12.24%  |
| 2400  | 5         | 10.2%   |
| 3266  | 3         | 6.12%   |
| 4199  | 2         | 4.08%   |
| 6400  | 1         | 2.04%   |
| 4800  | 1         | 2.04%   |
| 3733  | 1         | 2.04%   |
| 2933  | 1         | 2.04%   |
| 2267  | 1         | 2.04%   |
| 1866  | 1         | 2.04%   |
| 667   | 1         | 2.04%   |

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
| Chicony Electronics                    | 10        | 20.41%  |
| Acer                                   | 7         | 14.29%  |
| Sunplus Innovation Technology          | 4         | 8.16%   |
| Microdia                               | 4         | 8.16%   |
| IMC Networks                           | 4         | 8.16%   |
| Realtek Semiconductor                  | 3         | 6.12%   |
| Quanta                                 | 3         | 6.12%   |
| Lite-On Technology                     | 3         | 6.12%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.08%   |
| Apple                                  | 2         | 4.08%   |
| Suyin                                  | 1         | 2.04%   |
| Sonix Technology                       | 1         | 2.04%   |
| Microsoft                              | 1         | 2.04%   |
| kingcome                               | 1         | 2.04%   |
| Generalplus Technology                 | 1         | 2.04%   |
| DJKANA19IDX53W                         | 1         | 2.04%   |
| Cubeternet                             | 1         | 2.04%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 4         | 8.16%   |
| Acer Integrated Camera                                         | 3         | 6.12%   |
| Sunplus HD WebCam                                              | 2         | 4.08%   |
| Realtek Integrated Webcam HD                                   | 2         | 4.08%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 4.08%   |
| Lite-On HP Wide Vision HD Camera                               | 2         | 4.08%   |
| Chicony HP TrueVision HD Camera                                | 2         | 4.08%   |
| Chicony HD User Facing                                         | 2         | 4.08%   |
| Acer HD Webcam                                                 | 2         | 4.08%   |
| Suyin HP Truevision HD                                         | 1         | 2.04%   |
| Sunplus FHD Camera Microphone                                  | 1         | 2.04%   |
| Sunplus 1080p FHD Camera                                       | 1         | 2.04%   |
| Sonix USB2.0 HD UVC WebCam                                     | 1         | 2.04%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 2.04%   |
| Quanta USB2.0 HD UVC WebCam                                    | 1         | 2.04%   |
| Quanta HD Webcam                                               | 1         | 2.04%   |
| Quanta HD User Facing                                          | 1         | 2.04%   |
| Microsoft Xbox NUI Camera                                      | 1         | 2.04%   |
| Microdia Sonix Integrated Webcam                               | 1         | 2.04%   |
| Microdia HP Integrated Webcam                                  | 1         | 2.04%   |
| Lite-On HP HD Webcam                                           | 1         | 2.04%   |
| kingcome 720p HD Camera                                        | 1         | 2.04%   |
| IMC Networks USB2.0 UVC HD Webcam                              | 1         | 2.04%   |
| IMC Networks Integrated Camera                                 | 1         | 2.04%   |
| IMC Networks EasyCamera                                        | 1         | 2.04%   |
| IMC Networks 2M Integrated Webcam                              | 1         | 2.04%   |
| Generalplus GENERAL WEBCAM                                     | 1         | 2.04%   |
| DJKANA19IDX53W HP Wide Vision HD Camera                        | 1         | 2.04%   |
| Cubeternet WebCam                                              | 1         | 2.04%   |
| Chicony Integrated Camera (1280x720@30)                        | 1         | 2.04%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 2.04%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 1         | 2.04%   |
| Apple FaceTime HD Camera (Built-in)                            | 1         | 2.04%   |
| Acer SunplusIT Integrated Camera                               | 1         | 2.04%   |
| Acer EasyCamera                                                | 1         | 2.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 42.86%  |
| Synaptics                  | 2         | 28.57%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |
| Elan Microelectronics      | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS491                           | 1         | 14.29%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 14.29%  |
| Validity Sensors Synaptics WBDI                   | 1         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 14.29%  |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 14.29%  |
| Shenzhen Goodix  FingerPrint Device               | 1         | 14.29%  |
| Elan ELAN:ARM-M4                                  | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./All/images/line_chart/chipcard_vendor.svg)

| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 80%     |
| Alcor Micro | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Broadcom 5880                       | 2         | 40%     |
| Broadcom 58200                      | 2         | 40%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 34        | 60.71%  |
| 1     | 16        | 28.57%  |
| 2     | 5         | 8.93%   |
| 4     | 1         | 1.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 8         | 28.57%  |
| Fingerprint reader       | 6         | 21.43%  |
| Chipcard                 | 5         | 17.86%  |
| Graphics card            | 3         | 10.71%  |
| Camera                   | 2         | 7.14%   |
| Bluetooth                | 2         | 7.14%   |
| Storage                  | 1         | 3.57%   |
| Communication controller | 1         | 3.57%   |

