Pop!_OS - Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Pop!_OS/Desktop/README.md) and [notebooks](/Dist/Pop!_OS/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: Apr, 2023.

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
| Pop!_OS 22.04 | 209       | 99.52%  |
| Pop!_OS 21.04 | 1         | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Pop!_OS | 210       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 6.2.6-76060206-generic    | 184       | 87.62%  |
| 6.2.0-76060200-generic    | 7         | 3.33%   |
| 6.0.12-76060006-generic   | 5         | 2.38%   |
| 6.2.11-060211-generic     | 2         | 0.95%   |
| 5.19.0-76051900-generic   | 2         | 0.95%   |
| 5.17.5-76051705-generic   | 2         | 0.95%   |
| 6.2.9-1-liquorix-amd64    | 1         | 0.48%   |
| 6.2.9-060209-generic      | 1         | 0.48%   |
| 6.2.8-060208-generic      | 1         | 0.48%   |
| 6.2.10-060210-generic     | 1         | 0.48%   |
| 6.0.6-76060006-generic    | 1         | 0.48%   |
| 5.18.0-9.1-liquorix-amd64 | 1         | 0.48%   |
| 5.15.5-76051505-generic   | 1         | 0.48%   |
| 5.15.0-1027-raspi         | 1         | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.6   | 184       | 87.62%  |
| 6.2.0   | 7         | 3.33%   |
| 6.0.12  | 5         | 2.38%   |
| 6.2.9   | 2         | 0.95%   |
| 6.2.11  | 2         | 0.95%   |
| 5.19.0  | 2         | 0.95%   |
| 5.17.5  | 2         | 0.95%   |
| 6.2.8   | 1         | 0.48%   |
| 6.2.10  | 1         | 0.48%   |
| 6.0.6   | 1         | 0.48%   |
| 5.18.0  | 1         | 0.48%   |
| 5.15.5  | 1         | 0.48%   |
| 5.15.0  | 1         | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 197       | 93.81%  |
| 6.0     | 6         | 2.86%   |
| 5.19    | 2         | 0.95%   |
| 5.17    | 2         | 0.95%   |
| 5.15    | 2         | 0.95%   |
| 5.18    | 1         | 0.48%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 209       | 99.52%  |
| aarch64 | 1         | 0.48%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 201       | 95.71%  |
| KDE5       | 5         | 2.38%   |
| X-Cinnamon | 2         | 0.95%   |
| MATE       | 1         | 0.48%   |
| Unknown    | 1         | 0.48%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 202       | 96.19%  |
| Wayland | 8         | 3.81%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 159       | 75.71%  |
| GDM3    | 49        | 23.33%  |
| LightDM | 1         | 0.48%   |
| GDM     | 1         | 0.48%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 120       | 57.14%  |
| de_DE   | 14        | 6.67%   |
| en_GB   | 12        | 5.71%   |
| pt_BR   | 9         | 4.29%   |
| it_IT   | 5         | 2.38%   |
| fr_FR   | 5         | 2.38%   |
| es_CL   | 4         | 1.9%    |
| en_AU   | 4         | 1.9%    |
| C       | 4         | 1.9%    |
| pl_PL   | 3         | 1.43%   |
| nb_NO   | 3         | 1.43%   |
| fi_FI   | 3         | 1.43%   |
| en_CA   | 3         | 1.43%   |
| sv_SE   | 2         | 0.95%   |
| pt_PT   | 2         | 0.95%   |
| es_MX   | 2         | 0.95%   |
| en_DK   | 2         | 0.95%   |
| da_DK   | 2         | 0.95%   |
| zh_CN   | 1         | 0.48%   |
| tl_PH   | 1         | 0.48%   |
| ja_JP   | 1         | 0.48%   |
| hu_HU   | 1         | 0.48%   |
| es_ES   | 1         | 0.48%   |
| es_CO   | 1         | 0.48%   |
| en_ZA   | 1         | 0.48%   |
| en_IN   | 1         | 0.48%   |
| de_CH   | 1         | 0.48%   |
| ar_LY   | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 163       | 77.62%  |
| EFI  | 47        | 22.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 201       | 95.71%  |
| Btrfs   | 6         | 2.86%   |
| Overlay | 3         | 1.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 159       | 75.71%  |
| GPT     | 49        | 23.33%  |
| MBR     | 2         | 0.95%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 207       | 98.57%  |
| Yes       | 3         | 1.43%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 189       | 90%     |
| Yes       | 21        | 10%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 37        | 17.62%  |
| Dell                    | 30        | 14.29%  |
| Hewlett-Packard         | 23        | 10.95%  |
| ASUSTek Computer        | 23        | 10.95%  |
| MSI                     | 19        | 9.05%   |
| Gigabyte Technology     | 17        | 8.1%    |
| Apple                   | 9         | 4.29%   |
| ASRock                  | 8         | 3.81%   |
| System76                | 5         | 2.38%   |
| Acer                    | 5         | 2.38%   |
| Samsung Electronics     | 4         | 1.9%    |
| Microsoft               | 3         | 1.43%   |
| Intel                   | 3         | 1.43%   |
| Toshiba                 | 2         | 0.95%   |
| Razer                   | 2         | 0.95%   |
| HUAWEI                  | 2         | 0.95%   |
| BESSTAR Tech            | 2         | 0.95%   |
| Alienware               | 2         | 0.95%   |
| Unknown                 | 2         | 0.95%   |
| Timi                    | 1         | 0.48%   |
| Sony                    | 1         | 0.48%   |
| Raspberry Pi Foundation | 1         | 0.48%   |
| PS                      | 1         | 0.48%   |
| Packard Bell            | 1         | 0.48%   |
| Medion                  | 1         | 0.48%   |
| GPU Company             | 1         | 0.48%   |
| G7-2011                 | 1         | 0.48%   |
| Foxconn                 | 1         | 0.48%   |
| Chuwi                   | 1         | 0.48%   |
| Biostar                 | 1         | 0.48%   |
| American Megatrends     | 1         | 0.48%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Apple MacBookPro12,1            | 3         | 1.43%   |
| MSI MS-7D32                     | 2         | 0.95%   |
| Microsoft Surface Pro 3         | 2         | 0.95%   |
| Lenovo Legion 5 15ARH05H 82B1   | 2         | 0.95%   |
| HUAWEI BOHK-WAX9X               | 2         | 0.95%   |
| Gigabyte B550M DS3H             | 2         | 0.95%   |
| Gigabyte B550 AORUS ELITE AX V2 | 2         | 0.95%   |
| ASUS TUF Gaming B550M-PLUS      | 2         | 0.95%   |
| ASUS ROG CROSSHAIR VIII HERO    | 2         | 0.95%   |
| Apple MacBookPro8,1             | 2         | 0.95%   |
| Unknown                         | 2         | 0.95%   |
| Toshiba Satellite L45-B         | 1         | 0.48%   |
| Toshiba Satellite E45-B         | 1         | 0.48%   |
| Timi TM1707                     | 1         | 0.48%   |
| System76 Thelio                 | 1         | 0.48%   |
| System76 Pangolin               | 1         | 0.48%   |
| System76 Oryx Pro               | 1         | 0.48%   |
| System76 Kudu                   | 1         | 0.48%   |
| System76 Gazelle                | 1         | 0.48%   |
| Sony VPCSC1AFM                  | 1         | 0.48%   |
| Samsung RC530/RC730             | 1         | 0.48%   |
| Samsung DeskTop System          | 1         | 0.48%   |
| Samsung 760XDA                  | 1         | 0.48%   |
| Samsung 300E4Z/300E5Z/300E7Z    | 1         | 0.48%   |
| Razer Blade Stealth             | 1         | 0.48%   |
| Razer Blade                     | 1         | 0.48%   |
| RPi Raspberry Pi                | 1         | 0.48%   |
| PS G706                         | 1         | 0.48%   |
| Packard Bell IPOWER G3610       | 1         | 0.48%   |
| MSI PS42 Modern 8RC             | 1         | 0.48%   |
| MSI MS-7D67                     | 1         | 0.48%   |
| MSI MS-7D53                     | 1         | 0.48%   |
| MSI MS-7D19                     | 1         | 0.48%   |
| MSI MS-7C94                     | 1         | 0.48%   |
| MSI MS-7C35                     | 1         | 0.48%   |
| MSI MS-7C13                     | 1         | 0.48%   |
| MSI MS-7B00                     | 1         | 0.48%   |
| MSI MS-7A34                     | 1         | 0.48%   |
| MSI MS-7996                     | 1         | 0.48%   |
| MSI MS-7817                     | 1         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 11        | 5.24%   |
| Dell Inspiron      | 9         | 4.29%   |
| Lenovo IdeaPad     | 8         | 3.81%   |
| Dell XPS           | 7         | 3.33%   |
| Dell Latitude      | 7         | 3.33%   |
| ASUS ROG           | 7         | 3.33%   |
| Lenovo Legion      | 6         | 2.86%   |
| HP Pavilion        | 4         | 1.9%    |
| Microsoft Surface  | 3         | 1.43%   |
| HP Laptop          | 3         | 1.43%   |
| Dell Precision     | 3         | 1.43%   |
| Dell OptiPlex      | 3         | 1.43%   |
| Apple MacBookPro12 | 3         | 1.43%   |
| Toshiba Satellite  | 2         | 0.95%   |
| Razer Blade        | 2         | 0.95%   |
| MSI MS-7D32        | 2         | 0.95%   |
| Lenovo ThinkBook   | 2         | 0.95%   |
| HUAWEI BOHK-WAX9X  | 2         | 0.95%   |
| HP ZBook           | 2         | 0.95%   |
| HP Spectre         | 2         | 0.95%   |
| HP ENVY            | 2         | 0.95%   |
| HP Compaq          | 2         | 0.95%   |
| Gigabyte B550M     | 2         | 0.95%   |
| Gigabyte B550      | 2         | 0.95%   |
| ASUS ZenBook       | 2         | 0.95%   |
| ASUS TUF           | 2         | 0.95%   |
| ASUS PRIME         | 2         | 0.95%   |
| ASRock X670E       | 2         | 0.95%   |
| Apple MacBookPro8  | 2         | 0.95%   |
| Apple MacBookPro11 | 2         | 0.95%   |
| Alienware 13       | 2         | 0.95%   |
| Acer Swift         | 2         | 0.95%   |
| Acer Aspire        | 2         | 0.95%   |
| Unknown            | 2         | 0.95%   |
| Timi TM1707        | 1         | 0.48%   |
| System76 Thelio    | 1         | 0.48%   |
| System76 Pangolin  | 1         | 0.48%   |
| System76 Oryx      | 1         | 0.48%   |
| System76 Kudu      | 1         | 0.48%   |
| System76 Gazelle   | 1         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 29        | 13.81%  |
| 2020    | 26        | 12.38%  |
| 2018    | 22        | 10.48%  |
| 2021    | 21        | 10%     |
| 2019    | 17        | 8.1%    |
| 2017    | 15        | 7.14%   |
| 2014    | 13        | 6.19%   |
| 2015    | 12        | 5.71%   |
| 2011    | 12        | 5.71%   |
| 2016    | 11        | 5.24%   |
| 2013    | 10        | 4.76%   |
| 2012    | 7         | 3.33%   |
| 2010    | 5         | 2.38%   |
| 2008    | 3         | 1.43%   |
| 2023    | 2         | 0.95%   |
| Unknown | 2         | 0.95%   |
| 2009    | 1         | 0.48%   |
| 2007    | 1         | 0.48%   |
| 2006    | 1         | 0.48%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 116       | 55.24%  |
| Desktop        | 79        | 37.62%  |
| Tablet         | 5         | 2.38%   |
| Convertible    | 5         | 2.38%   |
| Mini pc        | 3         | 1.43%   |
| System on chip | 1         | 0.48%   |
| All in one     | 1         | 0.48%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 210       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 207       | 98.57%  |
| Yes  | 3         | 1.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 47        | 22.38%  |
| 16.01-24.0  | 46        | 21.9%   |
| 8.01-16.0   | 42        | 20%     |
| 32.01-64.0  | 30        | 14.29%  |
| 3.01-4.0    | 23        | 10.95%  |
| 64.01-256.0 | 13        | 6.19%   |
| 24.01-32.0  | 5         | 2.38%   |
| 1.01-2.0    | 3         | 1.43%   |
| 2.01-3.0    | 1         | 0.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 79        | 37.62%  |
| 3.01-4.0   | 47        | 22.38%  |
| 2.01-3.0   | 42        | 20%     |
| 8.01-16.0  | 25        | 11.9%   |
| 1.01-2.0   | 13        | 6.19%   |
| 16.01-24.0 | 2         | 0.95%   |
| 32.01-64.0 | 1         | 0.48%   |
| 0.51-1.0   | 1         | 0.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 122       | 58.1%   |
| 2      | 48        | 22.86%  |
| 3      | 20        | 9.52%   |
| 4      | 9         | 4.29%   |
| 5      | 6         | 2.86%   |
| 26     | 1         | 0.48%   |
| 8      | 1         | 0.48%   |
| 7      | 1         | 0.48%   |
| 6      | 1         | 0.48%   |
| 0      | 1         | 0.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 164       | 78.1%   |
| Yes       | 46        | 21.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 164       | 78.1%   |
| No        | 46        | 21.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 168       | 80%     |
| No        | 42        | 20%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 145       | 69.05%  |
| No        | 65        | 30.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 68        | 32.38%  |
| Germany      | 19        | 9.05%   |
| Canada       | 11        | 5.24%   |
| Brazil       | 11        | 5.24%   |
| UK           | 10        | 4.76%   |
| France       | 8         | 3.81%   |
| Mexico       | 6         | 2.86%   |
| Italy        | 6         | 2.86%   |
| Poland       | 5         | 2.38%   |
| Chile        | 5         | 2.38%   |
| Norway       | 4         | 1.9%    |
| Australia    | 4         | 1.9%    |
| Sweden       | 3         | 1.43%   |
| South Africa | 3         | 1.43%   |
| Netherlands  | 3         | 1.43%   |
| Finland      | 3         | 1.43%   |
| Denmark      | 3         | 1.43%   |
| Bulgaria     | 3         | 1.43%   |
| Spain        | 2         | 0.95%   |
| Serbia       | 2         | 0.95%   |
| Portugal     | 2         | 0.95%   |
| Japan        | 2         | 0.95%   |
| Indonesia    | 2         | 0.95%   |
| India        | 2         | 0.95%   |
| Hungary      | 2         | 0.95%   |
| Hong Kong    | 2         | 0.95%   |
| Greece       | 2         | 0.95%   |
| Austria      | 2         | 0.95%   |
| Vietnam      | 1         | 0.48%   |
| Ukraine      | 1         | 0.48%   |
| Thailand     | 1         | 0.48%   |
| Switzerland  | 1         | 0.48%   |
| Sri Lanka    | 1         | 0.48%   |
| Saudi Arabia | 1         | 0.48%   |
| Philippines  | 1         | 0.48%   |
| Morocco      | 1         | 0.48%   |
| Malaysia     | 1         | 0.48%   |
| Libya        | 1         | 0.48%   |
| Kazakhstan   | 1         | 0.48%   |
| Georgia      | 1         | 0.48%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City               | Computers | Percent |
|--------------------|-----------|---------|
| New York           | 4         | 1.9%    |
| Sydney             | 3         | 1.43%   |
| Helsinki           | 3         | 1.43%   |
| Vienna             | 2         | 0.95%   |
| Temuco             | 2         | 0.95%   |
| Seattle            | 2         | 0.95%   |
| Santiago           | 2         | 0.95%   |
| Poznan             | 2         | 0.95%   |
| Moss               | 2         | 0.95%   |
| Maringá           | 2         | 0.95%   |
| Edmonton           | 2         | 0.95%   |
| Denton             | 2         | 0.95%   |
| Colorado Springs   | 2         | 0.95%   |
| Atlanta            | 2         | 0.95%   |
| Zurich             | 1         | 0.48%   |
| Zapotlan el Grande | 1         | 0.48%   |
| Yokohama           | 1         | 0.48%   |
| Winnipeg           | 1         | 0.48%   |
| Williston          | 1         | 0.48%   |
| Westville          | 1         | 0.48%   |
| West Jordan        | 1         | 0.48%   |
| Wenzenbach         | 1         | 0.48%   |
| Washington         | 1         | 0.48%   |
| Vra                | 1         | 0.48%   |
| Vila do Conde      | 1         | 0.48%   |
| Verona             | 1         | 0.48%   |
| Vechelde           | 1         | 0.48%   |
| Varna              | 1         | 0.48%   |
| Trondheim          | 1         | 0.48%   |
| Trige              | 1         | 0.48%   |
| Tracy              | 1         | 0.48%   |
| Toronto            | 1         | 0.48%   |
| The Hague          | 1         | 0.48%   |
| Tbilisi            | 1         | 0.48%   |
| Tampa              | 1         | 0.48%   |
| Swindon            | 1         | 0.48%   |
| Surat              | 1         | 0.48%   |
| Sturgis            | 1         | 0.48%   |
| State College      | 1         | 0.48%   |
| Stari Grad         | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 62        | 79     | 18.45%  |
| Seagate                     | 40        | 45     | 11.9%   |
| WDC                         | 35        | 40     | 10.42%  |
| SanDisk                     | 18        | 20     | 5.36%   |
| Kingston                    | 18        | 18     | 5.36%   |
| Unknown                     | 14        | 15     | 4.17%   |
| SK hynix                    | 14        | 14     | 4.17%   |
| Crucial                     | 11        | 12     | 3.27%   |
| Toshiba                     | 9         | 10     | 2.68%   |
| Intel                       | 9         | 11     | 2.68%   |
| Hitachi                     | 9         | 30     | 2.68%   |
| Micron/Crucial Technology   | 8         | 10     | 2.38%   |
| Phison Electronics          | 7         | 9      | 2.08%   |
| HGST                        | 6         | 6      | 1.79%   |
| China                       | 6         | 6      | 1.79%   |
| A-DATA Technology           | 6         | 6      | 1.79%   |
| Apple                       | 5         | 5      | 1.49%   |
| SPCC                        | 4         | 4      | 1.19%   |
| PNY                         | 4         | 4      | 1.19%   |
| Micron Technology           | 4         | 4      | 1.19%   |
| Kingston Technology Company | 4         | 4      | 1.19%   |
| Intenso                     | 4         | 4      | 1.19%   |
| Phison                      | 3         | 3      | 0.89%   |
| T-FORCE                     | 2         | 2      | 0.6%    |
| Silicon Motion              | 2         | 2      | 0.6%    |
| LITEONIT                    | 2         | 2      | 0.6%    |
| Unknown                     | 2         | 2      | 0.6%    |
| XPG                         | 1         | 1      | 0.3%    |
| Verbatim                    | 1         | 1      | 0.3%    |
| Transcend                   | 1         | 1      | 0.3%    |
| Team                        | 1         | 2      | 0.3%    |
| SSSTC                       | 1         | 1      | 0.3%    |
| sobetter                    | 1         | 1      | 0.3%    |
| ShiJi                       | 1         | 1      | 0.3%    |
| SABRENT                     | 1         | 1      | 0.3%    |
| S3+                         | 1         | 1      | 0.3%    |
| Realtek Semiconductor       | 1         | 1      | 0.3%    |
| Realtek                     | 1         | 1      | 0.3%    |
| Patriot                     | 1         | 1      | 0.3%    |
| Palit                       | 1         | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB      | 12        | 3.31%   |
| Samsung SSD 850 EVO 250GB                              | 5         | 1.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB    | 4         | 1.1%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB     | 4         | 1.1%    |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                    | 4         | 1.1%    |
| Unknown MMC Card  64GB                                 | 3         | 0.83%   |
| Seagate ST500DM002-1BD142 500GB                        | 3         | 0.83%   |
| Seagate ST1000DM010-2EP102 1TB                         | 3         | 0.83%   |
| Seagate Expansion Desk 8TB                             | 3         | 0.83%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                  | 3         | 0.83%   |
| SanDisk NVMe SSD Drive 1TB                             | 3         | 0.83%   |
| Samsung SSD 870 QVO 1TB                                | 3         | 0.83%   |
| Samsung SSD 860 EVO 1TB                                | 3         | 0.83%   |
| Samsung SSD 850 EVO 500GB                              | 3         | 0.83%   |
| Kingston SA400S37120G 120GB SSD                        | 3         | 0.83%   |
| Kingston OM8PCP3512F 512GB SSD                         | 3         | 0.83%   |
| Apple SSD SM0128G 121GB                                | 3         | 0.83%   |
| Unknown MMC Card  250GB                                | 2         | 0.55%   |
| Unknown MMC Card  128GB                                | 2         | 0.55%   |
| Toshiba DT01ACA100 1TB                                 | 2         | 0.55%   |
| T-FORCE 1TB                                            | 2         | 0.55%   |
| SK hynix BC511 512GB                                   | 2         | 0.55%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 1024GB | 2         | 0.55%   |
| Seagate ST4000DM004-2CV104 4TB                         | 2         | 0.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                     | 2         | 0.55%   |
| Seagate ST1000DM003-1ER162 1TB                         | 2         | 0.55%   |
| Samsung SSD 980 500GB                                  | 2         | 0.55%   |
| Samsung SSD 970 EVO Plus 1TB                           | 2         | 0.55%   |
| Samsung SSD 850 PRO 256GB                              | 2         | 0.55%   |
| Samsung MZVLB1T0HBLR-000L2 1TB                         | 2         | 0.55%   |
| PNY ELITE PSSD 240GB                                   | 2         | 0.55%   |
| Phison PS5013 E13 NVMe Controller 500GB                | 2         | 0.55%   |
| Kingston SKC3000S1024G 1TB                             | 2         | 0.55%   |
| Kingston SA400S37240G 240GB SSD                        | 2         | 0.55%   |
| Intel SSD 660P Series 512GB                            | 2         | 0.55%   |
| Hitachi HTS547575A9E384 752GB                          | 2         | 0.55%   |
| HGST HTS721010A9E630 1TB                               | 2         | 0.55%   |
| Crucial CT2000BX500SSD1 2TB                            | 2         | 0.55%   |
| A-DATA SU630 480GB SSD                                 | 2         | 0.55%   |
| Unknown                                                | 2         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 37        | 42     | 38.95%  |
| WDC                 | 30        | 35     | 31.58%  |
| Hitachi             | 9         | 30     | 9.47%   |
| Toshiba             | 7         | 8      | 7.37%   |
| HGST                | 6         | 6      | 6.32%   |
| Samsung Electronics | 3         | 3      | 3.16%   |
| SABRENT             | 1         | 1      | 1.05%   |
| Intenso             | 1         | 1      | 1.05%   |
| Fujitsu             | 1         | 1      | 1.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 38     | 30.1%   |
| Kingston            | 11        | 11     | 10.68%  |
| Crucial             | 8         | 8      | 7.77%   |
| China               | 6         | 6      | 5.83%   |
| Apple               | 5         | 5      | 4.85%   |
| A-DATA Technology   | 5         | 5      | 4.85%   |
| SK hynix            | 4         | 4      | 3.88%   |
| SanDisk             | 4         | 4      | 3.88%   |
| PNY                 | 4         | 4      | 3.88%   |
| SPCC                | 3         | 3      | 2.91%   |
| Intel               | 3         | 4      | 2.91%   |
| Micron Technology   | 2         | 2      | 1.94%   |
| LITEONIT            | 2         | 2      | 1.94%   |
| Intenso             | 2         | 2      | 1.94%   |
| WDC                 | 1         | 1      | 0.97%   |
| Verbatim            | 1         | 1      | 0.97%   |
| Transcend           | 1         | 1      | 0.97%   |
| Toshiba             | 1         | 1      | 0.97%   |
| S3+                 | 1         | 1      | 0.97%   |
| Patriot             | 1         | 1      | 0.97%   |
| Palit               | 1         | 1      | 0.97%   |
| OCZ                 | 1         | 1      | 0.97%   |
| Lexar               | 1         | 1      | 0.97%   |
| Fanxiang            | 1         | 1      | 0.97%   |
| Colorful            | 1         | 1      | 0.97%   |
| Apacer              | 1         | 1      | 0.97%   |
| Aarvex              | 1         | 1      | 0.97%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 101       | 133    | 35.31%  |
| SSD     | 86        | 111    | 30.07%  |
| HDD     | 78        | 127    | 27.27%  |
| MMC     | 11        | 11     | 3.85%   |
| Unknown | 10        | 15     | 3.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 138       | 207    | 51.3%   |
| NVMe | 100       | 132    | 37.17%  |
| SAS  | 20        | 47     | 7.43%   |
| MMC  | 11        | 11     | 4.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 87        | 108    | 48.88%  |
| 0.51-1.0   | 60        | 71     | 33.71%  |
| 1.01-2.0   | 15        | 22     | 8.43%   |
| 4.01-10.0  | 7         | 27     | 3.93%   |
| 3.01-4.0   | 6         | 7      | 3.37%   |
| 10.01-20.0 | 2         | 2      | 1.12%   |
| 2.01-3.0   | 1         | 1      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 51        | 24.29%  |
| 501-1000       | 49        | 23.33%  |
| 101-250        | 47        | 22.38%  |
| More than 3000 | 23        | 10.95%  |
| 1001-2000      | 18        | 8.57%   |
| 51-100         | 7         | 3.33%   |
| 2001-3000      | 6         | 2.86%   |
| 21-50          | 4         | 1.9%    |
| 1-20           | 3         | 1.43%   |
| Unknown        | 2         | 0.95%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 60        | 28.57%  |
| 21-50          | 40        | 19.05%  |
| 101-250        | 31        | 14.76%  |
| 51-100         | 22        | 10.48%  |
| 251-500        | 19        | 9.05%   |
| 501-1000       | 18        | 8.57%   |
| More than 3000 | 9         | 4.29%   |
| 2001-3000      | 5         | 2.38%   |
| 1001-2000      | 4         | 1.9%    |
| Unknown        | 2         | 0.95%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD20EFRX-68AX9N0 2TB           | 1         | 1      | 25%     |
| SK hynix PC711 HFS001TDE9X073N 1TB | 1         | 1      | 25%     |
| Seagate STM3500418AS 500GB         | 1         | 1      | 25%     |
| Seagate ST6000AS0002-1N917X 6TB    | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 2         | 2      | 50%     |
| WDC      | 1         | 1      | 25%     |
| SK hynix | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| WDC     | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 75%     |
| NVMe | 1         | 1      | 25%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)

