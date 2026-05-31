---
layout: post
title:  "X86pc build support"
date:   2026-05-31 03:57:46 -0500
---
I've added a variant for i686 architecture PC's for running it on QEMU in this release. This is a source only release (e.g. binaries are not included).

The current release can be downloaded by going to this [link](https://www.mediafire.com/file/fxpd66g64vwfbhz/PDK_3.0.4.zip/file).

Please check the README.md file included for more info.

## Packages required to build
### PDT
The PDT version used to build this release has the **same release date** as the PDK.

[PDT_1.7.7z](https://github.com/jonebontus/PDT/raw/refs/heads/main/PDT_1.7.7z)

[PDT_1.7-dependencies.7z](https://www.mediafire.com/file/2tmcl59liktmq2g/PDT_1.7-dependencies.7z/file)

### OpenJDK
[java-17-openjdk-amd64.tar.xz](https://github.com/jonebontus/openjdk/releases/download/openjdk-17/java-17-openjdk-amd64.tar.xz)

### GNU Toolchain
This package includes binutils and gcc for Symbian ARM targets.

[gcc-10.2.0-arm-none-symbianelf-x86_64-pc-linux-gnu.tar.xz](https://github.com/jonebontus/GNU-Toolchain/releases/download/01/gcc-10.2.0-arm-none-symbianelf-x86_64-pc-linux-gnu.tar.xz)

## Also needed to run non hosted target
### QEMU
[source](https://github.com/jonebontus/QEMU/raw/refs/heads/main/qemu-symbian-svp-src.7z)
