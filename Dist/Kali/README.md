Kali - Hardware Trends
----------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Kali/Desktop/README.md) and [notebooks](/Dist/Kali/Notebook/README.md).

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

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Kali 2022.2 | 42        | 91.3%   |
| Kali 2022.1 | 3         | 6.52%   |
| Kali 2021.4 | 1         | 2.17%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| Kali | 46        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 5.16.0-kali7-amd64 | 18        | 39.13%  |
| 5.17.0-kali3-amd64 | 17        | 36.96%  |
| 5.18.0-kali2-amd64 | 6         | 13.04%  |
| 5.17.0-kali2-amd64 | 1         | 2.17%   |
| 5.16.0-kali1-amd64 | 1         | 2.17%   |
| 5.15.0-kali3-amd64 | 1         | 2.17%   |
| 5.14.0-kali4-amd64 | 1         | 2.17%   |
| 4.19.113-23222000  | 1         | 2.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.16.0   | 19        | 41.3%   |
| 5.17.0   | 18        | 39.13%  |
| 5.18.0   | 6         | 13.04%  |
| 5.15.0   | 1         | 2.17%   |
| 5.14.0   | 1         | 2.17%   |
| 4.19.113 | 1         | 2.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 19        | 41.3%   |
| 5.17    | 18        | 39.13%  |
| 5.18    | 6         | 13.04%  |
| 5.15    | 1         | 2.17%   |
| 5.14    | 1         | 2.17%   |
| 4.19    | 1         | 2.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 45        | 97.83%  |
| aarch64 | 1         | 2.17%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| XFCE       | 24        | 52.17%  |
| GNOME      | 12        | 26.09%  |
| KDE5       | 3         | 6.52%   |
| X-Cinnamon | 2         | 4.35%   |
| Cinnamon   | 2         | 4.35%   |
| MATE       | 1         | 2.17%   |
| Budgie     | 1         | 2.17%   |
| Unknown    | 1         | 2.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 41        | 89.13%  |
| Wayland | 4         | 8.7%    |
| Tty     | 1         | 2.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 24        | 52.17%  |
| Unknown | 10        | 21.74%  |
| GDM3    | 8         | 17.39%  |
| SDDM    | 4         | 8.7%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 24        | 52.17%  |
| ru_RU   | 4         | 8.7%    |
| de_DE   | 4         | 8.7%    |
| en_GB   | 3         | 6.52%   |
| en_AU   | 3         | 6.52%   |
| sv_SE   | 1         | 2.17%   |
| pt_BR   | 1         | 2.17%   |
| pl_PL   | 1         | 2.17%   |
| nl_NL   | 1         | 2.17%   |
| it_IT   | 1         | 2.17%   |
| en_IE   | 1         | 2.17%   |
| en_CA   | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 34        | 73.91%  |
| BIOS | 12        | 26.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 42        | 91.3%   |
| Overlay | 4         | 8.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 28        | 60.87%  |
| Unknown | 11        | 23.91%  |
| MBR     | 7         | 15.22%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 95.65%  |
| Yes       | 2         | 4.35%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 24        | 52.17%  |
| Yes       | 22        | 47.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 8         | 17.39%  |
| ASUSTek Computer    | 7         | 15.22%  |
| Dell                | 6         | 13.04%  |
| Gigabyte Technology | 5         | 10.87%  |
| MSI                 | 4         | 8.7%    |
| Hewlett-Packard     | 4         | 8.7%    |
| Samsung Electronics | 2         | 4.35%   |
| Acer                | 2         | 4.35%   |
| Toshiba             | 1         | 2.17%   |
| Razer               | 1         | 2.17%   |
| MicroByte           | 1         | 2.17%   |
| Megaware            | 1         | 2.17%   |
| Fujitsu             | 1         | 2.17%   |
| ECS                 | 1         | 2.17%   |
| Apple               | 1         | 2.17%   |
| Unknown             | 1         | 2.17%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop TP412FA_TP412FA   | 2         | 4.35%   |
| Toshiba Satellite L775D                    | 1         | 2.17%   |
| Samsung Galaxy Book 12                     | 1         | 2.17%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 2.17%   |
| Razer Blade 17 (2022) - RZ09-0423          | 1         | 2.17%   |
| MSI MS-7D42                                | 1         | 2.17%   |
| MSI MS-7C02                                | 1         | 2.17%   |
| MSI MS-7A70                                | 1         | 2.17%   |
| MSI GL63 8RD                               | 1         | 2.17%   |
| MicroByte ezbook                           | 1         | 2.17%   |
| Megaware MW-HDC-M                          | 1         | 2.17%   |
| Lenovo Z41-70 80K5                         | 1         | 2.17%   |
| Lenovo ThinkStation P500 30A6S4JY00        | 1         | 2.17%   |
| Lenovo ThinkPad T560 20FJS1KE00            | 1         | 2.17%   |
| Lenovo ThinkPad L480 20LTS1NK27            | 1         | 2.17%   |
| Lenovo ThinkCentre M70q 11DUS3N000         | 1         | 2.17%   |
| Lenovo Legion Y740-17IRHg 81UJ             | 1         | 2.17%   |
| Lenovo Legion Y540-15IRH 81SX              | 1         | 2.17%   |
| Lenovo G500 20236                          | 1         | 2.17%   |
| HP ENVY x360 Convertible 15-dr1xxx         | 1         | 2.17%   |
| HP Compaq Pro 6300 SFF                     | 1         | 2.17%   |
| HP 8460p                                   | 1         | 2.17%   |
| HP 650                                     | 1         | 2.17%   |
| Gigabyte Z690 AORUS ELITE AX DDR4          | 1         | 2.17%   |
| Gigabyte H77M-D3H                          | 1         | 2.17%   |
| Gigabyte GB-BXi3-5010                      | 1         | 2.17%   |
| Gigabyte B550 AORUS ELITE V2               | 1         | 2.17%   |
| Gigabyte B450 GAMING X                     | 1         | 2.17%   |
| Fujitsu CELSIUS H730                       | 1         | 2.17%   |
| ECS 945GZ/CT-M                             | 1         | 2.17%   |
| Dell XPS 9320                              | 1         | 2.17%   |
| Dell XPS 15 9520                           | 1         | 2.17%   |
| Dell XPS 15 9510                           | 1         | 2.17%   |
| Dell Vostro 2520                           | 1         | 2.17%   |
| Dell OptiPlex 3010                         | 1         | 2.17%   |
| Dell Inspiron 3520                         | 1         | 2.17%   |
| ASUS ROG STRIX B550-F GAMING               | 1         | 2.17%   |
| ASUS ROG STRIX B550-E GAMING               | 1         | 2.17%   |
| ASUS ROG STRIX B365-G GAMING               | 1         | 2.17%   |
| ASUS H61-PLUS                              | 1         | 2.17%   |
| ASUS ASUS TUF Gaming F15 FX507ZM_FX507ZM   | 1         | 2.17%   |
| Apple MacPro3,1                            | 1         | 2.17%   |
| Acer Nitro AN515-54                        | 1         | 2.17%   |
| Acer Aspire A314-32                        | 1         | 2.17%   |
| Unknown                                    | 1         | 2.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell XPS              | 3         | 6.52%   |
| ASUS ROG              | 3         | 6.52%   |
| Lenovo ThinkPad       | 2         | 4.35%   |
| Lenovo Legion         | 2         | 4.35%   |
| ASUS VivoBook         | 2         | 4.35%   |
| Toshiba Satellite     | 1         | 2.17%   |
| Samsung Galaxy        | 1         | 2.17%   |
| Samsung 300V3A        | 1         | 2.17%   |
| Razer Blade           | 1         | 2.17%   |
| MSI MS-7D42           | 1         | 2.17%   |
| MSI MS-7C02           | 1         | 2.17%   |
| MSI MS-7A70           | 1         | 2.17%   |
| MSI GL63              | 1         | 2.17%   |
| MicroByte ezbook      | 1         | 2.17%   |
| Megaware MW-HDC-M     | 1         | 2.17%   |
| Lenovo Z41-70         | 1         | 2.17%   |
| Lenovo ThinkStation   | 1         | 2.17%   |
| Lenovo ThinkCentre    | 1         | 2.17%   |
| Lenovo G500           | 1         | 2.17%   |
| HP ENVY               | 1         | 2.17%   |
| HP Compaq             | 1         | 2.17%   |
| HP 8460p              | 1         | 2.17%   |
| HP 650                | 1         | 2.17%   |
| Gigabyte Z690         | 1         | 2.17%   |
| Gigabyte H77M-D3H     | 1         | 2.17%   |
| Gigabyte GB-BXi3-5010 | 1         | 2.17%   |
| Gigabyte B550         | 1         | 2.17%   |
| Gigabyte B450         | 1         | 2.17%   |
| Fujitsu CELSIUS       | 1         | 2.17%   |
| ECS 945GZ             | 1         | 2.17%   |
| Dell Vostro           | 1         | 2.17%   |
| Dell OptiPlex         | 1         | 2.17%   |
| Dell Inspiron         | 1         | 2.17%   |
| ASUS H61-PLUS         | 1         | 2.17%   |
| ASUS ASUS             | 1         | 2.17%   |
| Apple MacPro3         | 1         | 2.17%   |
| Acer Nitro            | 1         | 2.17%   |
| Acer Aspire           | 1         | 2.17%   |
| Unknown               | 1         | 2.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 9         | 19.57%  |
| 2012    | 7         | 15.22%  |
| 2022    | 6         | 13.04%  |
| 2021    | 4         | 8.7%    |
| 2018    | 4         | 8.7%    |
| 2020    | 3         | 6.52%   |
| 2016    | 3         | 6.52%   |
| 2014    | 2         | 4.35%   |
| 2013    | 2         | 4.35%   |
| 2011    | 2         | 4.35%   |
| 2017    | 1         | 2.17%   |
| 2008    | 1         | 2.17%   |
| 2007    | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 22        | 47.83%  |
| Desktop        | 18        | 39.13%  |
| Convertible    | 3         | 6.52%   |
| System on chip | 1         | 2.17%   |
| Tablet         | 1         | 2.17%   |
| Mini pc        | 1         | 2.17%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 46        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 46        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 13        | 28.26%  |
| 16.01-24.0  | 10        | 21.74%  |
| 4.01-8.0    | 8         | 17.39%  |
| 3.01-4.0    | 5         | 10.87%  |
| 8.01-16.0   | 4         | 8.7%    |
| 24.01-32.0  | 2         | 4.35%   |
| 64.01-256.0 | 2         | 4.35%   |
| 2.01-3.0    | 1         | 2.17%   |
| 1.01-2.0    | 1         | 2.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 16        | 34.78%  |
| 1.01-2.0  | 12        | 26.09%  |
| 3.01-4.0  | 8         | 17.39%  |
| 4.01-8.0  | 6         | 13.04%  |
| 0.51-1.0  | 2         | 4.35%   |
| 8.01-16.0 | 1         | 2.17%   |
| 0.01-0.5  | 1         | 2.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 24        | 52.17%  |
| 2      | 15        | 32.61%  |
| 3      | 5         | 10.87%  |
| 6      | 1         | 2.17%   |
| 0      | 1         | 2.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 76.09%  |
| Yes       | 11        | 23.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 93.48%  |
| No        | 3         | 6.52%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 84.78%  |
| No        | 7         | 15.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 63.04%  |
| No        | 17        | 36.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 10        | 21.74%  |
| UK           | 4         | 8.7%    |
| Russia       | 4         | 8.7%    |
| Germany      | 4         | 8.7%    |
| Australia    | 3         | 6.52%   |
| Spain        | 2         | 4.35%   |
| Poland       | 2         | 4.35%   |
| Iran         | 2         | 4.35%   |
| Brazil       | 2         | 4.35%   |
| Sweden       | 1         | 2.17%   |
| Serbia       | 1         | 2.17%   |
| Saudi Arabia | 1         | 2.17%   |
| Pakistan     | 1         | 2.17%   |
| Netherlands  | 1         | 2.17%   |
| Malaysia     | 1         | 2.17%   |
| Italy        | 1         | 2.17%   |
| Indonesia    | 1         | 2.17%   |
| France       | 1         | 2.17%   |
| Ecuador      | 1         | 2.17%   |
| Costa Rica   | 1         | 2.17%   |
| Canada       | 1         | 2.17%   |
| Bulgaria     | 1         | 2.17%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City            | Computers | Percent |
|-----------------|-----------|---------|
| Sao Paulo       | 2         | 4.35%   |
| Modesto         | 2         | 4.35%   |
| Zaragoza        | 1         | 2.17%   |
| Warsaw          | 1         | 2.17%   |
| Walsall         | 1         | 2.17%   |
| Tres Rios       | 1         | 2.17%   |
| Toowoomba       | 1         | 2.17%   |
| Sussex          | 1         | 2.17%   |
| Stockholm       | 1         | 2.17%   |
| Shiraz          | 1         | 2.17%   |
| Seremban        | 1         | 2.17%   |
| Salzgitter      | 1         | 2.17%   |
| Salamanca       | 1         | 2.17%   |
| Ruinerwold      | 1         | 2.17%   |
| Phenix City     | 1         | 2.17%   |
| Peronne         | 1         | 2.17%   |
| Oxford          | 1         | 2.17%   |
| Omsk            | 1         | 2.17%   |
| Novosibirsk     | 1         | 2.17%   |
| Novi Sad        | 1         | 2.17%   |
| New York        | 1         | 2.17%   |
| Munich          | 1         | 2.17%   |
| Maricopa        | 1         | 2.17%   |
| Las Vegas       | 1         | 2.17%   |
| Lahore          | 1         | 2.17%   |
| Krasnoyarsk     | 1         | 2.17%   |
| Khorramabad     | 1         | 2.17%   |
| Khobar          | 1         | 2.17%   |
| Kenzingen       | 1         | 2.17%   |
| Jakarta         | 1         | 2.17%   |
| Harrow          | 1         | 2.17%   |
| Hamilton        | 1         | 2.17%   |
| Fossano         | 1         | 2.17%   |
| Edmonton        | 1         | 2.17%   |
| Derby           | 1         | 2.17%   |
| Cuenca          | 1         | 2.17%   |
| Crosby          | 1         | 2.17%   |
| Burgas          | 1         | 2.17%   |
| Bojszowy        | 1         | 2.17%   |
| Blagoveshchensk | 1         | 2.17%   |
| Beverstedt      | 1         | 2.17%   |
| Ballarat        | 1         | 2.17%   |
| Alpharetta      | 1         | 2.17%   |
| Adelaide        | 1         | 2.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 14        | 15     | 20.59%  |
| WDC                            | 12        | 14     | 17.65%  |
| Seagate                        | 9         | 9      | 13.24%  |
| Kingston                       | 7         | 7      | 10.29%  |
| Crucial                        | 4         | 4      | 5.88%   |
| Toshiba                        | 3         | 4      | 4.41%   |
| Intel                          | 3         | 3      | 4.41%   |
| Verbatim                       | 1         | 1      | 1.47%   |
| Unknown                        | 1         | 1      | 1.47%   |
| Solid State Storage Technology | 1         | 1      | 1.47%   |
| SanDisk                        | 1         | 1      | 1.47%   |
| PNY                            | 1         | 1      | 1.47%   |
| Phison                         | 1         | 1      | 1.47%   |
| Patriot                        | 1         | 1      | 1.47%   |
| Micron Technology              | 1         | 1      | 1.47%   |
| Maxtor                         | 1         | 1      | 1.47%   |
| LITEON                         | 1         | 1      | 1.47%   |
| Hitachi                        | 1         | 1      | 1.47%   |
| Hewlett-Packard                | 1         | 1      | 1.47%   |
| Fujitsu                        | 1         | 1      | 1.47%   |
| Foxline                        | 1         | 1      | 1.47%   |
| Corsair                        | 1         | 1      | 1.47%   |
| China                          | 1         | 1      | 1.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston RBUSNS8180DS3128GJ 128GB SSD  | 3         | 4.17%   |
| WDC WD10EZEX-08WN4A0 1TB               | 2         | 2.78%   |
| Seagate ST1000DM003-1SB102 1TB         | 2         | 2.78%   |
| Samsung SSD 850 EVO 250GB              | 2         | 2.78%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 1         | 1.39%   |
| WDC WD5000AAKX-00ERMA0 500GB           | 1         | 1.39%   |
| WDC WD40EFAX-68JH4N0 4TB               | 1         | 1.39%   |
| WDC WD3200BPVT-00JJ5T0 320GB           | 1         | 1.39%   |
| WDC WD3200AAKS-00L9A0 320GB            | 1         | 1.39%   |
| WDC WD1600AAJS-75WAA0 160GB            | 1         | 1.39%   |
| WDC WD1200BEVS-22UST0 120GB            | 1         | 1.39%   |
| WDC WD10SPZX-24Z10 1TB                 | 1         | 1.39%   |
| WDC WD10JPCX-24UE4T0 1TB               | 1         | 1.39%   |
| WDC WD10EARS-00Y5B1 1TB                | 1         | 1.39%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB   | 1         | 1.39%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB   | 1         | 1.39%   |
| Verbatim Portable SSD 240GB            | 1         | 1.39%   |
| Unknown SD256  249GB                   | 1         | 1.39%   |
| Toshiba MK1665GSX H 160GB              | 1         | 1.39%   |
| Toshiba HDWR160 6TB                    | 1         | 1.39%   |
| Toshiba HDWE150 5TB                    | 1         | 1.39%   |
| Toshiba DT01ABA200 2TB                 | 1         | 1.39%   |
| Solid State Storage NVMe SSD Drive 1TB | 1         | 1.39%   |
| Seagate ST4000DM004-2CV104 4TB         | 1         | 1.39%   |
| Seagate ST3500418AS 500GB              | 1         | 1.39%   |
| Seagate ST3500413AS 500GB              | 1         | 1.39%   |
| Seagate ST2000LM007-1R8174 2TB         | 1         | 1.39%   |
| Seagate ST2000DM008-2FR102 2TB         | 1         | 1.39%   |
| Seagate ST2000DM001-1CH164 2TB         | 1         | 1.39%   |
| Seagate Expansion+ Desk 4TB            | 1         | 1.39%   |
| SanDisk SD9SN8W256G 256GB SSD          | 1         | 1.39%   |
| Samsung SSD 980 PRO 2TB                | 1         | 1.39%   |
| Samsung SSD 980 PRO 1TB                | 1         | 1.39%   |
| Samsung SSD 980 500GB                  | 1         | 1.39%   |
| Samsung SSD 970 EVO Plus 500GB         | 1         | 1.39%   |
| Samsung SSD 960 EVO 250GB              | 1         | 1.39%   |
| Samsung SSD 840 EVO 120GB              | 1         | 1.39%   |
| Samsung PM9A1 NVMe 512GB               | 1         | 1.39%   |
| Samsung PM9A1 NVMe 1024GB              | 1         | 1.39%   |
| Samsung MZVLQ1T0HBLB-00B00 1TB         | 1         | 1.39%   |
| Samsung MZVLB1T0HALR-000L2 1TB         | 1         | 1.39%   |
| Samsung MZ7TE256HMHP-00004 256GB SSD   | 1         | 1.39%   |
| Samsung MZ7LN512HMJP-000L7 512GB SSD   | 1         | 1.39%   |
| Samsung HD502HJ 500GB                  | 1         | 1.39%   |
| PNY CS900 120GB SSD                    | 1         | 1.39%   |
| Phison MSI M390 1TB                    | 1         | 1.39%   |
| Patriot P200 2TB SSD                   | 1         | 1.39%   |
| Micron 3400 NVMe 1024GB                | 1         | 1.39%   |
| Maxtor STM3250310AS 250GB              | 1         | 1.39%   |
| LITEON CV3-8D128 128GB SSD             | 1         | 1.39%   |
| Kingston SV300S37A240G 240GB SSD       | 1         | 1.39%   |
| Kingston SV300S37A120G 120GB SSD       | 1         | 1.39%   |
| Kingston SNVS1000G 1TB                 | 1         | 1.39%   |
| Kingston SA400S37480G 480GB SSD        | 1         | 1.39%   |
| Intel SSDSC2BW240A4 240GB              | 1         | 1.39%   |
| Intel SSDPEKNW512G8H 512GB             | 1         | 1.39%   |
| Intel H10 HBRPEKNX0202A NVMe 512GB     | 1         | 1.39%   |
| Hitachi HTS547575A9E384 752GB          | 1         | 1.39%   |
| HP SSD S650 120GB                      | 1         | 1.39%   |
| Fujitsu MHZ2160BH G1 160GB             | 1         | 1.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 11     | 38.46%  |
| Seagate             | 9         | 9      | 34.62%  |
| Toshiba             | 3         | 4      | 11.54%  |
| Samsung Electronics | 1         | 1      | 3.85%   |
| Maxtor              | 1         | 1      | 3.85%   |
| Hitachi             | 1         | 1      | 3.85%   |
| Fujitsu             | 1         | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 6      | 25%     |
| Samsung Electronics | 5         | 5      | 20.83%  |
| Crucial             | 3         | 3      | 12.5%   |
| WDC                 | 1         | 1      | 4.17%   |
| Verbatim            | 1         | 1      | 4.17%   |
| SanDisk             | 1         | 1      | 4.17%   |
| PNY                 | 1         | 1      | 4.17%   |
| Patriot             | 1         | 1      | 4.17%   |
| LITEON              | 1         | 1      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| Hewlett-Packard     | 1         | 1      | 4.17%   |
| Foxline             | 1         | 1      | 4.17%   |
| China               | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 28     | 37.93%  |
| SSD  | 19        | 24     | 32.76%  |
| NVMe | 16        | 19     | 27.59%  |
| MMC  | 1         | 1      | 1.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 50     | 66.07%  |
| NVMe | 16        | 19     | 28.57%  |
| SAS  | 2         | 2      | 3.57%   |
| MMC  | 1         | 1      | 1.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 25        | 32     | 58.14%  |
| 0.51-1.0   | 9         | 10     | 20.93%  |
| 1.01-2.0   | 5         | 5      | 11.63%  |
| 3.01-4.0   | 3         | 3      | 6.98%   |
| 4.01-10.0  | 1         | 2      | 2.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 16        | 34.78%  |
| 251-500        | 11        | 23.91%  |
| 1001-2000      | 4         | 8.7%    |
| 501-1000       | 4         | 8.7%    |
| 1-20           | 3         | 6.52%   |
| More than 3000 | 2         | 4.35%   |
| 21-50          | 2         | 4.35%   |
| Unknown        | 2         | 4.35%   |
| 2001-3000      | 1         | 2.17%   |
| 51-100         | 1         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 13        | 28.26%  |
| 1-20           | 11        | 23.91%  |
| 101-250        | 7         | 15.22%  |
| 51-100         | 6         | 13.04%  |
| 251-500        | 3         | 6.52%   |
| Unknown        | 2         | 4.35%   |
| More than 3000 | 1         | 2.17%   |
| 2001-3000      | 1         | 2.17%   |
| 1001-2000      | 1         | 2.17%   |
| 501-1000       | 1         | 2.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 1      | 11.11%  |
| WDC WD1200BEVS-22UST0 120GB         | 1         | 1      | 11.11%  |
| Toshiba MK1665GSX H 160GB           | 1         | 1      | 11.11%  |
| Seagate ST3500418AS 500GB           | 1         | 1      | 11.11%  |
| Seagate ST2000LM007-1R8174 2TB      | 1         | 1      | 11.11%  |
| Samsung Electronics SSD 980 PRO 2TB | 1         | 1      | 11.11%  |
| Patriot P200 2TB SSD                | 1         | 1      | 11.11%  |
| Hitachi HTS547575A9E384 752GB       | 1         | 1      | 11.11%  |
| Fujitsu MHZ2160BH G1 160GB          | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 22.22%  |
| Seagate             | 2         | 2      | 22.22%  |
| Toshiba             | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| Patriot             | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 1      | 11.11%  |
| Fujitsu             | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 28.57%  |
| Seagate | 2         | 2      | 28.57%  |
| Toshiba | 1         | 1      | 14.29%  |
| Hitachi | 1         | 1      | 14.29%  |
| Fujitsu | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 7      | 75%     |
| NVMe | 1         | 1      | 12.5%   |
| SSD  | 1         | 1      | 12.5%   |

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
| Works    | 32        | 46     | 60.38%  |
| Detected | 13        | 17     | 24.53%  |
| Malfunc  | 8         | 9      | 15.09%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 35        | 59.32%  |
| Samsung Electronics            | 8         | 13.56%  |
| AMD                            | 7         | 11.86%  |
| SanDisk                        | 2         | 3.39%   |
| Phison Electronics             | 2         | 3.39%   |
| Solid State Storage Technology | 1         | 1.69%   |
| Micron/Crucial Technology      | 1         | 1.69%   |
| Micron Technology              | 1         | 1.69%   |
| Kingston Technology Company    | 1         | 1.69%   |
| ASMedia Technology             | 1         | 1.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 5.97%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 5.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 4.48%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 4.48%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 4.48%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 4.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 2.99%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 2.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 2.99%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 2.99%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 2.99%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 2.99%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 2.99%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 2.99%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 1.49%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 1.49%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.49%   |
| Phison Electronics Non-Volatile memory controller                              | 1         | 1.49%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 1.49%   |
| Micron/Crucial NVMe Controller                                                 | 1         | 1.49%   |
| Micron Non-Volatile memory controller                                          | 1         | 1.49%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.49%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.49%   |
| Intel SSD 660P Series                                                          | 1         | 1.49%   |
| Intel Non-Volatile memory controller                                           | 1         | 1.49%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 1.49%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.49%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.49%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.49%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 1         | 1.49%   |
| Intel C610/X99 series chipset IDE-r Controller                                 | 1         | 1.49%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1         | 1.49%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 1.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.49%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                     | 1         | 1.49%   |
| Intel 631xESB/632xESB IDE Controller                                           | 1         | 1.49%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 1.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.49%   |
| AMD FCH SATA Controller [IDE mode]                                             | 1         | 1.49%   |
| AMD FCH IDE Controller                                                         | 1         | 1.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 36        | 60%     |
| NVMe | 16        | 26.67%  |
| RAID | 4         | 6.67%   |
| IDE  | 4         | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 38        | 82.61%  |
| AMD      | 7         | 15.22%  |
| QUALCOMM | 1         | 2.17%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz          | 3         | 6.52%   |
| Intel Core i3-8145U CPU @ 2.10GHz          | 2         | 4.35%   |
| Intel Core i3-2328M CPU @ 2.20GHz          | 2         | 4.35%   |
| AMD Ryzen 7 5800X 8-Core Processor         | 2         | 4.35%   |
| QUALCOMM AArch64 Processor rev 0 (aarch64) | 1         | 2.17%   |
| Intel Xeon CPU X5482 @ 3.20GHz             | 1         | 2.17%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz        | 1         | 2.17%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 1         | 2.17%   |
| Intel Core i7-7700 CPU @ 3.60GHz           | 1         | 2.17%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 1         | 2.17%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz         | 1         | 2.17%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 1         | 2.17%   |
| Intel Core i5-8350U CPU @ 1.70GHz          | 1         | 2.17%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 1         | 2.17%   |
| Intel Core i5-5200U CPU @ 2.20GHz          | 1         | 2.17%   |
| Intel Core i5-3570 CPU @ 3.40GHz           | 1         | 2.17%   |
| Intel Core i5-3470 CPU @ 3.20GHz           | 1         | 2.17%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 1         | 2.17%   |
| Intel Core i5-2520M CPU @ 2.50GHz          | 1         | 2.17%   |
| Intel Core i5-2400S CPU @ 2.50GHz          | 1         | 2.17%   |
| Intel Core i5-10400T CPU @ 2.00GHz         | 1         | 2.17%   |
| Intel Core i3-9100 CPU @ 3.60GHz           | 1         | 2.17%   |
| Intel Core i3-5010U CPU @ 2.10GHz          | 1         | 2.17%   |
| Intel Core i3-3240 CPU @ 3.40GHz           | 1         | 2.17%   |
| Intel Core i3-3110M CPU @ 2.40GHz          | 1         | 2.17%   |
| Intel Core i3-2350M CPU @ 2.30GHz          | 1         | 2.17%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz       | 1         | 2.17%   |
| Intel Celeron N4020 CPU @ 1.10GHz          | 1         | 2.17%   |
| Intel Celeron CPU N3450 @ 1.10GHz          | 1         | 2.17%   |
| Intel 12th Gen Core i9-12900K              | 1         | 2.17%   |
| Intel 12th Gen Core i7-12800H              | 1         | 2.17%   |
| Intel 12th Gen Core i7-12700H              | 1         | 2.17%   |
| Intel 12th Gen Core i7-1260P               | 1         | 2.17%   |
| Intel 12th Gen Core i5-12500H              | 1         | 2.17%   |
| Intel 12th Gen Core i5-12400F              | 1         | 2.17%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz    | 1         | 2.17%   |
| AMD Ryzen 7 3700X 8-Core Processor         | 1         | 2.17%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 1         | 2.17%   |
| AMD Ryzen 3 1200 Quad-Core Processor       | 1         | 2.17%   |
| AMD C-50 Processor                         | 1         | 2.17%   |
| AMD A6-3400M APU with Radeon HD Graphics   | 1         | 2.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 9         | 19.57%  |
| Intel Core i3    | 9         | 19.57%  |
| Intel Core i7    | 8         | 17.39%  |
| Other            | 7         | 15.22%  |
| AMD Ryzen 7      | 3         | 6.52%   |
| Intel Xeon       | 2         | 4.35%   |
| Intel Celeron    | 2         | 4.35%   |
| QUALCOMM AArch64 | 1         | 2.17%   |
| Intel Core 2 Duo | 1         | 2.17%   |
| AMD Ryzen 5      | 1         | 2.17%   |
| AMD Ryzen 3      | 1         | 2.17%   |
| AMD C-50         | 1         | 2.17%   |
| AMD A6           | 1         | 2.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 15        | 32.61%  |
| 4      | 13        | 28.26%  |
| 6      | 7         | 15.22%  |
| 8      | 5         | 10.87%  |
| 14     | 2         | 4.35%   |
| 12     | 2         | 4.35%   |
| 16     | 1         | 2.17%   |
| 1      | 1         | 2.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 44        | 95.65%  |
| 2      | 2         | 4.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 34        | 73.91%  |
| 1      | 12        | 26.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 46        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 5         | 10.87%  |
| 0x906ea    | 4         | 8.7%    |
| 0x906a3    | 4         | 8.7%    |
| 0x206a7    | 4         | 8.7%    |
| 0x806ec    | 3         | 6.52%   |
| Unknown    | 3         | 6.52%   |
| 0x90672    | 2         | 4.35%   |
| 0x306d4    | 2         | 4.35%   |
| 0xa0653    | 1         | 2.17%   |
| 0x906eb    | 1         | 2.17%   |
| 0x906e9    | 1         | 2.17%   |
| 0x806ea    | 1         | 2.17%   |
| 0x806e9    | 1         | 2.17%   |
| 0x806d1    | 1         | 2.17%   |
| 0x706a8    | 1         | 2.17%   |
| 0x506c9    | 1         | 2.17%   |
| 0x406e3    | 1         | 2.17%   |
| 0x306f2    | 1         | 2.17%   |
| 0x306c3    | 1         | 2.17%   |
| 0x1067a    | 1         | 2.17%   |
| 0x0a50000d | 1         | 2.17%   |
| 0x0a201204 | 1         | 2.17%   |
| 0x0a201016 | 1         | 2.17%   |
| 0x08701021 | 1         | 2.17%   |
| 0x0800820d | 1         | 2.17%   |
| 0x05000028 | 1         | 2.17%   |
| 0x03000027 | 1         | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 11        | 23.91%  |
| Alderlake Hybrid | 6         | 13.04%  |
| SandyBridge      | 5         | 10.87%  |
| IvyBridge        | 5         | 10.87%  |
| Zen 3            | 3         | 6.52%   |
| Penryn           | 2         | 4.35%   |
| Haswell          | 2         | 4.35%   |
| Broadwell        | 2         | 4.35%   |
| Zen+             | 1         | 2.17%   |
| Zen 2            | 1         | 2.17%   |
| Skylake          | 1         | 2.17%   |
| K10 Llano        | 1         | 2.17%   |
| Icelake          | 1         | 2.17%   |
| Goldmont plus    | 1         | 2.17%   |
| Goldmont         | 1         | 2.17%   |
| CometLake        | 1         | 2.17%   |
| Bobcat           | 1         | 2.17%   |
| Unknown          | 1         | 2.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 30        | 53.57%  |
| Nvidia | 20        | 35.71%  |
| AMD    | 6         | 10.71%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 5         | 8.77%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 4         | 7.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 5.26%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 2         | 3.51%   |
| Intel HD Graphics 5500                                                                | 2         | 3.51%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 2         | 3.51%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 1.75%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 1.75%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                 | 1         | 1.75%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                              | 1         | 1.75%   |
| Nvidia GP108M [GeForce MX250]                                                         | 1         | 1.75%   |
| Nvidia GP104 [GeForce GTX 1070]                                                       | 1         | 1.75%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                    | 1         | 1.75%   |
| Nvidia GP104 [GeForce GTX 1060 6GB]                                                   | 1         | 1.75%   |
| Nvidia GM206 [GeForce GTX 950]                                                        | 1         | 1.75%   |
| Nvidia GM204 [GeForce GTX 980]                                                        | 1         | 1.75%   |
| Nvidia GM204 [GeForce GTX 970]                                                        | 1         | 1.75%   |
| Nvidia GM107GL [Quadro K2200]                                                         | 1         | 1.75%   |
| Nvidia GK106GLM [Quadro K2100M]                                                       | 1         | 1.75%   |
| Nvidia GF119M [GeForce GT 520MX]                                                      | 1         | 1.75%   |
| Nvidia GF119 [GeForce GT 610]                                                         | 1         | 1.75%   |
| Nvidia GF108 [GeForce GT 730]                                                         | 1         | 1.75%   |
| Nvidia GF108 [GeForce GT 630]                                                         | 1         | 1.75%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 1         | 1.75%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 1         | 1.75%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                        | 1         | 1.75%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Laptop GPU]                                        | 1         | 1.75%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 1         | 1.75%   |
| Intel UHD Graphics 620                                                                | 1         | 1.75%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 1.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 1         | 1.75%   |
| Intel HD Graphics 620                                                                 | 1         | 1.75%   |
| Intel HD Graphics 500                                                                 | 1         | 1.75%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 1.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 1.75%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                              | 1         | 1.75%   |
| Intel AlderLake-S GT1                                                                 | 1         | 1.75%   |
| Intel 82945G/GZ Integrated Graphics Controller                                        | 1         | 1.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 1         | 1.75%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.75%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                   | 1         | 1.75%   |
| AMD Sumo [Radeon HD 6520G]                                                            | 1         | 1.75%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                  | 1         | 1.75%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 1         | 1.75%   |
| AMD Cezanne                                                                           | 1         | 1.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 19        | 41.3%   |
| 1 x Nvidia     | 10        | 21.74%  |
| Intel + Nvidia | 9         | 19.57%  |
| 1 x AMD        | 4         | 8.7%    |
| Intel + AMD    | 2         | 4.35%   |
| Other          | 1         | 2.17%   |
| 2 x Nvidia     | 1         | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 37        | 80.43%  |
| Proprietary | 7         | 15.22%  |
| Unknown     | 2         | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 54.35%  |
| 1.01-2.0   | 6         | 13.04%  |
| 3.01-4.0   | 5         | 10.87%  |
| 7.01-8.0   | 2         | 4.35%   |
| 5.01-6.0   | 2         | 4.35%   |
| 8.01-16.0  | 2         | 4.35%   |
| 0.51-1.0   | 2         | 4.35%   |
| 0.01-0.5   | 2         | 4.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 11        | 18.97%  |
| Dell                    | 6         | 10.34%  |
| Chimei Innolux          | 6         | 10.34%  |
| LG Display              | 5         | 8.62%   |
| AU Optronics            | 4         | 6.9%    |
| AOC                     | 4         | 6.9%    |
| Hewlett-Packard         | 3         | 5.17%   |
| BOE                     | 3         | 5.17%   |
| Sharp                   | 2         | 3.45%   |
| Goldstar                | 2         | 3.45%   |
| Acer                    | 2         | 3.45%   |
| SAC                     | 1         | 1.72%   |
| QCM                     | 1         | 1.72%   |
| Panasonic               | 1         | 1.72%   |
| OEM                     | 1         | 1.72%   |
| MStar                   | 1         | 1.72%   |
| Iiyama                  | 1         | 1.72%   |
| Gateway                 | 1         | 1.72%   |
| CS_                     | 1         | 1.72%   |
| Chi Mei Optoelectronics | 1         | 1.72%   |
| BenQ                    | 1         | 1.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 3.28%   |
| Sharp LCD Monitor SHP1548 1920x1200 288x180mm 13.4-inch                  | 1         | 1.64%   |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch                  | 1         | 1.64%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch        | 1         | 1.64%   |
| Samsung Electronics SyncMaster SAM0273 1440x900 410x257mm 19.1-inch      | 1         | 1.64%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch     | 1         | 1.64%   |
| Samsung Electronics S24C300 SAM0A28 1920x1080 531x299mm 24.0-inch        | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SMBX2450 3200x1080                       | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch    | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch   | 1         | 1.64%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch      | 1         | 1.64%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 1.64%   |
| SAC LED MONITOR SAC952D 1920x1080 600x340mm 27.2-inch                    | 1         | 1.64%   |
| QCM LCD Monitor QCM0001 2800x1752 270x170mm 12.6-inch                    | 1         | 1.64%   |
| Panasonic TV MEIA0CC 1920x1080 698x392mm 31.5-inch                       | 1         | 1.64%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                          | 1         | 1.64%   |
| MStar PROJECTORS MST0B01 1920x540 708x398mm 32.0-inch                    | 1         | 1.64%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch             | 1         | 1.64%   |
| LG Display LCD Monitor LGD05E0 1920x1080 382x215mm 17.3-inch             | 1         | 1.64%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 1         | 1.64%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch             | 1         | 1.64%   |
| LG Display LCD Monitor LGD040F 1920x1080 345x194mm 15.6-inch             | 1         | 1.64%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                    | 1         | 1.64%   |
| Hewlett-Packard OMEN by HP 25 HPN3425 1920x1080 543x302mm 24.5-inch      | 1         | 1.64%   |
| Hewlett-Packard LCD Monitor LA1951                                       | 1         | 1.64%   |
| Hewlett-Packard LA1956x HWP3021 1280x1024 376x301mm 19.0-inch            | 1         | 1.64%   |
| Hewlett-Packard 2009 HWP2827 1600x900 442x249mm 20.0-inch                | 1         | 1.64%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 1         | 1.64%   |
| Goldstar 2D HD TV GSM59C8 1366x768 509x286mm 23.0-inch                   | 1         | 1.64%   |
| Gateway FHD2400 GWY096C 1920x1200 518x291mm 23.4-inch                    | 1         | 1.64%   |
| Dell U3419W DELA12E 3440x1440 800x335mm 34.1-inch                        | 1         | 1.64%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                    | 1         | 1.64%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                        | 1         | 1.64%   |
| Dell P2212H DELA07F 1920x1080 531x299mm 24.0-inch                        | 1         | 1.64%   |
| Dell E197FP DELA024 1280x1024 380x305mm 19.2-inch                        | 1         | 1.64%   |
| Dell D3218HN DEL200B 1920x1080 698x393mm 31.5-inch                       | 1         | 1.64%   |
| CS_ LCD Monitor CS_5211 1920x1080 519x324mm 24.1-inch                    | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch         | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15A9 1366x768 344x194mm 15.5-inch          | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch         | 1         | 1.64%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 1.64%   |
| BOE LCD Monitor BOE09F9 2560x1440 381x214mm 17.2-inch                    | 1         | 1.64%   |
| BOE LCD Monitor BOE0630 1920x1080 344x194mm 15.5-inch                    | 1         | 1.64%   |
| BOE LCD Monitor BOE05B3 1366x768 344x193mm 15.5-inch                     | 1         | 1.64%   |
| BenQ GW2283 BNQ78E9 1920x1080 476x268mm 21.5-inch                        | 1         | 1.64%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                        | 1         | 1.64%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 1         | 1.64%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch            | 1         | 1.64%   |
| AU Optronics LCD Monitor AUO20ED 1920x1080 344x194mm 15.5-inch           | 1         | 1.64%   |
| AU Optronics LCD Monitor AUO1B3D 1920x1080 309x173mm 13.9-inch           | 1         | 1.64%   |
| AOC U34G2G4R3 AOC3402 3440x1440 797x334mm 34.0-inch                      | 1         | 1.64%   |
| AOC 913FW AOC1913 1440x900 410x260mm 19.1-inch                           | 1         | 1.64%   |
| AOC 716Sw AOC1716 1280x720 340x270mm 17.1-inch                           | 1         | 1.64%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                         | 1         | 1.64%   |
| Acer LCD Monitor AL1717 1280x1024                                        | 1         | 1.64%   |
| Acer EI242QR P ACR0958 1920x1080 530x300mm 24.0-inch                     | 1         | 1.64%   |
| Acer AL1717 ACRAD72 1280x1024 340x270mm 17.1-inch                        | 1         | 1.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 26        | 46.43%  |
| 1366x768 (WXGA)   | 7         | 12.5%   |
| 3840x2160 (4K)    | 4         | 7.14%   |
| 1920x1200 (WUXGA) | 4         | 7.14%   |
| 1600x900 (HD+)    | 3         | 5.36%   |
| 1440x900 (WXGA+)  | 3         | 5.36%   |
| 1920x540          | 2         | 3.57%   |
| 1280x1024 (SXGA)  | 2         | 3.57%   |
| 3440x1440         | 1         | 1.79%   |
| 3200x1080         | 1         | 1.79%   |
| 2800x1752         | 1         | 1.79%   |
| 2560x1440 (QHD)   | 1         | 1.79%   |
| Unknown           | 1         | 1.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 14        | 24.14%  |
| 24      | 8         | 13.79%  |
| 27      | 6         | 10.34%  |
| 13      | 6         | 10.34%  |
| 17      | 4         | 6.9%    |
| 19      | 3         | 5.17%   |
| 31      | 2         | 3.45%   |
| 21      | 2         | 3.45%   |
| 18      | 2         | 3.45%   |
| Unknown | 2         | 3.45%   |
| 84      | 1         | 1.72%   |
| 66      | 1         | 1.72%   |
| 48      | 1         | 1.72%   |
| 34      | 1         | 1.72%   |
| 32      | 1         | 1.72%   |
| 26      | 1         | 1.72%   |
| 23      | 1         | 1.72%   |
| 20      | 1         | 1.72%   |
| 14      | 1         | 1.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 38.18%  |
| 501-600     | 13        | 23.64%  |
| 401-500     | 6         | 10.91%  |
| 601-700     | 4         | 7.27%   |
| 351-400     | 4         | 7.27%   |
| 701-800     | 2         | 3.64%   |
| Unknown     | 2         | 3.64%   |
| 201-300     | 1         | 1.82%   |
| 1501-2000   | 1         | 1.82%   |
| 1001-1500   | 1         | 1.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 37        | 74%     |
| 16/10   | 7         | 14%     |
| 5/4     | 2         | 4%      |
| Unknown | 2         | 4%      |
| 21/9    | 1         | 2%      |
| 0.45    | 1         | 2%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 13        | 22.41%  |
| 201-250        | 9         | 15.52%  |
| 81-90          | 6         | 10.34%  |
| 301-350        | 6         | 10.34%  |
| 151-200        | 5         | 8.62%   |
| 351-500        | 4         | 6.9%    |
| More than 1000 | 3         | 5.17%   |
| 251-300        | 3         | 5.17%   |
| 121-130        | 3         | 5.17%   |
| 141-150        | 2         | 3.45%   |
| Unknown        | 2         | 3.45%   |
| 71-80          | 1         | 1.72%   |
| 111-120        | 1         | 1.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 23        | 42.59%  |
| 121-160       | 16        | 29.63%  |
| 101-120       | 8         | 14.81%  |
| 1-50          | 2         | 3.7%    |
| 161-240       | 2         | 3.7%    |
| Unknown       | 2         | 3.7%    |
| More than 240 | 1         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 31        | 67.39%  |
| 2     | 13        | 28.26%  |
| 4     | 1         | 2.17%   |
| 0     | 1         | 2.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 31        | 36.05%  |
| Intel                           | 26        | 30.23%  |
| Qualcomm Atheros                | 9         | 10.47%  |
| TP-Link                         | 3         | 3.49%   |
| Ralink Technology               | 3         | 3.49%   |
| Google                          | 2         | 2.33%   |
| D-Link System                   | 2         | 2.33%   |
| Broadcom                        | 2         | 2.33%   |
| ASIX Electronics                | 2         | 2.33%   |
| Xiaomi                          | 1         | 1.16%   |
| Samsung Electronics             | 1         | 1.16%   |
| Qualcomm Atheros Communications | 1         | 1.16%   |
| NetGear                         | 1         | 1.16%   |
| D-Link                          | 1         | 1.16%   |
| AboCom Systems                  | 1         | 1.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 16        | 15.84%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 5         | 4.95%   |
| Realtek RTL8125 2.5GbE Controller                                    | 4         | 3.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 4         | 3.96%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 4         | 3.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 3         | 2.97%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 2         | 1.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 2         | 1.98%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 2         | 1.98%   |
| Intel Ethernet Controller I225-V                                     | 2         | 1.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 2         | 1.98%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 2         | 1.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 2         | 1.98%   |
| Google Pixel 6                                                       | 2         | 1.98%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B2) [Ralink RT3072] | 2         | 1.98%   |
| ASIX AX88772B                                                        | 2         | 1.98%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1         | 0.99%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                           | 1         | 0.99%   |
| TP-Link 802.11n NIC                                                  | 1         | 0.99%   |
| TP-Link 802.11ac WLAN Adapter                                        | 1         | 0.99%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 1         | 0.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.99%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter              | 1         | 0.99%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1         | 0.99%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                               | 1         | 0.99%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1         | 0.99%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter              | 1         | 0.99%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 0.99%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1         | 0.99%   |
| Realtek 802.11n WLAN Adapter                                         | 1         | 0.99%   |
| Realtek 802.11ac NIC                                                 | 1         | 0.99%   |
| Ralink RT5572 Wireless Adapter                                       | 1         | 0.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1         | 0.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1         | 0.99%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 1         | 0.99%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 1         | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 0.99%   |
| Qualcomm Atheros AR9271 802.11n                                      | 1         | 0.99%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 1         | 0.99%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 1         | 0.99%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]          | 1         | 0.99%   |
| Intel Wireless 8265 / 8275                                           | 1         | 0.99%   |
| Intel Wireless 8260                                                  | 1         | 0.99%   |
| Intel Wireless 7260                                                  | 1         | 0.99%   |
| Intel Wi-Fi 6 AX200                                                  | 1         | 0.99%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 1         | 0.99%   |
| Intel Ethernet Connection I219-LM                                    | 1         | 0.99%   |
| Intel Ethernet Connection I217-LM                                    | 1         | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                                | 1         | 0.99%   |
| Intel Ethernet Connection (2) I219-V                                 | 1         | 0.99%   |
| Intel Ethernet Connection (2) I218-LM                                | 1         | 0.99%   |
| Intel Ethernet Connection (16) I219-LM                               | 1         | 0.99%   |
| Intel Ethernet Connection (11) I219-V                                | 1         | 0.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 1         | 0.99%   |
| Intel Centrino Wireless-N 130                                        | 1         | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 1         | 0.99%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)               | 1         | 0.99%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                       | 1         | 0.99%   |
| Broadcom BCM4321 802.11a/b/g/n                                       | 1         | 0.99%   |
| Broadcom BCM43162 802.11ac Wireless Network Adapter                  | 1         | 0.99%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 39.22%  |
| Realtek Semiconductor           | 10        | 19.61%  |
| Qualcomm Atheros                | 7         | 13.73%  |
| TP-Link                         | 3         | 5.88%   |
| Ralink Technology               | 3         | 5.88%   |
| D-Link System                   | 2         | 3.92%   |
| Broadcom                        | 2         | 3.92%   |
| Qualcomm Atheros Communications | 1         | 1.96%   |
| NetGear                         | 1         | 1.96%   |
| D-Link                          | 1         | 1.96%   |
| AboCom Systems                  | 1         | 1.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Cannon Lake PCH CNVi WiFi                                      | 4         | 7.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 4         | 7.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 3         | 5.77%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 2         | 3.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 2         | 3.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 2         | 3.85%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 2         | 3.85%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B2) [Ralink RT3072] | 2         | 3.85%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                           | 1         | 1.92%   |
| TP-Link 802.11n NIC                                                  | 1         | 1.92%   |
| TP-Link 802.11ac WLAN Adapter                                        | 1         | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.92%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter              | 1         | 1.92%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1         | 1.92%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                               | 1         | 1.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1         | 1.92%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter              | 1         | 1.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 1.92%   |
| Realtek 802.11n WLAN Adapter                                         | 1         | 1.92%   |
| Realtek 802.11ac NIC                                                 | 1         | 1.92%   |
| Ralink RT5572 Wireless Adapter                                       | 1         | 1.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1         | 1.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1         | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 1.92%   |
| Qualcomm Atheros AR9271 802.11n                                      | 1         | 1.92%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 1         | 1.92%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]          | 1         | 1.92%   |
| Intel Wireless 8265 / 8275                                           | 1         | 1.92%   |
| Intel Wireless 8260                                                  | 1         | 1.92%   |
| Intel Wireless 7260                                                  | 1         | 1.92%   |
| Intel Wi-Fi 6 AX200                                                  | 1         | 1.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 1         | 1.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 1         | 1.92%   |
| Intel Centrino Wireless-N 130                                        | 1         | 1.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 1         | 1.92%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                       | 1         | 1.92%   |
| Broadcom BCM4321 802.11a/b/g/n                                       | 1         | 1.92%   |
| Broadcom BCM43162 802.11ac Wireless Network Adapter                  | 1         | 1.92%   |
| AboCom Systems 802.11n WLAN Adapter                                  | 1         | 1.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 28        | 57.14%  |
| Intel                 | 12        | 24.49%  |
| Qualcomm Atheros      | 3         | 6.12%   |
| Google                | 2         | 4.08%   |
| ASIX Electronics      | 2         | 4.08%   |
| Xiaomi                | 1         | 2.04%   |
| Samsung Electronics   | 1         | 2.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 32.65%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 10.2%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 8.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 4.08%   |
| Intel Ethernet Controller I225-V                                  | 2         | 4.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.08%   |
| Google Pixel 6                                                    | 2         | 4.08%   |
| ASIX AX88772B                                                     | 2         | 4.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.04%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.04%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.04%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.04%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.04%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.04%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.04%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 2.04%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 2.04%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 2.04%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1         | 2.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 43        | 52.44%  |
| WiFi     | 39        | 47.56%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 26        | 60.47%  |
| WiFi     | 17        | 39.53%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 23        | 50%     |
| 1     | 21        | 45.65%  |
| 3     | 1         | 2.17%   |
| 0     | 1         | 2.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 33        | 71.74%  |
| Yes  | 13        | 28.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 56.67%  |
| Qualcomm Atheros Communications | 5         | 16.67%  |
| Realtek Semiconductor           | 2         | 6.67%   |
| Lite-On Technology              | 1         | 3.33%   |
| Hewlett-Packard                 | 1         | 3.33%   |
| Foxconn / Hon Hai               | 1         | 3.33%   |
| Edimax Technology               | 1         | 3.33%   |
| Broadcom                        | 1         | 3.33%   |
| Apple                           | 1         | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                           | 8         | 26.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 6         | 20%     |
| Realtek Bluetooth Radio                          | 2         | 6.67%   |
| Qualcomm Atheros Bluetooth USB Host Controller   | 2         | 6.67%   |
| Intel Bluetooth wireless interface               | 2         | 6.67%   |
| Qualcomm Atheros  Bluetooth Device               | 1         | 3.33%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0           | 1         | 3.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 1         | 3.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 1         | 3.33%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 3.33%   |
| HP Broadcom 2070 Bluetooth Combo                 | 1         | 3.33%   |
| Foxconn / Hon Hai BCM2045A0                      | 1         | 3.33%   |
| Edimax Bluetooth Device                          | 1         | 3.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                | 1         | 3.33%   |
| Apple Bluetooth HCI                              | 1         | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 37        | 55.22%  |
| Nvidia                | 16        | 23.88%  |
| AMD                   | 8         | 11.94%  |
| SteelSeries ApS       | 1         | 1.49%   |
| Realtek Semiconductor | 1         | 1.49%   |
| Razer USA             | 1         | 1.49%   |
| Logitech              | 1         | 1.49%   |
| C-Media Electronics   | 1         | 1.49%   |
| ASUSTek Computer      | 1         | 1.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 6.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 5.41%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 5.41%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 4.05%   |
| Nvidia Audio device                                                        | 3         | 4.05%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 4.05%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 4.05%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 2.7%    |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 2.7%    |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 2.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2.7%    |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.7%    |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 2.7%    |
| Intel 200 Series PCH HD Audio                                              | 2         | 2.7%    |
| SteelSeries ApS SteelSeries Arctis 5                                       | 1         | 1.35%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.35%   |
| Razer USA RZ19-0229 Gaming Microphone                                      | 1         | 1.35%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.35%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.35%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 1.35%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.35%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.35%   |
| Logitech Logitech G PRO X Gaming Headset                                   | 1         | 1.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.35%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.35%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.35%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.35%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.35%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 1.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.35%   |
| Intel 631xESB/632xESB High Definition Audio Controller                     | 1         | 1.35%   |
| C-Media Electronics Audio Adapter                                          | 1         | 1.35%   |
| ASUSTek Computer C-Media Audio                                             | 1         | 1.35%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.35%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 1.35%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1         | 1.35%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.35%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 1.35%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 1.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 1.35%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1         | 1.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 25.53%  |
| SK hynix            | 7         | 14.89%  |
| Ramaxel Technology  | 4         | 8.51%   |
| Micron Technology   | 4         | 8.51%   |
| Kingston            | 4         | 8.51%   |
| Corsair             | 4         | 8.51%   |
| Unknown             | 2         | 4.26%   |
| Nanya Technology    | 2         | 4.26%   |
| G.Skill             | 2         | 4.26%   |
| Crucial             | 2         | 4.26%   |
| Unknown (ABCD)      | 1         | 2.13%   |
| AMD                 | 1         | 2.13%   |
| A-DATA Technology   | 1         | 2.13%   |
| Unknown             | 1         | 2.13%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 2         | 3.85%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 1.92%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 1         | 1.92%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 1.92%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s                | 1         | 1.92%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.92%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 1.92%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.92%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.92%   |
| SK hynix RAM HMCG66MEBSA095N 8GB SODIMM 4800MT/s                    | 1         | 1.92%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 1.92%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.92%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 1.92%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.92%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.92%   |
| Samsung RAM M471B1G73EB0-YK0 8GB Chip DDR3 1600MT/s                 | 1         | 1.92%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.92%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 1         | 1.92%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s              | 1         | 1.92%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 1.92%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16384MB SODIMM 4800MT/s              | 1         | 1.92%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s                  | 1         | 1.92%   |
| Samsung RAM M393A4K40BB0-CPB 32GB DIMM DDR4 2133MT/s                | 1         | 1.92%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s                | 1         | 1.92%   |
| Samsung RAM K3QF3F30BM-AGCF 2GB Row Of Chips LPDDR3 1867MT/s        | 1         | 1.92%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s             | 1         | 1.92%   |
| Ramaxel RAM RMR5030EF68F9W1600 4GB DIMM DDR3 1600MT/s               | 1         | 1.92%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s                | 1         | 1.92%   |
| Nanya RAM NT1GC64BH4B0PS-CG 1GB SODIMM DDR3 1333MT/s                | 1         | 1.92%   |
| Micron RAM Module 4GB SODIMM DDR4 2400MT/s                          | 1         | 1.92%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 1         | 1.92%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 1         | 1.92%   |
| Micron RAM 16ATF4G64HZ-2G6B4 32GB SODIMM DDR4 2667MT/s              | 1         | 1.92%   |
| Kingston RAM Module 8GB DIMM DDR3 1333MT/s                          | 1         | 1.92%   |
| Kingston RAM KVR648-PSB 8GB DIMM DDR3 1600MT/s                      | 1         | 1.92%   |
| Kingston RAM KVR648-MIN 8GB DIMM DDR3 1600MT/s                      | 1         | 1.92%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 3600MT/s               | 1         | 1.92%   |
| Kingston RAM ACR256X64D3S1333C9 2048MB SODIMM DDR3 1334MT/s         | 1         | 1.92%   |
| Kingston RAM 9905458-009.A00LF 2GB DIMM DDR3 1333MT/s               | 1         | 1.92%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                | 1         | 1.92%   |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 3200MT/s                  | 1         | 1.92%   |
| Crucial RAM CT16G4SFD8266.M16FJ 16GB SODIMM DDR4 2667MT/s           | 1         | 1.92%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s               | 1         | 1.92%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s               | 1         | 1.92%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s              | 1         | 1.92%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s              | 1         | 1.92%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s               | 1         | 1.92%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 1         | 1.92%   |
| AMD RAM R538G1601S2S 8GB SODIMM DDR3 1600MT/s                       | 1         | 1.92%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                         | 1         | 1.92%   |
| Unknown                                                             | 1         | 1.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 18        | 50%     |
| DDR3    | 11        | 30.56%  |
| Unknown | 4         | 11.11%  |
| SDRAM   | 1         | 2.78%   |
| LPDDR4  | 1         | 2.78%   |
| LPDDR3  | 1         | 2.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 22        | 59.46%  |
| DIMM         | 12        | 32.43%  |
| Row Of Chips | 2         | 5.41%   |
| Chip         | 1         | 2.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 14        | 34.15%  |
| 4096  | 11        | 26.83%  |
| 16384 | 10        | 24.39%  |
| 2048  | 3         | 7.32%   |
| 32768 | 2         | 4.88%   |
| 1024  | 1         | 2.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 9         | 22.5%   |
| 2667    | 6         | 15%     |
| 3200    | 5         | 12.5%   |
| 4800    | 3         | 7.5%    |
| 3600    | 3         | 7.5%    |
| 3266    | 2         | 5%      |
| 2400    | 2         | 5%      |
| 1334    | 2         | 5%      |
| 1333    | 2         | 5%      |
| 6400    | 1         | 2.5%    |
| 3733    | 1         | 2.5%    |
| 3000    | 1         | 2.5%    |
| 2133    | 1         | 2.5%    |
| 1867    | 1         | 2.5%    |
| Unknown | 1         | 2.5%    |

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

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Chicony Electronics   | 5         | 22.73%  |
| Acer                  | 3         | 13.64%  |
| Quanta                | 2         | 9.09%   |
| Microdia              | 2         | 9.09%   |
| Logitech              | 2         | 9.09%   |
| Apple                 | 2         | 9.09%   |
| Suyin                 | 1         | 4.55%   |
| Sonix Technology      | 1         | 4.55%   |
| Silicon Motion        | 1         | 4.55%   |
| Realtek Semiconductor | 1         | 4.55%   |
| Lite-On Technology    | 1         | 4.55%   |
| IMC Networks          | 1         | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Microdia Laptop_Integrated_Webcam_HD     | 2         | 9.09%   |
| Chicony USB2.0 VGA UVC WebCam            | 2         | 9.09%   |
| Chicony Lenovo EasyCamera                | 2         | 9.09%   |
| Apple iPhone 5/5C/5S/6/SE                | 2         | 9.09%   |
| Acer SunplusIT Integrated Camera         | 2         | 9.09%   |
| Suyin HP TrueVision HD Integrated Webcam | 1         | 4.55%   |
| Sonix USB2.0 HD UVC WebCam               | 1         | 4.55%   |
| Silicon Motion WebCam SCB-1100N          | 1         | 4.55%   |
| Realtek USB2.0 camera                    | 1         | 4.55%   |
| Quanta VGA WebCam                        | 1         | 4.55%   |
| Quanta HD Webcam                         | 1         | 4.55%   |
| Logitech HD Webcam C525                  | 1         | 4.55%   |
| Logitech C920 PRO HD Webcam              | 1         | 4.55%   |
| Lite-On Integrated Camera                | 1         | 4.55%   |
| IMC Networks Integrated RGB Camera       | 1         | 4.55%   |
| Chicony Integrated Camera                | 1         | 4.55%   |
| Acer HD Webcam                           | 1         | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Synaptics        | 2         | 66.67%  |
| Validity Sensors | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor     | 1         | 33.33%  |
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 33.33%  |
| Unknown                                          | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./All/images/line_chart/chipcard_vendor.svg)

| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| O2 Micro    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 26        | 56.52%  |
| 1     | 16        | 34.78%  |
| 2     | 4         | 8.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 9         | 40.91%  |
| Graphics card         | 3         | 13.64%  |
| Fingerprint reader    | 3         | 13.64%  |
| Multimedia controller | 2         | 9.09%   |
| Chipcard              | 2         | 9.09%   |
| Bluetooth             | 2         | 9.09%   |
| Unassigned class      | 1         | 4.55%   |

