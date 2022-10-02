Endless - Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Endless/Desktop/README.md) and [notebooks](/Dist/Endless/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/linuxhw/TestCoverage)

Period: Sep, 2022.

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
| Endless 4.0.9         | 16        | 50%     |
| Endless 4.0.8         | 5         | 15.63%  |
| Endless 4.0.4         | 3         | 9.38%   |
| Endless 3.9.7         | 2         | 6.25%   |
| Endless 4.0.7         | 1         | 3.13%   |
| Endless 4.0.3         | 1         | 3.13%   |
| Endless 4.0.0         | 1         | 3.13%   |
| Endless 3.9.6         | 1         | 3.13%   |
| Endless 3.9.3-nexthw1 | 1         | 3.13%   |
| Endless 3.8.0         | 1         | 3.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Endless | 32        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.11.0-35-generic | 27        | 84.38%  |
| 5.8.0-14-generic  | 3         | 9.38%   |
| 5.4.0-19-generic  | 1         | 3.13%   |
| 5.11.0-12-generic | 1         | 3.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 28        | 87.5%   |
| 5.8.0   | 3         | 9.38%   |
| 5.4.0   | 1         | 3.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 28        | 87.5%   |
| 5.8     | 3         | 9.38%   |
| 5.4     | 1         | 3.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 32        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name  | Computers | Percent |
|-------|-----------|---------|
| GNOME | 32        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 32        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 32        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| pt_BR | 10        | 31.25%  |
| en_US | 9         | 28.13%  |
| de_DE | 2         | 6.25%   |
| uk_UA | 1         | 3.13%   |
| ru_RU | 1         | 3.13%   |
| it_IT | 1         | 3.13%   |
| fr_FR | 1         | 3.13%   |
| es_MX | 1         | 3.13%   |
| es_ES | 1         | 3.13%   |
| es_CO | 1         | 3.13%   |
| es_AR | 1         | 3.13%   |
| en_PH | 1         | 3.13%   |
| en_GB | 1         | 3.13%   |
| az_AZ | 1         | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 18        | 56.25%  |
| BIOS | 14        | 43.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 31        | 96.88%  |
| Tmpfs | 1         | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 32        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 13        | 40.63%  |
| Acer                | 7         | 21.88%  |
| Dell                | 3         | 9.38%   |
| Hewlett-Packard     | 2         | 6.25%   |
| Biostar             | 2         | 6.25%   |
| Sony                | 1         | 3.13%   |
| Positivo            | 1         | 3.13%   |
| Lenovo              | 1         | 3.13%   |
| Intel               | 1         | 3.13%   |
| Gigabyte Technology | 1         | 3.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Acer Nitro AN515-44                        | 3         | 9.38%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 2         | 6.25%   |
| Sony SVE1712L1EW                           | 1         | 3.13%   |
| Positivo S14CT01                           | 1         | 3.13%   |
| Lenovo Yoga 3 Pro-1370 80HE                | 1         | 3.13%   |
| Intel H61                                  | 1         | 3.13%   |
| HP Pavilion Gaming Laptop 16-a0xxx         | 1         | 3.13%   |
| HP 255 G8 Notebook PC                      | 1         | 3.13%   |
| Gigabyte GA-990FXA-UD5                     | 1         | 3.13%   |
| Dell XPS 13 9360                           | 1         | 3.13%   |
| Dell Latitude E7240                        | 1         | 3.13%   |
| Dell Inspiron 1545                         | 1         | 3.13%   |
| Biostar G41D3C                             | 1         | 3.13%   |
| Biostar A780L3B                            | 1         | 3.13%   |
| ASUS X541UAK                               | 1         | 3.13%   |
| ASUS X441NA                                | 1         | 3.13%   |
| ASUS VivoBook_ASUSLaptop X515JA_X515JA     | 1         | 3.13%   |
| ASUS VivoBook_ASUSLaptop X515DAP_M515DA    | 1         | 3.13%   |
| ASUS VivoBook_ASUSLaptop X513EA_K513EA     | 1         | 3.13%   |
| ASUS VivoBook_ASUSLaptop X513EAN_X513EAN   | 1         | 3.13%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 1         | 3.13%   |
| ASUS VivoBook 15_ASUS Laptop X540BP        | 1         | 3.13%   |
| ASUS P5Q PRO TURBO                         | 1         | 3.13%   |
| ASUS M5A78L-M/USB3                         | 1         | 3.13%   |
| ASUS M2N68                                 | 1         | 3.13%   |
| Acer TravelMate P449-G3-MG                 | 1         | 3.13%   |
| Acer TravelMate 8572T                      | 1         | 3.13%   |
| Acer Aspire A515-54                        | 1         | 3.13%   |
| Acer Aspire A317-52                        | 1         | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUS VivoBook          | 8         | 25%     |
| Acer Nitro             | 3         | 9.38%   |
| Acer TravelMate        | 2         | 6.25%   |
| Acer Aspire            | 2         | 6.25%   |
| Sony SVE1712L1EW       | 1         | 3.13%   |
| Positivo S14CT01       | 1         | 3.13%   |
| Lenovo Yoga            | 1         | 3.13%   |
| Intel H61              | 1         | 3.13%   |
| HP Pavilion            | 1         | 3.13%   |
| HP 255                 | 1         | 3.13%   |
| Gigabyte GA-990FXA-UD5 | 1         | 3.13%   |
| Dell XPS               | 1         | 3.13%   |
| Dell Latitude          | 1         | 3.13%   |
| Dell Inspiron          | 1         | 3.13%   |
| Biostar G41D3C         | 1         | 3.13%   |
| Biostar A780L3B        | 1         | 3.13%   |
| ASUS X541UAK           | 1         | 3.13%   |
| ASUS X441NA            | 1         | 3.13%   |
| ASUS P5Q               | 1         | 3.13%   |
| ASUS M5A78L-M          | 1         | 3.13%   |
| ASUS M2N68             | 1         | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 7         | 21.88%  |
| 2018 | 5         | 15.63%  |
| 2021 | 3         | 9.38%   |
| 2016 | 3         | 9.38%   |
| 2017 | 2         | 6.25%   |
| 2012 | 2         | 6.25%   |
| 2011 | 2         | 6.25%   |
| 2010 | 2         | 6.25%   |
| 2008 | 2         | 6.25%   |
| 2019 | 1         | 3.13%   |
| 2014 | 1         | 3.13%   |
| 2013 | 1         | 3.13%   |
| 2009 | 1         | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 25        | 78.13%  |
| Desktop  | 7         | 21.88%  |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 29        | 90.63%  |
| Enabled  | 3         | 9.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 32        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 15        | 46.88%  |
| 4.01-8.0   | 11        | 34.38%  |
| 8.01-16.0  | 3         | 9.38%   |
| 32.01-64.0 | 1         | 3.13%   |
| 16.01-24.0 | 1         | 3.13%   |
| 1.01-2.0   | 1         | 3.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 15        | 46.88%  |
| 2.01-3.0 | 8         | 25%     |
| 0.51-1.0 | 5         | 15.63%  |
| 4.01-8.0 | 2         | 6.25%   |
| 3.01-4.0 | 2         | 6.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 29        | 90.63%  |
| 2      | 3         | 9.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 25        | 78.13%  |
| Yes       | 7         | 21.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 65.63%  |
| No        | 11        | 34.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 78.13%  |
| No        | 7         | 21.88%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 68.75%  |
| No        | 10        | 31.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country     | Computers | Percent |
|-------------|-----------|---------|
| Brazil      | 10        | 31.25%  |
| Germany     | 3         | 9.38%   |
| USA         | 2         | 6.25%   |
| Spain       | 2         | 6.25%   |
| Philippines | 2         | 6.25%   |
| Ukraine     | 1         | 3.13%   |
| Serbia      | 1         | 3.13%   |
| Russia      | 1         | 3.13%   |
| Malta       | 1         | 3.13%   |
| Italy       | 1         | 3.13%   |
| Georgia     | 1         | 3.13%   |
| Egypt       | 1         | 3.13%   |
| Ecuador     | 1         | 3.13%   |
| Colombia    | 1         | 3.13%   |
| Belgium     | 1         | 3.13%   |
| Bangladesh  | 1         | 3.13%   |
| Azerbaijan  | 1         | 3.13%   |
| Australia   | 1         | 3.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Quezon City               | 2         | 6.25%   |
| Valparaiso de Goias       | 1         | 3.13%   |
| Trindade                  | 1         | 3.13%   |
| Três Lagoas              | 1         | 3.13%   |
| Taquaritinga              | 1         | 3.13%   |
| Tambau                    | 1         | 3.13%   |
| Sao Paulo                 | 1         | 3.13%   |
| Sant Ferran de ses Roques | 1         | 3.13%   |
| Rathenow                  | 1         | 3.13%   |
| Potsdam                   | 1         | 3.13%   |
| Moscow                    | 1         | 3.13%   |
| Matao                     | 1         | 3.13%   |
| Maringá                  | 1         | 3.13%   |
| Malyn                     | 1         | 3.13%   |
| Londrina                  | 1         | 3.13%   |
| K'alak'i T'bilisi         | 1         | 3.13%   |
| Guayaquil                 | 1         | 3.13%   |
| Guapimirim                | 1         | 3.13%   |
| Goose Creek               | 1         | 3.13%   |
| Faenza                    | 1         | 3.13%   |
| El Carmen de Viboral      | 1         | 3.13%   |
| Dhaka                     | 1         | 3.13%   |
| Dallas                    | 1         | 3.13%   |
| Brisbane                  | 1         | 3.13%   |
| Belgrade                  | 1         | 3.13%   |
| Barcelona                 | 1         | 3.13%   |
| Baku                      | 1         | 3.13%   |
| Bad Kreuznach             | 1         | 3.13%   |
| Attard                    | 1         | 3.13%   |
| Ans                       | 1         | 3.13%   |
| Alexandria                | 1         | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| SanDisk                     | 5         | 5      | 14.29%  |
| Samsung Electronics         | 5         | 6      | 14.29%  |
| Seagate                     | 3         | 3      | 8.57%   |
| WDC                         | 2         | 2      | 5.71%   |
| SK hynix                    | 2         | 2      | 5.71%   |
| Kingston                    | 2         | 2      | 5.71%   |
| Intel                       | 2         | 2      | 5.71%   |
| ADATA Technology            | 2         | 2      | 5.71%   |
| USB                         | 1         | 1      | 2.86%   |
| Unknown                     | 1         | 1      | 2.86%   |
| Transcend                   | 1         | 1      | 2.86%   |
| Toshiba                     | 1         | 1      | 2.86%   |
| Timetec                     | 1         | 1      | 2.86%   |
| SPCC                        | 1         | 1      | 2.86%   |
| Phison                      | 1         | 1      | 2.86%   |
| OWC                         | 1         | 1      | 2.86%   |
| LITEONIT                    | 1         | 1      | 2.86%   |
| Kingston Technology Company | 1         | 1      | 2.86%   |
| KingFast                    | 1         | 1      | 2.86%   |
| China                       | 1         | 1      | 2.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| WDC WD10SPZX-21Z10T0 1TB                            | 2         | 5.56%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB               | 2         | 5.56%   |
| SanDisk NVMe SSD Drive 256GB                        | 2         | 5.56%   |
| Kingston RBUSC180DS37256GJ 256GB SSD                | 2         | 5.56%   |
| USB Disk 640GB                                      | 1         | 2.78%   |
| Unknown MMC Card  32GB                              | 1         | 2.78%   |
| Transcend TS128GSSD370S 128GB                       | 1         | 2.78%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 2.78%   |
| Timetec 30TT253X2-512G                              | 1         | 2.78%   |
| SPCC Solid State Disk 128GB                         | 1         | 2.78%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 1         | 2.78%   |
| SK hynix BC511 512GB                                | 1         | 2.78%   |
| Seagate ST640LM001 HN-M640MBB 640GB                 | 1         | 2.78%   |
| Seagate ST500LM030-1RK17D 500GB                     | 1         | 2.78%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 2.78%   |
| SanDisk SDSSDA120G 120GB                            | 1         | 2.78%   |
| Samsung NVMe SSD Drive 256GB                        | 1         | 2.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 2.78%   |
| Samsung MZNTE256HMHP-000L2 256GB SSD                | 1         | 2.78%   |
| Samsung HD161GJ 160GB                               | 1         | 2.78%   |
| Samsung HD103SJ 1TB                                 | 1         | 2.78%   |
| Samsung HD080HJ/ 80GB                               | 1         | 2.78%   |
| Phison NVMe SSD Drive 256GB                         | 1         | 2.78%   |
| OWC Mercury Electra 3G SSD                          | 1         | 2.78%   |
| LITEONIT LMT-128M6M-HP 128GB SSD                    | 1         | 2.78%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB             | 1         | 2.78%   |
| KingFast 256GB                                      | 1         | 2.78%   |
| Intel NVMe SSD Drive 256GB                          | 1         | 2.78%   |
| Intel Micron_2210_MTFDHBA1T0QFD 1024GB              | 1         | 2.78%   |
| China SSD 240GB                                     | 1         | 2.78%   |
| ADATA SM2P32A8-256GC1 256GB                         | 1         | 2.78%   |
| ADATA NVMe SSD Drive 256GB                          | 1         | 2.78%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 33.33%  |
| Samsung Electronics | 3         | 3      | 33.33%  |
| WDC                 | 2         | 2      | 22.22%  |
| Toshiba             | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 2         | 2      | 20%     |
| Transcend           | 1         | 1      | 10%     |
| SPCC                | 1         | 1      | 10%     |
| SK hynix            | 1         | 1      | 10%     |
| SanDisk             | 1         | 1      | 10%     |
| Samsung Electronics | 1         | 1      | 10%     |
| OWC                 | 1         | 1      | 10%     |
| LITEONIT            | 1         | 1      | 10%     |
| China               | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 12        | 13     | 34.29%  |
| SSD     | 10        | 10     | 28.57%  |
| HDD     | 9         | 9      | 25.71%  |
| Unknown | 3         | 3      | 8.57%   |
| MMC     | 1         | 1      | 2.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 20        | 21     | 58.82%  |
| NVMe | 12        | 13     | 35.29%  |
| SAS  | 1         | 1      | 2.94%   |
| MMC  | 1         | 1      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 13        | 13     | 68.42%  |
| 0.51-1.0   | 6         | 6      | 31.58%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 19        | 59.38%  |
| 251-500    | 6         | 18.75%  |
| 501-1000   | 5         | 15.63%  |
| 21-50      | 1         | 3.13%   |
| 1-20       | 1         | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 21-50    | 12        | 37.5%   |
| 1-20     | 8         | 25%     |
| 51-100   | 6         | 18.75%  |
| 101-250  | 5         | 15.63%  |
| 501-1000 | 1         | 3.13%   |

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
| Detected | 32        | 36     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 21        | 50%     |
| AMD                         | 8         | 19.05%  |
| SanDisk                     | 4         | 9.52%   |
| ADATA Technology            | 2         | 4.76%   |
| SK hynix                    | 1         | 2.38%   |
| Samsung Electronics         | 1         | 2.38%   |
| Phison Electronics          | 1         | 2.38%   |
| Nvidia                      | 1         | 2.38%   |
| Marvell Technology Group    | 1         | 2.38%   |
| Kingston Technology Company | 1         | 2.38%   |
| JMicron Technology          | 1         | 2.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 5         | 9.62%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 5         | 9.62%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 4         | 7.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 3         | 5.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                              | 3         | 5.77%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 3         | 5.77%   |
| Intel Volume Management Device NVMe RAID Controller                           | 2         | 3.85%   |
| Intel Tiger Lake-LP SATA Controller                                           | 2         | 3.85%   |
| Intel PROSet/Wireless WiFi Software extension                                 | 2         | 3.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 3.85%   |
| SK hynix BC511                                                                | 1         | 1.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1         | 1.92%   |
| Phison PS5013 E13 NVMe Controller                                             | 1         | 1.92%   |
| Nvidia MCP67 IDE Controller                                                   | 1         | 1.92%   |
| Nvidia MCP67 AHCI Controller                                                  | 1         | 1.92%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                         | 1         | 1.92%   |
| Kingston Company OM3PDP3 NVMe SSD                                             | 1         | 1.92%   |
| JMicron JMB361 AHCI/IDE                                                       | 1         | 1.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 1         | 1.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 1         | 1.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 1         | 1.92%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                    | 1         | 1.92%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                    | 1         | 1.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 1         | 1.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 1         | 1.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1         | 1.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 1         | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 1         | 1.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                | 1         | 1.92%   |
| ADATA Non-Volatile memory controller                                          | 1         | 1.92%   |
| ADATA A Non-Volatile memory controller                                        | 1         | 1.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 24        | 50%     |
| NVMe | 12        | 25%     |
| RAID | 6         | 12.5%   |
| IDE  | 6         | 12.5%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 22        | 68.75%  |
| AMD    | 10        | 31.25%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| AMD Ryzen 7 4800H with Radeon Graphics       | 3         | 9.38%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz           | 2         | 6.25%   |
| Intel Celeron N4000 CPU @ 1.10GHz            | 2         | 6.25%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz  | 1         | 3.13%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz  | 1         | 3.13%   |
| Intel Core M-5Y71 CPU @ 1.20GHz              | 1         | 3.13%   |
| Intel Core i7-7500U CPU @ 2.70GHz            | 1         | 3.13%   |
| Intel Core i7-2600 CPU @ 3.40GHz             | 1         | 3.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 1         | 3.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 1         | 3.13%   |
| Intel Core i5-4210U CPU @ 1.70GHz            | 1         | 3.13%   |
| Intel Core i5-10300H CPU @ 2.50GHz           | 1         | 3.13%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 1         | 3.13%   |
| Intel Core i5 CPU M 540 @ 2.53GHz            | 1         | 3.13%   |
| Intel Core i3-7020U CPU @ 2.30GHz            | 1         | 3.13%   |
| Intel Core i3-3110M CPU @ 2.40GHz            | 1         | 3.13%   |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz         | 1         | 3.13%   |
| Intel Celeron CPU N3350 @ 1.10GHz            | 1         | 3.13%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 1         | 3.13%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz      | 1         | 3.13%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz      | 1         | 3.13%   |
| AMD Ryzen 3 3250U with Radeon Graphics       | 1         | 3.13%   |
| AMD Phenom II X6 1090T Processor             | 1         | 3.13%   |
| AMD Phenom II X6 1055T Processor             | 1         | 3.13%   |
| AMD FX-8150 Eight-Core Processor             | 1         | 3.13%   |
| AMD Athlon II X2 215 Processor               | 1         | 3.13%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G | 1         | 3.13%   |
| AMD 3020e with Radeon Graphics               | 1         | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 8         | 25%     |
| Other                   | 3         | 9.38%   |
| Intel Celeron           | 3         | 9.38%   |
| AMD Ryzen 7             | 3         | 9.38%   |
| Intel Pentium Dual-Core | 2         | 6.25%   |
| Intel Core i7           | 2         | 6.25%   |
| Intel Core i3           | 2         | 6.25%   |
| AMD Phenom II X6        | 2         | 6.25%   |
| Intel Core M            | 1         | 3.13%   |
| Intel Core 2 Duo        | 1         | 3.13%   |
| Intel Atom              | 1         | 3.13%   |
| AMD Ryzen 3             | 1         | 3.13%   |
| AMD FX                  | 1         | 3.13%   |
| AMD Athlon II X2        | 1         | 3.13%   |
| AMD A6                  | 1         | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 18        | 56.25%  |
| 4      | 8         | 25%     |
| 8      | 3         | 9.38%   |
| 6      | 2         | 6.25%   |
| 3      | 1         | 3.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 32        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 20        | 62.5%   |
| 1      | 12        | 37.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 32        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806e9    | 3         | 9.38%   |
| 0x1067a    | 3         | 9.38%   |
| 0x08600103 | 3         | 9.38%   |
| 0x806c1    | 2         | 6.25%   |
| 0x706e5    | 2         | 6.25%   |
| 0x706a1    | 2         | 6.25%   |
| 0x010000dc | 2         | 6.25%   |
| Unknown    | 2         | 6.25%   |
| 0xa0652    | 1         | 3.13%   |
| 0x806ea    | 1         | 3.13%   |
| 0x506c9    | 1         | 3.13%   |
| 0x406c4    | 1         | 3.13%   |
| 0x40651    | 1         | 3.13%   |
| 0x306d4    | 1         | 3.13%   |
| 0x306a9    | 1         | 3.13%   |
| 0x206a7    | 1         | 3.13%   |
| 0x20652    | 1         | 3.13%   |
| 0x08200103 | 1         | 3.13%   |
| 0x06006705 | 1         | 3.13%   |
| 0x0600063e | 1         | 3.13%   |
| 0x010000c7 | 1         | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 5         | 15.63%  |
| Zen 2         | 3         | 9.38%   |
| Penryn        | 3         | 9.38%   |
| K10           | 3         | 9.38%   |
| TigerLake     | 2         | 6.25%   |
| IceLake       | 2         | 6.25%   |
| Goldmont plus | 2         | 6.25%   |
| Zen+          | 1         | 3.13%   |
| Zen           | 1         | 3.13%   |
| Westmere      | 1         | 3.13%   |
| Silvermont    | 1         | 3.13%   |
| SandyBridge   | 1         | 3.13%   |
| IvyBridge     | 1         | 3.13%   |
| Haswell       | 1         | 3.13%   |
| Goldmont      | 1         | 3.13%   |
| Excavator     | 1         | 3.13%   |
| CometLake     | 1         | 3.13%   |
| Bulldozer     | 1         | 3.13%   |
| Broadwell     | 1         | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 20        | 54.05%  |
| AMD    | 9         | 24.32%  |
| Nvidia | 8         | 21.62%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia TU117M                                                                            | 3         | 7.89%   |
| AMD Renoir                                                                               | 3         | 7.89%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 5.26%   |
| Intel HD Graphics 620                                                                    | 2         | 5.26%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 5.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 5.26%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 2.63%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 2.63%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 1         | 2.63%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1         | 2.63%   |
| Nvidia G92 [GeForce 9800 GT]                                                             | 1         | 2.63%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.63%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 2.63%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 2.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.63%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                        | 1         | 2.63%   |
| Intel HD Graphics 5300                                                                   | 1         | 2.63%   |
| Intel HD Graphics 500                                                                    | 1         | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.63%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 2.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.63%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1         | 2.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 2.63%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 2.63%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 2.63%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 2.63%   |
| AMD RS780L [Radeon 3000]                                                                 | 1         | 2.63%   |
| AMD Juniper XT [Radeon HD 6770]                                                          | 1         | 2.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 56.25%  |
| 1 x AMD        | 5         | 15.63%  |
| 1 x Nvidia     | 3         | 9.38%   |
| AMD + Nvidia   | 3         | 9.38%   |
| Intel + Nvidia | 2         | 6.25%   |
| 2 x AMD        | 1         | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 27        | 84.38%  |
| Proprietary | 5         | 15.63%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 65.63%  |
| 0.51-1.0   | 5         | 15.63%  |
| 0.01-0.5   | 5         | 15.63%  |
| 1.01-2.0   | 1         | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 9         | 27.27%  |
| BOE                 | 5         | 15.15%  |
| AU Optronics        | 4         | 12.12%  |
| Samsung Electronics | 3         | 9.09%   |
| LG Display          | 2         | 6.06%   |
| Sharp               | 1         | 3.03%   |
| SANYO               | 1         | 3.03%   |
| Philips             | 1         | 3.03%   |
| PANDA               | 1         | 3.03%   |
| LLL                 | 1         | 3.03%   |
| KDC                 | 1         | 3.03%   |
| Goldstar            | 1         | 3.03%   |
| EKD                 | 1         | 3.03%   |
| Dell                | 1         | 3.03%   |
| AOC                 | 1         | 3.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 9.09%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 9.09%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 2         | 6.06%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 2         | 6.06%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 3.03%   |
| SANYO LED MONITOR SAN309A 1920x1080 443x249mm 20.0-inch               | 1         | 3.03%   |
| Samsung Electronics SyncMaster SAM0420 1680x1050 474x296mm 22.0-inch  | 1         | 3.03%   |
| Samsung Electronics SMB2230 SAM063F 1920x1080 477x268mm 21.5-inch     | 1         | 3.03%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch | 1         | 3.03%   |
| Philips 215Vw PHL2151 1920x1080 476x268mm 21.5-inch                   | 1         | 3.03%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 3.03%   |
| LLL Monitor LLL0001 1920x1080                                         | 1         | 3.03%   |
| LG Display LCD Monitor LGD03DC 1366x768 277x156mm 12.5-inch           | 1         | 3.03%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 3.03%   |
| KDC LCD Monitor KDC0830 1920x1080 344x193mm 15.5-inch                 | 1         | 3.03%   |
| Goldstar L1760TQ GSM4446 1280x1024 338x270mm 17.0-inch                | 1         | 3.03%   |
| EKD AW1851 EKD073B 1366x768 344x194mm 15.5-inch                       | 1         | 3.03%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 1         | 3.03%   |
| BOE LCD Monitor BOE08F6 1920x1080 355x200mm 16.0-inch                 | 1         | 3.03%   |
| BOE LCD Monitor BOE0788 1920x1080 381x214mm 17.2-inch                 | 1         | 3.03%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO499F 1920x1080 344x194mm 15.5-inch        | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch         | 1         | 3.03%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                          | 1         | 3.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 14        | 46.67%  |
| 1366x768 (WXGA)    | 13        | 43.33%  |
| 3200x1800 (QHD+)   | 1         | 3.33%   |
| 1680x1050 (WSXGA+) | 1         | 3.33%   |
| 1280x1024 (SXGA)   | 1         | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 17        | 53.13%  |
| 13     | 5         | 15.63%  |
| 17     | 2         | 6.25%   |
| 39     | 1         | 3.13%   |
| 24     | 1         | 3.13%   |
| 22     | 1         | 3.13%   |
| 21     | 1         | 3.13%   |
| 20     | 1         | 3.13%   |
| 18     | 1         | 3.13%   |
| 16     | 1         | 3.13%   |
| 12     | 1         | 3.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 65.63%  |
| 401-500     | 4         | 12.5%   |
| 201-300     | 3         | 9.38%   |
| 351-400     | 2         | 6.25%   |
| 801-900     | 1         | 3.13%   |
| 501-600     | 1         | 3.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 28        | 90.32%  |
| 16/10 | 2         | 6.45%   |
| 5/4   | 1         | 3.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 56.25%  |
| 81-90          | 3         | 9.38%   |
| 71-80          | 2         | 6.25%   |
| 151-200        | 2         | 6.25%   |
| 141-150        | 2         | 6.25%   |
| 61-70          | 1         | 3.13%   |
| 251-300        | 1         | 3.13%   |
| 201-250        | 1         | 3.13%   |
| 121-130        | 1         | 3.13%   |
| 501-1000       | 1         | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 13        | 40.63%  |
| 121-160       | 12        | 37.5%   |
| 51-100        | 5         | 15.63%  |
| More than 240 | 1         | 3.13%   |
| 161-240       | 1         | 3.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 27        | 84.38%  |
| 2     | 3         | 9.38%   |
| 0     | 2         | 6.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 18        | 40%     |
| Intel                           | 10        | 22.22%  |
| Qualcomm Atheros                | 7         | 15.56%  |
| Broadcom Limited                | 3         | 6.67%   |
| TP-Link                         | 1         | 2.22%   |
| Ralink Technology               | 1         | 2.22%   |
| Ralink                          | 1         | 2.22%   |
| Qualcomm Atheros Communications | 1         | 2.22%   |
| OnePlus Technology (Shenzhen)   | 1         | 2.22%   |
| Nvidia                          | 1         | 2.22%   |
| Marvell Technology Group        | 1         | 2.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 14%     |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 8%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 8%      |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 6%      |
| Intel Wi-Fi 6 AX200                                               | 3         | 6%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 4%      |
| Intel Wi-Fi 6 AX201                                               | 2         | 4%      |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1         | 2%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 2%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 2%      |
| Realtek 802.11ac NIC                                              | 1         | 2%      |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 2%      |
| Ralink RT3062 Wireless 802.11n 2T/2R                              | 1         | 2%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 2%      |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 2%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 2%      |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2%      |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 2%      |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 2%      |
| Nvidia MCP67 Ethernet                                             | 1         | 2%      |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 2%      |
| Intel Wireless 8265 / 8275                                        | 1         | 2%      |
| Intel Wireless 7265                                               | 1         | 2%      |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 2%      |
| Intel Ethernet Connection I219-LM                                 | 1         | 2%      |
| Intel Ethernet Connection I218-LM                                 | 1         | 2%      |
| Intel Centrino Advanced-N 6200                                    | 1         | 2%      |
| Broadcom Limited NetXtreme BCM57760 Gigabit Ethernet PCIe         | 1         | 2%      |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 2%      |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 1         | 2%      |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 32.14%  |
| Realtek Semiconductor           | 8         | 28.57%  |
| Qualcomm Atheros                | 5         | 17.86%  |
| Broadcom Limited                | 2         | 7.14%   |
| TP-Link                         | 1         | 3.57%   |
| Ralink Technology               | 1         | 3.57%   |
| Ralink                          | 1         | 3.57%   |
| Qualcomm Atheros Communications | 1         | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 4         | 14.29%  |
| Intel Wi-Fi 6 AX200                                        | 3         | 10.71%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 7.14%   |
| Intel Wi-Fi 6 AX201                                        | 2         | 7.14%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 1         | 3.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.57%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1         | 3.57%   |
| Realtek 802.11ac NIC                                       | 1         | 3.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 1         | 3.57%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                       | 1         | 3.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 3.57%   |
| Qualcomm Atheros AR9271 802.11n                            | 1         | 3.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 1         | 3.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 1         | 3.57%   |
| Intel Wireless 8265 / 8275                                 | 1         | 3.57%   |
| Intel Wireless 7265                                        | 1         | 3.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 1         | 3.57%   |
| Intel Centrino Advanced-N 6200                             | 1         | 3.57%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter | 1         | 3.57%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                  | 1         | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 14        | 63.64%  |
| Qualcomm Atheros              | 2         | 9.09%   |
| Intel                         | 2         | 9.09%   |
| OnePlus Technology (Shenzhen) | 1         | 4.55%   |
| Nvidia                        | 1         | 4.55%   |
| Marvell Technology Group      | 1         | 4.55%   |
| Broadcom Limited              | 1         | 4.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 31.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 18.18%  |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 13.64%  |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 4.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 4.55%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 4.55%   |
| Nvidia MCP67 Ethernet                                             | 1         | 4.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 4.55%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 4.55%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 4.55%   |
| Broadcom Limited NetXtreme BCM57760 Gigabit Ethernet PCIe         | 1         | 4.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 54.35%  |
| Ethernet | 21        | 45.65%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 23        | 71.88%  |
| Ethernet | 9         | 28.13%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 16        | 50%     |
| 2     | 14        | 43.75%  |
| 0     | 2         | 6.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| Yes  | 16        | 50%     |
| No   | 16        | 50%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 8         | 36.36%  |
| IMC Networks                    | 4         | 18.18%  |
| Lite-On Technology              | 3         | 13.64%  |
| Realtek Semiconductor           | 2         | 9.09%   |
| Qualcomm Atheros Communications | 2         | 9.09%   |
| Foxconn / Hon Hai               | 2         | 9.09%   |
| Cambridge Silicon Radio         | 1         | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Bluetooth Radio                        | 4         | 18.18%  |
| Intel AX200 Bluetooth                               | 3         | 13.64%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 9.09%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 9.09%   |
| Intel Bluetooth wireless interface                  | 2         | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 9.09%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 4.55%   |
| Realtek Bluetooth Radio                             | 1         | 4.55%   |
| Lite-On Bluetooth Device                            | 1         | 4.55%   |
| Intel AX201 Bluetooth                               | 1         | 4.55%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 4.55%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 4.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 21        | 55.26%  |
| AMD                 | 10        | 26.32%  |
| Nvidia              | 6         | 15.79%  |
| C-Media Electronics | 1         | 2.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 5         | 11.36%  |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 9.09%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 9.09%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 6.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 4.55%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 4.55%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 4.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 4.55%   |
| Nvidia MCP67 High Definition Audio                                         | 1         | 2.27%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 2.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 2.27%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.27%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.27%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 2.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 2.27%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.27%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 2.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.27%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2.27%   |
| C-Media Electronics Audio Adapter                                          | 1         | 2.27%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 2.27%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 1         | 2.27%   |
| AMD High Definition Audio Controller                                       | 1         | 2.27%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 2.27%   |

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

| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| IMC Networks                  | 8         | 29.63%  |
| Chicony Electronics           | 4         | 14.81%  |
| Quanta                        | 3         | 11.11%  |
| Microdia                      | 3         | 11.11%  |
| Luxvisions Innotech Limited   | 2         | 7.41%   |
| Acer                          | 2         | 7.41%   |
| Sunplus Innovation Technology | 1         | 3.7%    |
| Sonix Technology              | 1         | 3.7%    |
| Ricoh                         | 1         | 3.7%    |
| Realtek Semiconductor         | 1         | 3.7%    |
| KYE Systems (Mouse Systems)   | 1         | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                  | 7         | 25.93%  |
| Quanta HD User Facing                               | 2         | 7.41%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 7.41%   |
| Chicony HD User Facing                              | 2         | 7.41%   |
| Sunplus Lenovo EasyCamera                           | 1         | 3.7%    |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 3.7%    |
| Ricoh Integrated Webcam                             | 1         | 3.7%    |
| Realtek HD WebCam                                   | 1         | 3.7%    |
| Quanta USB2.0 HD UVC WebCam                         | 1         | 3.7%    |
| Microdia Sonix USB 2.0 Camera                       | 1         | 3.7%    |
| Microdia Integrated Webcam HD                       | 1         | 3.7%    |
| Microdia Integrated Webcam                          | 1         | 3.7%    |
| KYE Systems (Mouse Systems) FaceCam 1000X           | 1         | 3.7%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 3.7%    |
| Chicony VGA WebCam                                  | 1         | 3.7%    |
| Chicony 1.3M Webcam                                 | 1         | 3.7%    |
| Acer VGA WebCam                                     | 1         | 3.7%    |
| Acer USB2.0 Camera                                  | 1         | 3.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| LighTuning Technology | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| LighTuning Fingerprint Reader               | 1         | 50%     |
| LighTuning EgisTec Touch Fingerprint Sensor | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./images/line_chart/chipcard_vendor.svg)

| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)

![Chipcard Model](./images/line_chart/chipcard_model.svg)

| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 22        | 68.75%  |
| 1     | 9         | 28.13%  |
| 2     | 1         | 3.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 5         | 45.45%  |
| Net/wireless          | 2         | 18.18%  |
| Fingerprint reader    | 2         | 18.18%  |
| Chipcard              | 2         | 18.18%  |