![Failed Drives](./All/images/line_chart/drive_failed.svg)

| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)

![Failed Drive Vendor](./All/images/line_chart/drive_failed_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)

![Drive Status](./All/images/line_chart/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 170       | 313    | 76.23%  |
| Works    | 48        | 79     | 21.52%  |
| Malfunc  | 4         | 4      | 1.79%   |
| Failed   | 1         | 1      | 0.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 116       | 38.41%  |
| AMD                            | 58        | 19.21%  |
| Samsung Electronics            | 40        | 13.25%  |
| SanDisk                        | 18        | 5.96%   |
| Phison Electronics             | 12        | 3.97%   |
| Micron/Crucial Technology      | 11        | 3.64%   |
| SK hynix                       | 10        | 3.31%   |
| Kingston Technology Company    | 10        | 3.31%   |
| ASMedia Technology             | 6         | 1.99%   |
| Realtek Semiconductor          | 3         | 0.99%   |
| Toshiba America Info Systems   | 2         | 0.66%   |
| Solidigm                       | 2         | 0.66%   |
| Silicon Motion                 | 2         | 0.66%   |
| Micron Technology              | 2         | 0.66%   |
| JMicron Technology             | 2         | 0.66%   |
| ADATA Technology               | 2         | 0.66%   |
| Solid State Storage Technology | 1         | 0.33%   |
| Seagate Technology             | 1         | 0.33%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.33%   |
| Marvell Technology Group       | 1         | 0.33%   |
| LSI Logic / Symbios Logic      | 1         | 0.33%   |
| Lite-On Technology             | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 45        | 13.8%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 18        | 5.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 3.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10        | 3.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 2.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 2.15%   |
| AMD 500 Series Chipset SATA Controller                                         | 7         | 2.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 1.84%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 6         | 1.84%   |
| Kingston Company Company Non-Volatile memory controller                        | 6         | 1.84%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 6         | 1.84%   |
| AMD 400 Series Chipset SATA Controller                                         | 6         | 1.84%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 5         | 1.53%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 5         | 1.53%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 1.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 1.53%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 1.53%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.53%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.23%   |
| Samsung Electronics SATA controller                                            | 4         | 1.23%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 1.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.23%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 4         | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 1.23%   |
| SK hynix BC511                                                                 | 3         | 0.92%   |
| Phison Electronics Non-Volatile memory controller                              | 3         | 0.92%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3         | 0.92%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.92%   |
| Intel SSD 660P Series                                                          | 3         | 0.92%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 0.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 0.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 0.92%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 0.92%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 0.92%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 0.92%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 156       | 54.74%  |
| NVMe | 99        | 34.74%  |
| RAID | 16        | 5.61%   |
| IDE  | 13        | 4.56%   |
| SAS  | 1         | 0.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 139       | 66.19%  |
| AMD    | 70        | 33.33%  |
| ARM    | 1         | 0.48%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 1.9%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 1.9%    |
| Intel Core i7-8700 CPU @ 3.20GHz              | 3         | 1.43%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.43%   |
| Intel Core i5-5257U CPU @ 2.70GHz             | 3         | 1.43%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 1.43%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 1.43%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 1.43%   |
| AMD Ryzen 9 7950X3D 16-Core Processor         | 3         | 1.43%   |
| AMD Ryzen 7 6800HS Creator Edition            | 3         | 1.43%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.95%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.95%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.95%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.95%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.95%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 2         | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.95%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.95%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 2         | 0.95%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.95%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.95%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.95%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 2         | 0.95%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.95%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.95%   |
| Intel 12th Gen Core i7-1255U                  | 2         | 0.95%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.95%   |
| AMD Ryzen 9 7950X 16-Core Processor           | 2         | 0.95%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 2         | 0.95%   |
| AMD Ryzen 7 7700X 8-Core Processor            | 2         | 0.95%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 2         | 0.95%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 0.95%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 0.95%   |
| AMD Ryzen 7 3800XT 8-Core Processor           | 2         | 0.95%   |
| AMD Ryzen 5 7600X 6-Core Processor            | 2         | 0.95%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 0.95%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 0.95%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 2         | 0.95%   |
| AMD FX-8320E Eight-Core Processor             | 2         | 0.95%   |
| AMD Athlon Silver 3050U with Radeon Graphics  | 2         | 0.95%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 48        | 22.86%  |
| Intel Core i7        | 41        | 19.52%  |
| AMD Ryzen 7          | 28        | 13.33%  |
| Other                | 19        | 9.05%   |
| AMD Ryzen 5          | 16        | 7.62%   |
| AMD Ryzen 9          | 10        | 4.76%   |
| Intel Xeon           | 8         | 3.81%   |
| Intel Celeron        | 8         | 3.81%   |
| Intel Core i3        | 6         | 2.86%   |
| Intel Core 2 Duo     | 4         | 1.9%    |
| AMD FX               | 4         | 1.9%    |
| AMD Athlon           | 3         | 1.43%   |
| AMD A6               | 2         | 0.95%   |
| Intel Pentium Silver | 1         | 0.48%   |
| Intel Pentium        | 1         | 0.48%   |
| Intel Core m5        | 1         | 0.48%   |
| Intel Core i9        | 1         | 0.48%   |
| Intel Core 2 Quad    | 1         | 0.48%   |
| Intel Core 2         | 1         | 0.48%   |
| Intel Atom           | 1         | 0.48%   |
| AMD Ryzen Embedded   | 1         | 0.48%   |
| AMD Ryzen 7 PRO      | 1         | 0.48%   |
| AMD Ryzen 3          | 1         | 0.48%   |
| AMD Phenom II X4     | 1         | 0.48%   |
| AMD A8               | 1         | 0.48%   |
| AMD A10              | 1         | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 68        | 32.38%  |
| 2       | 61        | 29.05%  |
| 8       | 36        | 17.14%  |
| 6       | 24        | 11.43%  |
| 16      | 9         | 4.29%   |
| 12      | 6         | 2.86%   |
| 10      | 3         | 1.43%   |
| 3       | 1         | 0.48%   |
| 1       | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 208       | 99.05%  |
| 2       | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 169       | 80.48%  |
| 1       | 40        | 19.05%  |
| Unknown | 1         | 0.48%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 209       | 99.52%  |
| 64-bit         | 1         | 0.48%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 191       | 90.95%  |
| 0x0a50000d | 3         | 1.43%   |
| 0x0a601203 | 2         | 0.95%   |
| 0x0a50000c | 2         | 0.95%   |
| 0x0a404102 | 2         | 0.95%   |
| 0x08701021 | 2         | 0.95%   |
| 0x806ea    | 1         | 0.48%   |
| 0x406e3    | 1         | 0.48%   |
| 0x0a20120a | 1         | 0.48%   |
| 0x0a201205 | 1         | 0.48%   |
| 0x08608103 | 1         | 0.48%   |
| 0x08600106 | 1         | 0.48%   |
| 0x08108109 | 1         | 0.48%   |
| 0x0700010f | 1         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 35        | 16.67%  |
| Unknown          | 22        | 10.48%  |
| Haswell          | 20        | 9.52%   |
| Zen 3            | 16        | 7.62%   |
| SandyBridge      | 13        | 6.19%   |
| Zen 2            | 12        | 5.71%   |
| Skylake          | 12        | 5.71%   |
| Zen+             | 9         | 4.29%   |
| Broadwell        | 8         | 3.81%   |
| IvyBridge        | 7         | 3.33%   |
| Zen              | 6         | 2.86%   |
| Goldmont plus    | 6         | 2.86%   |
| Alderlake Hybrid | 6         | 2.86%   |
| TigerLake        | 5         | 2.38%   |
| CometLake        | 5         | 2.38%   |
| Core             | 4         | 1.9%    |
| Silvermont       | 3         | 1.43%   |
| Piledriver       | 3         | 1.43%   |
| Penryn           | 3         | 1.43%   |
| IceLake          | 3         | 1.43%   |
| Puma             | 2         | 0.95%   |
| Nehalem          | 2         | 0.95%   |
| Bulldozer        | 2         | 0.95%   |
| Westmere         | 1         | 0.48%   |
| Steamroller      | 1         | 0.48%   |
| K10              | 1         | 0.48%   |
| Jaguar           | 1         | 0.48%   |
| Goldmont         | 1         | 0.48%   |
| Excavator        | 1         | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 112       | 42.75%  |
| Nvidia | 81        | 30.92%  |
| AMD    | 69        | 26.34%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9         | 3.31%   |
| AMD Raphael                                                                 | 9         | 3.31%   |
| Intel HD Graphics 620                                                       | 7         | 2.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 7         | 2.57%   |
| Intel UHD Graphics 620                                                      | 6         | 2.21%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6         | 2.21%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 5         | 1.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 5         | 1.84%   |
| Intel HD Graphics 630                                                       | 5         | 1.84%   |
| Intel HD Graphics 5500                                                      | 5         | 1.84%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 5         | 1.84%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 5         | 1.84%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 5         | 1.84%   |
| AMD Renoir                                                                  | 5         | 1.84%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5         | 1.84%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 4         | 1.47%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 4         | 1.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 4         | 1.47%   |
| AMD Rembrandt [Radeon 680M]                                                 | 4         | 1.47%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3         | 1.1%    |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 3         | 1.1%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 1.1%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3         | 1.1%    |
| Nvidia GA102 [GeForce RTX 3090]                                             | 3         | 1.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 1.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 3         | 1.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 3         | 1.1%    |
| Intel Iris Graphics 6100                                                    | 3         | 1.1%    |
| Intel HD Graphics 530                                                       | 3         | 1.1%    |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 3         | 1.1%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 1.1%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 1.1%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3         | 1.1%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3         | 1.1%    |
| AMD Lucienne                                                                | 3         | 1.1%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 2         | 0.74%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 0.74%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2         | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 2         | 0.74%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                     | 2         | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 77        | 36.67%  |
| 1 x AMD        | 41        | 19.52%  |
| 1 x Nvidia     | 38        | 18.1%   |
| Intel + Nvidia | 25        | 11.9%   |
| AMD + Nvidia   | 18        | 8.57%   |
| 2 x AMD        | 5         | 2.38%   |
| Intel + AMD    | 5         | 2.38%   |
| Other          | 1         | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 144       | 68.57%  |
| Proprietary | 63        | 30%     |
| Unknown     | 3         | 1.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 177       | 84.29%  |
| 7.01-8.0   | 9         | 4.29%   |
| 1.01-2.0   | 9         | 4.29%   |
| 0.01-0.5   | 7         | 3.33%   |
| 8.01-16.0  | 3         | 1.43%   |
| 5.01-6.0   | 2         | 0.95%   |
| 3.01-4.0   | 1         | 0.48%   |
| 16.01-24.0 | 1         | 0.48%   |
| 0.51-1.0   | 1         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 28        | 11.76%  |
| Chimei Innolux          | 23        | 9.66%   |
| BOE                     | 20        | 8.4%    |
| AU Optronics            | 20        | 8.4%    |
| LG Display              | 17        | 7.14%   |
| Dell                    | 15        | 6.3%    |
| Goldstar                | 14        | 5.88%   |
| Sharp                   | 11        | 4.62%   |
| AOC                     | 10        | 4.2%    |
| Acer                    | 10        | 4.2%    |
| Hewlett-Packard         | 9         | 3.78%   |
| BenQ                    | 5         | 2.1%    |
| Apple                   | 5         | 2.1%    |
| Philips                 | 4         | 1.68%   |
| MSI                     | 4         | 1.68%   |
| Ancor Communications    | 4         | 1.68%   |
| PANDA                   | 3         | 1.26%   |
| NEC Computers           | 3         | 1.26%   |
| InfoVision              | 3         | 1.26%   |
| Iiyama                  | 3         | 1.26%   |
| CSO                     | 3         | 1.26%   |
| Sceptre Tech            | 2         | 0.84%   |
| Lenovo                  | 2         | 0.84%   |
| Chi Mei Optoelectronics | 2         | 0.84%   |
| ASUSTek Computer        | 2         | 0.84%   |
| Wacom                   | 1         | 0.42%   |
| Vestel Elektronik       | 1         | 0.42%   |
| Toshiba                 | 1         | 0.42%   |
| Sony                    | 1         | 0.42%   |
| Planar                  | 1         | 0.42%   |
| Medion                  | 1         | 0.42%   |
| LG Electronics          | 1         | 0.42%   |
| Kogan                   | 1         | 0.42%   |
| Insignia                | 1         | 0.42%   |
| Hitachi                 | 1         | 0.42%   |
| Gigabyte Technology     | 1         | 0.42%   |
| FUS                     | 1         | 0.42%   |
| DENON                   | 1         | 0.42%   |
| CVT                     | 1         | 0.42%   |
| CRM                     | 1         | 0.42%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 3         | 1.2%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                   | 3         | 1.2%    |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                       | 3         | 1.2%    |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch         | 2         | 0.8%    |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch     | 2         | 0.8%    |
| NEC Computers P403 NEC692B 1920x1080 886x498mm 40.0-inch                  | 2         | 0.8%    |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch              | 2         | 0.8%    |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch              | 2         | 0.8%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 2         | 0.8%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 2         | 0.8%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 2         | 0.8%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.8%    |
| BOE LCD Monitor BOE08DF 1920x1080 344x194mm 15.5-inch                     | 2         | 0.8%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                     | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.8%    |
| Acer GN246HL ACR02FA 1920x1080 531x299mm 24.0-inch                        | 2         | 0.8%    |
| Wacom Cintiq 22HD WAC1031 1920x1080 476x268mm 21.5-inch                   | 1         | 0.4%    |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch    | 1         | 0.4%    |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                          | 1         | 0.4%    |
| Sony TV SNY4502 1920x1080                                                 | 1         | 0.4%    |
| Sharp LQ135P1JX51 SHP14B3 2256x1504 285x190mm 13.5-inch                   | 1         | 0.4%    |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 1         | 0.4%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 1         | 0.4%    |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                   | 1         | 0.4%    |
| Sharp LCD Monitor SHP14A2 1920x1080 309x174mm 14.0-inch                   | 1         | 0.4%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 0.4%    |
| Sharp LCD Monitor SHP144F 1920x1080 276x156mm 12.5-inch                   | 1         | 0.4%    |
| Sharp LCD Monitor SHP144D 3840x2160 276x156mm 12.5-inch                   | 1         | 0.4%    |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                   | 1         | 0.4%    |
| Sharp LCD Monitor SHP1421 3200x1800 294x165mm 13.3-inch                   | 1         | 0.4%    |
| Sharp LCD Monitor SHP1420 1920x1080 294x165mm 13.3-inch                   | 1         | 0.4%    |
| Sceptre Tech E32 SPT0CB8 1366x768 575x323mm 26.0-inch                     | 1         | 0.4%    |
| Sceptre Tech E248W-19203S SPT099D 1920x1080 443x249mm 20.0-inch           | 1         | 0.4%    |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch         | 1         | 0.4%    |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch         | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch      | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM05D5 1360x768                           | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM0216 1280x1024 338x270mm 17.0-inch      | 1         | 0.4%    |
| Samsung Electronics SMS27A550H SAM07CC 1920x1080 598x336mm 27.0-inch      | 1         | 0.4%    |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch         | 1         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 114       | 48.93%  |
| 1366x768 (WXGA)    | 31        | 13.3%   |
| 3840x2160 (4K)     | 20        | 8.58%   |
| 2560x1440 (QHD)    | 17        | 7.3%    |
| 2560x1080          | 7         | 3%      |
| 1600x900 (HD+)     | 6         | 2.58%   |
| 3440x1440          | 5         | 2.15%   |
| 2880x1800          | 5         | 2.15%   |
| 2560x1600          | 4         | 1.72%   |
| 1920x1200 (WUXGA)  | 4         | 1.72%   |
| 1280x800 (WXGA)    | 4         | 1.72%   |
| 1440x900 (WXGA+)   | 3         | 1.29%   |
| 1360x768           | 3         | 1.29%   |
| 2160x1440          | 2         | 0.86%   |
| 1280x1024 (SXGA)   | 2         | 0.86%   |
| 3840x2400          | 1         | 0.43%   |
| 3840x1080          | 1         | 0.43%   |
| 3200x1800 (QHD+)   | 1         | 0.43%   |
| 2256x1504          | 1         | 0.43%   |
| 1680x1050 (WSXGA+) | 1         | 0.43%   |
| Unknown            | 1         | 0.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 61        | 24.8%   |
| 27      | 27        | 10.98%  |
| 13      | 21        | 8.54%   |
| 24      | 20        | 8.13%   |
| 14      | 17        | 6.91%   |
| 23      | 16        | 6.5%    |
| 34      | 11        | 4.47%   |
| 31      | 11        | 4.47%   |
| 17      | 10        | 4.07%   |
| 21      | 8         | 3.25%   |
| 12      | 5         | 2.03%   |
| 84      | 4         | 1.63%   |
| 33      | 4         | 1.63%   |
| 19      | 4         | 1.63%   |
| 40      | 3         | 1.22%   |
| 16      | 3         | 1.22%   |
| Unknown | 3         | 1.22%   |
| 72      | 2         | 0.81%   |
| 48      | 2         | 0.81%   |
| 32      | 2         | 0.81%   |
| 18      | 2         | 0.81%   |
| 11      | 2         | 0.81%   |
| 74      | 1         | 0.41%   |
| 65      | 1         | 0.41%   |
| 36      | 1         | 0.41%   |
| 29      | 1         | 0.41%   |
| 28      | 1         | 0.41%   |
| 26      | 1         | 0.41%   |
| 22      | 1         | 0.41%   |
| 20      | 1         | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 91        | 38.72%  |
| 501-600     | 54        | 22.98%  |
| 201-300     | 19        | 8.09%   |
| 701-800     | 17        | 7.23%   |
| 401-500     | 16        | 6.81%   |
| 601-700     | 12        | 5.11%   |
| 351-400     | 9         | 3.83%   |
| 1501-2000   | 7         | 2.98%   |
| 801-900     | 4         | 1.7%    |
| 1001-1500   | 3         | 1.28%   |
| Unknown     | 3         | 1.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 172       | 80%     |
| 16/10   | 25        | 11.63%  |
| 21/9    | 12        | 5.58%   |
| Unknown | 2         | 0.93%   |
| 5/4     | 1         | 0.47%   |
| 4/3     | 1         | 0.47%   |
| 32/9    | 1         | 0.47%   |
| 3/2     | 1         | 0.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 61        | 25.1%   |
| 201-250        | 34        | 13.99%  |
| 81-90          | 29        | 11.93%  |
| 301-350        | 29        | 11.93%  |
| 351-500        | 28        | 11.52%  |
| More than 1000 | 9         | 3.7%    |
| 71-80          | 9         | 3.7%    |
| 121-130        | 8         | 3.29%   |
| 251-300        | 7         | 2.88%   |
| 151-200        | 7         | 2.88%   |
| 61-70          | 5         | 2.06%   |
| 501-1000       | 5         | 2.06%   |
| 141-150        | 3         | 1.23%   |
| 111-120        | 3         | 1.23%   |
| Unknown        | 3         | 1.23%   |
| 51-60          | 2         | 0.82%   |
| 131-140        | 1         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 76        | 32.9%   |
| 121-160       | 68        | 29.44%  |
| 101-120       | 51        | 22.08%  |
| 161-240       | 18        | 7.79%   |
| More than 240 | 9         | 3.9%    |
| 1-50          | 6         | 2.6%    |
| Unknown       | 3         | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 164       | 78.1%   |
| 2     | 33        | 15.71%  |
| 3     | 7         | 3.33%   |
| 0     | 5         | 2.38%   |
| 4     | 1         | 0.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 118       | 36.99%  |
| Intel                             | 104       | 32.6%   |
| Qualcomm Atheros                  | 25        | 7.84%   |
| MediaTek                          | 12        | 3.76%   |
| Broadcom                          | 11        | 3.45%   |
| TP-Link                           | 5         | 1.57%   |
| Broadcom Limited                  | 5         | 1.57%   |
| Ralink                            | 4         | 1.25%   |
| Marvell Technology Group          | 4         | 1.25%   |
| Microsoft                         | 3         | 0.94%   |
| Sierra Wireless                   | 2         | 0.63%   |
| Samsung Electronics               | 2         | 0.63%   |
| Ralink Technology                 | 2         | 0.63%   |
| OPPO Electronics                  | 2         | 0.63%   |
| NetGear                           | 2         | 0.63%   |
| Linksys                           | 2         | 0.63%   |
| ASUSTek Computer                  | 2         | 0.63%   |
| ASIX Electronics                  | 2         | 0.63%   |
| Xiaomi                            | 1         | 0.31%   |
| VIA Technologies                  | 1         | 0.31%   |
| Qualcomm Atheros Communications   | 1         | 0.31%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.31%   |
| Mellanox Technologies             | 1         | 0.31%   |
| InterBiometrics                   | 1         | 0.31%   |
| Hewlett-Packard                   | 1         | 0.31%   |
| Google                            | 1         | 0.31%   |
| Fibocom                           | 1         | 0.31%   |
| Ericsson Business Mobile Networks | 1         | 0.31%   |
| Dell                              | 1         | 0.31%   |
| D-Link System                     | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 17.69%  |
| Realtek RTL8125 2.5GbE Controller                                 | 20        | 5.36%   |
| Intel Wireless 8265 / 8275                                        | 10        | 2.68%   |
| Intel Wi-Fi 6 AX200                                               | 10        | 2.68%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 2.41%   |
| Intel I211 Gigabit Network Connection                             | 9         | 2.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 1.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6         | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.34%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 5         | 1.34%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 1.34%   |
| Intel Ethernet Controller I225-V                                  | 5         | 1.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 1.34%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 4         | 1.07%   |
| Realtek 802.11ac NIC                                              | 4         | 1.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 1.07%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4         | 1.07%   |
| Intel Wireless 7260                                               | 4         | 1.07%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 1.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.07%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 1.07%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.8%    |
| Intel Wireless 8260                                               | 3         | 0.8%    |
| Intel Wireless 7265                                               | 3         | 0.8%    |
| Intel Wireless 3165                                               | 3         | 0.8%    |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.8%    |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 3         | 0.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 0.8%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 3         | 0.8%    |
| Sierra Wireless EM7455                                            | 2         | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.54%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.54%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 83        | 44.15%  |
| Realtek Semiconductor           | 34        | 18.09%  |
| Qualcomm Atheros                | 19        | 10.11%  |
| MediaTek                        | 12        | 6.38%   |
| Broadcom                        | 9         | 4.79%   |
| TP-Link                         | 4         | 2.13%   |
| Ralink                          | 4         | 2.13%   |
| Broadcom Limited                | 4         | 2.13%   |
| Microsoft                       | 3         | 1.6%    |
| Sierra Wireless                 | 2         | 1.06%   |
| Ralink Technology               | 2         | 1.06%   |
| NetGear                         | 2         | 1.06%   |
| Marvell Technology Group        | 2         | 1.06%   |
| Linksys                         | 2         | 1.06%   |
| ASUSTek Computer                | 2         | 1.06%   |
| Qualcomm Atheros Communications | 1         | 0.53%   |
| Hewlett-Packard                 | 1         | 0.53%   |
| Fibocom                         | 1         | 0.53%   |
| D-Link System                   | 1         | 0.53%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                    | 10        | 5.29%   |
| Intel Wi-Fi 6 AX200                                           | 10        | 5.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 7         | 3.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 7         | 3.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 6         | 3.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 5         | 2.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 5         | 2.65%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 5         | 2.65%   |
| Intel Wi-Fi 6 AX201                                           | 5         | 2.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 4         | 2.12%   |
| Realtek 802.11ac NIC                                          | 4         | 2.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 4         | 2.12%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 4         | 2.12%   |
| Intel Wireless 7260                                           | 4         | 2.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 4         | 2.12%   |
| Intel Comet Lake PCH CNVi WiFi                                | 4         | 2.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 3         | 1.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3         | 1.59%   |
| Intel Wireless 8260                                           | 3         | 1.59%   |
| Intel Wireless 7265                                           | 3         | 1.59%   |
| Intel Wireless 3165                                           | 3         | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 3         | 1.59%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 3         | 1.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 3         | 1.59%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter    | 3         | 1.59%   |
| Sierra Wireless EM7455                                        | 2         | 1.06%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 2         | 1.06%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 2         | 1.06%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 2         | 1.06%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                     | 2         | 1.06%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]   | 2         | 1.06%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless             | 2         | 1.06%   |
| Intel Wireless-AC 9260                                        | 2         | 1.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 1.06%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 2         | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 2         | 1.06%   |
| Intel Centrino Wireless-N 130                                 | 2         | 1.06%   |
| Intel Centrino Ultimate-N 6300                                | 2         | 1.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 2         | 1.06%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 102       | 56.98%  |
| Intel                         | 48        | 26.82%  |
| Qualcomm Atheros              | 10        | 5.59%   |
| Broadcom                      | 4         | 2.23%   |
| Samsung Electronics           | 2         | 1.12%   |
| OPPO Electronics              | 2         | 1.12%   |
| Marvell Technology Group      | 2         | 1.12%   |
| ASIX Electronics              | 2         | 1.12%   |
| Xiaomi                        | 1         | 0.56%   |
| VIA Technologies              | 1         | 0.56%   |
| TP-Link                       | 1         | 0.56%   |
| OnePlus Technology (Shenzhen) | 1         | 0.56%   |
| Mellanox Technologies         | 1         | 0.56%   |
| Google                        | 1         | 0.56%   |
| Broadcom Limited              | 1         | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 36.46%  |
| Realtek RTL8125 2.5GbE Controller                                 | 20        | 11.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 4.97%   |
| Intel I211 Gigabit Network Connection                             | 9         | 4.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 3.87%   |
| Intel Ethernet Controller I225-V                                  | 5         | 2.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 2.21%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 1.66%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.66%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.1%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.1%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.1%    |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                              | 2         | 1.1%    |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.1%    |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.1%    |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.1%    |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.1%    |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.1%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.1%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.55%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.55%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.55%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.55%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 0.55%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1         | 0.55%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.55%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.55%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.55%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.55%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.55%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.55%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.55%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 0.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 169       | 50.3%   |
| Ethernet | 164       | 48.81%  |
| Modem    | 3         | 0.89%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 130       | 60.75%  |
| Ethernet | 84        | 39.25%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 102       | 48.57%  |
| 1     | 96        | 45.71%  |
| 3     | 6         | 2.86%   |
| 0     | 6         | 2.86%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 148       | 70.48%  |
| Yes  | 62        | 29.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 70        | 47.62%  |
| Realtek Semiconductor           | 18        | 12.24%  |
| Qualcomm Atheros Communications | 12        | 8.16%   |
| MediaTek                        | 8         | 5.44%   |
| Apple                           | 6         | 4.08%   |
| Foxconn / Hon Hai               | 5         | 3.4%    |
| Cambridge Silicon Radio         | 5         | 3.4%    |
| Broadcom                        | 5         | 3.4%    |
| Lite-On Technology              | 4         | 2.72%   |
| ASUSTek Computer                | 3         | 2.04%   |
| TP-Link                         | 2         | 1.36%   |
| Marvell Semiconductor           | 2         | 1.36%   |
| IMC Networks                    | 2         | 1.36%   |
| Dell                            | 2         | 1.36%   |
| Realtek                         | 1         | 0.68%   |
| Ralink                          | 1         | 0.68%   |
| Actions                         | 1         | 0.68%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 23        | 15.65%  |
| Intel AX201 Bluetooth                                                               | 16        | 10.88%  |
| Realtek Bluetooth Radio                                                             | 14        | 9.52%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 6.12%   |
| Intel AX200 Bluetooth                                                               | 9         | 6.12%   |
| MediaTek Wireless_Device                                                            | 8         | 5.44%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 4.76%   |
| Intel AX210 Bluetooth                                                               | 6         | 4.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 3.4%    |
| Apple Bluetooth Host Controller                                                     | 4         | 2.72%   |
| Intel Bluetooth Device                                                              | 3         | 2.04%   |
| TP-Link UB500 Adapter                                                               | 2         | 1.36%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.36%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 1.36%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 2         | 1.36%   |
| Lite-On Wireless_Device                                                             | 2         | 1.36%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.36%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.36%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.36%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth                                     | 2         | 1.36%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.68%   |
| Realtek Bluetooth 5.1 Radio                                                         | 1         | 0.68%   |
| Realtek 802.11ac WLAN Adapter                                                       | 1         | 0.68%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.68%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.68%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.68%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.68%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.68%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.68%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.68%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.68%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.68%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.68%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.68%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle                                  | 1         | 0.68%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.68%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 0.68%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.68%   |
| Broadcom BCM2045A0                                                                  | 1         | 0.68%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.68%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 138       | 42.33%  |
| AMD                                  | 78        | 23.93%  |
| Nvidia                               | 64        | 19.63%  |
| C-Media Electronics                  | 7         | 2.15%   |
| Micro Star International             | 5         | 1.53%   |
| Focusrite-Novation                   | 3         | 0.92%   |
| ASUSTek Computer                     | 3         | 0.92%   |
| SteelSeries ApS                      | 2         | 0.61%   |
| Razer USA                            | 2         | 0.61%   |
| JMTek                                | 2         | 0.61%   |
| Generalplus Technology               | 2         | 0.61%   |
| DSEA A/S                             | 2         | 0.61%   |
| Creative Technology                  | 2         | 0.61%   |
| Trust                                | 1         | 0.31%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.31%   |
| Solid State Logic                    | 1         | 0.31%   |
| RME                                  | 1         | 0.31%   |
| Realtek Semiconductor                | 1         | 0.31%   |
| Plantronics                          | 1         | 0.31%   |
| Nordic Semiconductor ASA             | 1         | 0.31%   |
| Mackie Designs                       | 1         | 0.31%   |
| Logitech                             | 1         | 0.31%   |
| Lewitt                               | 1         | 0.31%   |
| Kingston Technology                  | 1         | 0.31%   |
| GYROCOM C&C                          | 1         | 0.31%   |
| GN Netcom                            | 1         | 0.31%   |
| Corsair                              | 1         | 0.31%   |
| CMTECK                               | 1         | 0.31%   |
| AKAI Professional M.I.               | 1         | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 38        | 9.48%   |
| Intel Sunrise Point-LP HD Audio                                                   | 19        | 4.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 13        | 3.24%   |
| AMD Starship/Matisse HD Audio Controller                                          | 13        | 3.24%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 13        | 3.24%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 13        | 3.24%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 11        | 2.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 9         | 2.24%   |
| Nvidia GA104 High Definition Audio Controller                                     | 8         | 2%      |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 8         | 2%      |
| Intel Broadwell-U Audio Controller                                                | 8         | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 8         | 2%      |
| Intel Cannon Lake PCH cAVS                                                        | 7         | 1.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 7         | 1.75%   |
| Nvidia TU106 High Definition Audio Controller                                     | 6         | 1.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 6         | 1.5%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 6         | 1.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 6         | 1.5%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 5         | 1.25%   |
| Nvidia GA102 High Definition Audio Controller                                     | 5         | 1.25%   |
| Micro Star International USB Audio                                                | 5         | 1.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 5         | 1.25%   |
| Intel Haswell-ULT HD Audio Controller                                             | 5         | 1.25%   |
| Intel Alder Lake-S HD Audio Controller                                            | 5         | 1.25%   |
| Intel 8 Series HD Audio Controller                                                | 5         | 1.25%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 5         | 1.25%   |
| AMD FCH Azalia Controller                                                         | 5         | 1.25%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 5         | 1.25%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4         | 1%      |
| Nvidia GP104 High Definition Audio Controller                                     | 4         | 1%      |
| Nvidia GF108 High Definition Audio Controller                                     | 4         | 1%      |
| Nvidia GA106 High Definition Audio Controller                                     | 4         | 1%      |
| Intel Comet Lake PCH-LP cAVS                                                      | 4         | 1%      |
| Intel Comet Lake PCH cAVS                                                         | 4         | 1%      |
| Intel CM238 HD Audio Controller                                                   | 4         | 1%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 4         | 1%      |
| Intel 200 Series PCH HD Audio                                                     | 4         | 1%      |
| C-Media Electronics Blue Snowball                                                 | 4         | 1%      |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4         | 1%      |
| Nvidia TU116 High Definition Audio Controller                                     | 3         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 25%     |
| SK hynix            | 13        | 20.31%  |
| Micron Technology   | 8         | 12.5%   |
| G.Skill             | 4         | 6.25%   |
| Corsair             | 4         | 6.25%   |
| A-DATA Technology   | 4         | 6.25%   |
| Crucial             | 3         | 4.69%   |
| Unknown (ABCD)      | 2         | 3.13%   |
| Team                | 2         | 3.13%   |
| Neo Forza           | 2         | 3.13%   |
| Kingston            | 2         | 3.13%   |
| Unknown (09B6)      | 1         | 1.56%   |
| Unknown (09A4)      | 1         | 1.56%   |
| Unknown             | 1         | 1.56%   |
| Goldkey             | 1         | 1.56%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 2.99%   |
| Samsung RAM Module 4GB SODIMM DDR3 1867MT/s                      | 2         | 2.99%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 2.99%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.99%   |
| Unknown RAM Module 4GB DIMM DDR3 667MT/s                         | 1         | 1.49%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 1         | 1.49%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 1.49%   |
| Unknown (09B6) RAM 16D2666CL190 16GB SODIMM DDR4 2667MT/s        | 1         | 1.49%   |
| Unknown (09A4) RAM 16D2666CL190 16GB SODIMM DDR4 2667MT/s        | 1         | 1.49%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s               | 1         | 1.49%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2933MT/s              | 1         | 1.49%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.49%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 1.49%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 1         | 1.49%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.49%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.49%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.49%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.49%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.49%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 1         | 1.49%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 1.49%   |
| SK hynix RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s           | 1         | 1.49%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.49%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.49%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.49%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.49%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.49%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s            | 1         | 1.49%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.49%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.49%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.49%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.49%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s              | 1         | 1.49%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s              | 1         | 1.49%   |
| Neo Forza RAM NMUD480E82-2400E 8GB DIMM DDR4 2400MT/s            | 1         | 1.49%   |
| Neo Forza RAM NMSO416E82-3200E 16GB SODIMM DDR4 3200MT/s         | 1         | 1.49%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 1.49%   |
| Micron RAM MT53E512M32D2NP-046 4GB SODIMM LPDDR4 4266MT/s        | 1         | 1.49%   |
| Micron RAM MT53E1G32D4NQ-046 8GB Row Of Chips LPDDR4 4267MT/s    | 1         | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 37        | 66.07%  |
| DDR3   | 9         | 16.07%  |
| LPDDR4 | 4         | 7.14%   |
| LPDDR5 | 3         | 5.36%   |
| DDR5   | 3         | 5.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 36        | 62.07%  |
| DIMM         | 17        | 29.31%  |
| Row Of Chips | 5         | 8.62%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 26        | 44.07%  |
| 16384 | 15        | 25.42%  |
| 4096  | 12        | 20.34%  |
| 32768 | 5         | 8.47%   |
| 2048  | 1         | 1.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 15        | 24.59%  |
| 2667  | 10        | 16.39%  |
| 2400  | 7         | 11.48%  |
| 1600  | 5         | 8.2%    |
| 3600  | 4         | 6.56%   |
| 6400  | 3         | 4.92%   |
| 4800  | 2         | 3.28%   |
| 1867  | 2         | 3.28%   |
| 6000  | 1         | 1.64%   |
| 4267  | 1         | 1.64%   |
| 4266  | 1         | 1.64%   |
| 3733  | 1         | 1.64%   |
| 3534  | 1         | 1.64%   |
| 3500  | 1         | 1.64%   |
| 3266  | 1         | 1.64%   |
| 3000  | 1         | 1.64%   |
| 2933  | 1         | 1.64%   |
| 2133  | 1         | 1.64%   |
| 1800  | 1         | 1.64%   |
| 667   | 1         | 1.64%   |
| 666   | 1         | 1.64%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)

