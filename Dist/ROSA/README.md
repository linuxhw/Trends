ROSA Hardware Trends
--------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by ROSA users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/ROSA/Desktop/README.md) and [notebooks](/Dist/ROSA/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

Period: Oct, 2021.

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
| ROSA R11.1  | 108       | 49.54%  |
| ROSA 12     | 102       | 46.79%  |
| ROSA R12    | 5         | 2.29%   |
| ROSA R9-R11 | 1         | 0.46%   |
| ROSA R9     | 1         | 0.46%   |
| ROSA R11    | 1         | 0.46%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| ROSA | 218       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 5.10.71-generic-1rosa2021.1-x86_64  | 101       | 46.33%  |
| 5.4.83-generic-2rosa-x86_64         | 31        | 14.22%  |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 23        | 10.55%  |
| 5.4.32-generic-2rosa-x86_64         | 18        | 8.26%   |
| 5.4.32-generic-2rosa-i586           | 13        | 5.96%   |
| 5.4.83-generic-2rosa-i586           | 10        | 4.59%   |
| 4.15.0-desktop-122.124.1rosa-i586   | 5         | 2.29%   |
| 5.10.70-generic-2rosa2021.1-x86_64  | 4         | 1.83%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 4         | 1.83%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 2         | 0.92%   |
| 5.4.150-generic-1rosa2021.1-x86_64  | 1         | 0.46%   |
| 5.4.122-nrj-desktop-1rosa-x86_64    | 1         | 0.46%   |
| 5.11.0-desktop-18.19.1rosa-x86_64   | 1         | 0.46%   |
| 5.10.65-generic-2rosa2021.1-x86_64  | 1         | 0.46%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 1         | 0.46%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 1         | 0.46%   |
| 4.15.0-desktop-45.1rosa-i586        | 1         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.71 | 101       | 46.33%  |
| 5.4.83  | 41        | 18.81%  |
| 4.15.0  | 32        | 14.68%  |
| 5.4.32  | 31        | 14.22%  |
| 5.10.70 | 4         | 1.83%   |
| 4.9.155 | 4         | 1.83%   |
| 5.4.150 | 1         | 0.46%   |
| 5.4.122 | 1         | 0.46%   |
| 5.11.0  | 1         | 0.46%   |
| 5.10.65 | 1         | 0.46%   |
| 4.9.20  | 1         | 0.46%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 106       | 48.62%  |
| 5.4     | 74        | 33.94%  |
| 4.15    | 32        | 14.68%  |
| 4.9     | 5         | 2.29%   |
| 5.11    | 1         | 0.46%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 188       | 86.24%  |
| i686   | 30        | 13.76%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| KDE5    | 133       | 61.01%  |
| KDE4    | 60        | 27.52%  |
| LXQt    | 17        | 7.8%    |
| XFCE    | 4         | 1.83%   |
| GNOME   | 3         | 1.38%   |
| Unknown | 1         | 0.46%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 128       | 58.72%  |
| Wayland | 90        | 41.28%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| GDM  | 103       | 47.25%  |
| KDM  | 60        | 27.52%  |
| SDDM | 55        | 25.23%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang    | Computers | Percent |
|---------|-----------|---------|
| ru_RU   | 184       | 84.4%   |
| en_US   | 7         | 3.21%   |
| pt_BR   | 5         | 2.29%   |
| fr_FR   | 4         | 1.83%   |
| ru_UA   | 3         | 1.38%   |
| en_GB   | 3         | 1.38%   |
| pl_PL   | 2         | 0.92%   |
| fr_BE   | 2         | 0.92%   |
| de_DE   | 2         | 0.92%   |
| Unknown | 2         | 0.92%   |
| pt_PT   | 1         | 0.46%   |
| es_ES   | 1         | 0.46%   |
| es_CO   | 1         | 0.46%   |
| C       | 1         | 0.46%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 143       | 65.6%   |
| EFI  | 75        | 34.4%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 207       | 94.95%  |
| Btrfs | 5         | 2.29%   |
| Ext3  | 3         | 1.38%   |
| Xfs   | 1         | 0.46%   |
| F2fs  | 1         | 0.46%   |
| Aufs  | 1         | 0.46%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type | Computers | Percent |
|------|-----------|---------|
| MBR  | 133       | 61.01%  |
| GPT  | 85        | 38.99%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 152       | 69.72%  |
| Yes       | 66        | 30.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 119       | 54.59%  |
| Yes       | 99        | 45.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 45        | 20.64%  |
| Lenovo              | 22        | 10.09%  |
| Gigabyte Technology | 22        | 10.09%  |
| MSI                 | 20        | 9.17%   |
| Hewlett-Packard     | 19        | 8.72%   |
| ASRock              | 18        | 8.26%   |
| Acer                | 15        | 6.88%   |
| Dell                | 10        | 4.59%   |
| Samsung Electronics | 8         | 3.67%   |
| Intel               | 5         | 2.29%   |
| Sony                | 3         | 1.38%   |
| eMachines           | 3         | 1.38%   |
| Unknown             | 3         | 1.38%   |
| Toshiba             | 2         | 0.92%   |
| Shuttle             | 2         | 0.92%   |
| Packard Bell        | 2         | 0.92%   |
| Huanan              | 2         | 0.92%   |
| ECS                 | 2         | 0.92%   |
| Apple               | 2         | 0.92%   |
| Quanta              | 1         | 0.46%   |
| Nvidia              | 1         | 0.46%   |
| Medion              | 1         | 0.46%   |
| iRU                 | 1         | 0.46%   |
| ICL                 | 1         | 0.46%   |
| IBM                 | 1         | 0.46%   |
| Fujitsu Siemens     | 1         | 0.46%   |
| Fujitsu             | 1         | 0.46%   |
| Compaq              | 1         | 0.46%   |
| Colorful Technology | 1         | 0.46%   |
| Biostar             | 1         | 0.46%   |
| Athermiter/PlexHD   | 1         | 0.46%   |
| AQUARIUS            | 1         | 0.46%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 4         | 1.83%   |
| ASUS All Series                        | 3         | 1.38%   |
| MSI MS-7A36                            | 2         | 0.92%   |
| MSI MS-7592                            | 2         | 0.92%   |
| MSI MS-7529                            | 2         | 0.92%   |
| HP Pavilion dv6                        | 2         | 0.92%   |
| Dell OptiPlex 760                      | 2         | 0.92%   |
| Dell Inspiron N5110                    | 2         | 0.92%   |
| ASRock G41M-VS3                        | 2         | 0.92%   |
| ASRock G31M-GS                         | 2         | 0.92%   |
| Acer Aspire E5-573G                    | 2         | 0.92%   |
| Toshiba Satellite U300                 | 1         | 0.46%   |
| Toshiba Satellite C655                 | 1         | 0.46%   |
| Sony VGN-Z11VRN_B                      | 1         | 0.46%   |
| Sony VGN-CR19VN_B                      | 1         | 0.46%   |
| Sony SVE1512G1RB                       | 1         | 0.46%   |
| Shuttle SN78S                          | 1         | 0.46%   |
| Shuttle DS57U                          | 1         | 0.46%   |
| Samsung R530/R730                      | 1         | 0.46%   |
| Samsung R528/R728                      | 1         | 0.46%   |
| Samsung R508                           | 1         | 0.46%   |
| Samsung NC210/NC110                    | 1         | 0.46%   |
| Samsung NC110P/NC108P/NC111P           | 1         | 0.46%   |
| Samsung NC10                           | 1         | 0.46%   |
| Samsung 350V5C/351V5C/3540VC/3440VC    | 1         | 0.46%   |
| Samsung 300E5K/300E5Q                  | 1         | 0.46%   |
| Quanta TWH                             | 1         | 0.46%   |
| Packard Bell EasyNote TJ71             | 1         | 0.46%   |
| Packard Bell EasyNote TE11HC           | 1         | 0.46%   |
| Nvidia MCP7A                           | 1         | 0.46%   |
| MSI MS-7C51                            | 1         | 0.46%   |
| MSI MS-7B98                            | 1         | 0.46%   |
| MSI MS-7B38                            | 1         | 0.46%   |
| MSI MS-7A33                            | 1         | 0.46%   |
| MSI MS-7A15                            | 1         | 0.46%   |
| MSI MS-7995                            | 1         | 0.46%   |
| MSI MS-7817                            | 1         | 0.46%   |
| MSI MS-7808                            | 1         | 0.46%   |
| MSI MS-7721                            | 1         | 0.46%   |
| MSI MS-7693                            | 1         | 0.46%   |
| MSI MS-7309                            | 1         | 0.46%   |
| MSI MS-7222                            | 1         | 0.46%   |
| MSI GL65 9SEK                          | 1         | 0.46%   |
| MSI CR61 2M/CX61 2OC/CX61 2OD          | 1         | 0.46%   |
| Medion V20                             | 1         | 0.46%   |
| Lenovo V580c 20160                     | 1         | 0.46%   |
| Lenovo ThinkPad T60p 200793G           | 1         | 0.46%   |
| Lenovo ThinkCentre M93z 10AES02G00     | 1         | 0.46%   |
| Lenovo ThinkCentre M71e 3167A46        | 1         | 0.46%   |
| Lenovo ThinkCentre A55 89857DG         | 1         | 0.46%   |
| Lenovo S40-70 80GQ                     | 1         | 0.46%   |
| Lenovo IdeaPad Z580                    | 1         | 0.46%   |
| Lenovo IdeaPad S205 Brazos             | 1         | 0.46%   |
| Lenovo IdeaPad S12 20021,2959          | 1         | 0.46%   |
| Lenovo IdeaPad 330-15AST 81D6          | 1         | 0.46%   |
| Lenovo IdeaPad 320-15IAP 80XR          | 1         | 0.46%   |
| Lenovo IdeaPad 3 17ADA05 81W2          | 1         | 0.46%   |
| Lenovo IdeaPad 110-15ACL 80TJ          | 1         | 0.46%   |
| Lenovo IdeaCentre 300-20ISH 90DA00HNRS | 1         | 0.46%   |
| Lenovo H420                            | 1         | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 7         | 3.21%   |
| Acer Aspire           | 7         | 3.21%   |
| HP Pavilion           | 6         | 2.75%   |
| Dell Inspiron         | 6         | 2.75%   |
| ASUS PRIME            | 4         | 1.83%   |
| Unknown               | 4         | 1.83%   |
| Lenovo ThinkCentre    | 3         | 1.38%   |
| HP Compaq             | 3         | 1.38%   |
| Dell OptiPlex         | 3         | 1.38%   |
| ASUS All              | 3         | 1.38%   |
| Toshiba Satellite     | 2         | 0.92%   |
| Packard Bell EasyNote | 2         | 0.92%   |
| MSI MS-7A36           | 2         | 0.92%   |
| MSI MS-7592           | 2         | 0.92%   |
| MSI MS-7529           | 2         | 0.92%   |
| Lenovo G580           | 2         | 0.92%   |
| Lenovo B590           | 2         | 0.92%   |
| HP Mini               | 2         | 0.92%   |
| ASUS VivoBook         | 2         | 0.92%   |
| ASUS P8H61-M          | 2         | 0.92%   |
| ASRock G41M-VS3       | 2         | 0.92%   |
| ASRock G31M-GS        | 2         | 0.92%   |
| Acer Veriton          | 2         | 0.92%   |
| Acer TravelMate       | 2         | 0.92%   |
| Sony VGN-Z11VRN       | 1         | 0.46%   |
| Sony VGN-CR19VN       | 1         | 0.46%   |
| Sony SVE1512G1RB      | 1         | 0.46%   |
| Shuttle SN78S         | 1         | 0.46%   |
| Shuttle DS57U         | 1         | 0.46%   |
| Samsung R530          | 1         | 0.46%   |
| Samsung R528          | 1         | 0.46%   |
| Samsung R508          | 1         | 0.46%   |
| Samsung NC210         | 1         | 0.46%   |
| Samsung NC110P        | 1         | 0.46%   |
| Samsung NC10          | 1         | 0.46%   |
| Samsung 350V5C        | 1         | 0.46%   |
| Samsung 300E5K        | 1         | 0.46%   |
| Quanta TWH            | 1         | 0.46%   |
| Nvidia MCP7A          | 1         | 0.46%   |
| MSI MS-7C51           | 1         | 0.46%   |
| MSI MS-7B98           | 1         | 0.46%   |
| MSI MS-7B38           | 1         | 0.46%   |
| MSI MS-7A33           | 1         | 0.46%   |
| MSI MS-7A15           | 1         | 0.46%   |
| MSI MS-7995           | 1         | 0.46%   |
| MSI MS-7817           | 1         | 0.46%   |
| MSI MS-7808           | 1         | 0.46%   |
| MSI MS-7721           | 1         | 0.46%   |
| MSI MS-7693           | 1         | 0.46%   |
| MSI MS-7309           | 1         | 0.46%   |
| MSI MS-7222           | 1         | 0.46%   |
| MSI GL65              | 1         | 0.46%   |
| MSI CR61              | 1         | 0.46%   |
| Medion V20            | 1         | 0.46%   |
| Lenovo V580c          | 1         | 0.46%   |
| Lenovo ThinkPad       | 1         | 0.46%   |
| Lenovo S40-70         | 1         | 0.46%   |
| Lenovo IdeaCentre     | 1         | 0.46%   |
| Lenovo H420           | 1         | 0.46%   |
| Lenovo B70-80         | 1         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 23        | 10.55%  |
| 2012 | 22        | 10.09%  |
| 2010 | 19        | 8.72%   |
| 2009 | 19        | 8.72%   |
| 2013 | 18        | 8.26%   |
| 2020 | 17        | 7.8%    |
| 2019 | 16        | 7.34%   |
| 2014 | 15        | 6.88%   |
| 2015 | 14        | 6.42%   |
| 2018 | 12        | 5.5%    |
| 2007 | 10        | 4.59%   |
| 2021 | 9         | 4.13%   |
| 2016 | 9         | 4.13%   |
| 2008 | 5         | 2.29%   |
| 2017 | 4         | 1.83%   |
| 2006 | 4         | 1.83%   |
| 2005 | 1         | 0.46%   |
| 2004 | 1         | 0.46%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 126       | 57.8%   |
| Notebook   | 87        | 39.91%  |
| All in one | 5         | 2.29%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 218       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 218       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 63        | 28.9%   |
| 8.01-16.0   | 48        | 22.02%  |
| 4.01-8.0    | 41        | 18.81%  |
| 1.01-2.0    | 25        | 11.47%  |
| 16.01-24.0  | 22        | 10.09%  |
| 2.01-3.0    | 7         | 3.21%   |
| 32.01-64.0  | 5         | 2.29%   |
| 0.51-1.0    | 5         | 2.29%   |
| 24.01-32.0  | 1         | 0.46%   |
| 64.01-256.0 | 1         | 0.46%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 104       | 47.71%  |
| 0.51-1.0 | 82        | 37.61%  |
| 2.01-3.0 | 17        | 7.8%    |
| 3.01-4.0 | 6         | 2.75%   |
| 4.01-8.0 | 5         | 2.29%   |
| 0.01-0.5 | 4         | 1.83%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 136       | 62.39%  |
| 2      | 51        | 23.39%  |
| 3      | 22        | 10.09%  |
| 4      | 6         | 2.75%   |
| 5      | 2         | 0.92%   |
| 0      | 1         | 0.46%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 111       | 50.92%  |
| No        | 107       | 49.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 213       | 97.71%  |
| No        | 5         | 2.29%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 126       | 57.8%   |
| No        | 92        | 42.2%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 138       | 63.3%   |
| Yes       | 80        | 36.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country    | Computers | Percent |
|------------|-----------|---------|
| Russia     | 159       | 72.94%  |
| Ukraine    | 14        | 6.42%   |
| Belarus    | 6         | 2.75%   |
| France     | 5         | 2.29%   |
| Brazil     | 5         | 2.29%   |
| Poland     | 4         | 1.83%   |
| Germany    | 4         | 1.83%   |
| USA        | 3         | 1.38%   |
| Kazakhstan | 3         | 1.38%   |
| UK         | 2         | 0.92%   |
| Hungary    | 2         | 0.92%   |
| Greece     | 2         | 0.92%   |
| Belgium    | 2         | 0.92%   |
| Serbia     | 1         | 0.46%   |
| Moldova    | 1         | 0.46%   |
| Mexico     | 1         | 0.46%   |
| India      | 1         | 0.46%   |
| Finland    | 1         | 0.46%   |
| Colombia   | 1         | 0.46%   |
| Austria    | 1         | 0.46%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 29        | 13.3%   |
| St Petersburg     | 13        | 5.96%   |
| Yekaterinburg     | 10        | 4.59%   |
| Nizhniy Novgorod  | 5         | 2.29%   |
| Kazan?ˆ™          | 5         | 2.29%   |
| Irkutsk           | 5         | 2.29%   |
| Samara            | 4         | 1.83%   |
| Minsk             | 4         | 1.83%   |
| Chelyabinsk       | 4         | 1.83%   |
| Perm              | 3         | 1.38%   |
| Paris             | 3         | 1.38%   |
| Novosibirsk       | 3         | 1.38%   |
| Kyiv              | 3         | 1.38%   |
| Krasnoyarsk       | 3         | 1.38%   |
| Krasnodar         | 3         | 1.38%   |
| Barnaul           | 3         | 1.38%   |
| Voronezh          | 2         | 0.92%   |
| Vladivostok       | 2         | 0.92%   |
| Veliky Novgorod   | 2         | 0.92%   |
| Taman'            | 2         | 0.92%   |
| Penza             | 2         | 0.92%   |
| Novoaltaysk       | 2         | 0.92%   |
| Miass             | 2         | 0.92%   |
| Cherepovets       | 2         | 0.92%   |
| Bryansk           | 2         | 0.92%   |
| Brussels          | 2         | 0.92%   |
| Yoshkar-Ola       | 1         | 0.46%   |
| Yaroslavl         | 1         | 0.46%   |
| Warsaw            | 1         | 0.46%   |
| Volgograd         | 1         | 0.46%   |
| Volgodonsk        | 1         | 0.46%   |
| Vienna            | 1         | 0.46%   |
| Ust-Kamenogorsk   | 1         | 0.46%   |
| Uruapan           | 1         | 0.46%   |
| Ulyanovsk         | 1         | 0.46%   |
| Ufa               | 1         | 0.46%   |
| Tyumen            | 1         | 0.46%   |
| Tver              | 1         | 0.46%   |
| Turkheim          | 1         | 0.46%   |
| Tula              | 1         | 0.46%   |
| Torzhok           | 1         | 0.46%   |
| Tiraspol          | 1         | 0.46%   |
| Terra Boa         | 1         | 0.46%   |
| Temirtau          | 1         | 0.46%   |
| Tal'menka         | 1         | 0.46%   |
| Taganrog          | 1         | 0.46%   |
| Szigetszentmarton | 1         | 0.46%   |
| Stuttgart         | 1         | 0.46%   |
| Stavropol         | 1         | 0.46%   |
| Staraya Yurga     | 1         | 0.46%   |
| Srednyaya Akhtuba | 1         | 0.46%   |
| Sosnowiec         | 1         | 0.46%   |
| Sochi             | 1         | 0.46%   |
| Simferopol        | 1         | 0.46%   |
| Shchelkovo        | 1         | 0.46%   |
| Sevastopol??™     | 1         | 0.46%   |
| Sevastopol        | 1         | 0.46%   |
| Serdobsk          | 1         | 0.46%   |
| Seleshchina       | 1         | 0.46%   |
| S??o Leopoldo     | 1         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives  | Percent |
|---------------------|-----------|---------|---------|
| WDC                 | 80        | 91      | 25.89%  |
| Seagate             | 48        | 51      | 15.53%  |
| Samsung Electronics | 26        | 28      | 8.41%   |
| Toshiba             | 23        | 27      | 7.44%   |
| Hitachi             | 22        | 22      | 7.12%   |
| Kingston            | 13        | 13      | 4.21%   |
| China               | 11        | 11      | 3.56%   |
| SanDisk             | 7         | 9       | 2.27%   |
| HGST                | 7         | 7       | 2.27%   |
| SPCC                | 5         | 5       | 1.62%   |
| GOODRAM             | 5         | 6       | 1.62%   |
| Unknown             | 4         | 5       | 1.29%   |
| OCZ                 | 4         | 4       | 1.29%   |
| MAXTOR              | 4         | 4       | 1.29%   |
| Intel               | 4         | 4       | 1.29%   |
| Apacer              | 4         | 4       | 1.29%   |
| A-DATA Technology   | 4         | 4       | 1.29%   |
| Transcend           | 2         | 2       | 0.65%   |
| Smartbuy            | 2         | 2       | 0.65%   |
| Silicon Motion      | 2         | 2       | 0.65%   |
| PLEXTOR             | 2         | 2       | 0.65%   |
| Micron Technology   | 2         | 2       | 0.65%   |
| KingSpec            | 2         | 2       | 0.65%   |
| KingDian            | 2         | 2       | 0.65%   |
| Intenso             | 2         | 3       | 0.65%   |
| Gigabyte Technology | 2         | 2       | 0.65%   |
| FOXLINE             | 2         | 2       | 0.65%   |
| Crucial             | 2         | 2       | 0.65%   |
| AMD                 | 2         | 2       | 0.65%   |
| XrayDisk            | 1         | 1       | 0.32%   |
| TMI                 | 1         | 1       | 0.32%   |
| Patriot             | 1         | 1       | 0.32%   |
| Mass                | 1         | Unknown | 0.32%   |
| Lexar               | 1         | 1       | 0.32%   |
| KingFast            | 1         | 1       | 0.32%   |
| JMicron             | 1         | 1       | 0.32%   |
| Hewlett-Packard     | 1         | 1       | 0.32%   |
| GeIL                | 1         | 1       | 0.32%   |
| FATTYDOVE           | 1         | 1       | 0.32%   |
| CHN25SATAS1         | 1         | 1       | 0.32%   |
| Apple               | 1         | 1       | 0.32%   |
| 2.5                 | 1         | 1       | 0.32%   |
| Unknown             | 1         | 1       | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba HDWD110 1TB                  | 5         | 1.52%   |
| Toshiba DT01ACA050 500GB             | 4         | 1.22%   |
| Seagate ST500DM002-1BD142 500GB      | 4         | 1.22%   |
| WDC WD20PURZ-85GU6Y0 2TB             | 3         | 0.91%   |
| Seagate ST2000DM008-2FR102 2TB       | 3         | 0.91%   |
| Seagate ST1000DM010-2EP102 1TB       | 3         | 0.91%   |
| SanDisk SDSSDA120G 120GB             | 3         | 0.91%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 0.91%   |
| HGST HTS545050A7E380 500GB           | 3         | 0.91%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.61%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 2         | 0.61%   |
| WDC WD2500BEVT-22A23T0 250GB         | 2         | 0.61%   |
| WDC WD10PURZ-85U8XY0 1TB             | 2         | 0.61%   |
| WDC WD10JPVX-75JC3T0 1TB             | 2         | 0.61%   |
| WDC WD10EZRX-00L4HB0 1TB             | 2         | 0.61%   |
| WDC WD10EZEX-21M2NA0 1TB             | 2         | 0.61%   |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 0.61%   |
| WDC WD10EZEX-00BN5A0 1TB             | 2         | 0.61%   |
| WDC WD10EADS-65M2B0 1TB              | 2         | 0.61%   |
| Toshiba MQ01ABF050 500GB             | 2         | 0.61%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.61%   |
| Toshiba HDWD105 500GB                | 2         | 0.61%   |
| SPCC Solid State Disk 256GB          | 2         | 0.61%   |
| Seagate ST9500325AS 500GB            | 2         | 0.61%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 0.61%   |
| Seagate ST380815AS 80GB              | 2         | 0.61%   |
| Seagate ST380011A 34GB               | 2         | 0.61%   |
| Seagate ST3160811AS 160GB            | 2         | 0.61%   |
| Samsung SSD 860 EVO 500GB            | 2         | 0.61%   |
| Samsung SSD 860 EVO 250GB            | 2         | 0.61%   |
| Samsung SSD 750 EVO 250GB            | 2         | 0.61%   |
| Samsung HD502HJ 500GB                | 2         | 0.61%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 0.61%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 0.61%   |
| Hitachi HTS547564A9E384 640GB        | 2         | 0.61%   |
| Hitachi HDS721050CLA360 500GB        | 2         | 0.61%   |
| GOODRAM SSDPR-CL100-120-G3 120GB     | 2         | 0.61%   |
| Gigabyte GP-GSTFS31240GNTD 240GB SSD | 2         | 0.61%   |
| Apacer AS350 256GB SSD               | 2         | 0.61%   |
| XrayDisk SSD 256GB                   | 1         | 0.3%    |
| WDC WDS250G2B0A-00SM50 250GB SSD     | 1         | 0.3%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 0.3%    |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.3%    |
| WDC WD800JD-23LSA0 80GB              | 1         | 0.3%    |
| WDC WD800JD-08MSA1 80GB              | 1         | 0.3%    |
| WDC WD800JD-00LSA5 80GB              | 1         | 0.3%    |
| WDC WD800JD-00LSA0 80GB              | 1         | 0.3%    |
| WDC WD7500BPVT-26HXZT3 752GB         | 1         | 0.3%    |
| WDC WD60EFRX-68MYMN1 6TB             | 1         | 0.3%    |
| WDC WD60EFRX-68L0BN1 6TB             | 1         | 0.3%    |
| WDC WD5003AZEX-00MK2A0 500GB         | 1         | 0.3%    |
| WDC WD5003ABYZ-011FA0 500GB          | 1         | 0.3%    |
| WDC WD5002ABYS-01B1B0 500GB          | 1         | 0.3%    |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.3%    |
| WDC WD5000LPVX-00V0TT0 500GB         | 1         | 0.3%    |
| WDC WD5000LPLX-00ZNTT0 500GB         | 1         | 0.3%    |
| WDC WD5000LPCX-21VHAT0 4X5.8GB       | 1         | 0.3%    |
| WDC WD5000LPCX-00VHAT0 500GB         | 1         | 0.3%    |
| WDC WD5000BEVT-22A0RT0 500GB         | 1         | 0.3%    |
| WDC WD5000AZRX-00A8LB0 500GB         | 1         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 72        | 82     | 38.1%   |
| Seagate             | 48        | 51     | 25.4%   |
| Toshiba             | 23        | 26     | 12.17%  |
| Hitachi             | 22        | 22     | 11.64%  |
| Samsung Electronics | 12        | 13     | 6.35%   |
| HGST                | 7         | 7      | 3.7%    |
| MAXTOR              | 4         | 4      | 2.12%   |
| JMicron             | 1         | 1      | 0.53%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 11        | 11     | 11.22%  |
| China               | 11        | 11     | 11.22%  |
| Samsung Electronics | 8         | 9      | 8.16%   |
| SanDisk             | 7         | 9      | 7.14%   |
| WDC                 | 5         | 5      | 5.1%    |
| SPCC                | 5         | 5      | 5.1%    |
| GOODRAM             | 5         | 6      | 5.1%    |
| OCZ                 | 4         | 4      | 4.08%   |
| Apacer              | 4         | 4      | 4.08%   |
| Intel               | 3         | 3      | 3.06%   |
| Transcend           | 2         | 2      | 2.04%   |
| PLEXTOR             | 2         | 2      | 2.04%   |
| KingSpec            | 2         | 2      | 2.04%   |
| KingDian            | 2         | 2      | 2.04%   |
| Intenso             | 2         | 3      | 2.04%   |
| Gigabyte Technology | 2         | 2      | 2.04%   |
| FOXLINE             | 2         | 2      | 2.04%   |
| Crucial             | 2         | 2      | 2.04%   |
| AMD                 | 2         | 2      | 2.04%   |
| A-DATA Technology   | 2         | 2      | 2.04%   |
| XrayDisk            | 1         | 1      | 1.02%   |
| Toshiba             | 1         | 1      | 1.02%   |
| TMI                 | 1         | 1      | 1.02%   |
| Smartbuy            | 1         | 1      | 1.02%   |
| Patriot             | 1         | 1      | 1.02%   |
| Micron Technology   | 1         | 1      | 1.02%   |
| Lexar               | 1         | 1      | 1.02%   |
| KingFast            | 1         | 1      | 1.02%   |
| Hewlett-Packard     | 1         | 1      | 1.02%   |
| GeIL                | 1         | 1      | 1.02%   |
| FATTYDOVE           | 1         | 1      | 1.02%   |
| CHN25SATAS1         | 1         | 1      | 1.02%   |
| Apple               | 1         | 1      | 1.02%   |
| 2.5                 | 1         | 1      | 1.02%   |
| Unknown             | 1         | 1      | 1.02%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives  | Percent |
|---------|-----------|---------|---------|
| HDD     | 164       | 206     | 60.07%  |
| SSD     | 87        | 103     | 31.87%  |
| NVMe    | 17        | 19      | 6.23%   |
| MMC     | 4         | 5       | 1.47%   |
| Unknown | 1         | Unknown | 0.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 209       | 306    | 89.32%  |
| NVMe | 17        | 19     | 7.26%   |
| SAS  | 4         | 3      | 1.71%   |
| MMC  | 4         | 5      | 1.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 178       | 222    | 69.53%  |
| 0.51-1.0   | 59        | 65     | 23.05%  |
| 1.01-2.0   | 13        | 14     | 5.08%   |
| 2.01-3.0   | 3         | 3      | 1.17%   |
| 4.01-10.0  | 2         | 4      | 0.78%   |
| 3.01-4.0   | 1         | 1      | 0.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 64        | 29.36%  |
| 251-500        | 38        | 17.43%  |
| 1-20           | 32        | 14.68%  |
| 501-1000       | 24        | 11.01%  |
| 51-100         | 24        | 11.01%  |
| 21-50          | 15        | 6.88%   |
| 1001-2000      | 14        | 6.42%   |
| 2001-3000      | 4         | 1.83%   |
| More than 3000 | 3         | 1.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 151       | 69.27%  |
| 101-250        | 15        | 6.88%   |
| 21-50          | 14        | 6.42%   |
| 51-100         | 13        | 5.96%   |
| 251-500        | 8         | 3.67%   |
| 1001-2000      | 7         | 3.21%   |
| 501-1000       | 7         | 3.21%   |
| More than 3000 | 2         | 0.92%   |
| 2001-3000      | 1         | 0.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Toshiba DT01ACA050 500GB          | 3         | 4      | 3.3%    |
| WDC WD5000LPCX-24C6HT0 500GB      | 2         | 2      | 2.2%    |
| WDC WD10EADS-65M2B0 1TB           | 2         | 2      | 2.2%    |
| Seagate ST500DM002-1BD142 500GB   | 2         | 2      | 2.2%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD  | 1         | 1      | 1.1%    |
| WDC WD800JD-23LSA0 80GB           | 1         | 1      | 1.1%    |
| WDC WD800JD-00LSA0 80GB           | 1         | 1      | 1.1%    |
| WDC WD7500BPVT-26HXZT3 752GB      | 1         | 1      | 1.1%    |
| WDC WD5000BEVT-22A0RT0 500GB      | 1         | 1      | 1.1%    |
| WDC WD5000AZLX-22JKKA0 500GB      | 1         | 1      | 1.1%    |
| WDC WD5000AAKX-60U6AA0 500GB      | 1         | 1      | 1.1%    |
| WDC WD5000AAKX-083CA1 500GB       | 1         | 1      | 1.1%    |
| WDC WD3200BPVT-24ZEST0 320GB      | 1         | 1      | 1.1%    |
| WDC WD3200BEKT-75PVMT1 320GB      | 1         | 1      | 1.1%    |
| WDC WD30EZRX-00MMMB0 3TB          | 1         | 1      | 1.1%    |
| WDC WD2500KS-00MJB0 250GB         | 1         | 1      | 1.1%    |
| WDC WD2500JS-00NCB1 250GB         | 1         | 1      | 1.1%    |
| WDC WD2500BEVT-22A23T0 250GB      | 1         | 1      | 1.1%    |
| WDC WD20PURZ-85GU6Y0 2TB          | 1         | 1      | 1.1%    |
| WDC WD20EARS-00MVWB0 2TB          | 1         | 1      | 1.1%    |
| WDC WD1600BEVT-22ZCT0 160GB       | 1         | 1      | 1.1%    |
| WDC WD1600BEKT-60A25T1 160GB      | 1         | 1      | 1.1%    |
| WDC WD15EARS-00Z5B1 1TB           | 1         | 1      | 1.1%    |
| WDC WD10SPCX-60HWST0 1TB          | 1         | 1      | 1.1%    |
| WDC WD10JPVT-08A1YT2 1TB          | 1         | 1      | 1.1%    |
| WDC WD10EZEX-00RKKA0 1TB          | 1         | 1      | 1.1%    |
| WDC WD10EADS-00L5B1 1TB           | 1         | 1      | 1.1%    |
| Toshiba MK6476GSX 640GB           | 1         | 1      | 1.1%    |
| Toshiba MK3276GSX 320GB           | 1         | 1      | 1.1%    |
| Toshiba MK3265GSX 320GB           | 1         | 1      | 1.1%    |
| Toshiba MK2552GSX 250GB           | 1         | 1      | 1.1%    |
| Toshiba MK2002TSKB 2TB            | 1         | 1      | 1.1%    |
| Toshiba DT01ACA100 1TB            | 1         | 1      | 1.1%    |
| Seagate ST9500325AS 500GB         | 1         | 1      | 1.1%    |
| Seagate ST9320325AS 320GB         | 1         | 1      | 1.1%    |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 1.1%    |
| Seagate ST500LM021-1KJ152 500GB   | 1         | 1      | 1.1%    |
| Seagate ST380815AS 80GB           | 1         | 1      | 1.1%    |
| Seagate ST380011A 34GB            | 1         | 1      | 1.1%    |
| Seagate ST3750640AS 752GB         | 1         | 1      | 1.1%    |
| Seagate ST3500418AS 500GB         | 1         | 1      | 1.1%    |
| Seagate ST3360320AS 360GB         | 1         | 1      | 1.1%    |
| Seagate ST3250312AS 250GB         | 1         | 1      | 1.1%    |
| Seagate ST3250310AS 250GB         | 1         | 1      | 1.1%    |
| Seagate ST3160811AS 160GB         | 1         | 1      | 1.1%    |
| Seagate ST3160215A 160GB          | 1         | 1      | 1.1%    |
| Seagate ST3120827AS 120GB         | 1         | 1      | 1.1%    |
| Seagate ST31000340AS 1TB          | 1         | 1      | 1.1%    |
| Seagate ST3000DM008-2DM166 3TB    | 1         | 1      | 1.1%    |
| Seagate ST3000DM001-1CH166 3TB    | 1         | 1      | 1.1%    |
| Seagate ST1000LM048-2E7172 1TB    | 1         | 1      | 1.1%    |
| Seagate ST1000DM010-2EP102 1TB    | 1         | 1      | 1.1%    |
| Samsung Electronics SP2504C 250GB | 1         | 1      | 1.1%    |
| Samsung Electronics SP2004C 200GB | 1         | 1      | 1.1%    |
| Samsung Electronics HM160HI 160GB | 1         | 1      | 1.1%    |
| Samsung Electronics HD503HI 500GB | 1         | 1      | 1.1%    |
| Samsung Electronics HD502IJ 500GB | 1         | 1      | 1.1%    |
| Samsung Electronics HD502HI 500GB | 1         | 2      | 1.1%    |
| Samsung Electronics HD154UI 1TB   | 1         | 1      | 1.1%    |
| Samsung Electronics HD103SI 1TB   | 1         | 1      | 1.1%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 27        | 27     | 29.67%  |
| Seagate             | 21        | 21     | 23.08%  |
| Hitachi             | 10        | 10     | 10.99%  |
| Toshiba             | 9         | 10     | 9.89%   |
| Samsung Electronics | 8         | 9      | 8.79%   |
| HGST                | 4         | 4      | 4.4%    |
| MAXTOR              | 3         | 3      | 3.3%    |
| OCZ                 | 2         | 2      | 2.2%    |
| Kingston            | 1         | 1      | 1.1%    |
| KingSpec            | 1         | 1      | 1.1%    |
| Intel               | 1         | 1      | 1.1%    |
| China               | 1         | 1      | 1.1%    |
| Apple               | 1         | 1      | 1.1%    |
| AMD                 | 1         | 1      | 1.1%    |
| A-DATA Technology   | 1         | 1      | 1.1%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 26     | 32.1%   |
| Seagate             | 21        | 21     | 25.93%  |
| Hitachi             | 10        | 10     | 12.35%  |
| Toshiba             | 9         | 10     | 11.11%  |
| Samsung Electronics | 8         | 9      | 9.88%   |
| HGST                | 4         | 4      | 4.94%   |
| MAXTOR              | 3         | 3      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 74        | 83     | 88.1%   |
| SSD  | 9         | 9      | 10.71%  |
| NVMe | 1         | 1      | 1.19%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)

