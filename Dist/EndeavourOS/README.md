EndeavourOS - Hardware Trends
-----------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/EndeavourOS/Desktop/README.md) and [notebooks](/Dist/EndeavourOS/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: May, 2023.

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

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| EndeavourOS Rolling | 53        | 100%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| EndeavourOS | 53        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 6.3.1-arch1-1          | 13        | 24.53%  |
| 6.3.4-arch1-1          | 6         | 11.32%  |
| 6.2.13-arch1-1         | 6         | 11.32%  |
| 6.3.2-arch1-1          | 3         | 5.66%   |
| 6.3.1-zen1-1-zen       | 3         | 5.66%   |
| 6.3.1-arch2-1          | 3         | 5.66%   |
| 6.1.29-1-lts           | 3         | 5.66%   |
| 6.3.4-zen1-1-zen       | 2         | 3.77%   |
| 6.3.3-zen1-1-zen       | 2         | 3.77%   |
| 6.3.5-arch1-1          | 1         | 1.89%   |
| 6.3.4-273-tkg-pds      | 1         | 1.89%   |
| 6.3.2-zen1-1-zen       | 1         | 1.89%   |
| 6.3.2-273-tkg-bmq      | 1         | 1.89%   |
| 6.3.1-zen2-1-zen       | 1         | 1.89%   |
| 6.3.0-ging             | 1         | 1.89%   |
| 6.2.13-arch1-2-surface | 1         | 1.89%   |
| 6.2.13-arch1-1.1       | 1         | 1.89%   |
| 6.2.12-arch1-1         | 1         | 1.89%   |
| 6.2.11-arch1-1         | 1         | 1.89%   |
| 6.2.10-arch1-1         | 1         | 1.89%   |
| 6.1.11-arch1-1         | 1         | 1.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.3.1   | 20        | 37.74%  |
| 6.3.4   | 9         | 16.98%  |
| 6.2.13  | 8         | 15.09%  |
| 6.3.2   | 5         | 9.43%   |
| 6.1.29  | 3         | 5.66%   |
| 6.3.3   | 2         | 3.77%   |
| 6.3.5   | 1         | 1.89%   |
| 6.3.0   | 1         | 1.89%   |
| 6.2.12  | 1         | 1.89%   |
| 6.2.11  | 1         | 1.89%   |
| 6.2.10  | 1         | 1.89%   |
| 6.1.11  | 1         | 1.89%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.3     | 38        | 71.7%   |
| 6.2     | 11        | 20.75%  |
| 6.1     | 4         | 7.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 53        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 22        | 41.51%  |
| GNOME      | 18        | 33.96%  |
| XFCE       | 5         | 9.43%   |
| X-Cinnamon | 4         | 7.55%   |
| MATE       | 1         | 1.89%   |
| i3         | 1         | 1.89%   |
| bspwm      | 1         | 1.89%   |
| Unknown    | 1         | 1.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 33        | 62.26%  |
| Wayland | 17        | 32.08%  |
| Unknown | 2         | 3.77%   |
| Tty     | 1         | 1.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 19        | 35.85%  |
| SDDM    | 14        | 26.42%  |
| GDM     | 11        | 20.75%  |
| Unknown | 9         | 16.98%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 26        | 49.06%  |
| en_CA | 5         | 9.43%   |
| nl_NL | 4         | 7.55%   |
| en_GB | 4         | 7.55%   |
| pt_BR | 2         | 3.77%   |
| it_IT | 2         | 3.77%   |
| de_DE | 2         | 3.77%   |
| zh_CN | 1         | 1.89%   |
| pl_PL | 1         | 1.89%   |
| nl_BE | 1         | 1.89%   |
| fr_FR | 1         | 1.89%   |
| es_AR | 1         | 1.89%   |
| en_IN | 1         | 1.89%   |
| en_AU | 1         | 1.89%   |
| el_GR | 1         | 1.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 40        | 75.47%  |
| BIOS | 13        | 24.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 38        | 71.7%   |
| Btrfs | 13        | 24.53%  |
| Tmpfs | 2         | 3.77%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 42        | 79.25%  |
| Unknown | 8         | 15.09%  |
| MBR     | 3         | 5.66%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 81.13%  |
| Yes       | 10        | 18.87%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 66.04%  |
| Yes       | 18        | 33.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 19        | 35.85%  |
| MSI                 | 6         | 11.32%  |
| Hewlett-Packard     | 6         | 11.32%  |
| Dell                | 4         | 7.55%   |
| ASUSTek Computer    | 4         | 7.55%   |
| Gigabyte Technology | 3         | 5.66%   |
| Acer                | 3         | 5.66%   |
| Timi                | 1         | 1.89%   |
| Sony                | 1         | 1.89%   |
| Notebook            | 1         | 1.89%   |
| Microsoft           | 1         | 1.89%   |
| HUAWEI              | 1         | 1.89%   |
| Daten Tecnologia    | 1         | 1.89%   |
| ASRock              | 1         | 1.89%   |
| Apple               | 1         | 1.89%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Timi TM1701                               | 1         | 1.89%   |
| Sony SVE1713X1EB                          | 1         | 1.89%   |
| Notebook NS5x_NS7xPU                      | 1         | 1.89%   |
| MSI MS-7D69                               | 1         | 1.89%   |
| MSI MS-7C56                               | 1         | 1.89%   |
| MSI MS-7C02                               | 1         | 1.89%   |
| MSI MS-7B79                               | 1         | 1.89%   |
| MSI MS-7A34                               | 1         | 1.89%   |
| MSI Modern 14 B11MOL                      | 1         | 1.89%   |
| Microsoft Surface Laptop Go               | 1         | 1.89%   |
| Lenovo Yoga AIO 7 27ARH6 F0FN000NMT       | 1         | 1.89%   |
| Lenovo Yoga 710-11IKB 80V6                | 1         | 1.89%   |
| Lenovo ThinkPad Yoga 370 20JJS01S2U       | 1         | 1.89%   |
| Lenovo ThinkPad X230 23252UU              | 1         | 1.89%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S0ET00  | 1         | 1.89%   |
| Lenovo ThinkPad W530 24473F2              | 1         | 1.89%   |
| Lenovo ThinkPad T480 20L5A00PCD           | 1         | 1.89%   |
| Lenovo ThinkPad L13 Yoga 20R6S00800       | 1         | 1.89%   |
| Lenovo ThinkPad 11e Yoga Gen 6 20SES00200 | 1         | 1.89%   |
| Lenovo ThinkCentre M83 10AHS0W300         | 1         | 1.89%   |
| Lenovo ThinkBook 15 G2 ITL 20VE           | 1         | 1.89%   |
| Lenovo Legion Y540-17IRH 81Q4             | 1         | 1.89%   |
| Lenovo Legion 5 Pro 16ACH6 82JS           | 1         | 1.89%   |
| Lenovo Legion 5 15ARH7H 82RD              | 1         | 1.89%   |
| Lenovo Legion 5 15ACH6H 82JU              | 1         | 1.89%   |
| Lenovo IdeaPad 510-15IKB 80SV             | 1         | 1.89%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5          | 1         | 1.89%   |
| Lenovo IdeaPad 3 15ITL6 82H8              | 1         | 1.89%   |
| Lenovo G560 0679                          | 1         | 1.89%   |
| HUAWEI CREM-WXX9                          | 1         | 1.89%   |
| HP Z620 Workstation                       | 1         | 1.89%   |
| HP Z420 Workstation                       | 1         | 1.89%   |
| HP Pavilion All-in-One 27-d0xxx           | 1         | 1.89%   |
| HP Laptop 15s-eq2xxx                      | 1         | 1.89%   |
| HP Laptop 14s-dk1xxx                      | 1         | 1.89%   |
| HP EliteDesk 800 G1 TWR                   | 1         | 1.89%   |
| Gigabyte Z790 UD AX                       | 1         | 1.89%   |
| Gigabyte P55A-UD3                         | 1         | 1.89%   |
| Gigabyte B450 AORUS ELITE                 | 1         | 1.89%   |
| Dell Inspiron 5577                        | 1         | 1.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 7         | 13.21%  |
| Lenovo Legion             | 4         | 7.55%   |
| Dell Inspiron             | 4         | 7.55%   |
| Lenovo IdeaPad            | 3         | 5.66%   |
| Acer Aspire               | 3         | 5.66%   |
| Lenovo Yoga               | 2         | 3.77%   |
| HP Laptop                 | 2         | 3.77%   |
| Timi TM1701               | 1         | 1.89%   |
| Sony SVE1713X1EB          | 1         | 1.89%   |
| Notebook NS5x             | 1         | 1.89%   |
| MSI MS-7D69               | 1         | 1.89%   |
| MSI MS-7C56               | 1         | 1.89%   |
| MSI MS-7C02               | 1         | 1.89%   |
| MSI MS-7B79               | 1         | 1.89%   |
| MSI MS-7A34               | 1         | 1.89%   |
| MSI Modern                | 1         | 1.89%   |
| Microsoft Surface         | 1         | 1.89%   |
| Lenovo ThinkCentre        | 1         | 1.89%   |
| Lenovo ThinkBook          | 1         | 1.89%   |
| Lenovo G560               | 1         | 1.89%   |
| HUAWEI CREM-WXX9          | 1         | 1.89%   |
| HP Z620                   | 1         | 1.89%   |
| HP Z420                   | 1         | 1.89%   |
| HP Pavilion               | 1         | 1.89%   |
| HP EliteDesk              | 1         | 1.89%   |
| Gigabyte Z790             | 1         | 1.89%   |
| Gigabyte P55A-UD3         | 1         | 1.89%   |
| Gigabyte B450             | 1         | 1.89%   |
| Daten Tecnologia DH110MXV | 1         | 1.89%   |
| ASUS X455LF               | 1         | 1.89%   |
| ASUS VivoBook             | 1         | 1.89%   |
| ASUS N56VB                | 1         | 1.89%   |
| ASUS GL553VD              | 1         | 1.89%   |
| ASRock B450M              | 1         | 1.89%   |
| Apple MacBookPro16        | 1         | 1.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 11        | 20.75%  |
| 2020 | 6         | 11.32%  |
| 2019 | 5         | 9.43%   |
| 2017 | 5         | 9.43%   |
| 2012 | 5         | 9.43%   |
| 2022 | 4         | 7.55%   |
| 2018 | 4         | 7.55%   |
| 2016 | 4         | 7.55%   |
| 2013 | 3         | 5.66%   |
| 2015 | 2         | 3.77%   |
| 2023 | 1         | 1.89%   |
| 2014 | 1         | 1.89%   |
| 2010 | 1         | 1.89%   |
| 2009 | 1         | 1.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 32        | 60.38%  |
| Desktop     | 14        | 26.42%  |
| Convertible | 4         | 7.55%   |
| All in one  | 2         | 3.77%   |
| Tablet      | 1         | 1.89%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 51        | 96.23%  |
| Enabled  | 2         | 3.77%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 53        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 16        | 30.19%  |
| 32.01-64.0  | 12        | 22.64%  |
| 8.01-16.0   | 11        | 20.75%  |
| 4.01-8.0    | 10        | 18.87%  |
| 3.01-4.0    | 3         | 5.66%   |
| 64.01-256.0 | 1         | 1.89%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 14        | 26.42%  |
| 2.01-3.0   | 12        | 22.64%  |
| 3.01-4.0   | 11        | 20.75%  |
| 1.01-2.0   | 6         | 11.32%  |
| 8.01-16.0  | 6         | 11.32%  |
| 0.51-1.0   | 3         | 5.66%   |
| 16.01-24.0 | 1         | 1.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 25        | 47.17%  |
| 2      | 17        | 32.08%  |
| 3      | 6         | 11.32%  |
| 4      | 2         | 3.77%   |
| 8      | 1         | 1.89%   |
| 6      | 1         | 1.89%   |
| 5      | 1         | 1.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 81.13%  |
| Yes       | 10        | 18.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 83.02%  |
| No        | 9         | 16.98%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 83.02%  |
| No        | 9         | 16.98%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 79.25%  |
| No        | 11        | 20.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 9         | 16.98%  |
| Canada      | 6         | 11.32%  |
| Netherlands | 5         | 9.43%   |
| Italy       | 4         | 7.55%   |
| Germany     | 4         | 7.55%   |
| Brazil      | 4         | 7.55%   |
| Poland      | 3         | 5.66%   |
| Indonesia   | 2         | 3.77%   |
| Belgium     | 2         | 3.77%   |
| Sweden      | 1         | 1.89%   |
| Spain       | 1         | 1.89%   |
| Serbia      | 1         | 1.89%   |
| Russia      | 1         | 1.89%   |
| Morocco     | 1         | 1.89%   |
| Lithuania   | 1         | 1.89%   |
| India       | 1         | 1.89%   |
| Hungary     | 1         | 1.89%   |
| Greece      | 1         | 1.89%   |
| France      | 1         | 1.89%   |
| Finland     | 1         | 1.89%   |
| Croatia     | 1         | 1.89%   |
| Australia   | 1         | 1.89%   |
| Argentina   | 1         | 1.89%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Montreal             | 5         | 9.43%   |
| Amsterdam            | 2         | 3.77%   |
| Wappingers Falls     | 1         | 1.89%   |
| Vantaa               | 1         | 1.89%   |
| Turin                | 1         | 1.89%   |
| Suwałki             | 1         | 1.89%   |
| Salvador             | 1         | 1.89%   |
| Rydułtowy           | 1         | 1.89%   |
| Rotterdam            | 1         | 1.89%   |
| Rome                 | 1         | 1.89%   |
| Rekem                | 1         | 1.89%   |
| Poznan               | 1         | 1.89%   |
| Portland             | 1         | 1.89%   |
| Piraeus              | 1         | 1.89%   |
| Palermo              | 1         | 1.89%   |
| Osijek               | 1         | 1.89%   |
| Ocoee                | 1         | 1.89%   |
| New Orleans          | 1         | 1.89%   |
| Natal                | 1         | 1.89%   |
| Moscow               | 1         | 1.89%   |
| Los Angeles          | 1         | 1.89%   |
| Koblenz              | 1         | 1.89%   |
| Klaipėda            | 1         | 1.89%   |
| Juazeiro do Norte    | 1         | 1.89%   |
| Jakarta              | 1         | 1.89%   |
| Hyderabad            | 1         | 1.89%   |
| Hamilton             | 1         | 1.89%   |
| Hamburg              | 1         | 1.89%   |
| Gothenburg           | 1         | 1.89%   |
| Glen Carbon          | 1         | 1.89%   |
| Fortaleza            | 1         | 1.89%   |
| Fes                  | 1         | 1.89%   |
| Épinal              | 1         | 1.89%   |
| Edmond               | 1         | 1.89%   |
| Dallas               | 1         | 1.89%   |
| Castello di Cisterna | 1         | 1.89%   |
| Buenos Aires         | 1         | 1.89%   |
| Budapest             | 1         | 1.89%   |
| Brussels             | 1         | 1.89%   |
| Brey                 | 1         | 1.89%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 19        | 26     | 22.09%  |
| WDC                            | 8         | 13     | 9.3%    |
| Seagate                        | 8         | 9      | 9.3%    |
| Sandisk                        | 8         | 8      | 9.3%    |
| Kingston                       | 6         | 8      | 6.98%   |
| Crucial                        | 5         | 6      | 5.81%   |
| SK hynix                       | 3         | 5      | 3.49%   |
| Kingston Technology Company    | 3         | 3      | 3.49%   |
| Toshiba                        | 2         | 2      | 2.33%   |
| Realtek                        | 2         | 2      | 2.33%   |
| Intel                          | 2         | 2      | 2.33%   |
| WALRAM                         | 1         | 1      | 1.16%   |
| Unknown                        | 1         | 1      | 1.16%   |
| Timetec                        | 1         | 1      | 1.16%   |
| Solid State Storage Technology | 1         | 1      | 1.16%   |
| Shenzhen Longsys Electronics   | 1         | 1      | 1.16%   |
| Realtek Semiconductor          | 1         | 1      | 1.16%   |
| Phison                         | 1         | 1      | 1.16%   |
| Mushkin                        | 1         | 1      | 1.16%   |
| Micron/Crucial Technology      | 1         | 1      | 1.16%   |
| Micron Technology              | 1         | 1      | 1.16%   |
| LITEONIT                       | 1         | 1      | 1.16%   |
| LITEON                         | 1         | 1      | 1.16%   |
| KIOXIA                         | 1         | 1      | 1.16%   |
| JMicron Technology             | 1         | 1      | 1.16%   |
| HGST                           | 1         | 1      | 1.16%   |
| Fujitsu                        | 1         | 1      | 1.16%   |
| Fantom                         | 1         | 1      | 1.16%   |
| China                          | 1         | 1      | 1.16%   |
| Apple                          | 1         | 1      | 1.16%   |
| A-DATA Technology              | 1         | 1      | 1.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB  | 4         | 4.12%   |
| Seagate ST1000LM035-1RK172 1TB                       | 3         | 3.09%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 256GB     | 3         | 3.09%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB              | 3         | 3.09%   |
| Kingston SA400S37480G 480GB SSD                      | 3         | 3.09%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                 | 2         | 2.06%   |
| Samsung SSD 980 500GB                                | 2         | 2.06%   |
| Samsung SSD 850 EVO 250GB                            | 2         | 2.06%   |
| Samsung HD103SJ 1TB                                  | 2         | 2.06%   |
| Realtek RTL9210B-CG 1TB                              | 2         | 2.06%   |
| Kingston SKC3000D2048G 2TB                           | 2         | 2.06%   |
| Crucial CT240BX500SSD1 240GB                         | 2         | 2.06%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                     | 1         | 1.03%   |
| WDC WD3200BPVT-22JJ5T0 320GB                         | 1         | 1.03%   |
| WDC WD20EARS-42S0XB0 2TB                             | 1         | 1.03%   |
| WDC WD10SPZX-21Z10T0 1TB                             | 1         | 1.03%   |
| WDC WD10SPZX-08Z10 1TB                               | 1         | 1.03%   |
| WDC WD10JPCX-24UE4T0 1TB                             | 1         | 1.03%   |
| WDC WD10EZEX-60M2NA0 1TB                             | 1         | 1.03%   |
| WDC WD1003FBYZ-010FB0 1TB                            | 1         | 1.03%   |
| WDC WD1003FBYX-01Y7B2 1TB                            | 1         | 1.03%   |
| WDC WD1003FBYX-01Y7B1 1TB                            | 1         | 1.03%   |
| WALRAM 512G                                          | 1         | 1.03%   |
| Unknown MMC Card  128GB                              | 1         | 1.03%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD             | 1         | 1.03%   |
| Toshiba HDWE140 4TB                                  | 1         | 1.03%   |
| Timetec MS05 256GB SSD                               | 1         | 1.03%   |
| Solid State Storage NVMe CL1-8D512 512GB             | 1         | 1.03%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB               | 1         | 1.03%   |
| SK hynix SKHynix_HFS001TEJ9X115N 1TB                 | 1         | 1.03%   |
| SK hynix BC511 256GB                                 | 1         | 1.03%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD 1TB | 1         | 1.03%   |
| Seagate ST500LM021-1KJ152 500GB                      | 1         | 1.03%   |
| Seagate ST2000DM008-2UB102 2TB                       | 1         | 1.03%   |
| Seagate ST2000DM006-2DM164 2TB                       | 1         | 1.03%   |
| Seagate ST16000NM001G-2KK103 16TB                    | 1         | 1.03%   |
| Seagate ST1000DM003-1SB10C 1TB                       | 1         | 1.03%   |
| Seagate Expansion 1TB                                | 1         | 1.03%   |
| Sandisk WD_BLACK SN770 500GB                         | 1         | 1.03%   |
| Sandisk WD_BLACK SN750 SE 500GB                      | 1         | 1.03%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 9      | 38.1%   |
| WDC                 | 7         | 12     | 33.33%  |
| Samsung Electronics | 2         | 2      | 9.52%   |
| Toshiba             | 1         | 1      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |
| Fujitsu             | 1         | 1      | 4.76%   |
| Fantom              | 1         | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 10     | 29.63%  |
| Kingston            | 5         | 5      | 18.52%  |
| Crucial             | 5         | 6      | 18.52%  |
| WDC                 | 1         | 1      | 3.7%    |
| Toshiba             | 1         | 1      | 3.7%    |
| Timetec             | 1         | 1      | 3.7%    |
| SanDisk             | 1         | 1      | 3.7%    |
| Mushkin             | 1         | 1      | 3.7%    |
| LITEONIT            | 1         | 1      | 3.7%    |
| LITEON              | 1         | 1      | 3.7%    |
| Intel               | 1         | 1      | 3.7%    |
| China               | 1         | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 33        | 44     | 43.42%  |
| SSD     | 22        | 30     | 28.95%  |
| HDD     | 18        | 27     | 23.68%  |
| Unknown | 2         | 2      | 2.63%   |
| MMC     | 1         | 1      | 1.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 33        | 42     | 48.53%  |
| SATA | 30        | 55     | 44.12%  |
| SAS  | 4         | 6      | 5.88%   |
| MMC  | 1         | 1      | 1.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 29     | 50%     |
| 0.51-1.0   | 14        | 20     | 33.33%  |
| 1.01-2.0   | 3         | 4      | 7.14%   |
| 3.01-4.0   | 2         | 2      | 4.76%   |
| 10.01-20.0 | 1         | 1      | 2.38%   |
| 4.01-10.0  | 1         | 1      | 2.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1001-2000      | 12        | 22.64%  |
| 501-1000       | 10        | 18.87%  |
| 101-250        | 8         | 15.09%  |
| 251-500        | 7         | 13.21%  |
| More than 3000 | 5         | 9.43%   |
| 2001-3000      | 3         | 5.66%   |
| 21-50          | 2         | 3.77%   |
| 1-20           | 2         | 3.77%   |
| 51-100         | 2         | 3.77%   |
| Unknown        | 2         | 3.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 9         | 16.98%  |
| 251-500        | 8         | 15.09%  |
| 101-250        | 8         | 15.09%  |
| 21-50          | 7         | 13.21%  |
| 1001-2000      | 6         | 11.32%  |
| 51-100         | 6         | 11.32%  |
| 501-1000       | 5         | 9.43%   |
| Unknown        | 2         | 3.77%   |
| More than 3000 | 1         | 1.89%   |
| 0              | 1         | 1.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WD1003FBYZ-010FB0 1TB                                       | 1         | 2      | 12.5%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD                        | 1         | 1      | 12.5%   |
| Seagate ST500LM021-1KJ152 500GB                                 | 1         | 1      | 12.5%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 1         | 1      | 12.5%   |
| SanDisk SD8SNAT128G1002 128GB SSD                               | 1         | 1      | 12.5%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 256GB | 1         | 1      | 12.5%   |
| HGST HTS545050A7E680 500GB                                      | 1         | 1      | 12.5%   |
| Crucial CT500MX500SSD1 500GB                                    | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 25%     |
| WDC                 | 1         | 2      | 12.5%   |
| Toshiba             | 1         | 1      | 12.5%   |
| SanDisk             | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| HGST                | 1         | 1      | 12.5%   |
| Crucial             | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 50%     |
| WDC     | 1         | 2      | 25%     |
| HGST    | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 5      | 50%     |
| SSD  | 3         | 3      | 37.5%   |
| NVMe | 1         | 1      | 12.5%   |

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
| Works    | 43        | 74     | 70.49%  |
| Detected | 11        | 21     | 18.03%  |
| Malfunc  | 7         | 9      | 11.48%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 26        | 33.77%  |
| AMD                            | 14        | 18.18%  |
| Samsung Electronics            | 12        | 15.58%  |
| SanDisk                        | 7         | 9.09%   |
| Kingston Technology Company    | 5         | 6.49%   |
| SK hynix                       | 3         | 3.9%    |
| Solid State Storage Technology | 1         | 1.3%    |
| Shenzhen Longsys Electronics   | 1         | 1.3%    |
| Realtek Semiconductor          | 1         | 1.3%    |
| Phison Electronics             | 1         | 1.3%    |
| Micron/Crucial Technology      | 1         | 1.3%    |
| Micron Technology              | 1         | 1.3%    |
| KIOXIA                         | 1         | 1.3%    |
| ASMedia Technology             | 1         | 1.3%    |
| Apple                          | 1         | 1.3%    |
| ADATA Technology               | 1         | 1.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 12        | 13.33%  |
| Samsung NVMe SSD Controller 980                                                | 6         | 6.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 4.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 4.44%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 4.44%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 3.33%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 3         | 3.33%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 3.33%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 3.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 3.33%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 2.22%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 2.22%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 2.22%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 2         | 2.22%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 2         | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 2.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 2.22%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 1.11%   |
| SK hynix Platinum P41 NVMe Solid State Drive 2TB                               | 1         | 1.11%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 1         | 1.11%   |
| SK hynix BC511                                                                 | 1         | 1.11%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                               | 1         | 1.11%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 1         | 1.11%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 1.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.11%   |
| Samsung Electronics Non-Volatile memory controller                             | 1         | 1.11%   |
| Realtek NVMe Controller                                                        | 1         | 1.11%   |
| Phison E18 PCIe4 NVMe Controller                                               | 1         | 1.11%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 1.11%   |
| Micron NVMe Storage Controller                                                 | 1         | 1.11%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 1.11%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                             | 1         | 1.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.11%   |
| Intel Non-Volatile memory controller                                           | 1         | 1.11%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.11%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1         | 1.11%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 1         | 1.11%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                           | 1         | 1.11%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 37        | 46.84%  |
| NVMe | 33        | 41.77%  |
| RAID | 4         | 5.06%   |
| IDE  | 3         | 3.8%    |
| SAS  | 2         | 2.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 36        | 67.92%  |
| AMD    | 17        | 32.08%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics  | 3         | 5.66%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 2         | 3.77%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 3.77%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 3.77%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 2         | 3.77%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 2         | 3.77%   |
| Intel Xeon CPU E5-2643 0 @ 3.30GHz      | 1         | 1.89%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz     | 1         | 1.89%   |
| Intel Core m3-8100Y CPU @ 1.10GHz       | 1         | 1.89%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 1.89%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.89%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.89%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 1         | 1.89%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 1         | 1.89%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 1         | 1.89%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 1         | 1.89%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz        | 1         | 1.89%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 1         | 1.89%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 1         | 1.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 1.89%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 1         | 1.89%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 1         | 1.89%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 1         | 1.89%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 1         | 1.89%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.89%   |
| Intel Core i5-1038NG7 CPU @ 2.00GHz     | 1         | 1.89%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 1         | 1.89%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 1         | 1.89%   |
| Intel Core i5 CPU 750 @ 2.67GHz         | 1         | 1.89%   |
| Intel Core i3-6100 CPU @ 3.70GHz        | 1         | 1.89%   |
| Intel Core i3-3120M CPU @ 2.50GHz       | 1         | 1.89%   |
| Intel Core i3 CPU M 350 @ 2.27GHz       | 1         | 1.89%   |
| Intel 13th Gen Core i5-13600K           | 1         | 1.89%   |
| Intel 12th Gen Core i7-1260P            | 1         | 1.89%   |
| AMD Ryzen 9 7950X 16-Core Processor     | 1         | 1.89%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 1         | 1.89%   |
| AMD Ryzen 7 6800H with Radeon Graphics  | 1         | 1.89%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 1         | 1.89%   |
| AMD Ryzen 7 2700 Eight-Core Processor   | 1         | 1.89%   |
| AMD Ryzen 5 5600H with Radeon Graphics  | 1         | 1.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model         | Computers | Percent |
|---------------|-----------|---------|
| Intel Core i5 | 13        | 24.53%  |
| Intel Core i7 | 9         | 16.98%  |
| Other         | 8         | 15.09%  |
| AMD Ryzen 7   | 8         | 15.09%  |
| AMD Ryzen 5   | 6         | 11.32%  |
| Intel Core i3 | 3         | 5.66%   |
| Intel Xeon    | 2         | 3.77%   |
| AMD Ryzen 9   | 2         | 3.77%   |
| Intel Core m3 | 1         | 1.89%   |
| AMD Athlon    | 1         | 1.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 18        | 33.96%  |
| 2      | 16        | 30.19%  |
| 8      | 9         | 16.98%  |
| 6      | 6         | 11.32%  |
| 12     | 2         | 3.77%   |
| 16     | 1         | 1.89%   |
| 14     | 1         | 1.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 52        | 98.11%  |
| 2      | 1         | 1.89%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 49        | 92.45%  |
| 1      | 4         | 7.55%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 53        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 69.81%  |
| 0x0a50000c | 4         | 7.55%   |
| 0x08600106 | 2         | 3.77%   |
| 0x0800820d | 2         | 3.77%   |
| 0x40651    | 1         | 1.89%   |
| 0x0a601203 | 1         | 1.89%   |
| 0x0a404102 | 1         | 1.89%   |
| 0x0a201016 | 1         | 1.89%   |
| 0x08701030 | 1         | 1.89%   |
| 0x08608104 | 1         | 1.89%   |
| 0x08108109 | 1         | 1.89%   |
| 0x08001138 | 1         | 1.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 11        | 20.75%  |
| Zen 3            | 6         | 11.32%  |
| TigerLake        | 6         | 11.32%  |
| IvyBridge        | 5         | 9.43%   |
| Zen+             | 4         | 7.55%   |
| Haswell          | 4         | 7.55%   |
| Unknown          | 4         | 7.55%   |
| Zen 2            | 3         | 5.66%   |
| Skylake          | 2         | 3.77%   |
| IceLake          | 2         | 3.77%   |
| Zen              | 1         | 1.89%   |
| Westmere         | 1         | 1.89%   |
| SandyBridge      | 1         | 1.89%   |
| Nehalem          | 1         | 1.89%   |
| Broadwell        | 1         | 1.89%   |
| Alderlake Hybrid | 1         | 1.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 31        | 45.59%  |
| Nvidia | 24        | 35.29%  |
| AMD    | 13        | 19.12%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 5.8%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 4.35%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 2.9%    |
| Nvidia GP108M [GeForce MX150]                                               | 2         | 2.9%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 2.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 2.9%    |
| Intel UHD Graphics 620                                                      | 2         | 2.9%    |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                   | 2         | 2.9%    |
| Intel HD Graphics 630                                                       | 2         | 2.9%    |
| Intel HD Graphics 620                                                       | 2         | 2.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 2.9%    |
| AMD Renoir                                                                  | 2         | 2.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 2.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 2.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2         | 2.9%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1         | 1.45%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1         | 1.45%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 1.45%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 1.45%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1         | 1.45%   |
| Nvidia GM108M [GeForce 940MX]                                               | 1         | 1.45%   |
| Nvidia GM108M [GeForce 930M]                                                | 1         | 1.45%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1         | 1.45%   |
| Nvidia GM107 [GeForce 940MX]                                                | 1         | 1.45%   |
| Nvidia GK208BM [GeForce 920M]                                               | 1         | 1.45%   |
| Nvidia GK107M [GeForce GT 740M]                                             | 1         | 1.45%   |
| Nvidia GK107GLM [Quadro K1000M]                                             | 1         | 1.45%   |
| Nvidia GK107GL [Quadro K600]                                                | 1         | 1.45%   |
| Nvidia GA107BM [GeForce RTX 3050 Mobile]                                    | 1         | 1.45%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 1         | 1.45%   |
| Nvidia GA104M [Geforce RTX 3070 Ti Laptop GPU]                              | 1         | 1.45%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1         | 1.45%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1         | 1.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 1.45%   |
| Intel UHD Graphics 615                                                      | 1         | 1.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 1.45%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 1         | 1.45%   |
| Intel Iris Plus Graphics G7                                                 | 1         | 1.45%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 1         | 1.45%   |
| Intel HD Graphics 615                                                       | 1         | 1.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 19        | 35.85%  |
| 1 x Nvidia               | 11        | 20.75%  |
| Intel + Nvidia           | 10        | 18.87%  |
| 1 x AMD                  | 8         | 15.09%  |
| AMD + Nvidia             | 2         | 3.77%   |
| 2 x AMD                  | 1         | 1.89%   |
| Intel + AMD + 1 x Nvidia | 1         | 1.89%   |
| Intel + AMD              | 1         | 1.89%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 35        | 66.04%  |
| Proprietary | 18        | 33.96%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 54.72%  |
| 1.01-2.0   | 6         | 11.32%  |
| 0.01-0.5   | 5         | 9.43%   |
| 7.01-8.0   | 4         | 7.55%   |
| 5.01-6.0   | 4         | 7.55%   |
| 3.01-4.0   | 2         | 3.77%   |
| 0.51-1.0   | 2         | 3.77%   |
| 16.01-24.0 | 1         | 1.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 13        | 20.97%  |
| Chimei Innolux       | 8         | 12.9%   |
| LG Display           | 6         | 9.68%   |
| Samsung Electronics  | 5         | 8.06%   |
| Goldstar             | 5         | 8.06%   |
| AU Optronics         | 5         | 8.06%   |
| Lenovo               | 4         | 6.45%   |
| ASUSTek Computer     | 3         | 4.84%   |
| Acer                 | 3         | 4.84%   |
| Dell                 | 2         | 3.23%   |
| AOC                  | 2         | 3.23%   |
| ViewSonic            | 1         | 1.61%   |
| PANDA                | 1         | 1.61%   |
| Hitachi              | 1         | 1.61%   |
| Hewlett-Packard      | 1         | 1.61%   |
| Apple                | 1         | 1.61%   |
| Ancor Communications | 1         | 1.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 2         | 3.17%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch          | 1         | 1.59%   |
| Samsung Electronics S24R65x SAM1023 1920x1080 527x296mm 23.8-inch      | 1         | 1.59%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch      | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch  | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SAM0B5C 1920x1080 1212x682mm 54.8-inch | 1         | 1.59%   |
| Samsung Electronics LCD Monitor S24R65x 1920x1080                      | 1         | 1.59%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch                | 1         | 1.59%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD05EA 1920x1080 294x165mm 13.3-inch           | 1         | 1.59%   |
| LG Display LCD Monitor LGD0561 1920x1080 294x165mm 13.3-inch           | 1         | 1.59%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch           | 1         | 1.59%   |
| LG Display LCD Monitor LGD04F0 2560x1440 310x174mm 14.0-inch           | 1         | 1.59%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch            | 1         | 1.59%   |
| Lenovo P24q-10 LEN61A5 2560x1440 530x300mm 24.0-inch                   | 1         | 1.59%   |
| Lenovo LEN-Yoga27-A LEN1000 3840x2160 708x399mm 32.0-inch              | 1         | 1.59%   |
| Lenovo LEN LT2934zwA LEN60A5 2560x1080 673x284mm 28.8-inch             | 1         | 1.59%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch               | 1         | 1.59%   |
| Hitachi HDMI HEC0029 1920x1080 580x330mm 26.3-inch                     | 1         | 1.59%   |
| Hewlett-Packard ALL-in-One HPN4033 1920x1080 598x336mm 27.0-inch       | 1         | 1.59%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 1         | 1.59%   |
| Goldstar M2380D GSM57BC 1920x1080 598x336mm 27.0-inch                  | 1         | 1.59%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 1         | 1.59%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch              | 1         | 1.59%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 1         | 1.59%   |
| Dell P2219H DELA113 1920x1080 476x267mm 21.5-inch                      | 1         | 1.59%   |
| Dell E2414H DEL4090 1920x1080 530x300mm 24.0-inch                      | 1         | 1.59%   |
| Dell D3218HN DEL200B 1920x1080 698x393mm 31.5-inch                     | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN175C 1920x1080 381x214mm 17.2-inch       | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch       | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch       | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch       | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch       | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN1137 1920x1080 256x144mm 11.6-inch       | 1         | 1.59%   |
| BOE LCD Monitor BOE0A1C 1920x1080 344x194mm 15.5-inch                  | 1         | 1.59%   |
| BOE LCD Monitor BOE09B6 2560x1600 345x215mm 16.0-inch                  | 1         | 1.59%   |
| BOE LCD Monitor BOE0985 2560x1600 344x215mm 16.0-inch                  | 1         | 1.59%   |
| BOE LCD Monitor BOE092F 2520x1680 338x226mm 16.0-inch                  | 1         | 1.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 32        | 55.17%  |
| 1366x768 (WXGA)  | 7         | 12.07%  |
| 2560x1440 (QHD)  | 6         | 10.34%  |
| 3840x2160 (4K)   | 5         | 8.62%   |
| 2560x1600        | 3         | 5.17%   |
| 2560x1080        | 2         | 3.45%   |
| 2736x1824        | 1         | 1.72%   |
| 2520x1680        | 1         | 1.72%   |
| 1440x900 (WXGA+) | 1         | 1.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 17        | 27.42%  |
| 27      | 9         | 14.52%  |
| 13      | 6         | 9.68%   |
| 14      | 5         | 8.06%   |
| 24      | 3         | 4.84%   |
| 21      | 3         | 4.84%   |
| 16      | 3         | 4.84%   |
| 23      | 2         | 3.23%   |
| 12      | 2         | 3.23%   |
| 11      | 2         | 3.23%   |
| 54      | 1         | 1.61%   |
| 52      | 1         | 1.61%   |
| 34      | 1         | 1.61%   |
| 32      | 1         | 1.61%   |
| 31      | 1         | 1.61%   |
| 28      | 1         | 1.61%   |
| 26      | 1         | 1.61%   |
| 19      | 1         | 1.61%   |
| 17      | 1         | 1.61%   |
| Unknown | 1         | 1.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 28        | 45.9%   |
| 501-600     | 14        | 22.95%  |
| 201-300     | 7         | 11.48%  |
| 401-500     | 4         | 6.56%   |
| 701-800     | 2         | 3.28%   |
| 601-700     | 2         | 3.28%   |
| 1001-1500   | 2         | 3.28%   |
| 351-400     | 1         | 1.64%   |
| Unknown     | 1         | 1.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 44        | 83.02%  |
| 16/10   | 4         | 7.55%   |
| 3/2     | 2         | 3.77%   |
| 21/9    | 2         | 3.77%   |
| Unknown | 1         | 1.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 17        | 27.42%  |
| 301-350        | 10        | 16.13%  |
| 81-90          | 8         | 12.9%   |
| 201-250        | 8         | 12.9%   |
| 71-80          | 4         | 6.45%   |
| 351-500        | 3         | 4.84%   |
| 111-120        | 3         | 4.84%   |
| More than 1000 | 2         | 3.23%   |
| 51-60          | 2         | 3.23%   |
| 61-70          | 1         | 1.61%   |
| 251-300        | 1         | 1.61%   |
| 151-200        | 1         | 1.61%   |
| 121-130        | 1         | 1.61%   |
| Unknown        | 1         | 1.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 22        | 37.29%  |
| 101-120       | 12        | 20.34%  |
| 51-100        | 11        | 18.64%  |
| 161-240       | 10        | 16.95%  |
| 1-50          | 2         | 3.39%   |
| More than 240 | 1         | 1.69%   |
| Unknown       | 1         | 1.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 43        | 81.13%  |
| 2     | 8         | 15.09%  |
| 3     | 2         | 3.77%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 34        | 41.46%  |
| Intel                 | 28        | 34.15%  |
| Qualcomm Atheros      | 6         | 7.32%   |
| MediaTek              | 3         | 3.66%   |
| D-Link                | 3         | 3.66%   |
| Sierra Wireless       | 1         | 1.22%   |
| Microsoft             | 1         | 1.22%   |
| Lenovo                | 1         | 1.22%   |
| DisplayLink           | 1         | 1.22%   |
| Broadcom              | 1         | 1.22%   |
| ASIX Electronics      | 1         | 1.22%   |
| Aquantia              | 1         | 1.22%   |
| Apple                 | 1         | 1.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 25.25%  |
| Intel Wi-Fi 6 AX201                                               | 5         | 5.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 4.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 3.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 3.03%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 3.03%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 2.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 2.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 2.02%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 2.02%   |
| D-Link 802.11ac WLAN Adapter                                      | 2         | 2.02%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 1.01%   |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                    | 1         | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.01%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.01%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1         | 1.01%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 1.01%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 1.01%   |
| Realtek 802.11ac NIC                                              | 1         | 1.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.01%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.01%   |
| Microsoft XBOX ACC                                                | 1         | 1.01%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.01%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]       | 1         | 1.01%   |
| Intel Wireless-AC 9260                                            | 1         | 1.01%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.01%   |
| Intel Wireless 8260                                               | 1         | 1.01%   |
| Intel Wireless 7265                                               | 1         | 1.01%   |
| Intel Wireless 7260                                               | 1         | 1.01%   |
| Intel Wireless 3165                                               | 1         | 1.01%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.01%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.01%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.01%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.01%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.01%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 48%     |
| Realtek Semiconductor | 11        | 22%     |
| Qualcomm Atheros      | 6         | 12%     |
| MediaTek              | 3         | 6%      |
| D-Link                | 3         | 6%      |
| Sierra Wireless       | 1         | 2%      |
| Microsoft             | 1         | 2%      |
| Broadcom              | 1         | 2%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                           | 5         | 9.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 3         | 5.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 3         | 5.88%   |
| Intel Wi-Fi 6 AX200                                           | 3         | 5.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 2         | 3.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 3.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 2         | 3.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 3.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 3.92%   |
| D-Link 802.11ac WLAN Adapter                                  | 2         | 3.92%   |
| Sierra Wireless EM7345 4G LTE                                 | 1         | 1.96%   |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                | 1         | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 1.96%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 1         | 1.96%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter           | 1         | 1.96%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 1         | 1.96%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 1         | 1.96%   |
| Realtek 802.11ac NIC                                          | 1         | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 1         | 1.96%   |
| Microsoft XBOX ACC                                            | 1         | 1.96%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1         | 1.96%   |
| Intel Wireless-AC 9260                                        | 1         | 1.96%   |
| Intel Wireless 8265 / 8275                                    | 1         | 1.96%   |
| Intel Wireless 8260                                           | 1         | 1.96%   |
| Intel Wireless 7265                                           | 1         | 1.96%   |
| Intel Wireless 7260                                           | 1         | 1.96%   |
| Intel Wireless 3165                                           | 1         | 1.96%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 1         | 1.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 1.96%   |
| Intel Centrino Advanced-N 6200                                | 1         | 1.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 1         | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 1         | 1.96%   |
| D-Link DWA-171                                                | 1         | 1.96%   |
| D-Link 802.11ac NIC                                           | 1         | 1.96%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter            | 1         | 1.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 30        | 65.22%  |
| Intel                 | 10        | 21.74%  |
| Qualcomm Atheros      | 1         | 2.17%   |
| Lenovo                | 1         | 2.17%   |
| DisplayLink           | 1         | 2.17%   |
| ASIX Electronics      | 1         | 2.17%   |
| Aquantia              | 1         | 2.17%   |
| Apple                 | 1         | 2.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 25        | 52.08%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 4         | 8.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 2         | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                   | 2         | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 2         | 4.17%   |
| Intel Ethernet Connection I217-LM                                   | 2         | 4.17%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 1         | 2.08%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]         | 1         | 2.08%   |
| Intel Ethernet Connection I218-LM                                   | 1         | 2.08%   |
| Intel Ethernet Connection (4) I219-V                                | 1         | 2.08%   |
| Intel Ethernet Connection (4) I219-LM                               | 1         | 2.08%   |
| Intel Ethernet Connection (10) I219-V                               | 1         | 2.08%   |
| Intel 82574L Gigabit Network Connection                             | 1         | 2.08%   |
| DisplayLink ThinkPad USB 3.0 Ultra Dock                             | 1         | 2.08%   |
| ASIX AX88179 Gigabit Ethernet                                       | 1         | 2.08%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 2.08%   |
| Apple iBridge                                                       | 1         | 2.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 44        | 50%     |
| Ethernet | 44        | 50%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 70.91%  |
| Ethernet | 16        | 29.09%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 30        | 56.6%   |
| 1     | 22        | 41.51%  |
| 3     | 1         | 1.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 45        | 84.91%  |
| Yes  | 8         | 15.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 21        | 48.84%  |
| Realtek Semiconductor   | 7         | 16.28%  |
| Foxconn / Hon Hai       | 4         | 9.3%    |
| Lite-On Technology      | 2         | 4.65%   |
| IMC Networks            | 2         | 4.65%   |
| Cambridge Silicon Radio | 2         | 4.65%   |
| Broadcom                | 2         | 4.65%   |
| ASUSTek Computer        | 2         | 4.65%   |
| MediaTek                | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 5         | 11.63%  |
| Intel Bluetooth wireless interface                  | 5         | 11.63%  |
| Intel AX201 Bluetooth                               | 5         | 11.63%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 9.3%    |
| Intel AX210 Bluetooth                               | 3         | 6.98%   |
| Intel AX200 Bluetooth                               | 3         | 6.98%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 4.65%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 4.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 4.65%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 4.65%   |
| Realtek RTL8821A Bluetooth                          | 1         | 2.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.33%   |
| MediaTek Wireless_Device                            | 1         | 2.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.33%   |
| IMC Networks Bluetooth Device                       | 1         | 2.33%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 2.33%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 2.33%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.33%   |
| ASUS ASUS USB-BT500                                 | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 35        | 38.89%  |
| AMD                        | 21        | 23.33%  |
| Nvidia                     | 16        | 17.78%  |
| Creative Labs              | 2         | 2.22%   |
| C-Media Electronics        | 2         | 2.22%   |
| Texas Instruments          | 1         | 1.11%   |
| Tenx Technology            | 1         | 1.11%   |
| SteelSeries ApS            | 1         | 1.11%   |
| Realtek Semiconductor      | 1         | 1.11%   |
| Micro Star International   | 1         | 1.11%   |
| Logitech                   | 1         | 1.11%   |
| KORG                       | 1         | 1.11%   |
| Kingston Technology        | 1         | 1.11%   |
| Guangzhou FiiO Electronics | 1         | 1.11%   |
| Generalplus Technology     | 1         | 1.11%   |
| Creative Technology        | 1         | 1.11%   |
| Blue Microphones           | 1         | 1.11%   |
| Apple                      | 1         | 1.11%   |
| AKAI                       | 1         | 1.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 11        | 10.68%  |
| Intel Sunrise Point-LP HD Audio                                     | 7         | 6.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 6         | 5.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 4         | 3.88%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 4         | 3.88%   |
| Nvidia GK107 HDMI Audio Controller                                  | 3         | 2.91%   |
| AMD Starship/Matisse HD Audio Controller                            | 3         | 2.91%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 3         | 2.91%   |
| Nvidia GP104 High Definition Audio Controller                       | 2         | 1.94%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]       | 2         | 1.94%   |
| Nvidia GA104 High Definition Audio Controller                       | 2         | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 2         | 1.94%   |
| Intel Haswell-ULT HD Audio Controller                               | 2         | 1.94%   |
| Intel CM238 HD Audio Controller                                     | 2         | 1.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2         | 1.94%   |
| Intel 8 Series HD Audio Controller                                  | 2         | 1.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio            | 2         | 1.94%   |
| C-Media Electronics USB Audio Device                                | 2         | 1.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 2         | 1.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 2         | 1.94%   |
| Texas Instruments PCM2902 Audio Codec                               | 1         | 0.97%   |
| Tenx Technology USB AUDIO                                           | 1         | 0.97%   |
| SteelSeries ApS SteelSeries Arctis 7                                | 1         | 0.97%   |
| Realtek Semiconductor USB SPDIF Adapter                             | 1         | 0.97%   |
| Nvidia TU116 High Definition Audio Controller                       | 1         | 0.97%   |
| Nvidia TU106 High Definition Audio Controller                       | 1         | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                     | 1         | 0.97%   |
| Nvidia GP106 High Definition Audio Controller                       | 1         | 0.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                               | 1         | 0.97%   |
| Nvidia GA106 High Definition Audio Controller                       | 1         | 0.97%   |
| Nvidia GA102 High Definition Audio Controller                       | 1         | 0.97%   |
| Micro Star International USB Audio                                  | 1         | 0.97%   |
| Logitech Blue Microphones                                           | 1         | 0.97%   |
| KORG microKEY2                                                      | 1         | 0.97%   |
| Kingston Technology HyperX 7.1 Audio                                | 1         | 0.97%   |
| Intel Wildcat Point-LP High Definition Audio Controller             | 1         | 0.97%   |
| Intel Smart Sound Technology Audio Controller                       | 1         | 0.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller           | 1         | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                        | 1         | 0.97%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 1         | 0.97%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 26.42%  |
| SK hynix            | 11        | 20.75%  |
| Kingston            | 6         | 11.32%  |
| Micron Technology   | 4         | 7.55%   |
| G.Skill             | 4         | 7.55%   |
| Crucial             | 3         | 5.66%   |
| Corsair             | 2         | 3.77%   |
| Unknown             | 1         | 1.89%   |
| Ramaxel Technology  | 1         | 1.89%   |
| Magnum Tech         | 1         | 1.89%   |
| Kllisre             | 1         | 1.89%   |
| Juhor               | 1         | 1.89%   |
| GOODRAM             | 1         | 1.89%   |
| Elpida              | 1         | 1.89%   |
| Apacer              | 1         | 1.89%   |
| Unknown             | 1         | 1.89%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 3.7%    |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.85%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.85%   |
| SK hynix RAM HMT41GU6AFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 1.85%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.85%   |
| SK hynix RAM HMT325U7EFR8C-PB 2GB DIMM DDR3 1600MT/s             | 1         | 1.85%   |
| SK hynix RAM HMT325U7CFR8C-PB 2GB DIMM DDR3 1600MT/s             | 1         | 1.85%   |
| SK hynix RAM HMAA1GS6CMR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.85%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.85%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s | 1         | 1.85%   |
| SK hynix RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s           | 1         | 1.85%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 1.85%   |
| Samsung RAM M471B5674-H0-YK0--- 4GB Chip DDR3 1600MT/s           | 1         | 1.85%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.85%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.85%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.85%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.85%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 1.85%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s     | 1         | 1.85%   |
| Samsung RAM K4E6E304ED-EGCG 4GB Row Of Chips LPDDR3 1867MT/s     | 1         | 1.85%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s     | 1         | 1.85%   |
| Ramaxel RAM RMSA3270MB86H9F2400 4GB SODIMM DDR4 2400MT/s         | 1         | 1.85%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.85%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s            | 1         | 1.85%   |
| Micron RAM 4ATF11G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.85%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.85%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s              | 1         | 1.85%   |
| Kllisre RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 1.85%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 1         | 1.85%   |
| Kingston RAM KF3200C20S4/32GX 32GB SODIMM DDR4 3200MT/s          | 1         | 1.85%   |
| Kingston RAM HX426S15IB2/16-SP 16GB SODIMM DDR4 2667MT/s         | 1         | 1.85%   |
| Kingston RAM ACR16D3LS1KNG/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 1.85%   |
| Kingston RAM 9905700-118.A00G 8GB SODIMM DDR4 3200MT/s           | 1         | 1.85%   |
| Kingston RAM 9905428-435.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 1.85%   |
| Juhor RAM JHD2666S1916JG 16GB SODIMM DDR4 2667MT/s               | 1         | 1.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 27        | 60%     |
| DDR3    | 11        | 24.44%  |
| LPDDR4  | 2         | 4.44%   |
| LPDDR3  | 2         | 4.44%   |
| DDR5    | 2         | 4.44%   |
| Unknown | 1         | 2.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 28        | 60.87%  |
| DIMM         | 10        | 21.74%  |
| Row Of Chips | 7         | 15.22%  |
| Chip         | 1         | 2.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 22        | 44.9%   |
| 16384 | 12        | 24.49%  |
| 4096  | 11        | 22.45%  |
| 32768 | 2         | 4.08%   |
| 2048  | 2         | 4.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 16        | 34.78%  |
| 1600  | 10        | 21.74%  |
| 2667  | 6         | 13.04%  |
| 4800  | 3         | 6.52%   |
| 3600  | 2         | 4.35%   |
| 2400  | 2         | 4.35%   |
| 1867  | 2         | 4.35%   |
| 4267  | 1         | 2.17%   |
| 3866  | 1         | 2.17%   |
| 2133  | 1         | 2.17%   |
| 1280  | 1         | 2.17%   |
| 1067  | 1         | 2.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)

