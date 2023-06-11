Debian - Hardware Trends
------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/Debian/Desktop/README.md) and [notebooks](/Dist/Debian/Notebook/README.md).

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

![OS](./images/pie_chart/os_name.svg)

![OS](./images/line_chart/os_name.svg)

| Name      | Computers | Percent |
|-----------|-----------|---------|
| Debian 11 | 255       | 61.15%  |
| Debian 12 | 157       | 37.65%  |
| Debian 10 | 3         | 0.72%   |
| Debian 9  | 1         | 0.24%   |
| Debian 23 | 1         | 0.24%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)

![OS Family](./images/line_chart/os_family.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| Debian | 417       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)

![Kernel](./images/line_chart/os_kernel.svg)

| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-22-amd64           | 77        | 18.47%  |
| 5.10.0-23-amd64           | 70        | 16.79%  |
| 6.1.0-4-amd64             | 53        | 12.71%  |
| 6.1.0-9-amd64             | 46        | 11.03%  |
| 6.1.0-7-amd64             | 26        | 6.24%   |
| 5.10.0-21-amd64           | 17        | 4.08%   |
| 6.1.0-8-amd64             | 14        | 3.36%   |
| 5.10.0-20-amd64           | 12        | 2.88%   |
| 5.15.107-1-pve            | 9         | 2.16%   |
| 5.15.107-2-pve            | 8         | 1.92%   |
| 6.1.21-v8+                | 6         | 1.44%   |
| 6.1.0-0.deb11.7-amd64     | 5         | 1.2%    |
| 5.15.102-1-pve            | 4         | 0.96%   |
| 6.1.0-0.deb11.6-amd64     | 3         | 0.72%   |
| 5.10.0-18-amd64           | 3         | 0.72%   |
| 6.2.11-1-pve              | 2         | 0.48%   |
| 6.1.0-7-rt-amd64          | 2         | 0.48%   |
| 6.1.0-6-amd64             | 2         | 0.48%   |
| 6.0.0-6mx-amd64           | 2         | 0.48%   |
| 5.15.104-1-pve            | 2         | 0.48%   |
| 5.15.0-starfive           | 2         | 0.48%   |
| 5.10.110-rockchip-rk3588  | 2         | 0.48%   |
| 4.19.0-24-amd64           | 2         | 0.48%   |
| 6.3.4-latitude-xanmod1    | 1         | 0.24%   |
| 6.3.4-dell-latitude-e5510 | 1         | 0.24%   |
| 6.3.4-asus-amd            | 1         | 0.24%   |
| 6.3.3-tkg-cfs             | 1         | 0.24%   |
| 6.3.0-titanide            | 1         | 0.24%   |
| 6.3.0-7-amd64             | 1         | 0.24%   |
| 6.3.0-0-amd64             | 1         | 0.24%   |
| 6.2.14-1-liquorix-amd64   | 1         | 0.24%   |
| 6.1.20-bootes0-p-1000     | 1         | 0.24%   |
| 6.1.15-1-pve              | 1         | 0.24%   |
| 6.1.11-sunxi              | 1         | 0.24%   |
| 6.1.11-stb-cbq            | 1         | 0.24%   |
| 6.1.0-8mx-ahs-amd64       | 1         | 0.24%   |
| 6.1.0-0.deb11.5-amd64     | 1         | 0.24%   |
| 6.1.0-0-amd64             | 1         | 0.24%   |
| 6.1-sunxi64               | 1         | 0.24%   |
| 6.0.9                     | 1         | 0.24%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)

![Kernel Family](./images/line_chart/os_kernel_family.svg)

| Version    | Computers | Percent |
|------------|-----------|---------|
| 5.10.0     | 189       | 45.32%  |
| 6.1.0      | 154       | 36.93%  |
| 5.15.107   | 17        | 4.08%   |
| 6.1.21     | 6         | 1.44%   |
| 6.0.0      | 5         | 1.2%    |
| 5.15.102   | 4         | 0.96%   |
| 4.19.0     | 4         | 0.96%   |
| 6.3.4      | 3         | 0.72%   |
| 6.3.0      | 3         | 0.72%   |
| 5.15.0     | 3         | 0.72%   |
| 6.2.11     | 2         | 0.48%   |
| 6.1.11     | 2         | 0.48%   |
| 5.16.0     | 2         | 0.48%   |
| 5.15.79    | 2         | 0.48%   |
| 5.15.104   | 2         | 0.48%   |
| 5.10.110   | 2         | 0.48%   |
| 6.3.3      | 1         | 0.24%   |
| 6.2.14     | 1         | 0.24%   |
| 6.1.20     | 1         | 0.24%   |
| 6.1.15     | 1         | 0.24%   |
| 6.1        | 1         | 0.24%   |
| 6.0.9      | 1         | 0.24%   |
| 5.18.0     | 1         | 0.24%   |
| 5.15.94    | 1         | 0.24%   |
| 5.15.85    | 1         | 0.24%   |
| 5.15.84    | 1         | 0.24%   |
| 5.15.74    | 1         | 0.24%   |
| 5.15.60    | 1         | 0.24%   |
| 5.10.78    | 1         | 0.24%   |
| 5.10.164.2 | 1         | 0.24%   |
| 5.10.113   | 1         | 0.24%   |
| 4.9.318    | 1         | 0.24%   |
| 4.14.180   | 1         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./images/line_chart/os_kernel_major.svg)

| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10     | 193       | 46.28%  |
| 6.1      | 164       | 39.33%  |
| 5.15     | 33        | 7.91%   |
| 6.3      | 7         | 1.68%   |
| 6.0      | 6         | 1.44%   |
| 4.19     | 4         | 0.96%   |
| 6.2      | 3         | 0.72%   |
| 5.16     | 2         | 0.48%   |
| 6        | 1         | 0.24%   |
| 5.18     | 1         | 0.24%   |
| 5.10.164 | 1         | 0.24%   |
| 4.9      | 1         | 0.24%   |
| 4.14     | 1         | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)

![Arch](./images/line_chart/os_arch.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 392       | 94%     |
| aarch64 | 15        | 3.6%    |
| i686    | 5         | 1.2%    |
| riscv64 | 3         | 0.72%   |
| armv7l  | 2         | 0.48%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)

![DE](./images/line_chart/os_de.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 128       | 30.7%   |
| GNOME         | 113       | 27.1%   |
| KDE5          | 59        | 14.15%  |
| XFCE          | 55        | 13.19%  |
| X-Cinnamon    | 17        | 4.08%   |
| MATE          | 14        | 3.36%   |
| LXDE          | 6         | 1.44%   |
| LXQt          | 5         | 1.2%    |
| Cinnamon      | 5         | 1.2%    |
| GNOME Classic | 3         | 0.72%   |
| Trinity       | 2         | 0.48%   |
| openbox       | 2         | 0.48%   |
| KDE           | 2         | 0.48%   |
| i3            | 2         | 0.48%   |
| Budgie        | 2         | 0.48%   |
| Pantheon      | 1         | 0.24%   |
| GNUstep       | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)

![Display Server](./images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 195       | 46.76%  |
| Unknown | 83        | 19.9%   |
| Wayland | 79        | 18.94%  |
| Tty     | 60        | 14.39%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)

![Display Manager](./images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 181       | 43.41%  |
| LightDM | 93        | 22.3%   |
| GDM3    | 57        | 13.67%  |
| SDDM    | 44        | 10.55%  |
| GDM     | 40        | 9.59%   |
| SLiM    | 1         | 0.24%   |
| Ly      | 1         | 0.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)

![OS Lang](./images/line_chart/os_lang.svg)

| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 139       | 33.33%  |
| ru_RU   | 67        | 16.07%  |
| de_DE   | 41        | 9.83%   |
| fr_FR   | 36        | 8.63%   |
| sv_SE   | 17        | 4.08%   |
| en_GB   | 17        | 4.08%   |
| pt_BR   | 9         | 2.16%   |
| es_ES   | 8         | 1.92%   |
| C       | 8         | 1.92%   |
| Unknown | 8         | 1.92%   |
| zh_CN   | 7         | 1.68%   |
| pl_PL   | 6         | 1.44%   |
| it_IT   | 6         | 1.44%   |
| en_CA   | 6         | 1.44%   |
| en_IE   | 4         | 0.96%   |
| es_MX   | 3         | 0.72%   |
| es_AR   | 3         | 0.72%   |
| en_IN   | 3         | 0.72%   |
| sk_SK   | 2         | 0.48%   |
| nl_BE   | 2         | 0.48%   |
| fi_FI   | 2         | 0.48%   |
| en_AU   | 2         | 0.48%   |
| de_AT   | 2         | 0.48%   |
| cs_CZ   | 2         | 0.48%   |
| tr_TR   | 1         | 0.24%   |
| ru_UA   | 1         | 0.24%   |
| ko_KR   | 1         | 0.24%   |
| ja_JP   | 1         | 0.24%   |
| hu_HU   | 1         | 0.24%   |
| hr_HR   | 1         | 0.24%   |
| fr_CH   | 1         | 0.24%   |
| fr_BE   | 1         | 0.24%   |
| es_VE   | 1         | 0.24%   |
| es_PA   | 1         | 0.24%   |
| es_EC   | 1         | 0.24%   |
| en_NZ   | 1         | 0.24%   |
| en_IL   | 1         | 0.24%   |
| en_HK   | 1         | 0.24%   |
| en_DK   | 1         | 0.24%   |
| el_GR   | 1         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)

![Boot Mode](./images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 224       | 53.72%  |
| BIOS | 193       | 46.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)

![Filesystem](./images/line_chart/os_filesystem.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 304       | 72.9%   |
| Overlay | 77        | 18.47%  |
| Btrfs   | 16        | 3.84%   |
| Zfs     | 7         | 1.68%   |
| Tmpfs   | 5         | 1.2%    |
| Xfs     | 3         | 0.72%   |
| Ext2    | 3         | 0.72%   |
| Ext3    | 2         | 0.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)

![Part. scheme](./images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 246       | 58.99%  |
| MBR     | 111       | 26.62%  |
| Unknown | 60        | 14.39%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 365       | 87.53%  |
| Yes       | 52        | 12.47%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 283       | 67.87%  |
| Yes       | 134       | 32.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)

![Vendor](./images/line_chart/node_vendor.svg)

| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 76        | 18.23%  |
| Lenovo                  | 64        | 15.35%  |
| Hewlett-Packard         | 48        | 11.51%  |
| Dell                    | 46        | 11.03%  |
| Gigabyte Technology     | 32        | 7.67%   |
| MSI                     | 22        | 5.28%   |
| Acer                    | 19        | 4.56%   |
| ASRock                  | 15        | 3.6%    |
| Unknown                 | 15        | 3.6%    |
| Intel                   | 9         | 2.16%   |
| Raspberry Pi Foundation | 8         | 1.92%   |
| Apple                   | 7         | 1.68%   |
| Fujitsu                 | 6         | 1.44%   |
| Supermicro              | 5         | 1.2%    |
| Aquarius                | 4         | 0.96%   |
| Toshiba                 | 3         | 0.72%   |
| AZW                     | 3         | 0.72%   |
| sunxi                   | 2         | 0.48%   |
| Rockchip                | 2         | 0.48%   |
| Pegatron                | 2         | 0.48%   |
| Notebook                | 2         | 0.48%   |
| Microsoft               | 2         | 0.48%   |
| HUAWEI                  | 2         | 0.48%   |
| ECS                     | 2         | 0.48%   |
| BESSTAR Tech            | 2         | 0.48%   |
| AMI                     | 2         | 0.48%   |
| Terrans Force           | 1         | 0.24%   |
| Sony                    | 1         | 0.24%   |
| Samsung Electronics     | 1         | 0.24%   |
| Pine Microsystems       | 1         | 0.24%   |
| Medion                  | 1         | 0.24%   |
| Inventec                | 1         | 0.24%   |
| HPE                     | 1         | 0.24%   |
| GreatWall               | 1         | 0.24%   |
| GPD                     | 1         | 0.24%   |
| Google                  | 1         | 0.24%   |
| eMachines               | 1         | 0.24%   |
| Chuwi                   | 1         | 0.24%   |
| Boot Hardware           | 1         | 0.24%   |
| Biostar                 | 1         | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)

