Manjaro - Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Manjaro/Desktop/README.md) and [notebooks](/Dist/Manjaro/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/linuxhw/TestCoverage)

Period: Jan, 2023.

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

| Name           | Computers | Percent |
|----------------|-----------|---------|
| Manjaro        | 87        | 48.88%  |
| Manjaro 22.0.0 | 48        | 26.97%  |
| Manjaro 22.0   | 24        | 13.48%  |
| Manjaro 22.0.1 | 18        | 10.11%  |
| Manjaro 21.0.7 | 1         | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Manjaro | 178       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 6.1.1-1-MANJARO       | 78        | 43.82%  |
| 5.15.85-1-MANJARO     | 36        | 20.22%  |
| 6.1.7-1-MANJARO       | 21        | 11.8%   |
| 6.0.15-1-MANJARO      | 7         | 3.93%   |
| 5.15.89-1-MANJARO     | 5         | 2.81%   |
| 5.19.17-2-MANJARO     | 4         | 2.25%   |
| 5.10.161-1-MANJARO    | 4         | 2.25%   |
| 5.10.164-1-MANJARO    | 3         | 1.69%   |
| 6.0.5-2-rt14-MANJARO  | 2         | 1.12%   |
| 6.0.19-3-MANJARO      | 2         | 1.12%   |
| 5.16.20-2-MANJARO     | 2         | 1.12%   |
| 6.2.0-2-MANJARO       | 1         | 0.56%   |
| 6.1.6-2-ck-generic-v3 | 1         | 0.56%   |
| 6.1.5-lqx2-1-lqx      | 1         | 0.56%   |
| 6.0.15-1-espMANJARO   | 1         | 0.56%   |
| 5.9.16-1-MANJARO      | 1         | 0.56%   |
| 5.19.16-2-MANJARO     | 1         | 0.56%   |
| 5.19.0-2-MANJARO      | 1         | 0.56%   |
| 5.18.0-4-rt11-MANJARO | 1         | 0.56%   |
| 5.15.84-1-MANJARO     | 1         | 0.56%   |
| 5.15.72-1-MANJARO     | 1         | 0.56%   |
| 5.15.65-1-MANJARO     | 1         | 0.56%   |
| 5.14.21-2-MANJARO     | 1         | 0.56%   |
| 5.13.19-2-MANJARO     | 1         | 0.56%   |
| 5.10.42-1-MANJARO     | 1         | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version  | Computers | Percent |
|----------|-----------|---------|
| 6.1.1    | 78        | 43.82%  |
| 5.15.85  | 36        | 20.22%  |
| 6.1.7    | 21        | 11.8%   |
| 6.0.15   | 8         | 4.49%   |
| 5.15.89  | 5         | 2.81%   |
| 5.19.17  | 4         | 2.25%   |
| 5.10.161 | 4         | 2.25%   |
| 5.10.164 | 3         | 1.69%   |
| 6.0.5    | 2         | 1.12%   |
| 6.0.19   | 2         | 1.12%   |
| 5.16.20  | 2         | 1.12%   |
| 6.2.0    | 1         | 0.56%   |
| 6.1.6    | 1         | 0.56%   |
| 6.1.5    | 1         | 0.56%   |
| 5.9.16   | 1         | 0.56%   |
| 5.19.16  | 1         | 0.56%   |
| 5.19.0   | 1         | 0.56%   |
| 5.18.0   | 1         | 0.56%   |
| 5.15.84  | 1         | 0.56%   |
| 5.15.72  | 1         | 0.56%   |
| 5.15.65  | 1         | 0.56%   |
| 5.14.21  | 1         | 0.56%   |
| 5.13.19  | 1         | 0.56%   |
| 5.10.42  | 1         | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 101       | 56.74%  |
| 5.15    | 44        | 24.72%  |
| 6.0     | 12        | 6.74%   |
| 5.10    | 8         | 4.49%   |
| 5.19    | 6         | 3.37%   |
| 5.16    | 2         | 1.12%   |
| 6.2     | 1         | 0.56%   |
| 5.9     | 1         | 0.56%   |
| 5.18    | 1         | 0.56%   |
| 5.14    | 1         | 0.56%   |
| 5.13    | 1         | 0.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 178       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 94        | 52.81%  |
| GNOME      | 43        | 24.16%  |
| XFCE       | 23        | 12.92%  |
| X-Cinnamon | 10        | 5.62%   |
| KDE        | 3         | 1.69%   |
| MATE       | 2         | 1.12%   |
| Unknown    | 2         | 1.12%   |
| i3         | 1         | 0.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 145       | 81.46%  |
| Wayland | 30        | 16.85%  |
| Tty     | 2         | 1.12%   |
| Unknown | 1         | 0.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 87        | 48.88%  |
| SDDM    | 43        | 24.16%  |
| LightDM | 28        | 15.73%  |
| GDM     | 19        | 10.67%  |
| LYNDE   | 1         | 0.56%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 74        | 41.57%  |
| en_GB   | 18        | 10.11%  |
| fr_FR   | 10        | 5.62%   |
| de_DE   | 9         | 5.06%   |
| ru_RU   | 7         | 3.93%   |
| pt_BR   | 7         | 3.93%   |
| pl_PL   | 6         | 3.37%   |
| it_IT   | 5         | 2.81%   |
| es_MX   | 5         | 2.81%   |
| nl_NL   | 4         | 2.25%   |
| es_ES   | 4         | 2.25%   |
| en_CA   | 4         | 2.25%   |
| pt_PT   | 2         | 1.12%   |
| es_CO   | 2         | 1.12%   |
| en_AU   | 2         | 1.12%   |
| de_AT   | 2         | 1.12%   |
| C       | 2         | 1.12%   |
| Unknown | 2         | 1.12%   |
| zh_TW   | 1         | 0.56%   |
| zh_CN   | 1         | 0.56%   |
| sv_SE   | 1         | 0.56%   |
| sl_SI   | 1         | 0.56%   |
| he_IL   | 1         | 0.56%   |
| fr_BE   | 1         | 0.56%   |
| es_PE   | 1         | 0.56%   |
| es_GT   | 1         | 0.56%   |
| es_CR   | 1         | 0.56%   |
| es_CL   | 1         | 0.56%   |
| es_AR   | 1         | 0.56%   |
| Default | 1         | 0.56%   |
| bg_BG   | 1         | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 102       | 57.3%   |
| EFI  | 76        | 42.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 147       | 82.58%  |
| Btrfs | 26        | 14.61%  |
| Xfs   | 3         | 1.69%   |
| Tmpfs | 2         | 1.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 88        | 49.44%  |
| Unknown | 81        | 45.51%  |
| MBR     | 9         | 5.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 162       | 91.01%  |
| Yes       | 16        | 8.99%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 139       | 78.09%  |
| Yes       | 39        | 21.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 33        | 18.54%  |
| Lenovo                               | 31        | 17.42%  |
| Hewlett-Packard                      | 22        | 12.36%  |
| Dell                                 | 17        | 9.55%   |
| Gigabyte Technology                  | 14        | 7.87%   |
| MSI                                  | 11        | 6.18%   |
| Acer                                 | 9         | 5.06%   |
| ASRock                               | 6         | 3.37%   |
| Apple                                | 6         | 3.37%   |
| Samsung Electronics                  | 3         | 1.69%   |
| Schenker                             | 2         | 1.12%   |
| Medion                               | 2         | 1.12%   |
| Intel                                | 2         | 1.12%   |
| AZW                                  | 2         | 1.12%   |
| Unknown                              | 2         | 1.12%   |
| TUXEDO                               | 1         | 0.56%   |
| Toshiba                              | 1         | 0.56%   |
| System76                             | 1         | 0.56%   |
| Sony                                 | 1         | 0.56%   |
| Shuttle                              | 1         | 0.56%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.56%   |
| realme                               | 1         | 0.56%   |
| PC Specialist                        | 1         | 0.56%   |
| Notebook                             | 1         | 0.56%   |
| Microsoft                            | 1         | 0.56%   |
| LG Electronics                       | 1         | 0.56%   |
| IPASON                               | 1         | 0.56%   |
| HUAWEI                               | 1         | 0.56%   |
| HONOR                                | 1         | 0.56%   |
| Biostar                              | 1         | 0.56%   |
| ALLDOCUBE                            | 1         | 0.56%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| MSI MS-7C37                                | 2         | 1.12%   |
| MSI MS-7C02                                | 2         | 1.12%   |
| Lenovo IdeaPad 5 14ALC05 82LM              | 2         | 1.12%   |
| HP Laptop 15s-eq2xxx                       | 2         | 1.12%   |
| HP EliteBook 840 G5                        | 2         | 1.12%   |
| Dell OptiPlex 755                          | 2         | 1.12%   |
| ASUS M5A97 R2.0                            | 2         | 1.12%   |
| ASUS All Series                            | 2         | 1.12%   |
| Unknown                                    | 2         | 1.12%   |
| TUXEDO Aura 15 Gen1                        | 1         | 0.56%   |
| Toshiba Satellite C50-C                    | 1         | 0.56%   |
| System76 Darter UltraThin                  | 1         | 0.56%   |
| Sony SVS1512U1RW                           | 1         | 0.56%   |
| Shuttle DS61                               | 1         | 0.56%   |
| Shenzhen Meigao Electronic Equipment UM560 | 1         | 0.56%   |
| Schenker XMG FUSION 15 (XFU15L19)          | 1         | 0.56%   |
| Schenker VISION 15 (SVS15E21)              | 1         | 0.56%   |
| Samsung R530/R730                          | 1         | 0.56%   |
| Samsung 730QDA                             | 1         | 0.56%   |
| Samsung 350V5C/351V5C/3540VC/3440VC        | 1         | 0.56%   |
| realme CloudProXXXX                        | 1         | 0.56%   |
| PC Specialist NH5x_7xRCx,RDx               | 1         | 0.56%   |
| Notebook L14xMU                            | 1         | 0.56%   |
| MSI Prestige 15 A11SCX                     | 1         | 0.56%   |
| MSI MS-7C96                                | 1         | 0.56%   |
| MSI MS-7C95                                | 1         | 0.56%   |
| MSI MS-7C09                                | 1         | 0.56%   |
| MSI MS-7851                                | 1         | 0.56%   |
| MSI Modern 14 A10RB                        | 1         | 0.56%   |
| MSI GS63 Stealth 8RE                       | 1         | 0.56%   |
| Microsoft Surface Book 3                   | 1         | 0.56%   |
| Medion E4251 MD61435                       | 1         | 0.56%   |
| Medion E4251                               | 1         | 0.56%   |
| LG 17Z90N-R.AAS9U1                         | 1         | 0.56%   |
| Lenovo Z50-75 80EC                         | 1         | 0.56%   |
| Lenovo Yoga 900-13ISK 80MK                 | 1         | 0.56%   |
| Lenovo Yoga 6 13ALC7 82UD                  | 1         | 0.56%   |
| Lenovo V15 G2 ITL 82KB                     | 1         | 0.56%   |
| Lenovo ThinkStation S30 43511K5            | 1         | 0.56%   |
| Lenovo ThinkPad X380 Yoga 20LJS0JK0A       | 1         | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 17        | 9.55%   |
| ASUS PRIME                                 | 8         | 4.49%   |
| ASUS ROG                                   | 7         | 3.93%   |
| HP Laptop                                  | 6         | 3.37%   |
| Dell OptiPlex                              | 6         | 3.37%   |
| Lenovo IdeaPad                             | 5         | 2.81%   |
| HP EliteBook                               | 5         | 2.81%   |
| Acer Aspire                                | 5         | 2.81%   |
| Dell Inspiron                              | 4         | 2.25%   |
| HP Pavilion                                | 3         | 1.69%   |
| Dell XPS                                   | 3         | 1.69%   |
| ASUS M5A97                                 | 3         | 1.69%   |
| MSI MS-7C37                                | 2         | 1.12%   |
| MSI MS-7C02                                | 2         | 1.12%   |
| Medion E4251                               | 2         | 1.12%   |
| Lenovo Yoga                                | 2         | 1.12%   |
| HP ProBook                                 | 2         | 1.12%   |
| HP OMEN                                    | 2         | 1.12%   |
| Dell Latitude                              | 2         | 1.12%   |
| ASUS VivoBook                              | 2         | 1.12%   |
| ASUS All                                   | 2         | 1.12%   |
| Acer Predator                              | 2         | 1.12%   |
| Unknown                                    | 2         | 1.12%   |
| TUXEDO Aura                                | 1         | 0.56%   |
| Toshiba Satellite                          | 1         | 0.56%   |
| System76 Darter                            | 1         | 0.56%   |
| Sony SVS1512U1RW                           | 1         | 0.56%   |
| Shuttle DS61                               | 1         | 0.56%   |
| Shenzhen Meigao Electronic Equipment UM560 | 1         | 0.56%   |
| Schenker XMG                               | 1         | 0.56%   |
| Schenker VISION                            | 1         | 0.56%   |
| Samsung R530                               | 1         | 0.56%   |
| Samsung 730QDA                             | 1         | 0.56%   |
| Samsung 350V5C                             | 1         | 0.56%   |
| realme CloudProXXXX                        | 1         | 0.56%   |
| PC Specialist NH5x                         | 1         | 0.56%   |
| Notebook L14xMU                            | 1         | 0.56%   |
| MSI Prestige                               | 1         | 0.56%   |
| MSI MS-7C96                                | 1         | 0.56%   |
| MSI MS-7C95                                | 1         | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 28        | 15.73%  |
| 2020 | 26        | 14.61%  |
| 2021 | 23        | 12.92%  |
| 2019 | 23        | 12.92%  |
| 2022 | 13        | 7.3%    |
| 2013 | 13        | 7.3%    |
| 2014 | 12        | 6.74%   |
| 2012 | 12        | 6.74%   |
| 2017 | 7         | 3.93%   |
| 2015 | 5         | 2.81%   |
| 2009 | 4         | 2.25%   |
| 2007 | 4         | 2.25%   |
| 2016 | 3         | 1.69%   |
| 2011 | 3         | 1.69%   |
| 2010 | 1         | 0.56%   |
| 2008 | 1         | 0.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 91        | 51.12%  |
| Desktop     | 69        | 38.76%  |
| Convertible | 8         | 4.49%   |
| Mini pc     | 4         | 2.25%   |
| All in one  | 4         | 2.25%   |
| Tablet      | 2         | 1.12%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 178       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 178       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 50        | 28.09%  |
| 4.01-8.0    | 33        | 18.54%  |
| 32.01-64.0  | 31        | 17.42%  |
| 8.01-16.0   | 31        | 17.42%  |
| 3.01-4.0    | 13        | 7.3%    |
| 24.01-32.0  | 11        | 6.18%   |
| 64.01-256.0 | 8         | 4.49%   |
| 1.01-2.0    | 1         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 52        | 29.21%  |
| 3.01-4.0   | 42        | 23.6%   |
| 2.01-3.0   | 31        | 17.42%  |
| 1.01-2.0   | 30        | 16.85%  |
| 8.01-16.0  | 17        | 9.55%   |
| 16.01-24.0 | 4         | 2.25%   |
| 32.01-64.0 | 1         | 0.56%   |
| 0.51-1.0   | 1         | 0.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 98        | 55.06%  |
| 2      | 44        | 24.72%  |
| 3      | 18        | 10.11%  |
| 4      | 8         | 4.49%   |
| 5      | 6         | 3.37%   |
| 9      | 2         | 1.12%   |
| 7      | 1         | 0.56%   |
| 6      | 1         | 0.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 138       | 77.53%  |
| Yes       | 40        | 22.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 145       | 81.46%  |
| No        | 33        | 18.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 146       | 82.02%  |
| No        | 32        | 17.98%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 131       | 73.6%   |
| No        | 47        | 26.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 32        | 17.98%  |
| Germany      | 15        | 8.43%   |
| France       | 13        | 7.3%    |
| Russia       | 12        | 6.74%   |
| Italy        | 8         | 4.49%   |
| Brazil       | 7         | 3.93%   |
| UK           | 6         | 3.37%   |
| Spain        | 6         | 3.37%   |
| Poland       | 6         | 3.37%   |
| Netherlands  | 6         | 3.37%   |
| Canada       | 4         | 2.25%   |
| Bulgaria     | 4         | 2.25%   |
| Turkey       | 3         | 1.69%   |
| Switzerland  | 3         | 1.69%   |
| Mexico       | 3         | 1.69%   |
| Indonesia    | 3         | 1.69%   |
| Colombia     | 3         | 1.69%   |
| Australia    | 3         | 1.69%   |
| Taiwan       | 2         | 1.12%   |
| Sweden       | 2         | 1.12%   |
| Slovenia     | 2         | 1.12%   |
| Portugal     | 2         | 1.12%   |
| India        | 2         | 1.12%   |
| Chile        | 2         | 1.12%   |
| Austria      | 2         | 1.12%   |
| Argentina    | 2         | 1.12%   |
| Uzbekistan   | 1         | 0.56%   |
| Ukraine      | 1         | 0.56%   |
| Thailand     | 1         | 0.56%   |
| Saudi Arabia | 1         | 0.56%   |
| Romania      | 1         | 0.56%   |
| Peru         | 1         | 0.56%   |
| Oman         | 1         | 0.56%   |
| Nicaragua    | 1         | 0.56%   |
| Kenya        | 1         | 0.56%   |
| Kazakhstan   | 1         | 0.56%   |
| Japan        | 1         | 0.56%   |
| Iran         | 1         | 0.56%   |
| Guatemala    | 1         | 0.56%   |
| Ghana        | 1         | 0.56%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City             | Computers | Percent |
|------------------|-----------|---------|
| St Petersburg    | 3         | 1.69%   |
| Moscow           | 3         | 1.69%   |
| Leeds            | 3         | 1.69%   |
| Warsaw           | 2         | 1.12%   |
| Vienna           | 2         | 1.12%   |
| Sao Paulo        | 2         | 1.12%   |
| San Antonio      | 2         | 1.12%   |
| New York         | 2         | 1.12%   |
| Narbonne         | 2         | 1.12%   |
| Mexico City      | 2         | 1.12%   |
| Madrid           | 2         | 1.12%   |
| Istanbul         | 2         | 1.12%   |
| Hamburg          | 2         | 1.12%   |
| Bogotá          | 2         | 1.12%   |
| Blaricum         | 2         | 1.12%   |
| Amsterdam        | 2         | 1.12%   |
| Zweibrücken     | 1         | 0.56%   |
| Zaragoza         | 1         | 0.56%   |
| Yekaterinburg    | 1         | 0.56%   |
| Winston-Salem    | 1         | 0.56%   |
| Wallisellen      | 1         | 0.56%   |
| Waldshut-Tiengen | 1         | 0.56%   |
| Vinton           | 1         | 0.56%   |
| Varna            | 1         | 0.56%   |
| Urbana           | 1         | 0.56%   |
| Tucson           | 1         | 0.56%   |
| Tübingen        | 1         | 0.56%   |
| Tokyo            | 1         | 0.56%   |
| Tehran           | 1         | 0.56%   |
| Tashkent         | 1         | 0.56%   |
| Taman Sari       | 1         | 0.56%   |
| Taipei           | 1         | 0.56%   |
| Syktyvkar        | 1         | 0.56%   |
| Sydney           | 1         | 0.56%   |
| Sundbyberg       | 1         | 0.56%   |
| Stuttgart        | 1         | 0.56%   |
| Spokane          | 1         | 0.56%   |
| Sofia            | 1         | 0.56%   |
| Simferopol       | 1         | 0.56%   |
| Shanghai         | 1         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 45        | 54     | 15.31%  |
| WDC                          | 37        | 47     | 12.59%  |
| Seagate                      | 31        | 40     | 10.54%  |
| SanDisk                      | 26        | 28     | 8.84%   |
| Kingston                     | 15        | 15     | 5.1%    |
| Toshiba                      | 12        | 12     | 4.08%   |
| SK hynix                     | 12        | 12     | 4.08%   |
| Crucial                      | 12        | 12     | 4.08%   |
| Intel                        | 9         | 10     | 3.06%   |
| Silicon Motion               | 8         | 9      | 2.72%   |
| A-DATA Technology            | 6         | 7      | 2.04%   |
| Kingston Technology Company  | 5         | 6      | 1.7%    |
| China                        | 5         | 5      | 1.7%    |
| Phison Electronics           | 4         | 4      | 1.36%   |
| Micron Technology            | 4         | 4      | 1.36%   |
| Hitachi                      | 4         | 5      | 1.36%   |
| Unknown                      | 3         | 5      | 1.02%   |
| Micron/Crucial Technology    | 3         | 3      | 1.02%   |
| KIOXIA                       | 3         | 3      | 1.02%   |
| HGST                         | 3         | 3      | 1.02%   |
| GOODRAM                      | 3         | 4      | 1.02%   |
| ADATA Technology             | 3         | 3      | 1.02%   |
| Union Memory (Shenzhen)      | 2         | 2      | 0.68%   |
| Phison                       | 2         | 2      | 0.68%   |
| Patriot                      | 2         | 2      | 0.68%   |
| Leven                        | 2         | 2      | 0.68%   |
| Lenovo                       | 2         | 2      | 0.68%   |
| JMicron Technology           | 2         | 2      | 0.68%   |
| Apple                        | 2         | 2      | 0.68%   |
| Unknown                      | 2         | 2      | 0.68%   |
| WD MediaMax                  | 1         | 1      | 0.34%   |
| V-GeN                        | 1         | 1      | 0.34%   |
| TwinMOS                      | 1         | 1      | 0.34%   |
| TO Exter                     | 1         | 1      | 0.34%   |
| Thinkplus                    | 1         | 1      | 0.34%   |
| SPCC                         | 1         | 1      | 0.34%   |
| Solid State Storage          | 1         | 1      | 0.34%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.34%   |
| Seagate Technology           | 1         | 1      | 0.34%   |
| Realtek Semiconductor        | 1         | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB               | 14        | 4.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB              | 7         | 2.2%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB             | 5         | 1.57%   |
| Samsung SSD 980 1TB                                               | 5         | 1.57%   |
| Kingston SA400S37240G 240GB SSD                                   | 5         | 1.57%   |
| WDC WD30EZRZ-00Z5HB0 3TB                                          | 3         | 0.94%   |
| Seagate ST2000LM007-1R8174 2TB                                    | 3         | 0.94%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1TB                    | 3         | 0.94%   |
| Samsung SSD 860 EVO 500GB                                         | 3         | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB               | 3         | 0.94%   |
| Kingston Company A2000 NVMe SSD 1TB                               | 3         | 0.94%   |
| Kingston SA400S37960G 960GB SSD                                   | 3         | 0.94%   |
| Crucial CT500MX500SSD1 500GB                                      | 3         | 0.94%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 256GB | 3         | 0.94%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                                    | 2         | 0.63%   |
| WDC WD40EZRZ-00WN9B0 4TB                                          | 2         | 0.63%   |
| WDC WD40EFRX-68N32N0 4TB                                          | 2         | 0.63%   |
| WDC WD10SPZX-21Z10T0 1TB                                          | 2         | 0.63%   |
| WDC WD10JPVX-60JC3T0 1TB                                          | 2         | 0.63%   |
| WDC WD10EZEX-08WN4A0 1TB                                          | 2         | 0.63%   |
| Unknown MMC Card  128GB                                           | 2         | 0.63%   |
| Toshiba MQ04ABF100 1TB                                            | 2         | 0.63%   |
| Toshiba DT01ACA200 2TB                                            | 2         | 0.63%   |
| Toshiba BG3 NVMe SSD Controller 256GB                             | 2         | 0.63%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB                            | 2         | 0.63%   |
| SK hynix BC501 NVMe Solid State Drive 512GB                       | 2         | 0.63%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB                 | 2         | 0.63%   |
| Seagate ST500DM002-1BD142 500GB                                   | 2         | 0.63%   |
| Seagate ST4000DM004-2CV104 4TB                                    | 2         | 0.63%   |
| Seagate ST2000DM008-2FR102 2TB                                    | 2         | 0.63%   |
| Seagate ST1000LX015-1U7172 1TB                                    | 2         | 0.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                                | 2         | 0.63%   |
| Sandisk WD_BLACK SN770 2TB                                        | 2         | 0.63%   |
| Sandisk WD Blue SN570 1TB                                         | 2         | 0.63%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                                | 2         | 0.63%   |
| Sandisk WD Black SN850 2TB                                        | 2         | 0.63%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD 512GB             | 2         | 0.63%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD                               | 2         | 0.63%   |
| Samsung MZALQ512HBLU-00BL2 512GB                                  | 2         | 0.63%   |
| Phison E16 PCIe4 NVMe Controller 2TB                              | 2         | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 31        | 38     | 36.9%   |
| Seagate             | 29        | 34     | 34.52%  |
| Toshiba             | 10        | 10     | 11.9%   |
| Samsung Electronics | 4         | 4      | 4.76%   |
| Hitachi             | 4         | 5      | 4.76%   |
| HGST                | 3         | 3      | 3.57%   |
| Maxtor              | 1         | 1      | 1.19%   |
| Intenso             | 1         | 1      | 1.19%   |
| ASMT                | 1         | 1      | 1.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 12        | 12     | 12.63%  |
| Crucial             | 12        | 12     | 12.63%  |
| Samsung Electronics | 10        | 10     | 10.53%  |
| SanDisk             | 8         | 10     | 8.42%   |
| WDC                 | 7         | 9      | 7.37%   |
| A-DATA Technology   | 6         | 7      | 6.32%   |
| China               | 5         | 5      | 5.26%   |
| SK hynix            | 3         | 3      | 3.16%   |
| GOODRAM             | 3         | 4      | 3.16%   |
| Patriot             | 2         | 2      | 2.11%   |
| Leven               | 2         | 2      | 2.11%   |
| Intel               | 2         | 2      | 2.11%   |
| Apple               | 2         | 2      | 2.11%   |
| Unknown             | 2         | 2      | 2.11%   |
| V-GeN               | 1         | 1      | 1.05%   |
| TwinMOS             | 1         | 1      | 1.05%   |
| TO Exter            | 1         | 1      | 1.05%   |
| Thinkplus           | 1         | 1      | 1.05%   |
| SPCC                | 1         | 1      | 1.05%   |
| Seagate             | 1         | 1      | 1.05%   |
| PNY                 | 1         | 1      | 1.05%   |
| Phison              | 1         | 1      | 1.05%   |
| OCZ                 | 1         | 2      | 1.05%   |
| Micron Technology   | 1         | 1      | 1.05%   |
| LITEONIT            | 1         | 1      | 1.05%   |
| Lexar               | 1         | 1      | 1.05%   |
| KLEVV               | 1         | 1      | 1.05%   |
| KingSpec            | 1         | 1      | 1.05%   |
| JMicron Technology  | 1         | 1      | 1.05%   |
| Initio              | 1         | 1      | 1.05%   |
| HS-SSD-C100         | 1         | 1      | 1.05%   |
| Gigabyte Technology | 1         | 1      | 1.05%   |
| Corsair             | 1         | 1      | 1.05%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 101       | 120    | 38.7%   |
| SSD     | 80        | 102    | 30.65%  |
| HDD     | 71        | 97     | 27.2%   |
| Unknown | 7         | 15     | 2.68%   |
| MMC     | 2         | 2      | 0.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 114       | 192    | 49.57%  |
| NVMe | 101       | 120    | 43.91%  |
| SAS  | 13        | 22     | 5.65%   |
| MMC  | 2         | 2      | 0.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 70        | 97     | 44.87%  |
| 0.51-1.0   | 54        | 62     | 34.62%  |
| 1.01-2.0   | 14        | 16     | 8.97%   |
| 3.01-4.0   | 6         | 9      | 3.85%   |
| 2.01-3.0   | 6         | 7      | 3.85%   |
| 4.01-10.0  | 5         | 7      | 3.21%   |
| 10.01-20.0 | 1         | 1      | 0.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 45        | 25.28%  |
| 501-1000       | 30        | 16.85%  |
| 101-250        | 29        | 16.29%  |
| 1001-2000      | 23        | 12.92%  |
| Unknown        | 18        | 10.11%  |
| More than 3000 | 16        | 8.99%   |
| 2001-3000      | 11        | 6.18%   |
| 1-20           | 3         | 1.69%   |
| 51-100         | 3         | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 32        | 17.98%  |
| 101-250        | 24        | 13.48%  |
| 1-20           | 23        | 12.92%  |
| 51-100         | 23        | 12.92%  |
| 21-50          | 22        | 12.36%  |
| 501-1000       | 19        | 10.67%  |
| Unknown        | 18        | 10.11%  |
| 1001-2000      | 7         | 3.93%   |
| More than 3000 | 6         | 3.37%   |
| 2001-3000      | 4         | 2.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD30EZRZ-00Z5HB0 3TB        | 1         | 1      | 12.5%   |
| WDC WD30EFRX-68EUZN0 3TB        | 1         | 1      | 12.5%   |
| TwinMOS SSD 128GB               | 1         | 1      | 12.5%   |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 12.5%   |
| Seagate ST250DM000-1BD141 250GB | 1         | 1      | 12.5%   |
| SanDisk SSD PLUS 240 GB         | 1         | 1      | 12.5%   |
| KingSpec P3-128 128GB SSD       | 1         | 1      | 12.5%   |
| Crucial CT525MX300SSD1 528GB    | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 2         | 2      | 25%     |
| Seagate  | 2         | 2      | 25%     |
| TwinMOS  | 1         | 1      | 12.5%   |
| SanDisk  | 1         | 1      | 12.5%   |
| KingSpec | 1         | 1      | 12.5%   |
| Crucial  | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 50%     |
| Seagate | 2         | 2      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 4         | 4      | 50%     |
| HDD  | 4         | 4      | 50%     |

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
| Detected | 120       | 226    | 62.83%  |
| Works    | 64        | 102    | 33.51%  |
| Malfunc  | 7         | 8      | 3.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 84        | 32.56%  |
| AMD                            | 55        | 21.32%  |
| Samsung Electronics            | 37        | 14.34%  |
| SanDisk                        | 17        | 6.59%   |
| SK hynix                       | 9         | 3.49%   |
| Silicon Motion                 | 8         | 3.1%    |
| Kingston Technology Company    | 8         | 3.1%    |
| Phison Electronics             | 5         | 1.94%   |
| ASMedia Technology             | 5         | 1.94%   |
| Micron/Crucial Technology      | 3         | 1.16%   |
| Micron Technology              | 3         | 1.16%   |
| Marvell Technology Group       | 3         | 1.16%   |
| KIOXIA                         | 3         | 1.16%   |
| ADATA Technology               | 3         | 1.16%   |
| Union Memory (Shenzhen)        | 2         | 0.78%   |
| Toshiba America Info Systems   | 2         | 0.78%   |
| Lenovo                         | 2         | 0.78%   |
| JMicron Technology             | 2         | 0.78%   |
| Solid State Storage Technology | 1         | 0.39%   |
| Silicon Image                  | 1         | 0.39%   |
| Shenzhen Longsys Electronics   | 1         | 0.39%   |
| Seagate Technology             | 1         | 0.39%   |
| Realtek Semiconductor          | 1         | 0.39%   |
| Promise Technology             | 1         | 0.39%   |
| Nvidia                         | 1         | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 39        | 13.88%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 14        | 4.98%   |
| Samsung NVMe SSD Controller 980                                                | 12        | 4.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9         | 3.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 8         | 2.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 2.85%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 2.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 2.49%   |
| AMD 500 Series Chipset SATA Controller                                         | 7         | 2.49%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 6         | 2.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 2.14%   |
| SanDisk Non-Volatile memory controller                                         | 5         | 1.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 1.78%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 1.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 1.78%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 4         | 1.42%   |
| Kingston Company Company Non-Volatile memory controller                        | 4         | 1.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 1.42%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.42%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 3         | 1.07%   |
| Micron Non-Volatile memory controller                                          | 3         | 1.07%   |
| Kingston Company A2000 NVMe SSD                                                | 3         | 1.07%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.07%   |
| Intel Non-Volatile memory controller                                           | 3         | 1.07%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 3         | 1.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 1.07%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3         | 1.07%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 0.71%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.71%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 0.71%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 0.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 0.71%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.71%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.71%   |
| Samsung Apple PCIe SSD                                                         | 2         | 0.71%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.71%   |
| Micron/Crucial NVMe Controller                                                 | 2         | 0.71%   |
| Lenovo Non-Volatile memory controller                                          | 2         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 123       | 49.6%   |
| NVMe | 99        | 39.92%  |
| RAID | 15        | 6.05%   |
| IDE  | 10        | 4.03%   |
| SAS  | 1         | 0.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 108       | 60.67%  |
| AMD    | 70        | 39.33%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5700U with Radeon Graphics        | 6         | 3.37%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 2.25%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.69%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 1.69%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.69%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.69%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.69%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 1.69%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 1.69%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 1.12%   |
| Intel Core i7-4770S CPU @ 3.10GHz             | 2         | 1.12%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.12%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 1.12%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 2         | 1.12%   |
| Intel 12th Gen Core i7-1260P                  | 2         | 1.12%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 1.12%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 2         | 1.12%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 2         | 1.12%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.12%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 2         | 1.12%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 2         | 1.12%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 2         | 1.12%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.12%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 2         | 1.12%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 2         | 1.12%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 1.12%   |
| AMD FX-8350 Eight-Core Processor              | 2         | 1.12%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz           | 1         | 0.56%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz            | 1         | 0.56%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz           | 1         | 0.56%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz           | 1         | 0.56%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 1         | 0.56%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 1         | 0.56%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.56%   |
| Intel Core i7-8700T CPU @ 2.40GHz             | 1         | 0.56%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 0.56%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.56%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 37        | 20.79%  |
| Intel Core i5           | 30        | 16.85%  |
| AMD Ryzen 7             | 22        | 12.36%  |
| AMD Ryzen 5             | 21        | 11.8%   |
| Other                   | 14        | 7.87%   |
| Intel Celeron           | 7         | 3.93%   |
| AMD FX                  | 6         | 3.37%   |
| Intel Core i3           | 5         | 2.81%   |
| Intel Core 2 Duo        | 5         | 2.81%   |
| AMD Ryzen 9             | 5         | 2.81%   |
| Intel Xeon              | 4         | 2.25%   |
| AMD Ryzen 3             | 4         | 2.25%   |
| Intel Core i9           | 2         | 1.12%   |
| Intel Core 2 Quad       | 2         | 1.12%   |
| AMD Ryzen 7 PRO         | 2         | 1.12%   |
| AMD A8                  | 2         | 1.12%   |
| AMD A10                 | 2         | 1.12%   |
| Intel Core 2            | 1         | 0.56%   |
| Intel Celeron Dual-Core | 1         | 0.56%   |
| AMD Ryzen 5 PRO         | 1         | 0.56%   |
| AMD PRO A10             | 1         | 0.56%   |
| AMD Phenom II X4        | 1         | 0.56%   |
| AMD E1                  | 1         | 0.56%   |
| AMD Athlon              | 1         | 0.56%   |
| AMD A6                  | 1         | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 63        | 35.39%  |
| 2      | 44        | 24.72%  |
| 6      | 35        | 19.66%  |
| 8      | 28        | 15.73%  |
| 12     | 5         | 2.81%   |
| 24     | 1         | 0.56%   |
| 16     | 1         | 0.56%   |
| 1      | 1         | 0.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 178       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 150       | 84.27%  |
| 1      | 28        | 15.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 178       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 98        | 55.06%  |
| 0x0a50000c | 6         | 3.37%   |
| 0x806ea    | 5         | 2.81%   |
| 0x08600106 | 5         | 2.81%   |
| 0x906ea    | 4         | 2.25%   |
| 0x306c3    | 4         | 2.25%   |
| 0x306a9    | 4         | 2.25%   |
| 0x08608103 | 4         | 2.25%   |
| 0xa0652    | 3         | 1.69%   |
| 0x806c1    | 3         | 1.69%   |
| 0x706e5    | 3         | 1.69%   |
| 0x40651    | 3         | 1.69%   |
| 0x08701021 | 3         | 1.69%   |
| 0x1067a    | 2         | 1.12%   |
| 0x0a50000d | 2         | 1.12%   |
| 0x0a404102 | 2         | 1.12%   |
| 0x0a201016 | 2         | 1.12%   |
| 0x08600104 | 2         | 1.12%   |
| 0x06000852 | 2         | 1.12%   |
| 0xb0671    | 1         | 0.56%   |
| 0xa0671    | 1         | 0.56%   |
| 0x906ed    | 1         | 0.56%   |
| 0x806ec    | 1         | 0.56%   |
| 0x806eb    | 1         | 0.56%   |
| 0x806e9    | 1         | 0.56%   |
| 0x706a1    | 1         | 0.56%   |
| 0x506e3    | 1         | 0.56%   |
| 0x406e3    | 1         | 0.56%   |
| 0x40661    | 1         | 0.56%   |
| 0x306e4    | 1         | 0.56%   |
| 0x0a601203 | 1         | 0.56%   |
| 0x0a50000b | 1         | 0.56%   |
| 0x0a201009 | 1         | 0.56%   |
| 0x08701013 | 1         | 0.56%   |
| 0x08608102 | 1         | 0.56%   |
| 0x08108102 | 1         | 0.56%   |
| 0x0800820d | 1         | 0.56%   |
| 0x06003106 | 1         | 0.56%   |
| 0x0600111f | 1         | 0.56%   |
| 0x0600063e | 1         | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 35        | 19.66%  |
| Zen 3         | 18        | 10.11%  |
| Haswell       | 17        | 9.55%   |
| Unknown       | 17        | 9.55%   |
| Zen 2         | 16        | 8.99%   |
| IvyBridge     | 11        | 6.18%   |
| Zen+          | 9         | 5.06%   |
| TigerLake     | 8         | 4.49%   |
| Piledriver    | 7         | 3.93%   |
| IceLake       | 5         | 2.81%   |
| Goldmont plus | 5         | 2.81%   |
| Core          | 5         | 2.81%   |
| Steamroller   | 4         | 2.25%   |
| Skylake       | 4         | 2.25%   |
| Penryn        | 4         | 2.25%   |
| SandyBridge   | 3         | 1.69%   |
| CometLake     | 3         | 1.69%   |
| Zen           | 1         | 0.56%   |
| Westmere      | 1         | 0.56%   |
| Silvermont    | 1         | 0.56%   |
| K10           | 1         | 0.56%   |
| Jaguar        | 1         | 0.56%   |
| Bulldozer     | 1         | 0.56%   |
| Broadwell     | 1         | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 87        | 40.65%  |
| AMD    | 65        | 30.37%  |
| Nvidia | 62        | 28.97%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                | 9         | 4.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 9         | 4.04%   |
| AMD Lucienne                                                                          | 9         | 4.04%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 8         | 3.59%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 8         | 3.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 7         | 3.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 7         | 3.14%   |
| AMD Renoir                                                                            | 6         | 2.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 5         | 2.24%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 5         | 2.24%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 5         | 2.24%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 4         | 1.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 4         | 1.79%   |
| Nvidia GP108M [GeForce MX250]                                                         | 3         | 1.35%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                    | 3         | 1.35%   |
| Nvidia GM107 [GeForce GTX 750]                                                        | 3         | 1.35%   |
| Intel HD Graphics 620                                                                 | 3         | 1.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 3         | 1.35%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 3         | 1.35%   |
| Nvidia TU116 [GeForce GTX 1660]                                                       | 2         | 0.9%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 2         | 0.9%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 2         | 0.9%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 0.9%    |
| Nvidia GP104 [GeForce GTX 1070]                                                       | 2         | 0.9%    |
| Nvidia GK208B [GeForce GT 710]                                                        | 2         | 0.9%    |
| Nvidia GF119 [NVS 310]                                                                | 2         | 0.9%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 2         | 0.9%    |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                     | 2         | 0.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 0.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 2         | 0.9%    |
| Intel Iris Plus Graphics G7                                                           | 2         | 0.9%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 2         | 0.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 0.9%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 2         | 0.9%    |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 2         | 0.9%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 0.9%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 0.9%    |
| AMD Rembrandt [Radeon 680M]                                                           | 2         | 0.9%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                            | 2         | 0.9%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                  | 2         | 0.9%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 55        | 30.9%   |
| 1 x AMD        | 49        | 27.53%  |
| 1 x Nvidia     | 31        | 17.42%  |
| Intel + Nvidia | 26        | 14.61%  |
| 2 x AMD        | 8         | 4.49%   |
| Intel + AMD    | 4         | 2.25%   |
| AMD + Nvidia   | 4         | 2.25%   |
| 2 x Nvidia     | 1         | 0.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 127       | 71.35%  |
| Proprietary | 51        | 28.65%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 108       | 60.67%  |
| 0.01-0.5   | 17        | 9.55%   |
| 3.01-4.0   | 12        | 6.74%   |
| 1.01-2.0   | 10        | 5.62%   |
| 7.01-8.0   | 9         | 5.06%   |
| 0.51-1.0   | 8         | 4.49%   |
| 5.01-6.0   | 5         | 2.81%   |
| 2.01-3.0   | 5         | 2.81%   |
| 8.01-16.0  | 3         | 1.69%   |
| 16.01-24.0 | 1         | 0.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 31        | 14.35%  |
| Samsung Electronics     | 24        | 11.11%  |
| Chimei Innolux          | 18        | 8.33%   |
| LG Display              | 17        | 7.87%   |
| Goldstar                | 13        | 6.02%   |
| AU Optronics            | 13        | 6.02%   |
| Hewlett-Packard         | 12        | 5.56%   |
| Dell                    | 10        | 4.63%   |
| AOC                     | 9         | 4.17%   |
| Acer                    | 9         | 4.17%   |
| LG Electronics          | 6         | 2.78%   |
| ViewSonic               | 4         | 1.85%   |
| Sharp                   | 4         | 1.85%   |
| BenQ                    | 4         | 1.85%   |
| Apple                   | 4         | 1.85%   |
| Ancor Communications    | 4         | 1.85%   |
| Sony                    | 3         | 1.39%   |
| Unknown                 | 3         | 1.39%   |
| Unknown                 | 2         | 0.93%   |
| Toshiba                 | 2         | 0.93%   |
| Sceptre Tech            | 2         | 0.93%   |
| Philips                 | 2         | 0.93%   |
| PANDA                   | 2         | 0.93%   |
| Panasonic               | 2         | 0.93%   |
| Lenovo Group Limited    | 2         | 0.93%   |
| Lenovo                  | 2         | 0.93%   |
| InfoVision              | 2         | 0.93%   |
| Chi Mei Optoelectronics | 2         | 0.93%   |
| ASUSTek Computer        | 2         | 0.93%   |
| Olevia                  | 1         | 0.46%   |
| Mi                      | 1         | 0.46%   |
| Idek Iiyama             | 1         | 0.46%   |
| HPN                     | 1         | 0.46%   |
| HKC                     | 1         | 0.46%   |
| Hitachi                 | 1         | 0.46%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Unknown                                                              | 3         | 1.37%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch         | 2         | 0.91%   |
| LG Electronics LCD Monitor 22MP55 1920x1080                          | 2         | 0.91%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 2         | 0.91%   |
| Goldstar 25UM58G GSM5B98 2560x1080 670x280mm 28.6-inch               | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch     | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 0.91%   |
| BOE LCD Monitor BOE0852 1920x1080 344x194mm 15.5-inch                | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.91%   |
| AOC AG322QWS4R4 AOC3220 2560x1440 697x392mm 31.5-inch                | 2         | 0.91%   |
| ViewSonic VG2449 Series VSCF332 1920x1080 521x293mm 23.5-inch        | 1         | 0.46%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch        | 1         | 0.46%   |
| ViewSonic VA2419 Series VSC7B32 1920x1080 527x296mm 23.8-inch        | 1         | 0.46%   |
| ViewSonic VA2359 Series VSC6332 1920x1080 509x286mm 23.0-inch        | 1         | 0.46%   |
| Unknown LCD Monitor TXD HDMI                                         | 1         | 0.46%   |
| Unknown LCD Monitor SAMSUNG                                          | 1         | 0.46%   |
| Toshiba TV TSB0200 1360x768 409x230mm 18.5-inch                      | 1         | 0.46%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                     | 1         | 0.46%   |
| Sony TV SNYE903 1920x1080                                            | 1         | 0.46%   |
| Sony TV SNY9600 1920x540 735x420mm 33.3-inch                         | 1         | 0.46%   |
| Sony TV *06 SNYB203 1920x1080 1218x685mm 55.0-inch                   | 1         | 0.46%   |
| Sharp PN-K321 SHP21DD 3840x2160                                      | 1         | 0.46%   |
| Sharp LCD Monitor SHP1548 1920x1200 288x180mm 13.4-inch              | 1         | 0.46%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch              | 1         | 0.46%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch              | 1         | 0.46%   |
| Sceptre Tech W50 SPT13C5 3840x2160 575x323mm 26.0-inch               | 1         | 0.46%   |
| Sceptre Tech E22 SPT08D5 1920x1080 470x300mm 22.0-inch               | 1         | 0.46%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch    | 1         | 0.46%   |
| Samsung Electronics T28C570 SAM0AFC 1920x1080 649x369mm 29.4-inch    | 1         | 0.46%   |
| Samsung Electronics T24D391 SAM0B73 1920x1080 521x293mm 23.5-inch    | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM020D 1280x1024 338x270mm 17.0-inch | 1         | 0.46%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch | 1         | 0.46%   |
| Samsung Electronics S24R35x SAM100E 1920x1080 527x296mm 23.8-inch    | 1         | 0.46%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 1         | 0.46%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 1         | 0.46%   |
| Samsung Electronics LCD Monitor T27B750 1920x1080                    | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                 | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SyncMaster                           | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch | 1         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 103       | 51.24%  |
| 1366x768 (WXGA)    | 17        | 8.46%   |
| 3840x2160 (4K)     | 15        | 7.46%   |
| 2560x1440 (QHD)    | 13        | 6.47%   |
| Unknown            | 7         | 3.48%   |
| 1280x1024 (SXGA)   | 5         | 2.49%   |
| 2560x1600          | 4         | 1.99%   |
| 2560x1080          | 4         | 1.99%   |
| 1920x1200 (WUXGA)  | 4         | 1.99%   |
| 1440x900 (WXGA+)   | 4         | 1.99%   |
| 3440x1440          | 3         | 1.49%   |
| 1600x900 (HD+)     | 3         | 1.49%   |
| 1280x800 (WXGA)    | 3         | 1.49%   |
| 7680x2160          | 2         | 1%      |
| 3360x1080          | 2         | 1%      |
| 6000x1440          | 1         | 0.5%    |
| 4960x1080          | 1         | 0.5%    |
| 3840x1080          | 1         | 0.5%    |
| 3200x1800 (QHD+)   | 1         | 0.5%    |
| 2944x1080          | 1         | 0.5%    |
| 2880x1800          | 1         | 0.5%    |
| 2880x1620          | 1         | 0.5%    |
| 2160x1440          | 1         | 0.5%    |
| 1920x540           | 1         | 0.5%    |
| 1920x1280          | 1         | 0.5%    |
| 1680x1050 (WSXGA+) | 1         | 0.5%    |
| 1360x768           | 1         | 0.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 47        | 22.6%   |
| 13      | 23        | 11.06%  |
| Unknown | 19        | 9.13%   |
| 23      | 18        | 8.65%   |
| 14      | 18        | 8.65%   |
| 27      | 14        | 6.73%   |
| 24      | 11        | 5.29%   |
| 17      | 10        | 4.81%   |
| 31      | 9         | 4.33%   |
| 21      | 8         | 3.85%   |
| 19      | 5         | 2.4%    |
| 34      | 4         | 1.92%   |
| 40      | 2         | 0.96%   |
| 32      | 2         | 0.96%   |
| 28      | 2         | 0.96%   |
| 18      | 2         | 0.96%   |
| 12      | 2         | 0.96%   |
| 84      | 1         | 0.48%   |
| 74      | 1         | 0.48%   |
| 72      | 1         | 0.48%   |
| 55      | 1         | 0.48%   |
| 54      | 1         | 0.48%   |
| 33      | 1         | 0.48%   |
| 29      | 1         | 0.48%   |
| 26      | 1         | 0.48%   |
| 22      | 1         | 0.48%   |
| 20      | 1         | 0.48%   |
| 16      | 1         | 0.48%   |
| 10      | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 83        | 40.69%  |
| 501-600     | 39        | 19.12%  |
| Unknown     | 19        | 9.31%   |
| 401-500     | 17        | 8.33%   |
| 601-700     | 13        | 6.37%   |
| 201-300     | 13        | 6.37%   |
| 701-800     | 7         | 3.43%   |
| 351-400     | 6         | 2.94%   |
| 1501-2000   | 3         | 1.47%   |
| 801-900     | 2         | 0.98%   |
| 1001-1500   | 2         | 0.98%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 136       | 73.51%  |
| 16/10   | 19        | 10.27%  |
| Unknown | 18        | 9.73%   |
| 21/9    | 6         | 3.24%   |
| 5/4     | 4         | 2.16%   |
| 3/2     | 2         | 1.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 46        | 22.44%  |
| 81-90          | 33        | 16.1%   |
| 201-250        | 31        | 15.12%  |
| Unknown        | 19        | 9.27%   |
| 351-500        | 17        | 8.29%   |
| 301-350        | 14        | 6.83%   |
| 71-80          | 8         | 3.9%    |
| 151-200        | 8         | 3.9%    |
| 141-150        | 6         | 2.93%   |
| 121-130        | 6         | 2.93%   |
| More than 1000 | 5         | 2.44%   |
| 251-300        | 5         | 2.44%   |
| 61-70          | 2         | 0.98%   |
| 111-120        | 2         | 0.98%   |
| 501-1000       | 2         | 0.98%   |
| 51-60          | 1         | 0.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 65        | 32.66%  |
| 51-100        | 53        | 26.63%  |
| 101-120       | 33        | 16.58%  |
| 161-240       | 20        | 10.05%  |
| Unknown       | 19        | 9.55%   |
| 1-50          | 5         | 2.51%   |
| More than 240 | 4         | 2.01%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 140       | 78.65%  |
| 2     | 33        | 18.54%  |
| 3     | 4         | 2.25%   |
| 4     | 1         | 0.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 101       | 38.7%   |
| Intel                             | 94        | 36.02%  |
| Qualcomm Atheros                  | 20        | 7.66%   |
| Broadcom                          | 13        | 4.98%   |
| MediaTek                          | 9         | 3.45%   |
| TP-Link                           | 6         | 2.3%    |
| Ralink Technology                 | 3         | 1.15%   |
| Samsung Electronics               | 2         | 0.77%   |
| Fibocom                           | 2         | 0.77%   |
| ASIX Electronics                  | 2         | 0.77%   |
| Sierra Wireless                   | 1         | 0.38%   |
| Qualcomm                          | 1         | 0.38%   |
| Microsoft                         | 1         | 0.38%   |
| Marvell Technology Group          | 1         | 0.38%   |
| Google                            | 1         | 0.38%   |
| Ericsson Business Mobile Networks | 1         | 0.38%   |
| D-Link                            | 1         | 0.38%   |
| Broadcom Limited                  | 1         | 0.38%   |
| Allwinner Technology              | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 65        | 20.77%  |
| Intel Wi-Fi 6 AX200                                               | 14        | 4.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 2.88%   |
| Intel Wireless 8265 / 8275                                        | 8         | 2.56%   |
| Intel I211 Gigabit Network Connection                             | 8         | 2.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 6         | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 1.6%    |
| Intel Wi-Fi 6 AX201                                               | 5         | 1.6%    |
| Intel Ethernet Connection I217-V                                  | 5         | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.28%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 1.28%   |
| Intel Ethernet Controller I225-V                                  | 4         | 1.28%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.28%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 3         | 0.96%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.96%   |
| Realtek Realtek Network controller                                | 3         | 0.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 0.96%   |
| MediaTek WLAN controller                                          | 3         | 0.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.96%   |
| Intel Wireless 8260                                               | 3         | 0.96%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.96%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 0.96%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3         | 0.96%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 2         | 0.64%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.64%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.64%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2         | 0.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2         | 0.64%   |
| Ralink RT3072 Wireless Adapter                                    | 2         | 0.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 73        | 47.4%   |
| Realtek Semiconductor | 34        | 22.08%  |
| Qualcomm Atheros      | 14        | 9.09%   |
| MediaTek              | 9         | 5.84%   |
| Broadcom              | 9         | 5.84%   |
| TP-Link               | 6         | 3.9%    |
| Ralink Technology     | 3         | 1.95%   |
| Fibocom               | 2         | 1.3%    |
| Sierra Wireless       | 1         | 0.65%   |
| Qualcomm              | 1         | 0.65%   |
| Microsoft             | 1         | 0.65%   |
| D-Link                | 1         | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 14        | 9.03%   |
| Intel Wireless 8265 / 8275                                    | 8         | 5.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 6         | 3.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 5         | 3.23%   |
| Intel Wi-Fi 6 AX201                                           | 5         | 3.23%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 5         | 3.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 4         | 2.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 4         | 2.58%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                           | 3         | 1.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 3         | 1.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 3         | 1.94%   |
| Realtek Realtek Network controller                            | 3         | 1.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 3         | 1.94%   |
| MediaTek WLAN controller                                      | 3         | 1.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3         | 1.94%   |
| Intel Wireless 8260                                           | 3         | 1.94%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 3         | 1.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 3         | 1.94%   |
| Intel Centrino Advanced-N 6235                                | 3         | 1.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 3         | 1.94%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 3         | 1.94%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 2         | 1.29%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 2         | 1.29%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 2         | 1.29%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 2         | 1.29%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 2         | 1.29%   |
| Ralink RT3072 Wireless Adapter                                | 2         | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 2         | 1.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 2         | 1.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 2         | 1.29%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 2         | 1.29%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 2         | 1.29%   |
| Intel Wireless 7265                                           | 2         | 1.29%   |
| Intel Wireless 7260                                           | 2         | 1.29%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 2         | 1.29%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 2         | 1.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 1.29%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 1.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 1.29%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 2         | 1.29%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 85        | 55.92%  |
| Intel                    | 44        | 28.95%  |
| Qualcomm Atheros         | 8         | 5.26%   |
| Broadcom                 | 8         | 5.26%   |
| Samsung Electronics      | 2         | 1.32%   |
| ASIX Electronics         | 2         | 1.32%   |
| Marvell Technology Group | 1         | 0.66%   |
| Google                   | 1         | 0.66%   |
| Broadcom Limited         | 1         | 0.66%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 65        | 41.67%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 5.77%   |
| Intel I211 Gigabit Network Connection                             | 8         | 5.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 3.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 3.21%   |
| Intel Ethernet Connection I217-V                                  | 5         | 3.21%   |
| Intel Ethernet Controller I225-V                                  | 4         | 2.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.92%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.28%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.28%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.28%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.28%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.28%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.28%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.28%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.28%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 1.28%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2         | 1.28%   |
| Intel 82566DC Gigabit Network Connection                          | 2         | 1.28%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.28%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.28%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.64%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.64%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.64%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.64%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.64%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.64%   |
| Intel Ethernet Controller X550                                    | 1         | 0.64%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.64%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.64%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.64%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.64%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.64%   |
| Google Pixel 6                                                    | 1         | 0.64%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 0.64%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 0.64%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 146       | 50%     |
| Ethernet | 144       | 49.32%  |
| Modem    | 1         | 0.34%   |
| Unknown  | 1         | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 110       | 59.78%  |
| Ethernet | 74        | 40.22%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 89        | 50%     |
| 1     | 85        | 47.75%  |
| 5     | 2         | 1.12%   |
| 3     | 2         | 1.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 122       | 68.54%  |
| Yes  | 56        | 31.46%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 64        | 47.41%  |
| Realtek Semiconductor           | 24        | 17.78%  |
| Cambridge Silicon Radio         | 10        | 7.41%   |
| Apple                           | 7         | 5.19%   |
| Qualcomm Atheros Communications | 6         | 4.44%   |
| IMC Networks                    | 5         | 3.7%    |
| Lite-On Technology              | 3         | 2.22%   |
| Broadcom                        | 3         | 2.22%   |
| ASUSTek Computer                | 3         | 2.22%   |
| TP-Link                         | 2         | 1.48%   |
| MediaTek                        | 2         | 1.48%   |
| Foxconn / Hon Hai               | 2         | 1.48%   |
| Toshiba                         | 1         | 0.74%   |
| Realtek                         | 1         | 0.74%   |
| Hewlett-Packard                 | 1         | 0.74%   |
| Edimax Technology               | 1         | 0.74%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 17        | 12.59%  |
| Intel Bluetooth wireless interface                  | 17        | 12.59%  |
| Intel Bluetooth Device                              | 14        | 10.37%  |
| Intel AX200 Bluetooth                               | 12        | 8.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10        | 7.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 7.41%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 3.7%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 2.96%   |
| Apple Bluetooth USB Host Controller                 | 4         | 2.96%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 2.22%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 2.22%   |
| Intel AX210 Bluetooth                               | 3         | 2.22%   |
| IMC Networks Wireless_Device                        | 3         | 2.22%   |
| TP-Link TPuLink UB500 Adapter                       | 2         | 1.48%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.48%   |
| MediaTek Wireless_Device                            | 2         | 1.48%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 1.48%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.48%   |
| ASUS ASUS USB-BT500                                 | 2         | 1.48%   |
| Apple Bluetooth Host Controller                     | 2         | 1.48%   |
| Toshiba BCM43142A0                                  | 1         | 0.74%   |
| Realtek Bluetooth Radio                             | 1         | 0.74%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.74%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.74%   |
| Lite-On Wireless_Device                             | 1         | 0.74%   |
| Lite-On Bluetooth Device                            | 1         | 0.74%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.74%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.74%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.74%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.74%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.74%   |
| Edimax Bluetooth Adapter                            | 1         | 0.74%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.74%   |
| ASUS Bluetooth Radio                                | 1         | 0.74%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.74%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 107       | 40.53%  |
| AMD                         | 78        | 29.55%  |
| Nvidia                      | 49        | 18.56%  |
| C-Media Electronics         | 5         | 1.89%   |
| Logitech                    | 3         | 1.14%   |
| ROCCAT                      | 2         | 0.76%   |
| Hewlett-Packard             | 2         | 0.76%   |
| Blue Microphones            | 2         | 0.76%   |
| BEHRINGER International     | 2         | 0.76%   |
| Other World Computing       | 1         | 0.38%   |
| Microsoft                   | 1         | 0.38%   |
| Lenovo                      | 1         | 0.38%   |
| Kingston Technology         | 1         | 0.38%   |
| JMTek                       | 1         | 0.38%   |
| GN Netcom                   | 1         | 0.38%   |
| Generalplus Technology      | 1         | 0.38%   |
| Focusrite-Novation          | 1         | 0.38%   |
| FiiO Electronics Technology | 1         | 0.38%   |
| eMeet                       | 1         | 0.38%   |
| Dell                        | 1         | 0.38%   |
| Creative Technology         | 1         | 0.38%   |
| Corsair                     | 1         | 0.38%   |
| Astro Gaming                | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 37        | 10.91%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 25        | 7.37%   |
| AMD Starship/Matisse HD Audio Controller                                   | 15        | 4.42%   |
| Intel Sunrise Point-LP HD Audio                                            | 14        | 4.13%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 3.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10        | 2.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 2.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 2.65%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 2.36%   |
| AMD FCH Azalia Controller                                                  | 8         | 2.36%   |
| Nvidia TU116 High Definition Audio Controller                              | 7         | 2.06%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 1.77%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 1.77%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6         | 1.77%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 1.47%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 1.47%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5         | 1.47%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 1.18%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 1.18%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.18%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.18%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 1.18%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 1.18%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 0.88%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 0.88%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.88%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 0.88%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 0.88%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3         | 0.88%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 0.88%   |
| AMD Trinity HDMI Audio Controller                                          | 3         | 0.88%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 0.88%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 0.88%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 3         | 0.88%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 3         | 0.88%   |
| ROCCAT Elo 7.1 Air                                                         | 2         | 0.59%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 20        | 19.42%  |
| Micron Technology            | 15        | 14.56%  |
| Kingston                     | 15        | 14.56%  |
| SK hynix                     | 9         | 8.74%   |
| Crucial                      | 9         | 8.74%   |
| Corsair                      | 6         | 5.83%   |
| Elpida                       | 5         | 4.85%   |
| GOODRAM                      | 4         | 3.88%   |
| G.Skill                      | 4         | 3.88%   |
| Unknown                      | 2         | 1.94%   |
| Team                         | 2         | 1.94%   |
| Ramaxel Technology           | 2         | 1.94%   |
| Nanya Technology             | 2         | 1.94%   |
| Unknown                      | 2         | 1.94%   |
| Unknown (0x8AF1)             | 1         | 0.97%   |
| TEXTORM                      | 1         | 0.97%   |
| Silicon Power                | 1         | 0.97%   |
| Sesame                       | 1         | 0.97%   |
| Patriot Memory (PDP Systems) | 1         | 0.97%   |
| A-DATA Technology            | 1         | 0.97%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                    | 3         | 2.7%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s                    | 3         | 2.7%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s                   | 2         | 1.8%    |
| Unknown                                                                  | 2         | 1.8%    |
| Unknown RAM Module 4GB SODIMM DDR3                                       | 1         | 0.9%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                                 | 1         | 0.9%    |
| Unknown (0x8AF1) RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.9%    |
| TEXTORM RAM TXU8G1M3200C16X 8GB DIMM DDR4 2666MT/s                       | 1         | 0.9%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s                       | 1         | 0.9%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s                       | 1         | 0.9%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                             | 1         | 0.9%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                             | 1         | 0.9%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                             | 1         | 0.9%    |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s                | 1         | 0.9%    |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s                  | 1         | 0.9%    |
| SK hynix RAM HMAA1GS6CMR8N-VK 8GB Row Of Chips DDR4 2667MT/s             | 1         | 0.9%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s                   | 1         | 0.9%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4                            | 1         | 0.9%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s                | 1         | 0.9%    |
| Silicon Power RAM Module 16GB SODIMM DDR4 2667MT/s                       | 1         | 0.9%    |
| Sesame RAM S939A2UGS-ITR 8GB DIMM DDR3 1600MT/s                          | 1         | 0.9%    |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s            | 1         | 0.9%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                              | 1         | 0.9%    |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                             | 1         | 0.9%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.9%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                    | 1         | 0.9%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                    | 1         | 0.9%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.9%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s                    | 1         | 0.9%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                    | 1         | 0.9%    |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s                      | 1         | 0.9%    |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s                      | 1         | 0.9%    |
| Samsung RAM K4UCE3Q4AA-MGCL 16GB Row Of Chips LPDDR4 4267MT/s            | 1         | 0.9%    |
| Samsung RAM K4UBE3D4AA-MGCR 8GB SODIMM LPDDR4 4266MT/s                   | 1         | 0.9%    |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.9%    |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s                  | 1         | 0.9%    |
| Ramaxel RAM RMR5030EF68F9W1600 4GB DIMM DDR3 1600MT/s                    | 1         | 0.9%    |
| Patriot Memory (PDP Systems) RAM 3600 C18 Series 16GB DIMM DDR4 3600MT/s | 1         | 0.9%    |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.9%    |
| Nanya RAM NT4GC64B8HG0NF-CG 4GB DIMM DDR3 1333MT/s                       | 1         | 0.9%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 54        | 58.7%   |
| DDR3   | 22        | 23.91%  |
| LPDDR4 | 7         | 7.61%   |
| DDR5   | 4         | 4.35%   |
| LPDDR3 | 3         | 3.26%   |
| LPDDR5 | 1         | 1.09%   |
| DDR2   | 1         | 1.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 53        | 56.38%  |
| DIMM         | 30        | 31.91%  |
| Row Of Chips | 10        | 10.64%  |
| Chip         | 1         | 1.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 45        | 45.92%  |
| 16384 | 27        | 27.55%  |
| 4096  | 13        | 13.27%  |
| 32768 | 8         | 8.16%   |
| 2048  | 5         | 5.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 22        | 22.68%  |
| 1600    | 17        | 17.53%  |
| 2667    | 13        | 13.4%   |
| 2133    | 7         | 7.22%   |
| 3600    | 6         | 6.19%   |
| 4267    | 4         | 4.12%   |
| 2400    | 4         | 4.12%   |
| 4800    | 2         | 2.06%   |
| 4266    | 2         | 2.06%   |
| 3733    | 2         | 2.06%   |
| 3400    | 2         | 2.06%   |
| 3000    | 2         | 2.06%   |
| 1867    | 2         | 2.06%   |
| 1333    | 2         | 2.06%   |
| 6400    | 1         | 1.03%   |
| 5808    | 1         | 1.03%   |
| 5200    | 1         | 1.03%   |
| 3266    | 1         | 1.03%   |
| 2933    | 1         | 1.03%   |
| 2666    | 1         | 1.03%   |
| 1067    | 1         | 1.03%   |
| 1066    | 1         | 1.03%   |
| 667     | 1         | 1.03%   |
| Unknown | 1         | 1.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)