![Failed Drives](./All/images/line_chart/drive_failed.svg)

| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD3200AAJS-00L7A0 320GB | 1         | 1      | 25%     |
| Seagate ST9500325AS 500GB   | 1         | 1      | 25%     |
| Seagate ST9320423AS 320GB   | 1         | 1      | 25%     |
| Seagate ST3320613AS 320GB   | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)

![Failed Drive Vendor](./All/images/line_chart/drive_failed_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 75%     |
| WDC     | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)

![Drive Status](./All/images/line_chart/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 159       | 228    | 63.1%   |
| Malfunc  | 81        | 93     | 32.14%  |
| Detected | 8         | 8      | 3.17%   |
| Failed   | 4         | 4      | 1.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 155       | 62.25%  |
| AMD                         | 48        | 19.28%  |
| Nvidia                      | 12        | 4.82%   |
| JMicron Technology          | 7         | 2.81%   |
| Samsung Electronics         | 6         | 2.41%   |
| Sandisk                     | 4         | 1.61%   |
| VIA Technologies            | 3         | 1.2%    |
| ASMedia Technology          | 3         | 1.2%    |
| Silicon Motion              | 2         | 0.8%    |
| Phison Electronics          | 2         | 0.8%    |
| Marvell Technology Group    | 2         | 0.8%    |
| ADATA Technology            | 2         | 0.8%    |
| Silicon Image               | 1         | 0.4%    |
| Micron Technology           | 1         | 0.4%    |
| Kingston Technology Company | 1         | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 26        | 8.13%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 20        | 6.25%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 19        | 5.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11        | 3.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11        | 3.44%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 11        | 3.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 10        | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 10        | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9         | 2.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8         | 2.5%    |
| Nvidia MCP61 SATA Controller                                                            | 7         | 2.19%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 7         | 2.19%   |
| Nvidia MCP61 IDE                                                                        | 6         | 1.88%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5         | 1.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 5         | 1.56%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 5         | 1.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 1.56%   |
| AMD FCH SATA Controller D                                                               | 5         | 1.56%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 4         | 1.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 1.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 1.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 1.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 0.94%   |
| Samsung NVMe SSD Controller 980                                                         | 3         | 0.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 0.94%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 0.94%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3         | 0.94%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3         | 0.94%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 3         | 0.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 0.94%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3         | 0.94%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3         | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 0.94%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 0.94%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3         | 0.94%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2         | 0.63%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 2         | 0.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2         | 0.63%   |
| Nvidia MCP79 AHCI Controller                                                            | 2         | 0.63%   |
| JMicron JMB368 IDE controller                                                           | 2         | 0.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 0.63%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2         | 0.63%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 0.63%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2         | 0.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 0.63%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 0.63%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2         | 0.63%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 0.63%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 2         | 0.63%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 2         | 0.63%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 2         | 0.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 0.63%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2         | 0.63%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 2         | 0.63%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 0.63%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2         | 0.63%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1         | 0.31%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1         | 0.31%   |
| Phison E7 NVMe Controller                                                               | 1         | 0.31%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 161       | 62.4%   |
| IDE  | 74        | 28.68%  |
| NVMe | 17        | 6.59%   |
| RAID | 6         | 2.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 161       | 73.85%  |
| AMD    | 57        | 26.15%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz                 | 4         | 1.83%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 3         | 1.38%   |
| Intel Pentium 4 CPU 3.00GHz                   | 3         | 1.38%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 1.38%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 1.38%   |
| AMD Athlon II X2 240 Processor                | 3         | 1.38%   |
| Intel Xeon CPU E5450 @ 3.00GHz                | 2         | 0.92%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 2         | 0.92%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 2         | 0.92%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 2         | 0.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.92%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.92%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.92%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.92%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 0.92%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.92%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.92%   |
| Intel Core i5-2500 CPU @ 3.30GHz              | 2         | 0.92%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 2         | 0.92%   |
| Intel Core i3-2348M CPU @ 2.30GHz             | 2         | 0.92%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 2         | 0.92%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz          | 2         | 0.92%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 0.92%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 2         | 0.92%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz          | 2         | 0.92%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 2         | 0.92%   |
| AMD V120 Processor                            | 2         | 0.92%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 0.92%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 2         | 0.92%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 2         | 0.92%   |
| AMD Phenom 8650 Triple-Core Processor         | 2         | 0.92%   |
| AMD FX-6300 Six-Core Processor                | 2         | 0.92%   |
| AMD Athlon Gold 3150U with Radeon Graphics    | 2         | 0.92%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 2         | 0.92%   |
| Intel Xeon CPU X3450 @ 2.67GHz                | 1         | 0.46%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1         | 0.46%   |
| Intel Xeon CPU E5-2640 v3 @ 2.60GHz           | 1         | 0.46%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz           | 1         | 0.46%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz            | 1         | 0.46%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz           | 1         | 0.46%   |
| Intel Pentium Silver J5040 CPU @ 2.00GHz      | 1         | 0.46%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz      | 1         | 0.46%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.46%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.46%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz   | 1         | 0.46%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 1         | 0.46%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz   | 1         | 0.46%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 1         | 0.46%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 1         | 0.46%   |
| Intel Pentium D CPU 3.40GHz                   | 1         | 0.46%   |
| Intel Pentium D CPU 3.00GHz                   | 1         | 0.46%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.46%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.46%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 0.46%   |
| Intel Pentium CPU G840 @ 2.80GHz              | 1         | 0.46%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 1         | 0.46%   |
| Intel Pentium CPU G3430 @ 3.30GHz             | 1         | 0.46%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 1         | 0.46%   |
| Intel Pentium CPU G3220 @ 3.00GHz             | 1         | 0.46%   |
| Intel Pentium CPU G2130 @ 3.20GHz             | 1         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 35        | 16.06%  |
| Intel Core i3           | 22        | 10.09%  |
| Intel Core 2 Duo        | 18        | 8.26%   |
| Intel Pentium           | 14        | 6.42%   |
| Intel Celeron           | 14        | 6.42%   |
| Intel Atom              | 11        | 5.05%   |
| Intel Xeon              | 10        | 4.59%   |
| Intel Pentium Dual-Core | 9         | 4.13%   |
| Intel Core i7           | 8         | 3.67%   |
| AMD Ryzen 5             | 8         | 3.67%   |
| AMD Athlon II X2        | 6         | 2.75%   |
| AMD FX                  | 5         | 2.29%   |
| Intel Pentium 4         | 4         | 1.83%   |
| Intel Core 2            | 4         | 1.83%   |
| AMD A8                  | 4         | 1.83%   |
| Intel Core 2 Quad       | 3         | 1.38%   |
| AMD Ryzen 7             | 3         | 1.38%   |
| AMD Ryzen 3             | 3         | 1.38%   |
| AMD A6                  | 3         | 1.38%   |
| Intel Pentium Silver    | 2         | 0.92%   |
| Intel Pentium D         | 2         | 0.92%   |
| Intel Genuine           | 2         | 0.92%   |
| AMD V120                | 2         | 0.92%   |
| AMD Phenom II X4        | 2         | 0.92%   |
| AMD Phenom              | 2         | 0.92%   |
| AMD Athlon II X4        | 2         | 0.92%   |
| AMD Athlon 64 X2        | 2         | 0.92%   |
| AMD Athlon              | 2         | 0.92%   |
| AMD A10                 | 2         | 0.92%   |
| Other                   | 1         | 0.46%   |
| Intel Pentium Dual      | 1         | 0.46%   |
| Intel Celeron Dual-Core | 1         | 0.46%   |
| AMD Turion II Dual-Core | 1         | 0.46%   |
| AMD Sempron X2          | 1         | 0.46%   |
| AMD Ryzen 5 PRO         | 1         | 0.46%   |
| AMD Phenom II X3        | 1         | 0.46%   |
| AMD E2                  | 1         | 0.46%   |
| AMD E1                  | 1         | 0.46%   |
| AMD E                   | 1         | 0.46%   |
| AMD C-60                | 1         | 0.46%   |
| AMD Athlon X4           | 1         | 0.46%   |
| AMD Athlon II Dual-Core | 1         | 0.46%   |
| AMD A4                  | 1         | 0.46%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 120       | 55.05%  |
| 4      | 51        | 23.39%  |
| 1      | 20        | 9.17%   |
| 6      | 15        | 6.88%   |
| 3      | 6         | 2.75%   |
| 8      | 5         | 2.29%   |
| 24     | 1         | 0.46%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 217       | 99.54%  |
| 2      | 1         | 0.46%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 120       | 55.05%  |
| 2      | 98        | 44.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 211       | 96.79%  |
| 32-bit         | 7         | 3.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 23        | 10.55%  |
| 0x1067a    | 22        | 10.09%  |
| 0x306a9    | 16        | 7.34%   |
| 0x306c3    | 11        | 5.05%   |
| 0x010000c8 | 9         | 4.13%   |
| Unknown    | 9         | 4.13%   |
| 0x6fd      | 8         | 3.67%   |
| 0x106ca    | 6         | 2.75%   |
| 0x306d4    | 5         | 2.29%   |
| 0x06001119 | 5         | 2.29%   |
| 0x40651    | 4         | 1.83%   |
| 0x106c2    | 4         | 1.83%   |
| 0x10676    | 4         | 1.83%   |
| 0x08701021 | 4         | 1.83%   |
| 0x08108109 | 4         | 1.83%   |
| 0x06000852 | 4         | 1.83%   |
| 0x906ed    | 3         | 1.38%   |
| 0x906eb    | 3         | 1.38%   |
| 0x906ea    | 3         | 1.38%   |
| 0x306f2    | 3         | 1.38%   |
| 0x010000db | 3         | 1.38%   |
| 0x906e9    | 2         | 0.92%   |
| 0x806e9    | 2         | 0.92%   |
| 0x706a8    | 2         | 0.92%   |
| 0x6fb      | 2         | 0.92%   |
| 0x6f6      | 2         | 0.92%   |
| 0x6f2      | 2         | 0.92%   |
| 0x506e3    | 2         | 0.92%   |
| 0x406e3    | 2         | 0.92%   |
| 0x206d7    | 2         | 0.92%   |
| 0x0810100b | 2         | 0.92%   |
| 0x0800820d | 2         | 0.92%   |
| 0x0600611a | 2         | 0.92%   |
| 0x06003106 | 2         | 0.92%   |
| 0x05000119 | 2         | 0.92%   |
| 0xf64      | 1         | 0.46%   |
| 0xf62      | 1         | 0.46%   |
| 0xf4a      | 1         | 0.46%   |
| 0xf49      | 1         | 0.46%   |
| 0xf43      | 1         | 0.46%   |
| 0xf41      | 1         | 0.46%   |
| 0xf29      | 1         | 0.46%   |
| 0xa0671    | 1         | 0.46%   |
| 0xa0654    | 1         | 0.46%   |
| 0xa0653    | 1         | 0.46%   |
| 0x906ec    | 1         | 0.46%   |
| 0x806ec    | 1         | 0.46%   |
| 0x706e5    | 1         | 0.46%   |
| 0x706a1    | 1         | 0.46%   |
| 0x6e8      | 1         | 0.46%   |
| 0x406c4    | 1         | 0.46%   |
| 0x406c3    | 1         | 0.46%   |
| 0x306e4    | 1         | 0.46%   |
| 0x30678    | 1         | 0.46%   |
| 0x30673    | 1         | 0.46%   |
| 0x30661    | 1         | 0.46%   |
| 0x20655    | 1         | 0.46%   |
| 0x106e5    | 1         | 0.46%   |
| 0x106a5    | 1         | 0.46%   |
| 0x10677    | 1         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| Penryn        | 27        | 12.39%  |
| SandyBridge   | 25        | 11.47%  |
| Haswell       | 20        | 9.17%   |
| K10           | 18        | 8.26%   |
| IvyBridge     | 17        | 7.8%    |
| KabyLake      | 15        | 6.88%   |
| Core          | 14        | 6.42%   |
| Bonnell       | 11        | 5.05%   |
| Piledriver    | 9         | 4.13%   |
| NetBurst      | 7         | 3.21%   |
| Zen+          | 6         | 2.75%   |
| Zen           | 6         | 2.75%   |
| Zen 2         | 5         | 2.29%   |
| Broadwell     | 5         | 2.29%   |
| Skylake       | 4         | 1.83%   |
| Silvermont    | 4         | 1.83%   |
| Bobcat        | 4         | 1.83%   |
| Goldmont plus | 3         | 1.38%   |
| Excavator     | 3         | 1.38%   |
| Steamroller   | 2         | 0.92%   |
| Nehalem       | 2         | 0.92%   |
| K8 Hammer     | 2         | 0.92%   |
| CometLake     | 2         | 0.92%   |
| Westmere      | 1         | 0.46%   |
| Puma          | 1         | 0.46%   |
| P6            | 1         | 0.46%   |
| IceLake       | 1         | 0.46%   |
| Goldmont      | 1         | 0.46%   |
| Bulldozer     | 1         | 0.46%   |
| Unknown       | 1         | 0.46%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Nvidia           | 99        | 39.13%  |
| Intel            | 98        | 38.74%  |
| AMD              | 55        | 21.74%  |
| VIA Technologies | 1         | 0.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 18        | 6.82%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 3.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 2.65%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 2.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 2.27%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4         | 1.52%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 4         | 1.52%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4         | 1.52%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 1.52%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 4         | 1.52%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 1.52%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 1.52%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.52%   |
| AMD Picasso                                                                              | 4         | 1.52%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 3         | 1.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.14%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 1.14%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.14%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.14%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 1.14%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.14%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 1.14%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 3         | 1.14%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.76%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.76%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.76%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 2         | 0.76%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2         | 0.76%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.76%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2         | 0.76%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 2         | 0.76%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 2         | 0.76%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 2         | 0.76%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 2         | 0.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.76%   |
| Intel HD Graphics 630                                                                    | 2         | 0.76%   |
| Intel HD Graphics 620                                                                    | 2         | 0.76%   |
| Intel HD Graphics                                                                        | 2         | 0.76%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.76%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 0.76%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 0.76%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.76%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.76%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.76%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 2         | 0.76%   |
| AMD RV370 [Radeon X300]                                                                  | 2         | 0.76%   |
| AMD RV370 [Radeon X300 SE]                                                               | 2         | 0.76%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                                | 2         | 0.76%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 0.76%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro]            | 1         | 0.38%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 0.38%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.38%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1         | 0.38%   |
| Nvidia NV44A [GeForce 6200]                                                              | 1         | 0.38%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Nvidia     | 70        | 32.11%  |
| 1 x Intel      | 66        | 30.28%  |
| 1 x AMD        | 43        | 19.72%  |
| Intel + Nvidia | 26        | 11.93%  |
| 2 x AMD        | 5         | 2.29%   |
| Intel + AMD    | 4         | 1.83%   |
| AMD + Nvidia   | 2         | 0.92%   |
| 2 x Nvidia     | 1         | 0.46%   |
| 1 x VIA        | 1         | 0.46%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 194       | 88.99%  |
| Proprietary | 20        | 9.17%   |
| Unknown     | 4         | 1.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 32.11%  |
| 0.51-1.0   | 47        | 21.56%  |
| 1.01-2.0   | 43        | 19.72%  |
| 0.01-0.5   | 40        | 18.35%  |
| 3.01-4.0   | 10        | 4.59%   |
| 7.01-8.0   | 5         | 2.29%   |
| 2.01-3.0   | 2         | 0.92%   |
| 5.01-6.0   | 1         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 51        | 24.29%  |
| Acer                    | 18        | 8.57%   |
| AU Optronics            | 17        | 8.1%    |
| LG Display              | 14        | 6.67%   |
| BenQ                    | 12        | 5.71%   |
| Goldstar                | 9         | 4.29%   |
| Philips                 | 7         | 3.33%   |
| Dell                    | 7         | 3.33%   |
| Chimei Innolux          | 7         | 3.33%   |
| Ancor Communications    | 7         | 3.33%   |
| ViewSonic               | 6         | 2.86%   |
| Chi Mei Optoelectronics | 6         | 2.86%   |
| BOE                     | 5         | 2.38%   |
| Hewlett-Packard         | 4         | 1.9%    |
| Sony                    | 3         | 1.43%   |
| Iiyama                  | 3         | 1.43%   |
| HannStar                | 3         | 1.43%   |
| GDH                     | 3         | 1.43%   |
| Apple                   | 3         | 1.43%   |
| PANDA                   | 2         | 0.95%   |
| Lenovo                  | 2         | 0.95%   |
| AOC                     | 2         | 0.95%   |
| XSP                     | 1         | 0.48%   |
| TR_                     | 1         | 0.48%   |
| Toshiba                 | 1         | 0.48%   |
| SLD                     | 1         | 0.48%   |
| RTK                     | 1         | 0.48%   |
| NEC Computers           | 1         | 0.48%   |
| MStar                   | 1         | 0.48%   |
| MSI                     | 1         | 0.48%   |
| MiTAC                   | 1         | 0.48%   |
| Mi                      | 1         | 0.48%   |
| LG Philips              | 1         | 0.48%   |
| InfoVision              | 1         | 0.48%   |
| HKC                     | 1         | 0.48%   |
| Haier                   | 1         | 0.48%   |
| eMachines               | 1         | 0.48%   |
| ECS                     | 1         | 0.48%   |
| DRD                     | 1         | 0.48%   |
| CPT                     | 1         | 0.48%   |
| ASUSTek Computer        | 1         | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch     | 3         | 1.42%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 3         | 1.42%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 3         | 1.42%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch    | 3         | 1.42%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch     | 2         | 0.95%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 2         | 0.95%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.95%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 0.95%   |
| GDH Smart TV GDH0030 3840x2160 708x398mm 32.0-inch                       | 2         | 0.95%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 2         | 0.95%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch            | 2         | 0.95%   |
| Acer AL1717 A ACRAD46 1280x1024 338x270mm 17.0-inch                      | 2         | 0.95%   |
| XSP Digital XSP2380 1920x1080 520x310mm 23.8-inch                        | 1         | 0.47%   |
| ViewSonic VP191s VSCB916 1280x1024 376x301mm 19.0-inch                   | 1         | 0.47%   |
| ViewSonic VA2445 SERIES VSC712E 1920x1080 521x293mm 23.5-inch            | 1         | 0.47%   |
| ViewSonic VA2419 Series VSC7B32 1920x1080 527x296mm 23.8-inch            | 1         | 0.47%   |
| ViewSonic VA2261 VSC0F30 1920x1080 477x268mm 21.5-inch                   | 1         | 0.47%   |
| ViewSonic VA2016w-2 VSC2820 1680x1050 433x271mm 20.1-inch                | 1         | 0.47%   |
| ViewSonic VA1913 series VSC1A22 1366x768 410x230mm 18.5-inch             | 1         | 0.47%   |
| TR_ LCD Monitor TR_5511 1920x1080 519x324mm 24.1-inch                    | 1         | 0.47%   |
| Toshiba TV TSB010B 1920x1080 1600x900mm 72.3-inch                        | 1         | 0.47%   |
| Sony TV SNYEE01 1920x1080 1600x900mm 72.3-inch                           | 1         | 0.47%   |
| Sony TV SNYC901 1920x1080 1600x900mm 72.3-inch                           | 1         | 0.47%   |
| Sony TV SNY4201 1360x768 710x400mm 32.1-inch                             | 1         | 0.47%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                     | 1         | 0.47%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch        | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0609 1920x1080 510x290mm 23.1-inch     | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0594 1680x1050 459x296mm 21.5-inch     | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 477x268mm 21.5-inch     | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0499 1600x900 443x249mm 20.0-inch      | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0482 1680x1050 433x271mm 20.1-inch     | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 474x296mm 22.0-inch     | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0352 1680x1050 459x296mm 21.5-inch     | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0287 1680x1050 474x296mm 22.0-inch     | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch      | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM026F 1280x1024 376x301mm 19.0-inch     | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0254 1680x1050 474x296mm 22.0-inch     | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch     | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0043 1024x768 312x234mm 15.4-inch      | 1         | 0.47%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch       | 1         | 0.47%   |
| Samsung Electronics SME2320 SAM06B2 1920x1080 510x287mm 23.0-inch        | 1         | 0.47%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 376x301mm 19.0-inch      | 1         | 0.47%   |
| Samsung Electronics SA300/SA350 SAM0791 1920x1080 510x287mm 23.0-inch    | 1         | 0.47%   |
| Samsung Electronics S27R35x SAM1054 1920x1080 598x336mm 27.0-inch        | 1         | 0.47%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch        | 1         | 0.47%   |
| Samsung Electronics S24C350 SAM0A37 1920x1080 521x293mm 23.5-inch        | 1         | 0.47%   |
| Samsung Electronics S23A750D SAM0796 1920x1080 509x286mm 23.0-inch       | 1         | 0.47%   |
| Samsung Electronics S22E391 SAM0C0D 1920x1080 477x268mm 21.5-inch        | 1         | 0.47%   |
| Samsung Electronics S22C570 SAM0A55 1920x1080 480x270mm 21.7-inch        | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4754 1280x800 261x163mm 12.1-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 303x190mm 14.1-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 344x194mm 15.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3454 1600x900 382x215mm 17.3-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3342 1024x600 223x125mm 10.1-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 79        | 37.98%  |
| 1366x768 (WXGA)    | 51        | 24.52%  |
| 1280x1024 (SXGA)   | 15        | 7.21%   |
| 1600x900 (HD+)     | 14        | 6.73%   |
| 1024x600           | 10        | 4.81%   |
| 1680x1050 (WSXGA+) | 9         | 4.33%   |
| 1440x900 (WXGA+)   | 7         | 3.37%   |
| 3840x2160 (4K)     | 4         | 1.92%   |
| 2560x1440 (QHD)    | 4         | 1.92%   |
| 1920x1200 (WUXGA)  | 4         | 1.92%   |
| 1280x800 (WXGA)    | 4         | 1.92%   |
| 1600x1200          | 2         | 0.96%   |
| 1360x768           | 2         | 0.96%   |
| 1024x768 (XGA)     | 2         | 0.96%   |
| 1920x540           | 1         | 0.48%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 55        | 26.19%  |
| 23     | 25        | 11.9%   |
| 21     | 23        | 10.95%  |
| 17     | 15        | 7.14%   |
| 19     | 14        | 6.67%   |
| 24     | 13        | 6.19%   |
| 27     | 9         | 4.29%   |
| 10     | 9         | 4.29%   |
| 20     | 7         | 3.33%   |
| 13     | 7         | 3.33%   |
| 18     | 5         | 2.38%   |
| 32     | 4         | 1.9%    |
| 22     | 4         | 1.9%    |
| 72     | 3         | 1.43%   |
| 14     | 3         | 1.43%   |
| 54     | 2         | 0.95%   |
| 52     | 2         | 0.95%   |
| 31     | 2         | 0.95%   |
| 11     | 2         | 0.95%   |
| 46     | 1         | 0.48%   |
| 40     | 1         | 0.48%   |
| 33     | 1         | 0.48%   |
| 25     | 1         | 0.48%   |
| 16     | 1         | 0.48%   |
| 8      | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 68        | 32.38%  |
| 501-600     | 47        | 22.38%  |
| 401-500     | 46        | 21.9%   |
| 351-400     | 16        | 7.62%   |
| 201-300     | 15        | 7.14%   |
| 701-800     | 5         | 2.38%   |
| 1001-1500   | 5         | 2.38%   |
| 601-700     | 3         | 1.43%   |
| 1501-2000   | 3         | 1.43%   |
| 801-900     | 1         | 0.48%   |
| 101-200     | 1         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 160       | 78.43%  |
| 16/10 | 25        | 12.25%  |
| 5/4   | 14        | 6.86%   |
| 4/3   | 4         | 1.96%   |
| 6/5   | 1         | 0.49%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inchÂ² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 55        | 26.19%  |
| 101-110        | 54        | 25.71%  |
| 151-200        | 28        | 13.33%  |
| 141-150        | 13        | 6.19%   |
| 81-90          | 9         | 4.29%   |
| 41-50          | 9         | 4.29%   |
| 301-350        | 9         | 4.29%   |
| More than 1000 | 7         | 3.33%   |
| 351-500        | 7         | 3.33%   |
| 121-130        | 6         | 2.86%   |
| 251-300        | 5         | 2.38%   |
| 51-60          | 2         | 0.95%   |
| 111-120        | 2         | 0.95%   |
| 501-1000       | 2         | 0.95%   |
| 71-80          | 1         | 0.48%   |
| 1-40           | 1         | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 97        | 46.41%  |
| 101-120 | 84        | 40.19%  |
| 121-160 | 19        | 9.09%   |
| 1-50    | 9         | 4.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 204       | 93.58%  |
| 2     | 9         | 4.13%   |
| 0     | 5         | 2.29%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 144       | 42.86%  |
| Qualcomm Atheros                | 62        | 18.45%  |
| Intel                           | 47        | 13.99%  |
| Broadcom                        | 21        | 6.25%   |
| Nvidia                          | 9         | 2.68%   |
| Ralink Technology               | 8         | 2.38%   |
| Broadcom Limited                | 7         | 2.08%   |
| Ralink                          | 6         | 1.79%   |
| Marvell Technology Group        | 6         | 1.79%   |
| Xiaomi                          | 5         | 1.49%   |
| VIA Technologies                | 4         | 1.19%   |
| TP-LINK                         | 3         | 0.89%   |
| Huawei Technologies             | 3         | 0.89%   |
| ZTE WCDMA Technologies MSM      | 2         | 0.6%    |
| MediaTek                        | 2         | 0.6%    |
| Xilinx                          | 1         | 0.3%    |
| Vimtron Electronics             | 1         | 0.3%    |
| Samsung Electronics             | 1         | 0.3%    |
| Realtek                         | 1         | 0.3%    |
| Qualcomm Atheros Communications | 1         | 0.3%    |
| D-Link                          | 1         | 0.3%    |
| Attansic Technology             | 1         | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 101       | 27.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 27        | 7.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 3.81%   |
| Nvidia MCP61 Ethernet                                                   | 7         | 1.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 1.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 1.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 1.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 1.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 1.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.09%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 1.09%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.09%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 1.09%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 4         | 1.09%   |
| Intel WiMAX/WiFi Link 5150                                              | 4         | 1.09%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 1.09%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.09%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.82%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 3         | 0.82%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 3         | 0.82%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 3         | 0.82%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.82%   |
| Intel Wireless 3165                                                     | 3         | 0.82%   |
| Intel I211 Gigabit Network Connection                                   | 3         | 0.82%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 3         | 0.82%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 0.82%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                             | 2         | 0.54%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 2         | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.54%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.54%   |
| Realtek RTL8187 Wireless Adapter                                        | 2         | 0.54%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.54%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                              | 2         | 0.54%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                           | 2         | 0.54%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.54%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 2         | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 2         | 0.54%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.54%   |
| Intel WiMAX Connection 2400m                                            | 2         | 0.54%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 0.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.54%   |
| Intel Ethernet Connection (2) I219-V                                    | 2         | 0.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.54%   |
| Intel Centrino Wireless-N 130                                           | 2         | 0.54%   |
| Intel 82579V Gigabit Network Connection                                 | 2         | 0.54%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 2         | 0.54%   |
| Xilinx Network controller                                               | 1         | 0.27%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1         | 0.27%   |
| Vimtron Mobile Composite Device Bus                                     | 1         | 0.27%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 1         | 0.27%   |
| VIA VIA VNT-6656 [WiFi 802.11b/g USB Dongle]                            | 1         | 0.27%   |
| TP-LINK USB 10/100 LAN                                                  | 1         | 0.27%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1         | 0.27%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 0.27%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.27%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 39        | 29.55%  |
| Realtek Semiconductor           | 25        | 18.94%  |
| Intel                           | 24        | 18.18%  |
| Broadcom                        | 18        | 13.64%  |
| Ralink Technology               | 8         | 6.06%   |
| Ralink                          | 6         | 4.55%   |
| Broadcom Limited                | 5         | 3.79%   |
| TP-Link                         | 2         | 1.52%   |
| VIA Technologies                | 1         | 0.76%   |
| Realtek                         | 1         | 0.76%   |
| Qualcomm Atheros Communications | 1         | 0.76%   |
| MediaTek                        | 1         | 0.76%   |
| D-Link                          | 1         | 0.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 10.53%  |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 5.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 4.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 4.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 3.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 3.01%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 3.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 3.01%   |
| Intel WiMAX/WiFi Link 5150                                              | 4         | 3.01%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 3.01%   |
| Realtek 802.11ac NIC                                                    | 3         | 2.26%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 2.26%   |
| Intel Wireless-AC 9260                                                  | 3         | 2.26%   |
| Intel Wireless 3165                                                     | 3         | 2.26%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 3         | 2.26%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 2.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 1.5%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.5%    |
| Realtek RTL8187 Wireless Adapter                                        | 2         | 1.5%    |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 1.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.5%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 2         | 1.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.5%    |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.5%    |
| Intel Centrino Wireless-N 130                                           | 2         | 1.5%    |
| VIA VIA VNT-6656 [WiFi 802.11b/g USB Dongle]                            | 1         | 0.75%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1         | 0.75%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 0.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.75%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.75%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.75%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.75%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.75%   |
| Realtek 802.11n NIC                                                     | 1         | 0.75%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 0.75%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 1         | 0.75%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.75%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.75%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 1         | 0.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.75%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.75%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 0.75%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.75%   |
| MediaTek WiFi                                                           | 1         | 0.75%   |
| Intel Wireless 7265                                                     | 1         | 0.75%   |
| Intel Wireless 7260                                                     | 1         | 0.75%   |
| Intel Wireless 3160                                                     | 1         | 0.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.75%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.75%   |
| Intel Centrino Wireless-N 100                                           | 1         | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 0.75%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]           | 1         | 0.75%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                 | 1         | 0.75%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 0.75%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 130       | 56.77%  |
| Qualcomm Atheros           | 30        | 13.1%   |
| Intel                      | 29        | 12.66%  |
| Nvidia                     | 9         | 3.93%   |
| Marvell Technology Group   | 6         | 2.62%   |
| Broadcom                   | 6         | 2.62%   |
| Xiaomi                     | 5         | 2.18%   |
| VIA Technologies           | 3         | 1.31%   |
| ZTE WCDMA Technologies MSM | 2         | 0.87%   |
| Huawei Technologies        | 2         | 0.87%   |
| Broadcom Limited           | 2         | 0.87%   |
| Vimtron Electronics        | 1         | 0.44%   |
| TP-LINK                    | 1         | 0.44%   |
| Samsung Electronics        | 1         | 0.44%   |
| MediaTek                   | 1         | 0.44%   |
| Attansic Technology        | 1         | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 101       | 43.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 11.64%  |
| Nvidia MCP61 Ethernet                                             | 7         | 3.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 2.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 1.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 1.72%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4         | 1.72%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.72%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 3         | 1.29%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 1.29%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 1.29%   |
| Intel I211 Gigabit Network Connection                             | 3         | 1.29%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 2         | 0.86%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 0.86%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2         | 0.86%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2         | 0.86%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.86%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.86%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.86%   |
| Intel WiMAX Connection 2400m                                      | 2         | 0.86%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.86%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.86%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.43%   |
| Vimtron Mobile Composite Device Bus                               | 1         | 0.43%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.43%   |
| TP-LINK USB 10/100 LAN                                            | 1         | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.43%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.43%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.43%   |
| Nvidia MCP77 Ethernet                                             | 1         | 0.43%   |
| MediaTek moto g(8) power lite                                     | 1         | 0.43%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.43%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.43%   |
| Marvell Group 88E8052 PCI-E ASF Gigabit Ethernet Controller       | 1         | 0.43%   |
| Intel PRO/100 VM Network Connection                               | 1         | 0.43%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 0.43%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.43%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.43%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.43%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.43%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 0.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 0.43%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.43%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                 | 1         | 0.43%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1         | 0.43%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.43%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 0.43%   |
| Intel 82562V-2 10/100 Network Connection                          | 1         | 0.43%   |
| Intel 82547EI Gigabit Ethernet Controller                         | 1         | 0.43%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1         | 0.43%   |
| Huawei E353/E3131                                                 | 1         | 0.43%   |
| Huawei BLA-L29                                                    | 1         | 0.43%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.43%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 1         | 0.43%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.43%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.43%   |
| Broadcom Micromax                                                 | 1         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 213       | 62.46%  |
| WiFi     | 126       | 36.95%  |
| Modem    | 1         | 0.29%   |
| Unknown  | 1         | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 121       | 54.75%  |
| WiFi     | 100       | 45.25%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 107       | 49.08%  |
| 2     | 106       | 48.62%  |
| 3     | 3         | 1.38%   |
| 0     | 2         | 0.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 204       | 93.58%  |
| Yes  | 14        | 6.42%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 18.75%  |
| Qualcomm Atheros Communications | 10        | 12.5%   |
| Cambridge Silicon Radio         | 10        | 12.5%   |
| Broadcom                        | 9         | 11.25%  |
| Realtek Semiconductor           | 7         | 8.75%   |
| IMC Networks                    | 7         | 8.75%   |
| Lite-On Technology              | 5         | 6.25%   |
| Foxconn / Hon Hai               | 5         | 6.25%   |
| Ralink                          | 3         | 3.75%   |
| Foxconn International           | 2         | 2.5%    |
| ASUSTek Computer                | 2         | 2.5%    |
| Apple                           | 2         | 2.5%    |
| Alps Electric                   | 2         | 2.5%    |
| Toshiba                         | 1         | 1.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 12.5%   |
| Intel Bluetooth wireless interface                  | 6         | 7.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 5%      |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 3.75%   |
| Ralink RT3290 Bluetooth                             | 3         | 3.75%   |
| Lite-On Bluetooth Device                            | 3         | 3.75%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 3         | 3.75%   |
| Realtek Bluetooth Radio                             | 2         | 2.5%    |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.5%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 2.5%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 2.5%    |
| Intel Bluetooth Device                              | 2         | 2.5%    |
| Intel AX200 Bluetooth                               | 2         | 2.5%    |
| IMC Networks Bluetooth Radio                        | 2         | 2.5%    |
| IMC Networks Bluetooth Device                       | 2         | 2.5%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 2.5%    |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 2.5%    |
| Broadcom BCM2045 Bluetooth                          | 2         | 2.5%    |
| Toshiba Integrated Bluetooth HCI                    | 1         | 1.25%   |
| Realtek RTL8821A Bluetooth                          | 1         | 1.25%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.25%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.25%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 1.25%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.25%   |
| Lite-On Bluetooth Radio                             | 1         | 1.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.25%   |
| Intel AX210 Bluetooth                               | 1         | 1.25%   |
| IMC Networks Bluetooth                              | 1         | 1.25%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 1.25%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 1.25%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.25%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.25%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.25%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.25%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 1.25%   |
| Broadcom BCM2035 Bluetooth dongle                   | 1         | 1.25%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 1.25%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.25%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.25%   |
| Apple Bluetooth Host Controller                     | 1         | 1.25%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 1.25%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 1.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 152       | 48.87%  |
| Nvidia                    | 76        | 24.44%  |
| AMD                       | 66        | 21.22%  |
| Logitech                  | 5         | 1.61%   |
| Creative Labs             | 4         | 1.29%   |
| VIA Technologies          | 2         | 0.64%   |
| C-Media Electronics       | 2         | 0.64%   |
| Sennheiser Communications | 1         | 0.32%   |
| Pixart Imaging            | 1         | 0.32%   |
| JMTek                     | 1         | 0.32%   |
| BEHRINGER International   | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 32        | 8.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 22        | 6.16%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 20        | 5.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 5.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 13        | 3.64%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 13        | 3.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 3.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 3.36%   |
| AMD FCH Azalia Controller                                                                         | 10        | 2.8%    |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 10        | 2.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.24%   |
| Nvidia MCP61 High Definition Audio                                                                | 7         | 1.96%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 1.68%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 5         | 1.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.4%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.4%    |
| Intel Broadwell-U Audio Controller                                                                | 5         | 1.4%    |
| Nvidia GP108 High Definition Audio Controller                                                     | 4         | 1.12%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 1.12%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 1.12%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 1.12%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 1.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.12%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4         | 1.12%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 1.12%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 1.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.12%   |
| AMD Wrestler HDMI Audio                                                                           | 4         | 1.12%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 1.12%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.84%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.84%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 3         | 0.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.84%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3         | 0.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.84%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.84%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 3         | 0.84%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 0.84%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 0.84%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 0.84%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.84%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 2         | 0.56%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.56%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.56%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.56%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 0.56%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.56%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 2         | 0.56%   |
| Logitech USB Headset H540                                                                         | 2         | 0.56%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller                                    | 2         | 0.56%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2         | 0.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.56%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 0.56%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                                         | 2         | 0.56%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.56%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.56%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.56%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 74        | 28.57%  |
| Samsung Electronics          | 36        | 13.9%   |
| Kingston                     | 35        | 13.51%  |
| SK Hynix                     | 28        | 10.81%  |
| Micron Technology            | 11        | 4.25%   |
| Corsair                      | 7         | 2.7%    |
| AMD                          | 7         | 2.7%    |
| Elpida                       | 6         | 2.32%   |
| Crucial                      | 6         | 2.32%   |
| Ramaxel Technology           | 5         | 1.93%   |
| Nanya Technology             | 5         | 1.93%   |
| A-DATA Technology            | 5         | 1.93%   |
| GOODRAM                      | 4         | 1.54%   |
| Patriot                      | 3         | 1.16%   |
| ASint Technology             | 3         | 1.16%   |
| Team                         | 2         | 0.77%   |
| SHARETRONIC                  | 2         | 0.77%   |
| Goldkey                      | 2         | 0.77%   |
| Unknown (8A02)               | 1         | 0.39%   |
| Unknown (0x8001440000000000) | 1         | 0.39%   |
| Unknown (0B7A)               | 1         | 0.39%   |
| TOP MEDIA                    | 1         | 0.39%   |
| Smart                        | 1         | 0.39%   |
| SKHynix                      | 1         | 0.39%   |
| Ramos Technology             | 1         | 0.39%   |
| Qumo                         | 1         | 0.39%   |
| MLLSE                        | 1         | 0.39%   |
| Kllisre                      | 1         | 0.39%   |
| Kingmax                      | 1         | 0.39%   |
| GeIL                         | 1         | 0.39%   |
| Foxline                      | 1         | 0.39%   |
| Exceleram                    | 1         | 0.39%   |
| atermiter                    | 1         | 0.39%   |
| Ankowall                     | 1         | 0.39%   |
| 48spaces                     | 1         | 0.39%   |
| Unknown                      | 1         | 0.39%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB DIMM 800MT/s                        | 4         | 1.4%    |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s     | 4         | 1.4%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 3         | 1.05%   |
| Unknown RAM Module 2GB DIMM SDRAM                          | 3         | 1.05%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s   | 3         | 1.05%   |
| Samsung RAM M471B2873FHS-CH9 1024MB SODIMM DDR3 1334MT/s   | 3         | 1.05%   |
| Unknown SODIMM 4096MB SODIMM DDR2 800MT/s                  | 2         | 0.7%    |
| Unknown SODIMM 2GB SODIMM DDR2 667MT/s                     | 2         | 0.7%    |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                  | 2         | 0.7%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                  | 2         | 0.7%    |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s               | 2         | 0.7%    |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                | 2         | 0.7%    |
| Unknown RAM Module 2048MB DIMM 800MT/s                     | 2         | 0.7%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                    | 2         | 0.7%    |
| Unknown RAM Module 1024MB DIMM                             | 2         | 0.7%    |
| SK Hynix RAM HYMP112U64CP8-Y5 1GB DIMM DDR2 1639MT/s       | 2         | 0.7%    |
| SK Hynix RAM HMT451S6DFR8A-PB 4096MB SODIMM DDR3 1600MT/s  | 2         | 0.7%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 0.7%    |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 2         | 0.7%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s  | 2         | 0.7%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 2         | 0.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 2         | 0.7%    |
| Samsung RAM M471B5173BH0-CK0 4096MB SODIMM DDR3 1600MT/s   | 2         | 0.7%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 2         | 0.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s      | 2         | 0.7%    |
| Ramaxel RAM RMT3170EB68F9W1600 4096MB SODIMM DDR3 1600MT/s | 2         | 0.7%    |
| Ramaxel RAM RMT3150ED58E8W1600 2048MB SODIMM DDR3 1600MT/s | 2         | 0.7%    |
| Micron RAM 16KTF51264AZ-1G6M1 4096MB DIMM 1600MT/s         | 2         | 0.7%    |
| Kingston RAM KHX1600C9D3/2GX 2GB DIMM DDR3 1600MT/s        | 2         | 0.7%    |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1600MT/s      | 2         | 0.7%    |
| Kingston RAM 99U5471-020.A00LF 4096MB DIMM DDR3 1600MT/s   | 2         | 0.7%    |
| Kingston RAM 9905471-017.A00LF 4096MB DIMM DDR3 1333MT/s   | 2         | 0.7%    |
| Unknown SODIMM 2048MB SODIMM DDR2 800MT/s                  | 1         | 0.35%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                  | 1         | 0.35%   |
| Unknown SODIMM 2048MB SODIMM DDR2 533MT/s                  | 1         | 0.35%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                  | 1         | 0.35%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s               | 1         | 0.35%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s               | 1         | 0.35%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                | 1         | 0.35%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                | 1         | 0.35%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                | 1         | 0.35%   |
| Unknown RAM Module 4GB DIMM DDR4 2400MT/s                  | 1         | 0.35%   |
| Unknown RAM Module 4GB DIMM DDR 1066MT/s                   | 1         | 0.35%   |
| Unknown RAM Module 4GB DIMM 400MT/s                        | 1         | 0.35%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 1         | 0.35%   |
| Unknown RAM Module 4GB DIMM                                | 1         | 0.35%   |
| Unknown RAM Module 4096MB SODIMM DDR3                      | 1         | 0.35%   |
| Unknown RAM Module 4096MB DIMM SDRAM 1066MT/s              | 1         | 0.35%   |
| Unknown RAM Module 4096MB DIMM SDRAM                       | 1         | 0.35%   |
| Unknown RAM Module 4096MB DIMM 800MT/s                     | 1         | 0.35%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                    | 1         | 0.35%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                | 1         | 0.35%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 1         | 0.35%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                      | 1         | 0.35%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                  | 1         | 0.35%   |
| Unknown RAM Module 2GB DIMM SDRAM 1066MT/s                 | 1         | 0.35%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                  | 1         | 0.35%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                   | 1         | 0.35%   |
| Unknown RAM Module 2GB DIMM DDR2                           | 1         | 0.35%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                   | 1         | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 95        | 42.79%  |
| DDR4    | 48        | 21.62%  |
| DDR2    | 28        | 12.61%  |
| Unknown | 22        | 9.91%   |
| SDRAM   | 21        | 9.46%   |
| DDR     | 7         | 3.15%   |
| DRAM    | 1         | 0.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 121       | 56.02%  |
| SODIMM       | 94        | 43.52%  |
| Row Of Chips | 1         | 0.46%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 90        | 37.04%  |
| 2048  | 71        | 29.22%  |
| 8192  | 45        | 18.52%  |
| 1024  | 26        | 10.7%   |
| 16384 | 9         | 3.7%    |
| 512   | 2         | 0.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 60        | 24.39%  |
| 1333    | 32        | 13.01%  |
| 2400    | 21        | 8.54%   |
| 800     | 20        | 8.13%   |
| Unknown | 17        | 6.91%   |
| 2667    | 16        | 6.5%    |
| 667     | 14        | 5.69%   |
| 1334    | 12        | 4.88%   |
| 3200    | 6         | 2.44%   |
| 1067    | 5         | 2.03%   |
| 1066    | 5         | 2.03%   |
| 400     | 5         | 2.03%   |
| 2133    | 4         | 1.63%   |
| 2048    | 4         | 1.63%   |
| 2933    | 3         | 1.22%   |
| 533     | 3         | 1.22%   |
| 4199    | 2         | 0.81%   |
| 3266    | 2         | 0.81%   |
| 1867    | 2         | 0.81%   |
| 1639    | 2         | 0.81%   |
| 3600    | 1         | 0.41%   |
| 3533    | 1         | 0.41%   |
| 3500    | 1         | 0.41%   |
| 3400    | 1         | 0.41%   |
| 3151    | 1         | 0.41%   |
| 3007    | 1         | 0.41%   |
| 3000    | 1         | 0.41%   |
| 2800    | 1         | 0.41%   |
| 2666    | 1         | 0.41%   |
| 333     | 1         | 0.41%   |
| 133     | 1         | 0.41%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)