![Model](./images/line_chart/node_model.svg)

| Name                                            | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| ASUS All Series                                 | 18        | 4.32%   |
| Unknown                                         | 17        | 4.08%   |
| Gigabyte H81M-S2V                               | 8         | 1.92%   |
| Lenovo ThinkPad L14 Gen 2 20X1004CMX            | 4         | 0.96%   |
| Lenovo ThinkPad L13 Gen 2 20VJS6RY00            | 4         | 0.96%   |
| Aquarius NS585                                  | 4         | 0.96%   |
| RPi Raspberry Pi 3 Model B Plus Rev 1.3         | 3         | 0.72%   |
| HP Elite x360 830 13 inch G9 2-in-1 Notebook PC | 3         | 0.72%   |
| Dell Precision Tower 5810                       | 3         | 0.72%   |
| Rockchip Orange Pi 5                            | 2         | 0.48%   |
| Notebook W54_55SU1,SUW                          | 2         | 0.48%   |
| MSI MS-7816                                     | 2         | 0.48%   |
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US       | 2         | 0.48%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US           | 2         | 0.48%   |
| Intel X99                                       | 2         | 0.48%   |
| HP ProBook 640 G1                               | 2         | 0.48%   |
| HP ProBook 440 14 inch G9 Notebook PC           | 2         | 0.48%   |
| Gigabyte M68MT-S2                               | 2         | 0.48%   |
| Gigabyte M56S-S3                                | 2         | 0.48%   |
| Gigabyte B550I AORUS PRO AX                     | 2         | 0.48%   |
| ECS G31T-M9                                     | 2         | 0.48%   |
| Dell Latitude E5430 non-vPro                    | 2         | 0.48%   |
| Dell Latitude 5411                              | 2         | 0.48%   |
| ASUS PRIME B760M-A D4                           | 2         | 0.48%   |
| ASUS P8H67-M                                    | 2         | 0.48%   |
| ASRock B450 Gaming-ITX/ac                       | 2         | 0.48%   |
| Apple Macmini7,1                                | 2         | 0.48%   |
| Toshiba Satellite X200                          | 1         | 0.24%   |
| Toshiba Satellite Pro C660                      | 1         | 0.24%   |
| Toshiba Satellite C855-22N                      | 1         | 0.24%   |
| Terrans Force AMD                               | 1         | 0.24%   |
| Supermicro X9DRW                                | 1         | 0.24%   |
| Supermicro X9DR3-F                              | 1         | 0.24%   |
| Supermicro X8DTU                                | 1         | 0.24%   |
| Supermicro X10DRi                               | 1         | 0.24%   |
| Supermicro PIO-617R-TLN4F+-ST031                | 1         | 0.24%   |
| sunxi Banana Pi BPI-M2-Ultra                    | 1         | 0.24%   |
| Sony VPCF13WFX                                  | 1         | 0.24%   |
| Samsung 530U3C/530U4C/532U3C                    | 1         | 0.24%   |
| RPi Raspberry Pi 4 Model B Rev 1.4              | 1         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)

![Model Family](./images/line_chart/node_model_family.svg)

| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 45        | 10.79%  |
| ASUS All           | 18        | 4.32%   |
| Unknown            | 17        | 4.08%   |
| Dell Latitude      | 16        | 3.84%   |
| ASUS PRIME         | 16        | 3.84%   |
| Acer Aspire        | 12        | 2.88%   |
| RPi Raspberry      | 8         | 1.92%   |
| Gigabyte H81M-S2V  | 8         | 1.92%   |
| Dell Precision     | 8         | 1.92%   |
| HP EliteBook       | 7         | 1.68%   |
| ASUS ROG           | 7         | 1.68%   |
| Lenovo ThinkCentre | 6         | 1.44%   |
| HP ProBook         | 6         | 1.44%   |
| Dell OptiPlex      | 6         | 1.44%   |
| Lenovo IdeaPad     | 5         | 1.2%    |
| HP Laptop          | 5         | 1.2%    |
| Dell Inspiron      | 5         | 1.2%    |
| HP Elite           | 4         | 0.96%   |
| HP Compaq          | 4         | 0.96%   |
| Dell Vostro        | 4         | 0.96%   |
| Dell PowerEdge     | 4         | 0.96%   |
| Aquarius NS585     | 4         | 0.96%   |
| Toshiba Satellite  | 3         | 0.72%   |
| HP EliteDesk       | 3         | 0.72%   |
| ASUS MINIPC        | 3         | 0.72%   |
| ASUS ASUS          | 3         | 0.72%   |
| Acer TravelMate    | 3         | 0.72%   |
| Rockchip Orange    | 2         | 0.48%   |
| Notebook W54       | 2         | 0.48%   |
| MSI MS-7816        | 2         | 0.48%   |
| Microsoft Surface  | 2         | 0.48%   |
| Intel X99          | 2         | 0.48%   |
| HP Pavilion        | 2         | 0.48%   |
| HP ENVY            | 2         | 0.48%   |
| HP 250             | 2         | 0.48%   |
| Gigabyte M68MT-S2  | 2         | 0.48%   |
| Gigabyte M56S-S3   | 2         | 0.48%   |
| Gigabyte B550I     | 2         | 0.48%   |
| Fujitsu LIFEBOOK   | 2         | 0.48%   |
| Fujitsu ESPRIMO    | 2         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)

![MFG Year](./images/line_chart/node_year.svg)

| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 41        | 9.83%   |
| 2020    | 39        | 9.35%   |
| 2022    | 38        | 9.11%   |
| 2012    | 37        | 8.87%   |
| 2018    | 31        | 7.43%   |
| 2019    | 30        | 7.19%   |
| 2017    | 24        | 5.76%   |
| 2013    | 24        | 5.76%   |
| 2010    | 24        | 5.76%   |
| 2014    | 23        | 5.52%   |
| 2015    | 18        | 4.32%   |
| 2011    | 18        | 4.32%   |
| Unknown | 18        | 4.32%   |
| 2016    | 15        | 3.6%    |
| 2009    | 12        | 2.88%   |
| 2023    | 10        | 2.4%    |
| 2007    | 9         | 2.16%   |
| 2008    | 5         | 1.2%    |
| 2003    | 1         | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)

![Form Factor](./images/line_chart/node_formfactor.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 188       | 45.08%  |
| Notebook       | 164       | 39.33%  |
| System on chip | 19        | 4.56%   |
| Convertible    | 15        | 3.6%    |
| Mini pc        | 14        | 3.36%   |
| Server         | 12        | 2.88%   |
| Tablet         | 3         | 0.72%   |
| Phone          | 1         | 0.24%   |
| All in one     | 1         | 0.24%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)

![Secure Boot](./images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 381       | 91.37%  |
| Enabled  | 36        | 8.63%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)

![Coreboot](./images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 417       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)

![RAM Size](./images/line_chart/node_ram_total.svg)

| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 95        | 22.78%  |
| 3.01-4.0        | 71        | 17.03%  |
| 16.01-24.0      | 66        | 15.83%  |
| 8.01-16.0       | 65        | 15.59%  |
| 32.01-64.0      | 63        | 15.11%  |
| 64.01-256.0     | 24        | 5.76%   |
| 1.01-2.0        | 10        | 2.4%    |
| 0.51-1.0        | 9         | 2.16%   |
| 2.01-3.0        | 6         | 1.44%   |
| 24.01-32.0      | 5         | 1.2%    |
| More than 256.0 | 2         | 0.48%   |
| 0.01-0.5        | 1         | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)

![RAM Used](./images/line_chart/node_ram_used.svg)

| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 121       | 29.02%  |
| 2.01-3.0   | 72        | 17.27%  |
| 0.51-1.0   | 71        | 17.03%  |
| 4.01-8.0   | 56        | 13.43%  |
| 3.01-4.0   | 40        | 9.59%   |
| 0.01-0.5   | 24        | 5.76%   |
| 8.01-16.0  | 22        | 5.28%   |
| 16.01-24.0 | 5         | 1.2%    |
| 32.01-64.0 | 4         | 0.96%   |
| 24.01-32.0 | 2         | 0.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)

![Total Drives](./images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 261       | 62.59%  |
| 2      | 87        | 20.86%  |
| 3      | 30        | 7.19%   |
| 6      | 10        | 2.4%    |
| 4      | 10        | 2.4%    |
| 5      | 7         | 1.68%   |
| 0      | 4         | 0.96%   |
| 7      | 3         | 0.72%   |
| 9      | 2         | 0.48%   |
| 8      | 2         | 0.48%   |
| 79     | 1         | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 311       | 74.58%  |
| Yes       | 106       | 25.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 366       | 87.77%  |
| No        | 51        | 12.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)

![Has WiFi](./images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 257       | 61.63%  |
| No        | 160       | 38.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 214       | 51.32%  |
| No        | 203       | 48.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)

![Country](./images/line_chart/node_location.svg)

| Country     | Computers | Percent |
|-------------|-----------|---------|
| Russia      | 72        | 17.27%  |
| Germany     | 53        | 12.71%  |
| USA         | 52        | 12.47%  |
| France      | 38        | 9.11%   |
| Sweden      | 25        | 6%      |
| Brazil      | 17        | 4.08%   |
| Poland      | 11        | 2.64%   |
| UK          | 10        | 2.4%    |
| Spain       | 10        | 2.4%    |
| China       | 10        | 2.4%    |
| Canada      | 10        | 2.4%    |
| Italy       | 9         | 2.16%   |
| Argentina   | 8         | 1.92%   |
| Mexico      | 5         | 1.2%    |
| Czechia     | 5         | 1.2%    |
| Switzerland | 4         | 0.96%   |
| Slovakia    | 4         | 0.96%   |
| Norway      | 4         | 0.96%   |
| Netherlands | 4         | 0.96%   |
| India       | 4         | 0.96%   |
| Hungary     | 4         | 0.96%   |
| Finland     | 4         | 0.96%   |
| Japan       | 3         | 0.72%   |
| Ireland     | 3         | 0.72%   |
| Denmark     | 3         | 0.72%   |
| Belgium     | 3         | 0.72%   |
| Austria     | 3         | 0.72%   |
| Australia   | 3         | 0.72%   |
| Uzbekistan  | 2         | 0.48%   |
| Ukraine     | 2         | 0.48%   |
| UAE         | 2         | 0.48%   |
| Pakistan    | 2         | 0.48%   |
| New Zealand | 2         | 0.48%   |
| Israel      | 2         | 0.48%   |
| Greece      | 2         | 0.48%   |
| Croatia     | 2         | 0.48%   |
| Belarus     | 2         | 0.48%   |
| Vietnam     | 1         | 0.24%   |
| Venezuela   | 1         | 0.24%   |
| Uruguay     | 1         | 0.24%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)

![City](./images/line_chart/node_city.svg)

| City             | Computers | Percent |
|------------------|-----------|---------|
| Voronezh         | 53        | 12.71%  |
| Saltsjoe-Boo     | 21        | 5.04%   |
| Moscow           | 11        | 2.64%   |
| Bangor           | 6         | 1.44%   |
| Paris            | 5         | 1.2%    |
| Lherm            | 4         | 0.96%   |
| Berlin           | 4         | 0.96%   |
| Tiranges         | 3         | 0.72%   |
| Stuttgart        | 3         | 0.72%   |
| Santos           | 3         | 0.72%   |
| Nuremberg        | 3         | 0.72%   |
| Hamburg          | 3         | 0.72%   |
| Gladbeck         | 3         | 0.72%   |
| Dublin           | 3         | 0.72%   |
| Buenos Aires     | 3         | 0.72%   |
| Warsaw           | 2         | 0.48%   |
| Tilst            | 2         | 0.48%   |
| Tashkent         | 2         | 0.48%   |
| Siegsdorf        | 2         | 0.48%   |
| Seattle          | 2         | 0.48%   |
| Sao Paulo        | 2         | 0.48%   |
| Prague           | 2         | 0.48%   |
| Oslo             | 2         | 0.48%   |
| Montreal         | 2         | 0.48%   |
| Minsk            | 2         | 0.48%   |
| Miami            | 2         | 0.48%   |
| Manchester       | 2         | 0.48%   |
| Londrina         | 2         | 0.48%   |
| La Roche-de-Glun | 2         | 0.48%   |
| Karachi          | 2         | 0.48%   |
| Helsinki         | 2         | 0.48%   |
| Gaocheng         | 2         | 0.48%   |
| Foshan           | 2         | 0.48%   |
| Florence         | 2         | 0.48%   |
| Dubai            | 2         | 0.48%   |
| Dortmund         | 2         | 0.48%   |
| Budapest         | 2         | 0.48%   |
| Brussels         | 2         | 0.48%   |
| Bad Koetzting    | 2         | 0.48%   |
| Asker            | 2         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)

