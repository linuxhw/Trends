Arch Hardware Trends
--------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Arch users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Arch/Desktop/README.md) and [notebooks](/Dist/Arch/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/linuxhw/TestCoverage)

Period: Apr, 2022.

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

| Name         | Computers | Percent |
|--------------|-----------|---------|
| Arch         | 121       | 59.61%  |
| Arch Rolling | 82        | 40.39%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| Arch | 203       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.17.1-arch1-1               | 80        | 39.41%  |
| 5.17.1-zen1-1-zen            | 20        | 9.85%   |
| 5.17.4-arch1-1               | 15        | 7.39%   |
| 5.17.3-arch1-1               | 15        | 7.39%   |
| 5.17.2-arch3-1               | 14        | 6.9%    |
| 5.17.5-arch1-1               | 8         | 3.94%   |
| 5.15.33-1-lts                | 6         | 2.96%   |
| 5.15.32-1-lts                | 6         | 2.96%   |
| 5.16.16-arch1-1              | 5         | 2.46%   |
| 5.17.4-zen1-1-zen            | 3         | 1.48%   |
| 5.17.3-zen1-1-zen            | 3         | 1.48%   |
| 5.16.15-arch1-1              | 2         | 0.99%   |
| 5.16.13-arch1-1              | 2         | 0.99%   |
| 5.18.0-rc2-1-mainline        | 1         | 0.49%   |
| 5.18.0-rc1-252-tkg-cfs       | 1         | 0.49%   |
| 5.17.5.ll48-1-lin-git+       | 1         | 0.49%   |
| 5.17.5-zen1-1-zen            | 1         | 0.49%   |
| 5.17.5-lqx1-1-lqx            | 1         | 0.49%   |
| 5.17.4-256-tkg-pds           | 1         | 0.49%   |
| 5.17.4-256-tkg-cfs           | 1         | 0.49%   |
| 5.17.3-lqx2-1-lqx            | 1         | 0.49%   |
| 5.17.2-zen3-1.1-zen          | 1         | 0.49%   |
| 5.17.2-arch2-1-custom        | 1         | 0.49%   |
| 5.17.2                       | 1         | 0.49%   |
| 5.17.1-arch1-1.1             | 1         | 0.49%   |
| 5.17.0-247-tkg-pds           | 1         | 0.49%   |
| 5.16.5-arch1-1               | 1         | 0.49%   |
| 5.16.18-hardened1-1-hardened | 1         | 0.49%   |
| 5.16.18-1-ck-generic-v3      | 1         | 0.49%   |
| 5.16.17-hardened1-1-hardened | 1         | 0.49%   |
| 5.16.16-zen1-1-zen           | 1         | 0.49%   |
| 5.16.16-arch1-1-surface      | 1         | 0.49%   |
| 5.16.14-arch1-1              | 1         | 0.49%   |
| 5.16.11-xanmod0-rog-1        | 1         | 0.49%   |
| 5.15.36-1-lts                | 1         | 0.49%   |
| 5.15.35-1-lts                | 1         | 0.49%   |
| 5.15.13-arch1-1              | 1         | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.1  | 101       | 49.75%  |
| 5.17.4  | 20        | 9.85%   |
| 5.17.3  | 19        | 9.36%   |
| 5.17.2  | 17        | 8.37%   |
| 5.17.5  | 11        | 5.42%   |
| 5.16.16 | 7         | 3.45%   |
| 5.15.33 | 6         | 2.96%   |
| 5.15.32 | 6         | 2.96%   |
| 5.18.0  | 2         | 0.99%   |
| 5.16.18 | 2         | 0.99%   |
| 5.16.15 | 2         | 0.99%   |
| 5.16.13 | 2         | 0.99%   |
| 5.17.0  | 1         | 0.49%   |
| 5.16.5  | 1         | 0.49%   |
| 5.16.17 | 1         | 0.49%   |
| 5.16.14 | 1         | 0.49%   |
| 5.16.11 | 1         | 0.49%   |
| 5.15.36 | 1         | 0.49%   |
| 5.15.35 | 1         | 0.49%   |
| 5.15.13 | 1         | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17    | 169       | 83.25%  |
| 5.16    | 17        | 8.37%   |
| 5.15    | 15        | 7.39%   |
| 5.18    | 2         | 0.99%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 203       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 70        | 34.48%  |
| GNOME           | 53        | 26.11%  |
| Unknown         | 27        | 13.3%   |
| i3              | 16        | 7.88%   |
| XFCE            | 7         | 3.45%   |
| X-Cinnamon      | 6         | 2.96%   |
| sway            | 5         | 2.46%   |
| awesome         | 4         | 1.97%   |
| Budgie          | 3         | 1.48%   |
| LXQt            | 2         | 0.99%   |
| Deepin          | 2         | 0.99%   |
| Cinnamon        | 2         | 0.99%   |
| bspwm           | 2         | 0.99%   |
| xmonad          | 1         | 0.49%   |
| MATE            | 1         | 0.49%   |
| GNOME Flashback | 1         | 0.49%   |
| DWM             | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 118       | 58.13%  |
| Wayland | 46        | 22.66%  |
| Tty     | 22        | 10.84%  |
| Unknown | 17        | 8.37%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 79        | 38.92%  |
| SDDM    | 52        | 25.62%  |
| LightDM | 39        | 19.21%  |
| GDM     | 24        | 11.82%  |
| Ly      | 4         | 1.97%   |
| LXDM    | 3         | 1.48%   |
| GREETD  | 1         | 0.49%   |
| EMPTTY  | 1         | 0.49%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 114       | 56.16%  |
| en_GB       | 11        | 5.42%   |
| de_DE       | 11        | 5.42%   |
| Unknown     | 10        | 4.93%   |
| it_IT       | 7         | 3.45%   |
| en_IN       | 7         | 3.45%   |
| pt_BR       | 6         | 2.96%   |
| fr_FR       | 5         | 2.46%   |
| pl_PL       | 4         | 1.97%   |
| zh_CN       | 3         | 1.48%   |
| en_NZ       | 3         | 1.48%   |
| en_CA       | 3         | 1.48%   |
| ca_ES       | 3         | 1.48%   |
| ru_RU       | 2         | 0.99%   |
| C           | 2         | 0.99%   |
| vi_VN       | 1         | 0.49%   |
| szl_PL      | 1         | 0.49%   |
| nl_NL       | 1         | 0.49%   |
| ja_JP       | 1         | 0.49%   |
| es_MX       | 1         | 0.49%   |
| es_ES       | 1         | 0.49%   |
| es_CL       | 1         | 0.49%   |
| en_US-UTF-8 | 1         | 0.49%   |
| en_IE       | 1         | 0.49%   |
| en_AU       | 1         | 0.49%   |
| en_150      | 1         | 0.49%   |
| cs_CZ       | 1         | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 121       | 59.61%  |
| BIOS | 82        | 40.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 141       | 69.46%  |
| Btrfs | 50        | 24.63%  |
| Xfs   | 7         | 3.45%   |
| F2fs  | 3         | 1.48%   |
| Zfs   | 2         | 0.99%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 141       | 69.46%  |
| Unknown | 46        | 22.66%  |
| MBR     | 16        | 7.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 186       | 91.63%  |
| Yes       | 17        | 8.37%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 137       | 67.49%  |
| Yes       | 66        | 32.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 40        | 19.7%   |
| ASUSTek Computer       | 33        | 16.26%  |
| Dell                   | 26        | 12.81%  |
| MSI                    | 17        | 8.37%   |
| Hewlett-Packard        | 16        | 7.88%   |
| Gigabyte Technology    | 13        | 6.4%    |
| Acer                   | 12        | 5.91%   |
| ASRock                 | 7         | 3.45%   |
| Framework              | 5         | 2.46%   |
| Intel                  | 4         | 1.97%   |
| Apple                  | 4         | 1.97%   |
| TUXEDO                 | 3         | 1.48%   |
| Razer                  | 3         | 1.48%   |
| LG Electronics         | 2         | 0.99%   |
| HUAWEI                 | 2         | 0.99%   |
| Fujitsu                | 2         | 0.99%   |
| Alienware              | 2         | 0.99%   |
| Toshiba                | 1         | 0.49%   |
| Star Labs              | 1         | 0.49%   |
| Sony                   | 1         | 0.49%   |
| Samsung Electronics    | 1         | 0.49%   |
| OEM                    | 1         | 0.49%   |
| MouseComputer          | 1         | 0.49%   |
| Monster                | 1         | 0.49%   |
| Microsoft              | 1         | 0.49%   |
| Jetway                 | 1         | 0.49%   |
| Foxconn                | 1         | 0.49%   |
| EVGA                   | 1         | 0.49%   |
| Avell High Performance | 1         | 0.49%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Framework Laptop                                      | 5         | 2.46%   |
| ASUS All Series                                       | 4         | 1.97%   |
| MSI MS-7C37                                           | 2         | 0.99%   |
| Lenovo Legion 5 15IMH05H 81Y6                         | 2         | 0.99%   |
| Dell XPS 13 9310                                      | 2         | 0.99%   |
| ASUS TUF Gaming X570-PLUS                             | 2         | 0.99%   |
| TUXEDO Pulse 15 Gen1                                  | 1         | 0.49%   |
| TUXEDO InfinityBook Pro 14 Gen6                       | 1         | 0.49%   |
| TUXEDO Book_XA1510                                    | 1         | 0.49%   |
| Toshiba TECRA R940                                    | 1         | 0.49%   |
| Star Labs Lite                                        | 1         | 0.49%   |
| Sony VPCF115FM                                        | 1         | 0.49%   |
| Samsung 270E5J/2570EJ                                 | 1         | 0.49%   |
| Razer Blade Stealth                                   | 1         | 0.49%   |
| Razer Blade 15 Studio Edition (Early 2020) - RZ09-033 | 1         | 0.49%   |
| Razer Blade                                           | 1         | 0.49%   |
| OEM V1.0                                              | 1         | 0.49%   |
| MSI MS-7C94                                           | 1         | 0.49%   |
| MSI MS-7C91                                           | 1         | 0.49%   |
| MSI MS-7C90                                           | 1         | 0.49%   |
| MSI MS-7C83                                           | 1         | 0.49%   |
| MSI MS-7C75                                           | 1         | 0.49%   |
| MSI MS-7B85                                           | 1         | 0.49%   |
| MSI MS-7B79                                           | 1         | 0.49%   |
| MSI MS-7A38                                           | 1         | 0.49%   |
| MSI MS-7A34                                           | 1         | 0.49%   |
| MSI MS-7A33                                           | 1         | 0.49%   |
| MSI MS-7721                                           | 1         | 0.49%   |
| MSI Modern 15 A5M                                     | 1         | 0.49%   |
| MSI GL75 Leopard 10SDK                                | 1         | 0.49%   |
| MSI GL63 9SD                                          | 1         | 0.49%   |
| MSI Creator 15 A10SFS                                 | 1         | 0.49%   |
| MouseComputer NH55Dx                                  | 1         | 0.49%   |
| Monster ABRA A5 V15.8                                 | 1         | 0.49%   |
| Microsoft Surface Laptop 3                            | 1         | 0.49%   |
| LG S430-G.BC33P1                                      | 1         | 0.49%   |
| LG 15Z95P-G.AA78B                                     | 1         | 0.49%   |
| Lenovo Yoga Slim 7 Carbon 14ACN6 82L0                 | 1         | 0.49%   |
| Lenovo Yoga Slim 7 14ARE05 82A2                       | 1         | 0.49%   |
| Lenovo Yoga C640-13IML 81UE                           | 1         | 0.49%   |
| Lenovo XiaoXin Chao7000-14IKBR 81GA                   | 1         | 0.49%   |
| Lenovo XiaoXin Air 13IML 81WV                         | 1         | 0.49%   |
| Lenovo V130-15IGM 81HL                                | 1         | 0.49%   |
| Lenovo ThinkPad X220 Tablet 42992PG                   | 1         | 0.49%   |
| Lenovo ThinkPad X1 Yoga 2nd 20JES03429                | 1         | 0.49%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDCTO1WW              | 1         | 0.49%   |
| Lenovo ThinkPad T550 20CKCTO1WW                       | 1         | 0.49%   |
| Lenovo ThinkPad T490s 20NY000JMZ                      | 1         | 0.49%   |
| Lenovo ThinkPad T490s 20NXCTO1WW                      | 1         | 0.49%   |
| Lenovo ThinkPad T480s 20L70058GE                      | 1         | 0.49%   |
| Lenovo ThinkPad T480 20L6S93F00                       | 1         | 0.49%   |
| Lenovo ThinkPad T440p 20AN006GUS                      | 1         | 0.49%   |
| Lenovo ThinkPad T410 2537E82                          | 1         | 0.49%   |
| Lenovo ThinkPad T14s Gen 2i 20WM0051US                | 1         | 0.49%   |
| Lenovo ThinkPad T14 Gen 2i 20W00097FR                 | 1         | 0.49%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013MH                  | 1         | 0.49%   |
| Lenovo ThinkPad P14s Gen 2a 21A1S04W00                | 1         | 0.49%   |
| Lenovo ThinkPad P1 Gen 4i 20Y30010MH                  | 1         | 0.49%   |
| Lenovo ThinkPad E14 Gen 2 20T6000MGE                  | 1         | 0.49%   |
| Lenovo ThinkCentre M82 2929AC4                        | 1         | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 16        | 7.88%   |
| Lenovo IdeaPad       | 9         | 4.43%   |
| ASUS ROG             | 9         | 4.43%   |
| ASUS PRIME           | 8         | 3.94%   |
| Dell Inspiron        | 7         | 3.45%   |
| HP Pavilion          | 5         | 2.46%   |
| Framework Laptop     | 5         | 2.46%   |
| Dell XPS             | 5         | 2.46%   |
| Dell Latitude        | 5         | 2.46%   |
| Acer Aspire          | 5         | 2.46%   |
| Lenovo Legion        | 4         | 1.97%   |
| Dell Precision       | 4         | 1.97%   |
| ASUS All             | 4         | 1.97%   |
| Razer Blade          | 3         | 1.48%   |
| Lenovo Yoga          | 3         | 1.48%   |
| Gigabyte X570        | 3         | 1.48%   |
| Acer Nitro           | 3         | 1.48%   |
| MSI MS-7C37          | 2         | 0.99%   |
| Lenovo XiaoXin       | 2         | 0.99%   |
| HP ZBook             | 2         | 0.99%   |
| HP ENVY              | 2         | 0.99%   |
| HP EliteBook         | 2         | 0.99%   |
| Gigabyte B450M       | 2         | 0.99%   |
| Dell Vostro          | 2         | 0.99%   |
| ASUS TUF             | 2         | 0.99%   |
| ASRock X470          | 2         | 0.99%   |
| TUXEDO Pulse         | 1         | 0.49%   |
| TUXEDO InfinityBook  | 1         | 0.49%   |
| TUXEDO Book          | 1         | 0.49%   |
| Toshiba TECRA        | 1         | 0.49%   |
| Star Labs Lite       | 1         | 0.49%   |
| Sony VPCF115FM       | 1         | 0.49%   |
| Samsung 270E5J       | 1         | 0.49%   |
| OEM V1.0             | 1         | 0.49%   |
| MSI MS-7C94          | 1         | 0.49%   |
| MSI MS-7C91          | 1         | 0.49%   |
| MSI MS-7C90          | 1         | 0.49%   |
| MSI MS-7C83          | 1         | 0.49%   |
| MSI MS-7C75          | 1         | 0.49%   |
| MSI MS-7B85          | 1         | 0.49%   |
| MSI MS-7B79          | 1         | 0.49%   |
| MSI MS-7A38          | 1         | 0.49%   |
| MSI MS-7A34          | 1         | 0.49%   |
| MSI MS-7A33          | 1         | 0.49%   |
| MSI MS-7721          | 1         | 0.49%   |
| MSI Modern           | 1         | 0.49%   |
| MSI GL75             | 1         | 0.49%   |
| MSI GL63             | 1         | 0.49%   |
| MSI Creator          | 1         | 0.49%   |
| MouseComputer NH55Dx | 1         | 0.49%   |
| Monster ABRA         | 1         | 0.49%   |
| Microsoft Surface    | 1         | 0.49%   |
| LG S430-G.BC33P1     | 1         | 0.49%   |
| LG 15Z95P-G.AA78B    | 1         | 0.49%   |
| Lenovo V130-15IGM    | 1         | 0.49%   |
| Lenovo ThinkCentre   | 1         | 0.49%   |
| Lenovo ThinkBook     | 1         | 0.49%   |
| Lenovo IdeaPadFlex   | 1         | 0.49%   |
| Lenovo Flex          | 1         | 0.49%   |
| Lenovo E31-80        | 1         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 37        | 18.23%  |
| 2021 | 34        | 16.75%  |
| 2019 | 30        | 14.78%  |
| 2018 | 27        | 13.3%   |
| 2017 | 16        | 7.88%   |
| 2015 | 15        | 7.39%   |
| 2014 | 8         | 3.94%   |
| 2013 | 8         | 3.94%   |
| 2016 | 7         | 3.45%   |
| 2011 | 7         | 3.45%   |
| 2012 | 5         | 2.46%   |
| 2022 | 3         | 1.48%   |
| 2010 | 3         | 1.48%   |
| 2008 | 2         | 0.99%   |
| 2009 | 1         | 0.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 119       | 58.62%  |
| Desktop     | 75        | 36.95%  |
| Convertible | 6         | 2.96%   |
| Tablet      | 2         | 0.99%   |
| All in one  | 1         | 0.49%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 201       | 99.01%  |
| Enabled  | 2         | 0.99%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 203       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 65        | 32.02%  |
| 8.01-16.0   | 42        | 20.69%  |
| 32.01-64.0  | 35        | 17.24%  |
| 4.01-8.0    | 26        | 12.81%  |
| 3.01-4.0    | 14        | 6.9%    |
| 64.01-256.0 | 14        | 6.9%    |
| 24.01-32.0  | 5         | 2.46%   |
| 2.01-3.0    | 1         | 0.49%   |
| 1.01-2.0    | 1         | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 56        | 27.59%  |
| 3.01-4.0   | 41        | 20.2%   |
| 1.01-2.0   | 39        | 19.21%  |
| 2.01-3.0   | 28        | 13.79%  |
| 8.01-16.0  | 24        | 11.82%  |
| 16.01-24.0 | 5         | 2.46%   |
| 0.51-1.0   | 5         | 2.46%   |
| 24.01-32.0 | 2         | 0.99%   |
| 0.01-0.5   | 2         | 0.99%   |
| 32.01-64.0 | 1         | 0.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 109       | 53.69%  |
| 2      | 46        | 22.66%  |
| 3      | 25        | 12.32%  |
| 4      | 10        | 4.93%   |
| 5      | 5         | 2.46%   |
| 6      | 3         | 1.48%   |
| 7      | 2         | 0.99%   |
| 15     | 1         | 0.49%   |
| 12     | 1         | 0.49%   |
| 8      | 1         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 164       | 80.79%  |
| Yes       | 39        | 19.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 167       | 82.27%  |
| No        | 36        | 17.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 164       | 80.79%  |
| No        | 39        | 19.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 152       | 74.88%  |
| No        | 51        | 25.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 30        | 14.78%  |
| Germany      | 26        | 12.81%  |
| Brazil       | 12        | 5.91%   |
| France       | 11        | 5.42%   |
| Italy        | 10        | 4.93%   |
| India        | 9         | 4.43%   |
| UK           | 8         | 3.94%   |
| Russia       | 8         | 3.94%   |
| Netherlands  | 7         | 3.45%   |
| Spain        | 6         | 2.96%   |
| Poland       | 6         | 2.96%   |
| Turkey       | 5         | 2.46%   |
| China        | 5         | 2.46%   |
| Canada       | 5         | 2.46%   |
| Sweden       | 4         | 1.97%   |
| Switzerland  | 3         | 1.48%   |
| Finland      | 3         | 1.48%   |
| Vietnam      | 2         | 0.99%   |
| Romania      | 2         | 0.99%   |
| New Zealand  | 2         | 0.99%   |
| Japan        | 2         | 0.99%   |
| Indonesia    | 2         | 0.99%   |
| Greece       | 2         | 0.99%   |
| Estonia      | 2         | 0.99%   |
| Czechia      | 2         | 0.99%   |
| Bulgaria     | 2         | 0.99%   |
| Austria      | 2         | 0.99%   |
| Uruguay      | 1         | 0.49%   |
| Ukraine      | 1         | 0.49%   |
| Thailand     | 1         | 0.49%   |
| South Africa | 1         | 0.49%   |
| Slovenia     | 1         | 0.49%   |
| Philippines  | 1         | 0.49%   |
| Peru         | 1         | 0.49%   |
| Pakistan     | 1         | 0.49%   |
| Norway       | 1         | 0.49%   |
| Mexico       | 1         | 0.49%   |
| Lithuania    | 1         | 0.49%   |
| Latvia       | 1         | 0.49%   |
| Kenya        | 1         | 0.49%   |
| Kazakhstan   | 1         | 0.49%   |
| Jersey       | 1         | 0.49%   |
| Israel       | 1         | 0.49%   |
| Ireland      | 1         | 0.49%   |
| Hungary      | 1         | 0.49%   |
| Hong Kong    | 1         | 0.49%   |
| Ghana        | 1         | 0.49%   |
| Egypt        | 1         | 0.49%   |
| Colombia     | 1         | 0.49%   |
| Chile        | 1         | 0.49%   |
| Bangladesh   | 1         | 0.49%   |
| Australia    | 1         | 0.49%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 4         | 1.97%   |
| Paris             | 3         | 1.48%   |
| Munich            | 3         | 1.48%   |
| Moscow            | 3         | 1.48%   |
| Milan             | 3         | 1.48%   |
| Barcelona         | 3         | 1.48%   |
| Singen            | 2         | 0.99%   |
| Salvador          | 2         | 0.99%   |
| Pipe Creek        | 2         | 0.99%   |
| Nantes            | 2         | 0.99%   |
| London            | 2         | 0.99%   |
| Helsinki          | 2         | 0.99%   |
| Cologne           | 2         | 0.99%   |
| Brescia           | 2         | 0.99%   |
| Bengaluru         | 2         | 0.99%   |
| Amsterdam         | 2         | 0.99%   |
| Zug               | 1         | 0.49%   |
| Zhanjiang         | 1         | 0.49%   |
| Zapopan           | 1         | 0.49%   |
| Yogyakarta        | 1         | 0.49%   |
| Yekaterinburg     | 1         | 0.49%   |
| Xanthi            | 1         | 0.49%   |
| Wuhan             | 1         | 0.49%   |
| Wroclaw           | 1         | 0.49%   |
| Worms             | 1         | 0.49%   |
| Wellington        | 1         | 0.49%   |
| Waterloo          | 1         | 0.49%   |
| Wasilla           | 1         | 0.49%   |
| Warsaw            | 1         | 0.49%   |
| Vřesina          | 1         | 0.49%   |
| Vinkeveen         | 1         | 0.49%   |
| Vilnius           | 1         | 0.49%   |
| Villeneuve-d'Ascq | 1         | 0.49%   |
| Vienna            | 1         | 0.49%   |
| Victoria          | 1         | 0.49%   |
| Vedevag           | 1         | 0.49%   |
| Vancouver         | 1         | 0.49%   |
| Vaajakoski        | 1         | 0.49%   |
| Uppsala           | 1         | 0.49%   |
| Ulan-Ude          | 1         | 0.49%   |
| Ufa               | 1         | 0.49%   |
| Uberlândia       | 1         | 0.49%   |
| Trier             | 1         | 0.49%   |
| Trento            | 1         | 0.49%   |
| Trabzon           | 1         | 0.49%   |
| Toronto           | 1         | 0.49%   |
| Tornesch          | 1         | 0.49%   |
| Thuan An          | 1         | 0.49%   |
| Tholey            | 1         | 0.49%   |
| Terni             | 1         | 0.49%   |
| Temuco            | 1         | 0.49%   |
| Tel Aviv          | 1         | 0.49%   |
| Tallinn           | 1         | 0.49%   |
| Sundsvall         | 1         | 0.49%   |
| Songadh           | 1         | 0.49%   |
| Sofia             | 1         | 0.49%   |
| Soest             | 1         | 0.49%   |
| Simferopol        | 1         | 0.49%   |
| Shumen            | 1         | 0.49%   |
| Shinjuku          | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 71        | 94     | 21.65%  |
| WDC                         | 49        | 77     | 14.94%  |
| Seagate                     | 36        | 46     | 10.98%  |
| SanDisk                     | 23        | 24     | 7.01%   |
| Crucial                     | 20        | 27     | 6.1%    |
| SK Hynix                    | 19        | 20     | 5.79%   |
| Toshiba                     | 14        | 19     | 4.27%   |
| Kingston                    | 14        | 15     | 4.27%   |
| Unknown                     | 9         | 9      | 2.74%   |
| Phison                      | 8         | 9      | 2.44%   |
| Intel                       | 8         | 11     | 2.44%   |
| Micron Technology           | 6         | 6      | 1.83%   |
| HGST                        | 5         | 5      | 1.52%   |
| OCZ                         | 4         | 4      | 1.22%   |
| A-DATA Technology           | 4         | 5      | 1.22%   |
| Lexar                       | 3         | 3      | 0.91%   |
| Corsair                     | 3         | 3      | 0.91%   |
| Apple                       | 3         | 3      | 0.91%   |
| XrayDisk                    | 2         | 3      | 0.61%   |
| XPG                         | 2         | 2      | 0.61%   |
| Netac                       | 2         | 2      | 0.61%   |
| Micron/Crucial Technology   | 2         | 2      | 0.61%   |
| Hitachi                     | 2         | 2      | 0.61%   |
| ZHITAI                      | 1         | 1      | 0.3%    |
| Union Memory (Shenzhen)     | 1         | 1      | 0.3%    |
| TrueNAS                     | 1         | 1      | 0.3%    |
| StoreJet                    | 1         | 1      | 0.3%    |
| SPCC                        | 1         | 1      | 0.3%    |
| Realtek                     | 1         | 1      | 0.3%    |
| PNY                         | 1         | 1      | 0.3%    |
| Patriot                     | 1         | 1      | 0.3%    |
| MAXTOR                      | 1         | 1      | 0.3%    |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.3%    |
| Lite-On                     | 1         | 1      | 0.3%    |
| Lenovo                      | 1         | 1      | 0.3%    |
| KIOXIA                      | 1         | 1      | 0.3%    |
| KingSpec                    | 1         | 1      | 0.3%    |
| Indilinx                    | 1         | 1      | 0.3%    |
| Inateck                     | 1         | 1      | 0.3%    |
| China                       | 1         | 1      | 0.3%    |
| AMD                         | 1         | 1      | 0.3%    |
| Unknown                     | 1         | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 7         | 1.86%   |
| Samsung SSD 970 EVO Plus 1TB        | 7         | 1.86%   |
| Sandisk NVMe SSD Drive 1TB          | 6         | 1.59%   |
| Samsung SSD 970 EVO Plus 2TB        | 5         | 1.33%   |
| Samsung SSD 850 EVO 250GB           | 5         | 1.33%   |
| Crucial CT240BX500SSD1 240GB        | 5         | 1.33%   |
| WDC WD10EZEX-00BN5A0 1TB            | 4         | 1.06%   |
| SK Hynix NVMe SSD Drive 512GB       | 4         | 1.06%   |
| Samsung SSD 970 EVO 1TB             | 4         | 1.06%   |
| Samsung SSD 860 EVO 500GB           | 4         | 1.06%   |
| Toshiba MQ01ABD100 1TB              | 3         | 0.8%    |
| Seagate ST1000LX015-1U7172 1TB      | 3         | 0.8%    |
| SanDisk SSD PLUS 1000GB             | 3         | 0.8%    |
| Samsung SSD 960 EVO 250GB           | 3         | 0.8%    |
| Samsung SSD 860 EVO 250GB           | 3         | 0.8%    |
| Samsung SSD 850 EVO 500GB           | 3         | 0.8%    |
| Samsung SSD 830 Series 128GB        | 3         | 0.8%    |
| Samsung NVMe SSD Drive 250GB        | 3         | 0.8%    |
| Lexar 128GB SSD                     | 3         | 0.8%    |
| Kingston SA400S37480G 480GB SSD     | 3         | 0.8%    |
| Kingston SA400S37240G 240GB SSD     | 3         | 0.8%    |
| Crucial CT500MX500SSD1 500GB        | 3         | 0.8%    |
| WDC WDS500G3X0C-00SJG0 500GB        | 2         | 0.53%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 2         | 0.53%   |
| WDC WDS100T1X0E-00AFY0 1TB          | 2         | 0.53%   |
| WDC WD6003FZBX-00K5WB0 6TB          | 2         | 0.53%   |
| WDC WD10SPZX-21Z10T0 1TB            | 2         | 0.53%   |
| WDC WD10EZEX-08WN4A0 1TB            | 2         | 0.53%   |
| Unknown MMC Card  64GB              | 2         | 0.53%   |
| Toshiba MQ04ABF100 1TB              | 2         | 0.53%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 2         | 0.53%   |
| SK Hynix PC601 NVMe 512GB           | 2         | 0.53%   |
| SK Hynix NVMe SSD Drive 256GB       | 2         | 0.53%   |
| SK Hynix BC711 NVMe 512GB           | 2         | 0.53%   |
| Seagate ST4000DM004-2CV104 4TB      | 2         | 0.53%   |
| Seagate ST3500418AS 500GB           | 2         | 0.53%   |
| Seagate ST2000LM007-1R8174 2TB      | 2         | 0.53%   |
| Seagate ST2000DM008-2FR102 2TB      | 2         | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB      | 2         | 0.53%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 0.53%   |
| Seagate ST1000DM010-2EP102 1TB      | 2         | 0.53%   |
| Seagate BUP Slim 2TB                | 2         | 0.53%   |
| SanDisk SDSSDHP256G 256GB           | 2         | 0.53%   |
| Sandisk NVMe SSD Drive 500GB        | 2         | 0.53%   |
| Samsung SSD 980 PRO 500GB           | 2         | 0.53%   |
| Samsung SSD 980 PRO 1TB             | 2         | 0.53%   |
| Samsung SSD 980 1TB                 | 2         | 0.53%   |
| Samsung SSD 970 EVO 500GB           | 2         | 0.53%   |
| Samsung SSD 870 QVO 2TB             | 2         | 0.53%   |
| Samsung SSD 870 QVO 1TB             | 2         | 0.53%   |
| Samsung SSD 860 QVO 1TB             | 2         | 0.53%   |
| Samsung NVMe SSD Drive 1TB          | 2         | 0.53%   |
| Samsung MZVLB512HBJQ-000L2 512GB    | 2         | 0.53%   |
| Phison Sabrent Rocket Q 500GB       | 2         | 0.53%   |
| Micron NVMe SSD Drive 512GB         | 2         | 0.53%   |
| Kingston SA400S37120G 120GB SSD     | 2         | 0.53%   |
| Intel NVMe SSD Drive 512GB          | 2         | 0.53%   |
| HGST HTS725050A7E630 500GB          | 2         | 0.53%   |
| HGST HTS541010A9E680 1TB            | 2         | 0.53%   |
| Crucial M4-CT256M4SSD2 256GB        | 2         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 45     | 37.63%  |
| WDC                 | 34        | 52     | 36.56%  |
| Toshiba             | 12        | 16     | 12.9%   |
| HGST                | 5         | 5      | 5.38%   |
| Samsung Electronics | 3         | 3      | 3.23%   |
| Hitachi             | 2         | 2      | 2.15%   |
| TrueNAS             | 1         | 1      | 1.08%   |
| MAXTOR              | 1         | 1      | 1.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 33     | 25%     |
| Crucial             | 18        | 24     | 18.75%  |
| SanDisk             | 11        | 12     | 11.46%  |
| Kingston            | 9         | 10     | 9.38%   |
| WDC                 | 7         | 11     | 7.29%   |
| OCZ                 | 4         | 4      | 4.17%   |
| SK Hynix            | 3         | 3      | 3.13%   |
| Lexar               | 3         | 3      | 3.13%   |
| Apple               | 3         | 3      | 3.13%   |
| XrayDisk            | 2         | 2      | 2.08%   |
| A-DATA Technology   | 2         | 2      | 2.08%   |
| Unknown             | 1         | 1      | 1.04%   |
| StoreJet            | 1         | 1      | 1.04%   |
| PNY                 | 1         | 1      | 1.04%   |
| Patriot             | 1         | 1      | 1.04%   |
| Netac               | 1         | 1      | 1.04%   |
| KingSpec            | 1         | 1      | 1.04%   |
| Indilinx            | 1         | 1      | 1.04%   |
| Inateck             | 1         | 1      | 1.04%   |
| China               | 1         | 1      | 1.04%   |
| Unknown             | 1         | 1      | 1.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 125       | 159    | 42.66%  |
| SSD     | 80        | 117    | 27.3%   |
| HDD     | 79        | 125    | 26.96%  |
| MMC     | 8         | 8      | 2.73%   |
| Unknown | 1         | 1      | 0.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 125       | 158    | 48.45%  |
| SATA | 120       | 239    | 46.51%  |
| MMC  | 8         | 8      | 3.1%    |
| SAS  | 5         | 5      | 1.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 83        | 117    | 48.82%  |
| 0.51-1.0   | 58        | 70     | 34.12%  |
| 1.01-2.0   | 18        | 20     | 10.59%  |
| 4.01-10.0  | 4         | 20     | 2.35%   |
| 3.01-4.0   | 3         | 8      | 1.76%   |
| 2.01-3.0   | 3         | 5      | 1.76%   |
| 10.01-20.0 | 1         | 2      | 0.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 50        | 24.63%  |
| 501-1000       | 41        | 20.2%   |
| 101-250        | 33        | 16.26%  |
| More than 3000 | 28        | 13.79%  |
| 1001-2000      | 27        | 13.3%   |
| 2001-3000      | 9         | 4.43%   |
| Unknown        | 6         | 2.96%   |
| 51-100         | 5         | 2.46%   |
| 1-20           | 3         | 1.48%   |
| 21-50          | 1         | 0.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 42        | 20.69%  |
| 21-50          | 29        | 14.29%  |
| 1-20           | 24        | 11.82%  |
| 501-1000       | 24        | 11.82%  |
| 251-500        | 23        | 11.33%  |
| 1001-2000      | 19        | 9.36%   |
| 51-100         | 18        | 8.87%   |
| More than 3000 | 9         | 4.43%   |
| 2001-3000      | 9         | 4.43%   |
| Unknown        | 6         | 2.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB            | 2         | 2      | 9.09%   |
| XrayDisk SSD 256GB                    | 1         | 1      | 4.55%   |
| WDC WD5000AAKS-22V1A0 500GB           | 1         | 1      | 4.55%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 4.55%   |
| WDC WD10EARS-003BB1 1TB               | 1         | 1      | 4.55%   |
| Toshiba MQ02ABD100H 1TB               | 1         | 1      | 4.55%   |
| Toshiba HDWQ140 4TB                   | 1         | 4      | 4.55%   |
| Toshiba HDWL110 1TB                   | 1         | 1      | 4.55%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 4.55%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 4.55%   |
| Seagate ST3500320NS 500GB             | 1         | 1      | 4.55%   |
| Seagate ST1000LX015-1U7172 1TB        | 1         | 1      | 4.55%   |
| Seagate ST1000LM014-SSHD-8GB          | 1         | 1      | 4.55%   |
| Seagate ST1000DX001-1NS162 1TB        | 1         | 1      | 4.55%   |
| Seagate ST1000DM003-1ER162 1TB        | 1         | 1      | 4.55%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 4.55%   |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 1      | 4.55%   |
| Kingston SA400S37480G 480GB SSD       | 1         | 1      | 4.55%   |
| KingSpec MT-1TB SSD                   | 1         | 1      | 4.55%   |
| HGST HTS541010A9E680 1TB              | 1         | 1      | 4.55%   |
| Crucial M4-CT256M4SSD2 256GB          | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 31.82%  |
| WDC                 | 3         | 3      | 13.64%  |
| Toshiba             | 3         | 6      | 13.64%  |
| HGST                | 3         | 3      | 13.64%  |
| Samsung Electronics | 2         | 2      | 9.09%   |
| XrayDisk            | 1         | 1      | 4.55%   |
| Kingston            | 1         | 1      | 4.55%   |
| KingSpec            | 1         | 1      | 4.55%   |
| Crucial             | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 7      | 43.75%  |
| WDC     | 3         | 3      | 18.75%  |
| Toshiba | 3         | 6      | 18.75%  |
| HGST    | 3         | 3      | 18.75%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 19     | 70%     |
| SSD  | 4         | 4      | 20%     |
| NVMe | 2         | 2      | 10%     |

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
| Works    | 122       | 239    | 54.22%  |
| Detected | 85        | 146    | 37.78%  |
| Malfunc  | 18        | 25     | 8%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 106       | 34.3%   |
| Samsung Electronics          | 55        | 17.8%   |
| AMD                          | 54        | 17.48%  |
| Sandisk                      | 22        | 7.12%   |
| SK Hynix                     | 16        | 5.18%   |
| Phison Electronics           | 12        | 3.88%   |
| ASMedia Technology           | 8         | 2.59%   |
| Micron Technology            | 7         | 2.27%   |
| Kingston Technology Company  | 5         | 1.62%   |
| Micron/Crucial Technology    | 4         | 1.29%   |
| ADATA Technology             | 4         | 1.29%   |
| Toshiba America Info Systems | 2         | 0.65%   |
| Silicon Motion               | 2         | 0.65%   |
| Marvell Technology Group     | 2         | 0.65%   |
| LSI Logic / Symbios Logic    | 2         | 0.65%   |
| KIOXIA                       | 2         | 0.65%   |
| Yangtze Memory Technologies  | 1         | 0.32%   |
| Union Memory (Shenzhen)      | 1         | 0.32%   |
| Seagate Technology           | 1         | 0.32%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.32%   |
| Lite-On Technology           | 1         | 0.32%   |
| Lenovo                       | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 41        | 11.99%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 31        | 9.06%   |
| AMD 400 Series Chipset SATA Controller                                                 | 14        | 4.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 10        | 2.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 9         | 2.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 9         | 2.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 8         | 2.34%   |
| AMD 500 Series Chipset SATA Controller                                                 | 8         | 2.34%   |
| Micron Non-Volatile memory controller                                                  | 7         | 2.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 7         | 2.05%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 7         | 2.05%   |
| SK Hynix Gold P31 SSD                                                                  | 6         | 1.75%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                             | 6         | 1.75%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 6         | 1.75%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 6         | 1.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 6         | 1.75%   |
| ASMedia ASM1062 Serial ATA Controller                                                  | 6         | 1.75%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 5         | 1.46%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 5         | 1.46%   |
| Phison E12 NVMe Controller                                                             | 5         | 1.46%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 5         | 1.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 5         | 1.46%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 5         | 1.46%   |
| SK Hynix Non-Volatile memory controller                                                | 4         | 1.17%   |
| Phison PS5013 E13 NVMe Controller                                                      | 4         | 1.17%   |
| Intel SSD 660P Series                                                                  | 4         | 1.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 1.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 4         | 1.17%   |
| SK Hynix BC511                                                                         | 3         | 0.88%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 3         | 0.88%   |
| Sandisk Non-Volatile memory controller                                                 | 3         | 0.88%   |
| Samsung NVMe SSD Controller 980                                                        | 3         | 0.88%   |
| Phison E16 PCIe4 NVMe Controller                                                       | 3         | 0.88%   |
| Intel Non-Volatile memory controller                                                   | 3         | 0.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]           | 3         | 0.88%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 3         | 0.88%   |
| AMD X370 Series Chipset SATA Controller                                                | 3         | 0.88%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                            | 3         | 0.88%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 2         | 0.58%   |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 2         | 0.58%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 2         | 0.58%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 2         | 0.58%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 2         | 0.58%   |
| KIOXIA Non-Volatile memory controller                                                  | 2         | 0.58%   |
| Kingston Company Company Non-Volatile memory controller                                | 2         | 0.58%   |
| Kingston Company A2000 NVMe SSD                                                        | 2         | 0.58%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 2         | 0.58%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 0.58%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 2         | 0.58%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                             | 2         | 0.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 0.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 0.58%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 0.58%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.58%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                             | 2         | 0.58%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 0.58%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 2         | 0.58%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 2         | 0.58%   |
| AMD 300 Series Chipset SATA Controller                                                 | 2         | 0.58%   |
| Yangtze Memory Non-Volatile memory controller                                          | 1         | 0.29%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 145       | 50.52%  |
| NVMe | 125       | 43.55%  |
| RAID | 8         | 2.79%   |
| IDE  | 7         | 2.44%   |
| SAS  | 2         | 0.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 134       | 66.01%  |
| AMD    | 69        | 33.99%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 8         | 3.94%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 5         | 2.46%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 4         | 1.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 4         | 1.97%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 4         | 1.97%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 4         | 1.97%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 3         | 1.48%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 3         | 1.48%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 3         | 1.48%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 3         | 1.48%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 3         | 1.48%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 1.48%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 3         | 1.48%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 3         | 1.48%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 3         | 1.48%   |
| AMD Ryzen 5 3600 6-Core Processor       | 3         | 1.48%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 0.99%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 0.99%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 2         | 0.99%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 2         | 0.99%   |
| Intel Core i7-10875H CPU @ 2.30GHz      | 2         | 0.99%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 2         | 0.99%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 2         | 0.99%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 2         | 0.99%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 0.99%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 2         | 0.99%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 0.99%   |
| Intel Core i5-2500 CPU @ 3.30GHz        | 2         | 0.99%   |
| Intel Core i3-2330M CPU @ 2.20GHz       | 2         | 0.99%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 2         | 0.99%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 2         | 0.99%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 2         | 0.99%   |
| AMD Ryzen 7 5800U with Radeon Graphics  | 2         | 0.99%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 2         | 0.99%   |
| AMD Ryzen 7 4800U with Radeon Graphics  | 2         | 0.99%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 2         | 0.99%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 2         | 0.99%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 2         | 0.99%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 2         | 0.99%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz     | 1         | 0.49%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz     | 1         | 0.49%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz     | 1         | 0.49%   |
| Intel Pentium CPU N4200 @ 1.10GHz       | 1         | 0.49%   |
| Intel Pentium CPU N3700 @ 1.60GHz       | 1         | 0.49%   |
| Intel Pentium CPU G3240 @ 3.10GHz       | 1         | 0.49%   |
| Intel Pentium CPU 4415U @ 2.30GHz       | 1         | 0.49%   |
| Intel Genuine CPU U7300 @ 1.30GHz       | 1         | 0.49%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz        | 1         | 0.49%   |
| Intel Core i9-9900K CPU @ 3.60GHz       | 1         | 0.49%   |
| Intel Core i9-10980XE CPU @ 3.00GHz     | 1         | 0.49%   |
| Intel Core i7-9850H CPU @ 2.60GHz       | 1         | 0.49%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 1         | 0.49%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 1         | 0.49%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 1         | 0.49%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 0.49%   |
| Intel Core i7-6800K CPU @ 3.40GHz       | 1         | 0.49%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 0.49%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 1         | 0.49%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 1         | 0.49%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz      | 1         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i7     | 48        | 23.65%  |
| Intel Core i5     | 39        | 19.21%  |
| AMD Ryzen 7       | 30        | 14.78%  |
| Other             | 20        | 9.85%   |
| AMD Ryzen 5       | 20        | 9.85%   |
| AMD Ryzen 9       | 10        | 4.93%   |
| Intel Core i3     | 9         | 4.43%   |
| Intel Celeron     | 5         | 2.46%   |
| Intel Pentium     | 4         | 1.97%   |
| Intel Xeon        | 3         | 1.48%   |
| Intel Core i9     | 2         | 0.99%   |
| AMD Ryzen 7 PRO   | 2         | 0.99%   |
| AMD Ryzen 3       | 2         | 0.99%   |
| Intel Genuine     | 1         | 0.49%   |
| Intel Core m5     | 1         | 0.49%   |
| Intel Core 2 Quad | 1         | 0.49%   |
| Intel Core 2 Duo  | 1         | 0.49%   |
| AMD Ryzen 5 PRO   | 1         | 0.49%   |
| AMD Phenom II X6  | 1         | 0.49%   |
| AMD FX            | 1         | 0.49%   |
| AMD E2            | 1         | 0.49%   |
| AMD Athlon X4     | 1         | 0.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 70        | 34.48%  |
| 2      | 46        | 22.66%  |
| 8      | 38        | 18.72%  |
| 6      | 36        | 17.73%  |
| 12     | 6         | 2.96%   |
| 16     | 5         | 2.46%   |
| 18     | 1         | 0.49%   |
| 14     | 1         | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 203       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 174       | 85.71%  |
| 1      | 29        | 14.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 203       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 74        | 36.45%  |
| 0x806c1    | 8         | 3.94%   |
| 0x08701021 | 8         | 3.94%   |
| 0x0800820d | 7         | 3.45%   |
| 0x406e3    | 6         | 2.96%   |
| 0x206a7    | 6         | 2.96%   |
| 0x0a50000c | 6         | 2.96%   |
| 0xa0652    | 5         | 2.46%   |
| 0x906ea    | 5         | 2.46%   |
| 0x906e9    | 5         | 2.46%   |
| 0x306c3    | 5         | 2.46%   |
| 0x08600106 | 5         | 2.46%   |
| 0x506e3    | 4         | 1.97%   |
| 0x806ec    | 3         | 1.48%   |
| 0x806ea    | 3         | 1.48%   |
| 0x806e9    | 3         | 1.48%   |
| 0x306d4    | 3         | 1.48%   |
| 0x306a9    | 3         | 1.48%   |
| 0x0a201016 | 3         | 1.48%   |
| 0x0a201009 | 3         | 1.48%   |
| 0x08600103 | 3         | 1.48%   |
| 0x706e5    | 2         | 0.99%   |
| 0x0a201204 | 2         | 0.99%   |
| 0x08608103 | 2         | 0.99%   |
| 0x08608102 | 2         | 0.99%   |
| 0x08108109 | 2         | 0.99%   |
| 0x08108102 | 2         | 0.99%   |
| 0xa0671    | 1         | 0.49%   |
| 0xa0655    | 1         | 0.49%   |
| 0xa0653    | 1         | 0.49%   |
| 0x906ed    | 1         | 0.49%   |
| 0x906ec    | 1         | 0.49%   |
| 0x906a3    | 1         | 0.49%   |
| 0x90672    | 1         | 0.49%   |
| 0x806c2    | 1         | 0.49%   |
| 0x506c9    | 1         | 0.49%   |
| 0x50657    | 1         | 0.49%   |
| 0x406f1    | 1         | 0.49%   |
| 0x406c4    | 1         | 0.49%   |
| 0x406c3    | 1         | 0.49%   |
| 0x30673    | 1         | 0.49%   |
| 0x20652    | 1         | 0.49%   |
| 0x1067a    | 1         | 0.49%   |
| 0x0a404101 | 1         | 0.49%   |
| 0x08701013 | 1         | 0.49%   |
| 0x08600104 | 1         | 0.49%   |
| 0x0800820b | 1         | 0.49%   |
| 0x08001138 | 1         | 0.49%   |
| 0x08001126 | 1         | 0.49%   |
| 0x06001119 | 1         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 36        | 17.73%  |
| Zen 2            | 22        | 10.84%  |
| Zen 3            | 18        | 8.87%   |
| Zen+             | 14        | 6.9%    |
| Haswell          | 14        | 6.9%    |
| TigerLake        | 13        | 6.4%    |
| Skylake          | 13        | 6.4%    |
| SandyBridge      | 11        | 5.42%   |
| Unknown          | 11        | 5.42%   |
| CometLake        | 10        | 4.93%   |
| IvyBridge        | 8         | 3.94%   |
| Broadwell        | 8         | 3.94%   |
| Zen              | 4         | 1.97%   |
| Icelake          | 4         | 1.97%   |
| Silvermont       | 3         | 1.48%   |
| Penryn           | 3         | 1.48%   |
| Piledriver       | 2         | 0.99%   |
| Goldmont plus    | 2         | 0.99%   |
| Alderlake Hybrid | 2         | 0.99%   |
| Westmere         | 1         | 0.49%   |
| Nehalem          | 1         | 0.49%   |
| K10              | 1         | 0.49%   |
| Goldmont         | 1         | 0.49%   |
| Excavator        | 1         | 0.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 114       | 44.19%  |
| Nvidia | 78        | 30.23%  |
| AMD    | 66        | 25.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 4.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 11        | 4.2%    |
| AMD Renoir                                                                               | 10        | 3.82%   |
| Intel HD Graphics 630                                                                    | 8         | 3.05%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 3.05%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 3.05%   |
| AMD Cezanne                                                                              | 8         | 3.05%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 2.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.29%   |
| AMD Lucienne                                                                             | 6         | 2.29%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.91%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.91%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 1.91%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 5         | 1.91%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 4         | 1.53%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.53%   |
| Intel HD Graphics 620                                                                    | 4         | 1.53%   |
| Intel HD Graphics 530                                                                    | 4         | 1.53%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.53%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 4         | 1.53%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 1.15%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3         | 1.15%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.15%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 1.15%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 3         | 1.15%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 1.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.15%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.76%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.76%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 2         | 0.76%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2         | 0.76%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.76%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.76%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.76%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.76%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.76%   |
| Nvidia GK104GLM [Quadro K3100M]                                                          | 2         | 0.76%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.76%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 2         | 0.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.76%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.76%   |
| AMD Tonga PRO [Radeon R9 285/380]                                                        | 2         | 0.76%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 0.76%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 0.76%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 2         | 0.76%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.38%   |
| Nvidia TU116 [GeForce GTX 1650]                                                          | 1         | 0.38%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.38%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.38%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1         | 0.38%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1         | 0.38%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 0.38%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                                         | 1         | 0.38%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1         | 0.38%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1         | 0.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 66        | 32.51%  |
| 1 x AMD        | 50        | 24.63%  |
| Intel + Nvidia | 43        | 21.18%  |
| 1 x Nvidia     | 28        | 13.79%  |
| AMD + Nvidia   | 7         | 3.45%   |
| Intel + AMD    | 5         | 2.46%   |
| 2 x AMD        | 4         | 1.97%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 143       | 70.44%  |
| Proprietary | 59        | 29.06%  |
| Unknown     | 1         | 0.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 127       | 62.56%  |
| 7.01-8.0   | 18        | 8.87%   |
| 1.01-2.0   | 17        | 8.37%   |
| 3.01-4.0   | 12        | 5.91%   |
| 5.01-6.0   | 9         | 4.43%   |
| 0.01-0.5   | 9         | 4.43%   |
| 8.01-16.0  | 8         | 3.94%   |
| 0.51-1.0   | 3         | 1.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 34        | 13.49%  |
| Dell                 | 30        | 11.9%   |
| BOE                  | 26        | 10.32%  |
| Samsung Electronics  | 22        | 8.73%   |
| LG Display           | 20        | 7.94%   |
| Goldstar             | 17        | 6.75%   |
| Chimei Innolux       | 17        | 6.75%   |
| AOC                  | 10        | 3.97%   |
| Ancor Communications | 9         | 3.57%   |
| Sharp                | 7         | 2.78%   |
| Philips              | 6         | 2.38%   |
| BenQ                 | 5         | 1.98%   |
| Apple                | 5         | 1.98%   |
| Lenovo               | 4         | 1.59%   |
| Hewlett-Packard      | 4         | 1.59%   |
| ASUSTek Computer     | 4         | 1.59%   |
| Acer                 | 4         | 1.59%   |
| PANDA                | 3         | 1.19%   |
| NEC Computers        | 3         | 1.19%   |
| Iiyama               | 3         | 1.19%   |
| Gigabyte Technology  | 3         | 1.19%   |
| Sony                 | 2         | 0.79%   |
| InfoVision           | 2         | 0.79%   |
| Belinea              | 2         | 0.79%   |
| WST                  | 1         | 0.4%    |
| ViewSonic            | 1         | 0.4%    |
| Valve                | 1         | 0.4%    |
| RTK                  | 1         | 0.4%    |
| Pixio                | 1         | 0.4%    |
| HUAWEI               | 1         | 0.4%    |
| HannStar             | 1         | 0.4%    |
| Fujitsu Siemens      | 1         | 0.4%    |
| Eizo                 | 1         | 0.4%    |
| CSO                  | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 5         | 1.92%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 3         | 1.15%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 3         | 1.15%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 3         | 1.15%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 2         | 0.77%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 2         | 0.77%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 2         | 0.77%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 2         | 0.77%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 2         | 0.77%   |
| Goldstar ULTRAGEAR GSM5B80 2560x1440 597x336mm 27.0-inch              | 2         | 0.77%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.77%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch      | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 2         | 0.77%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                  | 2         | 0.77%   |
| AU Optronics LCD Monitor AUOB78D 1920x1080 344x193mm 15.5-inch        | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.77%   |
| WST LCD Monitor WST3316 2160x1440 250x170mm 11.9-inch                 | 1         | 0.38%   |
| ViewSonic VP3481a VSCB13A 3440x1440 797x333mm 34.0-inch               | 1         | 0.38%   |
| Valve Index HMD VLV91A8                                               | 1         | 0.38%   |
| Sony TV SNYEF03 1600x900                                              | 1         | 0.38%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch | 1         | 0.38%   |
| Sharp LQ135P1JX51 SHP14B3 2256x1504 285x190mm 13.5-inch               | 1         | 0.38%   |
| Sharp LQ134N1JW54 SHP154F 1920x1200 288x180mm 13.4-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP14A1 3840x2160 344x194mm 15.5-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.38%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 344x194mm 15.5-inch   | 1         | 0.38%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1         | 0.38%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch     | 1         | 0.38%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4152 2880x1800 302x189mm 14.0-inch | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SAM7106 1920x1080 600x340mm 27.2-inch | 1         | 0.38%   |
| Samsung Electronics LCD Monitor S27D590 1920x1080                     | 1         | 0.38%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 1         | 0.38%   |
| Samsung Electronics C32HG7x SAM0E13 2560x1440 697x392mm 31.5-inch     | 1         | 0.38%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.38%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                     | 1         | 0.38%   |
| Pixio PX279P PNS0279 1920x1080 698x393mm 31.5-inch                    | 1         | 0.38%   |
| Philips PHL 345E2 PHLC237 3440x1440 800x335mm 34.1-inch               | 1         | 0.38%   |
| Philips PHL 345B1C PHL093D 3440x1440 797x334mm 34.0-inch              | 1         | 0.38%   |
| Philips PHL 276E8V PHLC18F 1920x1080 597x336mm 27.0-inch              | 1         | 0.38%   |
| Philips LCD Monitor PHL 345B1C 3440x1440                              | 1         | 0.38%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch               | 1         | 0.38%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.38%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.38%   |
| NEC Computers LCD172VXM NEC67C5 1280x1024 338x270mm 17.0-inch         | 1         | 0.38%   |
| NEC Computers EA244WMi NEC68D6 1920x1200 519x324mm 24.1-inch          | 1         | 0.38%   |
| NEC Computers E231W NEC67EA 1920x1080 510x287mm 23.0-inch             | 1         | 0.38%   |
| LG Display LCD Monitor LGD06AA 3840x2400 344x215mm 16.0-inch          | 1         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 115       | 47.72%  |
| 1366x768 (WXGA)    | 25        | 10.37%  |
| 2560x1440 (QHD)    | 22        | 9.13%   |
| 3840x2160 (4K)     | 20        | 8.3%    |
| 3440x1440          | 9         | 3.73%   |
| 1920x1200 (WUXGA)  | 7         | 2.9%    |
| 2256x1504          | 6         | 2.49%   |
| 1280x1024 (SXGA)   | 6         | 2.49%   |
| 1680x1050 (WSXGA+) | 5         | 2.07%   |
| 2560x1600          | 4         | 1.66%   |
| 2560x1080          | 4         | 1.66%   |
| 2160x1440          | 3         | 1.24%   |
| 1600x900 (HD+)     | 3         | 1.24%   |
| 3840x2400          | 2         | 0.83%   |
| 2880x1800          | 2         | 0.83%   |
| 1280x800 (WXGA)    | 2         | 0.83%   |
| 3840x1600          | 1         | 0.41%   |
| 3840x1080          | 1         | 0.41%   |
| 2240x1400          | 1         | 0.41%   |
| 1440x900 (WXGA+)   | 1         | 0.41%   |
| 1360x768           | 1         | 0.41%   |
| Unknown            | 1         | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 54        | 21.43%  |
| 13      | 33        | 13.1%   |
| 24      | 29        | 11.51%  |
| 27      | 28        | 11.11%  |
| 14      | 24        | 9.52%   |
| 23      | 14        | 5.56%   |
| 17      | 11        | 4.37%   |
| 34      | 10        | 3.97%   |
| 21      | 9         | 3.57%   |
| 31      | 8         | 3.17%   |
| 28      | 4         | 1.59%   |
| 20      | 4         | 1.59%   |
| 19      | 4         | 1.59%   |
| Unknown | 4         | 1.59%   |
| 22      | 3         | 1.19%   |
| 72      | 2         | 0.79%   |
| 11      | 2         | 0.79%   |
| 54      | 1         | 0.4%    |
| 48      | 1         | 0.4%    |
| 37      | 1         | 0.4%    |
| 35      | 1         | 0.4%    |
| 32      | 1         | 0.4%    |
| 29      | 1         | 0.4%    |
| 18      | 1         | 0.4%    |
| 16      | 1         | 0.4%    |
| 12      | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 89        | 37.08%  |
| 501-600     | 58        | 24.17%  |
| 201-300     | 25        | 10.42%  |
| 401-500     | 18        | 7.5%    |
| 601-700     | 16        | 6.67%   |
| 351-400     | 13        | 5.42%   |
| 701-800     | 11        | 4.58%   |
| Unknown     | 4         | 1.67%   |
| 801-900     | 2         | 0.83%   |
| 1501-2000   | 2         | 0.83%   |
| 1001-1500   | 2         | 0.83%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 159       | 71.95%  |
| 16/10   | 29        | 13.12%  |
| 21/9    | 13        | 5.88%   |
| 3/2     | 9         | 4.07%   |
| 5/4     | 6         | 2.71%   |
| Unknown | 4         | 1.81%   |
| 32/9    | 1         | 0.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 54        | 21.77%  |
| 81-90          | 45        | 18.15%  |
| 201-250        | 42        | 16.94%  |
| 301-350        | 28        | 11.29%  |
| 351-500        | 24        | 9.68%   |
| 71-80          | 12        | 4.84%   |
| 251-300        | 9         | 3.63%   |
| 151-200        | 9         | 3.63%   |
| 121-130        | 8         | 3.23%   |
| 141-150        | 4         | 1.61%   |
| Unknown        | 4         | 1.61%   |
| More than 1000 | 3         | 1.21%   |
| 61-70          | 2         | 0.81%   |
| 501-1000       | 2         | 0.81%   |
| 51-60          | 1         | 0.4%    |
| 111-120        | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 73        | 30.67%  |
| 51-100        | 71        | 29.83%  |
| 101-120       | 51        | 21.43%  |
| 161-240       | 26        | 10.92%  |
| More than 240 | 11        | 4.62%   |
| Unknown       | 4         | 1.68%   |
| 1-50          | 2         | 0.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 141       | 69.46%  |
| 2     | 50        | 24.63%  |
| 3     | 7         | 3.45%   |
| 0     | 4         | 1.97%   |
| 4     | 1         | 0.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 125       | 40.72%  |
| Realtek Semiconductor    | 114       | 37.13%  |
| Qualcomm Atheros         | 30        | 9.77%   |
| Broadcom                 | 10        | 3.26%   |
| MEDIATEK                 | 6         | 1.95%   |
| Microsoft                | 3         | 0.98%   |
| Sierra Wireless          | 2         | 0.65%   |
| Ralink Technology        | 2         | 0.65%   |
| ASIX Electronics         | 2         | 0.65%   |
| Aquantia                 | 2         | 0.65%   |
| Xiaomi                   | 1         | 0.33%   |
| Samsung Electronics      | 1         | 0.33%   |
| Ralink                   | 1         | 0.33%   |
| Mellanox Technologies    | 1         | 0.33%   |
| Marvell Technology Group | 1         | 0.33%   |
| Lenovo                   | 1         | 0.33%   |
| Huawei Technologies      | 1         | 0.33%   |
| Foxconn / Hon Hai        | 1         | 0.33%   |
| DisplayLink              | 1         | 0.33%   |
| D-Link                   | 1         | 0.33%   |
| Arduino SA               | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 72        | 20%     |
| Intel Wi-Fi 6 AX200                                               | 24        | 6.67%   |
| Intel I211 Gigabit Network Connection                             | 18        | 5%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 3.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 3.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 11        | 3.06%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 2.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 8         | 2.22%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 1.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.67%   |
| Intel Wireless 8265 / 8275                                        | 6         | 1.67%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.39%   |
| Intel Wireless 3165                                               | 5         | 1.39%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.39%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 4         | 1.11%   |
| Intel Wireless 7265                                               | 4         | 1.11%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.83%   |
| Realtek 802.11ac NIC                                              | 3         | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 0.83%   |
| Intel Wireless 8260                                               | 3         | 0.83%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.83%   |
| Intel Ethernet Controller I225-V                                  | 3         | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.83%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.56%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.56%   |
| Microsoft Wireless XBox Controller Dongle                         | 2         | 0.56%   |
| Intel Wireless-AC 9260                                            | 2         | 0.56%   |
| Intel Wireless 7260                                               | 2         | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.56%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.56%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.56%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 0.56%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.56%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 0.56%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 2         | 0.56%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.28%   |
| Sierra Wireless MC7700                                            | 1         | 0.28%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A               | 1         | 0.28%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.28%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.28%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.28%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.28%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.28%   |
| Realtek 802.11n NIC                                               | 1         | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 97        | 56.73%  |
| Qualcomm Atheros      | 27        | 15.79%  |
| Realtek Semiconductor | 24        | 14.04%  |
| Broadcom              | 8         | 4.68%   |
| MEDIATEK              | 6         | 3.51%   |
| Microsoft             | 3         | 1.75%   |
| Sierra Wireless       | 2         | 1.17%   |
| Ralink Technology     | 2         | 1.17%   |
| Ralink                | 1         | 0.58%   |
| D-Link                | 1         | 0.58%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 24        | 14.04%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 11        | 6.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 8         | 4.68%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 7         | 4.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 6         | 3.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 6         | 3.51%   |
| Intel Wireless 8265 / 8275                                           | 6         | 3.51%   |
| Intel Wi-Fi 6 AX201                                                  | 6         | 3.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 5         | 2.92%   |
| Intel Wireless 3165                                                  | 5         | 2.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 5         | 2.92%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter        | 4         | 2.34%   |
| Intel Wireless 7265                                                  | 4         | 2.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 4         | 2.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 3         | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 3         | 1.75%   |
| Realtek 802.11ac NIC                                                 | 3         | 1.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 3         | 1.75%   |
| Intel Wireless 8260                                                  | 3         | 1.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 3         | 1.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 3         | 1.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 3         | 1.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 3         | 1.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 2         | 1.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 1.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2         | 1.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2         | 1.17%   |
| Microsoft Wireless XBox Controller Dongle                            | 2         | 1.17%   |
| Intel Wireless-AC 9260                                               | 2         | 1.17%   |
| Intel Wireless 7260                                                  | 2         | 1.17%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 2         | 1.17%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 2         | 1.17%   |
| Sierra Wireless MC7700                                               | 1         | 0.58%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                  | 1         | 0.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.58%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 1         | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1         | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 0.58%   |
| Realtek 802.11n NIC                                                  | 1         | 0.58%   |
| Ralink RT5370 Wireless Adapter                                       | 1         | 0.58%   |
| Ralink RT2070 Wireless Adapter                                       | 1         | 0.58%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 1         | 0.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1         | 0.58%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 1         | 0.58%   |
| MEDIATEK WLAN controller                                             | 1         | 0.58%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                        | 1         | 0.58%   |
| Intel WiFi Link 5100                                                 | 1         | 0.58%   |
| Intel Centrino Wireless-N 2230                                       | 1         | 0.58%   |
| Intel Centrino Ultimate-N 6300                                       | 1         | 0.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 1         | 0.58%   |
| Intel Centrino Advanced-N 6200                                       | 1         | 0.58%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 1         | 0.58%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU] | 1         | 0.58%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 1         | 0.58%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1         | 0.58%   |
| Broadcom BCM43142 802.11b/g/n                                        | 1         | 0.58%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 1         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 103       | 56.91%  |
| Intel                    | 58        | 32.04%  |
| Qualcomm Atheros         | 4         | 2.21%   |
| Broadcom                 | 4         | 2.21%   |
| ASIX Electronics         | 2         | 1.1%    |
| Aquantia                 | 2         | 1.1%    |
| Xiaomi                   | 1         | 0.55%   |
| Samsung Electronics      | 1         | 0.55%   |
| Mellanox Technologies    | 1         | 0.55%   |
| Marvell Technology Group | 1         | 0.55%   |
| Lenovo                   | 1         | 0.55%   |
| Huawei Technologies      | 1         | 0.55%   |
| Foxconn / Hon Hai        | 1         | 0.55%   |
| DisplayLink              | 1         | 0.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 72        | 38.3%   |
| Intel I211 Gigabit Network Connection                             | 18        | 9.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 5.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 5.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 4.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.72%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 2.66%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 2.13%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.6%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 1.06%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.06%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.06%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 1.06%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.06%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.06%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 1.06%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.06%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.06%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.53%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.53%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.53%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1         | 0.53%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.53%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 0.53%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.53%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1         | 0.53%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.53%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.53%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.53%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.53%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.53%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.53%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.53%   |
| Huawei JNY-LX1                                                    | 1         | 0.53%   |
| Foxconn / Hon Hai Nokia 7.1                                       | 1         | 0.53%   |
| DisplayLink dynadock U3.0                                         | 1         | 0.53%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.53%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 0.53%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1         | 0.53%   |
| Aquantia Ethernet controller                                      | 1         | 0.53%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 167       | 50.3%   |
| WiFi     | 164       | 49.4%   |
| Modem    | 1         | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 132       | 61.97%  |
| Ethernet | 81        | 38.03%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 107       | 52.71%  |
| 1     | 86        | 42.36%  |
| 3     | 10        | 4.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 155       | 76.35%  |
| Yes  | 48        | 23.65%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 84        | 54.19%  |
| Realtek Semiconductor           | 17        | 10.97%  |
| Qualcomm Atheros Communications | 12        | 7.74%   |
| Cambridge Silicon Radio         | 11        | 7.1%    |
| Lite-On Technology              | 8         | 5.16%   |
| Apple                           | 4         | 2.58%   |
| IMC Networks                    | 3         | 1.94%   |
| Foxconn / Hon Hai               | 3         | 1.94%   |
| Broadcom                        | 3         | 1.94%   |
| ASUSTek Computer                | 3         | 1.94%   |
| Realtek                         | 2         | 1.29%   |
| TP-Link                         | 1         | 0.65%   |
| Toshiba                         | 1         | 0.65%   |
| MediaTek                        | 1         | 0.65%   |
| HTC (High Tech Computer)        | 1         | 0.65%   |
| Dell                            | 1         | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                               | 22        | 14.19%  |
| Intel Bluetooth wireless interface                                                  | 19        | 12.26%  |
| Intel Bluetooth Device                                                              | 17        | 10.97%  |
| Realtek Bluetooth Radio                                                             | 12        | 7.74%   |
| Intel AX210 Bluetooth                                                               | 11        | 7.1%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 11        | 7.1%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 5.81%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 5.16%   |
| Lite-On Bluetooth Device                                                            | 4         | 2.58%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 1.94%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 3         | 1.94%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.94%   |
| Apple Bluetooth Host Controller                                                     | 3         | 1.94%   |
| Realtek Bluetooth Radio                                                             | 2         | 1.29%   |
| Lite-On Wireless_Device                                                             | 2         | 1.29%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.29%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.29%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 1.29%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 2         | 1.29%   |
| TP-Link UB500 Adapter                                                               | 1         | 0.65%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.65%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.65%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.65%   |
| MediaTek Wireless_Device                                                            | 1         | 0.65%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.65%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.65%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.65%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.65%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703)                | 1         | 0.65%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.65%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.65%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.65%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.65%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.65%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 1         | 0.65%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 133       | 40.06%  |
| AMD                         | 75        | 22.59%  |
| Nvidia                      | 60        | 18.07%  |
| C-Media Electronics         | 8         | 2.41%   |
| SteelSeries ApS             | 6         | 1.81%   |
| Realtek Semiconductor       | 5         | 1.51%   |
| Logitech                    | 5         | 1.51%   |
| Yamaha                      | 3         | 0.9%    |
| Kingston Technology         | 3         | 0.9%    |
| Blue Microphones            | 3         | 0.9%    |
| XMOS                        | 2         | 0.6%    |
| Texas Instruments           | 2         | 0.6%    |
| Sennheiser Communications   | 2         | 0.6%    |
| Samson Technologies         | 2         | 0.6%    |
| Razer USA                   | 2         | 0.6%    |
| Lenovo                      | 2         | 0.6%    |
| JMTek                       | 2         | 0.6%    |
| GN Netcom                   | 2         | 0.6%    |
| Focusrite-Novation          | 2         | 0.6%    |
| Valve Software              | 1         | 0.3%    |
| USB MICROPHONE              | 1         | 0.3%    |
| Superlux digit              | 1         | 0.3%    |
| Shure                       | 1         | 0.3%    |
| Plantronics                 | 1         | 0.3%    |
| Generalplus Technology      | 1         | 0.3%    |
| FiiO Electronics Technology | 1         | 0.3%    |
| Creative Labs               | 1         | 0.3%    |
| Cooler Master               | 1         | 0.3%    |
| Comtrue                     | 1         | 0.3%    |
| Arturia                     | 1         | 0.3%    |
| Apple                       | 1         | 0.3%    |
| Unknown                     | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 29        | 7.25%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 21        | 5.25%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 19        | 4.75%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 3.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 13        | 3.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 12        | 3%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 2.75%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 11        | 2.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 2.5%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 8         | 2%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 2%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 2%      |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 8         | 2%      |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 1.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 1.75%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 6         | 1.5%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 1.5%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 6         | 1.5%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.5%    |
| Intel CM238 HD Audio Controller                                                                   | 6         | 1.5%    |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.5%    |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.5%    |
| Nvidia Audio device                                                                               | 5         | 1.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.25%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 5         | 1.25%   |
| AMD Navi 10 HDMI Audio                                                                            | 5         | 1.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1%      |
| Nvidia TU104 HD Audio Controller                                                                  | 4         | 1%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1%      |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 1%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1%      |
| Nvidia GP108 High Definition Audio Controller                                                     | 3         | 0.75%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.75%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 0.75%   |
| Yamaha AG06/AG03                                                                                  | 2         | 0.5%    |
| SteelSeries ApS Arctis Pro Wireless                                                               | 2         | 0.5%    |
| Realtek Semiconductor USB2.0 Microphone                                                           | 2         | 0.5%    |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.5%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.5%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.5%    |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.5%    |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 0.5%    |
| Logitech Blue Microphones                                                                         | 2         | 0.5%    |
| Intel Comet Lake PCH-V cAVS                                                                       | 2         | 0.5%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.5%    |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 2         | 0.5%    |
| Intel Audio device                                                                                | 2         | 0.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 0.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 0.5%    |
| Focusrite-Novation Scarlett Solo USB                                                              | 2         | 0.5%    |
| C-Media Electronics USB Audio Device                                                              | 2         | 0.5%    |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 2         | 0.5%    |
| C-Media Electronics Blue Snowball                                                                 | 2         | 0.5%    |
| Blue Microphones Yeti Stereo Microphone                                                           | 2         | 0.5%    |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                                          | 2         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 37        | 20.56%  |
| Micron Technology   | 24        | 13.33%  |
| SK Hynix            | 23        | 12.78%  |
| Kingston            | 21        | 11.67%  |
| Crucial             | 19        | 10.56%  |
| G.Skill             | 16        | 8.89%   |
| Corsair             | 15        | 8.33%   |
| Unknown             | 4         | 2.22%   |
| Team                | 4         | 2.22%   |
| A-DATA Technology   | 4         | 2.22%   |
| Patriot             | 2         | 1.11%   |
| GOODRAM             | 2         | 1.11%   |
| Elpida              | 2         | 1.11%   |
| Unknown (ABCD)      | 1         | 0.56%   |
| Unknown (07F7)      | 1         | 0.56%   |
| Teikon              | 1         | 0.56%   |
| Silicon Power       | 1         | 0.56%   |
| Ramaxel Technology  | 1         | 0.56%   |
| Kingmax             | 1         | 0.56%   |
| Goldkey             | 1         | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 3         | 1.58%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 1.58%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 3         | 1.58%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 2         | 1.05%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.05%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.05%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.05%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.05%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.05%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 1.05%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 1.05%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 1.05%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 2         | 1.05%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 2         | 1.05%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 2         | 1.05%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s            | 2         | 1.05%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.53%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                        | 1         | 0.53%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 1         | 0.53%   |
| Unknown (07F7) RAM CMB6-5FAA1BAR01B00 4GB SODIMM DDR4 2133MT/s   | 1         | 0.53%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8192MB SODIMM DDR4 2400MT/s        | 1         | 0.53%   |
| Team RAM TEAMGROUP-UD4-4000 8GB DIMM DDR4 2400MT/s               | 1         | 0.53%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s               | 1         | 0.53%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 1         | 0.53%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s                       | 1         | 0.53%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1867MT/s                     | 1         | 0.53%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.53%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.53%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.53%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s             | 1         | 0.53%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.53%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 1         | 0.53%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 0.53%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.53%   |
| SK Hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s             | 1         | 0.53%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.53%   |
| SK Hynix RAM HMA82GU6CJR8N-VK 16GB DIMM DDR4 2667MT/s            | 1         | 0.53%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s       | 1         | 0.53%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.53%   |
| SK Hynix RAM HMA81GR7AFR8N-VK 8GB RIMM DDR4 2667MT/s             | 1         | 0.53%   |
| SK Hynix RAM HCNNNCPMBLHR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 0.53%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 0.53%   |
| Silicon Power RAM SP008GBLTU160N02 8GB DIMM DDR3 1600MT/s        | 1         | 0.53%   |
| Samsung RAM UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s       | 1         | 0.53%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 0.53%   |
| Samsung RAM Module 2GB SODIMM LPDDR3 1867MT/s                    | 1         | 0.53%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 0.53%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 0.53%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 0.53%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 1         | 0.53%   |
| Samsung RAM M471B5273DH0-YKO 4GB SODIMM DDR4 2400MT/s            | 1         | 0.53%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.53%   |
| Samsung RAM M471B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s              | 1         | 0.53%   |
| Samsung RAM M471B1G73BH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 0.53%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 0.53%   |
| Samsung RAM M471A2K43EB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 0.53%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 0.53%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 0.53%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 0.53%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 103       | 64.78%  |
| DDR3    | 37        | 23.27%  |
| LPDDR4  | 10        | 6.29%   |
| LPDDR3  | 4         | 2.52%   |
| Unknown | 3         | 1.89%   |
| SDRAM   | 2         | 1.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 82        | 52.23%  |
| DIMM         | 55        | 35.03%  |
| Row Of Chips | 19        | 12.1%   |
| RIMM         | 1         | 0.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 75        | 46.01%  |
| 16384 | 35        | 21.47%  |
| 4096  | 33        | 20.25%  |
| 32768 | 11        | 6.75%   |
| 2048  | 9         | 5.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 39        | 22.81%  |
| 2667  | 28        | 16.37%  |
| 1600  | 26        | 15.2%   |
| 2400  | 13        | 7.6%    |
| 3600  | 12        | 7.02%   |
| 4267  | 8         | 4.68%   |
| 2133  | 6         | 3.51%   |
| 1867  | 5         | 2.92%   |
| 1333  | 5         | 2.92%   |
| 3466  | 4         | 2.34%   |
| 3266  | 3         | 1.75%   |
| 4800  | 2         | 1.17%   |
| 4199  | 2         | 1.17%   |
| 3733  | 2         | 1.17%   |
| 3400  | 2         | 1.17%   |
| 3000  | 2         | 1.17%   |
| 2666  | 2         | 1.17%   |
| 6400  | 1         | 0.58%   |
| 4400  | 1         | 0.58%   |
| 4266  | 1         | 0.58%   |
| 4133  | 1         | 0.58%   |
| 3800  | 1         | 0.58%   |
| 3533  | 1         | 0.58%   |
| 3134  | 1         | 0.58%   |
| 1866  | 1         | 0.58%   |
| 1400  | 1         | 0.58%   |
| 1067  | 1         | 0.58%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)

