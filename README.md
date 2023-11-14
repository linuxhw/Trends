Linux - Hardware Trends
-----------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by Linux users at https://Linux-Hardware.org.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Desktop/README.md) and [notebooks](/Notebook/README.md).

Distribution-specific reports: [Arch](/Dist/Arch), [ArcoLinux](/Dist/ArcoLinux), [BlackPanther](/Dist/BlackPanther), [CentOS](/Dist/CentOS), [Clear Linux](/Dist/Clear_Linux), [Debian](/Dist/Debian), [Elementary](/Dist/Elementary), [EndeavourOS](/Dist/EndeavourOS), [Endless](/Dist/Endless), [Fedora](/Dist/Fedora), [Garuda Linux](/Dist/Garuda_Linux), [Gentoo](/Dist/Gentoo), [Kali](/Dist/Kali), [KDE neon](/Dist/KDE_neon), [Kubuntu](/Dist/Kubuntu), [Linux Mint](/Dist/Linux_Mint), [Manjaro](/Dist/Manjaro), [OpenMandriva](/Dist/OpenMandriva), [openSUSE](/Dist/openSUSE), [Pop!_OS](/Dist/Pop!_OS), [Red OS](/Dist/Red_OS), [ROSA](/Dist/ROSA), [SteamOS](/Dist/SteamOS), [Ubuntu MATE](/Dist/Ubuntu_MATE), [Ubuntu](/Dist/Ubuntu), [Xubuntu](/Dist/Xubuntu), [Zorin](/Dist/Zorin).

This report is for one last month. Overall report since the beginning of time: [TestDays](https://github.com/linuxhw/TestDays)

Period: Oct, 2023.

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

| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 22.04                 | 918       | 15.53%  |
| Fedora 38                    | 457       | 7.73%   |
| Linux Mint 21.2              | 429       | 7.26%   |
| Debian 12                    | 392       | 6.63%   |
| Arch Rolling                 | 244       | 4.13%   |
| Pop!_OS 22.04                | 215       | 3.64%   |
| Ubuntu 23.04                 | 204       | 3.45%   |
| ROSA 12.4                    | 180       | 3.05%   |
| Zorin 16                     | 152       | 2.57%   |
| OpenMandriva 23.08           | 148       | 2.5%    |
| Ubuntu 23.10                 | 143       | 2.42%   |
| ArcoLinux Rolling            | 123       | 2.08%   |
| Ubuntu 20.04                 | 100       | 1.69%   |
| OpenMandriva 23.10           | 92        | 1.56%   |
| BlackPanther 18.1            | 92        | 1.56%   |
| Manjaro                      | 78        | 1.32%   |
| Kubuntu 22.04                | 76        | 1.29%   |
| Kali 2023.3                  | 75        | 1.27%   |
| KDE neon 22.04               | 71        | 1.2%    |
| openSUSE Tumbleweed-XXXXXXXX | 69        | 1.17%   |
| Debian 11                    | 68        | 1.15%   |
| EndeavourOS Rolling          | 64        | 1.08%   |
| Gentoo 2.14                  | 52        | 0.88%   |
| Debian                       | 50        | 0.85%   |
| Fedora 39                    | 47        | 0.8%    |
| Xero Rolling                 | 46        | 0.78%   |
| LMDE 6                       | 45        | 0.76%   |
| Linux Mint 21.1              | 44        | 0.74%   |
| Kubuntu 23.04                | 44        | 0.74%   |
| Nobara 38                    | 42        | 0.71%   |
| Elementary 7.1               | 39        | 0.66%   |
| Linux Mint 20.3              | 38        | 0.64%   |
| Kubuntu 23.10                | 33        | 0.56%   |
| SteamOS 3.4.11               | 32        | 0.54%   |
| Xubuntu 22.04                | 31        | 0.52%   |
| OpenMandriva 4.3             | 31        | 0.52%   |
| openSUSE Leap-15.5           | 28        | 0.47%   |
| Lubuntu 22.04                | 25        | 0.42%   |
| NixOS 23.05                  | 23        | 0.39%   |
| Manjaro 23.0.4               | 23        | 0.39%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)

![OS Family](./All/images/line_chart/os_family.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1403      | 23.74%  |
| Linux Mint    | 561       | 9.49%   |
| Fedora        | 523       | 8.85%   |
| Debian        | 516       | 8.73%   |
| OpenMandriva  | 346       | 5.85%   |
| Arch          | 244       | 4.13%   |
| ROSA          | 220       | 3.72%   |
| Pop!_OS       | 216       | 3.65%   |
| Kubuntu       | 161       | 2.72%   |
| Zorin         | 154       | 2.61%   |
| Manjaro       | 130       | 2.2%    |
| ArcoLinux     | 126       | 2.13%   |
| openSUSE      | 105       | 1.78%   |
| BlackPanther  | 103       | 1.74%   |
| Kali          | 79        | 1.34%   |
| SteamOS       | 78        | 1.32%   |
| KDE neon      | 73        | 1.23%   |
| EndeavourOS   | 64        | 1.08%   |
| Xubuntu       | 54        | 0.91%   |
| Gentoo        | 54        | 0.91%   |
| LMDE          | 51        | 0.86%   |
| Xero          | 46        | 0.78%   |
| Nobara        | 45        | 0.76%   |
| Elementary    | 44        | 0.74%   |
| Lubuntu       | 37        | 0.63%   |
| Ubuntu MATE   | 32        | 0.54%   |
| MX            | 32        | 0.54%   |
| NixOS         | 29        | 0.49%   |
| Garuda Linux  | 29        | 0.49%   |
| ALT Linux     | 28        | 0.47%   |
| Red OS        | 19        | 0.32%   |
| Ubuntu Budgie | 17        | 0.29%   |
| Endless       | 14        | 0.24%   |
| blendOS       | 13        | 0.22%   |
| Rocky Linux   | 12        | 0.2%    |
| ChimeraOS     | 12        | 0.2%    |
| BigLinux      | 12        | 0.2%    |
| Parrot        | 11        | 0.19%   |
| Cyber Infra   | 11        | 0.19%   |
| AlmaLinux     | 10        | 0.17%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)

![Kernel](./All/images/line_chart/os_kernel.svg)

| Version                           | Computers | Percent |
|-----------------------------------|-----------|---------|
| 6.2.0-34-generic                  | 573       | 9.69%   |
| 6.2.0-35-generic                  | 343       | 5.8%    |
| 5.15.0-86-generic                 | 295       | 4.99%   |
| 6.1.0-13-amd64                    | 259       | 4.38%   |
| 5.15.0-87-generic                 | 203       | 3.43%   |
| 6.2.0-33-generic                  | 199       | 3.37%   |
| 6.5.5-200.fc38.x86_64             | 132       | 2.23%   |
| 6.4.11-desktop-1omv2390           | 132       | 2.23%   |
| 6.5.0-9-generic                   | 123       | 2.08%   |
| 6.1.0-12-amd64                    | 109       | 1.84%   |
| 5.15.0-84-generic                 | 109       | 1.84%   |
| 6.5.6-200.fc38.x86_64             | 100       | 1.69%   |
| 6.5.4-76060504-generic            | 97        | 1.64%   |
| 6.5.5-arch1-1                     | 94        | 1.59%   |
| 6.5.5-desktop-1omv2390            | 93        | 1.57%   |
| 6.5.7-200.fc38.x86_64             | 84        | 1.42%   |
| 6.5.7-arch1-1                     | 77        | 1.3%    |
| 6.1.46-generic-2rosa2021.1-x86_64 | 76        | 1.29%   |
| 6.1.20-generic-2rosa2021.1-x86_64 | 61        | 1.03%   |
| 6.5.6-76060506-generic            | 60        | 1.02%   |
| 6.5.5-1-MANJARO                   | 57        | 0.96%   |
| 5.19.0-38-generic                 | 56        | 0.95%   |
| 6.2.0-26-generic                  | 55        | 0.93%   |
| 6.5.8-arch1-1                     | 54        | 0.91%   |
| 6.5.8-200.fc38.x86_64             | 54        | 0.91%   |
| 6.5.9-arch2-1                     | 51        | 0.86%   |
| 6.2.9-300.fc38.x86_64             | 51        | 0.86%   |
| 5.15.0-76-generic                 | 51        | 0.86%   |
| 6.5.0-10-generic                  | 46        | 0.78%   |
| 5.13.0-valve37-1-neptune          | 46        | 0.78%   |
| 6.2.0-36-generic                  | 44        | 0.74%   |
| 5.6.14-desktop-2bP                | 44        | 0.74%   |
| 6.4.6-76060406-generic            | 42        | 0.71%   |
| 6.5.0-kali2-amd64                 | 33        | 0.56%   |
| 6.5.5-zen1-1-zen                  | 30        | 0.51%   |
| 6.5.4-1-default                   | 28        | 0.47%   |
| 4.18.16-desktop-1bP               | 28        | 0.47%   |
| 6.5.6-300.fc39.x86_64             | 25        | 0.42%   |
| 6.5.6-1-default                   | 24        | 0.41%   |
| 6.4.8-desktop-2omv2390            | 24        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)

![Kernel Family](./All/images/line_chart/os_kernel_family.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.0   | 1286      | 21.76%  |
| 5.15.0  | 806       | 13.64%  |
| 6.5.5   | 474       | 8.02%   |
| 6.1.0   | 459       | 7.77%   |
| 6.5.0   | 301       | 5.09%   |
| 6.5.6   | 288       | 4.87%   |
| 6.5.7   | 239       | 4.04%   |
| 6.5.8   | 162       | 2.74%   |
| 6.4.11  | 146       | 2.47%   |
| 6.5.4   | 141       | 2.39%   |
| 5.4.0   | 94        | 1.59%   |
| 5.19.0  | 92        | 1.56%   |
| 6.5.9   | 91        | 1.54%   |
| 6.1.46  | 79        | 1.34%   |
| 6.1.20  | 61        | 1.03%   |
| 5.10.0  | 61        | 1.03%   |
| 6.5.3   | 53        | 0.9%    |
| 5.13.0  | 53        | 0.9%    |
| 6.2.9   | 52        | 0.88%   |
| 6.1.55  | 46        | 0.78%   |
| 5.6.14  | 44        | 0.74%   |
| 6.4.6   | 43        | 0.73%   |
| 6.1.52  | 32        | 0.54%   |
| 6.1.58  | 31        | 0.52%   |
| 5.14.21 | 29        | 0.49%   |
| 6.6.0   | 28        | 0.47%   |
| 6.2.6   | 28        | 0.47%   |
| 4.18.16 | 28        | 0.47%   |
| 6.4.8   | 27        | 0.46%   |
| 4.15.0  | 25        | 0.42%   |
| 6.4.0   | 24        | 0.41%   |
| 5.14.0  | 24        | 0.41%   |
| 6.2.16  | 22        | 0.37%   |
| 5.16.7  | 22        | 0.37%   |
| 6.4.12  | 21        | 0.36%   |
| 5.15.85 | 21        | 0.36%   |
| 6.1.57  | 20        | 0.34%   |
| 6.1.53  | 20        | 0.34%   |
| 6.1.1   | 15        | 0.25%   |
| 3.10.0  | 15        | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)

![Kernel Major Ver.](./All/images/line_chart/os_kernel_major.svg)

| Version | Computers | Percent |
|---------|-----------|---------|
| 6.5     | 1766      | 29.88%  |
| 6.2     | 1402      | 23.72%  |
| 5.15    | 875       | 14.8%   |
| 6.1     | 845       | 14.3%   |
| 6.4     | 305       | 5.16%   |
| 5.10    | 107       | 1.81%   |
| 5.4     | 106       | 1.79%   |
| 5.19    | 94        | 1.59%   |
| 6.3     | 55        | 0.93%   |
| 5.14    | 55        | 0.93%   |
| 5.13    | 54        | 0.91%   |
| 5.6     | 45        | 0.76%   |
| 4.18    | 42        | 0.71%   |
| 5.16    | 34        | 0.58%   |
| 6.6     | 28        | 0.47%   |
| 4.15    | 25        | 0.42%   |
| 3.10    | 15        | 0.25%   |
| 6.0     | 12        | 0.2%    |
| 5.8     | 8         | 0.14%   |
| 5.11    | 8         | 0.14%   |
| 5.17    | 6         | 0.1%    |
| 4.19    | 5         | 0.08%   |
| 4.4     | 4         | 0.07%   |
| 5.18    | 3         | 0.05%   |
| 5.0     | 3         | 0.05%   |
| 4.9     | 3         | 0.05%   |
| 96.5    | 1         | 0.02%   |
| 6.5.2   | 1         | 0.02%   |
| 6       | 1         | 0.02%   |
| 5.3     | 1         | 0.02%   |
| 4.14    | 1         | 0.02%   |
| 4.1     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)

![Arch](./All/images/line_chart/os_arch.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 5831      | 98.65%  |
| i686    | 36        | 0.61%   |
| aarch64 | 34        | 0.58%   |
| armv7l  | 5         | 0.08%   |
| riscv64 | 3         | 0.05%   |
| mips64  | 1         | 0.02%   |
| armv6l  | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)

![DE](./All/images/line_chart/os_de.svg)

| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| GNOME                   | 2530      | 42.8%   |
| KDE5                    | 1512      | 25.58%  |
| X-Cinnamon              | 530       | 8.97%   |
| Unknown                 | 364       | 6.16%   |
| XFCE                    | 350       | 5.92%   |
| MATE                    | 175       | 2.96%   |
| LXQt                    | 98        | 1.66%   |
| Cinnamon                | 50        | 0.85%   |
| Pantheon                | 45        | 0.76%   |
| i3                      | 40        | 0.68%   |
| Budgie                  | 32        | 0.54%   |
| Hyprland                | 24        | 0.41%   |
| LXDE                    | 20        | 0.34%   |
| GNOME Classic           | 14        | 0.24%   |
| KDE                     | 13        | 0.22%   |
| KDE4                    | 11        | 0.19%   |
| GNOME Flashback         | 11        | 0.19%   |
| Deepin                  | 11        | 0.19%   |
| Unity                   | 9         | 0.15%   |
| sway                    | 7         | 0.12%   |
| Endless:GNOME           | 7         | 0.12%   |
| Openbox                 | 6         | 0.1%    |
| awesome                 | 5         | 0.08%   |
| lightdm-xsession        | 4         | 0.07%   |
| DWM                     | 4         | 0.07%   |
| DDE                     | 4         | 0.07%   |
| bspwm                   | 4         | 0.07%   |
| icewm                   | 3         | 0.05%   |
| x-session-manager       | 2         | 0.03%   |
| none+i3                 | 2         | 0.03%   |
| LXDE-pi-wayfire         | 2         | 0.03%   |
| JWM                     | 2         | 0.03%   |
| fly                     | 2         | 0.03%   |
| Enlightenment           | 2         | 0.03%   |
| Wayfire:wayfire:wlroots | 1         | 0.02%   |
| Unicorn:XFCE            | 1         | 0.02%   |
| UKUI                    | 1         | 0.02%   |
| Trinity                 | 1         | 0.02%   |
| swayland                | 1         | 0.02%   |
| qtile                   | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)

![Display Server](./All/images/line_chart/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3328      | 56.3%   |
| Wayland | 2176      | 36.81%  |
| Unknown | 244       | 4.13%   |
| Tty     | 162       | 2.74%   |
| Web     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)

![Display Manager](./All/images/line_chart/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2083      | 35.24%  |
| GDM3    | 1352      | 22.87%  |
| SDDM    | 1224      | 20.71%  |
| LightDM | 772       | 13.06%  |
| GDM     | 437       | 7.39%   |
| LXDM    | 11        | 0.19%   |
| KDM     | 11        | 0.19%   |
| XDM     | 5         | 0.08%   |
| LY-DM   | 5         | 0.08%   |
| SLiM    | 4         | 0.07%   |
| GREETD  | 2         | 0.03%   |
| TDM     | 1         | 0.02%   |
| SLIMSKI | 1         | 0.02%   |
| NODM    | 1         | 0.02%   |
| LEMURS  | 1         | 0.02%   |
| FLY-DM  | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)