![Drive Vendor](./images/line_chart/drive_vendor.svg)

| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 107       | 138    | 18.23%  |
| Samsung Electronics         | 88        | 116    | 14.99%  |
| Seagate                     | 73        | 163    | 12.44%  |
| Toshiba                     | 37        | 42     | 6.3%    |
| Unknown                     | 31        | 36     | 5.28%   |
| Sandisk                     | 25        | 28     | 4.26%   |
| Kingston                    | 24        | 25     | 4.09%   |
| Crucial                     | 21        | 26     | 3.58%   |
| HGST                        | 14        | 17     | 2.39%   |
| SK hynix                    | 11        | 11     | 1.87%   |
| Micron Technology           | 10        | 10     | 1.7%    |
| A-DATA Technology           | 10        | 10     | 1.7%    |
| Transcend                   | 8         | 8      | 1.36%   |
| China                       | 8         | 8      | 1.36%   |
| Intel                       | 7         | 9      | 1.19%   |
| Hitachi                     | 7         | 10     | 1.19%   |
| KIOXIA                      | 5         | 5      | 0.85%   |
| Unknown                     | 5         | 5      | 0.85%   |
| Team                        | 4         | 6      | 0.68%   |
| SPCC                        | 4         | 4      | 0.68%   |
| PNY                         | 4         | 4      | 0.68%   |
| Patriot                     | 4         | 5      | 0.68%   |
| Kingston Technology Company | 4         | 4      | 0.68%   |
| Silicon Motion              | 3         | 3      | 0.51%   |
| Phison Electronics          | 3         | 4      | 0.51%   |
| Netac                       | 3         | 3      | 0.51%   |
| LITEON                      | 3         | 3      | 0.51%   |
| Intenso                     | 3         | 3      | 0.51%   |
| GOODRAM                     | 3         | 3      | 0.51%   |
| Gigabyte Technology         | 3         | 3      | 0.51%   |
| USB                         | 2         | 2      | 0.34%   |
| TO Exter                    | 2         | 2      | 0.34%   |
| ShiJi                       | 2         | 2      | 0.34%   |
| LITEONIT                    | 2         | 2      | 0.34%   |
| Lexar                       | 2         | 2      | 0.34%   |
| JMicron Technology          | 2         | 2      | 0.34%   |
| Hewlett-Packard             | 2         | 2      | 0.34%   |
| ASMT                        | 2         | 2      | 0.34%   |
| Apple                       | 2         | 3      | 0.34%   |
| XPG                         | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)

![Drive Model](./images/line_chart/drive_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| WDC WD5000AAKX-60U6AA0 500GB                        | 16        | 2.41%   |
| Seagate ST1000DM003-1ER162 1TB                      | 11        | 1.66%   |
| Samsung SSD 970 EVO Plus 1TB                        | 7         | 1.05%   |
| Samsung SSD 850 EVO 500GB                           | 7         | 1.05%   |
| Seagate ST1000DM010-2EP102 1TB                      | 5         | 0.75%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 256GB    | 5         | 0.75%   |
| Crucial CT500MX500SSD1 500GB                        | 5         | 0.75%   |
| Unknown                                             | 5         | 0.75%   |
| WDC WD40EFRX-68WT0N0 4TB                            | 4         | 0.6%    |
| Toshiba XG6 NVMe SSD Controller 256GB               | 4         | 0.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 4         | 0.6%    |
| Kingston SA400S37240G 240GB SSD                     | 4         | 0.6%    |
| Crucial CT480BX500SSD1 480GB                        | 4         | 0.6%    |
| A-DATA SU800 512GB SSD                              | 4         | 0.6%    |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 3         | 0.45%   |
| WDC WD40EFRX-68N32N0 4TB                            | 3         | 0.45%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 3         | 0.45%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                | 3         | 0.45%   |
| Toshiba MQ04ABF100 1TB                              | 3         | 0.45%   |
| Toshiba HDWQ140 4TB                                 | 3         | 0.45%   |
| Toshiba DT01ACA050 500GB                            | 3         | 0.45%   |
| SPCC Solid State Disk 128GB                         | 3         | 0.45%   |
| Seagate ST4000DM004-2CV104 4TB                      | 3         | 0.45%   |
| Seagate ST2000DM008-2FR102 2TB                      | 3         | 0.45%   |
| Samsung SSD 870 EVO 500GB                           | 3         | 0.45%   |
| Samsung SSD 860 EVO 1TB                             | 3         | 0.45%   |
| Samsung SSD 850 EVO 250GB                           | 3         | 0.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 3         | 0.45%   |
| Samsung MZVLQ256HBJD-00BH1 256GB                    | 3         | 0.45%   |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 3         | 0.45%   |
| Kingston SV300S37A120G 120GB SSD                    | 3         | 0.45%   |
| Kingston SA400S37120G 120GB SSD                     | 3         | 0.45%   |
| HGST HUS726T4TALA6L4 4TB                            | 3         | 0.45%   |
| Crucial CT1000MX500SSD1 1TB                         | 3         | 0.45%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                    | 2         | 0.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2         | 0.3%    |
| WDC WDS240G1G0A-00SS50 240GB SSD                    | 2         | 0.3%    |
| WDC WDS100T2G0A-00JH30 1TB SSD                      | 2         | 0.3%    |
| WDC WD5000AAKX-08ANVA0 500GB                        | 2         | 0.3%    |
| WDC WD40EZRZ-00GXCB0 4TB                            | 2         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 81        | 103    | 38.03%  |
| Seagate             | 71        | 161    | 33.33%  |
| Toshiba             | 27        | 32     | 12.68%  |
| HGST                | 14        | 17     | 6.57%   |
| Hitachi             | 7         | 10     | 3.29%   |
| Samsung Electronics | 4         | 4      | 1.88%   |
| Unknown             | 2         | 2      | 0.94%   |
| WD MediaMax         | 1         | 6      | 0.47%   |
| USB                 | 1         | 1      | 0.47%   |
| LaCie               | 1         | 1      | 0.47%   |
| HPE                 | 1         | 4      | 0.47%   |
| Fujitsu             | 1         | 1      | 0.47%   |
| External            | 1         | 1      | 0.47%   |
| DELLBOSS            | 1         | 1      | 0.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 49     | 18.32%  |
| WDC                 | 19        | 20     | 9.95%   |
| Kingston            | 19        | 20     | 9.95%   |
| Crucial             | 17        | 19     | 8.9%    |
| SanDisk             | 13        | 15     | 6.81%   |
| China               | 8         | 8      | 4.19%   |
| A-DATA Technology   | 7         | 7      | 3.66%   |
| Transcend           | 5         | 5      | 2.62%   |
| Team                | 4         | 4      | 2.09%   |
| SPCC                | 4         | 4      | 2.09%   |
| Intel               | 4         | 5      | 2.09%   |
| SK hynix            | 3         | 3      | 1.57%   |
| PNY                 | 3         | 3      | 1.57%   |
| Intenso             | 3         | 3      | 1.57%   |
| GOODRAM             | 3         | 3      | 1.57%   |
| Gigabyte Technology | 3         | 3      | 1.57%   |
| Toshiba             | 2         | 2      | 1.05%   |
| TO Exter            | 2         | 2      | 1.05%   |
| Patriot             | 2         | 3      | 1.05%   |
| Netac               | 2         | 2      | 1.05%   |
| LITEONIT            | 2         | 2      | 1.05%   |
| LITEON              | 2         | 2      | 1.05%   |
| JMicron Technology  | 2         | 2      | 1.05%   |
| ASMT                | 2         | 2      | 1.05%   |
| Unknown             | 2         | 2      | 1.05%   |
| TrekStor            | 1         | 1      | 0.52%   |
| Teclast             | 1         | 1      | 0.52%   |
| ShiJi               | 1         | 1      | 0.52%   |
| Ramsta              | 1         | 1      | 0.52%   |
| Plextor             | 1         | 1      | 0.52%   |
| Phison              | 1         | 1      | 0.52%   |
| OCZ                 | 1         | 1      | 0.52%   |
| NT-1TB              | 1         | 1      | 0.52%   |
| Mushkin             | 1         | 1      | 0.52%   |
| Micron Technology   | 1         | 1      | 0.52%   |
| Londisk             | 1         | 1      | 0.52%   |
| Lexar               | 1         | 1      | 0.52%   |
| Lenovo              | 1         | 1      | 0.52%   |
| LDLC                | 1         | 1      | 0.52%   |
| INNOVATION IT       | 1         | 1      | 0.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)

![Drive Kind](./images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 186       | 344    | 34.38%  |
| SSD     | 161       | 213    | 29.76%  |
| NVMe    | 158       | 180    | 29.21%  |
| MMC     | 30        | 32     | 5.55%   |
| Unknown | 6         | 9      | 1.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)

![Drive Connector](./images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 283       | 527    | 57.17%  |
| NVMe | 157       | 178    | 31.72%  |
| MMC  | 30        | 32     | 6.06%   |
| SAS  | 25        | 41     | 5.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)

![Drive Size](./images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 199       | 240    | 52.65%  |
| 0.51-1.0   | 100       | 121    | 26.46%  |
| 1.01-2.0   | 32        | 45     | 8.47%   |
| 3.01-4.0   | 24        | 95     | 6.35%   |
| 2.01-3.0   | 10        | 16     | 2.65%   |
| 4.01-10.0  | 10        | 37     | 2.65%   |
| 10.01-20.0 | 3         | 3      | 0.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)

![Space Total](./images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 95        | 22.78%  |
| 251-500        | 84        | 20.14%  |
| Unknown        | 71        | 17.03%  |
| 501-1000       | 55        | 13.19%  |
| More than 3000 | 30        | 7.19%   |
| 51-100         | 23        | 5.52%   |
| 1-20           | 18        | 4.32%   |
| 1001-2000      | 17        | 4.08%   |
| 2001-3000      | 14        | 3.36%   |
| 21-50          | 10        | 2.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)

![Space Used](./images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 140       | 33.57%  |
| Unknown        | 71        | 17.03%  |
| 21-50          | 47        | 11.27%  |
| 51-100         | 37        | 8.87%   |
| 101-250        | 36        | 8.63%   |
| 251-500        | 27        | 6.47%   |
| 501-1000       | 24        | 5.76%   |
| 1001-2000      | 20        | 4.8%    |
| More than 3000 | 9         | 2.16%   |
| 2001-3000      | 6         | 1.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart/drive_malfunc.svg)

| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB          | 12        | 12     | 17.14%  |
| WDC WD40EFRX-68WT0N0 4TB              | 3         | 5      | 4.29%   |
| Seagate ST3250410AS 250GB             | 2         | 2      | 2.86%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 2      | 2.86%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 2      | 1.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 1.43%   |
| WDC WD800AAJS-60WAA0 80GB             | 1         | 1      | 1.43%   |
| WDC WD40EFRX-68N32N0 4TB              | 1         | 1      | 1.43%   |
| WDC WD3200AAJS-00L7A0 320GB           | 1         | 1      | 1.43%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1         | 1      | 1.43%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1         | 1      | 1.43%   |
| WDC WD2500BEKT-00A25T0 250GB          | 1         | 1      | 1.43%   |
| WDC WD2500AAKS-00VSA0 250GB           | 1         | 1      | 1.43%   |
| WDC WD20PURX-64P6ZY0 2TB              | 1         | 1      | 1.43%   |
| WDC WD20EFRX-68AX9N0 2TB              | 1         | 1      | 1.43%   |
| WDC WD20EARS-00MVWB0 2TB              | 1         | 1      | 1.43%   |
| WDC WD1600BEVT-24A23T0 160GB          | 1         | 1      | 1.43%   |
| WDC WD10JPLX-00MBPT1 1TB              | 1         | 1      | 1.43%   |
| Toshiba XG4 NVMe SSD Controller 256GB | 1         | 1      | 1.43%   |
| Toshiba MQ01ACF032 320GB              | 1         | 1      | 1.43%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 1.43%   |
| Toshiba MQ01ABD100M 1TB               | 1         | 1      | 1.43%   |
| Toshiba MK6459GSXP 640GB              | 1         | 1      | 1.43%   |
| ShiJi 1TB                             | 1         | 1      | 1.43%   |
| Seagate ST980411ASG 80GB              | 1         | 1      | 1.43%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 1.43%   |
| Seagate ST9120822AS 120GB             | 1         | 1      | 1.43%   |
| Seagate ST8000VX0022-2EJ112 8TB       | 1         | 2      | 1.43%   |
| Seagate ST4000NM0035-1V4107 4TB       | 1         | 8      | 1.43%   |
| Seagate ST4000DM005-2DP166 4TB        | 1         | 2      | 1.43%   |
| Seagate ST3500312CS 500GB             | 1         | 1      | 1.43%   |
| Seagate ST3320418AS 320GB             | 1         | 1      | 1.43%   |
| Seagate ST3250310AS 250GB             | 1         | 1      | 1.43%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 1.43%   |
| Seagate ST3160815AS 160GB             | 1         | 1      | 1.43%   |
| Seagate ST31000528AS 1TB              | 1         | 1      | 1.43%   |
| Seagate ST2000LX001-1RG174 2TB        | 1         | 1      | 1.43%   |
| Seagate ST2000DM001-9YN164 2TB        | 1         | 1      | 1.43%   |
| Seagate ST10000NE0004-1ZF101 10TB     | 1         | 1      | 1.43%   |
| Samsung Electronics SSD 980 1TB       | 1         | 1      | 1.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart/drive_malfunc_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 27        | 32     | 40.3%   |
| Seagate             | 17        | 26     | 25.37%  |
| Toshiba             | 5         | 5      | 7.46%   |
| Samsung Electronics | 4         | 5      | 5.97%   |
| Kingston            | 4         | 4      | 5.97%   |
| A-DATA Technology   | 3         | 3      | 4.48%   |
| Hitachi             | 2         | 2      | 2.99%   |
| ShiJi               | 1         | 1      | 1.49%   |
| Intenso             | 1         | 1      | 1.49%   |
| Intel               | 1         | 1      | 1.49%   |
| HGST                | 1         | 1      | 1.49%   |
| Crucial             | 1         | 1      | 1.49%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 25        | 29     | 50%     |
| Seagate             | 17        | 26     | 34%     |
| Toshiba             | 4         | 4      | 8%      |
| Hitachi             | 2         | 2      | 4%      |
| Samsung Electronics | 1         | 1      | 2%      |
| HGST                | 1         | 1      | 2%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 50        | 63     | 74.63%  |
| SSD  | 13        | 14     | 19.4%   |
| NVMe | 4         | 5      | 5.97%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)

![Failed Drives](./images/line_chart/drive_failed.svg)

| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| Toshiba MQ04ABF100 1TB                      | 1         | 1      | 25%     |
| Samsung Electronics SSD PM871 2.5 7mm 128GB | 1         | 1      | 25%     |
| Samsung Electronics HD103SJ 1TB             | 1         | 1      | 25%     |
| Intel SSDSC2KW256G8 256GB                   | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)

![Failed Drive Vendor](./images/line_chart/drive_failed_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 50%     |
| Toshiba             | 1         | 1      | 25%     |
| Intel               | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)

![Drive Status](./images/line_chart/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 279       | 511    | 60.65%  |
| Detected | 111       | 181    | 24.13%  |
| Malfunc  | 66        | 82     | 14.35%  |
| Failed   | 4         | 4      | 0.87%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)

![Storage Vendor](./images/line_chart/storage_vendor.svg)

| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 271       | 50.37%  |
| AMD                              | 58        | 10.78%  |
| Samsung Electronics              | 54        | 10.04%  |
| SanDisk                          | 27        | 5.02%   |
| ASMedia Technology               | 15        | 2.79%   |
| Toshiba America Info Systems     | 10        | 1.86%   |
| Kingston Technology Company      | 10        | 1.86%   |
| Micron Technology                | 9         | 1.67%   |
| SK hynix                         | 8         | 1.49%   |
| Phison Electronics               | 7         | 1.3%    |
| Micron/Crucial Technology        | 7         | 1.3%    |
| JMicron Technology               | 7         | 1.3%    |
| Nvidia                           | 6         | 1.12%   |
| Marvell Technology Group         | 6         | 1.12%   |
| Silicon Motion                   | 5         | 0.93%   |
| ADATA Technology                 | 5         | 0.93%   |
| Adaptec                          | 5         | 0.93%   |
| Broadcom / LSI                   | 4         | 0.74%   |
| Transcend                        | 3         | 0.56%   |
| KIOXIA                           | 3         | 0.56%   |
| VIA Technologies                 | 2         | 0.37%   |
| Seagate Technology               | 2         | 0.37%   |
| Realtek Semiconductor            | 2         | 0.37%   |
| Apple                            | 2         | 0.37%   |
| Union Memory (Shenzhen)          | 1         | 0.19%   |
| Solid State Storage Technology   | 1         | 0.19%   |
| Silicon Integrated Systems [SiS] | 1         | 0.19%   |
| Shenzhen Longsys Electronics     | 1         | 0.19%   |
| Nextorage                        | 1         | 0.19%   |
| Netac Technology                 | 1         | 0.19%   |
| LSI Logic / Symbios Logic        | 1         | 0.19%   |
| Lite-On Technology               | 1         | 0.19%   |
| INNOGRIT                         | 1         | 0.19%   |
| Biwin Storage Technology         | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)

![Storage Model](./images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 40        | 6.6%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 35        | 5.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 22        | 3.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 20        | 3.3%    |
| Samsung NVMe SSD Controller 980                                                | 14        | 2.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 14        | 2.31%   |
| Intel Volume Management Device NVMe RAID Controller                            | 13        | 2.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 13        | 2.15%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 13        | 2.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 11        | 1.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 11        | 1.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 11        | 1.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 1.65%   |
| AMD 400 Series Chipset SATA Controller                                         | 10        | 1.65%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 9         | 1.49%   |
| AMD 500 Series Chipset SATA Controller                                         | 9         | 1.49%   |
| Micron NVMe Storage Controller                                                 | 8         | 1.32%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 8         | 1.32%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 8         | 1.32%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 8         | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 8         | 1.32%   |
| Intel Tiger Lake-LP SATA Controller                                            | 7         | 1.16%   |
| Intel SATA Controller [RAID mode]                                              | 7         | 1.16%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 7         | 1.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 1.16%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 6         | 0.99%   |
| Sandisk Non-Volatile memory controller                                         | 6         | 0.99%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 0.99%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 0.83%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 5         | 0.83%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 5         | 0.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 0.83%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 5         | 0.83%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 5         | 0.83%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                           | 5         | 0.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 0.83%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 0.83%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 4         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)

![Storage Kind](./images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 287       | 53.95%  |
| NVMe | 157       | 29.51%  |
| IDE  | 40        | 7.52%   |
| RAID | 39        | 7.33%   |
| SAS  | 7         | 1.32%   |
| SCSI | 2         | 0.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./images/line_chart/cpu_vendor.svg)

| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 319       | 76.5%   |
| AMD           | 78        | 18.71%  |
| ARM           | 15        | 3.6%    |
| sifive,u74-mc | 2         | 0.48%   |
| Qualcomm      | 1         | 0.24%   |
| Phytium       | 1         | 0.24%   |
| Unknown       | 1         | 0.24%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)

![CPU Model](./images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium CPU G3420 @ 3.20GHz             | 15        | 3.6%    |
| ARM Processor                                 | 13        | 3.12%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 8         | 1.92%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 1.92%   |
| Intel 12th Gen Core i5-1235U                  | 6         | 1.44%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 6         | 1.44%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 1.2%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 1.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 0.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.96%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 4         | 0.96%   |
| Intel Celeron N4120 CPU @ 1.10GHz             | 4         | 0.96%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 3         | 0.72%   |
| Intel Core i7 CPU M 640 @ 2.80GHz             | 3         | 0.72%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 0.72%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 3         | 0.72%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 0.72%   |
| Intel 12th Gen Core i7-1255U                  | 3         | 0.72%   |
| Intel 12th Gen Core i5-12600K                 | 3         | 0.72%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 3         | 0.72%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 0.72%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.72%   |
| sifive,u74-mc rv64imafdc                      | 2         | 0.48%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz           | 2         | 0.48%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 2         | 0.48%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.48%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.48%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.48%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.48%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 2         | 0.48%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 2         | 0.48%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 2         | 0.48%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 2         | 0.48%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 2         | 0.48%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.48%   |
| Intel Core i5-4278U CPU @ 2.60GHz             | 2         | 0.48%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.48%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 0.48%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.48%   |
| Intel Core i5-2300 CPU @ 2.80GHz              | 2         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)

![CPU Model Family](./images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 79        | 18.94%  |
| Other                   | 72        | 17.27%  |
| Intel Core i7           | 52        | 12.47%  |
| Intel Core i3           | 31        | 7.43%   |
| Intel Celeron           | 27        | 6.47%   |
| Intel Pentium           | 23        | 5.52%   |
| AMD Ryzen 7             | 20        | 4.8%    |
| Intel Xeon              | 19        | 4.56%   |
| AMD Ryzen 5             | 16        | 3.84%   |
| Intel Core 2 Duo        | 11        | 2.64%   |
| AMD Ryzen 9             | 11        | 2.64%   |
| Intel Atom              | 7         | 1.68%   |
| Intel Pentium Dual-Core | 6         | 1.44%   |
| AMD Ryzen 5 PRO         | 4         | 0.96%   |
| AMD FX                  | 4         | 0.96%   |
| AMD A6                  | 4         | 0.96%   |
| AMD E                   | 3         | 0.72%   |
| AMD Athlon 64 X2        | 3         | 0.72%   |
| Intel Xeon Silver       | 2         | 0.48%   |
| Intel Core m3           | 2         | 0.48%   |
| AMD Ryzen 3             | 2         | 0.48%   |
| AMD Athlon II X3        | 2         | 0.48%   |
| Intel Xeon Gold         | 1         | 0.24%   |
| Intel Genuine           | 1         | 0.24%   |
| Intel Core m7           | 1         | 0.24%   |
| Intel Core i9           | 1         | 0.24%   |
| Intel Core Duo          | 1         | 0.24%   |
| Intel Core 2 Quad       | 1         | 0.24%   |
| ARM BCM                 | 1         | 0.24%   |
| ARM Allwinner           | 1         | 0.24%   |
| AMD Ryzen 3 PRO         | 1         | 0.24%   |
| AMD Quad-Core Opteron   | 1         | 0.24%   |
| AMD GX                  | 1         | 0.24%   |
| AMD G                   | 1         | 0.24%   |
| AMD E1                  | 1         | 0.24%   |
| AMD Athlon II X4        | 1         | 0.24%   |
| AMD A8                  | 1         | 0.24%   |
| AMD A4                  | 1         | 0.24%   |
| AMD A10                 | 1         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)