![Printer Vendor](./All/images/line_chart/printer_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 36.36%  |
| Seiko Epson         | 3         | 27.27%  |
| Hewlett-Packard     | 3         | 27.27%  |
| Canon               | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)

![Printer Model](./All/images/line_chart/printer_model.svg)

| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| Seiko Epson L805 Series   | 1         | 9.09%   |
| Seiko Epson L222 Series   | 1         | 9.09%   |
| Seiko Epson L210 Series   | 1         | 9.09%   |
| Samsung SCX-4200 series   | 1         | 9.09%   |
| Samsung SCX-4100 Scanner  | 1         | 9.09%   |
| Samsung Phaser 3121       | 1         | 9.09%   |
| Samsung ML-1210 Printer   | 1         | 9.09%   |
| HP LaserJet 1020          | 1         | 9.09%   |
| HP LaserJet 1010          | 1         | 9.09%   |
| HP DeskJet 2130 series    | 1         | 9.09%   |
| Canon PIXMA MG2500 Series | 1         | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)

![Scanner Vendor](./All/images/line_chart/scanner_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)

![Scanner Model](./All/images/line_chart/scanner_model.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 33.33%  |
| Canon CanoScan LiDE 210 | 1         | 33.33%  |
| Canon CanoScan LiDE 110 | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)