![OS Lang](./All/images/line_chart/os_lang.svg)

| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2419      | 40.92%  |
| de_DE   | 495       | 8.37%   |
| ru_RU   | 451       | 7.63%   |
| en_GB   | 283       | 4.79%   |
| fr_FR   | 261       | 4.42%   |
| it_IT   | 252       | 4.26%   |
| C       | 216       | 3.65%   |
| Unknown | 211       | 3.57%   |
| pt_BR   | 180       | 3.05%   |
| es_ES   | 136       | 2.3%    |
| en_CA   | 107       | 1.81%   |
| en_AU   | 86        | 1.45%   |
| pl_PL   | 80        | 1.35%   |
| en_IN   | 62        | 1.05%   |
| es_MX   | 55        | 0.93%   |
| nl_NL   | 39        | 0.66%   |
| hu_HU   | 36        | 0.61%   |
| zh_CN   | 30        | 0.51%   |
| es_AR   | 26        | 0.44%   |
| tr_TR   | 25        | 0.42%   |
| cs_CZ   | 23        | 0.39%   |
| pt_PT   | 22        | 0.37%   |
| ja_JP   | 22        | 0.37%   |
| de_AT   | 22        | 0.37%   |
| en_ZA   | 21        | 0.36%   |
| sv_SE   | 20        | 0.34%   |
| fi_FI   | 19        | 0.32%   |
| de_CH   | 15        | 0.25%   |
| en_NZ   | 13        | 0.22%   |
| es_CL   | 12        | 0.2%    |
| en_IE   | 12        | 0.2%    |
| fr_CA   | 11        | 0.19%   |
| es_CO   | 11        | 0.19%   |
| nb_NO   | 10        | 0.17%   |
| es_VE   | 10        | 0.17%   |
| en_DK   | 10        | 0.17%   |
| ca_ES   | 10        | 0.17%   |
| zh_TW   | 9         | 0.15%   |
| nl_BE   | 8         | 0.14%   |
| ko_KR   | 8         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)

![Boot Mode](./All/images/line_chart/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 3202      | 54.17%  |
| BIOS | 2709      | 45.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)

![Filesystem](./All/images/line_chart/os_filesystem.svg)

| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3418      | 57.82%  |
| Btrfs    | 998       | 16.88%  |
| Tmpfs    | 900       | 15.23%  |
| Overlay  | 414       | 7%      |
| Xfs      | 102       | 1.73%   |
| Zfs      | 41        | 0.69%   |
| F2fs     | 16        | 0.27%   |
| Ext3     | 7         | 0.12%   |
| Ext2     | 5         | 0.08%   |
| Unknown  | 4         | 0.07%   |
| Jfs      | 2         | 0.03%   |
| Aufs     | 2         | 0.03%   |
| XXXXXXX  | 1         | 0.02%   |
| Reiserfs | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)

![Part. scheme](./All/images/line_chart/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3495      | 59.13%  |
| Unknown | 1808      | 30.59%  |
| MBR     | 608       | 10.29%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)

![Dual Boot with Linux/BSD](./All/images/line_chart/os_dual_boot.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5083      | 85.99%  |
| Yes       | 828       | 14.01%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)

![Dual Boot (Win)](./All/images/line_chart/os_dual_boot_win.svg)

| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4272      | 72.27%  |
| Yes       | 1639      | 27.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)

![Vendor](./All/images/line_chart/node_vendor.svg)

| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 883       | 14.94%  |
| Lenovo                               | 842       | 14.24%  |
| Hewlett-Packard                      | 798       | 13.5%   |
| Dell                                 | 666       | 11.27%  |
| Gigabyte Technology                  | 401       | 6.78%   |
| MSI                                  | 372       | 6.29%   |
| Acer                                 | 289       | 4.89%   |
| ASRock                               | 181       | 3.06%   |
| Apple                                | 162       | 2.74%   |
| Intel                                | 100       | 1.69%   |
| Unknown                              | 77        | 1.3%    |
| Valve                                | 70        | 1.18%   |
| Toshiba                              | 68        | 1.15%   |
| Google                               | 67        | 1.13%   |
| HUAWEI                               | 63        | 1.07%   |
| Samsung Electronics                  | 62        | 1.05%   |
| Supermicro                           | 49        | 0.83%   |
| Fujitsu                              | 47        | 0.8%    |
| Sony                                 | 32        | 0.54%   |
| AZW                                  | 31        | 0.52%   |
| Notebook                             | 22        | 0.37%   |
| Microsoft                            | 22        | 0.37%   |
| Biostar                              | 22        | 0.37%   |
| Pegatron                             | 20        | 0.34%   |
| Medion                               | 19        | 0.32%   |
| Raspberry Pi Foundation              | 18        | 0.3%    |
| ETegro Technologies                  | 16        | 0.27%   |
| Alienware                            | 15        | 0.25%   |
| Packard Bell                         | 13        | 0.22%   |
| AMI                                  | 13        | 0.22%   |
| Timi                                 | 12        | 0.2%    |
| System76                             | 12        | 0.2%    |
| Fujitsu Siemens                      | 12        | 0.2%    |
| Foxconn                              | 12        | 0.2%    |
| ECS                                  | 12        | 0.2%    |
| Shenzhen Meigao Electronic Equipment | 11        | 0.19%   |
| MACHINIST                            | 11        | 0.19%   |
| Chuwi                                | 11        | 0.19%   |
| Panasonic                            | 10        | 0.17%   |
| Framework                            | 10        | 0.17%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)

![Model](./All/images/line_chart/node_model.svg)

| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 93        | 1.57%   |
| Valve Jupiter                    | 70        | 1.18%   |
| ASUS All Series                  | 33        | 0.56%   |
| Google Reks                      | 32        | 0.54%   |
| HP Notebook                      | 26        | 0.44%   |
| Lenovo ThinkPad E475 20H40006US  | 22        | 0.37%   |
| MSI MS-7C37                      | 16        | 0.27%   |
| ETegro Hyperion RS125 G4         | 16        | 0.27%   |
| Dell OptiPlex 9020               | 12        | 0.2%    |
| Dell OptiPlex 7010               | 12        | 0.2%    |
| ASUS TUF Gaming X570-PLUS        | 12        | 0.2%    |
| Apple MacBookPro9,2              | 12        | 0.2%    |
| Apple MacBookPro8,1              | 12        | 0.2%    |
| MSI MS-7C56                      | 11        | 0.19%   |
| MSI MS-7C02                      | 11        | 0.19%   |
| AZW SER                          | 11        | 0.19%   |
| Dell OptiPlex 7050               | 10        | 0.17%   |
| ASUS ROG STRIX B550-F GAMING     | 10        | 0.17%   |
| MSI MS-7B79                      | 9         | 0.15%   |
| HP Victus by Laptop 16-e0xxx     | 9         | 0.15%   |
| HP Pavilion dv6                  | 9         | 0.15%   |
| Dell XPS 15 9530                 | 9         | 0.15%   |
| ASUS Vivobook Go E1504FA_E1504FA | 9         | 0.15%   |
| ASUS PRIME A320M-K               | 9         | 0.15%   |
| MSI MS-7C95                      | 8         | 0.14%   |
| MSI MS-7B86                      | 8         | 0.14%   |
| MSI MS-7817                      | 8         | 0.14%   |
| Intel H61                        | 8         | 0.14%   |
| HP Pavilion Notebook             | 8         | 0.14%   |
| HP Pavilion dv7                  | 8         | 0.14%   |
| HP Compaq Elite 8300 SFF         | 8         | 0.14%   |
| Gigabyte B550M DS3H              | 8         | 0.14%   |
| Gigabyte B450M DS3H              | 8         | 0.14%   |
| Dell OptiPlex 780                | 8         | 0.14%   |
| Apple MacBookPro12,1             | 8         | 0.14%   |
| Apple MacBookPro11,1             | 8         | 0.14%   |
| Apple MacBookAir6,2              | 8         | 0.14%   |
| AMI Intel                        | 8         | 0.14%   |
| Supermicro X8DTU                 | 7         | 0.12%   |
| MSI MS-7D75                      | 7         | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)

![Model Family](./All/images/line_chart/node_model_family.svg)

| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 356       | 6.02%   |
| Acer Aspire        | 181       | 3.06%   |
| Dell Latitude      | 170       | 2.88%   |
| Lenovo IdeaPad     | 159       | 2.69%   |
| Dell Inspiron      | 135       | 2.28%   |
| ASUS ROG           | 131       | 2.22%   |
| HP Pavilion        | 123       | 2.08%   |
| ASUS PRIME         | 120       | 2.03%   |
| ASUS VivoBook      | 100       | 1.69%   |
| HP EliteBook       | 94        | 1.59%   |
| Dell OptiPlex      | 94        | 1.59%   |
| Unknown            | 93        | 1.57%   |
| Dell Precision     | 90        | 1.52%   |
| HP Laptop          | 82        | 1.39%   |
| Dell XPS           | 74        | 1.25%   |
| Valve Jupiter      | 70        | 1.18%   |
| HP ProBook         | 70        | 1.18%   |
| ASUS TUF           | 68        | 1.15%   |
| Lenovo ThinkCentre | 59        | 1%      |
| Toshiba Satellite  | 57        | 0.96%   |
| HP Compaq          | 48        | 0.81%   |
| Dell Vostro        | 45        | 0.76%   |
| Lenovo Yoga        | 43        | 0.73%   |
| ASUS ASUS          | 42        | 0.71%   |
| ASUS Zenbook       | 40        | 0.68%   |
| Lenovo Legion      | 38        | 0.64%   |
| HP EliteDesk       | 37        | 0.63%   |
| ASUS All           | 33        | 0.56%   |
| Google Reks        | 32        | 0.54%   |
| HP ENVY            | 31        | 0.52%   |
| Acer Nitro         | 30        | 0.51%   |
| Lenovo ThinkBook   | 28        | 0.47%   |
| Dell PowerEdge     | 27        | 0.46%   |
| HP Notebook        | 26        | 0.44%   |
| HP ZBook           | 25        | 0.42%   |
| HP OMEN            | 24        | 0.41%   |
| HP 250             | 23        | 0.39%   |
| Gigabyte B550M     | 23        | 0.39%   |
| Acer Swift         | 23        | 0.39%   |
| Microsoft Surface  | 22        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)

![MFG Year](./All/images/line_chart/node_year.svg)

| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 626       | 10.59%  |
| 2022    | 605       | 10.24%  |
| 2020    | 537       | 9.08%   |
| 2023    | 474       | 8.02%   |
| 2018    | 456       | 7.71%   |
| 2019    | 444       | 7.51%   |
| 2013    | 377       | 6.38%   |
| 2012    | 346       | 5.85%   |
| 2017    | 314       | 5.31%   |
| 2011    | 310       | 5.24%   |
| 2014    | 288       | 4.87%   |
| 2015    | 274       | 4.64%   |
| 2016    | 223       | 3.77%   |
| 2010    | 207       | 3.5%    |
| 2009    | 155       | 2.62%   |
| 2008    | 126       | 2.13%   |
| 2007    | 65        | 1.1%    |
| Unknown | 41        | 0.69%   |
| 2006    | 31        | 0.52%   |
| 2005    | 8         | 0.14%   |
| 2004    | 3         | 0.05%   |
| 2001    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)

![Form Factor](./All/images/line_chart/node_formfactor.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3184      | 53.87%  |
| Desktop        | 2179      | 36.86%  |
| Convertible    | 164       | 2.77%   |
| Server         | 109       | 1.84%   |
| Mini pc        | 103       | 1.74%   |
| All in one     | 79        | 1.34%   |
| Tablet         | 50        | 0.85%   |
| System on chip | 40        | 0.68%   |
| Other          | 2         | 0.03%   |
| Firewall       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)

![Secure Boot](./All/images/line_chart/node_secureboot.svg)

| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 5490      | 92.88%  |
| Enabled  | 421       | 7.12%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)

![Coreboot](./All/images/line_chart/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5831      | 98.65%  |
| Yes  | 80        | 1.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)

![RAM Size](./All/images/line_chart/node_ram_total.svg)

| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1334      | 22.57%  |
| 16.01-24.0      | 1262      | 21.35%  |
| 8.01-16.0       | 1064      | 18%     |
| 32.01-64.0      | 782       | 13.23%  |
| 3.01-4.0        | 777       | 13.14%  |
| 64.01-256.0     | 316       | 5.35%   |
| 24.01-32.0      | 159       | 2.69%   |
| 1.01-2.0        | 112       | 1.89%   |
| 2.01-3.0        | 63        | 1.07%   |
| More than 256.0 | 21        | 0.36%   |
| 0.51-1.0        | 18        | 0.3%    |
| 0.01-0.5        | 2         | 0.03%   |
| Unknown         | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)

![RAM Used](./All/images/line_chart/node_ram_used.svg)

| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1536      | 25.99%  |
| 2.01-3.0    | 1496      | 25.31%  |
| 4.01-8.0    | 1218      | 20.61%  |
| 3.01-4.0    | 888       | 15.02%  |
| 8.01-16.0   | 353       | 5.97%   |
| 0.51-1.0    | 247       | 4.18%   |
| 0.01-0.5    | 74        | 1.25%   |
| 16.01-24.0  | 50        | 0.85%   |
| 24.01-32.0  | 21        | 0.36%   |
| 32.01-64.0  | 16        | 0.27%   |
| 64.01-256.0 | 11        | 0.19%   |
| Unknown     | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)

![Total Drives](./All/images/line_chart/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3471      | 58.72%  |
| 2      | 1495      | 25.29%  |
| 3      | 486       | 8.22%   |
| 4      | 203       | 3.43%   |
| 5      | 94        | 1.59%   |
| 6      | 60        | 1.02%   |
| 7      | 31        | 0.52%   |
| 0      | 23        | 0.39%   |
| 9      | 15        | 0.25%   |
| 8      | 13        | 0.22%   |
| 10     | 7         | 0.12%   |
| 11     | 5         | 0.08%   |
| 410    | 1         | 0.02%   |
| 25     | 1         | 0.02%   |
| 22     | 1         | 0.02%   |
| 19     | 1         | 0.02%   |
| 18     | 1         | 0.02%   |
| 17     | 1         | 0.02%   |
| 13     | 1         | 0.02%   |
| 12     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)

![Has CD-ROM](./All/images/line_chart/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4226      | 71.49%  |
| Yes       | 1685      | 28.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)

![Has Ethernet](./All/images/line_chart/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4854      | 82.12%  |
| No        | 1057      | 17.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)

![Has WiFi](./All/images/line_chart/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4622      | 78.19%  |
| No        | 1289      | 21.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)

![Has Bluetooth](./All/images/line_chart/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3892      | 65.84%  |
| No        | 2019      | 34.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)

![Country](./All/images/line_chart/node_location.svg)

| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1086      | 18.37%  |
| Germany      | 617       | 10.44%  |
| Russia       | 587       | 9.93%   |
| Italy        | 351       | 5.94%   |
| France       | 307       | 5.19%   |
| Brazil       | 268       | 4.53%   |
| UK           | 226       | 3.82%   |
| Spain        | 186       | 3.15%   |
| Canada       | 171       | 2.89%   |
| Hungary      | 136       | 2.3%    |
| Poland       | 135       | 2.28%   |
| India        | 113       | 1.91%   |
| Australia    | 103       | 1.74%   |
| Netherlands  | 100       | 1.69%   |
| Mexico       | 79        | 1.34%   |
| Sweden       | 61        | 1.03%   |
| Switzerland  | 60        | 1.02%   |
| Czechia      | 56        | 0.95%   |
| Argentina    | 54        | 0.91%   |
| Turkey       | 53        | 0.9%    |
| Austria      | 51        | 0.86%   |
| Romania      | 50        | 0.85%   |
| Portugal     | 48        | 0.81%   |
| Finland      | 46        | 0.78%   |
| Belgium      | 46        | 0.78%   |
| Indonesia    | 42        | 0.71%   |
| China        | 42        | 0.71%   |
| Japan        | 41        | 0.69%   |
| Norway       | 39        | 0.66%   |
| Greece       | 31        | 0.52%   |
| Bulgaria     | 31        | 0.52%   |
| South Africa | 30        | 0.51%   |
| Vietnam      | 29        | 0.49%   |
| Colombia     | 27        | 0.46%   |
| Belarus      | 24        | 0.41%   |
| Denmark      | 22        | 0.37%   |
| Philippines  | 21        | 0.36%   |
| Ukraine      | 19        | 0.32%   |
| Thailand     | 19        | 0.32%   |
| Taiwan       | 19        | 0.32%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)

