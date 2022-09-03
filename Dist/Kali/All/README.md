Kali - Hardware Trends
----------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Kali/Desktop/README.md) and [notebooks](/Dist/Kali/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/linuxhw/TestCoverage)

Period: Aug, 2022.

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

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Kali 2022.3 | 45        | 83.33%  |
| Kali 2022.2 | 6         | 11.11%  |
| Kali 2022.1 | 2         | 3.7%    |
| Kali 2021.4 | 1         | 1.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| Kali | 54        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.18.0-kali5-amd64   | 44        | 81.48%  |
| 5.16.0-kali7-amd64   | 4         | 7.41%   |
| 4.14.113-22495969    | 2         | 3.7%    |
| 5.16.0-kali6-amd64   | 1         | 1.85%   |
| 5.15.0-kali3-amd64   | 1         | 1.85%   |
| 5.14.0-kali4-amd64   | 1         | 1.85%   |
| 5.10.103-Re4son-v7l+ | 1         | 1.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.18.0   | 44        | 81.48%  |
| 5.16.0   | 5         | 9.26%   |
| 4.14.113 | 2         | 3.7%    |
| 5.15.0   | 1         | 1.85%   |
| 5.14.0   | 1         | 1.85%   |
| 5.10.103 | 1         | 1.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.18    | 44        | 81.48%  |
| 5.16    | 5         | 9.26%   |
| 4.14    | 2         | 3.7%    |
| 5.15    | 1         | 1.85%   |
| 5.14    | 1         | 1.85%   |
| 5.10    | 1         | 1.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 51        | 94.44%  |
| aarch64 | 2         | 3.7%    |
| armv7l  | 1         | 1.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| XFCE    | 38        | 70.37%  |
| GNOME   | 9         | 16.67%  |
| KDE5    | 6         | 11.11%  |
| Unknown | 1         | 1.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 52        | 96.3%   |
| Wayland | 2         | 3.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 36        | 66.67%  |
| SDDM    | 7         | 12.96%  |
| GDM3    | 6         | 11.11%  |
| Unknown | 5         | 9.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 31        | 57.41%  |
| de_DE   | 4         | 7.41%   |
| en_IN   | 3         | 5.56%   |
| Unknown | 3         | 5.56%   |
| ru_RU   | 2         | 3.7%    |
| en_GB   | 2         | 3.7%    |
| pt_BR   | 1         | 1.85%   |
| fr_FR   | 1         | 1.85%   |
| fr_CA   | 1         | 1.85%   |
| es_ES   | 1         | 1.85%   |
| es_AR   | 1         | 1.85%   |
| en_ZA   | 1         | 1.85%   |
| en_CA   | 1         | 1.85%   |
| en_AU   | 1         | 1.85%   |
| de_AT   | 1         | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 39        | 72.22%  |
| BIOS | 15        | 27.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 50        | 92.59%  |
| Overlay | 2         | 3.7%    |
| Ext3    | 1         | 1.85%   |
| Btrfs   | 1         | 1.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 41        | 75.93%  |
| Unknown | 7         | 12.96%  |
| MBR     | 6         | 11.11%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 92.59%  |
| Yes       | 4         | 7.41%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 66.67%  |
| Yes       | 18        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 13        | 24.07%  |
| Hewlett-Packard         | 12        | 22.22%  |
| Dell                    | 8         | 14.81%  |
| Acer                    | 3         | 5.56%   |
| MSI                     | 2         | 3.7%    |
| Lenovo                  | 2         | 3.7%    |
| Gigabyte Technology     | 2         | 3.7%    |
| Apple                   | 2         | 3.7%    |
| Unknown                 | 2         | 3.7%    |
| Sony                    | 1         | 1.85%   |
| Samsung Electronics     | 1         | 1.85%   |
| Raspberry Pi Foundation | 1         | 1.85%   |
| Novatech                | 1         | 1.85%   |
| Microsoft               | 1         | 1.85%   |
| MicroByte               | 1         | 1.85%   |
| IPASON                  | 1         | 1.85%   |
| Google                  | 1         | 1.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                                           | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 2         | 3.7%    |
| Sony VPCZ12M9E                                                 | 1         | 1.85%   |
| Samsung GTA4XLWIFI EUR OPEN 04A board based on EXYNOS9611 (DT) | 1         | 1.85%   |
| RPi Raspberry Pi                                               | 1         | 1.85%   |
| Novatech C141WP-I5HS                                           | 1         | 1.85%   |
| MSI MS-7D18                                                    | 1         | 1.85%   |
| MSI MS-7C02                                                    | 1         | 1.85%   |
| Microsoft Surface Pro 3                                        | 1         | 1.85%   |
| MicroByte ezbook                                               | 1         | 1.85%   |
| Lenovo Yoga C640-13IML 81UE                                    | 1         | 1.85%   |
| Lenovo ThinkPad E15 Gen 4 21EES00100                           | 1         | 1.85%   |
| IPASON MaxBook P1X                                             | 1         | 1.85%   |
| HP ProBook 6540b                                               | 1         | 1.85%   |
| HP ProBook 440 G5                                              | 1         | 1.85%   |
| HP OMEN Laptop 15-ek0xxx                                       | 1         | 1.85%   |
| HP Laptop 15-dw0xxx                                            | 1         | 1.85%   |
| HP Laptop 15 3v0c9ea                                           | 1         | 1.85%   |
| HP ENVY m6                                                     | 1         | 1.85%   |
| HP EliteBook 820 G3                                            | 1         | 1.85%   |
| HP EliteBook 820 G1                                            | 1         | 1.85%   |
| HP EliteBook 645 14 inch G9 Notebook PC                        | 1         | 1.85%   |
| HP Compaq 620                                                  | 1         | 1.85%   |
| HP 245 G7 Notebook PC                                          | 1         | 1.85%   |
| HP 205 G2 AiO Business PC                                      | 1         | 1.85%   |
| Google Bard                                                    | 1         | 1.85%   |
| Gigabyte B550 AORUS ELITE V2                                   | 1         | 1.85%   |
| Gigabyte AB350M-DS3H                                           | 1         | 1.85%   |
| Dell Precision M4600                                           | 1         | 1.85%   |
| Dell Precision 3551                                            | 1         | 1.85%   |
| Dell OptiPlex 780                                              | 1         | 1.85%   |
| Dell OptiPlex 7050                                             | 1         | 1.85%   |
| Dell Latitude E5470                                            | 1         | 1.85%   |
| Dell Latitude 7290                                             | 1         | 1.85%   |
| Dell Inspiron 3542                                             | 1         | 1.85%   |
| Dell Inspiron 15-3567                                          | 1         | 1.85%   |
| ASUS X541UV                                                    | 1         | 1.85%   |
| ASUS VivoBook_ASUSLaptop X531FL_S531FL                         | 1         | 1.85%   |
| ASUS VivoBook_ASUSLaptop TP412FA_TP412FA                       | 1         | 1.85%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR                           | 1         | 1.85%   |
| ASUS TUF Z390-PLUS GAMING                                      | 1         | 1.85%   |
| ASUS ROG Strix G533ZW_G533ZW                                   | 1         | 1.85%   |
| ASUS ROG STRIX B550-F GAMING                                   | 1         | 1.85%   |
| ASUS ROG STRIX B450-F GAMING II                                | 1         | 1.85%   |
| ASUS ROG STRIX B365-G GAMING                                   | 1         | 1.85%   |
| ASUS P7P55-M                                                   | 1         | 1.85%   |
| ASUS H170 PRO GAMING                                           | 1         | 1.85%   |
| ASUS G750JM                                                    | 1         | 1.85%   |
| ASUS Crosshair IV Formula                                      | 1         | 1.85%   |
| Apple Macmini6,1                                               | 1         | 1.85%   |
| Apple MacBookPro14,1                                           | 1         | 1.85%   |
| Acer Nitro AN515-43                                            | 1         | 1.85%   |
| Acer Aspire R5-471T                                            | 1         | 1.85%   |
| Acer Aspire 5755G                                              | 1         | 1.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| ASUS ROG             | 4         | 7.41%   |
| HP EliteBook         | 3         | 5.56%   |
| ASUS VivoBook        | 3         | 5.56%   |
| HP ProBook           | 2         | 3.7%    |
| HP Laptop            | 2         | 3.7%    |
| Dell Precision       | 2         | 3.7%    |
| Dell OptiPlex        | 2         | 3.7%    |
| Dell Latitude        | 2         | 3.7%    |
| Dell Inspiron        | 2         | 3.7%    |
| Acer Aspire          | 2         | 3.7%    |
| Unknown              | 2         | 3.7%    |
| Sony VPCZ12M9E       | 1         | 1.85%   |
| Samsung GTA4XLWIFI   | 1         | 1.85%   |
| RPi Raspberry        | 1         | 1.85%   |
| Novatech C141WP-I5HS | 1         | 1.85%   |
| MSI MS-7D18          | 1         | 1.85%   |
| MSI MS-7C02          | 1         | 1.85%   |
| Microsoft Surface    | 1         | 1.85%   |
| MicroByte ezbook     | 1         | 1.85%   |
| Lenovo Yoga          | 1         | 1.85%   |
| Lenovo ThinkPad      | 1         | 1.85%   |
| IPASON MaxBook       | 1         | 1.85%   |
| HP OMEN              | 1         | 1.85%   |
| HP ENVY              | 1         | 1.85%   |
| HP Compaq            | 1         | 1.85%   |
| HP 245               | 1         | 1.85%   |
| HP 205               | 1         | 1.85%   |
| Google Bard          | 1         | 1.85%   |
| Gigabyte B550        | 1         | 1.85%   |
| Gigabyte AB350M-DS3H | 1         | 1.85%   |
| ASUS X541UV          | 1         | 1.85%   |
| ASUS TUF             | 1         | 1.85%   |
| ASUS P7P55-M         | 1         | 1.85%   |
| ASUS H170            | 1         | 1.85%   |
| ASUS G750JM          | 1         | 1.85%   |
| ASUS Crosshair       | 1         | 1.85%   |
| Apple Macmini6       | 1         | 1.85%   |
| Apple MacBookPro14   | 1         | 1.85%   |
| Acer Nitro           | 1         | 1.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 7         | 12.96%  |
| 2022    | 5         | 9.26%   |
| 2021    | 5         | 9.26%   |
| 2020    | 5         | 9.26%   |
| 2018    | 5         | 9.26%   |
| 2016    | 5         | 9.26%   |
| 2017    | 4         | 7.41%   |
| 2010    | 4         | 7.41%   |
| 2012    | 3         | 5.56%   |
| 2011    | 3         | 5.56%   |
| Unknown | 3         | 5.56%   |
| 2015    | 2         | 3.7%    |
| 2014    | 2         | 3.7%    |
| 2013    | 1         | 1.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 33        | 61.11%  |
| Desktop        | 13        | 24.07%  |
| System on chip | 3         | 5.56%   |
| Convertible    | 2         | 3.7%    |
| Tablet         | 1         | 1.85%   |
| Mini pc        | 1         | 1.85%   |
| All in one     | 1         | 1.85%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 54        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 53        | 98.15%  |
| Yes  | 1         | 1.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 18        | 33.33%  |
| 3.01-4.0    | 10        | 18.52%  |
| 8.01-16.0   | 10        | 18.52%  |
| 32.01-64.0  | 9         | 16.67%  |
| 16.01-24.0  | 4         | 7.41%   |
| 2.01-3.0    | 1         | 1.85%   |
| 64.01-256.0 | 1         | 1.85%   |
| 1.01-2.0    | 1         | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 17        | 31.48%  |
| 1.01-2.0  | 14        | 25.93%  |
| 4.01-8.0  | 12        | 22.22%  |
| 3.01-4.0  | 6         | 11.11%  |
| 8.01-16.0 | 3         | 5.56%   |
| 0.51-1.0  | 2         | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 55.56%  |
| 2      | 18        | 33.33%  |
| 3      | 3         | 5.56%   |
| 0      | 2         | 3.7%    |
| 6      | 1         | 1.85%   |

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
| Yes       | 42        | 77.78%  |
| No        | 12        | 22.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 96.3%   |
| No        | 2         | 3.7%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 72.22%  |
| No        | 15        | 27.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 18        | 33.33%  |
| Germany      | 5         | 9.26%   |
| UK           | 3         | 5.56%   |
| Russia       | 3         | 5.56%   |
| India        | 3         | 5.56%   |
| Ukraine      | 2         | 3.7%    |
| Serbia       | 2         | 3.7%    |
| Norway       | 2         | 3.7%    |
| France       | 2         | 3.7%    |
| Canada       | 2         | 3.7%    |
| Sweden       | 1         | 1.85%   |
| Sri Lanka    | 1         | 1.85%   |
| Spain        | 1         | 1.85%   |
| South Africa | 1         | 1.85%   |
| Netherlands  | 1         | 1.85%   |
| Jordan       | 1         | 1.85%   |
| Italy        | 1         | 1.85%   |
| Indonesia    | 1         | 1.85%   |
| Brazil       | 1         | 1.85%   |
| Austria      | 1         | 1.85%   |
| Australia    | 1         | 1.85%   |
| Argentina    | 1         | 1.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Phoenix               | 2         | 3.7%    |
| Pasadena              | 2         | 3.7%    |
| Kherson               | 2         | 3.7%    |
| Elkhart               | 2         | 3.7%    |
| Belgrade              | 2         | 3.7%    |
| Yekaterinburg         | 1         | 1.85%   |
| Vienna                | 1         | 1.85%   |
| Tucson                | 1         | 1.85%   |
| Trondheim             | 1         | 1.85%   |
| Trois-Rivières       | 1         | 1.85%   |
| Sydney                | 1         | 1.85%   |
| Stuttgart             | 1         | 1.85%   |
| Schwalbach            | 1         | 1.85%   |
| Round Lake            | 1         | 1.85%   |
| Rock Springs          | 1         | 1.85%   |
| Pune                  | 1         | 1.85%   |
| Pretoria              | 1         | 1.85%   |
| Okemos                | 1         | 1.85%   |
| Newark                | 1         | 1.85%   |
| Namsos                | 1         | 1.85%   |
| Nagercoil             | 1         | 1.85%   |
| Mumbai                | 1         | 1.85%   |
| Modesto               | 1         | 1.85%   |
| Marbella              | 1         | 1.85%   |
| Lyon                  | 1         | 1.85%   |
| Los Angeles           | 1         | 1.85%   |
| Liverpool             | 1         | 1.85%   |
| Las Vegas             | 1         | 1.85%   |
| Kista                 | 1         | 1.85%   |
| Khabarovsk            | 1         | 1.85%   |
| Kazan’              | 1         | 1.85%   |
| Jakarta               | 1         | 1.85%   |
| Heilbad Heiligenstadt | 1         | 1.85%   |
| Edmond                | 1         | 1.85%   |
| Draguignan            | 1         | 1.85%   |
| Denver                | 1         | 1.85%   |
| Defiance              | 1         | 1.85%   |
| Corrientes            | 1         | 1.85%   |
| Colombo               | 1         | 1.85%   |
| Bristol               | 1         | 1.85%   |
| Braunschweig          | 1         | 1.85%   |
| Brasília             | 1         | 1.85%   |
| Berlin                | 1         | 1.85%   |
| Bellizzi              | 1         | 1.85%   |
| Bella Vista           | 1         | 1.85%   |
| Balham                | 1         | 1.85%   |
| Amman                 | 1         | 1.85%   |
| Airdrie               | 1         | 1.85%   |
| Unknown               | 1         | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 12     | 13.7%   |
| Seagate             | 9         | 10     | 12.33%  |
| WDC                 | 8         | 9      | 10.96%  |
| Toshiba             | 7         | 9      | 9.59%   |
| Kingston            | 5         | 6      | 6.85%   |
| Unknown             | 4         | 5      | 5.48%   |
| SanDisk             | 4         | 5      | 5.48%   |
| A-DATA Technology   | 4         | 4      | 5.48%   |
| Hitachi             | 3         | 3      | 4.11%   |
| SK hynix            | 2         | 2      | 2.74%   |
| Intel               | 2         | 2      | 2.74%   |
| Unknown             | 2         | 2      | 2.74%   |
| XrayDisk            | 1         | 1      | 1.37%   |
| UMIS                | 1         | 1      | 1.37%   |
| SPCC                | 1         | 1      | 1.37%   |
| Silicon Motion      | 1         | 2      | 1.37%   |
| Phison              | 1         | 1      | 1.37%   |
| NFORCE              | 1         | 1      | 1.37%   |
| Micron Technology   | 1         | 1      | 1.37%   |
| Maxtor              | 1         | 1      | 1.37%   |
| KingSpec            | 1         | 1      | 1.37%   |
| KingFast            | 1         | 1      | 1.37%   |
| HGST                | 1         | 1      | 1.37%   |
| China               | 1         | 1      | 1.37%   |
| Apple               | 1         | 2      | 1.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Samsung SSD 970 EVO Plus 2TB             | 2         | 2.47%   |
| Kingston SV300S37A120G 120GB SSD         | 2         | 2.47%   |
| Unknown                                  | 2         | 2.47%   |
| XrayDisk SSD 512GB                       | 1         | 1.23%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD         | 1         | 1.23%   |
| WDC WDS200T2B0A-00SM50 2TB SSD           | 1         | 1.23%   |
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1         | 1.23%   |
| WDC WD5000LPZX-60Z10T0 500GB             | 1         | 1.23%   |
| WDC WD40EFAX-68JH4N0 4TB                 | 1         | 1.23%   |
| WDC WD30EZRX-00MMMB0 3TB                 | 1         | 1.23%   |
| WDC WD10SPZX-60Z10T1 1TB                 | 1         | 1.23%   |
| WDC WD10SPZX-60Z10T0 1TB                 | 1         | 1.23%   |
| WDC PC SN520 SDAPNUW-512G-1114 512GB     | 1         | 1.23%   |
| Unknown USDU1  64GB                      | 1         | 1.23%   |
| Unknown USDU1  32GB                      | 1         | 1.23%   |
| Unknown SS08G  8GB                       | 1         | 1.23%   |
| Unknown SR128  128GB                     | 1         | 1.23%   |
| Unknown DA4128  128GB                    | 1         | 1.23%   |
| UMIS RPJTJ512MGE1QDQ 512GB               | 1         | 1.23%   |
| Toshiba THNS064GG2BNAA 64GB SSD          | 1         | 1.23%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1.23%   |
| Toshiba MQ01ACF050 500GB                 | 1         | 1.23%   |
| Toshiba MQ01ABF050 500GB                 | 1         | 1.23%   |
| Toshiba MK7559GSXP 752GB                 | 1         | 1.23%   |
| Toshiba KBG40ZNT256G MEMORY 256GB        | 1         | 1.23%   |
| Toshiba HDWR160 6TB                      | 1         | 1.23%   |
| Toshiba HDWE150 5TB                      | 1         | 1.23%   |
| SPCC Solid State Disk 256GB              | 1         | 1.23%   |
| SK hynix SC311 SATA 256GB SSD            | 1         | 1.23%   |
| SK hynix PC300 NVMe 512GB                | 1         | 1.23%   |
| Silicon Motion NVMe SSD Drive 512GB      | 1         | 1.23%   |
| Silicon Motion NVME SSD 512GB            | 1         | 1.23%   |
| Seagate ST9750420AS 752GB                | 1         | 1.23%   |
| Seagate ST9160821AS 160GB                | 1         | 1.23%   |
| Seagate ST6000NM0044 6TB                 | 1         | 1.23%   |
| Seagate ST500DM002-1BD142 500GB          | 1         | 1.23%   |
| Seagate ST3500418AS 500GB                | 1         | 1.23%   |
| Seagate ST2000DM008-2UB102 2TB           | 1         | 1.23%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 1.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1.23%   |
| Seagate ST1000DM003-1SB102 1TB           | 1         | 1.23%   |
| Seagate BarraCuda SSD ZA500CM10002 500GB | 1         | 1.23%   |
| SanDisk Ultra II 480GB SSD               | 1         | 1.23%   |
| SanDisk SDSSDH3 1T02 1TB                 | 1         | 1.23%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD      | 1         | 1.23%   |
| SanDisk NVMe SSD Drive 256GB             | 1         | 1.23%   |
| Samsung SSD 980 PRO 2TB                  | 1         | 1.23%   |
| Samsung SSD 970 EVO 500GB                | 1         | 1.23%   |
| Samsung SSD 860 EVO 500GB                | 1         | 1.23%   |
| Samsung SSD 850 EVO 500GB                | 1         | 1.23%   |
| Samsung SSD 840 Series 120GB             | 1         | 1.23%   |
| Samsung SSD 840 EVO 120GB                | 1         | 1.23%   |
| Samsung PSSD T7 1TB                      | 1         | 1.23%   |
| Samsung MZVLQ512HBLU-00BH1 512GB         | 1         | 1.23%   |
| Samsung MZVLB512HBJQ-000H1 512GB         | 1         | 1.23%   |
| Samsung MZMTE256HMHP-000MV 256GB SSD     | 1         | 1.23%   |
| Phison MSI M390 1TB                      | 1         | 1.23%   |
| NFORCE 25625G2 TAS-SSQE3 256GB SSD       | 1         | 1.23%   |
| Micron 3400_MTFDKBA1T0TFH 1TB            | 1         | 1.23%   |
| Maxtor 6Y080M0 81GB                      | 1         | 1.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 9      | 34.78%  |
| WDC     | 5         | 5      | 21.74%  |
| Toshiba | 5         | 6      | 21.74%  |
| Hitachi | 3         | 3      | 13.04%  |
| Maxtor  | 1         | 1      | 4.35%   |
| HGST    | 1         | 1      | 4.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 6      | 17.86%  |
| Kingston            | 4         | 4      | 14.29%  |
| WDC                 | 3         | 3      | 10.71%  |
| SanDisk             | 3         | 4      | 10.71%  |
| A-DATA Technology   | 2         | 2      | 7.14%   |
| Unknown             | 2         | 2      | 7.14%   |
| XrayDisk            | 1         | 1      | 3.57%   |
| Toshiba             | 1         | 2      | 3.57%   |
| SPCC                | 1         | 1      | 3.57%   |
| SK hynix            | 1         | 1      | 3.57%   |
| Seagate             | 1         | 1      | 3.57%   |
| NFORCE              | 1         | 1      | 3.57%   |
| KingSpec            | 1         | 1      | 3.57%   |
| KingFast            | 1         | 1      | 3.57%   |
| China               | 1         | 1      | 3.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 25        | 31     | 37.31%  |
| HDD  | 20        | 25     | 29.85%  |
| NVMe | 18        | 23     | 26.87%  |
| MMC  | 4         | 5      | 5.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 39        | 55     | 62.9%   |
| NVMe | 18        | 23     | 29.03%  |
| MMC  | 4         | 5      | 6.45%   |
| SAS  | 1         | 1      | 1.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 33     | 58.33%  |
| 0.51-1.0   | 14        | 16     | 29.17%  |
| 1.01-2.0   | 2         | 2      | 4.17%   |
| 4.01-10.0  | 2         | 3      | 4.17%   |
| 3.01-4.0   | 1         | 1      | 2.08%   |
| 2.01-3.0   | 1         | 1      | 2.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 19        | 35.19%  |
| 251-500        | 16        | 29.63%  |
| 501-1000       | 6         | 11.11%  |
| More than 3000 | 3         | 5.56%   |
| 51-100         | 3         | 5.56%   |
| Unknown        | 3         | 5.56%   |
| 21-50          | 2         | 3.7%    |
| 1001-2000      | 1         | 1.85%   |
| 1-20           | 1         | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 14        | 25.93%  |
| 21-50          | 12        | 22.22%  |
| 51-100         | 11        | 20.37%  |
| 101-250        | 9         | 16.67%  |
| Unknown        | 3         | 5.56%   |
| 251-500        | 2         | 3.7%    |
| 1001-2000      | 2         | 3.7%    |
| More than 3000 | 1         | 1.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD5000LPZX-60Z10T0 500GB     | 1         | 1      | 16.67%  |
| Seagate ST500DM002-1BD142 500GB  | 1         | 1      | 16.67%  |
| Kingston SV300S37A120G 120GB SSD | 1         | 1      | 16.67%  |
| Hitachi HTS725050A9A360 500GB    | 1         | 1      | 16.67%  |
| Hitachi HTS543232L9A300 320GB    | 1         | 1      | 16.67%  |
| Hitachi HTS541010A9E680 1TB      | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Hitachi  | 3         | 3      | 50%     |
| WDC      | 1         | 1      | 16.67%  |
| Seagate  | 1         | 1      | 16.67%  |
| Kingston | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 60%     |
| WDC     | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 83.33%  |
| SSD  | 1         | 1      | 16.67%  |

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
| Works    | 40        | 63     | 71.43%  |
| Detected | 10        | 15     | 17.86%  |
| Malfunc  | 6         | 6      | 10.71%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 36        | 54.55%  |
| AMD                         | 10        | 15.15%  |
| Samsung Electronics         | 6         | 9.09%   |
| SanDisk                     | 2         | 3.03%   |
| ADATA Technology            | 2         | 3.03%   |
| VIA Technologies            | 1         | 1.52%   |
| Union Memory (Shenzhen)     | 1         | 1.52%   |
| SK hynix                    | 1         | 1.52%   |
| Silicon Motion              | 1         | 1.52%   |
| Phison Electronics          | 1         | 1.52%   |
| Micron Technology           | 1         | 1.52%   |
| KIOXIA                      | 1         | 1.52%   |
| Kingston Technology Company | 1         | 1.52%   |
| JMicron Technology          | 1         | 1.52%   |
| Apple                       | 1         | 1.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 9.33%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 8%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 6.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 5.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 4%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 4%      |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.67%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 2.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2         | 2.67%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2         | 2.67%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 2.67%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 2.67%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 2.67%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1         | 1.33%   |
| Union Memory (Shenzhen) AM630 PCIe 4.0 x4 NVMe SSD Controller                  | 1         | 1.33%   |
| SK hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 1.33%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 1.33%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 1.33%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 1.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.33%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.33%   |
| Phison Electronics Non-Volatile memory controller                              | 1         | 1.33%   |
| Micron Non-Volatile memory controller                                          | 1         | 1.33%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 1.33%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 1.33%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1         | 1.33%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.33%   |
| Intel SSD 660P Series                                                          | 1         | 1.33%   |
| Intel SSD 600P Series                                                          | 1         | 1.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.33%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.33%   |
| Intel Comet Lake PCH-H RAID                                                    | 1         | 1.33%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.33%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 1.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.33%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 1.33%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 1         | 1.33%   |
| Apple S3X NVMe Controller                                                      | 1         | 1.33%   |
| AMD X370 Series Chipset SATA Controller                                        | 1         | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1         | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1         | 1.33%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 1.33%   |
| ADATA ADATA XPG GAMMIXS1 1L Media                                              | 1         | 1.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 34        | 50.75%  |
| NVMe | 18        | 26.87%  |
| RAID | 10        | 14.93%  |
| IDE  | 5         | 7.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 39        | 72.22%  |
| AMD    | 12        | 22.22%  |
| ARM    | 3         | 5.56%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 3.7%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 3.7%    |
| ARM Processor                                 | 2         | 3.7%    |
| AMD Ryzen 7 5825U with Radeon Graphics        | 2         | 3.7%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 1.85%   |
| Intel Genuine 0000 @ 1.80GHz                  | 1         | 1.85%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 1         | 1.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.85%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 1.85%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 1.85%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 1.85%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 1.85%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 1.85%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 1.85%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.85%   |
| Intel Core i5-7360U CPU @ 2.30GHz             | 1         | 1.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.85%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 1         | 1.85%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.85%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 1.85%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.85%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.85%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.85%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 1.85%   |
| Intel Core i5 CPU 750 @ 2.67GHz               | 1         | 1.85%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 1         | 1.85%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 1.85%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 1         | 1.85%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 1.85%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.85%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 1.85%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz          | 1         | 1.85%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 1         | 1.85%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 1.85%   |
| Intel Celeron J4005 CPU @ 2.00GHz             | 1         | 1.85%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 1         | 1.85%   |
| Intel 12th Gen Core i9-12900H                 | 1         | 1.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 1.85%   |
| ARM BCM2711 Processor                         | 1         | 1.85%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 1.85%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 1         | 1.85%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 1         | 1.85%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 1.85%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 1         | 1.85%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 1         | 1.85%   |
| AMD Ryzen 3 3300U with Radeon Vega Mobile Gfx | 1         | 1.85%   |
| AMD E1-6010 APU with AMD Radeon R2 Graphics   | 1         | 1.85%   |
| AMD Athlon II X2 250 Processor                | 1         | 1.85%   |
| AMD A10-4600M APU with Radeon HD Graphics     | 1         | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 15        | 27.78%  |
| Intel Core i7        | 9         | 16.67%  |
| Intel Core i3        | 6         | 11.11%  |
| Other                | 4         | 7.41%   |
| AMD Ryzen 5          | 4         | 7.41%   |
| Intel Celeron        | 3         | 5.56%   |
| AMD Ryzen 7          | 3         | 5.56%   |
| Intel Core 2 Duo     | 2         | 3.7%    |
| Intel Pentium Silver | 1         | 1.85%   |
| Intel Genuine        | 1         | 1.85%   |
| ARM BCM              | 1         | 1.85%   |
| AMD Ryzen 9          | 1         | 1.85%   |
| AMD Ryzen 3          | 1         | 1.85%   |
| AMD E1               | 1         | 1.85%   |
| AMD Athlon II X2     | 1         | 1.85%   |
| AMD A10              | 1         | 1.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 23        | 42.59%  |
| 4      | 19        | 35.19%  |
| 8      | 5         | 9.26%   |
| 6      | 5         | 9.26%   |
| 14     | 1         | 1.85%   |
| 12     | 1         | 1.85%   |

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
| 2      | 39        | 72.22%  |
| 1      | 15        | 27.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 53        | 98.15%  |
| Unknown        | 1         | 1.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x406e3    | 5         | 9.26%   |
| Unknown    | 5         | 9.26%   |
| 0x806ea    | 3         | 5.56%   |
| 0x40651    | 3         | 5.56%   |
| 0xa0652    | 2         | 3.7%    |
| 0x806ec    | 2         | 3.7%    |
| 0x806e9    | 2         | 3.7%    |
| 0x706a8    | 2         | 3.7%    |
| 0x1067a    | 2         | 3.7%    |
| 0x0a50000c | 2         | 3.7%    |
| 0xa0670    | 1         | 1.85%   |
| 0x906ed    | 1         | 1.85%   |
| 0x906eb    | 1         | 1.85%   |
| 0x906e9    | 1         | 1.85%   |
| 0x906a3    | 1         | 1.85%   |
| 0x806eb    | 1         | 1.85%   |
| 0x806c1    | 1         | 1.85%   |
| 0x706e5    | 1         | 1.85%   |
| 0x706a1    | 1         | 1.85%   |
| 0x506e3    | 1         | 1.85%   |
| 0x506c9    | 1         | 1.85%   |
| 0x306c3    | 1         | 1.85%   |
| 0x306a9    | 1         | 1.85%   |
| 0x206a7    | 1         | 1.85%   |
| 0x20655    | 1         | 1.85%   |
| 0x20652    | 1         | 1.85%   |
| 0x106e5    | 1         | 1.85%   |
| 0x0a50000d | 1         | 1.85%   |
| 0x0a201204 | 1         | 1.85%   |
| 0x08701021 | 1         | 1.85%   |
| 0x08108109 | 1         | 1.85%   |
| 0x08108102 | 1         | 1.85%   |
| 0x0800820d | 1         | 1.85%   |
| 0x08001129 | 1         | 1.85%   |
| 0x07030105 | 1         | 1.85%   |
| 0x06001119 | 1         | 1.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 11        | 20.37%  |
| Skylake       | 6         | 11.11%  |
| Zen 3         | 4         | 7.41%   |
| Haswell       | 4         | 7.41%   |
| Unknown       | 4         | 7.41%   |
| Zen+          | 3         | 5.56%   |
| Goldmont plus | 3         | 5.56%   |
| Westmere      | 2         | 3.7%    |
| SandyBridge   | 2         | 3.7%    |
| Penryn        | 2         | 3.7%    |
| IceLake       | 2         | 3.7%    |
| CometLake     | 2         | 3.7%    |
| Zen 2         | 1         | 1.85%   |
| Zen           | 1         | 1.85%   |
| TigerLake     | 1         | 1.85%   |
| Puma          | 1         | 1.85%   |
| Piledriver    | 1         | 1.85%   |
| Nehalem       | 1         | 1.85%   |
| K10           | 1         | 1.85%   |
| IvyBridge     | 1         | 1.85%   |
| Goldmont      | 1         | 1.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 36        | 57.14%  |
| Nvidia | 17        | 26.98%  |
| AMD    | 10        | 15.87%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                       | 5         | 7.69%   |
| Intel UHD Graphics 620                                                    | 3         | 4.62%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 4.62%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 3.08%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 3.08%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 3.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 3.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 3.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 3.08%   |
| AMD Barcelo                                                               | 2         | 3.08%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 1         | 1.54%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 1.54%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                     | 1         | 1.54%   |
| Nvidia GT216M [GeForce GT 330M]                                           | 1         | 1.54%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 1.54%   |
| Nvidia GP107M [GeForce MX350]                                             | 1         | 1.54%   |
| Nvidia GP107GLM [Quadro P620]                                             | 1         | 1.54%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 1         | 1.54%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                        | 1         | 1.54%   |
| Nvidia GM108M [GeForce 920MX]                                             | 1         | 1.54%   |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 1.54%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                         | 1         | 1.54%   |
| Nvidia GF108GLM [Quadro 1000M]                                            | 1         | 1.54%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                        | 1         | 1.54%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                             | 1         | 1.54%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                       | 1         | 1.54%   |
| Nvidia G96C [GeForce 9500 GT]                                             | 1         | 1.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 1.54%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                 | 1         | 1.54%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 1.54%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 1.54%   |
| Intel Iris Plus Graphics 640                                              | 1         | 1.54%   |
| Intel HD Graphics 630                                                     | 1         | 1.54%   |
| Intel HD Graphics 620                                                     | 1         | 1.54%   |
| Intel HD Graphics 530                                                     | 1         | 1.54%   |
| Intel HD Graphics 500                                                     | 1         | 1.54%   |
| Intel GeminiLake [UHD Graphics 605]                                       | 1         | 1.54%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 1.54%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1         | 1.54%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 1         | 1.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 1.54%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 1         | 1.54%   |
| AMD Trinity [Radeon HD 7660G]                                             | 1         | 1.54%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                 | 1         | 1.54%   |
| AMD RV620 LE [Radeon HD 3450]                                             | 1         | 1.54%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]         | 1         | 1.54%   |
| AMD Mullins [Radeon R2 Graphics]                                          | 1         | 1.54%   |
| AMD Cezanne                                                               | 1         | 1.54%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                            | 1         | 1.54%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]       | 1         | 1.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 23        | 42.59%  |
| Intel + Nvidia | 11        | 20.37%  |
| 1 x AMD        | 7         | 12.96%  |
| 1 x Nvidia     | 6         | 11.11%  |
| Other          | 3         | 5.56%   |
| 2 x AMD        | 2         | 3.7%    |
| 2 x Intel      | 1         | 1.85%   |
| Intel + AMD    | 1         | 1.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 43        | 79.63%  |
| Proprietary | 7         | 12.96%  |
| Unknown     | 4         | 7.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 59.26%  |
| 0.01-0.5   | 6         | 11.11%  |
| 3.01-4.0   | 5         | 9.26%   |
| 7.01-8.0   | 3         | 5.56%   |
| 1.01-2.0   | 3         | 5.56%   |
| 0.51-1.0   | 3         | 5.56%   |
| 5.01-6.0   | 1         | 1.85%   |
| 8.01-16.0  | 1         | 1.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 10        | 20%     |
| LG Display          | 7         | 14%     |
| Chimei Innolux      | 6         | 12%     |
| BOE                 | 5         | 10%     |
| Samsung Electronics | 4         | 8%      |
| Dell                | 3         | 6%      |
| Sony                | 2         | 4%      |
| Unknown (XXX)       | 1         | 2%      |
| Unknown             | 1         | 2%      |
| Toshiba             | 1         | 2%      |
| TMX                 | 1         | 2%      |
| MXL                 | 1         | 2%      |
| InfoVision          | 1         | 2%      |
| Hewlett-Packard     | 1         | 2%      |
| Goldstar            | 1         | 2%      |
| GJX                 | 1         | 2%      |
| CS_                 | 1         | 2%      |
| ASUSTek Computer    | 1         | 2%      |
| Apple               | 1         | 2%      |
| Acer                | 1         | 2%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor SKYDATA S.P.A. TV-monitor 1360x768                | 1         | 2%      |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch        | 1         | 2%      |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                      | 1         | 2%      |
| TMX TL156VDXP0101 TMX1561 1920x1080 344x194mm 15.5-inch               | 1         | 2%      |
| Sony TV SNY8200 1920x1080 560x420mm 27.6-inch                         | 1         | 2%      |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                         | 1         | 2%      |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1         | 2%      |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch     | 1         | 2%      |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 2%      |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch | 1         | 2%      |
| MXL Projector MXL6786 1920x1080 1600x1000mm 74.3-inch                 | 1         | 2%      |
| LG Display LP156WH2-TLR2 LGD027D 1366x768 344x194mm 15.5-inch         | 1         | 2%      |
| LG Display LCD Monitor LGD061E 1920x1080 344x194mm 15.5-inch          | 1         | 2%      |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch          | 1         | 2%      |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 1         | 2%      |
| LG Display LCD Monitor LGD0404 1366x768 277x156mm 12.5-inch           | 1         | 2%      |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 1         | 2%      |
| LG Display LCD Monitor LGD02AD 1366x768 344x194mm 15.5-inch           | 1         | 2%      |
| InfoVision LCD Monitor IVO8544 1920x1200 286x179mm 13.3-inch          | 1         | 2%      |
| Hewlett-Packard All-in-One HWP4240 1366x768 344x194mm 15.5-inch       | 1         | 2%      |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 2%      |
| GJX LCD Monitor GJX0704 1366x768 344x194mm 15.5-inch                  | 1         | 2%      |
| Dell U3818DW DELA0F3 3840x1600 880x367mm 37.5-inch                    | 1         | 2%      |
| Dell P2213 DELF041 1680x1050 470x300mm 22.0-inch                      | 1         | 2%      |
| Dell E2210 DELD037 1680x1050 473x296mm 22.0-inch                      | 1         | 2%      |
| CS_ LCD Monitor CS_5211 1366x768 518x333mm 24.2-inch                  | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 344x194mm 15.5-inch       | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 1         | 2%      |
| BOE LCD Monitor BOE097D 1920x1080 344x194mm 15.5-inch                 | 1         | 2%      |
| BOE LCD Monitor BOE094A 1920x1080 344x194mm 15.5-inch                 | 1         | 2%      |
| BOE LCD Monitor BOE06EB 1920x1080 309x173mm 13.9-inch                 | 1         | 2%      |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 1         | 2%      |
| BOE LCD Monitor BOE05F4 1366x768 277x156mm 12.5-inch                  | 1         | 2%      |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch         | 1         | 2%      |
| AU Optronics LCD Monitor AUO3E3D 1920x1080 309x174mm 14.0-inch        | 1         | 2%      |
| AU Optronics LCD Monitor AUO3191 1366x768 344x193mm 15.5-inch         | 1         | 2%      |
| AU Optronics LCD Monitor AUO26ED 1920x1080 344x194mm 15.5-inch        | 1         | 2%      |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch        | 1         | 2%      |
| AU Optronics LCD Monitor AUO20ED 1920x1080 344x194mm 15.5-inch        | 1         | 2%      |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 1         | 2%      |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 1         | 2%      |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 1         | 2%      |
| AU Optronics LCD Monitor AUO068B 1920x1080 309x174mm 14.0-inch        | 1         | 2%      |
| ASUSTek Computer XG258 AUS25B3 1920x1080 540x300mm 24.3-inch          | 1         | 2%      |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                 | 1         | 2%      |
| Acer XZ240Q ACR0946 1920x1080 520x290mm 23.4-inch                     | 1         | 2%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 22        | 44%     |
| 1366x768 (WXGA)    | 17        | 34%     |
| 3840x2160 (4K)     | 2         | 4%      |
| 1680x1050 (WSXGA+) | 2         | 4%      |
| 3840x1600          | 1         | 2%      |
| 2880x1800          | 1         | 2%      |
| 2560x1080          | 1         | 2%      |
| 2160x1440          | 1         | 2%      |
| 1600x900 (HD+)     | 1         | 2%      |
| 1600x1200          | 1         | 2%      |
| 1360x768           | 1         | 2%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 22        | 44%     |
| 13      | 6         | 12%     |
| 14      | 3         | 6%      |
| 12      | 3         | 6%      |
| 74      | 2         | 4%      |
| 24      | 2         | 4%      |
| 22      | 2         | 4%      |
| 17      | 2         | 4%      |
| 54      | 1         | 2%      |
| 37      | 1         | 2%      |
| 34      | 1         | 2%      |
| 31      | 1         | 2%      |
| 27      | 1         | 2%      |
| 23      | 1         | 2%      |
| 18      | 1         | 2%      |
| Unknown | 1         | 2%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 28        | 56%     |
| 201-300     | 5         | 10%     |
| 501-600     | 3         | 6%      |
| 401-500     | 3         | 6%      |
| 351-400     | 3         | 6%      |
| 601-700     | 2         | 4%      |
| 1501-2000   | 2         | 4%      |
| 801-900     | 1         | 2%      |
| 701-800     | 1         | 2%      |
| 1001-1500   | 1         | 2%      |
| Unknown     | 1         | 2%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 41        | 82%     |
| 16/10   | 6         | 12%     |
| 21/9    | 2         | 4%      |
| Unknown | 1         | 2%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 22        | 44%     |
| 81-90          | 7         | 14%     |
| More than 1000 | 3         | 6%      |
| 61-70          | 3         | 6%      |
| 201-250        | 3         | 6%      |
| 71-80          | 2         | 4%      |
| 351-500        | 2         | 4%      |
| 251-300        | 2         | 4%      |
| 121-130        | 2         | 4%      |
| 301-350        | 1         | 2%      |
| 141-150        | 1         | 2%      |
| 501-1000       | 1         | 2%      |
| Unknown        | 1         | 2%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 20        | 40%     |
| 101-120       | 15        | 30%     |
| 51-100        | 10        | 20%     |
| 1-50          | 2         | 4%      |
| More than 240 | 1         | 2%      |
| 161-240       | 1         | 2%      |
| Unknown       | 1         | 2%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 48        | 88.89%  |
| 0     | 4         | 7.41%   |
| 2     | 2         | 3.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 29        | 31.18%  |
| Intel                           | 26        | 27.96%  |
| Broadcom                        | 7         | 7.53%   |
| Ralink Technology               | 6         | 6.45%   |
| TP-Link                         | 4         | 4.3%    |
| Qualcomm Atheros                | 4         | 4.3%    |
| Samsung Electronics             | 3         | 3.23%   |
| Marvell Technology Group        | 3         | 3.23%   |
| Ralink                          | 2         | 2.15%   |
| ZTE WCDMA Technologies MSM      | 1         | 1.08%   |
| Spreadtrum Communications       | 1         | 1.08%   |
| Qualcomm Atheros Communications | 1         | 1.08%   |
| Qualcomm                        | 1         | 1.08%   |
| NetGear                         | 1         | 1.08%   |
| Linksys                         | 1         | 1.08%   |
| Edimax Technology               | 1         | 1.08%   |
| Belkin Components               | 1         | 1.08%   |
| ASIX Electronics                | 1         | 1.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 14        | 12.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 5         | 4.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 4         | 3.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4         | 3.45%   |
| Intel Wireless 8265 / 8275                                                                    | 4         | 3.45%   |
| TP-Link TL-WN722N v2                                                                          | 3         | 2.59%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 3         | 2.59%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 3         | 2.59%   |
| Ralink MT7601U Wireless Adapter                                                               | 3         | 2.59%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                                   | 2         | 1.72%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 1.72%   |
| Intel Wireless 8260                                                                           | 2         | 1.72%   |
| Intel Ethernet Connection I219-LM                                                             | 2         | 1.72%   |
| Intel Ethernet Connection (2) I219-V                                                          | 2         | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 2         | 1.72%   |
| Intel Centrino Advanced-N 6200                                                                | 2         | 1.72%   |
| ZTE WCDMA MSM ZTE Mobile Broadband Station                                                    | 1         | 0.86%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1         | 0.86%   |
| Spreadtrum Note 6                                                                             | 1         | 0.86%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 1         | 0.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 0.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 0.86%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 0.86%   |
| Realtek Realtek Network controller                                                            | 1         | 0.86%   |
| Realtek 802.11n WLAN Adapter                                                                  | 1         | 0.86%   |
| Realtek 802.11ac NIC                                                                          | 1         | 0.86%   |
| Ralink RT5572 Wireless Adapter                                                                | 1         | 0.86%   |
| Ralink RT5370 Wireless Adapter                                                                | 1         | 0.86%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1         | 0.86%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.86%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.86%   |
| Qualcomm QCNFA765 Wireless Network Adapter                                                    | 1         | 0.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1         | 0.86%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                     | 1         | 0.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 0.86%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 0.86%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 0.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 0.86%   |
| NetGear A6150                                                                                 | 1         | 0.86%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB]                | 1         | 0.86%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                             | 1         | 0.86%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                                       | 1         | 0.86%   |
| Linksys WUSB6300 V2                                                                           | 1         | 0.86%   |
| Intel Wireless 7265                                                                           | 1         | 0.86%   |
| Intel Wireless 7260                                                                           | 1         | 0.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1         | 0.86%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 0.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 1         | 0.86%   |
| Intel I211 Gigabit Network Connection                                                         | 1         | 0.86%   |
| Intel Ethernet Controller I225-V                                                              | 1         | 0.86%   |
| Intel Ethernet Connection I218-LM                                                             | 1         | 0.86%   |
| Intel Ethernet Connection (7) I219-V                                                          | 1         | 0.86%   |
| Intel Ethernet Connection (5) I219-LM                                                         | 1         | 0.86%   |
| Intel Ethernet Connection (4) I219-LM                                                         | 1         | 0.86%   |
| Intel Ethernet Connection (11) I219-LM                                                        | 1         | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 1         | 0.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 1         | 0.86%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 1         | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1         | 0.86%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 20        | 28.99%  |
| Intel                           | 20        | 28.99%  |
| Ralink Technology               | 6         | 8.7%    |
| Broadcom                        | 6         | 8.7%    |
| TP-Link                         | 4         | 5.8%    |
| Qualcomm Atheros                | 4         | 5.8%    |
| Ralink                          | 2         | 2.9%    |
| Qualcomm Atheros Communications | 1         | 1.45%   |
| Qualcomm                        | 1         | 1.45%   |
| NetGear                         | 1         | 1.45%   |
| Marvell Technology Group        | 1         | 1.45%   |
| Linksys                         | 1         | 1.45%   |
| Edimax Technology               | 1         | 1.45%   |
| Belkin Components               | 1         | 1.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 4         | 5.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4         | 5.8%    |
| Intel Wireless 8265 / 8275                                                                    | 4         | 5.8%    |
| TP-Link TL-WN722N v2                                                                          | 3         | 4.35%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 3         | 4.35%   |
| Ralink MT7601U Wireless Adapter                                                               | 3         | 4.35%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 2.9%    |
| Intel Wireless 8260                                                                           | 2         | 2.9%    |
| Intel Comet Lake PCH CNVi WiFi                                                                | 2         | 2.9%    |
| Intel Centrino Advanced-N 6200                                                                | 2         | 2.9%    |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1         | 1.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 1.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 1.45%   |
| Realtek Realtek Network controller                                                            | 1         | 1.45%   |
| Realtek 802.11n WLAN Adapter                                                                  | 1         | 1.45%   |
| Realtek 802.11ac NIC                                                                          | 1         | 1.45%   |
| Ralink RT5572 Wireless Adapter                                                                | 1         | 1.45%   |
| Ralink RT5370 Wireless Adapter                                                                | 1         | 1.45%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1         | 1.45%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.45%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.45%   |
| Qualcomm QCNFA765 Wireless Network Adapter                                                    | 1         | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1         | 1.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 1.45%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 1.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 1.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 1.45%   |
| NetGear A6150                                                                                 | 1         | 1.45%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                             | 1         | 1.45%   |
| Linksys WUSB6300 V2                                                                           | 1         | 1.45%   |
| Intel Wireless 7265                                                                           | 1         | 1.45%   |
| Intel Wireless 7260                                                                           | 1         | 1.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1         | 1.45%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 1.45%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 1         | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 1         | 1.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 1         | 1.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 1         | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1         | 1.45%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 1         | 1.45%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                                | 1         | 1.45%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                                   | 1         | 1.45%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 1         | 1.45%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                                            | 1         | 1.45%   |
| Broadcom BCM4331 802.11a/b/g/n                                                                | 1         | 1.45%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 1         | 1.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 1         | 1.45%   |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU]       | 1         | 1.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 22        | 47.83%  |
| Intel                     | 14        | 30.43%  |
| Samsung Electronics       | 3         | 6.52%   |
| Marvell Technology Group  | 2         | 4.35%   |
| Broadcom                  | 2         | 4.35%   |
| Spreadtrum Communications | 1         | 2.17%   |
| Qualcomm Atheros          | 1         | 2.17%   |
| ASIX Electronics          | 1         | 2.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 14        | 30.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 5         | 10.87%  |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 6.52%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 2         | 4.35%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 4.35%   |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 4.35%   |
| Spreadtrum Note 6                                                              | 1         | 2.17%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 2.17%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 2.17%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 2.17%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 2.17%   |
| Intel I211 Gigabit Network Connection                                          | 1         | 2.17%   |
| Intel Ethernet Controller I225-V                                               | 1         | 2.17%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 2.17%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 2.17%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 2.17%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 2.17%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 2.17%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 2.17%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1         | 2.17%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 1         | 2.17%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 1         | 2.17%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 2.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 52        | 54.74%  |
| Ethernet | 42        | 44.21%  |
| Modem    | 1         | 1.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 65.38%  |
| Ethernet | 18        | 34.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 33        | 61.11%  |
| 1     | 17        | 31.48%  |
| 0     | 4         | 7.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 32        | 59.26%  |
| Yes  | 22        | 40.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 41.03%  |
| Realtek Semiconductor           | 8         | 20.51%  |
| Qualcomm Atheros Communications | 2         | 5.13%   |
| Foxconn / Hon Hai               | 2         | 5.13%   |
| Broadcom                        | 2         | 5.13%   |
| Ralink Technology               | 1         | 2.56%   |
| Ralink                          | 1         | 2.56%   |
| Marvell Semiconductor           | 1         | 2.56%   |
| Lite-On Technology              | 1         | 2.56%   |
| IMC Networks                    | 1         | 2.56%   |
| Dell                            | 1         | 2.56%   |
| Cambridge Silicon Radio         | 1         | 2.56%   |
| ASUSTek Computer                | 1         | 2.56%   |
| Apple                           | 1         | 2.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 8         | 20.51%  |
| Realtek Bluetooth Radio                                                             | 6         | 15.38%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 4         | 10.26%  |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 5.13%   |
| Intel AX201 Bluetooth                                                               | 2         | 5.13%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 2.56%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 2.56%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 2.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 2.56%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 2.56%   |
| Lite-On Bluetooth Device                                                            | 1         | 2.56%   |
| Intel Bluetooth Device                                                              | 1         | 2.56%   |
| Intel AX200 Bluetooth                                                               | 1         | 2.56%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 2.56%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 2.56%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 2.56%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 2.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 2.56%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 2.56%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 2.56%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 2.56%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 2.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 39        | 60.94%  |
| AMD                    | 13        | 20.31%  |
| Nvidia                 | 10        | 15.63%  |
| SteelSeries ApS        | 1         | 1.56%   |
| Generalplus Technology | 1         | 1.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 10        | 13.33%  |
| AMD Family 17h/19h HD Audio Controller                                     | 5         | 6.67%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 4%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 4%      |
| Intel 8 Series HD Audio Controller                                         | 3         | 4%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 4%      |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 4%      |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 2.67%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 2.67%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 2.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.67%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 2.67%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 2.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.67%   |
| AMD FCH Azalia Controller                                                  | 2         | 2.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 2.67%   |
| SteelSeries ApS SteelSeries GameDAC                                        | 1         | 1.33%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.33%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.33%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.33%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.33%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.33%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 1.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.33%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.33%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.33%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.33%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.33%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 1.33%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 1.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 1.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.33%   |
| Generalplus Technology USB Audio Device                                    | 1         | 1.33%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 1.33%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.33%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1.33%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 1.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 10        | 18.87%  |
| Samsung Electronics | 10        | 18.87%  |
| Kingston            | 6         | 11.32%  |
| Unknown             | 5         | 9.43%   |
| Micron Technology   | 4         | 7.55%   |
| Unknown (ABCD)      | 3         | 5.66%   |
| Corsair             | 3         | 5.66%   |
| A-DATA Technology   | 3         | 5.66%   |
| G.Skill             | 2         | 3.77%   |
| Crucial             | 2         | 3.77%   |
| Transcend           | 1         | 1.89%   |
| Sesame              | 1         | 1.89%   |
| Patriot             | 1         | 1.89%   |
| Elpida              | 1         | 1.89%   |
| Atermiter           | 1         | 1.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 3.64%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 2         | 3.64%   |
| Unknown RAM Module 8GB SODIMM DDR3 800MT/s                          | 1         | 1.82%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 1.82%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                            | 1         | 1.82%   |
| Unknown RAM Module 2GB SODIMM                                       | 1         | 1.82%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                            | 1         | 1.82%   |
| Unknown RAM 3400 C16 Series 8GB DIMM DDR4 2133MT/s                  | 1         | 1.82%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s        | 1         | 1.82%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1333MT/s                 | 1         | 1.82%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                        | 1         | 1.82%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                        | 1         | 1.82%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.82%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 1.82%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 1.82%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 1.82%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 1.82%   |
| SK hynix RAM HMA851S6AFR6N-TF 4GB SODIMM DDR4 2133MT/s              | 1         | 1.82%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 1         | 1.82%   |
| SK hynix RAM H5AN4G6NAFR-UHC 2GB SODIMM DDR4 2400MT/s               | 1         | 1.82%   |
| Sesame RAM S939A2SGS-ITR 8GB SODIMM DDR3 1600MT/s                   | 1         | 1.82%   |
| Samsung RAM Module 4GB SODIMM LPDDR3 1600MT/s                       | 1         | 1.82%   |
| Samsung RAM Module 4GB SODIMM DDR3 1067MT/s                         | 1         | 1.82%   |
| Samsung RAM M471B5773CHS-CF8 2GB SODIMM DDR3 1067MT/s               | 1         | 1.82%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 1         | 1.82%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.82%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.82%   |
| Samsung RAM M471A1G44BB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 1         | 1.82%   |
| Patriot RAM 2400 C16 Series 16GB DIMM DDR4 2400MT/s                 | 1         | 1.82%   |
| Micron RAM Module 4GB SODIMM LPDDR3 2133MT/s                        | 1         | 1.82%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s               | 1         | 1.82%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s                | 1         | 1.82%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 1         | 1.82%   |
| Kingston RAM Module 8GB SODIMM DDR4 2400MT/s                        | 1         | 1.82%   |
| Kingston RAM KM0VW4-MIH 8GB DIMM DDR4 2400MT/s                      | 1         | 1.82%   |
| Kingston RAM KHX1866C11S3L/8G 8GB SODIMM DDR3 1867MT/s              | 1         | 1.82%   |
| Kingston RAM KF548S38-32 32GB SODIMM 4800MT/s                       | 1         | 1.82%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s               | 1         | 1.82%   |
| Kingston RAM K1CXP8-MIE 16GB SODIMM DDR4 3200MT/s                   | 1         | 1.82%   |
| G.Skill RAM F4-3200C16-16GTZKW 16GB DIMM DDR4 3200MT/s              | 1         | 1.82%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s                | 1         | 1.82%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s               | 1         | 1.82%   |
| Crucial RAM CT8G4S266M.M8FJ 8GB SODIMM DDR4 2667MT/s                | 1         | 1.82%   |
| Crucial RAM CB8GS2666.C8ET 8GB SODIMM DDR4 2667MT/s                 | 1         | 1.82%   |
| Corsair RAM Module 4GB SODIMM DDR3 1067MT/s                         | 1         | 1.82%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s               | 1         | 1.82%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s              | 1         | 1.82%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 1         | 1.82%   |
| Atermiter RAM Module 8GB DIMM DDR4 2133MT/s                         | 1         | 1.82%   |
| A-DATA RAM DDR4 2666 2OZ 8GB DIMM DDR4 3200MT/s                     | 1         | 1.82%   |
| A-DATA RAM DDR4 2400 2OZ 8GB DIMM DDR4 3000MT/s                     | 1         | 1.82%   |
| A-DATA RAM AO1P24HC8T1-BSFS 8GB SODIMM DDR4 2400MT/s                | 1         | 1.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 28        | 59.57%  |
| DDR3    | 11        | 23.4%   |
| LPDDR4  | 3         | 6.38%   |
| LPDDR3  | 2         | 4.26%   |
| DDR5    | 1         | 2.13%   |
| DDR     | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 35        | 74.47%  |
| DIMM   | 12        | 25.53%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 23        | 47.92%  |
| 4096  | 13        | 27.08%  |
| 16384 | 6         | 12.5%   |
| 2048  | 4         | 8.33%   |
| 32768 | 2         | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2400    | 9         | 17.31%  |
| 3200    | 8         | 15.38%  |
| 2667    | 6         | 11.54%  |
| 1600    | 5         | 9.62%   |
| 2133    | 4         | 7.69%   |
| 1334    | 4         | 7.69%   |
| 3266    | 3         | 5.77%   |
| 3600    | 2         | 3.85%   |
| 3000    | 2         | 3.85%   |
| 1333    | 2         | 3.85%   |
| 1067    | 2         | 3.85%   |
| 4800    | 1         | 1.92%   |
| 2933    | 1         | 1.92%   |
| 1867    | 1         | 1.92%   |
| 800     | 1         | 1.92%   |
| Unknown | 1         | 1.92%   |

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

| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 7         | 21.21%  |
| Realtek Semiconductor                  | 5         | 15.15%  |
| Quanta                                 | 3         | 9.09%   |
| Suyin                                  | 2         | 6.06%   |
| Sunplus Innovation Technology          | 2         | 6.06%   |
| Luxvisions Innotech Limited            | 2         | 6.06%   |
| IMC Networks                           | 2         | 6.06%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.06%   |
| Y Media                                | 1         | 3.03%   |
| Ricoh                                  | 1         | 3.03%   |
| Microsoft                              | 1         | 3.03%   |
| Logitech                               | 1         | 3.03%   |
| Jieli Technology                       | 1         | 3.03%   |
| icSpring                               | 1         | 3.03%   |
| Alcor Micro                            | 1         | 3.03%   |
| Acer                                   | 1         | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                   | 3         | 8.82%   |
| Chicony HP HD Camera                                           | 3         | 8.82%   |
| Quanta HD User Facing                                          | 2         | 5.88%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 5.88%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 2         | 5.88%   |
| Y Media USB Camera                                             | 1         | 2.94%   |
| Suyin HP Integrated Webcam                                     | 1         | 2.94%   |
| Suyin 1.3M HD WebCam                                           | 1         | 2.94%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 2.94%   |
| Sunplus HP Truevision HD                                       | 1         | 2.94%   |
| Ricoh Sony Visual Communication Camera                         | 1         | 2.94%   |
| Realtek Integrated Webcam_HD                                   | 1         | 2.94%   |
| Realtek Integrated Webcam                                      | 1         | 2.94%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 2.94%   |
| Microsoft LifeCam Rear                                         | 1         | 2.94%   |
| Microsoft LifeCam Front                                        | 1         | 2.94%   |
| Logitech Webcam C925e                                          | 1         | 2.94%   |
| Jieli USB PHY 2.0                                              | 1         | 2.94%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 1         | 2.94%   |
| IMC Networks USB2.0 HD IR UVC WebCam                           | 1         | 2.94%   |
| icSpring camera                                                | 1         | 2.94%   |
| Chicony USB2.0 HD UVC WebCam                                   | 1         | 2.94%   |
| Chicony Integrated Camera                                      | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam            | 1         | 2.94%   |
| Alcor Micro USB 2.0 Camera                                     | 1         | 2.94%   |
| Acer Integrated RGB Camera                                     | 1         | 2.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 5         | 71.43%  |
| Upek             | 1         | 14.29%  |
| Synaptics        | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 3         | 42.86%  |
| Validity Sensors VFS451 Fingerprint Reader | 1         | 14.29%  |
| Validity Sensors Fingerprint scanner       | 1         | 14.29%  |
| Upek TCS5B Fingerprint sensor              | 1         | 14.29%  |
| Unknown                                    | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./images/line_chart/chipcard_vendor.svg)

| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 4         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)

![Chipcard Model](./images/line_chart/chipcard_model.svg)

| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 2         | 50%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 25%     |
| Broadcom 58200                                 | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 29        | 53.7%   |
| 1     | 21        | 38.89%  |
| 2     | 4         | 7.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 11        | 35.48%  |
| Fingerprint reader    | 7         | 22.58%  |
| Chipcard              | 4         | 12.9%   |
| Graphics card         | 3         | 9.68%   |
| Camera                | 2         | 6.45%   |
| Storage               | 1         | 3.23%   |
| Sound                 | 1         | 3.23%   |
| Multimedia controller | 1         | 3.23%   |
| Bluetooth             | 1         | 3.23%   |