![Camera Vendor](./All/images/line_chart/camera_vendor.svg)

| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 20        | 18.02%  |
| Acer                                   | 11        | 9.91%   |
| Logitech                               | 9         | 8.11%   |
| Sunplus Innovation Technology          | 8         | 7.21%   |
| IMC Networks                           | 7         | 6.31%   |
| Suyin                                  | 5         | 4.5%    |
| Silicon Motion                         | 5         | 4.5%    |
| Alcor Micro                            | 5         | 4.5%    |
| Z-Star Microelectronics                | 4         | 3.6%    |
| Realtek Semiconductor                  | 4         | 3.6%    |
| Microsoft                              | 3         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.7%    |
| Syntek                                 | 2         | 1.8%    |
| Ricoh                                  | 2         | 1.8%    |
| Quanta                                 | 2         | 1.8%    |
| KYE Systems (Mouse Systems)            | 2         | 1.8%    |
| DigiTech                               | 2         | 1.8%    |
| Apple                                  | 2         | 1.8%    |
| ALi                                    | 2         | 1.8%    |
| A4Tech                                 | 2         | 1.8%    |
| Trust                                  | 1         | 0.9%    |
| Pixart Imaging                         | 1         | 0.9%    |
| Novatek Microelectronics               | 1         | 0.9%    |
| Microdia                               | 1         | 0.9%    |
| Luxvisions Innotech Limited            | 1         | 0.9%    |
| lihappe8                               | 1         | 0.9%    |
| Hewlett-Packard                        | 1         | 0.9%    |
| Genesys Logic                          | 1         | 0.9%    |
| GEMBIRD                                | 1         | 0.9%    |
| Cubeternet                             | 1         | 0.9%    |
| Unknown                                | 1         | 0.9%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Sunplus HD WebCam                                           | 4         | 3.6%    |
| Logitech Webcam C270                                        | 3         | 2.7%    |
| Chicony HP Truevision HD                                    | 3         | 2.7%    |
| Z-Star Venus USB2.0 Camera                                  | 2         | 1.8%    |
| Suyin Integrated_Webcam_HD                                  | 2         | 1.8%    |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 1.8%    |
| DigiTech USB 2.0 PC Camera                                  | 2         | 1.8%    |
| Chicony Lenovo EasyCamera                                   | 2         | 1.8%    |
| Chicony EasyCamera                                          | 2         | 1.8%    |
| Alcor Micro Asus Integrated Webcam                          | 2         | 1.8%    |
| Acer Lenovo Integrated Webcam                               | 2         | 1.8%    |
| Acer HP Webcam                                              | 2         | 1.8%    |
| Z-Star Vega USB 2.0 Camera                                  | 1         | 0.9%    |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 0.9%    |
| Trust 17676 Webcam                                          | 1         | 0.9%    |
| Syntek Web Cam - Asus A8J, F3S, F5R, VX2S, V1S              | 1         | 0.9%    |
| Syntek Lenovo EasyCamera                                    | 1         | 0.9%    |
| Suyin HD Video WebCam                                       | 1         | 0.9%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.9%    |
| Suyin 1.3M HD WebCam                                        | 1         | 0.9%    |
| Sunplus Lenovo EasyCamera                                   | 1         | 0.9%    |
| Sunplus HP Truevision HD                                    | 1         | 0.9%    |
| Sunplus Dell HD Webcam                                      | 1         | 0.9%    |
| Sunplus Asus Webcam                                         | 1         | 0.9%    |
| Silicon Motion WebCam SCB-0385N                             | 1         | 0.9%    |
| Silicon Motion WebCam SC-13HDL11939N                        | 1         | 0.9%    |
| Silicon Motion WebCam SC-0311139N                           | 1         | 0.9%    |
| Silicon Motion Web Camera                                   | 1         | 0.9%    |
| Silicon Motion HP Webcam-101                                | 1         | 0.9%    |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870]         | 1         | 0.9%    |
| Ricoh Sony Vaio Integrated Webcam                           | 1         | 0.9%    |
| Realtek Lenovo EasyCamera                                   | 1         | 0.9%    |
| Realtek Integrated_Webcam_HD                                | 1         | 0.9%    |
| Realtek HP Truevision HD                                    | 1         | 0.9%    |
| Realtek 2SF022                                              | 1         | 0.9%    |
| Quanta VGA WebCam                                           | 1         | 0.9%    |
| Quanta HD User Facing                                       | 1         | 0.9%    |
| Pixart Imaging Multimedia audio controller                  | 1         | 0.9%    |
| Novatek AF HD 720P Webcam                                   | 1         | 0.9%    |
| Microsoft LifeCam VX-800                                    | 1         | 0.9%    |
| Microsoft LifeCam VX-700                                    | 1         | 0.9%    |
| Microsoft LifeCam VX-2000                                   | 1         | 0.9%    |
| Microdia USB 2.0 Camera                                     | 1         | 0.9%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 1         | 0.9%    |
| Logitech Webcam C310                                        | 1         | 0.9%    |
| Logitech Webcam C210                                        | 1         | 0.9%    |
| Logitech Webcam C170                                        | 1         | 0.9%    |
| Logitech Logitech Webcam C160                               | 1         | 0.9%    |
| Logitech HD Webcam B910                                     | 1         | 0.9%    |
| Logitech C922 Pro Stream Webcam                             | 1         | 0.9%    |
| lihappe8 USB 2.0 Camera                                     | 1         | 0.9%    |
| KYE Systems (Mouse Systems) FaceCam 1320                    | 1         | 0.9%    |
| KYE Systems (Mouse Systems) eFace 1300                      | 1         | 0.9%    |
| IMC Networks USB2.0 UVC 2M WebCam                           | 1         | 0.9%    |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 0.9%    |
| IMC Networks Lenovo EasyCamera                              | 1         | 0.9%    |
| IMC Networks Integrated Webcam                              | 1         | 0.9%    |
| IMC Networks HP TrueVision HD Camera                        | 1         | 0.9%    |
| HP Webcam HD 4310                                           | 1         | 0.9%    |
| Genesys Logic USB 2.0 Camera                                | 1         | 0.9%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 33.33%  |
| STMicroelectronics         | 2         | 33.33%  |
| Upek                       | 1         | 16.67%  |
| Shenzhen Goodix Technology | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| STMicroelectronics Fingerprint Reader                  | 2         | 33.33%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 16.67%  |
| Validity Sensors Fingerprint scanner                   | 1         | 16.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 16.67%  |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 16.67%  |

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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 188       | 86.24%  |
| 1     | 28        | 12.84%  |
| 2     | 2         | 0.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 11        | 35.48%  |
| Fingerprint reader       | 6         | 19.35%  |
| Net/wireless             | 5         | 16.13%  |
| Bluetooth                | 4         | 12.9%   |
| Unassigned class         | 3         | 9.68%   |
| Communication controller | 2         | 6.45%   |