![City](./All/images/line_chart/node_city.svg)

| City           | Computers | Percent |
|----------------|-----------|---------|
| Moscow         | 209       | 3.54%   |
| Bangor         | 63        | 1.07%   |
| Berlin         | 51        | 0.86%   |
| St Petersburg  | 47        | 0.8%    |
| Budapest       | 45        | 0.76%   |
| Paris          | 43        | 0.73%   |
| Sydney         | 37        | 0.63%   |
| Warsaw         | 36        | 0.61%   |
| Milan          | 36        | 0.61%   |
| Vienna         | 29        | 0.49%   |
| Rome           | 28        | 0.47%   |
| Toronto        | 27        | 0.46%   |
| Sao Paulo      | 27        | 0.46%   |
| Rio de Janeiro | 25        | 0.42%   |
| Munich         | 24        | 0.41%   |
| Prague         | 23        | 0.39%   |
| Melbourne      | 22        | 0.37%   |
| Hamburg        | 22        | 0.37%   |
| Voronezh       | 21        | 0.36%   |
| Milano         | 21        | 0.36%   |
| Montreal       | 20        | 0.34%   |
| Madrid         | 20        | 0.34%   |
| Los Angeles    | 20        | 0.34%   |
| Amsterdam      | 20        | 0.34%   |
| Barcelona      | 19        | 0.32%   |
| Sofia          | 18        | 0.3%    |
| New York       | 18        | 0.3%    |
| Helsinki       | 18        | 0.3%    |
| Istanbul       | 17        | 0.29%   |
| Delhi          | 17        | 0.29%   |
| Yekaterinburg  | 16        | 0.27%   |
| Athens         | 16        | 0.27%   |
| Turin          | 15        | 0.25%   |
| Krasnodar      | 14        | 0.24%   |
| Brussels       | 14        | 0.24%   |
| Bengaluru      | 14        | 0.24%   |
| Seattle        | 13        | 0.22%   |
| Rostov-on-Don  | 13        | 0.22%   |
| Nuremberg      | 13        | 0.22%   |
| Novosibirsk    | 13        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)

![Drive Vendor](./All/images/line_chart/drive_vendor.svg)

| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1405      | 1784   | 16.01%  |
| WDC                         | 1024      | 1265   | 11.67%  |
| Seagate                     | 958       | 1201   | 10.91%  |
| SanDisk                     | 565       | 617    | 6.44%   |
| Kingston                    | 489       | 529    | 5.57%   |
| Toshiba                     | 399       | 451    | 4.55%   |
| Unknown                     | 374       | 423    | 4.26%   |
| Crucial                     | 321       | 348    | 3.66%   |
| SK hynix                    | 245       | 251    | 2.79%   |
| Intel                       | 243       | 317    | 2.77%   |
| Micron Technology           | 224       | 266    | 2.55%   |
| Hitachi                     | 183       | 201    | 2.08%   |
| HGST                        | 140       | 195    | 1.6%    |
| A-DATA Technology           | 122       | 130    | 1.39%   |
| Phison Electronics          | 121       | 128    | 1.38%   |
| China                       | 105       | 108    | 1.2%    |
| Micron/Crucial Technology   | 99        | 116    | 1.13%   |
| KIOXIA                      | 90        | 91     | 1.03%   |
| Kingston Technology Company | 89        | 95     | 1.01%   |
| Apple                       | 82        | 95     | 0.93%   |
| Unknown                     | 77        | 79     | 0.88%   |
| Silicon Motion              | 71        | 71     | 0.81%   |
| SPCC                        | 64        | 72     | 0.73%   |
| PNY                         | 51        | 60     | 0.58%   |
| Intenso                     | 49        | 50     | 0.56%   |
| Fujitsu                     | 44        | 62     | 0.5%    |
| ADATA Technology            | 40        | 44     | 0.46%   |
| Patriot                     | 38        | 39     | 0.43%   |
| MAXIO Technology (Hangzhou) | 36        | 38     | 0.41%   |
| Apacer                      | 33        | 35     | 0.38%   |
| Transcend                   | 31        | 32     | 0.35%   |
| Team                        | 31        | 32     | 0.35%   |
| Hewlett-Packard             | 31        | 39     | 0.35%   |
| Phison                      | 30        | 31     | 0.34%   |
| KingSpec                    | 30        | 32     | 0.34%   |
| Realtek Semiconductor       | 29        | 30     | 0.33%   |
| JMicron Technology          | 27        | 27     | 0.31%   |
| Netac                       | 26        | 26     | 0.3%    |
| Lexar                       | 25        | 26     | 0.28%   |
| Maxtor                      | 24        | 24     | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)

![Drive Model](./All/images/line_chart/drive_model.svg)

| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 202       | 2.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 137       | 1.43%   |
| Kingston SA400S37240G 240GB SSD                       | 90        | 0.94%   |
| Unknown                                               | 77        | 0.81%   |
| Kingston SA400S37480G 480GB SSD                       | 68        | 0.71%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 67        | 0.7%    |
| Seagate ST2000DM008-2FR102 2TB                        | 65        | 0.68%   |
| Kingston SA400S37120G 120GB SSD                       | 64        | 0.67%   |
| Samsung SSD 850 EVO 250GB                             | 63        | 0.66%   |
| Unknown MMC Card  64GB                                | 60        | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB                        | 55        | 0.58%   |
| Samsung SSD 860 EVO 500GB                             | 55        | 0.58%   |
| Samsung SSD 980 1TB                                   | 52        | 0.54%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 51        | 0.53%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                    | 49        | 0.51%   |
| Seagate ST1000DM010-2EP102 1TB                        | 47        | 0.49%   |
| Crucial CT500MX500SSD1 500GB                          | 45        | 0.47%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 42        | 0.44%   |
| Crucial CT240BX500SSD1 240GB                          | 42        | 0.44%   |
| Unknown SD/MMC/MS PRO 16GB                            | 38        | 0.4%    |
| Unknown MMC Card  128GB                               | 38        | 0.4%    |
| Seagate ST500DM002-1BD142 500GB                       | 38        | 0.4%    |
| Samsung SSD 860 EVO 1TB                               | 37        | 0.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 121GB   | 37        | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 36        | 0.38%   |
| Toshiba DT01ACA100 1TB                                | 36        | 0.38%   |
| Intel SSD 660P Series 1024GB                          | 36        | 0.38%   |
| Samsung SSD 870 EVO 1TB                               | 35        | 0.37%   |
| Samsung SSD 850 EVO 500GB                             | 35        | 0.37%   |
| Unknown MMC Card  32GB                                | 34        | 0.36%   |
| Crucial CT1000MX500SSD1 1TB                           | 34        | 0.36%   |
| Toshiba MQ01ABD100 1TB                                | 33        | 0.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 33        | 0.35%   |
| Phison PS5013 E13 NVMe Controller 256GB               | 33        | 0.35%   |
| Toshiba MQ01ABF050 500GB                              | 32        | 0.33%   |
| Seagate ST500LT012-1DG142 500GB                       | 31        | 0.32%   |
| Phison E12 NVMe Controller 1TB                        | 31        | 0.32%   |
| Kingston SV300S37A120G 120GB SSD                      | 31        | 0.32%   |
| Intel SSDPEKNU512GZ 512GB                             | 30        | 0.31%   |
| Toshiba MQ04ABF100 1TB                                | 29        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)

![HDD Vendor](./All/images/line_chart/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 926       | 1163   | 35.09%  |
| WDC                 | 820       | 1003   | 31.07%  |
| Toshiba             | 296       | 344    | 11.22%  |
| Hitachi             | 183       | 201    | 6.93%   |
| HGST                | 139       | 194    | 5.27%   |
| Samsung Electronics | 98        | 115    | 3.71%   |
| Fujitsu             | 44        | 62     | 1.67%   |
| Unknown             | 40        | 40     | 1.52%   |
| Maxtor              | 22        | 22     | 0.83%   |
| Apple               | 22        | 22     | 0.83%   |
| External            | 8         | 11     | 0.3%    |
| SSK                 | 5         | 5      | 0.19%   |
| Hewlett-Packard     | 5         | 11     | 0.19%   |
| USB3.0              | 4         | 4      | 0.15%   |
| DELLBOSS            | 3         | 3      | 0.11%   |
| Maxone              | 2         | 2      | 0.08%   |
| LaCie               | 2         | 2      | 0.08%   |
| Intenso             | 2         | 2      | 0.08%   |
| IBM/Hitachi         | 2         | 2      | 0.08%   |
| HPE                 | 2         | 2      | 0.08%   |
| HGST HTS            | 2         | 2      | 0.08%   |
| Unknown             | 2         | 2      | 0.08%   |
| USB                 | 1         | 1      | 0.04%   |
| SABRENT             | 1         | 1      | 0.04%   |
| QNAP                | 1         | 6      | 0.04%   |
| Magnetic Data       | 1         | 1      | 0.04%   |
| KESU                | 1         | 1      | 0.04%   |
| Initio              | 1         | 1      | 0.04%   |
| IBM-ESXS            | 1         | 1      | 0.04%   |
| ExcelStor           | 1         | 1      | 0.04%   |
| ASMT                | 1         | 1      | 0.04%   |
| ASMedia             | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)

![SSD Vendor](./All/images/line_chart/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 594       | 695    | 20.89%  |
| Kingston            | 361       | 383    | 12.7%   |
| Crucial             | 277       | 291    | 9.74%   |
| SanDisk             | 215       | 229    | 7.56%   |
| WDC                 | 157       | 164    | 5.52%   |
| China               | 104       | 107    | 3.66%   |
| A-DATA Technology   | 100       | 107    | 3.52%   |
| Intel               | 72        | 100    | 2.53%   |
| Micron Technology   | 61        | 103    | 2.15%   |
| SPCC                | 57        | 64     | 2%      |
| PNY                 | 49        | 55     | 1.72%   |
| SK hynix            | 46        | 46     | 1.62%   |
| Apple               | 41        | 41     | 1.44%   |
| Intenso             | 38        | 39     | 1.34%   |
| Toshiba             | 35        | 36     | 1.23%   |
| Patriot             | 35        | 36     | 1.23%   |
| Team                | 30        | 31     | 1.06%   |
| KingSpec            | 30        | 32     | 1.06%   |
| Transcend           | 28        | 29     | 0.98%   |
| Apacer              | 27        | 29     | 0.95%   |
| Hewlett-Packard     | 22        | 24     | 0.77%   |
| GOODRAM             | 20        | 21     | 0.7%    |
| Netac               | 18        | 18     | 0.63%   |
| LITEON              | 17        | 17     | 0.6%    |
| Lexar               | 16        | 17     | 0.56%   |
| OCZ                 | 15        | 15     | 0.53%   |
| Corsair             | 14        | 25     | 0.49%   |
| SABRENT             | 13        | 13     | 0.46%   |
| Gigabyte Technology | 13        | 13     | 0.46%   |
| LITEONIT            | 12        | 12     | 0.42%   |
| Emtec               | 11        | 11     | 0.39%   |
| Verbatim            | 10        | 10     | 0.35%   |
| Unknown             | 9         | 9      | 0.32%   |
| XrayDisk            | 8         | 8      | 0.28%   |
| Smartbuy            | 8         | 8      | 0.28%   |
| FORESEE             | 8         | 8      | 0.28%   |
| Fanxiang            | 8         | 8      | 0.28%   |
| KingFast            | 6         | 6      | 0.21%   |
| KingDian            | 6         | 6      | 0.21%   |
| Dogfish             | 6         | 6      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)

![Drive Kind](./All/images/line_chart/drive_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2667      | 3311   | 34.02%  |
| SSD     | 2444      | 3536   | 31.18%  |
| HDD     | 2229      | 3229   | 28.43%  |
| MMC     | 345       | 390    | 4.4%    |
| Unknown | 154       | 173    | 1.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)

![Drive Connector](./All/images/line_chart/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3780      | 6455   | 52.68%  |
| NVMe | 2653      | 3267   | 36.97%  |
| SAS  | 398       | 527    | 5.55%   |
| MMC  | 345       | 390    | 4.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)

![Drive Size](./All/images/line_chart/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2707      | 3891   | 55.09%  |
| 0.51-1.0   | 1410      | 1724   | 28.69%  |
| 1.01-2.0   | 436       | 572    | 8.87%   |
| 3.01-4.0   | 143       | 236    | 2.91%   |
| 2.01-3.0   | 105       | 143    | 2.14%   |
| 4.01-10.0  | 86        | 146    | 1.75%   |
| 10.01-20.0 | 26        | 52     | 0.53%   |
| 20.01-50.0 | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)

![Space Total](./All/images/line_chart/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1366      | 23.11%  |
| 251-500        | 1268      | 21.45%  |
| 501-1000       | 965       | 16.33%  |
| 1001-2000      | 543       | 9.19%   |
| More than 3000 | 441       | 7.46%   |
| 1-20           | 362       | 6.12%   |
| 51-100         | 320       | 5.41%   |
| Unknown        | 291       | 4.92%   |
| 2001-3000      | 215       | 3.64%   |
| 21-50          | 140       | 2.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)

![Space Used](./All/images/line_chart/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1832      | 30.99%  |
| 21-50          | 1063      | 17.98%  |
| 101-250        | 769       | 13.01%  |
| 51-100         | 656       | 11.1%   |
| 251-500        | 504       | 8.53%   |
| 501-1000       | 341       | 5.77%   |
| Unknown        | 291       | 4.92%   |
| 1001-2000      | 230       | 3.89%   |
| More than 3000 | 151       | 2.55%   |
| 2001-3000      | 73        | 1.23%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)

![Malfunc. Drives](./All/images/line_chart/drive_malfunc.svg)

| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB         | 8         | 8      | 1.45%   |
| Seagate ST500LT012-1DG142 500GB         | 8         | 8      | 1.45%   |
| Seagate ST500DM002-1BD142 500GB         | 8         | 8      | 1.45%   |
| Seagate ST3500418AS 500GB               | 6         | 8      | 1.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 6         | 6      | 1.08%   |
| HGST HTS545050A7E680 500GB              | 6         | 6      | 1.08%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 5         | 5      | 0.9%    |
| Seagate ST9500325AS 500GB               | 5         | 5      | 0.9%    |
| Seagate ST1000DM010-2EP102 1TB          | 5         | 5      | 0.9%    |
| HGST HTS725050A7E630 500GB              | 5         | 5      | 0.9%    |
| HGST HTS721010A9E630 1TB                | 5         | 5      | 0.9%    |
| HGST HTS541010A9E680 1TB                | 5         | 5      | 0.9%    |
| Toshiba MQ01ABD100 1TB                  | 4         | 4      | 0.72%   |
| Toshiba DT01ACA100 1TB                  | 4         | 4      | 0.72%   |
| Seagate ST1000DM003-1ER162 1TB          | 4         | 4      | 0.72%   |
| Samsung Electronics SSD 870 EVO 500GB   | 4         | 4      | 0.72%   |
| Samsung Electronics SSD 870 EVO 1TB     | 4         | 4      | 0.72%   |
| WDC WD5000AAKS-00UU3A0 500GB            | 3         | 3      | 0.54%   |
| WDC WD20EZRX-00D8PB0 2TB                | 3         | 3      | 0.54%   |
| WDC WD20EFRX-68EUZN0 2TB                | 3         | 3      | 0.54%   |
| Toshiba MQ01ABF050 500GB                | 3         | 3      | 0.54%   |
| Seagate ST31000524AS 1TB                | 3         | 3      | 0.54%   |
| Seagate ST2000DM008-2FR102 2TB          | 3         | 4      | 0.54%   |
| SanDisk SSD PLUS 480GB                  | 3         | 3      | 0.54%   |
| SanDisk SSD PLUS 1000GB                 | 3         | 3      | 0.54%   |
| Samsung Electronics HD501LJ 500GB       | 3         | 4      | 0.54%   |
| Neo Forza NFS121SA312-6007000 120GB SSD | 3         | 3      | 0.54%   |
| Kingston SA400S37480G 480GB SSD         | 3         | 4      | 0.54%   |
| Kingston SA400S37120G 120GB SSD         | 3         | 3      | 0.54%   |
| Intel SSDSC2BF180A4L 180GB              | 3         | 3      | 0.54%   |
| Intel SSDSC2BB800G7 800GB               | 3         | 3      | 0.54%   |
| Hitachi HTS543232A7A384 320GB           | 3         | 3      | 0.54%   |
| Hitachi HDP725050GLA360 500GB           | 3         | 3      | 0.54%   |
| WDC WD5000LPCX-24C6HT0 500GB            | 2         | 2      | 0.36%   |
| WDC WD5000AAKX-00ERMA0 500GB            | 2         | 2      | 0.36%   |
| WDC WD5000AAKS-22A7B0 500GB             | 2         | 2      | 0.36%   |
| WDC WD5000AAKS-007AA0 500GB             | 2         | 2      | 0.36%   |
| WDC WD3200BPVT-80ZEST0 320GB            | 2         | 2      | 0.36%   |
| WDC WD30EFRX-68EUZN0 3TB                | 2         | 2      | 0.36%   |
| WDC WD2500AAKX-001CA0 250GB             | 2         | 2      | 0.36%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./All/images/line_chart/drive_malfunc_vendor.svg)

| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 127       | 144    | 23.65%  |
| WDC                   | 117       | 130    | 21.79%  |
| Samsung Electronics   | 50        | 54     | 9.31%   |
| Hitachi               | 37        | 38     | 6.89%   |
| Toshiba               | 35        | 36     | 6.52%   |
| HGST                  | 26        | 26     | 4.84%   |
| Intel                 | 19        | 21     | 3.54%   |
| Kingston              | 17        | 18     | 3.17%   |
| SK hynix              | 11        | 11     | 2.05%   |
| Crucial               | 10        | 10     | 1.86%   |
| SanDisk               | 9         | 9      | 1.68%   |
| Maxtor                | 9         | 9      | 1.68%   |
| A-DATA Technology     | 8         | 9      | 1.49%   |
| Micron Technology     | 6         | 12     | 1.12%   |
| Fujitsu               | 5         | 5      | 0.93%   |
| Corsair               | 5         | 5      | 0.93%   |
| Neo                   | 3         | 3      | 0.56%   |
| LITEON                | 3         | 3      | 0.56%   |
| China                 | 3         | 3      | 0.56%   |
| IBM/Hitachi           | 2         | 2      | 0.37%   |
| ASMedia               | 2         | 2      | 0.37%   |
| Apple                 | 2         | 2      | 0.37%   |
| XrayDisk              | 1         | 1      | 0.19%   |
| Transcend             | 1         | 1      | 0.19%   |
| Silicon Motion        | 1         | 1      | 0.19%   |
| Realtek Semiconductor | 1         | 1      | 0.19%   |
| PNY                   | 1         | 1      | 0.19%   |
| Phison                | 1         | 1      | 0.19%   |
| OWC                   | 1         | 1      | 0.19%   |
| OCZ                   | 1         | 1      | 0.19%   |
| Netac                 | 1         | 1      | 0.19%   |
| Magnetic Data         | 1         | 1      | 0.19%   |
| LITEONIT              | 1         | 1      | 0.19%   |
| Lenovo                | 1         | 1      | 0.19%   |
| LDLC                  | 1         | 1      | 0.19%   |
| Kingmax               | 1         | 1      | 0.19%   |
| KingFast              | 1         | 1      | 0.19%   |
| Kimtigo               | 1         | 1      | 0.19%   |
| JMicron Technology    | 1         | 1      | 0.19%   |
| HS-SSD-C100           | 1         | 1      | 0.19%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./All/images/line_chart/drive_malfunc_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 127       | 144    | 34.23%  |
| WDC                 | 104       | 117    | 28.03%  |
| Hitachi             | 37        | 38     | 9.97%   |
| Toshiba             | 33        | 34     | 8.89%   |
| HGST                | 26        | 26     | 7.01%   |
| Samsung Electronics | 21        | 24     | 5.66%   |
| Maxtor              | 9         | 9      | 2.43%   |
| Fujitsu             | 5         | 5      | 1.35%   |
| IBM/Hitachi         | 2         | 2      | 0.54%   |
| Apple               | 2         | 2      | 0.54%   |
| Magnetic Data       | 1         | 1      | 0.27%   |
| HPE                 | 1         | 1      | 0.27%   |
| ExcelStor           | 1         | 1      | 0.27%   |
| ASMedia             | 1         | 1      | 0.27%   |
| Unknown             | 1         | 1      | 0.27%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./All/images/line_chart/drive_malfunc_kind.svg)

| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 346       | 406    | 67.58%  |
| SSD     | 138       | 149    | 26.95%  |
| NVMe    | 27        | 27     | 5.27%   |
| Unknown | 1         | 1      | 0.2%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)

![Failed Drives](./All/images/line_chart/drive_failed.svg)

| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| Toshiba MK2575GSX 250GB                     | 1         | 1      | 12.5%   |
| Toshiba HDWD110 1TB                         | 1         | 1      | 12.5%   |
| SK hynix PC401 NVMe Solid State Drive 256GB | 1         | 1      | 12.5%   |
| Seagate ST500LT012-1DG142 500GB             | 1         | 1      | 12.5%   |
| Samsung Electronics HM160HC 160GB           | 1         | 1      | 12.5%   |
| Intel SSDSC2BB480G7 480GB                   | 1         | 4      | 12.5%   |
| Hitachi HTS723232A7A364 320GB               | 1         | 1      | 12.5%   |
| HGST HTS541010A9E680 1TB                    | 1         | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)

![Failed Drive Vendor](./All/images/line_chart/drive_failed_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 2      | 25%     |
| SK hynix            | 1         | 1      | 12.5%   |
| Seagate             | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| Intel               | 1         | 4      | 12.5%   |
| Hitachi             | 1         | 1      | 12.5%   |
| HGST                | 1         | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)

![Drive Status](./All/images/line_chart/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3083      | 5118   | 48.22%  |
| Works    | 2801      | 4925   | 43.81%  |
| Malfunc  | 499       | 583    | 7.81%   |
| Failed   | 8         | 11     | 0.13%   |
| Fixed    | 2         | 2      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)

![Storage Vendor](./All/images/line_chart/storage_vendor.svg)

| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 3526      | 44.37%  |
| AMD                                     | 1201      | 15.11%  |
| Samsung Electronics                     | 847       | 10.66%  |
| Sandisk                                 | 438       | 5.51%   |
| Kingston Technology Company             | 227       | 2.86%   |
| SK hynix                                | 198       | 2.49%   |
| Phison Electronics                      | 172       | 2.16%   |
| Micron Technology                       | 164       | 2.06%   |
| Micron/Crucial Technology               | 150       | 1.89%   |
| ASMedia Technology                      | 122       | 1.54%   |
| KIOXIA                                  | 91        | 1.15%   |
| Silicon Motion                          | 84        | 1.06%   |
| Marvell Technology Group                | 80        | 1.01%   |
| Toshiba America Info Systems            | 74        | 0.93%   |
| ADATA Technology                        | 66        | 0.83%   |
| JMicron Technology                      | 63        | 0.79%   |
| Nvidia                                  | 61        | 0.77%   |
| MAXIO Technology (Hangzhou)             | 60        | 0.76%   |
| LSI Logic / Symbios Logic               | 38        | 0.48%   |
| Realtek Semiconductor                   | 37        | 0.47%   |
| Shenzhen Longsys Electronics            | 26        | 0.33%   |
| Union Memory (Shenzhen)                 | 24        | 0.3%    |
| Broadcom / LSI                          | 23        | 0.29%   |
| Solid State Storage Technology          | 18        | 0.23%   |
| Apple                                   | 17        | 0.21%   |
| Seagate Technology                      | 16        | 0.2%    |
| VIA Technologies                        | 12        | 0.15%   |
| INNOGRIT                                | 11        | 0.14%   |
| Adaptec                                 | 11        | 0.14%   |
| Solidigm                                | 10        | 0.13%   |
| Biwin Storage Technology                | 9         | 0.11%   |
| Lite-On Technology                      | 8         | 0.1%    |
| Hewlett-Packard                         | 8         | 0.1%    |
| O2 Micro                                | 7         | 0.09%   |
| Silicon Image                           | 6         | 0.08%   |
| Yangtze Memory Technologies             | 5         | 0.06%   |
| Shenzhen Shichuangyi Electronics        | 5         | 0.06%   |
| Netac Technology                        | 5         | 0.06%   |
| Lenovo                                  | 5         | 0.06%   |
| Shenzhen Unionmemory Information System | 4         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)

![Storage Model](./All/images/line_chart/storage_model.svg)

| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 802       | 8.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 307       | 3.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 236       | 2.62%   |
| Intel Volume Management Device NVMe RAID Controller                            | 230       | 2.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 224       | 2.49%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 219       | 2.43%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 213       | 2.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 200       | 2.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 162       | 1.8%    |
| AMD 500 Series Chipset SATA Controller                                         | 159       | 1.77%   |
| AMD 400 Series Chipset SATA Controller                                         | 152       | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 141       | 1.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 123       | 1.37%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 109       | 1.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 107       | 1.19%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 104       | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 98        | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 96        | 1.07%   |
| Intel Tiger Lake-LP SATA Controller                                            | 93        | 1.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 91        | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 87        | 0.97%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 85        | 0.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 84        | 0.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 83        | 0.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 82        | 0.91%   |
| Intel SATA Controller [RAID mode]                                              | 80        | 0.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 80        | 0.89%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 78        | 0.87%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 72        | 0.8%    |
| Intel Comet Lake SATA AHCI Controller                                          | 71        | 0.79%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 70        | 0.78%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 68        | 0.76%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 65        | 0.72%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 63        | 0.7%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 61        | 0.68%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 61        | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 59        | 0.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 58        | 0.64%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 57        | 0.63%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 56        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)

![Storage Kind](./All/images/line_chart/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3993      | 50.78%  |
| NVMe | 2653      | 33.74%  |
| RAID | 597       | 7.59%   |
| IDE  | 549       | 6.98%   |
| SAS  | 60        | 0.76%   |
| SCSI | 12        | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)

![CPU Vendor](./All/images/line_chart/cpu_vendor.svg)

| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 4172      | 70.58%  |
| AMD           | 1690      | 28.59%  |
| ARM           | 37        | 0.63%   |
| Unknown       | 6         | 0.1%    |
| CentaurHauls  | 3         | 0.05%   |
| sifive,u74-mc | 2         | 0.03%   |
| Qualcomm      | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)

![CPU Model](./All/images/line_chart/cpu_model.svg)

| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 86        | 1.45%   |
| AMD Custom APU 0405                           | 70        | 1.18%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 63        | 1.07%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 55        | 0.93%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 48        | 0.81%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 47        | 0.8%    |
| AMD Ryzen 5 3600 6-Core Processor             | 44        | 0.74%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 43        | 0.73%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 40        | 0.68%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 38        | 0.64%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 37        | 0.63%   |
| Intel 12th Gen Core i7-12700H                 | 36        | 0.61%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 36        | 0.61%   |
| Intel 12th Gen Core i5-1235U                  | 35        | 0.59%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 35        | 0.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 34        | 0.58%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 34        | 0.58%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 31        | 0.52%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 31        | 0.52%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 31        | 0.52%   |
| ARM Processor                                 | 30        | 0.51%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 30        | 0.51%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 29        | 0.49%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 29        | 0.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 28        | 0.47%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 27        | 0.46%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 26        | 0.44%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 26        | 0.44%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 26        | 0.44%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 25        | 0.42%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 25        | 0.42%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 25        | 0.42%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 25        | 0.42%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 24        | 0.41%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 24        | 0.41%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 24        | 0.41%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 24        | 0.41%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 24        | 0.41%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 24        | 0.41%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 24        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)

![CPU Model Family](./All/images/line_chart/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1109      | 18.76%  |
| Other                   | 959       | 16.22%  |
| Intel Core i7           | 871       | 14.74%  |
| AMD Ryzen 5             | 468       | 7.92%   |
| AMD Ryzen 7             | 395       | 6.68%   |
| Intel Core i3           | 310       | 5.24%   |
| Intel Celeron           | 302       | 5.11%   |
| Intel Xeon              | 213       | 3.6%    |
| AMD Ryzen 9             | 155       | 2.62%   |
| Intel Core 2 Duo        | 147       | 2.49%   |
| Intel Pentium           | 101       | 1.71%   |
| AMD Ryzen 3             | 76        | 1.29%   |
| AMD FX                  | 67        | 1.13%   |
| Intel Atom              | 59        | 1%      |
| Intel Pentium Dual-Core | 49        | 0.83%   |
| AMD A8                  | 39        | 0.66%   |
| AMD A6                  | 39        | 0.66%   |
| Intel Core i9           | 36        | 0.61%   |
| AMD Ryzen 7 PRO         | 36        | 0.61%   |
| Intel Core 2 Quad       | 31        | 0.52%   |
| AMD A10                 | 31        | 0.52%   |
| AMD A4                  | 30        | 0.51%   |
| Intel Pentium Silver    | 24        | 0.41%   |
| Intel Core 2            | 22        | 0.37%   |
| AMD E2                  | 19        | 0.32%   |
| AMD Ryzen 5 PRO         | 16        | 0.27%   |
| AMD Athlon II X2        | 16        | 0.27%   |
| AMD Athlon              | 16        | 0.27%   |
| AMD Phenom II X4        | 15        | 0.25%   |
| AMD Athlon II X4        | 15        | 0.25%   |
| AMD E1                  | 14        | 0.24%   |
| Intel Xeon Silver       | 13        | 0.22%   |
| Intel Pentium Dual      | 13        | 0.22%   |
| Intel Genuine           | 13        | 0.22%   |
| AMD E                   | 12        | 0.2%    |
| AMD Phenom II X6        | 11        | 0.19%   |
| AMD Ryzen Threadripper  | 10        | 0.17%   |
| Intel Core m3           | 9         | 0.15%   |
| Intel Pentium 4         | 8         | 0.14%   |
| Intel Celeron Dual-Core | 8         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)

![CPU Cores](./All/images/line_chart/cpu_cores.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1983      | 33.55%  |
| 2       | 1785      | 30.2%   |
| 6       | 699       | 11.83%  |
| 8       | 618       | 10.46%  |
| 12      | 213       | 3.6%    |
| 10      | 171       | 2.89%   |
| 14      | 113       | 1.91%   |
| 16      | 104       | 1.76%   |
| 1       | 95        | 1.61%   |
| 24      | 38        | 0.64%   |
| 3       | 28        | 0.47%   |
| Unknown | 21        | 0.36%   |
| 20      | 9         | 0.15%   |
| 32      | 8         | 0.14%   |
| 28      | 7         | 0.12%   |
| 40      | 4         | 0.07%   |
| 64      | 3         | 0.05%   |
| 36      | 3         | 0.05%   |
| 18      | 3         | 0.05%   |
| 44      | 2         | 0.03%   |
| 5       | 2         | 0.03%   |
| 48      | 1         | 0.02%   |
| 9       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)

![CPU Sockets](./All/images/line_chart/cpu_sockets.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5771      | 97.63%  |
| 2       | 119       | 2.01%   |
| Unknown | 21        | 0.36%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)

![CPU Threads](./All/images/line_chart/cpu_threads.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4201      | 71.07%  |
| 1       | 1687      | 28.54%  |
| Unknown | 21        | 0.36%   |
| 8       | 2         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)