![Printer Vendor](./All/images/line_chart/printer_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 50%     |
| Samsung Electronics | 1         | 16.67%  |
| Ricoh               | 1         | 16.67%  |
| Canon               | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)

![Printer Model](./All/images/line_chart/printer_model.svg)

| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-1640 Series Laser Printer | 1         | 16.67%  |
| Ricoh Printing Support               | 1         | 16.67%  |
| HP ENVY Inspire 7200 series          | 1         | 16.67%  |
| HP DeskJet 4530 series               | 1         | 16.67%  |
| HP DeskJet 2600 series               | 1         | 16.67%  |
| Canon PIXMA MX340                    | 1         | 16.67%  |

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
| Chicony Electronics                    | 19        | 15.57%  |
| Logitech                               | 14        | 11.48%  |
| IMC Networks                           | 13        | 10.66%  |
| Acer                                   | 13        | 10.66%  |
| Realtek Semiconductor                  | 9         | 7.38%   |
| Quanta                                 | 9         | 7.38%   |
| Microdia                               | 9         | 7.38%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 4.92%   |
| Luxvisions Innotech Limited            | 4         | 3.28%   |
| Apple                                  | 4         | 3.28%   |
| Samsung Electronics                    | 3         | 2.46%   |
| Microsoft                              | 3         | 2.46%   |
| Suyin                                  | 2         | 1.64%   |
| Generalplus Technology                 | 2         | 1.64%   |
| TANDBERG                               | 1         | 0.82%   |
| Syntek                                 | 1         | 0.82%   |
| SunplusIT                              | 1         | 0.82%   |
| Sunplus Innovation Technology          | 1         | 0.82%   |
| Sony Electronics                       | 1         | 0.82%   |
| Silicon Motion                         | 1         | 0.82%   |
| Lite-On Technology                     | 1         | 0.82%   |
| icSpring                               | 1         | 0.82%   |
| Foxconn / Hon Hai                      | 1         | 0.82%   |
| DigiTech                               | 1         | 0.82%   |
| AVerMedia Technologies                 | 1         | 0.82%   |
| Alcor Micro                            | 1         | 0.82%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                 | 7         | 5.74%   |
| Chicony Integrated Camera                                      | 6         | 4.92%   |
| Realtek Integrated_Webcam_HD                                   | 5         | 4.1%    |
| Acer Integrated Camera                                         | 4         | 3.28%   |
| Samsung Galaxy A5 (MTP)                                        | 3         | 2.46%   |
| Microdia Integrated_Webcam_HD                                  | 3         | 2.46%   |
| Logitech Webcam C270                                           | 3         | 2.46%   |
| Logitech HD Pro Webcam C920                                    | 3         | 2.46%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 3         | 2.46%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 3         | 2.46%   |
| Quanta HD User Facing                                          | 2         | 1.64%   |
| Microsoft LifeCam HD-3000                                      | 2         | 1.64%   |
| Microdia Webcam Vitade AF                                      | 2         | 1.64%   |
| Microdia USB 2.0 Camera                                        | 2         | 1.64%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 1.64%   |
| Logitech C920 PRO HD Webcam                                    | 2         | 1.64%   |
| Chicony HP Truevision HD camera                                | 2         | 1.64%   |
| Chicony HP HD Camera                                           | 2         | 1.64%   |
| Chicony HD WebCam                                              | 2         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 1.64%   |
| Acer Lenovo EasyCamera                                         | 2         | 1.64%   |
| Acer BisonCam,NB Pro                                           | 2         | 1.64%   |
| TANDBERG PrecisionHD Camera                                    | 1         | 0.82%   |
| Syntek Integrated Camera                                       | 1         | 0.82%   |
| Suyin HD WebCam                                                | 1         | 0.82%   |
| Suyin HD Video WebCam                                          | 1         | 0.82%   |
| SunplusIT 720p HD Camera                                       | 1         | 0.82%   |
| Sunplus Integrated_Webcam_FHD                                  | 1         | 0.82%   |
| Sony OV5648                                                    | 1         | 0.82%   |
| Silicon Motion WebCam SC-13HDL11939N                           | 1         | 0.82%   |
| Realtek USB Camera                                             | 1         | 0.82%   |
| Realtek LG Camera                                              | 1         | 0.82%   |
| Realtek HD WebCam                                              | 1         | 0.82%   |
| Realtek 720p HD Camera                                         | 1         | 0.82%   |
| Quanta VGA WebCam                                              | 1         | 0.82%   |
| Quanta USB2.0 HD UVC WebCam                                    | 1         | 0.82%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 0.82%   |
| Quanta HP High Definition 1MP Webcam                           | 1         | 0.82%   |
| Quanta HP HD Camera                                            | 1         | 0.82%   |
| Quanta hm1091_techfront                                        | 1         | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 10        | 35.71%  |
| Validity Sensors           | 8         | 28.57%  |
| Shenzhen Goodix Technology | 5         | 17.86%  |
| LighTuning Technology      | 2         | 7.14%   |
| Samsung Electronics        | 1         | 3.57%   |
| Elan Microelectronics      | 1         | 3.57%   |
| AuthenTec                  | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 14.29%  |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 10.71%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 7.14%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 7.14%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 7.14%   |
| Unknown                                                                    | 2         | 7.14%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 3.57%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 3.57%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 3.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 3.57%   |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 3.57%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 3.57%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 3.57%   |
| LighTuning Fingerprint Sensor                                              | 1         | 3.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 3.57%   |
| Elan ELAN:ARM-M4                                                           | 1         | 3.57%   |
| AuthenTec AES2810                                                          | 1         | 3.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./All/images/line_chart/chipcard_vendor.svg)

| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 5         | 50%     |
| Broadcom    | 2         | 20%     |
| Upek        | 1         | 10%     |
| O2 Micro    | 1         | 10%     |
| Clay Logic  | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 5         | 50%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 10%     |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 10%     |
| Clay Logic Nitrokey Pro                                    | 1         | 10%     |
| Broadcom 5880                                              | 1         | 10%     |
| Broadcom 58200                                             | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 118       | 66.29%  |
| 1     | 47        | 26.4%   |
| 2     | 12        | 6.74%   |
| 3     | 1         | 0.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 28        | 37.33%  |
| Net/wireless             | 13        | 17.33%  |
| Multimedia controller    | 12        | 16%     |
| Chipcard                 | 8         | 10.67%  |
| Graphics card            | 7         | 9.33%   |
| Camera                   | 3         | 4%      |
| Storage/raid             | 1         | 1.33%   |
| Network                  | 1         | 1.33%   |
| Net/ethernet             | 1         | 1.33%   |
| Communication controller | 1         | 1.33%   |

