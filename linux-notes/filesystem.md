WSL / UBUNTU Installed

Linux File Hierarchy Structure also known as the Filesystem Hierarchy Standard(FHS) is the directory structure and content in Unix- related operating systems. The FHS is maintained by the Linux Foundation.

* In FHS, all files and directories appear under the root directory /
* Most directories in UNIX operating systems are used in same way and are not considered to be used by non-Linux platforms.

1. / (Root)
Every Linux system has the root directory represented by a forward slash. It is base point and there is no directory above it. Only the root user has permission to write under this doirectory. 
Now **/root** is the root user's home directory, which is not the same as **/**. If you try to create a file or folder in / as a non root user, there will be a denied error.
2. /bin
This one contains essential, common commands and binary executables e.g ls, CP, dir etc. that system users make use of.
3. /boot
This directory contains all the files needed to boot a Linux system. It contains kernel files loaded during startup Example: initrd.img-2.6.32-24-generic.
4. /dev