![CPU Op-Modes](./All/images/line_chart/cpu_op_modes.svg)

| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5869      | 99.29%  |
| 32-bit         | 18        | 0.3%    |
| Unknown        | 14        | 0.24%   |
| 64-bit         | 10        | 0.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)

![CPU Microcode](./All/images/line_chart/cpu_microcode.svg)

| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3341      | 56.52%  |
| 0x306a9    | 119       | 2.01%   |
| 0x206a7    | 118       | 2%      |
| 0x306c3    | 110       | 1.86%   |
| 0x0a50000d | 91        | 1.54%   |
| 0x1067a    | 85        | 1.44%   |
| 0x0a50000c | 81        | 1.37%   |
| 0x08108109 | 68        | 1.15%   |
| 0x806c1    | 61        | 1.03%   |
| 0x0a601203 | 57        | 0.96%   |
| 0x906ea    | 50        | 0.85%   |
| 0x406c4    | 49        | 0.83%   |
| 0x0a20120a | 48        | 0.81%   |
| 0x08701021 | 44        | 0.74%   |
| 0x0a404102 | 43        | 0.73%   |
| 0x08600106 | 42        | 0.71%   |
| 0x506e3    | 41        | 0.69%   |
| 0x08608103 | 40        | 0.68%   |
| 0x906e9    | 37        | 0.63%   |
| 0x906a3    | 34        | 0.58%   |
| 0x806ec    | 33        | 0.56%   |
| 0x0800820d | 33        | 0.56%   |
| 0x0600611a | 33        | 0.56%   |
| 0x010000c8 | 31        | 0.52%   |
| 0x406e3    | 30        | 0.51%   |
| 0x706a8    | 29        | 0.49%   |
| 0x306e4    | 29        | 0.49%   |
| 0x08701030 | 29        | 0.49%   |
| 0x806e9    | 28        | 0.47%   |
| 0x40651    | 28        | 0.47%   |
| 0x306d4    | 28        | 0.47%   |
| 0x906a4    | 27        | 0.46%   |
| 0x20655    | 27        | 0.46%   |
| 0x806ea    | 26        | 0.44%   |
| 0x06000852 | 25        | 0.42%   |
| 0x306f2    | 24        | 0.41%   |
| 0x406f1    | 22        | 0.37%   |
| 0x06001119 | 22        | 0.37%   |
| 0x6fd      | 20        | 0.34%   |
| 0x08600104 | 18        | 0.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)

![CPU Microarch](./All/images/line_chart/cpu_microarch.svg)

| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 740       | 12.52%  |
| Unknown           | 615       | 10.4%   |
| Haswell           | 459       | 7.77%   |
| Zen 3             | 385       | 6.51%   |
| IvyBridge         | 368       | 6.23%   |
| Alderlake Hybrid  | 322       | 5.45%   |
| SandyBridge       | 315       | 5.33%   |
| Skylake           | 288       | 4.87%   |
| TigerLake         | 247       | 4.18%   |
| Zen 2             | 241       | 4.08%   |
| Penryn            | 209       | 3.54%   |
| Zen+              | 173       | 2.93%   |
| CometLake         | 145       | 2.45%   |
| Silvermont        | 144       | 2.44%   |
| Broadwell         | 131       | 2.22%   |
| Westmere          | 128       | 2.17%   |
| Icelake           | 120       | 2.03%   |
| Goldmont plus     | 100       | 1.69%   |
| Excavator         | 99        | 1.67%   |
| Piledriver        | 94        | 1.59%   |
| Core              | 93        | 1.57%   |
| Zen               | 81        | 1.37%   |
| K10               | 79        | 1.34%   |
| Nehalem           | 57        | 0.96%   |
| Goldmont          | 40        | 0.68%   |
| Puma              | 34        | 0.58%   |
| K8 Hammer         | 30        | 0.51%   |
| Bobcat            | 26        | 0.44%   |
| Tremont           | 25        | 0.42%   |
| Jaguar            | 22        | 0.37%   |
| Bonnell           | 19        | 0.32%   |
| Steamroller       | 17        | 0.29%   |
| K10 Llano         | 15        | 0.25%   |
| NetBurst          | 12        | 0.2%    |
| Bulldozer         | 11        | 0.19%   |
| P6                | 9         | 0.15%   |
| Gracemont         | 9         | 0.15%   |
| K8 & K10 hybrid   | 8         | 0.14%   |
| Meteorlake Hybrid | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)

![GPU Vendor](./All/images/line_chart/gpu_vendor.svg)

| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3208      | 46.49%  |
| AMD                                          | 1789      | 25.92%  |
| Nvidia                                       | 1775      | 25.72%  |
| ASPEED Technology                            | 63        | 0.91%   |
| Matrox Electronics Systems                   | 58        | 0.84%   |
| Zhaoxin                                      | 2         | 0.03%   |
| VIA Technologies                             | 2         | 0.03%   |
| ATI Technologies                             | 2         | 0.03%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)

![GPU Model](./All/images/line_chart/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 225       | 3.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 201       | 2.84%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 188       | 2.66%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 152       | 2.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 123       | 1.74%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 108       | 1.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 108       | 1.53%   |
| Intel UHD Graphics 620                                                                   | 107       | 1.51%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 106       | 1.5%    |
| Intel HD Graphics 620                                                                    | 103       | 1.46%   |
| Intel HD Graphics 530                                                                    | 99        | 1.4%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 98        | 1.39%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 96        | 1.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 96        | 1.36%   |
| AMD Lucienne                                                                             | 93        | 1.32%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 92        | 1.3%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 85        | 1.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 84        | 1.19%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 84        | 1.19%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 78        | 1.1%    |
| Intel HD Graphics 5500                                                                   | 74        | 1.05%   |
| Intel Core Processor Integrated Graphics Controller                                      | 74        | 1.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 74        | 1.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 72        | 1.02%   |
| Intel HD Graphics 630                                                                    | 70        | 0.99%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 70        | 0.99%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 67        | 0.95%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 65        | 0.92%   |
| AMD Raphael                                                                              | 64        | 0.91%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 63        | 0.89%   |
| AMD Rembrandt [Radeon 680M]                                                              | 63        | 0.89%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 58        | 0.82%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 57        | 0.81%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 56        | 0.79%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 54        | 0.76%   |
| AMD Barcelo                                                                              | 54        | 0.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 50        | 0.71%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 50        | 0.71%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 47        | 0.67%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 46        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)

![GPU Combo](./All/images/line_chart/gpu_combo.svg)

| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 2324      | 39.32%  |
| 1 x AMD                 | 1387      | 23.46%  |
| 1 x Nvidia              | 913       | 15.45%  |
| Intel + Nvidia          | 671       | 11.35%  |
| AMD + Nvidia            | 164       | 2.77%   |
| Intel + AMD             | 123       | 2.08%   |
| 2 x AMD                 | 107       | 1.81%   |
| 1 x ASPEED              | 58        | 0.98%   |
| Other                   | 52        | 0.88%   |
| 1 x Matrox              | 51        | 0.86%   |
| 2 x Intel               | 30        | 0.51%   |
| 2 x Nvidia              | 8         | 0.14%   |
| Nvidia + Matrox         | 6         | 0.1%    |
| 1 x Zhaoxin             | 2         | 0.03%   |
| Nvidia + ASPEED         | 2         | 0.03%   |
| AMD + ASPEED            | 2         | 0.03%   |
| 3 x Nvidia              | 1         | 0.02%   |
| 3 x AMD                 | 1         | 0.02%   |
| 2 x Nvidia + 1 x ASPEED | 1         | 0.02%   |
| 1 x XGI                 | 1         | 0.02%   |
| 1 x VIA                 | 1         | 0.02%   |
| 1 x SiS                 | 1         | 0.02%   |
| Intel + 2 x Nvidia      | 1         | 0.02%   |
| Intel + 2 x AMD         | 1         | 0.02%   |
| AMD + 2 x Nvidia        | 1         | 0.02%   |
| AMD + VIA               | 1         | 0.02%   |
| AMD + Matrox            | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)

![GPU Driver](./All/images/line_chart/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4640      | 78.5%   |
| Proprietary | 967       | 16.36%  |
| Unknown     | 304       | 5.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)

![GPU Memory](./All/images/line_chart/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3818      | 64.59%  |
| 0.01-0.5   | 591       | 10%     |
| 1.01-2.0   | 449       | 7.6%    |
| 0.51-1.0   | 275       | 4.65%   |
| 3.01-4.0   | 263       | 4.45%   |
| 7.01-8.0   | 243       | 4.11%   |
| 8.01-16.0  | 119       | 2.01%   |
| 5.01-6.0   | 103       | 1.74%   |
| 16.01-24.0 | 28        | 0.47%   |
| 2.01-3.0   | 20        | 0.34%   |
| 4.01-5.0   | 2         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)

![Monitor Vendor](./All/images/line_chart/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 784       | 12.42%  |
| AU Optronics            | 678       | 10.74%  |
| BOE                     | 649       | 10.28%  |
| Chimei Innolux          | 552       | 8.74%   |
| LG Display              | 462       | 7.32%   |
| Goldstar                | 362       | 5.73%   |
| Dell                    | 338       | 5.35%   |
| Hewlett-Packard         | 218       | 3.45%   |
| Acer                    | 191       | 3.03%   |
| AOC                     | 152       | 2.41%   |
| Apple                   | 146       | 2.31%   |
| Philips                 | 136       | 2.15%   |
| BenQ                    | 136       | 2.15%   |
| Ancor Communications    | 120       | 1.9%    |
| Lenovo                  | 113       | 1.79%   |
| Sharp                   | 97        | 1.54%   |
| Valve                   | 70        | 1.11%   |
| PANDA                   | 67        | 1.06%   |
| ViewSonic               | 66        | 1.05%   |
| Chi Mei Optoelectronics | 66        | 1.05%   |
| ASUSTek Computer        | 66        | 1.05%   |
| Iiyama                  | 51        | 0.81%   |
| InfoVision              | 50        | 0.79%   |
| CSO                     | 44        | 0.7%    |
| Sony                    | 37        | 0.59%   |
| MSI                     | 29        | 0.46%   |
| Unknown                 | 28        | 0.44%   |
| Eizo                    | 28        | 0.44%   |
| Gigabyte Technology     | 25        | 0.4%    |
| Fujitsu Siemens         | 23        | 0.36%   |
| Panasonic               | 22        | 0.35%   |
| Sceptre Tech            | 18        | 0.29%   |
| LG Electronics          | 18        | 0.29%   |
| RTK                     | 17        | 0.27%   |
| HKC                     | 17        | 0.27%   |
| Vizio                   | 16        | 0.25%   |
| NEC Computers           | 16        | 0.25%   |
| Unknown                 | 16        | 0.25%   |
| Mi                      | 15        | 0.24%   |
| LG Philips              | 14        | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)

![Monitor Model](./All/images/line_chart/mon_model.svg)

| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 70        | 1.08%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 35        | 0.54%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 30        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 27        | 0.42%   |
| BOE LCD Monitor BOE06B3 1920x1080                                        | 23        | 0.35%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 22        | 0.34%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 21        | 0.32%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 20        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 19        | 0.29%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 18        | 0.28%   |
| AOC Q27P2W AOC2702 2560x1440 597x336mm 27.0-inch                         | 18        | 0.28%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 17        | 0.26%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                     | 17        | 0.26%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 17        | 0.26%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 16        | 0.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 16        | 0.25%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 16        | 0.25%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 16        | 0.25%   |
| Unknown                                                                  | 16        | 0.25%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 15        | 0.23%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 15        | 0.23%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 14        | 0.22%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 14        | 0.22%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 14        | 0.22%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 14        | 0.22%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch              | 13        | 0.2%    |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                   | 13        | 0.2%    |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                    | 13        | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.2%    |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch         | 12        | 0.18%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 12        | 0.18%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 12        | 0.18%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 12        | 0.18%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 11        | 0.17%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch             | 11        | 0.17%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 11        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 11        | 0.17%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 11        | 0.17%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 11        | 0.17%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 11        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)

![Monitor Resolution](./All/images/line_chart/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2776      | 46.12%  |
| 1366x768 (WXGA)    | 889       | 14.77%  |
| 3840x2160 (4K)     | 417       | 6.93%   |
| 2560x1440 (QHD)    | 325       | 5.4%    |
| 1920x1200 (WUXGA)  | 203       | 3.37%   |
| 1600x900 (HD+)     | 200       | 3.32%   |
| 1280x1024 (SXGA)   | 146       | 2.43%   |
| 1680x1050 (WSXGA+) | 134       | 2.23%   |
| 1440x900 (WXGA+)   | 110       | 1.83%   |
| 2560x1600          | 108       | 1.79%   |
| 1280x800 (WXGA)    | 90        | 1.5%    |
| 800x1280           | 70        | 1.16%   |
| 3440x1440          | 66        | 1.1%    |
| 2880x1800          | 58        | 0.96%   |
| 2560x1080          | 57        | 0.95%   |
| 3840x1080          | 31        | 0.52%   |
| Unknown            | 30        | 0.5%    |
| 2160x1440          | 28        | 0.47%   |
| 1360x768           | 27        | 0.45%   |
| 3840x2400          | 26        | 0.43%   |
| 2288x1287          | 19        | 0.32%   |
| 1024x768 (XGA)     | 19        | 0.32%   |
| 2256x1504          | 14        | 0.23%   |
| 3200x2000          | 13        | 0.22%   |
| 2736x1824          | 13        | 0.22%   |
| 3072x1920          | 11        | 0.18%   |
| 1024x600           | 11        | 0.18%   |
| 2240x1400          | 10        | 0.17%   |
| 1920x1280          | 10        | 0.17%   |
| 2880x1620          | 9         | 0.15%   |
| 1280x720 (HD)      | 9         | 0.15%   |
| 3456x2160          | 8         | 0.13%   |
| 3000x2000          | 8         | 0.13%   |
| 1920x540           | 8         | 0.13%   |
| 3200x1800 (QHD+)   | 7         | 0.12%   |
| 2520x1680          | 7         | 0.12%   |
| 1600x1200          | 7         | 0.12%   |
| 3840x1600          | 4         | 0.07%   |
| 2048x1152          | 4         | 0.07%   |
| 4480x1440          | 3         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)

![Monitor Diagonal](./All/images/line_chart/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1524      | 24.18%  |
| 13      | 549       | 8.71%   |
| 27      | 530       | 8.41%   |
| 14      | 513       | 8.14%   |
| 24      | 452       | 7.17%   |
| 23      | 410       | 6.5%    |
| 21      | 360       | 5.71%   |
| 17      | 324       | 5.14%   |
| 31      | 177       | 2.81%   |
| Unknown | 150       | 2.38%   |
| 19      | 141       | 2.24%   |
| 16      | 137       | 2.17%   |
| 34      | 100       | 1.59%   |
| 12      | 96        | 1.52%   |
| 11      | 96        | 1.52%   |
| 22      | 86        | 1.36%   |
| 18      | 82        | 1.3%    |
| 20      | 76        | 1.21%   |
| 7       | 71        | 1.13%   |
| 84      | 51        | 0.81%   |
| 40      | 47        | 0.75%   |
| 72      | 39        | 0.62%   |
| 32      | 31        | 0.49%   |
| 54      | 30        | 0.48%   |
| 28      | 24        | 0.38%   |
| 26      | 22        | 0.35%   |
| 48      | 19        | 0.3%    |
| 25      | 19        | 0.3%    |
| 142     | 18        | 0.29%   |
| 10      | 16        | 0.25%   |
| 29      | 14        | 0.22%   |
| 52      | 12        | 0.19%   |
| 46      | 11        | 0.17%   |
| 65      | 7         | 0.11%   |
| 74      | 6         | 0.1%    |
| 33      | 6         | 0.1%    |
| 8       | 6         | 0.1%    |
| 49      | 5         | 0.08%   |
| 39      | 5         | 0.08%   |
| 69      | 4         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)

![Monitor Width](./All/images/line_chart/mon_width.svg)

| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2411      | 38.89%  |
| 501-600        | 1293      | 20.85%  |
| 401-500        | 660       | 10.65%  |
| 201-300        | 502       | 8.1%    |
| 351-400        | 408       | 6.58%   |
| 601-700        | 272       | 4.39%   |
| Unknown        | 150       | 2.42%   |
| 701-800        | 140       | 2.26%   |
| 1501-2000      | 102       | 1.65%   |
| 1001-1500      | 101       | 1.63%   |
| 1-100          | 70        | 1.13%   |
| 801-900        | 53        | 0.85%   |
| More than 2000 | 18        | 0.29%   |
| 901-1000       | 13        | 0.21%   |
| 101-200        | 7         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)

![Aspect Ratio](./All/images/line_chart/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4277      | 75%     |
| 16/10   | 786       | 13.78%  |
| 5/4     | 138       | 2.42%   |
| 21/9    | 125       | 2.19%   |
| Unknown | 110       | 1.93%   |
| 3/2     | 93        | 1.63%   |
| 0.67    | 70        | 1.23%   |
| 4/3     | 47        | 0.82%   |
| 32/9    | 21        | 0.37%   |
| 1.00    | 19        | 0.33%   |
| 6/5     | 9         | 0.16%   |
| 3.40    | 2         | 0.04%   |
| 0.62    | 2         | 0.04%   |
| 0.56    | 2         | 0.04%   |
| 2.65    | 1         | 0.02%   |
| 0.65    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)

![Monitor Area](./All/images/line_chart/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1541      | 24.65%  |
| 201-250        | 1022      | 16.35%  |
| 81-90          | 859       | 13.74%  |
| 301-350        | 551       | 8.81%   |
| 351-500        | 341       | 5.45%   |
| 151-200        | 316       | 5.05%   |
| 121-130        | 225       | 3.6%    |
| 71-80          | 214       | 3.42%   |
| More than 1000 | 186       | 2.98%   |
| 251-300        | 185       | 2.96%   |
| Unknown        | 150       | 2.4%    |
| 141-150        | 138       | 2.21%   |
| 111-120        | 104       | 1.66%   |
| 51-60          | 100       | 1.6%    |
| 501-1000       | 99        | 1.58%   |
| 1-40           | 77        | 1.23%   |
| 61-70          | 70        | 1.12%   |
| 131-140        | 35        | 0.56%   |
| 91-100         | 25        | 0.4%    |
| 41-50          | 14        | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)

![Pixel Density](./All/images/line_chart/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1934      | 31.82%  |
| 121-160       | 1733      | 28.51%  |
| 101-120       | 1417      | 23.31%  |
| 161-240       | 540       | 8.88%   |
| More than 240 | 169       | 2.78%   |
| Unknown       | 150       | 2.47%   |
| 1-50          | 135       | 2.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)

![Multiple Monitors](./All/images/line_chart/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4562      | 77.18%  |
| 2     | 879       | 14.87%  |
| 0     | 344       | 5.82%   |
| 3     | 111       | 1.88%   |
| 4     | 13        | 0.22%   |
| 5     | 2         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)

![Net Controller Vendor](./All/images/line_chart/net_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 3281      | 37.67%  |
| Intel                           | 2906      | 33.36%  |
| Qualcomm Atheros                | 726       | 8.33%   |
| Broadcom                        | 441       | 5.06%   |
| MediaTek                        | 312       | 3.58%   |
| Ralink Technology               | 92        | 1.06%   |
| Broadcom Limited                | 89        | 1.02%   |
| TP-Link                         | 86        | 0.99%   |
| Marvell Technology Group        | 69        | 0.79%   |
| ASIX Electronics                | 57        | 0.65%   |
| Ralink                          | 52        | 0.6%    |
| Nvidia                          | 47        | 0.54%   |
| Xiaomi                          | 33        | 0.38%   |
| Samsung Electronics             | 32        | 0.37%   |
| Qualcomm                        | 31        | 0.36%   |
| NetGear                         | 25        | 0.29%   |
| Sierra Wireless                 | 23        | 0.26%   |
| Qualcomm Atheros Communications | 21        | 0.24%   |
| Aquantia                        | 21        | 0.24%   |
| Microsoft                       | 19        | 0.22%   |
| DisplayLink                     | 19        | 0.22%   |
| Lenovo                          | 17        | 0.2%    |
| Huawei Technologies             | 17        | 0.2%    |
| Dell                            | 17        | 0.2%    |
| ASUSTek Computer                | 17        | 0.2%    |
| Mellanox Technologies           | 16        | 0.18%   |
| Hewlett-Packard                 | 16        | 0.18%   |
| D-Link                          | 16        | 0.18%   |
| D-Link System                   | 13        | 0.15%   |
| OPPO Electronics                | 12        | 0.14%   |
| Google                          | 12        | 0.14%   |
| Microchip Technology            | 11        | 0.13%   |
| JMicron Technology              | 9         | 0.1%    |
| Belkin Components               | 8         | 0.09%   |
| Arduino SA                      | 8         | 0.09%   |
| QinHeng Electronics             | 7         | 0.08%   |
| Motorola PCS                    | 7         | 0.08%   |
| Linksys                         | 7         | 0.08%   |
| IMC Networks                    | 7         | 0.08%   |
| Fibocom                         | 7         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)

![Net Controller Model](./All/images/line_chart/net_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2072      | 20.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 288       | 2.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 250       | 2.43%   |
| Intel Wi-Fi 6 AX200                                               | 224       | 2.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 203       | 1.98%   |
| Intel Wi-Fi 6 AX201                                               | 190       | 1.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 173       | 1.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 167       | 1.63%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 155       | 1.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 152       | 1.48%   |
| Intel Wireless 8265 / 8275                                        | 142       | 1.38%   |
| Intel Wireless 7265                                               | 139       | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 126       | 1.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 125       | 1.22%   |
| Intel Ethernet Controller I225-V                                  | 115       | 1.12%   |
| Intel I211 Gigabit Network Connection                             | 108       | 1.05%   |
| Intel Wireless 8260                                               | 104       | 1.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 103       | 1%      |
| Intel Ethernet Connection I217-LM                                 | 98        | 0.95%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 97        | 0.94%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 94        | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 91        | 0.89%   |
| Intel Wireless 7260                                               | 86        | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 85        | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 80        | 0.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 79        | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 78        | 0.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 77        | 0.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 73        | 0.71%   |
| Intel Ethernet Connection (2) I219-V                              | 70        | 0.68%   |
| Intel Wireless 3165                                               | 65        | 0.63%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 64        | 0.62%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 58        | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 58        | 0.56%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 58        | 0.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 55        | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 52        | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 52        | 0.51%   |
| Intel I350 Gigabit Network Connection                             | 50        | 0.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 50        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)

![Wireless Vendor](./All/images/line_chart/net_wireless_vendor.svg)

| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2197      | 45.29%  |
| Realtek Semiconductor                 | 941       | 19.4%   |
| Qualcomm Atheros                      | 581       | 11.98%  |
| MediaTek                              | 304       | 6.27%   |
| Broadcom                              | 300       | 6.18%   |
| Ralink Technology                     | 92        | 1.9%    |
| TP-Link                               | 83        | 1.71%   |
| Broadcom Limited                      | 62        | 1.28%   |
| Ralink                                | 52        | 1.07%   |
| NetGear                               | 25        | 0.52%   |
| Sierra Wireless                       | 23        | 0.47%   |
| Qualcomm                              | 22        | 0.45%   |
| Qualcomm Atheros Communications       | 21        | 0.43%   |
| Microsoft                             | 18        | 0.37%   |
| D-Link                                | 15        | 0.31%   |
| ASUSTek Computer                      | 15        | 0.31%   |
| Marvell Technology Group              | 13        | 0.27%   |
| Dell                                  | 10        | 0.21%   |
| D-Link System                         | 9         | 0.19%   |
| Belkin Components                     | 8         | 0.16%   |
| Linksys                               | 7         | 0.14%   |
| IMC Networks                          | 7         | 0.14%   |
| Fibocom                               | 7         | 0.14%   |
| Edimax Technology                     | 7         | 0.14%   |
| AVM                                   | 7         | 0.14%   |
| Unknown                               | 5         | 0.1%    |
| Hewlett-Packard                       | 4         | 0.08%   |
| BUFFALO                               | 3         | 0.06%   |
| Wacom                                 | 2         | 0.04%   |
| Micro Star International              | 2         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.04%   |
| ZyDAS                                 | 1         | 0.02%   |
| Xiaomi                                | 1         | 0.02%   |
| Tenda                                 | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Mercucys                              | 1         | 0.02%   |
| Fujitsu Siemens Computers             | 1         | 0.02%   |
| Arduino SA                            | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)

![Wireless Model](./All/images/line_chart/net_wireless_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 224       | 4.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 203       | 4.16%   |
| Intel Wi-Fi 6 AX201                                            | 190       | 3.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 155       | 3.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 152       | 3.12%   |
| Intel Wireless 8265 / 8275                                     | 142       | 2.91%   |
| Intel Wireless 7265                                            | 139       | 2.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 126       | 2.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 125       | 2.56%   |
| Intel Wireless 8260                                            | 104       | 2.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 103       | 2.11%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 97        | 1.99%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 94        | 1.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 91        | 1.87%   |
| Intel Wireless 7260                                            | 86        | 1.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 85        | 1.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 80        | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 79        | 1.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 78        | 1.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 77        | 1.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 73        | 1.5%    |
| Intel Wireless 3165                                            | 65        | 1.33%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 64        | 1.31%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 58        | 1.19%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 58        | 1.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 55        | 1.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 52        | 1.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 50        | 1.03%   |
| Realtek 802.11ac NIC                                           | 49        | 1.01%   |
| Intel Wireless-AC 9260                                         | 47        | 0.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 46        | 0.94%   |
| Ralink MT7601U Wireless Adapter                                | 45        | 0.92%   |
| Broadcom BCM43142 802.11b/g/n                                  | 44        | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 43        | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 42        | 0.86%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 41        | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 39        | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 39        | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 39        | 0.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 35        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)

![Ethernet Vendor](./All/images/line_chart/net_ethernet_vendor.svg)

| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2830      | 54.65%  |
| Intel                            | 1452      | 28.04%  |
| Broadcom                         | 219       | 4.23%   |
| Qualcomm Atheros                 | 211       | 4.07%   |
| ASIX Electronics                 | 57        | 1.1%    |
| Marvell Technology Group         | 56        | 1.08%   |
| Nvidia                           | 47        | 0.91%   |
| Xiaomi                           | 32        | 0.62%   |
| Samsung Electronics              | 32        | 0.62%   |
| Broadcom Limited                 | 27        | 0.52%   |
| Aquantia                         | 21        | 0.41%   |
| DisplayLink                      | 19        | 0.37%   |
| Lenovo                           | 17        | 0.33%   |
| Mellanox Technologies            | 14        | 0.27%   |
| OPPO Electronics                 | 12        | 0.23%   |
| Huawei Technologies              | 12        | 0.23%   |
| Google                           | 12        | 0.23%   |
| Qualcomm                         | 9         | 0.17%   |
| JMicron Technology               | 9         | 0.17%   |
| Microchip Technology             | 8         | 0.15%   |
| MediaTek                         | 7         | 0.14%   |
| American Megatrends              | 7         | 0.14%   |
| VIA Technologies                 | 6         | 0.12%   |
| Hewlett-Packard                  | 6         | 0.12%   |
| Apple                            | 6         | 0.12%   |
| ICS Advent                       | 5         | 0.1%    |
| Motorola PCS                     | 4         | 0.08%   |
| D-Link System                    | 4         | 0.08%   |
| ZTE WCDMA Technologies MSM       | 3         | 0.06%   |
| TP-Link                          | 3         | 0.06%   |
| IBM                              | 3         | 0.06%   |
| Standard Microsystems            | 2         | 0.04%   |
| Silicon Integrated Systems [SiS] | 2         | 0.04%   |
| Novatel Wireless                 | 2         | 0.04%   |
| Insyde Software                  | 2         | 0.04%   |
| Emulex                           | 2         | 0.04%   |
| Dell                             | 2         | 0.04%   |
| ASUSTek Computer                 | 2         | 0.04%   |
| Vimtron Electronics              | 1         | 0.02%   |
| Tehuti Networks                  | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)

![Ethernet Model](./All/images/line_chart/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2072      | 38.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 288       | 5.4%    |
| Realtek RTL8125 2.5GbE Controller                                 | 250       | 4.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 173       | 3.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 167       | 3.13%   |
| Intel Ethernet Controller I225-V                                  | 115       | 2.16%   |
| Intel I211 Gigabit Network Connection                             | 108       | 2.03%   |
| Intel Ethernet Connection I217-LM                                 | 98        | 1.84%   |
| Intel Ethernet Connection (2) I219-V                              | 70        | 1.31%   |
| Intel Ethernet Connection (4) I219-LM                             | 58        | 1.09%   |
| Intel Ethernet Connection (2) I219-LM                             | 52        | 0.98%   |
| Intel I350 Gigabit Network Connection                             | 50        | 0.94%   |
| Intel Ethernet Connection (7) I219-V                              | 48        | 0.9%    |
| ASIX AX88179 Gigabit Ethernet                                     | 48        | 0.9%    |
| Intel Ethernet Connection I219-LM                                 | 46        | 0.86%   |
| Intel Ethernet Connection I217-V                                  | 40        | 0.75%   |
| Intel I210 Gigabit Network Connection                             | 37        | 0.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 37        | 0.69%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 34        | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 32        | 0.6%    |
| Intel 82579V Gigabit Network Connection                           | 32        | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                             | 30        | 0.56%   |
| Intel Ethernet Connection (5) I219-LM                             | 27        | 0.51%   |
| Intel Ethernet Connection (4) I219-V                              | 27        | 0.51%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 27        | 0.51%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 26        | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 25        | 0.47%   |
| Intel Ethernet Controller I226-V                                  | 25        | 0.47%   |
| Intel Ethernet Connection (16) I219-V                             | 25        | 0.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 23        | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 23        | 0.43%   |
| Intel Ethernet Connection (3) I218-LM                             | 23        | 0.43%   |
| Intel Ethernet Connection (14) I219-V                             | 22        | 0.41%   |
| Intel 82577LM Gigabit Network Connection                          | 22        | 0.41%   |
| Intel Ethernet Connection (13) I219-V                             | 20        | 0.38%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 19        | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 18        | 0.34%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 18        | 0.34%   |
| Nvidia MCP61 Ethernet                                             | 17        | 0.32%   |
| Intel 82574L Gigabit Network Connection                           | 17        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)

![Net Controller Kind](./All/images/line_chart/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4845      | 50.88%  |
| WiFi     | 4612      | 48.43%  |
| Modem    | 54        | 0.57%   |
| Unknown  | 12        | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)

![Used Controller](./All/images/line_chart/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3516      | 58.32%  |
| Ethernet | 2512      | 41.67%  |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)

![NICs](./All/images/line_chart/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3065      | 51.85%  |
| 1     | 2527      | 42.75%  |
| 3     | 141       | 2.39%   |
| 0     | 104       | 1.76%   |
| 4     | 45        | 0.76%   |
| 6     | 14        | 0.24%   |
| 5     | 9         | 0.15%   |
| 8     | 3         | 0.05%   |
| 7     | 2         | 0.03%   |
| 11    | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)

![IPv6](./All/images/line_chart/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4132      | 69.9%   |
| Yes  | 1779      | 30.1%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)

