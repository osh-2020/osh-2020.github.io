# Linux 的安装与使用

## 安装 Linux 操作系统

### 发行版选择

Linux 发行版数量众多（见参考资料1），其中部分较为主流的 Linux 发行版有：

* [Debian](https://www.debian.org/releases/stable/installmanual)
* [Ubuntu](https://www.ubuntu.com/download/desktop/install-ubuntu-desktop)
* [Fedora](https://docs.fedoraproject.org/en-US/Fedora/25/html/Installation_Guide/index.html)
* [Arch Linux](https://wiki.archlinux.org/index.php/Installation_guide_(简体中文))
* [Elementary OS](https://elementary.io/zh_CN/docs/installation#installation)
* [Deepin](https://wiki.deepin.org/?title=原生安装)
* [Gentoo Linux](https://www.gentoo.org/get-started/)

不同的发行版有各自的特点，设计哲学也不尽相同，大家可以选择任意一款自己喜欢的 Linux 发行版。如果是初次接触 Linux，可以选择 Ubuntu，安装相对容易。

### 安装方式

常见的两种安装方式：

* 直接安装在裸金属 (bare metal) 中
* 安装在虚拟机中

如果打算将 Linux 直接安装在裸金属中，且与 Windows/macOS 共存，请自行查找相关资料。这种方案操作相对繁琐，但系统性能和使用体验相对较好。

下面列出了一些常用的虚拟化软件，请大家根据自身情况选择。

* [Virtual Box](https://www.virtualbox.org)（免费软件，GPLv2 协议，支持 macOS, Windows, Linux操作系统）
* [Parallels Desktop](http://www.parallels.com/products/desktop/) （商业软件，支持 macOS）
* [VMware Fusion](http://www.vmware.com/products/fusion.html) （商业软件，支持 macOS）
* [VMware WorkStation](http://www.vmware.com/products/workstation.html) （商业软件，支持 Windows, Linux）
* [VMware Player](http://www.vmware.com/products/player.html) （商业软件，非商业用途免费，支持 Windows, Linux）

### 桌面环境

常见的桌面环境：

* GNOME (Ubuntu, Debian, Fedora 默认桌面环境)
* KDE
* Unity (Ubuntu 17.10 以前版本默认桌面环境)
* XFCE

虽然可以在纯命令行 (command line) 模式下使用 Linux，但由于后续实验需要使用浏览器执行部分操作，因此建议大家安装至少一种桌面环境。

许多面向桌面用户的发行版都会默认安装桌面环境，如安装 Ubuntu Desktop 时，安装程序会默认安装 GNOME 桌面环境。一般而言，这些默认的桌面环境就能够满足我们的需求。

### Vlab 平台

你也可以使用 <https://vlab.ustc.edu.cn> 来进行实验。

### 参考资料

1. [现存的 Linux 发行版](https://upload.wikimedia.org/wikipedia/commons/1/1b/Linux_Distribution_Timeline.svg)
2. [Linux 基本概念和安装指南（Linux 入门公开课）](https://ftp.ustclug.org/course/)


## 使用 Linux 操作系统

这一部分主要目的是让大家了解一些常用的 Linux 命令，减少后续实验遇到的阻力。

Linux 命令行是 Linux 的重要组成部分。它提供了一种命令行界面 (*command-line interface*, abbr. *CLI*) 允许我们与操作系统、应用程序进行交互。相比于图形用户界面(*Graphical User Interface*，abbr. *GUI*)，CLI 更容易使用编程的方法来调用，为程序化控制打下基础。

### 部分常用命令

* 文件/目录相关：ls, cd, pwd, mv, cp, rm, mkdir, cat, touch, find, tar, dd
* 文本处理：echo, grep, sed, wc, tee, sort, vi
* 操作系统相关：shutdown, reboot, w, ps, kill, df

建议大家熟悉以上命令的基本用法，亲自尝试上述命令。具体用法可以参考 Linux 命令大全（见参考资料 1）。

### 参考资料

1. [Linux 命令大全](http://man.linuxde.net)
2. [图形界面 VS 命令行界面（Linux 入门公开课）](https://ftp.ustclug.org/course/)
3. USTCLUG [本学期的 Linux 101 活动讲义](https://101.ustclug.org/)（未完成）与[往年的 Slides](https://github.com/ustclug/Linux101-USTC)