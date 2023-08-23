Lubuntu - Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu/Desktop/README.md) and [notebooks](/Dist/Lubuntu/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: Jul, 2023.

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
| Lubuntu 22.04 | 21        | 58.33%  |
| Lubuntu 23.04 | 8         | 22.22%  |
| Lubuntu 20.04 | 3         | 8.33%   |
| Lubuntu 18.04 | 2         | 5.56%   |
| Lubuntu 22.10 | 1         | 2.78%   |
| Lubuntu 13.04 | 1         | 2.78%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Lubuntu | 36        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.19.0-46-generic             | 9         | 25%     |
| 5.19.0-50-generic             | 5         | 13.89%  |
| 6.2.0-25-generic              | 4         | 11.11%  |
| 5.15.0-76-generic             | 3         | 8.33%   |
| 6.2.0-24-generic              | 2         | 5.56%   |
| 6.2.0-20-generic              | 2         | 5.56%   |
| 5.19.0-32-generic             | 2         | 5.56%   |
| 5.4.0-42-generic              | 1         | 2.78%   |
| 5.4.0-150-generic             | 1         | 2.78%   |
| 5.4.0-132-generic             | 1         | 2.78%   |
| 5.19.0-45-generic             | 1         | 2.78%   |
| 5.19.0-15-generic             | 1         | 2.78%   |
| 5.19.0-1010-nvidia-lowlatency | 1         | 2.78%   |
| 5.15.0-35-generic             | 1         | 2.78%   |
| 5.11.0-051100-generic         | 1         | 2.78%   |
| 3.1.10-6-ac100                | 1         | 2.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19.0  | 19        | 52.78%  |
| 6.2.0   | 8         | 22.22%  |
| 5.15.0  | 4         | 11.11%  |
| 5.4.0   | 3         | 8.33%   |
| 5.11.0  | 1         | 2.78%   |
| 3.1.10  | 1         | 2.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19    | 19        | 52.78%  |
| 6.2     | 8         | 22.22%  |
| 5.15    | 4         | 11.11%  |
| 5.4     | 3         | 8.33%   |
| 5.11    | 1         | 2.78%   |
| 3.1     | 1         | 2.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 35        | 97.22%  |
| armv7l | 1         | 2.78%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| LXQt    | 29        | 80.56%  |
| LXDE    | 5         | 13.89%  |
| Lubuntu | 1         | 2.78%   |
| KDE5    | 1         | 2.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 34        | 94.44%  |
| Tty  | 2         | 5.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 27        | 75%     |
| LightDM | 4         | 11.11%  |
| Unknown | 4         | 11.11%  |
| GDM3    | 1         | 2.78%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 17        | 47.22%  |
| pt_BR | 4         | 11.11%  |
| fr_FR | 4         | 11.11%  |
| ru_RU | 2         | 5.56%   |
| C     | 2         | 5.56%   |
| es_MX | 1         | 2.78%   |
| es_AR | 1         | 2.78%   |
| en_IE | 1         | 2.78%   |
| en_AU | 1         | 2.78%   |
| de_DE | 1         | 2.78%   |
| da_DK | 1         | 2.78%   |
| cs_CZ | 1         | 2.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 18        | 50%     |
| EFI  | 18        | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 26        | 72.22%  |
| Tmpfs   | 6         | 16.67%  |
| Overlay | 2         | 5.56%   |
| Xfs     | 1         | 2.78%   |
| Btrfs   | 1         | 2.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 22        | 61.11%  |
| MBR     | 9         | 25%     |
| Unknown | 5         | 13.89%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 29        | 80.56%  |
| Yes       | 7         | 19.44%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 29        | 80.56%  |
| Yes       | 7         | 19.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| Dell             | 6         | 16.67%  |
| Unknown          | 5         | 13.89%  |
| Hewlett-Packard  | 4         | 11.11%  |
| Acer             | 4         | 11.11%  |
| ASUSTek Computer | 3         | 8.33%   |
| Apple            | 3         | 8.33%   |
| MSI              | 2         | 5.56%   |
| Lenovo           | 2         | 5.56%   |
| Shuttle          | 1         | 2.78%   |
| LG Electronics   | 1         | 2.78%   |
| Google           | 1         | 2.78%   |
| Gateway          | 1         | 2.78%   |
| Fujitsu          | 1         | 2.78%   |
| ASRock           | 1         | 2.78%   |
| AAEON            | 1         | 2.78%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 5         | 13.89%  |
| Shuttle XS35V3               | 1         | 2.78%   |
| MSI MS-7D54                  | 1         | 2.78%   |
| MSI MS-7721                  | 1         | 2.78%   |
| LG 15Z90N-U.ARS5U1           | 1         | 2.78%   |
| Lenovo ThinkPad T61 7659WCN  | 1         | 2.78%   |
| Lenovo ThinkPad T430 2349G7G | 1         | 2.78%   |
| HP t620 Dual Core TC         | 1         | 2.78%   |
| HP ProBook 4525s             | 1         | 2.78%   |
| HP Compaq 8000 Elite SFF PC  | 1         | 2.78%   |
| HP 255 G2                    | 1         | 2.78%   |
| Google Pyro                  | 1         | 2.78%   |
| Gateway ZX4250               | 1         | 2.78%   |
| Fujitsu FMVNC4BC4            | 1         | 2.78%   |
| Dell OptiPlex 360            | 1         | 2.78%   |
| Dell Latitude 5290           | 1         | 2.78%   |
| Dell Inspiron N5110          | 1         | 2.78%   |
| Dell Inspiron 5576           | 1         | 2.78%   |
| Dell Inspiron 1520           | 1         | 2.78%   |
| Dell Inspiron 13-5378        | 1         | 2.78%   |
| ASUS TUF Gaming X570-PLUS    | 1         | 2.78%   |
| ASUS ROG Strix G733QR_G733QR | 1         | 2.78%   |
| ASUS P5G41T-M LX2/BR         | 1         | 2.78%   |
| ASRock 970M Pro3             | 1         | 2.78%   |
| Apple MacPro3,1              | 1         | 2.78%   |
| Apple Macmini3,1             | 1         | 2.78%   |
| Apple iMac7,1                | 1         | 2.78%   |
| Acer Swift SFE16-42          | 1         | 2.78%   |
| Acer Aspire SW3-013          | 1         | 2.78%   |
| Acer Aspire E5-523G          | 1         | 2.78%   |
| Acer Aspire E1-771           | 1         | 2.78%   |
| AAEON MF-001                 | 1         | 2.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Unknown            | 5         | 13.89%  |
| Dell Inspiron      | 4         | 11.11%  |
| Acer Aspire        | 3         | 8.33%   |
| Lenovo ThinkPad    | 2         | 5.56%   |
| Shuttle XS35V3     | 1         | 2.78%   |
| MSI MS-7D54        | 1         | 2.78%   |
| MSI MS-7721        | 1         | 2.78%   |
| LG 15Z90N-U.ARS5U1 | 1         | 2.78%   |
| HP t620            | 1         | 2.78%   |
| HP ProBook         | 1         | 2.78%   |
| HP Compaq          | 1         | 2.78%   |
| HP 255             | 1         | 2.78%   |
| Google Pyro        | 1         | 2.78%   |
| Gateway ZX4250     | 1         | 2.78%   |
| Fujitsu FMVNC4BC4  | 1         | 2.78%   |
| Dell OptiPlex      | 1         | 2.78%   |
| Dell Latitude      | 1         | 2.78%   |
| ASUS TUF           | 1         | 2.78%   |
| ASUS ROG           | 1         | 2.78%   |
| ASUS P5G41T-M      | 1         | 2.78%   |
| ASRock 970M        | 1         | 2.78%   |
| Apple MacPro3      | 1         | 2.78%   |
| Apple Macmini3     | 1         | 2.78%   |
| Apple iMac7        | 1         | 2.78%   |
| Acer Swift         | 1         | 2.78%   |
| AAEON MF-001       | 1         | 2.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year    | Computers | Percent |
|---------|-----------|---------|
| 2007    | 4         | 11.11%  |
| 2019    | 3         | 8.33%   |
| 2015    | 3         | 8.33%   |
| 2013    | 3         | 8.33%   |
| 2012    | 3         | 8.33%   |
| 2009    | 3         | 8.33%   |
| 2008    | 3         | 8.33%   |
| 2021    | 2         | 5.56%   |
| 2020    | 2         | 5.56%   |
| 2017    | 2         | 5.56%   |
| 2016    | 2         | 5.56%   |
| 2010    | 2         | 5.56%   |
| 2023    | 1         | 2.78%   |
| 2022    | 1         | 2.78%   |
| 2011    | 1         | 2.78%   |
| Unknown | 1         | 2.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 18        | 50%     |
| Desktop    | 14        | 38.89%  |
| All in one | 2         | 5.56%   |
| Other      | 1         | 2.78%   |
| Mini pc    | 1         | 2.78%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 34        | 94.44%  |
| Enabled  | 2         | 5.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 35        | 97.22%  |
| Yes  | 1         | 2.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 9         | 25%     |
| 1.01-2.0   | 8         | 22.22%  |
| 4.01-8.0   | 7         | 19.44%  |
| 32.01-64.0 | 5         | 13.89%  |
| 8.01-16.0  | 4         | 11.11%  |
| 2.01-3.0   | 1         | 2.78%   |
| 16.01-24.0 | 1         | 2.78%   |
| 0.01-0.5   | 1         | 2.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 13        | 36.11%  |
| 2.01-3.0   | 8         | 22.22%  |
| 0.51-1.0   | 7         | 19.44%  |
| 4.01-8.0   | 4         | 11.11%  |
| 3.01-4.0   | 1         | 2.78%   |
| 16.01-24.0 | 1         | 2.78%   |
| 8.01-16.0  | 1         | 2.78%   |
| Unknown    | 1         | 2.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 23        | 63.89%  |
| 2      | 9         | 25%     |
| 3      | 2         | 5.56%   |
| 8      | 1         | 2.78%   |
| 4      | 1         | 2.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 20        | 55.56%  |
| Yes       | 16        | 44.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 83.33%  |
| No        | 6         | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 72.22%  |
| No        | 10        | 27.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 58.33%  |
| No        | 15        | 41.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 7         | 19.44%  |
| Brazil       | 5         | 13.89%  |
| France       | 4         | 11.11%  |
| Russia       | 3         | 8.33%   |
| Sweden       | 2         | 5.56%   |
| Indonesia    | 2         | 5.56%   |
| South Africa | 1         | 2.78%   |
| Pakistan     | 1         | 2.78%   |
| Mexico       | 1         | 2.78%   |
| Luxembourg   | 1         | 2.78%   |
| Lithuania    | 1         | 2.78%   |
| Israel       | 1         | 2.78%   |
| Ireland      | 1         | 2.78%   |
| India        | 1         | 2.78%   |
| Germany      | 1         | 2.78%   |
| Denmark      | 1         | 2.78%   |
| Czechia      | 1         | 2.78%   |
| Australia    | 1         | 2.78%   |
| Argentina    | 1         | 2.78%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City                | Computers | Percent |
|---------------------|-----------|---------|
| Brasília           | 2         | 5.56%   |
| Yogyakarta          | 1         | 2.78%   |
| West Jordan         | 1         | 2.78%   |
| Ufa                 | 1         | 2.78%   |
| Trabuco Canyon      | 1         | 2.78%   |
| Tolyatti            | 1         | 2.78%   |
| Santa Fe            | 1         | 2.78%   |
| Saint-Jean-le-Blanc | 1         | 2.78%   |
| Prague              | 1         | 2.78%   |
| Paris               | 1         | 2.78%   |
| Nova Iguaçu        | 1         | 2.78%   |
| Mumbai              | 1         | 2.78%   |
| Monterrey           | 1         | 2.78%   |
| Mogi Guacu          | 1         | 2.78%   |
| Melbourne           | 1         | 2.78%   |
| Luxembourg          | 1         | 2.78%   |
| Lipetsk             | 1         | 2.78%   |
| Lattes              | 1         | 2.78%   |
| Kaunas              | 1         | 2.78%   |
| Karlstad            | 1         | 2.78%   |
| Karachi             | 1         | 2.78%   |
| Jakarta             | 1         | 2.78%   |
| Houston             | 1         | 2.78%   |
| Holstebro           | 1         | 2.78%   |
| Hod HaSharon        | 1         | 2.78%   |
| Gonesse             | 1         | 2.78%   |
| Flanders            | 1         | 2.78%   |
| Escondido           | 1         | 2.78%   |
| Enkoeping           | 1         | 2.78%   |
| Durban              | 1         | 2.78%   |
| Craughwell          | 1         | 2.78%   |
| Charlotte           | 1         | 2.78%   |
| Bonn                | 1         | 2.78%   |
| Belo Horizonte      | 1         | 2.78%   |
| Bellingham          | 1         | 2.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 14%     |
| Seagate             | 7         | 9      | 14%     |
| Samsung Electronics | 7         | 10     | 14%     |
| Kingston            | 5         | 5      | 10%     |
| Toshiba             | 3         | 4      | 6%      |
| SK hynix            | 3         | 3      | 6%      |
| Unknown             | 3         | 3      | 6%      |
| Unknown             | 2         | 2      | 4%      |
| SanDisk             | 2         | 2      | 4%      |
| Hitachi             | 2         | 2      | 4%      |
| WALRAM              | 1         | 1      | 2%      |
| Transcend           | 1         | 1      | 2%      |
| Micron Technology   | 1         | 1      | 2%      |
| KingSpec            | 1         | 1      | 2%      |
| JMicron Technology  | 1         | 1      | 2%      |
| Crucial             | 1         | 1      | 2%      |
| China               | 1         | 1      | 2%      |
| Apple               | 1         | 1      | 2%      |
| A-DATA Technology   | 1         | 1      | 2%      |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD               | 3         | 5.56%   |
| Unknown                                       | 3         | 5.56%   |
| WDC WDS480G2G0A-00JH30 480GB SSD              | 1         | 1.85%   |
| WDC WD800JD-75MSA3 80GB                       | 1         | 1.85%   |
| WDC WD5000BPVT-75HXZT1 500GB                  | 1         | 1.85%   |
| WDC WD5000AAKX-00ERMA0 500GB                  | 1         | 1.85%   |
| WDC WD30EZRX-00D8PB0 3TB                      | 1         | 1.85%   |
| WDC WD10JPVX-22JC3T0 1TB                      | 1         | 1.85%   |
| WDC WD Green 2.5 240GB SSD                    | 1         | 1.85%   |
| WALRAM SSD 240G                               | 1         | 1.85%   |
| Unknown MMC Card  16GB                        | 1         | 1.85%   |
| Unknown M52516  16GB                          | 1         | 1.85%   |
| Transcend TS256GSSD720 256GB                  | 1         | 1.85%   |
| Toshiba MQ01ABD100 1TB                        | 1         | 1.85%   |
| Toshiba MK2556GSY 250GB                       | 1         | 1.85%   |
| Toshiba DT01ACA300 3TB                        | 1         | 1.85%   |
| SK hynix HFS256GD9TNG-L2A0A 256GB             | 1         | 1.85%   |
| SK hynix HFM001TD3JX013N 1TB                  | 1         | 1.85%   |
| SK hynix HBG4e  32GB                          | 1         | 1.85%   |
| Seagate ST9160314AS 160GB                     | 1         | 1.85%   |
| Seagate ST6000DM001-1XY17Z 6TB                | 1         | 1.85%   |
| Seagate ST4000VN008-2DR166 4TB                | 1         | 1.85%   |
| Seagate ST4000DM004-2U9104 4TB                | 1         | 1.85%   |
| Seagate ST3500312CS 500GB                     | 1         | 1.85%   |
| Seagate ST3000DM001-9YN166 3TB                | 1         | 1.85%   |
| Seagate ST1000LM035-1RK172 1TB                | 1         | 1.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB            | 1         | 1.85%   |
| SanDisk SDSA6MM-032G-1006 32GB SSD            | 1         | 1.85%   |
| SanDisk DF4032  32GB                          | 1         | 1.85%   |
| Samsung SSD 980 PRO 2TB                       | 1         | 1.85%   |
| Samsung SSD 970 EVO Plus 500GB                | 1         | 1.85%   |
| Samsung SSD 970 EVO Plus 250GB                | 1         | 1.85%   |
| Samsung SSD 870 EVO 1TB                       | 1         | 1.85%   |
| Samsung SSD 840 PRO Series 256GB              | 1         | 1.85%   |
| Samsung SSD 840 PRO Series 128GB              | 1         | 1.85%   |
| Samsung NVMe SSD Controller SM951/PM951 128GB | 1         | 1.85%   |
| Samsung HM160HI 160GB                         | 1         | 1.85%   |
| Samsung HD103SJ 1TB                           | 1         | 1.85%   |
| Samsung CJNB4R  64GB                          | 1         | 1.85%   |
| Micron 3400_MTFDKBA1T0TFH 1TB                 | 1         | 1.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 9      | 33.33%  |
| WDC                 | 5         | 5      | 23.81%  |
| Toshiba             | 3         | 4      | 14.29%  |
| Samsung Electronics | 2         | 2      | 9.52%   |
| Hitachi             | 2         | 2      | 9.52%   |
| JMicron Technology  | 1         | 1      | 4.76%   |
| Apple               | 1         | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 5         | 5      | 31.25%  |
| Samsung Electronics | 3         | 3      | 18.75%  |
| WDC                 | 2         | 2      | 12.5%   |
| WALRAM              | 1         | 1      | 6.25%   |
| Transcend           | 1         | 1      | 6.25%   |
| SanDisk             | 1         | 1      | 6.25%   |
| KingSpec            | 1         | 1      | 6.25%   |
| China               | 1         | 1      | 6.25%   |
| A-DATA Technology   | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 24     | 36.36%  |
| SSD  | 15        | 16     | 34.09%  |
| MMC  | 8         | 8      | 18.18%  |
| NVMe | 5         | 8      | 11.36%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 27        | 39     | 65.85%  |
| MMC  | 8         | 8      | 19.51%  |
| NVMe | 5         | 8      | 12.2%   |
| SAS  | 1         | 1      | 2.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 22        | 23     | 62.86%  |
| 0.51-1.0   | 6         | 8      | 17.14%  |
| 2.01-3.0   | 3         | 4      | 8.57%   |
| 3.01-4.0   | 2         | 3      | 5.71%   |
| 1.01-2.0   | 1         | 1      | 2.86%   |
| 4.01-10.0  | 1         | 1      | 2.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 14        | 38.89%  |
| 251-500        | 5         | 13.89%  |
| 1-20           | 5         | 13.89%  |
| 501-1000       | 4         | 11.11%  |
| 21-50          | 3         | 8.33%   |
| More than 3000 | 2         | 5.56%   |
| 51-100         | 2         | 5.56%   |
| 2001-3000      | 1         | 2.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 20        | 55.56%  |
| 101-250        | 6         | 16.67%  |
| 21-50          | 3         | 8.33%   |
| More than 3000 | 2         | 5.56%   |
| 251-500        | 2         | 5.56%   |
| 2001-3000      | 1         | 2.78%   |
| 501-1000       | 1         | 2.78%   |
| 51-100         | 1         | 2.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD    | 1         | 1      | 12.5%   |
| WDC WD5000BPVT-75HXZT1 500GB        | 1         | 1      | 12.5%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 1      | 12.5%   |
| Transcend TS256GSSD720 256GB        | 1         | 1      | 12.5%   |
| Toshiba MK2556GSY 250GB             | 1         | 1      | 12.5%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 12.5%   |
| Samsung Electronics SSD 870 EVO 1TB | 1         | 1      | 12.5%   |
| Apple HDD HTS547550A9E384 500GB     | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 37.5%   |
| Transcend           | 1         | 1      | 12.5%   |
| Toshiba             | 1         | 1      | 12.5%   |
| Seagate             | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| Apple               | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 40%     |
| Toshiba | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |
| Apple   | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 62.5%   |
| SSD  | 3         | 3      | 37.5%   |

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
| Detected | 19        | 24     | 47.5%   |
| Works    | 13        | 24     | 32.5%   |
| Malfunc  | 8         | 8      | 20%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 17        | 47.22%  |
| AMD                       | 10        | 27.78%  |
| Samsung Electronics       | 3         | 8.33%   |
| SK hynix                  | 2         | 5.56%   |
| Nvidia                    | 1         | 2.78%   |
| Micron/Crucial Technology | 1         | 2.78%   |
| Micron Technology         | 1         | 2.78%   |
| ASMedia Technology        | 1         | 2.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 7         | 14.89%  |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 3         | 6.38%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 3         | 6.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 2         | 4.26%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                            | 2         | 4.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                 | 2         | 4.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 2         | 4.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 2         | 4.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 2         | 4.26%   |
| SK hynix PC601 NVMe Solid State Drive                                        | 1         | 2.13%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 1         | 2.13%   |
| Samsung NVMe SSD Controller SM951/PM951                                      | 1         | 2.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 1         | 2.13%   |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 2.13%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                     | 1         | 2.13%   |
| Micron 3400 NVMe SSD [Hendrix]                                               | 1         | 2.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 1         | 2.13%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 1         | 2.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 1         | 2.13%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                   | 1         | 2.13%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                   | 1         | 2.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 2.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 1         | 2.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 1         | 2.13%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                   | 1         | 2.13%   |
| Intel 631xESB/632xESB IDE Controller                                         | 1         | 2.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 1         | 2.13%   |
| Intel 4 Series Chipset PT IDER Controller                                    | 1         | 2.13%   |
| ASMedia ASM1062 Serial ATA Controller                                        | 1         | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                             | 1         | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                         | 1         | 2.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 22        | 57.89%  |
| IDE  | 10        | 26.32%  |
| NVMe | 5         | 13.16%  |
| RAID | 1         | 2.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 23        | 63.89%  |
| AMD     | 12        | 33.33%  |
| Unknown | 1         | 2.78%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU T7300 @ 2.00GHz            | 2         | 5.56%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 2         | 5.56%   |
| Intel Xeon CPU X5472 @ 3.00GHz                  | 1         | 2.78%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz     | 1         | 2.78%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 2.78%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 1         | 2.78%   |
| Intel Core i5-7300U CPU @ 2.60GHz               | 1         | 2.78%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 1         | 2.78%   |
| Intel Core i5-1035G7 CPU @ 1.20GHz              | 1         | 2.78%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 1         | 2.78%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz           | 1         | 2.78%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz            | 1         | 2.78%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz            | 1         | 2.78%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 1         | 2.78%   |
| Intel Core 2 CPU T5500 @ 1.66GHz                | 1         | 2.78%   |
| Intel Celeron CPU N3450 @ 1.10GHz               | 1         | 2.78%   |
| Intel Celeron CPU J3355 @ 2.00GHz               | 1         | 2.78%   |
| Intel Celeron CPU 450 @ 2.20GHz                 | 1         | 2.78%   |
| Intel Atom CPU Z3735F @ 1.33GHz                 | 1         | 2.78%   |
| Intel Atom CPU D510 @ 1.66GHz                   | 1         | 2.78%   |
| Intel Atom CPU D2550 @ 1.86GHz                  | 1         | 2.78%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 1         | 2.78%   |
| AMD Ryzen 9 5900HX with Radeon Graphics         | 1         | 2.78%   |
| AMD Ryzen 7 7735U with Radeon Graphics          | 1         | 2.78%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 1         | 2.78%   |
| AMD GX-217GA SOC with Radeon HD Graphics        | 1         | 2.78%   |
| AMD FX-6300 Six-Core Processor                  | 1         | 2.78%   |
| AMD E2-3800 APU with Radeon HD Graphics         | 1         | 2.78%   |
| AMD E-350 APU with Radeon HD Graphics           | 1         | 2.78%   |
| AMD Athlon II P320 Dual-Core Processor          | 1         | 2.78%   |
| AMD A6-9210 RADEON R4, 5 COMPUTE CORES 2C+3G    | 1         | 2.78%   |
| AMD A10-9630P RADEON R5, 10 COMPUTE CORES 4C+6G | 1         | 2.78%   |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 1         | 2.78%   |
|                                                 | 1         | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core 2 Duo        | 5         | 13.89%  |
| Intel Atom              | 5         | 13.89%  |
| Intel Core i5           | 3         | 8.33%   |
| Intel Celeron           | 3         | 8.33%   |
| Intel Core i7           | 2         | 5.56%   |
| AMD Ryzen 9             | 2         | 5.56%   |
| AMD A10                 | 2         | 5.56%   |
| Other                   | 1         | 2.78%   |
| Intel Xeon              | 1         | 2.78%   |
| Intel Pentium Dual-Core | 1         | 2.78%   |
| Intel Core i3           | 1         | 2.78%   |
| Intel Core 2 Quad       | 1         | 2.78%   |
| Intel Core 2            | 1         | 2.78%   |
| AMD Ryzen 7             | 1         | 2.78%   |
| AMD Ryzen 5             | 1         | 2.78%   |
| AMD GX                  | 1         | 2.78%   |
| AMD FX                  | 1         | 2.78%   |
| AMD E2                  | 1         | 2.78%   |
| AMD E                   | 1         | 2.78%   |
| AMD Athlon II           | 1         | 2.78%   |
| AMD A6                  | 1         | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 22        | 61.11%  |
| 4      | 7         | 19.44%  |
| 8      | 3         | 8.33%   |
| 12     | 1         | 2.78%   |
| 6      | 1         | 2.78%   |
| 3      | 1         | 2.78%   |
| 1      | 1         | 2.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 34        | 94.44%  |
| 2      | 2         | 5.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 58.33%  |
| 2      | 15        | 41.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 35        | 97.22%  |
| Unknown        | 1         | 2.78%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 38.89%  |
| 0x1067a    | 3         | 8.33%   |
| 0x506c9    | 2         | 5.56%   |
| 0x406c4    | 2         | 5.56%   |
| 0x0700010f | 2         | 5.56%   |
| 0x806e9    | 1         | 2.78%   |
| 0x6fb      | 1         | 2.78%   |
| 0x306a9    | 1         | 2.78%   |
| 0x30678    | 1         | 2.78%   |
| 0x206a7    | 1         | 2.78%   |
| 0x10661    | 1         | 2.78%   |
| 0x0a50000d | 1         | 2.78%   |
| 0x0a50000b | 1         | 2.78%   |
| 0x0a404102 | 1         | 2.78%   |
| 0x06006704 | 1         | 2.78%   |
| 0x06000852 | 1         | 2.78%   |
| 0x05000119 | 1         | 2.78%   |
| 0x010000c8 | 1         | 2.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Penryn      | 5         | 13.89%  |
| Core        | 5         | 13.89%  |
| Zen 3       | 3         | 8.33%   |
| Silvermont  | 3         | 8.33%   |
| KabyLake    | 2         | 5.56%   |
| Jaguar      | 2         | 5.56%   |
| IvyBridge   | 2         | 5.56%   |
| Goldmont    | 2         | 5.56%   |
| Excavator   | 2         | 5.56%   |
| Bonnell     | 2         | 5.56%   |
| Unknown     | 2         | 5.56%   |
| Steamroller | 1         | 2.78%   |
| SandyBridge | 1         | 2.78%   |
| Piledriver  | 1         | 2.78%   |
| K10         | 1         | 2.78%   |
| IceLake     | 1         | 2.78%   |
| Bobcat      | 1         | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 18        | 46.15%  |
| AMD    | 12        | 30.77%  |
| Nvidia | 9         | 23.08%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 2         | 4.65%   |
| Intel HD Graphics 500                                                                    | 2         | 4.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 4.65%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 4.65%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 4.65%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 2.33%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 2.33%   |
| Nvidia GF108M [NVS 5400M]                                                                | 1         | 2.33%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 2.33%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 2.33%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 1         | 2.33%   |
| Nvidia G92 [GeForce 8800 GT]                                                             | 1         | 2.33%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 2.33%   |
| Nvidia C79 [GeForce 9400]                                                                | 1         | 2.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.33%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 2.33%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 2.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.33%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 2.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 2.33%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 2.33%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 2.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 2.33%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 2.33%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 2.33%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 2.33%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 2.33%   |
| AMD Seymour LP [Radeon HD 6430M]                                                         | 1         | 2.33%   |
| AMD RV610/M74 [Mobility Radeon HD 2400 XT]                                               | 1         | 2.33%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 2.33%   |
| AMD Rembrandt [Radeon 680M]                                                              | 1         | 2.33%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 1         | 2.33%   |
| AMD Kabini [Radeon HD 8280E]                                                             | 1         | 2.33%   |
| AMD Kabini [Radeon HD 8280 / R3 Series]                                                  | 1         | 2.33%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1         | 2.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1         | 2.33%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1         | 2.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 14        | 38.89%  |
| 1 x AMD        | 9         | 25%     |
| 1 x Nvidia     | 5         | 13.89%  |
| Intel + Nvidia | 3         | 8.33%   |
| Other          | 2         | 5.56%   |
| 2 x AMD        | 2         | 5.56%   |
| AMD + Nvidia   | 1         | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 29        | 80.56%  |
| Proprietary | 4         | 11.11%  |
| Unknown     | 3         | 8.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 66.67%  |
| 0.01-0.5   | 7         | 19.44%  |
| 0.51-1.0   | 2         | 5.56%   |
| 7.01-8.0   | 1         | 2.78%   |
| 3.01-4.0   | 1         | 2.78%   |
| 1.01-2.0   | 1         | 2.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| LG Display          | 7         | 21.88%  |
| Samsung Electronics | 3         | 9.38%   |
| AU Optronics        | 3         | 9.38%   |
| Apple               | 2         | 6.25%   |
| AOC                 | 2         | 6.25%   |
| Acer                | 2         | 6.25%   |
| ViewSonic           | 1         | 3.13%   |
| Unknown             | 1         | 3.13%   |
| Sharp               | 1         | 3.13%   |
| Philips             | 1         | 3.13%   |
| Lenovo              | 1         | 3.13%   |
| Iiyama              | 1         | 3.13%   |
| HannStar            | 1         | 3.13%   |
| Goldstar            | 1         | 3.13%   |
| Dell                | 1         | 3.13%   |
| Chimei Innolux      | 1         | 3.13%   |
| BOE                 | 1         | 3.13%   |
| BenQ                | 1         | 3.13%   |
| ASUSTek Computer    | 1         | 3.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch         | 1         | 2.94%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1         | 2.94%   |
| Sharp LQ173M1JW04 SHP14E1 1920x1080 382x215mm 17.3-inch               | 1         | 2.94%   |
| Samsung Electronics S23C570 SAM0A57 1920x1080 510x287mm 23.0-inch     | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch  | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SDC416B 3840x2400 344x215mm 16.0-inch | 1         | 2.94%   |
| Philips PHL 272E1GJ PHLC245 1920x1080 598x336mm 27.0-inch             | 1         | 2.94%   |
| LG Display LP156WH2-TLRA LGD026B 1366x768 344x194mm 15.5-inch         | 1         | 2.94%   |
| LG Display LCD Monitor LGD0645 1920x1080 344x194mm 15.5-inch          | 1         | 2.94%   |
| LG Display LCD Monitor LGD0506 1366x768 344x194mm 15.5-inch           | 1         | 2.94%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 2.94%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 1         | 2.94%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 1         | 2.94%   |
| LG Display LCD Monitor LGD01F6 1280x800 331x207mm 15.4-inch           | 1         | 2.94%   |
| Lenovo LCD Monitor LEN4031 1280x800 303x190mm 14.1-inch               | 1         | 2.94%   |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                  | 1         | 2.94%   |
| Iiyama PL2791Q IVM6646 2560x1440 597x336mm 27.0-inch                  | 1         | 2.94%   |
| HannStar Hanns.G HW173 HSD5A47 1440x900 408x255mm 18.9-inch           | 1         | 2.94%   |
| Goldstar E2241 GSM581A 1920x1080 477x268mm 21.5-inch                  | 1         | 2.94%   |
| Goldstar E2241 GSM5818 1920x1080 477x268mm 21.5-inch                  | 1         | 2.94%   |
| Dell S2721QS DELA198 3840x2160 597x336mm 27.0-inch                    | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN1138 1366x768 256x144mm 11.6-inch       | 1         | 2.94%   |
| BOE LCD Monitor BOE06A7 1920x1080 294x165mm 13.3-inch                 | 1         | 2.94%   |
| BenQ GL2450 BNQ78A4 1920x1080 531x298mm 24.0-inch                     | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch         | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 1         | 2.94%   |
| ASUSTek Computer MB16A AUS164B 1920x1080 344x194mm 15.5-inch          | 1         | 2.94%   |
| Apple Color LCD APP9C6A 1680x1050 433x270mm 20.1-inch                 | 1         | 2.94%   |
| Apple Cinema HD APP9221 2560x1600 641x401mm 29.8-inch                 | 1         | 2.94%   |
| AOC 2236 AOC2236 1920x1080 477x268mm 21.5-inch                        | 1         | 2.94%   |
| AOC 1670W AOC1670 1366x768 344x194mm 15.5-inch                        | 1         | 2.94%   |
| Acer LCD Monitor ACR285A 1600x900 442x249mm 20.0-inch                 | 1         | 2.94%   |
| Acer AL1707 A ACRAD46 1280x1024 338x270mm 17.0-inch                   | 1         | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 13        | 40.63%  |
| 1366x768 (WXGA)    | 7         | 21.88%  |
| 1600x900 (HD+)     | 2         | 6.25%   |
| 1440x900 (WXGA+)   | 2         | 6.25%   |
| 1280x800 (WXGA)    | 2         | 6.25%   |
| 3840x2400          | 1         | 3.13%   |
| 3840x2160 (4K)     | 1         | 3.13%   |
| 2560x1600          | 1         | 3.13%   |
| 2560x1440 (QHD)    | 1         | 3.13%   |
| 1680x1050 (WSXGA+) | 1         | 3.13%   |
| 1280x1024 (SXGA)   | 1         | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 9         | 28.13%  |
| 27      | 3         | 9.38%   |
| 24      | 3         | 9.38%   |
| 17      | 3         | 9.38%   |
| 14      | 3         | 9.38%   |
| 21      | 2         | 6.25%   |
| 29      | 1         | 3.13%   |
| 23      | 1         | 3.13%   |
| 20      | 1         | 3.13%   |
| 18      | 1         | 3.13%   |
| 16      | 1         | 3.13%   |
| 13      | 1         | 3.13%   |
| 12      | 1         | 3.13%   |
| 11      | 1         | 3.13%   |
| Unknown | 1         | 3.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 41.94%  |
| 501-600     | 7         | 22.58%  |
| 401-500     | 4         | 12.9%   |
| 201-300     | 3         | 9.68%   |
| 351-400     | 2         | 6.45%   |
| 601-700     | 1         | 3.23%   |
| Unknown     | 1         | 3.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 21        | 70%     |
| 16/10   | 7         | 23.33%  |
| 5/4     | 1         | 3.33%   |
| Unknown | 1         | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 9         | 28.13%  |
| 201-250        | 5         | 15.63%  |
| 81-90          | 3         | 9.38%   |
| 301-350        | 3         | 9.38%   |
| 151-200        | 3         | 9.38%   |
| 121-130        | 2         | 6.25%   |
| 71-80          | 1         | 3.13%   |
| 61-70          | 1         | 3.13%   |
| 51-60          | 1         | 3.13%   |
| 351-500        | 1         | 3.13%   |
| 141-150        | 1         | 3.13%   |
| 111-120        | 1         | 3.13%   |
| Unknown        | 1         | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 12        | 37.5%   |
| 51-100        | 10        | 31.25%  |
| 121-160       | 6         | 18.75%  |
| 161-240       | 2         | 6.25%   |
| More than 240 | 1         | 3.13%   |
| Unknown       | 1         | 3.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 30        | 83.33%  |
| 2     | 3         | 8.33%   |
| 0     | 2         | 5.56%   |
| 3     | 1         | 2.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 18        | 33.96%  |
| Intel                    | 12        | 22.64%  |
| Qualcomm Atheros         | 7         | 13.21%  |
| Broadcom                 | 4         | 7.55%   |
| Ralink Technology        | 2         | 3.77%   |
| NetGear                  | 2         | 3.77%   |
| Marvell Technology Group | 2         | 3.77%   |
| Xiaomi                   | 1         | 1.89%   |
| Samsung Electronics      | 1         | 1.89%   |
| Nvidia                   | 1         | 1.89%   |
| Micro Star International | 1         | 1.89%   |
| MediaTek                 | 1         | 1.89%   |
| Broadcom Limited         | 1         | 1.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 15        | 24.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 2         | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 3.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 3.23%   |
| Intel Wireless-AC 9260                                                  | 2         | 3.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 1.61%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 1.61%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.61%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 1.61%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 1.61%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 1.61%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 1.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 1.61%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.61%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 1.61%   |
| NetGear LB1120-100NAS                                                   | 1         | 1.61%   |
| NetGear A6210                                                           | 1         | 1.61%   |
| Micro Star International 802.11 n WLAN                                  | 1         | 1.61%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.61%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 1         | 1.61%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 1         | 1.61%   |
| Intel Wireless 8265 / 8275                                              | 1         | 1.61%   |
| Intel Wireless 7265                                                     | 1         | 1.61%   |
| Intel Wireless 3165                                                     | 1         | 1.61%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.61%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.61%   |
| Intel Ethernet Connection (4) I219-LM                                   | 1         | 1.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.61%   |
| Intel 82583V Gigabit Network Connection                                 | 1         | 1.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 1         | 1.61%   |
| Intel 82567V-3 Gigabit Network Connection                               | 1         | 1.61%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 1         | 1.61%   |
| Intel 82566MM Gigabit Network Connection                                | 1         | 1.61%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                  | 1         | 1.61%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                         | 1         | 1.61%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                  | 1         | 1.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 9         | 33.33%  |
| Qualcomm Atheros         | 7         | 25.93%  |
| Broadcom                 | 3         | 11.11%  |
| Realtek Semiconductor    | 2         | 7.41%   |
| Ralink Technology        | 2         | 7.41%   |
| NetGear                  | 1         | 3.7%    |
| Micro Star International | 1         | 3.7%    |
| MediaTek                 | 1         | 3.7%    |
| Broadcom Limited         | 1         | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 7.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 7.14%   |
| Intel Wireless-AC 9260                                                  | 2         | 7.14%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 3.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 3.57%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 3.57%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 3.57%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 3.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 3.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 3.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 3.57%   |
| NetGear A6210                                                           | 1         | 3.57%   |
| Micro Star International 802.11 n WLAN                                  | 1         | 3.57%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 3.57%   |
| Intel Wireless 8265 / 8275                                              | 1         | 3.57%   |
| Intel Wireless 7265                                                     | 1         | 3.57%   |
| Intel Wireless 3165                                                     | 1         | 3.57%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 3.57%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 3.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 3.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 3.57%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                  | 1         | 3.57%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 3.57%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 3.57%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 1         | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 18        | 54.55%  |
| Intel                    | 6         | 18.18%  |
| Marvell Technology Group | 2         | 6.06%   |
| Broadcom                 | 2         | 6.06%   |
| Xiaomi                   | 1         | 3.03%   |
| Samsung Electronics      | 1         | 3.03%   |
| Qualcomm Atheros         | 1         | 3.03%   |
| Nvidia                   | 1         | 3.03%   |
| NetGear                  | 1         | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 44.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 5.88%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.94%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.94%   |
| Nvidia MCP79 Ethernet                                             | 1         | 2.94%   |
| NetGear LB1120-100NAS                                             | 1         | 2.94%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 2.94%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 2.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.94%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 2.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.94%   |
| Intel 82567V-3 Gigabit Network Connection                         | 1         | 2.94%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 2.94%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2.94%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1         | 2.94%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 2.94%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 2.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 30        | 53.57%  |
| WiFi     | 26        | 46.43%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 54.05%  |
| Ethernet | 17        | 45.95%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 20        | 55.56%  |
| 1     | 14        | 38.89%  |
| 0     | 2         | 5.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 29        | 80.56%  |
| Yes  | 7         | 19.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 7         | 33.33%  |
| Qualcomm Atheros Communications | 3         | 14.29%  |
| Apple                           | 3         | 14.29%  |
| Lite-On Technology              | 2         | 9.52%   |
| Broadcom                        | 2         | 9.52%   |
| Micro Star International        | 1         | 4.76%   |
| Hewlett-Packard                 | 1         | 4.76%   |
| Foxconn / Hon Hai               | 1         | 4.76%   |
| Cambridge Silicon Radio         | 1         | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 3         | 14.29%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 9.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 9.52%   |
| Apple Bluetooth HCI                                 | 2         | 9.52%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 4.76%   |
| Micro Star International Bluetooth Device           | 1         | 4.76%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 4.76%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 4.76%   |
| Intel AX201 Bluetooth                               | 1         | 4.76%   |
| Intel AX200 Bluetooth                               | 1         | 4.76%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 4.76%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 4.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.76%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 4.76%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 4.76%   |
| Apple Bluetooth USB Host Controller                 | 1         | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 18        | 45%     |
| AMD                      | 13        | 32.5%   |
| Nvidia                   | 6         | 15%     |
| Plantronics              | 1         | 2.5%    |
| Micro Star International | 1         | 2.5%    |
| C-Media Electronics      | 1         | 2.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 4         | 8%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3         | 6%      |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3         | 6%      |
| AMD Kabini HDMI/DP Audio                                                          | 3         | 6%      |
| AMD FCH Azalia Controller                                                         | 3         | 6%      |
| AMD Family 17h/19h HD Audio Controller                                            | 3         | 6%      |
| Nvidia GF108 High Definition Audio Controller                                     | 2         | 4%      |
| Nvidia GA104 High Definition Audio Controller                                     | 2         | 4%      |
| Intel Sunrise Point-LP HD Audio                                                   | 2         | 4%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 2         | 4%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 2         | 4%      |
| AMD Renoir Radeon High Definition Audio Controller                                | 2         | 4%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 2         | 4%      |
| Plantronics GameCom 777 5.1 Headset                                               | 1         | 2%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 2%      |
| Nvidia MCP79 High Definition Audio                                                | 1         | 2%      |
| Micro Star International USB Audio                                                | 1         | 2%      |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 1         | 2%      |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 1         | 2%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1         | 2%      |
| Intel 631xESB/632xESB High Definition Audio Controller                            | 1         | 2%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 1         | 2%      |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 1         | 2%      |
| AMD Starship/Matisse HD Audio Controller                                          | 1         | 2%      |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 1         | 2%      |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 1         | 2%      |
| AMD Kaveri HDMI/DP Audio Controller                                               | 1         | 2%      |
| AMD High Definition Audio Controller                                              | 1         | 2%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1         | 2%      |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 2%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 6         | 20%     |
| Samsung Electronics | 5         | 16.67%  |
| Unknown             | 3         | 10%     |
| Kingston            | 3         | 10%     |
| Crucial             | 2         | 6.67%   |
| Corsair             | 2         | 6.67%   |
| Unknown (ABCD)      | 1         | 3.33%   |
| Teikon              | 1         | 3.33%   |
| Smart               | 1         | 3.33%   |
| Ramaxel Technology  | 1         | 3.33%   |
| Patriot             | 1         | 3.33%   |
| Micron Technology   | 1         | 3.33%   |
| G.Skill             | 1         | 3.33%   |
| fef5                | 1         | 3.33%   |
| Elpida              | 1         | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                       | 1         | 3.23%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                          | 1         | 3.23%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                        | 1         | 3.23%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 1         | 3.23%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s            | 1         | 3.23%   |
| Smart RAM SG564568FG8NWKFSQR 2GB SODIMM DDR2 800MT/s              | 1         | 3.23%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s                        | 1         | 3.23%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                        | 1         | 3.23%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1         | 3.23%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s              | 1         | 3.23%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s              | 1         | 3.23%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s            | 1         | 3.23%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s        | 1         | 3.23%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                       | 1         | 3.23%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 1         | 3.23%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 1         | 3.23%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s            | 1         | 3.23%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                   | 1         | 3.23%   |
| Ramaxel RAM RMT1970ED48E8F1333 2GB SODIMM DDR3 1333MT/s           | 1         | 3.23%   |
| Patriot RAM PSD22G80026 2GB DIMM DDR2 800MT/s                     | 1         | 3.23%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s            | 1         | 3.23%   |
| Kingston RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 3.23%   |
| Kingston RAM ACR24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s             | 1         | 3.23%   |
| Kingston RAM 99U5663-001.A00G 16GB SODIMM DDR4 2400MT/s           | 1         | 3.23%   |
| G.Skill RAM F3-1600C9-8GSR 8GB DIMM DDR3 1600MT/s                 | 1         | 3.23%   |
| fef5 RAM K4F8E304HB-MGCJ 1GB 2400MT/s                             | 1         | 3.23%   |
| Elpida RAM EBJ21UE8BDS1-DJ-F 2048MB SODIMM DDR3 1333MT/s          | 1         | 3.23%   |
| Crucial RAM CT8G4SFS824A.C8FAD1 8GB SODIMM DDR4 2400MT/s          | 1         | 3.23%   |
| Crucial RAM BL25664BA1339.8FD 2GB DIMM DDR3 1333MT/s              | 1         | 3.23%   |
| Corsair RAM CMN32GX4M2Z3600C16 16GB DIMM DDR4 3200MT/s            | 1         | 3.23%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s            | 1         | 3.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 12        | 44.44%  |
| DDR4    | 7         | 25.93%  |
| DDR2    | 4         | 14.81%  |
| LPDDR4  | 2         | 7.41%   |
| LPDDR5  | 1         | 3.7%    |
| Unknown | 1         | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| SODIMM  | 16        | 61.54%  |
| DIMM    | 9         | 34.62%  |
| Unknown | 1         | 3.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 10        | 37.04%  |
| 8192  | 7         | 25.93%  |
| 16384 | 5         | 18.52%  |
| 4096  | 3         | 11.11%  |
| 1024  | 2         | 7.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 2400  | 6         | 21.43%  |
| 1600  | 5         | 17.86%  |
| 1333  | 5         | 17.86%  |
| 3200  | 2         | 7.14%   |
| 800   | 2         | 7.14%   |
| 667   | 2         | 7.14%   |
| 6400  | 1         | 3.57%   |
| 3534  | 1         | 3.57%   |
| 2667  | 1         | 3.57%   |
| 1334  | 1         | 3.57%   |
| 1067  | 1         | 3.57%   |
| 1066  | 1         | 3.57%   |

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
| Realtek Semiconductor                  | 4         | 26.67%  |
| Chicony Electronics                    | 4         | 26.67%  |
| Sunplus Innovation Technology          | 3         | 20%     |
| Quanta                                 | 1         | 6.67%   |
| Microdia                               | 1         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 6.67%   |
| Apple                                  | 1         | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                  | 1         | 6.67%   |
| Sunplus HD WebCam                             | 1         | 6.67%   |
| Sunplus Dell HD Webcam                        | 1         | 6.67%   |
| Realtek USB Camera                            | 1         | 6.67%   |
| Realtek Integrated_Webcam_HD                  | 1         | 6.67%   |
| Realtek Integrated Webcam HD                  | 1         | 6.67%   |
| Realtek HP Truevision HD integrated webcam    | 1         | 6.67%   |
| Quanta Acer FHD User Facing                   | 1         | 6.67%   |
| Microdia Webcam Vitade AF                     | 1         | 6.67%   |
| Chicony USB 2.0 camera                        | 1         | 6.67%   |
| Chicony thinkpad t430s camera                 | 1         | 6.67%   |
| Chicony Integrated Camera                     | 1         | 6.67%   |
| Chicony HD WebCam                             | 1         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 1         | 6.67%   |
| Apple Built-in iSight                         | 1         | 6.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./All/images/line_chart/chipcard_vendor.svg)

| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Upek     | 1         | 50%     |
| Broadcom | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 50%     |
| Broadcom 5880                                              | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 32        | 88.89%  |
| 1     | 4         | 11.11%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type          | Computers | Percent |
|---------------|-----------|---------|
| Graphics card | 2         | 50%     |
| Chipcard      | 2         | 50%     |