![Printer Vendor](./All/images/line_chart/printer_vendor.svg)

| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Xerox           | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)

![Printer Model](./All/images/line_chart/printer_model.svg)

| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| Xerox B210                   | 1         | 50%     |
| HP OfficeJet Pro 8020 series | 1         | 50%     |

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
| Chicony Electronics                    | 8         | 18.6%   |
| IMC Networks                           | 6         | 13.95%  |
| Realtek Semiconductor                  | 4         | 9.3%    |
| Bison Electronics                      | 4         | 9.3%    |
| Quanta                                 | 3         | 6.98%   |
| Acer                                   | 3         | 6.98%   |
| Sunplus Innovation Technology          | 2         | 4.65%   |
| MacroSilicon                           | 2         | 4.65%   |
| Logitech                               | 2         | 4.65%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.65%   |
| Apple                                  | 2         | 4.65%   |
| Syntek                                 | 1         | 2.33%   |
| Sonix Technology                       | 1         | 2.33%   |
| ShineTech                              | 1         | 2.33%   |
| Lite-On Technology                     | 1         | 2.33%   |
| GEMBIRD                                | 1         | 2.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                 | 4         | 9.09%   |
| Chicony Integrated Camera                                      | 3         | 6.82%   |
| MacroSilicon usb video                                         | 2         | 4.55%   |
| Logitech C922 Pro Stream Webcam                                | 2         | 4.55%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                | 2         | 4.55%   |
| Syntek Integrated RGB Camera                                   | 1         | 2.27%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 2.27%   |
| Sunplus Asus Webcam                                            | 1         | 2.27%   |
| Sonix USB2.0 HD UVC WebCam                                     | 1         | 2.27%   |
| ShineTech HD Camera                                            | 1         | 2.27%   |
| Realtek USB2.0 HD UVC WebCam                                   | 1         | 2.27%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 2.27%   |
| Realtek HD WebCam                                              | 1         | 2.27%   |
| Realtek EasyCamera                                             | 1         | 2.27%   |
| Quanta VGA WebCam                                              | 1         | 2.27%   |
| Quanta HP 5M Camera                                            | 1         | 2.27%   |
| Quanta HD Camera                                               | 1         | 2.27%   |
| Lite-On Integrated Camera                                      | 1         | 2.27%   |
| IMC Networks SunplusIT Integrated Camera                       | 1         | 2.27%   |
| IMC Networks EasyCamera                                        | 1         | 2.27%   |
| GEMBIRD USB2.0 PC CAMERA                                       | 1         | 2.27%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 1         | 2.27%   |
| Chicony USB2.0 Camera                                          | 1         | 2.27%   |
| Chicony Lenovo EasyCamera                                      | 1         | 2.27%   |
| Chicony HP TrueVision HD Camera                                | 1         | 2.27%   |
| Chicony HD WebCam                                              | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam   | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 2.27%   |
| Bison USB2.0 Camera                                            | 1         | 2.27%   |
| Bison SunplusIT Integrated Camera                              | 1         | 2.27%   |
| Bison Integrated Camera                                        | 1         | 2.27%   |
| Bison Integrated 5M Camera                                     | 1         | 2.27%   |
| Apple FaceTime HD Camera (Built-in)                            | 1         | 2.27%   |
| Acer Integrated Camera                                         | 1         | 2.27%   |
| Acer Integrated 5M Camera                                      | 1         | 2.27%   |
| Acer HD Webcam                                                 | 1         | 2.27%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 40%     |
| Shenzhen Goodix Technology | 2         | 40%     |
| Elan Microelectronics      | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI     | 2         | 40%     |
| Shenzhen Goodix  FingerPrint Device | 1         | 20%     |
| Shenzhen Goodix Fingerprint Reader  | 1         | 20%     |
| Elan ELAN:Fingerprint               | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./All/images/line_chart/chipcard_vendor.svg)

| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 2         | 50%     |
| Upek        | 1         | 25%     |
| Lenovo      | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 25%     |
| Lenovo Integrated Smart Card Reader                        | 1         | 25%     |
| Alcor Micro Watchdata W 1981                               | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                        | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 40        | 75.47%  |
| 1     | 8         | 15.09%  |
| 2     | 4         | 7.55%   |
| 4     | 1         | 1.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 5         | 27.78%  |
| Net/wireless       | 4         | 22.22%  |
| Chipcard           | 4         | 22.22%  |
| Graphics card      | 2         | 11.11%  |
| Camera             | 2         | 11.11%  |
| Dvb card           | 1         | 5.56%   |