![CPU Cores](./images/line_chart/cpu_cores.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 149       | 35.73%  |
| 4       | 134       | 32.13%  |
| 6       | 40        | 9.59%   |
| 8       | 34        | 8.15%   |
| 10      | 16        | 3.84%   |
| 12      | 12        | 2.88%   |
| 1       | 8         | 1.92%   |
| 24      | 7         | 1.68%   |
| Unknown | 5         | 1.2%    |
| 16      | 4         | 0.96%   |
| 3       | 4         | 0.96%   |
| 14      | 3         | 0.72%   |
| 32      | 1         | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./images/line_chart/cpu_sockets.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 397       | 95.2%   |
| 2       | 12        | 2.88%   |
| Unknown | 5         | 1.2%    |
| 3       | 2         | 0.48%   |
| 0       | 1         | 0.24%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)

![CPU Threads](./images/line_chart/cpu_threads.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 264       | 63.31%  |
| 1       | 148       | 35.49%  |
| Unknown | 5         | 1.2%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 410       | 98.32%  |
| Unknown        | 5         | 1.2%    |
| 32-bit         | 2         | 0.48%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 88        | 21.1%   |
| 0x306c3    | 42        | 10.07%  |
| 0x806c1    | 18        | 4.32%   |
| 0x206a7    | 14        | 3.36%   |
| 0x306a9    | 13        | 3.12%   |
| 0x1067a    | 12        | 2.88%   |
| 0x906a4    | 11        | 2.64%   |
| 0x806e9    | 11        | 2.64%   |
| 0x506e3    | 9         | 2.16%   |
| 0x406e3    | 9         | 2.16%   |
| 0x90672    | 8         | 1.92%   |
| 0x806ec    | 8         | 1.92%   |
| 0x906ea    | 7         | 1.68%   |
| 0x906e9    | 7         | 1.68%   |
| 0x906c0    | 6         | 1.44%   |
| 0x0a20120a | 6         | 1.44%   |
| 0xa0653    | 5         | 1.2%    |
| 0x806ea    | 5         | 1.2%    |
| 0x306f2    | 5         | 1.2%    |
| 0x0a50000c | 5         | 1.2%    |
| 0x906ed    | 4         | 0.96%   |
| 0x906eb    | 4         | 0.96%   |
| 0x706a8    | 4         | 0.96%   |
| 0x40651    | 4         | 0.96%   |
| 0x306d4    | 4         | 0.96%   |
| 0x106ca    | 4         | 0.96%   |
| 0x08701021 | 4         | 0.96%   |
| 0x08600106 | 4         | 0.96%   |
| 0xa0652    | 3         | 0.72%   |
| 0x906a3    | 3         | 0.72%   |
| 0x706a1    | 3         | 0.72%   |
| 0x6fb      | 3         | 0.72%   |
| 0x206d7    | 3         | 0.72%   |
| 0x206c2    | 3         | 0.72%   |
| 0x20655    | 3         | 0.72%   |
| 0x0a50000d | 3         | 0.72%   |
| 0x0a404102 | 3         | 0.72%   |
| 0x08108109 | 3         | 0.72%   |
| 0x90675    | 2         | 0.48%   |
| 0x806c2    | 2         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./images/line_chart/cpu_microarch.svg)

| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 61        | 14.63%  |
| KabyLake         | 59        | 14.15%  |
| Unknown          | 40        | 9.59%   |
| Skylake          | 24        | 5.76%   |
| TigerLake        | 21        | 5.04%   |
| Zen 3            | 20        | 4.8%    |
| SandyBridge      | 20        | 4.8%    |
| IvyBridge        | 20        | 4.8%    |
| Alderlake Hybrid | 19        | 4.56%   |
| Zen 2            | 14        | 3.36%   |
| Penryn           | 14        | 3.36%   |
| Westmere         | 13        | 3.12%   |
| CometLake        | 11        | 2.64%   |
| Zen+             | 8         | 1.92%   |
| Goldmont plus    | 8         | 1.92%   |
| Tremont          | 7         | 1.68%   |
| Piledriver       | 6         | 1.44%   |
| Core             | 6         | 1.44%   |
| Broadwell        | 6         | 1.44%   |
| Zen              | 5         | 1.2%    |
| Silvermont       | 4         | 0.96%   |
| K10              | 4         | 0.96%   |
| Bonnell          | 4         | 0.96%   |
| Bobcat           | 4         | 0.96%   |
| Nehalem          | 3         | 0.72%   |
| K8 Hammer        | 3         | 0.72%   |
| Jaguar           | 3         | 0.72%   |
| Excavator        | 3         | 0.72%   |
| Icelake          | 2         | 0.48%   |
| Goldmont         | 2         | 0.48%   |
| P6               | 1         | 0.24%   |
| NetBurst         | 1         | 0.24%   |
| Bulldozer        | 1         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./images/line_chart/gpu_vendor.svg)

| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 244       | 55.84%  |
| Nvidia                           | 97        | 22.2%   |
| AMD                              | 81        | 18.54%  |
| Matrox Electronics Systems       | 8         | 1.83%   |
| ASPEED Technology                | 6         | 1.37%   |
| Silicon Integrated Systems [SiS] | 1         | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)

![GPU Model](./images/line_chart/gpu_model.svg)

| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 20        | 4.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 15        | 3.39%   |
| Nvidia GF108 [GeForce GT 730]                                               | 14        | 3.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 14        | 3.17%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 14        | 3.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 12        | 2.71%   |
| Intel HD Graphics 630                                                       | 10        | 2.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 10        | 2.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 9         | 2.04%   |
| Intel HD Graphics 620                                                       | 9         | 2.04%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 9         | 2.04%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 8         | 1.81%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 8         | 1.81%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 8         | 1.81%   |
| Intel Core Processor Integrated Graphics Controller                         | 7         | 1.58%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 7         | 1.58%   |
| Intel UHD Graphics 620                                                      | 6         | 1.36%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                   | 6         | 1.36%   |
| Intel JasperLake [UHD Graphics]                                             | 6         | 1.36%   |
| ASPEED Technology ASPEED Graphics Family                                    | 6         | 1.36%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6         | 1.36%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 5         | 1.13%   |
| Intel HD Graphics 530                                                       | 5         | 1.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 5         | 1.13%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 5         | 1.13%   |
| Intel AlderLake-S GT1                                                       | 5         | 1.13%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5         | 1.13%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4         | 0.9%    |
| Nvidia GK208B [GeForce GT 710]                                              | 4         | 0.9%    |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 4         | 0.9%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 4         | 0.9%    |
| Intel Alder Lake-P Integrated Graphics Controller                           | 4         | 0.9%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 0.9%    |
| AMD Renoir                                                                  | 4         | 0.9%    |
| Nvidia GP108M [GeForce MX250]                                               | 3         | 0.68%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3         | 0.68%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 3         | 0.68%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 0.68%   |
| Intel HD Graphics 5500                                                      | 3         | 0.68%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)

![GPU Combo](./images/line_chart/gpu_combo.svg)

| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 210       | 50.36%  |
| 1 x AMD         | 72        | 17.27%  |
| 1 x Nvidia      | 61        | 14.63%  |
| Intel + Nvidia  | 30        | 7.19%   |
| Other           | 21        | 5.04%   |
| 1 x Matrox      | 8         | 1.92%   |
| 1 x ASPEED      | 4         | 0.96%   |
| AMD + Nvidia    | 4         | 0.96%   |
| 2 x AMD         | 2         | 0.48%   |
| Intel + AMD     | 2         | 0.48%   |
| 1 x SiS         | 1         | 0.24%   |
| Nvidia + ASPEED | 1         | 0.24%   |
| AMD + ASPEED    | 1         | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)

![GPU Driver](./images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 284       | 68.11%  |
| Unknown     | 106       | 25.42%  |
| Proprietary | 27        | 6.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)

![GPU Memory](./images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 324       | 77.7%   |
| 0.01-0.5   | 22        | 5.28%   |
| 1.01-2.0   | 18        | 4.32%   |
| 7.01-8.0   | 16        | 3.84%   |
| 3.01-4.0   | 14        | 3.36%   |
| 0.51-1.0   | 13        | 3.12%   |
| 8.01-16.0  | 5         | 1.2%    |
| 2.01-3.0   | 3         | 0.72%   |
| 5.01-6.0   | 2         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 35        | 10.61%  |
| AU Optronics            | 35        | 10.61%  |
| Chimei Innolux          | 31        | 9.39%   |
| LG Display              | 28        | 8.48%   |
| BOE                     | 26        | 7.88%   |
| Dell                    | 22        | 6.67%   |
| Goldstar                | 18        | 5.45%   |
| Hewlett-Packard         | 14        | 4.24%   |
| Lenovo                  | 12        | 3.64%   |
| BenQ                    | 12        | 3.64%   |
| AOC                     | 10        | 3.03%   |
| Sharp                   | 8         | 2.42%   |
| Philips                 | 7         | 2.12%   |
| Ancor Communications    | 7         | 2.12%   |
| Acer                    | 6         | 1.82%   |
| ViewSonic               | 5         | 1.52%   |
| PANDA                   | 4         | 1.21%   |
| NEC Computers           | 4         | 1.21%   |
| InfoVision              | 3         | 0.91%   |
| CSO                     | 3         | 0.91%   |
| Chi Mei Optoelectronics | 3         | 0.91%   |
| Apple                   | 3         | 0.91%   |
| Sony                    | 2         | 0.61%   |
| Plain Tree Systems      | 2         | 0.61%   |
| Medion                  | 2         | 0.61%   |
| Iiyama                  | 2         | 0.61%   |
| HannStar                | 2         | 0.61%   |
| ASUSTek Computer        | 2         | 0.61%   |
| Unknown                 | 2         | 0.61%   |
| ___                     | 1         | 0.3%    |
| YSD                     | 1         | 0.3%    |
| Vizio                   | 1         | 0.3%    |
| Unknown                 | 1         | 0.3%    |
| SKY                     | 1         | 0.3%    |
| Sceptre Tech            | 1         | 0.3%    |
| PCT                     | 1         | 0.3%    |
| Panasonic               | 1         | 0.3%    |
| Packard Bell            | 1         | 0.3%    |
| MSI                     | 1         | 0.3%    |
| LG Philips              | 1         | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)

![Monitor Model](./images/line_chart/mon_model.svg)

| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 7         | 2.1%    |
| AU Optronics LCD Monitor AUO332C 1366x768 293x165mm 13.2-inch        | 4         | 1.2%    |
| Chimei Innolux LCD Monitor CMN13C6 1920x1200 286x178mm 13.3-inch     | 3         | 0.9%    |
| BenQ PD2700U BNQ802E 3840x2160 597x336mm 27.0-inch                   | 3         | 0.9%    |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch               | 2         | 0.6%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 2         | 0.6%    |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch    | 2         | 0.6%    |
| Samsung Electronics S20B350 SAM0916 1600x900 443x249mm 20.0-inch     | 2         | 0.6%    |
| Plain Tree Systems Monitor PTS06A5 1280x1024 337x270mm 17.0-inch     | 2         | 0.6%    |
| NEC Computers LCD1770NX NEC6664 1280x1024 338x270mm 17.0-inch        | 2         | 0.6%    |
| LG Display LCD Monitor LGD03F1 1600x900 309x174mm 14.0-inch          | 2         | 0.6%    |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch          | 2         | 0.6%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.6%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 2         | 0.6%    |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch              | 2         | 0.6%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 2         | 0.6%    |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                    | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch      | 2         | 0.6%    |
| BOE LCD Monitor BOE081D 1920x1080 309x174mm 14.0-inch                | 2         | 0.6%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 2         | 0.6%    |
| BenQ BenQG2222HDL BNQ785A 1920x1080 478x269mm 21.6-inch              | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch       | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO559C 1920x1080 309x174mm 14.0-inch       | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch       | 2         | 0.6%    |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                     | 2         | 0.6%    |
| Unknown                                                              | 2         | 0.6%    |
| ___ VG500b ___B40A 1024x768 300x230mm 14.9-inch                      | 1         | 0.3%    |
| YSD HDMI YSD0190 1440x900 368x207mm 16.6-inch                        | 1         | 0.3%    |
| Vizio E231-B1 VIZ0095 1360x768 534x311mm 24.3-inch                   | 1         | 0.3%    |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch               | 1         | 0.3%    |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch        | 1         | 0.3%    |
| ViewSonic VA2719 Series VSCC132 1920x1080 598x336mm 27.0-inch        | 1         | 0.3%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1         | 0.3%    |
| Sony TV SNY4803 1920x1080 930x520mm 41.9-inch                        | 1         | 0.3%    |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch | 1         | 0.3%    |
| SKY TV-monitor SKY1801 3840x2160 708x398mm 32.0-inch                 | 1         | 0.3%    |
| Sharp LCD Monitor SHP1548 1920x1200 288x180mm 13.4-inch              | 1         | 0.3%    |
| Sharp LCD Monitor SHP14CB 1920x1200 290x180mm 13.4-inch              | 1         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 152       | 47.95%  |
| 1366x768 (WXGA)    | 50        | 15.77%  |
| 1920x1200 (WUXGA)  | 16        | 5.05%   |
| 1280x1024 (SXGA)   | 16        | 5.05%   |
| 1600x900 (HD+)     | 15        | 4.73%   |
| 3840x2160 (4K)     | 14        | 4.42%   |
| 2560x1440 (QHD)    | 13        | 4.1%    |
| 1680x1050 (WSXGA+) | 5         | 1.58%   |
| 1440x900 (WXGA+)   | 4         | 1.26%   |
| 1280x800 (WXGA)    | 4         | 1.26%   |
| 2560x1600          | 3         | 0.95%   |
| 2560x1080          | 3         | 0.95%   |
| 1024x768 (XGA)     | 3         | 0.95%   |
| 3840x1600          | 2         | 0.63%   |
| 3440x1440          | 2         | 0.63%   |
| 3000x2000          | 2         | 0.63%   |
| 2160x1440          | 2         | 0.63%   |
| 1024x600           | 2         | 0.63%   |
| 7280x2160          | 1         | 0.32%   |
| 3840x2400          | 1         | 0.32%   |
| 3072x1920          | 1         | 0.32%   |
| 2736x1824          | 1         | 0.32%   |
| 2304x1440          | 1         | 0.32%   |
| 2288x1287          | 1         | 0.32%   |
| 1600x1200          | 1         | 0.32%   |
| 1360x768           | 1         | 0.32%   |
| Unknown            | 1         | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 67        | 20.49%  |
| 13      | 49        | 14.98%  |
| 14      | 32        | 9.79%   |
| 27      | 30        | 9.17%   |
| 24      | 30        | 9.17%   |
| 17      | 19        | 5.81%   |
| 21      | 17        | 5.2%    |
| 23      | 15        | 4.59%   |
| 12      | 9         | 2.75%   |
| 31      | 8         | 2.45%   |
| Unknown | 8         | 2.45%   |
| 20      | 6         | 1.83%   |
| 11      | 6         | 1.83%   |
| 22      | 5         | 1.53%   |
| 19      | 5         | 1.53%   |
| 34      | 4         | 1.22%   |
| 18      | 3         | 0.92%   |
| 37      | 2         | 0.61%   |
| 16      | 2         | 0.61%   |
| 10      | 2         | 0.61%   |
| 142     | 1         | 0.31%   |
| 72      | 1         | 0.31%   |
| 65      | 1         | 0.31%   |
| 60      | 1         | 0.31%   |
| 54      | 1         | 0.31%   |
| 32      | 1         | 0.31%   |
| 29      | 1         | 0.31%   |
| 28      | 1         | 0.31%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)

![Monitor Width](./images/line_chart/mon_width.svg)

| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 133       | 41.43%  |
| 501-600        | 65        | 20.25%  |
| 201-300        | 42        | 13.08%  |
| 401-500        | 33        | 10.28%  |
| 601-700        | 15        | 4.67%   |
| 351-400        | 13        | 4.05%   |
| Unknown        | 8         | 2.49%   |
| 701-800        | 5         | 1.56%   |
| 1001-1500      | 3         | 0.93%   |
| 801-900        | 2         | 0.62%   |
| More than 2000 | 1         | 0.31%   |
| 1501-2000      | 1         | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 229       | 75.33%  |
| 16/10   | 36        | 11.84%  |
| 5/4     | 15        | 4.93%   |
| 3/2     | 6         | 1.97%   |
| 21/9    | 6         | 1.97%   |
| 4/3     | 5         | 1.64%   |
| Unknown | 5         | 1.64%   |
| 6/5     | 1         | 0.33%   |
| 1.00    | 1         | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)

![Monitor Area](./images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 67        | 20.74%  |
| 81-90          | 58        | 17.96%  |
| 201-250        | 49        | 15.17%  |
| 301-350        | 30        | 9.29%   |
| 71-80          | 24        | 7.43%   |
| 351-500        | 15        | 4.64%   |
| 141-150        | 15        | 4.64%   |
| 151-200        | 14        | 4.33%   |
| 251-300        | 12        | 3.72%   |
| Unknown        | 8         | 2.48%   |
| 61-70          | 7         | 2.17%   |
| 51-60          | 6         | 1.86%   |
| 121-130        | 6         | 1.86%   |
| More than 1000 | 5         | 1.55%   |
| 41-50          | 2         | 0.62%   |
| 111-120        | 2         | 0.62%   |
| 501-1000       | 2         | 0.62%   |
| 131-140        | 1         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)

![Pixel Density](./images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 97        | 30.7%   |
| 121-160       | 94        | 29.75%  |
| 101-120       | 75        | 23.73%  |
| 161-240       | 30        | 9.49%   |
| Unknown       | 8         | 2.53%   |
| 1-50          | 7         | 2.22%   |
| More than 240 | 5         | 1.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)

![Multiple Monitors](./images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 255       | 61.15%  |
| 0     | 118       | 28.3%   |
| 2     | 37        | 8.87%   |
| 3     | 7         | 1.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./images/line_chart/net_vendor.svg)

| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 216       | 37.24%  |
| Realtek Semiconductor             | 208       | 35.86%  |
| Qualcomm Atheros                  | 43        | 7.41%   |
| Broadcom                          | 27        | 4.66%   |
| MediaTek                          | 14        | 2.41%   |
| ASIX Electronics                  | 8         | 1.38%   |
| Xiaomi                            | 6         | 1.03%   |
| Nvidia                            | 6         | 1.03%   |
| Broadcom Limited                  | 5         | 0.86%   |
| Standard Microsystems             | 3         | 0.52%   |
| Microsoft                         | 3         | 0.52%   |
| Marvell Technology Group          | 3         | 0.52%   |
| TP-Link                           | 2         | 0.34%   |
| Sierra Wireless                   | 2         | 0.34%   |
| Ralink                            | 2         | 0.34%   |
| QinHeng Electronics               | 2         | 0.34%   |
| Edimax Technology                 | 2         | 0.34%   |
| Dell                              | 2         | 0.34%   |
| U-Blox                            | 1         | 0.17%   |
| Spreadtrum Communications         | 1         | 0.17%   |
| Sigma Designs                     | 1         | 0.17%   |
| Samsung Electronics               | 1         | 0.17%   |
| Ralink Technology                 | 1         | 0.17%   |
| PCTel                             | 1         | 0.17%   |
| OpenMoko                          | 1         | 0.17%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.17%   |
| Microchip Technology              | 1         | 0.17%   |
| Manta                             | 1         | 0.17%   |
| Lenovo                            | 1         | 0.17%   |
| Lakeview Research                 | 1         | 0.17%   |
| JMicron Technology                | 1         | 0.17%   |
| Huawei Technologies               | 1         | 0.17%   |
| Hewlett-Packard                   | 1         | 0.17%   |
| Gemtek                            | 1         | 0.17%   |
| Fujitsu                           | 1         | 0.17%   |
| Ericsson Business Mobile Networks | 1         | 0.17%   |
| Encore Electronics                | 1         | 0.17%   |
| Emulex                            | 1         | 0.17%   |
| ASUSTek Computer                  | 1         | 0.17%   |
| Aquantia                          | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)

![Net Controller Model](./images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 142       | 20.2%   |
| Realtek RTL8125 2.5GbE Controller                                 | 19        | 2.7%    |
| Intel Wi-Fi 6 AX201                                               | 15        | 2.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 1.99%   |
| Intel Wi-Fi 6 AX200                                               | 14        | 1.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 1.85%   |
| Intel Wireless 8265 / 8275                                        | 12        | 1.71%   |
| Intel I211 Gigabit Network Connection                             | 12        | 1.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 12        | 1.71%   |
| Intel Ethernet Connection (13) I219-V                             | 11        | 1.56%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 1.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 1.28%   |
| Intel Wireless 7260                                               | 9         | 1.28%   |
| Intel Ethernet Controller I225-V                                  | 9         | 1.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 1.28%   |
| Intel Wireless 8260                                               | 8         | 1.14%   |
| Intel Ethernet Connection (2) I219-V                              | 8         | 1.14%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 1.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1%      |
| Intel I350 Gigabit Network Connection                             | 7         | 1%      |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 7         | 1%      |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 6         | 0.85%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 6         | 0.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5         | 0.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 0.71%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 0.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 0.71%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.57%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 4         | 0.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 0.57%   |
| Realtek 802.11ac NIC                                              | 4         | 0.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 4         | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.57%   |
| Nvidia MCP61 Ethernet                                             | 4         | 0.57%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 4         | 0.57%   |
| Intel Wireless-AC 9260                                            | 4         | 0.57%   |
| Intel Wireless 7265                                               | 4         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart/net_wireless_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 141       | 51.65%  |
| Realtek Semiconductor    | 54        | 19.78%  |
| Qualcomm Atheros         | 30        | 10.99%  |
| MediaTek                 | 14        | 5.13%   |
| Broadcom                 | 14        | 5.13%   |
| Broadcom Limited         | 3         | 1.1%    |
| TP-Link                  | 2         | 0.73%   |
| Sierra Wireless          | 2         | 0.73%   |
| Ralink                   | 2         | 0.73%   |
| Marvell Technology Group | 2         | 0.73%   |
| Edimax Technology        | 2         | 0.73%   |
| Ralink Technology        | 1         | 0.37%   |
| Microsoft                | 1         | 0.37%   |
| Hewlett-Packard          | 1         | 0.37%   |
| Gemtek                   | 1         | 0.37%   |
| Encore Electronics       | 1         | 0.37%   |
| Dell                     | 1         | 0.37%   |
| ASUSTek Computer         | 1         | 0.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)

![Wireless Model](./images/line_chart/net_wireless_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 15        | 5.47%   |
| Intel Wi-Fi 6 AX200                                            | 14        | 5.11%   |
| Intel Wireless 8265 / 8275                                     | 12        | 4.38%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 12        | 4.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 3.28%   |
| Intel Wireless 7260                                            | 9         | 3.28%   |
| Intel Wireless 8260                                            | 8         | 2.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 2.55%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 7         | 2.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 6         | 2.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 6         | 2.19%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 5         | 1.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 5         | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 1.82%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 4         | 1.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 1.46%   |
| Realtek 802.11ac NIC                                           | 4         | 1.46%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 4         | 1.46%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 4         | 1.46%   |
| Intel Wireless-AC 9260                                         | 4         | 1.46%   |
| Intel Wireless 7265                                            | 4         | 1.46%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 1.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 1.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 1.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 1.09%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 1.09%   |
| Intel Wireless 3165                                            | 3         | 1.09%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 1.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 1.09%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.09%   |
| Sierra Wireless EM7455                                         | 2         | 0.73%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2         | 0.73%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.73%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.73%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart/net_ethernet_vendor.svg)

| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 187       | 46.87%  |
| Intel                     | 141       | 35.34%  |
| Qualcomm Atheros          | 18        | 4.51%   |
| Broadcom                  | 15        | 3.76%   |
| ASIX Electronics          | 8         | 2.01%   |
| Xiaomi                    | 6         | 1.5%    |
| Nvidia                    | 6         | 1.5%    |
| Standard Microsystems     | 3         | 0.75%   |
| Broadcom Limited          | 2         | 0.5%    |
| Spreadtrum Communications | 1         | 0.25%   |
| Samsung Electronics       | 1         | 0.25%   |
| Microsoft                 | 1         | 0.25%   |
| Microchip Technology      | 1         | 0.25%   |
| Marvell Technology Group  | 1         | 0.25%   |
| Lenovo                    | 1         | 0.25%   |
| JMicron Technology        | 1         | 0.25%   |
| Emulex                    | 1         | 0.25%   |
| Dell                      | 1         | 0.25%   |
| Aquantia                  | 1         | 0.25%   |
| Apple                     | 1         | 0.25%   |
| American Megatrends       | 1         | 0.25%   |
| 3Com                      | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart/net_ethernet_model.svg)

| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 142       | 34.22%  |
| Realtek RTL8125 2.5GbE Controller                                             | 19        | 4.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 14        | 3.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 13        | 3.13%   |
| Intel I211 Gigabit Network Connection                                         | 12        | 2.89%   |
| Intel Ethernet Connection (13) I219-V                                         | 11        | 2.65%   |
| Intel Ethernet Connection I217-LM                                             | 10        | 2.41%   |
| Intel Ethernet Controller I225-V                                              | 9         | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9         | 2.17%   |
| Intel Ethernet Connection (2) I219-V                                          | 8         | 1.93%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 8         | 1.93%   |
| Intel I350 Gigabit Network Connection                                         | 7         | 1.69%   |
| Intel Ethernet Connection I219-LM                                             | 6         | 1.45%   |
| Intel Ethernet Connection (4) I219-V                                          | 5         | 1.2%    |
| Intel 82579V Gigabit Network Connection                                       | 5         | 1.2%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 4         | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 4         | 0.96%   |
| Nvidia MCP61 Ethernet                                                         | 4         | 0.96%   |
| Intel Ethernet Connection (7) I219-LM                                         | 4         | 0.96%   |
| Intel 82577LM Gigabit Network Connection                                      | 4         | 0.96%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 4         | 0.96%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 4         | 0.96%   |
| Standard Microsystems Ethernet controller                                     | 3         | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 3         | 0.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 3         | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 3         | 0.72%   |
| Intel Ethernet Connection I217-V                                              | 3         | 0.72%   |
| Intel Ethernet Connection (7) I219-V                                          | 3         | 0.72%   |
| Intel Ethernet Connection (4) I219-LM                                         | 3         | 0.72%   |
| Intel 82576 Gigabit Network Connection                                        | 3         | 0.72%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 2         | 0.48%   |
| Nvidia MCP65 Ethernet                                                         | 2         | 0.48%   |
| Intel I210 Gigabit Network Connection                                         | 2         | 0.48%   |
| Intel Ethernet Controller X550                                                | 2         | 0.48%   |
| Intel Ethernet Connection I218-LM                                             | 2         | 0.48%   |
| Intel Ethernet Connection (6) I219-V                                          | 2         | 0.48%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2         | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2         | 0.48%   |
| Intel Ethernet Connection (17) I219-LM                                        | 2         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)

![Net Controller Kind](./images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 366       | 57.55%  |
| WiFi     | 256       | 40.25%  |
| Modem    | 10        | 1.57%   |
| Unknown  | 4         | 0.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)

![Used Controller](./images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 247       | 61.9%   |
| WiFi     | 152       | 38.1%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)

![NICs](./images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 190       | 45.56%  |
| 1     | 180       | 43.17%  |
| 0     | 21        | 5.04%   |
| 3     | 9         | 2.16%   |
| 4     | 6         | 1.44%   |
| 7     | 5         | 1.2%    |
| 6     | 3         | 0.72%   |
| 8     | 2         | 0.48%   |
| 9     | 1         | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)

![IPv6](./images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 304       | 72.9%   |
| Yes  | 113       | 27.1%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 117       | 53.67%  |
| Realtek Semiconductor           | 29        | 13.3%   |
| Qualcomm Atheros Communications | 13        | 5.96%   |
| Cambridge Silicon Radio         | 12        | 5.5%    |
| Broadcom                        | 9         | 4.13%   |
| Foxconn / Hon Hai               | 8         | 3.67%   |
| Lite-On Technology              | 5         | 2.29%   |
| ASUSTek Computer                | 5         | 2.29%   |
| Apple                           | 5         | 2.29%   |
| MediaTek                        | 3         | 1.38%   |
| IMC Networks                    | 3         | 1.38%   |
| Toshiba                         | 2         | 0.92%   |
| Marvell Semiconductor           | 2         | 0.92%   |
| Dell                            | 2         | 0.92%   |
| Integrated System Solution      | 1         | 0.46%   |
| Hewlett-Packard                 | 1         | 0.46%   |
| Askey Computer                  | 1         | 0.46%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)

![Bluetooth Model](./images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 36        | 16.51%  |
| Realtek Bluetooth Radio                             | 22        | 10.09%  |
| Intel AX201 Bluetooth                               | 22        | 10.09%  |
| Intel Bluetooth Device                              | 18        | 8.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 16        | 7.34%   |
| Intel AX200 Bluetooth                               | 13        | 5.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12        | 5.5%    |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 4.13%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 2.29%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 1.83%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.83%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 1.83%   |
| ASUS ASUS USB-BT500                                 | 4         | 1.83%   |
| MediaTek Wireless_Device                            | 3         | 1.38%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.38%   |
| Apple Bluetooth Host Controller                     | 3         | 1.38%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.92%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.92%   |
| Lite-On Wireless_Device                             | 2         | 0.92%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.92%   |
| Intel AX210 Bluetooth                               | 2         | 0.92%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 0.92%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 0.92%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.92%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.92%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.92%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.46%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.46%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.46%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)     | 1         | 0.46%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 0.46%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 0.46%   |
| Integrated System Solution Bluetooth Device         | 1         | 0.46%   |
| IMC Networks Wireless_Device                        | 1         | 0.46%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.46%   |
| IMC Networks Bluetooth Device                       | 1         | 0.46%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter          | 1         | 0.46%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.46%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.46%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)

![Sound Vendor](./images/line_chart/snd_vendor.svg)

| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 297       | 56.68%  |
| AMD                                          | 89        | 16.98%  |
| Nvidia                                       | 84        | 16.03%  |
| Logitech                                     | 9         | 1.72%   |
| C-Media Electronics                          | 8         | 1.53%   |
| Creative Labs                                | 4         | 0.76%   |
| Realtek Semiconductor                        | 3         | 0.57%   |
| KTMicro                                      | 3         | 0.57%   |
| ASUSTek Computer                             | 3         | 0.57%   |
| Tenx Technology                              | 2         | 0.38%   |
| JMTek                                        | 2         | 0.38%   |
| Giga-Byte Technology                         | 2         | 0.38%   |
| Generalplus Technology                       | 2         | 0.38%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.19%   |
| Texas Instruments                            | 1         | 0.19%   |
| SteelSeries ApS                              | 1         | 0.19%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.19%   |
| Sennheiser Communications                    | 1         | 0.19%   |
| Nordic Semiconductor ASA                     | 1         | 0.19%   |
| Microsoft                                    | 1         | 0.19%   |
| Micro Star International                     | 1         | 0.19%   |
| Lenovo                                       | 1         | 0.19%   |
| Kingston Technology                          | 1         | 0.19%   |
| Hewlett-Packard                              | 1         | 0.19%   |
| Focusrite-Novation                           | 1         | 0.19%   |
| Dell                                         | 1         | 0.19%   |
| Cirrus Logic                                 | 1         | 0.19%   |
| Audient                                      | 1         | 0.19%   |
| Apple                                        | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)

![Sound Model](./images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 42        | 6.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 32        | 5.11%   |
| AMD Family 17h/19h HD Audio Controller                                     | 30        | 4.79%   |
| Intel Sunrise Point-LP HD Audio                                            | 29        | 4.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 21        | 3.35%   |
| AMD Starship/Matisse HD Audio Controller                                   | 19        | 3.04%   |
| Nvidia GF108 High Definition Audio Controller                              | 18        | 2.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18        | 2.88%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 15        | 2.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 15        | 2.4%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 15        | 2.4%    |
| Intel 200 Series PCH HD Audio                                              | 14        | 2.24%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 12        | 1.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 1.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11        | 1.76%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 1.6%    |
| Intel 8 Series HD Audio Controller                                         | 10        | 1.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10        | 1.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10        | 1.6%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 9         | 1.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 8         | 1.28%   |
| Intel Alder Lake-S HD Audio Controller                                     | 8         | 1.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8         | 1.28%   |
| AMD FCH Azalia Controller                                                  | 7         | 1.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 0.96%   |
| Intel Jasper Lake HD Audio                                                 | 6         | 0.96%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 0.96%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 6         | 0.96%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 0.96%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6         | 0.96%   |
| Nvidia GT216 HDMI Audio Controller                                         | 5         | 0.8%    |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 0.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 0.8%    |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 5         | 0.8%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5         | 0.8%    |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 0.64%   |
| Nvidia MCP61 High Definition Audio                                         | 4         | 0.64%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 0.64%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 0.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)

![Memory Vendor](./images/line_chart/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 76        | 20.38%  |
| SK hynix            | 59        | 15.82%  |
| Kingston            | 58        | 15.55%  |
| Crucial             | 39        | 10.46%  |
| Micron Technology   | 29        | 7.77%   |
| Unknown             | 27        | 7.24%   |
| Corsair             | 19        | 5.09%   |
| G.Skill             | 12        | 3.22%   |
| A-DATA Technology   | 12        | 3.22%   |
| Patriot             | 8         | 2.14%   |
| Elpida              | 5         | 1.34%   |
| Unknown (ABCD)      | 4         | 1.07%   |
| Smart               | 3         | 0.8%    |
| Ramaxel Technology  | 3         | 0.8%    |
| Silicon Power       | 2         | 0.54%   |
| OCZ                 | 2         | 0.54%   |
| Nanya Technology    | 2         | 0.54%   |
| Unknown (89BA)      | 1         | 0.27%   |
| Unknown (768A)      | 1         | 0.27%   |
| Unknown (0x5846)    | 1         | 0.27%   |
| Unknown (0x0B45)    | 1         | 0.27%   |
| Toshiba             | 1         | 0.27%   |
| Timetec             | 1         | 0.27%   |
| Team                | 1         | 0.27%   |
| PNY                 | 1         | 0.27%   |
| OM Nanotech         | 1         | 0.27%   |
| Hikvision           | 1         | 0.27%   |
| CSX                 | 1         | 0.27%   |
| 2B0B00000000        | 1         | 0.27%   |
| Unknown             | 1         | 0.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)

![Memory Model](./images/line_chart/memory_model.svg)

| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s            | 15        | 3.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 1.76%   |
| Patriot RAM PSD38G13332 8GB DIMM DDR3 1333MT/s                   | 6         | 1.51%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 1.01%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 1.01%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 4         | 1.01%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 4         | 1.01%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 3         | 0.75%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.75%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.75%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.75%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 3         | 0.75%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                             | 2         | 0.5%    |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 2         | 0.5%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 2         | 0.5%    |
| Unknown RAM Module 1GB DIMM 800MT/s                              | 2         | 0.5%    |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s             | 2         | 0.5%    |
| SK hynix RAM HMT41GU6AFR8A-PB 8GB DIMM DDR3 1600MT/s             | 2         | 0.5%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.5%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 0.5%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.5%    |
| SK hynix RAM HMA42GR7MFR4N-TF 16GB DIMM DDR4 2133MT/s            | 2         | 0.5%    |
| Samsung RAM Module 8GB SODIMM DDR5 4800MT/s                      | 2         | 0.5%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.5%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.5%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.5%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.5%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 0.5%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 0.5%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.5%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.5%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.5%    |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s             | 2         | 0.5%    |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s              | 2         | 0.5%    |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 2         | 0.5%    |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 0.5%    |
| Kingston RAM 9965745-039.A00G 32GB DIMM DDR4 3200MT/s            | 2         | 0.5%    |
| Kingston RAM 9905474-012.A00LF 2GB DIMM DDR3 1333MT/s            | 2         | 0.5%    |
| Kingston RAM 2G-UDIMM 2GB DIMM DDR2 800MT/s                      | 2         | 0.5%    |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s          | 2         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)