![Printer Vendor](./All/images/line_chart/printer_vendor.svg)

| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)

![Printer Model](./All/images/line_chart/printer_model.svg)

| Model            | Computers | Percent |
|------------------|-----------|---------|
| Brother DCP-7040 | 1         | 100%    |

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
| Chicony Electronics                    | 37        | 24.34%  |
| Microdia                               | 18        | 11.84%  |
| Logitech                               | 18        | 11.84%  |
| Acer                                   | 17        | 11.18%  |
| IMC Networks                           | 14        | 9.21%   |
| Sunplus Innovation Technology          | 8         | 5.26%   |
| Realtek Semiconductor                  | 7         | 4.61%   |
| Quanta                                 | 5         | 3.29%   |
| Apple                                  | 4         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 1.97%   |
| Syntek                                 | 2         | 1.32%   |
| Microsoft                              | 2         | 1.32%   |
| MacroSilicon                           | 2         | 1.32%   |
| Luxvisions Innotech Limited            | 2         | 1.32%   |
| Lite-On Technology                     | 2         | 1.32%   |
| KYE Systems (Mouse Systems)            | 2         | 1.32%   |
| Alcor Micro                            | 2         | 1.32%   |
| Valve Software                         | 1         | 0.66%   |
| Suyin                                  | 1         | 0.66%   |
| Razer USA                              | 1         | 0.66%   |
| Oculus VR                              | 1         | 0.66%   |
| Lenovo                                 | 1         | 0.66%   |
| Creative Technology                    | 1         | 0.66%   |
| ARC International                      | 1         | 0.66%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 13        | 8.5%    |
| Microdia Integrated_Webcam_HD                       | 11        | 7.19%   |
| IMC Networks Integrated Camera                      | 8         | 5.23%   |
| Sunplus Integrated_Webcam_HD                        | 6         | 3.92%   |
| Acer Integrated Camera                              | 6         | 3.92%   |
| Chicony HD WebCam                                   | 5         | 3.27%   |
| Logitech Webcam C270                                | 4         | 2.61%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 2.61%   |
| Acer HD Webcam                                      | 4         | 2.61%   |
| Realtek Laptop Camera                               | 3         | 1.96%   |
| Logitech HD Webcam C525                             | 3         | 1.96%   |
| Logitech HD Pro Webcam C920                         | 3         | 1.96%   |
| Chicony USB2.0 Camera                               | 3         | 1.96%   |
| Syntek Integrated Camera                            | 2         | 1.31%   |
| Quanta HD User Facing                               | 2         | 1.31%   |
| Microdia USB 2.0 Camera                             | 2         | 1.31%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 1.31%   |
| MacroSilicon USB Video                              | 2         | 1.31%   |
| Logitech StreamCam                                  | 2         | 1.31%   |
| Logitech BRIO Ultra HD Webcam                       | 2         | 1.31%   |
| KYE Systems (Mouse Systems) Genius Webcam           | 2         | 1.31%   |
| Chicony USB2.0 HD UVC WebCam                        | 2         | 1.31%   |
| Chicony HP Truevision HD                            | 2         | 1.31%   |
| Chicony HD User Facing                              | 2         | 1.31%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 2         | 1.31%   |
| Apple FaceTime HD Camera (Built-in)                 | 2         | 1.31%   |
| Acer SunplusIT Integrated Camera                    | 2         | 1.31%   |
| Acer Lenovo EasyCamera                              | 2         | 1.31%   |
| Valve Software 3D Camera                            | 1         | 0.65%   |
| Suyin Sony Visual Communication Camera              | 1         | 0.65%   |
| Sunplus SPCA2281 Web Camera                         | 1         | 0.65%   |
| Sunplus Laptop Integrated Webcam FHD                | 1         | 0.65%   |
| Realtek USB Camera                                  | 1         | 0.65%   |
| Realtek Integrated Webcam                           | 1         | 0.65%   |
| Realtek HD Webcam - Realtek                         | 1         | 0.65%   |
| Realtek Acer 640 x 480 laptop camera                | 1         | 0.65%   |
| Razer USA Razer Kiyo Pro                            | 1         | 0.65%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 0.65%   |
| Quanta HP True Vision HD Camera                     | 1         | 0.65%   |
| Quanta HP HD Camera                                 | 1         | 0.65%   |
| Oculus VR Quest                                     | 1         | 0.65%   |
| Microsoft Surface Camera Front                      | 1         | 0.65%   |
| Microsoft LifeCam Cinema                            | 1         | 0.65%   |
| Microdia Webcam SC-10HDD12636P                      | 1         | 0.65%   |
| Microdia Laptop_Integrated_Webcam_1.3M              | 1         | 0.65%   |
| Microdia Integrated Webcam HD                       | 1         | 0.65%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 0.65%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 0.65%   |
| Logitech Webcam C310                                | 1         | 0.65%   |
| Logitech Webcam C170                                | 1         | 0.65%   |
| Logitech HD Webcam C615                             | 1         | 0.65%   |
| Logitech C922 Pro Stream Webcam                     | 1         | 0.65%   |
| Logitech C920 PRO HD Webcam                         | 1         | 0.65%   |
| Lite-On HP HD Webcam                                | 1         | 0.65%   |
| Lite-On HP 2.0MP High Definition Webcam             | 1         | 0.65%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 0.65%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 0.65%   |
| IMC Networks LG HD WebCam                           | 1         | 0.65%   |
| Creative VF0610 Live! Cam Socialize HD              | 1         | 0.65%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 11        | 40.74%  |
| Shenzhen Goodix Technology | 8         | 29.63%  |
| Validity Sensors           | 4         | 14.81%  |
| Elan Microelectronics      | 2         | 7.41%   |
| Upek                       | 1         | 3.7%    |
| AuthenTec                  | 1         | 3.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 5         | 18.52%  |
| Shenzhen Goodix  FingerPrint Device                       | 4         | 14.81%  |
| Unknown                                                   | 4         | 14.81%  |
| Shenzhen Goodix Fingerprint Reader                        | 2         | 7.41%   |
| Shenzhen Goodix FingerPrint                               | 2         | 7.41%   |
| Elan ELAN:Fingerprint                                     | 2         | 7.41%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 3.7%    |
| Validity Sensors VFS495 Fingerprint Reader                | 1         | 3.7%    |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 3.7%    |
| Validity Sensors Synaptics WBDI                           | 1         | 3.7%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 1         | 3.7%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 3.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 3.7%    |
| AuthenTec Fingerprint Sensor                              | 1         | 3.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./All/images/line_chart/chipcard_vendor.svg)

| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 41.67%  |
| Alcor Micro | 5         | 41.67%  |
| Yubico.com  | 1         | 8.33%   |
| Clay Logic  | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 41.67%  |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 8.33%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 8.33%   |
| Broadcom 5880                                                                | 1         | 8.33%   |
| Broadcom 58200                                                               | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 147       | 72.41%  |
| 1     | 44        | 21.67%  |
| 2     | 11        | 5.42%   |
| 3     | 1         | 0.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 26        | 37.68%  |
| Graphics card         | 10        | 14.49%  |
| Chipcard              | 9         | 13.04%  |
| Net/wireless          | 4         | 5.8%    |
| Multimedia controller | 4         | 5.8%    |
| Camera                | 4         | 5.8%    |
| Unassigned class      | 3         | 4.35%   |
| Sound                 | 2         | 2.9%    |
| Net/ethernet          | 2         | 2.9%    |
| Bluetooth             | 2         | 2.9%    |
| Wireless              | 1         | 1.45%   |
| Storage               | 1         | 1.45%   |
| Network               | 1         | 1.45%   |

