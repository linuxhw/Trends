Endless - Hardware Trends (Notebooks)
-------------------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

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

| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Endless 4.0.7         | 11        | 55%     |
| Endless 3.9.7         | 3         | 15%     |
| Endless 3.9.3-nexthw1 | 1         | 5%      |
| Endless 3.8.7-nexthw2 | 1         | 5%      |
| Endless 3.8.7         | 1         | 5%      |
| Endless 3.8.1         | 1         | 5%      |
| Endless 3.7.7-nexthw1 | 1         | 5%      |
| Endless 3.4.0         | 1         | 5%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Endless | 20        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.11.0-35-generic | 11        | 55%     |
| 5.8.0-14-generic  | 4         | 20%     |
| 5.4.0-7-generic   | 1         | 5%      |
| 5.4.0-42-generic  | 1         | 5%      |
| 5.4.0-19-generic  | 1         | 5%      |
| 5.11.0-12-generic | 1         | 5%      |
| 4.15.0-15-generic | 1         | 5%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 12        | 60%     |
| 5.8.0   | 4         | 20%     |
| 5.4.0   | 3         | 15%     |
| 4.15.0  | 1         | 5%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 12        | 60%     |
| 5.8     | 4         | 20%     |
| 5.4     | 3         | 15%     |
| 4.15    | 1         | 5%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 20        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name  | Notebooks | Percent |
|-------|-----------|---------|
| GNOME | 20        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 20        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 20        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| pt_BR | 7         | 35%     |
| en_US | 6         | 30%     |
| fr_FR | 2         | 10%     |
| es_ES | 2         | 10%     |
| tr_TR | 1         | 5%      |
| ru_RU | 1         | 5%      |
| ro_RO | 1         | 5%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 14        | 70%     |
| BIOS | 6         | 30%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type | Notebooks | Percent |
|------|-----------|---------|
| Ext4 | 20        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 20        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 10        | 50%     |
| Acer                | 5         | 25%     |
| Sony                | 2         | 10%     |
| Samsung Electronics | 1         | 5%      |
| Chuwi               | 1         | 5%      |
| AMI                 | 1         | 5%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop X513EAN_X513EAN    | 2         | 10%     |
| Acer Nitro AN515-44                         | 2         | 10%     |
| Sony VPCEG33FL                              | 1         | 5%      |
| Sony VPCEA26FG                              | 1         | 5%      |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 5%      |
| Chuwi LarkBook                              | 1         | 5%      |
| ASUS VivoBook_ASUSLaptop X712FA_X712FA      | 1         | 5%      |
| ASUS VivoBook_ASUSLaptop X515JAB_F515JA     | 1         | 5%      |
| ASUS VivoBook_ASUSLaptop X515DA_X515DA      | 1         | 5%      |
| ASUS VivoBook_ASUSLaptop X409DAP_D409DA     | 1         | 5%      |
| ASUS VivoBook 15_ASUS Laptop X540UAR        | 1         | 5%      |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA  | 1         | 5%      |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA  | 1         | 5%      |
| ASUS VivoBook 15_ASUS Laptop X540BA         | 1         | 5%      |
| AMI F3C                                     | 1         | 5%      |
| Acer TravelMate 8572T                       | 1         | 5%      |
| Acer Aspire F5-573G                         | 1         | 5%      |
| Acer Aspire A515-54                         | 1         | 5%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| ASUS VivoBook   | 10        | 50%     |
| Acer Nitro      | 2         | 10%     |
| Acer Aspire     | 2         | 10%     |
| Sony VPCEG33FL  | 1         | 5%      |
| Sony VPCEA26FG  | 1         | 5%      |
| Samsung RV411   | 1         | 5%      |
| Chuwi LarkBook  | 1         | 5%      |
| AMI F3C         | 1         | 5%      |
| Acer TravelMate | 1         | 5%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 4         | 20%     |
| 2021 | 3         | 15%     |
| 2019 | 3         | 15%     |
| 2018 | 3         | 15%     |
| 2011 | 2         | 10%     |
| 2010 | 2         | 10%     |
| 2022 | 1         | 5%      |
| 2017 | 1         | 5%      |
| 2016 | 1         | 5%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 20        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 16        | 80%     |
| Enabled  | 4         | 20%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 20        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 10        | 50%     |
| 3.01-4.0   | 8         | 40%     |
| 1.01-2.0   | 1         | 5%      |
| 8.01-16.0  | 1         | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 10        | 50%     |
| 2.01-3.0  | 4         | 20%     |
| 4.01-8.0  | 2         | 10%     |
| 0.51-1.0  | 2         | 10%     |
| 3.01-4.0  | 1         | 5%      |
| 8.01-16.0 | 1         | 5%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 17        | 85%     |
| 2      | 3         | 15%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 80%     |
| Yes       | 4         | 20%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 11        | 55%     |
| Yes       | 9         | 45%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 95%     |
| No        | 1         | 5%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 90%     |
| No        | 2         | 10%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Brazil    | 6         | 30%     |
| Spain     | 2         | 10%     |
| Romania   | 2         | 10%     |
| France    | 2         | 10%     |
| Turkey    | 1         | 5%      |
| Russia    | 1         | 5%      |
| Pakistan  | 1         | 5%      |
| Nigeria   | 1         | 5%      |
| Egypt     | 1         | 5%      |
| Colombia  | 1         | 5%      |
| Belgium   | 1         | 5%      |
| Australia | 1         | 5%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Viseu de Sus    | 1         | 5%      |
| Vigo            | 1         | 5%      |
| Vehari          | 1         | 5%      |
| Tours           | 1         | 5%      |
| Sector 5        | 1         | 5%      |
| Sao Carlos      | 1         | 5%      |
| Patrocinio      | 1         | 5%      |
| Montblanc       | 1         | 5%      |
| Mol             | 1         | 5%      |
| Maua            | 1         | 5%      |
| Manizales       | 1         | 5%      |
| Maceió         | 1         | 5%      |
| Kano            | 1         | 5%      |
| Jaraguá do Sul | 1         | 5%      |
| Izmir           | 1         | 5%      |
| Dimitrovgrad    | 1         | 5%      |
| Creil           | 1         | 5%      |
| Brisbane        | 1         | 5%      |
| Belo Horizonte  | 1         | 5%      |
| Alexandria      | 1         | 5%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 17.39%  |
| Toshiba             | 3         | 3      | 13.04%  |
| SanDisk             | 3         | 3      | 13.04%  |
| ADATA Technology    | 2         | 2      | 8.7%    |
| WDC                 | 1         | 1      | 4.35%   |
| Unknown             | 1         | 1      | 4.35%   |
| Silicon Motion      | 1         | 1      | 4.35%   |
| Samsung Electronics | 1         | 1      | 4.35%   |
| Phison              | 1         | 1      | 4.35%   |
| OWC                 | 1         | 1      | 4.35%   |
| Kingston            | 1         | 1      | 4.35%   |
| KingSpec            | 1         | 1      | 4.35%   |
| JMicron Technology  | 1         | 1      | 4.35%   |
| Intel               | 1         | 1      | 4.35%   |
| Fujitsu             | 1         | 1      | 4.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB            | 2         | 8.7%    |
| ADATA NVMe SSD Drive 256GB          | 2         | 8.7%    |
| WDC WD10SPZX-21Z10T0 1TB            | 1         | 4.35%   |
| Unknown MMC Card  32GB              | 1         | 4.35%   |
| Toshiba MQ01ABD100 1TB              | 1         | 4.35%   |
| Silicon Motion NVMe SSD Drive 256GB | 1         | 4.35%   |
| Seagate ST500VT000-1DK142 500GB     | 1         | 4.35%   |
| Seagate ST500LM030-2E717D 500GB     | 1         | 4.35%   |
| Seagate ST2000LM007-1R8174 2TB      | 1         | 4.35%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 4.35%   |
| SanDisk SD9SB8W256G1102 256GB SSD   | 1         | 4.35%   |
| SanDisk NVMe SSD Drive 512GB        | 1         | 4.35%   |
| SanDisk NVMe SSD Drive 256GB        | 1         | 4.35%   |
| Samsung NVMe SSD Drive 256GB        | 1         | 4.35%   |
| Phison NVMe SSD Drive 256GB         | 1         | 4.35%   |
| OWC Mercury Electra 3G SSD          | 1         | 4.35%   |
| Kingston OM8P0S3256B-A0 256GB SSD   | 1         | 4.35%   |
| KingSpec P4-120 120GB               | 1         | 4.35%   |
| JMicron Generic 2TB                 | 1         | 4.35%   |
| Intel NVMe SSD Drive 256GB          | 1         | 4.35%   |
| Fujitsu MHV2120BH PL 120GB          | 1         | 4.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 44.44%  |
| Toshiba | 3         | 3      | 33.33%  |
| WDC     | 1         | 1      | 11.11%  |
| Fujitsu | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| SanDisk  | 1         | 1      | 25%     |
| OWC      | 1         | 1      | 25%     |
| Kingston | 1         | 1      | 25%     |
| KingSpec | 1         | 1      | 25%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 9         | 9      | 39.13%  |
| HDD  | 9         | 9      | 39.13%  |
| SSD  | 4         | 4      | 17.39%  |
| MMC  | 1         | 1      | 4.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 12        | 13     | 54.55%  |
| NVMe | 8         | 8      | 36.36%  |
| SAS  | 1         | 1      | 4.55%   |
| MMC  | 1         | 1      | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 8         | 9      | 66.67%  |
| 0.51-1.0   | 3         | 3      | 25%     |
| 1.01-2.0   | 1         | 1      | 8.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 6         | 30%     |
| 251-500    | 5         | 25%     |
| 501-1000   | 4         | 20%     |
| 21-50      | 3         | 15%     |
| 1001-2000  | 2         | 10%     |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 10        | 50%     |
| 51-100   | 4         | 20%     |
| 101-250  | 2         | 10%     |
| 1-20     | 2         | 10%     |
| 501-1000 | 2         | 10%     |

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
| Detected | 20        | 23     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 14        | 53.85%  |
| AMD                 | 5         | 19.23%  |
| SanDisk             | 2         | 7.69%   |
| ADATA Technology    | 2         | 7.69%   |
| Silicon Motion      | 1         | 3.85%   |
| Samsung Electronics | 1         | 3.85%   |
| Phison Electronics  | 1         | 3.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 5         | 17.24%  |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 3         | 10.34%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 3         | 10.34%  |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 3         | 10.34%  |
| SanDisk WD Blue SN550 NVMe SSD                                               | 2         | 6.9%    |
| Intel Volume Management Device NVMe RAID Controller                          | 2         | 6.9%    |
| Intel Tiger Lake-LP SATA Controller                                          | 2         | 6.9%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 2         | 6.9%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                              | 1         | 3.45%   |
| Samsung NVMe SSD Controller 980                                              | 1         | 3.45%   |
| Phison PS5013 E13 NVMe Controller                                            | 1         | 3.45%   |
| Intel PROSet/Wireless WiFi Software extension                                | 1         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 1         | 3.45%   |
| ADATA Non-Volatile memory controller                                         | 1         | 3.45%   |
| ADATA A Non-Volatile memory controller                                       | 1         | 3.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 17        | 58.62%  |
| NVMe | 8         | 27.59%  |
| RAID | 4         | 13.79%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 15        | 75%     |
| AMD    | 5         | 25%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 10%     |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 10%     |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 5%      |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 5%      |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 5%      |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 5%      |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 5%      |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 1         | 5%      |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 5%      |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 5%      |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 1         | 5%      |
| Intel Celeron N4120 CPU @ 1.10GHz             | 1         | 5%      |
| Intel Celeron N4000C CPU @ 1.10GHz            | 1         | 5%      |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 5%      |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 5%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 5%      |
| AMD Ryzen 3 3250U with Radeon Graphics        | 1         | 5%      |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 5%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i5 | 5         | 25%     |
| Other         | 3         | 15%     |
| Intel Core i3 | 3         | 15%     |
| Intel Celeron | 3         | 15%     |
| AMD Ryzen 7   | 2         | 10%     |
| Intel Core i7 | 1         | 5%      |
| Intel Atom    | 1         | 5%      |
| AMD Ryzen 5   | 1         | 5%      |
| AMD Ryzen 3   | 1         | 5%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 11        | 55%     |
| 4      | 7         | 35%     |
| 8      | 2         | 10%     |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 20        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 15        | 75%     |
| 1      | 5         | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 20        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 2         | 10%     |
| 0x706a1    | 2         | 10%     |
| 0x20655    | 2         | 10%     |
| 0x08600103 | 2         | 10%     |
| 0x806ec    | 1         | 5%      |
| 0x806eb    | 1         | 5%      |
| 0x806e9    | 1         | 5%      |
| 0x706e5    | 1         | 5%      |
| 0x706a8    | 1         | 5%      |
| 0x406e3    | 1         | 5%      |
| 0x406c4    | 1         | 5%      |
| 0x206a7    | 1         | 5%      |
| 0x20652    | 1         | 5%      |
| 0x08108109 | 1         | 5%      |
| 0x06006705 | 1         | 5%      |
| Unknown    | 1         | 5%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Westmere      | 3         | 15%     |
| KabyLake      | 3         | 15%     |
| Goldmont plus | 3         | 15%     |
| Zen+          | 2         | 10%     |
| Zen 2         | 2         | 10%     |
| TigerLake     | 2         | 10%     |
| Skylake       | 1         | 5%      |
| Silvermont    | 1         | 5%      |
| SandyBridge   | 1         | 5%      |
| IceLake       | 1         | 5%      |
| Excavator     | 1         | 5%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 13        | 56.52%  |
| AMD    | 6         | 26.09%  |
| Nvidia | 4         | 17.39%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 13.04%  |
| Nvidia TU117M                                                                            | 2         | 8.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 8.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 8.7%    |
| AMD Renoir                                                                               | 2         | 8.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 8.7%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 4.35%   |
| Nvidia GF119M [GeForce 410M]                                                             | 1         | 4.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 4.35%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 4.35%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                        | 1         | 4.35%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 4.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 4.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 4.35%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 4.35%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 1         | 4.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 12        | 60%     |
| 1 x AMD        | 4         | 20%     |
| AMD + Nvidia   | 2         | 10%     |
| 1 x Nvidia     | 1         | 5%      |
| Intel + Nvidia | 1         | 5%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 17        | 85%     |
| Proprietary | 3         | 15%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 65%     |
| 0.01-0.5   | 3         | 15%     |
| 1.01-2.0   | 2         | 10%     |
| 3.01-4.0   | 1         | 5%      |
| 0.51-1.0   | 1         | 5%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 6         | 28.57%  |
| Chimei Innolux          | 5         | 23.81%  |
| AU Optronics            | 4         | 19.05%  |
| Sony                    | 1         | 4.76%   |
| Samsung Electronics     | 1         | 4.76%   |
| Philips                 | 1         | 4.76%   |
| PANDA                   | 1         | 4.76%   |
| Dell                    | 1         | 4.76%   |
| Chi Mei Optoelectronics | 1         | 4.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 9.09%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 9.09%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 2         | 9.09%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                    | 1         | 4.55%   |
| Samsung Electronics LCD Monitor SEC3142 1366x768 309x174mm 14.0-inch     | 1         | 4.55%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 1210x680mm 54.6-inch   | 1         | 4.55%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch                  | 1         | 4.55%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 1         | 4.55%   |
| Dell P2319H DELD0D7 1920x1080 509x286mm 23.0-inch                        | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 4.55%   |
| Chi Mei Optoelectronics LCD Monitor CMO1465 1366x768 309x174mm 14.0-inch | 1         | 4.55%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                    | 1         | 4.55%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                    | 1         | 4.55%   |
| BOE LCD Monitor BOE07AA 1366x768 344x194mm 15.5-inch                     | 1         | 4.55%   |
| BOE LCD BOE07E7 1920x1080 294x165mm 13.3-inch                            | 1         | 4.55%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 1         | 4.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 11        | 52.38%  |
| 1920x1080 (FHD) | 10        | 47.62%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 14        | 63.64%  |
| 14     | 3         | 13.64%  |
| 54     | 1         | 4.55%   |
| 24     | 1         | 4.55%   |
| 23     | 1         | 4.55%   |
| 17     | 1         | 4.55%   |
| 13     | 1         | 4.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 77.27%  |
| 501-600     | 2         | 9.09%   |
| 351-400     | 1         | 4.55%   |
| 201-300     | 1         | 4.55%   |
| 1001-1500   | 1         | 4.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 19        | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 13        | 59.09%  |
| 81-90          | 3         | 13.64%  |
| 201-250        | 2         | 9.09%   |
| More than 1000 | 1         | 4.55%   |
| 71-80          | 1         | 4.55%   |
| 121-130        | 1         | 4.55%   |
| 91-100         | 1         | 4.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 11        | 50%     |
| 121-160 | 7         | 31.82%  |
| 51-100  | 2         | 9.09%   |
| 1-50    | 1         | 4.55%   |
| 161-240 | 1         | 4.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 17        | 85%     |
| 2     | 3         | 15%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 11        | 39.29%  |
| Intel                    | 9         | 32.14%  |
| Qualcomm Atheros         | 5         | 17.86%  |
| Marvell Technology Group | 1         | 3.57%   |
| Broadcom Limited         | 1         | 3.57%   |
| ASIX Electronics         | 1         | 3.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 10.34%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 3         | 10.34%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 3         | 10.34%  |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 2         | 6.9%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 6.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2         | 6.9%    |
| Intel Wi-Fi 6 AX201                                                            | 2         | 6.9%    |
| Intel Wi-Fi 6 AX200                                                            | 2         | 6.9%    |
| Intel Centrino Advanced-N 6200                                                 | 2         | 6.9%    |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 3.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 3.45%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 3.45%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 3.45%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 3.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 1         | 3.45%   |
| Broadcom Limited NetXtreme BCM57760 Gigabit Ethernet PCIe                      | 1         | 3.45%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 3.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 47.37%  |
| Realtek Semiconductor | 5         | 26.32%  |
| Qualcomm Atheros      | 5         | 26.32%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 15.79%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 15.79%  |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 10.53%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 10.53%  |
| Intel Wi-Fi 6 AX201                                            | 2         | 10.53%  |
| Intel Wi-Fi 6 AX200                                            | 2         | 10.53%  |
| Intel Centrino Advanced-N 6200                                 | 2         | 10.53%  |
| Intel Wireless 8265 / 8275                                     | 1         | 5.26%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 5.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 5.26%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 6         | 60%     |
| Qualcomm Atheros         | 1         | 10%     |
| Marvell Technology Group | 1         | 10%     |
| Broadcom Limited         | 1         | 10%     |
| ASIX Electronics         | 1         | 10%     |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 3         | 30%     |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 20%     |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 10%     |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 10%     |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 10%     |
| Broadcom Limited NetXtreme BCM57760 Gigabit Ethernet PCIe                      | 1         | 10%     |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 10%     |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 19        | 67.86%  |
| Ethernet | 9         | 32.14%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 18        | 85.71%  |
| Ethernet | 3         | 14.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 11        | 55%     |
| 2     | 8         | 40%     |
| 0     | 1         | 5%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 12        | 60%     |
| Yes  | 8         | 40%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 7         | 38.89%  |
| IMC Networks                    | 5         | 27.78%  |
| Lite-On Technology              | 2         | 11.11%  |
| Foxconn / Hon Hai               | 2         | 11.11%  |
| Qualcomm Atheros Communications | 1         | 5.56%   |
| Hewlett-Packard                 | 1         | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 4         | 22.22%  |
| IMC Networks Bluetooth Radio                                                        | 4         | 22.22%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 11.11%  |
| Intel AX200 Bluetooth                                                               | 2         | 11.11%  |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 5.56%   |
| Intel Bluetooth wireless interface                                                  | 1         | 5.56%   |
| IMC Networks Bluetooth Device                                                       | 1         | 5.56%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                                          | 1         | 5.56%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 5.56%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 14        | 60.87%  |
| AMD    | 6         | 26.09%  |
| Nvidia | 3         | 13.04%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 15.38%  |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 11.54%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 11.54%  |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 7.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 7.69%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 7.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 7.69%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 3.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 3.85%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 3.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 3.85%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 3.85%   |
| AMD High Definition Audio Controller                                       | 1         | 3.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 3.85%   |

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

| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Quanta                | 5         | 26.32%  |
| IMC Networks          | 5         | 26.32%  |
| Chicony Electronics   | 4         | 21.05%  |
| Sonix Technology      | 2         | 10.53%  |
| Silicon Motion        | 1         | 5.26%   |
| Realtek Semiconductor | 1         | 5.26%   |
| Microdia              | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam       | 4         | 21.05%  |
| Quanta HD User Facing                    | 3         | 15.79%  |
| Sonix USB2.0 HD UVC WebCam               | 2         | 10.53%  |
| Quanta USB2.0 HD UVC WebCam              | 2         | 10.53%  |
| Silicon Motion WebCam SCB-0385N          | 1         | 5.26%   |
| Realtek MTD Camera                       | 1         | 5.26%   |
| Microdia Webcam                          | 1         | 5.26%   |
| IMC Networks USB2.0 HD UVC WebCam        | 1         | 5.26%   |
| Chicony USB2.0 VGA UVC WebCam            | 1         | 5.26%   |
| Chicony Sony Visual Communication Camera | 1         | 5.26%   |
| Chicony HD WebCam                        | 1         | 5.26%   |
| Chicony 1.3M Webcam                      | 1         | 5.26%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| LighTuning Technology | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| LighTuning Fingerprint Reader | 1         | 100%    |

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

| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 13        | 65%     |
| 1     | 7         | 35%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 5         | 71.43%  |
| Fingerprint reader    | 1         | 14.29%  |
| Bluetooth             | 1         | 14.29%  |