![Memory Kind](./images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 165       | 49.25%  |
| DDR3    | 109       | 32.54%  |
| Unknown | 15        | 4.48%   |
| DDR2    | 10        | 2.99%   |
| DDR5    | 9         | 2.69%   |
| LPDDR4  | 8         | 2.39%   |
| LPDDR3  | 8         | 2.39%   |
| SDRAM   | 7         | 2.09%   |
| LPDDR5  | 3         | 0.9%    |
| DRAM    | 1         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 168       | 50.15%  |
| DIMM         | 152       | 45.37%  |
| Row Of Chips | 11        | 3.28%   |
| RIMM         | 3         | 0.9%    |
| Chip         | 1         | 0.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)

![Memory Size](./images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 138       | 38.76%  |
| 4096  | 86        | 24.16%  |
| 16384 | 65        | 18.26%  |
| 2048  | 37        | 10.39%  |
| 32768 | 16        | 4.49%   |
| 1024  | 11        | 3.09%   |
| 512   | 2         | 0.56%   |
| 65536 | 1         | 0.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)

![Memory Speed](./images/line_chart/memory_speed.svg)

| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 62        | 17.37%  |
| 1600    | 55        | 15.41%  |
| 2667    | 40        | 11.2%   |
| 1333    | 26        | 7.28%   |
| 2400    | 24        | 6.72%   |
| 2133    | 21        | 5.88%   |
| 1866    | 18        | 5.04%   |
| 3600    | 16        | 4.48%   |
| 800     | 11        | 3.08%   |
| 1867    | 10        | 2.8%    |
| 4800    | 9         | 2.52%   |
| 1066    | 7         | 1.96%   |
| Unknown | 7         | 1.96%   |
| 667     | 6         | 1.68%   |
| 1067    | 5         | 1.4%    |
| 3266    | 4         | 1.12%   |
| 1334    | 4         | 1.12%   |
| 6400    | 3         | 0.84%   |
| 4267    | 3         | 0.84%   |
| 3800    | 3         | 0.84%   |
| 8400    | 2         | 0.56%   |
| 3534    | 2         | 0.56%   |
| 2666    | 2         | 0.56%   |
| 1800    | 2         | 0.56%   |
| 6000    | 1         | 0.28%   |
| 5600    | 1         | 0.28%   |
| 4133    | 1         | 0.28%   |
| 3933    | 1         | 0.28%   |
| 3466    | 1         | 0.28%   |
| 3400    | 1         | 0.28%   |
| 3334    | 1         | 0.28%   |
| 3100    | 1         | 0.28%   |
| 3000    | 1         | 0.28%   |
| 2933    | 1         | 0.28%   |
| 2733    | 1         | 0.28%   |
| 2176    | 1         | 0.28%   |
| 1639    | 1         | 0.28%   |
| 1331    | 1         | 0.28%   |
| 975     | 1         | 0.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)

![Printer Vendor](./images/line_chart/printer_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 6         | 46.15%  |
| Canon                 | 3         | 23.08%  |
| Brother Industries    | 2         | 15.38%  |
| Seiko Epson           | 1         | 7.69%   |
| Lexmark International | 1         | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)

![Printer Model](./images/line_chart/printer_model.svg)

| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| HP LaserJet 1200              | 2         | 15.38%  |
| Seiko Epson L6290 Series      | 1         | 7.69%   |
| Lexmark International B2338dw | 1         | 7.69%   |
| HP LaserJet P2035             | 1         | 7.69%   |
| HP LaserJet P1005             | 1         | 7.69%   |
| HP DeskJet 840c               | 1         | 7.69%   |
| HP DeskJet 2700 series        | 1         | 7.69%   |
| Canon MF4010 series           | 1         | 7.69%   |
| Canon MF3010                  | 1         | 7.69%   |
| Canon LBP2900                 | 1         | 7.69%   |
| Brother QL-570 Label Printer  | 1         | 7.69%   |
| Brother DCP-7030              | 1         | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)

![Scanner Vendor](./images/line_chart/scanner_vendor.svg)

| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 2         | 66.67%  |
| Mustek Systems | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)

![Scanner Model](./images/line_chart/scanner_model.svg)

| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Mustek Systems BearPaw 2400 CU Plus | 1         | 33.33%  |
| Canon CanoScan LiDE 210             | 1         | 33.33%  |
| Canon CanoScan 4400F                | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)

![Camera Vendor](./images/line_chart/camera_vendor.svg)

| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 53        | 28.65%  |
| IMC Networks                           | 17        | 9.19%   |
| Acer                                   | 12        | 6.49%   |
| Quanta                                 | 11        | 5.95%   |
| Sunplus Innovation Technology          | 9         | 4.86%   |
| Realtek Semiconductor                  | 8         | 4.32%   |
| Microdia                               | 8         | 4.32%   |
| Logitech                               | 8         | 4.32%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 4.32%   |
| Lite-On Technology                     | 7         | 3.78%   |
| Bison Electronics                      | 7         | 3.78%   |
| Suyin                                  | 5         | 2.7%    |
| Luxvisions Innotech Limited            | 4         | 2.16%   |
| Lenovo                                 | 4         | 2.16%   |
| Syntek                                 | 3         | 1.62%   |
| Microsoft                              | 3         | 1.62%   |
| Generalplus Technology                 | 3         | 1.62%   |
| Jieli Technology                       | 2         | 1.08%   |
| icSpring                               | 2         | 1.08%   |
| ARC International                      | 2         | 1.08%   |
| Apple                                  | 2         | 1.08%   |
| USB3.0 HD Audio Capture                | 1         | 0.54%   |
| Silicon Motion                         | 1         | 0.54%   |
| Ricoh                                  | 1         | 0.54%   |
| KYE Systems (Mouse Systems)            | 1         | 0.54%   |
| BRS 2Mp Camera                         | 1         | 0.54%   |
| AVerMedia Technologies                 | 1         | 0.54%   |
| Alcor Micro                            | 1         | 0.54%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)

![Camera Model](./images/line_chart/camera_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 15        | 7.98%   |
| IMC Networks Integrated Camera                      | 7         | 3.72%   |
| Microdia Integrated_Webcam_HD                       | 6         | 3.19%   |
| Chicony HD WebCam                                   | 6         | 3.19%   |
| Realtek Integrated_Webcam_HD                        | 5         | 2.66%   |
| Quanta HD User Facing                               | 5         | 2.66%   |
| Chicony HP HD Camera                                | 5         | 2.66%   |
| Logitech HD Pro Webcam C920                         | 4         | 2.13%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 2.13%   |
| Acer BisonCam, NB Pro                               | 4         | 2.13%   |
| Lite-On Integrated Camera                           | 3         | 1.6%    |
| Generalplus GENERAL WEBCAM                          | 3         | 1.6%    |
| Chicony USB 2.0 Camera                              | 3         | 1.6%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 3         | 1.6%    |
| Syntek Integrated Camera                            | 2         | 1.06%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.06%   |
| Sunplus FHD Camera Microphone                       | 2         | 1.06%   |
| Quanta HP Wide Vision HD Camera                     | 2         | 1.06%   |
| Luxvisions Innotech Limited HP 5MP Camera           | 2         | 1.06%   |
| Lite-On HP HD Camera                                | 2         | 1.06%   |
| Lenovo Integrated Webcam [R5U877]                   | 2         | 1.06%   |
| Jieli USB PHY 2.0                                   | 2         | 1.06%   |
| IMC Networks UVC VGA Webcam                         | 2         | 1.06%   |
| IMC Networks Lenovo EasyCamera                      | 2         | 1.06%   |
| icSpring camera                                     | 2         | 1.06%   |
| Chicony USB2.0 HD UVC WebCam                        | 2         | 1.06%   |
| Chicony Integrated Camera [ThinkPad]                | 2         | 1.06%   |
| Chicony Integrated Camera (1280x720@30)             | 2         | 1.06%   |
| Chicony HP Wide Vision HD Camera                    | 2         | 1.06%   |
| Chicony HP Webcam                                   | 2         | 1.06%   |
| Chicony HD User Facing                              | 2         | 1.06%   |
| Chicony FJ Camera                                   | 2         | 1.06%   |
| Chicony 1.3M Webcam                                 | 2         | 1.06%   |
| Bison ThinkPad P50 Integrated Camera                | 2         | 1.06%   |
| Bison Lenovo EasyCamera                             | 2         | 1.06%   |
| Bison Integrated Camera                             | 2         | 1.06%   |
| ARC International Camera                            | 2         | 1.06%   |
| Acer Integrated RGB Camera                          | 2         | 1.06%   |
| Acer Integrated Camera                              | 2         | 1.06%   |
| Acer Integrated 5M Camera                           | 2         | 1.06%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 17        | 41.46%  |
| Validity Sensors           | 12        | 29.27%  |
| Upek                       | 2         | 4.88%   |
| Shenzhen Goodix Technology | 2         | 4.88%   |
| LighTuning Technology      | 2         | 4.88%   |
| Elan Microelectronics      | 2         | 4.88%   |
| AuthenTec                  | 2         | 4.88%   |
| STMicroelectronics         | 1         | 2.44%   |
| Focal-systems.Corp         | 1         | 2.44%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart/fingerprint_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 21.95%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 9.76%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 7.32%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 4.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 4.88%   |
| Synaptics UWP WBDI Device                                                  | 2         | 4.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 4.88%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 4.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 4.88%   |
| Elan ELAN:ARM-M4                                                           | 2         | 4.88%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.44%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.44%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.44%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 2.44%   |
| Synaptics UWP WBDI                                                         | 1         | 2.44%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 2.44%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 2.44%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 2.44%   |
| AuthenTec AES2810                                                          | 1         | 2.44%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 2.44%   |
| Unknown                                                                    | 1         | 2.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./images/line_chart/chipcard_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Alcor Micro              | 13        | 40.63%  |
| Broadcom                 | 9         | 28.13%  |
| Upek                     | 3         | 9.38%   |
| Lenovo                   | 3         | 9.38%   |
| SCM Microsystems         | 1         | 3.13%   |
| Reiner SCT Kartensysteme | 1         | 3.13%   |
| Realtek Semiconductor    | 1         | 3.13%   |
| O2 Micro                 | 1         | 3.13%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)

![Chipcard Model](./images/line_chart/chipcard_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                        | 13        | 40.63%  |
| Broadcom 58200                                                             | 5         | 15.63%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                 | 3         | 9.38%   |
| Lenovo Integrated Smart Card Reader                                        | 3         | 9.38%   |
| Broadcom 5880                                                              | 3         | 9.38%   |
| SCM Microsystems SCR331 SmartCard Reader                                   | 1         | 3.13%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1         | 3.13%   |
| Realtek Semiconductor Smart Card Reader Interface                          | 1         | 3.13%   |
| O2 Micro OZ776 CCID Smartcard Reader                                       | 1         | 3.13%   |
| Broadcom BCM5880 Secure Applications Processor                             | 1         | 3.13%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 204       | 48.92%  |
| 1     | 157       | 37.65%  |
| 2     | 46        | 11.03%  |
| 3     | 8         | 1.92%   |
| 4     | 2         | 0.48%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart/device_unsupported_type.svg)

| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 106       | 40.61%  |
| Fingerprint reader       | 40        | 15.33%  |
| Net/wireless             | 31        | 11.88%  |
| Chipcard                 | 29        | 11.11%  |
| Unassigned class         | 12        | 4.6%    |
| Multimedia controller    | 12        | 4.6%    |
| Communication controller | 12        | 4.6%    |
| Camera                   | 5         | 1.92%   |
| Bluetooth                | 5         | 1.92%   |
| Wireless                 | 2         | 0.77%   |
| Sound                    | 2         | 0.77%   |
| Storage/raid             | 1         | 0.38%   |
| Storage/nvme             | 1         | 0.38%   |
| Storage                  | 1         | 0.38%   |
| Dvb card                 | 1         | 0.38%   |
| Card reader              | 1         | 0.38%   |

