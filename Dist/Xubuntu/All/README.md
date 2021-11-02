Xubuntu Hardware Trends
-----------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Xubuntu users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Xubuntu/Desktop/README.md) and [notebooks](/Dist/Xubuntu/Notebook/README.md).

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

![OS](./images/pie_chart/os_name.svg)

![OS](./images/line_chart/os_name.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| Xubuntu 20.04 | 81        | 65.32%  |
| Xubuntu 18.04 | 21        | 16.94%  |
| Xubuntu 21.04 | 12        | 9.68%   |
| Xubuntu 21.10 | 8         | 6.45%   |
| Xubuntu 20.10 | 1         | 0.81%   |
| Xubuntu 16.04 | 1         | 0.81%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Xubuntu | 124       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.11.0-37-generic           | 23        | 18.55%  |
| 5.4.0-88-generic            | 12        | 9.68%   |
| 5.11.0-38-generic           | 11        | 8.87%   |
| 5.4.0-89-generic            | 9         | 7.26%   |
| 5.4.0-87-generic            | 8         | 6.45%   |
| 5.11.0-27-generic           | 8         | 6.45%   |
| 5.11.0-38-lowlatency        | 6         | 4.84%   |
| 5.13.0-20-generic           | 5         | 4.03%   |
| 5.11.0-37-lowlatency        | 3         | 2.42%   |
| 5.11.0-36-generic           | 3         | 2.42%   |
| 5.4.0-89-lowlatency         | 2         | 1.61%   |
| 5.4.0-88-lowlatency         | 2         | 1.61%   |
| 4.15.0-159-lowlatency       | 2         | 1.61%   |
| 4.15.0-159-generic          | 2         | 1.61%   |
| 5.8.0-63-generic            | 1         | 0.81%   |
| 5.8.0-43-generic            | 1         | 0.81%   |
| 5.4.0-86-generic            | 1         | 0.81%   |
| 5.4.0-84-generic            | 1         | 0.81%   |
| 5.4.0-81-generic            | 1         | 0.81%   |
| 5.4.0-80-generic            | 1         | 0.81%   |
| 5.4.0-77-lowlatency         | 1         | 0.81%   |
| 5.4.0-77-generic            | 1         | 0.81%   |
| 5.4.0-72-lowlatency         | 1         | 0.81%   |
| 5.14.8-051408-generic       | 1         | 0.81%   |
| 5.14.7-xanmod1-edge         | 1         | 0.81%   |
| 5.14.0-11.1-liquorix-amd64  | 1         | 0.81%   |
| 5.13.0-21-generic           | 1         | 0.81%   |
| 5.13.0-19-generic           | 1         | 0.81%   |
| 5.11.0-36-lowlatency        | 1         | 0.81%   |
| 5.11.0-27-lowlatency        | 1         | 0.81%   |
| 5.11.0-22-generic           | 1         | 0.81%   |
| 5.11.0-16-generic           | 1         | 0.81%   |
| 5.10.60-sunxi               | 1         | 0.81%   |
| 5.0.0-19-generic            | 1         | 0.81%   |
| 4.9.241                     | 1         | 0.81%   |
| 4.4.254-20721-gc5eeb683840e | 1         | 0.81%   |
| 4.4.0-217-generic           | 1         | 0.81%   |
| 4.18.0-21-generic           | 1         | 0.81%   |
| 4.15.0-158-lowlatency       | 1         | 0.81%   |
| 4.15.0-158-generic          | 1         | 0.81%   |
| 4.15.0-151-generic          | 1         | 0.81%   |
| 4.15.0-121-lowlatency       | 1         | 0.81%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 58        | 46.77%  |
| 5.4.0   | 40        | 32.26%  |
| 4.15.0  | 8         | 6.45%   |
| 5.13.0  | 7         | 5.65%   |
| 5.8.0   | 2         | 1.61%   |
| 5.14.8  | 1         | 0.81%   |
| 5.14.7  | 1         | 0.81%   |
| 5.14.0  | 1         | 0.81%   |
| 5.10.60 | 1         | 0.81%   |
| 5.0.0   | 1         | 0.81%   |
| 4.9.241 | 1         | 0.81%   |
| 4.4.254 | 1         | 0.81%   |
| 4.4.0   | 1         | 0.81%   |
| 4.18.0  | 1         | 0.81%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 58        | 46.77%  |
| 5.4     | 40        | 32.26%  |
| 4.15    | 8         | 6.45%   |
| 5.13    | 7         | 5.65%   |
| 5.14    | 3         | 2.42%   |
| 5.8     | 2         | 1.61%   |
| 4.4     | 2         | 1.61%   |
| 5.10    | 1         | 0.81%   |
| 5.0     | 1         | 0.81%   |
| 4.9     | 1         | 0.81%   |
| 4.18    | 1         | 0.81%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 113       | 91.13%  |
| i686    | 9         | 7.26%   |
| armv7l  | 1         | 0.81%   |
| aarch64 | 1         | 0.81%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| XFCE    | 119       | 95.97%  |
| GNOME   | 2         | 1.61%   |
| KDE5    | 1         | 0.81%   |
| i3      | 1         | 0.81%   |
| GNUstep | 1         | 0.81%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 121       | 97.58%  |
| Wayland | 2         | 1.61%   |
| Tty     | 1         | 0.81%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 110       | 88.71%  |
| Unknown | 6         | 4.84%   |
| GDM3    | 5         | 4.03%   |
| GDM     | 3         | 2.42%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 42        | 33.87%  |
| fr_FR | 15        | 12.1%   |
| de_DE | 15        | 12.1%   |
| C     | 8         | 6.45%   |
| ru_RU | 6         | 4.84%   |
| it_IT | 5         | 4.03%   |
| pt_BR | 3         | 2.42%   |
| hu_HU | 3         | 2.42%   |
| es_ES | 3         | 2.42%   |
| en_GB | 3         | 2.42%   |
| en_CA | 3         | 2.42%   |
| nl_NL | 2         | 1.61%   |
| es_CR | 2         | 1.61%   |
| es_AR | 2         | 1.61%   |
| en_AU | 2         | 1.61%   |
| cs_CZ | 2         | 1.61%   |
| sv_SE | 1         | 0.81%   |
| sv_FI | 1         | 0.81%   |
| ru_UA | 1         | 0.81%   |
| pl_PL | 1         | 0.81%   |
| es_VE | 1         | 0.81%   |
| en_ZA | 1         | 0.81%   |
| el_GR | 1         | 0.81%   |
| ca_ES | 1         | 0.81%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 84        | 67.74%  |
| EFI  | 40        | 32.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 108       | 87.1%   |
| Overlay | 10        | 8.06%   |
| Btrfs   | 4         | 3.23%   |
| Zfs     | 1         | 0.81%   |
| Unknown | 1         | 0.81%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 72        | 58.06%  |
| GPT     | 37        | 29.84%  |
| MBR     | 15        | 12.1%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 107       | 86.29%  |
| Yes       | 17        | 13.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 64        | 51.61%  |
| Yes       | 60        | 48.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 22        | 17.74%  |
| Lenovo              | 17        | 13.71%  |
| Dell                | 17        | 13.71%  |
| Hewlett-Packard     | 14        | 11.29%  |
| Gigabyte Technology | 7         | 5.65%   |
| Acer                | 7         | 5.65%   |
| MSI                 | 5         | 4.03%   |
| Sony                | 4         | 3.23%   |
| ASRock              | 4         | 3.23%   |
| Toshiba             | 3         | 2.42%   |
| HUAWEI              | 3         | 2.42%   |
| Medion              | 2         | 1.61%   |
| Alienware           | 2         | 1.61%   |
| VIT                 | 1         | 0.81%   |
| Supermicro          | 1         | 0.81%   |
| sunxi               | 1         | 0.81%   |
| Samsung Electronics | 1         | 0.81%   |
| Razer               | 1         | 0.81%   |
| PCChips             | 1         | 0.81%   |
| NCR                 | 1         | 0.81%   |
| Multilaser          | 1         | 0.81%   |
| MiTAC               | 1         | 0.81%   |
| LG Electronics      | 1         | 0.81%   |
| Khadas              | 1         | 0.81%   |
| Fujitsu Siemens     | 1         | 0.81%   |
| Fujitsu             | 1         | 0.81%   |
| Foxconn             | 1         | 0.81%   |
| Clientron           | 1         | 0.81%   |
| Biostar             | 1         | 0.81%   |
| Apple               | 1         | 0.81%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop X571LH_K571LH   | 3         | 2.42%   |
| HP Compaq 6730s                          | 2         | 1.61%   |
| VIT P3400                                | 1         | 0.81%   |
| Toshiba Satellite P55W-C                 | 1         | 0.81%   |
| Toshiba Satellite L850                   | 1         | 0.81%   |
| Toshiba Satellite A100                   | 1         | 0.81%   |
| Supermicro X8DTH-i/6/iF/6F               | 1         | 0.81%   |
| sunxi Libre Board ALL-H3-CC H3           | 1         | 0.81%   |
| Sony VPCSB1V9R                           | 1         | 0.81%   |
| Sony VGN-NR38E_S                         | 1         | 0.81%   |
| Sony VGN-NR11Z_T                         | 1         | 0.81%   |
| Sony VGN-N11M_W                          | 1         | 0.81%   |
| Samsung R530/R730/P590                   | 1         | 0.81%   |
| Razer Blade Stealth 13 Late 2019         | 1         | 0.81%   |
| PCChips P49G                             | 1         | 0.81%   |
| NCR 7606-1309-8801                       | 1         | 0.81%   |
| Multilaser UB32X                         | 1         | 0.81%   |
| MSI MS-7C37                              | 1         | 0.81%   |
| MSI MS-7A34                              | 1         | 0.81%   |
| MSI MS-7982                              | 1         | 0.81%   |
| MSI MS-7917                              | 1         | 0.81%   |
| MSI MS-1034                              | 1         | 0.81%   |
| MiTAC PD14RI                             | 1         | 0.81%   |
| Medion E62009                            | 1         | 0.81%   |
| Medion E14303                            | 1         | 0.81%   |
| LG R710-S.APSAG                          | 1         | 0.81%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US | 1         | 0.81%   |
| Lenovo ThinkPad W510 431963G             | 1         | 0.81%   |
| Lenovo ThinkPad T60 1952W97              | 1         | 0.81%   |
| Lenovo ThinkPad T510 4384A78             | 1         | 0.81%   |
| Lenovo ThinkPad T440s 20AQ009DGE         | 1         | 0.81%   |
| Lenovo ThinkPad T420 4180AP3             | 1         | 0.81%   |
| Lenovo ThinkPad T14s Gen 1 20UH0016GE    | 1         | 0.81%   |
| Lenovo ThinkPad E14 20RA0016RT           | 1         | 0.81%   |
| Lenovo ThinkCentre M82 2756AT9           | 1         | 0.81%   |
| Lenovo ThinkCentre A55 92658HG           | 1         | 0.81%   |
| Lenovo ThinkBook 14 G2 ITL 20VD          | 1         | 0.81%   |
| Lenovo MIIX 320-10ICR 80XF               | 1         | 0.81%   |
| Lenovo IdeaPad U550 20034,3749           | 1         | 0.81%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 1         | 0.81%   |
| Lenovo IdeaPad 500S-13ISK 80Q2           | 1         | 0.81%   |
| Lenovo B5400 s20278Q                     | 1         | 0.81%   |
| Lenovo B50-30 20382                      | 1         | 0.81%   |
| Khadas VIM3                              | 1         | 0.81%   |
| HUAWEI NBLK-WAX9X                        | 1         | 0.81%   |
| HUAWEI NBLB-WAX9N                        | 1         | 0.81%   |
| HUAWEI KLVL-WXX9                         | 1         | 0.81%   |
| HP ProDesk 400 G7 Microtower PC          | 1         | 0.81%   |
| HP ProBook 650 G4                        | 1         | 0.81%   |
| HP Pavilion Laptop 15-cw1xxx             | 1         | 0.81%   |
| HP Pavilion g4                           | 1         | 0.81%   |
| HP Pavilion Desktop 590-p0xxx            | 1         | 0.81%   |
| HP OMEN by HP Laptop                     | 1         | 0.81%   |
| HP Notebook                              | 1         | 0.81%   |
| HP Mini 110-3000                         | 1         | 0.81%   |
| HP kip                                   | 1         | 0.81%   |
| HP EliteDesk 800 G1 SFF                  | 1         | 0.81%   |
| HP Compaq Presario CQ61                  | 1         | 0.81%   |
| HP 255 G7 Notebook PC                    | 1         | 0.81%   |
| Gigabyte X470 AORUS ULTRA GAMING         | 1         | 0.81%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 8         | 6.45%   |
| Acer Aspire            | 5         | 4.03%   |
| Dell Precision         | 4         | 3.23%   |
| Toshiba Satellite      | 3         | 2.42%   |
| Lenovo IdeaPad         | 3         | 2.42%   |
| HP Pavilion            | 3         | 2.42%   |
| HP Compaq              | 3         | 2.42%   |
| Dell Latitude          | 3         | 2.42%   |
| Dell Inspiron          | 3         | 2.42%   |
| ASUS VivoBook          | 3         | 2.42%   |
| ASUS ROG               | 3         | 2.42%   |
| Lenovo ThinkCentre     | 2         | 1.61%   |
| Dell OptiPlex          | 2         | 1.61%   |
| ASUS TUF               | 2         | 1.61%   |
| ASUS PRIME             | 2         | 1.61%   |
| VIT P3400              | 1         | 0.81%   |
| Supermicro X8DTH-i     | 1         | 0.81%   |
| sunxi Libre            | 1         | 0.81%   |
| Sony VPCSB1V9R         | 1         | 0.81%   |
| Sony VGN-NR38E         | 1         | 0.81%   |
| Sony VGN-NR11Z         | 1         | 0.81%   |
| Sony VGN-N11M          | 1         | 0.81%   |
| Samsung R530           | 1         | 0.81%   |
| Razer Blade            | 1         | 0.81%   |
| PCChips P49G           | 1         | 0.81%   |
| NCR 7606-1309-8801     | 1         | 0.81%   |
| Multilaser UB32X       | 1         | 0.81%   |
| MSI MS-7C37            | 1         | 0.81%   |
| MSI MS-7A34            | 1         | 0.81%   |
| MSI MS-7982            | 1         | 0.81%   |
| MSI MS-7917            | 1         | 0.81%   |
| MSI MS-1034            | 1         | 0.81%   |
| MiTAC PD14RI           | 1         | 0.81%   |
| Medion E62009          | 1         | 0.81%   |
| Medion E14303          | 1         | 0.81%   |
| LG R710-S.APSAG        | 1         | 0.81%   |
| Lenovo ThinkBook       | 1         | 0.81%   |
| Lenovo MIIX            | 1         | 0.81%   |
| Lenovo B5400           | 1         | 0.81%   |
| Lenovo B50-30          | 1         | 0.81%   |
| Khadas VIM3            | 1         | 0.81%   |
| HUAWEI NBLK-WAX9X      | 1         | 0.81%   |
| HUAWEI NBLB-WAX9N      | 1         | 0.81%   |
| HUAWEI KLVL-WXX9       | 1         | 0.81%   |
| HP ProDesk             | 1         | 0.81%   |
| HP ProBook             | 1         | 0.81%   |
| HP OMEN                | 1         | 0.81%   |
| HP Notebook            | 1         | 0.81%   |
| HP Mini                | 1         | 0.81%   |
| HP kip                 | 1         | 0.81%   |
| HP EliteDesk           | 1         | 0.81%   |
| HP 255                 | 1         | 0.81%   |
| Gigabyte X470          | 1         | 0.81%   |
| Gigabyte M68MT-D3P     | 1         | 0.81%   |
| Gigabyte H510M         | 1         | 0.81%   |
| Gigabyte H370HD3       | 1         | 0.81%   |
| Gigabyte GA-990FXA-D3  | 1         | 0.81%   |
| Gigabyte GA-78LMT-USB3 | 1         | 0.81%   |
| Gigabyte B450          | 1         | 0.81%   |
| Fujitsu Siemens AMILO  | 1         | 0.81%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 18        | 14.52%  |
| 2021    | 15        | 12.1%   |
| 2011    | 15        | 12.1%   |
| 2010    | 10        | 8.06%   |
| 2019    | 9         | 7.26%   |
| 2018    | 9         | 7.26%   |
| 2008    | 8         | 6.45%   |
| 2014    | 7         | 5.65%   |
| 2016    | 5         | 4.03%   |
| 2015    | 5         | 4.03%   |
| 2012    | 5         | 4.03%   |
| 2007    | 5         | 4.03%   |
| 2006    | 4         | 3.23%   |
| 2013    | 3         | 2.42%   |
| 2009    | 3         | 2.42%   |
| Unknown | 2         | 1.61%   |
| 2017    | 1         | 0.81%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 69        | 55.65%  |
| Desktop        | 48        | 38.71%  |
| Server         | 3         | 2.42%   |
| System on chip | 2         | 1.61%   |
| Tablet         | 1         | 0.81%   |
| All in one     | 1         | 0.81%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 119       | 95.97%  |
| Enabled  | 5         | 4.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 123       | 99.19%  |
| Yes  | 1         | 0.81%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 30        | 24.19%  |
| 16.01-24.0  | 26        | 20.97%  |
| 8.01-16.0   | 20        | 16.13%  |
| 3.01-4.0    | 18        | 14.52%  |
| 1.01-2.0    | 12        | 9.68%   |
| 2.01-3.0    | 8         | 6.45%   |
| 32.01-64.0  | 5         | 4.03%   |
| 64.01-256.0 | 3         | 2.42%   |
| 24.01-32.0  | 1         | 0.81%   |
| 0.51-1.0    | 1         | 0.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 52        | 41.94%  |
| 0.51-1.0  | 20        | 16.13%  |
| 4.01-8.0  | 18        | 14.52%  |
| 2.01-3.0  | 17        | 13.71%  |
| 3.01-4.0  | 12        | 9.68%   |
| 8.01-16.0 | 4         | 3.23%   |
| 0.01-0.5  | 1         | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 71        | 57.26%  |
| 2      | 32        | 25.81%  |
| 3      | 11        | 8.87%   |
| 4      | 6         | 4.84%   |
| 0      | 2         | 1.61%   |
| 8      | 1         | 0.81%   |
| 5      | 1         | 0.81%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 52.42%  |
| No        | 59        | 47.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 87.9%   |
| No        | 15        | 12.1%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 70.97%  |
| No        | 36        | 29.03%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 50%     |
| No        | 62        | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 21        | 16.94%  |
| USA          | 17        | 13.71%  |
| France       | 15        | 12.1%   |
| Canada       | 10        | 8.06%   |
| Spain        | 6         | 4.84%   |
| Russia       | 6         | 4.84%   |
| Italy        | 5         | 4.03%   |
| UK           | 4         | 3.23%   |
| Netherlands  | 4         | 3.23%   |
| Costa Rica   | 3         | 2.42%   |
| Brazil       | 3         | 2.42%   |
| Sweden       | 2         | 1.61%   |
| Romania      | 2         | 1.61%   |
| Poland       | 2         | 1.61%   |
| Mexico       | 2         | 1.61%   |
| Hungary      | 2         | 1.61%   |
| Greece       | 2         | 1.61%   |
| Czechia      | 2         | 1.61%   |
| Australia    | 2         | 1.61%   |
| Argentina    | 2         | 1.61%   |
| Venezuela    | 1         | 0.81%   |
| Uruguay      | 1         | 0.81%   |
| Ukraine      | 1         | 0.81%   |
| South Africa | 1         | 0.81%   |
| Portugal     | 1         | 0.81%   |
| Norway       | 1         | 0.81%   |
| Malaysia     | 1         | 0.81%   |
| Indonesia    | 1         | 0.81%   |
| Iceland      | 1         | 0.81%   |
| Guadeloupe   | 1         | 0.81%   |
| Finland      | 1         | 0.81%   |
| Egypt        | 1         | 0.81%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Qu?©bec               | 5         | 4.03%   |
| Madrid                | 3         | 2.42%   |
| Hamburg               | 3         | 2.42%   |
| Saint-Quentin         | 2         | 1.61%   |
| Oldenburg             | 2         | 1.61%   |
| Garland               | 2         | 1.61%   |
| Bucharest             | 2         | 1.61%   |
| Bonn                  | 2         | 1.61%   |
| Berlin                | 2         | 1.61%   |
| Barcelona             | 2         | 1.61%   |
| Yuma                  | 1         | 0.81%   |
| Yoshkar-Ola           | 1         | 0.81%   |
| Wilderness Rim        | 1         | 0.81%   |
| Vlaardingen           | 1         | 0.81%   |
| Vitry-sur-Seine       | 1         | 0.81%   |
| Villa Ballester       | 1         | 0.81%   |
| Vilanova i la Geltr?? | 1         | 0.81%   |
| V?¤ster??s            | 1         | 0.81%   |
| Ufa                   | 1         | 0.81%   |
| Turrialba             | 1         | 0.81%   |
| Toms River            | 1         | 0.81%   |
| Stavanger             | 1         | 0.81%   |
| St Petersburg         | 1         | 0.81%   |
| Six-Fours-les-Plages  | 1         | 0.81%   |
| Serra de' Conti       | 1         | 0.81%   |
| Serpukhov             | 1         | 0.81%   |
| Semmes                | 1         | 0.81%   |
| Seelze                | 1         | 0.81%   |
| S??o Paulo            | 1         | 0.81%   |
| Santa Rosa            | 1         | 0.81%   |
| Sankt Augustin        | 1         | 0.81%   |
| San Juan              | 1         | 0.81%   |
| Salvador              | 1         | 0.81%   |
| Rosario               | 1         | 0.81%   |
| Riviere-Rouge         | 1         | 0.81%   |
| Reykjavik             | 1         | 0.81%   |
| Rennes                | 1         | 0.81%   |
| Rastatt               | 1         | 0.81%   |
| Pretoria              | 1         | 0.81%   |
| Prague                | 1         | 0.81%   |
| Peterborough          | 1         | 0.81%   |
| Perth                 | 1         | 0.81%   |
| Perpignan             | 1         | 0.81%   |
| Paris                 | 1         | 0.81%   |
| Pabianice             | 1         | 0.81%   |
| Oulu                  | 1         | 0.81%   |
| New York              | 1         | 0.81%   |
| Nagold                | 1         | 0.81%   |
| Munich                | 1         | 0.81%   |
| Moyock                | 1         | 0.81%   |
| Moscow                | 1         | 0.81%   |
| Montreal              | 1         | 0.81%   |
| Montevideo            | 1         | 0.81%   |
| Milan                 | 1         | 0.81%   |
| Miami                 | 1         | 0.81%   |
| Mexico City           | 1         | 0.81%   |
| Mesa                  | 1         | 0.81%   |
| Melbourne             | 1         | 0.81%   |
| Mansfield             | 1         | 0.81%   |
| Manchester            | 1         | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 31        | 35     | 17.03%  |
| WDC                   | 21        | 25     | 11.54%  |
| Samsung Electronics   | 20        | 23     | 10.99%  |
| Toshiba               | 14        | 14     | 7.69%   |
| Kingston              | 11        | 11     | 6.04%   |
| Unknown               | 9         | 10     | 4.95%   |
| Crucial               | 9         | 10     | 4.95%   |
| SanDisk               | 7         | 7      | 3.85%   |
| Hitachi               | 6         | 6      | 3.3%    |
| HGST                  | 6         | 8      | 3.3%    |
| Intel                 | 5         | 8      | 2.75%   |
| Fujitsu               | 5         | 5      | 2.75%   |
| Phison                | 3         | 3      | 1.65%   |
| MAXTOR                | 3         | 3      | 1.65%   |
| Intenso               | 3         | 3      | 1.65%   |
| A-DATA Technology     | 3         | 3      | 1.65%   |
| SK Hynix              | 2         | 2      | 1.1%    |
| PNY                   | 2         | 2      | 1.1%    |
| Micron Technology     | 2         | 2      | 1.1%    |
| Apple                 | 2         | 2      | 1.1%    |
| UMIS                  | 1         | 1      | 0.55%   |
| SPCC                  | 1         | 2      | 0.55%   |
| S3+                   | 1         | 1      | 0.55%   |
| Realtek Semiconductor | 1         | 1      | 0.55%   |
| OCZ                   | 1         | 1      | 0.55%   |
| Mushkin               | 1         | 1      | 0.55%   |
| LITEONIT              | 1         | 1      | 0.55%   |
| LITEON                | 1         | 1      | 0.55%   |
| LaCie                 | 1         | 1      | 0.55%   |
| KIOXIA                | 1         | 1      | 0.55%   |
| ICY BOX               | 1         | 1      | 0.55%   |
| HUAWEI                | 1         | 1      | 0.55%   |
| GOODRAM               | 1         | 1      | 0.55%   |
| Gigabyte Technology   | 1         | 1      | 0.55%   |
| DOGFISH               | 1         | 1      | 0.55%   |
| China                 | 1         | 1      | 0.55%   |
| ASMT                  | 1         | 1      | 0.55%   |
| Apacer                | 1         | 1      | 0.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Kingston SA400S37480G 480GB SSD       | 4         | 2.03%   |
| Unknown MMC Card  16GB                | 3         | 1.52%   |
| Intel HBRPEKNX0202AO 32GB             | 3         | 1.52%   |
| Intel HBRPEKNX0202A 512GB             | 3         | 1.52%   |
| HGST HTS541010A9E680 1TB              | 3         | 1.52%   |
| Crucial CT1000MX500SSD1 1TB           | 3         | 1.52%   |
| WDC WD10JPVT-00A1YT0 1TB              | 2         | 1.02%   |
| Unknown MMC Card  32GB                | 2         | 1.02%   |
| Toshiba NVMe SSD Drive 256GB          | 2         | 1.02%   |
| Toshiba MQ01ABF050 500GB              | 2         | 1.02%   |
| Seagate ST1000DM010-2EP102 1TB        | 2         | 1.02%   |
| Seagate Expansion 1TB                 | 2         | 1.02%   |
| Samsung SSD 860 EVO 250GB             | 2         | 1.02%   |
| Samsung SSD 850 EVO 250GB             | 2         | 1.02%   |
| Samsung NVMe SSD Drive 1TB            | 2         | 1.02%   |
| Kingston SV300S37A60G 64GB SSD        | 2         | 1.02%   |
| Kingston SA400S37240G 240GB SSD       | 2         | 1.02%   |
| Intenso External USB 3.0 4TB          | 2         | 1.02%   |
| Fujitsu MHZ2160BH G2 160GB            | 2         | 1.02%   |
| Crucial CT500MX500SSD1 500GB          | 2         | 1.02%   |
| WDC WDS500G2B0A-00SM50 500GB SSD      | 1         | 0.51%   |
| WDC WDS250G2B0A-00SM50 250GB SSD      | 1         | 0.51%   |
| WDC WD7500BPVX-60JC3T0 752GB          | 1         | 0.51%   |
| WDC WD5002ABYS-02B1B0 500GB           | 1         | 0.51%   |
| WDC WD5000AAKX-22ERMA0 500GB          | 1         | 0.51%   |
| WDC WD5000AAKS-07YGA0 500GB           | 1         | 0.51%   |
| WDC WD5000AAKS-00UU3A0 500GB          | 1         | 0.51%   |
| WDC WD40EZRZ-75GXCB0 4TB              | 1         | 0.51%   |
| WDC WD3201ABYS-01B9A0 320GB           | 1         | 0.51%   |
| WDC WD3200BEVT-22ZCT0 320GB           | 1         | 0.51%   |
| WDC WD3200BEVS-26VAT0 320GB           | 1         | 0.51%   |
| WDC WD3200AAJB-00J3A0 320GB           | 1         | 0.51%   |
| WDC WD2500BEVT-22A23T0 250GB          | 1         | 0.51%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 1         | 0.51%   |
| WDC WD1600JS-00MHB0 160GB             | 1         | 0.51%   |
| WDC WD1600AABS-00H4A0 160GB           | 1         | 0.51%   |
| WDC WD1502FYPS-02W3B0 1TB             | 1         | 0.51%   |
| WDC WD10SPCX-24HWST1 1TB              | 1         | 0.51%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 0.51%   |
| WDC WD10EFRX-68FYTN0 1TB              | 1         | 0.51%   |
| WDC WD1001FAES-75W7A0 1TB             | 1         | 0.51%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB    | 1         | 0.51%   |
| WDC PC SN530 NVMe 512GB               | 1         | 0.51%   |
| Unknown SL16G  16GB                   | 1         | 0.51%   |
| Unknown SABRENT SABRENT 500GB         | 1         | 0.51%   |
| Unknown S11-256G-PHISON-SSD-B27 256GB | 1         | 0.51%   |
| Unknown MMC Card  128GB               | 1         | 0.51%   |
| Unknown 00000  2GB                    | 1         | 0.51%   |
| UMIS RPJTJ256MEE1OWX 256GB            | 1         | 0.51%   |
| Toshiba THNSN5512GPU7 512GB           | 1         | 0.51%   |
| Toshiba Q300. 120GB SSD               | 1         | 0.51%   |
| Toshiba MQ01ABD100 1TB                | 1         | 0.51%   |
| Toshiba MK8032GSX 80GB                | 1         | 0.51%   |
| Toshiba MK5076GSX 500GB               | 1         | 0.51%   |
| Toshiba MK5065GSXN 500GB              | 1         | 0.51%   |
| Toshiba MK5065GSX 500GB               | 1         | 0.51%   |
| Toshiba KXG60ZNV512G 512GB            | 1         | 0.51%   |
| Toshiba KBG40ZNT256G MEMORY 256GB     | 1         | 0.51%   |
| Toshiba HDWD110 1TB                   | 1         | 0.51%   |
| SPCC Solid State Disk 512GB           | 1         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 35     | 36.47%  |
| WDC                 | 17        | 21     | 20%     |
| Toshiba             | 8         | 8      | 9.41%   |
| Hitachi             | 6         | 6      | 7.06%   |
| HGST                | 6         | 8      | 7.06%   |
| Fujitsu             | 5         | 5      | 5.88%   |
| Samsung Electronics | 4         | 4      | 4.71%   |
| MAXTOR              | 3         | 3      | 3.53%   |
| Intenso             | 2         | 2      | 2.35%   |
| LaCie               | 1         | 1      | 1.18%   |
| ICY BOX             | 1         | 1      | 1.18%   |
| Apple               | 1         | 1      | 1.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 10        | 10     | 16.95%  |
| Crucial             | 9         | 10     | 15.25%  |
| Samsung Electronics | 8         | 9      | 13.56%  |
| SanDisk             | 7         | 7      | 11.86%  |
| WDC                 | 2         | 2      | 3.39%   |
| PNY                 | 2         | 2      | 3.39%   |
| Micron Technology   | 2         | 2      | 3.39%   |
| Intel               | 2         | 2      | 3.39%   |
| A-DATA Technology   | 2         | 2      | 3.39%   |
| Unknown             | 1         | 1      | 1.69%   |
| Toshiba             | 1         | 1      | 1.69%   |
| SPCC                | 1         | 2      | 1.69%   |
| S3+                 | 1         | 1      | 1.69%   |
| OCZ                 | 1         | 1      | 1.69%   |
| Mushkin             | 1         | 1      | 1.69%   |
| LITEONIT            | 1         | 1      | 1.69%   |
| LITEON              | 1         | 1      | 1.69%   |
| Intenso             | 1         | 1      | 1.69%   |
| GOODRAM             | 1         | 1      | 1.69%   |
| DOGFISH             | 1         | 1      | 1.69%   |
| China               | 1         | 1      | 1.69%   |
| ASMT                | 1         | 1      | 1.69%   |
| Apple               | 1         | 1      | 1.69%   |
| Apacer              | 1         | 1      | 1.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 69        | 95     | 43.4%   |
| SSD     | 53        | 62     | 33.33%  |
| NVMe    | 28        | 34     | 17.61%  |
| MMC     | 7         | 8      | 4.4%    |
| Unknown | 2         | 2      | 1.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 100       | 148    | 69.44%  |
| NVMe | 28        | 34     | 19.44%  |
| SAS  | 9         | 11     | 6.25%   |
| MMC  | 7         | 8      | 4.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 84        | 108    | 68.85%  |
| 0.51-1.0   | 27        | 34     | 22.13%  |
| 1.01-2.0   | 6         | 7      | 4.92%   |
| 3.01-4.0   | 3         | 5      | 2.46%   |
| 2.01-3.0   | 1         | 2      | 0.82%   |
| 4.01-10.0  | 1         | 1      | 0.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 46        | 37.1%   |
| 251-500        | 28        | 22.58%  |
| 51-100         | 15        | 12.1%   |
| 501-1000       | 11        | 8.87%   |
| 21-50          | 8         | 6.45%   |
| 1001-2000      | 6         | 4.84%   |
| 1-20           | 4         | 3.23%   |
| More than 3000 | 3         | 2.42%   |
| 2001-3000      | 3         | 2.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 49        | 39.52%  |
| 101-250        | 23        | 18.55%  |
| 21-50          | 22        | 17.74%  |
| 51-100         | 11        | 8.87%   |
| 251-500        | 10        | 8.06%   |
| 501-1000       | 4         | 3.23%   |
| More than 3000 | 2         | 1.61%   |
| 2001-3000      | 2         | 1.61%   |
| 1001-2000      | 1         | 0.81%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD1600AABS-00H4A0 160GB                         | 1         | 1      | 8.33%   |
| WDC WD10SPCX-24HWST1 1TB                            | 1         | 1      | 8.33%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 1      | 8.33%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 8.33%   |
| Toshiba MK5076GSX 500GB                             | 1         | 1      | 8.33%   |
| Toshiba MK5065GSXN 500GB                            | 1         | 1      | 8.33%   |
| Toshiba MK5065GSX 500GB                             | 1         | 1      | 8.33%   |
| Seagate ST3320620AS 320GB                           | 1         | 1      | 8.33%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 8.33%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 8.33%   |
| ICY BOX IB-250StU3+BH15 2TB                         | 1         | 1      | 8.33%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 4         | 4      | 33.33%  |
| WDC               | 3         | 3      | 25%     |
| Seagate           | 2         | 2      | 16.67%  |
| Micron Technology | 1         | 1      | 8.33%   |
| ICY BOX           | 1         | 1      | 8.33%   |
| HGST              | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 4      | 36.36%  |
| WDC     | 3         | 3      | 27.27%  |
| Seagate | 2         | 2      | 18.18%  |
| ICY BOX | 1         | 1      | 9.09%   |
| HGST    | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 11     | 91.67%  |
| SSD  | 1         | 1      | 8.33%   |

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
| Detected | 78        | 123    | 57.78%  |
| Works    | 45        | 66     | 33.33%  |
| Malfunc  | 12        | 12     | 8.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 90        | 61.22%  |
| AMD                          | 17        | 11.56%  |
| Samsung Electronics          | 9         | 6.12%   |
| Toshiba America Info Systems | 4         | 2.72%   |
| Phison Electronics           | 4         | 2.72%   |
| Nvidia                       | 4         | 2.72%   |
| SK Hynix                     | 2         | 1.36%   |
| Silicon Image                | 2         | 1.36%   |
| Sandisk                      | 2         | 1.36%   |
| KIOXIA                       | 2         | 1.36%   |
| ASMedia Technology           | 2         | 1.36%   |
| VIA Technologies             | 1         | 0.68%   |
| Union Memory (Shenzhen)      | 1         | 0.68%   |
| Realtek Semiconductor        | 1         | 0.68%   |
| LSI Logic / Symbios Logic    | 1         | 0.68%   |
| Kingston Technology Company  | 1         | 0.68%   |
| JMicron Technology           | 1         | 0.68%   |
| Broadcom / LSI               | 1         | 0.68%   |
| ADATA Technology             | 1         | 0.68%   |
| Adaptec                      | 1         | 0.68%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 11        | 5.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 8         | 4.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 7         | 3.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 2.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 2.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 2.16%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4         | 2.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 2.16%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 4         | 2.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 2.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 2.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 2.16%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 4         | 2.16%   |
| Phison PS5013 E13 NVMe Controller                                                | 3         | 1.62%   |
| Intel Non-Volatile memory controller                                             | 3         | 1.62%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.62%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 3         | 1.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 1.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 3         | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3         | 1.62%   |
| AMD 400 Series Chipset SATA Controller                                           | 3         | 1.62%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 1.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.08%   |
| Nvidia MCP61 SATA Controller                                                     | 2         | 1.08%   |
| Nvidia CK804 Serial ATA Controller                                               | 2         | 1.08%   |
| Nvidia CK804 IDE                                                                 | 2         | 1.08%   |
| KIOXIA Non-Volatile memory controller                                            | 2         | 1.08%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 1.08%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 1.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.08%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.08%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 1.08%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 2         | 1.08%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1.08%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 2         | 1.08%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 1.08%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.08%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 2         | 1.08%   |
| AMD 300 Series Chipset SATA Controller                                           | 2         | 1.08%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.54%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 0.54%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.54%   |
| Toshiba America Info Systems NVMe Controller                                     | 1         | 0.54%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 0.54%   |
| SK Hynix Non-Volatile memory controller                                          | 1         | 0.54%   |
| SK Hynix Gold P31 SSD                                                            | 1         | 0.54%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                             | 1         | 0.54%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1         | 0.54%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.54%   |
| Sandisk Non-Volatile memory controller                                           | 1         | 0.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.54%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.54%   |
| Samsung Apple PCIe SSD                                                           | 1         | 0.54%   |
| Realtek Realtek Non-Volatile memory controller                                   | 1         | 0.54%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.54%   |
| Nvidia MCP61 IDE                                                                 | 1         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 84        | 53.5%   |
| IDE  | 32        | 20.38%  |
| NVMe | 27        | 17.2%   |
| RAID | 12        | 7.64%   |
| SAS  | 1         | 0.64%   |
| SCSI | 1         | 0.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 96        | 77.42%  |
| AMD    | 26        | 20.97%  |
| ARM    | 2         | 1.61%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 3.23%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 2         | 1.61%   |
| Intel Pentium 4 CPU 3.00GHz                   | 2         | 1.61%   |
| Intel Genuine CPU 575 @ 2.00GHz               | 2         | 1.61%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 2         | 1.61%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.61%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.61%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 2         | 1.61%   |
| Intel Core 2 CPU T5200 @ 1.60GHz              | 2         | 1.61%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.61%   |
| Intel Celeron CPU E3400 @ 2.60GHz             | 2         | 1.61%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.61%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 2         | 1.61%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz          | 1         | 0.81%   |
| Intel Xeon CPU E5530 @ 2.40GHz                | 1         | 0.81%   |
| Intel Xeon CPU E5-2623 v3 @ 3.00GHz           | 1         | 0.81%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz           | 1         | 0.81%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 1         | 0.81%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.81%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 1         | 0.81%   |
| Intel Pentium D CPU 3.40GHz                   | 1         | 0.81%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.81%   |
| Intel Pentium CPU J3710 @ 1.60GHz             | 1         | 0.81%   |
| Intel Pentium CPU G850 @ 2.90GHz              | 1         | 0.81%   |
| Intel Pentium CPU G2020 @ 2.90GHz             | 1         | 0.81%   |
| Intel Genuine CPU U4100 @ 1.30GHz             | 1         | 0.81%   |
| Intel Genuine CPU T2050 @ 1.60GHz             | 1         | 0.81%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz              | 1         | 0.81%   |
| Intel Core i9-9900 CPU @ 3.10GHz              | 1         | 0.81%   |
| Intel Core i9-10980HK CPU @ 2.40GHz           | 1         | 0.81%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 0.81%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1         | 0.81%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.81%   |
| Intel Core i7-7820HK CPU @ 2.90GHz            | 1         | 0.81%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.81%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 0.81%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.81%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1         | 0.81%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.81%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.81%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.81%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1         | 0.81%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.81%   |
| Intel Core i7-2820QM CPU @ 2.30GHz            | 1         | 0.81%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 1         | 0.81%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 0.81%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.81%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 0.81%   |
| Intel Core i7 CPU 920 @ 2.67GHz               | 1         | 0.81%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1         | 0.81%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 0.81%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 0.81%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 1         | 0.81%   |
| Intel Core i5-4310M CPU @ 2.70GHz             | 1         | 0.81%   |
| Intel Core i5-4278U CPU @ 2.60GHz             | 1         | 0.81%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.81%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 0.81%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 0.81%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 0.81%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 0.81%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 25        | 20.16%  |
| Intel Core i5           | 17        | 13.71%  |
| Intel Core i3           | 8         | 6.45%   |
| Intel Celeron           | 7         | 5.65%   |
| AMD Ryzen 5             | 7         | 5.65%   |
| Intel Pentium           | 4         | 3.23%   |
| Intel Genuine           | 4         | 3.23%   |
| Intel Atom              | 4         | 3.23%   |
| AMD Ryzen 7             | 4         | 3.23%   |
| Other                   | 3         | 2.42%   |
| Intel Xeon              | 3         | 2.42%   |
| Intel Pentium Dual-Core | 3         | 2.42%   |
| Intel Core 2 Duo        | 3         | 2.42%   |
| Intel Core 2            | 3         | 2.42%   |
| Intel Pentium Dual      | 2         | 1.61%   |
| Intel Pentium 4         | 2         | 1.61%   |
| Intel Core i9           | 2         | 1.61%   |
| Intel Core 2 Quad       | 2         | 1.61%   |
| AMD Ryzen 9             | 2         | 1.61%   |
| AMD Ryzen 3             | 2         | 1.61%   |
| AMD FX                  | 2         | 1.61%   |
| AMD Athlon II X2        | 2         | 1.61%   |
| Intel Xeon Silver       | 1         | 0.81%   |
| Intel Pentium D         | 1         | 0.81%   |
| Intel Core m7           | 1         | 0.81%   |
| Intel Core Duo          | 1         | 0.81%   |
| Intel Core 2 Extreme    | 1         | 0.81%   |
| ARM Allwinner           | 1         | 0.81%   |
| AMD Ryzen 7 PRO         | 1         | 0.81%   |
| AMD Phenom II X4        | 1         | 0.81%   |
| AMD E                   | 1         | 0.81%   |
| AMD Athlon II X4        | 1         | 0.81%   |
| AMD Athlon 64 X2        | 1         | 0.81%   |
| AMD Athlon 64           | 1         | 0.81%   |
| AMD Athlon              | 1         | 0.81%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 57        | 45.97%  |
| 4      | 30        | 24.19%  |
| 6      | 14        | 11.29%  |
| 8      | 11        | 8.87%   |
| 1      | 8         | 6.45%   |
| 20     | 1         | 0.81%   |
| 16     | 1         | 0.81%   |
| 12     | 1         | 0.81%   |
| 3      | 1         | 0.81%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 120       | 96.77%  |
| 2      | 4         | 3.23%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 76        | 61.29%  |
| 1      | 48        | 38.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 119       | 95.97%  |
| 32-bit         | 3         | 2.42%   |
| Unknown        | 2         | 1.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 14.52%  |
| 0x206a7    | 12        | 9.68%   |
| 0x6fd      | 6         | 4.84%   |
| 0xa0652    | 5         | 4.03%   |
| 0x1067a    | 5         | 4.03%   |
| 0x40651    | 4         | 3.23%   |
| 0x306a9    | 4         | 3.23%   |
| 0x6f6      | 3         | 2.42%   |
| 0x406e3    | 3         | 2.42%   |
| 0x306c3    | 3         | 2.42%   |
| 0x20655    | 3         | 2.42%   |
| 0x08701021 | 3         | 2.42%   |
| 0x0800820d | 3         | 2.42%   |
| 0xf43      | 2         | 1.61%   |
| 0x906ed    | 2         | 1.61%   |
| 0x906e9    | 2         | 1.61%   |
| 0x806ec    | 2         | 1.61%   |
| 0x506e3    | 2         | 1.61%   |
| 0x406c4    | 2         | 1.61%   |
| 0x30678    | 2         | 1.61%   |
| 0x106ca    | 2         | 1.61%   |
| 0x10676    | 2         | 1.61%   |
| 0x08600106 | 2         | 1.61%   |
| 0x08108109 | 2         | 1.61%   |
| 0x06000852 | 2         | 1.61%   |
| 0xf64      | 1         | 0.81%   |
| 0xa0655    | 1         | 0.81%   |
| 0xa0653    | 1         | 0.81%   |
| 0x906ea    | 1         | 0.81%   |
| 0x806eb    | 1         | 0.81%   |
| 0x806ea    | 1         | 0.81%   |
| 0x806e9    | 1         | 0.81%   |
| 0x806c1    | 1         | 0.81%   |
| 0x706e5    | 1         | 0.81%   |
| 0x6fb      | 1         | 0.81%   |
| 0x6ec      | 1         | 0.81%   |
| 0x6e8      | 1         | 0.81%   |
| 0x50654    | 1         | 0.81%   |
| 0x406f1    | 1         | 0.81%   |
| 0x306f2    | 1         | 0.81%   |
| 0x20652    | 1         | 0.81%   |
| 0x106c2    | 1         | 0.81%   |
| 0x106a5    | 1         | 0.81%   |
| 0x10677    | 1         | 0.81%   |
| 0x10661    | 1         | 0.81%   |
| 0x0a50000b | 1         | 0.81%   |
| 0x0a201016 | 1         | 0.81%   |
| 0x08600104 | 1         | 0.81%   |
| 0x08101016 | 1         | 0.81%   |
| 0x08001137 | 1         | 0.81%   |
| 0x05000119 | 1         | 0.81%   |
| 0x010000c8 | 1         | 0.81%   |
| 0x010000c7 | 1         | 0.81%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| SandyBridge | 13        | 10.48%  |
| KabyLake    | 11        | 8.87%   |
| Core        | 11        | 8.87%   |
| Haswell     | 10        | 8.06%   |
| Penryn      | 9         | 7.26%   |
| Zen 2       | 7         | 5.65%   |
| CometLake   | 7         | 5.65%   |
| Zen+        | 6         | 4.84%   |
| Skylake     | 6         | 4.84%   |
| Silvermont  | 6         | 4.84%   |
| Westmere    | 4         | 3.23%   |
| K10         | 4         | 3.23%   |
| IvyBridge   | 4         | 3.23%   |
| NetBurst    | 3         | 2.42%   |
| Bonnell     | 3         | 2.42%   |
| Unknown     | 3         | 2.42%   |
| Zen 3       | 2         | 1.61%   |
| Zen         | 2         | 1.61%   |
| Piledriver  | 2         | 1.61%   |
| P6          | 2         | 1.61%   |
| Nehalem     | 2         | 1.61%   |
| K8 Hammer   | 2         | 1.61%   |
| Broadwell   | 2         | 1.61%   |
| TigerLake   | 1         | 0.81%   |
| IceLake     | 1         | 0.81%   |
| Bobcat      | 1         | 0.81%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 73        | 50.69%  |
| Nvidia                     | 42        | 29.17%  |
| AMD                        | 27        | 18.75%  |
| Matrox Electronics Systems | 2         | 1.39%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 7.19%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 3.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 3.27%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 3.27%   |
| Nvidia TU117M                                                                            | 4         | 2.61%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 2.61%   |
| AMD Renoir                                                                               | 4         | 2.61%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 1.96%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.96%   |
| AMD Picasso                                                                              | 3         | 1.96%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 1.31%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2         | 1.31%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 1.31%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.31%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 2         | 1.31%   |
| Nvidia G92 [GeForce GTS 250]                                                             | 2         | 1.31%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.31%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.31%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.31%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.31%   |
| Intel HD Graphics 630                                                                    | 2         | 1.31%   |
| Intel HD Graphics 530                                                                    | 2         | 1.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.31%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.31%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.31%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 1.31%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.31%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.31%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.65%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.65%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 0.65%   |
| Nvidia NV34 [GeForce FX 5200]                                                            | 1         | 0.65%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.65%   |
| Nvidia GT218 [GeForce 310]                                                               | 1         | 0.65%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.65%   |
| Nvidia GT200GL [Quadro FX 3800]                                                          | 1         | 0.65%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.65%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.65%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.65%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.65%   |
| Nvidia GM107GL [Quadro K620]                                                             | 1         | 0.65%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1         | 0.65%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 0.65%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.65%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 0.65%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                                           | 1         | 0.65%   |
| Nvidia G98M [GeForce G 103M]                                                             | 1         | 0.65%   |
| Nvidia G98 [Quadro NVS 450]                                                              | 1         | 0.65%   |
| Nvidia G86M [Quadro NVS 135M]                                                            | 1         | 0.65%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1         | 0.65%   |
| Nvidia G80GL [Quadro FX 5600]                                                            | 1         | 0.65%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                            | 1         | 0.65%   |
| Nvidia G71M [GeForce Go 7950 GTX]                                                        | 1         | 0.65%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 0.65%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 0.65%   |
| Matrox Electronics Systems G200eR2                                                       | 1         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 54        | 43.55%  |
| 1 x Nvidia              | 27        | 21.77%  |
| 1 x AMD                 | 18        | 14.52%  |
| Intel + Nvidia          | 12        | 9.68%   |
| Intel + AMD             | 6         | 4.84%   |
| Other                   | 2         | 1.61%   |
| AMD + Nvidia            | 2         | 1.61%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.81%   |
| 2 x AMD                 | 1         | 0.81%   |
| 1 x Matrox              | 1         | 0.81%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 99        | 79.84%  |
| Proprietary | 22        | 17.74%  |
| Unknown     | 3         | 2.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 62        | 50%     |
| 0.01-0.5   | 23        | 18.55%  |
| 1.01-2.0   | 17        | 13.71%  |
| 0.51-1.0   | 7         | 5.65%   |
| 3.01-4.0   | 6         | 4.84%   |
| 7.01-8.0   | 3         | 2.42%   |
| 8.01-16.0  | 3         | 2.42%   |
| 2.01-3.0   | 2         | 1.61%   |
| 5.01-6.0   | 1         | 0.81%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 16        | 13.45%  |
| LG Display              | 14        | 11.76%  |
| Dell                    | 12        | 10.08%  |
| AU Optronics            | 10        | 8.4%    |
| BOE                     | 8         | 6.72%   |
| Chimei Innolux          | 7         | 5.88%   |
| Goldstar                | 5         | 4.2%    |
| Ancor Communications    | 5         | 4.2%    |
| Hewlett-Packard         | 4         | 3.36%   |
| ViewSonic               | 3         | 2.52%   |
| Sharp                   | 3         | 2.52%   |
| RTK                     | 2         | 1.68%   |
| LG Philips              | 2         | 1.68%   |
| Lenovo                  | 2         | 1.68%   |
| Iiyama                  | 2         | 1.68%   |
| HannStar                | 2         | 1.68%   |
| Chi Mei Optoelectronics | 2         | 1.68%   |
| Westinghouse            | 1         | 0.84%   |
| Unknown                 | 1         | 0.84%   |
| Toshiba                 | 1         | 0.84%   |
| TEO                     | 1         | 0.84%   |
| Sony                    | 1         | 0.84%   |
| SLD                     | 1         | 0.84%   |
| Seiko/Epson             | 1         | 0.84%   |
| Sceptre Tech            | 1         | 0.84%   |
| Philips                 | 1         | 0.84%   |
| MStar                   | 1         | 0.84%   |
| Lenovo Group Limited    | 1         | 0.84%   |
| InnoLux Display         | 1         | 0.84%   |
| Hyundai ImageQuest      | 1         | 0.84%   |
| Hitachi                 | 1         | 0.84%   |
| GDH                     | 1         | 0.84%   |
| FUS                     | 1         | 0.84%   |
| BenQ                    | 1         | 0.84%   |
| ASUSTek Computer        | 1         | 0.84%   |
| Apple                   | 1         | 0.84%   |
| Acer                    | 1         | 0.84%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch           | 3         | 2.5%    |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch   | 2         | 1.67%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch              | 2         | 1.67%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 2         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch        | 2         | 1.67%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch  | 2         | 1.67%   |
| Westinghouse SK-32H640G WDE6040 1440x900 710x400mm 32.1-inch           | 1         | 0.83%   |
| ViewSonic VX2478 Series VSCE032 2560x1440 526x296mm 23.8-inch          | 1         | 0.83%   |
| ViewSonic VP2000s VSC231A 1600x1200 408x306mm 20.1-inch                | 1         | 0.83%   |
| ViewSonic LCD Monitor VA1931 Series 1366x768                           | 1         | 0.83%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 1         | 0.83%   |
| Toshiba TV TSB0108 1920x1080 890x500mm 40.2-inch                       | 1         | 0.83%   |
| TEO TEO TL765 TEO6700 1280x1024 338x270mm 17.0-inch                    | 1         | 0.83%   |
| Sony TV SNYE903 1920x1080 1600x900mm 72.3-inch                         | 1         | 0.83%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                   | 1         | 0.83%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                | 1         | 0.83%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                | 1         | 0.83%   |
| Sharp LCD Monitor SHP1460 1920x1080 294x165mm 13.3-inch                | 1         | 0.83%   |
| Seiko/Epson LCD Monitor                                                | 1         | 0.83%   |
| Sceptre Tech E205W-1600 SPT080D 1600x900 477x268mm 21.5-inch           | 1         | 0.83%   |
| Samsung Electronics SyncMaster SAM03EF 1680x1050 433x271mm 20.1-inch   | 1         | 0.83%   |
| Samsung Electronics SyncMaster SAM001B 1280x1024 338x270mm 17.0-inch   | 1         | 0.83%   |
| Samsung Electronics SMS27A850 SAM083D 1280x1024 520x320mm 24.0-inch    | 1         | 0.83%   |
| Samsung Electronics Monitor SAM1035 1024x768 267x200mm 13.1-inch       | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 340x190mm 15.3-inch   | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 303x190mm 14.1-inch   | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch   | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch   | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 309x174mm 14.0-inch   | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch   | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch   | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch | 1         | 0.83%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 1         | 0.83%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                 | 1         | 0.83%   |
| RTK CPL AIO PC RTK2472 1920x1080 442x249mm 20.0-inch                   | 1         | 0.83%   |
| Philips 170S PHL0839 1280x1024 338x270mm 17.0-inch                     | 1         | 0.83%   |
| MStar TV_MONITOR MST0030 1440x900 1150x650mm 52.0-inch                 | 1         | 0.83%   |
| LG Philips LCD Monitor LPLC700 1280x800 331x207mm 15.4-inch            | 1         | 0.83%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch            | 1         | 0.83%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch            | 1         | 0.83%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD056D 1920x1080 380x210mm 17.1-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD04BA 1600x900 382x215mm 17.3-inch            | 1         | 0.83%   |
| LG Display LCD Monitor LGD048C 1920x1080 294x165mm 13.3-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD0470 1920x1080 345x194mm 15.6-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch            | 1         | 0.83%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch            | 1         | 0.83%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch            | 1         | 0.83%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 1         | 0.83%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch            | 1         | 0.83%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                | 1         | 0.83%   |
| Lenovo LCD Monitor LEN4022 1400x1050 287x215mm 14.1-inch               | 1         | 0.83%   |
| Lenovo Group Limited LCD Monitor 1600x900                              | 1         | 0.83%   |
| InnoLux Display LCD Monitor INL0005 1366x768 344x194mm 15.5-inch       | 1         | 0.83%   |
| Iiyama PLE485S IVM4822 1280x1024 376x301mm 19.0-inch                   | 1         | 0.83%   |
| Iiyama PL2792UH IVM664E 3840x2160 596x335mm 26.9-inch                  | 1         | 0.83%   |
| Hyundai ImageQuest HIQ T91D HIQ6D0B 1280x1024 304x228mm 15.0-inch      | 1         | 0.83%   |
| Hitachi X220W D-sub HIT6021 1680x1050 473x296mm 22.0-inch              | 1         | 0.83%   |
| Hewlett-Packard E233 HPN3460 1920x1080 509x286mm 23.0-inch             | 1         | 0.83%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 44        | 37.61%  |
| 1366x768 (WXGA)    | 25        | 21.37%  |
| 1280x1024 (SXGA)   | 8         | 6.84%   |
| 1600x900 (HD+)     | 6         | 5.13%   |
| 1680x1050 (WSXGA+) | 5         | 4.27%   |
| 1280x800 (WXGA)    | 5         | 4.27%   |
| 3840x2160 (4K)     | 4         | 3.42%   |
| 2560x1440 (QHD)    | 4         | 3.42%   |
| 1440x900 (WXGA+)   | 3         | 2.56%   |
| 1920x1200 (WUXGA)  | 2         | 1.71%   |
| 1024x600           | 2         | 1.71%   |
| 7680x2164          | 1         | 0.85%   |
| 5360x1440          | 1         | 0.85%   |
| 2560x1600          | 1         | 0.85%   |
| 2160x1440          | 1         | 0.85%   |
| 1920x540           | 1         | 0.85%   |
| 1600x1200          | 1         | 0.85%   |
| 1400x1050          | 1         | 0.85%   |
| 1024x768 (XGA)     | 1         | 0.85%   |
| Unknown            | 1         | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 28        | 23.53%  |
| 14      | 13        | 10.92%  |
| 13      | 12        | 10.08%  |
| Unknown | 11        | 9.24%   |
| 17      | 10        | 8.4%    |
| 24      | 7         | 5.88%   |
| 23      | 7         | 5.88%   |
| 21      | 5         | 4.2%    |
| 27      | 4         | 3.36%   |
| 19      | 4         | 3.36%   |
| 22      | 3         | 2.52%   |
| 20      | 3         | 2.52%   |
| 72      | 2         | 1.68%   |
| 32      | 2         | 1.68%   |
| 18      | 2         | 1.68%   |
| 10      | 2         | 1.68%   |
| 52      | 1         | 0.84%   |
| 48      | 1         | 0.84%   |
| 46      | 1         | 0.84%   |
| 25      | 1         | 0.84%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 50        | 42.02%  |
| 501-600     | 17        | 14.29%  |
| 401-500     | 15        | 12.61%  |
| Unknown     | 11        | 9.24%   |
| 351-400     | 9         | 7.56%   |
| 201-300     | 9         | 7.56%   |
| 1001-1500   | 3         | 2.52%   |
| 701-800     | 2         | 1.68%   |
| 1501-2000   | 2         | 1.68%   |
| 601-700     | 1         | 0.84%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 71        | 63.96%  |
| 16/10   | 16        | 14.41%  |
| Unknown | 11        | 9.91%   |
| 5/4     | 7         | 6.31%   |
| 4/3     | 4         | 3.6%    |
| 3/2     | 2         | 1.8%    |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inchÂ² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 28        | 23.73%  |
| 81-90          | 19        | 16.1%   |
| 201-250        | 18        | 15.25%  |
| Unknown        | 11        | 9.32%   |
| 151-200        | 7         | 5.93%   |
| 141-150        | 6         | 5.08%   |
| 121-130        | 5         | 4.24%   |
| More than 1000 | 4         | 3.39%   |
| 71-80          | 4         | 3.39%   |
| 301-350        | 4         | 3.39%   |
| 251-300        | 4         | 3.39%   |
| 351-500        | 2         | 1.69%   |
| 41-50          | 2         | 1.69%   |
| 91-100         | 2         | 1.69%   |
| 131-140        | 1         | 0.85%   |
| 501-1000       | 1         | 0.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 37        | 31.62%  |
| 101-120       | 32        | 27.35%  |
| 121-160       | 24        | 20.51%  |
| Unknown       | 11        | 9.4%    |
| 1-50          | 6         | 5.13%   |
| 161-240       | 6         | 5.13%   |
| More than 240 | 1         | 0.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 109       | 87.9%   |
| 2     | 11        | 8.87%   |
| 0     | 3         | 2.42%   |
| 3     | 1         | 0.81%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 62        | 33.7%   |
| Intel                           | 54        | 29.35%  |
| Qualcomm Atheros                | 23        | 12.5%   |
| Broadcom                        | 12        | 6.52%   |
| Marvell Technology Group        | 7         | 3.8%    |
| Nvidia                          | 4         | 2.17%   |
| Ralink Technology               | 3         | 1.63%   |
| Huawei Technologies             | 2         | 1.09%   |
| ASUSTek Computer                | 2         | 1.09%   |
| Aquantia                        | 2         | 1.09%   |
| Xiaomi                          | 1         | 0.54%   |
| VIA Technologies                | 1         | 0.54%   |
| TRENDnet                        | 1         | 0.54%   |
| Realtek                         | 1         | 0.54%   |
| Ralink                          | 1         | 0.54%   |
| Qualcomm Atheros Communications | 1         | 0.54%   |
| Microsoft                       | 1         | 0.54%   |
| MediaTek                        | 1         | 0.54%   |
| JMicron Technology              | 1         | 0.54%   |
| D-Link System                   | 1         | 0.54%   |
| Broadcom Limited                | 1         | 0.54%   |
| AVM                             | 1         | 0.54%   |
| ASIX Electronics                | 1         | 0.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 45        | 21.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 9         | 4.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 5         | 2.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 4         | 1.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 4         | 1.88%   |
| Intel Wi-Fi 6 AX200                                                                           | 4         | 1.88%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 4         | 1.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 4         | 1.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 3         | 1.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 3         | 1.41%   |
| Intel Wireless 7260                                                                           | 3         | 1.41%   |
| Intel Ethernet Connection I217-LM                                                             | 3         | 1.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 0.94%   |
| Realtek 802.11n WLAN Adapter                                                                  | 2         | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2         | 0.94%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 2         | 0.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 2         | 0.94%   |
| Nvidia MCP61 Ethernet                                                                         | 2         | 0.94%   |
| Nvidia CK804 Ethernet Controller                                                              | 2         | 0.94%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                                          | 2         | 0.94%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                                          | 2         | 0.94%   |
| Intel Wireless-AC 9260                                                                        | 2         | 0.94%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 0.94%   |
| Intel Wireless 7265                                                                           | 2         | 0.94%   |
| Intel Wireless 3165                                                                           | 2         | 0.94%   |
| Intel WiFi Link 5100                                                                          | 2         | 0.94%   |
| Intel I210 Gigabit Network Connection                                                         | 2         | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 2         | 0.94%   |
| Intel Centrino Ultimate-N 6300                                                                | 2         | 0.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 2         | 0.94%   |
| Intel 82579V Gigabit Network Connection                                                       | 2         | 0.94%   |
| Intel 82577LM Gigabit Network Connection                                                      | 2         | 0.94%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                             | 2         | 0.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 1         | 0.47%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                  | 1         | 0.47%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU]                    | 1         | 0.47%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 1         | 0.47%   |
| Realtek RTL8187 Wireless Adapter                                                              | 1         | 0.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 1         | 0.47%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 1         | 0.47%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.47%   |
| Realtek 802.11n NIC                                                                           | 1         | 0.47%   |
| Realtek 802.11n NIC                                                                           | 1         | 0.47%   |
| Ralink RT3072 Wireless Adapter                                                                | 1         | 0.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.47%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 0.47%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1         | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                     | 1         | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1         | 0.47%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 0.47%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                                 | 1         | 0.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 0.47%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 0.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 1         | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1         | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 1         | 0.47%   |
| Microsoft Wireless XBox Controller Dongle                                                     | 1         | 0.47%   |
| MediaTek SP-001                                                                               | 1         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 45.05%  |
| Qualcomm Atheros                | 20        | 21.98%  |
| Realtek Semiconductor           | 13        | 14.29%  |
| Broadcom                        | 5         | 5.49%   |
| Ralink Technology               | 3         | 3.3%    |
| ASUSTek Computer                | 2         | 2.2%    |
| TRENDnet                        | 1         | 1.1%    |
| Realtek                         | 1         | 1.1%    |
| Ralink                          | 1         | 1.1%    |
| Qualcomm Atheros Communications | 1         | 1.1%    |
| Microsoft                       | 1         | 1.1%    |
| Broadcom Limited                | 1         | 1.1%    |
| AVM                             | 1         | 1.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 5         | 5.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 4         | 4.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 4         | 4.35%   |
| Intel Wi-Fi 6 AX200                                                                           | 4         | 4.35%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 4         | 4.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 3.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 3         | 3.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 3         | 3.26%   |
| Intel Wireless 7260                                                                           | 3         | 3.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 2.17%   |
| Realtek 802.11n WLAN Adapter                                                                  | 2         | 2.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2         | 2.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 2         | 2.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 2         | 2.17%   |
| Intel Wireless-AC 9260                                                                        | 2         | 2.17%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 2.17%   |
| Intel Wireless 7265                                                                           | 2         | 2.17%   |
| Intel Wireless 3165                                                                           | 2         | 2.17%   |
| Intel WiFi Link 5100                                                                          | 2         | 2.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 2         | 2.17%   |
| Intel Centrino Ultimate-N 6300                                                                | 2         | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 2         | 2.17%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                             | 2         | 2.17%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU]                    | 1         | 1.09%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 1         | 1.09%   |
| Realtek RTL8187 Wireless Adapter                                                              | 1         | 1.09%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.09%   |
| Realtek 802.11n NIC                                                                           | 1         | 1.09%   |
| Realtek 802.11n NIC                                                                           | 1         | 1.09%   |
| Ralink RT3072 Wireless Adapter                                                                | 1         | 1.09%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 1.09%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 1.09%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1         | 1.09%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 1.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 1.09%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 1.09%   |
| Microsoft Wireless XBox Controller Dongle                                                     | 1         | 1.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1         | 1.09%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 1.09%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 1         | 1.09%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                  | 1         | 1.09%   |
| Intel Centrino Advanced-N 6235                                                                | 1         | 1.09%   |
| Intel Centrino Advanced-N 6200                                                                | 1         | 1.09%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                                          | 1         | 1.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 1         | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1         | 1.09%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 1         | 1.09%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 1         | 1.09%   |
| Broadcom BCM43227 802.11b/g/n                                                                 | 1         | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 1         | 1.09%   |
| AVM Fritz!WLAN N 2.4 [Atheros AR9001U]                                                        | 1         | 1.09%   |
| ASUS USB-AC56 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]                           | 1         | 1.09%   |
| ASUS 802.11n WLAN Adapter                                                                     | 1         | 1.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 56        | 47.46%  |
| Intel                    | 28        | 23.73%  |
| Broadcom                 | 8         | 6.78%   |
| Marvell Technology Group | 7         | 5.93%   |
| Qualcomm Atheros         | 6         | 5.08%   |
| Nvidia                   | 4         | 3.39%   |
| Aquantia                 | 2         | 1.69%   |
| Xiaomi                   | 1         | 0.85%   |
| VIA Technologies         | 1         | 0.85%   |
| MediaTek                 | 1         | 0.85%   |
| JMicron Technology       | 1         | 0.85%   |
| Huawei Technologies      | 1         | 0.85%   |
| D-Link System            | 1         | 0.85%   |
| ASIX Electronics         | 1         | 0.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 45        | 37.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 7.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 3.33%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 2.5%    |
| Nvidia MCP61 Ethernet                                                          | 2         | 1.67%   |
| Nvidia CK804 Ethernet Controller                                               | 2         | 1.67%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 2         | 1.67%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 2         | 1.67%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 1.67%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.67%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.83%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.83%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.83%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.83%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 1         | 0.83%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.83%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.83%   |
| MediaTek SP-001                                                                | 1         | 0.83%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.83%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1         | 0.83%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 0.83%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.83%   |
| Intel WiMAX Connection 2400m                                                   | 1         | 0.83%   |
| Intel PRO/100 VE Network Connection                                            | 1         | 0.83%   |
| Intel I211 Gigabit Network Connection                                          | 1         | 0.83%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.83%   |
| Intel Ethernet controller                                                      | 1         | 0.83%   |
| Intel Ethernet Connection I218-V                                               | 1         | 0.83%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.83%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.83%   |
| Intel Ethernet Connection (3) I219-LM                                          | 1         | 0.83%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 0.83%   |
| Intel 82576 Gigabit Network Connection                                         | 1         | 0.83%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.83%   |
| Intel 82567LF Gigabit Network Connection                                       | 1         | 0.83%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 1         | 0.83%   |
| Intel 82562V-2 10/100 Network Connection                                       | 1         | 0.83%   |
| Intel 82541GI Gigabit Ethernet Controller                                      | 1         | 0.83%   |
| Huawei BLA-L29                                                                 | 1         | 0.83%   |
| D-Link System RTL8139 Ethernet                                                 | 1         | 0.83%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                              | 1         | 0.83%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1         | 0.83%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 1         | 0.83%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 1         | 0.83%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 1         | 0.83%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                          | 1         | 0.83%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 1         | 0.83%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 0.83%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.83%   |
| Aquantia Ethernet controller                                                   | 1         | 0.83%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 1         | 0.83%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 109       | 55.05%  |
| WiFi     | 88        | 44.44%  |
| Modem    | 1         | 0.51%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 74        | 50%     |
| Ethernet | 74        | 50%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 70        | 56.45%  |
| 1     | 46        | 37.1%   |
| 0     | 5         | 4.03%   |
| 3     | 2         | 1.61%   |
| 4     | 1         | 0.81%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 94        | 75.81%  |
| Yes  | 30        | 24.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 40.32%  |
| Qualcomm Atheros Communications | 6         | 9.68%   |
| Cambridge Silicon Radio         | 6         | 9.68%   |
| Realtek Semiconductor           | 5         | 8.06%   |
| Broadcom                        | 4         | 6.45%   |
| Dell                            | 3         | 4.84%   |
| Realtek                         | 2         | 3.23%   |
| Lite-On Technology              | 2         | 3.23%   |
| IMC Networks                    | 2         | 3.23%   |
| Hewlett-Packard                 | 2         | 3.23%   |
| Foxconn / Hon Hai               | 2         | 3.23%   |
| Toshiba                         | 1         | 1.61%   |
| ASUSTek Computer                | 1         | 1.61%   |
| Apple                           | 1         | 1.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 7         | 11.29%  |
| Intel AX201 Bluetooth                                                               | 7         | 11.29%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 9.68%   |
| Intel AX200 Bluetooth                                                               | 4         | 6.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 4.84%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 3.23%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 3.23%   |
| Realtek Bluetooth Radio                                                             | 2         | 3.23%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 3.23%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 3.23%   |
| Lite-On Bluetooth Device                                                            | 2         | 3.23%   |
| Intel Bluetooth Device                                                              | 2         | 3.23%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 3.23%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 3.23%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 1.61%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.61%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 1.61%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.61%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.61%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 1.61%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.61%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 1.61%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 1.61%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 1.61%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.61%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 1.61%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 1.61%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 1.61%   |
| Apple Bluetooth Host Controller                                                     | 1         | 1.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 92        | 58.23%  |
| AMD                       | 27        | 17.09%  |
| Nvidia                    | 25        | 15.82%  |
| C-Media Electronics       | 2         | 1.27%   |
| VIA Technologies          | 1         | 0.63%   |
| Texas Instruments         | 1         | 0.63%   |
| TEAC                      | 1         | 0.63%   |
| Sennheiser Communications | 1         | 0.63%   |
| Realtek Semiconductor     | 1         | 0.63%   |
| GN Netcom                 | 1         | 0.63%   |
| Generalplus Technology    | 1         | 0.63%   |
| Focusrite-Novation        | 1         | 0.63%   |
| Creative Technology       | 1         | 0.63%   |
| ASUSTek Computer          | 1         | 0.63%   |
| Alesis                    | 1         | 0.63%   |
| AKAI Professional M.I.    | 1         | 0.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 13        | 7.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 6.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 5.56%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 8         | 4.44%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 3.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 3.33%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 2.78%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 2.78%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 2.78%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 2.78%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 2.22%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 2.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 2.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 2.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.22%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.67%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 1.67%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 1.11%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 1.11%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.11%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.11%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.11%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 2         | 1.11%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 1.11%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 2         | 1.11%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 1.11%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.11%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.11%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 2         | 1.11%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.56%   |
| Texas Instruments PCM2900C Audio CODEC                                                            | 1         | 0.56%   |
| TEAC SERIES 208i                                                                                  | 1         | 0.56%   |
| Sennheiser Communications SC60 for Lync                                                           | 1         | 0.56%   |
| Realtek Semiconductor TX-384Khz Hifi Type-C Audio                                                 | 1         | 0.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.56%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.56%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Nvidia CK804 AC'97 Audio Controller                                                               | 1         | 0.56%   |
| Nvidia Audio device                                                                               | 1         | 0.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.56%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.56%   |
| Intel Lewisburg MROM 0                                                                            | 1         | 0.56%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.56%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller                                    | 1         | 0.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.56%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1         | 0.56%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 0.56%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 0.56%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 0.56%   |
| GN Netcom Jabra EVOLVE 30 II                                                                      | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 18        | 21.95%  |
| Samsung Electronics | 17        | 20.73%  |
| Unknown             | 13        | 15.85%  |
| Kingston            | 10        | 12.2%   |
| Micron Technology   | 5         | 6.1%    |
| Crucial             | 5         | 6.1%    |
| A-DATA Technology   | 3         | 3.66%   |
| Ramaxel Technology  | 2         | 2.44%   |
| Nanya Technology    | 2         | 2.44%   |
| Elpida              | 2         | 2.44%   |
| Corsair             | 2         | 2.44%   |
| GEIL                | 1         | 1.22%   |
| G.Skill             | 1         | 1.22%   |
| Apacer              | 1         | 1.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 3         | 3.53%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 3         | 3.53%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB Row Of Chips DDR4 3200MT/s   | 2         | 2.35%   |
| Unknown RAM Module 8192MB SODIMM LPDDR3 1600MT/s                 | 1         | 1.18%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.18%   |
| Unknown RAM Module 4096MB DIMM DDR2 800MT/s                      | 1         | 1.18%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 1.18%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 1.18%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 1.18%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 1.18%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 1.18%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 1.18%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 1.18%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                         | 1         | 1.18%   |
| SK Hynix RAM Module 16384MB DIMM DDR4 3200MT/s                   | 1         | 1.18%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 1.18%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK Hynix RAM HMT125S6TFR8C-H9 2GB DIMM DDR2 1599MT/s             | 1         | 1.18%   |
| SK Hynix RAM HMT125R7AFP4C-H9 2048MB DIMM DDR3 1066MT/s          | 1         | 1.18%   |
| SK Hynix RAM HMP351S6AFR8C-S6 4GB SODIMM DDR 800MT/s             | 1         | 1.18%   |
| SK Hynix RAM HMP125U6EFR8C-S6 2048MB DIMM DDR2 800MT/s           | 1         | 1.18%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16384MB Row Of Chips DDR4 3200MT/s | 1         | 1.18%   |
| SK Hynix RAM HMAA1GS6CMR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s        | 1         | 1.18%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.18%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| SK Hynix RAM HMA81GR7MFR8N-UH 8192MB DIMM DDR4 2400MT/s          | 1         | 1.18%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 1         | 1.18%   |
| Samsung RAM M471B5674-H0-YK0--- 4096MB Chip DDR3 1600MT/s        | 1         | 1.18%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 1         | 1.18%   |
| Samsung RAM M471B2874EH1-CH9 1024MB SODIMM DDR3 1333MT/s         | 1         | 1.18%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.18%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.18%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.18%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.18%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.18%   |
| Samsung RAM M393A5143DB0-CPB 4GB DIMM 2133MT/s                   | 1         | 1.18%   |
| Samsung RAM M393A2K43BB1-CTD 16GB DIMM DDR4 2666MT/s             | 1         | 1.18%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s              | 1         | 1.18%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s              | 1         | 1.18%   |
| Samsung RAM K4UBE3D4AA-MGCL 8192MB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.18%   |
| Samsung RAM 16ATF2G64HZ-2G6H1 16GB SODIMM DDR4 2667MT/s          | 1         | 1.18%   |
| Ramaxel RAM RMT3170ME68F9F1600 4096MB SODIMM DDR3 1600MT/s       | 1         | 1.18%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 1.18%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 1         | 1.18%   |
| Nanya RAM NT2GT64U8HD0BN-AD 2GB SODIMM DDR2 975MT/s              | 1         | 1.18%   |
| Micron RAM Module 8192MB SODIMM DDR4 2400MT/s                    | 1         | 1.18%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                    | 1         | 1.18%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s         | 1         | 1.18%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 1.18%   |
| Micron RAM 16HTF25664AY-800E1 2048MB DIMM DDR2 800MT/s           | 1         | 1.18%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s                     | 1         | 1.18%   |
| Kingston RAM LV32D4S2S8HD-8 8192MB SODIMM DDR4 3200MT/s          | 1         | 1.18%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 1         | 1.18%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s                | 1         | 1.18%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 32        | 47.76%  |
| DDR3    | 18        | 26.87%  |
| DDR2    | 10        | 14.93%  |
| SDRAM   | 4         | 5.97%   |
| LPDDR4  | 1         | 1.49%   |
| LPDDR3  | 1         | 1.49%   |
| Unknown | 1         | 1.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 36        | 54.55%  |
| DIMM         | 25        | 37.88%  |
| Row Of Chips | 4         | 6.06%   |
| Chip         | 1         | 1.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 26        | 35.14%  |
| 4096  | 20        | 27.03%  |
| 2048  | 13        | 17.57%  |
| 16384 | 9         | 12.16%  |
| 1024  | 5         | 6.76%   |
| 32768 | 1         | 1.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 12        | 17.14%  |
| 3200    | 11        | 15.71%  |
| 2667    | 10        | 14.29%  |
| 800     | 5         | 7.14%   |
| Unknown | 5         | 7.14%   |
| 2400    | 4         | 5.71%   |
| 2666    | 3         | 4.29%   |
| 1334    | 3         | 4.29%   |
| 1333    | 3         | 4.29%   |
| 667     | 3         | 4.29%   |
| 4267    | 1         | 1.43%   |
| 4199    | 1         | 1.43%   |
| 3800    | 1         | 1.43%   |
| 3600    | 1         | 1.43%   |
| 3000    | 1         | 1.43%   |
| 2200    | 1         | 1.43%   |
| 2133    | 1         | 1.43%   |
| 2048    | 1         | 1.43%   |
| 1800    | 1         | 1.43%   |
| 1599    | 1         | 1.43%   |
| 1066    | 1         | 1.43%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)