![Bluetooth Vendor](./All/images/line_chart/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1933      | 48.99%  |
| Realtek Semiconductor           | 441       | 11.18%  |
| IMC Networks                    | 260       | 6.59%   |
| Qualcomm Atheros Communications | 253       | 6.41%   |
| Cambridge Silicon Radio         | 180       | 4.56%   |
| Apple                           | 144       | 3.65%   |
| Foxconn / Hon Hai               | 127       | 3.22%   |
| Broadcom                        | 118       | 2.99%   |
| MediaTek                        | 96        | 2.43%   |
| Lite-On Technology              | 96        | 2.43%   |
| ASUSTek Computer                | 52        | 1.32%   |
| Realtek                         | 43        | 1.09%   |
| Dell                            | 26        | 0.66%   |
| Toshiba                         | 25        | 0.63%   |
| TP-Link                         | 23        | 0.58%   |
| Ralink                          | 21        | 0.53%   |
| Hewlett-Packard                 | 19        | 0.48%   |
| USI                             | 14        | 0.35%   |
| Marvell Semiconductor           | 12        | 0.3%    |
| Foxconn International           | 10        | 0.25%   |
| Alps Electric                   | 7         | 0.18%   |
| Edimax Technology               | 6         | 0.15%   |
| Belkin Components               | 4         | 0.1%    |
| Unknown                         | 4         | 0.1%    |
| Ralink Technology               | 3         | 0.08%   |
| Dynex                           | 3         | 0.08%   |
| Actions                         | 3         | 0.08%   |
| Taiyo Yuden                     | 2         | 0.05%   |
| Micro Star International        | 2         | 0.05%   |
| Logitech                        | 2         | 0.05%   |
| Integrated System Solution      | 2         | 0.05%   |
| Fujitsu                         | 2         | 0.05%   |
| Conwise Technology              | 2         | 0.05%   |
| Askey Computer                  | 2         | 0.05%   |
| SIN                             | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| Mobile Action Technology        | 1         | 0.03%   |
| Kensington                      | 1         | 0.03%   |
| ISSC                            | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)

![Bluetooth Model](./All/images/line_chart/bt_model.svg)

| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 533       | 13.5%   |
| Intel AX201 Bluetooth                               | 399       | 10.11%  |
| Realtek Bluetooth Radio                             | 348       | 8.82%   |
| Intel Bluetooth Device                              | 260       | 6.59%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 244       | 6.18%   |
| Intel AX200 Bluetooth                               | 218       | 5.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 180       | 4.56%   |
| Qualcomm Atheros  Bluetooth Device                  | 124       | 3.14%   |
| IMC Networks Bluetooth Radio                        | 124       | 3.14%   |
| Intel AX210 Bluetooth                               | 117       | 2.96%   |
| MediaTek Wireless_Device                            | 96        | 2.43%   |
| IMC Networks Wireless_Device                        | 94        | 2.38%   |
| Foxconn / Hon Hai Wireless_Device                   | 74        | 1.87%   |
| Intel Wireless-AC 3168 Bluetooth                    | 73        | 1.85%   |
| Apple Bluetooth Host Controller                     | 73        | 1.85%   |
| Realtek  Bluetooth 4.2 Adapter                      | 64        | 1.62%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 47        | 1.19%   |
| Realtek Bluetooth Radio                             | 43        | 1.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 43        | 1.09%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 39        | 0.99%   |
| Apple Bluetooth USB Host Controller                 | 37        | 0.94%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 36        | 0.91%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 33        | 0.84%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 27        | 0.68%   |
| IMC Networks Bluetooth Device                       | 26        | 0.66%   |
| TP-Link UB500 Adapter                               | 23        | 0.58%   |
| Lite-On Bluetooth Device                            | 22        | 0.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 22        | 0.56%   |
| Ralink RT3290 Bluetooth                             | 21        | 0.53%   |
| Lite-On Wireless_Device                             | 20        | 0.51%   |
| Foxconn / Hon Hai Bluetooth Device                  | 19        | 0.48%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 18        | 0.46%   |
| HP Broadcom 2070 Bluetooth Combo                    | 17        | 0.43%   |
| ASUS ASUS USB-BT500                                 | 15        | 0.38%   |
| USI Bluetooth Device                                | 13        | 0.33%   |
| Broadcom HP Portable Bumble Bee                     | 13        | 0.33%   |
| Realtek RTL8821A Bluetooth                          | 12        | 0.3%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 12        | 0.3%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 11        | 0.28%   |
| Lite-On Bluetooth Radio                             | 11        | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)

![Sound Vendor](./All/images/line_chart/snd_vendor.svg)

| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3954      | 48.28%  |
| AMD                                          | 1920      | 23.45%  |
| Nvidia                                       | 1376      | 16.8%   |
| C-Media Electronics                          | 125       | 1.53%   |
| Logitech                                     | 68        | 0.83%   |
| Creative Labs                                | 46        | 0.56%   |
| ASUSTek Computer                             | 45        | 0.55%   |
| Texas Instruments                            | 41        | 0.5%    |
| GN Netcom                                    | 38        | 0.46%   |
| JMTek                                        | 36        | 0.44%   |
| Generalplus Technology                       | 30        | 0.37%   |
| Micro Star International                     | 29        | 0.35%   |
| Lenovo                                       | 26        | 0.32%   |
| Kingston Technology                          | 24        | 0.29%   |
| Realtek Semiconductor                        | 23        | 0.28%   |
| SteelSeries ApS                              | 19        | 0.23%   |
| Razer USA                                    | 19        | 0.23%   |
| Focusrite-Novation                           | 18        | 0.22%   |
| Creative Technology                          | 18        | 0.22%   |
| Hewlett-Packard                              | 16        | 0.2%    |
| Blue Microphones                             | 14        | 0.17%   |
| Apple                                        | 14        | 0.17%   |
| Corsair                                      | 13        | 0.16%   |
| Plantronics                                  | 10        | 0.12%   |
| Jieli Technology                             | 10        | 0.12%   |
| VIA Technologies                             | 9         | 0.11%   |
| Zoran Co. Personal Media Division (Nogatech) | 7         | 0.09%   |
| Tenx Technology                              | 7         | 0.09%   |
| Sennheiser Communications                    | 7         | 0.09%   |
| RODE Microphones                             | 7         | 0.09%   |
| Sony                                         | 6         | 0.07%   |
| Native Instruments                           | 6         | 0.07%   |
| Dell                                         | 6         | 0.07%   |
| Thesycon Systemsoftware & Consulting         | 5         | 0.06%   |
| M-Audio                                      | 5         | 0.06%   |
| DSEA A/S                                     | 5         | 0.06%   |
| BEHRINGER International                      | 5         | 0.06%   |
| Astro Gaming                                 | 5         | 0.06%   |
| AKAI Professional M.I.                       | 5         | 0.06%   |
| Samson Technologies                          | 4         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)

![Sound Model](./All/images/line_chart/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 768       | 7.76%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 403       | 4.07%   |
| Intel Sunrise Point-LP HD Audio                                            | 349       | 3.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 335       | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 287       | 2.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 286       | 2.89%   |
| AMD Starship/Matisse HD Audio Controller                                   | 257       | 2.6%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 252       | 2.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 246       | 2.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 204       | 2.06%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 196       | 1.98%   |
| Intel Cannon Lake PCH cAVS                                                 | 182       | 1.84%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 158       | 1.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 151       | 1.53%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 151       | 1.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 142       | 1.43%   |
| Nvidia Audio device                                                        | 135       | 1.36%   |
| AMD FCH Azalia Controller                                                  | 135       | 1.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 125       | 1.26%   |
| Intel 200 Series PCH HD Audio                                              | 116       | 1.17%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 114       | 1.15%   |
| Intel Haswell-ULT HD Audio Controller                                      | 107       | 1.08%   |
| Intel 8 Series HD Audio Controller                                         | 107       | 1.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 107       | 1.08%   |
| AMD Kabini HDMI/DP Audio                                                   | 102       | 1.03%   |
| Nvidia GA106 High Definition Audio Controller                              | 99        | 1%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 99        | 1%      |
| Intel Broadwell-U Audio Controller                                         | 99        | 1%      |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 97        | 0.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 95        | 0.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 93        | 0.94%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 93        | 0.94%   |
| Intel Comet Lake PCH-LP cAVS                                               | 92        | 0.93%   |
| Nvidia GA104 High Definition Audio Controller                              | 90        | 0.91%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 89        | 0.9%    |
| Nvidia GP107GL High Definition Audio Controller                            | 88        | 0.89%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 88        | 0.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 85        | 0.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 83        | 0.84%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 81        | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)

![Memory Vendor](./All/images/line_chart/memory_vendor.svg)

| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 924       | 23.22%  |
| SK hynix                                | 647       | 16.26%  |
| Kingston                                | 477       | 11.98%  |
| Micron Technology                       | 398       | 10%     |
| Unknown                                 | 311       | 7.81%   |
| Crucial                                 | 242       | 6.08%   |
| Corsair                                 | 198       | 4.97%   |
| G.Skill                                 | 118       | 2.96%   |
| Unknown                                 | 81        | 2.04%   |
| A-DATA Technology                       | 75        | 1.88%   |
| Ramaxel Technology                      | 57        | 1.43%   |
| Unknown (ABCD)                          | 44        | 1.11%   |
| Nanya Technology                        | 44        | 1.11%   |
| Elpida                                  | 42        | 1.06%   |
| Team                                    | 36        | 0.9%    |
| Transcend                               | 22        | 0.55%   |
| Patriot                                 | 22        | 0.55%   |
| Smart                                   | 21        | 0.53%   |
| AMD                                     | 18        | 0.45%   |
| Apacer                                  | 16        | 0.4%    |
| Kingmax                                 | 10        | 0.25%   |
| Timetec                                 | 6         | 0.15%   |
| Silicon Power                           | 6         | 0.15%   |
| Hewlett-Packard                         | 6         | 0.15%   |
| PNY                                     | 5         | 0.13%   |
| Lexar                                   | 5         | 0.13%   |
| GOODRAM                                 | 5         | 0.13%   |
| CSX                                     | 5         | 0.13%   |
| Unknown (0x0BEC)                        | 4         | 0.1%    |
| Silicon Power Computer & Communications | 4         | 0.1%    |
| Sesame                                  | 4         | 0.1%    |
| Neo Forza                               | 4         | 0.1%    |
| Lexar Co Limited                        | 4         | 0.1%    |
| Kllisre                                 | 4         | 0.1%    |
| ACPI Digital                            | 4         | 0.1%    |
| Unknown (0x7FFF)                        | 3         | 0.08%   |
| Teikon                                  | 3         | 0.08%   |
| Qimonda                                 | 3         | 0.08%   |
| HPE                                     | 3         | 0.08%   |
| ff                                      | 3         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)

![Memory Model](./All/images/line_chart/memory_model.svg)

| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 81        | 1.91%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                  | 35        | 0.83%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 33        | 0.78%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 33        | 0.78%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 32        | 0.75%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 31        | 0.73%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 31        | 0.73%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 25        | 0.59%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 23        | 0.54%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 22        | 0.52%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 21        | 0.5%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 20        | 0.47%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 20        | 0.47%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 19        | 0.45%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 19        | 0.45%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.42%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 18        | 0.42%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 17        | 0.4%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 17        | 0.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 0.4%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 16        | 0.38%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 0.38%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.35%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 15        | 0.35%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 0.33%   |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s            | 14        | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 13        | 0.31%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 13        | 0.31%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 13        | 0.31%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 13        | 0.31%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 13        | 0.31%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 13        | 0.31%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 0.31%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 0.31%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 13        | 0.31%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s              | 12        | 0.28%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 12        | 0.28%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 11        | 0.26%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 11        | 0.26%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 11        | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)

![Memory Kind](./All/images/line_chart/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1650      | 47.95%  |
| DDR3    | 940       | 27.32%  |
| DDR5    | 180       | 5.23%   |
| LPDDR4  | 151       | 4.39%   |
| LPDDR5  | 126       | 3.66%   |
| DDR2    | 122       | 3.55%   |
| LPDDR3  | 92        | 2.67%   |
| Unknown | 88        | 2.56%   |
| SDRAM   | 65        | 1.89%   |
| DDR     | 20        | 0.58%   |
| DRAM    | 7         | 0.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)

![Memory Form Factor](./All/images/line_chart/memory_formfactor.svg)

| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1846      | 53.68%  |
| DIMM            | 1209      | 35.16%  |
| Row Of Chips    | 321       | 9.33%   |
| Unknown         | 49        | 1.42%   |
| Chip            | 8         | 0.23%   |
| RIMM            | 3         | 0.09%   |
| FB-DIMM         | 2         | 0.06%   |
| Proprietary Car | 1         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)

![Memory Size](./All/images/line_chart/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1425      | 37.94%  |
| 4096  | 898       | 23.91%  |
| 16384 | 665       | 17.71%  |
| 2048  | 423       | 11.26%  |
| 32768 | 214       | 5.7%    |
| 1024  | 96        | 2.56%   |
| 512   | 19        | 0.51%   |
| 65536 | 4         | 0.11%   |
| 49152 | 4         | 0.11%   |
| 256   | 4         | 0.11%   |
| 6144  | 2         | 0.05%   |
| 3072  | 1         | 0.03%   |
| 1536  | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)

![Memory Speed](./All/images/line_chart/memory_speed.svg)

| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 747       | 20.16%  |
| 1600    | 604       | 16.3%   |
| 2667    | 449       | 12.12%  |
| 2400    | 246       | 6.64%   |
| 1333    | 240       | 6.48%   |
| 2133    | 170       | 4.59%   |
| 6400    | 119       | 3.21%   |
| 4800    | 108       | 2.91%   |
| 3600    | 108       | 2.91%   |
| 1867    | 85        | 2.29%   |
| 1334    | 72        | 1.94%   |
| 667     | 70        | 1.89%   |
| 4267    | 57        | 1.54%   |
| Unknown | 57        | 1.54%   |
| 800     | 50        | 1.35%   |
| 5600    | 37        | 1%      |
| 1067    | 34        | 0.92%   |
| 3266    | 32        | 0.86%   |
| 2666    | 29        | 0.78%   |
| 1066    | 29        | 0.78%   |
| 3733    | 28        | 0.76%   |
| 1866    | 26        | 0.7%    |
| 2933    | 18        | 0.49%   |
| 6000    | 17        | 0.46%   |
| 3000    | 17        | 0.46%   |
| 4266    | 16        | 0.43%   |
| 4199    | 16        | 0.43%   |
| 533     | 16        | 0.43%   |
| 3800    | 15        | 0.4%    |
| 1800    | 13        | 0.35%   |
| 400     | 12        | 0.32%   |
| 3400    | 11        | 0.3%    |
| 3666    | 10        | 0.27%   |
| 3533    | 10        | 0.27%   |
| 8400    | 9         | 0.24%   |
| 5200    | 9         | 0.24%   |
| 4000    | 8         | 0.22%   |
| 3466    | 8         | 0.22%   |
| 975     | 8         | 0.22%   |
| 2048    | 7         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)

![Printer Vendor](./All/images/line_chart/printer_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 39        | 29.32%  |
| Brother Industries    | 25        | 18.8%   |
| Canon                 | 21        | 15.79%  |
| Seiko Epson           | 19        | 14.29%  |
| Samsung Electronics   | 9         | 6.77%   |
| Dymo-CoStar           | 5         | 3.76%   |
| Pantum                | 3         | 2.26%   |
| Xerox                 | 2         | 1.5%    |
| Prolific Technology   | 2         | 1.5%    |
| Lexmark International | 2         | 1.5%    |
| Zebra                 | 1         | 0.75%   |
| XiaoMi                | 1         | 0.75%   |
| QinHeng Electronics   | 1         | 0.75%   |
| nemonic               | 1         | 0.75%   |
| Kyocera               | 1         | 0.75%   |
| GG IMAGE              | 1         | 0.75%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)

![Printer Model](./All/images/line_chart/printer_model.svg)

| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP LaserJet P1102                    | 4         | 2.99%   |
| Seiko Epson ET-2710 Series           | 3         | 2.24%   |
| HP DeskJet 4100 series               | 3         | 2.24%   |
| Brother Printer                      | 3         | 2.24%   |
| Seiko Epson ET-2600 Series           | 2         | 1.49%   |
| Samsung M2070 Series                 | 2         | 1.49%   |
| Prolific PL2305 Parallel Port        | 2         | 1.49%   |
| HP OfficeJet 6950                    | 2         | 1.49%   |
| HP LaserJet P1005                    | 2         | 1.49%   |
| HP LaserJet M14-M17                  | 2         | 1.49%   |
| HP LaserJet 1320                     | 2         | 1.49%   |
| HP LaserJet 1018                     | 2         | 1.49%   |
| HP DeskJet 3830 series               | 2         | 1.49%   |
| HP DeskJet 2600 series               | 2         | 1.49%   |
| Canon TR4600 series                  | 2         | 1.49%   |
| Brother HL-L2350DW series            | 2         | 1.49%   |
| Brother DCP-L2530DW series           | 2         | 1.49%   |
| Zebra Printer                        | 1         | 0.75%   |
| XiaoMi MIIIW MECH-KBPro              | 1         | 0.75%   |
| Xerox Phaser 6500N                   | 1         | 0.75%   |
| Xerox Phaser 3010                    | 1         | 0.75%   |
| Seiko Epson XP-4100 Series           | 1         | 0.75%   |
| Seiko Epson XP-3100 Series           | 1         | 0.75%   |
| Seiko Epson XP-235 Series            | 1         | 0.75%   |
| Seiko Epson XP-2100 Series           | 1         | 0.75%   |
| Seiko Epson WF-2870 Series           | 1         | 0.75%   |
| Seiko Epson USB2.0 Printer           | 1         | 0.75%   |
| Seiko Epson Printer                  | 1         | 0.75%   |
| Seiko Epson L6160 Series             | 1         | 0.75%   |
| Seiko Epson L300 Series              | 1         | 0.75%   |
| Seiko Epson L132 Series              | 1         | 0.75%   |
| Seiko Epson ET-3760 Series           | 1         | 0.75%   |
| Seiko Epson ET-2820 Series           | 1         | 0.75%   |
| Seiko Epson ET-1810 Series           | 1         | 0.75%   |
| Seiko Epson AL-M310DN                | 1         | 0.75%   |
| Samsung ML-2510 Series               | 1         | 0.75%   |
| Samsung ML-2250 Series               | 1         | 0.75%   |
| Samsung ML-1865                      | 1         | 0.75%   |
| Samsung ML-1640 Series Laser Printer | 1         | 0.75%   |
| Samsung M267x 287x Series            | 1         | 0.75%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)

![Scanner Vendor](./All/images/line_chart/scanner_vendor.svg)

| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 24        | 63.16%  |
| Seiko Epson     | 9         | 23.68%  |
| Plustek         | 2         | 5.26%   |
| Hewlett-Packard | 2         | 5.26%   |
| Mustek Systems  | 1         | 2.63%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)

![Scanner Model](./All/images/line_chart/scanner_model.svg)

| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                 | 5         | 13.16%  |
| Canon CanoScan LiDE 220                                 | 4         | 10.53%  |
| Canon CanoScan LiDE 110                                 | 4         | 10.53%  |
| Seiko Epson GT-X770 [Perfection V500]                   | 3         | 7.89%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 2         | 5.26%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1         | 2.63%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 2.63%   |
| Seiko Epson GT-F700 [Perfection V350]                   | 1         | 2.63%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]            | 1         | 2.63%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]           | 1         | 2.63%   |
| Seiko Epson ES-H300 [GT-2500]                           | 1         | 2.63%   |
| Plustek USB Scanner                                     | 1         | 2.63%   |
| Plustek 1200dpi USB Scanner                             | 1         | 2.63%   |
| Mustek Systems BearPaw 2448 TA Plus                     | 1         | 2.63%   |
| HP ScanJet G4050                                        | 1         | 2.63%   |
| HP Scanjet G2710                                        | 1         | 2.63%   |
| Canon CanoScan N650U/N656U                              | 1         | 2.63%   |
| Canon CanoScan LiDE 90                                  | 1         | 2.63%   |
| Canon CanoScan LiDE 700F                                | 1         | 2.63%   |
| Canon CanoScan LiDE 70                                  | 1         | 2.63%   |
| Canon CanoScan LiDE 500F                                | 1         | 2.63%   |
| Canon CanoScan LIDE 25                                  | 1         | 2.63%   |
| Canon CanoScan LiDE 120                                 | 1         | 2.63%   |
| Canon CanoScan 8800F                                    | 1         | 2.63%   |
| Canon CanoScan 4400F                                    | 1         | 2.63%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)

![Camera Vendor](./All/images/line_chart/camera_vendor.svg)

| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 661       | 19.18%  |
| IMC Networks                           | 312       | 9.05%   |
| Microdia                               | 270       | 7.83%   |
| Realtek Semiconductor                  | 248       | 7.19%   |
| Quanta                                 | 232       | 6.73%   |
| Bison Electronics                      | 215       | 6.24%   |
| Logitech                               | 191       | 5.54%   |
| Sunplus Innovation Technology          | 165       | 4.79%   |
| Apple                                  | 123       | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) | 122       | 3.54%   |
| Luxvisions Innotech Limited            | 105       | 3.05%   |
| Syntek                                 | 101       | 2.93%   |
| Acer                                   | 64        | 1.86%   |
| Sonix Technology                       | 59        | 1.71%   |
| Suyin                                  | 58        | 1.68%   |
| Lite-On Technology                     | 58        | 1.68%   |
| Silicon Motion                         | 39        | 1.13%   |
| Microsoft                              | 34        | 0.99%   |
| Alcor Micro                            | 32        | 0.93%   |
| Samsung Electronics                    | 31        | 0.9%    |
| SunplusIT                              | 20        | 0.58%   |
| Ricoh                                  | 20        | 0.58%   |
| Z-Star Microelectronics                | 18        | 0.52%   |
| ShineTech                              | 18        | 0.52%   |
| Generalplus Technology                 | 18        | 0.52%   |
| Lenovo                                 | 16        | 0.46%   |
| HD 2MP WEBCAM                          | 10        | 0.29%   |
| KYE Systems (Mouse Systems)            | 9         | 0.26%   |
| ARC International                      | 9         | 0.26%   |
| Jieli Technology                       | 8         | 0.23%   |
| ALi                                    | 8         | 0.23%   |
| Y Media                                | 7         | 0.2%    |
| Trust                                  | 7         | 0.2%    |
| Importek                               | 7         | 0.2%    |
| Shenzhen Kingcome Optoelectronic       | 6         | 0.17%   |
| icSpring                               | 6         | 0.17%   |
| DigiTech                               | 6         | 0.17%   |
| Creative Technology                    | 6         | 0.17%   |
| 8SSC21D67422V1SR28902JL                | 6         | 0.17%   |
| MacroSilicon                           | 5         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)

![Camera Model](./All/images/line_chart/camera_model.svg)

| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 163       | 4.7%    |
| Microdia Integrated_Webcam_HD                        | 106       | 3.06%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 102       | 2.94%   |
| Realtek Integrated_Webcam_HD                         | 90        | 2.6%    |
| IMC Networks Integrated Camera                       | 89        | 2.57%   |
| Syntek Integrated Camera                             | 66        | 1.9%    |
| Bison Integrated Camera                              | 65        | 1.87%   |
| Chicony HD WebCam                                    | 45        | 1.3%    |
| Logitech Webcam C270                                 | 42        | 1.21%   |
| Quanta HD User Facing                                | 38        | 1.1%    |
| Chicony HP TrueVision HD Camera                      | 37        | 1.07%   |
| Apple Built-in iSight                                | 34        | 0.98%   |
| Sonix USB2.0 HD UVC WebCam                           | 32        | 0.92%   |
| Quanta Chromebook HD Camera                          | 32        | 0.92%   |
| Bison HD Webcam                                      | 32        | 0.92%   |
| Apple FaceTime HD Camera (Built-in)                  | 32        | 0.92%   |
| Samsung Galaxy series, misc. (MTP mode)              | 31        | 0.89%   |
| Chicony HP HD Camera                                 | 31        | 0.89%   |
| Sunplus Integrated_Webcam_HD                         | 30        | 0.87%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 29        | 0.84%   |
| Apple FaceTime HD Camera                             | 29        | 0.84%   |
| Acer Integrated Camera                               | 29        | 0.84%   |
| Logitech HD Pro Webcam C920                          | 27        | 0.78%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 25        | 0.72%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 24        | 0.69%   |
| Chicony HP Truevision HD                             | 24        | 0.69%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 24        | 0.69%   |
| Quanta HP HD Camera                                  | 23        | 0.66%   |
| Microdia Integrated Webcam                           | 23        | 0.66%   |
| Sonix USB2.0 FHD UVC WebCam                          | 22        | 0.63%   |
| Quanta ACER HD User Facing                           | 22        | 0.63%   |
| Logitech C922 Pro Stream Webcam                      | 21        | 0.61%   |
| Chicony HD User Facing                               | 21        | 0.61%   |
| Quanta HP TrueVision HD Camera                       | 20        | 0.58%   |
| Chicony HP Wide Vision HD Camera                     | 20        | 0.58%   |
| Microdia Webcam Vitade AF                            | 19        | 0.55%   |
| Microdia USB 2.0 Camera                              | 19        | 0.55%   |
| Lite-On Integrated Camera                            | 19        | 0.55%   |
| Chicony USB2.0 Camera                                | 19        | 0.55%   |
| Bison Integrated RGB Camera                          | 19        | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)

![Fingerprint Vendor](./All/images/line_chart/fingerprint_vendor.svg)

| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 169       | 29.44%  |
| Validity Sensors                   | 166       | 28.92%  |
| Shenzhen Goodix Technology         | 116       | 20.21%  |
| Elan Microelectronics              | 40        | 6.97%   |
| AuthenTec                          | 20        | 3.48%   |
| Upek                               | 18        | 3.14%   |
| LighTuning Technology              | 16        | 2.79%   |
| Realtek USB2.0 Finger Print Bridge | 12        | 2.09%   |
| Focal-systems.Corp                 | 6         | 1.05%   |
| STMicroelectronics                 | 4         | 0.7%    |
| Samsung Electronics                | 2         | 0.35%   |
| FocalTech                          | 2         | 0.35%   |
| DigitalPersona                     | 2         | 0.35%   |
| Gingytech                          | 1         | 0.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)

![Fingerprint Model](./All/images/line_chart/fingerprint_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 77        | 13.41%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 40        | 6.97%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 38        | 6.62%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 33        | 5.75%   |
| Elan ELAN:ARM-M4                                                           | 28        | 4.88%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 23        | 4.01%   |
| Shenzhen Goodix Fingerprint Reader                                         | 23        | 4.01%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 17        | 2.96%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 16        | 2.79%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 16        | 2.79%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 16        | 2.79%   |
| Shenzhen Goodix FingerPrint                                                | 16        | 2.79%   |
| Synaptics WBDI                                                             | 15        | 2.61%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 12        | 2.09%   |
| Validity Sensors Synaptics WBDI                                            | 11        | 1.92%   |
| Elan ELAN:Fingerprint                                                      | 11        | 1.92%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 10        | 1.74%   |
| Synaptics UWP WBDI Device                                                  | 10        | 1.74%   |
| Synaptics UWP WBDI                                                         | 10        | 1.74%   |
| Validity Sensors VFS491                                                    | 9         | 1.57%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 1.57%   |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 1.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 8         | 1.39%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.22%   |
| Synaptics  WBDI                                                            | 7         | 1.22%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 1.22%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 6         | 1.05%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 6         | 1.05%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 6         | 1.05%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.05%   |
| Synaptics TouchPad                                                         | 5         | 0.87%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 0.87%   |
| AuthenTec AES2810                                                          | 5         | 0.87%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 0.7%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.7%    |
| STMicroelectronics Fingerprint Reader                                      | 4         | 0.7%    |
| LighTuning Fingerprint Sensor                                              | 4         | 0.7%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 0.7%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.52%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)

![Chipcard Vendor](./All/images/line_chart/chipcard_vendor.svg)

| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 132       | 50.97%  |
| Alcor Micro                       | 74        | 28.57%  |
| Lenovo                            | 9         | 3.47%   |
| Upek                              | 7         | 2.7%    |
| O2 Micro                          | 7         | 2.7%    |
| Advanced Card Systems             | 5         | 1.93%   |
| SCM Microsystems                  | 3         | 1.16%   |
| Realtek Semiconductor             | 3         | 1.16%   |
| Gemalto (was Gemplus)             | 3         | 1.16%   |
| Aladdin Knowledge Systems         | 3         | 1.16%   |
| Chicony Electronics               | 2         | 0.77%   |
| Bit4id                            | 2         | 0.77%   |
| Yubico.com                        | 1         | 0.39%   |
| VASCO Data Security International | 1         | 0.39%   |
| Reiner SCT Kartensysteme          | 1         | 0.39%   |
| OmniKey                           | 1         | 0.39%   |
| NXP Semiconductors                | 1         | 0.39%   |
| Feitian Technologies              | 1         | 0.39%   |
| Cherry                            | 1         | 0.39%   |
| Aladdin R.D.                      | 1         | 0.39%   |
| Aktiv                             | 1         | 0.39%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)

![Chipcard Model](./All/images/line_chart/chipcard_model.svg)

| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 74        | 28.57%  |
| Broadcom 58200                                                               | 40        | 15.44%  |
| Broadcom 5880                                                                | 38        | 14.67%  |
| Broadcom BCM5880 Secure Applications Processor                               | 35        | 13.51%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 16        | 6.18%   |
| Lenovo Integrated Smart Card Reader                                          | 8         | 3.09%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 2.7%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 2.32%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 1.16%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 3         | 1.16%   |
| Aladdin Knowledge Systems Token JC                                           | 3         | 1.16%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 0.77%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.77%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.77%   |
| Advanced Card Systems ACR122U                                                | 2         | 0.77%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.39%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.39%   |
| SCM Microsystems SCR333 SmartCard Reader                                     | 1         | 0.39%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.39%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.39%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.39%   |
| NXP Semiconductors PR533                                                     | 1         | 0.39%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.39%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.39%   |
| Feitian Technologies FIDO CCID KB                                            | 1         | 0.39%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.39%   |
| Bit4id miniLector-s                                                          | 1         | 0.39%   |
| Bit4id miniLector EVO                                                        | 1         | 0.39%   |
| Aladdin R.D. JaCarta                                                         | 1         | 0.39%   |
| Aktiv Rutoken lite                                                           | 1         | 0.39%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.39%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.39%   |
| Advanced Card Systems ACR1252 CL Reader PICC                                 | 1         | 0.39%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)

![Unsupported Devices](./All/images/line_chart/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4150      | 70.21%  |
| 1     | 1391      | 23.53%  |
| 2     | 244       | 4.13%   |
| 3     | 73        | 1.23%   |
| 4     | 37        | 0.63%   |
| 6     | 6         | 0.1%    |
| 5     | 6         | 0.1%    |
| 7     | 2         | 0.03%   |
| 9     | 1         | 0.02%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)

![Unsupported Device Types](./All/images/line_chart/device_unsupported_type.svg)

| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 567       | 25.73%  |
| Graphics card            | 516       | 23.41%  |
| Net/wireless             | 227       | 10.3%   |
| Chipcard                 | 210       | 9.53%   |
| Multimedia controller    | 181       | 8.21%   |
| Communication controller | 130       | 5.9%    |
| Unassigned class         | 87        | 3.95%   |
| Camera                   | 67        | 3.04%   |
| Bluetooth                | 53        | 2.4%    |
| Sound                    | 48        | 2.18%   |
| Storage                  | 27        | 1.23%   |
| Card reader              | 24        | 1.09%   |
| Net/ethernet             | 22        | 1%      |
| Network                  | 12        | 0.54%   |
| Storage/raid             | 7         | 0.32%   |
| Modem                    | 6         | 0.27%   |
| Storage/ide              | 5         | 0.23%   |
| Storage/nvme             | 4         | 0.18%   |
| Flash memory             | 3         | 0.14%   |
| Firewire controller      | 2         | 0.09%   |
| Wireless                 | 1         | 0.05%   |
| Video                    | 1         | 0.05%   |
| Unclassified device      | 1         | 0.05%   |
| Tv card                  | 1         | 0.05%   |
| Storage/ata              | 1         | 0.05%   |
| Dvb card                 | 1         | 0.05%   |

