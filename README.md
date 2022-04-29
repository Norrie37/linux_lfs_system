# #1.1 How to Build an LFS System

## Objective

The LFS System will be built using an existing Linux Distribution. The Linux Distro will provide these necessary programs:

* a compiler,
* a linker,
* and shell,

to build the new system.

## Chapter 2 - Create Linux Native Partition and File System

In this phase:

* LFS System will be compiled and installed.

## Chapter 3 - Required Packages and Patches

In this phase:

* Download required packages and patches needed to build the LFS system.
* How to store these packages and patches on the new file system.

## Chapter 4 - Setup Working Environment

In this phase:

* Setup an appropropriate working environment

## Chapter 5 - Install the Initial Tool Chain

* Install the initial toolchain including: ***`binutils`***, ***`gcc`***, and ***`glibc`***
* Use cross-compilation techniques to isolate the new tools from the host system

## Chapter 6 - Cross-Compile Basic Utilities

In this phase:

* Cross-compile basic utilities using the newly-build toolchain

## Chapter 7 - Enter `chroot` environment and Build Additional Tools

In this phase:

* Enter a `chroot` environment and use the previously built tools to build additional tools needed to build and test the final system

## Chapter 8 - Full LFS System is Built

In this phase:

* The Full LFS System is Built

## Chapter 9 - Setup Basic System Configuration

In this phase:

* Basic System Configuration is setup

## Chapter 10 - Setup Kernel and Boot Loader

In this phase:

* Kernel and Boot Loader is setup

## Chapter 11 - Reboot into New LFS System

In this phase:

* Reboot and use the new LFS System

## Package Updates - Required

* Automake-1.16.5
* Bash 5.1.16
* Bc 5.2.2
* Bison-3.8.2
* Coreutils-9.0
* E2fsprogs-1.46.5
* Eudev-3.2.11
* Expat-2.4.6
* File-5.41
* Findutils-4.9.0
* Gawk-5.1.1
* GDBM-1.23
* Glibc-2.35
* Gzip-1.11
* IANA-Etc-20220207
* Inetutils-2.2
* IPRoute2-5.16.0
* LiBCAP-2.63
* Libelf-0.186(from elfutils)
* Libpipeline-1.5.5
* Linux-5.16.9
* Man-DB-2.10.1
* Meson-0.61.1
* Ncurses-6.3
* Openssl-3.0.1
* Python-3.10.2
* Readline-8.1.2
* Shadow-4.11.1
* SysVinit-3.01
* Tcl-8.6.12
* Tzdata-2021e
* Util-Linux-2.37.4
* Vim-8.2.4383
* Zstd-1.5.2

Added:

* binutils-2.38-lto_fix-1.patch
* coreutils-9.0-chmod_fix-1.patch
* file-5.40-upstream_fixes-1.patch
* sysvinit-3.01-consolidated-1.patch