![Printer Vendor](./images/line_chart/printer_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| QinHeng Electronics | 1         | 33.33%  |
| Kyocera             | 1         | 33.33%  |
| Brother Industries  | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)

![Printer Model](./images/line_chart/printer_model.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| QinHeng CH340S          | 1         | 33.33%  |
| Kyocera Mita FS-920     | 1         | 33.33%  |
| Brother HL-1210W series | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)

![Scanner Vendor](./images/line_chart/scanner_vendor.svg)

| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)

![Scanner Model](./images/line_chart/scanner_model.svg)

| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| HP ScanJet 3570c           | 1         | 50%     |
| Canon CanoScan N650U/N656U | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)

![Camera Vendor](./images/line_chart/camera_vendor.svg)

| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 12        | 18.75%  |
| IMC Networks                           | 11        | 17.19%  |
| Microdia                               | 7         | 10.94%  |
| Realtek Semiconductor                  | 6         | 9.38%   |
| Logitech                               | 4         | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 6.25%   |
| Acer                                   | 4         | 6.25%   |
| Suyin                                  | 2         | 3.13%   |
| Quanta                                 | 2         | 3.13%   |
| Lite-On Technology                     | 2         | 3.13%   |
| Alcor Micro                            | 2         | 3.13%   |
| Tobii AB                               | 1         | 1.56%   |
| Mimaki Engineering                     | 1         | 1.56%   |
| MacroSilicon                           | 1         | 1.56%   |
| LG Innotek                             | 1         | 1.56%   |
| Lenovo                                 | 1         | 1.56%   |
| DigiTech                               | 1         | 1.56%   |
| Creative Technology                    | 1         | 1.56%   |
| Apple                                  | 1         | 1.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony integrated camera                                                  | 4         | 6.25%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 4.69%   |
| IMC Networks Integrated Camera                                             | 3         | 4.69%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 3.13%   |
| Microdia USB 2.0 Camera                                                    | 2         | 3.13%   |
| Chicony CKF7063 Webcam (HP)                                                | 2         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 2         | 3.13%   |
| Tobii AB EyeChip                                                           | 1         | 1.56%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)                | 1         | 1.56%   |
| Suyin 1.3M HD WebCam                                                       | 1         | 1.56%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 1         | 1.56%   |
| Realtek USB Camera                                                         | 1         | 1.56%   |
| Realtek Integrated Webcam HD                                               | 1         | 1.56%   |
| Realtek 2SF022                                                             | 1         | 1.56%   |
| Quanta ov9734_techfront_camera                                             | 1         | 1.56%   |
| Quanta HP TrueVision HD Webcam                                             | 1         | 1.56%   |
| Mimaki Engineering HD WEB CAMERA                                           | 1         | 1.56%   |
| Microdia Webcam Vitade AF                                                  | 1         | 1.56%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 1         | 1.56%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.56%   |
| Microdia Integrated Webcam                                                 | 1         | 1.56%   |
| Microdia HP Integrated Webcam                                              | 1         | 1.56%   |
| MacroSilicon USB Video                                                     | 1         | 1.56%   |
| Logitech Webcam C930e                                                      | 1         | 1.56%   |
| Logitech Webcam C310                                                       | 1         | 1.56%   |
| Logitech Webcam C270                                                       | 1         | 1.56%   |
| Logitech HD Pro Webcam C920                                                | 1         | 1.56%   |
| Lite-On Integrated Camera                                                  | 1         | 1.56%   |
| Lite-On HP HD Camera                                                       | 1         | 1.56%   |
| LG Innotek LG Webcam                                                       | 1         | 1.56%   |
| Lenovo Integrated Webcam [R5U877]                                          | 1         | 1.56%   |
| IMC Networks XHC Camera                                                    | 1         | 1.56%   |
| IMC Networks UVC VGA Webcam                                                | 1         | 1.56%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                                        | 1         | 1.56%   |
| IMC Networks USB Camera                                                    | 1         | 1.56%   |
| IMC Networks ov9734_azurewave_camera                                       | 1         | 1.56%   |
| DigiTech USB 2.0 PC Camera                                                 | 1         | 1.56%   |
| Creative Live! Cam Chat HD [VF0700]                                        | 1         | 1.56%   |
| Chicony TOSHIBA Web Camera - HD                                            | 1         | 1.56%   |
| Chicony TOSHIBA Web Camera                                                 | 1         | 1.56%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 1.56%   |
| Chicony HP Wide Vision HD Camera                                           | 1         | 1.56%   |
| Chicony HD WebCam                                                          | 1         | 1.56%   |
| Chicony FJ Camera                                                          | 1         | 1.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 1.56%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                           | 1         | 1.56%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 1         | 1.56%   |
| Alcor Micro USB 2.0 Camera                                                 | 1         | 1.56%   |
| Alcor Micro HP Webcam                                                      | 1         | 1.56%   |
| Acer USB HD Webcam                                                         | 1         | 1.56%   |
| Acer Lenovo EasyCamera                                                     | 1         | 1.56%   |
| Acer Integrated Camera                                                     | 1         | 1.56%   |
| Acer HP Webcam-101                                                         | 1         | 1.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 40%     |
| Shenzhen Goodix Technology | 4         | 26.67%  |
| AuthenTec                  | 2         | 13.33%  |
| Upek                       | 1         | 6.67%   |
| Synaptics                  | 1         | 6.67%   |
| LighTuning Technology      | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                    | 4         | 26.67%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 3         | 20%     |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 13.33%  |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 6.67%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 6.67%   |
| AuthenTec Fingerprint Sensor                           | 1         | 6.67%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./images/line_chart/chipcard_vendor.svg)

| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| O2 Micro    | 3         | 42.86%  |
| Broadcom    | 3         | 42.86%  |
| Alcor Micro | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)

![Chipcard Model](./images/line_chart/chipcard_model.svg)

| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader           | 2         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor | 2         | 28.57%  |
| O2 Micro Oz776 SmartCard Reader                | 1         | 14.29%  |
| Broadcom 5880                                  | 1         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 92        | 74.19%  |
| 1     | 25        | 20.16%  |
| 2     | 6         | 4.84%   |
| 3     | 1         | 0.81%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 15        | 40.54%  |
| Chipcard                 | 7         | 18.92%  |
| Graphics card            | 5         | 13.51%  |
| Unassigned class         | 3         | 8.11%   |
| Net/wireless             | 2         | 5.41%   |
| Multimedia controller    | 2         | 5.41%   |
| Storage                  | 1         | 2.7%    |
| Net/ethernet             | 1         | 2.7%    |
| Communication controller | 1         | 2.7%    |