![Printer Vendor](./All/images/line_chart/printer_vendor.svg)

| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 1         | 33.33%  |
| Canon              | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)

![Printer Model](./All/images/line_chart/printer_model.svg)

| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 33.33%  |
| Canon TR4700 series                          | 1         | 33.33%  |
| Brother HL-1200 series                       | 1         | 33.33%  |

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
| Chicony Electronics                    | 18        | 14.06%  |
| Microdia                               | 16        | 12.5%   |
| IMC Networks                           | 14        | 10.94%  |
| Realtek Semiconductor                  | 10        | 7.81%   |
| Sunplus Innovation Technology          | 8         | 6.25%   |
| Bison Electronics                      | 7         | 5.47%   |
| Acer                                   | 7         | 5.47%   |
| Luxvisions Innotech Limited            | 6         | 4.69%   |
| Syntek                                 | 5         | 3.91%   |
| Microsoft                              | 5         | 3.91%   |
| Logitech                               | 5         | 3.91%   |
| Quanta                                 | 3         | 2.34%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.34%   |
| SunplusIT                              | 2         | 1.56%   |
| Silicon Motion                         | 2         | 1.56%   |
| icSpring                               | 2         | 1.56%   |
| Apple                                  | 2         | 1.56%   |
| Xiongmai                               | 1         | 0.78%   |
| XHT-210518                             | 1         | 0.78%   |
| Suyin                                  | 1         | 0.78%   |
| Sonix Technology                       | 1         | 0.78%   |
| Samsung Electronics                    | 1         | 0.78%   |
| Ricoh                                  | 1         | 0.78%   |
| Razer USA                              | 1         | 0.78%   |
| OmniVision Technologies                | 1         | 0.78%   |
| Lenovo                                 | 1         | 0.78%   |
| Hewlett-Packard                        | 1         | 0.78%   |
| Generalplus Technology                 | 1         | 0.78%   |
| Creative Technology                    | 1         | 0.78%   |
| AVerMedia Technologies                 | 1         | 0.78%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 7         | 5.38%   |
| Syntek Integrated Camera                            | 5         | 3.85%   |
| Microdia Integrated_Webcam_HD                       | 5         | 3.85%   |
| Sunplus Integrated_Webcam_HD                        | 3         | 2.31%   |
| Realtek USB Camera                                  | 3         | 2.31%   |
| Realtek Integrated_Webcam_HD                        | 3         | 2.31%   |
| IMC Networks Integrated Camera                      | 3         | 2.31%   |
| Bison BisonCam,NB Pro                               | 3         | 2.31%   |
| Realtek Integrated Webcam HD                        | 2         | 1.54%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.54%   |
| Microsoft LifeCam Rear                              | 2         | 1.54%   |
| Microsoft LifeCam Front                             | 2         | 1.54%   |
| Microdia Integrated_Webcam_FHD                      | 2         | 1.54%   |
| Microdia Integrated Webcam HD                       | 2         | 1.54%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 1.54%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 1.54%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 1.54%   |
| IMC Networks ov9734_azurewave_camera                | 2         | 1.54%   |
| IMC Networks Integrated RGB Camera                  | 2         | 1.54%   |
| IMC Networks EasyCamera                             | 2         | 1.54%   |
| icSpring camera                                     | 2         | 1.54%   |
| Chicony HP True Vision HD Camera                    | 2         | 1.54%   |
| Chicony HD WebCam                                   | 2         | 1.54%   |
| Chicony HD User Facing                              | 2         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 2         | 1.54%   |
| Bison SunplusIT Integrated Camera                   | 2         | 1.54%   |
| Apple FaceTime HD Camera                            | 2         | 1.54%   |
| Acer Lenovo EasyCamera                              | 2         | 1.54%   |
| Acer Integrated Camera                              | 2         | 1.54%   |
| Xiongmai web camera                                 | 1         | 0.77%   |
| XHT-210518 EC500X                                   | 1         | 0.77%   |
| Suyin HP TrueVision HD                              | 1         | 0.77%   |
| SunplusIT USB camera                                | 1         | 0.77%   |
| SunplusIT 720p HD Camera                            | 1         | 0.77%   |
| Sunplus SPCA2650 PC Camera                          | 1         | 0.77%   |
| Sunplus MTD Camera                                  | 1         | 0.77%   |
| Sunplus Laptop Integrated Webcam HD                 | 1         | 0.77%   |
| Sunplus HP HD Webcam [Fixed]                        | 1         | 0.77%   |
| Sunplus Asus Webcam                                 | 1         | 0.77%   |
| Sonix USB2.0 FHD UVC WebCam                         | 1         | 0.77%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 29.63%  |
| Synaptics                  | 8         | 29.63%  |
| Shenzhen Goodix Technology | 6         | 22.22%  |
| Upek                       | 1         | 3.7%    |
| HOLTEK                     | 1         | 3.7%    |
| Focal-systems.Corp         | 1         | 3.7%    |
| Elan Microelectronics      | 1         | 3.7%    |
| AuthenTec                  | 1         | 3.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix FingerPrint                              | 3         | 11.11%  |
| Validity Sensors VFS495 Fingerprint Reader               | 2         | 7.41%   |
| Validity Sensors Swipe Fingerprint Sensor                | 2         | 7.41%   |
| Synaptics UWP WBDI                                       | 2         | 7.41%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 2         | 7.41%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 2         | 7.41%   |
| Shenzhen Goodix  Fingerprint Device                      | 2         | 7.41%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 1         | 3.7%    |
| Validity Sensors VFS471 Fingerprint Reader               | 1         | 3.7%    |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 3.7%    |
| Validity Sensors Synaptics WBDI                          | 1         | 3.7%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 1         | 3.7%    |
| Synaptics WBDI Fingerprint Reader USB 086                | 1         | 3.7%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 3.7%    |
| Shenzhen Goodix Fingerprint Reader                       | 1         | 3.7%    |
| HOLTEK FocalTech Fingerprint Device                      | 1         | 3.7%    |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 3.7%    |
| Elan ELAN:Fingerprint                                    | 1         | 3.7%    |
| AuthenTec AES2501 Fingerprint Sensor                     | 1         | 3.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./All/images/line_chart/chipcard_vendor.svg)

| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 5         | 62.5%   |
| Broadcom    | 3         | 37.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 50%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 12.5%   |
| Broadcom 5880                                                                | 1         | 12.5%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 147       | 70%     |
| 1     | 53        | 25.24%  |
| 2     | 9         | 4.29%   |
| 3     | 1         | 0.48%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 27        | 37.5%   |
| Net/wireless             | 11        | 15.28%  |
| Graphics card            | 10        | 13.89%  |
| Multimedia controller    | 8         | 11.11%  |
| Chipcard                 | 8         | 11.11%  |
| Camera                   | 3         | 4.17%   |
| Bluetooth                | 2         | 2.78%   |
| Storage                  | 1         | 1.39%   |
| Network                  | 1         | 1.39%   |
| Communication controller | 1         | 1.39%   |

