Arch Hardware Trends
--------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Arch users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Arch/Desktop/README.md) and [notebooks](/Dist/Arch/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

Period: Dec, 2021.

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

| Name         | Computers | Percent |
|--------------|-----------|---------|
| Arch         | 72        | 50.7%   |
| Arch Rolling | 70        | 49.3%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name | Computers | Percent |
|------|-----------|---------|
| Arch | 143       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.7-arch1-1         | 29        | 20.28%  |
| 5.15.10-arch1-1        | 19        | 13.29%  |
| 5.15.6-arch2-1         | 14        | 9.79%   |
| 5.15.11-arch2-1        | 11        | 7.69%   |
| 5.15.8-arch1-1         | 9         | 6.29%   |
| 5.15.10-zen1-1-zen     | 6         | 4.2%    |
| 5.15.5-arch1-1         | 5         | 3.5%    |
| 5.15.11-zen1-1-zen     | 5         | 3.5%    |
| 5.10.88-2-lts          | 5         | 3.5%    |
| 5.15.7-zen1-1-zen      | 4         | 2.8%    |
| 5.15.6-zen2-1-zen      | 4         | 2.8%    |
| 5.10.84-1-lts          | 4         | 2.8%    |
| 5.15.8-zen1-1-zen      | 3         | 2.1%    |
| 5.15.7-4-clear         | 3         | 2.1%    |
| 5.15.5-zen1-1-zen      | 2         | 1.4%    |
| 5.15.2-arch1-1         | 2         | 1.4%    |
| 5.10.87-1-lts          | 2         | 1.4%    |
| 5.10.81-1-lts          | 2         | 1.4%    |
| 5.15.8-227-tkg-pds     | 1         | 0.7%    |
| 5.15.6-lqx2-1-lqx      | 1         | 0.7%    |
| 5.15.6-arch2-1-surface | 1         | 0.7%    |
| 5.15.4-zen1-1-zen      | 1         | 0.7%    |
| 5.15.11-xanmod1-1      | 1         | 0.7%    |
| 5.14.14-arch1-1        | 1         | 0.7%    |
| 5.13.19-2-MANJARO      | 1         | 0.7%    |
| 5.10.83-1-lts          | 1         | 0.7%    |
| 5.10.82-1-lts          | 1         | 0.7%    |
| 5.10.79-1-lts          | 1         | 0.7%    |
| 5.10.75-1-lts          | 1         | 0.7%    |
| 5.10.69-1-lts          | 1         | 0.7%    |
| 4.19.206-1-surface-lts | 1         | 0.7%    |
| Unknown                | 1         | 0.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.7   | 36        | 25.17%  |
| 5.15.10  | 25        | 17.48%  |
| 5.15.6   | 20        | 13.99%  |
| 5.15.11  | 17        | 11.89%  |
| 5.15.8   | 13        | 9.09%   |
| 5.15.5   | 7         | 4.9%    |
| 5.10.88  | 5         | 3.5%    |
| 5.10.84  | 4         | 2.8%    |
| 5.15.2   | 2         | 1.4%    |
| 5.10.87  | 2         | 1.4%    |
| 5.10.81  | 2         | 1.4%    |
| 5.15.4   | 1         | 0.7%    |
| 5.14.14  | 1         | 0.7%    |
| 5.13.19  | 1         | 0.7%    |
| 5.10.83  | 1         | 0.7%    |
| 5.10.82  | 1         | 0.7%    |
| 5.10.79  | 1         | 0.7%    |
| 5.10.75  | 1         | 0.7%    |
| 5.10.69  | 1         | 0.7%    |
| 4.19.206 | 1         | 0.7%    |
| Unknown  | 1         | 0.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 121       | 84.62%  |
| 5.10    | 18        | 12.59%  |
| 5.14    | 1         | 0.7%    |
| 5.13    | 1         | 0.7%    |
| 4.19    | 1         | 0.7%    |
| Unknown | 1         | 0.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 143       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| KDE5           | 55        | 38.46%  |
| GNOME          | 43        | 30.07%  |
| Unknown        | 14        | 9.79%   |
| XFCE           | 10        | 6.99%   |
| awesome        | 4         | 2.8%    |
| MATE           | 3         | 2.1%    |
| Budgie         | 3         | 2.1%    |
| X-Cinnamon     | 2         | 1.4%    |
| Cinnamon       | 2         | 1.4%    |
| xmonad         | 1         | 0.7%    |
| xinitrc        | 1         | 0.7%    |
| Unity          | 1         | 0.7%    |
| KDE            | 1         | 0.7%    |
| i3-with-shmlog | 1         | 0.7%    |
| i3             | 1         | 0.7%    |
| bspwm          | 1         | 0.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 89        | 62.24%  |
| Wayland | 29        | 20.28%  |
| Tty     | 17        | 11.89%  |
| Unknown | 8         | 5.59%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 52        | 36.36%  |
| Unknown | 35        | 24.48%  |
| LightDM | 27        | 18.88%  |
| GDM     | 24        | 16.78%  |
| Ly      | 4         | 2.8%    |
| LXDM    | 1         | 0.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 79        | 55.24%  |
| C       | 7         | 4.9%    |
| en_IN   | 6         | 4.2%    |
| en_GB   | 6         | 4.2%    |
| ru_RU   | 5         | 3.5%    |
| it_IT   | 5         | 3.5%    |
| fr_FR   | 5         | 3.5%    |
| de_DE   | 5         | 3.5%    |
| Unknown | 5         | 3.5%    |
| pl_PL   | 4         | 2.8%    |
| pt_BR   | 3         | 2.1%    |
| unm_US  | 1         | 0.7%    |
| tr_TR   | 1         | 0.7%    |
| sv_SE   | 1         | 0.7%    |
| ru_UA   | 1         | 0.7%    |
| ko_KR   | 1         | 0.7%    |
| fi_FI   | 1         | 0.7%    |
| es_ES   | 1         | 0.7%    |
| es_AR   | 1         | 0.7%    |
| en_SG   | 1         | 0.7%    |
| en_DK   | 1         | 0.7%    |
| en_DE   | 1         | 0.7%    |
| en_CA   | 1         | 0.7%    |
| de_AT   | 1         | 0.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 100       | 69.93%  |
| BIOS | 43        | 30.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 94        | 65.73%  |
| Btrfs   | 40        | 27.97%  |
| Xfs     | 3         | 2.1%    |
| F2fs    | 3         | 2.1%    |
| XXXXX   | 1         | 0.7%    |
| Overlay | 1         | 0.7%    |
| Ext3    | 1         | 0.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 110       | 76.92%  |
| Unknown | 25        | 17.48%  |
| MBR     | 8         | 5.59%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 118       | 82.52%  |
| Yes       | 25        | 17.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 84        | 58.74%  |
| Yes       | 59        | 41.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 33        | 23.08%  |
| Lenovo              | 19        | 13.29%  |
| Hewlett-Packard     | 18        | 12.59%  |
| Dell                | 18        | 12.59%  |
| MSI                 | 11        | 7.69%   |
| ASRock              | 9         | 6.29%   |
| Gigabyte Technology | 7         | 4.9%    |
| Apple               | 4         | 2.8%    |
| Acer                | 4         | 2.8%    |
| Timi                | 2         | 1.4%    |
| System76            | 2         | 1.4%    |
| Microsoft           | 2         | 1.4%    |
| UNOWHY              | 1         | 0.7%    |
| Toshiba             | 1         | 0.7%    |
| Schenker            | 1         | 0.7%    |
| Samsung Electronics | 1         | 0.7%    |
| Microtech           | 1         | 0.7%    |
| Medion              | 1         | 0.7%    |
| LG Electronics      | 1         | 0.7%    |
| Intel               | 1         | 0.7%    |
| Hyperbook           | 1         | 0.7%    |
| HUAWEI              | 1         | 0.7%    |
| Chuwi               | 1         | 0.7%    |
| Biostar             | 1         | 0.7%    |
| AMI                 | 1         | 0.7%    |
| Alienware           | 1         | 0.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| ASUS All Series                        | 3         | 2.1%    |
| MSI MS-7B86                            | 2         | 1.4%    |
| MSI MS-7B79                            | 2         | 1.4%    |
| Dell XPS 15 9500                       | 2         | 1.4%    |
| ASUS TUF GAMING X570-PLUS              | 2         | 1.4%    |
| ASUS ROG CROSSHAIR VIII DARK HERO      | 2         | 1.4%    |
| ASUS H170 PRO GAMING                   | 2         | 1.4%    |
| ASRock AB350 Pro4                      | 2         | 1.4%    |
| UNOWHY Y13G002S4EI                     | 1         | 0.7%    |
| Toshiba Satellite L650                 | 1         | 0.7%    |
| Timi TM1701                            | 1         | 0.7%    |
| Timi RedmiBook 14 II                   | 1         | 0.7%    |
| System76 Gazelle                       | 1         | 0.7%    |
| System76 Galago Pro                    | 1         | 0.7%    |
| Schenker XMG CORE 15(M20, RTX 2060)    | 1         | 0.7%    |
| Samsung RV415/RV515                    | 1         | 0.7%    |
| MSI MS-7D22                            | 1         | 0.7%    |
| MSI MS-7D07                            | 1         | 0.7%    |
| MSI MS-7C91                            | 1         | 0.7%    |
| MSI MS-7B77                            | 1         | 0.7%    |
| MSI MS-7B49                            | 1         | 0.7%    |
| MSI MS-7721                            | 1         | 0.7%    |
| MSI GS66 Stealth 10UH                  | 1         | 0.7%    |
| Microtech ebookPro                     | 1         | 0.7%    |
| Microsoft Surface Pro 4                | 1         | 0.7%    |
| Microsoft Surface Laptop Go            | 1         | 0.7%    |
| Medion ERAZER X7857 MD60893            | 1         | 0.7%    |
| LG 16ZD90P-GX7LK                       | 1         | 0.7%    |
| Lenovo V15 G2 ALC 82KD                 | 1         | 0.7%    |
| Lenovo V14-ADA 82C6                    | 1         | 0.7%    |
| Lenovo ThinkPad X13 Gen 1 20UGS11Q00   | 1         | 0.7%    |
| Lenovo ThinkPad T470s 20HF004UMD       | 1         | 0.7%    |
| Lenovo ThinkPad T460s 20FAS05Q00       | 1         | 0.7%    |
| Lenovo ThinkPad T400 2768GB4           | 1         | 0.7%    |
| Lenovo ThinkPad P51 20HJS16Q0K         | 1         | 0.7%    |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW  | 1         | 0.7%    |
| Lenovo ThinkPad E14 20RA001LMC         | 1         | 0.7%    |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 1         | 0.7%    |
| Lenovo Legion Y7000 81FW               | 1         | 0.7%    |
| Lenovo Legion Y7000 2019 1050 81V4     | 1         | 0.7%    |
| Lenovo IdeaPad Y510P 20217             | 1         | 0.7%    |
| Lenovo IdeaPad S540-15IWL GTX 81SW     | 1         | 0.7%    |
| Lenovo IdeaPad S145-15IWL 81S9         | 1         | 0.7%    |
| Lenovo IdeaPad L340-15API 81LW         | 1         | 0.7%    |
| Lenovo IdeaPad 5 14ARE05 81YM          | 1         | 0.7%    |
| Lenovo IdeaPad 300-15ISK 80Q7          | 1         | 0.7%    |
| Lenovo G580 20150                      | 1         | 0.7%    |
| Intel DH67BL AAG10189-213              | 1         | 0.7%    |
| Hyperbook Z15 Zen                      | 1         | 0.7%    |
| HUAWEI KLVD-WXX9                       | 1         | 0.7%    |
| HP Victus by Laptop 16-e0xxx           | 1         | 0.7%    |
| HP ProLiant BL460c Gen8                | 1         | 0.7%    |
| HP ProBook 4740s                       | 1         | 0.7%    |
| HP ProBook 450 G4                      | 1         | 0.7%    |
| HP ProBook 440 G8 Notebook PC          | 1         | 0.7%    |
| HP Pavilion x360 Convertible 14-cd0xxx | 1         | 0.7%    |
| HP Pavilion Gaming Laptop 15-ec0xxx    | 1         | 0.7%    |
| HP Pavilion Gaming Desktop TG01-2xxx   | 1         | 0.7%    |
| HP Pavilion Gaming Desktop TG01-0xxx   | 1         | 0.7%    |
| HP Pavilion g7                         | 1         | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 7         | 4.9%    |
| Lenovo IdeaPad     | 6         | 4.2%    |
| HP Pavilion        | 6         | 4.2%    |
| Dell Latitude      | 6         | 4.2%    |
| ASUS ROG           | 5         | 3.5%    |
| Dell XPS           | 4         | 2.8%    |
| ASUS TUF           | 4         | 2.8%    |
| HP ProBook         | 3         | 2.1%    |
| Dell Inspiron      | 3         | 2.1%    |
| ASUS ZenBook       | 3         | 2.1%    |
| ASUS All           | 3         | 2.1%    |
| MSI MS-7B86        | 2         | 1.4%    |
| MSI MS-7B79        | 2         | 1.4%    |
| Microsoft Surface  | 2         | 1.4%    |
| Lenovo Legion      | 2         | 1.4%    |
| HP Laptop          | 2         | 1.4%    |
| Gigabyte B450M     | 2         | 1.4%    |
| Dell Vostro        | 2         | 1.4%    |
| ASUS PRIME         | 2         | 1.4%    |
| ASUS H170          | 2         | 1.4%    |
| ASUS ASUS          | 2         | 1.4%    |
| ASRock AB350       | 2         | 1.4%    |
| Acer Aspire        | 2         | 1.4%    |
| UNOWHY Y13G002S4EI | 1         | 0.7%    |
| Toshiba Satellite  | 1         | 0.7%    |
| Timi TM1701        | 1         | 0.7%    |
| Timi RedmiBook     | 1         | 0.7%    |
| System76 Gazelle   | 1         | 0.7%    |
| System76 Galago    | 1         | 0.7%    |
| Schenker XMG       | 1         | 0.7%    |
| Samsung RV415      | 1         | 0.7%    |
| MSI MS-7D22        | 1         | 0.7%    |
| MSI MS-7D07        | 1         | 0.7%    |
| MSI MS-7C91        | 1         | 0.7%    |
| MSI MS-7B77        | 1         | 0.7%    |
| MSI MS-7B49        | 1         | 0.7%    |
| MSI MS-7721        | 1         | 0.7%    |
| MSI GS66           | 1         | 0.7%    |
| Microtech ebookPro | 1         | 0.7%    |
| Medion ERAZER      | 1         | 0.7%    |
| LG 16ZD90P-GX7LK   | 1         | 0.7%    |
| Lenovo V15         | 1         | 0.7%    |
| Lenovo V14-ADA     | 1         | 0.7%    |
| Lenovo ThinkBook   | 1         | 0.7%    |
| Lenovo G580        | 1         | 0.7%    |
| Intel DH67BL       | 1         | 0.7%    |
| Hyperbook Z15      | 1         | 0.7%    |
| HUAWEI KLVD-WXX9   | 1         | 0.7%    |
| HP Victus          | 1         | 0.7%    |
| HP ProLiant        | 1         | 0.7%    |
| HP Pav             | 1         | 0.7%    |
| HP OMEN            | 1         | 0.7%    |
| HP ENVY            | 1         | 0.7%    |
| HP EliteBook       | 1         | 0.7%    |
| HP 250             | 1         | 0.7%    |
| Gigabyte Z390      | 1         | 0.7%    |
| Gigabyte X58A-UD3R | 1         | 0.7%    |
| Gigabyte H110M-H   | 1         | 0.7%    |
| Gigabyte B450      | 1         | 0.7%    |
| Gigabyte 970A-DS3P | 1         | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 52        | 36.36%  |
| 2019 | 26        | 18.18%  |
| 2020 | 23        | 16.08%  |
| 2018 | 12        | 8.39%   |
| 2016 | 6         | 4.2%    |
| 2013 | 6         | 4.2%    |
| 2012 | 6         | 4.2%    |
| 2014 | 3         | 2.1%    |
| 2011 | 2         | 1.4%    |
| 2010 | 2         | 1.4%    |
| 2009 | 2         | 1.4%    |
| 2017 | 1         | 0.7%    |
| 2015 | 1         | 0.7%    |
| 2008 | 1         | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 79        | 55.24%  |
| Desktop     | 55        | 38.46%  |
| Convertible | 3         | 2.1%    |
| Tablet      | 2         | 1.4%    |
| Server      | 2         | 1.4%    |
| Mini pc     | 1         | 0.7%    |
| All in one  | 1         | 0.7%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 141       | 98.6%   |
| Enabled  | 2         | 1.4%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 142       | 99.3%   |
| Yes  | 1         | 0.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 48        | 33.57%  |
| 4.01-8.0    | 24        | 16.78%  |
| 32.01-64.0  | 24        | 16.78%  |
| 8.01-16.0   | 22        | 15.38%  |
| 3.01-4.0    | 12        | 8.39%   |
| 64.01-256.0 | 6         | 4.2%    |
| 24.01-32.0  | 3         | 2.1%    |
| 2.01-3.0    | 2         | 1.4%    |
| 1.01-2.0    | 2         | 1.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 36        | 25.17%  |
| 1.01-2.0   | 34        | 23.78%  |
| 4.01-8.0   | 29        | 20.28%  |
| 3.01-4.0   | 18        | 12.59%  |
| 8.01-16.0  | 12        | 8.39%   |
| 0.51-1.0   | 7         | 4.9%    |
| 16.01-24.0 | 3         | 2.1%    |
| 0.01-0.5   | 2         | 1.4%    |
| 32.01-64.0 | 1         | 0.7%    |
| 24.01-32.0 | 1         | 0.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 63        | 44.06%  |
| 2      | 42        | 29.37%  |
| 3      | 17        | 11.89%  |
| 4      | 8         | 5.59%   |
| 6      | 6         | 4.2%    |
| 5      | 3         | 2.1%    |
| 17     | 1         | 0.7%    |
| 11     | 1         | 0.7%    |
| 10     | 1         | 0.7%    |
| 7      | 1         | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 117       | 81.82%  |
| Yes       | 26        | 18.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 117       | 81.82%  |
| No        | 26        | 18.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 110       | 76.92%  |
| No        | 33        | 23.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 108       | 75.52%  |
| No        | 35        | 24.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 21        | 14.69%  |
| Germany     | 15        | 10.49%  |
| Russia      | 10        | 6.99%   |
| Poland      | 9         | 6.29%   |
| India       | 8         | 5.59%   |
| UK          | 7         | 4.9%    |
| France      | 7         | 4.9%    |
| Italy       | 6         | 4.2%    |
| Ukraine     | 4         | 2.8%    |
| Spain       | 4         | 2.8%    |
| Brazil      | 4         | 2.8%    |
| Turkey      | 3         | 2.1%    |
| Singapore   | 3         | 2.1%    |
| Norway      | 3         | 2.1%    |
| Canada      | 3         | 2.1%    |
| Sweden      | 2         | 1.4%    |
| Romania     | 2         | 1.4%    |
| Qatar       | 2         | 1.4%    |
| Portugal    | 2         | 1.4%    |
| Netherlands | 2         | 1.4%    |
| Iran        | 2         | 1.4%    |
| Hungary     | 2         | 1.4%    |
| Denmark     | 2         | 1.4%    |
| Bangladesh  | 2         | 1.4%    |
| Austria     | 2         | 1.4%    |
| Argentina   | 2         | 1.4%    |
| Venezuela   | 1         | 0.7%    |
| Switzerland | 1         | 0.7%    |
| South Korea | 1         | 0.7%    |
| Serbia      | 1         | 0.7%    |
| Moldova     | 1         | 0.7%    |
| Mexico      | 1         | 0.7%    |
| Latvia      | 1         | 0.7%    |
| Indonesia   | 1         | 0.7%    |
| Greece      | 1         | 0.7%    |
| Finland     | 1         | 0.7%    |
| Czechia     | 1         | 0.7%    |
| China       | 1         | 0.7%    |
| Belarus     | 1         | 0.7%    |
| Azerbaijan  | 1         | 0.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Singapore            | 3         | 2.1%    |
| Ponder               | 3         | 2.1%    |
| Moscow               | 3         | 2.1%    |
| Basingstoke          | 3         | 2.1%    |
| Warsaw               | 2         | 1.4%    |
| Vancouver            | 2         | 1.4%    |
| Uberl??ndia          | 2         | 1.4%    |
| Tongi                | 2         | 1.4%    |
| St Petersburg        | 2         | 1.4%    |
| Oslo                 | 2         | 1.4%    |
| Northampton          | 2         | 1.4%    |
| Montreal             | 2         | 1.4%    |
| Miami                | 2         | 1.4%    |
| Istanbul             | 2         | 1.4%    |
| Doha                 | 2         | 1.4%    |
| Creutzwald           | 2         | 1.4%    |
| Wittenbach           | 1         | 0.7%    |
| West Sacramento      | 1         | 0.7%    |
| Volgograd            | 1         | 0.7%    |
| Velbert              | 1         | 0.7%    |
| Vadodara             | 1         | 0.7%    |
| Turku                | 1         | 0.7%    |
| Tirschenreuth        | 1         | 0.7%    |
| Tighina              | 1         | 0.7%    |
| Tehran               | 1         | 0.7%    |
| Swarozyn             | 1         | 0.7%    |
| Stavanger            | 1         | 0.7%    |
| Soborg               | 1         | 0.7%    |
| Sk?�vde              | 1         | 0.7%    |
| Sighetu Marma??iei   | 1         | 0.7%    |
| Sergiyev Posad       | 1         | 0.7%    |
| Senta                | 1         | 0.7%    |
| Seattle              | 1         | 0.7%    |
| S??o Paulo           | 1         | 0.7%    |
| San Vito sullo Ionio | 1         | 0.7%    |
| Roydon               | 1         | 0.7%    |
| Riga                 | 1         | 0.7%    |
| Reus                 | 1         | 0.7%    |
| Remscheid            | 1         | 0.7%    |
| R??mnicu V??lcea     | 1         | 0.7%    |
| Radom                | 1         | 0.7%    |
| Quincy               | 1         | 0.7%    |
| Queens               | 1         | 0.7%    |
| Pune                 | 1         | 0.7%    |
| Prague               | 1         | 0.7%    |
| Poznan               | 1         | 0.7%    |
| Porto                | 1         | 0.7%    |
| Patna                | 1         | 0.7%    |
| Pasadena             | 1         | 0.7%    |
| Orneta               | 1         | 0.7%    |
| Oberhausen           | 1         | 0.7%    |
| Noida                | 1         | 0.7%    |
| Navi Mumbai          | 1         | 0.7%    |
| Navalcarnero         | 1         | 0.7%    |
| Naples               | 1         | 0.7%    |
| Nantes               | 1         | 0.7%    |
| Mykolayiv            | 1         | 0.7%    |
| Moscow Oblast        | 1         | 0.7%    |
| Modena               | 1         | 0.7%    |
| Missoula             | 1         | 0.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 59        | 90     | 24.38%  |
| WDC                 | 36        | 43     | 14.88%  |
| Seagate             | 29        | 57     | 11.98%  |
| Toshiba             | 14        | 17     | 5.79%   |
| Sandisk             | 13        | 15     | 5.37%   |
| Kingston            | 10        | 11     | 4.13%   |
| SK Hynix            | 9         | 9      | 3.72%   |
| Crucial             | 8         | 11     | 3.31%   |
| Micron Technology   | 6         | 6      | 2.48%   |
| HGST                | 6         | 8      | 2.48%   |
| Unknown             | 5         | 6      | 2.07%   |
| Intel               | 5         | 7      | 2.07%   |
| A-DATA Technology   | 5         | 6      | 2.07%   |
| Hitachi             | 4         | 5      | 1.65%   |
| Phison              | 3         | 3      | 1.24%   |
| GOODRAM             | 3         | 3      | 1.24%   |
| PNY                 | 2         | 2      | 0.83%   |
| Patriot             | 2         | 2      | 0.83%   |
| OCZ                 | 2         | 2      | 0.83%   |
| JMicron             | 2         | 2      | 0.83%   |
| Apple               | 2         | 2      | 0.83%   |
| XPG                 | 1         | 1      | 0.41%   |
| Verbatim            | 1         | 1      | 0.41%   |
| UMIS                | 1         | 1      | 0.41%   |
| Silicon Motion      | 1         | 1      | 0.41%   |
| SABRENT             | 1         | 1      | 0.41%   |
| RSH-319             | 1         | 1      | 0.41%   |
| PLEXTOR             | 1         | 1      | 0.41%   |
| Netac               | 1         | 1      | 0.41%   |
| Microtech           | 1         | 1      | 0.41%   |
| LITEON              | 1         | 1      | 0.41%   |
| Lenovo              | 1         | 1      | 0.41%   |
| KLEVV               | 1         | 1      | 0.41%   |
| KIOXIA              | 1         | 1      | 0.41%   |
| HS-SSD-E100N        | 1         | 1      | 0.41%   |
| Freecom             | 1         | 1      | 0.41%   |
| China               | 1         | 1      | 0.41%   |
| ASMT                | 1         | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Samsung SSD 860 EVO 1TB          | 7         | 2.46%   |
| Seagate ST4000DM004-2CV104 4TB   | 4         | 1.4%    |
| Samsung SSD 970 EVO Plus 500GB   | 4         | 1.4%    |
| Samsung SSD 850 EVO 500GB        | 4         | 1.4%    |
| Samsung NVMe SSD Drive 256GB     | 4         | 1.4%    |
| Samsung NVMe SSD Drive 1TB       | 4         | 1.4%    |
| Sandisk NVMe SSD Drive 1TB       | 3         | 1.05%   |
| Samsung SSD 970 EVO Plus 1TB     | 3         | 1.05%   |
| Samsung SSD 860 EVO 500GB        | 3         | 1.05%   |
| Samsung NVMe SSD Drive 500GB     | 3         | 1.05%   |
| WDC WD3200AAJS-00L7A0 320GB      | 2         | 0.7%    |
| WDC WD10EZEX-22MFCA0 1TB         | 2         | 0.7%    |
| WDC WD1002FAEX-00Z3A0 1TB        | 2         | 0.7%    |
| Unknown MMC Card  64GB           | 2         | 0.7%    |
| Toshiba DT01ACA100 1TB           | 2         | 0.7%    |
| SK Hynix PC711 NVMe 512GB        | 2         | 0.7%    |
| Seagate ST3500312CS 500GB        | 2         | 0.7%    |
| Seagate ST2000LM007-1R8174 2TB   | 2         | 0.7%    |
| Seagate ST2000DM008-2FR102 2TB   | 2         | 0.7%    |
| Seagate ST1000LM049-2GH172 1TB   | 2         | 0.7%    |
| Seagate ST1000DM003-1CH162 1TB   | 2         | 0.7%    |
| Sandisk NVMe SSD Drive 512GB     | 2         | 0.7%    |
| Sandisk NVMe SSD Drive 256GB     | 2         | 0.7%    |
| Samsung SSD 980 PRO 1TB          | 2         | 0.7%    |
| Samsung SSD 970 EVO 250GB        | 2         | 0.7%    |
| Samsung SSD 970 EVO 1TB          | 2         | 0.7%    |
| Samsung SSD 850 EVO 250GB        | 2         | 0.7%    |
| Samsung NVMe SSD Drive 512GB     | 2         | 0.7%    |
| Samsung NVMe SSD Drive 250GB     | 2         | 0.7%    |
| Samsung MZVLB256HAHQ-00000 256GB | 2         | 0.7%    |
| Intel NVMe SSD Drive 512GB       | 2         | 0.7%    |
| Crucial CT500MX500SSD1 500GB     | 2         | 0.7%    |
| A-DATA SX8200PNP 512GB           | 2         | 0.7%    |
| XPG NVMe SSD Drive 512GB         | 1         | 0.35%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1         | 0.35%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1         | 0.35%   |
| WDC WDS200T2B0B-00YS70 2TB SSD   | 1         | 0.35%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 1         | 0.35%   |
| WDC WDS100T2B0C 1TB              | 1         | 0.35%   |
| WDC WD60EZAZ-00SF3B0 6TB         | 1         | 0.35%   |
| WDC WD5000LPLX-00ZNTT0 500GB     | 1         | 0.35%   |
| WDC WD5000LPCX-24VHAT0 500GB     | 1         | 0.35%   |
| WDC WD5000LPCX-24C6HT0 500GB     | 1         | 0.35%   |
| WDC WD5000BPKT-80PK4T0 500GB     | 1         | 0.35%   |
| WDC WD5000AZRX-00L4HB0 500GB     | 1         | 0.35%   |
| WDC WD5000AAKX-001CA0 500GB      | 1         | 0.35%   |
| WDC WD5000AACS-07G8B0 500GB      | 1         | 0.35%   |
| WDC WD40EZRZ-00WN9B0 4TB         | 1         | 0.35%   |
| WDC WD40EFRX-68N32N0 4TB         | 1         | 0.35%   |
| WDC WD4004FZWX-00GBGB0 4TB       | 1         | 0.35%   |
| WDC WD4000FYYZ-01UL1B0 4TB       | 1         | 0.35%   |
| WDC WD3200BEKT-60V5T1 320GB      | 1         | 0.35%   |
| WDC WD30EZRX-00MMMB0 3TB         | 1         | 0.35%   |
| WDC WD30EZRX-00DC0B0 3TB         | 1         | 0.35%   |
| WDC WD20EFRX-68AX9N0 2TB         | 1         | 0.35%   |
| WDC WD160EDFZ-11AFWA0 16TB       | 1         | 0.35%   |
| WDC WD10SPZX-60Z10T1 1TB         | 1         | 0.35%   |
| WDC WD10SPZX-24Z10 1TB           | 1         | 0.35%   |
| WDC WD10SPZX-21Z10T0 1TB         | 1         | 0.35%   |
| WDC WD10SPZX-08Z10 1TB           | 1         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 30        | 36     | 35.29%  |
| Seagate             | 29        | 57     | 34.12%  |
| Toshiba             | 9         | 11     | 10.59%  |
| HGST                | 6         | 8      | 7.06%   |
| Samsung Electronics | 4         | 5      | 4.71%   |
| Hitachi             | 4         | 5      | 4.71%   |
| SABRENT             | 1         | 1      | 1.18%   |
| RSH-319             | 1         | 1      | 1.18%   |
| ASMT                | 1         | 1      | 1.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 30        | 39     | 38.46%  |
| Crucial             | 8         | 11     | 10.26%  |
| SanDisk             | 6         | 7      | 7.69%   |
| Kingston            | 6         | 7      | 7.69%   |
| WDC                 | 3         | 3      | 3.85%   |
| GOODRAM             | 3         | 3      | 3.85%   |
| A-DATA Technology   | 3         | 3      | 3.85%   |
| SK Hynix            | 2         | 2      | 2.56%   |
| PNY                 | 2         | 2      | 2.56%   |
| Patriot             | 2         | 2      | 2.56%   |
| OCZ                 | 2         | 2      | 2.56%   |
| Apple               | 2         | 2      | 2.56%   |
| Verbatim            | 1         | 1      | 1.28%   |
| Netac               | 1         | 1      | 1.28%   |
| Microtech           | 1         | 1      | 1.28%   |
| LITEON              | 1         | 1      | 1.28%   |
| JMicron             | 1         | 1      | 1.28%   |
| Intel               | 1         | 1      | 1.28%   |
| HS-SSD-E100N        | 1         | 1      | 1.28%   |
| Freecom             | 1         | 1      | 1.28%   |
| China               | 1         | 1      | 1.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 81        | 100    | 36.99%  |
| SSD     | 68        | 92     | 31.05%  |
| HDD     | 64        | 125    | 29.22%  |
| MMC     | 5         | 6      | 2.28%   |
| Unknown | 1         | 1      | 0.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 100       | 209    | 52.36%  |
| NVMe | 81        | 100    | 42.41%  |
| SAS  | 5         | 9      | 2.62%   |
| MMC  | 5         | 6      | 2.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 69        | 91     | 46.31%  |
| 0.51-1.0   | 44        | 61     | 29.53%  |
| 1.01-2.0   | 15        | 23     | 10.07%  |
| 3.01-4.0   | 11        | 24     | 7.38%   |
| 2.01-3.0   | 4         | 6      | 2.68%   |
| 4.01-10.0  | 4         | 7      | 2.68%   |
| 10.01-20.0 | 2         | 5      | 1.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 32        | 22.38%  |
| 251-500        | 30        | 20.98%  |
| 501-1000       | 26        | 18.18%  |
| 1001-2000      | 19        | 13.29%  |
| More than 3000 | 18        | 12.59%  |
| 2001-3000      | 8         | 5.59%   |
| 51-100         | 6         | 4.2%    |
| 21-50          | 2         | 1.4%    |
| Unknown        | 2         | 1.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 23        | 16.08%  |
| 101-250        | 22        | 15.38%  |
| 21-50          | 19        | 13.29%  |
| 51-100         | 19        | 13.29%  |
| 501-1000       | 18        | 12.59%  |
| 251-500        | 15        | 10.49%  |
| More than 3000 | 10        | 6.99%   |
| 1001-2000      | 9         | 6.29%   |
| 2001-3000      | 6         | 4.2%    |
| Unknown        | 2         | 1.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000BPKT-80PK4T0 500GB          | 1         | 1      | 4.76%   |
| WDC WD5000AAKX-001CA0 500GB           | 1         | 1      | 4.76%   |
| WDC WD3200BEKT-60V5T1 320GB           | 1         | 1      | 4.76%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1         | 1      | 4.76%   |
| WDC WD10EZEX-60ZF5A0 1TB              | 1         | 1      | 4.76%   |
| WDC WD10EZEX-08M2NA0 1TB              | 1         | 1      | 4.76%   |
| WDC WD10EARS-00Y5B1 1TB               | 1         | 1      | 4.76%   |
| Seagate ST4000DM004-2CV104 4TB        | 1         | 1      | 4.76%   |
| Seagate ST3500312CS 500GB             | 1         | 1      | 4.76%   |
| Seagate ST31000528AS 1TB              | 1         | 1      | 4.76%   |
| Seagate ST1000LX015-1U7172-SSHD 1TB   | 1         | 1      | 4.76%   |
| Seagate ST1000DX001-1NS162 1TB        | 1         | 1      | 4.76%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 870 EVO 2TB   | 1         | 4      | 4.76%   |
| Samsung Electronics HD161HJ 160GB     | 1         | 1      | 4.76%   |
| PLEXTOR PX-1TM8SeG 1TB                | 1         | 1      | 4.76%   |
| Kingston SV300S37A60G 64GB SSD        | 1         | 1      | 4.76%   |
| Hitachi HUS724030ALE641 3TB           | 1         | 1      | 4.76%   |
| Hitachi HTS543232A7A384 320GB         | 1         | 1      | 4.76%   |
| Crucial CT240M500SSD1 240GB           | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 35%     |
| Seagate             | 4         | 5      | 20%     |
| Samsung Electronics | 3         | 6      | 15%     |
| Hitachi             | 2         | 2      | 10%     |
| SanDisk             | 1         | 1      | 5%      |
| PLEXTOR             | 1         | 1      | 5%      |
| Kingston            | 1         | 1      | 5%      |
| Crucial             | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 50%     |
| Seagate             | 4         | 5      | 28.57%  |
| Hitachi             | 2         | 2      | 14.29%  |
| Samsung Electronics | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 15     | 68.42%  |
| SSD  | 5         | 8      | 26.32%  |
| NVMe | 1         | 1      | 5.26%   |

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
| Works    | 84        | 199    | 53.16%  |
| Detected | 55        | 101    | 34.81%  |
| Malfunc  | 19        | 24     | 12.03%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 76        | 35.02%  |
| AMD                          | 42        | 19.35%  |
| Samsung Electronics          | 37        | 17.05%  |
| Sandisk                      | 11        | 5.07%   |
| SK Hynix                     | 7         | 3.23%   |
| Micron Technology            | 6         | 2.76%   |
| Toshiba America Info Systems | 5         | 2.3%    |
| ASMedia Technology           | 5         | 2.3%    |
| Marvell Technology Group     | 4         | 1.84%   |
| Kingston Technology Company  | 4         | 1.84%   |
| Phison Electronics           | 3         | 1.38%   |
| ADATA Technology             | 3         | 1.38%   |
| Silicon Motion               | 2         | 0.92%   |
| LSI Logic / Symbios Logic    | 2         | 0.92%   |
| KIOXIA                       | 2         | 0.92%   |
| VIA Technologies             | 1         | 0.46%   |
| Union Memory (Shenzhen)      | 1         | 0.46%   |
| Nvidia                       | 1         | 0.46%   |
| Lite-On Technology           | 1         | 0.46%   |
| Lenovo                       | 1         | 0.46%   |
| JMicron Technology           | 1         | 0.46%   |
| Hewlett-Packard              | 1         | 0.46%   |
| Broadcom / LSI               | 1         | 0.46%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 31        | 12.5%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 21        | 8.47%   |
| AMD 400 Series Chipset SATA Controller                                           | 14        | 5.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 9         | 3.63%   |
| SK Hynix Gold P31 SSD                                                            | 7         | 2.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 7         | 2.82%   |
| Samsung NVMe SSD Controller 980                                                  | 7         | 2.82%   |
| Intel Volume Management Device NVMe RAID Controller                              | 7         | 2.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7         | 2.82%   |
| Micron Non-Volatile memory controller                                            | 6         | 2.42%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 2.42%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 2.42%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 2.02%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 5         | 2.02%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 5         | 2.02%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 4         | 1.61%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 4         | 1.61%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 3         | 1.21%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.21%   |
| Kingston Company A2000 NVMe SSD                                                  | 3         | 1.21%   |
| Intel SSD 660P Series                                                            | 3         | 1.21%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.21%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 1.21%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3         | 1.21%   |
| AMD X370 Series Chipset SATA Controller                                          | 3         | 1.21%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                         | 3         | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 1.21%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 3         | 1.21%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2         | 0.81%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.81%   |
| Sandisk Non-Volatile memory controller                                           | 2         | 0.81%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo            | 2         | 0.81%   |
| KIOXIA Non-Volatile memory controller                                            | 2         | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 0.81%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 0.81%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 2         | 0.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 2         | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 0.81%   |
| AMD 300 Series Chipset SATA Controller                                           | 2         | 0.81%   |
| VIA VT6415 PATA IDE Host Controller                                              | 1         | 0.4%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.4%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.4%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.4%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 0.4%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.4%    |
| Samsung Electronics SATA controller                                              | 1         | 0.4%    |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.4%    |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.4%    |
| Phison E12 NVMe Controller                                                       | 1         | 0.4%    |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 0.4%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 1         | 0.4%    |
| Marvell Group 88SE912x IDE Controller                                            | 1         | 0.4%    |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                          | 1         | 0.4%    |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]          | 1         | 0.4%    |
| LSI Logic / Symbios Logic MegaRAID SAS 2208 [Thunderbolt]                        | 1         | 0.4%    |
| Lite-On Non-Volatile memory controller                                           | 1         | 0.4%    |
| Lenovo Non-Volatile memory controller                                            | 1         | 0.4%    |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 106       | 50.48%  |
| NVMe | 81        | 38.57%  |
| RAID | 15        | 7.14%   |
| IDE  | 7         | 3.33%   |
| SAS  | 1         | 0.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 91        | 63.64%  |
| AMD    | 52        | 36.36%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 4.2%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 6         | 4.2%    |
| AMD Ryzen 5 3600 6-Core Processor             | 5         | 3.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 2.8%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.1%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 2.1%    |
| Intel 11th Gen Core i5-11400 @ 2.60GHz        | 3         | 2.1%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 2.1%    |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 1.4%    |
| Intel Core i7-10870H CPU @ 2.20GHz            | 2         | 1.4%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.4%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.4%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.4%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.4%    |
| Intel Core i5-10300H CPU @ 2.50GHz            | 2         | 1.4%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.4%    |
| AMD Ryzen 9 5950X 16-Core Processor           | 2         | 1.4%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.4%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.4%    |
| AMD Ryzen 5 2600 Six-Core Processor           | 2         | 1.4%    |
| AMD Ryzen 5 1600 Six-Core Processor           | 2         | 1.4%    |
| AMD FX-4300 Quad-Core Processor               | 2         | 1.4%    |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 1         | 0.7%    |
| Intel Xeon CPU E5-2643 0 @ 3.30GHz            | 1         | 0.7%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.7%    |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz   | 1         | 0.7%    |
| Intel Core i9-10885H CPU @ 2.40GHz            | 1         | 0.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.7%    |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.7%    |
| Intel Core i7-6850K CPU @ 3.60GHz             | 1         | 0.7%    |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 0.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.7%    |
| Intel Core i7-5650U CPU @ 2.20GHz             | 1         | 0.7%    |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1         | 0.7%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 1         | 0.7%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.7%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.7%    |
| Intel Core i7-2600K CPU @ 3.40GHz             | 1         | 0.7%    |
| Intel Core i7-2600 CPU @ 3.40GHz              | 1         | 0.7%    |
| Intel Core i7 CPU 930 @ 2.80GHz               | 1         | 0.7%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 0.7%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.7%    |
| Intel Core i5-7500 CPU @ 3.40GHz              | 1         | 0.7%    |
| Intel Core i5-7440HQ CPU @ 2.80GHz            | 1         | 0.7%    |
| Intel Core i5-7400 CPU @ 3.00GHz              | 1         | 0.7%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.7%    |
| Intel Core i5-6600 CPU @ 3.30GHz              | 1         | 0.7%    |
| Intel Core i5-6440HQ CPU @ 2.60GHz            | 1         | 0.7%    |
| Intel Core i5-6400 CPU @ 2.70GHz              | 1         | 0.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.7%    |
| Intel Core i5-4690 CPU @ 3.50GHz              | 1         | 0.7%    |
| Intel Core i5-3340M CPU @ 2.70GHz             | 1         | 0.7%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 0.7%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 0.7%    |
| Intel Core i5-2500K CPU @ 3.30GHz             | 1         | 0.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 0.7%    |
| Intel Core i3-8350K CPU @ 4.00GHz             | 1         | 0.7%    |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 30        | 20.98%  |
| Intel Core i5           | 26        | 18.18%  |
| AMD Ryzen 5             | 21        | 14.69%  |
| Other                   | 16        | 11.19%  |
| AMD Ryzen 7             | 16        | 11.19%  |
| Intel Core i3           | 6         | 4.2%    |
| Intel Core 2 Duo        | 5         | 3.5%    |
| AMD Ryzen 9             | 4         | 2.8%    |
| Intel Xeon              | 2         | 1.4%    |
| Intel Celeron           | 2         | 1.4%    |
| AMD Ryzen 3             | 2         | 1.4%    |
| AMD FX                  | 2         | 1.4%    |
| AMD A8                  | 2         | 1.4%    |
| Intel Pentium Silver    | 1         | 0.7%    |
| Intel Pentium Dual-Core | 1         | 0.7%    |
| Intel Core i9           | 1         | 0.7%    |
| Intel Atom              | 1         | 0.7%    |
| AMD Ryzen 7 PRO         | 1         | 0.7%    |
| AMD Ryzen 5 PRO         | 1         | 0.7%    |
| AMD Phenom II X4        | 1         | 0.7%    |
| AMD E2                  | 1         | 0.7%    |
| AMD E                   | 1         | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 59        | 41.26%  |
| 2      | 29        | 20.28%  |
| 6      | 26        | 18.18%  |
| 8      | 24        | 16.78%  |
| 16     | 4         | 2.8%    |
| 12     | 1         | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 141       | 98.6%   |
| 2      | 2         | 1.4%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 116       | 81.12%  |
| 1      | 27        | 18.88%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 143       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 23.78%  |
| 0x806c1    | 7         | 4.9%    |
| 0x906ea    | 6         | 4.2%    |
| 0x08701021 | 6         | 4.2%    |
| 0x906e9    | 5         | 3.5%    |
| 0x806ec    | 5         | 3.5%    |
| 0x1067a    | 5         | 3.5%    |
| 0xa0652    | 4         | 2.8%    |
| 0x306a9    | 4         | 2.8%    |
| 0x08600106 | 4         | 2.8%    |
| 0x08001138 | 4         | 2.8%    |
| 0xa0671    | 3         | 2.1%    |
| 0x806ea    | 3         | 2.1%    |
| 0x806e9    | 3         | 2.1%    |
| 0x506e3    | 3         | 2.1%    |
| 0x406e3    | 3         | 2.1%    |
| 0x306c3    | 3         | 2.1%    |
| 0x206a7    | 3         | 2.1%    |
| 0x08108102 | 3         | 2.1%    |
| 0x0800820d | 3         | 2.1%    |
| 0x806eb    | 2         | 1.4%    |
| 0x806d1    | 2         | 1.4%    |
| 0x206d7    | 2         | 1.4%    |
| 0x0a201016 | 2         | 1.4%    |
| 0x0a201009 | 2         | 1.4%    |
| 0x08701013 | 2         | 1.4%    |
| 0x08108109 | 2         | 1.4%    |
| 0x03000027 | 2         | 1.4%    |
| 0x906eb    | 1         | 0.7%    |
| 0x706e5    | 1         | 0.7%    |
| 0x706a8    | 1         | 0.7%    |
| 0x306d4    | 1         | 0.7%    |
| 0x20655    | 1         | 0.7%    |
| 0x106a5    | 1         | 0.7%    |
| 0x10676    | 1         | 0.7%    |
| 0x0a50000c | 1         | 0.7%    |
| 0x0a50000b | 1         | 0.7%    |
| 0x08608102 | 1         | 0.7%    |
| 0x08600103 | 1         | 0.7%    |
| 0x08001137 | 1         | 0.7%    |
| 0x06001119 | 1         | 0.7%    |
| 0x0600081f | 1         | 0.7%    |
| 0x0600081c | 1         | 0.7%    |
| 0x05000119 | 1         | 0.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 29        | 20.28%  |
| Zen 2         | 20        | 13.99%  |
| Zen+          | 11        | 7.69%   |
| TigerLake     | 9         | 6.29%   |
| Skylake       | 8         | 5.59%   |
| Zen           | 7         | 4.9%    |
| SandyBridge   | 7         | 4.9%    |
| Zen 3         | 6         | 4.2%    |
| Penryn        | 6         | 4.2%    |
| IvyBridge     | 6         | 4.2%    |
| IceLake       | 5         | 3.5%    |
| CometLake     | 5         | 3.5%    |
| Unknown       | 5         | 3.5%    |
| Haswell       | 4         | 2.8%    |
| Piledriver    | 3         | 2.1%    |
| K10 Llano     | 2         | 1.4%    |
| Goldmont plus | 2         | 1.4%    |
| Broadwell     | 2         | 1.4%    |
| Westmere      | 1         | 0.7%    |
| Silvermont    | 1         | 0.7%    |
| Nehalem       | 1         | 0.7%    |
| K10           | 1         | 0.7%    |
| Goldmont      | 1         | 0.7%    |
| Bobcat        | 1         | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 72        | 40.22%  |
| Nvidia                     | 55        | 30.73%  |
| AMD                        | 50        | 27.93%  |
| Matrox Electronics Systems | 2         | 1.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 9         | 5%      |
| AMD Renoir                                                                | 8         | 4.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 7         | 3.89%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 3.33%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 5         | 2.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 5         | 2.78%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 5         | 2.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 2.22%   |
| Intel HD Graphics 630                                                     | 4         | 2.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 4         | 2.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 2.22%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 3         | 1.67%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                               | 3         | 1.67%   |
| Nvidia GP104 [GeForce GTX 1070]                                           | 3         | 1.67%   |
| Intel UHD Graphics 620                                                    | 3         | 1.67%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 3         | 1.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 3         | 1.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 1.67%   |
| Intel HD Graphics 620                                                     | 3         | 1.67%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                  | 3         | 1.67%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 3         | 1.67%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 2         | 1.11%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 2         | 1.11%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 1.11%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 2         | 1.11%   |
| Nvidia GK104 [GeForce GTX 760]                                            | 2         | 1.11%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 2         | 1.11%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                 | 2         | 1.11%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 1.11%   |
| Intel HD Graphics 530                                                     | 2         | 1.11%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                | 2         | 1.11%   |
| AMD Cezanne                                                               | 2         | 1.11%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                            | 2         | 1.11%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.56%   |
| Nvidia TU117GLM [T600 Mobile]                                             | 1         | 0.56%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.56%   |
| Nvidia TU116 [GeForce GTX 1660]                                           | 1         | 0.56%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.56%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                    | 1         | 0.56%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                    | 1         | 0.56%   |
| Nvidia MCP89 [GeForce 320M]                                               | 1         | 0.56%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 0.56%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 1         | 0.56%   |
| Nvidia GP107 [GeForce GTX 1050]                                           | 1         | 0.56%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                  | 1         | 0.56%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                  | 1         | 0.56%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 1         | 0.56%   |
| Nvidia GP102 [TITAN X]                                                    | 1         | 0.56%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                     | 1         | 0.56%   |
| Nvidia GM206 [GeForce GTX 960]                                            | 1         | 0.56%   |
| Nvidia GM204M [GeForce GTX 970M]                                          | 1         | 0.56%   |
| Nvidia GM204 [GeForce GTX 970]                                            | 1         | 0.56%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.56%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                         | 1         | 0.56%   |
| Nvidia GK107M [GeForce GT 755M]                                           | 1         | 0.56%   |
| Nvidia GK107 [GeForce GTX 650]                                            | 1         | 0.56%   |
| Nvidia GK106 [GeForce GTX 660]                                            | 1         | 0.56%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 0.56%   |
| Nvidia GF110 [GeForce GTX 590]                                            | 1         | 0.56%   |
| Nvidia GF108M [GeForce GT 540M]                                           | 1         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 44        | 30.77%  |
| 1 x AMD        | 38        | 26.57%  |
| 1 x Nvidia     | 24        | 16.78%  |
| Intel + Nvidia | 22        | 15.38%  |
| AMD + Nvidia   | 8         | 5.59%   |
| Intel + AMD    | 4         | 2.8%    |
| 1 x Matrox     | 2         | 1.4%    |
| 2 x Nvidia     | 1         | 0.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 98        | 68.53%  |
| Proprietary | 45        | 31.47%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 80        | 55.94%  |
| 7.01-8.0   | 15        | 10.49%  |
| 1.01-2.0   | 15        | 10.49%  |
| 0.01-0.5   | 12        | 8.39%   |
| 3.01-4.0   | 8         | 5.59%   |
| 5.01-6.0   | 4         | 2.8%    |
| 8.01-16.0  | 4         | 2.8%    |
| 2.01-3.0   | 3         | 2.1%    |
| 0.51-1.0   | 2         | 1.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 27        | 16.56%  |
| Samsung Electronics     | 18        | 11.04%  |
| Dell                    | 18        | 11.04%  |
| BOE                     | 18        | 11.04%  |
| Goldstar                | 10        | 6.13%   |
| LG Display              | 9         | 5.52%   |
| Hewlett-Packard         | 9         | 5.52%   |
| Chimei Innolux          | 9         | 5.52%   |
| Sharp                   | 7         | 4.29%   |
| Lenovo                  | 5         | 3.07%   |
| AOC                     | 4         | 2.45%   |
| Philips                 | 3         | 1.84%   |
| BenQ                    | 3         | 1.84%   |
| Ancor Communications    | 3         | 1.84%   |
| Acer                    | 3         | 1.84%   |
| PANDA                   | 2         | 1.23%   |
| Denver                  | 2         | 1.23%   |
| Chi Mei Optoelectronics | 2         | 1.23%   |
| Apple                   | 2         | 1.23%   |
| ViewSonic               | 1         | 0.61%   |
| Toshiba                 | 1         | 0.61%   |
| RSR                     | 1         | 0.61%   |
| LGD                     | 1         | 0.61%   |
| LG Electronics          | 1         | 0.61%   |
| Iiyama                  | 1         | 0.61%   |
| HVR                     | 1         | 0.61%   |
| Gigabyte Technology     | 1         | 0.61%   |
| ADI                     | 1         | 0.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 4         | 2.35%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 1.18%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 1.18%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                    | 2         | 1.18%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch        | 2         | 1.18%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch         | 2         | 1.18%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 1         | 0.59%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                      | 1         | 0.59%   |
| Sharp LQ156M1JW26 SHP1532 1920x1080 344x194mm 15.5-inch               | 1         | 0.59%   |
| Sharp LQ156M1JW23 SHP1514 1920x1080 344x194mm 15.5-inch               | 1         | 0.59%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch               | 1         | 0.59%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.59%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.59%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.59%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.59%   |
| Samsung Electronics T19B300 SAM0928 1366x768 410x230mm 18.5-inch      | 1         | 0.59%   |
| Samsung Electronics SyncMaster SAM05EC 1920x1080 597x336mm 27.0-inch  | 1         | 0.59%   |
| Samsung Electronics SyncMaster SAM05C4 1920x1080 510x287mm 23.0-inch  | 1         | 0.59%   |
| Samsung Electronics SyncMaster SAM056E 1920x1200 518x324mm 24.1-inch  | 1         | 0.59%   |
| Samsung Electronics SyncMaster SAM0255 1680x1050 474x296mm 22.0-inch  | 1         | 0.59%   |
| Samsung Electronics SyncMaster SAM0218 1280x1024 376x301mm 19.0-inch  | 1         | 0.59%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch   | 1         | 0.59%   |
| Samsung Electronics SMS22A350H SAM07D2 1920x1080 480x270mm 21.7-inch  | 1         | 0.59%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 1         | 0.59%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch     | 1         | 0.59%   |
| Samsung Electronics S22D300 SAM0B3B 1920x1080 477x268mm 21.5-inch     | 1         | 0.59%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1         | 0.59%   |
| Samsung Electronics LS32R75 SAM0F93 3840x2160 697x392mm 31.5-inch     | 1         | 0.59%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC4449 1366x768 309x174mm 14.0-inch  | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch | 1         | 0.59%   |
| Samsung Electronics LCD Monitor S23C650 1920x1080                     | 1         | 0.59%   |
| Samsung Electronics LC24RG50 SAM0F91 1920x1080 532x304mm 24.1-inch    | 1         | 0.59%   |
| RSR LCD Monitor RSR0100 3840x2160 1872x1053mm 84.6-inch               | 1         | 0.59%   |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch              | 1         | 0.59%   |
| Philips LCD Monitor PHL 243V5 1920x1080                               | 1         | 0.59%   |
| Philips LCD Monitor FTV 3286x1080                                     | 1         | 0.59%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.59%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.59%   |
| LGD LCD Monitor 1920x1080                                             | 1         | 0.59%   |
| LG Electronics LCD Monitor LG HDR 4K                                  | 1         | 0.59%   |
| LG Display LCD Monitor LGD0694 2560x1600 344x215mm 16.0-inch          | 1         | 0.59%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 1         | 0.59%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.59%   |
| LG Display LCD Monitor LGD0570 1920x1080 344x194mm 15.5-inch          | 1         | 0.59%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch          | 1         | 0.59%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.59%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 1         | 0.59%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x174mm 14.0-inch          | 1         | 0.59%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch           | 1         | 0.59%   |
| Lenovo LEN T27p-10 LEN61DA 3840x2160 597x336mm 27.0-inch              | 1         | 0.59%   |
| Lenovo LEN T2424pA LEN60C8 1920x1080 527x296mm 23.8-inch              | 1         | 0.59%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch              | 1         | 0.59%   |
| Lenovo LEN L201p LEN2404 1600x1200 400x300mm 19.7-inch                | 1         | 0.59%   |
| Lenovo LCD Monitor LEN4033 1440x900 304x190mm 14.1-inch               | 1         | 0.59%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                  | 1         | 0.59%   |
| Iiyama PL2730H IVM663B 1920x1080 598x336mm 27.0-inch                  | 1         | 0.59%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                        | 1         | 0.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 82        | 52.56%  |
| 1366x768 (WXGA)    | 19        | 12.18%  |
| 2560x1440 (QHD)    | 15        | 9.62%   |
| 3840x2160 (4K)     | 7         | 4.49%   |
| 1920x1200 (WUXGA)  | 5         | 3.21%   |
| 3440x1440          | 4         | 2.56%   |
| 1440x900 (WXGA+)   | 4         | 2.56%   |
| 1600x900 (HD+)     | 3         | 1.92%   |
| 1280x1024 (SXGA)   | 3         | 1.92%   |
| 2736x1824          | 2         | 1.28%   |
| 2160x1440          | 2         | 1.28%   |
| Unknown            | 2         | 1.28%   |
| 7680x2160          | 1         | 0.64%   |
| 3840x2400          | 1         | 0.64%   |
| 3286x1080          | 1         | 0.64%   |
| 2560x1600          | 1         | 0.64%   |
| 2560x1080          | 1         | 0.64%   |
| 2160x1200          | 1         | 0.64%   |
| 1680x1050 (WSXGA+) | 1         | 0.64%   |
| 1600x1200          | 1         | 0.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 42        | 25.77%  |
| 27      | 21        | 12.88%  |
| 24      | 15        | 9.2%    |
| 14      | 15        | 9.2%    |
| 23      | 13        | 7.98%   |
| 13      | 12        | 7.36%   |
| 17      | 8         | 4.91%   |
| 21      | 6         | 3.68%   |
| Unknown | 6         | 3.68%   |
| 18      | 5         | 3.07%   |
| 34      | 4         | 2.45%   |
| 12      | 4         | 2.45%   |
| 31      | 2         | 1.23%   |
| 19      | 2         | 1.23%   |
| 16      | 2         | 1.23%   |
| 84      | 1         | 0.61%   |
| 74      | 1         | 0.61%   |
| 35      | 1         | 0.61%   |
| 28      | 1         | 0.61%   |
| 25      | 1         | 0.61%   |
| 22      | 1         | 0.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 64        | 40.25%  |
| 501-600     | 45        | 28.3%   |
| 401-500     | 12        | 7.55%   |
| 201-300     | 11        | 6.92%   |
| 351-400     | 10        | 6.29%   |
| Unknown     | 6         | 3.77%   |
| 701-800     | 4         | 2.52%   |
| 601-700     | 4         | 2.52%   |
| 1501-2000   | 2         | 1.26%   |
| 801-900     | 1         | 0.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 115       | 77.7%   |
| 16/10   | 15        | 10.14%  |
| 21/9    | 5         | 3.38%   |
| Unknown | 5         | 3.38%   |
| 3/2     | 4         | 2.7%    |
| 5/4     | 3         | 2.03%   |
| 4/3     | 1         | 0.68%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 43        | 26.71%  |
| 201-250        | 28        | 17.39%  |
| 81-90          | 23        | 14.29%  |
| 301-350        | 21        | 13.04%  |
| 351-500        | 7         | 4.35%   |
| 251-300        | 7         | 4.35%   |
| 141-150        | 7         | 4.35%   |
| Unknown        | 6         | 3.73%   |
| 71-80          | 5         | 3.11%   |
| 121-130        | 4         | 2.48%   |
| 61-70          | 3         | 1.86%   |
| More than 1000 | 2         | 1.24%   |
| 151-200        | 2         | 1.24%   |
| 131-140        | 2         | 1.24%   |
| 111-120        | 1         | 0.62%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 59        | 37.58%  |
| 51-100        | 44        | 28.03%  |
| 101-120       | 35        | 22.29%  |
| 161-240       | 10        | 6.37%   |
| Unknown       | 6         | 3.82%   |
| More than 240 | 2         | 1.27%   |
| 1-50          | 1         | 0.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 115       | 80.42%  |
| 2     | 18        | 12.59%  |
| 3     | 7         | 4.9%    |
| 0     | 3         | 2.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 85        | 41.67%  |
| Realtek Semiconductor    | 75        | 36.76%  |
| Qualcomm Atheros         | 14        | 6.86%   |
| Broadcom                 | 8         | 3.92%   |
| Ralink Technology        | 3         | 1.47%   |
| Marvell Technology Group | 2         | 0.98%   |
| ASIX Electronics         | 2         | 0.98%   |
| TP-Link                  | 1         | 0.49%   |
| Sierra Wireless          | 1         | 0.49%   |
| Samsung Electronics      | 1         | 0.49%   |
| Ralink                   | 1         | 0.49%   |
| Qualcomm                 | 1         | 0.49%   |
| Microsoft                | 1         | 0.49%   |
| Microchip Technology     | 1         | 0.49%   |
| Lenovo                   | 1         | 0.49%   |
| Huawei Technologies      | 1         | 0.49%   |
| Emulex                   | 1         | 0.49%   |
| Dresden Elektronik       | 1         | 0.49%   |
| Dell                     | 1         | 0.49%   |
| D-Link                   | 1         | 0.49%   |
| Broadcom Limited         | 1         | 0.49%   |
| ASUSTek Computer         | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 60        | 24.69%  |
| Intel Wi-Fi 6 AX200                                               | 15        | 6.17%   |
| Intel I211 Gigabit Network Connection                             | 10        | 4.12%   |
| Intel Wireless 8265 / 8275                                        | 8         | 3.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 2.88%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 2.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 2.06%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 2.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 1.65%   |
| Intel Ethernet Connection (2) I218-V                              | 4         | 1.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 1.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.23%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.23%   |
| Intel Wireless 7265                                               | 3         | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.23%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 2         | 0.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.82%   |
| Intel Wireless 8260                                               | 2         | 0.82%   |
| Intel Wireless 3165                                               | 2         | 0.82%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.82%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.82%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.82%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.82%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 0.82%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.82%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.82%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.41%   |
| Sierra Wireless EM7455                                            | 1         | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.41%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.41%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.41%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.41%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.41%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.41%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.41%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]       | 1         | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.41%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.41%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.41%   |
| Microsoft Wireless XBox Controller Dongle                         | 1         | 0.41%   |
| Microchip HTC Hub Controller                                      | 1         | 0.41%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 1         | 0.41%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.41%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 0.41%   |
| Intel Wireless-AC 9260                                            | 1         | 0.41%   |
| Intel Wireless 7260                                               | 1         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 67        | 58.77%  |
| Realtek Semiconductor    | 18        | 15.79%  |
| Qualcomm Atheros         | 10        | 8.77%   |
| Broadcom                 | 7         | 6.14%   |
| Ralink Technology        | 3         | 2.63%   |
| TP-Link                  | 1         | 0.88%   |
| Sierra Wireless          | 1         | 0.88%   |
| Ralink                   | 1         | 0.88%   |
| Qualcomm                 | 1         | 0.88%   |
| Microsoft                | 1         | 0.88%   |
| Marvell Technology Group | 1         | 0.88%   |
| D-Link                   | 1         | 0.88%   |
| Broadcom Limited         | 1         | 0.88%   |
| ASUSTek Computer         | 1         | 0.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 15        | 13.16%  |
| Intel Wireless 8265 / 8275                                          | 8         | 7.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 7         | 6.14%   |
| Intel Wi-Fi 6 AX201                                                 | 7         | 6.14%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 5         | 4.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                   | 4         | 3.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 3         | 2.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 3         | 2.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 3         | 2.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 3         | 2.63%   |
| Intel Wireless 7265                                                 | 3         | 2.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                            | 3         | 2.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 3         | 2.63%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                   | 2         | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 2         | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 2         | 1.75%   |
| Intel Wireless 8260                                                 | 2         | 1.75%   |
| Intel Wireless 3165                                                 | 2         | 1.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 2         | 1.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 2         | 1.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                     | 2         | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 2         | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 2         | 1.75%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 1         | 0.88%   |
| Sierra Wireless EM7455                                              | 1         | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 1         | 0.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 1         | 0.88%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1         | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                          | 1         | 0.88%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 1         | 0.88%   |
| Ralink MT7601U Wireless Adapter                                     | 1         | 0.88%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                           | 1         | 0.88%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]         | 1         | 0.88%   |
| Microsoft Wireless XBox Controller Dongle                           | 1         | 0.88%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                   | 1         | 0.88%   |
| Intel Wireless-AC 9260                                              | 1         | 0.88%   |
| Intel Wireless 7260                                                 | 1         | 0.88%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection             | 1         | 0.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 1         | 0.88%   |
| Intel Centrino Wireless-N 2230                                      | 1         | 0.88%   |
| D-Link DWA-171                                                      | 1         | 0.88%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter          | 1         | 0.88%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 1         | 0.88%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                  | 1         | 0.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                      | 1         | 0.88%   |
| Broadcom BCM43224 802.11a/b/g/n                                     | 1         | 0.88%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller              | 1         | 0.88%   |
| Broadcom BCM4321 802.11a/b/g/n                                      | 1         | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                       | 1         | 0.88%   |
| ASUS USB-AC56 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU] | 1         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 71        | 58.2%   |
| Intel                    | 37        | 30.33%  |
| Qualcomm Atheros         | 5         | 4.1%    |
| Broadcom                 | 2         | 1.64%   |
| ASIX Electronics         | 2         | 1.64%   |
| Samsung Electronics      | 1         | 0.82%   |
| Marvell Technology Group | 1         | 0.82%   |
| Lenovo                   | 1         | 0.82%   |
| Huawei Technologies      | 1         | 0.82%   |
| Emulex                   | 1         | 0.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 60        | 47.62%  |
| Intel I211 Gigabit Network Connection                             | 10        | 7.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 3.97%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 3.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 3.17%   |
| Intel Ethernet Connection (2) I218-V                              | 4         | 3.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.38%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.59%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 1.59%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 1.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.59%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.59%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.59%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.79%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.79%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.79%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.79%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.79%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.79%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 0.79%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.79%   |
| Intel Ethernet controller                                         | 1         | 0.79%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.79%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.79%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.79%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 0.79%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.79%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1         | 0.79%   |
| Huawei E353/E3131                                                 | 1         | 0.79%   |
| Emulex OneConnect 10Gb NIC (be3)                                  | 1         | 0.79%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 0.79%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 117       | 50.87%  |
| WiFi     | 110       | 47.83%  |
| Modem    | 3         | 1.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 88        | 51.16%  |
| Ethernet | 84        | 48.84%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 73        | 51.05%  |
| 1     | 63        | 44.06%  |
| 3     | 4         | 2.8%    |
| 0     | 2         | 1.4%    |
| 4     | 1         | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 112       | 78.32%  |
| Yes  | 31        | 21.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 62        | 55.36%  |
| Realtek Semiconductor           | 15        | 13.39%  |
| Cambridge Silicon Radio         | 10        | 8.93%   |
| Qualcomm Atheros Communications | 7         | 6.25%   |
| Broadcom                        | 5         | 4.46%   |
| Apple                           | 5         | 4.46%   |
| IMC Networks                    | 2         | 1.79%   |
| HTC (High Tech Computer)        | 2         | 1.79%   |
| ASUSTek Computer                | 2         | 1.79%   |
| Marvell Semiconductor           | 1         | 0.89%   |
| Dell                            | 1         | 0.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                               | 35        | 31.25%  |
| Intel AX200 Bluetooth                                                | 15        | 13.39%  |
| Realtek Bluetooth Radio                                              | 11        | 9.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 10        | 8.93%   |
| Intel Bluetooth wireless interface                                   | 8         | 7.14%   |
| Qualcomm Atheros  Bluetooth Device                                   | 5         | 4.46%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 4         | 3.57%   |
| Apple Bluetooth USB Host Controller                                  | 4         | 3.57%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 2         | 1.79%   |
| IMC Networks Bluetooth Radio                                         | 2         | 1.79%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 2         | 1.79%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2         | 1.79%   |
| Qualcomm Atheros Bluetooth                                           | 1         | 0.89%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1         | 0.89%   |
| Marvell Bluetooth and Wireless LAN Composite                         | 1         | 0.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 1         | 0.89%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1         | 0.89%   |
| Dell BCM20702A0 Bluetooth Module                                     | 1         | 0.89%   |
| Broadcom HP Portable SoftSailing                                     | 1         | 0.89%   |
| Broadcom Bluetooth Device                                            | 1         | 0.89%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1         | 0.89%   |
| ASUS Bluetooth Radio                                                 | 1         | 0.89%   |
| ASUS BCM20702A0                                                      | 1         | 0.89%   |
| Apple Bluetooth HCI                                                  | 1         | 0.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 84        | 38.71%  |
| AMD                                  | 55        | 25.35%  |
| Nvidia                               | 46        | 21.2%   |
| C-Media Electronics                  | 4         | 1.84%   |
| Texas Instruments                    | 3         | 1.38%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.92%   |
| Realtek Semiconductor                | 2         | 0.92%   |
| Logitech                             | 2         | 0.92%   |
| Kingston Technology                  | 2         | 0.92%   |
| Generalplus Technology               | 2         | 0.92%   |
| Focusrite-Novation                   | 2         | 0.92%   |
| Corsair                              | 2         | 0.92%   |
| Valve Software                       | 1         | 0.46%   |
| Sennheiser Communications            | 1         | 0.46%   |
| RODE Microphones                     | 1         | 0.46%   |
| No brand                             | 1         | 0.46%   |
| Micro Star International             | 1         | 0.46%   |
| M-Audio                              | 1         | 0.46%   |
| Lenovo                               | 1         | 0.46%   |
| GYROCOM C&C                          | 1         | 0.46%   |
| Fnatic Gear                          | 1         | 0.46%   |
| Creative Technology                  | 1         | 0.46%   |
| Audient                              | 1         | 0.46%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 19        | 7.42%   |
| AMD Starship/Matisse HD Audio Controller                                   | 15        | 5.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 3.52%   |
| Intel Sunrise Point-LP HD Audio                                            | 9         | 3.52%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 3.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 3.13%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 3.13%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8         | 3.13%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 2.73%   |
| Nvidia GP104 High Definition Audio Controller                              | 6         | 2.34%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 2.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 2.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 2.34%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 1.95%   |
| Intel CM238 HD Audio Controller                                            | 5         | 1.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5         | 1.95%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5         | 1.95%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.56%   |
| Nvidia Audio device                                                        | 4         | 1.56%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 1.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.56%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 1.56%   |
| AMD Navi 10 HDMI Audio                                                     | 4         | 1.56%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3         | 1.17%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 1.17%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 1.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 1.17%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 3         | 1.17%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.17%   |
| Thesycon Systemsoftware & Consulting SMSL M7 1.1.2                         | 2         | 0.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.78%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.78%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.78%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 0.78%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.78%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2         | 0.78%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 0.78%   |
| Generalplus Technology USB Audio Device                                    | 2         | 0.78%   |
| C-Media Electronics Blue Snowball                                          | 2         | 0.78%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 2         | 0.78%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 2         | 0.78%   |
| Valve Software Valve VR Radio & HMD Mic                                    | 1         | 0.39%   |
| Sennheiser Communications GSP 370                                          | 1         | 0.39%   |
| RODE Microphones RODE NT-USB Mini                                          | 1         | 0.39%   |
| Realtek Semiconductor USB2.0 Microphone                                    | 1         | 0.39%   |
| Realtek Semiconductor USB-C to 3.5mm-Headphone Adapter                     | 1         | 0.39%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 0.39%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.39%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 0.39%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.39%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.39%   |
| Nvidia GF110 High Definition Audio Controller                              | 1         | 0.39%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 0.39%   |
| No brand CalDigit Thunderbolt 3 Audio                                      | 1         | 0.39%   |
| Micro Star International USB Audio                                         | 1         | 0.39%   |
| M-Audio M-Track 2X2                                                        | 1         | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Samsung Electronics            | 44        | 30.14%  |
| Kingston                       | 18        | 12.33%  |
| SK Hynix                       | 15        | 10.27%  |
| G.Skill                        | 14        | 9.59%   |
| Corsair                        | 14        | 9.59%   |
| Micron Technology              | 12        | 8.22%   |
| Crucial                        | 10        | 6.85%   |
| Unknown                        | 5         | 3.42%   |
| Ramaxel Technology             | 2         | 1.37%   |
| Unknown (ABCD)                 | 1         | 0.68%   |
| SMART Brazil                   | 1         | 0.68%   |
| Smart                          | 1         | 0.68%   |
| Patriot                        | 1         | 0.68%   |
| Nanya Technology               | 1         | 0.68%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1         | 0.68%   |
| GOODRAM                        | 1         | 0.68%   |
| Goldkey                        | 1         | 0.68%   |
| GeIL                           | 1         | 0.68%   |
| Essencore Limited              | 1         | 0.68%   |
| Elpida                         | 1         | 0.68%   |
| A-DATA Technology              | 1         | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 3.87%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 2.58%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 1.94%   |
| SK Hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 2         | 1.29%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.29%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 2667MT/s         | 2         | 1.29%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1.29%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.29%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s            | 2         | 1.29%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 2         | 1.29%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.29%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s              | 2         | 1.29%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s            | 2         | 1.29%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 0.65%   |
| Unknown RAM Module 4GB DIMM 400MT/s                              | 1         | 0.65%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1         | 0.65%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                        | 1         | 0.65%   |
| Unknown RAM 2133 C14 Series 8192MB DIMM DDR4 2133MT/s            | 1         | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.65%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1333MT/s            | 1         | 0.65%   |
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 1         | 0.65%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 0.65%   |
| SK Hynix RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 0.65%   |
| SK Hynix RAM Module 2GB Row Of Chips LPDDR3 1867MT/s             | 1         | 0.65%   |
| SK Hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.65%   |
| SK Hynix RAM HMT351U6CFR8C 4GB DIMM DDR3 1333MT/s                | 1         | 0.65%   |
| SK Hynix RAM HMT351R7BFR4A-H9 4096MB DIMM DDR3 1333MT/s          | 1         | 0.65%   |
| SK Hynix RAM HMT31GR7CFR4A-H9 8192MB DIMM DDR3 1333MT/s          | 1         | 0.65%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 0.65%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.65%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.65%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 0.65%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.65%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 0.65%   |
| SK Hynix RAM HCNNNCPMBLHR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 0.65%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.65%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                   | 1         | 0.65%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.65%   |
| Samsung RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 0.65%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 0.65%   |
| Samsung RAM M471B5673EH1-CF8 2048MB SODIMM DDR3 4199MT/s         | 1         | 0.65%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 0.65%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 0.65%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 0.65%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 0.65%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s        | 1         | 0.65%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 0.65%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 0.65%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 1         | 0.65%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s            | 1         | 0.65%   |
| Samsung RAM M4 70T5663QZ3-CF7 2048MB SODIMM DDR2 2048MT/s        | 1         | 0.65%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 800MT/s            | 1         | 0.65%   |
| Samsung RAM M4 70T2864EH3-CF7 1GB SODIMM DDR2 2048MT/s           | 1         | 0.65%   |
| Samsung RAM M393B5273DH0-CK0 4096MB DIMM DDR3 1600MT/s           | 1         | 0.65%   |
| Samsung RAM M378A1K43BB1-CPB 8GB DIMM DDR4 2733MT/s              | 1         | 0.65%   |
| Samsung RAM K4U6E3S4AA-MGCL 4GB Row Of Chips LPDDR4 4267MT/s     | 1         | 0.65%   |
| Ramaxel RAM RMSA3310MJ86H9F-3200 4GB SODIMM DDR4 3200MT/s        | 1         | 0.65%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8192MB SODIMM DDR4 2667MT/s     | 1         | 0.65%   |
| Patriot RAM 2666 C18 Series 8GB SODIMM DDR4 2667MT/s             | 1         | 0.65%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4096MB SODIMM DDR3 1600MT/s          | 1         | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 83        | 68.03%  |
| DDR3    | 24        | 19.67%  |
| LPDDR4  | 6         | 4.92%   |
| SDRAM   | 4         | 3.28%   |
| LPDDR3  | 2         | 1.64%   |
| Unknown | 2         | 1.64%   |
| DDR2    | 1         | 0.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 64        | 51.61%  |
| DIMM         | 48        | 38.71%  |
| Row Of Chips | 11        | 8.87%   |
| Chip         | 1         | 0.81%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 58        | 44.96%  |
| 4096  | 31        | 24.03%  |
| 16384 | 22        | 17.05%  |
| 2048  | 11        | 8.53%   |
| 32768 | 4         | 3.1%    |
| 1024  | 3         | 2.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 31        | 22.46%  |
| 2667  | 26        | 18.84%  |
| 1600  | 16        | 11.59%  |
| 2400  | 13        | 9.42%   |
| 3600  | 7         | 5.07%   |
| 2133  | 6         | 4.35%   |
| 4267  | 5         | 3.62%   |
| 3266  | 4         | 2.9%    |
| 1333  | 4         | 2.9%    |
| 2933  | 3         | 2.17%   |
| 1867  | 3         | 2.17%   |
| 4199  | 2         | 1.45%   |
| 3733  | 2         | 1.45%   |
| 3466  | 2         | 1.45%   |
| 2666  | 2         | 1.45%   |
| 2048  | 2         | 1.45%   |
| 1334  | 2         | 1.45%   |
| 667   | 2         | 1.45%   |
| 4000  | 1         | 0.72%   |
| 3866  | 1         | 0.72%   |
| 3000  | 1         | 0.72%   |
| 2733  | 1         | 0.72%   |
| 1067  | 1         | 0.72%   |
| 400   | 1         | 0.72%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)

![Printer Vendor](./images/line_chart/printer_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |
| Brother Industries  | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)

![Printer Model](./images/line_chart/printer_model.svg)

| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 1         | 33.33%  |
| HP ENVY 5540 series           | 1         | 33.33%  |
| Brother Printer               | 1         | 33.33%  |

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
| Chicony Electronics                    | 20        | 20.83%  |
| Microdia                               | 13        | 13.54%  |
| Logitech                               | 10        | 10.42%  |
| IMC Networks                           | 10        | 10.42%  |
| Quanta                                 | 8         | 8.33%   |
| Realtek Semiconductor                  | 6         | 6.25%   |
| Acer                                   | 5         | 5.21%   |
| Sunplus Innovation Technology          | 4         | 4.17%   |
| Lite-On Technology                     | 3         | 3.13%   |
| Alcor Micro                            | 3         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.08%   |
| Apple                                  | 2         | 2.08%   |
| Valve Software                         | 1         | 1.04%   |
| Syntek                                 | 1         | 1.04%   |
| Sonix Technology                       | 1         | 1.04%   |
| SJ-180517-N                            | 1         | 1.04%   |
| Silicon Motion                         | 1         | 1.04%   |
| MACROSILICON                           | 1         | 1.04%   |
| Luxvisions Innotech Limited            | 1         | 1.04%   |
| Lenovo                                 | 1         | 1.04%   |
| Holitech                               | 1         | 1.04%   |
| DJJHNA29IE9J88                         | 1         | 1.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 8         | 8.33%   |
| Microdia Integrated_Webcam_HD                                | 5         | 5.21%   |
| Realtek Integrated_Webcam_HD                                 | 4         | 4.17%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 4         | 4.17%   |
| Logitech HD Pro Webcam C920                                  | 3         | 3.13%   |
| IMC Networks Integrated Camera                               | 3         | 3.13%   |
| Acer Integrated Camera                                       | 3         | 3.13%   |
| Sunplus Integrated_Webcam_HD                                 | 2         | 2.08%   |
| Sunplus HD 720P webcam                                       | 2         | 2.08%   |
| Quanta HP Wide Vision HD Camera                              | 2         | 2.08%   |
| Quanta HP Webcam                                             | 2         | 2.08%   |
| Quanta HP TrueVision HD Camera                               | 2         | 2.08%   |
| Logitech HD Webcam C910                                      | 2         | 2.08%   |
| Logitech BRIO                                                | 2         | 2.08%   |
| IMC Networks USB2.0 HD IR UVC WebCam                         | 2         | 2.08%   |
| Chicony HP HD Webcam [Fixed]                                 | 2         | 2.08%   |
| Chicony HD Webcam                                            | 2         | 2.08%   |
| Valve Software 3D Camera                                     | 1         | 1.04%   |
| Syntek Lenovo EasyCamera                                     | 1         | 1.04%   |
| Sonix USB2.0 HD UVC WebCam                                   | 1         | 1.04%   |
| SJ-180517-N 1080P Webcam                                     | 1         | 1.04%   |
| Silicon Motion WebCam SC-0311139N                            | 1         | 1.04%   |
| Realtek LG Webcam                                            | 1         | 1.04%   |
| Realtek LG Camera                                            | 1         | 1.04%   |
| Quanta HD User Facing                                        | 1         | 1.04%   |
| Quanta HD Camera                                             | 1         | 1.04%   |
| Microdia Webcam Vitade AF                                    | 1         | 1.04%   |
| Microdia USB 2.0 Camera                                      | 1         | 1.04%   |
| Microdia Sonix Integrated Webcam                             | 1         | 1.04%   |
| Microdia Laptop_Integrated_Webcam_E4HD                       | 1         | 1.04%   |
| Microdia Integrated Webcam HD                                | 1         | 1.04%   |
| Microdia Integrated Camera                                   | 1         | 1.04%   |
| Microdia Dell Laptop Integrated Webcam HD                    | 1         | 1.04%   |
| Microdia Camera                                              | 1         | 1.04%   |
| MACROSILICON ShadowCast                                      | 1         | 1.04%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera         | 1         | 1.04%   |
| Logitech Webcam C930e                                        | 1         | 1.04%   |
| Logitech Webcam C310                                         | 1         | 1.04%   |
| Logitech Webcam C270                                         | 1         | 1.04%   |
| Lite-On Integrated Camera                                    | 1         | 1.04%   |
| Lite-On HP HD Camera                                         | 1         | 1.04%   |
| Lite-On HP 2.0MP High Definition Webcam                      | 1         | 1.04%   |
| Lenovo Integrated Webcam                                     | 1         | 1.04%   |
| IMC Networks 2M Integrated Webcam                            | 1         | 1.04%   |
| Holitech USB2.0 HD UVC WebCam                                | 1         | 1.04%   |
| DJJHNA29IE9J88 HP HD Camera                                  | 1         | 1.04%   |
| Chicony UVC 1.00 device HD UVC WebCam                        | 1         | 1.04%   |
| Chicony USB2.0 HD UVC WebCam                                 | 1         | 1.04%   |
| Chicony USB2.0 Camera                                        | 1         | 1.04%   |
| Chicony USB 2.0 Camera                                       | 1         | 1.04%   |
| Chicony Lenovo EasyCamera                                    | 1         | 1.04%   |
| Chicony HP Wide Vision HD Camera                             | 1         | 1.04%   |
| Chicony HD User Facing                                       | 1         | 1.04%   |
| Chicony CNF9055 Toshiba Webcam                               | 1         | 1.04%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 1.04%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera             | 1         | 1.04%   |
| Apple FaceTime Camera                                        | 1         | 1.04%   |
| Apple Built-in iSight                                        | 1         | 1.04%   |
| Alcor Micro USB Camera                                       | 1         | 1.04%   |
| Alcor Micro USB 2.0 Camera                                   | 1         | 1.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 42.86%  |
| Shenzhen Goodix Technology | 6         | 42.86%  |
| Elan Microelectronics      | 1         | 7.14%   |
| AuthenTec                  | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device               | 3         | 21.43%  |
| Validity Sensors VFS491                           | 2         | 14.29%  |
| Validity Sensors Synaptics WBDI                   | 2         | 14.29%  |
| Shenzhen Goodix FingerPrint                       | 2         | 14.29%  |
| Validity Sensors VFS7552 Touch Fingerprint Sensor | 1         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 7.14%   |
| Elan ELAN:Fingerprint                             | 1         | 7.14%   |
| AuthenTec AES2810                                 | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./images/line_chart/chipcard_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 62.5%   |
| Lenovo                | 1         | 12.5%   |
| Alcor Micro           | 1         | 12.5%   |
| Advanced Card Systems | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)

![Chipcard Model](./images/line_chart/chipcard_model.svg)

| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 2         | 25%     |
| Lenovo Integrated Smart Card Reader                                          | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 12.5%   |
| Broadcom 5880                                                                | 1         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 12.5%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 106       | 74.13%  |
| 1     | 31        | 21.68%  |
| 2     | 5         | 3.5%    |
| 3     | 1         | 0.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 13        | 29.55%  |
| Chipcard                 | 7         | 15.91%  |
| Graphics card            | 6         | 13.64%  |
| Multimedia controller    | 4         | 9.09%   |
| Camera                   | 4         | 9.09%   |
| Net/wireless             | 2         | 4.55%   |
| Bluetooth                | 2         | 4.55%   |
| Unassigned class         | 1         | 2.27%   |
| Storage                  | 1         | 2.27%   |
| Network                  | 1         | 2.27%   |
| Net/ethernet             | 1         | 2.27%   |
| Firewire controller      | 1         | 2.27%   |
| Communication controller | 1         | 2.27%   |

